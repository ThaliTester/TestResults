#### Test 969189475a60225_thali03_samsung-SM-G930F Logs


```
--------- beginning of system
,01-27 16:49:18.852  3465  6030 D SSRM:n  : SIOP:: AP = 310, PST = 324 (W:14), CP = 275, CUR = 143, LCD = 40
01-27 16:49:19.112  3465  4487 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
01-27 16:49:19.112  3465  4487 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4347, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
01-27 16:49:19.112  3465  4487 D BatteryService: online:4, current avg:141, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:156
01-27 16:49:19.112  3465  3465 D BatteryService: Sending ACTION_BATTERY_CHANGED.
01-27 16:49:19.112  3465  3465 I MotionRecognitionService: Plugged
01-27 16:49:19.112  3465  3465 D MotionRecognitionService:   cableConnection= 1
01-27 16:49:19.112  3465  3465 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
01-27 16:49:19.112  3465  3465 D MotionRecognitionService: skip setTransmitPower. 
--------- beginning of main
01-27 16:49:19.122  3465  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
01-27 16:49:19.122  3950  3950 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
01-27 16:49:19.122  3950  3950 D KeyguardUpdateMonitor: handleBatteryUpdate
01-27 16:49:19.122  3950  3950 D PowerUI : priorPlugType = 2 mPlugType =  2
01-27 16:49:19.122  3950  3950 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
01-27 16:49:19.122  3950  3950 D PowerUI.Notification: There is no change about charging status, so return!
01-27 16:49:19.142  4990  4990 D CommonServiceConfiguration: getStringValueSetting
01-27 16:49:19.142  4942  4942 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
01-27 16:49:19.152  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
01-27 16:49:19.142  4942  5321 D HeadsetStateMachine: Disconnected process message: 10, size: 0
01-27 16:49:19.152  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
01-27 16:49:19.152  4990  4990 D BatteryMonitor: new battery level: 100
01-27 16:49:19.322  9577  9577 I FIPS_bssl: FIPS approved mode (1) | 9577 | app_process
01-27 16:49:19.322  9577  9577 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
01-27 16:49:19.322  9577  9577 D AndroidRuntime: CheckJNI is OFF
01-27 16:49:19.322  9577  9577 D AndroidRuntime: readGMSProperty: start
01-27 16:49:19.322  9577  9577 D AndroidRuntime: readGMSProperty: already setted!!
01-27 16:49:19.322  9577  9577 D AndroidRuntime: propertySet: couldn't set property (it is from app)
01-27 16:49:19.322  9577  9577 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
01-27 16:49:19.322  9577  9577 D AndroidRuntime: readGMSProperty: end
01-27 16:49:19.322  9577  9577 D AndroidRuntime: addProductProperty: start
01-27 16:49:19.342  9577  9577 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
01-27 16:49:19.372  9577  9577 I Radio-JNI: register_android_hardware_Radio DONE
01-27 16:49:19.372  9577  9577 E AffinityControl: AffinityControl: registerfunction enter
01-27 16:49:19.382  9577  9577 D AndroidRuntime: Calling main entry com.android.commands.am.Am
01-27 16:49:19.412  3465  4042 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
01-27 16:49:19.412  3465  4042 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
01-27 16:49:19.452  3465  4042 D ResourcesManager: For user 0 new overlays fetched Null
01-27 16:49:19.452  3465  4042 D GameManagerService: identifyGamePackage. com.test.thalitest
01-27 16:49:19.452  3465  4042 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
01-27 16:49:19.452  3465  4042 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3465  pkgName : ACTIVITY_RESUME_BOOSTER@3
01-27 16:49:19.452  3465  4042 D ActivityManager: mDVFSHelper.acquire()
01-27 16:49:19.452  3465  4042 V WindowManager: addAppToken: AppWindowToken{d09de2eb6 token=Token{b872651 ActivityRecord{77f1f78 u0 com.test.thalitest/.MainActivity t5}}} to stack=2 task=5 at 0
01-27 16:49:19.472  3465  4042 D InputDispatcher: Focused application set to: xxxx
01-27 16:49:19.472  3465  4042 D InputDispatcher: Focus left window: 6097
01-27 16:49:19.472  3465  3540 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{9075f93 u0 d0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}
01-27 16:49:19.482  3465  3560 I InjectionManager: Inside getClassLibPath caller 
01-27 16:49:19.482  3465  3560 D SecWifiDisplayUtil: Metadata value : SecSettings2
01-27 16:49:19.482  9577  9577 D AndroidRuntime: Shutting down VM
01-27 16:49:19.482  3950  3950 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=8000 newVal=8600 diff=600
01-27 16:49:19.482  3465  3560 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{a905e8e V.E...... R.....ID 0,0-0,0}
01-27 16:49:19.482  3465  3560 D ISSUE_DEBUG: InputChannelName : 3d04abc Starting com.test.thalitest
01-27 16:49:19.492  3465  3560 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3465 uid:1000
01-27 16:49:19.492  3465  3560 D PointerIcon: setMouseCustomIcon IconType is same.101
01-27 16:49:19.492  3014  3014 I SurfaceFlinger: id=18 createSurf (1x1),1 flag=404, uhalitest
01-27 16:49:19.492  9588  9588 E Zygote  : v2
01-27 16:49:19.492  9588  9588 I libpersona: KNOX_SDCARD checking this for 10074
01-27 16:49:19.492  9588  9588 I libpersona: KNOX_SDCARD not a persona
01-27 16:49:19.492  3465  4487 I ActivityManager: Start proc 9588:com.test.thalitest/u0a74 for activity com.test.thalitest/.MainActivity
01-27 16:49:19.492  9588  9588 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
01-27 16:49:19.492  9588  9588 E Zygote  : accessInfo : 0
01-27 16:49:19.492  9588  9588 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
01-27 16:49:19.502  3465  3560 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
01-27 16:49:19.502  3465  3858 D NetworkPolicy: isUidForegroundLocked: 10074, mScreenOn: true, uidstate: -1, mProxSensorScreenOff: false
01-27 16:49:19.512  9588  9588 D TimaKeyStoreProvider: TimaSignature is unavailable
01-27 16:49:19.512  9588  9588 D ActivityThread: Added TimaKeyStore provider
01-27 16:49:19.512  3465  3973 V WindowOrientationListener: setCurrentAppOrientation :-1
01-27 16:49:19.512  3465  3973 V WindowOrientationListener: OrientationSensorJudge.getProposedRotation, Rotation: -1
01-27 16:49:19.512  3465  3973 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
01-27 16:49:19.512  3465  3973 V WindowOrientationListener: OrientationSensorJudge.getProposedRotation, Rotation: -1
01-27 16:49:19.512  3465  3973 D ActivityManager:  Launching com.test.thalitest, updated priority
01-27 16:49:19.512  4314  4314 D Launcher.HomeView: onStop
01-27 16:49:19.512  6759  6759 V ActivityThread: updateVisibility : ActivityRecord{48ca612 token=android.os.BinderProxy@e2641a2 {com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity}} show : false
01-27 16:49:19.512  4314  4314 D capture : ----destroy
01-27 16:49:19.522  4314  4314 V ActivityThread: updateVisibility : ActivityRecord{2e7a518 token=android.os.BinderProxy@2252039 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
01-27 16:49:19.522  3014  3024 D libEGL  : eglTerminate EGLDisplay = 0x7fa6440e78
01-27 16:49:19.522  3014  3024 D libEGL  : eglTerminate EGLDisplay = 0x7fa6440e78
01-27 16:49:19.532  3465  3465 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
01-27 16:49:19.532  3014  3014 D libEGL  : eglInitialize EGLDisplay = 0x7fc1e5c6c8
01-27 16:49:19.532  3465  3560 V WindowStateAnimator: Finishing drawing window Window{3d04abc u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
01-27 16:49:19.542  3465  3538 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
01-27 16:49:19.542  9588  9588 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
01-27 16:49:19.542  3465  4382 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
01-27 16:49:19.542  9588  9588 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
01-27 16:49:19.542  3014  4368 D libEGL  : eglTerminate EGLDisplay = 0x7f9f4ffe78
01-27 16:49:19.542  3014  4368 D libEGL  : eglTerminate EGLDisplay = 0x7f9f4ffe78
01-27 16:49:19.552  3465  6030 D GameManagerService: identifyGamePackage. com.test.thalitest
01-27 16:49:19.552  3465  6030 D GameManagerService: identifyGamePackage. com.test.thalitest
01-27 16:49:19.552  9588  9588 D ResourcesManager: For user 0 new overlays fetched Null
01-27 16:49:19.552  3465  3540 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{3d04abc u0 d0 Starting com.test.thalitest}
01-27 16:49:19.552  3465  3557 D MARsDBManager: onChange - mSmartManagerObserver! Uri = content://com.samsung.android.sm/AppFreezer?MARs-self=true&MARs=true
01-27 16:49:19.562  4314  4314 D Launcher: onTrimMemory. Level: 20
01-27 16:49:19.562  9588  9588 I InjectionManager: Inside getClassLibPath caller 
01-27 16:49:19.562  3465  6030 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
01-27 16:49:19.562  9588  9588 D InjectionManager: InjectionManager
01-27 16:49:19.562  9588  9588 D InjectionManager: fillFeatureStoreMap com.test.thalitest
01-27 16:49:19.572  9588  9588 I InjectionManager: Constructor com.test.thalitest, Feature store :{}
01-27 16:49:19.572  9588  9588 I InjectionManager: featureStore :{}
01-27 16:49:19.572  3465  6030 D GameManagerService: identifyGamePackage. com.test.thalitest
01-27 16:49:19.572  3465  6030 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
01-27 16:49:19.572  9588  9588 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
01-27 16:49:19.572  9588  9588 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
01-27 16:49:19.572  9588  9588 D RelationGraph: garbageCollect()
01-27 16:49:19.572  3465  6030 D GameManagerService: identifyGamePackage. com.test.thalitest
01-27 16:49:19.572  3465  6030 D GameManagerService: identifyGamePackage. com.test.thalitest
01-27 16:49:19.572  9588  9588 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
01-27 16:49:19.572  3014  4368 D libEGL  : eglTerminate EGLDisplay = 0x7f9f4ffe78
01-27 16:49:19.572  3014  4368 D libEGL  : eglTerminate EGLDisplay = 0x7f9f4ffe78
01-27 16:49:19.592  9588  9588 I CordovaLog: Changing log level to DEBUG(3)
01-27 16:49:19.592  9588  9588 I CordovaActivity: Apache Cordova native platform version 6.0.0 is starting
01-27 16:49:19.592  9588  9588 D CordovaActivity: CordovaActivity.onCreate()
01-27 16:49:19.592  3465  3475 I art     : Background partial concurrent mark sweep GC freed 104839(8MB) AllocSpace objects, 62(1240KB) LOS objects, 30% free, 35MB/51MB, paused 1.767ms total 121.970ms
01-27 16:49:19.602  9588  9588 I WebViewFactory: Loading com.google.android.webview version 50.0.2661.86 (code 266108650)
01-27 16:49:19.612  9588  9588 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package com.google.android.webview
01-27 16:49:19.612  9588  9588 D ResourcesManager: For user 0 new overlays fetched Null
01-27 16:49:19.612  9588  9588 I InjectionManager: Inside getClassLibPath caller 
01-27 16:49:19.612  9588  9588 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
01-27 16:49:19.652  9588  9588 I cr_LibraryLoader: Time to load native libraries: 19 ms (timestamps 5731-5750)
01-27 16:49:19.652  9588  9588 I cr_LibraryLoader: Expected native library version number "50.0.2661.86", actual native library version number "50.0.2661.86"
01-27 16:49:19.672  9588  9602 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
01-27 16:49:19.682  9588  9588 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {5548134}
01-27 16:49:19.682  9588  9588 I cr_LibraryLoader: Expected native library version number "50.0.2661.86", actual native library version number "50.0.2661.86"
,01-27 16:49:19.702  9588  9588 I chromium: [INFO:library_loader_hooks.cc(143)] Chromium logging enabled: level = 0, default verbosity = 0
,01-27 16:49:19.742  9588  9588 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,01-27 16:49:19.802  3465  3882 D MdnieScenarioControlService:  packageName : com.test.thalitest    className : com.test.thalitest.MainActivity
,01-27 16:49:19.822  9588  9588 D libEGL  : eglInitialize EGLDisplay = 0xffd2e044
,01-27 16:49:19.862  3465  4416 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10074
01-27 16:49:19.872  3465  4416 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29757 com.android.server.am.ActivityManagerService.registerReceiver:22622 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,01-27 16:49:19.882  3465  3858 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: true, uidstate: 2, mProxSensorScreenOff: false
,01-27 16:49:19.902  3465  3882 I MdnieScenarioControlService: mGameModeLauncher : false
,01-27 16:49:19.902  3465  3882 I MdnieScenarioControlService: setUIMode
,01-27 16:49:19.902  9588  9588 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10074, CallingPid : 9588
,01-27 16:49:19.912  3465  4488 D ConnectivityService: listenForNetwork for Listen from uid/pid:10074/9588 for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,01-27 16:49:19.912  3465  3869 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
01-27 16:49:19.912  3465  3869 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -51]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,01-27 16:49:19.912  3465  3869 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,01-27 16:49:19.912  3465  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,01-27 16:49:19.912  3465  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,01-27 16:49:19.922  3465  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,01-27 16:49:19.922  9588  9588 D cr_Ime  : [InputMethodManagerWrapper.java:30] Constructor
,01-27 16:49:19.922  3465  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,01-27 16:49:19.922  3465  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,01-27 16:49:19.922  3465  3869 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
01-27 16:49:19.922  3014  4367 I SurfaceFlinger: id=9 Removed MauncherAct (4/14)
,01-27 16:49:19.922  3014  4368 I SurfaceFlinger: id=15 Removed YUIInstallC (4/13)
01-27 16:49:19.922  3014  3024 I SurfaceFlinger: id=9 Removed MauncherAct (-2/13)
01-27 16:49:19.922  3014  4500 I SurfaceFlinger: id=14 Removed YUIInstallC (4/12)
,01-27 16:49:19.922  3014  4368 I SurfaceFlinger: id=17 Removed VSBConnecti (4/11)
01-27 16:49:19.932  3014  3024 I SurfaceFlinger: id=16 Removed VSBConnecti (5/10)
01-27 16:49:19.932  3014  4368 I SurfaceFlinger: id=15 Removed YUIInstallC (-2/10)
01-27 16:49:19.932  3014  4367 I SurfaceFlinger: id=14 Removed YUIInstallC (-2/10)
01-27 16:49:19.932  3014  4368 I SurfaceFlinger: id=17 Removed VSBConnecti (-2/10)
01-27 16:49:19.932  3014  3026 I SurfaceFlinger: id=16 Removed VSBConnecti (-2/10)
,01-27 16:49:19.932  3950  3950 D ImageWallpaper: onVisibilityChanged:false
,01-27 16:49:19.932  3950  3950 D ImageWallpaper: drawFrame:false rotation:0 mLastRotation:0
01-27 16:49:19.932  3950  3950 D ImageWallpaper: drawFrame:[frame.width()]2240[frame.height()]2560
01-27 16:49:19.932  3950  3950 D ImageWallpaper: Suppressed drawFrame since redraw is not needed and offsets have not changed.
,01-27 16:49:19.932  9588  9588 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,01-27 16:49:19.942  9588  9588 D cr_Ime  : [InputMethodManagerWrapper.java:59] isActive: false
,01-27 16:49:19.942  3014  3014 D libEGL  : eglTerminate EGLDisplay = 0x7fc1e5c7e8
,01-27 16:49:19.942  3014  3014 D libEGL  : eglTerminate EGLDisplay = 0x7fc1e5c7e8
,01-27 16:49:19.942  3014  3014 D libEGL  : eglTerminate EGLDisplay = 0x7fc1e5c7e8
01-27 16:49:19.942  3014  3014 D libEGL  : eglTerminate EGLDisplay = 0x7fc1e5c7e8
,01-27 16:49:19.952  9588  9588 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,01-27 16:49:19.962  9588  9588 D PluginManager: init()
,01-27 16:49:19.962  9588  9588 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,01-27 16:49:19.972  9588  9588 I cr_Ime  : ImeThread is not enabled.
,01-27 16:49:19.972  9588  9588 D Activity: performCreate Call Injection manager
,01-27 16:49:19.972  9588  9588 D CordovaActivity: Started the activity.
,01-27 16:49:19.972  9588  9588 I InjectionManager: dispatchOnViewCreated > Target : com.test.thalitest.MainActivity isFragment :false
01-27 16:49:19.972  9588  9588 D CordovaActivity: Resumed the activity.
,01-27 16:49:19.982  9588  9588 D SecWifiDisplayUtil: Metadata value : SecSettings2
,01-27 16:49:19.982  9588  9588 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{838bd83 I.E...... R.....ID 0,0-0,0}
,01-27 16:49:19.982  9588  9637 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,01-27 16:49:19.992  3465  4485 D ISSUE_DEBUG: InputChannelName : 4f6aa87 com.test.thalitest/com.test.thalitest.MainActivity
,01-27 16:49:19.992  3465  4225 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
01-27 16:49:19.992  3465  4225 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
01-27 16:49:19.992  3465  3465 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,01-27 16:49:19.992  3465  3465 I KnoxTimeoutHandler: Shared devices show user statefalse
,01-27 16:49:19.992  9588  9588 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10074, CallingPid : 9588
,01-27 16:49:19.992  3465  3973 D ConnectivityService: listenForNetwork for Listen from uid/pid:10074/9588 for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
01-27 16:49:19.992  9588  9602 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
01-27 16:49:19.992  3465  3869 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
01-27 16:49:20.002  3465  3869 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -51]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
01-27 16:49:20.002  3465  3869 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
01-27 16:49:20.002  3465  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
01-27 16:49:20.002  3465  3858 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: true, uidstate: 6, mProxSensorScreenOff: false
01-27 16:49:20.002  3465  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
01-27 16:49:20.002  3465  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
01-27 16:49:20.012  3465  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
01-27 16:49:20.012  9588  9588 D SecWifiDisplayUtil: Metadata value : SecSettings2
01-27 16:49:20.012  3465  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
01-27 16:49:20.012  3465  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
01-27 16:49:20.012  3465  3869 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
01-27 16:49:20.012  3014  3014 I SurfaceFlinger: id=19 createSurf (1x1),1 flag=404, NainActivit
01-27 16:49:20.022  3465  3977 D InputDispatcher: Focus entered window: 9588
,01-27 16:49:20.032  3465  3560 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3465 uid:1000
01-27 16:49:20.032  3465  3560 D PointerIcon: setMouseCustomIcon IconType is same.101
01-27 16:49:20.032  9588  9637 D libEGL  : eglInitialize EGLDisplay = 0xdc1ff7c4
01-27 16:49:20.032  9588  9637 I OpenGLRenderer: Initialized EGL, version 1.4
,01-27 16:49:20.032  9588  9637 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,01-27 16:49:20.032  9588  9588 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
,01-27 16:49:20.042  9588  9588 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,01-27 16:49:20.062  9588  9641 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
01-27 16:49:20.062  9588  9641 D libEGL  : eglInitialize EGLDisplay = 0xdac6c3e4
,01-27 16:49:20.062  9588  9641 D libGLESv2: DTS_GLAPI : DTS is not allowed for Package : com.test.thalitest
,01-27 16:49:20.072  3014  3014 D libEGL  : eglInitialize EGLDisplay = 0x7fc1e5c6c8
,01-27 16:49:20.072  3465  4485 V WindowStateAnimator: Finishing drawing window Window{4f6aa87 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,01-27 16:49:20.072  3465  4225 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,01-27 16:49:20.082  3465  3560 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
01-27 16:49:20.082  3465  3465 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
01-27 16:49:20.082  3465  3560 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +601ms
01-27 16:49:20.082  3465  3560 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3465  tag : ACTIVITY_RESUME_BOOSTER@3
,01-27 16:49:20.082  3465  3465 I KnoxTimeoutHandler: SD activityfalse
01-27 16:49:20.082  3465  3560 D ActivityManager: mDVFSHelper.release()
01-27 16:49:20.082  3465  3560 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{77f1f78 u0 com.test.thalitest/.MainActivity t5} time:186181
01-27 16:49:20.082  3465  3538 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3465  pkgName : ACTIVITY_RESUME_BOOSTER@9
01-27 16:49:20.082  3465  3560 D ViewRootImpl: #3 mView = null
,01-27 16:49:20.082  4826  4826 D SamsungIME: IMPL finishInput
,01-27 16:49:20.082  4826  4826 D SamsungIME: SwiftKeyWrapper writeDBdataToFileOnFinishInput
01-27 16:49:20.082  4826  4826 D SamsungIME: saveAndClear +
01-27 16:49:20.082  4826  4826 D SamsungIME: saveAndClear -
,01-27 16:49:20.092  9588  9588 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
,01-27 16:49:20.092  9588  9588 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@c2682b time:186195
,01-27 16:49:20.092  6097  6097 V ActivityThread: updateVisibility : ActivityRecord{e861213 token=android.os.BinderProxy@981ed3d {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
,01-27 16:49:20.092  9588  9588 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9588
,01-27 16:49:20.102  9588  9588 D cr_Ime  : [InputMethodManagerWrapper.java:59] isActive: true
01-27 16:49:20.102  9588  9588 D cr_Ime  : [InputMethodManagerWrapper.java:68] hideSoftInputFromWindow
,01-27 16:49:20.102  3014  3014 D libEGL  : eglInitialize EGLDisplay = 0x7fc1e5c6c8
,01-27 16:49:20.122  3014  3014 D libEGL  : eglInitialize EGLDisplay = 0x7fc1e5c6c8
,01-27 16:49:20.152  9588  9588 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,01-27 16:49:20.282  3014  3026 I SurfaceFlinger: id=18 Removed uhalitest (7/10)
,01-27 16:49:20.282  3014  4500 I SurfaceFlinger: id=18 Removed uhalitest (-2/10)
,01-27 16:49:20.282  9588  9650 D jxcore_app_log: JniHelper::setJavaVM(0xf48f4000), pthread_self() = -688916176
,01-27 16:49:20.292  9588  9650 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
01-27 16:49:20.292  9588  9650 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
01-27 16:49:20.292  9588  9650 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
01-27 16:49:20.292  9588  9650 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
01-27 16:49:20.292  9588  9650 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
01-27 16:49:20.292  9588  9650 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d485e2 added. We now have 1 listener(s)
,01-27 16:49:20.292  9588  9650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d485e2 added. We now have 1 listener(s)
01-27 16:49:20.292  9588  9650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
01-27 16:49:20.292  9588  9650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
01-27 16:49:20.292  9588  9650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
01-27 16:49:20.292  9588  9650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: null
01-27 16:49:20.292  9588  9650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
01-27 16:49:20.292  9588  9650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
01-27 16:49:20.292  9588  9650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
01-27 16:49:20.292  9588  9650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
01-27 16:49:20.292  9588  9650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 256
01-27 16:49:20.292  9588  9650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
01-27 16:49:20.292  9588  9650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
01-27 16:49:20.292  9588  9650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
01-27 16:49:20.292  9588  9650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
01-27 16:49:20.292  9588  9650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,01-27 16:49:20.292  9588  9650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 44:78:3E:94:2C:E6
,01-27 16:49:20.292  9588  9650 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: ", Bluetooth MAC address: "44:78:3E:94:2C:E6"Peer extra info: "256
01-27 16:49:20.292  9588  9650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
01-27 16:49:20.292  9588  9650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,01-27 16:49:20.292  3014  3014 D libEGL  : eglTerminate EGLDisplay = 0x7fc1e5c7e8
,01-27 16:49:20.292  9588  9650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
01-27 16:49:20.292  9588  9650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cf2c8a9 added. We now have 2 listener(s)
01-27 16:49:20.292  9588  9650 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,01-27 16:49:20.292  9588  9650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
01-27 16:49:20.292  9588  9650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,01-27 16:49:20.292  9588  9650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,7,main], id: 137
01-27 16:49:20.292  9588  9650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
01-27 16:49:20.292  9588  9650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
01-27 16:49:20.292  9588  9650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
01-27 16:49:20.292  9588  9650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,7,main], id: 137
,01-27 16:49:20.302  9588  9650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
01-27 16:49:20.302  9588  9650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 44:78:3E:94:2C:E6
,01-27 16:49:20.302  9588  9650 D BluetoothAdapter: STATE_ON
,01-27 16:49:20.302  9588  9650 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,01-27 16:49:20.302  9588  9650 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
01-27 16:49:20.302  9588  9650 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
01-27 16:49:20.302  9588  9650 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
01-27 16:49:20.302  9588  9650 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
01-27 16:49:20.302  9588  9650 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
01-27 16:49:20.302  9588  9650 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
01-27 16:49:20.302  9588  9650 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
01-27 16:49:20.302  9588  9650 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
01-27 16:49:20.302  9588  9650 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
01-27 16:49:20.302  9588  9650 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
01-27 16:49:20.302  9588  9650 D io.jxcore.node.ConnectivityMonitor: start: OK
01-27 16:49:20.302  9588  9650 I io.jxcore.node.LifeCycleMonitor: start: OK
,01-27 16:49:20.312  9588  9588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,01-27 16:49:20.312  9588  9588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,01-27 16:49:20.322  9588  9588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,01-27 16:49:20.342  9588  9588 D SystemWebChromeClient: file:///android_asset/www/js/index.js: Line 36 : Uncaught TypeError: Cannot read property 'querySelector' of null
01-27 16:49:20.342  9588  9588 I chromium: [INFO:CONSOLE(36)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (36)
,01-27 16:49:20.342  9588  9588 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,01-27 16:49:20.362  3465  3882 D MdnieScenarioControlService:  packageName : com.test.thalitest    className : com.test.thalitest.MainActivity
,01-27 16:49:20.382  3465  3465 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3465  tag : ACTIVITY_RESUME_BOOSTER@9
,01-27 16:49:20.462  3465  3882 I MdnieScenarioControlService: mGameModeLauncher : false
,01-27 16:49:20.472  3465  3882 I MdnieScenarioControlService: setUIMode
,01-27 16:49:20.512  4025  4025 D Recents : onTaskStackChanged
,01-27 16:49:20.512  4025  4025 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.test.thalitest
,01-27 16:49:20.522  4025  4025 D ResourcesManager: For user 0 new overlays fetched Null
,01-27 16:49:20.552  3465  6031 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
,01-27 16:49:20.812  9588  9651 W jxcore-log: Initializing JXcore engine
01-27 16:49:20.812  9588  9651 W jxcore-log: JXcore engine is ready
,01-27 16:49:20.832  4953  4953 E audit   : type=1400 msg=audit(1485532160.832:264): avc:  denied  { ioctl } for  pid=9651 comm="Thread-138" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3203 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
01-27 16:49:20.832  4953  4953 E audit   :  SEPF_SECMOBILE_6.0.1_0031
01-27 16:49:20.832  4953  4953 E audit   : type=1300 msg=audit(1485532160.832:264): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=8 a1=5451 a2=2 a3=d61bf3c8 items=0 ppid=3191 pid=9651 auid=4294967295 uid=10074 gid=10074 euid=10074 suid=10074 fsuid=10074 egid=10074 sgid=10074 fsgid=10074 tty=(none) ses=4294967295 comm="Thread-138" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
01-27 16:49:20.832  4953  4953 E audit   : type=1327 msg=audit(1485532160.832:264): proctitle="com.test.thalitest"
01-27 16:49:20.832  4953  4953 E audit   : type=1320 msg=audit(1485532160.832:264): 
01-27 16:49:20.832  4953  4953 E audit   : type=1400 msg=audit(1485532160.832:265): avc:  denied  { ioctl } for  pid=9651 comm="Thread-138" path="socket:[33756]" dev="sockfs" ino=33756 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
01-27 16:49:20.832  4953  4953 E audit   :  SEPF_SECMOBILE_6.0.1_0031
01-27 16:49:20.832  4953  4953 E audit   : type=1300 msg=audit(1485532160.832:265): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=33 a1=5451 a2=2 a3=d61bf3c8 items=0 ppid=3191 pid=9651 auid=4294967295 uid=10074 gid=10074 euid=10074 suid=10074 fsuid=10074 egid=10074 sgid=10074 fsgid=10074 tty=(none) ses=4294967295 comm="Thread-138" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
01-27 16:49:20.832  4953  4953 E audit   : type=1327 msg=audit(1485532160.832:265): proctitle="com.test.thalitest"
01-27 16:49:20.832  4953  4953 E audit   : type=1320 msg=audit(1485532160.832:265): 
,01-27 16:49:20.842  9588  9651 W jxcore-log: Starting JXcore engine
,01-27 16:49:20.872  9588  9651 W jxcore-log: Platform android
01-27 16:49:20.872  9588  9651 W jxcore-log: 
01-27 16:49:20.872  9588  9651 W jxcore-log: Process ARCH arm
01-27 16:49:20.872  9588  9651 W jxcore-log: 
,01-27 16:49:21.002  9588  9651 I jxcore-log: JXcore Cordova bridge is ready!
01-27 16:49:21.002  9588  9651 I jxcore-log: 
01-27 16:49:21.002  9588  9651 W jxcore-log: JXcore engine is started
,01-27 16:49:21.012  9588  9650 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,01-27 16:49:21.012  9588  9588 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 41 : Application has the required permission.
01-27 16:49:21.012  9588  9588 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,01-27 16:49:22.462  3465  3907 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/5_task.xml.bak
,01-27 16:49:22.552  3465  6030 D GameManagerService: identifyGamePackage. com.test.thalitest
,01-27 16:49:23.392  3465  6068 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,01-27 16:49:25.602  3465  6030 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,01-27 16:49:27.662  3465  4152 E Watchdog: !@Sync 6 [01-27 16:49:27.669]
,01-27 16:49:27.912  9588  9651 I jxcore-log: 2017-01-27 15:49:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
01-27 16:49:27.912  9588  9651 I jxcore-log: 
,01-27 16:49:27.912  9588  9651 I jxcore-log: 2017-01-27 15:49:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
01-27 16:49:27.912  9588  9651 I jxcore-log: 
01-27 16:49:27.912  9588  9651 I jxcore-log: 2017-01-27 15:49:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
01-27 16:49:27.912  9588  9651 I jxcore-log: 
,01-27 16:49:27.922  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:49:27.932  9588  9651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
01-27 16:49:27.932  9588  9651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
01-27 16:49:27.932  9588  9651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
01-27 16:49:27.932  9588  9651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
01-27 16:49:27.932  9588  9651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
01-27 16:49:27.932  9588  9651 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
01-27 16:49:27.932  9588  9651 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
01-27 16:49:27.932  9588  9651 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
01-27 16:49:27.932  9588  9651 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,01-27 16:49:27.942  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:49:27.942  9588  9651 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,01-27 16:49:27.942  9588  9651 I jxcore-log: 2017-01-27 15:49:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
01-27 16:49:27.942  9588  9651 I jxcore-log: 
01-27 16:49:27.942  9588  9651 I jxcore-log: 2017-01-27 15:49:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
01-27 16:49:27.942  9588  9651 I jxcore-log: 
01-27 16:49:27.942  9588  9651 I jxcore-log: 2017-01-27 15:49:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
01-27 16:49:27.942  9588  9651 I jxcore-log: 
,01-27 16:49:28.092  9588  9651 D ExecuteNativeTests: Running unit tests
,01-27 16:49:28.092  9588  9651 D BluetoothAdapter: enable()
,01-27 16:49:28.102  9588  9651 D BluetoothAdapter: enable(): BT is already enabled..!
,01-27 16:49:28.112  3465  3538 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{33a2be4 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{47dcb8b 4974:com.samsung.android.providers.context/u0a7}
,01-27 16:49:28.112  9588  9651 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,01-27 16:49:28.122  3465  4331 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,01-27 16:49:28.122  3465  4331 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,01-27 16:49:28.132  3465  4331 D WifiService: setWifiEnabled: true pid=9588, uid=10074
,01-27 16:49:28.132  3465  4331 W ActivityManager: Permission Denial: getCurrentUser() from pid=9588, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
,01-27 16:49:28.142  3465  4331 W WifiService: Failed getting userId using ActivityManagerNative
01-27 16:49:28.142  3465  4331 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9588, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
01-27 16:49:28.142  3465  4331 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
01-27 16:49:28.142  3465  4331 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
01-27 16:49:28.142  3465  4331 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
01-27 16:49:28.142  3465  4331 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
01-27 16:49:28.142  3465  4331 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
,01-27 16:49:28.142  3465  3860 D WifiBigDataLog: getJsonFormat() - feature : ONOF
01-27 16:49:28.142  3465  4331 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
01-27 16:49:28.142  3465  4331 D SettingsProvider: isChangeAllowed() : name = wifi_on
01-27 16:49:28.142  3465  3863 D WifiStateMachine: setFccChannel: channel = -1
,01-27 16:49:28.142  3465  3863 D WifiController: [FCC]setFccChannel() is called !!!
01-27 16:49:28.142  3465  3863 D WifiController: [FCC]Airplane off, setFccChannel(-1)!!!
01-27 16:49:28.142  3465  3860 D WifiBigDataLog: init : 
,01-27 16:49:28.142  3465  3860 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,01-27 16:49:28.152  3465  3860 D WifiStateMachine: setFccChannelNative: channel = -1
,01-27 16:49:28.152  3465  3860 D WifiNative-wlan0: callSECApiInt - ID [230]
,01-27 16:49:28.162  3465  3538 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f7c584d u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{47dcb8b 4974:com.samsung.android.providers.context/u0a7}
,01-27 16:49:28.392  3465  4485 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,01-27 16:49:28.392  3465  4485 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4309, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
01-27 16:49:28.392  3465  4485 D BatteryService: online:4, current avg:-261, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:161
01-27 16:49:28.392  3465  3465 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,01-27 16:49:28.392  3465  3465 I MotionRecognitionService: Plugged
01-27 16:49:28.392  3465  3465 D MotionRecognitionService:   cableConnection= 1
01-27 16:49:28.392  3465  3465 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
01-27 16:49:28.392  3465  3465 D MotionRecognitionService: skip setTransmitPower. 
,01-27 16:49:28.392  3465  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,01-27 16:49:28.402  3950  3950 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
01-27 16:49:28.402  3950  3950 D KeyguardUpdateMonitor: handleBatteryUpdate
,01-27 16:49:28.402  3950  3950 D PowerUI : priorPlugType = 2 mPlugType =  2
,01-27 16:49:28.402  3950  3950 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
01-27 16:49:28.402  3950  3950 D PowerUI.Notification: There is no change about charging status, so return!
,01-27 16:49:28.412  4990  4990 D CommonServiceConfiguration: getStringValueSetting
,01-27 16:49:28.422  4942  4942 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,01-27 16:49:28.422  4942  5321 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,01-27 16:49:28.422  4990  4990 D BatteryMonitor: new battery level: 100
,01-27 16:49:28.432  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,01-27 16:49:28.432  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,01-27 16:49:28.522  4261  4329 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
01-27 16:49:28.522  4261  4329 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,01-27 16:49:28.662  4261  4329 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 132ms lastUpdatedAfter : 129200ms
,01-27 16:49:28.672  3465  4331 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
01-27 16:49:28.672  3465  4331 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4334, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
01-27 16:49:28.672  3465  4331 D BatteryService: online:4, current avg:-247, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:180
01-27 16:49:28.672  3465  3465 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,01-27 16:49:28.672  3465  3465 I MotionRecognitionService: Plugged
01-27 16:49:28.672  3465  3465 D MotionRecognitionService:   cableConnection= 1
01-27 16:49:28.672  3465  3465 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
01-27 16:49:28.672  3465  3465 D MotionRecognitionService: skip setTransmitPower. 
,01-27 16:49:28.682  3465  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,01-27 16:49:28.682  3950  3950 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,01-27 16:49:28.682  3950  3950 D KeyguardUpdateMonitor: handleBatteryUpdate
01-27 16:49:28.682  3950  3950 D PowerUI : priorPlugType = 2 mPlugType =  2
,01-27 16:49:28.682  3950  3950 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
01-27 16:49:28.682  3950  3950 D PowerUI.Notification: There is no change about charging status, so return!
,01-27 16:49:28.692  4990  4990 D CommonServiceConfiguration: getStringValueSetting
,01-27 16:49:28.692  4942  4942 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
01-27 16:49:28.692  4942  5321 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,01-27 16:49:28.702  4990  4990 D BatteryMonitor: new battery level: 100
,01-27 16:49:28.712  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,01-27 16:49:28.712  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,01-27 16:49:28.872  3465  6030 D SSRM:n  : SIOP:: AP = 390, PST = 327 (W:6), CP = 285, CUR = -247, LCD = 40
,01-27 16:49:28.882  3465  6030 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,01-27 16:49:28.892  3465  4225 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
01-27 16:49:28.892  3465  4225 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4328, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
01-27 16:49:28.892  3465  4225 D BatteryService: online:4, current avg:-242, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:95
01-27 16:49:28.902  3465  3465 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,01-27 16:49:28.902  3465  3465 I MotionRecognitionService: Plugged
01-27 16:49:28.902  3465  3465 D MotionRecognitionService:   cableConnection= 1
01-27 16:49:28.902  3465  3465 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
01-27 16:49:28.902  3465  3465 D MotionRecognitionService: skip setTransmitPower. 
,01-27 16:49:28.902  3465  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,01-27 16:49:28.902  3950  3950 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
01-27 16:49:28.902  3950  3950 D KeyguardUpdateMonitor: handleBatteryUpdate
,01-27 16:49:28.902  3950  3950 D PowerUI : priorPlugType = 2 mPlugType =  2
,01-27 16:49:28.902  3950  3950 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,01-27 16:49:28.902  3950  3950 D PowerUI.Notification: There is no change about charging status, so return!
,01-27 16:49:28.912  4990  4990 D CommonServiceConfiguration: getStringValueSetting
,01-27 16:49:28.912  4942  4942 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,01-27 16:49:28.912  4942  5321 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,01-27 16:49:28.922  4990  4990 D BatteryMonitor: new battery level: 100
,01-27 16:49:28.932  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,01-27 16:49:28.932  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,01-27 16:49:29.532  3465  3582 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,01-27 16:49:29.552  3465  3582 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,01-27 16:49:32.422  3465  4487 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
01-27 16:49:32.422  3465  4487 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4340, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
01-27 16:49:32.422  3465  4487 D BatteryService: online:4, current avg:-135, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-21
01-27 16:49:32.422  3465  3465 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,01-27 16:49:32.432  3465  3465 I MotionRecognitionService: Plugged
,01-27 16:49:32.432  3465  3465 D MotionRecognitionService:   cableConnection= 1
01-27 16:49:32.432  3465  3465 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
01-27 16:49:32.432  3465  3465 D MotionRecognitionService: skip setTransmitPower. 
,01-27 16:49:32.432  3465  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,01-27 16:49:32.442  3950  3950 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
01-27 16:49:32.442  3950  3950 D KeyguardUpdateMonitor: handleBatteryUpdate
,01-27 16:49:32.442  3950  3950 D PowerUI : priorPlugType = 2 mPlugType =  2
,01-27 16:49:32.442  3950  3950 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
01-27 16:49:32.442  3950  3950 D PowerUI.Notification: There is no change about charging status, so return!
,01-27 16:49:32.462  4990  4990 D CommonServiceConfiguration: getStringValueSetting
,01-27 16:49:32.472  4942  4942 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
01-27 16:49:32.472  4942  5321 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,01-27 16:49:32.472  4990  4990 D BatteryMonitor: new battery level: 100
,01-27 16:49:32.482  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,01-27 16:49:32.482  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,01-27 16:49:32.682  3465  3484 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
01-27 16:49:32.682  3465  3484 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4336, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
01-27 16:49:32.682  3465  3484 D BatteryService: online:4, current avg:-128, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:196
01-27 16:49:32.682  3465  3465 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,01-27 16:49:32.682  3465  3465 I MotionRecognitionService: Plugged
01-27 16:49:32.682  3465  3465 D MotionRecognitionService:   cableConnection= 1
01-27 16:49:32.682  3465  3465 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
01-27 16:49:32.682  3465  3465 D MotionRecognitionService: skip setTransmitPower. 
,01-27 16:49:32.682  3465  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,01-27 16:49:32.692  3950  3950 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
01-27 16:49:32.692  3950  3950 D KeyguardUpdateMonitor: handleBatteryUpdate
,01-27 16:49:32.692  3950  3950 D PowerUI : priorPlugType = 2 mPlugType =  2
01-27 16:49:32.692  3950  3950 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
01-27 16:49:32.692  3950  3950 D PowerUI.Notification: There is no change about charging status, so return!
,01-27 16:49:32.702  4990  4990 D CommonServiceConfiguration: getStringValueSetting
,01-27 16:49:32.702  4942  4942 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,01-27 16:49:32.702  4942  5321 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,01-27 16:49:32.712  4990  4990 D BatteryMonitor: new battery level: 100
,01-27 16:49:32.722  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,01-27 16:49:32.722  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,01-27 16:49:38.152  9588  9651 I com.test.thalitest.ThaliTestRunner: Running UT
,01-27 16:49:38.232  9588  9651 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
01-27 16:49:38.232  9588  9651 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49a8aa8 added. We now have 2 listener(s)
01-27 16:49:38.232  9588  9651 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49a8aa8 added. We now have 3 listener(s)
01-27 16:49:38.232  9588  9651 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,01-27 16:49:38.232  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: ", Bluetooth MAC address: "44:78:3E:94:2C:E6"Peer extra info: "256
01-27 16:49:38.232  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
01-27 16:49:38.232  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
01-27 16:49:38.232  9588  9651 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
01-27 16:49:38.232  9588  9651 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fc69c1 added. We now have 4 listener(s)
01-27 16:49:38.232  9588  9651 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,01-27 16:49:38.232  9588  9651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,01-27 16:49:38.242  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:49:38.262  9588  9651 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
,01-27 16:49:38.262  9588  9651 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,01-27 16:49:38.272  9588  9651 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,01-27 16:49:38.272  9588  9651 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,01-27 16:49:38.272  9588  9651 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [00:11:22:33:44:55] timed out,
,01-27 16:49:38.272  9588  9651 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
01-27 16:49:38.272  9588  9651 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,01-27 16:49:38.272  9588  9651 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,01-27 16:49:38.272  9588  9651 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,01-27 16:49:38.272  9588  9651 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
,01-27 16:49:38.282  9588  9651 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,01-27 16:49:38.282  9588  9651 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
,01-27 16:49:38.282  9588  9651 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
,01-27 16:49:38.282  9588  9651 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,01-27 16:49:38.292  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,01-27 16:49:38.292  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:49:38.302  9588  9651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
01-27 16:49:38.302  9588  9651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
01-27 16:49:38.302  9588  9651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
01-27 16:49:38.302  9588  9651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
01-27 16:49:38.302  9588  9651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
01-27 16:49:38.302  9588  9651 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
01-27 16:49:38.302  9588  9651 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
01-27 16:49:38.302  9588  9651 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
01-27 16:49:38.302  9588  9651 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,01-27 16:49:38.302  9588  9651 D io.jxcore.node.ConnectivityMonitor: start: OK
01-27 16:49:38.302  9588  9651 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 0
01-27 16:49:38.302  9588  9651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 256 -> 0
01-27 16:49:38.302  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,01-27 16:49:38.302  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":0,"address":"44:78:3E:94:2C:E6"}
,01-27 16:49:38.302  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":0,"address":"44:78:3E:94:2C:E6"}
,01-27 16:49:38.302  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:49:38.302  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
01-27 16:49:38.302  9588  9588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,01-27 16:49:38.302  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":0,"address":"44:78:3E:94:2C:E6"}
,01-27 16:49:38.302  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":0,"address":"44:78:3E:94:2C:E6"}
,01-27 16:49:38.302  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:49:38.302  9588  9651 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
01-27 16:49:38.302  9588  9651 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
01-27 16:49:38.302  9588  9651 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,01-27 16:49:38.302  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
01-27 16:49:38.312  9588  9588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,01-27 16:49:38.312  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
01-27 16:49:38.312  9588  9651 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
01-27 16:49:38.312  9588  9651 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,01-27 16:49:38.312  9588  9651 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,01-27 16:49:38.312  9588  9664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,01-27 16:49:38.312  9588  9651 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,01-27 16:49:38.312  9588  9651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
01-27 16:49:38.312  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,01-27 16:49:38.312  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
01-27 16:49:38.312  9588  9588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,01-27 16:49:38.312  9588  9588 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
01-27 16:49:38.322  9588  9664 D BluetoothSocket: bindListen(): myUserId = 0
,01-27 16:49:38.322  9588  9664 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,01-27 16:49:38.322  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,01-27 16:49:38.322  9588  9651 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,01-27 16:49:38.322  9588  9651 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,01-27 16:49:38.322  9588  9664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,01-27 16:49:38.322  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:49:38.332  9588  9651 D BluetoothAdapter: STATE_ON
01-27 16:49:38.332  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:49:38.332  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:38.332  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,01-27 16:49:38.342  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:49:38.342  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:49:38.342  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,01-27 16:49:38.342  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,01-27 16:49:38.342  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 0
,01-27 16:49:38.342  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:49:38.342  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:49:38.342  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:38.342  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
01-27 16:49:38.342  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
01-27 16:49:38.342  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "44:78:3E:94:2C:E6"
,01-27 16:49:38.352  9588  9651 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 44 78 3E 94 2C E6
,01-27 16:49:38.352  9588  9651 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,01-27 16:49:38.352  3465  4331 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
01-27 16:49:38.352  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
01-27 16:49:38.352  3465  4331 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4337, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
01-27 16:49:38.352  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:49:38.352  3465  4331 D BatteryService: online:4, current avg:-15, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-34
01-27 16:49:38.352  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:38.352  3465  3465 D BatteryService: Sending ACTION_BATTERY_CHANGED.
01-27 16:49:38.352  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
01-27 16:49:38.352  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
01-27 16:49:38.352  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:49:38.352  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:38.352  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:49:38.352  3465  3465 I MotionRecognitionService: Plugged
01-27 16:49:38.352  9588  9651 D BluetoothAdapter: STATE_ON
01-27 16:49:38.352  3465  3465 D MotionRecognitionService:   cableConnection= 1
,01-27 16:49:38.352  3465  3465 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
01-27 16:49:38.352  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:49:38.352  3465  3465 D MotionRecognitionService: skip setTransmitPower. 
01-27 16:49:38.352  9588  9651 D BluetoothLeAdvertiser: start advertising
,01-27 16:49:38.362  3465  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,01-27 16:49:38.362  9588  9651 D BluetoothAdapter: STATE_ON
01-27 16:49:38.362  3950  3950 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,01-27 16:49:38.362  3950  3950 D KeyguardUpdateMonitor: handleBatteryUpdate
01-27 16:49:38.362  3950  3950 D PowerUI : priorPlugType = 2 mPlugType =  2
,01-27 16:49:38.362  3950  3950 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
01-27 16:49:38.362  3950  3950 D PowerUI.Notification: There is no change about charging status, so return!
,01-27 16:49:38.362  4942  4960 D BtGatt.GattService: registerClient() - UUID=bd415911-4951-4307-ab5d-94c06b2191ae
,01-27 16:49:38.372  4990  4990 D CommonServiceConfiguration: getStringValueSetting
,01-27 16:49:38.372  4942  4942 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,01-27 16:49:38.372  4942  5321 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,01-27 16:49:38.372  4990  4990 D BatteryMonitor: new battery level: 100
,01-27 16:49:38.382  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,01-27 16:49:38.382  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,01-27 16:49:38.412  4942  5106 D BtGatt.GattService: onClientRegistered() - UUID=bd415911-4951-4307-ab5d-94c06b2191ae, clientIf=8
,01-27 16:49:38.412  9588  9598 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=8
,01-27 16:49:38.412  4942  4966 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,01-27 16:49:38.422  4942  4966 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
01-27 16:49:38.422  4942  4966 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,01-27 16:49:38.422  4942  5190 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_ADV
01-27 16:49:38.422  4942  5190 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 27, currDate: 27
,01-27 16:49:38.422  4942  5179 D BtGatt.AdvertiseManager: message : 0
,01-27 16:49:38.422  4942  5179 D BtGatt.AdvertiseManager: number of adv instance running = 0
,01-27 16:49:38.422  4942  5179 D BtGatt.AdvertiseManager: size of list is =0
,01-27 16:49:38.432  4942  5179 D BtGatt.AdvertiseManager: starting advertising
,01-27 16:49:38.432  4942  5190 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.test.thalitest : 75
,01-27 16:49:38.432  4942  5190 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.test.thalitest@LowLatency : 24758869
01-27 16:49:38.432  4942  5179 D BtGatt.AdvertiseManager: isStandardAdv = false
,01-27 16:49:38.432  4942  5190 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.test.thalitest@LowLatency : 2
01-27 16:49:38.432  4942  5190 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
01-27 16:49:38.432  4942  5190 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 3 => 3
,01-27 16:49:38.442  3465  4059 V AlarmManager:  remove PendingIntent] PendingIntent{3ad137c: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:38.472  3465  3484 V AlarmManager:  remove PendingIntent] PendingIntent{a894405: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:38.472  4942  5106 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=8, status=0
,01-27 16:49:38.472  4942  5179 D BtGatt.AdvertiseManager: starting multi advertising
,01-27 16:49:38.472  3465  4488 V AlarmManager:  remove PendingIntent] PendingIntent{9ac5a: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:38.472  4942  5106 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=8, status=0
01-27 16:49:38.472  4942  5179 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
01-27 16:49:38.472  4942  5179 D BtGatt.AdvertiseManager: clientIf: 8, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
01-27 16:49:38.472  4942  5179 D BtGatt.AdvertiseManager: postCallback clientIf = 8 status = 0
01-27 16:49:38.472  4942  5179 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=8, status=0, isStart=true
01-27 16:49:38.472  9588  9599 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
,01-27 16:49:38.472  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:49:38.472  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:38.472  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
01-27 16:49:38.482  3465  3483 V AlarmManager:  remove PendingIntent] PendingIntent{e3dfe8b: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
01-27 16:49:38.482  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:49:38.482  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:38.482  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:38.482  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:49:38.482  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:38.482  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,01-27 16:49:38.482  9588  9651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
01-27 16:49:38.482  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:49:38.482  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:38.482  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:38.482  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:49:38.482  9588  9651 I io.jxcore.node.ConnectionHelper: start: OK
01-27 16:49:38.482  9588  9588 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
01-27 16:49:38.482  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,01-27 16:49:38.482  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
01-27 16:49:38.482  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
01-27 16:49:38.482  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
01-27 16:49:38.482  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
,01-27 16:49:38.482  9588  9588 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
01-27 16:49:38.482  3465  4489 V AlarmManager:  remove PendingIntent] PendingIntent{e75eb68: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
01-27 16:49:38.482  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
01-27 16:49:38.482  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
,01-27 16:49:38.482  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
01-27 16:49:38.482  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
01-27 16:49:38.482  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
,01-27 16:49:38.482  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
01-27 16:49:38.482  9588  9588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
01-27 16:49:38.482  9588  9588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,01-27 16:49:38.492  3465  4225 V AlarmManager:  remove PendingIntent] PendingIntent{5f1b81: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
01-27 16:49:38.492  9588  9588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
01-27 16:49:38.492  9588  9588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
01-27 16:49:38.492  9588  9588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
01-27 16:49:38.492  9588  9588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
01-27 16:49:38.492  9588  9588 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,01-27 16:49:38.492  3465  4488 V AlarmManager:  remove PendingIntent] PendingIntent{9a63426: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:38.692  3465  3977 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
01-27 16:49:38.692  3465  3977 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4329, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
01-27 16:49:38.692  3465  3977 D BatteryService: online:4, current avg:-16, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-40
01-27 16:49:38.692  3465  3465 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,01-27 16:49:38.692  3465  3465 I MotionRecognitionService: Plugged
01-27 16:49:38.692  3465  3465 D MotionRecognitionService:   cableConnection= 1
01-27 16:49:38.692  3465  3465 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
01-27 16:49:38.692  3465  3465 D MotionRecognitionService: skip setTransmitPower. 
,01-27 16:49:38.702  3465  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,01-27 16:49:38.702  3950  3950 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
01-27 16:49:38.702  3950  3950 D KeyguardUpdateMonitor: handleBatteryUpdate
,01-27 16:49:38.702  3950  3950 D PowerUI : priorPlugType = 2 mPlugType =  2
,01-27 16:49:38.702  3950  3950 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,01-27 16:49:38.702  3950  3950 D PowerUI.Notification: There is no change about charging status, so return!
,01-27 16:49:38.722  4990  4990 D CommonServiceConfiguration: getStringValueSetting
,01-27 16:49:38.722  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
01-27 16:49:38.722  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,01-27 16:49:38.722  4942  4942 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
01-27 16:49:38.722  4942  5321 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,01-27 16:49:38.732  4990  4990 D BatteryMonitor: new battery level: 100
,01-27 16:49:38.912  3465  6030 D SSRM:n  : SIOP:: AP = 350, PST = 335 (W:14), CP = 288, CUR = -16, LCD = 40
,01-27 16:49:38.992  9588  9667 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,01-27 16:49:38.992  9588  9651 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
01-27 16:49:38.992  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [00:11:22:33:44:55]
01-27 16:49:38.992  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [10:010:010:010:010:010]
01-27 16:49:38.992  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [11:110:110:110:110:110]
01-27 16:49:38.992  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [12:210:210:210:210:210]
01-27 16:49:38.992  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [13:310:310:310:310:310]
01-27 16:49:38.992  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [14:410:410:410:410:410]
01-27 16:49:38.992  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [15:510:510:510:510:510]
01-27 16:49:38.992  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [16:610:610:610:610:610]
01-27 16:49:38.992  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [17:710:710:710:710:710]
01-27 16:49:38.992  9588  9588 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
01-27 16:49:38.992  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [18:810:810:810:810:810]
01-27 16:49:38.992  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [19:910:910:910:910:910]
01-27 16:49:38.992  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [20:1010:1010:1010:1010:1010]
01-27 16:49:38.992  9588  9588 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
01-27 16:49:38.992  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [21:1110:1110:1110:1110:1110]
01-27 16:49:38.992  9588  9588 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
01-27 16:49:38.992  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [22:1210:1210:1210:1210:1210]
01-27 16:49:38.992  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [23:1310:1310:1310:1310:1310]
01-27 16:49:38.992  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [24:1410:1410:1410:1410:1410]
01-27 16:49:38.992  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [25:1510:1510:1510:1510:1510]
01-27 16:49:38.992  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [26:1610:1610:1610:1610:1610]
01-27 16:49:38.992  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [27:1710:1710:1710:1710:1710]
01-27 16:49:38.992  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [28:1810:1810:1810:1810:1810]
01-27 16:49:38.992  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [29:1910:1910:1910:1910:1910]
01-27 16:49:38.992  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [30:2010:2010:2010:2010:2010]
01-27 16:49:38.992  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [31:2110:2110:2110:2110:2110]
01-27 16:49:38.992  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [32:2210:2210:2210:2210:2210]
,01-27 16:49:38.992  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [33:2310:2310:2310:2310:2310]
01-27 16:49:38.992  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [34:2410:2410:2410:2410:2410]
01-27 16:49:38.992  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [35:2510:2510:2510:2510:2510]
01-27 16:49:38.992  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [36:2610:2610:2610:2610:2610]
01-27 16:49:38.992  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [37:2710:2710:2710:2710:2710]
01-27 16:49:38.992  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [38:2810:2810:2810:2810:2810]
01-27 16:49:38.992  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [39:2910:2910:2910:2910:2910]
01-27 16:49:38.992  9588  9651 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
01-27 16:49:38.992  9588  9651 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
01-27 16:49:38.992  9588  9651 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
01-27 16:49:38.992  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
01-27 16:49:38.992  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
01-27 16:49:38.992  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
01-27 16:49:38.992  9588  9651 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
01-27 16:49:38.992  9588  9651 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
01-27 16:49:38.992  9588  9664 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
01-27 16:49:38.992  9588  9651 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
01-27 16:49:38.992  9588  9664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
01-27 16:49:38.992  9588  9664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
01-27 16:49:38.992  9588  9651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
01-27 16:49:38.992  9588  9588 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
01-27 16:49:38.992  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:38.992  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
01-27 16:49:38.992  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
01-27 16:49:39.002  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.002  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.002  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.002  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.002  9588  9651 D BluetoothAdapter: STATE_ON
01-27 16:49:39.002  9588  9651 D BluetoothAdapter: STATE_ON
01-27 16:49:39.002  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
01-27 16:49:39.012  9588  9651 D BluetoothAdapter: STATE_ON
01-27 16:49:39.012  9588  9651 D BluetoothAdapter: STATE_ON
01-27 16:49:39.012  9588  9651 D BluetoothLeScanner: could not find callback wrapper
01-27 16:49:39.012  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
01-27 16:49:39.012  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.012  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.012  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.012  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
01-27 16:49:39.012  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.012  9588  9651 D BluetoothAdapter: STATE_ON
01-27 16:49:39.022  9588  9651 D BluetoothAdapter: STATE_ON
01-27 16:49:39.022  9588  9651 D BluetoothLeAdvertiser: stop advertising
01-27 16:49:39.032  4942  5319 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
01-27 16:49:39.032  4942  5319 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
01-27 16:49:39.032  4942  5179 D BtGatt.AdvertiseManager: message : 1
01-27 16:49:39.032  4942  5190 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_ADV
01-27 16:49:39.032  4942  5190 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 27, currDate: 27
01-27 16:49:39.032  4942  5190 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
01-27 16:49:39.032  4942  5190 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 3 => 3
01-27 16:49:39.032  4942  5190 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
01-27 16:49:39.032  4942  5179 D BtGatt.AdvertiseManager: stop advertise for client =  8
01-27 16:49:39.032  4942  5179 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 8
,01-27 16:49:39.032  4942  5179 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
01-27 16:49:39.032  3465  3973 V AlarmManager:  remove PendingIntent] PendingIntent{b0bf867: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
01-27 16:49:39.032  4942  5106 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=8, status=0
01-27 16:49:39.042  4942  5106 D BtGatt.GattService: Client app is not null!
01-27 16:49:39.042  9588  9598 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
01-27 16:49:39.042  4942  4960 D BtGatt.GattService: unregisterClient() - clientIf=8
01-27 16:49:39.042  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
01-27 16:49:39.042  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.042  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
01-27 16:49:39.042  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.042  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.042  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.042  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
01-27 16:49:39.042  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
01-27 16:49:39.052  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
01-27 16:49:39.052  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.052  3465  4487 V AlarmManager:  remove PendingIntent] PendingIntent{725614: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
01-27 16:49:39.052  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.052  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
01-27 16:49:39.052  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.052  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.052  9588  9588 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
01-27 16:49:39.052  9588  9588 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
01-27 16:49:39.052  9588  9588 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
01-27 16:49:39.052  9588  9588 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
01-27 16:49:39.052  9588  9588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
01-27 16:49:39.052  9588  9588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
01-27 16:49:39.052  9588  9588 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
01-27 16:49:39.052  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
01-27 16:49:39.052  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
01-27 16:49:39.052  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
01-27 16:49:39.052  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
01-27 16:49:39.052  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
01-27 16:49:39.052  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
01-27 16:49:39.052  9588  9588 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
01-27 16:49:39.062  9588  9671 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
01-27 16:49:39.062  9588  9651 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
01-27 16:49:39.062  9588  9651 V io.jxcore.node.ConnectivityMonitor: start: Already started
01-27 16:49:39.062  9588  9651 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
01-27 16:49:39.062  9588  9651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
01-27 16:49:39.062  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
01-27 16:49:39.062  3465  4331 V AlarmManager:  remove PendingIntent] PendingIntent{e60eebd: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
01-27 16:49:39.062  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":1,"address":"44:78:3E:94:2C:E6"}
01-27 16:49:39.072  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":1,"address":"44:78:3E:94:2C:E6"}
01-27 16:49:39.072  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.072  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
01-27 16:49:39.072  3465  3973 V AlarmManager:  remove PendingIntent] PendingIntent{b316cb2: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}},
01-27 16:49:39.072  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":1,"address":"44:78:3E:94:2C:E6"}
01-27 16:49:39.072  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":1,"address":"44:78:3E:94:2C:E6"}
01-27 16:49:39.072  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.072  9588  9651 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
01-27 16:49:39.072  9588  9651 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
01-27 16:49:39.072  9588  9651 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
01-27 16:49:39.072  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
01-27 16:49:39.072  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
01-27 16:49:39.072  9588  9651 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
01-27 16:49:39.072  9588  9651 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
01-27 16:49:39.072  9588  9651 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
01-27 16:49:39.072  9588  9651 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
01-27 16:49:39.072  9588  9651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
01-27 16:49:39.072  9588  9588 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
01-27 16:49:39.072  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
01-27 16:49:39.072  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
01-27 16:49:39.082  9588  9672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
01-27 16:49:39.082  3465  4488 V AlarmManager:  remove PendingIntent] PendingIntent{1c5a1fe: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
01-27 16:49:39.082  9588  9672 D BluetoothSocket: bindListen(): myUserId = 0
01-27 16:49:39.082  9588  9672 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
01-27 16:49:39.092  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
01-27 16:49:39.092  9588  9651 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
01-27 16:49:39.092  9588  9651 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
01-27 16:49:39.092  9588  9672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
01-27 16:49:39.092  9588  9651 D BluetoothAdapter: STATE_ON
01-27 16:49:39.092  3465  4489 V AlarmManager:  remove PendingIntent] PendingIntent{f58d5f: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
01-27 16:49:39.092  9588  9651 D BluetoothAdapter: STATE_ON
01-27 16:49:39.092  9588  9651 D BluetoothAdapter: STATE_ON
01-27 16:49:39.102  3465  4225 V AlarmManager:  remove PendingIntent] PendingIntent{1a53ac: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
01-27 16:49:39.102  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.102  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
01-27 16:49:39.102  9588  9651 D BluetoothAdapter: STATE_ON
01-27 16:49:39.102  9588  9651 D BluetoothAdapter: STATE_ON
01-27 16:49:39.102  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
01-27 16:49:39.102  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
01-27 16:49:39.102  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 1
01-27 16:49:39.102  3465  4416 V AlarmManager:  remove PendingIntent] PendingIntent{3bc3875: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
01-27 16:49:39.112  9588  9651 D BluetoothAdapter: STATE_ON
01-27 16:49:39.112  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:49:39.112  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.112  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
01-27 16:49:39.112  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
01-27 16:49:39.112  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "44:78:3E:94:2C:E6"
01-27 16:49:39.112  9588  9651 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 44 78 3E 94 2C E6
,01-27 16:49:39.112  9588  9651 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
01-27 16:49:39.112  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
01-27 16:49:39.112  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.112  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:49:39.112  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
01-27 16:49:39.112  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,01-27 16:49:39.112  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.112  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.112  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.112  9588  9651 D BluetoothAdapter: STATE_ON
01-27 16:49:39.122  9588  9651 D BluetoothAdapter: STATE_ON
01-27 16:49:39.122  9588  9651 D BluetoothLeAdvertiser: start advertising
,01-27 16:49:39.122  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:49:39.122  4942  5319 D BtGatt.GattService: registerClient() - UUID=fa680404-e7a2-4df7-9c2e-6968beb812ea
,01-27 16:49:39.162  4942  5106 D BtGatt.GattService: onClientRegistered() - UUID=fa680404-e7a2-4df7-9c2e-6968beb812ea, clientIf=8
,01-27 16:49:39.172  9588  9599 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=8
,01-27 16:49:39.172  4942  4966 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,01-27 16:49:39.182  4942  4966 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,01-27 16:49:39.182  4942  4966 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,01-27 16:49:39.182  4942  5179 D BtGatt.AdvertiseManager: message : 0
01-27 16:49:39.182  4942  5190 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_ADV
,01-27 16:49:39.182  4942  5190 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 27, currDate: 27
,01-27 16:49:39.182  4942  5179 D BtGatt.AdvertiseManager: number of adv instance running = 0
,01-27 16:49:39.182  4942  5179 D BtGatt.AdvertiseManager: size of list is =0
,01-27 16:49:39.192  4942  5179 D BtGatt.AdvertiseManager: starting advertising
,01-27 16:49:39.192  4942  5190 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.test.thalitest : 76
,01-27 16:49:39.192  4942  5190 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.test.thalitest@LowLatency : 24758869
01-27 16:49:39.192  4942  5190 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.test.thalitest@LowLatency : 2
01-27 16:49:39.192  4942  5190 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
01-27 16:49:39.192  4942  5190 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 3 => 3
,01-27 16:49:39.192  4942  5179 D BtGatt.AdvertiseManager: isStandardAdv = false
,01-27 16:49:39.202  3465  3977 V AlarmManager:  remove PendingIntent] PendingIntent{fd5e00a: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:39.202  4942  5106 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=8, status=0
,01-27 16:49:39.212  4942  5179 D BtGatt.AdvertiseManager: starting multi advertising
,01-27 16:49:39.212  4942  5106 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=8, status=0
,01-27 16:49:39.212  3465  3484 V AlarmManager:  remove PendingIntent] PendingIntent{a0fa07b: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:39.212  4942  5179 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
01-27 16:49:39.212  4942  5179 D BtGatt.AdvertiseManager: clientIf: 8, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
01-27 16:49:39.212  4942  5179 D BtGatt.AdvertiseManager: postCallback clientIf = 8 status = 0
,01-27 16:49:39.212  4942  5179 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=8, status=0, isStart=true
01-27 16:49:39.212  9588  9598 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
,01-27 16:49:39.212  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.212  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.212  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,01-27 16:49:39.212  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.212  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.212  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
,01-27 16:49:39.212  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.212  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.212  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,01-27 16:49:39.222  9588  9651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
01-27 16:49:39.222  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.222  9588  9651 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: seems that updateState call different BlePeerDiscoverer
,01-27 16:49:39.222  3465  3483 V AlarmManager:  remove PendingIntent] PendingIntent{5aefe98: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
01-27 16:49:39.222  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:49:39.222  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.232  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.232  9588  9651 I io.jxcore.node.ConnectionHelper: start: OK
,01-27 16:49:39.232  9588  9588 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,01-27 16:49:39.232  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
01-27 16:49:39.232  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
01-27 16:49:39.232  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
01-27 16:49:39.232  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
,01-27 16:49:39.232  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
01-27 16:49:39.232  9588  9588 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,01-27 16:49:39.232  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
01-27 16:49:39.232  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
01-27 16:49:39.232  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,01-27 16:49:39.232  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
01-27 16:49:39.232  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
01-27 16:49:39.232  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
01-27 16:49:39.232  9588  9588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
,01-27 16:49:39.232  9588  9588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,01-27 16:49:39.252  9588  9588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,01-27 16:49:39.252  9588  9588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
01-27 16:49:39.252  3465  4485 V AlarmManager:  remove PendingIntent] PendingIntent{ea4e6f1: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:39.252  9588  9588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
01-27 16:49:39.252  9588  9588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
01-27 16:49:39.252  9588  9588 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,01-27 16:49:39.252  3465  3484 V AlarmManager:  remove PendingIntent] PendingIntent{9f9f2d6: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:39.262  3465  4059 V AlarmManager:  remove PendingIntent] PendingIntent{eedc957: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:39.262  3465  3483 V AlarmManager:  remove PendingIntent] PendingIntent{ee16c44: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:39.272  3465  3977 V AlarmManager:  remove PendingIntent] PendingIntent{590012d: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:39.732  9588  9674 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,01-27 16:49:39.732  9588  9651 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
,01-27 16:49:39.732  9588  9651 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
01-27 16:49:39.732  9588  9651 V io.jxcore.node.ConnectivityMonitor: start: Already started
01-27 16:49:39.732  9588  9651 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
01-27 16:49:39.732  9588  9651 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
01-27 16:49:39.732  9588  9651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
01-27 16:49:39.742  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,01-27 16:49:39.742  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":2,"address":"44:78:3E:94:2C:E6"}
,01-27 16:49:39.742  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":2,"address":"44:78:3E:94:2C:E6"}
,01-27 16:49:39.742  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.742  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,01-27 16:49:39.752  9588  9588 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,01-27 16:49:39.752  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":2,"address":"44:78:3E:94:2C:E6"}
,01-27 16:49:39.752  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":2,"address":"44:78:3E:94:2C:E6"}
01-27 16:49:39.752  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:49:39.752  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
01-27 16:49:39.752  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
01-27 16:49:39.752  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
01-27 16:49:39.752  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 2
01-27 16:49:39.752  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
01-27 16:49:39.752  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
01-27 16:49:39.752  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
01-27 16:49:39.752  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
01-27 16:49:39.752  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
01-27 16:49:39.752  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.752  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 2
01-27 16:49:39.752  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted true Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:49:39.752  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop advertiser Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.752  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.762  9588  9651 D BluetoothAdapter: STATE_ON
01-27 16:49:39.762  9588  9651 D BluetoothAdapter: STATE_ON
01-27 16:49:39.762  9588  9651 D BluetoothLeAdvertiser: stop advertising
,01-27 16:49:39.762  4942  5319 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,01-27 16:49:39.762  4942  5319 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
01-27 16:49:39.762  4942  5190 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_ADV
01-27 16:49:39.762  4942  5179 D BtGatt.AdvertiseManager: message : 1
01-27 16:49:39.762  4942  5190 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 27, currDate: 27
01-27 16:49:39.762  4942  5190 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
01-27 16:49:39.772  4942  5190 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 3 => 3
01-27 16:49:39.772  4942  5190 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
01-27 16:49:39.772  4942  5179 D BtGatt.AdvertiseManager: stop advertise for client =  8
01-27 16:49:39.772  4942  5179 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 8
01-27 16:49:39.772  4942  5179 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
01-27 16:49:39.772  3465  4059 V AlarmManager:  remove PendingIntent] PendingIntent{47a6662: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
01-27 16:49:39.782  3465  3483 V AlarmManager:  remove PendingIntent] PendingIntent{51ba3f3: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:39.812  4942  5106 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=8, status=0
,01-27 16:49:39.812  4942  5106 D BtGatt.GattService: Client app is not null!
01-27 16:49:39.812  9588  9599 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
01-27 16:49:39.812  3465  3977 V AlarmManager:  remove PendingIntent] PendingIntent{9ab08b0: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
01-27 16:49:39.812  4942  4966 D BtGatt.GattService: unregisterClient() - clientIf=8
,01-27 16:49:39.812  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
01-27 16:49:39.812  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.812  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
01-27 16:49:39.812  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.812  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.812  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.812  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
01-27 16:49:39.812  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.812  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.812  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.812  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
01-27 16:49:39.812  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
01-27 16:49:39.812  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "44:78:3E:94:2C:E6"
01-27 16:49:39.812  3465  4331 V AlarmManager:  remove PendingIntent] PendingIntent{2988329: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
01-27 16:49:39.812  9588  9651 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 44 78 3E 94 2C E6
01-27 16:49:39.812  9588  9651 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
01-27 16:49:39.812  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
01-27 16:49:39.812  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.812  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.812  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
01-27 16:49:39.812  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
01-27 16:49:39.812  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.812  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.812  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.812  9588  9651 D BluetoothAdapter: STATE_ON
01-27 16:49:39.822  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:49:39.822  9588  9651 D BluetoothLeAdvertiser: start advertising
,01-27 16:49:39.822  3465  3483 V AlarmManager:  remove PendingIntent] PendingIntent{d9c86ae: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:39.822  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:49:39.822  3465  4403 V AlarmManager:  remove PendingIntent] PendingIntent{5428c4f: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:39.832  4942  4960 D BtGatt.GattService: registerClient() - UUID=897d00a0-2611-49b3-9c72-3da3201032d1
,01-27 16:49:39.832  3465  4416 V AlarmManager:  remove PendingIntent] PendingIntent{82fffdc: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:39.832  3465  3977 V AlarmManager:  remove PendingIntent] PendingIntent{c8d28e5: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:39.872  4942  5106 D BtGatt.GattService: onClientRegistered() - UUID=897d00a0-2611-49b3-9c72-3da3201032d1, clientIf=8
,01-27 16:49:39.872  9588  9598 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=8
,01-27 16:49:39.872  4942  4966 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,01-27 16:49:39.872  4942  4966 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
01-27 16:49:39.872  4942  4966 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
01-27 16:49:39.872  4942  5179 D BtGatt.AdvertiseManager: message : 0
01-27 16:49:39.872  4942  5190 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_ADV
01-27 16:49:39.872  4942  5190 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 27, currDate: 27
,01-27 16:49:39.872  4942  5179 D BtGatt.AdvertiseManager: number of adv instance running = 0
01-27 16:49:39.872  4942  5179 D BtGatt.AdvertiseManager: size of list is =0
,01-27 16:49:39.882  4942  5179 D BtGatt.AdvertiseManager: starting advertising
,01-27 16:49:39.882  4942  5179 D BtGatt.AdvertiseManager: isStandardAdv = false
,01-27 16:49:39.882  4942  5190 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.test.thalitest : 77
01-27 16:49:39.882  4942  5190 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.test.thalitest@LowLatency : 24758869
,01-27 16:49:39.882  4942  5190 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.test.thalitest@LowLatency : 2
01-27 16:49:39.882  4942  5190 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
,01-27 16:49:39.882  4942  5190 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 3 => 3
01-27 16:49:39.892  3465  4382 V AlarmManager:  remove PendingIntent] PendingIntent{ae5fba: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:39.892  4942  5106 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=8, status=0
,01-27 16:49:39.892  4942  5179 D BtGatt.AdvertiseManager: starting multi advertising
,01-27 16:49:39.902  4942  5106 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=8, status=0
,01-27 16:49:39.902  3465  4488 V AlarmManager:  remove PendingIntent] PendingIntent{f459e6b: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:39.902  4942  5179 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,01-27 16:49:39.902  4942  5179 D BtGatt.AdvertiseManager: clientIf: 8, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
01-27 16:49:39.902  4942  5179 D BtGatt.AdvertiseManager: postCallback clientIf = 8 status = 0
,01-27 16:49:39.902  4942  5179 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=8, status=0, isStart=true
01-27 16:49:39.902  9588  9599 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
01-27 16:49:39.902  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.902  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.902  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
01-27 16:49:39.902  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.902  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.902  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.902  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:49:39.902  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:49:39.902  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser started = true Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.902  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
01-27 16:49:39.902  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted false Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.902  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,01-27 16:49:39.902  9588  9651 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
01-27 16:49:39.902  9588  9651 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
01-27 16:49:39.902  9588  9651 I io.jxcore.node.ConnectionHelper: start: OK
,01-27 16:49:39.902  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,01-27 16:49:39.902  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
01-27 16:49:39.912  3465  4403 V AlarmManager:  remove PendingIntent] PendingIntent{8ab3dc8: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:39.902  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
01-27 16:49:39.902  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
01-27 16:49:39.902  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
01-27 16:49:39.902  9588  9588 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,01-27 16:49:39.902  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
01-27 16:49:39.902  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
01-27 16:49:39.902  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
,01-27 16:49:39.902  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
01-27 16:49:39.902  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
01-27 16:49:39.902  9588  9676 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
01-27 16:49:39.902  9588  9651 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,01-27 16:49:39.902  9588  9651 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
01-27 16:49:39.902  9588  9651 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
01-27 16:49:39.902  9588  9651 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
01-27 16:49:39.902  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
01-27 16:49:39.902  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
01-27 16:49:39.902  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
01-27 16:49:39.902  9588  9651 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
01-27 16:49:39.902  9588  9651 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
01-27 16:49:39.902  9588  9651 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
01-27 16:49:39.902  9588  9651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
01-27 16:49:39.902  9588  9588 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
01-27 16:49:39.902  9588  9672 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
01-27 16:49:39.902  9588  9672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
01-27 16:49:39.902  9588  9672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,01-27 16:49:39.902  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.902  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
01-27 16:49:39.902  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
01-27 16:49:39.902  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.922  3465  3977 V AlarmManager:  remove PendingIntent] PendingIntent{e6c6e61: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
01-27 16:49:39.902  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.902  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:49:39.902  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:49:39.912  9588  9651 D BluetoothAdapter: STATE_ON
01-27 16:49:39.912  9588  9651 D BluetoothAdapter: STATE_ON
01-27 16:49:39.912  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
01-27 16:49:39.912  9588  9651 D BluetoothAdapter: STATE_ON
01-27 16:49:39.912  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:49:39.912  9588  9651 D BluetoothLeScanner: could not find callback wrapper
01-27 16:49:39.912  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
01-27 16:49:39.912  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.912  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.912  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:49:39.912  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
01-27 16:49:39.912  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.922  9588  9651 D BluetoothAdapter: STATE_ON
01-27 16:49:39.922  9588  9651 D BluetoothAdapter: STATE_ON
01-27 16:49:39.922  9588  9651 D BluetoothLeAdvertiser: stop advertising
,01-27 16:49:39.932  4942  4960 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,01-27 16:49:39.932  4942  4960 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
01-27 16:49:39.932  4942  5179 D BtGatt.AdvertiseManager: message : 1
01-27 16:49:39.932  4942  5190 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_ADV
01-27 16:49:39.932  4942  5190 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 27, currDate: 27
01-27 16:49:39.932  4942  5190 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
,01-27 16:49:39.932  4942  5190 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 3 => 3
01-27 16:49:39.932  4942  5190 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
01-27 16:49:39.932  4942  5179 D BtGatt.AdvertiseManager: stop advertise for client =  8
01-27 16:49:39.932  4942  5179 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 8
,01-27 16:49:39.932  4942  5179 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,01-27 16:49:39.932  3465  3484 V AlarmManager:  remove PendingIntent] PendingIntent{dd2bd86: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:39.932  4942  5106 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=8, status=0
01-27 16:49:39.932  4942  5106 D BtGatt.GattService: Client app is not null!
,01-27 16:49:39.932  9588  9598 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,01-27 16:49:39.932  4942  4966 D BtGatt.GattService: unregisterClient() - clientIf=8
,01-27 16:49:39.942  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,01-27 16:49:39.942  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
,01-27 16:49:39.942  3465  3483 V AlarmManager:  remove PendingIntent] PendingIntent{41db647: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
01-27 16:49:39.942  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
01-27 16:49:39.942  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:49:39.942  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.942  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.942  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
01-27 16:49:39.942  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,01-27 16:49:39.942  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
01-27 16:49:39.942  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:39.942  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:49:39.942  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
01-27 16:49:39.942  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:49:39.942  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:49:39.952  9588  9588 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,01-27 16:49:39.952  9588  9588 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
01-27 16:49:39.952  9588  9588 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
01-27 16:49:39.952  9588  9588 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,01-27 16:49:39.952  9588  9588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
01-27 16:49:39.952  9588  9588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
01-27 16:49:39.952  9588  9588 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,01-27 16:49:39.952  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
01-27 16:49:39.952  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
01-27 16:49:39.952  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
,01-27 16:49:39.952  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
01-27 16:49:39.952  3465  4403 V AlarmManager:  remove PendingIntent] PendingIntent{1a6e74: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
01-27 16:49:39.952  9588  9677 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
,01-27 16:49:39.952  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
01-27 16:49:39.952  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
01-27 16:49:39.952  9588  9588 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,01-27 16:49:39.952  9588  9651 I io.jxcore.node.ConnectionHelperTest: Starting test: testListenToConnectivityChanges
,01-27 16:49:39.952  9588  9651 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,01-27 16:49:39.952  9588  9651 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97aed4a added. We now have 3 listener(s)
01-27 16:49:39.952  9588  9651 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97aed4a added. We now have 5 listener(s)
,01-27 16:49:39.952  9588  9651 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,01-27 16:49:39.952  3465  4489 V AlarmManager:  remove PendingIntent] PendingIntent{aa08f9d: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
01-27 16:49:39.952  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":2,"address":"44:78:3E:94:2C:E6"}
,01-27 16:49:39.952  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
01-27 16:49:39.952  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":2,"address":"44:78:3E:94:2C:E6"}
01-27 16:49:39.962  9588  9651 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,01-27 16:49:39.962  9588  9651 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@edfc4bb added. We now have 6 listener(s)
01-27 16:49:39.962  9588  9651 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,01-27 16:49:39.962  9588  9651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,01-27 16:49:39.962  3465  3483 V AlarmManager:  remove PendingIntent] PendingIntent{28d2c12: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:39.962  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,01-27 16:49:39.972  3465  3484 V AlarmManager:  remove PendingIntent] PendingIntent{f0df75e: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:39.972  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:49:39.972  9588  9651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
01-27 16:49:39.972  9588  9651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
01-27 16:49:39.972  9588  9651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
01-27 16:49:39.972  9588  9651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
01-27 16:49:39.972  9588  9651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
01-27 16:49:39.972  9588  9651 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
01-27 16:49:39.972  9588  9651 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
01-27 16:49:39.972  9588  9651 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
01-27 16:49:39.972  9588  9651 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,01-27 16:49:39.972  9588  9651 D io.jxcore.node.ConnectivityMonitor: start: OK
01-27 16:49:39.972  3465  4331 V AlarmManager:  remove PendingIntent] PendingIntent{b05273f: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:39.982  9588  9588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,01-27 16:49:39.982  3465  4042 V AlarmManager:  remove PendingIntent] PendingIntent{ce1180c: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:39.982  9588  9651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,01-27 16:49:39.982  3465  4488 V AlarmManager:  remove PendingIntent] PendingIntent{6731555: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:39.992  9588  9588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,01-27 16:49:39.992  3465  4042 V AlarmManager:  remove PendingIntent] PendingIntent{43e2b6a: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:39.992  3465  4488 V AlarmManager:  remove PendingIntent] PendingIntent{daef85b: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:39.992  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:49:40.002  9588  9651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
01-27 16:49:40.002  9588  9651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
01-27 16:49:40.002  9588  9651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
01-27 16:49:40.002  9588  9651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
01-27 16:49:40.002  9588  9651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
01-27 16:49:40.002  9588  9651 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
01-27 16:49:40.002  9588  9651 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
01-27 16:49:40.002  9588  9651 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
01-27 16:49:40.002  9588  9651 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,01-27 16:49:40.002  3465  4416 V AlarmManager:  remove PendingIntent] PendingIntent{48da8f8: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
01-27 16:49:40.002  9588  9651 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
01-27 16:49:40.002  9588  9651 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
01-27 16:49:40.002  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
01-27 16:49:40.002  9588  9651 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,01-27 16:49:40.002  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,01-27 16:49:40.002  9588  9651 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97aed4a removed from the list
,01-27 16:49:40.002  9588  9651 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97aed4a removed from the list
,01-27 16:49:40.002  9588  9651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
01-27 16:49:40.002  9588  9651 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@edfc4bb removed from the list
,01-27 16:49:40.002  9588  9588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
01-27 16:49:40.002  9588  9651 D io.jxcore.node.ConnectivityMonitor: stop
,01-27 16:49:40.002  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,01-27 16:49:40.012  9588  9651 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
,01-27 16:49:40.012  9588  9651 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,01-27 16:49:40.012  9588  9651 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
,01-27 16:49:40.012  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [incoming]
,01-27 16:49:40.012  9588  9651 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
,01-27 16:49:40.012  9588  9651 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,01-27 16:49:40.012  9588  9651 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
,01-27 16:49:40.012  9588  9651 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,01-27 16:49:40.012  9588  9651 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
,01-27 16:49:40.012  9588  9651 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
01-27 16:49:40.012  9588  9651 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
01-27 16:49:40.012  9588  9651 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
01-27 16:49:40.012  9588  9651 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,01-27 16:49:40.012  9588  9651 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
01-27 16:49:40.012  9588  9651 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
01-27 16:49:40.012  9588  9651 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,01-27 16:49:40.012  9588  9651 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
01-27 16:49:40.012  9588  9651 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
01-27 16:49:40.012  9588  9651 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
,01-27 16:49:40.012  9588  9651 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
01-27 16:49:40.012  9588  9651 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
01-27 16:49:40.012  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [00:11:22:33:44:55]
,01-27 16:49:40.022  9588  9651 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
01-27 16:49:40.022  9588  9651 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,01-27 16:49:40.022  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [10:010:010:010:010:010]
01-27 16:49:40.022  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [11:110:110:110:110:110]
01-27 16:49:40.022  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [12:210:210:210:210:210]
01-27 16:49:40.022  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [13:310:310:310:310:310]
01-27 16:49:40.022  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [14:410:410:410:410:410]
01-27 16:49:40.022  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [15:510:510:510:510:510]
,01-27 16:49:40.022  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [16:610:610:610:610:610]
01-27 16:49:40.022  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [17:710:710:710:710:710]
01-27 16:49:40.022  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [18:810:810:810:810:810]
01-27 16:49:40.022  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [19:910:910:910:910:910]
01-27 16:49:40.022  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [20:1010:1010:1010:1010:1010]
,01-27 16:49:40.022  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [21:1110:1110:1110:1110:1110]
01-27 16:49:40.022  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [22:1210:1210:1210:1210:1210]
01-27 16:49:40.022  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [23:1310:1310:1310:1310:1310]
01-27 16:49:40.022  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [24:1410:1410:1410:1410:1410]
01-27 16:49:40.022  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [25:1510:1510:1510:1510:1510]
,01-27 16:49:40.022  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [26:1610:1610:1610:1610:1610]
01-27 16:49:40.022  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [27:1710:1710:1710:1710:1710]
01-27 16:49:40.022  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [28:1810:1810:1810:1810:1810]
01-27 16:49:40.022  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [29:1910:1910:1910:1910:1910]
01-27 16:49:40.022  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [30:2010:2010:2010:2010:2010]
01-27 16:49:40.022  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [31:2110:2110:2110:2110:2110]
01-27 16:49:40.022  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [32:2210:2210:2210:2210:2210]
01-27 16:49:40.022  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [33:2310:2310:2310:2310:2310]
01-27 16:49:40.022  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [34:2410:2410:2410:2410:2410]
01-27 16:49:40.022  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [35:2510:2510:2510:2510:2510]
01-27 16:49:40.022  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [36:2610:2610:2610:2610:2610]
01-27 16:49:40.022  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [37:2710:2710:2710:2710:2710]
01-27 16:49:40.022  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [38:2810:2810:2810:2810:2810]
01-27 16:49:40.022  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [39:2910:2910:2910:2910:2910]
01-27 16:49:40.022  9588  9651 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
01-27 16:49:40.022  9588  9651 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
01-27 16:49:40.022  9588  9651 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
01-27 16:49:40.022  9588  9651 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
01-27 16:49:40.022  9588  9651 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
01-27 16:49:40.022  9588  9651 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
01-27 16:49:40.022  9588  9651 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
01-27 16:49:40.022  9588  9651 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
01-27 16:49:40.022  9588  9651 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [00:11:22:33:44:55]
,01-27 16:49:40.022  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,01-27 16:49:40.022  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port 1
,01-27 16:49:40.032  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,01-27 16:49:40.032  9588  9651 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
01-27 16:49:40.032  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
01-27 16:49:40.032  9588  9651 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,01-27 16:49:40.032  9588  9651 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
01-27 16:49:40.032  9588  9651 E io.jxcore.node.ConnectionHelper: connect: Callback is null
01-27 16:49:40.032  9588  9678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 210)
01-27 16:49:40.032  9588  9678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
,01-27 16:49:40.032  9588  9678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
01-27 16:49:40.032  9588  9678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: given port
,01-27 16:49:40.032  9588  9651 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest,
01-27 16:49:40.032  9588  9651 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,01-27 16:49:40.032  9588  9651 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
01-27 16:49:40.032  9588  9651 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,01-27 16:49:40.032  9588  9651 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
,01-27 16:49:40.032  9588  9651 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
01-27 16:49:40.032  9588  9651 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
,01-27 16:49:40.032  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
01-27 16:49:40.032  9588  9651 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
01-27 16:49:40.032  9588  9651 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,01-27 16:49:40.032  9588  9651 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
01-27 16:49:40.032  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
01-27 16:49:40.032  9588  9651 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
,01-27 16:49:40.032  9588  9651 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
01-27 16:49:40.032  9588  9651 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
01-27 16:49:40.032  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
01-27 16:49:40.032  9588  9651 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
01-27 16:49:40.032  9588  9651 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
,01-27 16:49:40.032  9588  9651 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
01-27 16:49:40.032  9588  9651 V io.jxcore.node.ConnectivityMonitor: start: Already started
01-27 16:49:40.032  9588  9651 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
,01-27 16:49:40.032  9588  9651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
,01-27 16:49:40.032  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
01-27 16:49:40.042  9588  9678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: createBluetoothSocketToServiceRecord: Socket created with channel/port 1
01-27 16:49:40.042  9588  9678 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
01-27 16:49:40.042  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"44:78:3E:94:2C:E6"}
01-27 16:49:40.042  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"44:78:3E:94:2C:E6"}
,01-27 16:49:40.042  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:40.042  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,01-27 16:49:40.042  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"44:78:3E:94:2C:E6"}
,01-27 16:49:40.042  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"44:78:3E:94:2C:E6"}
01-27 16:49:40.042  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:40.042  9588  9651 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
01-27 16:49:40.042  9588  9651 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
01-27 16:49:40.042  9588  9651 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
01-27 16:49:40.042  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,01-27 16:49:40.042  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,01-27 16:49:40.042  9588  9651 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,01-27 16:49:40.042  9588  9651 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,01-27 16:49:40.042  9588  9651 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
01-27 16:49:40.042  9588  9651 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
01-27 16:49:40.042  9588  9651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
01-27 16:49:40.042  9588  9588 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,01-27 16:49:40.042  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
01-27 16:49:40.042  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
01-27 16:49:40.042  9588  9679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
01-27 16:49:40.042  9588  9678 D BluetoothSocket: connect(): myUserId = 0
01-27 16:49:40.052  9588  9678 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,01-27 16:49:40.052  9588  9679 D BluetoothSocket: bindListen(): myUserId = 0
,01-27 16:49:40.052  9588  9679 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,01-27 16:49:40.052  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,01-27 16:49:40.052  9588  9651 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
01-27 16:49:40.052  9588  9651 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,01-27 16:49:40.052  9588  9679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,01-27 16:49:40.062  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:49:40.062  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:49:40.062  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:49:40.062  3465  3484 D SecContentProvider: insert(), uri = 2
,01-27 16:49:40.062  4942  5285 W bt_btif : bta_dm_acl_change(), event : 2
,01-27 16:49:40.062  3465  4331 V AlarmManager:  remove PendingIntent] PendingIntent{705ca4: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:40.072  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:49:40.072  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,01-27 16:49:40.072  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:49:40.072  3465  4382 V AlarmManager:  remove PendingIntent] PendingIntent{6e99a0d: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
01-27 16:49:40.072  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:49:40.072  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
01-27 16:49:40.072  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
01-27 16:49:40.072  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 3
,01-27 16:49:40.072  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:49:40.072  3465  4059 V AlarmManager:  remove PendingIntent] PendingIntent{174bdc2: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:40.072  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:49:40.072  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:40.072  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,01-27 16:49:40.072  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
01-27 16:49:40.072  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "44:78:3E:94:2C:E6"
01-27 16:49:40.072  9588  9651 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 44 78 3E 94 2C E6
,01-27 16:49:40.072  9588  9651 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
01-27 16:49:40.072  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
01-27 16:49:40.072  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:49:40.072  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:40.072  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
01-27 16:49:40.072  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
01-27 16:49:40.072  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:40.072  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:40.072  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:49:40.082  9588  9651 D BluetoothAdapter: STATE_ON
01-27 16:49:40.082  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:49:40.082  9588  9651 D BluetoothLeAdvertiser: start advertising
01-27 16:49:40.082  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:49:40.082  4942  5319 D BtGatt.GattService: registerClient() - UUID=01a497ff-281f-4c8b-be76-7334c41d87f9
,01-27 16:49:40.132  4942  5106 D BtGatt.GattService: onClientRegistered() - UUID=01a497ff-281f-4c8b-be76-7334c41d87f9, clientIf=8
,01-27 16:49:40.132  9588  9599 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=8
,01-27 16:49:40.132  4942  4960 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,01-27 16:49:40.132  4942  4960 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,01-27 16:49:40.132  4942  4960 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
01-27 16:49:40.132  4942  5179 D BtGatt.AdvertiseManager: message : 0
01-27 16:49:40.132  4942  5190 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_ADV
01-27 16:49:40.132  4942  5190 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 27, currDate: 27
,01-27 16:49:40.132  4942  5179 D BtGatt.AdvertiseManager: number of adv instance running = 0
,01-27 16:49:40.132  4942  5179 D BtGatt.AdvertiseManager: size of list is =0
,01-27 16:49:40.142  4942  5179 D BtGatt.AdvertiseManager: starting advertising
,01-27 16:49:40.142  4942  5179 D BtGatt.AdvertiseManager: isStandardAdv = false
,01-27 16:49:40.142  3465  4485 V AlarmManager:  remove PendingIntent] PendingIntent{69217d3: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:40.142  4942  5190 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.test.thalitest : 78
,01-27 16:49:40.142  4942  5190 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.test.thalitest@LowLatency : 24758869
01-27 16:49:40.142  4942  5190 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.test.thalitest@LowLatency : 2,
01-27 16:49:40.142  4942  5190 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
01-27 16:49:40.142  4942  5190 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 3 => 3
01-27 16:49:40.142  4942  5106 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=8, status=0
,01-27 16:49:40.142  4942  5179 D BtGatt.AdvertiseManager: starting multi advertising
,01-27 16:49:40.142  3465  4042 V AlarmManager:  remove PendingIntent] PendingIntent{fa89f10: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:40.152  4942  5106 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=8, status=0
,01-27 16:49:40.152  4942  5179 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
01-27 16:49:40.152  4942  5179 D BtGatt.AdvertiseManager: clientIf: 8, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,01-27 16:49:40.152  4942  5179 D BtGatt.AdvertiseManager: postCallback clientIf = 8 status = 0
01-27 16:49:40.152  3465  4487 V AlarmManager:  remove PendingIntent] PendingIntent{1a2ca09: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
01-27 16:49:40.152  4942  5179 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=8, status=0, isStart=true
01-27 16:49:40.152  9588  9598 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
01-27 16:49:40.152  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:49:40.152  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:40.152  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
01-27 16:49:40.152  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:49:40.152  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:40.152  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:40.152  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:40.152  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:40.152  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
01-27 16:49:40.152  9588  9651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
01-27 16:49:40.152  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:40.152  9588  9651 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: seems that updateState call different BlePeerDiscoverer
01-27 16:49:40.152  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:40.162  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:40.162  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:40.162  9588  9651 I io.jxcore.node.ConnectionHelper: start: OK
01-27 16:49:40.162  9588  9588 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,01-27 16:49:40.162  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
01-27 16:49:40.162  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
01-27 16:49:40.162  3465  4488 V AlarmManager:  remove PendingIntent] PendingIntent{7d4f40e: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
01-27 16:49:40.162  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
01-27 16:49:40.162  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
,01-27 16:49:40.162  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
01-27 16:49:40.162  9588  9588 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
01-27 16:49:40.162  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
01-27 16:49:40.162  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
01-27 16:49:40.162  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
01-27 16:49:40.162  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,01-27 16:49:40.162  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
01-27 16:49:40.162  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
01-27 16:49:40.162  9588  9588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
01-27 16:49:40.162  9588  9588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
01-27 16:49:40.162  9588  9588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
01-27 16:49:40.162  9588  9588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,01-27 16:49:40.162  3465  3484 V AlarmManager:  remove PendingIntent] PendingIntent{8dc5e2f: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
01-27 16:49:40.162  9588  9588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
01-27 16:49:40.162  9588  9588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
01-27 16:49:40.162  9588  9588 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,01-27 16:49:40.172  3465  4416 V AlarmManager:  remove PendingIntent] PendingIntent{1e09c3c: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:40.172  3465  4226 V AlarmManager:  remove PendingIntent] PendingIntent{ea4fdc5: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:40.182  3465  4489 V AlarmManager:  remove PendingIntent] PendingIntent{cf0431a: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:40.662  9588  9667 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
01-27 16:49:40.662  9588  9651 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
01-27 16:49:40.662  9588  9651 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
01-27 16:49:40.662  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,01-27 16:49:40.662  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
01-27 16:49:40.662  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
01-27 16:49:40.662  9588  9651 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
01-27 16:49:40.662  9588  9651 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,01-27 16:49:40.662  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
01-27 16:49:40.662  9588  9679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,01-27 16:49:40.662  9588  9679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
01-27 16:49:40.662  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
01-27 16:49:40.662  9588  9679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
01-27 16:49:40.662  9588  9588 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,01-27 16:49:40.662  9588  9588 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
01-27 16:49:40.662  9588  9588 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
01-27 16:49:40.662  9588  9588 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,01-27 16:49:40.662  9588  9651 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49a8aa8 removed from the list
01-27 16:49:40.672  9588  9651 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49a8aa8 removed from the list
01-27 16:49:40.672  9588  9651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
01-27 16:49:40.672  9588  9651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,01-27 16:49:40.672  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:40.672  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
01-27 16:49:40.672  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
01-27 16:49:40.672  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:40.672  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:40.672  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:40.672  9588  9682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 210
01-27 16:49:40.672  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:49:40.672  9588  9682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
01-27 16:49:40.672  9588  9682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 210)
01-27 16:49:40.672  9588  9682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 210)
,01-27 16:49:40.672  4942  5393 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 8, channel: 1
01-27 16:49:40.672  9588  9678 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, read failed, socket might closed or timeout, read ret: -1
01-27 16:49:40.672  9588  9651 D BluetoothAdapter: STATE_ON
01-27 16:49:40.672  9588  9678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
01-27 16:49:40.672  9588  9678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 210)
,01-27 16:49:40.682  9588  9651 D BluetoothAdapter: STATE_ON
01-27 16:49:40.682  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,01-27 16:49:40.682  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:49:40.682  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:49:40.682  9588  9651 D BluetoothLeScanner: could not find callback wrapper
01-27 16:49:40.682  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,01-27 16:49:40.682  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:40.682  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:40.682  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:40.682  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
01-27 16:49:40.682  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:49:40.692  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:49:40.692  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:49:40.692  9588  9651 D BluetoothLeAdvertiser: stop advertising
,01-27 16:49:40.702  4942  5319 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,01-27 16:49:40.702  4942  5319 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
01-27 16:49:40.702  4942  5179 D BtGatt.AdvertiseManager: message : 1
01-27 16:49:40.702  4942  5190 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_ADV
,01-27 16:49:40.702  4942  5190 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 27, currDate: 27
01-27 16:49:40.702  4942  5190 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
01-27 16:49:40.702  4942  5190 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 3 => 3
01-27 16:49:40.702  4942  5190 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
,01-27 16:49:40.702  4942  5179 D BtGatt.AdvertiseManager: stop advertise for client =  8
01-27 16:49:40.702  4942  5179 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 8
,01-27 16:49:40.712  4942  5179 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,01-27 16:49:40.712  4942  5106 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=8, status=0
,01-27 16:49:40.712  4942  5106 D BtGatt.GattService: Client app is not null!
01-27 16:49:40.712  3465  4403 V AlarmManager:  remove PendingIntent] PendingIntent{6daae4b: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
01-27 16:49:40.712  9588  9599 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,01-27 16:49:40.712  4942  4966 D BtGatt.GattService: unregisterClient() - clientIf=8
,01-27 16:49:40.722  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,01-27 16:49:40.722  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:40.722  3465  4485 V AlarmManager:  remove PendingIntent] PendingIntent{5394028: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
01-27 16:49:40.722  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,01-27 16:49:40.722  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:40.722  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:49:40.722  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:40.722  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
01-27 16:49:40.722  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
01-27 16:49:40.722  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
01-27 16:49:40.722  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:49:40.732  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:49:40.732  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
01-27 16:49:40.732  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:40.732  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:49:40.732  9588  9651 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fc69c1 removed from the list
01-27 16:49:40.732  9588  9588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
01-27 16:49:40.732  9588  9651 D io.jxcore.node.ConnectivityMonitor: stop
,01-27 16:49:40.732  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
01-27 16:49:40.732  9588  9588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
01-27 16:49:40.732  9588  9588 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,01-27 16:49:40.732  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
01-27 16:49:40.732  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,01-27 16:49:40.732  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
01-27 16:49:40.732  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
01-27 16:49:40.732  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,01-27 16:49:40.732  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
01-27 16:49:40.732  9588  9588 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,01-27 16:49:40.732  3465  4226 V AlarmManager:  remove PendingIntent] PendingIntent{1dcb141: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:40.742  3465  4489 V AlarmManager:  remove PendingIntent] PendingIntent{23f76e6: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:40.752  3465  3977 V AlarmManager:  remove PendingIntent] PendingIntent{723e427: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:40.762  3465  4382 V AlarmManager:  remove PendingIntent] PendingIntent{6f636d4: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:40.772  3465  4225 V AlarmManager:  remove PendingIntent] PendingIntent{782207d: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:40.782  3465  4042 V AlarmManager:  remove PendingIntent] PendingIntent{5fc1b72: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:41.232  9588  9588 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,01-27 16:49:43.402  3465  6068 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,01-27 16:49:45.732  9588  9671 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
,01-27 16:49:45.732  9588  9651 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,01-27 16:49:45.742  9588  9651 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,01-27 16:49:45.742  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,01-27 16:49:45.742  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,01-27 16:49:45.742  9588  9651 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
01-27 16:49:45.742  9588  9651 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
01-27 16:49:45.742  9588  9651 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,01-27 16:49:45.742  9588  9651 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
01-27 16:49:45.742  9588  9651 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
01-27 16:49:45.742  9588  9588 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
01-27 16:49:45.742  9588  9683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,01-27 16:49:45.752  9588  9651 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
,01-27 16:49:45.752  9588  9683 D BluetoothSocket: bindListen(): myUserId = 0
01-27 16:49:45.752  9588  9683 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
01-27 16:49:45.752  9588  9651 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [00:11:22:33:44:55], error message: ErrorMessage
01-27 16:49:45.752  9588  9651 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,01-27 16:49:45.752  9588  9651 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
01-27 16:49:45.752  9588  9651 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,01-27 16:49:45.752  9588  9651 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
,01-27 16:49:45.762  9588  9683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,01-27 16:49:45.772  9588  9651 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
01-27 16:49:45.772  9588  9651 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,01-27 16:49:45.772  9588  9651 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
01-27 16:49:45.772  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
01-27 16:49:45.772  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
01-27 16:49:45.772  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,01-27 16:49:45.772  9588  9651 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
01-27 16:49:45.772  9588  9651 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
01-27 16:49:45.772  9588  9651 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49a8aa8 not in the list
01-27 16:49:45.772  9588  9683 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,01-27 16:49:45.772  9588  9683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
01-27 16:49:45.772  9588  9651 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49a8aa8 not in the list
01-27 16:49:45.772  9588  9683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,01-27 16:49:45.772  9588  9651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
01-27 16:49:45.772  9588  9588 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
01-27 16:49:45.772  9588  9651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
01-27 16:49:45.772  9588  9588 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
01-27 16:49:45.772  9588  9588 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,01-27 16:49:45.772  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:45.772  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
01-27 16:49:45.772  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
01-27 16:49:45.772  9588  9651 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
01-27 16:49:45.772  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
01-27 16:49:45.772  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:45.782  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:49:45.782  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
01-27 16:49:45.782  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:45.782  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:49:45.782  9588  9651 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fc69c1 not in the list
01-27 16:49:45.782  9588  9588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,01-27 16:49:45.782  9588  9651 D io.jxcore.node.ConnectivityMonitor: stop
01-27 16:49:45.782  9588  9651 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
01-27 16:49:45.782  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
01-27 16:49:45.782  9588  9588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
01-27 16:49:45.782  9588  9588 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,01-27 16:49:45.782  9588  9651 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
01-27 16:49:45.782  9588  9651 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,01-27 16:49:45.782  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
01-27 16:49:45.782  9588  9651 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
01-27 16:49:45.782  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
01-27 16:49:45.782  9588  9651 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,01-27 16:49:45.792  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
01-27 16:49:45.792  9588  9651 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
,01-27 16:49:45.792  9588  9651 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
,01-27 16:49:45.792  9588  9651 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
,01-27 16:49:45.792  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [incoming]
,01-27 16:49:45.792  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [outgoing]
,01-27 16:49:45.802  9588  9651 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
01-27 16:49:45.802  9588  9651 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
01-27 16:49:45.802  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,01-27 16:49:45.802  9588  9651 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
01-27 16:49:45.802  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
01-27 16:49:45.802  9588  9651 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
01-27 16:49:45.802  9588  9651 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,01-27 16:49:45.802  9588  9651 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
01-27 16:49:45.802  9588  9651 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
01-27 16:49:45.802  9588  9651 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,01-27 16:49:45.802  9588  9651 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
01-27 16:49:45.802  9588  9651 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,01-27 16:49:45.802  9588  9651 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
01-27 16:49:45.802  9588  9651 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
01-27 16:49:45.802  9588  9651 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,01-27 16:49:45.802  9588  9651 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
,01-27 16:49:45.812  9588  9651 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,01-27 16:49:45.812  9588  9651 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aec0f84 added. We now have 2 listener(s)
01-27 16:49:45.812  9588  9651 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aec0f84 added. We now have 3 listener(s)
01-27 16:49:45.812  9588  9651 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,01-27 16:49:45.812  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"44:78:3E:94:2C:E6"}
,01-27 16:49:45.812  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
01-27 16:49:45.812  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"44:78:3E:94:2C:E6"}
01-27 16:49:45.812  9588  9651 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
01-27 16:49:45.812  9588  9651 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@755036d added. We now have 4 listener(s)
01-27 16:49:45.812  9588  9651 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,01-27 16:49:45.812  9588  9651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,01-27 16:49:45.822  9588  9651 D BluetoothAdapter: enable()
,01-27 16:49:45.832  9588  9651 D BluetoothAdapter: enable(): BT is already enabled..!
,01-27 16:49:45.842  3465  3538 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8e09bc3 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{47dcb8b 4974:com.samsung.android.providers.context/u0a7}
01-27 16:49:45.842  9588  9651 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,01-27 16:49:45.842  3465  4416 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,01-27 16:49:45.842  3465  4416 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,01-27 16:49:45.852  3465  4416 D WifiService: setWifiEnabled: true pid=9588, uid=10074
,01-27 16:49:45.852  3465  4416 W ActivityManager: Permission Denial: getCurrentUser() from pid=9588, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
01-27 16:49:45.852  3465  4416 W WifiService: Failed getting userId using ActivityManagerNative
01-27 16:49:45.852  3465  4416 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9588, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
01-27 16:49:45.852  3465  4416 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
01-27 16:49:45.852  3465  4416 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
01-27 16:49:45.852  3465  4416 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
01-27 16:49:45.852  3465  4416 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
01-27 16:49:45.852  3465  4416 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
01-27 16:49:45.852  3465  4416 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
01-27 16:49:45.852  3465  4416 D SettingsProvider: isChangeAllowed() : name = wifi_on
,01-27 16:49:45.852  3465  3860 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,01-27 16:49:45.852  3465  3863 D WifiController: [FCC]setFccChannel() is called !!!
,01-27 16:49:45.852  3465  3863 D WifiStateMachine: setFccChannel: channel = -1
,01-27 16:49:45.852  3465  3863 D WifiController: [FCC]Airplane off, setFccChannel(-1)!!!
01-27 16:49:45.852  9588  9651 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
,01-27 16:49:45.852  3465  3860 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 ,
,01-27 16:49:45.852  3465  3860 D WifiBigDataLog: init : 
01-27 16:49:45.862  3465  3860 D WifiStateMachine: setFccChannelNative: channel = -1
01-27 16:49:45.862  3465  3860 D WifiNative-wlan0: callSECApiInt - ID [230]
01-27 16:49:45.862  9588  9651 D BluetoothAdapter: STATE_ON
01-27 16:49:45.872  9588  9651 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
,01-27 16:49:45.872  9588  9651 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
01-27 16:49:45.872  9588  9651 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
,01-27 16:49:45.872  3465  3538 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2e9ec40 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{47dcb8b 4974:com.samsung.android.providers.context/u0a7}
,01-27 16:49:45.882  9588  9684 D BluetoothAdapter: disable()
,01-27 16:49:45.892  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:49:45.892  9588  9651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
01-27 16:49:45.892  9588  9651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
01-27 16:49:45.892  9588  9651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
01-27 16:49:45.892  9588  9651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
01-27 16:49:45.892  9588  9651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
01-27 16:49:45.892  9588  9651 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
01-27 16:49:45.892  9588  9651 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
01-27 16:49:45.892  9588  9651 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
01-27 16:49:45.892  9588  9651 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,01-27 16:49:45.902  3465  3538 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d154779 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{47dcb8b 4974:com.samsung.android.providers.context/u0a7}
,01-27 16:49:45.902  3465  4042 D SettingsProvider: isChangeAllowed() : name = bluetooth_on
,01-27 16:49:45.902  3465  3559 D SecContentProvider: insert(), uri = 2
,01-27 16:49:45.902  4942  5097 D BluetoothAdapterState: Current state: ON, message: BLE_TURN_OFF
,01-27 16:49:45.912  4942  5097 D BluetoothAdapterProperties: Setting state to 13
,01-27 16:49:45.912  4942  5097 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
01-27 16:49:45.912  4942  5097 D BluetoothAdapterService: Bluetooth PBAP supproted is true
01-27 16:49:45.912  4942  5097 D BluetoothAdapterService: updateAdapterState state is 13
,01-27 16:49:45.922  4942  4942 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,01-27 16:49:45.922  4942  5097 D BluetoothAdapterService: Autoconnection is available 
01-27 16:49:45.922  3465  3559 D BluetoothManagerService: Turning On/Off, G state: 3, S state: 2, mBLE count: 2, s BLE count: 2
01-27 16:49:45.922  4942  5097 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
,01-27 16:49:45.922  4942  5097 D BluetoothAdapterService: terminating service from this receiver
,01-27 16:49:45.922  3465  3465 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,01-27 16:49:45.922  3465  3465 I InputMethodManagerService: [BT Setting State] State =13
,01-27 16:49:45.922  3950  4150 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
01-27 16:49:45.922  3950  4150 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,01-27 16:49:45.922  4374  4374 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
,01-27 16:49:45.932  4826  4826 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,01-27 16:49:45.932  3465  3465 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
,01-27 16:49:45.932  3465  3465 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
01-27 16:49:45.932  3465  3465 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,01-27 16:49:45.942  9588  9588 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,01-27 16:49:45.942  9588  9588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
01-27 16:49:45.942  9588  9588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
01-27 16:49:45.942  9588  9588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
01-27 16:49:45.942  9588  9588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
01-27 16:49:45.942  9588  9588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
01-27 16:49:45.942  9588  9588 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
01-27 16:49:45.942  9588  9588 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
01-27 16:49:45.942  9588  9588 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
01-27 16:49:45.942  9588  9588 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
01-27 16:49:45.942  9588  9588 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,01-27 16:49:45.942  9588  9588 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,01-27 16:49:45.942  3465  3538 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b27311f u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9f9c89d 9097:com.android.settings/1000}
,01-27 16:49:45.942  4942  5097 D BluetoothAdapterProperties: onBluetoothDisable()
,01-27 16:49:45.942  3950  3950 D BluetoothPbap: Proxy object disconnected
01-27 16:49:45.942  3950  3950 D PbapServerProfile: Bluetooth service disconnected
,01-27 16:49:45.952  4942  5097 W bt_btif : btif_dm_cancel_discovery
,01-27 16:49:45.952  3465  3973 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
01-27 16:49:45.952  4942  4942 D BleAudioService: onReceive:: INTENT mAobleStateChangeListener got : android.bluetooth.adapter.action.STATE_CHANGED
01-27 16:49:45.952  4942  4942 D BleAudioService: BluetoothAdapter.ACTION_STATE_CHANGED,  state is13
,01-27 16:49:45.952  3465  3484 D SecContentProvider: insert(), uri = 2
,01-27 16:49:45.962  3465  4489 V AlarmManager:  remove PendingIntent] PendingIntent{da18c6c: PendingIntentRecord{e19e235 com.android.bluetooth broadcastIntent}}
,01-27 16:49:45.962  4942  5097 I BluetoothAdapterState: Entering PendingCommandState
01-27 16:49:45.962  9097  9097 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,01-27 16:49:45.962  3465  4331 V AlarmManager:  remove PendingIntent] PendingIntent{defa6ca: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:45.962  4942  5106 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
01-27 16:49:45.962  4942  5106 D BluetoothAdapterProperties: Scan Mode:20
,01-27 16:49:45.962  3950  4188 D BluetoothTile: handleUpdateState :  supported = true, enabled = false, enabling = false, connected = false, connecting = false, mController.getLastDeviceName() = null
,01-27 16:49:45.972  3465  4059 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
01-27 16:49:45.972  3950  3950 D QSTileView: handleLabelStateChanged() label = Bluetooth cellWidth 272
,01-27 16:49:45.972  9588  9588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,01-27 16:49:45.972  4942  5097 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BEGIN_DISABLE
,01-27 16:49:45.982  9097  9097 D LocalBluetoothManager: LocalBluetoothManager :: sInstance == null
,01-27 16:49:45.982  3465  4416 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b27311f u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{47dcb8b 4974:com.samsung.android.providers.context/u0a7}
,01-27 16:49:45.982  9097  9097 D LocalBluetoothManager: LocalBluetoothManager :: constructor
,01-27 16:49:45.992  9097  9097 D BluetoothEventManager: BluetoothEventManager Constructor :: 
,01-27 16:49:45.992  3465  4416 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b27311f u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fa96432 4239:com.google.android.gms.persistent/u0a19}
,01-27 16:49:45.992  4239  4239 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
,01-27 16:49:46.002  4942  4942 D ObexServerSockets: shutdown(block = true)
01-27 16:49:46.002  4942  4942 D ObexServerSockets: shutdown called from another thread - interrupt().
01-27 16:49:46.002  4942  5434 V ObexServerSockets: Accept exception: (expected at shutdown)java.io.IOException: read failed, socket might closed or timeout, read ret: -1
01-27 16:49:46.002  4942  4942 D ObexServerSockets: shutdown called from another thread - interrupt().
01-27 16:49:46.002  4942  5434 D ObexServerSockets: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
01-27 16:49:46.002  4942  5393 E bt_btif : BTM_SEC_CLR[17]: id 
01-27 16:49:46.002  4942  5435 V ObexServerSockets: Accept exception: (expected at shutdown)java.io.IOException: read failed, socket might closed or timeout, read ret: -1
01-27 16:49:46.002  4942  5435 D ObexServerSockets: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
01-27 16:49:46.002  4942  4942 D BluetoothSdpJni: sdpRemoveSdpRecordNative:
01-27 16:49:46.002  4942  4942 D BluetoothSdpJni: SDP Remove record success - handle: 1
01-27 16:49:46.002  4942  5097 E BluetoothServiceJni: disableBrEdrNative:
01-27 16:49:46.002  4942  5097 E bt_bluedroid: disable_bredr
01-27 16:49:46.002  4942  4942 D BluetoothSdpJni: sdpRemoveSdpRecordNative:
01-27 16:49:46.002  4942  4942 D BluetoothSdpJni: SDP Remove record success - handle: 0
01-27 16:49:46.002  4942  4942 I BtOppRfcommListener: stopping Accept Thread
,01-27 16:49:46.012  4942  5099 E bt_btif : BTA_DisableBluetoothOnly
01-27 16:49:46.012  4942  5285 W bt_btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
01-27 16:49:46.012  4942  5285 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,01-27 16:49:46.012  4942  5421 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,01-27 16:49:46.012  4942  5421 I BtOppRfcommListener: BluetoothSocket listen thread finished
,01-27 16:49:46.012  9097  9097 D LocalBluetoothProfileManager: PANU : true
,01-27 16:49:46.012  4942  5099 D IOP_DB_BT: db_close: nbr users 0
,01-27 16:49:46.012  4942  5099 D IOP_DB_BT: db_close: free database
,01-27 16:49:46.022  4942  5285 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x2  CID 0x40
,01-27 16:49:46.022  4942  5285 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 8
01-27 16:49:46.022  4942  5285 W bt_btif : bta_dm_acl_change(), event : 2
01-27 16:49:46.022  4942  5285 W bt_btif : bta_dm_acl_change(), event : 5
,01-27 16:49:46.022  3465  4416 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b27311f u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{33d4c87 8711:com.sec.android.app.shealth:remote/u0a36}
,01-27 16:49:46.032  3465  4489 V AlarmManager:  remove PendingIntent] PendingIntent{68ffbb3: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:46.042  9097  9097 D BluetoothSap: Create BluetoothSap proxy object
01-27 16:49:46.042  3465  4382 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
01-27 16:49:46.042  3465  4382 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4336, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
01-27 16:49:46.042  3465  4382 D BatteryService: online:4, current avg:56, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-42
01-27 16:49:46.042  3465  3465 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,01-27 16:49:46.052  3465  4403 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b27311f u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9f9c89d 9097:com.android.settings/1000}
,01-27 16:49:46.052  4942  4942 V BluetoothOppManager: cleanUp...
,01-27 16:49:46.052  3465  3465 I MotionRecognitionService: Plugged
01-27 16:49:46.052  3465  3465 D MotionRecognitionService:   cableConnection= 1
01-27 16:49:46.052  3465  3465 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
01-27 16:49:46.052  3465  3465 D MotionRecognitionService: skip setTransmitPower. 
,01-27 16:49:46.062  3465  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,01-27 16:49:46.062  3950  3950 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
01-27 16:49:46.062  3950  3950 D KeyguardUpdateMonitor: handleBatteryUpdate
,01-27 16:49:46.062  3950  3950 D PowerUI : priorPlugType = 2 mPlugType =  2
,01-27 16:49:46.062  3950  3950 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,01-27 16:49:46.062  3950  3950 D PowerUI.Notification: There is no change about charging status, so return!
,01-27 16:49:46.062  4990  4990 D CommonServiceConfiguration: getStringValueSetting
,01-27 16:49:46.072  4942  4942 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
01-27 16:49:46.072  4942  5321 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,01-27 16:49:46.072  4990  4990 D BatteryMonitor: new battery level: 100
,01-27 16:49:46.072  9097  9097 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
01-27 16:49:46.072  9097  9097 D LocalBluetoothManager: LocalBluetoothManager :: onInitCallback != null
,01-27 16:49:46.072  4942  5285 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
01-27 16:49:46.072  4942  5285 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
01-27 16:49:46.072  4942  5285 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
01-27 16:49:46.072  4942  5285 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
01-27 16:49:46.072  4942  5285 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
01-27 16:49:46.072  4942  5285 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
01-27 16:49:46.072  4942  5285 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
01-27 16:49:46.072  4942  5285 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
01-27 16:49:46.072  4942  5285 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
01-27 16:49:46.072  4942  5285 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
01-27 16:49:46.072  4942  5285 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
01-27 16:49:46.072  4942  5285 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
01-27 16:49:46.072  4942  5285 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
01-27 16:49:46.072  4942  5285 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
01-27 16:49:46.072  4942  5285 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,01-27 16:49:46.082  3465  4416 V AlarmManager:  remove PendingIntent] PendingIntent{e37f288: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
01-27 16:49:46.082  9097  9097 D DockEventReceiver: finishStartingService: stopping service
,01-27 16:49:46.092  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
01-27 16:49:46.092  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,01-27 16:49:46.092  9097  9097 D BluetoothPan: BluetoothPAN Proxy object connected
,01-27 16:49:46.092  9097  9097 D PanProfile: Bluetooth service connected
,01-27 16:49:46.092  4942  5097 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5548134
01-27 16:49:46.092  4942  5106 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:11:22:33:44:55, value is empty for type: 1
,01-27 16:49:46.092  3950  4150 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CLASS_CHANGED
,01-27 16:49:46.102  9097  9097 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
01-27 16:49:46.102  3465  4331 V AlarmManager:  remove PendingIntent] PendingIntent{6e7e421: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
01-27 16:49:46.102  9097  9097 D BluetoothStatusReceiver: AdapterStateChanged :: state = 13
,01-27 16:49:46.102  4942  5106 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
01-27 16:49:46.102  4942  5106 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:11:22:33:44:55, value is empty for type: 241
,01-27 16:49:46.102  9097  9097 D BluetoothSap: Proxy object connected
01-27 16:49:46.102  9097  9097 D SapProfile: Bluetooth service connected
01-27 16:49:46.102  9097  9097 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CLASS_CHANGED
,01-27 16:49:46.112  3465  4416 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b27311f u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cc5b0ad 4942:com.android.bluetooth/1002}
,01-27 16:49:46.132  3465  4226 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b27311f u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9f3bf76 7012:com.google.android.apps.maps/u0a119}
,01-27 16:49:46.212  4942  5106 E BluetoothAdapterState: stateChangeCallback : 16
01-27 16:49:46.212  4942  5097 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_NATIVE_STOPED
01-27 16:49:46.212  3465  3484 V AlarmManager:  remove PendingIntent] PendingIntent{ac46046: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:46.212  4942  5097 D BtConfig.SecureMode: isSecureModeOn:false
01-27 16:49:46.212  4942  5097 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,01-27 16:49:46.212  4942  5097 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,01-27 16:49:46.212  4942  4942 D HeadsetService: Received stop request...Stopping profile...
,01-27 16:49:46.212  4942  5097 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
01-27 16:49:46.212  4942  4942 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Message sending
01-27 16:49:46.212  4942  4942 E HeadsetService: notifyProfileServiceStateChanged
,01-27 16:49:46.232  4942  5097 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,01-27 16:49:46.232  3950  3950 D HeadsetProfile: Bluetooth service disconnected
,01-27 16:49:46.232  3465  3465 D BluetoothHeadset: unRegisterMessageListener : 11
,01-27 16:49:46.232  3465  3465 W BluetoothHeadset: Proxy not attached to service
01-27 16:49:46.232  3465  3465 I Telecom : BluetoothManager : unregister MessageListener
,01-27 16:49:46.232  3465  3465 I Telecom : CallAudioManager: onBluetoothStateChange: no focus
,01-27 16:49:46.242  4942  5097 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,01-27 16:49:46.242  4942  4942 D A2dpService: Received stop request...Stopping profile...
,01-27 16:49:46.242  4942  5361 D A2dpStateMachine: Exit Disconnected: -1
01-27 16:49:46.242  4942  5097 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
01-27 16:49:46.242  4942  4942 D Avrcp   : unregisterContentObserver
01-27 16:49:46.242  4942  4942 D Avrcp   : removeOnActiveSessionsChangedListener
,01-27 16:49:46.242  4942  4942 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Message sending
01-27 16:49:46.242  4942  4942 E A2dpService: notifyProfileServiceStateChanged
,01-27 16:49:46.242  3465  3465 D BluetoothA2dp: Proxy object disconnected
01-27 16:49:46.252  4942  5097 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
01-27 16:49:46.252  3950  3950 D BluetoothA2dp: Proxy object disconnected
01-27 16:49:46.252  3950  3950 D A2dpProfile: Bluetooth service disconnected
01-27 16:49:46.252  4974  4974 D BluetoothA2dp: Proxy object disconnected
,01-27 16:49:46.252  4942  4942 E BluetoothAdapterService: handleMessage() - Message: 1
,01-27 16:49:46.252  4942  4942 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Before synchronized
01-27 16:49:46.252  4942  4942 V BluetoothAdapterState: isTurningOff()=true
,01-27 16:49:46.252  4942  4942 V BluetoothAdapterState: isTurningOn()=false
01-27 16:49:46.252  4942  4942 V BluetoothAdapterState: isBleTurningOn()=false
,01-27 16:49:46.252  4942  4942 V BluetoothAdapterState: isBleTurningOff()=false
01-27 16:49:46.252  4942  5097 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,01-27 16:49:46.252  4942  5097 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,01-27 16:49:46.252  4942  5097 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
01-27 16:49:46.252  4942  5097 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
01-27 16:49:46.252  4942  5097 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.bleaudio.BleAudioService
,01-27 16:49:46.252  4942  4942 D HidService: Received stop request...Stopping profile...
01-27 16:49:46.252  4942  4942 D HidService: Stopping Bluetooth HidService
,01-27 16:49:46.252  4942  4942 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
01-27 16:49:46.252  4942  4942 W bt_btif : cleanup: HH disabling or disabled already, status = 0
01-27 16:49:46.252  4942  4942 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
01-27 16:49:46.252  4942  4942 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, Message sending
01-27 16:49:46.252  4942  4942 E HidService: notifyProfileServiceStateChanged
01-27 16:49:46.252  3950  3950 D BluetoothInputDevice: Proxy object disconnected
,01-27 16:49:46.252  3950  3950 D HidProfile: Bluetooth service disconnected
,01-27 16:49:46.272  4942  4942 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,01-27 16:49:46.272  4942  4942 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
01-27 16:49:46.272  4942  4942 D HeadsetProvider: cleanup
01-27 16:49:46.272  4942  4942 I HeadsetProvider: clearAllHeadsetSettings(0)
,01-27 16:49:46.282  9588  9588 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,01-27 16:49:46.292  4942  4942 D HealthService: Received stop request...Stopping profile...
,01-27 16:49:46.292  4942  4942 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, Message sending
01-27 16:49:46.292  4942  4942 E HealthService: notifyProfileServiceStateChanged
,01-27 16:49:46.292  4942  4942 D PanService: Received stop request...Stopping profile...
,01-27 16:49:46.292  4942  4942 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, Message sending
01-27 16:49:46.292  4942  4942 E PanService: notifyProfileServiceStateChanged
01-27 16:49:46.292  3465  3465 D BluetoothPan: BluetoothPAN Proxy object disconnected
,01-27 16:49:46.292  9097  9097 D BluetoothPan: BluetoothPAN Proxy object disconnected
01-27 16:49:46.292  9097  9097 D PanProfile: Bluetooth service disconnected
01-27 16:49:46.292  3950  3950 D BluetoothPan: BluetoothPAN Proxy object disconnected
01-27 16:49:46.292  3950  3950 D PanProfile: Bluetooth service disconnected
,01-27 16:49:46.292  4942  4942 E BluetoothAdapterService: handleMessage() - Message: 1
01-27 16:49:46.292  4942  4942 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Before synchronized
,01-27 16:49:46.292  4942  4942 V BluetoothAdapterState: isTurningOff()=true
01-27 16:49:46.292  4942  4942 V BluetoothAdapterState: isTurningOn()=false
01-27 16:49:46.292  4942  4942 V BluetoothAdapterState: isBleTurningOn()=false
01-27 16:49:46.292  4942  4942 V BluetoothAdapterState: isBleTurningOff()=false
,01-27 16:49:46.302  4942  4942 D BluetoothMapService: Received stop request...Stopping profile...
,01-27 16:49:46.302  4942  4942 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Message sending
,01-27 16:49:46.302  4942  4942 E BluetoothMapService: notifyProfileServiceStateChanged
,01-27 16:49:46.302  3950  3950 D BluetoothMap: Proxy object disconnected
01-27 16:49:46.302  3950  3950 D MapProfile: Bluetooth service disconnected
,01-27 16:49:46.302  4942  4942 D SapService: Received stop request...Stopping profile...
,01-27 16:49:46.302  4942  4942 V SapService: stop()
01-27 16:49:46.312  4942  4942 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=10, Message sending
,01-27 16:49:46.312  4942  4942 E SapService: notifyProfileServiceStateChanged
,01-27 16:49:46.312  3950  3950 D BluetoothSap: Proxy object disconnected
01-27 16:49:46.312  3950  3950 D SapProfile: Bluetooth service disconnected
01-27 16:49:46.312  9097  9097 D BluetoothSap: Proxy object disconnected
01-27 16:49:46.312  9097  9097 D SapProfile: Bluetooth service disconnected
,01-27 16:49:46.312  4942  4942 E BluetoothAdapterService: handleMessage() - Message: 1
,01-27 16:49:46.312  4942  4942 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, Before synchronized
01-27 16:49:46.312  4942  4942 V BluetoothAdapterState: isTurningOff()=true
,01-27 16:49:46.312  4942  4942 V BluetoothAdapterState: isTurningOn()=false
01-27 16:49:46.312  4942  4942 V BluetoothAdapterState: isBleTurningOn()=false
01-27 16:49:46.312  4942  4942 V BluetoothAdapterState: isBleTurningOff()=false
01-27 16:49:46.312  4942  4942 D BluetoothAdapterService: HID Host service will be diabled
,01-27 16:49:46.312  4942  4942 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,01-27 16:49:46.312  4942  4942 D BleAudioService: Received stop request...Stopping profile...
01-27 16:49:46.312  4942  4942 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.broadcom.bt.service.bleaudio.BleAudioService, state=10, Message sending
01-27 16:49:46.312  4942  5377 E BleAudioStateMachine_L: Exit Disconnected: -1
01-27 16:49:46.312  4942  5379 E BleAudioStateMachine_R: Exit Disconnected: -1
01-27 16:49:46.312  4942  4942 E BleAudioService: notifyProfileServiceStateChanged
,01-27 16:49:46.312  3950  3950 D BluetoothLeAudio: Proxy object disconnected
01-27 16:49:46.312  3950  3950 D BleAudioProfile: Bluetooth service disconnected
,01-27 16:49:46.322  4942  4942 E BluetoothAdapterService: handleMessage() - Message: 1
,01-27 16:49:46.322  4942  4942 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, Before synchronized
,01-27 16:49:46.322  4942  4942 V BluetoothAdapterState: isTurningOff()=true
01-27 16:49:46.322  4942  4942 V BluetoothAdapterState: isTurningOn()=false
01-27 16:49:46.322  4942  4942 V BluetoothAdapterState: isBleTurningOn()=false
,01-27 16:49:46.322  4942  4942 V BluetoothAdapterState: isBleTurningOff()=false
01-27 16:49:46.322  4942  4942 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,01-27 16:49:46.322  4942  4942 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
01-27 16:49:46.322  4942  4942 E BluetoothAdapterService: handleMessage() - Message: 1
01-27 16:49:46.322  4942  4942 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, Before synchronized
,01-27 16:49:46.322  4942  4942 V BluetoothAdapterState: isTurningOff()=true
,01-27 16:49:46.322  4942  4942 V BluetoothAdapterState: isTurningOn()=false
01-27 16:49:46.322  4942  4942 V BluetoothAdapterState: isBleTurningOn()=false
01-27 16:49:46.322  4942  4942 V BluetoothAdapterState: isBleTurningOff()=false
01-27 16:49:46.322  4942  4942 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
01-27 16:49:46.322  4942  4942 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,01-27 16:49:46.332  4942  4942 E BluetoothAdapterService: handleMessage() - Message: 1
,01-27 16:49:46.332  4942  4942 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Before synchronized
01-27 16:49:46.332  4942  4942 V BluetoothAdapterState: isTurningOff()=true
01-27 16:49:46.332  4942  4942 V BluetoothAdapterState: isTurningOn()=false
,01-27 16:49:46.332  4942  4942 V BluetoothAdapterState: isBleTurningOn()=false
01-27 16:49:46.332  4942  4942 V BluetoothAdapterState: isBleTurningOff()=false
01-27 16:49:46.332  4942  4942 E BluetoothAdapterService: handleMessage() - Message: 1
01-27 16:49:46.332  4942  4942 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=10, Before synchronized
,01-27 16:49:46.332  4942  4942 V BluetoothAdapterState: isTurningOff()=true
01-27 16:49:46.332  4942  4942 V BluetoothAdapterState: isTurningOn()=false
,01-27 16:49:46.332  4942  4942 V BluetoothAdapterState: isBleTurningOn()=false
01-27 16:49:46.332  4942  4942 V BluetoothAdapterState: isBleTurningOff()=false
01-27 16:49:46.332  4942  4942 E BluetoothAdapterService: handleMessage() - Message: 1
01-27 16:49:46.332  4942  4942 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.bleaudio.BleAudioService, state=10, Before synchronized
,01-27 16:49:46.332  4942  4942 V BluetoothAdapterState: isTurningOff()=true
01-27 16:49:46.332  4942  4942 V BluetoothAdapterState: isTurningOn()=false
01-27 16:49:46.332  4942  4942 V BluetoothAdapterState: isBleTurningOn()=false
01-27 16:49:46.332  4942  4942 V BluetoothAdapterState: isBleTurningOff()=false
01-27 16:49:46.332  4942  5097 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_STOPPED
,01-27 16:49:46.332  4942  4942 V BleAudioService: [unregisterCallStateListener]
,01-27 16:49:46.332  4942  4942 W BtBleAudio.JNI: WARNING: cleanupNative(L385): Cleaning up  Ble audio left callback object##
01-27 16:49:46.332  4942  4942 W BtBleAudio.JNI: WARNING: cleanupNative(L403): Cleaning up Ble audio Interface...##
,01-27 16:49:46.332  4942  4942 W BtBleAudio.JNI: WARNING: cleanupNative(L391): Cleaning up  Ble audio right callback object##
01-27 16:49:46.332  4942  5097 D BluetoothAdapterProperties: Setting state to 15
01-27 16:49:46.332  4942  5097 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
01-27 16:49:46.332  4942  4942 V BleAudioService: [unregisterAobleStateChangeListener] Unregistering mAobleStateChangeListener
,01-27 16:49:46.332  4942  5097 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,01-27 16:49:46.332  4942  5097 D BluetoothAdapterService: updateAdapterState state is 15
,01-27 16:49:46.342  4942  5097 D BluetoothAdapterService: Autoconnection is available 
01-27 16:49:46.342  4942  5097 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 15
,01-27 16:49:46.342  9097  9107 D BluetoothAdapter: onBluetoothStateChange: up=false
01-27 16:49:46.342  9097  9107 D BluetoothAdapter: Bluetooth is turned off, stop adv
01-27 16:49:46.342  4942  5097 I BluetoothAdapterState: Entering BleOnState
,01-27 16:49:46.342  9097  9107 D BluetoothAdapter: There are no active google scan apps, stop scan
,01-27 16:49:46.342  7498  7510 D BluetoothAdapter: onBluetoothStateChange: up=false
,01-27 16:49:46.342  3950  4357 D BluetoothLeAudio: onBluetoothStateChange: up=false
01-27 16:49:46.342  3950  4357 D BluetoothLeAudio: Unbinding service...
01-27 16:49:46.342  4974  4989 D BluetoothA2dp: onBluetoothStateChange: up=false
,01-27 16:49:46.342  4290  4301 D BluetoothAdapter: onBluetoothStateChange: up=false
01-27 16:49:46.342  4290  4301 D BluetoothAdapter: Bluetooth is turned off, stop adv
,01-27 16:49:46.352  3465  3973 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,01-27 16:49:46.352  3465  3973 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4338, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
01-27 16:49:46.352  3465  3973 D BatteryService: online:4, current avg:55, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:137
01-27 16:49:46.352  3465  3465 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,01-27 16:49:46.352  4290  4301 D BluetoothAdapter: There are no active google scan apps, stop scan
,01-27 16:49:46.352  3950  3965 D BluetoothMap: onBluetoothStateChange: up=false
01-27 16:49:46.352  3465  3465 I MotionRecognitionService: Plugged
,01-27 16:49:46.352  3465  3465 D MotionRecognitionService:   cableConnection= 1
01-27 16:49:46.352  3465  3465 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
01-27 16:49:46.352  3465  3465 D MotionRecognitionService: skip setTransmitPower. 
,01-27 16:49:46.352  3465  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,01-27 16:49:46.352  3950  3950 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
01-27 16:49:46.352  3950  3950 D KeyguardUpdateMonitor: handleBatteryUpdate
,01-27 16:49:46.352  3950  3950 D PowerUI : priorPlugType = 2 mPlugType =  2
,01-27 16:49:46.352  3950  3950 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
01-27 16:49:46.352  3950  3950 D PowerUI.Notification: There is no change about charging status, so return!
,01-27 16:49:46.362  4990  4990 D CommonServiceConfiguration: getStringValueSetting
,01-27 16:49:46.362  4990  4990 D BatteryMonitor: new battery level: 100
01-27 16:49:46.372  9588  9598 D BluetoothAdapter: onBluetoothStateChange: up=false
01-27 16:49:46.372  9588  9598 D BluetoothAdapter: Bluetooth is turned off, stop adv
,01-27 16:49:46.372  9588  9598 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
01-27 16:49:46.372  9588  9598 D BluetoothLeAdvertiser: Exit stop advertising
,01-27 16:49:46.372  9588  9598 D BluetoothAdapter: There are no active google scan apps, stop scan
01-27 16:49:46.372  9588  9598 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
01-27 16:49:46.372  9588  9598 D BluetoothLeScanner: Exiting stopAllScan
,01-27 16:49:46.372  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,01-27 16:49:46.372  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,01-27 16:49:46.372  8711  8722 D BluetoothAdapter: onBluetoothStateChange: up=false
,01-27 16:49:46.372  8711  8722 D BluetoothAdapter: Bluetooth is turned off, stop adv
01-27 16:49:46.382  8711  8722 D BluetoothAdapter: There are no active google scan apps, stop scan
,01-27 16:49:46.382  3950  5552 D BluetoothA2dp: onBluetoothStateChange: up=false
,01-27 16:49:46.382  4239  6933 D BluetoothAdapter: onBluetoothStateChange: up=false
,01-27 16:49:46.382  4239  6933 D BluetoothAdapter: Bluetooth is turned off, stop adv
01-27 16:49:46.382  4239  6933 D BluetoothAdapter: There are no active google scan apps, stop scan
,01-27 16:49:46.382  4239  6933 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
01-27 16:49:46.382  4239  6933 D BluetoothLeScanner: Exiting stopAllScan
01-27 16:49:46.382  3950  4357 D BluetoothPbap: onBluetoothStateChange: up=false
,01-27 16:49:46.382  3950  3963 D BluetoothInputDevice: onBluetoothStateChange: up=false
,01-27 16:49:46.382  3950  3965 D BluetoothPan: onBluetoothStateChange on: false
,01-27 16:49:46.382  9097  9109 D BluetoothSap: onBluetoothStateChange: up=false
,01-27 16:49:46.382  4942  5319 D BluetoothAdapter: onBluetoothStateChange: up=false
,01-27 16:49:46.382  3950  5549 D BluetoothAdapter: onBluetoothStateChange: up=false
01-27 16:49:46.382  3950  5549 D BluetoothAdapter: Bluetooth is turned off, stop adv
,01-27 16:49:46.382  3950  5549 D BluetoothAdapter: There are no active google scan apps, stop scan
,01-27 16:49:46.392  4302  5231 D BluetoothAdapter: onBluetoothStateChange: up=false
01-27 16:49:46.392  4302  5231 D BluetoothAdapter: Bluetooth is turned off, stop adv
,01-27 16:49:46.392  4302  5231 D BluetoothAdapter: There are no active google scan apps, stop scan
01-27 16:49:46.392  3465  3559 D BluetoothPan: onBluetoothStateChange on: false
,01-27 16:49:46.392  3465  3559 D BluetoothAdapter: onBluetoothStateChange: up=false
01-27 16:49:46.392  3465  3559 D BluetoothAdapter: Bluetooth is turned off, stop adv
01-27 16:49:46.392  3465  3559 D BluetoothAdapter: There are no active google scan apps, stop scan
01-27 16:49:46.392  9097  9107 D BluetoothPan: onBluetoothStateChange on: false
,01-27 16:49:46.392  4974  4988 D BluetoothAdapter: onBluetoothStateChange: up=false
,01-27 16:49:46.392  4974  4988 D BluetoothAdapter: Bluetooth is turned off, stop adv
01-27 16:49:46.392  4974  4988 D BluetoothAdapter: There are no active google scan apps, stop scan
,01-27 16:49:46.392  7012  7527 D BluetoothAdapter: onBluetoothStateChange: up=false
01-27 16:49:46.392  7012  7527 D BluetoothAdapter: Bluetooth is turned off, stop adv
,01-27 16:49:46.392  7012  7527 D BluetoothAdapter: There are no active google scan apps, stop scan
,01-27 16:49:46.392  3465  3559 D BluetoothA2dp: onBluetoothStateChange: up=false
,01-27 16:49:46.392  3950  4357 D BluetoothSap: onBluetoothStateChange: up=false
,01-27 16:49:46.402  3465  3465 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
01-27 16:49:46.402  3465  3465 I InputMethodManagerService: [BT Setting State] State =10
01-27 16:49:46.402  3465  3465 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,01-27 16:49:46.402  3950  4150 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
01-27 16:49:46.402  3950  4150 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,01-27 16:49:46.402  4374  4374 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
,01-27 16:49:46.402  4826  4826 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,01-27 16:49:46.402  3465  3465 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
01-27 16:49:46.402  3465  3465 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
01-27 16:49:46.402  3465  3465 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,01-27 16:49:46.412  9097  9097 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,01-27 16:49:46.412  9097  9097 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,01-27 16:49:46.422  3465  3538 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7168207 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9f9c89d 9097:com.android.settings/1000}
,01-27 16:49:46.422  9588  9684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
01-27 16:49:46.422  9588  9684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
01-27 16:49:46.422  9588  9684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
01-27 16:49:46.422  9588  9684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
01-27 16:49:46.422  9588  9684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
01-27 16:49:46.422  9588  9684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
01-27 16:49:46.422  9588  9684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
01-27 16:49:46.422  9588  9684 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
01-27 16:49:46.422  9588  9684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
01-27 16:49:46.422  9588  9684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,01-27 16:49:46.422  9588  9588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,01-27 16:49:46.432  9588  9684 D BluetoothAdapter: enable()
,01-27 16:49:46.432  9588  9651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,01-27 16:49:46.432  3950  4188 D BluetoothTile: handleUpdateState :  supported = true, enabled = false, enabling = false, connected = false, connecting = false, mController.getLastDeviceName() = null
01-27 16:49:46.432  9097  9097 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,01-27 16:49:46.432  3465  4489 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,01-27 16:49:46.442  3465  4416 W ActivityManager: Permission Denial: getCurrentUser() from pid=9588, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
,01-27 16:49:46.442  3465  4416 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
01-27 16:49:46.442  3465  4416 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9588, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
01-27 16:49:46.442  3465  4416 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
01-27 16:49:46.442  3465  4416 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2852)
01-27 16:49:46.442  3465  4416 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2842)
01-27 16:49:46.442  3465  4416 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.setBtEnableFlag(BluetoothManagerService.java:1222)
01-27 16:49:46.442  3465  4416 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:254)
01-27 16:49:46.442  3465  4416 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:453)
01-27 16:49:46.442  3465  4416 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,01-27 16:49:46.442  3465  4416 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,01-27 16:49:46.442  3465  4416 D SettingsProvider: isChangeAllowed() : name = bluetooth_on
,01-27 16:49:46.452  9588  9684 D BluetoothAdapter: BT is in BLE_ON State or TURNING_OFF state
,01-27 16:49:46.462  3465  4382 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7168207 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{47dcb8b 4974:com.samsung.android.providers.context/u0a7}
,01-27 16:49:46.472  4942  5097 D BluetoothAdapterState: Current state: BLE ON, message: USER_TURN_ON
,01-27 16:49:46.482  3465  4382 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7168207 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fa96432 4239:com.google.android.gms.persistent/u0a19}
,01-27 16:49:46.482  4239  4239 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
,01-27 16:49:46.492  9097  9097 D DockEventReceiver: finishStartingService: stopping service
01-27 16:49:46.492  4942  5097 D BluetoothAdapterProperties: Setting state to 11
01-27 16:49:46.492  4942  5097 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
01-27 16:49:46.492  4942  5097 D BluetoothAdapterService: Bluetooth PBAP supproted is true
01-27 16:49:46.492  4942  5097 D BluetoothAdapterService: updateAdapterState state is 11
,01-27 16:49:46.492  3465  3559 D BluetoothManagerService: Turning On/Off, G state: 1, S state: 2, mBLE count: 2, s BLE count: 2
,01-27 16:49:46.492  4942  5097 D BluetoothAdapterService: Autoconnection is available 
01-27 16:49:46.492  4942  5097 D BluetoothAdapterService: updateAdapterState prevState = 15newState = 11
01-27 16:49:46.492  4942  5097 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
01-27 16:49:46.492  4942  5097 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
01-27 16:49:46.492  4942  5097 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,01-27 16:49:46.502  3465  4382 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7168207 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{33d4c87 8711:com.sec.android.app.shealth:remote/u0a36}
,01-27 16:49:46.522  4942  5097 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,01-27 16:49:46.522  4942  4942 D HeadsetService: Received start request. Starting profile...
01-27 16:49:46.522  4942  4942 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5548134
01-27 16:49:46.522  3465  3465 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
01-27 16:49:46.522  4942  4942 D HeadsetProvider: make
01-27 16:49:46.522  3465  3465 I InputMethodManagerService: [BT Setting State] State =11
01-27 16:49:46.522  4942  4942 D HeadsetProvider: HeadsetProvider
01-27 16:49:46.522  4942  4942 I HeadsetProvider: clearAllHeadsetSettings(0)
,01-27 16:49:46.532  3950  4150 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
01-27 16:49:46.532  3950  4150 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,01-27 16:49:46.532  4374  4374 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
,01-27 16:49:46.532  4826  4826 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,01-27 16:49:46.532  4942  4942 D HeadsetStateMachine: make
01-27 16:49:46.532  3465  3465 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
01-27 16:49:46.532  3465  3465 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
01-27 16:49:46.532  3465  3465 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,01-27 16:49:46.532  4942  4942 E HeadsetStateMachine: # of Max HF connection is 3
,01-27 16:49:46.542  9097  9097 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,01-27 16:49:46.542  9097  9097 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,01-27 16:49:46.552  4942  5097 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,01-27 16:49:46.562  9588  9588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,01-27 16:49:46.562  3465  4488 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
01-27 16:49:46.562  3950  4188 D BluetoothTile: handleUpdateState :  supported = true, enabled = false, enabling = true, connected = false, connecting = false, mController.getLastDeviceName() = null
,01-27 16:49:46.562  3950  3950 D QSTileView: handleLabelStateChanged() label = Bluetooth cellWidth 272
,01-27 16:49:46.572  4942  5097 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,01-27 16:49:46.572  3465  4382 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7168207 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9f9c89d 9097:com.android.settings/1000}
,01-27 16:49:46.572  9097  9097 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
01-27 16:49:46.572  9097  9097 D BluetoothStatusReceiver: AdapterStateChanged :: state = 10
,01-27 16:49:46.592  4942  5097 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,01-27 16:49:46.602  4942  4942 I bt_bluedroid: get_profile_interface handsfree
,01-27 16:49:46.602  4942  5097 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,01-27 16:49:46.612  3465  4059 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7168207 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cc5b0ad 4942:com.android.bluetooth/1002}
,01-27 16:49:46.622  4942  4942 E DualScoManager: Dual Sco Manager already instantiated
01-27 16:49:46.622  4942  5097 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
01-27 16:49:46.622  4942  4942 I DualScoManager: Set HeadsetServiceHelper
01-27 16:49:46.622  4942  4942 D BluetoothAtMessage: createCMTIContentObservers
,01-27 16:49:46.632  4942  5097 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
01-27 16:49:46.632  4942  5097 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
01-27 16:49:46.632  4942  5097 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
01-27 16:49:46.632  4942  5097 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
01-27 16:49:46.632  4942  5097 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.bleaudio.BleAudioService
,01-27 16:49:46.642  4942  5097 I BluetoothAdapterState: Entering PendingCommandState
,01-27 16:49:46.652  4942  5097 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5548134
,01-27 16:49:46.652  4942  4942 D HeadsetProvider: Created cursor android.database.sqlite.SQLiteCursor@7f250f0
01-27 16:49:46.652  4942  4942 D HeadsetProvider: setHeadsetDB - Can't find 300 for 44:78:3E:94:2C:XX
,01-27 16:49:46.662  4942  4942 I HeadsetProvider: setHeadsetDB - 44:78:3E:94:2C:XX, 300, 1, true
,01-27 16:49:46.672  4942  4942 D HeadsetProvider: Created cursor android.database.sqlite.SQLiteCursor@df7a18f
,01-27 16:49:46.672  4942  4942 D HeadsetProvider: setHeadsetDB - Can't find 400 for 44:78:3E:94:2C:XX
,01-27 16:49:46.682  4942  4942 I HeadsetProvider: setHeadsetDB - 44:78:3E:94:2C:XX, 400, 1, true
,01-27 16:49:46.682  4942  9696 D HeadsetStateMachine: Enter Disconnected: -2, size: 0/0
,01-27 16:49:46.682  4942  4942 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Message sending
,01-27 16:49:46.682  4942  4942 E HeadsetService: notifyProfileServiceStateChanged
,01-27 16:49:46.682  4942  9696 D HeadsetStateMachine: Clear mHeadsetBrsf
01-27 16:49:46.682  4942  9696 D HeadsetStateMachine: map size, before remove : 0
,01-27 16:49:46.682  4942  9696 D HeadsetStateMachine: map size, after remove: 0
,01-27 16:49:46.692  4942  4942 D A2dpService: Received start request. Starting profile...
,01-27 16:49:46.692  4942  4942 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5548134
01-27 16:49:46.692  4942  4942 I bt_bluedroid: get_profile_interface avrcp
,01-27 16:49:46.692  4942  4942 I Avrcp   : No of Audio players :: 1
,01-27 16:49:46.692  4942  4942 I Avrcp   : App Package name is GM
,01-27 16:49:46.702  4942  4942 V Avrcp   : MediaPlayerInfo: mPlayerId=1
,01-27 16:49:46.702  4942  4942 I Avrcp   : No of Video players :: 2
,01-27 16:49:46.702  4942  4942 I Avrcp   : Video App Package name is others
,01-27 16:49:46.702  4942  4942 V Avrcp   : MediaPlayerInfo: mPlayerId=2
01-27 16:49:46.702  4942  4942 I Avrcp   : Video App Package name is VP
,01-27 16:49:46.702  4942  4942 V Avrcp   : MediaPlayerInfo: mPlayerId=3
,01-27 16:49:46.702  4942  4942 I Avrcp   : Add tempPlayer
01-27 16:49:46.702  4942  4942 V Avrcp   : MediaPlayerInfo: mPlayerId=4
01-27 16:49:46.702  4942  4942 V Avrcp   : no_of_players : 4
01-27 16:49:46.702  4942  4942 I Avrcp   : Total no of players: 4
01-27 16:49:46.702  4942  4942 V Avrcp   : Samsung player is the 1st player
01-27 16:49:46.702  4942  4942 D Avrcp   : Compose Browsing Service Candidate
01-27 16:49:46.702  4942  4942 D Avrcp   : ResolveInfo info ResolveInfo{70b4e08 com.google.android.music/.browse.MediaBrowserService m=0x108000}
01-27 16:49:46.702  4942  4942 D Avrcp   : Initialize Media Controller
,01-27 16:49:46.702  4942  4942 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,01-27 16:49:46.702  4942  4942 E Avrcp   : getActiveSessions
01-27 16:49:46.702  4942  4942 D Avrcp   : pick active media Controller
01-27 16:49:46.702  4942  4942 D Avrcp   : Get the active Media Controller 
01-27 16:49:46.712  4942  4942 D A2dpStateMachine: make
01-27 16:49:46.712  4942  4942 I bt_bluedroid: get_profile_interface a2dp
,01-27 16:49:46.712  4942  4942 E bt_btif : warning : media task started media_task_refcnt 1 
,01-27 16:49:46.712  4942  9699 D A2dpStateMachine: Enter Disconnected: -2
,01-27 16:49:46.712  4942  4942 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Message sending
01-27 16:49:46.712  4942  4942 E A2dpService: notifyProfileServiceStateChanged
,01-27 16:49:46.712  4942  4942 D HeadsetStateMachine: Try to query the phonestate on bind
01-27 16:49:46.712  3465  4042 I Telecom : BluetoothPhoneService: queryPhoneState
,01-27 16:49:46.712  3465  4042 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState : true
,01-27 16:49:46.712  4942  4942 D HidService: Received start request. Starting profile...
,01-27 16:49:46.712  4942  4942 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5548134
01-27 16:49:46.712  4942  4942 I bt_bluedroid: get_profile_interface hidhost
01-27 16:49:46.712  4942  4942 D HidService: setHidService(): set to: null
01-27 16:49:46.712  4942  4942 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, Message sending
01-27 16:49:46.722  4942  4942 E HidService: notifyProfileServiceStateChanged
,01-27 16:49:46.722  4942  4942 D HeadsetStateMachine: Proxy object connected
,01-27 16:49:46.722  4942  4942 D HealthService: Received start request. Starting profile...
01-27 16:49:46.722  4942  4942 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5548134
,01-27 16:49:46.722  4942  4942 I bt_bluedroid: get_profile_interface health
,01-27 16:49:46.722  4942  4942 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, Message sending
01-27 16:49:46.722  4942  4942 E HealthService: notifyProfileServiceStateChanged
,01-27 16:49:46.722  4942  4942 D PanService: Received start request. Starting profile...
,01-27 16:49:46.722  4942  4942 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5548134
01-27 16:49:46.722  4942  4942 D BluetoothPanServiceJni: initializeNative(L118): pan
01-27 16:49:46.722  4942  4942 I bt_bluedroid: get_profile_interface pan
01-27 16:49:46.722  4942  4942 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, Message sending
01-27 16:49:46.722  4942  4942 E PanService: notifyProfileServiceStateChanged
,01-27 16:49:46.722  4942  4942 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
01-27 16:49:46.722  4942  9696 D HeadsetStateMachine: Disconnected process message: 11, size: 0
01-27 16:49:46.722  4942  9696 E HeadsetStateMachine: Unknown message: 11
01-27 16:49:46.722  4942  4942 D HeadsetPhoneState: sendDeviceDataStateChanged
01-27 16:49:46.722  4942  9696 D HeadsetStateMachine: Disconnected process message: 19, size: 0
01-27 16:49:46.722  4942  9696 E HeadsetStateMachine: Unknown message: 19
01-27 16:49:46.722  4942  4942 D HeadsetPhoneState: Signal level : previous=0 curr=4
01-27 16:49:46.732  4942  4942 D BluetoothMapService: Received start request. Starting profile...
,01-27 16:49:46.732  4942  4942 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5548134
,01-27 16:49:46.732  3465  4488 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7168207 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9f3bf76 7012:com.google.android.apps.maps/u0a119}
,01-27 16:49:46.752  3465  4485 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1f07785 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{47dcb8b 4974:com.samsung.android.providers.context/u0a7}
,01-27 16:49:46.762  4942  4942 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Message sending
01-27 16:49:46.762  4942  4942 E BluetoothMapService: notifyProfileServiceStateChanged
,01-27 16:49:46.762  4942  4942 V SapService: SapBinder()
,01-27 16:49:46.762  4942  4942 D SapService: Received start request. Starting profile...
01-27 16:49:46.762  4942  4942 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5548134
01-27 16:49:46.762  4942  4942 V SapService: start()
01-27 16:49:46.762  4942  4942 D SapService: Disable sap : false
,01-27 16:49:46.772  3465  4485 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{38d1e0b u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9f9c89d 9097:com.android.settings/1000}
,01-27 16:49:46.772  4942  4942 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=12, Message sending
01-27 16:49:46.772  4942  4942 E SapService: notifyProfileServiceStateChanged
,01-27 16:49:46.782  4942  4942 D BleAudioService: Received start request. Starting profile...
01-27 16:49:46.782  4942  4942 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5548134
01-27 16:49:46.782  4942  4942 E DualScoManager: Dual Sco Manager already instantiated
01-27 16:49:46.782  4942  4942 D BleAudioStateMachine: make
,01-27 16:49:46.782  4942  4942 I BleAudioStateMachine: Constructor Of BleAudioStateMachine
01-27 16:49:46.782  4942  4942 D BtBleAudio.JNI: initializeNative(L309): ble audio jni initializeNative: 0
01-27 16:49:46.782  4942  4942 I bt_bluedroid: get_profile_interface bleaudio_source
01-27 16:49:46.782  4942  4942 D BleAudioStateMachine: make
01-27 16:49:46.782  4942  9704 E BleAudioStateMachine_L: Enter Disconnected: -2
,01-27 16:49:46.782  4942  4942 I BleAudioStateMachine: Constructor Of BleAudioStateMachine
,01-27 16:49:46.782  4942  4942 D BtBleAudio.JNI: initializeNative(L309): ble audio jni initializeNative: 1
01-27 16:49:46.782  4942  4942 V BleAudioService: [registerCallStateListener]
01-27 16:49:46.782  4942  9705 E BleAudioStateMachine_R: Enter Disconnected: -2
,01-27 16:49:46.782  3465  4331 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{38d1e0b u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{47dcb8b 4974:com.samsung.android.providers.context/u0a7}
,01-27 16:49:46.792  4942  4942 V BleAudioService: [registerAobleStateChangeListener]
,01-27 16:49:46.802  3465  4489 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{38d1e0b u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fa96432 4239:com.google.android.gms.persistent/u0a19}
,01-27 16:49:46.802  4239  4239 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
,01-27 16:49:46.812  4942  4942 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.broadcom.bt.service.bleaudio.BleAudioService, state=12, Message sending
,01-27 16:49:46.812  4942  4942 E BleAudioService: notifyProfileServiceStateChanged
01-27 16:49:46.812  4942  4942 E BluetoothAdapterService: handleMessage() - Message: 1
01-27 16:49:46.812  4942  4942 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Before synchronized
01-27 16:49:46.812  4942  4942 V BluetoothAdapterState: isTurningOff()=false
,01-27 16:49:46.812  4942  4942 V BluetoothAdapterState: isTurningOn()=true
01-27 16:49:46.812  4942  4942 V BluetoothAdapterState: isBleTurningOn()=false
01-27 16:49:46.812  4942  4942 V BluetoothAdapterState: isBleTurningOff()=false
01-27 16:49:46.812  4942  4942 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
01-27 16:49:46.812  4942  4942 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
01-27 16:49:46.812  4942  9696 D HeadsetStateMachine: Disconnected process message: 10, size: 0
01-27 16:49:46.812  4942  4942 D HeadsetPhoneState: sendDeviceDataStateChanged
01-27 16:49:46.812  4942  4942 D HeadsetPhoneState: Signal level : previous=0 curr=4
01-27 16:49:46.812  4942  9696 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
01-27 16:49:46.812  4942  4942 E BluetoothAdapterService: handleMessage() - Message: 1
,01-27 16:49:46.812  4942  4942 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Before synchronized
01-27 16:49:46.812  4942  9696 D HeadsetStateMachine: Disconnected process message: 11, size: 0
01-27 16:49:46.812  4942  9696 E HeadsetStateMachine: Unknown message: 11
01-27 16:49:46.812  4942  9696 D HeadsetStateMachine: Disconnected process message: 19, size: 0
01-27 16:49:46.812  4942  9696 E HeadsetStateMachine: Unknown message: 19
01-27 16:49:46.812  4942  9696 D HeadsetStateMachine: Disconnected process message: 11, size: 0
01-27 16:49:46.812  4942  9696 E HeadsetStateMachine: Unknown message: 11
01-27 16:49:46.812  4942  4942 V BluetoothAdapterState: isTurningOff()=false
01-27 16:49:46.812  4942  4942 V BluetoothAdapterState: isTurningOn()=true
,01-27 16:49:46.812  4942  4942 V BluetoothAdapterState: isBleTurningOn()=false
01-27 16:49:46.812  4942  4942 V BluetoothAdapterState: isBleTurningOff()=false
01-27 16:49:46.812  4942  4942 E BluetoothAdapterService: handleMessage() - Message: 1
01-27 16:49:46.812  4942  4942 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, Before synchronized
01-27 16:49:46.812  4942  4942 V BluetoothAdapterState: isTurningOff()=false
01-27 16:49:46.812  4942  4942 V BluetoothAdapterState: isTurningOn()=true
01-27 16:49:46.812  4942  4942 V BluetoothAdapterState: isBleTurningOn()=false
01-27 16:49:46.812  4942  4942 V BluetoothAdapterState: isBleTurningOff()=false
01-27 16:49:46.812  4942  4942 D BluetoothAdapterService: HID Host service started
,01-27 16:49:46.812  3465  4489 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{38d1e0b u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{33d4c87 8711:com.sec.android.app.shealth:remote/u0a36}
,01-27 16:49:46.822  3950  4150 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CONNECTION_HID_HOST
01-27 16:49:46.822  4942  4942 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
01-27 16:49:46.822  4942  4942 E BluetoothAdapterService: handleMessage() - Message: 1
01-27 16:49:46.822  4942  4942 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, Before synchronized
01-27 16:49:46.822  9097  9097 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CONNECTION_HID_HOST
,01-27 16:49:46.822  3950  4150 W LocalBluetoothProfileManager: updateLocalProfiles :: A2DP profile was previously added but the UUID is now missing.
,01-27 16:49:46.822  4942  4942 V BluetoothAdapterState: isTurningOff()=false
01-27 16:49:46.822  4942  4942 V BluetoothAdapterState: isTurningOn()=true
01-27 16:49:46.822  4942  4942 V BluetoothAdapterState: isBleTurningOn()=false
01-27 16:49:46.822  4942  4942 V BluetoothAdapterState: isBleTurningOff()=false
01-27 16:49:46.822  4942  4942 E BluetoothAdapterService: handleMessage() - Message: 1
01-27 16:49:46.822  4942  4942 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, Before synchronized
01-27 16:49:46.822  3950  4150 W LocalBluetoothProfileManager: updateLocalProfiles :: HEADSET profile was previously added but the UUID is now missing.
,01-27 16:49:46.822  3950  4150 W LocalBluetoothProfileManager: updateLocalProfiles :: MAP profile was previously added but the UUID is now missing.
,01-27 16:49:46.822  3950  4150 W LocalBluetoothProfileManager: updateLocalProfiles :: PBAP profile was previously added but the UUID is now missing.
01-27 16:49:46.822  4942  4942 V BluetoothAdapterState: isTurningOff()=false
01-27 16:49:46.822  9097  9097 D BluetoothMap: Create BluetoothMap proxy object
01-27 16:49:46.822  4942  4942 V BluetoothAdapterState: isTurningOn()=true
01-27 16:49:46.822  4942  4942 V BluetoothAdapterState: isBleTurningOn()=false
01-27 16:49:46.822  4942  4942 V BluetoothAdapterState: isBleTurningOff()=false
01-27 16:49:46.832  3950  4150 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
01-27 16:49:46.832  4942  4942 E BluetoothAdapterService: handleMessage() - Message: 1
01-27 16:49:46.832  4942  4942 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Before synchronized
,01-27 16:49:46.832  3950  4150 D HidProfile: mService is null. need to get proxy again!!
,01-27 16:49:46.832  4942  4942 V BluetoothAdapterState: isTurningOff()=false
01-27 16:49:46.832  4942  4942 V BluetoothAdapterState: isTurningOn()=true
01-27 16:49:46.832  4942  4942 V BluetoothAdapterState: isBleTurningOn()=false
01-27 16:49:46.832  4942  4942 V BluetoothAdapterState: isBleTurningOff()=false
,01-27 16:49:46.832  4942  4942 E BluetoothAdapterService: handleMessage() - Message: 1
01-27 16:49:46.832  4942  4942 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=12, Before synchronized
,01-27 16:49:46.832  4942  4942 V BluetoothAdapterState: isTurningOff()=false
01-27 16:49:46.832  3465  4489 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{38d1e0b u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9f9c89d 9097:com.android.settings/1000}
01-27 16:49:46.832  4942  4942 V BluetoothAdapterState: isTurningOn()=true
01-27 16:49:46.832  4942  4942 V BluetoothAdapterState: isBleTurningOn()=false
01-27 16:49:46.832  4942  4942 V BluetoothAdapterState: isBleTurningOff()=false
01-27 16:49:46.832  4942  4942 D BleAudioService: [onCallStateChanged] ENTER -- State: (0)
01-27 16:49:46.832  4942  4942 D BleAudioService: [onCallStateChanged] No devices in connected state
01-27 16:49:46.832  4942  4942 D BleAudioService: [onCallStateChanged][PHONECALL STATE Changed]: EXIT
01-27 16:49:46.832  4942  4942 E BluetoothAdapterService: handleMessage() - Message: 1
01-27 16:49:46.832  4942  4942 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.bleaudio.BleAudioService, state=12, Before synchronized
,01-27 16:49:46.832  4942  4942 V BluetoothAdapterState: isTurningOff()=false
01-27 16:49:46.832  4942  4942 V BluetoothAdapterState: isTurningOn()=true
01-27 16:49:46.832  4942  4942 V BluetoothAdapterState: isBleTurningOn()=false
01-27 16:49:46.832  4942  4942 V BluetoothAdapterState: isBleTurningOff()=false
01-27 16:49:46.832  4942  5097 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_STARTED
,01-27 16:49:46.842  4942  9707 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,01-27 16:49:46.842  4942  5097 E BluetoothServiceJni: enableBrEdrNative:
01-27 16:49:46.842  4942  5097 I bt_bluedroid: enable_bredr
,01-27 16:49:46.852  3950  3950 D BluetoothInputDevice: Proxy object connected
01-27 16:49:46.852  3950  3950 D HidProfile: Bluetooth service connected
,01-27 16:49:46.852  4942  5106 I bt_bta_hh: BTA_HhEnable sec_mask:0x24 p_cback:0xf33b5f29
01-27 16:49:46.852  4942  5106 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x100048
01-27 16:49:46.852  4942  9707 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
01-27 16:49:46.852  4942  5106 D BluetoothAdapterProperties: Address is:44:78:3E:94:2C:E6
01-27 16:49:46.852  4942  5285 D CODEC_IF: codec_if_open: opening libbt-codec_aptx.so...
01-27 16:49:46.852  4942  5106 E BluetoothServiceJni: populateRssiValuesNative
01-27 16:49:46.852  4942  5106 I bt_bluedroid: getModelRssiValues
01-27 16:49:46.852  4942  5106 E BluetoothServiceJni: model_rssi_values_callback: low = -75, mid = -65, high = 127
01-27 16:49:46.852  4942  5106 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -75,-65,127
01-27 16:49:46.852  4942  5285 D CODEC_IF_MOD: codec_open: codec_open
01-27 16:49:46.852  4942  5285 D CODEC_IF_MOD: codec_open: apt-x encoder initialized successfully
01-27 16:49:46.852  4942  5285 D CODEC_IF_MOD: codec_open:    version : 1.0.1.0
01-27 16:49:46.852  4942  5285 D CODEC_IF_MOD: codec_open:    build : Android_JB_4.2.2
01-27 16:49:46.852  4942  5285 D CODEC_IF: codec_if_open: codec module opened (v0.1
01-27 16:49:46.852  4942  5285 D CODEC_IF: codec_if_close: codec_if_close hdl -293859324
01-27 16:49:46.852  4942  5285 D CODEC_IF_MOD: codec_close: codec_close
01-27 16:49:46.852  4942  5285 D CODEC_IF_MOD: codec_close: freed apt-x encoder
01-27 16:49:46.852  3465  4042 V AlarmManager:  remove PendingIntent] PendingIntent{7259ffb: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:46.852  4942  5285 D         : Codec ==> check 96kHz mode : check_sshd_encoder_available:332
01-27 16:49:46.852  3465  3465 D SettingsProvider: isChangeAllowed() : name = bluetooth_name
01-27 16:49:46.852  4942  5285 D CODEC_IF: codec_if_open: opening libbt-codec_sshd.so...
,01-27 16:49:46.852  4942  5285 D CODEC_IF_SSHD: codec_open: codec_open
01-27 16:49:46.852  4942  5285 D CODEC_IF_SSHD: Codec ==> pcm_info.sampling_freq : 96000
01-27 16:49:46.852  4942  5285 D CODEC_IF_SSHD: codec_open: SSHD encoder initialized successfully
01-27 16:49:46.852  4942  5285 D CODEC_IF: codec_if_open: codec module opened (v0.1
01-27 16:49:46.852  4942  5285 D CODEC_IF: codec_if_close: codec_if_close hdl -587473536
01-27 16:49:46.852  4942  5285 D CODEC_IF_SSHD: codec_close: codec_close
01-27 16:49:46.852  4942  5285 D         : Codec ==> copy capability info [bta_av_co_audio_init:559]
01-27 16:49:46.852  4942  5285 D CODEC_IF: codec_if_open: opening libbt-codec_aptx.so...
01-27 16:49:46.852  9097  9097 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
,01-27 16:49:46.852  4942  5285 D CODEC_IF_MOD: codec_open: codec_open
01-27 16:49:46.852  4942  5285 D CODEC_IF_MOD: codec_open: apt-x encoder initialized successfully
,01-27 16:49:46.852  4942  5285 D CODEC_IF_MOD: codec_open:    version : 1.0.1.0
,01-27 16:49:46.852  4942  5285 D CODEC_IF_MOD: codec_open:    build : Android_JB_4.2.2
01-27 16:49:46.852  4942  5285 D CODEC_IF: codec_if_open: codec module opened (v0.1
01-27 16:49:46.852  4942  5285 D CODEC_IF: codec_if_close: codec_if_close hdl -293859324
,01-27 16:49:46.852  4942  5285 D CODEC_IF_MOD: codec_close: codec_close
01-27 16:49:46.852  4942  5285 D CODEC_IF_MOD: codec_close: freed apt-x encoder
01-27 16:49:46.852  4942  5285 D         : Codec ==> check 96kHz mode : check_sshd_encoder_available:332
01-27 16:49:46.852  4942  5285 D CODEC_IF: codec_if_open: opening libbt-codec_sshd.so...
01-27 16:49:46.852  4942  5285 D CODEC_IF_SSHD: codec_open: codec_open
01-27 16:49:46.852  4942  5285 D CODEC_IF_SSHD: Codec ==> pcm_info.sampling_freq : 96000
01-27 16:49:46.852  4942  5285 D CODEC_IF_SSHD: codec_open: SSHD encoder initialized successfully
,01-27 16:49:46.852  4942  5285 D CODEC_IF: codec_if_open: codec module opened (v0.1
01-27 16:49:46.852  4942  5285 D CODEC_IF: codec_if_close: codec_if_close hdl -587473536
01-27 16:49:46.852  4942  5285 D CODEC_IF_SSHD: codec_close: codec_close
01-27 16:49:46.852  4942  5285 D         : Codec ==> copy capability info [bta_av_co_audio_init:559]
01-27 16:49:46.852  4942  5106 D BluetoothAdapterProperties: Name is: Samsung Galaxy S7
01-27 16:49:46.862  3950  4150 W LocalBluetoothProfileManager: updateLocalProfiles :: BleAudio profile was created already 
01-27 16:49:46.862  4942  5106 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,01-27 16:49:46.862  4942  5106 D BluetoothAdapterProperties: Scan Mode:20
01-27 16:49:46.862  3465  4416 V AlarmManager:  remove PendingIntent] PendingIntent{75db271: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
01-27 16:49:46.862  4942  5106 D BluetoothAdapterProperties: Discoverable Timeout:-1
01-27 16:49:46.862  4942  5106 E bt_btif : btif_handle_bluetooth_enable_evt
,01-27 16:49:46.862  4942  5106 E bt_btif : JVenable fails
,01-27 16:49:46.862  4942  5106 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
01-27 16:49:46.862  4942  5106 D IOP_DB_BT: db_open: db_open : handle 4080242704l, read 18483 bytes onto local cache
01-27 16:49:46.862  4942  5106 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
01-27 16:49:46.862  4942  5106 D IOP_DB_BT: db_query: result 1
01-27 16:49:46.862  4942  5106 I         : iop_db_open: iop_db_open status 0
,01-27 16:49:46.862  4942  5106 E BluetoothAdapterState: stateChangeCallback : 17
,01-27 16:49:46.862  4942  5097 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_NATIVE_STARTED
01-27 16:49:46.872  4942  5106 E bt_btif : no av cb found, event:0, BTA_AV_ENABLE_EVT ignored!
01-27 16:49:46.872  4942  5106 E bt_btif : btif_sm_dispatch : Invalid handle
,01-27 16:49:46.872  4942  5106 E bt_btif : no av control block available at state:3
01-27 16:49:46.872  4942  5106 E bt_btif : no av control block available at state:3
01-27 16:49:46.872  4942  5106 E bt_btif : no av control block available at state:2
01-27 16:49:46.872  4942  5106 E bt_btif : warning : no command pending, ignore ack
01-27 16:49:46.872  4942  5106 E bt_btif : no av control block available at state:3
01-27 16:49:46.872  4942  5106 E bt_btif : no av control block available at state:2
01-27 16:49:46.872  4942  5106 W bt_btif : btif_av_state_idle_handler : unhandled event:BTA_AV_REGISTER_EVT
,01-27 16:49:46.872  4942  5106 E bt_btif : btif_sm_dispatch : Invalid handle
01-27 16:49:46.872  4942  5106 E bt_btif : no av control block available at state:3
01-27 16:49:46.872  4942  5106 E bt_btif : no av control block available at state:3
01-27 16:49:46.872  4942  5106 E bt_btif : no av control block available at state:2
01-27 16:49:46.872  4942  5106 E bt_btif : warning : no command pending, ignore ack
01-27 16:49:46.872  4942  5106 E bt_btif : no av control block available at state:3
01-27 16:49:46.872  4942  5106 E bt_btif : no av control block available at state:2
01-27 16:49:46.872  4942  5106 W bt_btif : btif_av_state_idle_handler : unhandled event:BTA_AV_REGISTER_EVT
01-27 16:49:46.872  4942  5106 E bt_btif : btif_sm_dispatch : Invalid handle
01-27 16:49:46.872  4942  5106 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
01-27 16:49:46.872  4942  5097 D BluetoothAdapterProperties: ScanMode =  20
01-27 16:49:46.872  4942  5097 D BluetoothAdapterProperties: State =  11
01-27 16:49:46.872  9097  9097 D LocalBluetoothProfileManager: Adding local BleAudio profile
01-27 16:49:46.872  3465  4485 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
,01-27 16:49:46.872  9097  9097 D BluetoothLeAudio: getProfileProxy()
,01-27 16:49:46.872  3465  3973 V AlarmManager:  remove PendingIntent] PendingIntent{c7b4dc4: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:46.872  9588  9588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,01-27 16:49:46.882  3465  4488 D SecContentProvider: insert(), uri = 2
,01-27 16:49:46.882  3465  3977 V AlarmManager:  remove PendingIntent] PendingIntent{21373: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:46.882  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,01-27 16:49:46.892  4942  5106 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
01-27 16:49:46.892  4942  5106 D BluetoothAdapterProperties: Scan Mode:21
01-27 16:49:46.892  4942  5097 D BluetoothAdapterProperties: Setting state to 12
01-27 16:49:46.892  4942  5097 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
01-27 16:49:46.892  4942  5097 D HeadsetService: setBleAudioService(): com.broadcom.bt.service.bleaudio.BleAudioService@f4ec126
01-27 16:49:46.892  4942  5097 D A2dpService: setBleAudioService(): com.broadcom.bt.service.bleaudio.BleAudioService@f4ec126
01-27 16:49:46.892  4942  5097 D BleAudioService: setHeadsetService: setting HeadsetService
01-27 16:49:46.892  4942  5097 D BleAudioService: setA2dpService: setting A2dpService
01-27 16:49:46.892  4942  5106 D BluetoothAdapterProperties: Discoverable Timeout:-1
01-27 16:49:46.892  4942  5097 D BluetoothAdapterService: Bluetooth PBAP supproted is true
01-27 16:49:46.892  4942  5097 D BluetoothAdapterService: updateAdapterState state is 12
,01-27 16:49:46.892  9097  9097 D BluetoothLeAudio: Success to bind to IBluetoothLeAudio with Intent { act=com.broadcom.bt.service.bleaudio.IBluetoothLeAudio cmp=com.android.bluetooth/com.broadcom.bt.service.bleaudio.BleAudioService VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
,01-27 16:49:46.892  9097  9097 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
01-27 16:49:46.892  9097  9097 D BluetoothStatusReceiver: AdapterStateChanged :: state = 11
,01-27 16:49:46.892  9588  9588 D BluetoothAdapter: STATE_ON
01-27 16:49:46.892  9097  9097 D BluetoothMap: Proxy object connected
,01-27 16:49:46.892  9097  9097 D MapProfile: Bluetooth service connected
,01-27 16:49:46.902  9588  9588 D BluetoothAdapter: STATE_ON
01-27 16:49:46.902  9097  9097 D BluetoothMap: getConnectedDevices()
,01-27 16:49:46.902  9588  9588 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,01-27 16:49:46.902  4942  5097 V BluetoothAdapterService: start opp service
,01-27 16:49:46.902  9588  9588 D BluetoothAdapter: STATE_ON
,01-27 16:49:46.902  9588  9588 D BluetoothAdapter: STATE_ON
,01-27 16:49:46.912  9588  9588 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,01-27 16:49:46.912  3465  3977 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{38d1e0b u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cc5b0ad 4942:com.android.bluetooth/1002}
,01-27 16:49:46.912  9588  9588 D BluetoothAdapter: STATE_ON
,01-27 16:49:46.922  9588  9588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
01-27 16:49:46.922  9588  9588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
01-27 16:49:46.922  9588  9588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
01-27 16:49:46.922  9588  9588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
01-27 16:49:46.922  9588  9588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
01-27 16:49:46.922  9588  9588 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
01-27 16:49:46.922  9588  9588 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
01-27 16:49:46.922  9588  9588 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
01-27 16:49:46.922  9588  9588 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,01-27 16:49:46.922  9588  9588 D BluetoothAdapter: STATE_ON
,01-27 16:49:46.922  9588  9588 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,01-27 16:49:46.932  4942  4942 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,01-27 16:49:46.932  3465  4331 V AlarmManager:  remove PendingIntent] PendingIntent{8941c65: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:46.932  4942  4942 I BluetoothPbapService: Handler(): got msg=1
01-27 16:49:46.932  4942  5097 D BluetoothAdapterService: Autoconnection is available 
01-27 16:49:46.932  9097  9107 D BluetoothAdapter: onBluetoothStateChange: up=true
,01-27 16:49:46.932  4942  5097 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
01-27 16:49:46.932  9097  9107 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
01-27 16:49:46.932  4942  5097 D BluetoothAdapterService: starting service from this receiver
,01-27 16:49:46.942  7498  7511 D BluetoothAdapter: onBluetoothStateChange: up=true
,01-27 16:49:46.942  7498  7511 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,01-27 16:49:46.942  9097  9097 D BluetoothInputDevice: Proxy object connected
,01-27 16:49:46.942  3465  4382 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
01-27 16:49:46.942  9097  9097 D HidProfile: Bluetooth service connected
01-27 16:49:46.942  9097  9109 D BluetoothPbap: onBluetoothStateChange: up=true
01-27 16:49:46.942  9097  9109 D BluetoothPbap: Binding service...
,01-27 16:49:46.942  4942  5097 D BluetoothAdapterService: BT on, init HID DEV count : 0
,01-27 16:49:46.942  4942  5097 I BluetoothAdapterState: Entering OnState
,01-27 16:49:46.952  3950  4357 D BluetoothLeAudio: onBluetoothStateChange: up=true
,01-27 16:49:46.952  3950  4357 D BluetoothLeAudio: Binding service...
,01-27 16:49:46.952  3465  4488 V AlarmManager:  remove PendingIntent] PendingIntent{9e76748: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:46.952  4942  9711 V BluetoothPbapService: PBAP Service initSocket try: 0
,01-27 16:49:46.952  3950  3950 D BluetoothLeAudio: Proxy object connected
01-27 16:49:46.952  3950  3950 D BleAudioProfile: Bluetooth service connected
01-27 16:49:46.952  3950  3950 D BluetoothLeAudio: getConnectedDevices()
,01-27 16:49:46.962  3950  4357 D BluetoothLeAudio: Success to bind to IBluetoothLeAudio with Intent { act=com.broadcom.bt.service.bleaudio.IBluetoothLeAudio cmp=com.android.bluetooth/com.broadcom.bt.service.bleaudio.BleAudioService VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
,01-27 16:49:46.962  9097  9097 D BluetoothLeAudio: Proxy object connected
,01-27 16:49:46.962  4942  4942 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,01-27 16:49:46.962  9097  9097 D BleAudioProfile: Bluetooth service connected
01-27 16:49:46.962  9097  9097 D BluetoothLeAudio: getConnectedDevices()
,01-27 16:49:46.962  4942  4942 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,01-27 16:49:46.962  4974  5076 D BluetoothA2dp: onBluetoothStateChange: up=true
01-27 16:49:46.962  4974  5076 D BluetoothA2dp: Binding service...
,01-27 16:49:46.972  3465  4403 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{38d1e0b u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9f3bf76 7012:com.google.android.apps.maps/u0a119}
,01-27 16:49:46.972  9097  9097 D BluetoothPbap: Proxy object connected
01-27 16:49:46.972  4942  4942 V BtOppService: isOwner == true
,01-27 16:49:46.972  9097  9097 D PbapServerProfile: Bluetooth service connected
01-27 16:49:46.972  4974  5076 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,01-27 16:49:46.982  3465  4487 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
01-27 16:49:46.982  3465  4487 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4317, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
01-27 16:49:46.982  3465  4487 D BatteryService: online:4, current avg:49, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-303
,01-27 16:49:46.982  3465  3973 V AlarmManager:  remove PendingIntent] PendingIntent{96bf63: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:46.982  3465  3465 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,01-27 16:49:46.992  9097  9107 D BluetoothMap: onBluetoothStateChange: up=true
,01-27 16:49:46.992  4290  4300 D BluetoothAdapter: onBluetoothStateChange: up=true
01-27 16:49:46.992  4290  4300 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,01-27 16:49:46.992  4942  9711 D BluetoothSocket: bindListen(): myUserId = 0
01-27 16:49:46.992  4942  9711 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,01-27 16:49:46.992  3465  4403 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{811d760 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{47dcb8b 4974:com.samsung.android.providers.context/u0a7}
,01-27 16:49:47.002  3950  3965 D BluetoothMap: onBluetoothStateChange: up=true
01-27 16:49:47.002  3950  3965 D BluetoothMap: Binding service...
,01-27 16:49:47.002  3950  3950 D BluetoothMap: Proxy object connected
01-27 16:49:47.002  3950  3950 D MapProfile: Bluetooth service connected
01-27 16:49:47.002  3950  3950 D BluetoothMap: getConnectedDevices()
,01-27 16:49:47.002  3950  5552 D BluetoothInputDevice: onBluetoothStateChange: up=true
,01-27 16:49:47.012  9588  9684 D BluetoothAdapter: STATE_ON
,01-27 16:49:47.012  9588  9599 D BluetoothAdapter: onBluetoothStateChange: up=true
01-27 16:49:47.012  9588  9599 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,01-27 16:49:47.012  3465  3465 I MotionRecognitionService: Plugged
01-27 16:49:47.012  3465  3465 D MotionRecognitionService:   cableConnection= 1
01-27 16:49:47.012  3465  3465 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
01-27 16:49:47.012  3465  3465 D MotionRecognitionService: skip setTransmitPower. 
,01-27 16:49:47.012  8711  8722 D BluetoothAdapter: onBluetoothStateChange: up=true
,01-27 16:49:47.012  8711  8722 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,01-27 16:49:47.012  3950  4357 D BluetoothA2dp: onBluetoothStateChange: up=true
,01-27 16:49:47.012  3950  4357 D BluetoothA2dp: Binding service...
,01-27 16:49:47.012  3465  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
01-27 16:49:47.012  9588  9684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
01-27 16:49:47.012  9588  9684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
01-27 16:49:47.012  9588  9684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
01-27 16:49:47.012  9588  9684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
01-27 16:49:47.012  9588  9684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
01-27 16:49:47.012  9588  9684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
01-27 16:49:47.012  9588  9684 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
01-27 16:49:47.012  9588  9684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
01-27 16:49:47.012  9588  9684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
01-27 16:49:47.012  9588  9651 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
01-27 16:49:47.012  3950  4357 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,01-27 16:49:47.022  3465  4226 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,01-27 16:49:47.022  9588  9651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,01-27 16:49:47.022  3465  4226 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,01-27 16:49:47.022  3465  4226 D WifiService: setWifiEnabled: false pid=9588, uid=10074
,01-27 16:49:47.032  4990  4990 D CommonServiceConfiguration: getStringValueSetting
,01-27 16:49:47.032  4990  4990 D BatteryMonitor: new battery level: 100
,01-27 16:49:47.032  3465  4226 D SettingsProvider: isChangeAllowed() : name = wifi_on
,01-27 16:49:47.032  3465  3863 D WifiStateMachine: setFccChannel: channel = -1
01-27 16:49:47.032  3465  3863 D WifiController: [FCC]setFccChannel() is called !!!
01-27 16:49:47.032  3465  3863 D WifiController: MHS off and WIFI tunred off and move to mApStaDisabledState
01-27 16:49:47.032  3465  3863 D WifiController: [FCC]Airplane off, setFccChannel(-1)!!!
01-27 16:49:47.032  3465  3863 D SecContentProvider: insert(), uri = 2
01-27 16:49:47.032  3465  3860 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
01-27 16:49:47.032  3465  3860 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,01-27 16:49:47.042  3950  3950 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,01-27 16:49:47.042  3950  3950 D PowerUI : priorPlugType = 2 mPlugType =  2
,01-27 16:49:47.042  3465  4382 V AlarmManager:  remove PendingIntent] PendingIntent{322f6b7: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:47.042  3950  3950 D KeyguardUpdateMonitor: handleBatteryUpdate
,01-27 16:49:47.042  3950  3950 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
01-27 16:49:47.042  3950  3950 D PowerUI.Notification: There is no change about charging status, so return!
01-27 16:49:47.042  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
01-27 16:49:47.042  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,01-27 16:49:47.052  4942  9711 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
01-27 16:49:47.052  3465  3860 D WifiBigDataLog: init : 
,01-27 16:49:47.052  4239  4256 D BluetoothAdapter: onBluetoothStateChange: up=true
,01-27 16:49:47.052  4239  4256 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,01-27 16:49:47.052  3465  3860 D WifiStateMachine: setFccChannelNative: channel = -1,
,01-27 16:49:47.052  3465  3860 D WifiNative-wlan0: callSECApiInt - ID [230]
01-27 16:49:47.052  3950  3965 D BluetoothPbap: onBluetoothStateChange: up=true
01-27 16:49:47.062  3465  4485 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{598fe24 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{47dcb8b 4974:com.samsung.android.providers.context/u0a7}
01-27 16:49:47.052  3950  3965 D BluetoothPbap: Binding service...
,01-27 16:49:47.072  3950  3950 D BluetoothPbap: Proxy object connected
01-27 16:49:47.072  3950  3950 D PbapServerProfile: Bluetooth service connected
,01-27 16:49:47.072  3950  5552 D BluetoothInputDevice: onBluetoothStateChange: up=true
,01-27 16:49:47.072  3950  5552 D BluetoothInputDevice: Binding service...
,01-27 16:49:47.082  3465  3860 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,01-27 16:49:47.082  3465  3860 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
01-27 16:49:47.092  3465  4382 V AlarmManager:  remove PendingIntent] PendingIntent{154dcb: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
01-27 16:49:47.092  3950  5549 D BluetoothPan: onBluetoothStateChange on: true
,01-27 16:49:47.092  3950  3950 D BluetoothInputDevice: Proxy object connected
01-27 16:49:47.092  3950  5549 D BluetoothPan: onBluetoothStateChange calling doBind()
01-27 16:49:47.092  3950  3950 D HidProfile: Bluetooth service connected
,01-27 16:49:47.092  3465  3860 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
01-27 16:49:47.092  3465  3860 D WifiStateMachine: sendBroadcastForCaptivePortalNotLoginIcon : false
,01-27 16:49:47.092  4974  4974 D BluetoothA2dp: Proxy object connected
,01-27 16:49:47.092  3465  3860 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
,01-27 16:49:47.092  3465  3860 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
,01-27 16:49:47.092  3950  4150 D NetworkController: onReceive: intent=Intent { act=com.samsung.intent.action.WIFI_CAPTIVE_NOT_LOGIN flg=0x10 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
01-27 16:49:47.092  3465  3860 D SecContentProvider: insert(), uri = 2
01-27 16:49:47.092  3950  4150 D NetworkController.WifiSignalController: updateWifiState : mCurrentState.wifiCaptiveNotLogin = false
,01-27 16:49:47.092  3950  3950 D BluetoothA2dp: Proxy object connected
01-27 16:49:47.092  3950  3950 D A2dpProfile: Bluetooth service connected
,01-27 16:49:47.092  3465  4489 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,01-27 16:49:47.102  3465  3860 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
,01-27 16:49:47.102  3465  3860 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
01-27 16:49:47.102  3465  3860 D WifiStateMachine: sendBroadcastForCaptivePortalNotLoginIcon : false
01-27 16:49:47.102  9097  9109 D BluetoothInputDevice: onBluetoothStateChange: up=true
,01-27 16:49:47.102  3465  3860 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
01-27 16:49:47.102  3465  3860 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
01-27 16:49:47.102  3465  3860 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,01-27 16:49:47.102  3950  4150 D NetworkController: onReceive: intent=Intent { act=com.samsung.intent.action.WIFI_CAPTIVE_NOT_LOGIN flg=0x10 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,01-27 16:49:47.102  3465  3859 D WifiP2pService: InactiveState{ what=143375 }
01-27 16:49:47.102  3950  4150 D NetworkController.WifiSignalController: updateWifiState : mCurrentState.wifiCaptiveNotLogin = false
01-27 16:49:47.102  3465  3859 D WifiP2pService: P2pEnabledState{ what=143375 }
,01-27 16:49:47.102  9097  9710 D BluetoothSap: onBluetoothStateChange: up=true
01-27 16:49:47.102  9097  9710 D BluetoothSap: Binding service...
,01-27 16:49:47.102  4942  4960 D A2dpStateMachine: getConnectedDevices : size=0
01-27 16:49:47.102  3465  4867 V AlarmManager:  remove PendingIntent] PendingIntent{7543c66: PendingIntentRecord{ae71553 android broadcastIntent}}
01-27 16:49:47.102  3162  3715 D CommandListener: Clearing all IP addresses on wlan0
,01-27 16:49:47.112  4239  7673 V NativeCrypto: Read error: ssl=0x7f83328480: I/O error during system call, Connection timed out
,01-27 16:49:47.122  3465  4487 V AlarmManager:  remove PendingIntent] PendingIntent{628fba7: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
01-27 16:49:47.132  3465  3869 E ConnectivityService: updateNetworkInfo()
01-27 16:49:47.132  3465  3869 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -51]
01-27 16:49:47.132  3465  3869 E ConnectivityService: updateNetworkInfo()
01-27 16:49:47.132  3465  3869 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = DISCONNECTED
01-27 16:49:47.132  3465  3869 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 6
,01-27 16:49:47.132  3465  3869 V NetworkStats: updateIfacesLocked()
,01-27 16:49:47.132  3465  3869 D NtpTrustedTime: currentTimeMillis() cache hit
01-27 16:49:47.132  3465  3869 V NetworkStats: performPollLocked(flags=0x1)
,01-27 16:49:47.132  3465  3869 D NetworkStatsRecorder: entry.iface is null
,01-27 16:49:47.132  4239  7673 V NativeCrypto: SSL shutdown failed: ssl=0x7f83328480: I/O error during system call, Broken pipe
,01-27 16:49:47.132  3465  3869 D NetworkStatsRecorder: entry.iface is null
,01-27 16:49:47.132  3465  3869 D NtpTrustedTime: currentTimeMillis() cache hit
,01-27 16:49:47.132  3465  3869 D NetworkStatsRecorder: entry.iface is null
01-27 16:49:47.132  3465  3869 D NetworkStatsRecorder: entry.iface is null
01-27 16:49:47.142  4942  4942 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
01-27 16:49:47.132  3465  3869 V NetworkStats: performPollLocked() took 6ms
01-27 16:49:47.142  4942  9696 D HeadsetStateMachine: Disconnected process message: 10, size: 0
01-27 16:49:47.142  3950  4150 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,01-27 16:49:47.142  3465  4059 V AlarmManager:  remove PendingIntent] PendingIntent{64a3854: PendingIntentRecord{1767c6d com.google.android.gms broadcastIntent}}
,01-27 16:49:47.142  4239  7673 E GCM     : Wifi connection closed with errorCode 20
,01-27 16:49:47.142  3465  3869 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
01-27 16:49:47.142  3465  3869 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -51]
01-27 16:49:47.152  3465  3869 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
01-27 16:49:47.152  3465  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
01-27 16:49:47.152  3465  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
01-27 16:49:47.152  3465  3869 D ConnectivityService: sending notification LOST for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
01-27 16:49:47.152  3465  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
,01-27 16:49:47.152  3465  3869 D ConnectivityService: sending notification LOST for NetworkRequest [ id=5, legacyType=-1, [] ]
01-27 16:49:47.152  3950  3950 D BluetoothPan: BluetoothPAN Proxy object connected
,01-27 16:49:47.152  3950  3950 D PanProfile: Bluetooth service connected
,01-27 16:49:47.152  3465  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,01-27 16:49:47.152  3465  3869 D ConnectivityService: sending notification LOST for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,01-27 16:49:47.152  4942  4966 D BluetoothAdapter: onBluetoothStateChange: up=true
,01-27 16:49:47.152  4942  4966 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,01-27 16:49:47.152  3465  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
01-27 16:49:47.152  3465  3869 D ConnectivityService: sending notification LOST for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,01-27 16:49:47.162  3465  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,01-27 16:49:47.162  9097  9107 D BluetoothLeAudio: onBluetoothStateChange: up=true
01-27 16:49:47.162  3465  3869 D ConnectivityService: sending notification LOST for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,01-27 16:49:47.162  3465  4403 D ConnectivityService: getVpnConfig > userId : 0
,01-27 16:49:47.162  3465  4866 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,01-27 16:49:47.162  3465  3869 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
01-27 16:49:47.162  3465  3894 D Ethernet: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
01-27 16:49:47.162  3465  3894 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
01-27 16:49:47.162  3465  3894 D Ethernet: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,01-27 16:49:47.162  3465  3894 D Ethernet: evalRequest
01-27 16:49:47.162  3465  3894 D Ethernet:   done
01-27 16:49:47.162  3950  5549 D BluetoothAdapter: onBluetoothStateChange: up=true
01-27 16:49:47.162  3950  5549 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
01-27 16:49:47.162  3465  3859 D WIFI_P2P: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
01-27 16:49:47.162  3465  3859 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,01-27 16:49:47.162  3465  3859 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,01-27 16:49:47.162  3465  3859 D WIFI_P2P: evalRequest
01-27 16:49:47.162  3465  3859 D WIFI_P2P:   done
01-27 16:49:47.162  3465  3465 I WifiTrafficPoller: evaluateTrafficStatsPolling
01-27 16:49:47.162  4302  4698 D BluetoothAdapter: onBluetoothStateChange: up=true
01-27 16:49:47.162  4302  4698 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
01-27 16:49:47.172  4942  9718 D BluetoothSocket: bindListen(): myUserId = 0
,01-27 16:49:47.172  4942  9718 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
01-27 16:49:47.172  3465  3559 D BluetoothPan: onBluetoothStateChange on: true
,01-27 16:49:47.172  3465  3559 D BluetoothPan: onBluetoothStateChange calling doBind()
,01-27 16:49:47.172  3465  3465 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
,01-27 16:49:47.172  3465  3465 D HS20StateMachine: [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true]
01-27 16:49:47.172  3465  3465 D HS20StateMachine: checkifOSUAP  null disconnectedFromSsid"NG700"
01-27 16:49:47.172  3465  3465 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
01-27 16:49:47.172  3465  3867 I WifiHs20Service: Message received 5007
01-27 16:49:47.172  3465  3465 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
,01-27 16:49:47.172  3950  4150 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,01-27 16:49:47.182  3465  3858 D NtpTrustedTime: currentTimeMillis() cache hit
,01-27 16:49:47.182  4302  4302 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
01-27 16:49:47.182  3465  3858 D NtpTrustedTime: currentTimeMillis() cache hit
,01-27 16:49:47.182  4942  9717 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,01-27 16:49:47.182  4942  9717 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,01-27 16:49:47.182  3465  3538 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{bdfab43 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e533db5 6432:com.enhance.gameservice/u0a106}
,01-27 16:49:47.192  9097  9097 D BluetoothSap: Proxy object connected
,01-27 16:49:47.192  9097  9097 D SapProfile: Bluetooth service connected
,01-27 16:49:47.192  3465  3559 D BluetoothAdapter: onBluetoothStateChange: up=true
01-27 16:49:47.192  3465  3559 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
01-27 16:49:47.192  9097  9710 D BluetoothPan: onBluetoothStateChange on: true
,01-27 16:49:47.192  9097  9710 D BluetoothPan: onBluetoothStateChange calling doBind()
01-27 16:49:47.192  3465  3465 D BluetoothPan: BluetoothPAN Proxy object connected
,01-27 16:49:47.192  3465  3859 D WifiP2pService: InactiveState{ what=131204 }
,01-27 16:49:47.192  3465  3860 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
01-27 16:49:47.192  3465  3859 D WifiP2pService: P2pEnabledState{ what=131204 }
,01-27 16:49:47.192  3465  3859 D WifiP2pService: sending p2p persistent groups changed broadcast
01-27 16:49:47.192  3465  3484 V AlarmManager:  remove PendingIntent] PendingIntent{da4723e: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
01-27 16:49:47.192  3465  3860 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,01-27 16:49:47.192  3465  3465 D WifiNotificationController: SHOW_NOTI_MESSAGE : 17, visible : false, ssid : null, targetSSID : null, netId : -1, titleType : -1
01-27 16:49:47.192  3465  3860 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
01-27 16:49:47.192  3465  3465 D WifiNotificationController: showMaliciousHotspotDetectionNotification - MaliciousNetwork:null, visible:false
01-27 16:49:47.192  3465  3860 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
01-27 16:49:47.192  3465  3860 D WIFI    : evalRequest
01-27 16:49:47.192  3465  3860 D WIFI    :   needNetworkFor
01-27 16:49:47.192  3465  3860 D WIFI_UT : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
01-27 16:49:47.192  3465  3860 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
01-27 16:49:47.192  3465  3860 D WIFI_UT : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,01-27 16:49:47.192  3465  3860 D WIFI_UT : evalRequest
01-27 16:49:47.192  3465  3860 D WIFI_UT :   done
01-27 16:49:47.192  3465  3860 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
01-27 16:49:47.192  3465  3860 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
01-27 16:49:47.192  3465  3860 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
01-27 16:49:47.192  3465  3860 D WIFI    : evalRequest
01-27 16:49:47.192  3465  3860 D WIFI    :   done
,01-27 16:49:47.202  4942  9718 I BtOppRfcommListener: Accept thread started.
,01-27 16:49:47.202  3465  3465 D RttService: SCAN_AVAILABLE : 1
01-27 16:49:47.202  3465  3893 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
01-27 16:49:47.202  3162  3715 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,01-27 16:49:47.212  4064  4064 I wpa_supplicant: P2P: Set prekey state (NONE -> NONE)
01-27 16:49:47.212  4064  4064 I wpa_supplicant: P2P: Clear a pre-passphrase (State NONE)
,01-27 16:49:47.212  3465  3859 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,01-27 16:49:47.212  4974  4989 D BluetoothAdapter: onBluetoothStateChange: up=true
,01-27 16:49:47.212  4974  4989 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
01-27 16:49:47.212  9097  9097 D BluetoothPan: BluetoothPAN Proxy object connected
01-27 16:49:47.212  9097  9097 D PanProfile: Bluetooth service connected
,01-27 16:49:47.222  7012  7527 D BluetoothAdapter: onBluetoothStateChange: up=true
01-27 16:49:47.222  7012  7527 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,01-27 16:49:47.222  3465  3559 D BluetoothA2dp: onBluetoothStateChange: up=true
,01-27 16:49:47.222  3465  3559 D BluetoothA2dp: Binding service...
01-27 16:49:47.222  3465  3559 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,01-27 16:49:47.232  3162  3715 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,01-27 16:49:47.232  3465  3869 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -51]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} } wasDefault=true
,01-27 16:49:47.232  3465  3869 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
01-27 16:49:47.232  3465  3869 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,01-27 16:49:47.272  3950  3950 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 272
,01-27 16:49:47.292  3465  3538 W ProcessCpuTracker: Skipping unknown process pid 9722
01-27 16:49:47.292  3465  3538 D ActivityManager:  getDeferredInfo final delay 300
,01-27 16:49:47.292  3465  3560 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:47.292  3465  3560 I WifiDisplayAdapter: onP2pDisconnected
01-27 16:49:47.292  3465  3560 D IpRemoteDisplayController: disconnectWfdBridgeServer
01-27 16:49:47.292  3465  3560 D IpRemoteDisplayController: WfdBridgeServer is already null
,01-27 16:49:47.292  3950  3950 D WifiP2pController: onReceive android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,01-27 16:49:47.302  3465  3859 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,01-27 16:49:47.302  3465  3465 D BluetoothA2dp: Proxy object connected
,01-27 16:49:47.312  3950  4357 D BluetoothSap: onBluetoothStateChange: up=true
01-27 16:49:47.312  3950  4357 D BluetoothSap: Binding service...
,01-27 16:49:47.312  3465  3535 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,01-27 16:49:47.312  3465  3535 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,01-27 16:49:47.312  3950  4150 D NetworkController: onReceive: intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,01-27 16:49:47.322  3465  3535 D GpsLocationProvider: updateNetworkState unavailable info: [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,01-27 16:49:47.322  4826  4826 D SamsungIME: EngineType = SWIFTKEY
,01-27 16:49:47.322  4990  5088 D CellLocationSupport: onReceive ACTION = android.net.conn.CONNECTIVITY_CHANGE
01-27 16:49:47.322  4990  5088 I CellLocationSupport: onCellLocationChanged
,01-27 16:49:47.332  4826  4826 D SamsungIME: mNetworkChangeReceiver isWLANConnected : false
,01-27 16:49:47.342  4990  4990 D PdnController: CONNECTIVITY_ACTION: networkType 1 isConnected false
01-27 16:49:47.342  4990  4990 D PdnController: isSuspended [false] networktype [1]
,01-27 16:49:47.342  3465  3977 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,01-27 16:49:47.342  4990  4990 D PdnController: isPdnUp  [false] networktype [1]
01-27 16:49:47.342  4990  4990 D PdnController: Notify Result to LocalIP Registrants! : networkType [1] isConnected [false] 
,01-27 16:49:47.342  5287  5287 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@88e74bc and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,01-27 16:49:47.352  3465  4487 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,01-27 16:49:47.352  6759  6759 I FOTA_AGENT: [com.samsung.android.app.syncmldm.XDMService(1060/IIllllIIlIIllIIIIlll)] WiFi network Connected : false
,01-27 16:49:47.352  4990  5088 I CellLocationSupport: Block to update PANI information in non VoWIFI
01-27 16:49:47.352  4990  5088 D SlickSSConfigHandler: EVENT_LOCAL_IP_CHANGED
,01-27 16:49:47.352  4465  4465 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
01-27 16:49:47.352  3465  4059 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,01-27 16:49:47.362  4990  5088 D PdnController: isIfaceDisconnected result [true] networkType [0] interfaceName [null] 
01-27 16:49:47.362  3465  4485 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:47.362  4990  5088 D PdnController: isPdnUp  [false] networktype [0]
01-27 16:49:47.362  3465  3869 D ConnectivityService: setProvNotificationVisibleIntent SIGN_IN visible=false networkType=WIFI extraInfo=null highPriority=false
01-27 16:49:47.362  4990  5088 D SlickSSConfigHandler: handleNetworkStateChange: check isDefaultPDNConnected[false], mReadyForDocFetch[false
01-27 16:49:47.362  3465  3869 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
01-27 16:49:47.362  3162  3715 E Netd    : netlink response contains error (No such file or directory)
01-27 16:49:47.362  3465  3869 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
01-27 16:49:47.362  3465  3869 D ConnectivityService: nai.networkMonitor.doQuit()
01-27 16:49:47.362  3465  3869 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: doQuit - quitNow()
01-27 16:49:47.362  3162  3711 D EnterpriseController: netId is 0
01-27 16:49:47.362  3465  3869 E ConnectivityService: updateNetworkInfo()
01-27 16:49:47.362  3162  3711 D Netd    : getNetworkForDns: using netid 0 for uid 10001
01-27 16:49:47.362  3465  3869 E ConnectivityService: updateNetworkInfo()
,01-27 16:49:47.362  4570  9727 E         : Error communicating to API: https://prod.yana.asideas.de/api/v2/advertising/frequencies/pl
01-27 16:49:47.362  4570  9727 E         : retrofit.RetrofitError: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
01-27 16:49:47.362  4570  9727 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:395)
01-27 16:49:47.362  4570  9727 E         : 	at retrofit.RestAdapter$RestHandler.access$100(RestAdapter.java:220)
01-27 16:49:47.362  4570  9727 E         : 	at retrofit.RestAdapter$RestHandler$1.invoke(RestAdapter.java:265)
01-27 16:49:47.362  4570  9727 E         : 	at retrofit.RxSupport$2.run(RxSupport.java:55)
01-27 16:49:47.362  4570  9727 E         : 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
01-27 16:49:47.362  4570  9727 E         : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
01-27 16:49:47.362  4570  9727 E         : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
01-27 16:49:47.362  4570  9727 E         : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
01-27 16:49:47.362  4570  9727 E         : 	at retrofit.Platform$Android$2$1.run(Platform.java:142)
01-27 16:49:47.362  4570  9727 E         : 	at java.lang.Thread.run(Thread.java:818)
01-27 16:49:47.362  4570  9727 E         : Caused by: java.net.UnknownHostException: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
01-27 16:49:47.362  4570  9727 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:470)
01-27 16:49:47.362  4570  9727 E         : 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
01-27 16:49:47.362  4570  9727 E         : 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
01-27 16:49:47.362  4570  9727 E         : 	at com.squareup.okhttp.internal.Network$1.resolveInetAddresses(Network.java:29)
01-27 16:49:47.362  4570  9727 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:187)
01-27 16:49:47.362  4570  9727 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.nextProxy(RouteSelector.java:156)
01-27 16:49:47.362  4570  9727 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.next(RouteSelector.java:98)
01-27 16:49:47.362  4570  9727 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.createNextConnection(HttpEngine.java:344)
01-27 16:49:47.362  4570  9727 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:327)
01-27 16:49:47.362  4570  9727 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:245)
01-27 16:49:47.362  4570  9727 E         : 	at com.squareup.okhttp.Call.getResponse(Call.java:267)
01-27 16:49:47.362  4570  9727 E         : 	at com.squareup.okhttp.Call$ApplicationInterceptorChain.proceed(Call.java:224)
01-27 16:49:47.362  4570  9727 E         : 	at com.squareup.okhttp.Call.getResponseWithInterceptorChain(Call.java:195)
01-27 16:49:47.362  4570  9727 E         : 	at com.squareup.okhttp.Call.execute(Call.java:79)
01-27 16:49:47.362  4570  9727 E         : 	at retrofit.client.OkClient.execute(OkClient.java:53)
01-27 16:49:47.362  4570  9727 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:326)
01-27 16:49:47.362  4570  9727 E         : 	... 9 more
01-27 16:49:47.362  4570  9727 E         : Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
01-27 16:49:47.362  4570  9727 E         : 	at libcore.io.Posix.android_getaddrinfo(Native Method)
01-27 16:49:47.362  4570  9727 E         : 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
01-27 16:49:47.362  4570  9727 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:451)
01-27 16:49:47.362  4570  9727 E         : 	... 24 more
01-27 16:49:47.362  4570  9727 E         : 
,01-27 16:49:47.362  4570  9727 E         : Unable to fetch advertisement frequency.
01-27 16:49:47.362  4570  9727 E         : retrofit.RetrofitError: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
01-27 16:49:47.362  4570  9727 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:395)
01-27 16:49:47.362  4570  9727 E         : 	at retrofit.RestAdapter$RestHandler.access$100(RestAdapter.java:220)
01-27 16:49:47.362  4570  9727 E         : 	at retrofit.RestAdapter$RestHandler$1.invoke(RestAdapter.java:265)
01-27 16:49:47.362  4570  9727 E         : 	at retrofit.RxSupport$2.run(RxSupport.java:55)
01-27 16:49:47.362  4570  9727 E         : 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
01-27 16:49:47.362  4570  9727 E         : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
01-27 16:49:47.362  4570  9727 E         : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
01-27 16:49:47.362  4570  9727 E         : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
01-27 16:49:47.362  4570  9727 E         : 	at retrofit.Platform$Android$2$1.run(Platform.java:142)
01-27 16:49:47.362  4570  9727 E         : 	at java.lang.Thread.run(Thread.java:818)
01-27 16:49:47.362  4570  9727 E         : Caused by: java.net.UnknownHostException: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
01-27 16:49:47.362  4570  9727 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:470)
01-27 16:49:47.362  4570  9727 E         : 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
01-27 16:49:47.362  4570  9727 E         : 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
01-27 16:49:47.362  4570  9727 E         : 	at com.squareup.okhttp.internal.Network$1.resolveInetAddresses(Network.java:29)
01-27 16:49:47.362  4570  9727 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:187)
01-27 16:49:47.362  4570  9727 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.nextProxy(RouteSelector.java:156)
01-27 16:49:47.362  4570  9727 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.next(RouteSelector.java:98)
01-27 16:49:47.362  4570  9727 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.createNextConnection(HttpEngine.java:344)
01-27 16:49:47.362  4570  9727 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:327)
01-27 16:49:47.362  4570  9727 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:245)
01-27 16:49:47.362  4570  9727 E         : 	at com.squareup.okhttp.Call.getResponse(Call.java:267)
01-27 16:49:47.362  4570  9727 E         : 	at com.squareup.okhttp.Call$ApplicationInterceptorChain.proceed(Call.java:224)
01-27 16:49:47.362  4570  9727 E         : 	at com.squareup.okhttp.Call.getResponseWithInterceptorChain(Call.java:195)
01-27 16:49:47.362  4570  9727 E         : 	at com.squareup.okhttp.Call.execute(Call.java:79)
01-27 16:49:47.362  4570  9727 E         : 	at retrofit.client.OkClient.execute(OkClient.java:53)
01-27 16:49:47.362  4570  9727 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:326)
01-27 16:49:47.362  4570  9727 E         : 	... 9 more
01-27 16:49:47.362  4570  9727 E         : Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
01-27 16:49:47.362  4570  9727 E         : 	at libcore.io.Posix.android_getaddrinfo(Native Method)
01-27 16:49:47.362  4570  9727 E         : 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
01-27 16:49:47.362  4570  9727 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:451)
01-27 16:49:47.362  4570  9727 E         : 	... 24 more
01-27 16:49:47.362  4570  9727 E         : 
,01-27 16:49:47.372  3465  3858 D NtpTrustedTime: currentTimeMillis() cache hit
01-27 16:49:47.372  3465  3858 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
01-27 16:49:47.372  3465  3858 D NtpTrustedTime: currentTimeMillis() cache hit
01-27 16:49:47.372  3465  3858 D NtpTrustedTime: currentTimeMillis() cache hit
01-27 16:49:47.372  3465  3858 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
01-27 16:49:47.372  3465  3858 D NtpTrustedTime: currentTimeMillis() cache hit
,01-27 16:49:47.372  4990  5088 D RegistrationManager: handleMessage(): 5
,01-27 16:49:47.372  3465  4489 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,01-27 16:49:47.382  4990  5088 D PdnController: isIfaceDisconnected result [true] networkType [11] interfaceName [null] 
01-27 16:49:47.382  4990  5088 D PdnController: isPdnUp  [false] networktype [11]
01-27 16:49:47.382  4990  5088 D RegistrationManager: setEPDGIPSecConnected [false]
01-27 16:49:47.382  4990  5088 D RegistrationManager: notifyNetworkState : NetworkType [1] IsConnected [false] IPAddresses [[]] DNSAddresses [[]] 
01-27 16:49:47.382  4990  5088 D RegistrationManager: isEPDGAvailable [false]
01-27 16:49:47.382  4990  5088 D CoreController: setState [DEREGISTERED]
,01-27 16:49:47.382  9588  9588 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,01-27 16:49:47.392  9588  9588 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,01-27 16:49:47.392  3465  3560 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false, mScanRequestedInConnected = false
01-27 16:49:47.392  3465  3560 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
01-27 16:49:47.392  3465  3560 D WifiDisplayController: disconnect
01-27 16:49:47.392  3465  3560 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,01-27 16:49:47.402  9588  9588 D BluetoothAdapter: STATE_ON
,01-27 16:49:47.402  9588  9588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
01-27 16:49:47.402  9588  9588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
01-27 16:49:47.402  9588  9588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
01-27 16:49:47.402  9588  9588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
01-27 16:49:47.402  9588  9588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
01-27 16:49:47.402  9588  9588 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
01-27 16:49:47.402  9588  9588 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
01-27 16:49:47.402  9588  9588 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
01-27 16:49:47.402  9588  9588 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,01-27 16:49:47.402  3465  3538 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{12d4cd8 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4c3b831 9588:com.test.thalitest/u0a74}
,01-27 16:49:47.402  4302  4545 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
01-27 16:49:47.402  4302  4545 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
01-27 16:49:47.402  3465  3859 D SecContentProvider: insert(), uri = 2
01-27 16:49:47.402  3465  3535 D TelephonyManager: getDataEnabled: retVal=true
,01-27 16:49:47.412  3950  3950 D BluetoothSap: Proxy object connected
01-27 16:49:47.412  3465  3859 D WifiP2pService: P2pDisablingState
01-27 16:49:47.412  3950  3950 D SapProfile: Bluetooth service connected
,01-27 16:49:47.412  3465  3859 D WifiP2pService: P2pDisablingState{ what=147458 }
,01-27 16:49:47.412  3465  3859 D WifiP2pService: p2p socket connection lost
,01-27 16:49:47.412  3465  3859 D SecContentProvider: insert(), uri = 2
01-27 16:49:47.412  9588  9588 D BluetoothAdapter: STATE_ON
,01-27 16:49:47.412  4990  5088 D TranslatorCollection: translateToNwkSvcType: networkType XAN_NWK_TYPE_WLAN
01-27 16:49:47.412  4990  5088 D RegistrationManager: getNetworkType [0]
01-27 16:49:47.412  4990  5088 D CoreStackAdaptor2: notifyNetworkState() [1] isConnected [false] nwkSvcType  [XAN_NWK_TYPE_WLAN] nwkInfoType [XAN_SVC_NETWORK_SVCTYPE_WIFI] dedicated   [NONE] 
01-27 16:49:47.412  4990  5088 D TranslatorCollection: translateToNwkSvcType: networkType XAN_NWK_TYPE_WLAN
01-27 16:49:47.412  4990  5088 D CoreStackAdaptor2: ipList =  Null
01-27 16:49:47.412  4990  5088 D RegistrationManager: tryRegister(CONNECTIVITY_STATUS_CHANGE)
01-27 16:49:47.412  4990  5088 D RegistrationManager: isPreconditionProperToGoOn
01-27 16:49:47.412  4990  5088 D RegistrationManager: isDeviceShutdown [false]
01-27 16:49:47.412  4990  5088 D RegistrationManager: isStackShuttingDownForAllPDNs [false]
01-27 16:49:47.422  4990  5088 D RegistrationManager: isDmVoLTEUpdated [false]
01-27 16:49:47.422  4990  5088 D RegistrationManager: tryRegister : Abort Reason [IMS feature disabled]
01-27 16:49:47.422  4990  5088 D RegistrationManager: tryRegister : Not all preconditions are met!
,01-27 16:49:47.422  4302  5231 D TelephonyProvider: query: url=content://telephony/carriers/preferapn, projectionIn=[Ljava.lang.String;@3ff2605, selection=nullselectionArgs=null, sort=name ASC
01-27 16:49:47.422  3465  3860 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
01-27 16:49:47.422  3465  3859 D WifiP2pService: P2pDisabledState
,01-27 16:49:47.422  3162  3715 D CommandListener: Clearing all IP addresses on wlan0
,01-27 16:49:47.422  3465  3560 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
01-27 16:49:47.422  3465  3560 I WifiDisplayAdapter: onP2pDisconnected
01-27 16:49:47.422  3465  3560 D IpRemoteDisplayController: disconnectWfdBridgeServer
01-27 16:49:47.422  3465  3560 D IpRemoteDisplayController: WfdBridgeServer is already null
,01-27 16:49:47.422  3950  3950 D WifiP2pController: onReceive android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,01-27 16:49:47.422  4302  5231 D TelephonyProvider: query: match = 5
01-27 16:49:47.422  4302  5231 D TelephonyProvider: getPreferredApnId(subId = 2147483643),return -1
01-27 16:49:47.422  4302  5231 D TelephonyProvider: query: selection modified to edited!=2 and edited!=3 and edited!=5 and edited!=6
01-27 16:49:47.422  9588  9588 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,01-27 16:49:47.432  3950  3950 D SoundPathController: onReceive - android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,01-27 16:49:47.432  3465  3484 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:47.432  3465  3484 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:47.432  3465  3484 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:47.432  3465  3484 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:47.432  3465  3484 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:47.432  3465  3484 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:47.432  3465  3484 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:47.432  3465  3484 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:47.432  7012  7183 I SQLiteDatabase: can't enable WAL for memory databases.
01-27 16:49:47.432  3465  3484 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:47.432  3465  3484 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:47.432  3465  3484 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:47.432  3465  3484 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
01-27 16:49:47.432  3465  3484 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:47.432  3465  3484 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:47.432  3465  3484 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:47.432  3950  3950 D ApMirroringController: onReceive android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,01-27 16:49:47.432  3465  3973 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
01-27 16:49:47.432  3950  3950 D AllShareCastTile: onReceive : android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
01-27 16:49:47.432  4942  5319 D A2dpStateMachine: getConnectedDevices : size=0
01-27 16:49:47.432  3950  3950 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
01-27 16:49:47.442  3465  3860 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
01-27 16:49:47.442  3465  3465 D Tethering: Tethering got CONNECTIVITY_ACTION
01-27 16:49:47.442  3465  3465 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:47.442  3465  3465 I CLocInfoService: ['16.5] External Intent Received android.net.conn.CONNECTIVITY_CHANGE
01-27 16:49:47.442  3465  3465 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:47.442  3465  3465 I CLocInfoService: CLoinfo wifi false
01-27 16:49:47.442  3465  3465 V MARsPolicyManager: DataConnection: false
01-27 16:49:47.442  3465  3465 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
01-27 16:49:47.442  3465  4204 V AlarmManager:  remove PendingIntent] PendingIntent{6f8715e: PendingIntentRecord{707193f android broadcastIntent}}
01-27 16:49:47.442  3465  9730 I ApplicationPolicy: updateDataUsageMap
01-27 16:49:47.442  4064  4064 I wpa_supplicant: Blacklist: Clear (all) 
,01-27 16:49:47.442  4064  4064 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
,01-27 16:49:47.442  3465  4202 W SLocation: No Active Data Connection
,01-27 16:49:47.442  3465  4202 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:47.442  7012  7183 I SQLiteDatabase: can't enable WAL for memory databases.
01-27 16:49:47.442  3465  3465 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
01-27 16:49:47.442  3465  3465 I InputMethodManagerService: [BT Setting State] State =12
01-27 16:49:47.442  3465  3465 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,01-27 16:49:47.452  3465  3871 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,01-27 16:49:47.452  3465  3559 D EntConnectivity: Not allowed due to - mEnabled false
01-27 16:49:47.452  4302  4545 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
01-27 16:49:47.452  4302  4545 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,01-27 16:49:47.452  3465  3871 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,01-27 16:49:47.492  3162  3708 D Netd    : Iface p2p0 link up
,01-27 16:49:47.492  4990  5002 D PdnController: Interface Changed p2p0 link up
01-27 16:49:47.492  3465  3542 D Tethering: interfaceLinkStateChanged p2p0, true
01-27 16:49:47.492  3465  3542 D Tethering: interfaceStatusChanged p2p0, true
,01-27 16:49:47.512  3950  4150 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,01-27 16:49:47.512  3950  4150 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,01-27 16:49:47.512  4374  4374 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
01-27 16:49:47.512  3465  3465 I Telecom : BluetoothPhoneService: queryPhoneState
01-27 16:49:47.512  3465  3465 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState : true
,01-27 16:49:47.522  4826  4826 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,01-27 16:49:47.522  3465  3465 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
01-27 16:49:47.522  3465  3465 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
01-27 16:49:47.522  3465  3465 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,01-27 16:49:47.522  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
01-27 16:49:47.522  9097  9097 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
01-27 16:49:47.522  9097  9097 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,01-27 16:49:47.532  4064  4064 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,01-27 16:49:47.532  4064  4064 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,01-27 16:49:47.542  9588  9588 D BluetoothAdapter: STATE_ON
,01-27 16:49:47.542  3162  3708 D Netd    : Iface wlan0 link up
,01-27 16:49:47.542  4990  5007 D PdnController: Interface Changed wlan0 link up
,01-27 16:49:47.542  3465  3542 D Tethering: interfaceLinkStateChanged wlan0, true
01-27 16:49:47.542  3465  3542 D Tethering: interfaceStatusChanged wlan0, true
,01-27 16:49:47.542  9588  9588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
01-27 16:49:47.542  9588  9588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
01-27 16:49:47.542  9588  9588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
01-27 16:49:47.542  9588  9588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
01-27 16:49:47.542  9588  9588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
01-27 16:49:47.542  9588  9588 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
01-27 16:49:47.542  9588  9588 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
01-27 16:49:47.542  9588  9588 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
01-27 16:49:47.542  9588  9588 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,01-27 16:49:47.552  9588  9588 D BluetoothAdapter: STATE_ON
,01-27 16:49:47.552  4302  4302 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,01-27 16:49:47.552  9588  9684 D BluetoothAdapter: STATE_ON
,01-27 16:49:47.552  9588  9588 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,01-27 16:49:47.552  9588  9684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
01-27 16:49:47.552  9588  9684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
01-27 16:49:47.552  9588  9684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
01-27 16:49:47.552  9588  9684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
01-27 16:49:47.552  9588  9684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
01-27 16:49:47.552  9588  9684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
01-27 16:49:47.552  9588  9684 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
01-27 16:49:47.552  9588  9684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
01-27 16:49:47.552  9588  9684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,01-27 16:49:47.562  9588  9684 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,01-27 16:49:47.562  9588  9651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,01-27 16:49:47.562  3465  3977 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{12d4cd8 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b3d1f23 3465:system/1000}
,01-27 16:49:47.572  3950  3950 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,01-27 16:49:47.572  3950  3950 I HotspotTile: Provider is not defined returning false
,01-27 16:49:47.572  3950  3950 D HotspotTile: onReceive : 0, 0
,01-27 16:49:47.582  3465  3559 D Tethering: MasterInitialState.processMessage what=3
01-27 16:49:47.582  3465  3535 E GpsLocationProvider: No APN found to select.
,01-27 16:49:47.582  3465  3465 I WifiTrafficPoller: evaluateTrafficStatsPolling
01-27 16:49:47.582  3465  3465 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
,01-27 16:49:47.582  3465  3860 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
01-27 16:49:47.582  3465  3465 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
01-27 16:49:47.582  3465  3465 D HS20StateMachine: [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false]
,01-27 16:49:47.582  3465  3465 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
01-27 16:49:47.582  3465  3867 I WifiHs20Service: Message received 5007
01-27 16:49:47.582  3465  3973 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,01-27 16:49:47.582  9588  9588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
01-27 16:49:47.582  9097  9097 D LocalBluetoothProfileManager: Adding local A2DP profile
,01-27 16:49:47.582  3465  3973 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,01-27 16:49:47.592  3465  3973 D WifiService: setWifiEnabled: true pid=9588, uid=10074
,01-27 16:49:47.592  9097  9097 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,01-27 16:49:47.602  9733  9733 E Zygote  : v2
01-27 16:49:47.602  9733  9733 I libpersona: KNOX_SDCARD checking this for 10049
01-27 16:49:47.602  9733  9733 I libpersona: KNOX_SDCARD not a persona
01-27 16:49:47.602  9733  9733 E Zygote  : isSdpEnabledProcess - SDP enabled
,01-27 16:49:47.602  9733  9733 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,01-27 16:49:47.602  9733  9733 E Zygote  : accessInfo : 64
01-27 16:49:47.602  9733  9733 E Zygote  : isSdpEnabledProcess - SDP enabled
01-27 16:49:47.602  9733  9733 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10049 / [uid]: 10049
,01-27 16:49:47.602  9733  9733 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.email.provider 
,01-27 16:49:47.612  3465  4059 I ActivityManager: Start proc 9733:com.samsung.android.email.provider/u0a49 for content provider com.samsung.android.email.provider/.provider.database.EmailProvider
,01-27 16:49:47.612  3465  4488 V AlarmManager:  remove PendingIntent] PendingIntent{dec42a2: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:47.612  3465  3535 D libgps  : agps_ril_update_network_state: Waiting for IPC connection...
01-27 16:49:47.612  3465  3538 D ActivityManager:  getDeferredInfo final delay 300
,01-27 16:49:47.612  3465  3858 D NetworkPolicy: isUidForegroundLocked: 10049, mScreenOn: true, uidstate: -1, mProxSensorScreenOff: false
,01-27 16:49:47.622  4526  8399 D MdnsClient: Multicast lock held. Releasing
,01-27 16:49:47.632  3950  4150 W LocalBluetoothProfileManager: updateLocalProfiles :: MAP profile was previously added but the UUID is now missing.
,01-27 16:49:47.632  3950  4150 W LocalBluetoothProfileManager: updateLocalProfiles :: PBAP profile was previously added but the UUID is now missing.
01-27 16:49:47.632  3950  4150 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
01-27 16:49:47.632  3950  4150 W LocalBluetoothProfileManager: updateLocalProfiles :: HID profile was previously added but the UUID is now missing.
01-27 16:49:47.632  3950  4150 W LocalBluetoothProfileManager: updateLocalProfiles :: BleAudio profile was created already 
,01-27 16:49:47.632  3465  3465 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{12d4cd8 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cdfcc89 4526:com.google.android.gms/u0a19}
,01-27 16:49:47.632  4526  4526 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,01-27 16:49:47.642  4526  5484 I iu.UploadsManager: num queued entries: 0
01-27 16:49:47.642  4064  4064 I wpa_supplicant: Blacklist: Clear (all) 
01-27 16:49:47.642  4526  5484 I iu.UploadsManager: num updated entries: 0
01-27 16:49:47.642  4064  4064 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
01-27 16:49:47.642  4526  5484 I iu.SyncManager: NEXT; no task
,01-27 16:49:47.642  3465  3465 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
,01-27 16:49:47.642  3465  3465 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
01-27 16:49:47.642  3465  3867 I WifiHs20Service: Message received 5011
01-27 16:49:47.642  3465  3465 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,01-27 16:49:47.642  9588  9588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,01-27 16:49:47.642  3465  3973 W ActivityManager: Permission Denial: getCurrentUser() from pid=9588, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
01-27 16:49:47.642  3465  3973 W WifiService: Failed getting userId using ActivityManagerNative
01-27 16:49:47.642  3465  3973 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9588, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
01-27 16:49:47.642  3465  3973 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
01-27 16:49:47.642  3465  3973 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
01-27 16:49:47.642  3465  3973 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
01-27 16:49:47.642  3465  3973 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
01-27 16:49:47.642  3465  3973 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
01-27 16:49:47.642  3465  3973 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
01-27 16:49:47.642  3465  3860 D WifiBigDataLog: getJsonFormat() - feature : ONOF
01-27 16:49:47.642  3465  3973 D SettingsProvider: isChangeAllowed() : name = wifi_on
01-27 16:49:47.642  3465  3860 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,01-27 16:49:47.652  3465  3863 D WifiStateMachine: setFccChannel: channel = -1
01-27 16:49:47.652  3465  3863 D WifiController: [FCC]setFccChannel() is called !!!
01-27 16:49:47.652  3465  3863 D WifiStateMachine: setFccChannel: channel = -1
,01-27 16:49:47.652  3465  3863 D WifiController: [FCC]Airplane off, setFccChannel(-1)!!!
01-27 16:49:47.652  3465  3863 D SecContentProvider: insert(), uri = 2
,01-27 16:49:47.652  9097  9097 D LocalBluetoothProfileManager: Adding local HEADSET profile
,01-27 16:49:47.652  3465  3465 D WifiNotificationController: SHOW_NOTI_MESSAGE : 17, visible : false, ssid : null, targetSSID : null, netId : -1, titleType : -1
,01-27 16:49:47.652  3465  3465 D WifiNotificationController: showMaliciousHotspotDetectionNotification - MaliciousNetwork:null, visible:false
,01-27 16:49:47.652  9733  9733 D TimaKeyStoreProvider: TimaSignature is unavailable
01-27 16:49:47.652  9733  9733 D ActivityThread: Added TimaKeyStore provider
,01-27 16:49:47.652  9097  9097 E BluetoothHeadset: BTStateChangeCB is registed
,01-27 16:49:47.662  9097  9097 W LocalBluetoothProfileManager: updateLocalProfiles :: MAP profile was previously added but the UUID is now missing.
,01-27 16:49:47.662  9097  9097 W LocalBluetoothProfileManager: updateLocalProfiles :: PBAP profile was previously added but the UUID is now missing.
01-27 16:49:47.662  9097  9097 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
01-27 16:49:47.662  9097  9097 W LocalBluetoothProfileManager: updateLocalProfiles :: HID profile was previously added but the UUID is now missing.
01-27 16:49:47.662  9097  9097 W LocalBluetoothProfileManager: updateLocalProfiles :: BleAudio profile was created already 
01-27 16:49:47.662  3465  3871 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,01-27 16:49:47.662  3465  4416 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{12d4cd8 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cdfcc89 4526:com.google.android.gms/u0a19}
,01-27 16:49:47.672  4302  4545 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,01-27 16:49:47.672  4302  4545 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,01-27 16:49:47.672  3465  3871 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,01-27 16:49:47.672  3465  3858 D NetworkPolicy: isUidForegroundLocked: 10049, mScreenOn: true, uidstate: 16, mProxSensorScreenOff: false
,01-27 16:49:47.682  3465  3483 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{12d4cd8 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fa96432 4239:com.google.android.gms.persistent/u0a19}
,01-27 16:49:47.692  3162  3708 D Netd    : Iface wlan0 link up
01-27 16:49:47.692  3162  3708 D Netd    : Iface wlan0 link up
,01-27 16:49:47.692  4990  5002 D PdnController: Interface Changed wlan0 link up
,01-27 16:49:47.692  3465  3542 D Tethering: interfaceLinkStateChanged wlan0, true
01-27 16:49:47.692  3465  3542 D Tethering: interfaceStatusChanged wlan0, true
01-27 16:49:47.692  4990  5007 D PdnController: Interface Changed wlan0 link up
,01-27 16:49:47.692  3465  3542 D Tethering: interfaceLinkStateChanged wlan0, true
01-27 16:49:47.692  3465  3542 D Tethering: interfaceStatusChanged wlan0, true
,01-27 16:49:47.692  3162  3708 D Netd    : Iface p2p0 link down
,01-27 16:49:47.692  4990  5473 D PdnController: Interface Changed p2p0 link down
,01-27 16:49:47.692  3465  3542 D Tethering: interfaceLinkStateChanged p2p0, false
01-27 16:49:47.692  3465  3542 D Tethering: interfaceStatusChanged p2p0, false
01-27 16:49:47.692  3465  3860 D WifiBigDataLog: init : 
,01-27 16:49:47.702  3465  4382 V AlarmManager:  remove PendingIntent] PendingIntent{c8fa1c: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:47.712  3950  4150 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
01-27 16:49:47.712  3950  4188 D BluetoothTile: handleUpdateState :  supported = true, enabled = true, enabling = false, connected = false, connecting = false, mController.getLastDeviceName() = null
,01-27 16:49:47.712  3950  4150 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
01-27 16:49:47.712  3465  4487 D StatusBarManagerService: setIcon slot=bluetooth index=18 icon=StatusBarIcon(icon=Icon(typ=RESOURCE pkg=com.android.systemui id=0x7f02049a) visible user=0 )
,01-27 16:49:47.712  9097  9097 D BluetoothA2dp: Proxy object connected
01-27 16:49:47.712  3465  4331 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,01-27 16:49:47.722  9097  9097 D A2dpProfile: Bluetooth service connected
,01-27 16:49:47.732  9733  9733 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in com.samsung.android.email.provider rsrc of package com.samsung.android.email.provider
,01-27 16:49:47.732  3465  3538 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{12d4cd8 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{704957e 7358:com.osp.app.signin/u0a41}
,01-27 16:49:47.732  7358  7358 I SA      : [OR] onReceive log=[SA = 2.2.02-12 V = 23 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = pl_PL CSC = XEO MCC = 0 MNC 0 T = user DEVICE = herolte P = heroltexx I = MMB29K M = SM-G930F OKLEFT false DIS MMB29K.G930FXXU1BPJG PSS = 5.059173621445858  ]
,01-27 16:49:47.742  7358  7358 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
01-27 16:49:47.742  3465  4331 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
01-27 16:49:47.742  7358  7358 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
01-27 16:49:47.742  9733  9733 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,01-27 16:49:47.742  9733  9733 D ResourcesManager: For user 0 new overlays fetched Null
,01-27 16:49:47.742  3465  4489 V AlarmManager:  remove PendingIntent] PendingIntent{f6f3625: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:47.752  4942  4960 D A2dpStateMachine: getConnectedDevices : size=0
,01-27 16:49:47.752  3465  3483 V AlarmManager:  remove PendingIntent] PendingIntent{a7783fa: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:47.752  3950  3950 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 272
,01-27 16:49:47.762  9733  9733 I InjectionManager: Inside getClassLibPath caller 
,01-27 16:49:47.762  3465  4226 V AlarmManager:  remove PendingIntent] PendingIntent{c799c08: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:47.772  7358  7358 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
01-27 16:49:47.772  7358  7358 I SA      : [OR] == isSIMCardReady false ==
01-27 16:49:47.772  3465  4403 V AlarmManager:  remove PendingIntent] PendingIntent{3820fa1: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
01-27 16:49:47.772  7358  7358 I SA      : [SCU] == networkStateCheck == false
01-27 16:49:47.772  7358  7358 I SA      : [OR] onReceive END
,01-27 16:49:47.792  3465  3973 V AlarmManager:  remove PendingIntent] PendingIntent{6a9e5c6: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:47.792  9733  9733 W System  : ClassLoader referenced unknown path: /system/priv-app/SecEmail_M/lib/arm64
,01-27 16:49:47.802  3465  3538 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{77d5987 u0 com.google.android.gcm.DISCONNECTED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3655c31 8494:com.google.android.talk/u0a112}
,01-27 16:49:47.802  3465  3484 V AlarmManager:  remove PendingIntent] PendingIntent{71070b4: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:47.812  3465  4487 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{38f04dd u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9f9c89d 9097:com.android.settings/1000}
,01-27 16:49:47.812  9097  9097 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,01-27 16:49:47.822  3465  3973 D RCPManagerService: exchangeData() failure , invalid userId
,01-27 16:49:47.832  3465  4485 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{38f04dd u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{47dcb8b 4974:com.samsung.android.providers.context/u0a7}
,01-27 16:49:47.842  3465  4489 V AlarmManager:  remove PendingIntent] PendingIntent{4c0723: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:47.852  9097  9097 D DockEventReceiver: finishStartingService: stopping service
,01-27 16:49:47.862  3465  4485 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{38f04dd u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fa96432 4239:com.google.android.gms.persistent/u0a19}
,01-27 16:49:47.862  4239  4239 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
,01-27 16:49:47.872  3465  4403 D RCPManagerService: exchangeData() failure , invalid userId
,01-27 16:49:47.882  9733  9733 D InjectionManager: InjectionManager
01-27 16:49:47.882  9733  9733 D InjectionManager: fillFeatureStoreMap com.samsung.android.email.provider
,01-27 16:49:47.882  9733  9733 I InjectionManager: Constructor com.samsung.android.email.provider, Feature store :{}
01-27 16:49:47.882  9733  9733 I InjectionManager: featureStore :{}
,01-27 16:49:47.882  3465  4487 V AlarmManager:  remove PendingIntent] PendingIntent{29de420: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:47.892  3465  4226 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{38f04dd u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{33d4c87 8711:com.sec.android.app.shealth:remote/u0a36}
,01-27 16:49:47.912  9753  9753 E Zygote  : v2
01-27 16:49:47.912  9753  9753 I libpersona: KNOX_SDCARD checking this for 10049
01-27 16:49:47.912  9753  9753 E Zygote  : isSdpEnabledProcess - SDP enabled
01-27 16:49:47.912  9753  9753 I libpersona: KNOX_SDCARD not a persona
,01-27 16:49:47.912  3465  3973 I ActivityManager: Start proc 9753:com.samsung.android.email.provider:service/u0a49 for service com.samsung.android.email.provider/com.samsung.android.email.sync.service.EmailService
01-27 16:49:47.912  9753  9753 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,01-27 16:49:47.922  9753  9753 E Zygote  : accessInfo : 64
01-27 16:49:47.922  9753  9753 E Zygote  : isSdpEnabledProcess - SDP enabled
01-27 16:49:47.922  9753  9753 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10049 / [uid]: 10049
01-27 16:49:47.922  9753  9753 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.email.provider:service 
,01-27 16:49:47.922  3465  4226 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{38f04dd u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9f9c89d 9097:com.android.settings/1000}
,01-27 16:49:47.922  9097  9097 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
01-27 16:49:47.932  9097  9097 D BluetoothStatusReceiver: AdapterStateChanged :: state = 12
,01-27 16:49:47.932  4942  4942 D BleAudioService: onReceive:: INTENT mAobleStateChangeListener got : android.bluetooth.adapter.action.STATE_CHANGED
01-27 16:49:47.932  4942  4942 D BleAudioService: BluetoothAdapter.ACTION_STATE_CHANGED,  state is12
01-27 16:49:47.932  4942  9704 D BleAudioStateMachine_L: [Disconnected] Disconnected process message: 41
01-27 16:49:47.932  4942  9704 D BleAudioStateMachine_L: [Disconnected] MSG_ADAPTER_BT_ON_EVT event received
01-27 16:49:47.932  4942  9705 D BleAudioStateMachine_R: [Disconnected] Disconnected process message: 41
01-27 16:49:47.932  4942  9705 D BleAudioStateMachine_R: [Disconnected] MSG_ADAPTER_BT_ON_EVT event received
01-27 16:49:47.932  3465  3538 D ActivityManager:  getDeferredInfo final delay 300
,01-27 16:49:47.942  4942  9704 D BleAudioStateMachine: getLastConnectedDeviceAddress() for channel = 1
01-27 16:49:47.942  4942  9704 D BleAudioService: NotifyEvents: n : 0
,01-27 16:49:47.942  4942  9705 D BleAudioStateMachine: getLastConnectedDeviceAddress() for channel = 2
01-27 16:49:47.942  3465  4331 V AlarmManager:  remove PendingIntent] PendingIntent{97c11d9: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
01-27 16:49:47.942  4942  9705 D BleAudioService: NotifyEvents: n : 0
01-27 16:49:47.942  3950  3950 D HeadsetProfile: Bluetooth service connected
,01-27 16:49:47.952  9097  9097 D HeadsetProfile: Bluetooth service connected
,01-27 16:49:47.962  3465  4382 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{38f04dd u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cc5b0ad 4942:com.android.bluetooth/1002}
,01-27 16:49:47.972  3465  3465 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@e19e79e
01-27 16:49:47.972  3465  3465 D BluetoothHeadset: registerMessageListener
,01-27 16:49:47.972  9753  9753 D TimaKeyStoreProvider: TimaSignature is unavailable
01-27 16:49:47.972  9753  9753 D ActivityThread: Added TimaKeyStore provider
,01-27 16:49:47.972  3465  4487 I ActivityManager: Killing 8795:com.samsung.android.app.aodservice:settingui/u0a0 (adj 15): DHA:empty #33
,01-27 16:49:47.982  4942  5319 D HeadsetService: registerMessageListener
,01-27 16:49:47.982  4942  5319 D HeadsetService: registerMessageListener
01-27 16:49:47.982  4942  9696 D HeadsetStateMachine: Disconnected process message: 70, size: 0
01-27 16:49:47.982  4942  9696 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@b5b597b
,01-27 16:49:47.982  3465  3465 I Telecom : BluetoothManager : register MessageListener
01-27 16:49:47.982  3465  3465 I Telecom : CallAudioManager: onBluetoothStateChange: no focus
,01-27 16:49:47.992  3465  4487 V AlarmManager:  remove PendingIntent] PendingIntent{7cdf27f: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:47.992  4942  4942 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2) for masId0
,01-27 16:49:48.002  4942  4966 D A2dpStateMachine: getConnectedDevices : size=0
,01-27 16:49:48.012  3465  4382 D ActivityManager: cleanUpApplicationRecord -- 8795
,01-27 16:49:48.012  4942  9768 D BluetoothSocket: bindListen(): myUserId = 0
01-27 16:49:48.012  4942  9768 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
01-27 16:49:48.012  3465  4382 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.aodservice, Auto Run ON
,01-27 16:49:48.012  4942  4942 D BluetoothSocket: bindListen(): myUserId = 0
,01-27 16:49:48.012  4942  4942 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,01-27 16:49:48.022  9753  9753 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in com.samsung.android.email.provider rsrc of package com.samsung.android.email.provider
,01-27 16:49:48.022  3465  4485 V AlarmManager:  remove PendingIntent] PendingIntent{d92f295: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:48.022  4942  9768 D BluetoothSdpJni: sdpCreateSapsRecordNative:
01-27 16:49:48.022  4942  9768 D BluetoothSdpJni: SDP Create record success - handle: 0
,01-27 16:49:48.022  3465  4487 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,01-27 16:49:48.022  9753  9753 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,01-27 16:49:48.032  4942  4942 D BluetoothSocket: bindListen(): myUserId = 0
01-27 16:49:48.032  4942  4942 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
01-27 16:49:48.032  9753  9753 D ResourcesManager: For user 0 new overlays fetched Null
,01-27 16:49:48.032  3465  3484 V AlarmManager:  remove PendingIntent] PendingIntent{1b8dfaa: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:48.032  4942  4942 D ObexServerSockets: Succeed to create listening sockets 
01-27 16:49:48.032  4942  4942 D ObexServerSockets: startAccept()
,01-27 16:49:48.032  4942  9770 D ObexServerSockets: Accepting socket connection for masId0
,01-27 16:49:48.032  9753  9753 I InjectionManager: Inside getClassLibPath caller 
,01-27 16:49:48.042  4942  9771 D ObexServerSockets: Accepting socket connection for masId0
,01-27 16:49:48.042  4942  4942 D BluetoothMapMasInstance: set MAP SDP message type : 1
01-27 16:49:48.042  4942  4942 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,01-27 16:49:48.042  4942  4942 D BluetoothSdpJni: SDP Create record success - handle: 1
,01-27 16:49:48.042  4942  4942 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5548134
01-27 16:49:48.042  4942  4942 D BtConfig.SecureMode: isSecureModeOn:false
,01-27 16:49:48.052  9772  9772 E Zygote  : v2
01-27 16:49:48.052  9772  9772 I libpersona: KNOX_SDCARD checking this for 10003
01-27 16:49:48.052  9772  9772 I libpersona: KNOX_SDCARD not a persona
,01-27 16:49:48.052  9772  9772 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,01-27 16:49:48.052  9772  9772 E Zygote  : accessInfo : 0
,01-27 16:49:48.052  9772  9772 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.provider.badge 
,01-27 16:49:48.052  3465  4331 I ActivityManager: Start proc 9772:com.sec.android.provider.badge/u0a3 for content provider com.sec.android.provider.badge/.BadgeProvider
,01-27 16:49:48.062  9753  9753 W System  : ClassLoader referenced unknown path: /system/priv-app/SecEmail_M/lib/arm64
,01-27 16:49:48.062  3465  4382 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{38f04dd u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9f3bf76 7012:com.google.android.apps.maps/u0a119}
,01-27 16:49:48.072  3465  4403 V AlarmManager:  remove PendingIntent] PendingIntent{759379b: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:48.082  3465  3538 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cd01738 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e533db5 6432:com.enhance.gameservice/u0a106}
,01-27 16:49:48.082  9772  9772 D TimaKeyStoreProvider: TimaSignature is unavailable
01-27 16:49:48.082  9772  9772 D ActivityThread: Added TimaKeyStore provider
,01-27 16:49:48.092  4942  9784 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,01-27 16:49:48.092  4942  9784 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,01-27 16:49:48.112  3465  3538 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8fd2311 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4c3b831 9588:com.test.thalitest/u0a74}
,01-27 16:49:48.112  3465  4416 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:48.112  3465  4416 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:48.112  3465  4416 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:48.112  3465  4416 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:48.112  3465  4416 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:48.112  3465  4416 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:48.112  3465  4416 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,01-27 16:49:48.112  3465  4416 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:48.112  3465  4416 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,01-27 16:49:48.112  3465  4416 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:48.112  3465  4416 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:48.112  3465  4416 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
,01-27 16:49:48.112  3465  4416 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:48.112  3465  4416 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:48.112  3465  4416 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:48.112  3465  4042 I ActivityManager: Killing 8019:com.samsung.android.coreapps/5011 (adj 15): DHA:empty #33
,01-27 16:49:48.122  9753  9753 I BNRClientProivder, VERSION : 1.7.5: register - xml6 quick_backup : Email, QJ5JBlRnP9, com.samsung.android.email.provider.service.sCloudBNRService
,01-27 16:49:48.122  9753  9753 I QBNRClientHelper: init SyncClientHelper : Email
,01-27 16:49:48.132  9772  9772 W ResourcesManager: getTopLevelResources: /system/priv-app/BadgeProvider_M/BadgeProvider_M.apk / 1.0 running in com.sec.android.provider.badge rsrc of package com.sec.android.provider.badge
,01-27 16:49:48.132  9772  9772 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,01-27 16:49:48.132  3465  4226 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,01-27 16:49:48.132  9772  9772 D ResourcesManager: For user 0 new overlays fetched Null
,01-27 16:49:48.132  3465  3538 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{49d4c76 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{47dcb8b 4974:com.samsung.android.providers.context/u0a7}
,01-27 16:49:48.142  3465  3977 V AlarmManager:  remove PendingIntent] PendingIntent{d89b277: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:48.142  3465  4403 D ActivityManager: cleanUpApplicationRecord -- 8019
,01-27 16:49:48.142  3465  4403 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.coreapps, Auto Run ON
,01-27 16:49:48.142  9772  9772 I InjectionManager: Inside getClassLibPath caller 
,01-27 16:49:48.152  9772  9772 W System  : ClassLoader referenced unknown path: /system/priv-app/BadgeProvider_M/lib/arm64
,01-27 16:49:48.152  9588  9684 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,01-27 16:49:48.152  3465  4226 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,01-27 16:49:48.152  9772  9772 D BadgeProvider: onCreate
01-27 16:49:48.152  9772  9772 D BadgeProvider: DatabaseHelper
01-27 16:49:48.152  3465  4226 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,01-27 16:49:48.162  3465  4226 D WifiService: setWifiEnabled: true pid=9588, uid=10074
,01-27 16:49:48.162  3465  4226 W ActivityManager: Permission Denial: getCurrentUser() from pid=9588, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
,01-27 16:49:48.162  3465  4226 W WifiService: Failed getting userId using ActivityManagerNative
01-27 16:49:48.162  3465  4226 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9588, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
01-27 16:49:48.162  3465  4226 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
01-27 16:49:48.162  3465  4226 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
01-27 16:49:48.162  3465  4226 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
01-27 16:49:48.162  3465  4226 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
01-27 16:49:48.162  3465  4226 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
01-27 16:49:48.172  3465  4226 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
,01-27 16:49:48.172  3465  4226 D SettingsProvider: isChangeAllowed() : name = wifi_on
01-27 16:49:48.172  3465  3860 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,01-27 16:49:48.172  3465  3860 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
01-27 16:49:48.172  3465  3863 D WifiStateMachine: setFccChannel: channel = -1
,01-27 16:49:48.172  3465  3863 D WifiController: [FCC]setFccChannel() is called !!!
01-27 16:49:48.172  3465  3860 D WifiBigDataLog: init : 
,01-27 16:49:48.172  3465  3863 D WifiController: [FCC]Airplane off, setFccChannel(-1)!!!
,01-27 16:49:48.172  9772  9772 D InjectionManager: InjectionManager
,01-27 16:49:48.172  9772  9772 D InjectionManager: fillFeatureStoreMap com.sec.android.provider.badge
,01-27 16:49:48.182  3465  3538 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{70b6ee4 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{47dcb8b 4974:com.samsung.android.providers.context/u0a7}
,01-27 16:49:48.182  9772  9772 I InjectionManager: Constructor com.sec.android.provider.badge, Feature store :{}
,01-27 16:49:48.182  9772  9772 I InjectionManager: featureStore :{}
,01-27 16:49:48.182  3465  4059 V AlarmManager:  remove PendingIntent] PendingIntent{3ffdf4d: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:48.192  3465  3973 V AlarmManager:  remove PendingIntent] PendingIntent{c89ba02: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:48.192  3465  4331 V AlarmManager:  remove PendingIntent] PendingIntent{cdcff13: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:48.202  3465  4059 V AlarmManager:  remove PendingIntent] PendingIntent{b829550: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:48.202  3465  4489 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1248000  uid : 1000  pid : 3465  pkgName : BADGE_UPDATE@CPU_MIN@1
,01-27 16:49:48.212  3465  4331 V AlarmManager:  remove PendingIntent] PendingIntent{bf82349: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:48.222  3465  4403 D RCPManagerService: exchangeData() failure , invalid userId
,01-27 16:49:48.222  3465  4226 V AlarmManager:  remove PendingIntent] PendingIntent{6dd744e: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:48.222  9753  9753 D InjectionManager: InjectionManager
01-27 16:49:48.222  9753  9753 D InjectionManager: fillFeatureStoreMap com.samsung.android.email.provider
,01-27 16:49:48.222  9753  9753 I InjectionManager: Constructor com.samsung.android.email.provider, Feature store :{}
01-27 16:49:48.222  3465  4382 V AlarmManager:  remove PendingIntent] PendingIntent{80e796f: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
01-27 16:49:48.222  9753  9753 I InjectionManager: featureStore :{}
,01-27 16:49:48.232  3162  3708 D Netd    : Iface wlan0 link down
,01-27 16:49:48.232  9772  9782 D BaseReflect: null getOwnClass TEST
01-27 16:49:48.232  9772  9782 D MethodReflector: android.content.ContentResolver getClass TEST
01-27 16:49:48.232  9772  9782 D BaseReflect: class android.content.ContentResolver isSupportClass TEST
01-27 16:49:48.232  9772  9782 D BaseReflect: class android.content.ContentResolver getOwnClass TEST
,01-27 16:49:48.232  4990  5007 D PdnController: Interface Changed wlan0 link down
01-27 16:49:48.232  4990  5007 D PdnController: Removed Interface [wlan0] For Network [1]
01-27 16:49:48.232  3465  3542 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,01-27 16:49:48.232  3465  6030 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:48.232  3465  4485 V AlarmManager:  remove PendingIntent] PendingIntent{203b67c: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:48.242  4990  5007 D PdnController: CONNECTIVITY_ACTION: networkType 1 isConnected false
01-27 16:49:48.242  4990  5007 D PdnController: isSuspended [false] networktype [1]
,01-27 16:49:48.242  3465  3542 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,01-27 16:49:48.242  4990  5007 D PdnController: isPdnUp  [false] networktype [1]
01-27 16:49:48.242  4990  5007 D PdnController: Ignore Notifying Same Result to LocalIP Registrants!
,01-27 16:49:48.242  3465  3542 D Tethering: interfaceLinkStateChanged wlan0, false
01-27 16:49:48.242  3465  3542 D Tethering: interfaceStatusChanged wlan0, false
,01-27 16:49:48.272  3465  3538 D ActivityManager:  getDeferredInfo final delay 300
,01-27 16:49:48.272  4314  4314 D Launcher.Model: reloadBadges entered.
,01-27 16:49:48.272  9772  9782 D MethodReflector: notifyChange is called
,01-27 16:49:48.272  3465  4331 V AlarmManager:  remove PendingIntent] PendingIntent{d16ab05: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
01-27 16:49:48.282  4064  4064 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,01-27 16:49:48.282  4314  4314 D Launcher.Model: reloadBadges entered.
,01-27 16:49:48.282  9772  9783 D BadgeProvider: query, [selection] : null
,01-27 16:49:48.282  3465  4225 V AlarmManager:  remove PendingIntent] PendingIntent{5a0875a: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:48.292  4314  4421 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.email.provider = 0
,01-27 16:49:48.292  4314  4421 D BadgeCache: 1. updateBadgeCounts: com.android.mms = 0
01-27 16:49:48.292  4314  4421 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 1
01-27 16:49:48.292  4314  4421 D BadgeCache: 2. updateBadgeCounts: com.android.settings/.Settings = 1
01-27 16:49:48.292  4314  4421 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 1
01-27 16:49:48.292  4314  4421 D BadgeCache: 2. updateBadgeCounts: com.android.settings/.GridSettings = 1
01-27 16:49:48.292  4314  4421 D BadgeCache: 1. updateBadgeCounts: com.sec.android.app.samsungapps = 0
01-27 16:49:48.292  4314  4421 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.sm = 0
01-27 16:49:48.292  9772  9782 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
01-27 16:49:48.292  9772  9782 D BadgeProvider: sendNotify, [notify] : null
,01-27 16:49:48.292  9772  9782 D BadgeProvider: update, getCallingPackage() : com.samsung.android.email.provider
01-27 16:49:48.292  9772  9782 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
01-27 16:49:48.292  9772  9782 D BadgeProvider: update, [uri.query] : null
,01-27 16:49:48.292  9772  9782 D BadgeProvider: update, [BadgeCount] : badgecount=0
01-27 16:49:48.292  9772  9782 D BadgeProvider: update, [UpdateCount] : 1
01-27 16:49:48.292  3465  4059 V AlarmManager:  remove PendingIntent] PendingIntent{8333d8b: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:48.302  3465  4226 V AlarmManager:  remove PendingIntent] PendingIntent{8962767: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:48.302  9772  9789 D BadgeProvider: query, [selection] : null
,01-27 16:49:48.312  4314  4421 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.email.provider = 0
01-27 16:49:48.312  3465  3484 V AlarmManager:  remove PendingIntent] PendingIntent{89a5914: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
01-27 16:49:48.312  4314  4421 D BadgeCache: 1. updateBadgeCounts: com.android.mms = 0
01-27 16:49:48.312  4314  4421 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 1
01-27 16:49:48.312  4314  4421 D BadgeCache: 2. updateBadgeCounts: com.android.settings/.Settings = 1
01-27 16:49:48.312  4314  4421 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 1
01-27 16:49:48.312  4314  4421 D BadgeCache: 2. updateBadgeCounts: com.android.settings/.GridSettings = 1
01-27 16:49:48.312  4314  4421 D BadgeCache: 1. updateBadgeCounts: com.sec.android.app.samsungapps = 0
01-27 16:49:48.312  4314  4421 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.sm = 0
,01-27 16:49:48.322  3465  3483 V AlarmManager:  remove PendingIntent] PendingIntent{a5435bd: PendingIntentRecord{cf6eb0b com.android.bluetooth broadcastIntent}}
,01-27 16:49:48.332  3465  3973 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:48.332  3465  3973 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:48.332  3465  3973 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:48.332  3465  3973 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:48.332  3465  3973 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:48.332  3465  3973 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:48.332  3465  3973 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:48.332  3465  3973 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:48.332  3465  3973 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:48.332  3465  3973 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:48.332  3465  3973 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:48.332  3465  3973 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
01-27 16:49:48.332  3465  3973 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:48.332  3465  3973 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:48.332  3465  3973 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,01-27 16:49:48.382  3465  3860 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,01-27 16:49:48.382  3465  3465 D WifiNotificationController: SHOW_NOTI_MESSAGE : 9, visible : false, ssid : <unknown ssid>, targetSSID : null, netId : -1, titleType : -1
,01-27 16:49:48.382  3465  3465 D WifiNotificationController: SHOW_NOTI_MESSAGE : 13, visible : false, ssid : <unknown ssid>, targetSSID : null, netId : -1, titleType : 0
01-27 16:49:48.382  3465  3465 D WifiNotificationController: showCaptivePortalDisabledStatus with ssid/visible/title:null/false/0
,01-27 16:49:48.382  3465  3465 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
01-27 16:49:48.382  3465  3465 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
,01-27 16:49:48.382  3465  3864 D HS20StateMachine: WIFI_STATE_DISABLED
01-27 16:49:48.382  3465  3867 I WifiHs20Service: Message received 5011
01-27 16:49:48.382  3465  3864 D HS20StateMachine: CMD_HOTSPOT20_DISABLE
01-27 16:49:48.382  3465  3864 D HS20StateMachine: enter : DisablingState
01-27 16:49:48.392  3465  3866 D HS20SubscriptionManager: Received CMD_RELEASE_TLS, flag=1
01-27 16:49:48.392  3465  3864 D HS20StateMachine: enter : DisabledState
,01-27 16:49:48.392  3950  4150 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,01-27 16:49:48.392  3465  3465 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
01-27 16:49:48.392  3465  3871 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,01-27 16:49:48.392  3950  3950 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
01-27 16:49:48.392  3950  3950 I HotspotTile: Provider is not defined returning false
,01-27 16:49:48.392  3950  3950 D HotspotTile: onReceive : 1, 0
,01-27 16:49:48.392  4302  4312 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
01-27 16:49:48.392  4302  4312 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
01-27 16:49:48.392  3465  3871 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,01-27 16:49:48.402  4239  5192 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,01-27 16:49:48.402  9588  9588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,01-27 16:49:48.402  3465  3538 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b68a7b2 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4c3b831 9588:com.test.thalitest/u0a74}
,01-27 16:49:48.402  3465  4042 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:48.402  3465  4042 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:48.402  3465  4042 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:48.402  3465  4042 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,01-27 16:49:48.402  3465  4042 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:48.402  3465  4042 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:48.402  3465  4042 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:48.402  3465  4042 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:48.402  3465  4042 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:48.402  3465  4042 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:48.402  3465  4042 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:48.402  3465  4042 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
01-27 16:49:48.402  3465  4042 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:48.402  3465  4042 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:48.402  3465  4042 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,01-27 16:49:48.572  3465  3538 D ActivityManager:  getDeferredInfo final delay 0
,01-27 16:49:48.582  3465  3860 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,01-27 16:49:48.582  9792  9792 E Zygote  : v2
01-27 16:49:48.582  9792  9792 I libpersona: KNOX_SDCARD checking this for 1000
01-27 16:49:48.582  9792  9792 I libpersona: KNOX_SDCARD not a persona
01-27 16:49:48.582  9792  9792 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
01-27 16:49:48.582  3465  3860 D SettingsProvider: isChangeAllowed() : name = wifi_country_code
,01-27 16:49:48.592  3465  3860 E WifiStateMachine: Error! unhandled message{ when=-3m34s690ms what=131156 target=com.android.internal.util.StateMachine$SmHandler }
01-27 16:49:48.592  9792  9792 E Zygote  : accessInfo : 0
01-27 16:49:48.592  3465  3860 E WifiHW  : ##################### set firmware type 0 #####################
,01-27 16:49:48.592  3465  3538 I ActivityManager: Start proc 9792:com.sec.android.diagmonagent/1000 for broadcast-5 com.sec.android.diagmonagent/.DiagMonConnectivityChangeReciever
,01-27 16:49:48.592  3162  3715 I WifiHW  : wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
,01-27 16:49:48.592  3162  3715 I WifiHW  : module is semco
01-27 16:49:48.592  3162  3715 E WifiHW  : ==========[WIFI] SEMCO MODULE ===========
01-27 16:49:48.592  3162  3715 I WifiHW  : wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
01-27 16:49:48.592  3162  3715 E WifiHW  : TEMP_FAILURE_RETRY complete
01-27 16:49:48.592  3162  3715 D SoftapController: Softap fwReload - Ok
,01-27 16:49:48.602  3162  3715 D CommandListener: Setting iface cfg
01-27 16:49:48.602  3162  3715 D CommandListener: Trying to bring down wlan0
,01-27 16:49:48.602  3162  3715 D CommandListener: Clearing all IP addresses on wlan0
,01-27 16:49:48.602  3465  3860 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,01-27 16:49:48.602  3465  3860 D wifi    : Can not initialize the vendor function pointer table
01-27 16:49:48.602  3465  3860 E WifiNative-HAL: Could not start hal
01-27 16:49:48.602  3465  3860 E WifiStateMachine: Failed to start HAL
,01-27 16:49:48.612  3465  3860 E WifiHW  : supplicant_name : p2p_supplicant
,01-27 16:49:48.612  3465  3973 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
01-27 16:49:48.612  3465  3973 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4335, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
01-27 16:49:48.612  3465  3973 D BatteryService: online:4, current avg:36, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:153
01-27 16:49:48.612  3465  3465 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,01-27 16:49:48.622  9792  9792 D TimaKeyStoreProvider: TimaSignature is unavailable
,01-27 16:49:48.622  3465  3465 I MotionRecognitionService: Plugged
01-27 16:49:48.622  9792  9792 D ActivityThread: Added TimaKeyStore provider
01-27 16:49:48.622  3465  3465 D MotionRecognitionService:   cableConnection= 1
01-27 16:49:48.622  3465  3535 D libgps  : agps_ril_update_network_state: Waiting for IPC connection - timeout
01-27 16:49:48.622  3465  3465 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
01-27 16:49:48.622  3465  3535 E libgps  : LIBGPS: Cannot communicate (write) with a GPSD
01-27 16:49:48.622  3465  3465 D MotionRecognitionService: skip setTransmitPower. 
01-27 16:49:48.622  3465  3535 E libgps  : IPC Communication Error, ../../../../tmp/14982990_270314/allPartners/os/android/gps_interface/gpsi_client/GpsiClient.cpp:1710 agps_ril_update_network_state
01-27 16:49:48.622  3465  3535 D libgps  : agps_ril_update_network_availability: Waiting for IPC connection...
01-27 16:49:48.622  3465  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,01-27 16:49:48.622  3950  3950 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,01-27 16:49:48.622  3950  3950 D KeyguardUpdateMonitor: handleBatteryUpdate
,01-27 16:49:48.622  3950  3950 D PowerUI : priorPlugType = 2 mPlugType =  2
,01-27 16:49:48.632  3950  3950 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
01-27 16:49:48.632  3950  3950 D PowerUI.Notification: There is no change about charging status, so return!
,01-27 16:49:48.632  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
01-27 16:49:48.632  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,01-27 16:49:48.632  4990  4990 D CommonServiceConfiguration: getStringValueSetting
,01-27 16:49:48.642  4942  4942 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,01-27 16:49:48.642  4942  9696 D HeadsetStateMachine: Disconnected process message: 10, size: 0
01-27 16:49:48.642  4990  4990 D BatteryMonitor: new battery level: 100
,01-27 16:49:48.642  3465  4487 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{bdfab43 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{453d303 9792:com.sec.android.diagmonagent/1000}
,01-27 16:49:48.652  9792  9792 W ResourcesManager: getTopLevelResources: /system/priv-app/DiagMonAgent/DiagMonAgent.apk / 1.0 running in com.sec.android.diagmonagent rsrc of package com.sec.android.diagmonagent
,01-27 16:49:48.652  3465  4416 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,01-27 16:49:48.652  9792  9792 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,01-27 16:49:48.662  9792  9792 D ResourcesManager: For user 0 new overlays fetched Null
,01-27 16:49:48.662  9792  9792 I InjectionManager: Inside getClassLibPath caller 
,01-27 16:49:48.672  9792  9792 W System  : ClassLoader referenced unknown path: /system/priv-app/DiagMonAgent/lib/arm64
,01-27 16:49:48.672  9588  9684 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,01-27 16:49:48.672  3465  3484 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,01-27 16:49:48.672  3465  3484 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,01-27 16:49:48.672  3465  3484 D WifiService: setWifiEnabled: true pid=9588, uid=10074
01-27 16:49:48.672  3465  3484 W ActivityManager: Permission Denial: getCurrentUser() from pid=9588, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
,01-27 16:49:48.672  3465  3484 W WifiService: Failed getting userId using ActivityManagerNative
01-27 16:49:48.672  3465  3484 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9588, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
01-27 16:49:48.672  3465  3484 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
01-27 16:49:48.672  3465  3484 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
01-27 16:49:48.672  3465  3484 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
01-27 16:49:48.672  3465  3484 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
01-27 16:49:48.672  3465  3484 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
01-27 16:49:48.672  3465  3484 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
01-27 16:49:48.672  3465  3484 D SettingsProvider: isChangeAllowed() : name = wifi_on
,01-27 16:49:48.672  3465  3863 D WifiStateMachine: setFccChannel: channel = -1
,01-27 16:49:48.672  3465  3863 D WifiController: [FCC]setFccChannel() is called !!!
01-27 16:49:48.672  3465  3863 D WifiController: [FCC]Airplane off, setFccChannel(-1)!!!
01-27 16:49:48.682  3465  3863 E WifiController: illegal state found both WifiController and WifiStateMachine
,01-27 16:49:48.682  9792  9792 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,01-27 16:49:48.712  3465  4403 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,01-27 16:49:48.712  3465  4403 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4329, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
01-27 16:49:48.712  3465  4403 D BatteryService: online:4, current avg:34, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-68
01-27 16:49:48.712  3465  3465 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,01-27 16:49:48.712  3465  3465 I MotionRecognitionService: Plugged
01-27 16:49:48.712  3465  3465 D MotionRecognitionService:   cableConnection= 1
01-27 16:49:48.712  3465  3465 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
01-27 16:49:48.712  3465  3465 D MotionRecognitionService: skip setTransmitPower. 
,01-27 16:49:48.712  3465  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,01-27 16:49:48.712  3950  3950 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
01-27 16:49:48.712  3950  3950 D PowerUI : priorPlugType = 2 mPlugType =  2
,01-27 16:49:48.712  3950  3950 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
01-27 16:49:48.712  3950  3950 D PowerUI.Notification: There is no change about charging status, so return!
,01-27 16:49:48.722  3950  3950 D KeyguardUpdateMonitor: handleBatteryUpdate
,01-27 16:49:48.722  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
01-27 16:49:48.722  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,01-27 16:49:48.722  4990  4990 D CommonServiceConfiguration: getStringValueSetting
,01-27 16:49:48.732  4942  4942 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,01-27 16:49:48.732  4942  9696 D HeadsetStateMachine: Disconnected process message: 10, size: 0
01-27 16:49:48.732  3465  3860 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
01-27 16:49:48.732  4990  4990 D BatteryMonitor: new battery level: 100
,01-27 16:49:48.732  3465  3465 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
,01-27 16:49:48.732  3465  3465 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
01-27 16:49:48.732  3465  3867 I WifiHs20Service: Message received 5011
,01-27 16:49:48.732  3465  3465 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,01-27 16:49:48.732  3950  3950 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
01-27 16:49:48.732  3465  3871 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
01-27 16:49:48.732  3950  3950 I HotspotTile: Provider is not defined returning false
,01-27 16:49:48.732  3950  4150 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,01-27 16:49:48.742  3950  3950 D HotspotTile: onReceive : 2, 0
,01-27 16:49:48.742  4302  4312 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
01-27 16:49:48.742  4302  4312 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,01-27 16:49:48.742  3465  3871 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,01-27 16:49:48.752  9588  9588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,01-27 16:49:48.752  3465  3538 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{94df280 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4c3b831 9588:com.test.thalitest/u0a74}
,01-27 16:49:48.752  3465  3484 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:48.752  3465  3484 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:48.752  3465  3484 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:48.752  3465  3484 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:48.752  3465  3484 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,01-27 16:49:48.752  3465  3484 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:48.752  3465  3484 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:48.752  3465  3484 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:48.752  3465  3484 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:48.752  3465  3484 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:48.752  3465  3484 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:48.752  3465  3484 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
,01-27 16:49:48.752  3465  3484 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:48.752  3465  3484 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,01-27 16:49:48.752  3465  3484 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,01-27 16:49:48.772  9792  9792 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,01-27 16:49:48.782  9804  9804 I FIPS_bssl: FIPS approved mode (1) | 9804 | /system/bin/wpa_supplicant
,01-27 16:49:48.782  9792  9792 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(72/onCreate)] DiagMon DM Application Start !
01-27 16:49:48.782  9792  9792 D InjectionManager: InjectionManager
,01-27 16:49:48.782  9792  9792 D InjectionManager: fillFeatureStoreMap com.sec.android.diagmonagent
01-27 16:49:48.782  9792  9792 I InjectionManager: Constructor com.sec.android.diagmonagent, Feature store :{}
01-27 16:49:48.782  9792  9792 I InjectionManager: featureStore :{}
,01-27 16:49:48.782  9792  9792 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,01-27 16:49:48.782  9804  9804 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
01-27 16:49:48.782  9804  9804 I wpa_supplicant: Successfully initialized wpa_supplicant
,01-27 16:49:48.782  9804  9804 I wpa_supplicant: set_csc_config : ifname(wlan0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x20000), vendorssid_list()
01-27 16:49:48.782  9804  9804 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
01-27 16:49:48.782  9792  9792 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
01-27 16:49:48.782  9792  9792 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
01-27 16:49:48.782  9792  9792 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
01-27 16:49:48.782  3465  3973 D ActivityManager:  getDeferredInfo final delay 0
,01-27 16:49:48.802  9808  9808 E Zygote  : v2
01-27 16:49:48.802  9808  9808 I libpersona: KNOX_SDCARD checking this for 1000
01-27 16:49:48.802  9808  9808 I libpersona: KNOX_SDCARD not a persona
,01-27 16:49:48.802  9808  9808 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,01-27 16:49:48.802  3465  3973 I ActivityManager: Start proc 9808:com.sec.knox.switcher/1000 for broadcast-5 com.sec.knox.switcher/.knoxusage.KnoxUsageReceiver
01-27 16:49:48.802  9808  9808 E Zygote  : accessInfo : 0
01-27 16:49:48.802  3465  3973 I ActivityManager: Killing 8543:com.android.providers.calendar/u0a47 (adj 15): DHA:empty #33
,01-27 16:49:48.802  9804  9804 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,01-27 16:49:48.812  3019  3019 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 9804
,01-27 16:49:48.812  3019  3019 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
01-27 16:49:48.812  9804  9804 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
01-27 16:49:48.812  9804  9804 I wpa_supplicant: ssSupport state is = 1
01-27 16:49:48.812  9804  9804 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
01-27 16:49:48.812  9804  9804 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
01-27 16:49:48.812  3019  3019 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 9804
01-27 16:49:48.812  3019  3019 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x00000106
,01-27 16:49:48.822  9804  9804 I SecureStorage: [INFO]: SPID(0x00000005)ss_id will be loaded by secure_storage_daemon: /system/bin/wpa_supplicant
,01-27 16:49:48.832  3465  4331 D ActivityManager: cleanUpApplicationRecord -- 8543
,01-27 16:49:48.832  3465  4331 D ActivityManager: isAutoRunBlockedApp:: com.android.providers.calendar, Auto Run ON
,01-27 16:49:48.832  9808  9808 D TimaKeyStoreProvider: TimaSignature is unavailable
01-27 16:49:48.832  9808  9808 D ActivityThread: Added TimaKeyStore provider
,01-27 16:49:48.842  3465  4059 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{bdfab43 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{51370b9 9808:com.sec.knox.switcher/1000}
,01-27 16:49:48.842  9808  9808 W ResourcesManager: getTopLevelResources: /system/app/KnoxSwitcher/KnoxSwitcher.apk / 1.0 running in com.sec.knox.switcher rsrc of package com.sec.knox.switcher
,01-27 16:49:48.842  3465  4487 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,01-27 16:49:48.842  9808  9808 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,01-27 16:49:48.852  9808  9808 D ResourcesManager: For user 0 new overlays fetched Null
,01-27 16:49:48.852  9808  9808 I InjectionManager: Inside getClassLibPath caller 
,01-27 16:49:48.852  9808  9808 W System  : ClassLoader referenced unknown path: /system/app/KnoxSwitcher/lib/arm64
,01-27 16:49:48.852  9808  9808 D KnoxUsageDB: getInstance - KnoxUsageDBHelper
01-27 16:49:48.852  9808  9808 D KnoxUsageDB: null == mDbHelperInstance - KnoxUsageDBHelper
,01-27 16:49:48.862  9808  9808 D InjectionManager: InjectionManager
01-27 16:49:48.862  9808  9808 D InjectionManager: fillFeatureStoreMap com.sec.knox.switcher
,01-27 16:49:48.862  9808  9808 I InjectionManager: Constructor com.sec.knox.switcher, Feature store :{}
01-27 16:49:48.862  9808  9808 I InjectionManager: featureStore :{}
01-27 16:49:48.862  9808  9808 I usagelog: received in receiver
,01-27 16:49:48.862  9808  9808 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
,01-27 16:49:48.862  9808  9808 I KnoxUsageLogPro: premStatus:2
,01-27 16:49:48.862  9808  9808 I KnoxUsageLogPro: isEulaShown : false
01-27 16:49:48.862  9808  9808 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,01-27 16:49:48.862  3465  4489 D ActivityManager:  getDeferredInfo final delay 0
,01-27 16:49:48.872  3465  4489 I ActivityManager: Start proc 9820:com.samsung.android.sm.policy/u0a135 for broadcast-5 com.samsung.android.sm.policy/.PolicyBroadCastReceiver
01-27 16:49:48.872  9820  9820 E Zygote  : v2
01-27 16:49:48.872  9820  9820 I libpersona: KNOX_SDCARD checking this for 10135
01-27 16:49:48.872  9820  9820 I libpersona: KNOX_SDCARD not a persona
,01-27 16:49:48.872  9820  9820 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
01-27 16:49:48.872  3465  4489 I ActivityManager: Killing 8825:com.google.android.apps.photos/u0a129 (adj 15): DHA:empty #33
,01-27 16:49:48.872  9820  9820 E Zygote  : accessInfo : 0
01-27 16:49:48.872  9820  9820 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.sm.policy 
,01-27 16:49:48.902  9820  9820 D TimaKeyStoreProvider: TimaSignature is unavailable
01-27 16:49:48.902  9820  9820 D ActivityThread: Added TimaKeyStore provider
,01-27 16:49:48.902  3465  4059 D ActivityManager: cleanUpApplicationRecord -- 8825
01-27 16:49:48.902  3465  4059 D ActivityManager: isAutoRunBlockedApp:: com.google.android.apps.photos, Auto Run ON
,01-27 16:49:48.912  3465  4403 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{bdfab43 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{db58cfe 9820:com.samsung.android.sm.policy/u0a135}
,01-27 16:49:48.912  9820  9820 W ResourcesManager: getTopLevelResources: /system/app/SCPMClient/SCPMClient.apk / 1.0 running in com.samsung.android.sm.policy rsrc of package com.samsung.android.sm.policy
,01-27 16:49:48.912  3465  4331 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,01-27 16:49:48.912  9820  9820 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,01-27 16:49:48.912  9820  9820 D ResourcesManager: For user 0 new overlays fetched Null
,01-27 16:49:48.922  9820  9820 I InjectionManager: Inside getClassLibPath caller 
,01-27 16:49:48.922  9820  9820 W System  : ClassLoader referenced unknown path: /system/app/SCPMClient/lib/arm64
,01-27 16:49:48.922  3465  6030 D SSRM:n  : SIOP:: AP = 340, PST = 345 (W:14), CP = 285, CUR = 34, LCD = 40
,01-27 16:49:48.932  3465  6030 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,01-27 16:49:48.932  9820  9820 D InjectionManager: InjectionManager
01-27 16:49:48.932  9820  9820 D InjectionManager: fillFeatureStoreMap com.samsung.android.sm.policy
,01-27 16:49:48.932  9820  9820 I InjectionManager: Constructor com.samsung.android.sm.policy, Feature store :{}
01-27 16:49:48.932  9820  9820 I InjectionManager: featureStore :{}
,01-27 16:49:48.932  3465  4488 D ActivityManager:  getDeferredInfo final delay 0
,01-27 16:49:48.942  9833  9833 E Zygote  : v2
01-27 16:49:48.942  9833  9833 I libpersona: KNOX_SDCARD checking this for 5005
01-27 16:49:48.942  9833  9833 I libpersona: KNOX_SDCARD not a persona
,01-27 16:49:48.942  9833  9833 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,01-27 16:49:48.942  3465  4488 I ActivityManager: Start proc 9833:com.samsung.android.app.FileShareClient/5005 for broadcast-5 com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver
01-27 16:49:48.942  9833  9833 E Zygote  : accessInfo : 0
01-27 16:49:48.942  9833  9833 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.app.FileShareClient 
,01-27 16:49:48.942  3465  4488 I ActivityManager: Killing 5736:com.android.defcontainer/u0a8 (adj 15): DHA:empty #33
,01-27 16:49:48.962  9833  9833 D TimaKeyStoreProvider: TimaSignature is unavailable
01-27 16:49:48.962  9833  9833 D ActivityThread: Added TimaKeyStore provider
,01-27 16:49:48.962  3465  4059 D ActivityManager: cleanUpApplicationRecord -- 5736
,01-27 16:49:48.962  3465  4059 D ActivityManager: isAutoRunBlockedApp:: com.android.defcontainer, Auto Run ON
,01-27 16:49:48.972  3465  4489 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{1b69c5f u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{edfb6ac 9833:com.samsung.android.app.FileShareClient/5005}
,01-27 16:49:48.982  9833  9833 W ResourcesManager: getTopLevelResources: /system/app/AllshareFileShareClient/AllshareFileShareClient.apk / 1.0 running in com.samsung.android.app.FileShareClient rsrc of package com.samsung.android.app.FileShareClient
,01-27 16:49:48.982  3465  3973 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,01-27 16:49:48.982  9833  9833 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,01-27 16:49:48.982  9833  9833 D ResourcesManager: For user 0 new overlays fetched Null
,01-27 16:49:48.982  9833  9833 I InjectionManager: Inside getClassLibPath caller 
,01-27 16:49:48.992  9833  9833 W System  : ClassLoader referenced unknown path: /system/app/AllshareFileShareClient/lib/arm64
,01-27 16:49:48.992  9833  9833 D InjectionManager: InjectionManager
01-27 16:49:48.992  9833  9833 D InjectionManager: fillFeatureStoreMap com.samsung.android.app.FileShareClient
,01-27 16:49:48.992  9833  9833 I InjectionManager: Constructor com.samsung.android.app.FileShareClient, Feature store :{}
01-27 16:49:48.992  9833  9833 I InjectionManager: featureStore :{}
,01-27 16:49:48.992  9833  9833 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,01-27 16:49:48.992  3465  3818 V AlarmManager: Expired Alarm result :4
01-27 16:49:48.992  9833  9833 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,01-27 16:49:49.002  3465  3858 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: true, uidstate: 6, mProxSensorScreenOff: false
01-27 16:49:49.002  3465  3858 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: true, uidstate: 6, mProxSensorScreenOff: false
,01-27 16:49:49.002  3162  3711 D EnterpriseController: netId is 0
01-27 16:49:49.002  3162  3711 D Netd    : getNetworkForDns: using netid 0 for uid 10019
,01-27 16:49:49.002  3465  3484 V AlarmManager:  remove PendingIntent] PendingIntent{2597b0a: PendingIntentRecord{3c7b89f com.google.android.gms broadcastIntent}}
,01-27 16:49:49.012  9833  9833 D FileShare-Client: Outbound.stopDelayTimer - 
01-27 16:49:49.012  3465  3538 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7529f7b u0 com.google.android.gcm.DISCONNECTED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3655c31 8494:com.google.android.talk/u0a112}
,01-27 16:49:49.012  3465  4225 D ActivityManager:  getDeferredInfo final delay 0
,01-27 16:49:49.022  9847  9847 E Zygote  : v2
01-27 16:49:49.022  9847  9847 I libpersona: KNOX_SDCARD checking this for 5005
01-27 16:49:49.022  9847  9847 I libpersona: KNOX_SDCARD not a persona
,01-27 16:49:49.022  9847  9847 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,01-27 16:49:49.022  3465  4225 I ActivityManager: Start proc 9847:com.samsung.android.app.FileShareServer/5005 for broadcast-5 com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver
,01-27 16:49:49.022  9847  9847 E Zygote  : accessInfo : 0
01-27 16:49:49.022  9847  9847 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.app.FileShareServer 
,01-27 16:49:49.032  3465  4225 I ActivityManager: Killing 8995:com.samsung.android.app.galaxylabs/u0a15 (adj 15): DHA:empty #33
,01-27 16:49:49.042  9847  9847 D TimaKeyStoreProvider: TimaSignature is unavailable
01-27 16:49:49.042  9847  9847 D ActivityThread: Added TimaKeyStore provider
,01-27 16:49:49.052  3465  4331 D ActivityManager: cleanUpApplicationRecord -- 8995
,01-27 16:49:49.052  3465  4331 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.galaxylabs, Auto Run ON
,01-27 16:49:49.062  3465  4489 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{1b69c5f u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ee79198 9847:com.samsung.android.app.FileShareServer/5005}
,01-27 16:49:49.062  9847  9847 W ResourcesManager: getTopLevelResources: /system/app/AllshareFileShareServer/AllshareFileShareServer.apk / 1.0 running in com.samsung.android.app.FileShareServer rsrc of package com.samsung.android.app.FileShareServer
,01-27 16:49:49.062  3465  3973 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,01-27 16:49:49.062  9847  9847 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,01-27 16:49:49.062  9847  9847 D ResourcesManager: For user 0 new overlays fetched Null
,01-27 16:49:49.072  9847  9847 I InjectionManager: Inside getClassLibPath caller 
,01-27 16:49:49.072  9847  9847 D InjectionManager: InjectionManager
01-27 16:49:49.072  9847  9847 D InjectionManager: fillFeatureStoreMap com.samsung.android.app.FileShareServer
,01-27 16:49:49.072  9847  9847 I InjectionManager: Constructor com.samsung.android.app.FileShareServer, Feature store :{}
01-27 16:49:49.072  9847  9847 I InjectionManager: featureStore :{}
,01-27 16:49:49.072  9847  9847 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,01-27 16:49:49.072  9847  9847 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
01-27 16:49:49.072  9847  9847 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,01-27 16:49:49.082  3465  4487 D ActivityManager:  getDeferredInfo final delay 0
,01-27 16:49:49.092  9859  9859 E Zygote  : v2
01-27 16:49:49.092  9859  9859 I libpersona: KNOX_SDCARD checking this for 1000
01-27 16:49:49.092  9859  9859 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
01-27 16:49:49.092  9859  9859 I libpersona: KNOX_SDCARD not a persona
01-27 16:49:49.092  3465  4487 I ActivityManager: Start proc 9859:com.policydm/1000 for broadcast-5 com.policydm/.XDMBroadcastReceiver
01-27 16:49:49.092  3465  4487 I ActivityManager: Killing 9013:com.google.android.partnersetup/u0a23 (adj 15): DHA:empty #33
,01-27 16:49:49.102  9859  9859 E Zygote  : accessInfo : 0
,01-27 16:49:49.122  3465  4489 D ActivityManager: cleanUpApplicationRecord -- 9013
,01-27 16:49:49.122  3465  4489 D ActivityManager: isAutoRunBlockedApp:: com.google.android.partnersetup, Auto Run ON
,01-27 16:49:49.132  9859  9859 D TimaKeyStoreProvider: TimaSignature is unavailable
01-27 16:49:49.132  9859  9859 D ActivityThread: Added TimaKeyStore provider
,01-27 16:49:49.142  9804  9804 I SecureStorage: [INFO]: SPID(0x00000005)Processing data has been completed
01-27 16:49:49.142  3019  3019 I SecureStorage: [INFO]: SPID(0x00000005)Secure Storage Daemon finished processing with result: 0
,01-27 16:49:49.142  3465  3483 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{12d4cd8 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a857df1 9859:com.policydm/1000}
,01-27 16:49:49.152  9859  9859 W ResourcesManager: getTopLevelResources: /system/priv-app/SPDClient/SPDClient.apk / 1.0 running in com.policydm rsrc of package com.policydm
,01-27 16:49:49.152  3465  4403 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,01-27 16:49:49.152  9859  9859 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,01-27 16:49:49.152  9859  9859 D ResourcesManager: For user 0 new overlays fetched Null
,01-27 16:49:49.162  9859  9859 I InjectionManager: Inside getClassLibPath caller 
,01-27 16:49:49.162  9859  9859 W System  : ClassLoader referenced unknown path: /system/priv-app/SPDClient/lib/arm64
,01-27 16:49:49.182  9588  9684 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,01-27 16:49:49.182  3465  3977 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
01-27 16:49:49.182  9859  9859 I FOTA    : [lIlIIlIIlIlllIIIIlll(108/llIIIIlllllIIllIIllI)] oms: /customer.xml
,01-27 16:49:49.182  9859  9859 I FOTA    : [lIlIIlIIlIlllIIIIlll(199/lllIlIlIIIllIIlIllIl)] read default : /system/csc/customer.xml
,01-27 16:49:49.182  3465  3977 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,01-27 16:49:49.182  9804  9804 I wpa_supplicant: Ctrl_iface: loading system cred
01-27 16:49:49.182  9804  9804 I SecureStorage: [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,01-27 16:49:49.182  3465  3977 D WifiService: setWifiEnabled: true pid=9588, uid=10074
01-27 16:49:49.182  3465  3977 W ActivityManager: Permission Denial: getCurrentUser() from pid=9588, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
01-27 16:49:49.182  3465  3977 W WifiService: Failed getting userId using ActivityManagerNative
01-27 16:49:49.182  3465  3977 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9588, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
01-27 16:49:49.182  3465  3977 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
01-27 16:49:49.182  3465  3977 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
01-27 16:49:49.182  3465  3977 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
01-27 16:49:49.182  3465  3977 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
01-27 16:49:49.182  3465  3977 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
,01-27 16:49:49.192  3465  3977 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
01-27 16:49:49.192  3465  3977 D SettingsProvider: isChangeAllowed() : name = wifi_on
01-27 16:49:49.192  3465  3863 D WifiStateMachine: setFccChannel: channel = -1
01-27 16:49:49.192  3465  3863 D WifiController: [FCC]setFccChannel() is called !!!
01-27 16:49:49.192  3465  3863 D WifiController: [FCC]Airplane off, setFccChannel(-1)!!!
,01-27 16:49:49.192  9859  9859 I FOTA    : [com.sec.android.policyagent.PolicyApplication(36/onCreate)] PolicyApplication onCreated!
,01-27 16:49:49.202  9859  9859 I DBG_POLICYDM: [com.policydm.db.XDB(1600/IllIlIIIIlIIlIIIllIl)] xdbDMffs_Init
,01-27 16:49:49.202  9804  9804 I SecureStorage: [INFO]: SPID(0x00000005)This device supports Secure Storage
,01-27 16:49:49.202  3019  3019 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 9804
01-27 16:49:49.202  3019  3019 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
01-27 16:49:49.202  9804  9804 I SecureStorage: [INFO]: SPID(0x00000005)SS Daemon is running
01-27 16:49:49.202  9804  9804 I wpa_supplicant: ssSupport state is = 1
,01-27 16:49:49.202  9804  9804 I wpa_supplicant: Blacklist: Clear (all) 
,01-27 16:49:49.202  9804  9804 E wpa_supplicant: getSavedIMSI cannot open /data/misc/radio/kmem: No such file or directory
01-27 16:49:49.212  9804  9804 I wpa_supplicant: [getIMSI]: sim_num 0
,01-27 16:49:49.212  9804  9804 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,01-27 16:49:49.212  9859  9859 I DBG_POLICYDM: [com.policydm.db.llIIIIlllllIIllIIllI(142/llIIIIlllllIIllIIllI)] try read dbString
,01-27 16:49:49.282  9859  9859 I DBG_POLICYDM: [com.policydm.XDMService(161/llIIIIlllllIIllIIllI)] xdmUIHandelerInit
,01-27 16:49:49.282  9859  9859 I DBG_POLICYDM: [IlIIIllIlIIIlIIlIIlI(52/<init>)] 
,01-27 16:49:49.282  9859  9859 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1394 android.content.ContextWrapper.bindService:632 IlIIIllIlIIIlIIlIIlI.<init>:56 IIIlIIlllIlIlIIIIIII.llIIIIlllllIIllIIllI:19 IIIlIIlllIlIlIIIIIII.llllIIIllIlIIIIllllI:25 
,01-27 16:49:49.302  9876  9876 E Zygote  : v2
01-27 16:49:49.302  9876  9876 I libpersona: KNOX_SDCARD checking this for 1000
01-27 16:49:49.302  9876  9876 I libpersona: KNOX_SDCARD not a persona
,01-27 16:49:49.302  9876  9876 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,01-27 16:49:49.302  9876  9876 E Zygote  : accessInfo : 0
,01-27 16:49:49.312  3465  4331 I ActivityManager: Start proc 9876:com.samsung.aasaservice/1000 for service com.samsung.aasaservice/.AASAService
,01-27 16:49:49.312  9859  9859 I DBG_POLICYDM: [IIIlIIlllIlIlIIIIIII(28/llllIIIllIlIIIIllllI)] AASAUpdater Init Success
,01-27 16:49:49.322  9859  9859 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,01-27 16:49:49.322  9859  9859 I DBG_POLICYDM: [com.policydm.XDMService(585/llIlIllllllllllllllI)] get NotibarState : 0
,01-27 16:49:49.332  9859  9859 D InjectionManager: InjectionManager
01-27 16:49:49.332  9859  9859 D InjectionManager: fillFeatureStoreMap com.policydm
,01-27 16:49:49.332  9859  9859 I InjectionManager: Constructor com.policydm, Feature store :{}
01-27 16:49:49.332  9859  9859 I InjectionManager: featureStore :{}
,01-27 16:49:49.332  9876  9876 D TimaKeyStoreProvider: TimaSignature is unavailable
01-27 16:49:49.332  9876  9876 D ActivityThread: Added TimaKeyStore provider
,01-27 16:49:49.352  9859  9859 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(574/IlIIIllllIIlIIIIIlII)] Initiated Type: 0
01-27 16:49:49.352  9876  9876 W ResourcesManager: getTopLevelResources: /system/app/AASAservice/AASAservice.apk / 1.0 running in com.samsung.aasaservice rsrc of package com.samsung.aasaservice
,01-27 16:49:49.352  3465  4403 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,01-27 16:49:49.352  9876  9876 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,01-27 16:49:49.352  9876  9876 D ResourcesManager: For user 0 new overlays fetched Null
,01-27 16:49:49.352  9859  9859 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,01-27 16:49:49.362  9859  9859 I DBG_POLICYDM: [com.policydm.XDMService(585/llIlIllllllllllllllI)] get NotibarState : 0
,01-27 16:49:49.362  9876  9876 I InjectionManager: Inside getClassLibPath caller 
,01-27 16:49:49.362  9876  9876 W System  : ClassLoader referenced unknown path: /system/app/AASAservice/lib/arm64
,01-27 16:49:49.362  9876  9876 D InjectionManager: InjectionManager
01-27 16:49:49.362  9876  9876 D InjectionManager: fillFeatureStoreMap com.samsung.aasaservice
01-27 16:49:49.362  9876  9876 I InjectionManager: Constructor com.samsung.aasaservice, Feature store :{}
01-27 16:49:49.362  9876  9876 I InjectionManager: featureStore :{}
,01-27 16:49:49.372  9876  9876 D AASAservice: onCreate()
,01-27 16:49:49.372  9859  9859 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(38/onServiceConnected)] AASA: onServiceConnected
,01-27 16:49:49.402  3465  4331 D ActivityManager:  getDeferredInfo final delay 300
01-27 16:49:49.402  3465  4331 I ActivityManager: Killing 9035:com.samsung.android.asksmanager/u0a171 (adj 15): DHA:empty #33
,01-27 16:49:49.402  3465  4331 I ActivityManager: Killing 9061:com.samsung.svoice.sync/u0a40 (adj 15): DHA:empty #33
,01-27 16:49:49.422  3465  3483 D ActivityManager: cleanUpApplicationRecord -- 9035
,01-27 16:49:49.422  3465  3483 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.asksmanager, Auto Run ON
,01-27 16:49:49.432  3465  4485 D ActivityManager: cleanUpApplicationRecord -- 9061
,01-27 16:49:49.432  3465  4485 D ActivityManager: isAutoRunBlockedApp:: com.samsung.svoice.sync, Auto Run ON
,01-27 16:49:49.622  3465  3535 D libgps  : agps_ril_update_network_availability: Waiting for IPC connection - timeout
01-27 16:49:49.622  3465  3535 E libgps  : LIBGPS: Cannot communicate (write) with a GPSD
01-27 16:49:49.622  3465  3535 E libgps  : IPC Communication Error, ../../../../tmp/14982990_270314/allPartners/os/android/gps_interface/gpsi_client/GpsiClient.cpp:1729 agps_ril_update_network_availability
,01-27 16:49:49.672  3465  4403 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,01-27 16:49:49.672  3465  4403 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4340, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
01-27 16:49:49.672  3465  4403 D BatteryService: online:4, current avg:26, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:94
01-27 16:49:49.672  3465  3465 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,01-27 16:49:49.672  3465  3465 I MotionRecognitionService: Plugged
01-27 16:49:49.672  3465  3465 D MotionRecognitionService:   cableConnection= 1
01-27 16:49:49.672  3465  3465 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
01-27 16:49:49.672  3465  3465 D MotionRecognitionService: skip setTransmitPower. 
,01-27 16:49:49.672  3465  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,01-27 16:49:49.672  3950  3950 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,01-27 16:49:49.672  3950  3950 D KeyguardUpdateMonitor: handleBatteryUpdate
,01-27 16:49:49.672  3950  3950 D PowerUI : priorPlugType = 2 mPlugType =  2
,01-27 16:49:49.682  3950  3950 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
01-27 16:49:49.682  3950  3950 D PowerUI.Notification: There is no change about charging status, so return!
,01-27 16:49:49.682  4990  4990 D CommonServiceConfiguration: getStringValueSetting
,01-27 16:49:49.682  4942  4942 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
01-27 16:49:49.682  4942  9696 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,01-27 16:49:49.682  4990  4990 D BatteryMonitor: new battery level: 100
,01-27 16:49:49.692  9588  9684 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,01-27 16:49:49.692  3465  3977 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,01-27 16:49:49.692  3465  3977 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,01-27 16:49:49.692  3465  3977 D WifiService: setWifiEnabled: true pid=9588, uid=10074
,01-27 16:49:49.692  3465  3977 W ActivityManager: Permission Denial: getCurrentUser() from pid=9588, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
01-27 16:49:49.692  3465  3977 W WifiService: Failed getting userId using ActivityManagerNative
01-27 16:49:49.692  3465  3977 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9588, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
01-27 16:49:49.692  3465  3977 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
01-27 16:49:49.692  3465  3977 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
01-27 16:49:49.692  3465  3977 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
01-27 16:49:49.692  3465  3977 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
01-27 16:49:49.692  3465  3977 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
01-27 16:49:49.692  3465  3977 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
01-27 16:49:49.692  3465  3977 D SettingsProvider: isChangeAllowed() : name = wifi_on
01-27 16:49:49.692  3465  3863 D WifiController: [FCC]setFccChannel() is called !!!
01-27 16:49:49.692  3465  3863 D WifiStateMachine: setFccChannel: channel = -1
01-27 16:49:49.692  3465  3863 D WifiController: [FCC]Airplane off, setFccChannel(-1)!!!
,01-27 16:49:49.702  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,01-27 16:49:49.702  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,01-27 16:49:49.702  3465  3538 D ActivityManager:  getDeferredInfo final delay 80
,01-27 16:49:49.712  3465  4382 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
01-27 16:49:49.712  3465  4382 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4340, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
,01-27 16:49:49.712  3465  4382 D BatteryService: online:4, current avg:26, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-38
01-27 16:49:49.712  3465  3465 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,01-27 16:49:49.722  3465  3465 I MotionRecognitionService: Plugged
01-27 16:49:49.722  3465  3465 D MotionRecognitionService:   cableConnection= 1
01-27 16:49:49.722  3465  3465 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
01-27 16:49:49.722  3465  3465 D MotionRecognitionService: skip setTransmitPower. 
,01-27 16:49:49.722  3465  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,01-27 16:49:49.722  3950  3950 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,01-27 16:49:49.722  3950  3950 D PowerUI : priorPlugType = 2 mPlugType =  2
,01-27 16:49:49.722  3950  3950 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
01-27 16:49:49.722  3950  3950 D KeyguardUpdateMonitor: handleBatteryUpdate
01-27 16:49:49.722  3950  3950 D PowerUI.Notification: There is no change about charging status, so return!
01-27 16:49:49.722  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,01-27 16:49:49.722  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
01-27 16:49:49.722  4990  4990 D CommonServiceConfiguration: getStringValueSetting
,01-27 16:49:49.722  4942  4942 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
01-27 16:49:49.722  4942  9696 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,01-27 16:49:49.722  4990  4990 D BatteryMonitor: new battery level: 100
,01-27 16:49:49.842  3465  3538 D ActivityManager:  getDeferredInfo final delay 80
,01-27 16:49:49.922  3465  3538 D ActivityManager:  getDeferredInfo final delay 80
,01-27 16:49:49.972  3162  3708 D Netd    : Iface wlan0 link up
,01-27 16:49:49.972  3162  3708 D Netd    : Iface wlan0 link up
01-27 16:49:49.972  3162  3708 D Netd    : Iface wlan0 link up
,01-27 16:49:49.982  4990  5007 D PdnController: Interface Changed wlan0 link up
,01-27 16:49:49.982  3465  3542 D Tethering: interfaceLinkStateChanged wlan0, true
01-27 16:49:49.982  3465  3542 D Tethering: interfaceStatusChanged wlan0, true
,01-27 16:49:49.982  4990  5002 D PdnController: Interface Changed wlan0 link up
01-27 16:49:49.982  3465  3542 D Tethering: interfaceLinkStateChanged wlan0, true
01-27 16:49:49.982  3465  3542 D Tethering: interfaceStatusChanged wlan0, true
,01-27 16:49:49.982  4990  5473 D PdnController: Interface Changed wlan0 link up
01-27 16:49:49.982  3465  3542 D Tethering: interfaceLinkStateChanged wlan0, true
01-27 16:49:49.982  3465  3542 D Tethering: interfaceStatusChanged wlan0, true
,01-27 16:49:50.002  3465  3538 D ActivityManager:  getDeferredInfo final delay 80
,01-27 16:49:50.032  9804  9804 I wpa_supplicant: set_csc_config : ifname(p2p0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x0), vendorssid_list()
01-27 16:49:50.032  9804  9804 I SecureStorage: [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,01-27 16:49:50.052  9804  9804 I SecureStorage: [INFO]: SPID(0x00000005)This device supports Secure Storage
,01-27 16:49:50.052  3019  3019 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 9804
01-27 16:49:50.052  3019  3019 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
,01-27 16:49:50.052  9804  9804 I SecureStorage: [INFO]: SPID(0x00000005)SS Daemon is running
01-27 16:49:50.052  9804  9804 I wpa_supplicant: ssSupport state is = 1
,01-27 16:49:50.052  9804  9804 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,01-27 16:49:50.052  9804  9804 E wpa_supplicant: nl80211: Could not configure driver mode
01-27 16:49:50.052  9804  9804 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
01-27 16:49:50.052  9804  9804 E wpa_supplicant: p2p0: Failed to initialize driver interface
01-27 16:49:50.052  9804  9804 I wpa_supplicant: Blacklist: Clear (all) 
,01-27 16:49:50.062  9804  9804 I wpa_supplicant: set_csc_config : ifname(p2p0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x0), vendorssid_list()
01-27 16:49:50.062  9804  9804 I SecureStorage: [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,01-27 16:49:50.072  9804  9804 I SecureStorage: [INFO]: SPID(0x00000005)This device supports Secure Storage
,01-27 16:49:50.082  3019  3019 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 9804
01-27 16:49:50.082  3019  3019 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
01-27 16:49:50.082  9804  9804 I SecureStorage: [INFO]: SPID(0x00000005)SS Daemon is running
01-27 16:49:50.082  9804  9804 I wpa_supplicant: ssSupport state is = 1
01-27 16:49:50.082  9804  9804 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,01-27 16:49:50.082  3465  3538 D ActivityManager:  getDeferredInfo final delay 80
,01-27 16:49:50.082  9804  9804 I wpa_supplicant: P2P: Set prekey state (NONE -> NONE)
,01-27 16:49:50.092  3465  3860 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
01-27 16:49:50.092  3465  3860 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,01-27 16:49:50.092  3465  3860 E WifiStateMachine: Deffering msg in Supplicant Starting State131085
01-27 16:49:50.092  3465  3860 D WifiBigDataLog: getJsonFormat() - feature : ONOF
01-27 16:49:50.092  3465  3860 D WifiBigDataLog: init : 
,01-27 16:49:50.092  3465  3860 E WifiStateMachine: Deffering msg in Supplicant Starting State131083
01-27 16:49:50.092  3465  3860 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,01-27 16:49:50.092  3465  3860 D WifiBigDataLog: getJsonFormat() - feature : ONOF
01-27 16:49:50.092  3465  3860 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,01-27 16:49:50.102  3465  3538 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{463082d u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{47dcb8b 4974:com.samsung.android.providers.context/u0a7}
,01-27 16:49:50.102  3465  3860 D WifiBigDataLog: init : 
,01-27 16:49:50.102  3465  3860 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,01-27 16:49:50.102  3465  3860 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,01-27 16:49:50.112  3465  4489 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a766162 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{47dcb8b 4974:com.samsung.android.providers.context/u0a7}
,01-27 16:49:50.112  3465  3860 D WifiBigDataLog: init : 
,01-27 16:49:50.112  3465  3860 D WifiNative-wlan0: callSECApiBoolean - ID [301]
,01-27 16:49:50.112  9804  9804 I wpa_supplicant: HOTSPOT20_ENABLE called ON
,01-27 16:49:50.112  9804  9804 I wpa_supplicant: Blacklist: Clear (all) 
,01-27 16:49:50.122  3465  4489 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{902fbb0 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{47dcb8b 4974:com.samsung.android.providers.context/u0a7}
,01-27 16:49:50.122  9804  9804 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,01-27 16:49:50.132  9804  9804 I wpa_supplicant: wlan0: Skip scan - bUseNetwork false
,01-27 16:49:50.132  3465  3860 D WifiNative-wlan0: callSECApiInt - ID [210]
,01-27 16:49:50.132  3465  3465 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
01-27 16:49:50.132  3465  3465 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
,01-27 16:49:50.132  3465  3864 D HS20StateMachine: WIFI_STATE_ENABLED
01-27 16:49:50.132  3465  3864 D HS20StateMachine: reloadCredentialsToSupplicant
01-27 16:49:50.132  3465  3867 I WifiHs20Service: Message received 5011
01-27 16:49:50.132  3465  3864 D HotspotDBHandler: getCredentialIds
,01-27 16:49:50.142  3465  3871 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,01-27 16:49:50.142  3465  3465 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
01-27 16:49:50.142  3950  4150 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
01-27 16:49:50.142  3465  4202 W SLocation: No Active Data Connection
01-27 16:49:50.142  4302  5231 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,01-27 16:49:50.142  4302  5231 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
01-27 16:49:50.142  3465  3871 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
01-27 16:49:50.142  3950  3950 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,01-27 16:49:50.142  3950  3950 I HotspotTile: Provider is not defined returning false
,01-27 16:49:50.142  3950  3950 D HotspotTile: onReceive : 3, 0
,01-27 16:49:50.142  3950  3950 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 272
,01-27 16:49:50.152  9588  9588 D BluetoothAdapter: STATE_ON
,01-27 16:49:50.152  9588  9588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
01-27 16:49:50.152  9588  9588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
01-27 16:49:50.152  9588  9588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
01-27 16:49:50.152  9588  9588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
01-27 16:49:50.152  9588  9588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
01-27 16:49:50.152  9588  9588 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
01-27 16:49:50.152  9588  9588 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
01-27 16:49:50.152  9588  9588 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
01-27 16:49:50.152  9588  9588 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,01-27 16:49:50.152  3465  3538 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{914fa29 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4c3b831 9588:com.test.thalitest/u0a74}
,01-27 16:49:50.152  9588  9588 D BluetoothAdapter: STATE_ON
,01-27 16:49:50.162  9588  9588 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,01-27 16:49:50.162  3465  4225 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:50.162  3465  4225 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,01-27 16:49:50.162  3465  4225 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:50.162  3465  4225 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:50.162  3465  4225 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:50.162  3465  4225 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:50.162  3465  4225 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:50.162  3465  4225 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:50.162  3465  4225 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:50.162  3465  4225 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:50.162  3465  4225 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:50.162  3465  4225 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
01-27 16:49:50.162  3465  4225 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:50.162  3465  4225 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,01-27 16:49:50.162  3465  4225 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,01-27 16:49:50.172  9897  9897 E Zygote  : v2
01-27 16:49:50.172  9897  9897 I libpersona: KNOX_SDCARD checking this for 10114
01-27 16:49:50.172  9897  9897 I libpersona: KNOX_SDCARD not a persona
,01-27 16:49:50.172  9897  9897 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,01-27 16:49:50.172  3465  3864 I ActivityManager: Start proc 9897:com.samsung.hs20provider/u0a114 for content provider com.samsung.hs20provider/.Hs20Provider
,01-27 16:49:50.172  9897  9897 E Zygote  : accessInfo : 0
01-27 16:49:50.172  9897  9897 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.samsung.hs20provider 
,01-27 16:49:50.182  9804  9804 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,01-27 16:49:50.182  3465  3860 D WifiConfigStore: Loading config and enabling all networks 
,01-27 16:49:50.182  3465  3538 D ActivityManager:  getDeferredInfo final delay 80
,01-27 16:49:50.192  3465  3860 I WifiConfigStore: "AndroidHotspot2346" is a verified password AP: true
01-27 16:49:50.192  3465  3860 E WifiConfigStore: Not a HS20
,01-27 16:49:50.202  9588  9684 D BluetoothAdapter: STATE_ON
,01-27 16:49:50.202  3465  3860 I WifiConfigStore: "MC" is a verified password AP: true
01-27 16:49:50.202  3465  3860 E WifiConfigStore: Not a HS20
,01-27 16:49:50.202  9897  9897 D TimaKeyStoreProvider: TimaSignature is unavailable
01-27 16:49:50.202  9897  9897 D ActivityThread: Added TimaKeyStore provider
01-27 16:49:50.202  9588  9684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
01-27 16:49:50.202  9588  9684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
01-27 16:49:50.202  9588  9684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
01-27 16:49:50.202  9588  9684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
01-27 16:49:50.202  9588  9684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
01-27 16:49:50.202  9588  9684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
01-27 16:49:50.202  9588  9684 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
01-27 16:49:50.202  9588  9684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
01-27 16:49:50.202  9588  9684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,01-27 16:49:50.202  9588  9651 D BluetoothAdapter: enable()
,01-27 16:49:50.212  3465  3860 I WifiConfigStore: "MC" is a verified password AP: false
01-27 16:49:50.212  3465  3860 E WifiConfigStore: Not a HS20
,01-27 16:49:50.212  9588  9651 D BluetoothAdapter: enable(): BT is already enabled..!
,01-27 16:49:50.212  3465  3538 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{be55b4f u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{47dcb8b 4974:com.samsung.android.providers.context/u0a7}
,01-27 16:49:50.222  3465  3860 I WifiConfigStore: "NG700" is a verified password AP: true
01-27 16:49:50.222  3465  3860 E WifiConfigStore: Not a HS20
,01-27 16:49:50.222  3465  3860 D WifiConfigStore: loaded 0 passpoint configs
,01-27 16:49:50.222  3465  4059 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1248000  uid : 1000  pid : 3465  tag : BADGE_UPDATE@CPU_MIN@1
01-27 16:49:50.222  9588  9651 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
01-27 16:49:50.222  3465  3860 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
01-27 16:49:50.222  3465  3860 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,01-27 16:49:50.222  3465  3860 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
01-27 16:49:50.222  3465  3860 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
01-27 16:49:50.222  3465  3860 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 4
01-27 16:49:50.222  3465  3860 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
01-27 16:49:50.222  3465  3860 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
01-27 16:49:50.222  3465  3860 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
01-27 16:49:50.222  3465  3860 E WifiConfigStore: found sortedWifiConfigurations : "MC"NONE
,01-27 16:49:50.222  3465  4487 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,01-27 16:49:50.232  3465  4487 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,01-27 16:49:50.232  3465  4487 D WifiService: setWifiEnabled: true pid=9588, uid=10074
,01-27 16:49:50.232  9897  9897 W ResourcesManager: getTopLevelResources: /system/app/Hs20Provider/Hs20Provider.apk / 1.0 running in com.samsung.hs20provider rsrc of package com.samsung.hs20provider
,01-27 16:49:50.232  3465  3860 D WifiConfigStore: setNetworkPriorityDefault: networkId = 1, priority = 1
,01-27 16:49:50.232  3465  4489 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
01-27 16:49:50.232  3465  3860 D WifiConfigStore: setNetworkPriorityDefault: networkId = 0, priority = 1
01-27 16:49:50.232  3465  4487 W ActivityManager: Permission Denial: getCurrentUser() from pid=9588, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
,01-27 16:49:50.232  9897  9897 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,01-27 16:49:50.232  3465  3465 I WifiHs20Service: Broadcast received:android.net.wifi.CONFIGURED_NETWORKS_CHANGE
,01-27 16:49:50.232  3465  4487 D SettingsProvider: isChangeAllowed() : name = wifi_on
,01-27 16:49:50.232  3465  3465 D WifiHs20Service: reason: 2
,01-27 16:49:50.232  9897  9897 D ResourcesManager: For user 0 new overlays fetched Null
,01-27 16:49:50.232  3465  3867 I WifiHs20Service: Message received 5014
01-27 16:49:50.232  3465  3863 D WifiController: [FCC]setFccChannel() is called !!!
,01-27 16:49:50.232  3465  3867 E WifiHs20Service: received HS20_UTILITY_ACTION_TYPE_HS20_CONFIGURATION_CHANGED
,01-27 16:49:50.232  3465  3863 D WifiController: [FCC]Airplane off, setFccChannel(-1)!!!
,01-27 16:49:50.232  3465  3867 E WifiHs20Service: The changed config is NULL
01-27 16:49:50.232  3465  4487 W WifiService: Failed getting userId using ActivityManagerNative
01-27 16:49:50.232  3465  4487 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9588, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
01-27 16:49:50.232  3465  4487 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
01-27 16:49:50.232  3465  4487 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
01-27 16:49:50.232  3465  4487 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
01-27 16:49:50.232  3465  4487 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
01-27 16:49:50.232  3465  4487 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
01-27 16:49:50.232  3465  4487 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
,01-27 16:49:50.232  3465  3860 D WifiConfigStore: setNetworkPriorityDefault: networkId = 3, priority = 1
01-27 16:49:50.232  3465  3860 D WifiConfigStore: setNetworkPriorityDefault: networkId = 2, priority = 1
01-27 16:49:50.232  9588  9651 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,01-27 16:49:50.232  9588  9651 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
01-27 16:49:50.232  3465  3863 D WifiStateMachine: setFccChannel: channel = -1
01-27 16:49:50.232  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,01-27 16:49:50.232  9588  9651 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
01-27 16:49:50.232  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
01-27 16:49:50.232  9588  9651 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aec0f84 removed from the list
01-27 16:49:50.232  9588  9651 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aec0f84 removed from the list
,01-27 16:49:50.232  9588  9651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
01-27 16:49:50.232  9588  9651 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@755036d removed from the list
,01-27 16:49:50.232  9588  9651 D io.jxcore.node.ConnectivityMonitor: stop
,01-27 16:49:50.232  9588  9651 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
01-27 16:49:50.232  3465  3860 D WifiNative-wlan0: callSECApiInt - ID [65]
01-27 16:49:50.232  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,01-27 16:49:50.232  9588  9651 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testRun
,01-27 16:49:50.242  9897  9897 I InjectionManager: Inside getClassLibPath caller 
01-27 16:49:50.242  9588  9909 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
01-27 16:49:50.242  9588  9909 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,01-27 16:49:50.242  3465  3860 D WifiNative-wlan0: callSECApiBoolean - ID [13]
,01-27 16:49:50.242  9804  9804 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
01-27 16:49:50.242  9804  9804 I wpa_supplicant: resume autoscan
01-27 16:49:50.242  9804  9804 I wpa_supplicant: autoscan_samsung_exponential_notify_scan : scan_interval = 8
01-27 16:49:50.242  9804  9804 I wpa_supplicant: autoscan: autoscan_notify_scan, scan_interval = 8
01-27 16:49:50.242  9804  9804 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
01-27 16:49:50.242  9804  9804 I wpa_supplicant: reset timer : RESET_TIMER 0
01-27 16:49:50.242  9804  9804 I wpa_supplicant: P2P: Current p2p state = IDLE
01-27 16:49:50.242  9897  9897 W System  : ClassLoader referenced unknown path: /system/app/Hs20Provider/lib/arm64
01-27 16:49:50.252  3162  3711 D EnterpriseController: netId is 0
01-27 16:49:50.252  3162  3711 D Netd    : getNetworkForDns: using netid 0 for uid 10074
,01-27 16:49:50.252  9804  9804 I wpa_supplicant: First Scan Start
,01-27 16:49:50.252  9897  9897 D InjectionManager: InjectionManager,
,01-27 16:49:50.252  9897  9897 D InjectionManager: fillFeatureStoreMap com.samsung.hs20provider
,01-27 16:49:50.252  9588  9911 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
01-27 16:49:50.252  9588  9911 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
01-27 16:49:50.252  9588  9911 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,01-27 16:49:50.252  9588  9909 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,01-27 16:49:50.252  9588  9909 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
01-27 16:49:50.252  9588  9909 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
01-27 16:49:50.262  3465  3538 D ActivityManager:  getDeferredInfo final delay 80
01-27 16:49:50.252  9588  9911 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
01-27 16:49:50.262  3465  6030 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:50.252  9804  9804 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,01-27 16:49:50.252  9588  9909 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
01-27 16:49:50.262  9588  9911 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,01-27 16:49:50.262  3465  3860 D WifiNative-wlan0: Setting external_sim to 1
01-27 16:49:50.262  9588  9913 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 237, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
01-27 16:49:50.262  9588  9913 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
01-27 16:49:50.262  9588  9913 D io.jxcore.node.StreamCopyingThread:  id: 74
01-27 16:49:50.262  9588  9909 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,01-27 16:49:50.262  9588  9914 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 238, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
01-27 16:49:50.262  9588  9914 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
01-27 16:49:50.262  9588  9914 D io.jxcore.node.StreamCopyingThread:  id: 75
,01-27 16:49:50.262  9588  9915 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 239, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
01-27 16:49:50.262  9588  9915 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
01-27 16:49:50.262  9588  9915 D io.jxcore.node.StreamCopyingThread:  id: 74
01-27 16:49:50.262  9588  9915 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 239, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
01-27 16:49:50.262  9588  9915 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
01-27 16:49:50.262  9588  9915 D io.jxcore.node.StreamCopyingThread:  id: 74
01-27 16:49:50.262  9588  9915 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
01-27 16:49:50.262  9588  9915 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
01-27 16:49:50.262  9588  9915 D io.jxcore.node.StreamCopyingThread:  id: 74
,01-27 16:49:50.262  9588  9915 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
01-27 16:49:50.262  9588  9915 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
01-27 16:49:50.262  9588  9915 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
01-27 16:49:50.262  9588  9915 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,01-27 16:49:50.262  9588  9915 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
01-27 16:49:50.262  9588  9915 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
01-27 16:49:50.262  9588  9915 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 239, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
01-27 16:49:50.262  9588  9915 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
01-27 16:49:50.262  9588  9915 D io.jxcore.node.StreamCopyingThread:  id: 74 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
01-27 16:49:50.262  9897  9897 I InjectionManager: Constructor com.samsung.hs20provider, Feature store :{}
,01-27 16:49:50.262  9897  9897 I InjectionManager: featureStore :{}
01-27 16:49:50.262  9588  9916 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 240, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
01-27 16:49:50.262  9588  9916 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
01-27 16:49:50.262  9588  9916 D io.jxcore.node.StreamCopyingThread:  id: 75
01-27 16:49:50.262  9588  9916 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 240, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
01-27 16:49:50.262  9588  9916 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
01-27 16:49:50.262  9588  9916 D io.jxcore.node.StreamCopyingThread:  id: 75
,01-27 16:49:50.262  9588  9916 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
01-27 16:49:50.262  9588  9916 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
01-27 16:49:50.262  9588  9916 D io.jxcore.node.StreamCopyingThread:  id: 75
01-27 16:49:50.262  9588  9916 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
01-27 16:49:50.262  9588  9916 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
01-27 16:49:50.262  3465  3860 D WifiStateMachine: Setting OUI to DA-A1-19
,01-27 16:49:50.262  9588  9914 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 238, thread name: OutgoingSocketThread/Sender): Socket closed
01-27 16:49:50.262  9588  9913 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 237, thread name: IncomingSocketThread/Sender): Socket closed
01-27 16:49:50.262  9588  9914 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 238, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
01-27 16:49:50.262  9588  9914 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
01-27 16:49:50.262  9588  9914 D io.jxcore.node.StreamCopyingThread:  id: 75 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
01-27 16:49:50.262  9588  9914 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
01-27 16:49:50.262  9588  9914 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,01-27 16:49:50.262  9588  9913 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 237, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
01-27 16:49:50.262  9588  9913 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
01-27 16:49:50.262  9588  9913 D io.jxcore.node.StreamCopyingThread:  id: 74 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
01-27 16:49:50.262  9588  9914 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 238, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
01-27 16:49:50.262  9588  9914 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
01-27 16:49:50.262  9588  9914 D io.jxcore.node.StreamCopyingThread:  id: 75 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,01-27 16:49:50.262  9588  9913 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
01-27 16:49:50.262  9588  9916 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
01-27 16:49:50.262  9588  9913 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
01-27 16:49:50.262  9588  9913 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 237, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
01-27 16:49:50.262  9588  9913 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
01-27 16:49:50.262  9588  9913 D io.jxcore.node.StreamCopyingThread:  id: 74 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
01-27 16:49:50.262  9588  9916 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,01-27 16:49:50.262  9588  9916 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
01-27 16:49:50.262  9588  9916 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
01-27 16:49:50.262  9588  9916 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 240, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
01-27 16:49:50.262  9588  9916 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
01-27 16:49:50.262  9588  9916 D io.jxcore.node.StreamCopyingThread:  id: 75 .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,01-27 16:49:50.262  9804  9804 I wpa_supplicant: bt_status is set be DISCONNECTED
01-27 16:49:50.272  9897  9908 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_credentials
01-27 16:49:50.272  9897  9908 D HotspotProvider: CREDENTIAL
01-27 16:49:50.272  9897  9908 D HotspotProvider: No prepend tags
01-27 16:49:50.272  3465  3860 E WifiNative-wlan0: do suspend false
,01-27 16:49:50.282  3465  3864 D HS20StateMachine: CMD_HOTSPOT20_ENABLE : 
01-27 16:49:50.282  3465  3864 D HS20StateMachine: enter : DiscoveringState
,01-27 16:49:50.282  3465  3465 I ActivityManager: Killing 9117:com.samsung.android.provider.shootingmodeprovider/u0a57 (adj 15): DHA:empty #33
,01-27 16:49:50.292  3465  3860 D WifiStateMachine:  p2p Needed be enabled 
01-27 16:49:50.292  3465  3859 D WifiP2pService: P2pDisabledState{ what=131203 }
,01-27 16:49:50.292  3465  3860 D WifiNative-HAL: Failing getSupportedFeatureset because HAL isn't started
01-27 16:49:50.292  3465  3860 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
01-27 16:49:50.292  3465  3860 D WifiStateMachine: [FCC]Airplane off, setFccChannel(-1)!!!
01-27 16:49:50.292  3465  3860 D WifiStateMachine: setFccChannelNative: channel = -1
01-27 16:49:50.292  3465  3860 D WifiNative-wlan0: callSECApiInt - ID [230]
01-27 16:49:50.292  3465  3465 D RttService: SCAN_AVAILABLE : 3
01-27 16:49:50.292  3465  3893 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,01-27 16:49:50.292  3465  3892 E WifiScanningService: could not start HAL
01-27 16:49:50.292  3162  3715 D CommandListener: Setting iface cfg
01-27 16:49:50.292  3162  3715 D CommandListener: Trying to bring up p2p0
,01-27 16:49:50.302  3162  3708 D Netd    : Iface p2p0 link up
,01-27 16:49:50.302  3465  3859 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
01-27 16:49:50.302  4990  9374 D PdnController: Interface Changed p2p0 link up
,01-27 16:49:50.302  3465  3542 D Tethering: interfaceLinkStateChanged p2p0, true
01-27 16:49:50.302  3465  3542 D Tethering: interfaceStatusChanged p2p0, true
,01-27 16:49:50.302  3465  3860 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,01-27 16:49:50.302  3465  3860 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,01-27 16:49:50.302  3465  3977 D ActivityManager: cleanUpApplicationRecord -- 9117
,01-27 16:49:50.302  3465  3859 D SecContentProvider: insert(), uri = 2
,01-27 16:49:50.312  3465  3977 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.provider.shootingmodeprovider, Auto Run ON
,01-27 16:49:50.312  3465  3859 D WifiP2pService: P2pEnablingState
01-27 16:49:50.312  3465  3859 D WifiP2pService: P2pEnablingState{ what=147457 }
01-27 16:49:50.312  3465  3859 D WifiP2pService: P2p socket connection successful
,01-27 16:49:50.312  3465  3859 D WifiP2pService: P2pEnabledState
01-27 16:49:50.312  3465  3859 D SecContentProvider: insert(), uri = 2
,01-27 16:49:50.312  3465  3860 D WifiBigDataLog: init : 
,01-27 16:49:50.322  3465  3860 D WifiStateMachine: setFccChannelNative: channel = -1
01-27 16:49:50.322  3465  3860 D WifiNative-wlan0: callSECApiInt - ID [230]
,01-27 16:49:50.322  3465  3538 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3da0fe5 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{47dcb8b 4974:com.samsung.android.providers.context/u0a7}
,01-27 16:49:50.322  3465  3859 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,01-27 16:49:50.322  3465  3869 E ConnectivityService: updateNetworkInfo()
01-27 16:49:50.322  3465  3869 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
,01-27 16:49:50.322  3465  3465 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
01-27 16:49:50.322  3465  3560 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
01-27 16:49:50.322  3465  3560 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false, mScanRequestedInConnected = false
01-27 16:49:50.322  3465  3560 D WifiDisplayController: disconnect
01-27 16:49:50.322  3465  3560 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,01-27 16:49:50.332  3465  3560 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,01-27 16:49:50.332  3465  3560 I WifiDisplayAdapter: onP2pDisconnected
01-27 16:49:50.332  3465  3560 D IpRemoteDisplayController: disconnectWfdBridgeServer
01-27 16:49:50.332  3465  3560 D IpRemoteDisplayController: WfdBridgeServer is already null
01-27 16:49:50.332  3950  3950 D WifiP2pController: onReceive android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,01-27 16:49:50.342  3950  3950 D SoundPathController: onReceive - android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,01-27 16:49:50.342  3950  3950 D ApMirroringController: onReceive android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,01-27 16:49:50.342  3950  3950 D AllShareCastTile: onReceive : android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,01-27 16:49:50.342  3465  3483 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
01-27 16:49:50.342  3950  3950 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,01-27 16:49:50.352  3465  3538 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4cebaba u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{edfb6ac 9833:com.samsung.android.app.FileShareClient/5005}
,01-27 16:49:50.352  3465  3538 D ActivityManager:  getDeferredInfo final delay 80
,01-27 16:49:50.352  9833  9833 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,01-27 16:49:50.352  9833  9833 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
01-27 16:49:50.352  9833  9833 D FileShare-Client: Outbound.stopDelayTimer - 
,01-27 16:49:50.362  3465  4382 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4cebaba u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ee79198 9847:com.samsung.android.app.FileShareServer/5005}
,01-27 16:49:50.372  9847  9847 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,01-27 16:49:50.372  9847  9847 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,01-27 16:49:50.372  9847  9847 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
01-27 16:49:50.372  9804  9804 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,01-27 16:49:50.372  9804  9804 I wpa_supplicant: Scan aborted because the firmware maybe busy.
01-27 16:49:50.372  9804  9804 I wpa_supplicant: Therefore we will repeat the scan command after 1 seconds.
01-27 16:49:50.372  9804  9804 I wpa_supplicant: wlan0: Setting scan request: 1 sec 0 usec
01-27 16:49:50.372  3465  3860 I WifiStateMachine: mWifiNative.bssFlush()
01-27 16:49:50.372  3465  3860 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,01-27 16:49:50.382  9804  9804 I wpa_supplicant: P2P: Set Samsung Discovery Icon = 256
,01-27 16:49:50.382  9804  9804 I wpa_supplicant: P2P: Set Samsung Discovery name = 
,01-27 16:49:50.382  3465  3860 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,01-27 16:49:50.382  9588  9588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,01-27 16:49:50.392  4302  4312 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,01-27 16:49:50.392  9588  9588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,01-27 16:49:50.412  3465  3859 E WifiP2pService: Failed to set my phone number info into probe response
,01-27 16:49:50.422  3465  3859 D WifiNative-p2p0: p2pGetDeviceAddress
,01-27 16:49:50.422  3465  3859 D WifiNative-p2p0: p2pGetDeviceAddress returning 4e:66:41:a9:a3:f3
,01-27 16:49:50.422  3465  3859 D WifiP2pService: DeviceAddress: 4e:a3:f3
,01-27 16:49:50.422  3465  3560 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: [Phone] Samsung Galaxy S7
01-27 16:49:50.422  3465  3560 D WifiDisplayController:  deviceAddress: 4e:66:41:a9:a3:f3
01-27 16:49:50.422  3465  3560 D WifiDisplayController:  primary type: 10-0050F204-5
01-27 16:49:50.422  3465  3560 D WifiDisplayController:  secondary type: null
01-27 16:49:50.422  3465  3560 D WifiDisplayController:  wps: 0
01-27 16:49:50.422  3465  3560 D WifiDisplayController:  grpcapab: 0
01-27 16:49:50.422  3465  3560 D WifiDisplayController:  devcapab: 0
01-27 16:49:50.422  3465  3560 D WifiDisplayController:  status: 3
01-27 16:49:50.422  3465  3560 D WifiDisplayController:  wfdInfo: null
01-27 16:49:50.422  3465  3560 D WifiDisplayController:  groupownerAddress: null
01-27 16:49:50.422  3465  3560 D WifiDisplayController:  GOdeviceName: null
01-27 16:49:50.422  3465  3560 D WifiDisplayController:  interfaceAddress: 
01-27 16:49:50.422  3465  3560 D WifiDisplayController:  SConnectInfo : null
01-27 16:49:50.422  3465  3560 D WifiDisplayController:  contactInfoHash : null
01-27 16:49:50.422  3465  3560 D WifiDisplayController:  ssDevInfo : 0
01-27 16:49:50.422  3465  3560 D WifiDisplayController:  iconIdx : 0
,01-27 16:49:50.432  3465  3859 D WifiP2pService: sending p2p persistent groups changed broadcast
,01-27 16:49:50.462  3465  3538 D ActivityManager:  getDeferredInfo final delay 80
,01-27 16:49:50.472  3465  3859 D WifiP2pService: InactiveState
,01-27 16:49:50.472  3465  3859 D WifiP2pService: InactiveState{ what=143376 }
01-27 16:49:50.472  3465  3859 D WifiP2pService: P2pEnabledState{ what=143376 }
,01-27 16:49:50.472  9804  9804 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,01-27 16:49:50.472  3465  3859 D WifiP2pService: InactiveState{ what=143376 }
,01-27 16:49:50.472  3465  3859 D WifiP2pService: P2pEnabledState{ what=143376 }
,01-27 16:49:50.552  3465  3538 D ActivityManager:  getDeferredInfo final delay 80
,01-27 16:49:50.632  3465  3538 D ActivityManager:  getDeferredInfo final delay 0
,01-27 16:49:50.652  3465  3538 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{12d4cd8 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a857df1 9859:com.policydm/1000}
,01-27 16:49:50.652  9859  9859 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(51/onReceive)] RegistrationReceiver onReceive! action = android.net.conn.CONNECTIVITY_CHANGE
,01-27 16:49:50.662  3465  4487 D ActivityManager:  getDeferredInfo final delay 0
,01-27 16:49:50.682  3465  4487 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{12d4cd8 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3b49439 6759:com.wssyncmldm/1000}
,01-27 16:49:50.692  3465  4487 D ActivityManager:  getDeferredInfo final delay 0
,01-27 16:49:50.702  3465  4487 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{12d4cd8 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{23f5e8f 6866:com.samsung.fresco.logging/5015}
,01-27 16:49:50.702  3465  4382 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,01-27 16:49:50.702  3465  4059 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,01-27 16:49:50.712  3465  4487 D ActivityManager:  getDeferredInfo final delay 0
,01-27 16:49:50.722  3465  4487 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{12d4cd8 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{aec1e46 7316:com.sec.spp.push/u0a39}
,01-27 16:49:50.722  7316  7316 E SPPClientService: [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
01-27 16:49:50.722  7316  7316 E SPPClientService: [SystemStateMoniter] Current Time : 216822
,01-27 16:49:50.722  7316  7316 E SPPClientService: [SystemStateMoniter] No Connect : true
,01-27 16:49:50.732  3465  4487 D ActivityManager:  getDeferredInfo final delay 300
,01-27 16:49:50.742  7316  9917 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,01-27 16:49:51.032  3465  3538 D ActivityManager:  getDeferredInfo final delay 0
,01-27 16:49:51.052  3465  3538 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{12d4cd8 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{831919a 4781:android.process.media/u0a48}
,01-27 16:49:51.062  4781  4781 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,01-27 16:49:51.062  3465  4489 D ActivityManager:  getDeferredInfo final delay 0
,01-27 16:49:51.102  9918  9918 E Zygote  : v2
01-27 16:49:51.102  9918  9918 I libpersona: KNOX_SDCARD checking this for 1000
01-27 16:49:51.102  9918  9918 I libpersona: KNOX_SDCARD not a persona
,01-27 16:49:51.102  9918  9918 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,01-27 16:49:51.102  9918  9918 E Zygote  : accessInfo : 0
,01-27 16:49:51.102  3465  4489 I ActivityManager: Start proc 9918:com.samsung.android.SettingsReceiver/1000 for broadcast-5 com.samsung.android.SettingsReceiver/.SettingsIntentReceiver
,01-27 16:49:51.142  9918  9918 D TimaKeyStoreProvider: TimaSignature is unavailable
01-27 16:49:51.142  9918  9918 D ActivityThread: Added TimaKeyStore provider
,01-27 16:49:51.162  3465  4403 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{12d4cd8 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6ae90c8 9918:com.samsung.android.SettingsReceiver/1000}
,01-27 16:49:51.172  9918  9918 W ResourcesManager: getTopLevelResources: /system/priv-app/SettingsReceiver/SettingsReceiver.apk / 1.0 running in com.samsung.android.SettingsReceiver rsrc of package com.samsung.android.SettingsReceiver
,01-27 16:49:51.172  3465  3484 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,01-27 16:49:51.172  9918  9918 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,01-27 16:49:51.182  9918  9918 D ResourcesManager: For user 0 new overlays fetched Null
,01-27 16:49:51.182  9918  9918 I InjectionManager: Inside getClassLibPath caller 
,01-27 16:49:51.192  9918  9918 W System  : ClassLoader referenced unknown path: /system/priv-app/SettingsReceiver/lib/arm64
,01-27 16:49:51.202  9918  9918 D InjectionManager: InjectionManager
01-27 16:49:51.202  9918  9918 D InjectionManager: fillFeatureStoreMap com.samsung.android.SettingsReceiver
,01-27 16:49:51.202  9918  9918 I InjectionManager: Constructor com.samsung.android.SettingsReceiver, Feature store :{}
01-27 16:49:51.202  9918  9918 I InjectionManager: featureStore :{}
,01-27 16:49:51.202  9918  9918 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in com.samsung.android.SettingsReceiver rsrc of package com.android.settings
,01-27 16:49:51.212  9918  9918 D ResourcesManager: For user 0 new overlays fetched Null
,01-27 16:49:51.212  9918  9918 E ActivityThread: Failed to find provider info for com.myscript.atk.rmc
,01-27 16:49:51.222  3465  4382 D ActivityManager:  getDeferredInfo final delay 0
,01-27 16:49:51.242  9931  9931 E Zygote  : v2
01-27 16:49:51.242  9931  9931 I libpersona: KNOX_SDCARD checking this for 10064
01-27 16:49:51.242  9931  9931 I libpersona: KNOX_SDCARD not a persona
,01-27 16:49:51.242  9931  9931 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,01-27 16:49:51.252  9931  9931 E Zygote  : accessInfo : 0
01-27 16:49:51.252  9931  9931 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.android.themestore 
01-27 16:49:51.252  3465  4382 I ActivityManager: Start proc 9931:com.samsung.android.themestore/u0a64 for broadcast-5 com.samsung.android.themestore/.manager.autoSelfUpgradeService.AutoSelfUpgradeReceiver
,01-27 16:49:51.252  3465  4382 I ActivityManager: Killing 8852:com.samsung.android.sm.devicesecurity/5012 (adj 15): DHA:empty #33
,01-27 16:49:51.282  3465  4331 D ActivityManager: cleanUpApplicationRecord -- 8852
,01-27 16:49:51.282  3465  4331 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sm.devicesecurity, Auto Run ON
,01-27 16:49:51.282  9931  9931 D TimaKeyStoreProvider: TimaSignature is unavailable
01-27 16:49:51.282  9931  9931 D ActivityThread: Added TimaKeyStore provider
,01-27 16:49:51.302  3465  4042 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{12d4cd8 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b20c561 9931:com.samsung.android.themestore/u0a64}
,01-27 16:49:51.312  9931  9931 W ResourcesManager: getTopLevelResources: /system/priv-app/ThemeStore_3xh/ThemeStore_3xh.apk / 1.0 running in com.samsung.android.themestore rsrc of package com.samsung.android.themestore
,01-27 16:49:51.312  3465  3483 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
01-27 16:49:51.312  9931  9931 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,01-27 16:49:51.322  9931  9931 D ResourcesManager: For user 0 new overlays fetched Null
,01-27 16:49:51.322  3465  3818 V AlarmManager: Expired Alarm result :4
,01-27 16:49:51.332  9931  9931 I InjectionManager: Inside getClassLibPath caller 
,01-27 16:49:51.342  9931  9931 W System  : ClassLoader referenced unknown path: /system/priv-app/ThemeStore_3xh/lib/arm64
,01-27 16:49:51.362  9931  9931 D a       : Exist Config : false
,01-27 16:49:51.362  9931  9931 D a       : getMcc
,01-27 16:49:51.362  9931  9931 D ai      : isQaMode
,01-27 16:49:51.372  9931  9931 D a       : getMnc
01-27 16:49:51.372  9931  9931 D a       : getCsc
,01-27 16:49:51.372  9931  9931 D a       : getSystemCountryCode
01-27 16:49:51.372  9931  9931 D a       : getImei
,01-27 16:49:51.372  9804  9804 I wpa_supplicant: P2P: Current p2p state = IDLE
,01-27 16:49:51.372  9804  9804 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,01-27 16:49:51.382  9931  9931 D ai      : getMd5HashString
,01-27 16:49:51.382  9931  9931 D ai      : getSha256HashString
,01-27 16:49:51.382  9931  9931 D a       : getMsisdn
,01-27 16:49:51.392  4302  4545 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,01-27 16:49:51.392  9931  9931 D a       : getModelName
,01-27 16:49:51.392  9931  9931 D a       : getVirtualModelName
01-27 16:49:51.392  9931  9931 D a       : getAndroidSDKVersion
,01-27 16:49:51.392  9931  9931 D a       : getLanguageCode
01-27 16:49:51.392  9931  9931 D a       : getCountryCode
,01-27 16:49:51.402  9931  9931 D a       : getNetworkType
,01-27 16:49:51.412  9931  9931 D t       : isSupportedAodSystemFeature
,01-27 16:49:51.412  9931  9931 D a       : isLogPrintMode
,01-27 16:49:51.412  9931  9931 D ai      : isQaMode
,01-27 16:49:51.422  9931  9931 D a       : getVerName
,01-27 16:49:51.422  9931  9931 D a       : getVerCode
,01-27 16:49:51.422  9931  9931 D a       : getPackageName
01-27 16:49:51.422  9931  9931 D a       : getAutoUpgradeInterval
,01-27 16:49:51.422  9931  9931 D a       : loadCountrySearchEx
,01-27 16:49:51.442  9931  9931 I a       : voCountrySearchEx loaded.
,01-27 16:49:51.442  9931  9931 I a       : # initConfig Time : 86
01-27 16:49:51.442  9931  9931 I a       : ● MCCNNC : 260 0
01-27 16:49:51.442  9931  9931 I a       : ● Model : SM-G930F_TM
01-27 16:49:51.442  9931  9931 I a       : ● MyApp Vertion : 1.03.22(20160524)
01-27 16:49:51.442  9931  9931 I a       : ● OS Vertion : 23
,01-27 16:49:51.472  9931  9931 D InjectionManager: InjectionManager
01-27 16:49:51.472  9931  9931 D InjectionManager: fillFeatureStoreMap com.samsung.android.themestore
,01-27 16:49:51.472  9931  9931 I InjectionManager: Constructor com.samsung.android.themestore, Feature store :{}
01-27 16:49:51.472  9931  9931 I InjectionManager: featureStore :{}
,01-27 16:49:51.472  9931  9931 D AutoSelfUpgradeReceiver: onReceive() android.net.conn.CONNECTIVITY_CHANGE
,01-27 16:49:51.522  3465  4226 D ActivityManager:  getDeferredInfo final delay 0
,01-27 16:49:51.522  3465  4226 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{12d4cd8 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ae46917 8255:com.samsung.android.scloud:contentsync/5009}
,01-27 16:49:51.532  8255  8255 I [SC]DetectorReceiver: onReceive [android.net.conn.CONNECTIVITY_CHANGE]
01-27 16:49:51.532  8255  8255 I [SC]CloudManager: requestInit
,01-27 16:49:51.532  8255  8255 I [SC]Utils: folder : cachecreate fail, try again.
,01-27 16:49:51.532  8255  8255 I [SC]Utils: folder : cache create fail.
01-27 16:49:51.532  8255  8255 I [SC]Utils: folder : thumbnailcreate fail, try again.
01-27 16:49:51.532  8255  8255 I [SC]Utils: folder : thumbnail create fail.
01-27 16:49:51.532  8255  8255 I [SC]Utils: folder : sharecreate fail, try again.
01-27 16:49:51.532  8255  8255 I [SC]Utils: folder : share create fail.
01-27 16:49:51.532  8255  8255 I [SC]Utils: folder : scratchcreate fail, try again.
,01-27 16:49:51.532  8255  8255 I [SC]Utils: folder : scratch create fail.
,01-27 16:49:51.532  8255  8255 I [SC]Utils: folder : eventSynccreate fail, try again.
,01-27 16:49:51.532  8255  8255 I [SC]Utils: folder : eventSync create fail.
,01-27 16:49:51.542  7358  7369 I SA      : [SCU] isHaveSA() - false
01-27 16:49:51.542  7358  7369 I SA      : [OCP] Samsung account is not Signed-in
,01-27 16:49:51.552  7358  7369 I SA      : [OCP] Delete DB (TNC data)
,01-27 16:49:51.552  8255  8255 I [SC]CommonUtil: Samsung Account Not Logged in
,01-27 16:49:51.552  3465  4487 D ActivityManager:  getDeferredInfo final delay 0
,01-27 16:49:51.552  3465  3977 I ActivityManager: Killing 9131:com.samsung.android.themecenter/1000 (adj 15): DHA:empty #33
,01-27 16:49:51.592  9951  9951 E Zygote  : v2
01-27 16:49:51.592  9951  9951 I libpersona: KNOX_SDCARD checking this for 5011
01-27 16:49:51.592  9951  9951 I libpersona: KNOX_SDCARD not a persona
,01-27 16:49:51.602  9951  9951 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,01-27 16:49:51.602  3465  4487 I ActivityManager: Start proc 9951:com.samsung.android.coreapps/5011 for broadcast-5 com.samsung.android.coreapps/.easysignup.receiver.NetworkStateListener
01-27 16:49:51.602  9951  9951 E Zygote  : accessInfo : 0
,01-27 16:49:51.602  9951  9951 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.coreapps 
,01-27 16:49:51.622  3465  4225 D ActivityManager: cleanUpApplicationRecord -- 9131
,01-27 16:49:51.622  3465  4225 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.themecenter, Auto Run ON
,01-27 16:49:51.642  9951  9951 D TimaKeyStoreProvider: TimaSignature is unavailable
01-27 16:49:51.642  9951  9951 D ActivityThread: Added TimaKeyStore provider
,01-27 16:49:51.662  3465  4382 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{12d4cd8 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{67ff174 9951:com.samsung.android.coreapps/5011}
,01-27 16:49:51.672  9951  9951 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in com.samsung.android.coreapps rsrc of package com.samsung.android.coreapps
,01-27 16:49:51.672  3465  3484 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
01-27 16:49:51.672  9951  9951 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,01-27 16:49:51.672  9951  9951 D ResourcesManager: For user 0 new overlays fetched Null
,01-27 16:49:51.682  9951  9951 I InjectionManager: Inside getClassLibPath caller 
,01-27 16:49:51.692  9951  9951 W System  : ClassLoader referenced unknown path: /system/app/CoreApps/lib/arm64
,01-27 16:49:51.712  9951  9951 D CoreApps: SEC_LOG - true
,01-27 16:49:51.772  9951  9951 E GooglePlayServicesUtil: The Google Play services resources were not found. Check your project configuration to ensure that the resources are included.
,01-27 16:49:51.972  9951  9951 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Epic_Common/SecMms_Epic_Common.apk / 1.0 running in com.samsung.android.coreapps rsrc of package com.android.mms
,01-27 16:49:51.982  9951  9951 D ResourcesManager: For user 0 new overlays fetched Null
,01-27 16:49:51.982  9951  9951 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.samsung.android.coreapps rsrc of package com.google.android.talk
,01-27 16:49:51.992  9951  9951 D ResourcesManager: For user 0 new overlays fetched Null
,01-27 16:49:52.002  9951  9951 D InjectionManager: InjectionManager
01-27 16:49:52.002  9951  9951 D InjectionManager: fillFeatureStoreMap com.samsung.android.coreapps
,01-27 16:49:52.002  9951  9951 I InjectionManager: Constructor com.samsung.android.coreapps, Feature store :{}
01-27 16:49:52.002  9951  9951 I InjectionManager: featureStore :{}
,01-27 16:49:52.012  3465  4331 D ActivityManager:  getDeferredInfo final delay 0
,01-27 16:49:52.022  3465  4331 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{12d4cd8 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{67ff174 9951:com.samsung.android.coreapps/5011}
,01-27 16:49:52.032  3465  4042 D ActivityManager:  getDeferredInfo final delay 0
,01-27 16:49:52.042  3465  4042 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{12d4cd8 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{67ff174 9951:com.samsung.android.coreapps/5011}
,01-27 16:49:52.052  3465  4042 D ActivityManager:  getDeferredInfo final delay 0
,01-27 16:49:52.052  3465  4042 I ActivityManager: Killing 9144:com.samsung.android.scloud/5009 (adj 15): DHA:empty #33
,01-27 16:49:52.062  3465  4042 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{12d4cd8 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{370da43 4847:com.microsoft.skydrive/u0a124}
,01-27 16:49:52.062  3465  3483 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,01-27 16:49:52.082  3465  3973 W IntentResolver: resolveIntent failed: found match, but none with CATEGORY_DEFAULT
,01-27 16:49:52.082  3465  4382 D ActivityManager: cleanUpApplicationRecord -- 9144
,01-27 16:49:52.082  3465  4382 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.scloud, Auto Run ON
,01-27 16:49:52.092  3465  4225 D ActivityManager:  getDeferredInfo final delay 300
,01-27 16:49:52.392  3465  3538 D ActivityManager:  getDeferredInfo final delay 0
,01-27 16:49:52.432  9979  9979 E Zygote  : v2
01-27 16:49:52.432  9979  9979 I libpersona: KNOX_SDCARD checking this for 10129
01-27 16:49:52.432  9979  9979 I libpersona: KNOX_SDCARD not a persona
,01-27 16:49:52.432  9979  9979 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,01-27 16:49:52.432  9979  9979 E Zygote  : accessInfo : 0
01-27 16:49:52.432  9979  9979 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.photos 
,01-27 16:49:52.442  3465  3538 I ActivityManager: Start proc 9979:com.google.android.apps.photos/u0a129 for broadcast-5 com.google.android.apps.photos/.actionqueue.SystemReceiver
,01-27 16:49:52.442  3465  3858 D NetworkPolicy: isUidForegroundLocked: 10129, mScreenOn: true, uidstate: -1, mProxSensorScreenOff: false
,01-27 16:49:52.472  9979  9979 D TimaKeyStoreProvider: TimaSignature is unavailable
01-27 16:49:52.472  9979  9979 D ActivityThread: Added TimaKeyStore provider
,01-27 16:49:52.492  3465  4226 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{12d4cd8 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a6f0ee3 9979:com.google.android.apps.photos/u0a129}
,01-27 16:49:52.492  3465  3858 D NetworkPolicy: isUidForegroundLocked: 10129, mScreenOn: true, uidstate: 11, mProxSensorScreenOff: false
,01-27 16:49:52.502  9979  9979 W ResourcesManager: getTopLevelResources: /system/app/Photos/Photos.apk / 1.0 running in com.google.android.apps.photos rsrc of package com.google.android.apps.photos
,01-27 16:49:52.502  3465  3977 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
01-27 16:49:52.502  9979  9979 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,01-27 16:49:52.512  9979  9979 D ResourcesManager: For user 0 new overlays fetched Null
,01-27 16:49:52.512  9979  9979 I InjectionManager: Inside getClassLibPath caller 
,01-27 16:49:52.532  9979  9979 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm64
,01-27 16:49:52.702  3465  3818 V AlarmManager: Expired Alarm result :4
,01-27 16:49:52.712  3162  3711 D EnterpriseController: netId is 0
,01-27 16:49:52.712  3162  3711 D Netd    : getNetworkForDns: using netid 0 for uid 10019
,01-27 16:49:52.712  3465  4485 V AlarmManager:  remove PendingIntent] PendingIntent{c03bf99: PendingIntentRecord{3c7b89f com.google.android.gms broadcastIntent}}
,01-27 16:49:52.742  3465  3538 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b4f625e u0 com.google.android.gcm.DISCONNECTED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3655c31 8494:com.google.android.talk/u0a112}
,01-27 16:49:52.762  9979  9979 W ResourcesManager: getTopLevelResources: /system/app/Photos/Photos.apk / 1.0 running in com.google.android.apps.photos rsrc of package com.google.android.apps.photos
,01-27 16:49:52.842  9979  9979 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,01-27 16:49:52.942  9979  9979 D InjectionManager: InjectionManager
01-27 16:49:52.942  9979  9979 D InjectionManager: fillFeatureStoreMap com.google.android.apps.photos
01-27 16:49:52.942  9979  9979 I InjectionManager: Constructor com.google.android.apps.photos, Feature store :{}
01-27 16:49:52.942  9979  9979 I InjectionManager: featureStore :{}
,01-27 16:49:52.962  3465  3538 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b94c8d1 u0 com.google.android.apps.photos.actionqueue.INTERNAL_ACTION qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a6f0ee3 9979:com.google.android.apps.photos/u0a129}
,01-27 16:49:53.012  3465  4059 D ActivityManager:  getDeferredInfo final delay 0
,01-27 16:49:53.022  3465  4059 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{12d4cd8 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a6f0ee3 9979:com.google.android.apps.photos/u0a129}
,01-27 16:49:53.042  3465  4059 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{62f5f36 u0 com.google.android.apps.photos.jobqueue.EXECUTE_JOBS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a6f0ee3 9979:com.google.android.apps.photos/u0a129}
,01-27 16:49:53.052  3465  4059 D ActivityManager:  getDeferredInfo final delay 300
,01-27 16:49:53.072  3465  4059 I ActivityManager: Killing 9165:com.samsung.android.bbc.bbcagent/1000 (adj 15): DHA:empty #33
,01-27 16:49:53.102  3465  4485 D ActivityManager: cleanUpApplicationRecord -- 9165
,01-27 16:49:53.102  3465  4485 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.bbc.bbcagent, Auto Run ON
,01-27 16:49:53.152  3162  3708 D Netd    : Iface wlan0 link up
,01-27 16:49:53.152  9804  9804 I wpa_supplicant: nl80211: Received scan results (24 BSSes)
,01-27 16:49:53.152  4990  9374 D PdnController: Interface Changed wlan0 link up
01-27 16:49:53.152  3465  3542 D Tethering: interfaceLinkStateChanged wlan0, true
01-27 16:49:53.152  3465  3542 D Tethering: interfaceStatusChanged wlan0, true
,01-27 16:49:53.162  9804  9804 I wpa_supplicant: autoscan_samsung_exponential_notify_scan : scan_interval = 8
01-27 16:49:53.162  9804  9804 I wpa_supplicant: autoscan: autoscan_notify_scan, scan_interval = 8
01-27 16:49:53.162  9804  9804 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
01-27 16:49:53.162  9804  9804 I wpa_supplicant:    allow  - level is under -85dBm [-59] or selected nid [-1] [3]
,01-27 16:49:53.162  9804  9804 I wpa_supplicant:  selected from pick network BSS F4.99.3E ssid='NG700' et= 090,gp=03,cu=987654321,sc=987654321
01-27 16:49:53.162  9804  9804 I wpa_supplicant:    allow  - level is under -85dBm [-59] or selected nid [-1] [3]
,01-27 16:49:53.162  9804  9804 I wpa_supplicant: wlan0: Trying to associate with f4:f2:6d:22:99:3e (SSID='NG700' freq=2437 MHz level=-59) 
,01-27 16:49:53.192  3465  3860 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,01-27 16:49:53.202  3465  3465 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.SCAN_RESULTS
,01-27 16:49:53.212  3465  3538 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8bc9fa4 u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b3411c4 3950:com.android.systemui/u0a62}
,01-27 16:49:53.222  9588  9588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,01-27 16:49:53.252  9804  9804 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,01-27 16:49:53.262  3162  3708 D Netd    : Iface wlan0 link up
01-27 16:49:53.262  3162  3708 D Netd    : Iface wlan0 link up
01-27 16:49:53.262  3162  3708 D Netd    : Iface wlan0 link up
,01-27 16:49:53.262  4990  5007 D PdnController: Interface Changed wlan0 link up
,01-27 16:49:53.262  3465  3542 D Tethering: interfaceLinkStateChanged wlan0, true
01-27 16:49:53.262  3465  3542 D Tethering: interfaceStatusChanged wlan0, true
,01-27 16:49:53.262  4990  5002 D PdnController: Interface Changed wlan0 link up
,01-27 16:49:53.262  3465  3542 D Tethering: interfaceLinkStateChanged wlan0, true
01-27 16:49:53.262  3465  3542 D Tethering: interfaceStatusChanged wlan0, true
01-27 16:49:53.262  9804  9804 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
01-27 16:49:53.262  9804  9804 I wpa_supplicant: wlan0: WPA: RX message 1 of 4-Way Handshake from F4.99.3E (ver=2)
01-27 16:49:53.272  4990  5473 D PdnController: Interface Changed wlan0 link up
,01-27 16:49:53.272  9804  9804 I wpa_supplicant: wlan0: WPA: Sending EAPOL-Key 2/4
,01-27 16:49:53.272  3465  3542 D Tethering: interfaceLinkStateChanged wlan0, true
,01-27 16:49:53.272  3465  3542 D Tethering: interfaceStatusChanged wlan0, true
,01-27 16:49:53.282  3465  3860 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,01-27 16:49:53.282  3465  3860 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,01-27 16:49:53.282  9588  9588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,01-27 16:49:53.292  9588  9588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,01-27 16:49:53.292  9804  9804 I wpa_supplicant: wlan0: WPA: RX message 3 of 4-Way Handshake from F4.99.3E (ver=2)
,01-27 16:49:53.302  9804  9804 I wpa_supplicant: wlan0: WPA: Sending EAPOL-Key 4/4
,01-27 16:49:53.302  9804  9804 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,01-27 16:49:53.302  9804  9804 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=3 id_str=]
,01-27 16:49:53.302  9804  9804 I wpa_supplicant: Blacklist: Clear (temp) 
01-27 16:49:53.302  3162  3708 D Netd    : Iface wlan0 link up
,01-27 16:49:53.302  4990  9374 D PdnController: Interface Changed wlan0 link up
,01-27 16:49:53.302  3465  3542 D Tethering: interfaceLinkStateChanged wlan0, true
01-27 16:49:53.302  3465  3542 D Tethering: interfaceStatusChanged wlan0, true
,01-27 16:49:53.312  3465  3860 D WifiNative-wlan0: callSECApiVoid - ID [50]
,01-27 16:49:53.322  3465  3860 V AlarmManager:  remove PendingIntent] PendingIntent{fa42cb5: PendingIntentRecord{7845f4a android broadcastIntent}}
,01-27 16:49:53.322  3465  3860 D WifiNetworkAgent: NetworkAgent: Registering NetworkAgent
,01-27 16:49:53.322  3465  3465 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
,01-27 16:49:53.322  3465  3465 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
01-27 16:49:53.322  3465  3465 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
,01-27 16:49:53.322  3465  3867 I WifiHs20Service: Message received 5007
,01-27 16:49:53.322  3465  3465 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
01-27 16:49:53.322  3465  3869 E ConnectivityService: updateNetworkInfo()
01-27 16:49:53.322  3465  3860 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,01-27 16:49:53.322  3465  3869 D ConnectivityService: Got NetworkAgent Messenger
01-27 16:49:53.322  3465  3869 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
01-27 16:49:53.322  3465  3869 D ConnectivityService: NetworkAgent connected
,01-27 16:49:53.332  3950  4150 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
01-27 16:49:53.332  3162  3715 D CommandListener: Setting iface cfg
,01-27 16:49:53.332  4302  4302 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,01-27 16:49:53.342  3465  3538 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1621328 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{453d303 9792:com.sec.android.diagmonagent/1000}
,01-27 16:49:53.342  3465  3860 D WifiStateMachine: Start Dhcp Watchdog 2
01-27 16:49:53.342  9792  9792 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
01-27 16:49:53.342  9792  9792 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
01-27 16:49:53.342  9792  9792 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
,01-27 16:49:53.342  9792  9792 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,01-27 16:49:53.342  3465  3860 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,01-27 16:49:53.352  3465  4485 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1621328 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e533db5 6432:com.enhance.gameservice/u0a106}
,01-27 16:49:53.362  9588  9588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,01-27 16:49:53.362  3465  4485 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1621328 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{51370b9 9808:com.sec.knox.switcher/1000}
,01-27 16:49:53.362  9808  9808 I usagelog: received in receiver
01-27 16:49:53.362  9808  9808 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
,01-27 16:49:53.362  9808  9808 I KnoxUsageLogPro: premStatus:2
01-27 16:49:53.362  9808  9808 I KnoxUsageLogPro: isEulaShown : false
,01-27 16:49:53.362  9808  9808 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,01-27 16:49:53.372  3465  3538 D ActivityManager:  getDeferredInfo final delay 0
01-27 16:49:53.372  3465  3860 D WifiNetworkAgent: NetworkAgent: NetworkAgent fully connected
01-27 16:49:53.372  3465  3869 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]
01-27 16:49:53.372  3465  3869 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,01-27 16:49:53.382  3465  3538 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{12d4cd8 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b1960c8 4701:com.sec.android.daemonapp/u0a159}
,01-27 16:49:53.382  4701  4701 D [Weather Widget]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CFAAE09BFCA326403459399C53A4EE79DAC193CEB26509F8FF7498BE5251A746097407E81C28CD811D388C49D613C81F395B356AA489D29CB4C3BE983CCC84BA76AF507AA66A943348DF162DECA2A5A7DD]}
,01-27 16:49:53.382  4701  4701 D [Weather Widget]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CFE2E89F45594D9820F24D88E9AF210A78F9CD3967C07B6DE6AAB9923C4C53919020112019F4465EB3AA6FD266958B212E]}
,01-27 16:49:53.382  3465  3869 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,01-27 16:49:53.382  3465  3860 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,01-27 16:49:53.382  3950  4150 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,01-27 16:49:53.392  3465  3538 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1621328 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{db58cfe 9820:com.samsung.android.sm.policy/u0a135}
,01-27 16:49:53.402  3465  4489 D ActivityManager:  getDeferredInfo final delay 0
,01-27 16:49:53.402  9588  9588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,01-27 16:49:53.412  3465  4489 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{12d4cd8 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6283eb1 8868:com.sec.android.app.samsungapps/u0a14}
,01-27 16:49:53.422  3465  4331 D ActivityManager:  getDeferredInfo final delay 0
,01-27 16:49:53.432  3465  4331 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{cd01738 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{453d303 9792:com.sec.android.diagmonagent/1000}
,01-27 16:49:53.432  9792  9792 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,01-27 16:49:53.432  9792  9792 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
,01-27 16:49:53.432  9792  9792 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,01-27 16:49:53.442  3465  4331 D ActivityManager:  getDeferredInfo final delay 0
,01-27 16:49:53.452  3465  4331 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{cd01738 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{51370b9 9808:com.sec.knox.switcher/1000}
,01-27 16:49:53.452  9808  9808 I usagelog: received in receiver
01-27 16:49:53.452  9808  9808 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
,01-27 16:49:53.452  9808  9808 I KnoxUsageLogPro: premStatus:2
01-27 16:49:53.452  9808  9808 I KnoxUsageLogPro: isEulaShown : false
01-27 16:49:53.452  9808  9808 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,01-27 16:49:53.452  3465  4331 D ActivityManager:  getDeferredInfo final delay 0
,01-27 16:49:53.462  3465  4331 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{cd01738 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{db58cfe 9820:com.samsung.android.sm.policy/u0a135}
,01-27 16:49:53.472  3465  4331 D ActivityManager:  getDeferredInfo final delay 0
,01-27 16:49:53.492 10006 10006 E Zygote  : v2
01-27 16:49:53.492 10006 10006 I libpersona: KNOX_SDCARD checking this for 1000
,01-27 16:49:53.492 10006 10006 I libpersona: KNOX_SDCARD not a persona
01-27 16:49:53.492 10006 10006 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,01-27 16:49:53.492 10006 10006 E Zygote  : accessInfo : 0
,01-27 16:49:53.492  3465  3860 E WifiNative-wlan0: do suspend false
,01-27 16:49:53.492  3465  4331 I ActivityManager: Start proc 10006:com.samsung.android.securitylogagent/1000 for broadcast-5 com.samsung.android.securitylogagent/.receivers.NetworkReceiver
,01-27 16:49:53.502  3465  3859 D WifiP2pService: InactiveState{ what=143375 }
,01-27 16:49:53.502  3465  3859 D WifiP2pService: P2pEnabledState{ what=143375 }
,01-27 16:49:53.522 10006 10006 D TimaKeyStoreProvider: TimaSignature is unavailable
01-27 16:49:53.522 10006 10006 D ActivityThread: Added TimaKeyStore provider
,01-27 16:49:53.522 10018 10018 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,01-27 16:49:53.532 10018 10018 I dhcpcd  : version 5.5.6 starting
,01-27 16:49:53.532 10018 10018 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,01-27 16:49:53.532  3465  3973 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{914fa29 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b0f401f 10006:com.samsung.android.securitylogagent/1000}
,01-27 16:49:53.542 10006 10006 W ResourcesManager: getTopLevelResources: /system/app/SecurityLogAgent/SecurityLogAgent.apk / 1.0 running in com.samsung.android.securitylogagent rsrc of package com.samsung.android.securitylogagent
,01-27 16:49:53.542  3465  4416 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
01-27 16:49:53.542 10006 10006 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,01-27 16:49:53.542 10006 10006 D ResourcesManager: For user 0 new overlays fetched Null
,01-27 16:49:53.552 10006 10006 I InjectionManager: Inside getClassLibPath caller 
,01-27 16:49:53.552 10006 10006 W System  : ClassLoader referenced unknown path: /system/app/SecurityLogAgent/lib/arm64
,01-27 16:49:53.552 10006 10006 D InjectionManager: InjectionManager
,01-27 16:49:53.552 10006 10006 D InjectionManager: fillFeatureStoreMap com.samsung.android.securitylogagent
01-27 16:49:53.562 10006 10006 I InjectionManager: Constructor com.samsung.android.securitylogagent, Feature store :{}
01-27 16:49:53.562 10006 10006 I InjectionManager: featureStore :{}
,01-27 16:49:53.562 10006 10006 D SecurityLogAgent: NetworkReceiver : Network Change Receiver Is Called
01-27 16:49:53.562 10006 10006 D SecurityLogAgent: NetworkReceiver : Wifi_state is 3
,01-27 16:49:53.572 10006 10006 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,01-27 16:49:53.572 10006 10006 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
01-27 16:49:53.572 10006 10006 D SecurityLogAgent: StateMachine : Current State = 1
,01-27 16:49:53.572  3465  3973 D ActivityManager:  getDeferredInfo final delay 0
,01-27 16:49:53.582  3465  3973 I ActivityManager: Killing 9177:com.google.android.apps.docs/u0a93 (adj 15): DHA:empty #33
,01-27 16:49:53.592 10018 10018 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,01-27 16:49:53.602 10018 10018 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
01-27 16:49:53.602 10018 10018 I dhcpcd  : bssid match
01-27 16:49:53.602 10018 10018 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
,01-27 16:49:53.612  3465  4059 D ActivityManager: cleanUpApplicationRecord -- 9177
,01-27 16:49:53.612  3465  4059 D ActivityManager: isAutoRunBlockedApp:: com.google.android.apps.docs, Auto Run ON
,01-27 16:49:53.672 10018 10018 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,01-27 16:49:53.722 10018 10018 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
,01-27 16:49:53.722  3465  3869 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,01-27 16:49:54.112  3465  3859 D WifiP2pService: InactiveState{ what=143375 }
01-27 16:49:54.112  3465  3859 D WifiP2pService: P2pEnabledState{ what=143375 }
,01-27 16:49:54.122  3465  3869 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,01-27 16:49:54.122  3465  3860 D WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,01-27 16:49:54.122  3465  3860 D WifiStateMachine: VerifyingLinkState enter
01-27 16:49:54.122  3465  3869 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]
,01-27 16:49:54.122  3950  4150 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,01-27 16:49:54.132  3465  3465 D WifiNotificationController: SHOW_NOTI_MESSAGE : 9, visible : false, ssid : "NG700", targetSSID : null, netId : -1, titleType : -1
,01-27 16:49:54.132  3465  3869 E ConnectivityService: updateNetworkInfo()
,01-27 16:49:54.142  3465  3869 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}, oldLp = null
01-27 16:49:54.142  3465  3869 D ConnectivityService: Adding iface wlan0 to network 503
,01-27 16:49:54.142  3465  3465 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
01-27 16:49:54.142  3465  3465 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,01-27 16:49:54.142  3465  3465 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
,01-27 16:49:54.142  3465  3867 I WifiHs20Service: Message received 5007
01-27 16:49:54.142  3465  3465 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
,01-27 16:49:54.152  3465  3885 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,01-27 16:49:54.152  3465  3885 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}
,01-27 16:49:54.152  3465  3885 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}
,01-27 16:49:54.152  3465  3885 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}
,01-27 16:49:54.152  3465  3885 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}
,01-27 16:49:54.152  3950  4150 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,01-27 16:49:54.162  4302  4302 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,01-27 16:49:54.172  3465  3538 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{201ef6c u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{453d303 9792:com.sec.android.diagmonagent/1000}
,01-27 16:49:54.172  3465  3885 I WifiManager: isCaptivePortalException
01-27 16:49:54.172  3465  3885 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
01-27 16:49:54.172  3465  3885 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
01-27 16:49:54.172  3465  3885 D WifiWatchdogStateMachine: 3Captive portal check should be processed whether SNS option is on or off.
01-27 16:49:54.172  3465  3885 D WifiWatchdogStateMachine.CaptivePortalHandler: [checkCaptivePortal] - callbackHandler=Handler (com.android.server.wifi.WifiWatchdogStateMachine$CaptivePortalHandler) {26d5ac1}
01-27 16:49:54.172  3465  3885 I WifiManager: isCaptivePortalException
01-27 16:49:54.172  3465  3885 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
01-27 16:49:54.172  3465  3885 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
,01-27 16:49:54.172  3465  3860 D WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to CONNECTED
01-27 16:49:54.172  3465  3869 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 503
01-27 16:49:54.172  9792  9792 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,01-27 16:49:54.182  9792  9792 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
01-27 16:49:54.182  9792  9792 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
,01-27 16:49:54.182  3465  3869 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,01-27 16:49:54.182  9792  9792 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,01-27 16:49:54.182  3465  3869 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
,01-27 16:49:54.182  3465  3869 E ConnectivityService: Unexpected mtu value: 0, wlan0
01-27 16:49:54.182  3465  3869 D ConnectivityService: Setting Dns servers for network 503 to [/192.168.1.1]
,01-27 16:49:54.192  3465  4485 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{201ef6c u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e533db5 6432:com.enhance.gameservice/u0a106}
,01-27 16:49:54.192  3465  3860 D SecContentProvider: insert(), uri = 2
,01-27 16:49:54.192  3465  3869 D NtpTrustedTime: currentTimeMillis() cache hit
01-27 16:49:54.192  3465  3869 V NetworkStats: updateIfacesLocked()
,01-27 16:49:54.192  3465  3869 V NetworkStats: performPollLocked(flags=0x1)
01-27 16:49:54.192  3465  3465 D WifiNotificationController: SHOW_NOTI_MESSAGE : 9, visible : false, ssid : "NG700", targetSSID : null, netId : -1, titleType : -1
,01-27 16:49:54.202  3465  3869 D NetworkStatsRecorder: entry.iface is null
,01-27 16:49:54.202  3465  3869 D NetworkStatsRecorder: entry.iface is null
01-27 16:49:54.202  3465  3869 D NetworkStatsRecorder: entry.iface is null
01-27 16:49:54.202  3465  3869 D NetworkStatsRecorder: entry.iface is null
01-27 16:49:54.202  3465  3869 D NtpTrustedTime: currentTimeMillis() cache hit
01-27 16:49:54.202  3465  3869 V NetworkStats: performPollLocked() took 5ms
,01-27 16:49:54.202  3465  4485 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{201ef6c u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{51370b9 9808:com.sec.knox.switcher/1000}
,01-27 16:49:54.202  9808  9808 I usagelog: received in receiver
01-27 16:49:54.202  9808  9808 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
01-27 16:49:54.202  9808  9808 I KnoxUsageLogPro: premStatus:2
,01-27 16:49:54.202  9808  9808 I KnoxUsageLogPro: isEulaShown : false
01-27 16:49:54.202  9808  9808 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,01-27 16:49:54.212  3465  3869 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,01-27 16:49:54.212  3465  3860 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
01-27 16:49:54.212  3465  3869 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]
01-27 16:49:54.212  3465  3869 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
01-27 16:49:54.212  3465  3869 D ConnectivityService: Not required to send intent.
,01-27 16:49:54.212  3465  3869 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = CONNECTING
01-27 16:49:54.212  3465  3869 E ConnectivityService: updateNetworkInfo()
01-27 16:49:54.212  3465  3869 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]
,01-27 16:49:54.212  3465  3860 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,01-27 16:49:54.222  3465  3869 V NetworkStats: updateIfacesLocked()
01-27 16:49:54.222  3465  3869 D NtpTrustedTime: currentTimeMillis() cache hit
01-27 16:49:54.222  3465  3869 V NetworkStats: performPollLocked(flags=0x1)
,01-27 16:49:54.222  3465  3869 D NetworkStatsRecorder: entry.iface is null
,01-27 16:49:54.222  3465  3869 D NetworkStatsRecorder: entry.iface is null
01-27 16:49:54.222  3465  3869 D NetworkStatsRecorder: entry.iface is null
01-27 16:49:54.222  3465  3869 D NtpTrustedTime: currentTimeMillis() cache hit
01-27 16:49:54.222  3465  3869 D NetworkStatsRecorder: entry.iface is null
01-27 16:49:54.222  3465  3869 V NetworkStats: performPollLocked() took 5ms
,01-27 16:49:54.232  3465  3465 I WifiTrafficPoller: evaluateTrafficStatsPolling
,01-27 16:49:54.232  3465  3465 D WifiNative-wlan0: callSECApiVoid - ID [212]
,01-27 16:49:54.232  3465  3465 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
,01-27 16:49:54.232  3465  3465 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
01-27 16:49:54.232  3465  3465 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
01-27 16:49:54.232  3465  3465 D HS20StateMachine: SSID : "NG700"
,01-27 16:49:54.232  3465  3465 D HS20StateMachine: NetId : 3
01-27 16:49:54.232  3465  3465 D HS20StateMachine: checkifOSUAP  null
01-27 16:49:54.232  3465  3465 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
01-27 16:49:54.232  3465  3867 I WifiHs20Service: Message received 5007
,01-27 16:49:54.232  3950  4150 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,01-27 16:49:54.242  3465  4487 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
01-27 16:49:54.242  4302  4302 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,01-27 16:49:54.242  3465  3858 D NtpTrustedTime: currentTimeMillis() cache hit
,01-27 16:49:54.242  3465  3858 D NtpTrustedTime: currentTimeMillis() cache hit
01-27 16:49:54.242  3465  4382 D SecContentProvider2: query(), uri = 15 selection = getToastGravityEnabledState
,01-27 16:49:54.242  3465  3484 D SecContentProvider2: query(), uri = 15 selection = getToastEnabledState
,01-27 16:49:54.252  3465  4331 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{201ef6c u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{db58cfe 9820:com.samsung.android.sm.policy/u0a135}
01-27 16:49:54.252  3465  4226 D SecContentProvider2: query(), uri = 15 selection = getToastShowPackageNameState
,01-27 16:49:54.252  3465  3869 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,01-27 16:49:54.252  3465  3869 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]
01-27 16:49:54.252  3465  3869 D ConnectivityService: scheduleUnvalidatedPrompt 503
01-27 16:49:54.252  3465  3869 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 503]
,01-27 16:49:54.252  3465  3860 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
01-27 16:49:54.252  3465  3869 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
01-27 16:49:54.262  3465 10004 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
01-27 16:49:54.262  3465 10004 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: Connected
01-27 16:49:54.262  3465  3869 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,01-27 16:49:54.262  3465 10004 D NetworkMonitor: registerReceiver Captive portal receiver
01-27 16:49:54.262  3465  3860 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
01-27 16:49:54.262  3465  3858 D NtpTrustedTime: currentTimeMillis() cache hit
01-27 16:49:54.262  3465  3858 D NtpTrustedTime: currentTimeMillis() cache hit
,01-27 16:49:54.262  3465  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: true
,01-27 16:49:54.262  3465  3869 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,01-27 16:49:54.262  4302  4545 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0,
01-27 16:49:54.262  4302  4545 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,01-27 16:49:54.262  3465  3869 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,01-27 16:49:54.262  3465  3869 D ConnectivityService: currentScore = 0, newScore = 20
01-27 16:49:54.262  3465  3860 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,01-27 16:49:54.262  3465  3869 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 503]
01-27 16:49:54.262  3465  3869 D ConnectivityService:    accepting network in place of null
01-27 16:49:54.272  3465  3894 D Ethernet: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
01-27 16:49:54.262  3465  3869 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
01-27 16:49:54.272  3465  3860 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
01-27 16:49:54.272  3465  3894 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
01-27 16:49:54.272  3465  3977 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5f1bf3b u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{453d303 9792:com.sec.android.diagmonagent/1000}
,01-27 16:49:54.272  3465  3860 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
01-27 16:49:54.272  9792  9792 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 android.content.ContextWrapper.sendBroadcast:410 android.content.ContextWrapper.sendBroadcast:410 com.sec.android.diagmonagent.DiagMonConnectivityChangeReciever.onReceive:19 android.app.ActivityThread.handleReceiver:3635 
01-27 16:49:54.272  3465  3894 D Ethernet: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
01-27 16:49:54.272  3465  3860 D WIFI    : evalRequest
01-27 16:49:54.272  3465  3894 D Ethernet: evalRequest
01-27 16:49:54.272  3465  3894 D Ethernet:   done
01-27 16:49:54.272  3465  3860 D WIFI    :   done
01-27 16:49:54.272  3465  3860 D WIFI_UT : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
01-27 16:49:54.272  3465  3860 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
01-27 16:49:54.272  3465  3860 D WIFI_UT : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
01-27 16:49:54.272  3465  3860 D WIFI_UT : evalRequest
01-27 16:49:54.272  3465  3860 D WIFI_UT :   done
01-27 16:49:54.272  3465  3860 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,01-27 16:49:54.272  3465  3860 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
01-27 16:49:54.272  3465  3860 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
01-27 16:49:54.272  3465  3860 D WIFI    : evalRequest
01-27 16:49:54.272  3465  3860 D WIFI    :   done
01-27 16:49:54.272  3465  3859 D WIFI_P2P: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
01-27 16:49:54.272  3465  3859 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,01-27 16:49:54.272  3465  3859 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
01-27 16:49:54.272  3465  3859 D WIFI_P2P: evalRequest
01-27 16:49:54.272  3465  3859 D WIFI_P2P:   done
01-27 16:49:54.272  9792  9792 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
01-27 16:49:54.272  9792  9792 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
01-27 16:49:54.272  9792  9792 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
01-27 16:49:54.272  3465 10004 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
01-27 16:49:54.272  3465 10004 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: Validated
,01-27 16:49:54.292  3950  4150 D ViewRootImpl: #1 mView = android.widget.LinearLayout{dbaf86f V.E...... ......I. 0,0-0,0 #102039c android:id/toast_layout_root}
,01-27 16:49:54.302  3950  3950 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 272
,01-27 16:49:54.302  3465  4416 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5f1bf3b u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e533db5 6432:com.enhance.gameservice/u0a106}
01-27 16:49:54.302  3465  4487 D ISSUE_DEBUG: InputChannelName : 328c004 Toast
,01-27 16:49:54.312  3465  4487 V MARsPolicyManager: handelAlertToastWindowStarted pkgName = com.android.systemui
,01-27 16:49:54.322  3465  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,01-27 16:49:54.332  3014  3014 I SurfaceFlinger: id=20 createSurf (1x1),1 flag=4, Uoast
,01-27 16:49:54.342  3465  3977 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5f1bf3b u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{51370b9 9808:com.sec.knox.switcher/1000}
,01-27 16:49:54.342  9808  9808 I usagelog: received in receiver
01-27 16:49:54.342  9808  9808 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
01-27 16:49:54.342  9808  9808 I KnoxUsageLogPro: premStatus:2
,01-27 16:49:54.342  9808  9808 I KnoxUsageLogPro: isEulaShown : false
,01-27 16:49:54.342  9808  9808 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,01-27 16:49:54.352  3465  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,01-27 16:49:54.362  3465  4331 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3465
,01-27 16:49:54.362  3465  4225 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5f1bf3b u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{db58cfe 9820:com.samsung.android.sm.policy/u0a135}
,01-27 16:49:54.372  3465  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,01-27 16:49:54.372  3950  4131 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1033x201]-format:1
,01-27 16:49:54.372  3950  4150 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,01-27 16:49:54.382  3465  3973 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1cadab3 u0 com.sec.android.diagmonagent.intent.NETWORK_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{453d303 9792:com.sec.android.diagmonagent/1000}
,01-27 16:49:54.382  9792  9792 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: com.sec.android.diagmonagent.intent.NETWORK_CHANGED
01-27 16:49:54.382  3465  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
01-27 16:49:54.382  9792  9792 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
,01-27 16:49:54.382  9792  9792 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(67/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,01-27 16:49:54.392  3950  4150 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,01-27 16:49:54.392  3465  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,01-27 16:49:54.402  3465  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,01-27 16:49:54.402  3465  3869 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,01-27 16:49:54.402  3465  4487 V WindowStateAnimator: Finishing drawing window Window{328c004 u0 d0 Toast}: mDrawState=DRAW_PENDING
,01-27 16:49:54.402  3014  3014 D libEGL  : eglInitialize EGLDisplay = 0x7fc1e5c6c8
,01-27 16:49:54.432  3162  3715 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,01-27 16:49:54.462  3162  3715 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,01-27 16:49:54.462  3465  3869 D ConnectivityService: 503 network ip type : v4
,01-27 16:49:54.472  3465  3869 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
01-27 16:49:54.472  3465  3869 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,01-27 16:49:54.472  3465  3869 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,01-27 16:49:54.472  3465  3869 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,01-27 16:49:54.472  3465  3559 D EntConnectivity: Not allowed due to - mEnabled false
,01-27 16:49:54.472  3465  3869 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=5, legacyType=-1, [] ]
,01-27 16:49:54.482  3465  3869 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} } for legacy network type 1
01-27 16:49:54.482  3465  3869 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
01-27 16:49:54.482  3465  3869 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,01-27 16:49:54.482  3465  3889 D WifiWatchdogStateMachine.CaptivePortalHandler: start check captive portal 
,01-27 16:49:54.482  3465  3977 D ConnectivityService: getVpnConfig > userId : 0
,01-27 16:49:54.492  3465  3559 D EntConnectivity: Not allowed due to - mEnabled false
01-27 16:49:54.492  3465  3869 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
01-27 16:49:54.492  3465  3869 D ConnectivityService: unneeded: NetworkRequestInfo for = Request from uid/pid:1000/3465 for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,01-27 16:49:54.492  3465  3869 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
01-27 16:49:54.492  3465  3869 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
01-27 16:49:54.492  3465  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
01-27 16:49:54.492  3465  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
01-27 16:49:54.492  3465  3869 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
01-27 16:49:54.492  3465  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
,01-27 16:49:54.492  3465  3869 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=5, legacyType=-1, [] ]
,01-27 16:49:54.492  3465  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,01-27 16:49:54.492  3465  3869 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,01-27 16:49:54.492  3465  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,01-27 16:49:54.492  3465  3869 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
01-27 16:49:54.502  3465  3465 D Tethering: Tethering got CONNECTIVITY_ACTION
01-27 16:49:54.492  3465  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
01-27 16:49:54.502  3465  3559 D Tethering: MasterInitialState.processMessage what=3
,01-27 16:49:54.492  3465  3869 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
01-27 16:49:54.492  3465  3869 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
01-27 16:49:54.492  3465  3869 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] validation  passed
,01-27 16:49:54.492  3465  3869 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]
01-27 16:49:54.492  3465  3869 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
01-27 16:49:54.502  3465  3869 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
01-27 16:49:54.502  3465  3465 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
01-27 16:49:54.502  3465  3465 I CLocInfoService: ['16.5] External Intent Received android.net.conn.CONNECTIVITY_CHANGE
01-27 16:49:54.502  3465  3465 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
01-27 16:49:54.502  3465  3465 I CLocInfoService: CLocinfo wifi true 
,01-27 16:49:54.502  3950  4150 D NetworkController: onReceive: intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,01-27 16:49:54.502  3465  3535 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
01-27 16:49:54.502  3465  3871 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,01-27 16:49:54.502  3465  3535 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,01-27 16:49:54.502  3465  3535 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,01-27 16:49:54.502  4302  4698 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
01-27 16:49:54.502  4302  4698 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
01-27 16:49:54.502  3465  3871 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,01-27 16:49:54.512  3465  4204 V AlarmManager:  remove PendingIntent] PendingIntent{6f8715e: PendingIntentRecord{707193f android broadcastIntent}}
,01-27 16:49:54.512  3465  3869 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
,01-27 16:49:54.522  3465  3465 V MARsPolicyManager: DataConnection: true
,01-27 16:49:54.532  4302  4698 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,01-27 16:49:54.532  4302  4698 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,01-27 16:49:54.532  3465  3858 D NtpTrustedTime: currentTimeMillis() cache hit
,01-27 16:49:54.532  3465  3858 D NtpTrustedTime: currentTimeMillis() cache hit
01-27 16:49:54.532  3465  3858 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
01-27 16:49:54.532  3465  3858 D NtpTrustedTime: currentTimeMillis() cache hit
01-27 16:49:54.532  3465  3858 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]
01-27 16:49:54.532  4826  4826 D SamsungIME: EngineType = SWIFTKEY
01-27 16:49:54.532  3465  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
01-27 16:49:54.532  3465  3858 D NtpTrustedTime: currentTimeMillis() cache hit
01-27 16:49:54.532  3465  3858 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
01-27 16:49:54.532  3465  3888 D WifiWatchdogStateMachine: response code : 204
01-27 16:49:54.532  4826  4826 D SamsungIME: mNetworkChangeReceiver isWLANConnected : true
,01-27 16:49:54.532  3465  3535 D TelephonyManager: getDataEnabled: retVal=true
,01-27 16:49:54.532  3465  4202 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,01-27 16:49:54.542  4990  5088 D CellLocationSupport: onReceive ACTION = android.net.conn.CONNECTIVITY_CHANGE
01-27 16:49:54.542  4990  5088 I CellLocationSupport: onCellLocationChanged
,01-27 16:49:54.542  4990  4990 D PdnController: CONNECTIVITY_ACTION: networkType 1 isConnected true
01-27 16:49:54.542  4990  4990 D PdnController: isSuspended [false] networktype [1]
01-27 16:49:54.542  4990  4990 D PdnController: Updated Interface [wlan0] For Network [1]
,01-27 16:49:54.542  3465  4487 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,01-27 16:49:54.542  4990  4990 D PdnController: isPdnUp  [true] networktype [1]
01-27 16:49:54.542  4990  4990 D PdnController: Notify Result to LocalIP Registrants! : networkType [1] isConnected [true] 
,01-27 16:49:54.552  5287  5287 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@88e74bc and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,01-27 16:49:54.552  5287  5287 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,01-27 16:49:54.552  3465  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,01-27 16:49:54.552  3465  4331 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,01-27 16:49:54.552  6759  6759 I FOTA_AGENT: [lIlIIlIlIlIllllllIII(91/llllIIIllIlIIIIllllI)] WiFi Network is connected
,01-27 16:49:54.562  4990  5088 I CellLocationSupport: Block to update PANI information in non VoWIFI
01-27 16:49:54.562  4990  5088 D SlickSSConfigHandler: EVENT_LOCAL_IP_CHANGED
,01-27 16:49:54.562  3465  4488 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,01-27 16:49:54.562  4990  5088 D PdnController: isIfaceDisconnected result [true] networkType [0] interfaceName [null] 
01-27 16:49:54.562  4990  5088 D PdnController: isPdnUp  [false] networktype [0]
01-27 16:49:54.562  4990  5088 D SlickSSConfigHandler: handleNetworkStateChange: check isDefaultPDNConnected[false], mReadyForDocFetch[false
,01-27 16:49:54.572  4990  5088 D RegistrationManager: handleMessage(): 5
,01-27 16:49:54.572  3465  4487 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,01-27 16:49:54.572  4990  5088 D PdnController: isIfaceDisconnected result [true] networkType [11] interfaceName [null] 
01-27 16:49:54.572  4990  5088 D PdnController: isPdnUp  [false] networktype [11]
01-27 16:49:54.572  4990  5088 D RegistrationManager: setEPDGIPSecConnected [false]
01-27 16:49:54.572  4990  5088 D RegistrationManager: notifyNetworkState : NetworkType [1] IsConnected [true] IPAddresses [[/192.168.1.135]] DNSAddresses [[/192.168.1.1]] 
01-27 16:49:54.572  4990  5088 D RegistrationManager: isEPDGAvailable [false]
01-27 16:49:54.572  4990  5088 D RegistrationManager: setWifiPreparedOnAPM [true]
,01-27 16:49:54.582  3465  4226 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,01-27 16:49:54.582  4195  4195 D FusedRequestManager: manageLocationRequest, new passive request from com.samsung.voiceserviceplatform with 6a0eb74 , interval = 1800000 through LocationManagerService
01-27 16:49:54.582  9076  9076 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 com.samsung.SMT.SamsungTTSService.g:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.c.onReceive:-1 
,01-27 16:49:54.582  3465  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,01-27 16:49:54.592  3465  3889 D WifiWatchdogStateMachine.CaptivePortalHandler: result = 0, mCaptivePortalCheckMode = 11, mCouldNotIdentifyCaptivePortalState = true
,01-27 16:49:54.602  9859  9869 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(86/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
,01-27 16:49:54.602  9859  9869 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(86/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
,01-27 16:49:54.602  3162  3711 D EnterpriseController: netId is 0
01-27 16:49:54.602  3162  3711 D Netd    : getNetworkForDns: using netid 503 for uid 10001
,01-27 16:49:54.602  9859  9869 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(43/llIIIIlllllIIllIIllI)] already Eula Agree
,01-27 16:49:54.612  4990  5088 D TranslatorCollection: translateToNwkSvcType: networkType XAN_NWK_TYPE_WLAN
01-27 16:49:54.612  4990  5088 D RegistrationManager: getNetworkType [0]
01-27 16:49:54.612  4990  5088 D CoreStackAdaptor2: notifyNetworkState() [1] isConnected [true] nwkSvcType  [XAN_NWK_TYPE_WLAN] nwkInfoType [XAN_SVC_NETWORK_SVCTYPE_WIFI] dedicated   [NONE] 
01-27 16:49:54.612  4990  5088 D CellLocationSupport: Siso Stack not called RegisterAN yet on XAN_NWK_TYPE_WLAN
,01-27 16:49:54.612  4465  4465 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
01-27 16:49:54.612  4990  5088 D TranslatorCollection: translateToNwkSvcType: networkType XAN_NWK_TYPE_WLAN
,01-27 16:49:54.612  4990  5088 D CoreStackAdaptor2: ipList Not Null[/192.168.1.135]
01-27 16:49:54.612  4990  5088 D RegistrationManager: tryRegister(CONNECTIVITY_STATUS_CHANGE)
01-27 16:49:54.612  4990  5088 D RegistrationManager: isPreconditionProperToGoOn
01-27 16:49:54.612  4990  5088 D RegistrationManager: isDeviceShutdown [false]
01-27 16:49:54.612  4990  5088 D RegistrationManager: isStackShuttingDownForAllPDNs [false]
01-27 16:49:54.612  4990  5088 D RegistrationManager: isDmVoLTEUpdated [false]
01-27 16:49:54.612  4990  5088 D RegistrationManager: tryRegister : Abort Reason [IMS feature disabled]
01-27 16:49:54.612  4990  5088 D RegistrationManager: tryRegister : Not all preconditions are met!
,01-27 16:49:54.622  9588  9588 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,01-27 16:49:54.622  3465  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,01-27 16:49:54.632  9859  9870 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(86/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
,01-27 16:49:54.632  9859  9870 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(86/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
,01-27 16:49:54.632  9859  9870 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(43/llIIIIlllllIIllIIllI)] already Eula Agree
,01-27 16:49:54.652  4953  4953 E audit   : type=1400 msg=audit(1485532194.652:278): avc:  denied  { ioctl } for  pid=7024 comm="ChromiumNet" path="socket:[45138]" dev="sockfs" ino=45138 ioctlcmd=8b1b scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=udp_socket permissive=0
01-27 16:49:54.652  4953  4953 E audit   :  SEPF_SECMOBILE_6.0.1_0031
01-27 16:49:54.652  4953  4953 E audit   : type=1300 msg=audit(1485532194.652:278): arch=c00000b7 syscall=29 success=no exit=-13 a0=18 a1=8b1b a2=7f86d3ecc8 a3=7f86d3ec90 items=0 ppid=3190 pid=7024 auid=4294967295 uid=10068 gid=10068 euid=10068 suid=10068 fsuid=10068 egid=10068 sgid=10068 fsgid=10068 tty=(none) ses=4294967295 comm="ChromiumNet" exe="/system/bin/app_process64" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
01-27 16:49:54.652  4953  4953 E audit   : type=1327 msg=audit(1485532194.652:278): proctitle="com.google.android.googlequicksearchbox:search"
01-27 16:49:54.652  4953  4953 E audit   : type=1320 msg=audit(1485532194.652:278): 
01-27 16:49:54.652  4953  4953 E audit   : type=1400 msg=audit(1485532194.652:279): avc:  denied  { ioctl } for  pid=7024 comm="ChromiumNet" path="socket:[45139]" dev="sockfs" ino=45139 ioctlcmd=8b1b scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=udp_socket permissive=0
01-27 16:49:54.652  4953  4953 E audit   :  SEPF_SECMOBILE_6.0.1_0031
01-27 16:49:54.652  4953  4953 E audit   : type=1300 msg=audit(1485532194.652:279): arch=c00000b7 syscall=29 success=no exit=-13 a0=18 a1=8b1b a2=7f86d3ecc8 a3=7f86d3ec90 items=0 ppid=3190 pid=7024 auid=4294967295 uid=10068 gid=10068 euid=10068 suid=10068 fsuid=10068 egid=10068 sgid=10068 fsgid=10068 tty=(none) ses=4294967295 comm="ChromiumNet" exe="/system/bin/app_process64" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
01-27 16:49:54.652  4953  4953 E audit   : type=1327 msg=audit(1485532194.652:279): proctitle="com.google.android.googlequicksearchbox:search"
01-27 16:49:54.652  4953  4953 E audit   : type=1320 msg=audit(1485532194.652:279): 
,01-27 16:49:54.652  3465  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,01-27 16:49:54.652  4302  4313 D TelephonyProvider: query: url=content://telephony/carriers/preferapn, projectionIn=[Ljava.lang.String;@e16e65a, selection=nullselectionArgs=null, sort=name ASC
,01-27 16:49:54.662  4302  4313 D TelephonyProvider: query: match = 5
,01-27 16:49:54.662  4302  4313 D TelephonyProvider: getPreferredApnId(subId = 2147483643),return -1
01-27 16:49:54.662  4302  4313 D TelephonyProvider: query: selection modified to edited!=2 and edited!=3 and edited!=5 and edited!=6
,01-27 16:49:54.662  3465  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
01-27 16:49:54.662  3465  3869 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
01-27 16:49:54.662  3465  3869 D ConnectivityService: unneeded: NetworkRequestInfo for = Request from uid/pid:1000/3465 for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
01-27 16:49:54.672  3465  3869 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
01-27 16:49:54.672  3465  3869 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 503]
01-27 16:49:54.672  3465  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
01-27 16:49:54.672  3465  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
01-27 16:49:54.672  3465  3869 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,01-27 16:49:54.672  3465  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
01-27 16:49:54.672  3465  3977 I ActivityManager: Start proc 10061:com.sec.android.soagent/1000 for content provider com.sec.android.soagent/.log.MasterLogProvider
,01-27 16:49:54.672 10061 10061 E Zygote  : v2
01-27 16:49:54.672 10061 10061 I libpersona: KNOX_SDCARD checking this for 1000
01-27 16:49:54.672  9588  9588 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
01-27 16:49:54.672 10061 10061 I libpersona: KNOX_SDCARD not a persona
,01-27 16:49:54.672 10061 10061 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
01-27 16:49:54.672  3465  3869 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=5, legacyType=-1, [] ]
,01-27 16:49:54.672  3465  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
01-27 16:49:54.672 10061 10061 E Zygote  : accessInfo : 0
01-27 16:49:54.672  3465  3869 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,01-27 16:49:54.682  3465  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,01-27 16:49:54.682  3465  3869 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,01-27 16:49:54.682  3465  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
01-27 16:49:54.682  3465  3869 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,01-27 16:49:54.682  3465  3894 D Ethernet: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
01-27 16:49:54.682  3465  3869 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
01-27 16:49:54.682  3465  3894 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
01-27 16:49:54.682  3465  3894 D Ethernet: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
01-27 16:49:54.682  3465  3894 D Ethernet: evalRequest
01-27 16:49:54.682  3465  3894 D Ethernet:   done
01-27 16:49:54.682  3465  3860 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
01-27 16:49:54.682  3465  3860 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
01-27 16:49:54.682  3465  3860 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
01-27 16:49:54.682  3465  3860 D WIFI    : evalRequest
01-27 16:49:54.682  3465  3860 D WIFI    :   done
01-27 16:49:54.682  3465  3860 D WIFI_UT : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
01-27 16:49:54.682  3465  3860 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
01-27 16:49:54.682  3465  3860 D WIFI_UT : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
01-27 16:49:54.682  3465  3860 D WIFI_UT : evalRequest
01-27 16:49:54.682  3465  3860 D WIFI_UT :   done
01-27 16:49:54.682  3465  3860 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
01-27 16:49:54.682  3465  3860 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
01-27 16:49:54.682  3465  3860 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
01-27 16:49:54.682  3465  3860 D WIFI    : evalRequest
01-27 16:49:54.682  3465  3860 D WIFI    :   done
,01-27 16:49:54.682  3465  3869 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
01-27 16:49:54.682  3465  3859 D WIFI_P2P: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
01-27 16:49:54.682  3465  3859 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
01-27 16:49:54.682  3465  3859 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
01-27 16:49:54.682  3465  3859 D WIFI_P2P: evalRequest
01-27 16:49:54.682  3465  3859 D WIFI_P2P:   done
,01-27 16:49:54.692  3465  3860 D WifiNetworkAgent: NetworkAgent: CMD_REPORT_NETWORK_STATUS(VALID)
01-27 16:49:54.692  3465  3860 D WifiNetworkAgent: NetworkAgent: CMD_REPORT_NETWORK_STATUS(1)
,01-27 16:49:54.702  3465  3860 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
01-27 16:49:54.702  3950  4150 D NetworkController: onReceive: intent=Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
01-27 16:49:54.702  3465  3860 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
01-27 16:49:54.702  3465  3860 D WifiStateMachine: sendBroadcastForCaptivePortalNotLoginIcon : false
,01-27 16:49:54.702  3465  3860 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
01-27 16:49:54.702  3465  3860 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
,01-27 16:49:54.712  9588  9588 D BluetoothAdapter: STATE_ON
,01-27 16:49:54.712  3465  3535 E GpsLocationProvider: No APN found to select.
,01-27 16:49:54.712 10061 10061 D TimaKeyStoreProvider: TimaSignature is unavailable
01-27 16:49:54.712 10061 10061 D ActivityThread: Added TimaKeyStore provider
,01-27 16:49:54.712  3950  4150 D NetworkController: onReceive: intent=Intent { act=com.samsung.intent.action.WIFI_CAPTIVE_NOT_LOGIN flg=0x10 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
01-27 16:49:54.712  3950  4150 D NetworkController.WifiSignalController: updateWifiState : mCurrentState.wifiCaptiveNotLogin = false
,01-27 16:49:54.722  9588  9588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
01-27 16:49:54.722  9588  9588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
01-27 16:49:54.722  9588  9588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
01-27 16:49:54.722  9588  9588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
01-27 16:49:54.722  9588  9588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
01-27 16:49:54.722  9588  9588 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
01-27 16:49:54.722  9588  9588 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
01-27 16:49:54.722  9588  9588 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
01-27 16:49:54.722  9588  9588 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,01-27 16:49:54.722  9588  9588 D BluetoothAdapter: STATE_ON
,01-27 16:49:54.732  9588  9588 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,01-27 16:49:54.732  3465  3535 D libgps  : agps_ril_update_network_state: Waiting for IPC connection...
,01-27 16:49:54.742 10061 10061 W ResourcesManager: getTopLevelResources: /system/priv-app/SOAgent/SOAgent.apk / 1.0 running in com.sec.android.soagent rsrc of package com.sec.android.soagent
,01-27 16:49:54.742  3465  4331 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
01-27 16:49:54.742 10061 10061 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,01-27 16:49:54.742 10061 10061 D ResourcesManager: For user 0 new overlays fetched Null
,01-27 16:49:54.752 10061 10061 I InjectionManager: Inside getClassLibPath caller 
,01-27 16:49:54.752 10061 10061 W System  : ClassLoader referenced unknown path: /system/priv-app/SOAgent/lib/arm64
,01-27 16:49:54.782 10061 10061 D InjectionManager: InjectionManager
01-27 16:49:54.782 10061 10061 D InjectionManager: fillFeatureStoreMap com.sec.android.soagent
,01-27 16:49:54.782 10061 10061 I InjectionManager: Constructor com.sec.android.soagent, Feature store :{}
01-27 16:49:54.782 10061 10061 I InjectionManager: featureStore :{}
,01-27 16:49:54.812  3465  4487 I ActivityManager: Killing 9199:com.samsung.android.app.filterinstaller/1000 (adj 15): DHA:empty #33
,01-27 16:49:54.822  3465  4487 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b4b3b21 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4c3b831 9588:com.test.thalitest/u0a74}
,01-27 16:49:54.822  3465  4225 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:54.822  3465  4225 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
01-27 16:49:54.822  3465  4225 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:54.822  3465  4225 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:54.822  3465  4225 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:54.822  3465  4225 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:54.822  3465  4225 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:54.822  3465  4225 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:54.822  3465  4225 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:54.822  3465  4225 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,01-27 16:49:54.822  3465  4225 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,01-27 16:49:54.822  3465  4225 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:54.822  3465  4225 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:54.832  3465  4225 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
01-27 16:49:54.832  3465  4225 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,01-27 16:49:54.852  3465  4485 D ActivityManager: cleanUpApplicationRecord -- 9199
,01-27 16:49:54.852  3465  4485 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.filterinstaller, Auto Run ON
,01-27 16:49:54.862  3465  4487 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b4b3b21 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b3d1f23 3465:system/1000}
,01-27 16:49:54.882  3465  3465 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b4b3b21 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cdfcc89 4526:com.google.android.gms/u0a19}
,01-27 16:49:54.882  4526  4526 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,01-27 16:49:54.892  4526  5484 I iu.UploadsManager: num queued entries: 0
,01-27 16:49:54.892  4526  5484 I iu.UploadsManager: num updated entries: 0
,01-27 16:49:54.892  4526  5484 I iu.SyncManager: NEXT; no task
,01-27 16:49:54.892  3465  4059 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b4b3b21 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cdfcc89 4526:com.google.android.gms/u0a19}
,01-27 16:49:54.912  3465  4059 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b4b3b21 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fa96432 4239:com.google.android.gms.persistent/u0a19}
,01-27 16:49:54.932  3162  3711 D EnterpriseController: netId is 0
01-27 16:49:54.932  3162  3711 D Netd    : getNetworkForDns: using netid 503 for uid 10019
,01-27 16:49:54.932  3465  4225 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b4b3b21 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a857df1 9859:com.policydm/1000}
,01-27 16:49:54.952  9859  9859 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(574/IlIIIllllIIlIIIIIlII)] Initiated Type: 0
,01-27 16:49:54.962  9859  9859 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,01-27 16:49:54.962  9859  9859 I DBG_POLICYDM: [com.policydm.XDMService(585/llIlIllllllllllllllI)] get NotibarState : 0
,01-27 16:49:55.042  3465  3538 D ActivityManager:  getDeferredInfo final delay 300
,01-27 16:49:55.262  3465  4042 V AlarmManager:  remove PendingIntent] PendingIntent{7926b46: PendingIntentRecord{3c7b89f com.google.android.gms broadcastIntent}}
,01-27 16:49:55.272  3465  3538 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{42b3107 u0 com.google.android.gcm.CONNECTED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3655c31 8494:com.google.android.talk/u0a112}
,01-27 16:49:55.282  3465  4042 V AlarmManager:  remove PendingIntent] PendingIntent{1be3234: PendingIntentRecord{1767c6d com.google.android.gms broadcastIntent}}
,01-27 16:49:55.322  3465  4382 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
01-27 16:49:55.322  3465  4382 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4331, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
01-27 16:49:55.322  3465  4382 D BatteryService: online:4, current avg:-7, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:5
01-27 16:49:55.322  3465  3465 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,01-27 16:49:55.322  3465  3465 I MotionRecognitionService: Plugged
01-27 16:49:55.322  3465  3465 D MotionRecognitionService:   cableConnection= 1
01-27 16:49:55.322  3465  3465 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
01-27 16:49:55.322  3465  3465 D MotionRecognitionService: skip setTransmitPower. 
,01-27 16:49:55.322  3465  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,01-27 16:49:55.332  3950  3950 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,01-27 16:49:55.332  3950  3950 D PowerUI : priorPlugType = 2 mPlugType =  2
,01-27 16:49:55.332  3950  3950 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,01-27 16:49:55.332  3950  3950 D KeyguardUpdateMonitor: handleBatteryUpdate
01-27 16:49:55.332  3950  3950 D PowerUI.Notification: There is no change about charging status, so return!
,01-27 16:49:55.342  4990  4990 D CommonServiceConfiguration: getStringValueSetting
,01-27 16:49:55.352  3465  3538 D ActivityManager:  getDeferredInfo final delay 0
,01-27 16:49:55.362  4942  4942 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,01-27 16:49:55.362  4942  9696 D HeadsetStateMachine: Disconnected process message: 10, size: 0
01-27 16:49:55.362  4990  4990 D BatteryMonitor: new battery level: 100
,01-27 16:49:55.372  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,01-27 16:49:55.372  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,01-27 16:49:55.372  9859  9859 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(51/onReceive)] RegistrationReceiver onReceive! action = android.net.conn.CONNECTIVITY_CHANGE
01-27 16:49:55.372  3465  3538 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{b4b3b21 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a857df1 9859:com.policydm/1000}
,01-27 16:49:55.402  3465  4488 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
01-27 16:49:55.402  3465  4488 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4330, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
01-27 16:49:55.402  3465  4488 D BatteryService: online:4, current avg:-7, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:5
01-27 16:49:55.402  3465  3465 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,01-27 16:49:55.402  3465  3465 I MotionRecognitionService: Plugged
01-27 16:49:55.402  3465  3465 D MotionRecognitionService:   cableConnection= 1
01-27 16:49:55.402  3465  3465 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
01-27 16:49:55.402  3465  3465 D MotionRecognitionService: skip setTransmitPower. 
,01-27 16:49:55.402  3465  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,01-27 16:49:55.402  3950  3950 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,01-27 16:49:55.412  3950  3950 D PowerUI : priorPlugType = 2 mPlugType =  2
01-27 16:49:55.412  9859  9859 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(87/llllIIIllIlIIIIllllI)] device register flag at setting DB : true
,01-27 16:49:55.412  3950  3950 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
01-27 16:49:55.412  3950  3950 D KeyguardUpdateMonitor: handleBatteryUpdate
01-27 16:49:55.412  3950  3950 D PowerUI.Notification: There is no change about charging status, so return!
,01-27 16:49:55.422  4990  4990 D CommonServiceConfiguration: getStringValueSetting
,01-27 16:49:55.422  4942  4942 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
01-27 16:49:55.422  4942  9696 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,01-27 16:49:55.422  4990  4990 D BatteryMonitor: new battery level: 100
,01-27 16:49:55.432  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
01-27 16:49:55.432  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,01-27 16:49:55.432  9859  9859 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(96/onReceive)] Already device registered...
,01-27 16:49:55.442  9859  9859 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(87/llllIIIllIlIIIIllllI)] device register flag at setting DB : true
,01-27 16:49:55.442  9859  9859 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(342/lllIlIlIIIllIIlIllIl)] OMC not Supported model
,01-27 16:49:55.452  9859  9859 I DBG_POLICYDM: [IIIIlllIIIlIlllllIll(111/llIlIIIIlIIIIIlIlIII)] Polling time is vaild
,01-27 16:49:55.452  9859  9859 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(281/llIIIIlllllIIllIIllI)] Heartbeat settings is activated.
,01-27 16:49:55.452  9859  9859 I DBG_POLICYDM: [IIlllIIllIllIllIIlll(52/llllIIIllIlIIIIllllI)] Next heartbeat time:2017/02/04/05:57:37
,01-27 16:49:55.452  9859  9859 I DBG_POLICYDM: [IIlllIIllIllIllIIlll(55/llllIIIllIlIIIIllllI)] heartbeat time is vaild
,01-27 16:49:55.452  3465  3973 D ActivityManager:  getDeferredInfo final delay 0
,01-27 16:49:55.462  3465  3973 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{b4b3b21 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{704957e 7358:com.osp.app.signin/u0a41}
,01-27 16:49:55.462  7358  7358 I SA      : [OR] onReceive log=[SA = 2.2.02-12 V = 23 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = pl_PL CSC = XEO MCC = 0 MNC 0 T = user DEVICE = herolte P = heroltexx I = MMB29K M = SM-G930F OKLEFT false DIS MMB29K.G930FXXU1BPJG PSS = 5.059173621445858  ]
,01-27 16:49:55.462  7358  7358 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
,01-27 16:49:55.462  7358  7358 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,01-27 16:49:55.472  3465  3869 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
01-27 16:49:55.472  7358  7358 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
01-27 16:49:55.472  7358  7358 I SA      : [OR] == isSIMCardReady false ==
,01-27 16:49:55.472  7358  7358 I SA      : [SCU] == networkStateCheck == true
01-27 16:49:55.472  7358  7358 I SA      : [DM] getCountryCodeFromCSC : PL
01-27 16:49:55.472  7358  7358 I SA      : isChinaCountryCode : false
01-27 16:49:55.472  7358  7358 I SA      : [SCU] is ChinestModel Data Restricted   : false
01-27 16:49:55.472  7358  7358 I SA      : [OR] == networkStateCheck true ==
01-27 16:49:55.472  7358  7358 I SA      : [OR] GetMyCountryZoneTask
,01-27 16:49:55.472  7358  7358 I SA      : [OR] onReceive END
,01-27 16:49:55.472  7358 10080 I SA      : [SRS] prepareGetMyCountryZone
01-27 16:49:55.472  3465  4331 D ActivityManager:  getDeferredInfo final delay 0
,01-27 16:49:55.482  3465  4331 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{b4b3b21 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3b49439 6759:com.wssyncmldm/1000}
,01-27 16:49:55.482  7358 10080 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,01-27 16:49:55.482  7358 10080 I SA      : [SSP] query invoked
,01-27 16:49:55.492  7358 10080 I SA      : [TPMU] GetMccFromDB : null
01-27 16:49:55.492  7358 10080 I SA      : [SCU] getMccFromPreferece mcc = 260
,01-27 16:49:55.492  7358 10080 I SA      : [LBE] isSupportCheckDomainRegion : true
01-27 16:49:55.492  7358 10080 I SA      : [TPM] isNoProxy(default) : true
01-27 16:49:55.492  7358 10080 I SA_HTTPURLCONNECTION: [RC New] Execute method=[GET] start
,01-27 16:49:55.492  3465  4226 D ActivityManager:  getDeferredInfo final delay 300
,01-27 16:49:55.502  6759 10081 I FOTA_AGENT: [com.samsung.android.app.fotaclient.llIlIIIIlIIIIIlIlIII(87/llIIIIlllllIIllIIllI)] Nothing to do action: android.net.conn.CONNECTIVITY_CHANGE
,01-27 16:49:55.512  7358 10080 I SA_HTTPURLCONNECTION: [RC New] Security=[true]
01-27 16:49:55.512  7358 10080 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
01-27 16:49:55.512  7358 10080 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,01-27 16:49:55.522  3162  3711 D EnterpriseController: netId is 0
01-27 16:49:55.522  3162  3711 D Netd    : getNetworkForDns: using netid 503 for uid 10041
,01-27 16:49:55.732  3465  3535 D libgps  : agps_ril_update_network_state: Waiting for IPC connection - timeout
01-27 16:49:55.732  3465  3535 E libgps  : LIBGPS: Cannot communicate (write) with a GPSD
01-27 16:49:55.732  3465  3535 E libgps  : IPC Communication Error, ../../../../tmp/14982990_270314/allPartners/os/android/gps_interface/gpsi_client/GpsiClient.cpp:1710 agps_ril_update_network_state
01-27 16:49:55.732  3465  3535 D libgps  : agps_ril_update_network_availability: Waiting for IPC connection...
,01-27 16:49:55.752  9588  9651 I io.jxcore.node.IncomingSocketThreadTest: testRun
01-27 16:49:55.752  9588  9651 I !!      :  finally closed
,01-27 16:49:55.752  9588  9651 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
,01-27 16:49:55.752  9588  9651 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,01-27 16:49:55.752  9588  9651 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
,01-27 16:49:55.752  9588  9651 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,01-27 16:49:55.752  9588  9651 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,01-27 16:49:55.762  9588  9651 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
,01-27 16:49:55.762  9588  9651 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@185a185 Bundle[{}]
,01-27 16:49:55.762  9588  9651 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
01-27 16:49:55.762  9588  9651 I io.jxcore.node.LifeCycleMonitor: start: OK
,01-27 16:49:55.762  9588  9651 I io.jxcore.node.LifeCycleMonitor: stop: OK
01-27 16:49:55.762  9588  9651 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
,01-27 16:49:55.762  9588  9651 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,01-27 16:49:55.762  9588  9651 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
01-27 16:49:55.762  9588  9651 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,01-27 16:49:55.762  9588  9651 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
,01-27 16:49:55.762  9588  9651 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,01-27 16:49:55.762  9588  9651 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
01-27 16:49:55.762  9588  9651 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,01-27 16:49:55.762  9588  9651 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString,
,01-27 16:49:55.772  9588  9651 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,01-27 16:49:55.772  9588  9651 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
,01-27 16:49:55.772  9588  9651 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
,01-27 16:49:55.772  9588  9651 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
,01-27 16:49:55.772  9588  9651 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
,01-27 16:49:55.772  9588  9651 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testRun
,01-27 16:49:55.782  9588 10084 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,01-27 16:49:55.782  9588 10084 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,01-27 16:49:55.782  3162  3711 D EnterpriseController: netId is 0
,01-27 16:49:55.782  3162  3711 D Netd    : getNetworkForDns: using netid 503 for uid 10074
,01-27 16:49:55.782  9588 10086 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,01-27 16:49:55.782  9588 10086 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
01-27 16:49:55.782  9588 10086 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
01-27 16:49:55.782  9588 10086 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
01-27 16:49:55.782  9588 10084 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
01-27 16:49:55.782  9588 10084 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
01-27 16:49:55.782  9588 10086 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,01-27 16:49:55.782  9588 10084 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,01-27 16:49:55.792  9588 10084 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,01-27 16:49:55.802  3465  3538 D ActivityManager:  getDeferredInfo final delay 0
,01-27 16:49:55.802  9588 10090 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 246, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
01-27 16:49:55.802  9588 10090 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
01-27 16:49:55.802  9588 10090 D io.jxcore.node.StreamCopyingThread:  id: 78
,01-27 16:49:55.802  9588 10084 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,01-27 16:49:55.802  9588 10088 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 244, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
01-27 16:49:55.802  9588 10088 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
01-27 16:49:55.802  9588 10088 D io.jxcore.node.StreamCopyingThread:  id: 77
,01-27 16:49:55.802  9588 10089 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 245, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
01-27 16:49:55.802  9588 10089 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
01-27 16:49:55.802  9588 10089 D io.jxcore.node.StreamCopyingThread:  id: 77
,01-27 16:49:55.802  9588 10091 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 247, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
01-27 16:49:55.802  9588 10091 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
01-27 16:49:55.802  9588 10091 D io.jxcore.node.StreamCopyingThread:  id: 78
,01-27 16:49:55.802  9588 10091 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 247, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
01-27 16:49:55.802  9588 10091 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
01-27 16:49:55.802  9588 10091 D io.jxcore.node.StreamCopyingThread:  id: 78
01-27 16:49:55.802  9588 10091 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
01-27 16:49:55.802  9588 10091 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
01-27 16:49:55.802  9588 10091 D io.jxcore.node.StreamCopyingThread:  id: 78
01-27 16:49:55.802  9588 10091 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
01-27 16:49:55.802  9588 10091 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
01-27 16:49:55.802  9588 10091 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
01-27 16:49:55.802  9588 10091 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
01-27 16:49:55.802  9588 10091 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,01-27 16:49:55.802  9588 10091 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
01-27 16:49:55.802  9588 10091 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 247, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
01-27 16:49:55.802  9588 10091 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
01-27 16:49:55.802  9588 10091 D io.jxcore.node.StreamCopyingThread:  id: 78 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,01-27 16:49:55.812  9588 10090 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 246, thread name: OutgoingSocketThread/Sender): Socket closed
,01-27 16:49:55.812  9588 10089 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 245, thread name: IncomingSocketThread/Receiver): sendto failed: EPIPE (Broken pipe)
01-27 16:49:55.812  9588 10090 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 246, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
01-27 16:49:55.812  9588 10090 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
01-27 16:49:55.812  9588 10090 D io.jxcore.node.StreamCopyingThread:  id: 78 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
01-27 16:49:55.812  9588 10089 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 245, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
01-27 16:49:55.812  9588 10089 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
01-27 16:49:55.812  9588 10089 D io.jxcore.node.StreamCopyingThread:  id: 77 .During the lifetime of the thread the total number of bytes read was 188416 and the total number of bytes written 184320
01-27 16:49:55.812  9588 10090 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
01-27 16:49:55.812  9588 10090 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,01-27 16:49:55.812  3465  3538 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{b4b3b21 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{23f5e8f 6866:com.samsung.fresco.logging/5015}
01-27 16:49:55.812  9588 10089 E io.jxcore.node.IncomingSocketThread: The receiving thread failed with error "Failed to write to the output stream: sendto failed: EPIPE (Broken pipe)", this is likely due to peer having disconnected
01-27 16:49:55.812  9588 10088 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 244, thread name: IncomingSocketThread/Sender): recvfrom failed: ECONNRESET (Connection reset by peer)
01-27 16:49:55.812  9588 10090 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 246, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
01-27 16:49:55.812  9588 10090 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
01-27 16:49:55.812  9588 10090 D io.jxcore.node.StreamCopyingThread:  id: 78 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
01-27 16:49:55.812  9588 10089 D io.jxcore.node.StreamCopyingThread: number of bytes read = 4096
01-27 16:49:55.812  9588 10089 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 245, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
01-27 16:49:55.812  9588 10089 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
01-27 16:49:55.812  9588 10089 D io.jxcore.node.StreamCopyingThread:  id: 77 .During the lifetime of the thread the total number of bytes read was 188416 and the total number of bytes written 184320
,01-27 16:49:55.812  9588 10088 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 244, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
01-27 16:49:55.812  9588 10088 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
01-27 16:49:55.812  9588 10088 D io.jxcore.node.StreamCopyingThread:  id: 77 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
01-27 16:49:55.812  9588 10088 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: recvfrom failed: ECONNRESET (Connection reset by peer)
01-27 16:49:55.812  9588 10088 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
01-27 16:49:55.812  9588 10088 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 244, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
01-27 16:49:55.812  9588 10088 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
01-27 16:49:55.812  9588 10088 D io.jxcore.node.StreamCopyingThread:  id: 77 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
01-27 16:49:55.812  3465  3484 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,01-27 16:49:55.812  3465  4487 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,01-27 16:49:55.812  3465  3973 D ActivityManager:  getDeferredInfo final delay 0
,01-27 16:49:55.822  3465  3973 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{b4b3b21 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{aec1e46 7316:com.sec.spp.push/u0a39}
,01-27 16:49:55.822  7316  7316 E SPPClientService: [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,01-27 16:49:55.822  7316  7316 E SPPClientService: [SystemStateMoniter] Current Time : 221926
,01-27 16:49:55.822  7316  7316 E SPPClientService: [SystemStateMoniter] No Connect : false
,01-27 16:49:55.832  3465  3973 D ActivityManager:  getDeferredInfo final delay 0
,01-27 16:49:55.842  3465  3973 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{b4b3b21 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{831919a 4781:android.process.media/u0a48}
,01-27 16:49:55.842  4781  4781 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,01-27 16:49:55.842  3465  4059 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
01-27 16:49:55.842  3465  4059 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4333, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
01-27 16:49:55.852  3465  4059 D BatteryService: online:4, current avg:-7, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-69
01-27 16:49:55.852  3465  3465 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,01-27 16:49:55.862  3465  3465 I MotionRecognitionService: Plugged
01-27 16:49:55.862  3465  3465 D MotionRecognitionService:   cableConnection= 1
01-27 16:49:55.862  3465  3465 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
01-27 16:49:55.862  3465  3465 D MotionRecognitionService: skip setTransmitPower. 
,01-27 16:49:55.862  3465  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,01-27 16:49:55.862  3950  3950 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
01-27 16:49:55.862  3950  3950 D KeyguardUpdateMonitor: handleBatteryUpdate
,01-27 16:49:55.862  3950  3950 D PowerUI : priorPlugType = 2 mPlugType =  2
,01-27 16:49:55.872  3950  3950 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
01-27 16:49:55.872  3950  3950 D PowerUI.Notification: There is no change about charging status, so return!
,01-27 16:49:55.882  4990  4990 D CommonServiceConfiguration: getStringValueSetting
,01-27 16:49:55.892  3465  4489 D SecContentProvider2: query(), uri = 15 selection = getAppBlockDownloadState
,01-27 16:49:55.892  4990  4990 D BatteryMonitor: new battery level: 100
,01-27 16:49:55.902  4942  4942 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
01-27 16:49:55.902  3465  4416 D ActivityManager:  getDeferredInfo final delay 300
01-27 16:49:55.902  4942  9696 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,01-27 16:49:55.902  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
01-27 16:49:55.902  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,01-27 16:49:55.932  3465  4489 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
01-27 16:49:55.932  3465  4489 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4325, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
01-27 16:49:55.932  3465  4489 D BatteryService: online:4, current avg:-8, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-69
01-27 16:49:55.932  3465  3465 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,01-27 16:49:55.932  3465  3465 I MotionRecognitionService: Plugged
01-27 16:49:55.932  3465  3465 D MotionRecognitionService:   cableConnection= 1
01-27 16:49:55.932  3465  3465 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
01-27 16:49:55.932  3465  3465 D MotionRecognitionService: skip setTransmitPower. 
,01-27 16:49:55.932  3465  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,01-27 16:49:55.932  3950  3950 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
01-27 16:49:55.932  3950  3950 D KeyguardUpdateMonitor: handleBatteryUpdate
,01-27 16:49:55.932  3950  3950 D PowerUI : priorPlugType = 2 mPlugType =  2
,01-27 16:49:55.932  3950  3950 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
01-27 16:49:55.942  3950  3950 D PowerUI.Notification: There is no change about charging status, so return!
,01-27 16:49:55.942  4990  4990 D CommonServiceConfiguration: getStringValueSetting
,01-27 16:49:55.942  4942  4942 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
01-27 16:49:55.942  4942  9696 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,01-27 16:49:55.942  4990  4990 D BatteryMonitor: new battery level: 100
,01-27 16:49:55.962  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
01-27 16:49:55.962  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,01-27 16:49:56.202  7358 10080 I SA_HTTPURLCONNECTION: [RC New] [v2liruge] api execute + 682
,01-27 16:49:56.202  7358 10080 I SA      : [ODM] saveOpenData( GEO_IP, PL )
,01-27 16:49:56.212  7358 10080 I SA      : [OCP] update openData : PL
,01-27 16:49:56.212  7358 10080 I SA      : [TPMU] getNetworkMcc : 260
,01-27 16:49:56.212  7358 10080 I SA      : [SCU] saveMccToPreferece Start
01-27 16:49:56.212  7358 10080 I SA      : [SCU] RegionMCC : 260
01-27 16:49:56.212  7358 10080 I SA      : [SSP] query invoked
,01-27 16:49:56.222  7358 10080 I SA      : [TPMU] GetMccFromDB : null
01-27 16:49:56.222  7358 10080 I SA      : [SCU] getMccFromPreferece mcc = 260
01-27 16:49:56.222  7358 10080 I SA      : [SCU] saveMccToPreferece End
01-27 16:49:56.222  7358 10080 I SA_HTTPURLCONNECTION: [RC New] executeRequest [v2liruge] end. 731
01-27 16:49:56.222  7358 10080 I SA_HTTPURLCONNECTION: [RC New] Execute end
,01-27 16:49:56.222  7358  7358 I SA      : [OR] GetMyCountryZoneTask mcc = 260
01-27 16:49:56.222  7358  7358 I SA      : [OR] GetMyCountryZoneTask Success
,01-27 16:49:56.232  3465  3538 D ActivityManager:  getDeferredInfo final delay 0
,01-27 16:49:56.242  3465  3538 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{b4b3b21 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6ae90c8 9918:com.samsung.android.SettingsReceiver/1000}
,01-27 16:49:56.242  9918  9918 E ActivityThread: Failed to find provider info for com.myscript.atk.rmc
,01-27 16:49:56.242  3465  3977 D ActivityManager:  getDeferredInfo final delay 0
,01-27 16:49:56.252  3465  3977 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{b4b3b21 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b20c561 9931:com.samsung.android.themestore/u0a64}
,01-27 16:49:56.252  9931  9931 D AutoSelfUpgradeReceiver: onReceive() android.net.conn.CONNECTIVITY_CHANGE
,01-27 16:49:56.262  3465  4225 D ActivityManager:  getDeferredInfo final delay 300
,01-27 16:49:56.272  9931  9931 D AutoSelfUpgradeService: onCreate() 
,01-27 16:49:56.272  9931  9931 D AutoSelfUpgradeService: onStartCommand() action.selfupgrade.via.net
,01-27 16:49:56.272  9931 10098 D AutoSelfUpgradeService: startInitAutoSelfUpdate()
,01-27 16:49:56.272  3950  4150 D ViewRootImpl: #3 mView = null
,01-27 16:49:56.282  9931 10098 D AutoSelfUpgradeService: getAlarmIntent() 
,01-27 16:49:56.282  3465  4487 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3465) eventTime = 222384
,01-27 16:49:56.282  9931 10098 D AutoSelfUpgradeService: isAlarmActivated() false
01-27 16:49:56.282  3465  4487 D PowerManagerService: [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3465 (0x0)
01-27 16:49:56.282  9931 10098 I AutoSelfUpgradeService: Not a time to rum self upgrade yet.
01-27 16:49:56.282  3465  4487 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3465, ws=WorkSource{10062}) (elapsedTime=1925)
,01-27 16:49:56.292  9931  9931 D AutoSelfUpgradeService: onDestroy()
,01-27 16:49:56.382  3465  3869 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -51]
01-27 16:49:56.382  3465  3869 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
01-27 16:49:56.382  3465  3869 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -51]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,01-27 16:49:56.392  3950  4150 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,01-27 16:49:56.402  3465  3869 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
,01-27 16:49:56.412  3465  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,01-27 16:49:56.412  3465  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,01-27 16:49:56.422  3465  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,01-27 16:49:56.432  3465  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,01-27 16:49:56.442  3465  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,01-27 16:49:56.442  3465  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
01-27 16:49:56.442  3465  3869 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 503]
01-27 16:49:56.442  3465  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
01-27 16:49:56.442  3465  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,01-27 16:49:56.442  3465  3869 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
01-27 16:49:56.442  3465  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
01-27 16:49:56.442  3465  3869 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=5, legacyType=-1, [] ]
,01-27 16:49:56.442  3465  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
01-27 16:49:56.442  3465  3869 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
01-27 16:49:56.442  3465  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,01-27 16:49:56.442  3465  3869 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
01-27 16:49:56.442  3465  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
01-27 16:49:56.442  3465  3869 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,01-27 16:49:56.562  3465  3538 D ActivityManager:  getDeferredInfo final delay 0
,01-27 16:49:56.582  3465  3538 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{b4b3b21 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ae46917 8255:com.samsung.android.scloud:contentsync/5009}
,01-27 16:49:56.582  8255  8255 I [SC]DetectorReceiver: onReceive [android.net.conn.CONNECTIVITY_CHANGE]
,01-27 16:49:56.582  8255  8255 I [SC]CloudManager: requestInit
,01-27 16:49:56.592  8255  8255 I [SC]Utils: folder : cachecreate fail, try again.
,01-27 16:49:56.592  8255  8255 I [SC]Utils: folder : cache create fail.
01-27 16:49:56.592  8255  8255 I [SC]Utils: folder : thumbnailcreate fail, try again.
01-27 16:49:56.592  8255  8255 I [SC]Utils: folder : thumbnail create fail.
,01-27 16:49:56.592  8255  8255 I [SC]Utils: folder : sharecreate fail, try again.
01-27 16:49:56.592  8255  8255 I [SC]Utils: folder : share create fail.
01-27 16:49:56.592  8255  8255 I [SC]Utils: folder : scratchcreate fail, try again.
01-27 16:49:56.592  8255  8255 I [SC]Utils: folder : scratch create fail.
,01-27 16:49:56.592  8255  8255 I [SC]Utils: folder : eventSynccreate fail, try again.
,01-27 16:49:56.592  8255  8255 I [SC]Utils: folder : eventSync create fail.
,01-27 16:49:56.612  7358  7369 I SA      : [SCU] isHaveSA() - false
01-27 16:49:56.612  7358  7369 I SA      : [OCP] Samsung account is not Signed-in
,01-27 16:49:56.612  7358  7369 I SA      : [OCP] Delete DB (TNC data)
,01-27 16:49:56.622  8255  8255 I [SC]CommonUtil: Samsung Account Not Logged in
,01-27 16:49:56.622  3465  3977 D ActivityManager:  getDeferredInfo final delay 0
,01-27 16:49:56.642  3465  3977 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{b4b3b21 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{67ff174 9951:com.samsung.android.coreapps/5011}
,01-27 16:49:56.732  3465  4416 D ActivityManager:  getDeferredInfo final delay 0
,01-27 16:49:56.732  3465  4416 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{b4b3b21 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{67ff174 9951:com.samsung.android.coreapps/5011}
,01-27 16:49:56.742  3465  3535 D libgps  : agps_ril_update_network_availability: Waiting for IPC connection - timeout
01-27 16:49:56.742  3465  3535 E libgps  : LIBGPS: Cannot communicate (write) with a GPSD
01-27 16:49:56.742  3465  3535 E libgps  : IPC Communication Error, ../../../../tmp/14982990_270314/allPartners/os/android/gps_interface/gpsi_client/GpsiClient.cpp:1729 agps_ril_update_network_availability
,01-27 16:49:56.752  3465  4403 D ActivityManager:  getDeferredInfo final delay 0
,01-27 16:49:56.762  3465  4403 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{b4b3b21 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{67ff174 9951:com.samsung.android.coreapps/5011}
,01-27 16:49:56.772  3465  4403 D ActivityManager:  getDeferredInfo final delay 0
,01-27 16:49:56.782  3465  4403 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{b4b3b21 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{370da43 4847:com.microsoft.skydrive/u0a124}
,01-27 16:49:56.792  3465  4489 W IntentResolver: resolveIntent failed: found match, but none with CATEGORY_DEFAULT
,01-27 16:49:56.802  3465  4416 D ActivityManager:  getDeferredInfo final delay 300
,01-27 16:49:56.832  3014  4500 I SurfaceFlinger: id=20 Removed Uoast (8/10)
,01-27 16:49:56.832  3014  4367 I SurfaceFlinger: id=20 Removed Uoast (-2/10)
,01-27 16:49:56.842  3014  3014 D libEGL  : eglTerminate EGLDisplay = 0x7fc1e5c7e8
,01-27 16:49:57.042  3465  4416 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
01-27 16:49:57.042  3465  4416 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4329, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
01-27 16:49:57.042  3465  4416 D BatteryService: online:4, current avg:-8, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:2
01-27 16:49:57.042  3465  3465 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,01-27 16:49:57.042  3465  3465 I MotionRecognitionService: Plugged
01-27 16:49:57.042  3465  3465 D MotionRecognitionService:   cableConnection= 1
01-27 16:49:57.042  3465  3465 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
01-27 16:49:57.042  3465  3465 D MotionRecognitionService: skip setTransmitPower. 
,01-27 16:49:57.042  3465  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,01-27 16:49:57.042  3950  3950 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
01-27 16:49:57.052  3950  3950 D KeyguardUpdateMonitor: handleBatteryUpdate
01-27 16:49:57.052  3950  3950 D PowerUI : priorPlugType = 2 mPlugType =  2
,01-27 16:49:57.052  3950  3950 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
01-27 16:49:57.052  3950  3950 D PowerUI.Notification: There is no change about charging status, so return!
,01-27 16:49:57.062  4990  4990 D CommonServiceConfiguration: getStringValueSetting
,01-27 16:49:57.062  4990  4990 D BatteryMonitor: new battery level: 100
,01-27 16:49:57.062  4942  4942 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
01-27 16:49:57.062  4942  9696 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,01-27 16:49:57.072  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
01-27 16:49:57.072  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,01-27 16:49:57.102  3465  3538 D ActivityManager:  getDeferredInfo final delay 0
,01-27 16:49:57.112  3465  3538 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{b4b3b21 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a6f0ee3 9979:com.google.android.apps.photos/u0a129}
,01-27 16:49:57.122  3465  3538 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{74193cc u0 com.google.android.apps.photos.actionqueue.INTERNAL_ACTION qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a6f0ee3 9979:com.google.android.apps.photos/u0a129}
,01-27 16:49:57.122  3465  3484 D ActivityManager:  getDeferredInfo final delay 0
,01-27 16:49:57.132  3465  3484 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{b4b3b21 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a6f0ee3 9979:com.google.android.apps.photos/u0a129}
,01-27 16:49:57.172  3465  3538 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{fc26d2a u0 com.google.android.apps.photos.jobqueue.EXECUTE_JOBS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a6f0ee3 9979:com.google.android.apps.photos/u0a129}
01-27 16:49:57.172  3465  4403 D ActivityManager:  getDeferredInfo final delay 300
,01-27 16:49:57.522  3465  3538 D ActivityManager:  getDeferredInfo final delay 0
,01-27 16:49:57.532  3465  3538 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{b4b3b21 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b1960c8 4701:com.sec.android.daemonapp/u0a159}
,01-27 16:49:57.532  4701  4701 D [Weather Widget]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CFAAE09BFCA326403459399C53A4EE79DAC193CEB26509F8FF7498BE5251A746097407E81C28CD811D388C49D613C81F395B356AA489D29CB4C3BE983CCC84BA76AF507AA66A943348DF162DECA2A5A7DD]}
,01-27 16:49:57.532  4701  4701 D [Weather Widget]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CFE2E89F45594D9820F24D88E9AF210A78152C254DDD0027D207FA50AD616546E30965FECE0D7B834EEF4B0E211833EA2B]}
01-27 16:49:57.532  3465  4331 D ActivityManager:  getDeferredInfo final delay 0
,01-27 16:49:57.542  3465  4331 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{b4b3b21 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6283eb1 8868:com.sec.android.app.samsungapps/u0a14}
,01-27 16:49:57.552  8868  8868 D WaitQueueForNetworkActivate: notifyNetworkActivated
01-27 16:49:57.552  8868  8868 D [SAUI]  : NetworkStateReceiver::connected::recovered?false
,01-27 16:49:57.562  8868  8868 D [SAUI]  : Global::recovered::false
,01-27 16:49:57.562  3465  4225 D ActivityManager:  getDeferredInfo final delay 300
,01-27 16:49:57.562  8868  8868 D [SAUI]  : AutoUpdateService::onStartCommand
,01-27 16:49:57.562  8868  8868 D [SAUI]  : AutoUpdateService::runAutoUpdateManager
,01-27 16:49:57.572  8868  8868 D hcjo    : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,01-27 16:49:57.572  8868  8868 D hcjo    : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
,01-27 16:49:57.572  8868  8868 D [SA_INIT]: AutoUpdateManager ServiceInitializer startInitialize()
,01-27 16:49:57.572  8868 10105 D [SA_INIT]: createTaskForServiceInitialize()
,01-27 16:49:57.572  8868 10107 D [SA_INIT]: NetworkStateCheckUnit workImpl()
,01-27 16:49:57.582  8868 10107 D [SA_INIT]: NetworkStateCheckUnit result : 1
,01-27 16:49:57.582  8868  8868 V JOULE   : JOULELOG [main]  com.sec.android.app.joule.f Task [35, 180538412_0] [END] FINISHED
01-27 16:49:57.582  8868  8868 D [SA_INIT]: ServiceInitializer onInitializeResult() reuslt : true
,01-27 16:49:57.582  8868  8868 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,01-27 16:49:57.582  8868  8868 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
01-27 16:49:57.582  8868  8868 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,01-27 16:49:57.602  3465  4226 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,01-27 16:49:57.602  3465  4226 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4328, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
01-27 16:49:57.602  3465  4226 D BatteryService: online:4, current avg:-2, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-67
01-27 16:49:57.602  3465  3465 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,01-27 16:49:57.612  3465  3465 I MotionRecognitionService: Plugged
,01-27 16:49:57.612  3465  3465 D MotionRecognitionService:   cableConnection= 1
01-27 16:49:57.612  3465  3465 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
01-27 16:49:57.612  3465  3465 D MotionRecognitionService: skip setTransmitPower. 
,01-27 16:49:57.612  3465  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,01-27 16:49:57.612  3950  3950 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
01-27 16:49:57.612  3950  3950 D KeyguardUpdateMonitor: handleBatteryUpdate
,01-27 16:49:57.612  3950  3950 D PowerUI : priorPlugType = 2 mPlugType =  2
,01-27 16:49:57.612  3950  3950 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,01-27 16:49:57.612  3950  3950 D PowerUI.Notification: There is no change about charging status, so return!
,01-27 16:49:57.622  4990  4990 D CommonServiceConfiguration: getStringValueSetting
,01-27 16:49:57.622  4942  4942 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
01-27 16:49:57.622  4942  9696 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,01-27 16:49:57.632  4990  4990 D BatteryMonitor: new battery level: 100
,01-27 16:49:57.642  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
01-27 16:49:57.642  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,01-27 16:49:57.662  3465  4152 E Watchdog: !@Sync 7 [01-27 16:49:57.670]
,01-27 16:49:57.762  3465  3483 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,01-27 16:49:57.762  3465  3483 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4328, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
01-27 16:49:57.762  3465  3483 D BatteryService: online:4, current avg:-3, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:149
01-27 16:49:57.762  3465  3465 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,01-27 16:49:57.772  3465  3465 I MotionRecognitionService: Plugged
,01-27 16:49:57.772  3465  3465 D MotionRecognitionService:   cableConnection= 1
01-27 16:49:57.772  3465  3465 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
01-27 16:49:57.772  3465  3465 D MotionRecognitionService: skip setTransmitPower. 
,01-27 16:49:57.772  3465  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,01-27 16:49:57.772  3950  3950 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,01-27 16:49:57.772  3950  3950 D KeyguardUpdateMonitor: handleBatteryUpdate
01-27 16:49:57.772  3950  3950 D PowerUI : priorPlugType = 2 mPlugType =  2
,01-27 16:49:57.782  3950  3950 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,01-27 16:49:57.782  3950  3950 D PowerUI.Notification: There is no change about charging status, so return!
,01-27 16:49:57.782  4990  4990 D CommonServiceConfiguration: getStringValueSetting
,01-27 16:49:57.792  4990  4990 D BatteryMonitor: new battery level: 100
,01-27 16:49:57.792  4942  4942 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
01-27 16:49:57.792  4942  9696 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,01-27 16:49:57.812  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
01-27 16:49:57.812  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,01-27 16:49:57.982 10018 10018 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,01-27 16:49:58.952  3465  6030 D SSRM:n  : SIOP:: AP = 340, PST = 346 (W:14), CP = 285, CUR = -3, LCD = 40
,01-27 16:49:58.992  3465  6030 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,01-27 16:49:59.992  3465  3818 V AlarmManager: Expired Alarm result :8
,01-27 16:50:00.002  3950  3950 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
01-27 16:50:00.002  3950  3950 D KeyguardUpdateMonitor: handleTimeUpdate
,01-27 16:50:00.022  3950  3950 D Clock   : received broadcast android.intent.action.TIME_TICK
,01-27 16:50:00.092  3950  3950 D DateView: received broadcast android.intent.action.TIME_TICK
,01-27 16:50:00.112  4701  4701 D [Weather Widget]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,01-27 16:50:00.112  4701  4701 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EEFA9050249635C043F7E254E316C2550]}
,01-27 16:50:00.112  4701  4701 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EAB01DC5C99149A39F887E17599325AFBFF089086AA9902184ADA25758C536FE2]}
,01-27 16:50:00.122  4701  4701 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EFF0B905BDFF72B69FB632A6CB072B41F95D2E6F4F84443284E97F40042D431D8350388453A923ABD8469D82798FA7548]}
,01-27 16:50:00.122  4701  4701 D [Weather Widget]  : {[A1AF0F6A1A65A89C43D705938923D0FEFB71880C4E84718DA0A3E1F383E54FB27A4284D9BEDF7BAA2ABFFE671EB65C640578FF9DE16A23BFE3280A9DCDBB09A08B20C24EA93CA639BFE88FC835FF7C2D390E9E75FB80A5CC3F1031A5B06CB9F79F5F80BEBB13DF6CC5761063D5CDFCBB]}
,01-27 16:50:00.122  4701  4701 D [Weather Widget]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,01-27 16:50:01.282  9588  9651 I io.jxcore.node.OutgoingSocketThreadTest: OutgoingSocketThreadTest
,01-27 16:50:01.292  9588  9651 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,01-27 16:50:01.292  9588  9651 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testNoAvailablePorts
,01-27 16:50:01.992 10018 10018 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,01-27 16:50:02.262  3465  3869 D ConnectivityService: handlePromptUnvalidated 503
,01-27 16:50:02.302  9588  9651 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,01-27 16:50:02.302  9588  9651 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
,01-27 16:50:02.302  9588  9651 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
,01-27 16:50:02.302  9588  9651 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 256)
,01-27 16:50:02.312  9588  9651 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
01-27 16:50:02.312  9588  9651 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
01-27 16:50:02.312  9588  9651 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 257)
,01-27 16:50:02.312  9588  9651 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
,01-27 16:50:02.312  9588  9651 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
,01-27 16:50:02.312  9588  9651 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
,01-27 16:50:02.322  9588  9651 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,01-27 16:50:02.322  9588  9651 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a4b6969 added. We now have 2 listener(s)
,01-27 16:50:02.322  9588  9651 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a4b6969 added. We now have 3 listener(s)
01-27 16:50:02.322  9588  9651 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,01-27 16:50:02.322  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"44:78:3E:94:2C:E6"}
,01-27 16:50:02.322  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
01-27 16:50:02.322  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"44:78:3E:94:2C:E6"}
01-27 16:50:02.322  9588  9651 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
01-27 16:50:02.322  9588  9651 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c700fee added. We now have 4 listener(s)
01-27 16:50:02.332  9588  9651 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,01-27 16:50:02.332  9588  9651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,01-27 16:50:02.332  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:50:02.342  9588  9651 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
,01-27 16:50:02.342  9588  9651 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
01-27 16:50:02.342  9588  9651 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
,01-27 16:50:02.342  9588  9651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
01-27 16:50:02.342  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,01-27 16:50:02.342  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":4,"address":"44:78:3E:94:2C:E6"}
,01-27 16:50:02.342  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":4,"address":"44:78:3E:94:2C:E6"}
01-27 16:50:02.342  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:02.342  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,01-27 16:50:02.352  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":4,"address":"44:78:3E:94:2C:E6"}
01-27 16:50:02.352  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":4,"address":"44:78:3E:94:2C:E6"}
01-27 16:50:02.352  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:50:02.352  9588  9651 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
01-27 16:50:02.352  9588  9651 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
01-27 16:50:02.352  9588  9651 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
01-27 16:50:02.352  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,01-27 16:50:02.352  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
01-27 16:50:02.352  9588  9651 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
01-27 16:50:02.352  9588  9651 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
01-27 16:50:02.352  9588  9651 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
01-27 16:50:02.352  9588  9651 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,01-27 16:50:02.352  9588  9651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
01-27 16:50:02.352  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
01-27 16:50:02.352  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
01-27 16:50:02.352  9588  9588 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
01-27 16:50:02.352  9588 10114 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,01-27 16:50:02.352  9588 10114 D BluetoothSocket: bindListen(): myUserId = 0
,01-27 16:50:02.352  9588 10114 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,01-27 16:50:02.362  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,01-27 16:50:02.362  9588  9651 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
01-27 16:50:02.362  9588  9651 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,01-27 16:50:02.362  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:50:02.372  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:50:02.372  9588 10114 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,01-27 16:50:02.372  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:50:02.372  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:50:02.372  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
01-27 16:50:02.372  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:50:02.372  9588  9651 D BluetoothAdapter: STATE_ON
01-27 16:50:02.372  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,01-27 16:50:02.372  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
01-27 16:50:02.372  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 4
,01-27 16:50:02.382  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:50:02.382  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:50:02.382  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:02.382  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
01-27 16:50:02.382  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
01-27 16:50:02.382  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "44:78:3E:94:2C:E6"
01-27 16:50:02.382  9588  9651 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 44 78 3E 94 2C E6
01-27 16:50:02.382  9588  9651 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
01-27 16:50:02.382  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
01-27 16:50:02.382  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:02.382  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:50:02.382  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
01-27 16:50:02.382  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
01-27 16:50:02.382  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:02.382  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:02.382  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:02.382  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:50:02.382  9588  9651 D BluetoothAdapter: STATE_ON
01-27 16:50:02.382  9588  9651 D BluetoothLeAdvertiser: start advertising
,01-27 16:50:02.382  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:50:02.392  4942  4966 D BtGatt.GattService: registerClient() - UUID=92044444-f093-4a55-ac33-b397b96af996
,01-27 16:50:02.432  4942  5106 D BtGatt.GattService: onClientRegistered() - UUID=92044444-f093-4a55-ac33-b397b96af996, clientIf=8
,01-27 16:50:02.442  9588  9598 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=8
,01-27 16:50:02.442  4942  9767 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,01-27 16:50:02.452  4942  9767 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
01-27 16:50:02.452  4942  9767 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
01-27 16:50:02.452  4942  5179 D BtGatt.AdvertiseManager: message : 0
,01-27 16:50:02.452  4942  5190 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_ADV
01-27 16:50:02.452  4942  5190 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 27, currDate: 27
01-27 16:50:02.452  4942  5179 D BtGatt.AdvertiseManager: number of adv instance running = 0
01-27 16:50:02.452  4942  5179 D BtGatt.AdvertiseManager: size of list is =0
,01-27 16:50:02.452  4942  5179 D BtGatt.AdvertiseManager: starting advertising
,01-27 16:50:02.462  4942  5179 D BtGatt.AdvertiseManager: isStandardAdv = false
,01-27 16:50:02.462  3465  3973 V AlarmManager:  remove PendingIntent] PendingIntent{5877782: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:02.472  4942  5190 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.test.thalitest : 79
,01-27 16:50:02.472  4942  5190 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.test.thalitest@LowLatency : 24758870
01-27 16:50:02.472  4942  5190 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.test.thalitest@LowLatency : 2
01-27 16:50:02.472  4942  5190 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
01-27 16:50:02.472  4942  5190 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 3 => 3
,01-27 16:50:02.472  4942  5106 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=8, status=0
,01-27 16:50:02.472  3465  4487 V AlarmManager:  remove PendingIntent] PendingIntent{1a3ae93: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:02.482  4942  5179 D BtGatt.AdvertiseManager: starting multi advertising
,01-27 16:50:02.482  4942  5106 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=8, status=0
,01-27 16:50:02.482  4942  5179 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
01-27 16:50:02.482  4942  5179 D BtGatt.AdvertiseManager: clientIf: 8, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,01-27 16:50:02.482  3465  4225 V AlarmManager:  remove PendingIntent] PendingIntent{a944ed0: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
01-27 16:50:02.482  4942  5179 D BtGatt.AdvertiseManager: postCallback clientIf = 8 status = 0
01-27 16:50:02.482  4942  5179 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=8, status=0, isStart=true
01-27 16:50:02.482  9588 10099 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
01-27 16:50:02.482  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:02.482  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:02.482  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
01-27 16:50:02.482  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:50:02.482  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:02.482  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:02.482  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:02.482  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:02.482  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,01-27 16:50:02.482  9588  9651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
01-27 16:50:02.482  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:50:02.492  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:50:02.492  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:02.492  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:02.492  3465  4489 V AlarmManager:  remove PendingIntent] PendingIntent{6091ec9: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
01-27 16:50:02.492  9588  9588 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,01-27 16:50:02.492  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,01-27 16:50:02.492  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
,01-27 16:50:02.492  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
01-27 16:50:02.502  3465  4382 V AlarmManager:  remove PendingIntent] PendingIntent{1b989ce: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
01-27 16:50:02.492  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
01-27 16:50:02.492  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
01-27 16:50:02.492  9588  9588 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
01-27 16:50:02.492  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
01-27 16:50:02.492  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
01-27 16:50:02.492  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,01-27 16:50:02.492  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
01-27 16:50:02.492  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
01-27 16:50:02.492  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
01-27 16:50:02.492  9588  9588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
01-27 16:50:02.492  9588  9588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
01-27 16:50:02.502  9588  9588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
01-27 16:50:02.502  9588  9588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
01-27 16:50:02.502  9588  9588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
01-27 16:50:02.502  9588  9588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
01-27 16:50:02.502  9588  9588 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,01-27 16:50:02.502  3465  4225 V AlarmManager:  remove PendingIntent] PendingIntent{750a0ef: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:02.512  3465  4331 V AlarmManager:  remove PendingIntent] PendingIntent{63787fc: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:02.512  3465  4485 V AlarmManager:  remove PendingIntent] PendingIntent{9fbde85: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:02.712  3465  3858 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: true, uidstate: 6, mProxSensorScreenOff: false
01-27 16:50:02.712  3465  3858 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: true, uidstate: 6, mProxSensorScreenOff: false
,01-27 16:50:02.992  9588  9651 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
01-27 16:50:02.992  9588  9651 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
01-27 16:50:02.992  9588  9651 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
01-27 16:50:02.992  9588  9651 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
01-27 16:50:02.992  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
01-27 16:50:02.992  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
01-27 16:50:02.992  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
01-27 16:50:02.992  9588  9651 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
01-27 16:50:02.992  9588  9651 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
01-27 16:50:02.992  9588 10114 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
01-27 16:50:02.992  9588 10114 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
01-27 16:50:02.992  9588  9651 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
01-27 16:50:02.992  9588 10114 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
01-27 16:50:02.992  9588  9651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
01-27 16:50:02.992  9588  9588 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
01-27 16:50:02.992  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:02.992  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
01-27 16:50:02.992  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
01-27 16:50:02.992  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:02.992  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:02.992  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:02.992  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:50:03.002  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:50:03.002  9588  9651 D BluetoothAdapter: STATE_ON
01-27 16:50:03.002  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,01-27 16:50:03.002  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:50:03.012  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:50:03.012  9588  9651 D BluetoothLeScanner: could not find callback wrapper
01-27 16:50:03.012  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
01-27 16:50:03.012  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:50:03.012  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:03.012  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:03.012  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,01-27 16:50:03.012  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:03.012  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:50:03.012  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:50:03.012  9588  9651 D BluetoothLeAdvertiser: stop advertising
,01-27 16:50:03.022  4942  9680 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
01-27 16:50:03.022  4942  9680 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,01-27 16:50:03.032  4942  5190 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_ADV
01-27 16:50:03.032  4942  5179 D BtGatt.AdvertiseManager: message : 1
,01-27 16:50:03.032  4942  5190 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 27, currDate: 27
01-27 16:50:03.032  4942  5190 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
01-27 16:50:03.032  4942  5190 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 3 => 3
01-27 16:50:03.032  4942  5190 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
01-27 16:50:03.032  4942  5179 D BtGatt.AdvertiseManager: stop advertise for client =  8
,01-27 16:50:03.032  4942  5179 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 8
,01-27 16:50:03.032  4942  5179 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,01-27 16:50:03.042  3465  3973 V AlarmManager:  remove PendingIntent] PendingIntent{de874da: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:03.042  4942  5106 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=8, status=0
01-27 16:50:03.042  4942  5106 D BtGatt.GattService: Client app is not null!
,01-27 16:50:03.042  9588  9599 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,01-27 16:50:03.042  4942  5319 D BtGatt.GattService: unregisterClient() - clientIf=8
,01-27 16:50:03.052  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,01-27 16:50:03.052  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:03.052  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
01-27 16:50:03.052  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:03.052  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:03.052  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:50:03.052  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
01-27 16:50:03.052  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
01-27 16:50:03.052  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
01-27 16:50:03.052  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:50:03.052  3465  4416 V AlarmManager:  remove PendingIntent] PendingIntent{a305d0b: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:03.062  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:03.062  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,01-27 16:50:03.062  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:03.062  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:03.062  9588  9588 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
01-27 16:50:03.062  9588  9588 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
01-27 16:50:03.062  9588  9588 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
01-27 16:50:03.062  9588  9588 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
01-27 16:50:03.062  9588  9588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
01-27 16:50:03.062  9588  9588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
01-27 16:50:03.062  9588  9588 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
01-27 16:50:03.062  9588  9588 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
01-27 16:50:03.062  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
01-27 16:50:03.062  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
01-27 16:50:03.062  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
01-27 16:50:03.062  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
01-27 16:50:03.062  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
01-27 16:50:03.062  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
01-27 16:50:03.062  9588  9588 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,01-27 16:50:03.072  3465  3977 V AlarmManager:  remove PendingIntent] PendingIntent{47327e8: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:03.082  3465  3973 V AlarmManager:  remove PendingIntent] PendingIntent{a0de01: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:03.082  3465  4489 V AlarmManager:  remove PendingIntent] PendingIntent{de904a6: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:03.092  3465  4059 V AlarmManager:  remove PendingIntent] PendingIntent{a05bee7: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:03.112  3465  4488 V AlarmManager:  remove PendingIntent] PendingIntent{246da94: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:03.112  3465  4225 V AlarmManager:  remove PendingIntent] PendingIntent{13c593d: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:03.402  3465  6068 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,01-27 16:50:03.562  9588  9588 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,01-27 16:50:06.002 10018 10018 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,01-27 16:50:06.002 10018 10018 I dhcpcd  : wlan0: no IPv6 Routers available
,01-27 16:50:06.062  9588  9651 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
,01-27 16:50:06.072  9588  9651 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
01-27 16:50:06.072  9588  9651 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
01-27 16:50:06.072  9588  9651 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
01-27 16:50:06.072  9588  9651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
01-27 16:50:06.072  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
01-27 16:50:06.072  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,01-27 16:50:06.082  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,01-27 16:50:06.082  9588  9651 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
01-27 16:50:06.082  9588  9651 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,01-27 16:50:06.092  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:50:06.092  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:50:06.092  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:50:06.102  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:50:06.102  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,01-27 16:50:06.102  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:50:06.112  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:50:06.112  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
01-27 16:50:06.112  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
01-27 16:50:06.112  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 4
,01-27 16:50:06.112  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:50:06.122  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:50:06.132  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:50:06.132  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:50:06.132  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:50:06.132  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
01-27 16:50:06.132  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
01-27 16:50:06.132  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
01-27 16:50:06.142  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,01-27 16:50:06.142  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:06.142  9588  9651 D BluetoothLeScanner: Start Scan
,01-27 16:50:06.142  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:50:06.142  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:50:06.152  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:50:06.152  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:50:06.162  4942  5319 D BtGatt.GattService: registerClient() - UUID=462123e2-31c6-4208-accc-1a429632e0c1
,01-27 16:50:06.202  4942  5106 D BtGatt.GattService: onClientRegistered() - UUID=462123e2-31c6-4208-accc-1a429632e0c1, clientIf=8
,01-27 16:50:06.202  9588  9598 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=8
01-27 16:50:06.202  4942  9732 D BtGatt.GattService: start scan with filters
,01-27 16:50:06.212  4942  9732 D BtGatt.GattService: getScanSettings
,01-27 16:50:06.212  4942  9732 D BtGatt.GattService: Is it foreground application = true
,01-27 16:50:06.212  4942  9732 D BtGatt.GattService: not a background application
,01-27 16:50:06.232  4942  9732 D BtGatt.GattService: [GSIM LOG]: getActualScanMode (2/100 vs 100/5)
,01-27 16:50:06.242  4942  9732 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
01-27 16:50:06.242  4942  9732 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,01-27 16:50:06.242  4942  5190 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_SCAN
01-27 16:50:06.242  4942  5190 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 27, currDate: 27
,01-27 16:50:06.242  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,01-27 16:50:06.242  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:06.242  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,01-27 16:50:06.242  4942  5182 D BtGatt.ScanManager: handling starting scan
01-27 16:50:06.242  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:06.242  4942  5182 D BluetoothAdapter: STATE_ON
01-27 16:50:06.252  9588  9588 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
01-27 16:50:06.252  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
01-27 16:50:06.252  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
01-27 16:50:06.252  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
01-27 16:50:06.252  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
01-27 16:50:06.252  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
01-27 16:50:06.252  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
01-27 16:50:06.252  3465  4331 V AlarmManager:  remove PendingIntent] PendingIntent{91a4c39: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
01-27 16:50:06.252  4942  5182 D BluetoothAdapter: STATE_ON
01-27 16:50:06.252  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
01-27 16:50:06.252  9588  9588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
,01-27 16:50:06.252  9588  9651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,01-27 16:50:06.252  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:50:06.262  4942  5106 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=8, status=0, action=1
,01-27 16:50:06.262  4942  5106 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
01-27 16:50:06.262  3465  4042 V AlarmManager:  remove PendingIntent] PendingIntent{82027e: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}},
01-27 16:50:06.262  4942  5190 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest : 43
,01-27 16:50:06.262  4942  5190 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest, com.test.thalitest
01-27 16:50:06.262  4942  5182 D BtGatt.ScanManager: set filter index= 7 for clientIf= 8
01-27 16:50:06.262  4942  5182 D BtGatt.ScanManager: High Rssi Filter value is = -128
01-27 16:50:06.262  4942  5182 D BtGatt.ScanManager: Low Rssi Filter value is = -128
01-27 16:50:06.262  4942  5182 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =2
01-27 16:50:06.262  4942  5106 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=8, status=0, action=0, availableSpace=27
,01-27 16:50:06.262  4942  5106 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
01-27 16:50:06.262  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:06.262  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
01-27 16:50:06.262  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:06.262  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:06.262  9588  9588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,01-27 16:50:06.272  4942  5182 D BtGatt.ScanManager: Starting BLE batch scan
01-27 16:50:06.272  3465  4488 V AlarmManager:  remove PendingIntent] PendingIntent{f91a3df: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
01-27 16:50:06.272  4942  5182 D BtGatt.ScanManager: configuring batch scan storage, appIf 8
,01-27 16:50:06.282  4942  5106 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=8, status=0
,01-27 16:50:06.282  4942  5106 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
01-27 16:50:06.282  4942  5190 D BtGatt.GattService: [GSIM LOG]: increaseScanCount 4 Battery : com.test.thalitest : 1
01-27 16:50:06.282  4942  5190 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24758870
01-27 16:50:06.282  4942  5190 D BtGatt.GattService: [GSIM LOG]: setRequestedScanType : com.test.thalitest : 2
01-27 16:50:06.282  4942  5190 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
01-27 16:50:06.282  4942  5190 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
01-27 16:50:06.282  4942  5190 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 4 => 4
,01-27 16:50:06.282  4942  5190 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 4 => 4
01-27 16:50:06.282  4942  5190 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
01-27 16:50:06.282  4942  5190 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 4 => 4
01-27 16:50:06.282  4942  5190 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 4 => 4
01-27 16:50:06.282  4942  5190 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
01-27 16:50:06.282  4942  5190 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
,01-27 16:50:06.282  4942  5190 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 4 => 4
01-27 16:50:06.282  4942  5190 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 4 => 4
01-27 16:50:06.282  4942  5190 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24758870
01-27 16:50:06.282  4942  5190 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 4
,01-27 16:50:06.292  9588  9588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
01-27 16:50:06.292  9588  9588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,01-27 16:50:06.292  3465  4487 V AlarmManager:  remove PendingIntent] PendingIntent{e6ae82c: PendingIntentRecord{44a72f5 com.android.bluetooth broadcastIntent}}
01-27 16:50:06.292  9588  9588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
01-27 16:50:06.292  9588  9588 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
01-27 16:50:06.292  4942  5106 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=8, status=0, startStopAction=1
01-27 16:50:06.292  4942  5106 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
01-27 16:50:06.292  4942  4958 I art     : Background sticky concurrent mark sweep GC freed 39025(2MB) AllocSpace objects, 25(500KB) LOS objects, 59% free, 2MB/6MB, paused 7.287ms total 79.407ms
,01-27 16:50:06.292  3465  4042 V AlarmManager:  remove PendingIntent] PendingIntent{137c88a: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:06.292  4942  5190 D BtGatt.GattService: [GSIM LOG]: com.samsung.android.beaconmanager@Custom, R time : 6 => 10
,01-27 16:50:06.302  3465  3973 V AlarmManager:  remove PendingIntent] PendingIntent{8969efb: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:06.312  3465  3977 V AlarmManager:  remove PendingIntent] PendingIntent{db45b18: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:06.312  4942  5190 D BtGatt.GattService: [GSIM LOG]: com.samsung.android.beaconmanager@Custom, A time : 5 => 9
,01-27 16:50:06.312  4942  5190 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.samsung.android.beaconmanager : 2
01-27 16:50:06.312  4942  5190 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
01-27 16:50:06.312  4942  5190 D BtGatt.GattService: [GSIM LOG]: com.samsung.android.beaconmanager@Custom, R time : 10 => 10
01-27 16:50:06.312  4942  5190 D BtGatt.GattService: [GSIM LOG]: com.samsung.android.beaconmanager@LowLatency, A time : 1 => 1
01-27 16:50:06.312  4942  5190 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.samsung.android.beaconmanager : 24758870
,01-27 16:50:06.312  3465  4487 V AlarmManager:  remove PendingIntent] PendingIntent{61c4971: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:06.322  3465  4059 V AlarmManager:  remove PendingIntent] PendingIntent{6d1e356: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:06.322  3465  4489 V AlarmManager:  remove PendingIntent] PendingIntent{5262fd7: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:06.322  3465  4331 V AlarmManager:  remove PendingIntent] PendingIntent{b2010c4: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:06.332  3465  4488 V AlarmManager:  remove PendingIntent] PendingIntent{d5b0bad: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:06.332  3465  4487 V AlarmManager:  remove PendingIntent] PendingIntent{220dee2: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:06.332  3465  4059 V AlarmManager:  remove PendingIntent] PendingIntent{b3f273: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:06.342  3465  4416 V AlarmManager:  remove PendingIntent] PendingIntent{86f7530: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:06.382  3465  4331 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,01-27 16:50:06.382  3465  4331 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4332, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
01-27 16:50:06.382  3465  4331 D BatteryService: online:4, current avg:67, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-4
01-27 16:50:06.382  3465  3465 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,01-27 16:50:06.382  3465  3465 I MotionRecognitionService: Plugged
,01-27 16:50:06.382  3465  3465 D MotionRecognitionService:   cableConnection= 1
01-27 16:50:06.382  3465  3465 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
01-27 16:50:06.382  3465  3465 D MotionRecognitionService: skip setTransmitPower. 
,01-27 16:50:06.382  3465  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,01-27 16:50:06.392  3950  3950 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
01-27 16:50:06.392  3950  3950 D KeyguardUpdateMonitor: handleBatteryUpdate
01-27 16:50:06.392  3950  3950 D PowerUI : priorPlugType = 2 mPlugType =  2
,01-27 16:50:06.392  3950  3950 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
01-27 16:50:06.392  3950  3950 D PowerUI.Notification: There is no change about charging status, so return!
,01-27 16:50:06.392  4990  4990 D CommonServiceConfiguration: getStringValueSetting
,01-27 16:50:06.402  4990  4990 D BatteryMonitor: new battery level: 100
,01-27 16:50:06.412  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
01-27 16:50:06.412  4942  4942 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
01-27 16:50:06.412  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
01-27 16:50:06.412  4942  9696 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,01-27 16:50:06.592  3465  4059 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
01-27 16:50:06.592  3465  4059 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4335, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
01-27 16:50:06.592  3465  4059 D BatteryService: online:4, current avg:67, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:95
01-27 16:50:06.592  3465  3465 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,01-27 16:50:06.592  3465  3465 I MotionRecognitionService: Plugged
01-27 16:50:06.592  3465  3465 D MotionRecognitionService:   cableConnection= 1
01-27 16:50:06.592  3465  3465 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
01-27 16:50:06.592  3465  3465 D MotionRecognitionService: skip setTransmitPower. 
,01-27 16:50:06.602  3465  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,01-27 16:50:06.602  3950  3950 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
01-27 16:50:06.602  3950  3950 D KeyguardUpdateMonitor: handleBatteryUpdate
,01-27 16:50:06.602  3950  3950 D PowerUI : priorPlugType = 2 mPlugType =  2
,01-27 16:50:06.602  3950  3950 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,01-27 16:50:06.602  3950  3950 D PowerUI.Notification: There is no change about charging status, so return!
,01-27 16:50:06.612  4990  4990 D CommonServiceConfiguration: getStringValueSetting
,01-27 16:50:06.622  4942  4942 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,01-27 16:50:06.622  4942  9696 D HeadsetStateMachine: Disconnected process message: 10, size: 0
01-27 16:50:06.622  4990  4990 D BatteryMonitor: new battery level: 100
,01-27 16:50:06.632  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,01-27 16:50:06.632  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,01-27 16:50:06.792  9588  9588 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
01-27 16:50:06.792  9588  9588 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
01-27 16:50:06.792  9588  9588 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,01-27 16:50:07.292  3465  3818 V AlarmManager: Expired Alarm result :4
,01-27 16:50:07.302  4942  4942 D BtGatt.ScanManager: awakened up at time 233401
,01-27 16:50:07.302  4942  5182 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 8
,01-27 16:50:07.302  3465  4403 V AlarmManager:  remove PendingIntent] PendingIntent{e72072e: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}},
,01-27 16:50:07.312  4942  5106 D BtGatt.GattService: onBatchScanReports() - clientIf=8, status=0, reportType=2, numRecords=6
,01-27 16:50:07.312  3465  4416 V AlarmManager:  remove PendingIntent] PendingIntent{5142cf: PendingIntentRecord{44a72f5 com.android.bluetooth broadcastIntent}}
01-27 16:50:07.312  4942  5106 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
01-27 16:50:07.312  4942  5106 D BtGatt.GattService: current time is 233414480410
,01-27 16:50:07.312  4942  5106 D BtGatt.GattService: Batch record : [-83, 7, 98, -20, -22, 96, 1, -128, -81, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 13, -88, -127, -107, -23, 95, 111, 0, 37, -47, 14, -113, 116, -46, 1, -128, -87, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -76, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 116, -43, -111, -91, -20, -29, 1, -128, -77, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -83, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -84, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0],
01-27 16:50:07.312  4942  5106 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 13, -88, -127, -107, -23, 95, 111]
,01-27 16:50:07.312  4942  5106 D ScanRecord: parseFromBytes
,01-27 16:50:07.312  4942  5106 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
01-27 16:50:07.312  4942  5106 D ScanRecord: parseFromBytes
01-27 16:50:07.322  4942  5106 D ScanRecord: first manudata for manu ID
01-27 16:50:07.322  4942  5106 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
01-27 16:50:07.322  4942  5106 D ScanRecord: parseFromBytes
01-27 16:50:07.322  4942  5106 D ScanRecord: first manudata for manu ID
01-27 16:50:07.322  4942  5106 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
01-27 16:50:07.322  4942  5106 D ScanRecord: parseFromBytes
01-27 16:50:07.322  4942  5106 D ScanRecord: first manudata for manu ID
01-27 16:50:07.322  4942  5106 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
,01-27 16:50:07.322  4942  5106 D ScanRecord: parseFromBytes
01-27 16:50:07.322  4942  5106 D ScanRecord: first manudata for manu ID
,01-27 16:50:07.332  4942  5106 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
01-27 16:50:07.332  4942  5106 D ScanRecord: parseFromBytes
01-27 16:50:07.332  4942  5106 D ScanRecord: first manudata for manu ID
01-27 16:50:07.332  9588 10099 D ScanRecord: parseFromBytes
01-27 16:50:07.332  9588 10099 D ScanRecord: first manudata for manu ID
01-27 16:50:07.332  9588 10099 D ScanRecord: parseFromBytes
,01-27 16:50:07.332  9588 10099 D ScanRecord: first manudata for manu ID
01-27 16:50:07.332  9588 10099 D ScanRecord: parseFromBytes
01-27 16:50:07.332  9588 10099 D ScanRecord: first manudata for manu ID
01-27 16:50:07.332  9588 10099 D ScanRecord: parseFromBytes
01-27 16:50:07.332  3465  4042 V AlarmManager:  remove PendingIntent] PendingIntent{eb45c: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
01-27 16:50:07.332  9588 10099 D ScanRecord: first manudata for manu ID
01-27 16:50:07.332  9588 10099 D ScanRecord: parseFromBytes
,01-27 16:50:07.332  9588 10099 D ScanRecord: first manudata for manu ID
01-27 16:50:07.332  9588 10099 D ScanRecord: parseFromBytes
,01-27 16:50:07.332  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 6. Current thread: Thread[main,5,main], id: 1
01-27 16:50:07.332  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=D2:74:8F:0E:D1:25, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-87, mTimestampNanos=232565654217}
,01-27 16:50:07.332  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=C8:16:A4:7E:61:23, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-76, mTimestampNanos=232865654217}
01-27 16:50:07.342  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=E3:EC:A5:91:D5:74, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-77, mTimestampNanos=232915654217}
01-27 16:50:07.342  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=F4:45:54:B3:86:47, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-83, mTimestampNanos=233015654217}
,01-27 16:50:07.342  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=DB:69:06:8B:FC:D2, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-84, mTimestampNanos=233315654217}
01-27 16:50:07.342  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=60:EA:EC:62:07:AD, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[13, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-81, mTimestampNanos=233365654217}
01-27 16:50:07.342  3465  3484 V AlarmManager:  remove PendingIntent] PendingIntent{c5f0365: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:07.342  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = A8:81:95:E9:5F:6F, provideBluetoothMacAddressRequestId = nullextra info = 13]
,01-27 16:50:07.342  9588  9588 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: Resolved advertisement type: ADVERTISEMENT_PEER_PROPERTIES
01-27 16:50:07.342  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: Parsed advertisment: [UUID = b6a44ad1-d319-4b3a-815d-8b805a47fb51, bluetoothMacAddress = A8:81:95:E9:5F:6F, provideBluetoothMacAddressRequestId = nullextra info = 13]
,01-27 16:50:07.342  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult onPeerDiscovered [A8:81:95:E9:5F:6F 13]
01-27 16:50:07.342  9588  9588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onPeerDiscovered: [A8:81:95:E9:5F:6F 13]
01-27 16:50:07.342  9588  9588 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: [A8:81:95:E9:5F:6F 13]
01-27 16:50:07.342  9588  9588 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: Want to call onPeerAdded. Listeners size = 1
01-27 16:50:07.342  9588  9588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onPeerAdded: [A8:81:95:E9:5F:6F 13]
,01-27 16:50:07.342  9588  9588 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [A8:81:95:E9:5F:6F 13], added - the peer count is 1
01-27 16:50:07.342  3465  4487 V AlarmManager:  remove PendingIntent] PendingIntent{c9b683a: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
01-27 16:50:07.342  9588  9588 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [A8:81:95:E9:5F:6F 13], Bluetooth address: A8:81:95:E9:5F:6F, device name: 'null', device address: 'null'
,01-27 16:50:07.352  3465  4403 V AlarmManager:  remove PendingIntent] PendingIntent{ec93ceb: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:07.352  3465  3973 V AlarmManager:  remove PendingIntent] PendingIntent{500ba48: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:07.362  3465  3977 V AlarmManager:  remove PendingIntent] PendingIntent{5c170e1: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:07.362  3465  4488 V AlarmManager:  remove PendingIntent] PendingIntent{2c7ce06: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:07.372  3465  4059 V AlarmManager:  remove PendingIntent] PendingIntent{e7cbcc7: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:07.602  8868  8868 D PreloadUpdateManagerStateMachine: execute::IDLE:EXECUTE
01-27 16:50:07.602  8868  8868 D PreloadUpdateManagerStateMachine: exit::IDLE
01-27 16:50:07.602  8868  8868 D PreloadUpdateManagerStateMachine: entry::CHECK_TIMEOUT_FOR_UPDATE
,01-27 16:50:07.602  8868  8868 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
01-27 16:50:07.602  8868  8868 D PreloadUpdateManagerStateMachine: execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,01-27 16:50:07.602  8868  8868 D PreloadUpdateManagerStateMachine: exit::CHECK_TIMEOUT_FOR_UPDATE
,01-27 16:50:07.602  8868  8868 D PreloadUpdateManagerStateMachine: entry::IDLE
,01-27 16:50:08.312  3465  3818 V AlarmManager: Expired Alarm result :4
,01-27 16:50:08.322  4942  4942 D BtGatt.ScanManager: awakened up at time 234423
,01-27 16:50:08.322  4942  5182 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 8
01-27 16:50:08.322  3465  4485 V AlarmManager:  remove PendingIntent] PendingIntent{d02c492: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:08.332  4942  5106 D BtGatt.GattService: onBatchScanReports() - clientIf=8, status=0, reportType=2, numRecords=6
01-27 16:50:08.332  4942  5106 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
01-27 16:50:08.332  4942  5106 D BtGatt.GattService: current time is 234434338986
01-27 16:50:08.332  4942  5106 D BtGatt.GattService: Batch record : [-83, 7, 98, -20, -22, 96, 1, -128, -68, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 13, -88, -127, -107, -23, 95, 111, 0, 37, -47, 14, -113, 116, -46, 1, -128, -86, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -77, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 116, -43, -111, -91, -20, -29, 1, -128, -77, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -80, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -79, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,01-27 16:50:08.332  3465  4059 V AlarmManager:  remove PendingIntent] PendingIntent{cfe5e63: PendingIntentRecord{44a72f5 com.android.bluetooth broadcastIntent}}
01-27 16:50:08.332  4942  5106 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 13, -88, -127, -107, -23, 95, 111]
01-27 16:50:08.332  4942  5106 D ScanRecord: parseFromBytes
01-27 16:50:08.332  4942  5106 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
01-27 16:50:08.332  4942  5106 D ScanRecord: parseFromBytes
01-27 16:50:08.332  4942  5106 D ScanRecord: first manudata for manu ID
,01-27 16:50:08.332  4942  5106 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
,01-27 16:50:08.332  4942  5106 D ScanRecord: parseFromBytes
01-27 16:50:08.332  4942  5106 D ScanRecord: first manudata for manu ID
01-27 16:50:08.332  4942  5106 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
01-27 16:50:08.342  4942  5106 D ScanRecord: parseFromBytes
01-27 16:50:08.342  4942  5106 D ScanRecord: first manudata for manu ID
01-27 16:50:08.342  4942  5106 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
01-27 16:50:08.342  4942  5106 D ScanRecord: parseFromBytes
,01-27 16:50:08.342  4942  5106 D ScanRecord: first manudata for manu ID
01-27 16:50:08.342  4942  5106 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
01-27 16:50:08.342  4942  5106 D ScanRecord: parseFromBytes
,01-27 16:50:08.342  4942  5106 D ScanRecord: first manudata for manu ID
01-27 16:50:08.342  9588  9598 D ScanRecord: parseFromBytes
01-27 16:50:08.342  9588  9598 D ScanRecord: parseFromBytes
,01-27 16:50:08.342  9588  9598 D ScanRecord: first manudata for manu ID
01-27 16:50:08.342  9588  9598 D ScanRecord: parseFromBytes
01-27 16:50:08.342  9588  9598 D ScanRecord: first manudata for manu ID
,01-27 16:50:08.342  9588  9598 D ScanRecord: parseFromBytes
,01-27 16:50:08.342  9588  9598 D ScanRecord: first manudata for manu ID
01-27 16:50:08.342  9588  9598 D ScanRecord: parseFromBytes
01-27 16:50:08.342  9588  9598 D ScanRecord: first manudata for manu ID
01-27 16:50:08.342  9588  9598 D ScanRecord: parseFromBytes
01-27 16:50:08.342  9588  9598 D ScanRecord: first manudata for manu ID
01-27 16:50:08.342  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 6. Current thread: Thread[main,5,main], id: 1
,01-27 16:50:08.342  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=D2:74:8F:0E:D1:25, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-86, mTimestampNanos=233535170140}
01-27 16:50:08.342  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=C8:16:A4:7E:61:23, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-77, mTimestampNanos=233885170140}
01-27 16:50:08.342  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=E3:EC:A5:91:D5:74, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-77, mTimestampNanos=233885170140}
01-27 16:50:08.342  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=F4:45:54:B3:86:47, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-80, mTimestampNanos=234285170140}
01-27 16:50:08.342  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = 86:B3:54:45:F4:B6, provideBluetoothMacAddressRequestId = nullextra info = 71]
,01-27 16:50:08.342  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
01-27 16:50:08.342  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=DB:69:06:8B:FC:D2, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[-46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-79, mTimestampNanos=234285170140}
01-27 16:50:08.352  3465  4225 V AlarmManager:  remove PendingIntent] PendingIntent{ca28a60: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
01-27 16:50:08.342  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = FC:8B:06:69:DB:B6, provideBluetoothMacAddressRequestId = nullextra info = 210]
01-27 16:50:08.342  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
,01-27 16:50:08.342  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=60:EA:EC:62:07:AD, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[13, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-68, mTimestampNanos=234335170140}
01-27 16:50:08.342  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = A8:81:95:E9:5F:6F, provideBluetoothMacAddressRequestId = nullextra info = 13]
01-27 16:50:08.342  9588  9588 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: Resolved advertisement type: ADVERTISEMENT_PEER_PROPERTIES
01-27 16:50:08.352  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: Parsed advertisment: [UUID = b6a44ad1-d319-4b3a-815d-8b805a47fb51, bluetoothMacAddress = A8:81:95:E9:5F:6F, provideBluetoothMacAddressRequestId = nullextra info = 13]
01-27 16:50:08.352  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult onPeerDiscovered [A8:81:95:E9:5F:6F 13]
01-27 16:50:08.352  9588  9588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onPeerDiscovered: [A8:81:95:E9:5F:6F 13]
,01-27 16:50:08.352  9588  9588 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: [A8:81:95:E9:5F:6F 13]
01-27 16:50:08.352  9588  9588 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: has more info: false,  extra info differs: false
01-27 16:50:08.352  9588  9588 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [A8:81:95:E9:5F:6F 13] updated - the peer count is 1
,01-27 16:50:08.362  3465  4382 V AlarmManager:  remove PendingIntent] PendingIntent{d9e5b19: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:08.362  3465  4489 V AlarmManager:  remove PendingIntent] PendingIntent{a8497de: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:08.372  3465  3484 V AlarmManager:  remove PendingIntent] PendingIntent{46e7dbf: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:08.372  3465  4226 V AlarmManager:  remove PendingIntent] PendingIntent{e15ec8c: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:08.382  3465  4403 V AlarmManager:  remove PendingIntent] PendingIntent{db08fd5: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:08.382  3465  4416 V AlarmManager:  remove PendingIntent] PendingIntent{3be53ea: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:08.392  3465  4331 V AlarmManager:  remove PendingIntent] PendingIntent{69736db: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:09.022  3465  6030 D SSRM:n  : SIOP:: AP = 330, PST = 347 (W:14), CP = 282, CUR = 67, LCD = 40
,01-27 16:50:09.272  9588  9651 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
01-27 16:50:09.272  9588  9651 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
01-27 16:50:09.272  9588  9651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
01-27 16:50:09.272  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,01-27 16:50:09.282  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":5,"address":"44:78:3E:94:2C:E6"}
,01-27 16:50:09.282  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":5,"address":"44:78:3E:94:2C:E6"}
01-27 16:50:09.282  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:09.282  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,01-27 16:50:09.292  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":5,"address":"44:78:3E:94:2C:E6"}
,01-27 16:50:09.292  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":5,"address":"44:78:3E:94:2C:E6"}
01-27 16:50:09.292  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:09.292  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
01-27 16:50:09.292  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
01-27 16:50:09.292  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
01-27 16:50:09.292  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 5
01-27 16:50:09.292  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
01-27 16:50:09.292  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
01-27 16:50:09.292  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
01-27 16:50:09.292  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
01-27 16:50:09.292  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
01-27 16:50:09.292  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:09.292  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 5
01-27 16:50:09.292  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted false Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:50:09.292  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:09.292  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
01-27 16:50:09.292  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
01-27 16:50:09.292  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted true Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:09.292  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop scanner Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:09.292  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:50:09.292  9588  9651 D BluetoothAdapter: STATE_ON
01-27 16:50:09.292  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:50:09.302  4942  9680 D BtGatt.GattService: flushPendingBatchResults - clientIf=8, isServer=false
01-27 16:50:09.302  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,01-27 16:50:09.302  4942  5182 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 8
,01-27 16:50:09.302  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:50:09.302  3465  4226 V AlarmManager:  remove PendingIntent] PendingIntent{97b4578: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:09.302  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:50:09.302  9588  9651 D BluetoothLeScanner: Stop Scan
,01-27 16:50:09.302  4942  5106 D BtGatt.GattService: onBatchScanReports() - clientIf=8, status=0, reportType=2, numRecords=7
01-27 16:50:09.302  3465  3973 V AlarmManager:  remove PendingIntent] PendingIntent{b775451: PendingIntentRecord{44a72f5 com.android.bluetooth broadcastIntent}}
01-27 16:50:09.302  4942  5106 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
01-27 16:50:09.302  4942  5106 D BtGatt.GattService: current time is 235408288985
01-27 16:50:09.302  4942  5106 D BtGatt.GattService: Batch record : [-83, 7, 98, -20, -22, 96, 1, -128, -67, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 13, -88, -127, -107, -23, 95, 111, 0, 81, 34, 97, 112, -14, -5, 1, -128, -78, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -90, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -79, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -92, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -87, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -80, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
01-27 16:50:09.302  4942  5106 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 13, -88, -127, -107, -23, 95, 111]
,01-27 16:50:09.302  4942  5106 D ScanRecord: parseFromBytes
01-27 16:50:09.302  4942  5106 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
01-27 16:50:09.302  4942  5106 D ScanRecord: parseFromBytes
01-27 16:50:09.302  4942  5106 D ScanRecord: first manudata for manu ID
01-27 16:50:09.312  4942  5106 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
01-27 16:50:09.312  4942  5106 D ScanRecord: parseFromBytes
01-27 16:50:09.312  4942  5106 D ScanRecord: first manudata for manu ID
01-27 16:50:09.312  4942  5106 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
01-27 16:50:09.312  4942  5106 D ScanRecord: parseFromBytes
,01-27 16:50:09.312  4942  5106 D ScanRecord: first manudata for manu ID
01-27 16:50:09.312  4942  5106 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
01-27 16:50:09.312  4942  5106 D ScanRecord: parseFromBytes
,01-27 16:50:09.312  4942  5106 D ScanRecord: first manudata for manu ID,
,01-27 16:50:09.312  4942  5106 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
01-27 16:50:09.312  4942  5106 D ScanRecord: parseFromBytes
01-27 16:50:09.312  4942  5106 D ScanRecord: first manudata for manu ID
01-27 16:50:09.312  4942  5106 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
01-27 16:50:09.312  4942  5106 D ScanRecord: parseFromBytes
01-27 16:50:09.312  4942  5106 D ScanRecord: first manudata for manu ID
01-27 16:50:09.312  4942  4960 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
01-27 16:50:09.312  4942  4960 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
01-27 16:50:09.312  4942  4960 D BtGatt.GattService: stopScan() - queue size =2
01-27 16:50:09.312  4942  5190 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_SCAN
01-27 16:50:09.312  4942  5190 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 27, currDate: 27
01-27 16:50:09.312  4942  5190 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
01-27 16:50:09.312  4942  5190 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 4 => 4
01-27 16:50:09.312  4942  5190 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 4 => 4
01-27 16:50:09.312  4942  5190 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_ACTUAL_DB
01-27 16:50:09.312  4942  5190 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_REQUESTED_DB
01-27 16:50:09.312  9588 10099 D ScanRecord: parseFromBytes
01-27 16:50:09.312  9588 10099 D ScanRecord: first manudata for manu ID
01-27 16:50:09.312  9588 10099 D ScanRecord: parseFromBytes
01-27 16:50:09.312  9588 10099 D ScanRecord: first manudata for manu ID
01-27 16:50:09.312  9588 10099 D ScanRecord: parseFromBytes
01-27 16:50:09.312  9588 10099 D ScanRecord: first manudata for manu ID
01-27 16:50:09.312  9588 10099 D ScanRecord: parseFromBytes
01-27 16:50:09.312  9588 10099 D ScanRecord: first manudata for manu ID
01-27 16:50:09.312  9588 10099 D ScanRecord: parseFromBytes
01-27 16:50:09.312  9588 10099 D ScanRecord: parseFromBytes
01-27 16:50:09.312  9588 10099 D ScanRecord: first manudata for manu ID
01-27 16:50:09.312  4942  9680 D BtGatt.GattService: unregisterClient() - clientIf=8
01-27 16:50:09.312  9588 10099 D ScanRecord: parseFromBytes
01-27 16:50:09.312  9588 10099 D ScanRecord: first manudata for manu ID
,01-27 16:50:09.312  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 7. Current thread: Thread[main,5,main], id: 1
01-27 16:50:09.312  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=D2:74:8F:0E:D1:25, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-90, mTimestampNanos=234458870178}
01-27 16:50:09.312  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
01-27 16:50:09.312  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = D1:0E:8F:74:D2:B6, provideBluetoothMacAddressRequestId = nullextra info = 37]
01-27 16:50:09.312  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
01-27 16:50:09.312  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:09.312  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
01-27 16:50:09.312  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:50:09.312  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
01-27 16:50:09.312  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=FB:F2:70:61:22:51, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-78, mTimestampNanos=234458870178}
01-27 16:50:09.312  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:09.312  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:09.312  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
01-27 16:50:09.312  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
01-27 16:50:09.312  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = 22:61:70:F2:FB:B6, provideBluetoothMacAddressRequestId = nullextra info = 81]
01-27 16:50:09.312  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,01-27 16:50:09.312  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
01-27 16:50:09.332  3465  4487 V AlarmManager:  remove PendingIntent] PendingIntent{525c4b6: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
01-27 16:50:09.312  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
01-27 16:50:09.312  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:09.312  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=DB:69:06:8B:FC:D2, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[-46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-79, mTimestampNanos=234658870178}
01-27 16:50:09.312  9588  9651 D BluetoothLeScanner: Start Scan
,01-27 16:50:09.312  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = FC:8B:06:69:DB:B6, provideBluetoothMacAddressRequestId = nullextra info = 210]
01-27 16:50:09.312  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
01-27 16:50:09.322  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=C8:16:A4:7E:61:23, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-92, mTimestampNanos=234808870178}
01-27 16:50:09.322  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = 61:7E:A4:16:C8:B6, provideBluetoothMacAddressRequestId = nullextra info = 35]
01-27 16:50:09.322  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
,01-27 16:50:09.322  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=E3:EC:A5:91:D5:74, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-87, mTimestampNanos=234808870178}
01-27 16:50:09.322  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = D5:91:A5:EC:E3:B6, provideBluetoothMacAddressRequestId = nullextra info = 116]
01-27 16:50:09.322  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
01-27 16:50:09.322  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=F4:45:54:B3:86:47, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-80, mTimestampNanos=235208870178}
01-27 16:50:09.322  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = 86:B3:54:45:F4:B6, provideBluetoothMacAddressRequestId = nullextra info = 71]
01-27 16:50:09.322  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
01-27 16:50:09.322  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=60:EA:EC:62:07:AD, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[13, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-67, mTimestampNanos=235408870178}
01-27 16:50:09.322  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = A8:81:95:E9:5F:6F, provideBluetoothMacAddressRequestId = nullextra info = 13]
,01-27 16:50:09.322  9588  9588 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: Resolved advertisement type: ADVERTISEMENT_PEER_PROPERTIES
01-27 16:50:09.322  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: Parsed advertisment: [UUID = b6a44ad1-d319-4b3a-815d-8b805a47fb51, bluetoothMacAddress = A8:81:95:E9:5F:6F, provideBluetoothMacAddressRequestId = nullextra info = 13]
01-27 16:50:09.322  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult onPeerDiscovered [A8:81:95:E9:5F:6F 13]
01-27 16:50:09.322  9588  9588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onPeerDiscovered: [A8:81:95:E9:5F:6F 13]
01-27 16:50:09.322  9588  9588 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: [A8:81:95:E9:5F:6F 13]
01-27 16:50:09.322  9588  9588 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: has more info: false,  extra info differs: false
01-27 16:50:09.322  9588  9588 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [A8:81:95:E9:5F:6F 13] updated - the peer count is 1
01-27 16:50:09.322  9588  9651 D BluetoothAdapter: STATE_ON
01-27 16:50:09.332  9588  9651 D BluetoothAdapter: STATE_ON
01-27 16:50:09.332  4942  5182 D BtGatt.ScanManager: filter size is 1
01-27 16:50:09.332  4942  5182 D BtGatt.ScanManager: delete FilterIndex - 7
01-27 16:50:09.332  9588  9651 D BluetoothAdapter: STATE_ON
01-27 16:50:09.332  4942  5106 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=8, status=0, action=1, availableSpace=28
01-27 16:50:09.332  4942  5106 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
,01-27 16:50:09.332  4942  5182 D BtGatt.ScanManager: stopping BLe Batch
01-27 16:50:09.332  4942  5106 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=8, status=0, startStopAction=0
01-27 16:50:09.332  4942  5106 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
01-27 16:50:09.332  4942  5182 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 8
,01-27 16:50:09.342  4942  5106 D BtGatt.GattService: onBatchScanReports() - clientIf=8, status=0, reportType=2, numRecords=2
01-27 16:50:09.342  4942  5106 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
01-27 16:50:09.342  4942  5106 D BtGatt.GattService: current time is 235441430101
01-27 16:50:09.342  4942  5106 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -78, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -91, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
01-27 16:50:09.342  4942  5106 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
01-27 16:50:09.342  4942  5106 D ScanRecord: parseFromBytes
01-27 16:50:09.342  4942  5106 D ScanRecord: first manudata for manu ID
01-27 16:50:09.342  4942  5106 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
01-27 16:50:09.342  4942  5106 D ScanRecord: parseFromBytes
01-27 16:50:09.342  4942  5106 D ScanRecord: first manudata for manu ID
01-27 16:50:09.342  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:50:09.342  3465  3484 V AlarmManager:  remove PendingIntent] PendingIntent{dc865b7: PendingIntentRecord{44a72f5 com.android.bluetooth broadcastIntent}}
01-27 16:50:09.342  3465  4059 V AlarmManager:  remove PendingIntent] PendingIntent{fdb4124: PendingIntentRecord{44a72f5 com.android.bluetooth broadcastIntent}}
01-27 16:50:09.342  4942  4960 D BtGatt.GattService: registerClient() - UUID=082d6e16-0974-48df-84c7-8130514382c9
,01-27 16:50:09.342  3465  4416 V AlarmManager:  remove PendingIntent] PendingIntent{40be48d: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:09.352  3465  4487 V AlarmManager:  remove PendingIntent] PendingIntent{ac17642: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:09.352  3465  4225 V AlarmManager:  remove PendingIntent] PendingIntent{f73a653: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:09.352  3465  4331 V AlarmManager:  remove PendingIntent] PendingIntent{81d4b90: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:09.362  3465  3483 V AlarmManager:  remove PendingIntent] PendingIntent{2df3c89: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:09.362  3465  4382 V AlarmManager:  remove PendingIntent] PendingIntent{874b48e: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:09.372  3465  3977 V AlarmManager:  remove PendingIntent] PendingIntent{c8854af: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:09.372  3465  4485 V AlarmManager:  remove PendingIntent] PendingIntent{e3390bc: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:09.382  3465  4042 V AlarmManager:  remove PendingIntent] PendingIntent{f761845: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:09.382  3465  4488 V AlarmManager:  remove PendingIntent] PendingIntent{b0b8b9a: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:09.382  4942  5106 D BtGatt.GattService: onClientRegistered() - UUID=082d6e16-0974-48df-84c7-8130514382c9, clientIf=8
01-27 16:50:09.382  9588  9598 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=8
,01-27 16:50:09.382  4942  9680 D BtGatt.GattService: start scan with filters
,01-27 16:50:09.392  4942  9680 D BtGatt.GattService: getScanSettings
01-27 16:50:09.392  3465  4487 V AlarmManager:  remove PendingIntent] PendingIntent{b8f8ccb: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:09.392  4942  9680 D BtGatt.GattService: Is it foreground application = true
,01-27 16:50:09.392  4942  9680 D BtGatt.GattService: not a background application
,01-27 16:50:09.392  4942  9680 D BtGatt.GattService: [GSIM LOG]: getActualScanMode (2/100 vs 100/5)
,01-27 16:50:09.392  3465  4382 V AlarmManager:  remove PendingIntent] PendingIntent{906fca8: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:09.392  4942  9680 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
01-27 16:50:09.392  4942  9680 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
01-27 16:50:09.392  4942  5190 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_SCAN
01-27 16:50:09.392  4942  5190 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 27, currDate: 27
01-27 16:50:09.402  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
01-27 16:50:09.402  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:50:09.402  3465  4059 V AlarmManager:  remove PendingIntent] PendingIntent{ae4f3c1: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
01-27 16:50:09.402  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
01-27 16:50:09.402  4942  5182 D BtGatt.ScanManager: handling starting scan
01-27 16:50:09.402  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:09.402  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner started = true Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:50:09.402  9588  9588 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
01-27 16:50:09.402  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
01-27 16:50:09.402  9588  9651 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
01-27 16:50:09.402  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
01-27 16:50:09.402  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
01-27 16:50:09.402  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
01-27 16:50:09.402  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
01-27 16:50:09.402  9588  9651 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
01-27 16:50:09.402  9588  9651 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
01-27 16:50:09.402  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
01-27 16:50:09.402  4942  5182 D BluetoothAdapter: STATE_ON
,01-27 16:50:09.402  4942  5182 D BluetoothAdapter: STATE_ON
,01-27 16:50:09.402  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
01-27 16:50:09.402  9588  9651 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,01-27 16:50:09.402  9588  9651 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
01-27 16:50:09.402  9588  9651 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
01-27 16:50:09.402  9588  9651 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,01-27 16:50:09.402  9588  9651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
01-27 16:50:09.402  9588  9588 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
01-27 16:50:09.402  9588 10124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,01-27 16:50:09.402  4942  5106 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=8, status=0, action=1
01-27 16:50:09.402  4942  5106 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
01-27 16:50:09.402  4942  5182 D BtGatt.ScanManager: set filter index= 8 for clientIf= 8
01-27 16:50:09.402  4942  5182 D BtGatt.ScanManager: High Rssi Filter value is = -128
,01-27 16:50:09.402  4942  5182 D BtGatt.ScanManager: Low Rssi Filter value is = -128
01-27 16:50:09.402  4942  5182 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =2
01-27 16:50:09.402  4942  5190 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest : 44
01-27 16:50:09.402  4942  5190 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest, com.test.thalitest
01-27 16:50:09.412  4942  5106 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=8, status=0, action=0, availableSpace=27
01-27 16:50:09.412  4942  5106 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
,01-27 16:50:09.412  4942  5182 D BtGatt.ScanManager: Starting BLE batch scan
01-27 16:50:09.412  4942  5182 D BtGatt.ScanManager: configuring batch scan storage, appIf 8
01-27 16:50:09.412  9588 10124 D BluetoothSocket: bindListen(): myUserId = 0
01-27 16:50:09.412  9588 10124 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
01-27 16:50:09.412  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
01-27 16:50:09.412  9588  9651 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,01-27 16:50:09.412  4942  5106 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=8, status=0
,01-27 16:50:09.412  3465  4485 V AlarmManager:  remove PendingIntent] PendingIntent{e06c766: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
01-27 16:50:09.412  4942  5106 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
01-27 16:50:09.412  4942  5190 D BtGatt.GattService: [GSIM LOG]: increaseScanCount 4 Battery : com.test.thalitest : 2
01-27 16:50:09.412  4942  5190 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24758870
,01-27 16:50:09.412  4942  5190 D BtGatt.GattService: [GSIM LOG]: setRequestedScanType : com.test.thalitest : 2
01-27 16:50:09.412  4942  5190 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
01-27 16:50:09.412  4942  5106 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=8, status=0, startStopAction=1
01-27 16:50:09.412  4942  5190 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
01-27 16:50:09.412  4942  5106 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
01-27 16:50:09.412  4942  5190 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 4 => 4
01-27 16:50:09.412  4942  5190 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 4 => 4
01-27 16:50:09.412  4942  5190 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
01-27 16:50:09.412  4942  5190 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 4 => 4
01-27 16:50:09.412  4942  5190 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 4 => 4
01-27 16:50:09.412  4942  5190 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
01-27 16:50:09.412  4942  5190 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
01-27 16:50:09.412  4942  5190 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 4 => 4
01-27 16:50:09.412  4942  5190 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 4 => 4
01-27 16:50:09.412  4942  5190 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24758870
01-27 16:50:09.412  4942  5190 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
01-27 16:50:09.422  4942  5190 D BtGatt.GattService: [GSIM LOG]: com.samsung.android.beaconmanager@Custom, R time : 10 => 10
01-27 16:50:09.422  9588  9651 D BluetoothAdapter: STATE_ON
01-27 16:50:09.422  4942  5190 D BtGatt.GattService: [GSIM LOG]: com.samsung.android.beaconmanager@LowLatency, A time : 1 => 1
01-27 16:50:09.422  4942  5190 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.samsung.android.beaconmanager : 2
,01-27 16:50:09.422  4942  5190 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
01-27 16:50:09.422  4942  5190 D BtGatt.GattService: [GSIM LOG]: com.samsung.android.beaconmanager@Custom, R time : 10 => 10
01-27 16:50:09.422  4942  5190 D BtGatt.GattService: [GSIM LOG]: com.samsung.android.beaconmanager@LowLatency, A time : 1 => 1
01-27 16:50:09.422  4942  5190 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.samsung.android.beaconmanager : 24758870
01-27 16:50:09.422  9588 10124 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,01-27 16:50:09.422  3465  4487 V AlarmManager:  remove PendingIntent] PendingIntent{8882aa7: PendingIntentRecord{44a72f5 com.android.bluetooth broadcastIntent}}
01-27 16:50:09.422  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:50:09.422  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:50:09.422  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:50:09.422  3465  4331 V AlarmManager:  remove PendingIntent] PendingIntent{3233b54: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:09.432  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:50:09.432  3465  3973 V AlarmManager:  remove PendingIntent] PendingIntent{90c0afd: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:09.432  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser : Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:09.432  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:09.432  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:09.432  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,01-27 16:50:09.432  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
01-27 16:50:09.432  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "44:78:3E:94:2C:E6"
01-27 16:50:09.432  9588  9651 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 44 78 3E 94 2C E6
01-27 16:50:09.432  9588  9651 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,01-27 16:50:09.432  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
01-27 16:50:09.432  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:50:09.432  3465  4225 V AlarmManager:  remove PendingIntent] PendingIntent{227f3f2: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
01-27 16:50:09.432  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:09.432  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
01-27 16:50:09.432  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
01-27 16:50:09.432  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:50:09.432  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:09.432  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:09.432  9588  9651 D BluetoothAdapter: STATE_ON
01-27 16:50:09.432  9588  9651 D BluetoothAdapter: STATE_ON
01-27 16:50:09.432  9588  9651 D BluetoothLeAdvertiser: start advertising
,01-27 16:50:09.432  9588  9651 D BluetoothAdapter: STATE_ON
01-27 16:50:09.442  3465  4403 V AlarmManager:  remove PendingIntent] PendingIntent{682ca43: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:09.442  4942  5319 D BtGatt.GattService: registerClient() - UUID=ce8b8f72-1933-4b54-a93b-0c4d711d6569
,01-27 16:50:09.442  3465  4487 V AlarmManager:  remove PendingIntent] PendingIntent{222b8c0: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:09.442  3465  4225 V AlarmManager:  remove PendingIntent] PendingIntent{19359f9: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:09.452  3465  4489 V AlarmManager:  remove PendingIntent] PendingIntent{bd5d3e: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:09.452  3465  3977 V AlarmManager:  remove PendingIntent] PendingIntent{efdc79f: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:09.452  3465  3973 V AlarmManager:  remove PendingIntent] PendingIntent{8daa0ec: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:09.462  3465  4226 V AlarmManager:  remove PendingIntent] PendingIntent{4a69cb5: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:09.462  3465  4485 V AlarmManager:  remove PendingIntent] PendingIntent{7ae0f4a: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:09.462  3465  4488 V AlarmManager:  remove PendingIntent] PendingIntent{b013ebb: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:09.472  3465  4059 V AlarmManager:  remove PendingIntent] PendingIntent{46dfd8: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:09.472  3465  4403 V AlarmManager:  remove PendingIntent] PendingIntent{f714f31: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:09.482  3465  4042 V AlarmManager:  remove PendingIntent] PendingIntent{a45d616: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:09.482  4942  5106 D BtGatt.GattService: onClientRegistered() - UUID=ce8b8f72-1933-4b54-a93b-0c4d711d6569, clientIf=9
,01-27 16:50:09.482  9588  9599 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=9
,01-27 16:50:09.482  4942  9732 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,01-27 16:50:09.482  3465  4485 V AlarmManager:  remove PendingIntent] PendingIntent{1fb0b97: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:09.482  4942  9732 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,01-27 16:50:09.482  4942  9732 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
01-27 16:50:09.482  4942  5190 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_ADV
01-27 16:50:09.482  4942  5190 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 27, currDate: 27
01-27 16:50:09.492  4942  5179 D BtGatt.AdvertiseManager: message : 0
01-27 16:50:09.492  4942  5179 D BtGatt.AdvertiseManager: number of adv instance running = 0
01-27 16:50:09.492  4942  5179 D BtGatt.AdvertiseManager: size of list is =0
,01-27 16:50:09.492  4942  5179 D BtGatt.AdvertiseManager: starting advertising
,01-27 16:50:09.492  4942  5190 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.test.thalitest : 80
,01-27 16:50:09.492  3465  4226 V AlarmManager:  remove PendingIntent] PendingIntent{3362184: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
01-27 16:50:09.492  4942  5190 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.test.thalitest@LowLatency : 24758870
01-27 16:50:09.492  4942  5190 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.test.thalitest@LowLatency : 2
01-27 16:50:09.492  4942  5190 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
01-27 16:50:09.492  4942  5190 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 3 => 3
01-27 16:50:09.492  4942  5179 D BtGatt.AdvertiseManager: isStandardAdv = false
,01-27 16:50:09.492  4942  5106 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=9, status=0
,01-27 16:50:09.502  4942  5179 D BtGatt.AdvertiseManager: starting multi advertising
01-27 16:50:09.502  3465  4382 V AlarmManager:  remove PendingIntent] PendingIntent{c5aad6d: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:09.502  4942  5106 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=9, status=0
01-27 16:50:09.502  4942  5179 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,01-27 16:50:09.502  4942  5179 D BtGatt.AdvertiseManager: clientIf: 9, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,01-27 16:50:09.502  4942  5179 D BtGatt.AdvertiseManager: postCallback clientIf = 9 status = 0
,01-27 16:50:09.502  3465  3973 V AlarmManager:  remove PendingIntent] PendingIntent{2c13da2: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:09.502  4942  5179 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=9, status=0, isStart=true
,01-27 16:50:09.502  9588 10099 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
01-27 16:50:09.502  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:09.502  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:09.512  3465  4487 V AlarmManager:  remove PendingIntent] PendingIntent{a5aca33: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
01-27 16:50:09.502  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
01-27 16:50:09.502  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:50:09.502  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:50:09.502  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
,01-27 16:50:09.502  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:50:09.512  3465  4059 V AlarmManager:  remove PendingIntent] PendingIntent{8b5d1f0: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
01-27 16:50:09.502  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:50:09.502  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: advertiser is started. Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:50:09.502  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:50:09.502  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:50:09.502  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
,01-27 16:50:09.512  3465  3483 V AlarmManager:  remove PendingIntent] PendingIntent{b01b369: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
01-27 16:50:09.502  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: adv = true, disc = true
01-27 16:50:09.502  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,01-27 16:50:09.522  3465  4416 V AlarmManager:  remove PendingIntent] PendingIntent{9991ee: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
01-27 16:50:09.502  9588  9651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,01-27 16:50:09.502  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:09.512  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:50:09.512  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:09.512  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:50:09.512  9588  9588 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
01-27 16:50:09.522  3465  4489 V AlarmManager:  remove PendingIntent] PendingIntent{7edd68f: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:09.512  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
01-27 16:50:09.512  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
,01-27 16:50:09.512  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
01-27 16:50:09.512  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
01-27 16:50:09.512  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
01-27 16:50:09.512  9588  9588 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,01-27 16:50:09.512  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
01-27 16:50:09.512  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
01-27 16:50:09.512  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
01-27 16:50:09.512  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
01-27 16:50:09.512  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]Current thread: Thread[main,5,main], id: 1
01-27 16:50:09.532  3465  4485 V AlarmManager:  remove PendingIntent] PendingIntent{93e1d1c: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
01-27 16:50:09.512  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
01-27 16:50:09.512  9588  9588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING] Current thread: Thread[main,5,main], id: 1
01-27 16:50:09.512  9588  9588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,01-27 16:50:09.512  9588  9588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
01-27 16:50:09.512  9588  9588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
01-27 16:50:09.512  9588  9588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
01-27 16:50:09.512  9588  9588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
01-27 16:50:09.522  9588  9588 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,01-27 16:50:09.532  3465  4331 V AlarmManager:  remove PendingIntent] PendingIntent{bf91d25: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:09.542  3465  4488 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,01-27 16:50:09.542  3465  4488 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4329, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
01-27 16:50:09.542  3465  4488 D BatteryService: online:4, current avg:80, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-60
01-27 16:50:09.542  3465  3465 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,01-27 16:50:09.542  3465  3465 I MotionRecognitionService: Plugged
,01-27 16:50:09.542  3465  3465 D MotionRecognitionService:   cableConnection= 1
01-27 16:50:09.542  3465  3465 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
01-27 16:50:09.542  3465  3465 D MotionRecognitionService: skip setTransmitPower. 
01-27 16:50:09.542  3465  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,01-27 16:50:09.542  3950  3950 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
01-27 16:50:09.542  3950  3950 D PowerUI : priorPlugType = 2 mPlugType =  2
,01-27 16:50:09.552  3950  3950 D KeyguardUpdateMonitor: handleBatteryUpdate
,01-27 16:50:09.552  3950  3950 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
01-27 16:50:09.552  3950  3950 D PowerUI.Notification: There is no change about charging status, so return!
,01-27 16:50:09.552  4990  4990 D CommonServiceConfiguration: getStringValueSetting
,01-27 16:50:09.552  4990  4990 D BatteryMonitor: new battery level: 100
,01-27 16:50:09.552  4942  4942 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,01-27 16:50:09.562  4942  9696 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,01-27 16:50:09.562  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
01-27 16:50:09.562  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,01-27 16:50:09.692  3465  4489 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,01-27 16:50:09.702  3465  4489 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4337, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
01-27 16:50:09.702  3465  4489 D BatteryService: online:4, current avg:80, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:87
01-27 16:50:09.702  3465  3465 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,01-27 16:50:09.702  3465  3465 I MotionRecognitionService: Plugged
,01-27 16:50:09.702  3465  3465 D MotionRecognitionService:   cableConnection= 1
01-27 16:50:09.702  3465  3465 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
01-27 16:50:09.702  3465  3465 D MotionRecognitionService: skip setTransmitPower. 
,01-27 16:50:09.702  3465  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,01-27 16:50:09.702  3950  3950 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,01-27 16:50:09.702  3950  3950 D KeyguardUpdateMonitor: handleBatteryUpdate
,01-27 16:50:09.702  3950  3950 D PowerUI : priorPlugType = 2 mPlugType =  2
,01-27 16:50:09.712  3950  3950 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
01-27 16:50:09.712  3950  3950 D PowerUI.Notification: There is no change about charging status, so return!
,01-27 16:50:09.712  4990  4990 D CommonServiceConfiguration: getStringValueSetting
,01-27 16:50:09.722  4990  4990 D BatteryMonitor: new battery level: 100
,01-27 16:50:09.722  4942  4942 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
01-27 16:50:09.722  4942  9696 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,01-27 16:50:09.732  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
01-27 16:50:09.732  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,01-27 16:50:10.022  9588  9588 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
01-27 16:50:10.022  9588  9588 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
01-27 16:50:10.022  9588  9588 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,01-27 16:50:10.422  3465  3818 V AlarmManager: Expired Alarm result :4
,01-27 16:50:10.432  4942  4942 D BtGatt.ScanManager: awakened up at time 236530
,01-27 16:50:10.432  4942  5182 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 8
,01-27 16:50:10.432  3465  4416 V AlarmManager:  remove PendingIntent] PendingIntent{3fb4cab: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:10.442  4942  5106 D BtGatt.GattService: onBatchScanReports() - clientIf=8, status=0, reportType=2, numRecords=6
01-27 16:50:10.442  4942  5106 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
,01-27 16:50:10.442  4942  5106 D BtGatt.GattService: current time is 236541394523
01-27 16:50:10.442  3465  4226 V AlarmManager:  remove PendingIntent] PendingIntent{a9def08: PendingIntentRecord{44a72f5 com.android.bluetooth broadcastIntent}}
01-27 16:50:10.442  4942  5106 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -84, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, -83, 7, 98, -20, -22, 96, 1, -128, -81, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 13, -88, -127, -107, -23, 95, 111, 0, 35, 97, 126, -92, 22, -56, 1, -128, -75, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -78, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -81, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -87, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
01-27 16:50:10.442  4942  5106 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
01-27 16:50:10.442  4942  5106 D ScanRecord: parseFromBytes
,01-27 16:50:10.442  4942  5106 D ScanRecord: first manudata for manu ID
01-27 16:50:10.442  4942  5106 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 13, -88, -127, -107, -23, 95, 111]
01-27 16:50:10.442  4942  5106 D ScanRecord: parseFromBytes
,01-27 16:50:10.442  4942  5106 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
01-27 16:50:10.442  4942  5106 D ScanRecord: parseFromBytes
01-27 16:50:10.442  4942  5106 D ScanRecord: first manudata for manu ID
01-27 16:50:10.442  4942  5106 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
01-27 16:50:10.442  4942  5106 D ScanRecord: parseFromBytes
01-27 16:50:10.442  4942  5106 D ScanRecord: first manudata for manu ID
01-27 16:50:10.442  4942  5106 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
01-27 16:50:10.442  4942  5106 D ScanRecord: parseFromBytes
01-27 16:50:10.442  4942  5106 D ScanRecord: first manudata for manu ID
01-27 16:50:10.442  4942  5106 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
01-27 16:50:10.442  4942  5106 D ScanRecord: parseFromBytes
01-27 16:50:10.442  4942  5106 D ScanRecord: first manudata for manu ID
01-27 16:50:10.442  9588  9599 D ScanRecord: parseFromBytes
01-27 16:50:10.442  9588  9599 D ScanRecord: first manudata for manu ID
01-27 16:50:10.442  9588  9599 D ScanRecord: parseFromBytes
,01-27 16:50:10.442  9588  9599 D ScanRecord: first manudata for manu ID
01-27 16:50:10.442  9588  9599 D ScanRecord: parseFromBytes
01-27 16:50:10.442  9588  9599 D ScanRecord: first manudata for manu ID
01-27 16:50:10.442  9588  9599 D ScanRecord: parseFromBytes
01-27 16:50:10.442  9588  9599 D ScanRecord: first manudata for manu ID
01-27 16:50:10.442  9588  9599 D ScanRecord: parseFromBytes
,01-27 16:50:10.442  9588  9599 D ScanRecord: parseFromBytes
01-27 16:50:10.442  9588  9599 D ScanRecord: first manudata for manu ID
01-27 16:50:10.452  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 6. Current thread: Thread[main,5,main], id: 1
01-27 16:50:10.452  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=DB:69:06:8B:FC:D2, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[-46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-84, mTimestampNanos=235592607638}
01-27 16:50:10.452  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = FC:8B:06:69:DB:B6, provideBluetoothMacAddressRequestId = nullextra info = 210]
,01-27 16:50:10.452  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
01-27 16:50:10.452  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=C8:16:A4:7E:61:23, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-75, mTimestampNanos=235742607638}
01-27 16:50:10.452  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = 61:7E:A4:16:C8:B6, provideBluetoothMacAddressRequestId = nullextra info = 35]
01-27 16:50:10.452  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
,01-27 16:50:10.452  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=E3:EC:A5:91:D5:74, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-78, mTimestampNanos=235792607638}
01-27 16:50:10.452  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=F4:45:54:B3:86:47, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-81, mTimestampNanos=236192607638}
01-27 16:50:10.452  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = 86:B3:54:45:F4:B6, provideBluetoothMacAddressRequestId = nullextra info = 71]
01-27 16:50:10.452  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
,01-27 16:50:10.452  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=FB:F2:70:61:22:51, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-87, mTimestampNanos=236392607638}
01-27 16:50:10.452  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = 22:61:70:F2:FB:B6, provideBluetoothMacAddressRequestId = nullextra info = 81]
01-27 16:50:10.452  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
01-27 16:50:10.452  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=60:EA:EC:62:07:AD, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[13, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-81, mTimestampNanos=236442607638}
,01-27 16:50:10.452  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = A8:81:95:E9:5F:6F, provideBluetoothMacAddressRequestId = nullextra info = 13]
01-27 16:50:10.452  9588  9588 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: Resolved advertisement type: ADVERTISEMENT_PEER_PROPERTIES
01-27 16:50:10.452  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: Parsed advertisment: [UUID = b6a44ad1-d319-4b3a-815d-8b805a47fb51, bluetoothMacAddress = A8:81:95:E9:5F:6F, provideBluetoothMacAddressRequestId = nullextra info = 13]
01-27 16:50:10.452  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult onPeerDiscovered [A8:81:95:E9:5F:6F 13]
01-27 16:50:10.452  9588  9588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onPeerDiscovered: [A8:81:95:E9:5F:6F 13]
,01-27 16:50:10.452  9588  9588 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: [A8:81:95:E9:5F:6F 13]
01-27 16:50:10.452  9588  9588 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: has more info: false,  extra info differs: false
01-27 16:50:10.452  9588  9588 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [A8:81:95:E9:5F:6F 13] updated - the peer count is 1
,01-27 16:50:10.462  3465  4487 V AlarmManager:  remove PendingIntent] PendingIntent{c4366a1: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:10.462  3465  4059 V AlarmManager:  remove PendingIntent] PendingIntent{37df0c6: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:10.472  3465  4382 V AlarmManager:  remove PendingIntent] PendingIntent{b200887: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:10.482  3465  4403 V AlarmManager:  remove PendingIntent] PendingIntent{ea6f3b4: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:10.482  3465  4042 V AlarmManager:  remove PendingIntent] PendingIntent{c8ecbdd: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:10.492  3465  3484 V AlarmManager:  remove PendingIntent] PendingIntent{4d85352: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:10.492  3465  4225 V AlarmManager:  remove PendingIntent] PendingIntent{ceaa623: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:10.502  3465  3977 V AlarmManager:  remove PendingIntent] PendingIntent{999720: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:11.442  3465  3818 V AlarmManager: Expired Alarm result :4
,01-27 16:50:11.452  4942  4942 D BtGatt.ScanManager: awakened up at time 237555
,01-27 16:50:11.452  4942  5182 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 8
,01-27 16:50:11.462  3465  4226 V AlarmManager:  remove PendingIntent] PendingIntent{a04529e: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:11.462  4942  5106 D BtGatt.GattService: onBatchScanReports() - clientIf=8, status=0, reportType=2, numRecords=5
,01-27 16:50:11.462  4942  5106 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
01-27 16:50:11.462  3465  3483 V AlarmManager:  remove PendingIntent] PendingIntent{937817f: PendingIntentRecord{44a72f5 com.android.bluetooth broadcastIntent}}
01-27 16:50:11.462  4942  5106 D BtGatt.GattService: current time is 237566977791
,01-27 16:50:11.462  4942  5106 D BtGatt.GattService: Batch record : [-83, 7, 98, -20, -22, 96, 1, -128, -82, 7, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 13, -88, -127, -107, -23, 95, 111, 0, 35, 97, 126, -92, 22, -56, 1, -128, -76, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -77, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -86, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -81, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
01-27 16:50:11.462  4942  5106 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 13, -88, -127, -107, -23, 95, 111]
,01-27 16:50:11.462  4942  5106 D ScanRecord: parseFromBytes
,01-27 16:50:11.462  4942  5106 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
01-27 16:50:11.462  4942  5106 D ScanRecord: parseFromBytes
01-27 16:50:11.462  4942  5106 D ScanRecord: first manudata for manu ID
01-27 16:50:11.462  4942  5106 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,01-27 16:50:11.472  4942  5106 D ScanRecord: parseFromBytes
01-27 16:50:11.472  4942  5106 D ScanRecord: first manudata for manu ID
01-27 16:50:11.472  4942  5106 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,01-27 16:50:11.472  4942  5106 D ScanRecord: parseFromBytes
01-27 16:50:11.472  4942  5106 D ScanRecord: first manudata for manu ID
01-27 16:50:11.472  4942  5106 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
01-27 16:50:11.472  4942  5106 D ScanRecord: parseFromBytes
,01-27 16:50:11.472  4942  5106 D ScanRecord: first manudata for manu ID
01-27 16:50:11.472  9588 10099 D ScanRecord: parseFromBytes
01-27 16:50:11.472  9588 10099 D ScanRecord: first manudata for manu ID
01-27 16:50:11.472  9588 10099 D ScanRecord: parseFromBytes
,01-27 16:50:11.472  9588 10099 D ScanRecord: first manudata for manu ID
01-27 16:50:11.472  9588 10099 D ScanRecord: parseFromBytes
01-27 16:50:11.472  9588 10099 D ScanRecord: parseFromBytes
01-27 16:50:11.472  9588 10099 D ScanRecord: first manudata for manu ID
01-27 16:50:11.472  9588 10099 D ScanRecord: parseFromBytes
01-27 16:50:11.472  9588 10099 D ScanRecord: first manudata for manu ID
01-27 16:50:11.472  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 5. Current thread: Thread[main,5,main], id: 1
01-27 16:50:11.482  3465  4485 V AlarmManager:  remove PendingIntent] PendingIntent{d51054c: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
01-27 16:50:11.472  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=C8:16:A4:7E:61:23, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-76, mTimestampNanos=236717845791}
01-27 16:50:11.472  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = 61:7E:A4:16:C8:B6, provideBluetoothMacAddressRequestId = nullextra info = 35]
01-27 16:50:11.472  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
,01-27 16:50:11.472  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=E3:EC:A5:91:D5:74, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-77, mTimestampNanos=236767845791}
01-27 16:50:11.472  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = D5:91:A5:EC:E3:B6, provideBluetoothMacAddressRequestId = nullextra info = 116]
01-27 16:50:11.472  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
01-27 16:50:11.472  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=D2:74:8F:0E:D1:25, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-86, mTimestampNanos=236767845791}
,01-27 16:50:11.472  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = D1:0E:8F:74:D2:B6, provideBluetoothMacAddressRequestId = nullextra info = 37]
01-27 16:50:11.472  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
01-27 16:50:11.472  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=F4:45:54:B3:86:47, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-81, mTimestampNanos=237167845791}
01-27 16:50:11.472  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = 86:B3:54:45:F4:B6, provideBluetoothMacAddressRequestId = nullextra info = 71]
,01-27 16:50:11.472  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
01-27 16:50:11.472  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=60:EA:EC:62:07:AD, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[13, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-82, mTimestampNanos=237217845791}
01-27 16:50:11.472  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = A8:81:95:E9:5F:6F, provideBluetoothMacAddressRequestId = nullextra info = 13]
,01-27 16:50:11.472  9588  9588 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: Resolved advertisement type: ADVERTISEMENT_PEER_PROPERTIES
01-27 16:50:11.472  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: Parsed advertisment: [UUID = b6a44ad1-d319-4b3a-815d-8b805a47fb51, bluetoothMacAddress = A8:81:95:E9:5F:6F, provideBluetoothMacAddressRequestId = nullextra info = 13]
01-27 16:50:11.472  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult onPeerDiscovered [A8:81:95:E9:5F:6F 13]
01-27 16:50:11.472  9588  9588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onPeerDiscovered: [A8:81:95:E9:5F:6F 13]
,01-27 16:50:11.472  9588  9588 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: [A8:81:95:E9:5F:6F 13]
01-27 16:50:11.472  9588  9588 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: has more info: false,  extra info differs: false
01-27 16:50:11.472  9588  9588 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [A8:81:95:E9:5F:6F 13] updated - the peer count is 1
,01-27 16:50:11.492  3465  3977 V AlarmManager:  remove PendingIntent] PendingIntent{fe49995: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:11.492  3465  4403 V AlarmManager:  remove PendingIntent] PendingIntent{95efaaa: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:11.502  3465  3483 V AlarmManager:  remove PendingIntent] PendingIntent{74cb69b: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:11.502  3465  4489 V AlarmManager:  remove PendingIntent] PendingIntent{22f2a38: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:11.512  3465  4485 V AlarmManager:  remove PendingIntent] PendingIntent{c423a11: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:11.512  3465  4331 V AlarmManager:  remove PendingIntent] PendingIntent{a1776: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:12.462  3465  3818 V AlarmManager: Expired Alarm result :4
,01-27 16:50:12.472  4942  4942 D BtGatt.ScanManager: awakened up at time 238574
,01-27 16:50:12.472  4942  5182 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 8
,01-27 16:50:12.482  3465  3973 V AlarmManager:  remove PendingIntent] PendingIntent{ec8b1e4: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:12.482  4942  5106 D BtGatt.GattService: onBatchScanReports() - clientIf=8, status=0, reportType=2, numRecords=3
01-27 16:50:12.482  4942  5106 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
01-27 16:50:12.492  4942  5106 D BtGatt.GattService: current time is 238589981521
01-27 16:50:12.492  3465  4489 V AlarmManager:  remove PendingIntent] PendingIntent{bff664d: PendingIntentRecord{44a72f5 com.android.bluetooth broadcastIntent}}
,01-27 16:50:12.492  4942  5106 D BtGatt.GattService: Batch record : [-83, 7, 98, -20, -22, 96, 1, -128, -67, 19, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 13, -88, -127, -107, -23, 95, 111, 0, 35, 97, 126, -92, 22, -56, 1, -128, -92, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -92, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
01-27 16:50:12.492  4942  5106 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 13, -88, -127, -107, -23, 95, 111]
,01-27 16:50:12.492  4942  5106 D ScanRecord: parseFromBytes
01-27 16:50:12.492  4942  5106 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
01-27 16:50:12.492  4942  5106 D ScanRecord: parseFromBytes
01-27 16:50:12.492  4942  5106 D ScanRecord: first manudata for manu ID
01-27 16:50:12.492  4942  5106 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
01-27 16:50:12.492  4942  5106 D ScanRecord: parseFromBytes
01-27 16:50:12.492  4942  5106 D ScanRecord: first manudata for manu ID
01-27 16:50:12.492  9588  9599 D ScanRecord: parseFromBytes
01-27 16:50:12.492  9588  9599 D ScanRecord: first manudata for manu ID
01-27 16:50:12.492  9588  9599 D ScanRecord: parseFromBytes
01-27 16:50:12.492  9588  9599 D ScanRecord: first manudata for manu ID
01-27 16:50:12.492  9588  9599 D ScanRecord: parseFromBytes
01-27 16:50:12.492  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 3. Current thread: Thread[main,5,main], id: 1
01-27 16:50:12.492  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=C8:16:A4:7E:61:23, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-92, mTimestampNanos=237640784868}
01-27 16:50:12.492  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=60:EA:EC:62:07:AD, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[13, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-67, mTimestampNanos=237640784868}
01-27 16:50:12.492  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = A8:81:95:E9:5F:6F, provideBluetoothMacAddressRequestId = nullextra info = 13]
01-27 16:50:12.492  9588  9588 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: Resolved advertisement type: ADVERTISEMENT_PEER_PROPERTIES
01-27 16:50:12.492  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: Parsed advertisment: [UUID = b6a44ad1-d319-4b3a-815d-8b805a47fb51, bluetoothMacAddress = A8:81:95:E9:5F:6F, provideBluetoothMacAddressRequestId = nullextra info = 13]
01-27 16:50:12.492  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult onPeerDiscovered [A8:81:95:E9:5F:6F 13]
,01-27 16:50:12.492  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=D2:74:8F:0E:D1:25, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-92, mTimestampNanos=237690784868}
01-27 16:50:12.492  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = D1:0E:8F:74:D2:B6, provideBluetoothMacAddressRequestId = nullextra info = 37]
01-27 16:50:12.492  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
01-27 16:50:12.492  9588  9588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onPeerDiscovered: [A8:81:95:E9:5F:6F 13]
01-27 16:50:12.492  9588  9588 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: [A8:81:95:E9:5F:6F 13]
,01-27 16:50:12.492  9588  9588 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: has more info: false,  extra info differs: false
01-27 16:50:12.492  9588  9588 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [A8:81:95:E9:5F:6F 13] updated - the peer count is 1
,01-27 16:50:12.512  3465  4485 V AlarmManager:  remove PendingIntent] PendingIntent{9783502: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:12.512  3465  4331 V AlarmManager:  remove PendingIntent] PendingIntent{9e15e13: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:12.512  9588  9651 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
01-27 16:50:12.512  9588  9651 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
01-27 16:50:12.512  9588  9651 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
01-27 16:50:12.512  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
01-27 16:50:12.512  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
01-27 16:50:12.512  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
01-27 16:50:12.512  9588  9651 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
01-27 16:50:12.512  9588  9651 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
01-27 16:50:12.512  9588 10124 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
01-27 16:50:12.512  9588 10124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
01-27 16:50:12.512  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
01-27 16:50:12.512  9588 10124 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
01-27 16:50:12.512  9588  9588 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
01-27 16:50:12.512  9588  9651 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a4b6969 removed from the list
01-27 16:50:12.512  9588  9651 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a4b6969 removed from the list
01-27 16:50:12.512  9588  9588 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
01-27 16:50:12.512  9588  9651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,01-27 16:50:12.512  9588  9651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
01-27 16:50:12.512  9588  9588 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
01-27 16:50:12.512  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:12.512  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,01-27 16:50:12.512  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
01-27 16:50:12.512  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:50:12.522  3465  3483 V AlarmManager:  remove PendingIntent] PendingIntent{5510850: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
01-27 16:50:12.512  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:12.512  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:12.512  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
01-27 16:50:12.512  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:12.522  9588  9651 D BluetoothAdapter: STATE_ON
01-27 16:50:12.522  9588  9651 D BluetoothAdapter: STATE_ON
01-27 16:50:12.522  4942  9680 D BtGatt.GattService: flushPendingBatchResults - clientIf=8, isServer=false
01-27 16:50:12.522  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
01-27 16:50:12.522  4942  5182 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 8
01-27 16:50:12.522  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:50:12.522  4942  5106 D BtGatt.GattService: onBatchScanReports() - clientIf=8, status=0, reportType=2, numRecords=0
,01-27 16:50:12.522  4942  5106 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
01-27 16:50:12.522  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:50:12.522  9588  9651 D BluetoothLeScanner: Stop Scan
,01-27 16:50:12.532  3465  4331 V AlarmManager:  remove PendingIntent] PendingIntent{1e91a49: PendingIntentRecord{44a72f5 com.android.bluetooth broadcastIntent}}
,01-27 16:50:12.532  3465  3483 V AlarmManager:  remove PendingIntent] PendingIntent{3b89f4e: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:12.532  4942  5319 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
01-27 16:50:12.532  4942  5319 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,01-27 16:50:12.532  4942  5319 D BtGatt.GattService: stopScan() - queue size =2
01-27 16:50:12.532  4942  5190 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_SCAN
01-27 16:50:12.542  3465  4489 V AlarmManager:  remove PendingIntent] PendingIntent{a79c86f: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
01-27 16:50:12.532  4942  5190 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 27, currDate: 27
01-27 16:50:12.532  4942  5190 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
01-27 16:50:12.532  4942  5190 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 4 => 4
01-27 16:50:12.532  4942  5190 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 4 => 4
01-27 16:50:12.532  4942  5190 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_ACTUAL_DB
,01-27 16:50:12.532  4942  5190 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_REQUESTED_DB
01-27 16:50:12.532  4942  4966 D BtGatt.GattService: unregisterClient() - clientIf=8
01-27 16:50:12.542  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
01-27 16:50:12.542  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:12.542  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
01-27 16:50:12.542  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:12.542  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:50:12.542  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:12.542  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
01-27 16:50:12.542  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:12.542  4942  5182 D BtGatt.ScanManager: filter size is 1
01-27 16:50:12.542  4942  5182 D BtGatt.ScanManager: delete FilterIndex - 8
01-27 16:50:12.542  9588  9651 D BluetoothAdapter: STATE_ON
01-27 16:50:12.542  9588  9651 D BluetoothAdapter: STATE_ON
01-27 16:50:12.542  9588  9651 D BluetoothLeAdvertiser: stop advertising
,01-27 16:50:12.542  4942  5106 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=8, status=0, action=1, availableSpace=28
01-27 16:50:12.542  4942  5106 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
01-27 16:50:12.542  4942  5182 D BtGatt.ScanManager: stopping BLe Batch
,01-27 16:50:12.542  4942  5106 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=8, status=0, startStopAction=0
01-27 16:50:12.542  4942  5106 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
,01-27 16:50:12.542  4942  5182 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 8
,01-27 16:50:12.552  3465  4485 V AlarmManager:  remove PendingIntent] PendingIntent{5c6597c: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
01-27 16:50:12.552  4942  9767 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,01-27 16:50:12.552  4942  9767 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
01-27 16:50:12.552  4942  5190 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_ADV
01-27 16:50:12.552  4942  5190 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 27, currDate: 27
01-27 16:50:12.552  4942  5106 D BtGatt.GattService: onBatchScanReports() - clientIf=8, status=0, reportType=2, numRecords=0
,01-27 16:50:12.552  4942  5190 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
01-27 16:50:12.552  3465  3973 V AlarmManager:  remove PendingIntent] PendingIntent{6a01205: PendingIntentRecord{44a72f5 com.android.bluetooth broadcastIntent}}
01-27 16:50:12.552  4942  5106 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
01-27 16:50:12.552  4942  5190 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 3 => 3
01-27 16:50:12.552  4942  5190 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
01-27 16:50:12.552  4942  5179 D BtGatt.AdvertiseManager: message : 1
,01-27 16:50:12.552  4942  5179 D BtGatt.AdvertiseManager: stop advertise for client =  9
01-27 16:50:12.552  4942  5179 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 9
,01-27 16:50:12.552  3465  3973 V AlarmManager:  remove PendingIntent] PendingIntent{c83625a: PendingIntentRecord{44a72f5 com.android.bluetooth broadcastIntent}}
01-27 16:50:12.552  3465  3977 V AlarmManager:  remove PendingIntent] PendingIntent{7847c8b: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:12.552  4942  5179 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,01-27 16:50:12.562  4942  5106 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=9, status=0
01-27 16:50:12.562  4942  5106 D BtGatt.GattService: Client app is not null!
,01-27 16:50:12.562  9588  9598 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
01-27 16:50:12.562  3465  3483 V AlarmManager:  remove PendingIntent] PendingIntent{fdd9168: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
01-27 16:50:12.562  4942  5319 D BtGatt.GattService: unregisterClient() - clientIf=9
,01-27 16:50:12.562  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
01-27 16:50:12.562  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:12.562  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
01-27 16:50:12.562  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:12.562  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:12.562  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:50:12.562  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
01-27 16:50:12.562  9588  9651 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
01-27 16:50:12.562  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
01-27 16:50:12.562  9588  9651 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
01-27 16:50:12.562  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:50:12.562  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:12.562  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
01-27 16:50:12.562  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-138,7,main], id: 138
,01-27 16:50:12.562  9588  9651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-138,7,main], id: 138
01-27 16:50:12.562  9588  9651 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c700fee removed from the list
01-27 16:50:12.562  9588  9588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
01-27 16:50:12.562  9588  9651 D io.jxcore.node.ConnectivityMonitor: stop
01-27 16:50:12.562  9588  9651 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
01-27 16:50:12.562  9588  9651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
01-27 16:50:12.572  3465  4488 V AlarmManager:  remove PendingIntent] PendingIntent{214c981: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
01-27 16:50:12.562  9588  9588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
01-27 16:50:12.562  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 0. Current thread: Thread[main,5,main], id: 1
01-27 16:50:12.562  9588  9588 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
01-27 16:50:12.562  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,01-27 16:50:12.562  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
01-27 16:50:12.562  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
01-27 16:50:12.562  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,01-27 16:50:12.562  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
01-27 16:50:12.562  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
01-27 16:50:12.562  9588  9588 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
01-27 16:50:12.562  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
01-27 16:50:12.562  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
01-27 16:50:12.572  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,01-27 16:50:12.572  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
01-27 16:50:12.572  9588  9588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
01-27 16:50:12.572  9588  9588 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
01-27 16:50:12.572  9588  9651 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
01-27 16:50:12.572  9588  9651 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
01-27 16:50:12.572  9588  9651 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
01-27 16:50:12.572  3465  4059 V AlarmManager:  remove PendingIntent] PendingIntent{3054a26: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
01-27 16:50:12.572  9588  9651 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
01-27 16:50:12.572  9588  9651 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,01-27 16:50:12.572  9588  9651 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
01-27 16:50:12.572  9588  9651 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
01-27 16:50:12.572  9588  9651 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
01-27 16:50:12.572  9588  9651 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
01-27 16:50:12.572  9588  9651 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
,01-27 16:50:12.572  9588  9651 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
,01-27 16:50:12.572  9588  9651 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
,01-27 16:50:12.572  3465  4403 V AlarmManager:  remove PendingIntent] PendingIntent{53c5667: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:12.582  9588  9651 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
,01-27 16:50:12.582  9588  9651 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
,01-27 16:50:12.582  3465  3483 V AlarmManager:  remove PendingIntent] PendingIntent{7ae5c14: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
01-27 16:50:12.582  9588  9651 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,01-27 16:50:12.582  3465  4226 V AlarmManager:  remove PendingIntent] PendingIntent{c37cbd: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:12.592  3465  4416 V AlarmManager:  remove PendingIntent] PendingIntent{a6be2b2: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:12.592  3465  3973 V AlarmManager:  remove PendingIntent] PendingIntent{6adf203: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:12.602  3465  4331 V AlarmManager:  remove PendingIntent] PendingIntent{91f2580: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:12.602  3465  4485 V AlarmManager:  remove PendingIntent] PendingIntent{b027b9: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:12.612  3465  4042 V AlarmManager:  remove PendingIntent] PendingIntent{93177fe: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:12.612  3465  4487 V AlarmManager:  remove PendingIntent] PendingIntent{913ab5f: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:12.612  3465  4489 V AlarmManager:  remove PendingIntent] PendingIntent{61119ac: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:12.622  3465  3977 V AlarmManager:  remove PendingIntent] PendingIntent{2228675: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:12.622  3465  4382 V AlarmManager:  remove PendingIntent] PendingIntent{129160a: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:12.632  3465  3484 V AlarmManager:  remove PendingIntent] PendingIntent{8f19e7b: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:12.632  3465  4225 V AlarmManager:  remove PendingIntent] PendingIntent{b4c2498: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:12.642  3465  4488 V AlarmManager:  remove PendingIntent] PendingIntent{82214f1: PendingIntentRecord{46b6547 com.android.bluetooth broadcastIntent}}
,01-27 16:50:13.072  9588  9588 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,01-27 16:50:14.592  9588  9651 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,01-27 16:50:14.752  9588 10130 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 270, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [0:0:0:0:0:0].
01-27 16:50:14.752  9588 10130 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
01-27 16:50:14.752  9588 10130 D io.jxcore.node.StreamCopyingThread:  id: 83
,01-27 16:50:14.842  3465  4382 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
01-27 16:50:14.842  3465  4382 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4339, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
01-27 16:50:14.842  3465  4382 D BatteryService: online:4, current avg:101, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:44
01-27 16:50:14.842  3465  3465 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,01-27 16:50:14.842  3465  3465 I MotionRecognitionService: Plugged
,01-27 16:50:14.842  3465  3465 D MotionRecognitionService:   cableConnection= 1
01-27 16:50:14.842  3465  3465 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
01-27 16:50:14.842  3465  3465 D MotionRecognitionService: skip setTransmitPower. 
,01-27 16:50:14.852  3465  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,01-27 16:50:14.852  3950  3950 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,01-27 16:50:14.852  3950  3950 D PowerUI : priorPlugType = 2 mPlugType =  2
,01-27 16:50:14.852  3950  3950 D KeyguardUpdateMonitor: handleBatteryUpdate
01-27 16:50:14.852  3950  3950 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,01-27 16:50:14.852  3950  3950 D PowerUI.Notification: There is no change about charging status, so return!
,01-27 16:50:14.872  4990  4990 D CommonServiceConfiguration: getStringValueSetting
,01-27 16:50:14.882  4990  4990 D BatteryMonitor: new battery level: 100
,01-27 16:50:14.882  4942  4942 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
01-27 16:50:14.882  4942  9696 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,01-27 16:50:14.892  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,01-27 16:50:14.892  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,01-27 16:50:15.552  9588 10130 W !!      : call onHalfStreamCopied
01-27 16:50:15.552  9588 10130 I testCopyDataAndClose: closing input stream
,01-27 16:50:16.232  9588 10130 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 270, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [0:0:0:0:0:0].
01-27 16:50:16.232  9588 10130 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
01-27 16:50:16.232  9588 10130 D io.jxcore.node.StreamCopyingThread:  id: 83
01-27 16:50:16.232  9588 10130 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
01-27 16:50:16.232  9588 10130 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
01-27 16:50:16.232  9588 10130 D io.jxcore.node.StreamCopyingThread:  id: 83
01-27 16:50:16.232  9588 10130 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
01-27 16:50:16.232  9588 10130 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
01-27 16:50:16.232  9588 10130 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
01-27 16:50:16.232  9588 10130 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
01-27 16:50:16.232  9588 10130 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
01-27 16:50:16.232  9588 10130 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 270, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [0:0:0:0:0:0].
01-27 16:50:16.232  9588 10130 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
01-27 16:50:16.232  9588 10130 D io.jxcore.node.StreamCopyingThread:  id: 83 .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,01-27 16:50:18.632  9588  9651 I StreamCopyingThreadTest: Starting test: testCopyBigData
,01-27 16:50:18.672  9588 10133 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 273, name: testCopyBigData thread). Connection data: Peer properties: [0:0:0:0:0:0].
01-27 16:50:18.672  9588 10133 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
01-27 16:50:18.672  9588 10133 D io.jxcore.node.StreamCopyingThread:  id: 85
,01-27 16:50:19.042  3465  6030 D SSRM:n  : SIOP:: AP = 370, PST = 351 (W:6), CP = 281, CUR = 101, LCD = 40
,01-27 16:50:20.182  9588 10133 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 273, thread name: testCopyBigData thread). Connection data: Peer properties: [0:0:0:0:0:0].
01-27 16:50:20.182  9588 10133 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
01-27 16:50:20.182  9588 10133 D io.jxcore.node.StreamCopyingThread:  id: 85
01-27 16:50:20.182  9588 10133 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
01-27 16:50:20.182  9588 10133 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
01-27 16:50:20.182  9588 10133 D io.jxcore.node.StreamCopyingThread:  id: 85
01-27 16:50:20.182  9588 10133 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
01-27 16:50:20.182  9588 10133 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
01-27 16:50:20.182  9588 10133 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
01-27 16:50:20.182  9588 10133 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
01-27 16:50:20.182  9588 10133 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
01-27 16:50:20.182  9588 10133 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 273, name: testCopyBigData thread). Connection data: Peer properties: [0:0:0:0:0:0].
01-27 16:50:20.182  9588 10133 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
01-27 16:50:20.182  9588 10133 D io.jxcore.node.StreamCopyingThread:  id: 85 .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,01-27 16:50:22.582  9588  9651 I StreamCopyingThreadTest: Starting test: testRunNotify
,01-27 16:50:22.582  9588 10134 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 275, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
01-27 16:50:22.582  9588 10134 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
01-27 16:50:22.582  9588 10134 D io.jxcore.node.StreamCopyingThread:  id: 86
01-27 16:50:22.582  9588 10134 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 275, thread name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
01-27 16:50:22.582  9588 10134 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
01-27 16:50:22.582  9588 10134 D io.jxcore.node.StreamCopyingThread:  id: 86
01-27 16:50:22.582  9588 10134 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
01-27 16:50:22.582  9588 10134 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
01-27 16:50:22.582  9588 10134 D io.jxcore.node.StreamCopyingThread:  id: 86
01-27 16:50:22.582  9588 10134 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
01-27 16:50:22.582  9588 10134 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
01-27 16:50:22.582  9588 10134 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
01-27 16:50:22.582  9588 10134 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
01-27 16:50:22.582  9588 10134 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
01-27 16:50:22.582  9588 10134 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 275, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
01-27 16:50:22.582  9588 10134 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
01-27 16:50:22.582  9588 10134 D io.jxcore.node.StreamCopyingThread:  id: 86 .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
01-27 16:50:22.582  9588  9651 I StreamCopyingThreadTest: Starting test: testSetBufferSize
01-27 16:50:22.582  9588  9651 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
01-27 16:50:22.582  9588  9651 I StreamCopyingThreadTest: Starting test: testRunWithException
01-27 16:50:22.582  9588 10135 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 279, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
01-27 16:50:22.582  9588 10135 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
01-27 16:50:22.582  9588 10135 D io.jxcore.node.StreamCopyingThread:  id: 89
01-27 16:50:22.582  9588 10135 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 279, thread name: My test thread name): Test exception.
01-27 16:50:22.582  9588 10135 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 279, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
01-27 16:50:22.582  9588 10135 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
01-27 16:50:22.582  9588 10135 D io.jxcore.node.StreamCopyingThread:  id: 89 .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
01-27 16:50:22.582  9588 10135 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
01-27 16:50:22.582  9588 10135 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 279, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
01-27 16:50:22.582  9588 10135 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
01-27 16:50:22.582  9588 10135 D io.jxcore.node.StreamCopyingThread:  id: 89 .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
01-27 16:50:22.582  9588  9651 I jxcore-log: 2017-01-27 15:50:22 - DEBUG UnitTest_app: 'Running unit tests'
01-27 16:50:22.582  9588  9651 I jxcore-log: 
01-27 16:50:22.582  9588  9651 I jxcore-log: *Native ,tests were executed*
01-27 16:50:22.582  9588  9651 I jxcore-log: 
01-27 16:50:22.582  9588  9651 I jxcore-log: Total number of executed tests:  78
01-27 16:50:22.582  9588  9651 I jxcore-log: 
01-27 16:50:22.582  9588  9651 I jxcore-log: Number of passed tests:  76
01-27 16:50:22.582  9588  9651 I jxcore-log: 
01-27 16:50:22.582  9588  9651 I jxcore-log: Number of failed tests:  0
01-27 16:50:22.582  9588  9651 I jxcore-log: 
01-27 16:50:22.582  9588  9651 I jxcore-log: Number of ignored tests:  2
01-27 16:50:22.582  9588  9651 I jxcore-log: 
01-27 16:50:22.582  9588  9651 I jxcore-log: Total duration:  44353
01-27 16:50:22.582  9588  9651 I jxcore-log: 
01-27 16:50:22.582  9588  9651 I jxcore-log: 2017-01-27 15:50:22 - DEBUG UnitTest_app: 'My device name is: 'samsung-SM-G930F''
01-27 16:50:22.582  9588  9651 I jxcore-log: 
01-27 16:50:22.582  9588  9651 I jxcore-log: 2017-01-27 15:50:22 - WARN testUtils: 'myNameCallback not set!'
01-27 16:50:22.582  9588  9651 I jxcore-log: 
,01-27 16:50:23.402  3465  6068 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,01-27 16:50:23.882  9588  9651 I jxcore-log: 2017-01-27 15:50:23 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: android'
01-27 16:50:23.882  9588  9651 I jxcore-log: 
,01-27 16:50:23.882  9588  9651 I jxcore-log: 2017-01-27 15:50:23 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
01-27 16:50:23.882  9588  9651 I jxcore-log: 
,01-27 16:50:23.892  9588  9651 I jxcore-log: 2017-01-27 15:50:23 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
01-27 16:50:23.892  9588  9651 I jxcore-log: 
,01-27 16:50:24.202  9588  9651 I jxcore-log: 2017-01-27 15:50:24 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
01-27 16:50:24.202  9588  9651 I jxcore-log: 
,01-27 16:50:24.232  9588  9651 I jxcore-log: 2017-01-27 15:50:24 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
01-27 16:50:24.232  9588  9651 I jxcore-log: 
,01-27 16:50:24.242  9588  9651 I jxcore-log: 2017-01-27 15:50:24 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
01-27 16:50:24.242  9588  9651 I jxcore-log: 
,01-27 16:50:24.262  9588  9651 I jxcore-log: 2017-01-27 15:50:24 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testUsn.js'
01-27 16:50:24.262  9588  9651 I jxcore-log: 
,01-27 16:50:24.282  9588  9651 I jxcore-log: 2017-01-27 15:50:24 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
01-27 16:50:24.282  9588  9651 I jxcore-log: 
,01-27 16:50:24.282  9588  9651 I jxcore-log: 2017-01-27 15:50:24 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
01-27 16:50:24.282  9588  9651 I jxcore-log: 
,01-27 16:50:24.322  9588  9651 I jxcore-log: 2017-01-27 15:50:24 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
01-27 16:50:24.322  9588  9651 I jxcore-log: 
,01-27 16:50:24.332  9588  9651 I jxcore-log: 2017-01-27 15:50:24 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
01-27 16:50:24.332  9588  9651 I jxcore-log: 
,01-27 16:50:24.342  9588  9651 I jxcore-log: 2017-01-27 15:50:24 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
01-27 16:50:24.342  9588  9651 I jxcore-log: 
,01-27 16:50:24.342  9588  9651 I jxcore-log: 2017-01-27 15:50:24 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
01-27 16:50:24.342  9588  9651 I jxcore-log: 
,01-27 16:50:24.542  9588  9651 I jxcore-log: 2017-01-27 15:50:24 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
01-27 16:50:24.542  9588  9651 I jxcore-log: 
,01-27 16:50:24.552  9588  9651 I jxcore-log: 2017-01-27 15:50:24 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
01-27 16:50:24.552  9588  9651 I jxcore-log: 
,01-27 16:50:24.612  9588  9651 I jxcore-log: 2017-01-27 15:50:24 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
01-27 16:50:24.612  9588  9651 I jxcore-log: 
,01-27 16:50:24.632  9588  9651 I jxcore-log: 2017-01-27 15:50:24 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
01-27 16:50:24.632  9588  9651 I jxcore-log: 
,01-27 16:50:24.642  9588  9651 I jxcore-log: 2017-01-27 15:50:24 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
01-27 16:50:24.642  9588  9651 I jxcore-log: 
,01-27 16:50:24.782  9588  9651 I jxcore-log: 2017-01-27 15:50:24 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
01-27 16:50:24.782  9588  9651 I jxcore-log: 
,01-27 16:50:24.872  3465  4382 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,01-27 16:50:24.872  3465  4382 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4274, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
01-27 16:50:24.872  3465  4382 D BatteryService: online:4, current avg:-308, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-558
01-27 16:50:24.872  3465  3465 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,01-27 16:50:24.882  3465  3465 I MotionRecognitionService: Plugged
,01-27 16:50:24.882  3465  3465 D MotionRecognitionService:   cableConnection= 1
01-27 16:50:24.882  3465  3465 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
01-27 16:50:24.882  3465  3465 D MotionRecognitionService: skip setTransmitPower. 
,01-27 16:50:24.882  3465  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,01-27 16:50:24.882  3950  3950 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
01-27 16:50:24.882  3950  3950 D KeyguardUpdateMonitor: handleBatteryUpdate
,01-27 16:50:24.882  3950  3950 D PowerUI : priorPlugType = 2 mPlugType =  2
,01-27 16:50:24.882  3950  3950 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,01-27 16:50:24.882  3950  3950 D PowerUI.Notification: There is no change about charging status, so return!
,01-27 16:50:24.892  4990  4990 D CommonServiceConfiguration: getStringValueSetting
,01-27 16:50:24.892  4942  4942 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,01-27 16:50:24.892  4942  9696 D HeadsetStateMachine: Disconnected process message: 10, size: 0
01-27 16:50:24.892  4990  4990 D BatteryMonitor: new battery level: 100
,01-27 16:50:24.902  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,01-27 16:50:24.902  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,01-27 16:50:24.922  9588  9651 I jxcore-log: 2017-01-27 15:50:24 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
01-27 16:50:24.922  9588  9651 I jxcore-log: 
,01-27 16:50:24.952  9588  9651 I jxcore-log: 2017-01-27 15:50:24 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
01-27 16:50:24.952  9588  9651 I jxcore-log: 
,01-27 16:50:24.982  9588  9651 I jxcore-log: 2017-01-27 15:50:24 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
01-27 16:50:24.982  9588  9651 I jxcore-log: 
,01-27 16:50:24.992  9588  9651 I jxcore-log: 2017-01-27 15:50:24 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
01-27 16:50:24.992  9588  9651 I jxcore-log: 
,01-27 16:50:25.032  9588  9651 I jxcore-log: 2017-01-27 15:50:25 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
01-27 16:50:25.032  9588  9651 I jxcore-log: 
,01-27 16:50:25.062  9588  9651 I jxcore-log: 2017-01-27 15:50:25 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
01-27 16:50:25.062  9588  9651 I jxcore-log: 
,01-27 16:50:25.632  9588  9651 I jxcore-log: 2017-01-27 15:50:25 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
01-27 16:50:25.632  9588  9651 I jxcore-log: 
,01-27 16:50:25.652  9588  9651 I jxcore-log: 2017-01-27 15:50:25 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
01-27 16:50:25.652  9588  9651 I jxcore-log: 
,01-27 16:50:25.662  9588  9651 I jxcore-log: 2017-01-27 15:50:25 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
01-27 16:50:25.662  9588  9651 I jxcore-log: 
,01-27 16:50:25.662  9588  9651 I jxcore-log: 2017-01-27 15:50:25 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
01-27 16:50:25.662  9588  9651 I jxcore-log: 
,01-27 16:50:25.672  9588  9651 I jxcore-log: 2017-01-27 15:50:25 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
01-27 16:50:25.672  9588  9651 I jxcore-log: 
,01-27 16:50:25.692  9588  9651 I jxcore-log: 2017-01-27 15:50:25 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
01-27 16:50:25.692  9588  9651 I jxcore-log: 
,01-27 16:50:25.702  9588  9651 I jxcore-log: 2017-01-27 15:50:25 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
01-27 16:50:25.702  9588  9651 I jxcore-log: 
,01-27 16:50:25.712  9588  9651 I jxcore-log: 2017-01-27 15:50:25 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
01-27 16:50:25.712  9588  9651 I jxcore-log: 
,01-27 16:50:25.722  9588  9651 I jxcore-log: 2017-01-27 15:50:25 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
01-27 16:50:25.722  9588  9651 I jxcore-log: 
,01-27 16:50:25.722  9588  9651 I jxcore-log: 2017-01-27 15:50:25 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
01-27 16:50:25.722  9588  9651 I jxcore-log: 
,01-27 16:50:25.742  9588  9651 I jxcore-log: 2017-01-27 15:50:25 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
01-27 16:50:25.742  9588  9651 I jxcore-log: 
,01-27 16:50:25.752  9588  9651 I jxcore-log: 2017-01-27 15:50:25 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
01-27 16:50:25.752  9588  9651 I jxcore-log: 
,01-27 16:50:25.762  9588  9651 I jxcore-log: 2017-01-27 15:50:25 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
01-27 16:50:25.762  9588  9651 I jxcore-log: 
,01-27 16:50:25.842  9588  9651 I jxcore-log: 2017-01-27 15:50:25 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
01-27 16:50:25.842  9588  9651 I jxcore-log: 
,01-27 16:50:25.932  9588  9651 I jxcore-log: 2017-01-27 15:50:25 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testSSDPServer.js'
01-27 16:50:25.932  9588  9651 I jxcore-log: 
,01-27 16:50:25.942  9588  9651 D BluetoothAdapter: STATE_ON
,01-27 16:50:25.952  9588  9651 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,01-27 16:50:25.952  9588  9651 I jxcore-log: 2017-01-27 15:50:25 - INFO testUtils: 'BLE multiple advertisement supported'
01-27 16:50:25.952  9588  9651 I jxcore-log: 
,01-27 16:50:25.952  9588  9651 I jxcore-log: 2017-01-27 15:50:25 - DEBUG UnitTest_app: 'Unit Test app is loaded'
01-27 16:50:25.952  9588  9651 I jxcore-log: 
,01-27 16:50:25.962  9588  9651 I jxcore-log: 2017-01-27 15:50:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"NG700"}'
01-27 16:50:25.962  9588  9651 I jxcore-log: 
,01-27 16:50:25.962  9588  9651 I jxcore-log: 2017-01-27 15:50:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
01-27 16:50:25.962  9588  9651 I jxcore-log: 
01-27 16:50:25.962  9588  9651 I jxcore-log: 2017-01-27 15:50:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"NG700"}'
01-27 16:50:25.962  9588  9651 I jxcore-log: 
01-27 16:50:25.962  9588  9651 I jxcore-log: 2017-01-27 15:50:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
01-27 16:50:25.962  9588  9651 I jxcore-log: 
01-27 16:50:25.962  9588  9651 I jxcore-log: 2017-01-27 15:50:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"NG700"}'
01-27 16:50:25.962  9588  9651 I jxcore-log: 
01-27 16:50:25.962  9588  9651 I jxcore-log: 2017-01-27 15:50:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
01-27 16:50:25.962  9588  9651 I jxcore-log: 
,01-27 16:50:25.962  9588  9651 I jxcore-log: 2017-01-27 15:50:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":null,"ssidName":null}'
01-27 16:50:25.962  9588  9651 I jxcore-log: 
01-27 16:50:25.962  9588  9651 I jxcore-log: 2017-01-27 15:50:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
01-27 16:50:25.962  9588  9651 I jxcore-log: 
01-27 16:50:25.962  9588  9651 I jxcore-log: 2017-01-27 15:50:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare","bssidName":null,"ssidName":null}'
01-27 16:50:25.962  9588  9651 I jxcore-log: 
01-27 16:50:25.962  9588  9651 I jxcore-log: 2017-01-27 15:50:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
01-27 16:50:25.962  9588  9651 I jxcore-log: 
,01-27 16:50:25.962  9588  9651 I jxcore-log: 2017-01-27 15:50:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":null,"ssidName":null}'
01-27 16:50:25.962  9588  9651 I jxcore-log: 
01-27 16:50:25.962  9588  9651 I jxcore-log: 2017-01-27 15:50:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
01-27 16:50:25.962  9588  9651 I jxcore-log: 
01-27 16:50:25.962  9588  9651 I jxcore-log: 2017-01-27 15:50:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"NG700"}'
01-27 16:50:25.962  9588  9651 I jxcore-log: 
,01-27 16:50:25.962  9588  9651 I jxcore-log: 2017-01-27 15:50:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
01-27 16:50:25.962  9588  9651 I jxcore-log: 
,01-27 16:50:25.972  9588  9588 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 68 : UIApp is all set and ready!
,01-27 16:50:25.972  9588  9588 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,01-27 16:50:25.992  9588  9651 I jxcore-log: 2017-01-27 15:50:26 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
01-27 16:50:25.992  9588  9651 I jxcore-log: 
,01-27 16:50:26.112  9588  9651 I jxcore-log: 2017-01-27 15:50:26 - DEBUG CoordinatedClient: 'connected to the test server'
01-27 16:50:26.112  9588  9651 I jxcore-log: 
,01-27 16:50:26.342  9588  9651 I jxcore-log: 2017-01-27 15:50:26 - DEBUG CoordinatedClient: 'device disconnected from the test server'
01-27 16:50:26.342  9588  9651 I jxcore-log: 
,01-27 16:50:26.802  3465  3484 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,01-27 16:50:26.802  3465  3484 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4331, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
01-27 16:50:26.802  3465  3484 D BatteryService: online:4, current avg:-322, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:166
01-27 16:50:26.802  3465  3465 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,01-27 16:50:26.812  3465  3465 I MotionRecognitionService: Plugged
01-27 16:50:26.812  3465  3465 D MotionRecognitionService:   cableConnection= 1
01-27 16:50:26.812  3465  3465 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
01-27 16:50:26.812  3465  3465 D MotionRecognitionService: skip setTransmitPower. 
,01-27 16:50:26.812  3465  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,01-27 16:50:26.812  3950  3950 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
01-27 16:50:26.812  3950  3950 D KeyguardUpdateMonitor: handleBatteryUpdate
,01-27 16:50:26.812  3950  3950 D PowerUI : priorPlugType = 2 mPlugType =  2
,01-27 16:50:26.822  3950  3950 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
01-27 16:50:26.822  3950  3950 D PowerUI.Notification: There is no change about charging status, so return!
,01-27 16:50:26.822  4990  4990 D CommonServiceConfiguration: getStringValueSetting
,01-27 16:50:26.832  4990  4990 D BatteryMonitor: new battery level: 100
,01-27 16:50:26.832  4942  4942 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
01-27 16:50:26.832  4942  9696 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,01-27 16:50:26.842  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
01-27 16:50:26.842  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,01-27 16:50:26.922  3465  3973 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,01-27 16:50:26.922  3465  3973 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4331, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
01-27 16:50:26.922  3465  3973 D BatteryService: online:4, current avg:-314, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:166
01-27 16:50:26.922  3465  3465 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,01-27 16:50:26.922  3465  3465 I MotionRecognitionService: Plugged
,01-27 16:50:26.922  3465  3465 D MotionRecognitionService:   cableConnection= 1
01-27 16:50:26.922  3465  3465 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
01-27 16:50:26.922  3465  3465 D MotionRecognitionService: skip setTransmitPower. 
,01-27 16:50:26.932  3465  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,01-27 16:50:26.932  3950  3950 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,01-27 16:50:26.932  3950  3950 D KeyguardUpdateMonitor: handleBatteryUpdate
01-27 16:50:26.932  3950  3950 D PowerUI : priorPlugType = 2 mPlugType =  2
,01-27 16:50:26.932  3950  3950 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,01-27 16:50:26.932  3950  3950 D PowerUI.Notification: There is no change about charging status, so return!
,01-27 16:50:26.942  4990  4990 D CommonServiceConfiguration: getStringValueSetting
,01-27 16:50:26.952  4990  4990 D BatteryMonitor: new battery level: 100
,01-27 16:50:26.952  4942  4942 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,01-27 16:50:26.952  4942  9696 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,01-27 16:50:26.962  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,01-27 16:50:26.962  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,01-27 16:50:27.202  3465  4042 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
01-27 16:50:27.202  3465  4042 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4332, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
01-27 16:50:27.202  3465  4042 D BatteryService: online:4, current avg:-301, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:117
01-27 16:50:27.202  3465  3465 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,01-27 16:50:27.202  3465  3465 I MotionRecognitionService: Plugged
01-27 16:50:27.202  3465  3465 D MotionRecognitionService:   cableConnection= 1
01-27 16:50:27.202  3465  3465 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
01-27 16:50:27.202  3465  3465 D MotionRecognitionService: skip setTransmitPower. 
,01-27 16:50:27.202  3465  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,01-27 16:50:27.212  3950  3950 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
01-27 16:50:27.212  3950  3950 D KeyguardUpdateMonitor: handleBatteryUpdate
,01-27 16:50:27.212  3950  3950 D PowerUI : priorPlugType = 2 mPlugType =  2
,01-27 16:50:27.212  3950  3950 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,01-27 16:50:27.212  3950  3950 D PowerUI.Notification: There is no change about charging status, so return!
,01-27 16:50:27.222  4990  4990 D CommonServiceConfiguration: getStringValueSetting
,01-27 16:50:27.222  4990  4990 D BatteryMonitor: new battery level: 100
,01-27 16:50:27.232  4942  4942 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,01-27 16:50:27.232  4942  9696 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,01-27 16:50:27.242  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,01-27 16:50:27.242  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,01-27 16:50:27.662  3465  4152 E Watchdog: !@Sync 8 [01-27 16:50:27.671]
,01-27 16:50:28.692  4261  4329 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
01-27 16:50:28.692  4261  4329 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,01-27 16:50:28.832  9588  9651 I jxcore-log: 2017-01-27 15:50:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
01-27 16:50:28.832  9588  9651 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
01-27 16:50:28.832  9588  9651 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
01-27 16:50:28.832  9588  9651 I jxcore-log: emit@events.js:82:1
01-27 16:50:28.832  9588  9651 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
01-27 16:50:28.832  9588  9651 I jxcore-log: emit@events.js:82:1''
01-27 16:50:28.832  9588  9651 I jxcore-log: 
,01-27 16:50:28.842  9588  9651 I jxcore-log: 2017-01-27 15:50:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
01-27 16:50:28.842  9588  9651 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
01-27 16:50:28.842  9588  9651 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
01-27 16:50:28.842  9588  9651 I jxcore-log: emit@events.js:82:1
01-27 16:50:28.842  9588  9651 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
01-27 16:50:28.842  9588  9651 I jxcore-log: emit@events.js:82:1''
01-27 16:50:28.842  9588  9651 I jxcore-log: 
,01-27 16:50:28.932  3465  4331 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,01-27 16:50:28.932  3465  4331 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4329, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
01-27 16:50:28.932  3465  4331 D BatteryService: online:4, current avg:-235, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:47
01-27 16:50:28.932  3465  3465 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,01-27 16:50:28.942  3465  3465 I MotionRecognitionService: Plugged
01-27 16:50:28.942  3465  3465 D MotionRecognitionService:   cableConnection= 1
01-27 16:50:28.942  3465  3465 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
01-27 16:50:28.942  3465  3465 D MotionRecognitionService: skip setTransmitPower. 
,01-27 16:50:28.952  3465  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,01-27 16:50:28.952  3950  3950 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
01-27 16:50:28.952  3950  3950 D KeyguardUpdateMonitor: handleBatteryUpdate
,01-27 16:50:28.952  3950  3950 D PowerUI : priorPlugType = 2 mPlugType =  2
,01-27 16:50:28.952  3950  3950 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,01-27 16:50:28.952  3950  3950 D PowerUI.Notification: There is no change about charging status, so return!
,01-27 16:50:28.972  4990  4990 D CommonServiceConfiguration: getStringValueSetting
,01-27 16:50:28.982  4942  4942 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
01-27 16:50:28.982  4942  9696 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,01-27 16:50:28.982  4990  4990 D BatteryMonitor: new battery level: 100
,01-27 16:50:29.002  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,01-27 16:50:29.002  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,01-27 16:50:29.062  3465  6030 D SSRM:n  : SIOP:: AP = 390, PST = 353 (W:6), CP = 294, CUR = -235, LCD = 40
,01-27 16:50:29.222  3465  4225 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
01-27 16:50:29.222  3465  4225 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4325, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
01-27 16:50:29.222  3465  4225 D BatteryService: online:4, current avg:-231, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:110
01-27 16:50:29.222  3465  3465 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,01-27 16:50:29.222  3465  3465 I MotionRecognitionService: Plugged
01-27 16:50:29.222  3465  3465 D MotionRecognitionService:   cableConnection= 1
01-27 16:50:29.222  3465  3465 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
01-27 16:50:29.222  3465  3465 D MotionRecognitionService: skip setTransmitPower. 
,01-27 16:50:29.232  3465  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,01-27 16:50:29.232  3950  3950 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
01-27 16:50:29.232  3950  3950 D KeyguardUpdateMonitor: handleBatteryUpdate
,01-27 16:50:29.232  3950  3950 D PowerUI : priorPlugType = 2 mPlugType =  2
,01-27 16:50:29.232  3950  3950 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
01-27 16:50:29.232  3950  3950 D PowerUI.Notification: There is no change about charging status, so return!
,01-27 16:50:29.242  4990  4990 D CommonServiceConfiguration: getStringValueSetting
,01-27 16:50:29.242  4990  4990 D BatteryMonitor: new battery level: 100
,01-27 16:50:29.252  4942  4942 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,01-27 16:50:29.252  4942  9696 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,01-27 16:50:29.262  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,01-27 16:50:29.262  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,01-27 16:50:33.732  9588  9651 I jxcore-log: 2017-01-27 15:50:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
01-27 16:50:33.732  9588  9651 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
01-27 16:50:33.732  9588  9651 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
01-27 16:50:33.732  9588  9651 I jxcore-log: emit@events.js:82:1
01-27 16:50:33.732  9588  9651 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
01-27 16:50:33.732  9588  9651 I jxcore-log: emit@events.js:82:1''
01-27 16:50:33.732  9588  9651 I jxcore-log: 
,01-27 16:50:33.742  9588  9651 I jxcore-log: 2017-01-27 15:50:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
01-27 16:50:33.742  9588  9651 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
01-27 16:50:33.742  9588  9651 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
01-27 16:50:33.742  9588  9651 I jxcore-log: emit@events.js:82:1
01-27 16:50:33.742  9588  9651 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
01-27 16:50:33.742  9588  9651 I jxcore-log: emit@events.js:82:1''
01-27 16:50:33.742  9588  9651 I jxcore-log: 
,01-27 16:50:33.822  3465  4331 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,01-27 16:50:33.822  3465  4331 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4329, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
01-27 16:50:33.822  3465  4331 D BatteryService: online:4, current avg:-101, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:68
01-27 16:50:33.822  3465  3465 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,01-27 16:50:33.832  3465  3465 I MotionRecognitionService: Plugged
,01-27 16:50:33.832  3465  3465 D MotionRecognitionService:   cableConnection= 1
01-27 16:50:33.832  3465  3465 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
01-27 16:50:33.832  3465  3465 D MotionRecognitionService: skip setTransmitPower. 
,01-27 16:50:33.832  3465  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,01-27 16:50:33.832  3950  3950 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
01-27 16:50:33.832  3950  3950 D KeyguardUpdateMonitor: handleBatteryUpdate
,01-27 16:50:33.842  3950  3950 D PowerUI : priorPlugType = 2 mPlugType =  2
01-27 16:50:33.842  3950  3950 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
01-27 16:50:33.842  3950  3950 D PowerUI.Notification: There is no change about charging status, so return!
,01-27 16:50:33.852  4990  4990 D CommonServiceConfiguration: getStringValueSetting
,01-27 16:50:33.862  4990  4990 D BatteryMonitor: new battery level: 100
01-27 16:50:33.862  4942  4942 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
01-27 16:50:33.862  4942  9696 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,01-27 16:50:33.872  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,01-27 16:50:33.872  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,01-27 16:50:34.092  3465  4489 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,01-27 16:50:34.092  3465  4489 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4329, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
01-27 16:50:34.092  3465  4489 D BatteryService: online:4, current avg:-98, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:72
01-27 16:50:34.092  3465  3465 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,01-27 16:50:34.102  3465  3465 I MotionRecognitionService: Plugged
01-27 16:50:34.102  3465  3465 D MotionRecognitionService:   cableConnection= 1
01-27 16:50:34.102  3465  3465 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
01-27 16:50:34.102  3465  3465 D MotionRecognitionService: skip setTransmitPower. 
,01-27 16:50:34.102  3465  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,01-27 16:50:34.102  3950  3950 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
01-27 16:50:34.102  3950  3950 D KeyguardUpdateMonitor: handleBatteryUpdate
,01-27 16:50:34.112  3950  3950 D PowerUI : priorPlugType = 2 mPlugType =  2
,01-27 16:50:34.112  3950  3950 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
01-27 16:50:34.112  3950  3950 D PowerUI.Notification: There is no change about charging status, so return!
,01-27 16:50:34.122  4990  4990 D CommonServiceConfiguration: getStringValueSetting
,01-27 16:50:34.122  4990  4990 D BatteryMonitor: new battery level: 100
,01-27 16:50:34.122  4942  4942 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
01-27 16:50:34.122  4942  9696 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,01-27 16:50:34.142  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,01-27 16:50:34.142  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,01-27 16:50:34.632  3465  4416 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
01-27 16:50:34.632  3465  4416 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4336, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
01-27 16:50:34.632  3465  4416 D BatteryService: online:4, current avg:-87, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:157
01-27 16:50:34.632  3465  3465 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,01-27 16:50:34.642  3465  3465 I MotionRecognitionService: Plugged
,01-27 16:50:34.642  3465  3465 D MotionRecognitionService:   cableConnection= 1
01-27 16:50:34.642  3465  3465 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
01-27 16:50:34.642  3465  3465 D MotionRecognitionService: skip setTransmitPower. 
,01-27 16:50:34.652  3465  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,01-27 16:50:34.652  3950  3950 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,01-27 16:50:34.652  3950  3950 D KeyguardUpdateMonitor: handleBatteryUpdate
,01-27 16:50:34.652  3950  3950 D PowerUI : priorPlugType = 2 mPlugType =  2
,01-27 16:50:34.652  3950  3950 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,01-27 16:50:34.652  3950  3950 D PowerUI.Notification: There is no change about charging status, so return!
,01-27 16:50:34.672  4990  4990 D CommonServiceConfiguration: getStringValueSetting
,01-27 16:50:34.682  4990  4990 D BatteryMonitor: new battery level: 100
,01-27 16:50:34.692  4942  4942 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,01-27 16:50:34.692  4942  9696 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,01-27 16:50:34.702  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
01-27 16:50:34.702  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,01-27 16:50:34.762  3465  3483 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,01-27 16:50:34.762  3465  3483 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4334, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
01-27 16:50:34.762  3465  3483 D BatteryService: online:4, current avg:-83, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:185
01-27 16:50:34.762  3465  3465 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,01-27 16:50:34.762  3465  3465 I MotionRecognitionService: Plugged
,01-27 16:50:34.762  3465  3465 D MotionRecognitionService:   cableConnection= 1
01-27 16:50:34.762  3465  3465 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
01-27 16:50:34.762  3465  3465 D MotionRecognitionService: skip setTransmitPower. 
,01-27 16:50:34.772  3465  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,01-27 16:50:34.772  3950  3950 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
01-27 16:50:34.772  3950  3950 D KeyguardUpdateMonitor: handleBatteryUpdate
,01-27 16:50:34.772  3950  3950 D PowerUI : priorPlugType = 2 mPlugType =  2
,01-27 16:50:34.772  3950  3950 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
01-27 16:50:34.772  3950  3950 D PowerUI.Notification: There is no change about charging status, so return!
,01-27 16:50:34.782  4990  4990 D CommonServiceConfiguration: getStringValueSetting
,01-27 16:50:34.792  4990  4990 D BatteryMonitor: new battery level: 100
,01-27 16:50:34.792  4942  4942 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,01-27 16:50:34.792  4942  9696 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,01-27 16:50:34.812  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,01-27 16:50:34.812  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2

```
