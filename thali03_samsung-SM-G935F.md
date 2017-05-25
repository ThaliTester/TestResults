#### Test 11335185108be6d0_thali03_samsung-SM-G935F Logs


```
--------- beginning of system
,05-25 13:49:13.767  3487  4920 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-25 13:49:13.767  3487  4920 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4351, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:49:13.767  3487  4920 D BatteryService: online:4, current avg:163, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:137
05-25 13:49:13.767  3487  3487 D BatteryService: Sending ACTION_BATTERY_CHANGED.
05-25 13:49:13.777  3487  3487 I MotionRecognitionService: Plugged
05-25 13:49:13.777  3487  3487 D MotionRecognitionService:   cableConnection= 1
05-25 13:49:13.777  3487  3487 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:49:13.777  3487  3487 D MotionRecognitionService: skip setTransmitPower. 
--------- beginning of main
05-25 13:49:13.777  3487  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
05-25 13:49:13.777  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
05-25 13:49:13.787  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
05-25 13:49:13.787  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
05-25 13:49:13.787  3949  3949 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
05-25 13:49:13.787  3949  3949 D PowerUI.Notification: There is no change about charging status, so return!
05-25 13:49:13.797  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
05-25 13:49:13.797  4952  4952 D CommonServiceConfiguration: getStringValueSetting
05-25 13:49:13.807  4907  4907 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-25 13:49:13.807  4907  5263 D HeadsetStateMachine: Disconnected process message: 10, size: 0
05-25 13:49:13.807  4952  4952 D BatteryMonitor: new battery level: 100
05-25 13:49:13.817  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
05-25 13:49:14.247  9834  9834 I FIPS_bssl: FIPS approved mode (1) | 9834 | app_process
05-25 13:49:14.257  9834  9834 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
05-25 13:49:14.257  9834  9834 D AndroidRuntime: CheckJNI is OFF
05-25 13:49:14.257  9834  9834 D AndroidRuntime: readGMSProperty: start
05-25 13:49:14.257  9834  9834 D AndroidRuntime: readGMSProperty: already setted!!
05-25 13:49:14.257  9834  9834 D AndroidRuntime: propertySet: couldn't set property (it is from app)
05-25 13:49:14.257  9834  9834 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
05-25 13:49:14.257  9834  9834 D AndroidRuntime: readGMSProperty: end
05-25 13:49:14.257  9834  9834 D AndroidRuntime: addProductProperty: start
05-25 13:49:14.277  9834  9834 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
05-25 13:49:14.297  9834  9834 I Radio-JNI: register_android_hardware_Radio DONE
05-25 13:49:14.307  9834  9834 E AffinityControl: AffinityControl: registerfunction enter
05-25 13:49:14.307  9834  9834 D AndroidRuntime: Calling main entry com.android.commands.am.Am
05-25 13:49:14.337  3487  3505 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
05-25 13:49:14.337  3487  3505 W ResourcesManager: getTopLevelResources: /data/app/com.thaliproject.thalitest-1/base.apk / 1.0 running in null rsrc of package com.thaliproject.thalitest
05-25 13:49:14.367  3487  3505 D ResourcesManager: For user 0 new overlays fetched Null
05-25 13:49:14.377  3487  3505 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
05-25 13:49:14.377  3487  3505 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.thaliproject.thalitest)
05-25 13:49:14.377  3487  3505 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3487  pkgName : ACTIVITY_RESUME_BOOSTER@7
05-25 13:49:14.377  3487  3505 D ActivityManager: mDVFSHelper.acquire()
05-25 13:49:14.377  3487  3505 V WindowManager: addAppToken: AppWindowToken{d0222c277 token=Token{6b09c76 ActivityRecord{50bb311 u0 com.thaliproject.thalitest/.MainActivity t20}}} to stack=2 task=20 at 0
05-25 13:49:14.407  3487  3600 I InjectionManager: Inside getClassLibPath caller 
05-25 13:49:14.407  3487  3505 D InputDispatcher: Focused application set to: xxxx
05-25 13:49:14.407  3487  3600 D SecWifiDisplayUtil: Metadata value : SecSettings2
05-25 13:49:14.407  3487  3600 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{4b9896f V.E...... R.....ID 0,0-0,0}
05-25 13:49:14.407  3487  3505 D InputDispatcher: Focus left window: 6377
05-25 13:49:14.407  3487  3572 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{2c5a17f u0 d0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}
05-25 13:49:14.407  9834  9834 D AndroidRuntime: Shutting down VM
05-25 13:49:14.407  3487  3600 D ISSUE_DEBUG: InputChannelName : a52d75a Starting com.thaliproject.thalitest
05-25 13:49:14.407  3949  3949 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=8000 newVal=8600 diff=600
05-25 13:49:14.417  9844  9844 E Zygote  : v2
05-25 13:49:14.417  9844  9844 I libpersona: KNOX_SDCARD checking this for 10078
05-25 13:49:14.417  9844  9844 I libpersona: KNOX_SDCARD not a persona
05-25 13:49:14.427  9844  9844 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
05-25 13:49:14.427  3487  4065 I ActivityManager: Start proc 9844:com.thaliproject.thalitest/u0a78 for activity com.thaliproject.thalitest/.MainActivity
05-25 13:49:14.427  9844  9844 E Zygote  : accessInfo : 0
05-25 13:49:14.427  9844  9844 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.thaliproject.thalitest 
05-25 13:49:14.427  3011  3011 I SurfaceFlinger: id=20 createSurf (1x1),1 flag=404, uhalitest
05-25 13:49:14.437  9844  9844 D TimaKeyStoreProvider: TimaSignature is unavailable
05-25 13:49:14.437  9844  9844 D ActivityThread: Added TimaKeyStore provider
05-25 13:49:14.447  3487  3600 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3487 uid:1000
05-25 13:49:14.447  3487  3600 D PointerIcon: setMouseCustomIcon IconType is same.101
05-25 13:49:14.447  3487  3857 D NetworkPolicy: isUidForegroundLocked: 10078, mScreenOn: true, uidstate: -1, mProxSensorScreenOff: false
05-25 13:49:14.447  3487  3600 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
05-25 13:49:14.447  3487  4196 V WindowOrientationListener: setCurrentAppOrientation :-1
05-25 13:49:14.447  3487  4196 V WindowOrientationListener: OrientationSensorJudge.getProposedRotation, Rotation: -1
05-25 13:49:14.447  3487  4196 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
05-25 13:49:14.447  3487  4196 V WindowOrientationListener: OrientationSensorJudge.getProposedRotation, Rotation: -1
05-25 13:49:14.447  3487  4196 D ActivityManager:  Launching com.thaliproject.thalitest, updated priority
05-25 13:49:14.447  6969  6969 V ActivityThread: updateVisibility : ActivityRecord{f21307 token=android.os.BinderProxy@75a8ff1 {com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity}} show : false
05-25 13:49:14.447  4326  4326 D Launcher.HomeView: onStop
05-25 13:49:14.447  4326  4326 D capture : ----destroy
05-25 13:49:14.457  3487  3487 D GameManagerService: NotifyRunnable. pkg: com.thaliproject.thalitest, type: 4, isMinimized: false, isTunableApp: false
05-25 13:49:14.457  4326  4326 V ActivityThread: updateVisibility : ActivityRecord{369b23e token=android.os.BinderProxy@91b7254 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
05-25 13:49:14.457  9844  9844 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
05-25 13:49:14.467  9844  9844 D RelationGraph: garbageCollect()
05-25 13:49:14.467  3011  4607 D libEGL  : eglTerminate EGLDisplay = 0x7f89ffee78
05-25 13:49:14.467  3487  3570 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.thaliproject.thalitest
05-25 13:49:14.467  3011  4607 D libEGL  : eglTerminate EGLDisplay = 0x7f89ffee78
05-25 13:49:14.467  9844  9844 W ResourcesManager: getTopLevelResources: /data/app/com.thaliproject.thalitest-1/base.apk / 1.0 running in com.thaliproject.thalitest rsrc of package com.thaliproject.thalitest
05-25 13:49:14.467  9844  9844 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
05-25 13:49:14.467  3487  3570 E MARsPolicyManager: getPackageInfo package com.test.thalitest not installed!
05-25 13:49:14.467  3011  3024 D libEGL  : eglTerminate EGLDisplay = 0x7f9b67ee78
05-25 13:49:14.467  3487  3980 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-25 13:49:14.467  3011  3024 D libEGL  : eglTerminate EGLDisplay = 0x7f9b67ee78
05-25 13:49:14.467  3487  3570 E MARsPolicyManager: getPackageInfo package com.rockwellautomation.thalitest not installed!
05-25 13:49:14.467  3487  6263 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
05-25 13:49:14.467  3487  6263 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
05-25 13:49:14.477  9844  9844 D ResourcesManager: For user 0 new overlays fetched Null
05-25 13:49:14.477  3011  3011 D libEGL  : eglInitialize EGLDisplay = 0x7fd4d61338
05-25 13:49:14.477  4326  4326 D Launcher: onTrimMemory. Level: 20
05-25 13:49:14.477  9844  9844 I InjectionManager: Inside getClassLibPath caller 
05-25 13:49:14.477  3487  6263 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
05-25 13:49:14.477  3487  3600 V WindowStateAnimator: Finishing drawing window Window{a52d75a u0 d0 Starting com.thaliproject.thalitest}: mDrawState=DRAW_PENDING
05-25 13:49:14.477  3487  6263 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
05-25 13:49:14.487  3487  3572 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{a52d75a u0 d0 Starting com.thaliproject.thalitest}
05-25 13:49:14.487  9844  9844 D InjectionManager: InjectionManager
05-25 13:49:14.487  9844  9844 D InjectionManager: fillFeatureStoreMap com.thaliproject.thalitest
05-25 13:49:14.487  3487  6263 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
05-25 13:49:14.487  9844  9844 I InjectionManager: Constructor com.thaliproject.thalitest, Feature store :{}
05-25 13:49:14.487  9844  9844 I InjectionManager: featureStore :{}
05-25 13:49:14.487  3487  6263 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
05-25 13:49:14.487  3487  6263 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
05-25 13:49:14.497  9844  9844 W ResourcesManager: getTopLevelResources: /data/app/com.thaliproject.thalitest-1/base.apk / 1.0 running in com.thaliproject.thalitest rsrc of package com.thaliproject.thalitest
05-25 13:49:14.497  9844  9844 D RelationGraph: garbageCollect()
05-25 13:49:14.497  9844  9844 W ResourcesManager: getTopLevelResources: /data/app/com.thaliproject.thalitest-1/base.apk / 1.0 running in com.thaliproject.thalitest rsrc of package com.thaliproject.thalitest
05-25 13:49:14.507  3011  3079 D libEGL  : eglTerminate EGLDisplay = 0x7f943fee78
05-25 13:49:14.507  3011  3079 D libEGL  : eglTerminate EGLDisplay = 0x7f943fee78
05-25 13:49:14.517  9844  9844 I CordovaLog: Changing log level to DEBUG(3)
05-25 13:49:14.517  9844  9844 I CordovaActivity: Apache Cordova native platform version 6.0.0 is starting
05-25 13:49:14.517  9844  9844 D CordovaActivity: CordovaActivity.onCreate()
05-25 13:49:14.527  3487  3498 I art     : Background partial concurrent mark sweep GC freed 61335(4MB) AllocSpace objects, 52(1040KB) LOS objects, 31% free, 34MB/50MB, paused 1.232ms total 132.495ms
05-25 13:49:14.527  9844  9844 I WebViewFactory: Loading com.google.android.webview version 50.0.2661.86 (code 266108650)
05-25 13:49:14.567  9844  9844 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.thaliproject.thalitest rsrc of package com.google.android.webview
05-25 13:49:14.567  9844  9844 D ResourcesManager: For user 0 new overlays fetched Null
05-25 13:49:14.567  9844  9844 I InjectionManager: Inside getClassLibPath caller 
05-25 13:49:14.577  9844  9844 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
05-25 13:49:14.617  9844  9844 I cr_LibraryLoader: Time to load native libraries: 25 ms (timestamps 5178-5203)
05-25 13:49:14.617  9844  9844 I cr_LibraryLoader: Expected native library version number "50.0.2661.86", actual native library version number "50.0.2661.86"
,05-25 13:49:14.637  9844  9859 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.thaliproject.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,05-25 13:49:14.657  9844  9844 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {5359fd5}
05-25 13:49:14.657  9844  9844 I cr_LibraryLoader: Expected native library version number "50.0.2661.86", actual native library version number "50.0.2661.86"
,05-25 13:49:14.677  9844  9844 I chromium: [INFO:library_loader_hooks.cc(143)] Chromium logging enabled: level = 0, default verbosity = 0
,05-25 13:49:14.707  9844  9844 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,05-25 13:49:14.717  3487  3882 D MdnieScenarioControlService:  packageName : com.thaliproject.thalitest    className : com.thaliproject.thalitest.MainActivity
,05-25 13:49:14.787  9844  9844 D libEGL  : eglInitialize EGLDisplay = 0xfffce1f4
,05-25 13:49:14.817  3487  3882 I MdnieScenarioControlService: mGameModeLauncher : false
,05-25 13:49:14.827  3487  3882 I MdnieScenarioControlService: setUIMode
,05-25 13:49:14.827  3487  4065 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10078
,05-25 13:49:14.827  3487  4065 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29757 com.android.server.am.ActivityManagerService.registerReceiver:22622 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,05-25 13:49:14.857  3487  3857 D NetworkPolicy: isUidForegroundLocked: 10021, mScreenOn: true, uidstate: 2, mProxSensorScreenOff: false
,05-25 13:49:14.867  3011  3022 I SurfaceFlinger: id=9 Removed MauncherAct (4/17)
05-25 13:49:14.867  3011  3079 I SurfaceFlinger: id=9 Removed MauncherAct (-2/17)
,05-25 13:49:14.867  3011  4607 I SurfaceFlinger: id=17 Removed YUIInstallC (4/16)
05-25 13:49:14.867  3011  3024 I SurfaceFlinger: id=16 Removed YUIInstallC (4/15)
05-25 13:49:14.867  3011  3022 I SurfaceFlinger: id=19 Removed VSBConnecti (4/14)
05-25 13:49:14.867  3011  3022 I SurfaceFlinger: id=17 Removed YUIInstallC (-2/14)
05-25 13:49:14.867  3011  3024 I SurfaceFlinger: id=16 Removed YUIInstallC (-2/14)
05-25 13:49:14.867  3011  3079 I SurfaceFlinger: id=19 Removed VSBConnecti (-2/14)
05-25 13:49:14.867  3011  4455 I SurfaceFlinger: id=18 Removed VSBConnecti (5/13)
05-25 13:49:14.867  3011  3022 I SurfaceFlinger: id=18 Removed VSBConnecti (-2/13)
,05-25 13:49:14.867  3949  3949 D ImageWallpaper: onVisibilityChanged:false
,05-25 13:49:14.877  3949  3949 D ImageWallpaper: drawFrame:false rotation:0 mLastRotation:0
05-25 13:49:14.877  3949  3949 D ImageWallpaper: drawFrame:[frame.width()]2240[frame.height()]2560
05-25 13:49:14.877  3949  3949 D ImageWallpaper: Suppressed drawFrame since redraw is not needed and offsets have not changed.
,05-25 13:49:14.877  9844  9844 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10078, CallingPid : 9844
,05-25 13:49:14.877  3487  3854 D ConnectivityService: listenForNetwork for Listen from uid/pid:10078/9844 for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:49:14.877  3487  3869 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
05-25 13:49:14.877  3487  3869 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -22]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,05-25 13:49:14.877  3487  3869 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,05-25 13:49:14.877  3011  3011 D libEGL  : eglTerminate EGLDisplay = 0x7fd4d61458
,05-25 13:49:14.877  3011  3011 D libEGL  : eglTerminate EGLDisplay = 0x7fd4d61458
05-25 13:49:14.877  3011  3011 D libEGL  : eglTerminate EGLDisplay = 0x7fd4d61458
05-25 13:49:14.877  3011  3011 D libEGL  : eglTerminate EGLDisplay = 0x7fd4d61458
,05-25 13:49:14.877  3487  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-25 13:49:14.887  3487  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,05-25 13:49:14.887  3487  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-25 13:49:14.887  9844  9844 D cr_Ime  : [InputMethodManagerWrapper.java:30] Constructor
,05-25 13:49:14.887  3487  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-25 13:49:14.887  3487  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,05-25 13:49:14.887  3487  3869 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:49:14.897  9844  9844 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,05-25 13:49:14.897  9844  9844 D cr_Ime  : [InputMethodManagerWrapper.java:59] isActive: false
,05-25 13:49:14.917  9844  9844 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,05-25 13:49:14.917  9844  9844 D PluginManager: init()
,05-25 13:49:14.927  9844  9844 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,05-25 13:49:14.927  9844  9844 I cr_Ime  : ImeThread is not enabled.
,05-25 13:49:14.937  9844  9844 D Activity: performCreate Call Injection manager
,05-25 13:49:14.937  9844  9844 D CordovaActivity: Started the activity.
05-25 13:49:14.937  9844  9844 I InjectionManager: dispatchOnViewCreated > Target : com.thaliproject.thalitest.MainActivity isFragment :false
05-25 13:49:14.937  9844  9844 D CordovaActivity: Resumed the activity.
,05-25 13:49:14.937  9844  9844 D SecWifiDisplayUtil: Metadata value : SecSettings2
,05-25 13:49:14.947  9844  9844 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{e7f5f31 I.E...... R.....ID 0,0-0,0}
,05-25 13:49:14.947  9844  9894 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,05-25 13:49:14.947  3487  4417 D ISSUE_DEBUG: InputChannelName : 4123712 com.thaliproject.thalitest/com.thaliproject.thalitest.MainActivity
,05-25 13:49:14.957  3487  3980 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
05-25 13:49:14.957  3487  3980 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
05-25 13:49:14.957  3487  3487 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,05-25 13:49:14.957  3487  3487 I KnoxTimeoutHandler: Shared devices show user statefalse
05-25 13:49:14.957  3487  6263 D SSRM:n  : SIOP:: AP = 320, PST = 315 (W:10), CP = 265, CUR = 163, LCD = 30
05-25 13:49:14.957  9844  9859 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.thaliproject.thalitest/shared_prefs/com.thaliproject.thalitest_preferences.xml.bak
05-25 13:49:14.957  3487  6263 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
05-25 13:49:14.957  9844  9844 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10078, CallingPid : 9844
05-25 13:49:14.957  3487  3506 D ConnectivityService: listenForNetwork for Listen from uid/pid:10078/9844 for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:14.967  3487  3869 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
05-25 13:49:14.967  3487  3869 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -22]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
05-25 13:49:14.967  3487  3857 D NetworkPolicy: isUidForegroundLocked: 10021, mScreenOn: true, uidstate: 6, mProxSensorScreenOff: false
05-25 13:49:14.967  3487  3869 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
05-25 13:49:14.967  3487  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
05-25 13:49:14.977  3487  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
05-25 13:49:14.977  3487  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
05-25 13:49:14.977  9844  9844 D SecWifiDisplayUtil: Metadata value : SecSettings2
05-25 13:49:14.977  3487  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
05-25 13:49:14.977  3487  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
05-25 13:49:14.987  3487  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
05-25 13:49:14.987  3011  3011 I SurfaceFlinger: id=21 createSurf (1x1),1 flag=404, NainActivit
05-25 13:49:14.987  3487  3869 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:49:14.997  3487  4671 D InputDispatcher: Focus entered window: 9844
,05-25 13:49:14.997  3487  3600 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3487 uid:1000
05-25 13:49:14.997  3487  3600 D PointerIcon: setMouseCustomIcon IconType is same.101
05-25 13:49:14.997  9844  9894 D libEGL  : eglInitialize EGLDisplay = 0xdc5bf7c4
05-25 13:49:14.997  9844  9894 I OpenGLRenderer: Initialized EGL, version 1.4
,05-25 13:49:15.007  9844  9894 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,05-25 13:49:15.017  9844  9898 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
05-25 13:49:15.017  9844  9898 D libEGL  : eglInitialize EGLDisplay = 0xda77f3e4
05-25 13:49:15.017  9844  9844 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,05-25 13:49:15.027  9844  9898 D libGLESv2: DTS_GLAPI : DTS is not allowed for Package : com.thaliproject.thalitest
,05-25 13:49:15.047  3487  4947 V WindowStateAnimator: Finishing drawing window Window{4123712 u0 d0 com.thaliproject.thalitest/com.thaliproject.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,05-25 13:49:15.047  9844  9844 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
,05-25 13:49:15.047  3487  4065 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,05-25 13:49:15.057  3487  3600 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,05-25 13:49:15.057  3487  3487 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
05-25 13:49:15.057  3487  3600 I ActivityManager: Displayed com.thaliproject.thalitest/.MainActivity: +644ms
05-25 13:49:15.057  3487  3600 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3487  tag : ACTIVITY_RESUME_BOOSTER@7
,05-25 13:49:15.057  3487  3487 I KnoxTimeoutHandler: SD activityfalse
05-25 13:49:15.057  3487  3600 D ActivityManager: mDVFSHelper.release()
05-25 13:49:15.057  3487  3600 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{50bb311 u0 com.thaliproject.thalitest/.MainActivity t20} time:175644
05-25 13:49:15.057  3487  3570 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3487  pkgName : ACTIVITY_RESUME_BOOSTER@13
05-25 13:49:15.057  3487  3600 D ViewRootImpl: #3 mView = null
,05-25 13:49:15.067  3011  3011 D libEGL  : eglInitialize EGLDisplay = 0x7fd4d61338
,05-25 13:49:15.067  4862  4862 D SamsungIME: IMPL finishInput
,05-25 13:49:15.067  4862  4862 D SamsungIME: SwiftKeyWrapper writeDBdataToFileOnFinishInput
05-25 13:49:15.067  4862  4862 D SamsungIME: saveAndClear +
05-25 13:49:15.067  4862  4862 D SamsungIME: saveAndClear -
,05-25 13:49:15.077  3487  3854 V WindowStateAnimator: Finishing drawing window Window{4123712 u0 d0 com.thaliproject.thalitest/com.thaliproject.thalitest.MainActivity}: mDrawState=HAS_DRAWN
,05-25 13:49:15.077  9844  9844 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
05-25 13:49:15.077  9844  9844 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@e7cda60 time:175661
,05-25 13:49:15.077  6377  6377 V ActivityThread: updateVisibility : ActivityRecord{a36d5f8 token=android.os.BinderProxy@6c93a9a {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
,05-25 13:49:15.077  9844  9844 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9844
,05-25 13:49:15.077  9844  9844 D cr_Ime  : [InputMethodManagerWrapper.java:59] isActive: true
,05-25 13:49:15.077  9844  9844 D cr_Ime  : [InputMethodManagerWrapper.java:68] hideSoftInputFromWindow
,05-25 13:49:15.077  3011  3011 D libEGL  : eglInitialize EGLDisplay = 0x7fd4d61338
,05-25 13:49:15.117  3011  3011 D libEGL  : eglInitialize EGLDisplay = 0x7fd4d61338
,05-25 13:49:15.137  9844  9844 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,05-25 13:49:15.247  3011  4455 I SurfaceFlinger: id=20 Removed uhalitest (7/13)
,05-25 13:49:15.247  3011  3024 I SurfaceFlinger: id=20 Removed uhalitest (-2/13)
,05-25 13:49:15.257  9844  9907 D jxcore_app_log: JniHelper::setJavaVM(0xf49b4000), pthread_self() = -706627280
,05-25 13:49:15.257  9844  9907 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
05-25 13:49:15.257  9844  9907 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
05-25 13:49:15.257  9844  9907 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
05-25 13:49:15.257  9844  9907 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
05-25 13:49:15.257  9844  9907 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
05-25 13:49:15.257  9844  9907 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38e3f08 added. We now have 1 listener(s)
,05-25 13:49:15.257  9844  9907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38e3f08 added. We now have 1 listener(s)
05-25 13:49:15.257  9844  9907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
05-25 13:49:15.257  9844  9907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
05-25 13:49:15.257  9844  9907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
05-25 13:49:15.257  9844  9907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: null
05-25 13:49:15.257  9844  9907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
05-25 13:49:15.257  9844  9907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
05-25 13:49:15.257  9844  9907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
05-25 13:49:15.257  9844  9907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
05-25 13:49:15.257  9844  9907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 256
05-25 13:49:15.257  9844  9907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
05-25 13:49:15.257  9844  9907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
05-25 13:49:15.257  9844  9907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
05-25 13:49:15.257  9844  9907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
05-25 13:49:15.257  9844  9907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,05-25 13:49:15.257  3011  3011 D libEGL  : eglTerminate EGLDisplay = 0x7fd4d61458
,05-25 13:49:15.267  9844  9907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: A8:81:95:E9:5F:6F
05-25 13:49:15.267  9844  9907 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: ", Bluetooth MAC address: "A8:81:95:E9:5F:6F"Peer extra info: "256
,05-25 13:49:15.267  9844  9907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
05-25 13:49:15.267  9844  9907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: null
05-25 13:49:15.267  9844  9907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
05-25 13:49:15.267  9844  9907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c89887 added. We now have 2 listener(s)
05-25 13:49:15.267  9844  9907 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
05-25 13:49:15.267  9844  9907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
05-25 13:49:15.267  9844  9907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 25730
05-25 13:49:15.267  9844  9907 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,7,main], id: 137
05-25 13:49:15.267  9844  9907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
05-25 13:49:15.267  9844  9907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
05-25 13:49:15.267  9844  9907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
05-25 13:49:15.267  9844  9907 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,7,main], id: 137
05-25 13:49:15.267  9844  9907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
05-25 13:49:15.267  9844  9907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is A8:81:95:E9:5F:6F
,05-25 13:49:15.277  9844  9907 D BluetoothAdapter: STATE_ON
05-25 13:49:15.277  9844  9907 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
05-25 13:49:15.277  9844  9907 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
05-25 13:49:15.277  9844  9907 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-25 13:49:15.277  9844  9907 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-25 13:49:15.277  9844  9907 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-25 13:49:15.277  9844  9907 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-25 13:49:15.277  9844  9907 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-25 13:49:15.277  9844  9907 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-25 13:49:15.277  9844  9907 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-25 13:49:15.277  9844  9907 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
05-25 13:49:15.277  9844  9907 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
05-25 13:49:15.277  9844  9907 D io.jxcore.node.ConnectivityMonitor: start: OK
05-25 13:49:15.277  9844  9907 I io.jxcore.node.LifeCycleMonitor: start: OK
05-25 13:49:15.277  9844  9844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
05-25 13:49:15.277  9844  9844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
05-25 13:49:15.287  9844  9844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
05-25 13:49:15.287  9844  9844 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
05-25 13:49:15.287  9844  9844 D SystemWebChromeClient: file:///android_asset/www/js/index.js: Line 36 : Uncaught TypeError: Cannot read property 'querySelector' of null
05-25 13:49:15.287  9844  9844 I chromium: [INFO:CONSOLE(36)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (36)
,05-25 13:49:15.337  3487  3882 D MdnieScenarioControlService:  packageName : com.thaliproject.thalitest    className : com.thaliproject.thalitest.MainActivity
,05-25 13:49:15.357  3487  3487 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3487  tag : ACTIVITY_RESUME_BOOSTER@13
,05-25 13:49:15.437  3487  3882 I MdnieScenarioControlService: mGameModeLauncher : false
,05-25 13:49:15.437  3487  3882 I MdnieScenarioControlService: setUIMode
,05-25 13:49:15.447  4029  4029 D Recents : onTaskStackChanged
,05-25 13:49:15.447  4029  4029 W ResourcesManager: getTopLevelResources: /data/app/com.thaliproject.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.thaliproject.thalitest
,05-25 13:49:15.467  3487  6265 W ResourcesManager: getTopLevelResources: /data/app/com.thaliproject.thalitest-1/base.apk / 1.0 running in null rsrc of package com.thaliproject.thalitest
,05-25 13:49:15.487  4029  4029 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:49:15.887  9844  9908 W jxcore-log: Initializing JXcore engine
05-25 13:49:15.887  9844  9908 W jxcore-log: JXcore engine is ready
,05-25 13:49:15.907  4912  4912 E audit   : type=1400 msg=audit(1495712955.907:264): avc:  denied  { ioctl } for  pid=9908 comm="Thread-138" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2237 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
05-25 13:49:15.907  4912  4912 E audit   :  SEPF_SECMOBILE_6.0.1_0031
05-25 13:49:15.907  4912  4912 E audit   : type=1300 msg=audit(1495712955.907:264): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=8 a1=5451 a2=2 a3=d51ba3c8 items=0 ppid=3182 pid=9908 auid=4294967295 uid=10078 gid=10078 euid=10078 suid=10078 fsuid=10078 egid=10078 sgid=10078 fsgid=10078 tty=(none) ses=4294967295 comm="Thread-138" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
05-25 13:49:15.907  4912  4912 E audit   : type=1327 msg=audit(1495712955.907:264): proctitle="com.thaliproject.thalitest"
05-25 13:49:15.907  4912  4912 E audit   : type=1320 msg=audit(1495712955.907:264): 
05-25 13:49:15.907  4912  4912 E audit   : type=1400 msg=audit(1495712955.907:265): avc:  denied  { ioctl } for  pid=9908 comm="Thread-138" path="socket:[40166]" dev="sockfs" ino=40166 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
05-25 13:49:15.907  4912  4912 E audit   :  SEPF_SECMOBILE_6.0.1_0031
05-25 13:49:15.907  4912  4912 E audit   : type=1300 msg=audit(1495712955.907:265): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=33 a1=5451 a2=2 a3=d51ba3c8 items=0 ppid=3182 pid=9908 auid=4294967295 uid=10078 gid=10078 euid=10078 suid=10078 fsuid=10078 egid=10078 sgid=10078 fsgid=10078 tty=(none) ses=4294967295 comm="Thread-138" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
05-25 13:49:15.907  4912  4912 E audit   : type=1327 msg=audit(1495712955.907:265): proctitle="com.thaliproject.thalitest"
05-25 13:49:15.907  4912  4912 E audit   : type=1320 msg=audit(1495712955.907:265): 
,05-25 13:49:15.917  9844  9908 W jxcore-log: Starting JXcore engine
,05-25 13:49:15.947  9844  9908 W jxcore-log: Platform android
05-25 13:49:15.947  9844  9908 W jxcore-log: 
05-25 13:49:15.947  9844  9908 W jxcore-log: Process ARCH arm
05-25 13:49:15.947  9844  9908 W jxcore-log: 
,05-25 13:49:16.077  9844  9908 I jxcore-log: JXcore Cordova bridge is ready!
05-25 13:49:16.077  9844  9908 I jxcore-log: 
05-25 13:49:16.077  9844  9908 W jxcore-log: JXcore engine is started
,05-25 13:49:16.087  9844  9907 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,05-25 13:49:16.087  9844  9844 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 41 : Application has the required permission.
05-25 13:49:16.087  9844  9844 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,05-25 13:49:17.387  3487  3908 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/20_task.xml.bak
,05-25 13:49:17.467  3487  6263 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
,05-25 13:49:20.507  3487  6263 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,05-25 13:49:23.177  9844  9908 I jxcore-log: 2017-05-25 11:49:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
05-25 13:49:23.177  9844  9908 I jxcore-log: 
,05-25 13:49:23.177  9844  9908 I jxcore-log: 2017-05-25 11:49:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
05-25 13:49:23.177  9844  9908 I jxcore-log: 
05-25 13:49:23.187  9844  9908 I jxcore-log: 2017-05-25 11:49:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
05-25 13:49:23.187  9844  9908 I jxcore-log: 
,05-25 13:49:23.187  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:49:23.197  9844  9908 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
05-25 13:49:23.197  9844  9908 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-25 13:49:23.197  9844  9908 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-25 13:49:23.197  9844  9908 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-25 13:49:23.197  9844  9908 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-25 13:49:23.197  9844  9908 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-25 13:49:23.197  9844  9908 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-25 13:49:23.197  9844  9908 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-25 13:49:23.197  9844  9908 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,05-25 13:49:23.197  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:49:23.197  9844  9908 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,05-25 13:49:23.197  9844  9908 I jxcore-log: 2017-05-25 11:49:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
05-25 13:49:23.197  9844  9908 I jxcore-log: 
05-25 13:49:23.207  9844  9908 I jxcore-log: 2017-05-25 11:49:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
05-25 13:49:23.207  9844  9908 I jxcore-log: 
,05-25 13:49:23.207  9844  9908 I jxcore-log: 2017-05-25 11:49:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
05-25 13:49:23.207  9844  9908 I jxcore-log: 
,05-25 13:49:23.467  9844  9908 D ExecuteNativeTests: Running unit tests
,05-25 13:49:23.467  9844  9908 D BluetoothAdapter: enable()
,05-25 13:49:23.477  9844  9908 D BluetoothAdapter: enable(): BT is already enabled..!
,05-25 13:49:23.487  3487  3570 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{fd288c2 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bad5c58 4933:com.samsung.android.providers.context/u0a9}
,05-25 13:49:23.487  9844  9908 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,05-25 13:49:23.497  3487  4196 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,05-25 13:49:23.497  3487  4196 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,05-25 13:49:23.497  3487  4196 D WifiService: setWifiEnabled: true pid=9844, uid=10078
,05-25 13:49:23.507  3487  4196 W ActivityManager: Permission Denial: getCurrentUser() from pid=9844, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
,05-25 13:49:23.507  3487  3860 D WifiBigDataLog: getJsonFormat() - feature : ONOF
05-25 13:49:23.507  3487  4196 W WifiService: Failed getting userId using ActivityManagerNative
05-25 13:49:23.507  3487  4196 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9844, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-25 13:49:23.507  3487  4196 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-25 13:49:23.507  3487  4196 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
05-25 13:49:23.507  3487  4196 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
05-25 13:49:23.507  3487  4196 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
05-25 13:49:23.507  3487  4196 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
05-25 13:49:23.507  3487  3860 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
05-25 13:49:23.507  3487  4196 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
05-25 13:49:23.507  3487  4196 D SettingsProvider: isChangeAllowed() : name = wifi_on
05-25 13:49:23.507  3487  3860 D WifiBigDataLog: init : 
05-25 13:49:23.507  3487  3863 D WifiController: [FCC]setFccChannel() is called !!!
05-25 13:49:23.507  3487  3863 D WifiStateMachine: setFccChannel: channel = 0
05-25 13:49:23.507  3487  3863 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
05-25 13:49:23.517  3487  3860 D WifiStateMachine: setFccChannelNative: channel = 0
05-25 13:49:23.517  3487  3860 D WifiNative-wlan0: callSECApiInt - ID [230]
,05-25 13:49:23.517  3487  3570 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a5b86d3 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bad5c58 4933:com.samsung.android.providers.context/u0a9}
,05-25 13:49:23.827  3487  4065 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-25 13:49:23.827  3487  4065 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4323, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:49:23.827  3487  4065 D BatteryService: online:4, current avg:-232, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:155
05-25 13:49:23.827  3487  3487 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:49:23.837  3487  3487 I MotionRecognitionService: Plugged
,05-25 13:49:23.837  3487  3487 D MotionRecognitionService:   cableConnection= 1
05-25 13:49:23.837  3487  3487 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:49:23.837  3487  3487 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:49:23.847  3487  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:49:23.847  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
05-25 13:49:23.847  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
,05-25 13:49:23.847  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
05-25 13:49:23.857  3949  3949 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,05-25 13:49:23.857  3949  3949 D PowerUI.Notification: There is no change about charging status, so return!
,05-25 13:49:23.867  4952  4952 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:49:23.867  4907  4907 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-25 13:49:23.867  4907  5263 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-25 13:49:23.877  4952  4952 D BatteryMonitor: new battery level: 100
,05-25 13:49:23.877  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
05-25 13:49:23.877  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,05-25 13:49:24.447  3487  3619 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,05-25 13:49:24.467  3487  3619 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,05-25 13:49:24.987  3487  6263 D SSRM:n  : SIOP:: AP = 380, PST = 318 (W:6), CP = 277, CUR = -232, LCD = 30
,05-25 13:49:25.007  3487  6263 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,05-25 13:49:29.367  3487  3604 I PowerManagerService: [PWL] On : 0 (189954 ms ago)
05-25 13:49:29.367  3487  3604 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4
,05-25 13:49:29.717  3487  6298 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,05-25 13:49:33.047  3487  4148 E Watchdog: !@Sync 6 [05-25 13:49:33.052]
,05-25 13:49:33.517  9844  9908 I com.test.thalitest.ThaliTestRunner: Running UT
,05-25 13:49:33.577  9844  9908 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
05-25 13:49:33.587  9844  9908 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f5836c7 added. We now have 2 listener(s)
05-25 13:49:33.587  9844  9908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f5836c7 added. We now have 3 listener(s)
05-25 13:49:33.587  9844  9908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,05-25 13:49:33.587  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: ", Bluetooth MAC address: "A8:81:95:E9:5F:6F"Peer extra info: "256
05-25 13:49:33.587  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
05-25 13:49:33.587  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: null
05-25 13:49:33.587  9844  9908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,05-25 13:49:33.587  9844  9908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2a24f4 added. We now have 4 listener(s)
05-25 13:49:33.587  9844  9908 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
05-25 13:49:33.587  9844  9908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,05-25 13:49:33.597  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:49:33.607  9844  9908 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
,05-25 13:49:33.607  9844  9908 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
05-25 13:49:33.607  9844  9908 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
05-25 13:49:33.607  9844  9908 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
05-25 13:49:33.607  9844  9908 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [00:11:22:33:44:55] timed out
05-25 13:49:33.607  9844  9908 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,05-25 13:49:33.607  9844  9908 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
05-25 13:49:33.607  9844  9908 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
05-25 13:49:33.607  9844  9908 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,05-25 13:49:33.607  9844  9908 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
05-25 13:49:33.607  9844  9908 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,05-25 13:49:33.607  9844  9908 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
,05-25 13:49:33.617  9844  9908 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
,05-25 13:49:33.617  9844  9908 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,05-25 13:49:33.617  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,05-25 13:49:33.637  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:49:33.637  9844  9908 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
05-25 13:49:33.637  9844  9908 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-25 13:49:33.637  9844  9908 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-25 13:49:33.637  9844  9908 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-25 13:49:33.637  9844  9908 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-25 13:49:33.637  9844  9908 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-25 13:49:33.637  9844  9908 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-25 13:49:33.637  9844  9908 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-25 13:49:33.637  9844  9908 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,05-25 13:49:33.637  9844  9908 D io.jxcore.node.ConnectivityMonitor: start: OK
,05-25 13:49:33.637  9844  9908 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 0
,05-25 13:49:33.637  9844  9908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 256 -> 0
05-25 13:49:33.637  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,05-25 13:49:33.647  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":0,"address":"A8:81:95:E9:5F:6F"}
05-25 13:49:33.647  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":0,"address":"A8:81:95:E9:5F:6F"}
,05-25 13:49:33.647  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:33.647  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
05-25 13:49:33.647  9844  9844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:49:33.647  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":0,"address":"A8:81:95:E9:5F:6F"}
05-25 13:49:33.647  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":0,"address":"A8:81:95:E9:5F:6F"}
05-25 13:49:33.647  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:49:33.647  9844  9908 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,05-25 13:49:33.647  9844  9908 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
05-25 13:49:33.647  9844  9908 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
05-25 13:49:33.647  9844  9844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:49:33.647  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,05-25 13:49:33.647  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
05-25 13:49:33.647  9844  9908 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
05-25 13:49:33.647  9844  9908 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
05-25 13:49:33.647  9844  9908 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
05-25 13:49:33.647  9844  9908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
05-25 13:49:33.647  9844  9908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
05-25 13:49:33.647  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
05-25 13:49:33.647  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
05-25 13:49:33.657  9844  9913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,05-25 13:49:33.657  9844  9913 D BluetoothSocket: bindListen(): myUserId = 0
05-25 13:49:33.657  9844  9913 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
05-25 13:49:33.657  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
05-25 13:49:33.657  9844  9908 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
05-25 13:49:33.657  9844  9908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,05-25 13:49:33.657  9844  9844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:49:33.667  9844  9844 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,05-25 13:49:33.667  9844  9913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
,05-25 13:49:33.667  9844  9913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@9177863, port: 6, type: 1, local socket address: null, socket type: 0
,05-25 13:49:33.677  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:49:33.677  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:49:33.677  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:49:33.677  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:49:33.677  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,05-25 13:49:33.687  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:49:33.687  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:49:33.687  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,05-25 13:49:33.687  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,05-25 13:49:33.687  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 0
05-25 13:49:33.687  9844  9908 D BluetoothAdapter: STATE_ON
05-25 13:49:33.687  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:33.687  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:33.687  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
05-25 13:49:33.687  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
05-25 13:49:33.687  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "1e0175e0-0d83-4d02-aa60-d3c622da762e", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
05-25 13:49:33.697  9844  9908 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 A8 81 95 E9 5F 6F
05-25 13:49:33.697  9844  9908 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[0, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-25 13:49:33.697  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[0, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-25 13:49:33.697  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:33.697  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[0, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:33.697  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
05-25 13:49:33.697  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[0, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-25 13:49:33.697  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:33.697  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:33.697  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[0, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:33.697  9844  9908 D BluetoothAdapter: STATE_ON
05-25 13:49:33.697  9844  9908 D BluetoothAdapter: STATE_ON
05-25 13:49:33.697  9844  9908 D BluetoothLeAdvertiser: start advertising
05-25 13:49:33.697  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:49:33.707  4907  4919 D BtGatt.GattService: registerClient() - UUID=a34b49f7-7022-4ba3-bb11-f121eab48862
,05-25 13:49:33.757  4907  5037 D BtGatt.GattService: onClientRegistered() - UUID=a34b49f7-7022-4ba3-bb11-f121eab48862, clientIf=7
,05-25 13:49:33.757  9844  9854 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,05-25 13:49:33.767  4907  5262 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,05-25 13:49:33.767  4907  5262 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,05-25 13:49:33.767  4907  5262 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,05-25 13:49:33.767  4907  5071 D BtGatt.AdvertiseManager: message : 0
05-25 13:49:33.767  4907  5081 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
,05-25 13:49:33.767  4907  5081 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 25, currDate: 25
05-25 13:49:33.767  4907  5071 D BtGatt.AdvertiseManager: number of adv instance running = 0
05-25 13:49:33.767  4907  5071 D BtGatt.AdvertiseManager: size of list is =0
,05-25 13:49:33.777  4907  5071 D BtGatt.AdvertiseManager: starting advertising
,05-25 13:49:33.777  4907  5071 D BtGatt.AdvertiseManager: isStandardAdv = false
,05-25 13:49:33.777  4907  5081 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.thaliproject.thalitest : 27
,05-25 13:49:33.787  3487  4927 V AlarmManager:  remove PendingIntent] PendingIntent{9dc6e1a: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
,05-25 13:49:33.787  4907  5081 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.thaliproject.thalitest@LowLatency : 24928549
,05-25 13:49:33.787  4907  5081 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.thaliproject.thalitest@LowLatency : 2
05-25 13:49:33.787  4907  5081 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
05-25 13:49:33.787  4907  5081 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 4 => 4
,05-25 13:49:33.787  3487  3505 V AlarmManager:  remove PendingIntent] PendingIntent{e82fd4b: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
,05-25 13:49:33.787  4907  5037 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,05-25 13:49:33.787  4907  5071 D BtGatt.AdvertiseManager: starting multi advertising
,05-25 13:49:33.797  4907  5037 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
05-25 13:49:33.797  3487  4408 V AlarmManager:  remove PendingIntent] PendingIntent{9f4e328: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
,05-25 13:49:33.797  4907  5071 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
05-25 13:49:33.797  4907  5071 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
05-25 13:49:33.797  4907  5071 D BtGatt.AdvertiseManager: postCallback clientIf = 7 status = 0
05-25 13:49:33.797  4907  5071 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=7, status=0, isStart=true
,05-25 13:49:33.797  9844  9855 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
,05-25 13:49:33.797  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:33.797  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:33.797  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,05-25 13:49:33.797  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:33.797  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:33.797  3487  3980 V AlarmManager:  remove PendingIntent] PendingIntent{36b1841: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
05-25 13:49:33.797  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:33.797  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:49:33.797  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:33.797  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
05-25 13:49:33.807  9844  9908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
05-25 13:49:33.807  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:49:33.807  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:33.807  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:33.807  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:33.807  3487  3985 V AlarmManager:  remove PendingIntent] PendingIntent{94351e6: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
05-25 13:49:33.807  9844  9908 I io.jxcore.node.ConnectionHelper: start: OK
05-25 13:49:33.807  9844  9844 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
05-25 13:49:33.807  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
05-25 13:49:33.807  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
05-25 13:49:33.807  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
05-25 13:49:33.807  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
05-25 13:49:33.807  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
,05-25 13:49:33.807  9844  9844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,05-25 13:49:33.807  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,05-25 13:49:33.807  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
05-25 13:49:33.807  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
05-25 13:49:33.807  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
05-25 13:49:33.807  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
05-25 13:49:33.817  3487  4671 V AlarmManager:  remove PendingIntent] PendingIntent{2822327: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
05-25 13:49:33.807  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
05-25 13:49:33.817  9844  9844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
05-25 13:49:33.817  9844  9844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,05-25 13:49:33.817  9844  9844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,05-25 13:49:33.817  9844  9844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
05-25 13:49:33.817  9844  9844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
05-25 13:49:33.817  9844  9844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
05-25 13:49:33.817  3487  4196 V AlarmManager:  remove PendingIntent] PendingIntent{f4909d4: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
05-25 13:49:33.817  9844  9844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,05-25 13:49:33.867  3487  4927 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,05-25 13:49:33.867  3487  4927 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4337, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:49:33.867  3487  4927 D BatteryService: online:4, current avg:13, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:124
05-25 13:49:33.867  3487  3487 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:49:33.867  3487  3487 I MotionRecognitionService: Plugged
,05-25 13:49:33.867  3487  3487 D MotionRecognitionService:   cableConnection= 1
05-25 13:49:33.867  3487  3487 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:49:33.867  3487  3487 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:49:33.867  3487  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:49:33.867  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
05-25 13:49:33.867  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
05-25 13:49:33.867  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:49:33.867  3949  3949 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
05-25 13:49:33.877  3949  3949 D PowerUI.Notification: There is no change about charging status, so return!
,05-25 13:49:33.877  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,05-25 13:49:33.877  4952  4952 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:49:33.877  4907  4907 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-25 13:49:33.877  4907  5263 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-25 13:49:33.887  4952  4952 D BatteryMonitor: new battery level: 100
,05-25 13:49:33.887  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,05-25 13:49:34.307  9844  9915 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,05-25 13:49:34.317  9844  9908 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
05-25 13:49:34.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [00:11:22:33:44:55]
05-25 13:49:34.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [10:010:010:010:010:010]
05-25 13:49:34.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [11:110:110:110:110:110]
05-25 13:49:34.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [12:210:210:210:210:210]
05-25 13:49:34.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [13:310:310:310:310:310]
05-25 13:49:34.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [14:410:410:410:410:410]
05-25 13:49:34.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [15:510:510:510:510:510]
05-25 13:49:34.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [16:610:610:610:610:610]
05-25 13:49:34.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [17:710:710:710:710:710]
05-25 13:49:34.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [18:810:810:810:810:810]
05-25 13:49:34.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [19:910:910:910:910:910]
05-25 13:49:34.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [20:1010:1010:1010:1010:1010]
05-25 13:49:34.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [21:1110:1110:1110:1110:1110]
05-25 13:49:34.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [22:1210:1210:1210:1210:1210]
05-25 13:49:34.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [23:1310:1310:1310:1310:1310]
05-25 13:49:34.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [24:1410:1410:1410:1410:1410]
05-25 13:49:34.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [25:1510:1510:1510:1510:1510]
05-25 13:49:34.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [26:1610:1610:1610:1610:1610]
05-25 13:49:34.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [27:1710:1710:1710:1710:1710]
05-25 13:49:34.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [28:1810:1810:1810:1810:1810]
05-25 13:49:34.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [29:1910:1910:1910:1910:1910]
05-25 13:49:34.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [30:2010:2010:2010:2010:2010]
05-25 13:49:34.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [31:2110:2110:2110:2110:2110]
05-25 13:49:34.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [32:2210:2210:2210:2210:2210]
05-25 13:49:34.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [33:2310:2310:2310:2310:2310]
05-25 13:49:34.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [34:2410:2410:2410:2410:2410]
05-25 13:49:34.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [35:2510:2510:2510:2510:2510]
05-25 13:49:34.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [36:2610:2610:2610:2610:2610]
05-25 13:49:34.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [37:2,710:2710:2710:2710:2710]
05-25 13:49:34.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [38:2810:2810:2810:2810:2810]
05-25 13:49:34.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [39:2910:2910:2910:2910:2910]
05-25 13:49:34.317  9844  9908 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
05-25 13:49:34.317  9844  9908 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
05-25 13:49:34.317  9844  9908 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
05-25 13:49:34.317  9844  9908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
05-25 13:49:34.317  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
05-25 13:49:34.317  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
05-25 13:49:34.317  9844  9844 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
05-25 13:49:34.327  9844  9913 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
05-25 13:49:34.327  9844  9913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
05-25 13:49:34.327  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,05-25 13:49:34.327  9844  9913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
05-25 13:49:34.327  9844  9908 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
05-25 13:49:34.327  9844  9908 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
05-25 13:49:34.327  9844  9908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,05-25 13:49:34.327  9844  9908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
05-25 13:49:34.327  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:34.327  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
05-25 13:49:34.327  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
05-25 13:49:34.327  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:49:34.327  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:34.327  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:34.327  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:49:34.327  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:49:34.337  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:49:34.337  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,05-25 13:49:34.337  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:49:34.337  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:49:34.337  9844  9908 D BluetoothLeScanner: could not find callback wrapper
05-25 13:49:34.337  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
05-25 13:49:34.337  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:34.337  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:49:34.337  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:34.337  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
05-25 13:49:34.337  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:49:34.347  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:49:34.347  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:49:34.347  9844  9908 D BluetoothLeAdvertiser: stop advertising
,05-25 13:49:34.357  4907  5262 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,05-25 13:49:34.357  4907  5262 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
05-25 13:49:34.357  4907  5071 D BtGatt.AdvertiseManager: message : 1
05-25 13:49:34.357  4907  5081 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
05-25 13:49:34.357  4907  5081 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 25, currDate: 25
05-25 13:49:34.357  4907  5081 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
,05-25 13:49:34.357  4907  5081 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 4 => 4
05-25 13:49:34.357  4907  5071 D BtGatt.AdvertiseManager: stop advertise for client =  7
,05-25 13:49:34.357  4907  5071 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 7
05-25 13:49:34.357  4907  5081 D BtGatt.GattService: [GSIM LOG]: remove : com.thaliproject.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
,05-25 13:49:34.367  3487  3505 V AlarmManager:  remove PendingIntent] PendingIntent{10ff77d: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
,05-25 13:49:34.367  4907  5037 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,05-25 13:49:34.367  4907  5037 D BtGatt.GattService: Client app is not null!
,05-25 13:49:34.367  4907  5071 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,05-25 13:49:34.367  9844  9854 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
05-25 13:49:34.367  4353  4435 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
05-25 13:49:34.367  4353  4435 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
05-25 13:49:34.377  4907  5371 D BtGatt.GattService: unregisterClient() - clientIf=7
,05-25 13:49:34.377  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
05-25 13:49:34.377  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:34.377  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,05-25 13:49:34.377  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:34.377  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:34.377  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:49:34.377  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
05-25 13:49:34.377  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
05-25 13:49:34.377  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
05-25 13:49:34.377  3487  4671 V AlarmManager:  remove PendingIntent] PendingIntent{8e2a672: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
05-25 13:49:34.377  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:49:34.387  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:49:34.387  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
05-25 13:49:34.387  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:34.387  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:34.387  9844  9844 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
05-25 13:49:34.387  9844  9844 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,05-25 13:49:34.387  9844  9844 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,05-25 13:49:34.387  9844  9844 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,05-25 13:49:34.387  3487  4065 V AlarmManager:  remove PendingIntent] PendingIntent{563cac3: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
05-25 13:49:34.387  9844  9844 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
05-25 13:49:34.387  9844  9844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
05-25 13:49:34.387  9844  9844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,05-25 13:49:34.387  9844  9844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
05-25 13:49:34.387  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
05-25 13:49:34.387  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
05-25 13:49:34.387  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
05-25 13:49:34.387  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
05-25 13:49:34.387  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
05-25 13:49:34.387  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
05-25 13:49:34.387  9844  9844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
05-25 13:49:34.397  9844  9918 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
05-25 13:49:34.397  9844  9908 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
05-25 13:49:34.397  9844  9908 V io.jxcore.node.ConnectivityMonitor: start: Already started
05-25 13:49:34.397  9844  9908 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
05-25 13:49:34.397  9844  9908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
05-25 13:49:34.397  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,05-25 13:49:34.397  3487  3985 V AlarmManager:  remove PendingIntent] PendingIntent{916ef40: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
,05-25 13:49:34.397  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":1,"address":"A8:81:95:E9:5F:6F"}
,05-25 13:49:34.397  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":1,"address":"A8:81:95:E9:5F:6F"}
05-25 13:49:34.397  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:49:34.397  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,05-25 13:49:34.407  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":1,"address":"A8:81:95:E9:5F:6F"}
,05-25 13:49:34.407  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":1,"address":"A8:81:95:E9:5F:6F"}
05-25 13:49:34.407  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:34.407  9844  9908 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
05-25 13:49:34.407  9844  9908 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
05-25 13:49:34.407  3487  4670 V AlarmManager:  remove PendingIntent] PendingIntent{7298e79: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
05-25 13:49:34.407  9844  9908 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
05-25 13:49:34.407  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
05-25 13:49:34.407  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,05-25 13:49:34.407  9844  9908 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,05-25 13:49:34.407  9844  9908 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
05-25 13:49:34.407  9844  9908 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
05-25 13:49:34.407  9844  9908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,05-25 13:49:34.407  9844  9844 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
05-25 13:49:34.407  9844  9908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
05-25 13:49:34.407  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
05-25 13:49:34.407  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,05-25 13:49:34.407  9844  9919 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
05-25 13:49:34.407  9844  9919 D BluetoothSocket: bindListen(): myUserId = 0
05-25 13:49:34.407  9844  9919 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
05-25 13:49:34.417  3487  4196 V AlarmManager:  remove PendingIntent] PendingIntent{2ab9935: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
,05-25 13:49:34.417  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,05-25 13:49:34.417  9844  9908 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
05-25 13:49:34.417  9844  9908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
05-25 13:49:34.417  9844  9919 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
05-25 13:49:34.417  9844  9919 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@1f0d9d5, port: 6, type: 1, local socket address: null, socket type: 0
,05-25 13:49:34.417  9844  9908 D BluetoothAdapter: STATE_ON
05-25 13:49:34.417  3487  4927 V AlarmManager:  remove PendingIntent] PendingIntent{fbc91ca: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
,05-25 13:49:34.427  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:49:34.427  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:49:34.427  3487  3985 V AlarmManager:  remove PendingIntent] PendingIntent{3f1cf3b: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
,05-25 13:49:34.427  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:34.427  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,05-25 13:49:34.427  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:49:34.427  9844  9908 D BluetoothAdapter: STATE_ON
05-25 13:49:34.427  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,05-25 13:49:34.427  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
05-25 13:49:34.427  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 1
,05-25 13:49:34.437  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:49:34.437  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:49:34.437  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:34.437  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
05-25 13:49:34.437  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
05-25 13:49:34.437  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "1e0175e0-0d83-4d02-aa60-d3c622da762e", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
05-25 13:49:34.437  9844  9908 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 A8 81 95 E9 5F 6F
05-25 13:49:34.437  9844  9908 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[1, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-25 13:49:34.437  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[1, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,05-25 13:49:34.437  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:34.437  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[1, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:34.437  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
05-25 13:49:34.437  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[1, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-25 13:49:34.437  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:34.437  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
,05-25 13:49:34.437  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[1, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:34.437  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:49:34.437  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:49:34.437  9844  9908 D BluetoothLeAdvertiser: start advertising
05-25 13:49:34.437  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:49:34.447  4907  5371 D BtGatt.GattService: registerClient() - UUID=5819f268-90bc-4ec6-94eb-4c105804a39c
,05-25 13:49:34.487  4907  5037 D BtGatt.GattService: onClientRegistered() - UUID=5819f268-90bc-4ec6-94eb-4c105804a39c, clientIf=7
,05-25 13:49:34.487  9844  9855 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,05-25 13:49:34.487  4907  4918 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,05-25 13:49:34.497  4907  4918 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,05-25 13:49:34.497  4907  4918 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
05-25 13:49:34.497  4907  5071 D BtGatt.AdvertiseManager: message : 0
05-25 13:49:34.497  4907  5081 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
05-25 13:49:34.497  4907  5081 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 25, currDate: 25
05-25 13:49:34.497  4907  5071 D BtGatt.AdvertiseManager: number of adv instance running = 0
,05-25 13:49:34.497  4907  5071 D BtGatt.AdvertiseManager: size of list is =0
,05-25 13:49:34.507  4907  5071 D BtGatt.AdvertiseManager: starting advertising
,05-25 13:49:34.517  4907  5071 D BtGatt.AdvertiseManager: isStandardAdv = false
,05-25 13:49:34.517  4907  5081 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.thaliproject.thalitest : 28
05-25 13:49:34.517  4907  5081 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.thaliproject.thalitest@LowLatency : 24928549
05-25 13:49:34.517  4907  5081 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.thaliproject.thalitest@LowLatency : 2
,05-25 13:49:34.517  4907  5081 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
05-25 13:49:34.517  4907  5081 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 4 => 4
,05-25 13:49:34.517  3487  4197 V AlarmManager:  remove PendingIntent] PendingIntent{dbb6658: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
,05-25 13:49:34.527  4907  5037 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,05-25 13:49:34.527  4907  5071 D BtGatt.AdvertiseManager: starting multi advertising
,05-25 13:49:34.527  4907  5037 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
05-25 13:49:34.527  4907  5071 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
05-25 13:49:34.527  4907  5071 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,05-25 13:49:34.527  3487  4407 V AlarmManager:  remove PendingIntent] PendingIntent{20993b1: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
05-25 13:49:34.527  4907  5071 D BtGatt.AdvertiseManager: postCallback clientIf = 7 status = 0
,05-25 13:49:34.527  4907  5071 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=7, status=0, isStart=true
05-25 13:49:34.527  9844  9854 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
05-25 13:49:34.537  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:49:34.537  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:34.537  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
05-25 13:49:34.537  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:49:34.537  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:34.537  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:34.537  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:49:34.537  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:49:34.537  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
05-25 13:49:34.537  9844  9908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
05-25 13:49:34.537  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:49:34.537  9844  9908 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: seems that updateState call different BlePeerDiscoverer
,05-25 13:49:34.537  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:34.547  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:34.547  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:34.547  9844  9908 I io.jxcore.node.ConnectionHelper: start: OK
05-25 13:49:34.547  3487  4927 V AlarmManager:  remove PendingIntent] PendingIntent{4fa0096: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
,05-25 13:49:34.547  9844  9844 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
05-25 13:49:34.547  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,05-25 13:49:34.547  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
05-25 13:49:34.547  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,05-25 13:49:34.547  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
05-25 13:49:34.547  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
05-25 13:49:34.547  9844  9844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,05-25 13:49:34.547  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
05-25 13:49:34.547  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
,05-25 13:49:34.547  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
05-25 13:49:34.547  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
05-25 13:49:34.547  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
,05-25 13:49:34.547  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
05-25 13:49:34.557  3487  4197 V AlarmManager:  remove PendingIntent] PendingIntent{4a42417: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
05-25 13:49:34.547  9844  9844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
,05-25 13:49:34.547  9844  9844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
05-25 13:49:34.547  9844  9844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
05-25 13:49:34.547  9844  9844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
05-25 13:49:34.547  9844  9844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
05-25 13:49:34.547  9844  9844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
05-25 13:49:34.547  9844  9844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,05-25 13:49:34.557  3487  4920 V AlarmManager:  remove PendingIntent] PendingIntent{dac9004: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
,05-25 13:49:34.567  3487  4670 V AlarmManager:  remove PendingIntent] PendingIntent{d72b9ed: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
,05-25 13:49:34.567  3487  4065 V AlarmManager:  remove PendingIntent] PendingIntent{8cd9022: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
,05-25 13:49:34.577  3487  4927 V AlarmManager:  remove PendingIntent] PendingIntent{dbceab3: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
,05-25 13:49:35.037  3487  6263 D SSRM:n  : SIOP:: AP = 330, PST = 326 (W:14), CP = 279, CUR = 13, LCD = 30
,05-25 13:49:35.047  9844  9921 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,05-25 13:49:35.047  9844  9908 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
,05-25 13:49:35.047  9844  9908 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
05-25 13:49:35.047  9844  9908 V io.jxcore.node.ConnectivityMonitor: start: Already started
05-25 13:49:35.047  9844  9908 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
05-25 13:49:35.047  9844  9908 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
,05-25 13:49:35.047  9844  9908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
05-25 13:49:35.047  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
05-25 13:49:35.057  9844  9844 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,05-25 13:49:35.057  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":2,"address":"A8:81:95:E9:5F:6F"}
,05-25 13:49:35.057  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":2,"address":"A8:81:95:E9:5F:6F"}
05-25 13:49:35.057  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:35.057  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,05-25 13:49:35.067  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":2,"address":"A8:81:95:E9:5F:6F"}
,05-25 13:49:35.067  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":2,"address":"A8:81:95:E9:5F:6F"}
05-25 13:49:35.067  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:35.067  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
05-25 13:49:35.067  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 25730
05-25 13:49:35.067  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
05-25 13:49:35.067  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 2
05-25 13:49:35.067  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
05-25 13:49:35.067  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
05-25 13:49:35.067  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
05-25 13:49:35.067  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
05-25 13:49:35.067  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
05-25 13:49:35.067  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:35.067  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 2
,05-25 13:49:35.067  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted true Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:35.067  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop advertiser Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:35.067  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:35.067  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:49:35.077  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:49:35.077  9844  9908 D BluetoothLeAdvertiser: stop advertising
,05-25 13:49:35.087  4907  5370 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
05-25 13:49:35.087  4907  5370 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,05-25 13:49:35.087  4907  5071 D BtGatt.AdvertiseManager: message : 1
05-25 13:49:35.087  4907  5081 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
05-25 13:49:35.087  4907  5081 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 25, currDate: 25
,05-25 13:49:35.087  4907  5081 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
05-25 13:49:35.087  4907  5081 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 4 => 4
05-25 13:49:35.087  4907  5081 D BtGatt.GattService: [GSIM LOG]: remove : com.thaliproject.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
05-25 13:49:35.087  4907  5071 D BtGatt.AdvertiseManager: stop advertise for client =  7
,05-25 13:49:35.087  4907  5071 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 7
,05-25 13:49:35.087  4907  5071 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,05-25 13:49:35.097  3487  4670 V AlarmManager:  remove PendingIntent] PendingIntent{264a870: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
,05-25 13:49:35.097  4907  5037 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,05-25 13:49:35.097  4907  5037 D BtGatt.GattService: Client app is not null!
05-25 13:49:35.097  9844  9855 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,05-25 13:49:35.097  4907  4919 D BtGatt.GattService: unregisterClient() - clientIf=7
,05-25 13:49:35.107  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,05-25 13:49:35.107  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:35.107  3487  3505 V AlarmManager:  remove PendingIntent] PendingIntent{6ce07e9: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
05-25 13:49:35.107  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,05-25 13:49:35.107  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:35.107  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:35.107  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:49:35.107  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
05-25 13:49:35.107  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:35.107  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:49:35.107  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:35.107  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
05-25 13:49:35.107  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
05-25 13:49:35.107  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "1e0175e0-0d83-4d02-aa60-d3c622da762e", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
05-25 13:49:35.107  9844  9908 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 A8 81 95 E9 5F 6F
,05-25 13:49:35.107  9844  9908 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[2, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-25 13:49:35.107  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[2, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-25 13:49:35.107  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:35.107  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[2, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:49:35.107  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
05-25 13:49:35.107  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[2, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,05-25 13:49:35.107  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:35.117  3487  4927 V AlarmManager:  remove PendingIntent] PendingIntent{3588c6e: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
05-25 13:49:35.107  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:35.107  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[2, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:49:35.107  9844  9908 D BluetoothAdapter: STATE_ON
05-25 13:49:35.117  9844  9908 D BluetoothAdapter: STATE_ON
05-25 13:49:35.117  9844  9908 D BluetoothLeAdvertiser: start advertising
05-25 13:49:35.117  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:49:35.127  3487  4671 V AlarmManager:  remove PendingIntent] PendingIntent{2917f0f: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
,05-25 13:49:35.127  4907  5371 D BtGatt.GattService: registerClient() - UUID=c602ca5c-0e7f-4c1e-b411-14a98d05ac9c
,05-25 13:49:35.137  3487  3854 V AlarmManager:  remove PendingIntent] PendingIntent{143db9c: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
,05-25 13:49:35.137  3487  4407 V AlarmManager:  remove PendingIntent] PendingIntent{d7639a5: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
,05-25 13:49:35.147  3487  4920 V AlarmManager:  remove PendingIntent] PendingIntent{b85017a: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
,05-25 13:49:35.157  3487  3505 V AlarmManager:  remove PendingIntent] PendingIntent{c70fd2b: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
,05-25 13:49:35.167  4907  5037 D BtGatt.GattService: onClientRegistered() - UUID=c602ca5c-0e7f-4c1e-b411-14a98d05ac9c, clientIf=7
,05-25 13:49:35.177  9844  9854 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,05-25 13:49:35.177  4907  4919 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,05-25 13:49:35.177  4907  4919 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,05-25 13:49:35.177  4907  4919 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,05-25 13:49:35.177  4907  5081 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
05-25 13:49:35.177  4907  5071 D BtGatt.AdvertiseManager: message : 0
05-25 13:49:35.177  4907  5081 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 25, currDate: 25
,05-25 13:49:35.187  4907  5071 D BtGatt.AdvertiseManager: number of adv instance running = 0
05-25 13:49:35.187  4907  5071 D BtGatt.AdvertiseManager: size of list is =0
,05-25 13:49:35.187  4907  5071 D BtGatt.AdvertiseManager: starting advertising
,05-25 13:49:35.197  4907  5071 D BtGatt.AdvertiseManager: isStandardAdv = false
,05-25 13:49:35.197  4907  5081 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.thaliproject.thalitest : 29
,05-25 13:49:35.197  4907  5081 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.thaliproject.thalitest@LowLatency : 24928549
05-25 13:49:35.197  4907  5081 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.thaliproject.thalitest@LowLatency : 2
05-25 13:49:35.197  4907  5081 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
05-25 13:49:35.197  3487  4408 V AlarmManager:  remove PendingIntent] PendingIntent{3811588: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
05-25 13:49:35.197  4907  5081 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 4 => 4
,05-25 13:49:35.197  4907  5037 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
05-25 13:49:35.197  4907  5071 D BtGatt.AdvertiseManager: starting multi advertising
,05-25 13:49:35.207  3487  3506 V AlarmManager:  remove PendingIntent] PendingIntent{1b5cb21: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
,05-25 13:49:35.207  4907  5037 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
05-25 13:49:35.207  4907  5071 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
05-25 13:49:35.207  4907  5071 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
05-25 13:49:35.207  4907  5071 D BtGatt.AdvertiseManager: postCallback clientIf = 7 status = 0
05-25 13:49:35.207  4907  5071 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=7, status=0, isStart=true
05-25 13:49:35.207  9844  9855 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
05-25 13:49:35.207  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:35.207  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:35.207  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
05-25 13:49:35.207  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:35.207  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:49:35.207  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:35.207  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:35.207  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:49:35.207  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser started = true Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:35.207  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
05-25 13:49:35.207  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted false Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:35.207  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
05-25 13:49:35.207  9844  9908 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
05-25 13:49:35.207  9844  9908 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,05-25 13:49:35.207  9844  9908 I io.jxcore.node.ConnectionHelper: start: OK
05-25 13:49:35.207  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
05-25 13:49:35.207  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
05-25 13:49:35.207  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
05-25 13:49:35.217  3487  3854 V AlarmManager:  remove PendingIntent] PendingIntent{ad1bb46: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
05-25 13:49:35.207  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
05-25 13:49:35.207  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
,05-25 13:49:35.207  9844  9844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
05-25 13:49:35.207  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
05-25 13:49:35.207  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
05-25 13:49:35.207  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
05-25 13:49:35.207  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
05-25 13:49:35.207  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,05-25 13:49:35.207  9844  9923 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
05-25 13:49:35.207  9844  9908 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
05-25 13:49:35.207  9844  9908 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
05-25 13:49:35.207  9844  9908 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,05-25 13:49:35.207  9844  9908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
05-25 13:49:35.207  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
05-25 13:49:35.207  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,05-25 13:49:35.207  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
05-25 13:49:35.207  9844  9908 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
05-25 13:49:35.217  9844  9908 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
05-25 13:49:35.217  9844  9919 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
05-25 13:49:35.217  9844  9919 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
05-25 13:49:35.217  9844  9908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
05-25 13:49:35.217  9844  9919 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
05-25 13:49:35.217  9844  9908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
05-25 13:49:35.217  9844  9844 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
05-25 13:49:35.217  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:35.217  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
05-25 13:49:35.217  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
05-25 13:49:35.217  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:35.217  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:35.217  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:35.217  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:35.217  9844  9908 D BluetoothAdapter: STATE_ON
05-25 13:49:35.217  9844  9908 D BluetoothAdapter: STATE_ON
05-25 13:49:35.217  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
05-25 13:49:35.217  9844  9908 D BluetoothAdapter: STATE_ON
05-25 13:49:35.217  9844  9908 D BluetoothAdapter: STATE_ON
05-25 13:49:35.217  9844  9908 D BluetoothLeScanner: could not find callback wrapper
05-25 13:49:35.217  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,05-25 13:49:35.217  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:35.217  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:35.217  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:35.217  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
05-25 13:49:35.227  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:35.227  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:49:35.227  9844  9908 D BluetoothAdapter: STATE_ON
05-25 13:49:35.227  9844  9908 D BluetoothLeAdvertiser: stop advertising
,05-25 13:49:35.227  3487  4671 V AlarmManager:  remove PendingIntent] PendingIntent{804107: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
,05-25 13:49:35.227  4907  4919 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,05-25 13:49:35.227  4907  4919 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
05-25 13:49:35.227  4907  5071 D BtGatt.AdvertiseManager: message : 1
05-25 13:49:35.227  4907  5081 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
05-25 13:49:35.227  4907  5081 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 25, currDate: 25
05-25 13:49:35.227  3487  3854 V AlarmManager:  remove PendingIntent] PendingIntent{cd60234: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
,05-25 13:49:35.227  4907  5081 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
05-25 13:49:35.227  4907  5081 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 4 => 4
05-25 13:49:35.227  4907  5081 D BtGatt.GattService: [GSIM LOG]: remove : com.thaliproject.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
,05-25 13:49:35.237  4907  5071 D BtGatt.AdvertiseManager: stop advertise for client =  7
05-25 13:49:35.237  4907  5071 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 7
05-25 13:49:35.237  4907  5071 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
05-25 13:49:35.237  4907  5037 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,05-25 13:49:35.237  4907  5037 D BtGatt.GattService: Client app is not null!
05-25 13:49:35.237  3487  4417 V AlarmManager:  remove PendingIntent] PendingIntent{402f85d: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
05-25 13:49:35.237  9844  9854 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
05-25 13:49:35.237  4907  4918 D BtGatt.GattService: unregisterClient() - clientIf=7
05-25 13:49:35.247  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
05-25 13:49:35.247  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:35.247  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
05-25 13:49:35.247  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:35.247  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:35.247  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:35.247  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,05-25 13:49:35.247  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
05-25 13:49:35.247  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
05-25 13:49:35.247  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:49:35.247  3487  4671 V AlarmManager:  remove PendingIntent] PendingIntent{1de45d2: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
05-25 13:49:35.247  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:35.247  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
05-25 13:49:35.247  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:35.247  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:35.247  3487  3854 V AlarmManager:  remove PendingIntent] PendingIntent{755e6a3: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
05-25 13:49:35.247  9844  9844 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
05-25 13:49:35.247  9844  9844 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
05-25 13:49:35.247  9844  9844 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
05-25 13:49:35.247  9844  9844 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
05-25 13:49:35.247  9844  9844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
05-25 13:49:35.247  9844  9844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
05-25 13:49:35.247  9844  9844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
05-25 13:49:35.247  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
05-25 13:49:35.247  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
05-25 13:49:35.247  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
05-25 13:49:35.247  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
05-25 13:49:35.247  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
05-25 13:49:35.247  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
05-25 13:49:35.247  9844  9844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
05-25 13:49:35.247  9844  9924 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
05-25 13:49:35.247  9844  9908 I io.jxcore.node.ConnectionHelperTest: Starting test: testListenToConnectivityChanges
05-25 13:49:35.247  9844  9908 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
05-25 13:49:35.247  9844  9908 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1765fb7 added. We now have 3 listener(s)
05-25 13:49:35.257  3487  4407 V AlarmManager:  remove PendingIntent] PendingIntent{eb0da0: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
05-25 13:49:35.247  9844  9908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1765fb7 added. We now have 5 listener(s)
05-25 13:49:35.247  9844  9908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
05-25 13:49:35.257  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":2,"address":"A8:81:95:E9:5F:6F"}
05-25 13:49:35.257  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
05-25 13:49:35.257  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":2,"address":"A8:81:95:E9:5F:6F"}
05-25 13:49:35.257  9844  9908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
05-25 13:49:35.257  9844  9908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f1ab324 added. We now have 6 listener(s)
05-25 13:49:35.257  9844  9908 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
05-25 13:49:35.257  9844  9908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
05-25 13:49:35.267  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
05-25 13:49:35.267  3487  3854 V AlarmManager:  remove PendingIntent] PendingIntent{38363cc: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
05-25 13:49:35.267  9844  9908 D BluetoothAdapter: STATE_ON
05-25 13:49:35.277  3487  4670 V AlarmManager:  remove PendingIntent] PendingIntent{321d615: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
05-25 13:49:35.277  9844  9908 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
05-25 13:49:35.277  9844  9908 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-25 13:49:35.277  9844  9908 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-25 13:49:35.277  9844  9908 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-25 13:49:35.277  9844  9908 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-25 13:49:35.277  9844  9908 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-25 13:49:35.277  9844  9908 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-25 13:49:35.277  9844  9908 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-25 13:49:35.277  9844  9908 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
05-25 13:49:35.277  9844  9908 D io.jxcore.node.ConnectivityMonitor: start: OK
05-25 13:49:35.277  3487  3980 V AlarmManager:  remove PendingIntent] PendingIntent{de0bd2a: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
05-25 13:49:35.277  9844  9908 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
05-25 13:49:35.287  3487  4671 V AlarmManager:  remove PendingIntent] PendingIntent{acf871b: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
05-25 13:49:35.287  9844  9844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:49:35.287  3487  4407 V AlarmManager:  remove PendingIntent] PendingIntent{f68f0b8: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
,05-25 13:49:35.287  9844  9844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:49:35.287  3487  3505 V AlarmManager:  remove PendingIntent] PendingIntent{f56be91: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
,05-25 13:49:35.297  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:49:35.297  3487  3854 V AlarmManager:  remove PendingIntent] PendingIntent{b2581f6: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
,05-25 13:49:35.297  9844  9908 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
05-25 13:49:35.297  9844  9908 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-25 13:49:35.297  9844  9908 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-25 13:49:35.297  9844  9908 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-25 13:49:35.297  9844  9908 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-25 13:49:35.297  9844  9908 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-25 13:49:35.297  9844  9908 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-25 13:49:35.297  9844  9908 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-25 13:49:35.297  9844  9908 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
05-25 13:49:35.297  9844  9908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
05-25 13:49:35.297  9844  9908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,05-25 13:49:35.297  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
05-25 13:49:35.297  9844  9908 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
05-25 13:49:35.297  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
05-25 13:49:35.297  9844  9908 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1765fb7 removed from the list
,05-25 13:49:35.297  9844  9908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1765fb7 removed from the list
05-25 13:49:35.297  9844  9908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
05-25 13:49:35.297  9844  9908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f1ab324 removed from the list
,05-25 13:49:35.307  9844  9844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:49:35.307  9844  9908 D io.jxcore.node.ConnectivityMonitor: stop
05-25 13:49:35.307  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,05-25 13:49:35.307  9844  9908 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
,05-25 13:49:35.307  9844  9908 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,05-25 13:49:35.307  9844  9908 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
,05-25 13:49:35.307  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [incoming]
,05-25 13:49:35.307  9844  9908 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
,05-25 13:49:35.307  9844  9908 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,05-25 13:49:35.307  9844  9908 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
,05-25 13:49:35.307  9844  9908 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,05-25 13:49:35.317  9844  9908 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
,05-25 13:49:35.317  9844  9908 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
05-25 13:49:35.317  9844  9908 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
05-25 13:49:35.317  9844  9908 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
05-25 13:49:35.317  9844  9908 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
05-25 13:49:35.317  9844  9908 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,05-25 13:49:35.317  9844  9908 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
05-25 13:49:35.317  9844  9908 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
05-25 13:49:35.317  9844  9908 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
05-25 13:49:35.317  9844  9908 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
05-25 13:49:35.317  9844  9908 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
05-25 13:49:35.317  9844  9908 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
05-25 13:49:35.317  9844  9908 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
05-25 13:49:35.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [00:11:22:33:44:55]
05-25 13:49:35.317  9844  9908 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
05-25 13:49:35.317  9844  9908 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
05-25 13:49:35.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [10:010:010:010:010:010]
05-25 13:49:35.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [11:110:110:110:110:110]
05-25 13:49:35.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [12:210:210:210:210:210]
05-25 13:49:35.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [13:310:310:310:310:310]
05-25 13:49:35.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [14:410:410:410:410:410]
05-25 13:49:35.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [15:510:510:510:510:510]
05-25 13:49:35.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [16:610:610:610:610:610]
05-25 13:49:35.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [17:710:710:710:710:710]
05-25 13:49:35.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [18:810:810:810:810:810]
05-25 13:49:35.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [19:910:910:910:910:910]
05-25 13:49:35.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [20:1010:1010:1010:1010:1010]
05-25 13:49:35.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [21:1110:1110:1110:1110:1110]
05-25 13:49:35.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [22:1210:1210:1210:1210:1210]
05-25 13:49:35.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [23:1310:1310:1310:1310:1310]
05-25 13:49:35.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [24:1410:1410:1410:1410:1410]
05-25 13:49:35.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [25:1510:1510:1510:1510:1510]
05-25 13:49:35.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [26:1610:1610:1610:1610:1610]
05-25 13:49:35.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [27:1710:1710:1710:1710:1710]
,05-25 13:49:35.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [28:1810:1810:1810:1810:1810]
05-25 13:49:35.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [29:1910:1910:1910:1910:1910]
05-25 13:49:35.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [30:2010:2010:2010:2010:2010]
05-25 13:49:35.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [31:2110:2110:2110:2110:2110]
05-25 13:49:35.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [32:2210:2210:2210:2210:2210]
05-25 13:49:35.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [33:2310:2310:2310:2310:2310]
05-25 13:49:35.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [34:2410:2410:2410:2410:2410]
05-25 13:49:35.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [35:2510:2510:2510:2510:2510]
05-25 13:49:35.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [36:2610:2610:2610:2610:2610]
05-25 13:49:35.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [37:2710:2710:2710:2710:2710]
05-25 13:49:35.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [38:2810:2810:2810:2810:2810]
05-25 13:49:35.317  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [39:2910:2910:2910:2910:2910]
05-25 13:49:35.317  9844  9908 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
,05-25 13:49:35.317  9844  9908 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
05-25 13:49:35.317  9844  9908 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
05-25 13:49:35.317  9844  9908 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,05-25 13:49:35.317  9844  9908 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,05-25 13:49:35.317  9844  9908 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
05-25 13:49:35.317  9844  9908 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
05-25 13:49:35.317  9844  9908 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
05-25 13:49:35.317  9844  9908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [00:11:22:33:44:55]
,05-25 13:49:35.327  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
05-25 13:49:35.327  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port 1
05-25 13:49:35.327  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
05-25 13:49:35.327  9844  9908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
05-25 13:49:35.327  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
05-25 13:49:35.327  9844  9908 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,05-25 13:49:35.327  9844  9908 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
05-25 13:49:35.327  9844  9908 E io.jxcore.node.ConnectionHelper: connect: Callback is null
05-25 13:49:35.327  9844  9925 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 210)
05-25 13:49:35.327  9844  9925 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect: mIsShuttingDown = false
05-25 13:49:35.327  9844  9925 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: createBluetoothSocket 1
05-25 13:49:35.327  9844  9925 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: createBluetoothSocket: given port
,05-25 13:49:35.327  9844  9908 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
05-25 13:49:35.327  9844  9908 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
05-25 13:49:35.327  9844  9908 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
,05-25 13:49:35.327  9844  9908 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,05-25 13:49:35.337  9844  9908 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
,05-25 13:49:35.337  9844  9908 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
05-25 13:49:35.337  9844  9908 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
05-25 13:49:35.337  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
05-25 13:49:35.337  9844  9908 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
,05-25 13:49:35.337  9844  9908 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
05-25 13:49:35.337  9844  9908 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
05-25 13:49:35.337  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,05-25 13:49:35.337  9844  9908 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
05-25 13:49:35.337  9844  9908 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
05-25 13:49:35.337  9844  9908 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
05-25 13:49:35.337  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
05-25 13:49:35.337  9844  9908 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
05-25 13:49:35.337  9844  9908 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
05-25 13:49:35.337  9844  9908 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,05-25 13:49:35.337  9844  9908 V io.jxcore.node.ConnectivityMonitor: start: Already started
05-25 13:49:35.337  9844  9908 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
05-25 13:49:35.337  9844  9908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
05-25 13:49:35.337  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,05-25 13:49:35.337  9844  9925 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: createBluetoothSocketToServiceRecord: Socket created with channel/port 1
05-25 13:49:35.337  9844  9925 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  connect: connecting
,05-25 13:49:35.337  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"A8:81:95:E9:5F:6F"}
,05-25 13:49:35.337  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"A8:81:95:E9:5F:6F"}
,05-25 13:49:35.337  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:35.337  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,05-25 13:49:35.347  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"A8:81:95:E9:5F:6F"}
,05-25 13:49:35.347  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"A8:81:95:E9:5F:6F"}
05-25 13:49:35.347  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:49:35.347  9844  9908 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
05-25 13:49:35.347  9844  9908 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
05-25 13:49:35.347  9844  9908 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,05-25 13:49:35.347  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,05-25 13:49:35.347  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
05-25 13:49:35.347  9844  9908 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,05-25 13:49:35.347  9844  9908 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
05-25 13:49:35.347  9844  9908 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,05-25 13:49:35.347  9844  9844 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
05-25 13:49:35.347  9844  9908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,05-25 13:49:35.347  9844  9908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
05-25 13:49:35.347  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
05-25 13:49:35.347  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
05-25 13:49:35.347  9844  9925 D BluetoothSocket: connect(): myUserId = 0
,05-25 13:49:35.347  9844  9925 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
05-25 13:49:35.347  9844  9926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
05-25 13:49:35.347  9844  9926 D BluetoothSocket: bindListen(): myUserId = 0
05-25 13:49:35.347  9844  9926 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,05-25 13:49:35.357  9844  9926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
,05-25 13:49:35.357  9844  9926 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@9074053, port: 6, type: 1, local socket address: null, socket type: 0
05-25 13:49:35.357  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
05-25 13:49:35.357  9844  9908 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
05-25 13:49:35.357  9844  9908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,05-25 13:49:35.357  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:49:35.357  3487  3505 D SecContentProvider: insert(), uri = 2
,05-25 13:49:35.367  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:49:35.367  4907  5209 W bt_btif : bta_dm_acl_change(), event : 2
,05-25 13:49:35.367  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:49:35.367  3487  3506 V AlarmManager:  remove PendingIntent] PendingIntent{f1fc782: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
,05-25 13:49:35.367  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:49:35.367  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,05-25 13:49:35.367  3487  4670 V AlarmManager:  remove PendingIntent] PendingIntent{fddbe93: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
,05-25 13:49:35.367  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:49:35.377  3487  3506 V AlarmManager:  remove PendingIntent] PendingIntent{a2d1ed0: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
,05-25 13:49:35.377  9844  9908 D BluetoothAdapter: STATE_ON
05-25 13:49:35.377  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
05-25 13:49:35.377  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
05-25 13:49:35.377  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 3
05-25 13:49:35.377  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:49:35.387  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:35.387  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:49:35.387  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
05-25 13:49:35.387  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
05-25 13:49:35.387  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "1e0175e0-0d83-4d02-aa60-d3c622da762e", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
05-25 13:49:35.387  9844  9908 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 A8 81 95 E9 5F 6F
05-25 13:49:35.387  9844  9908 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[3, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,05-25 13:49:35.387  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[3, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-25 13:49:35.387  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:35.387  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[3, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:35.387  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
,05-25 13:49:35.387  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[3, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-25 13:49:35.387  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:35.387  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:35.387  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[3, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:49:35.387  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:49:35.387  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:49:35.387  9844  9908 D BluetoothLeAdvertiser: start advertising
,05-25 13:49:35.387  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:49:35.397  4907  4918 D BtGatt.GattService: registerClient() - UUID=091f0760-628a-4ba3-8ca2-b22dfdde9afe
,05-25 13:49:35.437  4907  5037 D BtGatt.GattService: onClientRegistered() - UUID=091f0760-628a-4ba3-8ca2-b22dfdde9afe, clientIf=7
,05-25 13:49:35.437  9844  9854 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,05-25 13:49:35.437  4907  5371 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,05-25 13:49:35.447  4907  5371 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,05-25 13:49:35.447  4907  5371 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
05-25 13:49:35.447  4907  5071 D BtGatt.AdvertiseManager: message : 0
05-25 13:49:35.447  4907  5081 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
05-25 13:49:35.447  4907  5081 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 25, currDate: 25
05-25 13:49:35.447  4907  5071 D BtGatt.AdvertiseManager: number of adv instance running = 0
05-25 13:49:35.447  4907  5071 D BtGatt.AdvertiseManager: size of list is =0
,05-25 13:49:35.447  4907  5071 D BtGatt.AdvertiseManager: starting advertising
,05-25 13:49:35.447  4907  5071 D BtGatt.AdvertiseManager: isStandardAdv = false
,05-25 13:49:35.457  3487  4065 V AlarmManager:  remove PendingIntent] PendingIntent{979aec9: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
,05-25 13:49:35.457  4907  5037 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,05-25 13:49:35.457  4907  5081 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.thaliproject.thalitest : 30
05-25 13:49:35.457  4907  5081 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.thaliproject.thalitest@LowLatency : 24928549
05-25 13:49:35.457  4907  5081 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.thaliproject.thalitest@LowLatency : 2
05-25 13:49:35.457  4907  5081 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
05-25 13:49:35.457  4907  5081 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 4 => 4
,05-25 13:49:35.457  4907  5071 D BtGatt.AdvertiseManager: starting multi advertising
,05-25 13:49:35.457  4907  5037 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
05-25 13:49:35.457  4907  5071 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,05-25 13:49:35.457  4907  5071 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
05-25 13:49:35.457  4907  5071 D BtGatt.AdvertiseManager: postCallback clientIf = 7 status = 0
05-25 13:49:35.457  4907  5071 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=7, status=0, isStart=true
05-25 13:49:35.457  9844  9855 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
05-25 13:49:35.457  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:49:35.457  3487  4197 V AlarmManager:  remove PendingIntent] PendingIntent{486d9ce: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
05-25 13:49:35.457  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:35.457  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
05-25 13:49:35.457  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:35.457  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:35.457  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:35.457  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:35.457  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:35.457  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
05-25 13:49:35.457  9844  9908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
05-25 13:49:35.457  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:35.457  9844  9908 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: seems that updateState call different BlePeerDiscoverer
,05-25 13:49:35.467  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:35.467  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:35.467  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:35.467  9844  9908 I io.jxcore.node.ConnectionHelper: start: OK
05-25 13:49:35.467  9844  9844 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
05-25 13:49:35.467  3487  4927 V AlarmManager:  remove PendingIntent] PendingIntent{71bb0ef: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
05-25 13:49:35.467  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
05-25 13:49:35.467  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
,05-25 13:49:35.467  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
05-25 13:49:35.467  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
05-25 13:49:35.467  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
05-25 13:49:35.467  9844  9844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
05-25 13:49:35.467  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
05-25 13:49:35.467  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
,05-25 13:49:35.467  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
05-25 13:49:35.467  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
05-25 13:49:35.467  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
05-25 13:49:35.467  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
05-25 13:49:35.467  9844  9844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
05-25 13:49:35.467  9844  9844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,05-25 13:49:35.467  3487  4670 V AlarmManager:  remove PendingIntent] PendingIntent{e8d57fc: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
,05-25 13:49:35.467  9844  9844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
05-25 13:49:35.467  9844  9844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
05-25 13:49:35.467  9844  9844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
05-25 13:49:35.467  9844  9844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
05-25 13:49:35.467  9844  9844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,05-25 13:49:35.477  3487  4417 V AlarmManager:  remove PendingIntent] PendingIntent{be56e85: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
,05-25 13:49:35.477  3487  4947 V AlarmManager:  remove PendingIntent] PendingIntent{83ac4da: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
,05-25 13:49:35.477  3487  3985 V AlarmManager:  remove PendingIntent] PendingIntent{39c6d0b: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
,05-25 13:49:35.487  3487  4196 V AlarmManager:  remove PendingIntent] PendingIntent{455f7e8: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
,05-25 13:49:35.967  9844  9915 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,05-25 13:49:35.967  9844  9908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
05-25 13:49:35.967  9844  9908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
05-25 13:49:35.967  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
05-25 13:49:35.967  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,05-25 13:49:35.967  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
05-25 13:49:35.967  9844  9908 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,05-25 13:49:35.967  9844  9908 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
05-25 13:49:35.967  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
05-25 13:49:35.967  9844  9926 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,05-25 13:49:35.967  9844  9926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
05-25 13:49:35.967  9844  9926 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
05-25 13:49:35.967  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
05-25 13:49:35.967  9844  9908 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f5836c7 removed from the list
05-25 13:49:35.967  9844  9908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f5836c7 removed from the list
,05-25 13:49:35.967  9844  9908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
05-25 13:49:35.967  9844  9908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,05-25 13:49:35.967  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:35.967  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,05-25 13:49:35.967  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,05-25 13:49:35.967  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:35.967  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:49:35.967  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:35.967  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:35.967  9844  9928 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 210
,05-25 13:49:35.967  9844  9928 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
05-25 13:49:35.967  9844  9928 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: closeBluetoothSocket: Trying to close the bluetooth socket... (thread ID: 210)
05-25 13:49:35.967  9844  9844 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
05-25 13:49:35.967  9844  9844 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,05-25 13:49:35.967  9844  9844 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
05-25 13:49:35.967  9844  9844 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
05-25 13:49:35.977  9844  9908 D BluetoothAdapter: STATE_ON
05-25 13:49:35.977  9844  9928 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: closeBluetoothSocket: bluetooth socket closed (thread ID: 210)
05-25 13:49:35.977  4907  5363 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 8, channel: 1
,05-25 13:49:35.977  9844  9925 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  connect: read failed, socket might closed or timeout, read ret: -1
05-25 13:49:35.977  9844  9925 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socket is not connected
05-25 13:49:35.977  9844  9925 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 210)
05-25 13:49:35.977  9844  9908 D BluetoothAdapter: STATE_ON
05-25 13:49:35.977  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,05-25 13:49:35.977  9844  9908 D BluetoothAdapter: STATE_ON
05-25 13:49:35.987  9844  9908 D BluetoothAdapter: STATE_ON
05-25 13:49:35.987  9844  9908 D BluetoothLeScanner: could not find callback wrapper
05-25 13:49:35.987  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,05-25 13:49:35.987  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:35.987  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:35.987  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:35.987  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
05-25 13:49:35.987  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:49:35.987  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:49:35.987  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:49:35.987  9844  9908 D BluetoothLeAdvertiser: stop advertising
,05-25 13:49:35.997  4907  4918 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,05-25 13:49:35.997  4907  4918 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
05-25 13:49:35.997  4907  5071 D BtGatt.AdvertiseManager: message : 1
,05-25 13:49:35.997  4907  5081 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
05-25 13:49:35.997  4907  5081 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 25, currDate: 25
05-25 13:49:35.997  4907  5081 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
05-25 13:49:35.997  4907  5081 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 4 => 4
,05-25 13:49:35.997  4907  5081 D BtGatt.GattService: [GSIM LOG]: remove : com.thaliproject.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
05-25 13:49:36.007  4907  5071 D BtGatt.AdvertiseManager: stop advertise for client =  7
05-25 13:49:36.007  4907  5071 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 7
,05-25 13:49:36.007  4907  5071 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,05-25 13:49:36.007  4907  5037 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
05-25 13:49:36.007  4907  5037 D BtGatt.GattService: Client app is not null!
05-25 13:49:36.007  3487  4670 V AlarmManager:  remove PendingIntent] PendingIntent{f936e01: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
05-25 13:49:36.007  9844  9855 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,05-25 13:49:36.017  4907  5371 D BtGatt.GattService: unregisterClient() - clientIf=7
,05-25 13:49:36.017  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,05-25 13:49:36.017  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:36.017  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,05-25 13:49:36.017  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:36.017  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:36.017  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:49:36.017  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
05-25 13:49:36.017  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
05-25 13:49:36.017  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
05-25 13:49:36.017  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:49:36.027  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:36.027  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
05-25 13:49:36.027  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:36.027  3487  3985 V AlarmManager:  remove PendingIntent] PendingIntent{31054a6: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
05-25 13:49:36.027  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:36.027  9844  9908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2a24f4 removed from the list
05-25 13:49:36.027  9844  9844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
05-25 13:49:36.027  9844  9908 D io.jxcore.node.ConnectivityMonitor: stop
05-25 13:49:36.027  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
05-25 13:49:36.027  9844  9844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
05-25 13:49:36.027  9844  9844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
05-25 13:49:36.027  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
05-25 13:49:36.027  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
05-25 13:49:36.027  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
05-25 13:49:36.027  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
05-25 13:49:36.027  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
05-25 13:49:36.027  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
05-25 13:49:36.027  9844  9844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
05-25 13:49:36.037  3487  3505 V AlarmManager:  remove PendingIntent] PendingIntent{622cee7: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
05-25 13:49:36.047  3487  4920 V AlarmManager:  remove PendingIntent] PendingIntent{586aa94: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
05-25 13:49:36.057  3487  4927 V AlarmManager:  remove PendingIntent] PendingIntent{4c7e93d: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
,05-25 13:49:36.057  3487  3985 V AlarmManager:  remove PendingIntent] PendingIntent{45d1532: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
05-25 13:49:36.067  3487  4408 V AlarmManager:  remove PendingIntent] PendingIntent{ec37283: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
,05-25 13:49:36.527  9844  9844 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,05-25 13:49:41.027  9844  9918 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
,05-25 13:49:41.037  9844  9908 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,05-25 13:49:41.037  9844  9908 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
05-25 13:49:41.037  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,05-25 13:49:41.037  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,05-25 13:49:41.037  9844  9908 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,05-25 13:49:41.037  9844  9908 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
05-25 13:49:41.037  9844  9908 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,05-25 13:49:41.037  9844  9908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
05-25 13:49:41.037  9844  9908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
05-25 13:49:41.037  9844  9844 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,05-25 13:49:41.047  9844  9929 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
05-25 13:49:41.047  9844  9908 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
05-25 13:49:41.047  9844  9908 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [00:11:22:33:44:55], error message: ErrorMessage
,05-25 13:49:41.047  9844  9908 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
05-25 13:49:41.047  9844  9929 D BluetoothSocket: bindListen(): myUserId = 0
05-25 13:49:41.047  9844  9908 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
05-25 13:49:41.047  9844  9929 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
05-25 13:49:41.047  9844  9908 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,05-25 13:49:41.047  9844  9908 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
05-25 13:49:41.057  9844  9929 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
05-25 13:49:41.057  9844  9929 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@4e8968e, port: 6, type: 1, local socket address: null, socket type: 0
,05-25 13:49:41.057  9844  9908 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
,05-25 13:49:41.057  9844  9908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
05-25 13:49:41.057  9844  9908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
05-25 13:49:41.057  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
05-25 13:49:41.057  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,05-25 13:49:41.057  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
05-25 13:49:41.057  9844  9908 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,05-25 13:49:41.057  9844  9908 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
05-25 13:49:41.057  9844  9908 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f5836c7 not in the list
05-25 13:49:41.057  9844  9844 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
05-25 13:49:41.057  9844  9908 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f5836c7 not in the list
,05-25 13:49:41.057  9844  9929 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
05-25 13:49:41.057  9844  9908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
05-25 13:49:41.057  9844  9929 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
05-25 13:49:41.057  9844  9908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
05-25 13:49:41.057  9844  9929 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
05-25 13:49:41.067  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:41.067  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,05-25 13:49:41.067  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
05-25 13:49:41.067  9844  9908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
05-25 13:49:41.067  9844  9844 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
05-25 13:49:41.067  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
05-25 13:49:41.067  9844  9844 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,05-25 13:49:41.067  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:41.067  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:41.067  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
05-25 13:49:41.067  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:49:41.067  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:49:41.067  9844  9908 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2a24f4 not in the list
05-25 13:49:41.067  9844  9844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
05-25 13:49:41.067  9844  9908 D io.jxcore.node.ConnectivityMonitor: stop
05-25 13:49:41.067  9844  9908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
05-25 13:49:41.067  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,05-25 13:49:41.067  9844  9844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
05-25 13:49:41.067  9844  9844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
05-25 13:49:41.067  9844  9908 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
05-25 13:49:41.067  9844  9908 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
05-25 13:49:41.067  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,05-25 13:49:41.067  9844  9908 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
05-25 13:49:41.067  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
05-25 13:49:41.067  9844  9908 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
05-25 13:49:41.067  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,05-25 13:49:41.067  9844  9908 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
,05-25 13:49:41.077  9844  9908 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
,05-25 13:49:41.077  9844  9908 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
,05-25 13:49:41.077  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [incoming]
,05-25 13:49:41.077  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [outgoing]
,05-25 13:49:41.077  9844  9908 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
05-25 13:49:41.077  9844  9908 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
05-25 13:49:41.077  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,05-25 13:49:41.077  9844  9908 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
05-25 13:49:41.077  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
05-25 13:49:41.077  9844  9908 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
05-25 13:49:41.077  9844  9908 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,05-25 13:49:41.077  9844  9908 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
,05-25 13:49:41.077  9844  9908 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
05-25 13:49:41.077  9844  9908 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,05-25 13:49:41.077  9844  9908 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
,05-25 13:49:41.077  9844  9908 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
05-25 13:49:41.077  9844  9908 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
05-25 13:49:41.077  9844  9908 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
05-25 13:49:41.077  9844  9908 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,05-25 13:49:41.087  9844  9908 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
,05-25 13:49:41.087  9844  9908 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,05-25 13:49:41.087  9844  9908 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4bb8eaf added. We now have 2 listener(s)
05-25 13:49:41.087  9844  9908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4bb8eaf added. We now have 3 listener(s)
05-25 13:49:41.087  9844  9908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,05-25 13:49:41.087  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"A8:81:95:E9:5F:6F"}
,05-25 13:49:41.087  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
05-25 13:49:41.087  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"A8:81:95:E9:5F:6F"}
05-25 13:49:41.087  9844  9908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
05-25 13:49:41.087  9844  9908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3af42bc added. We now have 4 listener(s)
05-25 13:49:41.087  9844  9908 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,05-25 13:49:41.087  9844  9908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,05-25 13:49:41.087  9844  9908 D BluetoothAdapter: enable()
,05-25 13:49:41.097  9844  9908 D BluetoothAdapter: enable(): BT is already enabled..!
,05-25 13:49:41.107  3487  3570 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a6ddc00 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bad5c58 4933:com.samsung.android.providers.context/u0a9}
,05-25 13:49:41.107  9844  9908 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,05-25 13:49:41.117  3487  4197 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,05-25 13:49:41.117  3487  4197 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,05-25 13:49:41.117  3487  4197 D WifiService: setWifiEnabled: true pid=9844, uid=10078
,05-25 13:49:41.117  3487  4197 W WifiService: Failed getting userId using ActivityManagerNative
05-25 13:49:41.117  3487  4197 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9844, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-25 13:49:41.117  3487  4197 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-25 13:49:41.117  3487  4197 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
05-25 13:49:41.117  3487  4197 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
05-25 13:49:41.117  3487  4197 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
05-25 13:49:41.117  3487  4197 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
,05-25 13:49:41.117  3487  4197 W ActivityManager: Permission Denial: getCurrentUser() from pid=9844, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-25 13:49:41.117  3487  4197 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
05-25 13:49:41.117  3487  4197 D SettingsProvider: isChangeAllowed() : name = wifi_on
05-25 13:49:41.117  3487  3860 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,05-25 13:49:41.117  3487  3860 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
05-25 13:49:41.117  9844  9908 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
05-25 13:49:41.127  3487  3863 D WifiController: [FCC]setFccChannel() is called !!!
05-25 13:49:41.127  3487  3863 D WifiStateMachine: setFccChannel: channel = 0
05-25 13:49:41.127  3487  3863 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
05-25 13:49:41.127  3487  3860 D WifiBigDataLog: init : 
05-25 13:49:41.127  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:49:41.127  9844  9908 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
05-25 13:49:41.127  3487  3860 D WifiStateMachine: setFccChannelNative: channel = 0
05-25 13:49:41.127  3487  3860 D WifiNative-wlan0: callSECApiInt - ID [230]
,05-25 13:49:41.127  9844  9908 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
,05-25 13:49:41.137  9844  9908 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
05-25 13:49:41.137  3487  3570 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1cedc39 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bad5c58 4933:com.samsung.android.providers.context/u0a9}
,05-25 13:49:41.147  9844  9930 D BluetoothAdapter: disable()
,05-25 13:49:41.147  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:49:41.157  9844  9908 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-25 13:49:41.157  9844  9908 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-25 13:49:41.157  9844  9908 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-25 13:49:41.157  9844  9908 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-25 13:49:41.157  9844  9908 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-25 13:49:41.157  9844  9908 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-25 13:49:41.157  9844  9908 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-25 13:49:41.157  9844  9908 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-25 13:49:41.157  9844  9908 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,05-25 13:49:41.157  3487  3570 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{943527e u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bad5c58 4933:com.samsung.android.providers.context/u0a9}
,05-25 13:49:41.167  3487  3985 D SettingsProvider: isChangeAllowed() : name = bluetooth_on
,05-25 13:49:41.177  3487  3599 D SecContentProvider: insert(), uri = 2
05-25 13:49:41.177  4907  5033 D BluetoothAdapterState: Current state: ON, message: BLE_TURN_OFF
,05-25 13:49:41.177  4907  5033 D BluetoothAdapterProperties: Setting state to 13
05-25 13:49:41.187  4907  5033 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
05-25 13:49:41.187  4907  5033 D BluetoothAdapterService: Bluetooth PBAP supproted is true
05-25 13:49:41.187  4907  5033 D BluetoothAdapterService: updateAdapterState state is 13
,05-25 13:49:41.187  4907  4907 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,05-25 13:49:41.187  3487  3599 D BluetoothManagerService: Turning On/Off, G state: 3, S state: 3, mBLE count: 0, s BLE count: 0
,05-25 13:49:41.187  4907  5033 D BluetoothAdapterService: Autoconnection is available 
,05-25 13:49:41.187  4907  5033 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
05-25 13:49:41.187  4907  5033 D BluetoothAdapterService: terminating service from this receiver
,05-25 13:49:41.187  3487  3487 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
05-25 13:49:41.187  3487  3487 I InputMethodManagerService: [BT Setting State] State =13
,05-25 13:49:41.187  3949  4154 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,05-25 13:49:41.187  3949  4154 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,05-25 13:49:41.187  4348  4348 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
,05-25 13:49:41.197  4862  4862 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,05-25 13:49:41.197  3487  3487 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
05-25 13:49:41.197  3487  3487 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
05-25 13:49:41.197  3487  3487 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,05-25 13:49:41.207  9844  9844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
05-25 13:49:41.207  9844  9844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-25 13:49:41.207  9844  9844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-25 13:49:41.207  9844  9844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-25 13:49:41.207  9844  9844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-25 13:49:41.207  9844  9844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
05-25 13:49:41.207  9844  9844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-25 13:49:41.207  9844  9844 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-25 13:49:41.207  9844  9844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-25 13:49:41.207  9844  9844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,05-25 13:49:41.207  9844  9844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
05-25 13:49:41.207  9844  9844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,05-25 13:49:41.217  9932  9932 E Zygote  : v2
05-25 13:49:41.217  9932  9932 I libpersona: KNOX_SDCARD checking this for 1000
05-25 13:49:41.217  9932  9932 I libpersona: KNOX_SDCARD not a persona
05-25 13:49:41.217  9932  9932 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-25 13:49:41.217  9932  9932 E Zygote  : accessInfo : 0
,05-25 13:49:41.227  3487  3570 I ActivityManager: Start proc 9932:com.android.settings/1000 for broadcast-3 com.android.settings/.bluetooth.DockEventReceiver
,05-25 13:49:41.227  4907  5033 D BluetoothAdapterProperties: onBluetoothDisable()
05-25 13:49:41.227  3949  3949 D BluetoothPbap: Proxy object disconnected
05-25 13:49:41.227  3949  3949 D PbapServerProfile: Bluetooth service disconnected
,05-25 13:49:41.227  4907  5033 W bt_btif : btif_dm_cancel_discovery
,05-25 13:49:41.227  3487  4670 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
,05-25 13:49:41.227  4907  4907 D BleAudioService: onReceive:: INTENT mAobleStateChangeListener got : android.bluetooth.adapter.action.STATE_CHANGED
05-25 13:49:41.227  4907  4907 D BleAudioService: BluetoothAdapter.ACTION_STATE_CHANGED,  state is13
,05-25 13:49:41.237  3487  4407 D SecContentProvider: insert(), uri = 2
,05-25 13:49:41.237  4907  5033 I BluetoothAdapterState: Entering PendingCommandState
,05-25 13:49:41.237  3487  4197 V AlarmManager:  remove PendingIntent] PendingIntent{fd4b82c: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
,05-25 13:49:41.247  4907  5037 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,05-25 13:49:41.247  4907  5037 D BluetoothAdapterProperties: Scan Mode:20
,05-25 13:49:41.247  4907  5033 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BEGIN_DISABLE
,05-25 13:49:41.247  3487  3985 V AlarmManager:  remove PendingIntent] PendingIntent{bb802f5: PendingIntentRecord{cbe188a com.android.bluetooth broadcastIntent}}
,05-25 13:49:41.247  3949  4259 D BluetoothTile: handleUpdateState :  supported = true, enabled = false, enabling = false, connected = false, connecting = false, mController.getLastDeviceName() = null
,05-25 13:49:41.247  4907  5033 E BluetoothServiceJni: disableBrEdrNative:
05-25 13:49:41.247  3487  4927 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
05-25 13:49:41.247  4907  5033 E bt_bluedroid: disable_bredr
05-25 13:49:41.247  4907  5421 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
05-25 13:49:41.247  4907  5034 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
05-25 13:49:41.247  4907  5443 V ObexServerSockets: Accept exception: (expected at shutdown)java.io.IOException: read failed, socket might closed or timeout, read ret: -1
05-25 13:49:41.247  4907  5444 V ObexServerSockets: Accept exception: (expected at shutdown)java.io.IOException: read failed, socket might closed or timeout, read ret: -1
05-25 13:49:41.247  4907  5034 E bt_btif : BTA got event 0x1a03
05-25 13:49:41.247  4907  5443 D ObexServerSockets: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
05-25 13:49:41.247  4907  5444 D ObexServerSockets: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,05-25 13:49:41.257  3949  3949 D QSTileView: handleLabelStateChanged() label = Bluetooth cellWidth 272
,05-25 13:49:41.257  4907  5209 W bt_btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
05-25 13:49:41.257  4907  5209 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,05-25 13:49:41.257  3487  4197 V AlarmManager:  remove PendingIntent] PendingIntent{d26aefb: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
,05-25 13:49:41.257  9844  9844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:49:41.257  4907  5034 D IOP_DB_BT: db_close: nbr users 0
05-25 13:49:41.257  4907  5034 D IOP_DB_BT: db_close: free database
,05-25 13:49:41.267  4907  5209 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,05-25 13:49:41.267  4907  5209 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-25 13:49:41.267  4907  5209 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-25 13:49:41.267  4907  5209 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-25 13:49:41.267  4907  5209 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,05-25 13:49:41.267  4907  5209 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-25 13:49:41.267  4907  5209 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-25 13:49:41.267  4907  5209 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-25 13:49:41.267  4907  5209 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-25 13:49:41.267  4907  5209 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-25 13:49:41.267  4907  5209 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,05-25 13:49:41.267  4907  5209 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-25 13:49:41.267  4907  5209 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,05-25 13:49:41.267  4907  5209 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-25 13:49:41.267  4907  5209 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-25 13:49:41.277  4907  5209 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x2  CID 0x40
05-25 13:49:41.277  4907  5209 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 8
05-25 13:49:41.277  4907  5209 W bt_btif : bta_dm_acl_change(), event : 2
05-25 13:49:41.277  4907  5209 W bt_btif : bta_dm_acl_change(), event : 5
,05-25 13:49:41.277  9932  9932 D TimaKeyStoreProvider: TimaSignature is unavailable
,05-25 13:49:41.277  3487  4927 V AlarmManager:  remove PendingIntent] PendingIntent{3eb2b18: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
05-25 13:49:41.277  9932  9932 D ActivityThread: Added TimaKeyStore provider
05-25 13:49:41.287  4907  4907 D ObexServerSockets: shutdown(block = true)
05-25 13:49:41.287  4907  4907 D ObexServerSockets: shutdown called from another thread - interrupt().
05-25 13:49:41.287  4907  4907 D ObexServerSockets: shutdown called from another thread - interrupt().
,05-25 13:49:41.287  4907  4907 D BluetoothSdpJni: sdpRemoveSdpRecordNative:
,05-25 13:49:41.287  4907  5033 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5359fd5
,05-25 13:49:41.287  4907  5037 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:11:22:33:44:55, value is empty for type: 1
,05-25 13:49:41.297  4907  4907 D BluetoothSdpJni: SDP Remove record success - handle: 1
,05-25 13:49:41.297  4907  4907 D BluetoothSdpJni: sdpRemoveSdpRecordNative:
,05-25 13:49:41.297  4907  4907 D BluetoothSdpJni: SDP Remove record success - handle: 0
05-25 13:49:41.297  4907  4907 I BtOppRfcommListener: stopping Accept Thread
,05-25 13:49:41.297  3487  4920 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ed2d971 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c6d3356 9932:com.android.settings/1000}
,05-25 13:49:41.297  4907  5421 I BtOppRfcommListener: BluetoothSocket listen thread finished
,05-25 13:49:41.297  3949  4154 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CLASS_CHANGED
,05-25 13:49:41.297  4907  5037 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
05-25 13:49:41.297  4907  5037 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:11:22:33:44:55, value is empty for type: 241
,05-25 13:49:41.307  4907  4907 V BluetoothOppManager: cleanUp...
,05-25 13:49:41.307  9932  9932 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,05-25 13:49:41.307  9932  9932 D RelationGraph: garbageCollect()
,05-25 13:49:41.317  9932  9932 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in com.android.settings rsrc of package com.android.settings
,05-25 13:49:41.317  3487  4197 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-25 13:49:41.317  9932  9932 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-25 13:49:41.317  9932  9932 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:49:41.327  9932  9932 I InjectionManager: Inside getClassLibPath caller 
,05-25 13:49:41.347  9932  9932 W System  : ClassLoader referenced unknown path: /system/priv-app/SecSettings2/lib/arm64
,05-25 13:49:41.357  9932  9932 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in com.android.settings rsrc of package com.android.settings
,05-25 13:49:41.357  9932  9932 D SFinderConnectProvider: onCreate
,05-25 13:49:41.407  9932  9932 I BNRClientProivder, VERSION : 1.7.5: register - xml6 quick_backup : ACCESSIBILITYSETTINGS, X6qErjsfs2, com.android.settings.accessibility.sharedaccessibility.scloud.BNRTask
,05-25 13:49:41.407  9932  9932 I QBNRClientHelper: init SyncClientHelper : ACCESSIBILITYSETTINGS
,05-25 13:49:41.407  9932  9932 I BNRClientProivder, VERSION : 1.7.5: register - xml6 quick_backup : CONNECTIONS, C0phMaUuZZ, com.android.settings.wifi.mobileap.WifiApBackupRestore
05-25 13:49:41.407  9932  9932 I QBNRClientHelper: init SyncClientHelper : CONNECTIONS
05-25 13:49:41.407  9932  9932 I BNRClientProivder, VERSION : 1.7.5: register - xml6 quick_backup : WiFi, C0phMaUuZZ, com.android.settings.wifi.WifiBackupRestore
05-25 13:49:41.407  9932  9932 I QBNRClientHelper: init SyncClientHelper : WiFi
,05-25 13:49:41.417  9932  9932 D InjectionManager: InjectionManager
,05-25 13:49:41.417  9932  9932 D InjectionManager: fillFeatureStoreMap com.android.settings
05-25 13:49:41.417  9932  9932 I InjectionManager: Constructor com.android.settings, Feature store :{}
05-25 13:49:41.417  9932  9932 I InjectionManager: featureStore :{}
,05-25 13:49:41.427  9932  9932 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,05-25 13:49:41.447  9932  9932 D LocalBluetoothManager: LocalBluetoothManager :: sInstance == null
,05-25 13:49:41.457  4907  5037 E BluetoothAdapterState: stateChangeCallback : 16
,05-25 13:49:41.457  3487  4670 V AlarmManager:  remove PendingIntent] PendingIntent{2ea9bad: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
,05-25 13:49:41.457  4907  5033 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_NATIVE_STOPED
,05-25 13:49:41.457  9932  9932 D LocalBluetoothManager: LocalBluetoothManager :: constructor
,05-25 13:49:41.467  9932  9932 D BluetoothEventManager: BluetoothEventManager Constructor :: 
,05-25 13:49:41.467  3487  3980 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ed2d971 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bad5c58 4933:com.samsung.android.providers.context/u0a9}
,05-25 13:49:41.487  3487  3980 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ed2d971 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a95ad21 4274:com.google.android.gms.persistent/u0a21}
,05-25 13:49:41.487  4274  4274 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
,05-25 13:49:41.497  4907  5033 D BtConfig.SecureMode: isSecureModeOn:false
,05-25 13:49:41.497  4907  5033 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,05-25 13:49:41.507  9932  9932 D LocalBluetoothProfileManager: PANU : true
,05-25 13:49:41.507  3487  3980 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ed2d971 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{78dd1e5 8981:com.sec.android.app.shealth:remote/u0a39}
,05-25 13:49:41.517  4907  5033 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,05-25 13:49:41.527  4907  4907 D HeadsetService: Received stop request...Stopping profile...
,05-25 13:49:41.537  3487  3980 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ed2d971 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c6d3356 9932:com.android.settings/1000}
,05-25 13:49:41.537  4907  4907 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Message sending
05-25 13:49:41.547  4907  4907 E HeadsetService: notifyProfileServiceStateChanged
,05-25 13:49:41.547  4907  5033 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,05-25 13:49:41.547  9932  9932 D BluetoothSap: Create BluetoothSap proxy object
,05-25 13:49:41.547  3949  3949 D HeadsetProfile: Bluetooth service disconnected
,05-25 13:49:41.547  3487  3487 D BluetoothHeadset: unRegisterMessageListener : 11
05-25 13:49:41.547  3487  3487 W BluetoothHeadset: Proxy not attached to service
05-25 13:49:41.547  3487  3487 I Telecom : BluetoothManager : unregister MessageListener
05-25 13:49:41.547  3487  3487 I Telecom : CallAudioManager: onBluetoothStateChange: no focus
,05-25 13:49:41.547  4907  4907 E BluetoothAdapterService: handleMessage() - Message: 1
05-25 13:49:41.547  4907  4907 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Before synchronized
,05-25 13:49:41.557  4907  5033 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,05-25 13:49:41.557  4907  4907 V BluetoothAdapterState: isTurningOff()=true
05-25 13:49:41.557  4907  4907 V BluetoothAdapterState: isTurningOn()=false
05-25 13:49:41.557  4907  4907 V BluetoothAdapterState: isBleTurningOn()=false
05-25 13:49:41.557  4907  4907 V BluetoothAdapterState: isBleTurningOff()=false
,05-25 13:49:41.557  4907  4907 D A2dpService: Received stop request...Stopping profile...
05-25 13:49:41.557  4907  5033 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,05-25 13:49:41.557  9932  9932 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
05-25 13:49:41.557  9932  9932 D LocalBluetoothManager: LocalBluetoothManager :: onInitCallback != null
,05-25 13:49:41.557  4907  5324 D A2dpStateMachine: Exit Disconnected: -1
,05-25 13:49:41.557  4907  5033 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
05-25 13:49:41.557  4907  4907 D Avrcp   : unregisterContentObserver
05-25 13:49:41.557  4907  4907 D Avrcp   : removeOnActiveSessionsChangedListener
,05-25 13:49:41.567  4907  4907 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Message sending
05-25 13:49:41.567  4907  4907 E A2dpService: notifyProfileServiceStateChanged
,05-25 13:49:41.567  4907  5033 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
05-25 13:49:41.567  3487  3487 D BluetoothA2dp: Proxy object disconnected
,05-25 13:49:41.567  3949  3949 D BluetoothA2dp: Proxy object disconnected
05-25 13:49:41.567  3949  3949 D A2dpProfile: Bluetooth service disconnected
05-25 13:49:41.567  4933  4933 D BluetoothA2dp: Proxy object disconnected
,05-25 13:49:41.567  4907  5033 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
05-25 13:49:41.567  4907  5033 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
05-25 13:49:41.567  4907  5033 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
05-25 13:49:41.567  4907  5033 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
05-25 13:49:41.567  4907  5033 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.bleaudio.BleAudioService
,05-25 13:49:41.577  9932  9932 D DockEventReceiver: finishStartingService: stopping service
,05-25 13:49:41.577  9844  9844 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
05-25 13:49:41.577  9932  9932 D BluetoothPan: BluetoothPAN Proxy object connected
05-25 13:49:41.577  9932  9932 D PanProfile: Bluetooth service connected
05-25 13:49:41.577  9932  9932 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
05-25 13:49:41.577  9932  9932 D BluetoothStatusReceiver: AdapterStateChanged :: state = 13
05-25 13:49:41.577  9932  9932 D BluetoothSap: Proxy object connected
,05-25 13:49:41.577  9932  9932 D SapProfile: Bluetooth service connected
,05-25 13:49:41.587  4907  4907 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,05-25 13:49:41.587  4907  4907 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
05-25 13:49:41.587  4907  4907 D HeadsetProvider: cleanup
05-25 13:49:41.587  4907  4907 I HeadsetProvider: clearAllHeadsetSettings(0)
,05-25 13:49:41.597  3487  3985 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ed2d971 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b5595e1 4907:com.android.bluetooth/1002}
,05-25 13:49:41.607  3487  4920 I ActivityManager: Killing 9120:com.samsung.android.sm.devicesecurity/5012 (adj 15): DHA:empty #33
,05-25 13:49:41.607  4907  4907 D HidService: Received stop request...Stopping profile...
,05-25 13:49:41.607  4907  4907 D HidService: Stopping Bluetooth HidService
05-25 13:49:41.607  4907  4907 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
05-25 13:49:41.607  4907  4907 W bt_btif : cleanup: HH disabling or disabled already, status = 0
05-25 13:49:41.607  4907  4907 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
05-25 13:49:41.607  4907  4907 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, Message sending
05-25 13:49:41.607  4907  4907 E HidService: notifyProfileServiceStateChanged
,05-25 13:49:41.617  3949  3949 D BluetoothInputDevice: Proxy object disconnected
,05-25 13:49:41.617  3949  3949 D HidProfile: Bluetooth service disconnected
,05-25 13:49:41.617  4907  4907 D HealthService: Received stop request...Stopping profile...
,05-25 13:49:41.617  4907  4907 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, Message sending
05-25 13:49:41.617  4907  4907 E HealthService: notifyProfileServiceStateChanged
,05-25 13:49:41.617  4907  4907 D PanService: Received stop request...Stopping profile...
,05-25 13:49:41.617  4907  4907 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, Message sending
05-25 13:49:41.617  4907  4907 E PanService: notifyProfileServiceStateChanged
,05-25 13:49:41.617  3487  3487 D BluetoothPan: BluetoothPAN Proxy object disconnected
05-25 13:49:41.617  3949  3949 D BluetoothPan: BluetoothPAN Proxy object disconnected
,05-25 13:49:41.617  3949  3949 D PanProfile: Bluetooth service disconnected
05-25 13:49:41.617  9932  9932 D BluetoothPan: BluetoothPAN Proxy object disconnected
05-25 13:49:41.617  9932  9932 D PanProfile: Bluetooth service disconnected
05-25 13:49:41.617  4907  4907 E BluetoothAdapterService: handleMessage() - Message: 1
,05-25 13:49:41.617  4907  4907 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Before synchronized
05-25 13:49:41.617  4907  4907 V BluetoothAdapterState: isTurningOff()=true
05-25 13:49:41.617  4907  4907 V BluetoothAdapterState: isTurningOn()=false
05-25 13:49:41.617  4907  4907 V BluetoothAdapterState: isBleTurningOn()=false
05-25 13:49:41.617  4907  4907 V BluetoothAdapterState: isBleTurningOff()=false
,05-25 13:49:41.627  4907  4907 D BluetoothMapService: Received stop request...Stopping profile...
,05-25 13:49:41.627  3487  4196 D ActivityManager: cleanUpApplicationRecord -- 9120
,05-25 13:49:41.627  3487  4196 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sm.devicesecurity, Auto Run ON
,05-25 13:49:41.637  4907  4907 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Message sending
05-25 13:49:41.637  4907  4907 E BluetoothMapService: notifyProfileServiceStateChanged
,05-25 13:49:41.637  3949  3949 D BluetoothMap: Proxy object disconnected
05-25 13:49:41.637  3949  3949 D MapProfile: Bluetooth service disconnected
,05-25 13:49:41.637  4907  4907 D SapService: Received stop request...Stopping profile...
05-25 13:49:41.637  4907  4907 V SapService: stop()
,05-25 13:49:41.647  4907  4907 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=10, Message sending
05-25 13:49:41.647  4907  4907 E SapService: notifyProfileServiceStateChanged
,05-25 13:49:41.647  3949  3949 D BluetoothSap: Proxy object disconnected
,05-25 13:49:41.647  3949  3949 D SapProfile: Bluetooth service disconnected
05-25 13:49:41.647  9932  9932 D BluetoothSap: Proxy object disconnected
05-25 13:49:41.647  9932  9932 D SapProfile: Bluetooth service disconnected
,05-25 13:49:41.647  4907  4907 D BleAudioService: Received stop request...Stopping profile...
05-25 13:49:41.647  4907  4907 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.broadcom.bt.service.bleaudio.BleAudioService, state=10, Message sending
05-25 13:49:41.647  4907  5355 E BleAudioStateMachine_L: Exit Disconnected: -1
,05-25 13:49:41.647  4907  5356 E BleAudioStateMachine_R: Exit Disconnected: -1
05-25 13:49:41.647  4907  4907 E BleAudioService: notifyProfileServiceStateChanged
,05-25 13:49:41.647  3949  3949 D BluetoothLeAudio: Proxy object disconnected
,05-25 13:49:41.647  3949  3949 D BleAudioProfile: Bluetooth service disconnected
,05-25 13:49:41.647  4907  4907 E BluetoothAdapterService: handleMessage() - Message: 1
,05-25 13:49:41.647  4907  4907 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, Before synchronized
,05-25 13:49:41.657  4907  4907 V BluetoothAdapterState: isTurningOff()=true
,05-25 13:49:41.657  4907  4907 V BluetoothAdapterState: isTurningOn()=false
05-25 13:49:41.657  4907  4907 V BluetoothAdapterState: isBleTurningOn()=false
05-25 13:49:41.657  4907  4907 V BluetoothAdapterState: isBleTurningOff()=false
05-25 13:49:41.657  4907  4907 D BluetoothAdapterService: HID Host service will be diabled
,05-25 13:49:41.657  3487  3985 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ed2d971 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2bf0927 7227:com.google.android.apps.maps/u0a125}
,05-25 13:49:41.667  4907  4907 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,05-25 13:49:41.667  4907  4907 E BluetoothAdapterService: handleMessage() - Message: 1
05-25 13:49:41.667  4907  4907 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, Before synchronized,
05-25 13:49:41.667  4907  4907 V BluetoothAdapterState: isTurningOff()=true
05-25 13:49:41.667  4907  4907 V BluetoothAdapterState: isTurningOn()=false
,05-25 13:49:41.667  4907  4907 V BluetoothAdapterState: isBleTurningOn()=false
05-25 13:49:41.667  4907  4907 V BluetoothAdapterState: isBleTurningOff()=false
,05-25 13:49:41.667  4907  4907 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,05-25 13:49:41.667  4907  4907 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,05-25 13:49:41.667  4907  4907 E BluetoothAdapterService: handleMessage() - Message: 1
05-25 13:49:41.667  4907  4907 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, Before synchronized
05-25 13:49:41.667  4907  4907 V BluetoothAdapterState: isTurningOff()=true
05-25 13:49:41.667  4907  4907 V BluetoothAdapterState: isTurningOn()=false
05-25 13:49:41.667  4907  4907 V BluetoothAdapterState: isBleTurningOn()=false
,05-25 13:49:41.667  4907  4907 V BluetoothAdapterState: isBleTurningOff()=false
05-25 13:49:41.677  4907  4907 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
05-25 13:49:41.677  4907  4907 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,05-25 13:49:41.677  4907  4907 E BluetoothAdapterService: handleMessage() - Message: 1
,05-25 13:49:41.677  4907  4907 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Before synchronized
,05-25 13:49:41.677  4907  4907 V BluetoothAdapterState: isTurningOff()=true
05-25 13:49:41.677  4907  4907 V BluetoothAdapterState: isTurningOn()=false
05-25 13:49:41.677  4907  4907 V BluetoothAdapterState: isBleTurningOn()=false
05-25 13:49:41.677  4907  4907 V BluetoothAdapterState: isBleTurningOff()=false
,05-25 13:49:41.677  4907  4907 E BluetoothAdapterService: handleMessage() - Message: 1
05-25 13:49:41.677  4907  4907 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=10, Before synchronized
,05-25 13:49:41.677  9844  9930 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
05-25 13:49:41.677  9844  9930 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-25 13:49:41.677  9844  9930 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-25 13:49:41.677  9844  9930 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-25 13:49:41.677  9844  9930 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-25 13:49:41.677  9844  9930 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
05-25 13:49:41.677  9844  9930 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-25 13:49:41.677  9844  9930 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-25 13:49:41.677  9844  9930 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-25 13:49:41.677  9844  9930 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,05-25 13:49:41.677  4907  4907 V BluetoothAdapterState: isTurningOff()=true
05-25 13:49:41.677  4907  4907 V BluetoothAdapterState: isTurningOn()=false
,05-25 13:49:41.677  4907  4907 V BluetoothAdapterState: isBleTurningOn()=false
05-25 13:49:41.677  4907  4907 V BluetoothAdapterState: isBleTurningOff()=false
,05-25 13:49:41.687  4907  4907 E BluetoothAdapterService: handleMessage() - Message: 1
05-25 13:49:41.687  9844  9930 D BluetoothAdapter: enable()
05-25 13:49:41.687  4907  4907 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.bleaudio.BleAudioService, state=10, Before synchronized
,05-25 13:49:41.687  4907  4907 V BluetoothAdapterState: isTurningOff()=true
05-25 13:49:41.687  4907  4907 V BluetoothAdapterState: isTurningOn()=false
05-25 13:49:41.687  4907  4907 V BluetoothAdapterState: isBleTurningOn()=false
,05-25 13:49:41.687  4907  4907 V BluetoothAdapterState: isBleTurningOff()=false
05-25 13:49:41.687  9844  9908 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
05-25 13:49:41.687  4907  5033 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_STOPPED
05-25 13:49:41.687  4907  4907 V BleAudioService: [unregisterCallStateListener]
,05-25 13:49:41.687  4907  4907 W BtBleAudio.JNI: WARNING: cleanupNative(L385): Cleaning up  Ble audio left callback object##
05-25 13:49:41.687  4907  4907 W BtBleAudio.JNI: WARNING: cleanupNative(L403): Cleaning up Ble audio Interface...##
05-25 13:49:41.687  4907  4907 W BtBleAudio.JNI: WARNING: cleanupNative(L391): Cleaning up  Ble audio right callback object##
05-25 13:49:41.687  4907  4907 V BleAudioService: [unregisterAobleStateChangeListener] Unregistering mAobleStateChangeListener
05-25 13:49:41.687  3487  3506 W ActivityManager: Permission Denial: getCurrentUser() from pid=9844, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
,05-25 13:49:41.697  3487  3506 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
05-25 13:49:41.697  3487  3506 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9844, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-25 13:49:41.697  3487  3506 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-25 13:49:41.697  3487  3506 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2852)
05-25 13:49:41.697  3487  3506 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2842)
05-25 13:49:41.697  3487  3506 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.setBtEnableFlag(BluetoothManagerService.java:1222)
05-25 13:49:41.697  3487  3506 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:254)
05-25 13:49:41.697  3487  3506 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:453)
,05-25 13:49:41.697  3487  3506 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
05-25 13:49:41.697  3487  3506 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,05-25 13:49:41.697  3487  3570 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4f302f4 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bad5c58 4933:com.samsung.android.providers.context/u0a9}
,05-25 13:49:41.697  4907  5033 D BluetoothAdapterProperties: Setting state to 15
05-25 13:49:41.697  4907  5033 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,05-25 13:49:41.697  3487  3506 D SettingsProvider: isChangeAllowed() : name = bluetooth_on
,05-25 13:49:41.697  4907  5033 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,05-25 13:49:41.697  4907  5033 D BluetoothAdapterService: updateAdapterState state is 15
05-25 13:49:41.697  9844  9930 D BluetoothAdapter: BT is in BLE_ON State or TURNING_OFF state
05-25 13:49:41.707  4907  5033 D BluetoothAdapterService: Autoconnection is available 
05-25 13:49:41.707  4907  5033 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 15
05-25 13:49:41.707  4907  5033 I BluetoothAdapterState: Entering BleOnState
,05-25 13:49:41.717  9844  9855 D BluetoothAdapter: onBluetoothStateChange: up=false
,05-25 13:49:41.717  9844  9855 D BluetoothAdapter: Bluetooth is turned off, stop adv
05-25 13:49:41.717  9844  9855 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
05-25 13:49:41.717  9844  9855 D BluetoothLeAdvertiser: Exit stop advertising
05-25 13:49:41.717  4907  5033 D BluetoothAdapterState: Current state: BLE ON, message: USER_TURN_ON
,05-25 13:49:41.717  9844  9855 D BluetoothAdapter: There are no active google scan apps, stop scan
,05-25 13:49:41.717  9844  9855 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
05-25 13:49:41.717  9844  9855 D BluetoothLeScanner: Exiting stopAllScan
,05-25 13:49:41.717  9932  9942 D BluetoothSap: onBluetoothStateChange: up=false
,05-25 13:49:41.727  4907  5033 D BluetoothAdapterProperties: Setting state to 11
,05-25 13:49:41.727  4907  5033 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
05-25 13:49:41.727  3487  3599 D BluetoothA2dp: onBluetoothStateChange: up=false
05-25 13:49:41.727  4907  5033 D BluetoothAdapterService: Bluetooth PBAP supproted is true
05-25 13:49:41.727  4907  5033 D BluetoothAdapterService: updateAdapterState state is 11
,05-25 13:49:41.727  4907  5033 D BluetoothAdapterService: Autoconnection is available 
05-25 13:49:41.727  3949  3970 D BluetoothMap: onBluetoothStateChange: up=false
05-25 13:49:41.727  4907  5033 D BluetoothAdapterService: updateAdapterState prevState = 15newState = 11
05-25 13:49:41.727  4907  5033 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
05-25 13:49:41.727  4907  5033 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
,05-25 13:49:41.727  4907  5033 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,05-25 13:49:41.727  4300  4311 D BluetoothAdapter: onBluetoothStateChange: up=false
,05-25 13:49:41.727  4300  4311 D BluetoothAdapter: Bluetooth is turned off, stop adv
,05-25 13:49:41.727  4300  4311 D BluetoothAdapter: There are no active google scan apps, stop scan
,05-25 13:49:41.727  9932  9943 D BluetoothPan: onBluetoothStateChange on: false
,05-25 13:49:41.737  4907  5033 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,05-25 13:49:41.747  3949  4600 D BluetoothSap: onBluetoothStateChange: up=false
,05-25 13:49:41.747  4907  4907 D HeadsetService: Received start request. Starting profile...
05-25 13:49:41.747  4907  4907 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5359fd5
05-25 13:49:41.747  4907  4907 D HeadsetProvider: make
,05-25 13:49:41.747  4907  4907 D HeadsetProvider: HeadsetProvider
05-25 13:49:41.747  4907  4907 I HeadsetProvider: clearAllHeadsetSettings(0)
,05-25 13:49:41.747  4907  5033 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,05-25 13:49:41.747  4907  4907 D HeadsetStateMachine: make
,05-25 13:49:41.757  4907  4907 E HeadsetStateMachine: # of Max HF connection is 3
,05-25 13:49:41.757  4907  5033 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,05-25 13:49:41.757  4315  4599 D BluetoothAdapter: onBluetoothStateChange: up=false
05-25 13:49:41.757  4315  4599 D BluetoothAdapter: Bluetooth is turned off, stop adv
,05-25 13:49:41.757  4315  4599 D BluetoothAdapter: There are no active google scan apps, stop scan
,05-25 13:49:41.757  4274  5844 D BluetoothAdapter: onBluetoothStateChange: up=false
05-25 13:49:41.757  4274  5844 D BluetoothAdapter: Bluetooth is turned off, stop adv
,05-25 13:49:41.757  4274  5844 D BluetoothAdapter: There are no active google scan apps, stop scan
,05-25 13:49:41.757  4274  5844 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
05-25 13:49:41.757  4274  5844 D BluetoothLeScanner: Exiting stopAllScan
,05-25 13:49:41.767  3949  3974 D BluetoothAdapter: onBluetoothStateChange: up=false
05-25 13:49:41.767  3949  3974 D BluetoothAdapter: Bluetooth is turned off, stop adv
05-25 13:49:41.767  3949  3974 D BluetoothAdapter: There are no active google scan apps, stop scan
,05-25 13:49:41.767  8981  8993 D BluetoothAdapter: onBluetoothStateChange: up=false
05-25 13:49:41.767  8981  8993 D BluetoothAdapter: Bluetooth is turned off, stop adv
,05-25 13:49:41.767  8981  8993 D BluetoothAdapter: There are no active google scan apps, stop scan
,05-25 13:49:41.767  3487  3599 D BluetoothPan: onBluetoothStateChange on: false
05-25 13:49:41.767  4907  5033 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,05-25 13:49:41.777  4907  4918 D BluetoothAdapter: onBluetoothStateChange: up=false
05-25 13:49:41.777  4907  4918 D BluetoothAdapter: Bluetooth is turned off, stop adv
,05-25 13:49:41.777  4907  4918 D BluetoothAdapter: There are no active google scan apps, stop scan
,05-25 13:49:41.777  3949  4112 D BluetoothInputDevice: onBluetoothStateChange: up=false
,05-25 13:49:41.777  4907  5033 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,05-25 13:49:41.777  4907  4907 I bt_bluedroid: get_profile_interface handsfree
,05-25 13:49:41.777  4933  4954 D BluetoothA2dp: onBluetoothStateChange: up=false
,05-25 13:49:41.787  4907  5033 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
,05-25 13:49:41.797  3949  6326 D BluetoothLeAudio: onBluetoothStateChange: up=false
,05-25 13:49:41.797  3949  6326 D BluetoothLeAudio: Unbinding service...
05-25 13:49:41.797  3487  3599 D BluetoothAdapter: onBluetoothStateChange: up=false
05-25 13:49:41.797  3487  3599 D BluetoothAdapter: Bluetooth is turned off, stop adv
05-25 13:49:41.797  3487  3599 D BluetoothAdapter: There are no active google scan apps, stop scan
05-25 13:49:41.797  3949  5577 D BluetoothPbap: onBluetoothStateChange: up=false
,05-25 13:49:41.797  4907  5033 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
05-25 13:49:41.797  4907  5033 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,05-25 13:49:41.797  4907  4907 E DualScoManager: Dual Sco Manager already instantiated
05-25 13:49:41.797  4907  4907 I DualScoManager: Set HeadsetServiceHelper
05-25 13:49:41.797  4907  5033 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
05-25 13:49:41.797  4907  4907 D BluetoothAtMessage: createCMTIContentObservers
05-25 13:49:41.797  4907  5033 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
05-25 13:49:41.797  4907  5033 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.bleaudio.BleAudioService
,05-25 13:49:41.797  9932  9942 D BluetoothAdapter: onBluetoothStateChange: up=false
05-25 13:49:41.797  9932  9942 D BluetoothAdapter: Bluetooth is turned off, stop adv
05-25 13:49:41.797  9932  9942 D BluetoothAdapter: There are no active google scan apps, stop scan
05-25 13:49:41.797  3949  3970 D BluetoothA2dp: onBluetoothStateChange: up=false
,05-25 13:49:41.807  4907  5033 I BluetoothAdapterState: Entering PendingCommandState
,05-25 13:49:41.807  7227  7238 D BluetoothAdapter: onBluetoothStateChange: up=false
05-25 13:49:41.807  7227  7238 D BluetoothAdapter: Bluetooth is turned off, stop adv
05-25 13:49:41.807  4907  5033 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5359fd5
,05-25 13:49:41.807  7227  7238 D BluetoothAdapter: There are no active google scan apps, stop scan
,05-25 13:49:41.817  3949  4600 D BluetoothPan: onBluetoothStateChange on: false
,05-25 13:49:41.817  3487  3570 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2b5e451 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bad5c58 4933:com.samsung.android.providers.context/u0a9}
,05-25 13:49:41.817  4907  4907 D HeadsetProvider: Created cursor android.database.sqlite.SQLiteCursor@41d8129
,05-25 13:49:41.817  4907  4907 D HeadsetProvider: setHeadsetDB - Can't find 300 for A8:81:95:E9:5F:XX
,05-25 13:49:41.827  4933  4946 D BluetoothAdapter: onBluetoothStateChange: up=false
05-25 13:49:41.827  4933  4946 D BluetoothAdapter: Bluetooth is turned off, stop adv
,05-25 13:49:41.827  4933  4946 D BluetoothAdapter: There are no active google scan apps, stop scan
,05-25 13:49:41.827  4907  5033 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: USER_TURN_OFF
,05-25 13:49:41.827  3487  3599 D BluetoothManagerService: Turning On/Off, G state: 3, S state: 3, mBLE count: 0, s BLE count: 0
05-25 13:49:41.827  4907  4907 I HeadsetProvider: setHeadsetDB - A8:81:95:E9:5F:XX, 300, 1, true
,05-25 13:49:41.827  4907  5033 I BluetoothAdapterState: Deferring USER_TURN_OFF request...
05-25 13:49:41.827  3487  3487 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,05-25 13:49:41.827  3487  3487 I InputMethodManagerService: [BT Setting State] State =10
05-25 13:49:41.827  3487  3487 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,05-25 13:49:41.837  3949  4154 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,05-25 13:49:41.837  3949  4154 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
05-25 13:49:41.837  4348  4348 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
,05-25 13:49:41.837  4862  4862 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,05-25 13:49:41.837  3487  3487 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
05-25 13:49:41.837  3487  3487 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
05-25 13:49:41.837  3487  3487 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,05-25 13:49:41.837  9932  9932 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,05-25 13:49:41.837  9932  9932 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,05-25 13:49:41.847  9844  9844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:49:41.847  3487  3570 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{aa914b6 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c6d3356 9932:com.android.settings/1000}
,05-25 13:49:41.847  4348  4348 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
,05-25 13:49:41.847  4862  4862 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,05-25 13:49:41.857  3487  3487 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,05-25 13:49:41.857  3487  3487 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
05-25 13:49:41.857  3487  3487 I InputMethodManagerService: [BT Setting State] State =11
05-25 13:49:41.857  3487  3487 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
05-25 13:49:41.857  3487  3487 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,05-25 13:49:41.857  9844  9844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:49:41.857  3949  4259 D BluetoothTile: handleUpdateState :  supported = true, enabled = false, enabling = false, connected = false, connecting = false, mController.getLastDeviceName() = null
05-25 13:49:41.857  3949  4154 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
05-25 13:49:41.857  3949  4154 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,05-25 13:49:41.857  3487  4927 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,05-25 13:49:41.867  9932  9932 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,05-25 13:49:41.867  4907  4907 D HeadsetProvider: Created cursor android.database.sqlite.SQLiteCursor@bbf95dc
,05-25 13:49:41.867  4907  4907 D HeadsetProvider: setHeadsetDB - Can't find 400 for A8:81:95:E9:5F:XX
,05-25 13:49:41.867  3949  4259 D BluetoothTile: handleUpdateState :  supported = true, enabled = false, enabling = true, connected = false, connecting = false, mController.getLastDeviceName() = null
,05-25 13:49:41.877  3487  4417 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,05-25 13:49:41.877  3949  3949 D QSTileView: handleLabelStateChanged() label = Bluetooth cellWidth 272
05-25 13:49:41.877  9932  9932 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
05-25 13:49:41.877  9932  9932 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,05-25 13:49:41.877  4907  4907 I HeadsetProvider: setHeadsetDB - A8:81:95:E9:5F:XX, 400, 1, true
,05-25 13:49:41.877  4907  9949 D HeadsetStateMachine: Enter Disconnected: -2, size: 0/0
,05-25 13:49:41.877  3487  3505 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{aa914b6 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bad5c58 4933:com.samsung.android.providers.context/u0a9}
,05-25 13:49:41.887  9932  9932 D DockEventReceiver: finishStartingService: stopping service
,05-25 13:49:41.897  3487  4947 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{aa914b6 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a95ad21 4274:com.google.android.gms.persistent/u0a21}
,05-25 13:49:41.897  4274  4274 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
,05-25 13:49:41.897  4907  4907 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Message sending
05-25 13:49:41.897  4907  4907 E HeadsetService: notifyProfileServiceStateChanged
,05-25 13:49:41.897  4907  4907 D A2dpService: Received start request. Starting profile...
05-25 13:49:41.897  4907  4907 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5359fd5
05-25 13:49:41.897  4907  4907 I bt_bluedroid: get_profile_interface avrcp
,05-25 13:49:41.897  4907  9949 D HeadsetStateMachine: Clear mHeadsetBrsf
05-25 13:49:41.897  4907  9949 D HeadsetStateMachine: map size, before remove : 0
05-25 13:49:41.897  4907  9949 D HeadsetStateMachine: map size, after remove: 0
,05-25 13:49:41.907  4907  4907 I Avrcp   : No of Audio players :: 1
05-25 13:49:41.907  4907  4907 I Avrcp   : App Package name is GM
,05-25 13:49:41.917  4907  4907 V Avrcp   : MediaPlayerInfo: mPlayerId=1
,05-25 13:49:41.917  4907  4907 I Avrcp   : No of Video players :: 2
05-25 13:49:41.917  4907  4907 I Avrcp   : Video App Package name is others
,05-25 13:49:41.917  4907  4907 V Avrcp   : MediaPlayerInfo: mPlayerId=2
05-25 13:49:41.917  4907  4907 I Avrcp   : Video App Package name is VP
,05-25 13:49:41.917  4907  4907 V Avrcp   : MediaPlayerInfo: mPlayerId=3
05-25 13:49:41.917  4907  4907 I Avrcp   : Add tempPlayer
05-25 13:49:41.917  4907  4907 V Avrcp   : MediaPlayerInfo: mPlayerId=4
05-25 13:49:41.917  4907  4907 V Avrcp   : no_of_players : 4
05-25 13:49:41.917  4907  4907 I Avrcp   : Total no of players: 4
05-25 13:49:41.917  4907  4907 V Avrcp   : Samsung player is the 1st player
05-25 13:49:41.917  4907  4907 D Avrcp   : Compose Browsing Service Candidate
,05-25 13:49:41.917  4907  4907 D Avrcp   : ResolveInfo info ResolveInfo{fd32c61 com.google.android.music/.browse.MediaBrowserService m=0x108000}
05-25 13:49:41.917  4907  4907 D Avrcp   : Initialize Media Controller
,05-25 13:49:41.917  3487  4947 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{aa914b6 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{78dd1e5 8981:com.sec.android.app.shealth:remote/u0a39}
,05-25 13:49:41.917  4907  4907 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,05-25 13:49:41.917  4907  4907 E Avrcp   : getActiveSessions
,05-25 13:49:41.917  4907  4907 D Avrcp   : pick active media Controller
05-25 13:49:41.917  4907  4907 D Avrcp   : Get the active Media Controller 
05-25 13:49:41.917  4907  4907 D A2dpStateMachine: make
,05-25 13:49:41.927  4907  4907 I bt_bluedroid: get_profile_interface a2dp
,05-25 13:49:41.927  4907  4907 E bt_btif : warning : media task started media_task_refcnt 1 
,05-25 13:49:41.927  4907  9953 D A2dpStateMachine: Enter Disconnected: -2
,05-25 13:49:41.927  4907  4907 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Message sending
05-25 13:49:41.927  4907  4907 E A2dpService: notifyProfileServiceStateChanged
,05-25 13:49:41.937  3487  4947 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{aa914b6 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c6d3356 9932:com.android.settings/1000}
,05-25 13:49:41.937  9932  9932 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
05-25 13:49:41.937  9932  9932 D BluetoothStatusReceiver: AdapterStateChanged :: state = 10
,05-25 13:49:41.957  3487  4947 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{aa914b6 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b5595e1 4907:com.android.bluetooth/1002}
,05-25 13:49:41.967  4907  4907 D HidService: Received start request. Starting profile...
,05-25 13:49:41.967  4907  4907 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5359fd5
05-25 13:49:41.967  4907  4907 I bt_bluedroid: get_profile_interface hidhost
05-25 13:49:41.967  4907  4907 D HidService: setHidService(): set to: null
05-25 13:49:41.967  4907  4907 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, Message sending
05-25 13:49:41.967  4907  4907 E HidService: notifyProfileServiceStateChanged
,05-25 13:49:41.967  4907  4907 D HealthService: Received start request. Starting profile...
,05-25 13:49:41.967  4907  4907 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5359fd5
,05-25 13:49:41.967  4907  4907 I bt_bluedroid: get_profile_interface health
,05-25 13:49:41.967  4907  4907 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, Message sending
05-25 13:49:41.967  4907  4907 E HealthService: notifyProfileServiceStateChanged
05-25 13:49:41.967  4907  4907 D HeadsetStateMachine: Try to query the phonestate on bind
,05-25 13:49:41.967  3487  3980 I Telecom : BluetoothPhoneService: queryPhoneState
05-25 13:49:41.967  3487  3980 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState : true
,05-25 13:49:41.967  4907  4907 D PanService: Received start request. Starting profile...
,05-25 13:49:41.967  4907  4907 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5359fd5
05-25 13:49:41.967  4907  4907 D BluetoothPanServiceJni: initializeNative(L118): pan
05-25 13:49:41.967  4907  4907 I bt_bluedroid: get_profile_interface pan
,05-25 13:49:41.967  4907  4907 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, Message sending
05-25 13:49:41.967  4907  4907 E PanService: notifyProfileServiceStateChanged
05-25 13:49:41.977  4907  4907 D HeadsetStateMachine: Proxy object connected
,05-25 13:49:41.977  4907  4907 D BluetoothMapService: Received start request. Starting profile...
,05-25 13:49:41.977  4907  4907 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5359fd5
,05-25 13:49:41.977  4907  4907 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Message sending
,05-25 13:49:41.977  4907  4907 E BluetoothMapService: notifyProfileServiceStateChanged
05-25 13:49:41.977  4907  4907 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
05-25 13:49:41.977  4907  4907 D HeadsetPhoneState: sendDeviceDataStateChanged
05-25 13:49:41.977  4907  9949 D HeadsetStateMachine: Disconnected process message: 11, size: 0
05-25 13:49:41.977  4907  9949 E HeadsetStateMachine: Unknown message: 11
,05-25 13:49:41.977  4907  9949 D HeadsetStateMachine: Disconnected process message: 19, size: 0
05-25 13:49:41.977  4907  9949 E HeadsetStateMachine: Unknown message: 19
05-25 13:49:41.977  4907  4907 D HeadsetPhoneState: Signal level : previous=0 curr=0
05-25 13:49:41.977  4907  4907 V SapService: SapBinder()
,05-25 13:49:41.977  4907  4907 D SapService: Received start request. Starting profile...
,05-25 13:49:41.977  4907  4907 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5359fd5
05-25 13:49:41.977  4907  4907 V SapService: start()
05-25 13:49:41.977  4907  4907 D SapService: Disable sap : false
,05-25 13:49:41.987  4907  4907 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=12, Message sending
,05-25 13:49:41.987  4907  4907 E SapService: notifyProfileServiceStateChanged
,05-25 13:49:41.987  4907  4907 D BleAudioService: Received start request. Starting profile...
05-25 13:49:41.987  4907  4907 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5359fd5
,05-25 13:49:41.987  4907  4907 E DualScoManager: Dual Sco Manager already instantiated
05-25 13:49:41.987  4907  4907 D BleAudioStateMachine: make
,05-25 13:49:41.987  4907  4907 I BleAudioStateMachine: Constructor Of BleAudioStateMachine
,05-25 13:49:41.987  4907  4907 D BtBleAudio.JNI: initializeNative(L309): ble audio jni initializeNative: 0
05-25 13:49:41.987  4907  4907 I bt_bluedroid: get_profile_interface bleaudio_source
05-25 13:49:41.987  4907  4907 D BleAudioStateMachine: make
05-25 13:49:41.987  4907  9958 E BleAudioStateMachine_L: Enter Disconnected: -2
,05-25 13:49:41.987  4907  4907 I BleAudioStateMachine: Constructor Of BleAudioStateMachine
,05-25 13:49:41.987  4907  4907 D BtBleAudio.JNI: initializeNative(L309): ble audio jni initializeNative: 1
05-25 13:49:41.987  4907  4907 V BleAudioService: [registerCallStateListener]
05-25 13:49:41.987  4907  9959 E BleAudioStateMachine_R: Enter Disconnected: -2
,05-25 13:49:41.997  4907  4907 V BleAudioService: [registerAobleStateChangeListener]
,05-25 13:49:41.997  4907  4907 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.broadcom.bt.service.bleaudio.BleAudioService, state=12, Message sending
,05-25 13:49:41.997  4907  4907 E BleAudioService: notifyProfileServiceStateChanged
05-25 13:49:41.997  4907  4907 E BluetoothAdapterService: handleMessage() - Message: 1
05-25 13:49:41.997  4907  4907 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Before synchronized
,05-25 13:49:41.997  4907  4907 V BluetoothAdapterState: isTurningOff()=false
05-25 13:49:41.997  4907  4907 V BluetoothAdapterState: isTurningOn()=true
,05-25 13:49:41.997  4907  4907 V BluetoothAdapterState: isBleTurningOn()=false
05-25 13:49:41.997  4907  4907 V BluetoothAdapterState: isBleTurningOff()=false
05-25 13:49:41.997  4907  4907 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-25 13:49:41.997  4907  4907 E BluetoothAdapterService: handleMessage() - Message: 1
,05-25 13:49:41.997  4907  4907 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Before synchronized
05-25 13:49:41.997  4907  9949 D HeadsetStateMachine: Disconnected process message: 10, size: 0
05-25 13:49:41.997  4907  9949 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
05-25 13:49:41.997  4907  9949 D HeadsetStateMachine: Disconnected process message: 11, size: 0
,05-25 13:49:41.997  4907  9949 E HeadsetStateMachine: Unknown message: 11
,05-25 13:49:41.997  4907  4907 V BluetoothAdapterState: isTurningOff()=false
,05-25 13:49:41.997  4907  4907 V BluetoothAdapterState: isTurningOn()=true
05-25 13:49:41.997  4907  4907 V BluetoothAdapterState: isBleTurningOn()=false
05-25 13:49:41.997  4907  4907 V BluetoothAdapterState: isBleTurningOff()=false
05-25 13:49:41.997  4907  4907 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
05-25 13:49:41.997  4907  4907 D HeadsetPhoneState: sendDeviceDataStateChanged
,05-25 13:49:41.997  4907  9949 D HeadsetStateMachine: Disconnected process message: 11, size: 0
05-25 13:49:41.997  4907  9949 E HeadsetStateMachine: Unknown message: 11
05-25 13:49:41.997  4907  9949 D HeadsetStateMachine: Disconnected process message: 19, size: 0
05-25 13:49:41.997  4907  9949 E HeadsetStateMachine: Unknown message: 19
05-25 13:49:41.997  4907  4907 D HeadsetPhoneState: Signal level : previous=0 curr=0
05-25 13:49:41.997  4907  4907 E BluetoothAdapterService: handleMessage() - Message: 1
,05-25 13:49:41.997  4907  4907 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, Before synchronized
05-25 13:49:41.997  4907  4907 V BluetoothAdapterState: isTurningOff()=false
05-25 13:49:41.997  4907  4907 V BluetoothAdapterState: isTurningOn()=true
05-25 13:49:41.997  4907  4907 V BluetoothAdapterState: isBleTurningOn()=false
05-25 13:49:41.997  4907  4907 V BluetoothAdapterState: isBleTurningOff()=false
05-25 13:49:41.997  4907  4907 D BluetoothAdapterService: HID Host service started
,05-25 13:49:42.007  3487  4065 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{aa914b6 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2bf0927 7227:com.google.android.apps.maps/u0a125}
,05-25 13:49:42.017  4907  4907 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,05-25 13:49:42.017  4907  4907 E BluetoothAdapterService: handleMessage() - Message: 1
05-25 13:49:42.017  3949  4154 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CONNECTION_HID_HOST
05-25 13:49:42.017  4907  4907 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, Before synchronized
05-25 13:49:42.017  3949  4154 W LocalBluetoothProfileManager: updateLocalProfiles :: A2DP profile was previously added but the UUID is now missing.
05-25 13:49:42.017  3949  4154 W LocalBluetoothProfileManager: updateLocalProfiles :: HEADSET profile was previously added but the UUID is now missing.
05-25 13:49:42.017  3949  4154 W LocalBluetoothProfileManager: updateLocalProfiles :: MAP profile was previously added but the UUID is now missing.
05-25 13:49:42.017  4907  4907 V BluetoothAdapterState: isTurningOff()=false
05-25 13:49:42.017  3949  4154 W LocalBluetoothProfileManager: updateLocalProfiles :: PBAP profile was previously added but the UUID is now missing.
05-25 13:49:42.017  3949  4154 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
05-25 13:49:42.017  4907  4907 V BluetoothAdapterState: isTurningOn()=true
05-25 13:49:42.017  3949  4154 D HidProfile: mService is null. need to get proxy again!!
05-25 13:49:42.017  4907  4907 V BluetoothAdapterState: isBleTurningOn()=false
05-25 13:49:42.017  4907  4907 V BluetoothAdapterState: isBleTurningOff()=false
,05-25 13:49:42.017  4907  4907 E BluetoothAdapterService: handleMessage() - Message: 1
,05-25 13:49:42.017  4907  4907 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, Before synchronized
05-25 13:49:42.017  9932  9932 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CONNECTION_HID_HOST
,05-25 13:49:42.017  4907  4907 V BluetoothAdapterState: isTurningOff()=false
05-25 13:49:42.017  4907  4907 V BluetoothAdapterState: isTurningOn()=true
05-25 13:49:42.017  4907  4907 V BluetoothAdapterState: isBleTurningOn()=false
,05-25 13:49:42.017  4907  4907 V BluetoothAdapterState: isBleTurningOff()=false
05-25 13:49:42.017  4907  4907 E BluetoothAdapterService: handleMessage() - Message: 1
05-25 13:49:42.017  4907  4907 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Before synchronized
05-25 13:49:42.017  9932  9932 D BluetoothMap: Create BluetoothMap proxy object
,05-25 13:49:42.027  4907  4907 V BluetoothAdapterState: isTurningOff()=false
,05-25 13:49:42.027  4907  4907 V BluetoothAdapterState: isTurningOn()=true
05-25 13:49:42.027  4907  4907 V BluetoothAdapterState: isBleTurningOn()=false
05-25 13:49:42.027  4907  4907 V BluetoothAdapterState: isBleTurningOff()=false
,05-25 13:49:42.027  4907  4907 E BluetoothAdapterService: handleMessage() - Message: 1
05-25 13:49:42.027  4907  4907 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=12, Before synchronized
05-25 13:49:42.027  4907  4907 V BluetoothAdapterState: isTurningOff()=false
05-25 13:49:42.027  4907  4907 V BluetoothAdapterState: isTurningOn()=true
,05-25 13:49:42.027  4907  4907 V BluetoothAdapterState: isBleTurningOn()=false
05-25 13:49:42.027  4907  4907 V BluetoothAdapterState: isBleTurningOff()=false
05-25 13:49:42.027  4907  4907 D BleAudioService: [onCallStateChanged] ENTER -- State: (0)
05-25 13:49:42.027  4907  4907 D BleAudioService: [onCallStateChanged] No devices in connected state
,05-25 13:49:42.027  4907  4907 D BleAudioService: [onCallStateChanged][PHONECALL STATE Changed]: EXIT
05-25 13:49:42.027  4907  4907 E BluetoothAdapterService: handleMessage() - Message: 1
05-25 13:49:42.027  4907  4907 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.bleaudio.BleAudioService, state=12, Before synchronized
05-25 13:49:42.027  4907  4907 V BluetoothAdapterState: isTurningOff()=false
05-25 13:49:42.027  4907  4907 V BluetoothAdapterState: isTurningOn()=true
05-25 13:49:42.027  4907  4907 V BluetoothAdapterState: isBleTurningOn()=false
05-25 13:49:42.027  4907  4907 V BluetoothAdapterState: isBleTurningOff()=false
05-25 13:49:42.027  4907  5033 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_STARTED
,05-25 13:49:42.037  3487  4065 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{957e9f9 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c6d3356 9932:com.android.settings/1000}
,05-25 13:49:42.037  4907  9960 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,05-25 13:49:42.037  4907  9960 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,05-25 13:49:42.037  4907  5033 E BluetoothServiceJni: enableBrEdrNative:
05-25 13:49:42.037  4907  5033 I bt_bluedroid: enable_bredr
,05-25 13:49:42.047  3949  3949 D BluetoothInputDevice: Proxy object connected
05-25 13:49:42.047  3949  3949 D HidProfile: Bluetooth service connected
05-25 13:49:42.047  4907  5037 I bt_bta_hh: BTA_HhEnable sec_mask:0x24 p_cback:0xf346df29
05-25 13:49:42.047  4907  5037 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x100048
,05-25 13:49:42.047  4907  5037 D BluetoothAdapterProperties: Address is:A8:81:95:E9:5F:6F
05-25 13:49:42.047  4907  5037 E BluetoothServiceJni: populateRssiValuesNative
05-25 13:49:42.047  4907  5037 I bt_bluedroid: getModelRssiValues
05-25 13:49:42.047  4907  5209 D CODEC_IF: codec_if_open: opening libbt-codec_aptx.so...
05-25 13:49:42.047  4907  5037 E BluetoothServiceJni: model_rssi_values_callback: low = -75, mid = -65, high = 127
05-25 13:49:42.047  4907  5037 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -75,-65,127
05-25 13:49:42.047  4907  5209 D CODEC_IF_MOD: codec_open: codec_open
,05-25 13:49:42.047  4907  5209 D CODEC_IF_MOD: codec_open: apt-x encoder initialized successfully
05-25 13:49:42.047  4907  5209 D CODEC_IF_MOD: codec_open:    version : 1.0.1.0
05-25 13:49:42.047  4907  5209 D CODEC_IF_MOD: codec_open:    build : Android_JB_4.2.2
05-25 13:49:42.047  4907  5209 D CODEC_IF: codec_if_open: codec module opened (v0.1
05-25 13:49:42.047  4907  5209 D CODEC_IF: codec_if_close: codec_if_close hdl -550727676
05-25 13:49:42.047  4907  5209 D CODEC_IF_MOD: codec_close: codec_close
05-25 13:49:42.047  4907  5209 D CODEC_IF_MOD: codec_close: freed apt-x encoder
05-25 13:49:42.047  4907  5209 D         : Codec ==> check 96kHz mode : check_sshd_encoder_available:332
,05-25 13:49:42.047  4907  5209 D CODEC_IF: codec_if_open: opening libbt-codec_sshd.so...
05-25 13:49:42.047  4907  5209 D CODEC_IF_SSHD: codec_open: codec_open
05-25 13:49:42.047  4907  5209 D CODEC_IF_SSHD: Codec ==> pcm_info.sampling_freq : 96000
05-25 13:49:42.047  4907  5209 D CODEC_IF_SSHD: codec_open: SSHD encoder initialized successfully
05-25 13:49:42.047  4907  5209 D CODEC_IF: codec_if_open: codec module opened (v0.1
05-25 13:49:42.047  4907  5209 D CODEC_IF: codec_if_close: codec_if_close hdl -586793600
05-25 13:49:42.047  4907  5209 D CODEC_IF_SSHD: codec_close: codec_close
05-25 13:49:42.047  4907  5209 D         : Codec ==> copy capability info [bta_av_co_audio_init:559]
,05-25 13:49:42.047  4907  5209 D CODEC_IF: codec_if_open: opening libbt-codec_aptx.so...
05-25 13:49:42.047  4907  5209 D CODEC_IF_MOD: codec_open: codec_open
05-25 13:49:42.047  4907  5209 D CODEC_IF_MOD: codec_open: apt-x encoder initialized successfully
05-25 13:49:42.047  4907  5209 D CODEC_IF_MOD: codec_open:    version : 1.0.1.0
05-25 13:49:42.047  4907  5209 D CODEC_IF_MOD: codec_open:    build : Android_JB_4.2.2
05-25 13:49:42.047  4907  5209 D CODEC_IF: codec_if_open: codec module opened (v0.1
05-25 13:49:42.047  4907  5209 D CODEC_IF: codec_if_close: codec_if_close hdl -550727676
05-25 13:49:42.047  4907  5209 D CODEC_IF_MOD: codec_close: codec_close
05-25 13:49:42.047  4907  5209 D CODEC_IF_MOD: codec_close: freed apt-x encoder
05-25 13:49:42.047  4907  5209 D         : Codec ==> check 96kHz mode : check_sshd_encoder_available:332
,05-25 13:49:42.047  4907  5209 D CODEC_IF: codec_if_open: opening libbt-codec_sshd.so...
05-25 13:49:42.047  4907  5209 D CODEC_IF_SSHD: codec_open: codec_open
05-25 13:49:42.047  4907  5209 D CODEC_IF_SSHD: Codec ==> pcm_info.sampling_freq : 96000
05-25 13:49:42.047  4907  5209 D CODEC_IF_SSHD: codec_open: SSHD encoder initialized successfully
05-25 13:49:42.047  4907  5209 D CODEC_IF: codec_if_open: codec module opened (v0.1
05-25 13:49:42.047  4907  5209 D CODEC_IF: codec_if_close: codec_if_close hdl -586793600
05-25 13:49:42.047  4907  5209 D CODEC_IF_SSHD: codec_close: codec_close
05-25 13:49:42.047  4907  5209 D         : Codec ==> copy capability info [bta_av_co_audio_init:559]
,05-25 13:49:42.057  3487  4408 V AlarmManager:  remove PendingIntent] PendingIntent{6214ebb: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
,05-25 13:49:42.057  3487  3487 D SettingsProvider: isChangeAllowed() : name = bluetooth_name
,05-25 13:49:42.057  4907  5037 D BluetoothAdapterProperties: Name is: Samsung Galaxy S7 edge
,05-25 13:49:42.057  3949  4154 W LocalBluetoothProfileManager: updateLocalProfiles :: BleAudio profile was created already 
05-25 13:49:42.057  9932  9932 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
,05-25 13:49:42.067  4907  5037 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
05-25 13:49:42.067  4907  5037 D BluetoothAdapterProperties: Scan Mode:20
05-25 13:49:42.067  4907  5037 D BluetoothAdapterProperties: Discoverable Timeout:-1
05-25 13:49:42.067  4907  5037 E bt_btif : btif_handle_bluetooth_enable_evt
05-25 13:49:42.067  4907  5037 E bt_btif : JVenable fails
05-25 13:49:42.067  4907  5037 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,05-25 13:49:42.067  4907  5037 D IOP_DB_BT: db_open: db_open : handle 4080992272l, read 18483 bytes onto local cache
05-25 13:49:42.067  4907  5037 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
05-25 13:49:42.067  4907  5037 D IOP_DB_BT: db_query: result 1
05-25 13:49:42.067  4907  5037 I         : iop_db_open: iop_db_open status 0
05-25 13:49:42.067  4907  5037 E BluetoothAdapterState: stateChangeCallback : 17
05-25 13:49:42.067  4907  5033 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_NATIVE_STARTED
,05-25 13:49:42.067  4907  5037 E bt_btif : no av cb found, event:0, BTA_AV_ENABLE_EVT ignored!
05-25 13:49:42.067  4907  5037 E bt_btif : btif_sm_dispatch : Invalid handle
05-25 13:49:42.067  4907  5037 E bt_btif : no av control block available at state:3
05-25 13:49:42.067  4907  5037 E bt_btif : no av control block available at state:3
05-25 13:49:42.067  4907  5037 E bt_btif : no av control block available at state:2
05-25 13:49:42.067  4907  5037 E bt_btif : warning : no command pending, ignore ack
05-25 13:49:42.067  4907  5037 E bt_btif : no av control block available at state:3
05-25 13:49:42.067  4907  5037 E bt_btif : no av control block available at state:2
05-25 13:49:42.067  4907  5037 W bt_btif : btif_av_state_idle_handler : unhandled event:BTA_AV_REGISTER_EVT
05-25 13:49:42.067  4907  5037 E bt_btif : btif_sm_dispatch : Invalid handle
05-25 13:49:42.067  4907  5037 E bt_btif : no av control block available at state:3
05-25 13:49:42.067  4907  5037 E bt_btif : no av control block available at state:3
05-25 13:49:42.067  4907  5037 E bt_btif : no av control block available at state:2
05-25 13:49:42.067  4907  5037 E bt_btif : warning : no command pending, ignore ack
05-25 13:49:42.067  4907  5037 E bt_btif : no av control block available at state:3
05-25 13:49:42.067  4907  5037 E bt_btif : no av control block available at state:2
05-25 13:49:42.067  4907  5037 W bt_btif : btif_av_state_idle_handler : unhandled event:BTA_AV_REGISTER_EVT
05-25 13:49:42.067  4907  5037 E bt_btif : btif_sm_dispatch : Invalid handle
05-25 13:49:42.067  4907  5037 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
05-25 13:49:42.067  3487  4407 V AlarmManager:  remove PendingIntent] PendingIntent{e59f184: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
,05-25 13:49:42.077  4907  5033 D BluetoothAdapterProperties: ScanMode =  20
05-25 13:49:42.077  4907  5033 D BluetoothAdapterProperties: State =  11
,05-25 13:49:42.077  9932  9932 D LocalBluetoothProfileManager: Adding local BleAudio profile
,05-25 13:49:42.077  3487  4920 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
,05-25 13:49:42.077  9932  9932 D BluetoothLeAudio: getProfileProxy(),
,05-25 13:49:42.077  9844  9844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:49:42.077  3487  4196 D SecContentProvider: insert(), uri = 2
,05-25 13:49:42.087  3487  4927 V AlarmManager:  remove PendingIntent] PendingIntent{76cda33: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
,05-25 13:49:42.087  4907  5033 D BluetoothAdapterProperties: Setting state to 12
,05-25 13:49:42.087  4907  5033 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
05-25 13:49:42.087  4907  5033 D HeadsetService: setBleAudioService(): com.broadcom.bt.service.bleaudio.BleAudioService@f22d227
05-25 13:49:42.087  4907  5033 D A2dpService: setBleAudioService(): com.broadcom.bt.service.bleaudio.BleAudioService@f22d227
05-25 13:49:42.087  4907  5033 D BleAudioService: setHeadsetService: setting HeadsetService
05-25 13:49:42.087  4907  5033 D BleAudioService: setA2dpService: setting A2dpService
05-25 13:49:42.087  4907  5033 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,05-25 13:49:42.087  4907  5033 D BluetoothAdapterService: updateAdapterState state is 12
,05-25 13:49:42.097  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,05-25 13:49:42.097  4907  5037 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,05-25 13:49:42.097  4907  5037 D BluetoothAdapterProperties: Scan Mode:21
,05-25 13:49:42.097  4907  5037 D BluetoothAdapterProperties: Discoverable Timeout:-1
,05-25 13:49:42.097  4907  5033 V BluetoothAdapterService: start opp service
,05-25 13:49:42.107  9932  9932 D BluetoothLeAudio: Success to bind to IBluetoothLeAudio with Intent { act=com.broadcom.bt.service.bleaudio.IBluetoothLeAudio cmp=com.android.bluetooth/com.broadcom.bt.service.bleaudio.BleAudioService VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
,05-25 13:49:42.107  3487  4947 V AlarmManager:  remove PendingIntent] PendingIntent{5faad25: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
,05-25 13:49:42.117  9844  9844 D BluetoothAdapter: STATE_ON
,05-25 13:49:42.117  4907  5033 D BluetoothAdapterService: Autoconnection is available 
05-25 13:49:42.117  4907  5033 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
05-25 13:49:42.117  4907  5033 D BluetoothAdapterService: starting service from this receiver
,05-25 13:49:42.117  9844  9854 D BluetoothAdapter: onBluetoothStateChange: up=true
05-25 13:49:42.117  9844  9854 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
05-25 13:49:42.117  9932  9932 D BluetoothMap: Proxy object connected
,05-25 13:49:42.117  9932  9932 D MapProfile: Bluetooth service connected
05-25 13:49:42.117  9932  9932 D BluetoothMap: getConnectedDevices()
,05-25 13:49:42.117  9844  9844 D BluetoothAdapter: STATE_ON
,05-25 13:49:42.117  9844  9844 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,05-25 13:49:42.127  9932  9943 D BluetoothSap: onBluetoothStateChange: up=true
05-25 13:49:42.127  9932  9943 D BluetoothSap: Binding service...
,05-25 13:49:42.127  3487  3854 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{957e9f9 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bad5c58 4933:com.samsung.android.providers.context/u0a9}
,05-25 13:49:42.127  9844  9844 D BluetoothAdapter: STATE_ON
,05-25 13:49:42.127  9844  9844 D BluetoothAdapter: STATE_ON
,05-25 13:49:42.127  9844  9844 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,05-25 13:49:42.137  4907  4907 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
05-25 13:49:42.137  3487  3599 D BluetoothA2dp: onBluetoothStateChange: up=true
05-25 13:49:42.137  3487  3599 D BluetoothA2dp: Binding service...
05-25 13:49:42.137  3487  3599 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
05-25 13:49:42.137  9932  9932 D BluetoothInputDevice: Proxy object connected
,05-25 13:49:42.137  9932  9932 D HidProfile: Bluetooth service connected
,05-25 13:49:42.147  9844  9844 D BluetoothAdapter: STATE_ON
,05-25 13:49:42.147  4907  5033 D BluetoothAdapterService: BT on, init HID DEV count : 0
05-25 13:49:42.147  4907  5033 I BluetoothAdapterState: Entering OnState
,05-25 13:49:42.147  9844  9844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-25 13:49:42.147  9844  9844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-25 13:49:42.147  9844  9844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-25 13:49:42.147  9844  9844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-25 13:49:42.147  9844  9844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-25 13:49:42.147  9844  9844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-25 13:49:42.147  9844  9844 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-25 13:49:42.147  9844  9844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-25 13:49:42.147  9844  9844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,05-25 13:49:42.147  3949  4600 D BluetoothMap: onBluetoothStateChange: up=true
05-25 13:49:42.147  3487  4065 V AlarmManager:  remove PendingIntent] PendingIntent{25ec3b4: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
05-25 13:49:42.147  3949  4600 D BluetoothMap: Binding service...
,05-25 13:49:42.157  4907  4907 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,05-25 13:49:42.157  9932  9932 D BluetoothPbap: Proxy object connected
05-25 13:49:42.157  4907  4907 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,05-25 13:49:42.157  9932  9932 D PbapServerProfile: Bluetooth service connected
05-25 13:49:42.157  9844  9844 D BluetoothAdapter: STATE_ON
05-25 13:49:42.157  9932  9932 D BluetoothLeAudio: Proxy object connected
,05-25 13:49:42.157  9932  9932 D BleAudioProfile: Bluetooth service connected
,05-25 13:49:42.157  9932  9932 D BluetoothLeAudio: getConnectedDevices()
05-25 13:49:42.157  4907  4907 V BtOppService: isOwner == true
,05-25 13:49:42.157  3487  3854 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{957e9f9 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a95ad21 4274:com.google.android.gms.persistent/u0a21}
,05-25 13:49:42.157  4274  4274 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
,05-25 13:49:42.167  4163  7403 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg com.android.bluetooth,id=0,extra=Bundle[mParcelledData.dataSize=160]
05-25 13:49:42.167  4163  4163 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=0, samsung.notification.type=normal, samsung.people.package_name=com.android.bluetooth, samsung.notification.remove_all=true}]
,05-25 13:49:42.167  4163  4163 I PeopleStripeService: PeopleNotificationReceiver:3
,05-25 13:49:42.167  9844  9844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,05-25 13:49:42.167  4163  4163 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
05-25 13:49:42.167  4163  4163 I PeopleDataManager: removeNotification
05-25 13:49:42.167  4163  4163 I NotificationParser: getNotiType:com.android.bluetooth,null
,05-25 13:49:42.167  4163  4163 D PeopleDataManager: removeNotiInfo: id =0,packageName=com.android.bluetooth,isEdgeNotification=false,key=null,removeAll=true
05-25 13:49:42.167  4163  4163 D PeopleDataManager: removeNotiInfo =null
,05-25 13:49:42.167  3949  3949 D BluetoothMap: Proxy object connected
05-25 13:49:42.167  3949  3949 D MapProfile: Bluetooth service connected
05-25 13:49:42.167  3949  3949 D BluetoothMap: getConnectedDevices()
,05-25 13:49:42.167  4907  5033 D BluetoothAdapterState: Current state: ON, message: USER_TURN_OFF
,05-25 13:49:42.177  4907  4907 I BluetoothPbapService: Handler(): got msg=1
,05-25 13:49:42.177  3487  3980 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,05-25 13:49:42.177  3487  4408 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{957e9f9 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{78dd1e5 8981:com.sec.android.app.shealth:remote/u0a39}
,05-25 13:49:42.187  4300  4311 D BluetoothAdapter: onBluetoothStateChange: up=true
05-25 13:49:42.187  4300  4311 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,05-25 13:49:42.187  9932  9942 D BluetoothMap: onBluetoothStateChange: up=true
,05-25 13:49:42.187  9932  9963 D BluetoothPan: onBluetoothStateChange on: true
05-25 13:49:42.187  9932  9963 D BluetoothPan: onBluetoothStateChange calling doBind()
05-25 13:49:42.187  4907  9967 V BluetoothPbapService: PBAP Service initSocket try: 0
,05-25 13:49:42.197  9932  9932 D BluetoothSap: Proxy object connected
05-25 13:49:42.197  9932  9932 D SapProfile: Bluetooth service connected
,05-25 13:49:42.197  3487  4196 V AlarmManager:  remove PendingIntent] PendingIntent{632d54c: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
,05-25 13:49:42.197  3949  4112 D BluetoothSap: onBluetoothStateChange: up=true
05-25 13:49:42.197  3949  4112 D BluetoothSap: Binding service...
,05-25 13:49:42.197  4907  9967 D BluetoothSocket: bindListen(): myUserId = 0
05-25 13:49:42.197  4907  9967 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,05-25 13:49:42.207  3487  4927 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{957e9f9 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c6d3356 9932:com.android.settings/1000}
,05-25 13:49:42.207  9932  9932 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
05-25 13:49:42.207  9932  9932 D BluetoothStatusReceiver: AdapterStateChanged :: state = 11
,05-25 13:49:42.217  3949  3949 D BluetoothSap: Proxy object connected
,05-25 13:49:42.217  3949  3949 D SapProfile: Bluetooth service connected
,05-25 13:49:42.217  4315  4325 D BluetoothAdapter: onBluetoothStateChange: up=true
,05-25 13:49:42.217  4315  4325 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,05-25 13:49:42.217  4907  9967 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,05-25 13:49:42.217  3949  5577 D BluetoothInputDevice: onBluetoothStateChange: up=true
05-25 13:49:42.217  4274  5181 D BluetoothAdapter: onBluetoothStateChange: up=true
,05-25 13:49:42.217  4274  5181 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
05-25 13:49:42.217  3949  3970 D BluetoothAdapter: onBluetoothStateChange: up=true
05-25 13:49:42.217  3949  3970 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
05-25 13:49:42.217  8981  8993 D BluetoothAdapter: onBluetoothStateChange: up=true
05-25 13:49:42.217  8981  8993 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
05-25 13:49:42.217  3487  3599 D BluetoothPan: onBluetoothStateChange on: true
05-25 13:49:42.217  3487  3599 D BluetoothPan: onBluetoothStateChange calling doBind()
,05-25 13:49:42.227  9844  9930 D BluetoothAdapter: STATE_ON
05-25 13:49:42.227  3487  4927 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{957e9f9 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b5595e1 4907:com.android.bluetooth/1002}
,05-25 13:49:42.227  9844  9930 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-25 13:49:42.227  9844  9930 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-25 13:49:42.227  9844  9930 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-25 13:49:42.227  9844  9930 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-25 13:49:42.227  9844  9930 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-25 13:49:42.227  9844  9930 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-25 13:49:42.227  9844  9930 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-25 13:49:42.227  9844  9930 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-25 13:49:42.227  9844  9930 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,05-25 13:49:42.227  9844  9908 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
,05-25 13:49:42.227  3487  3854 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,05-25 13:49:42.237  4907  5370 D BluetoothAdapter: onBluetoothStateChange: up=true
,05-25 13:49:42.237  4907  5370 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
05-25 13:49:42.237  9844  9908 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:49:42.237  3487  3854 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,05-25 13:49:42.237  3487  3506 V AlarmManager:  remove PendingIntent] PendingIntent{a9a205: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
,05-25 13:49:42.237  3949  3974 D BluetoothInputDevice: onBluetoothStateChange: up=true
05-25 13:49:42.237  3949  3974 D BluetoothInputDevice: Binding service...
,05-25 13:49:42.237  3487  3854 D WifiService: setWifiEnabled: false pid=9844, uid=10078
,05-25 13:49:42.237  3487  3863 D WifiStateMachine: setFccChannel: channel = 0
05-25 13:49:42.237  3487  3854 D SettingsProvider: isChangeAllowed() : name = wifi_on
05-25 13:49:42.237  3487  3863 D WifiController: MHS off and WIFI tunred off and move to mApStaDisabledState
05-25 13:49:42.237  3487  3863 D WifiController: [FCC]setFccChannel() is called !!!
05-25 13:49:42.237  3487  3860 D WifiBigDataLog: getJsonFormat() - feature : ONOF
05-25 13:49:42.237  3487  3863 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
,05-25 13:49:42.237  3487  3863 D SecContentProvider: insert(), uri = 2
05-25 13:49:42.237  3487  3860 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,05-25 13:49:42.247  3487  3860 D WifiBigDataLog: init : 
,05-25 13:49:42.247  3949  3949 D BluetoothInputDevice: Proxy object connected
05-25 13:49:42.247  3949  3949 D HidProfile: Bluetooth service connected
05-25 13:49:42.247  9932  9963 D BluetoothInputDevice: onBluetoothStateChange: up=true
05-25 13:49:42.247  3487  3487 D BluetoothA2dp: Proxy object connected
,05-25 13:49:42.257  3487  3860 D WifiStateMachine: setFccChannelNative: channel = 0
05-25 13:49:42.257  3487  3860 D WifiNative-wlan0: callSECApiInt - ID [230]
,05-25 13:49:42.257  4907  5370 D A2dpStateMachine: getConnectedDevices : size=0
,05-25 13:49:42.257  4933  4946 D BluetoothA2dp: onBluetoothStateChange: up=true
05-25 13:49:42.257  3487  4408 V AlarmManager:  remove PendingIntent] PendingIntent{e606168: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
05-25 13:49:42.257  4933  4946 D BluetoothA2dp: Binding service...
,05-25 13:49:42.257  3487  4927 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
05-25 13:49:42.257  4933  4946 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,05-25 13:49:42.267  4933  4933 D BluetoothA2dp: Proxy object connected
,05-25 13:49:42.267  3949  6326 D BluetoothLeAudio: onBluetoothStateChange: up=true
05-25 13:49:42.267  3949  6326 D BluetoothLeAudio: Binding service...
,05-25 13:49:42.277  3487  4065 V AlarmManager:  remove PendingIntent] PendingIntent{8796667: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
,05-25 13:49:42.277  3949  3949 D BluetoothLeAudio: Proxy object connected
05-25 13:49:42.277  3949  3949 D BleAudioProfile: Bluetooth service connected
05-25 13:49:42.277  3949  3949 D BluetoothLeAudio: getConnectedDevices()
05-25 13:49:42.277  3487  3487 D BluetoothPan: BluetoothPAN Proxy object connected
,05-25 13:49:42.277  3487  3860 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,05-25 13:49:42.277  3949  6326 D BluetoothLeAudio: Success to bind to IBluetoothLeAudio with Intent { act=com.broadcom.bt.service.bleaudio.IBluetoothLeAudio cmp=com.android.bluetooth/com.broadcom.bt.service.bleaudio.BleAudioService VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
05-25 13:49:42.277  3487  3860 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
05-25 13:49:42.277  3487  3860 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
05-25 13:49:42.277  3487  3860 D WifiStateMachine: sendBroadcastForCaptivePortalNotLoginIcon : false
,05-25 13:49:42.287  9932  9932 D BluetoothPan: BluetoothPAN Proxy object connected
,05-25 13:49:42.287  3487  3860 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
,05-25 13:49:42.287  9932  9932 D PanProfile: Bluetooth service connected
05-25 13:49:42.287  3487  3860 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
,05-25 13:49:42.287  3487  3860 D SecContentProvider: insert(), uri = 2
,05-25 13:49:42.287  3949  4154 D NetworkController: onReceive: intent=Intent { act=com.samsung.intent.action.WIFI_CAPTIVE_NOT_LOGIN flg=0x10 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
05-25 13:49:42.287  3949  4154 D NetworkController.WifiSignalController: updateWifiState : mCurrentState.wifiCaptiveNotLogin = false
,05-25 13:49:42.287  9932  9943 D BluetoothPbap: onBluetoothStateChange: up=true
,05-25 13:49:42.287  9932  9942 D BluetoothLeAudio: onBluetoothStateChange: up=true
,05-25 13:49:42.287  3487  3599 D BluetoothAdapter: onBluetoothStateChange: up=true
05-25 13:49:42.287  3487  3599 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,05-25 13:49:42.287  3949  4600 D BluetoothPbap: onBluetoothStateChange: up=true
05-25 13:49:42.287  3949  4600 D BluetoothPbap: Binding service...
,05-25 13:49:42.297  4907  9971 D BluetoothSocket: bindListen(): myUserId = 0
,05-25 13:49:42.297  4907  9971 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,05-25 13:49:42.297  3487  3860 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
,05-25 13:49:42.297  3487  3985 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{957e9f9 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2bf0927 7227:com.google.android.apps.maps/u0a125}
,05-25 13:49:42.297  4907  9971 I BtOppRfcommListener: Accept thread started.
,05-25 13:49:42.297  3949  3949 D BluetoothPbap: Proxy object connected
05-25 13:49:42.297  3949  3949 D PbapServerProfile: Bluetooth service connected
,05-25 13:49:42.307  9932  9963 D BluetoothAdapter: onBluetoothStateChange: up=true
05-25 13:49:42.307  9932  9963 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,05-25 13:49:42.307  3949  4112 D BluetoothA2dp: onBluetoothStateChange: up=true
05-25 13:49:42.307  3949  4112 D BluetoothA2dp: Binding service...
,05-25 13:49:42.307  3949  4112 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,05-25 13:49:42.307  3487  3860 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
05-25 13:49:42.307  3487  3860 D WifiStateMachine: sendBroadcastForCaptivePortalNotLoginIcon : false
05-25 13:49:42.307  3487  4065 V AlarmManager:  remove PendingIntent] PendingIntent{784b7b9: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
05-25 13:49:42.307  4907  9970 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,05-25 13:49:42.307  3949  3949 D BluetoothA2dp: Proxy object connected
05-25 13:49:42.307  3949  3949 D A2dpProfile: Bluetooth service connected
,05-25 13:49:42.307  7227  7238 D BluetoothAdapter: onBluetoothStateChange: up=true
05-25 13:49:42.307  7227  7238 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,05-25 13:49:42.317  3949  4154 D NetworkController: onReceive: intent=Intent { act=com.samsung.intent.action.WIFI_CAPTIVE_NOT_LOGIN flg=0x10 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
05-25 13:49:42.317  3949  4154 D NetworkController.WifiSignalController: updateWifiState : mCurrentState.wifiCaptiveNotLogin = false
05-25 13:49:42.317  3949  4600 D BluetoothPan: onBluetoothStateChange on: true
05-25 13:49:42.317  3949  4600 D BluetoothPan: onBluetoothStateChange calling doBind()
,05-25 13:49:42.317  4907  9970 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,05-25 13:49:42.317  3487  3985 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{592c7fe u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bad5c58 4933:com.samsung.android.providers.context/u0a9}
,05-25 13:49:42.327  3487  3860 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
05-25 13:49:42.327  3487  3860 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
05-25 13:49:42.327  3487  3860 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,05-25 13:49:42.327  3487  3858 D WifiP2pService: InactiveState{ what=143375 }
,05-25 13:49:42.327  3487  3858 D WifiP2pService: P2pEnabledState{ what=143375 }
,05-25 13:49:42.327  4933  4954 D BluetoothAdapter: onBluetoothStateChange: up=true
05-25 13:49:42.327  4933  4954 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,05-25 13:49:42.337  3157  3638 D CommandListener: Clearing all IP addresses on wlan0
05-25 13:49:42.337  3487  4663 V AlarmManager:  remove PendingIntent] PendingIntent{9b01675: PendingIntentRecord{1c8f8f7 android broadcastIntent}}
,05-25 13:49:42.337  4907  5370 D A2dpStateMachine: getConnectedDevices : size=0
,05-25 13:49:42.337  3487  4671 V AlarmManager:  remove PendingIntent] PendingIntent{a4f660a: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
,05-25 13:49:42.347  3949  3949 D BluetoothPan: BluetoothPAN Proxy object connected
05-25 13:49:42.347  3949  3949 D PanProfile: Bluetooth service connected
,05-25 13:49:42.347  3949  4154 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
05-25 13:49:42.347  4274  7841 V NativeCrypto: Read error: ssl=0x7f89d73d80: I/O error during system call, Connection timed out
,05-25 13:49:42.357  3487  3869 E ConnectivityService: updateNetworkInfo()
05-25 13:49:42.357  3487  3869 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -22]
05-25 13:49:42.357  3487  3869 E ConnectivityService: updateNetworkInfo()
05-25 13:49:42.357  3487  3869 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = DISCONNECTED
05-25 13:49:42.357  3487  3869 D NtpTrustedTime: currentTimeMillis() cache hit
05-25 13:49:42.357  3487  3869 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 6
05-25 13:49:42.357  3487  3869 V NetworkStats: updateIfacesLocked()
05-25 13:49:42.357  3487  3869 V NetworkStats: performPollLocked(flags=0x1)
,05-25 13:49:42.357  3487  3869 D NetworkStatsRecorder: entry.iface is null
05-25 13:49:42.357  3487  3869 D NetworkStatsRecorder: entry.iface is null
05-25 13:49:42.357  3487  3869 D NetworkStatsRecorder: entry.iface is null
05-25 13:49:42.357  3487  3869 D NetworkStatsRecorder: entry.iface is null
,05-25 13:49:42.357  3487  3869 D NtpTrustedTime: currentTimeMillis() cache hit
05-25 13:49:42.357  3487  3869 V NetworkStats: performPollLocked() took 6ms
,05-25 13:49:42.367  4274  7841 V NativeCrypto: SSL shutdown failed: ssl=0x7f89d73d80: I/O error during system call, Broken pipe
,05-25 13:49:42.367  3487  4671 V AlarmManager:  remove PendingIntent] PendingIntent{aa1ae7b: PendingIntentRecord{1d11af1 com.google.android.gms broadcastIntent}}
,05-25 13:49:42.367  4274  7841 E GCM     : Wifi connection closed with errorCode 20
,05-25 13:49:42.367  3487  3487 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
05-25 13:49:42.367  3487  3487 I InputMethodManagerService: [BT Setting State] State =12
05-25 13:49:42.367  3487  3487 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,05-25 13:49:42.367  3949  4154 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
05-25 13:49:42.367  3949  4154 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
05-25 13:49:42.367  3487  3487 I Telecom : BluetoothPhoneService: queryPhoneState
05-25 13:49:42.367  3487  3487 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState : true
,05-25 13:49:42.377  4348  4348 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
,05-25 13:49:42.377  4862  4862 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,05-25 13:49:42.377  3487  3487 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
05-25 13:49:42.377  3487  3487 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
05-25 13:49:42.377  3487  3487 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,05-25 13:49:42.377  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,05-25 13:49:42.377  9932  9932 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,05-25 13:49:42.387  9932  9932 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,05-25 13:49:42.387  9844  9844 D BluetoothAdapter: STATE_ON
,05-25 13:49:42.397  9844  9844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-25 13:49:42.397  9844  9844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-25 13:49:42.397  9844  9844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-25 13:49:42.397  9844  9844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-25 13:49:42.397  9844  9844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-25 13:49:42.397  9844  9844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
05-25 13:49:42.397  9844  9844 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
05-25 13:49:42.397  9844  9844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
05-25 13:49:42.397  9844  9844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,05-25 13:49:42.397  9844  9844 D BluetoothAdapter: STATE_ON
,05-25 13:49:42.397  3487  3570 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{822f498 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c6d3356 9932:com.android.settings/1000}
,05-25 13:49:42.397  3487  3869 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-25 13:49:42.397  3487  3869 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -22]
,05-25 13:49:42.397  3487  3869 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
05-25 13:49:42.397  3487  3860 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
05-25 13:49:42.397  3487  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:42.397  3487  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:42.397  3487  3869 D ConnectivityService: sending notification LOST for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:42.397  3487  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
,05-25 13:49:42.397  3487  3869 D ConnectivityService: sending notification LOST for NetworkRequest [ id=5, legacyType=-1, [] ]
05-25 13:49:42.397  3487  3858 D WifiP2pService: InactiveState{ what=131204 }
,05-25 13:49:42.397  3487  3858 D WifiP2pService: P2pEnabledState{ what=131204 }
05-25 13:49:42.397  4113  4113 I wpa_supplicant: P2P: Set prekey state (NONE -> NONE)
05-25 13:49:42.397  4113  4113 I wpa_supplicant: P2P: Clear a pre-passphrase (State NONE)
,05-25 13:49:42.407  3487  3858 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,05-25 13:49:42.407  3487  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:42.407  3487  3869 D ConnectivityService: sending notification LOST for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:42.407  3487  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:49:42.407  3487  3869 D ConnectivityService: sending notification LOST for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:49:42.407  9844  9844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
05-25 13:49:42.407  3487  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:49:42.407  3487  3869 D ConnectivityService: sending notification LOST for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:49:42.407  3487  4417 D ConnectivityService: getVpnConfig > userId : 0
,05-25 13:49:42.407  3487  4662 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
05-25 13:49:42.407  3487  3869 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:42.407  3487  3895 D Ethernet: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:42.407  3487  3895 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
05-25 13:49:42.407  3487  3895 D Ethernet: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
05-25 13:49:42.407  3487  3895 D Ethernet: evalRequest
05-25 13:49:42.407  3487  3895 D Ethernet:   done
05-25 13:49:42.407  3487  3860 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:42.407  3487  3860 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-25 13:49:42.417  3487  3860 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
05-25 13:49:42.417  3487  3860 D WIFI    : evalRequest
05-25 13:49:42.417  3487  3860 D WIFI    :   needNetworkFor
05-25 13:49:42.417  3487  3860 D WIFI_UT : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:42.417  3487  3860 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-25 13:49:42.417  3487  3860 D WIFI_UT : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
05-25 13:49:42.417  3487  3860 D WIFI_UT : evalRequest
05-25 13:49:42.417  3487  3860 D WIFI_UT :   done
05-25 13:49:42.417  3487  3860 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:42.417  3487  3860 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,05-25 13:49:42.417  3487  3860 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
05-25 13:49:42.417  3487  3860 D WIFI    : evalRequest
05-25 13:49:42.417  3487  3860 D WIFI    :   done
,05-25 13:49:42.417  3487  3599 D EntConnectivity: Not allowed due to - mEnabled false
,05-25 13:49:42.417  9974  9974 E Zygote  : v2
05-25 13:49:42.417  9974  9974 I libpersona: KNOX_SDCARD checking this for 10052
05-25 13:49:42.417  9974  9974 E Zygote  : isSdpEnabledProcess - SDP enabled
05-25 13:49:42.417  9974  9974 I libpersona: KNOX_SDCARD not a persona
,05-25 13:49:42.417  9974  9974 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-25 13:49:42.427  3487  3854 I ActivityManager: Start proc 9974:com.samsung.android.email.provider/u0a52 for content provider com.samsung.android.email.provider/.provider.database.EmailProvider
,05-25 13:49:42.427  3487  3487 I WifiTrafficPoller: evaluateTrafficStatsPolling
05-25 13:49:42.427  9932  9932 D LocalBluetoothProfileManager: Adding local A2DP profile
,05-25 13:49:42.427  3487  3487 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
05-25 13:49:42.427  3487  3487 D HS20StateMachine: [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true]
,05-25 13:49:42.427  3487  3487 D HS20StateMachine: checkifOSUAP  null disconnectedFromSsid"NG700"
05-25 13:49:42.427  3487  3487 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
05-25 13:49:42.427  3487  3867 I WifiHs20Service: Message received 5007
,05-25 13:49:42.427  3487  3487 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
,05-25 13:49:42.427  9932  9932 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,05-25 13:49:42.437  4315  4315 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,05-25 13:49:42.437  3487  3857 D NtpTrustedTime: currentTimeMillis() cache hit
05-25 13:49:42.437  3487  3857 D NtpTrustedTime: currentTimeMillis() cache hit
,05-25 13:49:42.437  9974  9974 E Zygote  : accessInfo : 64
05-25 13:49:42.437  9974  9974 E Zygote  : isSdpEnabledProcess - SDP enabled
05-25 13:49:42.437  9974  9974 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10052 / [uid]: 10052
05-25 13:49:42.437  3487  3857 D NetworkPolicy: isUidForegroundLocked: 10052, mScreenOn: true, uidstate: -1, mProxSensorScreenOff: false
05-25 13:49:42.437  9974  9974 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.email.provider 
05-25 13:49:42.437  3949  4154 W LocalBluetoothProfileManager: updateLocalProfiles :: MAP profile was previously added but the UUID is now missing.
05-25 13:49:42.437  3487  4407 V AlarmManager:  remove PendingIntent] PendingIntent{e619f2d: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
05-25 13:49:42.437  3949  4154 W LocalBluetoothProfileManager: updateLocalProfiles :: PBAP profile was previously added but the UUID is now missing.
05-25 13:49:42.437  3949  4154 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
05-25 13:49:42.437  3949  4154 W LocalBluetoothProfileManager: updateLocalProfiles :: HID profile was previously added but the UUID is now missing.
05-25 13:49:42.437  3949  4154 W LocalBluetoothProfileManager: updateLocalProfiles :: BleAudio profile was created already 
,05-25 13:49:42.437  9932  9932 D LocalBluetoothProfileManager: Adding local HEADSET profile
,05-25 13:49:42.437  3487  3600 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:42.437  3487  3600 I WifiDisplayAdapter: onP2pDisconnected
,05-25 13:49:42.437  3487  3600 D IpRemoteDisplayController: disconnectWfdBridgeServer
,05-25 13:49:42.437  3487  3600 D IpRemoteDisplayController: WfdBridgeServer is already null
,05-25 13:49:42.447  3949  3949 D WifiP2pController: onReceive android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,05-25 13:49:42.447  3487  3487 D RttService: SCAN_AVAILABLE : 1
,05-25 13:49:42.447  3487  3894 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,05-25 13:49:42.447  9932  9932 E BluetoothHeadset: BTStateChangeCB is registed
,05-25 13:49:42.447  3487  3487 D WifiNotificationController: SHOW_NOTI_MESSAGE : 17, visible : false, ssid : null, targetSSID : null, netId : -1, titleType : -1
05-25 13:49:42.447  4163  4177 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=17041470,extra=Bundle[mParcelledData.dataSize=84]
05-25 13:49:42.447  3487  3487 D WifiNotificationController: showMaliciousHotspotDetectionNotification - MaliciousNetwork:null, visible:false
05-25 13:49:42.447  4163  4163 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=17041470, samsung.notification.type=normal, samsung.people.package_name=android}]
,05-25 13:49:42.447  3487  3858 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
05-25 13:49:42.447  4163  4163 I PeopleStripeService: PeopleNotificationReceiver:3
,05-25 13:49:42.457  9932  9932 W LocalBluetoothProfileManager: updateLocalProfiles :: MAP profile was previously added but the UUID is now missing.
05-25 13:49:42.457  9932  9932 W LocalBluetoothProfileManager: updateLocalProfiles :: PBAP profile was previously added but the UUID is now missing.
05-25 13:49:42.457  9932  9932 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
05-25 13:49:42.457  9932  9932 W LocalBluetoothProfileManager: updateLocalProfiles :: HID profile was previously added but the UUID is now missing.
05-25 13:49:42.457  9932  9932 W LocalBluetoothProfileManager: updateLocalProfiles :: BleAudio profile was created already 
,05-25 13:49:42.457  3157  3638 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,05-25 13:49:42.457  4163  4163 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
,05-25 13:49:42.457  4163  4163 I PeopleDataManager: removeNotification
05-25 13:49:42.457  4163  4163 I NotificationParser: getNotiType:android,null
,05-25 13:49:42.457  4163  4163 D PeopleDataManager: removeNotiInfo: id =17041470,packageName=android,isEdgeNotification=false,key=null,removeAll=false
05-25 13:49:42.457  4163  4163 D PeopleDataManager: removeNotiInfo =null
,05-25 13:49:42.457  3487  3487 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
05-25 13:49:42.457  3487  3600 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
05-25 13:49:42.457  3487  3600 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false, mScanRequestedInConnected = false
05-25 13:49:42.457  3487  3600 D WifiDisplayController: disconnect
05-25 13:49:42.457  3487  3600 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,05-25 13:49:42.457  3487  3858 D SecContentProvider: insert(), uri = 2
,05-25 13:49:42.467  3487  3858 D WIFI_P2P: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:42.467  3487  3858 D WifiP2pService: P2pDisablingState
05-25 13:49:42.467  3487  3858 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-25 13:49:42.467  3487  3858 D WifiP2pService: P2pDisablingState{ what=147458 }
05-25 13:49:42.467  3487  3858 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
05-25 13:49:42.467  3487  3858 D WifiP2pService: p2p socket connection lost
05-25 13:49:42.467  3487  3858 D WIFI_P2P: evalRequest
05-25 13:49:42.467  3487  3858 D WIFI_P2P:   done
05-25 13:49:42.467  3487  3858 D SecContentProvider: insert(), uri = 2
,05-25 13:49:42.467  3487  3600 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
05-25 13:49:42.467  3487  3600 I WifiDisplayAdapter: onP2pDisconnected
05-25 13:49:42.467  3487  3600 D IpRemoteDisplayController: disconnectWfdBridgeServer
05-25 13:49:42.467  3487  3600 D IpRemoteDisplayController: WfdBridgeServer is already null
,05-25 13:49:42.477  3157  3638 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,05-25 13:49:42.477  3487  3869 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -22]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} } wasDefault=true
05-25 13:49:42.477  3487  3869 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
05-25 13:49:42.477  3487  3869 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
05-25 13:49:42.477  9932  9932 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,05-25 13:49:42.477  3487  3860 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
05-25 13:49:42.477  3487  3858 D WifiP2pService: P2pDisabledState
,05-25 13:49:42.487  3949  3949 D WifiP2pController: onReceive android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,05-25 13:49:42.487  3487  3858 D WifiP2pService: P2pDisabledState{ what=143375 }
,05-25 13:49:42.487  3487  3858 D WifiP2pService: DefaultState{ what=143375 }
05-25 13:49:42.487  3487  3599 D EntConnectivity: Not allowed due to - mEnabled false
,05-25 13:49:42.487  9974  9974 D TimaKeyStoreProvider: TimaSignature is unavailable
,05-25 13:49:42.487  9974  9974 D ActivityThread: Added TimaKeyStore provider
05-25 13:49:42.487  3949  3949 D SoundPathController: onReceive - android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,05-25 13:49:42.487  3949  3949 D ApMirroringController: onReceive android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,05-25 13:49:42.487  3949  3949 D AllShareCastTile: onReceive : android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,05-25 13:49:42.487  3487  4408 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,05-25 13:49:42.487  3949  3949 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,05-25 13:49:42.497  9932  9932 D BluetoothA2dp: Proxy object connected
,05-25 13:49:42.497  9932  9932 D A2dpProfile: Bluetooth service connected
,05-25 13:49:42.497  3949  4259 D BluetoothTile: handleUpdateState :  supported = true, enabled = true, enabling = false, connected = false, connecting = false, mController.getLastDeviceName() = null
,05-25 13:49:42.497  3949  4154 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
05-25 13:49:42.497  3487  4920 D StatusBarManagerService: setIcon slot=bluetooth index=18 icon=StatusBarIcon(icon=Icon(typ=RESOURCE pkg=com.android.systemui id=0x7f02049a) visible user=0 )
,05-25 13:49:42.507  3487  4670 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,05-25 13:49:42.507  3487  4670 V AlarmManager:  remove PendingIntent] PendingIntent{9ff2cae: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
,05-25 13:49:42.517  3487  9991 I ApplicationPolicy: updateDataUsageMap
,05-25 13:49:42.527  3487  3487 D Tethering: Tethering got CONNECTIVITY_ACTION
,05-25 13:49:42.527  3487  3487 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:42.527  3949  4154 D NetworkController: onReceive: intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
05-25 13:49:42.527  3487  3487 I CLocInfoService: ['16.5] External Intent Received android.net.conn.CONNECTIVITY_CHANGE
05-25 13:49:42.527  3487  3599 D Tethering: MasterInitialState.processMessage what=3
05-25 13:49:42.527  3487  3487 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:42.527  3487  3487 I CLocInfoService: CLoinfo wifi false
,05-25 13:49:42.527  3487  3565 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,05-25 13:49:42.527  3487  3565 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:42.527  3487  3871 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,05-25 13:49:42.527  3487  3565 D GpsLocationProvider: updateNetworkState unavailable info: [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:42.527  3487  4245 V AlarmManager:  remove PendingIntent] PendingIntent{8da47d6: PendingIntentRecord{c57fa57 android broadcastIntent}}
,05-25 13:49:42.527  4315  4636 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,05-25 13:49:42.537  4315  4636 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,05-25 13:49:42.537  3487  3871 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,05-25 13:49:42.537  3487  4244 W SLocation: No Active Data Connection
05-25 13:49:42.537  9974  9974 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
05-25 13:49:42.537  3487  4244 W SLocation: No Active Data Connection
05-25 13:49:42.537  3487  4244 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:42.537  9974  9974 D RelationGraph: garbageCollect()
,05-25 13:49:42.547  3487  3487 V MARsPolicyManager: DataConnection: false
,05-25 13:49:42.567  3157  3638 E Netd    : netlink response contains error (No such file or directory)
05-25 13:49:42.567  3487  3857 D NtpTrustedTime: currentTimeMillis() cache hit
05-25 13:49:42.567  3157  3638 D CommandListener: Clearing all IP addresses on wlan0
05-25 13:49:42.567  3487  3857 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-25 13:49:42.567  3487  3857 D NtpTrustedTime: currentTimeMillis() cache hit
05-25 13:49:42.567  3487  3857 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
05-25 13:49:42.567  3487  3857 D NtpTrustedTime: currentTimeMillis() cache hit
05-25 13:49:42.567  3487  3857 D NtpTrustedTime: currentTimeMillis() cache hit
,05-25 13:49:42.567  3487  3869 D ConnectivityService: nai.networkMonitor.doQuit()
05-25 13:49:42.567  3487  3869 D ConnectivityService: setProvNotificationVisibleIntent SIGN_IN visible=false networkType=WIFI extraInfo=null highPriority=false
05-25 13:49:42.567  3487  3869 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: doQuit - quitNow()
05-25 13:49:42.567  3487  3869 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-25 13:49:42.567  3487  3869 E ConnectivityService: updateNetworkInfo()
05-25 13:49:42.567  3487  3869 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
05-25 13:49:42.567  3487  3869 E ConnectivityService: updateNetworkInfo()
,05-25 13:49:42.567  4163  4173 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=0,extra=Bundle[mParcelledData.dataSize=84]
05-25 13:49:42.577  4163  4163 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=0, samsung.notification.type=normal, samsung.people.package_name=android}]
,05-25 13:49:42.577  4163  4163 I PeopleStripeService: PeopleNotificationReceiver:3
05-25 13:49:42.577  4163  4163 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
,05-25 13:49:42.577  4163  4163 I PeopleDataManager: removeNotification
05-25 13:49:42.577  4163  4163 I NotificationParser: getNotiType:android,null
05-25 13:49:42.577  4163  4163 D PeopleDataManager: removeNotiInfo: id =0,packageName=android,isEdgeNotification=false,key=null,removeAll=false
05-25 13:49:42.577  4163  4163 D PeopleDataManager: removeNotiInfo =null
,05-25 13:49:42.577  4862  4862 D SamsungIME: EngineType = SWIFTKEY
05-25 13:49:42.577  4952  5065 D CellLocationSupport: onReceive ACTION = android.net.conn.CONNECTIVITY_CHANGE
05-25 13:49:42.577  4952  5065 I CellLocationSupport: onCellLocationChanged
,05-25 13:49:42.577  3949  3949 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 272
,05-25 13:49:42.587  4862  4862 D SamsungIME: mNetworkChangeReceiver isWLANConnected : false
,05-25 13:49:42.587  9974  9974 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in com.samsung.android.email.provider rsrc of package com.samsung.android.email.provider
,05-25 13:49:42.587  4952  4952 D PdnController: CONNECTIVITY_ACTION: networkType 1 isConnected false
05-25 13:49:42.587  4952  4952 D PdnController: isSuspended [false] networktype [1]
05-25 13:49:42.587  4315  4636 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
05-25 13:49:42.587  4315  4636 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,05-25 13:49:42.597  3487  3985 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:42.597  3487  4417 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-25 13:49:42.597  4952  4952 D PdnController: isPdnUp  [false] networktype [1]
05-25 13:49:42.597  4952  4952 D PdnController: Notify Result to LocalIP Registrants! : networkType [1] isConnected [false] 
,05-25 13:49:42.597  9974  9974 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-25 13:49:42.597  3487  3565 D TelephonyManager: getDataEnabled: retVal=true
,05-25 13:49:42.597  5461  5461 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@a4cef50 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-25 13:49:42.597  4952  5065 I CellLocationSupport: Block to update PANI information in non VoWIFI
05-25 13:49:42.597  4952  5065 D SlickSSConfigHandler: EVENT_LOCAL_IP_CHANGED
,05-25 13:49:42.597  3487  4671 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:42.597  4952  5065 D PdnController: isIfaceDisconnected result [true] networkType [0] interfaceName [null] 
05-25 13:49:42.597  4952  5065 D PdnController: isPdnUp  [false] networktype [0]
05-25 13:49:42.597  4952  5065 D SlickSSConfigHandler: handleNetworkStateChange: check isDefaultPDNConnected[false], mReadyForDocFetch[false
,05-25 13:49:42.607  9974  9974 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:49:42.607  3487  4920 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:42.607  6969  6969 I FOTA_AGENT: [com.samsung.android.app.syncmldm.XDMService(1060/IIllllIIlIIllIIIIlll)] WiFi network Connected : false
,05-25 13:49:42.607  3157  3634 D EnterpriseController: netId is 0
05-25 13:49:42.607  3157  3634 D Netd    : getNetworkForDns: using netid 0 for uid 10002
,05-25 13:49:42.617  3487  4196 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:42.617  4952  5065 D RegistrationManager: handleMessage(): 5
,05-25 13:49:42.617  4642  9994 E         : Error communicating to API: https://prod.yana.asideas.de/api/v2/advertising/frequencies/pl
05-25 13:49:42.617  4642  9994 E         : retrofit.RetrofitError: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
05-25 13:49:42.617  4642  9994 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:395)
05-25 13:49:42.617  4642  9994 E         : 	at retrofit.RestAdapter$RestHandler.access$100(RestAdapter.java:220)
05-25 13:49:42.617  4642  9994 E         : 	at retrofit.RestAdapter$RestHandler$1.invoke(RestAdapter.java:265)
05-25 13:49:42.617  4642  9994 E         : 	at retrofit.RxSupport$2.run(RxSupport.java:55)
05-25 13:49:42.617  4642  9994 E         : 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
05-25 13:49:42.617  4642  9994 E         : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
05-25 13:49:42.617  4642  9994 E         : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
05-25 13:49:42.617  4642  9994 E         : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
05-25 13:49:42.617  4642  9994 E         : 	at retrofit.Platform$Android$2$1.run(Platform.java:142)
05-25 13:49:42.617  4642  9994 E         : 	at java.lang.Thread.run(Thread.java:818)
05-25 13:49:42.617  4642  9994 E         : Caused by: java.net.UnknownHostException: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
05-25 13:49:42.617  4642  9994 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:470)
05-25 13:49:42.617  4642  9994 E         : 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
05-25 13:49:42.617  4642  9994 E         : 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
05-25 13:49:42.617  4642  9994 E         : 	at com.squareup.okhttp.internal.Network$1.resolveInetAddresses(Network.java:29)
05-25 13:49:42.617  4642  9994 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:187)
05-25 13:49:42.617  4642  9994 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.nextProxy(RouteSelector.java:156)
05-25 13:49:42.617  4642  9994 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.next(RouteSelector.java:98)
05-25 13:49:42.617  4642  9994 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.createNextConnection(HttpEngine.java:344)
05-25 13:49:42.617  4642  9994 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:327)
05-25 13:49:42.617  4642  9994 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:245)
05-25 13:49:42.617  4642  9994 E         : 	at com.squareup.okhttp.Call.getResponse(Call.java:267)
05-25 13:49:42.617  4642  9994 E         : 	at com.squareup.okhttp.Call$ApplicationInterceptorChain.proceed(Call.java:224)
05-25 13:49:42.617  4642  9994 E         : 	at com.squareup.okhttp.Call.getResponseWithInterceptorChain(Call.java:195)
05-25 13:49:42.617  4642  9994 E         : 	at com.squareup.okhttp.Call.execute(Call.java:79)
05-25 13:49:42.617  4642  9994 E         : 	at retrofit.client.OkClient.execute(OkClient.java:53)
05-25 13:49:42.617  4642  9994 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:326)
05-25 13:49:42.617  4642  9994 E         : 	... 9 more
05-25 13:49:42.617  4642  9994 E         : Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
05-25 13:49:42.617  4642  9994 E         : 	at libcore.io.Posix.android_getaddrinfo(Native Method)
05-25 13:49:42.617  4642  9994 E         : 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
05-25 13:49:42.617  4642  9994 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:451)
05-25 13:49:42.617  4642  9994 E         : 	... 24 more
05-25 13:49:42.617  4642  9994 E         : 
,05-25 13:49:42.617  4642  9994 E         : Unable to fetch advertisement frequency.
05-25 13:49:42.617  4642  9994 E         : retrofit.RetrofitError: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
05-25 13:49:42.617  4642  9994 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:395)
05-25 13:49:42.617  4642  9994 E         : 	at retrofit.RestAdapter$RestHandler.access$100(RestAdapter.java:220)
05-25 13:49:42.617  4642  9994 E         : 	at retrofit.RestAdapter$RestHandler$1.invoke(RestAdapter.java:265)
05-25 13:49:42.617  4642  9994 E         : 	at retrofit.RxSupport$2.run(RxSupport.java:55)
05-25 13:49:42.617  4642  9994 E         : 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
05-25 13:49:42.617  4642  9994 E         : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
05-25 13:49:42.617  4642  9994 E         : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
05-25 13:49:42.617  4642  9994 E         : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
05-25 13:49:42.617  4642  9994 E         : 	at retrofit.Platform$Android$2$1.run(Platform.java:142)
05-25 13:49:42.617  4642  9994 E         : 	at java.lang.Thread.run(Thread.java:818)
05-25 13:49:42.617  4642  9994 E         : Caused by: java.net.UnknownHostException: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
05-25 13:49:42.617  4642  9994 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:470)
05-25 13:49:42.617  4642  9994 E         : 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
05-25 13:49:42.617  4642  9994 E         : 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
05-25 13:49:42.617  4642  9994 E         : 	at com.squareup.okhttp.internal.Network$1.resolveInetAddresses(Network.java:29)
05-25 13:49:42.617  4642  9994 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:187)
05-25 13:49:42.617  4642  9994 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.nextProxy(RouteSelector.java:156)
05-25 13:49:42.617  4642  9994 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.next(RouteSelector.java:98)
05-25 13:49:42.617  4642  9994 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.createNextConnection(HttpEngine.java:344)
05-25 13:49:42.617  4642  9994 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:327)
05-25 13:49:42.617  4642  9994 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:245)
05-25 13:49:42.617  4642  9994 E         : 	at com.squareup.okhttp.Call.getResponse(Call.java:267)
05-25 13:49:42.617  4642  9994 E         : 	at com.squareup.okhttp.Call$ApplicationInterceptorChain.proceed(Call.java:224)
05-25 13:49:42.617  4642  9994 E         : 	at com.squareup.okhttp.Call.getResponseWithInterceptorChain(Call.java:195)
05-25 13:49:42.617  4642  9994 E         : 	at com.squareup.okhttp.Call.execute(Call.java:79)
05-25 13:49:42.617  4642  9994 E         : 	at retrofit.client.OkClient.execute(OkClient.java:53)
05-25 13:49:42.617  4642  9994 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:326)
05-25 13:49:42.617  4642  9994 E         : 	... 9 more
05-25 13:49:42.617  4642  9994 E         : Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
05-25 13:49:42.617  4642  9994 E         : 	at libcore.io.Posix.android_getaddrinfo(Native Method)
05-25 13:49:42.617  4642  9994 E         : 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
05-25 13:49:42.617  4642  9994 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:451)
05-25 13:49:42.617  4642  9994 E         : 	... 24 more
05-25 13:49:42.617  4642  9994 E         : 
05-25 13:49:42.617  3487  3980 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:42.617  4952  5065 D PdnController: isIfaceDisconnected result [true] networkType [11] interfaceName [null] 
05-25 13:49:42.617  4952  5065 D PdnController: isPdnUp  [false] networktype [11]
05-25 13:49:42.617  4952  5065 D RegistrationManager: setEPDGIPSecConnected [false]
05-25 13:49:42.617  4952  5065 D RegistrationManager: notifyNetworkState : NetworkType [1] IsConnected [false] IPAddresses [[]] DNSAddresses [[]] 
05-25 13:49:42.617  4952  5065 D RegistrationManager: isEPDGAvailable [false]
05-25 13:49:42.617  4952  5065 D CoreController: setState [DEREGISTERED]
05-25 13:49:42.617  4438  4438 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
05-25 13:49:42.627  9974  9974 I InjectionManager: Inside getClassLibPath caller 
05-25 13:49:42.647  9844  9844 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
05-25 13:49:42.657  9844  9844 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
05-25 13:49:42.657  9974  9974 W System  : ClassLoader referenced unknown path: /system/priv-app/SecEmail_M/lib/arm64
,05-25 13:49:42.657  3949  4154 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
05-25 13:49:42.667  9844  9844 D BluetoothAdapter: STATE_ON
05-25 13:49:42.667  3487  4408 D RCPManagerService: exchangeData() failure , invalid userId
05-25 13:49:42.667  3487  3505 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{822f498 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bad5c58 4933:com.samsung.android.providers.context/u0a9}
05-25 13:49:42.667  9844  9844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-25 13:49:42.667  9844  9844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-25 13:49:42.667  9844  9844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-25 13:49:42.667  9844  9844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-25 13:49:42.667  9844  9844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-25 13:49:42.667  9844  9844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
05-25 13:49:42.667  9844  9844 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
05-25 13:49:42.667  9844  9844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
05-25 13:49:42.667  9844  9844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
05-25 13:49:42.677  4907  4919 D A2dpStateMachine: getConnectedDevices : size=0
05-25 13:49:42.687  3487  3505 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{822f498 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a95ad21 4274:com.google.android.gms.persistent/u0a21}
05-25 13:49:42.687  4274  4274 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
05-25 13:49:42.687  7227  7401 I SQLiteDatabase: can't enable WAL for memory databases.
05-25 13:49:42.687  7227  7401 I SQLiteDatabase: can't enable WAL for memory databases.
05-25 13:49:42.697  3487  3857 D NetworkPolicy: isUidForegroundLocked: 10052, mScreenOn: true, uidstate: 6, mProxSensorScreenOff: false
05-25 13:49:42.697  4952  5065 D TranslatorCollection: translateToNwkSvcType: networkType XAN_NWK_TYPE_WLAN
05-25 13:49:42.697  4952  5065 D RegistrationManager: getNetworkType [0]
05-25 13:49:42.697  4952  5065 D CoreStackAdaptor2: notifyNetworkState() [1] isConnected [false] nwkSvcType  [XAN_NWK_TYPE_WLAN] nwkInfoType [XAN_SVC_NETWORK_SVCTYPE_WIFI] dedicated   [NONE] 
05-25 13:49:42.697  4952  5065 D TranslatorCollection: translateToNwkSvcType: networkType XAN_NWK_TYPE_WLAN
05-25 13:49:42.697  4952  5065 D CoreStackAdaptor2: ipList =  Null
05-25 13:49:42.697  4952  5065 D RegistrationManager: tryRegister(CONNECTIVITY_STATUS_CHANGE)
,05-25 13:49:42.697  4952  5065 D RegistrationManager: isPreconditionProperToGoOn
05-25 13:49:42.697  4952  5065 D RegistrationManager: isDeviceShutdown [false]
05-25 13:49:42.697  4952  5065 D RegistrationManager: isStackShuttingDownForAllPDNs [false]
05-25 13:49:42.697  4952  5065 D RegistrationManager: isDmVoLTEUpdated [false]
05-25 13:49:42.697  4952  5065 D RegistrationManager: tryRegister : Abort Reason [IMS feature disabled]
05-25 13:49:42.697  3487  3860 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
05-25 13:49:42.697  4952  5065 D RegistrationManager: tryRegister : Not all preconditions are met!
,05-25 13:49:42.697  4113  4113 I wpa_supplicant: Blacklist: Clear (all) 
,05-25 13:49:42.697  4113  4113 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
,05-25 13:49:42.707  3487  3487 I WifiTrafficPoller: evaluateTrafficStatsPolling
05-25 13:49:42.707  4315  4599 D TelephonyProvider: query: url=content://telephony/carriers/preferapn, projectionIn=[Ljava.lang.String;@d4c82c2, selection=nullselectionArgs=null, sort=name ASC
,05-25 13:49:42.707  4315  4599 D TelephonyProvider: query: match = 5
05-25 13:49:42.707  4315  4599 D TelephonyProvider: getPreferredApnId(subId = 2147483643),return -1
05-25 13:49:42.707  4315  4599 D TelephonyProvider: query: selection modified to edited!=2 and edited!=3 and edited!=5 and edited!=6
05-25 13:49:42.707  3487  3487 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
05-25 13:49:42.707  3487  3487 D HS20StateMachine: [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false]
05-25 13:49:42.707  3487  3487 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
05-25 13:49:42.707  3487  3867 I WifiHs20Service: Message received 5007
,05-25 13:49:42.707  3487  3487 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
,05-25 13:49:42.717  3487  4927 D RCPManagerService: exchangeData() failure , invalid userId
,05-25 13:49:42.717  3949  4154 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-25 13:49:42.717  9974  9974 D InjectionManager: InjectionManager
05-25 13:49:42.717  9974  9974 D InjectionManager: fillFeatureStoreMap com.samsung.android.email.provider
05-25 13:49:42.717  9974  9974 I InjectionManager: Constructor com.samsung.android.email.provider, Feature store :{}
05-25 13:49:42.717  9974  9974 I InjectionManager: featureStore :{}
,05-25 13:49:42.717  4315  4315 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,05-25 13:49:42.727  3949  4154 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-25 13:49:42.727  3949  3949 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,05-25 13:49:42.727  3949  3949 I HotspotTile: Provider is not defined returning false
,05-25 13:49:42.727  3949  3949 D HotspotTile: onReceive : 0, 0
,05-25 13:49:42.727  3949  3949 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 272
05-25 13:49:42.727  4585 10002 D MdnsClient: Multicast lock held. Releasing
,05-25 13:49:42.737  9844  9844 D BluetoothAdapter: STATE_ON
,05-25 13:49:42.737  9844  9844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-25 13:49:42.737  9844  9844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-25 13:49:42.737  9844  9844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-25 13:49:42.737  9844  9844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
05-25 13:49:42.737  9844  9844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-25 13:49:42.737  9844  9844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
05-25 13:49:42.737  9844  9844 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
05-25 13:49:42.737  9844  9844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
05-25 13:49:42.737  9844  9844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,05-25 13:49:42.737  9844  9844 D BluetoothAdapter: STATE_ON
,05-25 13:49:42.737  3487  4196 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{822f498 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{78dd1e5 8981:com.sec.android.app.shealth:remote/u0a39}
,05-25 13:49:42.747  3157  3631 D Netd    : Iface p2p0 link up
,05-25 13:49:42.747  4952  4966 D PdnController: Interface Changed p2p0 link up
,05-25 13:49:42.747  9844  9844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
05-25 13:49:42.747  3487  3577 D Tethering: interfaceLinkStateChanged p2p0, true
05-25 13:49:42.747  3487  3577 D Tethering: interfaceStatusChanged p2p0, true
,05-25 13:49:42.747  3487  3487 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
05-25 13:49:42.747  3487  3487 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
05-25 13:49:42.747  3487  3487 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
05-25 13:49:42.747  3487  3867 I WifiHs20Service: Message received 5011
05-25 13:49:42.747  3487  3860 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,05-25 13:49:42.757  3487  3487 D WifiNotificationController: SHOW_NOTI_MESSAGE : 17, visible : false, ssid : null, targetSSID : null, netId : -1, titleType : -1
05-25 13:49:42.757  3487  3487 D WifiNotificationController: showMaliciousHotspotDetectionNotification - MaliciousNetwork:null, visible:false
,05-25 13:49:42.757  4163  7403 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=17041470,extra=Bundle[mParcelledData.dataSize=84]
,05-25 13:49:42.757  4163  4163 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=17041470, samsung.notification.type=normal, samsung.people.package_name=android}]
05-25 13:49:42.757  4163  4163 I PeopleStripeService: PeopleNotificationReceiver:3
05-25 13:49:42.757  4163  4163 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
05-25 13:49:42.757  4163  4163 I PeopleDataManager: removeNotification
05-25 13:49:42.757  4163  4163 I NotificationParser: getNotiType:android,null
05-25 13:49:42.757  4163  4163 D PeopleDataManager: removeNotiInfo: id =17041470,packageName=android,isEdgeNotification=false,key=null,removeAll=false
05-25 13:49:42.757  4163  4163 D PeopleDataManager: removeNotiInfo =null
,05-25 13:49:42.757  9932  9932 D DockEventReceiver: finishStartingService: stopping service
,05-25 13:49:42.767  3487  3871 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,05-25 13:49:42.767  9844  9930 D BluetoothAdapter: STATE_ON
,05-25 13:49:42.767  4315  4599 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,05-25 13:49:42.767  4315  4599 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
05-25 13:49:42.767  3487  3871 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,05-25 13:49:42.777  9844  9930 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-25 13:49:42.777  9844  9930 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-25 13:49:42.777  9844  9930 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-25 13:49:42.777  9844  9930 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
05-25 13:49:42.777  9844  9930 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-25 13:49:42.777  9844  9930 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
05-25 13:49:42.777  9844  9930 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
05-25 13:49:42.777  9844  9930 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
05-25 13:49:42.777  9844  9930 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,05-25 13:49:42.777  9844  9930 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,05-25 13:49:42.777  9844  9908 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
05-25 13:49:42.777  4907  4907 D BleAudioService: onReceive:: INTENT mAobleStateChangeListener got : android.bluetooth.adapter.action.STATE_CHANGED
05-25 13:49:42.777  4907  4907 D BleAudioService: BluetoothAdapter.ACTION_STATE_CHANGED,  state is12
,05-25 13:49:42.777  4907  9958 D BleAudioStateMachine_L: [Disconnected] Disconnected process message: 41
05-25 13:49:42.777  4907  9958 D BleAudioStateMachine_L: [Disconnected] MSG_ADAPTER_BT_ON_EVT event received
05-25 13:49:42.777  4907  9959 D BleAudioStateMachine_R: [Disconnected] Disconnected process message: 41
05-25 13:49:42.777  4907  9959 D BleAudioStateMachine_R: [Disconnected] MSG_ADAPTER_BT_ON_EVT event received
,05-25 13:49:42.777 10007 10007 E Zygote  : v2
05-25 13:49:42.777 10007 10007 I libpersona: KNOX_SDCARD checking this for 10052
05-25 13:49:42.777 10007 10007 E Zygote  : isSdpEnabledProcess - SDP enabled
05-25 13:49:42.777 10007 10007 I libpersona: KNOX_SDCARD not a persona
05-25 13:49:42.777 10007 10007 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-25 13:49:42.777  3487  4197 I ActivityManager: Start proc 10007:com.samsung.android.email.provider:service/u0a52 for service com.samsung.android.email.provider/com.samsung.android.email.sync.service.EmailService
05-25 13:49:42.777  4907  9958 D BleAudioStateMachine: getLastConnectedDeviceAddress() for channel = 1
05-25 13:49:42.777  4907  9958 D BleAudioService: NotifyEvents: n : 0
05-25 13:49:42.777 10007 10007 E Zygote  : accessInfo : 64
05-25 13:49:42.777 10007 10007 E Zygote  : isSdpEnabledProcess - SDP enabled
05-25 13:49:42.777 10007 10007 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10052 / [uid]: 10052
05-25 13:49:42.777 10007 10007 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.email.provider:service 
05-25 13:49:42.777  4907  9959 D BleAudioStateMachine: getLastConnectedDeviceAddress() for channel = 2
05-25 13:49:42.777  4907  9959 D BleAudioService: NotifyEvents: n : 0
,05-25 13:49:42.777  3487  3565 E GpsLocationProvider: No APN found to select.
,05-25 13:49:42.787  3487  4920 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,05-25 13:49:42.787  3949  3949 D HeadsetProfile: Bluetooth service connected
,05-25 13:49:42.787  9932  9932 D HeadsetProfile: Bluetooth service connected
,05-25 13:49:42.787  3487  4920 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,05-25 13:49:42.797  3487  4196 V AlarmManager:  remove PendingIntent] PendingIntent{e3486e5: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
,05-25 13:49:42.797  3487  4920 D WifiService: setWifiEnabled: true pid=9844, uid=10078
,05-25 13:49:42.797  9844  9844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:49:42.807  4113  4113 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,05-25 13:49:42.807  4113  4113 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
05-25 13:49:42.807  3487  4920 W ActivityManager: Permission Denial: getCurrentUser() from pid=9844, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-25 13:49:42.807  3487  3860 D WifiBigDataLog: getJsonFormat() - feature : ONOF
05-25 13:49:42.807  3487  3860 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
05-25 13:49:42.807  3487  3487 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@79565ba
05-25 13:49:42.807  3487  4920 D SettingsProvider: isChangeAllowed() : name = wifi_on
05-25 13:49:42.807  3487  3487 D BluetoothHeadset: registerMessageListener
05-25 13:49:42.807  3487  4920 W WifiService: Failed getting userId using ActivityManagerNative
05-25 13:49:42.807  3487  4920 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9844, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-25 13:49:42.807  3487  4920 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-25 13:49:42.807  3487  4920 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
05-25 13:49:42.807  3487  4920 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
05-25 13:49:42.807  3487  4920 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
05-25 13:49:42.807  3487  4920 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
05-25 13:49:42.807  3487  4920 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
05-25 13:49:42.807  3487  3860 D WifiBigDataLog: init : 
,05-25 13:49:42.807  3487  3863 D WifiController: [FCC]setFccChannel() is called !!!
05-25 13:49:42.807  3487  3863 D WifiStateMachine: setFccChannel: channel = 0
,05-25 13:49:42.807  3487  3863 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
,05-25 13:49:42.807  3487  3863 D SecContentProvider: insert(), uri = 2
05-25 13:49:42.807  3157  3631 D Netd    : Iface wlan0 link up
,05-25 13:49:42.817  4952  5261 D PdnController: Interface Changed wlan0 link up
,05-25 13:49:42.817  3487  3577 D Tethering: interfaceLinkStateChanged wlan0, true
,05-25 13:49:42.817  3487  3577 D Tethering: interfaceStatusChanged wlan0, true
,05-25 13:49:42.817  4907  4907 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2) for masId0
,05-25 13:49:42.827 10007 10007 D TimaKeyStoreProvider: TimaSignature is unavailable
,05-25 13:49:42.827 10007 10007 D ActivityThread: Added TimaKeyStore provider
,05-25 13:49:42.827  3487  3506 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{822f498 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c6d3356 9932:com.android.settings/1000}
,05-25 13:49:42.827  9932  9932 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
05-25 13:49:42.827  9932  9932 D BluetoothStatusReceiver: AdapterStateChanged :: state = 12
,05-25 13:49:42.837  3487  3565 D libgps  : agps_ril_update_network_state: Waiting for IPC connection...
,05-25 13:49:42.837  4907  4918 D A2dpStateMachine: getConnectedDevices : size=0
,05-25 13:49:42.837  4907 10019 D BluetoothSocket: bindListen(): myUserId = 0
05-25 13:49:42.837  4907 10019 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,05-25 13:49:42.847  4907  4907 D BluetoothSocket: bindListen(): myUserId = 0
05-25 13:49:42.847  4907  4907 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,05-25 13:49:42.847  4907  9972 D HeadsetService: registerMessageListener
,05-25 13:49:42.847  4907  9972 D HeadsetService: registerMessageListener
05-25 13:49:42.847  4907  9949 D HeadsetStateMachine: Disconnected process message: 70, size: 0
05-25 13:49:42.847  4907  9949 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@2607958
05-25 13:49:42.847  3487  3487 I Telecom : BluetoothManager : register MessageListener
05-25 13:49:42.847  3487  3487 I Telecom : CallAudioManager: onBluetoothStateChange: no focus
,05-25 13:49:42.847  3487  3980 V AlarmManager:  remove PendingIntent] PendingIntent{308b3c8: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
,05-25 13:49:42.857  4907 10019 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,05-25 13:49:42.857  4907 10019 D BluetoothSdpJni: SDP Create record success - handle: 0
,05-25 13:49:42.857  3487  4670 I ActivityManager: Killing 9412:com.samsung.android.themecenter/1000 (adj 15): DHA:empty #33
,05-25 13:49:42.867 10007 10007 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,05-25 13:49:42.867 10007 10007 D RelationGraph: garbageCollect()
05-25 13:49:42.867  3487  4670 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{822f498 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b5595e1 4907:com.android.bluetooth/1002}
,05-25 13:49:42.867 10007 10007 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in com.samsung.android.email.provider rsrc of package com.samsung.android.email.provider
,05-25 13:49:42.867  3487  3980 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-25 13:49:42.867 10007 10007 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-25 13:49:42.877 10007 10007 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:49:42.887 10007 10007 I InjectionManager: Inside getClassLibPath caller 
,05-25 13:49:42.887  4907  4907 D BluetoothSocket: bindListen(): myUserId = 0
05-25 13:49:42.887  4907  4907 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,05-25 13:49:42.887  3487  4671 D ActivityManager: cleanUpApplicationRecord -- 9412
,05-25 13:49:42.897  3487  4671 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.themecenter, Auto Run ON
,05-25 13:49:42.907  3487  4670 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1248000  uid : 1000  pid : 3487  pkgName : BADGE_UPDATE@CPU_MIN@1
,05-25 13:49:42.907  3487  4407 V AlarmManager:  remove PendingIntent] PendingIntent{62bac61: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
05-25 13:49:42.907 10007 10007 W System  : ClassLoader referenced unknown path: /system/priv-app/SecEmail_M/lib/arm64
,05-25 13:49:42.907  4907  4907 D ObexServerSockets: Succeed to create listening sockets 
05-25 13:49:42.907  4907  4907 D ObexServerSockets: startAccept()
,05-25 13:49:42.917  4113  4113 I wpa_supplicant: Blacklist: Clear (all) 
05-25 13:49:42.917  4907 10022 D ObexServerSockets: Accepting socket connection for masId0
,05-25 13:49:42.917  4907 10023 D ObexServerSockets: Accepting socket connection for masId0
05-25 13:49:42.917  4113  4113 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
05-25 13:49:42.917  3487  3980 V AlarmManager:  remove PendingIntent] PendingIntent{3242386: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
,05-25 13:49:42.917  4907  4907 D BluetoothMapMasInstance: set MAP SDP message type : 1
05-25 13:49:42.917  4907  4907 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
05-25 13:49:42.917  4907  4907 D BluetoothSdpJni: SDP Create record success - handle: 1
,05-25 13:49:42.917  3487  6263 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:42.917  4907  4907 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5359fd5
05-25 13:49:42.917  4907  4907 D BtConfig.SecureMode: isSecureModeOn:false
05-25 13:49:42.917  3487  4196 V AlarmManager:  remove PendingIntent] PendingIntent{8da2447: PendingIntentRecord{832a900 com.android.bluetooth broadcastIntent}}
,05-25 13:49:42.927  9637  9648 D BaseReflect: null getOwnClass TEST
,05-25 13:49:42.927  9637  9648 D MethodReflector: android.content.ContentResolver getClass TEST
05-25 13:49:42.927  9637  9648 D BaseReflect: class android.content.ContentResolver isSupportClass TEST
05-25 13:49:42.927  9637  9648 D BaseReflect: class android.content.ContentResolver getOwnClass TEST
,05-25 13:49:42.937  3487  4417 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{822f498 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2bf0927 7227:com.google.android.apps.maps/u0a125}
,05-25 13:49:42.937  4150  4150 D CatchNotificationsService: Update badge
,05-25 13:49:42.937  4326  4326 D Launcher.Model: reloadBadges entered.
,05-25 13:49:42.937  5929  5929 D BadgeManager: onChange
,05-25 13:49:42.937  9637  9648 D MethodReflector: notifyChange is called
,05-25 13:49:42.947  4326  4326 D Launcher.Model: reloadBadges entered.
05-25 13:49:42.947  5929  5929 D BadgeManager: onChange
,05-25 13:49:42.947  9637  9648 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
05-25 13:49:42.947  9637  9648 D BadgeProvider: sendNotify, [notify] : null
05-25 13:49:42.947  9637  9648 D BadgeProvider: update, getCallingPackage() : com.samsung.android.email.provider
,05-25 13:49:42.947  9637  9648 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
05-25 13:49:42.947  9637  9648 D BadgeProvider: update, [uri.query] : null
05-25 13:49:42.947  9637  9648 D BadgeProvider: update, [BadgeCount] : badgecount=0
05-25 13:49:42.947  9637  9648 D BadgeProvider: update, [UpdateCount] : 1
,05-25 13:49:42.957  9637  9648 D BadgeProvider: query, [selection] : null
,05-25 13:49:42.967  9637  9647 D BadgeProvider: query, [selection] : null
,05-25 13:49:42.967 10007 10007 I BNRClientProivder, VERSION : 1.7.5: register - xml6 quick_backup : Email, QJ5JBlRnP9, com.samsung.android.email.provider.service.sCloudBNRService
,05-25 13:49:42.967 10007 10007 I QBNRClientHelper: init SyncClientHelper : Email
,05-25 13:49:42.967  3487  3570 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1d94474 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e6f874a 6550:com.enhance.gameservice/u0a111}
,05-25 13:49:42.977  3487  4670 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1d94474 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6fed98c 9704:com.sec.knox.switcher/1000}
,05-25 13:49:42.977  9704  9704 I usagelog: received in receiver
05-25 13:49:42.977  9704  9704 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
05-25 13:49:42.977  9704  9704 I KnoxUsageLogPro: premStatus:2
,05-25 13:49:42.977  9704  9704 I KnoxUsageLogPro: isEulaShown : false
05-25 13:49:42.977  9704  9704 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,05-25 13:49:42.987  3157  3631 D Netd    : Iface wlan0 link up
05-25 13:49:42.987  3157  3631 D Netd    : Iface wlan0 link up
,05-25 13:49:42.987  4952  5259 D PdnController: Interface Changed wlan0 link up
,05-25 13:49:42.987  3487  3577 D Tethering: interfaceLinkStateChanged wlan0, true
05-25 13:49:42.987  3487  3577 D Tethering: interfaceStatusChanged wlan0, true
,05-25 13:49:42.987  4952  4968 D PdnController: Interface Changed wlan0 link up
,05-25 13:49:42.987  3487  3577 D Tethering: interfaceLinkStateChanged wlan0, true
05-25 13:49:42.987  3487  3577 D Tethering: interfaceStatusChanged wlan0, true
,05-25 13:49:42.987  3157  3631 D Netd    : Iface p2p0 link down
,05-25 13:49:42.987  4952  4966 D PdnController: Interface Changed p2p0 link down
,05-25 13:49:42.997  3487  3577 D Tethering: interfaceLinkStateChanged p2p0, false
05-25 13:49:42.997  3487  3577 D Tethering: interfaceStatusChanged p2p0, false
,05-25 13:49:42.997  4326  4453 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.email.provider = 0
05-25 13:49:42.997  4326  4453 D BadgeCache: 1. updateBadgeCounts: com.android.mms = 0
05-25 13:49:42.997  4326  4453 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 1
05-25 13:49:42.997  4326  4453 D BadgeCache: 2. updateBadgeCounts: com.android.settings/.Settings = 1
05-25 13:49:42.997  4326  4453 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 1
05-25 13:49:42.997  4326  4453 D BadgeCache: 2. updateBadgeCounts: com.android.settings/.GridSettings = 1
05-25 13:49:42.997  4326  4453 D BadgeCache: 1. updateBadgeCounts: com.sec.android.app.samsungapps = 0
,05-25 13:49:42.997  4326  4453 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.sm = 0
,05-25 13:49:43.007 10026 10026 E Zygote  : v2
05-25 13:49:43.007 10026 10026 I libpersona: KNOX_SDCARD checking this for 10117
05-25 13:49:43.007 10026 10026 I libpersona: KNOX_SDCARD not a persona
,05-25 13:49:43.007  3487  3570 I ActivityManager: Start proc 10026:com.google.android.talk/u0a117 for broadcast-3 com.google.android.talk/com.google.android.apps.hangouts.service.GcmStateReceiver
05-25 13:49:43.007 10026 10026 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-25 13:49:43.007 10026 10026 E Zygote  : accessInfo : 0
05-25 13:49:43.007 10026 10026 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.talk 
,05-25 13:49:43.037 10026 10026 D TimaKeyStoreProvider: TimaSignature is unavailable
05-25 13:49:43.037 10026 10026 D ActivityThread: Added TimaKeyStore provider
,05-25 13:49:43.067  3487  3570 D ActivityManager:  getDeferredInfo final delay 300
,05-25 13:49:43.067  9637 10025 D BadgeProvider: query, [selection] : null
,05-25 13:49:43.077  4150  4150 D CatchNotificationsService: Update badge
,05-25 13:49:43.087  3487  4927 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{215ad9d u0 com.google.android.gcm.DISCONNECTED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{28ef212 10026:com.google.android.talk/u0a117}
,05-25 13:49:43.087  4326  4453 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.email.provider = 0
05-25 13:49:43.087  4326  4453 D BadgeCache: 1. updateBadgeCounts: com.android.mms = 0
,05-25 13:49:43.087  4326  4453 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 1
05-25 13:49:43.087  4326  4453 D BadgeCache: 2. updateBadgeCounts: com.android.settings/.Settings = 1
05-25 13:49:43.087  4326  4453 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 1
,05-25 13:49:43.087  4326  4453 D BadgeCache: 2. updateBadgeCounts: com.android.settings/.GridSettings = 1
05-25 13:49:43.087  4326  4453 D BadgeCache: 1. updateBadgeCounts: com.sec.android.app.samsungapps = 0
05-25 13:49:43.087  4326  4453 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.sm = 0
,05-25 13:49:43.097  9637 10024 D BadgeProvider: query, [selection] : null
,05-25 13:49:43.107 10026 10026 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,05-25 13:49:43.107 10026 10026 D RelationGraph: garbageCollect()
,05-25 13:49:43.107 10026 10026 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.google.android.talk rsrc of package com.google.android.talk
,05-25 13:49:43.117  3487  4197 D RCPManagerService: exchangeData() failure , invalid userId
05-25 13:49:43.117  3487  3505 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-25 13:49:43.117 10026 10026 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-25 13:49:43.117 10026 10026 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:49:43.117 10007 10007 D InjectionManager: InjectionManager
05-25 13:49:43.117 10007 10007 D InjectionManager: fillFeatureStoreMap com.samsung.android.email.provider
,05-25 13:49:43.117 10007 10007 I InjectionManager: Constructor com.samsung.android.email.provider, Feature store :{}
05-25 13:49:43.117 10007 10007 I InjectionManager: featureStore :{}
,05-25 13:49:43.127 10026 10026 I InjectionManager: Inside getClassLibPath caller 
,05-25 13:49:43.137 10026 10026 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm64
,05-25 13:49:43.147  3487  3854 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.147  3487  3854 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.147  3487  3854 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.147  3487  3854 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.147  3487  3854 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.147  3487  3854 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.147  3487  3854 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.147  3487  3854 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.147  3487  3854 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.147  3487  3854 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.147  3487  3854 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.147  3487  3854 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
05-25 13:49:43.147  3487  3854 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.147  3487  3854 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.147  3487  3854 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:43.157 10026 10026 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.google.android.talk rsrc of package com.google.android.talk
,05-25 13:49:43.227 10026 10026 I Babel_telephony: TeleModule.onApplicationCreate
,05-25 13:49:43.227 10026 10052 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
05-25 13:49:43.227 10026 10052 I Babel_SMS: MmsConfig.loadMmsSettings
,05-25 13:49:43.237 10026 10052 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/uaprof, mUaProfUrl=http://wap.samsungmobile.com/uaprof/uaprof.rdf
05-25 13:49:43.237 10026 10052 I Babel_SMS: MmsConfig.loadFromDatabase
,05-25 13:49:43.247 10026 10026 I Babel_Crash: Startup - clean
,05-25 13:49:43.247 10026 10052 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
05-25 13:49:43.247 10026 10052 I Babel_SMS: MmsConfig.loadFromResources
,05-25 13:49:43.247 10026 10052 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
05-25 13:49:43.247 10026 10052 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/uaprof, mUaProfUrl=http://wap.samsungmobile.com/uaprof/uaprof.rdf
,05-25 13:49:43.247  3487  4927 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.SmsReceiver newState = 2 callingPackage = 10117
,05-25 13:49:43.257  3487  4670 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.MmsWapPushReceiver newState = 2 callingPackage = 10117
,05-25 13:49:43.267  4907 10056 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,05-25 13:49:43.267  3487  4197 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.AbortSmsReceiver newState = 2 callingPackage = 10117
,05-25 13:49:43.267  4907 10056 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,05-25 13:49:43.267  3487  3985 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver newState = 2 callingPackage = 10117
,05-25 13:49:43.277  3487  4417 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.service.NoConfirmationSmsSendService newState = 1 callingPackage = 10117
,05-25 13:49:43.277 10026 10026 I Babel_Prime: startMemoryMonitor
,05-25 13:49:43.277 10026 10026 I Babel_Prime: isMemoryEnabled=false
05-25 13:49:43.277 10026 10026 I Babel_Prime: isTimerEnabled=true
,05-25 13:49:43.287 10026 10026 D InjectionManager: InjectionManager
05-25 13:49:43.287 10026 10026 D InjectionManager: fillFeatureStoreMap com.google.android.talk
,05-25 13:49:43.287 10026 10026 I InjectionManager: Constructor com.google.android.talk, Feature store :{}
05-25 13:49:43.287 10026 10026 I InjectionManager: featureStore :{}
,05-25 13:49:43.297  3487  3570 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{df2b16a u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{460065b 9844:com.thaliproject.thalitest/u0a78}
,05-25 13:49:43.307  3487  4920 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.307  3487  4920 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.307  3487  4920 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.307  3487  4920 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.307  3487  4920 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.307  3487  4920 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.307  3487  4920 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.307  3487  4920 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.307  3487  4920 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.307  3487  4920 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.307  3487  4920 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.307  3487  4920 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
05-25 13:49:43.307  3487  4920 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.307  3487  4920 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.307  3487  4920 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:43.317  3487  3980 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{df2b16a u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ea1539a 3487:system/1000}
,05-25 13:49:43.317  9844  9930 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,05-25 13:49:43.317  3487  4947 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,05-25 13:49:43.317  3487  4947 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,05-25 13:49:43.317  3487  4947 D WifiService: setWifiEnabled: true pid=9844, uid=10078
,05-25 13:49:43.327  3487  3487 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{df2b16a u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{20981f8 4585:com.google.android.gms/u0a21}
,05-25 13:49:43.327  4585  4585 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,05-25 13:49:43.327  3487  3860 D WifiBigDataLog: getJsonFormat() - feature : ONOF
05-25 13:49:43.327  3487  3860 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
05-25 13:49:43.327  3487  4947 W WifiService: Failed getting userId using ActivityManagerNative
05-25 13:49:43.327  3487  4947 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9844, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-25 13:49:43.327  3487  4947 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-25 13:49:43.327  3487  4947 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
05-25 13:49:43.327  3487  4947 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
05-25 13:49:43.327  3487  4947 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
05-25 13:49:43.327  3487  4947 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
,05-25 13:49:43.327  3487  4947 W ActivityManager: Permission Denial: getCurrentUser() from pid=9844, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-25 13:49:43.327  3487  4947 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
05-25 13:49:43.327  3487  4947 D SettingsProvider: isChangeAllowed() : name = wifi_on
05-25 13:49:43.327  3487  3863 D WifiStateMachine: setFccChannel: channel = 0
05-25 13:49:43.327  3487  3863 D WifiController: [FCC]setFccChannel() is called !!!
,05-25 13:49:43.327  3487  3863 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
,05-25 13:49:43.337  4585  5665 I iu.UploadsManager: num queued entries: 0
,05-25 13:49:43.337  4585  5665 I iu.UploadsManager: num updated entries: 0
05-25 13:49:43.337  4585  5665 I iu.SyncManager: NEXT; no task
,05-25 13:49:43.337  3487  3860 D WifiBigDataLog: init : 
,05-25 13:49:43.337  3487  4196 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{df2b16a u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{20981f8 4585:com.google.android.gms/u0a21}
,05-25 13:49:43.347  3487  4196 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{df2b16a u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a95ad21 4274:com.google.android.gms.persistent/u0a21}
,05-25 13:49:43.357 10026 10026 D Babel   : onCreate: Shutdown runnable posted in onCreate with a delay of 5000 ms.
,05-25 13:49:43.357  3487  3505 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{df2b16a u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7461dc7 9658:com.policydm/1000}
,05-25 13:49:43.367 10026 10026 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in com.google.android.talk rsrc of package com.google.android.gms
,05-25 13:49:43.367  3487  3570 D ActivityManager:  getDeferredInfo final delay 300
,05-25 13:49:43.367 10026 10026 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:49:43.367 10026 10026 I InjectionManager: Inside getClassLibPath caller 
,05-25 13:49:43.377  9658  9658 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(574/IlIIIllllIIlIIIIIlII)] Initiated Type: 0
,05-25 13:49:43.377 10026 10026 W System  : ClassLoader referenced unknown path: /system/priv-app/GmsCore/lib/arm64
,05-25 13:49:43.377  9658  9658 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
05-25 13:49:43.377  9658  9658 I DBG_POLICYDM: [com.policydm.XDMService(585/llIlIllllllllllllllI)] get NotibarState : 0
,05-25 13:49:43.387  3487  3570 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{40ead37 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e6f874a 6550:com.enhance.gameservice/u0a111}
,05-25 13:49:43.397  3487  4417 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{40ead37 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6fed98c 9704:com.sec.knox.switcher/1000}
,05-25 13:49:43.397  9704  9704 I usagelog: received in receiver
05-25 13:49:43.397  9704  9704 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
05-25 13:49:43.397  9704  9704 I KnoxUsageLogPro: premStatus:2
,05-25 13:49:43.397  9704  9704 I KnoxUsageLogPro: isEulaShown : false
05-25 13:49:43.397  9704  9704 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,05-25 13:49:43.407  3487  3570 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{290b2a4 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{460065b 9844:com.thaliproject.thalitest/u0a78}
,05-25 13:49:43.407  3487  3854 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.407  3487  3854 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.407  3487  3854 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:43.407  3487  3854 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.407  3487  3854 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.407  3487  3854 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.407  3487  3854 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.407  3487  3854 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.407  3487  3854 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.407  3487  3854 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.407  3487  3854 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.407  3487  3854 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
05-25 13:49:43.407  3487  3854 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.407  3487  3854 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.407  3487  3854 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:43.417  3487  4408 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{290b2a4 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d7dd589 9767:com.samsung.android.securitylogagent/1000}
,05-25 13:49:43.417  9767  9767 D SecurityLogAgent: NetworkReceiver : Network Change Receiver Is Called
05-25 13:49:43.417  9767  9767 D SecurityLogAgent: NetworkReceiver : Wifi_state is 0
,05-25 13:49:43.427  3487  4408 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ce2380d u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bad5c58 4933:com.samsung.android.providers.context/u0a9}
,05-25 13:49:43.427  3487  4408 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7403c2 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bad5c58 4933:com.samsung.android.providers.context/u0a9}
,05-25 13:49:43.437 10026 10026 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,05-25 13:49:43.447 10026 10026 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,05-25 13:49:43.447  3487  4407 V AlarmManager:  remove PendingIntent] PendingIntent{e829a0e: PendingIntentRecord{d600c2f com.google.android.talk startService}}
,05-25 13:49:43.457 10026 10062 D Babel   : Idle: Shutdown runnable posted in release with a delay of 5000 ms.
,05-25 13:49:43.617  3157  3631 D Netd    : Iface wlan0 link down
,05-25 13:49:43.617  4952  4968 D PdnController: Interface Changed wlan0 link down
05-25 13:49:43.617  4952  4968 D PdnController: Removed Interface [wlan0] For Network [1]
,05-25 13:49:43.617  3487  3577 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:43.617  4952  4968 D PdnController: CONNECTIVITY_ACTION: networkType 1 isConnected false
05-25 13:49:43.617  4952  4968 D PdnController: isSuspended [false] networktype [1]
,05-25 13:49:43.617  3487  3577 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.617  4952  4968 D PdnController: isPdnUp  [false] networktype [1]
,05-25 13:49:43.617  4952  4968 D PdnController: Ignore Notifying Same Result to LocalIP Registrants!
05-25 13:49:43.617  3487  3577 D Tethering: interfaceLinkStateChanged wlan0, false
05-25 13:49:43.617  3487  3577 D Tethering: interfaceStatusChanged wlan0, false
,05-25 13:49:43.667  4113  4113 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,05-25 13:49:43.667  3487  3570 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:43.677 10063 10063 E Zygote  : v2
05-25 13:49:43.677 10063 10063 I libpersona: KNOX_SDCARD checking this for 1000
05-25 13:49:43.677 10063 10063 I libpersona: KNOX_SDCARD not a persona
05-25 13:49:43.677  3487  3570 I ActivityManager: Start proc 10063:com.sec.android.diagmonagent/1000 for broadcast-5 com.sec.android.diagmonagent/.DiagMonConnectivityChangeReciever
,05-25 13:49:43.677 10063 10063 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-25 13:49:43.677 10063 10063 E Zygote  : accessInfo : 0
,05-25 13:49:43.697 10063 10063 D TimaKeyStoreProvider: TimaSignature is unavailable
05-25 13:49:43.697 10063 10063 D ActivityThread: Added TimaKeyStore provider
,05-25 13:49:43.707  3487  4408 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{1d94474 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f5b23c 10063:com.sec.android.diagmonagent/1000}
,05-25 13:49:43.707 10063 10063 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
05-25 13:49:43.707 10063 10063 D RelationGraph: garbageCollect()
,05-25 13:49:43.707 10063 10063 W ResourcesManager: getTopLevelResources: /system/priv-app/DiagMonAgent/DiagMonAgent.apk / 1.0 running in com.sec.android.diagmonagent rsrc of package com.sec.android.diagmonagent
,05-25 13:49:43.707  3487  3985 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-25 13:49:43.707 10063 10063 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-25 13:49:43.717 10063 10063 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:49:43.717 10063 10063 I InjectionManager: Inside getClassLibPath caller 
,05-25 13:49:43.717 10063 10063 W System  : ClassLoader referenced unknown path: /system/priv-app/DiagMonAgent/lib/arm64
,05-25 13:49:43.727 10063 10063 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,05-25 13:49:43.767  3487  3860 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,05-25 13:49:43.767  3487  3487 D WifiNotificationController: SHOW_NOTI_MESSAGE : 9, visible : false, ssid : <unknown ssid>, targetSSID : null, netId : -1, titleType : -1
,05-25 13:49:43.767  4163  4177 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=17041883,extra=Bundle[mParcelledData.dataSize=84]
05-25 13:49:43.767  4163  4163 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=17041883, samsung.notification.type=normal, samsung.people.package_name=android}]
05-25 13:49:43.767  3487  3487 D WifiNotificationController: SHOW_NOTI_MESSAGE : 13, visible : false, ssid : <unknown ssid>, targetSSID : null, netId : -1, titleType : 0
05-25 13:49:43.767  3487  3487 D WifiNotificationController: showCaptivePortalDisabledStatus with ssid/visible/title:null/false/0
,05-25 13:49:43.767  4163  4163 I PeopleStripeService: PeopleNotificationReceiver:3
05-25 13:49:43.767  4163  4173 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=17041473,extra=Bundle[mParcelledData.dataSize=84]
05-25 13:49:43.767  4163  4163 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
05-25 13:49:43.767  4163  4163 I PeopleDataManager: removeNotification
05-25 13:49:43.767  4163  4163 I NotificationParser: getNotiType:android,null
05-25 13:49:43.767  4163  4163 D PeopleDataManager: removeNotiInfo: id =17041883,packageName=android,isEdgeNotification=false,key=null,removeAll=false
05-25 13:49:43.767  4163  4163 D PeopleDataManager: removeNotiInfo =null
05-25 13:49:43.767  4163  4163 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=17041473, samsung.notification.type=normal, samsung.people.package_name=android}]
05-25 13:49:43.767  4163  4163 I PeopleStripeService: PeopleNotificationReceiver:3
05-25 13:49:43.767  4163  4163 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
05-25 13:49:43.767  4163  4163 I PeopleDataManager: removeNotification
05-25 13:49:43.767  4163  4163 I NotificationParser: getNotiType:android,null
05-25 13:49:43.767  4163  4163 D PeopleDataManager: removeNotiInfo: id =17041473,packageName=android,isEdgeNotification=false,key=null,removeAll=false
05-25 13:49:43.767  4163  4163 D PeopleDataManager: removeNotiInfo =null
,05-25 13:49:43.767  3487  3487 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
05-25 13:49:43.767  3487  3864 D HS20StateMachine: WIFI_STATE_DISABLED
05-25 13:49:43.767  3487  3864 D HS20StateMachine: CMD_HOTSPOT20_DISABLE
05-25 13:49:43.767  3487  3864 D HS20StateMachine: enter : DisablingState
05-25 13:49:43.767  3487  3866 D HS20SubscriptionManager: Received CMD_RELEASE_TLS, flag=1
05-25 13:49:43.767  3487  3487 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
05-25 13:49:43.767  3487  3867 I WifiHs20Service: Message received 5011
,05-25 13:49:43.767  3487  3487 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,05-25 13:49:43.777  3949  4154 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
05-25 13:49:43.777  3487  3864 D HS20StateMachine: enter : DisabledState
05-25 13:49:43.777  3949  3949 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
05-25 13:49:43.777  3949  3949 I HotspotTile: Provider is not defined returning false
05-25 13:49:43.777  3949  3949 D HotspotTile: onReceive : 1, 0
,05-25 13:49:43.777  3487  3871 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,05-25 13:49:43.777  4315  5521 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,05-25 13:49:43.777  4315  5521 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,05-25 13:49:43.777  3487  3871 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,05-25 13:49:43.777  4274  5094 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,05-25 13:49:43.787  9844  9844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:49:43.787  3487  3570 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b535bc5 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{460065b 9844:com.thaliproject.thalitest/u0a78}
,05-25 13:49:43.787  3487  3854 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.787  3487  3854 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.787  3487  3854 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.787  3487  3854 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.787  3487  3854 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.787  3487  3854 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.787  3487  3854 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.787  3487  3854 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.787  3487  3854 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.787  3487  3854 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.787  3487  3854 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.787  3487  3854 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
05-25 13:49:43.787  3487  3854 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.787  3487  3854 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.787  3487  3854 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:43.787 10063 10063 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,05-25 13:49:43.787  3487  3506 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b535bc5 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d7dd589 9767:com.samsung.android.securitylogagent/1000}
,05-25 13:49:43.787  9767  9767 D SecurityLogAgent: NetworkReceiver : Network Change Receiver Is Called
05-25 13:49:43.787  9767  9767 D SecurityLogAgent: NetworkReceiver : Wifi_state is 1
,05-25 13:49:43.797 10063 10063 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(72/onCreate)] DiagMon DM Application Start !
05-25 13:49:43.797 10063 10063 D InjectionManager: InjectionManager
05-25 13:49:43.797 10063 10063 D InjectionManager: fillFeatureStoreMap com.sec.android.diagmonagent
,05-25 13:49:43.797 10063 10063 I InjectionManager: Constructor com.sec.android.diagmonagent, Feature store :{}
05-25 13:49:43.797 10063 10063 I InjectionManager: featureStore :{}
05-25 13:49:43.797 10063 10063 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
05-25 13:49:43.797 10063 10063 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
05-25 13:49:43.797 10063 10063 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
05-25 13:49:43.797 10063 10063 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
05-25 13:49:43.797  3487  3505 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:43.807 10075 10075 E Zygote  : v2
05-25 13:49:43.807 10075 10075 I libpersona: KNOX_SDCARD checking this for 10142
05-25 13:49:43.807 10075 10075 I libpersona: KNOX_SDCARD not a persona
,05-25 13:49:43.807 10075 10075 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
05-25 13:49:43.807  3487  3505 I ActivityManager: Start proc 10075:com.samsung.android.sm.policy/u0a142 for broadcast-5 com.samsung.android.sm.policy/.PolicyBroadCastReceiver
05-25 13:49:43.807  3487  3505 I ActivityManager: Killing 9445:com.samsung.android.bbc.bbcagent/1000 (adj 15): DHA:empty #33
,05-25 13:49:43.807 10075 10075 E Zygote  : accessInfo : 0
05-25 13:49:43.807 10075 10075 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.sm.policy 
,05-25 13:49:43.827 10075 10075 D TimaKeyStoreProvider: TimaSignature is unavailable
05-25 13:49:43.827 10075 10075 D ActivityThread: Added TimaKeyStore provider
,05-25 13:49:43.827  3487  4196 D ActivityManager: cleanUpApplicationRecord -- 9445
,05-25 13:49:43.827  3487  4196 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.bbc.bbcagent, Auto Run ON
05-25 13:49:43.827  9844  9930 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,05-25 13:49:43.827  3487  3985 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,05-25 13:49:43.837  3487  3985 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,05-25 13:49:43.837  3487  3985 D WifiService: setWifiEnabled: true pid=9844, uid=10078
,05-25 13:49:43.837  3487  4920 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{1d94474 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7d2491a 10075:com.samsung.android.sm.policy/u0a142}
,05-25 13:49:43.837  3487  3985 W ActivityManager: Permission Denial: getCurrentUser() from pid=9844, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-25 13:49:43.837  3487  3985 W WifiService: Failed getting userId using ActivityManagerNative
05-25 13:49:43.837  3487  3985 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9844, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-25 13:49:43.837  3487  3985 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-25 13:49:43.837  3487  3985 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
05-25 13:49:43.837  3487  3985 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
05-25 13:49:43.837  3487  3985 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
05-25 13:49:43.837  3487  3985 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
05-25 13:49:43.837  3487  3985 D SettingsProvider: isChangeAllowed() : name = wifi_on
05-25 13:49:43.837  3487  3985 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
05-25 13:49:43.837  3487  3863 D WifiController: [FCC]setFccChannel() is called !!!
05-25 13:49:43.837  3487  3863 D WifiStateMachine: setFccChannel: channel = 0
05-25 13:49:43.837  3487  3863 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
05-25 13:49:43.837  3487  3863 E WifiController: illegal state found both WifiController and WifiStateMachine
05-25 13:49:43.837  3487  3565 D libgps  : agps_ril_update_network_state: Waiting for IPC connection - timeout
05-25 13:49:43.837  3487  3565 E libgps  : LIBGPS: Cannot communicate (write) with a GPSD
05-25 13:49:43.837  3487  3565 E libgps  : IPC Communication Error, ../../../../tmp/14982990_270314/allPartners/os/android/gps_interface/gpsi_client/GpsiClient.cpp:1710 agps_ril_update_network_state
05-25 13:49:43.837  3487  3565 D libgps  : agps_ril_update_network_availability: Waiting for IPC connection...
,05-25 13:49:43.847 10075 10075 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
05-25 13:49:43.847 10075 10075 D RelationGraph: garbageCollect()
,05-25 13:49:43.847 10075 10075 W ResourcesManager: getTopLevelResources: /system/app/SCPMClient/SCPMClient.apk / 1.0 running in com.samsung.android.sm.policy rsrc of package com.samsung.android.sm.policy
,05-25 13:49:43.847  3487  4671 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-25 13:49:43.847 10075 10075 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-25 13:49:43.847 10075 10075 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:49:43.847 10075 10075 I InjectionManager: Inside getClassLibPath caller 
,05-25 13:49:43.847 10075 10075 W System  : ClassLoader referenced unknown path: /system/app/SCPMClient/lib/arm64
,05-25 13:49:43.857 10075 10075 D InjectionManager: InjectionManager
,05-25 13:49:43.857 10075 10075 D InjectionManager: fillFeatureStoreMap com.samsung.android.sm.policy
05-25 13:49:43.857 10075 10075 I InjectionManager: Constructor com.samsung.android.sm.policy, Feature store :{}
05-25 13:49:43.857 10075 10075 I InjectionManager: featureStore :{}
,05-25 13:49:43.857  3487  4920 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:43.867 10087 10087 E Zygote  : v2
05-25 13:49:43.867 10087 10087 I libpersona: KNOX_SDCARD checking this for 5005
05-25 13:49:43.867 10087 10087 I libpersona: KNOX_SDCARD not a persona
,05-25 13:49:43.867 10087 10087 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-25 13:49:43.867 10087 10087 E Zygote  : accessInfo : 0
,05-25 13:49:43.867 10087 10087 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.app.FileShareClient 
,05-25 13:49:43.867  3487  4920 I ActivityManager: Start proc 10087:com.samsung.android.app.FileShareClient/5005 for broadcast-5 com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver
05-25 13:49:43.867  3487  4920 I ActivityManager: Killing 9457:com.google.android.apps.docs/u0a98 (adj 15): DHA:empty #33
,05-25 13:49:43.877 10087 10087 D TimaKeyStoreProvider: TimaSignature is unavailable
05-25 13:49:43.877 10087 10087 D ActivityThread: Added TimaKeyStore provider
,05-25 13:49:43.887  3487  3506 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{aeb3c4b u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f89b628 10087:com.samsung.android.app.FileShareClient/5005}
,05-25 13:49:43.887  3487  4197 D ActivityManager: cleanUpApplicationRecord -- 9457
,05-25 13:49:43.887  3487  4197 D ActivityManager: isAutoRunBlockedApp:: com.google.android.apps.docs, Auto Run ON
,05-25 13:49:43.897 10087 10087 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,05-25 13:49:43.897 10087 10087 D RelationGraph: garbageCollect()
05-25 13:49:43.897 10087 10087 W ResourcesManager: getTopLevelResources: /system/app/AllshareFileShareClient/AllshareFileShareClient.apk / 1.0 running in com.samsung.android.app.FileShareClient rsrc of package com.samsung.android.app.FileShareClient
,05-25 13:49:43.897  3487  4196 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-25 13:49:43.897 10087 10087 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-25 13:49:43.897 10087 10087 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:49:43.897 10087 10087 I InjectionManager: Inside getClassLibPath caller 
,05-25 13:49:43.897 10087 10087 W System  : ClassLoader referenced unknown path: /system/app/AllshareFileShareClient/lib/arm64
,05-25 13:49:43.907 10087 10087 D InjectionManager: InjectionManager
05-25 13:49:43.907 10087 10087 D InjectionManager: fillFeatureStoreMap com.samsung.android.app.FileShareClient
05-25 13:49:43.907 10087 10087 I InjectionManager: Constructor com.samsung.android.app.FileShareClient, Feature store :{}
05-25 13:49:43.907 10087 10087 I InjectionManager: featureStore :{}
,05-25 13:49:43.907 10087 10087 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
05-25 13:49:43.907  3487  3505 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,05-25 13:49:43.907  3487  3505 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4234, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:49:43.907  3487  3505 D BatteryService: online:4, current avg:-15, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-686
05-25 13:49:43.907  3487  3487 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:49:43.907  3487  3487 I MotionRecognitionService: Plugged
05-25 13:49:43.907 10087 10087 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
05-25 13:49:43.907  3487  3487 D MotionRecognitionService:   cableConnection= 1
05-25 13:49:43.907  3487  3487 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:49:43.907  3487  3487 D MotionRecognitionService: skip setTransmitPower. 
05-25 13:49:43.907  3487  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:49:43.907  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
05-25 13:49:43.907  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:49:43.907  3949  3949 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
05-25 13:49:43.907  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
05-25 13:49:43.907  3949  3949 D PowerUI.Notification: There is no change about charging status, so return!
,05-25 13:49:43.917  4952  4952 D CommonServiceConfiguration: getStringValueSetting
05-25 13:49:43.917  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,05-25 13:49:43.917  4907  4907 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-25 13:49:43.917  4907  9949 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-25 13:49:43.917  4952  4952 D BatteryMonitor: new battery level: 100
,05-25 13:49:43.917 10087 10087 D FileShare-Client: Outbound.stopDelayTimer - 
,05-25 13:49:43.917  3487  4197 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:43.927 10100 10100 E Zygote  : v2
05-25 13:49:43.927 10100 10100 I libpersona: KNOX_SDCARD checking this for 5005
05-25 13:49:43.927 10100 10100 I libpersona: KNOX_SDCARD not a persona
,05-25 13:49:43.927 10100 10100 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
05-25 13:49:43.927 10100 10100 E Zygote  : accessInfo : 0
,05-25 13:49:43.927 10100 10100 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.app.FileShareServer 
,05-25 13:49:43.927  3487  4197 I ActivityManager: Start proc 10100:com.samsung.android.app.FileShareServer/5005 for broadcast-5 com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver
,05-25 13:49:43.927  3487  4197 I ActivityManager: Killing 9479:com.samsung.android.app.filterinstaller/1000 (adj 15): DHA:empty #33
,05-25 13:49:43.937  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,05-25 13:49:43.947  3487  4417 D ActivityManager: cleanUpApplicationRecord -- 9479
,05-25 13:49:43.947  3487  4417 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.filterinstaller, Auto Run ON
,05-25 13:49:43.947 10100 10100 D TimaKeyStoreProvider: TimaSignature is unavailable
05-25 13:49:43.947 10100 10100 D ActivityThread: Added TimaKeyStore provider
,05-25 13:49:43.957  3487  4408 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{aeb3c4b u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e12ef41 10100:com.samsung.android.app.FileShareServer/5005}
,05-25 13:49:43.967 10100 10100 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
05-25 13:49:43.967 10100 10100 D RelationGraph: garbageCollect()
,05-25 13:49:43.967 10100 10100 W ResourcesManager: getTopLevelResources: /system/app/AllshareFileShareServer/AllshareFileShareServer.apk / 1.0 running in com.samsung.android.app.FileShareServer rsrc of package com.samsung.android.app.FileShareServer
,05-25 13:49:43.967  3487  3860 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
05-25 13:49:43.967  3487  3860 E WifiStateMachine: Error! unhandled message{ when=-3m24s554ms what=131156 target=com.android.internal.util.StateMachine$SmHandler }
05-25 13:49:43.967  3487  4196 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-25 13:49:43.967 10100 10100 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
05-25 13:49:43.967  3487  3860 E WifiHW  : ##################### set firmware type 0 #####################
,05-25 13:49:43.967  3157  3638 I WifiHW  : wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
05-25 13:49:43.967 10100 10100 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:49:43.967  3157  3638 I WifiHW  : module is semco
05-25 13:49:43.967  3157  3638 E WifiHW  : ==========[WIFI] SEMCO MODULE ===========
05-25 13:49:43.967  3157  3638 I WifiHW  : wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
05-25 13:49:43.967  3157  3638 E WifiHW  : TEMP_FAILURE_RETRY complete
05-25 13:49:43.967  3157  3638 D SoftapController: Softap fwReload - Ok
,05-25 13:49:43.967  3157  3638 D CommandListener: Setting iface cfg
05-25 13:49:43.967  3157  3638 D CommandListener: Trying to bring down wlan0
,05-25 13:49:43.967 10100 10100 I InjectionManager: Inside getClassLibPath caller 
,05-25 13:49:43.967  3157  3638 D CommandListener: Clearing all IP addresses on wlan0
,05-25 13:49:43.977  3487  3860 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,05-25 13:49:43.977  3487  3860 D wifi    : Can not initialize the vendor function pointer table
05-25 13:49:43.977  3487  3860 E WifiNative-HAL: Could not start hal
05-25 13:49:43.977  3487  3860 E WifiStateMachine: Failed to start HAL
,05-25 13:49:43.977  3487  3860 E WifiHW  : supplicant_name : p2p_supplicant
,05-25 13:49:43.977 10100 10100 D InjectionManager: InjectionManager
,05-25 13:49:43.977 10100 10100 D InjectionManager: fillFeatureStoreMap com.samsung.android.app.FileShareServer
05-25 13:49:43.977 10100 10100 I InjectionManager: Constructor com.samsung.android.app.FileShareServer, Feature store :{}
05-25 13:49:43.977 10100 10100 I InjectionManager: featureStore :{}
,05-25 13:49:43.977 10100 10100 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,05-25 13:49:43.977 10100 10100 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,05-25 13:49:43.977 10100 10100 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,05-25 13:49:43.987  3487  3980 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:43.987  3487  3980 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{df2b16a u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7461dc7 9658:com.policydm/1000}
,05-25 13:49:43.987  9658  9658 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(51/onReceive)] RegistrationReceiver onReceive! action = android.net.conn.CONNECTIVITY_CHANGE
,05-25 13:49:43.997  3487  3980 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:43.997  3487  3980 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{df2b16a u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c179cff 8501:com.osp.app.signin/u0a44}
,05-25 13:49:43.997  8501  8501 I SA      : [OR] onReceive log=[SA = 2.2.02-12 V = 23 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = pl_PL CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hero2lte P = hero2ltexx I = MMB29K M = SM-G935F OKLEFT false DIS MMB29K.G935FXXU1BPJG PSS = 5.460694751064798  ]
,05-25 13:49:43.997  8501  8501 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
05-25 13:49:43.997  8501  8501 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,05-25 13:49:44.007  8501  8501 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
05-25 13:49:44.007  8501  8501 I SA      : [OR] == isSIMCardReady false ==
,05-25 13:49:44.007  8501  8501 I SA      : [SCU] == networkStateCheck == false
05-25 13:49:44.007  8501  8501 I SA      : [OR] onReceive END
,05-25 13:49:44.007  3487  4196 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:44.007  3487  4196 I ActivityManager: Killing 9495:com.sec.android.widgetapp.samsungapps/u0a110 (adj 15): DHA:empty #33
,05-25 13:49:44.017  3487  4196 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{df2b16a u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b599297 6969:com.wssyncmldm/1000}
,05-25 13:49:44.027  3487  4920 D ActivityManager: cleanUpApplicationRecord -- 9495
,05-25 13:49:44.027  3487  4920 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.widgetapp.samsungapps, Auto Run ON
,05-25 13:49:44.047  3487  4197 D ActivityManager:  getDeferredInfo final delay 80
,05-25 13:49:44.077  3487  3860 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,05-25 13:49:44.077  3487  3487 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
,05-25 13:49:44.077  3487  3487 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
05-25 13:49:44.077  3487  3867 I WifiHs20Service: Message received 5011
,05-25 13:49:44.077  3487  3487 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,05-25 13:49:44.077  3487  3871 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
05-25 13:49:44.087  3949  4154 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
05-25 13:49:44.087  3949  3949 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,05-25 13:49:44.087  3949  3949 I HotspotTile: Provider is not defined returning false
05-25 13:49:44.087  4315  4636 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
05-25 13:49:44.087  4315  4636 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
05-25 13:49:44.087  3949  3949 D HotspotTile: onReceive : 2, 0
,05-25 13:49:44.087  3487  3871 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,05-25 13:49:44.087  9844  9844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:49:44.087  3487  3570 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3bdce6 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{460065b 9844:com.thaliproject.thalitest/u0a78}
,05-25 13:49:44.087  3487  4947 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:44.087  3487  4947 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:44.087  3487  4947 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:44.087  3487  4947 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:44.087  3487  4947 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:44.087  3487  4947 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:44.087  3487  4947 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:44.087  3487  4947 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:44.087  3487  4947 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:44.087  3487  4947 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:44.087  3487  4947 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:44.087  3487  4947 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
05-25 13:49:44.087  3487  4947 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:44.087  3487  4947 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:44.087  3487  4947 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:44.097  3487  4407 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3bdce6 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d7dd589 9767:com.samsung.android.securitylogagent/1000}
,05-25 13:49:44.097  9767  9767 D SecurityLogAgent: NetworkReceiver : Network Change Receiver Is Called
,05-25 13:49:44.097  9767  9767 D SecurityLogAgent: NetworkReceiver : Wifi_state is 2
,05-25 13:49:44.097 10112 10112 I FIPS_bssl: FIPS approved mode (1) | 10112 | /system/bin/wpa_supplicant
,05-25 13:49:44.097 10112 10112 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
05-25 13:49:44.097 10112 10112 I wpa_supplicant: Successfully initialized wpa_supplicant
05-25 13:49:44.097 10112 10112 I wpa_supplicant: set_csc_config : ifname(wlan0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x20000), vendorssid_list()
,05-25 13:49:44.097 10112 10112 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,05-25 13:49:44.107  9767  9767 D SecurityLogAgent: KnoxConfiguration : Current State = 0
05-25 13:49:44.107  9767  9767 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
05-25 13:49:44.107  9767  9767 D SecurityLogAgent: StateMachine : Initialized
05-25 13:49:44.107  9767  9767 D SecurityLogAgent: StateMachine : Changed Current State = 0
05-25 13:49:44.107  9767  9767 D SecurityLogAgent: StateMachine : Current State = 0
,05-25 13:49:44.117 10112 10112 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,05-25 13:49:44.117  3017  3017 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 10112
05-25 13:49:44.117  3017  3017 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
05-25 13:49:44.117 10112 10112 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
05-25 13:49:44.117 10112 10112 I wpa_supplicant: ssSupport state is = 1
05-25 13:49:44.117 10112 10112 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
05-25 13:49:44.117 10112 10112 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,05-25 13:49:44.117  3017  3017 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 10112
05-25 13:49:44.117  3017  3017 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x00000106
,05-25 13:49:44.117 10112 10112 I SecureStorage: [INFO]: SPID(0x00000005)ss_id will be loaded by secure_storage_daemon: /system/bin/wpa_supplicant
,05-25 13:49:44.127  3487  3570 D ActivityManager:  getDeferredInfo final delay 80
,05-25 13:49:44.207  3487  3570 D ActivityManager:  getDeferredInfo final delay 80
,05-25 13:49:44.287  3487  3570 D ActivityManager:  getDeferredInfo final delay 80
,05-25 13:49:44.337  9844  9930 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,05-25 13:49:44.347  3487  3505 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,05-25 13:49:44.347  3487  3505 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,05-25 13:49:44.347  3487  3505 D WifiService: setWifiEnabled: true pid=9844, uid=10078
05-25 13:49:44.347  3487  3505 W ActivityManager: Permission Denial: getCurrentUser() from pid=9844, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
,05-25 13:49:44.347  3487  3505 W WifiService: Failed getting userId using ActivityManagerNative
05-25 13:49:44.347  3487  3505 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9844, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-25 13:49:44.347  3487  3505 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-25 13:49:44.347  3487  3505 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
05-25 13:49:44.347  3487  3505 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
05-25 13:49:44.347  3487  3505 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
05-25 13:49:44.347  3487  3505 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
05-25 13:49:44.347  3487  3505 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
05-25 13:49:44.347  3487  3505 D SettingsProvider: isChangeAllowed() : name = wifi_on
05-25 13:49:44.347  3487  3863 D WifiController: [FCC]setFccChannel() is called !!!
05-25 13:49:44.347  3487  3863 D WifiStateMachine: setFccChannel: channel = 0
05-25 13:49:44.347  3487  3863 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
,05-25 13:49:44.367  3487  3570 D ActivityManager:  getDeferredInfo final delay 80
,05-25 13:49:44.387  3017  3017 I SecureStorage: [INFO]: SPID(0x00000005)Secure Storage Daemon finished processing with result: 0
05-25 13:49:44.387 10112 10112 I SecureStorage: [INFO]: SPID(0x00000005)Processing data has been completed
,05-25 13:49:44.407 10112 10112 I wpa_supplicant: Ctrl_iface: loading system cred
05-25 13:49:44.407 10112 10112 I SecureStorage: [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,05-25 13:49:44.427 10112 10112 I SecureStorage: [INFO]: SPID(0x00000005)This device supports Secure Storage
,05-25 13:49:44.427  3017  3017 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 10112
05-25 13:49:44.427  3017  3017 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
05-25 13:49:44.427 10112 10112 I SecureStorage: [INFO]: SPID(0x00000005)SS Daemon is running
05-25 13:49:44.427 10112 10112 I wpa_supplicant: ssSupport state is = 1
,05-25 13:49:44.427 10112 10112 I wpa_supplicant: Blacklist: Clear (all) 
,05-25 13:49:44.427 10112 10112 E wpa_supplicant: getSavedIMSI cannot open /data/misc/radio/kmem: No such file or directory
05-25 13:49:44.427 10112 10112 I wpa_supplicant: [getIMSI]: sim_num 0
,05-25 13:49:44.427 10112 10112 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,05-25 13:49:44.447  3487  3570 D ActivityManager:  getDeferredInfo final delay 80
,05-25 13:49:44.527  3487  3570 D ActivityManager:  getDeferredInfo final delay 80
,05-25 13:49:44.607  3487  3570 D ActivityManager:  getDeferredInfo final delay 80
,05-25 13:49:44.697  3487  3570 D ActivityManager:  getDeferredInfo final delay 80
,05-25 13:49:44.777  3487  3570 D ActivityManager:  getDeferredInfo final delay 80
,05-25 13:49:44.847  3487  3565 D libgps  : agps_ril_update_network_availability: Waiting for IPC connection - timeout
,05-25 13:49:44.847  3487  3565 E libgps  : LIBGPS: Cannot communicate (write) with a GPSD
05-25 13:49:44.847  3487  3565 E libgps  : IPC Communication Error, ../../../../tmp/14982990_270314/allPartners/os/android/gps_interface/gpsi_client/GpsiClient.cpp:1729 agps_ril_update_network_availability
,05-25 13:49:44.847  9844  9930 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,05-25 13:49:44.847  3487  4927 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,05-25 13:49:44.847  3487  4927 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,05-25 13:49:44.857  3487  3570 D ActivityManager:  getDeferredInfo final delay 80
,05-25 13:49:44.857  3487  4927 D WifiService: setWifiEnabled: true pid=9844, uid=10078
05-25 13:49:44.857  3487  4927 W ActivityManager: Permission Denial: getCurrentUser() from pid=9844, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
,05-25 13:49:44.857  3487  4927 W WifiService: Failed getting userId using ActivityManagerNative
05-25 13:49:44.857  3487  4927 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9844, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-25 13:49:44.857  3487  4927 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-25 13:49:44.857  3487  4927 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
05-25 13:49:44.857  3487  4927 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
05-25 13:49:44.857  3487  4927 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
05-25 13:49:44.857  3487  4927 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
05-25 13:49:44.857  3487  4927 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
05-25 13:49:44.857  3487  4927 D SettingsProvider: isChangeAllowed() : name = wifi_on
,05-25 13:49:44.857  3487  3863 D WifiStateMachine: setFccChannel: channel = 0
05-25 13:49:44.857  3487  3863 D WifiController: [FCC]setFccChannel() is called !!!
05-25 13:49:44.857  3487  3863 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
,05-25 13:49:44.907  3487  4947 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1248000  uid : 1000  pid : 3487  tag : BADGE_UPDATE@CPU_MIN@1
,05-25 13:49:44.937  3487  3570 D ActivityManager:  getDeferredInfo final delay 80
,05-25 13:49:44.947  3487  6263 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:45.017  3487  3570 D ActivityManager:  getDeferredInfo final delay 80
,05-25 13:49:45.067  3487  6263 D SSRM:n  : SIOP:: AP = 340, PST = 330 (W:10), CP = 276, CUR = -15, LCD = 30
,05-25 13:49:45.077  3487  6263 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:45.167  3487  3570 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:45.177  3157  3631 D Netd    : Iface wlan0 link up
,05-25 13:49:45.177  4952  4966 D PdnController: Interface Changed wlan0 link up
05-25 13:49:45.177  3487  3577 D Tethering: interfaceLinkStateChanged wlan0, true
05-25 13:49:45.177  3487  3577 D Tethering: interfaceStatusChanged wlan0, true
,05-25 13:49:45.177  3157  3631 D Netd    : Iface wlan0 link up
05-25 13:49:45.177  3157  3631 D Netd    : Iface wlan0 link up
05-25 13:49:45.177  3487  3570 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{df2b16a u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f2235e5 7080:com.samsung.fresco.logging/5015}
,05-25 13:49:45.177  4952  5261 D PdnController: Interface Changed wlan0 link up
,05-25 13:49:45.177  3487  3577 D Tethering: interfaceLinkStateChanged wlan0, true
05-25 13:49:45.177  3487  3577 D Tethering: interfaceStatusChanged wlan0, true
,05-25 13:49:45.187  3487  3980 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:45.187  4952  5259 D PdnController: Interface Changed wlan0 link up
05-25 13:49:45.187  3487  4670 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:45.187  3487  3577 D Tethering: interfaceLinkStateChanged wlan0, true
05-25 13:49:45.187  3487  3577 D Tethering: interfaceStatusChanged wlan0, true
,05-25 13:49:45.187  3487  4196 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:45.197  3487  4196 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{df2b16a u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e21f0f4 7478:com.sec.spp.push/u0a42}
,05-25 13:49:45.197  7478  7478 E SPPClientService: [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
05-25 13:49:45.197  7478  7478 E SPPClientService: [SystemStateMoniter] Current Time : 205783
,05-25 13:49:45.197  7478  7478 E SPPClientService: [SystemStateMoniter] No Connect : true
,05-25 13:49:45.207  3487  4196 D ActivityManager:  getDeferredInfo final delay 300
,05-25 13:49:45.217  7478 10117 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,05-25 13:49:45.287 10112 10112 I wpa_supplicant: set_csc_config : ifname(p2p0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x0), vendorssid_list()
05-25 13:49:45.287 10112 10112 I SecureStorage: [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,05-25 13:49:45.317 10112 10112 I SecureStorage: [INFO]: SPID(0x00000005)This device supports Secure Storage
,05-25 13:49:45.317  3017  3017 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 10112
,05-25 13:49:45.317  3017  3017 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
05-25 13:49:45.317 10112 10112 I SecureStorage: [INFO]: SPID(0x00000005)SS Daemon is running
,05-25 13:49:45.317 10112 10112 I wpa_supplicant: ssSupport state is = 1
05-25 13:49:45.327 10112 10112 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,05-25 13:49:45.327 10112 10112 E wpa_supplicant: nl80211: Could not configure driver mode
,05-25 13:49:45.327 10112 10112 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
05-25 13:49:45.327 10112 10112 E wpa_supplicant: p2p0: Failed to initialize driver interface
05-25 13:49:45.327 10112 10112 I wpa_supplicant: Blacklist: Clear (all) 
05-25 13:49:45.327 10112 10112 I wpa_supplicant: set_csc_config : ifname(p2p0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x0), vendorssid_list()
05-25 13:49:45.327 10112 10112 I SecureStorage: [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,05-25 13:49:45.357  9844  9930 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,05-25 13:49:45.357 10112 10112 I SecureStorage: [INFO]: SPID(0x00000005)This device supports Secure Storage
,05-25 13:49:45.367  3017  3017 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 10112
,05-25 13:49:45.367  3487  4927 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
05-25 13:49:45.367  3017  3017 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
,05-25 13:49:45.367 10112 10112 I SecureStorage: [INFO]: SPID(0x00000005)SS Daemon is running
05-25 13:49:45.367 10112 10112 I wpa_supplicant: ssSupport state is = 1
05-25 13:49:45.367  3487  4927 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,05-25 13:49:45.367 10112 10112 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,05-25 13:49:45.367  3487  4927 D WifiService: setWifiEnabled: true pid=9844, uid=10078
,05-25 13:49:45.377  3487  4927 W ActivityManager: Permission Denial: getCurrentUser() from pid=9844, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-25 13:49:45.377  3487  4927 W WifiService: Failed getting userId using ActivityManagerNative
05-25 13:49:45.377  3487  4927 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9844, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-25 13:49:45.377  3487  4927 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-25 13:49:45.377  3487  4927 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
05-25 13:49:45.377  3487  4927 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
05-25 13:49:45.377  3487  4927 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
05-25 13:49:45.377  3487  4927 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
05-25 13:49:45.377  3487  4927 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
,05-25 13:49:45.377  3487  4927 D SettingsProvider: isChangeAllowed() : name = wifi_on
05-25 13:49:45.377  3487  3863 D WifiStateMachine: setFccChannel: channel = 0
05-25 13:49:45.377  3487  3863 D WifiController: [FCC]setFccChannel() is called !!!
05-25 13:49:45.377  3487  3863 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
,05-25 13:49:45.387 10112 10112 I wpa_supplicant: P2P: Set prekey state (NONE -> NONE)
,05-25 13:49:45.397  3487  3860 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,05-25 13:49:45.397  3487  3860 E WifiStateMachine: Deffering msg in Supplicant Starting State131085
,05-25 13:49:45.397  3487  3860 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,05-25 13:49:45.397  3487  3860 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,05-25 13:49:45.407  3487  3860 D WifiBigDataLog: init : 
,05-25 13:49:45.407  3487  3860 E WifiStateMachine: Deffering msg in Supplicant Starting State131083
,05-25 13:49:45.407  3487  3860 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,05-25 13:49:45.407  3487  3860 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,05-25 13:49:45.407  3487  3860 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,05-25 13:49:45.417  3487  3570 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4d80cd4 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bad5c58 4933:com.samsung.android.providers.context/u0a9}
,05-25 13:49:45.417  3487  3860 D WifiBigDataLog: init : 
,05-25 13:49:45.417  3487  3860 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,05-25 13:49:45.417  3487  3860 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,05-25 13:49:45.427  3487  4947 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3de3e7d u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bad5c58 4933:com.samsung.android.providers.context/u0a9}
,05-25 13:49:45.437  3487  3860 D WifiBigDataLog: init : 
,05-25 13:49:45.437  3487  3860 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,05-25 13:49:45.437  3487  3860 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,05-25 13:49:45.447  3487  4947 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e58e172 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bad5c58 4933:com.samsung.android.providers.context/u0a9}
,05-25 13:49:45.457  3487  3860 D WifiBigDataLog: init : 
,05-25 13:49:45.457  3487  3860 D WifiNative-wlan0: callSECApiBoolean - ID [301]
,05-25 13:49:45.457 10112 10112 I wpa_supplicant: HOTSPOT20_ENABLE called ON
05-25 13:49:45.457 10112 10112 I wpa_supplicant: Blacklist: Clear (all) 
,05-25 13:49:45.467  3487  4947 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b4e9c3 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bad5c58 4933:com.samsung.android.providers.context/u0a9}
,05-25 13:49:45.467 10112 10112 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,05-25 13:49:45.467 10112 10112 I wpa_supplicant: wlan0: Skip scan - bUseNetwork false
,05-25 13:49:45.477  3487  3860 D WifiNative-wlan0: callSECApiInt - ID [210]
,05-25 13:49:45.477  3487  3487 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
05-25 13:49:45.477  3487  3487 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
,05-25 13:49:45.477  3487  3867 I WifiHs20Service: Message received 5011
05-25 13:49:45.477  3487  3864 D HS20StateMachine: WIFI_STATE_ENABLED
05-25 13:49:45.477  3487  3864 D HS20StateMachine: reloadCredentialsToSupplicant
05-25 13:49:45.477  3487  3864 D HotspotDBHandler: getCredentialIds
,05-25 13:49:45.487  3487  3871 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,05-25 13:49:45.487  3487  3487 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
05-25 13:49:45.487  3487  4244 W SLocation: No Active Data Connection
05-25 13:49:45.487  3949  4154 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
05-25 13:49:45.487  4315  4599 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
05-25 13:49:45.487  4315  4599 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,05-25 13:49:45.487  3487  3871 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
05-25 13:49:45.487  3949  3949 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
05-25 13:49:45.487  3949  3949 I HotspotTile: Provider is not defined returning false
,05-25 13:49:45.487  3949  3949 D HotspotTile: onReceive : 3, 0
,05-25 13:49:45.497  3949  3949 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 272
,05-25 13:49:45.497  9844  9844 D BluetoothAdapter: STATE_ON
,05-25 13:49:45.497  3487  3570 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c132240 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{460065b 9844:com.thaliproject.thalitest/u0a78}
05-25 13:49:45.497  9844  9844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-25 13:49:45.497  9844  9844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-25 13:49:45.497  9844  9844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-25 13:49:45.497  9844  9844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-25 13:49:45.497  9844  9844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-25 13:49:45.497  9844  9844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
05-25 13:49:45.497  9844  9844 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
05-25 13:49:45.497  9844  9844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
05-25 13:49:45.497  9844  9844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,05-25 13:49:45.507  9844  9844 D BluetoothAdapter: STATE_ON
,05-25 13:49:45.507  9844  9844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,05-25 13:49:45.507  3487  3985 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:45.507  3487  3985 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:45.507  3487  3985 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:45.507  3487  3985 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:45.507  3487  3985 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:45.507  3487  3985 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:45.507  3487  3985 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:45.507  3487  3985 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:45.507  3487  3985 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:45.507  3487  3985 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:45.507  3487  3985 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:45.507  3487  3985 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
05-25 13:49:45.507  3487  3985 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:45.507  3487  3985 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:45.507  3487  3985 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:45.517 10122 10122 E Zygote  : v2
,05-25 13:49:45.517 10122 10122 I libpersona: KNOX_SDCARD checking this for 10119
05-25 13:49:45.517 10122 10122 I libpersona: KNOX_SDCARD not a persona
,05-25 13:49:45.517 10122 10122 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-25 13:49:45.527  3487  3864 I ActivityManager: Start proc 10122:com.samsung.hs20provider/u0a119 for content provider com.samsung.hs20provider/.Hs20Provider
05-25 13:49:45.527 10122 10122 E Zygote  : accessInfo : 0
05-25 13:49:45.527  3487  3570 D ActivityManager:  getDeferredInfo final delay 0
05-25 13:49:45.527 10122 10122 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.samsung.hs20provider 
05-25 13:49:45.527 10112 10112 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
05-25 13:49:45.527  3487  3860 D WifiConfigStore: Loading config and enabling all networks 
,05-25 13:49:45.527  3487  3570 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{df2b16a u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{81e27c 4973:android.process.media/u0a51}
,05-25 13:49:45.537  4973  4973 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,05-25 13:49:45.537  3487  4197 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c132240 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d7dd589 9767:com.samsung.android.securitylogagent/1000}
,05-25 13:49:45.547  9767  9767 D SecurityLogAgent: NetworkReceiver : Network Change Receiver Is Called
05-25 13:49:45.547  9767  9767 D SecurityLogAgent: NetworkReceiver : Wifi_state is 3
,05-25 13:49:45.547  3487  3860 I WifiConfigStore: "NG700" is a verified password AP: true
05-25 13:49:45.547  3487  3860 E WifiConfigStore: Not a HS20
,05-25 13:49:45.547  3487  3860 D WifiConfigStore: loaded 0 passpoint configs
,05-25 13:49:45.547  3487  3505 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:45.547  3487  3860 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,05-25 13:49:45.547  3487  3860 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
05-25 13:49:45.547  3487  3860 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,05-25 13:49:45.557 10122 10122 D TimaKeyStoreProvider: TimaSignature is unavailable
05-25 13:49:45.557 10122 10122 D ActivityThread: Added TimaKeyStore provider
,05-25 13:49:45.567 10134 10134 E Zygote  : v2
05-25 13:49:45.567 10134 10134 I libpersona: KNOX_SDCARD checking this for 1000
05-25 13:49:45.567 10134 10134 I libpersona: KNOX_SDCARD not a persona
,05-25 13:49:45.567 10134 10134 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-25 13:49:45.567  3487  3505 I ActivityManager: Start proc 10134:com.samsung.android.SettingsReceiver/1000 for broadcast-5 com.samsung.android.SettingsReceiver/.SettingsIntentReceiver
05-25 13:49:45.567 10134 10134 E Zygote  : accessInfo : 0
,05-25 13:49:45.577  3487  3860 D WifiConfigStore: setNetworkPriorityDefault: networkId = 0, priority = 1
05-25 13:49:45.577  3487  3487 I WifiHs20Service: Broadcast received:android.net.wifi.CONFIGURED_NETWORKS_CHANGE
05-25 13:49:45.577  3487  3487 D WifiHs20Service: reason: 2
05-25 13:49:45.577  3487  3867 I WifiHs20Service: Message received 5014
05-25 13:49:45.577  3487  3867 E WifiHs20Service: received HS20_UTILITY_ACTION_TYPE_HS20_CONFIGURATION_CHANGED
05-25 13:49:45.577  3487  3867 E WifiHs20Service: The changed config is NULL
05-25 13:49:45.577  3487  3860 D WifiNative-wlan0: callSECApiInt - ID [65]
,05-25 13:49:45.587  9767  9767 D SecurityLogAgent: KnoxConfiguration : Current State = 0
05-25 13:49:45.587  9767  9767 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
05-25 13:49:45.587  9767  9767 D SecurityLogAgent: StateMachine : Initialized
05-25 13:49:45.587  9767  9767 D SecurityLogAgent: StateMachine : Changed Current State = 0
,05-25 13:49:45.587  9767  9767 D SecurityLogAgent: StateMachine : Current State = 0
,05-25 13:49:45.587  3487  3860 D WifiNative-wlan0: callSECApiBoolean - ID [13]
,05-25 13:49:45.587 10112 10112 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
05-25 13:49:45.587 10112 10112 I wpa_supplicant: resume autoscan
,05-25 13:49:45.587 10112 10112 I wpa_supplicant: autoscan_samsung_exponential_notify_scan : scan_interval = 8
05-25 13:49:45.587 10112 10112 I wpa_supplicant: autoscan: autoscan_notify_scan, scan_interval = 8
05-25 13:49:45.587 10112 10112 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,05-25 13:49:45.587 10112 10112 I wpa_supplicant: reset timer : RESET_TIMER 0
,05-25 13:49:45.587 10122 10122 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,05-25 13:49:45.587 10112 10112 I wpa_supplicant: P2P: Current p2p state = IDLE
,05-25 13:49:45.597 10122 10122 W ResourcesManager: getTopLevelResources: /system/app/Hs20Provider/Hs20Provider.apk / 1.0 running in com.samsung.hs20provider rsrc of package com.samsung.hs20provider
,05-25 13:49:45.587 10122 10122 D RelationGraph: garbageCollect()
,05-25 13:49:45.597  3487  4065 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-25 13:49:45.587 10112 10112 I wpa_supplicant: First Scan Start
,05-25 13:49:45.597 10122 10122 D ResourcesManager: For user 0 new overlays fetched Null
05-25 13:49:45.587 10134 10134 D TimaKeyStoreProvider: TimaSignature is unavailable
05-25 13:49:45.587 10134 10134 D ActivityThread: Added TimaKeyStore provider
,05-25 13:49:45.597 10122 10122 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
05-25 13:49:45.597 10112 10112 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,05-25 13:49:45.597 10122 10122 I InjectionManager: Inside getClassLibPath caller 
,05-25 13:49:45.607  3487  4670 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{df2b16a u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6154579 10134:com.samsung.android.SettingsReceiver/1000}
,05-25 13:49:45.607 10122 10122 W System  : ClassLoader referenced unknown path: /system/app/Hs20Provider/lib/arm64
,05-25 13:49:45.607  3487  3860 D WifiNative-wlan0: Setting external_sim to 1
05-25 13:49:45.607  3487  3860 D WifiStateMachine: [setCountryCode()] Airplane mode return !!!
,05-25 13:49:45.607  3487  3860 D WifiStateMachine: Setting OUI to DA-A1-19
,05-25 13:49:45.607 10112 10112 I wpa_supplicant: bt_status is set be DISCONNECTED
,05-25 13:49:45.617 10122 10122 D InjectionManager: InjectionManager
05-25 13:49:45.617 10122 10122 D InjectionManager: fillFeatureStoreMap com.samsung.hs20provider
,05-25 13:49:45.617 10122 10122 I InjectionManager: Constructor com.samsung.hs20provider, Feature store :{}
05-25 13:49:45.617 10122 10122 I InjectionManager: featureStore :{}
,05-25 13:49:45.617 10134 10134 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
05-25 13:49:45.617 10134 10134 D RelationGraph: garbageCollect()
,05-25 13:49:45.617  3487  3860 E WifiNative-wlan0: do suspend false
,05-25 13:49:45.617 10134 10134 W ResourcesManager: getTopLevelResources: /system/priv-app/SettingsReceiver/SettingsReceiver.apk / 1.0 running in com.samsung.android.SettingsReceiver rsrc of package com.samsung.android.SettingsReceiver
,05-25 13:49:45.617  3487  4407 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-25 13:49:45.617 10134 10134 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-25 13:49:45.627 10134 10134 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:49:45.627 10122 10133 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_credentials
,05-25 13:49:45.627 10122 10133 D HotspotProvider: CREDENTIAL
05-25 13:49:45.627 10122 10133 D HotspotProvider: No prepend tags
,05-25 13:49:45.627 10134 10134 I InjectionManager: Inside getClassLibPath caller 
,05-25 13:49:45.627  3487  3860 D WifiStateMachine:  p2p Needed be enabled 
,05-25 13:49:45.627  3487  3860 D WifiNative-HAL: Failing getSupportedFeatureset because HAL isn't started
,05-25 13:49:45.627  3487  3860 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
05-25 13:49:45.627  3487  3860 D WifiStateMachine: [FCC]Airplane on, setFccChannel(0)!!!
05-25 13:49:45.627  3487  3860 D WifiStateMachine: setFccChannelNative: channel = 0
,05-25 13:49:45.627  3487  3860 D WifiNative-wlan0: callSECApiInt - ID [230]
05-25 13:49:45.637  3487  3858 D WifiP2pService: P2pDisabledState{ what=131203 }
,05-25 13:49:45.637  3487  3487 D RttService: SCAN_AVAILABLE : 3
05-25 13:49:45.637  3487  3864 D HS20StateMachine: CMD_HOTSPOT20_ENABLE : 
05-25 13:49:45.637  3487  3864 D HS20StateMachine: enter : DiscoveringState
05-25 13:49:45.637  3487  3893 E WifiScanningService: could not start HAL
05-25 13:49:45.637  3487  3894 D RttService: DefaultState got{ when=-2ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
05-25 13:49:45.637 10134 10134 W System  : ClassLoader referenced unknown path: /system/priv-app/SettingsReceiver/lib/arm64
05-25 13:49:45.637  3487  3487 I ActivityManager: Killing 9509:com.samsung.android.app.mirrorlink/1000 (adj 15): DHA:empty #33
05-25 13:49:45.637 10134 10134 D InjectionManager: InjectionManager
05-25 13:49:45.637 10134 10134 D InjectionManager: fillFeatureStoreMap com.samsung.android.SettingsReceiver
05-25 13:49:45.637 10134 10134 I InjectionManager: Constructor com.samsung.android.SettingsReceiver, Feature store :{}
05-25 13:49:45.637 10134 10134 I InjectionManager: featureStore :{}
05-25 13:49:45.637 10134 10134 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in com.samsung.android.SettingsReceiver rsrc of package com.android.settings
05-25 13:49:45.647  3157  3638 D CommandListener: Setting iface cfg
05-25 13:49:45.647  3157  3638 D CommandListener: Trying to bring up p2p0
05-25 13:49:45.647  3157  3631 D Netd    : Iface p2p0 link up
05-25 13:49:45.647 10134 10134 D ResourcesManager: For user 0 new overlays fetched Null
05-25 13:49:45.647  3487  3860 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
05-25 13:49:45.647  3487  3858 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
05-25 13:49:45.647  3487  3858 D SecContentProvider: insert(), uri = 2
,05-25 13:49:45.647  4952  4968 D PdnController: Interface Changed p2p0 link up
05-25 13:49:45.647  3487  3577 D Tethering: interfaceLinkStateChanged p2p0, true
05-25 13:49:45.647  3487  3577 D Tethering: interfaceStatusChanged p2p0, true
,05-25 13:49:45.647  3487  3858 D WifiP2pService: P2pEnablingState
05-25 13:49:45.647  3487  3858 D WifiP2pService: P2pEnablingState{ what=147457 }
05-25 13:49:45.647  3487  3858 D WifiP2pService: P2p socket connection successful
05-25 13:49:45.647  3487  3858 D WifiP2pService: P2pEnabledState
,05-25 13:49:45.647  3487  3858 D SecContentProvider: insert(), uri = 2
,05-25 13:49:45.657  3487  3860 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,05-25 13:49:45.657 10134 10134 E ActivityThread: Failed to find provider info for com.myscript.atk.rmc
,05-25 13:49:45.657  3487  3858 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
05-25 13:49:45.657  3487  3869 E ConnectivityService: updateNetworkInfo()
05-25 13:49:45.657  3487  3869 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
,05-25 13:49:45.657  3487  3487 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,05-25 13:49:45.657  9844  9844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:49:45.657  3487  3600 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
05-25 13:49:45.657  3487  3600 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false, mScanRequestedInConnected = false
05-25 13:49:45.657  3487  3600 D WifiDisplayController: disconnect
05-25 13:49:45.657  3487  3600 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,05-25 13:49:45.667 10112 10112 I wpa_supplicant: P2P: Set Samsung Discovery Icon = 256
,05-25 13:49:45.667  9844  9844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
05-25 13:49:45.667 10112 10112 I wpa_supplicant: P2P: Set Samsung Discovery name = 
,05-25 13:49:45.667  3487  4407 D ActivityManager: cleanUpApplicationRecord -- 9509
,05-25 13:49:45.667  3487  4407 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.mirrorlink, Auto Run ON
,05-25 13:49:45.667  4315  5521 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,05-25 13:49:45.677  3487  4670 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:45.677  3487  3600 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:45.677  3487  3600 I WifiDisplayAdapter: onP2pDisconnected
05-25 13:49:45.677  3487  3600 D IpRemoteDisplayController: disconnectWfdBridgeServer
05-25 13:49:45.677  3949  3949 D WifiP2pController: onReceive android.net.wifi.p2p.CONNECTION_STATE_CHANGE
05-25 13:49:45.677  3487  3600 D IpRemoteDisplayController: WfdBridgeServer is already null
,05-25 13:49:45.687  3949  3949 D SoundPathController: onReceive - android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,05-25 13:49:45.687  3949  3949 D ApMirroringController: onReceive android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,05-25 13:49:45.687  3949  3949 D AllShareCastTile: onReceive : android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,05-25 13:49:45.687  3487  4197 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
05-25 13:49:45.687  3949  3949 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,05-25 13:49:45.697  3487  3570 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6f25f1f u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f89b628 10087:com.samsung.android.app.FileShareClient/5005}
,05-25 13:49:45.697 10087 10087 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,05-25 13:49:45.697 10087 10087 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,05-25 13:49:45.697 10087 10087 D FileShare-Client: Outbound.stopDelayTimer - 
,05-25 13:49:45.707 10147 10147 E Zygote  : v2
05-25 13:49:45.707 10147 10147 I libpersona: KNOX_SDCARD checking this for 10068
05-25 13:49:45.707 10147 10147 I libpersona: KNOX_SDCARD not a persona
,05-25 13:49:45.707 10147 10147 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-25 13:49:45.707  3487  4670 I ActivityManager: Start proc 10147:com.samsung.android.themestore/u0a68 for broadcast-5 com.samsung.android.themestore/.manager.autoSelfUpgradeService.AutoSelfUpgradeReceiver
,05-25 13:49:45.707 10147 10147 E Zygote  : accessInfo : 0
05-25 13:49:45.717 10147 10147 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.android.themestore 
,05-25 13:49:45.737  3487  3854 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6f25f1f u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e12ef41 10100:com.samsung.android.app.FileShareServer/5005}
,05-25 13:49:45.737 10147 10147 D TimaKeyStoreProvider: TimaSignature is unavailable
05-25 13:49:45.737 10147 10147 D ActivityThread: Added TimaKeyStore provider
,05-25 13:49:45.737 10100 10100 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,05-25 13:49:45.737 10100 10100 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,05-25 13:49:45.737 10100 10100 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,05-25 13:49:45.747  3487  4408 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{df2b16a u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f28226c 10147:com.samsung.android.themestore/u0a68}
,05-25 13:49:45.757  3487  4065 I ActivityManager: Killing 9521:com.sec.android.app.sbrowser/u0a141 (adj 15): DHA:empty #33
05-25 13:49:45.757  3487  3858 E WifiP2pService: Failed to set my phone number info into probe response
,05-25 13:49:45.757  3487  3858 D WifiNative-p2p0: p2pGetDeviceAddress
,05-25 13:49:45.757  3487  3858 D WifiNative-p2p0: p2pGetDeviceAddress returning 4e:66:41:a6:c7:2d
,05-25 13:49:45.757 10147 10147 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
05-25 13:49:45.757 10147 10147 D RelationGraph: garbageCollect()
,05-25 13:49:45.757 10147 10147 W ResourcesManager: getTopLevelResources: /system/priv-app/ThemeStore_3xh/ThemeStore_3xh.apk / 1.0 running in com.samsung.android.themestore rsrc of package com.samsung.android.themestore
,05-25 13:49:45.767  3487  4920 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-25 13:49:45.767 10147 10147 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
05-25 13:49:45.767  3487  3858 D WifiP2pService: DeviceAddress: 4e:c7:2d
,05-25 13:49:45.767 10147 10147 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:49:45.767 10147 10147 I InjectionManager: Inside getClassLibPath caller 
,05-25 13:49:45.767  3487  3600 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: [Phone] Samsung Galaxy S7 edge
05-25 13:49:45.767  3487  3600 D WifiDisplayController:  deviceAddress: 4e:66:41:a6:c7:2d
05-25 13:49:45.767  3487  3600 D WifiDisplayController:  primary type: 10-0050F204-5
05-25 13:49:45.767  3487  3600 D WifiDisplayController:  secondary type: null
05-25 13:49:45.767  3487  3600 D WifiDisplayController:  wps: 0
05-25 13:49:45.767  3487  3600 D WifiDisplayController:  grpcapab: 0
05-25 13:49:45.767  3487  3600 D WifiDisplayController:  devcapab: 0
05-25 13:49:45.767  3487  3600 D WifiDisplayController:  status: 3
05-25 13:49:45.767  3487  3600 D WifiDisplayController:  wfdInfo: null
05-25 13:49:45.767  3487  3600 D WifiDisplayController:  groupownerAddress: null
05-25 13:49:45.767  3487  3600 D WifiDisplayController:  GOdeviceName: null
05-25 13:49:45.767  3487  3600 D WifiDisplayController:  interfaceAddress: 
05-25 13:49:45.767  3487  3600 D WifiDisplayController:  SConnectInfo : null
05-25 13:49:45.767  3487  3600 D WifiDisplayController:  contactInfoHash : null
05-25 13:49:45.767  3487  3600 D WifiDisplayController:  ssDevInfo : 0
05-25 13:49:45.767  3487  3600 D WifiDisplayController:  iconIdx : 0
,05-25 13:49:45.777 10147 10147 W System  : ClassLoader referenced unknown path: /system/priv-app/ThemeStore_3xh/lib/arm64
,05-25 13:49:45.777  3487  3858 D WifiP2pService: sending p2p persistent groups changed broadcast
,05-25 13:49:45.777  3487  4407 D ActivityManager: cleanUpApplicationRecord -- 9521
05-25 13:49:45.777  3487  4407 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.sbrowser, Auto Run ON
,05-25 13:49:45.777 10147 10147 D a       : Exist Config : false
05-25 13:49:45.787 10147 10147 D a       : getMcc
,05-25 13:49:45.787 10147 10147 D ai      : isQaMode
,05-25 13:49:45.787  3487  3858 D WifiP2pService: InactiveState
,05-25 13:49:45.787  3487  3858 D WifiP2pService: InactiveState{ what=143376 }
05-25 13:49:45.787  3487  3858 D WifiP2pService: P2pEnabledState{ what=143376 }
,05-25 13:49:45.787  3487  3858 E WifiP2pService: Airplane mode : skipped SET_COUNTRY_CODE
,05-25 13:49:45.787 10147 10147 D a       : getMnc
,05-25 13:49:45.787 10147 10147 D a       : getCsc
05-25 13:49:45.787 10147 10147 D a       : getSystemCountryCode
05-25 13:49:45.787 10147 10147 D a       : getImei
,05-25 13:49:45.787 10147 10147 D ai      : getMd5HashString
,05-25 13:49:45.787 10147 10147 D ai      : getSha256HashString
,05-25 13:49:45.787 10147 10147 D a       : getMsisdn
,05-25 13:49:45.797  4315  4635 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,05-25 13:49:45.797 10147 10147 D a       : getModelName
,05-25 13:49:45.797 10147 10147 D a       : getVirtualModelName
05-25 13:49:45.797 10147 10147 D a       : getAndroidSDKVersion
05-25 13:49:45.797 10147 10147 D a       : getLanguageCode
05-25 13:49:45.797 10147 10147 D a       : getCountryCode
,05-25 13:49:45.797 10147 10147 D a       : getNetworkType
,05-25 13:49:45.807 10147 10147 D t       : isSupportedAodSystemFeature
,05-25 13:49:45.807 10147 10147 D a       : isLogPrintMode
,05-25 13:49:45.807 10147 10147 D ai      : isQaMode
,05-25 13:49:45.817 10147 10147 D a       : getVerName
,05-25 13:49:45.817 10147 10147 D a       : getVerCode
,05-25 13:49:45.817 10147 10147 D a       : getPackageName
,05-25 13:49:45.817 10147 10147 D a       : getAutoUpgradeInterval
05-25 13:49:45.817 10147 10147 D a       : loadCountrySearchEx
,05-25 13:49:45.827 10147 10147 I a       : voCountrySearchEx loaded.
,05-25 13:49:45.827 10147 10147 I a       : # initConfig Time : 45
05-25 13:49:45.827 10147 10147 I a       : ● MCCNNC : 260 0
05-25 13:49:45.827 10147 10147 I a       : ● Model : SM-G935F_TM
05-25 13:49:45.827 10147 10147 I a       : ● MyApp Vertion : 1.03.22(20160524)
05-25 13:49:45.827 10147 10147 I a       : ● OS Vertion : 23
,05-25 13:49:45.837 10147 10147 D InjectionManager: InjectionManager
,05-25 13:49:45.837 10147 10147 D InjectionManager: fillFeatureStoreMap com.samsung.android.themestore
05-25 13:49:45.837 10147 10147 I InjectionManager: Constructor com.samsung.android.themestore, Feature store :{}
05-25 13:49:45.837 10147 10147 I InjectionManager: featureStore :{}
,05-25 13:49:45.837 10147 10147 D AutoSelfUpgradeReceiver: onReceive() android.net.conn.CONNECTIVITY_CHANGE
,05-25 13:49:45.847  3487  4197 D ActivityManager:  getDeferredInfo final delay 80
,05-25 13:49:45.847  3487  4197 I ActivityManager: Killing 9536:com.facebook.system/u0a14 (adj 15): DHA:empty #33
,05-25 13:49:45.887  9844  9930 D BluetoothAdapter: STATE_ON
,05-25 13:49:45.887  3487  3980 D ActivityManager: cleanUpApplicationRecord -- 9536
,05-25 13:49:45.887  3487  3980 D ActivityManager: isAutoRunBlockedApp:: com.facebook.system, Auto Run ON
,05-25 13:49:45.887  9844  9930 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-25 13:49:45.887  9844  9930 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-25 13:49:45.887  9844  9930 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-25 13:49:45.887  9844  9930 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-25 13:49:45.887  9844  9930 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-25 13:49:45.887  9844  9930 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
05-25 13:49:45.887  9844  9930 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
05-25 13:49:45.887  9844  9930 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
05-25 13:49:45.887  9844  9930 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
05-25 13:49:45.897  9844  9908 D BluetoothAdapter: enable()
,05-25 13:49:45.907  9844  9908 D BluetoothAdapter: enable(): BT is already enabled..!
,05-25 13:49:45.917  3487  3570 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a1bc035 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bad5c58 4933:com.samsung.android.providers.context/u0a9}
,05-25 13:49:45.917  9844  9908 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,05-25 13:49:45.917  3487  4417 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,05-25 13:49:45.917  3487  3817 V AlarmManager: Expired Alarm result :4
,05-25 13:49:45.927  3487  4417 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,05-25 13:49:45.927  3487  4417 D WifiService: setWifiEnabled: true pid=9844, uid=10078
,05-25 13:49:45.927  3487  3570 D ActivityManager:  getDeferredInfo final delay 80
,05-25 13:49:45.927  3487  4417 W WifiService: Failed getting userId using ActivityManagerNative
05-25 13:49:45.927  3487  4417 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9844, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-25 13:49:45.927  3487  4417 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-25 13:49:45.927  3487  4417 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
05-25 13:49:45.927  3487  4417 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
05-25 13:49:45.927  3487  4417 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
05-25 13:49:45.927  3487  4417 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
05-25 13:49:45.927  3487  4417 W ActivityManager: Permission Denial: getCurrentUser() from pid=9844, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-25 13:49:45.927  3487  4417 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
05-25 13:49:45.927  3487  4417 D SettingsProvider: isChangeAllowed() : name = wifi_on
05-25 13:49:45.927  3487  3863 D WifiStateMachine: setFccChannel: channel = 0
,05-25 13:49:45.927  3487  3863 D WifiController: [FCC]setFccChannel() is called !!!
05-25 13:49:45.927  3487  3860 D WifiBigDataLog: getJsonFormat() - feature : ONOF
05-25 13:49:45.927  3487  3863 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
05-25 13:49:45.927  9844  9908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
05-25 13:49:45.937  3487  3860 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
05-25 13:49:45.927  9844  9908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,05-25 13:49:45.927  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
05-25 13:49:45.927  9844  9908 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
05-25 13:49:45.937  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
05-25 13:49:45.937  9844  9908 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4bb8eaf removed from the list
05-25 13:49:45.937  9844  9908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4bb8eaf removed from the list
05-25 13:49:45.937  9844  9908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,05-25 13:49:45.937  9844  9908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3af42bc removed from the list
05-25 13:49:45.937  9844  9908 D io.jxcore.node.ConnectivityMonitor: stop
05-25 13:49:45.937  9844  9908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
05-25 13:49:45.937  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
05-25 13:49:45.937  9844  9908 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testRun
,05-25 13:49:45.937  9844 10166 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,05-25 13:49:45.937  9844 10166 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,05-25 13:49:45.947  3487  3860 D WifiBigDataLog: init : 
05-25 13:49:45.947  3157  3634 D EnterpriseController: netId is 0
05-25 13:49:45.947  3157  3634 D Netd    : getNetworkForDns: using netid 0 for uid 10078
05-25 13:49:45.947  3487  3860 D WifiStateMachine: setFccChannelNative: channel = 0
05-25 13:49:45.947  3487  3860 D WifiNative-wlan0: callSECApiInt - ID [230]
,05-25 13:49:45.957  9844 10168 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,05-25 13:49:45.957  9844 10168 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
05-25 13:49:45.957  9844 10168 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-25 13:49:45.957  9844 10166 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
05-25 13:49:45.957  9844 10166 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
05-25 13:49:45.957  9844 10166 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-25 13:49:45.957  9844 10168 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-25 13:49:45.957  9844 10166 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,05-25 13:49:45.957  9844 10168 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
05-25 13:49:45.957  9844 10166 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,05-25 13:49:45.957  9844 10171 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 238, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:45.957  9844 10171 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:49:45.957  9844 10171 D io.jxcore.node.StreamCopyingThread:  id: 75
,05-25 13:49:45.957  3487  4927 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{667ce3b u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bad5c58 4933:com.samsung.android.providers.context/u0a9}
,05-25 13:49:45.957  9844 10170 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 237, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:45.957  9844 10170 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:49:45.957  9844 10170 D io.jxcore.node.StreamCopyingThread:  id: 74
,05-25 13:49:45.957  9844 10172 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 239, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:45.957  9844 10172 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:49:45.957  9844 10172 D io.jxcore.node.StreamCopyingThread:  id: 74
,05-25 13:49:45.957  9844 10172 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 239, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:45.957  9844 10172 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:49:45.957  9844 10172 D io.jxcore.node.StreamCopyingThread:  id: 74
,05-25 13:49:45.957  9844 10173 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 240, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:45.957  9844 10173 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:49:45.957  9844 10173 D io.jxcore.node.StreamCopyingThread:  id: 75
05-25 13:49:45.957  9844 10172 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:45.957  9844 10172 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:49:45.957  9844 10172 D io.jxcore.node.StreamCopyingThread:  id: 74
05-25 13:49:45.957  9844 10172 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
05-25 13:49:45.957  9844 10172 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
05-25 13:49:45.957  9844 10172 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
05-25 13:49:45.957  9844 10172 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,05-25 13:49:45.957  9844 10172 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
05-25 13:49:45.957  9844 10173 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 240, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:45.957  9844 10173 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:49:45.957  9844 10173 D io.jxcore.node.StreamCopyingThread:  id: 75
05-25 13:49:45.957  9844 10172 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
05-25 13:49:45.957  9844 10173 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:45.957  9844 10173 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:49:45.957  9844 10173 D io.jxcore.node.StreamCopyingThread:  id: 75
05-25 13:49:45.957  9844 10173 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
05-25 13:49:45.957  9844 10173 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
05-25 13:49:45.957  9844 10172 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 239, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:45.957  9844 10172 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:49:45.957  9844 10172 D io.jxcore.node.StreamCopyingThread:  id: 74 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,05-25 13:49:45.957  9844 10173 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
05-25 13:49:45.957  9844 10173 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
05-25 13:49:45.957  9844 10173 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
05-25 13:49:45.957  9844 10173 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
05-25 13:49:45.957  9844 10173 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 240, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:45.957  9844 10173 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:49:45.957  9844 10173 D io.jxcore.node.StreamCopyingThread:  id: 75 .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,05-25 13:49:45.957  9844 10171 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 238, thread name: OutgoingSocketThread/Sender): Socket closed
05-25 13:49:45.957  9844 10170 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 237, thread name: IncomingSocketThread/Sender): Socket closed
05-25 13:49:45.957  9844 10171 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 238, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:45.957  9844 10171 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:49:45.957  9844 10171 D io.jxcore.node.StreamCopyingThread:  id: 75 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
05-25 13:49:45.957  9844 10170 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 237, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:45.957  9844 10170 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:49:45.957  9844 10170 D io.jxcore.node.StreamCopyingThread:  id: 74 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
05-25 13:49:45.957  9844 10171 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
05-25 13:49:45.957  9844 10170 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
05-25 13:49:45.957  9844 10171 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
05-25 13:49:45.957  9844 10170 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
05-25 13:49:45.957  9844 10171 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 238, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:45.957  9844 10171 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:49:45.957  9844 10171 D io.jxcore.node.StreamCopyingThread:  id: 75 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
,05-25 13:49:45.957  9844 10170 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 237, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:45.957  9844 10170 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:49:45.957  9844 10170 D io.jxcore.node.StreamCopyingThread:  id: 74 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
,05-25 13:49:46.007  3487  3570 D ActivityManager:  getDeferredInfo final delay 80
,05-25 13:49:46.087  3487  3570 D ActivityManager:  getDeferredInfo final delay 80
,05-25 13:49:46.177  3157  3631 D Netd    : Iface wlan0 link up
,05-25 13:49:46.177 10112 10112 I wpa_supplicant: nl80211: Received scan results (10 BSSes)
05-25 13:49:46.177  4952  5259 D PdnController: Interface Changed wlan0 link up
05-25 13:49:46.177  3487  3577 D Tethering: interfaceLinkStateChanged wlan0, true
05-25 13:49:46.177  3487  3577 D Tethering: interfaceStatusChanged wlan0, true
05-25 13:49:46.177 10112 10112 I wpa_supplicant: autoscan_samsung_exponential_notify_scan : scan_interval = 8
05-25 13:49:46.177 10112 10112 I wpa_supplicant: autoscan: autoscan_notify_scan, scan_interval = 8
05-25 13:49:46.177 10112 10112 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
05-25 13:49:46.177 10112 10112 I wpa_supplicant:    allow  - level is under -85dBm [-31] or selected nid [-1] [0]
,05-25 13:49:46.177 10112 10112 I wpa_supplicant:  selected from pick network BSS F4.99.3E ssid='NG700' et= 090,gp=03,cu=987654321,sc=987654321
,05-25 13:49:46.177 10112 10112 I wpa_supplicant:    allow  - level is under -85dBm [-31] or selected nid [-1] [0]
,05-25 13:49:46.177 10112 10112 I wpa_supplicant: wlan0: Trying to associate with f4:f2:6d:22:99:3e (SSID='NG700' freq=2442 MHz level=-31) 
,05-25 13:49:46.227  3487  3570 D ActivityManager:  getDeferredInfo final delay 80
,05-25 13:49:46.237  3487  3860 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,05-25 13:49:46.237  3487  3487 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.SCAN_RESULTS
,05-25 13:49:46.247  3487  3570 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{dd52ab1 u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a665293 3949:com.android.systemui/u0a65}
,05-25 13:49:46.257  9844  9844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:49:46.307  3487  3570 D ActivityManager:  getDeferredInfo final delay 80
,05-25 13:49:46.357 10112 10112 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,05-25 13:49:46.357  3157  3631 D Netd    : Iface wlan0 link up
05-25 13:49:46.357  3157  3631 D Netd    : Iface wlan0 link up
05-25 13:49:46.367  3157  3631 D Netd    : Iface wlan0 link up
,05-25 13:49:46.367  4952  4968 D PdnController: Interface Changed wlan0 link up
05-25 13:49:46.367  3487  3577 D Tethering: interfaceLinkStateChanged wlan0, true
05-25 13:49:46.367  3487  3577 D Tethering: interfaceStatusChanged wlan0, true
,05-25 13:49:46.367  4952  4966 D PdnController: Interface Changed wlan0 link up
05-25 13:49:46.367  3487  3577 D Tethering: interfaceLinkStateChanged wlan0, true
,05-25 13:49:46.367  3487  3577 D Tethering: interfaceStatusChanged wlan0, true
,05-25 13:49:46.367  4952  5261 D PdnController: Interface Changed wlan0 link up
05-25 13:49:46.367  3487  3577 D Tethering: interfaceLinkStateChanged wlan0, true
05-25 13:49:46.367  3487  3577 D Tethering: interfaceStatusChanged wlan0, true
,05-25 13:49:46.367 10112 10112 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,05-25 13:49:46.367 10112 10112 I wpa_supplicant: wlan0: WPA: RX message 1 of 4-Way Handshake from F4.99.3E (ver=2)
,05-25 13:49:46.377 10112 10112 I wpa_supplicant: wlan0: WPA: Sending EAPOL-Key 2/4
,05-25 13:49:46.377  3487  3860 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,05-25 13:49:46.387  3487  3860 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,05-25 13:49:46.387 10112 10112 I wpa_supplicant: wlan0: WPA: RX message 3 of 4-Way Handshake from F4.99.3E (ver=2)
,05-25 13:49:46.387 10112 10112 I wpa_supplicant: wlan0: WPA: Sending EAPOL-Key 4/4
,05-25 13:49:46.387  3487  3570 D ActivityManager:  getDeferredInfo final delay 80
,05-25 13:49:46.397  9844  9844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:49:46.397 10112 10112 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,05-25 13:49:46.397 10112 10112 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
05-25 13:49:46.397 10112 10112 I wpa_supplicant: Blacklist: Clear (temp) 
05-25 13:49:46.397  3157  3631 D Netd    : Iface wlan0 link up
,05-25 13:49:46.397  9844  9844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:49:46.397  4952  5259 D PdnController: Interface Changed wlan0 link up
05-25 13:49:46.397  3487  3577 D Tethering: interfaceLinkStateChanged wlan0, true
05-25 13:49:46.397  3487  3577 D Tethering: interfaceStatusChanged wlan0, true
,05-25 13:49:46.407  3487  3860 D WifiNative-wlan0: callSECApiVoid - ID [50]
,05-25 13:49:46.417  3487  3860 V AlarmManager:  remove PendingIntent] PendingIntent{bc32afd: PendingIntentRecord{5e093f2 android broadcastIntent}}
,05-25 13:49:46.417  3487  3860 D WifiNetworkAgent: NetworkAgent: Registering NetworkAgent
,05-25 13:49:46.417  3487  3487 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
05-25 13:49:46.417  3487  3487 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
05-25 13:49:46.417  3487  3860 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
05-25 13:49:46.417  3487  3869 E ConnectivityService: updateNetworkInfo()
05-25 13:49:46.417  3487  3869 D ConnectivityService: Got NetworkAgent Messenger
05-25 13:49:46.417  3487  3869 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-25 13:49:46.417  3487  3869 D ConnectivityService: NetworkAgent connected
,05-25 13:49:46.417  3487  3487 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
,05-25 13:49:46.417  3487  3867 I WifiHs20Service: Message received 5007
,05-25 13:49:46.417  3487  3487 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
,05-25 13:49:46.417  3157  3638 D CommandListener: Setting iface cfg
,05-25 13:49:46.427  3949  4154 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-25 13:49:46.427  4315  4315 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,05-25 13:49:46.437  3487  3570 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{be20a5 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f5b23c 10063:com.sec.android.diagmonagent/1000}
,05-25 13:49:46.437  3487  3860 D WifiStateMachine: Start Dhcp Watchdog 2
,05-25 13:49:46.437 10063 10063 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
05-25 13:49:46.437 10063 10063 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
05-25 13:49:46.437 10063 10063 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
,05-25 13:49:46.437 10063 10063 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,05-25 13:49:46.437  3487  3860 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,05-25 13:49:46.447  3487  4196 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{be20a5 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e6f874a 6550:com.enhance.gameservice/u0a111}
,05-25 13:49:46.457  9844  9844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:49:46.467  3487  3570 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{be20a5 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6fed98c 9704:com.sec.knox.switcher/1000}
,05-25 13:49:46.467  9704  9704 I usagelog: received in receiver
05-25 13:49:46.467  9704  9704 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
05-25 13:49:46.467  9704  9704 I KnoxUsageLogPro: premStatus:2
,05-25 13:49:46.467  9704  9704 I KnoxUsageLogPro: isEulaShown : false
05-25 13:49:46.467  9704  9704 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,05-25 13:49:46.477  3487  3570 D ActivityManager:  getDeferredInfo final delay 80
,05-25 13:49:46.477  3487  3860 D WifiNetworkAgent: NetworkAgent: NetworkAgent fully connected
05-25 13:49:46.477  3487  3869 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -19]
05-25 13:49:46.477  3487  3869 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,05-25 13:49:46.477  3949  4154 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-25 13:49:46.477  3487  3869 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,05-25 13:49:46.487  3487  3860 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,05-25 13:49:46.487  3487  4196 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{be20a5 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7d2491a 10075:com.samsung.android.sm.policy/u0a142}
,05-25 13:49:46.507  9844  9844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:49:46.557  3487  3570 D ActivityManager:  getDeferredInfo final delay 80
,05-25 13:49:46.587  3487  3860 E WifiNative-wlan0: do suspend false
,05-25 13:49:46.597  3487  3858 D WifiP2pService: InactiveState{ what=143375 }
05-25 13:49:46.597  3487  3858 D WifiP2pService: P2pEnabledState{ what=143375 }
,05-25 13:49:46.637 10176 10176 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,05-25 13:49:46.637  3487  3570 D ActivityManager:  getDeferredInfo final delay 80
,05-25 13:49:46.637 10176 10176 I dhcpcd  : version 5.5.6 starting
,05-25 13:49:46.637 10176 10176 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,05-25 13:49:46.717  3487  3570 D ActivityManager:  getDeferredInfo final delay 80
05-25 13:49:46.717 10176 10176 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,05-25 13:49:46.717 10176 10176 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
05-25 13:49:46.717 10176 10176 I dhcpcd  : bssid match
,05-25 13:49:46.717 10176 10176 I dhcpcd  : wlan0: rebinding lease of 192.168.1.107
,05-25 13:49:46.797  3487  3570 D ActivityManager:  getDeferredInfo final delay 80
,05-25 13:49:46.807 10176 10176 I dhcpcd  : wlan0: acknowledged 192.168.1.107 from 192.168.1.1
,05-25 13:49:46.857 10176 10176 I dhcpcd  : wlan0: leased 192.168.1.107 for 172800 seconds
,05-25 13:49:46.867  3487  3869 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,05-25 13:49:46.877  3487  3570 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:46.897  3487  3570 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{df2b16a u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5e2cfd2 9132:com.samsung.android.scloud:contentsync/5009}
,05-25 13:49:46.897  9132  9132 I [SC]DetectorReceiver: onReceive [android.net.conn.CONNECTIVITY_CHANGE]
,05-25 13:49:46.897  9132  9132 I [SC]CloudManager: requestInit
,05-25 13:49:46.907  9132  9132 I [SC]Utils: folder : cachecreate fail, try again.
05-25 13:49:46.907  9132  9132 I [SC]Utils: folder : cache create fail.
,05-25 13:49:46.907  9132  9132 I [SC]Utils: folder : thumbnailcreate fail, try again.
05-25 13:49:46.907  9132  9132 I [SC]Utils: folder : thumbnail create fail.
05-25 13:49:46.907  9132  9132 I [SC]Utils: folder : sharecreate fail, try again.
05-25 13:49:46.907  9132  9132 I [SC]Utils: folder : share create fail.
05-25 13:49:46.907  9132  9132 I [SC]Utils: folder : scratchcreate fail, try again.
,05-25 13:49:46.907  9132  9132 I [SC]Utils: folder : scratch create fail.
,05-25 13:49:46.907  9132  9132 I [SC]Utils: folder : eventSynccreate fail, try again.
05-25 13:49:46.907  9132  9132 I [SC]Utils: folder : eventSync create fail.
,05-25 13:49:46.927  8501  8512 I SA      : [SCU] isHaveSA() - false
05-25 13:49:46.927  8501  8512 I SA      : [OCP] Samsung account is not Signed-in
,05-25 13:49:46.927  8501  8512 I SA      : [OCP] Delete DB (TNC data)
,05-25 13:49:46.927  9132  9132 I [SC]CommonUtil: Samsung Account Not Logged in
,05-25 13:49:46.927  3487  3506 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:46.947  3487  3506 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{df2b16a u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{882cab8 9147:com.samsung.android.coreapps/5011}
,05-25 13:49:46.957  3487  3506 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:46.967  3487  3506 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{df2b16a u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{882cab8 9147:com.samsung.android.coreapps/5011}
,05-25 13:49:46.997  3487  4197 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:47.007  3487  4197 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{df2b16a u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{882cab8 9147:com.samsung.android.coreapps/5011}
,05-25 13:49:47.017  3487  4197 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:47.027  3487  4197 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{df2b16a u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{10aea20 4985:com.microsoft.skydrive/u0a130}
,05-25 13:49:47.027  3487  4947 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:47.037  3487  3985 W IntentResolver: resolveIntent failed: found match, but none with CATEGORY_DEFAULT
,05-25 13:49:47.047  3487  4408 D ActivityManager:  getDeferredInfo final delay 300
,05-25 13:49:47.417  3487  3570 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:47.437 10206 10206 E Zygote  : v2
05-25 13:49:47.437 10206 10206 I libpersona: KNOX_SDCARD checking this for 10135
05-25 13:49:47.437 10206 10206 I libpersona: KNOX_SDCARD not a persona
,05-25 13:49:47.437 10206 10206 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-25 13:49:47.437 10206 10206 E Zygote  : accessInfo : 0
,05-25 13:49:47.437 10206 10206 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.photos 
,05-25 13:49:47.447  3487  3570 I ActivityManager: Start proc 10206:com.google.android.apps.photos/u0a135 for broadcast-5 com.google.android.apps.photos/.actionqueue.SystemReceiver
,05-25 13:49:47.447  3487  3857 D NetworkPolicy: isUidForegroundLocked: 10135, mScreenOn: true, uidstate: -1, mProxSensorScreenOff: false
,05-25 13:49:47.447  3487  3858 D WifiP2pService: InactiveState{ what=143375 }
,05-25 13:49:47.447  3487  3858 D WifiP2pService: P2pEnabledState{ what=143375 }
,05-25 13:49:47.457  3487  3869 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,05-25 13:49:47.457  3487  3860 D WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
05-25 13:49:47.457  3487  3860 D WifiStateMachine: VerifyingLinkState enter
,05-25 13:49:47.457  3487  3869 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -19], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -19]
,05-25 13:49:47.457  3949  4154 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-25 13:49:47.467  3487  3869 E ConnectivityService: updateNetworkInfo()
,05-25 13:49:47.467  3487  3487 D WifiNotificationController: SHOW_NOTI_MESSAGE : 9, visible : false, ssid : "NG700", targetSSID : null, netId : -1, titleType : -1
,05-25 13:49:47.467  4163  7403 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=17041883,extra=Bundle[mParcelledData.dataSize=84]
05-25 13:49:47.467  3487  3869 D ConnectivityService: Adding iface wlan0 to network 503
05-25 13:49:47.467  4163  4163 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=17041883, samsung.notification.type=normal, samsung.people.package_name=android}]
05-25 13:49:47.467  4163  4163 I PeopleStripeService: PeopleNotificationReceiver:3
,05-25 13:49:47.467  4163  4163 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
05-25 13:49:47.467  4163  4163 I PeopleDataManager: removeNotification
05-25 13:49:47.467  4163  4163 I NotificationParser: getNotiType:android,null
05-25 13:49:47.467  4163  4163 D PeopleDataManager: removeNotiInfo: id =17041883,packageName=android,isEdgeNotification=false,key=null,removeAll=false
05-25 13:49:47.467  4163  4163 D PeopleDataManager: removeNotiInfo =null
05-25 13:49:47.467  3487  3869 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}, oldLp = null
,05-25 13:49:47.467 10206 10206 D TimaKeyStoreProvider: TimaSignature is unavailable
,05-25 13:49:47.467 10206 10206 D ActivityThread: Added TimaKeyStore provider
,05-25 13:49:47.477  3487  3487 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
,05-25 13:49:47.477  3487  3487 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
05-25 13:49:47.477  3487  3487 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
05-25 13:49:47.477  3487  3487 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
05-25 13:49:47.477  3487  3867 I WifiHs20Service: Message received 5007
05-25 13:49:47.477  3487  3886 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,05-25 13:49:47.477  3487  3886 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}
05-25 13:49:47.477  3487  3886 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}
05-25 13:49:47.477  3487  3886 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}
,05-25 13:49:47.477  3487  3886 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}
,05-25 13:49:47.477  3949  4154 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-25 13:49:47.477  4315  4315 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,05-25 13:49:47.487  3487  3570 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3a7581e u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f5b23c 10063:com.sec.android.diagmonagent/1000}
,05-25 13:49:47.497 10063 10063 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,05-25 13:49:47.497 10063 10063 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
05-25 13:49:47.497 10063 10063 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
,05-25 13:49:47.497 10063 10063 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
05-25 13:49:47.497  3487  3869 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 503
,05-25 13:49:47.497  3487  3869 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,05-25 13:49:47.497  3487  3869 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
,05-25 13:49:47.497  3487  3869 E ConnectivityService: Unexpected mtu value: 0, wlan0
,05-25 13:49:47.507  3487  3869 D ConnectivityService: Setting Dns servers for network 503 to [/192.168.1.1]
,05-25 13:49:47.507  3487  4065 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{df2b16a u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4dd8ff 10206:com.google.android.apps.photos/u0a135}
,05-25 13:49:47.507  3487  3886 I WifiManager: isCaptivePortalException
05-25 13:49:47.507  3487  3857 D NetworkPolicy: isUidForegroundLocked: 10135, mScreenOn: true, uidstate: 11, mProxSensorScreenOff: false
,05-25 13:49:47.517  3487  3505 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3a7581e u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e6f874a 6550:com.enhance.gameservice/u0a111}
,05-25 13:49:47.527  3487  3886 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
,05-25 13:49:47.527 10206 10206 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
05-25 13:49:47.527 10206 10206 D RelationGraph: garbageCollect()
,05-25 13:49:47.527 10206 10206 W ResourcesManager: getTopLevelResources: /system/app/Photos/Photos.apk / 1.0 running in com.google.android.apps.photos rsrc of package com.google.android.apps.photos
,05-25 13:49:47.527  3487  4927 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-25 13:49:47.527 10206 10206 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-25 13:49:47.527  3487  4197 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3a7581e u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6fed98c 9704:com.sec.knox.switcher/1000}
05-25 13:49:47.527  3487  3886 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
05-25 13:49:47.527  3487  3886 D WifiWatchdogStateMachine: 3Captive portal check should be processed whether SNS option is on or off.
05-25 13:49:47.527  3487  3886 D WifiWatchdogStateMachine.CaptivePortalHandler: [checkCaptivePortal] - callbackHandler=Handler (com.android.server.wifi.WifiWatchdogStateMachine$CaptivePortalHandler) {d9ad2df}
05-25 13:49:47.537  3487  3886 I WifiManager: isCaptivePortalException
05-25 13:49:47.537  3487  3869 V NetworkStats: updateIfacesLocked()
05-25 13:49:47.537  3487  3886 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
05-25 13:49:47.537  3487  3869 V NetworkStats: performPollLocked(flags=0x1)
05-25 13:49:47.537  3487  3869 D NtpTrustedTime: currentTimeMillis() cache hit
05-25 13:49:47.537  9704  9704 I usagelog: received in receiver
,05-25 13:49:47.537  9704  9704 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
05-25 13:49:47.537  9704  9704 I KnoxUsageLogPro: premStatus:2
,05-25 13:49:47.537  3487  3869 D NetworkStatsRecorder: entry.iface is null
05-25 13:49:47.537  3487  3869 D NetworkStatsRecorder: entry.iface is null
05-25 13:49:47.537  3487  3869 D NetworkStatsRecorder: entry.iface is null
05-25 13:49:47.537  3487  3869 D NetworkStatsRecorder: entry.iface is null
,05-25 13:49:47.537  3487  3869 V NetworkStats: performPollLocked() took 5ms
05-25 13:49:47.537  3487  3869 D NtpTrustedTime: currentTimeMillis() cache hit
,05-25 13:49:47.557  3487  3886 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
,05-25 13:49:47.557  3487  3869 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-25 13:49:47.557  3487  3869 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -19]
05-25 13:49:47.557  3487  3869 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
05-25 13:49:47.557  3487  3869 D ConnectivityService: Not required to send intent.
05-25 13:49:47.557  3487  3869 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = CONNECTING
,05-25 13:49:47.557  3487  3860 D WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to CONNECTED
,05-25 13:49:47.557  9704  9704 I KnoxUsageLogPro: isEulaShown : false
05-25 13:49:47.557  9704  9704 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
05-25 13:49:47.557 10206 10206 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:49:47.557  3487  3857 D NtpTrustedTime: currentTimeMillis() cache hit
05-25 13:49:47.557  3487  3857 D NtpTrustedTime: currentTimeMillis() cache hit
,05-25 13:49:47.567  3487  3860 D SecContentProvider: insert(), uri = 2
,05-25 13:49:47.567 10206 10206 I InjectionManager: Inside getClassLibPath caller 
,05-25 13:49:47.567  3487  3854 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3a7581e u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7d2491a 10075:com.samsung.android.sm.policy/u0a142}
,05-25 13:49:47.577  3487  3487 D WifiNotificationController: SHOW_NOTI_MESSAGE : 9, visible : false, ssid : "NG700", targetSSID : null, netId : -1, titleType : -1
05-25 13:49:47.577  4163  4173 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=17041883,extra=Bundle[mParcelledData.dataSize=84]
,05-25 13:49:47.577  4163  4163 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=17041883, samsung.notification.type=normal, samsung.people.package_name=android}]
05-25 13:49:47.577  4163  4163 I PeopleStripeService: PeopleNotificationReceiver:3
05-25 13:49:47.577  4163  4163 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
05-25 13:49:47.577  4163  4163 I PeopleDataManager: removeNotification
05-25 13:49:47.577  4163  4163 I NotificationParser: getNotiType:android,null
05-25 13:49:47.577  4163  4163 D PeopleDataManager: removeNotiInfo: id =17041883,packageName=android,isEdgeNotification=false,key=null,removeAll=false
05-25 13:49:47.577  3487  3869 E ConnectivityService: updateNetworkInfo()
05-25 13:49:47.577  3487  3869 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -19]
05-25 13:49:47.577  4163  4163 D PeopleDataManager: removeNotiInfo =null
,05-25 13:49:47.577  3487  3869 D NtpTrustedTime: currentTimeMillis() cache hit
,05-25 13:49:47.577  3487  3869 V NetworkStats: updateIfacesLocked()
05-25 13:49:47.577  3487  3869 V NetworkStats: performPollLocked(flags=0x1)
,05-25 13:49:47.577 10206 10206 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm64
,05-25 13:49:47.577  3487  3869 D NetworkStatsRecorder: entry.iface is null
,05-25 13:49:47.577  3487  3869 D NetworkStatsRecorder: entry.iface is null
05-25 13:49:47.577  3487  3869 D NetworkStatsRecorder: entry.iface is null
05-25 13:49:47.577  3487  3869 D NtpTrustedTime: currentTimeMillis() cache hit
05-25 13:49:47.577  3487  3869 D NetworkStatsRecorder: entry.iface is null
05-25 13:49:47.577  3487  3869 V NetworkStats: performPollLocked() took 4ms
,05-25 13:49:47.587  3487  3869 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,05-25 13:49:47.587  3487  3869 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -19]
,05-25 13:49:47.587  3487  3857 D NtpTrustedTime: currentTimeMillis() cache hit
05-25 13:49:47.587  3487  3869 D ConnectivityService: scheduleUnvalidatedPrompt 503
05-25 13:49:47.587  3487  3857 D NtpTrustedTime: currentTimeMillis() cache hit
05-25 13:49:47.587  3487  3869 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 503]
05-25 13:49:47.587  3487 10174 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
,05-25 13:49:47.587  3487  3869 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
05-25 13:49:47.587  3487 10174 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: Connected
05-25 13:49:47.587  3487 10174 D NetworkMonitor: registerReceiver Captive portal receiver
,05-25 13:49:47.587  3487  3487 I WifiTrafficPoller: evaluateTrafficStatsPolling
,05-25 13:49:47.587  3487  3869 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -19]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
05-25 13:49:47.587  3487  3860 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
05-25 13:49:47.587  3487  3860 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
05-25 13:49:47.587  3487  3860 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,05-25 13:49:47.587  3487  3487 D WifiNative-wlan0: callSECApiVoid - ID [212]
05-25 13:49:47.587 10112 10112 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
05-25 13:49:47.587 10112 10112 I wpa_supplicant: P2P: Current p2p state = IDLE
05-25 13:49:47.587  3487  3860 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
05-25 13:49:47.587 10112 10112 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
05-25 13:49:47.597  3487  3487 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
05-25 13:49:47.597  3487  3487 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
05-25 13:49:47.597  3487  3487 D HS20StateMachine: SSID : "NG700"
05-25 13:49:47.597  3487  3487 D HS20StateMachine: NetId : 0
05-25 13:49:47.597  3487  3487 D HS20StateMachine: checkifOSUAP  null
,05-25 13:49:47.597  3487  3487 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
05-25 13:49:47.597  3487  3867 I WifiHs20Service: Message received 5007
05-25 13:49:47.597  3487  3487 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
,05-25 13:49:47.597  3487  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: true
,05-25 13:49:47.597  3487  3869 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,05-25 13:49:47.597  3949  4154 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
05-25 13:49:47.597  4315  4599 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
05-25 13:49:47.597  4315  4599 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,05-25 13:49:47.597  3487  3869 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,05-25 13:49:47.597  3487  3869 D ConnectivityService: currentScore = 0, newScore = 20
05-25 13:49:47.597  3487  3860 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:47.597  3487  3869 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 503]
05-25 13:49:47.597  3487  3895 D Ethernet: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:47.597  3487  3869 D ConnectivityService:    accepting network in place of null
05-25 13:49:47.597  3487  3869 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:47.607  3487  3860 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-25 13:49:47.607  3487  3895 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
05-25 13:49:47.607  3487  3895 D Ethernet: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
05-25 13:49:47.607  3487  3860 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,05-25 13:49:47.607  3487  3895 D Ethernet: evalRequest
05-25 13:49:47.607  3487  3860 D WIFI    : evalRequest
05-25 13:49:47.607  3487  3895 D Ethernet:   done
05-25 13:49:47.607  3487  3860 D WIFI    :   done
05-25 13:49:47.607  3487  3860 D WIFI_UT : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:47.607  3487  3860 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-25 13:49:47.607  3487  3860 D WIFI_UT : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
05-25 13:49:47.607  3487  3860 D WIFI_UT : evalRequest
05-25 13:49:47.607  3487  3860 D WIFI_UT :   done
05-25 13:49:47.607  3487  3860 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:47.607  3487  3860 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-25 13:49:47.607  3487  3860 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
05-25 13:49:47.607  3487  3860 D WIFI    : evalRequest
,05-25 13:49:47.607  3487  3860 D WIFI    :   done
05-25 13:49:47.607  3487  3858 D WIFI_P2P: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:47.607  3487  3858 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-25 13:49:47.607  3487  3858 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
05-25 13:49:47.607  3487  3858 D WIFI_P2P: evalRequest
05-25 13:49:47.607  3487  3858 D WIFI_P2P:   done
,05-25 13:49:47.607  4315  4315 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,05-25 13:49:47.607  3487  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-25 13:49:47.617  3487  3570 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{decd82a u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f5b23c 10063:com.sec.android.diagmonagent/1000}
,05-25 13:49:47.617  3487 10174 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
05-25 13:49:47.617 10063 10063 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
05-25 13:49:47.617  3487 10174 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: Validated
05-25 13:49:47.617  3487  4920 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
05-25 13:49:47.617 10063 10063 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
05-25 13:49:47.617 10063 10063 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
,05-25 13:49:47.617  3487  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,05-25 13:49:47.617 10063 10063 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 android.content.ContextWrapper.sendBroadcast:410 android.content.ContextWrapper.sendBroadcast:410 com.sec.android.diagmonagent.DiagMonConnectivityChangeReciever.onReceive:19 android.app.ActivityThread.handleReceiver:3635 
,05-25 13:49:47.617  3487  3505 D SecContentProvider2: query(), uri = 15 selection = getToastGravityEnabledState
05-25 13:49:47.627  3487  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-25 13:49:47.627  3487  4927 D SecContentProvider2: query(), uri = 15 selection = getToastEnabledState
05-25 13:49:47.627  3487  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
05-25 13:49:47.627  3487  4196 D SecContentProvider2: query(), uri = 15 selection = getToastShowPackageNameState
,05-25 13:49:47.627  3487  4670 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{decd82a u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e6f874a 6550:com.enhance.gameservice/u0a111}
,05-25 13:49:47.637  3487  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-25 13:49:47.637  3487  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,05-25 13:49:47.637  3487  3869 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -19]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,05-25 13:49:47.657  3949  4154 D ViewRootImpl: #1 mView = android.widget.LinearLayout{82ebb50 V.E...... ......I. 0,0-0,0 #102039c android:id/toast_layout_root}
,05-25 13:49:47.657  3487  4197 D ISSUE_DEBUG: InputChannelName : d0ba364 Toast
,05-25 13:49:47.657  3487  4197 V MARsPolicyManager: handelAlertToastWindowStarted pkgName = com.android.systemui
05-25 13:49:47.657  3487  3985 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{decd82a u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6fed98c 9704:com.sec.knox.switcher/1000}
,05-25 13:49:47.657  9704  9704 I usagelog: received in receiver
05-25 13:49:47.667  9704  9704 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
05-25 13:49:47.667  9704  9704 I KnoxUsageLogPro: premStatus:2
,05-25 13:49:47.667  3157  3638 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,05-25 13:49:47.667  9704  9704 I KnoxUsageLogPro: isEulaShown : false
05-25 13:49:47.667  9704  9704 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,05-25 13:49:47.667  3949  3949 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 272
,05-25 13:49:47.677  3011  3011 I SurfaceFlinger: id=22 createSurf (1x1),1 flag=4, Uoast
05-25 13:49:47.677  3487  4670 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{decd82a u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7d2491a 10075:com.samsung.android.sm.policy/u0a142}
,05-25 13:49:47.687  3157  3638 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,05-25 13:49:47.687  3487  3869 D ConnectivityService: 503 network ip type : v4
,05-25 13:49:47.687  3487  3869 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:49:47.697  3487  3869 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:49:47.697  3487  3869 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:49:47.697  3487  3869 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:49:47.697  3487  3869 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=5, legacyType=-1, [] ]
,05-25 13:49:47.707  3487  3869 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -19]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} } for legacy network type 1
05-25 13:49:47.707  3487  3869 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
05-25 13:49:47.707  3487  3869 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,05-25 13:49:47.707  3487  3599 D EntConnectivity: Not allowed due to - mEnabled false
,05-25 13:49:47.717  3487  4197 D ConnectivityService: getVpnConfig > userId : 0
05-25 13:49:47.717  3487  4407 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3487
05-25 13:49:47.717  3487  3905 D lights  : lcd : 40 +
05-25 13:49:47.717  3487  4407 D PowerManagerService: mDisplayReady: false
05-25 13:49:47.717  3487  3604 D DisplayPowerController: animateScreenStateChange[0]: target=2
05-25 13:49:47.717  3487  3604 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
05-25 13:49:47.717  3487  3604 D DisplayPowerController: getFinalBrightness : Summary is 40 -> 40
05-25 13:49:47.717  3487  3604 D SettingsProvider: isChangeAllowed() : name = brightness_pms_marker_screen
05-25 13:49:47.717  3487  3604 D DisplayPowerController: Tracking Direct to etc : 40
05-25 13:49:47.717  3487  3604 D DisplayPowerController: Animating brightness: target=40, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
05-25 13:49:47.717  3487  3604 D DisplayPowerController: animateScreenStateChange[0]: target=2
05-25 13:49:47.717  3487  3604 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
05-25 13:49:47.717  3487  3604 D DisplayPowerController: getFinalBrightness : Summary is 40 -> 40
05-25 13:49:47.717  3487  3604 D DisplayPowerController: Animating brightness: target=40, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
05-25 13:49:47.717  3487  3604 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
05-25 13:49:47.717  3487  3604 D PowerManagerService: mDisplayReady: true
,05-25 13:49:47.727  3487  3599 D EntConnectivity: Not allowed due to - mEnabled false
,05-25 13:49:47.727  3487  3905 D lights  : lcd : 40 -
,05-25 13:49:47.727  3487  3506 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b344282 u0 com.sec.android.diagmonagent.intent.NETWORK_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f5b23c 10063:com.sec.android.diagmonagent/1000}
05-25 13:49:47.727 10063 10063 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: com.sec.android.diagmonagent.intent.NETWORK_CHANGED
05-25 13:49:47.727  3487  3905 D DisplayPowerState: Tracking!!: 40
05-25 13:49:47.727 10063 10063 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
,05-25 13:49:47.727  3487  3905 D SettingsProvider: isChangeAllowed() : name = brightness_pms_marker_screen
05-25 13:49:47.727 10063 10063 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(67/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
05-25 13:49:47.727  3487  3604 D DisplayPowerController: animateScreenStateChange[0]: target=2
,05-25 13:49:47.727  3487  3604 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
05-25 13:49:47.727  3487  3604 D DisplayPowerController: getFinalBrightness : Summary is 40 -> 40
05-25 13:49:47.727  3487  3604 D DisplayPowerController: Animating brightness: target=40, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,05-25 13:49:47.737  3949  4140 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1033x201]-format:1
,05-25 13:49:47.737  3487  3869 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -19]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
05-25 13:49:47.737  3487  3869 D ConnectivityService: unneeded: NetworkRequestInfo for = Request from uid/pid:1000/3487 for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:49:47.737  3487  3869 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
05-25 13:49:47.737  3487  3869 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
05-25 13:49:47.737  3487  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:47.737  3487  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:49:47.737  3487  3869 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:47.737  3487  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
,05-25 13:49:47.737  3487  3869 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=5, legacyType=-1, [] ]
,05-25 13:49:47.737  3949  4154 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,05-25 13:49:47.737  3487  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:47.737  3487  3869 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:47.747  3949  4154 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
05-25 13:49:47.737  3487  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:47.747  4163  7403 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=503,extra=Bundle[mParcelledData.dataSize=84]
05-25 13:49:47.737  3487  3869 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:47.747  4163  4163 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=503, samsung.notification.type=normal, samsung.people.package_name=android}]
05-25 13:49:47.737  3487  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:49:47.747  4163  4163 I PeopleStripeService: PeopleNotificationReceiver:3
05-25 13:49:47.747  4163  4163 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
05-25 13:49:47.747  3487  3869 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:47.747  4163  4163 I PeopleDataManager: removeNotification
05-25 13:49:47.747  3487  3869 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
05-25 13:49:47.747  4163  4163 I NotificationParser: getNotiType:android,null
05-25 13:49:47.747  3487  3869 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] validation  passed
05-25 13:49:47.747  4163  4163 D PeopleDataManager: removeNotiInfo: id =503,packageName=android,isEdgeNotification=false,key=null,removeAll=false
05-25 13:49:47.747  3487  3869 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -19], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -19]
05-25 13:49:47.747  4163  4163 D PeopleDataManager: removeNotiInfo =null
05-25 13:49:47.747  3487  3869 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
,05-25 13:49:47.747  3487  3869 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -19]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,05-25 13:49:47.757  3487  3487 D Tethering: Tethering got CONNECTIVITY_ACTION
,05-25 13:49:47.757  3487  3487 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,05-25 13:49:47.757  3487  3599 D Tethering: MasterInitialState.processMessage what=3
05-25 13:49:47.757  3011  3011 D libEGL  : eglInitialize EGLDisplay = 0x7fd4d61338
,05-25 13:49:47.757  3487  3487 I CLocInfoService: ['16.5] External Intent Received android.net.conn.CONNECTIVITY_CHANGE
05-25 13:49:47.757  3487  3487 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
05-25 13:49:47.757  3487  3854 V WindowStateAnimator: Finishing drawing window Window{d0ba364 u0 d0 Toast}: mDrawState=DRAW_PENDING
05-25 13:49:47.757  3487  3487 I CLocInfoService: CLocinfo wifi true 
,05-25 13:49:47.767  3487  3869 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
,05-25 13:49:47.767  3487  3871 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,05-25 13:49:47.767  4315  4635 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,05-25 13:49:47.767  4315  4635 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,05-25 13:49:47.767  3487  3871 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,05-25 13:49:47.777  3487  3565 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,05-25 13:49:47.777  3487  3565 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,05-25 13:49:47.777  3487  3565 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,05-25 13:49:47.777  3487  4245 V AlarmManager:  remove PendingIntent] PendingIntent{8da47d6: PendingIntentRecord{c57fa57 android broadcastIntent}}
,05-25 13:49:47.787  3949  4154 D NetworkController: onReceive: intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-25 13:49:47.797  3487  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-25 13:49:47.807 10206 10206 W ResourcesManager: getTopLevelResources: /system/app/Photos/Photos.apk / 1.0 running in com.google.android.apps.photos rsrc of package com.google.android.apps.photos
,05-25 13:49:47.817  3487  3487 V MARsPolicyManager: DataConnection: true
,05-25 13:49:47.827  4862  4862 D SamsungIME: EngineType = SWIFTKEY
,05-25 13:49:47.827  3487  3857 D NtpTrustedTime: currentTimeMillis() cache hit
05-25 13:49:47.827  3487  3857 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-25 13:49:47.827  3487  3857 D NtpTrustedTime: currentTimeMillis() cache hit
05-25 13:49:47.827  3487  3857 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -19]
05-25 13:49:47.827  3487  3857 D NtpTrustedTime: currentTimeMillis() cache hit
05-25 13:49:47.827  3487  3857 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
05-25 13:49:47.827  3487  3857 D NtpTrustedTime: currentTimeMillis() cache hit
05-25 13:49:47.827  3487  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
05-25 13:49:47.827  4862  4862 D SamsungIME: mNetworkChangeReceiver isWLANConnected : true
05-25 13:49:47.827  4952  5065 D CellLocationSupport: onReceive ACTION = android.net.conn.CONNECTIVITY_CHANGE
05-25 13:49:47.827  4952  5065 I CellLocationSupport: onCellLocationChanged
,05-25 13:49:47.837  4315  4325 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
05-25 13:49:47.837  4315  4325 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
05-25 13:49:47.837  4952  4952 D PdnController: CONNECTIVITY_ACTION: networkType 1 isConnected true
05-25 13:49:47.837  4952  4952 D PdnController: isSuspended [false] networktype [1]
05-25 13:49:47.837  4952  4952 D PdnController: Updated Interface [wlan0] For Network [1]
05-25 13:49:47.837  3487  3565 D TelephonyManager: getDataEnabled: retVal=true
,05-25 13:49:47.837  3487  3854 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,05-25 13:49:47.837  4952  4952 D PdnController: isPdnUp  [true] networktype [1]
05-25 13:49:47.837  4952  4952 D PdnController: Notify Result to LocalIP Registrants! : networkType [1] isConnected [true] 
,05-25 13:49:47.837  5461  5461 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@a4cef50 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-25 13:49:47.847  5461  5461 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,05-25 13:49:47.847  3487  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-25 13:49:47.847  3487  4417 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,05-25 13:49:47.857  6969  6969 I FOTA_AGENT: [lIlIIlIlIlIllllllIII(91/llllIIIllIlIIIIllllI)] WiFi Network is connected
,05-25 13:49:47.857  4952  5065 I CellLocationSupport: Block to update PANI information in non VoWIFI
05-25 13:49:47.857  4952  5065 D SlickSSConfigHandler: EVENT_LOCAL_IP_CHANGED
,05-25 13:49:47.857  3487  4670 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:47.857  4952  5065 D PdnController: isIfaceDisconnected result [true] networkType [0] interfaceName [null] 
05-25 13:49:47.857  4952  5065 D PdnController: isPdnUp  [false] networktype [0]
05-25 13:49:47.857  4952  5065 D SlickSSConfigHandler: handleNetworkStateChange: check isDefaultPDNConnected[false], mReadyForDocFetch[false
,05-25 13:49:47.857  3487  3890 D WifiWatchdogStateMachine.CaptivePortalHandler: start check captive portal 
,05-25 13:49:47.867  4952  5065 D RegistrationManager: handleMessage(): 5
,05-25 13:49:47.867  3487  4920 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:47.877  4952  5065 D PdnController: isIfaceDisconnected result [true] networkType [11] interfaceName [null] 
05-25 13:49:47.877  4952  5065 D PdnController: isPdnUp  [false] networktype [11]
05-25 13:49:47.877  4952  5065 D RegistrationManager: setEPDGIPSecConnected [false]
05-25 13:49:47.877  4952  5065 D RegistrationManager: notifyNetworkState : NetworkType [1] IsConnected [true] IPAddresses [[/192.168.1.107]] DNSAddresses [[/192.168.1.1]] 
05-25 13:49:47.877  4952  5065 D RegistrationManager: isEPDGAvailable [false]
05-25 13:49:47.877  4952  5065 D RegistrationManager: setWifiPreparedOnAPM [true]
,05-25 13:49:47.887  3487  4196 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,05-25 13:49:47.887  9357  9357 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 com.samsung.SMT.SamsungTTSService.g:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.c.onReceive:-1 
,05-25 13:49:47.887  4229  4229 D FusedRequestManager: manageLocationRequest, new passive request from com.samsung.voiceserviceplatform with 61dccbe , interval = 1800000 through LocationManagerService
,05-25 13:49:47.887  3487  4244 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:47.897  3487  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-25 13:49:47.897  3157  3634 D EnterpriseController: netId is 0
05-25 13:49:47.897  3157  3634 D Netd    : getNetworkForDns: using netid 503 for uid 10002
,05-25 13:49:47.907  4952  5065 D TranslatorCollection: translateToNwkSvcType: networkType XAN_NWK_TYPE_WLAN
05-25 13:49:47.907  4952  5065 D RegistrationManager: getNetworkType [0]
05-25 13:49:47.907  4952  5065 D CoreStackAdaptor2: notifyNetworkState() [1] isConnected [true] nwkSvcType  [XAN_NWK_TYPE_WLAN] nwkInfoType [XAN_SVC_NETWORK_SVCTYPE_WIFI] dedicated   [NONE] 
05-25 13:49:47.907  4952  5065 D CellLocationSupport: Siso Stack not called RegisterAN yet on XAN_NWK_TYPE_WLAN
05-25 13:49:47.907  4952  5065 D TranslatorCollection: translateToNwkSvcType: networkType XAN_NWK_TYPE_WLAN
,05-25 13:49:47.907  4952  5065 D CoreStackAdaptor2: ipList Not Null[/192.168.1.107]
05-25 13:49:47.907  4952  5065 D RegistrationManager: tryRegister(CONNECTIVITY_STATUS_CHANGE)
05-25 13:49:47.907  4952  5065 D RegistrationManager: isPreconditionProperToGoOn
05-25 13:49:47.907  4952  5065 D RegistrationManager: isDeviceShutdown [false]
05-25 13:49:47.907  4952  5065 D RegistrationManager: isStackShuttingDownForAllPDNs [false]
05-25 13:49:47.907  4952  5065 D RegistrationManager: isDmVoLTEUpdated [false]
05-25 13:49:47.907  4952  5065 D RegistrationManager: tryRegister : Abort Reason [IMS feature disabled]
05-25 13:49:47.907  4952  5065 D RegistrationManager: tryRegister : Not all preconditions are met!
,05-25 13:49:47.917  3487  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-25 13:49:47.917  9844  9844 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,05-25 13:49:47.927  4438  4438 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,05-25 13:49:47.967  9658  9669 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(86/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
,05-25 13:49:47.967  9658  9669 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(86/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
,05-25 13:49:47.967  9658  9669 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(43/llIIIIlllllIIllIIllI)] already Eula Agree
,05-25 13:49:47.967  9844  9844 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,05-25 13:49:47.977  4912  4912 E audit   : type=1400 msg=audit(1495712987.977:278): avc:  denied  { ioctl } for  pid=7256 comm="ChromiumNet" path="socket:[44119]" dev="sockfs" ino=44119 ioctlcmd=8b1b scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=udp_socket permissive=0
05-25 13:49:47.977  4912  4912 E audit   :  SEPF_SECMOBILE_6.0.1_0031
05-25 13:49:47.977  4912  4912 E audit   : type=1300 msg=audit(1495712987.977:278): arch=c00000b7 syscall=29 success=no exit=-13 a0=18 a1=8b1b a2=7f682fecc8 a3=7f682fec90 items=0 ppid=3181 pid=7256 auid=4294967295 uid=10072 gid=10072 euid=10072 suid=10072 fsuid=10072 egid=10072 sgid=10072 fsgid=10072 tty=(none) ses=4294967295 comm="ChromiumNet" exe="/system/bin/app_process64" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
05-25 13:49:47.977  4912  4912 E audit   : type=1327 msg=audit(1495712987.977:278): proctitle="com.google.android.googlequicksearchbox:search"
05-25 13:49:47.977  4912  4912 E audit   : type=1320 msg=audit(1495712987.977:278): 
05-25 13:49:47.977  3487  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
05-25 13:49:47.977  4912  4912 E audit   : type=1400 msg=audit(1495712987.977:279): avc:  denied  { ioctl } for  pid=7256 comm="ChromiumNet" path="socket:[44120]" dev="sockfs" ino=44120 ioctlcmd=8b1b scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=udp_socket permissive=0
05-25 13:49:47.977  4912  4912 E audit   :  SEPF_SECMOBILE_6.0.1_0031
05-25 13:49:47.977  4912  4912 E audit   : type=1300 msg=audit(1495712987.977:279): arch=c00000b7 syscall=29 success=no exit=-13 a0=18 a1=8b1b a2=7f682fecc8 a3=7f682fec90 items=0 ppid=3181 pid=7256 auid=4294967295 uid=10072 gid=10072 euid=10072 suid=10072 fsuid=10072 egid=10072 sgid=10072 fsgid=10072 tty=(none) ses=4294967295 comm="ChromiumNet" exe="/system/bin/app_process64" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
05-25 13:49:47.977  4912  4912 E audit   : type=1327 msg=audit(1495712987.977:279): proctitle="com.google.android.googlequicksearchbox:search"
05-25 13:49:47.977  4912  4912 E audit   : type=1320 msg=audit(1495712987.977:279): 
,05-25 13:49:47.977  3487  3869 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -19]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
05-25 13:49:47.977  3487  3869 D ConnectivityService: unneeded: NetworkRequestInfo for = Request from uid/pid:1000/3487 for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:47.977  3487  3869 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
05-25 13:49:47.977  3487  3869 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 503]
05-25 13:49:47.977  3487  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:47.977  3487  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:49:47.977  3487  3869 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:47.977  3487  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
05-25 13:49:47.977  3487  3869 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=5, legacyType=-1, [] ]
,05-25 13:49:47.977  3487  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:47.977  3487  3869 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:49:47.977  3487  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:47.987  3487  3869 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:49:47.987  9658  9668 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(86/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
05-25 13:49:47.987  3487  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:47.987  3487  3869 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:49:47.987  9658  9668 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(86/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
,05-25 13:49:47.987  9658  9668 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(43/llIIIIlllllIIllIIllI)] already Eula Agree
,05-25 13:49:47.987  3487  3869 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:49:47.987  3487  3858 D WIFI_P2P: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:47.987  3487  3858 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-25 13:49:47.987  3487  3860 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:47.987  3487  3860 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-25 13:49:47.987  3487  3858 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
05-25 13:49:47.987  3487  3858 D WIFI_P2P: evalRequest
05-25 13:49:47.987  3487  3858 D WIFI_P2P:   done
05-25 13:49:47.987  3487  3860 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
05-25 13:49:47.987  3487  3860 D WIFI    : evalRequest
05-25 13:49:47.987  3487  3860 D WIFI    :   done
05-25 13:49:47.987  3487  3860 D WIFI_UT : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:47.987  3487  3860 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-25 13:49:47.987  3487  3860 D WIFI_UT : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
05-25 13:49:47.987  3487  3860 D WIFI_UT : evalRequest
05-25 13:49:47.987  3487  3860 D WIFI_UT :   done
05-25 13:49:47.987  3487  3860 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:47.987  3487  3860 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-25 13:49:47.987  3487  3860 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
05-25 13:49:47.987  3487  3860 D WIFI    : evalRequest
05-25 13:49:47.987  3487  3860 D WIFI    :   done
05-25 13:49:47.987  3487  3895 D Ethernet: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:47.987  3487  3895 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
05-25 13:49:47.987  3487  3895 D Ethernet: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
05-25 13:49:47.987  3487  3895 D Ethernet: evalRequest
05-25 13:49:47.987  3487  3895 D Ethernet:   done
,05-25 13:49:47.997  3487  3869 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,05-25 13:49:47.997  3487  3860 D WifiNetworkAgent: NetworkAgent: CMD_REPORT_NETWORK_STATUS(VALID)
05-25 13:49:47.997  3487  3860 D WifiNetworkAgent: NetworkAgent: CMD_REPORT_NETWORK_STATUS(1)
,05-25 13:49:48.007  3487  3889 D WifiWatchdogStateMachine: response code : 204
05-25 13:49:48.007  4315  5521 D TelephonyProvider: query: url=content://telephony/carriers/preferapn, projectionIn=[Ljava.lang.String;@d76f8d3, selection=nullselectionArgs=null, sort=name ASC
,05-25 13:49:48.017  4315  5521 D TelephonyProvider: query: match = 5
05-25 13:49:48.017 10239 10239 I libpersona: KNOX_SDCARD checking this for 1000
05-25 13:49:48.017 10239 10239 E Zygote  : v2
05-25 13:49:48.017 10239 10239 I libpersona: KNOX_SDCARD not a persona
05-25 13:49:48.017  4315  5521 D TelephonyProvider: getPreferredApnId(subId = 2147483643),return -1
05-25 13:49:48.017  4315  5521 D TelephonyProvider: query: selection modified to edited!=2 and edited!=3 and edited!=5 and edited!=6
,05-25 13:49:48.017 10239 10239 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-25 13:49:48.027 10239 10239 E Zygote  : accessInfo : 0
,05-25 13:49:48.027  9844  9844 D BluetoothAdapter: STATE_ON
05-25 13:49:48.027  3487  4947 I ActivityManager: Start proc 10239:com.sec.android.soagent/1000 for content provider com.sec.android.soagent/.log.MasterLogProvider
,05-25 13:49:48.027  3487  3860 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
05-25 13:49:48.027  3487  3890 D WifiWatchdogStateMachine.CaptivePortalHandler: result = 0, mCaptivePortalCheckMode = 11, mCouldNotIdentifyCaptivePortalState = true
05-25 13:49:48.027  3487  3860 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
05-25 13:49:48.027  3487  3860 D WifiStateMachine: sendBroadcastForCaptivePortalNotLoginIcon : false
05-25 13:49:48.027  3487  3860 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
05-25 13:49:48.027  9844  9844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-25 13:49:48.027  9844  9844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-25 13:49:48.027  9844  9844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-25 13:49:48.027  9844  9844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-25 13:49:48.027  9844  9844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-25 13:49:48.027  9844  9844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-25 13:49:48.027  9844  9844 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-25 13:49:48.027  9844  9844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-25 13:49:48.027  9844  9844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,05-25 13:49:48.037  3949  4154 D NetworkController: onReceive: intent=Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-25 13:49:48.037  3487  3860 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
,05-25 13:49:48.037  9844  9844 D BluetoothAdapter: STATE_ON
,05-25 13:49:48.047  9844  9844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,05-25 13:49:48.057  3949  4154 D NetworkController: onReceive: intent=Intent { act=com.samsung.intent.action.WIFI_CAPTIVE_NOT_LOGIN flg=0x10 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
05-25 13:49:48.057  3949  4154 D NetworkController.WifiSignalController: updateWifiState : mCurrentState.wifiCaptiveNotLogin = false
,05-25 13:49:48.057 10239 10239 D TimaKeyStoreProvider: TimaSignature is unavailable
05-25 13:49:48.057 10239 10239 D ActivityThread: Added TimaKeyStore provider
,05-25 13:49:48.077  3487  3565 E GpsLocationProvider: No APN found to select.
,05-25 13:49:48.087 10239 10239 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,05-25 13:49:48.087 10239 10239 D RelationGraph: garbageCollect()
,05-25 13:49:48.097 10239 10239 W ResourcesManager: getTopLevelResources: /system/priv-app/SOAgent/SOAgent.apk / 1.0 running in com.sec.android.soagent rsrc of package com.sec.android.soagent
,05-25 13:49:48.097  3487  3565 D libgps  : agps_ril_update_network_state: Waiting for IPC connection...
,05-25 13:49:48.097  3487  3854 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-25 13:49:48.107 10239 10239 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
05-25 13:49:48.107 10239 10239 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:49:48.117 10239 10239 I InjectionManager: Inside getClassLibPath caller 
,05-25 13:49:48.127 10239 10239 W System  : ClassLoader referenced unknown path: /system/priv-app/SOAgent/lib/arm64
,05-25 13:49:48.137 10206 10206 D InjectionManager: InjectionManager
05-25 13:49:48.137 10206 10206 D InjectionManager: fillFeatureStoreMap com.google.android.apps.photos
,05-25 13:49:48.147 10206 10206 I InjectionManager: Constructor com.google.android.apps.photos, Feature store :{}
05-25 13:49:48.147 10206 10206 I InjectionManager: featureStore :{}
,05-25 13:49:48.147  3487  3506 D ActivityManager:  getDeferredInfo final delay 300
,05-25 13:49:48.167 10239 10239 D InjectionManager: InjectionManager
05-25 13:49:48.167 10239 10239 D InjectionManager: fillFeatureStoreMap com.sec.android.soagent
,05-25 13:49:48.167 10239 10239 I InjectionManager: Constructor com.sec.android.soagent, Feature store :{}
05-25 13:49:48.167 10239 10239 I InjectionManager: featureStore :{}
,05-25 13:49:48.197  3487  4417 I ActivityManager: Killing 9555:com.facebook.appmanager/u0a103 (adj 15): DHA:empty #33
,05-25 13:49:48.207  3487  4417 I ActivityManager: Killing 8598:com.google.android.talk:matchstick/u0a117 (adj 15): DHA:empty #33
,05-25 13:49:48.217  3487  4417 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8065032 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{460065b 9844:com.thaliproject.thalitest/u0a78}
,05-25 13:49:48.217  3487  3980 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:48.217  3487  3980 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
05-25 13:49:48.217  3487  3980 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:48.217  3487  3980 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:48.217  3487  3980 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:48.217  3487  3980 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:48.217  3487  3980 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:48.217  3487  3980 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:48.217  3487  3980 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:48.217  3487  3980 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:48.217  3487  3980 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:48.217  3487  3980 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:48.217  3487  3980 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:48.217  3487  3980 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:48.217  3487  3980 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:48.237  3487  4417 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8065032 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ea1539a 3487:system/1000}
,05-25 13:49:48.247  3487  4920 D ActivityManager: cleanUpApplicationRecord -- 8598
,05-25 13:49:48.247  3487  4920 D ActivityManager: isAutoRunBlockedApp:: com.google.android.talk, Auto Run ON
,05-25 13:49:48.267  3487  3985 D ActivityManager: cleanUpApplicationRecord -- 9555
,05-25 13:49:48.267  3487  3985 D ActivityManager: isAutoRunBlockedApp:: com.facebook.appmanager, Auto Run ON
,05-25 13:49:48.277  3487  3487 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8065032 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{20981f8 4585:com.google.android.gms/u0a21}
,05-25 13:49:48.277  4585  4585 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,05-25 13:49:48.287  4585  5665 I iu.UploadsManager: num queued entries: 0
,05-25 13:49:48.287  4585  5665 I iu.UploadsManager: num updated entries: 0
,05-25 13:49:48.287  4585  5665 I iu.SyncManager: NEXT; no task
,05-25 13:49:48.297  3487  4671 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8065032 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{20981f8 4585:com.google.android.gms/u0a21}
,05-25 13:49:48.307  4163  4177 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg com.google.android.apps.photos,id=10436,extra=Bundle[mParcelledData.dataSize=84]
,05-25 13:49:48.307  4163  4163 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=10436, samsung.notification.type=normal, samsung.people.package_name=com.google.android.apps.photos}]
05-25 13:49:48.307  4163  4163 I PeopleStripeService: PeopleNotificationReceiver:3
05-25 13:49:48.307  4163  4163 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
05-25 13:49:48.307  4163  4163 I PeopleDataManager: removeNotification
05-25 13:49:48.307  4163  4163 I NotificationParser: getNotiType:com.google.android.apps.photos,null
05-25 13:49:48.307  4163  4163 D PeopleDataManager: removeNotiInfo: id =10436,packageName=com.google.android.apps.photos,isEdgeNotification=false,key=null,removeAll=false
05-25 13:49:48.307  4163  4163 D PeopleDataManager: removeNotiInfo =null
,05-25 13:49:48.327  3487  4920 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8065032 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a95ad21 4274:com.google.android.gms.persistent/u0a21}
,05-25 13:49:48.337  3487  3854 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8065032 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7461dc7 9658:com.policydm/1000}
,05-25 13:49:48.337  3157  3634 D EnterpriseController: netId is 0
,05-25 13:49:48.337  3157  3634 D Netd    : getNetworkForDns: using netid 503 for uid 10021
,05-25 13:49:48.357  9658  9658 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(574/IlIIIllllIIlIIIIIlII)] Initiated Type: 0
,05-25 13:49:48.367  9658  9658 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,05-25 13:49:48.367  9658  9658 I DBG_POLICYDM: [com.policydm.XDMService(585/llIlIllllllllllllllI)] get NotibarState : 0
,05-25 13:49:48.387  3487  3570 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{dc53d7e u0 com.google.android.apps.photos.actionqueue.INTERNAL_ACTION qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4dd8ff 10206:com.google.android.apps.photos/u0a135}
,05-25 13:49:48.507  3487  3570 D ActivityManager:  getDeferredInfo final delay 1020
,05-25 13:49:48.517 10026 10026 D Babel   : RefCountedService(com.google.android.apps.hangouts.requestwriter.RequestWriter) onDestroy (count=0, startId=1 stopped=true)
,05-25 13:49:48.517  3487  4408 I ActivityManager: Killing 8911:com.android.vending/u0a35 (adj 15): DHA:empty #33
,05-25 13:49:48.557  3487  4920 D ActivityManager: cleanUpApplicationRecord -- 8911
05-25 13:49:48.557  3487  4920 D ActivityManager: isAutoRunBlockedApp:: com.android.vending, Auto Run ON
,05-25 13:49:48.697  3487  3869 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,05-25 13:49:49.107  3487  3565 D libgps  : agps_ril_update_network_state: Waiting for IPC connection - timeout
05-25 13:49:49.107  3487  3565 E libgps  : LIBGPS: Cannot communicate (write) with a GPSD
05-25 13:49:49.107  3487  3565 E libgps  : IPC Communication Error, ../../../../tmp/14982990_270314/allPartners/os/android/gps_interface/gpsi_client/GpsiClient.cpp:1710 agps_ril_update_network_state
05-25 13:49:49.107  3487  3565 D libgps  : agps_ril_update_network_availability: Waiting for IPC connection...
,05-25 13:49:49.487  3487  3869 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -19], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -27]
05-25 13:49:49.487  3487  3869 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
,05-25 13:49:49.487  3487  3869 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -27]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,05-25 13:49:49.497  3949  4154 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-25 13:49:49.517  3487  3869 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
,05-25 13:49:49.527  3487  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-25 13:49:49.537  3487  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,05-25 13:49:49.537  3487  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-25 13:49:49.547  3487  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-25 13:49:49.557  3487  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-25 13:49:49.567  3487  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
05-25 13:49:49.567  3487  3869 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 503]
05-25 13:49:49.567  3487  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:49.567  3487  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:49.567  3487  3869 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:49.567  3487  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
,05-25 13:49:49.567  3487  3869 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=5, legacyType=-1, [] ]
,05-25 13:49:49.577  3487  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:49.577  3487  3869 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:49:49.577  3487  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:49:49.577  3487  3869 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:49.577  3487  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:49:49.577  3487  3869 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ],
,05-25 13:49:49.587  3487  3570 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:49.597  3487  3570 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{df2b16a u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4dd8ff 10206:com.google.android.apps.photos/u0a135}
,05-25 13:49:49.607  3487  3570 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{67c1b2c u0 com.google.android.gcm.CONNECTED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{28ef212 10026:com.google.android.talk/u0a117}
,05-25 13:49:49.617  3487  4920 V AlarmManager:  remove PendingIntent] PendingIntent{32729f5: PendingIntentRecord{1d11af1 com.google.android.gms broadcastIntent}}
,05-25 13:49:49.617  3487  3506 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ef3b38a u0 com.google.android.apps.photos.jobqueue.EXECUTE_JOBS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4dd8ff 10206:com.google.android.apps.photos/u0a135}
,05-25 13:49:49.627  3487  3506 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:49.627  3487  3506 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{df2b16a u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e493d9d 4690:com.sec.android.daemonapp/u0a166}
,05-25 13:49:49.637  4690  4690 D [Weather Widget]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CFAAE09BFCA326403459399C53A4EE79DAC193CEB26509F8FF7498BE5251A746097407E81C28CD811D388C49D613C81F395B356AA489D29CB4C3BE983CCC84BA76AF507AA66A943348DF162DECA2A5A7DD]}
,05-25 13:49:49.637  4690  4690 D [Weather Widget]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CFE2E89F45594D9820F24D88E9AF210A78F9CD3967C07B6DE6AAB9923C4C53919020112019F4465EB3AA6FD266958B212E]}
,05-25 13:49:49.647  3487  3506 D ActivityManager:  getDeferredInfo final delay 300
,05-25 13:49:49.657  3949  4154 D ViewRootImpl: #3 mView = null
,05-25 13:49:49.657  3487  4196 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3487) eventTime = 210249
,05-25 13:49:49.657  3487  4196 D PowerManagerService: [s] UserActivityState : 4 -> 1
05-25 13:49:49.657  3487  4196 D PowerManagerService: [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3487 (0x0)
05-25 13:49:49.657  3487  4196 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3487, ws=WorkSource{10065}) (elapsedTime=1949)
,05-25 13:49:49.727  3487  6298 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,05-25 13:49:49.947  3487  3570 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:49.967  3487  3570 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{df2b16a u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9038aca 8028:com.sec.android.app.samsungapps/u0a16}
,05-25 13:49:49.967  8028  8028 D [SAUI]  : NetworkStateReceiver::connected::recovered?false
,05-25 13:49:49.987  8028  8028 D [SAUI]  : Global::recovered::false
,05-25 13:49:49.987  3487  4408 D ActivityManager:  getDeferredInfo final delay 300
05-25 13:49:49.997  8028  8028 D [SAUI]  : AutoUpdateService::onStartCommand
05-25 13:49:49.997  8028  8028 D [SAUI]  : AutoUpdateService::runAutoUpdateManager
,05-25 13:49:49.997  8028  8028 D [SAUI]  : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,05-25 13:49:49.997  8028  8028 D [SAUI]  : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
,05-25 13:49:49.997  8028  8028 D [SA_INIT]: AutoUpdateManager ServiceInitializer startInitialize()
,05-25 13:49:49.997  8028  9205 D [SA_INIT]: createTaskForServiceInitialize()
,05-25 13:49:50.007  8028  9205 D [SA_INIT]: NetworkStateCheckUnit workImpl()
,05-25 13:49:50.007  8028  9205 D [SA_INIT]: NetworkStateCheckUnit result : 1
,05-25 13:49:50.007  8028  8028 V JOULE   : JOULELOG [main]  com.sec.android.app.joule.f Task [35, 196282281_0] [END] FINISHED
05-25 13:49:50.007  8028  8028 D [SA_INIT]: ServiceInitializer onInitializeResult() reuslt : true
05-25 13:49:50.007  8028  8028 D [SAUI]  : AutoUpdateManager:INITCHECK:onInitializeSuccess
,05-25 13:49:50.007  8028  8028 D [SAUI]  : AutoUpdateTriggerManager:IDLE:notifyNextTime
,05-25 13:49:50.007  8028  8028 D [SAUI]  : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,05-25 13:49:50.107  3487  3565 D libgps  : agps_ril_update_network_availability: Waiting for IPC connection - timeout
05-25 13:49:50.107  3487  3565 E libgps  : LIBGPS: Cannot communicate (write) with a GPSD
05-25 13:49:50.107  3487  3565 E libgps  : IPC Communication Error, ../../../../tmp/14982990_270314/allPartners/os/android/gps_interface/gpsi_client/GpsiClient.cpp:1729 agps_ril_update_network_availability
,05-25 13:49:50.207  3011  4455 I SurfaceFlinger: id=22 Removed Uoast (11/13)
,05-25 13:49:50.207  3011  3024 I SurfaceFlinger: id=22 Removed Uoast (-2/13)
,05-25 13:49:50.217  3011  3011 D libEGL  : eglTerminate EGLDisplay = 0x7fd4d61458
,05-25 13:49:50.297  3487  3570 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:50.317  3487  3570 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{40ead37 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f5b23c 10063:com.sec.android.diagmonagent/1000}
,05-25 13:49:50.317 10063 10063 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,05-25 13:49:50.317 10063 10063 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
,05-25 13:49:50.317 10063 10063 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,05-25 13:49:50.317  3487  4407 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:50.337  3487  4407 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{40ead37 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7d2491a 10075:com.samsung.android.sm.policy/u0a142}
,05-25 13:49:50.347  3487  4407 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:50.357  3487  4407 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{8065032 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7461dc7 9658:com.policydm/1000}
,05-25 13:49:50.357  9658  9658 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(51/onReceive)] RegistrationReceiver onReceive! action = android.net.conn.CONNECTIVITY_CHANGE
,05-25 13:49:50.397  9658  9658 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(87/llllIIIllIlIIIIllllI)] device register flag at setting DB : true
,05-25 13:49:50.407  9658  9658 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(96/onReceive)] Already device registered...
,05-25 13:49:50.407  9658  9658 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(87/llllIIIllIlIIIIllllI)] device register flag at setting DB : true
,05-25 13:49:50.417  9658  9658 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(342/lllIlIlIIIllIIlIllIl)] OMC not Supported model
,05-25 13:49:50.427  9658  9658 I DBG_POLICYDM: [IIIIlllIIIlIlllllIll(111/llIlIIIIlIIIIIlIlIII)] Polling time is vaild
,05-25 13:49:50.427  9658  9658 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(281/llIIIIlllllIIllIIllI)] Heartbeat settings is activated.
,05-25 13:49:50.427  9658  9658 I DBG_POLICYDM: [IIlllIIllIllIllIIlll(52/llllIIIllIlIIIIllllI)] Next heartbeat time:2017/06/06/21:30:16
,05-25 13:49:50.427  9658  9658 I DBG_POLICYDM: [IIlllIIllIllIllIIlll(55/llllIIIllIlIIIIllllI)] heartbeat time is vaild
,05-25 13:49:50.437  3487  3506 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:50.437  3487  3506 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{8065032 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c179cff 8501:com.osp.app.signin/u0a44}
,05-25 13:49:50.437  8501  8501 I SA      : [OR] onReceive log=[SA = 2.2.02-12 V = 23 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = pl_PL CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hero2lte P = hero2ltexx I = MMB29K M = SM-G935F OKLEFT false DIS MMB29K.G935FXXU1BPJG PSS = 5.460694751064798  ]
,05-25 13:49:50.447  8501  8501 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
,05-25 13:49:50.447  8501  8501 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,05-25 13:49:50.457  8501  8501 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
05-25 13:49:50.457  8501  8501 I SA      : [OR] == isSIMCardReady false ==
,05-25 13:49:50.457  8501  8501 I SA      : [SCU] == networkStateCheck == true
05-25 13:49:50.457  8501  8501 I SA      : [DM] getCountryCodeFromCSC : PL
05-25 13:49:50.457  8501  8501 I SA      : isChinaCountryCode : false
05-25 13:49:50.457  8501  8501 I SA      : [SCU] is ChinestModel Data Restricted   : false
05-25 13:49:50.457  8501  8501 I SA      : [OR] == networkStateCheck true ==
05-25 13:49:50.457  8501  8501 I SA      : [OR] GetMyCountryZoneTask
,05-25 13:49:50.457  8501  8501 I SA      : [OR] onReceive END
,05-25 13:49:50.457  8501 10267 I SA      : [SRS] prepareGetMyCountryZone
05-25 13:49:50.457  3487  4947 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:50.467  3487  4947 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{8065032 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b599297 6969:com.wssyncmldm/1000}
,05-25 13:49:50.467  8501 10267 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
05-25 13:49:50.467  8501 10267 I SA      : [SSP] query invoked
,05-25 13:49:50.477  8501 10267 I SA      : [TPMU] GetMccFromDB : null
05-25 13:49:50.477  8501 10267 I SA      : [SCU] getMccFromPreferece mcc = 260
05-25 13:49:50.477  8501 10267 I SA      : [LBE] isSupportCheckDomainRegion : true
05-25 13:49:50.477  8501 10267 I SA      : [TPM] isNoProxy(default) : true
,05-25 13:49:50.477  8501 10267 I SA_HTTPURLCONNECTION: [RC New] Execute method=[GET] start
,05-25 13:49:50.477  3487  3505 D ActivityManager:  getDeferredInfo final delay 300
,05-25 13:49:50.487  6969 10268 I FOTA_AGENT: [com.samsung.android.app.fotaclient.llIlIIIIlIIIIIlIlIII(87/llIIIIlllllIIllIIllI)] Nothing to do action: android.net.conn.CONNECTIVITY_CHANGE
,05-25 13:49:50.507  8501 10267 I SA_HTTPURLCONNECTION: [RC New] Security=[true]
05-25 13:49:50.507  8501 10267 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
05-25 13:49:50.507  8501 10267 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,05-25 13:49:50.507  3157  3634 D EnterpriseController: netId is 0
05-25 13:49:50.507  3157  3634 D Netd    : getNetworkForDns: using netid 503 for uid 10044
,05-25 13:49:50.817  3487  3570 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:50.827  3487  3570 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{8065032 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f2235e5 7080:com.samsung.fresco.logging/5015}
,05-25 13:49:50.837  3487  4408 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,05-25 13:49:50.837  3487  4196 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:50.837  3487  3985 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:50.847  3487  3985 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{8065032 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e21f0f4 7478:com.sec.spp.push/u0a42}
,05-25 13:49:50.847  7478  7478 E SPPClientService: [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,05-25 13:49:50.847  7478  7478 E SPPClientService: [SystemStateMoniter] Current Time : 211432
,05-25 13:49:50.847  7478  7478 E SPPClientService: [SystemStateMoniter] No Connect : false
,05-25 13:49:50.847  3487  3985 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:50.857  3487  3985 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{8065032 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{81e27c 4973:android.process.media/u0a51}
,05-25 13:49:50.857  4973  4973 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,05-25 13:49:50.867  3487  4920 D ActivityManager:  getDeferredInfo final delay 300
,05-25 13:49:50.887  3487  3854 D SecContentProvider2: query(), uri = 15 selection = getAppBlockDownloadState
,05-25 13:49:51.117 10176 10176 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,05-25 13:49:51.177  3487  3570 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:51.197  3487  3570 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{8065032 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6154579 10134:com.samsung.android.SettingsReceiver/1000}
,05-25 13:49:51.197 10134 10134 E ActivityThread: Failed to find provider info for com.myscript.atk.rmc
,05-25 13:49:51.197  3487  4407 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:51.207  3487  4407 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{8065032 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f28226c 10147:com.samsung.android.themestore/u0a68}
,05-25 13:49:51.207 10147 10147 D AutoSelfUpgradeReceiver: onReceive() android.net.conn.CONNECTIVITY_CHANGE
,05-25 13:49:51.237  3487  4065 D ActivityManager:  getDeferredInfo final delay 300
,05-25 13:49:51.237 10147 10147 D AutoSelfUpgradeService: onCreate() 
,05-25 13:49:51.247 10147 10147 D AutoSelfUpgradeService: onStartCommand() action.selfupgrade.via.net
,05-25 13:49:51.247 10147 10272 D AutoSelfUpgradeService: startInitAutoSelfUpdate()
,05-25 13:49:51.247 10147 10272 D AutoSelfUpgradeService: getAlarmIntent() 
,05-25 13:49:51.257 10147 10272 D AutoSelfUpgradeService: isAlarmActivated() false
,05-25 13:49:51.257 10147 10272 I AutoSelfUpgradeService: Not a time to rum self upgrade yet.
,05-25 13:49:51.257 10147 10147 D AutoSelfUpgradeService: onDestroy()
,05-25 13:49:51.447  9844  9908 I io.jxcore.node.IncomingSocketThreadTest: testRun
,05-25 13:49:51.457  9844 10273 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
05-25 13:49:51.457  9844 10273 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,05-25 13:49:51.457  3157  3634 D EnterpriseController: netId is 0
05-25 13:49:51.467  3157  3634 D Netd    : getNetworkForDns: using netid 503 for uid 10078
,05-25 13:49:51.467  9844 10275 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
05-25 13:49:51.467  9844 10275 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
05-25 13:49:51.467  9844 10275 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-25 13:49:51.467  9844 10275 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-25 13:49:51.467  9844 10275 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
05-25 13:49:51.467  9844 10273 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
05-25 13:49:51.467  9844 10273 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
05-25 13:49:51.467  9844 10273 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-25 13:49:51.467  9844 10273 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,05-25 13:49:51.467  9844 10273 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,05-25 13:49:51.467  9844 10278 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 245, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:51.467  9844 10278 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:49:51.467  9844 10278 D io.jxcore.node.StreamCopyingThread:  id: 77
05-25 13:49:51.467  9844 10277 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 244, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:51.467  9844 10277 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:49:51.467  9844 10277 D io.jxcore.node.StreamCopyingThread:  id: 77
05-25 13:49:51.467  9844 10278 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 245, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:51.467  9844 10278 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:49:51.467  9844 10278 D io.jxcore.node.StreamCopyingThread:  id: 77
,05-25 13:49:51.467  9844 10278 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:51.467  9844 10278 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:49:51.467  9844 10278 D io.jxcore.node.StreamCopyingThread:  id: 77
05-25 13:49:51.467  9844 10278 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
05-25 13:49:51.467  9844 10278 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
05-25 13:49:51.467  9844 10278 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,05-25 13:49:51.467  9844 10278 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
05-25 13:49:51.467  9844 10278 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
05-25 13:49:51.477  9844 10278 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
05-25 13:49:51.477  9844 10278 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 245, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:51.477  9844 10278 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:49:51.477  9844 10278 D io.jxcore.node.StreamCopyingThread:  id: 77 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
05-25 13:49:51.477  9844 10279 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 246, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:51.477  9844 10279 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:49:51.477  9844 10279 D io.jxcore.node.StreamCopyingThread:  id: 78
,05-25 13:49:51.477  9844 10279 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 246, thread name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:51.477  9844 10279 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:49:51.477  9844 10279 D io.jxcore.node.StreamCopyingThread:  id: 78
05-25 13:49:51.477  9844 10279 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:51.477  9844 10279 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:49:51.477  9844 10279 D io.jxcore.node.StreamCopyingThread:  id: 78
05-25 13:49:51.477  9844 10279 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
05-25 13:49:51.477  9844 10279 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
05-25 13:49:51.477  9844 10277 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 244, thread name: IncomingSocketThread/Sender): Socket closed
05-25 13:49:51.477  9844 10279 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
05-25 13:49:51.477  9844 10279 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,05-25 13:49:51.477  9844 10279 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
05-25 13:49:51.477  9844 10279 I io.jxcore.node.OutgoingSocketThread: The sending thread is done
05-25 13:49:51.477  9844 10279 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 246, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:51.477  9844 10279 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:49:51.477  9844 10279 D io.jxcore.node.StreamCopyingThread:  id: 78 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
05-25 13:49:51.477  9844 10277 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 244, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:51.477  9844 10277 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:49:51.477  9844 10277 D io.jxcore.node.StreamCopyingThread:  id: 77 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
05-25 13:49:51.477  9844 10280 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 247, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:51.477  9844 10280 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:49:51.477  9844 10280 D io.jxcore.node.StreamCopyingThread:  id: 78
05-25 13:49:51.477  9844 10277 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
,05-25 13:49:51.477  9844 10277 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
05-25 13:49:51.477  9844 10277 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 244, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:51.477  9844 10277 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:49:51.477  9844 10277 D io.jxcore.node.StreamCopyingThread:  id: 77 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
05-25 13:49:51.477  9844 10280 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 247, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:51.477  9844 10280 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:49:51.477  9844 10280 D io.jxcore.node.StreamCopyingThread:  id: 78
05-25 13:49:51.477  9844 10280 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:51.477  9844 10280 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:49:51.477  9844 10280 D io.jxcore.node.StreamCopyingThread:  id: 78
05-25 13:49:51.477  9844 10280 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
05-25 13:49:51.477  9844 10280 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,05-25 13:49:51.477  9844 10280 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
05-25 13:49:51.477  9844 10280 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
05-25 13:49:51.477  9844 10280 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
05-25 13:49:51.477  9844 10280 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
05-25 13:49:51.477  9844 10280 I io.jxcore.node.OutgoingSocketThread: Both threads are done, notifying the listener...
05-25 13:49:51.477  9844 10280 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 247, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:51.477  9844 10280 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:49:51.477  9844 10280 D io.jxcore.node.StreamCopyingThread:  id: 78 .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,05-25 13:49:51.537  3487  3570 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:51.557  3487  3570 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{8065032 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5e2cfd2 9132:com.samsung.android.scloud:contentsync/5009}
,05-25 13:49:51.557  9132  9132 I [SC]DetectorReceiver: onReceive [android.net.conn.CONNECTIVITY_CHANGE]
,05-25 13:49:51.557  9132  9132 I [SC]CloudManager: requestInit
05-25 13:49:51.557  9132  9132 I [SC]Utils: folder : cachecreate fail, try again.
05-25 13:49:51.557  9132  9132 I [SC]Utils: folder : cache create fail.
,05-25 13:49:51.557  9132  9132 I [SC]Utils: folder : thumbnailcreate fail, try again.
05-25 13:49:51.557  9132  9132 I [SC]Utils: folder : thumbnail create fail.
,05-25 13:49:51.557  9132  9132 I [SC]Utils: folder : sharecreate fail, try again.
05-25 13:49:51.557  9132  9132 I [SC]Utils: folder : share create fail.
,05-25 13:49:51.557  9132  9132 I [SC]Utils: folder : scratchcreate fail, try again.
05-25 13:49:51.557  9132  9132 I [SC]Utils: folder : scratch create fail.
,05-25 13:49:51.567  9132  9132 I [SC]Utils: folder : eventSynccreate fail, try again.
,05-25 13:49:51.567  9132  9132 I [SC]Utils: folder : eventSync create fail.
,05-25 13:49:51.597  8501  8512 I SA      : [SCU] isHaveSA() - false
05-25 13:49:51.597  8501  8512 I SA      : [OCP] Samsung account is not Signed-in
,05-25 13:49:51.597  8501  8512 I SA      : [OCP] Delete DB (TNC data)
,05-25 13:49:51.607  9132  9132 I [SC]CommonUtil: Samsung Account Not Logged in
,05-25 13:49:51.607  3157  3631 D Netd    : Iface wlan0 link up
05-25 13:49:51.607  3487  3980 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:51.617  4952  5261 D PdnController: Interface Changed wlan0 link up
05-25 13:49:51.617  3487  3577 D Tethering: interfaceLinkStateChanged wlan0, true
,05-25 13:49:51.617  3487  3577 D Tethering: interfaceStatusChanged wlan0, true
05-25 13:49:51.617 10112 10112 I wpa_supplicant: nl80211: Received scan results (28 BSSes)
,05-25 13:49:51.627  3487  3858 D WifiP2pService: InactiveState{ what=147461 }
,05-25 13:49:51.627  3487  3858 D WifiP2pService: P2pEnabledState{ what=147461 }
,05-25 13:49:51.627  3487  3858 D WifiP2pService: DefaultState{ what=147461 }
,05-25 13:49:51.637  3487  3980 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{8065032 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{882cab8 9147:com.samsung.android.coreapps/5011}
,05-25 13:49:51.667  3487  3487 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.SCAN_RESULTS
,05-25 13:49:51.677  3487  3570 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{80f29e2 u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a665293 3949:com.android.systemui/u0a65}
,05-25 13:49:51.697  3487  3985 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:51.707  3487  3985 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{8065032 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{882cab8 9147:com.samsung.android.coreapps/5011}
,05-25 13:49:51.727  3487  4417 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:51.727  3487  4417 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{8065032 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{882cab8 9147:com.samsung.android.coreapps/5011}
,05-25 13:49:51.737  3487  4417 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:51.747  3487  4417 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{8065032 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{10aea20 4985:com.microsoft.skydrive/u0a130}
,05-25 13:49:51.767  3487  4196 W IntentResolver: resolveIntent failed: found match, but none with CATEGORY_DEFAULT
,05-25 13:49:51.767  3487  3985 D ActivityManager:  getDeferredInfo final delay 300
,05-25 13:49:52.117  3487  3570 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:52.127  3487  3570 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{8065032 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4dd8ff 10206:com.google.android.apps.photos/u0a135}
,05-25 13:49:52.137  3487  3570 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{fd8bca9 u0 com.google.android.apps.photos.actionqueue.INTERNAL_ACTION qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4dd8ff 10206:com.google.android.apps.photos/u0a135}
05-25 13:49:52.137  3487  3985 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:52.147  3487  3985 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{8065032 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4dd8ff 10206:com.google.android.apps.photos/u0a135}
,05-25 13:49:52.177  3487  3570 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a3121cf u0 com.google.android.apps.photos.jobqueue.EXECUTE_JOBS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4dd8ff 10206:com.google.android.apps.photos/u0a135}
05-25 13:49:52.177  3487  4408 D ActivityManager:  getDeferredInfo final delay 300
,05-25 13:49:52.477  3487  3570 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:52.487  3487  3570 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{8065032 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e493d9d 4690:com.sec.android.daemonapp/u0a166}
,05-25 13:49:52.487  4690  4690 D [Weather Widget]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CFAAE09BFCA326403459399C53A4EE79DAC193CEB26509F8FF7498BE5251A746097407E81C28CD811D388C49D613C81F395B356AA489D29CB4C3BE983CCC84BA76AF507AA66A943348DF162DECA2A5A7DD]}
,05-25 13:49:52.487  4690  4690 D [Weather Widget]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CFE2E89F45594D9820F24D88E9AF210A78152C254DDD0027D207FA50AD616546E30965FECE0D7B834EEF4B0E211833EA2B]}
05-25 13:49:52.487  3487  4947 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:52.497  3487  4947 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{8065032 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9038aca 8028:com.sec.android.app.samsungapps/u0a16}
,05-25 13:49:52.497  8028  8028 D [SAUI]  : NetworkStateReceiver::connected::recovered?false
,05-25 13:49:52.517  8028  8028 D [SAUI]  : Global::recovered::false
,05-25 13:49:52.517  3487  4920 D ActivityManager:  getDeferredInfo final delay 300
05-25 13:49:52.517  8028  8028 D [SAUI]  : AutoUpdateService::onStartCommand
05-25 13:49:52.517  8028  8028 D [SAUI]  : AutoUpdateService::runAutoUpdateManager
,05-25 13:49:52.517  8028  8028 D [SAUI]  : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,05-25 13:49:52.517  8028  8028 D [SAUI]  : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
05-25 13:49:52.517  8028  8028 D [SA_INIT]: AutoUpdateManager ServiceInitializer startInitialize()
,05-25 13:49:52.517  8028  9604 D [SA_INIT]: createTaskForServiceInitialize()
05-25 13:49:52.517  8028  9604 D [SA_INIT]: NetworkStateCheckUnit workImpl()
,05-25 13:49:52.527  8028  9604 D [SA_INIT]: NetworkStateCheckUnit result : 1
,05-25 13:49:52.527  8028  8028 V JOULE   : JOULELOG [main]  com.sec.android.app.joule.f Task [35, 62762588_0] [END] FINISHED
05-25 13:49:52.527  8028  8028 D [SA_INIT]: ServiceInitializer onInitializeResult() reuslt : true
05-25 13:49:52.527  8028  8028 D [SAUI]  : AutoUpdateManager:INITCHECK:onInitializeSuccess
,05-25 13:49:52.527  8028  8028 D [SAUI]  : AutoUpdateTriggerManager:IDLE:notifyNextTime
,05-25 13:49:52.527  8028  8028 D [SAUI]  : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,05-25 13:49:52.747  8501 10267 I SA_HTTPURLCONNECTION: [RC New] [v2liruge] api execute + 2248
,05-25 13:49:52.757  8501 10267 I SA      : [ODM] saveOpenData( GEO_IP, PL )
,05-25 13:49:52.767  8501 10267 I SA      : [OCP] update openData : PL
,05-25 13:49:52.767  8501 10267 I SA      : [TPMU] getNetworkMcc : 
,05-25 13:49:52.777  8501 10267 I SA      : [SCU] saveMccToPreferece Start
05-25 13:49:52.777  8501 10267 I SA      : [SCU] RegionMCC : 260
05-25 13:49:52.777  8501 10267 I SA      : [SSP] query invoked
,05-25 13:49:52.777  8501 10267 I SA      : [TPMU] GetMccFromDB : null
05-25 13:49:52.777  8501 10267 I SA      : [SCU] getMccFromPreferece mcc = 260
,05-25 13:49:52.777  8501 10267 I SA      : [SCU] saveMccToPreferece End
05-25 13:49:52.777  8501 10267 I SA_HTTPURLCONNECTION: [RC New] executeRequest [v2liruge] end. 2301
05-25 13:49:52.777  8501 10267 I SA_HTTPURLCONNECTION: [RC New] Execute end
05-25 13:49:52.777  8501  8501 I SA      : [OR] GetMyCountryZoneTask mcc = 260
05-25 13:49:52.777  8501  8501 I SA      : [OR] GetMyCountryZoneTask Success
,05-25 13:49:53.977  3487  4417 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-25 13:49:53.977  3487  4417 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4346, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:49:53.977  3487  4417 D BatteryService: online:4, current avg:-1, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:180
05-25 13:49:53.977  3487  3487 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:49:53.977  3487  3487 I MotionRecognitionService: Plugged
,05-25 13:49:53.977  3487  3487 D MotionRecognitionService:   cableConnection= 1
05-25 13:49:53.977  3487  3487 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:49:53.977  3487  3487 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:49:53.987  3487  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:49:53.987  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
05-25 13:49:53.987  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
,05-25 13:49:53.997  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:49:53.997  3949  3949 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
05-25 13:49:53.997  3949  3949 D PowerUI.Notification: There is no change about charging status, so return!
,05-25 13:49:54.007  4952  4952 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:49:54.017  4952  4952 D BatteryMonitor: new battery level: 100
,05-25 13:49:54.017  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,05-25 13:49:54.017  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,05-25 13:49:54.027  4907  4907 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,05-25 13:49:54.027  4907  9949 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-25 13:49:55.107  3487  6263 D SSRM:n  : SIOP:: AP = 330, PST = 331 (W:10), CP = 276, CUR = -1, LCD = 40
,05-25 13:49:55.117 10176 10176 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,05-25 13:49:55.587  3487  3869 D ConnectivityService: handlePromptUnvalidated 503
,05-25 13:49:56.457  9844  9908 I io.jxcore.node.IncomingSocketThreadTest: IncomingSocketThreadTest failed, attempts left 9
05-25 13:49:56.457  9844  9908 I io.jxcore.node.IncomingSocketThreadTest: outgoingOutputStream.toString() = Nullam in massa. Vivamus elit odio, in neque ut congue quis, venenatis placerat, nulla ornare suscipit, erat urna, pellentesque dapibus vel, lorem. Sed egestas non, dolor. Aliquam hendrerit sollicitudin sed.
05-25 13:49:56.457  9844  9908 I io.jxcore.node.IncomingSocketThreadTest: textIncoming = Nullam in massa. Vivamus elit odio, in neque ut congue quis, venenatis placerat, nulla ornare suscipit, erat urna, pellentesque dapibus vel, lorem. Sed egestas non, dolor. Aliquam hendrerit sollicitudin sed.
05-25 13:49:56.457  9844  9908 I !!      :  finally closed
,05-25 13:49:56.467  9844  9908 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
,05-25 13:49:56.467  9844  9908 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,05-25 13:49:56.467  9844  9908 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
05-25 13:49:56.467  9844  9908 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,05-25 13:49:56.467  9844  9908 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,05-25 13:49:56.477  9844  9908 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
,05-25 13:49:56.477  9844  9908 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.thaliproject.thalitest.MainActivity@7edc3f2 Bundle[{}]
05-25 13:49:56.477  9844  9908 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
05-25 13:49:56.477  9844  9908 I io.jxcore.node.LifeCycleMonitor: start: OK
,05-25 13:49:56.477  9844  9908 I io.jxcore.node.LifeCycleMonitor: stop: OK
,05-25 13:49:56.477  9844  9908 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
05-25 13:49:56.477  9844  9908 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,05-25 13:49:56.487  9844  9908 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
05-25 13:49:56.487  9844  9908 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,05-25 13:49:56.487  9844  9908 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
05-25 13:49:56.487  9844  9908 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,05-25 13:49:56.487  9844  9908 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
,05-25 13:49:56.487  9844  9908 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,05-25 13:49:56.487  9844  9908 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
,05-25 13:49:56.497  9844  9908 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,05-25 13:49:56.497  9844  9908 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
,05-25 13:49:56.497  9844  9908 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
,05-25 13:49:56.497  9844  9908 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
05-25 13:49:56.497  9844  9908 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
,05-25 13:49:56.507  9844  9908 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testRun
,05-25 13:49:56.507  9844 10288 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
05-25 13:49:56.507  9844 10288 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,05-25 13:49:56.517  3157  3634 D EnterpriseController: netId is 0
,05-25 13:49:56.517  3157  3634 D Netd    : getNetworkForDns: using netid 503 for uid 10078
,05-25 13:49:56.517  9844 10290 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,05-25 13:49:56.517  9844 10290 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
05-25 13:49:56.517  9844 10290 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-25 13:49:56.517  9844 10288 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
05-25 13:49:56.517  9844 10288 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
05-25 13:49:56.517  9844 10290 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-25 13:49:56.517  9844 10288 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-25 13:49:56.517  9844 10290 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
05-25 13:49:56.517  9844 10288 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,05-25 13:49:56.517  9844 10288 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,05-25 13:49:56.527  9844 10295 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 254, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:56.527  9844 10295 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:49:56.527  9844 10295 D io.jxcore.node.StreamCopyingThread:  id: 81
05-25 13:49:56.527  9844 10295 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 254, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:56.527  9844 10295 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:49:56.527  9844 10295 D io.jxcore.node.StreamCopyingThread:  id: 81
05-25 13:49:56.527  9844 10295 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:56.527  9844 10295 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:49:56.527  9844 10295 D io.jxcore.node.StreamCopyingThread:  id: 81
05-25 13:49:56.527  9844 10295 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
05-25 13:49:56.527  9844 10295 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,05-25 13:49:56.527  9844 10295 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
05-25 13:49:56.527  9844 10295 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
05-25 13:49:56.527  9844 10295 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
05-25 13:49:56.527  9844 10295 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
05-25 13:49:56.527  9844 10295 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 254, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:56.527  9844 10295 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:49:56.527  9844 10295 D io.jxcore.node.StreamCopyingThread:  id: 81 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
05-25 13:49:56.527  9844 10293 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 252, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:56.527  9844 10293 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:49:56.527  9844 10293 D io.jxcore.node.StreamCopyingThread:  id: 80
05-25 13:49:56.527  9844 10293 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 252, thread name: IncomingSocketThread/Receiver): sendto failed: EPIPE (Broken pipe)
05-25 13:49:56.527  9844 10293 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 252, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:56.527  9844 10293 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:49:56.527  9844 10293 D io.jxcore.node.StreamCopyingThread:  id: 80 .During the lifetime of the thread the total number of bytes read was 8192 and the total number of bytes written 4096
05-25 13:49:56.527  9844 10293 E io.jxcore.node.IncomingSocketThread: The receiving thread failed with error "Failed to write to the output stream: sendto failed: EPIPE (Broken pipe)", this is likely due to peer having disconnected
,05-25 13:49:56.527  9844 10293 D io.jxcore.node.StreamCopyingThread: number of bytes read = 4096
05-25 13:49:56.527  9844 10293 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 252, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:56.527  9844 10293 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:49:56.527  9844 10293 D io.jxcore.node.StreamCopyingThread:  id: 80 .During the lifetime of the thread the total number of bytes read was 8192 and the total number of bytes written 4096
05-25 13:49:56.527  9844 10292 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 251, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:56.527  9844 10292 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:49:56.527  9844 10292 D io.jxcore.node.StreamCopyingThread:  id: 80
05-25 13:49:56.527  9844 10292 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 251, thread name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:56.527  9844 10292 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:49:56.527  9844 10292 D io.jxcore.node.StreamCopyingThread:  id: 80
05-25 13:49:56.527  9844 10292 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:56.527  9844 10292 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:49:56.527  9844 10292 D io.jxcore.node.StreamCopyingThread:  id: 80
05-25 13:49:56.527  9844 10292 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
05-25 13:49:56.527  9844 10292 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
05-25 13:49:56.527  9844 10292 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
05-25 13:49:56.527  9844 10292 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
05-25 13:49:56.527  9844 10292 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
05-25 13:49:56.527  9844 10292 I io.jxcore.node.IncomingSocketThread: The sending thread is done
05-25 13:49:56.527  9844 10292 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 251, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:56.527  9844 10292 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:49:56.527  9844 10292 D io.jxcore.node.StreamCopyingThread:  id: 80 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,05-25 13:49:56.527  9844 10294 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 253, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:56.527  9844 10294 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:49:56.527  9844 10294 D io.jxcore.node.StreamCopyingThread:  id: 81
05-25 13:49:56.527  9844 10294 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 253, thread name: OutgoingSocketThread/Sender): recvfrom failed: EBADF (Bad file descriptor)
05-25 13:49:56.527  9844 10294 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 253, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:56.527  9844 10294 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:49:56.527  9844 10294 D io.jxcore.node.StreamCopyingThread:  id: 81 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
05-25 13:49:56.527  9844 10294 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: recvfrom failed: EBADF (Bad file descriptor)
05-25 13:49:56.527  9844 10294 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
05-25 13:49:56.527  9844 10294 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 253, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:56.527  9844 10294 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:49:56.527  9844 10294 D io.jxcore.node.StreamCopyingThread:  id: 81 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
,05-25 13:49:58.227 10026 10047 W Babel   : ayr TOOK TOO LONG! (15001ms > 10000ms)
05-25 13:49:58.227 10026 10049 W Babel   : ayr TOOK TOO LONG! (15001ms > 10000ms)
,05-25 13:49:58.247  3487  3506 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity newState = 2 callingPackage = 10117
,05-25 13:49:58.297 10026 10058 W Babel   : ayr TOOK TOO LONG! (15001ms > 10000ms)
,05-25 13:49:58.307 10296 10296 E Zygote  : v2
05-25 13:49:58.307 10296 10296 I libpersona: KNOX_SDCARD checking this for 10117
05-25 13:49:58.307 10296 10296 I libpersona: KNOX_SDCARD not a persona
,05-25 13:49:58.307 10296 10296 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-25 13:49:58.307  3487  3570 I ActivityManager: Start proc 10296:com.google.android.talk:matchstick/u0a117 for broadcast-3 com.google.android.talk/com.google.android.libraries.matchstick.net.MatchstickInProcessReceiver
05-25 13:49:58.307 10296 10296 E Zygote  : accessInfo : 0
05-25 13:49:58.307 10296 10296 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.talk:matchstick 
,05-25 13:49:58.317  3487  4197 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,05-25 13:49:58.327 10026 10026 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,05-25 13:49:58.327 10026 10026 W Babel   : BAM#gBA: invalid account id: -1
05-25 13:49:58.327 10026 10026 W Babel   : BAM#gBA: invalid account id: -1
05-25 13:49:58.327 10026 10026 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,05-25 13:49:58.337  3487  4927 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,05-25 13:49:58.347 10296 10296 D TimaKeyStoreProvider: TimaSignature is unavailable
05-25 13:49:58.347 10296 10296 D ActivityThread: Added TimaKeyStore provider
,05-25 13:49:58.367  3487  3505 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{480beb u0 register_intent_action qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{510dd48 10296:com.google.android.talk:matchstick/u0a117}
,05-25 13:49:58.377 10296 10296 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,05-25 13:49:58.387 10296 10296 D RelationGraph: garbageCollect()
,05-25 13:49:58.387 10296 10296 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.google.android.talk rsrc of package com.google.android.talk
,05-25 13:49:58.387  3487  3505 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-25 13:49:58.387 10296 10296 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-25 13:49:58.397  4163  4173 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg com.google.android.talk,id=10436,extra=Bundle[mParcelledData.dataSize=84]
05-25 13:49:58.397 10296 10296 D ResourcesManager: For user 0 new overlays fetched Null
05-25 13:49:58.397  4163  4163 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=10436, samsung.notification.type=normal, samsung.people.package_name=com.google.android.talk}]
05-25 13:49:58.397  4163  4163 I PeopleStripeService: PeopleNotificationReceiver:3
05-25 13:49:58.397  4163  4163 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
05-25 13:49:58.397  4163  4163 I PeopleDataManager: removeNotification
05-25 13:49:58.397  4163  4163 I NotificationParser: getNotiType:com.google.android.talk,null
05-25 13:49:58.397  4163  4163 D PeopleDataManager: removeNotiInfo: id =10436,packageName=com.google.android.talk,isEdgeNotification=false,key=null,removeAll=false
05-25 13:49:58.397  4163  4163 D PeopleDataManager: removeNotiInfo =null
,05-25 13:49:58.407 10296 10296 I InjectionManager: Inside getClassLibPath caller 
,05-25 13:49:58.417 10296 10296 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm64
,05-25 13:49:58.497 10296 10296 D InjectionManager: InjectionManager
05-25 13:49:58.497 10296 10296 D InjectionManager: fillFeatureStoreMap com.google.android.talk
,05-25 13:49:58.497 10296 10296 I InjectionManager: Constructor com.google.android.talk, Feature store :{}
05-25 13:49:58.497 10296 10296 I InjectionManager: featureStore :{}
,05-25 13:49:58.657 10296 10314 I MS_RegisterService: RegisterService intent:Intent { act=register_intent_action flg=0x10 cmp=com.google.android.talk/com.google.android.libraries.matchstick.net.SilentRegisterService bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} } isPeriodic:false
,05-25 13:49:58.677 10296 10314 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in com.google.android.talk rsrc of package com.google.android.gms
,05-25 13:49:58.687 10296 10314 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:49:58.687 10296 10314 I InjectionManager: Inside getClassLibPath caller 
,05-25 13:49:58.707 10296 10314 W System  : ClassLoader referenced unknown path: /system/priv-app/GmsCore/lib/arm64
,05-25 13:49:58.797 10296 10314 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,05-25 13:49:58.827 10296 10314 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,05-25 13:49:58.837 10296 10314 I MS_RegisterService: Not registered and not enabled. Doing nothing.
,05-25 13:49:58.837  3487  4197 I ActivityManager: Killing 8935:com.samsung.android.app.appsedge/u0a1 (adj 15): DHA:empty #33
,05-25 13:49:58.877  3487  4408 D ActivityManager: cleanUpApplicationRecord -- 8935
,05-25 13:49:58.877  3487  4408 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.appsedge, Auto Run ON
,05-25 13:49:59.137 10176 10176 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,05-25 13:49:59.137 10176 10176 I dhcpcd  : wlan0: no IPv6 Routers available
,05-25 13:49:59.987  3487  3817 V AlarmManager: Expired Alarm result :8
,05-25 13:50:00.017  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
05-25 13:50:00.017  3949  3949 D KeyguardUpdateMonitor: handleTimeUpdate
,05-25 13:50:00.017  8028  8028 D PreloadUpdateManagerStateMachine: execute::IDLE:EXECUTE
05-25 13:50:00.017  8028  8028 D PreloadUpdateManagerStateMachine: exit::IDLE
05-25 13:50:00.017  8028  8028 D PreloadUpdateManagerStateMachine: entry::CHECK_TIMEOUT_FOR_UPDATE
,05-25 13:50:00.027  8028  8028 D [SAUI]  : AutoUpdateTriggerManager:IDLE:notifyNextTime
05-25 13:50:00.027  8028  8028 D PreloadUpdateManagerStateMachine: execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,05-25 13:50:00.027  3949  3949 D Clock   : received broadcast android.intent.action.TIME_TICK
,05-25 13:50:00.037  8028  8028 D PreloadUpdateManagerStateMachine: exit::CHECK_TIMEOUT_FOR_UPDATE
,05-25 13:50:00.037  8028  8028 D PreloadUpdateManagerStateMachine: entry::IDLE
,05-25 13:50:00.077  3949  3949 D DateView: received broadcast android.intent.action.TIME_TICK
,05-25 13:50:00.107  4690  4690 D [Weather Widget]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,05-25 13:50:00.107  4690  4690 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EEFA9050249635C043F7E254E316C2550]}
,05-25 13:50:00.107  4690  4690 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EAB01DC5C99149A39F887E17599325AFBFF089086AA9902184ADA25758C536FE2]}
,05-25 13:50:00.117  4690  4690 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EFF0B905BDFF72B69FB632A6CB072B41F95D2E6F4F84443284E97F40042D431D8350388453A923ABD8469D82798FA7548]}
,05-25 13:50:00.117  4690  4690 D [Weather Widget]  : {[A1AF0F6A1A65A89C43D705938923D0FEFB71880C4E84718DA0A3E1F383E54FB27A4284D9BEDF7BAA2ABFFE671EB65C640578FF9DE16A23BFE3280A9DCDBB09A0087A09617A4D2E4C8CA19F92E92E7F081209ADB459A570E8D870EBA866E0F8996B7829FAC6D5657983C2B9D0F41D1C4D]}
,05-25 13:50:00.117  4690  4690 D [Weather Widget]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,05-25 13:50:02.017  9844  9908 I io.jxcore.node.OutgoingSocketThreadTest: OutgoingSocketThreadTest
,05-25 13:50:02.017  9844  9908 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,05-25 13:50:02.027  9844  9908 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testNoAvailablePorts
,05-25 13:50:02.537  8028  8028 D PreloadUpdateManagerStateMachine: execute::IDLE:EXECUTE
05-25 13:50:02.537  8028  8028 D PreloadUpdateManagerStateMachine: exit::IDLE
05-25 13:50:02.537  8028  8028 D PreloadUpdateManagerStateMachine: entry::CHECK_TIMEOUT_FOR_UPDATE
,05-25 13:50:02.547  8028  8028 D [SAUI]  : AutoUpdateTriggerManager:IDLE:notifyNextTime
,05-25 13:50:02.547  8028  8028 D PreloadUpdateManagerStateMachine: execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,05-25 13:50:02.547  8028  8028 D PreloadUpdateManagerStateMachine: exit::CHECK_TIMEOUT_FOR_UPDATE
05-25 13:50:02.547  8028  8028 D PreloadUpdateManagerStateMachine: entry::IDLE
,05-25 13:50:03.037  9844  9908 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,05-25 13:50:03.037  9844  9908 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
,05-25 13:50:03.037  9844  9908 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
,05-25 13:50:03.037  9844  9908 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 262)
,05-25 13:50:03.037  9844  9908 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
05-25 13:50:03.037  9844  9908 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
05-25 13:50:03.037  9844  9908 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 263)
,05-25 13:50:03.047  9844  9908 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
,05-25 13:50:03.047  3487  4148 E Watchdog: !@Sync 7 [05-25 13:50:03.053]
,05-25 13:50:03.047  9844  9908 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
,05-25 13:50:03.047  9844  9908 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
,05-25 13:50:03.057  9844  9908 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,05-25 13:50:03.057  9844  9908 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56e5dc1 added. We now have 2 listener(s)
05-25 13:50:03.057  9844  9908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56e5dc1 added. We now have 3 listener(s)
05-25 13:50:03.057  9844  9908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,05-25 13:50:03.057  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"A8:81:95:E9:5F:6F"}
,05-25 13:50:03.057  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
05-25 13:50:03.057  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"A8:81:95:E9:5F:6F"}
05-25 13:50:03.057  9844  9908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
05-25 13:50:03.057  9844  9908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d4e966 added. We now have 4 listener(s)
05-25 13:50:03.057  9844  9908 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
05-25 13:50:03.057  9844  9908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,05-25 13:50:03.067  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:50:03.077  9844  9908 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
,05-25 13:50:03.077  9844  9908 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
05-25 13:50:03.077  9844  9908 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
05-25 13:50:03.077  9844  9908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
05-25 13:50:03.077  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,05-25 13:50:03.087  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":4,"address":"A8:81:95:E9:5F:6F"}
,05-25 13:50:03.087  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":4,"address":"A8:81:95:E9:5F:6F"}
05-25 13:50:03.087  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:03.087  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,05-25 13:50:03.087  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":4,"address":"A8:81:95:E9:5F:6F"}
,05-25 13:50:03.087  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":4,"address":"A8:81:95:E9:5F:6F"}
05-25 13:50:03.087  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:03.087  9844  9908 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
05-25 13:50:03.087  9844  9908 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
05-25 13:50:03.087  9844  9908 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
05-25 13:50:03.087  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,05-25 13:50:03.097  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,05-25 13:50:03.097  9844  9908 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
05-25 13:50:03.097  9844  9908 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
05-25 13:50:03.097  9844  9908 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
05-25 13:50:03.097  9844  9844 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
05-25 13:50:03.097  9844  9908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
05-25 13:50:03.097  9844 10320 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,05-25 13:50:03.097  9844  9908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
05-25 13:50:03.097  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
05-25 13:50:03.097  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,05-25 13:50:03.097  9844 10320 D BluetoothSocket: bindListen(): myUserId = 0
,05-25 13:50:03.097  9844 10320 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,05-25 13:50:03.107  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,05-25 13:50:03.107  9844  9908 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
05-25 13:50:03.107  9844  9908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,05-25 13:50:03.107  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:50:03.107  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:50:03.117  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:50:03.117  9844 10320 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
05-25 13:50:03.117  9844 10320 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@2232d54, port: 6, type: 1, local socket address: null, socket type: 0
,05-25 13:50:03.117  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:50:03.117  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
05-25 13:50:03.117  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:50:03.117  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:50:03.117  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
05-25 13:50:03.117  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
05-25 13:50:03.117  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 4
,05-25 13:50:03.127  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:50:03.127  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:50:03.127  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:03.127  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
05-25 13:50:03.127  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
05-25 13:50:03.127  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "1e0175e0-0d83-4d02-aa60-d3c622da762e", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
05-25 13:50:03.127  9844  9908 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 A8 81 95 E9 5F 6F
05-25 13:50:03.127  9844  9908 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[4, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,05-25 13:50:03.127  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[4, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-25 13:50:03.127  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:03.127  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[4, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:03.127  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
05-25 13:50:03.127  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[4, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-25 13:50:03.127  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:03.127  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
,05-25 13:50:03.127  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[4, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:03.127  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:50:03.127  9844  9908 D BluetoothAdapter: STATE_ON
05-25 13:50:03.127  9844  9908 D BluetoothLeAdvertiser: start advertising
,05-25 13:50:03.137  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:50:03.137  4907  5262 D BtGatt.GattService: registerClient() - UUID=af7f310c-eefc-4db5-9a43-c951cd513f43
,05-25 13:50:03.187  4907  5037 D BtGatt.GattService: onClientRegistered() - UUID=af7f310c-eefc-4db5-9a43-c951cd513f43, clientIf=7
,05-25 13:50:03.187  9844  9855 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,05-25 13:50:03.187  4907  5370 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,05-25 13:50:03.197  4907  5370 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,05-25 13:50:03.197  4907  5370 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
05-25 13:50:03.197  4907  5071 D BtGatt.AdvertiseManager: message : 0
05-25 13:50:03.197  4907  5081 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
05-25 13:50:03.197  4907  5081 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 25, currDate: 25
05-25 13:50:03.197  4907  5071 D BtGatt.AdvertiseManager: number of adv instance running = 0
05-25 13:50:03.197  4907  5071 D BtGatt.AdvertiseManager: size of list is =0
,05-25 13:50:03.207  4907  5071 D BtGatt.AdvertiseManager: starting advertising
,05-25 13:50:03.207  4907  5071 D BtGatt.AdvertiseManager: isStandardAdv = false
,05-25 13:50:03.207  4907  5081 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.thaliproject.thalitest : 31
05-25 13:50:03.207  4907  5081 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.thaliproject.thalitest@LowLatency : 24928550
05-25 13:50:03.207  4907  5081 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.thaliproject.thalitest@LowLatency : 2
,05-25 13:50:03.207  4907  5081 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
05-25 13:50:03.207  4907  5081 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 4 => 4
,05-25 13:50:03.217  3487  4670 V AlarmManager:  remove PendingIntent] PendingIntent{1841cbf: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:03.227  3487  4197 V AlarmManager:  remove PendingIntent] PendingIntent{bc9f8c: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:03.227  4907  5037 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,05-25 13:50:03.227  4907  5071 D BtGatt.AdvertiseManager: starting multi advertising
,05-25 13:50:03.227  4907  5037 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,05-25 13:50:03.227  4907  5071 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
05-25 13:50:03.227  3487  4196 V AlarmManager:  remove PendingIntent] PendingIntent{b34c6d5: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
05-25 13:50:03.227  4907  5071 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
05-25 13:50:03.227  4907  5071 D BtGatt.AdvertiseManager: postCallback clientIf = 7 status = 0
,05-25 13:50:03.227  4907  5071 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=7, status=0, isStart=true
05-25 13:50:03.227  9844  9854 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
05-25 13:50:03.227  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:03.227  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
,05-25 13:50:03.237  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
05-25 13:50:03.237  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:03.237  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:03.237  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
,05-25 13:50:03.237  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:03.237  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:03.237  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,05-25 13:50:03.237  9844  9908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
05-25 13:50:03.237  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:50:03.237  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:03.237  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:50:03.237  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:50:03.237  9844  9844 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
05-25 13:50:03.237  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,05-25 13:50:03.237  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
05-25 13:50:03.237  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
05-25 13:50:03.237  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
,05-25 13:50:03.237  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
,05-25 13:50:03.237  9844  9844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
05-25 13:50:03.247  3487  4065 V AlarmManager:  remove PendingIntent] PendingIntent{7cbbeea: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:03.237  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
05-25 13:50:03.237  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
05-25 13:50:03.237  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,05-25 13:50:03.237  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
05-25 13:50:03.237  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
05-25 13:50:03.237  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,05-25 13:50:03.237  9844  9844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
05-25 13:50:03.237  9844  9844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
05-25 13:50:03.247  9844  9844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,05-25 13:50:03.247  9844  9844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
05-25 13:50:03.247  9844  9844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
05-25 13:50:03.247  9844  9844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
05-25 13:50:03.247  9844  9844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,05-25 13:50:03.247  3487  4947 V AlarmManager:  remove PendingIntent] PendingIntent{8e7c5db: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:03.257  3487  4671 V AlarmManager:  remove PendingIntent] PendingIntent{b5a2878: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:03.257  3487  4407 V AlarmManager:  remove PendingIntent] PendingIntent{287fb51: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:03.267  3487  4920 V AlarmManager:  remove PendingIntent] PendingIntent{41edfb6: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}},
,05-25 13:50:03.737  9844  9908 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
05-25 13:50:03.747  9844  9908 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
05-25 13:50:03.747  9844  9908 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
05-25 13:50:03.747  9844  9908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
05-25 13:50:03.747  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
05-25 13:50:03.747  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
05-25 13:50:03.747  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
05-25 13:50:03.747  9844  9908 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
05-25 13:50:03.747  9844  9908 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
05-25 13:50:03.747  9844  9908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
05-25 13:50:03.747  9844  9908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
05-25 13:50:03.747  9844 10320 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
05-25 13:50:03.747  9844 10320 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
05-25 13:50:03.747  9844 10320 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
05-25 13:50:03.747  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:03.747  9844  9844 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
05-25 13:50:03.747  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
05-25 13:50:03.747  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
05-25 13:50:03.747  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:03.747  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:03.747  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:03.747  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:50:03.747  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:50:03.747  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:50:03.747  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,05-25 13:50:03.747  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:50:03.757  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:50:03.757  9844  9908 D BluetoothLeScanner: could not find callback wrapper
05-25 13:50:03.757  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
05-25 13:50:03.757  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:03.757  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:03.757  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:50:03.757  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
05-25 13:50:03.757  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:50:03.757  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:50:03.757  9844  9908 D BluetoothAdapter: STATE_ON
05-25 13:50:03.757  9844  9908 D BluetoothLeAdvertiser: stop advertising
,05-25 13:50:03.767  4907  9972 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,05-25 13:50:03.767  4907  9972 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
05-25 13:50:03.767  4907  5071 D BtGatt.AdvertiseManager: message : 1
05-25 13:50:03.767  4907  5081 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
05-25 13:50:03.767  4907  5081 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 25, currDate: 25
05-25 13:50:03.767  4907  5081 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
,05-25 13:50:03.767  4907  5081 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 4 => 4
05-25 13:50:03.767  4907  5081 D BtGatt.GattService: [GSIM LOG]: remove : com.thaliproject.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
05-25 13:50:03.767  4907  5071 D BtGatt.AdvertiseManager: stop advertise for client =  7
,05-25 13:50:03.767  4907  5071 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 7
,05-25 13:50:03.777  4907  5071 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,05-25 13:50:03.777  4907  5037 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,05-25 13:50:03.777  4907  5037 D BtGatt.GattService: Client app is not null!
05-25 13:50:03.777  3487  4197 V AlarmManager:  remove PendingIntent] PendingIntent{612e4b7: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:03.777  9844  9854 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,05-25 13:50:03.787  4907  4919 D BtGatt.GattService: unregisterClient() - clientIf=7
,05-25 13:50:03.787  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,05-25 13:50:03.787  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:03.787  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,05-25 13:50:03.787  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:03.787  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:03.787  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:03.787  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
05-25 13:50:03.787  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
05-25 13:50:03.787  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
05-25 13:50:03.787  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:03.787  3487  3854 V AlarmManager:  remove PendingIntent] PendingIntent{4455424: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:03.797  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:50:03.797  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
05-25 13:50:03.797  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:03.797  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:03.797  9844  9844 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
05-25 13:50:03.797  9844  9844 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
05-25 13:50:03.797  9844  9844 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
05-25 13:50:03.797  9844  9844 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
05-25 13:50:03.797  9844  9844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
05-25 13:50:03.797  9844  9844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,05-25 13:50:03.797  9844  9844 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
05-25 13:50:03.797  9844  9844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
05-25 13:50:03.797  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
05-25 13:50:03.797  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,05-25 13:50:03.797  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
05-25 13:50:03.797  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
05-25 13:50:03.797  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
05-25 13:50:03.797  3487  3505 V AlarmManager:  remove PendingIntent] PendingIntent{8fffb8d: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
05-25 13:50:03.797  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
05-25 13:50:03.797  9844  9844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,05-25 13:50:03.807  3487  4417 V AlarmManager:  remove PendingIntent] PendingIntent{fb14142: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:03.817  3487  4947 V AlarmManager:  remove PendingIntent] PendingIntent{b671553: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:03.817  3487  4671 V AlarmManager:  remove PendingIntent] PendingIntent{4958e90: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:03.827  3487  4408 V AlarmManager:  remove PendingIntent] PendingIntent{87dc389: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:03.837  3487  4920 V AlarmManager:  remove PendingIntent] PendingIntent{4162f8e: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:04.017  3487  4670 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-25 13:50:04.017  3487  4670 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4340, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:50:04.017  3487  4670 D BatteryService: online:4, current avg:97, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:135
05-25 13:50:04.017  3487  3487 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:50:04.027  3487  3487 I MotionRecognitionService: Plugged
,05-25 13:50:04.027  3487  3487 D MotionRecognitionService:   cableConnection= 1
05-25 13:50:04.027  3487  3487 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:50:04.027  3487  3487 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:50:04.027  3487  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:50:04.037  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,05-25 13:50:04.037  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
,05-25 13:50:04.037  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:50:04.037  3949  3949 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,05-25 13:50:04.037  3949  3949 D PowerUI.Notification: There is no change about charging status, so return!
,05-25 13:50:04.047  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,05-25 13:50:04.057  4952  4952 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:50:04.057  4907  4907 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,05-25 13:50:04.057  4907  9949 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-25 13:50:04.077  4952  4952 D BatteryMonitor: new battery level: 100
,05-25 13:50:04.077  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,05-25 13:50:04.297  9844  9844 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,05-25 13:50:05.137  3487  6263 D SSRM:n  : SIOP:: AP = 320, PST = 330 (W:10), CP = 273, CUR = 97, LCD = 40
,05-25 13:50:06.807  9844  9908 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
05-25 13:50:06.807  9844  9908 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
05-25 13:50:06.807  9844  9908 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
05-25 13:50:06.807  9844  9908 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
05-25 13:50:06.807  9844  9908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
05-25 13:50:06.807  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
05-25 13:50:06.807  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,05-25 13:50:06.817  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,05-25 13:50:06.817  9844  9908 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
05-25 13:50:06.817  9844  9908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,05-25 13:50:06.827  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:50:06.827  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:50:06.837  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:50:06.837  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:50:06.837  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,05-25 13:50:06.847  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:50:06.847  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:50:06.847  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
05-25 13:50:06.847  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
05-25 13:50:06.847  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 4
,05-25 13:50:06.857  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:50:06.857  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:50:06.867  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:50:06.867  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:50:06.877  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:50:06.877  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
05-25 13:50:06.877  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
05-25 13:50:06.877  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 25730
,05-25 13:50:06.877  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=25730, mManufacturerData=null, mManufacturerDataMask=null]
05-25 13:50:06.877  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:06.877  9844  9908 D BluetoothLeScanner: Start Scan
,05-25 13:50:06.877  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:50:06.887  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:50:06.887  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:50:06.887  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:50:06.897  4907  5370 D BtGatt.GattService: registerClient() - UUID=91b1fb3c-7ff1-4359-822e-68916e01b3e8
,05-25 13:50:06.947  4907  5037 D BtGatt.GattService: onClientRegistered() - UUID=91b1fb3c-7ff1-4359-822e-68916e01b3e8, clientIf=7
,05-25 13:50:06.947  9844  9855 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=7
,05-25 13:50:06.947  4907  5262 D BtGatt.GattService: start scan with filters
,05-25 13:50:06.947  4907  5262 D BtGatt.GattService: getScanSettings
,05-25 13:50:06.977  4907  5262 D BtGatt.GattService: Is it foreground application = true
,05-25 13:50:06.977  4907  5262 D BtGatt.GattService: not a background application
,05-25 13:50:06.987  4907  5262 D BtGatt.GattService: [GSIM LOG]: getActualScanMode (2/100 vs -2147483648/0)
,05-25 13:50:06.987  4907  5262 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,05-25 13:50:06.997  4907  5262 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,05-25 13:50:06.997  4907  5081 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_SCAN
05-25 13:50:06.997  4907  5081 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 25, currDate: 25
,05-25 13:50:06.997  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
05-25 13:50:06.997  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:06.997  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,05-25 13:50:06.997  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:06.997  4907  5073 D BtGatt.ScanManager: handling starting scan
05-25 13:50:06.997  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
05-25 13:50:06.997  4907  5073 D BtGatt.ScanManager: isFilteringSupported
,05-25 13:50:06.997  9844  9844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
05-25 13:50:06.997  4907  5073 D BluetoothAdapter: enableStandAloneBleMode=
05-25 13:50:06.997  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
05-25 13:50:06.997  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
05-25 13:50:06.997  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
05-25 13:50:06.997  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
05-25 13:50:06.997  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
05-25 13:50:06.997  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
05-25 13:50:06.997  9844  9844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
,05-25 13:50:06.997  4907  5073 D BluetoothAdapter: STATE_ON
05-25 13:50:06.997  4907  5073 D BluetoothAdapter: STATE_ON
05-25 13:50:07.007  9844  9908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
05-25 13:50:07.007  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:07.007  4907  5073 D BluetoothAdapter: STATE_ON
,05-25 13:50:07.007  4907  5081 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.thaliproject.thalitest : 18
05-25 13:50:07.007  4907  5081 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.thaliproject.thalitest, com.thaliproject.thalitest
,05-25 13:50:07.017  4907  5073 D BluetoothAdapter: STATE_ON
,05-25 13:50:07.017  4907  5081 D BtGatt.GattService: [GSIM LOG]: increaseScanCount 4 Battery : com.thaliproject.thalitest : 1
,05-25 13:50:07.017  4907  5073 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5359fd5
05-25 13:50:07.017  4907  5081 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.thaliproject.thalitest : 24928550
,05-25 13:50:07.017  4907  5081 D BtGatt.GattService: [GSIM LOG]: setRequestedScanType : com.thaliproject.thalitest : 2
,05-25 13:50:07.017  4907  5081 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.thaliproject.thalitest : 2
,05-25 13:50:07.027  3487  4197 V AlarmManager:  remove PendingIntent] PendingIntent{ec9b69a: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:07.027  4907  5081 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
,05-25 13:50:07.027  4907  5081 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 4 => 4
05-25 13:50:07.027  4907  5081 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, A time : 4 => 4
05-25 13:50:07.027  4907  5081 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
,05-25 13:50:07.027  4907  5081 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 4 => 4
05-25 13:50:07.027  4907  5081 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, A time : 4 => 4
,05-25 13:50:07.027  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:50:07.027  4907  5081 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.thaliproject.thalitest : 2
05-25 13:50:07.027  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
05-25 13:50:07.037  3487  4407 V AlarmManager:  remove PendingIntent] PendingIntent{6a1dbcb: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
05-25 13:50:07.027  4907  5081 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
,05-25 13:50:07.027  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:07.027  4907  5081 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 4 => 4
05-25 13:50:07.027  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:07.027  4907  5081 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, A time : 4 => 4
,05-25 13:50:07.027  9844  9844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
05-25 13:50:07.027  4907  5081 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.thaliproject.thalitest : 24928550
,05-25 13:50:07.027  4907  5037 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
,05-25 13:50:07.027  4907  5037 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
05-25 13:50:07.037  4907  5073 D BtGatt.ScanManager: set filter index= 3 for clientIf= 7
,05-25 13:50:07.047  3487  4196 V AlarmManager:  remove PendingIntent] PendingIntent{de49fa8: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
05-25 13:50:07.037  4907  5073 D BtGatt.ScanManager: High Rssi Filter value is = -128
05-25 13:50:07.037  4907  5073 D BtGatt.ScanManager: Low Rssi Filter value is = -128
05-25 13:50:07.037  4907  5073 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =2
05-25 13:50:07.037  9844  9844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
05-25 13:50:07.037  4907  5037 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=31
,05-25 13:50:07.047  3487  4920 V AlarmManager:  remove PendingIntent] PendingIntent{6ed5ac1: PendingIntentRecord{6fca266 com.android.bluetooth broadcastIntent}}
05-25 13:50:07.037  9844  9844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
05-25 13:50:07.037  4907  5037 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,05-25 13:50:07.037  9844  9844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
05-25 13:50:07.037  4907  5073 D BtGatt.ScanManager: Starting BLE batch scan
05-25 13:50:07.037  4907  5073 D BtGatt.ScanManager: configuring batch scan storage, appIf 7
,05-25 13:50:07.037  9844  9844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
05-25 13:50:07.047  4907  5037 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=7, status=0
05-25 13:50:07.047  4907  5037 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,05-25 13:50:07.047  4907  5037 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=1
05-25 13:50:07.047  4907  5037 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
05-25 13:50:07.047  3487  4065 V AlarmManager:  remove PendingIntent] PendingIntent{3f069a7: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:07.057  3487  4197 V AlarmManager:  remove PendingIntent] PendingIntent{bb80e54: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:07.067  3487  4671 V AlarmManager:  remove PendingIntent] PendingIntent{ab3e1fd: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:07.067  3487  3854 V AlarmManager:  remove PendingIntent] PendingIntent{4207ef2: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:07.077  3487  3506 V AlarmManager:  remove PendingIntent] PendingIntent{9aff943: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:07.077  3487  3505 V AlarmManager:  remove PendingIntent] PendingIntent{ab1bbc0: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:07.087  3487  4417 V AlarmManager:  remove PendingIntent] PendingIntent{b61a0f9: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:07.087  3487  3980 V AlarmManager:  remove PendingIntent] PendingIntent{133983e: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:07.097  3487  4407 V AlarmManager:  remove PendingIntent] PendingIntent{94ee69f: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:07.107  3487  4196 V AlarmManager:  remove PendingIntent] PendingIntent{ed6d3ec: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:07.107  3487  4670 V AlarmManager:  remove PendingIntent] PendingIntent{a9253b5: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:07.547  9844  9844 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,05-25 13:50:07.547  9844  9844 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
05-25 13:50:07.547  9844  9844 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,05-25 13:50:08.047  3487  3817 V AlarmManager: Expired Alarm result :4
,05-25 13:50:08.057  4907  4907 D BtGatt.ScanManager: awakened up at time 228643
,05-25 13:50:08.057  4907  5073 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,05-25 13:50:08.057  3487  4947 V AlarmManager:  remove PendingIntent] PendingIntent{2c54dbb: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:08.057  4907  5037 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=0
,05-25 13:50:08.057  4907  5037 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,05-25 13:50:08.067  3487  4671 V AlarmManager:  remove PendingIntent] PendingIntent{55342d8: PendingIntentRecord{6fca266 com.android.bluetooth broadcastIntent}}
,05-25 13:50:08.087  3487  4408 V AlarmManager:  remove PendingIntent] PendingIntent{de17631: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:08.097  3487  4920 V AlarmManager:  remove PendingIntent] PendingIntent{5e87116: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:09.067  3487  3817 V AlarmManager: Expired Alarm result :4
,05-25 13:50:09.077  4907  4907 D BtGatt.ScanManager: awakened up at time 229660
,05-25 13:50:09.077  4907  5073 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,05-25 13:50:09.077  3487  3854 V AlarmManager:  remove PendingIntent] PendingIntent{25b484: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
05-25 13:50:09.077  4907  5037 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=0
05-25 13:50:09.077  4907  5037 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,05-25 13:50:09.077  3487  4196 V AlarmManager:  remove PendingIntent] PendingIntent{f26446d: PendingIntentRecord{6fca266 com.android.bluetooth broadcastIntent}}
,05-25 13:50:09.107  3487  4670 V AlarmManager:  remove PendingIntent] PendingIntent{57288a2: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:09.107  3487  4417 V AlarmManager:  remove PendingIntent] PendingIntent{6b1b933: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:09.727  3487  6298 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,05-25 13:50:10.037  9844  9908 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
,05-25 13:50:10.037  9844  9908 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
05-25 13:50:10.037  9844  9908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
05-25 13:50:10.037  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,05-25 13:50:10.037  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":5,"address":"A8:81:95:E9:5F:6F"}
,05-25 13:50:10.037  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":5,"address":"A8:81:95:E9:5F:6F"}
05-25 13:50:10.037  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:10.037  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,05-25 13:50:10.047  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":5,"address":"A8:81:95:E9:5F:6F"}
,05-25 13:50:10.047  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":5,"address":"A8:81:95:E9:5F:6F"}
05-25 13:50:10.047  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:10.047  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
05-25 13:50:10.047  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 25730
05-25 13:50:10.047  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
05-25 13:50:10.047  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 5
05-25 13:50:10.047  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
05-25 13:50:10.047  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
05-25 13:50:10.047  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
05-25 13:50:10.047  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
05-25 13:50:10.047  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
05-25 13:50:10.047  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:10.047  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 5
,05-25 13:50:10.047  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted false Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:50:10.047  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:10.047  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,05-25 13:50:10.047  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
05-25 13:50:10.047  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted true Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:10.047  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop scanner Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:10.047  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:10.057  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:50:10.057  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:50:10.057  4907  5371 D BtGatt.GattService: flushPendingBatchResults - clientIf=7, isServer=false
05-25 13:50:10.057  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,05-25 13:50:10.057  4907  5073 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,05-25 13:50:10.067  4907  5037 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=0
,05-25 13:50:10.067  9844  9908 D BluetoothAdapter: STATE_ON
05-25 13:50:10.067  4907  5037 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,05-25 13:50:10.067  3487  4408 V AlarmManager:  remove PendingIntent] PendingIntent{8b94f0: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.067  3487  4920 V AlarmManager:  remove PendingIntent] PendingIntent{46fba69: PendingIntentRecord{6fca266 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.067  9844  9908 D BluetoothAdapter: STATE_ON
05-25 13:50:10.067  9844  9908 D BluetoothLeScanner: Stop Scan
,05-25 13:50:10.077  4907  5262 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,05-25 13:50:10.077  4907  5262 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,05-25 13:50:10.077  4907  5262 D BtGatt.GattService: stopScan() - queue size =1
05-25 13:50:10.077  4907  5081 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_SCAN
,05-25 13:50:10.077  3487  3980 V AlarmManager:  remove PendingIntent] PendingIntent{4948cee: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
05-25 13:50:10.077  4907  5081 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 25, currDate: 25
05-25 13:50:10.077  4907  5081 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
05-25 13:50:10.077  4907  5081 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 4 => 4
05-25 13:50:10.077  4907  4919 D BtGatt.GattService: unregisterClient() - clientIf=7
,05-25 13:50:10.077  4907  5081 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, A time : 4 => 4
05-25 13:50:10.077  4907  5081 D BtGatt.GattService: [GSIM LOG]: remove : com.thaliproject.thalitest at  BLE_SCAN_ACTUAL_DB
05-25 13:50:10.077  4907  5081 D BtGatt.GattService: [GSIM LOG]: remove : com.thaliproject.thalitest at  BLE_SCAN_REQUESTED_DB
05-25 13:50:10.077  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
05-25 13:50:10.077  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:50:10.077  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
05-25 13:50:10.077  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:10.077  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
05-25 13:50:10.077  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:10.077  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:10.077  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,05-25 13:50:10.077  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
05-25 13:50:10.077  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 25730
05-25 13:50:10.077  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=25730, mManufacturerData=null, mManufacturerDataMask=null]
05-25 13:50:10.077  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:10.077  9844  9908 D BluetoothLeScanner: Start Scan
05-25 13:50:10.087  9844  9908 D BluetoothAdapter: STATE_ON
05-25 13:50:10.087  9844  9908 D BluetoothAdapter: STATE_ON
05-25 13:50:10.087  4907  5073 D BtGatt.ScanManager: filter size is 1
,05-25 13:50:10.087  4907  5073 D BtGatt.ScanManager: delete FilterIndex - 3
05-25 13:50:10.087  4907  5037 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=32
,05-25 13:50:10.087  4907  5037 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
05-25 13:50:10.087  4907  5073 D BtGatt.ScanManager: stopping BLe Batch
,05-25 13:50:10.087  3487  3980 V AlarmManager:  remove PendingIntent] PendingIntent{444b58f: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.087  9844  9908 D BluetoothAdapter: STATE_ON
05-25 13:50:10.097  4907  5037 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=0
05-25 13:50:10.097  4907  5037 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
05-25 13:50:10.097  4907  5073 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,05-25 13:50:10.097  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:50:10.097  4907  5037 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=0
05-25 13:50:10.097  4907  5037 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
05-25 13:50:10.097  3487  3854 V AlarmManager:  remove PendingIntent] PendingIntent{c2d101c: PendingIntentRecord{6fca266 com.android.bluetooth broadcastIntent}}
05-25 13:50:10.097  4907  4918 D BtGatt.GattService: registerClient() - UUID=cbee6d33-5c82-4700-a290-f34be41b6f40
,05-25 13:50:10.097  3487  4417 V AlarmManager:  remove PendingIntent] PendingIntent{bc09425: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.097  3487  3985 V AlarmManager:  remove PendingIntent] PendingIntent{7c089fa: PendingIntentRecord{6fca266 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.107  3487  4196 V AlarmManager:  remove PendingIntent] PendingIntent{8611bab: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.107  3487  3980 V AlarmManager:  remove PendingIntent] PendingIntent{9091208: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.117  3487  4947 V AlarmManager:  remove PendingIntent] PendingIntent{68b4da1: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.117  3487  3505 V AlarmManager:  remove PendingIntent] PendingIntent{67d4bc6: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.127  3487  4417 V AlarmManager:  remove PendingIntent] PendingIntent{193c787: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.127  3487  4670 V AlarmManager:  remove PendingIntent] PendingIntent{c2146b4: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.127  3487  4927 V AlarmManager:  remove PendingIntent] PendingIntent{ee22dd: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.137  3487  4197 V AlarmManager:  remove PendingIntent] PendingIntent{7f25e52: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.137  4907  5037 D BtGatt.GattService: onClientRegistered() - UUID=cbee6d33-5c82-4700-a290-f34be41b6f40, clientIf=7
05-25 13:50:10.137  9844  9855 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=7
05-25 13:50:10.137  4907  9972 D BtGatt.GattService: start scan with filters
,05-25 13:50:10.147  4907  9972 D BtGatt.GattService: getScanSettings
,05-25 13:50:10.147  4907  9972 D BtGatt.GattService: Is it foreground application = true
05-25 13:50:10.147  4907  9972 D BtGatt.GattService: not a background application
,05-25 13:50:10.147  4907  9972 D BtGatt.GattService: [GSIM LOG]: getActualScanMode (2/100 vs -2147483648/0)
,05-25 13:50:10.147  4907  9972 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,05-25 13:50:10.147  4907  9972 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
05-25 13:50:10.157  4907  5081 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_SCAN
05-25 13:50:10.157  4907  5081 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 25, currDate: 25
05-25 13:50:10.157  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,05-25 13:50:10.157  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:10.157  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
05-25 13:50:10.157  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:50:10.157  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner started = true Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:10.157  9844  9844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
05-25 13:50:10.157  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
05-25 13:50:10.157  9844  9908 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
05-25 13:50:10.157  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
05-25 13:50:10.157  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
05-25 13:50:10.157  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
05-25 13:50:10.157  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
05-25 13:50:10.157  9844  9908 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
05-25 13:50:10.157  9844  9908 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
05-25 13:50:10.157  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
05-25 13:50:10.157  4907  5073 D BtGatt.ScanManager: handling starting scan
05-25 13:50:10.157  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
05-25 13:50:10.157  9844  9908 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
05-25 13:50:10.157  9844  9908 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
05-25 13:50:10.157  9844  9908 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
05-25 13:50:10.157  9844  9908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
05-25 13:50:10.157  9844  9908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
05-25 13:50:10.157  9844  9844 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
05-25 13:50:10.157  4907  5073 D BluetoothAdapter: STATE_ON
,05-25 13:50:10.157  9844 10328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
05-25 13:50:10.157  9844 10328 D BluetoothSocket: bindListen(): myUserId = 0
,05-25 13:50:10.157  9844 10328 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
05-25 13:50:10.157  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,05-25 13:50:10.157  9844  9908 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
05-25 13:50:10.167  4907  5073 D BluetoothAdapter: STATE_ON
05-25 13:50:10.167  4907  5081 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.thaliproject.thalitest : 19
05-25 13:50:10.167  4907  5081 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.thaliproject.thalitest, com.thaliproject.thalitest
,05-25 13:50:10.167  9844 10328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
,05-25 13:50:10.167  9844 10328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@f73819f, port: 6, type: 1, local socket address: null, socket type: 0
05-25 13:50:10.167  4907  5037 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
05-25 13:50:10.167  3487  4197 V AlarmManager:  remove PendingIntent] PendingIntent{5b5523: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
05-25 13:50:10.167  4907  5037 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,05-25 13:50:10.167  4907  5073 D BtGatt.ScanManager: set filter index= 4 for clientIf= 7
05-25 13:50:10.167  4907  5073 D BtGatt.ScanManager: High Rssi Filter value is = -128
,05-25 13:50:10.167  4907  5073 D BtGatt.ScanManager: Low Rssi Filter value is = -128
,05-25 13:50:10.167  4907  5073 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =2
05-25 13:50:10.167  9844  9908 D BluetoothAdapter: STATE_ON
05-25 13:50:10.177  4907  5037 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=31
05-25 13:50:10.177  4907  5037 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,05-25 13:50:10.177  4907  5081 D BtGatt.GattService: [GSIM LOG]: increaseScanCount 4 Battery : com.thaliproject.thalitest : 2
05-25 13:50:10.177  4907  5073 D BtGatt.ScanManager: Starting BLE batch scan
05-25 13:50:10.177  4907  5073 D BtGatt.ScanManager: configuring batch scan storage, appIf 7
,05-25 13:50:10.177  4907  5081 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.thaliproject.thalitest : 24928550
05-25 13:50:10.177  4907  5081 D BtGatt.GattService: [GSIM LOG]: setRequestedScanType : com.thaliproject.thalitest : 2
05-25 13:50:10.177  4907  5081 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.thaliproject.thalitest : 2
05-25 13:50:10.177  4907  5081 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
,05-25 13:50:10.177  4907  5081 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 4 => 4
05-25 13:50:10.177  4907  5081 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, A time : 4 => 4
05-25 13:50:10.177  3487  3980 V AlarmManager:  remove PendingIntent] PendingIntent{6e61a20: PendingIntentRecord{6fca266 com.android.bluetooth broadcastIntent}}
05-25 13:50:10.177  4907  5081 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
,05-25 13:50:10.177  4907  5081 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 4 => 4
05-25 13:50:10.177  4907  5081 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, A time : 4 => 4
05-25 13:50:10.177  4907  5081 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.thaliproject.thalitest : 2
05-25 13:50:10.177  4907  5081 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
05-25 13:50:10.177  4907  5081 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 4 => 4
,05-25 13:50:10.177  9844  9908 D BluetoothAdapter: STATE_ON
05-25 13:50:10.177  4907  5081 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, A time : 4 => 4
05-25 13:50:10.177  4907  5081 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.thaliproject.thalitest : 24928550
05-25 13:50:10.177  4907  5037 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=7, status=0
,05-25 13:50:10.187  3487  3505 V AlarmManager:  remove PendingIntent] PendingIntent{af0fd9: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
05-25 13:50:10.177  4907  5037 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
05-25 13:50:10.177  4907  5037 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=1
05-25 13:50:10.177  4907  5037 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,05-25 13:50:10.177  9844  9908 D BluetoothAdapter: STATE_ON
05-25 13:50:10.177  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:50:10.187  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:50:10.187  3487  3506 V AlarmManager:  remove PendingIntent] PendingIntent{c340d9e: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.197  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser : Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:50:10.197  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:10.197  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:10.197  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,05-25 13:50:10.197  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
05-25 13:50:10.197  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "1e0175e0-0d83-4d02-aa60-d3c622da762e", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
05-25 13:50:10.197  9844  9908 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 A8 81 95 E9 5F 6F
05-25 13:50:10.197  9844  9908 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[5, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,05-25 13:50:10.197  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[5, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-25 13:50:10.197  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:10.197  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[5, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:50:10.197  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
05-25 13:50:10.197  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[5, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-25 13:50:10.197  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:10.197  3487  4417 V AlarmManager:  remove PendingIntent] PendingIntent{484207f: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
05-25 13:50:10.197  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:10.197  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[5, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:50:10.197  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:50:10.197  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:50:10.197  9844  9908 D BluetoothLeAdvertiser: start advertising
05-25 13:50:10.197  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:50:10.207  3487  4407 V AlarmManager:  remove PendingIntent] PendingIntent{f62b84c: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.207  4907  9972 D BtGatt.GattService: registerClient() - UUID=4b2d6e5c-38ff-4cc4-8658-f15517c4ef13
,05-25 13:50:10.207  3487  4197 V AlarmManager:  remove PendingIntent] PendingIntent{7f7d095: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.217  3487  3854 V AlarmManager:  remove PendingIntent] PendingIntent{e4f65aa: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.217  3487  4947 V AlarmManager:  remove PendingIntent] PendingIntent{444459b: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.217  3487  4407 V AlarmManager:  remove PendingIntent] PendingIntent{f290d38: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.227  3487  3985 V AlarmManager:  remove PendingIntent] PendingIntent{7d1e111: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.227  3487  4671 V AlarmManager:  remove PendingIntent] PendingIntent{b163276: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.237  3487  4417 V AlarmManager:  remove PendingIntent] PendingIntent{917a077: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.237  3487  3980 V AlarmManager:  remove PendingIntent] PendingIntent{4fdc4e4: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.247  3487  4065 V AlarmManager:  remove PendingIntent] PendingIntent{e627d4d: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.247  4907  5037 D BtGatt.GattService: onClientRegistered() - UUID=4b2d6e5c-38ff-4cc4-8658-f15517c4ef13, clientIf=8
,05-25 13:50:10.247  9844  9854 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=8
,05-25 13:50:10.247  4907  4918 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,05-25 13:50:10.257  4907  4918 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
05-25 13:50:10.257  4907  4918 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,05-25 13:50:10.257  4907  5071 D BtGatt.AdvertiseManager: message : 0
05-25 13:50:10.257  4907  5081 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
05-25 13:50:10.257  4907  5081 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 25, currDate: 25
05-25 13:50:10.257  4907  5071 D BtGatt.AdvertiseManager: number of adv instance running = 0
05-25 13:50:10.257  4907  5071 D BtGatt.AdvertiseManager: size of list is =0
,05-25 13:50:10.257  4907  5071 D BtGatt.AdvertiseManager: starting advertising
,05-25 13:50:10.257  4907  5071 D BtGatt.AdvertiseManager: isStandardAdv = false
,05-25 13:50:10.267  4907  5081 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.thaliproject.thalitest : 32
,05-25 13:50:10.267  4907  5081 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.thaliproject.thalitest@LowLatency : 24928550
05-25 13:50:10.267  4907  5081 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.thaliproject.thalitest@LowLatency : 2
05-25 13:50:10.267  4907  5081 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
05-25 13:50:10.267  4907  5081 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 4 => 4
05-25 13:50:10.267  3487  4947 V AlarmManager:  remove PendingIntent] PendingIntent{8ab0002: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.267  4907  5037 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=8, status=0
,05-25 13:50:10.267  4907  5071 D BtGatt.AdvertiseManager: starting multi advertising
,05-25 13:50:10.267  4907  5037 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=8, status=0
,05-25 13:50:10.267  4907  5071 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
05-25 13:50:10.267  4907  5071 D BtGatt.AdvertiseManager: clientIf: 8, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
05-25 13:50:10.267  3487  4670 V AlarmManager:  remove PendingIntent] PendingIntent{e5bcd13: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
05-25 13:50:10.267  4907  5071 D BtGatt.AdvertiseManager: postCallback clientIf = 8 status = 0
05-25 13:50:10.267  4907  5071 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=8, status=0, isStart=true
05-25 13:50:10.267  9844  9855 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
05-25 13:50:10.267  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:10.267  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:10.267  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
05-25 13:50:10.267  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:10.267  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:10.267  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:10.267  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:10.267  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:10.267  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: advertiser is started. Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:10.267  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:10.267  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:10.267  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
05-25 13:50:10.267  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: adv = true, disc = true
05-25 13:50:10.267  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,05-25 13:50:10.277  9844  9908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,05-25 13:50:10.277  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:50:10.277  3487  3505 V AlarmManager:  remove PendingIntent] PendingIntent{5444b50: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.277  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:10.277  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:10.277  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:50:10.277  9844  9844 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
05-25 13:50:10.277  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
05-25 13:50:10.277  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
05-25 13:50:10.277  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
05-25 13:50:10.277  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
,05-25 13:50:10.277  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
05-25 13:50:10.277  9844  9844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
05-25 13:50:10.277  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
05-25 13:50:10.277  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
05-25 13:50:10.277  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
05-25 13:50:10.277  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
05-25 13:50:10.277  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]Current thread: Thread[main,5,main], id: 1
,05-25 13:50:10.277  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
05-25 13:50:10.277  9844  9844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING] Current thread: Thread[main,5,main], id: 1
05-25 13:50:10.277  9844  9844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,05-25 13:50:10.287  3487  4196 V AlarmManager:  remove PendingIntent] PendingIntent{ce6a149: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.287  9844  9844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,05-25 13:50:10.287  9844  9844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
05-25 13:50:10.287  9844  9844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
05-25 13:50:10.287  9844  9844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
05-25 13:50:10.287  9844  9844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,05-25 13:50:10.287  3487  4065 V AlarmManager:  remove PendingIntent] PendingIntent{acd1a4e: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.297  3487  4671 V AlarmManager:  remove PendingIntent] PendingIntent{dac276f: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.297  3487  3506 V AlarmManager:  remove PendingIntent] PendingIntent{52acc7c: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.297  3487  3980 V AlarmManager:  remove PendingIntent] PendingIntent{16f0905: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.787  9844  9844 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
,05-25 13:50:10.787  9844  9844 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
05-25 13:50:10.787  9844  9844 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,05-25 13:50:11.187  3487  3817 V AlarmManager: Expired Alarm result :4
,05-25 13:50:11.187  4907  4907 D BtGatt.ScanManager: awakened up at time 231775
,05-25 13:50:11.187  4907  5073 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,05-25 13:50:11.197  3487  4408 V AlarmManager:  remove PendingIntent] PendingIntent{4fdcb8b: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}},
,05-25 13:50:11.197  4907  5037 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=1
,05-25 13:50:11.197  4907  5037 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,05-25 13:50:11.197  4907  5037 D BtGatt.GattService: current time is 231783466871
05-25 13:50:11.197  4907  5037 D BtGatt.GattService: Batch record : [-47, 77, 96, -42, -16, 109, 1, -128, -63, 0, 0, 29, 17, 7, 46, 118, -38, 34, -58, -45, 96, -86, 2, 77, -125, 13, -32, 117, 1, 30, 10, 22, -32, 117, 5, 68, 120, 62, -108, 44, -26, 0]
05-25 13:50:11.197  3487  4670 V AlarmManager:  remove PendingIntent] PendingIntent{c963468: PendingIntentRecord{6fca266 com.android.bluetooth broadcastIntent}}
05-25 13:50:11.197  4907  5037 D BtGatt.GattService: ScanRecord : [17, 7, 46, 118, -38, 34, -58, -45, 96, -86, 2, 77, -125, 13, -32, 117, 1, 30, 10, 22, -32, 117, 5, 68, 120, 62, -108, 44, -26]
,05-25 13:50:11.197  4907  5037 D ScanRecord: parseFromBytes
,05-25 13:50:11.207  9844  9854 D ScanRecord: parseFromBytes
,05-25 13:50:11.207  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=6D:F0:D6:60:4D:D1, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={000075e0-0000-1000-8000-00805f9b34fb=[5, 68, 120, 62, -108, 44, -26]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-63, mTimestampNanos=231784279256}
,05-25 13:50:11.207  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = 44:78:3E:94:2C:E6, provideBluetoothMacAddressRequestId = nullextra info = 5]
,05-25 13:50:11.207  9844  9844 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: Resolved advertisement type: ADVERTISEMENT_PEER_PROPERTIES
05-25 13:50:11.217  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: Parsed advertisment: [UUID = 1e0175e0-0d83-4d02-aa60-d3c622da762e, bluetoothMacAddress = 44:78:3E:94:2C:E6, provideBluetoothMacAddressRequestId = nullextra info = 5]
05-25 13:50:11.217  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult onPeerDiscovered [44:78:3E:94:2C:E6 5]
05-25 13:50:11.217  9844  9844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onPeerDiscovered: [44:78:3E:94:2C:E6 5]
05-25 13:50:11.217  9844  9844 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: [44:78:3E:94:2C:E6 5]
05-25 13:50:11.217  9844  9844 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: Want to call onPeerAdded. Listeners size = 1
05-25 13:50:11.217  9844  9844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onPeerAdded: [44:78:3E:94:2C:E6 5]
,05-25 13:50:11.217  9844  9844 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [44:78:3E:94:2C:E6 5], added - the peer count is 1
05-25 13:50:11.217  9844  9844 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [44:78:3E:94:2C:E6 5], Bluetooth address: 44:78:3E:94:2C:E6, device name: 'null', device address: 'null'
05-25 13:50:11.217  3487  4927 V AlarmManager:  remove PendingIntent] PendingIntent{5c3081: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:11.217  3487  3505 V AlarmManager:  remove PendingIntent] PendingIntent{2ce2526: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:11.227  3487  3854 V AlarmManager:  remove PendingIntent] PendingIntent{27b9567: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:11.237  3487  4947 V AlarmManager:  remove PendingIntent] PendingIntent{ace2f14: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:11.237  3487  4196 V AlarmManager:  remove PendingIntent] PendingIntent{99a53bd: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:12.197  3487  3817 V AlarmManager: Expired Alarm result :4
,05-25 13:50:12.207  4907  4907 D BtGatt.ScanManager: awakened up at time 232792
,05-25 13:50:12.207  4907  5073 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,05-25 13:50:12.207  3487  3854 V AlarmManager:  remove PendingIntent] PendingIntent{2222103: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:12.217  4907  5037 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=1
,05-25 13:50:12.217  4907  5037 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
05-25 13:50:12.217  4907  5037 D BtGatt.GattService: current time is 232807912755
,05-25 13:50:12.217  4907  5037 D BtGatt.GattService: Batch record : [-47, 77, 96, -42, -16, 109, 1, -128, -63, 10, 0, 29, 17, 7, 46, 118, -38, 34, -58, -45, 96, -86, 2, 77, -125, 13, -32, 117, 1, 30, 10, 22, -32, 117, 5, 68, 120, 62, -108, 44, -26, 0]
05-25 13:50:12.217  3487  4407 V AlarmManager:  remove PendingIntent] PendingIntent{9e92880: PendingIntentRecord{6fca266 com.android.bluetooth broadcastIntent}}
05-25 13:50:12.217  4907  5037 D BtGatt.GattService: ScanRecord : [17, 7, 46, 118, -38, 34, -58, -45, 96, -86, 2, 77, -125, 13, -32, 117, 1, 30, 10, 22, -32, 117, 5, 68, 120, 62, -108, 44, -26]
05-25 13:50:12.217  4907  5037 D ScanRecord: parseFromBytes
05-25 13:50:12.227  9844  9854 D ScanRecord: parseFromBytes
05-25 13:50:12.227  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=6D:F0:D6:60:4D:D1, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={000075e0-0000-1000-8000-00805f9b34fb=[5, 68, 120, 62, -108, 44, -26]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-63, mTimestampNanos=232308241332}
05-25 13:50:12.227  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = 44:78:3E:94:2C:E6, provideBluetoothMacAddressRequestId = nullextra info = 5]
05-25 13:50:12.227  9844  9844 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: Resolved advertisement type: ADVERTISEMENT_PEER_PROPERTIES
,05-25 13:50:12.227  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: Parsed advertisment: [UUID = 1e0175e0-0d83-4d02-aa60-d3c622da762e, bluetoothMacAddress = 44:78:3E:94:2C:E6, provideBluetoothMacAddressRequestId = nullextra info = 5]
05-25 13:50:12.227  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult onPeerDiscovered [44:78:3E:94:2C:E6 5]
05-25 13:50:12.227  9844  9844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onPeerDiscovered: [44:78:3E:94:2C:E6 5]
05-25 13:50:12.227  9844  9844 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: [44:78:3E:94:2C:E6 5]
,05-25 13:50:12.227  9844  9844 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: has more info: false,  extra info differs: false
05-25 13:50:12.227  9844  9844 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [44:78:3E:94:2C:E6 5] updated - the peer count is 1
,05-25 13:50:12.237  3487  4670 V AlarmManager:  remove PendingIntent] PendingIntent{59d6eb9: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:12.247  3487  3985 V AlarmManager:  remove PendingIntent] PendingIntent{7dab2fe: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:12.247  3487  4197 V AlarmManager:  remove PendingIntent] PendingIntent{91bca5f: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:12.257  3487  3505 V AlarmManager:  remove PendingIntent] PendingIntent{cf84cac: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:12.267  3487  4417 V AlarmManager:  remove PendingIntent] PendingIntent{61d3d75: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:13.227  3487  3817 V AlarmManager: Expired Alarm result :4
,05-25 13:50:13.227  4907  4907 D BtGatt.ScanManager: awakened up at time 233817
,05-25 13:50:13.237  4907  5073 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,05-25 13:50:13.237  3487  4197 V AlarmManager:  remove PendingIntent] PendingIntent{adcad7b: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:13.237  4907  5037 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=0
,05-25 13:50:13.237  4907  5037 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,05-25 13:50:13.247  3487  3506 V AlarmManager:  remove PendingIntent] PendingIntent{4f38798: PendingIntentRecord{6fca266 com.android.bluetooth broadcastIntent}}
,05-25 13:50:13.257  3487  4417 V AlarmManager:  remove PendingIntent] PendingIntent{6913bf1: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:13.267  3487  4947 V AlarmManager:  remove PendingIntent] PendingIntent{98023d6: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:13.287  9844  9908 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,05-25 13:50:13.287  9844  9908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
05-25 13:50:13.287  9844  9908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
05-25 13:50:13.287  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
05-25 13:50:13.287  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,05-25 13:50:13.287  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
05-25 13:50:13.287  9844  9908 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
05-25 13:50:13.287  9844  9908 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
05-25 13:50:13.287  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
05-25 13:50:13.287  9844  9908 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56e5dc1 removed from the list
05-25 13:50:13.287  9844  9844 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,05-25 13:50:13.287  9844  9908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56e5dc1 removed from the list
05-25 13:50:13.287  9844  9908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
05-25 13:50:13.287  9844  9908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
05-25 13:50:13.287  9844 10328 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
05-25 13:50:13.287  9844 10328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
05-25 13:50:13.287  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:50:13.287  9844 10328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
05-25 13:50:13.287  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,05-25 13:50:13.287  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
05-25 13:50:13.287  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:13.287  9844  9844 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
05-25 13:50:13.287  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:50:13.287  9844  9844 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
05-25 13:50:13.287  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:13.287  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
05-25 13:50:13.287  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:13.287  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:50:13.287  9844  9908 D BluetoothAdapter: STATE_ON
05-25 13:50:13.287  4907  5262 D BtGatt.GattService: flushPendingBatchResults - clientIf=7, isServer=false
05-25 13:50:13.287  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,05-25 13:50:13.287  4907  5073 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
05-25 13:50:13.287  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:50:13.297  9844  9908 D BluetoothAdapter: STATE_ON
05-25 13:50:13.297  3487  4197 V AlarmManager:  remove PendingIntent] PendingIntent{3fea657: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:13.297  9844  9908 D BluetoothLeScanner: Stop Scan
05-25 13:50:13.297  4907  5037 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=0
05-25 13:50:13.297  4907  5037 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,05-25 13:50:13.297  3487  3854 V AlarmManager:  remove PendingIntent] PendingIntent{8658544: PendingIntentRecord{6fca266 com.android.bluetooth broadcastIntent}}
,05-25 13:50:13.297  4907  5370 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
05-25 13:50:13.297  4907  5370 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
05-25 13:50:13.297  4907  5370 D BtGatt.GattService: stopScan() - queue size =1
05-25 13:50:13.297  4907  5081 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_SCAN
05-25 13:50:13.297  4907  5081 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 25, currDate: 25
05-25 13:50:13.297  4907  5081 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
,05-25 13:50:13.297  4907  5081 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 4 => 4
05-25 13:50:13.297  4907  5081 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, A time : 4 => 4
05-25 13:50:13.297  4907  5081 D BtGatt.GattService: [GSIM LOG]: remove : com.thaliproject.thalitest at  BLE_SCAN_ACTUAL_DB
05-25 13:50:13.297  4907  5081 D BtGatt.GattService: [GSIM LOG]: remove : com.thaliproject.thalitest at  BLE_SCAN_REQUESTED_DB
,05-25 13:50:13.297  4907  5262 D BtGatt.GattService: unregisterClient() - clientIf=7
,05-25 13:50:13.297  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
05-25 13:50:13.297  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:13.297  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,05-25 13:50:13.297  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:13.297  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:50:13.297  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:50:13.297  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
05-25 13:50:13.307  3487  3985 V AlarmManager:  remove PendingIntent] PendingIntent{86ca62d: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
05-25 13:50:13.307  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:13.307  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:50:13.307  9844  9908 D BluetoothAdapter: STATE_ON
05-25 13:50:13.307  9844  9908 D BluetoothLeAdvertiser: stop advertising
05-25 13:50:13.307  4907  5073 D BtGatt.ScanManager: filter size is 1
05-25 13:50:13.307  4907  5073 D BtGatt.ScanManager: delete FilterIndex - 4
05-25 13:50:13.307  4907  5037 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=32
05-25 13:50:13.307  4907  5037 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,05-25 13:50:13.307  4907  5073 D BtGatt.ScanManager: stopping BLe Batch
,05-25 13:50:13.307  4907  4918 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,05-25 13:50:13.307  4907  4918 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
05-25 13:50:13.307  4907  5071 D BtGatt.AdvertiseManager: message : 1
,05-25 13:50:13.307  4907  5081 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
05-25 13:50:13.307  4907  5081 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 25, currDate: 25
,05-25 13:50:13.307  4907  5081 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
05-25 13:50:13.307  4907  5081 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 4 => 4
,05-25 13:50:13.307  4907  5081 D BtGatt.GattService: [GSIM LOG]: remove : com.thaliproject.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
05-25 13:50:13.307  4907  5071 D BtGatt.AdvertiseManager: stop advertise for client =  8
05-25 13:50:13.307  4907  5071 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 8
05-25 13:50:13.317  4907  5071 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
05-25 13:50:13.317  4907  5037 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=0
05-25 13:50:13.317  4907  5037 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
05-25 13:50:13.317  4907  5073 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,05-25 13:50:13.317  3487  4407 V AlarmManager:  remove PendingIntent] PendingIntent{4b2a762: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:13.317  3487  4196 V AlarmManager:  remove PendingIntent] PendingIntent{6dd50f3: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:13.327  4907  5037 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=8, status=0
,05-25 13:50:13.327  4907  5037 D BtGatt.GattService: Client app is not null!
05-25 13:50:13.327  9844  9855 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,05-25 13:50:13.327  4907  5037 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=0
,05-25 13:50:13.327  3487  3985 V AlarmManager:  remove PendingIntent] PendingIntent{9d7b1b0: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
05-25 13:50:13.327  4907  5037 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
05-25 13:50:13.327  3487  4927 V AlarmManager:  remove PendingIntent] PendingIntent{71a7829: PendingIntentRecord{6fca266 com.android.bluetooth broadcastIntent}}
05-25 13:50:13.327  4907  9972 D BtGatt.GattService: unregisterClient() - clientIf=8
05-25 13:50:13.327  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,05-25 13:50:13.327  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:13.327  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
05-25 13:50:13.327  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:13.327  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:13.327  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:13.327  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,05-25 13:50:13.327  9844  9908 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
05-25 13:50:13.327  3487  4417 V AlarmManager:  remove PendingIntent] PendingIntent{f97d7ae: PendingIntentRecord{6fca266 com.android.bluetooth broadcastIntent}}
,05-25 13:50:13.327  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,05-25 13:50:13.327  9844  9908 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
05-25 13:50:13.327  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:50:13.337  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:13.337  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
05-25 13:50:13.337  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:50:13.337  3487  4196 V AlarmManager:  remove PendingIntent] PendingIntent{5f2094f: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
05-25 13:50:13.337  9844  9908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-138,7,main], id: 138,
05-25 13:50:13.337  9844  9908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d4e966 removed from the list
05-25 13:50:13.337  9844  9844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
05-25 13:50:13.337  9844  9908 D io.jxcore.node.ConnectivityMonitor: stop
,05-25 13:50:13.337  9844  9908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
05-25 13:50:13.337  9844  9908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
05-25 13:50:13.337  9844  9844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
05-25 13:50:13.337  9844  9844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,05-25 13:50:13.337  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
05-25 13:50:13.337  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
05-25 13:50:13.337  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
05-25 13:50:13.337  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
05-25 13:50:13.337  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
05-25 13:50:13.337  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,05-25 13:50:13.337  9844  9844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
05-25 13:50:13.337  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
05-25 13:50:13.337  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
05-25 13:50:13.337  3487  3506 V AlarmManager:  remove PendingIntent] PendingIntent{8fe38dc: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
05-25 13:50:13.337  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
05-25 13:50:13.337  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
05-25 13:50:13.337  9844  9844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,05-25 13:50:13.337  9844  9844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
05-25 13:50:13.337  9844  9908 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
05-25 13:50:13.337  9844  9908 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
05-25 13:50:13.337  9844  9908 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
05-25 13:50:13.337  9844  9908 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
05-25 13:50:13.337  9844  9908 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
05-25 13:50:13.337  9844  9908 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
05-25 13:50:13.337  9844  9908 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
05-25 13:50:13.337  9844  9908 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
05-25 13:50:13.337  9844  9908 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
05-25 13:50:13.337  9844  9908 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
05-25 13:50:13.337  9844  9908 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
05-25 13:50:13.337  9844  9908 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
,05-25 13:50:13.337  9844  9908 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
05-25 13:50:13.337  3487  4927 V AlarmManager:  remove PendingIntent] PendingIntent{fb96de5: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
05-25 13:50:13.347  9844  9908 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
,05-25 13:50:13.347  9844  9908 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,05-25 13:50:13.347  3487  3980 V AlarmManager:  remove PendingIntent] PendingIntent{58dc0ba: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:13.347  3487  4408 V AlarmManager:  remove PendingIntent] PendingIntent{7efeb6b: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:13.357  3487  3505 V AlarmManager:  remove PendingIntent] PendingIntent{aa406c8: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:13.357  3487  4670 V AlarmManager:  remove PendingIntent] PendingIntent{8980361: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:13.357  3487  3985 V AlarmManager:  remove PendingIntent] PendingIntent{7c72e86: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:13.367  3487  4920 V AlarmManager:  remove PendingIntent] PendingIntent{19fd347: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:13.367  3487  4417 V AlarmManager:  remove PendingIntent] PendingIntent{356c774: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:13.367  3487  3854 V AlarmManager:  remove PendingIntent] PendingIntent{470749d: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:13.377  3487  4671 V AlarmManager:  remove PendingIntent] PendingIntent{5d7ad12: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:13.377  3487  4065 V AlarmManager:  remove PendingIntent] PendingIntent{17c5ce3: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:13.377  3487  4197 V AlarmManager:  remove PendingIntent] PendingIntent{d2e6e0: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:13.387  3487  4947 V AlarmManager:  remove PendingIntent] PendingIntent{d64bd99: PendingIntentRecord{7aaf958 com.android.bluetooth broadcastIntent}}
,05-25 13:50:13.667  3487  3604 D PowerManagerService: [s] UserActivityState : 1 -> 2
,05-25 13:50:13.667  3487  3604 D PowerManagerService: mDisplayReady: false
,05-25 13:50:13.667  3487  3604 D DisplayPowerController: animateScreenStateChange[0]: target=2
05-25 13:50:13.667  3487  3604 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
05-25 13:50:13.667  3487  3604 D DisplayPowerController: getFinalBrightness : Summary is 30 -> 30
05-25 13:50:13.667  3487  3604 D DisplayPowerController: Animating brightness: target=30, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,05-25 13:50:13.667  3487  3604 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
05-25 13:50:13.667  3487  3604 D PowerManagerService: mDisplayReady: true
,05-25 13:50:13.677  3487  3905 D lights  : lcd : 36 +
,05-25 13:50:13.677  3487  3905 D lights  : lcd : 36 -
,05-25 13:50:13.677  3487  3604 D DisplayPowerController: animateScreenStateChange[0]: target=2
05-25 13:50:13.677  3487  3604 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
,05-25 13:50:13.677  3487  3604 D DisplayPowerController: getFinalBrightness : Summary is 30 -> 30
05-25 13:50:13.677  3487  3604 D DisplayPowerController: Animating brightness: target=30, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,05-25 13:50:13.687  3487  3905 D lights  : lcd : 30 +
,05-25 13:50:13.687  3487  3604 D DisplayPowerController: animateScreenStateChange[0]: target=2
05-25 13:50:13.687  3487  3604 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
05-25 13:50:13.687  3487  3604 D DisplayPowerController: getFinalBrightness : Summary is 30 -> 30
,05-25 13:50:13.687  3487  3604 D DisplayPowerController: Animating brightness: target=30, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
05-25 13:50:13.687  3487  3905 D lights  : lcd : 30 -
,05-25 13:50:13.697  3487  3604 D DisplayPowerController: animateScreenStateChange[0]: target=2
05-25 13:50:13.697  3487  3604 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
05-25 13:50:13.697  3487  3604 D DisplayPowerController: getFinalBrightness : Summary is 30 -> 30
,05-25 13:50:13.697  3487  3604 D DisplayPowerController: Animating brightness: target=30, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,05-25 13:50:13.837  9844  9844 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,05-25 13:50:14.077  3487  4671 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-25 13:50:14.077  3487  4671 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4349, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:50:14.077  3487  4671 D BatteryService: online:4, current avg:137, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:191
05-25 13:50:14.077  3487  3487 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:50:14.077  3487  3487 I MotionRecognitionService: Plugged
,05-25 13:50:14.077  3487  3487 D MotionRecognitionService:   cableConnection= 1
05-25 13:50:14.077  3487  3487 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:50:14.077  3487  3487 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:50:14.087  3487  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:50:14.087  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
05-25 13:50:14.087  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
05-25 13:50:14.087  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:50:14.097  3949  3949 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
05-25 13:50:14.097  3949  3949 D PowerUI.Notification: There is no change about charging status, so return!
,05-25 13:50:14.097  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,05-25 13:50:14.107  4952  4952 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:50:14.117  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,05-25 13:50:14.127  4952  4952 D BatteryMonitor: new battery level: 100
05-25 13:50:14.127  4907  4907 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-25 13:50:14.127  4907  9949 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-25 13:50:15.157  3487  6263 D SSRM:n  : SIOP:: AP = 310, PST = 328 (W:10), CP = 270, CUR = 137, LCD = 30
,05-25 13:50:15.347  9844  9908 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,05-25 13:50:15.497  9844 10335 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 276, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:50:15.497  9844 10335 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:50:15.497  9844 10335 D io.jxcore.node.StreamCopyingThread:  id: 86
,05-25 13:50:16.287  9844 10335 W !!      : call onHalfStreamCopied
05-25 13:50:16.287  9844 10335 I testCopyDataAndClose: closing input stream
,05-25 13:50:16.977  9844 10335 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 276, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:50:16.977  9844 10335 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:50:16.977  9844 10335 D io.jxcore.node.StreamCopyingThread:  id: 86
05-25 13:50:16.977  9844 10335 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:50:16.977  9844 10335 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:50:16.977  9844 10335 D io.jxcore.node.StreamCopyingThread:  id: 86
05-25 13:50:16.977  9844 10335 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
05-25 13:50:16.977  9844 10335 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
05-25 13:50:16.977  9844 10335 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
05-25 13:50:16.977  9844 10335 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
05-25 13:50:16.977  9844 10335 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
05-25 13:50:16.977  9844 10335 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 276, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:50:16.977  9844 10335 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:50:16.977  9844 10335 D io.jxcore.node.StreamCopyingThread:  id: 86 .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,05-25 13:50:19.387  9844  9908 I StreamCopyingThreadTest: Starting test: testCopyBigData
,05-25 13:50:19.427  9844 10336 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 279, name: testCopyBigData thread). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:50:19.427  9844 10336 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:50:19.427  9844 10336 D io.jxcore.node.StreamCopyingThread:  id: 88
,05-25 13:50:19.667  3487  3604 D PowerManagerService: [s] UserActivityState : 2 -> 4
05-25 13:50:19.667  3487  3604 I PowerManagerService: [PWL] On : 0 (240255 ms ago)
05-25 13:50:19.667  3487  3604 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4
,05-25 13:50:20.937  9844 10336 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 279, thread name: testCopyBigData thread). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:50:20.937  9844 10336 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:50:20.937  9844 10336 D io.jxcore.node.StreamCopyingThread:  id: 88
05-25 13:50:20.937  9844 10336 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:50:20.937  9844 10336 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:50:20.937  9844 10336 D io.jxcore.node.StreamCopyingThread:  id: 88
05-25 13:50:20.937  9844 10336 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
05-25 13:50:20.937  9844 10336 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
05-25 13:50:20.937  9844 10336 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
05-25 13:50:20.937  9844 10336 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
05-25 13:50:20.937  9844 10336 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
05-25 13:50:20.937  9844 10336 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 279, name: testCopyBigData thread). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:50:20.937  9844 10336 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:50:20.937  9844 10336 D io.jxcore.node.StreamCopyingThread:  id: 88 .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,05-25 13:50:23.357  9844  9908 I StreamCopyingThreadTest: Starting test: testRunNotify
,05-25 13:50:23.357  9844 10337 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 281, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:50:23.357  9844 10337 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:50:23.357  9844 10337 D io.jxcore.node.StreamCopyingThread:  id: 89
05-25 13:50:23.357  9844 10337 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 281, thread name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:50:23.357  9844 10337 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:50:23.357  9844 10337 D io.jxcore.node.StreamCopyingThread:  id: 89
05-25 13:50:23.357  9844 10337 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:50:23.357  9844 10337 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:50:23.357  9844 10337 D io.jxcore.node.StreamCopyingThread:  id: 89
05-25 13:50:23.357  9844 10337 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
05-25 13:50:23.357  9844 10337 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
05-25 13:50:23.357  9844 10337 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
05-25 13:50:23.357  9844 10337 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
05-25 13:50:23.357  9844 10337 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
05-25 13:50:23.357  9844 10337 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 281, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:50:23.357  9844 10337 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:50:23.357  9844 10337 D io.jxcore.node.StreamCopyingThread:  id: 89 .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
05-25 13:50:23.357  9844  9908 I StreamCopyingThreadTest: Starting test: testSetBufferSize
05-25 13:50:23.357  9844  9908 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-25 13:50:23.357  9844  9908 I StreamCopyingThreadTest: Starting test: testRunWithException
05-25 13:50:23.357  9844 10338 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 285, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:50:23.357  9844 10338 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:50:23.357  9844 10338 D io.jxcore.node.StreamCopyingThread:  id: 92
05-25 13:50:23.357  9844 10338 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 285, thread name: My test thread name): Test exception.
05-25 13:50:23.357  9844 10338 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 285, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:50:23.357  9844 10338 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:50:23.357  9844 10338 D io.jxcore.node.StreamCopyingThread:  id: 92 .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
05-25 13:50:23.357  9844 10338 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
05-25 13:50:23.357  9844 10338 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 285, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:50:23.357  9844 10338 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:50:23.357  9844 10338 D io.jxcore.node.StreamCopyingThread:  id: 92 .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
05-25 13:50:23.357  9844  9908 I jxcore-log: 2017-05-25 11:50:23 - DEBUG UnitTest_app: 'Running unit tests'
05-25 13:50:23.357  9844  9908 I jxcore-log: 
05-25 13:50:23.357  9844  9908 I jxcore-log: *Native ,tests were executed*
05-25 13:50:23.357  9844  9908 I jxcore-log: 
05-25 13:50:23.357  9844  9908 I jxcore-log: Total number of executed tests:  78
05-25 13:50:23.357  9844  9908 I jxcore-log: 
05-25 13:50:23.357  9844  9908 I jxcore-log: Number of passed tests:  76
05-25 13:50:23.357  9844  9908 I jxcore-log: 
05-25 13:50:23.357  9844  9908 I jxcore-log: Number of failed tests:  0
05-25 13:50:23.357  9844  9908 I jxcore-log: 
05-25 13:50:23.357  9844  9908 I jxcore-log: Number of ignored tests:  2
05-25 13:50:23.357  9844  9908 I jxcore-log: 
05-25 13:50:23.357  9844  9908 I jxcore-log: Total duration:  49776
05-25 13:50:23.357  9844  9908 I jxcore-log: 
05-25 13:50:23.357  9844  9908 I jxcore-log: 2017-05-25 11:50:23 - DEBUG UnitTest_app: 'My device name is: 'samsung-SM-G935F''
05-25 13:50:23.357  9844  9908 I jxcore-log: 
05-25 13:50:23.357  9844  9908 I jxcore-log: 2017-05-25 11:50:23 - WARN testUtils: 'myNameCallback not set!'
05-25 13:50:23.357  9844  9908 I jxcore-log: 
,05-25 13:50:24.127  3487  3980 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,05-25 13:50:24.127  3487  3980 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4243, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:50:24.127  3487  3980 D BatteryService: online:4, current avg:-216, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-514
05-25 13:50:24.127  3487  3487 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:50:24.127  3487  3487 I MotionRecognitionService: Plugged
,05-25 13:50:24.127  3487  3487 D MotionRecognitionService:   cableConnection= 1
05-25 13:50:24.127  3487  3487 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:50:24.127  3487  3487 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:50:24.137  3487  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:50:24.137  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,05-25 13:50:24.137  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
05-25 13:50:24.137  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:50:24.137  3949  3949 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,05-25 13:50:24.137  3949  3949 D PowerUI.Notification: There is no change about charging status, so return!
,05-25 13:50:24.147  4952  4952 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:50:24.157  4907  4907 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-25 13:50:24.157  4907  9949 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-25 13:50:24.157  4952  4952 D BatteryMonitor: new battery level: 100
,05-25 13:50:24.167  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,05-25 13:50:24.167  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,05-25 13:50:24.837  9844  9908 I jxcore-log: 2017-05-25 11:50:24 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: android'
05-25 13:50:24.837  9844  9908 I jxcore-log: 
,05-25 13:50:24.837  9844  9908 I jxcore-log: 2017-05-25 11:50:24 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
05-25 13:50:24.837  9844  9908 I jxcore-log: 
,05-25 13:50:24.847  9844  9908 I jxcore-log: 2017-05-25 11:50:24 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
05-25 13:50:24.847  9844  9908 I jxcore-log: 
,05-25 13:50:24.997  9844  9908 I jxcore-log: 2017-05-25 11:50:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
05-25 13:50:24.997  9844  9908 I jxcore-log: 
,05-25 13:50:25.027  9844  9908 I jxcore-log: 2017-05-25 11:50:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
05-25 13:50:25.027  9844  9908 I jxcore-log: 
,05-25 13:50:25.037  9844  9908 I jxcore-log: 2017-05-25 11:50:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testTests.js'
05-25 13:50:25.037  9844  9908 I jxcore-log: 
,05-25 13:50:25.077  9844  9908 I jxcore-log: 2017-05-25 11:50:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testUsn.js'
05-25 13:50:25.077  9844  9908 I jxcore-log: 
,05-25 13:50:25.087  9844  9908 I jxcore-log: 2017-05-25 11:50:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
05-25 13:50:25.087  9844  9908 I jxcore-log: 
,05-25 13:50:25.097  9844  9908 I jxcore-log: 2017-05-25 11:50:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
05-25 13:50:25.097  9844  9908 I jxcore-log: 
,05-25 13:50:25.137  9844  9908 I jxcore-log: 2017-05-25 11:50:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
05-25 13:50:25.137  9844  9908 I jxcore-log: 
,05-25 13:50:25.147  9844  9908 I jxcore-log: 2017-05-25 11:50:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
05-25 13:50:25.147  9844  9908 I jxcore-log: 
,05-25 13:50:25.157  9844  9908 I jxcore-log: 2017-05-25 11:50:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
05-25 13:50:25.157  9844  9908 I jxcore-log: 
,05-25 13:50:25.157  9844  9908 I jxcore-log: 2017-05-25 11:50:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
05-25 13:50:25.157  9844  9908 I jxcore-log: 
,05-25 13:50:25.177  3487  6263 D SSRM:n  : SIOP:: AP = 390, PST = 334 (W:6), CP = 277, CUR = -216, LCD = 30
,05-25 13:50:25.367  9844  9908 I jxcore-log: 2017-05-25 11:50:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
05-25 13:50:25.367  9844  9908 I jxcore-log: 
,05-25 13:50:25.467  9844  9908 I jxcore-log: 2017-05-25 11:50:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
05-25 13:50:25.467  9844  9908 I jxcore-log: 
,05-25 13:50:25.527  9844  9908 I jxcore-log: 2017-05-25 11:50:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
05-25 13:50:25.527  9844  9908 I jxcore-log: 
,05-25 13:50:25.547  9844  9908 I jxcore-log: 2017-05-25 11:50:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
05-25 13:50:25.547  9844  9908 I jxcore-log: 
,05-25 13:50:25.557  9844  9908 I jxcore-log: 2017-05-25 11:50:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
05-25 13:50:25.557  9844  9908 I jxcore-log: 
,05-25 13:50:25.587  9844  9908 I jxcore-log: 2017-05-25 11:50:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
05-25 13:50:25.587  9844  9908 I jxcore-log: 
,05-25 13:50:25.627  9844  9908 I jxcore-log: 2017-05-25 11:50:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
05-25 13:50:25.627  9844  9908 I jxcore-log: 
,05-25 13:50:25.657  9844  9908 I jxcore-log: 2017-05-25 11:50:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
05-25 13:50:25.657  9844  9908 I jxcore-log: 
,05-25 13:50:25.687  9844  9908 I jxcore-log: 2017-05-25 11:50:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
05-25 13:50:25.687  9844  9908 I jxcore-log: 
,05-25 13:50:25.697  9844  9908 I jxcore-log: 2017-05-25 11:50:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
05-25 13:50:25.697  9844  9908 I jxcore-log: 
,05-25 13:50:25.737  9844  9908 I jxcore-log: 2017-05-25 11:50:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
05-25 13:50:25.737  9844  9908 I jxcore-log: 
,05-25 13:50:25.767  9844  9908 I jxcore-log: 2017-05-25 11:50:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
05-25 13:50:25.767  9844  9908 I jxcore-log: 
,05-25 13:50:26.357  9844  9908 I jxcore-log: 2017-05-25 11:50:26 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
05-25 13:50:26.357  9844  9908 I jxcore-log: 
,05-25 13:50:26.377  9844  9908 I jxcore-log: 2017-05-25 11:50:26 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
05-25 13:50:26.377  9844  9908 I jxcore-log: 
,05-25 13:50:26.387  9844  9908 I jxcore-log: 2017-05-25 11:50:26 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
05-25 13:50:26.387  9844  9908 I jxcore-log: 
,05-25 13:50:26.387  9844  9908 I jxcore-log: 2017-05-25 11:50:26 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
05-25 13:50:26.387  9844  9908 I jxcore-log: 
,05-25 13:50:26.407  9844  9908 I jxcore-log: 2017-05-25 11:50:26 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
05-25 13:50:26.407  9844  9908 I jxcore-log: 
,05-25 13:50:26.427  9844  9908 I jxcore-log: 2017-05-25 11:50:26 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
05-25 13:50:26.427  9844  9908 I jxcore-log: 
,05-25 13:50:26.437  9844  9908 I jxcore-log: 2017-05-25 11:50:26 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
05-25 13:50:26.437  9844  9908 I jxcore-log: 
,05-25 13:50:26.447  9844  9908 I jxcore-log: 2017-05-25 11:50:26 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
05-25 13:50:26.447  9844  9908 I jxcore-log: 
,05-25 13:50:26.457  9844  9908 I jxcore-log: 2017-05-25 11:50:26 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
05-25 13:50:26.457  9844  9908 I jxcore-log: 
,05-25 13:50:26.457  9844  9908 I jxcore-log: 2017-05-25 11:50:26 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
05-25 13:50:26.457  9844  9908 I jxcore-log: 
,05-25 13:50:26.477  9844  9908 I jxcore-log: 2017-05-25 11:50:26 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
05-25 13:50:26.477  9844  9908 I jxcore-log: 
,05-25 13:50:26.487  9844  9908 I jxcore-log: 2017-05-25 11:50:26 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
05-25 13:50:26.487  9844  9908 I jxcore-log: 
,05-25 13:50:26.497  9844  9908 I jxcore-log: 2017-05-25 11:50:26 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
05-25 13:50:26.497  9844  9908 I jxcore-log: 
,05-25 13:50:26.587  9844  9908 I jxcore-log: 2017-05-25 11:50:26 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
05-25 13:50:26.587  9844  9908 I jxcore-log: 
,05-25 13:50:26.757  9844  9908 I jxcore-log: 2017-05-25 11:50:26 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testHttp.js'
05-25 13:50:26.757  9844  9908 I jxcore-log: 
,05-25 13:50:26.767  9844  9908 I jxcore-log: 2017-05-25 11:50:26 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testSSDPServer.js'
05-25 13:50:26.767  9844  9908 I jxcore-log: 
,05-25 13:50:26.777  9844  9908 D BluetoothAdapter: STATE_ON
,05-25 13:50:26.777  9844  9908 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,05-25 13:50:26.777  9844  9908 I jxcore-log: 2017-05-25 11:50:26 - INFO testUtils: 'BLE multiple advertisement supported'
05-25 13:50:26.777  9844  9908 I jxcore-log: 
,05-25 13:50:26.787  9844  9908 I jxcore-log: 2017-05-25 11:50:26 - DEBUG UnitTest_app: 'Unit Test app is loaded'
05-25 13:50:26.787  9844  9908 I jxcore-log: 
,05-25 13:50:26.787  9844  9908 I jxcore-log: 2017-05-25 11:50:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"NG700"}'
05-25 13:50:26.787  9844  9908 I jxcore-log: 
,05-25 13:50:26.787  9844  9908 I jxcore-log: 2017-05-25 11:50:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
05-25 13:50:26.787  9844  9908 I jxcore-log: 
05-25 13:50:26.787  9844  9908 I jxcore-log: 2017-05-25 11:50:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"NG700"}'
05-25 13:50:26.787  9844  9908 I jxcore-log: 
05-25 13:50:26.787  9844  9908 I jxcore-log: 2017-05-25 11:50:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
05-25 13:50:26.787  9844  9908 I jxcore-log: 
05-25 13:50:26.787  9844  9908 I jxcore-log: 2017-05-25 11:50:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"NG700"}'
05-25 13:50:26.787  9844  9908 I jxcore-log: 
05-25 13:50:26.787  9844  9908 I jxcore-log: 2017-05-25 11:50:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
05-25 13:50:26.787  9844  9908 I jxcore-log: 
,05-25 13:50:26.787  9844  9908 I jxcore-log: 2017-05-25 11:50:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":null,"ssidName":null}'
05-25 13:50:26.787  9844  9908 I jxcore-log: 
05-25 13:50:26.797  9844  9908 I jxcore-log: 2017-05-25 11:50:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
05-25 13:50:26.797  9844  9908 I jxcore-log: 
05-25 13:50:26.797  9844  9908 I jxcore-log: 2017-05-25 11:50:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare","bssidName":null,"ssidName":null}'
05-25 13:50:26.797  9844  9908 I jxcore-log: 
05-25 13:50:26.797  9844  9908 I jxcore-log: 2017-05-25 11:50:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
05-25 13:50:26.797  9844  9908 I jxcore-log: 
05-25 13:50:26.797  9844  9908 I jxcore-log: 2017-05-25 11:50:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":null,"ssidName":null}'
05-25 13:50:26.797  9844  9908 I jxcore-log: 
,05-25 13:50:26.797  9844  9908 I jxcore-log: 2017-05-25 11:50:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
05-25 13:50:26.797  9844  9908 I jxcore-log: 
05-25 13:50:26.797  9844  9908 I jxcore-log: 2017-05-25 11:50:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"NG700"}'
05-25 13:50:26.797  9844  9908 I jxcore-log: 
05-25 13:50:26.797  9844  9908 I jxcore-log: 2017-05-25 11:50:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
05-25 13:50:26.797  9844  9908 I jxcore-log: 
,05-25 13:50:26.797  9844  9844 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 68 : UIApp is all set and ready!
,05-25 13:50:26.797  9844  9844 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,05-25 13:50:26.827  9844  9908 I jxcore-log: 2017-05-25 11:50:26 - INFO CoordinatedClient: 'Connecting to coordination server on http://192.168.1.150:3000/'
05-25 13:50:26.827  9844  9908 I jxcore-log: 
,05-25 13:50:26.907  9844  9908 I jxcore-log: 2017-05-25 11:50:26 - DEBUG CoordinatedClient: 'connected to the test server'
05-25 13:50:26.907  9844  9908 I jxcore-log: 
,05-25 13:50:27.137  9844  9908 I jxcore-log: 2017-05-25 11:50:27 - DEBUG CoordinatedClient: 'device disconnected from the test server'
05-25 13:50:27.137  9844  9908 I jxcore-log: 
,05-25 13:50:28.987  9844  9908 I jxcore-log: 2017-05-25 11:50:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
05-25 13:50:28.987  9844  9908 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
05-25 13:50:28.987  9844  9908 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
05-25 13:50:28.987  9844  9908 I jxcore-log: emit@events.js:82:1
05-25 13:50:28.987  9844  9908 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
05-25 13:50:28.987  9844  9908 I jxcore-log: emit@events.js:82:1''
05-25 13:50:28.987  9844  9908 I jxcore-log: 
,05-25 13:50:28.987  9844  9908 I jxcore-log: 2017-05-25 11:50:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
05-25 13:50:28.987  9844  9908 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
05-25 13:50:28.987  9844  9908 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
05-25 13:50:28.987  9844  9908 I jxcore-log: emit@events.js:82:1
05-25 13:50:28.987  9844  9908 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
05-25 13:50:28.987  9844  9908 I jxcore-log: emit@events.js:82:1''
05-25 13:50:28.987  9844  9908 I jxcore-log: 
,05-25 13:50:29.727  3487  6298 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,05-25 13:50:32.107  9844  9908 I jxcore-log: 2017-05-25 11:50:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
05-25 13:50:32.107  9844  9908 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
05-25 13:50:32.107  9844  9908 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
05-25 13:50:32.107  9844  9908 I jxcore-log: emit@events.js:82:1
05-25 13:50:32.107  9844  9908 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
05-25 13:50:32.107  9844  9908 I jxcore-log: emit@events.js:82:1''
05-25 13:50:32.107  9844  9908 I jxcore-log: 
,05-25 13:50:32.107  9844  9908 I jxcore-log: 2017-05-25 11:50:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
05-25 13:50:32.107  9844  9908 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
05-25 13:50:32.107  9844  9908 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
05-25 13:50:32.107  9844  9908 I jxcore-log: emit@events.js:82:1
05-25 13:50:32.107  9844  9908 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
05-25 13:50:32.107  9844  9908 I jxcore-log: emit@events.js:82:1''
05-25 13:50:32.107  9844  9908 I jxcore-log: 
,05-25 13:50:33.047  3487  4148 E Watchdog: !@Sync 8 [05-25 13:50:33.055]
,05-25 13:50:34.177  3487  4407 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-25 13:50:34.177  3487  4407 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4342, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:50:34.177  3487  4407 D BatteryService: online:4, current avg:-71, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:185
05-25 13:50:34.177  3487  3487 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:50:34.187  3487  3487 I MotionRecognitionService: Plugged
,05-25 13:50:34.187  3487  3487 D MotionRecognitionService:   cableConnection= 1
05-25 13:50:34.187  3487  3487 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:50:34.187  3487  3487 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:50:34.197  3487  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:50:34.197  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
05-25 13:50:34.197  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
,05-25 13:50:34.197  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:50:34.197  3949  3949 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,05-25 13:50:34.197  3949  3949 D PowerUI.Notification: There is no change about charging status, so return!
,05-25 13:50:34.217  4952  4952 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:50:34.227  4907  4907 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-25 13:50:34.227  4907  9949 D HeadsetStateMachine: Disconnected process message: 10, size: 0
05-25 13:50:34.227  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
05-25 13:50:34.227  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,05-25 13:50:34.237  4952  4952 D BatteryMonitor: new battery level: 100
,05-25 13:50:34.467  4353  4435 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
05-25 13:50:34.467  4353  4435 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,05-25 13:50:35.197  3487  6263 D SSRM:n  : SIOP:: AP = 350, PST = 340 (W:14), CP = 285, CUR = -71, LCD = 30
,05-25 13:50:41.417  9844  9908 I jxcore-log: 2017-05-25 11:50:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
05-25 13:50:41.417  9844  9908 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
05-25 13:50:41.417  9844  9908 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
05-25 13:50:41.417  9844  9908 I jxcore-log: emit@events.js:82:1
05-25 13:50:41.417  9844  9908 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
05-25 13:50:41.417  9844  9908 I jxcore-log: emit@events.js:82:1''
05-25 13:50:41.417  9844  9908 I jxcore-log: 
,05-25 13:50:41.427  9844  9908 I jxcore-log: 2017-05-25 11:50:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
05-25 13:50:41.427  9844  9908 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
05-25 13:50:41.427  9844  9908 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
05-25 13:50:41.427  9844  9908 I jxcore-log: emit@events.js:82:1
05-25 13:50:41.427  9844  9908 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
05-25 13:50:41.427  9844  9908 I jxcore-log: emit@events.js:82:1''
05-25 13:50:41.427  9844  9908 I jxcore-log: 
,05-25 13:50:44.237  3487  4670 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,05-25 13:50:44.237  3487  4670 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4343, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:50:44.237  3487  4670 D BatteryService: online:4, current avg:74, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:153
05-25 13:50:44.237  3487  3487 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:50:44.247  3487  3487 I MotionRecognitionService: Plugged
,05-25 13:50:44.247  3487  3487 D MotionRecognitionService:   cableConnection= 1
05-25 13:50:44.247  3487  3487 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:50:44.247  3487  3487 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:50:44.247  3487  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:50:44.247  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
05-25 13:50:44.247  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
,05-25 13:50:44.257  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:50:44.257  3949  3949 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,05-25 13:50:44.257  3949  3949 D PowerUI.Notification: There is no change about charging status, so return!
,05-25 13:50:44.267  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,05-25 13:50:44.277  4952  4952 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:50:44.287  4907  4907 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,05-25 13:50:44.287  4907  9949 D HeadsetStateMachine: Disconnected process message: 10, size: 0
05-25 13:50:44.287  4952  4952 D BatteryMonitor: new battery level: 100
,05-25 13:50:44.297  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,05-25 13:50:45.217  3487  6263 D SSRM:n  : SIOP:: AP = 330, PST = 345 (W:14), CP = 280, CUR = 74, LCD = 30
,05-25 13:50:49.727  3487  6298 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,05-25 13:50:51.477  9844  9908 I jxcore-log: 2017-05-25 11:50:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
05-25 13:50:51.477  9844  9908 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
05-25 13:50:51.477  9844  9908 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
05-25 13:50:51.477  9844  9908 I jxcore-log: emit@events.js:82:1
05-25 13:50:51.477  9844  9908 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
05-25 13:50:51.477  9844  9908 I jxcore-log: emit@events.js:82:1''
05-25 13:50:51.477  9844  9908 I jxcore-log: 
,05-25 13:50:51.487  9844  9908 I jxcore-log: 2017-05-25 11:50:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
05-25 13:50:51.487  9844  9908 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
05-25 13:50:51.487  9844  9908 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
05-25 13:50:51.487  9844  9908 I jxcore-log: emit@events.js:82:1
05-25 13:50:51.487  9844  9908 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
05-25 13:50:51.487  9844  9908 I jxcore-log: emit@events.js:82:1''
05-25 13:50:51.487  9844  9908 I jxcore-log: 
,05-25 13:50:54.287  3487  3985 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-25 13:50:54.287  3487  3985 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4340, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:50:54.287  3487  3985 D BatteryService: online:4, current avg:129, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:109
05-25 13:50:54.287  3487  3487 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:50:54.297  3487  3487 I MotionRecognitionService: Plugged
05-25 13:50:54.297  3487  3487 D MotionRecognitionService:   cableConnection= 1
05-25 13:50:54.297  3487  3487 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:50:54.297  3487  3487 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:50:54.307  3487  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:50:54.307  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
05-25 13:50:54.307  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
,05-25 13:50:54.307  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:50:54.317  3949  3949 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,05-25 13:50:54.317  3949  3949 D PowerUI.Notification: There is no change about charging status, so return!
,05-25 13:50:54.317  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,05-25 13:50:54.327  4952  4952 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:50:54.337  4952  4952 D BatteryMonitor: new battery level: 100
05-25 13:50:54.337  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
05-25 13:50:54.337  4907  4907 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-25 13:50:54.347  4907  9949 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-25 13:50:55.247  3487  6263 D SSRM:n  : SIOP:: AP = 320, PST = 344 (W:14), CP = 274, CUR = 129, LCD = 30
,05-25 13:50:59.987  3487  3817 V AlarmManager: Expired Alarm result :8
,05-25 13:50:59.997  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
05-25 13:50:59.997  3949  3949 D KeyguardUpdateMonitor: handleTimeUpdate
,05-25 13:51:00.017  3949  3949 D Clock   : received broadcast android.intent.action.TIME_TICK
,05-25 13:51:00.067  3949  3949 D DateView: received broadcast android.intent.action.TIME_TICK
,05-25 13:51:00.097  4690  4690 D [Weather Widget]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,05-25 13:51:00.097  4690  4690 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EEFA9050249635C043F7E254E316C2550]}
,05-25 13:51:00.097  4690  4690 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EAB01DC5C99149A39F887E17599325AFBFF089086AA9902184ADA25758C536FE2]}
,05-25 13:51:00.097  4690  4690 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EFF0B905BDFF72B69FB632A6CB072B41F95D2E6F4F84443284E97F40042D431D8350388453A923ABD8469D82798FA7548]}
,05-25 13:51:00.097  4690  4690 D [Weather Widget]  : {[A1AF0F6A1A65A89C43D705938923D0FEFB71880C4E84718DA0A3E1F383E54FB27A4284D9BEDF7BAA2ABFFE671EB65C640578FF9DE16A23BFE3280A9DCDBB09A0087A09617A4D2E4C8CA19F92E92E7F081209ADB459A570E8D870EBA866E0F8996B7829FAC6D5657983C2B9D0F41D1C4D]}
,05-25 13:51:00.097  4690  4690 D [Weather Widget]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,05-25 13:51:01.547  9844  9908 I jxcore-log: 2017-05-25 11:51:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
05-25 13:51:01.547  9844  9908 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
05-25 13:51:01.547  9844  9908 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
05-25 13:51:01.547  9844  9908 I jxcore-log: emit@events.js:82:1
05-25 13:51:01.547  9844  9908 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
05-25 13:51:01.547  9844  9908 I jxcore-log: emit@events.js:82:1''
05-25 13:51:01.547  9844  9908 I jxcore-log: 
,05-25 13:51:01.557  9844  9908 I jxcore-log: 2017-05-25 11:51:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
05-25 13:51:01.557  9844  9908 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
05-25 13:51:01.557  9844  9908 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
05-25 13:51:01.557  9844  9908 I jxcore-log: emit@events.js:82:1
05-25 13:51:01.557  9844  9908 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
05-25 13:51:01.557  9844  9908 I jxcore-log: emit@events.js:82:1''
05-25 13:51:01.557  9844  9908 I jxcore-log: 
,05-25 13:51:03.047  3487  4148 E Watchdog: !@Sync 9 [05-25 13:51:03.057]
,05-25 13:51:04.347  3487  4196 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-25 13:51:04.347  3487  4196 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4350, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:51:04.347  3487  4196 D BatteryService: online:4, current avg:152, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:209
05-25 13:51:04.347  3487  3487 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:51:04.357  3487  3487 I MotionRecognitionService: Plugged
,05-25 13:51:04.357  3487  3487 D MotionRecognitionService:   cableConnection= 1
05-25 13:51:04.357  3487  3487 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:51:04.357  3487  3487 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:51:04.357  3487  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:51:04.367  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
05-25 13:51:04.367  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
,05-25 13:51:04.367  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:51:04.367  3949  3949 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,05-25 13:51:04.367  3949  3949 D PowerUI.Notification: There is no change about charging status, so return!
,05-25 13:51:04.377  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,05-25 13:51:04.387  4952  4952 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:51:04.397  4907  4907 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-25 13:51:04.397  4907  9949 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-25 13:51:04.407  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,05-25 13:51:04.407  4952  4952 D BatteryMonitor: new battery level: 100
,05-25 13:51:04.667  3487  3604 I PowerManagerService: [PWL] On : 0 (285255 ms ago)
05-25 13:51:04.667  3487  3604 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4
,05-25 13:51:05.277  3487  6263 D SSRM:n  : SIOP:: AP = 310, PST = 343 (W:14), CP = 271, CUR = 152, LCD = 30
,05-25 13:51:09.727  3487  6298 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,05-25 13:51:11.587  9844  9908 I jxcore-log: 2017-05-25 11:51:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
05-25 13:51:11.587  9844  9908 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
05-25 13:51:11.587  9844  9908 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
05-25 13:51:11.587  9844  9908 I jxcore-log: emit@events.js:82:1
05-25 13:51:11.587  9844  9908 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
05-25 13:51:11.587  9844  9908 I jxcore-log: emit@events.js:82:1''
05-25 13:51:11.587  9844  9908 I jxcore-log: 
,05-25 13:51:11.587  9844  9908 I jxcore-log: 2017-05-25 11:51:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
05-25 13:51:11.587  9844  9908 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
05-25 13:51:11.587  9844  9908 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
05-25 13:51:11.587  9844  9908 I jxcore-log: emit@events.js:82:1
05-25 13:51:11.587  9844  9908 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
05-25 13:51:11.587  9844  9908 I jxcore-log: emit@events.js:82:1''
05-25 13:51:11.587  9844  9908 I jxcore-log: 
,05-25 13:51:14.407  3487  3506 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-25 13:51:14.407  3487  3506 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4352, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:51:14.407  3487  3506 D BatteryService: online:4, current avg:168, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:247
05-25 13:51:14.407  3487  3487 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:51:14.417  3487  3487 I MotionRecognitionService: Plugged
,05-25 13:51:14.417  3487  3487 D MotionRecognitionService:   cableConnection= 1
05-25 13:51:14.417  3487  3487 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:51:14.417  3487  3487 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:51:14.417  3487  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:51:14.427  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
05-25 13:51:14.427  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
05-25 13:51:14.427  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:51:14.427  3949  3949 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,05-25 13:51:14.427  3949  3949 D PowerUI.Notification: There is no change about charging status, so return!
,05-25 13:51:14.437  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,05-25 13:51:14.447  4952  4952 D CommonServiceConfiguration: getStringValueSetting,
,05-25 13:51:14.457  4907  4907 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,05-25 13:51:14.457  4907  9949 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-25 13:51:14.457  4952  4952 D BatteryMonitor: new battery level: 100
,05-25 13:51:14.467  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,05-25 13:51:15.307  3487  6263 D SSRM:n  : SIOP:: AP = 310, PST = 343 (W:14), CP = 269, CUR = 168, LCD = 30
,05-25 13:51:21.637  9844  9908 I jxcore-log: 2017-05-25 11:51:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
05-25 13:51:21.637  9844  9908 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
05-25 13:51:21.637  9844  9908 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
05-25 13:51:21.637  9844  9908 I jxcore-log: emit@events.js:82:1
05-25 13:51:21.637  9844  9908 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
05-25 13:51:21.637  9844  9908 I jxcore-log: emit@events.js:82:1''
05-25 13:51:21.637  9844  9908 I jxcore-log: 
,05-25 13:51:21.637  9844  9908 I jxcore-log: 2017-05-25 11:51:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
05-25 13:51:21.637  9844  9908 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
05-25 13:51:21.637  9844  9908 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
05-25 13:51:21.637  9844  9908 I jxcore-log: emit@events.js:82:1
05-25 13:51:21.637  9844  9908 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
05-25 13:51:21.637  9844  9908 I jxcore-log: emit@events.js:82:1''
05-25 13:51:21.637  9844  9908 I jxcore-log: 
,05-25 13:51:24.467  3487  4920 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-25 13:51:24.467  3487  4920 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4351, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:51:24.467  3487  4920 D BatteryService: online:4, current avg:167, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:138
05-25 13:51:24.467  3487  3487 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:51:24.467  3487  3487 I MotionRecognitionService: Plugged
,05-25 13:51:24.467  3487  3487 D MotionRecognitionService:   cableConnection= 1
05-25 13:51:24.467  3487  3487 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:51:24.467  3487  3487 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:51:24.477  3487  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:51:24.477  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,05-25 13:51:24.477  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
,05-25 13:51:24.477  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:51:24.487  3949  3949 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
05-25 13:51:24.487  3949  3949 D PowerUI.Notification: There is no change about charging status, so return!
,05-25 13:51:24.497  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,05-25 13:51:24.507  4952  4952 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:51:24.517  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,05-25 13:51:24.517  4952  4952 D BatteryMonitor: new battery level: 100
,05-25 13:51:24.517  4907  4907 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,05-25 13:51:24.517  4907  9949 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-25 13:51:25.327  3487  6263 D SSRM:n  : SIOP:: AP = 310, PST = 337 (W:14), CP = 267, CUR = 167, LCD = 30
,05-25 13:51:29.727  3487  6298 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,05-25 13:51:30.557  3487  3809 D TimaService: TIMA: TimaService scheduler is intialized. 
,05-25 13:51:30.557  3487  3809 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,05-25 13:51:30.567  3487  3808 D TimaService: TimaServiceHandler.handleMessage what =1
,05-25 13:51:30.567  3487  3809 I TLC_TIMA_PKM_initialize: initializing...
,05-25 13:51:30.567  3487  3809 I TLC_TIMA_PKM_initialize: root = 0, root_strlen = 1
05-25 13:51:30.567  3487  3809 I TLC_TIMA_PKM_initialize: process = ffffffff00000000000000000000000a, process_strlen = 32
05-25 13:51:30.567  3487  3809 I TZ: mc_tlc_communication: input max_sendmsg_size = 262196
05-25 13:51:30.567  3487  3809 I TZ: mc_tlc_communication: input max_recvmsg_size = 262196
05-25 13:51:30.567  3487  3809 I TZ: mc_tlc_communication: root = 0, root_len = 1
05-25 13:51:30.567  3487  3809 I TZ: mc_tlc_communication: process = ffffffff00000000000000000000000a, process_strlen = 32
05-25 13:51:30.567  3487  3809 I TZ: mc_tlc_communication: aligned max_sendmsg_size = 262208
05-25 13:51:30.567  3487  3809 I TZ: mc_tlc_communication: aligned max_recvmsg_size = 262208
,05-25 13:51:30.567  3487  3809 I TZ: mc_tlc_communication: device_id = 0x0
05-25 13:51:30.567  3487  3809 I TZ: mc_tlc_communication: tlc_open() was called
05-25 13:51:30.567  3487  3809 I TZ: mc_tlc_communication: Opening MobiCore device
05-25 13:51:30.567  3487  3809 I TeeDriverClient: driver client open [hardware/samsung_slsi/exynos8890/mobicore/ClientLib/src/driver_client.cpp:103]
05-25 13:51:30.567  3487  3809 I TZ: mc_tlc_communication: Allocating message buffer for TCI
05-25 13:51:30.567  3487  3809 I TZ: mc_tlc_communication: Opening the session
,05-25 13:51:30.627  3487  3809 I TZ: mc_tlc_communication: tlc_open() succeeded
05-25 13:51:30.627  3487  3809 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info1
,05-25 13:51:30.637  3487  3809 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info2
,05-25 13:51:30.667  3487  3809 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info3
,05-25 13:51:30.677  3487  3809 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info4
,05-25 13:51:30.687  3487  3809 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,05-25 13:51:31.697  9844  9908 I jxcore-log: 2017-05-25 11:51:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
05-25 13:51:31.697  9844  9908 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
05-25 13:51:31.697  9844  9908 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
05-25 13:51:31.697  9844  9908 I jxcore-log: emit@events.js:82:1
05-25 13:51:31.697  9844  9908 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
05-25 13:51:31.697  9844  9908 I jxcore-log: emit@events.js:82:1''
05-25 13:51:31.697  9844  9908 I jxcore-log: 
,05-25 13:51:31.697  9844  9908 I jxcore-log: 2017-05-25 11:51:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
05-25 13:51:31.697  9844  9908 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
05-25 13:51:31.697  9844  9908 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
05-25 13:51:31.697  9844  9908 I jxcore-log: emit@events.js:82:1
05-25 13:51:31.697  9844  9908 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
05-25 13:51:31.697  9844  9908 I jxcore-log: emit@events.js:82:1''
05-25 13:51:31.697  9844  9908 I jxcore-log: 
,05-25 13:51:33.047  3487  4148 E Watchdog: !@Sync 10 [05-25 13:51:33.058]
,05-25 13:51:34.267  3487  3809 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
05-25 13:51:34.267  3487  3809 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,05-25 13:51:34.277  3487  3809 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,05-25 13:51:34.277  3487  3809 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,05-25 13:51:34.517  3487  3854 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-25 13:51:34.517  3487  3854 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4345, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:51:34.517  3487  3854 D BatteryService: online:4, current avg:157, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:190
05-25 13:51:34.517  3487  3487 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:51:34.527  3487  3487 I MotionRecognitionService: Plugged
,05-25 13:51:34.527  3487  3487 D MotionRecognitionService:   cableConnection= 1
05-25 13:51:34.527  3487  3487 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:51:34.527  3487  3487 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:51:34.537  3487  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:51:34.537  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
05-25 13:51:34.537  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
,05-25 13:51:34.537  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:51:34.537  3949  3949 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
05-25 13:51:34.537  3949  3949 D PowerUI.Notification: There is no change about charging status, so return!
,05-25 13:51:34.557  4952  4952 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:51:34.567  4952  4952 D BatteryMonitor: new battery level: 100
,05-25 13:51:34.567  4353  4435 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
05-25 13:51:34.567  4353  4435 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,05-25 13:51:34.577  4907  4907 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,05-25 13:51:34.577  4907  9949 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-25 13:51:34.577  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
05-25 13:51:34.577  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,05-25 13:51:35.347  3487  6263 D SSRM:n  : SIOP:: AP = 310, PST = 335 (W:14), CP = 266, CUR = 157, LCD = 30
,05-25 13:51:36.307  3487  3817 V AlarmManager: Expired Alarm result :4
,05-25 13:51:36.317 10112 10112 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
05-25 13:51:36.317 10112 10112 I wpa_supplicant: P2P: Current p2p state = IDLE
,05-25 13:51:36.337 10112 10112 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,05-25 13:51:36.347  3487  3570 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{437cc6a u0 null qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{20981f8 4585:com.google.android.gms/u0a21}
,05-25 13:51:36.367 10367 10367 E Zygote  : v2
05-25 13:51:36.367 10367 10367 I libpersona: KNOX_SDCARD checking this for 1000
05-25 13:51:36.367 10367 10367 I libpersona: KNOX_SDCARD not a persona
,05-25 13:51:36.377 10367 10367 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-25 13:51:36.377 10367 10367 E Zygote  : accessInfo : 0
,05-25 13:51:36.377  3487  3817 I ActivityManager: Start proc 10367:com.mobeam.barcodeService/1000 for service com.mobeam.barcodeService/.system.AppService
,05-25 13:51:36.417 10367 10367 D TimaKeyStoreProvider: TimaSignature is unavailable
05-25 13:51:36.417 10367 10367 D ActivityThread: Added TimaKeyStore provider
,05-25 13:51:36.447 10367 10367 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,05-25 13:51:36.447 10367 10367 D RelationGraph: garbageCollect()
,05-25 13:51:36.457 10367 10367 W ResourcesManager: getTopLevelResources: /system/app/BeamService/BeamService.apk / 1.0 running in com.mobeam.barcodeService rsrc of package com.mobeam.barcodeService
,05-25 13:51:36.457  3487  4947 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-25 13:51:36.457 10367 10367 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-25 13:51:36.457 10367 10367 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:51:36.457  4585 10380 I EventLogService: Aggregate from 1495711296269 (log), 1495711296269 (data)
,05-25 13:51:36.467 10367 10367 I InjectionManager: Inside getClassLibPath caller 
,05-25 13:51:36.477 10367 10367 W System  : ClassLoader referenced unknown path: /system/app/BeamService/lib/arm64
,05-25 13:51:36.487 10367 10367 D InjectionManager: InjectionManager
05-25 13:51:36.487 10367 10367 D InjectionManager: fillFeatureStoreMap com.mobeam.barcodeService
05-25 13:51:36.487 10367 10367 I InjectionManager: Constructor com.mobeam.barcodeService, Feature store :{}
05-25 13:51:36.487 10367 10367 I InjectionManager: featureStore :{}
,05-25 13:51:36.507  3487  4196 I ActivityManager: Killing 9576:com.sec.android.app.shealth/u0a39 (adj 15): DHA:empty #33
,05-25 13:51:36.537  3487  4408 D ActivityManager: cleanUpApplicationRecord -- 9576
,05-25 13:51:36.537  3487  4408 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.shealth, Auto Run ON
,05-25 13:51:36.577  3487  3570 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{bf4f5a4 u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f7ccf63 9688:com.samsung.android.sm/1000}
,05-25 13:51:36.587  3487  4407 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{afcbf0d u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f7ccf63 9688:com.samsung.android.sm/1000}
,05-25 13:51:40.347  3157  3631 D Netd    : Iface wlan0 link up
05-25 13:51:40.347 10112 10112 I wpa_supplicant: nl80211: Received scan results (14 BSSes)
05-25 13:51:40.357 10112 10112 I wpa_supplicant: scan_only_handler, so autoscan_notify() !!!
,05-25 13:51:40.357  3487  3858 D WifiP2pService: InactiveState{ what=147461 }
,05-25 13:51:40.367  4952  5261 D PdnController: Interface Changed wlan0 link up
,05-25 13:51:40.367  3487  3577 D Tethering: interfaceLinkStateChanged wlan0, true
05-25 13:51:40.367  3487  3858 D WifiP2pService: P2pEnabledState{ what=147461 }
,05-25 13:51:40.367  3487  3577 D Tethering: interfaceStatusChanged wlan0, true
05-25 13:51:40.367  3487  3858 D WifiP2pService: DefaultState{ what=147461 }
,05-25 13:51:40.397  3487  3487 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.SCAN_RESULTS
,05-25 13:51:40.397  3487  3570 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e17ec2 u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a665293 3949:com.android.systemui/u0a65}
,05-25 13:51:41.737  9844  9908 I jxcore-log: 2017-05-25 11:51:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
05-25 13:51:41.737  9844  9908 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
05-25 13:51:41.737  9844  9908 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
05-25 13:51:41.737  9844  9908 I jxcore-log: emit@events.js:82:1
05-25 13:51:41.737  9844  9908 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
05-25 13:51:41.737  9844  9908 I jxcore-log: emit@events.js:82:1''
05-25 13:51:41.737  9844  9908 I jxcore-log: 
,05-25 13:51:41.737  9844  9908 I jxcore-log: 2017-05-25 11:51:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
05-25 13:51:41.737  9844  9908 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
05-25 13:51:41.737  9844  9908 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
05-25 13:51:41.737  9844  9908 I jxcore-log: emit@events.js:82:1
05-25 13:51:41.737  9844  9908 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
05-25 13:51:41.737  9844  9908 I jxcore-log: emit@events.js:82:1''
05-25 13:51:41.737  9844  9908 I jxcore-log: 
,05-25 13:51:44.577  3487  4197 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,05-25 13:51:44.577  3487  4197 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4349, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:51:44.577  3487  4197 D BatteryService: online:4, current avg:139, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:166
05-25 13:51:44.577  3487  3487 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:51:44.587  3487  3487 I MotionRecognitionService: Plugged
,05-25 13:51:44.587  3487  3487 D MotionRecognitionService:   cableConnection= 1
,05-25 13:51:44.587  3487  3487 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:51:44.587  3487  3487 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:51:44.597  3487  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:51:44.597  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,05-25 13:51:44.597  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:51:44.607  3949  3949 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,05-25 13:51:44.607  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
05-25 13:51:44.607  3949  3949 D PowerUI.Notification: There is no change about charging status, so return!
,05-25 13:51:44.607  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,05-25 13:51:44.617  4952  4952 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:51:44.627  4952  4952 D BatteryMonitor: new battery level: 100
,05-25 13:51:44.627  4907  4907 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,05-25 13:51:44.627  4907  9949 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-25 13:51:44.627  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,05-25 13:51:45.377  3487  6263 D SSRM:n  : SIOP:: AP = 310, PST = 332 (W:14), CP = 265, CUR = 139, LCD = 30

```
