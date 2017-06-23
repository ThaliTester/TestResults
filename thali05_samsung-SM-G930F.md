#### Test 127148139fecb998_thali05_samsung-SM-G930F Logs


```
--------- beginning of system
06-23 11:33:53.102  3486  4379 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-23 11:33:53.102  3486  4379 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4356, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-23 11:33:53.102  3486  4379 D BatteryService: online:4, current avg:159, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:144
06-23 11:33:53.102  3486  3486 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-23 11:33:53.102  3486  3486 I MotionRecognitionService: Plugged
--------- beginning of main
06-23 11:33:53.112  3486  3852 D WifiController: ApOrStaEnabledState  msg.what= 155652
06-23 11:33:53.112  3928  3928 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-23 11:33:53.112  3928  3928 D KeyguardUpdateMonitor: handleBatteryUpdate
06-23 11:33:53.112  3486  3486 D MotionRecognitionService:   cableConnection= 1
06-23 11:33:53.112  3486  3486 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-23 11:33:53.112  3486  3486 D MotionRecognitionService: skip setTransmitPower. 
06-23 11:33:53.112  3928  3928 D PowerUI : priorPlugType = 2 mPlugType =  2
06-23 11:33:53.122  4857  4857 D CommonServiceConfiguration: getStringValueSetting
06-23 11:33:53.132  4809  4809 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-23 11:33:53.132  4809  5244 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-23 11:33:53.132  4857  4857 D BatteryMonitor: new battery level: 100
06-23 11:33:53.152  3928  3928 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-23 11:33:53.152  3928  3928 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-23 11:33:53.632  9364  9364 I FIPS_bssl: FIPS approved mode (1) | 9364 | app_process
06-23 11:33:53.642  9364  9364 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
06-23 11:33:53.642  9364  9364 D AndroidRuntime: CheckJNI is OFF
06-23 11:33:53.642  9364  9364 D AndroidRuntime: readGMSProperty: start
06-23 11:33:53.642  9364  9364 D AndroidRuntime: readGMSProperty: already setted!!
06-23 11:33:53.642  9364  9364 D AndroidRuntime: propertySet: couldn't set property (it is from app)
06-23 11:33:53.642  9364  9364 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
06-23 11:33:53.642  9364  9364 D AndroidRuntime: readGMSProperty: end
06-23 11:33:53.642  9364  9364 D AndroidRuntime: addProductProperty: start
06-23 11:33:53.662  9364  9364 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
06-23 11:33:53.692  9364  9364 I Radio-JNI: register_android_hardware_Radio DONE
06-23 11:33:53.692  9364  9364 E AffinityControl: AffinityControl: registerfunction enter
06-23 11:33:53.702  9364  9364 D AndroidRuntime: Calling main entry com.android.commands.am.Am
06-23 11:33:53.732  3486  4285 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
06-23 11:33:53.732  3486  4285 W ResourcesManager: getTopLevelResources: /data/app/com.thaliproject.thalitest-1/base.apk / 1.0 running in null rsrc of package com.thaliproject.thalitest
06-23 11:33:53.762  3486  4285 D ResourcesManager: For user 0 new overlays fetched Null
06-23 11:33:53.762  3486  4285 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
06-23 11:33:53.762  3486  4285 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.thaliproject.thalitest)
06-23 11:33:53.762  3486  4285 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3486  pkgName : ACTIVITY_RESUME_BOOSTER@3
06-23 11:33:53.762  3486  4285 D ActivityManager: mDVFSHelper.acquire()
06-23 11:33:53.762  3486  4285 V WindowManager: addAppToken: AppWindowToken{d0905286c token=Token{5a7bd1f ActivityRecord{fa7b8be u0 com.thaliproject.thalitest/.MainActivity t5}}} to stack=2 task=5 at 0
06-23 11:33:53.782  3486  4285 D InputDispatcher: Focused application set to: xxxx
06-23 11:33:53.782  3486  4285 D InputDispatcher: Focus left window: 6117
06-23 11:33:53.782  3486  3569 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{1a0f790 u0 d0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}
06-23 11:33:53.782  9364  9364 D AndroidRuntime: Shutting down VM
06-23 11:33:53.792  3928  3928 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=8000 newVal=8600 diff=600
06-23 11:33:53.792  3486  3590 I InjectionManager: Inside getClassLibPath caller 
06-23 11:33:53.792  3486  3590 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{f740eed V.E...... R.....ID 0,0-0,0}
06-23 11:33:53.792  3486  3590 D SecWifiDisplayUtil: Metadata value : SecSettings2
06-23 11:33:53.792  3486  3590 D ISSUE_DEBUG: InputChannelName : 76ac7b3 Starting com.thaliproject.thalitest
06-23 11:33:53.802  3486  3590 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3486 uid:1000
06-23 11:33:53.802  3486  3590 D PointerIcon: setMouseCustomIcon IconType is same.101
06-23 11:33:53.802  9374  9374 E Zygote  : v2
06-23 11:33:53.802  9374  9374 I libpersona: KNOX_SDCARD checking this for 10074
06-23 11:33:53.802  9374  9374 I libpersona: KNOX_SDCARD not a persona
06-23 11:33:53.802  9374  9374 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
06-23 11:33:53.802  3486  4258 I ActivityManager: Start proc 9374:com.thaliproject.thalitest/u0a74 for activity com.thaliproject.thalitest/.MainActivity
06-23 11:33:53.802  9374  9374 E Zygote  : accessInfo : 0
06-23 11:33:53.802  9374  9374 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.thaliproject.thalitest 
06-23 11:33:53.802  3486  3847 D NetworkPolicy: isUidForegroundLocked: 10074, mScreenOn: true, uidstate: -1, mProxSensorScreenOff: false
06-23 11:33:53.802  3006  3006 I SurfaceFlinger: id=18 createSurf (1x1),1 flag=404, uhalitest
06-23 11:33:53.822  9374  9374 D TimaKeyStoreProvider: TimaSignature is unavailable
06-23 11:33:53.822  9374  9374 D ActivityThread: Added TimaKeyStore provider
06-23 11:33:53.822  3486  3590 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
06-23 11:33:53.822  3486  4395 V WindowOrientationListener: setCurrentAppOrientation :-1
06-23 11:33:53.822  3486  4395 V WindowOrientationListener: OrientationSensorJudge.getProposedRotation, Rotation: -1
06-23 11:33:53.822  3486  4395 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
06-23 11:33:53.822  3486  4395 V WindowOrientationListener: OrientationSensorJudge.getProposedRotation, Rotation: -1
06-23 11:33:53.822  3486  4395 D ActivityManager:  Launching com.thaliproject.thalitest, updated priority
06-23 11:33:53.832  6764  6764 V ActivityThread: updateVisibility : ActivityRecord{f06dd12 token=android.os.BinderProxy@408346d {com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity}} show : false
06-23 11:33:53.832  4259  4259 D Launcher.HomeView: onStop
06-23 11:33:53.832  4259  4259 D capture : ----destroy
06-23 11:33:53.832  4259  4259 V ActivityThread: updateVisibility : ActivityRecord{a079418 token=android.os.BinderProxy@b2b0183 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
06-23 11:33:53.832  3486  3486 D GameManagerService: NotifyRunnable. pkg: com.thaliproject.thalitest, type: 4, isMinimized: false, isTunableApp: false
06-23 11:33:53.842  3486  3567 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.thaliproject.thalitest
06-23 11:33:53.842  3486  3567 E MARsPolicyManager: getPackageInfo package com.test.thalitest not installed!
06-23 11:33:53.842  3486  3567 E MARsPolicyManager: getPackageInfo package com.rockwellautomation.thalitest not installed!
06-23 11:33:53.842  3486  6038 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
06-23 11:33:53.842  3486  6038 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
06-23 11:33:53.842  9374  9374 W ResourcesManager: getTopLevelResources: /data/app/com.thaliproject.thalitest-1/base.apk / 1.0 running in com.thaliproject.thalitest rsrc of package com.thaliproject.thalitest
06-23 11:33:53.842  3486  4049 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
06-23 11:33:53.842  9374  9374 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
06-23 11:33:53.842  3006  3016 D libEGL  : eglTerminate EGLDisplay = 0x7f77780e78
06-23 11:33:53.842  3006  3016 D libEGL  : eglTerminate EGLDisplay = 0x7f77780e78
06-23 11:33:53.852  3006  4468 D libEGL  : eglTerminate EGLDisplay = 0x7f700ffe78
06-23 11:33:53.852  3006  4468 D libEGL  : eglTerminate EGLDisplay = 0x7f700ffe78
06-23 11:33:53.852  9374  9374 D ResourcesManager: For user 0 new overlays fetched Null
06-23 11:33:53.852  3486  3590 V WindowStateAnimator: Finishing drawing window Window{76ac7b3 u0 d0 Starting com.thaliproject.thalitest}: mDrawState=DRAW_PENDING
06-23 11:33:53.852  3006  3006 D libEGL  : eglInitialize EGLDisplay = 0x7ffb1ed5e8
06-23 11:33:53.852  3486  6038 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
06-23 11:33:53.852  3486  6038 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
06-23 11:33:53.862  3486  3569 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{76ac7b3 u0 d0 Starting com.thaliproject.thalitest}
06-23 11:33:53.862  9374  9374 I InjectionManager: Inside getClassLibPath caller 
06-23 11:33:53.862  3486  6038 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
06-23 11:33:53.862  4259  4259 D Launcher: onTrimMemory. Level: 20
06-23 11:33:53.862  3486  6038 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
06-23 11:33:53.862  3486  6038 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
06-23 11:33:53.872  3006  3016 D libEGL  : eglTerminate EGLDisplay = 0x7f77780e78
06-23 11:33:53.872  3006  3016 D libEGL  : eglTerminate EGLDisplay = 0x7f77780e78
06-23 11:33:53.872  9374  9374 D InjectionManager: InjectionManager
06-23 11:33:53.872  9374  9374 D InjectionManager: fillFeatureStoreMap com.thaliproject.thalitest
06-23 11:33:53.872  9374  9374 I InjectionManager: Constructor com.thaliproject.thalitest, Feature store :{}
06-23 11:33:53.872  9374  9374 I InjectionManager: featureStore :{}
06-23 11:33:53.882  9374  9374 W ResourcesManager: getTopLevelResources: /data/app/com.thaliproject.thalitest-1/base.apk / 1.0 running in com.thaliproject.thalitest rsrc of package com.thaliproject.thalitest
06-23 11:33:53.882  9374  9374 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
06-23 11:33:53.882  9374  9374 D RelationGraph: garbageCollect()
06-23 11:33:53.882  9374  9374 W ResourcesManager: getTopLevelResources: /data/app/com.thaliproject.thalitest-1/base.apk / 1.0 running in com.thaliproject.thalitest rsrc of package com.thaliproject.thalitest
06-23 11:33:53.892  9374  9374 I CordovaLog: Changing log level to DEBUG(3)
06-23 11:33:53.892  9374  9374 I CordovaActivity: Apache Cordova native platform version 6.0.0 is starting
06-23 11:33:53.892  9374  9374 D CordovaActivity: CordovaActivity.onCreate()
06-23 11:33:53.902  9374  9374 I WebViewFactory: Loading com.google.android.webview version 50.0.2661.86 (code 266108650)
06-23 11:33:53.902  3486  3496 I art     : Background partial concurrent mark sweep GC freed 58059(3MB) AllocSpace objects, 52(1040KB) LOS objects, 31% free, 35MB/51MB, paused 1.231ms total 123.446ms
06-23 11:33:53.912  9374  9374 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.thaliproject.thalitest rsrc of package com.google.android.webview
06-23 11:33:53.912  9374  9374 D ResourcesManager: For user 0 new overlays fetched Null
06-23 11:33:53.922  9374  9374 I InjectionManager: Inside getClassLibPath caller 
06-23 11:33:53.922  9374  9374 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
06-23 11:33:53.952  9374  9374 I cr_LibraryLoader: Time to load native libraries: 20 ms (timestamps 4084-4104)
06-23 11:33:53.952  9374  9374 I cr_LibraryLoader: Expected native library version number "50.0.2661.86", actual native library version number "50.0.2661.86"
06-23 11:33:53.972  9374  9389 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.thaliproject.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
06-23 11:33:53.992  9374  9374 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1339123}
06-23 11:33:53.992  9374  9374 I cr_LibraryLoader: Expected native library version number "50.0.2661.86", actual native library version number "50.0.2661.86"
,06-23 11:33:54.002  9374  9374 I chromium: [INFO:library_loader_hooks.cc(143)] Chromium logging enabled: level = 0, default verbosity = 0
,06-23 11:33:54.042  9374  9374 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,06-23 11:33:54.092  3486  3871 D MdnieScenarioControlService:  packageName : com.thaliproject.thalitest    className : com.thaliproject.thalitest.MainActivity
,06-23 11:33:54.122  9374  9374 D libEGL  : eglInitialize EGLDisplay = 0xffb077f4
,06-23 11:33:54.172  3486  3504 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10074
,06-23 11:33:54.172  3486  3504 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29757 com.android.server.am.ActivityManagerService.registerReceiver:22622 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,06-23 11:33:54.182  3486  3847 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: true, uidstate: 2, mProxSensorScreenOff: false
,06-23 11:33:54.192  3486  3871 I MdnieScenarioControlService: mGameModeLauncher : false
,06-23 11:33:54.202  3486  3871 I MdnieScenarioControlService: setUIMode
,06-23 11:33:54.202  9374  9374 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10074, CallingPid : 9374
,06-23 11:33:54.202  3486  4396 D ConnectivityService: listenForNetwork for Listen from uid/pid:10074/9374 for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-23 11:33:54.202  3486  3858 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
06-23 11:33:54.212  3486  3858 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -38]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,06-23 11:33:54.212  3486  3858 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,06-23 11:33:54.212  3486  3858 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,06-23 11:33:54.212  3486  3858 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,06-23 11:33:54.212  3486  3858 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,06-23 11:33:54.222  9374  9374 D cr_Ime  : [InputMethodManagerWrapper.java:30] Constructor
06-23 11:33:54.222  3486  3858 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,06-23 11:33:54.222  3486  3858 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,06-23 11:33:54.222  3486  3858 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-23 11:33:54.232  9374  9374 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,06-23 11:33:54.232  9374  9374 D cr_Ime  : [InputMethodManagerWrapper.java:59] isActive: false
,06-23 11:33:54.232  3006  3016 I SurfaceFlinger: id=10 Removed MauncherAct (4/15)
06-23 11:33:54.232  3006  3018 I SurfaceFlinger: id=10 Removed MauncherAct (-2/15)
,06-23 11:33:54.232  3006  4305 I SurfaceFlinger: id=15 Removed YUIInstallC (4/14)
06-23 11:33:54.232  3006  4468 I SurfaceFlinger: id=15 Removed YUIInstallC (-2/14)
06-23 11:33:54.232  3006  4327 I SurfaceFlinger: id=14 Removed YUIInstallC (4/13)
,06-23 11:33:54.242  3006  3018 I SurfaceFlinger: id=14 Removed YUIInstallC (-2/13)
06-23 11:33:54.242  3006  3018 I SurfaceFlinger: id=17 Removed VSBConnecti (4/12)
06-23 11:33:54.242  3006  3016 I SurfaceFlinger: id=17 Removed VSBConnecti (-2/12)
06-23 11:33:54.242  3006  4468 I SurfaceFlinger: id=16 Removed VSBConnecti (5/11)
06-23 11:33:54.242  3006  4305 I SurfaceFlinger: id=16 Removed VSBConnecti (-2/11)
,06-23 11:33:54.242  3928  3928 D ImageWallpaper: onVisibilityChanged:false
,06-23 11:33:54.242  3928  3928 D ImageWallpaper: drawFrame:false rotation:0 mLastRotation:0
06-23 11:33:54.242  3928  3928 D ImageWallpaper: drawFrame:[frame.width()]2240[frame.height()]2560
06-23 11:33:54.242  3928  3928 D ImageWallpaper: Suppressed drawFrame since redraw is not needed and offsets have not changed.
,06-23 11:33:54.252  9374  9374 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,06-23 11:33:54.252  3006  3006 D libEGL  : eglTerminate EGLDisplay = 0x7ffb1ed708
,06-23 11:33:54.252  3006  3006 D libEGL  : eglTerminate EGLDisplay = 0x7ffb1ed708
06-23 11:33:54.252  3006  3006 D libEGL  : eglTerminate EGLDisplay = 0x7ffb1ed708
06-23 11:33:54.252  3006  3006 D libEGL  : eglTerminate EGLDisplay = 0x7ffb1ed708
,06-23 11:33:54.252  9374  9374 D PluginManager: init()
,06-23 11:33:54.252  9374  9374 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,06-23 11:33:54.262  9374  9374 I cr_Ime  : ImeThread is not enabled.
,06-23 11:33:54.272  9374  9374 D Activity: performCreate Call Injection manager
,06-23 11:33:54.272  9374  9374 D CordovaActivity: Started the activity.
06-23 11:33:54.272  9374  9374 I InjectionManager: dispatchOnViewCreated > Target : com.thaliproject.thalitest.MainActivity isFragment :false
06-23 11:33:54.272  9374  9374 D CordovaActivity: Resumed the activity.
,06-23 11:33:54.272  9374  9374 D SecWifiDisplayUtil: Metadata value : SecSettings2
,06-23 11:33:54.282  9374  9374 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{a731efe I.E...... R.....ID 0,0-0,0}
,06-23 11:33:54.282  9374  9424 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,06-23 11:33:54.282  3486  4395 D ISSUE_DEBUG: InputChannelName : 58b6a0b com.thaliproject.thalitest/com.thaliproject.thalitest.MainActivity
,06-23 11:33:54.282  3486  3975 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
06-23 11:33:54.282  3486  3975 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
06-23 11:33:54.282  3486  3486 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,06-23 11:33:54.292  3486  3486 I KnoxTimeoutHandler: Shared devices show user statefalse
06-23 11:33:54.292  9374  9374 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10074, CallingPid : 9374
06-23 11:33:54.292  3486  3969 D ConnectivityService: listenForNetwork for Listen from uid/pid:10074/9374 for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-23 11:33:54.292  9374  9389 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.thaliproject.thalitest/shared_prefs/com.thaliproject.thalitest_preferences.xml.bak
06-23 11:33:54.292  3486  3858 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
06-23 11:33:54.292  3486  3858 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -38]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
06-23 11:33:54.292  3486  3858 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
06-23 11:33:54.302  3486  3858 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
06-23 11:33:54.302  3486  3847 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: true, uidstate: 6, mProxSensorScreenOff: false
06-23 11:33:54.302  3486  3858 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
06-23 11:33:54.302  3486  3858 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
06-23 11:33:54.302  9374  9374 D SecWifiDisplayUtil: Metadata value : SecSettings2
06-23 11:33:54.312  3486  3858 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
06-23 11:33:54.312  3486  3858 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
06-23 11:33:54.312  3486  3858 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
06-23 11:33:54.312  3486  3858 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-23 11:33:54.312  3006  3006 I SurfaceFlinger: id=19 createSurf (1x1),1 flag=404, NainActivit
,06-23 11:33:54.332  3486  4396 D InputDispatcher: Focus entered window: 9374
,06-23 11:33:54.342  3486  3590 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3486 uid:1000
06-23 11:33:54.342  3486  3590 D PointerIcon: setMouseCustomIcon IconType is same.101
,06-23 11:33:54.342  9374  9424 D libEGL  : eglInitialize EGLDisplay = 0xdc7ff7c4
06-23 11:33:54.342  9374  9424 I OpenGLRenderer: Initialized EGL, version 1.4
,06-23 11:33:54.342  9374  9424 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,06-23 11:33:54.352  9374  9374 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,06-23 11:33:54.352  9374  9428 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
06-23 11:33:54.352  9374  9428 D libEGL  : eglInitialize EGLDisplay = 0xdaaff3e4
,06-23 11:33:54.362  9374  9428 D libGLESv2: DTS_GLAPI : DTS is not allowed for Package : com.thaliproject.thalitest
,06-23 11:33:54.382  3486  4395 V WindowStateAnimator: Finishing drawing window Window{58b6a0b u0 d0 com.thaliproject.thalitest/com.thaliproject.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,06-23 11:33:54.382  9374  9374 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
,06-23 11:33:54.382  3486  4379 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,06-23 11:33:54.382  3006  3006 D libEGL  : eglInitialize EGLDisplay = 0x7ffb1ed5e8
,06-23 11:33:54.392  3486  3590 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
06-23 11:33:54.392  3486  3486 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,06-23 11:33:54.392  3486  3590 I ActivityManager: Displayed com.thaliproject.thalitest/.MainActivity: +596ms
06-23 11:33:54.392  3486  3590 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3486  tag : ACTIVITY_RESUME_BOOSTER@3
,06-23 11:33:54.392  3486  3486 I KnoxTimeoutHandler: SD activityfalse
06-23 11:33:54.392  3486  3590 D ActivityManager: mDVFSHelper.release()
06-23 11:33:54.392  3486  3590 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{fa7b8be u0 com.thaliproject.thalitest/.MainActivity t5} time:174541
06-23 11:33:54.392  3486  3567 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3486  pkgName : ACTIVITY_RESUME_BOOSTER@9
06-23 11:33:54.392  3486  3590 D ViewRootImpl: #3 mView = null
,06-23 11:33:54.392  4726  4726 D SamsungIME: IMPL finishInput
,06-23 11:33:54.392  4726  4726 D SamsungIME: SwiftKeyWrapper writeDBdataToFileOnFinishInput
06-23 11:33:54.392  4726  4726 D SamsungIME: saveAndClear +
06-23 11:33:54.392  4726  4726 D SamsungIME: saveAndClear -
,06-23 11:33:54.392  3486  4257 V WindowStateAnimator: Finishing drawing window Window{58b6a0b u0 d0 com.thaliproject.thalitest/com.thaliproject.thalitest.MainActivity}: mDrawState=HAS_DRAWN
,06-23 11:33:54.402  9374  9374 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
,06-23 11:33:54.402  9374  9374 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@5be37c6 time:174550
,06-23 11:33:54.402  6117  6117 V ActivityThread: updateVisibility : ActivityRecord{a6e6276 token=android.os.BinderProxy@7527ae8 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
,06-23 11:33:54.402  3006  3006 D libEGL  : eglInitialize EGLDisplay = 0x7ffb1ed5e8
,06-23 11:33:54.412  9374  9374 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9374
,06-23 11:33:54.412  9374  9374 D cr_Ime  : [InputMethodManagerWrapper.java:59] isActive: true
06-23 11:33:54.412  9374  9374 D cr_Ime  : [InputMethodManagerWrapper.java:68] hideSoftInputFromWindow
,06-23 11:33:54.432  3006  3006 D libEGL  : eglInitialize EGLDisplay = 0x7ffb1ed5e8
,06-23 11:33:54.472  9374  9374 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,06-23 11:33:54.512  3486  6038 D SSRM:n  : SIOP:: AP = 310, PST = 307 (W:10), CP = 257, CUR = 159, LCD = 40
,06-23 11:33:54.512  3486  6038 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,06-23 11:33:54.592  3006  4327 I SurfaceFlinger: id=18 Removed uhalitest (7/11)
,06-23 11:33:54.592  3006  3018 I SurfaceFlinger: id=18 Removed uhalitest (-2/11)
,06-23 11:33:54.592  9374  9438 D jxcore_app_log: JniHelper::setJavaVM(0xf4df4000), pthread_self() = -702547664
,06-23 11:33:54.592  9374  9438 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
06-23 11:33:54.592  9374  9438 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
06-23 11:33:54.592  9374  9438 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
06-23 11:33:54.592  9374  9438 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
06-23 11:33:54.592  9374  9438 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
06-23 11:33:54.592  9374  9438 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1401429 added. We now have 1 listener(s)
,06-23 11:33:54.592  9374  9438 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1401429 added. We now have 1 listener(s)
06-23 11:33:54.592  9374  9438 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
06-23 11:33:54.592  9374  9438 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
06-23 11:33:54.592  9374  9438 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
06-23 11:33:54.592  9374  9438 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: null
06-23 11:33:54.592  9374  9438 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
06-23 11:33:54.592  9374  9438 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
06-23 11:33:54.592  9374  9438 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
06-23 11:33:54.592  9374  9438 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
06-23 11:33:54.592  9374  9438 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 256
06-23 11:33:54.592  9374  9438 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
06-23 11:33:54.592  9374  9438 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
06-23 11:33:54.592  9374  9438 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
06-23 11:33:54.592  9374  9438 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
06-23 11:33:54.592  9374  9438 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,06-23 11:33:54.602  9374  9438 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 44:78:3E:94:2C:E6
,06-23 11:33:54.602  9374  9438 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: ", Bluetooth MAC address: "44:78:3E:94:2C:E6"Peer extra info: "256
06-23 11:33:54.602  9374  9438 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
06-23 11:33:54.602  9374  9438 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: null
06-23 11:33:54.602  9374  9438 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
06-23 11:33:54.602  9374  9438 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2584dc added. We now have 2 listener(s)
06-23 11:33:54.602  9374  9438 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
06-23 11:33:54.602  9374  9438 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
06-23 11:33:54.602  9374  9438 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 53944
,06-23 11:33:54.602  9374  9438 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,7,main], id: 138
06-23 11:33:54.602  9374  9438 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
06-23 11:33:54.602  9374  9438 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
06-23 11:33:54.602  9374  9438 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
06-23 11:33:54.602  9374  9438 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,7,main], id: 138
,06-23 11:33:54.602  9374  9438 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
06-23 11:33:54.602  9374  9438 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 44:78:3E:94:2C:E6
06-23 11:33:54.602  3006  3006 D libEGL  : eglTerminate EGLDisplay = 0x7ffb1ed708
,06-23 11:33:54.602  9374  9438 D BluetoothAdapter: STATE_ON
,06-23 11:33:54.602  9374  9438 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
06-23 11:33:54.612  9374  9438 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-23 11:33:54.612  9374  9438 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-23 11:33:54.612  9374  9438 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
06-23 11:33:54.612  9374  9438 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-23 11:33:54.612  9374  9438 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-23 11:33:54.612  9374  9438 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
06-23 11:33:54.612  9374  9438 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
06-23 11:33:54.612  9374  9438 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
06-23 11:33:54.612  9374  9438 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
06-23 11:33:54.612  9374  9438 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
06-23 11:33:54.612  9374  9438 D io.jxcore.node.ConnectivityMonitor: start: OK
06-23 11:33:54.612  9374  9374 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-23 11:33:54.612  9374  9438 I io.jxcore.node.LifeCycleMonitor: start: OK
,06-23 11:33:54.612  9374  9374 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-23 11:33:54.612  9374  9374 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-23 11:33:54.622  9374  9374 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,06-23 11:33:54.622  9374  9374 D SystemWebChromeClient: file:///android_asset/www/js/index.js: Line 36 : Uncaught TypeError: Cannot read property 'querySelector' of null
,06-23 11:33:54.622  9374  9374 I chromium: [INFO:CONSOLE(36)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (36)
,06-23 11:33:54.662  3486  3871 D MdnieScenarioControlService:  packageName : com.thaliproject.thalitest    className : com.thaliproject.thalitest.MainActivity
,06-23 11:33:54.692  3486  3486 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3486  tag : ACTIVITY_RESUME_BOOSTER@9
,06-23 11:33:54.762  3486  3871 I MdnieScenarioControlService: mGameModeLauncher : false
,06-23 11:33:54.762  3486  3871 I MdnieScenarioControlService: setUIMode
,06-23 11:33:54.802  4019  4019 D Recents : onTaskStackChanged
,06-23 11:33:54.812  4019  4019 W ResourcesManager: getTopLevelResources: /data/app/com.thaliproject.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.thaliproject.thalitest
,06-23 11:33:54.822  4019  4019 D ResourcesManager: For user 0 new overlays fetched Null
,06-23 11:33:54.842  3486  6039 W ResourcesManager: getTopLevelResources: /data/app/com.thaliproject.thalitest-1/base.apk / 1.0 running in null rsrc of package com.thaliproject.thalitest
,06-23 11:33:55.122  9374  9439 W jxcore-log: Initializing JXcore engine
06-23 11:33:55.122  9374  9439 W jxcore-log: JXcore engine is ready
,06-23 11:33:55.142  4827  4827 E audit   : type=1400 msg=audit(1498210435.142:264): avc:  denied  { ioctl } for  pid=9439 comm="Thread-139" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
06-23 11:33:55.142  4827  4827 E audit   :  SEPF_SECMOBILE_6.0.1_0031
06-23 11:33:55.142  4827  4827 E audit   : type=1300 msg=audit(1498210435.142:264): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=8 a1=5451 a2=2 a3=d54bf3c8 items=0 ppid=3176 pid=9439 auid=4294967295 uid=10074 gid=10074 euid=10074 suid=10074 fsuid=10074 egid=10074 sgid=10074 fsgid=10074 tty=(none) ses=4294967295 comm="Thread-139" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
06-23 11:33:55.142  4827  4827 E audit   : type=1327 msg=audit(1498210435.142:264): proctitle="com.thaliproject.thalitest"
06-23 11:33:55.142  4827  4827 E audit   : type=1320 msg=audit(1498210435.142:264): 
,06-23 11:33:55.142  4827  4827 E audit   : type=1400 msg=audit(1498210435.142:265): avc:  denied  { ioctl } for  pid=9439 comm="Thread-139" path="socket:[38956]" dev="sockfs" ino=38956 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
06-23 11:33:55.142  4827  4827 E audit   :  SEPF_SECMOBILE_6.0.1_0031
06-23 11:33:55.142  4827  4827 E audit   : type=1300 msg=audit(1498210435.142:265): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=33 a1=5451 a2=2 a3=d54bf3c8 items=0 ppid=3176 pid=9439 auid=4294967295 uid=10074 gid=10074 euid=10074 suid=10074 fsuid=10074 egid=10074 sgid=10074 fsgid=10074 tty=(none) ses=4294967295 comm="Thread-139" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
06-23 11:33:55.142  4827  4827 E audit   : type=1327 msg=audit(1498210435.142:265): proctitle="com.thaliproject.thalitest"
06-23 11:33:55.142  4827  4827 E audit   : type=1320 msg=audit(1498210435.142:265): 
,06-23 11:33:55.142  9374  9439 W jxcore-log: Starting JXcore engine
,06-23 11:33:55.182  9374  9439 W jxcore-log: Platform android
06-23 11:33:55.182  9374  9439 W jxcore-log: 
06-23 11:33:55.182  9374  9439 W jxcore-log: Process ARCH arm
06-23 11:33:55.182  9374  9439 W jxcore-log: 
,06-23 11:33:55.312  9374  9439 I jxcore-log: JXcore Cordova bridge is ready!
06-23 11:33:55.312  9374  9439 I jxcore-log: 
06-23 11:33:55.312  9374  9439 W jxcore-log: JXcore engine is started
,06-23 11:33:55.312  9374  9438 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,06-23 11:33:55.322  9374  9374 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 41 : Application has the required permission.
06-23 11:33:55.322  9374  9374 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,06-23 11:33:56.782  3486  3897 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/5_task.xml.bak
,06-23 11:33:56.842  3486  6038 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
,06-23 11:33:59.882  3486  6038 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,06-23 11:33:59.992  3486  3807 V AlarmManager: Expired Alarm result :8
,06-23 11:33:59.992  3928  3928 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
06-23 11:33:59.992  3928  3928 D KeyguardUpdateMonitor: handleTimeUpdate
,06-23 11:34:00.012  3928  3928 D Clock   : received broadcast android.intent.action.TIME_TICK
,06-23 11:34:00.062  3928  3928 D DateView: received broadcast android.intent.action.TIME_TICK
,06-23 11:34:00.082  4622  4622 D [Weather Widget]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,06-23 11:34:00.082  4622  4622 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EEFA9050249635C043F7E254E316C2550]}
,06-23 11:34:00.092  4622  4622 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EAB01DC5C99149A39F887E17599325AFBFF089086AA9902184ADA25758C536FE2]}
,06-23 11:34:00.092  4622  4622 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EFF0B905BDFF72B69FB632A6CB072B41F95D2E6F4F84443284E97F40042D431D8350388453A923ABD8469D82798FA7548]}
06-23 11:34:00.092  4622  4622 D [Weather Widget]  : {[A1AF0F6A1A65A89C43D705938923D0FEFB71880C4E84718DA0A3E1F383E54FB27A4284D9BEDF7BAA2ABFFE671EB65C640578FF9DE16A23BFE3280A9DCDBB09A0930C2946B4A4DB933C502C8761FBEA50704C777D43C836F72ECCE6B5A21A213DA0A46164AC1F9A2A8026A390D761E721]}
06-23 11:34:00.092  4622  4622 D [Weather Widget]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,06-23 11:34:02.382  9374  9439 I jxcore-log: 2017-06-23 09:34:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
06-23 11:34:02.382  9374  9439 I jxcore-log: 
,06-23 11:34:02.382  9374  9439 I jxcore-log: 2017-06-23 09:34:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
06-23 11:34:02.382  9374  9439 I jxcore-log: 
06-23 11:34:02.382  9374  9439 I jxcore-log: 2017-06-23 09:34:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
06-23 11:34:02.382  9374  9439 I jxcore-log: 
,06-23 11:34:02.392  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:02.392  9374  9439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-23 11:34:02.392  9374  9439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-23 11:34:02.392  9374  9439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
06-23 11:34:02.392  9374  9439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-23 11:34:02.392  9374  9439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-23 11:34:02.392  9374  9439 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
06-23 11:34:02.392  9374  9439 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
06-23 11:34:02.392  9374  9439 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
06-23 11:34:02.392  9374  9439 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,06-23 11:34:02.392  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:02.402  9374  9439 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,06-23 11:34:02.402  9374  9439 I jxcore-log: 2017-06-23 09:34:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
06-23 11:34:02.402  9374  9439 I jxcore-log: 
,06-23 11:34:02.402  9374  9439 I jxcore-log: 2017-06-23 09:34:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
06-23 11:34:02.402  9374  9439 I jxcore-log: 
06-23 11:34:02.402  9374  9439 I jxcore-log: 2017-06-23 09:34:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
06-23 11:34:02.402  9374  9439 I jxcore-log: 
,06-23 11:34:02.662  9374  9439 D ExecuteNativeTests: Running unit tests
06-23 11:34:02.662  9374  9439 D BluetoothAdapter: enable()
,06-23 11:34:02.672  9374  9439 D BluetoothAdapter: enable(): BT is already enabled..!
,06-23 11:34:02.682  3486  3567 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ba32418 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{714895a 4842:com.samsung.android.providers.context/u0a7}
,06-23 11:34:02.682  9374  9439 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,06-23 11:34:02.692  3486  4379 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,06-23 11:34:02.692  3486  4379 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,06-23 11:34:02.692  3486  4379 D WifiService: setWifiEnabled: true pid=9374, uid=10074
,06-23 11:34:02.692  3486  4379 W ActivityManager: Permission Denial: getCurrentUser() from pid=9374, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
,06-23 11:34:02.702  3486  3849 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,06-23 11:34:02.702  3486  3849 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,06-23 11:34:02.702  3486  4379 W WifiService: Failed getting userId using ActivityManagerNative
06-23 11:34:02.702  3486  4379 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9374, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
06-23 11:34:02.702  3486  4379 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
06-23 11:34:02.702  3486  4379 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
06-23 11:34:02.702  3486  4379 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
06-23 11:34:02.702  3486  4379 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
06-23 11:34:02.702  3486  4379 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
06-23 11:34:02.702  3486  3849 D WifiBigDataLog: init : 
06-23 11:34:02.702  3486  4379 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
06-23 11:34:02.702  3486  4379 D SettingsProvider: isChangeAllowed() : name = wifi_on
,06-23 11:34:02.702  3486  3852 D WifiStateMachine: setFccChannel: channel = -1
06-23 11:34:02.702  3486  3852 D WifiController: [FCC]setFccChannel() is called !!!
06-23 11:34:02.702  3486  3852 D WifiController: [FCC]Airplane off, setFccChannel(-1)!!!
,06-23 11:34:02.702  3486  3849 D WifiStateMachine: setFccChannelNative: channel = -1
,06-23 11:34:02.702  3486  3849 D WifiNative-wlan0: callSECApiInt - ID [230]
,06-23 11:34:02.712  3486  3567 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c05de71 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{714895a 4842:com.samsung.android.providers.context/u0a7}
,06-23 11:34:03.172  3486  4395 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-23 11:34:03.172  3486  4395 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4356, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-23 11:34:03.172  3486  4395 D BatteryService: online:4, current avg:-94, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:237
06-23 11:34:03.172  3486  3486 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-23 11:34:03.172  3486  3486 I MotionRecognitionService: Plugged
,06-23 11:34:03.172  3486  3486 D MotionRecognitionService:   cableConnection= 1
06-23 11:34:03.172  3486  3486 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-23 11:34:03.172  3486  3486 D MotionRecognitionService: skip setTransmitPower. 
,06-23 11:34:03.182  3486  3852 D WifiController: ApOrStaEnabledState  msg.what= 155652
,06-23 11:34:03.182  3928  3928 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-23 11:34:03.182  3928  3928 D KeyguardUpdateMonitor: handleBatteryUpdate
06-23 11:34:03.182  3928  3928 D PowerUI : priorPlugType = 2 mPlugType =  2
,06-23 11:34:03.202  4857  4857 D CommonServiceConfiguration: getStringValueSetting
,06-23 11:34:03.212  4809  4809 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-23 11:34:03.212  4809  5244 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,06-23 11:34:03.222  4857  4857 D BatteryMonitor: new battery level: 100
,06-23 11:34:03.222  3928  3928 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-23 11:34:03.222  3928  3928 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-23 11:34:03.842  3486  3610 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,06-23 11:34:03.872  3486  3610 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,06-23 11:34:04.532  3486  6038 D SSRM:n  : SIOP:: AP = 370, PST = 308 (W:6), CP = 269, CUR = -94, LCD = 40
,06-23 11:34:04.562  3486  6038 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,06-23 11:34:09.322  3486  6077 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-23 11:34:12.712  9374  9439 I com.test.thalitest.ThaliTestRunner: Running UT
,06-23 11:34:12.772  9374  9439 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
06-23 11:34:12.772  9374  9439 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ad7d0c1 added. We now have 2 listener(s)
06-23 11:34:12.772  9374  9439 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ad7d0c1 added. We now have 3 listener(s)
06-23 11:34:12.772  9374  9439 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
06-23 11:34:12.772  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: ", Bluetooth MAC address: "44:78:3E:94:2C:E6"Peer extra info: "256
06-23 11:34:12.772  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
06-23 11:34:12.772  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: null
06-23 11:34:12.772  9374  9439 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
06-23 11:34:12.772  9374  9439 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c4e066 added. We now have 4 listener(s)
06-23 11:34:12.772  9374  9439 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,06-23 11:34:12.772  9374  9439 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,06-23 11:34:12.782  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:12.792  9374  9439 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
,06-23 11:34:12.792  9374  9439 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
06-23 11:34:12.792  9374  9439 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
06-23 11:34:12.792  9374  9439 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
06-23 11:34:12.792  9374  9439 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [00:11:22:33:44:55] timed out
,06-23 11:34:12.792  9374  9439 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
06-23 11:34:12.792  9374  9439 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
06-23 11:34:12.792  9374  9439 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
06-23 11:34:12.792  9374  9439 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,06-23 11:34:12.792  9374  9439 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
,06-23 11:34:12.792  9374  9439 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,06-23 11:34:12.802  9374  9439 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
,06-23 11:34:12.802  9374  9439 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
,06-23 11:34:12.802  9374  9439 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
06-23 11:34:12.802  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,06-23 11:34:12.822  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:12.822  9374  9439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-23 11:34:12.822  9374  9439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-23 11:34:12.822  9374  9439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
06-23 11:34:12.822  9374  9439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-23 11:34:12.822  9374  9439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-23 11:34:12.822  9374  9439 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
06-23 11:34:12.822  9374  9439 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
06-23 11:34:12.822  9374  9439 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
06-23 11:34:12.822  9374  9439 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,06-23 11:34:12.822  9374  9439 D io.jxcore.node.ConnectivityMonitor: start: OK
06-23 11:34:12.822  9374  9439 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 0
06-23 11:34:12.822  9374  9439 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 256 -> 0
06-23 11:34:12.822  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
06-23 11:34:12.832  9374  9374 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-23 11:34:12.832  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":0,"address":"44:78:3E:94:2C:E6"}
06-23 11:34:12.832  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":0,"address":"44:78:3E:94:2C:E6"}
06-23 11:34:12.832  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:12.832  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
06-23 11:34:12.832  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":0,"address":"44:78:3E:94:2C:E6"}
06-23 11:34:12.832  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":0,"address":"44:78:3E:94:2C:E6"}
06-23 11:34:12.832  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:12.832  9374  9439 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
06-23 11:34:12.832  9374  9439 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
06-23 11:34:12.832  9374  9374 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-23 11:34:12.832  9374  9439 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
06-23 11:34:12.842  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
06-23 11:34:12.842  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,06-23 11:34:12.842  9374  9439 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,06-23 11:34:12.842  9374  9439 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
06-23 11:34:12.842  9374  9439 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
06-23 11:34:12.842  9374  9439 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
06-23 11:34:12.842  9374  9444 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
06-23 11:34:12.842  9374  9439 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
06-23 11:34:12.842  9374  9374 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-23 11:34:12.842  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
06-23 11:34:12.842  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
06-23 11:34:12.842  9374  9374 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,06-23 11:34:12.852  9374  9444 D BluetoothSocket: bindListen(): myUserId = 0
,06-23 11:34:12.852  9374  9444 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
06-23 11:34:12.852  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,06-23 11:34:12.852  9374  9439 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
06-23 11:34:12.852  9374  9439 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,06-23 11:34:12.852  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:12.852  9374  9444 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
,06-23 11:34:12.862  9374  9444 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@1cfb7fd, port: 6, type: 1, local socket address: null, socket type: 0
06-23 11:34:12.862  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:12.862  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:12.862  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-139,7,main], id: 139
,06-23 11:34:12.862  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,06-23 11:34:12.872  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:12.872  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:12.872  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,06-23 11:34:12.872  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
06-23 11:34:12.872  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 0
,06-23 11:34:12.872  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:12.882  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-139,7,main], id: 139
,06-23 11:34:12.882  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:12.882  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
06-23 11:34:12.882  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
06-23 11:34:12.882  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "d73bd5ae-6d0d-480b-a594-f51893853407", Bluetooth MAC address: "44:78:3E:94:2C:E6"
06-23 11:34:12.882  9374  9439 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 44 78 3E 94 2C E6
,06-23 11:34:12.882  9374  9439 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[d73bd5ae-6d0d-480b-a594-f51893853407], mManufacturerSpecificData={}, mServiceData={d73bd5ae-6d0d-480b-a594-f51893853407=[0, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,06-23 11:34:12.882  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[d73bd5ae-6d0d-480b-a594-f51893853407], mManufacturerSpecificData={}, mServiceData={d73bd5ae-6d0d-480b-a594-f51893853407=[0, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
06-23 11:34:12.882  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:12.882  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[d73bd5ae-6d0d-480b-a594-f51893853407], mManufacturerSpecificData={}, mServiceData={d73bd5ae-6d0d-480b-a594-f51893853407=[0, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:12.882  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
,06-23 11:34:12.882  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[d73bd5ae-6d0d-480b-a594-f51893853407], mManufacturerSpecificData={}, mServiceData={d73bd5ae-6d0d-480b-a594-f51893853407=[0, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
06-23 11:34:12.882  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:12.882  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:12.882  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[d73bd5ae-6d0d-480b-a594-f51893853407], mManufacturerSpecificData={}, mServiceData={d73bd5ae-6d0d-480b-a594-f51893853407=[0, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-139,7,main], id: 139
,06-23 11:34:12.882  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:12.882  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:12.882  9374  9439 D BluetoothLeAdvertiser: start advertising
06-23 11:34:12.882  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:12.892  4809  5246 D BtGatt.GattService: registerClient() - UUID=89b6d87a-8c1d-476c-8e61-359c1ef9044f
,06-23 11:34:12.942  4809  4976 D BtGatt.GattService: onClientRegistered() - UUID=89b6d87a-8c1d-476c-8e61-359c1ef9044f, clientIf=8
,06-23 11:34:12.952  9374  9385 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=8
,06-23 11:34:12.952  4809  4828 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,06-23 11:34:12.962  4809  4828 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,06-23 11:34:12.962  4809  4828 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
06-23 11:34:12.962  4809  5035 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
06-23 11:34:12.962  4809  5035 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 23, currDate: 23
,06-23 11:34:12.962  4809  5020 D BtGatt.AdvertiseManager: message : 0
,06-23 11:34:12.962  4809  5020 D BtGatt.AdvertiseManager: number of adv instance running = 0
,06-23 11:34:12.962  4809  5020 D BtGatt.AdvertiseManager: size of list is =0
,06-23 11:34:12.972  4809  5020 D BtGatt.AdvertiseManager: starting advertising
,06-23 11:34:12.982  4809  5020 D BtGatt.AdvertiseManager: isStandardAdv = false
,06-23 11:34:12.982  4809  5035 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.thaliproject.thalitest : 28
06-23 11:34:12.982  4809  5035 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.thaliproject.thalitest@LowLatency : 24970174
,06-23 11:34:12.982  4809  5035 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.thaliproject.thalitest@LowLatency : 2
06-23 11:34:12.982  4809  5035 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
06-23 11:34:12.982  4809  5035 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 0 => 0
,06-23 11:34:12.992  3486  4257 V AlarmManager:  remove PendingIntent] PendingIntent{a4e5e30: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:12.992  4809  4976 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=8, status=0
,06-23 11:34:12.992  4809  5020 D BtGatt.AdvertiseManager: starting multi advertising
,06-23 11:34:13.002  3486  3504 V AlarmManager:  remove PendingIntent] PendingIntent{d30eaa9: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:13.002  4809  4976 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=8, status=0
06-23 11:34:13.002  4809  5020 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,06-23 11:34:13.002  4809  5020 D BtGatt.AdvertiseManager: clientIf: 8, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,06-23 11:34:13.002  4809  5020 D BtGatt.AdvertiseManager: postCallback clientIf = 8 status = 0
,06-23 11:34:13.002  4809  5020 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=8, status=0, isStart=true
,06-23 11:34:13.002  9374  9434 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
,06-23 11:34:13.012  3486  3505 V AlarmManager:  remove PendingIntent] PendingIntent{d09982e: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
06-23 11:34:13.002  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-139,7,main], id: 139
,06-23 11:34:13.002  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:13.002  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
06-23 11:34:13.002  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:13.002  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:13.002  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:13.012  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:13.012  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:13.012  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
06-23 11:34:13.012  9374  9439 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
06-23 11:34:13.012  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-139,7,main], id: 139
,06-23 11:34:13.012  3486  4379 V AlarmManager:  remove PendingIntent] PendingIntent{b07ffcf: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:13.022  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-139,7,main], id: 139
,06-23 11:34:13.022  3486  4422 V AlarmManager:  remove PendingIntent] PendingIntent{b732d5c: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
06-23 11:34:13.022  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:13.022  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:13.022  9374  9439 I io.jxcore.node.ConnectionHelper: start: OK
06-23 11:34:13.022  9374  9374 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,06-23 11:34:13.022  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
06-23 11:34:13.022  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
06-23 11:34:13.022  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
06-23 11:34:13.022  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
06-23 11:34:13.022  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
06-23 11:34:13.022  9374  9374 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
06-23 11:34:13.022  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,06-23 11:34:13.022  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
06-23 11:34:13.022  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
06-23 11:34:13.022  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
06-23 11:34:13.022  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
,06-23 11:34:13.022  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
06-23 11:34:13.022  9374  9374 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
06-23 11:34:13.022  9374  9374 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,06-23 11:34:13.032  3486  4049 V AlarmManager:  remove PendingIntent] PendingIntent{9048865: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:13.032  9374  9374 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,06-23 11:34:13.032  9374  9374 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
06-23 11:34:13.032  9374  9374 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
06-23 11:34:13.032  9374  9374 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
06-23 11:34:13.032  9374  9374 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,06-23 11:34:13.032  3486  4435 V AlarmManager:  remove PendingIntent] PendingIntent{b9b093a: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:13.222  3486  4433 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-23 11:34:13.232  3486  4433 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4358, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-23 11:34:13.232  3486  4433 D BatteryService: online:4, current avg:77, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:183
06-23 11:34:13.232  3486  3486 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-23 11:34:13.232  3486  3486 I MotionRecognitionService: Plugged
,06-23 11:34:13.232  3486  3486 D MotionRecognitionService:   cableConnection= 1
06-23 11:34:13.232  3486  3486 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-23 11:34:13.232  3486  3486 D MotionRecognitionService: skip setTransmitPower. 
,06-23 11:34:13.242  3486  3852 D WifiController: ApOrStaEnabledState  msg.what= 155652
,06-23 11:34:13.242  3928  3928 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-23 11:34:13.242  3928  3928 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-23 11:34:13.242  3928  3928 D PowerUI : priorPlugType = 2 mPlugType =  2
,06-23 11:34:13.272  4857  4857 D CommonServiceConfiguration: getStringValueSetting
,06-23 11:34:13.282  4809  4809 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-23 11:34:13.282  3928  3928 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-23 11:34:13.282  3928  3928 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-23 11:34:13.282  4809  5244 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,06-23 11:34:13.292  4857  4857 D BatteryMonitor: new battery level: 100
,06-23 11:34:13.522  9374  9446 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,06-23 11:34:13.522  9374  9439 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,06-23 11:34:13.532  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [00:11:22:33:44:55]
06-23 11:34:13.532  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [10:010:010:010:010:010]
06-23 11:34:13.532  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [11:110:110:110:110:110]
,06-23 11:34:13.532  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [12:210:210:210:210:210]
06-23 11:34:13.532  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [13:310:310:310:310:310]
06-23 11:34:13.532  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [14:410:410:410:410:410]
,06-23 11:34:13.532  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [15:510:510:510:510:510]
06-23 11:34:13.532  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [16:610:610:610:610:610]
06-23 11:34:13.532  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [17:710:710:710:710:710]
06-23 11:34:13.532  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [18:810:810:810:810:810]
06-23 11:34:13.532  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [19:910:910:910:910:910]
,06-23 11:34:13.532  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [20:1010:1010:1010:1010:1010]
06-23 11:34:13.532  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [21:1110:1110:1110:1110:1110]
,06-23 11:34:13.532  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [22:1210:1210:1210:1210:1210]
06-23 11:34:13.532  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [23:1310:1310:1310:1310:1310]
,06-23 11:34:13.532  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [24:1410:1410:1410:1410:1410]
,06-23 11:34:13.532  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [25:1510:1510:1510:1510:1510]
,06-23 11:34:13.532  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [26:1610:1610:1610:1610:1610]
06-23 11:34:13.532  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [27:1710:1710:1710:1710:1710]
06-23 11:34:13.532  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [28:1810:1810:1810:1810:1810]
,06-23 11:34:13.532  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [29:1910:1910:1910:1910:1910]
06-23 11:34:13.532  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [30:2010:2010:2010:2010:2010]
06-23 11:34:13.532  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [31:2110:2110:2110:2110:2110]
06-23 11:34:13.532  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [32:2210:2210:2210:2210:2210]
,06-23 11:34:13.532  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [33:2310:2310:2310:2310:2310]
06-23 11:34:13.532  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [34:2410:2410:2410:2410:2410]
06-23 11:34:13.532  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [35:2510:2510:2510:2510:2510]
06-23 11:34:13.532  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [36:2610:2610:2610:2610:2610]
,06-23 11:34:13.532  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [37:2710:2710:2710:2710:2710]
06-23 11:34:13.532  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [38:2810:2810:2810:2810:2810]
06-23 11:34:13.532  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [39:2910:2910:2910:2910:2910]
06-23 11:34:13.532  9374  9439 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
06-23 11:34:13.532  9374  9439 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,06-23 11:34:13.532  9374  9439 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
06-23 11:34:13.532  9374  9439 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
06-23 11:34:13.532  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,06-23 11:34:13.532  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
06-23 11:34:13.532  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
06-23 11:34:13.532  9374  9439 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
06-23 11:34:13.532  9374  9439 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
06-23 11:34:13.532  9374  9444 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,06-23 11:34:13.532  9374  9444 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
06-23 11:34:13.532  9374  9439 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
06-23 11:34:13.532  9374  9444 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
06-23 11:34:13.532  9374  9439 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,06-23 11:34:13.532  9374  9374 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
06-23 11:34:13.532  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-139,7,main], id: 139
,06-23 11:34:13.532  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
06-23 11:34:13.532  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
06-23 11:34:13.532  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:13.532  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:13.532  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-139,7,main], id: 139
,06-23 11:34:13.532  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:13.542  9374  9439 D BluetoothAdapter: STATE_ON
06-23 11:34:13.552  9374  9439 D BluetoothAdapter: STATE_ON
06-23 11:34:13.552  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
06-23 11:34:13.552  9374  9439 D BluetoothAdapter: STATE_ON
06-23 11:34:13.552  9374  9439 D BluetoothAdapter: STATE_ON
06-23 11:34:13.552  9374  9439 D BluetoothLeScanner: could not find callback wrapper
06-23 11:34:13.552  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
06-23 11:34:13.552  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:13.552  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:13.552  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:13.552  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
06-23 11:34:13.552  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:13.562  9374  9439 D BluetoothAdapter: STATE_ON
06-23 11:34:13.562  9374  9439 D BluetoothAdapter: STATE_ON
06-23 11:34:13.562  9374  9439 D BluetoothLeAdvertiser: stop advertising
06-23 11:34:13.572  4809  5246 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
06-23 11:34:13.572  4809  5246 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
06-23 11:34:13.572  4809  5020 D BtGatt.AdvertiseManager: message : 1
06-23 11:34:13.572  4809  5035 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
06-23 11:34:13.572  4809  5035 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 23, currDate: 23
06-23 11:34:13.572  4809  5035 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
06-23 11:34:13.572  4809  5020 D BtGatt.AdvertiseManager: stop advertise for client =  8
06-23 11:34:13.572  4809  5035 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 0 => 0
06-23 11:34:13.572  4809  5020 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 8
06-23 11:34:13.572  4809  5035 D BtGatt.GattService: [GSIM LOG]: remove : com.thaliproject.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
06-23 11:34:13.572  4809  5020 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
06-23 11:34:13.572  3486  3504 V AlarmManager:  remove PendingIntent] PendingIntent{aaec9eb: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
06-23 11:34:13.572  4809  4976 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=8, status=0
06-23 11:34:13.572  4809  4976 D BtGatt.GattService: Client app is not null!
06-23 11:34:13.582  9374  9385 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
06-23 11:34:13.582  4809  4828 D BtGatt.GattService: unregisterClient() - clientIf=8
06-23 11:34:13.582  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
06-23 11:34:13.582  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:13.582  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
06-23 11:34:13.582  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:13.582  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:13.582  3486  3969 V AlarmManager:  remove PendingIntent] PendingIntent{4b3c348: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
06-23 11:34:13.582  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:13.582  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
06-23 11:34:13.582  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
06-23 11:34:13.582  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
06-23 11:34:13.582  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-139,7,main], id: 139
,06-23 11:34:13.582  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:13.582  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
06-23 11:34:13.582  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:13.582  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:13.592  9374  9374 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
06-23 11:34:13.592  9374  9374 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
06-23 11:34:13.592  9374  9374 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
06-23 11:34:13.592  3486  4422 V AlarmManager:  remove PendingIntent] PendingIntent{7ba45e1: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
06-23 11:34:13.592  9374  9374 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
06-23 11:34:13.592  9374  9374 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
06-23 11:34:13.592  9374  9374 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
06-23 11:34:13.592  9374  9374 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
06-23 11:34:13.592  9374  9374 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
06-23 11:34:13.592  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
06-23 11:34:13.592  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
06-23 11:34:13.592  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
06-23 11:34:13.592  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
06-23 11:34:13.592  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
06-23 11:34:13.592  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
06-23 11:34:13.592  9374  9374 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
06-23 11:34:13.602  3486  3504 V AlarmManager:  remove PendingIntent] PendingIntent{8a07f06: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
06-23 11:34:13.592  9374  9449 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
06-23 11:34:13.602  3486  4128 E Watchdog: !@Sync 6 [06-23 11:34:13.608]
06-23 11:34:13.592  9374  9439 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
06-23 11:34:13.592  9374  9439 V io.jxcore.node.ConnectivityMonitor: start: Already started
06-23 11:34:13.592  9374  9439 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
06-23 11:34:13.592  9374  9439 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
06-23 11:34:13.592  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
06-23 11:34:13.602  3486  4435 V AlarmManager:  remove PendingIntent] PendingIntent{7ae19c7: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
06-23 11:34:13.602  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":1,"address":"44:78:3E:94:2C:E6"}
06-23 11:34:13.602  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":1,"address":"44:78:3E:94:2C:E6"}
06-23 11:34:13.602  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:13.602  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
06-23 11:34:13.612  3486  3975 V AlarmManager:  remove PendingIntent] PendingIntent{7e5cbf4: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
06-23 11:34:13.612  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":1,"address":"44:78:3E:94:2C:E6"}
06-23 11:34:13.612  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":1,"address":"44:78:3E:94:2C:E6"}
06-23 11:34:13.612  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:13.612  9374  9439 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
06-23 11:34:13.612  9374  9439 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
06-23 11:34:13.612  9374  9439 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
06-23 11:34:13.612  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
06-23 11:34:13.612  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
06-23 11:34:13.612  9374  9439 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
06-23 11:34:13.612  9374  9439 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
06-23 11:34:13.612  9374  9439 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
06-23 11:34:13.612  9374  9374 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
06-23 11:34:13.612  9374  9450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
06-23 11:34:13.612  9374  9439 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
06-23 11:34:13.612  9374  9439 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
06-23 11:34:13.612  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
06-23 11:34:13.612  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
06-23 11:34:13.612  3486  4395 V AlarmManager:  remove PendingIntent] PendingIntent{3b45f1d: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
06-23 11:34:13.622  9374  9450 D BluetoothSocket: bindListen(): myUserId = 0
06-23 11:34:13.622  9374  9450 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
06-23 11:34:13.622  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
06-23 11:34:13.622  9374  9439 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
06-23 11:34:13.622  9374  9439 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
06-23 11:34:13.622  9374  9450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
06-23 11:34:13.622  9374  9450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@11c0c9f, port: 6, type: 1, local socket address: null, socket type: 0
06-23 11:34:13.632  9374  9439 D BluetoothAdapter: STATE_ON
06-23 11:34:13.632  9374  9439 D BluetoothAdapter: STATE_ON
06-23 11:34:13.632  3486  3969 V AlarmManager:  remove PendingIntent] PendingIntent{13cd019: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:13.632  9374  9439 D BluetoothAdapter: STATE_ON
06-23 11:34:13.632  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:13.632  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
06-23 11:34:13.632  9374  9439 D BluetoothAdapter: STATE_ON
06-23 11:34:13.632  9374  9439 D BluetoothAdapter: STATE_ON
06-23 11:34:13.632  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
06-23 11:34:13.632  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
06-23 11:34:13.632  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 1
06-23 11:34:13.642  9374  9439 D BluetoothAdapter: STATE_ON
06-23 11:34:13.642  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:13.642  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:13.642  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
06-23 11:34:13.642  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
06-23 11:34:13.642  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "d73bd5ae-6d0d-480b-a594-f51893853407", Bluetooth MAC address: "44:78:3E:94:2C:E6"
06-23 11:34:13.642  9374  9439 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 44 78 3E 94 2C E6
06-23 11:34:13.642  9374  9439 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[d73bd5ae-6d0d-480b-a594-f51893853407], mManufacturerSpecificData={}, mServiceData={d73bd5ae-6d0d-480b-a594-f51893853407=[1, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
06-23 11:34:13.642  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[d73bd5ae-6d0d-480b-a594-f51893853407], mManufacturerSpecificData={}, mServiceData={d73bd5ae-6d0d-480b-a594-f51893853407=[1, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
06-23 11:34:13.642  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:13.642  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[d73bd5ae-6d0d-480b-a594-f51893853407], mManufacturerSpecificData={}, mServiceData={d73bd5ae-6d0d-480b-a594-f51893853407=[1, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:13.642  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
06-23 11:34:13.642  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[d73bd5ae-6d0d-480b-a594-f51893853407], mManufacturerSpecificData={}, mServiceData={d73bd5ae-6d0d-480b-a594-f51893853407=[1, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
06-23 11:34:13.642  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:13.642  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:13.642  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[d73bd5ae-6d0d-480b-a594-f51893853407], mManufacturerSpecificData={}, mServiceData={d73bd5ae-6d0d-480b-a594-f51893853407=[1, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:13.642  9374  9439 D BluetoothAdapter: STATE_ON
06-23 11:34:13.642  9374  9439 D BluetoothAdapter: STATE_ON
06-23 11:34:13.642  9374  9439 D BluetoothLeAdvertiser: start advertising
06-23 11:34:13.642  9374  9439 D BluetoothAdapter: STATE_ON
06-23 11:34:13.652  4809  4830 D BtGatt.GattService: registerClient() - UUID=c1f9b3db-65c8-4c24-93fe-a4add93eab5c
,06-23 11:34:13.692  4809  4976 D BtGatt.GattService: onClientRegistered() - UUID=c1f9b3db-65c8-4c24-93fe-a4add93eab5c, clientIf=8
,06-23 11:34:13.692  9374  9384 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=8
,06-23 11:34:13.692  4809  5345 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,06-23 11:34:13.702  4809  5345 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,06-23 11:34:13.702  4809  5345 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
06-23 11:34:13.702  4809  5020 D BtGatt.AdvertiseManager: message : 0
06-23 11:34:13.702  4809  5035 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
,06-23 11:34:13.702  4809  5035 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 23, currDate: 23
06-23 11:34:13.702  4809  5020 D BtGatt.AdvertiseManager: number of adv instance running = 0
06-23 11:34:13.702  4809  5020 D BtGatt.AdvertiseManager: size of list is =0
,06-23 11:34:13.712  4809  5020 D BtGatt.AdvertiseManager: starting advertising
,06-23 11:34:13.722  4809  5035 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.thaliproject.thalitest : 29
,06-23 11:34:13.722  4809  5035 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.thaliproject.thalitest@LowLatency : 24970174
06-23 11:34:13.722  4809  5020 D BtGatt.AdvertiseManager: isStandardAdv = false
06-23 11:34:13.722  4809  5035 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.thaliproject.thalitest@LowLatency : 2
,06-23 11:34:13.722  4809  5035 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
06-23 11:34:13.722  4809  5035 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 0 => 0
,06-23 11:34:13.722  3486  4434 V AlarmManager:  remove PendingIntent] PendingIntent{aa268de: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:13.732  4809  4976 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=8, status=0
,06-23 11:34:13.732  4809  5020 D BtGatt.AdvertiseManager: starting multi advertising
,06-23 11:34:13.732  4809  4976 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=8, status=0
,06-23 11:34:13.732  3486  3970 V AlarmManager:  remove PendingIntent] PendingIntent{cce7abf: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
06-23 11:34:13.742  4809  5020 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
06-23 11:34:13.742  4809  5020 D BtGatt.AdvertiseManager: clientIf: 8, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
06-23 11:34:13.742  4809  5020 D BtGatt.AdvertiseManager: postCallback clientIf = 8 status = 0
,06-23 11:34:13.742  4809  5020 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=8, status=0, isStart=true
,06-23 11:34:13.742  9374  9434 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
06-23 11:34:13.742  3486  4395 V AlarmManager:  remove PendingIntent] PendingIntent{c0aa58c: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
06-23 11:34:13.742  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:13.742  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-139,7,main], id: 139
,06-23 11:34:13.742  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
06-23 11:34:13.742  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:13.742  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:13.742  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:13.742  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-139,7,main], id: 139
,06-23 11:34:13.742  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:13.742  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
06-23 11:34:13.742  9374  9439 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,06-23 11:34:13.742  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:13.742  9374  9439 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: seems that updateState call different BlePeerDiscoverer
06-23 11:34:13.752  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:13.752  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:13.752  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:13.752  9374  9439 I io.jxcore.node.ConnectionHelper: start: OK
06-23 11:34:13.752  9374  9374 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
06-23 11:34:13.752  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
06-23 11:34:13.752  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
06-23 11:34:13.752  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,06-23 11:34:13.752  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
06-23 11:34:13.752  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
06-23 11:34:13.752  9374  9374 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,06-23 11:34:13.752  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
06-23 11:34:13.752  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
,06-23 11:34:13.752  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
06-23 11:34:13.752  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
06-23 11:34:13.752  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
06-23 11:34:13.752  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
06-23 11:34:13.752  9374  9374 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
06-23 11:34:13.762  9374  9374 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,06-23 11:34:13.762  3486  4049 V AlarmManager:  remove PendingIntent] PendingIntent{54154d5: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:13.762  9374  9374 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,06-23 11:34:13.762  9374  9374 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
06-23 11:34:13.762  9374  9374 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
06-23 11:34:13.762  9374  9374 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,06-23 11:34:13.762  9374  9374 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,06-23 11:34:13.772  3486  3975 V AlarmManager:  remove PendingIntent] PendingIntent{66834ea: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:13.772  3486  4435 V AlarmManager:  remove PendingIntent] PendingIntent{17a03db: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:13.782  3486  3969 V AlarmManager:  remove PendingIntent] PendingIntent{4828e78: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:13.782  3486  4396 V AlarmManager:  remove PendingIntent] PendingIntent{bcf6951: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:14.262  9374  9452 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,06-23 11:34:14.262  9374  9439 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
,06-23 11:34:14.262  9374  9439 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
06-23 11:34:14.262  9374  9439 V io.jxcore.node.ConnectivityMonitor: start: Already started
06-23 11:34:14.262  9374  9439 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
06-23 11:34:14.262  9374  9439 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
,06-23 11:34:14.262  9374  9439 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
06-23 11:34:14.262  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,06-23 11:34:14.272  9374  9374 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,06-23 11:34:14.272  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":2,"address":"44:78:3E:94:2C:E6"}
06-23 11:34:14.272  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":2,"address":"44:78:3E:94:2C:E6"}
06-23 11:34:14.272  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:14.272  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,06-23 11:34:14.282  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":2,"address":"44:78:3E:94:2C:E6"}
,06-23 11:34:14.282  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":2,"address":"44:78:3E:94:2C:E6"}
06-23 11:34:14.282  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:14.282  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
06-23 11:34:14.282  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 53944
06-23 11:34:14.282  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
06-23 11:34:14.282  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 2
06-23 11:34:14.282  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
06-23 11:34:14.282  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
06-23 11:34:14.282  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
06-23 11:34:14.282  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
06-23 11:34:14.282  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
06-23 11:34:14.282  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:14.282  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 2
06-23 11:34:14.282  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted true Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:14.282  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop advertiser Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:14.282  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-139,7,main], id: 139
,06-23 11:34:14.282  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:14.282  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:14.282  9374  9439 D BluetoothLeAdvertiser: stop advertising
,06-23 11:34:14.292  4809  5246 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,06-23 11:34:14.292  4809  5246 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
06-23 11:34:14.292  4809  5020 D BtGatt.AdvertiseManager: message : 1
06-23 11:34:14.292  4809  5035 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
06-23 11:34:14.292  4809  5035 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 23, currDate: 23
,06-23 11:34:14.292  4809  5035 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
06-23 11:34:14.292  4809  5035 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 0 => 0
06-23 11:34:14.292  4809  5035 D BtGatt.GattService: [GSIM LOG]: remove : com.thaliproject.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
06-23 11:34:14.292  4809  5020 D BtGatt.AdvertiseManager: stop advertise for client =  8
,06-23 11:34:14.292  4809  5020 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 8
06-23 11:34:14.292  4809  5020 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,06-23 11:34:14.292  3486  4422 V AlarmManager:  remove PendingIntent] PendingIntent{f0cb5b6: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:14.302  4809  4976 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=8, status=0
,06-23 11:34:14.302  4809  4976 D BtGatt.GattService: Client app is not null!
06-23 11:34:14.302  9374  9385 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,06-23 11:34:14.302  4809  4828 D BtGatt.GattService: unregisterClient() - clientIf=8
,06-23 11:34:14.302  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
06-23 11:34:14.302  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:14.302  3486  4396 V AlarmManager:  remove PendingIntent] PendingIntent{88b02b7: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
06-23 11:34:14.302  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
06-23 11:34:14.302  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:14.302  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:14.302  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:14.302  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
06-23 11:34:14.302  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser Current thread: Thread[Thread-139,7,main], id: 139
,06-23 11:34:14.302  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:14.302  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:14.302  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
06-23 11:34:14.302  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
06-23 11:34:14.302  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "d73bd5ae-6d0d-480b-a594-f51893853407", Bluetooth MAC address: "44:78:3E:94:2C:E6"
06-23 11:34:14.302  9374  9439 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 44 78 3E 94 2C E6
,06-23 11:34:14.302  9374  9439 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[d73bd5ae-6d0d-480b-a594-f51893853407], mManufacturerSpecificData={}, mServiceData={d73bd5ae-6d0d-480b-a594-f51893853407=[2, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
06-23 11:34:14.302  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[d73bd5ae-6d0d-480b-a594-f51893853407], mManufacturerSpecificData={}, mServiceData={d73bd5ae-6d0d-480b-a594-f51893853407=[2, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
06-23 11:34:14.302  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:14.302  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[d73bd5ae-6d0d-480b-a594-f51893853407], mManufacturerSpecificData={}, mServiceData={d73bd5ae-6d0d-480b-a594-f51893853407=[2, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:14.302  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
06-23 11:34:14.302  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[d73bd5ae-6d0d-480b-a594-f51893853407], mManufacturerSpecificData={}, mServiceData={d73bd5ae-6d0d-480b-a594-f51893853407=[2, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
06-23 11:34:14.302  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:14.302  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:14.302  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[d73bd5ae-6d0d-480b-a594-f51893853407], mManufacturerSpecificData={}, mServiceData={d73bd5ae-6d0d-480b-a594-f51893853407=[2, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:14.302  9374  9439 D BluetoothAdapter: STATE_ON
06-23 11:34:14.312  9374  9439 D BluetoothAdapter: STATE_ON
06-23 11:34:14.312  9374  9439 D BluetoothLeAdvertiser: start advertising
06-23 11:34:14.312  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:14.312  3486  4258 V AlarmManager:  remove PendingIntent] PendingIntent{e8e1a24: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:14.312  3486  4434 V AlarmManager:  remove PendingIntent] PendingIntent{a50498d: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:14.312  4809  5345 D BtGatt.GattService: registerClient() - UUID=3267a723-74f7-4f0e-8c4d-6ebda71e3639
,06-23 11:34:14.322  3486  4257 V AlarmManager:  remove PendingIntent] PendingIntent{aa67742: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:14.322  3486  4049 V AlarmManager:  remove PendingIntent] PendingIntent{431353: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:14.332  3486  3975 V AlarmManager:  remove PendingIntent] PendingIntent{1a4b490: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:14.332  3486  4435 V AlarmManager:  remove PendingIntent] PendingIntent{984f189: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:14.362  4809  4976 D BtGatt.GattService: onClientRegistered() - UUID=3267a723-74f7-4f0e-8c4d-6ebda71e3639, clientIf=8
,06-23 11:34:14.362  9374  9384 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=8
,06-23 11:34:14.362  4809  5246 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,06-23 11:34:14.362  4809  5246 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
06-23 11:34:14.362  4809  5246 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,06-23 11:34:14.362  4809  5020 D BtGatt.AdvertiseManager: message : 0
06-23 11:34:14.362  4809  5035 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
06-23 11:34:14.362  4809  5035 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 23, currDate: 23
,06-23 11:34:14.362  4809  5020 D BtGatt.AdvertiseManager: number of adv instance running = 0
06-23 11:34:14.362  4809  5020 D BtGatt.AdvertiseManager: size of list is =0
,06-23 11:34:14.372  4809  5020 D BtGatt.AdvertiseManager: starting advertising
,06-23 11:34:14.372  4809  5020 D BtGatt.AdvertiseManager: isStandardAdv = false
,06-23 11:34:14.372  4809  5035 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.thaliproject.thalitest : 30
,06-23 11:34:14.372  4809  5035 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.thaliproject.thalitest@LowLatency : 24970174
06-23 11:34:14.372  4809  5035 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.thaliproject.thalitest@LowLatency : 2
,06-23 11:34:14.372  3486  3970 V AlarmManager:  remove PendingIntent] PendingIntent{828c58e: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
06-23 11:34:14.372  4809  5035 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
06-23 11:34:14.372  4809  5035 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 0 => 0
,06-23 11:34:14.372  4809  4976 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=8, status=0
,06-23 11:34:14.382  4809  5020 D BtGatt.AdvertiseManager: starting multi advertising
,06-23 11:34:14.382  4809  4976 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=8, status=0
,06-23 11:34:14.382  4809  5020 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,06-23 11:34:14.382  3486  3969 V AlarmManager:  remove PendingIntent] PendingIntent{f6191af: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
06-23 11:34:14.382  4809  5020 D BtGatt.AdvertiseManager: clientIf: 8, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
06-23 11:34:14.382  4809  5020 D BtGatt.AdvertiseManager: postCallback clientIf = 8 status = 0
,06-23 11:34:14.382  4809  5020 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=8, status=0, isStart=true
06-23 11:34:14.382  9374  9434 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
06-23 11:34:14.382  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:14.382  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-139,7,main], id: 139
,06-23 11:34:14.382  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
06-23 11:34:14.382  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:14.382  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:14.382  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-139,7,main], id: 139
,06-23 11:34:14.382  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:14.382  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:14.382  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser started = true Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:14.382  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
06-23 11:34:14.382  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted false Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:14.382  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
06-23 11:34:14.382  9374  9439 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
06-23 11:34:14.382  9374  9439 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
06-23 11:34:14.382  9374  9439 I io.jxcore.node.ConnectionHelper: start: OK
06-23 11:34:14.382  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
06-23 11:34:14.382  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
06-23 11:34:14.382  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
06-23 11:34:14.382  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
,06-23 11:34:14.382  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
06-23 11:34:14.382  9374  9374 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
06-23 11:34:14.382  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
06-23 11:34:14.382  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
06-23 11:34:14.382  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
06-23 11:34:14.382  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
06-23 11:34:14.382  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
06-23 11:34:14.392  3486  4396 V AlarmManager:  remove PendingIntent] PendingIntent{34889bc: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:14.382  9374  9454 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
06-23 11:34:14.382  9374  9439 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
06-23 11:34:14.382  9374  9439 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
06-23 11:34:14.382  9374  9439 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
06-23 11:34:14.382  9374  9439 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
06-23 11:34:14.382  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
06-23 11:34:14.382  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,06-23 11:34:14.382  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
06-23 11:34:14.382  9374  9439 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
06-23 11:34:14.382  9374  9439 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
06-23 11:34:14.382  9374  9439 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
06-23 11:34:14.382  9374  9439 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,06-23 11:34:14.382  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:14.382  9374  9450 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
06-23 11:34:14.382  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
06-23 11:34:14.382  9374  9450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
06-23 11:34:14.382  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,06-23 11:34:14.382  9374  9450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
06-23 11:34:14.382  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:14.382  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:14.392  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-139,7,main], id: 139
,06-23 11:34:14.392  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:14.392  9374  9374 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
06-23 11:34:14.392  9374  9439 D BluetoothAdapter: STATE_ON
06-23 11:34:14.392  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:14.392  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
06-23 11:34:14.392  9374  9439 D BluetoothAdapter: STATE_ON
06-23 11:34:14.392  9374  9439 D BluetoothAdapter: STATE_ON
06-23 11:34:14.392  9374  9439 D BluetoothLeScanner: could not find callback wrapper
06-23 11:34:14.392  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
06-23 11:34:14.392  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-139,7,main], id: 139
,06-23 11:34:14.392  3486  4435 V AlarmManager:  remove PendingIntent] PendingIntent{3421d45: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
06-23 11:34:14.392  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:14.392  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:14.392  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,06-23 11:34:14.392  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:14.392  9374  9439 D BluetoothAdapter: STATE_ON
06-23 11:34:14.402  9374  9439 D BluetoothAdapter: STATE_ON
06-23 11:34:14.402  9374  9439 D BluetoothLeAdvertiser: stop advertising
,06-23 11:34:14.402  4809  5345 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,06-23 11:34:14.402  4809  5345 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
06-23 11:34:14.402  4809  5020 D BtGatt.AdvertiseManager: message : 1
06-23 11:34:14.402  4809  5035 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
06-23 11:34:14.402  4809  5035 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 23, currDate: 23
06-23 11:34:14.402  4809  5035 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
06-23 11:34:14.402  4809  5035 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 0 => 0
,06-23 11:34:14.402  4809  5035 D BtGatt.GattService: [GSIM LOG]: remove : com.thaliproject.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
06-23 11:34:14.402  4809  5020 D BtGatt.AdvertiseManager: stop advertise for client =  8
06-23 11:34:14.402  4809  5020 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 8
06-23 11:34:14.402  3486  4285 V AlarmManager:  remove PendingIntent] PendingIntent{6fac9a: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:14.402  4809  5020 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,06-23 11:34:14.412  4809  4976 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=8, status=0
,06-23 11:34:14.412  4809  4976 D BtGatt.GattService: Client app is not null!
06-23 11:34:14.412  9374  9385 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,06-23 11:34:14.412  4809  5246 D BtGatt.GattService: unregisterClient() - clientIf=8
,06-23 11:34:14.412  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,06-23 11:34:14.412  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:14.412  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
06-23 11:34:14.412  3486  4435 V AlarmManager:  remove PendingIntent] PendingIntent{f3f99cb: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:14.412  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:14.412  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:14.412  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-139,7,main], id: 139
,06-23 11:34:14.412  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
06-23 11:34:14.412  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
06-23 11:34:14.412  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
06-23 11:34:14.412  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:14.412  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:14.412  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
06-23 11:34:14.412  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:14.412  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:14.412  9374  9374 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
06-23 11:34:14.412  9374  9374 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
06-23 11:34:14.412  9374  9374 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
06-23 11:34:14.412  9374  9374 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
06-23 11:34:14.412  9374  9374 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,06-23 11:34:14.412  9374  9374 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
06-23 11:34:14.412  9374  9374 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
06-23 11:34:14.412  3486  3969 V AlarmManager:  remove PendingIntent] PendingIntent{cf285a8: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
06-23 11:34:14.412  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
06-23 11:34:14.412  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
06-23 11:34:14.412  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
06-23 11:34:14.412  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
06-23 11:34:14.412  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
06-23 11:34:14.412  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
06-23 11:34:14.412  9374  9374 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
06-23 11:34:14.412  9374  9455 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
06-23 11:34:14.422  9374  9439 I io.jxcore.node.ConnectionHelperTest: Starting test: testListenToConnectivityChanges
06-23 11:34:14.422  9374  9439 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
06-23 11:34:14.422  9374  9439 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4556c31 added. We now have 3 listener(s)
06-23 11:34:14.422  9374  9439 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4556c31 added. We now have 5 listener(s)
06-23 11:34:14.422  9374  9439 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,06-23 11:34:14.422  3486  3504 V AlarmManager:  remove PendingIntent] PendingIntent{fec48c1: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:14.422  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":2,"address":"44:78:3E:94:2C:E6"}
,06-23 11:34:14.422  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
06-23 11:34:14.422  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":2,"address":"44:78:3E:94:2C:E6"}
06-23 11:34:14.422  9374  9439 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,06-23 11:34:14.422  9374  9439 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3c2f16 added. We now have 6 listener(s)
06-23 11:34:14.422  9374  9439 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
06-23 11:34:14.422  9374  9439 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,06-23 11:34:14.422  3486  4422 V AlarmManager:  remove PendingIntent] PendingIntent{c0bf866: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:14.432  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,06-23 11:34:14.432  3486  4395 V AlarmManager:  remove PendingIntent] PendingIntent{9cf34f2: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:14.432  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:14.442  3486  3504 V AlarmManager:  remove PendingIntent] PendingIntent{4877743: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:14.442  9374  9439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-23 11:34:14.442  9374  9439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-23 11:34:14.442  9374  9439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
06-23 11:34:14.442  9374  9439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-23 11:34:14.442  9374  9439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-23 11:34:14.442  9374  9439 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
06-23 11:34:14.442  9374  9439 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
06-23 11:34:14.442  9374  9439 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
06-23 11:34:14.442  9374  9439 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
06-23 11:34:14.442  9374  9439 D io.jxcore.node.ConnectivityMonitor: start: OK
06-23 11:34:14.442  3486  4379 V AlarmManager:  remove PendingIntent] PendingIntent{4d661c0: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
06-23 11:34:14.442  9374  9374 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-23 11:34:14.452  3486  3504 V AlarmManager:  remove PendingIntent] PendingIntent{b904ef9: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
06-23 11:34:14.452  9374  9439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-23 11:34:14.452  3486  4379 V AlarmManager:  remove PendingIntent] PendingIntent{217ae3e: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
06-23 11:34:14.452  9374  9374 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-23 11:34:14.462  3486  4049 V AlarmManager:  remove PendingIntent] PendingIntent{d20449f: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
06-23 11:34:14.462  9374  9374 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-23 11:34:14.462  3486  4379 V AlarmManager:  remove PendingIntent] PendingIntent{d9fd9ec: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
06-23 11:34:14.462  9374  9439 D BluetoothAdapter: STATE_ON
06-23 11:34:14.472  9374  9439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-23 11:34:14.472  9374  9439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-23 11:34:14.472  9374  9439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
06-23 11:34:14.472  9374  9439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-23 11:34:14.472  9374  9439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-23 11:34:14.472  9374  9439 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
06-23 11:34:14.472  9374  9439 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
06-23 11:34:14.472  9374  9439 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
06-23 11:34:14.472  9374  9439 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
06-23 11:34:14.472  9374  9439 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
06-23 11:34:14.472  9374  9439 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
06-23 11:34:14.472  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
06-23 11:34:14.472  9374  9439 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
06-23 11:34:14.472  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
06-23 11:34:14.472  9374  9439 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4556c31 removed from the list
06-23 11:34:14.472  9374  9439 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4556c31 removed from the list
06-23 11:34:14.472  9374  9439 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
06-23 11:34:14.472  9374  9439 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3c2f16 removed from the list
06-23 11:34:14.472  9374  9439 D io.jxcore.node.ConnectivityMonitor: stop
06-23 11:34:14.472  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
06-23 11:34:14.472  9374  9439 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
06-23 11:34:14.472  9374  9439 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
06-23 11:34:14.472  9374  9439 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
06-23 11:34:14.472  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [incoming]
06-23 11:34:14.472  9374  9439 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
06-23 11:34:14.472  9374  9439 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
06-23 11:34:14.472  9374  9439 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
06-23 11:34:14.472  9374  9439 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
06-23 11:34:14.472  9374  9439 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
06-23 11:34:14.472  9374  9439 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
06-23 11:34:14.472  9374  9439 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
06-23 11:34:14.472  9374  9439 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
06-23 11:34:14.472  9374  9439 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
06-23 11:34:14.482  9374  9439 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
06-23 11:34:14.482  9374  9439 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
06-23 11:34:14.482  9374  9439 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
06-23 11:34:14.482  9374  9439 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
06-23 11:34:14.482  9374  9439 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,06-23 11:34:14.482  9374  9439 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
06-23 11:34:14.482  9374  9439 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
06-23 11:34:14.482  9374  9439 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
06-23 11:34:14.482  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [00:11:22:33:44:55]
06-23 11:34:14.482  9374  9439 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,06-23 11:34:14.482  9374  9439 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
06-23 11:34:14.482  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [10:010:010:010:010:010]
06-23 11:34:14.482  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [11:110:110:110:110:110]
06-23 11:34:14.482  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [12:210:210:210:210:210]
06-23 11:34:14.482  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [13:310:310:310:310:310]
06-23 11:34:14.482  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [14:410:410:410:410:410]
,06-23 11:34:14.482  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [15:510:510:510:510:510]
06-23 11:34:14.482  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [16:610:610:610:610:610]
06-23 11:34:14.482  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [17:710:710:710:710:710]
06-23 11:34:14.482  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [18:810:810:810:810:810]
06-23 11:34:14.482  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [19:910:910:910:910:910]
06-23 11:34:14.482  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [20:1010:1010:1010:1010:1010]
06-23 11:34:14.482  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [21:1110:1110:1110:1110:1110]
06-23 11:34:14.482  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [22:1210:1210:1210:1210:1210]
06-23 11:34:14.482  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [23:1310:1310:1310:1310:1310]
06-23 11:34:14.482  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [24:1410:1410:1410:1410:1410]
06-23 11:34:14.482  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [25:1510:1510:1510:1510:1510]
06-23 11:34:14.482  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [26:1610:1610:1610:1610:1610]
06-23 11:34:14.482  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [27:1710:1710:1710:1710:1710]
06-23 11:34:14.482  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [28:1810:1810:1810:1810:1810]
06-23 11:34:14.482  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [29:1910:1910:1910:1910:1910]
06-23 11:34:14.482  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [30:2010:2010:2010:2010:2010]
06-23 11:34:14.482  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [31:2110:2110:2110:2110:2110]
06-23 11:34:14.482  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [32:2210:2210:2210:2210:2210]
06-23 11:34:14.482  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [33:2310:2310:2310:2310:2310]
06-23 11:34:14.482  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [34:2410:2410:2410:2410:2410]
06-23 11:34:14.482  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [35:2510:2510:2510:2510:2510]
06-23 11:34:14.482  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [36:2610:2610:2610:2610:2610]
06-23 11:34:14.482  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [37:2710:2710:2710:2710:2710]
06-23 11:34:14.482  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [38:2810:2810:2810:2810:2810]
06-23 11:34:14.482  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [39:2910:2910:2910:2910:2910]
06-23 11:34:14.482  9374  9439 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
06-23 11:34:14.482  9374  9439 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
06-23 11:34:14.482  9374  9439 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
06-23 11:34:14.482  9374  9439 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
06-23 11:34:14.482  9374  9439 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
06-23 11:34:14.482  9374  9439 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
06-23 11:34:14.482  9374  9439 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
06-23 11:34:14.482  9374  9439 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
06-23 11:34:14.482  9374  9439 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [00:11:22:33:44:55]
,06-23 11:34:14.492  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,06-23 11:34:14.492  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port 1
06-23 11:34:14.492  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,06-23 11:34:14.492  9374  9439 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,06-23 11:34:14.492  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,06-23 11:34:14.492  9374  9439 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
06-23 11:34:14.492  9374  9439 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,06-23 11:34:14.492  9374  9439 E io.jxcore.node.ConnectionHelper: connect: Callback is null
06-23 11:34:14.492  9374  9456 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 211)
,06-23 11:34:14.492  9374  9456 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect: mIsShuttingDown = false
06-23 11:34:14.492  9374  9456 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: createBluetoothSocket 1
06-23 11:34:14.492  9374  9456 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: createBluetoothSocket: given port
06-23 11:34:14.492  9374  9439 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
,06-23 11:34:14.492  9374  9439 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
06-23 11:34:14.492  9374  9439 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
06-23 11:34:14.492  9374  9439 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,06-23 11:34:14.492  9374  9439 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
06-23 11:34:14.492  9374  9439 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
06-23 11:34:14.502  9374  9439 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
06-23 11:34:14.502  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,06-23 11:34:14.502  9374  9439 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
06-23 11:34:14.502  9374  9439 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
06-23 11:34:14.502  9374  9439 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
06-23 11:34:14.502  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
06-23 11:34:14.502  9374  9439 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
06-23 11:34:14.502  9374  9439 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
06-23 11:34:14.502  9374  9439 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
06-23 11:34:14.502  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
06-23 11:34:14.502  9374  9439 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
06-23 11:34:14.502  9374  9439 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
,06-23 11:34:14.502  9374  9439 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
06-23 11:34:14.502  9374  9439 V io.jxcore.node.ConnectivityMonitor: start: Already started
06-23 11:34:14.502  9374  9439 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
06-23 11:34:14.502  9374  9439 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
06-23 11:34:14.502  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,06-23 11:34:14.502  9374  9456 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: createBluetoothSocketToServiceRecord: Socket created with channel/port 1
06-23 11:34:14.502  9374  9456 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  connect: connecting
,06-23 11:34:14.502  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"44:78:3E:94:2C:E6"}
,06-23 11:34:14.502  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"44:78:3E:94:2C:E6"}
,06-23 11:34:14.502  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:14.502  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,06-23 11:34:14.502  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"44:78:3E:94:2C:E6"}
06-23 11:34:14.502  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"44:78:3E:94:2C:E6"}
,06-23 11:34:14.502  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:14.502  9374  9439 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,06-23 11:34:14.502  9374  9439 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
06-23 11:34:14.502  9374  9439 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
06-23 11:34:14.502  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
06-23 11:34:14.512  9374  9456 D BluetoothSocket: connect(): myUserId = 0
06-23 11:34:14.512  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,06-23 11:34:14.512  9374  9456 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
06-23 11:34:14.512  9374  9439 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
06-23 11:34:14.512  9374  9439 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
06-23 11:34:14.512  9374  9439 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
06-23 11:34:14.512  9374  9439 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
06-23 11:34:14.512  9374  9439 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
06-23 11:34:14.512  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
06-23 11:34:14.512  9374  9374 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
06-23 11:34:14.512  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,06-23 11:34:14.512  9374  9457 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
06-23 11:34:14.512  9374  9457 D BluetoothSocket: bindListen(): myUserId = 0
06-23 11:34:14.512  9374  9457 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,06-23 11:34:14.522  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,06-23 11:34:14.522  9374  9439 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
06-23 11:34:14.522  9374  9439 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,06-23 11:34:14.522  9374  9457 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
,06-23 11:34:14.522  9374  9457 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@7e39a6d, port: 6, type: 1, local socket address: null, socket type: 0
06-23 11:34:14.522  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:14.532  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:14.532  3486  4379 D SecContentProvider: insert(), uri = 2
,06-23 11:34:14.532  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:14.532  4809  5178 W bt_btif : bta_dm_acl_change(), event : 2
,06-23 11:34:14.532  3486  4433 V AlarmManager:  remove PendingIntent] PendingIntent{ea6a8d8: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:14.542  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-139,7,main], id: 139
,06-23 11:34:14.542  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
06-23 11:34:14.542  9374  9439 D BluetoothAdapter: STATE_ON
06-23 11:34:14.542  3486  3504 V AlarmManager:  remove PendingIntent] PendingIntent{377e431: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
06-23 11:34:14.542  9374  9439 D BluetoothAdapter: STATE_ON
06-23 11:34:14.542  3486  4285 V AlarmManager:  remove PendingIntent] PendingIntent{794716: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:14.542  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
06-23 11:34:14.542  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
06-23 11:34:14.542  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 3
,06-23 11:34:14.542  9374  9439 D BluetoothAdapter: STATE_ON
06-23 11:34:14.542  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:14.542  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:14.542  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
06-23 11:34:14.542  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
,06-23 11:34:14.542  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "d73bd5ae-6d0d-480b-a594-f51893853407", Bluetooth MAC address: "44:78:3E:94:2C:E6"
06-23 11:34:14.542  9374  9439 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 44 78 3E 94 2C E6
06-23 11:34:14.542  9374  9439 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[d73bd5ae-6d0d-480b-a594-f51893853407], mManufacturerSpecificData={}, mServiceData={d73bd5ae-6d0d-480b-a594-f51893853407=[3, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
06-23 11:34:14.542  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[d73bd5ae-6d0d-480b-a594-f51893853407], mManufacturerSpecificData={}, mServiceData={d73bd5ae-6d0d-480b-a594-f51893853407=[3, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
06-23 11:34:14.542  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-139,7,main], id: 139
,06-23 11:34:14.542  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[d73bd5ae-6d0d-480b-a594-f51893853407], mManufacturerSpecificData={}, mServiceData={d73bd5ae-6d0d-480b-a594-f51893853407=[3, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:14.542  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
06-23 11:34:14.552  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[d73bd5ae-6d0d-480b-a594-f51893853407], mManufacturerSpecificData={}, mServiceData={d73bd5ae-6d0d-480b-a594-f51893853407=[3, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
06-23 11:34:14.552  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-139,7,main], id: 139
,06-23 11:34:14.552  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:14.552  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[d73bd5ae-6d0d-480b-a594-f51893853407], mManufacturerSpecificData={}, mServiceData={d73bd5ae-6d0d-480b-a594-f51893853407=[3, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:14.552  9374  9439 D BluetoothAdapter: STATE_ON
06-23 11:34:14.552  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:14.552  9374  9439 D BluetoothLeAdvertiser: start advertising
06-23 11:34:14.552  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:14.552  4809  4828 D BtGatt.GattService: registerClient() - UUID=e6030f26-1745-4323-bebd-62e34979fc7f
,06-23 11:34:14.582  3486  6038 D SSRM:n  : SIOP:: AP = 330, PST = 318 (W:14), CP = 270, CUR = 77, LCD = 40
,06-23 11:34:14.592  4809  4976 D BtGatt.GattService: onClientRegistered() - UUID=e6030f26-1745-4323-bebd-62e34979fc7f, clientIf=8
,06-23 11:34:14.592  9374  9384 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=8
,06-23 11:34:14.602  4809  5246 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,06-23 11:34:14.602  4809  5246 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
06-23 11:34:14.602  4809  5246 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,06-23 11:34:14.602  4809  5020 D BtGatt.AdvertiseManager: message : 0
06-23 11:34:14.602  4809  5035 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
06-23 11:34:14.602  4809  5035 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 23, currDate: 23
,06-23 11:34:14.602  4809  5020 D BtGatt.AdvertiseManager: number of adv instance running = 0
06-23 11:34:14.602  4809  5020 D BtGatt.AdvertiseManager: size of list is =0
,06-23 11:34:14.602  4809  5020 D BtGatt.AdvertiseManager: starting advertising
,06-23 11:34:14.612  4809  5020 D BtGatt.AdvertiseManager: isStandardAdv = false
,06-23 11:34:14.612  4809  5035 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.thaliproject.thalitest : 31
,06-23 11:34:14.612  4809  5035 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.thaliproject.thalitest@LowLatency : 24970174
06-23 11:34:14.612  4809  5035 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.thaliproject.thalitest@LowLatency : 2
06-23 11:34:14.612  4809  5035 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
06-23 11:34:14.612  4809  5035 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 0 => 0
,06-23 11:34:14.612  3486  3505 V AlarmManager:  remove PendingIntent] PendingIntent{8502897: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:14.612  4809  4976 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=8, status=0
06-23 11:34:14.612  4809  5020 D BtGatt.AdvertiseManager: starting multi advertising
,06-23 11:34:14.612  4809  4976 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=8, status=0
,06-23 11:34:14.612  3486  4258 V AlarmManager:  remove PendingIntent] PendingIntent{2497a84: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
06-23 11:34:14.612  4809  5020 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
06-23 11:34:14.612  4809  5020 D BtGatt.AdvertiseManager: clientIf: 8, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
06-23 11:34:14.612  4809  5020 D BtGatt.AdvertiseManager: postCallback clientIf = 8 status = 0
,06-23 11:34:14.612  4809  5020 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=8, status=0, isStart=true
,06-23 11:34:14.612  9374  9385 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
06-23 11:34:14.612  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:14.612  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:14.612  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
06-23 11:34:14.612  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-139,7,main], id: 139
,06-23 11:34:14.612  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:14.612  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:14.612  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:14.612  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-139,7,main], id: 139
,06-23 11:34:14.612  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
06-23 11:34:14.622  9374  9439 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
06-23 11:34:14.622  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:14.622  9374  9439 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: seems that updateState call different BlePeerDiscoverer
,06-23 11:34:14.622  3486  4257 V AlarmManager:  remove PendingIntent] PendingIntent{2b5926d: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:14.622  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:14.622  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:14.622  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:14.622  9374  9439 I io.jxcore.node.ConnectionHelper: start: OK
06-23 11:34:14.622  9374  9374 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
06-23 11:34:14.622  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,06-23 11:34:14.622  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
06-23 11:34:14.622  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
06-23 11:34:14.622  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
06-23 11:34:14.622  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
06-23 11:34:14.622  9374  9374 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
06-23 11:34:14.622  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,06-23 11:34:14.622  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
06-23 11:34:14.622  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
06-23 11:34:14.622  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
06-23 11:34:14.622  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
06-23 11:34:14.622  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
06-23 11:34:14.622  9374  9374 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
06-23 11:34:14.622  9374  9374 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,06-23 11:34:14.622  9374  9374 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,06-23 11:34:14.622  9374  9374 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
06-23 11:34:14.622  9374  9374 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
06-23 11:34:14.622  9374  9374 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
06-23 11:34:14.622  9374  9374 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,06-23 11:34:14.622  3486  3505 V AlarmManager:  remove PendingIntent] PendingIntent{73abea2: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:14.632  3486  4379 V AlarmManager:  remove PendingIntent] PendingIntent{d64b733: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:14.632  3486  3975 V AlarmManager:  remove PendingIntent] PendingIntent{825baf0: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:14.632  3486  4433 V AlarmManager:  remove PendingIntent] PendingIntent{ca5e869: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:14.642  3486  4422 V AlarmManager:  remove PendingIntent] PendingIntent{9aa22ee: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:14.792  4339  4428 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-23 11:34:14.792  4339  4428 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-23 11:34:14.872  4339  4428 E ContactsProvider_EventLog: Flush buffer to file cnt : 4 size : 1Kb duration : 72ms lastUpdatedAfter : 129362ms
,06-23 11:34:15.122  9374  9446 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
06-23 11:34:15.122  9374  9439 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
06-23 11:34:15.122  9374  9439 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
06-23 11:34:15.122  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
06-23 11:34:15.122  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
06-23 11:34:15.122  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
06-23 11:34:15.122  9374  9439 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
06-23 11:34:15.122  9374  9439 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
06-23 11:34:15.122  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
06-23 11:34:15.122  9374  9457 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
06-23 11:34:15.122  9374  9457 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
06-23 11:34:15.122  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
06-23 11:34:15.122  9374  9457 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
06-23 11:34:15.122  9374  9374 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,06-23 11:34:15.122  9374  9439 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ad7d0c1 removed from the list
,06-23 11:34:15.122  9374  9374 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,06-23 11:34:15.122  9374  9439 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ad7d0c1 removed from the list
,06-23 11:34:15.122  9374  9439 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,06-23 11:34:15.122  9374  9374 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
06-23 11:34:15.122  9374  9439 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,06-23 11:34:15.122  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:15.122  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
06-23 11:34:15.122  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
06-23 11:34:15.122  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-139,7,main], id: 139
,06-23 11:34:15.122  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:15.122  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:15.132  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:15.132  9374  9374 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,06-23 11:34:15.132  9374  9459 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 211
06-23 11:34:15.132  9374  9459 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
06-23 11:34:15.132  9374  9459 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: closeBluetoothSocket: Trying to close the bluetooth socket... (thread ID: 211)
06-23 11:34:15.132  9374  9459 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: closeBluetoothSocket: bluetooth socket closed (thread ID: 211)
,06-23 11:34:15.132  4809  5323 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 8, channel: 1
06-23 11:34:15.132  9374  9439 D BluetoothAdapter: STATE_ON
06-23 11:34:15.132  9374  9439 D BluetoothAdapter: STATE_ON
06-23 11:34:15.132  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,06-23 11:34:15.132  9374  9456 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  connect: read failed, socket might closed or timeout, read ret: -1
06-23 11:34:15.132  9374  9456 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socket is not connected
06-23 11:34:15.132  9374  9456 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 211)
06-23 11:34:15.132  9374  9439 D BluetoothAdapter: STATE_ON
06-23 11:34:15.132  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:15.132  9374  9439 D BluetoothLeScanner: could not find callback wrapper
06-23 11:34:15.132  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
06-23 11:34:15.132  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:15.132  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:15.132  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-139,7,main], id: 139
,06-23 11:34:15.132  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
06-23 11:34:15.132  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:15.142  9374  9439 D BluetoothAdapter: STATE_ON
06-23 11:34:15.142  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:15.142  9374  9439 D BluetoothLeAdvertiser: stop advertising
,06-23 11:34:15.142  4809  4830 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,06-23 11:34:15.142  4809  4830 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
06-23 11:34:15.142  4809  5020 D BtGatt.AdvertiseManager: message : 1
,06-23 11:34:15.142  4809  5035 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
06-23 11:34:15.142  4809  5035 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 23, currDate: 23
06-23 11:34:15.142  4809  5035 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
06-23 11:34:15.142  4809  5035 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 0 => 0
06-23 11:34:15.142  4809  5035 D BtGatt.GattService: [GSIM LOG]: remove : com.thaliproject.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
06-23 11:34:15.142  4809  5020 D BtGatt.AdvertiseManager: stop advertise for client =  8
,06-23 11:34:15.142  4809  5020 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 8
,06-23 11:34:15.142  4809  5020 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
06-23 11:34:15.152  3486  4257 V AlarmManager:  remove PendingIntent] PendingIntent{629938f: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:15.152  3486  3504 V AlarmManager:  remove PendingIntent] PendingIntent{a43961c: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:15.182  4809  4976 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=8, status=0
,06-23 11:34:15.182  4809  4976 D BtGatt.GattService: Client app is not null!
06-23 11:34:15.182  3486  4395 V AlarmManager:  remove PendingIntent] PendingIntent{c2ba225: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
06-23 11:34:15.182  9374  9434 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,06-23 11:34:15.182  4809  5345 D BtGatt.GattService: unregisterClient() - clientIf=8
,06-23 11:34:15.182  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,06-23 11:34:15.182  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:15.182  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
06-23 11:34:15.182  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-139,7,main], id: 139
,06-23 11:34:15.182  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:15.182  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:15.182  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,06-23 11:34:15.182  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
06-23 11:34:15.182  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
06-23 11:34:15.182  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-139,7,main], id: 139
,06-23 11:34:15.182  3486  3969 V AlarmManager:  remove PendingIntent] PendingIntent{7997ffa: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
06-23 11:34:15.182  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:15.182  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
06-23 11:34:15.182  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-139,7,main], id: 139
,06-23 11:34:15.182  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:15.182  9374  9439 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c4e066 removed from the list
06-23 11:34:15.182  9374  9374 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,06-23 11:34:15.182  9374  9439 D io.jxcore.node.ConnectivityMonitor: stop
06-23 11:34:15.182  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
06-23 11:34:15.182  9374  9374 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
06-23 11:34:15.182  9374  9374 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
06-23 11:34:15.182  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
06-23 11:34:15.182  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
06-23 11:34:15.182  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
06-23 11:34:15.182  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,06-23 11:34:15.182  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
06-23 11:34:15.192  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
06-23 11:34:15.192  9374  9374 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,06-23 11:34:15.192  3486  4396 V AlarmManager:  remove PendingIntent] PendingIntent{6b5d9ab: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:15.192  3486  3505 V AlarmManager:  remove PendingIntent] PendingIntent{901f808: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:15.202  3486  4379 V AlarmManager:  remove PendingIntent] PendingIntent{d993ba1: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:15.202  3486  4049 V AlarmManager:  remove PendingIntent] PendingIntent{9efa1c6: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:15.692  9374  9374 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,06-23 11:34:20.192  9374  9449 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
,06-23 11:34:20.192  9374  9439 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,06-23 11:34:20.192  9374  9439 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
06-23 11:34:20.192  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,06-23 11:34:20.202  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,06-23 11:34:20.202  9374  9439 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,06-23 11:34:20.202  9374  9439 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
06-23 11:34:20.202  9374  9439 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,06-23 11:34:20.202  9374  9439 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
06-23 11:34:20.202  9374  9439 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
06-23 11:34:20.202  9374  9374 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
06-23 11:34:20.202  9374  9460 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,06-23 11:34:20.202  9374  9460 D BluetoothSocket: bindListen(): myUserId = 0
,06-23 11:34:20.202  9374  9460 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
06-23 11:34:20.202  9374  9439 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
,06-23 11:34:20.212  9374  9439 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [00:11:22:33:44:55], error message: ErrorMessage
06-23 11:34:20.212  9374  9439 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
06-23 11:34:20.212  9374  9439 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,06-23 11:34:20.212  9374  9439 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,06-23 11:34:20.212  9374  9439 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
,06-23 11:34:20.222  9374  9460 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
,06-23 11:34:20.222  9374  9460 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@79162f0, port: 6, type: 1, local socket address: null, socket type: 0
,06-23 11:34:20.232  9374  9439 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
06-23 11:34:20.232  9374  9439 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,06-23 11:34:20.232  9374  9439 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
06-23 11:34:20.232  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
06-23 11:34:20.232  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,06-23 11:34:20.232  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
06-23 11:34:20.232  9374  9439 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
06-23 11:34:20.232  9374  9439 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
06-23 11:34:20.232  9374  9439 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ad7d0c1 not in the list
06-23 11:34:20.232  9374  9374 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,06-23 11:34:20.232  9374  9460 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
06-23 11:34:20.232  9374  9439 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ad7d0c1 not in the list
06-23 11:34:20.232  9374  9460 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
06-23 11:34:20.232  9374  9439 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
06-23 11:34:20.232  9374  9460 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
06-23 11:34:20.232  9374  9439 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,06-23 11:34:20.232  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:20.232  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
06-23 11:34:20.232  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
06-23 11:34:20.232  9374  9439 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
06-23 11:34:20.232  9374  9374 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,06-23 11:34:20.232  9374  9374 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
06-23 11:34:20.232  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
06-23 11:34:20.232  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:20.232  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:20.232  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
06-23 11:34:20.232  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-139,7,main], id: 139
,06-23 11:34:20.232  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:20.232  9374  9439 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c4e066 not in the list
06-23 11:34:20.232  9374  9439 D io.jxcore.node.ConnectivityMonitor: stop
06-23 11:34:20.232  9374  9439 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
06-23 11:34:20.232  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,06-23 11:34:20.232  9374  9374 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
06-23 11:34:20.232  9374  9374 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
06-23 11:34:20.232  9374  9374 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,06-23 11:34:20.232  9374  9439 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
,06-23 11:34:20.232  9374  9439 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
06-23 11:34:20.232  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
06-23 11:34:20.232  9374  9439 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
06-23 11:34:20.232  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
06-23 11:34:20.232  9374  9439 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,06-23 11:34:20.232  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,06-23 11:34:20.242  9374  9439 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
,06-23 11:34:20.242  9374  9439 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
,06-23 11:34:20.242  9374  9439 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
,06-23 11:34:20.242  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [incoming]
,06-23 11:34:20.242  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [outgoing]
,06-23 11:34:20.242  9374  9439 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
06-23 11:34:20.242  9374  9439 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,06-23 11:34:20.242  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
06-23 11:34:20.242  9374  9439 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
06-23 11:34:20.242  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
06-23 11:34:20.242  9374  9439 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
06-23 11:34:20.242  9374  9439 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,06-23 11:34:20.242  9374  9439 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
,06-23 11:34:20.242  9374  9439 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
06-23 11:34:20.242  9374  9439 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,06-23 11:34:20.242  9374  9439 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
,06-23 11:34:20.242  9374  9439 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
06-23 11:34:20.242  9374  9439 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
06-23 11:34:20.242  9374  9439 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,06-23 11:34:20.242  9374  9439 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,06-23 11:34:20.252  9374  9439 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
,06-23 11:34:20.252  9374  9439 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,06-23 11:34:20.252  9374  9439 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aac7069 added. We now have 2 listener(s)
06-23 11:34:20.252  9374  9439 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aac7069 added. We now have 3 listener(s)
06-23 11:34:20.252  9374  9439 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,06-23 11:34:20.252  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"44:78:3E:94:2C:E6"}
,06-23 11:34:20.252  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,06-23 11:34:20.252  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"44:78:3E:94:2C:E6"}
06-23 11:34:20.252  9374  9439 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
06-23 11:34:20.252  9374  9439 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe20aee added. We now have 4 listener(s)
06-23 11:34:20.252  9374  9439 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,06-23 11:34:20.252  9374  9439 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,06-23 11:34:20.262  9374  9439 D BluetoothAdapter: enable()
,06-23 11:34:20.262  9374  9439 D BluetoothAdapter: enable(): BT is already enabled..!
,06-23 11:34:20.272  3486  3567 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3766587 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{714895a 4842:com.samsung.android.providers.context/u0a7}
,06-23 11:34:20.272  9374  9439 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,06-23 11:34:20.282  3486  4258 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,06-23 11:34:20.282  3486  4258 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,06-23 11:34:20.282  3486  4258 D WifiService: setWifiEnabled: true pid=9374, uid=10074
,06-23 11:34:20.282  3486  4258 W ActivityManager: Permission Denial: getCurrentUser() from pid=9374, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
,06-23 11:34:20.282  3486  4258 W WifiService: Failed getting userId using ActivityManagerNative
06-23 11:34:20.282  3486  4258 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9374, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
06-23 11:34:20.282  3486  4258 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
06-23 11:34:20.282  3486  4258 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
06-23 11:34:20.282  3486  4258 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
06-23 11:34:20.282  3486  4258 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
06-23 11:34:20.282  3486  4258 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
06-23 11:34:20.282  3486  4258 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
06-23 11:34:20.282  3486  4258 D SettingsProvider: isChangeAllowed() : name = wifi_on
06-23 11:34:20.292  3486  3852 D WifiStateMachine: setFccChannel: channel = -1
,06-23 11:34:20.292  3486  3852 D WifiController: [FCC]setFccChannel() is called !!!
06-23 11:34:20.292  3486  3852 D WifiController: [FCC]Airplane off, setFccChannel(-1)!!!
,06-23 11:34:20.292  3486  3849 D WifiBigDataLog: getJsonFormat() - feature : ONOF
06-23 11:34:20.292  9374  9439 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
,06-23 11:34:20.292  3486  3849 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
06-23 11:34:20.292  3486  3849 D WifiBigDataLog: init : 
,06-23 11:34:20.292  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:20.292  3486  3849 D WifiStateMachine: setFccChannelNative: channel = -1
,06-23 11:34:20.292  3486  3849 D WifiNative-wlan0: callSECApiInt - ID [230]
06-23 11:34:20.302  9374  9439 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
06-23 11:34:20.302  9374  9439 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
,06-23 11:34:20.302  9374  9439 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
,06-23 11:34:20.302  3486  3567 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9c28cb4 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{714895a 4842:com.samsung.android.providers.context/u0a7}
,06-23 11:34:20.312  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:20.312  9374  9439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-23 11:34:20.312  9374  9439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-23 11:34:20.312  9374  9439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
06-23 11:34:20.312  9374  9439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-23 11:34:20.312  9374  9439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-23 11:34:20.312  9374  9439 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
06-23 11:34:20.312  9374  9439 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
06-23 11:34:20.312  9374  9439 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
06-23 11:34:20.312  9374  9439 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
06-23 11:34:20.322  9374  9461 D BluetoothAdapter: disable()
,06-23 11:34:20.332  3486  3567 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5ecf0dd u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{714895a 4842:com.samsung.android.providers.context/u0a7}
,06-23 11:34:20.332  3486  3969 D SettingsProvider: isChangeAllowed() : name = bluetooth_on
06-23 11:34:20.332  3486  3589 D SecContentProvider: insert(), uri = 2
06-23 11:34:20.342  4809  4972 D BluetoothAdapterState: Current state: ON, message: BLE_TURN_OFF
,06-23 11:34:20.352  4809  4972 D BluetoothAdapterProperties: Setting state to 13
,06-23 11:34:20.352  4809  4972 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
06-23 11:34:20.352  4809  4972 D BluetoothAdapterService: Bluetooth PBAP supproted is true
06-23 11:34:20.352  4809  4972 D BluetoothAdapterService: updateAdapterState state is 13
,06-23 11:34:20.352  4809  4809 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,06-23 11:34:20.352  3486  3589 D BluetoothManagerService: Turning On/Off, G state: 3, S state: 2, mBLE count: 2, s BLE count: 2
06-23 11:34:20.352  4809  4972 D BluetoothAdapterService: Autoconnection is available 
06-23 11:34:20.352  3486  3486 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,06-23 11:34:20.352  4809  4972 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
06-23 11:34:20.352  3486  3486 I InputMethodManagerService: [BT Setting State] State =13
,06-23 11:34:20.352  4809  4972 D BluetoothAdapterService: terminating service from this receiver
,06-23 11:34:20.352  3928  4125 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
06-23 11:34:20.362  3928  4125 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
06-23 11:34:20.362  4306  4306 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
,06-23 11:34:20.362  4726  4726 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,06-23 11:34:20.362  3486  3486 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
,06-23 11:34:20.362  3486  3486 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
06-23 11:34:20.362  3486  3486 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,06-23 11:34:20.372  9374  9374 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,06-23 11:34:20.372  9374  9374 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-23 11:34:20.372  9374  9374 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-23 11:34:20.372  9374  9374 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
06-23 11:34:20.372  9374  9374 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-23 11:34:20.372  9374  9374 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-23 11:34:20.372  9374  9374 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
06-23 11:34:20.372  9374  9374 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
06-23 11:34:20.372  9374  9374 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
06-23 11:34:20.372  9374  9374 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,06-23 11:34:20.372  9374  9374 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
06-23 11:34:20.372  9374  9374 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,06-23 11:34:20.372  3486  3567 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c9d323 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ba5b784 9098:com.android.settings/1000}
,06-23 11:34:20.372  3928  3928 D BluetoothPbap: Proxy object disconnected
06-23 11:34:20.372  3928  3928 D PbapServerProfile: Bluetooth service disconnected
,06-23 11:34:20.372  4809  4809 D BleAudioService: onReceive:: INTENT mAobleStateChangeListener got : android.bluetooth.adapter.action.STATE_CHANGED
06-23 11:34:20.372  4809  4809 D BleAudioService: BluetoothAdapter.ACTION_STATE_CHANGED,  state is13
,06-23 11:34:20.382  4809  4972 D BluetoothAdapterProperties: onBluetoothDisable()
06-23 11:34:20.382  9098  9098 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
06-23 11:34:20.382  4809  4809 D ObexServerSockets: shutdown(block = true)
06-23 11:34:20.382  4809  5362 V ObexServerSockets: Accept exception: (expected at shutdown)java.io.IOException: read failed, socket might closed or timeout, read ret: -1
06-23 11:34:20.382  4809  5362 D ObexServerSockets: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
06-23 11:34:20.382  4809  4809 D ObexServerSockets: shutdown called from another thread - interrupt().
06-23 11:34:20.382  4809  5363 V ObexServerSockets: Accept exception: (expected at shutdown)java.io.IOException: read failed, socket might closed or timeout, read ret: -1
06-23 11:34:20.382  4809  5363 D ObexServerSockets: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
06-23 11:34:20.382  4809  4972 W bt_btif : btif_dm_cancel_discovery
06-23 11:34:20.382  4809  4809 D ObexServerSockets: shutdown called from another thread - interrupt().
06-23 11:34:20.382  4809  5323 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
06-23 11:34:20.382  4809  4809 D BluetoothSdpJni: sdpRemoveSdpRecordNative:
06-23 11:34:20.382  4809  4809 D BluetoothSdpJni: SDP Remove record success - handle: 1
06-23 11:34:20.382  4809  4809 D BluetoothSdpJni: sdpRemoveSdpRecordNative:
06-23 11:34:20.382  4809  4809 D BluetoothSdpJni: SDP Remove record success - handle: 0
06-23 11:34:20.382  4809  4809 I BtOppRfcommListener: stopping Accept Thread
06-23 11:34:20.382  4809  5351 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
06-23 11:34:20.382  4809  5351 I BtOppRfcommListener: BluetoothSocket listen thread finished
06-23 11:34:20.382  3486  4258 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
,06-23 11:34:20.382  3486  3504 D SecContentProvider: insert(), uri = 2
,06-23 11:34:20.392  4809  4972 I BluetoothAdapterState: Entering PendingCommandState
,06-23 11:34:20.402  3486  4379 V AlarmManager:  remove PendingIntent] PendingIntent{1ccbdd9: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:20.402  9098  9098 D LocalBluetoothManager: LocalBluetoothManager :: sInstance == null
,06-23 11:34:20.402  3486  3505 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c9d323 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{714895a 4842:com.samsung.android.providers.context/u0a7}
,06-23 11:34:20.402  4809  4976 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,06-23 11:34:20.402  4809  4976 D BluetoothAdapterProperties: Scan Mode:20
06-23 11:34:20.402  4809  4972 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BEGIN_DISABLE
,06-23 11:34:20.412  3486  4435 V AlarmManager:  remove PendingIntent] PendingIntent{5c7e7f: PendingIntentRecord{b26be4c com.android.bluetooth broadcastIntent}}
,06-23 11:34:20.412  3928  4181 D BluetoothTile: handleUpdateState :  supported = true, enabled = false, enabling = false, connected = false, connecting = false, mController.getLastDeviceName() = null
,06-23 11:34:20.412  3486  4396 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,06-23 11:34:20.412  3928  3928 D QSTileView: handleLabelStateChanged() label = Bluetooth cellWidth 272
,06-23 11:34:20.412  9098  9098 D LocalBluetoothManager: LocalBluetoothManager :: constructor
,06-23 11:34:20.422  9374  9374 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-23 11:34:20.422  9098  9098 D BluetoothEventManager: BluetoothEventManager Constructor :: 
,06-23 11:34:20.422  3486  4395 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c9d323 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ff226b8 4273:com.google.android.gms.persistent/u0a19}
,06-23 11:34:20.422  4273  4273 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
,06-23 11:34:20.432  4809  4972 E BluetoothServiceJni: disableBrEdrNative:
06-23 11:34:20.432  4809  4972 E bt_bluedroid: disable_bredr
,06-23 11:34:20.432  4809  4973 E bt_btif : BTA got event 0xe0b
,06-23 11:34:20.432  3486  3969 V AlarmManager:  remove PendingIntent] PendingIntent{844839b: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
06-23 11:34:20.432  4809  5178 W bt_btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
06-23 11:34:20.432  4809  5178 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,06-23 11:34:20.442  4809  4973 D IOP_DB_BT: db_close: nbr users 0
,06-23 11:34:20.442  4809  4973 D IOP_DB_BT: db_close: free database
,06-23 11:34:20.442  4809  5178 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x2  CID 0x40
06-23 11:34:20.442  4809  5178 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 8
06-23 11:34:20.442  4809  5178 W bt_btif : bta_dm_acl_change(), event : 2
,06-23 11:34:20.442  4809  5178 W bt_btif : bta_dm_acl_change(), event : 5
,06-23 11:34:20.442  3486  4395 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c9d323 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b251d48 8749:com.sec.android.app.shealth:remote/u0a36}
,06-23 11:34:20.462  9098  9098 D LocalBluetoothProfileManager: PANU : true
,06-23 11:34:20.462  3486  4395 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c9d323 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ba5b784 9098:com.android.settings/1000}
,06-23 11:34:20.472  4809  5178 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
06-23 11:34:20.472  4809  5178 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
06-23 11:34:20.472  4809  5178 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
06-23 11:34:20.472  4809  5178 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
06-23 11:34:20.472  4809  5178 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
06-23 11:34:20.472  4809  5178 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
06-23 11:34:20.472  4809  5178 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
06-23 11:34:20.472  4809  5178 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
06-23 11:34:20.472  4809  5178 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
06-23 11:34:20.472  4809  5178 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
06-23 11:34:20.472  4809  5178 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
06-23 11:34:20.472  4809  5178 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
06-23 11:34:20.472  4809  5178 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
06-23 11:34:20.472  4809  5178 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
06-23 11:34:20.472  4809  5178 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,06-23 11:34:20.472  3486  3504 V AlarmManager:  remove PendingIntent] PendingIntent{6c63602: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:20.482  4809  4809 V BluetoothOppManager: cleanUp...
,06-23 11:34:20.482  4809  4972 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1339123
,06-23 11:34:20.482  4809  4976 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:11:22:33:44:55, value is empty for type: 1
,06-23 11:34:20.492  3928  4125 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CLASS_CHANGED
06-23 11:34:20.492  4809  4976 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
06-23 11:34:20.492  4809  4976 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:11:22:33:44:55, value is empty for type: 241
,06-23 11:34:20.492  9098  9098 D BluetoothSap: Create BluetoothSap proxy object
,06-23 11:34:20.502  9098  9098 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
06-23 11:34:20.502  9098  9098 D LocalBluetoothManager: LocalBluetoothManager :: onInitCallback != null
,06-23 11:34:20.502  9098  9098 D DockEventReceiver: finishStartingService: stopping service
,06-23 11:34:20.512  9098  9098 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
06-23 11:34:20.512  9098  9098 D BluetoothStatusReceiver: AdapterStateChanged :: state = 13
06-23 11:34:20.512  9098  9098 D BluetoothPan: BluetoothPAN Proxy object connected
,06-23 11:34:20.512  9098  9098 D PanProfile: Bluetooth service connected
,06-23 11:34:20.512  9098  9098 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CLASS_CHANGED
,06-23 11:34:20.512  9098  9098 D BluetoothSap: Proxy object connected
,06-23 11:34:20.512  9098  9098 D SapProfile: Bluetooth service connected
,06-23 11:34:20.522  3486  4422 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c9d323 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a807202 4809:com.android.bluetooth/1002}
,06-23 11:34:20.542  3486  4422 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c9d323 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{214f1fb 7032:com.google.android.apps.maps/u0a119}
,06-23 11:34:20.632  4809  4976 E BluetoothAdapterState: stateChangeCallback : 16
06-23 11:34:20.632  4809  4972 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_NATIVE_STOPED
06-23 11:34:20.632  3486  4258 V AlarmManager:  remove PendingIntent] PendingIntent{8791705: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:20.632  4809  4972 D BtConfig.SecureMode: isSecureModeOn:false
,06-23 11:34:20.632  4809  4972 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,06-23 11:34:20.642  4809  4972 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,06-23 11:34:20.642  4809  4809 D HeadsetService: Received stop request...Stopping profile...
,06-23 11:34:20.652  4809  4972 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,06-23 11:34:20.652  4809  4809 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Message sending
06-23 11:34:20.652  4809  4809 E HeadsetService: notifyProfileServiceStateChanged
,06-23 11:34:20.652  4809  4972 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,06-23 11:34:20.662  3928  3928 D HeadsetProfile: Bluetooth service disconnected
,06-23 11:34:20.662  3486  3486 D BluetoothHeadset: unRegisterMessageListener : 11
,06-23 11:34:20.662  3486  3486 W BluetoothHeadset: Proxy not attached to service
06-23 11:34:20.662  3486  3486 I Telecom : BluetoothManager : unregister MessageListener
06-23 11:34:20.662  3486  3486 I Telecom : CallAudioManager: onBluetoothStateChange: no focus
,06-23 11:34:20.672  4809  4972 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
06-23 11:34:20.672  4809  4809 D A2dpService: Received stop request...Stopping profile...
,06-23 11:34:20.672  4809  5283 D A2dpStateMachine: Exit Disconnected: -1
,06-23 11:34:20.672  4809  4972 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,06-23 11:34:20.672  4809  4809 D Avrcp   : unregisterContentObserver
,06-23 11:34:20.672  4809  4809 D Avrcp   : removeOnActiveSessionsChangedListener
,06-23 11:34:20.682  4809  4972 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
,06-23 11:34:20.682  4809  4809 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Message sending
,06-23 11:34:20.682  4809  4809 E A2dpService: notifyProfileServiceStateChanged
,06-23 11:34:20.682  3486  3486 D BluetoothA2dp: Proxy object disconnected
,06-23 11:34:20.682  3928  3928 D BluetoothA2dp: Proxy object disconnected
06-23 11:34:20.682  3928  3928 D A2dpProfile: Bluetooth service disconnected
06-23 11:34:20.682  4842  4842 D BluetoothA2dp: Proxy object disconnected
,06-23 11:34:20.682  4809  4972 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
06-23 11:34:20.682  4809  4972 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
06-23 11:34:20.682  4809  4972 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,06-23 11:34:20.682  4809  4972 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
06-23 11:34:20.682  4809  4972 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.bleaudio.BleAudioService
,06-23 11:34:20.692  4809  4809 E BluetoothAdapterService: handleMessage() - Message: 1
06-23 11:34:20.692  4809  4809 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Before synchronized
,06-23 11:34:20.692  4809  4809 V BluetoothAdapterState: isTurningOff()=true
06-23 11:34:20.692  4809  4809 V BluetoothAdapterState: isTurningOn()=false
06-23 11:34:20.692  4809  4809 V BluetoothAdapterState: isBleTurningOn()=false
06-23 11:34:20.692  4809  4809 V BluetoothAdapterState: isBleTurningOff()=false
06-23 11:34:20.692  4809  4809 D HidService: Received stop request...Stopping profile...
06-23 11:34:20.692  4809  4809 D HidService: Stopping Bluetooth HidService
06-23 11:34:20.692  4809  4809 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,06-23 11:34:20.692  4809  4809 W bt_btif : cleanup: HH disabling or disabled already, status = 0
06-23 11:34:20.692  4809  4809 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
06-23 11:34:20.692  4809  4809 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, Message sending
06-23 11:34:20.692  4809  4809 E HidService: notifyProfileServiceStateChanged
,06-23 11:34:20.692  3928  3928 D BluetoothInputDevice: Proxy object disconnected
,06-23 11:34:20.692  3928  3928 D HidProfile: Bluetooth service disconnected
,06-23 11:34:20.712  4809  4809 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
06-23 11:34:20.712  4809  4809 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
06-23 11:34:20.712  4809  4809 D HeadsetProvider: cleanup
06-23 11:34:20.712  4809  4809 I HeadsetProvider: clearAllHeadsetSettings(0)
,06-23 11:34:20.732  9374  9374 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,06-23 11:34:20.742  4809  4809 D HealthService: Received stop request...Stopping profile...
,06-23 11:34:20.742  4809  4809 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, Message sending
06-23 11:34:20.742  4809  4809 E HealthService: notifyProfileServiceStateChanged
,06-23 11:34:20.742  4809  4809 D PanService: Received stop request...Stopping profile...
,06-23 11:34:20.742  4809  4809 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, Message sending
06-23 11:34:20.742  4809  4809 E PanService: notifyProfileServiceStateChanged
06-23 11:34:20.742  3486  3486 D BluetoothPan: BluetoothPAN Proxy object disconnected
,06-23 11:34:20.742  3928  3928 D BluetoothPan: BluetoothPAN Proxy object disconnected
,06-23 11:34:20.742  9098  9098 D BluetoothPan: BluetoothPAN Proxy object disconnected
06-23 11:34:20.742  3928  3928 D PanProfile: Bluetooth service disconnected
06-23 11:34:20.742  9098  9098 D PanProfile: Bluetooth service disconnected
,06-23 11:34:20.752  4809  4809 D BluetoothMapService: Received stop request...Stopping profile...
,06-23 11:34:20.752  4809  4809 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Message sending
,06-23 11:34:20.752  4809  4809 E BluetoothMapService: notifyProfileServiceStateChanged
,06-23 11:34:20.762  3928  3928 D BluetoothMap: Proxy object disconnected
06-23 11:34:20.762  3928  3928 D MapProfile: Bluetooth service disconnected
,06-23 11:34:20.762  4809  4809 E BluetoothAdapterService: handleMessage() - Message: 1
06-23 11:34:20.762  4809  4809 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Before synchronized
,06-23 11:34:20.762  4809  4809 V BluetoothAdapterState: isTurningOff()=true
06-23 11:34:20.762  4809  4809 V BluetoothAdapterState: isTurningOn()=false
06-23 11:34:20.762  4809  4809 V BluetoothAdapterState: isBleTurningOn()=false
,06-23 11:34:20.762  4809  4809 V BluetoothAdapterState: isBleTurningOff()=false
06-23 11:34:20.762  4809  4809 D SapService: Received stop request...Stopping profile...
06-23 11:34:20.762  4809  4809 V SapService: stop()
,06-23 11:34:20.762  4809  4809 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=10, Message sending
,06-23 11:34:20.762  4809  4809 E SapService: notifyProfileServiceStateChanged
,06-23 11:34:20.762  3928  3928 D BluetoothSap: Proxy object disconnected
,06-23 11:34:20.762  3928  3928 D SapProfile: Bluetooth service disconnected
06-23 11:34:20.772  9098  9098 D BluetoothSap: Proxy object disconnected
06-23 11:34:20.772  9098  9098 D SapProfile: Bluetooth service disconnected
,06-23 11:34:20.772  4809  4809 E BluetoothAdapterService: handleMessage() - Message: 1
,06-23 11:34:20.772  4809  4809 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, Before synchronized
06-23 11:34:20.772  4809  4809 V BluetoothAdapterState: isTurningOff()=true
06-23 11:34:20.772  4809  4809 V BluetoothAdapterState: isTurningOn()=false
06-23 11:34:20.772  4809  4809 V BluetoothAdapterState: isBleTurningOn()=false
,06-23 11:34:20.772  4809  4809 V BluetoothAdapterState: isBleTurningOff()=false
06-23 11:34:20.772  4809  4809 D BluetoothAdapterService: HID Host service will be diabled
,06-23 11:34:20.772  4809  4809 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,06-23 11:34:20.772  4809  4809 D BleAudioService: Received stop request...Stopping profile...
06-23 11:34:20.772  4809  4809 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.broadcom.bt.service.bleaudio.BleAudioService, state=10, Message sending
06-23 11:34:20.772  4809  5289 E BleAudioStateMachine_R: Exit Disconnected: -1
06-23 11:34:20.772  4809  5288 E BleAudioStateMachine_L: Exit Disconnected: -1
06-23 11:34:20.772  4809  4809 E BleAudioService: notifyProfileServiceStateChanged
,06-23 11:34:20.782  3928  3928 D BluetoothLeAudio: Proxy object disconnected
,06-23 11:34:20.782  3928  3928 D BleAudioProfile: Bluetooth service disconnected
,06-23 11:34:20.782  4809  4809 E BluetoothAdapterService: handleMessage() - Message: 1
,06-23 11:34:20.782  4809  4809 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, Before synchronized
06-23 11:34:20.782  4809  4809 V BluetoothAdapterState: isTurningOff()=true
,06-23 11:34:20.792  4809  4809 V BluetoothAdapterState: isTurningOn()=false
06-23 11:34:20.792  4809  4809 V BluetoothAdapterState: isBleTurningOn()=false
06-23 11:34:20.792  4809  4809 V BluetoothAdapterState: isBleTurningOff()=false
06-23 11:34:20.792  4809  4809 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,06-23 11:34:20.792  4809  4809 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
06-23 11:34:20.792  4809  4809 E BluetoothAdapterService: handleMessage() - Message: 1
06-23 11:34:20.792  4809  4809 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, Before synchronized
,06-23 11:34:20.792  4809  4809 V BluetoothAdapterState: isTurningOff()=true
06-23 11:34:20.792  4809  4809 V BluetoothAdapterState: isTurningOn()=false
,06-23 11:34:20.792  4809  4809 V BluetoothAdapterState: isBleTurningOn()=false
06-23 11:34:20.792  4809  4809 V BluetoothAdapterState: isBleTurningOff()=false
06-23 11:34:20.792  4809  4809 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
06-23 11:34:20.792  4809  4809 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,06-23 11:34:20.792  4809  4809 E BluetoothAdapterService: handleMessage() - Message: 1
,06-23 11:34:20.792  4809  4809 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Before synchronized
06-23 11:34:20.792  4809  4809 V BluetoothAdapterState: isTurningOff()=true
,06-23 11:34:20.792  4809  4809 V BluetoothAdapterState: isTurningOn()=false
06-23 11:34:20.792  4809  4809 V BluetoothAdapterState: isBleTurningOn()=false
06-23 11:34:20.792  4809  4809 V BluetoothAdapterState: isBleTurningOff()=false
,06-23 11:34:20.792  4809  4809 E BluetoothAdapterService: handleMessage() - Message: 1
06-23 11:34:20.802  4809  4809 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=10, Before synchronized
,06-23 11:34:20.802  4809  4809 V BluetoothAdapterState: isTurningOff()=true
06-23 11:34:20.802  4809  4809 V BluetoothAdapterState: isTurningOn()=false
,06-23 11:34:20.802  4809  4809 V BluetoothAdapterState: isBleTurningOn()=false
06-23 11:34:20.802  4809  4809 V BluetoothAdapterState: isBleTurningOff()=false
06-23 11:34:20.802  4809  4809 E BluetoothAdapterService: handleMessage() - Message: 1
06-23 11:34:20.802  4809  4809 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.bleaudio.BleAudioService, state=10, Before synchronized
,06-23 11:34:20.802  4809  4809 V BluetoothAdapterState: isTurningOff()=true
06-23 11:34:20.802  4809  4809 V BluetoothAdapterState: isTurningOn()=false
06-23 11:34:20.802  4809  4809 V BluetoothAdapterState: isBleTurningOn()=false
,06-23 11:34:20.802  4809  4809 V BluetoothAdapterState: isBleTurningOff()=false
06-23 11:34:20.802  4809  4972 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_STOPPED
06-23 11:34:20.802  4809  4809 V BleAudioService: [unregisterCallStateListener]
,06-23 11:34:20.802  4809  4809 W BtBleAudio.JNI: WARNING: cleanupNative(L385): Cleaning up  Ble audio left callback object##
,06-23 11:34:20.802  4809  4809 W BtBleAudio.JNI: WARNING: cleanupNative(L403): Cleaning up Ble audio Interface...##
06-23 11:34:20.802  4809  4809 W BtBleAudio.JNI: WARNING: cleanupNative(L391): Cleaning up  Ble audio right callback object##
06-23 11:34:20.802  4809  4972 D BluetoothAdapterProperties: Setting state to 15
06-23 11:34:20.802  4809  4972 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
06-23 11:34:20.802  4809  4809 V BleAudioService: [unregisterAobleStateChangeListener] Unregistering mAobleStateChangeListener
,06-23 11:34:20.812  4809  4972 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,06-23 11:34:20.812  4809  4972 D BluetoothAdapterService: updateAdapterState state is 15
,06-23 11:34:20.812  4809  4972 D BluetoothAdapterService: Autoconnection is available 
06-23 11:34:20.812  4809  4972 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 15
,06-23 11:34:20.812  4245  4619 D BluetoothAdapter: onBluetoothStateChange: up=false
06-23 11:34:20.812  4809  4972 I BluetoothAdapterState: Entering BleOnState
06-23 11:34:20.812  4245  4619 D BluetoothAdapter: Bluetooth is turned off, stop adv
,06-23 11:34:20.812  4245  4619 D BluetoothAdapter: There are no active google scan apps, stop scan
,06-23 11:34:20.812  3928  4524 D BluetoothPan: onBluetoothStateChange on: false
,06-23 11:34:20.812  4233  4244 D BluetoothAdapter: onBluetoothStateChange: up=false
,06-23 11:34:20.812  4233  4244 D BluetoothAdapter: Bluetooth is turned off, stop adv
,06-23 11:34:20.822  4233  4244 D BluetoothAdapter: There are no active google scan apps, stop scan
,06-23 11:34:20.822  3928  4099 D BluetoothSap: onBluetoothStateChange: up=false
,06-23 11:34:20.822  3928  3949 D BluetoothInputDevice: onBluetoothStateChange: up=false
,06-23 11:34:20.822  3928  3959 D BluetoothLeAudio: onBluetoothStateChange: up=false
,06-23 11:34:20.822  3928  3959 D BluetoothLeAudio: Unbinding service...
06-23 11:34:20.822  3928  4525 D BluetoothA2dp: onBluetoothStateChange: up=false
,06-23 11:34:20.822  4842  4906 D BluetoothAdapter: onBluetoothStateChange: up=false
,06-23 11:34:20.822  4842  4906 D BluetoothAdapter: Bluetooth is turned off, stop adv
,06-23 11:34:20.822  4842  4906 D BluetoothAdapter: There are no active google scan apps, stop scan
06-23 11:34:20.822  3486  3589 D BluetoothAdapter: onBluetoothStateChange: up=false
06-23 11:34:20.822  3486  3589 D BluetoothAdapter: Bluetooth is turned off, stop adv
06-23 11:34:20.822  3486  3589 D BluetoothAdapter: There are no active google scan apps, stop scan
,06-23 11:34:20.832  4809  5246 D BluetoothAdapter: onBluetoothStateChange: up=false
,06-23 11:34:20.832  9098  9109 D BluetoothAdapter: onBluetoothStateChange: up=false
,06-23 11:34:20.832  9098  9109 D BluetoothAdapter: Bluetooth is turned off, stop adv
,06-23 11:34:20.832  9098  9109 D BluetoothAdapter: There are no active google scan apps, stop scan
,06-23 11:34:20.832  7032  7042 D BluetoothAdapter: onBluetoothStateChange: up=false
06-23 11:34:20.832  7032  7042 D BluetoothAdapter: Bluetooth is turned off, stop adv
,06-23 11:34:20.832  7032  7042 D BluetoothAdapter: There are no active google scan apps, stop scan
06-23 11:34:20.832  3486  3589 D BluetoothPan: onBluetoothStateChange on: false
,06-23 11:34:20.832  4273  4283 D BluetoothAdapter: onBluetoothStateChange: up=false
,06-23 11:34:20.832  4273  4283 D BluetoothAdapter: Bluetooth is turned off, stop adv
,06-23 11:34:20.842  4273  4283 D BluetoothAdapter: There are no active google scan apps, stop scan
06-23 11:34:20.842  4273  4283 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
,06-23 11:34:20.842  4273  4283 D BluetoothLeScanner: Exiting stopAllScan
06-23 11:34:20.842  9374  9385 D BluetoothAdapter: onBluetoothStateChange: up=false
06-23 11:34:20.842  9374  9385 D BluetoothAdapter: Bluetooth is turned off, stop adv
06-23 11:34:20.842  9374  9385 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
06-23 11:34:20.842  9374  9385 D BluetoothLeAdvertiser: Exit stop advertising
,06-23 11:34:20.842  9374  9385 D BluetoothAdapter: There are no active google scan apps, stop scan
06-23 11:34:20.842  9374  9385 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
,06-23 11:34:20.842  9374  9385 D BluetoothLeScanner: Exiting stopAllScan
06-23 11:34:20.842  7594  7605 D BluetoothAdapter: onBluetoothStateChange: up=false
,06-23 11:34:20.842  3486  3589 D BluetoothA2dp: onBluetoothStateChange: up=false
06-23 11:34:20.842  3928  4524 D BluetoothAdapter: onBluetoothStateChange: up=false
,06-23 11:34:20.842  3928  4524 D BluetoothAdapter: Bluetooth is turned off, stop adv
06-23 11:34:20.842  9374  9461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,06-23 11:34:20.842  9374  9461 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-23 11:34:20.842  9374  9461 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-23 11:34:20.842  9374  9461 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
06-23 11:34:20.842  9374  9461 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-23 11:34:20.842  9374  9461 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-23 11:34:20.842  9374  9461 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
06-23 11:34:20.842  9374  9461 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
06-23 11:34:20.842  9374  9461 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
06-23 11:34:20.842  9374  9461 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
06-23 11:34:20.842  3928  4524 D BluetoothAdapter: There are no active google scan apps, stop scan
06-23 11:34:20.842  3928  4099 D BluetoothPbap: onBluetoothStateChange: up=false
,06-23 11:34:20.842  9374  9461 D BluetoothAdapter: enable()
,06-23 11:34:20.852  8749  8760 D BluetoothAdapter: onBluetoothStateChange: up=false
06-23 11:34:20.852  8749  8760 D BluetoothAdapter: Bluetooth is turned off, stop adv
,06-23 11:34:20.852  8749  8760 D BluetoothAdapter: There are no active google scan apps, stop scan
,06-23 11:34:20.852  9098  9110 D BluetoothSap: onBluetoothStateChange: up=false
,06-23 11:34:20.852  9374  9439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-23 11:34:20.852  3486  4379 W ActivityManager: Permission Denial: getCurrentUser() from pid=9374, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
,06-23 11:34:20.852  3486  4379 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
06-23 11:34:20.852  3486  4379 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9374, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
06-23 11:34:20.852  3486  4379 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
06-23 11:34:20.852  3486  4379 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2852)
06-23 11:34:20.852  3486  4379 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2842)
06-23 11:34:20.852  3486  4379 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.setBtEnableFlag(BluetoothManagerService.java:1222)
06-23 11:34:20.852  3486  4379 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:254)
06-23 11:34:20.852  3486  4379 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:453)
,06-23 11:34:20.852  3486  4379 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,06-23 11:34:20.862  3486  4379 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,06-23 11:34:20.862  3486  4379 D SettingsProvider: isChangeAllowed() : name = bluetooth_on
,06-23 11:34:20.862  9374  9461 D BluetoothAdapter: BT is in BLE_ON State or TURNING_OFF state
,06-23 11:34:20.862  3486  3567 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{370835a u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{714895a 4842:com.samsung.android.providers.context/u0a7}
,06-23 11:34:20.872  4809  4972 D BluetoothAdapterState: Current state: BLE ON, message: USER_TURN_ON
,06-23 11:34:20.872  3928  3949 D BluetoothMap: onBluetoothStateChange: up=false
,06-23 11:34:20.882  4809  4972 D BluetoothAdapterProperties: Setting state to 11
,06-23 11:34:20.882  4809  4972 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
06-23 11:34:20.882  4809  4972 D BluetoothAdapterService: Bluetooth PBAP supproted is true
06-23 11:34:20.882  4809  4972 D BluetoothAdapterService: updateAdapterState state is 11
,06-23 11:34:20.882  4842  4906 D BluetoothA2dp: onBluetoothStateChange: up=false
,06-23 11:34:20.882  4809  4972 D BluetoothAdapterService: Autoconnection is available 
06-23 11:34:20.882  4809  4972 D BluetoothAdapterService: updateAdapterState prevState = 15newState = 11
06-23 11:34:20.882  4809  4972 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
,06-23 11:34:20.882  4809  4972 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
06-23 11:34:20.882  4809  4972 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,06-23 11:34:20.892  9098  9109 D BluetoothPan: onBluetoothStateChange on: false
,06-23 11:34:20.902  4809  4972 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,06-23 11:34:20.912  4809  4809 D HeadsetService: Received start request. Starting profile...
06-23 11:34:20.912  4809  4809 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1339123
,06-23 11:34:20.912  4809  4809 D HeadsetProvider: make
06-23 11:34:20.912  4809  4809 D HeadsetProvider: HeadsetProvider
06-23 11:34:20.912  4809  4809 I HeadsetProvider: clearAllHeadsetSettings(0)
,06-23 11:34:20.912  4809  4972 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,06-23 11:34:20.912  4809  4809 D HeadsetStateMachine: make
06-23 11:34:20.912  3486  3589 D BluetoothManagerService: Turning On/Off, G state: 1, S state: 2, mBLE count: 2, s BLE count: 2
,06-23 11:34:20.912  3486  3486 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
06-23 11:34:20.912  3486  3486 I InputMethodManagerService: [BT Setting State] State =10
06-23 11:34:20.912  3486  3486 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
06-23 11:34:20.912  4809  4809 E HeadsetStateMachine: # of Max HF connection is 3
,06-23 11:34:20.922  3928  4125 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,06-23 11:34:20.922  3928  4125 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,06-23 11:34:20.922  4306  4306 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
,06-23 11:34:20.922  4726  4726 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,06-23 11:34:20.922  3486  3486 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
06-23 11:34:20.922  3486  3486 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
06-23 11:34:20.922  3486  3486 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,06-23 11:34:20.932  9098  9098 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
06-23 11:34:20.932  9098  9098 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,06-23 11:34:20.932  9374  9374 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-23 11:34:20.932  3486  3567 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8f91e81 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ba5b784 9098:com.android.settings/1000}
,06-23 11:34:20.942  4809  4972 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,06-23 11:34:20.942  3928  4181 D BluetoothTile: handleUpdateState :  supported = true, enabled = false, enabling = false, connected = false, connecting = false, mController.getLastDeviceName() = null
06-23 11:34:20.942  3486  3970 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,06-23 11:34:20.952  9098  9098 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,06-23 11:34:20.952  4809  4972 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,06-23 11:34:20.952  4809  4809 I bt_bluedroid: get_profile_interface handsfree
,06-23 11:34:20.972  4809  4972 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,06-23 11:34:20.972  3486  3486 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
06-23 11:34:20.972  3486  3486 I InputMethodManagerService: [BT Setting State] State =11
,06-23 11:34:20.972  3928  4125 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,06-23 11:34:20.972  3928  4125 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
06-23 11:34:20.972  4306  4306 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
,06-23 11:34:20.982  4726  4726 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
06-23 11:34:20.982  3486  3486 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
06-23 11:34:20.982  3486  3486 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
06-23 11:34:20.982  3486  3486 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,06-23 11:34:20.982  9098  9098 D DockEventReceiver: finishStartingService: stopping service
,06-23 11:34:20.982  9098  9098 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,06-23 11:34:20.982  9098  9098 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,06-23 11:34:20.992  9374  9374 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-23 11:34:20.992  3486  3975 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8f91e81 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{714895a 4842:com.samsung.android.providers.context/u0a7}
,06-23 11:34:21.002  3928  4181 D BluetoothTile: handleUpdateState :  supported = true, enabled = false, enabling = true, connected = false, connecting = false, mController.getLastDeviceName() = null
,06-23 11:34:21.002  3486  4422 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,06-23 11:34:21.002  3928  3928 D QSTileView: handleLabelStateChanged() label = Bluetooth cellWidth 272
,06-23 11:34:21.012  4809  4809 E DualScoManager: Dual Sco Manager already instantiated
,06-23 11:34:21.012  4809  4809 I DualScoManager: Set HeadsetServiceHelper
06-23 11:34:21.012  4809  4809 D BluetoothAtMessage: createCMTIContentObservers
06-23 11:34:21.012  4809  4972 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
,06-23 11:34:21.022  4809  4972 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,06-23 11:34:21.022  4809  4972 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
06-23 11:34:21.022  4809  4972 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
06-23 11:34:21.022  4809  4972 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,06-23 11:34:21.022  4809  4972 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.bleaudio.BleAudioService
,06-23 11:34:21.032  3486  4434 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8f91e81 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ff226b8 4273:com.google.android.gms.persistent/u0a19}
,06-23 11:34:21.032  4273  4273 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
,06-23 11:34:21.052  4809  4809 D HeadsetProvider: Created cursor android.database.sqlite.SQLiteCursor@b9a190f
,06-23 11:34:21.052  4809  4972 I BluetoothAdapterState: Entering PendingCommandState
06-23 11:34:21.052  4809  4809 D HeadsetProvider: setHeadsetDB - Can't find 300 for 44:78:3E:94:2C:XX
,06-23 11:34:21.062  4809  4809 I HeadsetProvider: setHeadsetDB - 44:78:3E:94:2C:XX, 300, 1, true
,06-23 11:34:21.062  3486  4434 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8f91e81 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b251d48 8749:com.sec.android.app.shealth:remote/u0a36}
,06-23 11:34:21.072  4809  4972 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1339123
,06-23 11:34:21.072  3486  4434 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8f91e81 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ba5b784 9098:com.android.settings/1000}
,06-23 11:34:21.082  9098  9098 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
06-23 11:34:21.082  9098  9098 D BluetoothStatusReceiver: AdapterStateChanged :: state = 10
,06-23 11:34:21.092  4809  4809 D HeadsetProvider: Created cursor android.database.sqlite.SQLiteCursor@1b1e37a
,06-23 11:34:21.092  4809  4809 D HeadsetProvider: setHeadsetDB - Can't find 400 for 44:78:3E:94:2C:XX
,06-23 11:34:21.092  3486  4434 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8f91e81 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a807202 4809:com.android.bluetooth/1002}
,06-23 11:34:21.102  4809  4809 I HeadsetProvider: setHeadsetDB - 44:78:3E:94:2C:XX, 400, 1, true
,06-23 11:34:21.102  4809  9468 D HeadsetStateMachine: Enter Disconnected: -2, size: 0/0
,06-23 11:34:21.102  4809  4809 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Message sending
06-23 11:34:21.102  4809  4809 E HeadsetService: notifyProfileServiceStateChanged
,06-23 11:34:21.102  4809  4809 D A2dpService: Received start request. Starting profile...
,06-23 11:34:21.102  4809  4809 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1339123
06-23 11:34:21.102  4809  4809 I bt_bluedroid: get_profile_interface avrcp
,06-23 11:34:21.102  4809  9468 D HeadsetStateMachine: Clear mHeadsetBrsf
06-23 11:34:21.102  4809  9468 D HeadsetStateMachine: map size, before remove : 0
06-23 11:34:21.102  4809  9468 D HeadsetStateMachine: map size, after remove: 0
,06-23 11:34:21.112  4809  4809 I Avrcp   : No of Audio players :: 1
,06-23 11:34:21.112  4809  4809 I Avrcp   : App Package name is GM
,06-23 11:34:21.112  4809  4809 V Avrcp   : MediaPlayerInfo: mPlayerId=1
,06-23 11:34:21.112  4809  4809 I Avrcp   : No of Video players :: 2
,06-23 11:34:21.112  4809  4809 I Avrcp   : Video App Package name is others
,06-23 11:34:21.112  4809  4809 V Avrcp   : MediaPlayerInfo: mPlayerId=2
,06-23 11:34:21.112  4809  4809 I Avrcp   : Video App Package name is VP
,06-23 11:34:21.112  4809  4809 V Avrcp   : MediaPlayerInfo: mPlayerId=3
,06-23 11:34:21.112  4809  4809 I Avrcp   : Add tempPlayer
06-23 11:34:21.112  4809  4809 V Avrcp   : MediaPlayerInfo: mPlayerId=4
06-23 11:34:21.112  4809  4809 V Avrcp   : no_of_players : 4
06-23 11:34:21.112  4809  4809 I Avrcp   : Total no of players: 4
06-23 11:34:21.112  4809  4809 V Avrcp   : Samsung player is the 1st player
06-23 11:34:21.112  4809  4809 D Avrcp   : Compose Browsing Service Candidate
,06-23 11:34:21.112  4809  4809 D Avrcp   : ResolveInfo info ResolveInfo{ac21b07 com.google.android.music/.browse.MediaBrowserService m=0x108000}
06-23 11:34:21.112  4809  4809 D Avrcp   : Initialize Media Controller
,06-23 11:34:21.122  4809  4809 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,06-23 11:34:21.122  4809  4809 E Avrcp   : getActiveSessions
,06-23 11:34:21.122  4809  4809 D Avrcp   : pick active media Controller
06-23 11:34:21.122  4809  4809 D Avrcp   : Get the active Media Controller 
06-23 11:34:21.122  4809  4809 D A2dpStateMachine: make
,06-23 11:34:21.122  4809  4809 I bt_bluedroid: get_profile_interface a2dp
,06-23 11:34:21.122  4809  4809 E bt_btif : warning : media task started media_task_refcnt 1 
,06-23 11:34:21.122  4809  9472 D A2dpStateMachine: Enter Disconnected: -2
,06-23 11:34:21.122  4809  4809 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Message sending
,06-23 11:34:21.122  4809  4809 E A2dpService: notifyProfileServiceStateChanged
,06-23 11:34:21.132  4809  4809 D HidService: Received start request. Starting profile...
,06-23 11:34:21.132  4809  4809 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1339123
06-23 11:34:21.132  4809  4809 I bt_bluedroid: get_profile_interface hidhost
06-23 11:34:21.132  4809  4809 D HidService: setHidService(): set to: null
,06-23 11:34:21.132  4809  4809 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, Message sending
06-23 11:34:21.132  4809  4809 E HidService: notifyProfileServiceStateChanged
06-23 11:34:21.132  3486  4435 I Telecom : BluetoothPhoneService: queryPhoneState
06-23 11:34:21.132  4809  4809 D HeadsetStateMachine: Try to query the phonestate on bind
06-23 11:34:21.132  3486  4435 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState : true
,06-23 11:34:21.132  4809  4809 D HealthService: Received start request. Starting profile...
,06-23 11:34:21.132  4809  4809 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1339123
,06-23 11:34:21.142  4809  4809 I bt_bluedroid: get_profile_interface health
,06-23 11:34:21.142  4809  4809 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, Message sending
06-23 11:34:21.142  4809  4809 E HealthService: notifyProfileServiceStateChanged
06-23 11:34:21.142  4809  4809 D HeadsetStateMachine: Proxy object connected
06-23 11:34:21.142  4809  4809 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,06-23 11:34:21.142  4809  9468 D HeadsetStateMachine: Disconnected process message: 11, size: 0
06-23 11:34:21.142  4809  9468 E HeadsetStateMachine: Unknown message: 11
,06-23 11:34:21.142  4809  4809 D PanService: Received start request. Starting profile...
06-23 11:34:21.142  4809  4809 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1339123
06-23 11:34:21.142  4809  4809 D BluetoothPanServiceJni: initializeNative(L118): pan
06-23 11:34:21.142  4809  4809 I bt_bluedroid: get_profile_interface pan
06-23 11:34:21.142  4809  4809 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, Message sending
06-23 11:34:21.142  4809  4809 E PanService: notifyProfileServiceStateChanged
,06-23 11:34:21.142  4809  4809 D HeadsetPhoneState: sendDeviceDataStateChanged
06-23 11:34:21.142  4809  9468 D HeadsetStateMachine: Disconnected process message: 19, size: 0
,06-23 11:34:21.142  4809  9468 E HeadsetStateMachine: Unknown message: 19
06-23 11:34:21.142  4809  4809 D HeadsetPhoneState: Signal level : previous=0 curr=4
,06-23 11:34:21.142  4809  4809 D BluetoothMapService: Received start request. Starting profile...
,06-23 11:34:21.142  4809  4809 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1339123
,06-23 11:34:21.142  4809  4809 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Message sending
,06-23 11:34:21.142  4809  4809 E BluetoothMapService: notifyProfileServiceStateChanged
06-23 11:34:21.152  4809  4809 V SapService: SapBinder()
,06-23 11:34:21.152  4809  4809 D SapService: Received start request. Starting profile...
06-23 11:34:21.152  4809  4809 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1339123
,06-23 11:34:21.152  4809  4809 V SapService: start()
06-23 11:34:21.152  4809  4809 D SapService: Disable sap : false
,06-23 11:34:21.152  4809  4809 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=12, Message sending
,06-23 11:34:21.152  4809  4809 E SapService: notifyProfileServiceStateChanged
,06-23 11:34:21.152  4809  4809 D BleAudioService: Received start request. Starting profile...
,06-23 11:34:21.152  4809  4809 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1339123
06-23 11:34:21.152  4809  4809 E DualScoManager: Dual Sco Manager already instantiated
06-23 11:34:21.152  4809  4809 D BleAudioStateMachine: make
,06-23 11:34:21.152  4809  4809 I BleAudioStateMachine: Constructor Of BleAudioStateMachine
,06-23 11:34:21.152  4809  4809 D BtBleAudio.JNI: initializeNative(L309): ble audio jni initializeNative: 0
06-23 11:34:21.152  4809  4809 I bt_bluedroid: get_profile_interface bleaudio_source
06-23 11:34:21.152  4809  4809 D BleAudioStateMachine: make
06-23 11:34:21.152  4809  9477 E BleAudioStateMachine_L: Enter Disconnected: -2
,06-23 11:34:21.152  4809  4809 I BleAudioStateMachine: Constructor Of BleAudioStateMachine
,06-23 11:34:21.152  4809  4809 D BtBleAudio.JNI: initializeNative(L309): ble audio jni initializeNative: 1
06-23 11:34:21.162  4809  4809 V BleAudioService: [registerCallStateListener]
,06-23 11:34:21.162  4809  9478 E BleAudioStateMachine_R: Enter Disconnected: -2
,06-23 11:34:21.162  4809  4809 V BleAudioService: [registerAobleStateChangeListener]
,06-23 11:34:21.162  4809  4809 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.broadcom.bt.service.bleaudio.BleAudioService, state=12, Message sending
,06-23 11:34:21.162  4809  4809 E BleAudioService: notifyProfileServiceStateChanged
,06-23 11:34:21.162  4809  4809 E BluetoothAdapterService: handleMessage() - Message: 1
06-23 11:34:21.162  4809  4809 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Before synchronized
,06-23 11:34:21.162  4809  4809 V BluetoothAdapterState: isTurningOff()=false
,06-23 11:34:21.162  4809  4809 V BluetoothAdapterState: isTurningOn()=true
06-23 11:34:21.162  4809  4809 V BluetoothAdapterState: isBleTurningOn()=false
06-23 11:34:21.162  4809  4809 V BluetoothAdapterState: isBleTurningOff()=false
06-23 11:34:21.162  4809  4809 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-23 11:34:21.162  4809  4809 E BluetoothAdapterService: handleMessage() - Message: 1
06-23 11:34:21.162  4809  9468 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,06-23 11:34:21.162  4809  4809 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Before synchronized
06-23 11:34:21.162  4809  9468 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
06-23 11:34:21.162  4809  9468 D HeadsetStateMachine: Disconnected process message: 11, size: 0
06-23 11:34:21.162  4809  9468 E HeadsetStateMachine: Unknown message: 11
06-23 11:34:21.172  4809  4809 V BluetoothAdapterState: isTurningOff()=false
06-23 11:34:21.172  4809  4809 V BluetoothAdapterState: isTurningOn()=true
,06-23 11:34:21.172  4809  4809 V BluetoothAdapterState: isBleTurningOn()=false
06-23 11:34:21.172  4809  4809 V BluetoothAdapterState: isBleTurningOff()=false
06-23 11:34:21.172  4809  4809 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
06-23 11:34:21.172  4809  4809 D HeadsetPhoneState: sendDeviceDataStateChanged
,06-23 11:34:21.172  4809  9468 D HeadsetStateMachine: Disconnected process message: 11, size: 0
06-23 11:34:21.172  4809  4809 D HeadsetPhoneState: Signal level : previous=0 curr=4
06-23 11:34:21.172  4809  9468 E HeadsetStateMachine: Unknown message: 11
06-23 11:34:21.172  4809  4809 E BluetoothAdapterService: handleMessage() - Message: 1
06-23 11:34:21.172  4809  9468 D HeadsetStateMachine: Disconnected process message: 19, size: 0
06-23 11:34:21.172  4809  4809 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, Before synchronized
06-23 11:34:21.172  4809  9468 E HeadsetStateMachine: Unknown message: 19
,06-23 11:34:21.172  4809  4809 V BluetoothAdapterState: isTurningOff()=false
06-23 11:34:21.172  4809  4809 V BluetoothAdapterState: isTurningOn()=true
06-23 11:34:21.172  4809  4809 V BluetoothAdapterState: isBleTurningOn()=false
06-23 11:34:21.172  4809  4809 V BluetoothAdapterState: isBleTurningOff()=false
06-23 11:34:21.172  4809  4809 D BluetoothAdapterService: HID Host service started
,06-23 11:34:21.172  3486  4258 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8f91e81 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{214f1fb 7032:com.google.android.apps.maps/u0a119}
,06-23 11:34:21.182  3928  4125 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CONNECTION_HID_HOST
,06-23 11:34:21.182  4809  4809 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
06-23 11:34:21.182  3928  4125 W LocalBluetoothProfileManager: updateLocalProfiles :: A2DP profile was previously added but the UUID is now missing.
06-23 11:34:21.182  3928  4125 W LocalBluetoothProfileManager: updateLocalProfiles :: HEADSET profile was previously added but the UUID is now missing.
06-23 11:34:21.182  3928  4125 W LocalBluetoothProfileManager: updateLocalProfiles :: MAP profile was previously added but the UUID is now missing.
,06-23 11:34:21.182  3928  4125 W LocalBluetoothProfileManager: updateLocalProfiles :: PBAP profile was previously added but the UUID is now missing.
,06-23 11:34:21.182  4809  4809 E BluetoothAdapterService: handleMessage() - Message: 1
06-23 11:34:21.182  3928  4125 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
06-23 11:34:21.182  4809  4809 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, Before synchronized
06-23 11:34:21.182  3928  4125 D HidProfile: mService is null. need to get proxy again!!
06-23 11:34:21.192  9098  9098 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CONNECTION_HID_HOST
,06-23 11:34:21.192  4809  4809 V BluetoothAdapterState: isTurningOff()=false
06-23 11:34:21.192  4809  4809 V BluetoothAdapterState: isTurningOn()=true
06-23 11:34:21.192  4809  4809 V BluetoothAdapterState: isBleTurningOn()=false
06-23 11:34:21.192  4809  4809 V BluetoothAdapterState: isBleTurningOff()=false
,06-23 11:34:21.192  9098  9098 D BluetoothMap: Create BluetoothMap proxy object
06-23 11:34:21.192  4809  4809 E BluetoothAdapterService: handleMessage() - Message: 1
06-23 11:34:21.192  4809  4809 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, Before synchronized
,06-23 11:34:21.192  4809  4809 V BluetoothAdapterState: isTurningOff()=false
06-23 11:34:21.192  4809  4809 V BluetoothAdapterState: isTurningOn()=true
06-23 11:34:21.192  4809  4809 V BluetoothAdapterState: isBleTurningOn()=false
06-23 11:34:21.192  4809  4809 V BluetoothAdapterState: isBleTurningOff()=false
06-23 11:34:21.192  4809  4809 E BluetoothAdapterService: handleMessage() - Message: 1
06-23 11:34:21.192  4809  4809 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Before synchronized
,06-23 11:34:21.192  4809  4809 V BluetoothAdapterState: isTurningOff()=false
,06-23 11:34:21.192  4809  4809 V BluetoothAdapterState: isTurningOn()=true
06-23 11:34:21.192  4809  4809 V BluetoothAdapterState: isBleTurningOn()=false
06-23 11:34:21.192  4809  4809 V BluetoothAdapterState: isBleTurningOff()=false
,06-23 11:34:21.192  4809  4809 E BluetoothAdapterService: handleMessage() - Message: 1
06-23 11:34:21.202  4809  4809 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=12, Before synchronized
,06-23 11:34:21.202  4809  4809 V BluetoothAdapterState: isTurningOff()=false
06-23 11:34:21.202  4809  4809 V BluetoothAdapterState: isTurningOn()=true
06-23 11:34:21.202  4809  4809 V BluetoothAdapterState: isBleTurningOn()=false
06-23 11:34:21.202  4809  4809 V BluetoothAdapterState: isBleTurningOff()=false
06-23 11:34:21.202  4809  4809 D BleAudioService: [onCallStateChanged] ENTER -- State: (0)
06-23 11:34:21.202  4809  4809 D BleAudioService: [onCallStateChanged] No devices in connected state
06-23 11:34:21.202  4809  4809 D BleAudioService: [onCallStateChanged][PHONECALL STATE Changed]: EXIT
06-23 11:34:21.202  4809  4809 E BluetoothAdapterService: handleMessage() - Message: 1
06-23 11:34:21.202  4809  4809 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.bleaudio.BleAudioService, state=12, Before synchronized
,06-23 11:34:21.202  4809  4809 V BluetoothAdapterState: isTurningOff()=false
06-23 11:34:21.202  4809  4809 V BluetoothAdapterState: isTurningOn()=true
06-23 11:34:21.202  4809  4809 V BluetoothAdapterState: isBleTurningOn()=false
06-23 11:34:21.202  4809  4809 V BluetoothAdapterState: isBleTurningOff()=false
,06-23 11:34:21.202  4809  4972 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_STARTED
,06-23 11:34:21.202  3486  3567 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7f8486 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ba5b784 9098:com.android.settings/1000}
,06-23 11:34:21.212  4809  9479 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,06-23 11:34:21.212  4809  9479 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,06-23 11:34:21.212  4809  4972 E BluetoothServiceJni: enableBrEdrNative:
06-23 11:34:21.212  4809  4972 I bt_bluedroid: enable_bredr
06-23 11:34:21.212  3928  4125 W LocalBluetoothProfileManager: updateLocalProfiles :: BleAudio profile was created already 
,06-23 11:34:21.212  3928  3928 D BluetoothInputDevice: Proxy object connected
06-23 11:34:21.212  3928  3928 D HidProfile: Bluetooth service connected
,06-23 11:34:21.222  4809  4976 I bt_bta_hh: BTA_HhEnable sec_mask:0x24 p_cback:0xf38bff29
06-23 11:34:21.222  4809  4976 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x100048
,06-23 11:34:21.222  4809  5178 D CODEC_IF: codec_if_open: opening libbt-codec_aptx.so...
06-23 11:34:21.222  4809  4976 D BluetoothAdapterProperties: Address is:44:78:3E:94:2C:E6
06-23 11:34:21.222  4809  4976 E BluetoothServiceJni: populateRssiValuesNative
06-23 11:34:21.222  4809  4976 I bt_bluedroid: getModelRssiValues
06-23 11:34:21.222  4809  4976 E BluetoothServiceJni: model_rssi_values_callback: low = -75, mid = -65, high = 127
06-23 11:34:21.222  4809  4976 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -75,-65,127
06-23 11:34:21.222  4809  5178 D CODEC_IF_MOD: codec_open: codec_open
06-23 11:34:21.222  4809  5178 D CODEC_IF_MOD: codec_open: apt-x encoder initialized successfully
06-23 11:34:21.222  4809  5178 D CODEC_IF_MOD: codec_open:    version : 1.0.1.0
06-23 11:34:21.222  4809  5178 D CODEC_IF_MOD: codec_open:    build : Android_JB_4.2.2
06-23 11:34:21.222  4809  5178 D CODEC_IF: codec_if_open: codec module opened (v0.1
06-23 11:34:21.222  4809  5178 D CODEC_IF: codec_if_close: codec_if_close hdl -288878588
06-23 11:34:21.222  4809  5178 D CODEC_IF_MOD: codec_close: codec_close
06-23 11:34:21.222  4809  5178 D CODEC_IF_MOD: codec_close: freed apt-x encoder
06-23 11:34:21.222  4809  5178 D         : Codec ==> check 96kHz mode : check_sshd_encoder_available:332
,06-23 11:34:21.222  4809  5178 D CODEC_IF: codec_if_open: opening libbt-codec_sshd.so...
,06-23 11:34:21.222  4809  5178 D CODEC_IF_SSHD: codec_open: codec_open
06-23 11:34:21.222  4809  5178 D CODEC_IF_SSHD: Codec ==> pcm_info.sampling_freq : 96000
06-23 11:34:21.222  4809  5178 D CODEC_IF_SSHD: codec_open: SSHD encoder initialized successfully
06-23 11:34:21.222  4809  5178 D CODEC_IF: codec_if_open: codec module opened (v0.1
06-23 11:34:21.222  4809  5178 D CODEC_IF: codec_if_close: codec_if_close hdl -553398912
06-23 11:34:21.222  4809  5178 D CODEC_IF_SSHD: codec_close: codec_close
06-23 11:34:21.222  4809  5178 D         : Codec ==> copy capability info [bta_av_co_audio_init:559]
06-23 11:34:21.222  4809  5178 D CODEC_IF: codec_if_open: opening libbt-codec_aptx.so...
06-23 11:34:21.222  4809  5178 D CODEC_IF_MOD: codec_open: codec_open
06-23 11:34:21.222  4809  5178 D CODEC_IF_MOD: codec_open: apt-x encoder initialized successfully
06-23 11:34:21.222  4809  5178 D CODEC_IF_MOD: codec_open:    version : 1.0.1.0
06-23 11:34:21.222  4809  5178 D CODEC_IF_MOD: codec_open:    build : Android_JB_4.2.2
06-23 11:34:21.222  4809  5178 D CODEC_IF: codec_if_open: codec module opened (v0.1
06-23 11:34:21.222  4809  5178 D CODEC_IF: codec_if_close: codec_if_close hdl -288878588
,06-23 11:34:21.222  4809  5178 D CODEC_IF_MOD: codec_close: codec_close
06-23 11:34:21.222  4809  5178 D CODEC_IF_MOD: codec_close: freed apt-x encoder
06-23 11:34:21.222  4809  5178 D         : Codec ==> check 96kHz mode : check_sshd_encoder_available:332
06-23 11:34:21.222  4809  5178 D CODEC_IF: codec_if_open: opening libbt-codec_sshd.so...
06-23 11:34:21.222  4809  5178 D CODEC_IF_SSHD: codec_open: codec_open
06-23 11:34:21.222  4809  5178 D CODEC_IF_SSHD: Codec ==> pcm_info.sampling_freq : 96000
06-23 11:34:21.222  4809  5178 D CODEC_IF_SSHD: codec_open: SSHD encoder initialized successfully
06-23 11:34:21.222  4809  5178 D CODEC_IF: codec_if_open: codec module opened (v0.1
06-23 11:34:21.222  4809  5178 D CODEC_IF: codec_if_close: codec_if_close hdl -553398912
06-23 11:34:21.222  3486  4379 V AlarmManager:  remove PendingIntent] PendingIntent{9588ce0: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
06-23 11:34:21.222  4809  5178 D CODEC_IF_SSHD: codec_close: codec_close
06-23 11:34:21.222  4809  5178 D         : Codec ==> copy capability info [bta_av_co_audio_init:559]
06-23 11:34:21.222  4809  4976 D BluetoothAdapterProperties: Name is: Samsung Galaxy S7
06-23 11:34:21.222  3486  3486 D SettingsProvider: isChangeAllowed() : name = bluetooth_name
,06-23 11:34:21.232  9098  9098 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
,06-23 11:34:21.232  4809  4976 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,06-23 11:34:21.232  3486  4396 V AlarmManager:  remove PendingIntent] PendingIntent{69970c: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
06-23 11:34:21.232  4809  4976 D BluetoothAdapterProperties: Scan Mode:20
06-23 11:34:21.232  4809  4976 D BluetoothAdapterProperties: Discoverable Timeout:-1
06-23 11:34:21.232  4809  4976 E bt_btif : btif_handle_bluetooth_enable_evt
06-23 11:34:21.232  4809  4976 E bt_btif : JVenable fails
06-23 11:34:21.232  4809  4976 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
06-23 11:34:21.232  4809  4976 D IOP_DB_BT: db_open: db_open : handle 4085526544l, read 18483 bytes onto local cache
06-23 11:34:21.232  4809  4976 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
06-23 11:34:21.232  4809  4976 D IOP_DB_BT: db_query: result 1
06-23 11:34:21.232  4809  4976 I         : iop_db_open: iop_db_open status 0
06-23 11:34:21.232  4809  4976 E BluetoothAdapterState: stateChangeCallback : 17
,06-23 11:34:21.232  4809  4972 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_NATIVE_STARTED
,06-23 11:34:21.232  4809  4976 E bt_btif : no av cb found, event:0, BTA_AV_ENABLE_EVT ignored!
06-23 11:34:21.232  4809  4976 E bt_btif : btif_sm_dispatch : Invalid handle
06-23 11:34:21.232  4809  4976 E bt_btif : no av control block available at state:3
06-23 11:34:21.232  4809  4976 E bt_btif : no av control block available at state:3
,06-23 11:34:21.232  4809  4976 E bt_btif : no av control block available at state:2
06-23 11:34:21.232  4809  4976 E bt_btif : warning : no command pending, ignore ack
06-23 11:34:21.242  4809  4976 E bt_btif : no av control block available at state:3
06-23 11:34:21.242  4809  4976 E bt_btif : no av control block available at state:2
,06-23 11:34:21.242  4809  4976 W bt_btif : btif_av_state_idle_handler : unhandled event:BTA_AV_REGISTER_EVT
,06-23 11:34:21.242  4809  4976 E bt_btif : btif_sm_dispatch : Invalid handle
06-23 11:34:21.242  4809  4976 E bt_btif : no av control block available at state:3
06-23 11:34:21.242  4809  4976 E bt_btif : no av control block available at state:3
06-23 11:34:21.242  4809  4976 E bt_btif : no av control block available at state:2
06-23 11:34:21.242  4809  4976 E bt_btif : warning : no command pending, ignore ack
,06-23 11:34:21.242  4809  4976 E bt_btif : no av control block available at state:3
,06-23 11:34:21.242  4809  4976 E bt_btif : no av control block available at state
06-23 11:34:21.242  4809  4976 W bt_btif : btif_av_state_idle_handler : unhandled event:BTA_AV_REGISTER_EVT
06-23 11:34:21.242  4809  4976 E bt_btif : btif_sm_dispatch : Invalid handle
06-23 11:34:21.242  4809  4976 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
06-23 11:34:21.242  4809  4972 D BluetoothAdapterProperties: ScanMode =  20
06-23 11:34:21.242  4809  4972 D BluetoothAdapterProperties: State =  11
,06-23 11:34:21.242  3486  3504 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
,06-23 11:34:21.242  3486  3975 V AlarmManager:  remove PendingIntent] PendingIntent{1a0426a: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:21.252  9374  9374 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-23 11:34:21.252  3486  4395 D SecContentProvider: insert(), uri = 2
,06-23 11:34:21.252  9098  9098 D LocalBluetoothProfileManager: Adding local BleAudio profile
,06-23 11:34:21.252  4809  4972 D BluetoothAdapterProperties: Setting state to 12
06-23 11:34:21.252  4809  4972 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
06-23 11:34:21.252  4809  4972 D HeadsetService: setBleAudioService(): com.broadcom.bt.service.bleaudio.BleAudioService@a6b533d
06-23 11:34:21.252  4809  4972 D A2dpService: setBleAudioService(): com.broadcom.bt.service.bleaudio.BleAudioService@a6b533d
,06-23 11:34:21.252  4809  4972 D BleAudioService: setHeadsetService: setting HeadsetService
06-23 11:34:21.252  4809  4972 D BleAudioService: setA2dpService: setting A2dpService
06-23 11:34:21.252  4809  4972 D BluetoothAdapterService: Bluetooth PBAP supproted is true
06-23 11:34:21.252  4809  4972 D BluetoothAdapterService: updateAdapterState state is 12
06-23 11:34:21.252  9098  9098 D BluetoothLeAudio: getProfileProxy()
,06-23 11:34:21.262  4809  4972 V BluetoothAdapterService: start opp service
,06-23 11:34:21.262  9098  9098 D BluetoothLeAudio: Success to bind to IBluetoothLeAudio with Intent { act=com.broadcom.bt.service.bleaudio.IBluetoothLeAudio cmp=com.android.bluetooth/com.broadcom.bt.service.bleaudio.BleAudioService VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
,06-23 11:34:21.262  4809  4976 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
06-23 11:34:21.262  4809  4976 D BluetoothAdapterProperties: Scan Mode:21
,06-23 11:34:21.262  4809  4976 D BluetoothAdapterProperties: Discoverable Timeout:-1
,06-23 11:34:21.262  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,06-23 11:34:21.272  3486  4396 V AlarmManager:  remove PendingIntent] PendingIntent{822b4c2: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:21.272  9374  9374 D BluetoothAdapter: STATE_ON
,06-23 11:34:21.272  9374  9374 D BluetoothAdapter: STATE_ON
,06-23 11:34:21.272  9374  9374 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,06-23 11:34:21.282  4809  4972 D BluetoothAdapterService: Autoconnection is available 
06-23 11:34:21.282  4809  4972 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
06-23 11:34:21.282  4809  4972 D BluetoothAdapterService: starting service from this receiver
,06-23 11:34:21.282  4245  4619 D BluetoothAdapter: onBluetoothStateChange: up=true
06-23 11:34:21.282  4245  4619 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
06-23 11:34:21.282  4809  4809 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,06-23 11:34:21.282  9098  9098 D BluetoothMap: Proxy object connected
,06-23 11:34:21.282  9098  9098 D MapProfile: Bluetooth service connected
06-23 11:34:21.282  9098  9098 D BluetoothMap: getConnectedDevices()
,06-23 11:34:21.282  9098  9109 D BluetoothMap: onBluetoothStateChange: up=true
,06-23 11:34:21.282  3928  3959 D BluetoothPan: onBluetoothStateChange on: true
06-23 11:34:21.282  3928  3959 D BluetoothPan: onBluetoothStateChange calling doBind()
,06-23 11:34:21.292  9374  9374 D BluetoothAdapter: STATE_ON
,06-23 11:34:21.292  9374  9374 D BluetoothAdapter: STATE_ON
,06-23 11:34:21.292  9374  9374 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,06-23 11:34:21.292  3486  4422 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7f8486 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{714895a 4842:com.samsung.android.providers.context/u0a7}
,06-23 11:34:21.302  9374  9374 D BluetoothAdapter: STATE_ON
,06-23 11:34:21.302  4809  4809 I BluetoothPbapService: Handler(): got msg=1
,06-23 11:34:21.302  9374  9374 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-23 11:34:21.302  9374  9374 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-23 11:34:21.302  9374  9374 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
06-23 11:34:21.302  9374  9374 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-23 11:34:21.302  9374  9374 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-23 11:34:21.302  9374  9374 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
06-23 11:34:21.302  9374  9374 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
06-23 11:34:21.302  9374  9374 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
06-23 11:34:21.302  9374  9374 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,06-23 11:34:21.302  3486  3975 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,06-23 11:34:21.302  4233  4244 D BluetoothAdapter: onBluetoothStateChange: up=true
,06-23 11:34:21.302  4233  4244 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,06-23 11:34:21.302  3928  4525 D BluetoothSap: onBluetoothStateChange: up=true
,06-23 11:34:21.312  3928  4525 D BluetoothSap: Binding service...
,06-23 11:34:21.312  9098  9098 D BluetoothInputDevice: Proxy object connected
,06-23 11:34:21.312  9098  9098 D HidProfile: Bluetooth service connected
06-23 11:34:21.312  9374  9374 D BluetoothAdapter: STATE_ON
,06-23 11:34:21.312  4809  4972 D BluetoothAdapterService: BT on, init HID DEV count : 0
,06-23 11:34:21.312  4809  4972 I BluetoothAdapterState: Entering OnState
,06-23 11:34:21.322  4809  9482 V BluetoothPbapService: PBAP Service initSocket try: 0
,06-23 11:34:21.322  4809  4809 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
06-23 11:34:21.322  3486  4049 V AlarmManager:  remove PendingIntent] PendingIntent{a1fd0c5: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:21.322  3928  4524 D BluetoothInputDevice: onBluetoothStateChange: up=true
06-23 11:34:21.322  3928  4524 D BluetoothInputDevice: Binding service...
,06-23 11:34:21.332  3486  3969 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7f8486 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ff226b8 4273:com.google.android.gms.persistent/u0a19}
06-23 11:34:21.332  4273  4273 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
,06-23 11:34:21.332  4809  4809 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,06-23 11:34:21.332  9374  9374 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,06-23 11:34:21.332  4809  4809 V BtOppService: isOwner == true
,06-23 11:34:21.332  3928  3928 D BluetoothInputDevice: Proxy object connected
,06-23 11:34:21.332  3928  3928 D HidProfile: Bluetooth service connected
,06-23 11:34:21.342  9098  9098 D BluetoothPbap: Proxy object connected
,06-23 11:34:21.342  9098  9098 D PbapServerProfile: Bluetooth service connected
,06-23 11:34:21.342  9098  9110 D BluetoothPbap: onBluetoothStateChange: up=true
06-23 11:34:21.342  9098  9098 D BluetoothLeAudio: Proxy object connected
,06-23 11:34:21.342  9098  9098 D BleAudioProfile: Bluetooth service connected
,06-23 11:34:21.342  9098  9098 D BluetoothLeAudio: getConnectedDevices()
,06-23 11:34:21.342  3928  3949 D BluetoothLeAudio: onBluetoothStateChange: up=true
,06-23 11:34:21.342  3928  3949 D BluetoothLeAudio: Binding service...
,06-23 11:34:21.342  4809  9482 D BluetoothSocket: bindListen(): myUserId = 0
06-23 11:34:21.342  4809  9482 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,06-23 11:34:21.352  3486  3969 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7f8486 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b251d48 8749:com.sec.android.app.shealth:remote/u0a36}
,06-23 11:34:21.362  3486  3969 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7f8486 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ba5b784 9098:com.android.settings/1000}
,06-23 11:34:21.362  9098  9098 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
,06-23 11:34:21.362  9098  9098 D BluetoothStatusReceiver: AdapterStateChanged :: state = 11
,06-23 11:34:21.372  4809  9482 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,06-23 11:34:21.382  9374  9461 D BluetoothAdapter: STATE_ON
,06-23 11:34:21.382  9374  9461 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-23 11:34:21.382  9374  9461 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-23 11:34:21.382  9374  9461 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
06-23 11:34:21.382  9374  9461 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-23 11:34:21.382  9374  9461 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-23 11:34:21.382  9374  9461 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
06-23 11:34:21.382  9374  9461 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
06-23 11:34:21.382  9374  9461 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
06-23 11:34:21.382  9374  9461 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,06-23 11:34:21.382  9374  9439 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
,06-23 11:34:21.382  3486  3969 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7f8486 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a807202 4809:com.android.bluetooth/1002}
,06-23 11:34:21.382  3486  4435 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,06-23 11:34:21.392  3486  4435 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,06-23 11:34:21.392  9374  9439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-23 11:34:21.392  3486  4435 D WifiService: setWifiEnabled: false pid=9374, uid=10074
,06-23 11:34:21.392  3486  4434 V AlarmManager:  remove PendingIntent] PendingIntent{1c555d4: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:21.392  3928  3928 D BluetoothPan: BluetoothPAN Proxy object connected
06-23 11:34:21.392  3928  3928 D PanProfile: Bluetooth service connected
,06-23 11:34:21.392  3486  4435 D SettingsProvider: isChangeAllowed() : name = wifi_on
,06-23 11:34:21.402  3486  3852 D WifiStateMachine: setFccChannel: channel = -1
06-23 11:34:21.402  3486  3852 D WifiController: [FCC]setFccChannel() is called !!!
06-23 11:34:21.402  3486  3852 D WifiController: MHS off and WIFI tunred off and move to mApStaDisabledState
,06-23 11:34:21.402  3486  3852 D WifiController: [FCC]Airplane off, setFccChannel(-1)!!!
06-23 11:34:21.402  3486  3852 D SecContentProvider: insert(), uri = 2
06-23 11:34:21.402  3486  3849 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
06-23 11:34:21.402  3486  3849 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,06-23 11:34:21.402  3928  3949 D BluetoothLeAudio: Success to bind to IBluetoothLeAudio with Intent { act=com.broadcom.bt.service.bleaudio.IBluetoothLeAudio cmp=com.android.bluetooth/com.broadcom.bt.service.bleaudio.BleAudioService VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
,06-23 11:34:21.412  3486  3849 D WifiBigDataLog: init : 
06-23 11:34:21.412  3928  4524 D BluetoothA2dp: onBluetoothStateChange: up=true
06-23 11:34:21.412  3928  4524 D BluetoothA2dp: Binding service...
,06-23 11:34:21.412  3928  3928 D BluetoothLeAudio: Proxy object connected
06-23 11:34:21.412  3928  3928 D BleAudioProfile: Bluetooth service connected
06-23 11:34:21.412  3928  3928 D BluetoothLeAudio: getConnectedDevices()
06-23 11:34:21.412  3486  3849 D WifiStateMachine: setFccChannelNative: channel = -1
06-23 11:34:21.412  3486  3849 D WifiNative-wlan0: callSECApiInt - ID [230]
,06-23 11:34:21.412  3928  4524 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,06-23 11:34:21.422  4842  4855 D BluetoothAdapter: onBluetoothStateChange: up=true
,06-23 11:34:21.422  4842  4855 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
06-23 11:34:21.422  3486  3589 D BluetoothAdapter: onBluetoothStateChange: up=true
,06-23 11:34:21.422  3486  3589 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
06-23 11:34:21.422  3486  4435 V AlarmManager:  remove PendingIntent] PendingIntent{9c5f258: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:21.422  3928  3959 D BluetoothInputDevice: onBluetoothStateChange: up=true
,06-23 11:34:21.432  4809  5345 D BluetoothAdapter: onBluetoothStateChange: up=true
,06-23 11:34:21.432  4809  5345 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,06-23 11:34:21.432  9098  9109 D BluetoothAdapter: onBluetoothStateChange: up=true
06-23 11:34:21.432  9098  9109 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,06-23 11:34:21.432  9098  9110 D BluetoothInputDevice: onBluetoothStateChange: up=true
,06-23 11:34:21.432  3486  4379 V AlarmManager:  remove PendingIntent] PendingIntent{dd3dc04: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:21.432  3928  3928 D BluetoothSap: Proxy object connected
06-23 11:34:21.432  3928  3928 D SapProfile: Bluetooth service connected
,06-23 11:34:21.432  7032  7258 D BluetoothAdapter: onBluetoothStateChange: up=true
06-23 11:34:21.432  7032  7258 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,06-23 11:34:21.432  3486  3589 D BluetoothPan: onBluetoothStateChange on: true
,06-23 11:34:21.432  3486  3589 D BluetoothPan: onBluetoothStateChange calling doBind()
06-23 11:34:21.442  3486  3970 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
06-23 11:34:21.442  3486  3486 D BluetoothPan: BluetoothPAN Proxy object connected
,06-23 11:34:21.442  3486  3849 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,06-23 11:34:21.442  3486  3849 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
06-23 11:34:21.442  3486  3849 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
06-23 11:34:21.442  3486  3849 D WifiStateMachine: sendBroadcastForCaptivePortalNotLoginIcon : false
,06-23 11:34:21.442  4273  4544 D BluetoothAdapter: onBluetoothStateChange: up=true
,06-23 11:34:21.442  4273  4544 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,06-23 11:34:21.442  3486  3849 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
,06-23 11:34:21.442  3486  3504 V AlarmManager:  remove PendingIntent] PendingIntent{155a6b3: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
06-23 11:34:21.442  3486  3849 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
06-23 11:34:21.442  3928  4125 D NetworkController: onReceive: intent=Intent { act=com.samsung.intent.action.WIFI_CAPTIVE_NOT_LOGIN flg=0x10 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
06-23 11:34:21.442  3928  4125 D NetworkController.WifiSignalController: updateWifiState : mCurrentState.wifiCaptiveNotLogin = false
06-23 11:34:21.442  3486  3849 D SecContentProvider: insert(), uri = 2
,06-23 11:34:21.442  9374  9384 D BluetoothAdapter: onBluetoothStateChange: up=true
06-23 11:34:21.442  9374  9384 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,06-23 11:34:21.452  7594  7604 D BluetoothAdapter: onBluetoothStateChange: up=true
,06-23 11:34:21.452  7594  7604 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
06-23 11:34:21.452  3486  3849 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
,06-23 11:34:21.452  3486  3849 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
06-23 11:34:21.452  3486  3849 D WifiStateMachine: sendBroadcastForCaptivePortalNotLoginIcon : false
06-23 11:34:21.452  3486  3589 D BluetoothA2dp: onBluetoothStateChange: up=true
,06-23 11:34:21.452  3486  3589 D BluetoothA2dp: Binding service...
06-23 11:34:21.452  3486  3589 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,06-23 11:34:21.452  3486  3849 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
,06-23 11:34:21.452  3928  4125 D NetworkController: onReceive: intent=Intent { act=com.samsung.intent.action.WIFI_CAPTIVE_NOT_LOGIN flg=0x10 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
06-23 11:34:21.452  3928  4125 D NetworkController.WifiSignalController: updateWifiState : mCurrentState.wifiCaptiveNotLogin = false
,06-23 11:34:21.452  3928  4524 D BluetoothAdapter: onBluetoothStateChange: up=true
,06-23 11:34:21.452  3928  4524 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
06-23 11:34:21.452  3928  3959 D BluetoothPbap: onBluetoothStateChange: up=true
06-23 11:34:21.452  3928  3959 D BluetoothPbap: Binding service...
,06-23 11:34:21.462  4809  9488 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,06-23 11:34:21.462  4809  9488 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,06-23 11:34:21.462  3486  3970 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7f8486 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{214f1fb 7032:com.google.android.apps.maps/u0a119}
,06-23 11:34:21.462  3486  3486 D BluetoothA2dp: Proxy object connected
,06-23 11:34:21.472  3928  3928 D BluetoothA2dp: Proxy object connected
,06-23 11:34:21.472  3928  3928 D A2dpProfile: Bluetooth service connected
,06-23 11:34:21.472  3486  3849 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
,06-23 11:34:21.472  3486  3849 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,06-23 11:34:21.472  3486  3848 D WifiP2pService: InactiveState{ what=143375 }
06-23 11:34:21.472  3486  3848 D WifiP2pService: P2pEnabledState{ what=143375 }
,06-23 11:34:21.472  3486  3504 V AlarmManager:  remove PendingIntent] PendingIntent{d88a79c: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:21.472  9098  9109 D BluetoothLeAudio: onBluetoothStateChange: up=true
,06-23 11:34:21.472  8749  8760 D BluetoothAdapter: onBluetoothStateChange: up=true
,06-23 11:34:21.472  8749  8760 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
06-23 11:34:21.472  4809  9489 D BluetoothSocket: bindListen(): myUserId = 0
,06-23 11:34:21.472  4809  9489 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
06-23 11:34:21.482  9098  9110 D BluetoothSap: onBluetoothStateChange: up=true
06-23 11:34:21.482  9098  9110 D BluetoothSap: Binding service...
,06-23 11:34:21.482  3486  3970 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4e915a5 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{714895a 4842:com.samsung.android.providers.context/u0a7}
,06-23 11:34:21.492  3486  4956 V AlarmManager:  remove PendingIntent] PendingIntent{e74ad7a: PendingIntentRecord{6956433 android broadcastIntent}}
,06-23 11:34:21.492  3151  3629 D CommandListener: Clearing all IP addresses on wlan0
06-23 11:34:21.492  3928  4125 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,06-23 11:34:21.502  4273  7679 V NativeCrypto: Read error: ssl=0x7f6e4ece80: I/O error during system call, Connection timed out
,06-23 11:34:21.502  4809  4830 D A2dpStateMachine: getConnectedDevices : size=0
,06-23 11:34:21.512  9098  9098 D BluetoothSap: Proxy object connected
06-23 11:34:21.512  9098  9098 D SapProfile: Bluetooth service connected
,06-23 11:34:21.512  4809  9489 I BtOppRfcommListener: Accept thread started.
,06-23 11:34:21.512  4273  7679 V NativeCrypto: SSL shutdown failed: ssl=0x7f6e4ece80: I/O error during system call, Broken pipe
,06-23 11:34:21.522  3486  3858 E ConnectivityService: updateNetworkInfo()
06-23 11:34:21.522  3486  3858 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -38]
06-23 11:34:21.522  3486  3858 E ConnectivityService: updateNetworkInfo()
,06-23 11:34:21.522  3486  3858 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = DISCONNECTED
06-23 11:34:21.522  3486  3858 D NtpTrustedTime: currentTimeMillis() cache hit
06-23 11:34:21.522  3486  3858 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 6
06-23 11:34:21.522  3486  3858 V NetworkStats: updateIfacesLocked()
06-23 11:34:21.522  3486  3858 V NetworkStats: performPollLocked(flags=0x1)
,06-23 11:34:21.522  3928  4524 D BluetoothMap: onBluetoothStateChange: up=true
06-23 11:34:21.522  3928  4524 D BluetoothMap: Binding service...
06-23 11:34:21.522  3486  3969 V AlarmManager:  remove PendingIntent] PendingIntent{37a6721: PendingIntentRecord{c15dbf7 com.google.android.gms broadcastIntent}}
,06-23 11:34:21.522  3486  3858 D NetworkStatsRecorder: entry.iface is null
06-23 11:34:21.522  3486  3858 D NetworkStatsRecorder: entry.iface is null
06-23 11:34:21.522  3486  3858 D NetworkStatsRecorder: entry.iface is null
06-23 11:34:21.522  3486  3858 D NetworkStatsRecorder: entry.iface is null
,06-23 11:34:21.532  3486  3858 V NetworkStats: performPollLocked() took 6ms
06-23 11:34:21.532  3486  3858 D NtpTrustedTime: currentTimeMillis() cache hit
,06-23 11:34:21.532  4273  7679 E GCM     : Wifi connection closed with errorCode 20
,06-23 11:34:21.532  3486  3970 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b102746 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{714895a 4842:com.samsung.android.providers.context/u0a7}
,06-23 11:34:21.542  3486  3486 I WifiTrafficPoller: evaluateTrafficStatsPolling
,06-23 11:34:21.542  3486  3486 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
,06-23 11:34:21.542  3486  3486 D HS20StateMachine: [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true]
06-23 11:34:21.542  3486  3486 D HS20StateMachine: checkifOSUAP  null disconnectedFromSsid"NG700"
06-23 11:34:21.542  3486  3486 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
06-23 11:34:21.542  3486  3856 I WifiHs20Service: Message received 5007
,06-23 11:34:21.542  3486  3486 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
,06-23 11:34:21.542  3928  4125 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
06-23 11:34:21.552  4245  4245 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
06-23 11:34:21.552  4809  5345 D A2dpStateMachine: getConnectedDevices : size=0
,06-23 11:34:21.552  3928  3928 D BluetoothPbap: Proxy object connected
06-23 11:34:21.552  3928  3928 D PbapServerProfile: Bluetooth service connected
,06-23 11:34:21.552  3928  3928 D BluetoothMap: Proxy object connected
06-23 11:34:21.552  3928  3928 D MapProfile: Bluetooth service connected
06-23 11:34:21.552  3928  3928 D BluetoothMap: getConnectedDevices()
,06-23 11:34:21.562  4842  4906 D BluetoothA2dp: onBluetoothStateChange: up=true
06-23 11:34:21.562  4842  4906 D BluetoothA2dp: Binding service...
,06-23 11:34:21.562  3486  3858 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-23 11:34:21.562  3486  3858 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -38]
06-23 11:34:21.562  3486  3849 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,06-23 11:34:21.562  4842  4906 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,06-23 11:34:21.562  3486  3848 D WifiP2pService: InactiveState{ what=131204 }
06-23 11:34:21.562  3486  3486 D WifiNotificationController: SHOW_NOTI_MESSAGE : 17, visible : false, ssid : null, targetSSID : null, netId : -1, titleType : -1
06-23 11:34:21.562  3486  3848 D WifiP2pService: P2pEnabledState{ what=131204 }
,06-23 11:34:21.562  3486  3975 V AlarmManager:  remove PendingIntent] PendingIntent{375545d: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
06-23 11:34:21.562  3486  3486 D WifiNotificationController: showMaliciousHotspotDetectionNotification - MaliciousNetwork:null, visible:false
06-23 11:34:21.562  3486  3848 D WifiP2pService: sending p2p persistent groups changed broadcast
06-23 11:34:21.562  3486  3858 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,06-23 11:34:21.562  3486  3858 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-23 11:34:21.562  3486  3858 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-23 11:34:21.562  3486  3858 D ConnectivityService: sending notification LOST for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-23 11:34:21.562  3486  3858 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
06-23 11:34:21.562  3486  3858 D ConnectivityService: sending notification LOST for NetworkRequest [ id=5, legacyType=-1, [] ]
06-23 11:34:21.562  3486  3858 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-23 11:34:21.562  3486  3847 D NtpTrustedTime: currentTimeMillis() cache hit
06-23 11:34:21.562  3486  3858 D ConnectivityService: sending notification LOST for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-23 11:34:21.562  3486  3847 D NtpTrustedTime: currentTimeMillis() cache hit
06-23 11:34:21.562  3486  3858 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-23 11:34:21.562  3486  4379 D ConnectivityService: getVpnConfig > userId : 0
,06-23 11:34:21.562  3486  3858 D ConnectivityService: sending notification LOST for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-23 11:34:21.562  3486  3486 D RttService: SCAN_AVAILABLE : 1
06-23 11:34:21.572  3486  3883 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
06-23 11:34:21.572  3486  3858 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-23 11:34:21.572  3486  3858 D ConnectivityService: sending notification LOST for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-23 11:34:21.572  3486  3858 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-23 11:34:21.572  3486  4955 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
06-23 11:34:21.572  3486  3849 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-23 11:34:21.572  3486  3849 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-23 11:34:21.572  3486  3849 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,06-23 11:34:21.572  3486  3849 D WIFI    : evalRequest
06-23 11:34:21.572  3486  3849 D WIFI    :   needNetworkFor
06-23 11:34:21.572  3486  3849 D WIFI_UT : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-23 11:34:21.572  3486  3849 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-23 11:34:21.572  3486  3849 D WIFI_UT : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
06-23 11:34:21.572  3486  3849 D WIFI_UT : evalRequest
06-23 11:34:21.572  3486  3849 D WIFI_UT :   done
06-23 11:34:21.572  3486  3849 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-23 11:34:21.572  3486  3849 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-23 11:34:21.572  3486  3849 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
06-23 11:34:21.572  3486  3849 D WIFI    : evalRequest
06-23 11:34:21.572  3486  3849 D WIFI    :   done
06-23 11:34:21.572  3486  3884 D Ethernet: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-23 11:34:21.572  3486  3884 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
06-23 11:34:21.572  3486  3884 D Ethernet: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,06-23 11:34:21.572  3486  3884 D Ethernet: evalRequest
06-23 11:34:21.572  3486  3884 D Ethernet:   done
,06-23 11:34:21.572  3486  3567 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{59771d2 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{aa2736c 6417:com.enhance.gameservice/u0a106}
,06-23 11:34:21.582  4116  4116 I wpa_supplicant: P2P: Set prekey state (NONE -> NONE)
06-23 11:34:21.582  4116  4116 I wpa_supplicant: P2P: Clear a pre-passphrase (State NONE)
,06-23 11:34:21.582  3486  3848 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,06-23 11:34:21.582  4842  4842 D BluetoothA2dp: Proxy object connected
,06-23 11:34:21.592  9098  9109 D BluetoothPan: onBluetoothStateChange on: true
06-23 11:34:21.592  9098  9109 D BluetoothPan: onBluetoothStateChange calling doBind()
,06-23 11:34:21.602  3486  3590 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:21.602  3486  3590 I WifiDisplayAdapter: onP2pDisconnected
06-23 11:34:21.602  3486  3590 D IpRemoteDisplayController: disconnectWfdBridgeServer
06-23 11:34:21.602  3486  3590 D IpRemoteDisplayController: WfdBridgeServer is already null
,06-23 11:34:21.602  9098  9098 D BluetoothPan: BluetoothPAN Proxy object connected
06-23 11:34:21.602  9098  9098 D PanProfile: Bluetooth service connected
,06-23 11:34:21.612  3151  3629 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,06-23 11:34:21.612  3486  3504 V AlarmManager:  remove PendingIntent] PendingIntent{932fcc: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:21.642  3151  3629 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,06-23 11:34:21.642  3486  3858 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -38]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} } wasDefault=true
06-23 11:34:21.642  3486  3858 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
06-23 11:34:21.642  3486  3858 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,06-23 11:34:21.642  3928  3928 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 272
,06-23 11:34:21.642  3928  3928 D WifiP2pController: onReceive android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,06-23 11:34:21.682  3486  3567 W ProcessCpuTracker: Skipping unknown process pid 9492
06-23 11:34:21.682  3486  3567 D ActivityManager:  getDeferredInfo final delay 300
,06-23 11:34:21.682  3486  3567 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b03b215 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9233b8d 8766:com.samsung.android.app.FileShareServer/5005}
,06-23 11:34:21.692  3486  3848 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,06-23 11:34:21.692  3486  3848 D SecContentProvider: insert(), uri = 2
,06-23 11:34:21.692  8766  8766 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,06-23 11:34:21.692  3486  3848 D WifiP2pService: P2pDisablingState
,06-23 11:34:21.692  3486  3848 D WIFI_P2P: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-23 11:34:21.692  3486  3848 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-23 11:34:21.702  3486  3848 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
06-23 11:34:21.702  3486  3848 D WIFI_P2P: evalRequest
06-23 11:34:21.702  3486  3848 D WIFI_P2P:   done
,06-23 11:34:21.702  3486  3848 D WifiP2pService: P2pDisablingState{ what=147458 }
06-23 11:34:21.702  3486  3848 D WifiP2pService: p2p socket connection lost
06-23 11:34:21.702  3486  3848 D SecContentProvider: insert(), uri = 2
,06-23 11:34:21.702  8766  8766 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,06-23 11:34:21.702  3486  3848 D WifiP2pService: P2pDisabledState
06-23 11:34:21.702  3486  3849 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,06-23 11:34:21.702  3486  9496 I ApplicationPolicy: updateDataUsageMap
,06-23 11:34:21.702  8766  8766 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
06-23 11:34:21.702  3486  3486 D Tethering: Tethering got CONNECTIVITY_ACTION
,06-23 11:34:21.712  3486  3589 D EntConnectivity: Not allowed due to - mEnabled false
,06-23 11:34:21.722  3486  3486 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:21.722  3486  3486 I CLocInfoService: ['16.5] External Intent Received android.net.conn.CONNECTIVITY_CHANGE
06-23 11:34:21.722  3486  3486 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:21.722  3486  3486 I CLocInfoService: CLoinfo wifi false
,06-23 11:34:21.722  3928  4125 D NetworkController: onReceive: intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,06-23 11:34:21.722  3486  3564 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
06-23 11:34:21.722  3486  3564 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-23 11:34:21.722  3486  4188 V AlarmManager:  remove PendingIntent] PendingIntent{c6556d1: PendingIntentRecord{e3fd536 android broadcastIntent}}
,06-23 11:34:21.722  3486  3860 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,06-23 11:34:21.722  3486  3564 D GpsLocationProvider: updateNetworkState unavailable info: [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:21.722  3486  4186 W SLocation: No Active Data Connection
06-23 11:34:21.722  3486  4186 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:21.722  3486  4186 W SLocation: No Active Data Connection
,06-23 11:34:21.732  4245  4255 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,06-23 11:34:21.732  4245  4255 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,06-23 11:34:21.732  3486  3860 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,06-23 11:34:21.732  3486  3486 V MARsPolicyManager: DataConnection: false
,06-23 11:34:21.742  4726  4726 D SamsungIME: EngineType = SWIFTKEY
,06-23 11:34:21.742  4857  4965 D CellLocationSupport: onReceive ACTION = android.net.conn.CONNECTIVITY_CHANGE
06-23 11:34:21.742  4857  4965 I CellLocationSupport: onCellLocationChanged
,06-23 11:34:21.742  4245  4606 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,06-23 11:34:21.742  4245  4606 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,06-23 11:34:21.742  3486  3564 D TelephonyManager: getDataEnabled: retVal=true
06-23 11:34:21.742  4857  4857 D PdnController: CONNECTIVITY_ACTION: networkType 1 isConnected false
06-23 11:34:21.742  4857  4857 D PdnController: isSuspended [false] networktype [1]
,06-23 11:34:21.742  3486  3504 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-23 11:34:21.742  4857  4857 D PdnController: isPdnUp  [false] networktype [1]
06-23 11:34:21.742  3151  3629 E Netd    : netlink response contains error (No such file or directory)
06-23 11:34:21.742  4857  4857 D PdnController: Notify Result to LocalIP Registrants! : networkType [1] isConnected [false] 
06-23 11:34:21.742  3151  3629 D CommandListener: Clearing all IP addresses on wlan0
,06-23 11:34:21.742  3486  3858 D ConnectivityService: setProvNotificationVisibleIntent SIGN_IN visible=false networkType=WIFI extraInfo=null highPriority=false
06-23 11:34:21.742  3486  3858 D ConnectivityService: nai.networkMonitor.doQuit()
06-23 11:34:21.742  3486  3858 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: doQuit - quitNow()
06-23 11:34:21.742  3486  3858 E ConnectivityService: updateNetworkInfo()
06-23 11:34:21.752  3486  3858 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-23 11:34:21.752  3486  3858 E ConnectivityService: updateNetworkInfo()
06-23 11:34:21.752  3486  3858 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
,06-23 11:34:21.752  5371  5371 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@e945f8e and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,06-23 11:34:21.762  3486  3847 D NtpTrustedTime: currentTimeMillis() cache hit
,06-23 11:34:21.762  3486  3847 D NtpTrustedTime: currentTimeMillis() cache hit
06-23 11:34:21.762  3486  3847 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-23 11:34:21.762  3486  3847 D NtpTrustedTime: currentTimeMillis() cache hit
06-23 11:34:21.762  3486  3847 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
06-23 11:34:21.762  3486  3847 D NtpTrustedTime: currentTimeMillis() cache hit
,06-23 11:34:21.762  4726  4726 D SamsungIME: mNetworkChangeReceiver isWLANConnected : false
,06-23 11:34:21.772  4857  4965 I CellLocationSupport: Block to update PANI information in non VoWIFI
06-23 11:34:21.772  4857  4965 D SlickSSConfigHandler: EVENT_LOCAL_IP_CHANGED
,06-23 11:34:21.772  3486  4434 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-23 11:34:21.772  3486  3505 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:21.772  4857  4965 D PdnController: isIfaceDisconnected result [true] networkType [0] interfaceName [null] 
06-23 11:34:21.772  4857  4965 D PdnController: isPdnUp  [false] networktype [0]
06-23 11:34:21.772  4857  4965 D SlickSSConfigHandler: handleNetworkStateChange: check isDefaultPDNConnected[false], mReadyForDocFetch[false
,06-23 11:34:21.782  6764  6764 I FOTA_AGENT: [com.samsung.android.app.syncmldm.XDMService(1060/IIllllIIlIIllIIIIlll)] WiFi network Connected : false
,06-23 11:34:21.782  3486  3969 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-23 11:34:21.782  4374  4374 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,06-23 11:34:21.782  4857  4965 D RegistrationManager: handleMessage(): 5
,06-23 11:34:21.792  3486  4379 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-23 11:34:21.792  4857  4965 D PdnController: isIfaceDisconnected result [true] networkType [11] interfaceName [null] 
06-23 11:34:21.792  4857  4965 D PdnController: isPdnUp  [false] networktype [11]
06-23 11:34:21.792  4857  4965 D RegistrationManager: setEPDGIPSecConnected [false]
06-23 11:34:21.792  4857  4965 D RegistrationManager: notifyNetworkState : NetworkType [1] IsConnected [false] IPAddresses [[]] DNSAddresses [[]] 
06-23 11:34:21.792  4857  4965 D RegistrationManager: isEPDGAvailable [false]
06-23 11:34:21.792  4857  4965 D CoreController: setState [DEREGISTERED]
,06-23 11:34:21.792  3151  3625 D EnterpriseController: netId is 0
06-23 11:34:21.792  3151  3625 D Netd    : getNetworkForDns: using netid 0 for uid 10001
,06-23 11:34:21.792  4581  9500 E         : Error communicating to API: https://prod.yana.asideas.de/api/v2/advertising/frequencies/pl
06-23 11:34:21.792  4581  9500 E         : retrofit.RetrofitError: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
06-23 11:34:21.792  4581  9500 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:395)
06-23 11:34:21.792  4581  9500 E         : 	at retrofit.RestAdapter$RestHandler.access$100(RestAdapter.java:220)
06-23 11:34:21.792  4581  9500 E         : 	at retrofit.RestAdapter$RestHandler$1.invoke(RestAdapter.java:265)
06-23 11:34:21.792  4581  9500 E         : 	at retrofit.RxSupport$2.run(RxSupport.java:55)
06-23 11:34:21.792  4581  9500 E         : 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
06-23 11:34:21.792  4581  9500 E         : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
06-23 11:34:21.792  4581  9500 E         : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
06-23 11:34:21.792  4581  9500 E         : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
06-23 11:34:21.792  4581  9500 E         : 	at retrofit.Platform$Android$2$1.run(Platform.java:142)
06-23 11:34:21.792  4581  9500 E         : 	at java.lang.Thread.run(Thread.java:818)
06-23 11:34:21.792  4581  9500 E         : Caused by: java.net.UnknownHostException: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
06-23 11:34:21.792  4581  9500 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:470)
06-23 11:34:21.792  4581  9500 E         : 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
06-23 11:34:21.792  4581  9500 E         : 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
06-23 11:34:21.792  4581  9500 E         : 	at com.squareup.okhttp.internal.Network$1.resolveInetAddresses(Network.java:29)
06-23 11:34:21.792  4581  9500 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:187)
06-23 11:34:21.792  4581  9500 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.nextProxy(RouteSelector.java:156)
06-23 11:34:21.792  4581  9500 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.next(RouteSelector.java:98)
06-23 11:34:21.792  4581  9500 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.createNextConnection(HttpEngine.java:344)
06-23 11:34:21.792  4581  9500 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:327)
06-23 11:34:21.792  4581  9500 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:245)
06-23 11:34:21.792  4581  9500 E         : 	at com.squareup.okhttp.Call.getResponse(Call.java:267)
06-23 11:34:21.792  4581  9500 E         : 	at com.squareup.okhttp.Call$ApplicationInterceptorChain.proceed(Call.java:224)
06-23 11:34:21.792  4581  9500 E         : 	at com.squareup.okhttp.Call.getResponseWithInterceptorChain(Call.java:195)
06-23 11:34:21.792  4581  9500 E         : 	at com.squareup.okhttp.Call.execute(Call.java:79)
06-23 11:34:21.792  4581  9500 E         : 	at retrofit.client.OkClient.execute(OkClient.java:53)
06-23 11:34:21.792  4581  9500 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:326)
06-23 11:34:21.792  4581  9500 E         : 	... 9 more
06-23 11:34:21.792  4581  9500 E         : Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
06-23 11:34:21.792  4581  9500 E         : 	at libcore.io.Posix.android_getaddrinfo(Native Method)
06-23 11:34:21.792  4581  9500 E         : 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
06-23 11:34:21.792  4581  9500 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:451)
06-23 11:34:21.792  4581  9500 E         : 	... 24 more
06-23 11:34:21.792  4581  9500 E         : 
,06-23 11:34:21.792  4581  9500 E         : Unable to fetch advertisement frequency.
06-23 11:34:21.792  4581  9500 E         : retrofit.RetrofitError: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
06-23 11:34:21.792  4581  9500 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:395)
06-23 11:34:21.792  4581  9500 E         : 	at retrofit.RestAdapter$RestHandler.access$100(RestAdapter.java:220)
06-23 11:34:21.792  4581  9500 E         : 	at retrofit.RestAdapter$RestHandler$1.invoke(RestAdapter.java:265)
06-23 11:34:21.792  4581  9500 E         : 	at retrofit.RxSupport$2.run(RxSupport.java:55)
06-23 11:34:21.792  4581  9500 E         : 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
06-23 11:34:21.792  4581  9500 E         : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
06-23 11:34:21.792  4581  9500 E         : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
06-23 11:34:21.792  4581  9500 E         : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
06-23 11:34:21.792  4581  9500 E         : 	at retrofit.Platform$Android$2$1.run(Platform.java:142)
06-23 11:34:21.792  4581  9500 E         : 	at java.lang.Thread.run(Thread.java:818)
06-23 11:34:21.792  4581  9500 E         : Caused by: java.net.UnknownHostException: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
06-23 11:34:21.792  4581  9500 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:470)
06-23 11:34:21.792  4581  9500 E         : 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
06-23 11:34:21.792  4581  9500 E         : 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
06-23 11:34:21.792  4581  9500 E         : 	at com.squareup.okhttp.internal.Network$1.resolveInetAddresses(Network.java:29)
06-23 11:34:21.792  4581  9500 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:187)
06-23 11:34:21.792  4581  9500 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.nextProxy(RouteSelector.java:156)
06-23 11:34:21.792  4581  9500 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.next(RouteSelector.java:98)
06-23 11:34:21.792  4581  9500 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.createNextConnection(HttpEngine.java:344)
06-23 11:34:21.792  4581  9500 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:327)
06-23 11:34:21.792  4581  9500 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:245)
06-23 11:34:21.792  4581  9500 E         : 	at com.squareup.okhttp.Call.getResponse(Call.java:267)
06-23 11:34:21.792  4581  9500 E         : 	at com.squareup.okhttp.Call$ApplicationInterceptorChain.proceed(Call.java:224)
06-23 11:34:21.792  4581  9500 E         : 	at com.squareup.okhttp.Call.getResponseWithInterceptorChain(Call.java:195)
06-23 11:34:21.792  4581  9500 E         : 	at com.squareup.okhttp.Call.execute(Call.java:79)
06-23 11:34:21.792  4581  9500 E         : 	at retrofit.client.OkClient.execute(OkClient.java:53)
06-23 11:34:21.792  4581  9500 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:326)
06-23 11:34:21.792  4581  9500 E         : 	... 9 more
06-23 11:34:21.792  4581  9500 E         : Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
06-23 11:34:21.792  4581  9500 E         : 	at libcore.io.Posix.android_getaddrinfo(Native Method)
06-23 11:34:21.792  4581  9500 E         : 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
06-23 11:34:21.792  4581  9500 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:451)
06-23 11:34:21.792  4581  9500 E         : 	... 24 more
06-23 11:34:21.792  4581  9500 E         : 
,06-23 11:34:21.812  9374  9374 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,06-23 11:34:21.812  9374  9374 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,06-23 11:34:21.812  3486  3486 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,06-23 11:34:21.812  3486  3590 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false, mScanRequestedInConnected = false
06-23 11:34:21.812  3486  3590 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
06-23 11:34:21.822  3486  3590 D WifiDisplayController: disconnect
06-23 11:34:21.822  3486  3590 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,06-23 11:34:21.822  3928  3928 D WifiP2pController: onReceive android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,06-23 11:34:21.822  3486  3486 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
06-23 11:34:21.822  3486  3486 I InputMethodManagerService: [BT Setting State] State =12
06-23 11:34:21.822  3486  3486 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,06-23 11:34:21.832  3928  4125 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
06-23 11:34:21.832  3928  4125 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
06-23 11:34:21.832  9374  9374 D BluetoothAdapter: STATE_ON
,06-23 11:34:21.832  3486  3486 I Telecom : BluetoothPhoneService: queryPhoneState
06-23 11:34:21.832  3486  3486 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState : true
,06-23 11:34:21.832  4306  4306 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
,06-23 11:34:21.832  4726  4726 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
06-23 11:34:21.832  9374  9374 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-23 11:34:21.832  9374  9374 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-23 11:34:21.832  9374  9374 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
06-23 11:34:21.832  9374  9374 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-23 11:34:21.832  9374  9374 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-23 11:34:21.832  9374  9374 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-23 11:34:21.832  9374  9374 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
06-23 11:34:21.832  9374  9374 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-23 11:34:21.832  9374  9374 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,06-23 11:34:21.842  3486  3486 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
06-23 11:34:21.842  3486  3486 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
06-23 11:34:21.842  3486  3486 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,06-23 11:34:21.842  9374  9374 D BluetoothAdapter: STATE_ON
,06-23 11:34:21.842  9098  9098 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
06-23 11:34:21.842  9098  9098 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,06-23 11:34:21.842  7032  7203 I SQLiteDatabase: can't enable WAL for memory databases.
,06-23 11:34:21.842  9374  9374 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,06-23 11:34:21.842  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
06-23 11:34:21.842  3486  3589 D Tethering: MasterInitialState.processMessage what=3
,06-23 11:34:21.842  7032  7203 I SQLiteDatabase: can't enable WAL for memory databases.
06-23 11:34:21.852  3486  3849 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,06-23 11:34:21.852  4116  4116 I wpa_supplicant: Blacklist: Clear (all) 
06-23 11:34:21.852  4116  4116 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
06-23 11:34:21.852  9374  9374 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-23 11:34:21.852  4245  4606 D TelephonyProvider: query: url=content://telephony/carriers/preferapn, projectionIn=[Ljava.lang.String;@956f905, selection=nullselectionArgs=null, sort=name ASC
,06-23 11:34:21.862  4245  4606 D TelephonyProvider: query: match = 5
06-23 11:34:21.862  4245  4606 D TelephonyProvider: getPreferredApnId(subId = 2147483643),return -1
06-23 11:34:21.862  4245  4606 D TelephonyProvider: query: selection modified to edited!=2 and edited!=3 and edited!=5 and edited!=6
,06-23 11:34:21.862  4245  4245 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,06-23 11:34:21.872  9504  9504 E Zygote  : v2
06-23 11:34:21.872  9504  9504 I libpersona: KNOX_SDCARD checking this for 10112
06-23 11:34:21.872  9504  9504 I libpersona: KNOX_SDCARD not a persona
,06-23 11:34:21.872  9504  9504 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,06-23 11:34:21.872  9504  9504 E Zygote  : accessInfo : 0
,06-23 11:34:21.872  9504  9504 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.talk 
,06-23 11:34:21.882  3486  4435 I ActivityManager: Start proc 9504:com.google.android.talk/u0a112 for broadcast-3 com.google.android.talk/com.google.android.apps.hangouts.service.GcmStateReceiver
,06-23 11:34:21.882  3486  3486 I WifiTrafficPoller: evaluateTrafficStatsPolling
06-23 11:34:21.882  3486  3486 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
06-23 11:34:21.882  3486  3486 D HS20StateMachine: [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false]
06-23 11:34:21.882  3486  3486 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
06-23 11:34:21.882  3486  3486 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
06-23 11:34:21.882  3486  3856 I WifiHs20Service: Message received 5007
,06-23 11:34:21.892  3151  3622 D Netd    : Iface p2p0 link up
,06-23 11:34:21.892  3928  4125 W LocalBluetoothProfileManager: updateLocalProfiles :: MAP profile was previously added but the UUID is now missing.
06-23 11:34:21.892  3486  3571 D Tethering: interfaceLinkStateChanged p2p0, true
06-23 11:34:21.892  3486  3571 D Tethering: interfaceStatusChanged p2p0, true
06-23 11:34:21.892  3928  4125 W LocalBluetoothProfileManager: updateLocalProfiles :: PBAP profile was previously added but the UUID is now missing.
06-23 11:34:21.892  3928  4125 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
06-23 11:34:21.892  3928  4125 W LocalBluetoothProfileManager: updateLocalProfiles :: HID profile was previously added but the UUID is now missing.
06-23 11:34:21.892  3928  4125 W LocalBluetoothProfileManager: updateLocalProfiles :: BleAudio profile was created already 
06-23 11:34:21.892  9504  9504 D TimaKeyStoreProvider: TimaSignature is unavailable
06-23 11:34:21.892  9504  9504 D ActivityThread: Added TimaKeyStore provider
,06-23 11:34:21.892  4857  4875 D PdnController: Interface Changed p2p0 link up
,06-23 11:34:21.902  9516  9516 E Zygote  : v2
06-23 11:34:21.902  9516  9516 I libpersona: KNOX_SDCARD checking this for 10049
06-23 11:34:21.902  9516  9516 E Zygote  : isSdpEnabledProcess - SDP enabled
06-23 11:34:21.902  9516  9516 I libpersona: KNOX_SDCARD not a persona
06-23 11:34:21.902  9516  9516 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,06-23 11:34:21.902  9516  9516 E Zygote  : accessInfo : 64
06-23 11:34:21.902  9516  9516 E Zygote  : isSdpEnabledProcess - SDP enabled
06-23 11:34:21.902  9516  9516 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10049 / [uid]: 10049
06-23 11:34:21.902  9516  9516 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.email.provider 
,06-23 11:34:21.902  3486  3970 I ActivityManager: Start proc 9516:com.samsung.android.email.provider/u0a49 for content provider com.samsung.android.email.provider/.provider.database.EmailProvider
06-23 11:34:21.902  9374  9461 D BluetoothAdapter: STATE_ON
,06-23 11:34:21.912  4857  4965 D TranslatorCollection: translateToNwkSvcType: networkType XAN_NWK_TYPE_WLAN
06-23 11:34:21.912  4857  4965 D RegistrationManager: getNetworkType [0]
06-23 11:34:21.912  4857  4965 D CoreStackAdaptor2: notifyNetworkState() [1] isConnected [false] nwkSvcType  [XAN_NWK_TYPE_WLAN] nwkInfoType [XAN_SVC_NETWORK_SVCTYPE_WIFI] dedicated   [NONE] 
,06-23 11:34:21.912  4857  4965 D TranslatorCollection: translateToNwkSvcType: networkType XAN_NWK_TYPE_WLAN
06-23 11:34:21.912  4857  4965 D CoreStackAdaptor2: ipList =  Null
06-23 11:34:21.912  4857  4965 D RegistrationManager: tryRegister(CONNECTIVITY_STATUS_CHANGE)
,06-23 11:34:21.912  4857  4965 D RegistrationManager: isPreconditionProperToGoOn
06-23 11:34:21.912  3486  3590 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
06-23 11:34:21.912  4857  4965 D RegistrationManager: isDeviceShutdown [false]
06-23 11:34:21.912  3486  3590 I WifiDisplayAdapter: onP2pDisconnected
06-23 11:34:21.912  4857  4965 D RegistrationManager: isStackShuttingDownForAllPDNs [false]
06-23 11:34:21.912  3486  3590 D IpRemoteDisplayController: disconnectWfdBridgeServer
06-23 11:34:21.912  4857  4965 D RegistrationManager: isDmVoLTEUpdated [false]
06-23 11:34:21.912  3486  3590 D IpRemoteDisplayController: WfdBridgeServer is already null
,06-23 11:34:21.912  4857  4965 D RegistrationManager: tryRegister : Abort Reason [IMS feature disabled]
06-23 11:34:21.912  3486  4049 V AlarmManager:  remove PendingIntent] PendingIntent{97a5a91: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
06-23 11:34:21.912  4857  4965 D RegistrationManager: tryRegister : Not all preconditions are met!
,06-23 11:34:21.912  9098  9098 D LocalBluetoothProfileManager: Adding local A2DP profile
,06-23 11:34:21.922  9374  9461 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-23 11:34:21.922  9374  9461 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-23 11:34:21.922  9374  9461 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
06-23 11:34:21.922  9374  9461 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-23 11:34:21.922  9374  9461 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-23 11:34:21.922  9374  9461 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-23 11:34:21.922  9374  9461 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
06-23 11:34:21.922  9374  9461 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-23 11:34:21.922  9374  9461 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,06-23 11:34:21.922  9098  9098 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,06-23 11:34:21.922  4551  9528 D MdnsClient: Multicast lock held. Releasing
06-23 11:34:21.922  9374  9461 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,06-23 11:34:21.922  9374  9439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-23 11:34:21.932  3486  3486 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
,06-23 11:34:21.932  3486  3486 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
06-23 11:34:21.932  3486  3856 I WifiHs20Service: Message received 5011
,06-23 11:34:21.932  9516  9516 D TimaKeyStoreProvider: TimaSignature is unavailable
06-23 11:34:21.932  9516  9516 D ActivityThread: Added TimaKeyStore provider
06-23 11:34:21.932  3486  3486 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,06-23 11:34:21.932  3486  3860 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,06-23 11:34:21.932  3928  3928 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
06-23 11:34:21.932  3928  3928 I HotspotTile: Provider is not defined returning false
,06-23 11:34:21.932  3928  3928 D HotspotTile: onReceive : 0, 0
,06-23 11:34:21.932  4245  4619 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
06-23 11:34:21.932  4245  4619 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,06-23 11:34:21.932  3486  3860 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,06-23 11:34:21.942  3928  3928 D SoundPathController: onReceive - android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,06-23 11:34:21.942  3928  3928 D ApMirroringController: onReceive android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,06-23 11:34:21.942  3928  3928 D AllShareCastTile: onReceive : android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,06-23 11:34:21.942  3486  4049 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
06-23 11:34:21.942  3928  3928 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,06-23 11:34:21.942  3486  3486 D WifiNotificationController: SHOW_NOTI_MESSAGE : 17, visible : false, ssid : null, targetSSID : null, netId : -1, titleType : -1
06-23 11:34:21.942  3486  3849 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
06-23 11:34:21.942  3486  3486 D WifiNotificationController: showMaliciousHotspotDetectionNotification - MaliciousNetwork:null, visible:false
06-23 11:34:21.942  3486  3564 E GpsLocationProvider: No APN found to select.
06-23 11:34:21.942  3486  3847 D NetworkPolicy: isUidForegroundLocked: 10049, mScreenOn: true, uidstate: -1, mProxSensorScreenOff: false
,06-23 11:34:21.942  3486  4422 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,06-23 11:34:21.942  9374  9374 D BluetoothAdapter: STATE_ON
,06-23 11:34:21.942  9098  9098 D LocalBluetoothProfileManager: Adding local HEADSET profile
,06-23 11:34:21.952  4116  4116 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,06-23 11:34:21.952  4116  4116 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,06-23 11:34:21.952  3486  4422 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,06-23 11:34:21.962  9098  9098 E BluetoothHeadset: BTStateChangeCB is registed
,06-23 11:34:21.962  3151  3622 D Netd    : Iface wlan0 link up
06-23 11:34:21.962  3486  3571 D Tethering: interfaceLinkStateChanged wlan0, true
06-23 11:34:21.962  3486  3571 D Tethering: interfaceStatusChanged wlan0, true
,06-23 11:34:21.962  4857  4872 D PdnController: Interface Changed wlan0 link up
,06-23 11:34:21.962  9098  9098 W LocalBluetoothProfileManager: updateLocalProfiles :: MAP profile was previously added but the UUID is now missing.
06-23 11:34:21.962  9098  9098 W LocalBluetoothProfileManager: updateLocalProfiles :: PBAP profile was previously added but the UUID is now missing.
06-23 11:34:21.962  9098  9098 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
06-23 11:34:21.962  9098  9098 W LocalBluetoothProfileManager: updateLocalProfiles :: HID profile was previously added but the UUID is now missing.
06-23 11:34:21.962  9098  9098 W LocalBluetoothProfileManager: updateLocalProfiles :: BleAudio profile was created already 
,06-23 11:34:21.962  3486  4422 D WifiService: setWifiEnabled: true pid=9374, uid=10074
,06-23 11:34:21.972  9374  9374 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-23 11:34:21.972  9374  9374 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-23 11:34:21.972  9374  9374 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
06-23 11:34:21.972  9374  9374 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-23 11:34:21.972  9374  9374 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-23 11:34:21.972  9374  9374 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-23 11:34:21.972  9374  9374 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
06-23 11:34:21.972  9374  9374 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-23 11:34:21.972  9374  9374 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-23 11:34:21.972  9374  9374 D BluetoothAdapter: STATE_ON
,06-23 11:34:21.972  9374  9374 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,06-23 11:34:21.972  9516  9516 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in com.samsung.android.email.provider rsrc of package com.samsung.android.email.provider
,06-23 11:34:21.982  3486  4395 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{97bf382 u0 com.google.android.gcm.DISCONNECTED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6847a93 9504:com.google.android.talk/u0a112}
,06-23 11:34:21.982  3486  4422 W ActivityManager: Permission Denial: getCurrentUser() from pid=9374, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
06-23 11:34:21.982  3486  4422 W WifiService: Failed getting userId using ActivityManagerNative
06-23 11:34:21.982  3486  4422 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9374, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
06-23 11:34:21.982  3486  4422 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
06-23 11:34:21.982  3486  4422 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
06-23 11:34:21.982  3486  4422 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
06-23 11:34:21.982  3486  4422 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
06-23 11:34:21.982  3486  4422 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
06-23 11:34:21.982  3486  3567 D ActivityManager:  getDeferredInfo final delay 300
06-23 11:34:21.982  3486  4422 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
,06-23 11:34:21.982  3486  4422 D SettingsProvider: isChangeAllowed() : name = wifi_on
,06-23 11:34:21.982  3486  3852 D WifiStateMachine: setFccChannel: channel = -1
06-23 11:34:21.982  3486  3852 D WifiController: [FCC]setFccChannel() is called !!!
06-23 11:34:21.982  3486  3852 D WifiStateMachine: setFccChannel: channel = -1
06-23 11:34:21.982  3486  3852 D WifiController: [FCC]Airplane off, setFccChannel(-1)!!!
06-23 11:34:21.982  3486  3852 D SecContentProvider: insert(), uri = 2
,06-23 11:34:21.982  3486  4285 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,06-23 11:34:21.982  3486  4257 V AlarmManager:  remove PendingIntent] PendingIntent{8f4cac9: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:21.982  9516  9516 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,06-23 11:34:21.992  3486  3849 D WifiBigDataLog: getJsonFormat() - feature : ONOF
06-23 11:34:21.992  3486  3849 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,06-23 11:34:21.992  9516  9516 D ResourcesManager: For user 0 new overlays fetched Null
,06-23 11:34:22.012  3486  3849 D WifiBigDataLog: init : 
,06-23 11:34:22.012  3486  3847 D NetworkPolicy: isUidForegroundLocked: 10049, mScreenOn: true, uidstate: 6, mProxSensorScreenOff: false
06-23 11:34:22.012  9504  9504 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.google.android.talk rsrc of package com.google.android.talk
,06-23 11:34:22.022  9374  9374 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-23 11:34:22.022  3486  4396 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,06-23 11:34:22.022  9098  9098 D BluetoothA2dp: Proxy object connected
,06-23 11:34:22.032  9504  9504 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,06-23 11:34:22.032  9516  9516 I InjectionManager: Inside getClassLibPath caller 
,06-23 11:34:22.032  3928  4125 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
06-23 11:34:22.032  3486  4433 D StatusBarManagerService: setIcon slot=bluetooth index=18 icon=StatusBarIcon(icon=Icon(typ=RESOURCE pkg=com.android.systemui id=0x7f02049a) visible user=0 )
06-23 11:34:22.032  3486  4258 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
06-23 11:34:22.032  3486  4434 V AlarmManager:  remove PendingIntent] PendingIntent{679c5ce: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:22.032  3928  4181 D BluetoothTile: handleUpdateState :  supported = true, enabled = true, enabling = false, connected = false, connecting = false, mController.getLastDeviceName() = null
,06-23 11:34:22.032  3928  4125 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,06-23 11:34:22.042  9098  9098 D A2dpProfile: Bluetooth service connected
,06-23 11:34:22.042  3486  3975 V AlarmManager:  remove PendingIntent] PendingIntent{7722cef: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:22.042  9504  9504 D ResourcesManager: For user 0 new overlays fetched Null
,06-23 11:34:22.052  3486  3564 D libgps  : agps_ril_update_network_state: Waiting for IPC connection...
,06-23 11:34:22.052  4809  5246 D A2dpStateMachine: getConnectedDevices : size=0
,06-23 11:34:22.052  3928  3928 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 272
,06-23 11:34:22.062  3486  4285 V AlarmManager:  remove PendingIntent] PendingIntent{52823fc: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
06-23 11:34:22.062  9504  9504 I InjectionManager: Inside getClassLibPath caller 
,06-23 11:34:22.062  9516  9516 W System  : ClassLoader referenced unknown path: /system/priv-app/SecEmail_M/lib/arm64
,06-23 11:34:22.062  3486  4379 V AlarmManager:  remove PendingIntent] PendingIntent{47070da: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:22.062  3486  4049 V AlarmManager:  remove PendingIntent] PendingIntent{8dea90b: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:22.072  4116  4116 I wpa_supplicant: Blacklist: Clear (all) 
,06-23 11:34:22.072  4116  4116 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,06-23 11:34:22.072  9504  9504 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm64
,06-23 11:34:22.072  3486  4422 V AlarmManager:  remove PendingIntent] PendingIntent{7d183e8: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:22.072  3486  3975 V AlarmManager:  remove PendingIntent] PendingIntent{7d60a01: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:22.082  3486  4396 D RCPManagerService: exchangeData() failure , invalid userId
,06-23 11:34:22.082  3486  4379 V AlarmManager:  remove PendingIntent] PendingIntent{af4c0a6: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:22.082  3486  3969 V AlarmManager:  remove PendingIntent] PendingIntent{34ccae7: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:22.082  3486  4422 V AlarmManager:  remove PendingIntent] PendingIntent{32ef694: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:22.092  3486  4434 V AlarmManager:  remove PendingIntent] PendingIntent{498453d: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:22.102  3486  4395 V AlarmManager:  remove PendingIntent] PendingIntent{41c4132: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:22.102  9504  9504 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.google.android.talk rsrc of package com.google.android.talk
,06-23 11:34:22.112  3486  4258 V AlarmManager:  remove PendingIntent] PendingIntent{a912e83: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:22.112  3486  4434 D RCPManagerService: exchangeData() failure , invalid userId
,06-23 11:34:22.112  9516  9516 D InjectionManager: InjectionManager
,06-23 11:34:22.112  9516  9516 D InjectionManager: fillFeatureStoreMap com.samsung.android.email.provider
,06-23 11:34:22.122  9516  9516 I InjectionManager: Constructor com.samsung.android.email.provider, Feature store :{}
,06-23 11:34:22.122  9516  9516 I InjectionManager: featureStore :{}
,06-23 11:34:22.122  3486  4396 V AlarmManager:  remove PendingIntent] PendingIntent{84ee800: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:22.132  3151  3622 D Netd    : Iface wlan0 link up
,06-23 11:34:22.132  3151  3622 D Netd    : Iface wlan0 link up
06-23 11:34:22.132  3486  3571 D Tethering: interfaceLinkStateChanged wlan0, true
06-23 11:34:22.132  3486  3571 D Tethering: interfaceStatusChanged wlan0, true
06-23 11:34:22.132  4857  5193 D PdnController: Interface Changed wlan0 link up
06-23 11:34:22.132  3486  3571 D Tethering: interfaceLinkStateChanged wlan0, true
06-23 11:34:22.132  3486  3571 D Tethering: interfaceStatusChanged wlan0, true
06-23 11:34:22.132  4857  4875 D PdnController: Interface Changed wlan0 link up
,06-23 11:34:22.142  3151  3622 D Netd    : Iface p2p0 link down
,06-23 11:34:22.142  3486  3571 D Tethering: interfaceLinkStateChanged p2p0, false
06-23 11:34:22.142  3486  3571 D Tethering: interfaceStatusChanged p2p0, false
,06-23 11:34:22.142  4857  4872 D PdnController: Interface Changed p2p0 link down
,06-23 11:34:22.142  3486  4379 I ActivityManager: Start proc 9536:com.samsung.android.email.provider:service/u0a49 for service com.samsung.android.email.provider/com.samsung.android.email.sync.service.EmailService
,06-23 11:34:22.142  9536  9536 E Zygote  : v2
,06-23 11:34:22.142  9536  9536 I libpersona: KNOX_SDCARD checking this for 10049
06-23 11:34:22.142  9536  9536 I libpersona: KNOX_SDCARD not a persona
06-23 11:34:22.152  9536  9536 E Zygote  : isSdpEnabledProcess - SDP enabled
,06-23 11:34:22.152  9536  9536 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,06-23 11:34:22.152  9536  9536 E Zygote  : accessInfo : 64
06-23 11:34:22.152  9536  9536 E Zygote  : isSdpEnabledProcess - SDP enabled
06-23 11:34:22.152  9536  9536 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10049 / [uid]: 10049
,06-23 11:34:22.152  9536  9536 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.email.provider:service 
,06-23 11:34:22.152  3486  4285 V AlarmManager:  remove PendingIntent] PendingIntent{448f839: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:22.162  4809  4809 D BleAudioService: onReceive:: INTENT mAobleStateChangeListener got : android.bluetooth.adapter.action.STATE_CHANGED
06-23 11:34:22.162  4809  4809 D BleAudioService: BluetoothAdapter.ACTION_STATE_CHANGED,  state is12
06-23 11:34:22.162  4809  9477 D BleAudioStateMachine_L: [Disconnected] Disconnected process message: 41
06-23 11:34:22.162  3486  4396 V AlarmManager:  remove PendingIntent] PendingIntent{3c93e7e: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
06-23 11:34:22.162  4809  9477 D BleAudioStateMachine_L: [Disconnected] MSG_ADAPTER_BT_ON_EVT event received
06-23 11:34:22.162  4809  9478 D BleAudioStateMachine_R: [Disconnected] Disconnected process message: 41
06-23 11:34:22.162  4809  9478 D BleAudioStateMachine_R: [Disconnected] MSG_ADAPTER_BT_ON_EVT event received
,06-23 11:34:22.162  3928  3928 D HeadsetProfile: Bluetooth service connected
06-23 11:34:22.162  4809  9477 D BleAudioStateMachine: getLastConnectedDeviceAddress() for channel = 1
06-23 11:34:22.162  4809  9477 D BleAudioService: NotifyEvents: n : 0
,06-23 11:34:22.162  4809  9478 D BleAudioStateMachine: getLastConnectedDeviceAddress() for channel = 2
06-23 11:34:22.162  4809  9478 D BleAudioService: NotifyEvents: n : 0
,06-23 11:34:22.172  3486  4258 I ActivityManager: Killing 8787:com.samsung.android.app.watchmanagerstub/u0a107 (adj 15): DHA:empty #33
,06-23 11:34:22.172  9098  9098 D HeadsetProfile: Bluetooth service connected
,06-23 11:34:22.182  3486  3486 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@12e2fdf
06-23 11:34:22.182  3486  3486 D BluetoothHeadset: registerMessageListener
,06-23 11:34:22.182  4809  5345 D HeadsetService: registerMessageListener
,06-23 11:34:22.182  4809  5345 D HeadsetService: registerMessageListener
,06-23 11:34:22.182  4809  9468 D HeadsetStateMachine: Disconnected process message: 70, size: 0
06-23 11:34:22.182  4809  9468 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@fb3b556
,06-23 11:34:22.182  3486  3486 I Telecom : BluetoothManager : register MessageListener
06-23 11:34:22.182  3486  3486 I Telecom : CallAudioManager: onBluetoothStateChange: no focus
,06-23 11:34:22.182  3486  3504 V AlarmManager:  remove PendingIntent] PendingIntent{8ba842c: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:22.192  4809  4809 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2) for masId0
,06-23 11:34:22.202  4809  9550 D BluetoothSocket: bindListen(): myUserId = 0
,06-23 11:34:22.202  4809  9550 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,06-23 11:34:22.202  3486  4285 D ActivityManager: cleanUpApplicationRecord -- 8787
,06-23 11:34:22.202  3486  3504 V AlarmManager:  remove PendingIntent] PendingIntent{1b7def5: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:22.212  3486  4285 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.watchmanagerstub, Auto Run ON
,06-23 11:34:22.212  4809  4809 D BluetoothSocket: bindListen(): myUserId = 0
06-23 11:34:22.212  4809  4809 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,06-23 11:34:22.212  9536  9536 D TimaKeyStoreProvider: TimaSignature is unavailable
06-23 11:34:22.212  9536  9536 D ActivityThread: Added TimaKeyStore provider
,06-23 11:34:22.222  4809  9550 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,06-23 11:34:22.222  4809  9550 D BluetoothSdpJni: SDP Create record success - handle: 0
,06-23 11:34:22.222  4809  9502 D A2dpStateMachine: getConnectedDevices : size=0
,06-23 11:34:22.242  4809  4809 D BluetoothSocket: bindListen(): myUserId = 0
06-23 11:34:22.242  4809  4809 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,06-23 11:34:22.242  3486  3969 V AlarmManager:  remove PendingIntent] PendingIntent{c449f56: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:22.242  9536  9536 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in com.samsung.android.email.provider rsrc of package com.samsung.android.email.provider
06-23 11:34:22.242  4809  4809 D ObexServerSockets: Succeed to create listening sockets 
06-23 11:34:22.242  4809  4809 D ObexServerSockets: startAccept()
,06-23 11:34:22.242  4809  9554 D ObexServerSockets: Accepting socket connection for masId0
,06-23 11:34:22.242  9536  9536 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
06-23 11:34:22.242  3486  4257 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
06-23 11:34:22.252  3486  3970 V AlarmManager:  remove PendingIntent] PendingIntent{4483bd7: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:22.252  4809  9555 D ObexServerSockets: Accepting socket connection for masId0
,06-23 11:34:22.262  9536  9536 D ResourcesManager: For user 0 new overlays fetched Null
,06-23 11:34:22.272  3486  4422 V AlarmManager:  remove PendingIntent] PendingIntent{4472cc4: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:22.272  4809  4809 D BluetoothMapMasInstance: set MAP SDP message type : 1
06-23 11:34:22.272  4809  4809 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
06-23 11:34:22.272  4809  4809 D BluetoothSdpJni: SDP Create record success - handle: 1
,06-23 11:34:22.272  3486  3975 V AlarmManager:  remove PendingIntent] PendingIntent{589f7ad: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:22.272  9536  9536 I InjectionManager: Inside getClassLibPath caller 
,06-23 11:34:22.282  3486  3567 D ActivityManager:  getDeferredInfo final delay 300
,06-23 11:34:22.282  3486  3505 V AlarmManager:  remove PendingIntent] PendingIntent{2035ae2: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:22.292  9504  9504 I Babel_telephony: TeleModule.onApplicationCreate
,06-23 11:34:22.292  9536  9536 W System  : ClassLoader referenced unknown path: /system/priv-app/SecEmail_M/lib/arm64
,06-23 11:34:22.302  9561  9561 E Zygote  : v2
06-23 11:34:22.302  9561  9561 I libpersona: KNOX_SDCARD checking this for 10003
06-23 11:34:22.302  9561  9561 I libpersona: KNOX_SDCARD not a persona
06-23 11:34:22.302  3486  3969 I ActivityManager: Start proc 9561:com.sec.android.provider.badge/u0a3 for content provider com.sec.android.provider.badge/.BadgeProvider
,06-23 11:34:22.302  9561  9561 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,06-23 11:34:22.302  3486  3970 V AlarmManager:  remove PendingIntent] PendingIntent{deabe73: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:22.302  3486  3975 V AlarmManager:  remove PendingIntent] PendingIntent{2ec5130: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
,06-23 11:34:22.312  9504  9567 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
06-23 11:34:22.312  9504  9567 I Babel_SMS: MmsConfig.loadMmsSettings
06-23 11:34:22.312  9561  9561 E Zygote  : accessInfo : 0
,06-23 11:34:22.312  9561  9561 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.provider.badge 
,06-23 11:34:22.312  3486  3504 V AlarmManager:  remove PendingIntent] PendingIntent{a7b61a9: PendingIntentRecord{4693982 com.android.bluetooth broadcastIntent}}
06-23 11:34:22.312  9504  9567 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/uaprof, mUaProfUrl=http://wap.samsungmobile.com/uaprof/uaprof.rdf
06-23 11:34:22.312  9504  9567 I Babel_SMS: MmsConfig.loadFromDatabase
,06-23 11:34:22.332  9561  9561 D TimaKeyStoreProvider: TimaSignature is unavailable
06-23 11:34:22.332  9561  9561 D ActivityThread: Added TimaKeyStore provider
,06-23 11:34:22.342  9504  9567 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
06-23 11:34:22.342  9504  9567 I Babel_SMS: MmsConfig.loadFromResources
,06-23 11:34:22.342  9504  9567 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
06-23 11:34:22.342  9504  9567 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/uaprof, mUaProfUrl=http://wap.samsungmobile.com/uaprof/uaprof.rdf
,06-23 11:34:22.352  9561  9561 W ResourcesManager: getTopLevelResources: /system/priv-app/BadgeProvider_M/BadgeProvider_M.apk / 1.0 running in com.sec.android.provider.badge rsrc of package com.sec.android.provider.badge
,06-23 11:34:22.352  9536  9536 I BNRClientProivder, VERSION : 1.7.5: register - xml6 quick_backup : Email, QJ5JBlRnP9, com.samsung.android.email.provider.service.sCloudBNRService
,06-23 11:34:22.352  9536  9536 I QBNRClientHelper: init SyncClientHelper : Email
06-23 11:34:22.352  3486  4379 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
06-23 11:34:22.352  9561  9561 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,06-23 11:34:22.352  9561  9561 D ResourcesManager: For user 0 new overlays fetched Null
,06-23 11:34:22.362  9561  9561 I InjectionManager: Inside getClassLibPath caller 
,06-23 11:34:22.372  9561  9561 W System  : ClassLoader referenced unknown path: /system/priv-app/BadgeProvider_M/lib/arm64
,06-23 11:34:22.372  9561  9561 D BadgeProvider: onCreate
06-23 11:34:22.372  9561  9561 D BadgeProvider: DatabaseHelper
,06-23 11:34:22.382  9504  9504 I Babel_Crash: Startup - clean
,06-23 11:34:22.382  9561  9561 D InjectionManager: InjectionManager
06-23 11:34:22.382  9561  9561 D InjectionManager: fillFeatureStoreMap com.sec.android.provider.badge
,06-23 11:34:22.392  9561  9561 I InjectionManager: Constructor com.sec.android.provider.badge, Feature store :{}
06-23 11:34:22.392  9561  9561 I InjectionManager: featureStore :{}
,06-23 11:34:22.392  3486  4396 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.SmsReceiver newState = 2 callingPackage = 10112
,06-23 11:34:22.392  3486  4379 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.MmsWapPushReceiver newState = 2 callingPackage = 10112
,06-23 11:34:22.402  3486  4258 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.AbortSmsReceiver newState = 2 callingPackage = 10112
,06-23 11:34:22.402  3486  3505 D RCPManagerService: exchangeData() failure , invalid userId
06-23 11:34:22.402  3486  4049 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1248000  uid : 1000  pid : 3486  pkgName : BADGE_UPDATE@CPU_MIN@1
,06-23 11:34:22.402  9536  9536 D InjectionManager: InjectionManager
06-23 11:34:22.402  9536  9536 D InjectionManager: fillFeatureStoreMap com.samsung.android.email.provider
,06-23 11:34:22.402  9536  9536 I InjectionManager: Constructor com.samsung.android.email.provider, Feature store :{}
06-23 11:34:22.402  9536  9536 I InjectionManager: featureStore :{}
,06-23 11:34:22.412  3486  3969 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver newState = 2 callingPackage = 10112
,06-23 11:34:22.412  3486  4395 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.service.NoConfirmationSmsSendService newState = 1 callingPackage = 10112
,06-23 11:34:22.412  9561  9573 D BaseReflect: null getOwnClass TEST
,06-23 11:34:22.412  9561  9573 D MethodReflector: android.content.ContentResolver getClass TEST
06-23 11:34:22.412  9561  9573 D BaseReflect: class android.content.ContentResolver isSupportClass TEST
06-23 11:34:22.412  9561  9573 D BaseReflect: class android.content.ContentResolver getOwnClass TEST
,06-23 11:34:22.422  3486  6038 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-23 11:34:22.422  4259  4259 D Launcher.Model: reloadBadges entered.
,06-23 11:34:22.422  9504  9504 I Babel_Prime: startMemoryMonitor
06-23 11:34:22.422  9504  9504 I Babel_Prime: isMemoryEnabled=false
,06-23 11:34:22.422  9504  9504 I Babel_Prime: isTimerEnabled=true
,06-23 11:34:22.422  9561  9573 D MethodReflector: notifyChange is called
,06-23 11:34:22.432  4259  4259 D Launcher.Model: reloadBadges entered.
06-23 11:34:22.432  9561  9573 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
06-23 11:34:22.432  9561  9573 D BadgeProvider: sendNotify, [notify] : null
,06-23 11:34:22.432  9561  9574 D BadgeProvider: query, [selection] : null
,06-23 11:34:22.432  9561  9573 D BadgeProvider: update, getCallingPackage() : com.samsung.android.email.provider
06-23 11:34:22.432  9561  9573 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
06-23 11:34:22.432  9561  9573 D BadgeProvider: update, [uri.query] : null
06-23 11:34:22.432  9561  9573 D BadgeProvider: update, [BadgeCount] : badgecount=0
06-23 11:34:22.432  9561  9573 D BadgeProvider: update, [UpdateCount] : 1
,06-23 11:34:22.432  4259  4338 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.email.provider = 0
06-23 11:34:22.432  4259  4338 D BadgeCache: 1. updateBadgeCounts: com.android.mms = 0
06-23 11:34:22.432  4259  4338 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 1
06-23 11:34:22.432  4259  4338 D BadgeCache: 2. updateBadgeCounts: com.android.settings/.Settings = 1
06-23 11:34:22.432  4259  4338 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 1
06-23 11:34:22.432  4259  4338 D BadgeCache: 2. updateBadgeCounts: com.android.settings/.GridSettings = 1
06-23 11:34:22.432  4259  4338 D BadgeCache: 1. updateBadgeCounts: com.sec.android.app.samsungapps = 0
06-23 11:34:22.432  4259  4338 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.sm = 0
,06-23 11:34:22.442  9504  9504 D InjectionManager: InjectionManager
,06-23 11:34:22.442  9504  9504 D InjectionManager: fillFeatureStoreMap com.google.android.talk
06-23 11:34:22.442  9504  9504 I InjectionManager: Constructor com.google.android.talk, Feature store :{}
06-23 11:34:22.442  9504  9504 I InjectionManager: featureStore :{}
,06-23 11:34:22.442  4809  9585 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,06-23 11:34:22.442  4809  9585 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,06-23 11:34:22.452  9561  9582 D BadgeProvider: query, [selection] : null
,06-23 11:34:22.452  3486  4285 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ed1643a u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a8d88eb 9374:com.thaliproject.thalitest/u0a74}
,06-23 11:34:22.462  3486  3505 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:22.462  3486  3505 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:22.462  3486  3505 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:22.462  3486  3505 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:22.462  3486  3505 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:22.462  3486  3505 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:22.462  3486  3505 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:22.462  3486  3505 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:22.462  3486  3505 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:22.462  3486  3505 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:22.462  3486  3505 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:22.462  3486  3505 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
06-23 11:34:22.462  3486  3505 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:22.462  3486  3505 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:22.462  3486  3505 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-23 11:34:22.462  4259  4338 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.email.provider = 0
06-23 11:34:22.462  4259  4338 D BadgeCache: 1. updateBadgeCounts: com.android.mms = 0
06-23 11:34:22.462  4259  4338 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 1
06-23 11:34:22.462  4259  4338 D BadgeCache: 2. updateBadgeCounts: com.android.settings/.Settings = 1
06-23 11:34:22.462  4259  4338 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 1
06-23 11:34:22.462  4259  4338 D BadgeCache: 2. updateBadgeCounts: com.android.settings/.GridSettings = 1
06-23 11:34:22.462  4259  4338 D BadgeCache: 1. updateBadgeCounts: com.sec.android.app.samsungapps = 0
06-23 11:34:22.462  4259  4338 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.sm = 0
,06-23 11:34:22.472  3486  4285 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ed1643a u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8b44752 3486:system/1000}
,06-23 11:34:22.472  3486  3486 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ed1643a u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{96cd387 4551:com.google.android.gms/u0a19}
,06-23 11:34:22.472  4551  4551 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,06-23 11:34:22.482  4551  5546 I iu.UploadsManager: num queued entries: 0
,06-23 11:34:22.482  4551  5546 I iu.UploadsManager: num updated entries: 0
06-23 11:34:22.482  4551  5546 I iu.SyncManager: NEXT; no task
,06-23 11:34:22.482  9374  9461 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,06-23 11:34:22.482  3486  4258 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,06-23 11:34:22.482  3486  4258 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,06-23 11:34:22.482  3486  4258 D WifiService: setWifiEnabled: true pid=9374, uid=10074
,06-23 11:34:22.492  3486  4379 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ed1643a u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{96cd387 4551:com.google.android.gms/u0a19}
,06-23 11:34:22.492  3486  4258 W ActivityManager: Permission Denial: getCurrentUser() from pid=9374, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
06-23 11:34:22.492  3486  4258 W WifiService: Failed getting userId using ActivityManagerNative
06-23 11:34:22.492  3486  4258 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9374, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
06-23 11:34:22.492  3486  4258 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
06-23 11:34:22.492  3486  4258 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
06-23 11:34:22.492  3486  4258 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
06-23 11:34:22.492  3486  4258 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
06-23 11:34:22.492  3486  4258 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
,06-23 11:34:22.492  3486  4258 D SettingsProvider: isChangeAllowed() : name = wifi_on
06-23 11:34:22.492  3486  4258 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
06-23 11:34:22.492  3486  3852 D WifiController: [FCC]setFccChannel() is called !!!
06-23 11:34:22.492  3486  3849 D WifiBigDataLog: getJsonFormat() - feature : ONOF
06-23 11:34:22.492  3486  3852 D WifiController: [FCC]Airplane off, setFccChannel(-1)!!!
06-23 11:34:22.492  3486  3852 D WifiStateMachine: setFccChannel: channel = -1
06-23 11:34:22.492  3486  3849 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,06-23 11:34:22.492  9504  9504 D Babel   : onCreate: Shutdown runnable posted in onCreate with a delay of 5000 ms.
,06-23 11:34:22.502  3486  4379 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ed1643a u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ff226b8 4273:com.google.android.gms.persistent/u0a19}
06-23 11:34:22.502  9504  9504 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in com.google.android.talk rsrc of package com.google.android.gms
,06-23 11:34:22.502  9504  9504 D ResourcesManager: For user 0 new overlays fetched Null
,06-23 11:34:22.502  3486  3849 D WifiBigDataLog: init : 
06-23 11:34:22.502  9504  9504 I InjectionManager: Inside getClassLibPath caller 
,06-23 11:34:22.512  3486  4396 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:22.512  3486  4396 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:22.512  3486  4396 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:22.512  3486  4396 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:22.512  3486  4396 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:22.512  3486  4396 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:22.512  3486  4396 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:22.512  3486  4396 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:22.512  3486  4396 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:22.512  3486  4396 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:22.512  3486  4396 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:22.512  3486  4396 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
06-23 11:34:22.512  3486  4396 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:22.512  3486  4396 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:22.512  3486  4396 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-23 11:34:22.522  3486  3970 I ActivityManager: Killing 8809:com.sec.android.service.health/u0a24 (adj 15): DHA:empty #33
,06-23 11:34:22.522  9504  9504 W System  : ClassLoader referenced unknown path: /system/priv-app/GmsCore/lib/arm64
,06-23 11:34:22.522  3486  3567 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ed1643a u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{39c8c7 8868:com.osp.app.signin/u0a41}
,06-23 11:34:22.532  8868  8868 I SA      : [DM] init START
,06-23 11:34:22.532  8868  8868 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,06-23 11:34:22.532  3486  4379 D ActivityManager: cleanUpApplicationRecord -- 8809
,06-23 11:34:22.532  3486  4379 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.service.health, Auto Run ON
,06-23 11:34:22.542  8868  8868 I SA      : [DM] This device is not a Vodafone
,06-23 11:34:22.542  8868  8868 W ResourceType: No package identifier when getting value for resource number 0x00000000
,06-23 11:34:22.542  8868  8868 W ResourceType: No package identifier when getting value for resource number 0x00000000
,06-23 11:34:22.542  8868  8868 W ResourceType: No package identifier when getting value for resource number 0x00000000
,06-23 11:34:22.542  8868  8868 W ResourceType: No package identifier when getting value for resource number 0x00000000
,06-23 11:34:22.552  8868  8868 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-23 11:34:22.552  8868  8868 W ResourceType: No package identifier when getting value for resource number 0x00000000
,06-23 11:34:22.552  8868  8868 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-23 11:34:22.552  8868  8868 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-23 11:34:22.552  8868  8868 W ResourceType: No package identifier when getting value for resource number 0x00000000
,06-23 11:34:22.552  8868  8868 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-23 11:34:22.552  8868  8868 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-23 11:34:22.552  8868  8868 W ResourceType: Failure getting entry for 0x7f0a0002 (t=9 e=2) (error -75)
06-23 11:34:22.552  8868  8868 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-23 11:34:22.552  8868  8868 W ResourceType: No package identifier when getting value for resource number 0x00000000
,06-23 11:34:22.552  8868  8868 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-23 11:34:22.552  8868  8868 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-23 11:34:22.552  8868  8868 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-23 11:34:22.552  8868  8868 W ResourceType: No package identifier when getting value for resource number 0x00000000
,06-23 11:34:22.552  8868  8868 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-23 11:34:22.552  8868  8868 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-23 11:34:22.552  8868  8868 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-23 11:34:22.552  8868  8868 W ResourceType: No package identifier when getting value for resource number 0x00000000
,06-23 11:34:22.552  8868  8868 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-23 11:34:22.552  8868  8868 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-23 11:34:22.552  8868  8868 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-23 11:34:22.552  8868  8868 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-23 11:34:22.552  8868  8868 W ResourceType: No package identifier when getting value for resource number 0x00000000
,06-23 11:34:22.552  8868  8868 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-23 11:34:22.552  8868  8868 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-23 11:34:22.552  8868  8868 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-23 11:34:22.552  8868  8868 W ResourceType: Failure getting entry for 0x7f0a0005 (t=9 e=5) (error -75)
06-23 11:34:22.552  8868  8868 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-23 11:34:22.552  8868  8868 W ResourceType: No package identifier when getting value for resource number 0x00000000
,06-23 11:34:22.552  8868  8868 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-23 11:34:22.552  8868  8868 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-23 11:34:22.552  8868  8868 W ResourceType: No package identifier when getting value for resource number 0x00000000
,06-23 11:34:22.552  8868  8868 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-23 11:34:22.552  8868  8868 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-23 11:34:22.552  8868  8868 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-23 11:34:22.552  8868  8868 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-23 11:34:22.552  8868  8868 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-23 11:34:22.552  8868  8868 W ResourceType: No package identifier when getting value for resource number 0x00000000
,06-23 11:34:22.552  8868  8868 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-23 11:34:22.552  8868  8868 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-23 11:34:22.552  8868  8868 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-23 11:34:22.552  8868  8868 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-23 11:34:22.552  8868  8868 W ResourceType: No package identifier when getting value for resource number 0x00000000
,06-23 11:34:22.552  8868  8868 W ResourceType: No package identifier when getting value for resource number 0x00000000
,06-23 11:34:22.562  8868  8868 I SA      : support phone number id : true
,06-23 11:34:22.562  8868  8868 I SA      : [DM] Supports Ref Jpn : true
06-23 11:34:22.562  8868  8868 I SA      : [DM] init END
06-23 11:34:22.562  8868  8868 I SA      : [OR] onReceive log=[SA = 2.2.02-12 V = 23 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = pl_PL CSC = XEO MCC = 0 MNC 0 T = user DEVICE = herolte P = heroltexx I = MMB29K M = SM-G930F OKLEFT false DIS MMB29K.G930FXXU1BPJG PSS = 5.059173621445858  ]
,06-23 11:34:22.562  8868  8868 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,06-23 11:34:22.562  8868  8868 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
06-23 11:34:22.562  8868  8868 I SA      : [SLFUCHKMGR] constructor called
,06-23 11:34:22.562  8868  8868 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,06-23 11:34:22.562  8868  8868 I SA      : [OR] == isSIMCardReady false ==
06-23 11:34:22.562  8868  8868 I SA      : [SCU] == networkStateCheck == false
06-23 11:34:22.562  8868  8868 I SA      : [OR] onReceive END
,06-23 11:34:22.582  3486  3567 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4b14ef4 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9233b8d 8766:com.samsung.android.app.FileShareServer/5005}
,06-23 11:34:22.582  8766  8766 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
06-23 11:34:22.582  3486  3567 D ActivityManager:  getDeferredInfo final delay 300
06-23 11:34:22.582  8766  8766 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,06-23 11:34:22.582  8766  8766 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,06-23 11:34:22.582  3486  4395 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a45261d u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ba5b784 9098:com.android.settings/1000}
,06-23 11:34:22.592  9098  9098 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,06-23 11:34:22.592  9504  9504 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,06-23 11:34:22.602  3486  4258 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a45261d u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{714895a 4842:com.samsung.android.providers.context/u0a7}
,06-23 11:34:22.612  9504  9504 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,06-23 11:34:22.612  3486  4379 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a45261d u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ff226b8 4273:com.google.android.gms.persistent/u0a19}
,06-23 11:34:22.612  4273  4273 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
,06-23 11:34:22.612  9098  9098 D DockEventReceiver: finishStartingService: stopping service
,06-23 11:34:22.622  9504  9594 D Babel   : Idle: Shutdown runnable posted in release with a delay of 5000 ms.
,06-23 11:34:22.622  3486  4379 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a45261d u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b251d48 8749:com.sec.android.app.shealth:remote/u0a36}
,06-23 11:34:22.622  3486  4396 V AlarmManager:  remove PendingIntent] PendingIntent{a19d3de: PendingIntentRecord{74109bf com.google.android.talk startService}}
,06-23 11:34:22.632  3486  4379 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a45261d u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ba5b784 9098:com.android.settings/1000}
,06-23 11:34:22.632  9098  9098 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
06-23 11:34:22.632  9098  9098 D BluetoothStatusReceiver: AdapterStateChanged :: state = 12
,06-23 11:34:22.642  9504  9504 D Babel   : Idle: Shutdown runnable posted in release with a delay of 5000 ms.
,06-23 11:34:22.642  3486  4379 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a45261d u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a807202 4809:com.android.bluetooth/1002}
,06-23 11:34:22.642  4809  4809 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1339123
06-23 11:34:22.642  4809  4809 D BtConfig.SecureMode: isSecureModeOn:false
,06-23 11:34:22.652  3486  3969 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a45261d u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{214f1fb 7032:com.google.android.apps.maps/u0a119}
,06-23 11:34:22.662  3486  3567 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{63888c u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{aa2736c 6417:com.enhance.gameservice/u0a106}
,06-23 11:34:22.672  3486  3567 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{643fbd5 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a8d88eb 9374:com.thaliproject.thalitest/u0a74}
,06-23 11:34:22.672  3486  4422 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:22.672  3486  4422 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-23 11:34:22.672  3486  4422 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:22.672  3486  4422 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:22.672  3486  4422 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:22.672  3486  4422 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:22.672  3486  4422 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:22.672  3486  4422 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:22.672  3486  4422 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:22.672  3486  4422 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:22.672  3486  4422 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:22.672  3486  4422 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
06-23 11:34:22.672  3486  4422 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:22.672  3486  4422 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:22.672  3486  4422 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-23 11:34:22.682  3486  3567 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d6b4fea u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{714895a 4842:com.samsung.android.providers.context/u0a7}
,06-23 11:34:22.682  3486  3970 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{20682db u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{714895a 4842:com.samsung.android.providers.context/u0a7}
,06-23 11:34:22.712  3151  3622 D Netd    : Iface wlan0 link down
,06-23 11:34:22.712  3486  3571 D Tethering: interfaceLinkStateChanged wlan0, false
06-23 11:34:22.712  3486  3571 D Tethering: interfaceStatusChanged wlan0, false
06-23 11:34:22.712  4857  4872 D PdnController: Interface Changed wlan0 link down
06-23 11:34:22.712  4857  4872 D PdnController: Removed Interface [wlan0] For Network [1]
,06-23 11:34:22.712  3486  3571 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-23 11:34:22.712  4857  4872 D PdnController: CONNECTIVITY_ACTION: networkType 1 isConnected false
06-23 11:34:22.712  4857  4872 D PdnController: isSuspended [false] networktype [1]
,06-23 11:34:22.712  3486  3571 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:22.712  4857  4872 D PdnController: isPdnUp  [false] networktype [1]
06-23 11:34:22.712  4857  4872 D PdnController: Ignore Notifying Same Result to LocalIP Registrants!
,06-23 11:34:22.762  4116  4116 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,06-23 11:34:22.862  3486  3849 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,06-23 11:34:22.862  3486  3486 D WifiNotificationController: SHOW_NOTI_MESSAGE : 9, visible : false, ssid : <unknown ssid>, targetSSID : null, netId : -1, titleType : -1
,06-23 11:34:22.862  3486  3486 D WifiNotificationController: SHOW_NOTI_MESSAGE : 13, visible : false, ssid : <unknown ssid>, targetSSID : null, netId : -1, titleType : 0
06-23 11:34:22.862  3486  3486 D WifiNotificationController: showCaptivePortalDisabledStatus with ssid/visible/title:null/false/0
,06-23 11:34:22.862  3486  3486 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
,06-23 11:34:22.862  3486  3853 D HS20StateMachine: WIFI_STATE_DISABLED
06-23 11:34:22.862  3486  3853 D HS20StateMachine: CMD_HOTSPOT20_DISABLE
06-23 11:34:22.862  3486  3853 D HS20StateMachine: enter : DisablingState
,06-23 11:34:22.862  3486  3855 D HS20SubscriptionManager: Received CMD_RELEASE_TLS, flag=1
06-23 11:34:22.862  3486  3486 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
06-23 11:34:22.862  3486  3856 I WifiHs20Service: Message received 5011
06-23 11:34:22.862  3486  3853 D HS20StateMachine: enter : DisabledState
,06-23 11:34:22.872  3486  3860 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
06-23 11:34:22.872  3928  4125 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,06-23 11:34:22.872  3486  3486 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
06-23 11:34:22.872  4245  4255 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,06-23 11:34:22.872  3928  3928 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
06-23 11:34:22.872  3928  3928 I HotspotTile: Provider is not defined returning false
,06-23 11:34:22.872  4245  4255 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
06-23 11:34:22.872  3928  3928 D HotspotTile: onReceive : 1, 0
,06-23 11:34:22.872  3486  3860 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,06-23 11:34:22.872  4273  5173 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,06-23 11:34:22.872  9374  9374 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-23 11:34:22.882  3486  3567 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{906a178 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a8d88eb 9374:com.thaliproject.thalitest/u0a74}
,06-23 11:34:22.882  3486  4257 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:22.882  3486  4257 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-23 11:34:22.882  3486  4257 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:22.882  3486  4257 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:22.882  3486  4257 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:22.882  3486  4257 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:22.882  3486  4257 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:22.882  3486  4257 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:22.882  3486  4257 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:22.882  3486  4257 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:22.882  3486  4257 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:22.882  3486  4257 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
06-23 11:34:22.882  3486  4257 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:22.882  3486  4257 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:22.882  3486  4257 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-23 11:34:22.912  3486  3567 D ActivityManager:  getDeferredInfo final delay 520
,06-23 11:34:23.002  9374  9461 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,06-23 11:34:23.002  3486  4379 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,06-23 11:34:23.002  3486  4379 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,06-23 11:34:23.002  3486  4379 D WifiService: setWifiEnabled: true pid=9374, uid=10074
,06-23 11:34:23.002  3486  4379 W ActivityManager: Permission Denial: getCurrentUser() from pid=9374, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
06-23 11:34:23.002  3486  4379 W WifiService: Failed getting userId using ActivityManagerNative
06-23 11:34:23.002  3486  4379 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9374, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
06-23 11:34:23.002  3486  4379 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
06-23 11:34:23.002  3486  4379 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
06-23 11:34:23.002  3486  4379 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
06-23 11:34:23.002  3486  4379 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
06-23 11:34:23.002  3486  4379 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
,06-23 11:34:23.002  3486  4379 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
06-23 11:34:23.002  3486  4379 D SettingsProvider: isChangeAllowed() : name = wifi_on
,06-23 11:34:23.002  3486  3852 D WifiStateMachine: setFccChannel: channel = -1
06-23 11:34:23.002  3486  3852 D WifiController: [FCC]setFccChannel() is called !!!
06-23 11:34:23.002  3486  3852 E WifiController: illegal state found both WifiController and WifiStateMachine
06-23 11:34:23.002  3486  3852 D WifiController: [FCC]Airplane off, setFccChannel(-1)!!!
,06-23 11:34:23.052  3486  3564 D libgps  : agps_ril_update_network_state: Waiting for IPC connection - timeout
06-23 11:34:23.052  3486  3564 E libgps  : LIBGPS: Cannot communicate (write) with a GPSD
06-23 11:34:23.052  3486  3564 E libgps  : IPC Communication Error, ../../../../tmp/14982990_270314/allPartners/os/android/gps_interface/gpsi_client/GpsiClient.cpp:1710 agps_ril_update_network_state
,06-23 11:34:23.052  3486  3564 D libgps  : agps_ril_update_network_availability: Waiting for IPC connection...
,06-23 11:34:23.062  3486  3849 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,06-23 11:34:23.062  3486  3849 E WifiStateMachine: Error! unhandled message{ when=-3m23s217ms what=131156 target=com.android.internal.util.StateMachine$SmHandler }
06-23 11:34:23.062  3486  3849 E WifiHW  : ##################### set firmware type 0 #####################
,06-23 11:34:23.062  3151  3629 I WifiHW  : wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
06-23 11:34:23.062  3151  3629 I WifiHW  : module is semco
06-23 11:34:23.062  3151  3629 E WifiHW  : ==========[WIFI] SEMCO MODULE ===========
06-23 11:34:23.062  3151  3629 I WifiHW  : wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
06-23 11:34:23.062  3151  3629 E WifiHW  : TEMP_FAILURE_RETRY complete
06-23 11:34:23.062  3151  3629 D SoftapController: Softap fwReload - Ok
,06-23 11:34:23.072  3151  3629 D CommandListener: Setting iface cfg
06-23 11:34:23.072  3151  3629 D CommandListener: Trying to bring down wlan0
,06-23 11:34:23.072  3151  3629 D CommandListener: Clearing all IP addresses on wlan0
,06-23 11:34:23.072  3486  3849 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,06-23 11:34:23.072  3486  3849 D wifi    : Can not initialize the vendor function pointer table
,06-23 11:34:23.072  3486  3849 E WifiNative-HAL: Could not start hal
06-23 11:34:23.072  3486  3849 E WifiStateMachine: Failed to start HAL
06-23 11:34:23.072  3486  3849 E WifiHW  : supplicant_name : p2p_supplicant
,06-23 11:34:23.172  3486  3849 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,06-23 11:34:23.182  3486  3486 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
,06-23 11:34:23.182  3486  3486 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
06-23 11:34:23.182  3486  3856 I WifiHs20Service: Message received 5011
,06-23 11:34:23.182  3486  3860 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
06-23 11:34:23.182  3486  3486 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
06-23 11:34:23.182  3928  4125 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,06-23 11:34:23.182  3928  3928 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
06-23 11:34:23.182  4245  4256 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
06-23 11:34:23.182  3928  3928 I HotspotTile: Provider is not defined returning false
,06-23 11:34:23.182  4245  4256 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
06-23 11:34:23.182  3928  3928 D HotspotTile: onReceive : 2, 0
06-23 11:34:23.192  3486  3860 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,06-23 11:34:23.192  9374  9374 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-23 11:34:23.202  3486  3567 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7d58051 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a8d88eb 9374:com.thaliproject.thalitest/u0a74}
,06-23 11:34:23.202  3486  4258 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:23.202  3486  4258 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-23 11:34:23.202  3486  4258 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:23.202  3486  4258 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:23.202  3486  4258 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-23 11:34:23.202  3486  4258 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:23.202  3486  4258 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:23.202  3486  4258 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-23 11:34:23.202  3486  4258 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:23.202  3486  4258 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:23.202  3486  4258 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:23.202  3486  4258 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
,06-23 11:34:23.202  3486  4258 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:23.202  3486  4258 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:23.202  3486  4258 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-23 11:34:23.232  9596  9596 I FIPS_bssl: FIPS approved mode (1) | 9596 | /system/bin/wpa_supplicant
,06-23 11:34:23.232  9596  9596 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
,06-23 11:34:23.232  9596  9596 I wpa_supplicant: Successfully initialized wpa_supplicant
06-23 11:34:23.232  9596  9596 I wpa_supplicant: set_csc_config : ifname(wlan0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x20000), vendorssid_list()
06-23 11:34:23.232  9596  9596 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,06-23 11:34:23.252  9596  9596 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,06-23 11:34:23.252  3010  3010 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 9596
06-23 11:34:23.252  3010  3010 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
06-23 11:34:23.252  9596  9596 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
06-23 11:34:23.252  9596  9596 I wpa_supplicant: ssSupport state is = 1
06-23 11:34:23.252  9596  9596 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
06-23 11:34:23.252  9596  9596 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,06-23 11:34:23.252  3010  3010 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 9596
06-23 11:34:23.252  3010  3010 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x00000106
,06-23 11:34:23.262  9596  9596 I SecureStorage: [INFO]: SPID(0x00000005)ss_id will be loaded by secure_storage_daemon: /system/bin/wpa_supplicant
,06-23 11:34:23.272  3486  3969 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-23 11:34:23.272  3486  3969 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4356, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-23 11:34:23.272  3486  3969 D BatteryService: online:4, current avg:117, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:176
06-23 11:34:23.272  3486  3486 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-23 11:34:23.282  3486  3486 I MotionRecognitionService: Plugged
06-23 11:34:23.282  3486  3486 D MotionRecognitionService:   cableConnection= 1
06-23 11:34:23.282  3486  3486 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-23 11:34:23.282  3486  3486 D MotionRecognitionService: skip setTransmitPower. 
,06-23 11:34:23.282  3486  3852 D WifiController: ApOrStaEnabledState  msg.what= 155652
,06-23 11:34:23.282  3928  3928 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-23 11:34:23.282  3928  3928 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-23 11:34:23.282  3928  3928 D PowerUI : priorPlugType = 2 mPlugType =  2
,06-23 11:34:23.292  4857  4857 D CommonServiceConfiguration: getStringValueSetting
,06-23 11:34:23.292  4857  4857 D BatteryMonitor: new battery level: 100
,06-23 11:34:23.292  4809  4809 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-23 11:34:23.292  4809  9468 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,06-23 11:34:23.302  3928  3928 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-23 11:34:23.302  3928  3928 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-23 11:34:23.432  3486  3567 D ActivityManager:  getDeferredInfo final delay 520
,06-23 11:34:23.502  9374  9461 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,06-23 11:34:23.502  3486  4258 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,06-23 11:34:23.502  3486  4258 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
06-23 11:34:23.502  3486  4258 D WifiService: setWifiEnabled: true pid=9374, uid=10074
,06-23 11:34:23.502  3486  4258 W ActivityManager: Permission Denial: getCurrentUser() from pid=9374, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
06-23 11:34:23.502  3486  4258 W WifiService: Failed getting userId using ActivityManagerNative
06-23 11:34:23.502  3486  4258 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9374, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
06-23 11:34:23.502  3486  4258 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
06-23 11:34:23.502  3486  4258 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
06-23 11:34:23.502  3486  4258 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
06-23 11:34:23.502  3486  4258 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
06-23 11:34:23.502  3486  4258 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
,06-23 11:34:23.512  3486  4258 D SettingsProvider: isChangeAllowed() : name = wifi_on
06-23 11:34:23.512  3486  4258 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
06-23 11:34:23.512  3486  3852 D WifiController: [FCC]setFccChannel() is called !!!
06-23 11:34:23.512  3486  3852 D WifiStateMachine: setFccChannel: channel = -1
06-23 11:34:23.512  3486  3852 D WifiController: [FCC]Airplane off, setFccChannel(-1)!!!
,06-23 11:34:23.552  3010  3010 I SecureStorage: [INFO]: SPID(0x00000005)Secure Storage Daemon finished processing with result: 0
06-23 11:34:23.552  9596  9596 I SecureStorage: [INFO]: SPID(0x00000005)Processing data has been completed
,06-23 11:34:23.582  9596  9596 I wpa_supplicant: Ctrl_iface: loading system cred
,06-23 11:34:23.592  9596  9596 I SecureStorage: [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,06-23 11:34:23.612  9596  9596 I SecureStorage: [INFO]: SPID(0x00000005)This device supports Secure Storage
,06-23 11:34:23.612  3010  3010 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 9596
06-23 11:34:23.612  3010  3010 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
06-23 11:34:23.612  9596  9596 I SecureStorage: [INFO]: SPID(0x00000005)SS Daemon is running
06-23 11:34:23.612  9596  9596 I wpa_supplicant: ssSupport state is = 1
06-23 11:34:23.612  9596  9596 I wpa_supplicant: Blacklist: Clear (all) 
06-23 11:34:23.612  9596  9596 E wpa_supplicant: getSavedIMSI cannot open /data/misc/radio/kmem: No such file or directory
06-23 11:34:23.612  9596  9596 I wpa_supplicant: [getIMSI]: sim_num 0
06-23 11:34:23.612  9596  9596 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,06-23 11:34:24.002  3486  3567 D ActivityManager:  getDeferredInfo final delay 0
,06-23 11:34:24.012  9374  9461 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,06-23 11:34:24.012  3486  4422 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,06-23 11:34:24.012  3486  4422 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,06-23 11:34:24.012  3486  4422 D WifiService: setWifiEnabled: true pid=9374, uid=10074
,06-23 11:34:24.022  3486  3567 I ActivityManager: Start proc 9601:com.sec.android.diagmonagent/1000 for broadcast-5 com.sec.android.diagmonagent/.DiagMonConnectivityChangeReciever
,06-23 11:34:24.022  3486  4422 W ActivityManager: Permission Denial: getCurrentUser() from pid=9374, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
,06-23 11:34:24.022  3486  4422 W WifiService: Failed getting userId using ActivityManagerNative
06-23 11:34:24.022  3486  4422 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9374, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
06-23 11:34:24.022  3486  4422 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
06-23 11:34:24.022  3486  4422 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
06-23 11:34:24.022  3486  4422 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
06-23 11:34:24.022  3486  4422 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
06-23 11:34:24.022  3486  4422 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
06-23 11:34:24.022  3486  4422 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
06-23 11:34:24.022  3486  4422 D SettingsProvider: isChangeAllowed() : name = wifi_on
06-23 11:34:24.022  3486  3852 D WifiStateMachine: setFccChannel: channel = -1
06-23 11:34:24.022  3486  3852 D WifiController: [FCC]setFccChannel() is called !!!
06-23 11:34:24.022  3486  3852 D WifiController: [FCC]Airplane off, setFccChannel(-1)!!!
,06-23 11:34:24.062  3486  3564 D libgps  : agps_ril_update_network_availability: Waiting for IPC connection - timeout
06-23 11:34:24.062  3486  3564 E libgps  : LIBGPS: Cannot communicate (write) with a GPSD
06-23 11:34:24.062  3486  3564 E libgps  : IPC Communication Error, ../../../../tmp/14982990_270314/allPartners/os/android/gps_interface/gpsi_client/GpsiClient.cpp:1729 agps_ril_update_network_availability
,06-23 11:34:24.182  9601  9601 E Zygote  : v2
06-23 11:34:24.182  9601  9601 I libpersona: KNOX_SDCARD checking this for 1000
06-23 11:34:24.182  9601  9601 I libpersona: KNOX_SDCARD not a persona
,06-23 11:34:24.192  9601  9601 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,06-23 11:34:24.192  9601  9601 E Zygote  : accessInfo : 0
,06-23 11:34:24.212  9601  9601 D TimaKeyStoreProvider: TimaSignature is unavailable
06-23 11:34:24.212  9601  9601 D ActivityThread: Added TimaKeyStore provider
,06-23 11:34:24.222  3486  4379 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{59771d2 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2a680b6 9601:com.sec.android.diagmonagent/1000}
,06-23 11:34:24.232  9601  9601 W ResourcesManager: getTopLevelResources: /system/priv-app/DiagMonAgent/DiagMonAgent.apk / 1.0 running in com.sec.android.diagmonagent rsrc of package com.sec.android.diagmonagent
,06-23 11:34:24.232  3486  4395 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,06-23 11:34:24.232  9601  9601 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,06-23 11:34:24.242  9601  9601 D ResourcesManager: For user 0 new overlays fetched Null
,06-23 11:34:24.242  9601  9601 I InjectionManager: Inside getClassLibPath caller 
,06-23 11:34:24.252  9601  9601 W System  : ClassLoader referenced unknown path: /system/priv-app/DiagMonAgent/lib/arm64
,06-23 11:34:24.262  9601  9601 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,06-23 11:34:24.302  3151  3622 D Netd    : Iface wlan0 link up
,06-23 11:34:24.302  3151  3622 D Netd    : Iface wlan0 link up
06-23 11:34:24.302  3151  3622 D Netd    : Iface wlan0 link up
06-23 11:34:24.302  3486  3571 D Tethering: interfaceLinkStateChanged wlan0, true
06-23 11:34:24.302  3486  3571 D Tethering: interfaceStatusChanged wlan0, true
,06-23 11:34:24.312  4857  4875 D PdnController: Interface Changed wlan0 link up
,06-23 11:34:24.312  3486  3571 D Tethering: interfaceLinkStateChanged wlan0, true
06-23 11:34:24.312  3486  3571 D Tethering: interfaceStatusChanged wlan0, true
06-23 11:34:24.312  4857  4872 D PdnController: Interface Changed wlan0 link up
06-23 11:34:24.312  3486  3571 D Tethering: interfaceLinkStateChanged wlan0, true
06-23 11:34:24.312  3486  3571 D Tethering: interfaceStatusChanged wlan0, true
,06-23 11:34:24.312  4857  5193 D PdnController: Interface Changed wlan0 link up
,06-23 11:34:24.332  9601  9601 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,06-23 11:34:24.332  9601  9601 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(72/onCreate)] DiagMon DM Application Start !
06-23 11:34:24.332  9601  9601 D InjectionManager: InjectionManager
06-23 11:34:24.332  9601  9601 D InjectionManager: fillFeatureStoreMap com.sec.android.diagmonagent
,06-23 11:34:24.332  9601  9601 I InjectionManager: Constructor com.sec.android.diagmonagent, Feature store :{}
06-23 11:34:24.332  9601  9601 I InjectionManager: featureStore :{}
06-23 11:34:24.332  9601  9601 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,06-23 11:34:24.332  9601  9601 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
06-23 11:34:24.332  9601  9601 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
06-23 11:34:24.332  9601  9601 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,06-23 11:34:24.332  3486  4285 D ActivityManager:  getDeferredInfo final delay 0
,06-23 11:34:24.342  9614  9614 E Zygote  : v2
06-23 11:34:24.342  9614  9614 I libpersona: KNOX_SDCARD checking this for 1000
06-23 11:34:24.342  9614  9614 I libpersona: KNOX_SDCARD not a persona
,06-23 11:34:24.342  9614  9614 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,06-23 11:34:24.342  9614  9614 E Zygote  : accessInfo : 0
,06-23 11:34:24.342  3486  4285 I ActivityManager: Start proc 9614:com.sec.knox.switcher/1000 for broadcast-5 com.sec.knox.switcher/.knoxusage.KnoxUsageReceiver
,06-23 11:34:24.342  3486  4285 I ActivityManager: Killing 8855:com.samsung.android.scloud:contentsync/5009 (adj 15): DHA:empty #33
,06-23 11:34:24.362  9614  9614 D TimaKeyStoreProvider: TimaSignature is unavailable
06-23 11:34:24.362  9614  9614 D ActivityThread: Added TimaKeyStore provider
,06-23 11:34:24.362  3486  4433 D ActivityManager: cleanUpApplicationRecord -- 8855
,06-23 11:34:24.362  3486  4433 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.scloud, Auto Run ON
,06-23 11:34:24.372  3486  4395 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{59771d2 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ee071b7 9614:com.sec.knox.switcher/1000}
,06-23 11:34:24.372  9614  9614 W ResourcesManager: getTopLevelResources: /system/app/KnoxSwitcher/KnoxSwitcher.apk / 1.0 running in com.sec.knox.switcher rsrc of package com.sec.knox.switcher
,06-23 11:34:24.372  3486  4257 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,06-23 11:34:24.372  9614  9614 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,06-23 11:34:24.372  9614  9614 D ResourcesManager: For user 0 new overlays fetched Null
,06-23 11:34:24.382  9614  9614 I InjectionManager: Inside getClassLibPath caller 
,06-23 11:34:24.382  9614  9614 W System  : ClassLoader referenced unknown path: /system/app/KnoxSwitcher/lib/arm64
,06-23 11:34:24.382  9614  9614 D KnoxUsageDB: getInstance - KnoxUsageDBHelper
06-23 11:34:24.382  9614  9614 D KnoxUsageDB: null == mDbHelperInstance - KnoxUsageDBHelper
,06-23 11:34:24.382  9614  9614 D InjectionManager: InjectionManager
06-23 11:34:24.382  9614  9614 D InjectionManager: fillFeatureStoreMap com.sec.knox.switcher
,06-23 11:34:24.382  9614  9614 I InjectionManager: Constructor com.sec.knox.switcher, Feature store :{}
06-23 11:34:24.382  9614  9614 I InjectionManager: featureStore :{}
06-23 11:34:24.382  9614  9614 I usagelog: received in receiver
06-23 11:34:24.382  9614  9614 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
,06-23 11:34:24.382  9614  9614 I KnoxUsageLogPro: premStatus:2
,06-23 11:34:24.382  9614  9614 I KnoxUsageLogPro: isEulaShown : false
06-23 11:34:24.382  9614  9614 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,06-23 11:34:24.382  3486  4396 D ActivityManager:  getDeferredInfo final delay 0
,06-23 11:34:24.392  9596  9596 I wpa_supplicant: set_csc_config : ifname(p2p0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x0), vendorssid_list()
06-23 11:34:24.392  9596  9596 I SecureStorage: [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,06-23 11:34:24.392  9627  9627 E Zygote  : v2
06-23 11:34:24.392  9627  9627 I libpersona: KNOX_SDCARD checking this for 10135
06-23 11:34:24.392  9627  9627 I libpersona: KNOX_SDCARD not a persona
,06-23 11:34:24.392  9627  9627 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,06-23 11:34:24.392  9627  9627 E Zygote  : accessInfo : 0
06-23 11:34:24.392  9627  9627 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.sm.policy 
,06-23 11:34:24.402  3486  4396 I ActivityManager: Start proc 9627:com.samsung.android.sm.policy/u0a135 for broadcast-5 com.samsung.android.sm.policy/.PolicyBroadCastReceiver
,06-23 11:34:24.402  3486  4396 I ActivityManager: Killing 8011:com.samsung.android.coreapps/5011 (adj 15): DHA:empty #33
,06-23 11:34:24.402  9596  9596 I SecureStorage: [INFO]: SPID(0x00000005)This device supports Secure Storage
,06-23 11:34:24.402  3010  3010 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 9596
06-23 11:34:24.402  3010  3010 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
,06-23 11:34:24.402  9596  9596 I SecureStorage: [INFO]: SPID(0x00000005)SS Daemon is running
06-23 11:34:24.402  9596  9596 I wpa_supplicant: ssSupport state is = 1
,06-23 11:34:24.402  9596  9596 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,06-23 11:34:24.402  9596  9596 E wpa_supplicant: nl80211: Could not configure driver mode
06-23 11:34:24.402  9596  9596 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
06-23 11:34:24.402  9596  9596 E wpa_supplicant: p2p0: Failed to initialize driver interface
06-23 11:34:24.402  9596  9596 I wpa_supplicant: Blacklist: Clear (all) 
,06-23 11:34:24.402  9596  9596 I wpa_supplicant: set_csc_config : ifname(p2p0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x0), vendorssid_list()
06-23 11:34:24.402  9596  9596 I SecureStorage: [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,06-23 11:34:24.412  3486  4395 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1248000  uid : 1000  pid : 3486  tag : BADGE_UPDATE@CPU_MIN@1
,06-23 11:34:24.422  9627  9627 D TimaKeyStoreProvider: TimaSignature is unavailable
06-23 11:34:24.422  9627  9627 D ActivityThread: Added TimaKeyStore provider
,06-23 11:34:24.422  9596  9596 I SecureStorage: [INFO]: SPID(0x00000005)This device supports Secure Storage
,06-23 11:34:24.422  3010  3010 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 9596
06-23 11:34:24.422  3010  3010 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
06-23 11:34:24.422  9596  9596 I SecureStorage: [INFO]: SPID(0x00000005)SS Daemon is running
06-23 11:34:24.422  9596  9596 I wpa_supplicant: ssSupport state is = 1
,06-23 11:34:24.422  9596  9596 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,06-23 11:34:24.422  3486  4258 D ActivityManager: cleanUpApplicationRecord -- 8011
,06-23 11:34:24.432  3486  4258 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.coreapps, Auto Run ON
,06-23 11:34:24.432  9596  9596 I wpa_supplicant: P2P: Set prekey state (NONE -> NONE)
,06-23 11:34:24.442  3486  3849 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,06-23 11:34:24.442  3486  3849 E WifiStateMachine: Deffering msg in Supplicant Starting State131085
,06-23 11:34:24.442  3486  3849 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,06-23 11:34:24.442  3486  3849 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,06-23 11:34:24.442  3486  3975 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{59771d2 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2c05d24 9627:com.samsung.android.sm.policy/u0a135}
,06-23 11:34:24.452  3486  3849 D WifiBigDataLog: init : 
,06-23 11:34:24.452  3486  3849 E WifiStateMachine: Deffering msg in Supplicant Starting State131083
06-23 11:34:24.452  3486  3849 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
06-23 11:34:24.452  3486  3849 D WifiBigDataLog: getJsonFormat() - feature : ONOF
06-23 11:34:24.452  3486  3849 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,06-23 11:34:24.452  9627  9627 W ResourcesManager: getTopLevelResources: /system/app/SCPMClient/SCPMClient.apk / 1.0 running in com.samsung.android.sm.policy rsrc of package com.samsung.android.sm.policy
,06-23 11:34:24.452  3486  4396 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,06-23 11:34:24.452  9627  9627 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
06-23 11:34:24.452  3486  3567 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{620d08d u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{714895a 4842:com.samsung.android.providers.context/u0a7}
,06-23 11:34:24.462  3486  3849 D WifiBigDataLog: init : 
06-23 11:34:24.462  9627  9627 D ResourcesManager: For user 0 new overlays fetched Null
06-23 11:34:24.462  3486  3849 D WifiBigDataLog: getJsonFormat() - feature : ONOF
06-23 11:34:24.462  3486  3849 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
06-23 11:34:24.462  9627  9627 I InjectionManager: Inside getClassLibPath caller 
06-23 11:34:24.462  3486  4422 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{591f242 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{714895a 4842:com.samsung.android.providers.context/u0a7}
,06-23 11:34:24.472  9627  9627 W System  : ClassLoader referenced unknown path: /system/app/SCPMClient/lib/arm64
,06-23 11:34:24.472  3486  6038 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-23 11:34:24.472  3486  3849 D WifiBigDataLog: init : 
,06-23 11:34:24.472  3486  3849 D WifiNative-wlan0: callSECApiBoolean - ID [301]
06-23 11:34:24.472  9596  9596 I wpa_supplicant: HOTSPOT20_ENABLE called ON
06-23 11:34:24.472  9596  9596 I wpa_supplicant: Blacklist: Clear (all) 
,06-23 11:34:24.482  3486  4422 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8007253 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{714895a 4842:com.samsung.android.providers.context/u0a7}
,06-23 11:34:24.482  9596  9596 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,06-23 11:34:24.492  9627  9627 D InjectionManager: InjectionManager
06-23 11:34:24.492  9627  9627 D InjectionManager: fillFeatureStoreMap com.samsung.android.sm.policy
,06-23 11:34:24.492  9627  9627 I InjectionManager: Constructor com.samsung.android.sm.policy, Feature store :{}
06-23 11:34:24.492  9627  9627 I InjectionManager: featureStore :{}
,06-23 11:34:24.492  9596  9596 I wpa_supplicant: wlan0: Skip scan - bUseNetwork false
,06-23 11:34:24.492  3486  3849 D WifiNative-wlan0: callSECApiInt - ID [210]
,06-23 11:34:24.492  3486  4422 D ActivityManager:  getDeferredInfo final delay 0
,06-23 11:34:24.492  3486  3486 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
06-23 11:34:24.492  3486  3486 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
06-23 11:34:24.492  3486  3853 D HS20StateMachine: WIFI_STATE_ENABLED
06-23 11:34:24.492  3486  3856 I WifiHs20Service: Message received 5011
06-23 11:34:24.492  3486  3853 D HS20StateMachine: reloadCredentialsToSupplicant
06-23 11:34:24.492  3486  3853 D HotspotDBHandler: getCredentialIds
,06-23 11:34:24.502  3486  3486 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,06-23 11:34:24.502  3486  3860 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
06-23 11:34:24.502  3486  4186 W SLocation: No Active Data Connection
06-23 11:34:24.502  3928  4125 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
06-23 11:34:24.502  4245  4256 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,06-23 11:34:24.502  4245  4256 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,06-23 11:34:24.502  3928  3928 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
06-23 11:34:24.502  3486  3860 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,06-23 11:34:24.502  3928  3928 I HotspotTile: Provider is not defined returning false
06-23 11:34:24.502  3928  3928 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 272
06-23 11:34:24.502  3928  3928 D HotspotTile: onReceive : 3, 0
,06-23 11:34:24.512  3486  3567 I ActivityManager: Killing 8889:com.google.android.apps.photos/u0a129 (adj 15): DHA:empty #33
,06-23 11:34:24.512  9374  9374 D BluetoothAdapter: STATE_ON
,06-23 11:34:24.522  9374  9374 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-23 11:34:24.522  9374  9374 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-23 11:34:24.522  9374  9374 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
06-23 11:34:24.522  9374  9374 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-23 11:34:24.522  9374  9374 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-23 11:34:24.522  9374  9374 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-23 11:34:24.522  9374  9374 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
06-23 11:34:24.522  9374  9374 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-23 11:34:24.522  9374  9374 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,06-23 11:34:24.522  3486  3567 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a382790 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a8d88eb 9374:com.thaliproject.thalitest/u0a74}
,06-23 11:34:24.522  9374  9374 D BluetoothAdapter: STATE_ON
,06-23 11:34:24.542  9374  9374 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,06-23 11:34:24.542  9374  9461 D BluetoothAdapter: STATE_ON
,06-23 11:34:24.542  3486  3970 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:24.542  3486  3970 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:24.542  3486  3970 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:24.542  9596  9596 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
06-23 11:34:24.542  3486  3970 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:24.542  3486  3970 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:24.542  3486  3970 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:24.542  3486  3970 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:24.542  3486  3970 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-23 11:34:24.542  3486  3970 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:24.542  3486  3970 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:24.542  3486  3970 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:24.542  3486  3970 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
,06-23 11:34:24.542  3486  3970 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:24.542  3486  3970 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:24.542  3486  3970 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-23 11:34:24.542  3486  3849 D WifiConfigStore: Loading config and enabling all networks 
,06-23 11:34:24.542  9374  9461 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
06-23 11:34:24.542  9374  9461 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-23 11:34:24.542  9374  9461 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
06-23 11:34:24.542  9374  9461 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-23 11:34:24.542  9374  9461 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-23 11:34:24.542  9374  9461 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-23 11:34:24.542  9374  9461 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
06-23 11:34:24.542  9374  9461 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-23 11:34:24.542  9374  9461 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-23 11:34:24.552  9374  9439 D BluetoothAdapter: enable()
,06-23 11:34:24.552  9642  9642 E Zygote  : v2
06-23 11:34:24.552  9642  9642 I libpersona: KNOX_SDCARD checking this for 5005
06-23 11:34:24.552  9642  9642 I libpersona: KNOX_SDCARD not a persona
06-23 11:34:24.552  9642  9642 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
06-23 11:34:24.552  3486  4422 I ActivityManager: Start proc 9642:com.samsung.android.app.FileShareClient/5005 for broadcast-5 com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver
06-23 11:34:24.552  9642  9642 E Zygote  : accessInfo : 0
06-23 11:34:24.552  9642  9642 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.app.FileShareClient 
,06-23 11:34:24.562  3486  3849 I WifiConfigStore: "AndroidHotspot2346" is a verified password AP: true
06-23 11:34:24.562  3486  3849 E WifiConfigStore: Not a HS20
,06-23 11:34:24.572  3486  3849 I WifiConfigStore: "MC" is a verified password AP: true
06-23 11:34:24.572  3486  3849 E WifiConfigStore: Not a HS20
,06-23 11:34:24.582  9654  9654 E Zygote  : v2
06-23 11:34:24.582  9654  9654 I libpersona: KNOX_SDCARD checking this for 10114
06-23 11:34:24.582  9654  9654 I libpersona: KNOX_SDCARD not a persona
,06-23 11:34:24.582  9654  9654 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,06-23 11:34:24.582  3486  3849 I WifiConfigStore: "MC" is a verified password AP: false
06-23 11:34:24.582  3486  3849 E WifiConfigStore: Not a HS20
,06-23 11:34:24.582  9654  9654 E Zygote  : accessInfo : 0
,06-23 11:34:24.582  9654  9654 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.samsung.hs20provider 
,06-23 11:34:24.592  9642  9642 D TimaKeyStoreProvider: TimaSignature is unavailable
06-23 11:34:24.592  9642  9642 D ActivityThread: Added TimaKeyStore provider
,06-23 11:34:24.592  3486  3853 I ActivityManager: Start proc 9654:com.samsung.hs20provider/u0a114 for content provider com.samsung.hs20provider/.Hs20Provider
06-23 11:34:24.592  3486  6038 D SSRM:n  : SIOP:: AP = 330, PST = 327 (W:14), CP = 267, CUR = 117, LCD = 40
06-23 11:34:24.592  3486  3849 I WifiConfigStore: "NG700" is a verified password AP: true
06-23 11:34:24.592  3486  3975 D ActivityManager: cleanUpApplicationRecord -- 8889
06-23 11:34:24.592  3486  3849 E WifiConfigStore: Not a HS20
06-23 11:34:24.602  3486  3849 D WifiConfigStore: loaded 0 passpoint configs
,06-23 11:34:24.602  3486  3975 D ActivityManager: isAutoRunBlockedApp:: com.google.android.apps.photos, Auto Run ON
,06-23 11:34:24.602  3486  3849 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,06-23 11:34:24.602  3486  3849 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
06-23 11:34:24.602  3486  3849 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,06-23 11:34:24.602  3486  3849 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,06-23 11:34:24.602  3486  3849 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 4
,06-23 11:34:24.602  3486  3849 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
06-23 11:34:24.602  3486  3849 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
06-23 11:34:24.602  3486  3849 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
06-23 11:34:24.602  3486  3849 E WifiConfigStore: found sortedWifiConfigurations : "MC"NONE
,06-23 11:34:24.612  9654  9654 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-23 11:34:24.612  9654  9654 D ActivityThread: Added TimaKeyStore provider
,06-23 11:34:24.612  3486  3849 D WifiConfigStore: setNetworkPriorityDefault: networkId = 1, priority = 1
06-23 11:34:24.612  3486  3849 D WifiConfigStore: setNetworkPriorityDefault: networkId = 0, priority = 1
06-23 11:34:24.612  9374  9439 D BluetoothAdapter: enable(): BT is already enabled..!
06-23 11:34:24.612  3486  3849 D WifiConfigStore: setNetworkPriorityDefault: networkId = 3, priority = 1
,06-23 11:34:24.622  3486  3849 D WifiConfigStore: setNetworkPriorityDefault: networkId = 2, priority = 1
,06-23 11:34:24.622  3486  3849 D WifiNative-wlan0: callSECApiInt - ID [65]
,06-23 11:34:24.622  3486  4257 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{4b14ef4 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f56e889 9642:com.samsung.android.app.FileShareClient/5005}
,06-23 11:34:24.622  3486  3486 I WifiHs20Service: Broadcast received:android.net.wifi.CONFIGURED_NETWORKS_CHANGE
06-23 11:34:24.622  3486  3486 D WifiHs20Service: reason: 2
06-23 11:34:24.622  3486  3856 I WifiHs20Service: Message received 5014
06-23 11:34:24.622  3486  3856 E WifiHs20Service: received HS20_UTILITY_ACTION_TYPE_HS20_CONFIGURATION_CHANGED
,06-23 11:34:24.622  3486  3856 E WifiHs20Service: The changed config is NULL
06-23 11:34:24.622  3486  3849 D WifiNative-wlan0: callSECApiBoolean - ID [13]
06-23 11:34:24.622  9596  9596 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
06-23 11:34:24.622  9596  9596 I wpa_supplicant: resume autoscan
,06-23 11:34:24.622  9596  9596 I wpa_supplicant: autoscan_samsung_exponential_notify_scan : scan_interval = 8
06-23 11:34:24.622  9596  9596 I wpa_supplicant: autoscan: autoscan_notify_scan, scan_interval = 8
06-23 11:34:24.622  9596  9596 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
06-23 11:34:24.622  9596  9596 I wpa_supplicant: reset timer : RESET_TIMER 0
06-23 11:34:24.622  9596  9596 I wpa_supplicant: P2P: Current p2p state = IDLE
06-23 11:34:24.622  9596  9596 I wpa_supplicant: First Scan Start
,06-23 11:34:24.632  3486  6038 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-23 11:34:24.632  9596  9596 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,06-23 11:34:24.632  3486  3567 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d0f08e u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{714895a 4842:com.samsung.android.providers.context/u0a7}
,06-23 11:34:24.642  9642  9642 W ResourcesManager: getTopLevelResources: /system/app/AllshareFileShareClient/AllshareFileShareClient.apk / 1.0 running in com.samsung.android.app.FileShareClient rsrc of package com.samsung.android.app.FileShareClient
,06-23 11:34:24.642  3486  4435 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,06-23 11:34:24.642  9642  9642 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,06-23 11:34:24.642  9374  9439 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,06-23 11:34:24.652  9642  9642 D ResourcesManager: For user 0 new overlays fetched Null
,06-23 11:34:24.652  3486  4257 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
06-23 11:34:24.652  3486  4257 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,06-23 11:34:24.652  3486  3849 D WifiNative-wlan0: Setting external_sim to 1
06-23 11:34:24.652  3486  4257 D WifiService: setWifiEnabled: true pid=9374, uid=10074
06-23 11:34:24.652  3486  3849 D WifiStateMachine: Setting OUI to DA-A1-19
06-23 11:34:24.652  3486  4257 W ActivityManager: Permission Denial: getCurrentUser() from pid=9374, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
06-23 11:34:24.652  3486  4257 W WifiService: Failed getting userId using ActivityManagerNative
06-23 11:34:24.652  3486  4257 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9374, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
06-23 11:34:24.652  3486  4257 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
06-23 11:34:24.652  3486  4257 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
06-23 11:34:24.652  3486  4257 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
06-23 11:34:24.652  3486  4257 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
06-23 11:34:24.652  3486  4257 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
06-23 11:34:24.652  3486  4257 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
06-23 11:34:24.652  3486  4257 D SettingsProvider: isChangeAllowed() : name = wifi_on
,06-23 11:34:24.652  3486  3852 D WifiStateMachine: setFccChannel: channel = -1
06-23 11:34:24.652  3486  3852 D WifiController: [FCC]setFccChannel() is called !!!
,06-23 11:34:24.652  9596  9596 I wpa_supplicant: bt_status is set be DISCONNECTED
06-23 11:34:24.652  3486  3852 D WifiController: [FCC]Airplane off, setFccChannel(-1)!!!
06-23 11:34:24.662  9374  9439 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
06-23 11:34:24.662  9374  9439 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,06-23 11:34:24.662  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
06-23 11:34:24.662  9374  9439 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
06-23 11:34:24.662  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
06-23 11:34:24.662  9374  9439 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aac7069 removed from the list
06-23 11:34:24.662  9374  9439 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aac7069 removed from the list
06-23 11:34:24.662  9374  9439 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
06-23 11:34:24.662  9374  9439 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe20aee removed from the list
06-23 11:34:24.662  9374  9439 D io.jxcore.node.ConnectivityMonitor: stop
,06-23 11:34:24.662  9374  9439 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
06-23 11:34:24.662  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
06-23 11:34:24.662  9374  9439 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testRun
,06-23 11:34:24.662  9642  9642 I InjectionManager: Inside getClassLibPath caller 
,06-23 11:34:24.662  9374  9666 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
06-23 11:34:24.662  9654  9654 W ResourcesManager: getTopLevelResources: /system/app/Hs20Provider/Hs20Provider.apk / 1.0 running in com.samsung.hs20provider rsrc of package com.samsung.hs20provider
06-23 11:34:24.662  9374  9666 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,06-23 11:34:24.672  3486  3849 E WifiNative-wlan0: do suspend false
,06-23 11:34:24.672  3486  3504 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
06-23 11:34:24.672  3151  3625 D EnterpriseController: netId is 0
06-23 11:34:24.672  3151  3625 D Netd    : getNetworkForDns: using netid 0 for uid 10074
06-23 11:34:24.672  9654  9654 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,06-23 11:34:24.672  9642  9642 W System  : ClassLoader referenced unknown path: /system/app/AllshareFileShareClient/lib/arm64
,06-23 11:34:24.672  9654  9654 D ResourcesManager: For user 0 new overlays fetched Null
,06-23 11:34:24.682  9642  9642 D InjectionManager: InjectionManager
,06-23 11:34:24.682  9642  9642 D InjectionManager: fillFeatureStoreMap com.samsung.android.app.FileShareClient
,06-23 11:34:24.682  9642  9642 I InjectionManager: Constructor com.samsung.android.app.FileShareClient, Feature store :{},
06-23 11:34:24.682  9642  9642 I InjectionManager: featureStore :{}
,06-23 11:34:24.682  9374  9668 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
06-23 11:34:24.682  9374  9668 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,06-23 11:34:24.682  9374  9668 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
06-23 11:34:24.682  9374  9666 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
06-23 11:34:24.682  9374  9666 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,06-23 11:34:24.682  9374  9666 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,06-23 11:34:24.682  3486  3848 D WifiP2pService: P2pDisabledState{ what=131203 }
,06-23 11:34:24.682  9374  9668 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
06-23 11:34:24.682  9374  9666 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,06-23 11:34:24.682  9374  9668 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
06-23 11:34:24.682  9374  9666 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
06-23 11:34:24.682  3486  3849 D WifiStateMachine:  p2p Needed be enabled 
06-23 11:34:24.682  9642  9642 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,06-23 11:34:24.682  9654  9654 I InjectionManager: Inside getClassLibPath caller 
06-23 11:34:24.682  9374  9672 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 240, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
06-23 11:34:24.682  9374  9672 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
06-23 11:34:24.682  9374  9672 D io.jxcore.node.StreamCopyingThread:  id: 74
06-23 11:34:24.682  3486  3849 D WifiNative-HAL: Failing getSupportedFeatureset because HAL isn't started
06-23 11:34:24.682  3486  3849 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,06-23 11:34:24.682  9374  9672 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 240, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
06-23 11:34:24.682  9374  9672 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
06-23 11:34:24.682  9374  9672 D io.jxcore.node.StreamCopyingThread:  id: 74
06-23 11:34:24.682  3486  3849 D WifiStateMachine: [FCC]Airplane off, setFccChannel(-1)!!!
06-23 11:34:24.682  3486  3849 D WifiStateMachine: setFccChannelNative: channel = -1
,06-23 11:34:24.682  3486  3849 D WifiNative-wlan0: callSECApiInt - ID [230]
,06-23 11:34:24.682  9374  9673 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 241, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
06-23 11:34:24.682  9374  9673 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
06-23 11:34:24.682  9374  9673 D io.jxcore.node.StreamCopyingThread:  id: 75
06-23 11:34:24.682  9374  9673 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 241, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
06-23 11:34:24.682  9374  9673 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
06-23 11:34:24.682  9374  9673 D io.jxcore.node.StreamCopyingThread:  id: 75
06-23 11:34:24.682  3486  3486 D RttService: SCAN_AVAILABLE : 3
06-23 11:34:24.682  3486  3883 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
06-23 11:34:24.682  3151  3629 D CommandListener: Setting iface cfg
06-23 11:34:24.682  3151  3629 D CommandListener: Trying to bring up p2p0
06-23 11:34:24.682  9374  9671 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 239, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
06-23 11:34:24.682  9374  9671 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
06-23 11:34:24.682  9374  9671 D io.jxcore.node.StreamCopyingThread:  id: 75
06-23 11:34:24.692  9374  9672 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
06-23 11:34:24.692  9374  9672 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
06-23 11:34:24.692  9374  9672 D io.jxcore.node.StreamCopyingThread:  id: 74
06-23 11:34:24.692  9374  9672 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
06-23 11:34:24.692  3151  3622 D Netd    : Iface p2p0 link up
,06-23 11:34:24.692  9374  9672 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
06-23 11:34:24.692  9374  9672 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
06-23 11:34:24.692  9374  9672 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
06-23 11:34:24.702  3486  3849 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
06-23 11:34:24.692  9374  9672 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
06-23 11:34:24.692  9374  9670 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 238, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
06-23 11:34:24.692  9374  9670 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
06-23 11:34:24.692  9374  9670 D io.jxcore.node.StreamCopyingThread:  id: 74
06-23 11:34:24.692  9374  9672 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,06-23 11:34:24.692  9374  9672 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 240, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
06-23 11:34:24.692  9374  9672 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
06-23 11:34:24.692  9374  9672 D io.jxcore.node.StreamCopyingThread:  id: 74 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
06-23 11:34:24.692  9374  9670 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 238, thread name: IncomingSocketThread/Sender): recvfrom failed: EBADF (Bad file descriptor)
06-23 11:34:24.692  9374  9670 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 238, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
06-23 11:34:24.692  9374  9670 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
06-23 11:34:24.692  9374  9670 D io.jxcore.node.StreamCopyingThread:  id: 74 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
06-23 11:34:24.692  9374  9670 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: recvfrom failed: EBADF (Bad file descriptor)
,06-23 11:34:24.692  9374  9670 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
06-23 11:34:24.692  9374  9670 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 238, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
06-23 11:34:24.692  9374  9670 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
06-23 11:34:24.692  9374  9670 D io.jxcore.node.StreamCopyingThread:  id: 74 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
06-23 11:34:24.692  9374  9671 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 239, thread name: OutgoingSocketThread/Sender): recvfrom failed: ECONNRESET (Connection reset by peer)
06-23 11:34:24.692  9374  9671 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 239, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
06-23 11:34:24.692  9374  9671 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
06-23 11:34:24.692  9374  9671 D io.jxcore.node.StreamCopyingThread:  id: 75 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
06-23 11:34:24.692  9374  9671 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: recvfrom failed: ECONNRESET (Connection reset by peer)
06-23 11:34:24.692  9374  9671 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,06-23 11:34:24.692  9374  9671 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 239, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
06-23 11:34:24.692  9374  9671 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
06-23 11:34:24.692  9374  9671 D io.jxcore.node.StreamCopyingThread:  id: 75 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
06-23 11:34:24.692  3486  3571 D Tethering: interfaceLinkStateChanged p2p0, true
06-23 11:34:24.692  3486  3571 D Tethering: interfaceStatusChanged p2p0, true
06-23 11:34:24.692  9374  9673 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
06-23 11:34:24.692  9374  9673 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
06-23 11:34:24.692  9374  9673 D io.jxcore.node.StreamCopyingThread:  id: 75
06-23 11:34:24.692  9374  9673 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
06-23 11:34:24.692  9374  9673 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
06-23 11:34:24.692  9374  9673 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
06-23 11:34:24.692  9374  9673 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,06-23 11:34:24.692  9374  9673 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
06-23 11:34:24.692  9374  9673 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
06-23 11:34:24.692  9374  9673 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 241, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
06-23 11:34:24.692  9374  9673 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
06-23 11:34:24.692  9374  9673 D io.jxcore.node.StreamCopyingThread:  id: 75 .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
06-23 11:34:24.692  4857  4875 D PdnController: Interface Changed p2p0 link up
06-23 11:34:24.692  3486  3882 E WifiScanningService: could not start HAL
06-23 11:34:24.692  3486  3848 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,06-23 11:34:24.692  9654  9654 W System  : ClassLoader referenced unknown path: /system/app/Hs20Provider/lib/arm64
06-23 11:34:24.692  3486  3848 D SecContentProvider: insert(), uri = 2
06-23 11:34:24.692  3486  3849 D WifiBigDataLog: getJsonFormat() - feature : ONOF
06-23 11:34:24.702  3486  3849 D WifiBigDataLog: init : 
,06-23 11:34:24.702  9642  9642 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,06-23 11:34:24.702  3486  3848 D WifiP2pService: P2pEnablingState
06-23 11:34:24.702  3486  3848 D WifiP2pService: P2pEnablingState{ what=147457 }
,06-23 11:34:24.702  3486  3848 D WifiP2pService: P2p socket connection successful
06-23 11:34:24.702  3486  3848 D WifiP2pService: P2pEnabledState
,06-23 11:34:24.702  3486  3848 D SecContentProvider: insert(), uri = 2
,06-23 11:34:24.712  3486  3567 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f15e0af u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{714895a 4842:com.samsung.android.providers.context/u0a7}
,06-23 11:34:24.712  3486  3848 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,06-23 11:34:24.712  3486  3858 E ConnectivityService: updateNetworkInfo()
06-23 11:34:24.712  3486  3858 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
,06-23 11:34:24.712  3486  3486 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,06-23 11:34:24.712  3486  3590 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
06-23 11:34:24.712  3486  3590 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false, mScanRequestedInConnected = false
06-23 11:34:24.712  3486  3590 D WifiDisplayController: disconnect
06-23 11:34:24.712  3486  3590 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,06-23 11:34:24.722  9654  9654 D InjectionManager: InjectionManager
,06-23 11:34:24.722  9654  9654 D InjectionManager: fillFeatureStoreMap com.samsung.hs20provider
,06-23 11:34:24.722  9654  9654 I InjectionManager: Constructor com.samsung.hs20provider, Feature store :{}
06-23 11:34:24.722  9654  9654 I InjectionManager: featureStore :{}
06-23 11:34:24.722  3928  3928 D WifiP2pController: onReceive android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,06-23 11:34:24.732  3486  4258 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9bc8445 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f56e889 9642:com.samsung.android.app.FileShareClient/5005}
,06-23 11:34:24.732  9654  9665 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_credentials
06-23 11:34:24.732  9654  9665 D HotspotProvider: CREDENTIAL
06-23 11:34:24.732  9654  9665 D HotspotProvider: No prepend tags
,06-23 11:34:24.732  9642  9642 D FileShare-Client: Outbound.stopDelayTimer - 
,06-23 11:34:24.732  9642  9642 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,06-23 11:34:24.732  9642  9642 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
06-23 11:34:24.732  9642  9642 D FileShare-Client: Outbound.stopDelayTimer - 
,06-23 11:34:24.732  3486  3590 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:24.732  3486  3590 I WifiDisplayAdapter: onP2pDisconnected
06-23 11:34:24.732  3486  3590 D IpRemoteDisplayController: disconnectWfdBridgeServer
06-23 11:34:24.732  3486  3590 D IpRemoteDisplayController: WfdBridgeServer is already null
,06-23 11:34:24.732  3928  3928 D SoundPathController: onReceive - android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,06-23 11:34:24.742  3928  3928 D ApMirroringController: onReceive android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,06-23 11:34:24.742  3928  3928 D AllShareCastTile: onReceive : android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
06-23 11:34:24.742  3486  4285 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
06-23 11:34:24.742  3928  3928 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
06-23 11:34:24.742  3486  4258 D ActivityManager:  getDeferredInfo final delay 0
,06-23 11:34:24.752  9596  9596 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,06-23 11:34:24.752  9596  9596 I wpa_supplicant: Scan aborted because the firmware maybe busy.
,06-23 11:34:24.752  9596  9596 I wpa_supplicant: Therefore we will repeat the scan command after 1 seconds.
06-23 11:34:24.752  3486  3849 I WifiStateMachine: mWifiNative.bssFlush()
06-23 11:34:24.752  9596  9596 I wpa_supplicant: wlan0: Setting scan request: 1 sec 0 usec
06-23 11:34:24.752  9674  9674 E Zygote  : v2
06-23 11:34:24.752  9674  9674 I libpersona: KNOX_SDCARD checking this for 1000
06-23 11:34:24.752  9674  9674 I libpersona: KNOX_SDCARD not a persona
,06-23 11:34:24.752  9596  9596 I wpa_supplicant: P2P: Set Samsung Discovery Icon = 256
06-23 11:34:24.752  3486  3849 D WifiStateMachine: setFccChannelNative: channel = -1
06-23 11:34:24.752  3486  3849 D WifiNative-wlan0: callSECApiInt - ID [230]
,06-23 11:34:24.752  9674  9674 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
06-23 11:34:24.762  3486  4258 I ActivityManager: Start proc 9674:com.policydm/1000 for broadcast-5 com.policydm/.XDMBroadcastReceiver
,06-23 11:34:24.762  9596  9596 I wpa_supplicant: P2P: Set Samsung Discovery name = 
06-23 11:34:24.762  9674  9674 E Zygote  : accessInfo : 0
,06-23 11:34:24.772  4245  4618 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,06-23 11:34:24.782  3486  4258 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9bc8445 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9233b8d 8766:com.samsung.android.app.FileShareServer/5005}
,06-23 11:34:24.782  3486  3853 D HS20StateMachine: CMD_HOTSPOT20_ENABLE : 
,06-23 11:34:24.782  3486  3853 D HS20StateMachine: enter : DiscoveringState
06-23 11:34:24.782  3486  3849 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,06-23 11:34:24.792  8766  8766 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
06-23 11:34:24.792  3486  3486 I ActivityManager: Killing 8578:com.android.providers.calendar/u0a47 (adj 15): DHA:empty #33
06-23 11:34:24.792  8766  8766 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
06-23 11:34:24.792  8766  8766 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
06-23 11:34:24.792  9674  9674 D TimaKeyStoreProvider: TimaSignature is unavailable
06-23 11:34:24.792  9674  9674 D ActivityThread: Added TimaKeyStore provider
,06-23 11:34:24.802  3486  3849 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,06-23 11:34:24.822  9374  9374 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-23 11:34:24.822  3486  4049 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{ed1643a u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7ef879a 9674:com.policydm/1000}
,06-23 11:34:24.822  3486  3504 I ActivityManager: Killing 8836:com.android.defcontainer/u0a8 (adj 15): DHA:empty #33
,06-23 11:34:24.832  9674  9674 W ResourcesManager: getTopLevelResources: /system/priv-app/SPDClient/SPDClient.apk / 1.0 running in com.policydm rsrc of package com.policydm
,06-23 11:34:24.832  3486  4433 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,06-23 11:34:24.842  9674  9674 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,06-23 11:34:24.842  9374  9374 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-23 11:34:24.842  3486  4258 D ActivityManager: cleanUpApplicationRecord -- 8578
,06-23 11:34:24.842  3486  4258 D ActivityManager: isAutoRunBlockedApp:: com.android.providers.calendar, Auto Run ON
,06-23 11:34:24.842  9674  9674 D ResourcesManager: For user 0 new overlays fetched Null
,06-23 11:34:24.852  9674  9674 I InjectionManager: Inside getClassLibPath caller 
,06-23 11:34:24.852  3486  4285 D ActivityManager: cleanUpApplicationRecord -- 8836
,06-23 11:34:24.852  3486  4285 D ActivityManager: isAutoRunBlockedApp:: com.android.defcontainer, Auto Run ON
,06-23 11:34:24.862  9674  9674 W System  : ClassLoader referenced unknown path: /system/priv-app/SPDClient/lib/arm64
06-23 11:34:24.862  3486  3848 E WifiP2pService: Failed to set my phone number info into probe response
,06-23 11:34:24.872  3486  3848 D WifiNative-p2p0: p2pGetDeviceAddress
,06-23 11:34:24.872  3486  3848 D WifiNative-p2p0: p2pGetDeviceAddress returning 4e:66:41:a9:a3:f3
,06-23 11:34:24.872  3486  3848 D WifiP2pService: DeviceAddress: 4e:a3:f3
,06-23 11:34:24.872  3486  3590 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: [Phone] Samsung Galaxy S7
06-23 11:34:24.872  3486  3590 D WifiDisplayController:  deviceAddress: 4e:66:41:a9:a3:f3
06-23 11:34:24.872  3486  3590 D WifiDisplayController:  primary type: 10-0050F204-5
06-23 11:34:24.872  3486  3590 D WifiDisplayController:  secondary type: null
06-23 11:34:24.872  3486  3590 D WifiDisplayController:  wps: 0
06-23 11:34:24.872  3486  3590 D WifiDisplayController:  grpcapab: 0
06-23 11:34:24.872  3486  3590 D WifiDisplayController:  devcapab: 0
06-23 11:34:24.872  3486  3590 D WifiDisplayController:  status: 3
06-23 11:34:24.872  3486  3590 D WifiDisplayController:  wfdInfo: null
06-23 11:34:24.872  3486  3590 D WifiDisplayController:  groupownerAddress: null
06-23 11:34:24.872  3486  3590 D WifiDisplayController:  GOdeviceName: null
06-23 11:34:24.872  3486  3590 D WifiDisplayController:  interfaceAddress: 
06-23 11:34:24.872  3486  3590 D WifiDisplayController:  SConnectInfo : null
06-23 11:34:24.872  3486  3590 D WifiDisplayController:  contactInfoHash : null
06-23 11:34:24.872  3486  3590 D WifiDisplayController:  ssDevInfo : 0
06-23 11:34:24.872  3486  3590 D WifiDisplayController:  iconIdx : 0
,06-23 11:34:24.882  3486  3848 D WifiP2pService: sending p2p persistent groups changed broadcast
,06-23 11:34:24.882  3486  3848 D WifiP2pService: InactiveState
06-23 11:34:24.882  3486  3848 D WifiP2pService: InactiveState{ what=143376 }
,06-23 11:34:24.882  9674  9674 I FOTA    : [lIlIIlIIlIlllIIIIlll(108/llIIIIlllllIIllIIllI)] oms: /customer.xml
06-23 11:34:24.882  3486  3848 D WifiP2pService: P2pEnabledState{ what=143376 }
06-23 11:34:24.882  9674  9674 I FOTA    : [lIlIIlIIlIlllIIIIlll(199/lllIlIlIIIllIIlIllIl)] read default : /system/csc/customer.xml
,06-23 11:34:24.892  9596  9596 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,06-23 11:34:24.892  3486  3848 D WifiP2pService: InactiveState{ what=143376 }
06-23 11:34:24.892  3486  3848 D WifiP2pService: P2pEnabledState{ what=143376 }
,06-23 11:34:24.912  9674  9674 I FOTA    : [com.sec.android.policyagent.PolicyApplication(36/onCreate)] PolicyApplication onCreated!
,06-23 11:34:24.922  9674  9674 I DBG_POLICYDM: [com.policydm.db.XDB(1600/IllIlIIIIlIIlIIIllIl)] xdbDMffs_Init
,06-23 11:34:24.942  9674  9674 I DBG_POLICYDM: [com.policydm.db.llIIIIlllllIIllIIllI(142/llIIIIlllllIIllIIllI)] try read dbString
,06-23 11:34:25.012  9674  9674 I DBG_POLICYDM: [com.policydm.XDMService(161/llIIIIlllllIIllIIllI)] xdmUIHandelerInit
,06-23 11:34:25.022  9674  9674 I DBG_POLICYDM: [IlIIIllIlIIIlIIlIIlI(52/<init>)] 
,06-23 11:34:25.022  9674  9674 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1394 android.content.ContextWrapper.bindService:632 IlIIIllIlIIIlIIlIIlI.<init>:56 IIIlIIlllIlIlIIIIIII.llIIIIlllllIIllIIllI:19 IIIlIIlllIlIlIIIIIII.llllIIIllIlIIIIllllI:25 
,06-23 11:34:25.052  9690  9690 E Zygote  : v2
06-23 11:34:25.052  9690  9690 I libpersona: KNOX_SDCARD checking this for 1000
06-23 11:34:25.052  9690  9690 I libpersona: KNOX_SDCARD not a persona
06-23 11:34:25.062  9690  9690 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,06-23 11:34:25.062  9690  9690 E Zygote  : accessInfo : 0
06-23 11:34:25.062  3486  4434 I ActivityManager: Start proc 9690:com.samsung.aasaservice/1000 for service com.samsung.aasaservice/.AASAService
,06-23 11:34:25.062  9674  9674 I DBG_POLICYDM: [IIIlIIlllIlIlIIIIIII(28/llllIIIllIlIIIIllllI)] AASAUpdater Init Success
,06-23 11:34:25.072  9674  9674 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,06-23 11:34:25.082  9674  9674 I DBG_POLICYDM: [com.policydm.XDMService(585/llIlIllllllllllllllI)] get NotibarState : 0
,06-23 11:34:25.082  9674  9674 D InjectionManager: InjectionManager
06-23 11:34:25.082  9674  9674 D InjectionManager: fillFeatureStoreMap com.policydm
,06-23 11:34:25.082  9674  9674 I InjectionManager: Constructor com.policydm, Feature store :{}
06-23 11:34:25.082  9674  9674 I InjectionManager: featureStore :{}
,06-23 11:34:25.092  9690  9690 D TimaKeyStoreProvider: TimaSignature is unavailable
06-23 11:34:25.092  9690  9690 D ActivityThread: Added TimaKeyStore provider
,06-23 11:34:25.102  9674  9674 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(574/IlIIIllllIIlIIIIIlII)] Initiated Type: 0
,06-23 11:34:25.112  9674  9674 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,06-23 11:34:25.112  9674  9674 I DBG_POLICYDM: [com.policydm.XDMService(585/llIlIllllllllllllllI)] get NotibarState : 0
,06-23 11:34:25.112  9690  9690 W ResourcesManager: getTopLevelResources: /system/app/AASAservice/AASAservice.apk / 1.0 running in com.samsung.aasaservice rsrc of package com.samsung.aasaservice
,06-23 11:34:25.112  3486  4257 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,06-23 11:34:25.112  9690  9690 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,06-23 11:34:25.122  9690  9690 D ResourcesManager: For user 0 new overlays fetched Null
,06-23 11:34:25.122  9690  9690 I InjectionManager: Inside getClassLibPath caller 
,06-23 11:34:25.132  9690  9690 W System  : ClassLoader referenced unknown path: /system/app/AASAservice/lib/arm64
,06-23 11:34:25.132  9690  9690 D InjectionManager: InjectionManager
,06-23 11:34:25.132  9690  9690 D InjectionManager: fillFeatureStoreMap com.samsung.aasaservice
06-23 11:34:25.132  9690  9690 I InjectionManager: Constructor com.samsung.aasaservice, Feature store :{}
06-23 11:34:25.132  9690  9690 I InjectionManager: featureStore :{}
,06-23 11:34:25.132  9690  9690 D AASAservice: onCreate()
,06-23 11:34:25.142  9674  9674 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(38/onServiceConnected)] AASA: onServiceConnected
,06-23 11:34:25.172  3486  3505 D ActivityManager:  getDeferredInfo final delay 300
,06-23 11:34:25.182  3486  3505 I ActivityManager: Killing 8999:com.samsung.android.app.galaxylabs/u0a15 (adj 15): DHA:empty #33
,06-23 11:34:25.192  3486  3505 I ActivityManager: Killing 9018:com.google.android.partnersetup/u0a23 (adj 15): DHA:empty #33
,06-23 11:34:25.202  3486  4435 D ActivityManager: cleanUpApplicationRecord -- 8999
,06-23 11:34:25.202  3486  4435 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.galaxylabs, Auto Run ON
,06-23 11:34:25.212  3486  3975 D ActivityManager: cleanUpApplicationRecord -- 9018
,06-23 11:34:25.212  3486  3975 D ActivityManager: isAutoRunBlockedApp:: com.google.android.partnersetup, Auto Run ON
,06-23 11:34:25.312  3486  3807 V AlarmManager: Expired Alarm result :4
,06-23 11:34:25.482  3486  3567 D ActivityManager:  getDeferredInfo final delay 0
,06-23 11:34:25.502  3486  3567 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{ed1643a u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7ef879a 9674:com.policydm/1000}
,06-23 11:34:25.502  9674  9674 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(51/onReceive)] RegistrationReceiver onReceive! action = android.net.conn.CONNECTIVITY_CHANGE
,06-23 11:34:25.512  3486  4434 D ActivityManager:  getDeferredInfo final delay 0
,06-23 11:34:25.522  3486  4434 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{ed1643a u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3d5d19d 6764:com.wssyncmldm/1000}
,06-23 11:34:25.532  3486  4434 D ActivityManager:  getDeferredInfo final delay 0
,06-23 11:34:25.542  3486  4434 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{ed1643a u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{abeac2a 6880:com.samsung.fresco.logging/5015}
,06-23 11:34:25.542  3486  3969 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-23 11:34:25.542  3486  4258 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-23 11:34:25.552  3486  4434 D ActivityManager:  getDeferredInfo final delay 0
,06-23 11:34:25.562  3486  4434 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{ed1643a u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{21eae4e 7313:com.sec.spp.push/u0a39}
,06-23 11:34:25.562  7313  7313 E SPPClientService: [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,06-23 11:34:25.562  7313  7313 E SPPClientService: [SystemStateMoniter] Current Time : 205713
,06-23 11:34:25.562  7313  7313 E SPPClientService: [SystemStateMoniter] No Connect : true
,06-23 11:34:25.572  3486  4434 D ActivityManager:  getDeferredInfo final delay 300
,06-23 11:34:25.582  7313  9703 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,06-23 11:34:25.752  9596  9596 I wpa_supplicant: P2P: Current p2p state = IDLE
,06-23 11:34:25.762  9596  9596 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,06-23 11:34:25.882  3486  3567 D ActivityManager:  getDeferredInfo final delay 0
,06-23 11:34:25.892  3486  3567 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{ed1643a u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bffa7e5 4913:android.process.media/u0a48}
,06-23 11:34:25.902  4913  4913 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,06-23 11:34:25.902  3486  4257 D ActivityManager:  getDeferredInfo final delay 0
,06-23 11:34:25.922  9704  9704 E Zygote  : v2
06-23 11:34:25.922  9704  9704 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
06-23 11:34:25.922  9704  9704 I libpersona: KNOX_SDCARD checking this for 1000
06-23 11:34:25.922  9704  9704 I libpersona: KNOX_SDCARD not a persona
,06-23 11:34:25.932  9704  9704 E Zygote  : accessInfo : 0
,06-23 11:34:25.932  3486  4257 I ActivityManager: Start proc 9704:com.samsung.android.SettingsReceiver/1000 for broadcast-5 com.samsung.android.SettingsReceiver/.SettingsIntentReceiver
,06-23 11:34:25.962  9704  9704 D TimaKeyStoreProvider: TimaSignature is unavailable
06-23 11:34:25.962  9704  9704 D ActivityThread: Added TimaKeyStore provider
,06-23 11:34:25.982  3486  4049 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{ed1643a u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{33f6fd 9704:com.samsung.android.SettingsReceiver/1000}
,06-23 11:34:25.992  9704  9704 W ResourcesManager: getTopLevelResources: /system/priv-app/SettingsReceiver/SettingsReceiver.apk / 1.0 running in com.samsung.android.SettingsReceiver rsrc of package com.samsung.android.SettingsReceiver
,06-23 11:34:25.992  3486  3505 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,06-23 11:34:25.992  9704  9704 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,06-23 11:34:25.992  9704  9704 D ResourcesManager: For user 0 new overlays fetched Null
,06-23 11:34:26.002  9704  9704 I InjectionManager: Inside getClassLibPath caller 
,06-23 11:34:26.012  9704  9704 W System  : ClassLoader referenced unknown path: /system/priv-app/SettingsReceiver/lib/arm64
,06-23 11:34:26.012  9704  9704 D InjectionManager: InjectionManager
06-23 11:34:26.012  9704  9704 D InjectionManager: fillFeatureStoreMap com.samsung.android.SettingsReceiver
,06-23 11:34:26.012  9704  9704 I InjectionManager: Constructor com.samsung.android.SettingsReceiver, Feature store :{}
06-23 11:34:26.012  9704  9704 I InjectionManager: featureStore :{}
,06-23 11:34:26.022  9704  9704 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in com.samsung.android.SettingsReceiver rsrc of package com.android.settings
,06-23 11:34:26.022  9704  9704 D ResourcesManager: For user 0 new overlays fetched Null
,06-23 11:34:26.032  9704  9704 E ActivityThread: Failed to find provider info for com.myscript.atk.rmc
,06-23 11:34:26.032  3486  3969 D ActivityManager:  getDeferredInfo final delay 0
,06-23 11:34:26.062  9717  9717 E Zygote  : v2
06-23 11:34:26.062  9717  9717 I libpersona: KNOX_SDCARD checking this for 10064
,06-23 11:34:26.062  9717  9717 I libpersona: KNOX_SDCARD not a persona
06-23 11:34:26.062  9717  9717 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,06-23 11:34:26.062  9717  9717 E Zygote  : accessInfo : 0
,06-23 11:34:26.062  9717  9717 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.android.themestore 
,06-23 11:34:26.062  3486  3969 I ActivityManager: Start proc 9717:com.samsung.android.themestore/u0a64 for broadcast-5 com.samsung.android.themestore/.manager.autoSelfUpgradeService.AutoSelfUpgradeReceiver
,06-23 11:34:26.062  3486  3969 I ActivityManager: Killing 9036:com.samsung.android.asksmanager/u0a171 (adj 15): DHA:empty #33
,06-23 11:34:26.092  3486  4049 D ActivityManager: cleanUpApplicationRecord -- 9036
,06-23 11:34:26.092  3486  4049 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.asksmanager, Auto Run ON
,06-23 11:34:26.092  9717  9717 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-23 11:34:26.092  9717  9717 D ActivityThread: Added TimaKeyStore provider
,06-23 11:34:26.112  3486  3504 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{ed1643a u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f6ff2 9717:com.samsung.android.themestore/u0a64}
,06-23 11:34:26.122  9717  9717 W ResourcesManager: getTopLevelResources: /system/priv-app/ThemeStore_3xh/ThemeStore_3xh.apk / 1.0 running in com.samsung.android.themestore rsrc of package com.samsung.android.themestore
,06-23 11:34:26.122  3486  4435 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,06-23 11:34:26.122  9717  9717 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,06-23 11:34:26.132  9717  9717 D ResourcesManager: For user 0 new overlays fetched Null
,06-23 11:34:26.132  9717  9717 I InjectionManager: Inside getClassLibPath caller 
,06-23 11:34:26.142  9717  9717 W System  : ClassLoader referenced unknown path: /system/priv-app/ThemeStore_3xh/lib/arm64
,06-23 11:34:26.162  9717  9717 D a       : Exist Config : false
,06-23 11:34:26.162  9717  9717 D a       : getMcc
,06-23 11:34:26.162  9717  9717 D ai      : isQaMode
,06-23 11:34:26.172  9717  9717 D a       : getMnc
06-23 11:34:26.172  9717  9717 D a       : getCsc
,06-23 11:34:26.172  9717  9717 D a       : getSystemCountryCode
06-23 11:34:26.172  9717  9717 D a       : getImei
,06-23 11:34:26.172  9717  9717 D ai      : getMd5HashString
,06-23 11:34:26.182  9717  9717 D ai      : getSha256HashString
,06-23 11:34:26.182  9717  9717 D a       : getMsisdn
,06-23 11:34:26.182  4245  4618 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,06-23 11:34:26.192  9717  9717 D a       : getModelName
,06-23 11:34:26.192  9717  9717 D a       : getVirtualModelName
06-23 11:34:26.192  9717  9717 D a       : getAndroidSDKVersion
,06-23 11:34:26.192  9717  9717 D a       : getLanguageCode
06-23 11:34:26.192  9717  9717 D a       : getCountryCode
,06-23 11:34:26.192  9717  9717 D a       : getNetworkType
,06-23 11:34:26.202  9717  9717 D t       : isSupportedAodSystemFeature
,06-23 11:34:26.202  9717  9717 D a       : isLogPrintMode
,06-23 11:34:26.212  9717  9717 D ai      : isQaMode
,06-23 11:34:26.212  9717  9717 D a       : getVerName
,06-23 11:34:26.212  9717  9717 D a       : getVerCode
,06-23 11:34:26.222  9717  9717 D a       : getPackageName
,06-23 11:34:26.222  9717  9717 D a       : getAutoUpgradeInterval
,06-23 11:34:26.222  9717  9717 D a       : loadCountrySearchEx
,06-23 11:34:26.232  9717  9717 I a       : voCountrySearchEx loaded.
,06-23 11:34:26.232  9717  9717 I a       : # initConfig Time : 84
,06-23 11:34:26.232  9717  9717 I a       : ● MCCNNC : 260 0
06-23 11:34:26.232  9717  9717 I a       : ● Model : SM-G930F_TM
06-23 11:34:26.232  9717  9717 I a       : ● MyApp Vertion : 1.03.22(20160524)
06-23 11:34:26.232  9717  9717 I a       : ● OS Vertion : 23
,06-23 11:34:26.262  9717  9717 D InjectionManager: InjectionManager
,06-23 11:34:26.262  9717  9717 D InjectionManager: fillFeatureStoreMap com.samsung.android.themestore
06-23 11:34:26.262  9717  9717 I InjectionManager: Constructor com.samsung.android.themestore, Feature store :{}
06-23 11:34:26.262  9717  9717 I InjectionManager: featureStore :{}
,06-23 11:34:26.262  9717  9717 D AutoSelfUpgradeReceiver: onReceive() android.net.conn.CONNECTIVITY_CHANGE
,06-23 11:34:26.312  3486  3975 D ActivityManager:  getDeferredInfo final delay 0
,06-23 11:34:26.332  9736  9736 E Zygote  : v2
06-23 11:34:26.332  9736  9736 I libpersona: KNOX_SDCARD checking this for 5009
,06-23 11:34:26.332  9736  9736 I libpersona: KNOX_SDCARD not a persona
06-23 11:34:26.332  9736  9736 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,06-23 11:34:26.332  9736  9736 E Zygote  : accessInfo : 0
06-23 11:34:26.332  3486  3975 I ActivityManager: Start proc 9736:com.samsung.android.scloud:contentsync/5009 for broadcast-5 com.samsung.android.scloud/.cloudagent.detector.DetectorReceiver
,06-23 11:34:26.332  9736  9736 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.scloud:contentsync 
,06-23 11:34:26.342  3486  3975 I ActivityManager: Killing 9062:com.samsung.svoice.sync/u0a40 (adj 15): DHA:empty #33
,06-23 11:34:26.362  3486  4257 D ActivityManager: cleanUpApplicationRecord -- 9062
,06-23 11:34:26.362  3486  4257 D ActivityManager: isAutoRunBlockedApp:: com.samsung.svoice.sync, Auto Run ON
,06-23 11:34:26.372  9736  9736 D TimaKeyStoreProvider: TimaSignature is unavailable
06-23 11:34:26.372  9736  9736 D ActivityThread: Added TimaKeyStore provider
,06-23 11:34:26.382  3486  4258 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{ed1643a u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1da9643 9736:com.samsung.android.scloud:contentsync/5009}
,06-23 11:34:26.392  9736  9736 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.samsung.android.scloud
,06-23 11:34:26.392  3486  3504 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
06-23 11:34:26.392  9736  9736 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,06-23 11:34:26.402  9736  9736 D ResourcesManager: For user 0 new overlays fetched Null
,06-23 11:34:26.402  9736  9736 I InjectionManager: Inside getClassLibPath caller 
,06-23 11:34:26.412  9736  9736 W System  : ClassLoader referenced unknown path: /system/priv-app/SamsungCloud/lib/arm64
,06-23 11:34:26.442  9736  9736 I [SC]CloudManager: requestInit
,06-23 11:34:26.482  9736  9736 I [SC]Utils: folder : cachecreate fail, try again.
,06-23 11:34:26.482  9736  9736 I [SC]Utils: folder : cache create fail.
06-23 11:34:26.482  9736  9736 I [SC]Utils: folder : thumbnailcreate fail, try again.
06-23 11:34:26.482  9736  9736 I [SC]Utils: folder : thumbnail create fail.
06-23 11:34:26.482  9736  9736 I [SC]Utils: folder : sharecreate fail, try again.
,06-23 11:34:26.482  9736  9736 I [SC]Utils: folder : share create fail.
06-23 11:34:26.482  9736  9736 I [SC]Utils: folder : scratchcreate fail, try again.
06-23 11:34:26.482  9736  9736 I [SC]Utils: folder : scratch create fail.
,06-23 11:34:26.482  9736  9736 I [SC]Utils: folder : eventSynccreate fail, try again.
,06-23 11:34:26.482  9736  9736 I [SC]Utils: folder : eventSync create fail.
,06-23 11:34:26.512  9736  9736 V SamsungCloudLogs:  set Log level [4->4]act[false]
,06-23 11:34:26.512  9736  9736 I [SC]CommonUtil: isSemAvailable:0
,06-23 11:34:26.522  9736  9736 I [SC]SamsungCloudApp: AppVer[2.1.14][L:4]Sem[false]V21MAIN_R slog[false]com.samsung.android.scloud:contentsync
,06-23 11:34:26.522  9736  9736 D InjectionManager: InjectionManager
06-23 11:34:26.522  9736  9736 D InjectionManager: fillFeatureStoreMap com.samsung.android.scloud
06-23 11:34:26.522  9736  9736 I InjectionManager: Constructor com.samsung.android.scloud, Feature store :{}
,06-23 11:34:26.522  9736  9736 I InjectionManager: featureStore :{}
,06-23 11:34:26.522  9736  9736 I [SC]FeatureManager: FeatureManager 
06-23 11:34:26.522  9736  9736 I [SC]FeatureManager: [SEC_FLOATING_FEATURE_SAMSUNGCLOUD_CONFIG_CLOUD_USAGE_MENU_TREE]str 
06-23 11:34:26.522  9736  9736 I [SC]FeatureManager: [SEC_FLOATING_FEATURE_SAMSUNGCLOUD_ENABLE_SETTING_MENU]bln true
,06-23 11:34:26.532  9736  9736 E [SC]SCLOUD_ERR-Utils: isShipMode : 1 
,06-23 11:34:26.532  9736  9736 I [SC]DetectorReceiver: onReceive [android.net.conn.CONNECTIVITY_CHANGE]
,06-23 11:34:26.532  9736  9736 I [SC]CloudManager: requestInit
06-23 11:34:26.532  9736  9736 I [SC]Utils: folder : cachecreate fail, try again.
06-23 11:34:26.532  9736  9736 I [SC]Utils: folder : cache create fail.
06-23 11:34:26.532  9736  9736 I [SC]Utils: folder : thumbnailcreate fail, try again.
06-23 11:34:26.532  9736  9736 I [SC]Utils: folder : thumbnail create fail.
,06-23 11:34:26.532  9736  9736 I [SC]Utils: folder : sharecreate fail, try again.
06-23 11:34:26.532  9736  9736 I [SC]Utils: folder : share create fail.
,06-23 11:34:26.532  9736  9736 I [SC]Utils: folder : scratchcreate fail, try again.
06-23 11:34:26.532  9736  9736 I [SC]Utils: folder : scratch create fail.
06-23 11:34:26.532  9736  9736 I [SC]Utils: folder : eventSynccreate fail, try again.
,06-23 11:34:26.542  9736  9736 I [SC]Utils: folder : eventSync create fail.
,06-23 11:34:26.552  8868  8878 I SA      : [SCU] isHaveSA() - false
,06-23 11:34:26.552  8868  8878 I SA      : [OCP] Samsung account is not Signed-in
,06-23 11:34:26.562  8868  8878 I SA      : [OCP] Delete DB (TNC data)
,06-23 11:34:26.562  9736  9736 I [SC]CommonUtil: Samsung Account Not Logged in
,06-23 11:34:26.562  3486  3505 D ActivityManager:  getDeferredInfo final delay 0
,06-23 11:34:26.562  3486  4049 I ActivityManager: Killing 9118:com.samsung.android.provider.shootingmodeprovider/u0a57 (adj 15): DHA:empty #33
,06-23 11:34:26.612  9750  9750 E Zygote  : v2
,06-23 11:34:26.612  9750  9750 I libpersona: KNOX_SDCARD checking this for 5011
06-23 11:34:26.612  9750  9750 I libpersona: KNOX_SDCARD not a persona
06-23 11:34:26.612  9750  9750 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,06-23 11:34:26.622  9750  9750 E Zygote  : accessInfo : 0
,06-23 11:34:26.622  9750  9750 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.coreapps 
06-23 11:34:26.622  3486  3505 I ActivityManager: Start proc 9750:com.samsung.android.coreapps/5011 for broadcast-5 com.samsung.android.coreapps/.easysignup.receiver.NetworkStateListener
,06-23 11:34:26.632  3486  3504 D ActivityManager: cleanUpApplicationRecord -- 9118
,06-23 11:34:26.642  3486  3504 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.provider.shootingmodeprovider, Auto Run ON
,06-23 11:34:26.652  9750  9750 D TimaKeyStoreProvider: TimaSignature is unavailable
06-23 11:34:26.652  9750  9750 D ActivityThread: Added TimaKeyStore provider
,06-23 11:34:26.662  3486  4435 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{ed1643a u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{606539f 9750:com.samsung.android.coreapps/5011}
,06-23 11:34:26.672  9750  9750 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in com.samsung.android.coreapps rsrc of package com.samsung.android.coreapps
,06-23 11:34:26.672  3486  4257 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,06-23 11:34:26.672  9750  9750 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,06-23 11:34:26.682  9750  9750 D ResourcesManager: For user 0 new overlays fetched Null
,06-23 11:34:26.682  9750  9750 I InjectionManager: Inside getClassLibPath caller 
,06-23 11:34:26.692  9750  9750 W System  : ClassLoader referenced unknown path: /system/app/CoreApps/lib/arm64
,06-23 11:34:26.712  9750  9750 D CoreApps: SEC_LOG - true
,06-23 11:34:26.772  9750  9750 E GooglePlayServicesUtil: The Google Play services resources were not found. Check your project configuration to ensure that the resources are included.
,06-23 11:34:26.992  9750  9750 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Epic_Common/SecMms_Epic_Common.apk / 1.0 running in com.samsung.android.coreapps rsrc of package com.android.mms
,06-23 11:34:27.002  9750  9750 D ResourcesManager: For user 0 new overlays fetched Null
,06-23 11:34:27.012  9750  9750 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.samsung.android.coreapps rsrc of package com.google.android.talk
,06-23 11:34:27.012  9750  9750 D ResourcesManager: For user 0 new overlays fetched Null
,06-23 11:34:27.022  9750  9750 D InjectionManager: InjectionManager
06-23 11:34:27.022  9750  9750 D InjectionManager: fillFeatureStoreMap com.samsung.android.coreapps
,06-23 11:34:27.022  9750  9750 I InjectionManager: Constructor com.samsung.android.coreapps, Feature store :{}
06-23 11:34:27.022  9750  9750 I InjectionManager: featureStore :{}
,06-23 11:34:27.032  3486  4257 D ActivityManager:  getDeferredInfo final delay 0
,06-23 11:34:27.042  3486  4257 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{ed1643a u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{606539f 9750:com.samsung.android.coreapps/5011}
,06-23 11:34:27.062  3486  4258 D ActivityManager:  getDeferredInfo final delay 0
,06-23 11:34:27.072  3486  4258 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{ed1643a u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{606539f 9750:com.samsung.android.coreapps/5011}
,06-23 11:34:27.072  3486  4258 D ActivityManager:  getDeferredInfo final delay 0
,06-23 11:34:27.072  3486  4258 I ActivityManager: Killing 8929:com.samsung.android.sm.devicesecurity/5012 (adj 15): DHA:empty #33
,06-23 11:34:27.082  3486  4258 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{ed1643a u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ba75d83 4876:com.microsoft.skydrive/u0a124}
,06-23 11:34:27.082  3486  4396 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-23 11:34:27.102  3486  3504 D ActivityManager: cleanUpApplicationRecord -- 8929
,06-23 11:34:27.102  3486  3504 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sm.devicesecurity, Auto Run ON
,06-23 11:34:27.112  3486  3970 W IntentResolver: resolveIntent failed: found match, but none with CATEGORY_DEFAULT
,06-23 11:34:27.112  3486  3505 D ActivityManager:  getDeferredInfo final delay 300
,06-23 11:34:27.462  3486  3567 D ActivityManager:  getDeferredInfo final delay 0
,06-23 11:34:27.482  9778  9778 E Zygote  : v2
06-23 11:34:27.482  9778  9778 I libpersona: KNOX_SDCARD checking this for 10129
06-23 11:34:27.482  9778  9778 I libpersona: KNOX_SDCARD not a persona
,06-23 11:34:27.482  9778  9778 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,06-23 11:34:27.482  3486  3567 I ActivityManager: Start proc 9778:com.google.android.apps.photos/u0a129 for broadcast-5 com.google.android.apps.photos/.actionqueue.SystemReceiver
06-23 11:34:27.482  3486  3847 D NetworkPolicy: isUidForegroundLocked: 10129, mScreenOn: true, uidstate: -1, mProxSensorScreenOff: false
06-23 11:34:27.482  9778  9778 E Zygote  : accessInfo : 0
06-23 11:34:27.482  9778  9778 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.photos 
,06-23 11:34:27.512  9778  9778 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-23 11:34:27.512  9778  9778 D ActivityThread: Added TimaKeyStore provider
,06-23 11:34:27.532  3151  3622 D Netd    : Iface wlan0 link up
,06-23 11:34:27.532  3486  3571 D Tethering: interfaceLinkStateChanged wlan0, true
06-23 11:34:27.532  3486  3571 D Tethering: interfaceStatusChanged wlan0, true
06-23 11:34:27.542  9596  9596 I wpa_supplicant: nl80211: Received scan results (24 BSSes)
,06-23 11:34:27.542  4857  4872 D PdnController: Interface Changed wlan0 link up
,06-23 11:34:27.542  9596  9596 I wpa_supplicant: autoscan_samsung_exponential_notify_scan : scan_interval = 8
06-23 11:34:27.542  9596  9596 I wpa_supplicant: autoscan: autoscan_notify_scan, scan_interval = 8
06-23 11:34:27.542  9596  9596 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
06-23 11:34:27.542  9596  9596 I wpa_supplicant:    allow  - level is under -85dBm [-35] or selected nid [-1] [3]
,06-23 11:34:27.542  3486  4379 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{ed1643a u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3890b4a 9778:com.google.android.apps.photos/u0a129}
06-23 11:34:27.542  3486  3847 D NetworkPolicy: isUidForegroundLocked: 10129, mScreenOn: true, uidstate: 11, mProxSensorScreenOff: false
,06-23 11:34:27.542  9596  9596 I wpa_supplicant:  selected from pick network BSS F4.99.3E ssid='NG700' et= 090,gp=03,cu=987654321,sc=987654321
,06-23 11:34:27.542  9596  9596 I wpa_supplicant:    allow  - level is under -85dBm [-35] or selected nid [-1] [3]
06-23 11:34:27.542  9596  9596 I wpa_supplicant: wlan0: Trying to associate with f4:f2:6d:22:99:3e (SSID='NG700' freq=2442 MHz level=-35) 
,06-23 11:34:27.552  9778  9778 W ResourcesManager: getTopLevelResources: /system/app/Photos/Photos.apk / 1.0 running in com.google.android.apps.photos rsrc of package com.google.android.apps.photos
,06-23 11:34:27.562  3486  4434 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,06-23 11:34:27.562  9778  9778 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,06-23 11:34:27.572  9778  9778 D ResourcesManager: For user 0 new overlays fetched Null
,06-23 11:34:27.572  9778  9778 I InjectionManager: Inside getClassLibPath caller 
,06-23 11:34:27.582  9778  9778 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm64
,06-23 11:34:27.592  3486  3849 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,06-23 11:34:27.592  3486  3486 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.SCAN_RESULTS
,06-23 11:34:27.602  3486  3567 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8068abb u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{33215a9 3928:com.android.systemui/u0a62}
,06-23 11:34:27.602  9374  9374 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-23 11:34:27.652  9504  9504 D Babel   : RefCountedService(com.google.android.apps.hangouts.requestwriter.RequestWriter) onDestroy (count=0, startId=1 stopped=true)
,06-23 11:34:27.652  3486  3970 I ActivityManager: Killing 9132:com.samsung.android.themecenter/1000 (adj 15): DHA:empty #33
06-23 11:34:27.652  9596  9596 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,06-23 11:34:27.662  3151  3622 D Netd    : Iface wlan0 link up
06-23 11:34:27.662  3151  3622 D Netd    : Iface wlan0 link up
06-23 11:34:27.662  3151  3622 D Netd    : Iface wlan0 link up
06-23 11:34:27.662  3486  3571 D Tethering: interfaceLinkStateChanged wlan0, true
06-23 11:34:27.662  3486  3571 D Tethering: interfaceStatusChanged wlan0, true
,06-23 11:34:27.662  4857  5193 D PdnController: Interface Changed wlan0 link up
06-23 11:34:27.662  3486  3571 D Tethering: interfaceLinkStateChanged wlan0, true
06-23 11:34:27.662  3486  3571 D Tethering: interfaceStatusChanged wlan0, true
,06-23 11:34:27.662  4857  4875 D PdnController: Interface Changed wlan0 link up
06-23 11:34:27.662  3486  3571 D Tethering: interfaceLinkStateChanged wlan0, true
06-23 11:34:27.662  3486  3571 D Tethering: interfaceStatusChanged wlan0, true
,06-23 11:34:27.672  4857  4872 D PdnController: Interface Changed wlan0 link up
06-23 11:34:27.672  9596  9596 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
06-23 11:34:27.672  9596  9596 I wpa_supplicant: wlan0: WPA: RX message 1 of 4-Way Handshake from F4.99.3E (ver=2)
06-23 11:34:27.672  9596  9596 I wpa_supplicant: wlan0: WPA: Sending EAPOL-Key 2/4
,06-23 11:34:27.682  3486  3849 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,06-23 11:34:27.682  9596  9596 I wpa_supplicant: wlan0: WPA: RX message 3 of 4-Way Handshake from F4.99.3E (ver=2)
,06-23 11:34:27.692  3486  4049 D ActivityManager: cleanUpApplicationRecord -- 9132
,06-23 11:34:27.692  3486  4049 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.themecenter, Auto Run ON
06-23 11:34:27.692  9596  9596 I wpa_supplicant: wlan0: WPA: Sending EAPOL-Key 4/4
,06-23 11:34:27.692  9596  9596 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
06-23 11:34:27.692  9596  9596 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=3 id_str=]
,06-23 11:34:27.692  3151  3622 D Netd    : Iface wlan0 link up
06-23 11:34:27.692  9596  9596 I wpa_supplicant: Blacklist: Clear (temp) 
,06-23 11:34:27.702  3486  3571 D Tethering: interfaceLinkStateChanged wlan0, true
,06-23 11:34:27.702  3486  3571 D Tethering: interfaceStatusChanged wlan0, true
,06-23 11:34:27.702  4857  5193 D PdnController: Interface Changed wlan0 link up
,06-23 11:34:27.702  3486  3849 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,06-23 11:34:27.702  9374  9374 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-23 11:34:27.712  3486  3849 D WifiNative-wlan0: callSECApiVoid - ID [50]
,06-23 11:34:27.712  9374  9374 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-23 11:34:27.722  3486  3849 V AlarmManager:  remove PendingIntent] PendingIntent{c37c543: PendingIntentRecord{6ab97c0 android broadcastIntent}}
,06-23 11:34:27.722  3486  3849 D WifiNetworkAgent: NetworkAgent: Registering NetworkAgent
,06-23 11:34:27.722  3486  3486 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
06-23 11:34:27.722  3486  3486 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
06-23 11:34:27.722  3486  3486 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
06-23 11:34:27.722  3486  3856 I WifiHs20Service: Message received 5007
06-23 11:34:27.722  3486  3849 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
06-23 11:34:27.722  3486  3858 E ConnectivityService: updateNetworkInfo()
06-23 11:34:27.722  3486  3858 D ConnectivityService: Got NetworkAgent Messenger
06-23 11:34:27.722  3486  3858 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-23 11:34:27.722  3486  3858 D ConnectivityService: NetworkAgent connected
06-23 11:34:27.722  3486  3486 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
,06-23 11:34:27.732  3928  4125 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,06-23 11:34:27.732  3151  3629 D CommandListener: Setting iface cfg
,06-23 11:34:27.732  4245  4245 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,06-23 11:34:27.742  3486  3567 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{831628f u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2a680b6 9601:com.sec.android.diagmonagent/1000}
,06-23 11:34:27.742  3486  3849 D WifiStateMachine: Start Dhcp Watchdog 2
,06-23 11:34:27.742  9601  9601 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,06-23 11:34:27.742  9601  9601 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
06-23 11:34:27.742  9601  9601 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
06-23 11:34:27.742  9601  9601 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,06-23 11:34:27.752  3486  3849 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,06-23 11:34:27.752  3486  3504 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{831628f u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{aa2736c 6417:com.enhance.gameservice/u0a106}
,06-23 11:34:27.772  9374  9374 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-23 11:34:27.772  3486  3504 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{831628f u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ee071b7 9614:com.sec.knox.switcher/1000}
,06-23 11:34:27.772  9614  9614 I usagelog: received in receiver
06-23 11:34:27.772  9614  9614 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
06-23 11:34:27.772  9614  9614 I KnoxUsageLogPro: premStatus:2
,06-23 11:34:27.772  9614  9614 I KnoxUsageLogPro: isEulaShown : false
06-23 11:34:27.772  9614  9614 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,06-23 11:34:27.782  3486  3849 D WifiNetworkAgent: NetworkAgent: NetworkAgent fully connected
06-23 11:34:27.782  3486  3858 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -37]
06-23 11:34:27.782  3486  3858 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,06-23 11:34:27.782  3928  4125 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,06-23 11:34:27.792  3486  3858 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,06-23 11:34:27.792  3486  3504 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{831628f u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2c05d24 9627:com.samsung.android.sm.policy/u0a135}
,06-23 11:34:27.812  9778  9778 W ResourcesManager: getTopLevelResources: /system/app/Photos/Photos.apk / 1.0 running in com.google.android.apps.photos rsrc of package com.google.android.apps.photos
,06-23 11:34:27.882  3486  3849 E WifiNative-wlan0: do suspend false
,06-23 11:34:27.892  3486  3849 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,06-23 11:34:27.892  3486  3848 D WifiP2pService: InactiveState{ what=143375 }
06-23 11:34:27.892  3486  3848 D WifiP2pService: P2pEnabledState{ what=143375 }
,06-23 11:34:27.892  9778  9778 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,06-23 11:34:27.892  9374  9374 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-23 11:34:27.902  9796  9796 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,06-23 11:34:27.912  9796  9796 I dhcpcd  : version 5.5.6 starting
,06-23 11:34:27.912  9796  9796 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,06-23 11:34:27.952  9796  9796 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,06-23 11:34:27.952  9796  9796 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
06-23 11:34:27.952  9796  9796 I dhcpcd  : bssid match
06-23 11:34:27.952  9796  9796 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
,06-23 11:34:27.992  9778  9778 D InjectionManager: InjectionManager
,06-23 11:34:27.992  9778  9778 D InjectionManager: fillFeatureStoreMap com.google.android.apps.photos
06-23 11:34:27.992  9778  9778 I InjectionManager: Constructor com.google.android.apps.photos, Feature store :{}
06-23 11:34:27.992  9778  9778 I InjectionManager: featureStore :{}
,06-23 11:34:28.002  9796  9796 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,06-23 11:34:28.012  3486  3567 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{49aa14c u0 com.google.android.apps.photos.actionqueue.INTERNAL_ACTION qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3890b4a 9778:com.google.android.apps.photos/u0a129}
,06-23 11:34:28.012  3486  4434 D ActivityManager:  getDeferredInfo final delay 0
,06-23 11:34:28.032  3486  4434 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{ed1643a u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3890b4a 9778:com.google.android.apps.photos/u0a129}
,06-23 11:34:28.072  9796  9796 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
,06-23 11:34:28.072  3486  3858 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,06-23 11:34:28.092  3486  3567 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{fc40595 u0 com.google.android.apps.photos.jobqueue.EXECUTE_JOBS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3890b4a 9778:com.google.android.apps.photos/u0a129}
,06-23 11:34:28.092  3486  3505 D ActivityManager:  getDeferredInfo final delay 0
,06-23 11:34:28.102  3486  3505 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{ed1643a u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9d0129b 4622:com.sec.android.daemonapp/u0a159}
,06-23 11:34:28.102  4622  4622 D [Weather Widget]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CFAAE09BFCA326403459399C53A4EE79DAC193CEB26509F8FF7498BE5251A746097407E81C28CD811D388C49D613C81F395B356AA489D29CB4C3BE983CCC84BA76AF507AA66A943348DF162DECA2A5A7DD]}
,06-23 11:34:28.102  4622  4622 D [Weather Widget]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CFE2E89F45594D9820F24D88E9AF210A78F9CD3967C07B6DE6AAB9923C4C53919020112019F4465EB3AA6FD266958B212E]}
,06-23 11:34:28.112  3486  3505 D ActivityManager:  getDeferredInfo final delay 300
,06-23 11:34:28.142  3486  3504 I ActivityManager: Killing 9145:com.samsung.android.scloud/5009 (adj 15): DHA:empty #33
,06-23 11:34:28.162  3486  4395 D ActivityManager: cleanUpApplicationRecord -- 9145
,06-23 11:34:28.162  3486  4395 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.scloud, Auto Run ON
,06-23 11:34:28.472  3486  3567 D ActivityManager:  getDeferredInfo final delay 0
,06-23 11:34:28.482  3486  3567 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{ed1643a u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ac9d8 7814:com.sec.android.app.samsungapps/u0a14}
,06-23 11:34:28.482  3486  3504 D ActivityManager:  getDeferredInfo final delay 0
,06-23 11:34:28.492  3486  3504 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{63888c u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2a680b6 9601:com.sec.android.diagmonagent/1000}
,06-23 11:34:28.502  9601  9601 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,06-23 11:34:28.502  9601  9601 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
06-23 11:34:28.502  9601  9601 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,06-23 11:34:28.502  3486  3504 D ActivityManager:  getDeferredInfo final delay 0
,06-23 11:34:28.512  3486  3848 D WifiP2pService: InactiveState{ what=143375 }
06-23 11:34:28.512  3486  3504 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{63888c u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ee071b7 9614:com.sec.knox.switcher/1000}
06-23 11:34:28.512  3486  3848 D WifiP2pService: P2pEnabledState{ what=143375 }
,06-23 11:34:28.512  9614  9614 I usagelog: received in receiver
,06-23 11:34:28.512  9614  9614 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
06-23 11:34:28.512  9614  9614 I KnoxUsageLogPro: premStatus:2
06-23 11:34:28.512  9614  9614 I KnoxUsageLogPro: isEulaShown : false
06-23 11:34:28.512  9614  9614 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,06-23 11:34:28.522  3486  3858 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,06-23 11:34:28.522  3486  3504 D ActivityManager:  getDeferredInfo final delay 0
,06-23 11:34:28.522  3486  3849 D WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
06-23 11:34:28.522  3486  3849 D WifiStateMachine: VerifyingLinkState enter
06-23 11:34:28.522  3486  3858 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -37], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -37]
,06-23 11:34:28.532  3486  3504 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{63888c u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2c05d24 9627:com.samsung.android.sm.policy/u0a135}
,06-23 11:34:28.532  3486  3858 E ConnectivityService: updateNetworkInfo()
,06-23 11:34:28.542  3928  4125 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,06-23 11:34:28.542  3486  3858 D ConnectivityService: Adding iface wlan0 to network 503
06-23 11:34:28.542  3486  3858 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}, oldLp = null
,06-23 11:34:28.542  3486  3486 D WifiNotificationController: SHOW_NOTI_MESSAGE : 9, visible : false, ssid : "NG700", targetSSID : null, netId : -1, titleType : -1
,06-23 11:34:28.542  3486  3504 D ActivityManager:  getDeferredInfo final delay 0
,06-23 11:34:28.552  3486  3486 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
06-23 11:34:28.552  3486  3486 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
06-23 11:34:28.552  3486  3486 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
,06-23 11:34:28.552  3486  3856 I WifiHs20Service: Message received 5007
06-23 11:34:28.552  3486  3486 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
,06-23 11:34:28.552  3486  3875 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,06-23 11:34:28.552  3486  3875 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}
06-23 11:34:28.552  3486  3875 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}
06-23 11:34:28.552  3486  3875 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}
,06-23 11:34:28.552  3486  3875 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}
,06-23 11:34:28.552  3928  4125 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,06-23 11:34:28.552  4245  4245 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,06-23 11:34:28.562  3486  3567 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{aa6d376 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2a680b6 9601:com.sec.android.diagmonagent/1000}
,06-23 11:34:28.562  9601  9601 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,06-23 11:34:28.562  9601  9601 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
06-23 11:34:28.562  9601  9601 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
,06-23 11:34:28.562  9601  9601 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,06-23 11:34:28.572  3486  3858 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 503
,06-23 11:34:28.572  3486  3858 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,06-23 11:34:28.582  3486  3858 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
,06-23 11:34:28.582  3486  3858 E ConnectivityService: Unexpected mtu value: 0, wlan0
06-23 11:34:28.582  3486  3858 D ConnectivityService: Setting Dns servers for network 503 to [/192.168.1.1]
,06-23 11:34:28.582  9839  9839 E Zygote  : v2
06-23 11:34:28.582  9839  9839 I libpersona: KNOX_SDCARD checking this for 1000
06-23 11:34:28.582  9839  9839 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
06-23 11:34:28.582  9839  9839 I libpersona: KNOX_SDCARD not a persona
,06-23 11:34:28.582  9839  9839 E Zygote  : accessInfo : 0
,06-23 11:34:28.582  3486  3504 I ActivityManager: Start proc 9839:com.samsung.android.securitylogagent/1000 for broadcast-5 com.samsung.android.securitylogagent/.receivers.NetworkReceiver
,06-23 11:34:28.602  9839  9839 D TimaKeyStoreProvider: TimaSignature is unavailable
06-23 11:34:28.602  9839  9839 D ActivityThread: Added TimaKeyStore provider
06-23 11:34:28.602  3486  3504 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{aa6d376 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{aa2736c 6417:com.enhance.gameservice/u0a106}
,06-23 11:34:28.612  3486  3875 I WifiManager: isCaptivePortalException
,06-23 11:34:28.612  3486  3858 V NetworkStats: updateIfacesLocked()
,06-23 11:34:28.612  3486  3858 D NtpTrustedTime: currentTimeMillis() cache hit
06-23 11:34:28.612  3486  3858 V NetworkStats: performPollLocked(flags=0x1)
,06-23 11:34:28.612  3486  3858 D NetworkStatsRecorder: entry.iface is null
06-23 11:34:28.612  3486  3858 D NetworkStatsRecorder: entry.iface is null
06-23 11:34:28.612  3486  3858 D NetworkStatsRecorder: entry.iface is null
06-23 11:34:28.612  3486  3858 D NetworkStatsRecorder: entry.iface is null
06-23 11:34:28.612  3486  3504 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{aa6d376 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ee071b7 9614:com.sec.knox.switcher/1000}
06-23 11:34:28.612  3486  3858 V NetworkStats: performPollLocked() took 4ms
,06-23 11:34:28.612  3486  3858 D NtpTrustedTime: currentTimeMillis() cache hit
06-23 11:34:28.612  9614  9614 I usagelog: received in receiver
06-23 11:34:28.612  9614  9614 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
,06-23 11:34:28.612  9614  9614 I KnoxUsageLogPro: premStatus:2
06-23 11:34:28.612  9614  9614 I KnoxUsageLogPro: isEulaShown : false
,06-23 11:34:28.612  9614  9614 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,06-23 11:34:28.622  3486  3875 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
,06-23 11:34:28.642  3486  4435 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{a382790 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ba2d77 9839:com.samsung.android.securitylogagent/1000}
,06-23 11:34:28.642  3486  3858 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-23 11:34:28.642  3486  3858 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -37]
,06-23 11:34:28.642  3486  3858 D ConnectivityService: Not required to send intent.
06-23 11:34:28.642  3486  3858 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
06-23 11:34:28.642  3486  3847 D NtpTrustedTime: currentTimeMillis() cache hit
06-23 11:34:28.642  3486  3858 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = CONNECTING
06-23 11:34:28.642  3486  3847 D NtpTrustedTime: currentTimeMillis() cache hit
06-23 11:34:28.642  3486  3875 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
06-23 11:34:28.642  3486  3875 D WifiWatchdogStateMachine: 3Captive portal check should be processed whether SNS option is on or off.
06-23 11:34:28.642  3486  3875 D WifiWatchdogStateMachine.CaptivePortalHandler: [checkCaptivePortal] - callbackHandler=Handler (com.android.server.wifi.WifiWatchdogStateMachine$CaptivePortalHandler) {3a5183b}
06-23 11:34:28.642  3486  3875 I WifiManager: isCaptivePortalException
,06-23 11:34:28.642  9839  9839 W ResourcesManager: getTopLevelResources: /system/app/SecurityLogAgent/SecurityLogAgent.apk / 1.0 running in com.samsung.android.securitylogagent rsrc of package com.samsung.android.securitylogagent
,06-23 11:34:28.652  3486  3504 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{aa6d376 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2c05d24 9627:com.samsung.android.sm.policy/u0a135}
,06-23 11:34:28.652  3486  4257 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
06-23 11:34:28.652  9839  9839 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,06-23 11:34:28.652  9839  9839 D ResourcesManager: For user 0 new overlays fetched Null
,06-23 11:34:28.652  3486  3875 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
,06-23 11:34:28.662  9839  9839 I InjectionManager: Inside getClassLibPath caller 
,06-23 11:34:28.662  3486  3875 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
,06-23 11:34:28.662  3486  3849 D WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to CONNECTED
,06-23 11:34:28.662  9839  9839 W System  : ClassLoader referenced unknown path: /system/app/SecurityLogAgent/lib/arm64
,06-23 11:34:28.672  9839  9839 D InjectionManager: InjectionManager
,06-23 11:34:28.672  9839  9839 D InjectionManager: fillFeatureStoreMap com.samsung.android.securitylogagent
06-23 11:34:28.672  3486  3849 D SecContentProvider: insert(), uri = 2
06-23 11:34:28.672  9839  9839 I InjectionManager: Constructor com.samsung.android.securitylogagent, Feature store :{}
06-23 11:34:28.672  9839  9839 I InjectionManager: featureStore :{}
,06-23 11:34:28.672  9839  9839 D SecurityLogAgent: NetworkReceiver : Network Change Receiver Is Called
06-23 11:34:28.672  3486  3486 D WifiNotificationController: SHOW_NOTI_MESSAGE : 9, visible : false, ssid : "NG700", targetSSID : null, netId : -1, titleType : -1
06-23 11:34:28.672  3486  3858 E ConnectivityService: updateNetworkInfo()
06-23 11:34:28.672  3486  3858 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -37]
06-23 11:34:28.672  9839  9839 D SecurityLogAgent: NetworkReceiver : Wifi_state is 3
06-23 11:34:28.672  3486  3858 V NetworkStats: updateIfacesLocked()
06-23 11:34:28.672  3486  3858 D NtpTrustedTime: currentTimeMillis() cache hit
06-23 11:34:28.672  3486  3858 V NetworkStats: performPollLocked(flags=0x1)
,06-23 11:34:28.672  3486  3849 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
06-23 11:34:28.672  3486  3486 I WifiTrafficPoller: evaluateTrafficStatsPolling
,06-23 11:34:28.672  3486  3849 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
06-23 11:34:28.672  3486  3486 D WifiNative-wlan0: callSECApiVoid - ID [212]
,06-23 11:34:28.682  3486  3858 D NetworkStatsRecorder: entry.iface is null
06-23 11:34:28.682  3486  3858 D NetworkStatsRecorder: entry.iface is null
06-23 11:34:28.682  3486  3858 D NetworkStatsRecorder: entry.iface is null
06-23 11:34:28.682  3486  3858 D NetworkStatsRecorder: entry.iface is null
,06-23 11:34:28.682  3486  3858 D NtpTrustedTime: currentTimeMillis() cache hit
06-23 11:34:28.682  3486  3858 V NetworkStats: performPollLocked() took 7ms
,06-23 11:34:28.682  3486  3486 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
06-23 11:34:28.682  3486  3486 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
06-23 11:34:28.682  3486  3486 D HS20StateMachine: SSID : "NG700"
06-23 11:34:28.682  3486  3486 D HS20StateMachine: NetId : 3
06-23 11:34:28.682  3486  3486 D HS20StateMachine: checkifOSUAP  null
,06-23 11:34:28.682  3486  3486 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
06-23 11:34:28.682  3486  3856 I WifiHs20Service: Message received 5007
,06-23 11:34:28.682  3486  3486 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
,06-23 11:34:28.692  3928  4125 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,06-23 11:34:28.692  3486  4396 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,06-23 11:34:28.692  4245  4245 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,06-23 11:34:28.692  3486  4395 D SecContentProvider2: query(), uri = 15 selection = getToastGravityEnabledState
,06-23 11:34:28.702  3486  4435 D SecContentProvider2: query(), uri = 15 selection = getToastEnabledState
,06-23 11:34:28.702  3486  3567 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2e0524d u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2a680b6 9601:com.sec.android.diagmonagent/1000}
,06-23 11:34:28.702  9601  9601 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
06-23 11:34:28.702  3486  3858 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-23 11:34:28.702  3486  9790 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
06-23 11:34:28.702  3486  3858 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -37]
06-23 11:34:28.702  3486  9790 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: Connected
06-23 11:34:28.702  3486  9790 D NetworkMonitor: registerReceiver Captive portal receiver
06-23 11:34:28.702  9601  9601 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
06-23 11:34:28.702  9601  9601 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
,06-23 11:34:28.702  3486  3858 D ConnectivityService: scheduleUnvalidatedPrompt 503
,06-23 11:34:28.702  3486  3970 D SecContentProvider2: query(), uri = 15 selection = getToastShowPackageNameState
06-23 11:34:28.702  3486  3858 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 503]
06-23 11:34:28.702  3486  3847 D NtpTrustedTime: currentTimeMillis() cache hit
06-23 11:34:28.702  3486  3858 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
06-23 11:34:28.702  3486  3847 D NtpTrustedTime: currentTimeMillis() cache hit
06-23 11:34:28.702  3486  3858 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -37]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
06-23 11:34:28.702  3486  9790 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,06-23 11:34:28.702  9601  9601 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 android.content.ContextWrapper.sendBroadcast:410 android.content.ContextWrapper.sendBroadcast:410 com.sec.android.diagmonagent.DiagMonConnectivityChangeReciever.onReceive:19 android.app.ActivityThread.handleReceiver:3635 
06-23 11:34:28.702  3486  9790 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: Validated
,06-23 11:34:28.702  3486  3849 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
06-23 11:34:28.702  3486  3849 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,06-23 11:34:28.712  3486  3858 D ConnectivityService:   checking if request is: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: true
,06-23 11:34:28.712  3486  3858 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,06-23 11:34:28.712  4245  4618 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,06-23 11:34:28.712  3486  3505 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2e0524d u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{aa2736c 6417:com.enhance.gameservice/u0a106}
06-23 11:34:28.712  4245  4618 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
06-23 11:34:28.712  3486  3858 D ConnectivityService: currentScore = 0, newScore = 20
06-23 11:34:28.712  3486  3858 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
06-23 11:34:28.722  3486  3858 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 503]
06-23 11:34:28.722  3486  3884 D Ethernet: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-23 11:34:28.722  3486  3858 D ConnectivityService:    accepting network in place of null
06-23 11:34:28.722  3486  3884 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
06-23 11:34:28.722  3486  3858 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-23 11:34:28.722  3486  3884 D Ethernet: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
06-23 11:34:28.722  3486  3884 D Ethernet: evalRequest
,06-23 11:34:28.722  3486  3884 D Ethernet:   done
06-23 11:34:28.722  3486  3848 D WIFI_P2P: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-23 11:34:28.722  3486  3848 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,06-23 11:34:28.722  3486  3848 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
06-23 11:34:28.722  3486  3848 D WIFI_P2P: evalRequest
06-23 11:34:28.722  3486  3848 D WIFI_P2P:   done
,06-23 11:34:28.732  3486  3849 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-23 11:34:28.732  3486  3849 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-23 11:34:28.732  3486  3849 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
06-23 11:34:28.732  3486  3849 D WIFI    : evalRequest
06-23 11:34:28.732  3486  3849 D WIFI    :   done
06-23 11:34:28.732  3486  3849 D WIFI_UT : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-23 11:34:28.732  3486  3849 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-23 11:34:28.732  3486  3849 D WIFI_UT : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
06-23 11:34:28.732  3486  3849 D WIFI_UT : evalRequest
06-23 11:34:28.732  3486  3849 D WIFI_UT :   done
06-23 11:34:28.732  3486  3849 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-23 11:34:28.732  3486  3849 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-23 11:34:28.732  3486  3849 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
06-23 11:34:28.732  3486  3849 D WIFI    : evalRequest
06-23 11:34:28.732  3486  3849 D WIFI    :   done
,06-23 11:34:28.732  9839  9839 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,06-23 11:34:28.732  9839  9839 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
06-23 11:34:28.732  9839  9839 D SecurityLogAgent: StateMachine : Current State = 1
,06-23 11:34:28.742  3486  3858 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,06-23 11:34:28.742  3486  3858 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,06-23 11:34:28.752  3928  4125 D ViewRootImpl: #1 mView = android.widget.LinearLayout{d2447cb V.E...... ......I. 0,0-0,0 #102039c android:id/toast_layout_root}
,06-23 11:34:28.752  3486  3969 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2e0524d u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ee071b7 9614:com.sec.knox.switcher/1000}
06-23 11:34:28.752  9614  9614 I usagelog: received in receiver
,06-23 11:34:28.752  9614  9614 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
06-23 11:34:28.752  9614  9614 I KnoxUsageLogPro: premStatus:2
,06-23 11:34:28.752  9614  9614 I KnoxUsageLogPro: isEulaShown : false
06-23 11:34:28.752  9614  9614 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,06-23 11:34:28.752  3486  3858 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,06-23 11:34:28.762  3486  3505 D ISSUE_DEBUG: InputChannelName : aef57c Toast
,06-23 11:34:28.762  3486  3505 V MARsPolicyManager: handelAlertToastWindowStarted pkgName = com.android.systemui
,06-23 11:34:28.762  3486  4257 D ActivityManager:  getDeferredInfo final delay 300
,06-23 11:34:28.772  3006  3006 I SurfaceFlinger: id=20 createSurf (1x1),1 flag=4, Uoast
,06-23 11:34:28.772  3928  3928 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 272
,06-23 11:34:28.772  3486  3858 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,06-23 11:34:28.782  3486  4396 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2e0524d u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2c05d24 9627:com.samsung.android.sm.policy/u0a135}
,06-23 11:34:28.792  3486  3858 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,06-23 11:34:28.802  3486  3969 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{bc35e5a u0 com.sec.android.diagmonagent.intent.NETWORK_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2a680b6 9601:com.sec.android.diagmonagent/1000}
,06-23 11:34:28.812  9601  9601 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: com.sec.android.diagmonagent.intent.NETWORK_CHANGED
,06-23 11:34:28.812  9601  9601 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
06-23 11:34:28.812  9601  9601 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(67/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,06-23 11:34:28.812  3486  4422 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3486
,06-23 11:34:28.822  3486  3858 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,06-23 11:34:28.822  3486  3858 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -37]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,06-23 11:34:28.832  3928  4121 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1033x201]-format:1
,06-23 11:34:28.832  3928  4125 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,06-23 11:34:28.842  3928  4125 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,06-23 11:34:28.842  3486  4285 V WindowStateAnimator: Finishing drawing window Window{aef57c u0 d0 Toast}: mDrawState=DRAW_PENDING
,06-23 11:34:28.852  3151  3629 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,06-23 11:34:28.852  3006  3006 D libEGL  : eglInitialize EGLDisplay = 0x7ffb1ed5e8
,06-23 11:34:28.882  3151  3629 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,06-23 11:34:28.882  3486  3858 D ConnectivityService: 503 network ip type : v4
,06-23 11:34:28.882  3486  3858 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-23 11:34:28.882  3486  3858 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-23 11:34:28.892  3486  3858 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-23 11:34:28.892  3486  3858 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-23 11:34:28.892  3486  3858 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=5, legacyType=-1, [] ]
,06-23 11:34:28.892  3486  3589 D EntConnectivity: Not allowed due to - mEnabled false
06-23 11:34:28.892  3486  3858 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -37]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} } for legacy network type 1
06-23 11:34:28.892  3486  3858 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
06-23 11:34:28.892  3486  3858 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,06-23 11:34:28.902  3486  4433 D ConnectivityService: getVpnConfig > userId : 0
,06-23 11:34:28.902  3486  3858 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -37]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
06-23 11:34:28.902  3486  3858 D ConnectivityService: unneeded: NetworkRequestInfo for = Request from uid/pid:1000/3486 for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-23 11:34:28.902  3486  3858 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
06-23 11:34:28.902  3486  3858 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
06-23 11:34:28.902  3486  3858 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-23 11:34:28.902  3486  3858 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-23 11:34:28.902  3486  3858 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-23 11:34:28.902  3486  3858 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
,06-23 11:34:28.902  3486  3858 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=5, legacyType=-1, [] ]
,06-23 11:34:28.902  3486  3858 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-23 11:34:28.902  3486  3589 D EntConnectivity: Not allowed due to - mEnabled false
06-23 11:34:28.902  3486  3858 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-23 11:34:28.912  3486  3858 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-23 11:34:28.912  3486  3858 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-23 11:34:28.912  3486  3858 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-23 11:34:28.912  3486  3858 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-23 11:34:28.912  3486  3486 D Tethering: Tethering got CONNECTIVITY_ACTION
,06-23 11:34:28.912  3486  3858 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,06-23 11:34:28.912  3486  3589 D Tethering: MasterInitialState.processMessage what=3
06-23 11:34:28.912  3486  3858 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] validation  passed
06-23 11:34:28.912  3486  3858 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -37], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -37]
,06-23 11:34:28.912  3486  3858 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
06-23 11:34:28.912  3486  3486 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
06-23 11:34:28.912  3486  3486 I CLocInfoService: ['16.5] External Intent Received android.net.conn.CONNECTIVITY_CHANGE
06-23 11:34:28.912  3486  3486 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,06-23 11:34:28.912  3486  3860 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
06-23 11:34:28.912  3486  3486 I CLocInfoService: CLocinfo wifi true 
06-23 11:34:28.912  3486  3858 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -37]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,06-23 11:34:28.912  3928  4125 D NetworkController: onReceive: intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,06-23 11:34:28.912  4245  4256 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
06-23 11:34:28.912  4245  4256 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,06-23 11:34:28.912  3486  3564 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,06-23 11:34:28.912  3486  3860 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
06-23 11:34:28.912  3486  3564 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
06-23 11:34:28.912  3486  3564 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
06-23 11:34:28.922  3486  4188 V AlarmManager:  remove PendingIntent] PendingIntent{c6556d1: PendingIntentRecord{e3fd536 android broadcastIntent}}
,06-23 11:34:28.932  3486  3486 V MARsPolicyManager: DataConnection: true
,06-23 11:34:28.932  3486  3858 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
,06-23 11:34:28.932  4726  4726 D SamsungIME: EngineType = SWIFTKEY
,06-23 11:34:28.942  4857  4965 D CellLocationSupport: onReceive ACTION = android.net.conn.CONNECTIVITY_CHANGE
06-23 11:34:28.942  4857  4965 I CellLocationSupport: onCellLocationChanged
,06-23 11:34:28.942  4726  4726 D SamsungIME: mNetworkChangeReceiver isWLANConnected : true
,06-23 11:34:28.952  4857  4857 D PdnController: CONNECTIVITY_ACTION: networkType 1 isConnected true
06-23 11:34:28.952  4857  4857 D PdnController: isSuspended [false] networktype [1]
06-23 11:34:28.952  4857  4857 D PdnController: Updated Interface [wlan0] For Network [1]
,06-23 11:34:28.952  3486  3505 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,06-23 11:34:28.962  4857  4857 D PdnController: isPdnUp  [true] networktype [1]
06-23 11:34:28.962  4857  4857 D PdnController: Notify Result to LocalIP Registrants! : networkType [1] isConnected [true] 
,06-23 11:34:28.962  3486  3847 D NtpTrustedTime: currentTimeMillis() cache hit
06-23 11:34:28.962  3486  3847 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-23 11:34:28.962  3486  3847 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -37]
,06-23 11:34:28.962  3486  3847 D NtpTrustedTime: currentTimeMillis() cache hit
06-23 11:34:28.962  3486  3847 D NtpTrustedTime: currentTimeMillis() cache hit
06-23 11:34:28.962  3486  3847 D NtpTrustedTime: currentTimeMillis() cache hit
06-23 11:34:28.962  3486  3847 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
,06-23 11:34:28.972  3486  3879 D WifiWatchdogStateMachine.CaptivePortalHandler: start check captive portal 
,06-23 11:34:28.972  5371  5371 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@e945f8e and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,06-23 11:34:28.972  4857  4965 I CellLocationSupport: Block to update PANI information in non VoWIFI
,06-23 11:34:28.972  3486  3858 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
06-23 11:34:28.972  4857  4965 D SlickSSConfigHandler: EVENT_LOCAL_IP_CHANGED
,06-23 11:34:28.972  3486  4435 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-23 11:34:28.982  4857  4965 D PdnController: isIfaceDisconnected result [true] networkType [0] interfaceName [null] 
,06-23 11:34:28.982  5371  5371 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
06-23 11:34:28.982  4857  4965 D PdnController: isPdnUp  [false] networktype [0]
06-23 11:34:28.982  4857  4965 D SlickSSConfigHandler: handleNetworkStateChange: check isDefaultPDNConnected[false], mReadyForDocFetch[false
,06-23 11:34:28.982  3486  3504 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,06-23 11:34:28.982  6764  6764 I FOTA_AGENT: [lIlIIlIlIlIllllllIII(91/llllIIIllIlIIIIllllI)] WiFi Network is connected
,06-23 11:34:28.992  4857  4965 D RegistrationManager: handleMessage(): 5
,06-23 11:34:28.992  3486  4395 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-23 11:34:28.992  4857  4965 D PdnController: isIfaceDisconnected result [true] networkType [11] interfaceName [null] 
06-23 11:34:28.992  4857  4965 D PdnController: isPdnUp  [false] networktype [11]
06-23 11:34:28.992  4857  4965 D RegistrationManager: setEPDGIPSecConnected [false]
06-23 11:34:28.992  4857  4965 D RegistrationManager: notifyNetworkState : NetworkType [1] IsConnected [true] IPAddresses [[/192.168.1.135]] DNSAddresses [[/192.168.1.1]] 
06-23 11:34:28.992  4857  4965 D RegistrationManager: isEPDGAvailable [false]
06-23 11:34:28.992  4857  4965 D RegistrationManager: setWifiPreparedOnAPM [true]
,06-23 11:34:29.002  9077  9077 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 com.samsung.SMT.SamsungTTSService.g:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.c.onReceive:-1 
,06-23 11:34:29.002  3486  3504 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,06-23 11:34:29.002  4175  4175 D FusedRequestManager: manageLocationRequest, new passive request from com.samsung.voiceserviceplatform with ab33997 , interval = 1800000 through LocationManagerService
,06-23 11:34:29.012  3486  3858 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,06-23 11:34:29.022  3486  4186 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-23 11:34:29.022  3151  3625 D EnterpriseController: netId is 0
06-23 11:34:29.022  3151  3625 D Netd    : getNetworkForDns: using netid 503 for uid 10001
,06-23 11:34:29.032  4857  4965 D TranslatorCollection: translateToNwkSvcType: networkType XAN_NWK_TYPE_WLAN
06-23 11:34:29.032  4857  4965 D RegistrationManager: getNetworkType [0]
06-23 11:34:29.032  3486  3858 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
06-23 11:34:29.032  4857  4965 D CoreStackAdaptor2: notifyNetworkState() [1] isConnected [true] nwkSvcType  [XAN_NWK_TYPE_WLAN] nwkInfoType [XAN_SVC_NETWORK_SVCTYPE_WIFI] dedicated   [NONE] 
06-23 11:34:29.032  4857  4965 D CellLocationSupport: Siso Stack not called RegisterAN yet on XAN_NWK_TYPE_WLAN
,06-23 11:34:29.032  4857  4965 D TranslatorCollection: translateToNwkSvcType: networkType XAN_NWK_TYPE_WLAN
06-23 11:34:29.032  4374  4374 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
06-23 11:34:29.032  4857  4965 D CoreStackAdaptor2: ipList Not Null[/192.168.1.135]
06-23 11:34:29.032  4857  4965 D RegistrationManager: tryRegister(CONNECTIVITY_STATUS_CHANGE)
06-23 11:34:29.032  4857  4965 D RegistrationManager: isPreconditionProperToGoOn
06-23 11:34:29.032  4857  4965 D RegistrationManager: isDeviceShutdown [false]
06-23 11:34:29.032  4857  4965 D RegistrationManager: isStackShuttingDownForAllPDNs [false]
06-23 11:34:29.032  4857  4965 D RegistrationManager: isDmVoLTEUpdated [false]
06-23 11:34:29.032  4857  4965 D RegistrationManager: tryRegister : Abort Reason [IMS feature disabled]
06-23 11:34:29.032  4857  4965 D RegistrationManager: tryRegister : Not all preconditions are met!
,06-23 11:34:29.032  9374  9374 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,06-23 11:34:29.032  3486  3878 D WifiWatchdogStateMachine: response code : 204
,06-23 11:34:29.042  3486  3879 D WifiWatchdogStateMachine.CaptivePortalHandler: result = 0, mCaptivePortalCheckMode = 11, mCouldNotIdentifyCaptivePortalState = true
,06-23 11:34:29.042  9674  9685 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(86/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
,06-23 11:34:29.042  9674  9685 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(86/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
,06-23 11:34:29.052  9674  9685 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(43/llIIIIlllllIIllIIllI)] already Eula Agree
,06-23 11:34:29.062  4827  4827 E audit   : type=1400 msg=audit(1498210469.062:278): avc:  denied  { ioctl } for  pid=7043 comm="ChromiumNet" path="socket:[44054]" dev="sockfs" ino=44054 ioctlcmd=8b1b scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=udp_socket permissive=0
06-23 11:34:29.062  4827  4827 E audit   :  SEPF_SECMOBILE_6.0.1_0031
06-23 11:34:29.062  4827  4827 E audit   : type=1300 msg=audit(1498210469.062:278): arch=c00000b7 syscall=29 success=no exit=-13 a0=18 a1=8b1b a2=7f71d83cc8 a3=7f71d83c90 items=0 ppid=3175 pid=7043 auid=4294967295 uid=10068 gid=10068 euid=10068 suid=10068 fsuid=10068 egid=10068 sgid=10068 fsgid=10068 tty=(none) ses=4294967295 comm="ChromiumNet" exe="/system/bin/app_process64" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
06-23 11:34:29.062  4827  4827 E audit   : type=1327 msg=audit(1498210469.062:278): proctitle="com.google.android.googlequicksearchbox:search"
06-23 11:34:29.062  4827  4827 E audit   : type=1320 msg=audit(1498210469.062:278): 
06-23 11:34:29.062  4827  4827 E audit   : type=1400 msg=audit(1498210469.062:279): avc:  denied  { ioctl } for  pid=7043 comm="ChromiumNet" path="socket:[44055]" dev="sockfs" ino=44055 ioctlcmd=8b1b scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=udp_socket permissive=0
06-23 11:34:29.062  4827  4827 E audit   :  SEPF_SECMOBILE_6.0.1_0031
06-23 11:34:29.062  4827  4827 E audit   : type=1300 msg=audit(1498210469.062:279): arch=c00000b7 syscall=29 success=no exit=-13 a0=18 a1=8b1b a2=7f71d83cc8 a3=7f71d83c90 items=0 ppid=3175 pid=7043 auid=4294967295 uid=10068 gid=10068 euid=10068 suid=10068 fsuid=10068 egid=10068 sgid=10068 fsgid=10068 tty=(none) ses=4294967295 comm="ChromiumNet" exe="/system/bin/app_process64" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
06-23 11:34:29.062  4827  4827 E audit   : type=1327 msg=audit(1498210469.062:279): proctitle="com.google.android.googlequicksearchbox:search"
06-23 11:34:29.062  4827  4827 E audit   : type=1320 msg=audit(1498210469.062:279): 
,06-23 11:34:29.072  9674  9684 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(86/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
,06-23 11:34:29.072  9674  9684 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(86/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
06-23 11:34:29.072  9674  9684 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(43/llIIIIlllllIIllIIllI)] already Eula Agree
,06-23 11:34:29.082  9374  9374 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,06-23 11:34:29.082  3486  3858 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,06-23 11:34:29.092  4245  4606 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,06-23 11:34:29.092  4245  4606 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,06-23 11:34:29.102  3486  3858 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,06-23 11:34:29.102  9374  9374 D BluetoothAdapter: STATE_ON
,06-23 11:34:29.102  9867  9867 E Zygote  : v2
06-23 11:34:29.102  9867  9867 I libpersona: KNOX_SDCARD checking this for 1000
06-23 11:34:29.102  9867  9867 I libpersona: KNOX_SDCARD not a persona
,06-23 11:34:29.102  9867  9867 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,06-23 11:34:29.112  9867  9867 E Zygote  : accessInfo : 0
,06-23 11:34:29.112  3486  3975 I ActivityManager: Start proc 9867:com.sec.android.soagent/1000 for content provider com.sec.android.soagent/.log.MasterLogProvider
,06-23 11:34:29.112  3486  3564 D TelephonyManager: getDataEnabled: retVal=true
,06-23 11:34:29.112  9374  9374 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-23 11:34:29.112  9374  9374 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-23 11:34:29.112  9374  9374 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
06-23 11:34:29.112  9374  9374 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-23 11:34:29.112  9374  9374 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-23 11:34:29.112  9374  9374 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
06-23 11:34:29.112  9374  9374 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
06-23 11:34:29.112  9374  9374 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
06-23 11:34:29.112  9374  9374 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,06-23 11:34:29.112  3486  3858 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,06-23 11:34:29.112  3486  3858 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -37]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
06-23 11:34:29.112  3486  3858 D ConnectivityService: unneeded: NetworkRequestInfo for = Request from uid/pid:1000/3486 for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-23 11:34:29.112  3486  3858 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
06-23 11:34:29.112  4245  4618 D TelephonyProvider: query: url=content://telephony/carriers/preferapn, projectionIn=[Ljava.lang.String;@8c5bd5a, selection=nullselectionArgs=null, sort=name ASC
06-23 11:34:29.112  3486  3858 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 503]
06-23 11:34:29.112  3486  3858 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-23 11:34:29.112  3486  3858 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-23 11:34:29.112  3486  3858 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-23 11:34:29.112  3486  3858 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
06-23 11:34:29.112  3486  3858 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=5, legacyType=-1, [] ]
06-23 11:34:29.122  4245  4618 D TelephonyProvider: query: match = 5
06-23 11:34:29.122  4245  4618 D TelephonyProvider: getPreferredApnId(subId = 2147483643),return -1
06-23 11:34:29.122  4245  4618 D TelephonyProvider: query: selection modified to edited!=2 and edited!=3 and edited!=5 and edited!=6
,06-23 11:34:29.122  3486  3858 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-23 11:34:29.122  3486  3858 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-23 11:34:29.122  9374  9374 D BluetoothAdapter: STATE_ON
06-23 11:34:29.122  3486  3858 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-23 11:34:29.122  3486  3858 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-23 11:34:29.122  3486  3858 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-23 11:34:29.122  3486  3858 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-23 11:34:29.132  3486  3858 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-23 11:34:29.132  3486  3884 D Ethernet: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-23 11:34:29.132  3486  3849 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-23 11:34:29.132  3486  3849 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-23 11:34:29.132  3486  3884 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
06-23 11:34:29.132  3486  3849 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
06-23 11:34:29.132  3486  3884 D Ethernet: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
06-23 11:34:29.132  3486  3849 D WIFI    : evalRequest
06-23 11:34:29.132  3486  3884 D Ethernet: evalRequest
06-23 11:34:29.132  3486  3884 D Ethernet:   done
06-23 11:34:29.132  3486  3849 D WIFI    :   done
06-23 11:34:29.132  3486  3849 D WIFI_UT : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-23 11:34:29.132  3486  3849 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-23 11:34:29.132  3486  3849 D WIFI_UT : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
06-23 11:34:29.132  3486  3849 D WIFI_UT : evalRequest
06-23 11:34:29.132  3486  3849 D WIFI_UT :   done
06-23 11:34:29.132  3486  3848 D WIFI_P2P: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-23 11:34:29.132  3486  3848 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-23 11:34:29.132  3486  3848 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
06-23 11:34:29.132  3486  3848 D WIFI_P2P: evalRequest
06-23 11:34:29.132  3486  3848 D WIFI_P2P:   done
,06-23 11:34:29.132  3486  3849 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-23 11:34:29.132  3486  3858 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
06-23 11:34:29.132  3486  3849 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-23 11:34:29.132  3486  3849 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
06-23 11:34:29.132  3486  3849 D WIFI    : evalRequest
06-23 11:34:29.132  3486  3849 D WIFI    :   done
,06-23 11:34:29.132  9374  9374 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,06-23 11:34:29.132  3486  3849 D WifiNetworkAgent: NetworkAgent: CMD_REPORT_NETWORK_STATUS(VALID)
06-23 11:34:29.132  3486  3849 D WifiNetworkAgent: NetworkAgent: CMD_REPORT_NETWORK_STATUS(1)
,06-23 11:34:29.142  3486  3849 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
06-23 11:34:29.142  3486  3849 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
06-23 11:34:29.142  3486  3849 D WifiStateMachine: sendBroadcastForCaptivePortalNotLoginIcon : false
06-23 11:34:29.142  3486  3849 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
06-23 11:34:29.142  3486  3849 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
,06-23 11:34:29.142  3928  4125 D NetworkController: onReceive: intent=Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,06-23 11:34:29.152  3928  4125 D NetworkController: onReceive: intent=Intent { act=com.samsung.intent.action.WIFI_CAPTIVE_NOT_LOGIN flg=0x10 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
06-23 11:34:29.152  3928  4125 D NetworkController.WifiSignalController: updateWifiState : mCurrentState.wifiCaptiveNotLogin = false
,06-23 11:34:29.152  3486  3564 E GpsLocationProvider: No APN found to select.
,06-23 11:34:29.152  9867  9867 D TimaKeyStoreProvider: TimaSignature is unavailable
06-23 11:34:29.152  9867  9867 D ActivityThread: Added TimaKeyStore provider
,06-23 11:34:29.162  3486  3564 D libgps  : agps_ril_update_network_state: Waiting for IPC connection...
,06-23 11:34:29.182  9867  9867 W ResourcesManager: getTopLevelResources: /system/priv-app/SOAgent/SOAgent.apk / 1.0 running in com.sec.android.soagent rsrc of package com.sec.android.soagent
,06-23 11:34:29.182  3486  4257 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,06-23 11:34:29.182  9867  9867 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,06-23 11:34:29.182  9867  9867 D ResourcesManager: For user 0 new overlays fetched Null
,06-23 11:34:29.192  9867  9867 I InjectionManager: Inside getClassLibPath caller 
,06-23 11:34:29.202  9867  9867 W System  : ClassLoader referenced unknown path: /system/priv-app/SOAgent/lib/arm64
,06-23 11:34:29.222  9867  9867 D InjectionManager: InjectionManager
06-23 11:34:29.222  9867  9867 D InjectionManager: fillFeatureStoreMap com.sec.android.soagent
,06-23 11:34:29.222  9867  9867 I InjectionManager: Constructor com.sec.android.soagent, Feature store :{}
06-23 11:34:29.222  9867  9867 I InjectionManager: featureStore :{}
,06-23 11:34:29.272  3486  3970 I ActivityManager: Killing 9177:com.google.android.apps.docs/u0a93 (adj 15): DHA:empty #33
,06-23 11:34:29.272  3486  3970 I ActivityManager: Killing 9165:com.samsung.android.bbc.bbcagent/1000 (adj 15): DHA:empty #33
,06-23 11:34:29.282  3486  3970 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e50180 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a8d88eb 9374:com.thaliproject.thalitest/u0a74}
,06-23 11:34:29.282  3486  4257 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:29.282  3486  4257 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
06-23 11:34:29.282  3486  4257 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:29.282  3486  4257 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:29.282  3486  4257 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:29.282  3486  4257 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:29.282  3486  4257 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:29.282  3486  4257 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:29.282  3486  4257 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:29.282  3486  4257 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:29.282  3486  4257 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:29.282  3486  4257 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:29.282  3486  4257 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:29.282  3486  4257 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-23 11:34:29.282  3486  4257 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-23 11:34:29.302  3486  4396 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e50180 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8b44752 3486:system/1000}
,06-23 11:34:29.322  3486  3975 D ActivityManager: cleanUpApplicationRecord -- 9177
,06-23 11:34:29.322  3486  3975 D ActivityManager: isAutoRunBlockedApp:: com.google.android.apps.docs, Auto Run ON
,06-23 11:34:29.322  3486  6077 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-23 11:34:29.332  3486  4433 D ActivityManager: cleanUpApplicationRecord -- 9165
,06-23 11:34:29.332  3486  4433 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.bbc.bbcagent, Auto Run ON
,06-23 11:34:29.342  3486  3486 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e50180 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{96cd387 4551:com.google.android.gms/u0a19}
,06-23 11:34:29.352  4551  4551 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,06-23 11:34:29.352  4551  5546 I iu.UploadsManager: num queued entries: 0
,06-23 11:34:29.352  4551  5546 I iu.UploadsManager: num updated entries: 0
,06-23 11:34:29.352  4551  5546 I iu.SyncManager: NEXT; no task
,06-23 11:34:29.362  3486  4379 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e50180 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{96cd387 4551:com.google.android.gms/u0a19}
,06-23 11:34:29.372  3486  4379 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e50180 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ff226b8 4273:com.google.android.gms.persistent/u0a19}
,06-23 11:34:29.392  3486  3505 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e50180 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7ef879a 9674:com.policydm/1000}
,06-23 11:34:29.392  3151  3625 D EnterpriseController: netId is 0
06-23 11:34:29.392  3151  3625 D Netd    : getNetworkForDns: using netid 503 for uid 10019
,06-23 11:34:29.402  9674  9674 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(574/IlIIIllllIIlIIIIIlII)] Initiated Type: 0
,06-23 11:34:29.412  9674  9674 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,06-23 11:34:29.412  9674  9674 I DBG_POLICYDM: [com.policydm.XDMService(585/llIlIllllllllllllllI)] get NotibarState : 0
,06-23 11:34:29.482  3486  3567 D ActivityManager:  getDeferredInfo final delay 660
,06-23 11:34:29.882  3486  3858 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,06-23 11:34:30.142  3486  3567 D ActivityManager:  getDeferredInfo final delay 360
,06-23 11:34:30.172  9374  9439 I io.jxcore.node.IncomingSocketThreadTest: testRun
06-23 11:34:30.172  9374  9439 I !!      :  finally closed
,06-23 11:34:30.172  9374  9439 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
,06-23 11:34:30.172  9374  9439 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
06-23 11:34:30.172  3486  3564 D libgps  : agps_ril_update_network_state: Waiting for IPC connection - timeout
06-23 11:34:30.172  3486  3564 E libgps  : LIBGPS: Cannot communicate (write) with a GPSD
,06-23 11:34:30.172  3486  3564 E libgps  : IPC Communication Error, ../../../../tmp/14982990_270314/allPartners/os/android/gps_interface/gpsi_client/GpsiClient.cpp:1710 agps_ril_update_network_state
06-23 11:34:30.172  3486  3564 D libgps  : agps_ril_update_network_availability: Waiting for IPC connection...
06-23 11:34:30.172  9374  9439 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
06-23 11:34:30.172  9374  9439 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,06-23 11:34:30.182  9374  9439 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,06-23 11:34:30.182  9374  9439 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
,06-23 11:34:30.182  9374  9439 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.thaliproject.thalitest.MainActivity@ef04068 Bundle[{}]
,06-23 11:34:30.182  9374  9439 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
06-23 11:34:30.182  9374  9439 I io.jxcore.node.LifeCycleMonitor: start: OK
06-23 11:34:30.182  9374  9439 I io.jxcore.node.LifeCycleMonitor: stop: OK
,06-23 11:34:30.192  9374  9439 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
,06-23 11:34:30.192  9374  9439 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,06-23 11:34:30.192  9374  9439 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
06-23 11:34:30.192  9374  9439 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,06-23 11:34:30.192  9374  9439 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
,06-23 11:34:30.192  9374  9439 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,06-23 11:34:30.192  9374  9439 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
,06-23 11:34:30.192  9374  9439 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,06-23 11:34:30.202  9374  9439 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
,06-23 11:34:30.202  9374  9439 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,06-23 11:34:30.202  9374  9439 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
,06-23 11:34:30.202  9374  9439 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
,06-23 11:34:30.202  9374  9439 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
,06-23 11:34:30.202  9374  9439 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
,06-23 11:34:30.212  9374  9439 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testRun
,06-23 11:34:30.212  9374  9883 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,06-23 11:34:30.212  9374  9883 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,06-23 11:34:30.222  3151  3625 D EnterpriseController: netId is 0
,06-23 11:34:30.222  3151  3625 D Netd    : getNetworkForDns: using netid 503 for uid 10074
,06-23 11:34:30.222  9374  9885 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,06-23 11:34:30.222  9374  9885 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
06-23 11:34:30.222  9374  9885 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
06-23 11:34:30.222  9374  9885 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
06-23 11:34:30.222  9374  9883 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
06-23 11:34:30.222  9374  9883 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
06-23 11:34:30.222  9374  9883 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,06-23 11:34:30.222  9374  9885 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
06-23 11:34:30.222  9374  9883 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,06-23 11:34:30.222  9374  9889 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 247, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
06-23 11:34:30.222  9374  9889 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
06-23 11:34:30.222  9374  9889 D io.jxcore.node.StreamCopyingThread:  id: 78
,06-23 11:34:30.232  9374  9883 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,06-23 11:34:30.232  9374  9887 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 245, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
06-23 11:34:30.232  9374  9887 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
06-23 11:34:30.232  9374  9887 D io.jxcore.node.StreamCopyingThread:  id: 77
,06-23 11:34:30.232  9374  9888 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 246, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
06-23 11:34:30.232  9374  9888 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
06-23 11:34:30.232  9374  9888 D io.jxcore.node.StreamCopyingThread:  id: 77
,06-23 11:34:30.232  9374  9890 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 248, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
06-23 11:34:30.232  9374  9890 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
06-23 11:34:30.232  9374  9890 D io.jxcore.node.StreamCopyingThread:  id: 78
,06-23 11:34:30.232  9374  9890 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 248, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
06-23 11:34:30.232  9374  9890 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
06-23 11:34:30.232  9374  9890 D io.jxcore.node.StreamCopyingThread:  id: 78
06-23 11:34:30.232  9374  9890 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
06-23 11:34:30.232  9374  9890 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
06-23 11:34:30.232  9374  9890 D io.jxcore.node.StreamCopyingThread:  id: 78
06-23 11:34:30.232  9374  9890 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
06-23 11:34:30.232  9374  9890 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
06-23 11:34:30.232  9374  9890 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,06-23 11:34:30.232  9374  9890 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
06-23 11:34:30.232  9374  9890 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
06-23 11:34:30.232  9374  9890 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
06-23 11:34:30.232  9374  9890 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 248, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
06-23 11:34:30.232  9374  9890 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
06-23 11:34:30.232  9374  9890 D io.jxcore.node.StreamCopyingThread:  id: 78 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,06-23 11:34:30.242  9374  9888 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 246, thread name: IncomingSocketThread/Receiver): sendto failed: ECONNRESET (Connection reset by peer)
,06-23 11:34:30.242  9374  9887 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 245, thread name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
06-23 11:34:30.242  9374  9887 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
06-23 11:34:30.242  9374  9887 D io.jxcore.node.StreamCopyingThread:  id: 77
06-23 11:34:30.242  9374  9888 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 246, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
06-23 11:34:30.242  9374  9888 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
06-23 11:34:30.242  9374  9888 D io.jxcore.node.StreamCopyingThread:  id: 77 .During the lifetime of the thread the total number of bytes read was 249856 and the total number of bytes written 245760
06-23 11:34:30.242  9374  9887 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
06-23 11:34:30.242  9374  9887 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
06-23 11:34:30.242  9374  9887 D io.jxcore.node.StreamCopyingThread:  id: 77
06-23 11:34:30.242  9374  9887 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
06-23 11:34:30.242  9374  9887 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
06-23 11:34:30.242  9374  9887 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,06-23 11:34:30.242  9374  9888 E io.jxcore.node.IncomingSocketThread: The receiving thread failed with error "Failed to write to the output stream: sendto failed: ECONNRESET (Connection reset by peer)", this is likely due to peer having disconnected
06-23 11:34:30.242  9374  9889 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 247, thread name: OutgoingSocketThread/Sender): Socket closed
06-23 11:34:30.242  9374  9887 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
06-23 11:34:30.242  9374  9888 D io.jxcore.node.StreamCopyingThread: number of bytes read = 4096
06-23 11:34:30.242  9374  9887 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
06-23 11:34:30.242  9374  9887 I io.jxcore.node.IncomingSocketThread: The sending thread is done
06-23 11:34:30.242  9374  9888 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 246, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
06-23 11:34:30.242  9374  9888 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
06-23 11:34:30.242  9374  9888 D io.jxcore.node.StreamCopyingThread:  id: 77 .During the lifetime of the thread the total number of bytes read was 249856 and the total number of bytes written 245760
,06-23 11:34:30.242  9374  9889 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 247, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
06-23 11:34:30.242  9374  9889 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
06-23 11:34:30.242  9374  9889 D io.jxcore.node.StreamCopyingThread:  id: 78 .During the lifetime of the thread the total number of bytes read was 4096 and the total number of bytes written 4096
06-23 11:34:30.242  9374  9887 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 245, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
06-23 11:34:30.242  9374  9887 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
06-23 11:34:30.242  9374  9887 D io.jxcore.node.StreamCopyingThread:  id: 77 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
06-23 11:34:30.242  9374  9889 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
06-23 11:34:30.242  9374  9889 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,06-23 11:34:30.242  9374  9889 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 247, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
06-23 11:34:30.242  9374  9889 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
06-23 11:34:30.242  9374  9889 D io.jxcore.node.StreamCopyingThread:  id: 78 .During the lifetime of the thread the total number of bytes read was 4096 and the total number of bytes written 4096
,06-23 11:34:30.522  3486  3807 V AlarmManager: Expired Alarm result :4
,06-23 11:34:30.552  3486  3567 D ActivityManager:  getDeferredInfo final delay 0
,06-23 11:34:30.562  3486  3567 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{e50180 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7ef879a 9674:com.policydm/1000}
,06-23 11:34:30.562  9674  9674 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(51/onReceive)] RegistrationReceiver onReceive! action = android.net.conn.CONNECTIVITY_CHANGE
06-23 11:34:30.562  3486  3847 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: true, uidstate: 6, mProxSensorScreenOff: false
06-23 11:34:30.562  3486  3847 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: true, uidstate: 6, mProxSensorScreenOff: false
,06-23 11:34:30.592  9674  9674 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(87/llllIIIllIlIIIIllllI)] device register flag at setting DB : true
,06-23 11:34:30.602  9674  9674 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(96/onReceive)] Already device registered...
,06-23 11:34:30.612  9674  9674 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(87/llllIIIllIlIIIIllllI)] device register flag at setting DB : true
,06-23 11:34:30.622  9674  9674 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(342/lllIlIlIIIllIIlIllIl)] OMC not Supported model
,06-23 11:34:30.622  9674  9674 I DBG_POLICYDM: [IIIIlllIIIlIlllllIll(111/llIlIIIIlIIIIIlIlIII)] Polling time is vaild
,06-23 11:34:30.622  9674  9674 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(281/llIIIIlllllIIllIIllI)] Heartbeat settings is activated.
,06-23 11:34:30.632  9674  9674 I DBG_POLICYDM: [IIlllIIllIllIllIIlll(52/llllIIIllIlIIIIllllI)] Next heartbeat time:2017/07/04/17:22:54
,06-23 11:34:30.632  9674  9674 I DBG_POLICYDM: [IIlllIIllIllIllIIlll(55/llllIIIllIlIIIIllllI)] heartbeat time is vaild
,06-23 11:34:30.632  3486  4434 D ActivityManager:  getDeferredInfo final delay 0
,06-23 11:34:30.642  3486  4434 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{e50180 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{39c8c7 8868:com.osp.app.signin/u0a41}
,06-23 11:34:30.642  8868  8868 I SA      : [OR] onReceive log=[SA = 2.2.02-12 V = 23 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = pl_PL CSC = XEO MCC = 0 MNC 0 T = user DEVICE = herolte P = heroltexx I = MMB29K M = SM-G930F OKLEFT false DIS MMB29K.G930FXXU1BPJG PSS = 5.059173621445858  ]
,06-23 11:34:30.642  8868  8868 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
06-23 11:34:30.642  8868  8868 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,06-23 11:34:30.652  8868  8868 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,06-23 11:34:30.652  8868  8868 I SA      : [OR] == isSIMCardReady false ==
06-23 11:34:30.652  8868  8868 I SA      : [SCU] == networkStateCheck == true
,06-23 11:34:30.652  8868  8868 I SA      : [DM] getCountryCodeFromCSC : PL
,06-23 11:34:30.652  8868  8868 I SA      : isChinaCountryCode : false
06-23 11:34:30.652  8868  8868 I SA      : [SCU] is ChinestModel Data Restricted   : false
06-23 11:34:30.652  8868  8868 I SA      : [OR] == networkStateCheck true ==
,06-23 11:34:30.662  8868  8868 I SA      : [OR] GetMyCountryZoneTask
,06-23 11:34:30.662  8868  8868 I SA      : [OR] onReceive END
,06-23 11:34:30.662  3486  4435 D ActivityManager:  getDeferredInfo final delay 0
,06-23 11:34:30.662  8868  9891 I SA      : [SRS] prepareGetMyCountryZone
,06-23 11:34:30.672  3486  4435 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{e50180 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3d5d19d 6764:com.wssyncmldm/1000}
,06-23 11:34:30.672  8868  9891 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,06-23 11:34:30.682  8868  9891 I SA      : [SSP] query invoked
,06-23 11:34:30.682  8868  9891 I SA      : [TPMU] GetMccFromDB : null
06-23 11:34:30.682  8868  9891 I SA      : [SCU] getMccFromPreferece mcc = 260
06-23 11:34:30.682  8868  9891 I SA      : [LBE] isSupportCheckDomainRegion : true
06-23 11:34:30.682  8868  9891 I SA      : [TPM] isNoProxy(default) : true
,06-23 11:34:30.682  3486  3504 D ActivityManager:  getDeferredInfo final delay 300
,06-23 11:34:30.692  6764  9893 I FOTA_AGENT: [com.samsung.android.app.fotaclient.llIlIIIIlIIIIIlIlIII(87/llIIIIlllllIIllIIllI)] Nothing to do action: android.net.conn.CONNECTIVITY_CHANGE
,06-23 11:34:30.752  3928  4125 D ViewRootImpl: #3 mView = null
,06-23 11:34:30.762  3486  4395 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3486) eventTime = 210913
,06-23 11:34:30.762  3486  4395 D PowerManagerService: [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3486 (0x0)
06-23 11:34:30.762  3486  4395 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3486, ws=WorkSource{10062}) (elapsedTime=1949)
,06-23 11:34:30.792  3486  3858 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -37], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -38]
06-23 11:34:30.792  3486  3858 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
,06-23 11:34:30.792  3486  3858 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -38]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,06-23 11:34:30.792  3928  4125 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,06-23 11:34:30.802  3486  3858 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
,06-23 11:34:30.802  3486  3858 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,06-23 11:34:30.812  3486  3858 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,06-23 11:34:30.812  3486  3858 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,06-23 11:34:30.822  3486  3858 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,06-23 11:34:30.822  3486  3858 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,06-23 11:34:30.832  3486  3858 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
06-23 11:34:30.832  3486  3858 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 503]
06-23 11:34:30.832  3486  3858 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-23 11:34:30.832  3486  3858 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-23 11:34:30.832  3486  3858 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-23 11:34:30.832  3486  3858 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
06-23 11:34:30.832  3486  3858 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=5, legacyType=-1, [] ]
,06-23 11:34:30.832  3486  3858 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-23 11:34:30.832  3486  3858 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-23 11:34:30.832  3486  3858 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-23 11:34:30.832  3486  3858 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-23 11:34:30.832  3486  3858 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-23 11:34:30.832  3486  3858 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-23 11:34:30.952  8868  9891 I SA_HTTPURLCONNECTION: [RC New] Execute method=[GET] start
,06-23 11:34:30.962  8868  9891 I SA_HTTPURLCONNECTION: [RC New] Security=[true]
,06-23 11:34:30.962  8868  9891 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
06-23 11:34:30.962  8868  9891 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-23 11:34:30.962  3151  3625 D EnterpriseController: netId is 0
06-23 11:34:30.962  3151  3625 D Netd    : getNetworkForDns: using netid 503 for uid 10041
,06-23 11:34:30.982  3486  3567 D ActivityManager:  getDeferredInfo final delay 0
,06-23 11:34:30.992  3486  3567 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{e50180 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{abeac2a 6880:com.samsung.fresco.logging/5015}
,06-23 11:34:30.992  3486  3970 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,06-23 11:34:30.992  3486  4379 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-23 11:34:31.002  3486  4257 D ActivityManager:  getDeferredInfo final delay 0
,06-23 11:34:31.012  3486  4257 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{e50180 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{21eae4e 7313:com.sec.spp.push/u0a39}
,06-23 11:34:31.012  7313  7313 E SPPClientService: [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,06-23 11:34:31.012  7313  7313 E SPPClientService: [SystemStateMoniter] Current Time : 211164
,06-23 11:34:31.012  7313  7313 E SPPClientService: [SystemStateMoniter] No Connect : false
,06-23 11:34:31.012  3486  4257 D ActivityManager:  getDeferredInfo final delay 0
,06-23 11:34:31.022  3486  4257 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{e50180 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bffa7e5 4913:android.process.media/u0a48}
,06-23 11:34:31.032  4913  4913 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,06-23 11:34:31.042  3486  3969 D ActivityManager:  getDeferredInfo final delay 300
,06-23 11:34:31.052  3486  4258 D SecContentProvider2: query(), uri = 15 selection = getAppBlockDownloadState
,06-23 11:34:31.182  3486  3564 D libgps  : agps_ril_update_network_availability: Waiting for IPC connection - timeout
06-23 11:34:31.182  3486  3564 E libgps  : LIBGPS: Cannot communicate (write) with a GPSD
06-23 11:34:31.182  3486  3564 E libgps  : IPC Communication Error, ../../../../tmp/14982990_270314/allPartners/os/android/gps_interface/gpsi_client/GpsiClient.cpp:1729 agps_ril_update_network_availability
,06-23 11:34:31.292  3006  4468 I SurfaceFlinger: id=20 Removed Uoast (9/11)
,06-23 11:34:31.292  3006  4327 I SurfaceFlinger: id=20 Removed Uoast (-2/11)
,06-23 11:34:31.302  3006  3006 D libEGL  : eglTerminate EGLDisplay = 0x7ffb1ed708
,06-23 11:34:31.342  3486  3567 D ActivityManager:  getDeferredInfo final delay 0
,06-23 11:34:31.362  3486  3567 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{e50180 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{33f6fd 9704:com.samsung.android.SettingsReceiver/1000}
,06-23 11:34:31.362  9704  9704 E ActivityThread: Failed to find provider info for com.myscript.atk.rmc
,06-23 11:34:31.362  3486  4435 D ActivityManager:  getDeferredInfo final delay 0
,06-23 11:34:31.382  3486  4435 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{e50180 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f6ff2 9717:com.samsung.android.themestore/u0a64}
,06-23 11:34:31.392  9717  9717 D AutoSelfUpgradeReceiver: onReceive() android.net.conn.CONNECTIVITY_CHANGE
,06-23 11:34:31.412  3486  4433 D ActivityManager:  getDeferredInfo final delay 300
,06-23 11:34:31.412  9717  9717 D AutoSelfUpgradeService: onCreate() 
,06-23 11:34:31.412  9717  9717 D AutoSelfUpgradeService: onStartCommand() action.selfupgrade.via.net
,06-23 11:34:31.412  9717  9897 D AutoSelfUpgradeService: startInitAutoSelfUpdate()
,06-23 11:34:31.422  9717  9897 D AutoSelfUpgradeService: getAlarmIntent() 
,06-23 11:34:31.422  9717  9897 D AutoSelfUpgradeService: isAlarmActivated() false
,06-23 11:34:31.422  9717  9897 I AutoSelfUpgradeService: Not a time to rum self upgrade yet.
,06-23 11:34:31.422  9717  9717 D AutoSelfUpgradeService: onDestroy()
,06-23 11:34:31.742  3486  3567 D ActivityManager:  getDeferredInfo final delay 0
,06-23 11:34:31.742  3486  3567 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{e50180 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1da9643 9736:com.samsung.android.scloud:contentsync/5009}
,06-23 11:34:31.742  9736  9736 I [SC]DetectorReceiver: onReceive [android.net.conn.CONNECTIVITY_CHANGE]
06-23 11:34:31.742  9736  9736 I [SC]CloudManager: requestInit
,06-23 11:34:31.752  9736  9736 I [SC]Utils: folder : cachecreate fail, try again.
,06-23 11:34:31.752  9736  9736 I [SC]Utils: folder : cache create fail.
06-23 11:34:31.752  9736  9736 I [SC]Utils: folder : thumbnailcreate fail, try again.
06-23 11:34:31.752  9736  9736 I [SC]Utils: folder : thumbnail create fail.
06-23 11:34:31.752  9736  9736 I [SC]Utils: folder : sharecreate fail, try again.
,06-23 11:34:31.752  9736  9736 I [SC]Utils: folder : share create fail.
06-23 11:34:31.752  9736  9736 I [SC]Utils: folder : scratchcreate fail, try again.
06-23 11:34:31.752  9736  9736 I [SC]Utils: folder : scratch create fail.
06-23 11:34:31.752  9736  9736 I [SC]Utils: folder : eventSynccreate fail, try again.
06-23 11:34:31.752  9736  9736 I [SC]Utils: folder : eventSync create fail.
,06-23 11:34:31.762  8868  8878 I SA      : [SCU] isHaveSA() - false
06-23 11:34:31.762  8868  8878 I SA      : [OCP] Samsung account is not Signed-in
,06-23 11:34:31.762  8868  8878 I SA      : [OCP] Delete DB (TNC data)
,06-23 11:34:31.762  9736  9736 I [SC]CommonUtil: Samsung Account Not Logged in
,06-23 11:34:31.762  3486  4435 D ActivityManager:  getDeferredInfo final delay 0
,06-23 11:34:31.772  3486  4435 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{e50180 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{606539f 9750:com.samsung.android.coreapps/5011}
,06-23 11:34:31.822  3486  4433 D ActivityManager:  getDeferredInfo final delay 0
,06-23 11:34:31.832  3486  4433 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{e50180 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{606539f 9750:com.samsung.android.coreapps/5011}
,06-23 11:34:31.842  3486  4434 D ActivityManager:  getDeferredInfo final delay 0
,06-23 11:34:31.862  3486  4434 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{e50180 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{606539f 9750:com.samsung.android.coreapps/5011}
,06-23 11:34:31.872  3486  4434 D ActivityManager:  getDeferredInfo final delay 0
,06-23 11:34:31.882  3486  4434 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{e50180 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ba75d83 4876:com.microsoft.skydrive/u0a124}
,06-23 11:34:31.912  3486  3504 W IntentResolver: resolveIntent failed: found match, but none with CATEGORY_DEFAULT
,06-23 11:34:31.912  3486  3567 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{222ea7b u0 com.google.android.gcm.CONNECTED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6847a93 9504:com.google.android.talk/u0a112}
,06-23 11:34:31.922  3486  4258 D ActivityManager:  getDeferredInfo final delay 300
,06-23 11:34:31.932  3486  4285 V AlarmManager:  remove PendingIntent] PendingIntent{2718098: PendingIntentRecord{c15dbf7 com.google.android.gms broadcastIntent}}
,06-23 11:34:32.222  3486  3567 D ActivityManager:  getDeferredInfo final delay 0
,06-23 11:34:32.242  3486  3567 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{e50180 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3890b4a 9778:com.google.android.apps.photos/u0a129}
,06-23 11:34:32.262  3486  3567 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5ebb357 u0 com.google.android.apps.photos.actionqueue.INTERNAL_ACTION qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3890b4a 9778:com.google.android.apps.photos/u0a129}
,06-23 11:34:32.262  3486  4379 D ActivityManager:  getDeferredInfo final delay 0
,06-23 11:34:32.272  3486  4379 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{e50180 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3890b4a 9778:com.google.android.apps.photos/u0a129}
,06-23 11:34:32.292  9796  9796 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,06-23 11:34:32.322  3486  3567 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{678fb2d u0 com.google.android.apps.photos.jobqueue.EXECUTE_JOBS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3890b4a 9778:com.google.android.apps.photos/u0a129}
06-23 11:34:32.322  3486  3504 D ActivityManager:  getDeferredInfo final delay 300
,06-23 11:34:32.622  3486  3567 D ActivityManager:  getDeferredInfo final delay 0
,06-23 11:34:32.632  3486  3567 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{e50180 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9d0129b 4622:com.sec.android.daemonapp/u0a159}
,06-23 11:34:32.632  4622  4622 D [Weather Widget]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CFAAE09BFCA326403459399C53A4EE79DAC193CEB26509F8FF7498BE5251A746097407E81C28CD811D388C49D613C81F395B356AA489D29CB4C3BE983CCC84BA76AF507AA66A943348DF162DECA2A5A7DD]}
,06-23 11:34:32.632  4622  4622 D [Weather Widget]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CFE2E89F45594D9820F24D88E9AF210A78152C254DDD0027D207FA50AD616546E30965FECE0D7B834EEF4B0E211833EA2B]}
,06-23 11:34:32.632  3486  3969 D ActivityManager:  getDeferredInfo final delay 0
,06-23 11:34:32.642  3486  3969 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{e50180 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ac9d8 7814:com.sec.android.app.samsungapps/u0a14}
,06-23 11:34:32.652  7814  7814 D WaitQueueForNetworkActivate: notifyNetworkActivated
,06-23 11:34:32.652  7814  7814 D [SAUI]  : NetworkStateReceiver::connected::recovered?false
,06-23 11:34:32.672  7814  7814 D [SAUI]  : Global::recovered::false
,06-23 11:34:32.672  3486  4258 D ActivityManager:  getDeferredInfo final delay 300
06-23 11:34:32.672  7814  7814 D [SAUI]  : AutoUpdateService::onStartCommand
06-23 11:34:32.672  7814  7814 D [SAUI]  : AutoUpdateService::runAutoUpdateManager
,06-23 11:34:32.672  7814  7814 D [SAUI]  : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,06-23 11:34:32.682  7814  7814 D [SAUI]  : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
,06-23 11:34:32.682  7814  7814 D [SA_INIT]: AutoUpdateManager ServiceInitializer startInitialize()
,06-23 11:34:32.682  7814  9901 D [SA_INIT]: createTaskForServiceInitialize()
,06-23 11:34:32.682  7814  9903 D [SA_INIT]: NetworkStateCheckUnit workImpl()
,06-23 11:34:32.682  7814  9903 D [SA_INIT]: NetworkStateCheckUnit result : 1
,06-23 11:34:32.682  7814  7814 V JOULE   : JOULELOG [main]  com.sec.android.app.joule.f Task [35, 153150346_0] [END] FINISHED
06-23 11:34:32.682  7814  7814 D [SA_INIT]: ServiceInitializer onInitializeResult() reuslt : true
06-23 11:34:32.682  7814  7814 D [SAUI]  : AutoUpdateManager:INITCHECK:onInitializeSuccess
,06-23 11:34:32.692  7814  7814 D [SAUI]  : AutoUpdateTriggerManager:IDLE:notifyNextTime
06-23 11:34:32.692  7814  7814 D [SAUI]  : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,06-23 11:34:32.732  8868  9891 I SA_HTTPURLCONNECTION: [RC New] [v2liruge] api execute + 1775
,06-23 11:34:32.742  8868  9891 I SA      : [ODM] saveOpenData( GEO_IP, PL )
,06-23 11:34:32.752  8868  9891 I SA      : [OCP] update openData : PL
,06-23 11:34:32.772  8868  9891 I SA      : [TPMU] getNetworkMcc : 260
,06-23 11:34:32.792  8868  9891 I SA      : [SCU] saveMccToPreferece Start
06-23 11:34:32.792  8868  9891 I SA      : [SCU] RegionMCC : 260
06-23 11:34:32.792  8868  9891 I SA      : [SSP] query invoked
,06-23 11:34:32.802  8868  9891 I SA      : [TPMU] GetMccFromDB : null
,06-23 11:34:32.802  8868  9891 I SA      : [SCU] getMccFromPreferece mcc = 260
06-23 11:34:32.802  8868  9891 I SA      : [SCU] saveMccToPreferece End
06-23 11:34:32.802  8868  9891 I SA_HTTPURLCONNECTION: [RC New] executeRequest [v2liruge] end. 1852
06-23 11:34:32.802  8868  9891 I SA_HTTPURLCONNECTION: [RC New] Execute end
06-23 11:34:32.802  8868  8868 I SA      : [OR] GetMyCountryZoneTask mcc = 260
06-23 11:34:32.802  8868  8868 I SA      : [OR] GetMyCountryZoneTask Success
,06-23 11:34:33.112  3486  3496 I art     : Background sticky concurrent mark sweep GC freed 174169(12MB) AllocSpace objects, 67(1376KB) LOS objects, 29% free, 36MB/51MB, paused 3.624ms total 137.318ms
,06-23 11:34:33.352  3486  3504 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-23 11:34:33.352  3486  3504 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4358, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-23 11:34:33.352  3486  3504 D BatteryService: online:4, current avg:133, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:167
06-23 11:34:33.352  3486  3486 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-23 11:34:33.362  3486  3486 I MotionRecognitionService: Plugged
,06-23 11:34:33.362  3486  3486 D MotionRecognitionService:   cableConnection= 1
06-23 11:34:33.362  3486  3486 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-23 11:34:33.362  3486  3486 D MotionRecognitionService: skip setTransmitPower. 
,06-23 11:34:33.362  3486  3852 D WifiController: ApOrStaEnabledState  msg.what= 155652
,06-23 11:34:33.362  3928  3928 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-23 11:34:33.372  3928  3928 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-23 11:34:33.372  3928  3928 D PowerUI : priorPlugType = 2 mPlugType =  2
,06-23 11:34:33.382  4857  4857 D CommonServiceConfiguration: getStringValueSetting
,06-23 11:34:33.392  4857  4857 D BatteryMonitor: new battery level: 100
,06-23 11:34:33.392  4809  4809 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-23 11:34:33.392  4809  9468 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,06-23 11:34:33.392  3928  3928 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-23 11:34:33.392  3928  3928 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-23 11:34:34.682  3486  6038 D SSRM:n  : SIOP:: AP = 320, PST = 328 (W:14), CP = 267, CUR = 133, LCD = 40
,06-23 11:34:35.722  9374  9439 I io.jxcore.node.OutgoingSocketThreadTest: OutgoingSocketThreadTest
,06-23 11:34:35.722  9374  9439 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,06-23 11:34:35.722  9374  9439 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testNoAvailablePorts
,06-23 11:34:36.302  9796  9796 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,06-23 11:34:36.712  3486  3858 D ConnectivityService: handlePromptUnvalidated 503
,06-23 11:34:36.732  9374  9439 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,06-23 11:34:36.742  9374  9439 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
,06-23 11:34:36.742  9374  9439 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
06-23 11:34:36.742  9374  9439 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 256)
,06-23 11:34:36.742  9374  9439 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
,06-23 11:34:36.742  9374  9439 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
06-23 11:34:36.742  9374  9439 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 257)
,06-23 11:34:36.742  9374  9439 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
,06-23 11:34:36.752  9374  9439 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
,06-23 11:34:36.752  9374  9439 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
,06-23 11:34:36.752  9374  9439 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,06-23 11:34:36.752  9374  9439 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d67e7fa added. We now have 2 listener(s)
06-23 11:34:36.752  9374  9439 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d67e7fa added. We now have 3 listener(s)
06-23 11:34:36.752  9374  9439 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,06-23 11:34:36.752  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"44:78:3E:94:2C:E6"}
,06-23 11:34:36.752  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
06-23 11:34:36.752  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"44:78:3E:94:2C:E6"}
06-23 11:34:36.752  9374  9439 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
06-23 11:34:36.752  9374  9439 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34821ab added. We now have 4 listener(s)
06-23 11:34:36.752  9374  9439 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
06-23 11:34:36.752  9374  9439 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,06-23 11:34:36.762  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:36.772  9374  9439 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
,06-23 11:34:36.772  9374  9439 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
06-23 11:34:36.772  9374  9439 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
,06-23 11:34:36.772  9374  9439 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
06-23 11:34:36.772  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,06-23 11:34:36.772  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":4,"address":"44:78:3E:94:2C:E6"}
,06-23 11:34:36.772  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":4,"address":"44:78:3E:94:2C:E6"}
06-23 11:34:36.772  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:36.772  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,06-23 11:34:36.782  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":4,"address":"44:78:3E:94:2C:E6"}
,06-23 11:34:36.782  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":4,"address":"44:78:3E:94:2C:E6"}
06-23 11:34:36.782  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:36.782  9374  9439 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
06-23 11:34:36.782  9374  9439 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
06-23 11:34:36.782  9374  9439 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,06-23 11:34:36.782  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,06-23 11:34:36.782  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,06-23 11:34:36.782  9374  9439 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
06-23 11:34:36.782  9374  9439 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,06-23 11:34:36.782  9374  9439 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,06-23 11:34:36.782  9374  9439 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
06-23 11:34:36.782  9374  9439 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,06-23 11:34:36.782  9374  9374 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
06-23 11:34:36.782  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
06-23 11:34:36.782  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
06-23 11:34:36.782  9374  9910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
06-23 11:34:36.782  9374  9910 D BluetoothSocket: bindListen(): myUserId = 0
06-23 11:34:36.782  9374  9910 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,06-23 11:34:36.792  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,06-23 11:34:36.792  9374  9439 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
06-23 11:34:36.792  9374  9439 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,06-23 11:34:36.792  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:36.792  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:36.802  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:36.802  9374  9910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
06-23 11:34:36.802  9374  9910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@4e8c3a1, port: 6, type: 1, local socket address: null, socket type: 0
,06-23 11:34:36.802  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-139,7,main], id: 139
,06-23 11:34:36.802  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,06-23 11:34:36.802  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:36.802  9374  9439 D BluetoothAdapter: STATE_ON
06-23 11:34:36.802  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
06-23 11:34:36.802  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
06-23 11:34:36.802  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 4
,06-23 11:34:36.802  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:36.812  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-139,7,main], id: 139
,06-23 11:34:36.812  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:36.812  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
06-23 11:34:36.812  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
06-23 11:34:36.812  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "d73bd5ae-6d0d-480b-a594-f51893853407", Bluetooth MAC address: "44:78:3E:94:2C:E6"
,06-23 11:34:36.812  9374  9439 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 44 78 3E 94 2C E6
06-23 11:34:36.812  9374  9439 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[d73bd5ae-6d0d-480b-a594-f51893853407], mManufacturerSpecificData={}, mServiceData={d73bd5ae-6d0d-480b-a594-f51893853407=[4, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
06-23 11:34:36.812  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[d73bd5ae-6d0d-480b-a594-f51893853407], mManufacturerSpecificData={}, mServiceData={d73bd5ae-6d0d-480b-a594-f51893853407=[4, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
06-23 11:34:36.812  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:36.812  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[d73bd5ae-6d0d-480b-a594-f51893853407], mManufacturerSpecificData={}, mServiceData={d73bd5ae-6d0d-480b-a594-f51893853407=[4, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-139,7,main], id: 139
,06-23 11:34:36.812  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
06-23 11:34:36.812  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[d73bd5ae-6d0d-480b-a594-f51893853407], mManufacturerSpecificData={}, mServiceData={d73bd5ae-6d0d-480b-a594-f51893853407=[4, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
06-23 11:34:36.812  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:36.812  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-139,7,main], id: 139
,06-23 11:34:36.812  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[d73bd5ae-6d0d-480b-a594-f51893853407], mManufacturerSpecificData={}, mServiceData={d73bd5ae-6d0d-480b-a594-f51893853407=[4, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:36.822  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:36.822  9374  9439 D BluetoothAdapter: STATE_ON
06-23 11:34:36.822  9374  9439 D BluetoothLeAdvertiser: start advertising
,06-23 11:34:36.822  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:36.822  4809  5345 D BtGatt.GattService: registerClient() - UUID=4e6d23ae-7419-4935-857c-4c9bc1ac37ea
,06-23 11:34:36.872  4809  4976 D BtGatt.GattService: onClientRegistered() - UUID=4e6d23ae-7419-4935-857c-4c9bc1ac37ea, clientIf=8
,06-23 11:34:36.872  9374  9434 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=8
,06-23 11:34:36.882  4809  5246 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,06-23 11:34:36.892  4809  5246 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,06-23 11:34:36.892  4809  5246 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
06-23 11:34:36.892  4809  5020 D BtGatt.AdvertiseManager: message : 0
,06-23 11:34:36.892  4809  5035 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
06-23 11:34:36.892  4809  5035 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 23, currDate: 23
06-23 11:34:36.892  4809  5020 D BtGatt.AdvertiseManager: number of adv instance running = 0
06-23 11:34:36.892  4809  5020 D BtGatt.AdvertiseManager: size of list is =0
,06-23 11:34:36.902  4809  5020 D BtGatt.AdvertiseManager: starting advertising
,06-23 11:34:36.902  4809  5020 D BtGatt.AdvertiseManager: isStandardAdv = false
,06-23 11:34:36.912  4809  5035 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.thaliproject.thalitest : 32
06-23 11:34:36.912  4809  5035 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.thaliproject.thalitest@LowLatency : 24970174
06-23 11:34:36.912  4809  5035 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.thaliproject.thalitest@LowLatency : 2
06-23 11:34:36.912  4809  5035 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
06-23 11:34:36.912  4809  5035 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 0 => 0
,06-23 11:34:36.912  3486  4433 V AlarmManager:  remove PendingIntent] PendingIntent{7cae1dc: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:36.922  4809  4976 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=8, status=0
,06-23 11:34:36.922  4809  5020 D BtGatt.AdvertiseManager: starting multi advertising
,06-23 11:34:36.922  4809  4976 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=8, status=0
06-23 11:34:36.922  4809  5020 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
06-23 11:34:36.922  4809  5020 D BtGatt.AdvertiseManager: clientIf: 8, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
06-23 11:34:36.922  4809  5020 D BtGatt.AdvertiseManager: postCallback clientIf = 8 status = 0
06-23 11:34:36.922  4809  5020 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=8, status=0, isStart=true
,06-23 11:34:36.922  3486  3975 V AlarmManager:  remove PendingIntent] PendingIntent{e5b62e5: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
06-23 11:34:36.922  9374  9384 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
06-23 11:34:36.922  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:36.922  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:36.922  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,06-23 11:34:36.922  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:36.922  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:36.922  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:36.922  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:36.922  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:36.922  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,06-23 11:34:36.932  9374  9439 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,06-23 11:34:36.932  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-139,7,main], id: 139
,06-23 11:34:36.932  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:36.932  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:36.932  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:36.932  9374  9374 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
06-23 11:34:36.932  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
06-23 11:34:36.932  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
06-23 11:34:36.932  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
06-23 11:34:36.932  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
06-23 11:34:36.932  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
06-23 11:34:36.932  9374  9374 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
06-23 11:34:36.932  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
06-23 11:34:36.932  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
06-23 11:34:36.932  3486  4258 V AlarmManager:  remove PendingIntent] PendingIntent{72911ba: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
06-23 11:34:36.932  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
06-23 11:34:36.932  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
06-23 11:34:36.932  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
06-23 11:34:36.932  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
06-23 11:34:36.932  9374  9374 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
,06-23 11:34:36.932  9374  9374 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,06-23 11:34:36.942  9374  9374 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
06-23 11:34:36.942  3486  4395 V AlarmManager:  remove PendingIntent] PendingIntent{fbf686b: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:36.942  9374  9374 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
06-23 11:34:36.942  9374  9374 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
06-23 11:34:36.942  9374  9374 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
06-23 11:34:36.942  9374  9374 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,06-23 11:34:36.942  3486  3504 V AlarmManager:  remove PendingIntent] PendingIntent{4123fc8: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:36.952  3486  3975 V AlarmManager:  remove PendingIntent] PendingIntent{7e44861: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:36.952  3486  4422 V AlarmManager:  remove PendingIntent] PendingIntent{6468f86: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:36.962  3486  3969 V AlarmManager:  remove PendingIntent] PendingIntent{36a2047: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:37.292  9504  9557 W Babel   : ayr TOOK TOO LONG! (15001ms > 10000ms)
,06-23 11:34:37.302  9504  9559 W Babel   : ayr TOOK TOO LONG! (15000ms > 10000ms)
,06-23 11:34:37.312  3486  4396 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity newState = 2 callingPackage = 10112
,06-23 11:34:37.352  3486  3567 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7ef9074 u0 register_intent_action qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e9f0f3b 8386:com.google.android.talk:matchstick/u0a112}
,06-23 11:34:37.382  3486  3970 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,06-23 11:34:37.392  8386  9913 I MS_RegisterService: RegisterService intent:Intent { act=register_intent_action flg=0x10 cmp=com.google.android.talk/com.google.android.libraries.matchstick.net.SilentRegisterService bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} } isPeriodic:false
,06-23 11:34:37.392  9504  9504 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
06-23 11:34:37.392  9504  9504 W Babel   : BAM#gBA: invalid account id: -1
06-23 11:34:37.392  9504  9504 W Babel   : BAM#gBA: invalid account id: -1
06-23 11:34:37.392  9504  9504 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,06-23 11:34:37.402  8386  9913 I MS_RegisterService: Not registered and not enabled. Doing nothing.
,06-23 11:34:37.402  3486  4395 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,06-23 11:34:37.432  9374  9439 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,06-23 11:34:37.432  9374  9439 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
06-23 11:34:37.432  9374  9439 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
06-23 11:34:37.432  9374  9439 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
06-23 11:34:37.432  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
06-23 11:34:37.432  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
06-23 11:34:37.432  9374  9910 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
06-23 11:34:37.432  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
06-23 11:34:37.432  9374  9910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,06-23 11:34:37.432  9374  9910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
06-23 11:34:37.432  9374  9439 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
06-23 11:34:37.432  9374  9439 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
06-23 11:34:37.432  9374  9439 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
06-23 11:34:37.432  9374  9439 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
06-23 11:34:37.432  9374  9374 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
06-23 11:34:37.432  9374  9374 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
06-23 11:34:37.432  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-139,7,main], id: 139
,06-23 11:34:37.432  9374  9374 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
06-23 11:34:37.432  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
06-23 11:34:37.432  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
06-23 11:34:37.432  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:37.432  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:37.432  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:37.432  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-139,7,main], id: 139
,06-23 11:34:37.442  9374  9439 D BluetoothAdapter: STATE_ON
06-23 11:34:37.442  9374  9439 D BluetoothAdapter: STATE_ON
06-23 11:34:37.442  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,06-23 11:34:37.442  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:37.442  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:37.442  9374  9439 D BluetoothLeScanner: could not find callback wrapper
06-23 11:34:37.442  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
06-23 11:34:37.442  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:37.442  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:37.442  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:37.442  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
06-23 11:34:37.442  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-139,7,main], id: 139
,06-23 11:34:37.442  9374  9439 D BluetoothAdapter: STATE_ON
06-23 11:34:37.442  9504  9587 W Babel   : ayr TOOK TOO LONG! (15000ms > 10000ms)
,06-23 11:34:37.452  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:37.452  9374  9439 D BluetoothLeAdvertiser: stop advertising
,06-23 11:34:37.452  4809  5345 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
06-23 11:34:37.452  4809  5345 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
06-23 11:34:37.452  4809  5035 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
06-23 11:34:37.452  4809  5035 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 23, currDate: 23
06-23 11:34:37.452  4809  5035 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
,06-23 11:34:37.452  4809  5035 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 0 => 0
06-23 11:34:37.452  4809  5035 D BtGatt.GattService: [GSIM LOG]: remove : com.thaliproject.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
06-23 11:34:37.452  4809  5020 D BtGatt.AdvertiseManager: message : 1
,06-23 11:34:37.452  4809  5020 D BtGatt.AdvertiseManager: stop advertise for client =  8
06-23 11:34:37.452  4809  5020 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 8,
,06-23 11:34:37.462  4809  5020 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
06-23 11:34:37.462  3486  4049 V AlarmManager:  remove PendingIntent] PendingIntent{36c1e12: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:37.462  4809  4976 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=8, status=0
,06-23 11:34:37.462  4809  4976 D BtGatt.GattService: Client app is not null!
06-23 11:34:37.462  9374  9385 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,06-23 11:34:37.462  4809  5246 D BtGatt.GattService: unregisterClient() - clientIf=8
,06-23 11:34:37.472  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,06-23 11:34:37.472  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:37.472  3486  4422 V AlarmManager:  remove PendingIntent] PendingIntent{a1e79e3: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
06-23 11:34:37.472  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
06-23 11:34:37.472  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-139,7,main], id: 139
,06-23 11:34:37.472  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:37.472  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:37.472  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,06-23 11:34:37.472  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
06-23 11:34:37.472  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
06-23 11:34:37.472  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-139,7,main], id: 139
,06-23 11:34:37.472  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-139,7,main], id: 139
,06-23 11:34:37.472  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
06-23 11:34:37.482  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:37.482  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-139,7,main], id: 139
,06-23 11:34:37.482  9374  9374 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
06-23 11:34:37.482  9374  9374 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
06-23 11:34:37.482  9374  9374 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
06-23 11:34:37.482  9374  9374 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
06-23 11:34:37.482  9374  9374 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
06-23 11:34:37.482  9374  9374 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,06-23 11:34:37.482  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
06-23 11:34:37.482  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
06-23 11:34:37.482  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
06-23 11:34:37.482  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
06-23 11:34:37.482  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
06-23 11:34:37.482  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
06-23 11:34:37.482  9374  9374 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,06-23 11:34:37.482  3486  3969 V AlarmManager:  remove PendingIntent] PendingIntent{3ea095e: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
06-23 11:34:37.482  3486  3505 V AlarmManager:  remove PendingIntent] PendingIntent{634d13f: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
06-23 11:34:37.492  3486  4435 V AlarmManager:  remove PendingIntent] PendingIntent{1f87a0c: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
06-23 11:34:37.502  3486  3504 V AlarmManager:  remove PendingIntent] PendingIntent{d43cf55: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
06-23 11:34:37.512  3486  3505 V AlarmManager:  remove PendingIntent] PendingIntent{d2f425b: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
06-23 11:34:37.522  3486  4395 V AlarmManager:  remove PendingIntent] PendingIntent{b92af8: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:37.982  9374  9374 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,06-23 11:34:40.312  9796  9796 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,06-23 11:34:40.322  9796  9796 I dhcpcd  : wlan0: no IPv6 Routers available
,06-23 11:34:40.482  9374  9439 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
06-23 11:34:40.482  9374  9439 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
06-23 11:34:40.482  9374  9439 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
06-23 11:34:40.482  9374  9439 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
06-23 11:34:40.482  9374  9439 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
06-23 11:34:40.482  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
06-23 11:34:40.482  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,06-23 11:34:40.502  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,06-23 11:34:40.502  9374  9439 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
06-23 11:34:40.502  9374  9439 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,06-23 11:34:40.512  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:40.512  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:40.512  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:40.522  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-139,7,main], id: 139
,06-23 11:34:40.522  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,06-23 11:34:40.522  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:40.532  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:40.532  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
06-23 11:34:40.532  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
06-23 11:34:40.532  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 4
,06-23 11:34:40.532  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:40.542  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:40.552  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:40.552  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:40.552  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-139,7,main], id: 139
,06-23 11:34:40.552  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
06-23 11:34:40.552  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
06-23 11:34:40.552  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 53944
,06-23 11:34:40.562  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=53944, mManufacturerData=null, mManufacturerDataMask=null]
06-23 11:34:40.562  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:40.562  9374  9439 D BluetoothLeScanner: Start Scan
,06-23 11:34:40.562  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:40.562  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:40.572  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:40.572  3486  3847 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: true, uidstate: 6, mProxSensorScreenOff: false
,06-23 11:34:40.572  3486  3847 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: true, uidstate: 6, mProxSensorScreenOff: false
06-23 11:34:40.572  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:40.582  4809  5246 D BtGatt.GattService: registerClient() - UUID=ff813435-9df0-4495-a6d3-5bf4fefed27d
,06-23 11:34:40.622  4809  4976 D BtGatt.GattService: onClientRegistered() - UUID=ff813435-9df0-4495-a6d3-5bf4fefed27d, clientIf=8
,06-23 11:34:40.622  9374  9384 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=8
,06-23 11:34:40.632  4809  9502 D BtGatt.GattService: start scan with filters
,06-23 11:34:40.632  4809  9502 D BtGatt.GattService: getScanSettings
,06-23 11:34:40.632  4809  9502 D BtGatt.GattService: Is it foreground application = true
,06-23 11:34:40.632  4809  9502 D BtGatt.GattService: not a background application
,06-23 11:34:40.642  4809  9502 D BtGatt.GattService: [GSIM LOG]: getActualScanMode (2/100 vs 100/5)
,06-23 11:34:40.652  4809  9502 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,06-23 11:34:40.652  4809  9502 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,06-23 11:34:40.652  4809  5035 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_SCAN
06-23 11:34:40.652  4809  5035 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 23, currDate: 23
,06-23 11:34:40.652  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
06-23 11:34:40.652  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:40.652  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,06-23 11:34:40.652  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:40.652  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
06-23 11:34:40.652  9374  9374 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,06-23 11:34:40.652  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
06-23 11:34:40.652  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
06-23 11:34:40.672  3486  4258 V AlarmManager:  remove PendingIntent] PendingIntent{d1fea4: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
06-23 11:34:40.652  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
06-23 11:34:40.652  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
06-23 11:34:40.652  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
06-23 11:34:40.652  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
06-23 11:34:40.652  9374  9374 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
06-23 11:34:40.662  4809  5027 D BtGatt.ScanManager: handling starting scan
06-23 11:34:40.662  4809  5027 D BluetoothAdapter: STATE_ON
06-23 11:34:40.662  9374  9439 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
06-23 11:34:40.662  4809  5027 D BluetoothAdapter: STATE_ON
06-23 11:34:40.662  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-139,7,main], id: 139,
06-23 11:34:40.672  4809  5035 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.thaliproject.thalitest : 20
06-23 11:34:40.672  4809  5035 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.thaliproject.thalitest, com.thaliproject.thalitest
06-23 11:34:40.682  3486  4433 V AlarmManager:  remove PendingIntent] PendingIntent{bd7940d: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
06-23 11:34:40.672  4809  4976 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=8, status=0, action=1
06-23 11:34:40.672  4809  4976 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
06-23 11:34:40.672  4809  5027 D BtGatt.ScanManager: set filter index= 7 for clientIf= 8
06-23 11:34:40.692  3486  4434 V AlarmManager:  remove PendingIntent] PendingIntent{8f42fc2: PendingIntentRecord{891a1d3 com.android.bluetooth broadcastIntent}}
06-23 11:34:40.672  4809  5027 D BtGatt.ScanManager: High Rssi Filter value is = -128
06-23 11:34:40.692  3486  3504 V AlarmManager:  remove PendingIntent] PendingIntent{1826110: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
06-23 11:34:40.672  4809  5027 D BtGatt.ScanManager: Low Rssi Filter value is = -128
06-23 11:34:40.672  4809  5027 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =2
06-23 11:34:40.682  4809  4976 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=8, status=0, action=0, availableSpace=27
06-23 11:34:40.682  4809  4976 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
06-23 11:34:40.682  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:40.682  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
06-23 11:34:40.682  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:40.682  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:40.682  9374  9374 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
06-23 11:34:40.682  4809  5027 D BtGatt.ScanManager: Starting BLE batch scan
06-23 11:34:40.682  4809  5027 D BtGatt.ScanManager: configuring batch scan storage, appIf 8
06-23 11:34:40.682  4809  5035 D BtGatt.GattService: [GSIM LOG]: increaseScanCount 4 Battery : com.thaliproject.thalitest : 1
06-23 11:34:40.682  4809  4976 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=8, status=0
06-23 11:34:40.682  4809  4976 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
06-23 11:34:40.682  4809  5035 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.thaliproject.thalitest : 24970174
06-23 11:34:40.682  4809  5035 D BtGatt.GattService: [GSIM LOG]: setRequestedScanType : com.thaliproject.thalitest : 2
06-23 11:34:40.682  4809  5035 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.thaliproject.thalitest : 2
06-23 11:34:40.682  4809  5035 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
06-23 11:34:40.682  4809  5035 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 0 => 0
06-23 11:34:40.682  4809  5035 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, A time : 0 => 0
06-23 11:34:40.682  4809  5035 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
06-23 11:34:40.682  4809  4976 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=8, status=0, startStopAction=1
06-23 11:34:40.682  9374  9374 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
06-23 11:34:40.682  4809  4976 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
06-23 11:34:40.682  9374  9374 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
06-23 11:34:40.692  3486  4258 V AlarmManager:  remove PendingIntent] PendingIntent{766409: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
06-23 11:34:40.682  9374  9374 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
06-23 11:34:40.692  9374  9374 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
06-23 11:34:40.692  4809  5035 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 0 => 0
06-23 11:34:40.692  4809  5035 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, A time : 0 => 0
06-23 11:34:40.692  4809  5035 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.thaliproject.thalitest : 2
06-23 11:34:40.692  4809  5035 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
06-23 11:34:40.692  4809  5035 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 0 => 0
06-23 11:34:40.692  4809  5035 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, A time : 0 => 0
06-23 11:34:40.692  4809  5035 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.thaliproject.thalitest : 24970174
06-23 11:34:40.692  4809  5035 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 3
06-23 11:34:40.702  4809  5035 D BtGatt.GattService: [GSIM LOG]: com.samsung.android.beaconmanager@Custom, R time : 6 => 9
06-23 11:34:40.702  3486  4433 V AlarmManager:  remove PendingIntent] PendingIntent{cd9860e: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
06-23 11:34:40.712  4809  5035 D BtGatt.GattService: [GSIM LOG]: com.samsung.android.beaconmanager@Custom, A time : 4 => 7
06-23 11:34:40.712  3486  4396 V AlarmManager:  remove PendingIntent] PendingIntent{c4a882f: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
06-23 11:34:40.712  4809  5035 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.samsung.android.beaconmanager : 2
06-23 11:34:40.712  4809  5035 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
06-23 11:34:40.712  4809  5035 D BtGatt.GattService: [GSIM LOG]: com.samsung.android.beaconmanager@Custom, R time : 9 => 9
06-23 11:34:40.712  4809  5035 D BtGatt.GattService: [GSIM LOG]: com.samsung.android.beaconmanager@LowLatency, A time : 2 => 2
06-23 11:34:40.712  4809  5035 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.samsung.android.beaconmanager : 24970174
,06-23 11:34:40.712  3486  4395 V AlarmManager:  remove PendingIntent] PendingIntent{4947e3c: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
06-23 11:34:40.722  3486  3504 V AlarmManager:  remove PendingIntent] PendingIntent{1837c5: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
06-23 11:34:40.722  3486  4258 V AlarmManager:  remove PendingIntent] PendingIntent{2abf51a: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
06-23 11:34:40.722  3486  4433 V AlarmManager:  remove PendingIntent] PendingIntent{401784b: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
06-23 11:34:40.732  3486  4396 V AlarmManager:  remove PendingIntent] PendingIntent{c494228: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
06-23 11:34:40.732  3486  4395 V AlarmManager:  remove PendingIntent] PendingIntent{498b41: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
06-23 11:34:40.742  3486  4257 V AlarmManager:  remove PendingIntent] PendingIntent{d0448e6: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
06-23 11:34:40.742  3486  3505 V AlarmManager:  remove PendingIntent] PendingIntent{ed4e27: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:41.192  9374  9374 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
06-23 11:34:41.192  9374  9374 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
06-23 11:34:41.192  9374  9374 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,06-23 11:34:41.692  3486  3807 V AlarmManager: Expired Alarm result :4
,06-23 11:34:41.702  4809  4809 D BtGatt.ScanManager: awakened up at time 221851
,06-23 11:34:41.702  4809  5027 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 8
,06-23 11:34:41.702  3486  4395 V AlarmManager:  remove PendingIntent] PendingIntent{8e29a7d: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:41.702  4809  4976 D BtGatt.GattService: onBatchScanReports() - clientIf=8, status=0, reportType=2, numRecords=3
06-23 11:34:41.702  4809  4976 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
06-23 11:34:41.712  3486  4434 V AlarmManager:  remove PendingIntent] PendingIntent{d3c0d72: PendingIntentRecord{891a1d3 com.android.bluetooth broadcastIntent}}
06-23 11:34:41.702  4809  4976 D BtGatt.GattService: current time is 221859818456
06-23 11:34:41.712  4809  4976 D BtGatt.GattService: Batch record : [106, -88, -106, -102, 81, 28, 1, -128, -96, 1, 0, 31, 30, -1, 6, 0, 1, 9, 32, 0, 21, 28, -117, 59, -61, -1, 54, 115, -12, -66, 35, -80, -54, -89, 95, 9, -96, -124, 99, -121, 99, 41, 76, 0, 65, 120, -89, 73, -35, 118, 1, -128, -65, 8, 0, 0, 0, 65, 120, -89, 73, -35, 118, 1, -128, -65, 2, 0, 29, 17, 7, 7, 52, -123, -109, 24, -11, -108, -91, 11, 72, 13, 109, -82, -43, 59, -41, 10, 22, -82, -43, 4, -88, -127, -107, -23, 95, 111, 0]
06-23 11:34:41.712  4809  4976 D BtGatt.GattService: ScanRecord : [30, -1, 6, 0, 1, 9, 32, 0, 21, 28, -117, 59, -61, -1, 54, 115, -12, -66, 35, -80, -54, -89, 95, 9, -96, -124, 99, -121, 99, 41, 76]
06-23 11:34:41.712  4809  4976 D ScanRecord: parseFromBytes
06-23 11:34:41.712  4809  4976 D ScanRecord: first manudata for manu ID
06-23 11:34:41.712  4809  4976 D BtGatt.GattService: ScanRecord : []
06-23 11:34:41.712  4809  4976 D ScanRecord: parseFromBytes
,06-23 11:34:41.712  4809  4976 D BtGatt.GattService: ScanRecord : [17, 7, 7, 52, -123, -109, 24, -11, -108, -91, 11, 72, 13, 109, -82, -43, 59, -41, 10, 22, -82, -43, 4, -88, -127, -107, -23, 95, 111]
06-23 11:34:41.712  4809  4976 D ScanRecord: parseFromBytes
,06-23 11:34:41.712  9374  9434 D ScanRecord: parseFromBytes
,06-23 11:34:41.722  9374  9434 D ScanRecord: parseFromBytes
,06-23 11:34:41.722  9374  9434 D ScanRecord: parseFromBytes
06-23 11:34:41.722  9374  9434 D ScanRecord: first manudata for manu ID
06-23 11:34:41.722  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=76:DD:49:A7:78:41, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=null, mManufacturerSpecificData={}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-65, mTimestampNanos=221460975072}
06-23 11:34:41.722  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=76:DD:49:A7:78:41, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[d73bd5ae-6d0d-480b-a594-f51893853407], mManufacturerSpecificData={}, mServiceData={0000d5ae-0000-1000-8000-00805f9b34fb=[4, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-65, mTimestampNanos=221760975072}
06-23 11:34:41.732  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = A8:81:95:E9:5F:6F, provideBluetoothMacAddressRequestId = nullextra info = 4]
,06-23 11:34:41.732  9374  9374 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: Resolved advertisement type: ADVERTISEMENT_PEER_PROPERTIES
06-23 11:34:41.732  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: Parsed advertisment: [UUID = d73bd5ae-6d0d-480b-a594-f51893853407, bluetoothMacAddress = A8:81:95:E9:5F:6F, provideBluetoothMacAddressRequestId = nullextra info = 4]
06-23 11:34:41.732  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult onPeerDiscovered [A8:81:95:E9:5F:6F 4]
,06-23 11:34:41.732  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=1C:51:9A:96:A8:6A, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=null, mManufacturerSpecificData={6=[1, 9, 32, 0, 21, 28, -117, 59, -61, -1, 54, 115, -12, -66, 35, -80, -54, -89, 95, 9, -96, -124, 99, -121, 99, 41, 76]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-96, mTimestampNanos=221810975072}
06-23 11:34:41.732  9374  9374 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onPeerDiscovered: [A8:81:95:E9:5F:6F 4]
06-23 11:34:41.732  9374  9374 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: [A8:81:95:E9:5F:6F 4]
06-23 11:34:41.732  9374  9374 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: Want to call onPeerAdded. Listeners size = 1
06-23 11:34:41.732  9374  9374 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onPeerAdded: [A8:81:95:E9:5F:6F 4]
06-23 11:34:41.732  9374  9374 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [A8:81:95:E9:5F:6F 4], added - the peer count is 1
,06-23 11:34:41.732  9374  9374 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [A8:81:95:E9:5F:6F 4], Bluetooth address: A8:81:95:E9:5F:6F, device name: 'null', device address: 'null'
,06-23 11:34:41.742  3486  4422 V AlarmManager:  remove PendingIntent] PendingIntent{6d6a5c3: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:41.742  3486  3970 V AlarmManager:  remove PendingIntent] PendingIntent{7b82e40: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:41.752  3486  4049 V AlarmManager:  remove PendingIntent] PendingIntent{d036179: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:41.762  3486  4434 V AlarmManager:  remove PendingIntent] PendingIntent{eb98ebe: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:41.762  3486  3504 V AlarmManager:  remove PendingIntent] PendingIntent{373db1f: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:42.692  7814  7814 D PreloadUpdateManagerStateMachine: execute::IDLE:EXECUTE
06-23 11:34:42.692  7814  7814 D PreloadUpdateManagerStateMachine: exit::IDLE
06-23 11:34:42.692  7814  7814 D PreloadUpdateManagerStateMachine: entry::CHECK_TIMEOUT_FOR_UPDATE
,06-23 11:34:42.702  7814  7814 D [SAUI]  : AutoUpdateTriggerManager:IDLE:notifyNextTime
,06-23 11:34:42.702  7814  7814 D PreloadUpdateManagerStateMachine: execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,06-23 11:34:42.702  7814  7814 D PreloadUpdateManagerStateMachine: exit::CHECK_TIMEOUT_FOR_UPDATE
06-23 11:34:42.702  7814  7814 D PreloadUpdateManagerStateMachine: entry::IDLE
,06-23 11:34:42.712  3486  3807 V AlarmManager: Expired Alarm result :4
,06-23 11:34:42.712  4809  4809 D BtGatt.ScanManager: awakened up at time 222865
,06-23 11:34:42.712  4809  5027 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 8
,06-23 11:34:42.712  3486  4379 V AlarmManager:  remove PendingIntent] PendingIntent{afbd8ca: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:42.722  4809  4976 D BtGatt.GattService: onBatchScanReports() - clientIf=8, status=0, reportType=2, numRecords=2
,06-23 11:34:42.722  4809  4976 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
06-23 11:34:42.722  4809  4976 D BtGatt.GattService: current time is 222878411763
06-23 11:34:42.722  4809  4976 D BtGatt.GattService: Batch record : [65, 120, -89, 73, -35, 118, 1, -128, -65, 18, 0, 29, 17, 7, 7, 52, -123, -109, 24, -11, -108, -91, 11, 72, 13, 109, -82, -43, 59, -41, 10, 22, -82, -43, 4, -88, -127, -107, -23, 95, 111, 0, 106, -88, -106, -102, 81, 28, 1, -128, -95, 11, 0, 31, 30, -1, 6, 0, 1, 9, 32, 0, 21, 28, -117, 59, -61, -1, 54, 115, -12, -66, 35, -80, -54, -89, 95, 9, -96, -124, 99, -121, 99, 41, 76, 0]
06-23 11:34:42.722  4809  4976 D BtGatt.GattService: ScanRecord : [17, 7, 7, 52, -123, -109, 24, -11, -108, -91, 11, 72, 13, 109, -82, -43, 59, -41, 10, 22, -82, -43, 4, -88, -127, -107, -23, 95, 111]
06-23 11:34:42.722  4809  4976 D ScanRecord: parseFromBytes
06-23 11:34:42.722  4809  4976 D BtGatt.GattService: ScanRecord : [30, -1, 6, 0, 1, 9, 32, 0, 21, 28, -117, 59, -61, -1, 54, 115, -12, -66, 35, -80, -54, -89, 95, 9, -96, -124, 99, -121, 99, 41, 76]
06-23 11:34:42.722  4809  4976 D ScanRecord: parseFromBytes
06-23 11:34:42.722  4809  4976 D ScanRecord: first manudata for manu ID
06-23 11:34:42.732  9374  9385 D ScanRecord: parseFromBytes
,06-23 11:34:42.732  9374  9385 D ScanRecord: parseFromBytes
06-23 11:34:42.732  9374  9385 D ScanRecord: first manudata for manu ID
06-23 11:34:42.732  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=76:DD:49:A7:78:41, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[d73bd5ae-6d0d-480b-a594-f51893853407], mManufacturerSpecificData={}, mServiceData={0000d5ae-0000-1000-8000-00805f9b34fb=[4, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-65, mTimestampNanos=221978653186}
06-23 11:34:42.732  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = A8:81:95:E9:5F:6F, provideBluetoothMacAddressRequestId = nullextra info = 4]
06-23 11:34:42.732  9374  9374 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: Resolved advertisement type: ADVERTISEMENT_PEER_PROPERTIES
,06-23 11:34:42.732  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: Parsed advertisment: [UUID = d73bd5ae-6d0d-480b-a594-f51893853407, bluetoothMacAddress = A8:81:95:E9:5F:6F, provideBluetoothMacAddressRequestId = nullextra info = 4]
06-23 11:34:42.732  3486  3504 V AlarmManager:  remove PendingIntent] PendingIntent{f850a3b: PendingIntentRecord{891a1d3 com.android.bluetooth broadcastIntent}}
06-23 11:34:42.732  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult onPeerDiscovered [A8:81:95:E9:5F:6F 4]
06-23 11:34:42.732  3486  3505 V AlarmManager:  remove PendingIntent] PendingIntent{9658558: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
06-23 11:34:42.732  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=1C:51:9A:96:A8:6A, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=null, mManufacturerSpecificData={6=[1, 9, 32, 0, 21, 28, -117, 59, -61, -1, 54, 115, -12, -66, 35, -80, -54, -89, 95, 9, -96, -124, 99, -121, 99, 41, 76]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-95, mTimestampNanos=222328653186}
06-23 11:34:42.732  9374  9374 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onPeerDiscovered: [A8:81:95:E9:5F:6F 4]
06-23 11:34:42.732  9374  9374 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: [A8:81:95:E9:5F:6F 4]
06-23 11:34:42.732  9374  9374 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: has more info: false,  extra info differs: false
,06-23 11:34:42.732  9374  9374 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [A8:81:95:E9:5F:6F 4] updated - the peer count is 1
,06-23 11:34:42.742  3486  4433 V AlarmManager:  remove PendingIntent] PendingIntent{8eac6b1: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:42.742  3486  4285 V AlarmManager:  remove PendingIntent] PendingIntent{266b796: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:42.742  3486  4379 V AlarmManager:  remove PendingIntent] PendingIntent{5b00f17: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:42.752  3486  3969 V AlarmManager:  remove PendingIntent] PendingIntent{3599f04: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:43.402  3486  4258 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-23 11:34:43.402  3486  4258 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4357, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-23 11:34:43.402  3486  4258 D BatteryService: online:4, current avg:147, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:155
06-23 11:34:43.402  3486  3486 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-23 11:34:43.412  3486  3486 I MotionRecognitionService: Plugged
06-23 11:34:43.412  3486  3486 D MotionRecognitionService:   cableConnection= 1
06-23 11:34:43.412  3486  3486 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-23 11:34:43.412  3486  3486 D MotionRecognitionService: skip setTransmitPower. 
,06-23 11:34:43.422  3486  3852 D WifiController: ApOrStaEnabledState  msg.what= 155652
,06-23 11:34:43.422  3928  3928 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-23 11:34:43.422  3928  3928 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-23 11:34:43.422  3928  3928 D PowerUI : priorPlugType = 2 mPlugType =  2
,06-23 11:34:43.442  4857  4857 D CommonServiceConfiguration: getStringValueSetting
,06-23 11:34:43.452  4857  4857 D BatteryMonitor: new battery level: 100
,06-23 11:34:43.452  4809  4809 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-23 11:34:43.452  4809  9468 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,06-23 11:34:43.462  3928  3928 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-23 11:34:43.462  3928  3928 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-23 11:34:43.602  3486  4128 E Watchdog: !@Sync 7 [06-23 11:34:43.610]
,06-23 11:34:43.682  9374  9439 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
,06-23 11:34:43.682  9374  9439 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
06-23 11:34:43.682  9374  9439 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
06-23 11:34:43.682  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,06-23 11:34:43.692  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":5,"address":"44:78:3E:94:2C:E6"}
06-23 11:34:43.692  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":5,"address":"44:78:3E:94:2C:E6"}
06-23 11:34:43.692  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:43.692  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,06-23 11:34:43.702  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":5,"address":"44:78:3E:94:2C:E6"}
,06-23 11:34:43.702  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":5,"address":"44:78:3E:94:2C:E6"}
06-23 11:34:43.702  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:43.702  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
06-23 11:34:43.702  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 53944
06-23 11:34:43.702  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
06-23 11:34:43.702  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 5
06-23 11:34:43.702  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
06-23 11:34:43.702  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
06-23 11:34:43.702  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
06-23 11:34:43.702  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
06-23 11:34:43.702  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
06-23 11:34:43.702  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:43.702  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 5
,06-23 11:34:43.702  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted false Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:43.702  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:43.702  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
06-23 11:34:43.702  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
06-23 11:34:43.702  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted true Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:43.702  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop scanner Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:43.702  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:43.702  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:43.702  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:43.702  4809  4830 D BtGatt.GattService: flushPendingBatchResults - clientIf=8, isServer=false
,06-23 11:34:43.702  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
06-23 11:34:43.702  4809  5027 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 8
06-23 11:34:43.712  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:43.712  4809  4976 D BtGatt.GattService: onBatchScanReports() - clientIf=8, status=0, reportType=2, numRecords=0
06-23 11:34:43.712  4809  4976 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
06-23 11:34:43.712  3486  4258 V AlarmManager:  remove PendingIntent] PendingIntent{cb41ced: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:43.712  9374  9439 D BluetoothAdapter: STATE_ON
06-23 11:34:43.712  9374  9439 D BluetoothLeScanner: Stop Scan
06-23 11:34:43.712  3486  3970 V AlarmManager:  remove PendingIntent] PendingIntent{5ceb722: PendingIntentRecord{891a1d3 com.android.bluetooth broadcastIntent}}
,06-23 11:34:43.712  4809  4828 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
06-23 11:34:43.712  4809  4828 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,06-23 11:34:43.712  4809  4828 D BtGatt.GattService: stopScan() - queue size =2
06-23 11:34:43.722  4809  5035 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_SCAN
06-23 11:34:43.722  4809  5035 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 23, currDate: 23
06-23 11:34:43.722  4809  5035 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
,06-23 11:34:43.722  4809  5035 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 0 => 0
06-23 11:34:43.722  4809  5035 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, A time : 0 => 0
06-23 11:34:43.722  4809  5035 D BtGatt.GattService: [GSIM LOG]: remove : com.thaliproject.thalitest at  BLE_SCAN_ACTUAL_DB
06-23 11:34:43.722  4809  4830 D BtGatt.GattService: unregisterClient() - clientIf=8
06-23 11:34:43.722  4809  5035 D BtGatt.GattService: [GSIM LOG]: remove : com.thaliproject.thalitest at  BLE_SCAN_REQUESTED_DB
06-23 11:34:43.722  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,06-23 11:34:43.722  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:43.722  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
06-23 11:34:43.722  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:43.722  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
06-23 11:34:43.722  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:43.722  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:43.722  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
06-23 11:34:43.722  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,06-23 11:34:43.722  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 53944
06-23 11:34:43.722  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=53944, mManufacturerData=null, mManufacturerDataMask=null]
06-23 11:34:43.722  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:43.722  9374  9439 D BluetoothLeScanner: Start Scan
,06-23 11:34:43.722  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:43.732  4809  5027 D BtGatt.ScanManager: filter size is 1
,06-23 11:34:43.732  4809  5027 D BtGatt.ScanManager: delete FilterIndex - 7
,06-23 11:34:43.732  3486  4422 V AlarmManager:  remove PendingIntent] PendingIntent{b1c85b3: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
06-23 11:34:43.732  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:43.732  4809  4976 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=8, status=0, action=1, availableSpace=28
06-23 11:34:43.732  4809  4976 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
06-23 11:34:43.732  4809  5027 D BtGatt.ScanManager: stopping BLe Batch
,06-23 11:34:43.742  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:43.742  4809  4976 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=8, status=0, startStopAction=0
06-23 11:34:43.742  4809  4976 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
06-23 11:34:43.742  9374  9439 D BluetoothAdapter: STATE_ON
06-23 11:34:43.742  4809  5027 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 8
,06-23 11:34:43.742  4809  4976 D BtGatt.GattService: onBatchScanReports() - clientIf=8, status=0, reportType=2, numRecords=0
06-23 11:34:43.742  4809  4976 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
,06-23 11:34:43.742  3486  4258 V AlarmManager:  remove PendingIntent] PendingIntent{753a770: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
06-23 11:34:43.742  3486  4049 V AlarmManager:  remove PendingIntent] PendingIntent{c429ae9: PendingIntentRecord{891a1d3 com.android.bluetooth broadcastIntent}}
,06-23 11:34:43.752  4809  9502 D BtGatt.GattService: registerClient() - UUID=8550b883-2e63-4506-8ef0-f393d86f61b6
,06-23 11:34:43.752  3486  4435 V AlarmManager:  remove PendingIntent] PendingIntent{cc5236e: PendingIntentRecord{891a1d3 com.android.bluetooth broadcastIntent}}
,06-23 11:34:43.752  3486  3975 V AlarmManager:  remove PendingIntent] PendingIntent{5cfca0f: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:43.772  3486  3969 V AlarmManager:  remove PendingIntent] PendingIntent{fa3ca9c: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:43.782  3486  4258 V AlarmManager:  remove PendingIntent] PendingIntent{120fca5: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:43.782  3486  4433 V AlarmManager:  remove PendingIntent] PendingIntent{4a4087a: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:43.792  3486  4422 V AlarmManager:  remove PendingIntent] PendingIntent{cc8f82b: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:43.792  4809  4976 D BtGatt.GattService: onClientRegistered() - UUID=8550b883-2e63-4506-8ef0-f393d86f61b6, clientIf=8
,06-23 11:34:43.792  9374  9385 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=8
,06-23 11:34:43.792  4809  4830 D BtGatt.GattService: start scan with filters
,06-23 11:34:43.792  3486  3970 V AlarmManager:  remove PendingIntent] PendingIntent{970f488: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:43.802  4809  4830 D BtGatt.GattService: getScanSettings
,06-23 11:34:43.802  4809  4830 D BtGatt.GattService: Is it foreground application = true
06-23 11:34:43.802  4809  4830 D BtGatt.GattService: not a background application
,06-23 11:34:43.802  3486  4379 V AlarmManager:  remove PendingIntent] PendingIntent{8c9be21: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:43.802  4809  4830 D BtGatt.GattService: [GSIM LOG]: getActualScanMode (2/100 vs 100/5)
,06-23 11:34:43.812  3486  4049 V AlarmManager:  remove PendingIntent] PendingIntent{45a3246: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:43.812  4809  4830 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,06-23 11:34:43.812  4809  4830 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
06-23 11:34:43.812  4809  5035 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_SCAN
06-23 11:34:43.812  4809  5035 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 23, currDate: 23
06-23 11:34:43.812  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started,
06-23 11:34:43.812  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-139,7,main], id: 139
,06-23 11:34:43.812  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
06-23 11:34:43.812  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:43.812  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner started = true Current thread: Thread[Thread-139,7,main], id: 139
,06-23 11:34:43.812  9374  9374 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
06-23 11:34:43.812  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
06-23 11:34:43.812  9374  9439 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
06-23 11:34:43.812  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
06-23 11:34:43.812  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,06-23 11:34:43.812  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
06-23 11:34:43.812  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
06-23 11:34:43.812  9374  9439 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
06-23 11:34:43.812  9374  9439 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,06-23 11:34:43.812  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
06-23 11:34:43.812  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
06-23 11:34:43.812  4809  5027 D BtGatt.ScanManager: handling starting scan
06-23 11:34:43.812  9374  9439 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
06-23 11:34:43.812  9374  9439 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
06-23 11:34:43.812  9374  9439 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
06-23 11:34:43.812  9374  9439 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
06-23 11:34:43.812  9374  9439 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
06-23 11:34:43.812  4809  5027 D BluetoothAdapter: STATE_ON
06-23 11:34:43.822  3486  4422 V AlarmManager:  remove PendingIntent] PendingIntent{ddcec07: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:43.812  9374  9374 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
06-23 11:34:43.812  9374  9924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
06-23 11:34:43.822  4809  5027 D BluetoothAdapter: STATE_ON
06-23 11:34:43.822  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,06-23 11:34:43.822  9374  9439 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
06-23 11:34:43.822  4809  5035 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.thaliproject.thalitest : 21
06-23 11:34:43.822  4809  5035 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.thaliproject.thalitest, com.thaliproject.thalitest
,06-23 11:34:43.822  9374  9924 D BluetoothSocket: bindListen(): myUserId = 0
06-23 11:34:43.822  9374  9924 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
06-23 11:34:43.822  4809  4976 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=8, status=0, action=1
,06-23 11:34:43.822  4809  4976 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
,06-23 11:34:43.822  4809  5027 D BtGatt.ScanManager: set filter index= 8 for clientIf= 8
06-23 11:34:43.822  4809  5027 D BtGatt.ScanManager: High Rssi Filter value is = -128
06-23 11:34:43.822  4809  5027 D BtGatt.ScanManager: Low Rssi Filter value is = -128
06-23 11:34:43.822  4809  5027 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =2
06-23 11:34:43.822  4809  4976 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=8, status=0, action=0, availableSpace=27
06-23 11:34:43.822  4809  4976 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
06-23 11:34:43.822  4809  5027 D BtGatt.ScanManager: Starting BLE batch scan
06-23 11:34:43.822  4809  5027 D BtGatt.ScanManager: configuring batch scan storage, appIf 8
06-23 11:34:43.832  4809  5035 D BtGatt.GattService: [GSIM LOG]: increaseScanCount 4 Battery : com.thaliproject.thalitest : 2
,06-23 11:34:43.832  4809  5035 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.thaliproject.thalitest : 24970174
06-23 11:34:43.832  9374  9924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
06-23 11:34:43.832  4809  5035 D BtGatt.GattService: [GSIM LOG]: setRequestedScanType : com.thaliproject.thalitest : 2
06-23 11:34:43.832  4809  5035 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.thaliproject.thalitest : 2
06-23 11:34:43.832  4809  5035 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
06-23 11:34:43.832  9374  9924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@cdd0b9e, port: 6, type: 1, local socket address: null, socket type: 0
06-23 11:34:43.832  4809  5035 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 0 => 0
06-23 11:34:43.832  4809  5035 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, A time : 0 => 0
06-23 11:34:43.832  4809  5035 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
06-23 11:34:43.832  4809  5035 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 0 => 0
06-23 11:34:43.832  4809  5035 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, A time : 0 => 0
,06-23 11:34:43.832  4809  5035 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.thaliproject.thalitest : 2
06-23 11:34:43.832  4809  5035 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
06-23 11:34:43.832  4809  5035 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 0 => 0
06-23 11:34:43.832  4809  5035 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, A time : 0 => 0
06-23 11:34:43.832  4809  5035 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.thaliproject.thalitest : 24970174
06-23 11:34:43.832  4809  5035 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
06-23 11:34:43.832  4809  5035 D BtGatt.GattService: [GSIM LOG]: com.samsung.android.beaconmanager@Custom, R time : 9 => 9
06-23 11:34:43.832  4809  5035 D BtGatt.GattService: [GSIM LOG]: com.samsung.android.beaconmanager@LowLatency, A time : 2 => 2
06-23 11:34:43.832  4809  5035 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.samsung.android.beaconmanager : 2
06-23 11:34:43.832  4809  5035 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
06-23 11:34:43.832  4809  5035 D BtGatt.GattService: [GSIM LOG]: com.samsung.android.beaconmanager@Custom, R time : 9 => 9
06-23 11:34:43.832  4809  5035 D BtGatt.GattService: [GSIM LOG]: com.samsung.android.beaconmanager@LowLatency, A time : 2 => 2
06-23 11:34:43.832  4809  5035 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.samsung.android.beaconmanager : 24970174
,06-23 11:34:43.832  3486  3970 V AlarmManager:  remove PendingIntent] PendingIntent{b64d134: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:43.842  3486  4395 V AlarmManager:  remove PendingIntent] PendingIntent{3e31b5d: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:43.842  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:43.842  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:43.842  9374  9439 D BluetoothAdapter: STATE_ON
06-23 11:34:43.842  3486  4379 V AlarmManager:  remove PendingIntent] PendingIntent{f72cd2: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:43.842  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:43.852  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:43.852  3486  3975 V AlarmManager:  remove PendingIntent] PendingIntent{55241a3: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:43.852  4809  4976 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=8, status=0
06-23 11:34:43.852  4809  4976 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
,06-23 11:34:43.852  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser : Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:43.852  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:43.852  4809  4976 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=8, status=0, startStopAction=1
06-23 11:34:43.852  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:43.852  4809  4976 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
06-23 11:34:43.852  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
06-23 11:34:43.852  3486  4434 V AlarmManager:  remove PendingIntent] PendingIntent{b17cca0: PendingIntentRecord{891a1d3 com.android.bluetooth broadcastIntent}}
,06-23 11:34:43.852  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
06-23 11:34:43.852  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "d73bd5ae-6d0d-480b-a594-f51893853407", Bluetooth MAC address: "44:78:3E:94:2C:E6"
06-23 11:34:43.852  9374  9439 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 44 78 3E 94 2C E6
06-23 11:34:43.852  9374  9439 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[d73bd5ae-6d0d-480b-a594-f51893853407], mManufacturerSpecificData={}, mServiceData={d73bd5ae-6d0d-480b-a594-f51893853407=[5, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
06-23 11:34:43.852  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[d73bd5ae-6d0d-480b-a594-f51893853407], mManufacturerSpecificData={}, mServiceData={d73bd5ae-6d0d-480b-a594-f51893853407=[5, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
06-23 11:34:43.852  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:43.852  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[d73bd5ae-6d0d-480b-a594-f51893853407], mManufacturerSpecificData={}, mServiceData={d73bd5ae-6d0d-480b-a594-f51893853407=[5, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:43.852  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
06-23 11:34:43.852  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[d73bd5ae-6d0d-480b-a594-f51893853407], mManufacturerSpecificData={}, mServiceData={d73bd5ae-6d0d-480b-a594-f51893853407=[5, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,06-23 11:34:43.852  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:43.852  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:43.852  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[d73bd5ae-6d0d-480b-a594-f51893853407], mManufacturerSpecificData={}, mServiceData={d73bd5ae-6d0d-480b-a594-f51893853407=[5, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-139,7,main], id: 139
,06-23 11:34:43.852  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:43.852  3486  4049 V AlarmManager:  remove PendingIntent] PendingIntent{d3b1059: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:43.862  9374  9439 D BluetoothAdapter: STATE_ON
06-23 11:34:43.862  9374  9439 D BluetoothLeAdvertiser: start advertising
,06-23 11:34:43.862  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:43.862  3486  4434 V AlarmManager:  remove PendingIntent] PendingIntent{ef7441e: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:43.862  4809  5345 D BtGatt.GattService: registerClient() - UUID=e6aae2b8-2f86-4703-9ec5-a5ba4309d8fe
,06-23 11:34:43.862  3486  4422 V AlarmManager:  remove PendingIntent] PendingIntent{33d54ff: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:43.872  3486  4396 V AlarmManager:  remove PendingIntent] PendingIntent{d3d12cc: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:43.872  3486  4379 V AlarmManager:  remove PendingIntent] PendingIntent{4835915: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:43.872  3486  4435 V AlarmManager:  remove PendingIntent] PendingIntent{c4f842a: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:43.882  3486  4434 V AlarmManager:  remove PendingIntent] PendingIntent{a9c421b: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:43.882  3486  4285 V AlarmManager:  remove PendingIntent] PendingIntent{c8e8fb8: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:43.882  3486  3970 V AlarmManager:  remove PendingIntent] PendingIntent{8cd7191: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:43.892  3486  3975 V AlarmManager:  remove PendingIntent] PendingIntent{f39b8f6: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:43.902  4809  4976 D BtGatt.GattService: onClientRegistered() - UUID=e6aae2b8-2f86-4703-9ec5-a5ba4309d8fe, clientIf=9
,06-23 11:34:43.902  9374  9384 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=9
,06-23 11:34:43.912  4809  9502 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,06-23 11:34:43.912  4809  9502 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,06-23 11:34:43.912  4809  9502 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
06-23 11:34:43.912  4809  5020 D BtGatt.AdvertiseManager: message : 0
06-23 11:34:43.912  4809  5035 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
,06-23 11:34:43.912  4809  5035 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 23, currDate: 23
06-23 11:34:43.912  4809  5020 D BtGatt.AdvertiseManager: number of adv instance running = 0
,06-23 11:34:43.912  4809  5020 D BtGatt.AdvertiseManager: size of list is =0
,06-23 11:34:43.912  4809  5020 D BtGatt.AdvertiseManager: starting advertising
,06-23 11:34:43.922  4809  5020 D BtGatt.AdvertiseManager: isStandardAdv = false
,06-23 11:34:43.922  4809  5035 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.thaliproject.thalitest : 33
,06-23 11:34:43.922  4809  5035 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.thaliproject.thalitest@LowLatency : 24970174
06-23 11:34:43.922  4809  5035 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.thaliproject.thalitest@LowLatency : 2
06-23 11:34:43.922  4809  5035 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
06-23 11:34:43.922  4809  5035 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 0 => 0
,06-23 11:34:43.922  3486  4396 V AlarmManager:  remove PendingIntent] PendingIntent{632e4f7: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:43.922  4809  4976 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=9, status=0
,06-23 11:34:43.922  4809  5020 D BtGatt.AdvertiseManager: starting multi advertising
,06-23 11:34:43.932  4809  4976 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=9, status=0
,06-23 11:34:43.932  4809  5020 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
06-23 11:34:43.932  4809  5020 D BtGatt.AdvertiseManager: clientIf: 9, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
06-23 11:34:43.932  4809  5020 D BtGatt.AdvertiseManager: postCallback clientIf = 9 status = 0
06-23 11:34:43.932  4809  5020 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=9, status=0, isStart=true
06-23 11:34:43.932  3486  4258 V AlarmManager:  remove PendingIntent] PendingIntent{378ef64: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
06-23 11:34:43.932  9374  9434 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
,06-23 11:34:43.932  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:43.932  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:43.932  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
06-23 11:34:43.932  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:43.932  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-139,7,main], id: 139
,06-23 11:34:43.932  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:43.932  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:43.932  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:43.932  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: advertiser is started. Current thread: Thread[Thread-139,7,main], id: 139
,06-23 11:34:43.932  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:43.932  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:43.932  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
06-23 11:34:43.932  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: adv = true, disc = true
06-23 11:34:43.932  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,06-23 11:34:43.932  9374  9439 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,06-23 11:34:43.932  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-139,7,main], id: 139
,06-23 11:34:43.942  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:43.942  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:43.942  3486  4422 V AlarmManager:  remove PendingIntent] PendingIntent{ec695cd: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
06-23 11:34:43.942  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:43.942  9374  9374 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
06-23 11:34:43.942  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
06-23 11:34:43.942  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
06-23 11:34:43.942  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
06-23 11:34:43.942  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
,06-23 11:34:43.942  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
06-23 11:34:43.942  9374  9374 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
06-23 11:34:43.942  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
06-23 11:34:43.942  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
06-23 11:34:43.942  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
06-23 11:34:43.942  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,06-23 11:34:43.942  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]Current thread: Thread[main,5,main], id: 1
06-23 11:34:43.942  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
06-23 11:34:43.942  9374  9374 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING] Current thread: Thread[main,5,main], id: 1
06-23 11:34:43.942  9374  9374 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,06-23 11:34:43.942  9374  9374 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,06-23 11:34:43.942  9374  9374 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
06-23 11:34:43.942  9374  9374 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
06-23 11:34:43.942  9374  9374 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
06-23 11:34:43.942  9374  9374 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,06-23 11:34:43.952  3486  4433 V AlarmManager:  remove PendingIntent] PendingIntent{5c06e82: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:43.952  3486  4257 V AlarmManager:  remove PendingIntent] PendingIntent{f26d993: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:43.962  3486  4434 V AlarmManager:  remove PendingIntent] PendingIntent{4879dd0: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:43.962  3486  4395 V AlarmManager:  remove PendingIntent] PendingIntent{eb3c1c9: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:43.972  3486  3969 V AlarmManager:  remove PendingIntent] PendingIntent{20af0ce: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:44.452  9374  9374 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
,06-23 11:34:44.452  9374  9374 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
06-23 11:34:44.452  9374  9374 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,06-23 11:34:44.712  3486  6038 D SSRM:n  : SIOP:: AP = 310, PST = 329 (W:14), CP = 264, CUR = 147, LCD = 40
,06-23 11:34:44.852  3486  3807 V AlarmManager: Expired Alarm result :4
,06-23 11:34:44.862  4809  4809 D BtGatt.ScanManager: awakened up at time 225010
,06-23 11:34:44.862  4809  5027 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 8
,06-23 11:34:44.862  3486  4285 V AlarmManager:  remove PendingIntent] PendingIntent{d90c6fc: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:44.862  4809  4976 D BtGatt.GattService: onBatchScanReports() - clientIf=8, status=0, reportType=2, numRecords=1
06-23 11:34:44.862  4809  4976 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
06-23 11:34:44.862  4809  4976 D BtGatt.GattService: current time is 225017391108
,06-23 11:34:44.862  3486  3504 V AlarmManager:  remove PendingIntent] PendingIntent{62db185: PendingIntentRecord{891a1d3 com.android.bluetooth broadcastIntent}}
,06-23 11:34:44.862  4809  4976 D BtGatt.GattService: Batch record : [106, -88, -106, -102, 81, 28, 1, -128, -96, 4, 0, 31, 30, -1, 6, 0, 1, 9, 32, 0, 21, 28, -117, 59, -61, -1, 54, 115, -12, -66, 35, -80, -54, -89, 95, 9, -96, -124, 99, -121, 99, 41, 76, 0]
,06-23 11:34:44.862  4809  4976 D BtGatt.GattService: ScanRecord : [30, -1, 6, 0, 1, 9, 32, 0, 21, 28, -117, 59, -61, -1, 54, 115, -12, -66, 35, -80, -54, -89, 95, 9, -96, -124, 99, -121, 99, 41, 76]
06-23 11:34:44.862  4809  4976 D ScanRecord: parseFromBytes
06-23 11:34:44.862  4809  4976 D ScanRecord: first manudata for manu ID
,06-23 11:34:44.872  9374  9384 D ScanRecord: parseFromBytes
06-23 11:34:44.872  9374  9384 D ScanRecord: first manudata for manu ID
06-23 11:34:44.872  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=1C:51:9A:96:A8:6A, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=null, mManufacturerSpecificData={6=[1, 9, 32, 0, 21, 28, -117, 59, -61, -1, 54, 115, -12, -66, 35, -80, -54, -89, 95, 9, -96, -124, 99, -121, 99, 41, 76]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-96, mTimestampNanos=224817680185}
,06-23 11:34:44.882  3486  3970 V AlarmManager:  remove PendingIntent] PendingIntent{f694bda: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:44.892  3486  4433 V AlarmManager:  remove PendingIntent] PendingIntent{98de80b: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:44.892  3486  4257 V AlarmManager:  remove PendingIntent] PendingIntent{1a156e8: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:44.902  3486  4434 V AlarmManager:  remove PendingIntent] PendingIntent{99ce101: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:44.912  3486  4258 V AlarmManager:  remove PendingIntent] PendingIntent{c204ba6: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:45.872  3486  3807 V AlarmManager: Expired Alarm result :4
,06-23 11:34:45.872  4809  4809 D BtGatt.ScanManager: awakened up at time 226027
,06-23 11:34:45.882  4809  5027 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 8
,06-23 11:34:45.882  3486  4049 V AlarmManager:  remove PendingIntent] PendingIntent{5a8f994: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:45.892  4809  4976 D BtGatt.GattService: onBatchScanReports() - clientIf=8, status=0, reportType=2, numRecords=1
06-23 11:34:45.892  4809  4976 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
06-23 11:34:45.892  4809  4976 D BtGatt.GattService: current time is 226045660876
,06-23 11:34:45.892  4809  4976 D BtGatt.GattService: Batch record : [106, -88, -106, -102, 81, 28, 1, -128, -97, 9, 0, 31, 30, -1, 6, 0, 1, 9, 32, 0, 21, 28, -117, 59, -61, -1, 54, 115, -12, -66, 35, -80, -54, -89, 95, 9, -96, -124, 99, -121, 99, 41, 76, 0]
06-23 11:34:45.892  3486  3975 V AlarmManager:  remove PendingIntent] PendingIntent{1758c3d: PendingIntentRecord{891a1d3 com.android.bluetooth broadcastIntent}}
,06-23 11:34:45.892  4809  4976 D BtGatt.GattService: ScanRecord : [30, -1, 6, 0, 1, 9, 32, 0, 21, 28, -117, 59, -61, -1, 54, 115, -12, -66, 35, -80, -54, -89, 95, 9, -96, -124, 99, -121, 99, 41, 76]
06-23 11:34:45.892  4809  4976 D ScanRecord: parseFromBytes
06-23 11:34:45.892  4809  4976 D ScanRecord: first manudata for manu ID
06-23 11:34:45.892  9374  9434 D ScanRecord: parseFromBytes
06-23 11:34:45.892  9374  9434 D ScanRecord: first manudata for manu ID
06-23 11:34:45.892  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=1C:51:9A:96:A8:6A, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=null, mManufacturerSpecificData={6=[1, 9, 32, 0, 21, 28, -117, 59, -61, -1, 54, 115, -12, -66, 35, -80, -54, -89, 95, 9, -96, -124, 99, -121, 99, 41, 76]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-97, mTimestampNanos=225595992530}
,06-23 11:34:45.902  3486  4379 V AlarmManager:  remove PendingIntent] PendingIntent{3f57c32: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:45.912  3486  4285 V AlarmManager:  remove PendingIntent] PendingIntent{c094d83: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:45.912  3486  4395 V AlarmManager:  remove PendingIntent] PendingIntent{be61b00: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:45.922  3486  3970 V AlarmManager:  remove PendingIntent] PendingIntent{f33af39: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:45.922  3486  3969 V AlarmManager:  remove PendingIntent] PendingIntent{77b297e: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:46.892  3486  3807 V AlarmManager: Expired Alarm result :4
,06-23 11:34:46.902  4809  4809 D BtGatt.ScanManager: awakened up at time 227054
,06-23 11:34:46.902  4809  5027 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 8
06-23 11:34:46.902  3486  4434 V AlarmManager:  remove PendingIntent] PendingIntent{a11e72c: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:46.912  4809  4976 D BtGatt.GattService: onBatchScanReports() - clientIf=8, status=0, reportType=2, numRecords=0
,06-23 11:34:46.912  4809  4976 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
06-23 11:34:46.912  3486  3504 V AlarmManager:  remove PendingIntent] PendingIntent{61705f5: PendingIntentRecord{891a1d3 com.android.bluetooth broadcastIntent}}
,06-23 11:34:46.932  3486  4422 V AlarmManager:  remove PendingIntent] PendingIntent{c1c5f8a: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:46.942  3486  4049 V AlarmManager:  remove PendingIntent] PendingIntent{bece9fb: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:46.942  9374  9439 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
06-23 11:34:46.942  9374  9439 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,06-23 11:34:46.942  9374  9439 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
06-23 11:34:46.942  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
06-23 11:34:46.942  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
06-23 11:34:46.942  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
06-23 11:34:46.942  9374  9439 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
06-23 11:34:46.942  9374  9439 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
06-23 11:34:46.942  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
06-23 11:34:46.942  9374  9439 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d67e7fa removed from the list
,06-23 11:34:46.942  9374  9439 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d67e7fa removed from the list
06-23 11:34:46.942  9374  9439 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
06-23 11:34:46.942  9374  9924 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
06-23 11:34:46.942  9374  9439 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
06-23 11:34:46.942  9374  9924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
06-23 11:34:46.942  9374  9924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
06-23 11:34:46.942  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:46.942  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,06-23 11:34:46.942  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
06-23 11:34:46.942  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:46.942  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:46.942  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:46.942  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
06-23 11:34:46.942  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:46.942  9374  9374 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
06-23 11:34:46.942  9374  9374 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
06-23 11:34:46.942  9374  9374 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
06-23 11:34:46.952  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:46.952  9374  9439 D BluetoothAdapter: STATE_ON
06-23 11:34:46.952  4809  4830 D BtGatt.GattService: flushPendingBatchResults - clientIf=8, isServer=false
06-23 11:34:46.952  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,06-23 11:34:46.952  4809  5027 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 8
06-23 11:34:46.952  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:46.952  3486  4434 V AlarmManager:  remove PendingIntent] PendingIntent{64c4a18: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:46.952  4809  4976 D BtGatt.GattService: onBatchScanReports() - clientIf=8, status=0, reportType=2, numRecords=0
06-23 11:34:46.952  4809  4976 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
06-23 11:34:46.952  3486  4257 V AlarmManager:  remove PendingIntent] PendingIntent{39f0c71: PendingIntentRecord{891a1d3 com.android.bluetooth broadcastIntent}}
06-23 11:34:46.952  9374  9439 D BluetoothAdapter: STATE_ON
06-23 11:34:46.952  9374  9439 D BluetoothLeScanner: Stop Scan
,06-23 11:34:46.962  4809  4828 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
06-23 11:34:46.962  4809  4828 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
06-23 11:34:46.962  4809  4828 D BtGatt.GattService: stopScan() - queue size =2
06-23 11:34:46.962  4809  5035 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_SCAN
06-23 11:34:46.962  4809  5035 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 23, currDate: 23
06-23 11:34:46.962  4809  5035 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
06-23 11:34:46.962  4809  5035 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 0 => 0
06-23 11:34:46.962  4809  5035 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, A time : 0 => 0
06-23 11:34:46.962  4809  5035 D BtGatt.GattService: [GSIM LOG]: remove : com.thaliproject.thalitest at  BLE_SCAN_ACTUAL_DB
06-23 11:34:46.962  4809  5035 D BtGatt.GattService: [GSIM LOG]: remove : com.thaliproject.thalitest at  BLE_SCAN_REQUESTED_DB
06-23 11:34:46.962  4809  4830 D BtGatt.GattService: unregisterClient() - clientIf=8
06-23 11:34:46.962  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
06-23 11:34:46.962  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-139,7,main], id: 139
,06-23 11:34:46.962  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
06-23 11:34:46.962  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:46.962  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:46.962  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:46.962  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
06-23 11:34:46.962  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-139,7,main], id: 139
,06-23 11:34:46.962  3486  4433 V AlarmManager:  remove PendingIntent] PendingIntent{e8ea56: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:46.962  4809  5027 D BtGatt.ScanManager: filter size is 1
06-23 11:34:46.962  4809  5027 D BtGatt.ScanManager: delete FilterIndex - 8
06-23 11:34:46.972  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:34:46.972  4809  4976 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=8, status=0, action=1, availableSpace=28
06-23 11:34:46.972  9374  9439 D BluetoothAdapter: STATE_ON
06-23 11:34:46.972  4809  4976 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
06-23 11:34:46.972  9374  9439 D BluetoothLeAdvertiser: stop advertising
,06-23 11:34:46.972  4809  5027 D BtGatt.ScanManager: stopping BLe Batch
06-23 11:34:46.972  4809  4976 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=8, status=0, startStopAction=0
06-23 11:34:46.972  4809  4976 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
06-23 11:34:46.972  4809  5027 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 8
,06-23 11:34:46.972  3486  3970 V AlarmManager:  remove PendingIntent] PendingIntent{f162ad7: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
06-23 11:34:46.972  4809  9502 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
06-23 11:34:46.972  4809  9502 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
06-23 11:34:46.972  4809  5035 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
,06-23 11:34:46.972  4809  5035 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 23, currDate: 23
06-23 11:34:46.972  4809  5035 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
06-23 11:34:46.972  4809  5035 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 0 => 0
06-23 11:34:46.972  4809  5035 D BtGatt.GattService: [GSIM LOG]: remove : com.thaliproject.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
,06-23 11:34:46.972  4809  5020 D BtGatt.AdvertiseManager: message : 1
06-23 11:34:46.972  4809  4976 D BtGatt.GattService: onBatchScanReports() - clientIf=8, status=0, reportType=2, numRecords=0
06-23 11:34:46.972  4809  4976 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
06-23 11:34:46.982  3486  3505 V AlarmManager:  remove PendingIntent] PendingIntent{6c7efc4: PendingIntentRecord{891a1d3 com.android.bluetooth broadcastIntent}}
,06-23 11:34:46.982  4809  5020 D BtGatt.AdvertiseManager: stop advertise for client =  9
06-23 11:34:46.982  4809  5020 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 9
,06-23 11:34:46.982  3486  4258 V AlarmManager:  remove PendingIntent] PendingIntent{3c6fead: PendingIntentRecord{891a1d3 com.android.bluetooth broadcastIntent}}
,06-23 11:34:46.982  3486  4395 V AlarmManager:  remove PendingIntent] PendingIntent{42155e2: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:46.982  4809  5020 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,06-23 11:34:46.982  4809  4976 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=9, status=0
,06-23 11:34:46.982  4809  4976 D BtGatt.GattService: Client app is not null!
06-23 11:34:46.982  9374  9434 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,06-23 11:34:46.982  4809  5246 D BtGatt.GattService: unregisterClient() - clientIf=9
,06-23 11:34:46.992  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,06-23 11:34:46.992  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:46.992  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
06-23 11:34:46.992  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:46.992  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-139,7,main], id: 139
,06-23 11:34:46.992  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:46.992  3486  3970 V AlarmManager:  remove PendingIntent] PendingIntent{9289d73: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
06-23 11:34:46.992  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
06-23 11:34:46.992  9374  9439 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
06-23 11:34:46.992  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
06-23 11:34:46.992  9374  9439 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
06-23 11:34:46.992  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-139,7,main], id: 139
,06-23 11:34:46.992  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:46.992  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
06-23 11:34:46.992  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:46.992  9374  9439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-139,7,main], id: 139
06-23 11:34:46.992  9374  9439 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34821ab removed from the list
06-23 11:34:46.992  9374  9439 D io.jxcore.node.ConnectivityMonitor: stop
06-23 11:34:46.992  9374  9374 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
06-23 11:34:46.992  9374  9439 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
06-23 11:34:46.992  9374  9439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
06-23 11:34:46.992  9374  9374 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
06-23 11:34:46.992  9374  9374 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
06-23 11:34:46.992  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
06-23 11:34:46.992  3486  4379 V AlarmManager:  remove PendingIntent] PendingIntent{364430: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
06-23 11:34:46.992  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
06-23 11:34:46.992  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
06-23 11:34:46.992  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
06-23 11:34:46.992  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
06-23 11:34:46.992  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
06-23 11:34:46.992  9374  9374 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
06-23 11:34:46.992  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
06-23 11:34:46.992  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
06-23 11:34:46.992  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
06-23 11:34:46.992  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
06-23 11:34:46.992  9374  9374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
06-23 11:34:46.992  9374  9374 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: fa,lse, is advertising: false
06-23 11:34:46.992  9374  9439 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
06-23 11:34:46.992  9374  9439 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
06-23 11:34:46.992  9374  9439 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
06-23 11:34:46.992  9374  9439 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
06-23 11:34:46.992  9374  9439 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
06-23 11:34:46.992  9374  9439 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
06-23 11:34:46.992  9374  9439 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
06-23 11:34:46.992  9374  9439 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
06-23 11:34:47.002  9374  9439 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
,06-23 11:34:47.002  9374  9439 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
06-23 11:34:47.002  3486  4258 V AlarmManager:  remove PendingIntent] PendingIntent{d01d8a9: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:47.002  9374  9439 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
,06-23 11:34:47.002  9374  9439 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
,06-23 11:34:47.002  9374  9439 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
,06-23 11:34:47.002  9374  9439 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
06-23 11:34:47.002  3486  4434 V AlarmManager:  remove PendingIntent] PendingIntent{582ee2e: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
06-23 11:34:47.002  9374  9439 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,06-23 11:34:47.012  3486  4257 V AlarmManager:  remove PendingIntent] PendingIntent{2e59dcf: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:47.012  3486  4396 V AlarmManager:  remove PendingIntent] PendingIntent{ef3735c: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:47.022  3486  4049 V AlarmManager:  remove PendingIntent] PendingIntent{ff65665: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:47.022  3486  4435 V AlarmManager:  remove PendingIntent] PendingIntent{153bf3a: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:47.032  3486  3504 V AlarmManager:  remove PendingIntent] PendingIntent{5c847eb: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:47.032  3486  4285 V AlarmManager:  remove PendingIntent] PendingIntent{6f26948: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:47.032  3486  3969 V AlarmManager:  remove PendingIntent] PendingIntent{6faf3e1: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:47.042  3486  3505 V AlarmManager:  remove PendingIntent] PendingIntent{2e9506: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:47.042  3486  3975 V AlarmManager:  remove PendingIntent] PendingIntent{de177c7: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:47.052  3486  4395 V AlarmManager:  remove PendingIntent] PendingIntent{668d1f4: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:47.052  3486  4422 V AlarmManager:  remove PendingIntent] PendingIntent{151ed1d: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:47.062  3486  3970 V AlarmManager:  remove PendingIntent] PendingIntent{78efb92: PendingIntentRecord{5bb36a7 com.android.bluetooth broadcastIntent}}
,06-23 11:34:47.502  9374  9374 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,06-23 11:34:49.012  9374  9439 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,06-23 11:34:49.162  9374  9927 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 270, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [0:0:0:0:0:0].
06-23 11:34:49.162  9374  9927 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
06-23 11:34:49.162  9374  9927 D io.jxcore.node.StreamCopyingThread:  id: 83
,06-23 11:34:49.352  3486  6077 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-23 11:34:49.952  9374  9927 W !!      : call onHalfStreamCopied
06-23 11:34:49.952  9374  9927 I testCopyDataAndClose: closing input stream
,06-23 11:34:50.642  9374  9927 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 270, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [0:0:0:0:0:0].
06-23 11:34:50.642  9374  9927 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
06-23 11:34:50.642  9374  9927 D io.jxcore.node.StreamCopyingThread:  id: 83
06-23 11:34:50.642  9374  9927 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
06-23 11:34:50.642  9374  9927 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
06-23 11:34:50.642  9374  9927 D io.jxcore.node.StreamCopyingThread:  id: 83
06-23 11:34:50.642  9374  9927 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
06-23 11:34:50.642  9374  9927 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
06-23 11:34:50.642  9374  9927 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
06-23 11:34:50.642  9374  9927 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
06-23 11:34:50.642  9374  9927 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
06-23 11:34:50.642  9374  9927 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 270, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [0:0:0:0:0:0].
06-23 11:34:50.642  9374  9927 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
06-23 11:34:50.642  9374  9927 D io.jxcore.node.StreamCopyingThread:  id: 83 .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,06-23 11:34:53.042  9374  9439 I StreamCopyingThreadTest: Starting test: testCopyBigData
,06-23 11:34:53.102  9374  9928 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 273, name: testCopyBigData thread). Connection data: Peer properties: [0:0:0:0:0:0].
06-23 11:34:53.102  9374  9928 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
06-23 11:34:53.102  9374  9928 D io.jxcore.node.StreamCopyingThread:  id: 85
,06-23 11:34:53.452  3486  4396 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-23 11:34:53.452  3486  4396 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4350, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-23 11:34:53.452  3486  4396 D BatteryService: online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:197
06-23 11:34:53.452  3486  3486 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-23 11:34:53.452  3486  3486 I MotionRecognitionService: Plugged
06-23 11:34:53.452  3486  3486 D MotionRecognitionService:   cableConnection= 1
06-23 11:34:53.452  3486  3486 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-23 11:34:53.452  3486  3486 D MotionRecognitionService: skip setTransmitPower. 
,06-23 11:34:53.462  3486  3852 D WifiController: ApOrStaEnabledState  msg.what= 155652
,06-23 11:34:53.462  3928  3928 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-23 11:34:53.462  3928  3928 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-23 11:34:53.462  3928  3928 D PowerUI : priorPlugType = 2 mPlugType =  2
,06-23 11:34:53.482  3928  3928 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-23 11:34:53.482  4857  4857 D CommonServiceConfiguration: getStringValueSetting
,06-23 11:34:53.482  3928  3928 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-23 11:34:53.492  4857  4857 D BatteryMonitor: new battery level: 100
,06-23 11:34:53.492  4809  4809 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-23 11:34:53.492  4809  9468 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,06-23 11:34:54.592  9374  9928 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 273, thread name: testCopyBigData thread). Connection data: Peer properties: [0:0:0:0:0:0].
06-23 11:34:54.592  9374  9928 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
06-23 11:34:54.592  9374  9928 D io.jxcore.node.StreamCopyingThread:  id: 85
06-23 11:34:54.592  9374  9928 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
06-23 11:34:54.592  9374  9928 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
06-23 11:34:54.592  9374  9928 D io.jxcore.node.StreamCopyingThread:  id: 85
06-23 11:34:54.592  9374  9928 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
06-23 11:34:54.592  9374  9928 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
06-23 11:34:54.592  9374  9928 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
06-23 11:34:54.592  9374  9928 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
06-23 11:34:54.592  9374  9928 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
06-23 11:34:54.592  9374  9928 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 273, name: testCopyBigData thread). Connection data: Peer properties: [0:0:0:0:0:0].
06-23 11:34:54.592  9374  9928 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
06-23 11:34:54.592  9374  9928 D io.jxcore.node.StreamCopyingThread:  id: 85 .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,06-23 11:34:54.732  3486  6038 D SSRM:n  : SIOP:: AP = 360, PST = 332 (W:6), CP = 264, CUR = 10, LCD = 40
,06-23 11:34:57.012  9374  9439 I StreamCopyingThreadTest: Starting test: testRunNotify
,06-23 11:34:57.012  9374  9931 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 275, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
06-23 11:34:57.012  9374  9931 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
06-23 11:34:57.012  9374  9931 D io.jxcore.node.StreamCopyingThread:  id: 86
06-23 11:34:57.012  9374  9931 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 275, thread name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
06-23 11:34:57.012  9374  9931 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
06-23 11:34:57.012  9374  9931 D io.jxcore.node.StreamCopyingThread:  id: 86
06-23 11:34:57.012  9374  9931 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
06-23 11:34:57.012  9374  9931 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
06-23 11:34:57.012  9374  9931 D io.jxcore.node.StreamCopyingThread:  id: 86
06-23 11:34:57.012  9374  9931 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
06-23 11:34:57.012  9374  9931 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
06-23 11:34:57.012  9374  9931 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
06-23 11:34:57.012  9374  9931 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
06-23 11:34:57.012  9374  9931 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
06-23 11:34:57.012  9374  9931 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 275, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
06-23 11:34:57.012  9374  9931 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
06-23 11:34:57.012  9374  9931 D io.jxcore.node.StreamCopyingThread:  id: 86 .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
06-23 11:34:57.012  9374  9439 I StreamCopyingThreadTest: Starting test: testSetBufferSize
06-23 11:34:57.012  9374  9439 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
06-23 11:34:57.012  9374  9439 I StreamCopyingThreadTest: Starting test: testRunWithException
06-23 11:34:57.012  9374  9932 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 279, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
06-23 11:34:57.012  9374  9932 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
06-23 11:34:57.012  9374  9932 D io.jxcore.node.StreamCopyingThread:  id: 89
06-23 11:34:57.012  9374  9932 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 279, thread name: My test thread name): Test exception.
06-23 11:34:57.012  9374  9932 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 279, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
06-23 11:34:57.012  9374  9932 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
06-23 11:34:57.012  9374  9932 D io.jxcore.node.StreamCopyingThread:  id: 89 .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
06-23 11:34:57.012  9374  9932 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
06-23 11:34:57.012  9374  9932 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 279, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
06-23 11:34:57.012  9374  9932 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
06-23 11:34:57.012  9374  9932 D io.jxcore.node.StreamCopyingThread:  id: 89 .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
06-23 11:34:57.012  9374  9439 I jxcore-log: 2017-06-23 09:34:57 - DEBUG UnitTest_app: 'Running unit tests'
06-23 11:34:57.012  9374  9439 I jxcore-log: 
06-23 11:34:57.012  9374  9439 I jxcore-log: *Native ,tests were executed*
06-23 11:34:57.012  9374  9439 I jxcore-log: 
06-23 11:34:57.012  9374  9439 I jxcore-log: Total number of executed tests:  78
06-23 11:34:57.012  9374  9439 I jxcore-log: 
06-23 11:34:57.012  9374  9439 I jxcore-log: Number of passed tests:  76
06-23 11:34:57.012  9374  9439 I jxcore-log: 
06-23 11:34:57.012  9374  9439 I jxcore-log: Number of failed tests:  0
06-23 11:34:57.012  9374  9439 I jxcore-log: 
06-23 11:34:57.012  9374  9439 I jxcore-log: Number of ignored tests:  2
06-23 11:34:57.012  9374  9439 I jxcore-log: 
06-23 11:34:57.012  9374  9439 I jxcore-log: Total duration:  44242
06-23 11:34:57.012  9374  9439 I jxcore-log: 
06-23 11:34:57.012  9374  9439 I jxcore-log: 2017-06-23 09:34:57 - DEBUG UnitTest_app: 'My device name is: 'samsung-SM-G930F''
06-23 11:34:57.012  9374  9439 I jxcore-log: 
06-23 11:34:57.012  9374  9439 I jxcore-log: 2017-06-23 09:34:57 - WARN testUtils: 'myNameCallback not set!'
06-23 11:34:57.012  9374  9439 I jxcore-log: 
,06-23 11:34:58.472  9374  9439 I jxcore-log: 2017-06-23 09:34:58 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: android'
06-23 11:34:58.472  9374  9439 I jxcore-log: 
,06-23 11:34:58.482  9374  9439 I jxcore-log: 2017-06-23 09:34:58 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
06-23 11:34:58.482  9374  9439 I jxcore-log: 
,06-23 11:34:58.492  9374  9439 I jxcore-log: 2017-06-23 09:34:58 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
06-23 11:34:58.492  9374  9439 I jxcore-log: 
,06-23 11:34:58.642  9374  9439 I jxcore-log: 2017-06-23 09:34:58 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
06-23 11:34:58.642  9374  9439 I jxcore-log: 
,06-23 11:34:58.672  9374  9439 I jxcore-log: 2017-06-23 09:34:58 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
06-23 11:34:58.672  9374  9439 I jxcore-log: 
,06-23 11:34:58.682  9374  9439 I jxcore-log: 2017-06-23 09:34:58 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testTests.js'
06-23 11:34:58.682  9374  9439 I jxcore-log: 
,06-23 11:34:58.722  9374  9439 I jxcore-log: 2017-06-23 09:34:58 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testUsn.js'
06-23 11:34:58.722  9374  9439 I jxcore-log: 
,06-23 11:34:58.732  9374  9439 I jxcore-log: 2017-06-23 09:34:58 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
06-23 11:34:58.732  9374  9439 I jxcore-log: 
,06-23 11:34:58.742  9374  9439 I jxcore-log: 2017-06-23 09:34:58 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
06-23 11:34:58.742  9374  9439 I jxcore-log: 
,06-23 11:34:58.782  9374  9439 I jxcore-log: 2017-06-23 09:34:58 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
06-23 11:34:58.782  9374  9439 I jxcore-log: 
,06-23 11:34:58.792  9374  9439 I jxcore-log: 2017-06-23 09:34:58 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
06-23 11:34:58.792  9374  9439 I jxcore-log: 
,06-23 11:34:58.802  9374  9439 I jxcore-log: 2017-06-23 09:34:58 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
06-23 11:34:58.802  9374  9439 I jxcore-log: 
,06-23 11:34:58.802  9374  9439 I jxcore-log: 2017-06-23 09:34:58 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
06-23 11:34:58.802  9374  9439 I jxcore-log: 
,06-23 11:34:59.122  9374  9439 I jxcore-log: 2017-06-23 09:34:59 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
06-23 11:34:59.122  9374  9439 I jxcore-log: 
,06-23 11:34:59.132  9374  9439 I jxcore-log: 2017-06-23 09:34:59 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
06-23 11:34:59.132  9374  9439 I jxcore-log: 
,06-23 11:34:59.192  9374  9439 I jxcore-log: 2017-06-23 09:34:59 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
06-23 11:34:59.192  9374  9439 I jxcore-log: 
,06-23 11:34:59.212  9374  9439 I jxcore-log: 2017-06-23 09:34:59 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
06-23 11:34:59.212  9374  9439 I jxcore-log: 
,06-23 11:34:59.222  9374  9439 I jxcore-log: 2017-06-23 09:34:59 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
06-23 11:34:59.222  9374  9439 I jxcore-log: 
,06-23 11:34:59.252  9374  9439 I jxcore-log: 2017-06-23 09:34:59 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
06-23 11:34:59.252  9374  9439 I jxcore-log: 
,06-23 11:34:59.292  9374  9439 I jxcore-log: 2017-06-23 09:34:59 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
06-23 11:34:59.292  9374  9439 I jxcore-log: 
,06-23 11:34:59.322  9374  9439 I jxcore-log: 2017-06-23 09:34:59 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
06-23 11:34:59.322  9374  9439 I jxcore-log: 
,06-23 11:34:59.352  9374  9439 I jxcore-log: 2017-06-23 09:34:59 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
06-23 11:34:59.352  9374  9439 I jxcore-log: 
,06-23 11:34:59.362  9374  9439 I jxcore-log: 2017-06-23 09:34:59 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
06-23 11:34:59.362  9374  9439 I jxcore-log: 
,06-23 11:34:59.412  9374  9439 I jxcore-log: 2017-06-23 09:34:59 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
06-23 11:34:59.412  9374  9439 I jxcore-log: 
,06-23 11:34:59.432  9374  9439 I jxcore-log: 2017-06-23 09:34:59 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
06-23 11:34:59.432  9374  9439 I jxcore-log: 
,06-23 11:34:59.992  3486  3807 V AlarmManager: Expired Alarm result :8
,06-23 11:34:59.992  3928  3928 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
06-23 11:35:00.002  3928  3928 D KeyguardUpdateMonitor: handleTimeUpdate
,06-23 11:35:00.012  3928  3928 D Clock   : received broadcast android.intent.action.TIME_TICK,
,06-23 11:35:00.062  9374  9439 I jxcore-log: 2017-06-23 09:35:00 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
06-23 11:35:00.062  9374  9439 I jxcore-log: 
,06-23 11:35:00.062  3928  3928 D DateView: received broadcast android.intent.action.TIME_TICK
,06-23 11:35:00.082  9374  9439 I jxcore-log: 2017-06-23 09:35:00 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
06-23 11:35:00.082  9374  9439 I jxcore-log: 
,06-23 11:35:00.092  4622  4622 D [Weather Widget]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,06-23 11:35:00.092  9374  9439 I jxcore-log: 2017-06-23 09:35:00 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
06-23 11:35:00.092  9374  9439 I jxcore-log: 
06-23 11:35:00.092  4622  4622 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EEFA9050249635C043F7E254E316C2550]}
06-23 11:35:00.092  4622  4622 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EAB01DC5C99149A39F887E17599325AFBFF089086AA9902184ADA25758C536FE2]}
06-23 11:35:00.092  9374  9439 I jxcore-log: 2017-06-23 09:35:00 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
06-23 11:35:00.092  9374  9439 I jxcore-log: 
06-23 11:35:00.092  4622  4622 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EFF0B905BDFF72B69FB632A6CB072B41F95D2E6F4F84443284E97F40042D431D8350388453A923ABD8469D82798FA7548]}
06-23 11:35:00.092  4622  4622 D [Weather Widget]  : {[A1AF0F6A1A65A89C43D705938923D0FEFB71880C4E84718DA0A3E1F383E54FB27A4284D9BEDF7BAA2ABFFE671EB65C640578FF9DE16A23BFE3280A9DCDBB09A0930C2946B4A4DB933C502C8761FBEA50704C777D43C836F72ECCE6B5A21A213DA0A46164AC1F9A2A8026A390D761E721]}
06-23 11:35:00.092  4622  4622 D [Weather Widget]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,06-23 11:35:00.112  9374  9439 I jxcore-log: 2017-06-23 09:35:00 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
06-23 11:35:00.112  9374  9439 I jxcore-log: 
,06-23 11:35:00.132  9374  9439 I jxcore-log: 2017-06-23 09:35:00 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
06-23 11:35:00.132  9374  9439 I jxcore-log: 
,06-23 11:35:00.142  9374  9439 I jxcore-log: 2017-06-23 09:35:00 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
06-23 11:35:00.142  9374  9439 I jxcore-log: 
,06-23 11:35:00.152  9374  9439 I jxcore-log: 2017-06-23 09:35:00 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
06-23 11:35:00.152  9374  9439 I jxcore-log: 
,06-23 11:35:00.162  9374  9439 I jxcore-log: 2017-06-23 09:35:00 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
06-23 11:35:00.162  9374  9439 I jxcore-log: 
,06-23 11:35:00.172  9374  9439 I jxcore-log: 2017-06-23 09:35:00 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
06-23 11:35:00.172  9374  9439 I jxcore-log: 
,06-23 11:35:00.182  9374  9439 I jxcore-log: 2017-06-23 09:35:00 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
06-23 11:35:00.182  9374  9439 I jxcore-log: 
,06-23 11:35:00.202  9374  9439 I jxcore-log: 2017-06-23 09:35:00 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
06-23 11:35:00.202  9374  9439 I jxcore-log: 
,06-23 11:35:00.212  9374  9439 I jxcore-log: 2017-06-23 09:35:00 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
06-23 11:35:00.212  9374  9439 I jxcore-log: 
,06-23 11:35:00.372  9374  9439 I jxcore-log: 2017-06-23 09:35:00 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
06-23 11:35:00.372  9374  9439 I jxcore-log: 
,06-23 11:35:00.452  9374  9439 I jxcore-log: 2017-06-23 09:35:00 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testHttp.js'
06-23 11:35:00.452  9374  9439 I jxcore-log: 
,06-23 11:35:00.452  9374  9439 I jxcore-log: 2017-06-23 09:35:00 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testSSDPServer.js'
06-23 11:35:00.452  9374  9439 I jxcore-log: 
,06-23 11:35:00.462  9374  9439 D BluetoothAdapter: STATE_ON
,06-23 11:35:00.472  9374  9439 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,06-23 11:35:00.472  9374  9439 I jxcore-log: 2017-06-23 09:35:00 - INFO testUtils: 'BLE multiple advertisement supported'
06-23 11:35:00.472  9374  9439 I jxcore-log: 
06-23 11:35:00.472  9374  9439 I jxcore-log: 2017-06-23 09:35:00 - DEBUG UnitTest_app: 'Unit Test app is loaded'
06-23 11:35:00.472  9374  9439 I jxcore-log: 
,06-23 11:35:00.482  9374  9439 I jxcore-log: 2017-06-23 09:35:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"NG700"}'
06-23 11:35:00.482  9374  9439 I jxcore-log: 
,06-23 11:35:00.482  9374  9439 I jxcore-log: 2017-06-23 09:35:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
06-23 11:35:00.482  9374  9439 I jxcore-log: 
06-23 11:35:00.482  9374  9439 I jxcore-log: 2017-06-23 09:35:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"NG700"}'
06-23 11:35:00.482  9374  9439 I jxcore-log: 
06-23 11:35:00.482  9374  9439 I jxcore-log: 2017-06-23 09:35:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
06-23 11:35:00.482  9374  9439 I jxcore-log: 
06-23 11:35:00.482  9374  9439 I jxcore-log: 2017-06-23 09:35:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"NG700"}'
06-23 11:35:00.482  9374  9439 I jxcore-log: 
06-23 11:35:00.482  9374  9439 I jxcore-log: 2017-06-23 09:35:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
06-23 11:35:00.482  9374  9439 I jxcore-log: 
06-23 11:35:00.482  9374  9439 I jxcore-log: 2017-06-23 09:35:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":null,"ssidName":null}'
06-23 11:35:00.482  9374  9439 I jxcore-log: 
,06-23 11:35:00.482  9374  9439 I jxcore-log: 2017-06-23 09:35:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
06-23 11:35:00.482  9374  9439 I jxcore-log: 
06-23 11:35:00.482  9374  9439 I jxcore-log: 2017-06-23 09:35:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare","bssidName":null,"ssidName":null}'
06-23 11:35:00.482  9374  9439 I jxcore-log: 
06-23 11:35:00.482  9374  9439 I jxcore-log: 2017-06-23 09:35:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
06-23 11:35:00.482  9374  9439 I jxcore-log: 
06-23 11:35:00.482  9374  9439 I jxcore-log: 2017-06-23 09:35:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":null,"ssidName":null}'
06-23 11:35:00.482  9374  9439 I jxcore-log: 
06-23 11:35:00.482  9374  9439 I jxcore-log: 2017-06-23 09:35:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
06-23 11:35:00.482  9374  9439 I jxcore-log: 
06-23 11:35:00.482  9374  9439 I jxcore-log: 2017-06-23 09:35:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"NG700"}'
06-23 11:35:00.482  9374  9439 I jxcore-log: 
06-23 11:35:00.482  9374  9439 I jxcore-log: 2017-06-23 09:35:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
06-23 11:35:00.482  9374  9439 I jxcore-log: 
,06-23 11:35:00.492  9374  9374 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 68 : UIApp is all set and ready!
,06-23 11:35:00.492  9374  9374 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,06-23 11:35:00.522  9374  9439 I jxcore-log: 2017-06-23 09:35:00 - INFO CoordinatedClient: 'Connecting to coordination server on http://192.168.1.150:3000/'
06-23 11:35:00.522  9374  9439 I jxcore-log: 
,06-23 11:35:00.612  9374  9439 I jxcore-log: 2017-06-23 09:35:00 - DEBUG CoordinatedClient: 'connected to the test server'
06-23 11:35:00.612  9374  9439 I jxcore-log: 
,06-23 11:35:03.512  3486  4396 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-23 11:35:03.512  3486  4396 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4358, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-23 11:35:03.512  3486  4396 D BatteryService: online:4, current avg:-68, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:215
06-23 11:35:03.512  3486  3486 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-23 11:35:03.522  3486  3486 I MotionRecognitionService: Plugged
,06-23 11:35:03.522  3486  3486 D MotionRecognitionService:   cableConnection= 1
06-23 11:35:03.522  3486  3486 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-23 11:35:03.522  3486  3486 D MotionRecognitionService: skip setTransmitPower. 
,06-23 11:35:03.522  3486  3852 D WifiController: ApOrStaEnabledState  msg.what= 155652
,06-23 11:35:03.532  3928  3928 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-23 11:35:03.532  3928  3928 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-23 11:35:03.532  3928  3928 D PowerUI : priorPlugType = 2 mPlugType =  2
,06-23 11:35:03.552  4857  4857 D CommonServiceConfiguration: getStringValueSetting
,06-23 11:35:03.562  4857  4857 D BatteryMonitor: new battery level: 100
,06-23 11:35:03.562  4809  4809 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-23 11:35:03.562  4809  9468 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,06-23 11:35:03.562  3928  3928 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-23 11:35:03.562  3928  3928 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-23 11:35:04.752  3486  6038 D SSRM:n  : SIOP:: AP = 370, PST = 336 (W:6), CP = 277, CUR = -68, LCD = 40
,06-23 11:35:09.352  3486  6077 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-23 11:35:13.562  3486  4285 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-23 11:35:13.572  3486  4285 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4357, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-23 11:35:13.572  3486  4285 D BatteryService: online:4, current avg:85, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:176
06-23 11:35:13.572  3486  3486 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-23 11:35:13.572  3486  3486 I MotionRecognitionService: Plugged,
06-23 11:35:13.572  3486  3486 D MotionRecognitionService:   cableConnection= 1
,06-23 11:35:13.572  3486  3486 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-23 11:35:13.572  3486  3486 D MotionRecognitionService: skip setTransmitPower. 
,06-23 11:35:13.582  3486  3852 D WifiController: ApOrStaEnabledState  msg.what= 155652
,06-23 11:35:13.582  3928  3928 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-23 11:35:13.582  3928  3928 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-23 11:35:13.582  3928  3928 D PowerUI : priorPlugType = 2 mPlugType =  2
,06-23 11:35:13.602  3486  4128 E Watchdog: !@Sync 8 [06-23 11:35:13.611]
,06-23 11:35:13.602  4857  4857 D CommonServiceConfiguration: getStringValueSetting
,06-23 11:35:13.612  4857  4857 D BatteryMonitor: new battery level: 100
,06-23 11:35:13.622  4809  4809 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-23 11:35:13.622  4809  9468 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,06-23 11:35:13.622  3928  3928 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-23 11:35:13.622  3928  3928 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-23 11:35:14.772  3486  6038 D SSRM:n  : SIOP:: AP = 330, PST = 336 (W:14), CP = 274, CUR = 85, LCD = 40
,06-23 11:35:14.972  4339  4428 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-23 11:35:14.972  4339  4428 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-23 11:35:23.062  3486  3807 V AlarmManager: Expired Alarm result :4
,06-23 11:35:23.632  3486  3504 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-23 11:35:23.632  3486  3504 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4356, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-23 11:35:23.632  3486  3504 D BatteryService: online:4, current avg:135, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:157
06-23 11:35:23.632  3486  3486 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-23 11:35:23.632  3486  3486 I MotionRecognitionService: Plugged
,06-23 11:35:23.632  3486  3486 D MotionRecognitionService:   cableConnection= 1
06-23 11:35:23.632  3486  3486 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-23 11:35:23.632  3486  3486 D MotionRecognitionService: skip setTransmitPower. 
,06-23 11:35:23.642  3486  3852 D WifiController: ApOrStaEnabledState  msg.what= 155652
,06-23 11:35:23.642  3928  3928 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-23 11:35:23.642  3928  3928 D KeyguardUpdateMonitor: handleBatteryUpdate
06-23 11:35:23.652  3928  3928 D PowerUI : priorPlugType = 2 mPlugType =  2
,06-23 11:35:23.672  4857  4857 D CommonServiceConfiguration: getStringValueSetting
,06-23 11:35:23.682  4809  4809 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-23 11:35:23.682  4809  9468 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-23 11:35:23.682  4857  4857 D BatteryMonitor: new battery level: 100
,06-23 11:35:23.682  3928  3928 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-23 11:35:23.692  3928  3928 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-23 11:35:24.792  3486  6038 D SSRM:n  : SIOP:: AP = 310, PST = 331 (W:14), CP = 269, CUR = 135, LCD = 40
,06-23 11:35:29.352  3486  6077 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-23 11:35:33.692  3486  3505 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-23 11:35:33.692  3486  3505 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4356, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-23 11:35:33.692  3486  3505 D BatteryService: online:4, current avg:147, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:150
06-23 11:35:33.692  3486  3486 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-23 11:35:33.702  3486  3486 I MotionRecognitionService: Plugged
,06-23 11:35:33.702  3486  3486 D MotionRecognitionService:   cableConnection= 1
06-23 11:35:33.702  3486  3486 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-23 11:35:33.702  3486  3486 D MotionRecognitionService: skip setTransmitPower. 
,06-23 11:35:33.702  3486  3852 D WifiController: ApOrStaEnabledState  msg.what= 155652
,06-23 11:35:33.702  3928  3928 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-23 11:35:33.712  3928  3928 D KeyguardUpdateMonitor: handleBatteryUpdate
06-23 11:35:33.712  3928  3928 D PowerUI : priorPlugType = 2 mPlugType =  2
,06-23 11:35:33.722  4857  4857 D CommonServiceConfiguration: getStringValueSetting
,06-23 11:35:33.732  4857  4857 D BatteryMonitor: new battery level: 100
,06-23 11:35:33.742  4809  4809 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-23 11:35:33.742  4809  9468 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,06-23 11:35:33.742  3928  3928 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-23 11:35:33.742  3928  3928 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-23 11:35:34.822  3486  6038 D SSRM:n  : SIOP:: AP = 310, PST = 330 (W:14), CP = 264, CUR = 147, LCD = 40
,06-23 11:35:43.602  3486  4128 E Watchdog: !@Sync 9 [06-23 11:35:43.613]
,06-23 11:35:43.752  3486  3970 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-23 11:35:43.752  3486  3970 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4355, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-23 11:35:43.752  3486  3970 D BatteryService: online:4, current avg:146, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:140
06-23 11:35:43.752  3486  3486 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-23 11:35:43.752  3486  3486 I MotionRecognitionService: Plugged
,06-23 11:35:43.752  3486  3486 D MotionRecognitionService:   cableConnection= 1
06-23 11:35:43.752  3486  3486 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-23 11:35:43.752  3486  3486 D MotionRecognitionService: skip setTransmitPower. 
,06-23 11:35:43.762  3486  3852 D WifiController: ApOrStaEnabledState  msg.what= 155652,
,06-23 11:35:43.762  3928  3928 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-23 11:35:43.762  3928  3928 D KeyguardUpdateMonitor: handleBatteryUpdate
06-23 11:35:43.762  3928  3928 D PowerUI : priorPlugType = 2 mPlugType =  2
,06-23 11:35:43.782  4857  4857 D CommonServiceConfiguration: getStringValueSetting
,06-23 11:35:43.792  4809  4809 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-23 11:35:43.792  4809  9468 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-23 11:35:43.792  4857  4857 D BatteryMonitor: new battery level: 100
,06-23 11:35:43.802  3928  3928 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-23 11:35:43.812  3928  3928 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-23 11:35:44.842  3486  6038 D SSRM:n  : SIOP:: AP = 300, PST = 330 (W:14), CP = 262, CUR = 146, LCD = 40
,06-23 11:35:49.352  3486  6077 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-23 11:35:53.802  3486  3505 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-23 11:35:53.812  3486  3505 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4357, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-23 11:35:53.812  3486  3505 D BatteryService: online:4, current avg:142, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:130
06-23 11:35:53.812  3486  3486 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-23 11:35:53.812  3486  3486 I MotionRecognitionService: Plugged
,06-23 11:35:53.812  3486  3486 D MotionRecognitionService:   cableConnection= 1
06-23 11:35:53.812  3486  3486 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-23 11:35:53.812  3486  3486 D MotionRecognitionService: skip setTransmitPower. 
,06-23 11:35:53.822  3486  3852 D WifiController: ApOrStaEnabledState  msg.what= 155652
,06-23 11:35:53.822  3928  3928 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-23 11:35:53.822  3928  3928 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-23 11:35:53.822  3928  3928 D PowerUI : priorPlugType = 2 mPlugType =  2
,06-23 11:35:53.852  4857  4857 D CommonServiceConfiguration: getStringValueSetting
,06-23 11:35:53.862  4857  4857 D BatteryMonitor: new battery level: 100
06-23 11:35:53.862  4809  4809 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-23 11:35:53.862  4809  9468 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,06-23 11:35:53.872  3928  3928 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-23 11:35:53.872  3928  3928 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-23 11:35:54.862  3486  6038 D SSRM:n  : SIOP:: AP = 300, PST = 325 (W:14), CP = 260, CUR = 142, LCD = 40
,06-23 11:35:59.992  3486  3807 V AlarmManager: Expired Alarm result :8
,06-23 11:36:00.002  3928  3928 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
06-23 11:36:00.002  3928  3928 D KeyguardUpdateMonitor: handleTimeUpdate
,06-23 11:36:00.022  3928  3928 D Clock   : received broadcast android.intent.action.TIME_TICK
,06-23 11:36:00.082  3928  3928 D DateView: received broadcast android.intent.action.TIME_TICK
,06-23 11:36:00.112  4622  4622 D [Weather Widget]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,06-23 11:36:00.112  4622  4622 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EEFA9050249635C043F7E254E316C2550]}
,06-23 11:36:00.112  4622  4622 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EAB01DC5C99149A39F887E17599325AFBFF089086AA9902184ADA25758C536FE2]}
,06-23 11:36:00.112  4622  4622 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EFF0B905BDFF72B69FB632A6CB072B41F95D2E6F4F84443284E97F40042D431D8350388453A923ABD8469D82798FA7548]}
,06-23 11:36:00.112  4622  4622 D [Weather Widget]  : {[A1AF0F6A1A65A89C43D705938923D0FEFB71880C4E84718DA0A3E1F383E54FB27A4284D9BEDF7BAA2ABFFE671EB65C640578FF9DE16A23BFE3280A9DCDBB09A0930C2946B4A4DB933C502C8761FBEA50704C777D43C836F72ECCE6B5A21A213DA0A46164AC1F9A2A8026A390D761E721]}
,06-23 11:36:00.112  4622  4622 D [Weather Widget]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,06-23 11:36:03.872  3486  3505 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-23 11:36:03.872  3486  3505 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4356, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-23 11:36:03.872  3486  3505 D BatteryService: online:4, current avg:137, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:132
06-23 11:36:03.872  3486  3486 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-23 11:36:03.882  3486  3486 I MotionRecognitionService: Plugged
,06-23 11:36:03.882  3486  3486 D MotionRecognitionService:   cableConnection= 1
06-23 11:36:03.882  3486  3486 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-23 11:36:03.882  3486  3486 D MotionRecognitionService: skip setTransmitPower. 
,06-23 11:36:03.882  3486  3852 D WifiController: ApOrStaEnabledState  msg.what= 155652
,06-23 11:36:03.892  3928  3928 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-23 11:36:03.892  3928  3928 D PowerUI : priorPlugType = 2 mPlugType =  2
06-23 11:36:03.892  3928  3928 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-23 11:36:03.912  4857  4857 D CommonServiceConfiguration: getStringValueSetting
,06-23 11:36:03.922  4857  4857 D BatteryMonitor: new battery level: 100
,06-23 11:36:03.922  4809  4809 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-23 11:36:03.922  4809  9468 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,06-23 11:36:03.932  3928  3928 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-23 11:36:03.932  3928  3928 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-23 11:36:04.892  3486  6038 D SSRM:n  : SIOP:: AP = 300, PST = 320 (W:14), CP = 258, CUR = 137, LCD = 40
,06-23 11:36:09.362  3486  6077 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-23 11:36:11.392  3486  3799 D TimaService: TIMA: TimaService scheduler is intialized. 
06-23 11:36:11.392  3486  3799 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-23 11:36:11.392  3486  3798 D TimaService: TimaServiceHandler.handleMessage what =1
,06-23 11:36:11.402  3486  3799 I TLC_TIMA_PKM_initialize: initializing...
06-23 11:36:11.402  3486  3799 I TLC_TIMA_PKM_initialize: root = 0, root_strlen = 1
,06-23 11:36:11.402  3486  3799 I TLC_TIMA_PKM_initialize: process = ffffffff00000000000000000000000a, process_strlen = 32
06-23 11:36:11.402  3486  3799 I TZ: mc_tlc_communication: input max_sendmsg_size = 262196
06-23 11:36:11.402  3486  3799 I TZ: mc_tlc_communication: input max_recvmsg_size = 262196
06-23 11:36:11.402  3486  3799 I TZ: mc_tlc_communication: root = 0, root_len = 1
06-23 11:36:11.402  3486  3799 I TZ: mc_tlc_communication: process = ffffffff00000000000000000000000a, process_strlen = 32
06-23 11:36:11.402  3486  3799 I TZ: mc_tlc_communication: aligned max_sendmsg_size = 262208
06-23 11:36:11.402  3486  3799 I TZ: mc_tlc_communication: aligned max_recvmsg_size = 262208
,06-23 11:36:11.402  3486  3799 I TZ: mc_tlc_communication: device_id = 0x0
06-23 11:36:11.402  3486  3799 I TZ: mc_tlc_communication: tlc_open() was called
06-23 11:36:11.402  3486  3799 I TZ: mc_tlc_communication: Opening MobiCore device
06-23 11:36:11.402  3486  3799 I TeeDriverClient: driver client open [hardware/samsung_slsi/exynos8890/mobicore/ClientLib/src/driver_client.cpp:103]
06-23 11:36:11.402  3486  3799 I TZ: mc_tlc_communication: Allocating message buffer for TCI
06-23 11:36:11.402  3486  3799 I TZ: mc_tlc_communication: Opening the session
,06-23 11:36:11.452  3486  3799 I TZ: mc_tlc_communication: tlc_open() succeeded
06-23 11:36:11.452  3486  3799 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info1
,06-23 11:36:11.462  3486  3799 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info2
,06-23 11:36:11.492  3486  3799 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info3
,06-23 11:36:11.502  3486  3799 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info4
,06-23 11:36:11.502  3486  3799 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,06-23 11:36:13.602  3486  4128 E Watchdog: !@Sync 10 [06-23 11:36:13.615]
,06-23 11:36:14.922  3486  6038 D SSRM:n  : SIOP:: AP = 300, PST = 318 (W:14), CP = 257, CUR = 137, LCD = 40
,06-23 11:36:15.072  3486  3807 V AlarmManager: Expired Alarm result :4
,06-23 11:36:15.092  9596  9596 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
06-23 11:36:15.092  9596  9596 I wpa_supplicant: P2P: Current p2p state = IDLE
,06-23 11:36:15.102  4339  4428 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-23 11:36:15.102  4339  4428 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-23 11:36:15.112  3486  3799 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
06-23 11:36:15.112  3486  3799 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-23 11:36:15.112  3486  3799 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-23 11:36:15.112  3486  3799 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-23 11:36:15.122  9957  9957 E Zygote  : v2
06-23 11:36:15.122  9957  9957 I libpersona: KNOX_SDCARD checking this for 1000
06-23 11:36:15.122  9957  9957 I libpersona: KNOX_SDCARD not a persona
,06-23 11:36:15.122  3486  3807 I ActivityManager: Start proc 9957:com.mobeam.barcodeService/1000 for service com.mobeam.barcodeService/.system.AppService
,06-23 11:36:15.122  9957  9957 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,06-23 11:36:15.122  9957  9957 E Zygote  : accessInfo : 0
,06-23 11:36:15.162  9957  9957 D TimaKeyStoreProvider: TimaSignature is unavailable
06-23 11:36:15.162  9957  9957 D ActivityThread: Added TimaKeyStore provider
06-23 11:36:15.162  9596  9596 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,06-23 11:36:15.192  9957  9957 W ResourcesManager: getTopLevelResources: /system/app/BeamService/BeamService.apk / 1.0 running in com.mobeam.barcodeService rsrc of package com.mobeam.barcodeService
,06-23 11:36:15.192  3486  4395 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
06-23 11:36:15.192  9957  9957 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,06-23 11:36:15.202  9957  9957 D ResourcesManager: For user 0 new overlays fetched Null
,06-23 11:36:15.202  9957  9957 I InjectionManager: Inside getClassLibPath caller 
,06-23 11:36:15.212  9957  9957 W System  : ClassLoader referenced unknown path: /system/app/BeamService/lib/arm64
,06-23 11:36:15.212  9957  9957 D InjectionManager: InjectionManager
,06-23 11:36:15.212  9957  9957 D InjectionManager: fillFeatureStoreMap com.mobeam.barcodeService
06-23 11:36:15.212  9957  9957 I InjectionManager: Constructor com.mobeam.barcodeService, Feature store :{}
06-23 11:36:15.212  9957  9957 I InjectionManager: featureStore :{}
,06-23 11:36:15.242  3486  4049 I ActivityManager: Killing 9199:com.samsung.android.app.filterinstaller/1000 (adj 15): DHA:empty #33
,06-23 11:36:15.272  3486  4379 D ActivityManager: cleanUpApplicationRecord -- 9199
06-23 11:36:15.272  3486  4379 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.filterinstaller, Auto Run ON
,06-23 11:36:19.192  3151  3622 D Netd    : Iface wlan0 link up
,06-23 11:36:19.202  3486  3571 D Tethering: interfaceLinkStateChanged wlan0, true
06-23 11:36:19.202  3486  3571 D Tethering: interfaceStatusChanged wlan0, true
,06-23 11:36:19.202  9596  9596 I wpa_supplicant: nl80211: Received scan results (14 BSSes)
,06-23 11:36:19.202  4857  4872 D PdnController: Interface Changed wlan0 link up
06-23 11:36:19.202  9596  9596 I wpa_supplicant: scan_only_handler, so autoscan_notify() !!!
,06-23 11:36:19.212  3486  3848 D WifiP2pService: InactiveState{ what=147461 }
,06-23 11:36:19.212  3486  3848 D WifiP2pService: P2pEnabledState{ what=147461 }
06-23 11:36:19.212  3486  3848 D WifiP2pService: DefaultState{ what=147461 }
,06-23 11:36:19.242  3486  3486 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.SCAN_RESULTS
,06-23 11:36:19.242  3486  3567 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{eba6aea u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{33215a9 3928:com.android.systemui/u0a62}
,06-23 11:36:24.952  3486  6038 D SSRM:n  : SIOP:: AP = 300, PST = 316 (W:14), CP = 257, CUR = 137, LCD = 40
,06-23 11:36:29.362  3486  6077 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-23 11:36:33.922  3486  4257 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-23 11:36:33.922  3486  4257 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4347, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-23 11:36:33.922  3486  4257 D BatteryService: online:4, current avg:9, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
06-23 11:36:33.922  3486  3486 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-23 11:36:33.922  3486  3486 I MotionRecognitionService: Plugged
,06-23 11:36:33.922  3486  3486 D MotionRecognitionService:   cableConnection= 1
06-23 11:36:33.922  3486  3486 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-23 11:36:33.922  3486  3486 D MotionRecognitionService: skip setTransmitPower. 
,06-23 11:36:33.932  3486  3852 D WifiController: ApOrStaEnabledState  msg.what= 155652
,06-23 11:36:33.932  3928  3928 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-23 11:36:33.932  3928  3928 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-23 11:36:33.932  3928  3928 D PowerUI : priorPlugType = 2 mPlugType =  2
,06-23 11:36:33.952  4857  4857 D CommonServiceConfiguration: getStringValueSetting
,06-23 11:36:33.962  4809  4809 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-23 11:36:33.962  4809  9468 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,06-23 11:36:33.962  4857  4857 D BatteryMonitor: new battery level: 100
,06-23 11:36:33.972  3928  3928 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-23 11:36:33.982  3928  3928 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-23 11:36:34.972  3486  6038 D SSRM:n  : SIOP:: AP = 300, PST = 314 (W:14), CP = 256, CUR = 9, LCD = 40
,06-23 11:36:39.302  8697  8742 W PlayEventLogger: No account for auth token provided
,06-23 11:36:39.312  8697  8742 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
06-23 11:36:39.312  8697  8742 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-23 11:36:39.312  3151  3625 D EnterpriseController: netId is 0
06-23 11:36:39.312  3151  3625 D Netd    : getNetworkForDns: using netid 503 for uid 10032
,06-23 11:36:39.812  9374  9439 I jxcore-log: TAP version 13
06-23 11:36:39.812  9374  9439 I jxcore-log: 
,06-23 11:36:39.842  9374  9439 I jxcore-log: # setup
06-23 11:36:39.842  9374  9439 I jxcore-log: 
,06-23 11:36:39.882  9374  9439 I jxcore-log: # closeAll can close even when connections open
06-23 11:36:39.882  9374  9439 I jxcore-log: 
,06-23 11:36:40.542  9374  9439 I jxcore-log: 2017-06-23 09:36:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
06-23 11:36:40.542  9374  9439 I jxcore-log: 
,06-23 11:36:40.572  9374  9439 I jxcore-log: ok 1 not possible to connect to the server anymore
06-23 11:36:40.572  9374  9439 I jxcore-log: 
,06-23 11:36:40.582  9374  9439 I jxcore-log: # teardown
06-23 11:36:40.582  9374  9439 I jxcore-log: 
,06-23 11:36:41.442  9374  9439 I jxcore-log: # setup
06-23 11:36:41.442  9374  9439 I jxcore-log: 
,06-23 11:36:41.472  9374  9439 I jxcore-log: # closeAll with promise
06-23 11:36:41.472  9374  9439 I jxcore-log: 
,06-23 11:36:41.962  9374  9439 I jxcore-log: 2017-06-23 09:36:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
06-23 11:36:41.962  9374  9439 I jxcore-log: 
,06-23 11:36:41.992  9374  9439 I jxcore-log: ok 2 not possible to connect to the server anymore
06-23 11:36:41.992  9374  9439 I jxcore-log: 
,06-23 11:36:42.002  9374  9439 I jxcore-log: # teardown
06-23 11:36:42.002  9374  9439 I jxcore-log: 
,06-23 11:36:42.502  9374  9439 I jxcore-log: # setup
06-23 11:36:42.502  9374  9439 I jxcore-log: 
,06-23 11:36:42.982  9374  9439 I jxcore-log: # closeAll properly throws when closing a non open server with eatNotRunning set to false
06-23 11:36:42.982  9374  9439 I jxcore-log: 
,06-23 11:36:43.612  3486  4128 E Watchdog: !@Sync 11 [06-23 11:36:43.616]
,06-23 11:36:43.942  9374  9439 I jxcore-log: 2017-06-23 09:36:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
06-23 11:36:43.942  9374  9439 I jxcore-log: 
,06-23 11:36:43.952  9374  9439 I jxcore-log: ok 3 Got the right error
06-23 11:36:43.952  9374  9439 I jxcore-log: 
,06-23 11:36:43.962  9374  9439 I jxcore-log: # teardown
06-23 11:36:43.962  9374  9439 I jxcore-log: 
,06-23 11:36:45.002  3486  6038 D SSRM:n  : SIOP:: AP = 300, PST = 312 (W:14), CP = 255, CUR = 9, LCD = 40
,06-23 11:36:46.372  9374  9439 I jxcore-log: # setup
06-23 11:36:46.372  9374  9439 I jxcore-log: 
,06-23 11:36:46.882  3928  4125 D NetworkController.MobileSignalController(0/2147483643): onSignalStrengthsChanged signalStrength=SignalStrength: 12 99 -12 -200 -12 -200 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 0x4 gsm|lte level=4
,06-23 11:36:46.882  3928  4125 D NetworkController.MobileSignalController(0/2147483643): getMobileIconGroup(): 0
,06-23 11:36:46.892  4809  4809 D HeadsetPhoneState: Signal level : previous=4 curr=4
,06-23 11:36:48.982  9374  9439 I jxcore-log: # closeAll works even with a server that is not listening yet witheatNotRunning set to true
06-23 11:36:48.982  9374  9439 I jxcore-log: 
,06-23 11:36:49.362  3486  6077 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-23 11:36:50.422  9374  9439 I jxcore-log: 2017-06-23 09:36:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
06-23 11:36:50.422  9374  9439 I jxcore-log: 
,06-23 11:36:50.442  9374  9439 I jxcore-log: # teardown
06-23 11:36:50.442  9374  9439 I jxcore-log: 
,06-23 11:36:55.022  3486  6038 D SSRM:n  : SIOP:: AP = 290, PST = 309 (W:14), CP = 255, CUR = 9, LCD = 40
,06-23 11:36:59.772  9374  9439 I jxcore-log: # setup
06-23 11:36:59.772  9374  9439 I jxcore-log: 
,06-23 11:36:59.912  9374  9439 I jxcore-log: # Call of onCheckpointReached handler on a single db change
06-23 11:36:59.912  9374  9439 I jxcore-log: 
,06-23 11:36:59.922  9374  9439 I jxcore-log: 2017-06-23 09:36:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
06-23 11:36:59.922  9374  9439 I jxcore-log: 
,06-23 11:36:59.992  3486  3807 V AlarmManager: Expired Alarm result :8
,06-23 11:36:59.992  3928  3928 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
06-23 11:36:59.992  3928  3928 D KeyguardUpdateMonitor: handleTimeUpdate
,06-23 11:37:00.002  3928  3928 D Clock   : received broadcast android.intent.action.TIME_TICK
,06-23 11:37:00.052  3928  3928 D DateView: received broadcast android.intent.action.TIME_TICK
,06-23 11:37:00.082  4622  4622 D [Weather Widget]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,06-23 11:37:00.082  4622  4622 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EEFA9050249635C043F7E254E316C2550]}
,06-23 11:37:00.082  4622  4622 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EAB01DC5C99149A39F887E17599325AFBFF089086AA9902184ADA25758C536FE2]}
,06-23 11:37:00.082  4622  4622 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EFF0B905BDFF72B69FB632A6CB072B41F95D2E6F4F84443284E97F40042D431D8350388453A923ABD8469D82798FA7548]}
,06-23 11:37:00.082  4622  4622 D [Weather Widget]  : {[A1AF0F6A1A65A89C43D705938923D0FEFB71880C4E84718DA0A3E1F383E54FB27A4284D9BEDF7BAA2ABFFE671EB65C640578FF9DE16A23BFE3280A9DCDBB09A0930C2946B4A4DB933C502C8761FBEA50704C777D43C836F72ECCE6B5A21A213DA0A46164AC1F9A2A8026A390D761E721]}
,06-23 11:37:00.082  4622  4622 D [Weather Widget]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,06-23 11:37:03.742  9374  9439 I jxcore-log: # teardown
06-23 11:37:03.742  9374  9439 I jxcore-log: 
,06-23 11:37:03.972  3486  3505 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-23 11:37:03.972  3486  3505 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-23 11:37:03.972  3486  3505 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
06-23 11:37:03.972  3486  3486 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-23 11:37:03.972  3486  3486 I MotionRecognitionService: Plugged
,06-23 11:37:03.972  3486  3486 D MotionRecognitionService:   cableConnection= 1
06-23 11:37:03.972  3486  3486 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-23 11:37:03.972  3486  3486 D MotionRecognitionService: skip setTransmitPower. 
,06-23 11:37:03.982  3486  3852 D WifiController: ApOrStaEnabledState  msg.what= 155652
,06-23 11:37:03.982  3928  3928 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-23 11:37:03.982  3928  3928 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-23 11:37:03.992  3928  3928 D PowerUI : priorPlugType = 2 mPlugType =  2
,06-23 11:37:04.002  4857  4857 D CommonServiceConfiguration: getStringValueSetting
,06-23 11:37:04.022  4857  4857 D BatteryMonitor: new battery level: 100
,06-23 11:37:04.022  3928  3928 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-23 11:37:04.022  3928  3928 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-23 11:37:04.022  4809  4809 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-23 11:37:04.022  4809  9468 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,06-23 11:37:05.052  3486  6038 D SSRM:n  : SIOP:: AP = 290, PST = 306 (W:14), CP = 254, LCD = 40
,06-23 11:37:07.072  9374  9439 I jxcore-log: # setup
06-23 11:37:07.072  9374  9439 I jxcore-log: 
,06-23 11:37:09.362  3486  6077 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-23 11:37:10.782  9374  9439 I jxcore-log: # Call of multiple onCheckpointReached handlers on a single db change
06-23 11:37:10.782  9374  9439 I jxcore-log: 
,06-23 11:37:10.792  9374  9439 I jxcore-log: 2017-06-23 09:37:10 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
06-23 11:37:10.792  9374  9439 I jxcore-log: 
,06-23 11:37:13.612  3486  4128 E Watchdog: !@Sync 12 [06-23 11:37:13.618]
,06-23 11:37:15.072  3486  6038 D SSRM:n  : SIOP:: AP = 290, PST = 303 (W:14), CP = 254, LCD = 40
,06-23 11:37:15.212  4339  4428 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-23 11:37:15.212  4339  4428 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-23 11:37:15.272  4339  4428 E ContactsProvider_EventLog: Flush buffer to file cnt : 3 size : 0Kb duration : 57ms lastUpdatedAfter : 170452ms
,06-23 11:37:25.102  3486  6038 D SSRM:n  : SIOP:: AP = 290, PST = 300 (W:14), CP = 253, LCD = 40
,06-23 11:37:29.362  3486  6077 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-23 11:37:34.012  3486  4396 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-23 11:37:34.012  3486  4396 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-23 11:37:34.022  3486  4396 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
06-23 11:37:34.022  3486  3486 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-23 11:37:34.022  3486  3486 I MotionRecognitionService: Plugged
,06-23 11:37:34.022  3486  3486 D MotionRecognitionService:   cableConnection= 1
06-23 11:37:34.022  3486  3486 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-23 11:37:34.022  3486  3486 D MotionRecognitionService: skip setTransmitPower. 
,06-23 11:37:34.032  3486  3852 D WifiController: ApOrStaEnabledState  msg.what= 155652
,06-23 11:37:34.032  3928  3928 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-23 11:37:34.032  3928  3928 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-23 11:37:34.032  3928  3928 D PowerUI : priorPlugType = 2 mPlugType =  2
,06-23 11:37:34.052  4857  4857 D CommonServiceConfiguration: getStringValueSetting
,06-23 11:37:34.062  4857  4857 D BatteryMonitor: new battery level: 100
,06-23 11:37:34.062  4809  4809 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-23 11:37:34.062  4809  9468 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,06-23 11:37:34.072  3928  3928 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-23 11:37:34.072  3928  3928 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-23 11:37:35.122  3486  6038 D SSRM:n  : SIOP:: AP = 290, PST = 297 (W:14), CP = 253, LCD = 40
,06-23 11:37:39.542  9374  9439 I jxcore-log: # teardown
06-23 11:37:39.542  9374  9439 I jxcore-log: 
,06-23 11:37:43.612  3486  4128 E Watchdog: !@Sync 13 [06-23 11:37:43.620]
,06-23 11:37:45.152  3486  6038 D SSRM:n  : SIOP:: AP = 290, PST = 296 (W:14), CP = 252, LCD = 40
,06-23 11:37:49.362  3486  6077 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-23 11:37:55.182  3486  6038 D SSRM:n  : SIOP:: AP = 290, PST = 295 (W:14), CP = 252, LCD = 40
,06-23 11:37:59.992  3486  3807 V AlarmManager: Expired Alarm result :8
,06-23 11:38:00.002  3928  3928 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,06-23 11:38:00.002  3928  3928 D KeyguardUpdateMonitor: handleTimeUpdate
,06-23 11:38:00.022  3928  3928 D Clock   : received broadcast android.intent.action.TIME_TICK
,06-23 11:38:00.072  3928  3928 D DateView: received broadcast android.intent.action.TIME_TICK
,06-23 11:38:00.102  4622  4622 D [Weather Widget]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,06-23 11:38:00.102  4622  4622 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EEFA9050249635C043F7E254E316C2550]}
,06-23 11:38:00.102  4622  4622 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EAB01DC5C99149A39F887E17599325AFBFF089086AA9902184ADA25758C536FE2]}
,06-23 11:38:00.112  4622  4622 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EFF0B905BDFF72B69FB632A6CB072B41F95D2E6F4F84443284E97F40042D431D8350388453A923ABD8469D82798FA7548]}
,06-23 11:38:00.112  4622  4622 D [Weather Widget]  : {[A1AF0F6A1A65A89C43D705938923D0FEFB71880C4E84718DA0A3E1F383E54FB27A4284D9BEDF7BAA2ABFFE671EB65C640578FF9DE16A23BFE3280A9DCDBB09A0930C2946B4A4DB933C502C8761FBEA50704C777D43C836F72ECCE6B5A21A213DA0A46164AC1F9A2A8026A390D761E721]}
,06-23 11:38:00.112  4622  4622 D [Weather Widget]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,06-23 11:38:04.072  3486  4258 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-23 11:38:04.072  3486  4258 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4344, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-23 11:38:04.072  3486  4258 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
06-23 11:38:04.072  3486  3486 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-23 11:38:04.072  3486  3486 I MotionRecognitionService: Plugged
06-23 11:38:04.072  3486  3486 D MotionRecognitionService:   cableConnection= 1
06-23 11:38:04.072  3486  3486 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-23 11:38:04.072  3486  3486 D MotionRecognitionService: skip setTransmitPower. 
,06-23 11:38:04.082  3486  3852 D WifiController: ApOrStaEnabledState  msg.what= 155652
,06-23 11:38:04.082  3928  3928 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-23 11:38:04.092  3928  3928 D PowerUI : priorPlugType = 2 mPlugType =  2
,06-23 11:38:04.082  3928  3928 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-23 11:38:04.102  4857  4857 D CommonServiceConfiguration: getStringValueSetting
,06-23 11:38:04.112  4857  4857 D BatteryMonitor: new battery level: 100
,06-23 11:38:04.122  4809  4809 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-23 11:38:04.122  4809  9468 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,06-23 11:38:04.132  3928  3928 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-23 11:38:04.132  3928  3928 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-23 11:38:05.202  3486  6038 D SSRM:n  : SIOP:: AP = 290, PST = 294 (W:14), CP = 251, LCD = 40
,06-23 11:38:09.372  3486  6077 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-23 11:38:13.612  3486  4128 E Watchdog: !@Sync 14 [06-23 11:38:13.621]
,06-23 11:38:15.232  3486  6038 D SSRM:n  : SIOP:: AP = 290, PST = 293 (W:14), CP = 251, LCD = 40
,06-23 11:38:15.382  4339  4428 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-23 11:38:15.382  4339  4428 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-23 11:38:25.252  3486  6038 D SSRM:n  : SIOP:: AP = 290, PST = 292 (W:14), CP = 251, LCD = 40
,06-23 11:38:29.372  3486  6077 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-23 11:38:34.122  3486  4396 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-23 11:38:34.122  3486  4396 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4344, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-23 11:38:34.122  3486  4396 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
06-23 11:38:34.122  3486  3486 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-23 11:38:34.132  3486  3486 I MotionRecognitionService: Plugged
,06-23 11:38:34.132  3486  3486 D MotionRecognitionService:   cableConnection= 1
06-23 11:38:34.132  3486  3486 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-23 11:38:34.132  3486  3486 D MotionRecognitionService: skip setTransmitPower. 
,06-23 11:38:34.132  3486  3852 D WifiController: ApOrStaEnabledState  msg.what= 155652
,06-23 11:38:34.132  3928  3928 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-23 11:38:34.132  3928  3928 D KeyguardUpdateMonitor: handleBatteryUpdate
06-23 11:38:34.132  3928  3928 D PowerUI : priorPlugType = 2 mPlugType =  2
,06-23 11:38:34.152  4857  4857 D CommonServiceConfiguration: getStringValueSetting
,06-23 11:38:34.162  4857  4857 D BatteryMonitor: new battery level: 100
,06-23 11:38:34.162  4809  4809 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-23 11:38:34.162  4809  9468 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,06-23 11:38:34.172  3928  3928 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-23 11:38:34.172  3928  3928 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-23 11:38:35.282  3486  6038 D SSRM:n  : SIOP:: AP = 290, PST = 292 (W:14), CP = 250, LCD = 40
,06-23 11:38:39.572  9374  9439 I jxcore-log: 2017-06-23 09:38:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
06-23 11:38:39.572  9374  9439 I jxcore-log: 
,06-23 11:38:39.572  9374  9439 I jxcore-log: 2017-06-23 09:38:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
06-23 11:38:39.572  9374  9439 I jxcore-log: 
06-23 11:38:39.572  9374  9439 I jxcore-log: 2017-06-23 09:38:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
06-23 11:38:39.572  9374  9439 I jxcore-log: 
,06-23 11:38:39.572  9374  9439 I jxcore-log: 2017-06-23 09:38:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server that is not listening yet witheatNotRunning set to true'
06-23 11:38:39.572  9374  9439 I jxcore-log: 
,06-23 11:38:39.582  9374  9439 I jxcore-log: 2017-06-23 09:38:39 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
06-23 11:38:39.582  9374  9439 I jxcore-log: 
,06-23 11:38:39.582  9374  9439 I jxcore-log: 2017-06-23 09:38:39 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - Call of multiple onCheckpointReached handlers on a single db change, error: 'TimeoutError', stack: 'TimeoutError: 
06-23 11:38:39.582  9374  9439 I jxcore-log:     at SubError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
06-23 11:38:39.582  9374  9439 I jxcore-log:     at module.exports/afterTimeout@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:49:15
06-23 11:38:39.582  9374  9439 I jxcore-log:     at timeoutTimeout@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
06-23 11:38:39.582  9374  9439 I jxcore-log:     at $9@timers.js:120:1
06-23 11:38:39.582  9374  9439 I jxcore-log: ''
06-23 11:38:39.582  9374  9439 I jxcore-log: 
,06-23 11:38:39.582  9374  9439 I jxcore-log: 2017-06-23 09:38:39 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'android''
06-23 11:38:39.582  9374  9439 I jxcore-log: 
,06-23 11:38:43.612  3486  4128 E Watchdog: !@Sync 15 [06-23 11:38:43.623]
,06-23 11:38:45.302  3486  6038 D SSRM:n  : SIOP:: AP = 290, PST = 291 (W:14), CP = 250, LCD = 40
,06-23 11:38:49.372  3486  6077 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-23 11:38:55.332  3486  6038 D SSRM:n  : SIOP:: AP = 290, PST = 290 (W:14), CP = 250, LCD = 40
,06-23 11:38:59.992  3486  3807 V AlarmManager: Expired Alarm result :8
,06-23 11:39:00.002  3928  3928 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
06-23 11:39:00.002  3928  3928 D KeyguardUpdateMonitor: handleTimeUpdate
,06-23 11:39:00.022  3928  3928 D Clock   : received broadcast android.intent.action.TIME_TICK
,06-23 11:39:00.072  3928  3928 D DateView: received broadcast android.intent.action.TIME_TICK
,06-23 11:39:00.092  4622  4622 D [Weather Widget]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,06-23 11:39:00.092  4622  4622 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EEFA9050249635C043F7E254E316C2550]}
,06-23 11:39:00.102  4622  4622 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EAB01DC5C99149A39F887E17599325AFBFF089086AA9902184ADA25758C536FE2]}
,06-23 11:39:00.102  4622  4622 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EFF0B905BDFF72B69FB632A6CB072B41F95D2E6F4F84443284E97F40042D431D8350388453A923ABD8469D82798FA7548]}
,06-23 11:39:00.102  4622  4622 D [Weather Widget]  : {[A1AF0F6A1A65A89C43D705938923D0FEFB71880C4E84718DA0A3E1F383E54FB27A4284D9BEDF7BAA2ABFFE671EB65C640578FF9DE16A23BFE3280A9DCDBB09A0930C2946B4A4DB933C502C8761FBEA50704C777D43C836F72ECCE6B5A21A213DA0A46164AC1F9A2A8026A390D761E721]}
06-23 11:39:00.102  4622  4622 D [Weather Widget]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,06-23 11:39:04.172  3486  4049 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-23 11:39:04.172  3486  4049 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4342, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-23 11:39:04.172  3486  4049 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
06-23 11:39:04.172  3486  3486 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-23 11:39:04.182  3486  3486 I MotionRecognitionService: Plugged
,06-23 11:39:04.182  3486  3486 D MotionRecognitionService:   cableConnection= 1
06-23 11:39:04.182  3486  3486 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-23 11:39:04.182  3486  3486 D MotionRecognitionService: skip setTransmitPower. 
,06-23 11:39:04.182  3486  3852 D WifiController: ApOrStaEnabledState  msg.what= 155652
,06-23 11:39:04.182  3928  3928 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-23 11:39:04.182  3928  3928 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-23 11:39:04.192  3928  3928 D PowerUI : priorPlugType = 2 mPlugType =  2
,06-23 11:39:04.202  4857  4857 D CommonServiceConfiguration: getStringValueSetting
,06-23 11:39:04.212  4857  4857 D BatteryMonitor: new battery level: 100
,06-23 11:39:04.222  4809  4809 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-23 11:39:04.222  4809  9468 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,06-23 11:39:04.222  3928  3928 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-23 11:39:04.222  3928  3928 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-23 11:39:04.552  9374  9439 I jxcore-log: 2017-06-23 09:39:04 - DEBUG CoordinatedClient: 'device disconnected from the test server'
06-23 11:39:04.552  9374  9439 I jxcore-log: 
,06-23 11:39:05.132  3186  3186 I bootchecker: bootchecker wake up!!
,06-23 11:39:05.352  3486  6038 D SSRM:n  : SIOP:: AP = 290, PST = 290 (W:14), CP = 250, LCD = 40
,06-23 11:39:06.822  9374  9439 I jxcore-log: 2017-06-23 09:39:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
06-23 11:39:06.822  9374  9439 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
06-23 11:39:06.822  9374  9439 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
06-23 11:39:06.822  9374  9439 I jxcore-log: emit@events.js:82:1
06-23 11:39:06.822  9374  9439 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
06-23 11:39:06.822  9374  9439 I jxcore-log: emit@events.js:82:1''
06-23 11:39:06.822  9374  9439 I jxcore-log: 
,06-23 11:39:06.832  9374  9439 I jxcore-log: 2017-06-23 09:39:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
06-23 11:39:06.832  9374  9439 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
06-23 11:39:06.832  9374  9439 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
06-23 11:39:06.832  9374  9439 I jxcore-log: emit@events.js:82:1
06-23 11:39:06.832  9374  9439 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
06-23 11:39:06.832  9374  9439 I jxcore-log: emit@events.js:82:1''
06-23 11:39:06.832  9374  9439 I jxcore-log: 
,06-23 11:39:09.372  3486  6077 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-23 11:39:11.582  9374  9439 I jxcore-log: 2017-06-23 09:39:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
06-23 11:39:11.582  9374  9439 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
06-23 11:39:11.582  9374  9439 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
06-23 11:39:11.582  9374  9439 I jxcore-log: emit@events.js:82:1
06-23 11:39:11.582  9374  9439 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
06-23 11:39:11.582  9374  9439 I jxcore-log: emit@events.js:82:1''
06-23 11:39:11.582  9374  9439 I jxcore-log: 
,06-23 11:39:11.582  9374  9439 I jxcore-log: 2017-06-23 09:39:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
06-23 11:39:11.582  9374  9439 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
06-23 11:39:11.582  9374  9439 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
06-23 11:39:11.582  9374  9439 I jxcore-log: emit@events.js:82:1
06-23 11:39:11.582  9374  9439 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
06-23 11:39:11.582  9374  9439 I jxcore-log: emit@events.js:82:1''
06-23 11:39:11.582  9374  9439 I jxcore-log: 
,06-23 11:39:13.612  3486  4128 E Watchdog: !@Sync 16 [06-23 11:39:13.625]
,06-23 11:39:15.382  3486  6038 D SSRM:n  : SIOP:: AP = 290, PST = 290 (W:14), CP = 249, LCD = 40
,06-23 11:39:15.492  4339  4428 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-23 11:39:15.492  4339  4428 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-23 11:39:21.612  9374  9439 I jxcore-log: 2017-06-23 09:39:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
06-23 11:39:21.612  9374  9439 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
06-23 11:39:21.612  9374  9439 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
06-23 11:39:21.612  9374  9439 I jxcore-log: emit@events.js:82:1
06-23 11:39:21.612  9374  9439 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
06-23 11:39:21.612  9374  9439 I jxcore-log: emit@events.js:82:1''
06-23 11:39:21.612  9374  9439 I jxcore-log: 
,06-23 11:39:21.622  9374  9439 I jxcore-log: 2017-06-23 09:39:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
06-23 11:39:21.622  9374  9439 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
06-23 11:39:21.622  9374  9439 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
06-23 11:39:21.622  9374  9439 I jxcore-log: emit@events.js:82:1
06-23 11:39:21.622  9374  9439 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
06-23 11:39:21.622  9374  9439 I jxcore-log: emit@events.js:82:1''
06-23 11:39:21.622  9374  9439 I jxcore-log: 
,06-23 11:39:25.402  3486  6038 D SSRM:n  : SIOP:: AP = 290, PST = 290 (W:14), CP = 249, LCD = 40
,06-23 11:39:29.372  3486  6077 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-23 11:39:31.652  9374  9439 I jxcore-log: 2017-06-23 09:39:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
06-23 11:39:31.652  9374  9439 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
06-23 11:39:31.652  9374  9439 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
06-23 11:39:31.652  9374  9439 I jxcore-log: emit@events.js:82:1
06-23 11:39:31.652  9374  9439 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
06-23 11:39:31.652  9374  9439 I jxcore-log: emit@events.js:82:1''
06-23 11:39:31.652  9374  9439 I jxcore-log: 
,06-23 11:39:31.662  9374  9439 I jxcore-log: 2017-06-23 09:39:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
06-23 11:39:31.662  9374  9439 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
06-23 11:39:31.662  9374  9439 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
06-23 11:39:31.662  9374  9439 I jxcore-log: emit@events.js:82:1
06-23 11:39:31.662  9374  9439 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
06-23 11:39:31.662  9374  9439 I jxcore-log: emit@events.js:82:1''
06-23 11:39:31.662  9374  9439 I jxcore-log: 
,06-23 11:39:34.232  3486  4258 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-23 11:39:34.232  3486  4258 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4343, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-23 11:39:34.232  3486  4258 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
06-23 11:39:34.232  3486  3486 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-23 11:39:34.232  3486  3486 I MotionRecognitionService: Plugged
,06-23 11:39:34.232  3486  3486 D MotionRecognitionService:   cableConnection= 1
06-23 11:39:34.232  3486  3486 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-23 11:39:34.232  3486  3486 D MotionRecognitionService: skip setTransmitPower. 
,06-23 11:39:34.242  3486  3852 D WifiController: ApOrStaEnabledState  msg.what= 155652
,06-23 11:39:34.242  3928  3928 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-23 11:39:34.242  3928  3928 D KeyguardUpdateMonitor: handleBatteryUpdate
06-23 11:39:34.242  3928  3928 D PowerUI : priorPlugType = 2 mPlugType =  2
,06-23 11:39:34.262  4857  4857 D CommonServiceConfiguration: getStringValueSetting
,06-23 11:39:34.262  4857  4857 D BatteryMonitor: new battery level: 100
,06-23 11:39:34.262  4809  4809 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-23 11:39:34.262  4809  9468 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,06-23 11:39:34.282  3928  3928 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-23 11:39:34.282  3928  3928 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-23 11:39:35.432  3486  6038 D SSRM:n  : SIOP:: AP = 290, PST = 290 (W:14), CP = 249, LCD = 40
,06-23 11:39:41.722  9374  9439 I jxcore-log: 2017-06-23 09:39:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
06-23 11:39:41.722  9374  9439 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
06-23 11:39:41.722  9374  9439 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
06-23 11:39:41.722  9374  9439 I jxcore-log: emit@events.js:82:1
06-23 11:39:41.722  9374  9439 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
06-23 11:39:41.722  9374  9439 I jxcore-log: emit@events.js:82:1''
06-23 11:39:41.722  9374  9439 I jxcore-log: 
,06-23 11:39:41.732  9374  9439 I jxcore-log: 2017-06-23 09:39:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
06-23 11:39:41.732  9374  9439 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
06-23 11:39:41.732  9374  9439 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
06-23 11:39:41.732  9374  9439 I jxcore-log: emit@events.js:82:1
06-23 11:39:41.732  9374  9439 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
06-23 11:39:41.732  9374  9439 I jxcore-log: emit@events.js:82:1''
06-23 11:39:41.732  9374  9439 I jxcore-log: 
,06-23 11:39:43.622  3486  4128 E Watchdog: !@Sync 17 [06-23 11:39:43.626]
,06-23 11:39:45.452  3486  6038 D SSRM:n  : SIOP:: AP = 290, PST = 290 (W:14), CP = 248, LCD = 40
,06-23 11:39:49.372  3486  6077 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-23 11:39:51.832  9374  9439 I jxcore-log: 2017-06-23 09:39:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
06-23 11:39:51.832  9374  9439 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
06-23 11:39:51.832  9374  9439 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
06-23 11:39:51.832  9374  9439 I jxcore-log: emit@events.js:82:1
06-23 11:39:51.832  9374  9439 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
06-23 11:39:51.832  9374  9439 I jxcore-log: emit@events.js:82:1''
06-23 11:39:51.832  9374  9439 I jxcore-log: 
,06-23 11:39:51.832  9374  9439 I jxcore-log: 2017-06-23 09:39:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
06-23 11:39:51.832  9374  9439 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
06-23 11:39:51.832  9374  9439 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
06-23 11:39:51.832  9374  9439 I jxcore-log: emit@events.js:82:1
06-23 11:39:51.832  9374  9439 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
06-23 11:39:51.832  9374  9439 I jxcore-log: emit@events.js:82:1''
06-23 11:39:51.832  9374  9439 I jxcore-log: 
,06-23 11:39:55.472  3486  6038 D SSRM:n  : SIOP:: AP = 290, PST = 290 (W:14), CP = 248, LCD = 40
,06-23 11:39:59.992  3486  3807 V AlarmManager: Expired Alarm result :8
,06-23 11:40:00.002  3928  3928 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,06-23 11:40:00.002  3928  3928 D KeyguardUpdateMonitor: handleTimeUpdate
,06-23 11:40:00.012  3928  3928 D Clock   : received broadcast android.intent.action.TIME_TICK
,06-23 11:40:00.082  3928  3928 D DateView: received broadcast android.intent.action.TIME_TICK
,06-23 11:40:00.112  4622  4622 D [Weather Widget]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,06-23 11:40:00.122  4622  4622 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EEFA9050249635C043F7E254E316C2550]}
,06-23 11:40:00.122  4622  4622 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EAB01DC5C99149A39F887E17599325AFBFF089086AA9902184ADA25758C536FE2]}
,06-23 11:40:00.122  4622  4622 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EFF0B905BDFF72B69FB632A6CB072B41F95D2E6F4F84443284E97F40042D431D8350388453A923ABD8469D82798FA7548]}
,06-23 11:40:00.122  4622  4622 D [Weather Widget]  : {[A1AF0F6A1A65A89C43D705938923D0FEFB71880C4E84718DA0A3E1F383E54FB27A4284D9BEDF7BAA2ABFFE671EB65C640578FF9DE16A23BFE3280A9DCDBB09A0930C2946B4A4DB933C502C8761FBEA50704C777D43C836F72ECCE6B5A21A213DA0A46164AC1F9A2A8026A390D761E721]}
,06-23 11:40:00.122  4622  4622 D [Weather Widget]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,06-23 11:40:01.872  9374  9439 I jxcore-log: 2017-06-23 09:40:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
06-23 11:40:01.872  9374  9439 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
06-23 11:40:01.872  9374  9439 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
06-23 11:40:01.872  9374  9439 I jxcore-log: emit@events.js:82:1
06-23 11:40:01.872  9374  9439 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
06-23 11:40:01.872  9374  9439 I jxcore-log: emit@events.js:82:1''
06-23 11:40:01.872  9374  9439 I jxcore-log: 
,06-23 11:40:01.882  9374  9439 I jxcore-log: 2017-06-23 09:40:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
06-23 11:40:01.882  9374  9439 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
06-23 11:40:01.882  9374  9439 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
06-23 11:40:01.882  9374  9439 I jxcore-log: emit@events.js:82:1
06-23 11:40:01.882  9374  9439 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
06-23 11:40:01.882  9374  9439 I jxcore-log: emit@events.js:82:1''
06-23 11:40:01.882  9374  9439 I jxcore-log: 
,06-23 11:40:04.272  3486  3975 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-23 11:40:04.282  3486  3975 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-23 11:40:04.282  3486  3975 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
06-23 11:40:04.282  3486  3486 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-23 11:40:04.282  3486  3486 I MotionRecognitionService: Plugged
,06-23 11:40:04.282  3486  3486 D MotionRecognitionService:   cableConnection= 1
06-23 11:40:04.282  3486  3486 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-23 11:40:04.282  3486  3486 D MotionRecognitionService: skip setTransmitPower. 
,06-23 11:40:04.292  3486  3852 D WifiController: ApOrStaEnabledState  msg.what= 155652
,06-23 11:40:04.292  3928  3928 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-23 11:40:04.292  3928  3928 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-23 11:40:04.292  3928  3928 D PowerUI : priorPlugType = 2 mPlugType =  2
,06-23 11:40:04.312  4857  4857 D CommonServiceConfiguration: getStringValueSetting
,06-23 11:40:04.322  4857  4857 D BatteryMonitor: new battery level: 100
,06-23 11:40:04.322  4809  4809 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-23 11:40:04.332  4809  9468 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,06-23 11:40:04.332  3928  3928 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-23 11:40:04.332  3928  3928 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-23 11:40:05.502  3486  6038 D SSRM:n  : SIOP:: AP = 290, PST = 290 (W:14), CP = 248, LCD = 40

```
