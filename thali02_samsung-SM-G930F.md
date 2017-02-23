#### Test 107380351ee7f847_thali02_samsung-SM-G930F Logs


```
--------- beginning of system
,02-23 11:45:46.515  3478  6391 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
--------- beginning of main
02-23 11:45:46.985  9542  9542 I FIPS_bssl: FIPS approved mode (1) | 9542 | app_process
02-23 11:45:46.995  9542  9542 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
02-23 11:45:46.995  9542  9542 D AndroidRuntime: CheckJNI is OFF
02-23 11:45:46.995  9542  9542 D AndroidRuntime: readGMSProperty: start
02-23 11:45:46.995  9542  9542 D AndroidRuntime: readGMSProperty: already setted!!
02-23 11:45:46.995  9542  9542 D AndroidRuntime: propertySet: couldn't set property (it is from app)
02-23 11:45:46.995  9542  9542 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
02-23 11:45:46.995  9542  9542 D AndroidRuntime: readGMSProperty: end
02-23 11:45:46.995  9542  9542 D AndroidRuntime: addProductProperty: start
02-23 11:45:47.015  9542  9542 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
02-23 11:45:47.035  9542  9542 I Radio-JNI: register_android_hardware_Radio DONE
02-23 11:45:47.045  9542  9542 E AffinityControl: AffinityControl: registerfunction enter
02-23 11:45:47.045  9542  9542 D AndroidRuntime: Calling main entry com.android.commands.am.Am
02-23 11:45:47.075  3478  4167 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
02-23 11:45:47.075  3478  4167 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
02-23 11:45:47.105  3478  4167 D ResourcesManager: For user 0 new overlays fetched Null
02-23 11:45:47.115  3478  4167 D GameManagerService: identifyGamePackage. com.test.thalitest
02-23 11:45:47.115  3478  4167 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
02-23 11:45:47.115  3478  4167 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3478  pkgName : ACTIVITY_RESUME_BOOSTER@3
02-23 11:45:47.115  3478  4167 D ActivityManager: mDVFSHelper.acquire()
02-23 11:45:47.115  3478  4167 V WindowManager: addAppToken: AppWindowToken{d06a113c4 token=Token{7cd5ed7 ActivityRecord{1ec6e56 u0 com.test.thalitest/.MainActivity t5}}} to stack=2 task=5 at 0
02-23 11:45:47.135  3478  4167 D InputDispatcher: Focused application set to: xxxx
02-23 11:45:47.135  3478  3579 I InjectionManager: Inside getClassLibPath caller 
02-23 11:45:47.135  3478  3579 D SecWifiDisplayUtil: Metadata value : SecSettings2
02-23 11:45:47.135  3478  3579 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{44d175c V.E...... R.....ID 0,0-0,0}
02-23 11:45:47.145  3478  4167 D InputDispatcher: Focus left window: 6447
02-23 11:45:47.145  3478  3579 D ISSUE_DEBUG: InputChannelName : 6993beb Starting com.test.thalitest
02-23 11:45:47.145  3478  3554 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{a3a00cd u0 d0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}
02-23 11:45:47.145  9542  9542 D AndroidRuntime: Shutting down VM
02-23 11:45:47.145  3942  3942 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=8000 newVal=8600 diff=600
02-23 11:45:47.155  3008  3008 I SurfaceFlinger: id=18 createSurf (1x1),1 flag=404, uhalitest
02-23 11:45:47.155  9551  9551 E Zygote  : v2
02-23 11:45:47.155  9551  9551 I libpersona: KNOX_SDCARD checking this for 10074
02-23 11:45:47.155  9551  9551 I libpersona: KNOX_SDCARD not a persona
02-23 11:45:47.155  9551  9551 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
02-23 11:45:47.155  3478  4303 I ActivityManager: Start proc 9551:com.test.thalitest/u0a74 for activity com.test.thalitest/.MainActivity
02-23 11:45:47.155  9551  9551 E Zygote  : accessInfo : 0
02-23 11:45:47.155  9551  9551 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
02-23 11:45:47.175  3478  3579 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3478 uid:1000
02-23 11:45:47.175  3478  3851 D NetworkPolicy: isUidForegroundLocked: 10074, mScreenOn: true, uidstate: -1, mProxSensorScreenOff: false
02-23 11:45:47.175  3478  3579 D PointerIcon: setMouseCustomIcon IconType is same.101
02-23 11:45:47.175  3478  3579 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
02-23 11:45:47.175  9551  9551 D TimaKeyStoreProvider: TimaSignature is unavailable
02-23 11:45:47.175  9551  9551 D ActivityThread: Added TimaKeyStore provider
02-23 11:45:47.175  3478  4277 V WindowOrientationListener: setCurrentAppOrientation :-1
02-23 11:45:47.175  3478  4277 V WindowOrientationListener: OrientationSensorJudge.getProposedRotation, Rotation: -1
02-23 11:45:47.175  3478  4277 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
02-23 11:45:47.175  3478  4277 V WindowOrientationListener: OrientationSensorJudge.getProposedRotation, Rotation: -1
02-23 11:45:47.175  3478  4277 D ActivityManager:  Launching com.test.thalitest, updated priority
02-23 11:45:47.175  4265  4265 D Launcher.HomeView: onStop
02-23 11:45:47.175  4265  4265 D capture : ----destroy
02-23 11:45:47.185  4265  4265 V ActivityThread: updateVisibility : ActivityRecord{722bd48 token=android.os.BinderProxy@50a13e2 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
02-23 11:45:47.185  3478  3478 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
02-23 11:45:47.195  3008  3070 D libEGL  : eglTerminate EGLDisplay = 0x7f9d5fee78
02-23 11:45:47.195  3008  3070 D libEGL  : eglTerminate EGLDisplay = 0x7f9d5fee78
02-23 11:45:47.195  3478  3553 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
02-23 11:45:47.195  3478  3579 V WindowStateAnimator: Finishing drawing window Window{6993beb u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
02-23 11:45:47.195  3478  6371 D GameManagerService: identifyGamePackage. com.test.thalitest
02-23 11:45:47.195  3478  6371 D GameManagerService: identifyGamePackage. com.test.thalitest
02-23 11:45:47.205  3008  3008 D libEGL  : eglInitialize EGLDisplay = 0x7fc150a738
02-23 11:45:47.205  3478  3554 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{6993beb u0 d0 Starting com.test.thalitest}
02-23 11:45:47.205  9551  9551 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
02-23 11:45:47.205  3478  4384 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
02-23 11:45:47.205  9551  9551 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
02-23 11:45:47.205  4265  4265 D Launcher: onTrimMemory. Level: 20
02-23 11:45:47.205  3478  3574 D MARsDBManager: onChange - mSmartManagerObserver! Uri = content://com.samsung.android.sm/AppFreezer?MARs-self=true&MARs=true
02-23 11:45:47.215  3008  4309 D libEGL  : eglTerminate EGLDisplay = 0x7f9c5fee78
02-23 11:45:47.215  3008  4309 D libEGL  : eglTerminate EGLDisplay = 0x7f9c5fee78
02-23 11:45:47.215  9551  9551 D ResourcesManager: For user 0 new overlays fetched Null
02-23 11:45:47.225  9551  9551 I InjectionManager: Inside getClassLibPath caller 
02-23 11:45:47.225  3478  6371 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
02-23 11:45:47.225  3478  6371 D GameManagerService: identifyGamePackage. com.test.thalitest
02-23 11:45:47.235  9551  9551 D InjectionManager: InjectionManager
02-23 11:45:47.235  9551  9551 D InjectionManager: fillFeatureStoreMap com.test.thalitest
02-23 11:45:47.235  3478  6371 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
02-23 11:45:47.235  9551  9551 I InjectionManager: Constructor com.test.thalitest, Feature store :{}
02-23 11:45:47.235  9551  9551 I InjectionManager: featureStore :{}
02-23 11:45:47.235  3478  6371 D GameManagerService: identifyGamePackage. com.test.thalitest
02-23 11:45:47.235  3478  6371 D GameManagerService: identifyGamePackage. com.test.thalitest
02-23 11:45:47.235  9551  9551 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
02-23 11:45:47.235  9551  9551 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
02-23 11:45:47.235  9551  9551 D RelationGraph: garbageCollect()
02-23 11:45:47.235  9551  9551 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
02-23 11:45:47.245  3478  3489 I art     : Background partial concurrent mark sweep GC freed 83100(5MB) AllocSpace objects, 72(1440KB) LOS objects, 31% free, 35MB/51MB, paused 1.390ms total 118.645ms
02-23 11:45:47.255  9551  9551 I CordovaLog: Changing log level to DEBUG(3)
02-23 11:45:47.255  9551  9551 I CordovaActivity: Apache Cordova native platform version 6.0.0 is starting
02-23 11:45:47.255  9551  9551 D CordovaActivity: CordovaActivity.onCreate()
02-23 11:45:47.255  9551  9551 I WebViewFactory: Loading com.google.android.webview version 50.0.2661.86 (code 266108650)
02-23 11:45:47.275  9551  9551 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package com.google.android.webview
02-23 11:45:47.275  9551  9551 D ResourcesManager: For user 0 new overlays fetched Null
02-23 11:45:47.275  9551  9551 I InjectionManager: Inside getClassLibPath caller 
02-23 11:45:47.275  9551  9551 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
02-23 11:45:47.315  9551  9551 I cr_LibraryLoader: Time to load native libraries: 20 ms (timestamps 3001-3021)
02-23 11:45:47.315  9551  9551 I cr_LibraryLoader: Expected native library version number "50.0.2661.86", actual native library version number "50.0.2661.86"
02-23 11:45:47.325  9551  9566 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
02-23 11:45:47.345  9551  9551 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {99d20de}
02-23 11:45:47.345  9551  9551 I cr_LibraryLoader: Expected native library version number "50.0.2661.86", actual native library version number "50.0.2661.86"
02-23 11:45:47.365  9551  9551 I chromium: [INFO:library_loader_hooks.cc(143)] Chromium logging enabled: level = 0, default verbosity = 0
,02-23 11:45:47.395  9551  9551 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,02-23 11:45:47.445  3478  3875 D MdnieScenarioControlService:  packageName : com.test.thalitest    className : com.test.thalitest.MainActivity
,02-23 11:45:47.475  9551  9551 D libEGL  : eglInitialize EGLDisplay = 0xffe89264
,02-23 11:45:47.525  3478  4278 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10074
,02-23 11:45:47.525  3478  4278 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29757 com.android.server.am.ActivityManagerService.registerReceiver:22622 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,02-23 11:45:47.545  3478  3851 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: true, uidstate: 2, mProxSensorScreenOff: false
,02-23 11:45:47.545  3478  3875 I MdnieScenarioControlService: mGameModeLauncher : false
,02-23 11:45:47.555  3478  3875 I MdnieScenarioControlService: setUIMode
,02-23 11:45:47.565  9551  9551 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10074, CallingPid : 9551
,02-23 11:45:47.565  3478  4414 D ConnectivityService: listenForNetwork for Listen from uid/pid:10074/9551 for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,02-23 11:45:47.565  3478  3862 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
02-23 11:45:47.565  3478  3862 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -50]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,02-23 11:45:47.565  3478  3862 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,02-23 11:45:47.575  3478  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
02-23 11:45:47.575  3008  3021 I SurfaceFlinger: id=9 Removed MauncherAct (4/13)
02-23 11:45:47.575  3008  3021 I SurfaceFlinger: id=9 Removed MauncherAct (-2/13)
,02-23 11:45:47.575  3008  4309 I SurfaceFlinger: id=17 Removed VSBConnecti (4/12)
02-23 11:45:47.575  3008  3019 I SurfaceFlinger: id=17 Removed VSBConnecti (-2/12)
02-23 11:45:47.575  3008  4456 I SurfaceFlinger: id=16 Removed VSBConnecti (5/11)
,02-23 11:45:47.575  3008  3070 I SurfaceFlinger: id=16 Removed VSBConnecti (-2/11)
,02-23 11:45:47.575  3942  3942 D ImageWallpaper: onVisibilityChanged:false
,02-23 11:45:47.575  3942  3942 D ImageWallpaper: drawFrame:false rotation:0 mLastRotation:0
02-23 11:45:47.575  3942  3942 D ImageWallpaper: drawFrame:[frame.width()]2240[frame.height()]2560
02-23 11:45:47.575  3478  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
02-23 11:45:47.575  3942  3942 D ImageWallpaper: Suppressed drawFrame since redraw is not needed and offsets have not changed.
,02-23 11:45:47.575  3478  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,02-23 11:45:47.575  9551  9551 D cr_Ime  : [InputMethodManagerWrapper.java:30] Constructor
02-23 11:45:47.575  3478  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,02-23 11:45:47.575  3478  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,02-23 11:45:47.575  3478  3862 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,02-23 11:45:47.585  3008  3008 D libEGL  : eglTerminate EGLDisplay = 0x7fc150a858
,02-23 11:45:47.585  3008  3008 D libEGL  : eglTerminate EGLDisplay = 0x7fc150a858
02-23 11:45:47.585  3008  3008 D libEGL  : eglTerminate EGLDisplay = 0x7fc150a858
,02-23 11:45:47.595  9551  9551 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,02-23 11:45:47.595  9551  9551 D cr_Ime  : [InputMethodManagerWrapper.java:59] isActive: false
,02-23 11:45:47.605  9551  9551 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,02-23 11:45:47.615  9551  9551 D PluginManager: init()
,02-23 11:45:47.615  9551  9551 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,02-23 11:45:47.625  9551  9551 I cr_Ime  : ImeThread is not enabled.
,02-23 11:45:47.625  9551  9551 D Activity: performCreate Call Injection manager
,02-23 11:45:47.635  9551  9551 D CordovaActivity: Started the activity.
02-23 11:45:47.635  9551  9551 I InjectionManager: dispatchOnViewCreated > Target : com.test.thalitest.MainActivity isFragment :false
02-23 11:45:47.635  9551  9551 D CordovaActivity: Resumed the activity.
,02-23 11:45:47.635  9551  9551 D SecWifiDisplayUtil: Metadata value : SecSettings2
,02-23 11:45:47.635  9551  9551 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{c4df9b5 I.E...... R.....ID 0,0-0,0}
,02-23 11:45:47.645  9551  9601 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,02-23 11:45:47.645  3478  4277 D ISSUE_DEBUG: InputChannelName : ffe6ef2 com.test.thalitest/com.test.thalitest.MainActivity
,02-23 11:45:47.645  3478  3977 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
02-23 11:45:47.645  3478  3977 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
02-23 11:45:47.645  3478  3478 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,02-23 11:45:47.645  3478  3478 I KnoxTimeoutHandler: Shared devices show user statefalse
,02-23 11:45:47.655  9551  9551 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10074, CallingPid : 9551
,02-23 11:45:47.655  3478  4414 D ConnectivityService: listenForNetwork for Listen from uid/pid:10074/9551 for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
02-23 11:45:47.655  9551  9566 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,02-23 11:45:47.655  3478  3862 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,02-23 11:45:47.655  3478  3862 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -50]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
02-23 11:45:47.655  3478  3862 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
02-23 11:45:47.655  3478  3851 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: true, uidstate: 6, mProxSensorScreenOff: false
02-23 11:45:47.655  3478  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
02-23 11:45:47.665  3478  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
02-23 11:45:47.665  9551  9551 D SecWifiDisplayUtil: Metadata value : SecSettings2
02-23 11:45:47.665  3478  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
02-23 11:45:47.665  3478  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
02-23 11:45:47.665  3478  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
02-23 11:45:47.675  3008  3008 I SurfaceFlinger: id=19 createSurf (1x1),1 flag=404, NainActivit
02-23 11:45:47.675  3478  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
02-23 11:45:47.675  3478  3862 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,02-23 11:45:47.685  3478  4414 D InputDispatcher: Focus entered window: 9551
,02-23 11:45:47.685  3478  3579 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3478 uid:1000
02-23 11:45:47.685  3478  3579 D PointerIcon: setMouseCustomIcon IconType is same.101
02-23 11:45:47.685  9551  9601 D libEGL  : eglInitialize EGLDisplay = 0xdc3f97c4
02-23 11:45:47.685  9551  9601 I OpenGLRenderer: Initialized EGL, version 1.4
,02-23 11:45:47.695  9551  9601 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,02-23 11:45:47.695  9551  9551 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,02-23 11:45:47.715  9551  9605 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
02-23 11:45:47.715  9551  9605 D libEGL  : eglInitialize EGLDisplay = 0xd982c3e4
,02-23 11:45:47.715  9551  9605 D libGLESv2: DTS_GLAPI : DTS is not allowed for Package : com.test.thalitest
,02-23 11:45:47.735  3478  4862 V WindowStateAnimator: Finishing drawing window Window{ffe6ef2 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,02-23 11:45:47.735  9551  9551 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
02-23 11:45:47.735  3008  3008 D libEGL  : eglInitialize EGLDisplay = 0x7fc150a738
,02-23 11:45:47.735  3478  4384 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,02-23 11:45:47.735  3478  3579 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
02-23 11:45:47.735  3478  3478 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,02-23 11:45:47.735  3478  3579 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +595ms
02-23 11:45:47.735  3478  3579 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3478  tag : ACTIVITY_RESUME_BOOSTER@3
,02-23 11:45:47.735  3478  3478 I KnoxTimeoutHandler: SD activityfalse
02-23 11:45:47.735  3478  3579 D ActivityManager: mDVFSHelper.release()
02-23 11:45:47.735  3478  3579 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1ec6e56 u0 com.test.thalitest/.MainActivity t5} time:173449
02-23 11:45:47.735  3478  3553 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3478  pkgName : ACTIVITY_RESUME_BOOSTER@9
,02-23 11:45:47.745  3478  3579 D ViewRootImpl: #3 mView = null
,02-23 11:45:47.745  4818  4818 D SamsungIME: IMPL finishInput
02-23 11:45:47.745  4818  4818 D SamsungIME: SwiftKeyWrapper writeDBdataToFileOnFinishInput
02-23 11:45:47.745  4818  4818 D SamsungIME: saveAndClear +
02-23 11:45:47.745  4818  4818 D SamsungIME: saveAndClear -
,02-23 11:45:47.755  3478  3968 V WindowStateAnimator: Finishing drawing window Window{ffe6ef2 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
,02-23 11:45:47.755  9551  9551 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
,02-23 11:45:47.755  9551  9551 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9551
,02-23 11:45:47.765  9551  9551 D cr_Ime  : [InputMethodManagerWrapper.java:59] isActive: true
02-23 11:45:47.765  9551  9551 D cr_Ime  : [InputMethodManagerWrapper.java:68] hideSoftInputFromWindow
,02-23 11:45:47.765  9551  9551 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@30d771d time:173471
,02-23 11:45:47.765  6447  6447 V ActivityThread: updateVisibility : ActivityRecord{29ae281 token=android.os.BinderProxy@80b0ffb {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
,02-23 11:45:47.765  3008  3008 D libEGL  : eglInitialize EGLDisplay = 0x7fc150a738
,02-23 11:45:47.785  3008  3008 D libEGL  : eglInitialize EGLDisplay = 0x7fc150a738
,02-23 11:45:47.815  9551  9551 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,02-23 11:45:47.905  3478  4277 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,02-23 11:45:47.905  3478  4277 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4269, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
02-23 11:45:47.905  3478  4277 D BatteryService: online:4, current avg:62, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-429
02-23 11:45:47.905  3478  3478 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,02-23 11:45:47.915  3478  3478 I MotionRecognitionService: Plugged
02-23 11:45:47.915  3478  3478 D MotionRecognitionService:   cableConnection= 1
02-23 11:45:47.915  3478  3478 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
02-23 11:45:47.915  3478  3478 D MotionRecognitionService: skip setTransmitPower. 
,02-23 11:45:47.915  3478  3856 D WifiController: ApOrStaEnabledState  msg.what= 155652
,02-23 11:45:47.915  3942  3942 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
02-23 11:45:47.915  3942  3942 D KeyguardUpdateMonitor: handleBatteryUpdate
,02-23 11:45:47.915  3942  3942 D PowerUI : priorPlugType = 2 mPlugType =  2
,02-23 11:45:47.915  3942  3942 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
02-23 11:45:47.915  3942  3942 D PowerUI.Notification: There is no change about charging status, so return!
,02-23 11:45:47.915  3942  3942 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:45:47.925  5295  5295 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,02-23 11:45:47.925  5328  5328 D CommonServiceConfiguration: getStringValueSetting
,02-23 11:45:47.925  5295  5604 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,02-23 11:45:47.925  3942  3942 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:45:47.925  5328  5328 D BatteryMonitor: new battery level: 100
,02-23 11:45:47.935  3008  3070 I SurfaceFlinger: id=18 Removed uhalitest (7/11)
,02-23 11:45:47.935  3008  4456 I SurfaceFlinger: id=18 Removed uhalitest (-2/11)
,02-23 11:45:47.955  3008  3008 D libEGL  : eglTerminate EGLDisplay = 0x7fc150a858
,02-23 11:45:47.975  9551  9616 D jxcore_app_log: JniHelper::setJavaVM(0xf48b4000), pthread_self() = -708576976
,02-23 11:45:47.975  9551  9616 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
02-23 11:45:47.975  9551  9616 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
02-23 11:45:47.975  9551  9616 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
02-23 11:45:47.975  9551  9616 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
02-23 11:45:47.975  9551  9616 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
02-23 11:45:47.975  9551  9616 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9330e1c added. We now have 1 listener(s)
,02-23 11:45:47.985  9551  9616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9330e1c added. We now have 1 listener(s)
02-23 11:45:47.985  9551  9616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
02-23 11:45:47.985  9551  9616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
02-23 11:45:47.985  9551  9616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
02-23 11:45:47.985  9551  9616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: null
02-23 11:45:47.985  9551  9616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
02-23 11:45:47.985  9551  9616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
02-23 11:45:47.985  9551  9616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
02-23 11:45:47.985  9551  9616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
02-23 11:45:47.985  9551  9616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 256
02-23 11:45:47.985  9551  9616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
02-23 11:45:47.985  9551  9616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
02-23 11:45:47.985  9551  9616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
02-23 11:45:47.985  9551  9616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
02-23 11:45:47.985  9551  9616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,02-23 11:45:47.985  9551  9616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 44:78:3E:94:4A:3E
,02-23 11:45:47.985  9551  9616 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: ", Bluetooth MAC address: "44:78:3E:94:4A:3E"Peer extra info: "256
,02-23 11:45:47.985  9551  9616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
02-23 11:45:47.985  9551  9616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: null
,02-23 11:45:47.985  9551  9616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
02-23 11:45:47.985  9551  9616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a25b1ab added. We now have 2 listener(s)
02-23 11:45:47.985  9551  9616 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,02-23 11:45:47.985  9551  9616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
02-23 11:45:47.985  9551  9616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 37329
,02-23 11:45:47.985  9551  9616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,7,main], id: 142
02-23 11:45:47.985  9551  9616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
02-23 11:45:47.985  9551  9616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
02-23 11:45:47.985  9551  9616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
02-23 11:45:47.985  9551  9616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,7,main], id: 142
,02-23 11:45:47.985  9551  9616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
02-23 11:45:47.985  9551  9616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 44:78:3E:94:4A:3E
,02-23 11:45:47.995  9551  9616 D BluetoothAdapter: STATE_ON
,02-23 11:45:47.995  9551  9616 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,02-23 11:45:47.995  9551  9616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
02-23 11:45:47.995  9551  9616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
02-23 11:45:47.995  9551  9616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
02-23 11:45:47.995  9551  9616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
02-23 11:45:47.995  9551  9616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
02-23 11:45:47.995  9551  9616 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
02-23 11:45:47.995  9551  9616 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
02-23 11:45:47.995  9551  9616 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
02-23 11:45:47.995  9551  9616 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
02-23 11:45:47.995  9551  9616 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
02-23 11:45:47.995  9551  9616 D io.jxcore.node.ConnectivityMonitor: start: OK
,02-23 11:45:47.995  9551  9616 I io.jxcore.node.LifeCycleMonitor: start: OK
,02-23 11:45:48.005  9551  9551 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,02-23 11:45:48.015  9551  9551 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,02-23 11:45:48.025  9551  9551 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,02-23 11:45:48.025  3478  3875 D MdnieScenarioControlService:  packageName : com.test.thalitest    className : com.test.thalitest.MainActivity
,02-23 11:45:48.025  9551  9551 D SystemWebChromeClient: file:///android_asset/www/js/index.js: Line 36 : Uncaught TypeError: Cannot read property 'querySelector' of null
02-23 11:45:48.025  9551  9551 I chromium: [INFO:CONSOLE(36)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (36)
,02-23 11:45:48.025  9551  9551 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,02-23 11:45:48.045  3478  3478 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3478  tag : ACTIVITY_RESUME_BOOSTER@9
,02-23 11:45:48.125  3478  3875 I MdnieScenarioControlService: mGameModeLauncher : false
,02-23 11:45:48.125  3478  3875 I MdnieScenarioControlService: setUIMode
,02-23 11:45:48.175  4020  4020 D Recents : onTaskStackChanged
,02-23 11:45:48.175  4020  4020 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.test.thalitest
,02-23 11:45:48.195  4020  4020 D ResourcesManager: For user 0 new overlays fetched Null
,02-23 11:45:48.195  3478  6372 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
,02-23 11:45:48.435  9551  9617 W jxcore-log: Initializing JXcore engine
02-23 11:45:48.435  9551  9617 W jxcore-log: JXcore engine is ready
,02-23 11:45:48.455  5301  5301 E audit   : type=1400 msg=audit(1487846748.455:264): avc:  denied  { ioctl } for  pid=9617 comm="Thread-143" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3089 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
02-23 11:45:48.455  5301  5301 E audit   :  SEPF_SECMOBILE_6.0.1_0031
02-23 11:45:48.455  5301  5301 E audit   : type=1300 msg=audit(1487846748.455:264): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=8 a1=5451 a2=2 a3=d48bd3c8 items=0 ppid=3181 pid=9617 auid=4294967295 uid=10074 gid=10074 euid=10074 suid=10074 fsuid=10074 egid=10074 sgid=10074 fsgid=10074 tty=(none) ses=4294967295 comm="Thread-143" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
02-23 11:45:48.455  5301  5301 E audit   : type=1327 msg=audit(1487846748.455:264): proctitle="com.test.thalitest"
02-23 11:45:48.455  5301  5301 E audit   : type=1320 msg=audit(1487846748.455:264): 
,02-23 11:45:48.455  5301  5301 E audit   : type=1400 msg=audit(1487846748.455:265): avc:  denied  { ioctl } for  pid=9617 comm="Thread-143" path="socket:[35199]" dev="sockfs" ino=35199 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
02-23 11:45:48.455  5301  5301 E audit   :  SEPF_SECMOBILE_6.0.1_0031
02-23 11:45:48.455  5301  5301 E audit   : type=1300 msg=audit(1487846748.455:265): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=33 a1=5451 a2=2 a3=d48bd3c8 items=0 ppid=3181 pid=9617 auid=4294967295 uid=10074 gid=10074 euid=10074 suid=10074 fsuid=10074 egid=10074 sgid=10074 fsgid=10074 tty=(none) ses=4294967295 comm="Thread-143" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
02-23 11:45:48.455  5301  5301 E audit   : type=1327 msg=audit(1487846748.455:265): proctitle="com.test.thalitest"
02-23 11:45:48.455  5301  5301 E audit   : type=1320 msg=audit(1487846748.455:265): 
,02-23 11:45:48.455  9551  9617 W jxcore-log: Starting JXcore engine
,02-23 11:45:48.495  9551  9617 W jxcore-log: Platform android
02-23 11:45:48.495  9551  9617 W jxcore-log: 
02-23 11:45:48.495  9551  9617 W jxcore-log: Process ARCH arm
02-23 11:45:48.495  9551  9617 W jxcore-log: 
,02-23 11:45:48.625  9551  9617 I jxcore-log: JXcore Cordova bridge is ready!
02-23 11:45:48.625  9551  9617 I jxcore-log: 
02-23 11:45:48.625  9551  9617 W jxcore-log: JXcore engine is started
,02-23 11:45:48.625  9551  9616 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,02-23 11:45:48.625  9551  9551 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 41 : Application has the required permission.
02-23 11:45:48.625  9551  9551 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,02-23 11:45:50.125  3478  3900 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/5_task.xml.bak
,02-23 11:45:50.205  3478  6371 D GameManagerService: identifyGamePackage. com.test.thalitest
,02-23 11:45:51.695  3478  6371 D SSRM:n  : SIOP:: AP = 370, PST = 321 (W:6), CP = 277, CUR = 62, LCD = 99
,02-23 11:45:51.715  3478  6371 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,02-23 11:45:53.245  3478  6371 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,02-23 11:45:55.585  9551  9617 I jxcore-log: 2017-02-23 10:45:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
02-23 11:45:55.585  9551  9617 I jxcore-log: 
,02-23 11:45:55.585  9551  9617 I jxcore-log: 2017-02-23 10:45:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
02-23 11:45:55.585  9551  9617 I jxcore-log: 
02-23 11:45:55.585  9551  9617 I jxcore-log: 2017-02-23 10:45:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
02-23 11:45:55.585  9551  9617 I jxcore-log: 
,02-23 11:45:55.595  9551  9617 D BluetoothAdapter: STATE_ON
,02-23 11:45:55.595  9551  9617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
02-23 11:45:55.595  9551  9617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
02-23 11:45:55.595  9551  9617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
02-23 11:45:55.595  9551  9617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
02-23 11:45:55.595  9551  9617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
02-23 11:45:55.595  9551  9617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
02-23 11:45:55.595  9551  9617 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
02-23 11:45:55.595  9551  9617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
02-23 11:45:55.595  9551  9617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,02-23 11:45:55.605  9551  9617 D BluetoothAdapter: STATE_ON
,02-23 11:45:55.605  9551  9617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,02-23 11:45:55.605  9551  9617 I jxcore-log: 2017-02-23 10:45:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
02-23 11:45:55.605  9551  9617 I jxcore-log: 
,02-23 11:45:55.605  9551  9617 I jxcore-log: 2017-02-23 10:45:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
02-23 11:45:55.605  9551  9617 I jxcore-log: 
02-23 11:45:55.605  9551  9617 I jxcore-log: 2017-02-23 10:45:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
02-23 11:45:55.605  9551  9617 I jxcore-log: 
,02-23 11:45:55.865  9551  9617 D ExecuteNativeTests: Running unit tests
,02-23 11:45:55.865  9551  9617 D BluetoothAdapter: enable()
,02-23 11:45:55.875  9551  9617 D BluetoothAdapter: enable(): BT is already enabled..!
,02-23 11:45:55.885  3478  3553 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cac78a2 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a92095e 5321:com.samsung.android.providers.context/u0a7}
,02-23 11:45:55.885  9551  9617 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,02-23 11:45:55.895  3478  4278 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,02-23 11:45:55.895  3478  4278 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,02-23 11:45:55.895  3478  4278 D WifiService: setWifiEnabled: true pid=9551, uid=10074
,02-23 11:45:55.895  3478  4278 W ActivityManager: Permission Denial: getCurrentUser() from pid=9551, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
,02-23 11:45:55.905  3478  3853 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,02-23 11:45:55.905  3478  4278 W WifiService: Failed getting userId using ActivityManagerNative
02-23 11:45:55.905  3478  4278 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9551, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
02-23 11:45:55.905  3478  4278 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
02-23 11:45:55.905  3478  4278 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
02-23 11:45:55.905  3478  4278 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
02-23 11:45:55.905  3478  4278 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
02-23 11:45:55.905  3478  4278 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
02-23 11:45:55.905  3478  3853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
02-23 11:45:55.905  3478  4278 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
,02-23 11:45:55.905  3478  4278 D SettingsProvider: isChangeAllowed() : name = wifi_on
02-23 11:45:55.905  3478  3856 D WifiStateMachine: setFccChannel: channel = 0
02-23 11:45:55.905  3478  3856 D WifiController: [FCC]setFccChannel() is called !!!
,02-23 11:45:55.905  3478  3853 D WifiBigDataLog: init : 
02-23 11:45:55.905  3478  3856 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
,02-23 11:45:55.905  3478  3853 D WifiStateMachine: setFccChannelNative: channel = 0
,02-23 11:45:55.905  3478  3853 D WifiNative-wlan0: callSECApiInt - ID [230]
,02-23 11:45:55.915  3478  3553 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{17ce933 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a92095e 5321:com.samsung.android.providers.context/u0a7}
,02-23 11:45:57.185  3478  3604 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,02-23 11:45:57.205  3478  3604 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,02-23 11:45:57.975  3478  4862 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,02-23 11:45:57.975  3478  4862 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4311, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
02-23 11:45:57.975  3478  4862 D BatteryService: online:4, current avg:-199, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:160
02-23 11:45:57.975  3478  3478 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,02-23 11:45:57.975  3478  3478 I MotionRecognitionService: Plugged
,02-23 11:45:57.975  3478  3478 D MotionRecognitionService:   cableConnection= 1
02-23 11:45:57.975  3478  3478 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
02-23 11:45:57.975  3478  3478 D MotionRecognitionService: skip setTransmitPower. 
,02-23 11:45:57.985  3478  3856 D WifiController: ApOrStaEnabledState  msg.what= 155652
,02-23 11:45:57.985  3942  3942 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
02-23 11:45:57.985  3942  3942 D KeyguardUpdateMonitor: handleBatteryUpdate
,02-23 11:45:57.985  3942  3942 D PowerUI : priorPlugType = 2 mPlugType =  2
,02-23 11:45:57.995  3942  3942 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,02-23 11:45:57.995  3942  3942 D PowerUI.Notification: There is no change about charging status, so return!
,02-23 11:45:58.005  3942  3942 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:45:58.005  5328  5328 D CommonServiceConfiguration: getStringValueSetting
,02-23 11:45:58.015  5295  5295 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,02-23 11:45:58.015  5295  5604 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,02-23 11:45:58.025  3942  3942 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:45:58.025  5328  5328 D BatteryMonitor: new battery level: 100
,02-23 11:45:59.985  3478  3810 V AlarmManager: Expired Alarm result :8
,02-23 11:45:59.995  3942  3942 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,02-23 11:45:59.995  3942  3942 D KeyguardUpdateMonitor: handleTimeUpdate
,02-23 11:46:00.015  3942  3942 D Clock   : received broadcast android.intent.action.TIME_TICK
,02-23 11:46:00.065  3942  3942 D DateView: received broadcast android.intent.action.TIME_TICK
,02-23 11:46:00.085  4746  4746 D [Weather Widget]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,02-23 11:46:00.085  4746  4746 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EEFA9050249635C043F7E254E316C2550]}
02-23 11:46:00.095  4746  4746 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EAB01DC5C99149A39F887E17599325AFBFF089086AA9902184ADA25758C536FE2]}
02-23 11:46:00.095  4746  4746 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EFF0B905BDFF72B69FB632A6CB072B41F95D2E6F4F84443284E97F40042D431D8350388453A923ABD8469D82798FA7548]}
02-23 11:46:00.095  4746  4746 D [Weather Widget]  : {[A1AF0F6A1A65A89C43D705938923D0FEFB71880C4E84718DA0A3E1F383E54FB27A4284D9BEDF7BAA2ABFFE671EB65C640578FF9DE16A23BFE3280A9DCDBB09A0608352BBBA44ED61A9FF53156343D2423B8D5D1650C9F395597052A680A2D99E34862742E5D4BBA906D2B32986C91FA5]}
02-23 11:46:00.095  4746  4746 D [Weather Widget]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,02-23 11:46:01.735  3478  6371 D SSRM:n  : SIOP:: AP = 360, PST = 328 (W:6), CP = 288, CUR = -199, LCD = 99
,02-23 11:46:01.755  3478  6371 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,02-23 11:46:05.915  9551  9617 I com.test.thalitest.ThaliTestRunner: Running UT
,02-23 11:46:06.045  9551  9617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
02-23 11:46:06.045  9551  9617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5467d5e added. We now have 2 listener(s)
02-23 11:46:06.045  9551  9617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5467d5e added. We now have 3 listener(s)
02-23 11:46:06.045  9551  9617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,02-23 11:46:06.045  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: ", Bluetooth MAC address: "44:78:3E:94:4A:3E"Peer extra info: "256
02-23 11:46:06.045  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
02-23 11:46:06.045  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: null
02-23 11:46:06.045  9551  9617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
02-23 11:46:06.045  9551  9617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dea353f added. We now have 4 listener(s)
02-23 11:46:06.045  9551  9617 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,02-23 11:46:06.045  9551  9617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,02-23 11:46:06.055  9551  9617 D BluetoothAdapter: STATE_ON
,02-23 11:46:06.055  9551  9617 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
02-23 11:46:06.055  9551  9617 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
02-23 11:46:06.055  9551  9617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
02-23 11:46:06.055  9551  9617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,02-23 11:46:06.055  9551  9617 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [00:11:22:33:44:55] timed out
02-23 11:46:06.055  9551  9617 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
02-23 11:46:06.055  9551  9617 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,02-23 11:46:06.055  9551  9617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
02-23 11:46:06.055  9551  9617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
02-23 11:46:06.055  9551  9617 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
02-23 11:46:06.055  9551  9617 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,02-23 11:46:06.065  9551  9617 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
,02-23 11:46:06.065  9551  9617 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
02-23 11:46:06.065  9551  9617 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,02-23 11:46:06.065  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,02-23 11:46:06.075  9551  9617 D BluetoothAdapter: STATE_ON
,02-23 11:46:06.075  9551  9617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
02-23 11:46:06.075  9551  9617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
02-23 11:46:06.075  9551  9617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
02-23 11:46:06.075  9551  9617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
02-23 11:46:06.075  9551  9617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
02-23 11:46:06.075  9551  9617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
02-23 11:46:06.075  9551  9617 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
02-23 11:46:06.075  9551  9617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
02-23 11:46:06.075  9551  9617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,02-23 11:46:06.075  9551  9617 D io.jxcore.node.ConnectivityMonitor: start: OK
02-23 11:46:06.075  9551  9617 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 0
02-23 11:46:06.075  9551  9617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 256 -> 0
02-23 11:46:06.075  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,02-23 11:46:06.085  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":0,"address":"44:78:3E:94:4A:3E"}
02-23 11:46:06.085  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":0,"address":"44:78:3E:94:4A:3E"}
02-23 11:46:06.085  9551  9617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:06.085  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,02-23 11:46:06.085  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":0,"address":"44:78:3E:94:4A:3E"}
02-23 11:46:06.085  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":0,"address":"44:78:3E:94:4A:3E"}
02-23 11:46:06.085  9551  9617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:06.085  9551  9617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
02-23 11:46:06.085  9551  9617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
02-23 11:46:06.085  9551  9617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
02-23 11:46:06.085  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,02-23 11:46:06.085  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,02-23 11:46:06.085  9551  9617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,02-23 11:46:06.085  9551  9617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
02-23 11:46:06.085  9551  9617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,02-23 11:46:06.085  9551  9617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
02-23 11:46:06.085  9551  9617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
02-23 11:46:06.085  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
02-23 11:46:06.085  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
02-23 11:46:06.085  9551  9551 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,02-23 11:46:06.085  9551  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,02-23 11:46:06.095  9551  9623 D BluetoothSocket: bindListen(): myUserId = 0
02-23 11:46:06.095  9551  9623 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,02-23 11:46:06.095  9551  9617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,02-23 11:46:06.095  9551  9617 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
02-23 11:46:06.095  9551  9617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,02-23 11:46:06.095  9551  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
,02-23 11:46:06.095  9551  9623 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@c79116a, port: 6, type: 1, local socket address: null, socket type: 0
02-23 11:46:06.105  9551  9617 D BluetoothAdapter: STATE_ON
,02-23 11:46:06.105  9551  9617 D BluetoothAdapter: STATE_ON
,02-23 11:46:06.105  9551  9617 D BluetoothAdapter: STATE_ON
,02-23 11:46:06.105  9551  9551 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,02-23 11:46:06.115  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-143,7,main], id: 143
,02-23 11:46:06.115  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
02-23 11:46:06.115  9551  9551 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
02-23 11:46:06.115  9551  9551 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,02-23 11:46:06.115  9551  9617 D BluetoothAdapter: STATE_ON
,02-23 11:46:06.115  9551  9617 D BluetoothAdapter: STATE_ON
02-23 11:46:06.115  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
02-23 11:46:06.115  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
02-23 11:46:06.115  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 0
,02-23 11:46:06.115  9551  9617 D BluetoothAdapter: STATE_ON
,02-23 11:46:06.125  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:06.125  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-143,7,main], id: 143
,02-23 11:46:06.125  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
02-23 11:46:06.125  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
02-23 11:46:06.125  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "6ad45288-6074-487c-b683-03a4a8e47a45", Bluetooth MAC address: "44:78:3E:94:4A:3E"
02-23 11:46:06.125  9551  9617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 44 78 3E 94 4A 3E
,02-23 11:46:06.125  9551  9617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[6ad45288-6074-487c-b683-03a4a8e47a45], mManufacturerSpecificData={}, mServiceData={6ad45288-6074-487c-b683-03a4a8e47a45=[0, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,02-23 11:46:06.125  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[6ad45288-6074-487c-b683-03a4a8e47a45], mManufacturerSpecificData={}, mServiceData={6ad45288-6074-487c-b683-03a4a8e47a45=[0, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
02-23 11:46:06.125  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:06.125  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[6ad45288-6074-487c-b683-03a4a8e47a45], mManufacturerSpecificData={}, mServiceData={6ad45288-6074-487c-b683-03a4a8e47a45=[0, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:06.125  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
02-23 11:46:06.125  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[6ad45288-6074-487c-b683-03a4a8e47a45], mManufacturerSpecificData={}, mServiceData={6ad45288-6074-487c-b683-03a4a8e47a45=[0, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
02-23 11:46:06.125  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:06.125  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:06.125  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[6ad45288-6074-487c-b683-03a4a8e47a45], mManufacturerSpecificData={}, mServiceData={6ad45288-6074-487c-b683-03a4a8e47a45=[0, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:06.125  9551  9617 D BluetoothAdapter: STATE_ON
,02-23 11:46:06.125  9551  9617 D BluetoothAdapter: STATE_ON
02-23 11:46:06.125  9551  9617 D BluetoothLeAdvertiser: start advertising
,02-23 11:46:06.125  9551  9617 D BluetoothAdapter: STATE_ON
,02-23 11:46:06.135  5295  5603 D BtGatt.GattService: registerClient() - UUID=0532f901-da27-46db-8da6-dd0f0eeab855
,02-23 11:46:06.185  5295  5373 D BtGatt.GattService: onClientRegistered() - UUID=0532f901-da27-46db-8da6-dd0f0eeab855, clientIf=7
,02-23 11:46:06.195  9551  9610 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,02-23 11:46:06.195  5295  5311 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,02-23 11:46:06.205  5295  5311 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,02-23 11:46:06.205  5295  5311 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
02-23 11:46:06.205  5295  5450 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_ADV
02-23 11:46:06.205  5295  5427 D BtGatt.AdvertiseManager: message : 0
,02-23 11:46:06.205  5295  5450 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 16, currDate: 23
,02-23 11:46:06.205  5295  5427 D BtGatt.AdvertiseManager: number of adv instance running = 0
02-23 11:46:06.205  5295  5427 D BtGatt.AdvertiseManager: size of list is =0
,02-23 11:46:06.215  5295  5427 D BtGatt.AdvertiseManager: starting advertising
,02-23 11:46:06.225  5295  5427 D BtGatt.AdvertiseManager: isStandardAdv = false
,02-23 11:46:06.225  5295  5450 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.test.thalitest@LowLatency : 24797446
02-23 11:46:06.225  5295  5450 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.test.thalitest@LowLatency : 2
,02-23 11:46:06.225  5295  5450 D BtGatt.GattService: [GSIM LOG]: reportData
02-23 11:46:06.225  5295  5450 D BtGatt.GattService: [GSIM LOG]: reportData, LAT: com.test.thalitest@LowLatency
,02-23 11:46:06.225  5295  5450 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.test.thalitest@LowLatency : 24797446
,02-23 11:46:06.225  3478  4167 V AlarmManager:  remove PendingIntent] PendingIntent{b624bab: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
,02-23 11:46:06.235  5295  5373 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,02-23 11:46:06.245  5295  5427 D BtGatt.AdvertiseManager: starting multi advertising
02-23 11:46:06.245  3478  3977 V AlarmManager:  remove PendingIntent] PendingIntent{d2a8208: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
,02-23 11:46:06.245  5295  5373 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,02-23 11:46:06.245  5295  5427 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,02-23 11:46:06.245  5295  5427 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
02-23 11:46:06.245  5295  5427 D BtGatt.AdvertiseManager: postCallback clientIf = 7 status = 0
02-23 11:46:06.245  5295  5427 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=7, status=0, isStart=true
,02-23 11:46:06.245  9551  9561 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
02-23 11:46:06.245  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-143,7,main], id: 143
,02-23 11:46:06.255  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:06.255  3478  4384 V AlarmManager:  remove PendingIntent] PendingIntent{8e7fda1: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
02-23 11:46:06.255  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
02-23 11:46:06.255  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:06.255  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-143,7,main], id: 143
,02-23 11:46:06.255  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:06.255  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:06.255  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:06.255  9551  9617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,02-23 11:46:06.255  9551  9617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,02-23 11:46:06.255  9551  9617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:06.255  5295  5450 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.test.thalitest : 1
,02-23 11:46:06.255  5295  5450 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
02-23 11:46:06.255  5295  5450 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
,02-23 11:46:06.255  9551  9617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:06.255  3478  4167 V AlarmManager:  remove PendingIntent] PendingIntent{5943bc6: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
,02-23 11:46:06.255  9551  9617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:06.255  9551  9617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-143,7,main], id: 143
,02-23 11:46:06.265  9551  9617 I io.jxcore.node.ConnectionHelper: start: OK
02-23 11:46:06.265  9551  9551 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,02-23 11:46:06.265  9551  9551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
02-23 11:46:06.265  9551  9551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
02-23 11:46:06.265  9551  9551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
02-23 11:46:06.265  9551  9551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
02-23 11:46:06.265  9551  9551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
,02-23 11:46:06.265  9551  9551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
02-23 11:46:06.265  3478  3968 V AlarmManager:  remove PendingIntent] PendingIntent{b77f787: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
02-23 11:46:06.265  9551  9551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,02-23 11:46:06.265  9551  9551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
02-23 11:46:06.265  9551  9551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,02-23 11:46:06.265  9551  9551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
02-23 11:46:06.265  9551  9551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
02-23 11:46:06.265  9551  9551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,02-23 11:46:06.265  9551  9551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
,02-23 11:46:06.265  9551  9551 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
02-23 11:46:06.275  3478  3499 V AlarmManager:  remove PendingIntent] PendingIntent{8e9b6b4: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
02-23 11:46:06.275  9551  9551 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
02-23 11:46:06.275  9551  9551 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
02-23 11:46:06.275  9551  9551 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
02-23 11:46:06.275  9551  9551 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
02-23 11:46:06.275  9551  9551 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,02-23 11:46:06.275  3478  3969 V AlarmManager:  remove PendingIntent] PendingIntent{465d2dd: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
,02-23 11:46:06.515  3478  6391 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,02-23 11:46:06.765  9551  9625 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,02-23 11:46:06.765  9551  9617 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
02-23 11:46:06.765  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [00:11:22:33:44:55]
02-23 11:46:06.765  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [10:010:010:010:010:010]
02-23 11:46:06.765  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [11:110:110:110:110:110]
02-23 11:46:06.765  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [12:210:210:210:210:210]
02-23 11:46:06.765  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [13:310:310:310:310:310]
02-23 11:46:06.765  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [14:410:410:410:410:410]
02-23 11:46:06.765  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [15:510:510:510:510:510]
02-23 11:46:06.765  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [16:610:610:610:610:610]
02-23 11:46:06.765  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [17:710:710:710:710:710]
02-23 11:46:06.765  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [18:810:810:810:810:810]
02-23 11:46:06.765  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [19:910:910:910:910:910]
02-23 11:46:06.765  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [20:1010:1010:1010:1010:1010]
02-23 11:46:06.765  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [21:1110:1110:1110:1110:1110]
02-23 11:46:06.765  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [22:1210:1210:1210:1210:1210]
02-23 11:46:06.765  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [23:1310:1310:1310:1310:1310]
02-23 11:46:06.765  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [24:1410:1410:1410:1410:1410]
02-23 11:46:06.765  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [25:1510:1510:1510:1510:1510]
02-23 11:46:06.765  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [26:1610:1610:1610:1610:1610]
02-23 11:46:06.765  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [27:1710:1710:1710:1710:1710]
02-23 11:46:06.775  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [28:1810:1810:1810:1810:1810]
02-23 11:46:06.775  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [29:1910:1910:1910:1910:1910]
02-23 11:46:06.775  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [30:2010:2010:2010:2010:2010]
02-23 11:46:06.775  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [31:2110:2110:2110:2110:2110]
02-23 11:46:06.775  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [32:2210:2210:2210:2210:2210]
02-23 11:46:06.775  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [33:2310:2310:2310:2310:2310]
02-23 11:46:06.775  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [34:2410:2410:2410:2410:2410]
02-23 11:46:06.775  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [35:2510:2510:2510:2510:2510]
02-23 11:46:06.775  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [36:2610:2610:2610:2610:2610]
02-23 11:46:06.775  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [37:2,710:2710:2710:2710:2710]
02-23 11:46:06.775  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [38:2810:2810:2810:2810:2810]
02-23 11:46:06.775  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [39:2910:2910:2910:2910:2910]
02-23 11:46:06.775  9551  9617 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
02-23 11:46:06.775  9551  9617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
02-23 11:46:06.775  9551  9617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
02-23 11:46:06.775  9551  9617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
02-23 11:46:06.775  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
02-23 11:46:06.775  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
02-23 11:46:06.775  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
02-23 11:46:06.775  9551  9617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
02-23 11:46:06.775  9551  9617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
02-23 11:46:06.775  9551  9623 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
02-23 11:46:06.775  9551  9617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
02-23 11:46:06.775  9551  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
02-23 11:46:06.775  9551  9623 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
02-23 11:46:06.775  9551  9617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
02-23 11:46:06.775  9551  9551 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
02-23 11:46:06.775  9551  9617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:06.775  9551  9617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
02-23 11:46:06.775  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
02-23 11:46:06.775  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:06.775  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:06.775  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:06.775  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:06.775  9551  9617 D BluetoothAdapter: STATE_ON
,02-23 11:46:06.785  9551  9617 D BluetoothAdapter: STATE_ON
,02-23 11:46:06.785  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,02-23 11:46:06.785  9551  9617 D BluetoothAdapter: STATE_ON
,02-23 11:46:06.795  9551  9617 D BluetoothAdapter: STATE_ON
,02-23 11:46:06.795  9551  9617 D BluetoothLeScanner: could not find callback wrapper
02-23 11:46:06.795  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
02-23 11:46:06.795  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:06.795  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:06.795  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-143,7,main], id: 143
,02-23 11:46:06.795  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
02-23 11:46:06.795  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-143,7,main], id: 143
,02-23 11:46:06.795  9551  9617 D BluetoothAdapter: STATE_ON
,02-23 11:46:06.795  9551  9617 D BluetoothAdapter: STATE_ON
,02-23 11:46:06.795  9551  9617 D BluetoothLeAdvertiser: stop advertising
,02-23 11:46:06.805  5295  5603 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,02-23 11:46:06.805  5295  5603 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
02-23 11:46:06.805  5295  5427 D BtGatt.AdvertiseManager: message : 1
,02-23 11:46:06.805  5295  5450 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_ADV
02-23 11:46:06.805  5295  5450 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 23, currDate: 23
02-23 11:46:06.815  5295  5450 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
,02-23 11:46:06.815  5295  5427 D BtGatt.AdvertiseManager: stop advertise for client =  7
02-23 11:46:06.815  5295  5450 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
02-23 11:46:06.815  5295  5427 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 7
,02-23 11:46:06.815  5295  5450 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
,02-23 11:46:06.815  5295  5427 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,02-23 11:46:06.815  3478  4277 V AlarmManager:  remove PendingIntent] PendingIntent{9884e52: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
,02-23 11:46:06.825  5295  5373 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
02-23 11:46:06.825  5295  5373 D BtGatt.GattService: Client app is not null!
,02-23 11:46:06.825  9551  9610 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,02-23 11:46:06.825  5295  5311 D BtGatt.GattService: unregisterClient() - clientIf=7
,02-23 11:46:06.825  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,02-23 11:46:06.825  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:06.825  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
02-23 11:46:06.825  3478  4416 V AlarmManager:  remove PendingIntent] PendingIntent{c528523: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
02-23 11:46:06.825  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:06.825  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-143,7,main], id: 143
,02-23 11:46:06.825  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:06.825  9551  9617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
02-23 11:46:06.825  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
02-23 11:46:06.835  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,02-23 11:46:06.835  9551  9617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-143,7,main], id: 143
,02-23 11:46:06.835  9551  9617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:06.835  9551  9617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
02-23 11:46:06.835  9551  9617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:06.835  9551  9617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:06.835  9551  9551 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
02-23 11:46:06.835  9551  9551 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
02-23 11:46:06.845  9551  9551 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
02-23 11:46:06.845  9551  9551 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
02-23 11:46:06.845  3478  3969 V AlarmManager:  remove PendingIntent] PendingIntent{fc58a20: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
02-23 11:46:06.845  9551  9551 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,02-23 11:46:06.845  9551  9551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
02-23 11:46:06.845  9551  9551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
02-23 11:46:06.845  9551  9551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
02-23 11:46:06.845  9551  9551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,02-23 11:46:06.845  9551  9551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
02-23 11:46:06.845  9551  9551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
02-23 11:46:06.845  9551  9551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
02-23 11:46:06.845  9551  9551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
02-23 11:46:06.845  9551  9551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
02-23 11:46:06.845  9551  9551 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
02-23 11:46:06.845  9551  9626 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
02-23 11:46:06.845  9551  9617 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
02-23 11:46:06.845  9551  9617 V io.jxcore.node.ConnectivityMonitor: start: Already started
02-23 11:46:06.845  9551  9617 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
02-23 11:46:06.845  9551  9617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
02-23 11:46:06.845  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,02-23 11:46:06.855  3478  4278 V AlarmManager:  remove PendingIntent] PendingIntent{bf1bfd9: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
,02-23 11:46:06.855  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":1,"address":"44:78:3E:94:4A:3E"}
,02-23 11:46:06.855  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":1,"address":"44:78:3E:94:4A:3E"}
02-23 11:46:06.855  9551  9617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-143,7,main], id: 143
,02-23 11:46:06.855  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
02-23 11:46:06.855  3478  3968 V AlarmManager:  remove PendingIntent] PendingIntent{938fd9e: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
,02-23 11:46:06.865  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":1,"address":"44:78:3E:94:4A:3E"}
,02-23 11:46:06.865  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":1,"address":"44:78:3E:94:4A:3E"}
02-23 11:46:06.865  9551  9617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:06.865  9551  9617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
02-23 11:46:06.865  3478  4414 V AlarmManager:  remove PendingIntent] PendingIntent{be507f: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
,02-23 11:46:06.865  9551  9617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
02-23 11:46:06.865  9551  9617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
02-23 11:46:06.865  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
02-23 11:46:06.865  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,02-23 11:46:06.865  9551  9617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
02-23 11:46:06.865  9551  9617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,02-23 11:46:06.865  9551  9617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
02-23 11:46:06.865  9551  9617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
02-23 11:46:06.865  9551  9617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
02-23 11:46:06.865  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,02-23 11:46:06.865  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
02-23 11:46:06.865  9551  9551 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,02-23 11:46:06.865  3478  3497 V AlarmManager:  remove PendingIntent] PendingIntent{1f1759b: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
02-23 11:46:06.865  9551  9627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,02-23 11:46:06.875  9551  9627 D BluetoothSocket: bindListen(): myUserId = 0
02-23 11:46:06.875  9551  9627 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,02-23 11:46:06.875  9551  9617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
02-23 11:46:06.875  9551  9617 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
02-23 11:46:06.875  9551  9617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
,02-23 11:46:06.875  9551  9627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
02-23 11:46:06.875  9551  9627 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@de412a4, port: 6, type: 1, local socket address: null, socket type: 0
02-23 11:46:06.875  3478  3969 V AlarmManager:  remove PendingIntent] PendingIntent{6867d38: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
,02-23 11:46:06.885  9551  9617 D BluetoothAdapter: STATE_ON
,02-23 11:46:06.885  9551  9617 D BluetoothAdapter: STATE_ON
,02-23 11:46:06.885  9551  9617 D BluetoothAdapter: STATE_ON
,02-23 11:46:06.885  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-143,7,main], id: 143
,02-23 11:46:06.885  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
02-23 11:46:06.885  9551  9617 D BluetoothAdapter: STATE_ON
,02-23 11:46:06.885  9551  9617 D BluetoothAdapter: STATE_ON
,02-23 11:46:06.885  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
02-23 11:46:06.885  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
02-23 11:46:06.885  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 1
,02-23 11:46:06.895  9551  9617 D BluetoothAdapter: STATE_ON
,02-23 11:46:06.895  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-143,7,main], id: 143
,02-23 11:46:06.895  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:06.895  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
02-23 11:46:06.895  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
02-23 11:46:06.895  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "6ad45288-6074-487c-b683-03a4a8e47a45", Bluetooth MAC address: "44:78:3E:94:4A:3E"
,02-23 11:46:06.895  9551  9617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 44 78 3E 94 4A 3E
02-23 11:46:06.895  9551  9617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[6ad45288-6074-487c-b683-03a4a8e47a45], mManufacturerSpecificData={}, mServiceData={6ad45288-6074-487c-b683-03a4a8e47a45=[1, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
02-23 11:46:06.895  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[6ad45288-6074-487c-b683-03a4a8e47a45], mManufacturerSpecificData={}, mServiceData={6ad45288-6074-487c-b683-03a4a8e47a45=[1, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
02-23 11:46:06.895  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:06.895  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[6ad45288-6074-487c-b683-03a4a8e47a45], mManufacturerSpecificData={}, mServiceData={6ad45288-6074-487c-b683-03a4a8e47a45=[1, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:06.895  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
02-23 11:46:06.895  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[6ad45288-6074-487c-b683-03a4a8e47a45], mManufacturerSpecificData={}, mServiceData={6ad45288-6074-487c-b683-03a4a8e47a45=[1, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
02-23 11:46:06.895  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:06.895  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-143,7,main], id: 143
,02-23 11:46:06.895  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[6ad45288-6074-487c-b683-03a4a8e47a45], mManufacturerSpecificData={}, mServiceData={6ad45288-6074-487c-b683-03a4a8e47a45=[1, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:06.895  9551  9617 D BluetoothAdapter: STATE_ON
,02-23 11:46:06.895  9551  9617 D BluetoothAdapter: STATE_ON
,02-23 11:46:06.895  9551  9617 D BluetoothLeAdvertiser: start advertising
,02-23 11:46:06.895  9551  9617 D BluetoothAdapter: STATE_ON
,02-23 11:46:06.905  5295  5307 D BtGatt.GattService: registerClient() - UUID=155707f1-80c9-4e3e-8713-0b43647f9826
,02-23 11:46:06.945  5295  5373 D BtGatt.GattService: onClientRegistered() - UUID=155707f1-80c9-4e3e-8713-0b43647f9826, clientIf=7
,02-23 11:46:06.945  9551  9562 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,02-23 11:46:06.945  5295  5311 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,02-23 11:46:06.955  5295  5311 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,02-23 11:46:06.955  5295  5311 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,02-23 11:46:06.955  5295  5427 D BtGatt.AdvertiseManager: message : 0
02-23 11:46:06.955  5295  5450 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_ADV
,02-23 11:46:06.955  5295  5450 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 23, currDate: 23
02-23 11:46:06.955  5295  5427 D BtGatt.AdvertiseManager: number of adv instance running = 0
02-23 11:46:06.955  5295  5427 D BtGatt.AdvertiseManager: size of list is =0
,02-23 11:46:06.955  5295  5427 D BtGatt.AdvertiseManager: starting advertising
,02-23 11:46:06.955  5295  5427 D BtGatt.AdvertiseManager: isStandardAdv = false
,02-23 11:46:06.965  3478  4416 V AlarmManager:  remove PendingIntent] PendingIntent{2ba9111: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
,02-23 11:46:06.965  5295  5450 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.test.thalitest : 2
02-23 11:46:06.965  5295  5450 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.test.thalitest@LowLatency : 24797446
02-23 11:46:06.965  5295  5450 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.test.thalitest@LowLatency : 2
02-23 11:46:06.965  5295  5450 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
02-23 11:46:06.965  5295  5450 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
,02-23 11:46:06.965  5295  5373 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,02-23 11:46:06.965  5295  5427 D BtGatt.AdvertiseManager: starting multi advertising
,02-23 11:46:06.965  5295  5373 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,02-23 11:46:06.965  5295  5427 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
02-23 11:46:06.965  5295  5427 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
02-23 11:46:06.965  5295  5427 D BtGatt.AdvertiseManager: postCallback clientIf = 7 status = 0
02-23 11:46:06.965  5295  5427 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=7, status=0, isStart=true
02-23 11:46:06.965  9551  9610 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
02-23 11:46:06.965  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-143,7,main], id: 143
,02-23 11:46:06.965  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:06.965  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
02-23 11:46:06.965  3478  4414 V AlarmManager:  remove PendingIntent] PendingIntent{5c92276: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
02-23 11:46:06.965  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:06.965  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:06.965  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:06.965  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:06.965  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-143,7,main], id: 143
,02-23 11:46:06.965  9551  9617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,02-23 11:46:06.965  9551  9617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
02-23 11:46:06.965  9551  9617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:06.965  9551  9617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: seems that updateState call different BlePeerDiscoverer
,02-23 11:46:06.975  9551  9617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:06.975  9551  9617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:06.975  3478  4303 V AlarmManager:  remove PendingIntent] PendingIntent{c67d077: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
02-23 11:46:06.975  9551  9617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-143,7,main], id: 143
,02-23 11:46:06.975  9551  9617 I io.jxcore.node.ConnectionHelper: start: OK
02-23 11:46:06.975  9551  9551 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
02-23 11:46:06.975  9551  9551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
02-23 11:46:06.975  9551  9551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
,02-23 11:46:06.975  9551  9551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
02-23 11:46:06.975  9551  9551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
02-23 11:46:06.975  9551  9551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
02-23 11:46:06.975  9551  9551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
02-23 11:46:06.975  9551  9551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
02-23 11:46:06.975  9551  9551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
02-23 11:46:06.975  9551  9551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
02-23 11:46:06.975  9551  9551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
02-23 11:46:06.975  9551  9551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
02-23 11:46:06.975  9551  9551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
02-23 11:46:06.975  9551  9551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
02-23 11:46:06.975  9551  9551 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,02-23 11:46:06.975  3478  4416 V AlarmManager:  remove PendingIntent] PendingIntent{cc234e4: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
,02-23 11:46:06.975  9551  9551 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,02-23 11:46:06.975  9551  9551 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
02-23 11:46:06.975  9551  9551 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
02-23 11:46:06.975  9551  9551 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
02-23 11:46:06.975  9551  9551 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,02-23 11:46:06.985  3478  3977 V AlarmManager:  remove PendingIntent] PendingIntent{7262d4d: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
,02-23 11:46:06.985  3478  4278 V AlarmManager:  remove PendingIntent] PendingIntent{39cf002: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
,02-23 11:46:06.985  3478  4435 V AlarmManager:  remove PendingIntent] PendingIntent{e7efd13: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
,02-23 11:46:06.995  3478  3969 V AlarmManager:  remove PendingIntent] PendingIntent{cdfbb50: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
,02-23 11:46:07.475  9551  9629 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,02-23 11:46:07.475  9551  9617 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
,02-23 11:46:07.475  9551  9617 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,02-23 11:46:07.475  9551  9617 V io.jxcore.node.ConnectivityMonitor: start: Already started
02-23 11:46:07.475  9551  9617 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
02-23 11:46:07.475  9551  9617 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
02-23 11:46:07.475  9551  9617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
,02-23 11:46:07.475  9551  9551 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
02-23 11:46:07.475  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,02-23 11:46:07.485  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":2,"address":"44:78:3E:94:4A:3E"}
,02-23 11:46:07.485  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":2,"address":"44:78:3E:94:4A:3E"}
02-23 11:46:07.485  9551  9617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:07.485  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,02-23 11:46:07.495  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":2,"address":"44:78:3E:94:4A:3E"}
,02-23 11:46:07.495  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":2,"address":"44:78:3E:94:4A:3E"}
02-23 11:46:07.495  9551  9617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-143,7,main], id: 143
,02-23 11:46:07.495  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
02-23 11:46:07.495  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 37329
02-23 11:46:07.495  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
02-23 11:46:07.495  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 2
02-23 11:46:07.495  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
02-23 11:46:07.495  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
02-23 11:46:07.495  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
02-23 11:46:07.495  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
02-23 11:46:07.495  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
02-23 11:46:07.495  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:07.495  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 2
02-23 11:46:07.495  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted true Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:07.495  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop advertiser Current thread: Thread[Thread-143,7,main], id: 143
,02-23 11:46:07.495  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:07.495  9551  9617 D BluetoothAdapter: STATE_ON
,02-23 11:46:07.505  9551  9617 D BluetoothAdapter: STATE_ON
,02-23 11:46:07.505  9551  9617 D BluetoothLeAdvertiser: stop advertising
,02-23 11:46:07.505  5295  5311 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
02-23 11:46:07.505  5295  5311 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
02-23 11:46:07.505  5295  5427 D BtGatt.AdvertiseManager: message : 1
,02-23 11:46:07.505  5295  5450 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_ADV
02-23 11:46:07.505  5295  5450 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 23, currDate: 23
02-23 11:46:07.505  5295  5450 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
02-23 11:46:07.505  5295  5450 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
02-23 11:46:07.505  5295  5450 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
,02-23 11:46:07.515  5295  5427 D BtGatt.AdvertiseManager: stop advertise for client =  7
02-23 11:46:07.515  5295  5427 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 7
,02-23 11:46:07.515  5295  5427 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,02-23 11:46:07.515  5295  5373 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
02-23 11:46:07.515  3478  4384 V AlarmManager:  remove PendingIntent] PendingIntent{6355149: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
02-23 11:46:07.515  5295  5373 D BtGatt.GattService: Client app is not null!
,02-23 11:46:07.515  9551  9562 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,02-23 11:46:07.515  5295  5685 D BtGatt.GattService: unregisterClient() - clientIf=7
,02-23 11:46:07.525  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,02-23 11:46:07.525  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:07.525  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
02-23 11:46:07.525  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:07.525  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-143,7,main], id: 143
,02-23 11:46:07.525  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:07.525  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
02-23 11:46:07.525  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser Current thread: Thread[Thread-143,7,main], id: 143
,02-23 11:46:07.525  3478  4167 V AlarmManager:  remove PendingIntent] PendingIntent{aee0a4e: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
02-23 11:46:07.525  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-143,7,main], id: 143
,02-23 11:46:07.525  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:07.525  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
02-23 11:46:07.525  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
02-23 11:46:07.525  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "6ad45288-6074-487c-b683-03a4a8e47a45", Bluetooth MAC address: "44:78:3E:94:4A:3E"
,02-23 11:46:07.525  9551  9617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 44 78 3E 94 4A 3E
02-23 11:46:07.525  9551  9617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[6ad45288-6074-487c-b683-03a4a8e47a45], mManufacturerSpecificData={}, mServiceData={6ad45288-6074-487c-b683-03a4a8e47a45=[2, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
02-23 11:46:07.525  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[6ad45288-6074-487c-b683-03a4a8e47a45], mManufacturerSpecificData={}, mServiceData={6ad45288-6074-487c-b683-03a4a8e47a45=[2, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
02-23 11:46:07.525  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:07.525  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[6ad45288-6074-487c-b683-03a4a8e47a45], mManufacturerSpecificData={}, mServiceData={6ad45288-6074-487c-b683-03a4a8e47a45=[2, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:07.525  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
02-23 11:46:07.525  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[6ad45288-6074-487c-b683-03a4a8e47a45], mManufacturerSpecificData={}, mServiceData={6ad45288-6074-487c-b683-03a4a8e47a45=[2, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
02-23 11:46:07.525  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:07.525  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:07.525  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[6ad45288-6074-487c-b683-03a4a8e47a45], mManufacturerSpecificData={}, mServiceData={6ad45288-6074-487c-b683-03a4a8e47a45=[2, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:07.525  9551  9617 D BluetoothAdapter: STATE_ON
,02-23 11:46:07.535  9551  9617 D BluetoothAdapter: STATE_ON
02-23 11:46:07.535  9551  9617 D BluetoothLeAdvertiser: start advertising
02-23 11:46:07.535  9551  9617 D BluetoothAdapter: STATE_ON
,02-23 11:46:07.535  3478  4414 V AlarmManager:  remove PendingIntent] PendingIntent{4d2576f: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
,02-23 11:46:07.545  5295  5311 D BtGatt.GattService: registerClient() - UUID=1735bfb7-c5a6-4a1d-bb82-4da8936f2ecd
,02-23 11:46:07.545  3478  4167 V AlarmManager:  remove PendingIntent] PendingIntent{30d3c7c: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
,02-23 11:46:07.545  3478  3977 V AlarmManager:  remove PendingIntent] PendingIntent{8f8b905: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
,02-23 11:46:07.555  3478  4414 V AlarmManager:  remove PendingIntent] PendingIntent{9247d5a: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
,02-23 11:46:07.555  3478  4853 V AlarmManager:  remove PendingIntent] PendingIntent{56fb8b: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
,02-23 11:46:07.565  3478  4384 V AlarmManager:  remove PendingIntent] PendingIntent{e2fa468: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
,02-23 11:46:07.585  5295  5373 D BtGatt.GattService: onClientRegistered() - UUID=1735bfb7-c5a6-4a1d-bb82-4da8936f2ecd, clientIf=7
,02-23 11:46:07.585  9551  9610 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,02-23 11:46:07.585  5295  5603 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
02-23 11:46:07.595  5295  5603 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
02-23 11:46:07.595  5295  5603 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
02-23 11:46:07.595  5295  5427 D BtGatt.AdvertiseManager: message : 0
02-23 11:46:07.595  5295  5450 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_ADV
02-23 11:46:07.595  5295  5450 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 23, currDate: 23
02-23 11:46:07.595  5295  5427 D BtGatt.AdvertiseManager: number of adv instance running = 0
02-23 11:46:07.595  5295  5427 D BtGatt.AdvertiseManager: size of list is =0
02-23 11:46:07.605  5295  5427 D BtGatt.AdvertiseManager: starting advertising
02-23 11:46:07.605  5295  5450 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.test.thalitest : 3
02-23 11:46:07.605  5295  5450 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.test.thalitest@LowLatency : 24797446
02-23 11:46:07.605  5295  5450 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.test.thalitest@LowLatency : 2
02-23 11:46:07.605  5295  5450 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
02-23 11:46:07.605  5295  5450 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
02-23 11:46:07.615  5295  5427 D BtGatt.AdvertiseManager: isStandardAdv = false
02-23 11:46:07.615  3478  3969 V AlarmManager:  remove PendingIntent] PendingIntent{ed0e081: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
02-23 11:46:07.615  5295  5373 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
02-23 11:46:07.625  5295  5427 D BtGatt.AdvertiseManager: starting multi advertising
,02-23 11:46:07.625  5295  5373 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,02-23 11:46:07.625  5295  5427 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
02-23 11:46:07.625  5295  5427 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
02-23 11:46:07.625  3478  4167 V AlarmManager:  remove PendingIntent] PendingIntent{81d1526: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
,02-23 11:46:07.625  5295  5427 D BtGatt.AdvertiseManager: postCallback clientIf = 7 status = 0
02-23 11:46:07.625  5295  5427 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=7, status=0, isStart=true
02-23 11:46:07.625  9551  9561 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
02-23 11:46:07.625  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:07.625  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:07.625  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
02-23 11:46:07.625  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:07.625  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:07.625  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:07.625  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:07.635  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:07.635  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser started = true Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:07.635  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
02-23 11:46:07.635  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted false Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:07.635  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
02-23 11:46:07.635  9551  9617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
02-23 11:46:07.635  9551  9617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
02-23 11:46:07.635  9551  9617 I io.jxcore.node.ConnectionHelper: start: OK
02-23 11:46:07.635  9551  9551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
02-23 11:46:07.635  9551  9551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
02-23 11:46:07.635  9551  9551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,02-23 11:46:07.635  9551  9551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
02-23 11:46:07.635  9551  9551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
02-23 11:46:07.635  9551  9551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
02-23 11:46:07.635  9551  9551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
02-23 11:46:07.635  9551  9551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
,02-23 11:46:07.635  9551  9551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
02-23 11:46:07.635  9551  9551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
02-23 11:46:07.635  9551  9551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
02-23 11:46:07.635  3478  3977 V AlarmManager:  remove PendingIntent] PendingIntent{237c567: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
,02-23 11:46:07.635  9551  9631 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
02-23 11:46:07.635  9551  9617 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
02-23 11:46:07.635  9551  9617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
02-23 11:46:07.635  9551  9617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
02-23 11:46:07.635  9551  9617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
02-23 11:46:07.635  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
02-23 11:46:07.635  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,02-23 11:46:07.635  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
02-23 11:46:07.635  9551  9617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
02-23 11:46:07.635  9551  9617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
02-23 11:46:07.635  9551  9617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,02-23 11:46:07.635  9551  9617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
02-23 11:46:07.635  9551  9551 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
02-23 11:46:07.635  9551  9617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:07.635  9551  9617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
02-23 11:46:07.635  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
02-23 11:46:07.635  9551  9627 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
02-23 11:46:07.635  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:07.635  9551  9627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
02-23 11:46:07.635  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:07.635  9551  9627 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
02-23 11:46:07.635  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:07.645  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:07.645  9551  9617 D BluetoothAdapter: STATE_ON
02-23 11:46:07.645  9551  9617 D BluetoothAdapter: STATE_ON
02-23 11:46:07.645  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
02-23 11:46:07.655  3478  3969 V AlarmManager:  remove PendingIntent] PendingIntent{48e9f14: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
02-23 11:46:07.645  9551  9617 D BluetoothAdapter: STATE_ON
,02-23 11:46:07.655  9551  9617 D BluetoothAdapter: STATE_ON
02-23 11:46:07.655  9551  9617 D BluetoothLeScanner: could not find callback wrapper
02-23 11:46:07.655  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
02-23 11:46:07.655  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:07.655  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:07.655  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-143,7,main], id: 143
,02-23 11:46:07.655  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
02-23 11:46:07.655  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:07.655  9551  9617 D BluetoothAdapter: STATE_ON
,02-23 11:46:07.655  9551  9617 D BluetoothAdapter: STATE_ON
,02-23 11:46:07.655  9551  9617 D BluetoothLeAdvertiser: stop advertising
02-23 11:46:07.655  3478  4303 V AlarmManager:  remove PendingIntent] PendingIntent{2aa03bd: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
,02-23 11:46:07.665  3478  4387 V AlarmManager:  remove PendingIntent] PendingIntent{b55db2: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
,02-23 11:46:07.665  5295  5684 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
02-23 11:46:07.665  5295  5684 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
02-23 11:46:07.665  5295  5450 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_ADV
02-23 11:46:07.665  5295  5450 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 23, currDate: 23
,02-23 11:46:07.665  5295  5450 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
02-23 11:46:07.665  5295  5427 D BtGatt.AdvertiseManager: message : 1
02-23 11:46:07.665  5295  5450 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
,02-23 11:46:07.665  5295  5450 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
02-23 11:46:07.665  5295  5427 D BtGatt.AdvertiseManager: stop advertise for client =  7
,02-23 11:46:07.665  5295  5427 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 7
,02-23 11:46:07.665  5295  5427 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,02-23 11:46:07.675  5295  5373 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
02-23 11:46:07.675  5295  5373 D BtGatt.GattService: Client app is not null!
,02-23 11:46:07.675  3478  3497 V AlarmManager:  remove PendingIntent] PendingIntent{9715103: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
02-23 11:46:07.675  9551  9562 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,02-23 11:46:07.675  5295  5603 D BtGatt.GattService: unregisterClient() - clientIf=7
,02-23 11:46:07.675  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
02-23 11:46:07.675  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:07.675  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
02-23 11:46:07.675  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:07.675  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:07.675  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:07.675  9551  9617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
02-23 11:46:07.675  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
02-23 11:46:07.675  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,02-23 11:46:07.675  9551  9617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:07.675  3478  3499 V AlarmManager:  remove PendingIntent] PendingIntent{7409880: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
,02-23 11:46:07.685  9551  9617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:07.685  9551  9617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
02-23 11:46:07.685  9551  9617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:07.685  9551  9617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:07.685  9551  9551 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
02-23 11:46:07.685  9551  9551 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
02-23 11:46:07.685  9551  9551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
02-23 11:46:07.685  9551  9551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
02-23 11:46:07.685  9551  9551 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
02-23 11:46:07.685  9551  9551 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
02-23 11:46:07.685  9551  9551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
02-23 11:46:07.685  9551  9551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
02-23 11:46:07.685  9551  9551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
02-23 11:46:07.685  9551  9551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
02-23 11:46:07.685  9551  9551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
02-23 11:46:07.685  9551  9551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
02-23 11:46:07.685  9551  9551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
02-23 11:46:07.685  9551  9551 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
02-23 11:46:07.685  9551  9632 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
02-23 11:46:07.685  9551  9617 I io.jxcore.node.ConnectionHelperTest: Starting test: testListenToConnectivityChanges
02-23 11:46:07.685  9551  9617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
02-23 11:46:07.685  3478  4862 V AlarmManager:  remove PendingIntent] PendingIntent{7f81eb9: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
02-23 11:46:07.685  9551  9617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@83afa0e added. We now have 3 listener(s)
02-23 11:46:07.685  9551  9617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@83afa0e added. We now have 5 listener(s)
02-23 11:46:07.685  9551  9617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,02-23 11:46:07.695  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":2,"address":"44:78:3E:94:4A:3E"}
,02-23 11:46:07.695  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
02-23 11:46:07.695  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":2,"address":"44:78:3E:94:4A:3E"}
02-23 11:46:07.695  9551  9617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
02-23 11:46:07.695  9551  9617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e20ec2f added. We now have 6 listener(s)
,02-23 11:46:07.695  9551  9617 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,02-23 11:46:07.695  9551  9617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
02-23 11:46:07.695  3478  3497 V AlarmManager:  remove PendingIntent] PendingIntent{a17a2fe: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
,02-23 11:46:07.695  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,02-23 11:46:07.705  3478  4862 V AlarmManager:  remove PendingIntent] PendingIntent{1c6f10a: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
,02-23 11:46:07.705  9551  9617 D BluetoothAdapter: STATE_ON
,02-23 11:46:07.705  3478  3968 V AlarmManager:  remove PendingIntent] PendingIntent{6e1dd7b: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
,02-23 11:46:07.715  9551  9617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
02-23 11:46:07.715  9551  9617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
02-23 11:46:07.715  9551  9617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
02-23 11:46:07.715  9551  9617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
02-23 11:46:07.715  9551  9617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
02-23 11:46:07.715  9551  9617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
02-23 11:46:07.715  9551  9617 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
02-23 11:46:07.715  9551  9617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
02-23 11:46:07.715  9551  9617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,02-23 11:46:07.715  9551  9617 D io.jxcore.node.ConnectivityMonitor: start: OK
,02-23 11:46:07.715  3478  4435 V AlarmManager:  remove PendingIntent] PendingIntent{7c8f798: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
,02-23 11:46:07.715  9551  9617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,02-23 11:46:07.725  3478  4167 V AlarmManager:  remove PendingIntent] PendingIntent{391ebf1: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
,02-23 11:46:07.725  9551  9551 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,02-23 11:46:07.725  3478  4435 V AlarmManager:  remove PendingIntent] PendingIntent{86b13d6: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
,02-23 11:46:07.735  9551  9617 D BluetoothAdapter: STATE_ON
,02-23 11:46:07.735  3478  4387 V AlarmManager:  remove PendingIntent] PendingIntent{326d657: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
,02-23 11:46:07.735  9551  9617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
02-23 11:46:07.735  9551  9617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
02-23 11:46:07.735  9551  9617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
02-23 11:46:07.735  9551  9617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
02-23 11:46:07.735  9551  9617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
02-23 11:46:07.735  9551  9617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
02-23 11:46:07.735  9551  9617 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
02-23 11:46:07.735  9551  9617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
02-23 11:46:07.735  9551  9617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,02-23 11:46:07.735  9551  9617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
02-23 11:46:07.735  9551  9617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
02-23 11:46:07.735  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
02-23 11:46:07.735  9551  9617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
02-23 11:46:07.735  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
02-23 11:46:07.735  9551  9617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@83afa0e removed from the list
02-23 11:46:07.735  9551  9617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@83afa0e removed from the list
02-23 11:46:07.735  9551  9617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
02-23 11:46:07.735  9551  9617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e20ec2f removed from the list
,02-23 11:46:07.735  9551  9551 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,02-23 11:46:07.735  9551  9617 D io.jxcore.node.ConnectivityMonitor: stop
02-23 11:46:07.735  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
02-23 11:46:07.745  9551  9617 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
,02-23 11:46:07.745  9551  9617 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
02-23 11:46:07.745  9551  9617 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
,02-23 11:46:07.745  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [incoming]
,02-23 11:46:07.745  9551  9617 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
,02-23 11:46:07.745  9551  9617 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
02-23 11:46:07.745  9551  9551 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,02-23 11:46:07.745  9551  9617 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
,02-23 11:46:07.745  9551  9617 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,02-23 11:46:07.745  9551  9617 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
,02-23 11:46:07.745  9551  9617 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
02-23 11:46:07.745  9551  9617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,02-23 11:46:07.745  9551  9617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
02-23 11:46:07.745  9551  9617 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,02-23 11:46:07.745  9551  9617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
02-23 11:46:07.745  9551  9617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
02-23 11:46:07.745  9551  9617 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,02-23 11:46:07.745  9551  9617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
02-23 11:46:07.745  9551  9617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,02-23 11:46:07.755  9551  9617 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
,02-23 11:46:07.755  9551  9617 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,02-23 11:46:07.755  9551  9617 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
02-23 11:46:07.755  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [00:11:22:33:44:55]
,02-23 11:46:07.755  9551  9617 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
02-23 11:46:07.755  9551  9617 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,02-23 11:46:07.755  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [10:010:010:010:010:010]
02-23 11:46:07.755  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [11:110:110:110:110:110]
02-23 11:46:07.755  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [12:210:210:210:210:210]
,02-23 11:46:07.755  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [13:310:310:310:310:310]
02-23 11:46:07.755  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [14:410:410:410:410:410]
02-23 11:46:07.755  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [15:510:510:510:510:510]
,02-23 11:46:07.755  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [16:610:610:610:610:610]
02-23 11:46:07.755  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [17:710:710:710:710:710]
,02-23 11:46:07.755  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [18:810:810:810:810:810]
02-23 11:46:07.755  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [19:910:910:910:910:910]
,02-23 11:46:07.755  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [20:1010:1010:1010:1010:1010]
02-23 11:46:07.755  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [21:1110:1110:1110:1110:1110]
02-23 11:46:07.755  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [22:1210:1210:1210:1210:1210]
02-23 11:46:07.755  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [23:1310:1310:1310:1310:1310]
02-23 11:46:07.755  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [24:1410:1410:1410:1410:1410]
02-23 11:46:07.755  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [25:1510:1510:1510:1510:1510]
02-23 11:46:07.755  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [26:1610:1610:1610:1610:1610]
02-23 11:46:07.755  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [27:1710:1710:1710:1710:1710]
02-23 11:46:07.755  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [28:1810:1810:1810:1810:1810]
02-23 11:46:07.755  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [29:1910:1910:1910:1910:1910]
02-23 11:46:07.755  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [30:2010:2010:2010:2010:2010]
02-23 11:46:07.755  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [31:2110:2110:2110:2110:2110]
02-23 11:46:07.755  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [32:2210:2210:2210:2210:2210]
02-23 11:46:07.755  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [33:2310:2310:2310:2310:2310]
02-23 11:46:07.755  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [34:2410:2410:2410:2410:2410]
02-23 11:46:07.755  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [35:2510:2510:2510:2510:2510]
02-23 11:46:07.755  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [36:2610:2610:2610:2610:2610]
02-23 11:46:07.755  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [37:2710:2710:2710:2710:2710]
02-23 11:46:07.755  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [38:2810:2810:2810:2810:2810]
02-23 11:46:07.755  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [39:2910:2910:2910:2910:2910]
02-23 11:46:07.755  9551  9617 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
02-23 11:46:07.755  9551  9617 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
02-23 11:46:07.755  9551  9617 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
02-23 11:46:07.755  9551  9617 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
02-23 11:46:07.755  9551  9617 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
02-23 11:46:07.755  9551  9617 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
02-23 11:46:07.755  9551  9617 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
02-23 11:46:07.755  9551  9617 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
02-23 11:46:07.755  9551  9617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [00:11:22:33:44:55]
02-23 11:46:07.755  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConne,ctor: connect: Trying to start connecting to null in address 00:11:22:33:44:55
02-23 11:46:07.755  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port 1
02-23 11:46:07.755  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
02-23 11:46:07.755  9551  9617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
02-23 11:46:07.755  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
02-23 11:46:07.755  9551  9617 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
02-23 11:46:07.755  9551  9617 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
02-23 11:46:07.765  9551  9617 E io.jxcore.node.ConnectionHelper: connect: Callback is null
02-23 11:46:07.765  9551  9633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 215)
02-23 11:46:07.765  9551  9633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect: mIsShuttingDown = false
02-23 11:46:07.765  9551  9633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: createBluetoothSocket 1
02-23 11:46:07.765  9551  9633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: createBluetoothSocket: given port
02-23 11:46:07.765  9551  9617 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
02-23 11:46:07.765  9551  9617 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
02-23 11:46:07.765  9551  9617 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
02-23 11:46:07.765  9551  9617 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
02-23 11:46:07.765  9551  9617 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
02-23 11:46:07.765  9551  9617 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
02-23 11:46:07.765  9551  9617 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
02-23 11:46:07.765  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
02-23 11:46:07.765  9551  9617 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
02-23 11:46:07.765  9551  9617 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
02-23 11:46:07.765  9551  9617 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
02-23 11:46:07.765  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
02-23 11:46:07.765  9551  9617 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
02-23 11:46:07.765  9551  9617 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
02-23 11:46:07.765  9551  9617 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
02-23 11:46:07.765  9551  9617 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
02-23 11:46:07.765  9551  9617 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
02-23 11:46:07.765  9551  9617 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
02-23 11:46:07.765  9551  9617 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
02-23 11:46:07.765  9551  9617 V io.jxcore.node.ConnectivityMonitor: start: Already started
02-23 11:46:07.765  9551  9617 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
02-23 11:46:07.765  9551  9617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
02-23 11:46:07.765  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
02-23 11:46:07.775  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"44:78:3E:94:4A:3E"}
02-23 11:46:07.775  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"44:78:3E:94:4A:3E"}
02-23 11:46:07.775  9551  9633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: createBluetoothSocketToServiceRecord: Socket created with channel/port 1
02-23 11:46:07.775  9551  9633 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  connect: connecting
02-23 11:46:07.775  9551  9617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:07.775  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
02-23 11:46:07.775  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"44:78:3E:94:4A:3E"}
02-23 11:46:07.775  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"44:78:3E:94:4A:3E"}
02-23 11:46:07.775  9551  9617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:07.775  9551  9617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
02-23 11:46:07.775  9551  9617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
02-23 11:46:07.775  9551  9617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
02-23 11:46:07.775  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
02-23 11:46:07.775  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
02-23 11:46:07.775  9551  9617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
02-23 11:46:07.775  9551  9617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
02-23 11:46:07.775  9551  9617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
02-23 11:46:07.775  9551  9551 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
02-23 11:46:07.775  9551  9634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
02-23 11:46:07.775  9551  9617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
02-23 11:46:07.775  9551  9617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
02-23 11:46:07.775  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
02-23 11:46:07.775  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
02-23 11:46:07.785  9551  9634 D BluetoothSocket: bindListen(): myUserId = 0
02-23 11:46:07.785  9551  9634 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
02-23 11:46:07.785  9551  9633 D BluetoothSocket: connect(): myUserId = 0
02-23 11:46:07.785  9551  9633 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
02-23 11:46:07.785  9551  9617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
02-23 11:46:07.785  9551  9617 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
02-23 11:46:07.785  9551  9617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
02-23 11:46:07.795  9551  9634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
02-23 11:46:07.795  9551  9634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@4b0a91a, port: 6, type: 1, local socket address: null, socket type: 0
02-23 11:46:07.795  9551  9617 D BluetoothAdapter: STATE_ON
02-23 11:46:07.795  9551  9617 D BluetoothAdapter: STATE_ON
02-23 11:46:07.795  9551  9617 D BluetoothAdapter: STATE_ON
02-23 11:46:07.795  3478  4384 D SecContentProvider: insert(), uri = 2
02-23 11:46:07.795  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-143,7,main], id: 143
,02-23 11:46:07.795  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
02-23 11:46:07.795  5295  5586 W bt_btif : bta_dm_acl_change(), event : 2
02-23 11:46:07.805  9551  9617 D BluetoothAdapter: STATE_ON
02-23 11:46:07.805  3478  4853 V AlarmManager:  remove PendingIntent] PendingIntent{85880f3: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
02-23 11:46:07.805  9551  9617 D BluetoothAdapter: STATE_ON
02-23 11:46:07.805  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
02-23 11:46:07.805  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
02-23 11:46:07.805  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 3
02-23 11:46:07.805  9551  9617 D BluetoothAdapter: STATE_ON
02-23 11:46:07.805  3478  4277 V AlarmManager:  remove PendingIntent] PendingIntent{3eb21b0: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
02-23 11:46:07.805  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:07.805  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:07.805  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
02-23 11:46:07.805  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
02-23 11:46:07.805  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "6ad45288-6074-487c-b683-03a4a8e47a45", Bluetooth MAC address: "44:78:3E:94:4A:3E"
02-23 11:46:07.805  9551  9617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 44 78 3E 94 4A 3E
02-23 11:46:07.805  9551  9617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[6ad45288-6074-487c-b683-03a4a8e47a45], mManufacturerSpecificData={}, mServiceData={6ad45288-6074-487c-b683-03a4a8e47a45=[3, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
02-23 11:46:07.805  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[6ad45288-6074-487c-b683-03a4a8e47a45], mManufacturerSpecificData={}, mServiceData={6ad45288-6074-487c-b683-03a4a8e47a45=[3, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
02-23 11:46:07.805  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:07.805  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[6ad45288-6074-487c-b683-03a4a8e47a45], mManufacturerSpecificData={}, mServiceData={6ad45288-6074-487c-b683-03a4a8e47a45=[3, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:07.805  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
02-23 11:46:07.805  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[6ad45288-6074-487c-b683-03a4a8e47a45], mManufacturerSpecificData={}, mServiceData={6ad45288-6074-487c-b683-03a4a8e47a45=[3, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
02-23 11:46:07.805  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:07.805  3478  3969 V AlarmManager:  remove PendingIntent] PendingIntent{d812829: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
02-23 11:46:07.805  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:07.805  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[6ad45288-6074-487c-b683-03a4a8e47a45], mManufacturerSpecificData={}, mServiceData={6ad45288-6074-487c-b683-03a4a8e47a45=[3, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:07.805  9551  9617 D BluetoothAdapter: STATE_ON
02-23 11:46:07.815  9551  9617 D BluetoothAdapter: STATE_ON
02-23 11:46:07.815  9551  9617 D BluetoothLeAdvertiser: start advertising
02-23 11:46:07.815  9551  9617 D BluetoothAdapter: STATE_ON
02-23 11:46:07.815  5295  5307 D BtGatt.GattService: registerClient() - UUID=568b32e2-7c45-4382-ba18-d57b6041504a
,02-23 11:46:07.855  5295  5373 D BtGatt.GattService: onClientRegistered() - UUID=568b32e2-7c45-4382-ba18-d57b6041504a, clientIf=7
,02-23 11:46:07.855  9551  9610 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,02-23 11:46:07.855  5295  5603 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,02-23 11:46:07.865  5295  5603 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
02-23 11:46:07.865  5295  5603 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,02-23 11:46:07.865  5295  5427 D BtGatt.AdvertiseManager: message : 0
02-23 11:46:07.865  5295  5450 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_ADV
02-23 11:46:07.865  5295  5450 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 23, currDate: 23
,02-23 11:46:07.865  5295  5427 D BtGatt.AdvertiseManager: number of adv instance running = 0
02-23 11:46:07.865  5295  5427 D BtGatt.AdvertiseManager: size of list is =0
,02-23 11:46:07.865  5295  5427 D BtGatt.AdvertiseManager: starting advertising
,02-23 11:46:07.865  5295  5427 D BtGatt.AdvertiseManager: isStandardAdv = false
,02-23 11:46:07.875  5295  5450 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.test.thalitest : 4
02-23 11:46:07.875  3478  4435 V AlarmManager:  remove PendingIntent] PendingIntent{2f0c7ae: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
,02-23 11:46:07.875  5295  5450 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.test.thalitest@LowLatency : 24797446
,02-23 11:46:07.875  5295  5450 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.test.thalitest@LowLatency : 2
02-23 11:46:07.875  5295  5450 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
,02-23 11:46:07.875  5295  5450 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
02-23 11:46:07.875  5295  5373 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
02-23 11:46:07.875  5295  5427 D BtGatt.AdvertiseManager: starting multi advertising
,02-23 11:46:07.875  5295  5373 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,02-23 11:46:07.875  5295  5427 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
02-23 11:46:07.875  5295  5427 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
02-23 11:46:07.875  5295  5427 D BtGatt.AdvertiseManager: postCallback clientIf = 7 status = 0
02-23 11:46:07.875  5295  5427 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=7, status=0, isStart=true
02-23 11:46:07.875  3478  4277 V AlarmManager:  remove PendingIntent] PendingIntent{bf0394f: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
02-23 11:46:07.875  9551  9562 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
02-23 11:46:07.875  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:07.875  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:07.875  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
02-23 11:46:07.875  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:07.875  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:07.875  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:07.875  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:07.875  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:07.875  9551  9617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
02-23 11:46:07.875  9551  9617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
02-23 11:46:07.875  9551  9617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-143,7,main], id: 143
,02-23 11:46:07.875  9551  9617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: seems that updateState call different BlePeerDiscoverer
,02-23 11:46:07.875  3478  4384 V AlarmManager:  remove PendingIntent] PendingIntent{8d8a8dc: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
,02-23 11:46:07.875  9551  9617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-143,7,main], id: 143
,02-23 11:46:07.875  9551  9617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:07.875  9551  9617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:07.875  9551  9617 I io.jxcore.node.ConnectionHelper: start: OK
02-23 11:46:07.875  9551  9551 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,02-23 11:46:07.885  9551  9551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
02-23 11:46:07.885  9551  9551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
02-23 11:46:07.885  9551  9551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,02-23 11:46:07.885  9551  9551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
02-23 11:46:07.885  9551  9551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
02-23 11:46:07.885  9551  9551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
02-23 11:46:07.885  9551  9551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
02-23 11:46:07.885  9551  9551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
,02-23 11:46:07.885  9551  9551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
02-23 11:46:07.885  9551  9551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
02-23 11:46:07.885  9551  9551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
02-23 11:46:07.885  9551  9551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
02-23 11:46:07.885  9551  9551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
02-23 11:46:07.885  9551  9551 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,02-23 11:46:07.885  3478  4435 V AlarmManager:  remove PendingIntent] PendingIntent{ddb1de5: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
,02-23 11:46:07.885  9551  9551 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
02-23 11:46:07.885  9551  9551 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,02-23 11:46:07.885  9551  9551 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
02-23 11:46:07.885  9551  9551 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
02-23 11:46:07.885  9551  9551 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,02-23 11:46:07.885  3478  4862 V AlarmManager:  remove PendingIntent] PendingIntent{d85b0ba: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
,02-23 11:46:07.895  3478  4277 V AlarmManager:  remove PendingIntent] PendingIntent{7a11b6b: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
,02-23 11:46:07.895  3478  3499 V AlarmManager:  remove PendingIntent] PendingIntent{5b576c8: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
,02-23 11:46:07.895  3478  3969 V AlarmManager:  remove PendingIntent] PendingIntent{f24b361: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
,02-23 11:46:07.915  3478  4140 E Watchdog: !@Sync 6 [02-23 11:46:07.928]
,02-23 11:46:08.025  3478  4414 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,02-23 11:46:08.025  3478  4414 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4303, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
02-23 11:46:08.025  3478  4414 D BatteryService: online:4, current avg:5, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:52
02-23 11:46:08.025  3478  3478 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,02-23 11:46:08.035  3478  3478 I MotionRecognitionService: Plugged
,02-23 11:46:08.035  3478  3478 D MotionRecognitionService:   cableConnection= 1
02-23 11:46:08.035  3478  3478 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
02-23 11:46:08.035  3478  3478 D MotionRecognitionService: skip setTransmitPower. 
,02-23 11:46:08.045  3478  3856 D WifiController: ApOrStaEnabledState  msg.what= 155652
,02-23 11:46:08.045  3942  3942 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,02-23 11:46:08.045  3942  3942 D KeyguardUpdateMonitor: handleBatteryUpdate
,02-23 11:46:08.045  3942  3942 D PowerUI : priorPlugType = 2 mPlugType =  2
,02-23 11:46:08.045  3942  3942 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,02-23 11:46:08.045  3942  3942 D PowerUI.Notification: There is no change about charging status, so return!
,02-23 11:46:08.065  5328  5328 D CommonServiceConfiguration: getStringValueSetting
,02-23 11:46:08.085  5328  5328 D BatteryMonitor: new battery level: 100
,02-23 11:46:08.085  5295  5295 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
02-23 11:46:08.085  3942  3942 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
02-23 11:46:08.085  5295  5604 D HeadsetStateMachine: Disconnected process message: 10, size: 0
02-23 11:46:08.085  3942  3942 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:08.385  9551  9625 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
02-23 11:46:08.385  9551  9617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
02-23 11:46:08.385  9551  9617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
02-23 11:46:08.385  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
02-23 11:46:08.385  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
02-23 11:46:08.385  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
02-23 11:46:08.385  9551  9617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
02-23 11:46:08.385  9551  9617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
02-23 11:46:08.385  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
02-23 11:46:08.385  9551  9634 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
02-23 11:46:08.385  9551  9634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
02-23 11:46:08.385  9551  9634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
02-23 11:46:08.385  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
02-23 11:46:08.385  9551  9551 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
02-23 11:46:08.385  9551  9551 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
02-23 11:46:08.385  9551  9551 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,02-23 11:46:08.385  9551  9617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5467d5e removed from the list
,02-23 11:46:08.385  9551  9617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5467d5e removed from the list
02-23 11:46:08.385  9551  9617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
02-23 11:46:08.385  9551  9617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,02-23 11:46:08.385  9551  9617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:08.385  9551  9617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
02-23 11:46:08.385  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
02-23 11:46:08.385  9551  9551 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,02-23 11:46:08.385  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:08.385  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:08.385  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-143,7,main], id: 143
,02-23 11:46:08.385  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-143,7,main], id: 143
,02-23 11:46:08.385  9551  9638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 215
02-23 11:46:08.385  9551  9638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
,02-23 11:46:08.385  9551  9638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: closeBluetoothSocket: Trying to close the bluetooth socket... (thread ID: 215)
,02-23 11:46:08.385  9551  9617 D BluetoothAdapter: STATE_ON
02-23 11:46:08.395  5295  5680 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 8, channel: 1
02-23 11:46:08.395  9551  9638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: closeBluetoothSocket: bluetooth socket closed (thread ID: 215)
,02-23 11:46:08.395  9551  9633 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  connect: read failed, socket might closed or timeout, read ret: -1
02-23 11:46:08.395  9551  9617 D BluetoothAdapter: STATE_ON
02-23 11:46:08.395  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
02-23 11:46:08.395  9551  9633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socket is not connected
,02-23 11:46:08.395  9551  9633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 215)
02-23 11:46:08.395  9551  9617 D BluetoothAdapter: STATE_ON
,02-23 11:46:08.395  9551  9617 D BluetoothAdapter: STATE_ON
02-23 11:46:08.395  9551  9617 D BluetoothLeScanner: could not find callback wrapper
02-23 11:46:08.395  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,02-23 11:46:08.395  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:08.395  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:08.405  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:08.405  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,02-23 11:46:08.405  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-143,7,main], id: 143
,02-23 11:46:08.405  9551  9617 D BluetoothAdapter: STATE_ON
,02-23 11:46:08.405  9551  9617 D BluetoothAdapter: STATE_ON
,02-23 11:46:08.405  9551  9617 D BluetoothLeAdvertiser: stop advertising
,02-23 11:46:08.415  5295  5603 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
02-23 11:46:08.415  5295  5603 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,02-23 11:46:08.415  5295  5427 D BtGatt.AdvertiseManager: message : 1
02-23 11:46:08.415  5295  5450 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_ADV
,02-23 11:46:08.415  5295  5450 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 23, currDate: 23
02-23 11:46:08.415  5295  5450 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
02-23 11:46:08.415  5295  5450 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
,02-23 11:46:08.415  5295  5450 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
02-23 11:46:08.425  5295  5427 D BtGatt.AdvertiseManager: stop advertise for client =  7
02-23 11:46:08.425  5295  5427 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 7
,02-23 11:46:08.425  5295  5427 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,02-23 11:46:08.425  3478  3968 V AlarmManager:  remove PendingIntent] PendingIntent{f4e1e86: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
,02-23 11:46:08.425  5295  5373 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
02-23 11:46:08.425  5295  5373 D BtGatt.GattService: Client app is not null!
02-23 11:46:08.425  9551  9561 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,02-23 11:46:08.435  5295  5685 D BtGatt.GattService: unregisterClient() - clientIf=7
,02-23 11:46:08.435  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,02-23 11:46:08.435  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:08.435  3478  4384 V AlarmManager:  remove PendingIntent] PendingIntent{3340347: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
02-23 11:46:08.435  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
02-23 11:46:08.435  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:08.435  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:08.435  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-143,7,main], id: 143
,02-23 11:46:08.435  9551  9617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
02-23 11:46:08.435  9551  9617 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
02-23 11:46:08.435  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
02-23 11:46:08.445  9551  9617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-143,7,main], id: 143
,02-23 11:46:08.445  9551  9617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:08.445  9551  9617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,02-23 11:46:08.445  3478  4416 V AlarmManager:  remove PendingIntent] PendingIntent{60f3774: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
02-23 11:46:08.445  9551  9617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-143,7,main], id: 143
02-23 11:46:08.445  9551  9617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-143,7,main], id: 143
,02-23 11:46:08.445  9551  9617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dea353f removed from the list
02-23 11:46:08.445  9551  9551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
02-23 11:46:08.445  9551  9617 D io.jxcore.node.ConnectivityMonitor: stop
,02-23 11:46:08.445  9551  9617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
02-23 11:46:08.445  9551  9551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
02-23 11:46:08.445  9551  9551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,02-23 11:46:08.445  9551  9551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
02-23 11:46:08.445  9551  9551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,02-23 11:46:08.445  9551  9551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
02-23 11:46:08.445  9551  9551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
02-23 11:46:08.445  9551  9551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,02-23 11:46:08.445  9551  9551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
02-23 11:46:08.445  9551  9551 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,02-23 11:46:08.455  3478  4277 V AlarmManager:  remove PendingIntent] PendingIntent{f18249d: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
,02-23 11:46:08.465  3478  3499 V AlarmManager:  remove PendingIntent] PendingIntent{6dd9d12: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
,02-23 11:46:08.475  3478  4384 V AlarmManager:  remove PendingIntent] PendingIntent{238ce3: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
,02-23 11:46:08.485  3478  4862 V AlarmManager:  remove PendingIntent] PendingIntent{ea256e0: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
,02-23 11:46:08.495  3478  4387 V AlarmManager:  remove PendingIntent] PendingIntent{2d76d99: PendingIntentRecord{9001fd1 com.android.bluetooth broadcastIntent}}
,02-23 11:46:08.955  9551  9551 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,02-23 11:46:09.095  4352  4404 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
02-23 11:46:09.095  4352  4404 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,02-23 11:46:09.235  4352  4404 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 136ms lastUpdatedAfter : 128058ms

```
