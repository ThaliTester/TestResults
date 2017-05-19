#### Test 11335185190ebf66_thali03_samsung-SM-G935F Logs


```
--------- beginning of system
,05-19 09:21:18.971  3511  4198 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-19 09:21:18.971  3511  4198 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4352, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-19 09:21:18.971  3511  4198 D BatteryService: online:4, current avg:168, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:193
05-19 09:21:18.971  3511  3511 D BatteryService: Sending ACTION_BATTERY_CHANGED.
05-19 09:21:18.981  3511  3511 I MotionRecognitionService: Plugged
05-19 09:21:18.981  3511  3511 D MotionRecognitionService:   cableConnection= 1
05-19 09:21:18.981  3511  3511 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-19 09:21:18.981  3511  3511 D MotionRecognitionService: skip setTransmitPower. 
--------- beginning of main
05-19 09:21:18.991  3511  3860 D WifiController: ApOrStaEnabledState  msg.what= 155652
05-19 09:21:18.991  3939  3939 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
05-19 09:21:18.991  3939  3939 D KeyguardUpdateMonitor: handleBatteryUpdate
05-19 09:21:18.991  3939  3939 D PowerUI : priorPlugType = 2 mPlugType =  2
05-19 09:21:18.991  3939  3939 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
05-19 09:21:18.991  3939  3939 D PowerUI.Notification: There is no change about charging status, so return!
05-19 09:21:19.011  4867  4867 D CommonServiceConfiguration: getStringValueSetting
05-19 09:21:19.011  4827  4827 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-19 09:21:19.011  4827  5228 D HeadsetStateMachine: Disconnected process message: 10, size: 0
05-19 09:21:19.021  4867  4867 D BatteryMonitor: new battery level: 100
05-19 09:21:19.031  3939  3939 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
05-19 09:21:19.031  3939  3939 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
05-19 09:21:19.451  9679  9679 I FIPS_bssl: FIPS approved mode (1) | 9679 | app_process
05-19 09:21:19.461  9679  9679 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
05-19 09:21:19.461  9679  9679 D AndroidRuntime: CheckJNI is OFF
05-19 09:21:19.461  9679  9679 D AndroidRuntime: readGMSProperty: start
05-19 09:21:19.461  9679  9679 D AndroidRuntime: readGMSProperty: already setted!!
05-19 09:21:19.461  9679  9679 D AndroidRuntime: propertySet: couldn't set property (it is from app)
05-19 09:21:19.461  9679  9679 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
05-19 09:21:19.461  9679  9679 D AndroidRuntime: readGMSProperty: end
05-19 09:21:19.461  9679  9679 D AndroidRuntime: addProductProperty: start
05-19 09:21:19.481  9679  9679 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
05-19 09:21:19.501  9679  9679 I Radio-JNI: register_android_hardware_Radio DONE
05-19 09:21:19.511  9679  9679 E AffinityControl: AffinityControl: registerfunction enter
05-19 09:21:19.511  9679  9679 D AndroidRuntime: Calling main entry com.android.commands.am.Am
05-19 09:21:19.541  3511  3984 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
05-19 09:21:19.541  3511  3984 W ResourcesManager: getTopLevelResources: /data/app/com.rockwellautomation.thalitest-1/base.apk / 1.0 running in null rsrc of package com.rockwellautomation.thalitest
05-19 09:21:19.571  3511  3984 D ResourcesManager: For user 0 new overlays fetched Null
05-19 09:21:19.581  3511  3984 D GameManagerService: identifyGamePackage. com.rockwellautomation.thalitest
05-19 09:21:19.581  3511  3984 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.rockwellautomation.thalitest)
05-19 09:21:19.581  3511  3984 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3511  pkgName : ACTIVITY_RESUME_BOOSTER@7
05-19 09:21:19.581  3511  3984 D ActivityManager: mDVFSHelper.acquire()
05-19 09:21:19.581  3511  3984 V WindowManager: addAppToken: AppWindowToken{d09871c5f token=Token{8780cfe ActivityRecord{f4ff0b9 u0 com.rockwellautomation.thalitest/.MainActivity t19}}} to stack=2 task=19 at 0
05-19 09:21:19.581  3014  4311 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (130 us)
05-19 09:21:19.601  3511  3649 I InjectionManager: Inside getClassLibPath caller 
05-19 09:21:19.601  3511  3984 D InputDispatcher: Focused application set to: xxxx
05-19 09:21:19.601  3511  3649 D SecWifiDisplayUtil: Metadata value : SecSettings2
05-19 09:21:19.601  3511  3649 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{8423857 V.E...... R.....ID 0,0-0,0}
05-19 09:21:19.611  3511  3601 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{319ab18 u0 d0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}
05-19 09:21:19.611  3511  3984 D InputDispatcher: Focus left window: 6232
05-19 09:21:19.611  3511  3649 D ISSUE_DEBUG: InputChannelName : 1f7882d Starting com.rockwellautomation.thalitest
05-19 09:21:19.611  3939  3939 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=8000 newVal=8600 diff=600
05-19 09:21:19.611  9679  9679 D AndroidRuntime: Shutting down VM
05-19 09:21:19.611  3014  3014 I SurfaceFlinger: id=18 createSurf (1x1),1 flag=404, uhalitest
05-19 09:21:19.621  9689  9689 E Zygote  : v2
05-19 09:21:19.621  9689  9689 I libpersona: KNOX_SDCARD checking this for 10078
05-19 09:21:19.621  9689  9689 I libpersona: KNOX_SDCARD not a persona
05-19 09:21:19.621  9689  9689 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
05-19 09:21:19.621  3511  4343 I ActivityManager: Start proc 9689:com.rockwellautomation.thalitest/u0a78 for activity com.rockwellautomation.thalitest/.MainActivity
05-19 09:21:19.621  9689  9689 E Zygote  : accessInfo : 0
05-19 09:21:19.621  9689  9689 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.rockwellautomation.thalitest 
05-19 09:21:19.631  3511  3649 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3511 uid:1000
05-19 09:21:19.631  3511  3855 D NetworkPolicy: isUidForegroundLocked: 10078, mScreenOn: true, uidstate: -1, mProxSensorScreenOff: false
05-19 09:21:19.631  3511  3649 D PointerIcon: setMouseCustomIcon IconType is same.101
05-19 09:21:19.631  3511  3649 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
05-19 09:21:19.641  9689  9689 D TimaKeyStoreProvider: TimaSignature is unavailable
05-19 09:21:19.641  9689  9689 D ActivityThread: Added TimaKeyStore provider
05-19 09:21:19.651  3511  4449 V WindowOrientationListener: setCurrentAppOrientation :-1
05-19 09:21:19.651  3511  4449 V WindowOrientationListener: OrientationSensorJudge.getProposedRotation, Rotation: -1
05-19 09:21:19.651  3511  4449 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
05-19 09:21:19.651  3511  4449 V WindowOrientationListener: OrientationSensorJudge.getProposedRotation, Rotation: -1
05-19 09:21:19.651  3511  4449 D ActivityManager:  Launching com.rockwellautomation.thalitest, updated priority
05-19 09:21:19.651  4299  4299 D Launcher.HomeView: onStop
05-19 09:21:19.651  4299  4299 D capture : ----destroy
05-19 09:21:19.651  4299  4299 V ActivityThread: updateVisibility : ActivityRecord{fce3fa1 token=android.os.BinderProxy@2e864f9 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
05-19 09:21:19.651  3511  3649 V WindowStateAnimator: Finishing drawing window Window{1f7882d u0 d0 Starting com.rockwellautomation.thalitest}: mDrawState=DRAW_PENDING
05-19 09:21:19.651  3511  3511 D GameManagerService: NotifyRunnable. pkg: com.rockwellautomation.thalitest, type: 4, isMinimized: false, isTunableApp: false
05-19 09:21:19.661  3014  3014 D libEGL  : eglInitialize EGLDisplay = 0x7fccf80d78
05-19 09:21:19.661  3511  3597 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.rockwellautomation.thalitest
05-19 09:21:19.661  3511  3597 E MARsPolicyManager: getPackageInfo package com.test.thalitest not installed!
05-19 09:21:19.661  3014  4311 D libEGL  : eglTerminate EGLDisplay = 0x7f8953ee78
05-19 09:21:19.661  3014  4311 D libEGL  : eglTerminate EGLDisplay = 0x7f8953ee78
05-19 09:21:19.671  3511  6156 D GameManagerService: identifyGamePackage. com.rockwellautomation.thalitest
05-19 09:21:19.671  3511  3601 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{1f7882d u0 d0 Starting com.rockwellautomation.thalitest}
05-19 09:21:19.671  3511  6156 D GameManagerService: identifyGamePackage. com.rockwellautomation.thalitest
05-19 09:21:19.671  3014  4311 D libEGL  : eglTerminate EGLDisplay = 0x7f8953ee78
05-19 09:21:19.671  3014  4311 D libEGL  : eglTerminate EGLDisplay = 0x7f8953ee78
05-19 09:21:19.671  9689  9689 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
05-19 09:21:19.671  9689  9689 D RelationGraph: garbageCollect()
05-19 09:21:19.671  9689  9689 W ResourcesManager: getTopLevelResources: /data/app/com.rockwellautomation.thalitest-1/base.apk / 1.0 running in com.rockwellautomation.thalitest rsrc of package com.rockwellautomation.thalitest
05-19 09:21:19.681  3511  6156 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
05-19 09:21:19.681  3511  6156 D GameManagerService: identifyGamePackage. com.rockwellautomation.thalitest
05-19 09:21:19.681  3511  3529 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-19 09:21:19.681  9689  9689 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
05-19 09:21:19.681  4299  4299 D Launcher: onTrimMemory. Level: 20
05-19 09:21:19.681  3511  6156 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
05-19 09:21:19.681  3511  6156 D GameManagerService: identifyGamePackage. com.rockwellautomation.thalitest
05-19 09:21:19.681  3511  6156 D GameManagerService: identifyGamePackage. com.rockwellautomation.thalitest
05-19 09:21:19.681  9689  9689 D ResourcesManager: For user 0 new overlays fetched Null
05-19 09:21:19.691  9689  9689 I InjectionManager: Inside getClassLibPath caller 
05-19 09:21:19.701  9689  9689 D InjectionManager: InjectionManager
05-19 09:21:19.701  9689  9689 D InjectionManager: fillFeatureStoreMap com.rockwellautomation.thalitest
05-19 09:21:19.701  9689  9689 I InjectionManager: Constructor com.rockwellautomation.thalitest, Feature store :{}
05-19 09:21:19.701  9689  9689 I InjectionManager: featureStore :{}
05-19 09:21:19.701  9689  9689 W ResourcesManager: getTopLevelResources: /data/app/com.rockwellautomation.thalitest-1/base.apk / 1.0 running in com.rockwellautomation.thalitest rsrc of package com.rockwellautomation.thalitest
05-19 09:21:19.701  9689  9689 D RelationGraph: garbageCollect()
05-19 09:21:19.701  9689  9689 W ResourcesManager: getTopLevelResources: /data/app/com.rockwellautomation.thalitest-1/base.apk / 1.0 running in com.rockwellautomation.thalitest rsrc of package com.rockwellautomation.thalitest
05-19 09:21:19.721  9689  9689 I CordovaLog: Changing log level to DEBUG(3)
05-19 09:21:19.721  9689  9689 I CordovaActivity: Apache Cordova native platform version 6.0.0 is starting
05-19 09:21:19.721  9689  9689 D CordovaActivity: CordovaActivity.onCreate()
05-19 09:21:19.731  9689  9689 I WebViewFactory: Loading com.google.android.webview version 50.0.2661.86 (code 266108650)
05-19 09:21:19.751  3511  3521 I art     : Background partial concurrent mark sweep GC freed 319856(21MB) AllocSpace objects, 85(5MB) LOS objects, 31% free, 34MB/50MB, paused 1.450ms total 157.434ms
05-19 09:21:19.781  9689  9689 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.rockwellautomation.thalitest rsrc of package com.google.android.webview
05-19 09:21:19.781  9689  9689 D ResourcesManager: For user 0 new overlays fetched Null
05-19 09:21:19.781  9689  9689 I InjectionManager: Inside getClassLibPath caller 
05-19 09:21:19.791  9689  9689 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
05-19 09:21:19.831  3511  6156 D SSRM:n  : SIOP:: AP = 290, PST = 295 (W:14), CP = 247, CUR = 168, LCD = 30
05-19 09:21:19.831  9689  9689 I cr_LibraryLoader: Time to load native libraries: 24 ms (timestamps 5247-5271)
05-19 09:21:19.831  9689  9689 I cr_LibraryLoader: Expected native library version number "50.0.2661.86", actual native library version number "50.0.2661.86"
,05-19 09:21:19.831  3511  6156 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,05-19 09:21:19.851  9689  9703 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.rockwellautomation.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,05-19 09:21:19.861  9689  9689 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {ca63953}
05-19 09:21:19.861  9689  9689 I cr_LibraryLoader: Expected native library version number "50.0.2661.86", actual native library version number "50.0.2661.86"
,05-19 09:21:19.881  9689  9689 I chromium: [INFO:library_loader_hooks.cc(143)] Chromium logging enabled: level = 0, default verbosity = 0
,05-19 09:21:19.911  9689  9689 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,05-19 09:21:19.921  3511  3879 D MdnieScenarioControlService:  packageName : com.rockwellautomation.thalitest    className : com.rockwellautomation.thalitest.MainActivity
,05-19 09:21:20.001  9689  9689 D libEGL  : eglInitialize EGLDisplay = 0xffc11cf4
,05-19 09:21:20.021  3511  3879 I MdnieScenarioControlService: mGameModeLauncher : false
,05-19 09:21:20.021  3511  3879 I MdnieScenarioControlService: setUIMode
,05-19 09:21:20.041  3511  3852 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10078
,05-19 09:21:20.041  3511  3852 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29757 com.android.server.am.ActivityManagerService.registerReceiver:22622 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,05-19 09:21:20.041  3014  3025 I SurfaceFlinger: id=10 Removed MauncherAct (4/15)
05-19 09:21:20.041  3014  3023 I SurfaceFlinger: id=10 Removed MauncherAct (-2/15)
05-19 09:21:20.041  3014  4311 I SurfaceFlinger: id=17 Removed VSBConnecti (4/14)
05-19 09:21:20.041  3014  4312 I SurfaceFlinger: id=17 Removed VSBConnecti (-2/14)
05-19 09:21:20.041  3014  3025 I SurfaceFlinger: id=16 Removed VSBConnecti (5/13)
05-19 09:21:20.041  3014  4483 I SurfaceFlinger: id=16 Removed VSBConnecti (-2/13)
,05-19 09:21:20.041  3939  3939 D ImageWallpaper: onVisibilityChanged:false
,05-19 09:21:20.051  3939  3939 D ImageWallpaper: drawFrame:false rotation:0 mLastRotation:0
05-19 09:21:20.051  3939  3939 D ImageWallpaper: drawFrame:[frame.width()]2240[frame.height()]2560
05-19 09:21:20.051  3939  3939 D ImageWallpaper: Suppressed drawFrame since redraw is not needed and offsets have not changed.
,05-19 09:21:20.061  3014  3014 D libEGL  : eglTerminate EGLDisplay = 0x7fccf80e98
05-19 09:21:20.061  3014  3014 D libEGL  : eglTerminate EGLDisplay = 0x7fccf80e98
05-19 09:21:20.061  3014  3014 D libEGL  : eglTerminate EGLDisplay = 0x7fccf80e98
,05-19 09:21:20.061  3511  3855 D NetworkPolicy: isUidForegroundLocked: 10021, mScreenOn: true, uidstate: 2, mProxSensorScreenOff: false
,05-19 09:21:20.081  9689  9689 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10078, CallingPid : 9689
,05-19 09:21:20.081  3511  4343 D ConnectivityService: listenForNetwork for Listen from uid/pid:10078/9689 for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-19 09:21:20.081  3511  3866 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,05-19 09:21:20.081  3511  3866 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -26]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,05-19 09:21:20.091  3511  3866 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,05-19 09:21:20.091  3511  3866 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-19 09:21:20.091  3511  3866 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,05-19 09:21:20.091  3511  3866 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-19 09:21:20.091  3511  3866 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-19 09:21:20.091  3511  3866 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,05-19 09:21:20.091  3511  3866 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 09:21:20.091  9689  9689 D cr_Ime  : [InputMethodManagerWrapper.java:30] Constructor
,05-19 09:21:20.101  9689  9689 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,05-19 09:21:20.111  9689  9689 D cr_Ime  : [InputMethodManagerWrapper.java:59] isActive: false
,05-19 09:21:20.121  9689  9689 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,05-19 09:21:20.121  9689  9689 D PluginManager: init()
,05-19 09:21:20.131  9689  9689 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,05-19 09:21:20.141  9689  9689 I cr_Ime  : ImeThread is not enabled.
,05-19 09:21:20.141  9689  9689 D Activity: performCreate Call Injection manager
,05-19 09:21:20.141  9689  9689 D CordovaActivity: Started the activity.
05-19 09:21:20.141  9689  9689 I InjectionManager: dispatchOnViewCreated > Target : com.rockwellautomation.thalitest.MainActivity isFragment :false
05-19 09:21:20.141  9689  9689 D CordovaActivity: Resumed the activity.
,05-19 09:21:20.151  9689  9689 D SecWifiDisplayUtil: Metadata value : SecSettings2
,05-19 09:21:20.151  9689  9689 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{ed4198f I.E...... R.....ID 0,0-0,0}
,05-19 09:21:20.151  9689  9738 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,05-19 09:21:20.161  3511  4198 D ISSUE_DEBUG: InputChannelName : 7b8bf3c com.rockwellautomation.thalitest/com.rockwellautomation.thalitest.MainActivity
,05-19 09:21:20.161  3511  3852 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
05-19 09:21:20.161  3511  3852 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
05-19 09:21:20.161  3511  3511 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,05-19 09:21:20.161  3511  3511 I KnoxTimeoutHandler: Shared devices show user statefalse
,05-19 09:21:20.161  9689  9703 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.rockwellautomation.thalitest/shared_prefs/com.rockwellautomation.thalitest_preferences.xml.bak
,05-19 09:21:20.161  9689  9689 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10078, CallingPid : 9689
,05-19 09:21:20.161  3511  4459 D ConnectivityService: listenForNetwork for Listen from uid/pid:10078/9689 for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-19 09:21:20.171  3511  3866 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,05-19 09:21:20.171  3511  3866 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -26]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,05-19 09:21:20.171  3511  3866 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,05-19 09:21:20.171  3511  3855 D NetworkPolicy: isUidForegroundLocked: 10021, mScreenOn: true, uidstate: 6, mProxSensorScreenOff: false
,05-19 09:21:20.171  3511  3866 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-19 09:21:20.171  3511  3866 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,05-19 09:21:20.181  3511  3866 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-19 09:21:20.181  9689  9689 D SecWifiDisplayUtil: Metadata value : SecSettings2
,05-19 09:21:20.181  3511  3866 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-19 09:21:20.181  3511  3866 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-19 09:21:20.191  3511  3866 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
05-19 09:21:20.191  3511  3866 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-19 09:21:20.191  3014  3014 I SurfaceFlinger: id=19 createSurf (1x1),1 flag=404, NainActivit
,05-19 09:21:20.211  3511  3529 D InputDispatcher: Focus entered window: 9689
05-19 09:21:20.211  3511  3649 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3511 uid:1000
05-19 09:21:20.211  3511  3649 D PointerIcon: setMouseCustomIcon IconType is same.101
05-19 09:21:20.211  9689  9738 D libEGL  : eglInitialize EGLDisplay = 0xdc7bf7c4
05-19 09:21:20.211  9689  9738 I OpenGLRenderer: Initialized EGL, version 1.4
05-19 09:21:20.211  9689  9738 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,05-19 09:21:20.221  9689  9742 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
05-19 09:21:20.221  9689  9742 D libEGL  : eglInitialize EGLDisplay = 0xda97f3e4
,05-19 09:21:20.221  9689  9689 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,05-19 09:21:20.231  9689  9742 D libGLESv2: DTS_GLAPI : DTS is not allowed for Package : com.rockwellautomation.thalitest
,05-19 09:21:20.261  3511  4407 V WindowStateAnimator: Finishing drawing window Window{7b8bf3c u0 d0 com.rockwellautomation.thalitest/com.rockwellautomation.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,05-19 09:21:20.261  9689  9689 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
05-19 09:21:20.261  3511  4451 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,05-19 09:21:20.261  3511  3649 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,05-19 09:21:20.261  3511  3511 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
05-19 09:21:20.271  3511  3649 I ActivityManager: Displayed com.rockwellautomation.thalitest/.MainActivity: +656ms
,05-19 09:21:20.271  3511  3649 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3511  tag : ACTIVITY_RESUME_BOOSTER@7
05-19 09:21:20.271  3511  3511 I KnoxTimeoutHandler: SD activityfalse
,05-19 09:21:20.271  3511  3649 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{f4ff0b9 u0 com.rockwellautomation.thalitest/.MainActivity t19} time:185712
05-19 09:21:20.271  3511  3649 D ActivityManager: mDVFSHelper.release()
05-19 09:21:20.271  3511  3649 D ViewRootImpl: #3 mView = null
,05-19 09:21:20.271  3511  3597 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3511  pkgName : ACTIVITY_RESUME_BOOSTER@13
,05-19 09:21:20.271  3014  3014 D libEGL  : eglInitialize EGLDisplay = 0x7fccf80d78
,05-19 09:21:20.271  4917  4917 D SamsungIME: IMPL finishInput
,05-19 09:21:20.271  4917  4917 D SamsungIME: SwiftKeyWrapper writeDBdataToFileOnFinishInput
05-19 09:21:20.271  4917  4917 D SamsungIME: saveAndClear +
05-19 09:21:20.271  4917  4917 D SamsungIME: saveAndClear -
,05-19 09:21:20.301  3511  3528 V WindowStateAnimator: Finishing drawing window Window{7b8bf3c u0 d0 com.rockwellautomation.thalitest/com.rockwellautomation.thalitest.MainActivity}: mDrawState=HAS_DRAWN
,05-19 09:21:20.301  9689  9689 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
,05-19 09:21:20.301  3014  3014 D libEGL  : eglInitialize EGLDisplay = 0x7fccf80d78
,05-19 09:21:20.311  9689  9689 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9689
,05-19 09:21:20.311  9689  9689 D cr_Ime  : [InputMethodManagerWrapper.java:59] isActive: true
05-19 09:21:20.311  9689  9689 D cr_Ime  : [InputMethodManagerWrapper.java:68] hideSoftInputFromWindow
,05-19 09:21:20.311  9689  9689 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@f68d3b6 time:185753
,05-19 09:21:20.311  6232  6232 V ActivityThread: updateVisibility : ActivityRecord{bbe430d token=android.os.BinderProxy@3c64da7 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
,05-19 09:21:20.321  3014  3014 D libEGL  : eglInitialize EGLDisplay = 0x7fccf80d78
,05-19 09:21:20.371  9689  9689 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,05-19 09:21:20.461  3014  4312 I SurfaceFlinger: id=18 Removed uhalitest (7/13)
05-19 09:21:20.461  3014  3025 I SurfaceFlinger: id=18 Removed uhalitest (-2/13)
,05-19 09:21:20.471  3014  3014 D libEGL  : eglTerminate EGLDisplay = 0x7fccf80e98
,05-19 09:21:20.491  9689  9752 D jxcore_app_log: JniHelper::setJavaVM(0xf4bf4000), pthread_self() = -703071952
,05-19 09:21:20.491  9689  9752 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
05-19 09:21:20.491  9689  9752 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
05-19 09:21:20.491  9689  9752 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
05-19 09:21:20.491  9689  9752 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
,05-19 09:21:20.491  9689  9752 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
05-19 09:21:20.491  9689  9752 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a17819e added. We now have 1 listener(s)
05-19 09:21:20.491  9689  9752 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a17819e added. We now have 1 listener(s)
05-19 09:21:20.491  9689  9752 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
05-19 09:21:20.491  9689  9752 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
05-19 09:21:20.491  9689  9752 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
05-19 09:21:20.491  9689  9752 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: null
05-19 09:21:20.491  9689  9752 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
05-19 09:21:20.491  9689  9752 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
05-19 09:21:20.491  9689  9752 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
05-19 09:21:20.491  9689  9752 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
05-19 09:21:20.491  9689  9752 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 256
05-19 09:21:20.491  9689  9752 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
05-19 09:21:20.491  9689  9752 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
05-19 09:21:20.491  9689  9752 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
05-19 09:21:20.491  9689  9752 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
05-19 09:21:20.491  9689  9752 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,05-19 09:21:20.491  9689  9752 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: A8:81:95:E9:5F:6F
,05-19 09:21:20.491  9689  9752 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: ", Bluetooth MAC address: "A8:81:95:E9:5F:6F"Peer extra info: "256
05-19 09:21:20.491  9689  9752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
05-19 09:21:20.491  9689  9752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: null
05-19 09:21:20.501  9689  9752 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
05-19 09:21:20.501  9689  9752 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f8d495 added. We now have 2 listener(s)
05-19 09:21:20.501  9689  9752 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,05-19 09:21:20.501  9689  9752 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
05-19 09:21:20.501  9689  9752 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 13612
,05-19 09:21:20.501  9689  9752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,7,main], id: 134
05-19 09:21:20.501  9689  9752 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
05-19 09:21:20.501  9689  9752 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
05-19 09:21:20.501  9689  9752 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
05-19 09:21:20.501  9689  9752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,7,main], id: 134
,05-19 09:21:20.501  9689  9752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
05-19 09:21:20.501  9689  9752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is A8:81:95:E9:5F:6F
,05-19 09:21:20.511  9689  9752 D BluetoothAdapter: STATE_ON
,05-19 09:21:20.511  9689  9752 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,05-19 09:21:20.511  9689  9752 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
05-19 09:21:20.511  9689  9752 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-19 09:21:20.511  9689  9752 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-19 09:21:20.511  9689  9752 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-19 09:21:20.511  9689  9752 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-19 09:21:20.511  9689  9752 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-19 09:21:20.511  9689  9752 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-19 09:21:20.511  9689  9752 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-19 09:21:20.511  9689  9752 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
05-19 09:21:20.511  9689  9752 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
05-19 09:21:20.511  9689  9752 D io.jxcore.node.ConnectivityMonitor: start: OK
05-19 09:21:20.511  9689  9752 I io.jxcore.node.LifeCycleMonitor: start: OK
,05-19 09:21:20.511  9689  9689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-19 09:21:20.511  9689  9689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-19 09:21:20.521  9689  9689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-19 09:21:20.521  9689  9689 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,05-19 09:21:20.521  9689  9689 D SystemWebChromeClient: file:///android_asset/www/js/index.js: Line 36 : Uncaught TypeError: Cannot read property 'querySelector' of null
,05-19 09:21:20.521  9689  9689 I chromium: [INFO:CONSOLE(36)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (36)
,05-19 09:21:20.571  3511  3511 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3511  tag : ACTIVITY_RESUME_BOOSTER@13
,05-19 09:21:20.581  3511  3879 D MdnieScenarioControlService:  packageName : com.rockwellautomation.thalitest    className : com.rockwellautomation.thalitest.MainActivity
,05-19 09:21:20.631  4025  4025 D Recents : onTaskStackChanged
,05-19 09:21:20.641  4025  4025 W ResourcesManager: getTopLevelResources: /data/app/com.rockwellautomation.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.rockwellautomation.thalitest
,05-19 09:21:20.651  4025  4025 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 09:21:20.671  3511  6157 W ResourcesManager: getTopLevelResources: /data/app/com.rockwellautomation.thalitest-1/base.apk / 1.0 running in null rsrc of package com.rockwellautomation.thalitest
,05-19 09:21:20.681  3511  3879 I MdnieScenarioControlService: mGameModeLauncher : false
,05-19 09:21:20.681  3511  3879 I MdnieScenarioControlService: setUIMode
,05-19 09:21:21.001  9689  9753 W jxcore-log: Initializing JXcore engine
05-19 09:21:21.001  9689  9753 W jxcore-log: JXcore engine is ready
,05-19 09:21:21.021  4838  4838 E audit   : type=1400 msg=audit(1495178481.011:264): avc:  denied  { ioctl } for  pid=9753 comm="Thread-135" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=1181 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
05-19 09:21:21.021  4838  4838 E audit   :  SEPF_SECMOBILE_6.0.1_0031
05-19 09:21:21.021  4838  4838 E audit   : type=1300 msg=audit(1495178481.011:264): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=8 a1=5451 a2=2 a3=d52bf3c8 items=0 ppid=3183 pid=9753 auid=4294967295 uid=10078 gid=10078 euid=10078 suid=10078 fsuid=10078 egid=10078 sgid=10078 fsgid=10078 tty=(none) ses=4294967295 comm="Thread-135" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
05-19 09:21:21.021  4838  4838 E audit   : type=1327 msg=audit(1495178481.011:264): proctitle="com.rockwellautomation.thalitest"
05-19 09:21:21.021  4838  4838 E audit   : type=1320 msg=audit(1495178481.011:264): 
,05-19 09:21:21.021  4838  4838 E audit   : type=1400 msg=audit(1495178481.021:265): avc:  denied  { ioctl } for  pid=9753 comm="Thread-135" path="socket:[34305]" dev="sockfs" ino=34305 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
05-19 09:21:21.021  4838  4838 E audit   :  SEPF_SECMOBILE_6.0.1_0031
05-19 09:21:21.021  4838  4838 E audit   : type=1300 msg=audit(1495178481.021:265): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=33 a1=5451 a2=2 a3=d52bf3c8 items=0 ppid=3183 pid=9753 auid=4294967295 uid=10078 gid=10078 euid=10078 suid=10078 fsuid=10078 egid=10078 sgid=10078 fsgid=10078 tty=(none) ses=4294967295 comm="Thread-135" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
05-19 09:21:21.021  4838  4838 E audit   : type=1327 msg=audit(1495178481.021:265): proctitle="com.rockwellautomation.thalitest"
05-19 09:21:21.021  4838  4838 E audit   : type=1320 msg=audit(1495178481.021:265): 
,05-19 09:21:21.021  9689  9753 W jxcore-log: Starting JXcore engine
,05-19 09:21:21.061  9689  9753 W jxcore-log: Platform android
05-19 09:21:21.061  9689  9753 W jxcore-log: 
05-19 09:21:21.061  9689  9753 W jxcore-log: Process ARCH arm
05-19 09:21:21.061  9689  9753 W jxcore-log: 
,05-19 09:21:21.181  9689  9753 I jxcore-log: JXcore Cordova bridge is ready!
05-19 09:21:21.181  9689  9753 I jxcore-log: 
05-19 09:21:21.181  9689  9753 W jxcore-log: JXcore engine is started
,05-19 09:21:21.191  9689  9752 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,05-19 09:21:21.201  9689  9689 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 41 : Application has the required permission.
05-19 09:21:21.201  9689  9689 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,05-19 09:21:22.591  3511  3906 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/19_task.xml.bak
,05-19 09:21:22.671  3511  6156 D GameManagerService: identifyGamePackage. com.rockwellautomation.thalitest
,05-19 09:21:24.661  3511  6192 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,05-19 09:21:24.961  3511  3654 I PowerManagerService: [PWL] On : 0 (190409 ms ago)
05-19 09:21:24.961  3511  3654 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4
,05-19 09:21:25.701  3511  6156 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,05-19 09:21:28.301  9689  9753 I jxcore-log: 2017-05-19 07:21:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
05-19 09:21:28.301  9689  9753 I jxcore-log: 
,05-19 09:21:28.301  9689  9753 I jxcore-log: 2017-05-19 07:21:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
05-19 09:21:28.301  9689  9753 I jxcore-log: 
05-19 09:21:28.301  9689  9753 I jxcore-log: 2017-05-19 07:21:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
05-19 09:21:28.301  9689  9753 I jxcore-log: 
,05-19 09:21:28.311  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:21:28.311  9689  9753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
05-19 09:21:28.311  9689  9753 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-19 09:21:28.311  9689  9753 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-19 09:21:28.311  9689  9753 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-19 09:21:28.311  9689  9753 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-19 09:21:28.311  9689  9753 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-19 09:21:28.311  9689  9753 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-19 09:21:28.311  9689  9753 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-19 09:21:28.311  9689  9753 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,05-19 09:21:28.321  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:21:28.321  9689  9753 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
05-19 09:21:28.321  9689  9753 I jxcore-log: 2017-05-19 07:21:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
05-19 09:21:28.321  9689  9753 I jxcore-log: 
05-19 09:21:28.321  9689  9753 I jxcore-log: 2017-05-19 07:21:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
05-19 09:21:28.321  9689  9753 I jxcore-log: 
05-19 09:21:28.321  9689  9753 I jxcore-log: 2017-05-19 07:21:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
05-19 09:21:28.321  9689  9753 I jxcore-log: 
,05-19 09:21:28.361  3511  4144 E Watchdog: !@Sync 6 [05-19 09:21:28.379]
,05-19 09:21:28.611  9689  9753 D ExecuteNativeTests: Running unit tests
05-19 09:21:28.611  9689  9753 D BluetoothAdapter: enable()
,05-19 09:21:28.621  9689  9753 D BluetoothAdapter: enable(): BT is already enabled..!
,05-19 09:21:28.631  3511  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5528935 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cf9e5aa 4853:com.samsung.android.providers.context/u0a9}
,05-19 09:21:28.631  9689  9753 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,05-19 09:21:28.641  3511  3852 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,05-19 09:21:28.641  3511  3852 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,05-19 09:21:28.641  3511  3852 D WifiService: setWifiEnabled: true pid=9689, uid=10078
,05-19 09:21:28.661  3511  3852 W ActivityManager: Permission Denial: getCurrentUser() from pid=9689, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
,05-19 09:21:28.661  3511  3852 W WifiService: Failed getting userId using ActivityManagerNative
05-19 09:21:28.661  3511  3852 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9689, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-19 09:21:28.661  3511  3852 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-19 09:21:28.661  3511  3852 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
05-19 09:21:28.661  3511  3852 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
05-19 09:21:28.661  3511  3852 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
05-19 09:21:28.661  3511  3852 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
,05-19 09:21:28.661  3511  3857 D WifiBigDataLog: getJsonFormat() - feature : ONOF
05-19 09:21:28.661  3511  3852 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
05-19 09:21:28.661  3511  3852 D SettingsProvider: isChangeAllowed() : name = wifi_on
05-19 09:21:28.661  3511  3860 D WifiStateMachine: setFccChannel: channel = 0
,05-19 09:21:28.661  3511  3860 D WifiController: [FCC]setFccChannel() is called !!!
05-19 09:21:28.661  3511  3860 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
,05-19 09:21:28.661  3511  3857 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
05-19 09:21:28.671  3511  3857 D WifiBigDataLog: init : 
,05-19 09:21:28.681  3511  3857 D WifiStateMachine: setFccChannelNative: channel = 0
,05-19 09:21:28.681  3511  3857 D WifiNative-wlan0: callSECApiInt - ID [230],
,05-19 09:21:28.681  3511  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{df0c1ca u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cf9e5aa 4853:com.samsung.android.providers.context/u0a9}
,05-19 09:21:29.031  3511  4407 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,05-19 09:21:29.031  3511  4407 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4324, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-19 09:21:29.031  3511  4407 D BatteryService: online:4, current avg:-215, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:213
05-19 09:21:29.031  3511  3511 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-19 09:21:29.041  3511  3511 I MotionRecognitionService: Plugged
05-19 09:21:29.041  3511  3511 D MotionRecognitionService:   cableConnection= 1
05-19 09:21:29.041  3511  3511 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-19 09:21:29.041  3511  3511 D MotionRecognitionService: skip setTransmitPower. 
,05-19 09:21:29.041  3511  3860 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-19 09:21:29.051  3939  3939 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,05-19 09:21:29.051  3939  3939 D KeyguardUpdateMonitor: handleBatteryUpdate
,05-19 09:21:29.051  3939  3939 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-19 09:21:29.051  3939  3939 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,05-19 09:21:29.051  3939  3939 D PowerUI.Notification: There is no change about charging status, so return!
,05-19 09:21:29.071  4867  4867 D CommonServiceConfiguration: getStringValueSetting
,05-19 09:21:29.081  3939  3939 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
05-19 09:21:29.081  3939  3939 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
05-19 09:21:29.081  4827  4827 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-19 09:21:29.081  4827  5228 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-19 09:21:29.091  4867  4867 D BatteryMonitor: new battery level: 100
,05-19 09:21:29.661  3511  3703 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,05-19 09:21:29.681  3511  3703 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,05-19 09:21:29.691  4378  4466 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
05-19 09:21:29.691  4378  4466 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,05-19 09:21:29.791  4378  4466 E ContactsProvider_EventLog: Flush buffer to file cnt : 4 size : 1Kb duration : 97ms lastUpdatedAfter : 128649ms
,05-19 09:21:29.851  3511  6156 D SSRM:n  : SIOP:: AP = 360, PST = 297 (W:6), CP = 258, CUR = -215, LCD = 30
,05-19 09:21:29.871  3511  6156 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,05-19 09:21:38.671  9689  9753 I com.test.thalitest.ThaliTestRunner: Running UT
,05-19 09:21:38.741  9689  9753 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
05-19 09:21:38.741  9689  9753 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@45067f5 added. We now have 2 listener(s)
05-19 09:21:38.741  9689  9753 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@45067f5 added. We now have 3 listener(s)
05-19 09:21:38.741  9689  9753 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
05-19 09:21:38.741  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: ", Bluetooth MAC address: "A8:81:95:E9:5F:6F"Peer extra info: "256
05-19 09:21:38.741  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
05-19 09:21:38.741  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: null
05-19 09:21:38.741  9689  9753 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
05-19 09:21:38.741  9689  9753 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@267198a added. We now have 4 listener(s)
05-19 09:21:38.741  9689  9753 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,05-19 09:21:38.741  9689  9753 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,05-19 09:21:38.751  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:21:38.761  9689  9753 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
,05-19 09:21:38.761  9689  9753 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
05-19 09:21:38.761  9689  9753 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
05-19 09:21:38.761  9689  9753 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
05-19 09:21:38.761  9689  9753 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [00:11:22:33:44:55] timed out
05-19 09:21:38.761  9689  9753 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,05-19 09:21:38.761  9689  9753 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
05-19 09:21:38.761  9689  9753 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
05-19 09:21:38.761  9689  9753 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,05-19 09:21:38.761  9689  9753 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
,05-19 09:21:38.761  9689  9753 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,05-19 09:21:38.761  9689  9753 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
,05-19 09:21:38.761  9689  9753 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
05-19 09:21:38.761  9689  9753 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
05-19 09:21:38.771  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,05-19 09:21:38.791  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:21:38.791  9689  9698 I art     : Background sticky concurrent mark sweep GC freed 39856(1788KB) AllocSpace objects, 7(188KB) LOS objects, 10% free, 13MB/15MB, paused 5.457ms total 60.159ms
,05-19 09:21:38.791  9689  9753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
05-19 09:21:38.791  9689  9753 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-19 09:21:38.791  9689  9753 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-19 09:21:38.791  9689  9753 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-19 09:21:38.791  9689  9753 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-19 09:21:38.791  9689  9753 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-19 09:21:38.791  9689  9753 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-19 09:21:38.791  9689  9753 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-19 09:21:38.791  9689  9753 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
05-19 09:21:38.791  9689  9753 D io.jxcore.node.ConnectivityMonitor: start: OK
,05-19 09:21:38.791  9689  9753 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 0
05-19 09:21:38.791  9689  9753 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 256 -> 0
05-19 09:21:38.791  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,05-19 09:21:38.791  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":0,"address":"A8:81:95:E9:5F:6F"}
,05-19 09:21:38.791  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":0,"address":"A8:81:95:E9:5F:6F"}
05-19 09:21:38.801  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:38.801  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,05-19 09:21:38.801  9689  9689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-19 09:21:38.801  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":0,"address":"A8:81:95:E9:5F:6F"}
05-19 09:21:38.801  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":0,"address":"A8:81:95:E9:5F:6F"}
05-19 09:21:38.801  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:38.801  9689  9753 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
05-19 09:21:38.801  9689  9753 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
05-19 09:21:38.801  9689  9753 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
05-19 09:21:38.801  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,05-19 09:21:38.801  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,05-19 09:21:38.801  9689  9689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-19 09:21:38.801  9689  9753 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,05-19 09:21:38.801  9689  9753 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
05-19 09:21:38.801  9689  9753 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,05-19 09:21:38.801  9689  9758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,05-19 09:21:38.801  9689  9753 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
05-19 09:21:38.801  9689  9753 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
05-19 09:21:38.801  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
05-19 09:21:38.801  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,05-19 09:21:38.811  9689  9689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
05-19 09:21:38.811  9689  9758 D BluetoothSocket: bindListen(): myUserId = 0
05-19 09:21:38.811  9689  9689 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
05-19 09:21:38.811  9689  9758 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
05-19 09:21:38.811  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
05-19 09:21:38.811  9689  9753 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
05-19 09:21:38.811  9689  9753 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,05-19 09:21:38.821  9689  9753 D BluetoothAdapter: STATE_ON
05-19 09:21:38.821  9689  9758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
05-19 09:21:38.821  9689  9758 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@90c8e71, port: 6, type: 1, local socket address: null, socket type: 0
05-19 09:21:38.821  9689  9753 D BluetoothAdapter: STATE_ON
05-19 09:21:38.821  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:21:38.831  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:38.831  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,05-19 09:21:38.831  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:21:38.831  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:21:38.831  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,05-19 09:21:38.831  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,05-19 09:21:38.831  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 0
,05-19 09:21:38.841  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:21:38.841  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-135,7,main], id: 135
,05-19 09:21:38.841  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:38.841  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
05-19 09:21:38.841  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
05-19 09:21:38.841  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b1b48b8e-977b-494d-8afb-10acf9d32846", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
,05-19 09:21:38.841  9689  9753 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 A8 81 95 E9 5F 6F
,05-19 09:21:38.841  9689  9753 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b1b48b8e-977b-494d-8afb-10acf9d32846], mManufacturerSpecificData={}, mServiceData={b1b48b8e-977b-494d-8afb-10acf9d32846=[0, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,05-19 09:21:38.841  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b1b48b8e-977b-494d-8afb-10acf9d32846], mManufacturerSpecificData={}, mServiceData={b1b48b8e-977b-494d-8afb-10acf9d32846=[0, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-19 09:21:38.841  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:38.841  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b1b48b8e-977b-494d-8afb-10acf9d32846], mManufacturerSpecificData={}, mServiceData={b1b48b8e-977b-494d-8afb-10acf9d32846=[0, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-135,7,main], id: 135
,05-19 09:21:38.841  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
05-19 09:21:38.841  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b1b48b8e-977b-494d-8afb-10acf9d32846], mManufacturerSpecificData={}, mServiceData={b1b48b8e-977b-494d-8afb-10acf9d32846=[0, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-19 09:21:38.841  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:38.841  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-135,7,main], id: 135
,05-19 09:21:38.841  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[b1b48b8e-977b-494d-8afb-10acf9d32846], mManufacturerSpecificData={}, mServiceData={b1b48b8e-977b-494d-8afb-10acf9d32846=[0, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-135,7,main], id: 135
,05-19 09:21:38.841  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:21:38.851  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:21:38.851  9689  9753 D BluetoothLeAdvertiser: start advertising
,05-19 09:21:38.851  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:21:38.861  4827  4840 D BtGatt.GattService: registerClient() - UUID=baf5e504-6f28-4a14-ab5b-c4d12663c5d5
,05-19 09:21:38.901  4827  4974 D BtGatt.GattService: onClientRegistered() - UUID=baf5e504-6f28-4a14-ab5b-c4d12663c5d5, clientIf=7
,05-19 09:21:38.911  9689  9700 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,05-19 09:21:38.911  4827  5441 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,05-19 09:21:38.911  4827  5441 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
05-19 09:21:38.911  4827  5441 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
,05-19 09:21:38.911  4827  5070 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.rockwellautomation.thalitest, msg: MESSAGE_START_ADV
,05-19 09:21:38.911  4827  5070 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 18, currDate: 19
05-19 09:21:38.911  4827  5046 D BtGatt.AdvertiseManager: message : 0
,05-19 09:21:38.921  4827  5046 D BtGatt.AdvertiseManager: number of adv instance running = 0
,05-19 09:21:38.921  4827  5046 D BtGatt.AdvertiseManager: size of list is =0
,05-19 09:21:38.921  4827  5046 D BtGatt.AdvertiseManager: starting advertising
,05-19 09:21:38.921  4827  5046 D BtGatt.AdvertiseManager: isStandardAdv = false
,05-19 09:21:38.931  4827  5070 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.rockwellautomation.thalitest@LowLatency : 24919641
,05-19 09:21:38.931  3511  3529 V AlarmManager:  remove PendingIntent] PendingIntent{7a9ed: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:38.931  4827  5070 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.rockwellautomation.thalitest@LowLatency : 2
05-19 09:21:38.931  4827  5070 D BtGatt.GattService: [GSIM LOG]: reportData
05-19 09:21:38.931  4827  5070 D BtGatt.GattService: [GSIM LOG]: reportData, LAT: com.rockwellautomation.thalitest@LowLatency
05-19 09:21:38.931  4827  5070 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.rockwellautomation.thalitest@LowLatency : 24919641
,05-19 09:21:38.931  3511  4422 V AlarmManager:  remove PendingIntent] PendingIntent{357c022: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:38.931  4827  4974 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,05-19 09:21:38.941  4827  5046 D BtGatt.AdvertiseManager: starting multi advertising
,05-19 09:21:38.941  3511  4459 V AlarmManager:  remove PendingIntent] PendingIntent{5335ab3: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:38.941  4827  4974 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,05-19 09:21:38.941  4827  5046 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,05-19 09:21:38.941  4827  5046 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
05-19 09:21:38.941  4827  5046 D BtGatt.AdvertiseManager: postCallback clientIf = 7 status = 0
05-19 09:21:38.941  4827  5046 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=7, status=0, isStart=true
,05-19 09:21:38.941  9689  9699 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
05-19 09:21:38.941  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:38.941  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:38.941  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
05-19 09:21:38.941  3511  3528 V AlarmManager:  remove PendingIntent] PendingIntent{5f25870: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:38.941  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:38.941  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:38.941  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:38.941  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:38.941  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:38.941  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
05-19 09:21:38.941  4827  5070 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.rockwellautomation.thalitest : 1
05-19 09:21:38.941  4827  5070 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
,05-19 09:21:38.951  4827  5070 D BtGatt.GattService: [GSIM LOG]: com.rockwellautomation.thalitest@LowLatency, R time : 0 => 0
,05-19 09:21:38.951  9689  9753 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
05-19 09:21:38.951  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-135,7,main], id: 135
,05-19 09:21:38.951  3511  4847 V AlarmManager:  remove PendingIntent] PendingIntent{5c1f7e9: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:38.951  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:38.951  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:38.951  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-135,7,main], id: 135
,05-19 09:21:38.951  9689  9753 I io.jxcore.node.ConnectionHelper: start: OK
,05-19 09:21:38.951  9689  9689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
05-19 09:21:38.951  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
05-19 09:21:38.951  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
05-19 09:21:38.951  3511  4407 V AlarmManager:  remove PendingIntent] PendingIntent{455bc6e: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:38.951  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
05-19 09:21:38.951  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
05-19 09:21:38.951  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
05-19 09:21:38.951  9689  9689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
05-19 09:21:38.951  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
05-19 09:21:38.951  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
05-19 09:21:38.951  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,05-19 09:21:38.961  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,05-19 09:21:38.961  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
05-19 09:21:38.961  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
05-19 09:21:38.961  9689  9689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
05-19 09:21:38.961  9689  9689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
05-19 09:21:38.961  3511  4459 V AlarmManager:  remove PendingIntent] PendingIntent{2feef0f: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:38.961  9689  9689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
05-19 09:21:38.961  9689  9689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,05-19 09:21:38.961  9689  9689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
05-19 09:21:38.961  9689  9689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
05-19 09:21:38.961  9689  9689 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,05-19 09:21:38.961  3511  3528 V AlarmManager:  remove PendingIntent] PendingIntent{7fc8b9c: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:39.091  3511  4198 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-19 09:21:39.091  3511  4198 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4327, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-19 09:21:39.091  3511  4198 D BatteryService: online:4, current avg:13, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:4
05-19 09:21:39.091  3511  3511 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-19 09:21:39.091  3511  3511 I MotionRecognitionService: Plugged
,05-19 09:21:39.091  3511  3511 D MotionRecognitionService:   cableConnection= 1
05-19 09:21:39.091  3511  3511 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-19 09:21:39.091  3511  3511 D MotionRecognitionService: skip setTransmitPower. 
,05-19 09:21:39.101  3511  3860 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-19 09:21:39.101  3939  3939 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,05-19 09:21:39.101  3939  3939 D KeyguardUpdateMonitor: handleBatteryUpdate
,05-19 09:21:39.101  3939  3939 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-19 09:21:39.111  3939  3939 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
05-19 09:21:39.111  3939  3939 D PowerUI.Notification: There is no change about charging status, so return!
,05-19 09:21:39.121  4867  4867 D CommonServiceConfiguration: getStringValueSetting
,05-19 09:21:39.131  4827  4827 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-19 09:21:39.131  4827  5228 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-19 09:21:39.131  4867  4867 D BatteryMonitor: new battery level: 100
,05-19 09:21:39.151  3939  3939 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,05-19 09:21:39.151  3939  3939 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,05-19 09:21:39.451  9689  9760 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,05-19 09:21:39.461  9689  9753 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
05-19 09:21:39.461  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [00:11:22:33:44:55]
05-19 09:21:39.461  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [10:010:010:010:010:010]
05-19 09:21:39.461  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [11:110:110:110:110:110]
05-19 09:21:39.461  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [12:210:210:210:210:210]
05-19 09:21:39.461  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [13:310:310:310:310:310]
05-19 09:21:39.461  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [14:410:410:410:410:410]
05-19 09:21:39.461  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [15:510:510:510:510:510]
05-19 09:21:39.461  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [16:610:610:610:610:610]
05-19 09:21:39.461  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [17:710:710:710:710:710]
05-19 09:21:39.461  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [18:810:810:810:810:810]
05-19 09:21:39.461  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [19:910:910:910:910:910]
05-19 09:21:39.461  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [20:1010:1010:1010:1010:1010]
05-19 09:21:39.461  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [21:1110:1110:1110:1110:1110]
05-19 09:21:39.461  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [22:1210:1210:1210:1210:1210]
05-19 09:21:39.461  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [23:1310:1310:1310:1310:1310]
05-19 09:21:39.461  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [24:1410:1410:1410:1410:1410]
05-19 09:21:39.461  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [25:1510:1510:1510:1510:1510]
05-19 09:21:39.461  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [26:1610:1610:1610:1610:1610]
05-19 09:21:39.461  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [27:1710:1710:1710:1710:1710]
05-19 09:21:39.461  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [28:1810:1810:1810:1810:1810]
05-19 09:21:39.461  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [29:1910:1910:1910:1910:1910]
05-19 09:21:39.461  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [30:2010:2010:2010:2010:2010]
05-19 09:21:39.461  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [31:2110:2110:2110:2110:2110]
05-19 09:21:39.461  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [32:2210:2210:2210:2210:2210]
05-19 09:21:39.461  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [33:2310:2310:2310:2310:2310]
05-19 09:21:39.461  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [34:2410:2410:2410:2410:2410]
05-19 09:21:39.461  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [35:2510:2510:2510:2510:2510]
05-19 09:21:39.461  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [36:2610:2610:2610:2610:2610]
05-19 09:21:39.461  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [37:2,710:2710:2710:2710:2710]
05-19 09:21:39.461  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [38:2810:2810:2810:2810:2810]
05-19 09:21:39.461  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [39:2910:2910:2910:2910:2910]
05-19 09:21:39.461  9689  9753 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
05-19 09:21:39.461  9689  9753 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
05-19 09:21:39.461  9689  9753 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
05-19 09:21:39.461  9689  9753 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
05-19 09:21:39.461  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
05-19 09:21:39.461  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
05-19 09:21:39.461  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
05-19 09:21:39.461  9689  9753 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
05-19 09:21:39.461  9689  9753 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,05-19 09:21:39.461  9689  9753 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
05-19 09:21:39.461  9689  9753 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
05-19 09:21:39.461  9689  9758 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
05-19 09:21:39.461  9689  9758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
05-19 09:21:39.461  9689  9758 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,05-19 09:21:39.461  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:39.461  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
05-19 09:21:39.461  9689  9689 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
05-19 09:21:39.461  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
05-19 09:21:39.461  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-135,7,main], id: 135
,05-19 09:21:39.461  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:39.471  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:39.471  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:39.471  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:21:39.471  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:21:39.471  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,05-19 09:21:39.481  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:21:39.481  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:21:39.481  9689  9753 D BluetoothLeScanner: could not find callback wrapper
05-19 09:21:39.481  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
05-19 09:21:39.481  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:39.481  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:39.481  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-135,7,main], id: 135
,05-19 09:21:39.481  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
05-19 09:21:39.481  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-135,7,main], id: 135
,05-19 09:21:39.491  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:21:39.491  9689  9753 D BluetoothAdapter: STATE_ON
05-19 09:21:39.491  9689  9753 D BluetoothLeAdvertiser: stop advertising
,05-19 09:21:39.501  4827  5441 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
,05-19 09:21:39.501  4827  5441 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
05-19 09:21:39.501  4827  5046 D BtGatt.AdvertiseManager: message : 1
05-19 09:21:39.501  4827  5070 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.rockwellautomation.thalitest, msg: MESSAGE_STOP_ADV
,05-19 09:21:39.501  4827  5070 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 19, currDate: 19
05-19 09:21:39.511  4827  5070 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
05-19 09:21:39.511  4827  5070 D BtGatt.GattService: [GSIM LOG]: com.rockwellautomation.thalitest@LowLatency, R time : 0 => 0
,05-19 09:21:39.511  4827  5046 D BtGatt.AdvertiseManager: stop advertise for client =  7
05-19 09:21:39.511  4827  5070 D BtGatt.GattService: [GSIM LOG]: remove : com.rockwellautomation.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
05-19 09:21:39.511  4827  5046 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 7
,05-19 09:21:39.511  4827  5046 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,05-19 09:21:39.511  4827  4974 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,05-19 09:21:39.511  4827  4974 D BtGatt.GattService: Client app is not null!
05-19 09:21:39.511  3511  4459 V AlarmManager:  remove PendingIntent] PendingIntent{fb929a5: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:39.511  9689  9699 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,05-19 09:21:39.521  4827  5227 D BtGatt.GattService: unregisterClient() - clientIf=7
,05-19 09:21:39.521  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,05-19 09:21:39.521  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:39.521  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
05-19 09:21:39.521  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-135,7,main], id: 135
,05-19 09:21:39.521  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:39.521  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:39.521  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,05-19 09:21:39.521  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,05-19 09:21:39.531  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
05-19 09:21:39.531  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-135,7,main], id: 135
,05-19 09:21:39.531  3511  4847 V AlarmManager:  remove PendingIntent] PendingIntent{725317a: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:39.531  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-135,7,main], id: 135
,05-19 09:21:39.531  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
05-19 09:21:39.531  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-135,7,main], id: 135
,05-19 09:21:39.531  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:39.531  9689  9689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
05-19 09:21:39.531  9689  9689 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,05-19 09:21:39.541  9689  9689 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,05-19 09:21:39.541  9689  9689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
05-19 09:21:39.541  9689  9689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
05-19 09:21:39.541  9689  9689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
05-19 09:21:39.541  9689  9689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
05-19 09:21:39.541  9689  9689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
05-19 09:21:39.541  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
05-19 09:21:39.541  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
05-19 09:21:39.541  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
05-19 09:21:39.541  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
05-19 09:21:39.541  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
05-19 09:21:39.541  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
05-19 09:21:39.541  9689  9763 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
05-19 09:21:39.541  9689  9689 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
05-19 09:21:39.541  9689  9753 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
05-19 09:21:39.541  9689  9753 V io.jxcore.node.ConnectivityMonitor: start: Already started
05-19 09:21:39.541  9689  9753 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
05-19 09:21:39.541  9689  9753 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
05-19 09:21:39.541  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
05-19 09:21:39.541  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":1,"address":"A8:81:95:E9:5F:6F"}
05-19 09:21:39.541  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":1,"address":"A8:81:95:E9:5F:6F"}
05-19 09:21:39.541  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:39.541  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,05-19 09:21:39.551  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":1,"address":"A8:81:95:E9:5F:6F"}
05-19 09:21:39.551  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":1,"address":"A8:81:95:E9:5F:6F"}
05-19 09:21:39.551  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-135,7,main], id: 135
,05-19 09:21:39.551  9689  9753 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
05-19 09:21:39.551  3511  4451 V AlarmManager:  remove PendingIntent] PendingIntent{e456d2b: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:39.551  9689  9753 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
05-19 09:21:39.551  9689  9753 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
05-19 09:21:39.551  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
05-19 09:21:39.551  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
05-19 09:21:39.551  9689  9753 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
05-19 09:21:39.551  9689  9753 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
05-19 09:21:39.551  9689  9753 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,05-19 09:21:39.551  9689  9753 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
05-19 09:21:39.551  9689  9753 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,05-19 09:21:39.551  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
05-19 09:21:39.551  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
05-19 09:21:39.551  9689  9764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,05-19 09:21:39.561  9689  9689 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,05-19 09:21:39.561  9689  9764 D BluetoothSocket: bindListen(): myUserId = 0
,05-19 09:21:39.561  9689  9764 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,05-19 09:21:39.561  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,05-19 09:21:39.561  9689  9753 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
05-19 09:21:39.561  9689  9753 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,05-19 09:21:39.561  3511  3852 V AlarmManager:  remove PendingIntent] PendingIntent{32bb107: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:39.561  9689  9764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
,05-19 09:21:39.561  9689  9764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@fda0f73, port: 6, type: 1, local socket address: null, socket type: 0
05-19 09:21:39.571  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:21:39.571  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:21:39.571  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:21:39.571  3511  4343 V AlarmManager:  remove PendingIntent] PendingIntent{bf4b234: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:39.571  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-135,7,main], id: 135
,05-19 09:21:39.571  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,05-19 09:21:39.571  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:21:39.571  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:21:39.571  3511  3529 V AlarmManager:  remove PendingIntent] PendingIntent{db3e85d: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:39.571  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,05-19 09:21:39.571  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
05-19 09:21:39.571  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 1
,05-19 09:21:39.581  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:21:39.581  3511  4449 V AlarmManager:  remove PendingIntent] PendingIntent{b5475d2: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:39.581  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-135,7,main], id: 135
,05-19 09:21:39.581  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:39.581  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
05-19 09:21:39.581  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
,05-19 09:21:39.581  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b1b48b8e-977b-494d-8afb-10acf9d32846", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
05-19 09:21:39.581  9689  9753 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 A8 81 95 E9 5F 6F
05-19 09:21:39.581  9689  9753 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b1b48b8e-977b-494d-8afb-10acf9d32846], mManufacturerSpecificData={}, mServiceData={b1b48b8e-977b-494d-8afb-10acf9d32846=[1, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-19 09:21:39.581  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b1b48b8e-977b-494d-8afb-10acf9d32846], mManufacturerSpecificData={}, mServiceData={b1b48b8e-977b-494d-8afb-10acf9d32846=[1, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-19 09:21:39.581  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:39.581  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b1b48b8e-977b-494d-8afb-10acf9d32846], mManufacturerSpecificData={}, mServiceData={b1b48b8e-977b-494d-8afb-10acf9d32846=[1, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-135,7,main], id: 135
,05-19 09:21:39.581  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
05-19 09:21:39.581  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b1b48b8e-977b-494d-8afb-10acf9d32846], mManufacturerSpecificData={}, mServiceData={b1b48b8e-977b-494d-8afb-10acf9d32846=[1, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-19 09:21:39.581  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:39.581  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:39.581  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[b1b48b8e-977b-494d-8afb-10acf9d32846], mManufacturerSpecificData={}, mServiceData={b1b48b8e-977b-494d-8afb-10acf9d32846=[1, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:39.581  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:21:39.581  3511  4451 V AlarmManager:  remove PendingIntent] PendingIntent{14856a3: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:39.581  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:21:39.581  9689  9753 D BluetoothLeAdvertiser: start advertising
,05-19 09:21:39.591  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:21:39.591  4827  5227 D BtGatt.GattService: registerClient() - UUID=e107195b-da51-449c-98ff-2998370335d1
,05-19 09:21:39.631  4827  4974 D BtGatt.GattService: onClientRegistered() - UUID=e107195b-da51-449c-98ff-2998370335d1, clientIf=7
,05-19 09:21:39.631  9689  9699 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,05-19 09:21:39.631  4827  4839 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,05-19 09:21:39.641  4827  4839 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
05-19 09:21:39.641  4827  4839 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
05-19 09:21:39.641  4827  5046 D BtGatt.AdvertiseManager: message : 0
05-19 09:21:39.641  4827  5070 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.rockwellautomation.thalitest, msg: MESSAGE_START_ADV
,05-19 09:21:39.641  4827  5070 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 19, currDate: 19
05-19 09:21:39.641  4827  5046 D BtGatt.AdvertiseManager: number of adv instance running = 0
05-19 09:21:39.641  4827  5046 D BtGatt.AdvertiseManager: size of list is =0
,05-19 09:21:39.641  4827  5046 D BtGatt.AdvertiseManager: starting advertising
,05-19 09:21:39.641  4827  5046 D BtGatt.AdvertiseManager: isStandardAdv = false
,05-19 09:21:39.651  4827  5070 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.rockwellautomation.thalitest : 2
,05-19 09:21:39.651  3511  4407 V AlarmManager:  remove PendingIntent] PendingIntent{b44bda0: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:39.651  4827  5070 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.rockwellautomation.thalitest@LowLatency : 24919641
05-19 09:21:39.651  4827  5070 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.rockwellautomation.thalitest@LowLatency : 2
05-19 09:21:39.651  4827  5070 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
05-19 09:21:39.651  4827  5070 D BtGatt.GattService: [GSIM LOG]: com.rockwellautomation.thalitest@LowLatency, R time : 0 => 0
,05-19 09:21:39.651  3511  4185 V AlarmManager:  remove PendingIntent] PendingIntent{7cbad59: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:39.681  3511  3528 V AlarmManager:  remove PendingIntent] PendingIntent{c601d1e: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:39.681  4827  4974 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,05-19 09:21:39.681  4827  5046 D BtGatt.AdvertiseManager: starting multi advertising
,05-19 09:21:39.681  4827  4974 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,05-19 09:21:39.681  4827  5046 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
05-19 09:21:39.681  4827  5046 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
05-19 09:21:39.681  3511  4198 V AlarmManager:  remove PendingIntent] PendingIntent{ffb9ff: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:39.681  4827  5046 D BtGatt.AdvertiseManager: postCallback clientIf = 7 status = 0
05-19 09:21:39.681  4827  5046 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=7, status=0, isStart=true
05-19 09:21:39.681  9689  9700 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
05-19 09:21:39.681  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:39.681  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:39.681  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
05-19 09:21:39.681  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:39.681  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:39.681  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:39.681  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:39.681  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:39.681  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
05-19 09:21:39.681  9689  9753 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
05-19 09:21:39.681  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:39.681  9689  9753 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: seems that updateState call different BlePeerDiscoverer
,05-19 09:21:39.691  3511  4407 V AlarmManager:  remove PendingIntent] PendingIntent{1c813cc: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:39.691  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:39.691  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:39.691  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-135,7,main], id: 135
,05-19 09:21:39.691  9689  9753 I io.jxcore.node.ConnectionHelper: start: OK
05-19 09:21:39.691  9689  9689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
05-19 09:21:39.691  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
05-19 09:21:39.691  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
05-19 09:21:39.691  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
05-19 09:21:39.691  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
,05-19 09:21:39.691  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
05-19 09:21:39.691  9689  9689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
05-19 09:21:39.691  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
05-19 09:21:39.691  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
,05-19 09:21:39.691  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
05-19 09:21:39.691  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
05-19 09:21:39.691  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
05-19 09:21:39.691  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
05-19 09:21:39.691  9689  9689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
05-19 09:21:39.691  3511  4847 V AlarmManager:  remove PendingIntent] PendingIntent{400c615: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:39.691  9689  9689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,05-19 09:21:39.691  9689  9689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,05-19 09:21:39.691  9689  9689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
05-19 09:21:39.691  9689  9689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
05-19 09:21:39.691  9689  9689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
05-19 09:21:39.691  9689  9689 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,05-19 09:21:39.691  3511  4422 V AlarmManager:  remove PendingIntent] PendingIntent{9eced2a: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:39.701  3511  4459 V AlarmManager:  remove PendingIntent] PendingIntent{29ff71b: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:39.901  3511  6156 D SSRM:n  : SIOP:: AP = 320, PST = 306 (W:14), CP = 261, CUR = 13, LCD = 30
,05-19 09:21:40.201  9689  9766 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,05-19 09:21:40.201  9689  9753 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
,05-19 09:21:40.201  9689  9753 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
05-19 09:21:40.201  9689  9753 V io.jxcore.node.ConnectivityMonitor: start: Already started
05-19 09:21:40.201  9689  9753 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,05-19 09:21:40.201  9689  9753 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
05-19 09:21:40.201  9689  9689 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
05-19 09:21:40.201  9689  9753 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
05-19 09:21:40.201  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,05-19 09:21:40.201  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":2,"address":"A8:81:95:E9:5F:6F"}
,05-19 09:21:40.211  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":2,"address":"A8:81:95:E9:5F:6F"}
05-19 09:21:40.211  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:40.211  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,05-19 09:21:40.211  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":2,"address":"A8:81:95:E9:5F:6F"}
,05-19 09:21:40.211  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":2,"address":"A8:81:95:E9:5F:6F"}
05-19 09:21:40.211  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:40.211  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
05-19 09:21:40.211  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 13612
05-19 09:21:40.211  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
05-19 09:21:40.211  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 2
05-19 09:21:40.211  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
05-19 09:21:40.211  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
05-19 09:21:40.211  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
05-19 09:21:40.211  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
05-19 09:21:40.211  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
05-19 09:21:40.211  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-135,7,main], id: 135
,05-19 09:21:40.211  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 2
05-19 09:21:40.211  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted true Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:40.211  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop advertiser Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:40.211  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:40.221  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:21:40.221  9689  9753 D BluetoothAdapter: STATE_ON
05-19 09:21:40.221  9689  9753 D BluetoothLeAdvertiser: stop advertising
,05-19 09:21:40.231  4827  5441 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
,05-19 09:21:40.231  4827  5441 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
05-19 09:21:40.231  4827  5046 D BtGatt.AdvertiseManager: message : 1
05-19 09:21:40.231  4827  5070 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.rockwellautomation.thalitest, msg: MESSAGE_STOP_ADV
05-19 09:21:40.231  4827  5070 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 19, currDate: 19
05-19 09:21:40.231  4827  5070 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
05-19 09:21:40.231  4827  5070 D BtGatt.GattService: [GSIM LOG]: com.rockwellautomation.thalitest@LowLatency, R time : 0 => 0
,05-19 09:21:40.231  4827  5070 D BtGatt.GattService: [GSIM LOG]: remove : com.rockwellautomation.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
05-19 09:21:40.231  4827  5046 D BtGatt.AdvertiseManager: stop advertise for client =  7
05-19 09:21:40.231  4827  5046 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 7
,05-19 09:21:40.231  4827  5046 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,05-19 09:21:40.231  3511  3852 V AlarmManager:  remove PendingIntent] PendingIntent{548a0b8: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:40.231  4827  4974 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,05-19 09:21:40.231  4827  4974 D BtGatt.GattService: Client app is not null!
05-19 09:21:40.231  9689  9747 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,05-19 09:21:40.241  4827  4840 D BtGatt.GattService: unregisterClient() - clientIf=7
,05-19 09:21:40.241  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
05-19 09:21:40.241  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:40.241  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
05-19 09:21:40.241  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:40.241  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:40.241  3511  4198 V AlarmManager:  remove PendingIntent] PendingIntent{734ae91: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:40.241  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:40.241  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
05-19 09:21:40.241  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:40.241  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:40.241  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:40.241  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
05-19 09:21:40.241  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
,05-19 09:21:40.241  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b1b48b8e-977b-494d-8afb-10acf9d32846", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
05-19 09:21:40.241  9689  9753 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 A8 81 95 E9 5F 6F
05-19 09:21:40.241  9689  9753 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b1b48b8e-977b-494d-8afb-10acf9d32846], mManufacturerSpecificData={}, mServiceData={b1b48b8e-977b-494d-8afb-10acf9d32846=[2, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-19 09:21:40.241  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b1b48b8e-977b-494d-8afb-10acf9d32846], mManufacturerSpecificData={}, mServiceData={b1b48b8e-977b-494d-8afb-10acf9d32846=[2, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-19 09:21:40.241  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-135,7,main], id: 135
,05-19 09:21:40.241  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b1b48b8e-977b-494d-8afb-10acf9d32846], mManufacturerSpecificData={}, mServiceData={b1b48b8e-977b-494d-8afb-10acf9d32846=[2, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:40.241  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
05-19 09:21:40.241  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b1b48b8e-977b-494d-8afb-10acf9d32846], mManufacturerSpecificData={}, mServiceData={b1b48b8e-977b-494d-8afb-10acf9d32846=[2, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-19 09:21:40.241  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:40.241  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:40.241  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[b1b48b8e-977b-494d-8afb-10acf9d32846], mManufacturerSpecificData={}, mServiceData={b1b48b8e-977b-494d-8afb-10acf9d32846=[2, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-135,7,main], id: 135
,05-19 09:21:40.241  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:21:40.251  9689  9753 D BluetoothAdapter: STATE_ON
05-19 09:21:40.251  3511  4407 V AlarmManager:  remove PendingIntent] PendingIntent{3c4b1f6: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:40.251  9689  9753 D BluetoothLeAdvertiser: start advertising
,05-19 09:21:40.251  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:21:40.251  3511  4198 V AlarmManager:  remove PendingIntent] PendingIntent{33ce9f7: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:40.251  4827  5441 D BtGatt.GattService: registerClient() - UUID=63bec2b1-f83b-45c7-a63a-74bde075f0e4
,05-19 09:21:40.261  3511  4459 V AlarmManager:  remove PendingIntent] PendingIntent{c431064: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:40.261  3511  4185 V AlarmManager:  remove PendingIntent] PendingIntent{8e4a2cd: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:40.271  3511  4070 V AlarmManager:  remove PendingIntent] PendingIntent{a81f782: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:40.271  3511  3529 V AlarmManager:  remove PendingIntent] PendingIntent{34c2e93: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:40.301  4827  4974 D BtGatt.GattService: onClientRegistered() - UUID=63bec2b1-f83b-45c7-a63a-74bde075f0e4, clientIf=7
,05-19 09:21:40.301  9689  9699 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,05-19 09:21:40.301  4827  4840 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,05-19 09:21:40.301  4827  4840 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
05-19 09:21:40.301  4827  4840 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
,05-19 09:21:40.301  4827  5046 D BtGatt.AdvertiseManager: message : 0
05-19 09:21:40.301  4827  5070 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.rockwellautomation.thalitest, msg: MESSAGE_START_ADV
05-19 09:21:40.301  4827  5070 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 19, currDate: 19
05-19 09:21:40.301  4827  5046 D BtGatt.AdvertiseManager: number of adv instance running = 0
,05-19 09:21:40.301  4827  5046 D BtGatt.AdvertiseManager: size of list is =0
,05-19 09:21:40.311  4827  5046 D BtGatt.AdvertiseManager: starting advertising
,05-19 09:21:40.311  4827  5046 D BtGatt.AdvertiseManager: isStandardAdv = false
,05-19 09:21:40.311  4827  5070 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.rockwellautomation.thalitest : 3
,05-19 09:21:40.311  4827  5070 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.rockwellautomation.thalitest@LowLatency : 24919641
05-19 09:21:40.311  4827  5070 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.rockwellautomation.thalitest@LowLatency : 2
05-19 09:21:40.311  4827  5070 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
05-19 09:21:40.311  4827  5070 D BtGatt.GattService: [GSIM LOG]: com.rockwellautomation.thalitest@LowLatency, R time : 0 => 0
,05-19 09:21:40.321  3511  4313 V AlarmManager:  remove PendingIntent] PendingIntent{652ced0: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:40.321  4827  4974 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
05-19 09:21:40.321  4827  5046 D BtGatt.AdvertiseManager: starting multi advertising
,05-19 09:21:40.321  3511  4451 V AlarmManager:  remove PendingIntent] PendingIntent{1259ec9: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:40.321  4827  4974 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,05-19 09:21:40.331  4827  5046 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
05-19 09:21:40.331  4827  5046 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
05-19 09:21:40.331  4827  5046 D BtGatt.AdvertiseManager: postCallback clientIf = 7 status = 0
05-19 09:21:40.331  4827  5046 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=7, status=0, isStart=true
05-19 09:21:40.331  9689  9700 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
05-19 09:21:40.331  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:40.331  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:40.331  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
05-19 09:21:40.331  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:40.331  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:40.331  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:40.331  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:40.331  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:40.331  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser started = true Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:40.331  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
05-19 09:21:40.331  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted false Current thread: Thread[Thread-135,7,main], id: 135
,05-19 09:21:40.331  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
05-19 09:21:40.331  3511  4343 V AlarmManager:  remove PendingIntent] PendingIntent{bdc09ce: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:40.331  9689  9753 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
05-19 09:21:40.331  9689  9753 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
05-19 09:21:40.331  9689  9753 I io.jxcore.node.ConnectionHelper: start: OK
05-19 09:21:40.331  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
05-19 09:21:40.331  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
05-19 09:21:40.331  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
05-19 09:21:40.331  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
05-19 09:21:40.331  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
05-19 09:21:40.331  9689  9689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
05-19 09:21:40.331  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,05-19 09:21:40.331  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
05-19 09:21:40.331  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
05-19 09:21:40.331  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
05-19 09:21:40.331  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
05-19 09:21:40.331  9689  9768 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
05-19 09:21:40.331  9689  9753 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
05-19 09:21:40.331  9689  9753 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
05-19 09:21:40.331  9689  9753 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
05-19 09:21:40.331  9689  9753 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
05-19 09:21:40.331  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
05-19 09:21:40.331  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
05-19 09:21:40.331  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
05-19 09:21:40.331  9689  9753 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
05-19 09:21:40.331  9689  9753 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
05-19 09:21:40.331  9689  9753 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
05-19 09:21:40.341  3511  4313 V AlarmManager:  remove PendingIntent] PendingIntent{b0120ef: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:40.331  9689  9753 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
05-19 09:21:40.331  9689  9689 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
05-19 09:21:40.331  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:40.331  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
05-19 09:21:40.331  9689  9764 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
05-19 09:21:40.331  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
05-19 09:21:40.331  9689  9764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
05-19 09:21:40.331  9689  9764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
05-19 09:21:40.331  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:40.331  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:40.331  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:40.331  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:40.331  9689  9753 D BluetoothAdapter: STATE_ON
05-19 09:21:40.331  9689  9753 D BluetoothAdapter: STATE_ON
05-19 09:21:40.331  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
05-19 09:21:40.341  9689  9753 D BluetoothAdapter: STATE_ON
05-19 09:21:40.341  9689  9753 D BluetoothAdapter: STATE_ON
05-19 09:21:40.341  9689  9753 D BluetoothLeScanner: could not find callback wrapper
05-19 09:21:40.341  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
05-19 09:21:40.341  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:40.341  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:40.341  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:40.341  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
05-19 09:21:40.341  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:40.341  3511  4343 V AlarmManager:  remove PendingIntent] PendingIntent{f5e07fc: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:40.341  9689  9753 D BluetoothAdapter: STATE_ON
05-19 09:21:40.341  9689  9753 D BluetoothAdapter: STATE_ON
05-19 09:21:40.341  9689  9753 D BluetoothLeAdvertiser: stop advertising
05-19 09:21:40.351  4827  4839 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
05-19 09:21:40.351  4827  4839 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
05-19 09:21:40.351  4827  5070 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.rockwellautomation.thalitest, msg: MESSAGE_STOP_ADV
05-19 09:21:40.351  4827  5070 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 19, currDate: 19
05-19 09:21:40.351  4827  5070 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
05-19 09:21:40.351  4827  5070 D BtGatt.GattService: [GSIM LOG]: com.rockwellautomation.thalitest@LowLatency, R time : 0 => 0
05-19 09:21:40.351  4827  5070 D BtGatt.GattService: [GSIM LOG]: remove : com.rockwellautomation.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
05-19 09:21:40.351  3511  3984 V AlarmManager:  remove PendingIntent] PendingIntent{a605e85: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:40.351  4827  5046 D BtGatt.AdvertiseManager: message : 1
05-19 09:21:40.351  4827  5046 D BtGatt.AdvertiseManager: stop advertise for client =  7
05-19 09:21:40.351  4827  5046 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 7
05-19 09:21:40.351  4827  5046 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
05-19 09:21:40.351  3511  3529 V AlarmManager:  remove PendingIntent] PendingIntent{7b2f4da: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:40.361  4827  4974 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
05-19 09:21:40.361  4827  4974 D BtGatt.GattService: Client app is not null!
05-19 09:21:40.361  9689  9747 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
05-19 09:21:40.361  4827  5441 D BtGatt.GattService: unregisterClient() - clientIf=7
05-19 09:21:40.361  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
05-19 09:21:40.361  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:40.361  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
05-19 09:21:40.361  3511  4459 V AlarmManager:  remove PendingIntent] PendingIntent{868dd0b: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:40.361  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:40.361  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:40.361  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:40.361  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
05-19 09:21:40.361  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
05-19 09:21:40.361  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
05-19 09:21:40.361  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:40.361  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:40.361  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
05-19 09:21:40.361  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:40.361  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:40.361  9689  9689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
05-19 09:21:40.361  9689  9689 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
05-19 09:21:40.361  9689  9689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
05-19 09:21:40.361  9689  9689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
05-19 09:21:40.361  9689  9689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
05-19 09:21:40.361  3511  4070 V AlarmManager:  remove PendingIntent] PendingIntent{981a7e8: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:40.361  9689  9689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
05-19 09:21:40.361  9689  9689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
05-19 09:21:40.361  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
05-19 09:21:40.361  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
05-19 09:21:40.361  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
05-19 09:21:40.361  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
05-19 09:21:40.361  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
05-19 09:21:40.361  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
05-19 09:21:40.361  9689  9689 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
05-19 09:21:40.371  9689  9769 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
05-19 09:21:40.371  9689  9753 I io.jxcore.node.ConnectionHelperTest: Starting test: testListenToConnectivityChanges
05-19 09:21:40.371  9689  9753 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
05-19 09:21:40.371  9689  9753 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@84c3865 added. We now have 3 listener(s)
05-19 09:21:40.371  9689  9753 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@84c3865 added. We now have 5 listener(s)
05-19 09:21:40.371  9689  9753 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
05-19 09:21:40.371  3511  4313 V AlarmManager:  remove PendingIntent] PendingIntent{2cd5e01: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:40.371  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":2,"address":"A8:81:95:E9:5F:6F"}
05-19 09:21:40.371  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
05-19 09:21:40.371  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":2,"address":"A8:81:95:E9:5F:6F"}
05-19 09:21:40.371  9689  9753 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
05-19 09:21:40.371  9689  9753 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4c0f93a added. We now have 6 listener(s)
05-19 09:21:40.371  9689  9753 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
05-19 09:21:40.371  9689  9753 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
05-19 09:21:40.371  3511  4198 V AlarmManager:  remove PendingIntent] PendingIntent{9db84a6: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:40.381  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
05-19 09:21:40.381  3511  4422 V AlarmManager:  remove PendingIntent] PendingIntent{4ab4532: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:40.381  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:21:40.381  3511  4343 V AlarmManager:  remove PendingIntent] PendingIntent{2ade283: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:40.391  9689  9753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
05-19 09:21:40.391  9689  9753 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-19 09:21:40.391  9689  9753 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-19 09:21:40.391  9689  9753 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-19 09:21:40.391  9689  9753 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-19 09:21:40.391  9689  9753 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-19 09:21:40.391  9689  9753 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-19 09:21:40.391  9689  9753 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-19 09:21:40.391  9689  9753 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,05-19 09:21:40.391  9689  9753 D io.jxcore.node.ConnectivityMonitor: start: OK
,05-19 09:21:40.391  3511  4185 V AlarmManager:  remove PendingIntent] PendingIntent{35f8c00: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:40.391  9689  9753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-19 09:21:40.391  3511  3982 V AlarmManager:  remove PendingIntent] PendingIntent{456cc39: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:40.391  9689  9689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-19 09:21:40.401  3511  3852 V AlarmManager:  remove PendingIntent] PendingIntent{844827e: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:40.401  9689  9689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-19 09:21:40.401  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:21:40.411  9689  9753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
05-19 09:21:40.411  9689  9753 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-19 09:21:40.411  9689  9753 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-19 09:21:40.411  9689  9753 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-19 09:21:40.411  9689  9753 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-19 09:21:40.411  9689  9753 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-19 09:21:40.411  9689  9753 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-19 09:21:40.411  9689  9753 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-19 09:21:40.411  9689  9753 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,05-19 09:21:40.411  9689  9753 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
05-19 09:21:40.411  9689  9753 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
05-19 09:21:40.411  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
05-19 09:21:40.411  9689  9753 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,05-19 09:21:40.411  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
05-19 09:21:40.411  9689  9753 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@84c3865 removed from the list
05-19 09:21:40.411  9689  9753 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@84c3865 removed from the list
05-19 09:21:40.411  9689  9753 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,05-19 09:21:40.411  9689  9753 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4c0f93a removed from the list
,05-19 09:21:40.411  9689  9689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-19 09:21:40.411  9689  9753 D io.jxcore.node.ConnectivityMonitor: stop
05-19 09:21:40.411  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,05-19 09:21:40.411  9689  9753 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
,05-19 09:21:40.411  9689  9753 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,05-19 09:21:40.411  9689  9753 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
,05-19 09:21:40.411  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [incoming]
,05-19 09:21:40.411  9689  9753 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
,05-19 09:21:40.411  9689  9753 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,05-19 09:21:40.421  9689  9753 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
05-19 09:21:40.421  9689  9753 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,05-19 09:21:40.421  9689  9753 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
05-19 09:21:40.421  9689  9753 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,05-19 09:21:40.421  9689  9753 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
05-19 09:21:40.421  9689  9753 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
05-19 09:21:40.421  9689  9753 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
05-19 09:21:40.421  9689  9753 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
05-19 09:21:40.421  9689  9753 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,05-19 09:21:40.421  9689  9753 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
05-19 09:21:40.421  9689  9753 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
05-19 09:21:40.421  9689  9753 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
05-19 09:21:40.421  9689  9753 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
,05-19 09:21:40.421  9689  9753 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
05-19 09:21:40.421  9689  9753 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
05-19 09:21:40.421  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [00:11:22:33:44:55]
05-19 09:21:40.421  9689  9753 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,05-19 09:21:40.421  9689  9753 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,05-19 09:21:40.421  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [10:010:010:010:010:010]
05-19 09:21:40.421  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [11:110:110:110:110:110]
05-19 09:21:40.421  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [12:210:210:210:210:210]
05-19 09:21:40.421  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [13:310:310:310:310:310]
05-19 09:21:40.421  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [14:410:410:410:410:410]
,05-19 09:21:40.421  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [15:510:510:510:510:510]
05-19 09:21:40.421  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [16:610:610:610:610:610]
05-19 09:21:40.421  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [17:710:710:710:710:710]
05-19 09:21:40.421  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [18:810:810:810:810:810]
05-19 09:21:40.421  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [19:910:910:910:910:910]
05-19 09:21:40.421  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [20:1010:1010:1010:1010:1010]
05-19 09:21:40.421  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [21:1110:1110:1110:1110:1110]
05-19 09:21:40.421  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [22:1210:1210:1210:1210:1210]
05-19 09:21:40.421  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [23:1310:1310:1310:1310:1310]
,05-19 09:21:40.421  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [24:1410:1410:1410:1410:1410]
05-19 09:21:40.421  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [25:1510:1510:1510:1510:1510]
05-19 09:21:40.421  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [26:1610:1610:1610:1610:1610]
05-19 09:21:40.421  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [27:1710:1710:1710:1710:1710]
05-19 09:21:40.421  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [28:1810:1810:1810:1810:1810]
05-19 09:21:40.421  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [29:1910:1910:1910:1910:1910]
05-19 09:21:40.421  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [30:2010:2010:2010:2010:2010]
,05-19 09:21:40.421  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [31:2110:2110:2110:2110:2110]
05-19 09:21:40.421  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [32:2210:2210:2210:2210:2210]
05-19 09:21:40.421  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [33:2310:2310:2310:2310:2310]
05-19 09:21:40.421  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [34:2410:2410:2410:2410:2410]
05-19 09:21:40.421  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [35:2510:2510:2510:2510:2510]
,05-19 09:21:40.421  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [36:2610:2610:2610:2610:2610]
05-19 09:21:40.421  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [37:2710:2710:2710:2710:2710]
05-19 09:21:40.421  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [38:2810:2810:2810:2810:2810]
05-19 09:21:40.421  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [39:2910:2910:2910:2910:2910]
05-19 09:21:40.421  9689  9753 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
05-19 09:21:40.421  9689  9753 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,05-19 09:21:40.421  9689  9753 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
05-19 09:21:40.421  9689  9753 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
05-19 09:21:40.421  9689  9753 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
05-19 09:21:40.421  9689  9753 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
05-19 09:21:40.421  9689  9753 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,05-19 09:21:40.421  9689  9753 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
05-19 09:21:40.421  9689  9753 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [00:11:22:33:44:55]
05-19 09:21:40.431  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
05-19 09:21:40.431  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port 1
,05-19 09:21:40.431  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,05-19 09:21:40.431  9689  9753 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
05-19 09:21:40.431  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
05-19 09:21:40.431  9689  9753 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,05-19 09:21:40.431  9689  9753 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
05-19 09:21:40.431  9689  9770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 207)
05-19 09:21:40.431  9689  9753 E io.jxcore.node.ConnectionHelper: connect: Callback is null
05-19 09:21:40.431  9689  9770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect: mIsShuttingDown = false
05-19 09:21:40.431  9689  9770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: createBluetoothSocket 1
05-19 09:21:40.431  9689  9770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: createBluetoothSocket: given port
,05-19 09:21:40.431  9689  9753 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
,05-19 09:21:40.431  9689  9753 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,05-19 09:21:40.431  9689  9753 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
05-19 09:21:40.431  9689  9753 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,05-19 09:21:40.431  9689  9753 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
,05-19 09:21:40.441  9689  9770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: createBluetoothSocketToServiceRecord: Socket created with channel/port 1
05-19 09:21:40.441  9689  9770 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  connect: connecting
,05-19 09:21:40.441  9689  9753 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
05-19 09:21:40.441  9689  9753 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
05-19 09:21:40.441  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
05-19 09:21:40.441  9689  9753 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
,05-19 09:21:40.441  9689  9753 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,05-19 09:21:40.441  9689  9753 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
05-19 09:21:40.441  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
05-19 09:21:40.441  9689  9753 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
,05-19 09:21:40.441  9689  9753 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
05-19 09:21:40.441  9689  9753 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
05-19 09:21:40.441  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
05-19 09:21:40.441  9689  9753 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
,05-19 09:21:40.441  9689  9753 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
,05-19 09:21:40.441  9689  9753 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
05-19 09:21:40.441  9689  9753 V io.jxcore.node.ConnectivityMonitor: start: Already started
05-19 09:21:40.441  9689  9753 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
05-19 09:21:40.441  9689  9753 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
05-19 09:21:40.441  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,05-19 09:21:40.441  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"A8:81:95:E9:5F:6F"}
,05-19 09:21:40.441  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"A8:81:95:E9:5F:6F"}
05-19 09:21:40.441  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:40.441  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
05-19 09:21:40.441  9689  9770 D BluetoothSocket: connect(): myUserId = 0
05-19 09:21:40.441  9689  9770 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,05-19 09:21:40.451  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"A8:81:95:E9:5F:6F"}
,05-19 09:21:40.451  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"A8:81:95:E9:5F:6F"}
05-19 09:21:40.451  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:40.451  9689  9753 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
05-19 09:21:40.451  9689  9753 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,05-19 09:21:40.451  9689  9753 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
05-19 09:21:40.451  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
05-19 09:21:40.451  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,05-19 09:21:40.451  9689  9753 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
05-19 09:21:40.451  9689  9753 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,05-19 09:21:40.451  9689  9753 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
05-19 09:21:40.451  9689  9753 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
05-19 09:21:40.451  9689  9753 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
05-19 09:21:40.451  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
05-19 09:21:40.451  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,05-19 09:21:40.451  9689  9689 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
05-19 09:21:40.451  9689  9771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,05-19 09:21:40.461  9689  9771 D BluetoothSocket: bindListen(): myUserId = 0
,05-19 09:21:40.461  9689  9771 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
05-19 09:21:40.461  3511  4449 D SecContentProvider: insert(), uri = 2
,05-19 09:21:40.461  4827  5181 W bt_btif : bta_dm_acl_change(), event : 2
05-19 09:21:40.461  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,05-19 09:21:40.461  9689  9753 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
05-19 09:21:40.461  9689  9753 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,05-19 09:21:40.461  9689  9771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
05-19 09:21:40.461  3511  4313 V AlarmManager:  remove PendingIntent] PendingIntent{2a2488a: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:40.461  9689  9771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@bccf5e1, port: 6, type: 1, local socket address: null, socket type: 0
,05-19 09:21:40.461  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:21:40.461  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:21:40.471  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:21:40.471  3511  3984 V AlarmManager:  remove PendingIntent] PendingIntent{5ef1efb: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:40.471  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:40.471  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
05-19 09:21:40.471  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:21:40.471  3511  4451 V AlarmManager:  remove PendingIntent] PendingIntent{362db18: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:40.471  9689  9753 D BluetoothAdapter: STATE_ON
05-19 09:21:40.471  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
05-19 09:21:40.471  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
05-19 09:21:40.471  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 3
,05-19 09:21:40.471  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:21:40.471  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-135,7,main], id: 135
,05-19 09:21:40.471  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:40.471  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
05-19 09:21:40.471  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
05-19 09:21:40.471  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b1b48b8e-977b-494d-8afb-10acf9d32846", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
,05-19 09:21:40.481  9689  9753 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 A8 81 95 E9 5F 6F
05-19 09:21:40.481  9689  9753 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b1b48b8e-977b-494d-8afb-10acf9d32846], mManufacturerSpecificData={}, mServiceData={b1b48b8e-977b-494d-8afb-10acf9d32846=[3, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-19 09:21:40.481  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b1b48b8e-977b-494d-8afb-10acf9d32846], mManufacturerSpecificData={}, mServiceData={b1b48b8e-977b-494d-8afb-10acf9d32846=[3, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-19 09:21:40.481  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:40.481  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b1b48b8e-977b-494d-8afb-10acf9d32846], mManufacturerSpecificData={}, mServiceData={b1b48b8e-977b-494d-8afb-10acf9d32846=[3, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-135,7,main], id: 135
,05-19 09:21:40.481  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
05-19 09:21:40.481  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b1b48b8e-977b-494d-8afb-10acf9d32846], mManufacturerSpecificData={}, mServiceData={b1b48b8e-977b-494d-8afb-10acf9d32846=[3, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-19 09:21:40.481  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:40.481  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:40.481  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[b1b48b8e-977b-494d-8afb-10acf9d32846], mManufacturerSpecificData={}, mServiceData={b1b48b8e-977b-494d-8afb-10acf9d32846=[3, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-135,7,main], id: 135
,05-19 09:21:40.481  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:21:40.481  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:21:40.481  9689  9753 D BluetoothLeAdvertiser: start advertising
,05-19 09:21:40.481  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:21:40.481  4827  4839 D BtGatt.GattService: registerClient() - UUID=34ad45ba-687b-437c-a8df-410349d5e750
,05-19 09:21:40.521  4827  4974 D BtGatt.GattService: onClientRegistered() - UUID=34ad45ba-687b-437c-a8df-410349d5e750, clientIf=7
,05-19 09:21:40.521  9689  9747 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,05-19 09:21:40.531  4827  5227 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,05-19 09:21:40.531  4827  5227 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
,05-19 09:21:40.531  4827  5227 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
05-19 09:21:40.531  4827  5046 D BtGatt.AdvertiseManager: message : 0
,05-19 09:21:40.531  4827  5070 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.rockwellautomation.thalitest, msg: MESSAGE_START_ADV
05-19 09:21:40.531  4827  5070 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 19, currDate: 19
05-19 09:21:40.531  4827  5046 D BtGatt.AdvertiseManager: number of adv instance running = 0
05-19 09:21:40.531  4827  5046 D BtGatt.AdvertiseManager: size of list is =0
,05-19 09:21:40.541  4827  5046 D BtGatt.AdvertiseManager: starting advertising
,05-19 09:21:40.541  4827  5046 D BtGatt.AdvertiseManager: isStandardAdv = false
,05-19 09:21:40.551  4827  5070 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.rockwellautomation.thalitest : 4
05-19 09:21:40.551  4827  5070 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.rockwellautomation.thalitest@LowLatency : 24919641
05-19 09:21:40.551  3511  3852 V AlarmManager:  remove PendingIntent] PendingIntent{c68c971: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:40.551  4827  5070 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.rockwellautomation.thalitest@LowLatency : 2
05-19 09:21:40.551  4827  5070 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
05-19 09:21:40.551  4827  5070 D BtGatt.GattService: [GSIM LOG]: com.rockwellautomation.thalitest@LowLatency, R time : 0 => 0
,05-19 09:21:40.551  4827  4974 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,05-19 09:21:40.551  4827  5046 D BtGatt.AdvertiseManager: starting multi advertising
,05-19 09:21:40.561  4827  4974 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,05-19 09:21:40.561  4827  5046 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,05-19 09:21:40.561  4827  5046 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
05-19 09:21:40.561  3511  4422 V AlarmManager:  remove PendingIntent] PendingIntent{4646356: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:40.561  4827  5046 D BtGatt.AdvertiseManager: postCallback clientIf = 7 status = 0
05-19 09:21:40.561  4827  5046 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=7, status=0, isStart=true
05-19 09:21:40.561  9689  9700 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
05-19 09:21:40.561  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-135,7,main], id: 135
,05-19 09:21:40.561  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-135,7,main], id: 135
,05-19 09:21:40.561  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
05-19 09:21:40.561  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:40.561  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-135,7,main], id: 135
,05-19 09:21:40.561  3511  3528 V AlarmManager:  remove PendingIntent] PendingIntent{f86afd7: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:40.561  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:40.561  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:40.561  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-135,7,main], id: 135
,05-19 09:21:40.561  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
05-19 09:21:40.561  9689  9753 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
05-19 09:21:40.561  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:40.561  9689  9753 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: seems that updateState call different BlePeerDiscoverer
,05-19 09:21:40.571  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:40.571  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:40.571  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:40.571  9689  9753 I io.jxcore.node.ConnectionHelper: start: OK
,05-19 09:21:40.571  9689  9689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
05-19 09:21:40.571  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
05-19 09:21:40.571  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
,05-19 09:21:40.571  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
05-19 09:21:40.571  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
05-19 09:21:40.571  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
05-19 09:21:40.571  9689  9689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,05-19 09:21:40.571  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
05-19 09:21:40.571  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
05-19 09:21:40.571  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
05-19 09:21:40.571  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,05-19 09:21:40.571  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
05-19 09:21:40.571  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
05-19 09:21:40.571  9689  9689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
05-19 09:21:40.571  9689  9689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,05-19 09:21:40.571  9689  9689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
05-19 09:21:40.571  9689  9689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,05-19 09:21:40.571  3511  4451 V AlarmManager:  remove PendingIntent] PendingIntent{d3690c4: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:40.571  9689  9689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
05-19 09:21:40.571  9689  9689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,05-19 09:21:40.571  9689  9689 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,05-19 09:21:40.581  3511  3982 V AlarmManager:  remove PendingIntent] PendingIntent{bef8bad: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:40.581  3511  4070 V AlarmManager:  remove PendingIntent] PendingIntent{65b5ee2: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:40.591  3511  3984 V AlarmManager:  remove PendingIntent] PendingIntent{9c7273: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:40.591  3511  4343 V AlarmManager:  remove PendingIntent] PendingIntent{56df530: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:41.081  9689  9760 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
05-19 09:21:41.081  9689  9753 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
05-19 09:21:41.081  9689  9753 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,05-19 09:21:41.081  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
05-19 09:21:41.081  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
05-19 09:21:41.081  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,05-19 09:21:41.081  9689  9753 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
05-19 09:21:41.081  9689  9753 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
05-19 09:21:41.081  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,05-19 09:21:41.081  9689  9771 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
05-19 09:21:41.081  9689  9771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
05-19 09:21:41.081  9689  9771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
05-19 09:21:41.081  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,05-19 09:21:41.081  9689  9689 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
05-19 09:21:41.081  9689  9689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
05-19 09:21:41.081  9689  9689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
05-19 09:21:41.081  9689  9753 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@45067f5 removed from the list
,05-19 09:21:41.081  9689  9753 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@45067f5 removed from the list
05-19 09:21:41.081  9689  9753 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
05-19 09:21:41.081  9689  9753 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,05-19 09:21:41.081  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:41.081  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
05-19 09:21:41.081  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,05-19 09:21:41.081  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:41.081  9689  9689 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
05-19 09:21:41.081  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-135,7,main], id: 135
,05-19 09:21:41.081  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:41.081  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:41.081  9689  9773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 207
05-19 09:21:41.081  9689  9773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
,05-19 09:21:41.081  9689  9773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: closeBluetoothSocket: Trying to close the bluetooth socket... (thread ID: 207)
05-19 09:21:41.081  9689  9773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: closeBluetoothSocket: bluetooth socket closed (thread ID: 207)
,05-19 09:21:41.081  4827  5311 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 7, channel: 1
05-19 09:21:41.081  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:21:41.081  9689  9770 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  connect: read failed, socket might closed or timeout, read ret: -1
05-19 09:21:41.081  9689  9770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socket is not connected
,05-19 09:21:41.081  9689  9770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 207)
05-19 09:21:41.081  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:21:41.081  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
05-19 09:21:41.091  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:21:41.091  9689  9753 D BluetoothAdapter: STATE_ON
05-19 09:21:41.091  9689  9753 D BluetoothLeScanner: could not find callback wrapper
,05-19 09:21:41.091  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
05-19 09:21:41.091  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:41.091  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:41.091  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:41.091  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
05-19 09:21:41.091  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:41.091  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:21:41.101  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:21:41.101  9689  9753 D BluetoothLeAdvertiser: stop advertising
,05-19 09:21:41.101  4827  4839 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
,05-19 09:21:41.101  4827  4839 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
05-19 09:21:41.101  4827  5070 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.rockwellautomation.thalitest, msg: MESSAGE_STOP_ADV
05-19 09:21:41.101  4827  5046 D BtGatt.AdvertiseManager: message : 1
05-19 09:21:41.101  4827  5070 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 19, currDate: 19
05-19 09:21:41.101  4827  5070 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
05-19 09:21:41.101  4827  5070 D BtGatt.GattService: [GSIM LOG]: com.rockwellautomation.thalitest@LowLatency, R time : 0 => 0
,05-19 09:21:41.101  4827  5070 D BtGatt.GattService: [GSIM LOG]: remove : com.rockwellautomation.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
,05-19 09:21:41.101  4827  5046 D BtGatt.AdvertiseManager: stop advertise for client =  7
05-19 09:21:41.101  4827  5046 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 7
,05-19 09:21:41.111  4827  5046 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
05-19 09:21:41.111  3511  4185 V AlarmManager:  remove PendingIntent] PendingIntent{3a635a9: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:41.111  4827  4974 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
05-19 09:21:41.111  4827  4974 D BtGatt.GattService: Client app is not null!
05-19 09:21:41.111  9689  9699 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,05-19 09:21:41.111  4827  4840 D BtGatt.GattService: unregisterClient() - clientIf=7
,05-19 09:21:41.111  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,05-19 09:21:41.111  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:41.121  3511  3852 V AlarmManager:  remove PendingIntent] PendingIntent{bd4872e: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:41.121  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
05-19 09:21:41.121  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:41.121  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:41.121  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:41.121  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,05-19 09:21:41.121  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
05-19 09:21:41.121  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
05-19 09:21:41.121  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-135,7,main], id: 135
,05-19 09:21:41.121  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-135,7,main], id: 135
,05-19 09:21:41.121  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
05-19 09:21:41.121  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:41.121  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-135,7,main], id: 135
,05-19 09:21:41.121  9689  9753 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@267198a removed from the list
05-19 09:21:41.121  9689  9689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
05-19 09:21:41.121  9689  9753 D io.jxcore.node.ConnectivityMonitor: stop
,05-19 09:21:41.121  3511  3528 V AlarmManager:  remove PendingIntent] PendingIntent{641c2cf: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:41.121  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
05-19 09:21:41.121  9689  9689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,05-19 09:21:41.121  9689  9689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
05-19 09:21:41.121  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,05-19 09:21:41.121  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
05-19 09:21:41.121  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
,05-19 09:21:41.121  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
05-19 09:21:41.121  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
05-19 09:21:41.121  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,05-19 09:21:41.121  9689  9689 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,05-19 09:21:41.131  3511  4407 V AlarmManager:  remove PendingIntent] PendingIntent{e75345c: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:41.131  3511  3852 V AlarmManager:  remove PendingIntent] PendingIntent{9038365: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:41.141  3511  4313 V AlarmManager:  remove PendingIntent] PendingIntent{da5e83a: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:41.141  3511  4422 V AlarmManager:  remove PendingIntent] PendingIntent{341bceb: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:41.151  3511  3982 V AlarmManager:  remove PendingIntent] PendingIntent{34f3a48: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:41.631  9689  9689 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,05-19 09:21:44.661  3511  6192 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,05-19 09:21:46.131  9689  9763 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
,05-19 09:21:46.131  9689  9753 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,05-19 09:21:46.131  9689  9753 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,05-19 09:21:46.131  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
05-19 09:21:46.131  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,05-19 09:21:46.131  9689  9753 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
05-19 09:21:46.131  9689  9753 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,05-19 09:21:46.131  9689  9753 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
05-19 09:21:46.131  9689  9753 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,05-19 09:21:46.131  9689  9753 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,05-19 09:21:46.131  9689  9689 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
05-19 09:21:46.131  9689  9774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
05-19 09:21:46.141  9689  9753 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
05-19 09:21:46.141  9689  9753 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [00:11:22:33:44:55], error message: ErrorMessage
05-19 09:21:46.141  9689  9753 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
05-19 09:21:46.141  9689  9753 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,05-19 09:21:46.141  9689  9753 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
05-19 09:21:46.141  9689  9774 D BluetoothSocket: bindListen(): myUserId = 0
,05-19 09:21:46.141  9689  9774 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
05-19 09:21:46.141  9689  9753 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
,05-19 09:21:46.151  9689  9774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
,05-19 09:21:46.151  9689  9774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@25c3bf4, port: 6, type: 1, local socket address: null, socket type: 0
,05-19 09:21:46.161  9689  9753 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
05-19 09:21:46.161  9689  9753 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,05-19 09:21:46.161  9689  9753 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
05-19 09:21:46.161  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,05-19 09:21:46.161  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
05-19 09:21:46.161  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
05-19 09:21:46.161  9689  9753 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
05-19 09:21:46.161  9689  9753 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
05-19 09:21:46.161  9689  9753 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@45067f5 not in the list
05-19 09:21:46.161  9689  9753 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@45067f5 not in the list
,05-19 09:21:46.161  9689  9753 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
05-19 09:21:46.161  9689  9753 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
05-19 09:21:46.161  9689  9774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
05-19 09:21:46.161  9689  9689 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
05-19 09:21:46.161  9689  9774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,05-19 09:21:46.161  9689  9774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
05-19 09:21:46.161  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:46.161  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
05-19 09:21:46.161  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
05-19 09:21:46.161  9689  9753 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,05-19 09:21:46.161  9689  9689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
05-19 09:21:46.161  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
05-19 09:21:46.161  9689  9689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
05-19 09:21:46.161  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:46.161  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-135,7,main], id: 135
,05-19 09:21:46.161  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
05-19 09:21:46.161  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:46.161  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:21:46.161  9689  9753 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@267198a not in the list
05-19 09:21:46.161  9689  9753 D io.jxcore.node.ConnectivityMonitor: stop
,05-19 09:21:46.161  9689  9689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
05-19 09:21:46.161  9689  9753 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
05-19 09:21:46.161  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
05-19 09:21:46.161  9689  9689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
05-19 09:21:46.161  9689  9689 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,05-19 09:21:46.161  9689  9753 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
05-19 09:21:46.161  9689  9753 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
05-19 09:21:46.161  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
05-19 09:21:46.161  9689  9753 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,05-19 09:21:46.161  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
05-19 09:21:46.161  9689  9753 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
05-19 09:21:46.171  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,05-19 09:21:46.171  9689  9753 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
,05-19 09:21:46.171  9689  9753 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
,05-19 09:21:46.171  9689  9753 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
,05-19 09:21:46.171  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [incoming]
,05-19 09:21:46.171  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [outgoing]
,05-19 09:21:46.171  9689  9753 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
05-19 09:21:46.171  9689  9753 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,05-19 09:21:46.171  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
05-19 09:21:46.171  9689  9753 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
05-19 09:21:46.171  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
05-19 09:21:46.171  9689  9753 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,05-19 09:21:46.171  9689  9753 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
05-19 09:21:46.171  9689  9753 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
,05-19 09:21:46.171  9689  9753 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
05-19 09:21:46.171  9689  9753 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,05-19 09:21:46.181  9689  9753 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
,05-19 09:21:46.181  9689  9753 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
05-19 09:21:46.181  9689  9753 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
05-19 09:21:46.181  9689  9753 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
05-19 09:21:46.181  9689  9753 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,05-19 09:21:46.181  9689  9753 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
,05-19 09:21:46.191  9689  9753 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,05-19 09:21:46.191  9689  9753 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e420f1d added. We now have 2 listener(s)
05-19 09:21:46.191  9689  9753 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e420f1d added. We now have 3 listener(s)
05-19 09:21:46.191  9689  9753 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,05-19 09:21:46.191  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"A8:81:95:E9:5F:6F"}
,05-19 09:21:46.191  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
05-19 09:21:46.191  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"A8:81:95:E9:5F:6F"}
,05-19 09:21:46.191  9689  9753 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
05-19 09:21:46.191  9689  9753 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@297592 added. We now have 4 listener(s)
05-19 09:21:46.191  9689  9753 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
05-19 09:21:46.191  9689  9753 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,05-19 09:21:46.201  9689  9753 D BluetoothAdapter: enable()
,05-19 09:21:46.211  9689  9753 D BluetoothAdapter: enable(): BT is already enabled..!
,05-19 09:21:46.211  3511  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{82df0e1 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cf9e5aa 4853:com.samsung.android.providers.context/u0a9}
,05-19 09:21:46.211  9689  9753 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,05-19 09:21:46.221  3511  4451 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,05-19 09:21:46.221  3511  4451 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,05-19 09:21:46.221  3511  4451 D WifiService: setWifiEnabled: true pid=9689, uid=10078
,05-19 09:21:46.221  3511  4451 W WifiService: Failed getting userId using ActivityManagerNative
05-19 09:21:46.221  3511  4451 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9689, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-19 09:21:46.221  3511  4451 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-19 09:21:46.221  3511  4451 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
05-19 09:21:46.221  3511  4451 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
05-19 09:21:46.221  3511  4451 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
05-19 09:21:46.221  3511  4451 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
05-19 09:21:46.221  3511  4451 W ActivityManager: Permission Denial: getCurrentUser() from pid=9689, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-19 09:21:46.221  3511  4451 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
05-19 09:21:46.221  3511  4451 D SettingsProvider: isChangeAllowed() : name = wifi_on
05-19 09:21:46.221  3511  3860 D WifiStateMachine: setFccChannel: channel = 0
05-19 09:21:46.221  3511  3860 D WifiController: [FCC]setFccChannel() is called !!!
05-19 09:21:46.221  3511  3857 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,05-19 09:21:46.221  3511  3860 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
,05-19 09:21:46.231  3511  3857 D WifiBigDataLog: init : 
,05-19 09:21:46.231  3511  3857 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,05-19 09:21:46.231  9689  9753 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
05-19 09:21:46.231  3511  3857 D WifiStateMachine: setFccChannelNative: channel = 0
,05-19 09:21:46.231  3511  3857 D WifiNative-wlan0: callSECApiInt - ID [230]
,05-19 09:21:46.241  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:21:46.241  3511  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9fa4e06 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cf9e5aa 4853:com.samsung.android.providers.context/u0a9}
,05-19 09:21:46.251  9689  9753 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
,05-19 09:21:46.251  9689  9753 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
,05-19 09:21:46.251  9689  9753 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
,05-19 09:21:46.261  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:21:46.261  9689  9753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-19 09:21:46.261  9689  9753 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-19 09:21:46.261  9689  9753 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-19 09:21:46.261  9689  9753 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-19 09:21:46.261  9689  9753 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-19 09:21:46.261  9689  9753 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-19 09:21:46.261  9689  9753 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-19 09:21:46.261  9689  9753 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-19 09:21:46.261  9689  9753 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,05-19 09:21:46.261  9689  9775 D BluetoothAdapter: disable()
,05-19 09:21:46.271  3511  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1fd3cc7 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cf9e5aa 4853:com.samsung.android.providers.context/u0a9}
,05-19 09:21:46.281  3511  3529 D SettingsProvider: isChangeAllowed() : name = bluetooth_on
,05-19 09:21:46.281  3511  3647 D SecContentProvider: insert(), uri = 2
,05-19 09:21:46.281  4827  4968 D BluetoothAdapterState: Current state: ON, message: BLE_TURN_OFF
,05-19 09:21:46.291  4827  4968 D BluetoothAdapterProperties: Setting state to 13
,05-19 09:21:46.291  4827  4968 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
05-19 09:21:46.291  4827  4968 D BluetoothAdapterService: Bluetooth PBAP supproted is true
05-19 09:21:46.291  4827  4968 D BluetoothAdapterService: updateAdapterState state is 13
,05-19 09:21:46.301  4827  4827 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,05-19 09:21:46.301  3511  3647 D BluetoothManagerService: Turning On/Off, G state: 3, S state: 3, mBLE count: 0, s BLE count: 0
,05-19 09:21:46.301  4827  4968 D BluetoothAdapterService: Autoconnection is available 
05-19 09:21:46.301  4827  4968 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
,05-19 09:21:46.301  4827  4968 D BluetoothAdapterService: terminating service from this receiver
,05-19 09:21:46.301  3939  3939 D BluetoothPbap: Proxy object disconnected
,05-19 09:21:46.301  3939  3939 D PbapServerProfile: Bluetooth service disconnected
,05-19 09:21:46.301  3511  3511 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,05-19 09:21:46.301  4827  4968 D BluetoothAdapterProperties: onBluetoothDisable()
05-19 09:21:46.301  3511  3511 I InputMethodManagerService: [BT Setting State] State =13
,05-19 09:21:46.301  4827  4968 W bt_btif : btif_dm_cancel_discovery
,05-19 09:21:46.311  3939  4163 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,05-19 09:21:46.311  3511  3529 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
05-19 09:21:46.311  3939  4163 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,05-19 09:21:46.311  3511  4198 D SecContentProvider: insert(), uri = 2
05-19 09:21:46.311  4344  4344 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
,05-19 09:21:46.311  4917  4917 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,05-19 09:21:46.311  4827  4968 I BluetoothAdapterState: Entering PendingCommandState
05-19 09:21:46.311  3511  4407 V AlarmManager:  remove PendingIntent] PendingIntent{f37ba1d: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:46.311  3511  3511 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
05-19 09:21:46.311  3511  3511 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
05-19 09:21:46.311  3511  3511 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,05-19 09:21:46.321  9689  9689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
05-19 09:21:46.321  9689  9689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-19 09:21:46.321  9689  9689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-19 09:21:46.321  9689  9689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-19 09:21:46.321  9689  9689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-19 09:21:46.321  9689  9689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
05-19 09:21:46.321  9689  9689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-19 09:21:46.321  9689  9689 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-19 09:21:46.321  9689  9689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-19 09:21:46.321  9689  9689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,05-19 09:21:46.321  9689  9689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
05-19 09:21:46.321  9689  9689 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,05-19 09:21:46.321  3511  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4dd4492 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a2e0fe7 9409:com.android.settings/1000}
,05-19 09:21:46.331  4827  4974 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
05-19 09:21:46.331  3511  4407 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
05-19 09:21:46.331  4827  4974 D BluetoothAdapterProperties: Scan Mode:20
05-19 09:21:46.331  3939  3939 D QSTileView: handleLabelStateChanged() label = Bluetooth cellWidth 272
05-19 09:21:46.331  3939  4254 D BluetoothTile: handleUpdateState :  supported = true, enabled = false, enabling = false, connected = false, connecting = false, mController.getLastDeviceName() = null
,05-19 09:21:46.331  4827  4968 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BEGIN_DISABLE
,05-19 09:21:46.341  9409  9409 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,05-19 09:21:46.341  9689  9689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
05-19 09:21:46.341  4827  4968 E BluetoothServiceJni: disableBrEdrNative:
05-19 09:21:46.341  4827  4968 E bt_bluedroid: disable_bredr
,05-19 09:21:46.341  4827  4969 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
05-19 09:21:46.341  4827  4969 E bt_btif : BTA got event 0xe0b
05-19 09:21:46.341  4827  5436 V ObexServerSockets: Accept exception: (expected at shutdown)java.io.IOException: read failed, socket might closed or timeout, read ret: -1
05-19 09:21:46.341  4827  5436 D ObexServerSockets: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
05-19 09:21:46.341  4827  5181 W bt_btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
,05-19 09:21:46.341  4827  5181 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-19 09:21:46.341  4827  5435 V ObexServerSockets: Accept exception: (expected at shutdown)java.io.IOException: read failed, socket might closed or timeout, read ret: -1
05-19 09:21:46.341  4827  5435 D ObexServerSockets: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
05-19 09:21:46.341  4827  5372 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,05-19 09:21:46.351  4827  5181 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x2  CID 0x40
,05-19 09:21:46.351  3511  4070 V AlarmManager:  remove PendingIntent] PendingIntent{6410a60: PendingIntentRecord{11adb19 com.android.bluetooth broadcastIntent}}
05-19 09:21:46.351  4827  5181 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 7
05-19 09:21:46.351  3511  4459 V AlarmManager:  remove PendingIntent] PendingIntent{58717de: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:46.351  4827  5181 W bt_btif : bta_dm_acl_change(), event : 2
05-19 09:21:46.351  4827  4969 D IOP_DB_BT: db_close: nbr users 0
,05-19 09:21:46.351  4827  4969 D IOP_DB_BT: db_close: free database
05-19 09:21:46.351  4827  5181 W bt_btif : bta_dm_acl_change(), event : 5
05-19 09:21:46.361  9409  9409 D LocalBluetoothManager: LocalBluetoothManager :: sInstance == null
,05-19 09:21:46.371  3511  4313 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4dd4492 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cf9e5aa 4853:com.samsung.android.providers.context/u0a9}
,05-19 09:21:46.371  9409  9409 D LocalBluetoothManager: LocalBluetoothManager :: constructor
,05-19 09:21:46.371  4827  5181 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.,
05-19 09:21:46.371  4827  5181 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-19 09:21:46.371  4827  5181 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-19 09:21:46.371  4827  5181 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-19 09:21:46.371  4827  5181 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-19 09:21:46.371  4827  5181 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,05-19 09:21:46.371  4827  5181 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-19 09:21:46.371  4827  5181 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-19 09:21:46.381  3511  4451 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4dd4492 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dc64001 4328:com.google.android.gms.persistent/u0a21}
05-19 09:21:46.371  4827  5181 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-19 09:21:46.371  4827  5181 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-19 09:21:46.371  4827  5181 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-19 09:21:46.371  4827  5181 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-19 09:21:46.371  4827  5181 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-19 09:21:46.371  4827  5181 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-19 09:21:46.371  4827  5181 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-19 09:21:46.381  9409  9409 D BluetoothEventManager: BluetoothEventManager Constructor :: 
05-19 09:21:46.381  4827  4968 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ca63953
05-19 09:21:46.381  4827  4974 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:11:22:33:44:55, value is empty for type: 1
05-19 09:21:46.381  4328  4328 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
,05-19 09:21:46.391  3511  4449 V AlarmManager:  remove PendingIntent] PendingIntent{c68d3ea: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:46.391  3939  4163 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CLASS_CHANGED
,05-19 09:21:46.391  4827  4974 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
05-19 09:21:46.391  4827  4974 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:11:22:33:44:55, value is empty for type: 241
,05-19 09:21:46.401  4827  4827 D BleAudioService: onReceive:: INTENT mAobleStateChangeListener got : android.bluetooth.adapter.action.STATE_CHANGED
,05-19 09:21:46.401  4827  4827 D BleAudioService: BluetoothAdapter.ACTION_STATE_CHANGED,  state is13
05-19 09:21:46.401  4827  4827 D ObexServerSockets: shutdown(block = true)
05-19 09:21:46.401  4827  4827 D ObexServerSockets: shutdown called from another thread - interrupt().
05-19 09:21:46.401  4827  4827 D ObexServerSockets: shutdown called from another thread - interrupt().
05-19 09:21:46.401  4827  4827 D BluetoothSdpJni: sdpRemoveSdpRecordNative:
05-19 09:21:46.401  4827  4827 D BluetoothSdpJni: SDP Remove record success - handle: 1
05-19 09:21:46.401  4827  4827 D BluetoothSdpJni: sdpRemoveSdpRecordNative:
05-19 09:21:46.401  4827  4827 D BluetoothSdpJni: SDP Remove record success - handle: 0
05-19 09:21:46.401  4827  4827 I BtOppRfcommListener: stopping Accept Thread
05-19 09:21:46.401  4827  5372 I BtOppRfcommListener: BluetoothSocket listen thread finished
,05-19 09:21:46.401  9409  9409 D LocalBluetoothProfileManager: PANU : true
,05-19 09:21:46.411  3511  4451 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4dd4492 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7e09761 8967:com.sec.android.app.shealth:remote/u0a39}
,05-19 09:21:46.431  3511  4451 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4dd4492 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a2e0fe7 9409:com.android.settings/1000}
,05-19 09:21:46.441  4827  4827 V BluetoothOppManager: cleanUp...
,05-19 09:21:46.441  9409  9409 D BluetoothSap: Create BluetoothSap proxy object
,05-19 09:21:46.441  9409  9409 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
05-19 09:21:46.441  9409  9409 D LocalBluetoothManager: LocalBluetoothManager :: onInitCallback != null
,05-19 09:21:46.451  9409  9409 D DockEventReceiver: finishStartingService: stopping service
,05-19 09:21:46.451  9409  9409 D BluetoothPan: BluetoothPAN Proxy object connected
,05-19 09:21:46.451  9409  9409 D PanProfile: Bluetooth service connected
,05-19 09:21:46.461  9409  9409 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
05-19 09:21:46.461  9409  9409 D BluetoothStatusReceiver: AdapterStateChanged :: state = 13
,05-19 09:21:46.461  9409  9409 D BluetoothSap: Proxy object connected
05-19 09:21:46.461  9409  9409 D SapProfile: Bluetooth service connected
,05-19 09:21:46.461  3511  4422 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4dd4492 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{71b783c 4827:com.android.bluetooth/1002}
,05-19 09:21:46.481  3511  4422 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4dd4492 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{40b9903 7208:com.google.android.apps.maps/u0a125}
,05-19 09:21:46.541  4827  4974 E BluetoothAdapterState: stateChangeCallback : 16
,05-19 09:21:46.541  4827  4968 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_NATIVE_STOPED
05-19 09:21:46.541  3511  3529 V AlarmManager:  remove PendingIntent] PendingIntent{4b8d4af: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:46.551  4827  4968 D BtConfig.SecureMode: isSecureModeOn:false
,05-19 09:21:46.551  4827  4968 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,05-19 09:21:46.551  4827  4968 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,05-19 09:21:46.551  4827  4827 D HeadsetService: Received stop request...Stopping profile...
,05-19 09:21:46.561  4827  4968 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
05-19 09:21:46.561  4827  4827 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Message sending
05-19 09:21:46.561  4827  4827 E HeadsetService: notifyProfileServiceStateChanged
,05-19 09:21:46.571  3939  3939 D HeadsetProfile: Bluetooth service disconnected
,05-19 09:21:46.571  3511  3511 D BluetoothHeadset: unRegisterMessageListener : 11
05-19 09:21:46.571  3511  3511 W BluetoothHeadset: Proxy not attached to service
05-19 09:21:46.571  3511  3511 I Telecom : BluetoothManager : unregister MessageListener
05-19 09:21:46.571  3511  3511 I Telecom : CallAudioManager: onBluetoothStateChange: no focus
05-19 09:21:46.571  4827  4827 D A2dpService: Received stop request...Stopping profile...
05-19 09:21:46.571  4827  4968 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,05-19 09:21:46.571  4827  5261 D A2dpStateMachine: Exit Disconnected: -1
,05-19 09:21:46.571  4827  4968 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,05-19 09:21:46.571  4827  4827 D Avrcp   : unregisterContentObserver
,05-19 09:21:46.571  4827  4968 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
05-19 09:21:46.571  4827  4827 D Avrcp   : removeOnActiveSessionsChangedListener
,05-19 09:21:46.581  4827  4827 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Message sending
05-19 09:21:46.581  4827  4827 E A2dpService: notifyProfileServiceStateChanged
,05-19 09:21:46.581  4827  4968 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
05-19 09:21:46.581  3939  3939 D BluetoothA2dp: Proxy object disconnected
05-19 09:21:46.581  3939  3939 D A2dpProfile: Bluetooth service disconnected
05-19 09:21:46.581  4853  4853 D BluetoothA2dp: Proxy object disconnected
05-19 09:21:46.581  3511  3511 D BluetoothA2dp: Proxy object disconnected
,05-19 09:21:46.581  4827  4827 E BluetoothAdapterService: handleMessage() - Message: 1
,05-19 09:21:46.581  4827  4827 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Before synchronized
05-19 09:21:46.581  4827  4827 V BluetoothAdapterState: isTurningOff()=true
05-19 09:21:46.581  4827  4827 V BluetoothAdapterState: isTurningOn()=false
05-19 09:21:46.581  4827  4827 V BluetoothAdapterState: isBleTurningOn()=false
05-19 09:21:46.581  4827  4827 V BluetoothAdapterState: isBleTurningOff()=false
05-19 09:21:46.581  4827  4968 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,05-19 09:21:46.581  4827  4968 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
05-19 09:21:46.581  4827  4968 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
05-19 09:21:46.581  4827  4968 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
05-19 09:21:46.581  4827  4968 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.bleaudio.BleAudioService
,05-19 09:21:46.601  4827  4827 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
05-19 09:21:46.601  4827  4827 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,05-19 09:21:46.601  4827  4827 D HeadsetProvider: cleanup
05-19 09:21:46.601  4827  4827 I HeadsetProvider: clearAllHeadsetSettings(0)
,05-19 09:21:46.611  4827  4827 D HidService: Received stop request...Stopping profile...
,05-19 09:21:46.611  4827  4827 D HidService: Stopping Bluetooth HidService
05-19 09:21:46.611  4827  4827 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
05-19 09:21:46.611  4827  4827 W bt_btif : cleanup: HH disabling or disabled already, status = 0
05-19 09:21:46.611  4827  4827 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
05-19 09:21:46.611  4827  4827 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, Message sending
,05-19 09:21:46.611  4827  4827 E HidService: notifyProfileServiceStateChanged
05-19 09:21:46.621  3939  3939 D BluetoothInputDevice: Proxy object disconnected
05-19 09:21:46.621  3939  3939 D HidProfile: Bluetooth service disconnected
,05-19 09:21:46.621  4827  4827 D HealthService: Received stop request...Stopping profile...
05-19 09:21:46.621  4827  4827 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, Message sending
,05-19 09:21:46.621  4827  4827 E HealthService: notifyProfileServiceStateChanged
,05-19 09:21:46.621  4827  4827 D PanService: Received stop request...Stopping profile...
,05-19 09:21:46.621  4827  4827 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, Message sending
05-19 09:21:46.621  4827  4827 E PanService: notifyProfileServiceStateChanged
05-19 09:21:46.621  3511  3511 D BluetoothPan: BluetoothPAN Proxy object disconnected
,05-19 09:21:46.621  3939  3939 D BluetoothPan: BluetoothPAN Proxy object disconnected
05-19 09:21:46.621  3939  3939 D PanProfile: Bluetooth service disconnected
05-19 09:21:46.621  9409  9409 D BluetoothPan: BluetoothPAN Proxy object disconnected
05-19 09:21:46.621  9409  9409 D PanProfile: Bluetooth service disconnected
,05-19 09:21:46.621  4827  4827 E BluetoothAdapterService: handleMessage() - Message: 1
05-19 09:21:46.621  4827  4827 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Before synchronized
,05-19 09:21:46.621  4827  4827 V BluetoothAdapterState: isTurningOff()=true
05-19 09:21:46.621  4827  4827 V BluetoothAdapterState: isTurningOn()=false
05-19 09:21:46.621  4827  4827 V BluetoothAdapterState: isBleTurningOn()=false
05-19 09:21:46.621  4827  4827 V BluetoothAdapterState: isBleTurningOff()=false
,05-19 09:21:46.631  4827  4827 D BluetoothMapService: Received stop request...Stopping profile...
,05-19 09:21:46.631  4827  4827 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Message sending
,05-19 09:21:46.631  4827  4827 E BluetoothMapService: notifyProfileServiceStateChanged
,05-19 09:21:46.631  3939  3939 D BluetoothMap: Proxy object disconnected
05-19 09:21:46.631  3939  3939 D MapProfile: Bluetooth service disconnected
,05-19 09:21:46.641  4827  4827 D SapService: Received stop request...Stopping profile...
,05-19 09:21:46.641  4827  4827 V SapService: stop()
05-19 09:21:46.641  4827  4827 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=10, Message sending
05-19 09:21:46.641  4827  4827 E SapService: notifyProfileServiceStateChanged
,05-19 09:21:46.641  3939  3939 D BluetoothSap: Proxy object disconnected
,05-19 09:21:46.641  3939  3939 D SapProfile: Bluetooth service disconnected
05-19 09:21:46.641  9409  9409 D BluetoothSap: Proxy object disconnected
05-19 09:21:46.641  9409  9409 D SapProfile: Bluetooth service disconnected
05-19 09:21:46.641  4827  4827 D BleAudioService: Received stop request...Stopping profile...
,05-19 09:21:46.641  4827  4827 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.broadcom.bt.service.bleaudio.BleAudioService, state=10, Message sending
05-19 09:21:46.641  4827  5298 E BleAudioStateMachine_L: Exit Disconnected: -1
05-19 09:21:46.641  4827  4827 E BleAudioService: notifyProfileServiceStateChanged
05-19 09:21:46.641  4827  5299 E BleAudioStateMachine_R: Exit Disconnected: -1
05-19 09:21:46.641  3939  3939 D BluetoothLeAudio: Proxy object disconnected
05-19 09:21:46.641  3939  3939 D BleAudioProfile: Bluetooth service disconnected
,05-19 09:21:46.651  4827  4827 E BluetoothAdapterService: handleMessage() - Message: 1
,05-19 09:21:46.651  4827  4827 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, Before synchronized
05-19 09:21:46.651  4827  4827 V BluetoothAdapterState: isTurningOff()=true
,05-19 09:21:46.651  4827  4827 V BluetoothAdapterState: isTurningOn()=false
05-19 09:21:46.651  4827  4827 V BluetoothAdapterState: isBleTurningOn()=false
05-19 09:21:46.651  4827  4827 V BluetoothAdapterState: isBleTurningOff()=false
05-19 09:21:46.651  4827  4827 D BluetoothAdapterService: HID Host service will be diabled
,05-19 09:21:46.651  4827  4827 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,05-19 09:21:46.651  4827  4827 E BluetoothAdapterService: handleMessage() - Message: 1
,05-19 09:21:46.651  4827  4827 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, Before synchronized
,05-19 09:21:46.651  4827  4827 V BluetoothAdapterState: isTurningOff()=true
05-19 09:21:46.651  4827  4827 V BluetoothAdapterState: isTurningOn()=false
,05-19 09:21:46.651  4827  4827 V BluetoothAdapterState: isBleTurningOn()=false
,05-19 09:21:46.651  4827  4827 V BluetoothAdapterState: isBleTurningOff()=false
05-19 09:21:46.651  4827  4827 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
05-19 09:21:46.651  4827  4827 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,05-19 09:21:46.661  4827  4827 E BluetoothAdapterService: handleMessage() - Message: 1
05-19 09:21:46.661  4827  4827 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, Before synchronized
05-19 09:21:46.661  4827  4827 V BluetoothAdapterState: isTurningOff()=true
,05-19 09:21:46.661  4827  4827 V BluetoothAdapterState: isTurningOn()=false
05-19 09:21:46.661  4827  4827 V BluetoothAdapterState: isBleTurningOn()=false
05-19 09:21:46.661  4827  4827 V BluetoothAdapterState: isBleTurningOff()=false
,05-19 09:21:46.661  4827  4827 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
05-19 09:21:46.661  4827  4827 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,05-19 09:21:46.661  4827  4827 E BluetoothAdapterService: handleMessage() - Message: 1
05-19 09:21:46.661  4827  4827 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Before synchronized
05-19 09:21:46.661  4827  4827 V BluetoothAdapterState: isTurningOff()=true
05-19 09:21:46.661  4827  4827 V BluetoothAdapterState: isTurningOn()=false
,05-19 09:21:46.661  4827  4827 V BluetoothAdapterState: isBleTurningOn()=false
05-19 09:21:46.661  4827  4827 V BluetoothAdapterState: isBleTurningOff()=false
05-19 09:21:46.661  4827  4827 E BluetoothAdapterService: handleMessage() - Message: 1
05-19 09:21:46.661  4827  4827 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=10, Before synchronized
05-19 09:21:46.661  4827  4827 V BluetoothAdapterState: isTurningOff()=true
05-19 09:21:46.661  4827  4827 V BluetoothAdapterState: isTurningOn()=false
,05-19 09:21:46.661  4827  4827 V BluetoothAdapterState: isBleTurningOn()=false
05-19 09:21:46.661  4827  4827 V BluetoothAdapterState: isBleTurningOff()=false
05-19 09:21:46.661  4827  4827 E BluetoothAdapterService: handleMessage() - Message: 1
05-19 09:21:46.661  4827  4827 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.bleaudio.BleAudioService, state=10, Before synchronized
05-19 09:21:46.661  4827  4827 V BluetoothAdapterState: isTurningOff()=true
,05-19 09:21:46.661  4827  4827 V BluetoothAdapterState: isTurningOn()=false
05-19 09:21:46.661  4827  4827 V BluetoothAdapterState: isBleTurningOn()=false
05-19 09:21:46.661  4827  4827 V BluetoothAdapterState: isBleTurningOff()=false
,05-19 09:21:46.661  4827  4968 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_STOPPED
05-19 09:21:46.661  4827  4827 V BleAudioService: [unregisterCallStateListener]
05-19 09:21:46.671  4827  4827 W BtBleAudio.JNI: WARNING: cleanupNative(L385): Cleaning up  Ble audio left callback object##
05-19 09:21:46.671  4827  4827 W BtBleAudio.JNI: WARNING: cleanupNative(L403): Cleaning up Ble audio Interface...##
,05-19 09:21:46.671  4827  4827 W BtBleAudio.JNI: WARNING: cleanupNative(L391): Cleaning up  Ble audio right callback object##
05-19 09:21:46.671  4827  4968 D BluetoothAdapterProperties: Setting state to 15
,05-19 09:21:46.671  4827  4968 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
05-19 09:21:46.671  4827  4827 V BleAudioService: [unregisterAobleStateChangeListener] Unregistering mAobleStateChangeListener
,05-19 09:21:46.671  4827  4968 D BluetoothAdapterService: Bluetooth PBAP supproted is true
05-19 09:21:46.671  4827  4968 D BluetoothAdapterService: updateAdapterState state is 15
,05-19 09:21:46.671  9689  9689 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,05-19 09:21:46.671  4827  4968 D BluetoothAdapterService: Autoconnection is available 
05-19 09:21:46.671  4827  4968 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 15
,05-19 09:21:46.671  4827  4968 I BluetoothAdapterState: Entering BleOnState
05-19 09:21:46.671  4328  4591 D BluetoothAdapter: onBluetoothStateChange: up=false
05-19 09:21:46.671  4328  4591 D BluetoothAdapter: Bluetooth is turned off, stop adv
,05-19 09:21:46.671  4328  4591 D BluetoothAdapter: There are no active google scan apps, stop scan
05-19 09:21:46.671  4328  4591 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false,
,05-19 09:21:46.671  4328  4591 D BluetoothLeScanner: Exiting stopAllScan
05-19 09:21:46.671  4853  4864 D BluetoothA2dp: onBluetoothStateChange: up=false
,05-19 09:21:46.681  3511  3647 D BluetoothAdapter: onBluetoothStateChange: up=false
05-19 09:21:46.681  3511  3647 D BluetoothAdapter: Bluetooth is turned off, stop adv
05-19 09:21:46.681  3511  3647 D BluetoothAdapter: There are no active google scan apps, stop scan
05-19 09:21:46.681  9409  9419 D BluetoothAdapter: onBluetoothStateChange: up=false
05-19 09:21:46.681  9409  9419 D BluetoothAdapter: Bluetooth is turned off, stop adv
05-19 09:21:46.681  9409  9419 D BluetoothAdapter: There are no active google scan apps, stop scan
,05-19 09:21:46.681  3939  3949 D BluetoothPan: onBluetoothStateChange on: false
05-19 09:21:46.681  4287  4542 D BluetoothAdapter: onBluetoothStateChange: up=false
05-19 09:21:46.681  4287  4542 D BluetoothAdapter: Bluetooth is turned off, stop adv
05-19 09:21:46.681  4287  4542 D BluetoothAdapter: There are no active google scan apps, stop scan
,05-19 09:21:46.681  3939  3950 D BluetoothA2dp: onBluetoothStateChange: up=false
,05-19 09:21:46.681  8967  8977 D BluetoothAdapter: onBluetoothStateChange: up=false
,05-19 09:21:46.681  8967  8977 D BluetoothAdapter: Bluetooth is turned off, stop adv
,05-19 09:21:46.681  8967  8977 D BluetoothAdapter: There are no active google scan apps, stop scan
,05-19 09:21:46.681  7208  7221 D BluetoothAdapter: onBluetoothStateChange: up=false
05-19 09:21:46.681  7208  7221 D BluetoothAdapter: Bluetooth is turned off, stop adv
,05-19 09:21:46.691  7208  7221 D BluetoothAdapter: There are no active google scan apps, stop scan
,05-19 09:21:46.691  9409  9420 D BluetoothSap: onBluetoothStateChange: up=false
,05-19 09:21:46.691  3939  5545 D BluetoothPbap: onBluetoothStateChange: up=false
,05-19 09:21:46.691  3939  4110 D BluetoothAdapter: onBluetoothStateChange: up=false
,05-19 09:21:46.691  3939  4110 D BluetoothAdapter: Bluetooth is turned off, stop adv
,05-19 09:21:46.691  3939  4110 D BluetoothAdapter: There are no active google scan apps, stop scan
,05-19 09:21:46.691  4827  5227 D BluetoothAdapter: onBluetoothStateChange: up=false
05-19 09:21:46.691  4827  5227 D BluetoothAdapter: Bluetooth is turned off, stop adv
,05-19 09:21:46.691  4827  5227 D BluetoothAdapter: There are no active google scan apps, stop scan
,05-19 09:21:46.691  3511  3647 D BluetoothA2dp: onBluetoothStateChange: up=false
,05-19 09:21:46.701  3939  4592 D BluetoothSap: onBluetoothStateChange: up=false
,05-19 09:21:46.701  3511  3647 D BluetoothPan: onBluetoothStateChange on: false
05-19 09:21:46.701  4275  4285 D BluetoothAdapter: onBluetoothStateChange: up=false
,05-19 09:21:46.701  4275  4285 D BluetoothAdapter: Bluetooth is turned off, stop adv
,05-19 09:21:46.701  4275  4285 D BluetoothAdapter: There are no active google scan apps, stop scan
,05-19 09:21:46.701  3939  3949 D BluetoothLeAudio: onBluetoothStateChange: up=false
,05-19 09:21:46.701  3939  3949 D BluetoothLeAudio: Unbinding service...
05-19 09:21:46.701  3939  3950 D BluetoothMap: onBluetoothStateChange: up=false
,05-19 09:21:46.701  9689  9700 D BluetoothAdapter: onBluetoothStateChange: up=false
,05-19 09:21:46.701  9689  9700 D BluetoothAdapter: Bluetooth is turned off, stop adv
05-19 09:21:46.701  9689  9700 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
05-19 09:21:46.701  9689  9700 D BluetoothLeAdvertiser: Exit stop advertising
,05-19 09:21:46.701  9689  9700 D BluetoothAdapter: There are no active google scan apps, stop scan
05-19 09:21:46.701  9689  9700 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
05-19 09:21:46.701  9689  9700 D BluetoothLeScanner: Exiting stopAllScan
,05-19 09:21:46.701  9409  9419 D BluetoothPan: onBluetoothStateChange on: false
,05-19 09:21:46.711  3939  5545 D BluetoothInputDevice: onBluetoothStateChange: up=false
,05-19 09:21:46.711  4853  4865 D BluetoothAdapter: onBluetoothStateChange: up=false
,05-19 09:21:46.711  4853  4865 D BluetoothAdapter: Bluetooth is turned off, stop adv
05-19 09:21:46.711  4853  4865 D BluetoothAdapter: There are no active google scan apps, stop scan
,05-19 09:21:46.711  4827  4968 D BluetoothAdapterState: Current state: BLE ON, message: USER_TURN_OFF
,05-19 09:21:46.711  3511  3511 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,05-19 09:21:46.711  3511  3511 I InputMethodManagerService: [BT Setting State] State =10
05-19 09:21:46.711  3511  3511 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,05-19 09:21:46.711  3939  4163 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,05-19 09:21:46.711  3939  4163 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,05-19 09:21:46.721  4344  4344 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
,05-19 09:21:46.721  4917  4917 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,05-19 09:21:46.721  3511  3511 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
05-19 09:21:46.721  3511  3511 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
05-19 09:21:46.721  3511  3511 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,05-19 09:21:46.721  9409  9409 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,05-19 09:21:46.731  9409  9409 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,05-19 09:21:46.731  9689  9689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-19 09:21:46.731  3511  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1da10bc u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a2e0fe7 9409:com.android.settings/1000}
,05-19 09:21:46.731  4827  4968 D BluetoothAdapterProperties: Setting state to 16
05-19 09:21:46.731  4827  4968 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
05-19 09:21:46.731  4827  4968 D BluetoothAdapterService: Bluetooth PBAP supproted is true
05-19 09:21:46.731  4827  4968 D BluetoothAdapterService: updateAdapterState state is 16
05-19 09:21:46.731  4827  4968 D BluetoothAdapterService: Autoconnection is available 
05-19 09:21:46.731  4827  4968 D BluetoothAdapterService: updateAdapterState prevState = 15newState = 16
05-19 09:21:46.731  4827  4968 D BluetoothAdapterProperties: onBleDisable
05-19 09:21:46.731  3511  3647 D BluetoothManagerService: Ble Turning On/Off, G state: 3, S state: 3
,05-19 09:21:46.731  3511  4313 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
,05-19 09:21:46.741  3511  3852 D SecContentProvider: insert(), uri = 2
,05-19 09:21:46.741  4827  4968 I BluetoothAdapterState: Entering PendingCommandState
,05-19 09:21:46.741  4827  4969 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
05-19 09:21:46.741  4827  4969 E bt_btif : btif_vhci_sock_cleanup
,05-19 09:21:46.741  4827  5181 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,05-19 09:21:46.741  3511  3982 V AlarmManager:  remove PendingIntent] PendingIntent{85a9845: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:46.751  4827  4974 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,05-19 09:21:46.751  4827  4974 D BluetoothAdapterProperties: Scan Mode:20
,05-19 09:21:46.761  3511  4459 V AlarmManager:  remove PendingIntent] PendingIntent{3560b9a: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:46.761  3939  4254 D BluetoothTile: handleUpdateState :  supported = true, enabled = false, enabling = false, connected = false, connecting = false, mController.getLastDeviceName() = null
,05-19 09:21:46.761  9409  9409 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
05-19 09:21:46.761  3511  4313 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,05-19 09:21:46.761  9689  9689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-19 09:21:46.781  3511  4198 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1da10bc u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cf9e5aa 4853:com.samsung.android.providers.context/u0a9}
,05-19 09:21:46.781  9689  9775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,05-19 09:21:46.781  9689  9775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-19 09:21:46.781  9689  9775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-19 09:21:46.781  9689  9775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-19 09:21:46.781  9689  9775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-19 09:21:46.781  9689  9775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
05-19 09:21:46.781  9689  9775 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-19 09:21:46.781  9689  9775 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-19 09:21:46.781  9689  9775 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-19 09:21:46.781  9689  9775 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,05-19 09:21:46.791  9409  9409 D DockEventReceiver: finishStartingService: stopping service
,05-19 09:21:46.791  9689  9775 D BluetoothAdapter: enable()
,05-19 09:21:46.791  9689  9753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-19 09:21:46.801  3511  4422 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1da10bc u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dc64001 4328:com.google.android.gms.persistent/u0a21}
,05-19 09:21:46.801  4328  4328 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
,05-19 09:21:46.821  3511  4070 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1da10bc u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7e09761 8967:com.sec.android.app.shealth:remote/u0a39}
,05-19 09:21:46.831  3511  4451 W ActivityManager: Permission Denial: getCurrentUser() from pid=9689, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
,05-19 09:21:46.831  3511  4451 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
05-19 09:21:46.831  3511  4451 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9689, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-19 09:21:46.831  3511  4451 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-19 09:21:46.831  3511  4451 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2852)
05-19 09:21:46.831  3511  4451 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2842)
05-19 09:21:46.831  3511  4451 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.setBtEnableFlag(BluetoothManagerService.java:1222)
05-19 09:21:46.831  3511  4451 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:254)
05-19 09:21:46.831  3511  4451 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:453)
05-19 09:21:46.831  3511  4451 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,05-19 09:21:46.831  3511  4451 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
05-19 09:21:46.831  3511  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1da10bc u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a2e0fe7 9409:com.android.settings/1000}
,05-19 09:21:46.831  3511  4451 D SettingsProvider: isChangeAllowed() : name = bluetooth_on
,05-19 09:21:46.841  9409  9409 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
05-19 09:21:46.841  9409  9409 D BluetoothStatusReceiver: AdapterStateChanged :: state = 10
,05-19 09:21:46.851  3511  4847 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1da10bc u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{71b783c 4827:com.android.bluetooth/1002}
,05-19 09:21:46.861  4827  9784 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
05-19 09:21:46.861  4827  9784 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,05-19 09:21:46.871  3511  4313 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1da10bc u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{40b9903 7208:com.google.android.apps.maps/u0a125}
,05-19 09:21:46.871  4827  4968 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BLE_TURN_ON
,05-19 09:21:46.881  3511  4313 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{957ca8 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cf9e5aa 4853:com.samsung.android.providers.context/u0a9}
,05-19 09:21:46.891  4827  4968 E BluetoothAdapterState: Don't defer BLE_TURN_ON request.
05-19 09:21:46.891  4827  4968 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ca63953
,05-19 09:21:46.911  3511  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d9173c1 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cf9e5aa 4853:com.samsung.android.providers.context/u0a9}
,05-19 09:21:46.941  4827  4974 I bt_hci  : shut_down
05-19 09:21:46.941  3511  4343 V AlarmManager:  remove PendingIntent] PendingIntent{794766: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:46.941  4827  5072 D bt_hwcfg: hw_epilog_process
,05-19 09:21:46.941  4827  5072 I bt_vendor: low_power_mode_cb
,05-19 09:21:46.941  4827  5072 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,05-19 09:21:46.941  4827  5072 I bt_vendor: epilog_cb
05-19 09:21:46.941  4827  5072 I bt_hci  : epilog_finished_callback
05-19 09:21:46.941  4827  4974 I bt_hci_h4: hal_close
,05-19 09:21:46.951  4827  4974 I bt_userial_vendor: device fd = 60 close
,05-19 09:21:46.951  3511  4451 V AlarmManager:  remove PendingIntent] PendingIntent{648aaa7: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:46.951  4827  4974 I bt_upio : upio_set_bluetooth_power(on: 0)
,05-19 09:21:46.951  3511  4407 V AlarmManager:  remove PendingIntent] PendingIntent{519bb54: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:46.951  4827  4969 D bt_stack_manager: event_shut_down_stack finished.
05-19 09:21:46.951  4827  4974 E BluetoothAdapterState: stateChangeCallback : 0
,05-19 09:21:46.951  4827  4968 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: DISABLED
,05-19 09:21:46.961  3511  4313 V AlarmManager:  remove PendingIntent] PendingIntent{a008afd: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:46.961  4827  4827 D BtGatt.DebugUtils: handleDebugAction() action=null
,05-19 09:21:46.961  4827  4968 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,05-19 09:21:46.961  4827  4827 D BtGatt.GattService: Received stop request...Stopping profile...
05-19 09:21:46.961  4827  4827 D BtGatt.GattService: stop()
05-19 09:21:46.961  4827  4827 D BtGatt.GattService: [GSIM LOG]: saveLogPref
05-19 09:21:46.961  4827  4827 D BtGatt.GattService: [GSIM LOG]: saveLogPref END
05-19 09:21:46.961  4827  4827 D BtGatt.GattService: cleanup binder
05-19 09:21:46.961  3511  3529 V AlarmManager:  remove PendingIntent] PendingIntent{94273f2: PendingIntentRecord{fcb4a43 com.android.bluetooth broadcastIntent}}
05-19 09:21:46.961  4827  4827 D BtGatt.AdvertiseManager: advertise clients cleared
05-19 09:21:46.961  4827  4827 D BtGatt.ScanManager: cleanup
,05-19 09:21:46.961  3511  4451 V AlarmManager:  remove PendingIntent] PendingIntent{d0138c0: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:46.961  4827  4827 D BtGatt.ScanManager: cleanup handler
,05-19 09:21:46.961  4827  4827 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, Message sending
05-19 09:21:46.961  4827  4827 E BtGatt.GattService: notifyProfileServiceStateChanged
05-19 09:21:46.971  4827  4827 E BluetoothAdapterService: handleMessage() - Message: 1
05-19 09:21:46.971  4827  4827 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, Before synchronized
,05-19 09:21:46.971  4827  4827 V BluetoothAdapterState: isTurningOff()=false
05-19 09:21:46.971  4827  4827 V BluetoothAdapterState: isTurningOn()=false
05-19 09:21:46.971  4827  4827 V BluetoothAdapterState: isBleTurningOn()=false
05-19 09:21:46.971  4827  4827 V BluetoothAdapterState: isBleTurningOff()=true
,05-19 09:21:46.971  4827  4968 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BLE_STOPPED
,05-19 09:21:46.971  3511  4313 V AlarmManager:  remove PendingIntent] PendingIntent{d4fd9f9: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:46.971  4827  4968 D BluetoothAdapterProperties: Setting state to 10
05-19 09:21:46.971  4827  4968 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
05-19 09:21:46.971  4827  4968 D BluetoothAdapterService: Bluetooth PBAP supproted is true
05-19 09:21:46.971  4827  4968 D BluetoothAdapterService: updateAdapterState state is 10
05-19 09:21:46.971  4827  4968 D BluetoothAdapterService: Autoconnection is available 
05-19 09:21:46.971  4827  4968 D BluetoothAdapterService: updateAdapterState prevState = 16newState = 10
05-19 09:21:46.971  4827  4968 D BluetoothAdapterService: BT on, init HID DEV count : 0
05-19 09:21:46.971  4827  4968 I BluetoothAdapterState: Entering OffState
05-19 09:21:46.971  3511  3647 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 11 receivers.
,05-19 09:21:46.971  3511  3529 V AlarmManager:  remove PendingIntent] PendingIntent{effdd3e: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:46.991  3511  3852 V AlarmManager:  remove PendingIntent] PendingIntent{44e479f: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:46.991  4827  4827 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
05-19 09:21:46.991  4827  4827 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,05-19 09:21:46.991  4827  4827 I BluetoothServiceJni: cleanupNative: return from cleanup
,05-19 09:21:46.991  4827  4969 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,05-19 09:21:46.991  4827  4827 I art     : System.exit called, status: 0
,05-19 09:21:46.991  4827  4827 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,05-19 09:21:47.021  3511  3984 I ActivityManager: Process com.android.bluetooth (pid 4827)(adj -11) has died(95,1807)
,05-19 09:21:47.021  3511  3984 D ActivityManager: cleanUpApplicationRecord -- 4827
05-19 09:21:47.021  3511  3984 D ActivityManager: isAutoRunBlockedApp:: com.android.bluetooth, Auto Run ON
05-19 09:21:47.021  3511  3984 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/.btservice.AdapterService in 1000ms
,05-19 09:21:47.371  9689  9775 D BluetoothAdapter: enable()
,05-19 09:21:47.381  3511  4451 W ActivityManager: Permission Denial: getCurrentUser() from pid=9689, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
,05-19 09:21:47.381  3511  4451 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
05-19 09:21:47.381  3511  4451 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9689, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-19 09:21:47.381  3511  4451 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-19 09:21:47.381  3511  4451 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2852)
05-19 09:21:47.381  3511  4451 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2842)
05-19 09:21:47.381  3511  4451 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.setBtEnableFlag(BluetoothManagerService.java:1222)
05-19 09:21:47.381  3511  4451 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:254)
05-19 09:21:47.381  3511  4451 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:453)
05-19 09:21:47.381  3511  4451 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,05-19 09:21:47.391  3511  4451 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,05-19 09:21:47.391  3511  4451 D SettingsProvider: isChangeAllowed() : name = bluetooth_on
,05-19 09:21:47.911  9689  9775 D BluetoothAdapter: enable()
,05-19 09:21:47.911  3511  4449 W ActivityManager: Permission Denial: getCurrentUser() from pid=9689, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
,05-19 09:21:47.911  3511  4449 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
05-19 09:21:47.911  3511  4449 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9689, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-19 09:21:47.911  3511  4449 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-19 09:21:47.911  3511  4449 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2852)
05-19 09:21:47.911  3511  4449 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2842)
05-19 09:21:47.911  3511  4449 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.setBtEnableFlag(BluetoothManagerService.java:1222)
05-19 09:21:47.911  3511  4449 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:254)
05-19 09:21:47.911  3511  4449 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:453)
05-19 09:21:47.911  3511  4449 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,05-19 09:21:47.911  3511  4449 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,05-19 09:21:47.911  3511  4449 D SettingsProvider: isChangeAllowed() : name = bluetooth_on
,05-19 09:21:48.061  9787  9787 E Zygote  : v2
05-19 09:21:48.061  9787  9787 I libpersona: KNOX_SDCARD checking this for 1002
05-19 09:21:48.061  9787  9787 I libpersona: KNOX_SDCARD not a persona
,05-19 09:21:48.061  9787  9787 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-19 09:21:48.061  9787  9787 E Zygote  : accessInfo : 0
,05-19 09:21:48.071  3511  3597 I ActivityManager: Start proc 9787:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,05-19 09:21:48.101  9787  9787 D TimaKeyStoreProvider: TimaSignature is unavailable
05-19 09:21:48.101  9787  9787 D ActivityThread: Added TimaKeyStore provider
,05-19 09:21:48.141  9787  9787 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
05-19 09:21:48.141  9787  9787 D RelationGraph: garbageCollect()
,05-19 09:21:48.141  9787  9787 W ResourcesManager: getTopLevelResources: /system/app/Bluetooth/Bluetooth.apk / 1.0 running in com.android.bluetooth rsrc of package com.android.bluetooth
,05-19 09:21:48.151  3511  4407 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-19 09:21:48.151  9787  9787 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-19 09:21:48.151  9787  9787 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 09:21:48.161  9787  9787 I InjectionManager: Inside getClassLibPath caller 
,05-19 09:21:48.191  9787  9787 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,05-19 09:21:48.221  9787  9787 D BtSettings.ProfileConfig: Adding GattService
,05-19 09:21:48.221  9787  9787 D BtSettings.ProfileConfig: Adding HeadsetService
,05-19 09:21:48.221  9787  9787 D BtSettings.ProfileConfig: Adding A2dpService
05-19 09:21:48.221  9787  9787 D BtSettings.ProfileConfig: Adding HidService
,05-19 09:21:48.221  9787  9787 D BtSettings.ProfileConfig: Adding HealthService
,05-19 09:21:48.231  9787  9787 D BtSettings.ProfileConfig: Adding PanService
,05-19 09:21:48.231  9787  9787 D BtSettings.ProfileConfig: Adding BluetoothMapService
,05-19 09:21:48.231  9787  9787 D BtSettings.ProfileConfig: Adding SapService
,05-19 09:21:48.231  9787  9787 D BtSettings.ProfileConfig: Adding HeadsetClientService
,05-19 09:21:48.231  9787  9787 D BtSettings.ProfileConfig: Adding A2dpSinkService
,05-19 09:21:48.231  9787  9787 D BtSettings.ProfileConfig: Adding BleAudioService
05-19 09:21:48.231  9787  9787 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,05-19 09:21:48.241  3511  4343 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.gatt.GattService
,05-19 09:21:48.241  3511  4343 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,05-19 09:21:48.241  3511  4343 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
05-19 09:21:48.241  3511  4343 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
05-19 09:21:48.241  3511  4343 D SettingsProvider: selectionArgs: false
05-19 09:21:48.241  3511  4343 D SettingsProvider: selectionArgs: 1002
05-19 09:21:48.241  3511  4343 D SettingsProvider: ret = -1
,05-19 09:21:48.241  3511  4847 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
05-19 09:21:48.241  3511  4847 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
05-19 09:21:48.241  3511  4847 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
05-19 09:21:48.241  3511  4847 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,05-19 09:21:48.241  3511  4847 D SettingsProvider: selectionArgs: false
05-19 09:21:48.241  3511  4847 D SettingsProvider: selectionArgs: 1002
05-19 09:21:48.241  3511  4847 D SettingsProvider: ret = -1
,05-19 09:21:48.241  3511  4313 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,05-19 09:21:48.241  3511  4313 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
05-19 09:21:48.241  3511  4313 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
05-19 09:21:48.241  3511  4313 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
05-19 09:21:48.241  3511  4313 D SettingsProvider: selectionArgs: false
05-19 09:21:48.241  3511  4313 D SettingsProvider: selectionArgs: 1002
,05-19 09:21:48.241  3511  4313 D SettingsProvider: ret = -1
,05-19 09:21:48.251  3511  4459 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.hid.HidService
,05-19 09:21:48.251  3511  4459 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
05-19 09:21:48.251  3511  4459 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
05-19 09:21:48.251  3511  4459 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
05-19 09:21:48.251  3511  4459 D SettingsProvider: selectionArgs: false
05-19 09:21:48.251  3511  4459 D SettingsProvider: selectionArgs: 1002
05-19 09:21:48.251  3511  4459 D SettingsProvider: ret = -1
,05-19 09:21:48.251  3511  3984 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.hdp.HealthService
,05-19 09:21:48.251  3511  3984 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
05-19 09:21:48.251  3511  3984 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
05-19 09:21:48.251  3511  3984 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
05-19 09:21:48.251  3511  3984 D SettingsProvider: selectionArgs: false
05-19 09:21:48.251  3511  3984 D SettingsProvider: selectionArgs: 1002
05-19 09:21:48.251  3511  3984 D SettingsProvider: ret = -1
,05-19 09:21:48.251  3511  4185 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.pan.PanService
05-19 09:21:48.251  3511  4185 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,05-19 09:21:48.251  3511  4185 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
05-19 09:21:48.251  3511  4185 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
05-19 09:21:48.251  3511  4185 D SettingsProvider: selectionArgs: false
05-19 09:21:48.251  3511  4185 D SettingsProvider: selectionArgs: 1002
05-19 09:21:48.251  3511  4185 D SettingsProvider: ret = -1
,05-19 09:21:48.251  3511  4451 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
,05-19 09:21:48.251  3511  4451 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
05-19 09:21:48.251  3511  4451 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
05-19 09:21:48.251  3511  4451 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,05-19 09:21:48.251  3511  4451 D SettingsProvider: selectionArgs: false
05-19 09:21:48.251  3511  4451 D SettingsProvider: selectionArgs: 1002
05-19 09:21:48.251  3511  4451 D SettingsProvider: ret = -1
,05-19 09:21:48.251  3511  4407 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.sap.SapService
,05-19 09:21:48.251  3511  4407 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
05-19 09:21:48.261  3511  4407 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
05-19 09:21:48.251  3511  4407 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
05-19 09:21:48.251  3511  4407 D SettingsProvider: selectionArgs: false
05-19 09:21:48.251  3511  4407 D SettingsProvider: selectionArgs: 1002
,05-19 09:21:48.261  3511  4407 D SettingsProvider: ret = -1
,05-19 09:21:48.261  3511  3852 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
05-19 09:21:48.261  3511  3852 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
05-19 09:21:48.261  3511  3852 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,05-19 09:21:48.261  3511  3852 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
05-19 09:21:48.261  3511  3852 D SettingsProvider: selectionArgs: false
05-19 09:21:48.261  3511  3852 D SettingsProvider: selectionArgs: 1002
05-19 09:21:48.261  3511  3852 D SettingsProvider: ret = -1
,05-19 09:21:48.261  3511  4198 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
,05-19 09:21:48.261  3511  4198 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
05-19 09:21:48.261  3511  4198 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
05-19 09:21:48.261  3511  4198 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
05-19 09:21:48.261  3511  4198 D SettingsProvider: selectionArgs: false
05-19 09:21:48.261  3511  4198 D SettingsProvider: selectionArgs: 1002
,05-19 09:21:48.261  3511  4198 D SettingsProvider: ret = -1
,05-19 09:21:48.261  3511  4449 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.broadcom.bt.service.bleaudio.BleAudioService
,05-19 09:21:48.261  3511  4449 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
05-19 09:21:48.261  3511  4449 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
05-19 09:21:48.261  3511  4449 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
05-19 09:21:48.261  3511  4449 D SettingsProvider: selectionArgs: false
05-19 09:21:48.261  3511  4449 D SettingsProvider: selectionArgs: 1002
05-19 09:21:48.261  3511  4449 D SettingsProvider: ret = -1
,05-19 09:21:48.261  9787  9787 D InjectionManager: InjectionManager
,05-19 09:21:48.261  9787  9787 D InjectionManager: fillFeatureStoreMap com.android.bluetooth
05-19 09:21:48.261  9787  9787 I InjectionManager: Constructor com.android.bluetooth, Feature store :{}
,05-19 09:21:48.261  9787  9787 I InjectionManager: featureStore :{}
,05-19 09:21:48.321  9787  9787 D BluetoothAdapterState: make() - Creating AdapterState
,05-19 09:21:48.321  9787  9787 I bt_bluedroid: init
05-19 09:21:48.321  9787  9800 I BluetoothAdapterState: Entering OffState
,05-19 09:21:48.331  9787  9801 E bt_core_counter: counter_init unable to open counter port
05-19 09:21:48.331  9787  9801 E bt_core_module: module_init failed to initialize "counter_module"
05-19 09:21:48.331  9787  9801 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
05-19 09:21:48.331  9787  9801 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
05-19 09:21:48.331  9787  9801 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
05-19 09:21:48.331  9787  9801 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,05-19 09:21:48.341  9787  9787 I bt_bluedroid: get_profile_interface socket
,05-19 09:21:48.341  9787  9787 W bt_btif : btif_get_adapter_property 2
05-19 09:21:48.341  9787  9787 W bt_btif : btif_get_adapter_property 1
,05-19 09:21:48.341  9787  9804 D BluetoothAdapterProperties: Address is:A8:81:95:E9:5F:6F
,05-19 09:21:48.341  9787  9804 E BluetoothServiceJni: populateRssiValuesNative
05-19 09:21:48.341  9787  9804 I bt_bluedroid: getModelRssiValues
05-19 09:21:48.341  9787  9804 E BluetoothServiceJni: model_rssi_values_callback: low = -75, mid = -65, high = 127
05-19 09:21:48.341  9787  9804 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -75,-65,127
05-19 09:21:48.341  9787  9787 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,05-19 09:21:48.341  9787  9804 D BluetoothAdapterProperties: Name is: Samsung Galaxy S7 edge
,05-19 09:21:48.341  3511  3511 D SettingsProvider: isChangeAllowed() : name = bluetooth_name
,05-19 09:21:48.341  9787  9787 I bt_bluedroid: get_profile_interface sdp
,05-19 09:21:48.361  9787  9798 I bt_bluedroid: config_hci_snoop_log
,05-19 09:21:48.361  3511  3647 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 11 receivers.
,05-19 09:21:48.371  9787  9800 D BluetoothAdapterState: Current state: OFF, message: BLE_TURN_ON
,05-19 09:21:48.371  9787  9800 D BluetoothAdapterProperties: Setting state to 14
,05-19 09:21:48.371  9787  9800 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
05-19 09:21:48.371  9787  9800 D BluetoothAdapterService: Bluetooth PBAP supproted is true
05-19 09:21:48.371  9787  9800 D BluetoothAdapterService: updateAdapterState state is 14
05-19 09:21:48.371  3511  3647 D BluetoothManagerService: Ble Turning On/Off, G state: 1, S state: 1
05-19 09:21:48.371  9787  9800 D BluetoothAdapterService: Autoconnection is available 
05-19 09:21:48.371  9787  9800 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 14
,05-19 09:21:48.371  9787  9800 D BluetoothSecureManager: getInstant: null
,05-19 09:21:48.371  9787  9800 D BluetoothSecureManager: calling getMethod for getService
05-19 09:21:48.371  9787  9800 D BluetoothSecureManager: calling getService
,05-19 09:21:48.371  9787  9800 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@f9897bc
,05-19 09:21:48.381  3511  4449 D BluetoothSecureManagerService: isSecureModeEnabled
05-19 09:21:48.381  3511  4449 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
05-19 09:21:48.381  9787  9800 D BtConfig.SecureMode: isSecureModeOn:false
,05-19 09:21:48.381  9787  9800 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,05-19 09:21:48.381  9787  9800 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
05-19 09:21:48.381  9787  9800 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
05-19 09:21:48.381  9787  9800 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
05-19 09:21:48.381  9787  9800 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,05-19 09:21:48.381  9787  9800 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
05-19 09:21:48.381  9787  9800 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,05-19 09:21:48.381  9787  9800 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
05-19 09:21:48.381  9787  9800 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,05-19 09:21:48.381  9787  9800 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
05-19 09:21:48.381  9787  9800 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,05-19 09:21:48.381  9787  9800 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
,05-19 09:21:48.381  9787  9800 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,05-19 09:21:48.381  9787  9800 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
05-19 09:21:48.381  9787  9800 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
,05-19 09:21:48.381  9787  9800 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.sap.SapService
05-19 09:21:48.381  9787  9800 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,05-19 09:21:48.391  9787  9800 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
,05-19 09:21:48.391  9787  9800 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
05-19 09:21:48.391  9787  9800 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
,05-19 09:21:48.391  9787  9800 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.bleaudio.BleAudioService
05-19 09:21:48.391  9787  9800 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.bleaudio.BleAudioService
,05-19 09:21:48.391  9787  9800 D BluetoothBondStateMachine: make
,05-19 09:21:48.391  9787  9805 I BluetoothBondStateMachine: StableState(): Entering Off State
,05-19 09:21:48.411  9787  9800 I BluetoothAdapterState: Entering PendingCommandState
,05-19 09:21:48.411  9787  9787 I BtGatt.JNI: classInitNative(L992): classInitNative: Success!
,05-19 09:21:48.411  9787  9787 D BtGatt.DebugUtils: handleDebugAction() action=null
,05-19 09:21:48.411  9787  9787 D BtGatt.GattService: Received start request. Starting profile...
,05-19 09:21:48.411  9787  9787 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ca63953
,05-19 09:21:48.411  9787  9787 D BtGatt.GattService: start()
,05-19 09:21:48.411  9787  9787 I bt_bluedroid: get_profile_interface gatt
05-19 09:21:48.421  9787  9787 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ca63953
05-19 09:21:48.421  9787  9787 D BtGatt.AdvertiseManager: advertise manager created
05-19 09:21:48.421  9787  9787 D BtGatt.AdvertiseManager: start
,05-19 09:21:48.421  9689  9775 D BluetoothAdapter: enable()
,05-19 09:21:48.421  9787  9787 D BtGatt.ScanManager: start
,05-19 09:21:48.431  9787  9787 D BtGatt.GattService: [GSIM LOG]: loadLogPref
,05-19 09:21:48.431  3511  4343 W ActivityManager: Permission Denial: getCurrentUser() from pid=9689, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-19 09:21:48.431  3511  4343 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
05-19 09:21:48.431  3511  4343 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9689, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-19 09:21:48.431  3511  4343 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-19 09:21:48.431  3511  4343 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2852)
05-19 09:21:48.431  3511  4343 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2842)
05-19 09:21:48.431  3511  4343 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.setBtEnableFlag(BluetoothManagerService.java:1222)
05-19 09:21:48.431  3511  4343 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:254)
05-19 09:21:48.431  3511  4343 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:453)
,05-19 09:21:48.431  3511  4343 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
05-19 09:21:48.431  3511  4343 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,05-19 09:21:48.431  3511  4343 D SettingsProvider: isChangeAllowed() : name = bluetooth_on
,05-19 09:21:48.431  3511  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4f3ccab u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cf9e5aa 4853:com.samsung.android.providers.context/u0a9}
,05-19 09:21:48.441  9787  9800 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BLE_TURN_ON
,05-19 09:21:48.441  9787  9800 E BluetoothAdapterState: Don't defer BLE_TURN_ON request.
,05-19 09:21:48.451  9787  9787 D BtGatt.GattService: [GSIM LOG]: loadLogPref END
,05-19 09:21:48.451  9787  9787 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, Message sending
05-19 09:21:48.451  9787  9787 E BtGatt.GattService: notifyProfileServiceStateChanged
,05-19 09:21:48.451  9787  9787 E BluetoothAdapterService: handleMessage() - Message: 1
05-19 09:21:48.451  9787  9787 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, Before synchronized
,05-19 09:21:48.461  9787  9787 V BluetoothAdapterState: isTurningOff()=false
,05-19 09:21:48.461  9787  9787 V BluetoothAdapterState: isTurningOn()=false
05-19 09:21:48.461  9787  9787 V BluetoothAdapterState: isBleTurningOn()=true
05-19 09:21:48.461  9787  9787 V BluetoothAdapterState: isBleTurningOff()=false
05-19 09:21:48.461  9787  9800 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BLE_STARTED
,05-19 09:21:48.461  9787  9800 I bt_bluedroid: bt_bluedroid
,05-19 09:21:48.461  9787  9801 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,05-19 09:21:48.461  9787  9801 I bt_hci  : start_up
,05-19 09:21:48.471  9787  9801 I bt_vendor: alloc value 0xf378e171
05-19 09:21:48.471  9787  9801 I bt_vendor: init
05-19 09:21:48.471  9787  9801 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
05-19 09:21:48.471  9787  9801 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
05-19 09:21:48.471  9787  9801 I bt_upio : upio_set_bluetooth_power(on: 0)
05-19 09:21:48.471  9787  9801 I bt_upio : upio_set_bluetooth_power(on: 1)
,05-19 09:21:48.581  9787  9801 D bt_hci  : start_up starting async portion
,05-19 09:21:48.581  9787  9817 I bt_hci  : event_finish_startup
05-19 09:21:48.581  9787  9817 I bt_hci_h4: hal_open
05-19 09:21:48.581  9787  9817 I bt_userial_vendor: userial vendor open: opening /dev/ttySAC1
,05-19 09:21:48.581  9787  9817 I bt_userial_vendor: userial_vendor_open():UART is setup
,05-19 09:21:48.581  9787  9817 I bt_userial_vendor: device fd = 60 open
05-19 09:21:48.581  9787  9817 E bt_hwcfg: Start CFG HW, HCI reset
,05-19 09:21:48.591  9787  9817 E bt_hwcfg: Read Local Name after HCI reset
,05-19 09:21:48.591  3511  4847 V AlarmManager:  remove PendingIntent] PendingIntent{3208887: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:48.611  9787  9817 D bt_hwcfg: Chipset BCM4359C0
05-19 09:21:48.611  9787  9817 D bt_hwcfg: Target name = [BCM4359C0]
,05-19 09:21:48.611  9787  9817 I bt_hwcfg: module_type[semco_b90s_c0].
,05-19 09:21:48.611  9787  9817 E bt_hwcfg: patchram path ORG . BCM4359C0
05-19 09:21:48.611  9787  9817 E bt_hwcfg: patchram path ORG .. BCM4359C0
05-19 09:21:48.611  9787  9817 E bt_hwcfg: patchram path ORG bcm4359C0_V0044.0061_murata.hcd BCM4359C0
05-19 09:21:48.611  9787  9817 E bt_hwcfg: patchram path ORG companion_2l1_master_setfile.bin BCM4359C0
05-19 09:21:48.611  9787  9817 E bt_hwcfg: patchram path ORG companion_2l1_mode_setfile.bin BCM4359C0
,05-19 09:21:48.611  9787  9817 E bt_hwcfg: patchram path ORG companion_fw_2l1.bin BCM4359C0
05-19 09:21:48.611  9787  9817 E bt_hwcfg: patchram path ORG companion_fw_imx260.bin BCM4359C0
05-19 09:21:48.611  9787  9817 E bt_hwcfg: patchram path ORG companion_imx260_master_setfile.bin BCM4359C0
05-19 09:21:48.611  9787  9817 E bt_hwcfg: patchram path ORG companion_imx260_mode_setfile.bin BCM4359C0
05-19 09:21:48.611  9787  9817 E bt_hwcfg: patchram path ORG fimc_is_fw2_2l1.bin BCM4359C0
05-19 09:21:48.611  9787  9817 E bt_hwcfg: patchram path ORG fimc_is_fw2_imx260.bin BCM4359C0
,05-19 09:21:48.611  9787  9817 E bt_hwcfg: patchram path ORG mfc_fw.bin BCM4359C0
05-19 09:21:48.611  9787  9817 E bt_hwcfg: patchram path ORG ois_fw_dom.bin BCM4359C0
05-19 09:21:48.611  9787  9817 E bt_hwcfg: patchram path ORG ois_fw_sec.bin BCM4359C0
05-19 09:21:48.611  9787  9817 E bt_hwcfg: patchram path ORG sec_s3nrn81_firmware.bin BCM4359C0
05-19 09:21:48.611  9787  9817 E bt_hwcfg: patchram path ORG seiren_fw_dram.bin BCM4359C0
05-19 09:21:48.611  9787  9817 E bt_hwcfg: patchram path ORG seiren_fw_sram.bin BCM4359C0
05-19 09:21:48.611  9787  9817 E bt_hwcfg: patchram path ORG setfile_2l1.bin BCM4359C0
,05-19 09:21:48.611  9787  9817 E bt_hwcfg: patchram path ORG setfile_4e6.bin BCM4359C0
05-19 09:21:48.611  9787  9817 E bt_hwcfg: patchram path ORG setfile_imx260.bin BCM4359C0
05-19 09:21:48.611  9787  9817 E bt_hwcfg: patchram path ORG bcm4359C0_V0044.0062_semco.hcd BCM4359C0
05-19 09:21:48.611  9787  9817 I bt_hwcfg: patch(org) : bcm4359C0_V0044.0062_semco.hcd
05-19 09:21:48.611  9787  9817 I bt_hwcfg: Found patchfile: /vendor/firmware/bcm4359C0_V0044.0062_semco.hcd
,05-19 09:21:48.611  9787  9817 E bt_hwcfg: ORG patchram base 0044
05-19 09:21:48.611  9787  9817 E bt_hwcfg: ORG patchram minor 0062
05-19 09:21:48.611  9787  9817 E bt_hwcfg: fw ver (org)44.62
05-19 09:21:48.611  9787  9817 E bt_hwcfg: Final Patchram is /vendor/firmware/bcm4359C0_V0044.0062_semco.hcd
,05-19 09:21:48.621  9787  9817 I bt_hwcfg: Axi patch failure or not include AXI patching
,05-19 09:21:48.621  3511  4185 V AlarmManager:  remove PendingIntent] PendingIntent{ddd73b4: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:48.621  9787  9817 I bt_hwcfg: bt vendor lib baud_1: set UART baud 3000000
,05-19 09:21:48.631  3511  3852 V AlarmManager:  remove PendingIntent] PendingIntent{1c34bdd: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:48.731  3511  4422 V AlarmManager:  remove PendingIntent] PendingIntent{b32d352: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:48.741  3511  3529 V AlarmManager:  remove PendingIntent] PendingIntent{4732623: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:48.781  3511  4847 V AlarmManager:  remove PendingIntent] PendingIntent{cb81720: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:48.791  3511  3984 V AlarmManager:  remove PendingIntent] PendingIntent{42dc8d9: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:48.811  3511  4451 V AlarmManager:  remove PendingIntent] PendingIntent{b86d29e: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:48.821  3511  4449 V AlarmManager:  remove PendingIntent] PendingIntent{c8017f: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:48.831  3511  3982 V AlarmManager:  remove PendingIntent] PendingIntent{cd7854c: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:48.841  3511  4343 V AlarmManager:  remove PendingIntent] PendingIntent{7291995: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:48.841  3511  4459 V AlarmManager:  remove PendingIntent] PendingIntent{897aaa: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:48.851  3511  4407 V AlarmManager:  remove PendingIntent] PendingIntent{765369b: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:48.861  3511  4198 V AlarmManager:  remove PendingIntent] PendingIntent{39daa38: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:48.871  3511  4070 V AlarmManager:  remove PendingIntent] PendingIntent{34eba11: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:48.881  3511  4847 V AlarmManager:  remove PendingIntent] PendingIntent{f5c9776: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:48.881  3511  3984 V AlarmManager:  remove PendingIntent] PendingIntent{bd6a177: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:48.891  3511  4451 V AlarmManager:  remove PendingIntent] PendingIntent{89f31e4: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:48.901  3511  4449 V AlarmManager:  remove PendingIntent] PendingIntent{753e64d: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:48.911  3511  3982 V AlarmManager:  remove PendingIntent] PendingIntent{b72b502: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:48.911  3511  3528 V AlarmManager:  remove PendingIntent] PendingIntent{489de13: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:48.921  3511  4459 V AlarmManager:  remove PendingIntent] PendingIntent{60f8850: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:48.921  3511  4407 V AlarmManager:  remove PendingIntent] PendingIntent{e059a49: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:48.931  3511  4198 V AlarmManager:  remove PendingIntent] PendingIntent{adb1f4e: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:48.941  3511  4070 V AlarmManager:  remove PendingIntent] PendingIntent{72a486f: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:48.941  3511  4343 V AlarmManager:  remove PendingIntent] PendingIntent{3ecd97c: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:48.951  9689  9775 D BluetoothAdapter: enable()
,05-19 09:21:48.961  3511  3852 W ActivityManager: Permission Denial: getCurrentUser() from pid=9689, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
,05-19 09:21:48.961  3511  3852 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
05-19 09:21:48.961  3511  3852 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9689, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-19 09:21:48.961  3511  3852 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-19 09:21:48.961  3511  3852 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2852)
05-19 09:21:48.961  3511  3852 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2842)
05-19 09:21:48.961  3511  3852 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.setBtEnableFlag(BluetoothManagerService.java:1222)
05-19 09:21:48.961  3511  3852 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:254)
05-19 09:21:48.961  3511  3852 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:453)
05-19 09:21:48.961  3511  3852 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
05-19 09:21:48.961  3511  3852 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
05-19 09:21:48.961  3511  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8049205 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cf9e5aa 4853:com.samsung.android.providers.context/u0a9}
05-19 09:21:48.961  3511  4198 V AlarmManager:  remove PendingIntent] PendingIntent{34de25a: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:48.971  3511  3852 D SettingsProvider: isChangeAllowed() : name = bluetooth_on
,05-19 09:21:48.981  9787  9800 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BLE_TURN_ON
05-19 09:21:48.981  3511  3984 V AlarmManager:  remove PendingIntent] PendingIntent{ebcfc8b: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:48.981  9787  9800 E BluetoothAdapterState: Don't defer BLE_TURN_ON request.
,05-19 09:21:48.981  3511  4198 V AlarmManager:  remove PendingIntent] PendingIntent{9ec1168: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:48.991  9787  9817 I bt_hwcfg: bt vendor lib: set UART baud 115200
05-19 09:21:48.991  9787  9817 I bt_hwcfg: FW Download delta = 404028
05-19 09:21:48.991  9787  9817 D bt_hwcfg: Settlement delay -- 100 ms
05-19 09:21:48.991  9787  9817 I bt_hwcfg: Setting fw settlement delay to 100 
05-19 09:21:48.991  3511  3852 V AlarmManager:  remove PendingIntent] PendingIntent{5414981: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:48.991  3511  3982 V AlarmManager:  remove PendingIntent] PendingIntent{bf7ca26: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.001  3511  4313 V AlarmManager:  remove PendingIntent] PendingIntent{77cd667: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.001  3511  3984 V AlarmManager:  remove PendingIntent] PendingIntent{424dc14: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.011  3511  4422 V AlarmManager:  remove PendingIntent] PendingIntent{a37fcbd: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.011  3511  4070 V AlarmManager:  remove PendingIntent] PendingIntent{662b2: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.011  3511  4449 V AlarmManager:  remove PendingIntent] PendingIntent{c767203: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.021  3511  4847 V AlarmManager:  remove PendingIntent] PendingIntent{67da580: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.021  3511  4185 V AlarmManager:  remove PendingIntent] PendingIntent{ceca7b9: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.031  3511  4451 V AlarmManager:  remove PendingIntent] PendingIntent{df3f7fe: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.031  3511  4459 V AlarmManager:  remove PendingIntent] PendingIntent{2e42b5f: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.031  3511  3529 V AlarmManager:  remove PendingIntent] PendingIntent{ad799ac: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.041  3511  4343 V AlarmManager:  remove PendingIntent] PendingIntent{5a70675: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.041  3511  3528 V AlarmManager:  remove PendingIntent] PendingIntent{f93960a: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.051  3511  4407 V AlarmManager:  remove PendingIntent] PendingIntent{f4a1e7b: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.051  3511  4198 V AlarmManager:  remove PendingIntent] PendingIntent{5faa498: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.061  3511  3852 V AlarmManager:  remove PendingIntent] PendingIntent{f6e94f1: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.061  3511  3982 V AlarmManager:  remove PendingIntent] PendingIntent{6dd08d6: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.061  3511  4313 V AlarmManager:  remove PendingIntent] PendingIntent{522757: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.071  3511  3984 V AlarmManager:  remove PendingIntent] PendingIntent{f417244: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.071  3511  4422 V AlarmManager:  remove PendingIntent] PendingIntent{4468f2d: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.081  3511  4070 V AlarmManager:  remove PendingIntent] PendingIntent{b78dc62: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.081  3511  4449 V AlarmManager:  remove PendingIntent] PendingIntent{b67e1f3: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.091  3511  4847 V AlarmManager:  remove PendingIntent] PendingIntent{7056eb0: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.091  3511  4185 V AlarmManager:  remove PendingIntent] PendingIntent{129f129: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.101  3511  4451 V AlarmManager:  remove PendingIntent] PendingIntent{50c5cae: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.101  3511  4459 V AlarmManager:  remove PendingIntent] PendingIntent{714aa4f: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.101  3511  3529 V AlarmManager:  remove PendingIntent] PendingIntent{7cac5dc: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.111  3511  4343 V AlarmManager:  remove PendingIntent] PendingIntent{dc776e5: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.111  3511  3528 V AlarmManager:  remove PendingIntent] PendingIntent{e4595ba: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.121  9787  9817 I bt_hwcfg: bt vendor lib baud_2: set UART baud 3000000
,05-19 09:21:49.121  3511  4407 V AlarmManager:  remove PendingIntent] PendingIntent{f1b9c6b: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.121  3511  4198 V AlarmManager:  remove PendingIntent] PendingIntent{e2c63c8: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.131  3511  3852 V AlarmManager:  remove PendingIntent] PendingIntent{3fd9c61: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.131  3511  3982 V AlarmManager:  remove PendingIntent] PendingIntent{ca75386: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.141  3511  4313 V AlarmManager:  remove PendingIntent] PendingIntent{e559447: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.141  3511  3984 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,05-19 09:21:49.141  3511  3984 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4333, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-19 09:21:49.141  3511  3984 D BatteryService: online:4, current avg:89, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:37
05-19 09:21:49.141  3511  4407 V AlarmManager:  remove PendingIntent] PendingIntent{387f474: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.141  3511  3511 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-19 09:21:49.141  3511  3511 I MotionRecognitionService: Plugged
,05-19 09:21:49.141  3511  3511 D MotionRecognitionService:   cableConnection= 1
05-19 09:21:49.141  3511  3511 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-19 09:21:49.141  3511  3511 D MotionRecognitionService: skip setTransmitPower. 
,05-19 09:21:49.151  3511  3860 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-19 09:21:49.151  3939  3939 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
05-19 09:21:49.151  3939  3939 D KeyguardUpdateMonitor: handleBatteryUpdate
,05-19 09:21:49.151  3939  3939 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-19 09:21:49.151  3939  3939 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
05-19 09:21:49.151  3939  3939 D PowerUI.Notification: There is no change about charging status, so return!
,05-19 09:21:49.151  4867  4867 D CommonServiceConfiguration: getStringValueSetting
,05-19 09:21:49.161  4867  4867 D BatteryMonitor: new battery level: 100
,05-19 09:21:49.161  3511  4449 V AlarmManager:  remove PendingIntent] PendingIntent{3169d9d: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.171  3511  4847 V AlarmManager:  remove PendingIntent] PendingIntent{9152212: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.171  3939  3939 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
05-19 09:21:49.171  3939  3939 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,05-19 09:21:49.171  3511  3984 V AlarmManager:  remove PendingIntent] PendingIntent{a4d2de3: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.181  3511  4198 V AlarmManager:  remove PendingIntent] PendingIntent{769e3e0: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:49.181  3511  4451 V AlarmManager:  remove PendingIntent] PendingIntent{ac47699: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.191  3511  4449 V AlarmManager:  remove PendingIntent] PendingIntent{51f4d5e: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.191  3511  4847 V AlarmManager:  remove PendingIntent] PendingIntent{c9ac53f: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.191  3511  4407 V AlarmManager:  remove PendingIntent] PendingIntent{3b95e0c: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.201  3511  4459 V AlarmManager:  remove PendingIntent] PendingIntent{9dce355: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.201  3511  4070 V AlarmManager:  remove PendingIntent] PendingIntent{90ee16a: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.211  3511  3982 V AlarmManager:  remove PendingIntent] PendingIntent{600765b: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.211  3511  4313 V AlarmManager:  remove PendingIntent] PendingIntent{7a44ef8: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.221  3511  4407 V AlarmManager:  remove PendingIntent] PendingIntent{cd55fd1: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.221  9787  9817 I bt_hwcfg: vendor lib fwcfg completed
,05-19 09:21:49.221  9787  9817 I bt_vendor: firmware callback
05-19 09:21:49.221  9787  9817 I bt_hci  : firmware_config_callback
05-19 09:21:49.221  3511  4459 V AlarmManager:  remove PendingIntent] PendingIntent{6b1aa36: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.221  9787  9822 I bt_btu_task: Bluetooth chip preload is complete
,05-19 09:21:49.221  9787  9822 I         : BTE_InitTraceLevels -- TRC_HCI
,05-19 09:21:49.221  9787  9822 I         : BTE_InitTraceLevels -- TRC_L2CAP
05-19 09:21:49.221  9787  9822 I         : BTE_InitTraceLevels -- TRC_RFCOMM
05-19 09:21:49.221  9787  9822 I         : BTE_InitTraceLevels -- TRC_AVDT
05-19 09:21:49.221  9787  9822 I         : BTE_InitTraceLevels -- TRC_AVRC
05-19 09:21:49.221  9787  9822 I         : BTE_InitTraceLevels -- TRC_A2D
,05-19 09:21:49.221  9787  9822 I         : BTE_InitTraceLevels -- TRC_BNEP
05-19 09:21:49.221  9787  9822 I         : BTE_InitTraceLevels -- TRC_BTM
05-19 09:21:49.221  9787  9822 I         : BTE_InitTraceLevels -- TRC_GAP
05-19 09:21:49.221  9787  9822 I         : BTE_InitTraceLevels -- TRC_PAN
05-19 09:21:49.221  9787  9822 I         : BTE_InitTraceLevels -- TRC_SDP
05-19 09:21:49.221  9787  9822 I         : BTE_InitTraceLevels -- TRC_GATT
,05-19 09:21:49.221  9787  9822 I         : BTE_InitTraceLevels -- TRC_SMP
05-19 09:21:49.221  9787  9822 I         : BTE_InitTraceLevels -- TRC_BTAPP
05-19 09:21:49.221  9787  9822 I         : BTE_InitTraceLevels -- TRC_BTIF
05-19 09:21:49.221  9787  9822 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,05-19 09:21:49.221  3511  4070 V AlarmManager:  remove PendingIntent] PendingIntent{7461d37: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.231  3511  3982 V AlarmManager:  remove PendingIntent] PendingIntent{54b62a4: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.231  3511  3984 V AlarmManager:  remove PendingIntent] PendingIntent{7ff280d: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.241  3511  4185 V AlarmManager:  remove PendingIntent] PendingIntent{ce633c2: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.241  3511  4198 V AlarmManager:  remove PendingIntent] PendingIntent{bd555d3: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.251  3511  4451 V AlarmManager:  remove PendingIntent] PendingIntent{e2e0510: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.251  3511  4449 V AlarmManager:  remove PendingIntent] PendingIntent{9833809: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.251  3511  4847 V AlarmManager:  remove PendingIntent] PendingIntent{7e7ca0e: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.261  3511  3528 V AlarmManager:  remove PendingIntent] PendingIntent{2157c2f: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.261  3511  4422 V AlarmManager:  remove PendingIntent] PendingIntent{a56623c: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.271  3511  3852 V AlarmManager:  remove PendingIntent] PendingIntent{f1e4bc5: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.271  3511  3529 V AlarmManager:  remove PendingIntent] PendingIntent{a5a791a: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.281  3511  4343 V AlarmManager:  remove PendingIntent] PendingIntent{d87ac4b: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.281  3511  4313 V AlarmManager:  remove PendingIntent] PendingIntent{6456628: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.291  3511  4407 V AlarmManager:  remove PendingIntent] PendingIntent{b9cdf41: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.291  3511  4459 V AlarmManager:  remove PendingIntent] PendingIntent{b170ce6: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.301  3511  4070 V AlarmManager:  remove PendingIntent] PendingIntent{ea2c227: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.301  3511  3982 V AlarmManager:  remove PendingIntent] PendingIntent{39ebcd4: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.311  3511  3984 V AlarmManager:  remove PendingIntent] PendingIntent{8172e7d: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.311  9787  9822 W bt_l2cap: l2c_link_processs_ble_num_bufs 15
,05-19 09:21:49.311  9787  9822 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf36de7ad
05-19 09:21:49.311  9787  9822 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf36de7ad 
05-19 09:21:49.311  9787  9822 E bt_btm  : btm_ble_set_search_if search_if=4
,05-19 09:21:49.311  3511  4185 V AlarmManager:  remove PendingIntent] PendingIntent{3b71172: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.311  3511  4198 V AlarmManager:  remove PendingIntent] PendingIntent{c6f59c3: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.321  3511  4451 V AlarmManager:  remove PendingIntent] PendingIntent{894d240: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.321  9787  9804 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 9 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 20 mIsExtendedScanSupported = true mIsDebugLogSupported = false mAobleSupported = 1
,05-19 09:21:49.321  3511  4449 V AlarmManager:  remove PendingIntent] PendingIntent{ced3579: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.331  3511  4847 V AlarmManager:  remove PendingIntent] PendingIntent{be0d2be: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.331  3511  3528 V AlarmManager:  remove PendingIntent] PendingIntent{be3cf1f: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.341  9787  9804 E bt_btif : btif_transfer_context() Caller thread is BTIF thread. Don't try context switch.
,05-19 09:21:49.341  9787  9804 D bt_hci  : do_postload posting postload work item
05-19 09:21:49.341  3511  4198 V AlarmManager:  remove PendingIntent] PendingIntent{a14d26c: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:49.341  9787  9817 I bt_hci  : event_postload
05-19 09:21:49.341  3511  3529 V AlarmManager:  remove PendingIntent] PendingIntent{e82b035: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:49.341  9787  9804 E bt_btif_sock: btif_sock_init: !vhci_init
05-19 09:21:49.341  9787  9817 D bt_hwcfg: hw_sco_config
05-19 09:21:49.341  9787  9817 I bt_vendor: sco_config_cb
05-19 09:21:49.341  9787  9804 E bt_btif : ## init_cmd_fd assert ts[h].cmd_fdr == -1 && ts[h].cmd_fdw == -1 failed at line:289 ##
05-19 09:21:49.341  9787  9817 I bt_hci  : sco_config_callback postload finished.
05-19 09:21:49.341  9787  9804 D bt_bte_conf: Device ID record 1 : primary
05-19 09:21:49.341  9787  9804 D bt_bte_conf:   vendorId            = 0075
05-19 09:21:49.341  9787  9804 D bt_bte_conf:   vendorIdSource      = 0001
05-19 09:21:49.341  9787  9804 D bt_bte_conf:   product             = 0100
05-19 09:21:49.341  9787  9804 D bt_bte_conf:   version             = 0200
05-19 09:21:49.341  9787  9804 D bt_bte_conf:   clientExecutableURL = 
05-19 09:21:49.341  9787  9804 D bt_bte_conf:   serviceDescription  = 
05-19 09:21:49.341  9787  9804 D bt_bte_conf:   documentationURL    = 
05-19 09:21:49.341  9787  9804 D bt_bte_conf: bte_load_did_conf no section named DID2.
05-19 09:21:49.341  9787  9801 D bt_stack_manager: event_start_up_stack finished
05-19 09:21:49.341  9787  9804 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  14 , val : 15
05-19 09:21:49.341  9787  9804 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  15 , val : 8
05-19 09:21:49.341  9787  9804 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  16 , val : 24838
05-19 09:21:49.341  9787  9804 D BluetoothDataManager: UpdateLocalInfo for String is called!!! type : 17, val : BCM4359C0 Hero SWB-B90S eLNA-0044
05-19 09:21:49.341  9787  9804 D BluetoothDataManager: firmwareVersion from Property : bcm4359C0_V0044.0062_semco.hcd
05-19 09:21:49.341  9787  9804 E BluetoothAdapterState: stateChangeCallback : 1
05-19 09:21:49.341  9787  9800 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: ENABLED_READY
05-19 09:21:49.351  3511  4185 V AlarmManager:  remove PendingIntent] PendingIntent{1003e3b: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:49.341  9787  9800 D BluetoothAdapterProperties: Setting state to 15
05-19 09:21:49.341  9787  9800 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
05-19 09:21:49.351  9787  9800 D BluetoothAdapterService: Bluetooth PBAP supproted is true
05-19 09:21:49.351  9787  9800 D BluetoothAdapterService: updateAdapterState state is 15
05-19 09:21:49.351  9787  9800 D BluetoothAdapterService: Autoconnection is available 
05-19 09:21:49.351  3511  3647 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
05-19 09:21:49.351  9787  9800 D BluetoothAdapterService: updateAdapterState prevState = 14newState = 15
05-19 09:21:49.351  9787  9800 I BluetoothAdapterState: Entering BleOnState
05-19 09:21:49.351  9787  9817 I bt_vendor: low_power_mode_cb
05-19 09:21:49.361  3511  3647 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
05-19 09:21:49.361  9787  9800 D BluetoothAdapterState: Current state: BLE ON, message: USER_TURN_ON
05-19 09:21:49.361  3511  4459 V AlarmManager:  remove PendingIntent] PendingIntent{cb2a958: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:49.361  9787  9800 D BluetoothAdapterProperties: Setting state to 11
05-19 09:21:49.361  9787  9800 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
05-19 09:21:49.361  9787  9800 D BluetoothAdapterService: Bluetooth PBAP supproted is true
05-19 09:21:49.361  9787  9800 D BluetoothAdapterServi,ce: updateAdapterState state is 11
05-19 09:21:49.361  3511  3647 D BluetoothManagerService: Turning On/Off, G state: 2, S state: 2, mBLE count: 0, s BLE count: 0
05-19 09:21:49.371  9787  9800 D BluetoothAdapterService: Autoconnection is available 
05-19 09:21:49.371  9787  9800 D BluetoothAdapterService: updateAdapterState prevState = 15newState = 11
05-19 09:21:49.371  9787  9800 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
05-19 09:21:49.371  3511  3511 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
05-19 09:21:49.371  9787  9800 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
05-19 09:21:49.371  3511  3511 I InputMethodManagerService: [BT Setting State] State =11
05-19 09:21:49.371  9787  9800 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
05-19 09:21:49.371  3939  4163 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
05-19 09:21:49.371  3939  4163 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
05-19 09:21:49.371  4344  4344 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
05-19 09:21:49.371  4917  4917 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
05-19 09:21:49.371  3511  3511 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
05-19 09:21:49.371  3511  3511 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
05-19 09:21:49.371  3511  3511 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
05-19 09:21:49.381  9409  9409 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
05-19 09:21:49.381  9409  9409 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
05-19 09:21:49.381  9689  9689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
05-19 09:21:49.381  3511  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9bb1ab1 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a2e0fe7 9409:com.android.settings/1000}
05-19 09:21:49.381  3511  4449 V AlarmManager:  remove PendingIntent] PendingIntent{5aa8317: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:49.391  9787  9800 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
05-19 09:21:49.401  3939  4254 D BluetoothTile: handleUpdateState :  supported = true, enabled = false, enabling = true, connected = false, connecting = false, mController.getLastDeviceName() = null
05-19 09:21:49.401  9787  9787 D HeadsetService: Received start request. Starting profile...
05-19 09:21:49.401  9787  9787 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ca63953
05-19 09:21:49.401  3511  4198 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
05-19 09:21:49.401  9787  9787 D HeadsetProvider: make
05-19 09:21:49.401  9787  9787 D HeadsetProvider: HeadsetProvider
05-19 09:21:49.401  3939  3939 D QSTileView: handleLabelStateChanged() label = Bluetooth cellWidth 272
,05-19 09:21:49.401  9787  9787 I HeadsetProvider: clearAllHeadsetSettings(0)
,05-19 09:21:49.401  3511  4070 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9bb1ab1 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cf9e5aa 4853:com.samsung.android.providers.context/u0a9}
,05-19 09:21:49.411  9787  9787 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,05-19 09:21:49.411  9787  9787 D HeadsetStateMachine: make
,05-19 09:21:49.411  9787  9787 E HeadsetStateMachine: # of Max HF connection is 3
,05-19 09:21:49.421  9787  9800 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,05-19 09:21:49.431  3511  4459 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9bb1ab1 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dc64001 4328:com.google.android.gms.persistent/u0a21}
,05-19 09:21:49.431  4328  4328 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
,05-19 09:21:49.441  9787  9800 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,05-19 09:21:49.451  3511  4459 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9bb1ab1 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7e09761 8967:com.sec.android.app.shealth:remote/u0a39}
,05-19 09:21:49.451  3511  4343 V AlarmManager:  remove PendingIntent] PendingIntent{445676e: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.461  9787  9800 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,05-19 09:21:49.471  3511  4459 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9bb1ab1 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a2e0fe7 9409:com.android.settings/1000}
,05-19 09:21:49.471  9409  9409 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
05-19 09:21:49.471  9409  9409 D BluetoothStatusReceiver: AdapterStateChanged :: state = 11
,05-19 09:21:49.481  9689  9775 D BluetoothAdapter: enable()
,05-19 09:21:49.481  9787  9800 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,05-19 09:21:49.481  9787  9787 I bt_bluedroid: get_profile_interface handsfree
,05-19 09:21:49.491  3511  4459 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9bb1ab1 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c35b0ed 9787:com.android.bluetooth/1002}
05-19 09:21:49.491  3511  4451 V AlarmManager:  remove PendingIntent] PendingIntent{de48c7a: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.501  9787  9800 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
,05-19 09:21:49.501  3511  4198 W ActivityManager: Permission Denial: getCurrentUser() from pid=9689, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
,05-19 09:21:49.511  3511  4198 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
05-19 09:21:49.511  3511  4198 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9689, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-19 09:21:49.511  3511  4198 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-19 09:21:49.511  3511  4198 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2852)
05-19 09:21:49.511  3511  4198 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2842)
05-19 09:21:49.511  3511  4198 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.setBtEnableFlag(BluetoothManagerService.java:1222)
05-19 09:21:49.511  3511  4198 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:254)
05-19 09:21:49.511  3511  4198 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:453)
05-19 09:21:49.511  3511  4198 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,05-19 09:21:49.511  3511  4198 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
05-19 09:21:49.511  3511  4198 D SettingsProvider: isChangeAllowed() : name = bluetooth_on
,05-19 09:21:49.521  9787  9800 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
05-19 09:21:49.521  9787  9800 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
05-19 09:21:49.521  9787  9800 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
05-19 09:21:49.521  9787  9800 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
05-19 09:21:49.521  9787  9800 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.bleaudio.BleAudioService
,05-19 09:21:49.521  9787  9787 I DualScoManager: Instantiating Dual Sco Manager
05-19 09:21:49.521  3511  3982 V AlarmManager:  remove PendingIntent] PendingIntent{8571221: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:49.521  9787  9787 I DualScoManager: Set HeadsetServiceHelper
05-19 09:21:49.521  9787  9787 D BluetoothAtMessage: createCMTIContentObservers
05-19 09:21:49.521  9787  9800 I BluetoothAdapterState: Entering PendingCommandState
,05-19 09:21:49.531  9787  9800 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BLE_TURN_ON
05-19 09:21:49.531  3511  3984 V AlarmManager:  remove PendingIntent] PendingIntent{b5c6007: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.531  9787  9800 E BluetoothAdapterState: Don't defer BLE_TURN_ON request.,
,05-19 09:21:49.541  3511  4451 V AlarmManager:  remove PendingIntent] PendingIntent{8013534: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.541  3511  4198 V AlarmManager:  remove PendingIntent] PendingIntent{f1af5d: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.541  9787  9787 D HeadsetProvider: Created cursor android.database.sqlite.SQLiteCursor@25cc884
,05-19 09:21:49.541  3511  3852 V AlarmManager:  remove PendingIntent] PendingIntent{94430d2: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.551  9787  9787 D HeadsetProvider: setHeadsetDB - Can't find 300 for A8:81:95:E9:5F:XX
,05-19 09:21:49.551  3511  3528 V AlarmManager:  remove PendingIntent] PendingIntent{d54f5a3: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.551  3511  4422 V AlarmManager:  remove PendingIntent] PendingIntent{f1670a0: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.561  9787  9787 I HeadsetProvider: setHeadsetDB - A8:81:95:E9:5F:XX, 300, 1, true
,05-19 09:21:49.561  3511  4185 V AlarmManager:  remove PendingIntent] PendingIntent{e9ee459: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.561  3511  4343 V AlarmManager:  remove PendingIntent] PendingIntent{910881e: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.561  3511  4449 V AlarmManager:  remove PendingIntent] PendingIntent{ab748ff: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.571  9787  9787 D HeadsetProvider: Created cursor android.database.sqlite.SQLiteCursor@e52dd33
,05-19 09:21:49.571  9787  9787 D HeadsetProvider: setHeadsetDB - Can't find 400 for A8:81:95:E9:5F:XX
,05-19 09:21:49.571  3511  4313 V AlarmManager:  remove PendingIntent] PendingIntent{c81f6cc: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.571  9787  9787 I HeadsetProvider: setHeadsetDB - A8:81:95:E9:5F:XX, 400, 1, true
,05-19 09:21:49.571  9787  9827 D HeadsetStateMachine: Enter Disconnected: -2, size: 0/0
,05-19 09:21:49.581  3511  3852 V AlarmManager:  remove PendingIntent] PendingIntent{53db3b8: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.581  9787  9787 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Message sending
,05-19 09:21:49.581  9787  9787 E HeadsetService: notifyProfileServiceStateChanged
,05-19 09:21:49.581  9787  9827 D HeadsetStateMachine: Clear mHeadsetBrsf
,05-19 09:21:49.581  9787  9827 D HeadsetStateMachine: map size, before remove : 0
05-19 09:21:49.581  9787  9827 D HeadsetStateMachine: map size, after remove: 0
,05-19 09:21:49.581  9787  9787 D A2dpService: Received start request. Starting profile...
05-19 09:21:49.581  9787  9787 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ca63953
05-19 09:21:49.581  9787  9787 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,05-19 09:21:49.581  3511  4847 V AlarmManager:  remove PendingIntent] PendingIntent{57c591: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.581  9787  9787 I bt_bluedroid: get_profile_interface avrcp
,05-19 09:21:49.591  3511  3529 V AlarmManager:  remove PendingIntent] PendingIntent{2b77cf6: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.591  3511  3984 V AlarmManager:  remove PendingIntent] PendingIntent{d567282: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.591  9787  9787 I Avrcp   : No of Audio players :: 1
,05-19 09:21:49.591  9787  9787 I Avrcp   : App Package name is GM
,05-19 09:21:49.591  3511  3982 V AlarmManager:  remove PendingIntent] PendingIntent{73e8d93: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.601  9787  9787 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in com.android.bluetooth rsrc of package com.google.android.music
,05-19 09:21:49.601  3511  4185 V AlarmManager:  remove PendingIntent] PendingIntent{77741d0: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.601  3511  3529 V AlarmManager:  remove PendingIntent] PendingIntent{ab495c9: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.601  9787  9787 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 09:21:49.601  9787  9787 V Avrcp   : MediaPlayerInfo: mPlayerId=1
,05-19 09:21:49.601  3511  3528 V AlarmManager:  remove PendingIntent] PendingIntent{6fd34ce: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.611  9787  9787 I Avrcp   : No of Video players :: 2
,05-19 09:21:49.611  9787  9787 I Avrcp   : Video App Package name is others
,05-19 09:21:49.611  9787  9787 W ResourcesManager: getTopLevelResources: /system/app/Photos/Photos.apk / 1.0 running in com.android.bluetooth rsrc of package com.google.android.apps.photos
,05-19 09:21:49.611  3511  4459 V AlarmManager:  remove PendingIntent] PendingIntent{53a6fef: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.611  3511  4343 V AlarmManager:  remove PendingIntent] PendingIntent{9d6aafc: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.611  9787  9787 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 09:21:49.611  9787  9787 V Avrcp   : MediaPlayerInfo: mPlayerId=2
,05-19 09:21:49.621  9787  9787 I Avrcp   : Video App Package name is VP
,05-19 09:21:49.621  9787  9787 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungVideoPlayer/SamsungVideoPlayer.apk / 1.0 running in com.android.bluetooth rsrc of package com.samsung.android.video
,05-19 09:21:49.621  3511  3982 V AlarmManager:  remove PendingIntent] PendingIntent{367c585: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.621  9787  9787 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 09:21:49.621  9787  9787 V Avrcp   : MediaPlayerInfo: mPlayerId=3
,05-19 09:21:49.621  9787  9787 I Avrcp   : Add tempPlayer
05-19 09:21:49.621  9787  9787 V Avrcp   : MediaPlayerInfo: mPlayerId=4
05-19 09:21:49.621  9787  9787 V Avrcp   : no_of_players : 4
05-19 09:21:49.621  9787  9787 I Avrcp   : Total no of players: 4
05-19 09:21:49.621  3511  4185 V AlarmManager:  remove PendingIntent] PendingIntent{b3bcfda: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:49.621  9787  9787 V Avrcp   : Samsung player is the 1st player
,05-19 09:21:49.621  9787  9787 D Avrcp   : Compose Browsing Service Candidate
,05-19 09:21:49.621  9787  9787 D Avrcp   : ResolveInfo info ResolveInfo{3b2a41c com.google.android.music/.browse.MediaBrowserService m=0x108000}
05-19 09:21:49.621  9787  9787 D Avrcp   : Initialize Media Controller
,05-19 09:21:49.621  9787  9787 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,05-19 09:21:49.621  3511  3529 V AlarmManager:  remove PendingIntent] PendingIntent{e681c0b: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.631  9787  9787 E Avrcp   : getActiveSessions
05-19 09:21:49.631  9787  9787 D Avrcp   : pick active media Controller
05-19 09:21:49.631  9787  9787 D Avrcp   : Get the active Media Controller 
05-19 09:21:49.631  9787  9787 I BluetoothA2dpServiceJni: classInitNative: succeeds
05-19 09:21:49.631  9787  9787 D A2dpStateMachine: make
,05-19 09:21:49.631  9787  9787 I bt_bluedroid: get_profile_interface a2dp
,05-19 09:21:49.631  9787  9787 E bt_btif : warning : media task started media_task_refcnt 1 
05-19 09:21:49.631  3511  4451 V AlarmManager:  remove PendingIntent] PendingIntent{6617ae8: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.631  9787  9830 D A2dpStateMachine: Enter Disconnected: -2
,05-19 09:21:49.631  9787  9787 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Message sending
,05-19 09:21:49.631  9787  9787 E A2dpService: notifyProfileServiceStateChanged
,05-19 09:21:49.631  3511  4847 V AlarmManager:  remove PendingIntent] PendingIntent{475d94: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.641  3511  4449 V AlarmManager:  remove PendingIntent] PendingIntent{15e203d: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.641  9787  9787 D HeadsetStateMachine: Try to query the phonestate on bind
,05-19 09:21:49.641  3511  3528 I Telecom : BluetoothPhoneService: queryPhoneState
05-19 09:21:49.641  3511  3528 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState : true
,05-19 09:21:49.641  9787  9787 I BluetoothHidServiceJni: classInitNative: succeeds
05-19 09:21:49.641  3511  3529 V AlarmManager:  remove PendingIntent] PendingIntent{f148032: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.641  9787  9787 D HidService: Received start request. Starting profile...
05-19 09:21:49.641  9787  9787 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ca63953
05-19 09:21:49.641  9787  9787 I bt_bluedroid: get_profile_interface hidhost
05-19 09:21:49.641  9787  9787 D HidService: setHidService(): set to: null
,05-19 09:21:49.641  9787  9787 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, Message sending
05-19 09:21:49.641  9787  9787 E HidService: notifyProfileServiceStateChanged
05-19 09:21:49.641  9787  9787 I BluetoothHealthServiceJni: classInitNative: succeeds
,05-19 09:21:49.641  9787  9787 D HealthService: Received start request. Starting profile...
05-19 09:21:49.641  9787  9787 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ca63953
,05-19 09:21:49.651  3511  4185 V AlarmManager:  remove PendingIntent] PendingIntent{3760183: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.651  9787  9787 I bt_bluedroid: get_profile_interface health
05-19 09:21:49.651  9787  9787 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, Message sending
05-19 09:21:49.651  9787  9787 E HealthService: notifyProfileServiceStateChanged
05-19 09:21:49.651  9787  9787 I BluetoothPanServiceJni: classInitNative(L113): succeeds
,05-19 09:21:49.651  9787  9787 D PanService: Received start request. Starting profile...
,05-19 09:21:49.651  9787  9787 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ca63953
05-19 09:21:49.651  9787  9787 D BluetoothPanServiceJni: initializeNative(L118): pan
05-19 09:21:49.651  9787  9787 I bt_bluedroid: get_profile_interface pan
,05-19 09:21:49.651  9787  9787 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, Message sending
05-19 09:21:49.651  9787  9787 E PanService: notifyProfileServiceStateChanged
05-19 09:21:49.651  9787  9787 D HeadsetStateMachine: Proxy object connected,
,05-19 09:21:49.651  3511  4407 V AlarmManager:  remove PendingIntent] PendingIntent{c06bf00: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:49.651  9787  9787 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,05-19 09:21:49.651  9787  9827 D HeadsetStateMachine: Disconnected process message: 11, size: 0
,05-19 09:21:49.651  9787  9827 E HeadsetStateMachine: Unknown message: 11
,05-19 09:21:49.651  9787  9787 D BluetoothMapService: Received start request. Starting profile...
05-19 09:21:49.651  9787  9787 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ca63953
,05-19 09:21:49.661  3511  3529 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9bb1ab1 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{40b9903 7208:com.google.android.apps.maps/u0a125}
,05-19 09:21:49.671  3511  4449 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{598cb2c u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cf9e5aa 4853:com.samsung.android.providers.context/u0a9}
,05-19 09:21:49.681  9787  9787 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Message sending
05-19 09:21:49.681  9787  9787 E BluetoothMapService: notifyProfileServiceStateChanged
05-19 09:21:49.681  9787  9787 D HeadsetPhoneState: sendDeviceDataStateChanged
,05-19 09:21:49.681  9787  9827 D HeadsetStateMachine: Disconnected process message: 19, size: 0
05-19 09:21:49.681  9787  9827 E HeadsetStateMachine: Unknown message: 19
05-19 09:21:49.681  9787  9787 D HeadsetPhoneState: Signal level : previous=0 curr=0
,05-19 09:21:49.681  9787  9787 V SapService: SapBinder()
,05-19 09:21:49.681  9787  9787 D SapService: Received start request. Starting profile...
05-19 09:21:49.681  9787  9787 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ca63953
05-19 09:21:49.681  9787  9787 V SapService: start()
,05-19 09:21:49.691  9787  9787 D SapService: Disable sap : false
,05-19 09:21:49.691  3511  4313 V AlarmManager:  remove PendingIntent] PendingIntent{397e38a: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.691  9787  9787 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=12, Message sending
05-19 09:21:49.691  9787  9787 E SapService: notifyProfileServiceStateChanged
,05-19 09:21:49.691  3511  4070 V AlarmManager:  remove PendingIntent] PendingIntent{e98ae56: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.701  3511  3984 V AlarmManager:  remove PendingIntent] PendingIntent{8a49ed7: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.701  3511  4422 V AlarmManager:  remove PendingIntent] PendingIntent{7c753c4: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.701  3511  3529 V AlarmManager:  remove PendingIntent] PendingIntent{8fc92ad: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.711  3511  4198 V AlarmManager:  remove PendingIntent] PendingIntent{70959e2: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.711  3511  4407 V AlarmManager:  remove PendingIntent] PendingIntent{f2a5173: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.711  9787  9787 D BleAudioService: Received start request. Starting profile...
05-19 09:21:49.711  9787  9787 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ca63953
05-19 09:21:49.711  9787  9787 E DualScoManager: Dual Sco Manager already instantiated
,05-19 09:21:49.711  9787  9787 I BtBleAudio.JNI: classInitNative(L304): succeeds
05-19 09:21:49.711  9787  9787 D BleAudioStateMachine: make
,05-19 09:21:49.721  9787  9787 I BleAudioStateMachine: Constructor Of BleAudioStateMachine
05-19 09:21:49.721  3511  4847 V AlarmManager:  remove PendingIntent] PendingIntent{bc7e830: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.721  9787  9787 D BtBleAudio.JNI: initializeNative(L309): ble audio jni initializeNative: 0
05-19 09:21:49.721  9787  9787 I bt_bluedroid: get_profile_interface bleaudio_source
,05-19 09:21:49.721  9787  9787 D BleAudioStateMachine: make
05-19 09:21:49.721  9787  9835 E BleAudioStateMachine_L: Enter Disconnected: -2
,05-19 09:21:49.721  9787  9787 I BleAudioStateMachine: Constructor Of BleAudioStateMachine
05-19 09:21:49.721  9787  9787 D BtBleAudio.JNI: initializeNative(L309): ble audio jni initializeNative: 1
05-19 09:21:49.721  9787  9787 V BleAudioService: [registerCallStateListener]
05-19 09:21:49.721  3511  4449 V AlarmManager:  remove PendingIntent] PendingIntent{1fcaca9: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:49.721  9787  9836 E BleAudioStateMachine_R: Enter Disconnected: -2
,05-19 09:21:49.721  9787  9787 V BleAudioService: [registerAobleStateChangeListener]
,05-19 09:21:49.721  3511  4198 V AlarmManager:  remove PendingIntent] PendingIntent{8e7322e: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.731  9787  9787 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.broadcom.bt.service.bleaudio.BleAudioService, state=12, Message sending
,05-19 09:21:49.731  9787  9787 E BleAudioService: notifyProfileServiceStateChanged
,05-19 09:21:49.731  9787  9787 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-19 09:21:49.731  9787  9787 E BluetoothAdapterService: handleMessage() - Message: 1
05-19 09:21:49.731  9787  9787 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Before synchronized
05-19 09:21:49.731  9787  9827 D HeadsetStateMachine: Disconnected process message: 10, size: 0
05-19 09:21:49.731  9787  9787 V BluetoothAdapterState: isTurningOff()=false
05-19 09:21:49.731  9787  9787 V BluetoothAdapterState: isTurningOn()=true
05-19 09:21:49.731  9787  9787 V BluetoothAdapterState: isBleTurningOn()=false
,05-19 09:21:49.731  9787  9787 V BluetoothAdapterState: isBleTurningOff()=false
05-19 09:21:49.731  9787  9827 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
05-19 09:21:49.731  9787  9787 E BluetoothAdapterService: handleMessage() - Message: 1
05-19 09:21:49.731  9787  9787 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Before synchronized
05-19 09:21:49.731  9787  9827 D HeadsetStateMachine: Disconnected process message: 11, size: 0
05-19 09:21:49.731  3511  4847 V AlarmManager:  remove PendingIntent] PendingIntent{b8433a: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:49.731  9787  9827 E HeadsetStateMachine: Unknown message: 11
05-19 09:21:49.731  9787  9787 V BluetoothAdapterState: isTurningOff()=false
05-19 09:21:49.731  9787  9787 V BluetoothAdapterState: isTurningOn()=true
05-19 09:21:49.731  9787  9787 V BluetoothAdapterState: isBleTurningOn()=false
05-19 09:21:49.731  9787  9787 V BluetoothAdapterState: isBleTurningOff()=false
,05-19 09:21:49.731  9787  9787 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
05-19 09:21:49.731  9787  9787 D HeadsetPhoneState: sendDeviceDataStateChanged
05-19 09:21:49.731  9787  9787 D HeadsetPhoneState: Signal level : previous=0 curr=0
05-19 09:21:49.731  9787  9827 D HeadsetStateMachine: Disconnected process message: 11, size: 0
05-19 09:21:49.731  9787  9787 E BluetoothAdapterService: handleMessage() - Message: 1
05-19 09:21:49.731  9787  9827 E HeadsetStateMachine: Unknown message: 11
05-19 09:21:49.731  9787  9787 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, Before synchronized
05-19 09:21:49.731  9787  9827 D HeadsetStateMachine: Disconnected process message: 19, size: 0
,05-19 09:21:49.731  9787  9827 E HeadsetStateMachine: Unknown message: 19
05-19 09:21:49.731  9787  9787 V BluetoothAdapterState: isTurningOff()=false
05-19 09:21:49.731  9787  9787 V BluetoothAdapterState: isTurningOn()=true
05-19 09:21:49.731  9787  9787 V BluetoothAdapterState: isBleTurningOn()=false
05-19 09:21:49.731  9787  9787 V BluetoothAdapterState: isBleTurningOff()=false
05-19 09:21:49.731  9787  9787 D BluetoothAdapterService: HID Host service started
,05-19 09:21:49.731  3939  4163 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CONNECTION_HID_HOST
,05-19 09:21:49.731  9409  9409 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CONNECTION_HID_HOST
05-19 09:21:49.731  3939  4163 W LocalBluetoothProfileManager: updateLocalProfiles :: A2DP profile was previously added but the UUID is now missing.
05-19 09:21:49.731  3939  4163 W LocalBluetoothProfileManager: updateLocalProfiles :: HEADSET profile was previously added but the UUID is now missing.
05-19 09:21:49.731  3939  4163 W LocalBluetoothProfileManager: updateLocalProfiles :: MAP profile was previously added but the UUID is now missing.
05-19 09:21:49.731  3939  4163 W LocalBluetoothProfileManager: updateLocalProfiles :: PBAP profile was previously added but the UUID is now missing.
05-19 09:21:49.731  3939  4163 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
05-19 09:21:49.731  3939  4163 D HidProfile: mService is null. need to get proxy again!!
,05-19 09:21:49.731  3511  3529 V AlarmManager:  remove PendingIntent] PendingIntent{6948d48: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:49.741  9409  9409 D BluetoothMap: Create BluetoothMap proxy object
,05-19 09:21:49.741  9787  9787 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,05-19 09:21:49.741  9787  9787 E BluetoothAdapterService: handleMessage() - Message: 1
05-19 09:21:49.741  9787  9787 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, Before synchronized
,05-19 09:21:49.741  9787  9787 V BluetoothAdapterState: isTurningOff()=false
05-19 09:21:49.741  9787  9787 V BluetoothAdapterState: isTurningOn()=true
05-19 09:21:49.741  9787  9787 V BluetoothAdapterState: isBleTurningOn()=false
05-19 09:21:49.741  9787  9787 V BluetoothAdapterState: isBleTurningOff()=false
05-19 09:21:49.741  9787  9787 E BluetoothAdapterService: handleMessage() - Message: 1
05-19 09:21:49.741  9787  9787 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, Before synchronized
,05-19 09:21:49.741  9787  9787 V BluetoothAdapterState: isTurningOff()=false
,05-19 09:21:49.741  9787  9787 V BluetoothAdapterState: isTurningOn()=true
05-19 09:21:49.741  9787  9787 V BluetoothAdapterState: isBleTurningOn()=false
05-19 09:21:49.741  9787  9787 V BluetoothAdapterState: isBleTurningOff()=false
05-19 09:21:49.741  9787  9787 E BluetoothAdapterService: handleMessage() - Message: 1
05-19 09:21:49.741  9787  9787 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Before synchronized
,05-19 09:21:49.741  9787  9787 V BluetoothAdapterState: isTurningOff()=false
05-19 09:21:49.741  9787  9787 V BluetoothAdapterState: isTurningOn()=true
05-19 09:21:49.741  3511  4407 V AlarmManager:  remove PendingIntent] PendingIntent{67fff92: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.741  9787  9787 V BluetoothAdapterState: isBleTurningOn()=false
05-19 09:21:49.741  9787  9787 V BluetoothAdapterState: isBleTurningOff()=false
,05-19 09:21:49.741  9787  9787 E BluetoothAdapterService: handleMessage() - Message: 1
,05-19 09:21:49.741  9787  9787 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=12, Before synchronized
,05-19 09:21:49.751  9787  9787 V BluetoothAdapterState: isTurningOff()=false
05-19 09:21:49.751  9787  9787 V BluetoothAdapterState: isTurningOn()=true
05-19 09:21:49.751  9787  9787 V BluetoothAdapterState: isBleTurningOn()=false
,05-19 09:21:49.751  9787  9787 V BluetoothAdapterState: isBleTurningOff()=false
05-19 09:21:49.751  9787  9787 D BleAudioService: [onCallStateChanged] ENTER -- State: (0)
05-19 09:21:49.751  9787  9787 D BleAudioService: [onCallStateChanged] No devices in connected state
05-19 09:21:49.751  9787  9787 D BleAudioService: [onCallStateChanged][PHONECALL STATE Changed]: EXIT
05-19 09:21:49.751  9787  9787 E BluetoothAdapterService: handleMessage() - Message: 1
05-19 09:21:49.751  9787  9787 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.bleaudio.BleAudioService, state=12, Before synchronized
05-19 09:21:49.751  9787  9787 V BluetoothAdapterState: isTurningOff()=false
,05-19 09:21:49.751  9787  9787 V BluetoothAdapterState: isTurningOn()=true
05-19 09:21:49.751  9787  9787 V BluetoothAdapterState: isBleTurningOn()=false
05-19 09:21:49.751  9787  9787 V BluetoothAdapterState: isBleTurningOff()=false
05-19 09:21:49.751  3939  4163 W LocalBluetoothProfileManager: updateLocalProfiles :: BleAudio profile was created already 
05-19 09:21:49.751  9787  9800 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_STARTED
,05-19 09:21:49.751  3511  4407 V AlarmManager:  remove PendingIntent] PendingIntent{c7dbd60: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.751  9409  9409 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
05-19 09:21:49.751  3939  3939 D BluetoothInputDevice: Proxy object connected
05-19 09:21:49.751  3939  3939 D HidProfile: Bluetooth service connected
05-19 09:21:49.751  9787  9800 E BluetoothServiceJni: enableBrEdrNative:
05-19 09:21:49.751  9787  9800 I bt_bluedroid: enable_bredr
,05-19 09:21:49.761  3511  4449 V AlarmManager:  remove PendingIntent] PendingIntent{bf14f8c: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.761  9787  9804 I bt_bta_hh: BTA_HhEnable sec_mask:0x24 p_cback:0xf36aff29
05-19 09:21:49.761  3511  3511 D SettingsProvider: isChangeAllowed() : name = bluetooth_name
,05-19 09:21:49.761  9787  9804 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x100048
05-19 09:21:49.761  9787  9804 D BluetoothAdapterProperties: Address is:A8:81:95:E9:5F:6F
05-19 09:21:49.761  9787  9804 E BluetoothServiceJni: populateRssiValuesNative
05-19 09:21:49.761  9787  9804 I bt_bluedroid: getModelRssiValues
05-19 09:21:49.761  9787  9804 E BluetoothServiceJni: model_rssi_values_callback: low = -75, mid = -65, high = 127
05-19 09:21:49.761  9787  9822 D CODEC_IF: codec_if_open: opening libbt-codec_aptx.so...
05-19 09:21:49.761  9787  9804 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -75,-65,127
05-19 09:21:49.761  9787  9804 D BluetoothAdapterProperties: Name is: Samsung Galaxy S7 edge
05-19 09:21:49.761  9409  9409 D LocalBluetoothProfileManager: Adding local BleAudio profile
05-19 09:21:49.761  9787  9804 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
05-19 09:21:49.761  9787  9804 D BluetoothAdapterProperties: Scan Mode:20
05-19 09:21:49.761  9787  9804 D BluetoothAdapterProperties: Discoverable Timeout:-1
05-19 09:21:49.761  9787  9804 E bt_btif : btif_handle_bluetooth_enable_evt
05-19 09:21:49.761  9787  9804 E bt_btif : ANT+ socket does not initialize.
05-19 09:21:49.771  9409  9409 D BluetoothLeAudio: getProfileProxy()
05-19 09:21:49.771  9787  9804 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
05-19 09:21:49.771  9787  9804 D IOP_DB_BT: db_open: db_open : handle 4083359760l, read 18483 bytes onto local cache
05-19 09:21:49.771  9787  9804 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
05-19 09:21:49.771  9787  9822 D CODEC_IF_MOD: codec_open: codec_open
05-19 09:21:49.771  9787  9804 D IOP_DB_BT: db_query: result 1
05-19 09:21:49.771  9787  9804 I         : iop_db_open: iop_db_open status 0
05-19 09:21:49.771  9787  9822 D CODEC_IF_MOD: codec_open: apt-x encoder initialized successfully
05-19 09:21:49.771  9787  9822 D CODEC_IF_MOD: codec_open:    version : 1.0.1.0
05-19 09:21:49.771  9787  9822 D CODEC_IF_MOD: codec_open:    build : Android_JB_4.2.2
05-19 09:21:49.771  9787  9822 D CODEC_IF: codec_if_open: codec module opened (v0.1
05-19 09:21:49.771  9787  9822 D CODEC_IF: codec_if_close: codec_if_close hdl -552574972
05-19 09:21:49.771  9787  9822 D CODEC_IF_MOD: codec_close: codec_close
05-19 09:21:49.771  9787  9822 D CODEC_IF_MOD: codec_close: freed apt-x encoder
05-19 09:21:49.771  9787  9804 E BluetoothAdapterState: stateChangeCallback : 17
05-19 09:21:49.771  9787  9822 D         : Codec ==> check 96kHz mode : check_sshd_encoder_available:332
05-19 09:21:49.771  9787  9822 D CODEC_IF: codec_if_open: opening libbt-codec_sshd.so...
05-19 09:21:49.771  9787  9800 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_NATIVE_STARTED
05-19 09:21:49.771  9787  9804 E bt_btif : no av cb found, event:0, BTA_AV_ENABLE_EVT ignored!
05-19 09:21:49.771  9787  9804 E bt_btif : btif_sm_dispatch : Invalid handle
,05-19 09:21:49.771  9787  9800 D BluetoothAdapterProperties: ScanMode =  20
05-19 09:21:49.771  9787  9800 D BluetoothAdapterProperties: State =  11
05-19 09:21:49.771  9787  9822 D CODEC_IF_SSHD: codec_open: codec_open
05-19 09:21:49.771  9787  9822 D CODEC_IF_SSHD: Codec ==> pcm_info.sampling_freq : 96000
05-19 09:21:49.771  9787  9822 D CODEC_IF_SSHD: codec_open: SSHD encoder initialized successfully
05-19 09:21:49.771  9787  9822 D CODEC_IF: codec_if_open: codec module opened (v0.1
05-19 09:21:49.771  3511  4451 V AlarmManager:  remove PendingIntent] PendingIntent{d29d878: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:49.771  9787  9822 D CODEC_IF: codec_if_close: codec_if_close hdl -584192640
05-19 09:21:49.771  9787  9822 D CODEC_IF_SSHD: codec_close: codec_close
05-19 09:21:49.771  9787  9822 D         : Codec ==> copy capability info [bta_av_co_audio_init:559]
05-19 09:21:49.771  9787  9822 D CODEC_IF: codec_if_open: opening libbt-codec_aptx.so...
05-19 09:21:49.771  9787  9804 E bt_btif : bta_av_co_get_peer peer index out of bounds:255
05-19 09:21:49.771  9787  9804 E bt_btif : bta_av_co_audio_peer_init No active peer with this handle 0x0
05-19 09:21:49.771  9787  9804 E bt_btif : no av control block available at state:3
05-19 09:21:49.781  9787  9804 E bt_btif : no av control block available at state:3
,05-19 09:21:49.781  9787  9804 E bt_btif : no av control block available at state:2
05-19 09:21:49.781  9787  9804 E bt_btif : warning : no command pending, ignore ack
05-19 09:21:49.781  9787  9804 E bt_btif : no av control block available at state:3
05-19 09:21:49.781  9787  9804 E bt_btif : no av control block available at state:2
05-19 09:21:49.781  9787  9804 W bt_btif : btif_av_state_idle_handler : unhandled event:BTA_AV_REGISTER_EVT
05-19 09:21:49.781  9787  9804 E bt_btif : btif_sm_dispatch : Invalid handle
05-19 09:21:49.781  9787  9822 D CODEC_IF_MOD: codec_open: codec_open
05-19 09:21:49.781  9787  9822 D CODEC_IF_MOD: codec_open: apt-x encoder initialized successfully
05-19 09:21:49.781  9787  9822 D CODEC_IF_MOD: codec_open:    version : 1.0.1.0
05-19 09:21:49.781  9787  9822 D CODEC_IF_MOD: codec_open:    build : Android_JB_4.2.2
05-19 09:21:49.781  9787  9822 D CODEC_IF: codec_if_open: codec module opened (v0.1
05-19 09:21:49.781  9787  9822 D CODEC_IF: codec_if_close: codec_if_close hdl -552574972
05-19 09:21:49.781  9787  9822 D CODEC_IF_MOD: codec_close: codec_close
05-19 09:21:49.781  9787  9822 D CODEC_IF_MOD: codec_close: freed apt-x encoder
,05-19 09:21:49.781  9787  9822 D         : Codec ==> check 96kHz mode : check_sshd_encoder_available:332
05-19 09:21:49.781  9787  9822 D CODEC_IF: codec_if_open: opening libbt-codec_sshd.so...
,05-19 09:21:49.781  9787  9822 D CODEC_IF_SSHD: codec_open: codec_open
05-19 09:21:49.781  9787  9822 D CODEC_IF_SSHD: Codec ==> pcm_info.sampling_freq : 96000
05-19 09:21:49.781  9787  9822 D CODEC_IF_SSHD: codec_open: SSHD encoder initialized successfully
05-19 09:21:49.781  9787  9822 D CODEC_IF: codec_if_open: codec module opened (v0.1
05-19 09:21:49.781  9787  9822 D CODEC_IF: codec_if_close: codec_if_close hdl -584192640
05-19 09:21:49.781  9787  9822 D CODEC_IF_SSHD: codec_close: codec_close
05-19 09:21:49.781  9787  9822 D         : Codec ==> copy capability info [bta_av_co_audio_init:559]
05-19 09:21:49.781  9787  9804 E bt_btif : bta_av_co_get_peer peer index out of bounds:255
05-19 09:21:49.781  9787  9804 E bt_btif : bta_av_co_audio_peer_init No active peer with this handle 0x0
05-19 09:21:49.781  9787  9804 E bt_btif : no av control block available at state:3
05-19 09:21:49.781  9787  9804 E bt_btif : no av control block available at state:3
,05-19 09:21:49.781  9787  9804 E bt_btif : no av control block available at state:2
05-19 09:21:49.781  9787  9804 E bt_btif : warning : no command pending, ignore ack
05-19 09:21:49.781  9787  9804 E bt_btif : no av control block available at state:3
05-19 09:21:49.781  9787  9804 E bt_btif : no av control block available at state:2
05-19 09:21:49.781  9787  9804 W bt_btif : btif_av_state_0001): State :, Event 0x0500
05-19 09:21:49.781  9787  9804 E bt_btif : Write Extended Inquiry Response t
,05-19 09:21:49.781  9787  9804 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,05-19 09:21:49.791  3511  4313 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
,05-19 09:21:49.791  3511  3984 D SecContentProvider: insert(), uri = 2
,05-19 09:21:49.791  3511  3528 V AlarmManager:  remove PendingIntent] PendingIntent{b600424: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:49.801  9787  9800 D BluetoothAdapterProperties: Setting state to 12
05-19 09:21:49.801  9787  9800 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,05-19 09:21:49.801  9409  9409 D BluetoothLeAudio: Success to bind to IBluetoothLeAudio with Intent { act=com.broadcom.bt.service.bleaudio.IBluetoothLeAudio cmp=com.android.bluetooth/com.broadcom.bt.service.bleaudio.BleAudioService VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
05-19 09:21:49.801  9787  9800 D HeadsetService: setBleAudioService(): com.broadcom.bt.service.bleaudio.BleAudioService@ba0415a
05-19 09:21:49.801  9787  9800 D A2dpService: setBleAudioService(): com.broadcom.bt.service.bleaudio.BleAudioService@ba0415a
05-19 09:21:49.801  9787  9800 D BleAudioService: setHeadsetService: setting HeadsetService
05-19 09:21:49.801  9787  9800 D BleAudioService: setA2dpService: setting A2dpService
,05-19 09:21:49.801  9787  9800 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,05-19 09:21:49.801  9787  9800 D BluetoothAdapterService: updateAdapterState state is 12
,05-19 09:21:49.801  9409  9409 D BluetoothMap: Proxy object connected
,05-19 09:21:49.801  9409  9409 D MapProfile: Bluetooth service connected
05-19 09:21:49.801  9409  9409 D BluetoothMap: getConnectedDevices()
,05-19 09:21:49.811  9787  9804 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,05-19 09:21:49.811  9787  9804 D BluetoothAdapterProperties: Scan Mode:21
05-19 09:21:49.811  9787  9804 D BluetoothAdapterProperties: Discoverable Timeout:-1
,05-19 09:21:49.811  9689  9689 D BluetoothAdapter: STATE_ON
,05-19 09:21:49.811  9689  9689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-19 09:21:49.811  9689  9689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-19 09:21:49.811  9689  9689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-19 09:21:49.811  9689  9689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-19 09:21:49.811  9689  9689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-19 09:21:49.811  9689  9689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-19 09:21:49.811  9689  9689 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-19 09:21:49.811  9689  9689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-19 09:21:49.811  9689  9689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,05-19 09:21:49.811  9787  9800 V BluetoothAdapterService: start opp service
,05-19 09:21:49.811  3511  4407 V AlarmManager:  remove PendingIntent] PendingIntent{aab3e90: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.811  9689  9689 D BluetoothAdapter: STATE_ON
,05-19 09:21:49.821  9409  9409 D BluetoothInputDevice: Proxy object connected
,05-19 09:21:49.821  9409  9409 D HidProfile: Bluetooth service connected
,05-19 09:21:49.821  9787  9800 D BluetoothAdapterService: Autoconnection is available 
,05-19 09:21:49.821  9787  9800 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
05-19 09:21:49.821  9787  9800 D BluetoothAdapterService: starting service from this receiver
05-19 09:21:49.821  9409  9419 D BluetoothPbap: onBluetoothStateChange: up=true
05-19 09:21:49.821  9409  9419 D BluetoothPbap: Binding service...
,05-19 09:21:49.821  9689  9689 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
05-19 09:21:49.821  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,05-19 09:21:49.831  9787  9800 D BluetoothAdapterService: BT on, init HID DEV count : 0
05-19 09:21:49.831  9787  9800 I BluetoothAdapterState: Entering OnState
05-19 09:21:49.831  9689  9689 D BluetoothAdapter: STATE_ON
,05-19 09:21:49.831  4328  7419 D BluetoothAdapter: onBluetoothStateChange: up=true
,05-19 09:21:49.831  4328  7419 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
05-19 09:21:49.841  9787  9787 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,05-19 09:21:49.841  4853  4865 D BluetoothA2dp: onBluetoothStateChange: up=true
,05-19 09:21:49.841  3511  4313 V AlarmManager:  remove PendingIntent] PendingIntent{5923af: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:49.841  4853  4865 D BluetoothA2dp: Binding service...
05-19 09:21:49.841  9689  9689 D BluetoothAdapter: STATE_ON
,05-19 09:21:49.841  4853  4865 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,05-19 09:21:49.841  9409  9409 D BluetoothLeAudio: Proxy object connected
,05-19 09:21:49.841  9409  9409 D BleAudioProfile: Bluetooth service connected
,05-19 09:21:49.841  9409  9409 D BluetoothLeAudio: getConnectedDevices()
,05-19 09:21:49.841  9689  9689 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,05-19 09:21:49.851  3511  3647 D BluetoothAdapter: onBluetoothStateChange: up=true
05-19 09:21:49.851  3511  3647 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,05-19 09:21:49.851  9409  9409 D BluetoothPbap: Proxy object connected
,05-19 09:21:49.851  9409  9409 D PbapServerProfile: Bluetooth service connected
,05-19 09:21:49.851  9409  9419 D BluetoothAdapter: onBluetoothStateChange: up=true
05-19 09:21:49.851  9409  9419 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,05-19 09:21:49.851  3511  4847 V AlarmManager:  remove PendingIntent] PendingIntent{8b1e69a: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.851  3939  3950 D BluetoothPan: onBluetoothStateChange on: true
,05-19 09:21:49.851  3939  3950 D BluetoothPan: onBluetoothStateChange calling doBind()
,05-19 09:21:49.861  9689  9689 D BluetoothAdapter: STATE_ON
,05-19 09:21:49.861  9787  9787 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
05-19 09:21:49.861  9787  9787 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,05-19 09:21:49.861  9689  9689 D BluetoothAdapter: STATE_ON
,05-19 09:21:49.861  3511  3528 V AlarmManager:  remove PendingIntent] PendingIntent{b574ac1: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.861  4287  4542 D BluetoothAdapter: onBluetoothStateChange: up=true
,05-19 09:21:49.861  4287  4542 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,05-19 09:21:49.861  9689  9689 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,05-19 09:21:49.861  9787  9787 V BtOppService: isOwner == true
05-19 09:21:49.861  3939  3949 D BluetoothA2dp: onBluetoothStateChange: up=true
05-19 09:21:49.861  3939  3949 D BluetoothA2dp: Binding service...
,05-19 09:21:49.871  3939  3949 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,05-19 09:21:49.871  8967  8978 D BluetoothAdapter: onBluetoothStateChange: up=true
05-19 09:21:49.871  8967  8978 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,05-19 09:21:49.871  7208  7220 D BluetoothAdapter: onBluetoothStateChange: up=true
05-19 09:21:49.871  7208  7220 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,05-19 09:21:49.871  3511  4198 V AlarmManager:  remove PendingIntent] PendingIntent{6debe54: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.871  9409  9420 D BluetoothSap: onBluetoothStateChange: up=true
05-19 09:21:49.871  9409  9420 D BluetoothSap: Binding service...
,05-19 09:21:49.881  9689  9689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-19 09:21:49.881  3511  4185 V AlarmManager:  remove PendingIntent] PendingIntent{54a6943: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.881  3939  4110 D BluetoothPbap: onBluetoothStateChange: up=true
,05-19 09:21:49.881  3939  4110 D BluetoothPbap: Binding service...
,05-19 09:21:49.881  4158  4174 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg com.android.bluetooth,id=0,extra=Bundle[mParcelledData.dataSize=160]
,05-19 09:21:49.881  4158  4158 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=0, samsung.notification.type=normal, samsung.people.package_name=com.android.bluetooth, samsung.notification.remove_all=true}]
05-19 09:21:49.881  4158  4158 I PeopleStripeService: PeopleNotificationReceiver:3
,05-19 09:21:49.891  4158  4158 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
,05-19 09:21:49.891  4158  4158 I PeopleDataManager: removeNotification
05-19 09:21:49.891  4158  4158 I NotificationParser: getNotiType:com.android.bluetooth,null
05-19 09:21:49.891  4158  4158 D PeopleDataManager: removeNotiInfo: id =0,packageName=com.android.bluetooth,isEdgeNotification=false,key=null,removeAll=true
05-19 09:21:49.891  4158  4158 D PeopleDataManager: removeNotiInfo =null
,05-19 09:21:49.891  3939  3939 D BluetoothPbap: Proxy object connected
,05-19 09:21:49.891  3511  4422 V AlarmManager:  remove PendingIntent] PendingIntent{fd943b5: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:49.891  3939  3939 D PbapServerProfile: Bluetooth service connected
,05-19 09:21:49.891  9787  9826 D BluetoothAdapter: onBluetoothStateChange: up=true
,05-19 09:21:49.891  9787  9826 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
05-19 09:21:49.891  9787  9787 I BluetoothPbapService: Handler(): got msg=1
,05-19 09:21:49.891  3939  4592 D BluetoothAdapter: onBluetoothStateChange: up=true
05-19 09:21:49.891  3939  4592 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,05-19 09:21:49.891  3511  4459 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,05-19 09:21:49.901  3511  3647 D BluetoothA2dp: onBluetoothStateChange: up=true
,05-19 09:21:49.901  3511  3647 D BluetoothA2dp: Binding service...
05-19 09:21:49.901  3511  3647 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
05-19 09:21:49.901  9409  9841 D BluetoothInputDevice: onBluetoothStateChange: up=true
05-19 09:21:49.901  3511  4313 V AlarmManager:  remove PendingIntent] PendingIntent{8baf2d8: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:49.901  3939  3950 D BluetoothSap: onBluetoothStateChange: up=true
,05-19 09:21:49.901  3939  3950 D BluetoothSap: Binding service...
,05-19 09:21:49.901  9787  9844 V BluetoothPbapService: PBAP Service initSocket try: 0
,05-19 09:21:49.901  3939  3949 D BluetoothInputDevice: onBluetoothStateChange: up=true
,05-19 09:21:49.901  3511  3647 D BluetoothPan: onBluetoothStateChange on: true
,05-19 09:21:49.901  3511  3647 D BluetoothPan: onBluetoothStateChange calling doBind()
05-19 09:21:49.911  3511  4459 V AlarmManager:  remove PendingIntent] PendingIntent{21cb8a2: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.911  4275  4285 D BluetoothAdapter: onBluetoothStateChange: up=true
05-19 09:21:49.911  4275  4285 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
05-19 09:21:49.911  3939  5545 D BluetoothLeAudio: onBluetoothStateChange: up=true
,05-19 09:21:49.911  3939  5545 D BluetoothLeAudio: Binding service...
,05-19 09:21:49.911  9787  9844 D BluetoothSocket: bindListen(): myUserId = 0
05-19 09:21:49.911  9787  9844 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,05-19 09:21:49.911  3939  3939 D BluetoothLeAudio: Proxy object connected
05-19 09:21:49.911  3939  3939 D BleAudioProfile: Bluetooth service connected
,05-19 09:21:49.911  3939  3939 D BluetoothLeAudio: getConnectedDevices()
,05-19 09:21:49.911  3939  5545 D BluetoothLeAudio: Success to bind to IBluetoothLeAudio with Intent { act=com.broadcom.bt.service.bleaudio.IBluetoothLeAudio cmp=com.android.bluetooth/com.broadcom.bt.service.bleaudio.BleAudioService VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
,05-19 09:21:49.911  9787  9844 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
05-19 09:21:49.921  3939  4592 D BluetoothMap: onBluetoothStateChange: up=true
05-19 09:21:49.921  3939  4592 D BluetoothMap: Binding service...
,05-19 09:21:49.921  3939  3939 D BluetoothA2dp: Proxy object connected
05-19 09:21:49.921  3939  3939 D A2dpProfile: Bluetooth service connected
,05-19 09:21:49.921  3511  4847 V AlarmManager:  remove PendingIntent] PendingIntent{9df3787: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.921  3511  3511 D BluetoothA2dp: Proxy object connected
05-19 09:21:49.921  3511  6156 D SSRM:n  : SIOP:: AP = 310, PST = 315 (W:14), CP = 257, CUR = 89, LCD = 30
,05-19 09:21:49.921  4853  4853 D BluetoothA2dp: Proxy object connected
,05-19 09:21:49.931  9787  9826 D A2dpStateMachine: getConnectedDevices : size=0
,05-19 09:21:49.931  9787  9840 D A2dpStateMachine: getConnectedDevices : size=0
,05-19 09:21:49.931  3511  3511 D BluetoothPan: BluetoothPAN Proxy object connected
,05-19 09:21:49.931  3939  3939 D BluetoothMap: Proxy object connected
,05-19 09:21:49.931  3939  3939 D MapProfile: Bluetooth service connected
05-19 09:21:49.931  3939  3939 D BluetoothMap: getConnectedDevices()
05-19 09:21:49.931  9689  9747 D BluetoothAdapter: onBluetoothStateChange: up=true
,05-19 09:21:49.931  9689  9747 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
05-19 09:21:49.931  9409  9409 D BluetoothSap: Proxy object connected
05-19 09:21:49.931  9409  9409 D SapProfile: Bluetooth service connected
,05-19 09:21:49.931  9409  9420 D BluetoothPan: onBluetoothStateChange on: true
05-19 09:21:49.931  9409  9420 D BluetoothPan: onBluetoothStateChange calling doBind()
,05-19 09:21:49.931  3511  3528 V AlarmManager:  remove PendingIntent] PendingIntent{b888e52: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.931  3939  3939 D BluetoothPan: BluetoothPAN Proxy object connected
05-19 09:21:49.931  3939  3939 D PanProfile: Bluetooth service connected
05-19 09:21:49.931  3511  4343 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,05-19 09:21:49.941  9409  9409 D BluetoothPan: BluetoothPAN Proxy object connected
,05-19 09:21:49.941  9409  9409 D PanProfile: Bluetooth service connected
,05-19 09:21:49.941  3939  3939 D BluetoothSap: Proxy object connected
05-19 09:21:49.941  3939  3939 D SapProfile: Bluetooth service connected
,05-19 09:21:49.941  3939  3950 D BluetoothInputDevice: onBluetoothStateChange: up=true
05-19 09:21:49.941  3939  3950 D BluetoothInputDevice: Binding service...
,05-19 09:21:49.941  3511  3982 V AlarmManager:  remove PendingIntent] PendingIntent{ccd907f: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.941  3939  3939 D BluetoothInputDevice: Proxy object connected
,05-19 09:21:49.941  3939  3939 D HidProfile: Bluetooth service connected
,05-19 09:21:49.951  9409  9419 D BluetoothMap: onBluetoothStateChange: up=true
,05-19 09:21:49.951  4853  4865 D BluetoothAdapter: onBluetoothStateChange: up=true
05-19 09:21:49.951  4853  4865 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,05-19 09:21:49.951  9409  9841 D BluetoothLeAudio: onBluetoothStateChange: up=true
,05-19 09:21:49.951  3511  4185 V AlarmManager:  remove PendingIntent] PendingIntent{6c7684c: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:49.951  9787  9847 D BluetoothSocket: bindListen(): myUserId = 0
05-19 09:21:49.951  9787  9847 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,05-19 09:21:49.961  3511  3511 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
05-19 09:21:49.961  3511  3511 I InputMethodManagerService: [BT Setting State] State =12
05-19 09:21:49.961  3511  3511 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,05-19 09:21:49.961  3939  4163 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,05-19 09:21:49.961  3939  4163 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
05-19 09:21:49.961  3511  3511 I Telecom : BluetoothPhoneService: queryPhoneState
05-19 09:21:49.961  3511  3511 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState : true
,05-19 09:21:49.961  4344  4344 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
,05-19 09:21:49.961  4917  4917 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
05-19 09:21:49.961  9787  9846 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,05-19 09:21:49.961  3511  3511 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
05-19 09:21:49.961  3511  3511 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
05-19 09:21:49.961  3511  3511 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,05-19 09:21:49.961  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,05-19 09:21:49.961  9787  9846 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,05-19 09:21:49.971  9409  9409 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
05-19 09:21:49.971  9409  9409 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,05-19 09:21:49.981  3511  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b76c095 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a2e0fe7 9409:com.android.settings/1000}
,05-19 09:21:49.981  9689  9689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-19 09:21:49.981  9787  9847 I BtOppRfcommListener: Accept thread started.
,05-19 09:21:49.981  9409  9409 D LocalBluetoothProfileManager: Adding local A2DP profile
,05-19 09:21:49.991  9409  9409 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,05-19 09:21:50.001  9849  9849 E Zygote  : v2
05-19 09:21:50.001  9849  9849 I libpersona: KNOX_SDCARD checking this for 10052
05-19 09:21:50.001  9849  9849 E Zygote  : isSdpEnabledProcess - SDP enabled
05-19 09:21:50.001  9849  9849 I libpersona: KNOX_SDCARD not a persona
,05-19 09:21:50.001  9849  9849 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-19 09:21:50.001  3511  3852 I ActivityManager: Start proc 9849:com.samsung.android.email.provider/u0a52 for content provider com.samsung.android.email.provider/.provider.database.EmailProvider
,05-19 09:21:50.001  9849  9849 E Zygote  : accessInfo : 64
05-19 09:21:50.001  9849  9849 E Zygote  : isSdpEnabledProcess - SDP enabled
05-19 09:21:50.001  9849  9849 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10052 / [uid]: 10052
05-19 09:21:50.001  3511  3855 D NetworkPolicy: isUidForegroundLocked: 10052, mScreenOn: true, uidstate: -1, mProxSensorScreenOff: false
05-19 09:21:50.001  9849  9849 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.email.provider 
,05-19 09:21:50.001  9409  9409 D LocalBluetoothProfileManager: Adding local HEADSET profile
,05-19 09:21:50.001  3511  4313 V AlarmManager:  remove PendingIntent] PendingIntent{3d56276: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:50.001  3939  4163 W LocalBluetoothProfileManager: updateLocalProfiles :: MAP profile was previously added but the UUID is now missing.
05-19 09:21:50.001  3939  4163 W LocalBluetoothProfileManager: updateLocalProfiles :: PBAP profile was previously added but the UUID is now missing.
05-19 09:21:50.001  3939  4163 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
05-19 09:21:50.001  3939  4163 W LocalBluetoothProfileManager: updateLocalProfiles :: HID profile was previously added but the UUID is now missing.
05-19 09:21:50.001  3939  4163 W LocalBluetoothProfileManager: updateLocalProfiles :: BleAudio profile was created already 
,05-19 09:21:50.011  9409  9409 E BluetoothHeadset: BTStateChangeCB is registed
,05-19 09:21:50.011  9409  9409 W LocalBluetoothProfileManager: updateLocalProfiles :: MAP profile was previously added but the UUID is now missing.
05-19 09:21:50.011  9409  9409 W LocalBluetoothProfileManager: updateLocalProfiles :: PBAP profile was previously added but the UUID is now missing.
05-19 09:21:50.011  9409  9409 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
05-19 09:21:50.011  9409  9409 W LocalBluetoothProfileManager: updateLocalProfiles :: HID profile was previously added but the UUID is now missing.
05-19 09:21:50.011  9409  9409 W LocalBluetoothProfileManager: updateLocalProfiles :: BleAudio profile was created already 
,05-19 09:21:50.011  3511  3529 V AlarmManager:  remove PendingIntent] PendingIntent{4cf6d4d: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:50.011  3939  4254 D BluetoothTile: handleUpdateState :  supported = true, enabled = true, enabling = false, connected = false, connecting = false, mController.getLastDeviceName() = null
,05-19 09:21:50.011  3511  3528 D StatusBarManagerService: setIcon slot=bluetooth index=18 icon=StatusBarIcon(icon=Icon(typ=RESOURCE pkg=com.android.systemui id=0x7f02049a) visible user=0 )
,05-19 09:21:50.021  3511  4449 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
05-19 09:21:50.021  3511  3982 V AlarmManager:  remove PendingIntent] PendingIntent{96a3d13: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:50.021  9409  9409 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,05-19 09:21:50.021  3511  3528 V AlarmManager:  remove PendingIntent] PendingIntent{5329149: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:50.031  3511  3855 D NetworkPolicy: isUidForegroundLocked: 10052, mScreenOn: true, uidstate: 16, mProxSensorScreenOff: false
,05-19 09:21:50.031  9409  9409 D BluetoothA2dp: Proxy object connected
,05-19 09:21:50.041  9409  9409 D A2dpProfile: Bluetooth service connected
,05-19 09:21:50.041  3511  4451 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b76c095 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cf9e5aa 4853:com.samsung.android.providers.context/u0a9}
,05-19 09:21:50.051  9689  9775 D BluetoothAdapter: STATE_ON
,05-19 09:21:50.051  9849  9849 D TimaKeyStoreProvider: TimaSignature is unavailable
05-19 09:21:50.051  9849  9849 D ActivityThread: Added TimaKeyStore provider
,05-19 09:21:50.051  9689  9775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-19 09:21:50.051  9689  9775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-19 09:21:50.051  9689  9775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-19 09:21:50.051  9689  9775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-19 09:21:50.051  9689  9775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-19 09:21:50.051  9689  9775 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-19 09:21:50.051  9689  9775 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-19 09:21:50.051  9689  9775 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-19 09:21:50.051  9689  9775 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,05-19 09:21:50.051  9689  9753 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
,05-19 09:21:50.051  9787  9826 D A2dpStateMachine: getConnectedDevices : size=0
,05-19 09:21:50.061  3511  4313 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,05-19 09:21:50.061  9689  9753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-19 09:21:50.061  3511  4313 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,05-19 09:21:50.061  3511  4313 D WifiService: setWifiEnabled: false pid=9689, uid=10078
05-19 09:21:50.061  3511  4451 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b76c095 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dc64001 4328:com.google.android.gms.persistent/u0a21}
05-19 09:21:50.061  4328  4328 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
,05-19 09:21:50.081  3511  4313 D SettingsProvider: isChangeAllowed() : name = wifi_on
,05-19 09:21:50.081  3511  4198 V AlarmManager:  remove PendingIntent] PendingIntent{6424a4e: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:50.081  3511  3857 D WifiBigDataLog: getJsonFormat() - feature : ONOF
05-19 09:21:50.081  9409  9409 D DockEventReceiver: finishStartingService: stopping service
05-19 09:21:50.081  3511  3857 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,05-19 09:21:50.081  3511  3860 D WifiController: [FCC]setFccChannel() is called !!!
05-19 09:21:50.081  3511  3860 D WifiStateMachine: setFccChannel: channel = 0
05-19 09:21:50.081  3511  3860 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
05-19 09:21:50.081  3511  3860 D WifiController: MHS off and WIFI tunred off and move to mApStaDisabledState
,05-19 09:21:50.081  3511  3860 D SecContentProvider: insert(), uri = 2
,05-19 09:21:50.091  3511  4070 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b76c095 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7e09761 8967:com.sec.android.app.shealth:remote/u0a39}
,05-19 09:21:50.101  9849  9849 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,05-19 09:21:50.101  9849  9849 D RelationGraph: garbageCollect()
,05-19 09:21:50.101  9849  9849 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in com.samsung.android.email.provider rsrc of package com.samsung.android.email.provider
,05-19 09:21:50.101  3511  4449 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-19 09:21:50.101  9849  9849 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-19 09:21:50.111  9849  9849 D ResourcesManager: For user 0 new overlays fetched Null
05-19 09:21:50.111  3511  3857 D WifiBigDataLog: init : 
,05-19 09:21:50.111  3511  3857 D WifiStateMachine: setFccChannelNative: channel = 0
05-19 09:21:50.111  3511  3857 D WifiNative-wlan0: callSECApiInt - ID [230]
,05-19 09:21:50.121  3511  4422 V AlarmManager:  remove PendingIntent] PendingIntent{71b7c7c: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:50.121  9849  9849 I InjectionManager: Inside getClassLibPath caller 
,05-19 09:21:50.131  3511  3528 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b76c095 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a2e0fe7 9409:com.android.settings/1000}
,05-19 09:21:50.131  9409  9409 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
05-19 09:21:50.131  9409  9409 D BluetoothStatusReceiver: AdapterStateChanged :: state = 12
,05-19 09:21:50.141  3511  3528 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b76c095 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c35b0ed 9787:com.android.bluetooth/1002}
,05-19 09:21:50.141  3511  3857 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,05-19 09:21:50.151  9849  9849 W System  : ClassLoader referenced unknown path: /system/priv-app/SecEmail_M/lib/arm64
,05-19 09:21:50.151  3511  3857 D WifiStateMachine: isPackageRunning - top:com.rockwellautomation.thalitest.MainActivity
,05-19 09:21:50.151  3511  3857 D WifiStateMachine: isPackageRunning - top:com.rockwellautomation.thalitest.MainActivity
05-19 09:21:50.151  3511  3857 D WifiStateMachine: sendBroadcastForCaptivePortalNotLoginIcon : false
,05-19 09:21:50.161  3511  4070 V AlarmManager:  remove PendingIntent] PendingIntent{a89f905: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:50.161  3511  3857 D WifiStateMachine: isPackageRunning - top:com.rockwellautomation.thalitest.MainActivity
05-19 09:21:50.161  3511  3857 D WifiStateMachine: isPackageRunning - top:com.rockwellautomation.thalitest.MainActivity
05-19 09:21:50.161  3939  4163 D NetworkController: onReceive: intent=Intent { act=com.samsung.intent.action.WIFI_CAPTIVE_NOT_LOGIN flg=0x10 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
05-19 09:21:50.161  3939  4163 D NetworkController.WifiSignalController: updateWifiState : mCurrentState.wifiCaptiveNotLogin = false
,05-19 09:21:50.161  3511  3857 D SecContentProvider: insert(), uri = 2
,05-19 09:21:50.161  3511  3857 D WifiStateMachine: isPackageRunning - top:com.rockwellautomation.thalitest.MainActivity
05-19 09:21:50.161  3511  3857 D WifiStateMachine: isPackageRunning - top:com.rockwellautomation.thalitest.MainActivity
05-19 09:21:50.161  3511  3857 D WifiStateMachine: sendBroadcastForCaptivePortalNotLoginIcon : false
,05-19 09:21:50.161  3511  4459 V AlarmManager:  remove PendingIntent] PendingIntent{57cbd5a: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:50.161  3939  4163 D NetworkController: onReceive: intent=Intent { act=com.samsung.intent.action.WIFI_CAPTIVE_NOT_LOGIN flg=0x10 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
05-19 09:21:50.161  3511  3857 D WifiStateMachine: isPackageRunning - top:com.rockwellautomation.thalitest.MainActivity
05-19 09:21:50.161  3939  4163 D NetworkController.WifiSignalController: updateWifiState : mCurrentState.wifiCaptiveNotLogin = false
05-19 09:21:50.161  3511  3857 D WifiStateMachine: isPackageRunning - top:com.rockwellautomation.thalitest.MainActivity
,05-19 09:21:50.161  3511  3857 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,05-19 09:21:50.171  3511  3856 D WifiP2pService: InactiveState{ what=143375 }
,05-19 09:21:50.171  3511  3856 D WifiP2pService: P2pEnabledState{ what=143375 }
05-19 09:21:50.171  3511  4741 V AlarmManager:  remove PendingIntent] PendingIntent{56a3b8b: PendingIntentRecord{101c2d8 android broadcastIntent}}
05-19 09:21:50.171  3158  3685 D CommandListener: Clearing all IP addresses on wlan0
,05-19 09:21:50.171  3511  4451 V AlarmManager:  remove PendingIntent] PendingIntent{4e1e468: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:50.171  3939  4163 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-19 09:21:50.181  4328  7702 V NativeCrypto: Read error: ssl=0x7f83844300: I/O error during system call, Connection timed out
,05-19 09:21:50.191  3511  3866 E ConnectivityService: updateNetworkInfo()
05-19 09:21:50.191  3511  3866 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -26]
05-19 09:21:50.191  3511  3866 E ConnectivityService: updateNetworkInfo()
05-19 09:21:50.191  3511  3866 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = DISCONNECTED
05-19 09:21:50.191  3511  3866 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 6
05-19 09:21:50.191  3511  3866 D NtpTrustedTime: currentTimeMillis() cache hit
05-19 09:21:50.191  3511  3866 V NetworkStats: updateIfacesLocked()
05-19 09:21:50.191  3511  3866 V NetworkStats: performPollLocked(flags=0x1)
,05-19 09:21:50.191  3511  3857 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,05-19 09:21:50.191  3511  3856 D WifiP2pService: InactiveState{ what=131204 }
05-19 09:21:50.201  4115  4115 I wpa_supplicant: P2P: Set prekey state (NONE -> NONE)
05-19 09:21:50.201  3511  3856 D WifiP2pService: P2pEnabledState{ what=131204 }
05-19 09:21:50.201  4115  4115 I wpa_supplicant: P2P: Clear a pre-passphrase (State NONE)
05-19 09:21:50.201  3511  3856 D WifiP2pService: sending p2p connection changed broadcast: FAILED
05-19 09:21:50.201  4328  7702 V NativeCrypto: SSL shutdown failed: ssl=0x7f83844300: I/O error during system call, Broken pipe
05-19 09:21:50.201  3511  3866 D NetworkStatsRecorder: entry.iface is null
05-19 09:21:50.201  3511  3866 D NtpTrustedTime: currentTimeMillis() cache hit
05-19 09:21:50.201  3511  3866 D NetworkStatsRecorder: entry.iface is null
,05-19 09:21:50.201  3511  3866 D NetworkStatsRecorder: entry.iface is null
05-19 09:21:50.201  3511  3866 D NetworkStatsRecorder: entry.iface is null
05-19 09:21:50.201  3511  3866 V NetworkStats: performPollLocked() took 12ms
,05-19 09:21:50.201  3511  4449 V AlarmManager:  remove PendingIntent] PendingIntent{8362081: PendingIntentRecord{2c2faaf com.google.android.gms broadcastIntent}}
,05-19 09:21:50.211  3511  4422 D RCPManagerService: exchangeData() failure , invalid userId
,05-19 09:21:50.211  3511  3511 I WifiTrafficPoller: evaluateTrafficStatsPolling
,05-19 09:21:50.211  3511  3511 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
,05-19 09:21:50.211  3511  3511 D HS20StateMachine: [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true]
05-19 09:21:50.211  3511  3511 D HS20StateMachine: checkifOSUAP  null disconnectedFromSsid"NG700"
05-19 09:21:50.211  3511  3511 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
,05-19 09:21:50.211  3511  3864 I WifiHs20Service: Message received 5007
05-19 09:21:50.221  3511  3511 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
,05-19 09:21:50.221  3939  4163 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-19 09:21:50.221  4287  4287 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
05-19 09:21:50.221  3511  3866 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-19 09:21:50.221  3511  3511 D RttService: SCAN_AVAILABLE : 1
05-19 09:21:50.221  3511  3866 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -26]
,05-19 09:21:50.221  3511  3891 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
05-19 09:21:50.221  3511  3866 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
05-19 09:21:50.221  3511  3866 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 09:21:50.221  3511  3866 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 09:21:50.221  3511  3866 D ConnectivityService: sending notification LOST for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 09:21:50.221  3511  3866 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
,05-19 09:21:50.221  3511  3866 D ConnectivityService: sending notification LOST for NetworkRequest [ id=5, legacyType=-1, [] ]
05-19 09:21:50.231  3511  3866 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 09:21:50.231  3511  3866 D ConnectivityService: sending notification LOST for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-19 09:21:50.231  3511  3866 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-19 09:21:50.231  3511  3866 D ConnectivityService: sending notification LOST for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-19 09:21:50.231  3511  3866 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-19 09:21:50.231  3511  3866 D ConnectivityService: sending notification LOST for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-19 09:21:50.231  3511  4198 D ConnectivityService: getVpnConfig > userId : 0
,05-19 09:21:50.241  3511  4739 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
05-19 09:21:50.241  3511  3866 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 09:21:50.241  3511  3857 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 09:21:50.241  3511  3857 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-19 09:21:50.241  3511  3857 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
05-19 09:21:50.241  3511  3857 D WIFI    : evalRequest
05-19 09:21:50.241  3511  3857 D WIFI    :   needNetworkFor
05-19 09:21:50.241  3511  3857 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 09:21:50.241  3511  3892 D Ethernet: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 09:21:50.241  3511  3857 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-19 09:21:50.241  3511  3892 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
05-19 09:21:50.241  3511  3857 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
05-19 09:21:50.241  3511  3892 D Ethernet: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
05-19 09:21:50.241  3511  3857 D WIFI    : evalRequest
05-19 09:21:50.241  3511  3892 D Ethernet: evalRequest
05-19 09:21:50.241  3511  3892 D Ethernet:   done
05-19 09:21:50.241  3511  3857 D WIFI    :   done
05-19 09:21:50.241  3511  3857 D WIFI_UT : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 09:21:50.241  3511  3857 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-19 09:21:50.241  3511  3857 D WIFI_UT : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
05-19 09:21:50.241  3511  3857 D WIFI_UT : evalRequest
05-19 09:21:50.241  3511  3857 D WIFI_UT :   done
,05-19 09:21:50.251  3511  3649 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-19 09:21:50.251  3511  3649 I WifiDisplayAdapter: onP2pDisconnected
05-19 09:21:50.251  3511  3649 D IpRemoteDisplayController: disconnectWfdBridgeServer
05-19 09:21:50.251  3511  3649 D IpRemoteDisplayController: WfdBridgeServer is already null
,05-19 09:21:50.271  3511  3855 D NtpTrustedTime: currentTimeMillis() cache hit
,05-19 09:21:50.271  3511  3855 D NtpTrustedTime: currentTimeMillis() cache hit
,05-19 09:21:50.271  3511  3647 D EntConnectivity: Not allowed due to - mEnabled false
,05-19 09:21:50.271  3511  3856 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
05-19 09:21:50.271  4328  7702 E GCM     : Wifi connection closed with errorCode 20
,05-19 09:21:50.271  3511  3511 D WifiNotificationController: SHOW_NOTI_MESSAGE : 17, visible : false, ssid : null, targetSSID : null, netId : -1, titleType : -1
,05-19 09:21:50.271  3511  3856 D SecContentProvider: insert(), uri = 2
,05-19 09:21:50.271  3511  3511 D WifiNotificationController: showMaliciousHotspotDetectionNotification - MaliciousNetwork:null, visible:false
,05-19 09:21:50.271  4158  4169 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=17041470,extra=Bundle[mParcelledData.dataSize=84]
,05-19 09:21:50.271  3511  4451 V AlarmManager:  remove PendingIntent] PendingIntent{1b95526: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:50.271  4158  4158 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=17041470, samsung.notification.type=normal, samsung.people.package_name=android}]
,05-19 09:21:50.281  3511  3856 D WifiP2pService: P2pDisablingState
05-19 09:21:50.271  4158  4158 I PeopleStripeService: PeopleNotificationReceiver:3
05-19 09:21:50.271  4158  4158 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
05-19 09:21:50.271  4158  4158 I PeopleDataManager: removeNotification
05-19 09:21:50.271  4158  4158 I NotificationParser: getNotiType:android,null
05-19 09:21:50.281  3511  3856 D WifiP2pService: P2pDisablingState{ what=147458 }
,05-19 09:21:50.271  4158  4158 D PeopleDataManager: removeNotiInfo: id =17041470,packageName=android,isEdgeNotification=false,key=null,removeAll=false
05-19 09:21:50.271  4158  4158 D PeopleDataManager: removeNotiInfo =null
05-19 09:21:50.281  3511  3856 D WifiP2pService: p2p socket connection lost
,05-19 09:21:50.281  3511  3511 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
05-19 09:21:50.281  3511  3856 D SecContentProvider: insert(), uri = 2
,05-19 09:21:50.281  3511  3649 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false, mScanRequestedInConnected = false
05-19 09:21:50.281  3511  3649 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
05-19 09:21:50.281  3511  3649 D WifiDisplayController: disconnect
,05-19 09:21:50.281  3511  3649 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,05-19 09:21:50.281  3511  3857 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,05-19 09:21:50.281  3511  3856 D WifiP2pService: P2pDisabledState
,05-19 09:21:50.281  3511  3856 D WIFI_P2P: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 09:21:50.281  3511  3856 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,05-19 09:21:50.291  3511  3856 D WifiP2pService: P2pDisabledState{ what=143375 }
05-19 09:21:50.281  3511  3856 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
05-19 09:21:50.291  3511  3856 D WifiP2pService: DefaultState{ what=143375 }
05-19 09:21:50.281  3511  3856 D WIFI_P2P: evalRequest
05-19 09:21:50.281  3511  3856 D WIFI_P2P:   done
,05-19 09:21:50.291  3158  3685 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,05-19 09:21:50.291  3939  3939 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 272
05-19 09:21:50.291  3939  3939 D WifiP2pController: onReceive android.net.wifi.p2p.CONNECTION_STATE_CHANGE
05-19 09:21:50.291  3939  3939 D WifiP2pController: onReceive android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,05-19 09:21:50.301  3511  3649 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
05-19 09:21:50.301  3511  3649 I WifiDisplayAdapter: onP2pDisconnected
05-19 09:21:50.301  3511  3649 D IpRemoteDisplayController: disconnectWfdBridgeServer
05-19 09:21:50.301  3511  3649 D IpRemoteDisplayController: WfdBridgeServer is already null
,05-19 09:21:50.321  3939  3939 D SoundPathController: onReceive - android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,05-19 09:21:50.321  3939  3939 D ApMirroringController: onReceive android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,05-19 09:21:50.321  3158  3685 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
05-19 09:21:50.321  3939  3939 D AllShareCastTile: onReceive : android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
05-19 09:21:50.321  3511  3528 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
05-19 09:21:50.321  3939  3939 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
05-19 09:21:50.321  3511  3866 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -26]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} } wasDefault=true
05-19 09:21:50.321  3511  3866 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
05-19 09:21:50.321  3511  3866 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,05-19 09:21:50.321  3158  3685 D CommandListener: Clearing all IP addresses on wlan0
,05-19 09:21:50.331  3511  3647 D EntConnectivity: Not allowed due to - mEnabled false
,05-19 09:21:50.331  3939  4163 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-19 09:21:50.341  3511  3857 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
05-19 09:21:50.341  4115  4115 I wpa_supplicant: Blacklist: Clear (all) 
05-19 09:21:50.341  4115  4115 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
,05-19 09:21:50.341  3511  4185 D RCPManagerService: exchangeData() failure , invalid userId
,05-19 09:21:50.341  3511  3511 I WifiTrafficPoller: evaluateTrafficStatsPolling
,05-19 09:21:50.351  3511  3511 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
05-19 09:21:50.351  3511  3511 D HS20StateMachine: [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false]
,05-19 09:21:50.351  9849  9849 D InjectionManager: InjectionManager
05-19 09:21:50.351  9849  9849 D InjectionManager: fillFeatureStoreMap com.samsung.android.email.provider
,05-19 09:21:50.351  3511  3511 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
05-19 09:21:50.351  9849  9849 I InjectionManager: Constructor com.samsung.android.email.provider, Feature store :{}
05-19 09:21:50.351  9849  9849 I InjectionManager: featureStore :{}
,05-19 09:21:50.351  3511  3864 I WifiHs20Service: Message received 5007
,05-19 09:21:50.351  3511  3511 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
,05-19 09:21:50.351  3939  4163 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-19 09:21:50.361  4287  4287 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,05-19 09:21:50.361  3939  4163 D NetworkController: onReceive: intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-19 09:21:50.361  3511  3589 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,05-19 09:21:50.361  3511  3589 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-19 09:21:50.361  3511  3589 D GpsLocationProvider: updateNetworkState unavailable info: [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-19 09:21:50.361  4287  4297 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,05-19 09:21:50.371  4287  4297 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
05-19 09:21:50.371  3511  3589 D TelephonyManager: getDataEnabled: retVal=true
,05-19 09:21:50.381  4867  4972 D CellLocationSupport: onReceive ACTION = android.net.conn.CONNECTIVITY_CHANGE
05-19 09:21:50.381  4867  4972 I CellLocationSupport: onCellLocationChanged
,05-19 09:21:50.381  3511  3855 D NtpTrustedTime: currentTimeMillis() cache hit
05-19 09:21:50.381  3511  3855 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-19 09:21:50.381  3511  3855 D NtpTrustedTime: currentTimeMillis() cache hit
05-19 09:21:50.381  3511  3855 D NtpTrustedTime: currentTimeMillis() cache hit
05-19 09:21:50.381  3511  3855 D NtpTrustedTime: currentTimeMillis() cache hit
05-19 09:21:50.381  3511  3855 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
,05-19 09:21:50.391  4917  4917 D SamsungIME: EngineType = SWIFTKEY
,05-19 09:21:50.391  4917  4917 D SamsungIME: mNetworkChangeReceiver isWLANConnected : false
,05-19 09:21:50.401  3158  3678 D Netd    : Iface p2p0 link up
,05-19 09:21:50.401  3511  3604 D Tethering: interfaceLinkStateChanged p2p0, true
05-19 09:21:50.401  3511  3604 D Tethering: interfaceStatusChanged p2p0, true
,05-19 09:21:50.401  4867  5177 D PdnController: Interface Changed p2p0 link up
,05-19 09:21:50.411  9787  9787 D BleAudioService: onReceive:: INTENT mAobleStateChangeListener got : android.bluetooth.adapter.action.STATE_CHANGED
05-19 09:21:50.411  9787  9787 D BleAudioService: BluetoothAdapter.ACTION_STATE_CHANGED,  state is12
,05-19 09:21:50.411  4867  4867 D PdnController: CONNECTIVITY_ACTION: networkType 1 isConnected false
05-19 09:21:50.411  9787  9836 D BleAudioStateMachine_R: [Disconnected] Disconnected process message: 41
05-19 09:21:50.411  4867  4867 D PdnController: isSuspended [false] networktype [1]
05-19 09:21:50.411  9787  9836 D BleAudioStateMachine_R: [Disconnected] MSG_ADAPTER_BT_ON_EVT event received
05-19 09:21:50.411  9787  9835 D BleAudioStateMachine_L: [Disconnected] Disconnected process message: 41
05-19 09:21:50.411  9787  9835 D BleAudioStateMachine_L: [Disconnected] MSG_ADAPTER_BT_ON_EVT event received
,05-19 09:21:50.411  3511  3852 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-19 09:21:50.411  4867  4867 D PdnController: isPdnUp  [false] networktype [1]
05-19 09:21:50.411  4867  4867 D PdnController: Notify Result to LocalIP Registrants! : networkType [1] isConnected [false] 
05-19 09:21:50.411  9787  9835 D BleAudioStateMachine: getLastConnectedDeviceAddress() for channel = 1
05-19 09:21:50.411  9787  9835 D BleAudioService: NotifyEvents: n : 0
05-19 09:21:50.421  9787  9836 D BleAudioStateMachine: getLastConnectedDeviceAddress() for channel = 2
05-19 09:21:50.421  9787  9836 D BleAudioService: NotifyEvents: n : 0
,05-19 09:21:50.421  5466  5466 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@70a607c and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-19 09:21:50.421  4867  4972 I CellLocationSupport: Block to update PANI information in non VoWIFI
05-19 09:21:50.421  4867  4972 D SlickSSConfigHandler: EVENT_LOCAL_IP_CHANGED
,05-19 09:21:50.421  3511  4422 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-19 09:21:50.421  4867  4972 D PdnController: isIfaceDisconnected result [true] networkType [0] interfaceName [null] 
05-19 09:21:50.421  4867  4972 D PdnController: isPdnUp  [false] networktype [0]
05-19 09:21:50.421  4867  4972 D SlickSSConfigHandler: handleNetworkStateChange: check isDefaultPDNConnected[false], mReadyForDocFetch[false
,05-19 09:21:50.421  4454  4454 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
05-19 09:21:50.421  3511  4343 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-19 09:21:50.421  6953  6953 I FOTA_AGENT: [com.samsung.android.app.syncmldm.XDMService(1060/IIllllIIlIIllIIIIlll)] WiFi network Connected : false
,05-19 09:21:50.431  3511  4070 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-19 09:21:50.431  4867  4972 D RegistrationManager: handleMessage(): 5
,05-19 09:21:50.431  3511  4422 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-19 09:21:50.431  4867  4972 D PdnController: isIfaceDisconnected result [true] networkType [11] interfaceName [null] 
05-19 09:21:50.431  4867  4972 D PdnController: isPdnUp  [false] networktype [11]
05-19 09:21:50.431  4867  4972 D RegistrationManager: setEPDGIPSecConnected [false]
05-19 09:21:50.431  4867  4972 D RegistrationManager: notifyNetworkState : NetworkType [1] IsConnected [false] IPAddresses [[]] DNSAddresses [[]] 
05-19 09:21:50.431  4867  4972 D RegistrationManager: isEPDGAvailable [false]
05-19 09:21:50.431  4867  4972 D CoreController: setState [DEREGISTERED]
,05-19 09:21:50.441  9689  9689 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,05-19 09:21:50.441  9689  9689 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,05-19 09:21:50.451  4115  4115 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,05-19 09:21:50.451  3158  3685 E Netd    : netlink response contains error (No such file or directory)
,05-19 09:21:50.451  3158  3681 D EnterpriseController: netId is 0
05-19 09:21:50.451  3158  3681 D Netd    : getNetworkForDns: using netid 0 for uid 10002
,05-19 09:21:50.461  3511  3866 D ConnectivityService: setProvNotificationVisibleIntent SIGN_IN visible=false networkType=WIFI extraInfo=null highPriority=false
,05-19 09:21:50.461  3511  3866 D ConnectivityService: nai.networkMonitor.doQuit()
05-19 09:21:50.461  3511  3866 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: doQuit - quitNow()
05-19 09:21:50.461  3511  3866 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-19 09:21:50.461  3511  3866 E ConnectivityService: updateNetworkInfo()
05-19 09:21:50.461  3511  3866 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
05-19 09:21:50.461  3511  3866 E ConnectivityService: updateNetworkInfo()
,05-19 09:21:50.461  4579  9878 E         : Error communicating to API: https://prod.yana.asideas.de/api/v2/advertising/frequencies/pl
05-19 09:21:50.461  4579  9878 E         : retrofit.RetrofitError: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
05-19 09:21:50.461  4579  9878 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:395)
05-19 09:21:50.461  4579  9878 E         : 	at retrofit.RestAdapter$RestHandler.access$100(RestAdapter.java:220)
05-19 09:21:50.461  4579  9878 E         : 	at retrofit.RestAdapter$RestHandler$1.invoke(RestAdapter.java:265)
05-19 09:21:50.461  4579  9878 E         : 	at retrofit.RxSupport$2.run(RxSupport.java:55)
05-19 09:21:50.461  4579  9878 E         : 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
05-19 09:21:50.461  4579  9878 E         : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
05-19 09:21:50.461  4579  9878 E         : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
05-19 09:21:50.461  4579  9878 E         : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
05-19 09:21:50.461  4579  9878 E         : 	at retrofit.Platform$Android$2$1.run(Platform.java:142)
05-19 09:21:50.461  4579  9878 E         : 	at java.lang.Thread.run(Thread.java:818)
05-19 09:21:50.461  4579  9878 E         : Caused by: java.net.UnknownHostException: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
05-19 09:21:50.461  4579  9878 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:470)
05-19 09:21:50.461  4579  9878 E         : 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
05-19 09:21:50.461  4579  9878 E         : 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
05-19 09:21:50.461  4579  9878 E         : 	at com.squareup.okhttp.internal.Network$1.resolveInetAddresses(Network.java:29)
05-19 09:21:50.461  4579  9878 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:187)
05-19 09:21:50.461  4579  9878 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.nextProxy(RouteSelector.java:156)
05-19 09:21:50.461  4579  9878 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.next(RouteSelector.java:98)
05-19 09:21:50.461  4579  9878 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.createNextConnection(HttpEngine.java:344)
05-19 09:21:50.461  4579  9878 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:327)
05-19 09:21:50.461  4579  9878 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:245)
05-19 09:21:50.461  4579  9878 E         : 	at com.squareup.okhttp.Call.getResponse(Call.java:267)
05-19 09:21:50.461  4579  9878 E         : 	at com.squareup.okhttp.Call$ApplicationInterceptorChain.proceed(Call.java:224)
05-19 09:21:50.461  4579  9878 E         : 	at com.squareup.okhttp.Call.getResponseWithInterceptorChain(Call.java:195)
05-19 09:21:50.461  4579  9878 E         : 	at com.squareup.okhttp.Call.execute(Call.java:79)
05-19 09:21:50.461  4579  9878 E         : 	at retrofit.client.OkClient.execute(OkClient.java:53)
05-19 09:21:50.461  4579  9878 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:326)
05-19 09:21:50.461  4579  9878 E         : 	... 9 more
05-19 09:21:50.461  4579  9878 E         : Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
05-19 09:21:50.461  4579  9878 E         : 	at libcore.io.Posix.android_getaddrinfo(Native Method)
05-19 09:21:50.461  4579  9878 E         : 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
05-19 09:21:50.461  4579  9878 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:451)
05-19 09:21:50.461  4579  9878 E         : 	... 24 more
05-19 09:21:50.461  4579  9878 E         : 
05-19 09:21:,50.461  4115  4115 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
05-19 09:21:50.461  4579  9878 E         : Unable to fetch advertisement frequency.
05-19 09:21:50.461  4579  9878 E         : retrofit.RetrofitError: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
05-19 09:21:50.461  4579  9878 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:395)
05-19 09:21:50.461  4579  9878 E         : 	at retrofit.RestAdapter$RestHandler.access$100(RestAdapter.java:220)
05-19 09:21:50.461  4579  9878 E         : 	at retrofit.RestAdapter$RestHandler$1.invoke(RestAdapter.java:265)
05-19 09:21:50.461  4579  9878 E         : 	at retrofit.RxSupport$2.run(RxSupport.java:55)
05-19 09:21:50.461  4579  9878 E         : 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
05-19 09:21:50.461  4579  9878 E         : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
05-19 09:21:50.461  4579  9878 E         : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
05-19 09:21:50.461  4579  9878 E         : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
05-19 09:21:50.461  4579  9878 E         : 	at retrofit.Platform$Android$2$1.run(Platform.java:142)
05-19 09:21:50.461  4579  9878 E         : 	at java.lang.Thread.run(Thread.java:818)
05-19 09:21:50.461  4579  9878 E         : Caused by: java.net.UnknownHostException: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
05-19 09:21:50.461  4579  9878 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:470)
05-19 09:21:50.461  4579  9878 E         : 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
05-19 09:21:50.461  4579  9878 E         : 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
05-19 09:21:50.461  4579  9878 E         : 	at com.squareup.okhttp.internal.Network$1.resolveInetAddresses(Network.java:29)
05-19 09:21:50.461  4579  9878 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:187)
05-19 09:21:50.461  4579  9878 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.nextProxy(RouteSelector.java:156)
05-19 09:21:50.461  4579  9878 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.next(RouteSelector.java:98)
05-19 09:21:50.461  4579  9878 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.createNextConnection(HttpEngine.java:344)
05-19 09:21:50.461  4579  9878 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:327)
05-19 09:21:50.461  4579  9878 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:245)
05-19 09:21:50.461  4579  9878 E         : 	at com.squareup.okhttp.Call.getResponse(Call.java:267)
05-19 09:21:50.461  4579  9878 E         : 	at com.squareup.okhttp.Call$ApplicationInterceptorChain.proceed(Call.java:224)
05-19 09:21:50.461  4579  9878 E         : 	at com.squareup.okhttp.Call.getResponseWithInterceptorChain(Call.java:195)
05-19 09:21:50.461  4579  9878 E         : 	at com.squareup.okhttp.Call.execute(Call.java:79)
05-19 09:21:50.461  4579  9878 E         : 	at retrofit.client.OkClient.execute(OkClient.java:53)
05-19 09:21:50.461  4579  9878 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:326)
05-19 09:21:50.461  4579  9878 E         : 	... 9 more
05-19 09:21:50.461  4579  9878 E         : Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
05-19 09:21:50.461  4579  9878 E         : 	at libcore.io.Posix.android_getaddrinfo(Native Method)
05-19 09:21:50.461  4579  9878 E         : 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
05-19 09:21:50.461  4579  9878 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:451)
05-19 09:21:50.461  4579  9878 E         : 	... 24 more
05-19 09:21:50.461  4579  9878 E         : 
05-19 09:21:50.461  3511  3857 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
05-19 09:21:50.461  3939  4163 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
05-19 09:21:50.471  3158  3678 D Netd    : Iface wlan0 link up
05-19 09:21:50.471  3939  3939 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 272
05-19 09:21:50.471  3939  3939 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
05-19 09:21:50.471  3511  3604 D Tethering: interfaceLinkStateChanged wlan0, true
05-19 09:21:50.471  3511  3604 D Tethering: interfaceStatusChanged wlan0, true
05-19 09:21:50.471  3939  3939 I HotspotTile: Provider is not defined returning false
05-19 09:21:50.481  4867  4880 D PdnController: Interface Changed wlan0 link up
05-19 09:21:50.481  9689  9689 D BluetoothAdapter: STATE_ON
05-19 09:21:50.481  3939  3939 D HotspotTile: onReceive : 0, 0
05-19 09:21:50.481  3511  3511 D Tethering: Tethering got CONNECTIVITY_ACTION
05-19 09:21:50.481  3511  3647 D Tethering: MasterInitialState.processMessage what=3
05-19 09:21:50.481  3511  3511 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:50.481  3511  3511 I CLocInfoService: ['16.5] External Intent Received android.net.conn.CONNECTIVITY_CHANGE
05-19 09:21:50.481  3511  3511 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:50.481  3511  3511 I CLocInfoService: CLoinfo wifi false
05-19 09:21:50.481  3511  3511 V MARsPolicyManager: DataConnection: false
05-19 09:21:50.481  3511  3511 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
05-19 09:21:50.481  3511  4238 V AlarmManager:  remove PendingIntent] PendingIntent{f635ff1: PendingIntentRecord{9f177d6 android broadcastIntent}}
05-19 09:21:50.481  3511  3511 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
05-19 09:21:50.481  3511  3864 I WifiHs20Service: Message received 5011
05-19 09:21:50.481  3511  3511 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
05-19 09:21:50.481  3511  4235 W SLocation: No Active Data Connection
05-19 09:21:50.481  3511  4235 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:50.481  3511  9881 I ApplicationPolicy: updateDataUsageMap
05-19 09:21:50.491  4158  7351 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=0,extra=Bundle[mParcelledData.dataSize=84]
05-19 09:21:50.491  4158  4158 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=0, samsung.notification.type=normal, samsung.people.package_name=android}]
05-19 09:21:50.491  4158  4158 I PeopleStripeService: PeopleNotificationReceiver:3
05-19 09:21:50.491  4158  4158 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
05-19 09:21:50.491  4158  4158 I PeopleDataManager: removeNotification
05-19 09:21:50.491  4158  4158 I NotificationParser: getNotiType:android,null
05-19 09:21:50.491  4158  4158 D PeopleDataManager: removeNotiInfo: id =0,packageName=android,isEdgeNotification=false,key=null,removeAll=false
05-19 09:21:50.491  4158  4158 D PeopleDataManager: removeNotiInfo =null
05-19 09:21:50.491  3511  4422 V AlarmManager:  remove PendingIntent] PendingIntent{53f0567: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:50.491  3511  3868 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
05-19 09:21:50.501  4287  4298 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
05-19 09:21:50.501  4287  4298 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
05-19 09:21:50.501  3511  3868 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,05-19 09:21:50.501  3511  3868 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
05-19 09:21:50.501  4287  4298 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
05-19 09:21:50.501  4287  4298 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
05-19 09:21:50.501  3511  3868 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
05-19 09:21:50.511  7208  7365 I SQLiteDatabase: can't enable WAL for memory databases.
05-19 09:21:50.521  7208  7365 I SQLiteDatabase: can't enable WAL for memory databases.
,05-19 09:21:50.561  9689  9689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-19 09:21:50.561  9689  9689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-19 09:21:50.561  9689  9689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-19 09:21:50.561  9689  9689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
05-19 09:21:50.561  9689  9689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-19 09:21:50.561  9689  9689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
05-19 09:21:50.561  9689  9689 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
05-19 09:21:50.561  9689  9689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
05-19 09:21:50.561  9689  9689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,05-19 09:21:50.561  9689  9689 D BluetoothAdapter: STATE_ON
,05-19 09:21:50.561  9689  9689 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,05-19 09:21:50.561  9689  9689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-19 09:21:50.571  9883  9883 E Zygote  : v2
05-19 09:21:50.571  9883  9883 I libpersona: KNOX_SDCARD checking this for 10052
05-19 09:21:50.571  9883  9883 I libpersona: KNOX_SDCARD not a persona
,05-19 09:21:50.571  9883  9883 E Zygote  : isSdpEnabledProcess - SDP enabled
,05-19 09:21:50.571  9883  9883 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
05-19 09:21:50.571  3511  4407 I ActivityManager: Start proc 9883:com.samsung.android.email.provider:service/u0a52 for service com.samsung.android.email.provider/com.samsung.android.email.sync.service.EmailService
,05-19 09:21:50.571  9883  9883 E Zygote  : accessInfo : 64
05-19 09:21:50.571  9883  9883 E Zygote  : isSdpEnabledProcess - SDP enabled
05-19 09:21:50.571  9883  9883 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10052 / [uid]: 10052
05-19 09:21:50.571  9883  9883 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.email.provider:service 
,05-19 09:21:50.581  4287  4542 D TelephonyProvider: query: url=content://telephony/carriers/preferapn, projectionIn=[Ljava.lang.String;@9d2e93c, selection=nullselectionArgs=null, sort=name ASC
,05-19 09:21:50.581  4287  4542 D TelephonyProvider: query: match = 5
05-19 09:21:50.581  4287  4542 D TelephonyProvider: getPreferredApnId(subId = 2147483643),return -1
05-19 09:21:50.581  4287  4542 D TelephonyProvider: query: selection modified to edited!=2 and edited!=3 and edited!=5 and edited!=6
,05-19 09:21:50.591  4115  4115 I wpa_supplicant: Blacklist: Clear (all) 
05-19 09:21:50.591  4115  4115 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,05-19 09:21:50.591  9787  9787 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ca63953
05-19 09:21:50.591  9787  9787 D BtConfig.SecureMode: isSecureModeOn:false
,05-19 09:21:50.591  4867  4972 D TranslatorCollection: translateToNwkSvcType: networkType XAN_NWK_TYPE_WLAN
05-19 09:21:50.591  4867  4972 D RegistrationManager: getNetworkType [0]
05-19 09:21:50.591  4867  4972 D CoreStackAdaptor2: notifyNetworkState() [1] isConnected [false] nwkSvcType  [XAN_NWK_TYPE_WLAN] nwkInfoType [XAN_SVC_NETWORK_SVCTYPE_WIFI] dedicated   [NONE] 
05-19 09:21:50.591  4867  4972 D TranslatorCollection: translateToNwkSvcType: networkType XAN_NWK_TYPE_WLAN
05-19 09:21:50.591  4867  4972 D CoreStackAdaptor2: ipList =  Null
05-19 09:21:50.591  4867  4972 D RegistrationManager: tryRegister(CONNECTIVITY_STATUS_CHANGE)
05-19 09:21:50.591  4867  4972 D RegistrationManager: isPreconditionProperToGoOn
05-19 09:21:50.591  4867  4972 D RegistrationManager: isDeviceShutdown [false]
05-19 09:21:50.591  4867  4972 D RegistrationManager: isStackShuttingDownForAllPDNs [false]
05-19 09:21:50.591  4867  4972 D RegistrationManager: isDmVoLTEUpdated [false]
05-19 09:21:50.591  4867  4972 D RegistrationManager: tryRegister : Abort Reason [IMS feature disabled]
05-19 09:21:50.591  4867  4972 D RegistrationManager: tryRegister : Not all preconditions are met!
,05-19 09:21:50.601  9409  9409 D HeadsetProfile: Bluetooth service connected
,05-19 09:21:50.601  3939  3939 D HeadsetProfile: Bluetooth service connected
,05-19 09:21:50.601  3511  3511 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@d2343bd
05-19 09:21:50.601  3511  3511 D BluetoothHeadset: registerMessageListener
,05-19 09:21:50.611  9689  9775 D BluetoothAdapter: STATE_ON
,05-19 09:21:50.621  9883  9883 D TimaKeyStoreProvider: TimaSignature is unavailable
05-19 09:21:50.621  9883  9883 D ActivityThread: Added TimaKeyStore provider
,05-19 09:21:50.631  3158  3678 D Netd    : Iface wlan0 link up
05-19 09:21:50.631  3158  3678 D Netd    : Iface wlan0 link up
05-19 09:21:50.631  3511  3604 D Tethering: interfaceLinkStateChanged wlan0, true
05-19 09:21:50.631  3511  3604 D Tethering: interfaceStatusChanged wlan0, true
,05-19 09:21:50.631  9689  9775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-19 09:21:50.631  9689  9775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-19 09:21:50.631  9689  9775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-19 09:21:50.631  9689  9775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
05-19 09:21:50.631  9689  9775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-19 09:21:50.631  9689  9775 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
05-19 09:21:50.631  9689  9775 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
05-19 09:21:50.631  9689  9775 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
05-19 09:21:50.631  9689  9775 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
05-19 09:21:50.631  4867  5177 D PdnController: Interface Changed wlan0 link up
05-19 09:21:50.631  3511  3982 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b76c095 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{40b9903 7208:com.google.android.apps.maps/u0a125}
,05-19 09:21:50.631  9689  9689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-19 09:21:50.631  3511  3604 D Tethering: interfaceLinkStateChanged wlan0, true
05-19 09:21:50.631  3511  3604 D Tethering: interfaceStatusChanged wlan0, true
,05-19 09:21:50.641  4867  4881 D PdnController: Interface Changed wlan0 link up
05-19 09:21:50.641  9689  9753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
05-19 09:21:50.641  9689  9775 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,05-19 09:21:50.641  9787  9797 D HeadsetService: registerMessageListener
05-19 09:21:50.641  3158  3678 D Netd    : Iface p2p0 link down
,05-19 09:21:50.641  3511  3604 D Tethering: interfaceLinkStateChanged p2p0, false
05-19 09:21:50.641  3511  3604 D Tethering: interfaceStatusChanged p2p0, false
,05-19 09:21:50.641  9787  9797 D HeadsetService: registerMessageListener
,05-19 09:21:50.641  9787  9827 D HeadsetStateMachine: Disconnected process message: 70, size: 0
05-19 09:21:50.641  9787  9827 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@cbbb50a
,05-19 09:21:50.641  3511  3511 I Telecom : CallAudioManager: onBluetoothStateChange: no focus
,05-19 09:21:50.641  3511  3511 I Telecom : BluetoothManager : register MessageListener
05-19 09:21:50.641  3511  3511 D WifiNotificationController: SHOW_NOTI_MESSAGE : 17, visible : false, ssid : null, targetSSID : null, netId : -1, titleType : -1
05-19 09:21:50.641  3511  3511 D WifiNotificationController: showMaliciousHotspotDetectionNotification - MaliciousNetwork:null, visible:false
,05-19 09:21:50.651  4867  4880 D PdnController: Interface Changed p2p0 link down
,05-19 09:21:50.651  3511  3589 E GpsLocationProvider: No APN found to select.,
,05-19 09:21:50.651  3511  3852 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,05-19 09:21:50.651  3511  3528 I ActivityManager: Killing 9081:com.samsung.android.themestore/u0a68 (adj 15): DHA:empty #33
,05-19 09:21:50.661  3511  3852 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,05-19 09:21:50.681  3511  4407 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7d59db2 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cf9e5aa 4853:com.samsung.android.providers.context/u0a9}
05-19 09:21:50.681  9787  9787 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2) for masId0
,05-19 09:21:50.681  3511  3852 D WifiService: setWifiEnabled: true pid=9689, uid=10078
,05-19 09:21:50.701  4158  4174 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=17041470,extra=Bundle[mParcelledData.dataSize=84]
,05-19 09:21:50.701  4158  4158 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=17041470, samsung.notification.type=normal, samsung.people.package_name=android}]
05-19 09:21:50.701  3511  4343 D ActivityManager: cleanUpApplicationRecord -- 9081
05-19 09:21:50.701  4158  4158 I PeopleStripeService: PeopleNotificationReceiver:3
05-19 09:21:50.701  3511  3529 V AlarmManager:  remove PendingIntent] PendingIntent{9fad880: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:50.701  4158  4158 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
05-19 09:21:50.701  4158  4158 I PeopleDataManager: removeNotification
05-19 09:21:50.701  4158  4158 I NotificationParser: getNotiType:android,null
05-19 09:21:50.701  4158  4158 D PeopleDataManager: removeNotiInfo: id =17041470,packageName=android,isEdgeNotification=false,key=null,removeAll=false
05-19 09:21:50.701  4158  4158 D PeopleDataManager: removeNotiInfo =null
,05-19 09:21:50.701  3511  4343 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.themestore, Auto Run ON
,05-19 09:21:50.701  9787  9899 D BluetoothSocket: bindListen(): myUserId = 0
05-19 09:21:50.701  9787  9899 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,05-19 09:21:50.711  3511  3589 D libgps  : agps_ril_update_network_state: Waiting for IPC connection...
05-19 09:21:50.711  3511  3852 W ActivityManager: Permission Denial: getCurrentUser() from pid=9689, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-19 09:21:50.711  3511  3852 W WifiService: Failed getting userId using ActivityManagerNative
05-19 09:21:50.711  3511  3852 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9689, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-19 09:21:50.711  3511  3852 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-19 09:21:50.711  3511  3852 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
05-19 09:21:50.711  3511  3852 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
05-19 09:21:50.711  3511  3852 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
05-19 09:21:50.711  3511  3852 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
05-19 09:21:50.711  3511  3852 D SettingsProvider: isChangeAllowed() : name = wifi_on
05-19 09:21:50.711  3511  3852 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
05-19 09:21:50.711  3511  3857 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
05-19 09:21:50.711  3511  3857 D WifiBigDataLog: getJsonFormat() - feature : ONOF
05-19 09:21:50.711  3511  3860 D WifiController: [FCC]setFccChannel() is called !!!
05-19 09:21:50.711  3511  3860 D WifiStateMachine: setFccChannel: channel = 0
05-19 09:21:50.711  3511  3860 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
05-19 09:21:50.711  3511  3860 D SecContentProvider: insert(), uri = 2
,05-19 09:21:50.711  9787  9848 D A2dpStateMachine: getConnectedDevices : size=0
,05-19 09:21:50.711  9883  9883 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,05-19 09:21:50.711  9883  9883 D RelationGraph: garbageCollect()
,05-19 09:21:50.711  9787  9787 D BluetoothSocket: bindListen(): myUserId = 0
,05-19 09:21:50.711  9787  9787 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,05-19 09:21:50.711  9883  9883 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in com.samsung.android.email.provider rsrc of package com.samsung.android.email.provider
,05-19 09:21:50.721  3511  3984 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-19 09:21:50.721  9883  9883 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-19 09:21:50.721  9883  9883 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 09:21:50.721  9900  9900 E Zygote  : v2
05-19 09:21:50.721  9900  9900 I libpersona: KNOX_SDCARD checking this for 10004
05-19 09:21:50.721  9900  9900 I libpersona: KNOX_SDCARD not a persona
05-19 09:21:50.721  9900  9900 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-19 09:21:50.721  9900  9900 E Zygote  : accessInfo : 0
05-19 09:21:50.721  9900  9900 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.provider.badge 
,05-19 09:21:50.721  9883  9883 I InjectionManager: Inside getClassLibPath caller 
,05-19 09:21:50.731  3511  3982 I ActivityManager: Start proc 9900:com.sec.android.provider.badge/u0a4 for content provider com.sec.android.provider.badge/.BadgeProvider
,05-19 09:21:50.731  3511  3857 D WifiBigDataLog: init : 
,05-19 09:21:50.741  9883  9883 W System  : ClassLoader referenced unknown path: /system/priv-app/SecEmail_M/lib/arm64
,05-19 09:21:50.751  9787  9899 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,05-19 09:21:50.751  9787  9899 D BluetoothSdpJni: SDP Create record success - handle: 0
,05-19 09:21:50.761  9900  9900 D TimaKeyStoreProvider: TimaSignature is unavailable
05-19 09:21:50.761  9900  9900 D ActivityThread: Added TimaKeyStore provider
,05-19 09:21:50.761  9787  9787 D BluetoothSocket: bindListen(): myUserId = 0
05-19 09:21:50.761  9787  9787 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,05-19 09:21:50.781  3511  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c55eb9 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ae2af57 6554:com.enhance.gameservice/u0a111}
,05-19 09:21:50.781  9900  9900 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
05-19 09:21:50.781  9900  9900 D RelationGraph: garbageCollect()
,05-19 09:21:50.781  3511  3511 I ActivityManager: Killing 9125:com.samsung.android.scloud:contentsync/5009 (adj 15): DHA:empty #33
,05-19 09:21:50.801  3511  4185 V AlarmManager:  remove PendingIntent] PendingIntent{2fbe2fe: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:50.801  9787  9787 D ObexServerSockets: Succeed to create listening sockets 
05-19 09:21:50.801  9787  9787 D ObexServerSockets: startAccept()
,05-19 09:21:50.801  9883  9883 I BNRClientProivder, VERSION : 1.7.5: register - xml6 quick_backup : Email, QJ5JBlRnP9, com.samsung.android.email.provider.service.sCloudBNRService
,05-19 09:21:50.801  9787  9913 D ObexServerSockets: Accepting socket connection for masId0
05-19 09:21:50.801  9883  9883 I QBNRClientHelper: init SyncClientHelper : Email
,05-19 09:21:50.801  9900  9900 W ResourcesManager: getTopLevelResources: /system/priv-app/BadgeProvider_M/BadgeProvider_M.apk / 1.0 running in com.sec.android.provider.badge rsrc of package com.sec.android.provider.badge
,05-19 09:21:50.801  9787  9914 D ObexServerSockets: Accepting socket connection for masId0
,05-19 09:21:50.811  3511  3529 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-19 09:21:50.811  9900  9900 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-19 09:21:50.811  9900  9900 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 09:21:50.811  9787  9787 D BluetoothMapMasInstance: set MAP SDP message type : 1
,05-19 09:21:50.811  9787  9787 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
05-19 09:21:50.811  9787  9787 D BluetoothSdpJni: SDP Create record success - handle: 1
,05-19 09:21:50.811  3511  3528 D ActivityManager: cleanUpApplicationRecord -- 9125
05-19 09:21:50.811  3511  3528 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.scloud, Auto Run ON
05-19 09:21:50.811  9900  9900 I InjectionManager: Inside getClassLibPath caller 
,05-19 09:21:50.821  9900  9900 W System  : ClassLoader referenced unknown path: /system/priv-app/BadgeProvider_M/lib/arm64
,05-19 09:21:50.821  9900  9900 D BadgeProvider: onCreate
,05-19 09:21:50.821  9900  9900 D BadgeProvider: DatabaseHelper
,05-19 09:21:50.891  3511  3597 D ActivityManager:  getDeferredInfo final delay 300
,05-19 09:21:50.901  9915  9915 E Zygote  : v2
,05-19 09:21:50.901  9915  9915 I libpersona: KNOX_SDCARD checking this for 10117
05-19 09:21:50.901  9915  9915 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
05-19 09:21:50.901  9915  9915 I libpersona: KNOX_SDCARD not a persona
05-19 09:21:50.901  3511  3597 I ActivityManager: Start proc 9915:com.google.android.talk/u0a117 for broadcast-3 com.google.android.talk/com.google.android.apps.hangouts.service.GcmStateReceiver
,05-19 09:21:50.901  9915  9915 E Zygote  : accessInfo : 0
05-19 09:21:50.901  9915  9915 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.talk 
05-19 09:21:50.901  9900  9900 D InjectionManager: InjectionManager
05-19 09:21:50.901  9900  9900 D InjectionManager: fillFeatureStoreMap com.sec.android.provider.badge
,05-19 09:21:50.911  9900  9900 I InjectionManager: Constructor com.sec.android.provider.badge, Feature store :{}
05-19 09:21:50.911  9900  9900 I InjectionManager: featureStore :{}
,05-19 09:21:50.921  3511  4343 V AlarmManager:  remove PendingIntent] PendingIntent{2dd3a5f: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:50.921  3511  4449 V AlarmManager:  remove PendingIntent] PendingIntent{474fcac: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:50.921  9915  9915 D TimaKeyStoreProvider: TimaSignature is unavailable
05-19 09:21:50.921  9915  9915 D ActivityThread: Added TimaKeyStore provider
,05-19 09:21:50.931  3511  4070 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1248000  uid : 1000  pid : 3511  pkgName : BADGE_UPDATE@CPU_MIN@1
,05-19 09:21:50.941  3511  4407 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3d42d75 u0 com.google.android.gcm.DISCONNECTED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4af310a 9915:com.google.android.talk/u0a117}
,05-19 09:21:50.941  3511  4185 V AlarmManager:  remove PendingIntent] PendingIntent{7451d7b: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:50.941  3511  3984 D RCPManagerService: exchangeData() failure , invalid userId
,05-19 09:21:50.941  3511  3529 V AlarmManager:  remove PendingIntent] PendingIntent{f8b3798: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:50.941  9883  9883 D InjectionManager: InjectionManager
05-19 09:21:50.941  9883  9883 D InjectionManager: fillFeatureStoreMap com.samsung.android.email.provider
,05-19 09:21:50.941  9883  9883 I InjectionManager: Constructor com.samsung.android.email.provider, Feature store :{}
05-19 09:21:50.941  9883  9883 I InjectionManager: featureStore :{}
,05-19 09:21:50.951  9900  9910 D BaseReflect: null getOwnClass TEST
05-19 09:21:50.951  9900  9910 D MethodReflector: android.content.ContentResolver getClass TEST
05-19 09:21:50.951  3511  4459 V AlarmManager:  remove PendingIntent] PendingIntent{c72bf1: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:50.951  9900  9910 D BaseReflect: class android.content.ContentResolver isSupportClass TEST
,05-19 09:21:50.951  9900  9910 D BaseReflect: class android.content.ContentResolver getOwnClass TEST
05-19 09:21:50.951  9915  9915 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
05-19 09:21:50.951  9915  9915 D RelationGraph: garbageCollect()
,05-19 09:21:50.951  9915  9915 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.google.android.talk rsrc of package com.google.android.talk
,05-19 09:21:50.951  3511  3982 V AlarmManager:  remove PendingIntent] PendingIntent{19753d6: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:50.951  9915  9915 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
05-19 09:21:50.951  3511  4070 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-19 09:21:50.951  3511  6156 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:50.951  3511  4449 V AlarmManager:  remove PendingIntent] PendingIntent{67e1657: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:50.961  9915  9915 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 09:21:50.961  3511  3982 V AlarmManager:  remove PendingIntent] PendingIntent{cc83544: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:50.961  4145  4145 D CatchNotificationsService: Update badge
05-19 09:21:50.961  4299  4299 D Launcher.Model: reloadBadges entered.
,05-19 09:21:50.961  5868  5868 D BadgeManager: onChange
,05-19 09:21:50.971  9900  9925 D BadgeProvider: query, [selection] : null
05-19 09:21:50.971  3511  4198 V AlarmManager:  remove PendingIntent] PendingIntent{811962d: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:50.971  9915  9915 I InjectionManager: Inside getClassLibPath caller 
,05-19 09:21:50.971  9900  9912 D BadgeProvider: query, [selection] : null
,05-19 09:21:50.971  3511  4343 V AlarmManager:  remove PendingIntent] PendingIntent{41e6829: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:50.981  4299  4367 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.email.provider = 0
05-19 09:21:50.981  4299  4367 D BadgeCache: 1. updateBadgeCounts: com.android.mms = 0
05-19 09:21:50.981  4299  4367 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 1
05-19 09:21:50.981  4299  4367 D BadgeCache: 2. updateBadgeCounts: com.android.settings/.Settings = 1
05-19 09:21:50.981  4299  4367 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 1
05-19 09:21:50.981  4299  4367 D BadgeCache: 2. updateBadgeCounts: com.android.settings/.GridSettings = 1
05-19 09:21:50.981  4299  4367 D BadgeCache: 1. updateBadgeCounts: com.sec.android.app.samsungapps = 0
05-19 09:21:50.981  4299  4367 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.sm = 0
,05-19 09:21:50.981  9900  9910 D MethodReflector: notifyChange is called
05-19 09:21:50.981  9787  9929 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,05-19 09:21:50.981  4299  4299 D Launcher.Model: reloadBadges entered.
,05-19 09:21:50.981  9915  9915 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm64
05-19 09:21:50.981  9900  9910 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
05-19 09:21:50.981  9900  9910 D BadgeProvider: sendNotify, [notify] : null
05-19 09:21:50.981  5868  5868 D BadgeManager: onChange
05-19 09:21:50.981  9787  9929 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
05-19 09:21:50.981  9900  9910 D BadgeProvider: update, getCallingPackage() : com.samsung.android.email.provider
,05-19 09:21:50.981  9900  9910 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
05-19 09:21:50.981  9900  9910 D BadgeProvider: update, [uri.query] : null
05-19 09:21:50.981  9900  9910 D BadgeProvider: update, [BadgeCount] : badgecount=0
05-19 09:21:50.981  9900  9910 D BadgeProvider: update, [UpdateCount] : 1
,05-19 09:21:50.991  4145  4145 D CatchNotificationsService: Update badge
,05-19 09:21:51.001  3511  3528 V AlarmManager:  remove PendingIntent] PendingIntent{d6507ae: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:51.001  9900  9910 D BadgeProvider: query, [selection] : null
05-19 09:21:51.001  9900  9925 D BadgeProvider: query, [selection] : null
,05-19 09:21:51.001  9915  9915 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.google.android.talk rsrc of package com.google.android.talk
05-19 09:21:51.001  3511  3528 V AlarmManager:  remove PendingIntent] PendingIntent{aef794f: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:51.001  4299  4367 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.email.provider = 0
05-19 09:21:51.001  4299  4367 D BadgeCache: 1. updateBadgeCounts: com.android.mms = 0
05-19 09:21:51.001  4299  4367 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 1
05-19 09:21:51.001  4299  4367 D BadgeCache: 2. updateBadgeCounts: com.android.settings/.Settings = 1
05-19 09:21:51.001  4299  4367 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 1
05-19 09:21:51.001  4299  4367 D BadgeCache: 2. updateBadgeCounts: com.android.settings/.GridSettings = 1
05-19 09:21:51.001  4299  4367 D BadgeCache: 1. updateBadgeCounts: com.sec.android.app.samsungapps = 0
05-19 09:21:51.001  4299  4367 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.sm = 0
,05-19 09:21:51.011  3511  3852 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.011  3511  3852 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.011  3511  4422 V AlarmManager:  remove PendingIntent] PendingIntent{106e8dc: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:51.011  3511  3852 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.011  3511  3852 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.011  3511  3852 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.011  3511  3852 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.011  3511  3852 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.011  3511  3852 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.011  3511  3852 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.011  3511  3852 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.011  3511  3852 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.011  3511  3852 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
05-19 09:21:51.011  3511  3852 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.011  3511  3852 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.011  3511  3852 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-19 09:21:51.021  3511  3529 V AlarmManager:  remove PendingIntent] PendingIntent{10c5de5: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:51.021  3511  4198 V AlarmManager:  remove PendingIntent] PendingIntent{afdf0ba: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:51.021  3511  3982 V AlarmManager:  remove PendingIntent] PendingIntent{7545b6b: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:51.021  3511  3528 V AlarmManager:  remove PendingIntent] PendingIntent{287b6c8: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:51.031  3511  3984 V AlarmManager:  remove PendingIntent] PendingIntent{429f361: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:51.031  3511  4070 V AlarmManager:  remove PendingIntent] PendingIntent{c0a5e86: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:51.031  3511  3852 V AlarmManager:  remove PendingIntent] PendingIntent{adb4347: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:51.031  3511  4313 V AlarmManager:  remove PendingIntent] PendingIntent{dc57774: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:51.031  3511  4449 V AlarmManager:  remove PendingIntent] PendingIntent{f31649d: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:51.031  3511  4451 V AlarmManager:  remove PendingIntent] PendingIntent{31ddd12: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:51.031  3511  4422 V AlarmManager:  remove PendingIntent] PendingIntent{afecce3: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:51.041  3511  4343 V AlarmManager:  remove PendingIntent] PendingIntent{b7c96e0: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:51.041  3511  4847 V AlarmManager:  remove PendingIntent] PendingIntent{b44ad99: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:51.041  3511  4185 V AlarmManager:  remove PendingIntent] PendingIntent{678b85e: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:51.041  3511  4407 V AlarmManager:  remove PendingIntent] PendingIntent{47543f: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:51.041  3511  4422 V AlarmManager:  remove PendingIntent] PendingIntent{1c4410c: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:51.041  3511  4343 V AlarmManager:  remove PendingIntent] PendingIntent{7a98a55: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:51.051  3511  4847 V AlarmManager:  remove PendingIntent] PendingIntent{e13fc6a: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:51.051  3511  4185 V AlarmManager:  remove PendingIntent] PendingIntent{966f55b: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:51.051  3511  4451 V AlarmManager:  remove PendingIntent] PendingIntent{efa61f8: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:51.051  3511  4459 V AlarmManager:  remove PendingIntent] PendingIntent{84576d1: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:51.051  3511  3529 V AlarmManager:  remove PendingIntent] PendingIntent{66d7536: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:51.051  3511  4198 V AlarmManager:  remove PendingIntent] PendingIntent{4158c37: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:51.051  3511  3982 V AlarmManager:  remove PendingIntent] PendingIntent{76fa5a4: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:51.051  3511  3528 V AlarmManager:  remove PendingIntent] PendingIntent{fd9af0d: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:51.051  3511  3984 V AlarmManager:  remove PendingIntent] PendingIntent{413aec2: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:51.061  3511  4070 V AlarmManager:  remove PendingIntent] PendingIntent{7acb4d3: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:51.061  3511  4847 V AlarmManager:  remove PendingIntent] PendingIntent{d83cb2f: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:51.061  3511  3528 V AlarmManager:  remove PendingIntent] PendingIntent{e60053c: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:51.071  3511  4422 V AlarmManager:  remove PendingIntent] PendingIntent{8e2b2c5: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:51.071  3511  4198 V AlarmManager:  remove PendingIntent] PendingIntent{45c541a: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:51.071  3511  3982 V AlarmManager:  remove PendingIntent] PendingIntent{30beb4b: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:51.071  3511  3528 V AlarmManager:  remove PendingIntent] PendingIntent{4c63928: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:51.071  3511  3984 V AlarmManager:  remove PendingIntent] PendingIntent{ac0b641: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:51.081  3511  4422 V AlarmManager:  remove PendingIntent] PendingIntent{2db97e6: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:51.081  9915  9915 I Babel_telephony: TeleModule.onApplicationCreate
,05-19 09:21:51.081  3511  4198 V AlarmManager:  remove PendingIntent] PendingIntent{1abf127: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:51.081  3511  4449 V AlarmManager:  remove PendingIntent] PendingIntent{4d9bfd4: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:51.081  9915  9945 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
05-19 09:21:51.081  9915  9945 I Babel_SMS: MmsConfig.loadMmsSettings
,05-19 09:21:51.081  9915  9945 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/uaprof, mUaProfUrl=http://wap.samsungmobile.com/uaprof/uaprof.rdf
05-19 09:21:51.081  9915  9945 I Babel_SMS: MmsConfig.loadFromDatabase
,05-19 09:21:51.081  3511  3984 V AlarmManager:  remove PendingIntent] PendingIntent{b21757d: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:51.091  3511  3529 V AlarmManager:  remove PendingIntent] PendingIntent{ab94c72: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:51.091  3511  4847 V AlarmManager:  remove PendingIntent] PendingIntent{5fd0540: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:51.091  3511  3982 V AlarmManager:  remove PendingIntent] PendingIntent{3d4ec79: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:51.101  3511  4407 V AlarmManager:  remove PendingIntent] PendingIntent{4bbdbe: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:51.101  9915  9945 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
05-19 09:21:51.101  9915  9945 I Babel_SMS: MmsConfig.loadFromResources
,05-19 09:21:51.101  3511  4422 V AlarmManager:  remove PendingIntent] PendingIntent{303de1f: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:21:51.101  9915  9945 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,05-19 09:21:51.101  9915  9945 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/uaprof, mUaProfUrl=http://wap.samsungmobile.com/uaprof/uaprof.rdf
,05-19 09:21:51.101  3511  3852 V AlarmManager:  remove PendingIntent] PendingIntent{14d356c: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:51.101  3511  4313 V AlarmManager:  remove PendingIntent] PendingIntent{1aed735: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:51.101  3511  4449 V AlarmManager:  remove PendingIntent] PendingIntent{501f7ca: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:51.111  9915  9915 I Babel_Crash: Startup - clean
,05-19 09:21:51.111  3511  4407 V AlarmManager:  remove PendingIntent] PendingIntent{b923d3b: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:51.111  3511  4422 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.SmsReceiver newState = 2 callingPackage = 10117
,05-19 09:21:51.111  3511  3529 V AlarmManager:  remove PendingIntent] PendingIntent{28e3c58: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:51.111  3511  4847 V AlarmManager:  remove PendingIntent] PendingIntent{102b1b1: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:51.111  3511  3982 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.MmsWapPushReceiver newState = 2 callingPackage = 10117
,05-19 09:21:51.111  3511  3528 V AlarmManager:  remove PendingIntent] PendingIntent{2fc696: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:51.111  3511  3984 V AlarmManager:  remove PendingIntent] PendingIntent{dd7217: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:51.121  3511  3529 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.AbortSmsReceiver newState = 2 callingPackage = 10117
05-19 09:21:51.121  3511  3852 V AlarmManager:  remove PendingIntent] PendingIntent{bd6c604: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:51.121  3511  4313 V AlarmManager:  remove PendingIntent] PendingIntent{5dfb7ed: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:51.121  3511  3528 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver newState = 2 callingPackage = 10117
,05-19 09:21:51.121  3511  4451 V AlarmManager:  remove PendingIntent] PendingIntent{899b622: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:51.121  3511  3984 V AlarmManager:  remove PendingIntent] PendingIntent{f3d18b3: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:51.121  3511  4459 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.service.NoConfirmationSmsSendService newState = 1 callingPackage = 10117
05-19 09:21:51.121  3511  4198 V AlarmManager:  remove PendingIntent] PendingIntent{7fc3e70: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:51.121  3511  4847 V AlarmManager:  remove PendingIntent] PendingIntent{c0ce5e9: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:51.121  3511  3529 V AlarmManager:  remove PendingIntent] PendingIntent{ac1126e: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:51.131  3511  4407 V AlarmManager:  remove PendingIntent] PendingIntent{6e68d0f: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:51.131  3511  4070 V AlarmManager:  remove PendingIntent] PendingIntent{7bed19c: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:51.131  9915  9915 I Babel_Prime: startMemoryMonitor
05-19 09:21:51.131  9915  9915 I Babel_Prime: isMemoryEnabled=false
,05-19 09:21:51.131  9915  9915 I Babel_Prime: isTimerEnabled=true
05-19 09:21:51.131  3511  4198 V AlarmManager:  remove PendingIntent] PendingIntent{ac4f7a5: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:51.131  3511  4459 V AlarmManager:  remove PendingIntent] PendingIntent{7efe77a: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:51.131  3511  4185 V AlarmManager:  remove PendingIntent] PendingIntent{c08eb2b: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:51.131  3511  4451 V AlarmManager:  remove PendingIntent] PendingIntent{5b56b88: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:51.131  3511  3984 V AlarmManager:  remove PendingIntent] PendingIntent{8326921: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:51.131  3511  4343 V AlarmManager:  remove PendingIntent] PendingIntent{a050146: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:51.141  9915  9915 D InjectionManager: InjectionManager
05-19 09:21:51.141  9915  9915 D InjectionManager: fillFeatureStoreMap com.google.android.talk
,05-19 09:21:51.141  9915  9915 I InjectionManager: Constructor com.google.android.talk, Feature store :{}
05-19 09:21:51.141  9915  9915 I InjectionManager: featureStore :{}
,05-19 09:21:51.151  3511  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ca90f07 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ae2af57 6554:com.enhance.gameservice/u0a111}
,05-19 09:21:51.161  3511  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cf9b834 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8ab765d 9689:com.rockwellautomation.thalitest/u0a78}
,05-19 09:21:51.161  3511  4451 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.161  3511  4451 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.161  3511  4451 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.161  3511  4451 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.161  3511  4451 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.161  3511  4451 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.161  3511  4451 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.161  3511  4451 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.161  3511  4451 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.161  3511  4451 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.161  3511  4451 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.161  3511  4451 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
05-19 09:21:51.161  3511  4451 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.161  3511  4451 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.161  3511  4451 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-19 09:21:51.171  3511  4407 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cf9b834 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7c9839a 3511:system/1000}
,05-19 09:21:51.171  3158  3678 D Netd    : Iface wlan0 link down
05-19 09:21:51.171  3511  3604 D Tethering: interfaceLinkStateChanged wlan0, false
05-19 09:21:51.171  9915  9915 D Babel   : onCreate: Shutdown runnable posted in onCreate with a delay of 5000 ms.
05-19 09:21:51.171  3511  3604 D Tethering: interfaceStatusChanged wlan0, false
,05-19 09:21:51.181  4867  4881 D PdnController: Interface Changed wlan0 link down
05-19 09:21:51.181  4867  4881 D PdnController: Removed Interface [wlan0] For Network [1]
,05-19 09:21:51.181  3511  3604 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-19 09:21:51.181  4867  4881 D PdnController: CONNECTIVITY_ACTION: networkType 1 isConnected false
05-19 09:21:51.181  4867  4881 D PdnController: isSuspended [false] networktype [1]
,05-19 09:21:51.181  3511  3604 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.181  4867  4881 D PdnController: isPdnUp  [false] networktype [1]
05-19 09:21:51.181  4867  4881 D PdnController: Ignore Notifying Same Result to LocalIP Registrants!
05-19 09:21:51.181  9915  9915 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in com.google.android.talk rsrc of package com.google.android.gms
,05-19 09:21:51.181  3511  3511 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cf9b834 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{19a4389 4618:com.google.android.gms/u0a21}
,05-19 09:21:51.181  4618  9898 D MdnsClient: Multicast lock held. Releasing
,05-19 09:21:51.181  4618  4618 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,05-19 09:21:51.191  4618  5653 I iu.UploadsManager: num queued entries: 0
05-19 09:21:51.191  4618  5653 I iu.UploadsManager: num updated entries: 0
,05-19 09:21:51.191  4618  5653 I iu.SyncManager: NEXT; no task
05-19 09:21:51.191  9915  9915 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 09:21:51.191  9915  9915 I InjectionManager: Inside getClassLibPath caller 
,05-19 09:21:51.191  3511  3597 D ActivityManager:  getDeferredInfo final delay 300
,05-19 09:21:51.201  9915  9915 W System  : ClassLoader referenced unknown path: /system/priv-app/GmsCore/lib/arm64
,05-19 09:21:51.201  3511  4070 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cf9b834 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{19a4389 4618:com.google.android.gms/u0a21}
,05-19 09:21:51.201  3511  4070 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cf9b834 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dc64001 4328:com.google.android.gms.persistent/u0a21}
,05-19 09:21:51.211  9689  9775 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,05-19 09:21:51.211  3511  4407 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,05-19 09:21:51.211  3511  4407 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,05-19 09:21:51.211  3511  4407 D WifiService: setWifiEnabled: true pid=9689, uid=10078
05-19 09:21:51.211  3511  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cf9b834 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5ae1b59 9138:com.osp.app.signin/u0a44}
,05-19 09:21:51.211  3511  4407 W ActivityManager: Permission Denial: getCurrentUser() from pid=9689, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-19 09:21:51.211  3511  4407 W WifiService: Failed getting userId using ActivityManagerNative
05-19 09:21:51.211  3511  4407 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9689, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-19 09:21:51.211  3511  4407 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-19 09:21:51.211  3511  4407 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
05-19 09:21:51.211  3511  4407 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
05-19 09:21:51.211  3511  4407 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
05-19 09:21:51.211  3511  4407 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
05-19 09:21:51.211  3511  4407 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
05-19 09:21:51.211  3511  4407 D SettingsProvider: isChangeAllowed() : name = wifi_on
05-19 09:21:51.211  3511  3860 D WifiStateMachine: setFccChannel: channel = 0
05-19 09:21:51.211  3511  3860 D WifiController: [FCC]setFccChannel() is called !!!
05-19 09:21:51.211  3511  3860 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
,05-19 09:21:51.211  3511  3857 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,05-19 09:21:51.211  9138  9138 I SA      : [DM] init START
05-19 09:21:51.211  3511  3857 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,05-19 09:21:51.211  3511  3857 D WifiBigDataLog: init : 
,05-19 09:21:51.221  9138  9138 I SA      : [DM] This device is not a Vodafone
,05-19 09:21:51.221  9138  9138 W ResourceType: No package identifier when getting value for resource number 0x00000000
,05-19 09:21:51.221  9138  9138 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 09:21:51.221  9138  9138 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 09:21:51.221  9138  9138 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 09:21:51.221  9138  9138 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 09:21:51.221  9138  9138 W ResourceType: No package identifier when getting value for resource number 0x00000000
,05-19 09:21:51.221  9138  9138 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 09:21:51.221  9138  9138 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 09:21:51.221  9138  9138 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 09:21:51.221  9138  9138 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 09:21:51.221  9138  9138 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 09:21:51.221  9138  9138 W ResourceType: Failure getting entry for 0x7f0a0002 (t=9 e=2) (error -75)
05-19 09:21:51.221  9138  9138 W ResourceType: No package identifier when getting value for resource number 0x00000000
,05-19 09:21:51.221  9138  9138 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 09:21:51.221  9138  9138 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 09:21:51.221  9138  9138 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 09:21:51.221  9138  9138 W ResourceType: No package identifier when getting value for resource number 0x00000000
,05-19 09:21:51.221  9138  9138 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 09:21:51.221  9138  9138 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 09:21:51.221  9138  9138 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 09:21:51.221  9138  9138 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 09:21:51.221  9138  9138 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 09:21:51.221  9138  9138 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 09:21:51.221  9138  9138 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 09:21:51.221  9138  9138 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 09:21:51.221  9138  9138 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 09:21:51.221  9138  9138 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 09:21:51.221  9138  9138 W ResourceType: No package identifier when getting value for resource number 0x00000000
,05-19 09:21:51.231  9138  9138 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 09:21:51.231  4115  4115 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
05-19 09:21:51.231  9138  9138 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 09:21:51.231  9138  9138 W ResourceType: Failure getting entry for 0x7f0a0005 (t=9 e=5) (error -75)
05-19 09:21:51.231  9138  9138 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 09:21:51.231  9138  9138 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 09:21:51.231  9138  9138 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 09:21:51.231  9138  9138 W ResourceType: No package identifier when getting value for resource number 0x00000000
,05-19 09:21:51.231  9138  9138 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 09:21:51.231  9138  9138 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 09:21:51.231  9138  9138 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 09:21:51.231  9138  9138 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 09:21:51.231  9138  9138 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 09:21:51.231  9138  9138 W ResourceType: No package identifier when getting value for resource number 0x00000000
,05-19 09:21:51.231  9138  9138 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 09:21:51.231  9138  9138 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 09:21:51.231  9138  9138 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 09:21:51.231  9138  9138 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 09:21:51.231  9138  9138 W ResourceType: No package identifier when getting value for resource number 0x00000000
,05-19 09:21:51.231  9138  9138 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 09:21:51.231  9138  9138 W ResourceType: No package identifier when getting value for resource number 0x00000000
,05-19 09:21:51.231  9138  9138 I SA      : support phone number id : true
05-19 09:21:51.231  9138  9138 I SA      : [DM] Supports Ref Jpn : true
,05-19 09:21:51.231  9138  9138 I SA      : [DM] init END
,05-19 09:21:51.231  9138  9138 I SA      : [OR] onReceive log=[SA = 2.2.02-12 V = 23 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = pl_PL CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hero2lte P = hero2ltexx I = MMB29K M = SM-G935F OKLEFT false DIS MMB29K.G935FXXU1BPJG PSS = 5.460694751064798  ]
,05-19 09:21:51.231  9138  9138 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,05-19 09:21:51.231  9138  9138 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,05-19 09:21:51.231  9138  9138 I SA      : [SLFUCHKMGR] constructor called
,05-19 09:21:51.241  9138  9138 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
05-19 09:21:51.241  9138  9138 I SA      : [OR] == isSIMCardReady false ==
,05-19 09:21:51.241  9138  9138 I SA      : [SCU] == networkStateCheck == false
05-19 09:21:51.241  9138  9138 I SA      : [OR] onReceive END
,05-19 09:21:51.241  9915  9915 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,05-19 09:21:51.251  3511  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{74cf31e u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8ab765d 9689:com.rockwellautomation.thalitest/u0a78}
,05-19 09:21:51.251  3511  3529 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.251  3511  3529 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.251  3511  3529 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.251  3511  3529 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.251  3511  3529 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.251  3511  3529 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.251  3511  3529 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.251  3511  3529 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.251  3511  3529 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.251  3511  3529 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.251  3511  3529 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.251  3511  3529 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
05-19 09:21:51.251  3511  3529 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.251  3511  3529 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.251  3511  3529 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-19 09:21:51.261  9915  9915 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,05-19 09:21:51.261  3511  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{50ad7ff u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cf9e5aa 4853:com.samsung.android.providers.context/u0a9}
,05-19 09:21:51.261  3511  3984 V AlarmManager:  remove PendingIntent] PendingIntent{f3ef51b: PendingIntentRecord{a5ec6b8 com.google.android.talk startService}}
,05-19 09:21:51.261  3511  4451 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{536dc91 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cf9e5aa 4853:com.samsung.android.providers.context/u0a9}
,05-19 09:21:51.271  9915  9915 D Babel   : Idle: Shutdown runnable posted in release with a delay of 5000 ms.
,05-19 09:21:51.331  3511  3857 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,05-19 09:21:51.331  3511  3511 D WifiNotificationController: SHOW_NOTI_MESSAGE : 9, visible : false, ssid : <unknown ssid>, targetSSID : null, netId : -1, titleType : -1
,05-19 09:21:51.331  4158  4169 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=17041883,extra=Bundle[mParcelledData.dataSize=84]
05-19 09:21:51.331  3511  3511 D WifiNotificationController: SHOW_NOTI_MESSAGE : 13, visible : false, ssid : <unknown ssid>, targetSSID : null, netId : -1, titleType : 0
05-19 09:21:51.331  4158  4158 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=17041883, samsung.notification.type=normal, samsung.people.package_name=android}]
05-19 09:21:51.331  3511  3511 D WifiNotificationController: showCaptivePortalDisabledStatus with ssid/visible/title:null/false/0
05-19 09:21:51.331  4158  4158 I PeopleStripeService: PeopleNotificationReceiver:3
05-19 09:21:51.331  4158  4174 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=17041473,extra=Bundle[mParcelledData.dataSize=84]
05-19 09:21:51.331  4158  4158 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
05-19 09:21:51.331  4158  4158 I PeopleDataManager: removeNotification
05-19 09:21:51.331  4158  4158 I NotificationParser: getNotiType:android,null
05-19 09:21:51.331  4158  4158 D PeopleDataManager: removeNotiInfo: id =17041883,packageName=android,isEdgeNotification=false,key=null,removeAll=false
05-19 09:21:51.331  4158  4158 D PeopleDataManager: removeNotiInfo =null
05-19 09:21:51.331  4158  4158 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=17041473, samsung.notification.type=normal, samsung.people.package_name=android}]
05-19 09:21:51.331  4158  4158 I PeopleStripeService: PeopleNotificationReceiver:3
05-19 09:21:51.331  4158  4158 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
05-19 09:21:51.331  4158  4158 I PeopleDataManager: removeNotification
05-19 09:21:51.331  4158  4158 I NotificationParser: getNotiType:android,null
05-19 09:21:51.331  4158  4158 D PeopleDataManager: removeNotiInfo: id =17041473,packageName=android,isEdgeNotification=false,key=null,removeAll=false
05-19 09:21:51.331  4158  4158 D PeopleDataManager: removeNotiInfo =null
,05-19 09:21:51.331  3511  3511 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
05-19 09:21:51.331  3511  3511 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
05-19 09:21:51.331  3511  3861 D HS20StateMachine: WIFI_STATE_DISABLED
05-19 09:21:51.331  3511  3861 D HS20StateMachine: CMD_HOTSPOT20_DISABLE
05-19 09:21:51.331  3511  3861 D HS20StateMachine: enter : DisablingState
05-19 09:21:51.331  3511  3864 I WifiHs20Service: Message received 5011
05-19 09:21:51.331  3511  3863 D HS20SubscriptionManager: Received CMD_RELEASE_TLS, flag=1
,05-19 09:21:51.331  3939  4163 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
05-19 09:21:51.331  3511  3511 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
05-19 09:21:51.331  3511  3868 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
05-19 09:21:51.331  3939  3939 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,05-19 09:21:51.331  3939  3939 I HotspotTile: Provider is not defined returning false
05-19 09:21:51.331  3939  3939 D HotspotTile: onReceive : 1, 0
,05-19 09:21:51.331  3511  3861 D HS20StateMachine: enter : DisabledState
,05-19 09:21:51.341  4287  4298 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,05-19 09:21:51.341  4287  4298 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,05-19 09:21:51.341  3511  3868 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,05-19 09:21:51.341  9689  9689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-19 09:21:51.341  4328  5111 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,05-19 09:21:51.341  3511  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8b647f6 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8ab765d 9689:com.rockwellautomation.thalitest/u0a78}
,05-19 09:21:51.341  3511  4313 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.341  3511  4313 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.341  3511  4313 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.341  3511  4313 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.341  3511  4313 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.341  3511  4313 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.341  3511  4313 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.341  3511  4313 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.341  3511  4313 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.341  3511  4313 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.341  3511  4313 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.341  3511  4313 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
05-19 09:21:51.341  3511  4313 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.341  3511  4313 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.341  3511  4313 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-19 09:21:51.491  3511  3597 D ActivityManager:  getDeferredInfo final delay 0
,05-19 09:21:51.511  9957  9957 E Zygote  : v2
05-19 09:21:51.511  9957  9957 I libpersona: KNOX_SDCARD checking this for 1000
05-19 09:21:51.511  9957  9957 I libpersona: KNOX_SDCARD not a persona
,05-19 09:21:51.511  3511  3597 I ActivityManager: Start proc 9957:com.sec.android.diagmonagent/1000 for broadcast-5 com.sec.android.diagmonagent/.DiagMonConnectivityChangeReciever
05-19 09:21:51.511  9957  9957 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-19 09:21:51.511  9957  9957 E Zygote  : accessInfo : 0
,05-19 09:21:51.531  3511  3857 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
05-19 09:21:51.531  3511  3857 E WifiHW  : ##################### set firmware type 0 #####################
,05-19 09:21:51.531  3158  3685 I WifiHW  : wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
,05-19 09:21:51.541  3158  3685 I WifiHW  : module is semco
05-19 09:21:51.541  3158  3685 E WifiHW  : ==========[WIFI] SEMCO MODULE ===========
05-19 09:21:51.541  3158  3685 I WifiHW  : wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
05-19 09:21:51.541  3158  3685 E WifiHW  : TEMP_FAILURE_RETRY complete
05-19 09:21:51.541  3158  3685 D SoftapController: Softap fwReload - Ok
,05-19 09:21:51.541  3158  3685 D CommandListener: Setting iface cfg
05-19 09:21:51.541  3158  3685 D CommandListener: Trying to bring down wlan0
,05-19 09:21:51.541  3158  3685 D CommandListener: Clearing all IP addresses on wlan0
,05-19 09:21:51.541  9957  9957 D TimaKeyStoreProvider: TimaSignature is unavailable
05-19 09:21:51.541  9957  9957 D ActivityThread: Added TimaKeyStore provider
,05-19 09:21:51.541  3511  3857 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,05-19 09:21:51.541  3511  3857 D wifi    : Can not initialize the vendor function pointer table
05-19 09:21:51.541  3511  3857 E WifiNative-HAL: Could not start hal
05-19 09:21:51.541  3511  3857 E WifiStateMachine: Failed to start HAL
,05-19 09:21:51.551  3511  3857 E WifiHW  : supplicant_name : p2p_supplicant
,05-19 09:21:51.561  3511  4459 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{c55eb9 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dcdc7f7 9957:com.sec.android.diagmonagent/1000}
,05-19 09:21:51.591  9957  9957 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
05-19 09:21:51.591  9957  9957 D RelationGraph: garbageCollect()
,05-19 09:21:51.591  9957  9957 W ResourcesManager: getTopLevelResources: /system/priv-app/DiagMonAgent/DiagMonAgent.apk / 1.0 running in com.sec.android.diagmonagent rsrc of package com.sec.android.diagmonagent
,05-19 09:21:51.591  3511  4343 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-19 09:21:51.591  9957  9957 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-19 09:21:51.601  9957  9957 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 09:21:51.601  9957  9957 I InjectionManager: Inside getClassLibPath caller 
,05-19 09:21:51.611  9957  9957 W System  : ClassLoader referenced unknown path: /system/priv-app/DiagMonAgent/lib/arm64
,05-19 09:21:51.631  9957  9957 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,05-19 09:21:51.651  3511  3857 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,05-19 09:21:51.651  3511  3511 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
05-19 09:21:51.651  3511  3511 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
,05-19 09:21:51.651  3511  3864 I WifiHs20Service: Message received 5011
,05-19 09:21:51.661  3511  3868 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,05-19 09:21:51.661  3511  3511 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
05-19 09:21:51.661  3939  4163 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-19 09:21:51.661  3939  3939 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,05-19 09:21:51.661  4287  4297 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
05-19 09:21:51.661  4287  4297 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
05-19 09:21:51.661  3939  3939 I HotspotTile: Provider is not defined returning false
05-19 09:21:51.661  3511  3868 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,05-19 09:21:51.661  3939  3939 D HotspotTile: onReceive : 2, 0
,05-19 09:21:51.671  9689  9689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-19 09:21:51.681  3511  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3959664 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8ab765d 9689:com.rockwellautomation.thalitest/u0a78}
,05-19 09:21:51.681  3511  4422 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-19 09:21:51.681  3511  4422 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.681  3511  4422 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.681  3511  4422 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.681  3511  4422 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.681  3511  4422 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.681  3511  4422 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.681  3511  4422 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.681  3511  4422 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-19 09:21:51.681  3511  4422 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.681  3511  4422 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.681  3511  4422 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
05-19 09:21:51.681  3511  4422 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.681  3511  4422 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:51.681  3511  4422 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-19 09:21:51.711  3511  3589 D libgps  : agps_ril_update_network_state: Waiting for IPC connection - timeout
,05-19 09:21:51.711  3511  3589 E libgps  : LIBGPS: Cannot communicate (write) with a GPSD
05-19 09:21:51.711  3511  3589 E libgps  : IPC Communication Error, ../../../../tmp/14982990_270314/allPartners/os/android/gps_interface/gpsi_client/GpsiClient.cpp:1710 agps_ril_update_network_state
05-19 09:21:51.711  3511  3589 D libgps  : agps_ril_update_network_availability: Waiting for IPC connection...
,05-19 09:21:51.711  9689  9775 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,05-19 09:21:51.711  3511  4185 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,05-19 09:21:51.721  9957  9957 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,05-19 09:21:51.721  3511  4185 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,05-19 09:21:51.721  9969  9969 I FIPS_bssl: FIPS approved mode (1) | 9969 | /system/bin/wpa_supplicant
05-19 09:21:51.721  3511  4185 D WifiService: setWifiEnabled: true pid=9689, uid=10078
05-19 09:21:51.721  3511  4185 W ActivityManager: Permission Denial: getCurrentUser() from pid=9689, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
,05-19 09:21:51.721  3511  4185 W WifiService: Failed getting userId using ActivityManagerNative
05-19 09:21:51.721  3511  4185 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9689, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-19 09:21:51.721  3511  4185 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-19 09:21:51.721  3511  4185 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
05-19 09:21:51.721  3511  4185 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
05-19 09:21:51.721  3511  4185 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
05-19 09:21:51.721  3511  4185 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
,05-19 09:21:51.721  3511  4185 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
05-19 09:21:51.721  3511  4185 D SettingsProvider: isChangeAllowed() : name = wifi_on
05-19 09:21:51.721  3511  3860 D WifiStateMachine: setFccChannel: channel = 0
05-19 09:21:51.721  3511  3860 D WifiController: [FCC]setFccChannel() is called !!!
05-19 09:21:51.721  3511  3860 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
,05-19 09:21:51.721  9969  9969 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
05-19 09:21:51.721  9969  9969 I wpa_supplicant: Successfully initialized wpa_supplicant
05-19 09:21:51.721  9969  9969 I wpa_supplicant: set_csc_config : ifname(wlan0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x20000), vendorssid_list()
,05-19 09:21:51.721  9969  9969 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,05-19 09:21:51.721  9957  9957 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(72/onCreate)] DiagMon DM Application Start !
,05-19 09:21:51.721  9957  9957 D InjectionManager: InjectionManager
05-19 09:21:51.721  9957  9957 D InjectionManager: fillFeatureStoreMap com.sec.android.diagmonagent
05-19 09:21:51.721  9957  9957 I InjectionManager: Constructor com.sec.android.diagmonagent, Feature store :{}
05-19 09:21:51.721  9957  9957 I InjectionManager: featureStore :{}
,05-19 09:21:51.721  9957  9957 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,05-19 09:21:51.721  9957  9957 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
05-19 09:21:51.721  9957  9957 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
05-19 09:21:51.721  9957  9957 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,05-19 09:21:51.721  3511  4407 D ActivityManager:  getDeferredInfo final delay 300
,05-19 09:21:51.731  3511  4407 I ActivityManager: Killing 8792:com.android.providers.calendar/u0a50 (adj 15): DHA:empty #33
,05-19 09:21:51.741  9969  9969 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,05-19 09:21:51.741  3018  3018 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 9969
,05-19 09:21:51.741  3018  3018 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
05-19 09:21:51.741  9969  9969 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
05-19 09:21:51.741  9969  9969 I wpa_supplicant: ssSupport state is = 1
05-19 09:21:51.741  9969  9969 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
05-19 09:21:51.741  9969  9969 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
05-19 09:21:51.741  3018  3018 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 9969
05-19 09:21:51.741  3018  3018 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x00000106
,05-19 09:21:51.751  3511  4459 D ActivityManager: cleanUpApplicationRecord -- 8792
,05-19 09:21:51.751  3511  4459 D ActivityManager: isAutoRunBlockedApp:: com.android.providers.calendar, Auto Run ON
,05-19 09:21:51.751  9969  9969 I SecureStorage: [INFO]: SPID(0x00000005)ss_id will be loaded by secure_storage_daemon: /system/bin/wpa_supplicant
,05-19 09:21:52.031  3018  3018 I SecureStorage: [INFO]: SPID(0x00000005)Secure Storage Daemon finished processing with result: 0
05-19 09:21:52.031  9969  9969 I SecureStorage: [INFO]: SPID(0x00000005)Processing data has been completed
,05-19 09:21:52.041  9969  9969 I wpa_supplicant: Ctrl_iface: loading system cred
05-19 09:21:52.041  9969  9969 I SecureStorage: [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,05-19 09:21:52.061  3511  3597 D ActivityManager:  getDeferredInfo final delay 0
,05-19 09:21:52.061  9969  9969 I SecureStorage: [INFO]: SPID(0x00000005)This device supports Secure Storage
05-19 09:21:52.061  3018  3018 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 9969
05-19 09:21:52.061  3018  3018 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
05-19 09:21:52.061  9969  9969 I SecureStorage: [INFO]: SPID(0x00000005)SS Daemon is running
05-19 09:21:52.061  9969  9969 I wpa_supplicant: ssSupport state is = 1
,05-19 09:21:52.061  9969  9969 I wpa_supplicant: Blacklist: Clear (all) 
,05-19 09:21:52.061  9969  9969 E wpa_supplicant: getSavedIMSI cannot open /data/misc/radio/kmem: No such file or directory
05-19 09:21:52.061  9969  9969 I wpa_supplicant: [getIMSI]: sim_num 0
,05-19 09:21:52.071  9969  9969 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,05-19 09:21:52.081  9972  9972 E Zygote  : v2
05-19 09:21:52.081  9972  9972 I libpersona: KNOX_SDCARD checking this for 1000
05-19 09:21:52.081  9972  9972 I libpersona: KNOX_SDCARD not a persona
,05-19 09:21:52.081  9972  9972 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
05-19 09:21:52.081  3511  3597 I ActivityManager: Start proc 9972:com.sec.knox.switcher/1000 for broadcast-5 com.sec.knox.switcher/.knoxusage.KnoxUsageReceiver
,05-19 09:21:52.081  9972  9972 E Zygote  : accessInfo : 0
,05-19 09:21:52.101  9972  9972 D TimaKeyStoreProvider: TimaSignature is unavailable
05-19 09:21:52.101  9972  9972 D ActivityThread: Added TimaKeyStore provider
,05-19 09:21:52.111  3511  3852 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{c55eb9 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fdbb0cd 9972:com.sec.knox.switcher/1000}
,05-19 09:21:52.111  9972  9972 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,05-19 09:21:52.111  9972  9972 D RelationGraph: garbageCollect()
,05-19 09:21:52.121  9972  9972 W ResourcesManager: getTopLevelResources: /system/app/KnoxSwitcher/KnoxSwitcher.apk / 1.0 running in com.sec.knox.switcher rsrc of package com.sec.knox.switcher
,05-19 09:21:52.121  3511  4422 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-19 09:21:52.121  9972  9972 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-19 09:21:52.121  9972  9972 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 09:21:52.121  9972  9972 I InjectionManager: Inside getClassLibPath caller 
,05-19 09:21:52.131  9972  9972 W System  : ClassLoader referenced unknown path: /system/app/KnoxSwitcher/lib/arm64
,05-19 09:21:52.131  9972  9972 D KnoxUsageDB: getInstance - KnoxUsageDBHelper
05-19 09:21:52.131  9972  9972 D KnoxUsageDB: null == mDbHelperInstance - KnoxUsageDBHelper
,05-19 09:21:52.131  9972  9972 D InjectionManager: InjectionManager
05-19 09:21:52.131  9972  9972 D InjectionManager: fillFeatureStoreMap com.sec.knox.switcher
,05-19 09:21:52.131  9972  9972 I InjectionManager: Constructor com.sec.knox.switcher, Feature store :{}
05-19 09:21:52.131  9972  9972 I InjectionManager: featureStore :{}
,05-19 09:21:52.131  9972  9972 I usagelog: received in receiver
05-19 09:21:52.131  9972  9972 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
,05-19 09:21:52.141  9972  9972 I KnoxUsageLogPro: premStatus:2
,05-19 09:21:52.141  9972  9972 I KnoxUsageLogPro: isEulaShown : false
05-19 09:21:52.141  9972  9972 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,05-19 09:21:52.141  3511  4185 D ActivityManager:  getDeferredInfo final delay 0
,05-19 09:21:52.151  9984  9984 E Zygote  : v2
05-19 09:21:52.151  9984  9984 I libpersona: KNOX_SDCARD checking this for 10142
05-19 09:21:52.151  9984  9984 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
05-19 09:21:52.151  9984  9984 I libpersona: KNOX_SDCARD not a persona
,05-19 09:21:52.161  9984  9984 E Zygote  : accessInfo : 0
05-19 09:21:52.161  9984  9984 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.sm.policy 
05-19 09:21:52.161  3511  4185 I ActivityManager: Start proc 9984:com.samsung.android.sm.policy/u0a142 for broadcast-5 com.samsung.android.sm.policy/.PolicyBroadCastReceiver
,05-19 09:21:52.161  3511  4185 I ActivityManager: Killing 9155:com.samsung.android.coreapps/5011 (adj 15): DHA:empty #33
,05-19 09:21:52.181  9984  9984 D TimaKeyStoreProvider: TimaSignature is unavailable
05-19 09:21:52.181  9984  9984 D ActivityThread: Added TimaKeyStore provider
,05-19 09:21:52.181  3511  3529 D ActivityManager: cleanUpApplicationRecord -- 9155
,05-19 09:21:52.181  3511  3529 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.coreapps, Auto Run ON
,05-19 09:21:52.201  3511  4343 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{c55eb9 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bf6ed82 9984:com.samsung.android.sm.policy/u0a142}
,05-19 09:21:52.201  9984  9984 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,05-19 09:21:52.201  9984  9984 D RelationGraph: garbageCollect()
,05-19 09:21:52.201  9984  9984 W ResourcesManager: getTopLevelResources: /system/app/SCPMClient/SCPMClient.apk / 1.0 running in com.samsung.android.sm.policy rsrc of package com.samsung.android.sm.policy
,05-19 09:21:52.211  3511  4847 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-19 09:21:52.211  9984  9984 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-19 09:21:52.211  9984  9984 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 09:21:52.211  9984  9984 I InjectionManager: Inside getClassLibPath caller 
,05-19 09:21:52.221  9984  9984 W System  : ClassLoader referenced unknown path: /system/app/SCPMClient/lib/arm64
,05-19 09:21:52.221  9689  9775 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,05-19 09:21:52.221  3511  4343 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,05-19 09:21:52.221  3511  4343 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,05-19 09:21:52.221  3511  4343 D WifiService: setWifiEnabled: true pid=9689, uid=10078
05-19 09:21:52.221  3511  4343 W ActivityManager: Permission Denial: getCurrentUser() from pid=9689, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
,05-19 09:21:52.221  3511  4343 W WifiService: Failed getting userId using ActivityManagerNative
05-19 09:21:52.221  3511  4343 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9689, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-19 09:21:52.221  3511  4343 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-19 09:21:52.221  3511  4343 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
05-19 09:21:52.221  3511  4343 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
05-19 09:21:52.221  3511  4343 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
05-19 09:21:52.221  3511  4343 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
05-19 09:21:52.221  3511  4343 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
05-19 09:21:52.221  3511  4343 D SettingsProvider: isChangeAllowed() : name = wifi_on
05-19 09:21:52.221  3511  3860 D WifiStateMachine: setFccChannel: channel = 0
05-19 09:21:52.221  3511  3860 D WifiController: [FCC]setFccChannel() is called !!!
05-19 09:21:52.221  3511  3860 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
,05-19 09:21:52.231  9984  9984 D InjectionManager: InjectionManager
05-19 09:21:52.231  9984  9984 D InjectionManager: fillFeatureStoreMap com.samsung.android.sm.policy
,05-19 09:21:52.231  9984  9984 I InjectionManager: Constructor com.samsung.android.sm.policy, Feature store :{}
05-19 09:21:52.231  9984  9984 I InjectionManager: featureStore :{}
,05-19 09:21:52.231  3511  3852 D ActivityManager:  getDeferredInfo final delay 0
,05-19 09:21:52.241  9996  9996 E Zygote  : v2
05-19 09:21:52.241  9996  9996 I libpersona: KNOX_SDCARD checking this for 5005
05-19 09:21:52.241  9996  9996 I libpersona: KNOX_SDCARD not a persona
,05-19 09:21:52.241  3511  3852 I ActivityManager: Start proc 9996:com.samsung.android.app.FileShareClient/5005 for broadcast-5 com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver
05-19 09:21:52.241  9996  9996 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-19 09:21:52.241  3511  3852 I ActivityManager: Killing 9185:com.google.android.apps.photos/u0a135 (adj 15): DHA:empty #33
05-19 09:21:52.241  9996  9996 E Zygote  : accessInfo : 0
,05-19 09:21:52.241  9996  9996 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.app.FileShareClient 
,05-19 09:21:52.261  9996  9996 D TimaKeyStoreProvider: TimaSignature is unavailable
05-19 09:21:52.261  9996  9996 D ActivityThread: Added TimaKeyStore provider
,05-19 09:21:52.271  3511  4422 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{90cec93 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{747b4d0 9996:com.samsung.android.app.FileShareClient/5005}
,05-19 09:21:52.271  3511  4198 D ActivityManager: cleanUpApplicationRecord -- 9185
,05-19 09:21:52.271  3511  4198 D ActivityManager: isAutoRunBlockedApp:: com.google.android.apps.photos, Auto Run ON
,05-19 09:21:52.281  9996  9996 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
05-19 09:21:52.281  9996  9996 D RelationGraph: garbageCollect()
,05-19 09:21:52.281  9996  9996 W ResourcesManager: getTopLevelResources: /system/app/AllshareFileShareClient/AllshareFileShareClient.apk / 1.0 running in com.samsung.android.app.FileShareClient rsrc of package com.samsung.android.app.FileShareClient
,05-19 09:21:52.281  3511  3852 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-19 09:21:52.281  9996  9996 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-19 09:21:52.281  9996  9996 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 09:21:52.281  9996  9996 I InjectionManager: Inside getClassLibPath caller 
,05-19 09:21:52.291  9996  9996 W System  : ClassLoader referenced unknown path: /system/app/AllshareFileShareClient/lib/arm64
,05-19 09:21:52.291  9996  9996 D InjectionManager: InjectionManager
05-19 09:21:52.291  9996  9996 D InjectionManager: fillFeatureStoreMap com.samsung.android.app.FileShareClient
,05-19 09:21:52.291  9996  9996 I InjectionManager: Constructor com.samsung.android.app.FileShareClient, Feature store :{}
05-19 09:21:52.291  9996  9996 I InjectionManager: featureStore :{}
,05-19 09:21:52.291  9996  9996 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,05-19 09:21:52.291  9996  9996 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,05-19 09:21:52.311  9996  9996 D FileShare-Client: Outbound.stopDelayTimer - 
,05-19 09:21:52.311  3511  4422 D ActivityManager:  getDeferredInfo final delay 0
,05-19 09:21:52.321 10008 10008 E Zygote  : v2
05-19 09:21:52.321 10008 10008 I libpersona: KNOX_SDCARD checking this for 5005
05-19 09:21:52.321 10008 10008 I libpersona: KNOX_SDCARD not a persona
,05-19 09:21:52.321 10008 10008 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-19 09:21:52.321  3511  4422 I ActivityManager: Start proc 10008:com.samsung.android.app.FileShareServer/5005 for broadcast-5 com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver
,05-19 09:21:52.321 10008 10008 E Zygote  : accessInfo : 0
05-19 09:21:52.321 10008 10008 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.app.FileShareServer 
05-19 09:21:52.321  3511  4422 I ActivityManager: Killing 8595:com.google.android.talk:matchstick/u0a117 (adj 15): DHA:empty #33
,05-19 09:21:52.341 10008 10008 D TimaKeyStoreProvider: TimaSignature is unavailable
05-19 09:21:52.341 10008 10008 D ActivityThread: Added TimaKeyStore provider
,05-19 09:21:52.351  3511  3528 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{90cec93 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b7f8cc9 10008:com.samsung.android.app.FileShareServer/5005}
,05-19 09:21:52.361  3511  4313 D ActivityManager: cleanUpApplicationRecord -- 8595
,05-19 09:21:52.361  3511  4313 D ActivityManager: isAutoRunBlockedApp:: com.google.android.talk, Auto Run ON
,05-19 09:21:52.361 10008 10008 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
05-19 09:21:52.361 10008 10008 D RelationGraph: garbageCollect()
,05-19 09:21:52.361 10008 10008 W ResourcesManager: getTopLevelResources: /system/app/AllshareFileShareServer/AllshareFileShareServer.apk / 1.0 running in com.samsung.android.app.FileShareServer rsrc of package com.samsung.android.app.FileShareServer
,05-19 09:21:52.361  3511  3529 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-19 09:21:52.361 10008 10008 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-19 09:21:52.371 10008 10008 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 09:21:52.371 10008 10008 I InjectionManager: Inside getClassLibPath caller 
,05-19 09:21:52.381 10008 10008 D InjectionManager: InjectionManager
05-19 09:21:52.381 10008 10008 D InjectionManager: fillFeatureStoreMap com.samsung.android.app.FileShareServer
,05-19 09:21:52.381 10008 10008 I InjectionManager: Constructor com.samsung.android.app.FileShareServer, Feature store :{}
05-19 09:21:52.381 10008 10008 I InjectionManager: featureStore :{}
,05-19 09:21:52.381 10008 10008 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,05-19 09:21:52.381 10008 10008 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,05-19 09:21:52.381 10008 10008 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,05-19 09:21:52.381  3511  4407 D ActivityManager:  getDeferredInfo final delay 0
,05-19 09:21:52.391  3511  4407 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{ca90f07 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dcdc7f7 9957:com.sec.android.diagmonagent/1000}
,05-19 09:21:52.391  9957  9957 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,05-19 09:21:52.391  9957  9957 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
,05-19 09:21:52.401  9957  9957 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,05-19 09:21:52.401  3511  4407 D ActivityManager:  getDeferredInfo final delay 0
,05-19 09:21:52.401  3511  4407 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{ca90f07 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fdbb0cd 9972:com.sec.knox.switcher/1000}
,05-19 09:21:52.401  9972  9972 I usagelog: received in receiver
05-19 09:21:52.401  9972  9972 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
05-19 09:21:52.401  9972  9972 I KnoxUsageLogPro: premStatus:2
,05-19 09:21:52.401  9972  9972 I KnoxUsageLogPro: isEulaShown : false
05-19 09:21:52.401  9972  9972 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,05-19 09:21:52.411  3511  4407 D ActivityManager:  getDeferredInfo final delay 0
,05-19 09:21:52.421  3511  4407 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{ca90f07 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bf6ed82 9984:com.samsung.android.sm.policy/u0a142}
,05-19 09:21:52.431  3511  4407 D ActivityManager:  getDeferredInfo final delay 0
,05-19 09:21:52.451 10020 10020 E Zygote  : v2
05-19 09:21:52.451 10020 10020 I libpersona: KNOX_SDCARD checking this for 1000
05-19 09:21:52.451 10020 10020 I libpersona: KNOX_SDCARD not a persona
,05-19 09:21:52.451 10020 10020 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
05-19 09:21:52.461 10020 10020 E Zygote  : accessInfo : 0
05-19 09:21:52.461  3511  4407 I ActivityManager: Start proc 10020:com.policydm/1000 for broadcast-5 com.policydm/.XDMBroadcastReceiver
05-19 09:21:52.461  3511  4407 I ActivityManager: Killing 9228:com.android.defcontainer/u0a10 (adj 15): DHA:empty #33
,05-19 09:21:52.491  3511  4847 D ActivityManager: cleanUpApplicationRecord -- 9228
,05-19 09:21:52.491  3511  4847 D ActivityManager: isAutoRunBlockedApp:: com.android.defcontainer, Auto Run ON
,05-19 09:21:52.521 10020 10020 D TimaKeyStoreProvider: TimaSignature is unavailable
05-19 09:21:52.521 10020 10020 D ActivityThread: Added TimaKeyStore provider
,05-19 09:21:52.531  3511  3982 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{cf9b834 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{eaa5fce 10020:com.policydm/1000}
,05-19 09:21:52.541 10020 10020 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
05-19 09:21:52.541 10020 10020 D RelationGraph: garbageCollect()
,05-19 09:21:52.541 10020 10020 W ResourcesManager: getTopLevelResources: /system/priv-app/SPDClient/SPDClient.apk / 1.0 running in com.policydm rsrc of package com.policydm
,05-19 09:21:52.541  3511  4407 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-19 09:21:52.541 10020 10020 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-19 09:21:52.541 10020 10020 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 09:21:52.551 10020 10020 I InjectionManager: Inside getClassLibPath caller 
,05-19 09:21:52.551 10020 10020 W System  : ClassLoader referenced unknown path: /system/priv-app/SPDClient/lib/arm64
,05-19 09:21:52.561 10020 10020 I FOTA    : [lIlIIlIIlIlllIIIIlll(108/llIIIIlllllIIllIIllI)] oms: /customer.xml
,05-19 09:21:52.561 10020 10020 I FOTA    : [lIlIIlIIlIlllIIIIlll(199/lllIlIlIIIllIIlIllIl)] read default : /system/csc/customer.xml
,05-19 09:21:52.581 10020 10020 I FOTA    : [com.sec.android.policyagent.PolicyApplication(36/onCreate)] PolicyApplication onCreated!
,05-19 09:21:52.581 10020 10020 I DBG_POLICYDM: [com.policydm.db.XDB(1600/IllIlIIIIlIIlIIIllIl)] xdbDMffs_Init
,05-19 09:21:52.591 10020 10020 I DBG_POLICYDM: [com.policydm.db.llIIIIlllllIIllIIllI(142/llIIIIlllllIIllIIllI)] try read dbString
,05-19 09:21:52.651 10020 10020 I DBG_POLICYDM: [com.policydm.XDMService(161/llIIIIlllllIIllIIllI)] xdmUIHandelerInit
,05-19 09:21:52.651 10020 10020 I DBG_POLICYDM: [IlIIIllIlIIIlIIlIIlI(52/<init>)] 
,05-19 09:21:52.651 10020 10020 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1394 android.content.ContextWrapper.bindService:632 IlIIIllIlIIIlIIlIIlI.<init>:56 IIIlIIlllIlIlIIIIIII.llIIIIlllllIIllIIllI:19 IIIlIIlllIlIlIIIIIII.llllIIIllIlIIIIllllI:25 
,05-19 09:21:52.661  3511  4459 I ActivityManager: Start proc 10036:com.samsung.aasaservice/1000 for service com.samsung.aasaservice/.AASAService
,05-19 09:21:52.661 10020 10020 I DBG_POLICYDM: [IIIlIIlllIlIlIIIIIII(28/llllIIIllIlIIIIllllI)] AASAUpdater Init Success
,05-19 09:21:52.671 10020 10020 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,05-19 09:21:52.671 10020 10020 I DBG_POLICYDM: [com.policydm.XDMService(585/llIlIllllllllllllllI)] get NotibarState : 0
,05-19 09:21:52.671 10020 10020 D InjectionManager: InjectionManager
05-19 09:21:52.671 10020 10020 D InjectionManager: fillFeatureStoreMap com.policydm
,05-19 09:21:52.671 10020 10020 I InjectionManager: Constructor com.policydm, Feature store :{}
05-19 09:21:52.671 10020 10020 I InjectionManager: featureStore :{}
,05-19 09:21:52.681 10020 10020 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(574/IlIIIllllIIlIIIIIlII)] Initiated Type: 0
,05-19 09:21:52.681 10020 10020 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,05-19 09:21:52.681 10020 10020 I DBG_POLICYDM: [com.policydm.XDMService(585/llIlIllllllllllllllI)] get NotibarState : 0
05-19 09:21:52.681  3511  4313 D ActivityManager:  getDeferredInfo final delay 0
,05-19 09:21:52.691  3511  4313 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{cf9b834 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{eaa5fce 10020:com.policydm/1000}
,05-19 09:21:52.691 10020 10020 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(51/onReceive)] RegistrationReceiver onReceive! action = android.net.conn.CONNECTIVITY_CHANGE
,05-19 09:21:52.691  3511  4313 D ActivityManager:  getDeferredInfo final delay 0
,05-19 09:21:52.691  3511  4313 I ActivityManager: Killing 8899:com.samsung.android.app.appsedge/u0a1 (adj 15): DHA:empty #33
,05-19 09:21:52.701  3511  4313 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{cf9b834 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fba2792 6953:com.wssyncmldm/1000}
,05-19 09:21:52.701  3511  4313 D ActivityManager:  getDeferredInfo final delay 0
,05-19 09:21:52.701 10036 10036 E Zygote  : v2
05-19 09:21:52.701 10036 10036 I libpersona: KNOX_SDCARD checking this for 1000
05-19 09:21:52.701 10036 10036 I libpersona: KNOX_SDCARD not a persona
,05-19 09:21:52.701 10036 10036 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-19 09:21:52.711 10036 10036 E Zygote  : accessInfo : 0
,05-19 09:21:52.711  3511  4313 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{cf9b834 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{55f0a76 7126:com.samsung.fresco.logging/5015}
,05-19 09:21:52.711  3511  3528 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-19 09:21:52.711  3511  3982 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:52.711  3511  3589 D libgps  : agps_ril_update_network_availability: Waiting for IPC connection - timeout
05-19 09:21:52.711  3511  3589 E libgps  : LIBGPS: Cannot communicate (write) with a GPSD
05-19 09:21:52.711  3511  3589 E libgps  : IPC Communication Error, ../../../../tmp/14982990_270314/allPartners/os/android/gps_interface/gpsi_client/GpsiClient.cpp:1729 agps_ril_update_network_availability
,05-19 09:21:52.721  3511  4343 D ActivityManager: cleanUpApplicationRecord -- 8899
,05-19 09:21:52.721  3511  4343 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.appsedge, Auto Run ON
,05-19 09:21:52.721  9689  9775 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,05-19 09:21:52.731  3511  4313 D ActivityManager:  getDeferredInfo final delay 0
,05-19 09:21:52.731  3511  4459 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
05-19 09:21:52.731  3511  4459 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,05-19 09:21:52.731  3511  4459 D WifiService: setWifiEnabled: true pid=9689, uid=10078
,05-19 09:21:52.731  3511  4313 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{cf9b834 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{59af32b 7448:com.sec.spp.push/u0a42}
,05-19 09:21:52.731  7448  7448 E SPPClientService: [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
05-19 09:21:52.731  7448  7448 E SPPClientService: [SystemStateMoniter] Current Time : 218176
,05-19 09:21:52.731  7448  7448 E SPPClientService: [SystemStateMoniter] No Connect : true
,05-19 09:21:52.741  3511  4313 D ActivityManager:  getDeferredInfo final delay 0
,05-19 09:21:52.741  3511  4459 W WifiService: Failed getting userId using ActivityManagerNative
05-19 09:21:52.741  3511  4459 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9689, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-19 09:21:52.741  3511  4459 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-19 09:21:52.741  3511  4459 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
05-19 09:21:52.741  3511  4459 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
05-19 09:21:52.741  3511  4459 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
05-19 09:21:52.741  3511  4459 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
05-19 09:21:52.741  3511  4459 W ActivityManager: Permission Denial: getCurrentUser() from pid=9689, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-19 09:21:52.741  3511  4459 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
05-19 09:21:52.741  3511  4459 D SettingsProvider: isChangeAllowed() : name = wifi_on
05-19 09:21:52.741  3511  3860 D WifiController: [FCC]setFccChannel() is called !!!
05-19 09:21:52.741  3511  3860 D WifiStateMachine: setFccChannel: channel = 0
05-19 09:21:52.741  3511  3860 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
,05-19 09:21:52.741 10036 10036 D TimaKeyStoreProvider: TimaSignature is unavailable
,05-19 09:21:52.741 10036 10036 D ActivityThread: Added TimaKeyStore provider
,05-19 09:21:52.751  7448 10049 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,05-19 09:21:52.751  3511  4313 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{cf9b834 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{40b0457 5011:android.process.media/u0a51}
,05-19 09:21:52.751  5011  5011 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,05-19 09:21:52.761  3511  4313 D ActivityManager:  getDeferredInfo final delay 300
,05-19 09:21:52.771 10036 10036 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,05-19 09:21:52.771 10036 10036 D RelationGraph: garbageCollect()
,05-19 09:21:52.771 10036 10036 W ResourcesManager: getTopLevelResources: /system/app/AASAservice/AASAservice.apk / 1.0 running in com.samsung.aasaservice rsrc of package com.samsung.aasaservice
,05-19 09:21:52.771  3511  4407 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-19 09:21:52.771 10036 10036 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-19 09:21:52.771 10036 10036 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 09:21:52.771 10036 10036 I InjectionManager: Inside getClassLibPath caller 
,05-19 09:21:52.781 10036 10036 W System  : ClassLoader referenced unknown path: /system/app/AASAservice/lib/arm64
,05-19 09:21:52.781 10036 10036 D InjectionManager: InjectionManager
05-19 09:21:52.781 10036 10036 D InjectionManager: fillFeatureStoreMap com.samsung.aasaservice
,05-19 09:21:52.781 10036 10036 I InjectionManager: Constructor com.samsung.aasaservice, Feature store :{}
05-19 09:21:52.781 10036 10036 I InjectionManager: featureStore :{}
,05-19 09:21:52.781 10036 10036 D AASAservice: onCreate()
,05-19 09:21:52.781 10020 10020 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(38/onServiceConnected)] AASA: onServiceConnected
,05-19 09:21:52.781  3511  4343 I ActivityManager: Killing 9308:com.samsung.android.app.galaxylabs/u0a17 (adj 15): DHA:empty #33
,05-19 09:21:52.791  3511  4422 D ActivityManager: cleanUpApplicationRecord -- 9308
,05-19 09:21:52.791  3511  4422 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.galaxylabs, Auto Run ON
,05-19 09:21:52.811  3511  4459 V AlarmManager:  remove PendingIntent] PendingIntent{1c35b0b: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:21:52.831  3158  3678 D Netd    : Iface wlan0 link up
,05-19 09:21:52.831  3511  3604 D Tethering: interfaceLinkStateChanged wlan0, true
05-19 09:21:52.831  3511  3604 D Tethering: interfaceStatusChanged wlan0, true
,05-19 09:21:52.831  4867  5177 D PdnController: Interface Changed wlan0 link up
05-19 09:21:52.831  3158  3678 D Netd    : Iface wlan0 link up
05-19 09:21:52.831  3158  3678 D Netd    : Iface wlan0 link up
,05-19 09:21:52.831  3511  3604 D Tethering: interfaceLinkStateChanged wlan0, true
05-19 09:21:52.831  3511  3604 D Tethering: interfaceStatusChanged wlan0, true
,05-19 09:21:52.831  4867  4881 D PdnController: Interface Changed wlan0 link up
,05-19 09:21:52.831  3511  3604 D Tethering: interfaceLinkStateChanged wlan0, true
05-19 09:21:52.831  3511  3604 D Tethering: interfaceStatusChanged wlan0, true
,05-19 09:21:52.831  4867  4880 D PdnController: Interface Changed wlan0 link up
,05-19 09:21:52.941  3511  4407 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1248000  uid : 1000  pid : 3511  tag : BADGE_UPDATE@CPU_MIN@1
,05-19 09:21:52.951  9969  9969 I wpa_supplicant: set_csc_config : ifname(p2p0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x0), vendorssid_list()
05-19 09:21:52.951  9969  9969 I SecureStorage: [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,05-19 09:21:52.991  9969  9969 I SecureStorage: [INFO]: SPID(0x00000005)This device supports Secure Storage
,05-19 09:21:52.991  3018  3018 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 9969
,05-19 09:21:52.991  3018  3018 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
05-19 09:21:52.991  9969  9969 I SecureStorage: [INFO]: SPID(0x00000005)SS Daemon is running
05-19 09:21:52.991  9969  9969 I wpa_supplicant: ssSupport state is = 1
,05-19 09:21:53.001  3511  6156 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-19 09:21:53.001  9969  9969 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,05-19 09:21:53.001  9969  9969 E wpa_supplicant: nl80211: Could not configure driver mode
,05-19 09:21:53.001  9969  9969 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
05-19 09:21:53.001  9969  9969 E wpa_supplicant: p2p0: Failed to initialize driver interface
05-19 09:21:53.001  9969  9969 I wpa_supplicant: Blacklist: Clear (all) 
,05-19 09:21:53.011  9969  9969 I wpa_supplicant: set_csc_config : ifname(p2p0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x0), vendorssid_list()
,05-19 09:21:53.011  9969  9969 I SecureStorage: [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,05-19 09:21:53.041  9969  9969 I SecureStorage: [INFO]: SPID(0x00000005)This device supports Secure Storage
,05-19 09:21:53.041  3018  3018 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 9969
05-19 09:21:53.041  3018  3018 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
05-19 09:21:53.041  9969  9969 I SecureStorage: [INFO]: SPID(0x00000005)SS Daemon is running
05-19 09:21:53.041  9969  9969 I wpa_supplicant: ssSupport state is = 1
,05-19 09:21:53.041  9969  9969 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,05-19 09:21:53.051  9969  9969 I wpa_supplicant: P2P: Set prekey state (NONE -> NONE)
,05-19 09:21:53.061  3511  3857 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,05-19 09:21:53.061  3511  3857 E WifiStateMachine: Deffering msg in Supplicant Starting State131085
05-19 09:21:53.061  3511  3857 E WifiStateMachine: Deffering msg in Supplicant Starting State131156
,05-19 09:21:53.061  3511  3857 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,05-19 09:21:53.061  3511  3857 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
05-19 09:21:53.061  3511  3857 D WifiBigDataLog: init : 
,05-19 09:21:53.071  3511  3857 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,05-19 09:21:53.071  3511  3857 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,05-19 09:21:53.141  3511  3597 D ActivityManager:  getDeferredInfo final delay 0
,05-19 09:21:53.161 10054 10054 E Zygote  : v2
05-19 09:21:53.161 10054 10054 I libpersona: KNOX_SDCARD checking this for 1000
05-19 09:21:53.161 10054 10054 I libpersona: KNOX_SDCARD not a persona
,05-19 09:21:53.161 10054 10054 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-19 09:21:53.161  3511  3597 I ActivityManager: Start proc 10054:com.samsung.android.SettingsReceiver/1000 for broadcast-5 com.samsung.android.SettingsReceiver/.SettingsIntentReceiver
,05-19 09:21:53.161 10054 10054 E Zygote  : accessInfo : 0
,05-19 09:21:53.171  3511  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b6d4de8 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cf9e5aa 4853:com.samsung.android.providers.context/u0a9}
,05-19 09:21:53.171  3511  3857 D WifiBigDataLog: init : 
,05-19 09:21:53.171  3511  3857 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,05-19 09:21:53.181  3511  3857 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,05-19 09:21:53.181  3511  3982 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4b70c01 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cf9e5aa 4853:com.samsung.android.providers.context/u0a9}
,05-19 09:21:53.191  3511  3857 D WifiBigDataLog: init : 
,05-19 09:21:53.191  3511  3857 D WifiNative-wlan0: callSECApiBoolean - ID [301]
05-19 09:21:53.191  9969  9969 I wpa_supplicant: HOTSPOT20_ENABLE called ON
05-19 09:21:53.191  9969  9969 I wpa_supplicant: Blacklist: Clear (all) 
,05-19 09:21:53.201  9969  9969 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,05-19 09:21:53.201  3511  3982 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{15e9aa6 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cf9e5aa 4853:com.samsung.android.providers.context/u0a9}
,05-19 09:21:53.201 10054 10054 D TimaKeyStoreProvider: TimaSignature is unavailable
,05-19 09:21:53.201  9969  9969 I wpa_supplicant: wlan0: Skip scan - bUseNetwork false
05-19 09:21:53.201 10054 10054 D ActivityThread: Added TimaKeyStore provider
,05-19 09:21:53.211  3511  3857 D WifiNative-wlan0: callSECApiInt - ID [210]
,05-19 09:21:53.211  3511  3511 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
05-19 09:21:53.221  3511  3861 D HS20StateMachine: WIFI_STATE_ENABLED
05-19 09:21:53.221  3511  3861 D HS20StateMachine: reloadCredentialsToSupplicant
05-19 09:21:53.221  3511  3861 D HotspotDBHandler: getCredentialIds
05-19 09:21:53.221  3511  3511 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
,05-19 09:21:53.221  3511  3864 I WifiHs20Service: Message received 5011
,05-19 09:21:53.221  3511  3511 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
05-19 09:21:53.221  3511  3868 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
05-19 09:21:53.221  3511  4235 W SLocation: No Active Data Connection
,05-19 09:21:53.221  3939  4163 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-19 09:21:53.221  3939  3939 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
05-19 09:21:53.221  3939  3939 I HotspotTile: Provider is not defined returning false
,05-19 09:21:53.231  3939  3939 D HotspotTile: onReceive : 3, 0
,05-19 09:21:53.231  4287  4297 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,05-19 09:21:53.231  4287  4297 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,05-19 09:21:53.231  3939  3939 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 272
05-19 09:21:53.231  3511  3868 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,05-19 09:21:53.251  3511  3982 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{aca9ce7 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8ab765d 9689:com.rockwellautomation.thalitest/u0a78}
,05-19 09:21:53.251  9969  9969 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,05-19 09:21:53.261  3511  3857 D WifiConfigStore: Loading config and enabling all networks 
,05-19 09:21:53.261  9689  9775 D BluetoothAdapter: STATE_ON
,05-19 09:21:53.261  9689  9689 D BluetoothAdapter: STATE_ON
,05-19 09:21:53.271  9689  9689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-19 09:21:53.271  9689  9689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-19 09:21:53.271  9689  9689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-19 09:21:53.271  9689  9689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-19 09:21:53.271  9689  9689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-19 09:21:53.271  9689  9689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
05-19 09:21:53.271  9689  9689 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
05-19 09:21:53.271  9689  9689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
05-19 09:21:53.271  9689  9689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,05-19 09:21:53.271  9689  9775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-19 09:21:53.271  9689  9775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-19 09:21:53.271  9689  9775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-19 09:21:53.271  9689  9775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-19 09:21:53.271  9689  9775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-19 09:21:53.271  9689  9775 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
05-19 09:21:53.271  9689  9775 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
05-19 09:21:53.271  9689  9775 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
05-19 09:21:53.271  9689  9775 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,05-19 09:21:53.271  9689  9753 D BluetoothAdapter: enable()
05-19 09:21:53.271  9689  9689 D BluetoothAdapter: STATE_ON
05-19 09:21:53.271  9689  9689 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
05-19 09:21:53.281  3511  4847 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{cf9b834 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5bd6094 10054:com.samsung.android.SettingsReceiver/1000}
05-19 09:21:53.281  3511  3528 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:53.281  3511  3528 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:53.281  3511  3528 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:53.281  3511  3528 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:53.281  3511  3528 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:53.281  3511  3528 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:53.281  3511  3528 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:53.281  3511  3528 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:53.281  3511  3528 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:53.281  3511  3528 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:53.281  3511  3528 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:53.281  3511  3528 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
05-19 09:21:53.281  3511  3528 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:53.281  3511  3528 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:53.281  3511  3528 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:53.291  3511  3857 I WifiConfigStore: "NG700" is a verified password AP: true
05-19 09:21:53.291  3511  3857 E WifiConfigStore: Not a HS20
05-19 09:21:53.291  3511  3857 D WifiConfigStore: loaded 0 passpoint configs
05-19 09:21:53.291  3511  3857 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
05-19 09:21:53.291  3511  3857 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
05-19 09:21:53.291 10054 10054 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
05-19 09:21:53.291  3511  3857 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
05-19 09:21:53.291 10067 10067 I libpersona: KNOX_SDCARD checking this for 10119
05-19 09:21:53.291 10067 10067 E Zygote  : v2
05-19 09:21:53.291 10067 10067 I libpersona: KNOX_SDCARD not a persona
05-19 09:21:53.301 10054 10054 D RelationGraph: garbageCollect()
05-19 09:21:53.301 10067 10067 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
05-19 09:21:53.301 10067 10067 E Zygote  : accessInfo : 0
05-19 09:21:53.301 10054 10054 W ResourcesManager: getTopLevelResources: /system/priv-app/SettingsReceiver/SettingsReceiver.apk / 1.0 running in com.samsung.android.SettingsReceiver rsrc of package com.samsung.android.SettingsReceiver
05-19 09:21:53.301 10067 10067 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.samsung.hs20provider 
05-19 09:21:53.301  3511  3861 I ActivityManager: Start proc 10067:com.samsung.hs20provider/u0a119 for content provider com.samsung.hs20provider/.Hs20Provider
05-19 09:21:53.301  3511  4407 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-19 09:21:53.301 10054 10054 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
05-19 09:21:53.301 10054 10054 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 09:21:53.311 10054 10054 I InjectionManager: Inside getClassLibPath caller 
05-19 09:21:53.311  3511  3857 D WifiConfigStore: setNetworkPriorityDefault: networkId = 0, priority = 1
05-19 09:21:53.311  3511  3857 D WifiNative-wlan0: callSECApiInt - ID [65]
05-19 09:21:53.311  9689  9753 D BluetoothAdapter: enable(): BT is already enabled..!
05-19 09:21:53.321 10054 10054 W System  : ClassLoader referenced unknown path: /system/priv-app/SettingsReceiver/lib/arm64
05-19 09:21:53.321  3511  3511 I WifiHs20Service: Broadcast received:android.net.wifi.CONFIGURED_NETWORKS_CHANGE
05-19 09:21:53.321  3511  3511 D WifiHs20Service: reason: 2
05-19 09:21:53.321  3511  3864 I WifiHs20Service: Message received 5014
05-19 09:21:53.321  3511  3864 E WifiHs20Service: received HS20_UTILITY_ACTION_TYPE_HS20_CONFIGURATION_CHANGED
05-19 09:21:53.321  3511  3864 E WifiHs20Service: The changed config is NULL
05-19 09:21:53.321 10054 10054 D InjectionManager: InjectionManager
05-19 09:21:53.321 10054 10054 D InjectionManager: fillFeatureStoreMap com.samsung.android.SettingsReceiver
05-19 09:21:53.321  3511  3857 D WifiNative-wlan0: callSECApiBoolean - ID [13]
05-19 09:21:53.321 10054 10054 I InjectionManager: Constructor com.samsung.android.SettingsReceiver, Feature store :{}
05-19 09:21:53.321 10054 10054 I InjectionManager: featureStore :{}
05-19 09:21:53.321  9969  9969 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
05-19 09:21:53.321  9969  9969 I wpa_supplicant: resume autoscan
05-19 09:21:53.321  9969  9969 I wpa_supplicant: autoscan_samsung_exponential_notify_scan : scan_interval = 8
05-19 09:21:53.321  9969  9969 I wpa_supplicant: autoscan: autoscan_notify_scan, scan_interval = 8
05-19 09:21:53.321  9969  9969 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
05-19 09:21:53.321  9969  9969 I wpa_supplicant: reset timer : RESET_TIMER 0
05-19 09:21:53.321  9969  9969 I wpa_supplicant: P2P: Current p2p state = IDLE
05-19 09:21:53.321  9969  9969 I wpa_supplicant: First Scan Start
05-19 09:21:53.331  3511  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b87673d u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cf9e5aa 4853:com.samsung.android.providers.context/u0a9}
05-19 09:21:53.331  9689  9753 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
05-19 09:21:53.331 10054 10054 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in com.samsung.android.SettingsReceiver rsrc of package com.android.settings
05-19 09:21:53.331  9969  9969 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
05-19 09:21:53.331  3511  4185 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
05-19 09:21:53.331  3511  4185 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
05-19 09:21:53.331  3511  4185 D WifiService: setWifiEnabled: true pid=9689, uid=10078
05-19 09:21:53.331  3511  3857 D WifiNative-wlan0: Setting external_sim to 1
05-19 09:21:53.341 10054 10054 D ResourcesManager: For user 0 new overlays fetched Null
05-19 09:21:53.331  3511  3857 D WifiStateMachine: [setCountryCode()] Airplane mode return !!!
05-19 09:21:53.331  3511  3857 D WifiStateMachine: Setting OUI to DA-A1-19
05-19 09:21:53.341  3511  4185 W ActivityManager: Permission Denial: getCurrentUser() from pid=9689, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-19 09:21:53.331  9969  9969 I wpa_supplicant: bt_status is set be DISCONNECTED
05-19 09:21:53.341  3511  4185 D SettingsProvider: isChangeAllowed() : name = wifi_on
05-19 09:21:53.331 10067 10067 D TimaKeyStoreProvider: TimaSignature is unavailable
05-19 09:21:53.341  3511  3860 D WifiController: [FCC]setFccChannel() is called !!!
05-19 09:21:53.331 10067 10067 D ActivityThread: Added TimaKeyStore provider
05-19 09:21:53.341  3511  3860 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
05-19 09:21:53.341  3511  4185 W WifiService: Failed getting userId using ActivityManagerNative
05-19 09:21:53.341  3511  4185 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9689, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-19 09:21:53.341  3511  4185 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-19 09:21:53.341  3511  4185 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
05-19 09:21:53.341  3511  4185 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
05-19 09:21:53.341  3511  4185 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
05-19 09:21:53.341  3511  4185 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
05-19 09:21:53.341  3511  4185 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
05-19 09:21:53.341  3511  3860 D WifiStateMachine: setFccChannel: channel = 0
05-19 09:21:53.341  9689  9753 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
05-19 09:21:53.341  9689  9753 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
05-19 09:21:53.341  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
05-19 09:21:53.341  9689  9753 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
05-19 09:21:53.341  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
05-19 09:21:53.341  9689  9753 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e420f1d removed from the list
05-19 09:21:53.341  9689  9753 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e420f1d removed from the list
05-19 09:21:53.341  9689  9753 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
05-19 09:21:53.341  9689  9753 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@297592 removed from the list
05-19 09:21:53.341  9689  9753 D io.jxcore.node.ConnectivityMonitor: stop
05-19 09:21:53.341  9689  9753 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
05-19 09:21:53.341  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
05-19 09:21:53.341  9689  9753 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testRun
05-19 09:21:53.341  3511  3857 E WifiNative-wlan0: do suspend false
05-19 09:21:53.351  9689 10079 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,05-19 09:21:53.351  9689 10079 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
05-19 09:21:53.351  3158  3681 D EnterpriseController: netId is 0
05-19 09:21:53.351 10054 10054 E ActivityThread: Failed to find provider info for com.myscript.atk.rmc
05-19 09:21:53.351  3158  3681 D Netd    : getNetworkForDns: using netid 0 for uid 10078
05-19 09:21:53.361  3511  3857 D WifiStateMachine:  p2p Needed be enabled 
05-19 09:21:53.361  3511  3856 D WifiP2pService: P2pDisabledState{ what=131203 }
05-19 09:21:53.361  3511  3857 D WifiNative-HAL: Failing getSupportedFeatureset because HAL isn't started
05-19 09:21:53.361  3511  3857 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
05-19 09:21:53.361  3511  3857 D WifiStateMachine: [FCC]Airplane on, setFccChannel(0)!!!
05-19 09:21:53.361  3511  3857 D WifiStateMachine: setFccChannelNative: channel = 0
05-19 09:21:53.361  3511  3857 D WifiNative-wlan0: callSECApiInt - ID [230]
05-19 09:21:53.361  3511  3511 D RttService: SCAN_AVAILABLE : 3
05-19 09:21:53.361  3511  4459 D ActivityManager:  getDeferredInfo final delay 0
05-19 09:21:53.361  3511  3891 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
05-19 09:21:53.361  3511  3890 E WifiScanningService: could not start HAL
05-19 09:21:53.361  9689 10081 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
05-19 09:21:53.361  9689 10081 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
05-19 09:21:53.361  9689 10081 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-19 09:21:53.361  3158  3685 D CommandListener: Setting iface cfg
05-19 09:21:53.361  3158  3685 D CommandListener: Trying to bring up p2p0
05-19 09:21:53.361  3158  3678 D Netd    : Iface p2p0 link up
05-19 09:21:53.361  9689 10081 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-19 09:21:53.361  9689 10079 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
05-19 09:21:53.361  9689 10079 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
05-19 09:21:53.361  9689 10079 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-19 09:21:53.371  9689 10079 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-19 09:21:53.371  3511  3604 D Tethering: interfaceLinkStateChanged p2p0, true
05-19 09:21:53.371  3511  3604 D Tethering: interfaceStatusChanged p2p0, true
05-19 09:21:53.371  9689 10079 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
05-19 09:21:53.371  4867  5179 D PdnController: Interface Changed p2p0 link up
05-19 09:21:53.371  3511  3856 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
05-19 09:21:53.371  3511  3856 D SecContentProvider: insert(), uri = 2
05-19 09:21:53.371 10067 10067 D RelationGraph: garbageCollect()
05-19 09:21:53.371 10067 10067 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
05-19 09:21:53.371  9689 10086 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 237, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:21:53.371  9689 10086 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 09:21:53.371  9689 10086 D io.jxcore.node.StreamCopyingThread:  id: 75
05-19 09:21:53.371  3511  3856 D WifiP2pService: P2pEnablingState
05-19 09:21:53.371  9689 10081 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
05-19 09:21:53.371  3511  3856 D WifiP2pService: P2pEnablingState{ what=147457 }
05-19 09:21:53.371  3511  3856 D SecContentProvider: insert(), uri = 2
05-19 09:21:53.371  3511  3856 D WifiP2pService: P2p socket connection successful
05-19 09:21:53.371  9689 10086 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 237, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:21:53.371  9689 10086 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 09:21:53.371  9689 10086 D io.jxcore.node.StreamCopyingThread:  id: 75
05-19 09:21:53.371  3511  3856 D WifiP2pService: P2pEnabledState
05-19 09:21:53.371 10067 10067 W ResourcesManager: getTopLevelResources: /system/app/Hs20Provider/Hs20Provider.apk / 1.0 running in com.samsung.hs20provider rsrc of package com.samsung.hs20provider
05-19 09:21:53.381  9689 10086 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:21:53.381  9689 10086 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 09:21:53.381  9689 10086 D io.jxcore.node.StreamCopyingThread:  id: 75
05-19 09:21:53.381  9689 10086 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
05-19 09:21:53.381  3511  3982 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-19 09:21:53.381  9689 10086 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
05-19 09:21:53.381  3511  3857 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
05-19 09:21:53.381  9689 10085 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 236, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:21:53.381  9689 10085 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 09:21:53.381  9689 10085 D io.jxcore.node.StreamCopyingThread:  id: 75
05-19 09:21:53.381 10088 10088 I libpersona: KNOX_SDCARD checking this for 10068
05-19 09:21:53.381  9689 10086 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
05-19 09:21:53.381 10088 10088 I libpersona: KNOX_SDCARD not a persona
05-19 09:21:53.381  9689 10086 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
05-19 09:21:53.381 10067 10067 D ResourcesManager: For user 0 new overlays fetched Null
05-19 09:21:53.381  9689 10086 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
05-19 09:21:53.381  3511  4459 I ActivityManager: Start proc 10088:com.samsung.android.themestore/u0a68 for broadcast-5 com.samsung.android.themestore/.manager.autoSelfUpgradeService.AutoSelfUpgradeReceiver
05-19 09:21:53.381  9689 10086 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
05-19 09:21:53.381  9689 10085 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 236, thread name: OutgoingSocketThread/Sender): recvfrom failed: EBADF (Bad file descriptor)
05-19 09:21:53.381  9689 10086 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 237, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:21:53.381  9689 10086 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 09:21:53.381  9689 10086 D io.jxcore.node.StreamCopyingThread:  id: 75 .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
05-19 09:21:53.381  9689 10085 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 236, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:21:53.381  9689 10085 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 09:21:53.381  9689 10085 D io.jxcore.node.StreamCopyingThread:  id: 75 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
05-19 09:21:53.381  9689 10085 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: recvfrom failed: EBADF (Bad file descriptor)
05-19 09:21:53.381  9689 10085 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
05-19 09:21:53.381  9689 10085 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 236, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:21:53.381  9689 10085 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 09:21:53.381  9689 10085 D io.jxcore.node.StreamCopyingThread:  id: 75 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
05-19 09:21:53.381  3511  4459 I ActivityManager: Killing 9325:com.google.android.partnersetup/u0a25 (adj 15): DHA:empty #33
05-19 09:21:53.381  9689 10084 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 234, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:21:53.381  9689 10084 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-19 09:21:53.381  9689 10084 D io.jxcore.node.StreamCopyingThread:  id: 74
05-19 09:21:53.381  9689 10084 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 234, thread name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:21:53.381  9689 10084 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-19 09:21:53.381  9689 10084 D io.jxcore.node.StreamCopyingThread:  id: 74
05-19 09:21:53.381  9689 10084 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:21:53.381  9689 10084 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-19 09:21:53.381  9689 10084 D io.jxcore.node.StreamCopyingThread:  id: 74
05-19 09:21:53.381  9689 10084 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
05-19 09:21:53.381  9689 10084 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,05-19 09:21:53.381  9689 10084 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
05-19 09:21:53.381  9689 10084 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
05-19 09:21:53.381  9689 10084 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
05-19 09:21:53.381  9689 10084 I io.jxcore.node.IncomingSocketThread: The sending thread is done
05-19 09:21:53.381  9689 10084 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 234, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:21:53.381  9689 10084 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-19 09:21:53.381  9689 10084 D io.jxcore.node.StreamCopyingThread:  id: 74 .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
05-19 09:21:53.381  9689 10087 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 235, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:21:53.381  9689 10087 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-19 09:21:53.381  9689 10087 D io.jxcore.node.StreamCopyingThread:  id: 74
05-19 09:21:53.381  3511  3857 D WifiBigDataLog: getJsonFormat() - feature : ONOF
05-19 09:21:53.381  9689 10087 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 235, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:21:53.381  9689 10087 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-19 09:21:53.381  9689 10087 D io.jxcore.node.StreamCopyingThread:  id: 74
05-19 09:21:53.381  9689 10087 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:21:53.381  9689 10087 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-19 09:21:53.381  9689 10087 D io.jxcore.node.StreamCopyingThread:  id: 74
05-19 09:21:53.381  9689 10087 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
05-19 09:21:53.381  9689 10087 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
05-19 09:21:53.381  9689 10087 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
05-19 09:21:53.381  9689 10087 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
05-19 09:21:53.381  9689 10087 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
05-19 09:21:53.381 10067 10067 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
05-19 09:21:53.381  9689 10087 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
05-19 09:21:53.381  9689 10087 I io.jxcore.node.IncomingSocketThread: Both threads are done, notifying the listener...
05-19 09:21:53.381  9689 10087 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 235, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:21:53.381  9689 10087 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-19 09:21:53.381  9689 10087 D io.jxcore.node.StreamCopyingThread:  id: 74 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
05-19 09:21:53.381 10088 10088 E Zygote  : v2
05-19 09:21:53.381 10088 10088 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
05-19 09:21:53.391 10088 10088 E Zygote  : accessInfo : 0
05-19 09:21:53.391 10088 10088 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.android.themestore 
05-19 09:21:53.391 10067 10067 I InjectionManager: Inside getClassLibPath caller 
05-19 09:21:53.391  3511  3866 E ConnectivityService: updateNetworkInfo()
05-19 09:21:53.391  3511  3856 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
05-19 09:21:53.391  3511  3511 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
05-19 09:21:53.391  3511  3866 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
05-19 09:21:53.391  3511  3649 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false, mScanRequestedInConnected = false
05-19 09:21:53.391  3511  3649 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
05-19 09:21:53.391  3511  3649 D WifiDisplayController: disconnect
05-19 09:21:53.391  3511  3649 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
05-19 09:21:53.391  3511  3857 D WifiBigDataLog: init : 
05-19 09:21:53.391 10067 10067 W System  : ClassLoader referenced unknown path: /system/app/Hs20Provider/lib/arm64
05-19 09:21:53.401  3511  3857 D WifiStateMachine: setFccChannelNative: channel = 0
05-19 09:21:53.401  3511  3857 D WifiNative-wlan0: callSECApiInt - ID [230]
05-19 09:21:53.401  9969  9969 I wpa_supplicant: P2P: Set Samsung Discovery Icon = 256
05-19 09:21:53.401  3939  3939 D WifiP2pController: onReceive android.net.wifi.p2p.CONNECTION_STATE_CHANGE
05-19 09:21:53.401  9969  9969 I wpa_supplicant: P2P: Set Samsung Discovery name = 
05-19 09:21:53.401  3511  3857 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
05-19 09:21:53.411  3511  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{49bb32 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cf9e5aa 4853:com.samsung.android.providers.context/u0a9}
05-19 09:21:53.411  3511  3649 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:53.411  3511  3649 I WifiDisplayAdapter: onP2pDisconnected
05-19 09:21:53.411  3511  3649 D IpRemoteDisplayController: disconnectWfdBridgeServer
05-19 09:21:53.411  3511  3649 D IpRemoteDisplayController: WfdBridgeServer is already null
05-19 09:21:53.411  4287  4298 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
05-19 09:21:53.411  3939  3939 D SoundPathController: onReceive - android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
05-19 09:21:53.411  3939  3939 D ApMirroringController: onReceive android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
05-19 09:21:53.411  3939  3939 D AllShareCastTile: onReceive : android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
05-19 09:21:53.411  3511  4343 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
05-19 09:21:53.411  3939  3939 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
05-19 09:21:53.421  3511  3857 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
05-19 09:21:53.431 10088 10088 D TimaKeyStoreProvider: TimaSignature is unavailable
05-19 09:21:53.431 10088 10088 D ActivityThread: Added TimaKeyStore provider
05-19 09:21:53.431 10067 10067 D InjectionManager: InjectionManager
05-19 09:21:53.431 10067 10067 D InjectionManager: fillFeatureStoreMap com.samsung.hs20provider
,05-19 09:21:53.431 10067 10067 I InjectionManager: Constructor com.samsung.hs20provider, Feature store :{}
05-19 09:21:53.431 10067 10067 I InjectionManager: featureStore :{}
,05-19 09:21:53.441  3511  4198 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{659f200 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{747b4d0 9996:com.samsung.android.app.FileShareClient/5005}
,05-19 09:21:53.441  9996  9996 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,05-19 09:21:53.441 10067 10078 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_credentials
05-19 09:21:53.441 10067 10078 D HotspotProvider: CREDENTIAL
05-19 09:21:53.441 10067 10078 D HotspotProvider: No prepend tags
05-19 09:21:53.441  9689  9689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-19 09:21:53.441  9996  9996 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
05-19 09:21:53.441  9996  9996 D FileShare-Client: Outbound.stopDelayTimer - 
,05-19 09:21:53.451  3511  3529 D ActivityManager: cleanUpApplicationRecord -- 9325
05-19 09:21:53.451  3511  3529 D ActivityManager: isAutoRunBlockedApp:: com.google.android.partnersetup, Auto Run ON
,05-19 09:21:53.461  9689  9689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-19 09:21:53.471  3511  4198 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{659f200 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b7f8cc9 10008:com.samsung.android.app.FileShareServer/5005}
,05-19 09:21:53.481  3511  3852 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{cf9b834 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8083a39 10088:com.samsung.android.themestore/u0a68}
,05-19 09:21:53.481 10008 10008 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,05-19 09:21:53.491  3511  3861 D HS20StateMachine: CMD_HOTSPOT20_ENABLE : 
05-19 09:21:53.491  3511  3861 D HS20StateMachine: enter : DiscoveringState
,05-19 09:21:53.491 10008 10008 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,05-19 09:21:53.501 10008 10008 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,05-19 09:21:53.501  3511  3529 I ActivityManager: Killing 9345:com.samsung.android.asksmanager/u0a177 (adj 15): DHA:empty #33
,05-19 09:21:53.511 10088 10088 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,05-19 09:21:53.511 10088 10088 D RelationGraph: garbageCollect()
,05-19 09:21:53.511 10088 10088 W ResourcesManager: getTopLevelResources: /system/priv-app/ThemeStore_3xh/ThemeStore_3xh.apk / 1.0 running in com.samsung.android.themestore rsrc of package com.samsung.android.themestore
05-19 09:21:53.511  3511  3856 E WifiP2pService: Failed to set my phone number info into probe response
,05-19 09:21:53.521  3511  4185 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-19 09:21:53.521 10088 10088 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
05-19 09:21:53.521  3511  3856 D WifiNative-p2p0: p2pGetDeviceAddress
,05-19 09:21:53.521  3511  3856 D WifiNative-p2p0: p2pGetDeviceAddress returning 4e:66:41:a6:c7:2d
,05-19 09:21:53.521  3511  3856 D WifiP2pService: DeviceAddress: 4e:c7:2d
,05-19 09:21:53.521 10088 10088 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 09:21:53.521  3511  3528 D ActivityManager: cleanUpApplicationRecord -- 9345
,05-19 09:21:53.531  3511  3528 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.asksmanager, Auto Run ON
,05-19 09:21:53.531 10088 10088 I InjectionManager: Inside getClassLibPath caller 
,05-19 09:21:53.531  3511  3649 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: [Phone] Samsung Galaxy S7 edge
05-19 09:21:53.531  3511  3649 D WifiDisplayController:  deviceAddress: 4e:66:41:a6:c7:2d
05-19 09:21:53.531  3511  3649 D WifiDisplayController:  primary type: 10-0050F204-5
05-19 09:21:53.531  3511  3649 D WifiDisplayController:  secondary type: null
05-19 09:21:53.531  3511  3649 D WifiDisplayController:  wps: 0
05-19 09:21:53.531  3511  3649 D WifiDisplayController:  grpcapab: 0
05-19 09:21:53.531  3511  3649 D WifiDisplayController:  devcapab: 0
05-19 09:21:53.531  3511  3649 D WifiDisplayController:  status: 3
05-19 09:21:53.531  3511  3649 D WifiDisplayController:  wfdInfo: null
05-19 09:21:53.531  3511  3649 D WifiDisplayController:  groupownerAddress: null
05-19 09:21:53.531  3511  3649 D WifiDisplayController:  GOdeviceName: null
05-19 09:21:53.531  3511  3649 D WifiDisplayController:  interfaceAddress: 
05-19 09:21:53.531  3511  3649 D WifiDisplayController:  SConnectInfo : null
05-19 09:21:53.531  3511  3649 D WifiDisplayController:  contactInfoHash : null
05-19 09:21:53.531  3511  3649 D WifiDisplayController:  ssDevInfo : 0
05-19 09:21:53.531  3511  3649 D WifiDisplayController:  iconIdx : 0
05-19 09:21:53.531  3511  3856 D WifiP2pService: sending p2p persistent groups changed broadcast
05-19 09:21:53.531  3511  3856 D WifiP2pService: InactiveState
,05-19 09:21:53.531  3511  3856 D WifiP2pService: InactiveState{ what=143376 }
05-19 09:21:53.531 10088 10088 W System  : ClassLoader referenced unknown path: /system/priv-app/ThemeStore_3xh/lib/arm64
05-19 09:21:53.531  3511  3856 D WifiP2pService: P2pEnabledState{ what=143376 }
05-19 09:21:53.531  3511  3856 E WifiP2pService: Airplane mode : skipped SET_COUNTRY_CODE
,05-19 09:21:53.551 10088 10088 D a       : Exist Config : false
,05-19 09:21:53.551 10088 10088 D a       : getMcc
05-19 09:21:53.551 10088 10088 D ai      : isQaMode
,05-19 09:21:53.561 10088 10088 D a       : getMnc
05-19 09:21:53.561 10088 10088 D a       : getCsc
,05-19 09:21:53.561 10088 10088 D a       : getSystemCountryCode
05-19 09:21:53.561 10088 10088 D a       : getImei
,05-19 09:21:53.561 10088 10088 D ai      : getMd5HashString
,05-19 09:21:53.571 10088 10088 D ai      : getSha256HashString
,05-19 09:21:53.571 10088 10088 D a       : getMsisdn
,05-19 09:21:53.571  4287  5318 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,05-19 09:21:53.581 10088 10088 D a       : getModelName
,05-19 09:21:53.581 10088 10088 D a       : getVirtualModelName
05-19 09:21:53.581 10088 10088 D a       : getAndroidSDKVersion
05-19 09:21:53.581 10088 10088 D a       : getLanguageCode
05-19 09:21:53.581 10088 10088 D a       : getCountryCode
,05-19 09:21:53.581 10088 10088 D a       : getNetworkType
,05-19 09:21:53.601 10088 10088 D t       : isSupportedAodSystemFeature
,05-19 09:21:53.601 10088 10088 D a       : isLogPrintMode
,05-19 09:21:53.611 10088 10088 D ai      : isQaMode
,05-19 09:21:53.621 10088 10088 D a       : getVerName
,05-19 09:21:53.621 10088 10088 D a       : getVerCode
,05-19 09:21:53.621 10088 10088 D a       : getPackageName
05-19 09:21:53.621 10088 10088 D a       : getAutoUpgradeInterval
,05-19 09:21:53.621 10088 10088 D a       : loadCountrySearchEx
,05-19 09:21:53.631 10088 10088 I a       : voCountrySearchEx loaded.
,05-19 09:21:53.631 10088 10088 I a       : # initConfig Time : 90
05-19 09:21:53.631 10088 10088 I a       : ● MCCNNC : 260 0
05-19 09:21:53.631 10088 10088 I a       : ● Model : SM-G935F_TM
05-19 09:21:53.631 10088 10088 I a       : ● MyApp Vertion : 1.03.22(20160524)
05-19 09:21:53.631 10088 10088 I a       : ● OS Vertion : 23
,05-19 09:21:53.651 10088 10088 D InjectionManager: InjectionManager
05-19 09:21:53.651 10088 10088 D InjectionManager: fillFeatureStoreMap com.samsung.android.themestore
,05-19 09:21:53.651 10088 10088 I InjectionManager: Constructor com.samsung.android.themestore, Feature store :{}
05-19 09:21:53.651 10088 10088 I InjectionManager: featureStore :{}
05-19 09:21:53.651 10088 10088 D AutoSelfUpgradeReceiver: onReceive() android.net.conn.CONNECTIVITY_CHANGE
,05-19 09:21:53.651  3511  4343 D ActivityManager:  getDeferredInfo final delay 0
,05-19 09:21:53.671 10107 10107 E Zygote  : v2
05-19 09:21:53.671 10107 10107 I libpersona: KNOX_SDCARD checking this for 5009
05-19 09:21:53.671 10107 10107 I libpersona: KNOX_SDCARD not a persona
,05-19 09:21:53.671 10107 10107 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-19 09:21:53.671  3511  4343 I ActivityManager: Start proc 10107:com.samsung.android.scloud:contentsync/5009 for broadcast-5 com.samsung.android.scloud/.cloudagent.detector.DetectorReceiver
,05-19 09:21:53.671 10107 10107 E Zygote  : accessInfo : 0
05-19 09:21:53.671 10107 10107 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.scloud:contentsync 
05-19 09:21:53.671  3511  4343 I ActivityManager: Killing 9371:com.samsung.svoice.sync/u0a43 (adj 15): DHA:empty #33
,05-19 09:21:53.691  3511  4847 D ActivityManager: cleanUpApplicationRecord -- 9371
,05-19 09:21:53.691  3511  4847 D ActivityManager: isAutoRunBlockedApp:: com.samsung.svoice.sync, Auto Run ON
,05-19 09:21:53.711 10107 10107 D TimaKeyStoreProvider: TimaSignature is unavailable
05-19 09:21:53.711 10107 10107 D ActivityThread: Added TimaKeyStore provider
,05-19 09:21:53.721  3511  4313 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{cf9b834 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e54587e 10107:com.samsung.android.scloud:contentsync/5009}
,05-19 09:21:53.741 10107 10107 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
05-19 09:21:53.741 10107 10107 D RelationGraph: garbageCollect()
,05-19 09:21:53.741 10107 10107 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.samsung.android.scloud
,05-19 09:21:53.741  3511  4451 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-19 09:21:53.741 10107 10107 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-19 09:21:53.751 10107 10107 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 09:21:53.751 10107 10107 I InjectionManager: Inside getClassLibPath caller 
,05-19 09:21:53.761 10107 10107 W System  : ClassLoader referenced unknown path: /system/priv-app/SamsungCloud/lib/arm64
,05-19 09:21:53.811 10107 10107 I [SC]CloudManager: requestInit
,05-19 09:21:53.841 10107 10107 I [SC]Utils: folder : cachecreate fail, try again.
05-19 09:21:53.841 10107 10107 I [SC]Utils: folder : cache create fail.
05-19 09:21:53.841 10107 10107 I [SC]Utils: folder : thumbnailcreate fail, try again.
05-19 09:21:53.841 10107 10107 I [SC]Utils: folder : thumbnail create fail.
,05-19 09:21:53.841 10107 10107 I [SC]Utils: folder : sharecreate fail, try again.
05-19 09:21:53.851 10107 10107 I [SC]Utils: folder : share create fail.
05-19 09:21:53.851 10107 10107 I [SC]Utils: folder : scratchcreate fail, try again.
05-19 09:21:53.851 10107 10107 I [SC]Utils: folder : scratch create fail.
,05-19 09:21:53.851 10107 10107 I [SC]Utils: folder : eventSynccreate fail, try again.
05-19 09:21:53.851 10107 10107 I [SC]Utils: folder : eventSync create fail.
,05-19 09:21:53.881 10107 10107 V SamsungCloudLogs:  set Log level [4->4]act[false]
,05-19 09:21:53.881 10107 10107 I [SC]CommonUtil: isSemAvailable:0
,05-19 09:21:53.891 10107 10107 I [SC]SamsungCloudApp: AppVer[2.1.14][L:4]Sem[false]V21MAIN_R slog[false]com.samsung.android.scloud:contentsync
,05-19 09:21:53.891 10107 10107 D InjectionManager: InjectionManager
05-19 09:21:53.891 10107 10107 D InjectionManager: fillFeatureStoreMap com.samsung.android.scloud
05-19 09:21:53.891 10107 10107 I InjectionManager: Constructor com.samsung.android.scloud, Feature store :{}
05-19 09:21:53.891 10107 10107 I InjectionManager: featureStore :{}
,05-19 09:21:53.901 10107 10107 I [SC]FeatureManager: FeatureManager 
05-19 09:21:53.901 10107 10107 I [SC]FeatureManager: [SEC_FLOATING_FEATURE_SAMSUNGCLOUD_CONFIG_CLOUD_USAGE_MENU_TREE]str 
05-19 09:21:53.901 10107 10107 I [SC]FeatureManager: [SEC_FLOATING_FEATURE_SAMSUNGCLOUD_ENABLE_SETTING_MENU]bln true
,05-19 09:21:53.901 10107 10107 E [SC]SCLOUD_ERR-Utils: isShipMode : 1 
,05-19 09:21:53.901  3158  3678 D Netd    : Iface wlan0 link up
,05-19 09:21:53.901  9969  9969 I wpa_supplicant: nl80211: Received scan results (8 BSSes)
05-19 09:21:53.901  3511  3604 D Tethering: interfaceLinkStateChanged wlan0, true
05-19 09:21:53.901  3511  3604 D Tethering: interfaceStatusChanged wlan0, true
,05-19 09:21:53.901  9969  9969 I wpa_supplicant: autoscan_samsung_exponential_notify_scan : scan_interval = 8
,05-19 09:21:53.901  9969  9969 I wpa_supplicant: autoscan: autoscan_notify_scan, scan_interval = 8
05-19 09:21:53.901  9969  9969 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
05-19 09:21:53.911  4867  4880 D PdnController: Interface Changed wlan0 link up
05-19 09:21:53.911  9969  9969 I wpa_supplicant:    allow  - level is under -85dBm [-31] or selected nid [-1] [0]
05-19 09:21:53.911  9969  9969 I wpa_supplicant:  selected from pick network BSS F4.99.3E ssid='NG700' et= 090,gp=03,cu=987654321,sc=987654321
05-19 09:21:53.911  9969  9969 I wpa_supplicant:    allow  - level is under -85dBm [-31] or selected nid [-1] [0]
05-19 09:21:53.911 10107 10107 I [SC]DetectorReceiver: onReceive [android.net.conn.CONNECTIVITY_CHANGE]
,05-19 09:21:53.911 10107 10107 I [SC]CloudManager: requestInit
05-19 09:21:53.911  9969  9969 I wpa_supplicant: wlan0: Trying to associate with f4:f2:6d:22:99:3e (SSID='NG700' freq=2442 MHz level=-31) 
05-19 09:21:53.911 10107 10107 I [SC]Utils: folder : cachecreate fail, try again.
05-19 09:21:53.911 10107 10107 I [SC]Utils: folder : cache create fail.
05-19 09:21:53.911 10107 10107 I [SC]Utils: folder : thumbnailcreate fail, try again.
,05-19 09:21:53.911 10107 10107 I [SC]Utils: folder : thumbnail create fail.
05-19 09:21:53.911 10107 10107 I [SC]Utils: folder : sharecreate fail, try again.
05-19 09:21:53.911 10107 10107 I [SC]Utils: folder : share create fail.
05-19 09:21:53.911 10107 10107 I [SC]Utils: folder : scratchcreate fail, try again.
,05-19 09:21:53.911 10107 10107 I [SC]Utils: folder : scratch create fail.
05-19 09:21:53.911 10107 10107 I [SC]Utils: folder : eventSynccreate fail, try again.
,05-19 09:21:53.911 10107 10107 I [SC]Utils: folder : eventSync create fail.
,05-19 09:21:53.931  9138  9148 I SA      : [SCU] isHaveSA() - false
,05-19 09:21:53.931  9138  9148 I SA      : [OCP] Samsung account is not Signed-in
,05-19 09:21:53.931  9138  9148 I SA      : [OCP] Delete DB (TNC data)
,05-19 09:21:53.941 10107 10107 I [SC]CommonUtil: Samsung Account Not Logged in
,05-19 09:21:53.941  3511  3857 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
05-19 09:21:53.941  3511  3511 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.SCAN_RESULTS
,05-19 09:21:53.951  3511  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8d97e8a u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a4d5f6 3939:com.android.systemui/u0a65}
05-19 09:21:53.951  3511  4070 D ActivityManager:  getDeferredInfo final delay 0
,05-19 09:21:53.951  3511  4343 I ActivityManager: Killing 9429:com.samsung.android.provider.shootingmodeprovider/u0a60 (adj 15): DHA:empty #33
,05-19 09:21:53.991 10121 10121 E Zygote  : v2
05-19 09:21:53.991 10121 10121 I libpersona: KNOX_SDCARD checking this for 5011
05-19 09:21:53.991 10121 10121 I libpersona: KNOX_SDCARD not a persona
,05-19 09:21:53.991 10121 10121 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-19 09:21:54.001  3511  4070 I ActivityManager: Start proc 10121:com.samsung.android.coreapps/5011 for broadcast-5 com.samsung.android.coreapps/.easysignup.receiver.NetworkStateListener
05-19 09:21:54.001 10121 10121 E Zygote  : accessInfo : 0
,05-19 09:21:54.001 10121 10121 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.coreapps 
,05-19 09:21:54.011  9969  9969 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,05-19 09:21:54.011  9689  9689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-19 09:21:54.011  3158  3678 D Netd    : Iface wlan0 link up
05-19 09:21:54.011  3158  3678 D Netd    : Iface wlan0 link up
05-19 09:21:54.011  3158  3678 D Netd    : Iface wlan0 link up
05-19 09:21:54.011  3511  3604 D Tethering: interfaceLinkStateChanged wlan0, true
05-19 09:21:54.011  3511  3604 D Tethering: interfaceStatusChanged wlan0, true
,05-19 09:21:54.011  4867  5179 D PdnController: Interface Changed wlan0 link up
,05-19 09:21:54.011  3511  3604 D Tethering: interfaceLinkStateChanged wlan0, true
05-19 09:21:54.011  3511  3604 D Tethering: interfaceStatusChanged wlan0, true
,05-19 09:21:54.021  4867  5177 D PdnController: Interface Changed wlan0 link up
05-19 09:21:54.021  3511  3604 D Tethering: interfaceLinkStateChanged wlan0, true
05-19 09:21:54.021  3511  3604 D Tethering: interfaceStatusChanged wlan0, true
,05-19 09:21:54.021  4867  4881 D PdnController: Interface Changed wlan0 link up
05-19 09:21:54.021  9969  9969 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,05-19 09:21:54.021  9969  9969 I wpa_supplicant: wlan0: WPA: RX message 1 of 4-Way Handshake from F4.99.3E (ver=2)
,05-19 09:21:54.021  9969  9969 I wpa_supplicant: wlan0: WPA: Sending EAPOL-Key 2/4
,05-19 09:21:54.021  3511  4422 D ActivityManager: cleanUpApplicationRecord -- 9429
05-19 09:21:54.021  3511  4422 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.provider.shootingmodeprovider, Auto Run ON
,05-19 09:21:54.031  3511  3857 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,05-19 09:21:54.031  9969  9969 I wpa_supplicant: wlan0: WPA: RX message 3 of 4-Way Handshake from F4.99.3E (ver=2)
,05-19 09:21:54.031  3511  3857 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,05-19 09:21:54.031 10121 10121 D TimaKeyStoreProvider: TimaSignature is unavailable
05-19 09:21:54.031 10121 10121 D ActivityThread: Added TimaKeyStore provider
,05-19 09:21:54.041  9969  9969 I wpa_supplicant: wlan0: WPA: Sending EAPOL-Key 4/4
,05-19 09:21:54.041  9689  9689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-19 09:21:54.041  9969  9969 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,05-19 09:21:54.041  9969  9969 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,05-19 09:21:54.041  9689  9689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
05-19 09:21:54.051  3158  3678 D Netd    : Iface wlan0 link up
05-19 09:21:54.051  9969  9969 I wpa_supplicant: Blacklist: Clear (temp) 
05-19 09:21:54.051  3511  3604 D Tethering: interfaceLinkStateChanged wlan0, true
05-19 09:21:54.051  3511  3604 D Tethering: interfaceStatusChanged wlan0, true
,05-19 09:21:54.051  4867  4880 D PdnController: Interface Changed wlan0 link up
,05-19 09:21:54.051  3511  3857 D WifiNative-wlan0: callSECApiVoid - ID [50]
,05-19 09:21:54.051  3511  4343 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{cf9b834 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1e51cfb 10121:com.samsung.android.coreapps/5011}
,05-19 09:21:54.061  3511  3857 V AlarmManager:  remove PendingIntent] PendingIntent{9c85850: PendingIntentRecord{3162a49 android broadcastIntent}}
,05-19 09:21:54.061  3511  3857 D WifiNetworkAgent: NetworkAgent: Registering NetworkAgent
,05-19 09:21:54.061  3511  3511 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
,05-19 09:21:54.061  3511  3511 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
05-19 09:21:54.061  3511  3857 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
05-19 09:21:54.061  3511  3866 D ConnectivityService: Got NetworkAgent Messenger
05-19 09:21:54.061  3511  3866 E ConnectivityService: updateNetworkInfo()
05-19 09:21:54.061  3511  3866 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-19 09:21:54.061  3511  3511 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
05-19 09:21:54.061  3511  3866 D ConnectivityService: NetworkAgent connected
05-19 09:21:54.071  3511  3864 I WifiHs20Service: Message received 5007
05-19 09:21:54.071  3511  3511 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
,05-19 09:21:54.071  3158  3685 D CommandListener: Setting iface cfg
05-19 09:21:54.071 10121 10121 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,05-19 09:21:54.071 10121 10121 D RelationGraph: garbageCollect()
,05-19 09:21:54.071  3939  4163 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-19 09:21:54.071  4287  4287 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,05-19 09:21:54.081 10121 10121 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in com.samsung.android.coreapps rsrc of package com.samsung.android.coreapps
,05-19 09:21:54.081  3511  4451 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-19 09:21:54.081 10121 10121 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-19 09:21:54.081  3511  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9f760cf u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dcdc7f7 9957:com.sec.android.diagmonagent/1000}
05-19 09:21:54.081 10121 10121 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 09:21:54.081  3511  3857 D WifiStateMachine: Start Dhcp Watchdog 2
05-19 09:21:54.081  9957  9957 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
05-19 09:21:54.081  9957  9957 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
05-19 09:21:54.081  9957  9957 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
05-19 09:21:54.081  9957  9957 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,05-19 09:21:54.081  3511  3857 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,05-19 09:21:54.091 10121 10121 I InjectionManager: Inside getClassLibPath caller 
,05-19 09:21:54.091  3511  4847 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9f760cf u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ae2af57 6554:com.enhance.gameservice/u0a111}
,05-19 09:21:54.101 10121 10121 W System  : ClassLoader referenced unknown path: /system/app/CoreApps/lib/arm64
,05-19 09:21:54.101  9689  9689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-19 09:21:54.111  3511  4847 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9f760cf u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fdbb0cd 9972:com.sec.knox.switcher/1000}
,05-19 09:21:54.111  9972  9972 I usagelog: received in receiver
05-19 09:21:54.111  9972  9972 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
05-19 09:21:54.111  9972  9972 I KnoxUsageLogPro: premStatus:2
,05-19 09:21:54.111  9972  9972 I KnoxUsageLogPro: isEulaShown : false
05-19 09:21:54.111  9972  9972 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,05-19 09:21:54.111  3511  3857 D WifiNetworkAgent: NetworkAgent: NetworkAgent fully connected
05-19 09:21:54.111  3511  3866 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -20]
05-19 09:21:54.111  3511  3866 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,05-19 09:21:54.121  3939  4163 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
05-19 09:21:54.121 10121 10121 D CoreApps: SEC_LOG - true
05-19 09:21:54.121  3511  3866 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,05-19 09:21:54.131  3511  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9f760cf u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bf6ed82 9984:com.samsung.android.sm.policy/u0a142}
,05-19 09:21:54.171 10121 10121 E GooglePlayServicesUtil: The Google Play services resources were not found. Check your project configuration to ensure that the resources are included.
,05-19 09:21:54.221  3511  3857 E WifiNative-wlan0: do suspend false
,05-19 09:21:54.241  3511  3857 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
05-19 09:21:54.241  3511  3856 D WifiP2pService: InactiveState{ what=143375 }
,05-19 09:21:54.241  3511  3856 D WifiP2pService: P2pEnabledState{ what=143375 }
,05-19 09:21:54.251  9689  9689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-19 09:21:54.271 10147 10147 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,05-19 09:21:54.271 10147 10147 I dhcpcd  : version 5.5.6 starting
,05-19 09:21:54.281 10147 10147 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,05-19 09:21:54.341 10121 10121 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Epic_Common/SecMms_Epic_Common.apk / 1.0 running in com.samsung.android.coreapps rsrc of package com.android.mms
,05-19 09:21:54.341 10121 10121 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 09:21:54.341 10121 10121 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.samsung.android.coreapps rsrc of package com.google.android.talk
,05-19 09:21:54.351 10121 10121 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 09:21:54.351 10147 10147 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,05-19 09:21:54.351 10147 10147 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
05-19 09:21:54.351 10147 10147 I dhcpcd  : bssid match
,05-19 09:21:54.351 10147 10147 I dhcpcd  : wlan0: rebinding lease of 192.168.1.107
,05-19 09:21:54.361 10121 10121 D InjectionManager: InjectionManager
05-19 09:21:54.361 10121 10121 D InjectionManager: fillFeatureStoreMap com.samsung.android.coreapps
,05-19 09:21:54.361 10121 10121 I InjectionManager: Constructor com.samsung.android.coreapps, Feature store :{}
05-19 09:21:54.361 10121 10121 I InjectionManager: featureStore :{}
,05-19 09:21:54.421  3511  4451 D ActivityManager:  getDeferredInfo final delay 80
05-19 09:21:54.421  3511  4451 I ActivityManager: Killing 9246:com.samsung.android.sm.devicesecurity/5012 (adj 15): DHA:empty #33
,05-19 09:21:54.421 10147 10147 I dhcpcd  : wlan0: acknowledged 192.168.1.107 from 192.168.1.1
,05-19 09:21:54.441  3511  3984 D ActivityManager: cleanUpApplicationRecord -- 9246
,05-19 09:21:54.441  3511  3984 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sm.devicesecurity, Auto Run ON
,05-19 09:21:54.471 10147 10147 I dhcpcd  : wlan0: leased 192.168.1.107 for 172800 seconds
,05-19 09:21:54.471  3511  3866 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,05-19 09:21:54.501  3511  3597 D ActivityManager:  getDeferredInfo final delay 80
,05-19 09:21:54.581  3511  3597 D ActivityManager:  getDeferredInfo final delay 80
,05-19 09:21:54.661  3511  3597 D ActivityManager:  getDeferredInfo final delay 80
,05-19 09:21:54.741  3511  3597 D ActivityManager:  getDeferredInfo final delay 80
,05-19 09:21:54.821  3511  3597 D ActivityManager:  getDeferredInfo final delay 80
,05-19 09:21:54.861  3511  3856 D WifiP2pService: InactiveState{ what=143375 }
,05-19 09:21:54.861  3511  3856 D WifiP2pService: P2pEnabledState{ what=143375 }
,05-19 09:21:54.871  3511  3866 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,05-19 09:21:54.881  3511  3857 D WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,05-19 09:21:54.881  3511  3857 D WifiStateMachine: VerifyingLinkState enter
05-19 09:21:54.881  3511  3866 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -20], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -25]
,05-19 09:21:54.881  3511  3866 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 503]
05-19 09:21:54.881  3939  4163 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-19 09:21:54.901  3511  3511 D WifiNotificationController: SHOW_NOTI_MESSAGE : 9, visible : false, ssid : "NG700", targetSSID : null, netId : -1, titleType : -1
05-19 09:21:54.901  3511  3866 E ConnectivityService: updateNetworkInfo()
,05-19 09:21:54.901  4158  4169 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=17041883,extra=Bundle[mParcelledData.dataSize=84]
,05-19 09:21:54.901  4158  4158 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=17041883, samsung.notification.type=normal, samsung.people.package_name=android}]
,05-19 09:21:54.901  3511  3866 D ConnectivityService: Adding iface wlan0 to network 503
05-19 09:21:54.901  4158  4158 I PeopleStripeService: PeopleNotificationReceiver:3
05-19 09:21:54.901  4158  4158 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
05-19 09:21:54.901  4158  4158 I PeopleDataManager: removeNotification
,05-19 09:21:54.901  4158  4158 I NotificationParser: getNotiType:android,null
05-19 09:21:54.901  3511  3866 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}, oldLp = null
05-19 09:21:54.901  4158  4158 D PeopleDataManager: removeNotiInfo: id =17041883,packageName=android,isEdgeNotification=false,key=null,removeAll=false
05-19 09:21:54.901  4158  4158 D PeopleDataManager: removeNotiInfo =null
,05-19 09:21:54.911  3511  3511 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
,05-19 09:21:54.911  3511  3511 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,05-19 09:21:54.911  3511  3511 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
,05-19 09:21:54.921  3511  3511 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
05-19 09:21:54.911  3511  3864 I WifiHs20Service: Message received 5007
05-19 09:21:54.921  3511  3883 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
05-19 09:21:54.921  3511  3883 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}
05-19 09:21:54.921  3511  3883 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}
05-19 09:21:54.921  3511  3883 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}
05-19 09:21:54.921  3511  3883 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}
,05-19 09:21:54.921  3939  4163 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-19 09:21:54.931  4287  4287 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,05-19 09:21:54.941  3511  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4eeba92 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dcdc7f7 9957:com.sec.android.diagmonagent/1000}
05-19 09:21:54.941  3511  3597 D ActivityManager:  getDeferredInfo final delay 80
05-19 09:21:54.941  3511  3883 I WifiManager: isCaptivePortalException
,05-19 09:21:54.941  3511  3883 D WifiStateMachine: isPackageRunning - top:com.rockwellautomation.thalitest.MainActivity
05-19 09:21:54.941  3511  3883 D WifiStateMachine: isPackageRunning - top:com.rockwellautomation.thalitest.MainActivity
05-19 09:21:54.941  3511  3883 D WifiWatchdogStateMachine: 3Captive portal check should be processed whether SNS option is on or off.
05-19 09:21:54.941  3511  3883 D WifiWatchdogStateMachine.CaptivePortalHandler: [checkCaptivePortal] - callbackHandler=Handler (com.android.server.wifi.WifiWatchdogStateMachine$CaptivePortalHandler) {e2f0d5a}
05-19 09:21:54.941  3511  3883 I WifiManager: isCaptivePortalException
05-19 09:21:54.941  3511  3883 D WifiStateMachine: isPackageRunning - top:com.rockwellautomation.thalitest.MainActivity
05-19 09:21:54.941  3511  3883 D WifiStateMachine: isPackageRunning - top:com.rockwellautomation.thalitest.MainActivity
,05-19 09:21:54.941  9957  9957 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,05-19 09:21:54.951  9957  9957 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
05-19 09:21:54.951  9957  9957 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
,05-19 09:21:54.951  3511  3857 D WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to CONNECTED
,05-19 09:21:54.951  9957  9957 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,05-19 09:21:54.951  3511  3866 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 503
,05-19 09:21:54.951  3511  3866 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,05-19 09:21:54.961  3511  3857 D SecContentProvider: insert(), uri = 2
05-19 09:21:54.961  3511  3866 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
,05-19 09:21:54.961  3511  3866 E ConnectivityService: Unexpected mtu value: 0, wlan0
05-19 09:21:54.961  3511  3866 D ConnectivityService: Setting Dns servers for network 503 to [/192.168.1.1]
,05-19 09:21:54.971  3511  4459 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4eeba92 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ae2af57 6554:com.enhance.gameservice/u0a111}
,05-19 09:21:54.981  3511  3511 D WifiNotificationController: SHOW_NOTI_MESSAGE : 9, visible : false, ssid : "NG700", targetSSID : null, netId : -1, titleType : -1
05-19 09:21:54.981  4158  7351 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=17041883,extra=Bundle[mParcelledData.dataSize=84]
,05-19 09:21:54.981  4158  4158 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=17041883, samsung.notification.type=normal, samsung.people.package_name=android}]
05-19 09:21:54.981  4158  4158 I PeopleStripeService: PeopleNotificationReceiver:3
,05-19 09:21:54.981  4158  4158 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
05-19 09:21:54.981  4158  4158 I PeopleDataManager: removeNotification
05-19 09:21:54.981  4158  4158 I NotificationParser: getNotiType:android,null
05-19 09:21:54.981  4158  4158 D PeopleDataManager: removeNotiInfo: id =17041883,packageName=android,isEdgeNotification=false,key=null,removeAll=false
05-19 09:21:54.981  4158  4158 D PeopleDataManager: removeNotiInfo =null
,05-19 09:21:54.981  3511  3857 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
05-19 09:21:54.981  3511  3511 I WifiTrafficPoller: evaluateTrafficStatsPolling
05-19 09:21:54.981  3511  3511 D WifiNative-wlan0: callSECApiVoid - ID [212]
05-19 09:21:54.981  9969  9969 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
05-19 09:21:54.981  3511  3857 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
05-19 09:21:54.981  9969  9969 I wpa_supplicant: P2P: Current p2p state = IDLE
,05-19 09:21:54.991  3511  3511 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
05-19 09:21:54.991  3511  3511 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,05-19 09:21:54.991  3511  3511 D HS20StateMachine: SSID : "NG700"
05-19 09:21:54.991  3511  3511 D HS20StateMachine: NetId : 0
05-19 09:21:54.991  3511  3511 D HS20StateMachine: checkifOSUAP  null
,05-19 09:21:54.991  3511  3511 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
05-19 09:21:54.991  3511  3864 I WifiHs20Service: Message received 5007
05-19 09:21:54.991  3511  3511 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
,05-19 09:21:54.991  3939  4163 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
05-19 09:21:54.991  9969  9969 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,05-19 09:21:55.001  4287  4287 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE,
05-19 09:21:55.001  3511  4422 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
05-19 09:21:55.001  3511  3866 V NetworkStats: updateIfacesLocked()
05-19 09:21:55.001  3511  3866 D NtpTrustedTime: currentTimeMillis() cache hit
05-19 09:21:55.001  3511  3866 V NetworkStats: performPollLocked(flags=0x1)
,05-19 09:21:55.001  3511  4449 D SecContentProvider2: query(), uri = 15 selection = getToastGravityEnabledState
,05-19 09:21:55.001  3511  3866 D NetworkStatsRecorder: entry.iface is null
,05-19 09:21:55.001  3511  3866 D NetworkStatsRecorder: entry.iface is null
05-19 09:21:55.001  3511  3866 D NtpTrustedTime: currentTimeMillis() cache hit
05-19 09:21:55.001  3511  3866 D NetworkStatsRecorder: entry.iface is null
05-19 09:21:55.001  3511  3866 D NetworkStatsRecorder: entry.iface is null
,05-19 09:21:55.001  3511  3866 V NetworkStats: performPollLocked() took 6ms
,05-19 09:21:55.011  3511  4185 D SecContentProvider2: query(), uri = 15 selection = getToastEnabledState
,05-19 09:21:55.011  3511  4451 D SecContentProvider2: query(), uri = 15 selection = getToastShowPackageNameState
,05-19 09:21:55.011  3511  4459 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4eeba92 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fdbb0cd 9972:com.sec.knox.switcher/1000}
05-19 09:21:55.011  9972  9972 I usagelog: received in receiver
,05-19 09:21:55.011  9972  9972 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
05-19 09:21:55.011  9972  9972 I KnoxUsageLogPro: premStatus:2
,05-19 09:21:55.011  9972  9972 I KnoxUsageLogPro: isEulaShown : false
05-19 09:21:55.011  9972  9972 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,05-19 09:21:55.031  3511  3597 D ActivityManager:  getDeferredInfo final delay 80
,05-19 09:21:55.051  3511  4459 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4eeba92 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bf6ed82 9984:com.samsung.android.sm.policy/u0a142}
,05-19 09:21:55.051  3939  4163 D ViewRootImpl: #1 mView = android.widget.LinearLayout{7b8111 V.E...... ......I. 0,0-0,0 #102039c android:id/toast_layout_root}
,05-19 09:21:55.061  3511  3866 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-19 09:21:55.061  3511  3866 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -25]
,05-19 09:21:55.061  3511  3855 D NtpTrustedTime: currentTimeMillis() cache hit
05-19 09:21:55.061  3511  3855 D NtpTrustedTime: currentTimeMillis() cache hit
05-19 09:21:55.061  3511  3866 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
05-19 09:21:55.061  3511  3866 D ConnectivityService: Not required to send intent.
05-19 09:21:55.061  3511  3866 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = CONNECTING
05-19 09:21:55.061  3511  3866 E ConnectivityService: updateNetworkInfo()
05-19 09:21:55.061  3511  3866 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -25]
05-19 09:21:55.061  3511  3866 D NtpTrustedTime: currentTimeMillis() cache hit
05-19 09:21:55.061  3511  3866 V NetworkStats: updateIfacesLocked()
05-19 09:21:55.061  3511  3866 V NetworkStats: performPollLocked(flags=0x1)
,05-19 09:21:55.061  3939  3939 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 272
,05-19 09:21:55.061  3511  3866 D NetworkStatsRecorder: entry.iface is null
05-19 09:21:55.061  3511  3866 D NetworkStatsRecorder: entry.iface is null
05-19 09:21:55.061  3511  3866 D NetworkStatsRecorder: entry.iface is null
05-19 09:21:55.061  3511  3866 D NetworkStatsRecorder: entry.iface is null
05-19 09:21:55.061  3511  3866 D NtpTrustedTime: currentTimeMillis() cache hit
05-19 09:21:55.061  3511  3866 V NetworkStats: performPollLocked() took 7ms
,05-19 09:21:55.071  3511  4459 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a667060 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dcdc7f7 9957:com.sec.android.diagmonagent/1000}
,05-19 09:21:55.071  9957  9957 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,05-19 09:21:55.071  9957  9957 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
05-19 09:21:55.071  9957  9957 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
,05-19 09:21:55.071  3511  3984 D ISSUE_DEBUG: InputChannelName : 439edde Toast
05-19 09:21:55.071  9957  9957 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 android.content.ContextWrapper.sendBroadcast:410 android.content.ContextWrapper.sendBroadcast:410 com.sec.android.diagmonagent.DiagMonConnectivityChangeReciever.onReceive:19 android.app.ActivityThread.handleReceiver:3635 
05-19 09:21:55.071  3511  3984 V MARsPolicyManager: handelAlertToastWindowStarted pkgName = com.android.systemui
,05-19 09:21:55.081  3511  3866 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-19 09:21:55.081  3511  3866 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -25]
,05-19 09:21:55.081  3511  3855 D NtpTrustedTime: currentTimeMillis() cache hit
05-19 09:21:55.081  3511  3866 D ConnectivityService: scheduleUnvalidatedPrompt 503
05-19 09:21:55.081  3511  3857 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
05-19 09:21:55.081  3511  3866 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 503]
05-19 09:21:55.081  3511  3855 D NtpTrustedTime: currentTimeMillis() cache hit
05-19 09:21:55.081  3511  3866 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
05-19 09:21:55.081  3511 10133 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
,05-19 09:21:55.081  3511  3866 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -25]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
05-19 09:21:55.081  3511 10133 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: Connected
05-19 09:21:55.081  3511 10133 D NetworkMonitor: registerReceiver Captive portal receiver
05-19 09:21:55.081  3511  3857 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,05-19 09:21:55.091  3014  3014 I SurfaceFlinger: id=20 createSurf (1x1),1 flag=4, Uoast
,05-19 09:21:55.101  3511  4313 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a667060 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ae2af57 6554:com.enhance.gameservice/u0a111}
,05-19 09:21:55.101  3511  3866 D ConnectivityService:   checking if request is: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: true
,05-19 09:21:55.101  3511 10133 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,05-19 09:21:55.101  3511 10133 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: Validated
05-19 09:21:55.111  3511  3866 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,05-19 09:21:55.111  4287  4542 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
05-19 09:21:55.111  4287  4542 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
05-19 09:21:55.111  3511  3866 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,05-19 09:21:55.111  3511  3866 D ConnectivityService: currentScore = 0, newScore = 20
05-19 09:21:55.111  3511  3892 D Ethernet: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 09:21:55.111  3511  3866 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 503]
05-19 09:21:55.111  3511  3857 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 09:21:55.111  3511  3866 D ConnectivityService:    accepting network in place of null
,05-19 09:21:55.111  3511  3892 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
05-19 09:21:55.111  3511  3866 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 09:21:55.111  3511  3857 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-19 09:21:55.111  3511  3892 D Ethernet: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
05-19 09:21:55.111  3511  3892 D Ethernet: evalRequest
05-19 09:21:55.111  3511  3857 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
05-19 09:21:55.111  3511  3892 D Ethernet:   done
05-19 09:21:55.111  3511  3857 D WIFI    : evalRequest
05-19 09:21:55.111  3511  3857 D WIFI    :   done
05-19 09:21:55.111  3511  3856 D WIFI_P2P: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 09:21:55.111  3511  3857 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 09:21:55.111  3511  3856 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-19 09:21:55.111  3511  3857 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-19 09:21:55.111  3511  3856 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
05-19 09:21:55.111  3511  3857 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
05-19 09:21:55.111  3511  3856 D WIFI_P2P: evalRequest
05-19 09:21:55.111  3511  3857 D WIFI    : evalRequest
05-19 09:21:55.111  3511  3856 D WIFI_P2P:   done
05-19 09:21:55.111  3511  3857 D WIFI    :   done
05-19 09:21:55.111  3511  3857 D WIFI_UT : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-19 09:21:55.111  3511  3857 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-19 09:21:55.111  3511  3857 D WIFI_UT : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
05-19 09:21:55.111  3511  3857 D WIFI_UT : evalRequest
05-19 09:21:55.111  3511  3857 D WIFI_UT :   done
,05-19 09:21:55.121  3511  4343 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3511
05-19 09:21:55.121  3511  4343 D PowerManagerService: mDisplayReady: false
,05-19 09:21:55.121  3511  3654 D DisplayPowerController: animateScreenStateChange[0]: target=2
05-19 09:21:55.121  3511  3654 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
05-19 09:21:55.121  3511  3654 D DisplayPowerController: getFinalBrightness : Summary is 40 -> 40
05-19 09:21:55.121  3511  3903 D lights  : lcd : 40 +
05-19 09:21:55.121  3511  3654 D SettingsProvider: isChangeAllowed() : name = brightness_pms_marker_screen
05-19 09:21:55.121  3511  3654 D DisplayPowerController: Tracking Direct to etc : 40
05-19 09:21:55.121  3511  3654 D DisplayPowerController: Animating brightness: target=40, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
05-19 09:21:55.121  3511  3654 D DisplayPowerController: animateScreenStateChange[0]: target=2
05-19 09:21:55.121  3511  3654 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
05-19 09:21:55.121  3511  3654 D DisplayPowerController: getFinalBrightness : Summary is 40 -> 40
,05-19 09:21:55.121  3511  3654 D DisplayPowerController: Animating brightness: target=40, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
05-19 09:21:55.121  3511  3654 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
05-19 09:21:55.121  3511  3654 D PowerManagerService: mDisplayReady: true
,05-19 09:21:55.121  3511  3597 D ActivityManager:  getDeferredInfo final delay 380
,05-19 09:21:55.131  3511  3852 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a667060 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fdbb0cd 9972:com.sec.knox.switcher/1000}
,05-19 09:21:55.131  9972  9972 I usagelog: received in receiver
05-19 09:21:55.131  9972  9972 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
05-19 09:21:55.131  9972  9972 I KnoxUsageLogPro: premStatus:2
05-19 09:21:55.131  3511  3866 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-19 09:21:55.131  9972  9972 I KnoxUsageLogPro: isEulaShown : false
05-19 09:21:55.131  9972  9972 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,05-19 09:21:55.141  3511  3903 D lights  : lcd : 40 -
05-19 09:21:55.141  3511  3903 D DisplayPowerState: Tracking!!: 40
,05-19 09:21:55.141  3511  3903 D SettingsProvider: isChangeAllowed() : name = brightness_pms_marker_screen
,05-19 09:21:55.141  3511  3654 D DisplayPowerController: animateScreenStateChange[0]: target=2
05-19 09:21:55.141  3511  3654 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
05-19 09:21:55.141  3511  3654 D DisplayPowerController: getFinalBrightness : Summary is 40 -> 40
05-19 09:21:55.141  3511  3654 D DisplayPowerController: Animating brightness: target=40, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,05-19 09:21:55.151  3939  4143 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1033x201]-format:1
,05-19 09:21:55.151  3511  3866 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,05-19 09:21:55.151  3511  3866 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-19 09:21:55.151  3939  4163 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,05-19 09:21:55.151  3511  3528 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a667060 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bf6ed82 9984:com.samsung.android.sm.policy/u0a142}
,05-19 09:21:55.161  3939  4163 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,05-19 09:21:55.161  3511  3866 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-19 09:21:55.171  3511  4422 V WindowStateAnimator: Finishing drawing window Window{439edde u0 d0 Toast}: mDrawState=DRAW_PENDING
,05-19 09:21:55.171  3014  3014 D libEGL  : eglInitialize EGLDisplay = 0x7fccf80d78
,05-19 09:21:55.171  3511  3866 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-19 09:21:55.181  3511  3866 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,05-19 09:21:55.181  3511  3866 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -25]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
05-19 09:21:55.181  3511  3984 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{96fdab6 u0 com.sec.android.diagmonagent.intent.NETWORK_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dcdc7f7 9957:com.sec.android.diagmonagent/1000}
,05-19 09:21:55.181  9957  9957 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: com.sec.android.diagmonagent.intent.NETWORK_CHANGED
,05-19 09:21:55.181  9957  9957 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
05-19 09:21:55.181  9957  9957 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(67/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,05-19 09:21:55.211  3158  3685 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,05-19 09:21:55.231  3158  3685 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,05-19 09:21:55.241  3511  3866 D ConnectivityService: 503 network ip type : v4
,05-19 09:21:55.241  3511  3866 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 09:21:55.241  3511  3866 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-19 09:21:55.241  3511  3866 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-19 09:21:55.251  3511  3866 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-19 09:21:55.251  3511  3866 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=5, legacyType=-1, [] ]
,05-19 09:21:55.251  3511  3866 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -25]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} } for legacy network type 1
,05-19 09:21:55.251  3511  3866 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
,05-19 09:21:55.251  3511  3887 D WifiWatchdogStateMachine.CaptivePortalHandler: start check captive portal 
,05-19 09:21:55.251  3511  3866 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,05-19 09:21:55.261  3511  3647 D EntConnectivity: Not allowed due to - mEnabled false
,05-19 09:21:55.261  3511  4459 D ConnectivityService: getVpnConfig > userId : 0
,05-19 09:21:55.261  3511  3866 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
05-19 09:21:55.261  3511  3647 D EntConnectivity: Not allowed due to - mEnabled false
05-19 09:21:55.261  3511  3866 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -25]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
05-19 09:21:55.261  3511  3866 D ConnectivityService: unneeded: NetworkRequestInfo for = Request from uid/pid:1000/3511 for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 09:21:55.261  3511  3866 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
05-19 09:21:55.261  3511  3866 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 09:21:55.261  3511  3866 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 09:21:55.261  3511  3866 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 09:21:55.261  3511  3866 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
05-19 09:21:55.261  3511  3866 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=5, legacyType=-1, [] ]
,05-19 09:21:55.271  3511  3866 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-19 09:21:55.271  3511  3866 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-19 09:21:55.271  3511  3866 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-19 09:21:55.271  3511  3511 D Tethering: Tethering got CONNECTIVITY_ACTION
05-19 09:21:55.271  3511  3866 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 09:21:55.271  3511  3647 D Tethering: MasterInitialState.processMessage what=3
05-19 09:21:55.271  3511  3511 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
05-19 09:21:55.271  3511  3511 I CLocInfoService: ['16.5] External Intent Received android.net.conn.CONNECTIVITY_CHANGE
,05-19 09:21:55.271  3511  3511 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
05-19 09:21:55.271  3511  3511 I CLocInfoService: CLocinfo wifi true 
05-19 09:21:55.271  3511  3866 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 09:21:55.281  3511  3866 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-19 09:21:55.281  3511  3866 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
05-19 09:21:55.281  3511  3866 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] validation  passed
05-19 09:21:55.281  3511  3866 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -25], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -25]
,05-19 09:21:55.281  3511  3866 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
05-19 09:21:55.281  3511  3866 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -25]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,05-19 09:21:55.281  4158  4169 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=503,extra=Bundle[mParcelledData.dataSize=84]
05-19 09:21:55.281  4158  4158 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=503, samsung.notification.type=normal, samsung.people.package_name=android}]
05-19 09:21:55.281  4158  4158 I PeopleStripeService: PeopleNotificationReceiver:3
05-19 09:21:55.281  4158  4158 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
05-19 09:21:55.281  4158  4158 I PeopleDataManager: removeNotification
,05-19 09:21:55.281  4158  4158 I NotificationParser: getNotiType:android,null
05-19 09:21:55.281  4158  4158 D PeopleDataManager: removeNotiInfo: id =503,packageName=android,isEdgeNotification=false,key=null,removeAll=false
05-19 09:21:55.281  4158  4158 D PeopleDataManager: removeNotiInfo =null
05-19 09:21:55.281  3511  3868 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,05-19 09:21:55.281  3939  4163 D NetworkController: onReceive: intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
05-19 09:21:55.281  4287  4297 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,05-19 09:21:55.281  4287  4297 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,05-19 09:21:55.291  3511  3868 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,05-19 09:21:55.291  3511  3589 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,05-19 09:21:55.291  3511  3589 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,05-19 09:21:55.291  3511  3589 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,05-19 09:21:55.291  3511  4238 V AlarmManager:  remove PendingIntent] PendingIntent{f635ff1: PendingIntentRecord{9f177d6 android broadcastIntent}}
,05-19 09:21:55.311  3511  3866 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
,05-19 09:21:55.311  3511  3511 V MARsPolicyManager: DataConnection: true
,05-19 09:21:55.321  4867  4972 D CellLocationSupport: onReceive ACTION = android.net.conn.CONNECTIVITY_CHANGE
05-19 09:21:55.321  4867  4972 I CellLocationSupport: onCellLocationChanged
,05-19 09:21:55.321  4917  4917 D SamsungIME: EngineType = SWIFTKEY
,05-19 09:21:55.321  3511  3855 D NtpTrustedTime: currentTimeMillis() cache hit
05-19 09:21:55.321  4917  4917 D SamsungIME: mNetworkChangeReceiver isWLANConnected : true
05-19 09:21:55.321  3511  3855 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-19 09:21:55.321  3511  3855 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -25]
05-19 09:21:55.321  3511  3855 D NtpTrustedTime: currentTimeMillis() cache hit
05-19 09:21:55.321  3511  3855 D NtpTrustedTime: currentTimeMillis() cache hit
,05-19 09:21:55.321  3511  3855 D NtpTrustedTime: currentTimeMillis() cache hit
05-19 09:21:55.321  3511  3855 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
,05-19 09:21:55.331  4867  4867 D PdnController: CONNECTIVITY_ACTION: networkType 1 isConnected true
05-19 09:21:55.331  4867  4867 D PdnController: isSuspended [false] networktype [1]
05-19 09:21:55.331  4867  4867 D PdnController: Updated Interface [wlan0] For Network [1]
,05-19 09:21:55.331  3511  4313 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,05-19 09:21:55.331  4867  4867 D PdnController: isPdnUp  [true] networktype [1]
05-19 09:21:55.331  4867  4867 D PdnController: Notify Result to LocalIP Registrants! : networkType [1] isConnected [true] 
,05-19 09:21:55.331  4287  4638 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,05-19 09:21:55.341  3511  3866 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
05-19 09:21:55.341  4867  4972 I CellLocationSupport: Block to update PANI information in non VoWIFI
05-19 09:21:55.341  4867  4972 D SlickSSConfigHandler: EVENT_LOCAL_IP_CHANGED
05-19 09:21:55.341  3511  4235 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-19 09:21:55.341  3511  4198 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:55.341  4867  4972 D PdnController: isIfaceDisconnected result [true] networkType [0] interfaceName [null] 
05-19 09:21:55.341  4867  4972 D PdnController: isPdnUp  [false] networktype [0]
05-19 09:21:55.341  4867  4972 D SlickSSConfigHandler: handleNetworkStateChange: check isDefaultPDNConnected[false], mReadyForDocFetch[false
05-19 09:21:55.341  5466  5466 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@70a607c and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-19 09:21:55.341  4287  4638 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,05-19 09:21:55.341  5466  5466 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
05-19 09:21:55.341  3511  3589 D TelephonyManager: getDataEnabled: retVal=true
,05-19 09:21:55.351  4867  4972 D RegistrationManager: handleMessage(): 5
,05-19 09:21:55.351  3511  3984 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-19 09:21:55.351  3511  4343 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
05-19 09:21:55.351  4867  4972 D PdnController: isIfaceDisconnected result [true] networkType [11] interfaceName [null] 
05-19 09:21:55.351  4867  4972 D PdnController: isPdnUp  [false] networktype [11]
05-19 09:21:55.351  4867  4972 D RegistrationManager: setEPDGIPSecConnected [false]
05-19 09:21:55.351  4867  4972 D RegistrationManager: notifyNetworkState : NetworkType [1] IsConnected [true] IPAddresses [[/192.168.1.107]] DNSAddresses [[/192.168.1.1]] 
05-19 09:21:55.351  4867  4972 D RegistrationManager: isEPDGAvailable [false]
05-19 09:21:55.351  4867  4972 D RegistrationManager: setWifiPreparedOnAPM [true]
,05-19 09:21:55.351  6953  6953 I FOTA_AGENT: [lIlIIlIlIlIllllllIII(91/llllIIIllIlIIIIllllI)] WiFi Network is connected
,05-19 09:21:55.361  3511  3529 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,05-19 09:21:55.361  4226  4226 D FusedRequestManager: manageLocationRequest, new passive request from com.samsung.voiceserviceplatform with c645900 , interval = 1800000 through LocationManagerService
,05-19 09:21:55.371  9387  9387 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 com.samsung.SMT.SamsungTTSService.g:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.c.onReceive:-1 
,05-19 09:21:55.371  3511  3866 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,05-19 09:21:55.381  3511  3866 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-19 09:21:55.391  3158  3681 D EnterpriseController: netId is 0
05-19 09:21:55.391  3158  3681 D Netd    : getNetworkForDns: using netid 503 for uid 10002
,05-19 09:21:55.391  4867  4972 D TranslatorCollection: translateToNwkSvcType: networkType XAN_NWK_TYPE_WLAN
05-19 09:21:55.391  4867  4972 D RegistrationManager: getNetworkType [0]
05-19 09:21:55.391  4867  4972 D CoreStackAdaptor2: notifyNetworkState() [1] isConnected [true] nwkSvcType  [XAN_NWK_TYPE_WLAN] nwkInfoType [XAN_SVC_NETWORK_SVCTYPE_WIFI] dedicated   [NONE] 
05-19 09:21:55.391  4867  4972 D CellLocationSupport: Siso Stack not called RegisterAN yet on XAN_NWK_TYPE_WLAN
05-19 09:21:55.391  4287  4542 D TelephonyProvider: query: url=content://telephony/carriers/preferapn, projectionIn=[Ljava.lang.String;@245c6c5, selection=nullselectionArgs=null, sort=name ASC
05-19 09:21:55.391  4454  4454 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
05-19 09:21:55.391  4867  4972 D TranslatorCollection: translateToNwkSvcType: networkType XAN_NWK_TYPE_WLAN
,05-19 09:21:55.391  4867  4972 D CoreStackAdaptor2: ipList Not Null[/192.168.1.107]
05-19 09:21:55.391  4867  4972 D RegistrationManager: tryRegister(CONNECTIVITY_STATUS_CHANGE)
05-19 09:21:55.391  4867  4972 D RegistrationManager: isPreconditionProperToGoOn
05-19 09:21:55.391  4867  4972 D RegistrationManager: isDeviceShutdown [false]
05-19 09:21:55.391  4867  4972 D RegistrationManager: isStackShuttingDownForAllPDNs [false]
05-19 09:21:55.391  4867  4972 D RegistrationManager: isDmVoLTEUpdated [false]
05-19 09:21:55.391  4867  4972 D RegistrationManager: tryRegister : Abort Reason [IMS feature disabled]
05-19 09:21:55.391  4867  4972 D RegistrationManager: tryRegister : Not all preconditions are met!
,05-19 09:21:55.401  9689  9689 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,05-19 09:21:55.411  3511  3866 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-19 09:21:55.411  4287  4542 D TelephonyProvider: query: match = 5
05-19 09:21:55.411  4287  4542 D TelephonyProvider: getPreferredApnId(subId = 2147483643),return -1
05-19 09:21:55.411  4287  4542 D TelephonyProvider: query: selection modified to edited!=2 and edited!=3 and edited!=5 and edited!=6
,05-19 09:21:55.421  4838  4838 E audit   : type=1400 msg=audit(1495178515.421:278): avc:  denied  { ioctl } for  pid=7150 comm="ChromiumNet" path="socket:[41156]" dev="sockfs" ino=41156 ioctlcmd=8b1b scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=udp_socket permissive=0
05-19 09:21:55.421  4838  4838 E audit   :  SEPF_SECMOBILE_6.0.1_0031
05-19 09:21:55.421  4838  4838 E audit   : type=1300 msg=audit(1495178515.421:278): arch=c00000b7 syscall=29 success=no exit=-13 a0=18 a1=8b1b a2=7f7d426cc8 a3=7f7d426c90 items=0 ppid=3182 pid=7150 auid=4294967295 uid=10072 gid=10072 euid=10072 suid=10072 fsuid=10072 egid=10072 sgid=10072 fsgid=10072 tty=(none) ses=4294967295 comm="ChromiumNet" exe="/system/bin/app_process64" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
05-19 09:21:55.421  4838  4838 E audit   : type=1327 msg=audit(1495178515.421:278): proctitle="com.google.android.googlequicksearchbox:search"
05-19 09:21:55.421  4838  4838 E audit   : type=1320 msg=audit(1495178515.421:278): 
05-19 09:21:55.421  4838  4838 E audit   : type=1400 msg=audit(1495178515.421:279): avc:  denied  { ioctl } for  pid=7150 comm="ChromiumNet" path="socket:[41157]" dev="sockfs" ino=41157 ioctlcmd=8b1b scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=udp_socket permissive=0
05-19 09:21:55.421  4838  4838 E audit   :  SEPF_SECMOBILE_6.0.1_0031
05-19 09:21:55.421  4838  4838 E audit   : type=1300 msg=audit(1495178515.421:279): arch=c00000b7 syscall=29 success=no exit=-13 a0=18 a1=8b1b a2=7f7d426cc8 a3=7f7d426c90 items=0 ppid=3182 pid=7150 auid=4294967295 uid=10072 gid=10072 euid=10072 suid=10072 fsuid=10072 egid=10072 sgid=10072 fsgid=10072 tty=(none) ses=4294967295 comm="ChromiumNet" exe="/system/bin/app_process64" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
05-19 09:21:55.421  4838  4838 E audit   : type=1327 msg=audit(1495178515.421:279): proctitle="com.google.android.googlequicksearchbox:search"
05-19 09:21:55.421  4838  4838 E audit   : type=1320 msg=audit(1495178515.421:279): 
,05-19 09:21:55.431  9689  9689 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,05-19 09:21:55.431  3511  3886 D WifiWatchdogStateMachine: response code : 204
,05-19 09:21:55.441  3511  3887 D WifiWatchdogStateMachine.CaptivePortalHandler: result = 0, mCaptivePortalCheckMode = 11, mCouldNotIdentifyCaptivePortalState = true
,05-19 09:21:55.451  3511  3866 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-19 09:21:55.451 10020 10030 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(86/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
,05-19 09:21:55.451 10020 10030 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(86/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
,05-19 09:21:55.461 10020 10030 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(43/llIIIIlllllIIllIIllI)] already Eula Agree
,05-19 09:21:55.461  9689  9689 D BluetoothAdapter: STATE_ON
,05-19 09:21:55.461  3511  3866 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
05-19 09:21:55.471 10020 10031 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(86/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
05-19 09:21:55.471  3511  3866 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
05-19 09:21:55.471 10020 10031 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(86/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
05-19 09:21:55.471  3511  3866 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -25]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
05-19 09:21:55.471 10020 10031 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(43/llIIIIlllllIIllIIllI)] already Eula Agree
05-19 09:21:55.471  3511  3866 D ConnectivityService: unneeded: NetworkRequestInfo for = Request from uid/pid:1000/3511 for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 09:21:55.471  3511  3866 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 503]
05-19 09:21:55.471  3511  3866 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 09:21:55.471  3511  3866 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 09:21:55.471  3511  3866 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 09:21:55.471  3511  3866 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
05-19 09:21:55.471  3511  3866 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=5, legacyType=-1, [] ]
,05-19 09:21:55.471  3511  3866 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-19 09:21:55.471  3511  3866 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-19 09:21:55.481  3511  3866 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 09:21:55.481  3511  3866 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-19 09:21:55.481  9689  9689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-19 09:21:55.481  9689  9689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-19 09:21:55.481  9689  9689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-19 09:21:55.481  9689  9689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-19 09:21:55.481  9689  9689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-19 09:21:55.481  9689  9689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-19 09:21:55.481  9689  9689 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-19 09:21:55.481  9689  9689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-19 09:21:55.481  9689  9689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,05-19 09:21:55.481  3511  3866 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 09:21:55.481  3511  3866 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-19 09:21:55.491  3511  3866 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 09:21:55.491  3511  3892 D Ethernet: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 09:21:55.491  3511  3892 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
05-19 09:21:55.491  3511  3892 D Ethernet: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
05-19 09:21:55.491  3511  3892 D Ethernet: evalRequest
05-19 09:21:55.491  3511  3892 D Ethernet:   done
05-19 09:21:55.491  3511  3857 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 09:21:55.491  3511  3857 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-19 09:21:55.491  3511  3857 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
05-19 09:21:55.491  3511  3857 D WIFI    : evalRequest
05-19 09:21:55.491  3511  3857 D WIFI    :   done
05-19 09:21:55.491  3511  3857 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 09:21:55.491  3511  3857 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-19 09:21:55.491  3511  3857 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
05-19 09:21:55.491  3511  3857 D WIFI    : evalRequest
05-19 09:21:55.491  3511  3857 D WIFI    :   done
05-19 09:21:55.491  3511  3857 D WIFI_UT : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 09:21:55.491  3511  3857 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-19 09:21:55.491  3511  3857 D WIFI_UT : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
05-19 09:21:55.491  3511  3857 D WIFI_UT : evalRequest
05-19 09:21:55.491  3511  3857 D WIFI_UT :   done
,05-19 09:21:55.491  3511  3856 D WIFI_P2P: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 09:21:55.491  3511  3866 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
05-19 09:21:55.491  3511  3856 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-19 09:21:55.491  3511  3856 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
05-19 09:21:55.491  3511  3856 D WIFI_P2P: evalRequest
05-19 09:21:55.491  3511  3856 D WIFI_P2P:   done
,05-19 09:21:55.501  9689  9689 D BluetoothAdapter: STATE_ON
,05-19 09:21:55.501  9689  9689 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,05-19 09:21:55.521 10194 10194 E Zygote  : v2
05-19 09:21:55.521 10194 10194 I libpersona: KNOX_SDCARD checking this for 1000
05-19 09:21:55.521 10194 10194 I libpersona: KNOX_SDCARD not a persona
,05-19 09:21:55.521 10194 10194 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-19 09:21:55.521 10194 10194 E Zygote  : accessInfo : 0
,05-19 09:21:55.531  3511  4343 I ActivityManager: Start proc 10194:com.sec.android.soagent/1000 for content provider com.sec.android.soagent/.log.MasterLogProvider
,05-19 09:21:55.531  3511  3857 D WifiNetworkAgent: NetworkAgent: CMD_REPORT_NETWORK_STATUS(VALID)
05-19 09:21:55.531  3511  3857 D WifiNetworkAgent: NetworkAgent: CMD_REPORT_NETWORK_STATUS(1)
,05-19 09:21:55.561 10194 10194 D TimaKeyStoreProvider: TimaSignature is unavailable
05-19 09:21:55.561 10194 10194 D ActivityThread: Added TimaKeyStore provider
,05-19 09:21:55.581  3511  3597 D ActivityManager:  getDeferredInfo final delay 300
,05-19 09:21:55.591  3511  3857 D WifiStateMachine: isPackageRunning - top:com.rockwellautomation.thalitest.MainActivity
05-19 09:21:55.591  3511  3857 D WifiStateMachine: isPackageRunning - top:com.rockwellautomation.thalitest.MainActivity
05-19 09:21:55.591  3939  4163 D NetworkController: onReceive: intent=Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
05-19 09:21:55.591  3511  3857 D WifiStateMachine: sendBroadcastForCaptivePortalNotLoginIcon : false
,05-19 09:21:55.591  3939  4163 D NetworkController: onReceive: intent=Intent { act=com.samsung.intent.action.WIFI_CAPTIVE_NOT_LOGIN flg=0x10 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
05-19 09:21:55.591  3939  4163 D NetworkController.WifiSignalController: updateWifiState : mCurrentState.wifiCaptiveNotLogin = false
,05-19 09:21:55.591  3511  3521 I art     : Background sticky concurrent mark sweep GC freed 167485(12MB) AllocSpace objects, 62(1240KB) LOS objects, 29% free, 35MB/50MB, paused 3.056ms total 113.710ms
,05-19 09:21:55.601  3511  3857 D WifiStateMachine: isPackageRunning - top:com.rockwellautomation.thalitest.MainActivity
05-19 09:21:55.601  3511  3857 D WifiStateMachine: isPackageRunning - top:com.rockwellautomation.thalitest.MainActivity
,05-19 09:21:55.601  3511  3589 E GpsLocationProvider: No APN found to select.
,05-19 09:21:55.611  3511  3589 D libgps  : agps_ril_update_network_state: Waiting for IPC connection...
05-19 09:21:55.621 10194 10194 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
05-19 09:21:55.621 10194 10194 D RelationGraph: garbageCollect()
,05-19 09:21:55.621 10194 10194 W ResourcesManager: getTopLevelResources: /system/priv-app/SOAgent/SOAgent.apk / 1.0 running in com.sec.android.soagent rsrc of package com.sec.android.soagent
,05-19 09:21:55.621  3511  3984 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-19 09:21:55.621 10194 10194 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-19 09:21:55.631 10194 10194 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 09:21:55.631 10194 10194 I InjectionManager: Inside getClassLibPath caller 
,05-19 09:21:55.641 10194 10194 W System  : ClassLoader referenced unknown path: /system/priv-app/SOAgent/lib/arm64
,05-19 09:21:55.661 10194 10194 D InjectionManager: InjectionManager
05-19 09:21:55.661 10194 10194 D InjectionManager: fillFeatureStoreMap com.sec.android.soagent
,05-19 09:21:55.661 10194 10194 I InjectionManager: Constructor com.sec.android.soagent, Feature store :{}
05-19 09:21:55.661 10194 10194 I InjectionManager: featureStore :{}
,05-19 09:21:55.691  3511  4449 I ActivityManager: Killing 8981:com.samsung.android.app.taskedge/u0a67 (adj 15): DHA:empty #33
,05-19 09:21:55.701  3511  4449 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{79572af u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8ab765d 9689:com.rockwellautomation.thalitest/u0a78}
,05-19 09:21:55.701  3511  4185 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:55.701  3511  4185 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
05-19 09:21:55.701  3511  4185 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:55.701  3511  4185 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:55.701  3511  4185 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:55.701  3511  4185 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:55.701  3511  4185 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:55.701  3511  4185 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:55.701  3511  4185 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:55.701  3511  4185 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:55.701  3511  4185 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:55.701  3511  4185 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:55.701  3511  4185 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:55.701  3511  4185 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 09:21:55.701  3511  4185 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-19 09:21:55.721  3511  4313 D ActivityManager: cleanUpApplicationRecord -- 8981
,05-19 09:21:55.721  3511  4313 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.taskedge, Auto Run ON
,05-19 09:21:55.741  3511  3984 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{79572af u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7c9839a 3511:system/1000}
,05-19 09:21:55.751  3511  3511 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{79572af u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{19a4389 4618:com.google.android.gms/u0a21}
,05-19 09:21:55.761  4618  4618 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,05-19 09:21:55.761  4618  5653 I iu.UploadsManager: num queued entries: 0
,05-19 09:21:55.761  4618  5653 I iu.UploadsManager: num updated entries: 0
,05-19 09:21:55.761  4618  5653 I iu.SyncManager: NEXT; no task
,05-19 09:21:55.771  3511  4847 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{79572af u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{19a4389 4618:com.google.android.gms/u0a21}
,05-19 09:21:55.791  3511  4847 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{79572af u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dc64001 4328:com.google.android.gms.persistent/u0a21}
,05-19 09:21:55.801  3511  4198 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{79572af u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{eaa5fce 10020:com.policydm/1000}
,05-19 09:21:55.801  3158  3681 D EnterpriseController: netId is 0
05-19 09:21:55.801  3158  3681 D Netd    : getNetworkForDns: using netid 503 for uid 10021
,05-19 09:21:55.821 10020 10020 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(574/IlIIIllllIIlIIIIIlII)] Initiated Type: 0
,05-19 09:21:55.821 10020 10020 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,05-19 09:21:55.831 10020 10020 I DBG_POLICYDM: [com.policydm.XDMService(585/llIlIllllllllllllllI)] get NotibarState : 0
,05-19 09:21:55.881  3511  3597 D ActivityManager:  getDeferredInfo final delay 300
,05-19 09:21:56.181  3511  3597 D ActivityManager:  getDeferredInfo final delay 0
,05-19 09:21:56.201  3511  3597 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{cf9b834 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1e51cfb 10121:com.samsung.android.coreapps/5011}
,05-19 09:21:56.231  3511  4198 D ActivityManager:  getDeferredInfo final delay 0
,05-19 09:21:56.241  3511  4198 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{cf9b834 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1e51cfb 10121:com.samsung.android.coreapps/5011}
,05-19 09:21:56.241  3511  3866 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,05-19 09:21:56.251  3511  4198 D ActivityManager:  getDeferredInfo final delay 0
,05-19 09:21:56.261  3511  4198 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{cf9b834 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1590928 5047:com.microsoft.skydrive/u0a130}
,05-19 09:21:56.271  9915  9915 D Babel   : RefCountedService(com.google.android.apps.hangouts.requestwriter.RequestWriter) onDestroy (count=0, startId=1 stopped=true)
,05-19 09:21:56.281  3511  3984 W IntentResolver: resolveIntent failed: found match, but none with CATEGORY_DEFAULT
,05-19 09:21:56.281  3511  4313 I ActivityManager: Killing 9443:com.samsung.android.themecenter/1000 (adj 15): DHA:empty #33
,05-19 09:21:56.291  3511  4313 D ActivityManager:  getDeferredInfo final delay 300
,05-19 09:21:56.301  3511  4198 D ActivityManager: cleanUpApplicationRecord -- 9443
05-19 09:21:56.301  3511  4198 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.themecenter, Auto Run ON
,05-19 09:21:56.581  3511  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{359c19a u0 com.google.android.gcm.CONNECTED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4af310a 9915:com.google.android.talk/u0a117}
,05-19 09:21:56.591  3511  3852 V AlarmManager:  remove PendingIntent] PendingIntent{d508acb: PendingIntentRecord{2c2faaf com.google.android.gms broadcastIntent}}
,05-19 09:21:56.621  3511  3589 D libgps  : agps_ril_update_network_state: Waiting for IPC connection - timeout
05-19 09:21:56.621  3511  3589 E libgps  : LIBGPS: Cannot communicate (write) with a GPSD
05-19 09:21:56.621  3511  3589 E libgps  : IPC Communication Error, ../../../../tmp/14982990_270314/allPartners/os/android/gps_interface/gpsi_client/GpsiClient.cpp:1710 agps_ril_update_network_state
05-19 09:21:56.621  3511  3589 D libgps  : agps_ril_update_network_availability: Waiting for IPC connection...
,05-19 09:21:56.651  3511  3597 D ActivityManager:  getDeferredInfo final delay 0
,05-19 09:21:56.661 10213 10213 E Zygote  : v2
05-19 09:21:56.661 10213 10213 I libpersona: KNOX_SDCARD checking this for 10135
05-19 09:21:56.661 10213 10213 I libpersona: KNOX_SDCARD not a persona
,05-19 09:21:56.671 10213 10213 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-19 09:21:56.671 10213 10213 E Zygote  : accessInfo : 0
05-19 09:21:56.671  3511  3597 I ActivityManager: Start proc 10213:com.google.android.apps.photos/u0a135 for broadcast-5 com.google.android.apps.photos/.actionqueue.SystemReceiver
05-19 09:21:56.671 10213 10213 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.photos 
05-19 09:21:56.671  3511  3855 D NetworkPolicy: isUidForegroundLocked: 10135, mScreenOn: true, uidstate: -1, mProxSensorScreenOff: false
,05-19 09:21:56.701 10213 10213 D TimaKeyStoreProvider: TimaSignature is unavailable
,05-19 09:21:56.701 10213 10213 D ActivityThread: Added TimaKeyStore provider
,05-19 09:21:56.721  3511  3529 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{cf9b834 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{99722a8 10213:com.google.android.apps.photos/u0a135}
,05-19 09:21:56.721  3511  3855 D NetworkPolicy: isUidForegroundLocked: 10135, mScreenOn: true, uidstate: 11, mProxSensorScreenOff: false
,05-19 09:21:56.741 10213 10213 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,05-19 09:21:56.741 10213 10213 D RelationGraph: garbageCollect()
,05-19 09:21:56.741 10213 10213 W ResourcesManager: getTopLevelResources: /system/app/Photos/Photos.apk / 1.0 running in com.google.android.apps.photos rsrc of package com.google.android.apps.photos
,05-19 09:21:56.741  3511  3852 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-19 09:21:56.741 10213 10213 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-19 09:21:56.751 10213 10213 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 09:21:56.751 10213 10213 I InjectionManager: Inside getClassLibPath caller 
,05-19 09:21:56.771 10213 10213 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm64
,05-19 09:21:57.001 10213 10213 W ResourcesManager: getTopLevelResources: /system/app/Photos/Photos.apk / 1.0 running in com.google.android.apps.photos rsrc of package com.google.android.apps.photos
,05-19 09:21:57.051  3939  4163 D ViewRootImpl: #3 mView = null
,05-19 09:21:57.061  3511  4070 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3511) eventTime = 222507
05-19 09:21:57.061  3511  4070 D PowerManagerService: [s] UserActivityState : 4 -> 1
05-19 09:21:57.061  3511  4070 D PowerManagerService: [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3511 (0x0)
05-19 09:21:57.061  3511  4070 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3511, ws=WorkSource{10065}) (elapsedTime=1946)
,05-19 09:21:57.121  3511  3866 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -25], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -24]
05-19 09:21:57.121  3511  3866 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
05-19 09:21:57.121  3511  3866 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -24]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,05-19 09:21:57.131  3939  4163 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-19 09:21:57.151  3511  3866 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
,05-19 09:21:57.161  3511  3866 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-19 09:21:57.171  3511  3866 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,05-19 09:21:57.171  3511  3866 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-19 09:21:57.171  3511  3866 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-19 09:21:57.191  3511  3866 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-19 09:21:57.191  3511  3866 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
05-19 09:21:57.191  3511  3866 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 503]
05-19 09:21:57.191  3511  3866 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 09:21:57.191  3511  3866 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 09:21:57.191  3511  3866 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 09:21:57.191  3511  3866 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
05-19 09:21:57.191  3511  3866 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=5, legacyType=-1, [] ]
05-19 09:21:57.191  3511  3866 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 09:21:57.191  3511  3866 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-19 09:21:57.191  3511  3866 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 09:21:57.191  3511  3866 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 09:21:57.201  3511  3866 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-19 09:21:57.201  3511  3866 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-19 09:21:57.241 10213 10213 D InjectionManager: InjectionManager
05-19 09:21:57.241 10213 10213 D InjectionManager: fillFeatureStoreMap com.google.android.apps.photos
,05-19 09:21:57.241 10213 10213 I InjectionManager: Constructor com.google.android.apps.photos, Feature store :{}
05-19 09:21:57.241 10213 10213 I InjectionManager: featureStore :{}
,05-19 09:21:57.251  3511  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{71f47f9 u0 com.google.android.apps.photos.actionqueue.INTERNAL_ACTION qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{99722a8 10213:com.google.android.apps.photos/u0a135}
05-19 09:21:57.251  3511  4847 D ActivityManager:  getDeferredInfo final delay 0
,05-19 09:21:57.271  3511  4847 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{cf9b834 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{99722a8 10213:com.google.android.apps.photos/u0a135}
,05-19 09:21:57.311  3511  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e8e659f u0 com.google.android.apps.photos.jobqueue.EXECUTE_JOBS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{99722a8 10213:com.google.android.apps.photos/u0a135}
,05-19 09:21:57.311  3511  3984 D ActivityManager:  getDeferredInfo final delay 300
,05-19 09:21:57.351  3511  4313 I ActivityManager: Killing 9456:com.samsung.android.scloud/5009 (adj 15): DHA:empty #33
,05-19 09:21:57.371  3511  4847 D ActivityManager: cleanUpApplicationRecord -- 9456
05-19 09:21:57.371  3511  4847 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.scloud, Auto Run ON
,05-19 09:21:57.401  4158  7351 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg com.google.android.apps.photos,id=10436,extra=Bundle[mParcelledData.dataSize=84]
05-19 09:21:57.401  4158  4158 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=10436, samsung.notification.type=normal, samsung.people.package_name=com.google.android.apps.photos}]
,05-19 09:21:57.401  4158  4158 I PeopleStripeService: PeopleNotificationReceiver:3
05-19 09:21:57.401  4158  4158 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
05-19 09:21:57.401  4158  4158 I PeopleDataManager: removeNotification
05-19 09:21:57.401  4158  4158 I NotificationParser: getNotiType:com.google.android.apps.photos,null
05-19 09:21:57.401  4158  4158 D PeopleDataManager: removeNotiInfo: id =10436,packageName=com.google.android.apps.photos,isEdgeNotification=false,key=null,removeAll=false
05-19 09:21:57.401  4158  4158 D PeopleDataManager: removeNotiInfo =null
,05-19 09:21:57.621  3014  3023 I SurfaceFlinger: id=20 Removed Uoast (11/13)
,05-19 09:21:57.621  3014  4312 I SurfaceFlinger: id=20 Removed Uoast (-2/13)
,05-19 09:21:57.621  3511  3589 D libgps  : agps_ril_update_network_availability: Waiting for IPC connection - timeout
05-19 09:21:57.621  3014  3014 D libEGL  : eglTerminate EGLDisplay = 0x7fccf80e98
05-19 09:21:57.631  3511  3589 E libgps  : LIBGPS: Cannot communicate (write) with a GPSD
05-19 09:21:57.631  3511  3589 E libgps  : IPC Communication Error, ../../../../tmp/14982990_270314/allPartners/os/android/gps_interface/gpsi_client/GpsiClient.cpp:1729 agps_ril_update_network_availability
,05-19 09:21:57.661  3511  3597 D ActivityManager:  getDeferredInfo final delay 0
,05-19 09:21:57.671  3511  3597 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{cf9b834 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b1c323c 4764:com.sec.android.daemonapp/u0a166}
,05-19 09:21:57.671  4764  4764 D [Weather Widget]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CFAAE09BFCA326403459399C53A4EE79DAC193CEB26509F8FF7498BE5251A746097407E81C28CD811D388C49D613C81F395B356AA489D29CB4C3BE983CCC84BA76AF507AA66A943348DF162DECA2A5A7DD]}
,05-19 09:21:57.671  4764  4764 D [Weather Widget]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CFE2E89F45594D9820F24D88E9AF210A78F9CD3967C07B6DE6AAB9923C4C53919020112019F4465EB3AA6FD266958B212E]}
,05-19 09:21:57.671  3511  4407 D ActivityManager:  getDeferredInfo final delay 0
,05-19 09:21:57.681  3511  4407 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{cf9b834 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{acfd302 7942:com.sec.android.app.samsungapps/u0a16}
,05-19 09:21:57.681  7942  7942 D [SAUI]  : NetworkStateReceiver::connected::recovered?false
,05-19 09:21:57.701  7942  7942 D [SAUI]  : Global::recovered::false
,05-19 09:21:57.701  3511  4847 D ActivityManager:  getDeferredInfo final delay 300
05-19 09:21:57.701  7942  7942 D [SAUI]  : AutoUpdateService::onStartCommand
05-19 09:21:57.701  7942  7942 D [SAUI]  : AutoUpdateService::runAutoUpdateManager
,05-19 09:21:57.701  7942  7942 D [SAUI]  : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,05-19 09:21:57.701  7942  7942 D [SAUI]  : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
,05-19 09:21:57.701  7942  7942 D [SA_INIT]: AutoUpdateManager ServiceInitializer startInitialize()
,05-19 09:21:57.711  7942 10242 D [SA_INIT]: createTaskForServiceInitialize()
,05-19 09:21:57.711  7942 10244 D [SA_INIT]: NetworkStateCheckUnit workImpl()
,05-19 09:21:57.711  7942 10244 D [SA_INIT]: NetworkStateCheckUnit result : 1
,05-19 09:21:57.711  7942  7942 V JOULE   : JOULELOG [main]  com.sec.android.app.joule.f Task [35, 8459992_0] [END] FINISHED
05-19 09:21:57.711  7942  7942 D [SA_INIT]: ServiceInitializer onInitializeResult() reuslt : true
05-19 09:21:57.711  7942  7942 D [SAUI]  : AutoUpdateManager:INITCHECK:onInitializeSuccess
,05-19 09:21:57.721  7942  7942 D [SAUI]  : AutoUpdateTriggerManager:IDLE:notifyNextTime
,05-19 09:21:57.721  7942  7942 D [SAUI]  : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,05-19 09:21:58.001  3511  3597 D ActivityManager:  getDeferredInfo final delay 300
,05-19 09:21:58.301  3511  3597 D ActivityManager:  getDeferredInfo final delay 0
,05-19 09:21:58.321 10246 10246 E Zygote  : v2
05-19 09:21:58.321 10246 10246 I libpersona: KNOX_SDCARD checking this for 1000
05-19 09:21:58.321 10246 10246 I libpersona: KNOX_SDCARD not a persona
,05-19 09:21:58.331 10246 10246 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-19 09:21:58.331 10246 10246 E Zygote  : accessInfo : 0
05-19 09:21:58.331  3511  3597 I ActivityManager: Start proc 10246:com.samsung.android.securitylogagent/1000 for broadcast-5 com.samsung.android.securitylogagent/.receivers.NetworkReceiver
,05-19 09:21:58.371 10246 10246 D TimaKeyStoreProvider: TimaSignature is unavailable
05-19 09:21:58.371  3511  4144 E Watchdog: !@Sync 7 [05-19 09:21:58.380]
05-19 09:21:58.371 10246 10246 D ActivityThread: Added TimaKeyStore provider
,05-19 09:21:58.391  3511  4070 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{aca9ce7 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ccfd31 10246:com.samsung.android.securitylogagent/1000}
,05-19 09:21:58.401 10246 10246 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
05-19 09:21:58.401 10246 10246 D RelationGraph: garbageCollect()
,05-19 09:21:58.411 10246 10246 W ResourcesManager: getTopLevelResources: /system/app/SecurityLogAgent/SecurityLogAgent.apk / 1.0 running in com.samsung.android.securitylogagent rsrc of package com.samsung.android.securitylogagent
,05-19 09:21:58.411  3511  4451 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-19 09:21:58.411 10246 10246 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-19 09:21:58.411 10246 10246 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 09:21:58.421 10246 10246 I InjectionManager: Inside getClassLibPath caller 
,05-19 09:21:58.421 10246 10246 W System  : ClassLoader referenced unknown path: /system/app/SecurityLogAgent/lib/arm64
,05-19 09:21:58.431 10246 10246 D InjectionManager: InjectionManager
,05-19 09:21:58.431 10246 10246 D InjectionManager: fillFeatureStoreMap com.samsung.android.securitylogagent
05-19 09:21:58.431 10246 10246 I InjectionManager: Constructor com.samsung.android.securitylogagent, Feature store :{}
05-19 09:21:58.431 10246 10246 I InjectionManager: featureStore :{}
,05-19 09:21:58.431 10246 10246 D SecurityLogAgent: NetworkReceiver : Network Change Receiver Is Called
05-19 09:21:58.431 10246 10246 D SecurityLogAgent: NetworkReceiver : Wifi_state is 3
,05-19 09:21:58.451 10246 10246 D SecurityLogAgent: KnoxConfiguration : Current State = 0
,05-19 09:21:58.451 10246 10246 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
05-19 09:21:58.451 10246 10246 D SecurityLogAgent: StateMachine : Initialized
05-19 09:21:58.451 10246 10246 D SecurityLogAgent: StateMachine : Changed Current State = 0
,05-19 09:21:58.451 10246 10246 D SecurityLogAgent: StateMachine : Current State = 0
,05-19 09:21:58.461  3511  3528 D ActivityManager:  getDeferredInfo final delay 0
,05-19 09:21:58.471  3511  3528 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{79572af u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{eaa5fce 10020:com.policydm/1000}
,05-19 09:21:58.471 10020 10020 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(51/onReceive)] RegistrationReceiver onReceive! action = android.net.conn.CONNECTIVITY_CHANGE
,05-19 09:21:58.511 10020 10020 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(87/llllIIIllIlIIIIllllI)] device register flag at setting DB : true
,05-19 09:21:58.521 10020 10020 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(96/onReceive)] Already device registered...
,05-19 09:21:58.531 10020 10020 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(87/llllIIIllIlIIIIllllI)] device register flag at setting DB : true
,05-19 09:21:58.541 10020 10020 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(342/lllIlIlIIIllIIlIllIl)] OMC not Supported model
,05-19 09:21:58.541 10020 10020 I DBG_POLICYDM: [IIIIlllIIIlIlllllIll(111/llIlIIIIlIIIIIlIlIII)] Polling time is vaild
,05-19 09:21:58.551 10020 10020 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(281/llIIIIlllllIIllIIllI)] Heartbeat settings is activated.
,05-19 09:21:58.551 10020 10020 I DBG_POLICYDM: [IIlllIIllIllIllIIlll(52/llllIIIllIlIIIIllllI)] Next heartbeat time:2017/05/23/13:22:44
,05-19 09:21:58.551 10020 10020 I DBG_POLICYDM: [IIlllIIllIllIllIIlll(55/llllIIIllIlIIIIllllI)] heartbeat time is vaild
,05-19 09:21:58.551  3511  4459 D ActivityManager:  getDeferredInfo final delay 0
,05-19 09:21:58.561  3511  4459 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{79572af u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5ae1b59 9138:com.osp.app.signin/u0a44}
,05-19 09:21:58.561  9138  9138 I SA      : [OR] onReceive log=[SA = 2.2.02-12 V = 23 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = pl_PL CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hero2lte P = hero2ltexx I = MMB29K M = SM-G935F OKLEFT false DIS MMB29K.G935FXXU1BPJG PSS = 5.460694751064798  ]
05-19 09:21:58.561  9138  9138 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
05-19 09:21:58.561  9138  9138 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,05-19 09:21:58.571  9138  9138 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,05-19 09:21:58.571  9138  9138 I SA      : [OR] == isSIMCardReady false ==
05-19 09:21:58.571  9138  9138 I SA      : [SCU] == networkStateCheck == true
,05-19 09:21:58.571  9138  9138 I SA      : [DM] getCountryCodeFromCSC : PL
05-19 09:21:58.571  9138  9138 I SA      : isChinaCountryCode : false
05-19 09:21:58.571  9138  9138 I SA      : [SCU] is ChinestModel Data Restricted   : false
05-19 09:21:58.571  9138  9138 I SA      : [OR] == networkStateCheck true ==
,05-19 09:21:58.581  9138  9138 I SA      : [OR] GetMyCountryZoneTask
,05-19 09:21:58.581  9138  9138 I SA      : [OR] onReceive END
05-19 09:21:58.581  3511  4070 D ActivityManager:  getDeferredInfo final delay 0
,05-19 09:21:58.581  9138 10259 I SA      : [SRS] prepareGetMyCountryZone
,05-19 09:21:58.581  3511  4070 I ActivityManager: Killing 9476:com.samsung.android.bbc.bbcagent/1000 (adj 15): DHA:empty #33
,05-19 09:21:58.591  3511  4070 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{79572af u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fba2792 6953:com.wssyncmldm/1000}
,05-19 09:21:58.591  9138 10259 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,05-19 09:21:58.601  9138 10259 I SA      : [SSP] query invoked
,05-19 09:21:58.601  9138 10259 I SA      : [TPMU] GetMccFromDB : null
05-19 09:21:58.601  9138 10259 I SA      : [SCU] getMccFromPreferece mcc = 260
05-19 09:21:58.601  9138 10259 I SA      : [LBE] isSupportCheckDomainRegion : true
05-19 09:21:58.601  9138 10259 I SA      : [TPM] isNoProxy(default) : true
,05-19 09:21:58.611  6953 10261 I FOTA_AGENT: [com.samsung.android.app.fotaclient.llIlIIIIlIIIIIlIlIII(87/llIIIIlllllIIllIIllI)] Nothing to do action: android.net.conn.CONNECTIVITY_CHANGE
,05-19 09:21:58.611  3511  4313 D ActivityManager: cleanUpApplicationRecord -- 9476
05-19 09:21:58.611  3511  4313 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.bbc.bbcagent, Auto Run ON
,05-19 09:21:58.641  3511  4451 D ActivityManager:  getDeferredInfo final delay 300
,05-19 09:21:58.741 10147 10147 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,05-19 09:21:58.851  9689  9753 I io.jxcore.node.IncomingSocketThreadTest: testRun
,05-19 09:21:58.851  9689 10262 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
05-19 09:21:58.851  9689 10262 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,05-19 09:21:58.861  3158  3681 D EnterpriseController: netId is 0
05-19 09:21:58.861  3158  3681 D Netd    : getNetworkForDns: using netid 503 for uid 10078
,05-19 09:21:58.861  9689 10264 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
05-19 09:21:58.861  9689 10264 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
05-19 09:21:58.861  9689 10264 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-19 09:21:58.861  9689 10264 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-19 09:21:58.861  9689 10262 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
05-19 09:21:58.861  9689 10262 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
05-19 09:21:58.861  9689 10262 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-19 09:21:58.861  9689 10266 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 241, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:21:58.861  9689 10266 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-19 09:21:58.861  9689 10266 D io.jxcore.node.StreamCopyingThread:  id: 77
05-19 09:21:58.861  9689 10262 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-19 09:21:58.861  9689 10264 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
05-19 09:21:58.861  9689 10262 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
05-19 09:21:58.861  9689 10267 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 243, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:21:58.861  9689 10267 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 09:21:58.861  9689 10267 D io.jxcore.node.StreamCopyingThread:  id: 78
05-19 09:21:58.861  9689 10269 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 244, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:21:58.861  9689 10269 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 09:21:58.861  9689 10269 D io.jxcore.node.StreamCopyingThread:  id: 78
05-19 09:21:58.861  9689 10269 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 244, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:21:58.861  9689 10269 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 09:21:58.861  9689 10269 D io.jxcore.node.StreamCopyingThread:  id: 78
05-19 09:21:58.861  9689 10269 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:21:58.861  9689 10269 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 09:21:58.861  9689 10269 D io.jxcore.node.StreamCopyingThread:  id: 78
05-19 09:21:58.861  9689 10269 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
05-19 09:21:58.861  9689 10269 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
05-19 09:21:58.861  9689 10269 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
05-19 09:21:58.861  9689 10269 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
05-19 09:21:58.861  9689 10269 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
05-19 09:21:58.861  9689 10269 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
05-19 09:21:58.861  9689 10267 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 243, thread name: OutgoingSocketThread/Sender): Socket closed
05-19 09:21:58.861  9689 10269 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 244, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:21:58.861  9689 10269 D io.jxcore.node.StreamCopyingThread:  Is in,comming connection: false.
05-19 09:21:58.861  9689 10269 D io.jxcore.node.StreamCopyingThread:  id: 78 .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
05-19 09:21:58.861  9689 10267 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 243, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:21:58.861  9689 10267 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 09:21:58.861  9689 10267 D io.jxcore.node.StreamCopyingThread:  id: 78 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
05-19 09:21:58.861  9689 10267 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
05-19 09:21:58.861  9689 10267 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
05-19 09:21:58.861  9689 10267 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 243, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:21:58.861  9689 10267 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 09:21:58.861  9689 10267 D io.jxcore.node.StreamCopyingThread:  id: 78 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
05-19 09:21:58.861  9689 10266 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 241, thread name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:21:58.861  9689 10266 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-19 09:21:58.861  9689 10266 D io.jxcore.node.StreamCopyingThread:  id: 77
05-19 09:21:58.861  9689 10266 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:21:58.861  9689 10266 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-19 09:21:58.861  9689 10266 D io.jxcore.node.StreamCopyingThread:  id: 77
05-19 09:21:58.861  9689 10266 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
05-19 09:21:58.861  9689 10266 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
05-19 09:21:58.861  9689 10266 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
05-19 09:21:58.861  9689 10266 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
05-19 09:21:58.861  9689 10266 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
05-19 09:21:58.861  9689 10266 I io.jxcore.node.IncomingSocketThread: The sending thread is done
05-19 09:21:58.861  9689 10266 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 241, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:21:58.861  9689 10266 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-19 09:21:58.861  9689 10266 D io.jxcore.node.StreamCopyingThread:  id: 77 .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
05-19 09:21:58.871  9689 10268 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 242, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:21:58.871  9689 10268 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-19 09:21:58.871  9689 10268 D io.jxcore.node.StreamCopyingThread:  id: 77
05-19 09:21:58.871  9689 10268 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 242, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:21:58.871  9689 10268 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-19 09:21:58.871  9689 10268 D io.jxcore.node.StreamCopyingThread:  id: 77
05-19 09:21:58.871  9689 10268 D io.jxcore.node.StreamCopyingThread: closeOutputStre,am. Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:21:58.871  9689 10268 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-19 09:21:58.871  9689 10268 D io.jxcore.node.StreamCopyingThread:  id: 77
05-19 09:21:58.871  9689 10268 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
05-19 09:21:58.871  9689 10268 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
05-19 09:21:58.871  9689 10268 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
05-19 09:21:58.871  9689 10268 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
05-19 09:21:58.871  9689 10268 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
05-19 09:21:58.871  9689 10268 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
05-19 09:21:58.871  9689 10268 I io.jxcore.node.IncomingSocketThread: Both threads are done, notifying the listener...
05-19 09:21:58.871  9689 10268 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 242, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:21:58.871  9689 10268 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-19 09:21:58.871  9689 10268 D io.jxcore.node.StreamCopyingThread:  id: 77 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
05-19 09:21:58.871  9138 10259 I SA_HTTPURLCONNECTION: [RC New] Execute method=[GET] start
05-19 09:21:58.881  9138 10259 I SA_HTTPURLCONNECTION: [RC New] Security=[true]
05-19 09:21:58.881  9138 10259 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
05-19 09:21:58.881  9138 10259 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
05-19 09:21:58.881  3158  3681 D EnterpriseController: netId is 0
05-19 09:21:58.881  3158  3681 D Netd    : getNetworkForDns: using netid 503 for uid 10044
,05-19 09:21:58.941  3511  3597 D ActivityManager:  getDeferredInfo final delay 0
,05-19 09:21:58.961  3511  3597 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{79572af u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{55f0a76 7126:com.samsung.fresco.logging/5015}
,05-19 09:21:58.971  3511  4847 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,05-19 09:21:58.971  3511  4070 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-19 09:21:58.971  3511  3852 D ActivityManager:  getDeferredInfo final delay 0
,05-19 09:21:58.981  3511  3852 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{79572af u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{59af32b 7448:com.sec.spp.push/u0a42}
,05-19 09:21:58.981  7448  7448 E SPPClientService: [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
05-19 09:21:58.981  7448  7448 E SPPClientService: [SystemStateMoniter] Current Time : 224427
,05-19 09:21:58.981  7448  7448 E SPPClientService: [SystemStateMoniter] No Connect : false
,05-19 09:21:58.991  3511  3852 D ActivityManager:  getDeferredInfo final delay 0
,05-19 09:21:59.001  3511  3852 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{79572af u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{40b0457 5011:android.process.media/u0a51}
,05-19 09:21:59.001  5011  5011 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,05-19 09:21:59.021  3511  4313 D ActivityManager:  getDeferredInfo final delay 300
,05-19 09:21:59.031  3158  3678 D Netd    : Iface wlan0 link up
,05-19 09:21:59.031  9969  9969 I wpa_supplicant: nl80211: Received scan results (26 BSSes)
,05-19 09:21:59.031  3511  3604 D Tethering: interfaceLinkStateChanged wlan0, true
05-19 09:21:59.031  3511  3604 D Tethering: interfaceStatusChanged wlan0, true
,05-19 09:21:59.031  3511  3982 D SecContentProvider2: query(), uri = 15 selection = getAppBlockDownloadState
,05-19 09:21:59.041  4867  5179 D PdnController: Interface Changed wlan0 link up
,05-19 09:21:59.041  3511  3856 D WifiP2pService: InactiveState{ what=147461 }
,05-19 09:21:59.041  3511  3856 D WifiP2pService: P2pEnabledState{ what=147461 }
05-19 09:21:59.041  3511  3856 D WifiP2pService: DefaultState{ what=147461 }
,05-19 09:21:59.071  3511  3511 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.SCAN_RESULTS
05-19 09:21:59.071  3511  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2d02784 u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a4d5f6 3939:com.android.systemui/u0a65}
,05-19 09:21:59.211  3511  3982 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-19 09:21:59.211  3511  3982 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4319, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-19 09:21:59.211  3511  3982 D BatteryService: online:4, current avg:-7, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:52
05-19 09:21:59.211  3511  3511 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-19 09:21:59.221  3511  3511 I MotionRecognitionService: Plugged
,05-19 09:21:59.221  3511  3511 D MotionRecognitionService:   cableConnection= 1
05-19 09:21:59.221  3511  3511 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,05-19 09:21:59.221  3511  3511 D MotionRecognitionService: skip setTransmitPower. 
,05-19 09:21:59.221  3511  3860 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-19 09:21:59.231  3939  3939 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,05-19 09:21:59.231  3939  3939 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-19 09:21:59.231  3939  3939 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
05-19 09:21:59.231  3939  3939 D KeyguardUpdateMonitor: handleBatteryUpdate
05-19 09:21:59.231  3939  3939 D PowerUI.Notification: There is no change about charging status, so return!
,05-19 09:21:59.241  4867  4867 D CommonServiceConfiguration: getStringValueSetting
,05-19 09:21:59.241  4867  4867 D BatteryMonitor: new battery level: 100
,05-19 09:21:59.241  9787  9787 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-19 09:21:59.241  9787  9827 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-19 09:21:59.261  3939  3939 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
05-19 09:21:59.261  3939  3939 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,05-19 09:21:59.321  3511  3597 D ActivityManager:  getDeferredInfo final delay 0
,05-19 09:21:59.331  3511  3597 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{79572af u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5bd6094 10054:com.samsung.android.SettingsReceiver/1000}
,05-19 09:21:59.341 10054 10054 E ActivityThread: Failed to find provider info for com.myscript.atk.rmc
,05-19 09:21:59.341  3511  4343 D ActivityManager:  getDeferredInfo final delay 0
,05-19 09:21:59.351  3511  4343 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{79572af u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8083a39 10088:com.samsung.android.themestore/u0a68}
,05-19 09:21:59.351 10088 10088 D AutoSelfUpgradeReceiver: onReceive() android.net.conn.CONNECTIVITY_CHANGE
,05-19 09:21:59.371  3511  4451 D ActivityManager:  getDeferredInfo final delay 300
,05-19 09:21:59.381 10088 10088 D AutoSelfUpgradeService: onCreate() 
,05-19 09:21:59.391 10088 10088 D AutoSelfUpgradeService: onStartCommand() action.selfupgrade.via.net
,05-19 09:21:59.391 10088 10273 D AutoSelfUpgradeService: startInitAutoSelfUpdate()
,05-19 09:21:59.391 10088 10273 D AutoSelfUpgradeService: getAlarmIntent() 
,05-19 09:21:59.401 10088 10273 D AutoSelfUpgradeService: isAlarmActivated() true
,05-19 09:21:59.401 10088 10088 D AutoSelfUpgradeService: onDestroy()
,05-19 09:21:59.701  9138 10259 I SA_HTTPURLCONNECTION: [RC New] [v2liruge] api execute + 821
,05-19 09:21:59.711  9138 10259 I SA      : [ODM] saveOpenData( GEO_IP, PL )
,05-19 09:21:59.721  9138 10259 I SA      : [OCP] update openData : PL
,05-19 09:21:59.731  9138 10259 I SA      : [TPMU] getNetworkMcc : 
,05-19 09:21:59.741  3511  3597 D ActivityManager:  getDeferredInfo final delay 0
,05-19 09:21:59.761  3511  3597 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{79572af u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e54587e 10107:com.samsung.android.scloud:contentsync/5009}
,05-19 09:21:59.761 10107 10107 I [SC]DetectorReceiver: onReceive [android.net.conn.CONNECTIVITY_CHANGE]
05-19 09:21:59.761 10107 10107 I [SC]CloudManager: requestInit
,05-19 09:21:59.761 10107 10107 I [SC]Utils: folder : cachecreate fail, try again.
05-19 09:21:59.761 10107 10107 I [SC]Utils: folder : cache create fail.
,05-19 09:21:59.761 10107 10107 I [SC]Utils: folder : thumbnailcreate fail, try again.
05-19 09:21:59.761 10107 10107 I [SC]Utils: folder : thumbnail create fail.
05-19 09:21:59.761 10107 10107 I [SC]Utils: folder : sharecreate fail, try again.
05-19 09:21:59.761 10107 10107 I [SC]Utils: folder : share create fail.
05-19 09:21:59.761 10107 10107 I [SC]Utils: folder : scratchcreate fail, try again.
05-19 09:21:59.761 10107 10107 I [SC]Utils: folder : scratch create fail.
,05-19 09:21:59.761 10107 10107 I [SC]Utils: folder : eventSynccreate fail, try again.
05-19 09:21:59.761 10107 10107 I [SC]Utils: folder : eventSync create fail.
,05-19 09:21:59.771  9138 10259 I SA      : [SCU] saveMccToPreferece Start
05-19 09:21:59.771  9138 10259 I SA      : [SCU] RegionMCC : 260
05-19 09:21:59.771  9138 10259 I SA      : [SSP] query invoked
,05-19 09:21:59.781  9138  9148 I SA      : [SCU] isHaveSA() - false
,05-19 09:21:59.781  9138  9148 I SA      : [OCP] Samsung account is not Signed-in
05-19 09:21:59.781  9138 10259 I SA      : [TPMU] GetMccFromDB : null
05-19 09:21:59.781  9138 10259 I SA      : [SCU] getMccFromPreferece mcc = 260
05-19 09:21:59.781  9138 10259 I SA      : [SCU] saveMccToPreferece End
05-19 09:21:59.781  9138 10259 I SA_HTTPURLCONNECTION: [RC New] executeRequest [v2liruge] end. 909
05-19 09:21:59.781  9138 10259 I SA_HTTPURLCONNECTION: [RC New] Execute end
05-19 09:21:59.781  9138  9138 I SA      : [OR] GetMyCountryZoneTask mcc = 260
05-19 09:21:59.781  9138  9138 I SA      : [OR] GetMyCountryZoneTask Success
,05-19 09:21:59.781  9138  9148 I SA      : [OCP] Delete DB (TNC data)
,05-19 09:21:59.781 10107 10107 I [SC]CommonUtil: Samsung Account Not Logged in
,05-19 09:21:59.781  3511  4847 D ActivityManager:  getDeferredInfo final delay 0
,05-19 09:21:59.791  3511  4847 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{79572af u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1e51cfb 10121:com.samsung.android.coreapps/5011}
,05-19 09:21:59.841  3511  4313 D ActivityManager:  getDeferredInfo final delay 0
,05-19 09:21:59.851  3511  4313 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{79572af u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1e51cfb 10121:com.samsung.android.coreapps/5011}
,05-19 09:21:59.861  3511  4185 D ActivityManager:  getDeferredInfo final delay 0
,05-19 09:21:59.871  3511  4185 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{79572af u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1e51cfb 10121:com.samsung.android.coreapps/5011}
,05-19 09:21:59.871  3511  4185 D ActivityManager:  getDeferredInfo final delay 0
,05-19 09:21:59.881  3511  4185 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{79572af u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1590928 5047:com.microsoft.skydrive/u0a130}
,05-19 09:21:59.901  3511  3528 W IntentResolver: resolveIntent failed: found match, but none with CATEGORY_DEFAULT
,05-19 09:21:59.901  3511  4313 D ActivityManager:  getDeferredInfo final delay 300
,05-19 09:21:59.941  3511  6156 D SSRM:n  : SIOP:: AP = 320, PST = 317 (W:10), CP = 258, CUR = -7, LCD = 40
,05-19 09:21:59.951  3511  6156 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,05-19 09:21:59.991  3511  3814 V AlarmManager: Expired Alarm result :8
,05-19 09:21:59.991  3939  3939 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
05-19 09:21:59.991  3939  3939 D KeyguardUpdateMonitor: handleTimeUpdate
,05-19 09:22:00.001  3939  3939 D Clock   : received broadcast android.intent.action.TIME_TICK
,05-19 09:22:00.071  3939  3939 D DateView: received broadcast android.intent.action.TIME_TICK
,05-19 09:22:00.101  4764  4764 D [Weather Widget]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,05-19 09:22:00.101  4764  4764 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EEFA9050249635C043F7E254E316C2550]}
,05-19 09:22:00.111  4764  4764 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EAB01DC5C99149A39F887E17599325AFBFF089086AA9902184ADA25758C536FE2]}
,05-19 09:22:00.111  4764  4764 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EFF0B905BDFF72B69FB632A6CB072B41F95D2E6F4F84443284E97F40042D431D8350388453A923ABD8469D82798FA7548]}
,05-19 09:22:00.111  4764  4764 D [Weather Widget]  : {[A1AF0F6A1A65A89C43D705938923D0FEFB71880C4E84718DA0A3E1F383E54FB27A4284D9BEDF7BAA2ABFFE671EB65C640578FF9DE16A23BFE3280A9DCDBB09A0A076401BE06F4E826A7580C814FC1B1906151CE3B0473FD800199023346D7A029DDB25A1F2C9F2C6ACCAE9F5F7FFF36C]}
,05-19 09:22:00.111  4764  4764 D [Weather Widget]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,05-19 09:22:00.201  3511  3597 D ActivityManager:  getDeferredInfo final delay 0
,05-19 09:22:00.221  3511  3597 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{79572af u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{99722a8 10213:com.google.android.apps.photos/u0a135}
,05-19 09:22:00.241  3511  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a652169 u0 com.google.android.apps.photos.actionqueue.INTERNAL_ACTION qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{99722a8 10213:com.google.android.apps.photos/u0a135}
,05-19 09:22:00.241  3511  4459 D ActivityManager:  getDeferredInfo final delay 0
,05-19 09:22:00.251  3511  4459 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{79572af u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{99722a8 10213:com.google.android.apps.photos/u0a135}
,05-19 09:22:00.291  3511  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3e1f48f u0 com.google.android.apps.photos.jobqueue.EXECUTE_JOBS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{99722a8 10213:com.google.android.apps.photos/u0a135}
05-19 09:22:00.291  3511  4449 D ActivityManager:  getDeferredInfo final delay 300
,05-19 09:22:00.591  3511  3597 D ActivityManager:  getDeferredInfo final delay 0
,05-19 09:22:00.611  3511  3597 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{79572af u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b1c323c 4764:com.sec.android.daemonapp/u0a166}
,05-19 09:22:00.621  4764  4764 D [Weather Widget]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CFAAE09BFCA326403459399C53A4EE79DAC193CEB26509F8FF7498BE5251A746097407E81C28CD811D388C49D613C81F395B356AA489D29CB4C3BE983CCC84BA76AF507AA66A943348DF162DECA2A5A7DD]}
,05-19 09:22:00.621  4764  4764 D [Weather Widget]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CFE2E89F45594D9820F24D88E9AF210A78152C254DDD0027D207FA50AD616546E30965FECE0D7B834EEF4B0E211833EA2B]}
,05-19 09:22:00.621  3511  3852 D ActivityManager:  getDeferredInfo final delay 0
,05-19 09:22:00.631  3511  3852 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{79572af u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{acfd302 7942:com.sec.android.app.samsungapps/u0a16}
,05-19 09:22:00.631  7942  7942 D [SAUI]  : NetworkStateReceiver::connected::recovered?false
,05-19 09:22:00.651  7942  7942 D [SAUI]  : Global::recovered::false
,05-19 09:22:00.651  3511  4185 D ActivityManager:  getDeferredInfo final delay 300
05-19 09:22:00.651  7942  7942 D [SAUI]  : AutoUpdateService::onStartCommand
05-19 09:22:00.651  7942  7942 D [SAUI]  : AutoUpdateService::runAutoUpdateManager
,05-19 09:22:00.651  7942  7942 D [SAUI]  : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,05-19 09:22:00.661  7942  7942 D [SAUI]  : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
05-19 09:22:00.661  7942  7942 D [SA_INIT]: AutoUpdateManager ServiceInitializer startInitialize()
,05-19 09:22:00.661  7942  9217 D [SA_INIT]: createTaskForServiceInitialize()
05-19 09:22:00.661  7942  9218 D [SA_INIT]: NetworkStateCheckUnit workImpl()
,05-19 09:22:00.661  7942  9218 D [SA_INIT]: NetworkStateCheckUnit result : 1
,05-19 09:22:00.661  7942  7942 V JOULE   : JOULELOG [main]  com.sec.android.app.joule.f Task [35, 240311603_0] [END] FINISHED
05-19 09:22:00.661  7942  7942 D [SA_INIT]: ServiceInitializer onInitializeResult() reuslt : true
05-19 09:22:00.661  7942  7942 D [SAUI]  : AutoUpdateManager:INITCHECK:onInitializeSuccess
,05-19 09:22:00.661  7942  7942 D [SAUI]  : AutoUpdateTriggerManager:IDLE:notifyNextTime
05-19 09:22:00.661  7942  7942 D [SAUI]  : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,05-19 09:22:02.741 10147 10147 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,05-19 09:22:03.081  3511  3866 D ConnectivityService: handlePromptUnvalidated 503
,05-19 09:22:03.861  9689  9753 I io.jxcore.node.IncomingSocketThreadTest: IncomingSocketThreadTest failed, attempts left 9
05-19 09:22:03.861  9689  9753 I io.jxcore.node.IncomingSocketThreadTest: outgoingOutputStream.toString() = 
05-19 09:22:03.861  9689  9753 I io.jxcore.node.IncomingSocketThreadTest: textIncoming = Nullam in massa. Vivamus elit odio, in neque ut congue quis, venenatis placerat, nulla ornare suscipit, erat urna, pellentesque dapibus vel, lorem. Sed egestas non, dolor. Aliquam hendrerit sollicitudin sed.
,05-19 09:22:03.861  9689 10280 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
05-19 09:22:03.861  9689 10280 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,05-19 09:22:03.871  3158  3681 D EnterpriseController: netId is 0
05-19 09:22:03.871  3158  3681 D Netd    : getNetworkForDns: using netid 503 for uid 10078
,05-19 09:22:03.871  9689 10282 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
05-19 09:22:03.871  9689 10282 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,05-19 09:22:03.871  9689 10282 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-19 09:22:03.871  9689 10282 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-19 09:22:03.871  9689 10280 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
05-19 09:22:03.871  9689 10282 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
05-19 09:22:03.871  9689 10280 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
05-19 09:22:03.871  9689 10280 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,05-19 09:22:03.881  9689 10284 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 248, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:22:03.881  9689 10284 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-19 09:22:03.881  9689 10284 D io.jxcore.node.StreamCopyingThread:  id: 80
05-19 09:22:03.881  9689 10280 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,05-19 09:22:03.881  9689 10285 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 249, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:22:03.881  9689 10285 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-19 09:22:03.881  9689 10285 D io.jxcore.node.StreamCopyingThread:  id: 80
05-19 09:22:03.881  9689 10280 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
05-19 09:22:03.881  9689 10285 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 249, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:22:03.881  9689 10285 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-19 09:22:03.881  9689 10285 D io.jxcore.node.StreamCopyingThread:  id: 80
05-19 09:22:03.881  9689 10285 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:22:03.881  9689 10285 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-19 09:22:03.881  9689 10285 D io.jxcore.node.StreamCopyingThread:  id: 80
05-19 09:22:03.881  9689 10285 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
05-19 09:22:03.881  9689 10285 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
05-19 09:22:03.881  9689 10285 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,05-19 09:22:03.881  9689 10285 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
05-19 09:22:03.881  9689 10285 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
05-19 09:22:03.881  9689 10285 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
05-19 09:22:03.881  9689 10285 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 249, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:22:03.881  9689 10285 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-19 09:22:03.881  9689 10285 D io.jxcore.node.StreamCopyingThread:  id: 80 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
05-19 09:22:03.881  9689 10284 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 248, thread name: IncomingSocketThread/Sender): Socket closed
05-19 09:22:03.881  9689 10284 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 248, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:22:03.881  9689 10284 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-19 09:22:03.881  9689 10284 D io.jxcore.node.StreamCopyingThread:  id: 80 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
05-19 09:22:03.881  9689 10284 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
,05-19 09:22:03.881  9689 10284 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
05-19 09:22:03.881  9689 10284 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 248, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:22:03.881  9689 10284 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-19 09:22:03.881  9689 10284 D io.jxcore.node.StreamCopyingThread:  id: 80 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
05-19 09:22:03.881  9689 10286 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 250, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:22:03.881  9689 10286 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 09:22:03.881  9689 10286 D io.jxcore.node.StreamCopyingThread:  id: 81
05-19 09:22:03.881  9689 10286 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 250, thread name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:22:03.881  9689 10286 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 09:22:03.881  9689 10286 D io.jxcore.node.StreamCopyingThread:  id: 81
05-19 09:22:03.881  9689 10286 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:22:03.881  9689 10286 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 09:22:03.881  9689 10286 D io.jxcore.node.StreamCopyingThread:  id: 81
05-19 09:22:03.881  9689 10286 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
05-19 09:22:03.881  9689 10286 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
05-19 09:22:03.881  9689 10286 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,05-19 09:22:03.881  9689 10286 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
05-19 09:22:03.881  9689 10286 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
05-19 09:22:03.881  9689 10286 I io.jxcore.node.OutgoingSocketThread: The sending thread is done
05-19 09:22:03.881  9689 10286 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 250, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:22:03.881  9689 10286 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 09:22:03.881  9689 10286 D io.jxcore.node.StreamCopyingThread:  id: 81 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
05-19 09:22:03.881  9689 10287 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 251, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:22:03.881  9689 10287 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 09:22:03.881  9689 10287 D io.jxcore.node.StreamCopyingThread:  id: 81
05-19 09:22:03.881  9689 10287 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 251, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:22:03.881  9689 10287 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 09:22:03.881  9689 10287 D io.jxcore.node.StreamCopyingThread:  id: 81
05-19 09:22:03.881  9689 10287 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:22:03.881  9689 10287 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 09:22:03.881  9689 10287 D io.jxcore.node.StreamCopyingThread:  id: 81
05-19 09:22:03.881  9689 10287 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
05-19 09:22:03.881  9689 10287 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,05-19 09:22:03.881  9689 10287 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
05-19 09:22:03.881  9689 10287 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
05-19 09:22:03.881  9689 10287 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
05-19 09:22:03.881  9689 10287 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
05-19 09:22:03.881  9689 10287 I io.jxcore.node.OutgoingSocketThread: Both threads are done, notifying the listener...
05-19 09:22:03.881  9689 10287 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 251, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:22:03.881  9689 10287 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 09:22:03.881  9689 10287 D io.jxcore.node.StreamCopyingThread:  id: 81 .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,05-19 09:22:04.661  3511  6192 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,05-19 09:22:06.081  9915  9940 W Babel   : ayr TOOK TOO LONG! (15001ms > 10000ms)
,05-19 09:22:06.081  9915  9942 W Babel   : ayr TOOK TOO LONG! (15001ms > 10000ms)
,05-19 09:22:06.091  3511  4313 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity newState = 2 callingPackage = 10117
,05-19 09:22:06.141  9915  9950 W Babel   : ayr TOOK TOO LONG! (15000ms > 10000ms)
,05-19 09:22:06.141 10288 10288 E Zygote  : v2
05-19 09:22:06.141 10288 10288 I libpersona: KNOX_SDCARD checking this for 10117
05-19 09:22:06.141 10288 10288 I libpersona: KNOX_SDCARD not a persona
,05-19 09:22:06.151 10288 10288 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-19 09:22:06.151  3511  3597 I ActivityManager: Start proc 10288:com.google.android.talk:matchstick/u0a117 for broadcast-3 com.google.android.talk/com.google.android.libraries.matchstick.net.MatchstickInProcessReceiver
,05-19 09:22:06.151 10288 10288 E Zygote  : accessInfo : 0
05-19 09:22:06.151 10288 10288 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.talk:matchstick 
,05-19 09:22:06.191  3511  4407 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,05-19 09:22:06.201 10288 10288 D TimaKeyStoreProvider: TimaSignature is unavailable
05-19 09:22:06.201 10288 10288 D ActivityThread: Added TimaKeyStore provider
,05-19 09:22:06.201  9915  9915 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
05-19 09:22:06.201  9915  9915 W Babel   : BAM#gBA: invalid account id: -1
05-19 09:22:06.201  9915  9915 W Babel   : BAM#gBA: invalid account id: -1
,05-19 09:22:06.201  9915  9915 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,05-19 09:22:06.221  3511  4449 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e134aab u0 register_intent_action qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a391508 10288:com.google.android.talk:matchstick/u0a117}
,05-19 09:22:06.231  3511  4185 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,05-19 09:22:06.241 10288 10288 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,05-19 09:22:06.241 10288 10288 D RelationGraph: garbageCollect()
,05-19 09:22:06.241 10288 10288 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.google.android.talk rsrc of package com.google.android.talk
,05-19 09:22:06.241  3511  4847 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-19 09:22:06.241 10288 10288 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-19 09:22:06.251 10288 10288 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 09:22:06.251 10288 10288 I InjectionManager: Inside getClassLibPath caller 
,05-19 09:22:06.271 10288 10288 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm64
,05-19 09:22:06.281  4158  4174 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg com.google.android.talk,id=10436,extra=Bundle[mParcelledData.dataSize=84]
05-19 09:22:06.281  4158  4158 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=10436, samsung.notification.type=normal, samsung.people.package_name=com.google.android.talk}]
,05-19 09:22:06.281  4158  4158 I PeopleStripeService: PeopleNotificationReceiver:3
05-19 09:22:06.281  4158  4158 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
05-19 09:22:06.281  4158  4158 I PeopleDataManager: removeNotification
05-19 09:22:06.281  4158  4158 I NotificationParser: getNotiType:com.google.android.talk,null
05-19 09:22:06.281  4158  4158 D PeopleDataManager: removeNotiInfo: id =10436,packageName=com.google.android.talk,isEdgeNotification=false,key=null,removeAll=false
05-19 09:22:06.281  4158  4158 D PeopleDataManager: removeNotiInfo =null
,05-19 09:22:06.351 10288 10288 D InjectionManager: InjectionManager
05-19 09:22:06.351 10288 10288 D InjectionManager: fillFeatureStoreMap com.google.android.talk
,05-19 09:22:06.351 10288 10288 I InjectionManager: Constructor com.google.android.talk, Feature store :{}
05-19 09:22:06.351 10288 10288 I InjectionManager: featureStore :{}
,05-19 09:22:06.521 10288 10306 I MS_RegisterService: RegisterService intent:Intent { act=register_intent_action flg=0x10 cmp=com.google.android.talk/com.google.android.libraries.matchstick.net.SilentRegisterService bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} } isPeriodic:false
,05-19 09:22:06.531 10288 10306 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in com.google.android.talk rsrc of package com.google.android.gms
,05-19 09:22:06.541 10288 10306 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 09:22:06.541 10288 10306 I InjectionManager: Inside getClassLibPath caller 
,05-19 09:22:06.561 10288 10306 W System  : ClassLoader referenced unknown path: /system/priv-app/GmsCore/lib/arm64
,05-19 09:22:06.651 10288 10306 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,05-19 09:22:06.691 10288 10306 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,05-19 09:22:06.691 10288 10306 I MS_RegisterService: Not registered and not enabled. Doing nothing.
,05-19 09:22:06.701  3511  4847 I ActivityManager: Killing 9488:com.google.android.apps.docs/u0a98 (adj 15): DHA:empty #33
,05-19 09:22:06.741  3511  4313 D ActivityManager: cleanUpApplicationRecord -- 9488
,05-19 09:22:06.741  3511  4313 D ActivityManager: isAutoRunBlockedApp:: com.google.android.apps.docs, Auto Run ON
,05-19 09:22:06.751 10147 10147 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,05-19 09:22:06.771 10147 10147 I dhcpcd  : wlan0: no IPv6 Routers available
,05-19 09:22:07.731  7942  7942 D PreloadUpdateManagerStateMachine: execute::IDLE:EXECUTE
05-19 09:22:07.731  7942  7942 D PreloadUpdateManagerStateMachine: exit::IDLE
05-19 09:22:07.731  7942  7942 D PreloadUpdateManagerStateMachine: entry::CHECK_TIMEOUT_FOR_UPDATE
,05-19 09:22:07.731  7942  7942 D [SAUI]  : AutoUpdateTriggerManager:IDLE:notifyNextTime
05-19 09:22:07.731  7942  7942 D PreloadUpdateManagerStateMachine: execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,05-19 09:22:07.741  7942  7942 D PreloadUpdateManagerStateMachine: exit::CHECK_TIMEOUT_FOR_UPDATE
05-19 09:22:07.741  7942  7942 D PreloadUpdateManagerStateMachine: entry::IDLE
,05-19 09:22:08.871  9689  9753 I io.jxcore.node.IncomingSocketThreadTest: IncomingSocketThreadTest failed, attempts left 8
05-19 09:22:08.871  9689  9753 I io.jxcore.node.IncomingSocketThreadTest: outgoingOutputStream.toString() = Nullam in massa. Vivamus elit odio, in neque ut congue quis, venenatis placerat, nulla ornare suscipit, erat urna, pellentesque dapibus vel, lorem. Sed egestas non, dolor. Aliquam hendrerit sollicitudin sed.
05-19 09:22:08.871  9689  9753 I io.jxcore.node.IncomingSocketThreadTest: textIncoming = Nullam in massa. Vivamus elit odio, in neque ut congue quis, venenatis placerat, nulla ornare suscipit, erat urna, pellentesque dapibus vel, lorem. Sed egestas non, dolor. Aliquam hendrerit sollicitudin sed.
05-19 09:22:08.871  9689  9753 I !!      :  finally closed
,05-19 09:22:08.871  9689  9753 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
,05-19 09:22:08.871  9689  9753 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,05-19 09:22:08.871  9689  9753 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
05-19 09:22:08.871  9689  9753 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,05-19 09:22:08.881  9689  9753 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,05-19 09:22:08.881  9689  9753 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
,05-19 09:22:08.881  9689  9753 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.rockwellautomation.thalitest.MainActivity@8116d8 Bundle[{}]
05-19 09:22:08.881  9689  9753 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
,05-19 09:22:08.881  9689  9753 I io.jxcore.node.LifeCycleMonitor: start: OK
05-19 09:22:08.881  9689  9753 I io.jxcore.node.LifeCycleMonitor: stop: OK
,05-19 09:22:08.891  9689  9753 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
05-19 09:22:08.891  9689  9753 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,05-19 09:22:08.891  9689  9753 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
05-19 09:22:08.891  9689  9753 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,05-19 09:22:08.891  9689  9753 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
05-19 09:22:08.891  9689  9753 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,05-19 09:22:08.891  9689  9753 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
05-19 09:22:08.891  9689  9753 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,05-19 09:22:08.901  9689  9753 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
,05-19 09:22:08.901  9689  9753 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,05-19 09:22:08.901  9689  9753 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
,05-19 09:22:08.901  9689  9753 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
,05-19 09:22:08.901  9689  9753 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
,05-19 09:22:08.901  9689  9753 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
,05-19 09:22:08.911  9689  9753 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testRun
,05-19 09:22:08.911  9689 10311 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
05-19 09:22:08.911  9689 10311 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,05-19 09:22:08.921  3158  3681 D EnterpriseController: netId is 0
05-19 09:22:08.921  3158  3681 D Netd    : getNetworkForDns: using netid 503 for uid 10078
,05-19 09:22:08.921  9689 10313 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
05-19 09:22:08.921  9689 10313 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
05-19 09:22:08.921  9689 10313 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-19 09:22:08.921  9689 10313 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-19 09:22:08.921  9689 10311 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
05-19 09:22:08.921  9689 10311 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
05-19 09:22:08.921  9689 10311 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-19 09:22:08.921  9689 10313 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,05-19 09:22:08.921  9689 10311 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-19 09:22:08.921  9689 10311 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,05-19 09:22:08.921  9689 10315 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 255, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:22:08.921  9689 10315 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-19 09:22:08.921  9689 10315 D io.jxcore.node.StreamCopyingThread:  id: 83
,05-19 09:22:08.921  9689 10316 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 256, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:22:08.921  9689 10316 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-19 09:22:08.921  9689 10316 D io.jxcore.node.StreamCopyingThread:  id: 83
,05-19 09:22:08.931  9689 10317 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 257, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:22:08.931  9689 10317 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 09:22:08.931  9689 10317 D io.jxcore.node.StreamCopyingThread:  id: 84
,05-19 09:22:08.941  9689 10318 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 258, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:22:08.941  9689 10318 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 09:22:08.941  9689 10318 D io.jxcore.node.StreamCopyingThread:  id: 84
,05-19 09:22:08.941  9689 10318 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 258, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:22:08.941  9689 10318 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 09:22:08.941  9689 10318 D io.jxcore.node.StreamCopyingThread:  id: 84
05-19 09:22:08.941  9689 10318 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:22:08.941  9689 10318 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 09:22:08.941  9689 10318 D io.jxcore.node.StreamCopyingThread:  id: 84
05-19 09:22:08.941  9689 10318 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
05-19 09:22:08.941  9689 10318 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
05-19 09:22:08.941  9689 10318 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
05-19 09:22:08.941  9689 10318 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
05-19 09:22:08.941  9689 10318 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
05-19 09:22:08.941  9689 10318 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
05-19 09:22:08.941  9689 10318 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 258, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:22:08.941  9689 10318 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 09:22:08.941  9689 10318 D io.jxcore.node.StreamCopyingThread:  id: 84 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
05-19 09:22:08.941  9689 10317 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 257, thread name: OutgoingSocketThread/Sender): recvfrom failed: EBADF (Bad file descriptor)
05-19 09:22:08.941  9689 10317 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 257, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:22:08.941  9689 10317 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 09:22:08.941  9689 10317 D io.jxcore.node.StreamCopyingThread:  id: 84 .During the lifetime of the thread the total number of bytes read was 36864 and the total number of bytes written 36864
05-19 09:22:08.941  9689 10317 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: recvfrom failed: EBADF (Bad file descriptor)
05-19 09:22:08.941  9689 10317 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
05-19 09:22:08.941  9689 10316 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 256, thread name: IncomingSocketThread/Receiver): sendto failed: EPIPE (Broken pipe)
,05-19 09:22:08.941  9689 10315 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 255, thread name: IncomingSocketThread/Sender): recvfrom failed: ECONNRESET (Connection reset by peer)
05-19 09:22:08.941  9689 10317 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 257, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:22:08.941  9689 10317 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 09:22:08.941  9689 10317 D io.jxcore.node.StreamCopyingThread:  id: 84 .During the lifetime of the thread the total number of bytes read was 36864 and the total number of bytes written 36864
05-19 09:22:08.941  9689 10316 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 256, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:22:08.941  9689 10316 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-19 09:22:08.941  9689 10316 D io.jxcore.node.StreamCopyingThread:  id: 83 .During the lifetime of the thread the total number of bytes read was 401408 and the total number of bytes written 397312
05-19 09:22:08.941  9689 10315 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 255, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:22:08.941  9689 10315 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-19 09:22:08.941  9689 10315 D io.jxcore.node.StreamCopyingThread:  id: 83 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
05-19 09:22:08.941  9689 10315 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: recvfrom failed: ECONNRESET (Connection reset by peer)
05-19 09:22:08.941  9689 10316 E io.jxcore.node.IncomingSocketThread: The receiving thread failed with error "Failed to write to the output stream: sendto failed: EPIPE (Broken pipe)", this is likely due to peer having disconnected
05-19 09:22:08.941  9689 10315 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
05-19 09:22:08.941  9689 10316 D io.jxcore.node.StreamCopyingThread: number of bytes read = 4096
05-19 09:22:08.941  9689 10315 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 255, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:22:08.941  9689 10315 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-19 09:22:08.941  9689 10315 D io.jxcore.node.StreamCopyingThread:  id: 83 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
05-19 09:22:08.941  9689 10316 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 256, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:22:08.941  9689 10316 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-19 09:22:08.941  9689 10316 D io.jxcore.node.StreamCopyingThread:  id: 83 .During the lifetime of the thread the total number of bytes read was 401408 and the total number of bytes written 397312
,05-19 09:22:09.271  3511  4198 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-19 09:22:09.271  3511  4198 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4346, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-19 09:22:09.271  3511  4198 D BatteryService: online:4, current avg:92, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:163
05-19 09:22:09.271  3511  3511 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-19 09:22:09.271  3511  3511 I MotionRecognitionService: Plugged
,05-19 09:22:09.271  3511  3511 D MotionRecognitionService:   cableConnection= 1
05-19 09:22:09.271  3511  3511 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-19 09:22:09.271  3511  3511 D MotionRecognitionService: skip setTransmitPower. 
,05-19 09:22:09.281  3511  3860 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-19 09:22:09.281  3939  3939 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,05-19 09:22:09.281  3939  3939 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-19 09:22:09.291  3939  3939 D KeyguardUpdateMonitor: handleBatteryUpdate
,05-19 09:22:09.291  3939  3939 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
05-19 09:22:09.291  3939  3939 D PowerUI.Notification: There is no change about charging status, so return!
,05-19 09:22:09.301  4867  4867 D CommonServiceConfiguration: getStringValueSetting
,05-19 09:22:09.321  9787  9787 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-19 09:22:09.321  4867  4867 D BatteryMonitor: new battery level: 100
05-19 09:22:09.321  9787  9827 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-19 09:22:09.331  3939  3939 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,05-19 09:22:09.331  3939  3939 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,05-19 09:22:09.981  3511  6156 D SSRM:n  : SIOP:: AP = 300, PST = 317 (W:14), CP = 256, CUR = 92, LCD = 40
,05-19 09:22:10.681  7942  7942 D PreloadUpdateManagerStateMachine: execute::IDLE:EXECUTE
05-19 09:22:10.681  7942  7942 D PreloadUpdateManagerStateMachine: exit::IDLE
05-19 09:22:10.681  7942  7942 D PreloadUpdateManagerStateMachine: entry::CHECK_TIMEOUT_FOR_UPDATE
,05-19 09:22:10.681  7942  7942 D [SAUI]  : AutoUpdateTriggerManager:IDLE:notifyNextTime
05-19 09:22:10.681  7942  7942 D PreloadUpdateManagerStateMachine: execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,05-19 09:22:10.681  7942  7942 D PreloadUpdateManagerStateMachine: exit::CHECK_TIMEOUT_FOR_UPDATE
05-19 09:22:10.681  7942  7942 D PreloadUpdateManagerStateMachine: entry::IDLE
,05-19 09:22:14.421  9689  9753 I io.jxcore.node.OutgoingSocketThreadTest: OutgoingSocketThreadTest
,05-19 09:22:14.431  9689 10321 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
05-19 09:22:14.431  9689 10321 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,05-19 09:22:14.431  3158  3681 D EnterpriseController: netId is 0
05-19 09:22:14.431  3158  3681 D Netd    : getNetworkForDns: using netid 503 for uid 10078
,05-19 09:22:14.441  9689 10323 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
05-19 09:22:14.441  9689 10323 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
05-19 09:22:14.441  9689 10323 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-19 09:22:14.441  9689 10323 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-19 09:22:14.441  9689 10321 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
05-19 09:22:14.441  9689 10321 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
05-19 09:22:14.441  9689 10323 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
05-19 09:22:14.441  9689 10321 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-19 09:22:14.441  9689 10321 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-19 09:22:14.441  9689 10321 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,05-19 09:22:14.441  9689 10325 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 262, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:22:14.441  9689 10325 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-19 09:22:14.441  9689 10325 D io.jxcore.node.StreamCopyingThread:  id: 86
,05-19 09:22:14.441  9689 10326 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 263, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:22:14.441  9689 10326 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-19 09:22:14.441  9689 10326 D io.jxcore.node.StreamCopyingThread:  id: 86
05-19 09:22:14.451  9689 10327 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 264, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:22:14.451  9689 10327 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 09:22:14.451  9689 10327 D io.jxcore.node.StreamCopyingThread:  id: 87
,05-19 09:22:14.451  9689 10328 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 265, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:22:14.451  9689 10328 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 09:22:14.451  9689 10328 D io.jxcore.node.StreamCopyingThread:  id: 87
05-19 09:22:14.451  9689 10328 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 265, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:22:14.451  9689 10328 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 09:22:14.451  9689 10328 D io.jxcore.node.StreamCopyingThread:  id: 87
,05-19 09:22:14.451  9689 10328 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:22:14.451  9689 10328 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 09:22:14.451  9689 10328 D io.jxcore.node.StreamCopyingThread:  id: 87
05-19 09:22:14.451  9689 10328 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
05-19 09:22:14.451  9689 10328 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
05-19 09:22:14.451  9689 10328 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
05-19 09:22:14.451  9689 10328 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
05-19 09:22:14.451  9689 10328 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
05-19 09:22:14.451  9689 10328 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
05-19 09:22:14.451  9689 10328 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 265, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:22:14.451  9689 10328 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 09:22:14.451  9689 10328 D io.jxcore.node.StreamCopyingThread:  id: 87 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,05-19 09:22:14.451  9689 10327 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 264, thread name: OutgoingSocketThread/Sender): recvfrom failed: EBADF (Bad file descriptor)
05-19 09:22:14.451  9689 10327 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 264, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:22:14.451  9689 10327 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 09:22:14.451  9689 10327 D io.jxcore.node.StreamCopyingThread:  id: 87 .During the lifetime of the thread the total number of bytes read was 8192 and the total number of bytes written 8192
05-19 09:22:14.451  9689 10327 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: recvfrom failed: EBADF (Bad file descriptor)
05-19 09:22:14.451  9689 10327 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
05-19 09:22:14.451  9689 10327 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 264, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:22:14.451  9689 10327 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 09:22:14.451  9689 10327 D io.jxcore.node.StreamCopyingThread:  id: 87 .During the lifetime of the thread the total number of bytes read was 8192 and the total number of bytes written 8192
05-19 09:22:14.451  9689 10325 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 262, thread name: IncomingSocketThread/Sender): recvfrom failed: ECONNRESET (Connection reset by peer)
05-19 09:22:14.451  9689 10325 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 262, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:22:14.451  9689 10325 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-19 09:22:14.451  9689 10325 D io.jxcore.node.StreamCopyingThread:  id: 86 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
,05-19 09:22:14.451  9689 10325 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: recvfrom failed: ECONNRESET (Connection reset by peer)
05-19 09:22:14.451  9689 10325 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
05-19 09:22:14.451  9689 10325 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 262, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:22:14.451  9689 10325 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-19 09:22:14.451  9689 10325 D io.jxcore.node.StreamCopyingThread:  id: 86 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
05-19 09:22:14.451  9689 10326 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 263, thread name: IncomingSocketThread/Receiver): sendto failed: EPIPE (Broken pipe)
05-19 09:22:14.451  9689 10326 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 263, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:22:14.451  9689 10326 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-19 09:22:14.451  9689 10326 D io.jxcore.node.StreamCopyingThread:  id: 86 .During the lifetime of the thread the total number of bytes read was 16384 and the total number of bytes written 12288
05-19 09:22:14.451  9689 10326 E io.jxcore.node.IncomingSocketThread: The receiving thread failed with error "Failed to write to the output stream: sendto failed: EPIPE (Broken pipe)", this is likely due to peer having disconnected
05-19 09:22:14.451  9689 10326 D io.jxcore.node.StreamCopyingThread: number of bytes read = 4096
05-19 09:22:14.451  9689 10326 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 263, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:22:14.451  9689 10326 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-19 09:22:14.451  9689 10326 D io.jxcore.node.StreamCopyingThread:  id: 86 .During the lifetime of the thread the total number of bytes read was 16384 and the total number of bytes written 12288
,05-19 09:22:19.321  3511  3852 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-19 09:22:19.321  3511  3852 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4350, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-19 09:22:19.321  3511  3852 D BatteryService: online:4, current avg:147, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:154
05-19 09:22:19.321  3511  3511 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-19 09:22:19.331  3511  3511 I MotionRecognitionService: Plugged
,05-19 09:22:19.331  3511  3511 D MotionRecognitionService:   cableConnection= 1
05-19 09:22:19.331  3511  3511 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-19 09:22:19.331  3511  3511 D MotionRecognitionService: skip setTransmitPower. 
,05-19 09:22:19.331  3511  3860 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-19 09:22:19.331  3939  3939 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
05-19 09:22:19.341  3939  3939 D KeyguardUpdateMonitor: handleBatteryUpdate
,05-19 09:22:19.341  3939  3939 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-19 09:22:19.341  3939  3939 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
05-19 09:22:19.341  3939  3939 D PowerUI.Notification: There is no change about charging status, so return!
,05-19 09:22:19.361  4867  4867 D CommonServiceConfiguration: getStringValueSetting
,05-19 09:22:19.371  4867  4867 D BatteryMonitor: new battery level: 100
,05-19 09:22:19.371  3939  3939 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
05-19 09:22:19.371  3939  3939 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,05-19 09:22:19.371  9787  9787 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-19 09:22:19.371  9787  9827 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-19 09:22:19.431  9689  9753 I io.jxcore.node.OutgoingSocketThreadTest: OutgoingSocketThreadTest failed, attempts left 9
,05-19 09:22:19.431  9689  9753 I io.jxcore.node.OutgoingSocketThreadTest: incomingOutputStream = 
05-19 09:22:19.431  9689  9753 I io.jxcore.node.OutgoingSocketThreadTest: textOutgoing= Nullam in massa. Vivamus elit odio, in neque ut congue quis, venenatis placerat, nulla ornare suscipit, erat urna, pellentesque dapibus vel, lorem. Sed egestas non, dolor. Aliquam hendrerit sollicitudin sed.
,05-19 09:22:19.441  9689 10330 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
05-19 09:22:19.441  9689 10330 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,05-19 09:22:19.451  3158  3681 D EnterpriseController: netId is 0
,05-19 09:22:19.451  3158  3681 D Netd    : getNetworkForDns: using netid 503 for uid 10078
,05-19 09:22:19.451  9689 10332 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
05-19 09:22:19.451  9689 10332 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
05-19 09:22:19.451  9689 10332 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-19 09:22:19.451  9689 10332 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,05-19 09:22:19.451  9689 10330 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
05-19 09:22:19.451  9689 10330 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
05-19 09:22:19.451  9689 10330 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-19 09:22:19.451  9689 10332 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
05-19 09:22:19.451  9689 10330 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-19 09:22:19.451  9689 10330 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,05-19 09:22:19.451  9689 10335 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 270, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:22:19.451  9689 10335 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-19 09:22:19.451  9689 10335 D io.jxcore.node.StreamCopyingThread:  id: 89
,05-19 09:22:19.451  9689 10334 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 269, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:22:19.451  9689 10334 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-19 09:22:19.451  9689 10334 D io.jxcore.node.StreamCopyingThread:  id: 89
,05-19 09:22:19.461  9689 10337 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 272, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:22:19.461  9689 10337 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 09:22:19.461  9689 10337 D io.jxcore.node.StreamCopyingThread:  id: 90
05-19 09:22:19.461  9689 10337 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 272, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:22:19.461  9689 10337 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 09:22:19.461  9689 10337 D io.jxcore.node.StreamCopyingThread:  id: 90
05-19 09:22:19.461  9689 10337 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:22:19.461  9689 10337 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 09:22:19.461  9689 10337 D io.jxcore.node.StreamCopyingThread:  id: 90
05-19 09:22:19.461  9689 10337 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,05-19 09:22:19.461  9689 10337 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
05-19 09:22:19.461  9689 10337 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
05-19 09:22:19.461  9689 10337 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
05-19 09:22:19.461  9689 10337 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
05-19 09:22:19.461  9689 10337 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
05-19 09:22:19.461  9689 10337 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 272, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:22:19.461  9689 10337 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 09:22:19.461  9689 10337 D io.jxcore.node.StreamCopyingThread:  id: 90 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
05-19 09:22:19.461  9689 10336 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 271, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:22:19.461  9689 10336 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 09:22:19.461  9689 10336 D io.jxcore.node.StreamCopyingThread:  id: 90
,05-19 09:22:19.461  9689 10336 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 271, thread name: OutgoingSocketThread/Sender): recvfrom failed: EBADF (Bad file descriptor)
05-19 09:22:19.461  9689 10336 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 271, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:22:19.461  9689 10336 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 09:22:19.461  9689 10336 D io.jxcore.node.StreamCopyingThread:  id: 90 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
05-19 09:22:19.461  9689 10336 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: recvfrom failed: EBADF (Bad file descriptor)
05-19 09:22:19.461  9689 10336 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
05-19 09:22:19.461  9689 10336 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 271, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:22:19.461  9689 10336 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 09:22:19.461  9689 10336 D io.jxcore.node.StreamCopyingThread:  id: 90 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
05-19 09:22:19.461  9689 10335 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 270, thread name: IncomingSocketThread/Receiver): sendto failed: ECONNRESET (Connection reset by peer)
05-19 09:22:19.461  9689 10334 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 269, thread name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:22:19.461  9689 10334 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-19 09:22:19.461  9689 10334 D io.jxcore.node.StreamCopyingThread:  id: 89
,05-19 09:22:19.461  9689 10335 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 270, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:22:19.461  9689 10335 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-19 09:22:19.461  9689 10335 D io.jxcore.node.StreamCopyingThread:  id: 89 .During the lifetime of the thread the total number of bytes read was 45056 and the total number of bytes written 40960
05-19 09:22:19.461  9689 10334 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:22:19.461  9689 10334 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-19 09:22:19.461  9689 10334 D io.jxcore.node.StreamCopyingThread:  id: 89
05-19 09:22:19.461  9689 10334 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
05-19 09:22:19.461  9689 10335 E io.jxcore.node.IncomingSocketThread: The receiving thread failed with error "Failed to write to the output stream: sendto failed: ECONNRESET (Connection reset by peer)", this is likely due to peer having disconnected
05-19 09:22:19.461  9689 10334 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
05-19 09:22:19.461  9689 10335 D io.jxcore.node.StreamCopyingThread: number of bytes read = 4096
05-19 09:22:19.461  9689 10334 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,05-19 09:22:19.461  9689 10334 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
05-19 09:22:19.461  9689 10334 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
05-19 09:22:19.461  9689 10335 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 270, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:22:19.461  9689 10335 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-19 09:22:19.461  9689 10335 D io.jxcore.node.StreamCopyingThread:  id: 89 .During the lifetime of the thread the total number of bytes read was 45056 and the total number of bytes written 40960
05-19 09:22:19.461  9689 10334 I io.jxcore.node.IncomingSocketThread: The sending thread is done
05-19 09:22:19.461  9689 10334 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 269, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 09:22:19.461  9689 10334 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-19 09:22:19.461  9689 10334 D io.jxcore.node.StreamCopyingThread:  id: 89 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,05-19 09:22:20.001  3511  6156 D SSRM:n  : SIOP:: AP = 290, PST = 310 (W:14), CP = 252, CUR = 147, LCD = 40
,05-19 09:22:21.071  3511  3654 D PowerManagerService: [s] UserActivityState : 1 -> 2
05-19 09:22:21.071  3511  3654 D PowerManagerService: mDisplayReady: false
05-19 09:22:21.071  3511  3654 D DisplayPowerController: animateScreenStateChange[0]: target=2
05-19 09:22:21.071  3511  3654 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
05-19 09:22:21.071  3511  3654 D DisplayPowerController: getFinalBrightness : Summary is 30 -> 30
05-19 09:22:21.071  3511  3654 D DisplayPowerController: Animating brightness: target=30, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
05-19 09:22:21.071  3511  3654 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
05-19 09:22:21.071  3511  3654 D PowerManagerService: mDisplayReady: true
,05-19 09:22:21.081  3511  3903 D lights  : lcd : 36 +
,05-19 09:22:21.081  3511  3903 D lights  : lcd : 36 -
,05-19 09:22:21.081  3511  3654 D DisplayPowerController: animateScreenStateChange[0]: target=2
05-19 09:22:21.081  3511  3654 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
05-19 09:22:21.081  3511  3654 D DisplayPowerController: getFinalBrightness : Summary is 30 -> 30
,05-19 09:22:21.081  3511  3654 D DisplayPowerController: Animating brightness: target=30, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,05-19 09:22:21.091  3511  3903 D lights  : lcd : 30 +
,05-19 09:22:21.091  3511  3654 D DisplayPowerController: animateScreenStateChange[0]: target=2
05-19 09:22:21.091  3511  3654 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
,05-19 09:22:21.091  3511  3654 D DisplayPowerController: getFinalBrightness : Summary is 30 -> 30
05-19 09:22:21.091  3511  3654 D DisplayPowerController: Animating brightness: target=30, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
05-19 09:22:21.101  3511  3903 D lights  : lcd : 30 -
,05-19 09:22:21.101  3511  3654 D DisplayPowerController: animateScreenStateChange[0]: target=2
05-19 09:22:21.101  3511  3654 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
05-19 09:22:21.101  3511  3654 D DisplayPowerController: getFinalBrightness : Summary is 30 -> 30
05-19 09:22:21.101  3511  3654 D DisplayPowerController: Animating brightness: target=30, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,05-19 09:22:24.451  9689  9753 I io.jxcore.node.OutgoingSocketThreadTest: OutgoingSocketThreadTest failed, attempts left 8
05-19 09:22:24.451  9689  9753 I io.jxcore.node.OutgoingSocketThreadTest: incomingOutputStream = Nullam in massa. Vivamus elit odio, in neque ut congue quis, venenatis placerat, nulla ornare suscipit, erat urna, pellentesque dapibus vel, lorem. Sed egestas non, dolor. Aliquam hendrerit sollicitudin sed.
05-19 09:22:24.451  9689  9753 I io.jxcore.node.OutgoingSocketThreadTest: textOutgoing= Nullam in massa. Vivamus elit odio, in neque ut congue quis, venenatis placerat, nulla ornare suscipit, erat urna, pellentesque dapibus vel, lorem. Sed egestas non, dolor. Aliquam hendrerit sollicitudin sed.
,05-19 09:22:24.451  9689  9753 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,05-19 09:22:24.451  9689  9753 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testNoAvailablePorts
,05-19 09:22:24.671  3511  6192 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,05-19 09:22:25.461  9689  9753 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,05-19 09:22:25.461  9689  9753 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
,05-19 09:22:25.461  9689  9753 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
05-19 09:22:25.461  9689  9753 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 280)
,05-19 09:22:25.461  9689  9753 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
,05-19 09:22:25.471  9689  9753 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
05-19 09:22:25.471  9689  9753 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 281)
,05-19 09:22:25.471  9689  9753 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
05-19 09:22:25.471  9689  9753 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
05-19 09:22:25.471  9689  9753 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
,05-19 09:22:25.471  9689  9753 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
05-19 09:22:25.471  9689  9753 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cea24ea added. We now have 2 listener(s)
05-19 09:22:25.471  9689  9753 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cea24ea added. We now have 3 listener(s)
05-19 09:22:25.471  9689  9753 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,05-19 09:22:25.481  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"A8:81:95:E9:5F:6F"}
,05-19 09:22:25.481  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
05-19 09:22:25.481  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"A8:81:95:E9:5F:6F"}
05-19 09:22:25.481  9689  9753 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
05-19 09:22:25.481  9689  9753 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ded33db added. We now have 4 listener(s)
05-19 09:22:25.481  9689  9753 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
05-19 09:22:25.481  9689  9753 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,05-19 09:22:25.491  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:22:25.491  9689  9753 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
,05-19 09:22:25.501  9689  9753 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
05-19 09:22:25.501  9689  9753 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
,05-19 09:22:25.501  9689  9753 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
05-19 09:22:25.501  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,05-19 09:22:25.501  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":4,"address":"A8:81:95:E9:5F:6F"}
,05-19 09:22:25.501  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":4,"address":"A8:81:95:E9:5F:6F"}
05-19 09:22:25.501  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:22:25.501  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,05-19 09:22:25.511  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":4,"address":"A8:81:95:E9:5F:6F"}
,05-19 09:22:25.511  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":4,"address":"A8:81:95:E9:5F:6F"}
05-19 09:22:25.511  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:22:25.511  9689  9753 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
05-19 09:22:25.511  9689  9753 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
05-19 09:22:25.511  9689  9753 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
05-19 09:22:25.511  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,05-19 09:22:25.511  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
05-19 09:22:25.511  9689  9753 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
05-19 09:22:25.511  9689  9753 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
05-19 09:22:25.511  9689  9753 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
05-19 09:22:25.511  9689  9753 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,05-19 09:22:25.511  9689  9753 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
05-19 09:22:25.511  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
05-19 09:22:25.511  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
05-19 09:22:25.511  9689  9689 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
05-19 09:22:25.511  9689 10342 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,05-19 09:22:25.521  9689 10342 D BluetoothSocket: bindListen(): myUserId = 0
,05-19 09:22:25.521  9689 10342 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,05-19 09:22:25.521  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
05-19 09:22:25.521  9689  9753 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,05-19 09:22:25.521  9689  9753 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
05-19 09:22:25.521  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:22:25.531  9689 10342 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
05-19 09:22:25.531  9689  9753 D BluetoothAdapter: STATE_ON
05-19 09:22:25.531  9689 10342 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@1ee1951, port: 6, type: 1, local socket address: null, socket type: 0
,05-19 09:22:25.531  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:22:25.531  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-135,7,main], id: 135
,05-19 09:22:25.531  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
05-19 09:22:25.531  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:22:25.531  9689  9753 D BluetoothAdapter: STATE_ON
05-19 09:22:25.531  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
05-19 09:22:25.531  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
05-19 09:22:25.531  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 4
,05-19 09:22:25.541  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:22:25.541  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:22:25.541  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-135,7,main], id: 135
,05-19 09:22:25.541  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
05-19 09:22:25.541  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
05-19 09:22:25.541  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b1b48b8e-977b-494d-8afb-10acf9d32846", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
05-19 09:22:25.541  9689  9753 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 A8 81 95 E9 5F 6F
05-19 09:22:25.541  9689  9753 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b1b48b8e-977b-494d-8afb-10acf9d32846], mManufacturerSpecificData={}, mServiceData={b1b48b8e-977b-494d-8afb-10acf9d32846=[4, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-19 09:22:25.541  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b1b48b8e-977b-494d-8afb-10acf9d32846], mManufacturerSpecificData={}, mServiceData={b1b48b8e-977b-494d-8afb-10acf9d32846=[4, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-19 09:22:25.541  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:22:25.541  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b1b48b8e-977b-494d-8afb-10acf9d32846], mManufacturerSpecificData={}, mServiceData={b1b48b8e-977b-494d-8afb-10acf9d32846=[4, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:22:25.541  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
05-19 09:22:25.541  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b1b48b8e-977b-494d-8afb-10acf9d32846], mManufacturerSpecificData={}, mServiceData={b1b48b8e-977b-494d-8afb-10acf9d32846=[4, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,05-19 09:22:25.541  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:22:25.541  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-135,7,main], id: 135
05-19 09:22:25.541  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[b1b48b8e-977b-494d-8afb-10acf9d32846], mManufacturerSpecificData={}, mServiceData={b1b48b8e-977b-494d-8afb-10acf9d32846=[4, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:22:25.541  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:22:25.541  9689  9753 D BluetoothAdapter: STATE_ON
05-19 09:22:25.541  9689  9753 D BluetoothLeAdvertiser: start advertising
,05-19 09:22:25.541  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:22:25.551  9787  9826 D BtGatt.GattService: registerClient() - UUID=fea5959f-b96c-41a5-87e5-a920875120a1
,05-19 09:22:25.601  9787  9804 D BtGatt.GattService: onClientRegistered() - UUID=fea5959f-b96c-41a5-87e5-a920875120a1, clientIf=7
,05-19 09:22:25.601  9689  9747 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,05-19 09:22:25.611  9787  9895 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,05-19 09:22:25.621  9787  9895 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
,05-19 09:22:25.621  9787  9895 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
05-19 09:22:25.621  9787  9806 D BtGatt.AdvertiseManager: message : 0
05-19 09:22:25.621  9787  9815 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.rockwellautomation.thalitest, msg: MESSAGE_START_ADV
05-19 09:22:25.621  9787  9815 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 19, currDate: 19
,05-19 09:22:25.621  9787  9806 D BtGatt.AdvertiseManager: number of adv instance running = 0
05-19 09:22:25.621  9787  9806 D BtGatt.AdvertiseManager: size of list is =0
,05-19 09:22:25.631  9787  9806 D BtGatt.AdvertiseManager: starting advertising
,05-19 09:22:25.631  9787  9815 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.rockwellautomation.thalitest : 5
,05-19 09:22:25.631  9787  9815 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.rockwellautomation.thalitest@LowLatency : 24919642
05-19 09:22:25.631  9787  9815 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.rockwellautomation.thalitest@LowLatency : 2
05-19 09:22:25.631  9787  9806 D BtGatt.AdvertiseManager: isStandardAdv = false
05-19 09:22:25.631  9787  9815 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
,05-19 09:22:25.631  9787  9815 D BtGatt.GattService: [GSIM LOG]: com.rockwellautomation.thalitest@LowLatency, R time : 0 => 0
,05-19 09:22:25.641  3511  4198 V AlarmManager:  remove PendingIntent] PendingIntent{3ffa89e: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:22:25.651  9787  9804 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,05-19 09:22:25.651  3511  4422 V AlarmManager:  remove PendingIntent] PendingIntent{16f1f7f: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:22:25.651  9787  9806 D BtGatt.AdvertiseManager: starting multi advertising
,05-19 09:22:25.661  9787  9804 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,05-19 09:22:25.661  9787  9806 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
05-19 09:22:25.661  9787  9806 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
05-19 09:22:25.661  9787  9806 D BtGatt.AdvertiseManager: postCallback clientIf = 7 status = 0
05-19 09:22:25.661  9787  9806 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=7, status=0, isStart=true
,05-19 09:22:25.661  9689  9699 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
05-19 09:22:25.661  3511  4451 V AlarmManager:  remove PendingIntent] PendingIntent{3234b4c: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:22:25.661  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:22:25.661  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-135,7,main], id: 135
05-19 09:22:25.661  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
05-19 09:22:25.661  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:22:25.661  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-135,7,main], id: 135
,05-19 09:22:25.661  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-135,7,main], id: 135
05-19 09:22:25.661  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:22:25.661  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:22:25.661  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,05-19 09:22:25.671  9689  9753 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,05-19 09:22:25.671  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-135,7,main], id: 135
,05-19 09:22:25.671  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-135,7,main], id: 135
,05-19 09:22:25.671  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:22:25.671  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:22:25.671  9689  9689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
05-19 09:22:25.671  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
05-19 09:22:25.681  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
05-19 09:22:25.681  3511  4449 V AlarmManager:  remove PendingIntent] PendingIntent{fc06795: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:22:25.681  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
05-19 09:22:25.681  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
05-19 09:22:25.681  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
05-19 09:22:25.681  9689  9689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,05-19 09:22:25.681  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
05-19 09:22:25.681  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
05-19 09:22:25.681  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
05-19 09:22:25.681  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
05-19 09:22:25.681  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
,05-19 09:22:25.681  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
05-19 09:22:25.681  9689  9689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
05-19 09:22:25.681  9689  9689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,05-19 09:22:25.681  9689  9689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,05-19 09:22:25.681  9689  9689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
05-19 09:22:25.681  9689  9689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
05-19 09:22:25.681  9689  9689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
05-19 09:22:25.681  9689  9689 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,05-19 09:22:25.691  3511  4422 V AlarmManager:  remove PendingIntent] PendingIntent{6b9b0aa: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:22:25.691  3511  3528 V AlarmManager:  remove PendingIntent] PendingIntent{e60349b: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:22:25.701  3511  4451 V AlarmManager:  remove PendingIntent] PendingIntent{9dfd038: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:22:25.701  3511  4459 V AlarmManager:  remove PendingIntent] PendingIntent{90ce811: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:22:26.181  9689  9753 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
05-19 09:22:26.181  9689  9753 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
05-19 09:22:26.181  9689  9753 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
05-19 09:22:26.181  9689  9753 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
05-19 09:22:26.181  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
05-19 09:22:26.181  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
05-19 09:22:26.181  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
05-19 09:22:26.181  9689  9753 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
05-19 09:22:26.181  9689  9753 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
05-19 09:22:26.181  9689  9753 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
05-19 09:22:26.181  9689 10342 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
05-19 09:22:26.181  9689  9753 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
05-19 09:22:26.181  9689 10342 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
05-19 09:22:26.181  9689 10342 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
05-19 09:22:26.181  9689  9689 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
05-19 09:22:26.181  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:22:26.181  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
05-19 09:22:26.181  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
05-19 09:22:26.181  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:22:26.181  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:22:26.181  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:22:26.181  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:22:26.191  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:22:26.191  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:22:26.191  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,05-19 09:22:26.191  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:22:26.191  9689  9753 D BluetoothAdapter: STATE_ON
05-19 09:22:26.191  9689  9753 D BluetoothLeScanner: could not find callback wrapper
,05-19 09:22:26.191  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
05-19 09:22:26.201  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:22:26.201  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:22:26.201  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:22:26.201  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
05-19 09:22:26.201  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-135,7,main], id: 135
,05-19 09:22:26.201  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:22:26.201  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:22:26.201  9689  9753 D BluetoothLeAdvertiser: stop advertising
,05-19 09:22:26.211  9787  9840 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
,05-19 09:22:26.211  9787  9840 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
05-19 09:22:26.211  9787  9806 D BtGatt.AdvertiseManager: message : 1
05-19 09:22:26.211  9787  9815 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.rockwellautomation.thalitest, msg: MESSAGE_STOP_ADV
05-19 09:22:26.211  9787  9815 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 19, currDate: 19
05-19 09:22:26.211  9787  9815 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
,05-19 09:22:26.211  9787  9815 D BtGatt.GattService: [GSIM LOG]: com.rockwellautomation.thalitest@LowLatency, R time : 0 => 0
05-19 09:22:26.211  9787  9806 D BtGatt.AdvertiseManager: stop advertise for client =  7
05-19 09:22:26.211  9787  9806 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 7
05-19 09:22:26.211  9787  9815 D BtGatt.GattService: [GSIM LOG]: remove : com.rockwellautomation.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
,05-19 09:22:26.211  9787  9806 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,05-19 09:22:26.221  3511  4449 V AlarmManager:  remove PendingIntent] PendingIntent{75a2d76: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:22:26.221  9787  9804 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
05-19 09:22:26.221  9787  9804 D BtGatt.GattService: Client app is not null!
,05-19 09:22:26.221  9689  9747 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,05-19 09:22:26.221  9787  9798 D BtGatt.GattService: unregisterClient() - clientIf=7
,05-19 09:22:26.231  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
05-19 09:22:26.231  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-135,7,main], id: 135
,05-19 09:22:26.231  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
05-19 09:22:26.231  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:22:26.231  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:22:26.231  3511  4070 V AlarmManager:  remove PendingIntent] PendingIntent{a837f77: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:22:26.231  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:22:26.231  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,05-19 09:22:26.231  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
05-19 09:22:26.231  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
05-19 09:22:26.231  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-135,7,main], id: 135
,05-19 09:22:26.231  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-135,7,main], id: 135
,05-19 09:22:26.231  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
05-19 09:22:26.231  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:22:26.231  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-135,7,main], id: 135
,05-19 09:22:26.241  9689  9689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
05-19 09:22:26.241  9689  9689 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
05-19 09:22:26.241  9689  9689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,05-19 09:22:26.241  9689  9689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
05-19 09:22:26.241  3511  4343 V AlarmManager:  remove PendingIntent] PendingIntent{7ddb7e4: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:22:26.241  9689  9689 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
05-19 09:22:26.241  9689  9689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
05-19 09:22:26.241  9689  9689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
05-19 09:22:26.241  9689  9689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
05-19 09:22:26.241  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
05-19 09:22:26.241  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
05-19 09:22:26.241  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
05-19 09:22:26.241  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
05-19 09:22:26.241  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,05-19 09:22:26.241  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
05-19 09:22:26.241  9689  9689 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,05-19 09:22:26.251  3511  4185 V AlarmManager:  remove PendingIntent] PendingIntent{5c6f44d: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:22:26.251  3511  4407 V AlarmManager:  remove PendingIntent] PendingIntent{4b3ab02: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:22:26.261  3511  4422 V AlarmManager:  remove PendingIntent] PendingIntent{4269c13: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:22:26.261  3511  3529 V AlarmManager:  remove PendingIntent] PendingIntent{1b06e50: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:22:26.271  3511  4847 V AlarmManager:  remove PendingIntent] PendingIntent{b9b8849: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:22:26.741  9689  9689 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,05-19 09:22:27.081  3511  3654 D PowerManagerService: [s] UserActivityState : 2 -> 4
,05-19 09:22:27.081  3511  3654 I PowerManagerService: [PWL] On : 0 (252514 ms ago)
05-19 09:22:27.081  3511  3654 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4
,05-19 09:22:28.371  3511  4144 E Watchdog: !@Sync 8 [05-19 09:22:28.382]
,05-19 09:22:29.241  9689  9753 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
05-19 09:22:29.241  9689  9753 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
05-19 09:22:29.241  9689  9753 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
05-19 09:22:29.241  9689  9753 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
05-19 09:22:29.241  9689  9753 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
05-19 09:22:29.251  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
05-19 09:22:29.251  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,05-19 09:22:29.261  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,05-19 09:22:29.261  9689  9753 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
05-19 09:22:29.261  9689  9753 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,05-19 09:22:29.261  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:22:29.271  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:22:29.271  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:22:29.281  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:22:29.281  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,05-19 09:22:29.281  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:22:29.281  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:22:29.281  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
05-19 09:22:29.281  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
05-19 09:22:29.281  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 4
,05-19 09:22:29.291  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:22:29.291  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:22:29.301  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:22:29.311  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:22:29.311  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-135,7,main], id: 135
,05-19 09:22:29.311  9689  9753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
05-19 09:22:29.311  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
05-19 09:22:29.311  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 13612
,05-19 09:22:29.311  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=13612, mManufacturerData=null, mManufacturerDataMask=null]
05-19 09:22:29.311  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:22:29.311  9689  9753 D BluetoothLeScanner: Start Scan
,05-19 09:22:29.311  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:22:29.321  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:22:29.321  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:22:29.331  9689  9753 D BluetoothAdapter: STATE_ON
,05-19 09:22:29.331  9787  9826 D BtGatt.GattService: registerClient() - UUID=171e6d20-d05b-48d0-8ce9-61bff43616ef
,05-19 09:22:29.371  9787  9804 D BtGatt.GattService: onClientRegistered() - UUID=171e6d20-d05b-48d0-8ce9-61bff43616ef, clientIf=7
,05-19 09:22:29.381  9689  9700 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=7
,05-19 09:22:29.381  9787  9895 D BtGatt.GattService: start scan with filters
,05-19 09:22:29.381  9787  9895 D BtGatt.GattService: getScanSettings
,05-19 09:22:29.391  3511  4422 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,05-19 09:22:29.391  3511  4422 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4350, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-19 09:22:29.391  3511  4422 D BatteryService: online:4, current avg:162, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:192
,05-19 09:22:29.391  3511  3511 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-19 09:22:29.401  3511  3511 I MotionRecognitionService: Plugged
,05-19 09:22:29.401  3511  3511 D MotionRecognitionService:   cableConnection= 1
05-19 09:22:29.401  3511  3511 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-19 09:22:29.401  3511  3511 D MotionRecognitionService: skip setTransmitPower. 
,05-19 09:22:29.411  3511  3860 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-19 09:22:29.411  3939  3939 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,05-19 09:22:29.411  3939  3939 D KeyguardUpdateMonitor: handleBatteryUpdate
05-19 09:22:29.411  3939  3939 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-19 09:22:29.411  3939  3939 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,05-19 09:22:29.411  3939  3939 D PowerUI.Notification: There is no change about charging status, so return!
,05-19 09:22:29.421  4867  4867 D CommonServiceConfiguration: getStringValueSetting
,05-19 09:22:29.431  9787  9787 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-19 09:22:29.431  9787  9827 D HeadsetStateMachine: Disconnected process message: 10, size: 0
05-19 09:22:29.431  4867  4867 D BatteryMonitor: new battery level: 100
05-19 09:22:29.431  9787  9895 D BtGatt.GattService: Is it foreground application = true
05-19 09:22:29.431  9787  9895 D BtGatt.GattService: not a background application
,05-19 09:22:29.431  3939  3939 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,05-19 09:22:29.431  3939  3939 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,05-19 09:22:29.451  9787  9895 D BtGatt.GattService: [GSIM LOG]: getActualScanMode (2/100 vs -2147483648/0)
,05-19 09:22:29.451  9787  9895 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
,05-19 09:22:29.451  9787  9895 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
05-19 09:22:29.451  9787  9815 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.rockwellautomation.thalitest, msg: MESSAGE_START_SCAN
,05-19 09:22:29.451  9787  9815 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 19, currDate: 19
05-19 09:22:29.451  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
05-19 09:22:29.451  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:22:29.451  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
05-19 09:22:29.451  9689  9753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:22:29.451  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,05-19 09:22:29.451  9787  9807 D BtGatt.ScanManager: handling starting scan
05-19 09:22:29.451  9689  9689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
05-19 09:22:29.451  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
05-19 09:22:29.451  9787  9807 D BtGatt.ScanManager: isFilteringSupported
05-19 09:22:29.451  9787  9807 D BluetoothAdapter: enableStandAloneBleMode=
05-19 09:22:29.451  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
05-19 09:22:29.451  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
05-19 09:22:29.451  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,05-19 09:22:29.451  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
05-19 09:22:29.451  9689  9689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
05-19 09:22:29.451  9689  9689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
05-19 09:22:29.451  9787  9807 D BluetoothAdapter: STATE_ON
05-19 09:22:29.451  9689  9753 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
05-19 09:22:29.451  9787  9807 D BluetoothAdapter: STATE_ON
05-19 09:22:29.451  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:22:29.461  9787  9807 D BluetoothAdapter: STATE_ON
05-19 09:22:29.461  9787  9815 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.rockwellautomation.thalitest : 1
,05-19 09:22:29.461  9787  9815 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.rockwellautomation.thalitest, com.rockwellautomation.thalitest
05-19 09:22:29.461  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:22:29.461  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
05-19 09:22:29.461  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-135,7,main], id: 135
,05-19 09:22:29.461  9689  9753 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-135,7,main], id: 135
05-19 09:22:29.461  9689  9689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
05-19 09:22:29.461  9787  9807 D BluetoothAdapter: STATE_ON
,05-19 09:22:29.461  9787  9807 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ca63953
,05-19 09:22:29.471  9787  9815 D BtGatt.GattService: [GSIM LOG]: increaseScanCount 4 Battery : com.rockwellautomation.thalitest : 1
,05-19 09:22:29.471  3511  3528 V AlarmManager:  remove PendingIntent] PendingIntent{40b6005: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:22:29.471  9787  9815 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.rockwellautomation.thalitest : 24919642
05-19 09:22:29.471  3511  4847 V AlarmManager:  remove PendingIntent] PendingIntent{8f7985a: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:22:29.471  9787  9815 D BtGatt.GattService: [GSIM LOG]: setRequestedScanType : com.rockwellautomation.thalitest : 2
05-19 09:22:29.471  9787  9815 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.rockwellautomation.thalitest : 2
,05-19 09:22:29.471  9689  9689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
05-19 09:22:29.471  9689  9689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
05-19 09:22:29.471  9689  9689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
05-19 09:22:29.471  9787  9815 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
05-19 09:22:29.471  9689  9689 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
05-19 09:22:29.471  9787  9804 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
05-19 09:22:29.471  9787  9804 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
05-19 09:22:29.471  9787  9807 D BtGatt.ScanManager: set filter index= 3 for clientIf= 7
05-19 09:22:29.471  9787  9807 D BtGatt.ScanManager: High Rssi Filter value is = -128
05-19 09:22:29.471  9787  9807 D BtGatt.ScanManager: Low Rssi Filter value is = -128
05-19 09:22:29.471  9787  9807 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =2
,05-19 09:22:29.481  9787  9815 D BtGatt.GattService: [GSIM LOG]: com.rockwellautomation.thalitest@LowLatency, R time : 0 => 0
,05-19 09:22:29.481  9787  9804 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=31
05-19 09:22:29.481  9787  9804 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
05-19 09:22:29.481  3511  4313 V AlarmManager:  remove PendingIntent] PendingIntent{1737a8b: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:22:29.481  9787  9807 D BtGatt.ScanManager: Starting BLE batch scan
05-19 09:22:29.481  9787  9807 D BtGatt.ScanManager: configuring batch scan storage, appIf 7
,05-19 09:22:29.481  9787  9804 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=7, status=0
,05-19 09:22:29.481  9787  9804 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,05-19 09:22:29.481  9787  9804 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=1
05-19 09:22:29.481  9787  9804 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
05-19 09:22:29.481  3511  3852 V AlarmManager:  remove PendingIntent] PendingIntent{3b768: PendingIntentRecord{fcb4a43 com.android.bluetooth broadcastIntent}}
,05-19 09:22:29.481  9787  9815 D BtGatt.GattService: [GSIM LOG]: com.rockwellautomation.thalitest@LowLatency, A time : 0 => 0
05-19 09:22:29.481  9787  9815 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
,05-19 09:22:29.481  9787  9815 D BtGatt.GattService: [GSIM LOG]: com.rockwellautomation.thalitest@LowLatency, R time : 0 => 0
05-19 09:22:29.481  3511  4422 V AlarmManager:  remove PendingIntent] PendingIntent{5e6f781: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:22:29.481  9787  9815 D BtGatt.GattService: [GSIM LOG]: com.rockwellautomation.thalitest@LowLatency, A time : 0 => 0
05-19 09:22:29.481  9787  9815 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.rockwellautomation.thalitest : 2
05-19 09:22:29.481  9787  9815 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
05-19 09:22:29.491  9787  9815 D BtGatt.GattService: [GSIM LOG]: com.rockwellautomation.thalitest@LowLatency, R time : 0 => 0
,05-19 09:22:29.491  9787  9815 D BtGatt.GattService: [GSIM LOG]: com.rockwellautomation.thalitest@LowLatency, A time : 0 => 0
05-19 09:22:29.491  9787  9815 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.rockwellautomation.thalitest : 24919642
,05-19 09:22:29.491  3511  4451 V AlarmManager:  remove PendingIntent] PendingIntent{186e026: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:22:29.491  3511  4070 V AlarmManager:  remove PendingIntent] PendingIntent{21d3467: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:22:29.501  3511  4343 V AlarmManager:  remove PendingIntent] PendingIntent{b10e214: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:22:29.501  3511  3852 V AlarmManager:  remove PendingIntent] PendingIntent{a8a8abd: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:22:29.511  3511  3984 V AlarmManager:  remove PendingIntent] PendingIntent{e70d8b2: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:22:29.511  3511  3529 V AlarmManager:  remove PendingIntent] PendingIntent{3beb003: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:22:29.511  3511  4459 V AlarmManager:  remove PendingIntent] PendingIntent{7240b80: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:22:29.521  3511  4185 V AlarmManager:  remove PendingIntent] PendingIntent{ada15b9: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:22:29.521  3511  3982 V AlarmManager:  remove PendingIntent] PendingIntent{78fcdfe: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:22:29.531  3511  4422 V AlarmManager:  remove PendingIntent] PendingIntent{972495f: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:22:29.871  4378  4466 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
05-19 09:22:29.871  4378  4466 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,05-19 09:22:29.981  9689  9689 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
05-19 09:22:29.981  9689  9689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
05-19 09:22:29.981  9689  9689 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,05-19 09:22:30.021  3511  6156 D SSRM:n  : SIOP:: AP = 290, PST = 307 (W:14), CP = 250, CUR = 162, LCD = 30
,05-19 09:22:30.481  3511  3814 V AlarmManager: Expired Alarm result :4
,05-19 09:22:30.491  9787  9787 D BtGatt.ScanManager: awakened up at time 255934
,05-19 09:22:30.491  9787  9807 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,05-19 09:22:30.491  3511  4459 V AlarmManager:  remove PendingIntent] PendingIntent{ffd5475: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
05-19 09:22:30.501  9787  9804 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=0
05-19 09:22:30.501  9787  9804 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,05-19 09:22:30.501  3511  4070 V AlarmManager:  remove PendingIntent] PendingIntent{616cc0a: PendingIntentRecord{fcb4a43 com.android.bluetooth broadcastIntent}}
,05-19 09:22:30.521  3511  4449 V AlarmManager:  remove PendingIntent] PendingIntent{39c1c7b: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:22:30.521  3511  4198 V AlarmManager:  remove PendingIntent] PendingIntent{c47ca98: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:22:31.511  3511  3814 V AlarmManager: Expired Alarm result :4
,05-19 09:22:31.511  9787  9787 D BtGatt.ScanManager: awakened up at time 256950
,05-19 09:22:31.511  9787  9807 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,05-19 09:22:31.521  3511  4313 V AlarmManager:  remove PendingIntent] PendingIntent{15d9ed6: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:22:31.521  9787  9804 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=0
05-19 09:22:31.521  9787  9804 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
05-19 09:22:31.531  3511  4343 V AlarmManager:  remove PendingIntent] PendingIntent{ac60557: PendingIntentRecord{fcb4a43 com.android.bluetooth broadcastIntent}}
,05-19 09:22:31.531  3511  4198 V AlarmManager:  remove PendingIntent] PendingIntent{43af844: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}
,05-19 09:22:31.541  3511  4407 V AlarmManager:  remove PendingIntent] PendingIntent{d589d2d: PendingIntentRecord{e39c5c1 com.android.bluetooth broadcastIntent}}

```
