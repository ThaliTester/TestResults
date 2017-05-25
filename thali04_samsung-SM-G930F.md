#### Test 11335185108be6d0_thali04_samsung-SM-G930F Logs


```
--------- beginning of system
,05-25 13:50:49.345  3549  6115 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
05-25 13:50:49.675  3549  4066 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-25 13:50:49.675  3549  4066 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4328, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:50:49.675  3549  4066 D BatteryService: online:4, current avg:147, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:10
05-25 13:50:49.675  3549  3549 D BatteryService: Sending ACTION_BATTERY_CHANGED.
05-25 13:50:49.675  3549  3549 I MotionRecognitionService: Plugged
05-25 13:50:49.675  3549  3549 D MotionRecognitionService:   cableConnection= 1
05-25 13:50:49.675  3549  3549 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:50:49.675  3549  3549 D MotionRecognitionService: skip setTransmitPower. 
--------- beginning of main
05-25 13:50:49.685  3549  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
05-25 13:50:49.685  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
05-25 13:50:49.685  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
05-25 13:50:49.685  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
05-25 13:50:49.695  4905  4905 D CommonServiceConfiguration: getStringValueSetting
05-25 13:50:49.695  4857  4857 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-25 13:50:49.705  4857  5186 D HeadsetStateMachine: Disconnected process message: 10, size: 0
05-25 13:50:49.705  4905  4905 D BatteryMonitor: new battery level: 100
05-25 13:50:49.715  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
05-25 13:50:49.725  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
05-25 13:50:49.815  9925  9925 I FIPS_bssl: FIPS approved mode (1) | 9925 | app_process
05-25 13:50:49.815  9925  9925 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
05-25 13:50:49.825  9925  9925 D AndroidRuntime: CheckJNI is OFF
05-25 13:50:49.825  9925  9925 D AndroidRuntime: readGMSProperty: start
05-25 13:50:49.825  9925  9925 D AndroidRuntime: readGMSProperty: already setted!!
05-25 13:50:49.825  9925  9925 D AndroidRuntime: propertySet: couldn't set property (it is from app)
05-25 13:50:49.825  9925  9925 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
05-25 13:50:49.825  9925  9925 D AndroidRuntime: readGMSProperty: end
05-25 13:50:49.825  9925  9925 D AndroidRuntime: addProductProperty: start
05-25 13:50:49.835  9925  9925 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
05-25 13:50:49.865  9925  9925 I Radio-JNI: register_android_hardware_Radio DONE
05-25 13:50:49.865  9925  9925 E AffinityControl: AffinityControl: registerfunction enter
05-25 13:50:49.875  9925  9925 D AndroidRuntime: Calling main entry com.android.commands.am.Am
05-25 13:50:49.905  3549  4435 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
05-25 13:50:49.905  3549  4435 W ResourcesManager: getTopLevelResources: /data/app/com.thaliproject.thalitest-1/base.apk / 1.0 running in null rsrc of package com.thaliproject.thalitest
05-25 13:50:49.935  3549  4435 D ResourcesManager: For user 0 new overlays fetched Null
05-25 13:50:49.935  3549  4435 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
05-25 13:50:49.935  3549  4435 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.thaliproject.thalitest)
05-25 13:50:49.935  3549  4435 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3549  pkgName : ACTIVITY_RESUME_BOOSTER@3
05-25 13:50:49.945  3549  4435 D ActivityManager: mDVFSHelper.acquire()
05-25 13:50:49.945  3549  4435 V WindowManager: addAppToken: AppWindowToken{d04ab37a2 token=Token{284f6d ActivityRecord{90d0b84 u0 com.thaliproject.thalitest/.MainActivity t5}}} to stack=2 task=5 at 0
05-25 13:50:49.955  3549  3620 I InjectionManager: Inside getClassLibPath caller 
05-25 13:50:49.965  3549  3620 D SecWifiDisplayUtil: Metadata value : SecSettings2
05-25 13:50:49.965  3549  3620 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{18018fa V.E...... R.....ID 0,0-0,0}
05-25 13:50:49.965  3549  3620 D ISSUE_DEBUG: InputChannelName : 2a0b908 Starting com.thaliproject.thalitest
05-25 13:50:49.975  3549  4435 D InputDispatcher: Focused application set to: xxxx
05-25 13:50:49.975  3549  4435 D InputDispatcher: Focus left window: 6446
05-25 13:50:49.975  3549  3605 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{d28b0b9 u0 d0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}
05-25 13:50:49.975  9925  9925 D AndroidRuntime: Shutting down VM
05-25 13:50:49.975  3949  3949 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=8000 newVal=8600 diff=600
05-25 13:50:49.975  3011  3011 I SurfaceFlinger: id=18 createSurf (1x1),1 flag=404, uhalitest
05-25 13:50:49.995  3549  3620 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3549 uid:1000
05-25 13:50:49.995  3549  3620 D PointerIcon: setMouseCustomIcon IconType is same.101
05-25 13:50:49.995  3549  3620 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
05-25 13:50:50.005  9936  9936 E Zygote  : v2
05-25 13:50:50.005  9936  9936 I libpersona: KNOX_SDCARD checking this for 10074
05-25 13:50:50.005  9936  9936 I libpersona: KNOX_SDCARD not a persona
05-25 13:50:50.005  9936  9936 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
05-25 13:50:50.005  3549  3567 I ActivityManager: Start proc 9936:com.thaliproject.thalitest/u0a74 for activity com.thaliproject.thalitest/.MainActivity
05-25 13:50:50.005  9936  9936 E Zygote  : accessInfo : 0
05-25 13:50:50.005  9936  9936 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.thaliproject.thalitest 
05-25 13:50:50.005  3549  3857 D NetworkPolicy: isUidForegroundLocked: 10074, mScreenOn: true, uidstate: -1, mProxSensorScreenOff: false
05-25 13:50:50.015  3549  3620 V WindowStateAnimator: Finishing drawing window Window{2a0b908 u0 d0 Starting com.thaliproject.thalitest}: mDrawState=DRAW_PENDING
05-25 13:50:50.025  3011  3011 D libEGL  : eglInitialize EGLDisplay = 0x7fcec79e68
05-25 13:50:50.025  9936  9936 D TimaKeyStoreProvider: TimaSignature is unavailable
05-25 13:50:50.025  9936  9936 D ActivityThread: Added TimaKeyStore provider
05-25 13:50:50.025  3549  3986 V WindowOrientationListener: setCurrentAppOrientation :-1
05-25 13:50:50.025  3549  3986 V WindowOrientationListener: OrientationSensorJudge.getProposedRotation, Rotation: -1
05-25 13:50:50.025  3549  3986 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
05-25 13:50:50.025  3549  3986 V WindowOrientationListener: OrientationSensorJudge.getProposedRotation, Rotation: -1
05-25 13:50:50.035  3549  3986 D ActivityManager:  Launching com.thaliproject.thalitest, updated priority
05-25 13:50:50.035  4273  4273 D Launcher.HomeView: onStop
05-25 13:50:50.035  4273  4273 D capture : ----destroy
05-25 13:50:50.035  6737  6737 V ActivityThread: updateVisibility : ActivityRecord{b1557ec token=android.os.BinderProxy@2f77efc {com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity}} show : false
05-25 13:50:50.035  4273  4273 V ActivityThread: updateVisibility : ActivityRecord{c7d9dc2 token=android.os.BinderProxy@7615a5b {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
05-25 13:50:50.035  3549  3549 D GameManagerService: NotifyRunnable. pkg: com.thaliproject.thalitest, type: 4, isMinimized: false, isTunableApp: false
05-25 13:50:50.045  3011  4312 D libEGL  : eglTerminate EGLDisplay = 0x7f99cffe78
05-25 13:50:50.045  3011  4312 D libEGL  : eglTerminate EGLDisplay = 0x7f99cffe78
05-25 13:50:50.045  3549  3856 D NtpTrustedTime: currentTimeMillis() cache hit
05-25 13:50:50.045  3549  3856 V NetworkStats: performPollLocked(flags=0x1)
05-25 13:50:50.045  3549  3856 D NetworkStatsRecorder: entry.iface is null
05-25 13:50:50.045  3549  3856 D NetworkStatsRecorder: entry.iface is null
05-25 13:50:50.045  3549  3856 D NetworkStatsRecorder: entry.iface is null
05-25 13:50:50.045  3549  3856 D NetworkStatsRecorder: entry.iface is null
05-25 13:50:50.045  9936  9936 W ResourcesManager: getTopLevelResources: /data/app/com.thaliproject.thalitest-1/base.apk / 1.0 running in com.thaliproject.thalitest rsrc of package com.thaliproject.thalitest
05-25 13:50:50.045  3549  3603 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.thaliproject.thalitest
05-25 13:50:50.045  3549  3603 E MARsPolicyManager: getPackageInfo package com.test.thalitest not installed!
05-25 13:50:50.045  3549  3603 E MARsPolicyManager: getPackageInfo package com.rockwellautomation.thalitest not installed!
05-25 13:50:50.045  3549  6068 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
05-25 13:50:50.045  3549  6068 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
05-25 13:50:50.045  3549  3605 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{2a0b908 u0 d0 Starting com.thaliproject.thalitest}
05-25 13:50:50.055  3549  4433 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-25 13:50:50.055  9936  9936 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
05-25 13:50:50.055  3011  3073 D libEGL  : eglTerminate EGLDisplay = 0x7f99dfee78
05-25 13:50:50.055  3011  3073 D libEGL  : eglTerminate EGLDisplay = 0x7f99dfee78
05-25 13:50:50.065  9936  9936 D ResourcesManager: For user 0 new overlays fetched Null
05-25 13:50:50.065  3549  3856 D NtpTrustedTime: currentTimeMillis() cache hit
05-25 13:50:50.065  3549  3856 V NetworkStats: performPollLocked() took 23ms
05-25 13:50:50.065  3549  3857 D NtpTrustedTime: currentTimeMillis() cache hit
05-25 13:50:50.065  3549  3857 D NtpTrustedTime: currentTimeMillis() cache hit
05-25 13:50:50.065  3549  6068 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
05-25 13:50:50.065  9936  9936 I InjectionManager: Inside getClassLibPath caller 
05-25 13:50:50.075  3549  6068 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
05-25 13:50:50.075  3011  3024 D libEGL  : eglTerminate EGLDisplay = 0x7fa01fee78
05-25 13:50:50.075  3011  3024 D libEGL  : eglTerminate EGLDisplay = 0x7fa01fee78
05-25 13:50:50.075  3549  3560 I art     : Background partial concurrent mark sweep GC freed 28637(2MB) AllocSpace objects, 14(280KB) LOS objects, 31% free, 35MB/51MB, paused 1.678ms total 115.172ms
05-25 13:50:50.075  4273  4273 D Launcher: onTrimMemory. Level: 20
05-25 13:50:50.075  3549  6068 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
05-25 13:50:50.075  3549  6068 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
05-25 13:50:50.075  3549  6068 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
05-25 13:50:50.085  9936  9936 D InjectionManager: InjectionManager
05-25 13:50:50.085  9936  9936 D InjectionManager: fillFeatureStoreMap com.thaliproject.thalitest
05-25 13:50:50.085  9936  9936 I InjectionManager: Constructor com.thaliproject.thalitest, Feature store :{}
05-25 13:50:50.085  9936  9936 I InjectionManager: featureStore :{}
05-25 13:50:50.085  9936  9936 W ResourcesManager: getTopLevelResources: /data/app/com.thaliproject.thalitest-1/base.apk / 1.0 running in com.thaliproject.thalitest rsrc of package com.thaliproject.thalitest
05-25 13:50:50.085  9936  9936 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
05-25 13:50:50.085  9936  9936 D RelationGraph: garbageCollect()
05-25 13:50:50.085  9936  9936 W ResourcesManager: getTopLevelResources: /data/app/com.thaliproject.thalitest-1/base.apk / 1.0 running in com.thaliproject.thalitest rsrc of package com.thaliproject.thalitest
05-25 13:50:50.105  9936  9936 I CordovaLog: Changing log level to DEBUG(3)
05-25 13:50:50.105  9936  9936 I CordovaActivity: Apache Cordova native platform version 6.0.0 is starting
05-25 13:50:50.105  9936  9936 D CordovaActivity: CordovaActivity.onCreate()
05-25 13:50:50.105  9936  9936 I WebViewFactory: Loading com.google.android.webview version 50.0.2661.86 (code 266108650)
05-25 13:50:50.125  9936  9936 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.thaliproject.thalitest rsrc of package com.google.android.webview
05-25 13:50:50.125  9936  9936 D ResourcesManager: For user 0 new overlays fetched Null
05-25 13:50:50.125  9936  9936 I InjectionManager: Inside getClassLibPath caller 
05-25 13:50:50.125  9936  9936 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
05-25 13:50:50.165  9936  9936 I cr_LibraryLoader: Time to load native libraries: 22 ms (timestamps 541-563)
05-25 13:50:50.165  9936  9936 I cr_LibraryLoader: Expected native library version number "50.0.2661.86", actual native library version number "50.0.2661.86"
05-25 13:50:50.185  9936  9950 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.thaliproject.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,05-25 13:50:50.205  9936  9936 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {aa689ba}
,05-25 13:50:50.205  9936  9936 I cr_LibraryLoader: Expected native library version number "50.0.2661.86", actual native library version number "50.0.2661.86"
,05-25 13:50:50.225  9936  9936 I chromium: [INFO:library_loader_hooks.cc(143)] Chromium logging enabled: level = 0, default verbosity = 0
,05-25 13:50:50.255  9936  9936 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,05-25 13:50:50.305  3549  3882 D MdnieScenarioControlService:  packageName : com.thaliproject.thalitest    className : com.thaliproject.thalitest.MainActivity
,05-25 13:50:50.335  9936  9936 D libEGL  : eglInitialize EGLDisplay = 0xff917854
,05-25 13:50:50.375  3549  4420 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10074
,05-25 13:50:50.385  3549  4420 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29757 com.android.server.am.ActivityManagerService.registerReceiver:22622 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,05-25 13:50:50.395  3549  3857 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: true, uidstate: 2, mProxSensorScreenOff: false
,05-25 13:50:50.405  3549  3882 I MdnieScenarioControlService: mGameModeLauncher : false
,05-25 13:50:50.405  3549  3882 I MdnieScenarioControlService: setUIMode
,05-25 13:50:50.415  9936  9936 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10074, CallingPid : 9936
,05-25 13:50:50.425  3549  3838 D ConnectivityService: listenForNetwork for Listen from uid/pid:10074/9936 for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:50:50.425  3549  3869 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,05-25 13:50:50.425  3549  3869 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -35]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,05-25 13:50:50.425  3011  4437 I SurfaceFlinger: id=9 Removed MauncherAct (4/14)
,05-25 13:50:50.425  3011  3024 I SurfaceFlinger: id=15 Removed YUIInstallC (4/13)
,05-25 13:50:50.425  3011  3024 I SurfaceFlinger: id=9 Removed MauncherAct (-2/13)
05-25 13:50:50.425  3011  3073 I SurfaceFlinger: id=14 Removed YUIInstallC (4/12)
,05-25 13:50:50.425  3011  3022 I SurfaceFlinger: id=17 Removed VSBConnecti (4/11)
,05-25 13:50:50.425  3011  3024 I SurfaceFlinger: id=15 Removed YUIInstallC (-2/11)
,05-25 13:50:50.425  3011  4312 I SurfaceFlinger: id=16 Removed VSBConnecti (5/10)
05-25 13:50:50.425  3011  3073 I SurfaceFlinger: id=14 Removed YUIInstallC (-2/10)
,05-25 13:50:50.425  3011  3024 I SurfaceFlinger: id=17 Removed VSBConnecti (-2/10)
05-25 13:50:50.425  3011  4312 I SurfaceFlinger: id=16 Removed VSBConnecti (-2/10)
,05-25 13:50:50.435  3949  3949 D ImageWallpaper: onVisibilityChanged:false
,05-25 13:50:50.435  3949  3949 D ImageWallpaper: drawFrame:false rotation:0 mLastRotation:0
05-25 13:50:50.435  3949  3949 D ImageWallpaper: drawFrame:[frame.width()]2240[frame.height()]2560
05-25 13:50:50.435  3949  3949 D ImageWallpaper: Suppressed drawFrame since redraw is not needed and offsets have not changed.
05-25 13:50:50.435  3549  3869 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,05-25 13:50:50.435  3549  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-25 13:50:50.435  3549  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,05-25 13:50:50.435  9936  9936 D cr_Ime  : [InputMethodManagerWrapper.java:30] Constructor
,05-25 13:50:50.435  3549  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-25 13:50:50.435  3011  3011 D libEGL  : eglTerminate EGLDisplay = 0x7fcec79f88
,05-25 13:50:50.435  3011  3011 D libEGL  : eglTerminate EGLDisplay = 0x7fcec79f88
,05-25 13:50:50.435  3549  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
05-25 13:50:50.435  3011  3011 D libEGL  : eglTerminate EGLDisplay = 0x7fcec79f88
,05-25 13:50:50.435  3011  3011 D libEGL  : eglTerminate EGLDisplay = 0x7fcec79f88
,05-25 13:50:50.445  3549  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,05-25 13:50:50.445  3549  3869 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:50:50.445  9936  9936 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,05-25 13:50:50.455  9936  9936 D cr_Ime  : [InputMethodManagerWrapper.java:59] isActive: false
,05-25 13:50:50.465  9936  9936 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,05-25 13:50:50.475  9936  9936 D PluginManager: init()
,05-25 13:50:50.475  9936  9936 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,05-25 13:50:50.485  9936  9936 I cr_Ime  : ImeThread is not enabled.
,05-25 13:50:50.485  9936  9936 D Activity: performCreate Call Injection manager
,05-25 13:50:50.495  9936  9936 D CordovaActivity: Started the activity.
05-25 13:50:50.495  9936  9936 I InjectionManager: dispatchOnViewCreated > Target : com.thaliproject.thalitest.MainActivity isFragment :false
05-25 13:50:50.495  9936  9936 D CordovaActivity: Resumed the activity.
,05-25 13:50:50.495  9936  9936 D SecWifiDisplayUtil: Metadata value : SecSettings2
,05-25 13:50:50.495  9936  9936 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{3eb6341 I.E...... R.....ID 0,0-0,0}
,05-25 13:50:50.505  9936  9985 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,05-25 13:50:50.505  3549  4285 D ISSUE_DEBUG: InputChannelName : 91ae403 com.thaliproject.thalitest/com.thaliproject.thalitest.MainActivity
05-25 13:50:50.505  3549  3567 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
05-25 13:50:50.505  3549  3567 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
05-25 13:50:50.505  3549  3549 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
05-25 13:50:50.505  3549  3549 I KnoxTimeoutHandler: Shared devices show user statefalse
05-25 13:50:50.515  9936  9950 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.thaliproject.thalitest/shared_prefs/com.thaliproject.thalitest_preferences.xml.bak
05-25 13:50:50.515  9936  9936 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10074, CallingPid : 9936
05-25 13:50:50.515  3549  3986 D ConnectivityService: listenForNetwork for Listen from uid/pid:10074/9936 for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:50:50.515  3549  3869 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
05-25 13:50:50.515  3549  3869 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -35]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
05-25 13:50:50.515  3549  3869 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
05-25 13:50:50.515  3549  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
05-25 13:50:50.515  3549  3857 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: true, uidstate: 6, mProxSensorScreenOff: false
05-25 13:50:50.525  3549  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
05-25 13:50:50.525  3549  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
05-25 13:50:50.525  3549  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
05-25 13:50:50.525  9936  9936 D SecWifiDisplayUtil: Metadata value : SecSettings2
05-25 13:50:50.535  3549  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
05-25 13:50:50.535  3549  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
05-25 13:50:50.535  3549  3869 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:50:50.535  3011  3011 I SurfaceFlinger: id=19 createSurf (1x1),1 flag=404, NainActivit
,05-25 13:50:50.555  3549  4430 D InputDispatcher: Focus entered window: 9936
,05-25 13:50:50.555  3549  3620 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3549 uid:1000
05-25 13:50:50.555  3549  3620 D PointerIcon: setMouseCustomIcon IconType is same.101
05-25 13:50:50.555  9936  9985 D libEGL  : eglInitialize EGLDisplay = 0xdca3f7c4
05-25 13:50:50.555  9936  9985 I OpenGLRenderer: Initialized EGL, version 1.4
,05-25 13:50:50.565  9936  9985 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,05-25 13:50:50.575  9936  9936 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,05-25 13:50:50.575  9936  9989 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
05-25 13:50:50.575  9936  9989 D libEGL  : eglInitialize EGLDisplay = 0xdbeff3e4
,05-25 13:50:50.585  9936  9989 D libGLESv2: DTS_GLAPI : DTS is not allowed for Package : com.thaliproject.thalitest
,05-25 13:50:50.605  3549  3567 V WindowStateAnimator: Finishing drawing window Window{91ae403 u0 d0 com.thaliproject.thalitest/com.thaliproject.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,05-25 13:50:50.605  9936  9936 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
,05-25 13:50:50.605  3011  3011 D libEGL  : eglInitialize EGLDisplay = 0x7fcec79e68
,05-25 13:50:50.605  3549  4420 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,05-25 13:50:50.605  3549  3620 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
05-25 13:50:50.605  3549  3549 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,05-25 13:50:50.605  3549  3620 I ActivityManager: Displayed com.thaliproject.thalitest/.MainActivity: +618ms
05-25 13:50:50.605  3549  3549 I KnoxTimeoutHandler: SD activityfalse
,05-25 13:50:50.615  3549  3620 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3549  tag : ACTIVITY_RESUME_BOOSTER@3
,05-25 13:50:50.615  3549  3620 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{90d0b84 u0 com.thaliproject.thalitest/.MainActivity t5} time:271011
05-25 13:50:50.615  3549  3620 D ActivityManager: mDVFSHelper.release()
05-25 13:50:50.615  3549  3620 D ViewRootImpl: #3 mView = null
,05-25 13:50:50.615  3549  3603 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3549  pkgName : ACTIVITY_RESUME_BOOSTER@9
,05-25 13:50:50.615  4782  4782 D SamsungIME: IMPL finishInput
,05-25 13:50:50.615  4782  4782 D SamsungIME: SwiftKeyWrapper writeDBdataToFileOnFinishInput
05-25 13:50:50.615  4782  4782 D SamsungIME: saveAndClear +
05-25 13:50:50.615  4782  4782 D SamsungIME: saveAndClear -
,05-25 13:50:50.625  3549  3986 V WindowStateAnimator: Finishing drawing window Window{91ae403 u0 d0 com.thaliproject.thalitest/com.thaliproject.thalitest.MainActivity}: mDrawState=HAS_DRAWN
,05-25 13:50:50.625  9936  9936 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
05-25 13:50:50.625  9936  9936 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@969f529 time:271027
,05-25 13:50:50.625  6446  6446 V ActivityThread: updateVisibility : ActivityRecord{f08e62e token=android.os.BinderProxy@e477e0 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
,05-25 13:50:50.635  9936  9936 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9936
,05-25 13:50:50.635  9936  9936 D cr_Ime  : [InputMethodManagerWrapper.java:59] isActive: true
,05-25 13:50:50.635  9936  9936 D cr_Ime  : [InputMethodManagerWrapper.java:68] hideSoftInputFromWindow
,05-25 13:50:50.635  3011  3011 D libEGL  : eglInitialize EGLDisplay = 0x7fcec79e68
,05-25 13:50:50.675  3011  3011 D libEGL  : eglInitialize EGLDisplay = 0x7fcec79e68
,05-25 13:50:50.745  9936  9936 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,05-25 13:50:50.805  3011  4312 I SurfaceFlinger: id=18 Removed uhalitest (7/10)
,05-25 13:50:50.805  3011  3024 I SurfaceFlinger: id=18 Removed uhalitest (-2/10)
,05-25 13:50:50.825  3011  3011 D libEGL  : eglTerminate EGLDisplay = 0x7fcec79f88
,05-25 13:50:50.825  9936  9998 D jxcore_app_log: JniHelper::setJavaVM(0xf4e34000), pthread_self() = -683673296
,05-25 13:50:50.825  9936  9998 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
05-25 13:50:50.825  9936  9998 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
05-25 13:50:50.825  9936  9998 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
05-25 13:50:50.825  9936  9998 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
05-25 13:50:50.825  9936  9998 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
05-25 13:50:50.835  9936  9998 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a85bd58 added. We now have 1 listener(s)
,05-25 13:50:50.835  9936  9998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a85bd58 added. We now have 1 listener(s)
05-25 13:50:50.835  9936  9998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
05-25 13:50:50.835  9936  9998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
05-25 13:50:50.835  9936  9998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
05-25 13:50:50.835  9936  9998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: null
05-25 13:50:50.835  9936  9998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
05-25 13:50:50.835  9936  9998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
05-25 13:50:50.835  9936  9998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
05-25 13:50:50.835  9936  9998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
05-25 13:50:50.835  9936  9998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 256
05-25 13:50:50.835  9936  9998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
05-25 13:50:50.835  9936  9998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
05-25 13:50:50.835  9936  9998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
05-25 13:50:50.835  9936  9998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
05-25 13:50:50.835  9936  9998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,05-25 13:50:50.835  9936  9998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 44:78:3E:94:4A:3E
05-25 13:50:50.835  9936  9998 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: ", Bluetooth MAC address: "44:78:3E:94:4A:3E"Peer extra info: "256
05-25 13:50:50.835  9936  9998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
05-25 13:50:50.835  9936  9998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: null
,05-25 13:50:50.835  9936  9998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
05-25 13:50:50.835  9936  9998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@297a717 added. We now have 2 listener(s)
05-25 13:50:50.835  9936  9998 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,05-25 13:50:50.835  9936  9998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
05-25 13:50:50.835  9936  9998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 25730
,05-25 13:50:50.835  9936  9998 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,7,main], id: 137
05-25 13:50:50.835  9936  9998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
05-25 13:50:50.835  9936  9998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
05-25 13:50:50.835  9936  9998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
05-25 13:50:50.835  9936  9998 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,7,main], id: 137
,05-25 13:50:50.835  9936  9998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
05-25 13:50:50.835  9936  9998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 44:78:3E:94:4A:3E
,05-25 13:50:50.845  9936  9998 D BluetoothAdapter: STATE_ON
,05-25 13:50:50.845  9936  9998 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
05-25 13:50:50.845  9936  9998 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
05-25 13:50:50.845  9936  9998 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-25 13:50:50.845  9936  9998 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-25 13:50:50.845  9936  9998 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-25 13:50:50.845  9936  9998 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-25 13:50:50.845  9936  9998 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-25 13:50:50.845  9936  9998 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-25 13:50:50.845  9936  9998 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-25 13:50:50.845  9936  9998 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
05-25 13:50:50.845  9936  9998 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
05-25 13:50:50.845  9936  9998 D io.jxcore.node.ConnectivityMonitor: start: OK
05-25 13:50:50.845  9936  9998 I io.jxcore.node.LifeCycleMonitor: start: OK
,05-25 13:50:50.845  9936  9936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:50:50.845  9936  9936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:50:50.845  9936  9936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:50:50.855  9936  9936 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,05-25 13:50:50.855  9936  9936 D SystemWebChromeClient: file:///android_asset/www/js/index.js: Line 36 : Uncaught TypeError: Cannot read property 'querySelector' of null
,05-25 13:50:50.855  9936  9936 I chromium: [INFO:CONSOLE(36)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (36)
,05-25 13:50:50.895  3549  3882 D MdnieScenarioControlService:  packageName : com.thaliproject.thalitest    className : com.thaliproject.thalitest.MainActivity
,05-25 13:50:50.915  3549  3549 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3549  tag : ACTIVITY_RESUME_BOOSTER@9
,05-25 13:50:50.995  3549  3882 I MdnieScenarioControlService: mGameModeLauncher : false
,05-25 13:50:50.995  3549  3882 I MdnieScenarioControlService: setUIMode
,05-25 13:50:51.005  4027  4027 D Recents : onTaskStackChanged
,05-25 13:50:51.015  4027  4027 W ResourcesManager: getTopLevelResources: /data/app/com.thaliproject.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.thaliproject.thalitest
,05-25 13:50:51.025  4027  4027 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:50:51.055  3549  6069 W ResourcesManager: getTopLevelResources: /data/app/com.thaliproject.thalitest-1/base.apk / 1.0 running in null rsrc of package com.thaliproject.thalitest
,05-25 13:50:51.375  9936  9999 W jxcore-log: Initializing JXcore engine
05-25 13:50:51.375  9936  9999 W jxcore-log: JXcore engine is ready
,05-25 13:50:51.395  4865  4865 E audit   : type=1400 msg=audit(1495713051.395:264): avc:  denied  { ioctl } for  pid=9999 comm="Thread-138" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=1194 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
05-25 13:50:51.395  4865  4865 E audit   :  SEPF_SECMOBILE_6.0.1_0031
05-25 13:50:51.395  4865  4865 E audit   : type=1300 msg=audit(1495713051.395:264): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=8 a1=5451 a2=1 a3=d673f3c8 items=0 ppid=3184 pid=9999 auid=4294967295 uid=10074 gid=10074 euid=10074 suid=10074 fsuid=10074 egid=10074 sgid=10074 fsgid=10074 tty=(none) ses=4294967295 comm="Thread-138" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
05-25 13:50:51.395  4865  4865 E audit   : type=1327 msg=audit(1495713051.395:264): proctitle="com.thaliproject.thalitest"
05-25 13:50:51.395  4865  4865 E audit   : type=1320 msg=audit(1495713051.395:264): 
05-25 13:50:51.395  4865  4865 E audit   : type=1400 msg=audit(1495713051.395:265): avc:  denied  { ioctl } for  pid=9999 comm="Thread-138" path="socket:[15265]" dev="sockfs" ino=15265 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
05-25 13:50:51.395  4865  4865 E audit   :  SEPF_SECMOBILE_6.0.1_0031
05-25 13:50:51.395  4865  4865 E audit   : type=1300 msg=audit(1495713051.395:265): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=33 a1=5451 a2=1 a3=d673f3c8 items=0 ppid=3184 pid=9999 auid=4294967295 uid=10074 gid=10074 euid=10074 suid=10074 fsuid=10074 egid=10074 sgid=10074 fsgid=10074 tty=(none) ses=4294967295 comm="Thread-138" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
05-25 13:50:51.395  4865  4865 E audit   : type=1327 msg=audit(1495713051.395:265): proctitle="com.thaliproject.thalitest"
05-25 13:50:51.395  4865  4865 E audit   : type=1320 msg=audit(1495713051.395:265): 
,05-25 13:50:51.405  9936  9999 W jxcore-log: Starting JXcore engine
,05-25 13:50:51.445  9936  9999 W jxcore-log: Platform android
05-25 13:50:51.445  9936  9999 W jxcore-log: 
05-25 13:50:51.445  9936  9999 W jxcore-log: Process ARCH arm
05-25 13:50:51.445  9936  9999 W jxcore-log: 
,05-25 13:50:51.575  9936  9999 I jxcore-log: JXcore Cordova bridge is ready!
05-25 13:50:51.575  9936  9999 I jxcore-log: 
05-25 13:50:51.575  9936  9999 W jxcore-log: JXcore engine is started
,05-25 13:50:51.575  9936  9998 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,05-25 13:50:51.575  9936  9936 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 41 : Application has the required permission.
05-25 13:50:51.575  9936  9936 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,05-25 13:50:52.955  3549  3908 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/5_task.xml.bak
,05-25 13:50:53.055  3549  6068 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
,05-25 13:50:54.735  3549  6068 D SSRM:n  : SIOP:: AP = 360, PST = 315 (W:6), CP = 271, CUR = 147, LCD = 40
,05-25 13:50:54.745  3549  6068 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,05-25 13:50:56.085  3549  6068 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,05-25 13:50:58.535  9936  9999 I jxcore-log: 2017-05-25 11:50:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
05-25 13:50:58.535  9936  9999 I jxcore-log: 
,05-25 13:50:58.535  9936  9999 I jxcore-log: 2017-05-25 11:50:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
05-25 13:50:58.535  9936  9999 I jxcore-log: 
05-25 13:50:58.535  9936  9999 I jxcore-log: 2017-05-25 11:50:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
05-25 13:50:58.535  9936  9999 I jxcore-log: 
,05-25 13:50:58.545  9936  9999 D BluetoothAdapter: STATE_ON
05-25 13:50:58.545  9936  9999 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
05-25 13:50:58.545  9936  9999 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-25 13:50:58.545  9936  9999 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-25 13:50:58.545  9936  9999 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-25 13:50:58.545  9936  9999 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-25 13:50:58.545  9936  9999 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-25 13:50:58.545  9936  9999 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-25 13:50:58.545  9936  9999 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-25 13:50:58.545  9936  9999 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,05-25 13:50:58.555  9936  9999 D BluetoothAdapter: STATE_ON
,05-25 13:50:58.555  9936  9999 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,05-25 13:50:58.555  9936  9999 I jxcore-log: 2017-05-25 11:50:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
05-25 13:50:58.555  9936  9999 I jxcore-log: 
05-25 13:50:58.565  9936  9999 I jxcore-log: 2017-05-25 11:50:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
05-25 13:50:58.565  9936  9999 I jxcore-log: 
05-25 13:50:58.565  9936  9999 I jxcore-log: 2017-05-25 11:50:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
05-25 13:50:58.565  9936  9999 I jxcore-log: 
,05-25 13:50:58.825  9936  9999 D ExecuteNativeTests: Running unit tests
05-25 13:50:58.825  9936  9999 D BluetoothAdapter: enable()
,05-25 13:50:58.835  9936  9999 D BluetoothAdapter: enable(): BT is already enabled..!
,05-25 13:50:58.845  3549  3603 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b0cd3f3 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{44442de 4889:com.samsung.android.providers.context/u0a7}
,05-25 13:50:58.845  9936  9999 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,05-25 13:50:58.845  3549  4430 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,05-25 13:50:58.855  3549  4430 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,05-25 13:50:58.855  3549  4430 D WifiService: setWifiEnabled: true pid=9936, uid=10074
,05-25 13:50:58.865  3549  4430 W ActivityManager: Permission Denial: getCurrentUser() from pid=9936, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
,05-25 13:50:58.875  3549  4430 W WifiService: Failed getting userId using ActivityManagerNative
05-25 13:50:58.875  3549  4430 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9936, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
05-25 13:50:58.875  3549  4430 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-25 13:50:58.875  3549  4430 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
05-25 13:50:58.875  3549  4430 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
05-25 13:50:58.875  3549  4430 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
05-25 13:50:58.875  3549  4430 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
,05-25 13:50:58.875  3549  3859 D WifiBigDataLog: getJsonFormat() - feature : ONOF
05-25 13:50:58.875  3549  4430 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
05-25 13:50:58.875  3549  4430 D SettingsProvider: isChangeAllowed() : name = wifi_on
05-25 13:50:58.875  3549  3863 D WifiController: [FCC]setFccChannel() is called !!!
05-25 13:50:58.875  3549  3863 D WifiStateMachine: setFccChannel: channel = 0
,05-25 13:50:58.875  3549  3863 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
05-25 13:50:58.875  3549  3859 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
05-25 13:50:58.875  3549  3859 D WifiBigDataLog: init : 
,05-25 13:50:58.885  3549  3859 D WifiStateMachine: setFccChannelNative: channel = 0
,05-25 13:50:58.885  3549  3859 D WifiNative-wlan0: callSECApiInt - ID [230]
,05-25 13:50:58.895  3549  3603 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{dfc78b0 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{44442de 4889:com.samsung.android.providers.context/u0a7}
,05-25 13:50:59.155  3549  3981 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-25 13:50:59.155  3549  3981 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:50:59.155  3549  3981 D BatteryService: online:4, current avg:-237, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:168
05-25 13:50:59.155  3549  3549 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:50:59.155  3549  3549 I MotionRecognitionService: Plugged
05-25 13:50:59.155  3549  3549 D MotionRecognitionService:   cableConnection= 1
05-25 13:50:59.155  3549  3549 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:50:59.155  3549  3549 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:50:59.165  3549  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:50:59.165  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,05-25 13:50:59.165  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
05-25 13:50:59.165  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:50:59.175  4905  4905 D CommonServiceConfiguration: getStringValueSetting
05-25 13:50:59.175  4857  4857 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-25 13:50:59.175  4857  5186 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-25 13:50:59.185  4905  4905 D BatteryMonitor: new battery level: 100
,05-25 13:50:59.205  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
05-25 13:50:59.205  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:50:59.995  3549  3813 V AlarmManager: Expired Alarm result :8
,05-25 13:50:59.995  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,05-25 13:51:00.005  3949  3949 D KeyguardUpdateMonitor: handleTimeUpdate
,05-25 13:51:00.015  3949  3949 D Clock   : received broadcast android.intent.action.TIME_TICK
,05-25 13:51:00.045  3549  3637 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,05-25 13:51:00.065  3549  3637 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,05-25 13:51:00.085  3949  3949 D DateView: received broadcast android.intent.action.TIME_TICK
,05-25 13:51:00.105  4724  4724 D [Weather Widget]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,05-25 13:51:00.115  4724  4724 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EEFA9050249635C043F7E254E316C2550]}
,05-25 13:51:00.115  4724  4724 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EAB01DC5C99149A39F887E17599325AFBFF089086AA9902184ADA25758C536FE2]}
,05-25 13:51:00.115  4724  4724 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EFF0B905BDFF72B69FB632A6CB072B41F95D2E6F4F84443284E97F40042D431D8350388453A923ABD8469D82798FA7548]}
,05-25 13:51:00.115  4724  4724 D [Weather Widget]  : {[A1AF0F6A1A65A89C43D705938923D0FEFB71880C4E84718DA0A3E1F383E54FB27A4284D9BEDF7BAA2ABFFE671EB65C640578FF9DE16A23BFE3280A9DCDBB09A0087A09617A4D2E4C8CA19F92E92E7F081209ADB459A570E8D870EBA866E0F8996B7829FAC6D5657983C2B9D0F41D1C4D]}
,05-25 13:51:00.115  4724  4724 D [Weather Widget]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]},
,05-25 13:51:00.195  3549  4285 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,05-25 13:51:00.195  3549  4285 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4322, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:51:00.195  3549  4285 D BatteryService: online:4, current avg:-203, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:18
05-25 13:51:00.195  3549  3549 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:51:00.205  3549  3549 I MotionRecognitionService: Plugged
05-25 13:51:00.205  3549  3549 D MotionRecognitionService:   cableConnection= 1
05-25 13:51:00.205  3549  3549 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:51:00.205  3549  3549 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:51:00.205  3549  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:51:00.205  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
05-25 13:51:00.205  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
,05-25 13:51:00.205  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:51:00.225  4905  4905 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:51:00.235  4857  4857 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-25 13:51:00.235  4857  5186 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-25 13:51:00.245  4905  4905 D BatteryMonitor: new battery level: 100
,05-25 13:51:00.255  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:00.255  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:00.325  3549  3986 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,05-25 13:51:00.325  3549  3986 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4322, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:51:00.325  3549  3986 D BatteryService: online:4, current avg:-203, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:102
05-25 13:51:00.325  3549  3549 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:51:00.335  3549  3549 I MotionRecognitionService: Plugged
,05-25 13:51:00.335  3549  3549 D MotionRecognitionService:   cableConnection= 1
05-25 13:51:00.335  3549  3549 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:51:00.335  3549  3549 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:51:00.335  3549  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:51:00.335  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
05-25 13:51:00.335  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
,05-25 13:51:00.335  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:51:00.345  4905  4905 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:51:00.345  4857  4857 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,05-25 13:51:00.345  4857  5186 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-25 13:51:00.355  4905  4905 D BatteryMonitor: new battery level: 100
05-25 13:51:00.365  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
05-25 13:51:00.365  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:03.345  3549  4131 E Watchdog: !@Sync 9 [05-25 13:51:03.353]
,05-25 13:51:04.775  3549  6068 D SSRM:n  : SIOP:: AP = 350, PST = 325 (W:6), CP = 283, CUR = -203, LCD = 40
,05-25 13:51:04.795  3549  6068 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,05-25 13:51:08.885  9936  9999 I com.test.thalitest.ThaliTestRunner: Running UT
,05-25 13:51:08.945  9936  9999 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
05-25 13:51:08.945  9936  9999 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@47866d9 added. We now have 2 listener(s)
05-25 13:51:08.945  9936  9999 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@47866d9 added. We now have 3 listener(s)
05-25 13:51:08.945  9936  9999 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
05-25 13:51:08.945  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: ", Bluetooth MAC address: "44:78:3E:94:4A:3E"Peer extra info: "256
05-25 13:51:08.945  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
05-25 13:51:08.945  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: null
05-25 13:51:08.945  9936  9999 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
05-25 13:51:08.945  9936  9999 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b70189e added. We now have 4 listener(s)
05-25 13:51:08.945  9936  9999 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,05-25 13:51:08.955  9936  9999 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,05-25 13:51:08.965  9936  9999 D BluetoothAdapter: STATE_ON
,05-25 13:51:08.965  9936  9999 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
05-25 13:51:08.965  9936  9999 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
05-25 13:51:08.965  9936  9999 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
05-25 13:51:08.965  9936  9999 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
05-25 13:51:08.965  9936  9999 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [00:11:22:33:44:55] timed out
05-25 13:51:08.975  9936  9999 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
05-25 13:51:08.975  9936  9999 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
05-25 13:51:08.975  9936  9999 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
05-25 13:51:08.975  9936  9999 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
05-25 13:51:08.975  9936  9999 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
05-25 13:51:08.975  9936  9999 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,05-25 13:51:08.975  9936  9999 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
,05-25 13:51:08.975  9936  9999 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
,05-25 13:51:08.975  9936  9999 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,05-25 13:51:08.985  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,05-25 13:51:08.995  9936  9999 D BluetoothAdapter: STATE_ON
,05-25 13:51:08.995  9936  9999 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
05-25 13:51:08.995  9936  9999 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-25 13:51:08.995  9936  9999 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-25 13:51:08.995  9936  9999 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-25 13:51:08.995  9936  9999 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-25 13:51:08.995  9936  9999 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-25 13:51:08.995  9936  9999 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-25 13:51:08.995  9936  9999 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-25 13:51:08.995  9936  9999 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,05-25 13:51:08.995  9936  9999 D io.jxcore.node.ConnectivityMonitor: start: OK
05-25 13:51:08.995  9936  9999 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 0
05-25 13:51:08.995  9936  9999 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 256 -> 0
05-25 13:51:08.995  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,05-25 13:51:09.005  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":0,"address":"44:78:3E:94:4A:3E"}
,05-25 13:51:09.005  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":0,"address":"44:78:3E:94:4A:3E"}
05-25 13:51:09.005  9936  9999 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:51:09.005  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,05-25 13:51:09.005  9936  9936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
05-25 13:51:09.005  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":0,"address":"44:78:3E:94:4A:3E"}
05-25 13:51:09.005  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":0,"address":"44:78:3E:94:4A:3E"}
05-25 13:51:09.005  9936  9999 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:51:09.005  9936  9999 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
05-25 13:51:09.005  9936  9999 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
05-25 13:51:09.005  9936  9999 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,05-25 13:51:09.005  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
05-25 13:51:09.005  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
05-25 13:51:09.005  9936  9936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:51:09.005  9936  9999 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
05-25 13:51:09.005  9936  9999 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,05-25 13:51:09.005  9936  9999 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
05-25 13:51:09.005  9936  9999 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
05-25 13:51:09.005  9936  9999 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
05-25 13:51:09.005  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,05-25 13:51:09.005  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,05-25 13:51:09.015  9936 10007 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,05-25 13:51:09.015  9936  9936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
05-25 13:51:09.015  9936  9936 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,05-25 13:51:09.015  9936  9999 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,05-25 13:51:09.015  9936  9999 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
05-25 13:51:09.015  9936  9999 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
05-25 13:51:09.015  9936 10007 D BluetoothSocket: bindListen(): myUserId = 0
,05-25 13:51:09.015  9936 10007 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,05-25 13:51:09.025  9936  9999 D BluetoothAdapter: STATE_ON
,05-25 13:51:09.025  9936  9999 D BluetoothAdapter: STATE_ON
,05-25 13:51:09.025  9936  9999 D BluetoothAdapter: STATE_ON
,05-25 13:51:09.025  9936 10007 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
05-25 13:51:09.025  9936 10007 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@47f9795, port: 6, type: 1, local socket address: null, socket type: 0
,05-25 13:51:09.035  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:09.035  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,05-25 13:51:09.035  9936  9999 D BluetoothAdapter: STATE_ON
,05-25 13:51:09.035  9936  9999 D BluetoothAdapter: STATE_ON
,05-25 13:51:09.035  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,05-25 13:51:09.035  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,05-25 13:51:09.035  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 0
,05-25 13:51:09.035  9936  9999 D BluetoothAdapter: STATE_ON
,05-25 13:51:09.045  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:51:09.045  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:09.045  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
05-25 13:51:09.045  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
05-25 13:51:09.045  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "1e0175e0-0d83-4d02-aa60-d3c622da762e", Bluetooth MAC address: "44:78:3E:94:4A:3E"
,05-25 13:51:09.045  9936  9999 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 44 78 3E 94 4A 3E
,05-25 13:51:09.045  9936  9999 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[0, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,05-25 13:51:09.045  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[0, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-25 13:51:09.045  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:09.045  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[0, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:51:09.045  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
05-25 13:51:09.045  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[0, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-25 13:51:09.045  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:09.045  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:09.045  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[0, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:51:09.055  9936  9999 D BluetoothAdapter: STATE_ON
,05-25 13:51:09.055  9936  9999 D BluetoothAdapter: STATE_ON
,05-25 13:51:09.055  9936  9999 D BluetoothLeAdvertiser: start advertising
,05-25 13:51:09.055  9936  9999 D BluetoothAdapter: STATE_ON
,05-25 13:51:09.065  4857  4876 D BtGatt.GattService: registerClient() - UUID=439a80dc-b55e-41e6-9be9-d586c13b36f4
,05-25 13:51:09.105  3549  4435 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-25 13:51:09.105  3549  4435 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4325, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:51:09.105  3549  4435 D BatteryService: online:4, current avg:-3, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:41
05-25 13:51:09.105  3549  3549 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:51:09.105  3549  3549 I MotionRecognitionService: Plugged
,05-25 13:51:09.105  3549  3549 D MotionRecognitionService:   cableConnection= 1
05-25 13:51:09.105  3549  3549 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:51:09.105  3549  3549 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:51:09.105  3549  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:51:09.105  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
05-25 13:51:09.105  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
,05-25 13:51:09.105  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:51:09.115  4857  5022 D BtGatt.GattService: onClientRegistered() - UUID=439a80dc-b55e-41e6-9be9-d586c13b36f4, clientIf=7
,05-25 13:51:09.115  9936  9946 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,05-25 13:51:09.115  4857  5221 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,05-25 13:51:09.115  4905  4905 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:51:09.125  4857  4857 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-25 13:51:09.125  4857  5186 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-25 13:51:09.125  4905  4905 D BatteryMonitor: new battery level: 100
,05-25 13:51:09.135  4857  5221 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,05-25 13:51:09.135  4857  5221 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
05-25 13:51:09.135  4857  5068 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
05-25 13:51:09.135  4857  5068 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 25, currDate: 25
,05-25 13:51:09.135  4857  5053 D BtGatt.AdvertiseManager: message : 0
05-25 13:51:09.135  4857  5053 D BtGatt.AdvertiseManager: number of adv instance running = 0
,05-25 13:51:09.135  4857  5053 D BtGatt.AdvertiseManager: size of list is =0
,05-25 13:51:09.145  4857  5053 D BtGatt.AdvertiseManager: starting advertising
,05-25 13:51:09.145  4857  5053 D BtGatt.AdvertiseManager: isStandardAdv = false
,05-25 13:51:09.155  3549  3981 V AlarmManager:  remove PendingIntent] PendingIntent{7baadc8: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:09.155  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:09.155  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
05-25 13:51:09.155  4857  5068 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.thaliproject.thalitest : 29
05-25 13:51:09.155  4857  5022 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,05-25 13:51:09.155  4857  5068 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.thaliproject.thalitest@LowLatency : 24928551
,05-25 13:51:09.155  4857  5068 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.thaliproject.thalitest@LowLatency : 2
05-25 13:51:09.155  3549  4432 V AlarmManager:  remove PendingIntent] PendingIntent{c1f1e61: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
05-25 13:51:09.155  4857  5068 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
05-25 13:51:09.155  4857  5053 D BtGatt.AdvertiseManager: starting multi advertising
05-25 13:51:09.155  4857  5068 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 3 => 3
,05-25 13:51:09.155  4857  5022 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
05-25 13:51:09.155  4857  5053 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
05-25 13:51:09.155  4857  5053 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
05-25 13:51:09.155  4857  5053 D BtGatt.AdvertiseManager: postCallback clientIf = 7 status = 0
05-25 13:51:09.155  4857  5053 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=7, status=0, isStart=true
,05-25 13:51:09.165  9936  9947 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
05-25 13:51:09.165  3549  4931 V AlarmManager:  remove PendingIntent] PendingIntent{487ad86: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:09.165  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:09.165  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:09.165  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
05-25 13:51:09.165  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:09.165  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:09.165  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:09.165  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:09.165  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:09.165  9936  9999 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
05-25 13:51:09.165  9936  9999 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
05-25 13:51:09.165  9936  9999 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:09.165  3549  3567 V AlarmManager:  remove PendingIntent] PendingIntent{47e647: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:09.165  9936  9999 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:51:09.165  9936  9999 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:09.165  9936  9999 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:09.165  9936  9999 I io.jxcore.node.ConnectionHelper: start: OK
05-25 13:51:09.165  9936  9936 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
05-25 13:51:09.165  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
05-25 13:51:09.165  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
05-25 13:51:09.165  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
05-25 13:51:09.175  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
05-25 13:51:09.175  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
05-25 13:51:09.175  9936  9936 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
05-25 13:51:09.175  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
05-25 13:51:09.175  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
05-25 13:51:09.175  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
05-25 13:51:09.175  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,05-25 13:51:09.175  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
05-25 13:51:09.175  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
05-25 13:51:09.175  3549  3568 V AlarmManager:  remove PendingIntent] PendingIntent{8b0de74: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
05-25 13:51:09.175  9936  9936 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
05-25 13:51:09.175  9936  9936 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
05-25 13:51:09.175  9936  9936 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
05-25 13:51:09.175  9936  9936 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
05-25 13:51:09.175  3549  4931 V AlarmManager:  remove PendingIntent] PendingIntent{8ce3f9d: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
05-25 13:51:09.175  9936  9936 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
05-25 13:51:09.175  9936  9936 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
05-25 13:51:09.175  9936  9936 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
05-25 13:51:09.185  3549  3567 V AlarmManager:  remove PendingIntent] PendingIntent{7a11c12: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:09.225  3549  3981 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,05-25 13:51:09.225  3549  3981 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4323, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:51:09.225  3549  3981 D BatteryService: online:4, current avg:-3, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:25
05-25 13:51:09.225  3549  3549 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:51:09.235  3549  3549 I MotionRecognitionService: Plugged
05-25 13:51:09.235  3549  3549 D MotionRecognitionService:   cableConnection= 1
05-25 13:51:09.235  3549  3549 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:51:09.235  3549  3549 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:51:09.235  3549  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:51:09.235  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
05-25 13:51:09.235  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
,05-25 13:51:09.235  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:51:09.245  4905  4905 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:51:09.245  4857  4857 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-25 13:51:09.245  4857  5186 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-25 13:51:09.245  4905  4905 D BatteryMonitor: new battery level: 100
,05-25 13:51:09.255  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:09.255  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:09.285  3549  4432 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,05-25 13:51:09.345  3549  6115 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,05-25 13:51:09.395  3549  4066 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,05-25 13:51:09.395  3549  4066 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4329, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:51:09.395  3549  4066 D BatteryService: online:4, current avg:-1, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:112
05-25 13:51:09.395  3549  3549 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:51:09.395  3549  3549 I MotionRecognitionService: Plugged
,05-25 13:51:09.395  3549  3549 D MotionRecognitionService:   cableConnection= 1
05-25 13:51:09.395  3549  3549 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:51:09.395  3549  3549 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:51:09.405  3549  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:51:09.405  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
05-25 13:51:09.405  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
,05-25 13:51:09.405  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:51:09.415  4905  4905 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:51:09.415  4857  4857 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-25 13:51:09.415  4857  5186 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-25 13:51:09.415  4905  4905 D BatteryMonitor: new battery level: 100
,05-25 13:51:09.425  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:09.425  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:09.675  9936 10010 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,05-25 13:51:09.675  9936  9999 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,05-25 13:51:09.675  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [00:11:22:33:44:55]
05-25 13:51:09.675  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [10:010:010:010:010:010]
05-25 13:51:09.675  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [11:110:110:110:110:110]
05-25 13:51:09.675  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [12:210:210:210:210:210]
,05-25 13:51:09.675  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [13:310:310:310:310:310]
05-25 13:51:09.675  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [14:410:410:410:410:410]
05-25 13:51:09.675  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [15:510:510:510:510:510]
05-25 13:51:09.675  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [16:610:610:610:610:610]
05-25 13:51:09.675  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [17:710:710:710:710:710]
,05-25 13:51:09.675  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [18:810:810:810:810:810]
05-25 13:51:09.675  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [19:910:910:910:910:910]
05-25 13:51:09.675  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [20:1010:1010:1010:1010:1010]
05-25 13:51:09.675  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [21:1110:1110:1110:1110:1110]
,05-25 13:51:09.675  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [22:1210:1210:1210:1210:1210]
05-25 13:51:09.675  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [23:1310:1310:1310:1310:1310]
05-25 13:51:09.675  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [24:1410:1410:1410:1410:1410]
,05-25 13:51:09.675  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [25:1510:1510:1510:1510:1510]
05-25 13:51:09.675  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [26:1610:1610:1610:1610:1610]
05-25 13:51:09.675  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [27:1710:1710:1710:1710:1710]
05-25 13:51:09.675  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [28:1810:1810:1810:1810:1810]
,05-25 13:51:09.675  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [29:1910:1910:1910:1910:1910]
05-25 13:51:09.675  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [30:2010:2010:2010:2010:2010]
05-25 13:51:09.675  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [31:2110:2110:2110:2110:2110]
05-25 13:51:09.675  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [32:2210:2210:2210:2210:2210]
,05-25 13:51:09.675  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [33:2310:2310:2310:2310:2310]
05-25 13:51:09.675  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [34:2410:2410:2410:2410:2410]
05-25 13:51:09.675  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [35:2510:2510:2510:2510:2510]
05-25 13:51:09.675  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [36:2610:2610:2610:2610:2610]
,05-25 13:51:09.675  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [37:2710:2710:2710:2710:2710]
05-25 13:51:09.675  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [38:2810:2810:2810:2810:2810]
05-25 13:51:09.675  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [39:2910:2910:2910:2910:2910]
05-25 13:51:09.675  9936  9999 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,05-25 13:51:09.675  9936  9999 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
05-25 13:51:09.675  9936  9999 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
05-25 13:51:09.675  9936  9999 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,05-25 13:51:09.675  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
05-25 13:51:09.675  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
05-25 13:51:09.675  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,05-25 13:51:09.675  9936 10007 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
05-25 13:51:09.675  9936  9999 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
05-25 13:51:09.675  9936 10007 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,05-25 13:51:09.675  9936  9999 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
05-25 13:51:09.675  9936 10007 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
05-25 13:51:09.675  9936  9936 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,05-25 13:51:09.675  9936  9999 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
05-25 13:51:09.675  9936  9999 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
05-25 13:51:09.685  9936  9999 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:09.685  9936  9999 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,05-25 13:51:09.685  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
05-25 13:51:09.685  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:09.685  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:51:09.685  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:09.685  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:09.685  9936  9999 D BluetoothAdapter: STATE_ON
,05-25 13:51:09.685  9936  9999 D BluetoothAdapter: STATE_ON
05-25 13:51:09.685  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
05-25 13:51:09.695  9936  9999 D BluetoothAdapter: STATE_ON
05-25 13:51:09.695  9936  9999 D BluetoothAdapter: STATE_ON
,05-25 13:51:09.695  9936  9999 D BluetoothLeScanner: could not find callback wrapper
05-25 13:51:09.695  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
05-25 13:51:09.695  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:51:09.695  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:09.695  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:09.695  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,05-25 13:51:09.695  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:51:09.695  9936  9999 D BluetoothAdapter: STATE_ON
,05-25 13:51:09.695  9936  9999 D BluetoothAdapter: STATE_ON
,05-25 13:51:09.695  9936  9999 D BluetoothLeAdvertiser: stop advertising
,05-25 13:51:09.705  4857  4875 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
05-25 13:51:09.705  4857  4875 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
05-25 13:51:09.705  4857  5053 D BtGatt.AdvertiseManager: message : 1
,05-25 13:51:09.705  4857  5068 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
05-25 13:51:09.705  4857  5068 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 25, currDate: 25
05-25 13:51:09.705  4857  5068 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
05-25 13:51:09.705  4857  5068 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 3 => 3
05-25 13:51:09.705  4857  5053 D BtGatt.AdvertiseManager: stop advertise for client =  7
,05-25 13:51:09.705  4857  5068 D BtGatt.GattService: [GSIM LOG]: remove : com.thaliproject.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
05-25 13:51:09.705  4857  5053 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 7
,05-25 13:51:09.705  4857  5053 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,05-25 13:51:09.705  3549  4367 V AlarmManager:  remove PendingIntent] PendingIntent{e129fe3: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:09.715  4857  5022 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
05-25 13:51:09.715  4857  5022 D BtGatt.GattService: Client app is not null!
05-25 13:51:09.715  9936  9947 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
05-25 13:51:09.715  4857  5221 D BtGatt.GattService: unregisterClient() - clientIf=7
,05-25 13:51:09.715  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,05-25 13:51:09.715  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:09.715  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
05-25 13:51:09.715  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:09.715  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:51:09.715  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:09.715  9936  9999 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
05-25 13:51:09.715  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
05-25 13:51:09.715  3549  4931 V AlarmManager:  remove PendingIntent] PendingIntent{7376de0: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
05-25 13:51:09.715  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
05-25 13:51:09.715  9936  9999 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:09.725  9936  9999 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:09.725  9936  9999 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
05-25 13:51:09.725  9936  9999 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:09.725  9936  9999 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:09.725  3549  4170 V AlarmManager:  remove PendingIntent] PendingIntent{1543899: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
05-25 13:51:09.725  9936  9936 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
05-25 13:51:09.725  9936  9936 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
05-25 13:51:09.725  9936  9936 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
05-25 13:51:09.725  9936  9936 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
05-25 13:51:09.725  9936  9936 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
05-25 13:51:09.725  9936  9936 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
05-25 13:51:09.725  9936  9936 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
05-25 13:51:09.725  9936  9936 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
05-25 13:51:09.725  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
05-25 13:51:09.725  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
05-25 13:51:09.725  3549  4367 V AlarmManager:  remove PendingIntent] PendingIntent{970e75e: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
05-25 13:51:09.725  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
05-25 13:51:09.725  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
05-25 13:51:09.725  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
05-25 13:51:09.725  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
05-25 13:51:09.725  9936  9936 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
05-25 13:51:09.725  9936 10015 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
05-25 13:51:09.725  9936  9999 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
05-25 13:51:09.725  9936  9999 V io.jxcore.node.ConnectivityMonitor: start: Already started
05-25 13:51:09.725  9936  9999 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
05-25 13:51:09.725  9936  9999 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
05-25 13:51:09.725  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
05-25 13:51:09.735  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":1,"address":"44:78:3E:94:4A:3E"}
05-25 13:51:09.735  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":1,"address":"44:78:3E:94:4A:3E"}
05-25 13:51:09.735  9936  9999 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:09.735  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
05-25 13:51:09.735  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":1,"address":"44:78:3E:94:4A:3E"}
05-25 13:51:09.735  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":1,"address":"44:78:3E:94:4A:3E"}
05-25 13:51:09.735  9936  9999 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:09.735  9936  9999 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
05-25 13:51:09.735  9936  9999 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
05-25 13:51:09.735  9936  9999 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
05-25 13:51:09.735  3549  4433 V AlarmManager:  remove PendingIntent] PendingIntent{c45573f: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
05-25 13:51:09.735  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
05-25 13:51:09.735  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
05-25 13:51:09.745  9936  9999 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
05-25 13:51:09.745  9936  9999 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
05-25 13:51:09.745  9936  9999 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
05-25 13:51:09.745  3549  4066 V AlarmManager:  remove PendingIntent] PendingIntent{3d5880c: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
05-25 13:51:09.745  9936  9999 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
05-25 13:51:09.745  9936  9999 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
05-25 13:51:09.745  9936  9936 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
05-25 13:51:09.745  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
05-25 13:51:09.745  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
05-25 13:51:09.745  9936 10016 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
05-25 13:51:09.745  9936 10016 D BluetoothSocket: bindListen(): myUserId = 0
05-25 13:51:09.745  9936 10016 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,05-25 13:51:09.755  9936  9999 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
05-25 13:51:09.755  9936  9999 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
05-25 13:51:09.755  9936  9999 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
05-25 13:51:09.755  9936 10016 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
05-25 13:51:09.755  9936 10016 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@1c92f77, port: 6, type: 1, local socket address: null, socket type: 0
05-25 13:51:09.755  3549  4420 V AlarmManager:  remove PendingIntent] PendingIntent{e5918f8: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
05-25 13:51:09.755  9936  9999 D BluetoothAdapter: STATE_ON
05-25 13:51:09.755  9936  9999 D BluetoothAdapter: STATE_ON
05-25 13:51:09.755  9936  9999 D BluetoothAdapter: STATE_ON
05-25 13:51:09.755  3549  3838 V AlarmManager:  remove PendingIntent] PendingIntent{95b61d1: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
05-25 13:51:09.765  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:09.765  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
05-25 13:51:09.765  9936  9999 D BluetoothAdapter: STATE_ON
05-25 13:51:09.765  9936  9999 D BluetoothAdapter: STATE_ON
05-25 13:51:09.765  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
05-25 13:51:09.765  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
05-25 13:51:09.765  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 1
05-25 13:51:09.765  9936  9999 D BluetoothAdapter: STATE_ON
05-25 13:51:09.765  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:09.765  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:09.765  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
05-25 13:51:09.765  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
05-25 13:51:09.765  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "1e0175e0-0d83-4d02-aa60-d3c622da762e", Bluetooth MAC address: "44:78:3E:94:4A:3E"
05-25 13:51:09.765  9936  9999 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 44 78 3E 94 4A 3E
05-25 13:51:09.765  9936  9999 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[1, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-25 13:51:09.765  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[1, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-25 13:51:09.765  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:09.765  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[1, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:09.765  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
05-25 13:51:09.765  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[1, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-25 13:51:09.765  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:09.765  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:09.765  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[1, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:09.775  9936  9999 D BluetoothAdapter: STATE_ON
05-25 13:51:09.775  9936  9999 D BluetoothAdapter: STATE_ON
05-25 13:51:09.775  9936  9999 D BluetoothLeAdvertiser: start advertising
05-25 13:51:09.775  9936  9999 D BluetoothAdapter: STATE_ON
05-25 13:51:09.775  4857  4875 D BtGatt.GattService: registerClient() - UUID=28867708-f2db-45e2-a424-d6da3607200c
,05-25 13:51:09.815  4857  5022 D BtGatt.GattService: onClientRegistered() - UUID=28867708-f2db-45e2-a424-d6da3607200c, clientIf=7
,05-25 13:51:09.815  9936  9946 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,05-25 13:51:09.825  4857  5184 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,05-25 13:51:09.825  4857  5184 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,05-25 13:51:09.825  4857  5184 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
05-25 13:51:09.825  4857  5068 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
05-25 13:51:09.825  4857  5068 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 25, currDate: 25
05-25 13:51:09.825  4857  5053 D BtGatt.AdvertiseManager: message : 0
,05-25 13:51:09.825  4857  5053 D BtGatt.AdvertiseManager: number of adv instance running = 0
05-25 13:51:09.825  4857  5053 D BtGatt.AdvertiseManager: size of list is =0
,05-25 13:51:09.825  4857  5053 D BtGatt.AdvertiseManager: starting advertising
,05-25 13:51:09.825  4857  5053 D BtGatt.AdvertiseManager: isStandardAdv = false
,05-25 13:51:09.835  3549  4435 V AlarmManager:  remove PendingIntent] PendingIntent{c5c8436: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:09.835  4857  5068 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.thaliproject.thalitest : 30
05-25 13:51:09.835  4857  5068 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.thaliproject.thalitest@LowLatency : 24928551
05-25 13:51:09.835  4857  5068 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.thaliproject.thalitest@LowLatency : 2
05-25 13:51:09.835  4857  5068 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
05-25 13:51:09.835  4857  5068 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 3 => 3
05-25 13:51:09.835  4857  5022 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,05-25 13:51:09.835  4857  5053 D BtGatt.AdvertiseManager: starting multi advertising
,05-25 13:51:09.835  3549  4931 V AlarmManager:  remove PendingIntent] PendingIntent{b70ef37: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
05-25 13:51:09.835  4857  5022 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
05-25 13:51:09.835  4857  5053 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
05-25 13:51:09.835  4857  5053 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
05-25 13:51:09.835  4857  5053 D BtGatt.AdvertiseManager: postCallback clientIf = 7 status = 0
05-25 13:51:09.835  4857  5053 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=7, status=0, isStart=true
05-25 13:51:09.835  9936  9947 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
05-25 13:51:09.835  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:09.835  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:09.835  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
05-25 13:51:09.835  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:09.835  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:09.835  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:09.835  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:09.835  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:09.835  9936  9999 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,05-25 13:51:09.845  9936  9999 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,05-25 13:51:09.845  3549  4170 V AlarmManager:  remove PendingIntent] PendingIntent{382cca4: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
05-25 13:51:09.845  9936  9999 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:09.845  9936  9999 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: seems that updateState call different BlePeerDiscoverer
05-25 13:51:09.845  9936  9999 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:09.845  9936  9999 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:09.845  9936  9999 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:09.845  9936  9999 I io.jxcore.node.ConnectionHelper: start: OK
,05-25 13:51:09.845  9936  9936 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
05-25 13:51:09.845  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
05-25 13:51:09.845  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
05-25 13:51:09.845  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,05-25 13:51:09.845  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
05-25 13:51:09.845  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
05-25 13:51:09.845  3549  4285 V AlarmManager:  remove PendingIntent] PendingIntent{3e34a0d: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
05-25 13:51:09.845  9936  9936 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,05-25 13:51:09.845  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
05-25 13:51:09.845  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
05-25 13:51:09.845  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
05-25 13:51:09.845  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
05-25 13:51:09.845  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
05-25 13:51:09.845  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
05-25 13:51:09.845  9936  9936 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
05-25 13:51:09.845  9936  9936 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,05-25 13:51:09.845  9936  9936 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
05-25 13:51:09.845  9936  9936 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
05-25 13:51:09.845  9936  9936 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,05-25 13:51:09.855  3549  4430 V AlarmManager:  remove PendingIntent] PendingIntent{b64adc2: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
05-25 13:51:09.845  9936  9936 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
05-25 13:51:09.845  9936  9936 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,05-25 13:51:09.855  3549  4367 V AlarmManager:  remove PendingIntent] PendingIntent{cdb47d3: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:09.855  3549  4420 V AlarmManager:  remove PendingIntent] PendingIntent{9720f10: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:09.865  3549  3981 V AlarmManager:  remove PendingIntent] PendingIntent{c877a09: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:09.915  3549  3838 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,05-25 13:51:09.915  3549  3838 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:51:09.915  3549  3838 D BatteryService: online:4, current avg:3, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:82
05-25 13:51:09.915  3549  3549 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:51:09.915  3549  3549 I MotionRecognitionService: Plugged
,05-25 13:51:09.915  3549  3549 D MotionRecognitionService:   cableConnection= 1
05-25 13:51:09.915  3549  3549 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:51:09.915  3549  3549 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:51:09.915  3549  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:51:09.915  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,05-25 13:51:09.925  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
05-25 13:51:09.915  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
,05-25 13:51:09.925  4905  4905 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:51:09.925  4857  4857 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-25 13:51:09.925  4857  5186 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-25 13:51:09.935  4905  4905 D BatteryMonitor: new battery level: 100
,05-25 13:51:09.945  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
05-25 13:51:09.945  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:10.025  3549  4066 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,05-25 13:51:10.125  3549  4170 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,05-25 13:51:10.125  3549  4170 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4328, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:51:10.125  3549  4170 D BatteryService: online:4, current avg:5, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:143
05-25 13:51:10.125  3549  3549 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:51:10.125  3549  3549 I MotionRecognitionService: Plugged
05-25 13:51:10.125  3549  3549 D MotionRecognitionService:   cableConnection= 1
05-25 13:51:10.125  3549  3549 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:51:10.125  3549  3549 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:51:10.135  3549  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:51:10.135  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,05-25 13:51:10.135  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
,05-25 13:51:10.135  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:51:10.145  4905  4905 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:51:10.145  4857  4857 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-25 13:51:10.145  4857  5186 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-25 13:51:10.145  4905  4905 D BatteryMonitor: new battery level: 100
,05-25 13:51:10.165  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
05-25 13:51:10.165  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:10.345  9936 10018 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,05-25 13:51:10.355  9936  9936 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
05-25 13:51:10.355  9936  9936 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
05-25 13:51:10.355  9936  9936 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
05-25 13:51:10.355  9936  9999 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
05-25 13:51:10.355  9936  9999 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
05-25 13:51:10.355  9936  9999 V io.jxcore.node.ConnectivityMonitor: start: Already started
05-25 13:51:10.355  9936  9999 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
05-25 13:51:10.355  9936  9999 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
05-25 13:51:10.355  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,05-25 13:51:10.365  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":2,"address":"44:78:3E:94:4A:3E"}
,05-25 13:51:10.365  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":2,"address":"44:78:3E:94:4A:3E"}
05-25 13:51:10.365  9936  9999 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:10.365  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,05-25 13:51:10.365  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":2,"address":"44:78:3E:94:4A:3E"}
,05-25 13:51:10.365  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":2,"address":"44:78:3E:94:4A:3E"}
,05-25 13:51:10.375  9936  9999 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:51:10.375  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
05-25 13:51:10.375  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 25730
05-25 13:51:10.375  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
05-25 13:51:10.375  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 2
05-25 13:51:10.375  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
05-25 13:51:10.375  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
05-25 13:51:10.375  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
05-25 13:51:10.375  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
05-25 13:51:10.375  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
05-25 13:51:10.375  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:10.375  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 2
05-25 13:51:10.375  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted true Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:10.375  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop advertiser Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:51:10.375  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:10.375  9936  9999 D BluetoothAdapter: STATE_ON
,05-25 13:51:10.375  9936  9999 D BluetoothAdapter: STATE_ON
,05-25 13:51:10.375  9936  9999 D BluetoothLeAdvertiser: stop advertising
,05-25 13:51:10.385  4857  4875 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,05-25 13:51:10.385  4857  4875 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
05-25 13:51:10.385  4857  5053 D BtGatt.AdvertiseManager: message : 1
05-25 13:51:10.385  4857  5068 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
05-25 13:51:10.385  4857  5068 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 25, currDate: 25
,05-25 13:51:10.385  4857  5068 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
05-25 13:51:10.385  4857  5068 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 3 => 3
05-25 13:51:10.385  4857  5068 D BtGatt.GattService: [GSIM LOG]: remove : com.thaliproject.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
05-25 13:51:10.385  4857  5053 D BtGatt.AdvertiseManager: stop advertise for client =  7
05-25 13:51:10.385  4857  5053 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 7
,05-25 13:51:10.385  4857  5053 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
05-25 13:51:10.385  3549  4420 V AlarmManager:  remove PendingIntent] PendingIntent{8d3e40e: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:10.395  4857  5022 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
05-25 13:51:10.395  4857  5022 D BtGatt.GattService: Client app is not null!
05-25 13:51:10.395  9936  9946 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
05-25 13:51:10.395  4857  5184 D BtGatt.GattService: unregisterClient() - clientIf=7
,05-25 13:51:10.395  3549  3986 V AlarmManager:  remove PendingIntent] PendingIntent{2888e2f: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
05-25 13:51:10.395  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
05-25 13:51:10.395  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:10.395  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
05-25 13:51:10.395  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:10.395  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:10.395  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:10.395  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
05-25 13:51:10.395  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:10.395  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:10.395  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:10.395  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
05-25 13:51:10.395  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
05-25 13:51:10.395  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "1e0175e0-0d83-4d02-aa60-d3c622da762e", Bluetooth MAC address: "44:78:3E:94:4A:3E"
05-25 13:51:10.395  9936  9999 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 44 78 3E 94 4A 3E
05-25 13:51:10.395  9936  9999 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[2, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-25 13:51:10.395  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[2, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-25 13:51:10.395  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:10.405  3549  4430 V AlarmManager:  remove PendingIntent] PendingIntent{6d10c3c: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
05-25 13:51:10.395  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[2, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:10.395  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
05-25 13:51:10.395  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[2, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-25 13:51:10.395  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:10.395  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:10.395  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[2, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:10.405  9936  9999 D BluetoothAdapter: STATE_ON
05-25 13:51:10.405  9936  9999 D BluetoothAdapter: STATE_ON
05-25 13:51:10.405  9936  9999 D BluetoothLeAdvertiser: start advertising
05-25 13:51:10.405  9936  9999 D BluetoothAdapter: STATE_ON
05-25 13:51:10.405  3549  4420 V AlarmManager:  remove PendingIntent] PendingIntent{b24adc5: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
05-25 13:51:10.415  4857  5221 D BtGatt.GattService: registerClient() - UUID=07234ea2-639d-4740-b9aa-6c94cb64b04a
05-25 13:51:10.415  3549  3567 V AlarmManager:  remove PendingIntent] PendingIntent{6ee331a: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
05-25 13:51:10.415  3549  4066 V AlarmManager:  remove PendingIntent] PendingIntent{719de4b: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
05-25 13:51:10.425  3549  4285 V AlarmManager:  remove PendingIntent] PendingIntent{c0b028: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
05-25 13:51:10.425  3549  3986 V AlarmManager:  remove PendingIntent] PendingIntent{ea76141: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:10.455  4857  5022 D BtGatt.GattService: onClientRegistered() - UUID=07234ea2-639d-4740-b9aa-6c94cb64b04a, clientIf=7
,05-25 13:51:10.455  9936  9947 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,05-25 13:51:10.455  4857  4875 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,05-25 13:51:10.465  4857  4875 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
05-25 13:51:10.465  4857  4875 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
05-25 13:51:10.465  4857  5053 D BtGatt.AdvertiseManager: message : 0
05-25 13:51:10.465  4857  5068 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
,05-25 13:51:10.465  4857  5068 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 25, currDate: 25
05-25 13:51:10.465  4857  5053 D BtGatt.AdvertiseManager: number of adv instance running = 0
,05-25 13:51:10.465  4857  5053 D BtGatt.AdvertiseManager: size of list is =0
,05-25 13:51:10.465  4857  5053 D BtGatt.AdvertiseManager: starting advertising
,05-25 13:51:10.465  4857  5053 D BtGatt.AdvertiseManager: isStandardAdv = false
,05-25 13:51:10.475  4857  5068 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.thaliproject.thalitest : 31
,05-25 13:51:10.475  4857  5068 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.thaliproject.thalitest@LowLatency : 24928551
05-25 13:51:10.475  4857  5068 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.thaliproject.thalitest@LowLatency : 2
05-25 13:51:10.475  4857  5068 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
05-25 13:51:10.475  4857  5068 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 3 => 3
,05-25 13:51:10.475  3549  4420 V AlarmManager:  remove PendingIntent] PendingIntent{62c66e6: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:10.475  4857  5022 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,05-25 13:51:10.475  4857  5053 D BtGatt.AdvertiseManager: starting multi advertising
,05-25 13:51:10.485  3549  4430 V AlarmManager:  remove PendingIntent] PendingIntent{4261427: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:10.485  4857  5022 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
05-25 13:51:10.485  4857  5053 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
05-25 13:51:10.485  4857  5053 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
05-25 13:51:10.485  4857  5053 D BtGatt.AdvertiseManager: postCallback clientIf = 7 status = 0
05-25 13:51:10.485  4857  5053 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=7, status=0, isStart=true
,05-25 13:51:10.485  9936  9946 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
05-25 13:51:10.485  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
05-25 13:51:10.485  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:10.485  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:10.485  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
05-25 13:51:10.485  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:10.485  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:10.485  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:10.485  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:10.485  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:10.485  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser started = true Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:10.485  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
05-25 13:51:10.485  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
05-25 13:51:10.485  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,05-25 13:51:10.485  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
05-25 13:51:10.485  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted false Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:10.485  3549  4367 V AlarmManager:  remove PendingIntent] PendingIntent{b84a6d4: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
05-25 13:51:10.485  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
05-25 13:51:10.485  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
,05-25 13:51:10.485  9936  9999 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
05-25 13:51:10.485  9936  9999 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
05-25 13:51:10.485  9936  9936 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
05-25 13:51:10.485  9936  9999 I io.jxcore.node.ConnectionHelper: start: OK
05-25 13:51:10.485  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,05-25 13:51:10.485  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
05-25 13:51:10.485  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
05-25 13:51:10.485  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
05-25 13:51:10.485  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
05-25 13:51:10.485  9936 10025 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
05-25 13:51:10.485  9936  9999 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
05-25 13:51:10.485  9936  9999 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
05-25 13:51:10.485  9936  9999 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
05-25 13:51:10.485  9936  9999 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
05-25 13:51:10.485  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
05-25 13:51:10.485  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
05-25 13:51:10.485  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
05-25 13:51:10.485  9936  9999 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
05-25 13:51:10.485  9936  9999 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
05-25 13:51:10.485  9936  9999 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
05-25 13:51:10.485  9936  9999 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
05-25 13:51:10.485  9936  9936 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,05-25 13:51:10.495  3549  4432 V AlarmManager:  remove PendingIntent] PendingIntent{e47d07d: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
05-25 13:51:10.495  9936 10016 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
05-25 13:51:10.495  9936  9999 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:10.495  9936 10016 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
05-25 13:51:10.495  9936  9999 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
05-25 13:51:10.495  9936 10016 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
05-25 13:51:10.495  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,05-25 13:51:10.495  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:10.495  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:10.495  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:10.495  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:10.495  9936  9999 D BluetoothAdapter: STATE_ON
,05-25 13:51:10.495  9936  9999 D BluetoothAdapter: STATE_ON
05-25 13:51:10.495  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
05-25 13:51:10.495  9936  9999 D BluetoothAdapter: STATE_ON
,05-25 13:51:10.495  9936  9999 D BluetoothAdapter: STATE_ON
,05-25 13:51:10.495  9936  9999 D BluetoothLeScanner: could not find callback wrapper
05-25 13:51:10.495  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,05-25 13:51:10.495  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:51:10.495  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:10.495  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:10.495  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
05-25 13:51:10.495  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:10.505  9936  9999 D BluetoothAdapter: STATE_ON
,05-25 13:51:10.505  3549  4430 V AlarmManager:  remove PendingIntent] PendingIntent{3c80b72: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:10.505  9936  9999 D BluetoothAdapter: STATE_ON
,05-25 13:51:10.505  9936  9999 D BluetoothLeAdvertiser: stop advertising
,05-25 13:51:10.505  3549  4432 V AlarmManager:  remove PendingIntent] PendingIntent{bd5cbc3: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:10.505  4857  5221 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
05-25 13:51:10.505  4857  5221 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
05-25 13:51:10.505  4857  5053 D BtGatt.AdvertiseManager: message : 1
05-25 13:51:10.505  4857  5068 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
,05-25 13:51:10.505  4857  5068 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 25, currDate: 25
05-25 13:51:10.505  4857  5068 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
05-25 13:51:10.515  4857  5068 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 3 => 3
05-25 13:51:10.515  4857  5068 D BtGatt.GattService: [GSIM LOG]: remove : com.thaliproject.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
05-25 13:51:10.515  4857  5053 D BtGatt.AdvertiseManager: stop advertise for client =  7
05-25 13:51:10.515  4857  5053 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 7
,05-25 13:51:10.515  4857  5053 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,05-25 13:51:10.515  4857  5022 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
05-25 13:51:10.515  4857  5022 D BtGatt.GattService: Client app is not null!
05-25 13:51:10.515  9936  9947 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,05-25 13:51:10.515  4857  4875 D BtGatt.GattService: unregisterClient() - clientIf=7
,05-25 13:51:10.515  3549  3568 V AlarmManager:  remove PendingIntent] PendingIntent{9ef5c40: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:10.515  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
05-25 13:51:10.515  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:10.515  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
05-25 13:51:10.515  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:10.525  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:10.525  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:10.525  9936  9999 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
05-25 13:51:10.525  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,05-25 13:51:10.525  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,05-25 13:51:10.525  9936  9999 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:10.525  3549  3567 V AlarmManager:  remove PendingIntent] PendingIntent{285f779: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:10.525  9936  9999 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:10.525  9936  9999 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
05-25 13:51:10.525  9936  9999 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:10.525  9936  9999 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:51:10.525  9936  9936 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
05-25 13:51:10.525  9936  9936 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
05-25 13:51:10.525  9936  9936 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
05-25 13:51:10.525  9936  9936 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
05-25 13:51:10.525  9936  9936 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
05-25 13:51:10.525  9936  9936 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
05-25 13:51:10.525  9936  9936 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
05-25 13:51:10.525  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
05-25 13:51:10.525  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
05-25 13:51:10.525  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
05-25 13:51:10.525  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
05-25 13:51:10.525  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
05-25 13:51:10.525  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
05-25 13:51:10.525  9936  9936 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
05-25 13:51:10.525  9936 10026 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
05-25 13:51:10.525  9936  9999 I io.jxcore.node.ConnectionHelperTest: Starting test: testListenToConnectivityChanges
05-25 13:51:10.525  3549  4420 V AlarmManager:  remove PendingIntent] PendingIntent{5076cbe: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:10.535  9936  9999 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
05-25 13:51:10.535  9936  9999 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d33b849 added. We now have 3 listener(s)
05-25 13:51:10.535  9936  9999 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d33b849 added. We now have 5 listener(s)
05-25 13:51:10.535  9936  9999 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,05-25 13:51:10.535  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":2,"address":"44:78:3E:94:4A:3E"}
,05-25 13:51:10.535  3549  3981 V AlarmManager:  remove PendingIntent] PendingIntent{3f611f: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
05-25 13:51:10.535  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
05-25 13:51:10.535  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":2,"address":"44:78:3E:94:4A:3E"}
05-25 13:51:10.535  9936  9999 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
05-25 13:51:10.535  9936  9999 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a1e54e added. We now have 6 listener(s)
,05-25 13:51:10.535  9936  9999 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,05-25 13:51:10.535  9936  9999 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,05-25 13:51:10.535  3549  4170 V AlarmManager:  remove PendingIntent] PendingIntent{482f03b: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:10.545  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,05-25 13:51:10.545  3549  4285 V AlarmManager:  remove PendingIntent] PendingIntent{9947358: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:10.545  9936  9999 D BluetoothAdapter: STATE_ON
,05-25 13:51:10.555  3549  4931 V AlarmManager:  remove PendingIntent] PendingIntent{d6a1cb1: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:10.555  9936  9999 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
05-25 13:51:10.555  9936  9999 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-25 13:51:10.555  9936  9999 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-25 13:51:10.555  9936  9999 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-25 13:51:10.555  9936  9999 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-25 13:51:10.555  9936  9999 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-25 13:51:10.555  9936  9999 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-25 13:51:10.555  9936  9999 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-25 13:51:10.555  9936  9999 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
05-25 13:51:10.555  9936  9999 D io.jxcore.node.ConnectivityMonitor: start: OK
,05-25 13:51:10.555  3549  4433 V AlarmManager:  remove PendingIntent] PendingIntent{cd25596: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:10.555  9936  9936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:51:10.555  3549  4931 V AlarmManager:  remove PendingIntent] PendingIntent{3a65517: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:10.555  9936  9999 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:51:10.565  3549  4285 V AlarmManager:  remove PendingIntent] PendingIntent{2896d04: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:10.565  9936  9936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:51:10.565  9936  9999 D BluetoothAdapter: STATE_ON
,05-25 13:51:10.575  9936  9999 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
05-25 13:51:10.575  9936  9999 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-25 13:51:10.575  9936  9999 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-25 13:51:10.575  9936  9999 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-25 13:51:10.575  9936  9999 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-25 13:51:10.575  9936  9999 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-25 13:51:10.575  9936  9999 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-25 13:51:10.575  9936  9999 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-25 13:51:10.575  9936  9999 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,05-25 13:51:10.575  9936  9999 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
05-25 13:51:10.575  9936  9999 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
05-25 13:51:10.575  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
05-25 13:51:10.575  9936  9999 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
05-25 13:51:10.575  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
05-25 13:51:10.575  9936  9999 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d33b849 removed from the list
,05-25 13:51:10.575  9936  9999 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d33b849 removed from the list
05-25 13:51:10.575  9936  9999 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
05-25 13:51:10.575  9936  9999 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a1e54e removed from the list
,05-25 13:51:10.575  9936  9936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:51:10.575  9936  9999 D io.jxcore.node.ConnectivityMonitor: stop
05-25 13:51:10.575  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,05-25 13:51:10.575  9936  9999 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
,05-25 13:51:10.575  9936  9999 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,05-25 13:51:10.575  9936  9999 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
,05-25 13:51:10.585  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [incoming]
,05-25 13:51:10.585  9936  9999 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
,05-25 13:51:10.585  9936  9999 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,05-25 13:51:10.585  9936  9999 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
05-25 13:51:10.585  9936  9999 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,05-25 13:51:10.585  9936  9999 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
,05-25 13:51:10.585  9936  9999 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
05-25 13:51:10.585  9936  9999 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
05-25 13:51:10.585  9936  9999 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
05-25 13:51:10.585  9936  9999 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,05-25 13:51:10.585  9936  9999 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
05-25 13:51:10.585  9936  9999 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
05-25 13:51:10.585  9936  9999 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,05-25 13:51:10.585  9936  9999 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
05-25 13:51:10.585  9936  9999 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
05-25 13:51:10.585  9936  9999 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
05-25 13:51:10.585  9936  9999 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
05-25 13:51:10.585  9936  9999 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,05-25 13:51:10.585  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [00:11:22:33:44:55]
05-25 13:51:10.585  9936  9999 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
05-25 13:51:10.585  9936  9999 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,05-25 13:51:10.585  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [10:010:010:010:010:010]
05-25 13:51:10.585  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [11:110:110:110:110:110]
05-25 13:51:10.585  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [12:210:210:210:210:210]
05-25 13:51:10.585  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [13:310:310:310:310:310]
05-25 13:51:10.585  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [14:410:410:410:410:410]
05-25 13:51:10.585  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [15:510:510:510:510:510]
,05-25 13:51:10.585  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [16:610:610:610:610:610]
05-25 13:51:10.585  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [17:710:710:710:710:710]
05-25 13:51:10.585  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [18:810:810:810:810:810]
05-25 13:51:10.585  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [19:910:910:910:910:910]
,05-25 13:51:10.585  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [20:1010:1010:1010:1010:1010]
05-25 13:51:10.585  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [21:1110:1110:1110:1110:1110]
05-25 13:51:10.585  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [22:1210:1210:1210:1210:1210]
,05-25 13:51:10.585  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [23:1310:1310:1310:1310:1310]
05-25 13:51:10.585  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [24:1410:1410:1410:1410:1410]
05-25 13:51:10.585  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [25:1510:1510:1510:1510:1510]
05-25 13:51:10.585  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [26:1610:1610:1610:1610:1610]
,05-25 13:51:10.585  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [27:1710:1710:1710:1710:1710]
05-25 13:51:10.585  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [28:1810:1810:1810:1810:1810]
05-25 13:51:10.585  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [29:1910:1910:1910:1910:1910]
05-25 13:51:10.585  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [30:2010:2010:2010:2010:2010]
05-25 13:51:10.585  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [31:2110:2110:2110:2110:2110]
05-25 13:51:10.585  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [32:2210:2210:2210:2210:2210]
05-25 13:51:10.585  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [33:2310:2310:2310:2310:2310]
,05-25 13:51:10.585  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [34:2410:2410:2410:2410:2410]
05-25 13:51:10.585  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [35:2510:2510:2510:2510:2510]
05-25 13:51:10.585  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [36:2610:2610:2610:2610:2610]
05-25 13:51:10.585  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [37:2710:2710:2710:2710:2710]
05-25 13:51:10.585  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [38:2810:2810:2810:2810:2810]
05-25 13:51:10.585  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [39:2910:2910:2910:2910:2910]
05-25 13:51:10.585  9936  9999 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
05-25 13:51:10.585  9936  9999 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
05-25 13:51:10.585  9936  9999 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
05-25 13:51:10.585  9936  9999 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
05-25 13:51:10.585  9936  9999 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
05-25 13:51:10.585  9936  9999 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
05-25 13:51:10.585  9936  9999 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,05-25 13:51:10.595  9936  9999 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
05-25 13:51:10.595  9936  9999 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [00:11:22:33:44:55]
05-25 13:51:10.595  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,05-25 13:51:10.595  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port 1
,05-25 13:51:10.595  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,05-25 13:51:10.595  9936  9999 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
05-25 13:51:10.595  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
05-25 13:51:10.595  9936  9999 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
05-25 13:51:10.595  9936  9999 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
05-25 13:51:10.595  9936  9999 E io.jxcore.node.ConnectionHelper: connect: Callback is null
05-25 13:51:10.595  9936 10027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 210)
05-25 13:51:10.595  9936 10027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect: mIsShuttingDown = false
05-25 13:51:10.595  9936 10027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: createBluetoothSocket 1
05-25 13:51:10.595  9936 10027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: createBluetoothSocket: given port
,05-25 13:51:10.605  9936  9999 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
05-25 13:51:10.605  9936  9999 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,05-25 13:51:10.605  9936  9999 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
,05-25 13:51:10.605  9936  9999 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
05-25 13:51:10.605  9936 10027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: createBluetoothSocketToServiceRecord: Socket created with channel/port 1
05-25 13:51:10.605  9936 10027 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  connect: connecting
,05-25 13:51:10.605  9936  9999 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
05-25 13:51:10.605  9936  9999 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
05-25 13:51:10.605  9936  9999 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
,05-25 13:51:10.605  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
05-25 13:51:10.605  9936  9999 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
05-25 13:51:10.605  9936  9999 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
05-25 13:51:10.605  9936  9999 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
05-25 13:51:10.605  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
05-25 13:51:10.605  9936  9999 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
,05-25 13:51:10.605  9936  9999 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
05-25 13:51:10.605  9936  9999 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
05-25 13:51:10.605  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
05-25 13:51:10.605  9936  9999 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
,05-25 13:51:10.615  9936  9999 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
,05-25 13:51:10.615  9936  9999 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
05-25 13:51:10.615  9936  9999 V io.jxcore.node.ConnectivityMonitor: start: Already started
05-25 13:51:10.615  9936  9999 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
05-25 13:51:10.615  9936  9999 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
05-25 13:51:10.615  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
05-25 13:51:10.615  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"44:78:3E:94:4A:3E"}
05-25 13:51:10.615  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"44:78:3E:94:4A:3E"}
05-25 13:51:10.615  9936  9999 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:10.615  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,05-25 13:51:10.615  9936 10027 D BluetoothSocket: connect(): myUserId = 0
,05-25 13:51:10.615  9936 10027 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,05-25 13:51:10.625  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"44:78:3E:94:4A:3E"}
05-25 13:51:10.625  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"44:78:3E:94:4A:3E"}
05-25 13:51:10.625  9936  9999 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:10.625  9936  9999 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,05-25 13:51:10.625  9936  9999 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
05-25 13:51:10.625  9936  9999 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
05-25 13:51:10.625  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
05-25 13:51:10.625  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,05-25 13:51:10.625  9936  9999 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
05-25 13:51:10.625  9936  9999 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,05-25 13:51:10.625  9936  9999 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
05-25 13:51:10.625  9936  9999 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
05-25 13:51:10.625  9936  9999 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
05-25 13:51:10.625  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
05-25 13:51:10.625  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
05-25 13:51:10.625  9936  9936 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,05-25 13:51:10.625  9936 10028 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,05-25 13:51:10.635  9936 10028 D BluetoothSocket: bindListen(): myUserId = 0
,05-25 13:51:10.635  9936 10028 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,05-25 13:51:10.635  9936  9999 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,05-25 13:51:10.635  9936  9999 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
05-25 13:51:10.635  9936  9999 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,05-25 13:51:10.635  9936 10028 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
,05-25 13:51:10.635  9936 10028 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@ef69005, port: 6, type: 1, local socket address: null, socket type: 0
,05-25 13:51:10.635  3549  3986 D SecContentProvider: insert(), uri = 2
05-25 13:51:10.635  9936  9999 D BluetoothAdapter: STATE_ON
,05-25 13:51:10.645  4857  5150 W bt_btif : bta_dm_acl_change(), event : 2
,05-25 13:51:10.645  3549  3567 V AlarmManager:  remove PendingIntent] PendingIntent{4b25570: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
05-25 13:51:10.645  9936  9999 D BluetoothAdapter: STATE_ON
,05-25 13:51:10.645  9936  9999 D BluetoothAdapter: STATE_ON
,05-25 13:51:10.645  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:10.645  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,05-25 13:51:10.645  3549  4931 V AlarmManager:  remove PendingIntent] PendingIntent{a96b0e9: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
05-25 13:51:10.645  9936  9999 D BluetoothAdapter: STATE_ON
,05-25 13:51:10.645  9936  9999 D BluetoothAdapter: STATE_ON
,05-25 13:51:10.645  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
05-25 13:51:10.645  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,05-25 13:51:10.645  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 3
05-25 13:51:10.655  9936  9999 D BluetoothAdapter: STATE_ON
,05-25 13:51:10.655  3549  3567 V AlarmManager:  remove PendingIntent] PendingIntent{946816e: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:10.655  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:51:10.655  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:10.655  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
05-25 13:51:10.655  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
05-25 13:51:10.655  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "1e0175e0-0d83-4d02-aa60-d3c622da762e", Bluetooth MAC address: "44:78:3E:94:4A:3E"
05-25 13:51:10.655  9936  9999 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 44 78 3E 94 4A 3E
05-25 13:51:10.655  9936  9999 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[3, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-25 13:51:10.655  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[3, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-25 13:51:10.655  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:10.655  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[3, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:51:10.655  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
05-25 13:51:10.655  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[3, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-25 13:51:10.655  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:10.655  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
,05-25 13:51:10.655  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[3, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:10.655  9936  9999 D BluetoothAdapter: STATE_ON
,05-25 13:51:10.655  9936  9999 D BluetoothAdapter: STATE_ON
05-25 13:51:10.655  9936  9999 D BluetoothLeAdvertiser: start advertising
,05-25 13:51:10.655  9936  9999 D BluetoothAdapter: STATE_ON
,05-25 13:51:10.665  4857  5184 D BtGatt.GattService: registerClient() - UUID=fe3d6029-880e-4ad7-a0c1-a9c931585cb9
,05-25 13:51:10.705  4857  5022 D BtGatt.GattService: onClientRegistered() - UUID=fe3d6029-880e-4ad7-a0c1-a9c931585cb9, clientIf=7
,05-25 13:51:10.705  9936  9947 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,05-25 13:51:10.705  4857  4875 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,05-25 13:51:10.705  4857  4875 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,05-25 13:51:10.705  4857  4875 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
05-25 13:51:10.705  4857  5053 D BtGatt.AdvertiseManager: message : 0
,05-25 13:51:10.705  4857  5068 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
05-25 13:51:10.705  4857  5068 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 25, currDate: 25
,05-25 13:51:10.705  4857  5053 D BtGatt.AdvertiseManager: number of adv instance running = 0
05-25 13:51:10.705  4857  5053 D BtGatt.AdvertiseManager: size of list is =0
,05-25 13:51:10.715  4857  5053 D BtGatt.AdvertiseManager: starting advertising
,05-25 13:51:10.715  4857  5053 D BtGatt.AdvertiseManager: isStandardAdv = false
,05-25 13:51:10.715  3549  3986 V AlarmManager:  remove PendingIntent] PendingIntent{788d00f: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:10.715  4857  5068 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.thaliproject.thalitest : 32
05-25 13:51:10.715  4857  5022 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
05-25 13:51:10.715  4857  5068 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.thaliproject.thalitest@LowLatency : 24928551
05-25 13:51:10.715  4857  5068 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.thaliproject.thalitest@LowLatency : 2
05-25 13:51:10.715  4857  5068 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
05-25 13:51:10.715  4857  5068 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 3 => 3
,05-25 13:51:10.715  4857  5053 D BtGatt.AdvertiseManager: starting multi advertising
05-25 13:51:10.715  4857  5022 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
05-25 13:51:10.725  4857  5053 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
05-25 13:51:10.725  4857  5053 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
05-25 13:51:10.725  4857  5053 D BtGatt.AdvertiseManager: postCallback clientIf = 7 status = 0
05-25 13:51:10.725  4857  5053 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=7, status=0, isStart=true
,05-25 13:51:10.725  9936  9946 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
05-25 13:51:10.725  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:10.725  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:10.725  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
05-25 13:51:10.725  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:51:10.725  3549  3567 V AlarmManager:  remove PendingIntent] PendingIntent{f3f589c: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
05-25 13:51:10.725  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:10.725  3549  3981 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-25 13:51:10.725  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:10.725  3549  3981 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
,05-25 13:51:10.725  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:10.725  3549  3981 D BatteryService: online:4, current avg:10, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:74
05-25 13:51:10.725  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:10.725  3549  3549 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:51:10.725  9936  9999 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
05-25 13:51:10.725  3549  4367 V AlarmManager:  remove PendingIntent] PendingIntent{fa072a5: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
05-25 13:51:10.725  9936  9999 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
05-25 13:51:10.725  9936  9999 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:10.725  3549  3549 I MotionRecognitionService: Plugged
05-25 13:51:10.725  9936  9999 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: seems that updateState call different BlePeerDiscoverer
05-25 13:51:10.725  3549  3549 D MotionRecognitionService:   cableConnection= 1
05-25 13:51:10.725  9936  9999 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:10.725  3549  3549 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,05-25 13:51:10.725  9936  9999 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:10.725  3549  3549 D MotionRecognitionService: skip setTransmitPower. 
05-25 13:51:10.725  9936  9999 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:10.725  9936  9936 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
05-25 13:51:10.725  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
05-25 13:51:10.725  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
,05-25 13:51:10.725  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
05-25 13:51:10.725  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
05-25 13:51:10.725  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
05-25 13:51:10.725  9936  9936 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
05-25 13:51:10.725  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,05-25 13:51:10.725  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
05-25 13:51:10.725  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
05-25 13:51:10.725  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
05-25 13:51:10.725  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
,05-25 13:51:10.725  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
05-25 13:51:10.725  9936  9936 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
05-25 13:51:10.725  9936  9936 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
05-25 13:51:10.725  9936  9999 I io.jxcore.node.ConnectionHelper: start: OK
05-25 13:51:10.735  3549  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:51:10.735  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,05-25 13:51:10.735  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
05-25 13:51:10.735  9936  9936 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
05-25 13:51:10.735  9936  9936 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
05-25 13:51:10.735  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
05-25 13:51:10.735  9936  9936 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
05-25 13:51:10.735  9936  9936 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,05-25 13:51:10.735  9936  9936 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,05-25 13:51:10.745  4905  4905 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:51:10.745  4857  4857 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,05-25 13:51:10.745  4857  5186 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-25 13:51:10.745  4905  4905 D BatteryMonitor: new battery level: 100
,05-25 13:51:10.745  3549  4420 V AlarmManager:  remove PendingIntent] PendingIntent{add467a: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:10.755  3549  4433 V AlarmManager:  remove PendingIntent] PendingIntent{80c5e2b: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:10.755  3549  4170 V AlarmManager:  remove PendingIntent] PendingIntent{2376288: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:10.755  3549  3568 V AlarmManager:  remove PendingIntent] PendingIntent{eca9421: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:10.765  3549  4066 V AlarmManager:  remove PendingIntent] PendingIntent{7e95046: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:10.765  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:10.765  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:10.995  3549  4433 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-25 13:51:10.995  3549  4433 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:51:10.995  3549  4433 D BatteryService: online:4, current avg:14, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:134
05-25 13:51:10.995  3549  3549 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:51:10.995  3549  3549 I MotionRecognitionService: Plugged
05-25 13:51:10.995  3549  3549 D MotionRecognitionService:   cableConnection= 1
05-25 13:51:10.995  3549  3549 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:51:10.995  3549  3549 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:51:10.995  3549  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:51:11.005  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,05-25 13:51:11.005  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
05-25 13:51:11.005  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
,05-25 13:51:11.015  4905  4905 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:51:11.015  4857  4857 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,05-25 13:51:11.015  4857  5186 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-25 13:51:11.025  4905  4905 D BatteryMonitor: new battery level: 100
,05-25 13:51:11.025  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:11.025  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:11.225  9936 10010 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
05-25 13:51:11.235  9936  9999 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
05-25 13:51:11.235  9936  9999 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
05-25 13:51:11.235  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
05-25 13:51:11.235  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
05-25 13:51:11.235  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
05-25 13:51:11.235  9936  9999 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
05-25 13:51:11.235  9936  9999 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
05-25 13:51:11.235  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
05-25 13:51:11.235  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
05-25 13:51:11.235  9936 10028 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
05-25 13:51:11.235  9936 10028 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
05-25 13:51:11.235  9936 10028 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,05-25 13:51:11.235  9936  9999 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@47866d9 removed from the list
05-25 13:51:11.235  9936  9999 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@47866d9 removed from the list
05-25 13:51:11.235  9936  9999 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,05-25 13:51:11.235  9936  9999 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
05-25 13:51:11.235  9936  9999 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:11.235  9936  9999 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
05-25 13:51:11.235  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,05-25 13:51:11.235  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:11.235  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:11.235  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:51:11.235  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:11.235  9936 10034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 210
05-25 13:51:11.235  9936 10034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
,05-25 13:51:11.235  9936 10034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: closeBluetoothSocket: Trying to close the bluetooth socket... (thread ID: 210)
05-25 13:51:11.235  9936 10034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: closeBluetoothSocket: bluetooth socket closed (thread ID: 210)
05-25 13:51:11.235  4857  5279 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 8, channel: 1
05-25 13:51:11.235  9936  9936 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
05-25 13:51:11.235  9936  9936 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
05-25 13:51:11.235  9936  9936 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,05-25 13:51:11.245  9936  9999 D BluetoothAdapter: STATE_ON
,05-25 13:51:11.245  9936 10027 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  connect: read failed, socket might closed or timeout, read ret: -1
05-25 13:51:11.245  9936 10027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socket is not connected
05-25 13:51:11.245  9936 10027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 210)
,05-25 13:51:11.245  9936  9999 D BluetoothAdapter: STATE_ON
05-25 13:51:11.245  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,05-25 13:51:11.245  9936  9999 D BluetoothAdapter: STATE_ON
,05-25 13:51:11.245  9936  9999 D BluetoothAdapter: STATE_ON
,05-25 13:51:11.245  9936  9999 D BluetoothLeScanner: could not find callback wrapper
05-25 13:51:11.245  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
05-25 13:51:11.245  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:11.245  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:51:11.245  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:11.245  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
05-25 13:51:11.245  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:51:11.245  9936  9999 D BluetoothAdapter: STATE_ON
,05-25 13:51:11.255  9936  9999 D BluetoothAdapter: STATE_ON
,05-25 13:51:11.255  9936  9999 D BluetoothLeAdvertiser: stop advertising
,05-25 13:51:11.255  4857  5184 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,05-25 13:51:11.255  4857  5184 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,05-25 13:51:11.255  4857  5053 D BtGatt.AdvertiseManager: message : 1
05-25 13:51:11.255  4857  5068 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
05-25 13:51:11.255  4857  5068 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 25, currDate: 25
05-25 13:51:11.255  4857  5068 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
,05-25 13:51:11.255  4857  5068 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 3 => 3
05-25 13:51:11.255  4857  5068 D BtGatt.GattService: [GSIM LOG]: remove : com.thaliproject.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
05-25 13:51:11.255  4857  5053 D BtGatt.AdvertiseManager: stop advertise for client =  7
05-25 13:51:11.255  4857  5053 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 7
,05-25 13:51:11.255  4857  5053 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,05-25 13:51:11.255  3549  4286 V AlarmManager:  remove PendingIntent] PendingIntent{f0b207: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:11.265  4857  5022 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
05-25 13:51:11.265  4857  5022 D BtGatt.GattService: Client app is not null!
05-25 13:51:11.265  9936  9947 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
05-25 13:51:11.265  4857  4875 D BtGatt.GattService: unregisterClient() - clientIf=7
,05-25 13:51:11.265  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
05-25 13:51:11.265  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:11.265  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
05-25 13:51:11.265  3549  4430 V AlarmManager:  remove PendingIntent] PendingIntent{5241f34: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:11.265  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:11.265  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:11.265  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:11.265  9936  9999 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,05-25 13:51:11.265  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,05-25 13:51:11.265  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
05-25 13:51:11.265  9936  9999 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:51:11.265  9936  9999 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:11.265  9936  9999 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
05-25 13:51:11.265  9936  9999 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:11.265  9936  9999 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:11.265  9936  9999 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b70189e removed from the list
05-25 13:51:11.265  9936  9936 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
05-25 13:51:11.265  9936  9999 D io.jxcore.node.ConnectivityMonitor: stop
05-25 13:51:11.265  9936  9936 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,05-25 13:51:11.265  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
05-25 13:51:11.265  9936  9936 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
05-25 13:51:11.265  9936  9936 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
05-25 13:51:11.275  3549  4931 V AlarmManager:  remove PendingIntent] PendingIntent{81b515d: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
05-25 13:51:11.265  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,05-25 13:51:11.265  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,05-25 13:51:11.265  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
05-25 13:51:11.265  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
05-25 13:51:11.265  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,05-25 13:51:11.265  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
05-25 13:51:11.265  9936  9936 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,05-25 13:51:11.275  3549  4367 V AlarmManager:  remove PendingIntent] PendingIntent{15a2ad2: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:11.275  3549  3986 V AlarmManager:  remove PendingIntent] PendingIntent{cdc67a3: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
05-25 13:51:11.285  3549  4430 V AlarmManager:  remove PendingIntent] PendingIntent{c7dfaa0: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:11.285  3549  3567 V AlarmManager:  remove PendingIntent] PendingIntent{bc0a659: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:11.295  3549  3838 V AlarmManager:  remove PendingIntent] PendingIntent{58c221e: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:11.775  9936  9936 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,05-25 13:51:14.825  3549  6068 D SSRM:n  : SIOP:: AP = 330, PST = 328 (W:14), CP = 280, CUR = 14, LCD = 40
,05-25 13:51:16.275  9936 10015 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
,05-25 13:51:16.275  9936  9999 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,05-25 13:51:16.275  9936  9999 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,05-25 13:51:16.275  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,05-25 13:51:16.275  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,05-25 13:51:16.285  9936  9999 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,05-25 13:51:16.285  9936  9999 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
05-25 13:51:16.285  9936  9999 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,05-25 13:51:16.285  9936  9999 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
05-25 13:51:16.285  9936  9999 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,05-25 13:51:16.285  9936 10035 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
05-25 13:51:16.285  9936  9936 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
05-25 13:51:16.285  9936  9999 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
,05-25 13:51:16.285  9936 10035 D BluetoothSocket: bindListen(): myUserId = 0
05-25 13:51:16.285  9936 10035 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
05-25 13:51:16.285  9936  9999 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [00:11:22:33:44:55], error message: ErrorMessage
05-25 13:51:16.285  9936  9999 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
05-25 13:51:16.285  9936  9999 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,05-25 13:51:16.285  9936  9999 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
05-25 13:51:16.295  9936  9999 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
,05-25 13:51:16.295  9936 10035 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
,05-25 13:51:16.295  9936 10035 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@f8ca768, port: 6, type: 1, local socket address: null, socket type: 0
,05-25 13:51:16.305  9936  9999 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
05-25 13:51:16.305  9936  9999 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,05-25 13:51:16.305  9936  9999 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
05-25 13:51:16.305  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,05-25 13:51:16.305  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
05-25 13:51:16.305  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
05-25 13:51:16.305  9936  9999 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
05-25 13:51:16.305  9936  9999 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,05-25 13:51:16.305  9936  9999 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@47866d9 not in the list
05-25 13:51:16.305  9936  9936 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
05-25 13:51:16.305  9936  9999 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@47866d9 not in the list
05-25 13:51:16.305  9936  9999 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
05-25 13:51:16.305  9936  9999 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,05-25 13:51:16.305  9936 10035 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
05-25 13:51:16.305  9936 10035 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
05-25 13:51:16.305  9936 10035 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
05-25 13:51:16.305  9936  9999 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:16.305  9936  9999 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
05-25 13:51:16.305  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,05-25 13:51:16.305  9936  9999 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
05-25 13:51:16.305  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
05-25 13:51:16.305  9936  9936 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
05-25 13:51:16.305  9936  9936 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,05-25 13:51:16.305  9936  9999 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:51:16.305  9936  9999 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-138,7,main], id: 138
,05-25 13:51:16.305  9936  9999 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
05-25 13:51:16.305  9936  9999 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:16.305  9936  9999 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-138,7,main], id: 138
05-25 13:51:16.305  9936  9999 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b70189e not in the list
05-25 13:51:16.305  9936  9936 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
05-25 13:51:16.305  9936  9999 D io.jxcore.node.ConnectivityMonitor: stop
,05-25 13:51:16.305  9936  9999 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
05-25 13:51:16.305  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
05-25 13:51:16.305  9936  9936 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
05-25 13:51:16.305  9936  9936 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
05-25 13:51:16.315  9936  9999 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
,05-25 13:51:16.315  9936  9999 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
05-25 13:51:16.315  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
05-25 13:51:16.315  9936  9999 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
05-25 13:51:16.315  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
05-25 13:51:16.315  9936  9999 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
05-25 13:51:16.315  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,05-25 13:51:16.315  9936  9999 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
05-25 13:51:16.315  9936  9999 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
05-25 13:51:16.315  9936  9999 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
05-25 13:51:16.315  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [incoming]
05-25 13:51:16.315  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [outgoing]
,05-25 13:51:16.315  9936  9999 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
05-25 13:51:16.315  9936  9999 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
05-25 13:51:16.315  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,05-25 13:51:16.315  9936  9999 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
05-25 13:51:16.315  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
05-25 13:51:16.315  9936  9999 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
05-25 13:51:16.315  9936  9999 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,05-25 13:51:16.315  9936  9999 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
05-25 13:51:16.315  9936  9999 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
05-25 13:51:16.315  9936  9999 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,05-25 13:51:16.325  9936  9999 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
,05-25 13:51:16.325  9936  9999 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
05-25 13:51:16.325  9936  9999 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
05-25 13:51:16.325  9936  9999 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
05-25 13:51:16.325  9936  9999 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,05-25 13:51:16.325  9936  9999 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
,05-25 13:51:16.325  9936  9999 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
05-25 13:51:16.325  9936  9999 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c552781 added. We now have 2 listener(s)
05-25 13:51:16.325  9936  9999 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c552781 added. We now have 3 listener(s)
,05-25 13:51:16.325  9936  9999 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,05-25 13:51:16.325  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"44:78:3E:94:4A:3E"}
,05-25 13:51:16.325  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
05-25 13:51:16.325  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"44:78:3E:94:4A:3E"}
05-25 13:51:16.325  9936  9999 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,05-25 13:51:16.325  9936  9999 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1115026 added. We now have 4 listener(s)
05-25 13:51:16.325  9936  9999 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
05-25 13:51:16.325  9936  9999 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,05-25 13:51:16.335  9936  9999 D BluetoothAdapter: enable()
,05-25 13:51:16.335  9936  9999 D BluetoothAdapter: enable(): BT is already enabled..!
,05-25 13:51:16.345  3549  3603 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{43daff u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{44442de 4889:com.samsung.android.providers.context/u0a7}
,05-25 13:51:16.345  9936  9999 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,05-25 13:51:16.345  3549  4420 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,05-25 13:51:16.345  3549  4420 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,05-25 13:51:16.355  3549  4420 D WifiService: setWifiEnabled: true pid=9936, uid=10074
,05-25 13:51:16.355  3549  4420 W ActivityManager: Permission Denial: getCurrentUser() from pid=9936, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
,05-25 13:51:16.355  3549  4420 W WifiService: Failed getting userId using ActivityManagerNative
05-25 13:51:16.355  3549  4420 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9936, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
05-25 13:51:16.355  3549  4420 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-25 13:51:16.355  3549  4420 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
05-25 13:51:16.355  3549  4420 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
05-25 13:51:16.355  3549  4420 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
05-25 13:51:16.355  3549  4420 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
,05-25 13:51:16.355  3549  4420 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
,05-25 13:51:16.355  3549  4420 D SettingsProvider: isChangeAllowed() : name = wifi_on
05-25 13:51:16.355  3549  3859 D WifiBigDataLog: getJsonFormat() - feature : ONOF
05-25 13:51:16.355  3549  3859 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
05-25 13:51:16.355  9936  9999 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
05-25 13:51:16.355  3549  3863 D WifiController: [FCC]setFccChannel() is called !!!
,05-25 13:51:16.355  3549  3863 D WifiStateMachine: setFccChannel: channel = 0
05-25 13:51:16.355  3549  3863 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
05-25 13:51:16.355  3549  3859 D WifiBigDataLog: init : 
05-25 13:51:16.365  9936  9999 D BluetoothAdapter: STATE_ON
,05-25 13:51:16.365  9936  9999 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
05-25 13:51:16.365  3549  3859 D WifiStateMachine: setFccChannelNative: channel = 0
05-25 13:51:16.365  3549  3859 D WifiNative-wlan0: callSECApiInt - ID [230]
05-25 13:51:16.365  9936  9999 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
,05-25 13:51:16.365  9936  9999 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
05-25 13:51:16.365  3549  3603 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9d820cc u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{44442de 4889:com.samsung.android.providers.context/u0a7}
,05-25 13:51:16.385  9936 10036 D BluetoothAdapter: disable()
,05-25 13:51:16.385  9936  9999 D BluetoothAdapter: STATE_ON
,05-25 13:51:16.385  9936  9999 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-25 13:51:16.385  9936  9999 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-25 13:51:16.385  9936  9999 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-25 13:51:16.385  9936  9999 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-25 13:51:16.385  9936  9999 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-25 13:51:16.385  9936  9999 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-25 13:51:16.385  9936  9999 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-25 13:51:16.385  9936  9999 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-25 13:51:16.385  9936  9999 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,05-25 13:51:16.395  3549  3603 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4cc4f15 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{44442de 4889:com.samsung.android.providers.context/u0a7}
,05-25 13:51:16.395  3549  3981 D SettingsProvider: isChangeAllowed() : name = bluetooth_on
,05-25 13:51:16.405  3549  3619 D SecContentProvider: insert(), uri = 2
,05-25 13:51:16.405  4857  5016 D BluetoothAdapterState: Current state: ON, message: BLE_TURN_OFF
,05-25 13:51:16.415  4857  5016 D BluetoothAdapterProperties: Setting state to 13
05-25 13:51:16.415  4857  5016 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
05-25 13:51:16.415  4857  5016 D BluetoothAdapterService: Bluetooth PBAP supproted is true
05-25 13:51:16.415  4857  5016 D BluetoothAdapterService: updateAdapterState state is 13
,05-25 13:51:16.415  4857  4857 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,05-25 13:51:16.415  3549  3619 D BluetoothManagerService: Turning On/Off, G state: 3, S state: 3, mBLE count: 0, s BLE count: 0
05-25 13:51:16.415  4857  5016 D BluetoothAdapterService: Autoconnection is available 
05-25 13:51:16.415  4857  5016 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
05-25 13:51:16.415  4857  5016 D BluetoothAdapterService: terminating service from this receiver
,05-25 13:51:16.415  3549  3549 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
05-25 13:51:16.415  3549  3549 I InputMethodManagerService: [BT Setting State] State =13
,05-25 13:51:16.425  3949  4133 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
05-25 13:51:16.425  3949  4133 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,05-25 13:51:16.425  4316  4316 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
,05-25 13:51:16.425  4782  4782 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,05-25 13:51:16.425  3549  3549 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
05-25 13:51:16.425  3549  3549 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
05-25 13:51:16.425  3549  3549 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,05-25 13:51:16.435  9936  9936 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,05-25 13:51:16.435  9936  9936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-25 13:51:16.435  9936  9936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-25 13:51:16.435  9936  9936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-25 13:51:16.435  9936  9936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-25 13:51:16.435  9936  9936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
05-25 13:51:16.435  9936  9936 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-25 13:51:16.435  9936  9936 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-25 13:51:16.435  9936  9936 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-25 13:51:16.435  9936  9936 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,05-25 13:51:16.435  9936  9936 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
05-25 13:51:16.435  9936  9936 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,05-25 13:51:16.445  3549  3603 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{885281b u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{244f13b 9180:com.android.settings/1000}
,05-25 13:51:16.445  3949  3949 D BluetoothPbap: Proxy object disconnected
05-25 13:51:16.445  3949  3949 D PbapServerProfile: Bluetooth service disconnected
05-25 13:51:16.445  4857  5016 D BluetoothAdapterProperties: onBluetoothDisable()
,05-25 13:51:16.445  4857  4857 D BleAudioService: onReceive:: INTENT mAobleStateChangeListener got : android.bluetooth.adapter.action.STATE_CHANGED
05-25 13:51:16.445  4857  4857 D BleAudioService: BluetoothAdapter.ACTION_STATE_CHANGED,  state is13
,05-25 13:51:16.445  4857  5016 W bt_btif : btif_dm_cancel_discovery
,05-25 13:51:16.455  3549  4931 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
,05-25 13:51:16.455  3549  3981 D SecContentProvider: insert(), uri = 2
,05-25 13:51:16.455  4857  5016 I BluetoothAdapterState: Entering PendingCommandState
,05-25 13:51:16.455  3549  4286 V AlarmManager:  remove PendingIntent] PendingIntent{2cc7db8: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
05-25 13:51:16.455  9180  9180 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,05-25 13:51:16.465  4857  5022 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
05-25 13:51:16.465  4857  5022 D BluetoothAdapterProperties: Scan Mode:20
,05-25 13:51:16.475  4857  5016 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BEGIN_DISABLE
,05-25 13:51:16.475  3549  3981 V AlarmManager:  remove PendingIntent] PendingIntent{bcc56f6: PendingIntentRecord{c42af7 com.android.bluetooth broadcastIntent}}
,05-25 13:51:16.475  4857  5016 E BluetoothServiceJni: disableBrEdrNative:
05-25 13:51:16.475  4857  5016 E bt_bluedroid: disable_bredr
,05-25 13:51:16.475  4857  5419 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
05-25 13:51:16.475  4857  5019 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
05-25 13:51:16.475  4857  5019 E bt_btif : BTA got event 0x1a03
05-25 13:51:16.475  4857  5468 V ObexServerSockets: Accept exception: (expected at shutdown)java.io.IOException: read failed, socket might closed or timeout, read ret: -1
05-25 13:51:16.475  4857  5150 W bt_btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
05-25 13:51:16.475  4857  5468 D ObexServerSockets: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
05-25 13:51:16.475  4857  5150 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,05-25 13:51:16.485  4857  5469 V ObexServerSockets: Accept exception: (expected at shutdown)java.io.IOException: read failed, socket might closed or timeout, read ret: -1
05-25 13:51:16.485  4857  5469 D ObexServerSockets: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,05-25 13:51:16.485  9936  9936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
05-25 13:51:16.485  9180  9180 D LocalBluetoothManager: LocalBluetoothManager :: sInstance == null
05-25 13:51:16.485  4857  5019 D IOP_DB_BT: db_close: nbr users 0
05-25 13:51:16.485  4857  5019 D IOP_DB_BT: db_close: free database
,05-25 13:51:16.495  3549  3981 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,05-25 13:51:16.505  3549  4432 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{885281b u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{44442de 4889:com.samsung.android.providers.context/u0a7}
,05-25 13:51:16.505  9180  9180 D LocalBluetoothManager: LocalBluetoothManager :: constructor
,05-25 13:51:16.505  9180  9180 D BluetoothEventManager: BluetoothEventManager Constructor :: 
,05-25 13:51:16.515  3549  3567 V AlarmManager:  remove PendingIntent] PendingIntent{8867f93: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:16.515  3949  4213 D BluetoothTile: handleUpdateState :  supported = true, enabled = false, enabling = false, connected = false, connecting = false, mController.getLastDeviceName() = null
,05-25 13:51:16.525  4287  4287 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
,05-25 13:51:16.525  3549  4170 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{885281b u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f3ae3d9 4287:com.google.android.gms.persistent/u0a19}
05-25 13:51:16.525  3949  3949 D QSTileView: handleLabelStateChanged() label = Bluetooth cellWidth 272
,05-25 13:51:16.525  4857  5150 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x2  CID 0x40
05-25 13:51:16.525  4857  5150 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 8
05-25 13:51:16.525  4857  5150 W bt_btif : bta_dm_acl_change(), event : 2
05-25 13:51:16.525  4857  5150 W bt_btif : bta_dm_acl_change(), event : 5
,05-25 13:51:16.535  4857  4857 D ObexServerSockets: shutdown(block = true)
05-25 13:51:16.535  4857  4857 D ObexServerSockets: shutdown called from another thread - interrupt().
05-25 13:51:16.535  4857  4857 D ObexServerSockets: shutdown called from another thread - interrupt().
05-25 13:51:16.535  4857  4857 D BluetoothSdpJni: sdpRemoveSdpRecordNative:
05-25 13:51:16.535  4857  4857 D BluetoothSdpJni: SDP Remove record success - handle: 1
05-25 13:51:16.535  4857  4857 D BluetoothSdpJni: sdpRemoveSdpRecordNative:
,05-25 13:51:16.535  4857  4857 D BluetoothSdpJni: SDP Remove record success - handle: 0
05-25 13:51:16.535  4857  4857 I BtOppRfcommListener: stopping Accept Thread
05-25 13:51:16.535  4857  5419 I BtOppRfcommListener: BluetoothSocket listen thread finished
,05-25 13:51:16.535  9180  9180 D LocalBluetoothProfileManager: PANU : true
,05-25 13:51:16.545  3549  4170 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{885281b u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a2429dc 8769:com.sec.android.app.shealth:remote/u0a36}
,05-25 13:51:16.555  4857  5150 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-25 13:51:16.555  4857  5150 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-25 13:51:16.555  4857  5150 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-25 13:51:16.555  4857  5150 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-25 13:51:16.555  4857  5150 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-25 13:51:16.555  4857  5150 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-25 13:51:16.555  4857  5150 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-25 13:51:16.555  4857  5150 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-25 13:51:16.555  4857  5150 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-25 13:51:16.555  4857  5150 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-25 13:51:16.555  4857  5150 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-25 13:51:16.555  4857  5150 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-25 13:51:16.555  4857  5150 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-25 13:51:16.555  4857  5150 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-25 13:51:16.555  4857  5150 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,05-25 13:51:16.555  3549  4066 V AlarmManager:  remove PendingIntent] PendingIntent{f1989da: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:16.565  4857  5016 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa689ba
,05-25 13:51:16.565  4857  5022 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:11:22:33:44:55, value is empty for type: 1
,05-25 13:51:16.565  3549  4170 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{885281b u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{244f13b 9180:com.android.settings/1000}
,05-25 13:51:16.575  4857  4857 V BluetoothOppManager: cleanUp...
,05-25 13:51:16.575  3949  4133 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CLASS_CHANGED
,05-25 13:51:16.575  4857  5022 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
05-25 13:51:16.575  4857  5022 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:11:22:33:44:55, value is empty for type: 241
,05-25 13:51:16.575  9180  9180 D BluetoothSap: Create BluetoothSap proxy object
,05-25 13:51:16.585  9180  9180 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
05-25 13:51:16.585  9180  9180 D LocalBluetoothManager: LocalBluetoothManager :: onInitCallback != null
,05-25 13:51:16.585  3549  4286 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-25 13:51:16.585  3549  4286 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4318, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:51:16.585  3549  4286 D BatteryService: online:4, current avg:60, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-61
05-25 13:51:16.585  3549  3549 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:51:16.585  3549  3549 I MotionRecognitionService: Plugged
05-25 13:51:16.585  3549  3549 D MotionRecognitionService:   cableConnection= 1
05-25 13:51:16.585  3549  3549 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:51:16.585  3549  3549 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:51:16.595  3549  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:51:16.595  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
05-25 13:51:16.595  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
,05-25 13:51:16.595  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:51:16.595  4905  4905 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:51:16.605  4857  4857 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,05-25 13:51:16.605  4857  5186 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-25 13:51:16.605  4905  4905 D BatteryMonitor: new battery level: 100
,05-25 13:51:16.615  9180  9180 D DockEventReceiver: finishStartingService: stopping service
05-25 13:51:16.615  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
05-25 13:51:16.615  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:16.615  9180  9180 D BluetoothPan: BluetoothPAN Proxy object connected
,05-25 13:51:16.615  9180  9180 D PanProfile: Bluetooth service connected
,05-25 13:51:16.615  9180  9180 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
05-25 13:51:16.615  9180  9180 D BluetoothStatusReceiver: AdapterStateChanged :: state = 13
,05-25 13:51:16.615  9180  9180 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CLASS_CHANGED
,05-25 13:51:16.625  9180  9180 D BluetoothSap: Proxy object connected
,05-25 13:51:16.625  9180  9180 D SapProfile: Bluetooth service connected
,05-25 13:51:16.625  3549  4170 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{885281b u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d7577e4 4857:com.android.bluetooth/1002}
,05-25 13:51:16.645  3549  4170 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{885281b u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a53ad79 7081:com.google.android.apps.maps/u0a119}
,05-25 13:51:16.675  4857  5022 E BluetoothAdapterState: stateChangeCallback : 16
05-25 13:51:16.675  4857  5016 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_NATIVE_STOPED
05-25 13:51:16.675  3549  3981 V AlarmManager:  remove PendingIntent] PendingIntent{a00c23d: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:16.675  4857  5016 D BtConfig.SecureMode: isSecureModeOn:false
05-25 13:51:16.675  4857  5016 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,05-25 13:51:16.685  4857  5016 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
05-25 13:51:16.685  4857  4857 D HeadsetService: Received stop request...Stopping profile...
05-25 13:51:16.685  4857  5016 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,05-25 13:51:16.685  4857  4857 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Message sending
,05-25 13:51:16.685  4857  4857 E HeadsetService: notifyProfileServiceStateChanged
,05-25 13:51:16.695  3949  3949 D HeadsetProfile: Bluetooth service disconnected
,05-25 13:51:16.695  3549  3549 D BluetoothHeadset: unRegisterMessageListener : 11
,05-25 13:51:16.695  3549  3549 W BluetoothHeadset: Proxy not attached to service
05-25 13:51:16.695  3549  3549 I Telecom : BluetoothManager : unregister MessageListener
05-25 13:51:16.695  3549  3549 I Telecom : CallAudioManager: onBluetoothStateChange: no focus
,05-25 13:51:16.705  4857  5016 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,05-25 13:51:16.705  4857  4857 D A2dpService: Received stop request...Stopping profile...
,05-25 13:51:16.705  4857  5016 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
05-25 13:51:16.705  4857  5255 D A2dpStateMachine: Exit Disconnected: -1
05-25 13:51:16.705  4857  4857 D Avrcp   : unregisterContentObserver
,05-25 13:51:16.705  4857  4857 D Avrcp   : removeOnActiveSessionsChangedListener
,05-25 13:51:16.705  4857  4857 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Message sending
,05-25 13:51:16.705  4857  4857 E A2dpService: notifyProfileServiceStateChanged
05-25 13:51:16.705  4857  5016 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
05-25 13:51:16.715  3549  3549 D BluetoothA2dp: Proxy object disconnected
,05-25 13:51:16.715  3949  3949 D BluetoothA2dp: Proxy object disconnected
05-25 13:51:16.715  3949  3949 D A2dpProfile: Bluetooth service disconnected
05-25 13:51:16.715  4889  4889 D BluetoothA2dp: Proxy object disconnected
05-25 13:51:16.715  4857  4857 E BluetoothAdapterService: handleMessage() - Message: 1
05-25 13:51:16.715  4857  4857 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Before synchronized
,05-25 13:51:16.715  4857  4857 V BluetoothAdapterState: isTurningOff()=true
05-25 13:51:16.715  4857  4857 V BluetoothAdapterState: isTurningOn()=false
05-25 13:51:16.715  4857  4857 V BluetoothAdapterState: isBleTurningOn()=false
05-25 13:51:16.715  4857  4857 V BluetoothAdapterState: isBleTurningOff()=false
05-25 13:51:16.715  4857  5016 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
,05-25 13:51:16.715  4857  5016 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
05-25 13:51:16.715  4857  5016 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
05-25 13:51:16.715  4857  5016 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
05-25 13:51:16.715  4857  5016 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
05-25 13:51:16.715  4857  5016 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.bleaudio.BleAudioService
,05-25 13:51:16.725  4857  4857 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
05-25 13:51:16.725  4857  4857 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
05-25 13:51:16.725  4857  4857 D HeadsetProvider: cleanup
05-25 13:51:16.725  4857  4857 I HeadsetProvider: clearAllHeadsetSettings(0)
,05-25 13:51:16.745  4857  4857 D HidService: Received stop request...Stopping profile...
05-25 13:51:16.745  4857  4857 D HidService: Stopping Bluetooth HidService
05-25 13:51:16.745  4857  4857 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
05-25 13:51:16.745  4857  4857 W bt_btif : cleanup: HH disabling or disabled already, status = 0
05-25 13:51:16.745  4857  4857 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
05-25 13:51:16.745  4857  4857 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, Message sending
05-25 13:51:16.745  4857  4857 E HidService: notifyProfileServiceStateChanged
,05-25 13:51:16.745  3949  3949 D BluetoothInputDevice: Proxy object disconnected
,05-25 13:51:16.745  3949  3949 D HidProfile: Bluetooth service disconnected
,05-25 13:51:16.745  4857  4857 D HealthService: Received stop request...Stopping profile...
,05-25 13:51:16.755  4857  4857 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, Message sending
05-25 13:51:16.755  4857  4857 E HealthService: notifyProfileServiceStateChanged
,05-25 13:51:16.755  4857  4857 D PanService: Received stop request...Stopping profile...
05-25 13:51:16.755  4857  4857 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, Message sending
05-25 13:51:16.755  4857  4857 E PanService: notifyProfileServiceStateChanged
05-25 13:51:16.755  3549  3549 D BluetoothPan: BluetoothPAN Proxy object disconnected
,05-25 13:51:16.755  3949  3949 D BluetoothPan: BluetoothPAN Proxy object disconnected
05-25 13:51:16.755  3949  3949 D PanProfile: Bluetooth service disconnected
05-25 13:51:16.755  9180  9180 D BluetoothPan: BluetoothPAN Proxy object disconnected
05-25 13:51:16.755  9180  9180 D PanProfile: Bluetooth service disconnected
,05-25 13:51:16.755  4857  4857 E BluetoothAdapterService: handleMessage() - Message: 1
05-25 13:51:16.755  4857  4857 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Before synchronized
,05-25 13:51:16.755  4857  4857 V BluetoothAdapterState: isTurningOff()=true
05-25 13:51:16.755  4857  4857 V BluetoothAdapterState: isTurningOn()=false
,05-25 13:51:16.755  4857  4857 V BluetoothAdapterState: isBleTurningOn()=false
,05-25 13:51:16.755  4857  4857 V BluetoothAdapterState: isBleTurningOff()=false
,05-25 13:51:16.755  4857  4857 D BluetoothMapService: Received stop request...Stopping profile...
,05-25 13:51:16.765  4857  4857 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Message sending
,05-25 13:51:16.765  4857  4857 E BluetoothMapService: notifyProfileServiceStateChanged
05-25 13:51:16.765  3949  3949 D BluetoothMap: Proxy object disconnected
,05-25 13:51:16.765  3949  3949 D MapProfile: Bluetooth service disconnected
05-25 13:51:16.765  4857  4857 D SapService: Received stop request...Stopping profile...
05-25 13:51:16.765  4857  4857 V SapService: stop()
,05-25 13:51:16.765  4857  4857 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=10, Message sending
,05-25 13:51:16.765  4857  4857 E SapService: notifyProfileServiceStateChanged
,05-25 13:51:16.765  3949  3949 D BluetoothSap: Proxy object disconnected
05-25 13:51:16.765  3949  3949 D SapProfile: Bluetooth service disconnected
05-25 13:51:16.775  4857  4857 D BleAudioService: Received stop request...Stopping profile...
,05-25 13:51:16.775  9180  9180 D BluetoothSap: Proxy object disconnected
05-25 13:51:16.775  9180  9180 D SapProfile: Bluetooth service disconnected
05-25 13:51:16.775  4857  4857 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.broadcom.bt.service.bleaudio.BleAudioService, state=10, Message sending
05-25 13:51:16.775  4857  4857 E BleAudioService: notifyProfileServiceStateChanged
05-25 13:51:16.775  4857  5263 E BleAudioStateMachine_L: Exit Disconnected: -1
05-25 13:51:16.775  4857  5264 E BleAudioStateMachine_R: Exit Disconnected: -1
,05-25 13:51:16.775  3949  3949 D BluetoothLeAudio: Proxy object disconnected
05-25 13:51:16.775  3949  3949 D BleAudioProfile: Bluetooth service disconnected
,05-25 13:51:16.775  4857  4857 E BluetoothAdapterService: handleMessage() - Message: 1
,05-25 13:51:16.775  4857  4857 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, Before synchronized
,05-25 13:51:16.775  4857  4857 V BluetoothAdapterState: isTurningOff()=true
,05-25 13:51:16.775  4857  4857 V BluetoothAdapterState: isTurningOn()=false
05-25 13:51:16.775  4857  4857 V BluetoothAdapterState: isBleTurningOn()=false
05-25 13:51:16.775  4857  4857 V BluetoothAdapterState: isBleTurningOff()=false
,05-25 13:51:16.775  4857  4857 D BluetoothAdapterService: HID Host service will be diabled
05-25 13:51:16.785  4857  4857 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,05-25 13:51:16.785  4857  4857 E BluetoothAdapterService: handleMessage() - Message: 1
05-25 13:51:16.785  4857  4857 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, Before synchronized
,05-25 13:51:16.785  4857  4857 V BluetoothAdapterState: isTurningOff()=true
05-25 13:51:16.785  4857  4857 V BluetoothAdapterState: isTurningOn()=false
05-25 13:51:16.785  4857  4857 V BluetoothAdapterState: isBleTurningOn()=false
05-25 13:51:16.785  4857  4857 V BluetoothAdapterState: isBleTurningOff()=false
05-25 13:51:16.785  4857  4857 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,05-25 13:51:16.785  4857  4857 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,05-25 13:51:16.785  4857  4857 E BluetoothAdapterService: handleMessage() - Message: 1
05-25 13:51:16.785  4857  4857 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, Before synchronized
05-25 13:51:16.785  4857  4857 V BluetoothAdapterState: isTurningOff()=true
05-25 13:51:16.785  4857  4857 V BluetoothAdapterState: isTurningOn()=false
05-25 13:51:16.785  4857  4857 V BluetoothAdapterState: isBleTurningOn()=false
05-25 13:51:16.785  4857  4857 V BluetoothAdapterState: isBleTurningOff()=false
05-25 13:51:16.785  4857  4857 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
05-25 13:51:16.785  4857  4857 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,05-25 13:51:16.785  4857  4857 E BluetoothAdapterService: handleMessage() - Message: 1
05-25 13:51:16.785  4857  4857 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Before synchronized
,05-25 13:51:16.785  4857  4857 V BluetoothAdapterState: isTurningOff()=true
05-25 13:51:16.785  4857  4857 V BluetoothAdapterState: isTurningOn()=false
05-25 13:51:16.785  4857  4857 V BluetoothAdapterState: isBleTurningOn()=false
,05-25 13:51:16.785  4857  4857 V BluetoothAdapterState: isBleTurningOff()=false
,05-25 13:51:16.785  4857  4857 E BluetoothAdapterService: handleMessage() - Message: 1
05-25 13:51:16.785  4857  4857 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=10, Before synchronized
,05-25 13:51:16.795  4857  4857 V BluetoothAdapterState: isTurningOff()=true
,05-25 13:51:16.795  4857  4857 V BluetoothAdapterState: isTurningOn()=false
05-25 13:51:16.795  4857  4857 V BluetoothAdapterState: isBleTurningOn()=false
05-25 13:51:16.795  4857  4857 V BluetoothAdapterState: isBleTurningOff()=false
,05-25 13:51:16.795  4857  4857 E BluetoothAdapterService: handleMessage() - Message: 1
05-25 13:51:16.795  4857  4857 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.bleaudio.BleAudioService, state=10, Before synchronized
,05-25 13:51:16.795  4857  4857 V BluetoothAdapterState: isTurningOff()=true
05-25 13:51:16.795  4857  4857 V BluetoothAdapterState: isTurningOn()=false
05-25 13:51:16.795  4857  4857 V BluetoothAdapterState: isBleTurningOn()=false
05-25 13:51:16.795  4857  4857 V BluetoothAdapterState: isBleTurningOff()=false
05-25 13:51:16.795  4857  5016 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_STOPPED
05-25 13:51:16.795  4857  4857 V BleAudioService: [unregisterCallStateListener]
,05-25 13:51:16.795  4857  4857 W BtBleAudio.JNI: WARNING: cleanupNative(L385): Cleaning up  Ble audio left callback object##
05-25 13:51:16.795  4857  4857 W BtBleAudio.JNI: WARNING: cleanupNative(L403): Cleaning up Ble audio Interface...##
,05-25 13:51:16.795  4857  4857 W BtBleAudio.JNI: WARNING: cleanupNative(L391): Cleaning up  Ble audio right callback object##
05-25 13:51:16.795  4857  5016 D BluetoothAdapterProperties: Setting state to 15
05-25 13:51:16.795  4857  5016 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
05-25 13:51:16.795  4857  4857 V BleAudioService: [unregisterAobleStateChangeListener] Unregistering mAobleStateChangeListener
,05-25 13:51:16.795  4857  5016 D BluetoothAdapterService: Bluetooth PBAP supproted is true
05-25 13:51:16.795  4857  5016 D BluetoothAdapterService: updateAdapterState state is 15
05-25 13:51:16.805  4857  5016 D BluetoothAdapterService: Autoconnection is available 
05-25 13:51:16.805  4857  5016 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 15
05-25 13:51:16.805  4857  5016 I BluetoothAdapterState: Entering BleOnState
05-25 13:51:16.805  4260  4621 D BluetoothAdapter: onBluetoothStateChange: up=false
05-25 13:51:16.805  4260  4621 D BluetoothAdapter: Bluetooth is turned off, stop adv
,05-25 13:51:16.805  4260  4621 D BluetoothAdapter: There are no active google scan apps, stop scan
,05-25 13:51:16.805  3949  3961 D BluetoothInputDevice: onBluetoothStateChange: up=false
,05-25 13:51:16.805  3949  4123 D BluetoothAdapter: onBluetoothStateChange: up=false
,05-25 13:51:16.805  3949  4123 D BluetoothAdapter: Bluetooth is turned off, stop adv
,05-25 13:51:16.805  3949  4123 D BluetoothAdapter: There are no active google scan apps, stop scan
,05-25 13:51:16.805  8769  8781 D BluetoothAdapter: onBluetoothStateChange: up=false
,05-25 13:51:16.805  8769  8781 D BluetoothAdapter: Bluetooth is turned off, stop adv
05-25 13:51:16.805  8769  8781 D BluetoothAdapter: There are no active google scan apps, stop scan
,05-25 13:51:16.805  3949  5555 D BluetoothPbap: onBluetoothStateChange: up=false
,05-25 13:51:16.805  9936  9936 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,05-25 13:51:16.805  9180  9191 D BluetoothAdapter: onBluetoothStateChange: up=false
05-25 13:51:16.815  9180  9191 D BluetoothAdapter: Bluetooth is turned off, stop adv
,05-25 13:51:16.815  9180  9191 D BluetoothAdapter: There are no active google scan apps, stop scan
,05-25 13:51:16.815  3949  4541 D BluetoothA2dp: onBluetoothStateChange: up=false
,05-25 13:51:16.815  3949  3969 D BluetoothLeAudio: onBluetoothStateChange: up=false
,05-25 13:51:16.815  3949  3969 D BluetoothLeAudio: Unbinding service...
05-25 13:51:16.815  9180  9192 D BluetoothPan: onBluetoothStateChange on: false
,05-25 13:51:16.815  4889  4907 D BluetoothA2dp: onBluetoothStateChange: up=false
,05-25 13:51:16.815  9180  9191 D BluetoothSap: onBluetoothStateChange: up=false
,05-25 13:51:16.815  4287  4297 D BluetoothAdapter: onBluetoothStateChange: up=false
,05-25 13:51:16.815  4287  4297 D BluetoothAdapter: Bluetooth is turned off, stop adv
,05-25 13:51:16.815  4287  4297 D BluetoothAdapter: There are no active google scan apps, stop scan
,05-25 13:51:16.815  4287  4297 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
05-25 13:51:16.815  4287  4297 D BluetoothLeScanner: Exiting stopAllScan
,05-25 13:51:16.815  4249  4259 D BluetoothAdapter: onBluetoothStateChange: up=false
05-25 13:51:16.815  4249  4259 D BluetoothAdapter: Bluetooth is turned off, stop adv
,05-25 13:51:16.825  4249  4259 D BluetoothAdapter: There are no active google scan apps, stop scan
,05-25 13:51:16.825  4857  5184 D BluetoothAdapter: onBluetoothStateChange: up=false
05-25 13:51:16.825  4857  5184 D BluetoothAdapter: Bluetooth is turned off, stop adv
,05-25 13:51:16.825  4857  5184 D BluetoothAdapter: There are no active google scan apps, stop scan
,05-25 13:51:16.825  3949  3961 D BluetoothSap: onBluetoothStateChange: up=false
,05-25 13:51:16.825  4889  4979 D BluetoothAdapter: onBluetoothStateChange: up=false
,05-25 13:51:16.825  4889  4979 D BluetoothAdapter: Bluetooth is turned off, stop adv
05-25 13:51:16.825  4889  4979 D BluetoothAdapter: There are no active google scan apps, stop scan
,05-25 13:51:16.825  3949  4123 D BluetoothPan: onBluetoothStateChange on: false
,05-25 13:51:16.825  9936  9946 D BluetoothAdapter: onBluetoothStateChange: up=false
,05-25 13:51:16.825  9936  9946 D BluetoothAdapter: Bluetooth is turned off, stop adv
05-25 13:51:16.825  9936  9946 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
05-25 13:51:16.825  9936  9946 D BluetoothLeAdvertiser: Exit stop advertising
,05-25 13:51:16.835  9936  9946 D BluetoothAdapter: There are no active google scan apps, stop scan
05-25 13:51:16.835  9936  9946 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
05-25 13:51:16.835  9936  9946 D BluetoothLeScanner: Exiting stopAllScan
,05-25 13:51:16.835  3549  3619 D BluetoothA2dp: onBluetoothStateChange: up=false
05-25 13:51:16.835  3949  5555 D BluetoothMap: onBluetoothStateChange: up=false
,05-25 13:51:16.835  7081  7091 D BluetoothAdapter: onBluetoothStateChange: up=false
,05-25 13:51:16.835  7081  7091 D BluetoothAdapter: Bluetooth is turned off, stop adv
05-25 13:51:16.835  7081  7091 D BluetoothAdapter: There are no active google scan apps, stop scan
05-25 13:51:16.835  3549  3619 D BluetoothPan: onBluetoothStateChange on: false
05-25 13:51:16.835  3549  3619 D BluetoothAdapter: onBluetoothStateChange: up=false
,05-25 13:51:16.835  3549  3619 D BluetoothAdapter: Bluetooth is turned off, stop adv
05-25 13:51:16.835  3549  3619 D BluetoothAdapter: There are no active google scan apps, stop scan
,05-25 13:51:16.835  4857  5016 D BluetoothAdapterState: Current state: BLE ON, message: USER_TURN_OFF
,05-25 13:51:16.835  3549  3549 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
05-25 13:51:16.835  3549  3549 I InputMethodManagerService: [BT Setting State] State =10
05-25 13:51:16.835  3549  3549 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,05-25 13:51:16.835  3949  4133 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,05-25 13:51:16.835  3949  4133 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
05-25 13:51:16.835  4316  4316 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
,05-25 13:51:16.845  4782  4782 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,05-25 13:51:16.845  3549  3549 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
05-25 13:51:16.845  3549  3549 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
05-25 13:51:16.845  3549  3549 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,05-25 13:51:16.845  9180  9180 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
05-25 13:51:16.845  9180  9180 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,05-25 13:51:16.855  9936  9936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:51:16.855  3549  3603 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5af7a32 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{244f13b 9180:com.android.settings/1000}
,05-25 13:51:16.855  4857  5016 D BluetoothAdapterProperties: Setting state to 16
05-25 13:51:16.855  4857  5016 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
05-25 13:51:16.855  4857  5016 D BluetoothAdapterService: Bluetooth PBAP supproted is true
05-25 13:51:16.855  4857  5016 D BluetoothAdapterService: updateAdapterState state is 16
,05-25 13:51:16.855  3549  3619 D BluetoothManagerService: Ble Turning On/Off, G state: 3, S state: 3
05-25 13:51:16.855  4857  5016 D BluetoothAdapterService: Autoconnection is available 
05-25 13:51:16.855  4857  5016 D BluetoothAdapterService: updateAdapterState prevState = 15newState = 16
05-25 13:51:16.855  4857  5016 D BluetoothAdapterProperties: onBleDisable
05-25 13:51:16.855  3549  4435 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
,05-25 13:51:16.855  3949  4213 D BluetoothTile: handleUpdateState :  supported = true, enabled = false, enabling = false, connected = false, connecting = false, mController.getLastDeviceName() = null
05-25 13:51:16.865  3549  3567 D SecContentProvider: insert(), uri = 2
05-25 13:51:16.865  3549  4420 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,05-25 13:51:16.865  4857  5016 I BluetoothAdapterState: Entering PendingCommandState
05-25 13:51:16.865  4857  5019 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
05-25 13:51:16.865  4857  5019 E bt_btif : btif_vhci_sock_cleanup
,05-25 13:51:16.865  4857  5150 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,05-25 13:51:16.865  3549  4367 V AlarmManager:  remove PendingIntent] PendingIntent{79e7383: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:16.875  4857  5022 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,05-25 13:51:16.875  4857  5022 D BluetoothAdapterProperties: Scan Mode:20
,05-25 13:51:16.875  3549  3568 V AlarmManager:  remove PendingIntent] PendingIntent{ffb4900: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:16.885  9180  9180 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,05-25 13:51:16.885  9936  9936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:51:16.905  3549  4435 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5af7a32 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{44442de 4889:com.samsung.android.providers.context/u0a7}
,05-25 13:51:16.905  9180  9180 D DockEventReceiver: finishStartingService: stopping service
05-25 13:51:16.905  9936 10036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
05-25 13:51:16.905  9936 10036 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-25 13:51:16.905  9936 10036 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-25 13:51:16.905  9936 10036 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-25 13:51:16.905  9936 10036 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-25 13:51:16.905  9936 10036 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
05-25 13:51:16.905  9936 10036 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-25 13:51:16.905  9936 10036 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-25 13:51:16.905  9936 10036 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-25 13:51:16.905  9936 10036 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,05-25 13:51:16.915  9936 10036 D BluetoothAdapter: enable()
,05-25 13:51:16.915  9936  9999 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
05-25 13:51:16.915  3549  4432 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5af7a32 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f3ae3d9 4287:com.google.android.gms.persistent/u0a19}
,05-25 13:51:16.915  4287  4287 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
,05-25 13:51:16.935  3549  3567 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5af7a32 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a2429dc 8769:com.sec.android.app.shealth:remote/u0a36}
,05-25 13:51:16.935  3549  4066 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,05-25 13:51:16.935  3549  4066 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4325, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:51:16.935  3549  4066 D BatteryService: online:4, current avg:58, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:46
05-25 13:51:16.935  3549  3549 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:51:16.945  3549  3549 I MotionRecognitionService: Plugged
,05-25 13:51:16.945  3549  4285 W ActivityManager: Permission Denial: getCurrentUser() from pid=9936, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
05-25 13:51:16.945  3549  3549 D MotionRecognitionService:   cableConnection= 1
05-25 13:51:16.945  3549  3549 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:51:16.945  3549  3549 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:51:16.945  3549  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
05-25 13:51:16.945  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,05-25 13:51:16.945  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
05-25 13:51:16.945  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
05-25 13:51:16.945  3549  4285 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
05-25 13:51:16.945  3549  4285 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9936, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
05-25 13:51:16.945  3549  4285 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-25 13:51:16.945  3549  4285 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2852)
05-25 13:51:16.945  3549  4285 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2842)
05-25 13:51:16.945  3549  4285 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.setBtEnableFlag(BluetoothManagerService.java:1222)
05-25 13:51:16.945  3549  4285 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:254)
05-25 13:51:16.945  3549  4285 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:453)
,05-25 13:51:16.945  3549  4285 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,05-25 13:51:16.945  3549  4285 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,05-25 13:51:16.955  3549  4285 D SettingsProvider: isChangeAllowed() : name = bluetooth_on
,05-25 13:51:16.955  4905  4905 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:51:16.965  4905  4905 D BatteryMonitor: new battery level: 100
,05-25 13:51:16.965  3549  3567 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5af7a32 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{244f13b 9180:com.android.settings/1000}
,05-25 13:51:16.965  9180  9180 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
,05-25 13:51:16.965  9180  9180 D BluetoothStatusReceiver: AdapterStateChanged :: state = 10
,05-25 13:51:16.985  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:16.985  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:16.985  3549  4435 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5af7a32 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d7577e4 4857:com.android.bluetooth/1002}
,05-25 13:51:16.995  4857 10046 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,05-25 13:51:16.995  4857 10046 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,05-25 13:51:17.005  4857  5016 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BLE_TURN_ON
,05-25 13:51:17.005  4857  5016 E BluetoothAdapterState: Don't defer BLE_TURN_ON request.
,05-25 13:51:17.015  3549  4435 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5af7a32 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a53ad79 7081:com.google.android.apps.maps/u0a119}
,05-25 13:51:17.025  3549  4931 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-25 13:51:17.025  3549  4931 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4322, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:51:17.025  3549  4931 D BatteryService: online:4, current avg:58, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-14
,05-25 13:51:17.025  3549  3549 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:51:17.025  3549  3549 I MotionRecognitionService: Plugged
05-25 13:51:17.025  3549  3549 D MotionRecognitionService:   cableConnection= 1
05-25 13:51:17.025  3549  3549 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:51:17.025  3549  3549 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:51:17.025  3549  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:51:17.025  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
05-25 13:51:17.025  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
05-25 13:51:17.035  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:51:17.035  4905  4905 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:51:17.035  4905  4905 D BatteryMonitor: new battery level: 100
,05-25 13:51:17.045  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
05-25 13:51:17.045  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:17.055  3549  4435 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{dd7077e u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{44442de 4889:com.samsung.android.providers.context/u0a7}
,05-25 13:51:17.065  4857  5022 I bt_hci  : shut_down
05-25 13:51:17.065  3549  4286 V AlarmManager:  remove PendingIntent] PendingIntent{24ac4df: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
05-25 13:51:17.065  4857  5072 D bt_hwcfg: hw_epilog_process
,05-25 13:51:17.065  4857  5016 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa689ba
05-25 13:51:17.065  4857  5072 I bt_vendor: low_power_mode_cb
,05-25 13:51:17.065  4857  5072 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,05-25 13:51:17.065  4857  5072 I bt_vendor: epilog_cb
05-25 13:51:17.065  4857  5072 I bt_hci  : epilog_finished_callback
05-25 13:51:17.065  4857  5022 I bt_hci_h4: hal_close
,05-25 13:51:17.065  4857  5022 I bt_userial_vendor: device fd = 60 close
,05-25 13:51:17.065  4857  5022 I bt_upio : upio_set_bluetooth_power(on: 0)
,05-25 13:51:17.075  3549  3603 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{54bf52c u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{44442de 4889:com.samsung.android.providers.context/u0a7}
,05-25 13:51:17.075  4857  5019 D bt_stack_manager: event_shut_down_stack finished.
,05-25 13:51:17.075  4857  5022 E BluetoothAdapterState: stateChangeCallback : 0
05-25 13:51:17.075  4857  5016 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: DISABLED
,05-25 13:51:17.085  3549  4367 V AlarmManager:  remove PendingIntent] PendingIntent{212fbf5: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:17.085  4857  4857 D BtGatt.DebugUtils: handleDebugAction() action=null
05-25 13:51:17.085  4857  5016 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
05-25 13:51:17.085  4857  4857 D BtGatt.GattService: Received stop request...Stopping profile...
05-25 13:51:17.085  4857  4857 D BtGatt.GattService: stop()
,05-25 13:51:17.085  4857  4857 D BtGatt.GattService: [GSIM LOG]: saveLogPref
05-25 13:51:17.085  4857  4857 D BtGatt.GattService: [GSIM LOG]: saveLogPref END
05-25 13:51:17.085  4857  4857 D BtGatt.GattService: cleanup binder
05-25 13:51:17.085  3549  4435 V AlarmManager:  remove PendingIntent] PendingIntent{f581d8a: PendingIntentRecord{440cffb com.android.bluetooth broadcastIntent}}
05-25 13:51:17.085  4857  4857 D BtGatt.AdvertiseManager: advertise clients cleared
05-25 13:51:17.085  4857  4857 D BtGatt.ScanManager: cleanup
,05-25 13:51:17.085  4857  4857 D BtGatt.ScanManager: cleanup handler
,05-25 13:51:17.085  4857  4857 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, Message sending
05-25 13:51:17.085  4857  4857 E BtGatt.GattService: notifyProfileServiceStateChanged
05-25 13:51:17.085  4857  4857 E BluetoothAdapterService: handleMessage() - Message: 1
05-25 13:51:17.085  4857  4857 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, Before synchronized
,05-25 13:51:17.085  4857  4857 V BluetoothAdapterState: isTurningOff()=false
05-25 13:51:17.085  4857  4857 V BluetoothAdapterState: isTurningOn()=false
05-25 13:51:17.085  3549  4170 V AlarmManager:  remove PendingIntent] PendingIntent{6193818: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:17.085  4857  4857 V BluetoothAdapterState: isBleTurningOn()=false
05-25 13:51:17.085  4857  4857 V BluetoothAdapterState: isBleTurningOff()=true
05-25 13:51:17.085  4857  5016 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BLE_STOPPED
,05-25 13:51:17.085  4857  5016 D BluetoothAdapterProperties: Setting state to 10
05-25 13:51:17.085  4857  5016 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
05-25 13:51:17.085  4857  5016 D BluetoothAdapterService: Bluetooth PBAP supproted is true
05-25 13:51:17.085  4857  5016 D BluetoothAdapterService: updateAdapterState state is 10
,05-25 13:51:17.095  4857  5016 D BluetoothAdapterService: Autoconnection is available 
,05-25 13:51:17.095  4857  5016 D BluetoothAdapterService: updateAdapterState prevState = 16newState = 10
05-25 13:51:17.095  4857  5016 D BluetoothAdapterService: BT on, init HID DEV count : 0
05-25 13:51:17.095  4857  5016 I BluetoothAdapterState: Entering OffState
,05-25 13:51:17.095  3549  3981 V AlarmManager:  remove PendingIntent] PendingIntent{2646271: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
05-25 13:51:17.095  3549  3619 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 11 receivers.
,05-25 13:51:17.095  3549  3568 V AlarmManager:  remove PendingIntent] PendingIntent{f228856: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:17.105  3549  3986 V AlarmManager:  remove PendingIntent] PendingIntent{fc270d7: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:17.115  3549  4420 V AlarmManager:  remove PendingIntent] PendingIntent{f534373: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:17.115  4857  4857 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
05-25 13:51:17.115  4857  4857 W BluetoothSdpJni: Cleaning up Bluetooth Health object
05-25 13:51:17.115  4857  4857 I BluetoothServiceJni: cleanupNative: return from cleanup
05-25 13:51:17.115  4857  5019 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,05-25 13:51:17.115  4857  4857 I art     : System.exit called, status: 0
05-25 13:51:17.115  4857  4857 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,05-25 13:51:17.145  3549  4285 I ActivityManager: Process com.android.bluetooth (pid 4857)(adj -11) has died(71,1848)
05-25 13:51:17.145  3549  4285 D ActivityManager: cleanUpApplicationRecord -- 4857
,05-25 13:51:17.145  3549  4285 D ActivityManager: isAutoRunBlockedApp:: com.android.bluetooth, Auto Run ON
05-25 13:51:17.145  3549  4285 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/.btservice.AdapterService in 1000ms
,05-25 13:51:17.365  3549  4435 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,05-25 13:51:17.365  3549  4435 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:51:17.365  3549  4435 D BatteryService: online:4, current avg:57, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:161
05-25 13:51:17.365  3549  3549 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:51:17.365  3549  3549 I MotionRecognitionService: Plugged
05-25 13:51:17.365  3549  3549 D MotionRecognitionService:   cableConnection= 1
05-25 13:51:17.365  3549  3549 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:51:17.365  3549  3549 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:51:17.375  3549  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:51:17.375  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
05-25 13:51:17.375  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
,05-25 13:51:17.375  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:51:17.385  4905  4905 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:51:17.395  4905  4905 D BatteryMonitor: new battery level: 100
,05-25 13:51:17.405  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:17.405  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:17.505  9936 10036 D BluetoothAdapter: enable()
,05-25 13:51:17.505  3549  4170 W ActivityManager: Permission Denial: getCurrentUser() from pid=9936, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
,05-25 13:51:17.505  3549  4170 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
05-25 13:51:17.505  3549  4170 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9936, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
05-25 13:51:17.505  3549  4170 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-25 13:51:17.505  3549  4170 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2852)
05-25 13:51:17.505  3549  4170 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2842)
05-25 13:51:17.505  3549  4170 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.setBtEnableFlag(BluetoothManagerService.java:1222)
05-25 13:51:17.505  3549  4170 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:254)
05-25 13:51:17.505  3549  4170 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:453)
,05-25 13:51:17.505  3549  4170 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,05-25 13:51:17.515  3549  4170 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,05-25 13:51:17.515  3549  4170 D SettingsProvider: isChangeAllowed() : name = bluetooth_on
,05-25 13:51:18.025  9936 10036 D BluetoothAdapter: enable()
,05-25 13:51:18.035  3549  4367 W ActivityManager: Permission Denial: getCurrentUser() from pid=9936, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
,05-25 13:51:18.035  3549  4367 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
05-25 13:51:18.035  3549  4367 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9936, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
05-25 13:51:18.035  3549  4367 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-25 13:51:18.035  3549  4367 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2852)
05-25 13:51:18.035  3549  4367 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2842)
05-25 13:51:18.035  3549  4367 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.setBtEnableFlag(BluetoothManagerService.java:1222)
05-25 13:51:18.035  3549  4367 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:254)
05-25 13:51:18.035  3549  4367 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:453)
05-25 13:51:18.035  3549  4367 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,05-25 13:51:18.035  3549  4367 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,05-25 13:51:18.035  3549  4367 D SettingsProvider: isChangeAllowed() : name = bluetooth_on
,05-25 13:51:18.185 10053 10053 E Zygote  : v2
05-25 13:51:18.185 10053 10053 I libpersona: KNOX_SDCARD checking this for 1002
05-25 13:51:18.185 10053 10053 I libpersona: KNOX_SDCARD not a persona
05-25 13:51:18.185 10053 10053 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-25 13:51:18.185 10053 10053 E Zygote  : accessInfo : 0
,05-25 13:51:18.185  3549  3603 I ActivityManager: Start proc 10053:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,05-25 13:51:18.225 10053 10053 D TimaKeyStoreProvider: TimaSignature is unavailable
05-25 13:51:18.225 10053 10053 D ActivityThread: Added TimaKeyStore provider
,05-25 13:51:18.255 10053 10053 W ResourcesManager: getTopLevelResources: /system/app/Bluetooth/Bluetooth.apk / 1.0 running in com.android.bluetooth rsrc of package com.android.bluetooth
,05-25 13:51:18.265  3549  4420 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-25 13:51:18.265 10053 10053 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-25 13:51:18.265 10053 10053 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:51:18.275 10053 10053 I InjectionManager: Inside getClassLibPath caller 
,05-25 13:51:18.305 10053 10053 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,05-25 13:51:18.335 10053 10053 D BtSettings.ProfileConfig: Adding GattService
,05-25 13:51:18.335 10053 10053 D BtSettings.ProfileConfig: Adding HeadsetService
05-25 13:51:18.335 10053 10053 D BtSettings.ProfileConfig: Adding A2dpService
,05-25 13:51:18.335 10053 10053 D BtSettings.ProfileConfig: Adding HidService
,05-25 13:51:18.335 10053 10053 D BtSettings.ProfileConfig: Adding HealthService
05-25 13:51:18.335 10053 10053 D BtSettings.ProfileConfig: Adding PanService
,05-25 13:51:18.335 10053 10053 D BtSettings.ProfileConfig: Adding BluetoothMapService
,05-25 13:51:18.335 10053 10053 D BtSettings.ProfileConfig: Adding SapService
,05-25 13:51:18.345 10053 10053 D BtSettings.ProfileConfig: Adding HeadsetClientService
,05-25 13:51:18.345 10053 10053 D BtSettings.ProfileConfig: Adding A2dpSinkService
05-25 13:51:18.345 10053 10053 D BtSettings.ProfileConfig: Adding BleAudioService
05-25 13:51:18.345 10053 10053 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,05-25 13:51:18.345  3549  3838 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.gatt.GattService
,05-25 13:51:18.345  3549  3838 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
05-25 13:51:18.345  3549  3838 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
05-25 13:51:18.345  3549  3838 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
05-25 13:51:18.345  3549  3838 D SettingsProvider: selectionArgs: false
05-25 13:51:18.345  3549  3838 D SettingsProvider: selectionArgs: 1002
,05-25 13:51:18.345  3549  3838 D SettingsProvider: ret = -1
,05-25 13:51:18.345  3549  4432 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,05-25 13:51:18.345  3549  4432 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
05-25 13:51:18.345  3549  4432 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
05-25 13:51:18.345  3549  4432 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
05-25 13:51:18.345  3549  4432 D SettingsProvider: selectionArgs: false
05-25 13:51:18.345  3549  4432 D SettingsProvider: selectionArgs: 1002
05-25 13:51:18.355  3549  4432 D SettingsProvider: ret = -1
,05-25 13:51:18.355  3549  3567 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,05-25 13:51:18.355  3549  3567 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
05-25 13:51:18.355  3549  3567 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
05-25 13:51:18.355  3549  3567 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
05-25 13:51:18.355  3549  3567 D SettingsProvider: selectionArgs: false
05-25 13:51:18.355  3549  3567 D SettingsProvider: selectionArgs: 1002
05-25 13:51:18.355  3549  3567 D SettingsProvider: ret = -1
,05-25 13:51:18.355  3549  3981 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.hid.HidService
,05-25 13:51:18.355  3549  3981 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
05-25 13:51:18.355  3549  3981 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
05-25 13:51:18.355  3549  3981 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
05-25 13:51:18.355  3549  3981 D SettingsProvider: selectionArgs: false
,05-25 13:51:18.355  3549  3981 D SettingsProvider: selectionArgs: 1002
05-25 13:51:18.355  3549  3981 D SettingsProvider: ret = -1
,05-25 13:51:18.355  3549  3986 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.hdp.HealthService
,05-25 13:51:18.355  3549  3986 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
05-25 13:51:18.355  3549  3986 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
05-25 13:51:18.355  3549  3986 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
05-25 13:51:18.355  3549  3986 D SettingsProvider: selectionArgs: false
05-25 13:51:18.355  3549  3986 D SettingsProvider: selectionArgs: 1002
,05-25 13:51:18.355  3549  3986 D SettingsProvider: ret = -1
,05-25 13:51:18.355  3549  4066 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.pan.PanService
,05-25 13:51:18.355  3549  4066 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
05-25 13:51:18.355  3549  4066 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
05-25 13:51:18.355  3549  4066 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
05-25 13:51:18.355  3549  4066 D SettingsProvider: selectionArgs: false
,05-25 13:51:18.355  3549  4066 D SettingsProvider: selectionArgs: 1002
05-25 13:51:18.355  3549  4066 D SettingsProvider: ret = -1
,05-25 13:51:18.365  3549  4286 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
,05-25 13:51:18.365  3549  4286 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
05-25 13:51:18.365  3549  4286 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
05-25 13:51:18.365  3549  4286 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
05-25 13:51:18.365  3549  4286 D SettingsProvider: selectionArgs: false
05-25 13:51:18.365  3549  4286 D SettingsProvider: selectionArgs: 1002
,05-25 13:51:18.365  3549  4286 D SettingsProvider: ret = -1
,05-25 13:51:18.365  3549  4420 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.sap.SapService
,05-25 13:51:18.365  3549  4420 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
05-25 13:51:18.365  3549  4420 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
05-25 13:51:18.365  3549  4420 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
05-25 13:51:18.365  3549  4420 D SettingsProvider: selectionArgs: false
05-25 13:51:18.365  3549  4420 D SettingsProvider: selectionArgs: 1002
05-25 13:51:18.365  3549  4420 D SettingsProvider: ret = -1
,05-25 13:51:18.365  3549  4170 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,05-25 13:51:18.365  3549  4170 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
05-25 13:51:18.365  3549  4170 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,05-25 13:51:18.365  3549  4170 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
05-25 13:51:18.365  3549  4170 D SettingsProvider: selectionArgs: false
05-25 13:51:18.365  3549  4170 D SettingsProvider: selectionArgs: 1002
05-25 13:51:18.365  3549  4170 D SettingsProvider: ret = -1
,05-25 13:51:18.365  3549  3568 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
05-25 13:51:18.365  3549  3568 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
05-25 13:51:18.365  3549  3568 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
05-25 13:51:18.365  3549  3568 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,05-25 13:51:18.365  3549  3568 D SettingsProvider: selectionArgs: false
05-25 13:51:18.365  3549  3568 D SettingsProvider: selectionArgs: 1002
05-25 13:51:18.365  3549  3568 D SettingsProvider: ret = -1
,05-25 13:51:18.365  3549  4430 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.broadcom.bt.service.bleaudio.BleAudioService
,05-25 13:51:18.365  3549  4430 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
05-25 13:51:18.365  3549  4430 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
05-25 13:51:18.365  3549  4430 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
05-25 13:51:18.365  3549  4430 D SettingsProvider: selectionArgs: false
05-25 13:51:18.365  3549  4430 D SettingsProvider: selectionArgs: 1002
,05-25 13:51:18.365  3549  4430 D SettingsProvider: ret = -1
05-25 13:51:18.375 10053 10053 D InjectionManager: InjectionManager
05-25 13:51:18.375 10053 10053 D InjectionManager: fillFeatureStoreMap com.android.bluetooth
05-25 13:51:18.375 10053 10053 I InjectionManager: Constructor com.android.bluetooth, Feature store :{}
,05-25 13:51:18.375 10053 10053 I InjectionManager: featureStore :{}
,05-25 13:51:18.385  3549  4285 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,05-25 13:51:18.385  3549  4285 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:51:18.385  3549  4285 D BatteryService: online:4, current avg:64, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:22
05-25 13:51:18.385  3549  3549 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:51:18.385  3549  3549 I MotionRecognitionService: Plugged
05-25 13:51:18.385  3549  3549 D MotionRecognitionService:   cableConnection= 1
05-25 13:51:18.385  3549  3549 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,05-25 13:51:18.385  3549  3549 D MotionRecognitionService: skip setTransmitPower. 
05-25 13:51:18.385  3549  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:51:18.385  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,05-25 13:51:18.385  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
05-25 13:51:18.385  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:51:18.395  4905  4905 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:51:18.405  4905  4905 D BatteryMonitor: new battery level: 100
,05-25 13:51:18.415  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:18.415  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:18.415 10053 10053 D BluetoothAdapterState: make() - Creating AdapterState
,05-25 13:51:18.425 10053 10053 I bt_bluedroid: init
,05-25 13:51:18.425 10053 10067 I BluetoothAdapterState: Entering OffState
,05-25 13:51:18.425 10053 10068 E bt_core_counter: counter_init unable to open counter port
05-25 13:51:18.425 10053 10068 E bt_core_module: module_init failed to initialize "counter_module"
,05-25 13:51:18.425 10053 10068 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
05-25 13:51:18.425 10053 10068 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
05-25 13:51:18.425 10053 10068 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
05-25 13:51:18.425 10053 10068 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,05-25 13:51:18.435 10053 10053 I bt_bluedroid: get_profile_interface socket
,05-25 13:51:18.435 10053 10053 W bt_btif : btif_get_adapter_property 2
05-25 13:51:18.435 10053 10053 W bt_btif : btif_get_adapter_property 1
,05-25 13:51:18.435 10053 10071 D BluetoothAdapterProperties: Address is:44:78:3E:94:4A:3E
05-25 13:51:18.435 10053 10071 E BluetoothServiceJni: populateRssiValuesNative
05-25 13:51:18.435 10053 10071 I bt_bluedroid: getModelRssiValues
,05-25 13:51:18.435 10053 10071 E BluetoothServiceJni: model_rssi_values_callback: low = -75, mid = -65, high = 127
05-25 13:51:18.435 10053 10071 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -75,-65,127
,05-25 13:51:18.435 10053 10071 D BluetoothAdapterProperties: Name is: Samsung Galaxy S7
,05-25 13:51:18.435  3549  3549 D SettingsProvider: isChangeAllowed() : name = bluetooth_name
,05-25 13:51:18.445 10053 10053 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,05-25 13:51:18.445 10053 10053 I bt_bluedroid: get_profile_interface sdp
,05-25 13:51:18.455 10053 10063 I bt_bluedroid: config_hci_snoop_log
,05-25 13:51:18.455  3549  3619 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 11 receivers.
,05-25 13:51:18.465 10053 10067 D BluetoothAdapterState: Current state: OFF, message: BLE_TURN_ON
,05-25 13:51:18.465 10053 10067 D BluetoothAdapterProperties: Setting state to 14
,05-25 13:51:18.465 10053 10067 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
05-25 13:51:18.465 10053 10067 D BluetoothAdapterService: Bluetooth PBAP supproted is true
05-25 13:51:18.465 10053 10067 D BluetoothAdapterService: updateAdapterState state is 14
05-25 13:51:18.465  3549  3619 D BluetoothManagerService: Ble Turning On/Off, G state: 1, S state: 1
,05-25 13:51:18.465 10053 10067 D BluetoothAdapterService: Autoconnection is available 
,05-25 13:51:18.465 10053 10067 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 14
05-25 13:51:18.475 10053 10067 D BluetoothSecureManager: getInstant: null
,05-25 13:51:18.475 10053 10067 D BluetoothSecureManager: calling getMethod for getService
05-25 13:51:18.475 10053 10067 D BluetoothSecureManager: calling getService
05-25 13:51:18.475 10053 10067 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@c14874
,05-25 13:51:18.475  3549  3986 D BluetoothSecureManagerService: isSecureModeEnabled
,05-25 13:51:18.475  3549  3986 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
05-25 13:51:18.475 10053 10067 D BtConfig.SecureMode: isSecureModeOn:false
05-25 13:51:18.475 10053 10067 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,05-25 13:51:18.475 10053 10067 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
05-25 13:51:18.475 10053 10067 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,05-25 13:51:18.475 10053 10067 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
,05-25 13:51:18.475 10053 10067 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
05-25 13:51:18.475 10053 10067 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
,05-25 13:51:18.475 10053 10067 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
05-25 13:51:18.475 10053 10067 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
05-25 13:51:18.475 10053 10067 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,05-25 13:51:18.485 10053 10067 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
05-25 13:51:18.485 10053 10067 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,05-25 13:51:18.485 10053 10067 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
,05-25 13:51:18.485 10053 10067 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
05-25 13:51:18.485 10053 10067 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
05-25 13:51:18.485 10053 10067 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
,05-25 13:51:18.485 10053 10067 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.sap.SapService
05-25 13:51:18.485 10053 10067 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,05-25 13:51:18.485 10053 10067 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
05-25 13:51:18.485 10053 10067 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,05-25 13:51:18.485 10053 10067 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
05-25 13:51:18.485 10053 10067 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.bleaudio.BleAudioService
,05-25 13:51:18.485 10053 10067 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.bleaudio.BleAudioService
,05-25 13:51:18.485 10053 10067 D BluetoothBondStateMachine: make
,05-25 13:51:18.495 10053 10072 I BluetoothBondStateMachine: StableState(): Entering Off State
,05-25 13:51:18.505 10053 10067 I BluetoothAdapterState: Entering PendingCommandState
,05-25 13:51:18.505 10053 10053 I BtGatt.JNI: classInitNative(L992): classInitNative: Success!
,05-25 13:51:18.505 10053 10053 D BtGatt.DebugUtils: handleDebugAction() action=null
,05-25 13:51:18.505 10053 10053 D BtGatt.GattService: Received start request. Starting profile...
05-25 13:51:18.505 10053 10053 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa689ba
05-25 13:51:18.505 10053 10053 D BtGatt.GattService: start()
05-25 13:51:18.505 10053 10053 I bt_bluedroid: get_profile_interface gatt
,05-25 13:51:18.505 10053 10053 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa689ba
05-25 13:51:18.505 10053 10053 D BtGatt.AdvertiseManager: advertise manager created
05-25 13:51:18.505 10053 10053 D BtGatt.AdvertiseManager: start
,05-25 13:51:18.515 10053 10053 D BtGatt.ScanManager: start
,05-25 13:51:18.515 10053 10053 D BtGatt.GattService: [GSIM LOG]: loadLogPref
,05-25 13:51:18.535 10053 10053 D BtGatt.GattService: [GSIM LOG]: loadLogPref END
,05-25 13:51:18.545 10053 10053 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, Message sending
05-25 13:51:18.545 10053 10053 E BtGatt.GattService: notifyProfileServiceStateChanged
05-25 13:51:18.545 10053 10053 E BluetoothAdapterService: handleMessage() - Message: 1
,05-25 13:51:18.545 10053 10053 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, Before synchronized
,05-25 13:51:18.545 10053 10053 V BluetoothAdapterState: isTurningOff()=false
05-25 13:51:18.545 10053 10053 V BluetoothAdapterState: isTurningOn()=false
05-25 13:51:18.545 10053 10053 V BluetoothAdapterState: isBleTurningOn()=true
05-25 13:51:18.545 10053 10053 V BluetoothAdapterState: isBleTurningOff()=false
05-25 13:51:18.545 10053 10067 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BLE_STARTED
,05-25 13:51:18.545  9936 10036 D BluetoothAdapter: enable()
,05-25 13:51:18.555 10053 10067 I bt_bluedroid: bt_bluedroid
05-25 13:51:18.555 10053 10068 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,05-25 13:51:18.555 10053 10068 I bt_hci  : start_up
,05-25 13:51:18.555  3549  4435 W ActivityManager: Permission Denial: getCurrentUser() from pid=9936, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
,05-25 13:51:18.555  3549  4435 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
05-25 13:51:18.555  3549  4435 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9936, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
05-25 13:51:18.555  3549  4435 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-25 13:51:18.555  3549  4435 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2852)
05-25 13:51:18.555  3549  4435 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2842)
05-25 13:51:18.555  3549  4435 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.setBtEnableFlag(BluetoothManagerService.java:1222)
05-25 13:51:18.555  3549  4435 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:254)
05-25 13:51:18.555  3549  4435 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:453)
05-25 13:51:18.555  3549  4435 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,05-25 13:51:18.555  3549  4435 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,05-25 13:51:18.555  3549  4435 D SettingsProvider: isChangeAllowed() : name = bluetooth_on
,05-25 13:51:18.565  3549  3603 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{84c1ebf u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{44442de 4889:com.samsung.android.providers.context/u0a7}
,05-25 13:51:18.575 10053 10068 I bt_vendor: alloc value 0xf39ce171
05-25 13:51:18.575 10053 10068 I bt_vendor: init
05-25 13:51:18.575 10053 10068 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
05-25 13:51:18.575 10053 10068 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
05-25 13:51:18.575 10053 10068 I bt_upio : upio_set_bluetooth_power(on: 0)
05-25 13:51:18.575 10053 10068 I bt_upio : upio_set_bluetooth_power(on: 1)
,05-25 13:51:18.585 10053 10067 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BLE_TURN_ON
,05-25 13:51:18.585 10053 10067 E BluetoothAdapterState: Don't defer BLE_TURN_ON request.
,05-25 13:51:18.685 10053 10068 D bt_hci  : start_up starting async portion
,05-25 13:51:18.685 10053 10084 I bt_hci  : event_finish_startup
05-25 13:51:18.685 10053 10084 I bt_hci_h4: hal_open
05-25 13:51:18.685 10053 10084 I bt_userial_vendor: userial vendor open: opening /dev/ttySAC1
,05-25 13:51:18.685 10053 10084 I bt_userial_vendor: userial_vendor_open():UART is setup
05-25 13:51:18.685 10053 10084 I bt_userial_vendor: device fd = 60 open
,05-25 13:51:18.685 10053 10084 E bt_hwcfg: Start CFG HW, HCI reset
,05-25 13:51:18.685 10053 10084 E bt_hwcfg: Read Local Name after HCI reset
,05-25 13:51:18.685  3549  4435 V AlarmManager:  remove PendingIntent] PendingIntent{81798c: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:18.705  3549  4432 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,05-25 13:51:18.715  3549  4432 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:51:18.715  3549  4432 D BatteryService: online:4, current avg:63, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:74
05-25 13:51:18.715 10053 10084 D bt_hwcfg: Chipset BCM4359C0
05-25 13:51:18.715  3549  3549 D BatteryService: Sending ACTION_BATTERY_CHANGED.
05-25 13:51:18.715 10053 10084 D bt_hwcfg: Target name = [BCM4359C0]
,05-25 13:51:18.715  3549  3549 I MotionRecognitionService: Plugged
,05-25 13:51:18.715 10053 10084 I bt_hwcfg: module_type[semco_b90s_c0].
05-25 13:51:18.715  3549  3549 D MotionRecognitionService:   cableConnection= 1
05-25 13:51:18.715 10053 10084 E bt_hwcfg: patchram path ORG . BCM4359C0
05-25 13:51:18.715  3549  3549 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:51:18.715 10053 10084 E bt_hwcfg: patchram path ORG .. BCM4359C0
,05-25 13:51:18.715  3549  3549 D MotionRecognitionService: skip setTransmitPower. 
05-25 13:51:18.715 10053 10084 E bt_hwcfg: patchram path ORG bcm4359C0_V0044.0061_murata.hcd BCM4359C0
05-25 13:51:18.715 10053 10084 E bt_hwcfg: patchram path ORG companion_2l1_master_setfile.bin BCM4359C0
05-25 13:51:18.715 10053 10084 E bt_hwcfg: patchram path ORG companion_2l1_mode_setfile.bin BCM4359C0
05-25 13:51:18.715 10053 10084 E bt_hwcfg: patchram path ORG companion_fw_2l1.bin BCM4359C0
05-25 13:51:18.715 10053 10084 E bt_hwcfg: patchram path ORG companion_fw_imx260.bin BCM4359C0
05-25 13:51:18.715 10053 10084 E bt_hwcfg: patchram path ORG companion_imx260_master_setfile.bin BCM4359C0
05-25 13:51:18.715 10053 10084 E bt_hwcfg: patchram path ORG companion_imx260_mode_setfile.bin BCM4359C0
,05-25 13:51:18.715 10053 10084 E bt_hwcfg: patchram path ORG fimc_is_fw2_2l1.bin BCM4359C0
05-25 13:51:18.715 10053 10084 E bt_hwcfg: patchram path ORG fimc_is_fw2_imx260.bin BCM4359C0
05-25 13:51:18.715 10053 10084 E bt_hwcfg: patchram path ORG mfc_fw.bin BCM4359C0
05-25 13:51:18.715 10053 10084 E bt_hwcfg: patchram path ORG ois_fw_dom.bin BCM4359C0
05-25 13:51:18.715 10053 10084 E bt_hwcfg: patchram path ORG ois_fw_sec.bin BCM4359C0
05-25 13:51:18.715 10053 10084 E bt_hwcfg: patchram path ORG sec_s3nrn81_firmware.bin BCM4359C0
05-25 13:51:18.715 10053 10084 E bt_hwcfg: patchram path ORG seiren_fw_dram.bin BCM4359C0
05-25 13:51:18.715 10053 10084 E bt_hwcfg: patchram path ORG seiren_fw_sram.bin BCM4359C0
,05-25 13:51:18.715 10053 10084 E bt_hwcfg: patchram path ORG setfile_2l1.bin BCM4359C0
05-25 13:51:18.715 10053 10084 E bt_hwcfg: patchram path ORG setfile_4e6.bin BCM4359C0
05-25 13:51:18.715 10053 10084 E bt_hwcfg: patchram path ORG setfile_imx260.bin BCM4359C0
05-25 13:51:18.715 10053 10084 E bt_hwcfg: patchram path ORG bcm4359C0_V0044.0062_semco.hcd BCM4359C0
05-25 13:51:18.715 10053 10084 I bt_hwcfg: patch(org) : bcm4359C0_V0044.0062_semco.hcd
05-25 13:51:18.715 10053 10084 I bt_hwcfg: Found patchfile: /vendor/firmware/bcm4359C0_V0044.0062_semco.hcd
05-25 13:51:18.715 10053 10084 E bt_hwcfg: ORG patchram base 0044
05-25 13:51:18.715 10053 10084 E bt_hwcfg: ORG patchram minor 0062
,05-25 13:51:18.715 10053 10084 E bt_hwcfg: fw ver (org)44.62
05-25 13:51:18.715 10053 10084 E bt_hwcfg: Final Patchram is /vendor/firmware/bcm4359C0_V0044.0062_semco.hcd
05-25 13:51:18.715  3549  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:51:18.725  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
05-25 13:51:18.725  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
05-25 13:51:18.725  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:51:18.725 10053 10084 I bt_hwcfg: Axi patch failure or not include AXI patching
05-25 13:51:18.725  3549  3981 V AlarmManager:  remove PendingIntent] PendingIntent{87198d5: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:18.725 10053 10084 I bt_hwcfg: bt vendor lib baud_1: set UART baud 3000000
,05-25 13:51:18.735  4905  4905 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:51:18.735  4905  4905 D BatteryMonitor: new battery level: 100
,05-25 13:51:18.735  3549  4430 V AlarmManager:  remove PendingIntent] PendingIntent{ead28ea: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:18.745  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:18.745  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:18.835  3549  3567 V AlarmManager:  remove PendingIntent] PendingIntent{12de7db: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:18.835  3549  3981 V AlarmManager:  remove PendingIntent] PendingIntent{b92a278: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:18.885  3549  3568 V AlarmManager:  remove PendingIntent] PendingIntent{bbfed51: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:18.895  3549  4420 V AlarmManager:  remove PendingIntent] PendingIntent{8ace9b6: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:18.905  3549  4285 V AlarmManager:  remove PendingIntent] PendingIntent{99926b7: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:18.915  3549  4435 V AlarmManager:  remove PendingIntent] PendingIntent{88b6e24: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:18.925  3549  4432 V AlarmManager:  remove PendingIntent] PendingIntent{2c50d8d: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:18.945  3549  4170 V AlarmManager:  remove PendingIntent] PendingIntent{15eb42: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:18.955  3549  4285 V AlarmManager:  remove PendingIntent] PendingIntent{e0f7753: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:18.965  3549  4435 V AlarmManager:  remove PendingIntent] PendingIntent{234890: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:18.975  3549  4432 V AlarmManager:  remove PendingIntent] PendingIntent{e81f589: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:18.985  3549  3568 V AlarmManager:  remove PendingIntent] PendingIntent{71b798e: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.005  3549  4430 V AlarmManager:  remove PendingIntent] PendingIntent{79035af: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.005  3549  4367 V AlarmManager:  remove PendingIntent] PendingIntent{d1c5dbc: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.015  3549  3567 V AlarmManager:  remove PendingIntent] PendingIntent{50b6145: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.025  3549  3981 V AlarmManager:  remove PendingIntent] PendingIntent{dd9a09a: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.035  3549  3568 V AlarmManager:  remove PendingIntent] PendingIntent{5b47dcb: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.035  3549  4066 V AlarmManager:  remove PendingIntent] PendingIntent{22f99a8: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.055  3549  4367 V AlarmManager:  remove PendingIntent] PendingIntent{f05ccc1: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.065  3549  3838 V AlarmManager:  remove PendingIntent] PendingIntent{8212c66: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.075  3549  3568 V AlarmManager:  remove PendingIntent] PendingIntent{e8b2ba7: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.075  9936 10036 D BluetoothAdapter: enable()
,05-25 13:51:19.085  3549  4367 W ActivityManager: Permission Denial: getCurrentUser() from pid=9936, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
,05-25 13:51:19.085  3549  4367 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
05-25 13:51:19.085  3549  4367 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9936, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
05-25 13:51:19.085  3549  4367 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-25 13:51:19.085  3549  4367 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2852)
05-25 13:51:19.085  3549  4367 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2842)
05-25 13:51:19.085  3549  4367 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.setBtEnableFlag(BluetoothManagerService.java:1222)
05-25 13:51:19.085  3549  4367 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:254)
05-25 13:51:19.085  3549  4367 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:453)
,05-25 13:51:19.085  3549  4367 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,05-25 13:51:19.085  3549  4367 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,05-25 13:51:19.095  3549  4367 D SettingsProvider: isChangeAllowed() : name = bluetooth_on
,05-25 13:51:19.095  3549  3603 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2b8a854 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{44442de 4889:com.samsung.android.providers.context/u0a7}
,05-25 13:51:19.095  3549  4432 V AlarmManager:  remove PendingIntent] PendingIntent{e173fd: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.115 10053 10084 I bt_hwcfg: bt vendor lib: set UART baud 115200
,05-25 13:51:19.115 10053 10084 I bt_hwcfg: FW Download delta = 425944
05-25 13:51:19.115 10053 10084 D bt_hwcfg: Settlement delay -- 100 ms
05-25 13:51:19.115 10053 10084 I bt_hwcfg: Setting fw settlement delay to 100 
05-25 13:51:19.115 10053 10067 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BLE_TURN_ON
,05-25 13:51:19.115  3549  3568 V AlarmManager:  remove PendingIntent] PendingIntent{403a8f2: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.115 10053 10067 E BluetoothAdapterState: Don't defer BLE_TURN_ON request.
,05-25 13:51:19.115  3549  4931 V AlarmManager:  remove PendingIntent] PendingIntent{34db43: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.125  3549  4435 V AlarmManager:  remove PendingIntent] PendingIntent{a21f5c0: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.125  3549  3567 V AlarmManager:  remove PendingIntent] PendingIntent{bd652f9: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.135  3549  3986 V AlarmManager:  remove PendingIntent] PendingIntent{d1f623e: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.135  3549  3568 V AlarmManager:  remove PendingIntent] PendingIntent{3fe89f: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.145  3549  4367 V AlarmManager:  remove PendingIntent] PendingIntent{e10adec: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.145  3549  3838 V AlarmManager:  remove PendingIntent] PendingIntent{2a025b5: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.155  3549  4432 V AlarmManager:  remove PendingIntent] PendingIntent{8ab644a: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.155  3549  4286 V AlarmManager:  remove PendingIntent] PendingIntent{4c46fbb: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.165  3549  4433 V AlarmManager:  remove PendingIntent] PendingIntent{750bcd8: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.165  3549  4285 V AlarmManager:  remove PendingIntent] PendingIntent{dfa6831: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.175  3549  4430 V AlarmManager:  remove PendingIntent] PendingIntent{6437b16: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.175  3549  3981 V AlarmManager:  remove PendingIntent] PendingIntent{3404c97: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.175  3549  4420 V AlarmManager:  remove PendingIntent] PendingIntent{d80ce84: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.185  3549  4170 V AlarmManager:  remove PendingIntent] PendingIntent{cdc566d: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.195  3549  4066 V AlarmManager:  remove PendingIntent] PendingIntent{17432a2: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.205  3549  4931 V AlarmManager:  remove PendingIntent] PendingIntent{1331b33: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.205  3549  4435 V AlarmManager:  remove PendingIntent] PendingIntent{17e4ef0: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.215  3549  3567 V AlarmManager:  remove PendingIntent] PendingIntent{c74ec69: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.215  3549  3986 V AlarmManager:  remove PendingIntent] PendingIntent{6d6ee: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.225  3549  3568 V AlarmManager:  remove PendingIntent] PendingIntent{27a378f: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.235  3549  4367 V AlarmManager:  remove PendingIntent] PendingIntent{2916a1c: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.235  3549  3838 V AlarmManager:  remove PendingIntent] PendingIntent{3e6e625: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.245 10053 10084 I bt_hwcfg: bt vendor lib baud_2: set UART baud 3000000
,05-25 13:51:19.245  3549  4432 V AlarmManager:  remove PendingIntent] PendingIntent{90d73fa: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.245  3549  4286 V AlarmManager:  remove PendingIntent] PendingIntent{16cbdab: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.255  3549  4433 V AlarmManager:  remove PendingIntent] PendingIntent{a590c08: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.255  3549  4285 V AlarmManager:  remove PendingIntent] PendingIntent{fc4bfa1: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.265  3549  4430 V AlarmManager:  remove PendingIntent] PendingIntent{aed5c6: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.275  3549  3981 V AlarmManager:  remove PendingIntent] PendingIntent{cb78987: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.285  3549  4420 V AlarmManager:  remove PendingIntent] PendingIntent{b76e0b4: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.295  3549  4170 V AlarmManager:  remove PendingIntent] PendingIntent{94cb4dd: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.305  3549  4066 V AlarmManager:  remove PendingIntent] PendingIntent{4b28852: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.315  3549  4931 V AlarmManager:  remove PendingIntent] PendingIntent{6f93723: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.325  3549  4435 V AlarmManager:  remove PendingIntent] PendingIntent{efb5420: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.335  3549  3567 V AlarmManager:  remove PendingIntent] PendingIntent{564c1d9: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.345  3549  3986 V AlarmManager:  remove PendingIntent] PendingIntent{5ccd79e: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.345 10053 10084 I bt_hwcfg: vendor lib fwcfg completed
05-25 13:51:19.345 10053 10084 I bt_vendor: firmware callback
05-25 13:51:19.345 10053 10084 I bt_hci  : firmware_config_callback
,05-25 13:51:19.345 10053 10091 I bt_btu_task: Bluetooth chip preload is complete
,05-25 13:51:19.345 10053 10091 I         : BTE_InitTraceLevels -- TRC_HCI
05-25 13:51:19.345 10053 10091 I         : BTE_InitTraceLevels -- TRC_L2CAP
05-25 13:51:19.345 10053 10091 I         : BTE_InitTraceLevels -- TRC_RFCOMM
05-25 13:51:19.345 10053 10091 I         : BTE_InitTraceLevels -- TRC_AVDT
05-25 13:51:19.345 10053 10091 I         : BTE_InitTraceLevels -- TRC_AVRC
,05-25 13:51:19.345 10053 10091 I         : BTE_InitTraceLevels -- TRC_A2D
05-25 13:51:19.345 10053 10091 I         : BTE_InitTraceLevels -- TRC_BNEP
05-25 13:51:19.345 10053 10091 I         : BTE_InitTraceLevels -- TRC_BTM
,05-25 13:51:19.345 10053 10091 I         : BTE_InitTraceLevels -- TRC_GAP
05-25 13:51:19.345 10053 10091 I         : BTE_InitTraceLevels -- TRC_PAN
05-25 13:51:19.345 10053 10091 I         : BTE_InitTraceLevels -- TRC_SDP
05-25 13:51:19.345 10053 10091 I         : BTE_InitTraceLevels -- TRC_GATT
05-25 13:51:19.345 10053 10091 I         : BTE_InitTraceLevels -- TRC_SMP
,05-25 13:51:19.345 10053 10091 I         : BTE_InitTraceLevels -- TRC_BTAPP
05-25 13:51:19.345 10053 10091 I         : BTE_InitTraceLevels -- TRC_BTIF
05-25 13:51:19.345 10053 10091 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,05-25 13:51:19.355  3549  3568 V AlarmManager:  remove PendingIntent] PendingIntent{41e227f: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.365  3549  4367 V AlarmManager:  remove PendingIntent] PendingIntent{c91924c: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.375  3549  3838 V AlarmManager:  remove PendingIntent] PendingIntent{756a295: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.385  3549  4432 V AlarmManager:  remove PendingIntent] PendingIntent{9aacfaa: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.395  3549  4286 V AlarmManager:  remove PendingIntent] PendingIntent{7c679b: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.405  3549  4433 V AlarmManager:  remove PendingIntent] PendingIntent{96b8738: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.415  3549  4285 V AlarmManager:  remove PendingIntent] PendingIntent{34bd311: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.425  3549  4430 V AlarmManager:  remove PendingIntent] PendingIntent{1be3c76: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.435  3549  3981 V AlarmManager:  remove PendingIntent] PendingIntent{dafe277: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.445  3549  4420 V AlarmManager:  remove PendingIntent] PendingIntent{9eddee4: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.455  3549  4170 V AlarmManager:  remove PendingIntent] PendingIntent{c898f4d: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.455 10053 10091 W bt_l2cap: l2c_link_processs_ble_num_bufs 15
,05-25 13:51:19.455 10053 10091 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf391e7ad
,05-25 13:51:19.455 10053 10091 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf391e7ad 
05-25 13:51:19.455 10053 10091 E bt_btm  : btm_ble_set_search_if search_if=4
,05-25 13:51:19.465  3549  4066 V AlarmManager:  remove PendingIntent] PendingIntent{2c9aa02: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.475 10053 10071 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 9 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 20 mIsExtendedScanSupported = true mIsDebugLogSupported = false mAobleSupported = 1
,05-25 13:51:19.475  3549  4931 V AlarmManager:  remove PendingIntent] PendingIntent{1362f13: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.485  3549  4435 V AlarmManager:  remove PendingIntent] PendingIntent{21c0550: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.485 10053 10071 E bt_btif : bta_dm_sm_execute e
05-25 13:51:19.485 10053 10071 D bt_hci  : do_postload posting postload work item
,05-25 13:51:19.485  3549  3567 V AlarmManager:  remove PendingIntent] PendingIntent{b6cd349: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
05-25 13:51:19.485 10053 10084 I bt_hci  : event_postload
05-25 13:51:19.485 10053 10071 E bt_btif_sock: btif_sock_init: !vhci_init
,05-25 13:51:19.485 10053 10084 D bt_hwcfg: hw_sco_config
05-25 13:51:19.485 10053 10084 I bt_vendor: sco_config_cb
05-25 13:51:19.485 10053 10071 E bt_btif : ## init_cmd_fd assert ts[h].cmd_fdr == -1 && ts[h].cmd_fdw == -1 failed at line:289 ##
05-25 13:51:19.485 10053 10084 I bt_hci  : sco_config_callback postload finished.
05-25 13:51:19.495 10053 10071 D bt_bte_conf: Device ID record 1 : primary
,05-25 13:51:19.495 10053 10071 D bt_bte_conf:   vendorId            = 0075
05-25 13:51:19.495 10053 10071 D bt_bte_conf:   vendorIdSource      = 0001
05-25 13:51:19.495 10053 10071 D bt_bte_conf:   product             = 0100
05-25 13:51:19.495 10053 10071 D bt_bte_conf:   version             = 0200
05-25 13:51:19.495 10053 10071 D bt_bte_conf:   clientExecutableURL = 
05-25 13:51:19.495 10053 10071 D bt_bte_conf:   serviceDescription  = 
05-25 13:51:19.495 10053 10071 D bt_bte_conf:   documentationURL    = 
05-25 13:51:19.495 10053 10071 D bt_bte_conf: bte_load_did_conf no section named DID2.
05-25 13:51:19.495 10053 10071 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  14 , val : 15
05-25 13:51:19.495 10053 10068 D bt_stack_manager: event_start_up_stack finished
05-25 13:51:19.495 10053 10071 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  15 , val : 8
05-25 13:51:19.495 10053 10071 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  16 , val : 24838
05-25 13:51:19.495 10053 10071 D BluetoothDataManager: UpdateLocalInfo for String is called!!! type : 17, val : BCM4359C0 Hero SWB-B90S eLNA-0044
05-25 13:51:19.495 10053 10071 D BluetoothDataManager: firmwareVersion from Property : bcm4359C0_V0044.0062_semco.hcd
05-25 13:51:19.495 10053 10071 E BluetoothAdapterState: stateChangeCallback : 1
05-25 13:51:19.495 10053 10067 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: ENABLED_READY
05-25 13:51:19.495 10053 10067 D BluetoothAdapterProperties: Setting state to 15
05-25 13:51:19.495 10053 10067 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
05-25 13:51:19.495  3549  4433 V AlarmManager:  remove PendingIntent] PendingIntent{92c644e: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.505 10053 10084 I bt_vendor: low_power_mode_cb
,05-25 13:51:19.505 10053 10067 D BluetoothAdapterService: Bluetooth PBAP supproted is true,
05-25 13:51:19.505 10053 10067 D BluetoothAdapterService: updateAdapterState state is 15
05-25 13:51:19.505  3549  4430 V AlarmManager:  remove PendingIntent] PendingIntent{caa96f: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
05-25 13:51:19.505 10053 10067 D BluetoothAdapterService: Autoconnection is available 
,05-25 13:51:19.505 10053 10067 D BluetoothAdapterService: updateAdapterState prevState = 14newState = 15
05-25 13:51:19.505 10053 10067 I BluetoothAdapterState: Entering BleOnState
,05-25 13:51:19.515  3549  3619 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
05-25 13:51:19.515  3549  4286 V AlarmManager:  remove PendingIntent] PendingIntent{7265b05: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.515  3549  3619 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,05-25 13:51:19.515 10053 10067 D BluetoothAdapterState: Current state: BLE ON, message: USER_TURN_ON
,05-25 13:51:19.515 10053 10067 D BluetoothAdapterProperties: Setting state to 11
,05-25 13:51:19.515 10053 10067 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
05-25 13:51:19.515 10053 10067 D BluetoothAdapterService: Bluetooth PBAP supproted is true
05-25 13:51:19.515 10053 10067 D BluetoothAdapterService: updateAdapterState state is 11
,05-25 13:51:19.515  3549  3619 D BluetoothManagerService: Turning On/Off, G state: 2, S state: 2, mBLE count: 0, s BLE count: 0
,05-25 13:51:19.515  3549  4367 V AlarmManager:  remove PendingIntent] PendingIntent{5ee775a: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.515 10053 10067 D BluetoothAdapterService: Autoconnection is available 
05-25 13:51:19.525  3549  3549 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
05-25 13:51:19.515 10053 10067 D BluetoothAdapterService: updateAdapterState prevState = 15newState = 11
05-25 13:51:19.525  3549  3549 I InputMethodManagerService: [BT Setting State] State =11
05-25 13:51:19.515 10053 10067 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
,05-25 13:51:19.515 10053 10067 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
05-25 13:51:19.525 10053 10067 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
05-25 13:51:19.525  3949  4133 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,05-25 13:51:19.525  3949  4133 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
05-25 13:51:19.525  4316  4316 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
05-25 13:51:19.525  4782  4782 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
05-25 13:51:19.525  3549  3549 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
,05-25 13:51:19.525  3549  3549 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
05-25 13:51:19.525  3549  3549 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
05-25 13:51:19.525  9180  9180 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
05-25 13:51:19.525  9180  9180 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,05-25 13:51:19.535  9936  9936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:51:19.535  3549  3603 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8826d8b u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{244f13b 9180:com.android.settings/1000}
,05-25 13:51:19.545 10053 10067 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,05-25 13:51:19.545  3949  4213 D BluetoothTile: handleUpdateState :  supported = true, enabled = false, enabling = true, connected = false, connecting = false, mController.getLastDeviceName() = null
,05-25 13:51:19.555 10053 10053 D HeadsetService: Received start request. Starting profile...
,05-25 13:51:19.555  3549  4420 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
05-25 13:51:19.555 10053 10053 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa689ba,
05-25 13:51:19.555  3949  3949 D QSTileView: handleLabelStateChanged() label = Bluetooth cellWidth 272
05-25 13:51:19.555 10053 10053 D HeadsetProvider: make
05-25 13:51:19.555  3549  4367 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8826d8b u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{44442de 4889:com.samsung.android.providers.context/u0a7}
05-25 13:51:19.555 10053 10053 D HeadsetProvider: HeadsetProvider
05-25 13:51:19.555 10053 10053 I HeadsetProvider: clearAllHeadsetSettings(0)
,05-25 13:51:19.565 10053 10053 I BluetoothHeadsetServiceJni: classInitNative: succeeds
05-25 13:51:19.565 10053 10053 D HeadsetStateMachine: make
,05-25 13:51:19.565 10053 10053 E HeadsetStateMachine: # of Max HF connection is 3
,05-25 13:51:19.565 10053 10067 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,05-25 13:51:19.575  3549  3568 V AlarmManager:  remove PendingIntent] PendingIntent{8caf26: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.575  3549  4433 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8826d8b u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f3ae3d9 4287:com.google.android.gms.persistent/u0a19}
,05-25 13:51:19.575  4287  4287 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
,05-25 13:51:19.595 10053 10067 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,05-25 13:51:19.605  3549  4433 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8826d8b u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a2429dc 8769:com.sec.android.app.shealth:remote/u0a36}
,05-25 13:51:19.605 10053 10053 I bt_bluedroid: get_profile_interface handsfree
,05-25 13:51:19.615  9936 10036 D BluetoothAdapter: enable()
,05-25 13:51:19.615 10053 10067 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
05-25 13:51:19.615  3549  4420 V AlarmManager:  remove PendingIntent] PendingIntent{9a07cfe: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.625  3549  4433 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8826d8b u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{244f13b 9180:com.android.settings/1000}
,05-25 13:51:19.625  9180  9180 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
05-25 13:51:19.625  9180  9180 D BluetoothStatusReceiver: AdapterStateChanged :: state = 11
,05-25 13:51:19.635  3549  4285 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8826d8b u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f8c914 10053:com.android.bluetooth/1002}
,05-25 13:51:19.655 10053 10067 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,05-25 13:51:19.665  3549  3838 W ActivityManager: Permission Denial: getCurrentUser() from pid=9936, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
,05-25 13:51:19.665  3549  3838 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
05-25 13:51:19.665  3549  3838 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9936, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
05-25 13:51:19.665  3549  3838 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-25 13:51:19.665  3549  3838 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2852)
05-25 13:51:19.665  3549  3838 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2842)
05-25 13:51:19.665  3549  3838 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.setBtEnableFlag(BluetoothManagerService.java:1222)
05-25 13:51:19.665  3549  3838 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:254)
05-25 13:51:19.665  3549  3838 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:453)
05-25 13:51:19.665  3549  3838 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,05-25 13:51:19.665  3549  3838 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,05-25 13:51:19.665  3549  3838 D SettingsProvider: isChangeAllowed() : name = bluetooth_on
,05-25 13:51:19.675 10053 10067 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
,05-25 13:51:19.675  3549  4931 V AlarmManager:  remove PendingIntent] PendingIntent{94d0f75: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.675 10053 10053 I DualScoManager: Instantiating Dual Sco Manager
,05-25 13:51:19.675 10053 10053 I DualScoManager: Set HeadsetServiceHelper
,05-25 13:51:19.675 10053 10053 D BluetoothAtMessage: createCMTIContentObservers
,05-25 13:51:19.685 10053 10067 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,05-25 13:51:19.685 10053 10067 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
05-25 13:51:19.685 10053 10067 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
05-25 13:51:19.685 10053 10067 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
05-25 13:51:19.685 10053 10067 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.bleaudio.BleAudioService
,05-25 13:51:19.695 10053 10067 I BluetoothAdapterState: Entering PendingCommandState
,05-25 13:51:19.695 10053 10067 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BLE_TURN_ON
05-25 13:51:19.695  3549  3986 V AlarmManager:  remove PendingIntent] PendingIntent{dfb0198: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.695 10053 10067 E BluetoothAdapterState: Don't defer BLE_TURN_ON request.
,05-25 13:51:19.705  3549  4170 V AlarmManager:  remove PendingIntent] PendingIntent{1ec2df1: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.705  3549  3567 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-25 13:51:19.705  3549  4286 V AlarmManager:  remove PendingIntent] PendingIntent{f52dd6: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
05-25 13:51:19.705  3549  3567 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:51:19.705  3549  3567 D BatteryService: online:4, current avg:66, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:32
05-25 13:51:19.705  3549  3549 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:51:19.705  3549  3549 I MotionRecognitionService: Plugged
05-25 13:51:19.705  3549  3549 D MotionRecognitionService:   cableConnection= 1
05-25 13:51:19.705 10053 10053 D HeadsetProvider: Created cursor android.database.sqlite.SQLiteCursor@83363c
05-25 13:51:19.705  3549  3549 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:51:19.705  3549  3549 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:51:19.705 10053 10053 D HeadsetProvider: setHeadsetDB - Can't find 300 for 44:78:3E:94:4A:XX
,05-25 13:51:19.715  3549  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:51:19.715  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
05-25 13:51:19.715  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
,05-25 13:51:19.715  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:51:19.715 10053 10053 I HeadsetProvider: setHeadsetDB - 44:78:3E:94:4A:XX, 300, 1, true
,05-25 13:51:19.725  4905  4905 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:51:19.725  4905  4905 D BatteryMonitor: new battery level: 100
,05-25 13:51:19.735 10053 10053 D HeadsetProvider: Created cursor android.database.sqlite.SQLiteCursor@ae9904b
,05-25 13:51:19.735  3549  4170 V AlarmManager:  remove PendingIntent] PendingIntent{5dfe857: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
05-25 13:51:19.735 10053 10053 D HeadsetProvider: setHeadsetDB - Can't find 400 for 44:78:3E:94:4A:XX
,05-25 13:51:19.735  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:19.735  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:19.745  3549  3567 V AlarmManager:  remove PendingIntent] PendingIntent{36a9f44: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.745 10053 10053 I HeadsetProvider: setHeadsetDB - 44:78:3E:94:4A:XX, 400, 1, true
,05-25 13:51:19.745 10053 10095 D HeadsetStateMachine: Enter Disconnected: -2, size: 0/0
,05-25 13:51:19.745 10053 10053 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Message sending
05-25 13:51:19.745 10053 10053 E HeadsetService: notifyProfileServiceStateChanged
,05-25 13:51:19.755  3549  3838 V AlarmManager:  remove PendingIntent] PendingIntent{9146bb0: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.755 10053 10053 D A2dpService: Received start request. Starting profile...
,05-25 13:51:19.755 10053 10053 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa689ba
05-25 13:51:19.755 10053 10095 D HeadsetStateMachine: Clear mHeadsetBrsf
05-25 13:51:19.755 10053 10095 D HeadsetStateMachine: map size, before remove : 0
,05-25 13:51:19.755 10053 10095 D HeadsetStateMachine: map size, after remove: 0
05-25 13:51:19.755 10053 10053 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,05-25 13:51:19.755 10053 10053 I bt_bluedroid: get_profile_interface avrcp
,05-25 13:51:19.755  3549  4432 V AlarmManager:  remove PendingIntent] PendingIntent{a1aa29: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.765 10053 10053 I Avrcp   : No of Audio players :: 1
,05-25 13:51:19.765 10053 10053 I Avrcp   : App Package name is GM
05-25 13:51:19.765  3549  3568 V AlarmManager:  remove PendingIntent] PendingIntent{f81bfe5: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.765  3549  4367 V AlarmManager:  remove PendingIntent] PendingIntent{2d4aaba: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.765 10053 10053 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in com.android.bluetooth rsrc of package com.google.android.music
,05-25 13:51:19.775  3549  4432 V AlarmManager:  remove PendingIntent] PendingIntent{66d8d6b: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.775 10053 10053 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:51:19.775  3549  4420 V AlarmManager:  remove PendingIntent] PendingIntent{97e00c8: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.775 10053 10053 V Avrcp   : MediaPlayerInfo: mPlayerId=1
,05-25 13:51:19.775 10053 10053 I Avrcp   : No of Video players :: 2
,05-25 13:51:19.775 10053 10053 I Avrcp   : Video App Package name is others
05-25 13:51:19.775  3549  4170 V AlarmManager:  remove PendingIntent] PendingIntent{1937561: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.775 10053 10053 W ResourcesManager: getTopLevelResources: /system/app/Photos/Photos.apk / 1.0 running in com.android.bluetooth rsrc of package com.google.android.apps.photos
,05-25 13:51:19.785  3549  4432 V AlarmManager:  remove PendingIntent] PendingIntent{392b886: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.785  3549  3838 V AlarmManager:  remove PendingIntent] PendingIntent{7559547: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.785 10053 10053 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:51:19.785 10053 10053 V Avrcp   : MediaPlayerInfo: mPlayerId=2
05-25 13:51:19.785 10053 10053 I Avrcp   : Video App Package name is VP
,05-25 13:51:19.785 10053 10053 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungVideoPlayer/SamsungVideoPlayer.apk / 1.0 running in com.android.bluetooth rsrc of package com.samsung.android.video
,05-25 13:51:19.785  3549  4170 V AlarmManager:  remove PendingIntent] PendingIntent{ed66174: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.785 10053 10053 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:51:19.795 10053 10053 V Avrcp   : MediaPlayerInfo: mPlayerId=3
05-25 13:51:19.795 10053 10053 I Avrcp   : Add tempPlayer
,05-25 13:51:19.795 10053 10053 V Avrcp   : MediaPlayerInfo: mPlayerId=4
05-25 13:51:19.795 10053 10053 V Avrcp   : no_of_players : 4
05-25 13:51:19.795 10053 10053 I Avrcp   : Total no of players: 4
05-25 13:51:19.795 10053 10053 V Avrcp   : Samsung player is the 1st player
05-25 13:51:19.795 10053 10053 D Avrcp   : Compose Browsing Service Candidate
,05-25 13:51:19.795  3549  4285 V AlarmManager:  remove PendingIntent] PendingIntent{6b1069d: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
05-25 13:51:19.795 10053 10053 D Avrcp   : ResolveInfo info ResolveInfo{1210d4 com.google.android.music/.browse.MediaBrowserService m=0x108000}
,05-25 13:51:19.795 10053 10053 D Avrcp   : Initialize Media Controller
,05-25 13:51:19.795 10053 10053 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,05-25 13:51:19.795 10053 10053 E Avrcp   : getActiveSessions
,05-25 13:51:19.795 10053 10053 D Avrcp   : pick active media Controller
05-25 13:51:19.795 10053 10053 D Avrcp   : Get the active Media Controller 
05-25 13:51:19.795 10053 10053 I BluetoothA2dpServiceJni: classInitNative: succeeds
05-25 13:51:19.795  3549  4430 V AlarmManager:  remove PendingIntent] PendingIntent{3d1d712: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
05-25 13:51:19.795 10053 10053 D A2dpStateMachine: make
,05-25 13:51:19.795 10053 10053 I bt_bluedroid: get_profile_interface a2dp
,05-25 13:51:19.795 10053 10053 E bt_btif : warning : media task started media_task_refcnt 1 
,05-25 13:51:19.805  3549  3568 V AlarmManager:  remove PendingIntent] PendingIntent{9cc3ee3: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.805 10053 10098 D A2dpStateMachine: Enter Disconnected: -2
,05-25 13:51:19.805 10053 10053 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Message sending
05-25 13:51:19.805 10053 10053 E A2dpService: notifyProfileServiceStateChanged
,05-25 13:51:19.805  3549  4285 V AlarmManager:  remove PendingIntent] PendingIntent{379e63f: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.805  3549  3838 V AlarmManager:  remove PendingIntent] PendingIntent{2c86b0c: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
05-25 13:51:19.805 10053 10053 I BluetoothHidServiceJni: classInitNative: succeeds
,05-25 13:51:19.815 10053 10053 D HidService: Received start request. Starting profile...
05-25 13:51:19.815 10053 10053 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa689ba
05-25 13:51:19.815 10053 10053 I bt_bluedroid: get_profile_interface hidhost
05-25 13:51:19.815 10053 10053 D HidService: setHidService(): set to: null
05-25 13:51:19.815 10053 10053 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, Message sending
05-25 13:51:19.815 10053 10053 E HidService: notifyProfileServiceStateChanged
05-25 13:51:19.815 10053 10053 D HeadsetStateMachine: Try to query the phonestate on bind
05-25 13:51:19.815  3549  4170 I Telecom : BluetoothPhoneService: queryPhoneState
,05-25 13:51:19.815  3549  4170 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState : true
05-25 13:51:19.815 10053 10053 D HeadsetStateMachine: Proxy object connected
,05-25 13:51:19.815 10053 10053 I BluetoothHealthServiceJni: classInitNative: succeeds
05-25 13:51:19.815  3549  3567 V AlarmManager:  remove PendingIntent] PendingIntent{73b6c55: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.815 10053 10053 D HealthService: Received start request. Starting profile...
05-25 13:51:19.815 10053 10053 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa689ba
,05-25 13:51:19.815 10053 10053 I bt_bluedroid: get_profile_interface health
,05-25 13:51:19.815 10053 10053 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, Message sending
05-25 13:51:19.815 10053 10053 E HealthService: notifyProfileServiceStateChanged
05-25 13:51:19.815  3549  4435 V AlarmManager:  remove PendingIntent] PendingIntent{e0d366a: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.815 10053 10053 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
05-25 13:51:19.815 10053 10095 D HeadsetStateMachine: Disconnected process message: 11, size: 0
,05-25 13:51:19.815 10053 10095 E HeadsetStateMachine: Unknown message: 11
05-25 13:51:19.815 10053 10053 I BluetoothPanServiceJni: classInitNative(L113): succeeds
,05-25 13:51:19.825 10053 10053 D PanService: Received start request. Starting profile...
05-25 13:51:19.825 10053 10053 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa689ba
05-25 13:51:19.825 10053 10053 D BluetoothPanServiceJni: initializeNative(L118): pan
05-25 13:51:19.825 10053 10053 I bt_bluedroid: get_profile_interface pan
,05-25 13:51:19.825 10053 10053 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, Message sending
05-25 13:51:19.825 10053 10053 E PanService: notifyProfileServiceStateChanged
05-25 13:51:19.825 10053 10053 D HeadsetPhoneState: sendDeviceDataStateChanged
,05-25 13:51:19.825 10053 10053 D HeadsetPhoneState: Signal level : previous=0 curr=0
05-25 13:51:19.825 10053 10095 D HeadsetStateMachine: Disconnected process message: 19, size: 0
05-25 13:51:19.825 10053 10095 E HeadsetStateMachine: Unknown message: 19
,05-25 13:51:19.825 10053 10053 D BluetoothMapService: Received start request. Starting profile...
,05-25 13:51:19.825 10053 10053 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa689ba
,05-25 13:51:19.825  3549  4430 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8826d8b u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a53ad79 7081:com.google.android.apps.maps/u0a119}
,05-25 13:51:19.835 10053 10053 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Message sending
,05-25 13:51:19.835 10053 10053 E BluetoothMapService: notifyProfileServiceStateChanged
05-25 13:51:19.835 10053 10053 V SapService: SapBinder()
,05-25 13:51:19.835 10053 10053 D SapService: Received start request. Starting profile...
,05-25 13:51:19.835 10053 10053 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa689ba
05-25 13:51:19.835 10053 10053 V SapService: start()
,05-25 13:51:19.835 10053 10053 D SapService: Disable sap : false
,05-25 13:51:19.845  3549  4420 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4c85e37 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{44442de 4889:com.samsung.android.providers.context/u0a7}
,05-25 13:51:19.845 10053 10053 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=12, Message sending
,05-25 13:51:19.845 10053 10053 E SapService: notifyProfileServiceStateChanged
,05-25 13:51:19.855  3549  4286 V AlarmManager:  remove PendingIntent] PendingIntent{5baa6d3: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.865  3549  4066 V AlarmManager:  remove PendingIntent] PendingIntent{97f8210: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.865  3549  4435 V AlarmManager:  remove PendingIntent] PendingIntent{d4b7109: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.865  3549  4433 V AlarmManager:  remove PendingIntent] PendingIntent{b860f0e: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.875 10053 10053 D BleAudioService: Received start request. Starting profile...
,05-25 13:51:19.875 10053 10053 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa689ba
05-25 13:51:19.875 10053 10053 E DualScoManager: Dual Sco Manager already instantiated
05-25 13:51:19.875 10053 10053 I BtBleAudio.JNI: classInitNative(L304): succeeds
,05-25 13:51:19.875 10053 10053 D BleAudioStateMachine: make
05-25 13:51:19.875  3549  4367 V AlarmManager:  remove PendingIntent] PendingIntent{37edd2f: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.875 10053 10053 I BleAudioStateMachine: Constructor Of BleAudioStateMachine
,05-25 13:51:19.875 10053 10053 D BtBleAudio.JNI: initializeNative(L309): ble audio jni initializeNative: 0
,05-25 13:51:19.875 10053 10053 I bt_bluedroid: get_profile_interface bleaudio_source
05-25 13:51:19.875 10053 10053 D BleAudioStateMachine: make
05-25 13:51:19.875  3549  3981 V AlarmManager:  remove PendingIntent] PendingIntent{5c2af3c: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
05-25 13:51:19.875 10053 10103 E BleAudioStateMachine_L: Enter Disconnected: -2
,05-25 13:51:19.875 10053 10053 I BleAudioStateMachine: Constructor Of BleAudioStateMachine
,05-25 13:51:19.875 10053 10053 D BtBleAudio.JNI: initializeNative(L309): ble audio jni initializeNative: 1
05-25 13:51:19.875 10053 10053 V BleAudioService: [registerCallStateListener]
05-25 13:51:19.875 10053 10104 E BleAudioStateMachine_R: Enter Disconnected: -2
,05-25 13:51:19.885  3549  4432 V AlarmManager:  remove PendingIntent] PendingIntent{9b114c5: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.885 10053 10053 V BleAudioService: [registerAobleStateChangeListener]
,05-25 13:51:19.885  3549  4170 V AlarmManager:  remove PendingIntent] PendingIntent{7133841: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.885 10053 10053 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.broadcom.bt.service.bleaudio.BleAudioService, state=12, Message sending
05-25 13:51:19.885 10053 10053 E BleAudioService: notifyProfileServiceStateChanged
,05-25 13:51:19.885 10053 10053 E BluetoothAdapterService: handleMessage() - Message: 1
05-25 13:51:19.885 10053 10053 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Before synchronized
,05-25 13:51:19.885 10053 10053 V BluetoothAdapterState: isTurningOff()=false
,05-25 13:51:19.885 10053 10053 V BluetoothAdapterState: isTurningOn()=true
05-25 13:51:19.885  3549  4367 V AlarmManager:  remove PendingIntent] PendingIntent{198f1e6: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.885 10053 10053 V BluetoothAdapterState: isBleTurningOn()=false
05-25 13:51:19.885 10053 10053 V BluetoothAdapterState: isBleTurningOff()=false
05-25 13:51:19.885 10053 10053 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-25 13:51:19.895 10053 10095 D HeadsetStateMachine: Disconnected process message: 10, size: 0
05-25 13:51:19.895 10053 10053 E BluetoothAdapterService: handleMessage() - Message: 1
05-25 13:51:19.895 10053 10053 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Before synchronized
,05-25 13:51:19.895 10053 10095 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
05-25 13:51:19.895 10053 10095 D HeadsetStateMachine: Disconnected process message: 11, size: 0
05-25 13:51:19.895 10053 10095 E HeadsetStateMachine: Unknown message: 11
05-25 13:51:19.895 10053 10053 V BluetoothAdapterState: isTurningOff()=false
05-25 13:51:19.895 10053 10053 V BluetoothAdapterState: isTurningOn()=true
05-25 13:51:19.895 10053 10053 V BluetoothAdapterState: isBleTurningOn()=false
05-25 13:51:19.895 10053 10053 V BluetoothAdapterState: isBleTurningOff()=false
05-25 13:51:19.895 10053 10053 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,05-25 13:51:19.895 10053 10053 D HeadsetPhoneState: sendDeviceDataStateChanged
05-25 13:51:19.895 10053 10095 D HeadsetStateMachine: Disconnected process message: 11, size: 0
05-25 13:51:19.895 10053 10095 E HeadsetStateMachine: Unknown message: 11
05-25 13:51:19.895 10053 10053 D HeadsetPhoneState: Signal level : previous=0 curr=0
05-25 13:51:19.895 10053 10095 D HeadsetStateMachine: Disconnected process message: 19, size: 0
05-25 13:51:19.895 10053 10095 E HeadsetStateMachine: Unknown message: 19
,05-25 13:51:19.895 10053 10053 E BluetoothAdapterService: handleMessage() - Message: 1
05-25 13:51:19.895 10053 10053 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, Before synchronized
05-25 13:51:19.895 10053 10053 V BluetoothAdapterState: isTurningOff()=false
05-25 13:51:19.895 10053 10053 V BluetoothAdapterState: isTurningOn()=true
05-25 13:51:19.895 10053 10053 V BluetoothAdapterState: isBleTurningOn()=false
05-25 13:51:19.895 10053 10053 V BluetoothAdapterState: isBleTurningOff()=false
05-25 13:51:19.895 10053 10053 D BluetoothAdapterService: HID Host service started
,05-25 13:51:19.895  3549  4435 V AlarmManager:  remove PendingIntent] PendingIntent{5b74327: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.895  3949  4133 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CONNECTION_HID_HOST
05-25 13:51:19.895  3949  4133 W LocalBluetoothProfileManager: updateLocalProfiles :: A2DP profile was previously added but the UUID is now missing.
,05-25 13:51:19.895  3949  4133 W LocalBluetoothProfileManager: updateLocalProfiles :: HEADSET profile was previously added but the UUID is now missing.
05-25 13:51:19.895  3949  4133 W LocalBluetoothProfileManager: updateLocalProfiles :: MAP profile was previously added but the UUID is now missing.
05-25 13:51:19.895  3949  4133 W LocalBluetoothProfileManager: updateLocalProfiles :: PBAP profile was previously added but the UUID is now missing.
,05-25 13:51:19.895  3949  4133 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
05-25 13:51:19.895  3949  4133 D HidProfile: mService is null. need to get proxy again!!
05-25 13:51:19.895  9180  9180 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CONNECTION_HID_HOST
,05-25 13:51:19.905  9180  9180 D BluetoothMap: Create BluetoothMap proxy object
,05-25 13:51:19.905 10053 10053 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,05-25 13:51:19.905 10053 10053 E BluetoothAdapterService: handleMessage() - Message: 1
05-25 13:51:19.905 10053 10053 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, Before synchronized
,05-25 13:51:19.905 10053 10053 V BluetoothAdapterState: isTurningOff()=false
05-25 13:51:19.905 10053 10053 V BluetoothAdapterState: isTurningOn()=true
,05-25 13:51:19.905 10053 10053 V BluetoothAdapterState: isBleTurningOn()=false
05-25 13:51:19.905 10053 10053 V BluetoothAdapterState: isBleTurningOff()=false
05-25 13:51:19.905 10053 10053 E BluetoothAdapterService: handleMessage() - Message: 1
05-25 13:51:19.905 10053 10053 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, Before synchronized
,05-25 13:51:19.905  3549  3986 V AlarmManager:  remove PendingIntent] PendingIntent{f24672: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.905 10053 10053 V BluetoothAdapterState: isTurningOff()=false
05-25 13:51:19.905 10053 10053 V BluetoothAdapterState: isTurningOn()=true
05-25 13:51:19.905 10053 10053 V BluetoothAdapterState: isBleTurningOn()=false
05-25 13:51:19.905 10053 10053 V BluetoothAdapterState: isBleTurningOff()=false
05-25 13:51:19.905 10053 10053 E BluetoothAdapterService: handleMessage() - Message: 1
05-25 13:51:19.905 10053 10053 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Before synchronized
,05-25 13:51:19.905 10053 10053 V BluetoothAdapterState: isTurningOff()=false
,05-25 13:51:19.905 10053 10053 V BluetoothAdapterState: isTurningOn()=true
05-25 13:51:19.905 10053 10053 V BluetoothAdapterState: isBleTurningOn()=false
05-25 13:51:19.905 10053 10053 V BluetoothAdapterState: isBleTurningOff()=false
05-25 13:51:19.905 10053 10053 E BluetoothAdapterService: handleMessage() - Message: 1
05-25 13:51:19.905 10053 10053 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=12, Before synchronized
,05-25 13:51:19.915 10053 10053 V BluetoothAdapterState: isTurningOff()=false
,05-25 13:51:19.915 10053 10053 V BluetoothAdapterState: isTurningOn()=true
05-25 13:51:19.915 10053 10053 V BluetoothAdapterState: isBleTurningOn()=false
05-25 13:51:19.915 10053 10053 V BluetoothAdapterState: isBleTurningOff()=false
05-25 13:51:19.915 10053 10053 D BleAudioService: [onCallStateChanged] ENTER -- State: (0)
05-25 13:51:19.915 10053 10053 D BleAudioService: [onCallStateChanged] No devices in connected state
05-25 13:51:19.915 10053 10053 D BleAudioService: [onCallStateChanged][PHONECALL STATE Changed]: EXIT
05-25 13:51:19.915 10053 10053 E BluetoothAdapterService: handleMessage() - Message: 1
,05-25 13:51:19.915 10053 10053 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.bleaudio.BleAudioService, state=12, Before synchronized
05-25 13:51:19.915  3549  3981 V AlarmManager:  remove PendingIntent] PendingIntent{a1a57be: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.915 10053 10053 V BluetoothAdapterState: isTurningOff()=false
,05-25 13:51:19.915 10053 10053 V BluetoothAdapterState: isTurningOn()=true
05-25 13:51:19.915 10053 10053 V BluetoothAdapterState: isBleTurningOn()=false
05-25 13:51:19.915 10053 10053 V BluetoothAdapterState: isBleTurningOff()=false
05-25 13:51:19.915 10053 10067 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_STARTED
,05-25 13:51:19.915  9180  9180 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
,05-25 13:51:19.925 10053 10067 E BluetoothServiceJni: enableBrEdrNative:
,05-25 13:51:19.925 10053 10067 I bt_bluedroid: enable_bredr
,05-25 13:51:19.925  3949  3949 D BluetoothInputDevice: Proxy object connected
05-25 13:51:19.925  3949  3949 D HidProfile: Bluetooth service connected
,05-25 13:51:19.925 10053 10071 I bt_bta_hh: BTA_HhEnable sec_mask:0x24 p_cback:0xf38eff29
05-25 13:51:19.925  3949  4133 W LocalBluetoothProfileManager: updateLocalProfiles :: BleAudio profile was created already 
05-25 13:51:19.925 10053 10071 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x100048
05-25 13:51:19.925 10053 10071 D BluetoothAdapterProperties: Address is:44:78:3E:94:4A:3E
05-25 13:51:19.925 10053 10071 E BluetoothServiceJni: populateRssiValuesNative
05-25 13:51:19.925 10053 10071 I bt_bluedroid: getModelRssiValues
05-25 13:51:19.925 10053 10071 E BluetoothServiceJni: model_rssi_values_callback: low = -75, mid = -65, high = 127
05-25 13:51:19.925 10053 10091 D CODEC_IF: codec_if_open: opening libbt-codec_aptx.so...
05-25 13:51:19.925 10053 10071 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -75,-65,127
,05-25 13:51:19.935  9180  9180 D LocalBluetoothProfileManager: Adding local BleAudio profile
,05-25 13:51:19.935  3549  3549 D SettingsProvider: isChangeAllowed() : name = bluetooth_name
05-25 13:51:19.935 10053 10071 D BluetoothAdapterProperties: Name is: Samsung Galaxy S7
,05-25 13:51:19.935  9180  9180 D BluetoothLeAudio: getProfileProxy()
,05-25 13:51:19.935 10053 10091 D CODEC_IF_MOD: codec_open: codec_open
05-25 13:51:19.935 10053 10071 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
05-25 13:51:19.935 10053 10071 D BluetoothAdapterProperties: Scan Mode:20
05-25 13:51:19.935 10053 10091 D CODEC_IF_MOD: codec_open: apt-x encoder initialized successfully
05-25 13:51:19.935 10053 10091 D CODEC_IF_MOD: codec_open:    version : 1.0.1.0
05-25 13:51:19.935 10053 10091 D CODEC_IF_MOD: codec_open:    build : Android_JB_4.2.2
05-25 13:51:19.935 10053 10071 D BluetoothAdapterProperties: Discoverable Timeout:-1
05-25 13:51:19.935 10053 10091 D CODEC_IF: codec_if_open: codec module opened (v0.1
05-25 13:51:19.935 10053 10091 D CODEC_IF: codec_if_close: codec_if_close hdl -288649212
05-25 13:51:19.935 10053 10091 D CODEC_IF_MOD: codec_close: codec_close
05-25 13:51:19.935 10053 10091 D CODEC_IF_MOD: codec_close: freed apt-x encoder
05-25 13:51:19.935 10053 10091 D         : Codec ==> check 96kHz mode : check_sshd_encoder_available:332
05-25 13:51:19.935 10053 10071 E bt_btif : btif_handle_bluetooth_enable_evt
05-25 13:51:19.935 10053 10091 D CODEC_IF: codec_if_open: opening libbt-codec_sshd.so...
05-25 13:51:19.935 10053 10071 E bt_btif : ANT+ socket does not initialize.
,05-25 13:51:19.935 10053 10071 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
05-25 13:51:19.935  3549  4433 V AlarmManager:  remove PendingIntent] PendingIntent{df7a096: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.945  9936  9936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
05-25 13:51:19.945 10053 10091 D CODEC_IF_SSHD: codec_open: codec_open
05-25 13:51:19.945 10053 10091 D CODEC_IF_SSHD: Codec ==> pcm_info.sampling_freq : 96000
05-25 13:51:19.945 10053 10091 D CODEC_IF_SSHD: codec_open: SSHD encoder initialized successfully
05-25 13:51:19.945 10053 10091 D CODEC_IF: codec_if_open: codec module opened (v0.1
05-25 13:51:19.945 10053 10091 D CODEC_IF: codec_if_close: codec_if_close hdl -582099584
05-25 13:51:19.945 10053 10091 D CODEC_IF_SSHD: codec_close: codec_close
05-25 13:51:19.945  9180  9180 D BluetoothLeAudio: Success to bind to IBluetoothLeAudio with Intent { act=com.broadcom.bt.service.bleaudio.IBluetoothLeAudio cmp=com.android.bluetooth/com.broadcom.bt.service.bleaudio.BleAudioService VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
05-25 13:51:19.945 10053 10091 D         : Codec ==> copy capability info [bta_av_co_audio_init:559]
05-25 13:51:19.945 10053 10091 D CODEC_IF: codec_if_open: opening libbt-codec_aptx.so...
05-25 13:51:19.945 10053 10091 D CODEC_IF_MOD: codec_open: codec_open
05-25 13:51:19.945 10053 10091 D CODEC_IF_MOD: codec_open: apt-x encoder initialized successfully
05-25 13:51:19.945 10053 10091 D CODEC_IF_MOD: codec_open:    version : 1.0.1.0
05-25 13:51:19.945 10053 10091 D CODEC_IF_MOD: codec_open:    build : Android_JB_4.2.2
05-25 13:51:19.945 10053 10091 D CODEC_IF: codec_if_open: codec module opened (v0.1
05-25 13:51:19.945 10053 10091 D CODEC_IF: codec_if_close: codec_if_close hdl -288649212
05-25 13:51:19.945 10053 10091 D CODEC_IF_MOD: codec_close: codec_close
05-25 13:51:19.945 10053 10091 D CODEC_IF_MOD: codec_close: freed apt-x encoder
05-25 13:51:19.945 10053 10091 D         : Codec ==> check 96kHz mode : check_sshd_encoder_available:332
05-25 13:51:19.945 10053 10091 D CODEC_IF: codec_if_open: opening libbt-codec_sshd.so...
05-25 13:51:19.945 10053 10091 D CODEC_IF_SSHD: codec_open: codec_open
05-25 13:51:19.945 10053 10091 D CODEC_IF_SSHD: Codec ==> pcm_info.sampling_freq : 96000
05-25 13:51:19.945 10053 10091 D CODEC_IF_SSHD: codec_open: SSHD encoder initialized successfully
05-25 13:51:19.945 10053 10091 D CODEC_IF: codec_if_open: codec module opened (v0.1
05-25 13:51:19.945 10053 10091 D CODEC_IF: codec_if_close: codec_if_close hdl -582099584
05-25 13:51:19.945 10053 10091 D CODEC_IF_SSHD: codec_close: codec_close
05-25 13:51:19.945 10053 10091 D         : Codec ==> copy capability info [bta_av_co_audio_init:559]
05-25 13:51:19.945  9180  9180 D BluetoothMap: Proxy object connected
05-25 13:51:19.945  9180  9180 D MapProfile: Bluetooth service connected
05-25 13:51:19.945  9180  9180 D BluetoothMap: getConnectedDevices()
05-25 13:51:19.945 10053 10071 D IOP_DB_BT: db_open: db_open : handle 4085719056l, read 18483 bytes onto local cache
05-25 13:51:19.945 10053 10071 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
05-25 13:51:19.945 10053 10071 D IOP_DB_BT: db_query: result 1
05-25 13:51:19.945 10053 10071 I         : iop_db_open: iop_db_open status 0
05-25 13:51:19.955 10053 10071 E BluetoothAdapterState: stateChangeCallback : 17
05-25 13:51:19.955 10053 10071 E bt_btif : no av cb found, event:0, BTA_AV_ENABLE_EVT ignored!
05-25 13:51:19.955 10053 10071 E bt_btif : btif_sm_dispatch : Invalid handle
05-25 13:51:19.955 10053 10071 E bt_btif : bta_av_co_get_peer peer index out of bounds:255
05-25 13:51:19.955 10053 10071 E bt_btif : bta_av_co_audio_peer_init No active peer with this handle 0x0
05-25 13:51:19.955 10053 10071 E bt_btif : no av control block available at state:3
05-25 13:51:19.955 10053 10071 E bt_btif : no av control block available at state:3
05-25 13:51:19.955  3549  4432 V AlarmManager:  remove PendingIntent] PendingIntent{2754870: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
05-25 13:51:19.955 10053 10071 E bt_btif : no av control block available at state:2
05-25 13:51:19.955 10053 10071 E bt_btif : ,warning : no command pending, ignore ack
05-25 13:51:19.955 10053 10071 E bt_btif : no av control block available at state:3
05-25 13:51:19.955 10053 10071 E bt_btif : no av control block available at state:2
05-25 13:51:19.955 10053 10071 W bt_btif : btif_av_state_idle_handler : unhandled event:BTA_AV_REGISTER_EVT
05-25 13:51:19.955 10053 10071 E bt_btif : btif_sm_dispatch : Invalid handle
05-25 13:51:19.955 10053 10071 E bt_btif : bta_av_co_get_peer peer index out of bounds:255
05-25 13:51:19.955 10053 10071 E bt_btif : bta_av_co_audio_peer_init No active peer with this handle 0x0
05-25 13:51:19.955 10053 10071 E bt_btif : no av control block available at state:3
05-25 13:51:19.955 10053 10071 E bt_btif : no av control block available at state:3
05-25 13:51:19.955 10053 10071 E bt_btif : no av control block available at state:2
05-25 13:51:19.955 10053 10071 E bt_btif : warning : no command pending, ignore ack
05-25 13:51:19.955 10053 10071 E bt_btif : no av control block available at state:3
05-25 13:51:19.955 10053 10071 E bt_btif : no av control block available at state:2
05-25 13:51:19.955 10053 10071 W bt_btif : btif_av_state_idle_handler : unhandled event:BTA_AV_REGISTER_EVT
05-25 13:51:19.955 10053 10071 E bt_btif : btif_sm_dispatch : Invalid handle
05-25 13:51:19.955 10053 10067 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_NATIVE_STARTED
05-25 13:51:19.955 10053 10071 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
05-25 13:51:19.955 10053 10067 D BluetoothAdapterProperties: ScanMode =  20
05-25 13:51:19.955 10053 10067 D BluetoothAdapterProperties: State =  11
05-25 13:51:19.955  9180  9180 D BluetoothMap: Bluetooth is Not enabled
05-25 13:51:19.955  9180  9180 D BluetoothInputDevice: Proxy object connected
05-25 13:51:19.955  9180  9180 D HidProfile: Bluetooth service connected
05-25 13:51:19.955  3549  4430 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
05-25 13:51:19.965  9180  9180 D BluetoothLeAudio: Proxy object connected
05-25 13:51:19.965  3549  4170 D SecContentProvider: insert(), uri = 2
05-25 13:51:19.965  9180  9180 D BleAudioProfile: Bluetooth service connected
05-25 13:51:19.965  9180  9180 D BluetoothLeAudio: getConnectedDevices()
05-25 13:51:19.965  3549  3838 V AlarmManager:  remove PendingIntent] PendingIntent{ea227e9: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
05-25 13:51:19.965 10053 10067 D BluetoothAdapterProperties: Setting state to 12
05-25 13:51:19.965 10053 10067 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
05-25 13:51:19.965 10053 10067 D HeadsetService: setBleAudioService(): com.broadcom.bt.service.bleaudio.BleAudioService@f4504a0
05-25 13:51:19.965 10053 10067 D A2dpService: setBleAudioService(): com.broadcom.bt.service.bleaudio.BleAudioService@f4504a0
05-25 13:51:19.965 10053 10067 D BleAudioService: setHeadsetService: setting HeadsetService
05-25 13:51:19.965 10053 10067 D BleAudioService: setA2dpService: setting A2dpService
05-25 13:51:19.965 10053 10067 D BluetoothAdapterService: Bluetooth PBAP supproted is true
05-25 13:51:19.965 10053 10067 D BluetoothAdapterService: updateAdapterState state is 12
05-25 13:51:19.975  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,05-25 13:51:19.975 10053 10071 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,05-25 13:51:19.975 10053 10071 D BluetoothAdapterProperties: Scan Mode:21
05-25 13:51:19.975 10053 10071 D BluetoothAdapterProperties: Discoverable Timeout:-1
,05-25 13:51:19.985  9936  9936 D BluetoothAdapter: STATE_ON
,05-25 13:51:19.985  3549  3986 V AlarmManager:  remove PendingIntent] PendingIntent{3d29f0f: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:19.985  9936  9936 D BluetoothAdapter: STATE_ON
,05-25 13:51:19.985 10053 10067 V BluetoothAdapterService: start opp service
,05-25 13:51:19.985  9936  9936 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,05-25 13:51:19.995  9936  9936 D BluetoothAdapter: STATE_ON
,05-25 13:51:19.995  9936  9936 D BluetoothAdapter: STATE_ON
,05-25 13:51:19.995  9936  9936 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,05-25 13:51:19.995  9180  9180 D BluetoothPbap: Proxy object connected
,05-25 13:51:19.995 10053 10053 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
05-25 13:51:20.005  9180  9180 D PbapServerProfile: Bluetooth service connected
05-25 13:51:20.005 10053 10067 D BluetoothAdapterService: Autoconnection is available 
05-25 13:51:20.005 10053 10067 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
05-25 13:51:20.005 10053 10067 D BluetoothAdapterService: starting service from this receiver
05-25 13:51:20.005  4260  4621 D BluetoothAdapter: onBluetoothStateChange: up=true
,05-25 13:51:20.005  4260  4621 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
05-25 13:51:20.005  3549  4931 V AlarmManager:  remove PendingIntent] PendingIntent{e6c59a5: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:20.005 10053 10053 I BluetoothPbapService: Handler(): got msg=1
,05-25 13:51:20.005  3949  3969 D BluetoothInputDevice: onBluetoothStateChange: up=true
,05-25 13:51:20.005  3949  3969 D BluetoothInputDevice: Binding service...
,05-25 13:51:20.015 10053 10067 D BluetoothAdapterService: BT on, init HID DEV count : 0
,05-25 13:51:20.015 10053 10067 I BluetoothAdapterState: Entering OnState
,05-25 13:51:20.015  3549  3568 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,05-25 13:51:20.015  3949  3949 D BluetoothInputDevice: Proxy object connected
,05-25 13:51:20.015  3949  3949 D HidProfile: Bluetooth service connected
,05-25 13:51:20.015  3949  4123 D BluetoothAdapter: onBluetoothStateChange: up=true
,05-25 13:51:20.015  3949  4123 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
05-25 13:51:20.015  8769  8779 D BluetoothAdapter: onBluetoothStateChange: up=true
05-25 13:51:20.015  8769  8779 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
05-25 13:51:20.025  9936  9936 D BluetoothAdapter: STATE_ON
,05-25 13:51:20.025  9180  9192 D BluetoothPbap: onBluetoothStateChange: up=true
,05-25 13:51:20.025  3549  3567 V AlarmManager:  remove PendingIntent] PendingIntent{bedeb21: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:20.025  3949  4541 D BluetoothPbap: onBluetoothStateChange: up=true
,05-25 13:51:20.025  3949  4541 D BluetoothPbap: Binding service...
,05-25 13:51:20.025 10053 10110 V BluetoothPbapService: PBAP Service initSocket try: 0
,05-25 13:51:20.035  3949  3949 D BluetoothPbap: Proxy object connected
05-25 13:51:20.035  3949  3949 D PbapServerProfile: Bluetooth service connected
05-25 13:51:20.035  3549  3986 V AlarmManager:  remove PendingIntent] PendingIntent{e04a234: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:20.035  9936  9936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-25 13:51:20.035  9936  9936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-25 13:51:20.035  9936  9936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-25 13:51:20.035  9936  9936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-25 13:51:20.035  9936  9936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-25 13:51:20.035  9936  9936 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-25 13:51:20.035  9936  9936 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-25 13:51:20.035  9936  9936 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-25 13:51:20.035  9936  9936 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,05-25 13:51:20.035  9180  9191 D BluetoothAdapter: onBluetoothStateChange: up=true
05-25 13:51:20.035  9180  9191 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,05-25 13:51:20.035  3949  3961 D BluetoothA2dp: onBluetoothStateChange: up=true
,05-25 13:51:20.035  3949  3961 D BluetoothA2dp: Binding service...
,05-25 13:51:20.035  3949  3961 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0,
,05-25 13:51:20.045  3549  4170 V AlarmManager:  remove PendingIntent] PendingIntent{99d185d: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:20.045  9936  9936 D BluetoothAdapter: STATE_ON
,05-25 13:51:20.045  3949  3969 D BluetoothInputDevice: onBluetoothStateChange: up=true
,05-25 13:51:20.045 10053 10110 D BluetoothSocket: bindListen(): myUserId = 0
,05-25 13:51:20.045 10053 10110 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
05-25 13:51:20.045 10053 10053 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,05-25 13:51:20.055  9180  9192 D BluetoothInputDevice: onBluetoothStateChange: up=true
,05-25 13:51:20.055 10053 10053 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,05-25 13:51:20.055  3549  4285 V AlarmManager:  remove PendingIntent] PendingIntent{663ada0: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:20.055  3949  4123 D BluetoothLeAudio: onBluetoothStateChange: up=true
,05-25 13:51:20.055  3949  4123 D BluetoothLeAudio: Binding service...
,05-25 13:51:20.055 10053 10110 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,05-25 13:51:20.055  9936  9936 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
05-25 13:51:20.055 10053 10053 V BtOppService: isOwner == true
,05-25 13:51:20.055  3949  3949 D BluetoothLeAudio: Proxy object connected
05-25 13:51:20.055  3949  3949 D BleAudioProfile: Bluetooth service connected
,05-25 13:51:20.055  3949  3949 D BluetoothLeAudio: getConnectedDevices()
05-25 13:51:20.055  3949  4123 D BluetoothLeAudio: Success to bind to IBluetoothLeAudio with Intent { act=com.broadcom.bt.service.bleaudio.IBluetoothLeAudio cmp=com.android.bluetooth/com.broadcom.bt.service.bleaudio.BleAudioService VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
,05-25 13:51:20.065  9180  9191 D BluetoothPan: onBluetoothStateChange on: true
05-25 13:51:20.065  9180  9191 D BluetoothPan: onBluetoothStateChange calling doBind()
05-25 13:51:20.065  3549  4430 V AlarmManager:  remove PendingIntent] PendingIntent{8708d1e: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:20.065 10053 10063 D BluetoothAdapter: onBluetoothStateChange: up=true
,05-25 13:51:20.065 10053 10063 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,05-25 13:51:20.065  4889  4904 D BluetoothA2dp: onBluetoothStateChange: up=true
05-25 13:51:20.065  4889  4904 D BluetoothA2dp: Binding service...
05-25 13:51:20.065  3549  3567 V AlarmManager:  remove PendingIntent] PendingIntent{ddff615: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:20.065  4889  4904 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,05-25 13:51:20.075  9180  9192 D BluetoothSap: onBluetoothStateChange: up=true
,05-25 13:51:20.075  9180  9192 D BluetoothSap: Binding service...
,05-25 13:51:20.075  3549  4420 V AlarmManager:  remove PendingIntent] PendingIntent{6a299f7: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:20.085  4287  4584 D BluetoothAdapter: onBluetoothStateChange: up=true
,05-25 13:51:20.085  3549  3838 V AlarmManager:  remove PendingIntent] PendingIntent{fdf8d0b: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
05-25 13:51:20.085  4287  4584 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,05-25 13:51:20.085  4249  4259 D BluetoothAdapter: onBluetoothStateChange: up=true
05-25 13:51:20.085  4249  4259 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,05-25 13:51:20.085  3949  4541 D BluetoothSap: onBluetoothStateChange: up=true
,05-25 13:51:20.085  3949  4541 D BluetoothSap: Binding service...
05-25 13:51:20.085  3549  4435 V AlarmManager:  remove PendingIntent] PendingIntent{377eee7: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:20.095  3949  3949 D BluetoothA2dp: Proxy object connected
,05-25 13:51:20.095  3949  3949 D A2dpProfile: Bluetooth service connected
,05-25 13:51:20.095  4889  4889 D BluetoothA2dp: Proxy object connected
,05-25 13:51:20.095  9180  9180 D BluetoothPan: BluetoothPAN Proxy object connected
05-25 13:51:20.095  4889  4979 D BluetoothAdapter: onBluetoothStateChange: up=true
05-25 13:51:20.095  3549  4435 V AlarmManager:  remove PendingIntent] PendingIntent{50cb532: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
05-25 13:51:20.095  4889  4979 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
05-25 13:51:20.095 10053 10094 D A2dpStateMachine: getConnectedDevices : size=0
,05-25 13:51:20.095  9180  9180 D PanProfile: Bluetooth service connected
,05-25 13:51:20.095  3549  4286 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
05-25 13:51:20.095  3949  3969 D BluetoothPan: onBluetoothStateChange on: true
05-25 13:51:20.095  3949  3969 D BluetoothPan: onBluetoothStateChange calling doBind()
,05-25 13:51:20.105  3949  3949 D BluetoothPan: BluetoothPAN Proxy object connected
05-25 13:51:20.105  3949  3949 D PanProfile: Bluetooth service connected
,05-25 13:51:20.105  3549  4435 V AlarmManager:  remove PendingIntent] PendingIntent{77afc39: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:20.115  9180  9192 D BluetoothMap: onBluetoothStateChange: up=true
,05-25 13:51:20.115  3549  3986 V AlarmManager:  remove PendingIntent] PendingIntent{54cf27e: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:20.115  9936  9947 D BluetoothAdapter: onBluetoothStateChange: up=true
05-25 13:51:20.115  9936  9947 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
05-25 13:51:20.115  3549  3619 D BluetoothA2dp: onBluetoothStateChange: up=true
,05-25 13:51:20.115  3549  3619 D BluetoothA2dp: Binding service...
05-25 13:51:20.115  3549  3619 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,05-25 13:51:20.115  3549  3549 D BluetoothA2dp: Proxy object connected
,05-25 13:51:20.115  3949  4123 D BluetoothMap: onBluetoothStateChange: up=true
05-25 13:51:20.115  3949  4123 D BluetoothMap: Binding service...
,05-25 13:51:20.125  9180  9180 D BluetoothSap: Proxy object connected
,05-25 13:51:20.125  9180  9180 D SapProfile: Bluetooth service connected
05-25 13:51:20.125  3949  3949 D BluetoothSap: Proxy object connected
05-25 13:51:20.125  3949  3949 D SapProfile: Bluetooth service connected
05-25 13:51:20.125 10053 10109 D A2dpStateMachine: getConnectedDevices : size=0
,05-25 13:51:20.125  3949  3949 D BluetoothMap: Proxy object connected
,05-25 13:51:20.125  3949  3949 D MapProfile: Bluetooth service connected
05-25 13:51:20.125  3949  3949 D BluetoothMap: getConnectedDevices()
05-25 13:51:20.125 10053 10115 D BluetoothSocket: bindListen(): myUserId = 0
05-25 13:51:20.125 10053 10115 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,05-25 13:51:20.125  3549  3838 V AlarmManager:  remove PendingIntent] PendingIntent{71cefb: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:20.135 10053 10115 I BtOppRfcommListener: Accept thread started.
,05-25 13:51:20.135  7081  7092 D BluetoothAdapter: onBluetoothStateChange: up=true
05-25 13:51:20.135  7081  7092 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
05-25 13:51:20.135  3549  3619 D BluetoothPan: onBluetoothStateChange on: true
,05-25 13:51:20.135  3549  3619 D BluetoothPan: onBluetoothStateChange calling doBind()
,05-25 13:51:20.135  3549  3549 D BluetoothPan: BluetoothPAN Proxy object connected
05-25 13:51:20.135  9180  9192 D BluetoothLeAudio: onBluetoothStateChange: up=true
05-25 13:51:20.135  3549  3619 D BluetoothAdapter: onBluetoothStateChange: up=true
05-25 13:51:20.135  3549  3981 V AlarmManager:  remove PendingIntent] PendingIntent{c0ad356: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
05-25 13:51:20.135  3549  3619 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,05-25 13:51:20.135 10053 10114 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,05-25 13:51:20.135 10053 10114 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
05-25 13:51:20.135  3549  3549 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
05-25 13:51:20.135  3549  3549 I InputMethodManagerService: [BT Setting State] State =12
,05-25 13:51:20.135  3549  3549 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,05-25 13:51:20.145  4316  4316 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
05-25 13:51:20.145  3949  4133 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,05-25 13:51:20.145  3949  4133 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
05-25 13:51:20.145  3549  3549 I Telecom : BluetoothPhoneService: queryPhoneState
05-25 13:51:20.145  3549  3549 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState : true
,05-25 13:51:20.145  3549  3549 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
05-25 13:51:20.145  3549  3549 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
05-25 13:51:20.145  3549  3549 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,05-25 13:51:20.145  4782  4782 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,05-25 13:51:20.145  9936  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,05-25 13:51:20.155  9180  9180 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
05-25 13:51:20.155  9180  9180 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,05-25 13:51:20.155  9936  9936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:51:20.165  3549  3603 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7845fd7 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{244f13b 9180:com.android.settings/1000}
,05-25 13:51:20.175  9180  9180 D LocalBluetoothProfileManager: Adding local A2DP profile
,05-25 13:51:20.175  9180  9180 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,05-25 13:51:20.185 10116 10116 E Zygote  : v2
05-25 13:51:20.185 10116 10116 I libpersona: KNOX_SDCARD checking this for 10049
05-25 13:51:20.185 10116 10116 E Zygote  : isSdpEnabledProcess - SDP enabled
05-25 13:51:20.185 10116 10116 I libpersona: KNOX_SDCARD not a persona
,05-25 13:51:20.185 10116 10116 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-25 13:51:20.195  3549  3981 I ActivityManager: Start proc 10116:com.samsung.android.email.provider/u0a49 for content provider com.samsung.android.email.provider/.provider.database.EmailProvider
,05-25 13:51:20.195 10116 10116 E Zygote  : accessInfo : 64
05-25 13:51:20.195 10116 10116 E Zygote  : isSdpEnabledProcess - SDP enabled
05-25 13:51:20.195 10116 10116 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10049 / [uid]: 10049
05-25 13:51:20.195 10116 10116 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.email.provider 
,05-25 13:51:20.195  3549  3857 D NetworkPolicy: isUidForegroundLocked: 10049, mScreenOn: true, uidstate: -1, mProxSensorScreenOff: false
05-25 13:51:20.195  3549  4432 V AlarmManager:  remove PendingIntent] PendingIntent{660e530: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:20.195  9936 10036 D BluetoothAdapter: STATE_ON
05-25 13:51:20.195  9180  9180 D LocalBluetoothProfileManager: Adding local HEADSET profile
,05-25 13:51:20.205  9180  9180 E BluetoothHeadset: BTStateChangeCB is registed
05-25 13:51:20.205  3549  4931 V AlarmManager:  remove PendingIntent] PendingIntent{3d8f72e: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:20.205  9180  9180 W LocalBluetoothProfileManager: updateLocalProfiles :: MAP profile was previously added but the UUID is now missing.
05-25 13:51:20.205  9180  9180 W LocalBluetoothProfileManager: updateLocalProfiles :: PBAP profile was previously added but the UUID is now missing.
05-25 13:51:20.205  9180  9180 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
05-25 13:51:20.205  9180  9180 W LocalBluetoothProfileManager: updateLocalProfiles :: HID profile was previously added but the UUID is now missing.
05-25 13:51:20.205  9180  9180 W LocalBluetoothProfileManager: updateLocalProfiles :: BleAudio profile was created already 
,05-25 13:51:20.205  9936 10036 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-25 13:51:20.205  9936 10036 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-25 13:51:20.205  9936 10036 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-25 13:51:20.205  9936 10036 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-25 13:51:20.205  9936 10036 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-25 13:51:20.205  9936 10036 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-25 13:51:20.205  9936 10036 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-25 13:51:20.205  9936 10036 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-25 13:51:20.205  9936 10036 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
05-25 13:51:20.205  9936  9999 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
,05-25 13:51:20.215  3549  4931 V AlarmManager:  remove PendingIntent] PendingIntent{3a7245c: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:20.215  9936  9999 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:51:20.215  3549  3838 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,05-25 13:51:20.215  3549  3838 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,05-25 13:51:20.215  3549  3838 D WifiService: setWifiEnabled: false pid=9936, uid=10074
05-25 13:51:20.215  3549  3838 D SettingsProvider: isChangeAllowed() : name = wifi_on
05-25 13:51:20.225  3549  3859 D WifiBigDataLog: getJsonFormat() - feature : ONOF
05-25 13:51:20.225  3549  3859 D WifiBigDataLog: init : 
05-25 13:51:20.225  3549  4433 V AlarmManager:  remove PendingIntent] PendingIntent{666b365: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
05-25 13:51:20.225  3549  3863 D WifiStateMachine: setFccChannel: channel = 0
05-25 13:51:20.225  3549  3859 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
05-25 13:51:20.225  3549  3863 D WifiController: [FCC]setFccChannel() is called !!!
05-25 13:51:20.225  3549  3863 D WifiController: MHS off and WIFI tunred off and move to mApStaDisabledState
05-25 13:51:20.225  3549  3863 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
05-25 13:51:20.225  3549  3863 D SecContentProvider: insert(), uri = 2
,05-25 13:51:20.225  3549  3859 D WifiStateMachine: setFccChannelNative: channel = 0
,05-25 13:51:20.225  3549  3859 D WifiNative-wlan0: callSECApiInt - ID [230]
,05-25 13:51:20.235  3949  4133 W LocalBluetoothProfileManager: updateLocalProfiles :: MAP profile was previously added but the UUID is now missing.
05-25 13:51:20.235  3949  4133 W LocalBluetoothProfileManager: updateLocalProfiles :: PBAP profile was previously added but the UUID is now missing.
05-25 13:51:20.235  3949  4133 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
05-25 13:51:20.235  3949  4133 W LocalBluetoothProfileManager: updateLocalProfiles :: HID profile was previously added but the UUID is now missing.
05-25 13:51:20.235  3949  4133 W LocalBluetoothProfileManager: updateLocalProfiles :: BleAudio profile was created already 
,05-25 13:51:20.235  9180  9180 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,05-25 13:51:20.235 10116 10116 D TimaKeyStoreProvider: TimaSignature is unavailable
05-25 13:51:20.235 10116 10116 D ActivityThread: Added TimaKeyStore provider
,05-25 13:51:20.245  3549  3857 D NetworkPolicy: isUidForegroundLocked: 10049, mScreenOn: true, uidstate: 16, mProxSensorScreenOff: false
,05-25 13:51:20.255  9180  9180 D BluetoothA2dp: Proxy object connected
,05-25 13:51:20.255  9180  9180 D A2dpProfile: Bluetooth service connected
,05-25 13:51:20.255  3549  3859 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,05-25 13:51:20.265  3549  3859 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
,05-25 13:51:20.265 10053 10109 D A2dpStateMachine: getConnectedDevices : size=0
05-25 13:51:20.265  3949  4213 D BluetoothTile: handleUpdateState :  supported = true, enabled = true, enabling = false, connected = false, connecting = false, mController.getLastDeviceName() = null
05-25 13:51:20.265  3549  4286 D StatusBarManagerService: setIcon slot=bluetooth index=18 icon=StatusBarIcon(icon=Icon(typ=RESOURCE pkg=com.android.systemui id=0x7f02049a) visible user=0 )
05-25 13:51:20.265  3549  3567 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,05-25 13:51:20.275  3549  4285 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7845fd7 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{44442de 4889:com.samsung.android.providers.context/u0a7}
,05-25 13:51:20.275  3549  3859 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
05-25 13:51:20.275  3549  3859 D WifiStateMachine: sendBroadcastForCaptivePortalNotLoginIcon : false
,05-25 13:51:20.275 10116 10116 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in com.samsung.android.email.provider rsrc of package com.samsung.android.email.provider
,05-25 13:51:20.275  3549  3859 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
,05-25 13:51:20.275  3549  4430 V AlarmManager:  remove PendingIntent] PendingIntent{1b02a48: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:20.275  3949  4133 D NetworkController: onReceive: intent=Intent { act=com.samsung.intent.action.WIFI_CAPTIVE_NOT_LOGIN flg=0x10 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
05-25 13:51:20.275  3949  4133 D NetworkController.WifiSignalController: updateWifiState : mCurrentState.wifiCaptiveNotLogin = false
,05-25 13:51:20.285  3549  3859 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
,05-25 13:51:20.285  3549  3859 D SecContentProvider: insert(), uri = 2
,05-25 13:51:20.295  9180  9180 D DockEventReceiver: finishStartingService: stopping service
,05-25 13:51:20.295  3549  3838 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-25 13:51:20.295 10116 10116 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-25 13:51:20.305 10116 10116 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:51:20.305  3549  3567 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7845fd7 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f3ae3d9 4287:com.google.android.gms.persistent/u0a19}
,05-25 13:51:20.305  4287  4287 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
,05-25 13:51:20.305 10116 10116 I InjectionManager: Inside getClassLibPath caller 
,05-25 13:51:20.315  3549  3859 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
05-25 13:51:20.315  3549  3859 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
05-25 13:51:20.315  3549  3859 D WifiStateMachine: sendBroadcastForCaptivePortalNotLoginIcon : false
,05-25 13:51:20.325  3549  3567 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7845fd7 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a2429dc 8769:com.sec.android.app.shealth:remote/u0a36}
,05-25 13:51:20.325  3549  4286 V AlarmManager:  remove PendingIntent] PendingIntent{1cbe06: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:20.335 10116 10116 W System  : ClassLoader referenced unknown path: /system/priv-app/SecEmail_M/lib/arm64
,05-25 13:51:20.335  3949  4133 D NetworkController: onReceive: intent=Intent { act=com.samsung.intent.action.WIFI_CAPTIVE_NOT_LOGIN flg=0x10 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
05-25 13:51:20.335  3949  4133 D NetworkController.WifiSignalController: updateWifiState : mCurrentState.wifiCaptiveNotLogin = false
,05-25 13:51:20.345  3549  3567 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7845fd7 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{244f13b 9180:com.android.settings/1000}
,05-25 13:51:20.345  9180  9180 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
05-25 13:51:20.345  9180  9180 D BluetoothStatusReceiver: AdapterStateChanged :: state = 12
,05-25 13:51:20.355  3549  3859 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
,05-25 13:51:20.355  3549  4435 D RCPManagerService: exchangeData() failure , invalid userId
,05-25 13:51:20.365  3549  3567 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7845fd7 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f8c914 10053:com.android.bluetooth/1002}
,05-25 13:51:20.365  3549  3859 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
,05-25 13:51:20.365  3549  3859 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,05-25 13:51:20.365  3549  3858 D WifiP2pService: InactiveState{ what=143375 }
,05-25 13:51:20.365  3549  3858 D WifiP2pService: P2pEnabledState{ what=143375 }
05-25 13:51:20.365  3549  4767 V AlarmManager:  remove PendingIntent] PendingIntent{cc6ecc7: PendingIntentRecord{ed0391a android broadcastIntent}}
,05-25 13:51:20.375  3949  4133 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-25 13:51:20.375  3157  3613 D CommandListener: Clearing all IP addresses on wlan0
,05-25 13:51:20.385  4287  7603 V NativeCrypto: Read error: ssl=0x7f7dd58a80: I/O error during system call, Connection timed out
,05-25 13:51:20.385  3549  3869 E ConnectivityService: updateNetworkInfo()
05-25 13:51:20.385  3549  3869 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -35]
05-25 13:51:20.385  3549  3869 E ConnectivityService: updateNetworkInfo()
05-25 13:51:20.395  3549  3869 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = DISCONNECTED
,05-25 13:51:20.395  3549  3869 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 6
05-25 13:51:20.395  3549  3869 D NtpTrustedTime: currentTimeMillis() cache hit
05-25 13:51:20.395  3549  3869 V NetworkStats: updateIfacesLocked()
05-25 13:51:20.395  3549  3869 V NetworkStats: performPollLocked(flags=0x1)
,05-25 13:51:20.395  3549  3869 D NetworkStatsRecorder: entry.iface is null
05-25 13:51:20.395  3549  3869 D NetworkStatsRecorder: entry.iface is null
05-25 13:51:20.395  3549  3869 D NetworkStatsRecorder: entry.iface is null
05-25 13:51:20.395  3549  3869 D NetworkStatsRecorder: entry.iface is null
,05-25 13:51:20.395  3549  3869 D NtpTrustedTime: currentTimeMillis() cache hit
,05-25 13:51:20.395  3549  3869 V NetworkStats: performPollLocked() took 8ms
,05-25 13:51:20.405  3549  4285 V AlarmManager:  remove PendingIntent] PendingIntent{5c1a2f4: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:20.415  3549  3549 I WifiTrafficPoller: evaluateTrafficStatsPolling
,05-25 13:51:20.415  4287  7603 V NativeCrypto: SSL shutdown failed: ssl=0x7f7dd58a80: I/O error during system call, Broken pipe
,05-25 13:51:20.415  3549  3981 V AlarmManager:  remove PendingIntent] PendingIntent{fd0ea1d: PendingIntentRecord{e1c90a com.google.android.gms broadcastIntent}}
,05-25 13:51:20.415  4287  7603 E GCM     : Wifi connection closed with errorCode 20
,05-25 13:51:20.425  3549  3549 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
05-25 13:51:20.425  3549  3549 D HS20StateMachine: [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true]
,05-25 13:51:20.425  3549  3549 D HS20StateMachine: checkifOSUAP  null disconnectedFromSsid"NG700"
,05-25 13:51:20.425  3549  3549 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
05-25 13:51:20.425  3549  3867 I WifiHs20Service: Message received 5007
05-25 13:51:20.425  3549  3549 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
,05-25 13:51:20.435  3949  4133 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-25 13:51:20.445  3549  3869 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-25 13:51:20.445  3549  3869 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -35]
,05-25 13:51:20.445  3549  3859 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
05-25 13:51:20.445  3549  3869 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
05-25 13:51:20.445  4122  4122 I wpa_supplicant: P2P: Set prekey state (NONE -> NONE)
05-25 13:51:20.445  3549  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:51:20.445  4122  4122 I wpa_supplicant: P2P: Clear a pre-passphrase (State NONE)
05-25 13:51:20.445  3549  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:51:20.445  4260  4260 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
05-25 13:51:20.445  3549  3858 D WifiP2pService: InactiveState{ what=131204 }
05-25 13:51:20.445  3549  3869 D ConnectivityService: sending notification LOST for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:51:20.445  3549  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
05-25 13:51:20.445  3549  3858 D WifiP2pService: P2pEnabledState{ what=131204 }
05-25 13:51:20.445  3549  3869 D ConnectivityService: sending notification LOST for NetworkRequest [ id=5, legacyType=-1, [] ]
,05-25 13:51:20.445  3549  3858 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,05-25 13:51:20.445  3549  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:51:20.445  3549  4285 D RCPManagerService: exchangeData() failure , invalid userId
,05-25 13:51:20.455  3549  4931 D ConnectivityService: getVpnConfig > userId : 0
,05-25 13:51:20.455  3549  3619 D EntConnectivity: Not allowed due to - mEnabled false
,05-25 13:51:20.455 10116 10116 D InjectionManager: InjectionManager
,05-25 13:51:20.455 10116 10116 D InjectionManager: fillFeatureStoreMap com.samsung.android.email.provider
,05-25 13:51:20.455  3549  3869 D ConnectivityService: sending notification LOST for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:51:20.455  3549  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:51:20.455  3549  3869 D ConnectivityService: sending notification LOST for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:51:20.455  3549  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:51:20.455  3549  3869 D ConnectivityService: sending notification LOST for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:51:20.465  3549  3549 D RttService: SCAN_AVAILABLE : 1
,05-25 13:51:20.465  3549  3869 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:51:20.465  3549  4761 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
05-25 13:51:20.465  3549  3893 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
05-25 13:51:20.465  3549  3894 D Ethernet: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:51:20.465  3549  3894 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
05-25 13:51:20.465  3549  3894 D Ethernet: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
05-25 13:51:20.465  3549  3894 D Ethernet: evalRequest
05-25 13:51:20.465  3549  3894 D Ethernet:   done
05-25 13:51:20.465  3549  3859 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:51:20.465  3549  3859 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-25 13:51:20.465  3549  3859 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
05-25 13:51:20.465  3549  3859 D WIFI    : evalRequest
05-25 13:51:20.465  3549  3859 D WIFI    :   needNetworkFor
05-25 13:51:20.465  3549  3859 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:51:20.465  3549  3859 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,05-25 13:51:20.465  3549  3859 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
05-25 13:51:20.465  3549  3859 D WIFI    : evalRequest
05-25 13:51:20.465  3549  3859 D WIFI    :   done
05-25 13:51:20.465  3549  3859 D WIFI_UT : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:51:20.465  3549  3859 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-25 13:51:20.465  3549  3859 D WIFI_UT : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
05-25 13:51:20.465  3549  3859 D WIFI_UT : evalRequest
05-25 13:51:20.465  3549  3859 D WIFI_UT :   done
,05-25 13:51:20.465 10116 10116 I InjectionManager: Constructor com.samsung.android.email.provider, Feature store :{}
05-25 13:51:20.465 10116 10116 I InjectionManager: featureStore :{}
05-25 13:51:20.475  3549  3549 D WifiNotificationController: SHOW_NOTI_MESSAGE : 17, visible : false, ssid : null, targetSSID : null, netId : -1, titleType : -1
05-25 13:51:20.475  3549  3857 D NtpTrustedTime: currentTimeMillis() cache hit
05-25 13:51:20.475  3549  3549 D WifiNotificationController: showMaliciousHotspotDetectionNotification - MaliciousNetwork:null, visible:false
05-25 13:51:20.475  3549  3857 D NtpTrustedTime: currentTimeMillis() cache hit
,05-25 13:51:20.485  3549  4420 V AlarmManager:  remove PendingIntent] PendingIntent{2b6b492: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:20.495  3157  3613 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,05-25 13:51:20.505 10140 10140 E Zygote  : v2
05-25 13:51:20.505 10140 10140 I libpersona: KNOX_SDCARD checking this for 10049
,05-25 13:51:20.505 10140 10140 I libpersona: KNOX_SDCARD not a persona
05-25 13:51:20.505 10140 10140 E Zygote  : isSdpEnabledProcess - SDP enabled
05-25 13:51:20.505 10140 10140 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-25 13:51:20.505 10140 10140 E Zygote  : accessInfo : 64
05-25 13:51:20.505 10140 10140 E Zygote  : isSdpEnabledProcess - SDP enabled
05-25 13:51:20.505 10140 10140 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10049 / [uid]: 10049
05-25 13:51:20.505 10140 10140 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.email.provider:service 
05-25 13:51:20.505 10053 10053 D BleAudioService: onReceive:: INTENT mAobleStateChangeListener got : android.bluetooth.adapter.action.STATE_CHANGED
05-25 13:51:20.505 10053 10053 D BleAudioService: BluetoothAdapter.ACTION_STATE_CHANGED,  state is12
,05-25 13:51:20.515  3949  3949 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 272
,05-25 13:51:20.515 10053 10103 D BleAudioStateMachine_L: [Disconnected] Disconnected process message: 41
05-25 13:51:20.515 10053 10103 D BleAudioStateMachine_L: [Disconnected] MSG_ADAPTER_BT_ON_EVT event received
05-25 13:51:20.515 10053 10104 D BleAudioStateMachine_R: [Disconnected] Disconnected process message: 41
05-25 13:51:20.515 10053 10104 D BleAudioStateMachine_R: [Disconnected] MSG_ADAPTER_BT_ON_EVT event received
,05-25 13:51:20.525  3549  4435 I ActivityManager: Start proc 10140:com.samsung.android.email.provider:service/u0a49 for service com.samsung.android.email.provider/com.samsung.android.email.sync.service.EmailService
,05-25 13:51:20.525 10053 10104 D BleAudioStateMachine: getLastConnectedDeviceAddress() for channel = 2
05-25 13:51:20.525 10053 10104 D BleAudioService: NotifyEvents: n : 0
05-25 13:51:20.525  3157  3613 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,05-25 13:51:20.525 10053 10103 D BleAudioStateMachine: getLastConnectedDeviceAddress() for channel = 1
05-25 13:51:20.525 10053 10103 D BleAudioService: NotifyEvents: n : 0
,05-25 13:51:20.525  3549  3869 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -35]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} } wasDefault=true
05-25 13:51:20.525  3549  3869 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
05-25 13:51:20.525  3549  3869 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,05-25 13:51:20.535  3549  3620 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:20.535  3549  3620 I WifiDisplayAdapter: onP2pDisconnected
05-25 13:51:20.535  3549  3620 D IpRemoteDisplayController: disconnectWfdBridgeServer
05-25 13:51:20.535  3549  3620 D IpRemoteDisplayController: WfdBridgeServer is already null
,05-25 13:51:20.535  3949  3949 D WifiP2pController: onReceive android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,05-25 13:51:20.535  3549  3858 D SecContentProvider: insert(), uri = 2
05-25 13:51:20.535  3549  3858 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,05-25 13:51:20.535  9180  9180 D HeadsetProfile: Bluetooth service connected
,05-25 13:51:20.545  3949  3949 D HeadsetProfile: Bluetooth service connected
,05-25 13:51:20.545 10053 10053 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa689ba
05-25 13:51:20.545 10053 10053 D BtConfig.SecureMode: isSecureModeOn:false
,05-25 13:51:20.545  3549  3619 D EntConnectivity: Not allowed due to - mEnabled false
,05-25 13:51:20.555  3549  3858 D WIFI_P2P: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:51:20.555  3549  3858 D WifiP2pService: P2pDisablingState
05-25 13:51:20.555  3549  3858 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-25 13:51:20.555  3549  3858 D WifiP2pService: P2pDisablingState{ what=147458 }
05-25 13:51:20.555  3549  3858 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
05-25 13:51:20.555  3549  3858 D WifiP2pService: p2p socket connection lost
05-25 13:51:20.555  3549  3858 D WIFI_P2P: evalRequest
05-25 13:51:20.555  3549  3858 D WIFI_P2P:   done
05-25 13:51:20.555  3549  3858 D SecContentProvider: insert(), uri = 2
,05-25 13:51:20.565  3549  3859 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,05-25 13:51:20.565  3549  3858 D WifiP2pService: P2pDisabledState
,05-25 13:51:20.565  3549  3858 D WifiP2pService: P2pDisabledState{ what=143375 }
05-25 13:51:20.565  3549  3858 D WifiP2pService: DefaultState{ what=143375 }
,05-25 13:51:20.565  3549  3620 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false, mScanRequestedInConnected = false
,05-25 13:51:20.565  3549  3620 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
05-25 13:51:20.565  3549  3620 D WifiDisplayController: disconnect
05-25 13:51:20.565  3549  3620 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,05-25 13:51:20.575 10140 10140 D TimaKeyStoreProvider: TimaSignature is unavailable
,05-25 13:51:20.575 10140 10140 D ActivityThread: Added TimaKeyStore provider
,05-25 13:51:20.575  3549  3601 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
05-25 13:51:20.575  3549  3601 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:51:20.575  3549  3601 D GpsLocationProvider: updateNetworkState unavailable info: [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:51:20.585  3949  4133 D NetworkController: onReceive: intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-25 13:51:20.595  4782  4782 D SamsungIME: EngineType = SWIFTKEY
,05-25 13:51:20.595  4782  4782 D SamsungIME: mNetworkChangeReceiver isWLANConnected : false
05-25 13:51:20.595  4905  5035 D CellLocationSupport: onReceive ACTION = android.net.conn.CONNECTIVITY_CHANGE
05-25 13:51:20.595  4905  5035 I CellLocationSupport: onCellLocationChanged
,05-25 13:51:20.595  3157  3613 E Netd    : netlink response contains error (No such file or directory)
,05-25 13:51:20.605  3549  3869 D ConnectivityService: setProvNotificationVisibleIntent SIGN_IN visible=false networkType=WIFI extraInfo=null highPriority=false
05-25 13:51:20.605  3549  3869 D ConnectivityService: nai.networkMonitor.doQuit()
05-25 13:51:20.605  3549  3869 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: doQuit - quitNow()
,05-25 13:51:20.605  3549  3869 E ConnectivityService: updateNetworkInfo()
05-25 13:51:20.605  3549  3869 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-25 13:51:20.605  3549  3869 E ConnectivityService: updateNetworkInfo()
05-25 13:51:20.605  3549  3869 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
,05-25 13:51:20.605  4905  4905 D PdnController: CONNECTIVITY_ACTION: networkType 1 isConnected false
05-25 13:51:20.605  3549  4367 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:20.605  4905  4905 D PdnController: isSuspended [false] networktype [1]
05-25 13:51:20.605  4905  4905 D PdnController: isPdnUp  [false] networktype [1]
05-25 13:51:20.615  3549  3857 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-25 13:51:20.605  4905  4905 D PdnController: Notify Result to LocalIP Registrants! : networkType [1] isConnected [false] 
05-25 13:51:20.615  5475  5475 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@fef2a46 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
05-25 13:51:20.615  3549  3857 D NtpTrustedTime: currentTimeMillis() cache hit
05-25 13:51:20.615  3549  3857 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
05-25 13:51:20.615  3549  3857 D NtpTrustedTime: currentTimeMillis() cache hit
05-25 13:51:20.615  3549  3857 D NtpTrustedTime: currentTimeMillis() cache hit
05-25 13:51:20.615  3549  3857 D NtpTrustedTime: currentTimeMillis() cache hit
,05-25 13:51:20.625  4905  5035 I CellLocationSupport: Block to update PANI information in non VoWIFI
05-25 13:51:20.625  4905  5035 D SlickSSConfigHandler: EVENT_LOCAL_IP_CHANGED
,05-25 13:51:20.625  3157  3609 D EnterpriseController: netId is 0
05-25 13:51:20.625  3157  3609 D Netd    : getNetworkForDns: using netid 0 for uid 10001
,05-25 13:51:20.625  3549  4420 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:51:20.625  3549  4367 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:51:20.635  4555 10159 E         : Error communicating to API: https://prod.yana.asideas.de/api/v2/advertising/frequencies/pl
05-25 13:51:20.635  4555 10159 E         : retrofit.RetrofitError: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
05-25 13:51:20.635  4555 10159 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:395)
05-25 13:51:20.635  4555 10159 E         : 	at retrofit.RestAdapter$RestHandler.access$100(RestAdapter.java:220)
05-25 13:51:20.635  4555 10159 E         : 	at retrofit.RestAdapter$RestHandler$1.invoke(RestAdapter.java:265)
05-25 13:51:20.635  4555 10159 E         : 	at retrofit.RxSupport$2.run(RxSupport.java:55)
05-25 13:51:20.635  4555 10159 E         : 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
05-25 13:51:20.635  4555 10159 E         : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
05-25 13:51:20.635  4555 10159 E         : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
05-25 13:51:20.635  4555 10159 E         : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
05-25 13:51:20.635  4555 10159 E         : 	at retrofit.Platform$Android$2$1.run(Platform.java:142)
05-25 13:51:20.635  4555 10159 E         : 	at java.lang.Thread.run(Thread.java:818)
05-25 13:51:20.635  4555 10159 E         : Caused by: java.net.UnknownHostException: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
05-25 13:51:20.635  4555 10159 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:470)
05-25 13:51:20.635  4555 10159 E         : 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
05-25 13:51:20.635  4555 10159 E         : 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
05-25 13:51:20.635  4555 10159 E         : 	at com.squareup.okhttp.internal.Network$1.resolveInetAddresses(Network.java:29)
05-25 13:51:20.635  4555 10159 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:187)
05-25 13:51:20.635  4555 10159 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.nextProxy(RouteSelector.java:156)
05-25 13:51:20.635  4555 10159 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.next(RouteSelector.java:98)
05-25 13:51:20.635  4555 10159 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.createNextConnection(HttpEngine.java:344)
05-25 13:51:20.635  4555 10159 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:327)
05-25 13:51:20.635  4555 10159 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:245)
05-25 13:51:20.635  4555 10159 E         : 	at com.squareup.okhttp.Call.getResponse(Call.java:267)
05-25 13:51:20.635  4555 10159 E         : 	at com.squareup.okhttp.Call$ApplicationInterceptorChain.proceed(Call.java:224)
05-25 13:51:20.635  4555 10159 E         : 	at com.squareup.okhttp.Call.getResponseWithInterceptorChain(Call.java:195)
05-25 13:51:20.635  4555 10159 E         : 	at com.squareup.okhttp.Call.execute(Call.java:79)
05-25 13:51:20.635  4555 10159 E         : 	at retrofit.client.OkClient.execute(OkClient.java:53)
05-25 13:51:20.635  4555 10159 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:326)
05-25 13:51:20.635  4555 10159 E         : 	... 9 more
05-25 13:51:20.635  4555 10159 E         : Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
05-25 13:51:20.635  4555 10159 E         : 	at libcore.io.Posix.android_getaddrinfo(Native Method)
05-25 13:51:20.635  4555 10159 E         : 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
05-25 13:51:20.635  4555 10159 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:451)
05-25 13:51:20.635  4555 10159 E         : 	... 24 more
05-25 13:51:20.635  4555 10159 E         : 
,05-25 13:51:20.635  4905  5035 D PdnController: isIfaceDisconnected result [true] networkType [0] interfaceName [null] 
05-25 13:51:20.635  4905  5035 D PdnController: isPdnUp  [false] networktype [0]
05-25 13:51:20.635  4905  5035 D SlickSSConfigHandler: handleNetworkStateChange: check isDefaultPDNConnected[false], mReadyForDocFetch[false
05-25 13:51:20.635  4555 10159 E         : Unable to fetch advertisement frequency.
05-25 13:51:20.635  4555 10159 E         : retrofit.RetrofitError: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
05-25 13:51:20.635  4555 10159 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:395)
05-25 13:51:20.635  4555 10159 E         : 	at retrofit.RestAdapter$RestHandler.access$100(RestAdapter.java:220)
05-25 13:51:20.635  4555 10159 E         : 	at retrofit.RestAdapter$RestHandler$1.invoke(RestAdapter.java:265)
05-25 13:51:20.635  4555 10159 E         : 	at retrofit.RxSupport$2.run(RxSupport.java:55)
05-25 13:51:20.635  4555 10159 E         : 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
05-25 13:51:20.635  4555 10159 E         : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
05-25 13:51:20.635  4555 10159 E         : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
05-25 13:51:20.635  4555 10159 E         : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
05-25 13:51:20.635  4555 10159 E         : 	at retrofit.Platform$Android$2$1.run(Platform.java:142)
05-25 13:51:20.635  4555 10159 E         : 	at java.lang.Thread.run(Thread.java:818)
05-25 13:51:20.635  4555 10159 E         : Caused by: java.net.UnknownHostException: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
05-25 13:51:20.635  4555 10159 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:470)
05-25 13:51:20.635  4555 10159 E         : 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
05-25 13:51:20.635  4555 10159 E         : 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
05-25 13:51:20.635  4555 10159 E         : 	at com.squareup.okhttp.internal.Network$1.resolveInetAddresses(Network.java:29)
05-25 13:51:20.635  4555 10159 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:187)
05-25 13:51:20.635  4555 10159 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.nextProxy(RouteSelector.java:156)
05-25 13:51:20.635  4555 10159 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.next(RouteSelector.java:98)
05-25 13:51:20.635  4555 10159 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.createNextConnection(HttpEngine.java:344)
05-25 13:51:20.635  4555 10159 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:327)
05-25 13:51:20.635  4555 10159 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:245)
05-25 13:51:20.635  4555 10159 E         : 	at com.squareup.okhttp.Call.getResponse(Call.java:267)
05-25 13:51:20.635  4555 10159 E         : 	at com.squareup.okhttp.Call$ApplicationInterceptorChain.proceed(Call.java:224)
05-25 13:51:20.635  4555 10159 E         : 	at com.squareup.okhttp.Call.getResponseWithInterceptorChain(Call.java:195)
05-25 13:51:20.635  4555 10159 E         : 	at com.squareup.okhttp.Call.execute(Call.java:79)
05-25 13:51:20.635  4555 10159 E         : 	at retrofit.client.OkClient.execute(OkClient.java:53)
05-25 13:51:20.635  4555 10159 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:326)
05-25 13:51:20.635  4555 10159 E         : 	... 9 more
05-25 13:51:20.635  4555 10159 E         : Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
05-25 13:51:20.635  4555 10159 E         : 	at libcore.io.Posix.android_getaddrinfo(Native Method)
05-25 13:51:20.635  4555 10159 E         ,: 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
05-25 13:51:20.635  4555 10159 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:451)
05-25 13:51:20.635  4555 10159 E         : 	... 24 more
05-25 13:51:20.635  4555 10159 E         : 
,05-25 13:51:20.635  6737  6737 I FOTA_AGENT: [com.samsung.android.app.syncmldm.XDMService(1060/IIllllIIlIIllIIIIlll)] WiFi network Connected : false
,05-25 13:51:20.645  3549  3986 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:51:20.645  4905  5035 D RegistrationManager: handleMessage(): 5
,05-25 13:51:20.645  4416  4416 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,05-25 13:51:20.645  3549  4435 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:51:20.645  4905  5035 D PdnController: isIfaceDisconnected result [true] networkType [11] interfaceName [null] 
05-25 13:51:20.645  4905  5035 D PdnController: isPdnUp  [false] networktype [11]
05-25 13:51:20.645  4905  5035 D RegistrationManager: setEPDGIPSecConnected [false]
05-25 13:51:20.645  4905  5035 D RegistrationManager: notifyNetworkState : NetworkType [1] IsConnected [false] IPAddresses [[]] DNSAddresses [[]] 
05-25 13:51:20.645  4905  5035 D RegistrationManager: isEPDGAvailable [false]
05-25 13:51:20.645  4905  5035 D CoreController: setState [DEREGISTERED]
,05-25 13:51:20.665  9936  9936 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,05-25 13:51:20.675  9936  9936 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,05-25 13:51:20.675  9936  9936 D BluetoothAdapter: STATE_ON
,05-25 13:51:20.685  9936  9936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-25 13:51:20.685  9936  9936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-25 13:51:20.685  9936  9936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-25 13:51:20.685  9936  9936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-25 13:51:20.685  9936  9936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-25 13:51:20.685  9936  9936 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
05-25 13:51:20.685  9936  9936 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
05-25 13:51:20.685  9936  9936 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
05-25 13:51:20.685  9936  9936 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
05-25 13:51:20.685  3549  4430 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7845fd7 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a53ad79 7081:com.google.android.apps.maps/u0a119}
,05-25 13:51:20.685  9936  9936 D BluetoothAdapter: STATE_ON
,05-25 13:51:20.685  9936  9936 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,05-25 13:51:20.695  3157  3613 D CommandListener: Clearing all IP addresses on wlan0
,05-25 13:51:20.695  3949  3949 D WifiP2pController: onReceive android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,05-25 13:51:20.695  3549  3620 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
05-25 13:51:20.695  3549  3620 I WifiDisplayAdapter: onP2pDisconnected
05-25 13:51:20.695  3549  3620 D IpRemoteDisplayController: disconnectWfdBridgeServer
05-25 13:51:20.695  3549  3620 D IpRemoteDisplayController: WfdBridgeServer is already null
,05-25 13:51:20.705  3949  4133 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-25 13:51:20.705  3949  3949 D SoundPathController: onReceive - android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,05-25 13:51:20.705  3949  3949 D ApMirroringController: onReceive android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,05-25 13:51:20.705  3949  3949 D AllShareCastTile: onReceive : android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,05-25 13:51:20.705  3549  4286 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,05-25 13:51:20.705  3949  3949 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,05-25 13:51:20.705  7081  7252 I SQLiteDatabase: can't enable WAL for memory databases.
,05-25 13:51:20.715  4260  4272 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,05-25 13:51:20.715  4260  4272 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,05-25 13:51:20.715  3549  3601 D TelephonyManager: getDataEnabled: retVal=true
,05-25 13:51:20.715  4905  5035 D TranslatorCollection: translateToNwkSvcType: networkType XAN_NWK_TYPE_WLAN
05-25 13:51:20.715  4905  5035 D RegistrationManager: getNetworkType [0]
05-25 13:51:20.715  4905  5035 D CoreStackAdaptor2: notifyNetworkState() [1] isConnected [false] nwkSvcType  [XAN_NWK_TYPE_WLAN] nwkInfoType [XAN_SVC_NETWORK_SVCTYPE_WIFI] dedicated   [NONE] 
05-25 13:51:20.715  4905  5035 D TranslatorCollection: translateToNwkSvcType: networkType XAN_NWK_TYPE_WLAN
,05-25 13:51:20.715  4905  5035 D CoreStackAdaptor2: ipList =  Null
05-25 13:51:20.715  4905  5035 D RegistrationManager: tryRegister(CONNECTIVITY_STATUS_CHANGE)
05-25 13:51:20.715  4905  5035 D RegistrationManager: isPreconditionProperToGoOn
05-25 13:51:20.715  4905  5035 D RegistrationManager: isDeviceShutdown [false]
05-25 13:51:20.715  4905  5035 D RegistrationManager: isStackShuttingDownForAllPDNs [false]
05-25 13:51:20.715  4905  5035 D RegistrationManager: isDmVoLTEUpdated [false]
05-25 13:51:20.715  4905  5035 D RegistrationManager: tryRegister : Abort Reason [IMS feature disabled]
05-25 13:51:20.715  4905  5035 D RegistrationManager: tryRegister : Not all preconditions are met!
,05-25 13:51:20.715  7081  7252 I SQLiteDatabase: can't enable WAL for memory databases.
,05-25 13:51:20.715  3549  4432 I ActivityManager: Killing 8842:com.samsung.android.SettingsReceiver/1000 (adj 15): DHA:empty #33
,05-25 13:51:20.725  3549  3549 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@1cffa60
05-25 13:51:20.725  3549  3549 D BluetoothHeadset: registerMessageListener
,05-25 13:51:20.735  3549  3986 V AlarmManager:  remove PendingIntent] PendingIntent{a170b19: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:20.735 10053 10053 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2) for masId0
,05-25 13:51:20.745  3549  4435 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f8787de u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{44442de 4889:com.samsung.android.providers.context/u0a7}
05-25 13:51:20.745  3549  4430 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,05-25 13:51:20.745  3549  4430 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,05-25 13:51:20.745  3549  4430 D WifiService: setWifiEnabled: false pid=9936, uid=10074
,05-25 13:51:20.755 10165 10165 E Zygote  : v2
,05-25 13:51:20.755 10165 10165 I libpersona: KNOX_SDCARD checking this for 10003
05-25 13:51:20.755 10165 10165 I libpersona: KNOX_SDCARD not a persona
05-25 13:51:20.755 10165 10165 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-25 13:51:20.755 10165 10165 E Zygote  : accessInfo : 0
05-25 13:51:20.755 10165 10165 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.provider.badge 
,05-25 13:51:20.765  3549  3567 I ActivityManager: Start proc 10165:com.sec.android.provider.badge/u0a3 for content provider com.sec.android.provider.badge/.BadgeProvider
,05-25 13:51:20.765  4260  4621 D TelephonyProvider: query: url=content://telephony/carriers/preferapn, projectionIn=[Ljava.lang.String;@2a89f4, selection=nullselectionArgs=null, sort=name ASC
,05-25 13:51:20.765  3549  3859 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
05-25 13:51:20.765 10053 10161 D HeadsetService: registerMessageListener
,05-25 13:51:20.765  4260  4621 D TelephonyProvider: query: match = 5
05-25 13:51:20.765  4260  4621 D TelephonyProvider: getPreferredApnId(subId = 2147483643),return -1
05-25 13:51:20.765  4260  4621 D TelephonyProvider: query: selection modified to edited!=2 and edited!=3 and edited!=5 and edited!=6
,05-25 13:51:20.765  4122  4122 I wpa_supplicant: Blacklist: Clear (all) 
05-25 13:51:20.765  4122  4122 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
,05-25 13:51:20.765 10053 10161 D HeadsetService: registerMessageListener
05-25 13:51:20.765 10053 10095 D HeadsetStateMachine: Disconnected process message: 70, size: 0
05-25 13:51:20.765 10053 10095 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@a72d5d0
05-25 13:51:20.765  3549  3549 I Telecom : BluetoothManager : register MessageListener
05-25 13:51:20.765  3549  3549 I Telecom : CallAudioManager: onBluetoothStateChange: no focus
,05-25 13:51:20.765  3549  3549 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,05-25 13:51:20.775  3549  3549 D Tethering: Tethering got CONNECTIVITY_ACTION
,05-25 13:51:20.775  3549  3619 D Tethering: MasterInitialState.processMessage what=3
,05-25 13:51:20.775  3549  3549 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:51:20.775  3549  3549 I CLocInfoService: ['16.5] External Intent Received android.net.conn.CONNECTIVITY_CHANGE
05-25 13:51:20.775  3549  4211 W SLocation: No Active Data Connection
05-25 13:51:20.775  3549  3549 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:51:20.775  3549  3549 I CLocInfoService: CLoinfo wifi false
05-25 13:51:20.775  3549  3549 V MARsPolicyManager: DataConnection: false
05-25 13:51:20.775  3549  4212 V AlarmManager:  remove PendingIntent] PendingIntent{41bdc30: PendingIntentRecord{a1390a9 android broadcastIntent}}
,05-25 13:51:20.775  3549  4211 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:20.775  3549 10177 I ApplicationPolicy: updateDataUsageMap
,05-25 13:51:20.785 10053 10163 D BluetoothSocket: bindListen(): myUserId = 0
,05-25 13:51:20.785 10053 10163 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,05-25 13:51:20.785 10053 10053 D BluetoothSocket: bindListen(): myUserId = 0
,05-25 13:51:20.785 10053 10053 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,05-25 13:51:20.785  3549  3871 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
05-25 13:51:20.785  4260  4271 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,05-25 13:51:20.785  4260  4271 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
05-25 13:51:20.785  3549  3871 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
05-25 13:51:20.785 10165 10165 D TimaKeyStoreProvider: TimaSignature is unavailable
05-25 13:51:20.785 10165 10165 D ActivityThread: Added TimaKeyStore provider
,05-25 13:51:20.835  4628 10178 D MdnsClient: Multicast lock held. Releasing
,05-25 13:51:20.845  3157  3606 D Netd    : Iface p2p0 link up
,05-25 13:51:20.845  3549  3614 D Tethering: interfaceLinkStateChanged p2p0, true
05-25 13:51:20.845  3549  3614 D Tethering: interfaceStatusChanged p2p0, true
05-25 13:51:20.845  4905  4920 D PdnController: Interface Changed p2p0 link up
,05-25 13:51:20.855  3549  3986 D ActivityManager: cleanUpApplicationRecord -- 8842
,05-25 13:51:20.855  3549  3986 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.SettingsReceiver, Auto Run ON
05-25 13:51:20.855 10140 10140 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in com.samsung.android.email.provider rsrc of package com.samsung.android.email.provider
,05-25 13:51:20.855  3549  3981 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-25 13:51:20.855 10140 10140 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-25 13:51:20.865 10140 10140 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:51:20.865  3549  4430 D SettingsProvider: isChangeAllowed() : name = wifi_on
05-25 13:51:20.865  3549  3863 D WifiStateMachine: setFccChannel: channel = 0
05-25 13:51:20.865  3549  3863 D WifiController: [FCC]setFccChannel() is called !!!
05-25 13:51:20.865  3549  3863 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
,05-25 13:51:20.875  3549  3859 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,05-25 13:51:20.875  3549  3859 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,05-25 13:51:20.875 10053 10162 D A2dpStateMachine: getConnectedDevices : size=0
,05-25 13:51:20.875  3549  4432 I ActivityManager: Killing 8855:com.samsung.android.themestore/u0a64 (adj 15): DHA:empty #33
,05-25 13:51:20.885 10140 10140 I InjectionManager: Inside getClassLibPath caller 
,05-25 13:51:20.895  4122  4122 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,05-25 13:51:20.895  4122  4122 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,05-25 13:51:20.905  3157  3606 D Netd    : Iface wlan0 link up
05-25 13:51:20.905  3549  3549 I WifiTrafficPoller: evaluateTrafficStatsPolling
05-25 13:51:20.905  3549  3614 D Tethering: interfaceLinkStateChanged wlan0, true
05-25 13:51:20.905  3549  3614 D Tethering: interfaceStatusChanged wlan0, true
05-25 13:51:20.905 10053 10163 D BluetoothSdpJni: sdpCreateSapsRecordNative:
05-25 13:51:20.905 10053 10163 D BluetoothSdpJni: SDP Create record success - handle: 0,
,05-25 13:51:20.905  4905  4919 D PdnController: Interface Changed wlan0 link up
,05-25 13:51:20.905  3549  3549 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
05-25 13:51:20.905  3549  3549 D HS20StateMachine: [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false]
,05-25 13:51:20.905  3549  3549 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
05-25 13:51:20.905  3549  3867 I WifiHs20Service: Message received 5007
05-25 13:51:20.905  3549  3549 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
,05-25 13:51:20.915 10140 10140 W System  : ClassLoader referenced unknown path: /system/priv-app/SecEmail_M/lib/arm64
,05-25 13:51:20.915  3949  4133 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-25 13:51:20.915  4260  4260 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
05-25 13:51:20.915 10165 10165 W ResourcesManager: getTopLevelResources: /system/priv-app/BadgeProvider_M/BadgeProvider_M.apk / 1.0 running in com.sec.android.provider.badge rsrc of package com.sec.android.provider.badge
,05-25 13:51:20.915  3549  4432 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-25 13:51:20.915 10165 10165 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-25 13:51:20.915  3949  4133 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-25 13:51:20.915 10165 10165 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:51:20.925  3949  3949 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 272
05-25 13:51:20.925  3949  3949 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
05-25 13:51:20.925  3549  3601 E GpsLocationProvider: No APN found to select.
,05-25 13:51:20.925  3949  3949 I HotspotTile: Provider is not defined returning false
,05-25 13:51:20.925  3549  3859 D WifiBigDataLog: init : 
05-25 13:51:20.925  3549  3549 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
05-25 13:51:20.925  3549  3549 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
05-25 13:51:20.925  3549  3549 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
05-25 13:51:20.925  3549  3867 I WifiHs20Service: Message received 5011
05-25 13:51:20.925  3549  3859 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,05-25 13:51:20.925  3949  3949 D HotspotTile: onReceive : 0, 0
,05-25 13:51:20.925  3549  4286 V AlarmManager:  remove PendingIntent] PendingIntent{aa5c8c: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:20.935  3549  4066 D ActivityManager: cleanUpApplicationRecord -- 8855
,05-25 13:51:20.935 10053 10053 D BluetoothSocket: bindListen(): myUserId = 0
05-25 13:51:20.935 10053 10053 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,05-25 13:51:20.935  3549  4066 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.themestore, Auto Run ON
,05-25 13:51:20.945  9936  9936 D BluetoothAdapter: STATE_ON
,05-25 13:51:20.945  3549  3871 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,05-25 13:51:20.945  9936  9936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-25 13:51:20.945  9936  9936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-25 13:51:20.945  9936  9936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-25 13:51:20.945  9936  9936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
05-25 13:51:20.945  9936  9936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-25 13:51:20.945  9936  9936 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
05-25 13:51:20.945  9936  9936 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
05-25 13:51:20.945  9936  9936 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
05-25 13:51:20.945  9936  9936 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,05-25 13:51:20.945 10165 10165 I InjectionManager: Inside getClassLibPath caller 
,05-25 13:51:20.945  4260  4546 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
05-25 13:51:20.945  4260  4546 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,05-25 13:51:20.945  3549  3549 D WifiNotificationController: SHOW_NOTI_MESSAGE : 17, visible : false, ssid : null, targetSSID : null, netId : -1, titleType : -1
05-25 13:51:20.945  3549  3549 D WifiNotificationController: showMaliciousHotspotDetectionNotification - MaliciousNetwork:null, visible:false
,05-25 13:51:20.955  3549  3871 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,05-25 13:51:20.955 10165 10165 W System  : ClassLoader referenced unknown path: /system/priv-app/BadgeProvider_M/lib/arm64
,05-25 13:51:20.955 10053 10053 D ObexServerSockets: Succeed to create listening sockets 
,05-25 13:51:20.955 10053 10053 D ObexServerSockets: startAccept()
05-25 13:51:20.955 10053 10179 D ObexServerSockets: Accepting socket connection for masId0
,05-25 13:51:20.965  9936  9936 D BluetoothAdapter: STATE_ON
,05-25 13:51:20.965 10053 10180 D ObexServerSockets: Accepting socket connection for masId0
,05-25 13:51:20.965 10165 10165 D BadgeProvider: onCreate
05-25 13:51:20.965 10165 10165 D BadgeProvider: DatabaseHelper
,05-25 13:51:20.965  9936  9936 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,05-25 13:51:20.975  9936  9936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
05-25 13:51:20.975 10053 10053 D BluetoothMapMasInstance: set MAP SDP message type : 1
05-25 13:51:20.975 10053 10053 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
05-25 13:51:20.975 10053 10053 D BluetoothSdpJni: SDP Create record success - handle: 1
,05-25 13:51:20.975  3549  3603 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1043fd5 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5d86d50 6413:com.enhance.gameservice/u0a106}
,05-25 13:51:20.985  3549  3568 V AlarmManager:  remove PendingIntent] PendingIntent{e0043ea: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:20.985  4122  4122 I wpa_supplicant: Blacklist: Clear (all) 
05-25 13:51:20.985 10165 10165 D InjectionManager: InjectionManager
05-25 13:51:20.985  4122  4122 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
05-25 13:51:20.985 10165 10165 D InjectionManager: fillFeatureStoreMap com.sec.android.provider.badge
,05-25 13:51:20.985 10165 10165 I InjectionManager: Constructor com.sec.android.provider.badge, Feature store :{}
,05-25 13:51:20.985 10165 10165 I InjectionManager: featureStore :{}
,05-25 13:51:20.985 10140 10140 I BNRClientProivder, VERSION : 1.7.5: register - xml6 quick_backup : Email, QJ5JBlRnP9, com.samsung.android.email.provider.service.sCloudBNRService
,05-25 13:51:20.995 10140 10140 I QBNRClientHelper: init SyncClientHelper : Email
,05-25 13:51:20.995 10181 10181 E Zygote  : v2
05-25 13:51:20.995 10181 10181 I libpersona: KNOX_SDCARD checking this for 10112
05-25 13:51:20.995 10181 10181 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
05-25 13:51:20.995 10181 10181 I libpersona: KNOX_SDCARD not a persona
05-25 13:51:20.995  3549  3568 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1248000  uid : 1000  pid : 3549  pkgName : BADGE_UPDATE@CPU_MIN@1
,05-25 13:51:20.995 10181 10181 E Zygote  : accessInfo : 0
05-25 13:51:20.995 10181 10181 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.talk 
05-25 13:51:20.995  3549  3603 I ActivityManager: Start proc 10181:com.google.android.talk/u0a112 for broadcast-3 com.google.android.talk/com.google.android.apps.hangouts.service.GcmStateReceiver
,05-25 13:51:21.005 10165 10176 D BaseReflect: null getOwnClass TEST
,05-25 13:51:21.005 10165 10176 D MethodReflector: android.content.ContentResolver getClass TEST
05-25 13:51:21.005 10165 10176 D BaseReflect: class android.content.ContentResolver isSupportClass TEST
05-25 13:51:21.005 10165 10176 D BaseReflect: class android.content.ContentResolver getOwnClass TEST
,05-25 13:51:21.015 10181 10181 D TimaKeyStoreProvider: TimaSignature is unavailable
,05-25 13:51:21.015 10181 10181 D ActivityThread: Added TimaKeyStore provider
,05-25 13:51:21.035  3549  3603 D ActivityManager:  getDeferredInfo final delay 300
,05-25 13:51:21.035  3549  3601 D libgps  : agps_ril_update_network_state: Waiting for IPC connection...
,05-25 13:51:21.035  4273  4273 D Launcher.Model: reloadBadges entered.
,05-25 13:51:21.035 10165 10176 D MethodReflector: notifyChange is called
,05-25 13:51:21.035  4273  4273 D Launcher.Model: reloadBadges entered.
,05-25 13:51:21.035 10165 10176 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
05-25 13:51:21.035 10165 10176 D BadgeProvider: sendNotify, [notify] : null
,05-25 13:51:21.035 10165 10176 D BadgeProvider: update, getCallingPackage() : com.samsung.android.email.provider
05-25 13:51:21.035 10165 10176 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
05-25 13:51:21.035 10165 10176 D BadgeProvider: update, [uri.query] : null
05-25 13:51:21.035 10165 10176 D BadgeProvider: update, [BadgeCount] : badgecount=0
05-25 13:51:21.035  3549  4066 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{bca66db u0 com.google.android.gcm.DISCONNECTED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8e6b578 10181:com.google.android.talk/u0a112}
05-25 13:51:21.035 10165 10176 D BadgeProvider: update, [UpdateCount] : 1
05-25 13:51:21.045  3157  3606 D Netd    : Iface wlan0 link up
05-25 13:51:21.045  3157  3606 D Netd    : Iface wlan0 link up
,05-25 13:51:21.045  3549  3614 D Tethering: interfaceLinkStateChanged wlan0, true
05-25 13:51:21.045  3549  3614 D Tethering: interfaceStatusChanged wlan0, true
05-25 13:51:21.045  4905  4920 D PdnController: Interface Changed wlan0 link up
,05-25 13:51:21.045  3549  3614 D Tethering: interfaceLinkStateChanged wlan0, true
05-25 13:51:21.045  3549  3614 D Tethering: interfaceStatusChanged wlan0, true
,05-25 13:51:21.045  4905  5185 D PdnController: Interface Changed wlan0 link up
,05-25 13:51:21.045 10181 10181 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.google.android.talk rsrc of package com.google.android.talk
,05-25 13:51:21.045  3549  6068 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:21.045 10181 10181 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
05-25 13:51:21.045  3549  4286 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-25 13:51:21.055 10181 10181 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:51:21.055 10165 10176 D BadgeProvider: query, [selection] : null
,05-25 13:51:21.055  3549  3981 V AlarmManager:  remove PendingIntent] PendingIntent{8560451: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.055 10181 10181 I InjectionManager: Inside getClassLibPath caller 
,05-25 13:51:21.055  3157  3606 D Netd    : Iface p2p0 link down
,05-25 13:51:21.055  3549  3614 D Tethering: interfaceLinkStateChanged p2p0, false
05-25 13:51:21.055  3549  3614 D Tethering: interfaceStatusChanged p2p0, false
,05-25 13:51:21.065  4905  9487 D PdnController: Interface Changed p2p0 link down
,05-25 13:51:21.065  4273  4365 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.email.provider = 0
05-25 13:51:21.065  4273  4365 D BadgeCache: 1. updateBadgeCounts: com.android.mms = 0
05-25 13:51:21.065  4273  4365 D BadgeCache: 1. updateBadgeCounts: com.sec.android.app.samsungapps = 0
05-25 13:51:21.065  4273  4365 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 1
05-25 13:51:21.065  4273  4365 D BadgeCache: 2. updateBadgeCounts: com.android.settings/.Settings = 1
05-25 13:51:21.065  4273  4365 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 1
05-25 13:51:21.065  4273  4365 D BadgeCache: 2. updateBadgeCounts: com.android.settings/.GridSettings = 1
05-25 13:51:21.065  4273  4365 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.sm = 0
,05-25 13:51:21.065  3549  4931 V AlarmManager:  remove PendingIntent] PendingIntent{996b4b6: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.065 10181 10181 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm64
,05-25 13:51:21.065  3549  4420 V AlarmManager:  remove PendingIntent] PendingIntent{afe95b7: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.075  3549  4435 D RCPManagerService: exchangeData() failure , invalid userId
,05-25 13:51:21.075 10140 10140 D InjectionManager: InjectionManager
05-25 13:51:21.075 10140 10140 D InjectionManager: fillFeatureStoreMap com.samsung.android.email.provider
05-25 13:51:21.075 10140 10140 I InjectionManager: Constructor com.samsung.android.email.provider, Feature store :{}
05-25 13:51:21.075 10140 10140 I InjectionManager: featureStore :{}
,05-25 13:51:21.085 10181 10181 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.google.android.talk rsrc of package com.google.android.talk
,05-25 13:51:21.085  3549  4367 V AlarmManager:  remove PendingIntent] PendingIntent{28db124: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
05-25 13:51:21.085 10165 10193 D BadgeProvider: query, [selection] : null
,05-25 13:51:21.085  4273  4365 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.email.provider = 0
05-25 13:51:21.085  4273  4365 D BadgeCache: 1. updateBadgeCounts: com.android.mms = 0
05-25 13:51:21.085  4273  4365 D BadgeCache: 1. updateBadgeCounts: com.sec.android.app.samsungapps = 0
05-25 13:51:21.085  4273  4365 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 1
05-25 13:51:21.085  4273  4365 D BadgeCache: 2. updateBadgeCounts: com.android.settings/.Settings = 1
05-25 13:51:21.085  4273  4365 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 1
05-25 13:51:21.085  4273  4365 D BadgeCache: 2. updateBadgeCounts: com.android.settings/.GridSettings = 1
05-25 13:51:21.085  4273  4365 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.sm = 0
,05-25 13:51:21.085  3549  4367 V AlarmManager:  remove PendingIntent] PendingIntent{825948d: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.085  3549  3986 V AlarmManager:  remove PendingIntent] PendingIntent{d516642: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.105  3549  3981 V AlarmManager:  remove PendingIntent] PendingIntent{c13a48e: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.105 10053 10197 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,05-25 13:51:21.115  3549  4170 V AlarmManager:  remove PendingIntent] PendingIntent{45484af: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.115 10053 10197 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,05-25 13:51:21.115  3549  3568 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:21.115  3549  3567 V AlarmManager:  remove PendingIntent] PendingIntent{6c400bc: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
05-25 13:51:21.115  3549  3568 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:21.115  3549  3568 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:21.115  3549  3568 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:21.115  3549  3568 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:21.115  3549  3568 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:21.115  3549  3568 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:21.115  3549  3568 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:21.115  3549  3568 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:21.115  3549  3568 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:21.115  3549  3568 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:21.115  3549  3568 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
05-25 13:51:21.115  3549  3568 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:21.115  3549  3568 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:21.115  3549  3568 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:51:21.125  3549  4286 V AlarmManager:  remove PendingIntent] PendingIntent{715c845: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.125  3549  4066 V AlarmManager:  remove PendingIntent] PendingIntent{1a97b9a: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.125  3549  4433 V AlarmManager:  remove PendingIntent] PendingIntent{beebccb: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.125  3549  3567 V AlarmManager:  remove PendingIntent] PendingIntent{22e6ca8: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.125  3549  4286 V AlarmManager:  remove PendingIntent] PendingIntent{f51ab54: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.135  3549  4170 V AlarmManager:  remove PendingIntent] PendingIntent{ef1bafd: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.135  3549  4432 V AlarmManager:  remove PendingIntent] PendingIntent{93e3f2: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.145  3549  4066 V AlarmManager:  remove PendingIntent] PendingIntent{d97fa43: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.145 10181 10181 I Babel_telephony: TeleModule.onApplicationCreate
,05-25 13:51:21.145  3549  3986 V AlarmManager:  remove PendingIntent] PendingIntent{ac828c0: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.145  3549  3568 V AlarmManager:  remove PendingIntent] PendingIntent{82409f9: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.155  3549  4286 V AlarmManager:  remove PendingIntent] PendingIntent{1f84d3e: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.155 10181 10209 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
05-25 13:51:21.155 10181 10209 I Babel_SMS: MmsConfig.loadMmsSettings
,05-25 13:51:21.155  3549  3981 V AlarmManager:  remove PendingIntent] PendingIntent{a35f79f: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
05-25 13:51:21.155 10181 10209 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/uaprof, mUaProfUrl=http://wap.samsungmobile.com/uaprof/uaprof.rdf
05-25 13:51:21.155 10181 10209 I Babel_SMS: MmsConfig.loadFromDatabase
,05-25 13:51:21.155  3549  4066 V AlarmManager:  remove PendingIntent] PendingIntent{e6710ec: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.165  3549  3567 V AlarmManager:  remove PendingIntent] PendingIntent{b924cb5: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.165  3549  4285 V AlarmManager:  remove PendingIntent] PendingIntent{98c6ebb: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.165  3549  4435 V AlarmManager:  remove PendingIntent] PendingIntent{a2a4fd8: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.175 10181 10181 I Babel_Crash: Startup - clean
,05-25 13:51:21.175 10181 10209 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
05-25 13:51:21.175 10181 10209 I Babel_SMS: MmsConfig.loadFromResources
,05-25 13:51:21.175  3549  4066 V AlarmManager:  remove PendingIntent] PendingIntent{167ff31: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.175  3549  4931 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.SmsReceiver newState = 2 callingPackage = 10112
,05-25 13:51:21.175  3549  4170 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.MmsWapPushReceiver newState = 2 callingPackage = 10112
,05-25 13:51:21.175  3549  3567 V AlarmManager:  remove PendingIntent] PendingIntent{9eec616: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.175  3549  4285 V AlarmManager:  remove PendingIntent] PendingIntent{6093b97: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.175  3549  4430 V AlarmManager:  remove PendingIntent] PendingIntent{fe09184: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.185 10181 10209 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
05-25 13:51:21.185 10181 10209 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/uaprof, mUaProfUrl=http://wap.samsungmobile.com/uaprof/uaprof.rdf
,05-25 13:51:21.185  3549  4435 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.AbortSmsReceiver newState = 2 callingPackage = 10112
,05-25 13:51:21.185  3549  4931 V AlarmManager:  remove PendingIntent] PendingIntent{f0c5d6d: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.195  3549  3567 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver newState = 2 callingPackage = 10112
,05-25 13:51:21.195  3549  3568 V AlarmManager:  remove PendingIntent] PendingIntent{c092da2: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.195  3549  4170 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.service.NoConfirmationSmsSendService newState = 1 callingPackage = 10112
,05-25 13:51:21.195  3549  4286 V AlarmManager:  remove PendingIntent] PendingIntent{91bfa33: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.195  3549  3981 V AlarmManager:  remove PendingIntent] PendingIntent{d9741f0: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.205  3549  4931 V AlarmManager:  remove PendingIntent] PendingIntent{f1e6369: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.205 10181 10181 I Babel_Prime: startMemoryMonitor
,05-25 13:51:21.205 10181 10181 I Babel_Prime: isMemoryEnabled=false
05-25 13:51:21.205 10181 10181 I Babel_Prime: isTimerEnabled=true
,05-25 13:51:21.205  3549  4433 V AlarmManager:  remove PendingIntent] PendingIntent{e7081ee: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.205  3549  4285 V AlarmManager:  remove PendingIntent] PendingIntent{992068f: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.205  3549  4286 V AlarmManager:  remove PendingIntent] PendingIntent{2c68d1c: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.205  3549  3981 V AlarmManager:  remove PendingIntent] PendingIntent{d30cd25: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.215  3549  4066 V AlarmManager:  remove PendingIntent] PendingIntent{be6cefa: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.215  3549  4433 V AlarmManager:  remove PendingIntent] PendingIntent{3b27cab: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.215 10181 10181 D InjectionManager: InjectionManager
05-25 13:51:21.215 10181 10181 D InjectionManager: fillFeatureStoreMap com.google.android.talk
,05-25 13:51:21.215 10181 10181 I InjectionManager: Constructor com.google.android.talk, Feature store :{}
05-25 13:51:21.215 10181 10181 I InjectionManager: featureStore :{}
,05-25 13:51:21.225  3549  3603 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c3d5f08 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{14616a1 9936:com.thaliproject.thalitest/u0a74}
,05-25 13:51:21.225  3549  4286 V AlarmManager:  remove PendingIntent] PendingIntent{742e0c6: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.225  3549  3981 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:21.225  3549  3981 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:21.225  3549  3981 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:21.225  3549  3981 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:21.225  3549  3981 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:21.225  3549  3981 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:21.225  3549  3981 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:21.225  3549  3981 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:21.225  3549  3981 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:21.225  3549  3981 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:21.225  3549  3981 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:21.225  3549  3981 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
05-25 13:51:21.225  3549  3981 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:21.225  3549  3981 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:21.225  3549  3981 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:51:21.235  3549  4367 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c3d5f08 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a61135 3549:system/1000}
,05-25 13:51:21.235  3549  4931 V AlarmManager:  remove PendingIntent] PendingIntent{71a3887: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.235  3549  3549 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c3d5f08 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c4f3aaa 4628:com.google.android.gms/u0a19}
,05-25 13:51:21.245  4628  4628 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,05-25 13:51:21.245  4628  5663 I iu.UploadsManager: num queued entries: 0
,05-25 13:51:21.245  4628  5663 I iu.UploadsManager: num updated entries: 0
05-25 13:51:21.245  4628  5663 I iu.SyncManager: NEXT; no task
,05-25 13:51:21.245  3549  4285 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c3d5f08 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c4f3aaa 4628:com.google.android.gms/u0a19}
,05-25 13:51:21.255 10181 10181 D Babel   : onCreate: Shutdown runnable posted in onCreate with a delay of 5000 ms.
,05-25 13:51:21.255  3549  4285 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c3d5f08 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f3ae3d9 4287:com.google.android.gms.persistent/u0a19}
,05-25 13:51:21.255 10181 10181 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in com.google.android.talk rsrc of package com.google.android.gms
,05-25 13:51:21.265  3549  3568 V AlarmManager:  remove PendingIntent] PendingIntent{657d623: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.265 10181 10181 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:51:21.265 10181 10181 I InjectionManager: Inside getClassLibPath caller 
,05-25 13:51:21.275  3549  3603 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c3d5f08 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1b75d8f 7288:com.osp.app.signin/u0a41}
,05-25 13:51:21.275  7288  7288 I SA      : [OR] onReceive log=[SA = 2.2.02-12 V = 23 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = pl_PL CSC = XEO MCC = 0 MNC 0 T = user DEVICE = herolte P = heroltexx I = MMB29K M = SM-G930F OKLEFT false DIS MMB29K.G930FXXU1BPJG PSS = 5.059173621445858  ]
05-25 13:51:21.275  7288  7288 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
05-25 13:51:21.275  7288  7288 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,05-25 13:51:21.275  3549  4066 V AlarmManager:  remove PendingIntent] PendingIntent{8b70720: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.275  7288  7288 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
05-25 13:51:21.275  7288  7288 I SA      : [OR] == isSIMCardReady false ==
,05-25 13:51:21.275  7288  7288 I SA      : [SCU] == networkStateCheck == false
05-25 13:51:21.275  7288  7288 I SA      : [OR] onReceive END
,05-25 13:51:21.275  3549  4430 V AlarmManager:  remove PendingIntent] PendingIntent{cd9f8d9: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.285 10181 10181 W System  : ClassLoader referenced unknown path: /system/priv-app/GmsCore/lib/arm64
,05-25 13:51:21.285  3549  3603 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{377429e u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5d86d50 6413:com.enhance.gameservice/u0a106}
,05-25 13:51:21.295  3549  3603 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{447b17f u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{14616a1 9936:com.thaliproject.thalitest/u0a74}
,05-25 13:51:21.295  3549  4285 V AlarmManager:  remove PendingIntent] PendingIntent{1d5754c: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
05-25 13:51:21.295  3549  3981 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:21.295  3549  3981 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:21.295  3549  3981 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:51:21.295  3549  3981 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:21.295  3549  3981 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:21.295  3549  3981 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:21.295  3549  3981 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:51:21.295  3549  3981 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:21.295  3549  3981 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:21.295  3549  3981 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:21.295  3549  3981 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:21.295  3549  3981 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
05-25 13:51:21.295  3549  3981 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:21.295  3549  3981 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:21.295  3549  3981 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:51:21.305  3549  3603 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6684995 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{44442de 4889:com.samsung.android.providers.context/u0a7}
,05-25 13:51:21.305  3549  3568 V AlarmManager:  remove PendingIntent] PendingIntent{f10eaaa: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.315  3549  3838 V AlarmManager:  remove PendingIntent] PendingIntent{b2fe69b: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.315  3549  3567 V AlarmManager:  remove PendingIntent] PendingIntent{28a9a38: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.315  3549  4435 V AlarmManager:  remove PendingIntent] PendingIntent{f50ea11: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.325  3549  3981 V AlarmManager:  remove PendingIntent] PendingIntent{6eb0776: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.325  3549  4367 V AlarmManager:  remove PendingIntent] PendingIntent{99c5177: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.325  3549  3838 V AlarmManager:  remove PendingIntent] PendingIntent{16b21e4: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.325  3549  3567 V AlarmManager:  remove PendingIntent] PendingIntent{949164d: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.335  3549  4435 V AlarmManager:  remove PendingIntent] PendingIntent{5782502: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.335 10181 10181 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,05-25 13:51:21.335  3549  3981 V AlarmManager:  remove PendingIntent] PendingIntent{fa8e13: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.335  3549  3603 D ActivityManager:  getDeferredInfo final delay 300
,05-25 13:51:21.335  3549  4066 V AlarmManager:  remove PendingIntent] PendingIntent{7aa7850: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.335  3549  4430 V AlarmManager:  remove PendingIntent] PendingIntent{21dca49: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.335  3549  4931 V AlarmManager:  remove PendingIntent] PendingIntent{7c78f4e: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.345  3549  4170 V AlarmManager:  remove PendingIntent] PendingIntent{1f5f86f: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.345  3549  4433 V AlarmManager:  remove PendingIntent] PendingIntent{c46c97c: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.345  3549  3568 V AlarmManager:  remove PendingIntent] PendingIntent{d6fc205: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.345 10181 10181 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,05-25 13:51:21.345  3549  4432 V AlarmManager:  remove PendingIntent] PendingIntent{a91525a: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.345  3549  4931 V AlarmManager:  remove PendingIntent] PendingIntent{293ac8b: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.345  3549  4420 V AlarmManager:  remove PendingIntent] PendingIntent{a0e8667: PendingIntentRecord{fcccc14 com.google.android.talk startService}}
,05-25 13:51:21.345  3549  4066 V AlarmManager:  remove PendingIntent] PendingIntent{bd92cbd: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.355  3549  4170 V AlarmManager:  remove PendingIntent] PendingIntent{e47d2b2: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
05-25 13:51:21.355 10181 10181 D Babel   : Idle: Shutdown runnable posted in release with a delay of 5000 ms.
,05-25 13:51:21.355  3549  4420 V AlarmManager:  remove PendingIntent] PendingIntent{e732203: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.355  3549  4430 V AlarmManager:  remove PendingIntent] PendingIntent{cb49580: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.355  3549  3986 V AlarmManager:  remove PendingIntent] PendingIntent{f70d7b9: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.355  3549  3838 V AlarmManager:  remove PendingIntent] PendingIntent{6dc67fe: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.355  3549  3567 V AlarmManager:  remove PendingIntent] PendingIntent{ffbdb5f: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.355  3549  4435 V AlarmManager:  remove PendingIntent] PendingIntent{58d89ac: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.355  3549  4432 V AlarmManager:  remove PendingIntent] PendingIntent{43e3675: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.355  3549  4367 V AlarmManager:  remove PendingIntent] PendingIntent{693060a: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.355  3549  4286 V AlarmManager:  remove PendingIntent] PendingIntent{e2cce7b: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.365  3549  4170 V AlarmManager:  remove PendingIntent] PendingIntent{e1f9498: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.365  3549  4433 V AlarmManager:  remove PendingIntent] PendingIntent{848c4f1: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.365  3549  3568 V AlarmManager:  remove PendingIntent] PendingIntent{66378d6: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.365  3549  4066 V AlarmManager:  remove PendingIntent] PendingIntent{2afd757: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.365  3549  4931 V AlarmManager:  remove PendingIntent] PendingIntent{cc56244: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.365  3549  4285 V AlarmManager:  remove PendingIntent] PendingIntent{893bf2d: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.365  3549  3981 V AlarmManager:  remove PendingIntent] PendingIntent{4f64c62: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.365  3549  4420 V AlarmManager:  remove PendingIntent] PendingIntent{df091f3: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.365  3549  4430 V AlarmManager:  remove PendingIntent] PendingIntent{d85eb0: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.365  3549  3986 V AlarmManager:  remove PendingIntent] PendingIntent{51a2129: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.365  3549  3838 V AlarmManager:  remove PendingIntent] PendingIntent{f0ccae: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.375  3549  3567 V AlarmManager:  remove PendingIntent] PendingIntent{1785a4f: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.375  3549  4435 V AlarmManager:  remove PendingIntent] PendingIntent{3dcb5dc: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.375  3549  4432 V AlarmManager:  remove PendingIntent] PendingIntent{88aa6e5: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.375  3549  4367 V AlarmManager:  remove PendingIntent] PendingIntent{c0105ba: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.375  3549  4420 V AlarmManager:  remove PendingIntent] PendingIntent{40a4c6b: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.375  9936 10036 D BluetoothAdapter: STATE_ON
,05-25 13:51:21.375  9936 10036 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-25 13:51:21.375  9936 10036 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-25 13:51:21.375  9936 10036 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-25 13:51:21.375  9936 10036 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
05-25 13:51:21.375  9936 10036 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-25 13:51:21.375  9936 10036 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
05-25 13:51:21.375  9936 10036 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
05-25 13:51:21.375  9936 10036 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
05-25 13:51:21.375  9936 10036 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,05-25 13:51:21.375  3549  4286 V AlarmManager:  remove PendingIntent] PendingIntent{16d53c8: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
05-25 13:51:21.375  9936 10036 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
05-25 13:51:21.375  9936  9999 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:51:21.375  3549  4931 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,05-25 13:51:21.375  3549  4931 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
05-25 13:51:21.375  3549  3986 V AlarmManager:  remove PendingIntent] PendingIntent{fc3cc61: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.375  3549  4931 D WifiService: setWifiEnabled: true pid=9936, uid=10074
05-25 13:51:21.375  3549  4931 W ActivityManager: Permission Denial: getCurrentUser() from pid=9936, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
05-25 13:51:21.375  3549  4931 W WifiService: Failed getting userId using ActivityManagerNative
05-25 13:51:21.375  3549  4931 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9936, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
05-25 13:51:21.375  3549  4931 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-25 13:51:21.375  3549  4931 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
05-25 13:51:21.375  3549  4931 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
05-25 13:51:21.375  3549  4931 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
05-25 13:51:21.375  3549  4931 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
,05-25 13:51:21.375  3549  4931 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
05-25 13:51:21.375  3549  3567 V AlarmManager:  remove PendingIntent] PendingIntent{2a9c386: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
05-25 13:51:21.375  3549  3859 D WifiBigDataLog: getJsonFormat() - feature : ONOF
05-25 13:51:21.375  3549  4931 D SettingsProvider: isChangeAllowed() : name = wifi_on
05-25 13:51:21.375  3549  3859 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
05-25 13:51:21.375  3549  3859 D WifiBigDataLog: init : 
05-25 13:51:21.375  3549  3863 D WifiController: [FCC]setFccChannel() is called !!!
05-25 13:51:21.375  3549  3863 D WifiStateMachine: setFccChannel: channel = 0
05-25 13:51:21.375  3549  3863 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
05-25 13:51:21.385  3549  3863 D SecContentProvider: insert(), uri = 2
,05-25 13:51:21.385  3549  3603 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b7f4447 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{44442de 4889:com.samsung.android.providers.context/u0a7}
,05-25 13:51:21.395  3549  4430 V AlarmManager:  remove PendingIntent] PendingIntent{1e7e474: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.395  3549  4170 V AlarmManager:  remove PendingIntent] PendingIntent{d0fcd9d: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.395  3549  4066 V AlarmManager:  remove PendingIntent] PendingIntent{4ce9212: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.395  3549  4931 V AlarmManager:  remove PendingIntent] PendingIntent{861dde3: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.405  3549  4420 V AlarmManager:  remove PendingIntent] PendingIntent{3d8d3e0: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.405  3549  4286 V AlarmManager:  remove PendingIntent] PendingIntent{320a699: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.405  3549  4432 V AlarmManager:  remove PendingIntent] PendingIntent{affbd5e: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.405  3549  3986 V AlarmManager:  remove PendingIntent] PendingIntent{f4a753f: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.405  3549  4435 V AlarmManager:  remove PendingIntent] PendingIntent{274e0c: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.405  3549  3981 V AlarmManager:  remove PendingIntent] PendingIntent{3cc1355: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.405  3549  4430 V AlarmManager:  remove PendingIntent] PendingIntent{486516a: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.405  3549  4170 V AlarmManager:  remove PendingIntent] PendingIntent{bfb265b: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.405  3549  4367 V AlarmManager:  remove PendingIntent] PendingIntent{5013ef8: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.405  3549  3567 V AlarmManager:  remove PendingIntent] PendingIntent{e878fd1: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.415  3549  3838 V AlarmManager:  remove PendingIntent] PendingIntent{a301a36: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.415  3549  4285 V AlarmManager:  remove PendingIntent] PendingIntent{a3bcd37: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.415  3549  4433 V AlarmManager:  remove PendingIntent] PendingIntent{38752a4: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.415  3549  3568 V AlarmManager:  remove PendingIntent] PendingIntent{aa4580d: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.415  3549  4066 V AlarmManager:  remove PendingIntent] PendingIntent{1dba3c2: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.415  3549  4931 V AlarmManager:  remove PendingIntent] PendingIntent{7605d3: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.415  3549  4420 V AlarmManager:  remove PendingIntent] PendingIntent{c38f510: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.415  3549  4286 V AlarmManager:  remove PendingIntent] PendingIntent{94b6809: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:21.575  3157  3606 D Netd    : Iface wlan0 link down
05-25 13:51:21.575  3549  3614 D Tethering: interfaceLinkStateChanged wlan0, false
05-25 13:51:21.575  3549  3614 D Tethering: interfaceStatusChanged wlan0, false
,05-25 13:51:21.575  4905  5185 D PdnController: Interface Changed wlan0 link down
05-25 13:51:21.575  4905  5185 D PdnController: Removed Interface [wlan0] For Network [1]
,05-25 13:51:21.575  3549  3614 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:51:21.585  4905  5185 D PdnController: CONNECTIVITY_ACTION: networkType 1 isConnected false
05-25 13:51:21.585  4905  5185 D PdnController: isSuspended [false] networktype [1]
05-25 13:51:21.585  3549  3614 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:51:21.585  4905  5185 D PdnController: isPdnUp  [false] networktype [1]
05-25 13:51:21.585  4905  5185 D PdnController: Ignore Notifying Same Result to LocalIP Registrants!
,05-25 13:51:21.625  4122  4122 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,05-25 13:51:21.635  3549  3603 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:51:21.655 10220 10220 E Zygote  : v2
05-25 13:51:21.655 10220 10220 I libpersona: KNOX_SDCARD checking this for 1000
05-25 13:51:21.655 10220 10220 I libpersona: KNOX_SDCARD not a persona
,05-25 13:51:21.655 10220 10220 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-25 13:51:21.655 10220 10220 E Zygote  : accessInfo : 0
,05-25 13:51:21.655  3549  3603 I ActivityManager: Start proc 10220:com.sec.android.diagmonagent/1000 for broadcast-5 com.sec.android.diagmonagent/.DiagMonConnectivityChangeReciever
,05-25 13:51:21.675  3549  3568 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-25 13:51:21.675  3549  3568 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4299, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:51:21.675  3549  3568 D BatteryService: online:4, current avg:12, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:107
05-25 13:51:21.685  3549  3549 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:51:21.685  3549  3549 I MotionRecognitionService: Plugged
05-25 13:51:21.685  3549  3549 D MotionRecognitionService:   cableConnection= 1
05-25 13:51:21.685  3549  3549 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:51:21.685  3549  3549 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:51:21.685  3549  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:51:21.685  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,05-25 13:51:21.685  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
05-25 13:51:21.685 10220 10220 D TimaKeyStoreProvider: TimaSignature is unavailable
05-25 13:51:21.685 10220 10220 D ActivityThread: Added TimaKeyStore provider
,05-25 13:51:21.695  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:51:21.695  4905  4905 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:51:21.705  4905  4905 D BatteryMonitor: new battery level: 100
,05-25 13:51:21.705 10053 10053 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-25 13:51:21.705 10053 10095 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-25 13:51:21.715  3549  4931 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{1043fd5 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ec43a0e 10220:com.sec.android.diagmonagent/1000}
,05-25 13:51:21.715  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:21.715  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:21.715 10220 10220 W ResourcesManager: getTopLevelResources: /system/priv-app/DiagMonAgent/DiagMonAgent.apk / 1.0 running in com.sec.android.diagmonagent rsrc of package com.sec.android.diagmonagent
,05-25 13:51:21.725  3549  3567 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-25 13:51:21.725 10220 10220 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-25 13:51:21.725 10220 10220 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:51:21.725  3549  3859 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,05-25 13:51:21.725  3549  3549 D WifiNotificationController: SHOW_NOTI_MESSAGE : 9, visible : false, ssid : <unknown ssid>, targetSSID : null, netId : -1, titleType : -1
05-25 13:51:21.725  3549  3549 D WifiNotificationController: SHOW_NOTI_MESSAGE : 13, visible : false, ssid : <unknown ssid>, targetSSID : null, netId : -1, titleType : 0
05-25 13:51:21.725  3549  3549 D WifiNotificationController: showCaptivePortalDisabledStatus with ssid/visible/title:null/false/0
,05-25 13:51:21.725  3549  3549 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
05-25 13:51:21.725  3549  3549 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
05-25 13:51:21.725  3549  3864 D HS20StateMachine: WIFI_STATE_DISABLED
05-25 13:51:21.725  3549  3864 D HS20StateMachine: CMD_HOTSPOT20_DISABLE
05-25 13:51:21.725  3549  3867 I WifiHs20Service: Message received 5011
05-25 13:51:21.725  3549  3864 D HS20StateMachine: enter : DisablingState
05-25 13:51:21.725  3549  3866 D HS20SubscriptionManager: Received CMD_RELEASE_TLS, flag=1
,05-25 13:51:21.725  3549  3871 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,05-25 13:51:21.725  3549  3549 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
05-25 13:51:21.725  3949  4133 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
05-25 13:51:21.735  3549  3864 D HS20StateMachine: enter : DisabledState
05-25 13:51:21.735  4260  4621 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,05-25 13:51:21.735  3949  3949 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
05-25 13:51:21.735  3949  3949 I HotspotTile: Provider is not defined returning false
05-25 13:51:21.735  4260  4621 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
05-25 13:51:21.735  3949  3949 D HotspotTile: onReceive : 1, 0
05-25 13:51:21.735  3549  3871 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,05-25 13:51:21.735 10220 10220 I InjectionManager: Inside getClassLibPath caller 
,05-25 13:51:21.735  4287  5122 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,05-25 13:51:21.745  9936  9936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
05-25 13:51:21.745  3549  3603 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8112c2f u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{14616a1 9936:com.thaliproject.thalitest/u0a74}
,05-25 13:51:21.745  3549  4435 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:21.745  3549  4435 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:21.745  3549  4435 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:21.745  3549  4435 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:21.745  3549  4435 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:21.745  3549  4435 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:21.745 10220 10220 W System  : ClassLoader referenced unknown path: /system/priv-app/DiagMonAgent/lib/arm64
05-25 13:51:21.745  3549  4435 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:21.745  3549  4435 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:21.745  3549  4435 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:21.745  3549  4435 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:21.745  3549  4435 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:21.745  3549  4435 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
05-25 13:51:21.745  3549  4435 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:21.745  3549  4435 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:21.745  3549  4435 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:51:21.755 10220 10220 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,05-25 13:51:21.845 10220 10220 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,05-25 13:51:21.855 10220 10220 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(72/onCreate)] DiagMon DM Application Start !
05-25 13:51:21.855 10220 10220 D InjectionManager: InjectionManager
05-25 13:51:21.855 10220 10220 D InjectionManager: fillFeatureStoreMap com.sec.android.diagmonagent
,05-25 13:51:21.855 10220 10220 I InjectionManager: Constructor com.sec.android.diagmonagent, Feature store :{}
05-25 13:51:21.855 10220 10220 I InjectionManager: featureStore :{}
05-25 13:51:21.855 10220 10220 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,05-25 13:51:21.855 10220 10220 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
05-25 13:51:21.855 10220 10220 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
05-25 13:51:21.855 10220 10220 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,05-25 13:51:21.855  3549  4286 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:51:21.875 10233 10233 E Zygote  : v2
05-25 13:51:21.875 10233 10233 I libpersona: KNOX_SDCARD checking this for 1000
05-25 13:51:21.875 10233 10233 I libpersona: KNOX_SDCARD not a persona
,05-25 13:51:21.875 10233 10233 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-25 13:51:21.875 10233 10233 E Zygote  : accessInfo : 0
,05-25 13:51:21.875  3549  4286 I ActivityManager: Start proc 10233:com.sec.knox.switcher/1000 for broadcast-5 com.sec.knox.switcher/.knoxusage.KnoxUsageReceiver
,05-25 13:51:21.875  3549  4286 I ActivityManager: Killing 8875:com.samsung.android.scloud:contentsync/5009 (adj 15): DHA:empty #33
,05-25 13:51:21.885  9936 10036 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,05-25 13:51:21.885  3549  3568 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,05-25 13:51:21.885  3549  3568 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,05-25 13:51:21.885  3549  3568 D WifiService: setWifiEnabled: true pid=9936, uid=10074
05-25 13:51:21.885  3549  3568 W ActivityManager: Permission Denial: getCurrentUser() from pid=9936, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
05-25 13:51:21.885  3549  3568 W WifiService: Failed getting userId using ActivityManagerNative
05-25 13:51:21.885  3549  3568 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9936, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
05-25 13:51:21.885  3549  3568 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-25 13:51:21.885  3549  3568 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
05-25 13:51:21.885  3549  3568 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
05-25 13:51:21.885  3549  3568 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
05-25 13:51:21.885  3549  3568 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
05-25 13:51:21.885  3549  3568 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
05-25 13:51:21.885  3549  3568 D SettingsProvider: isChangeAllowed() : name = wifi_on
05-25 13:51:21.885  3549  3863 D WifiController: [FCC]setFccChannel() is called !!!
05-25 13:51:21.885  3549  3863 D WifiStateMachine: setFccChannel: channel = 0
05-25 13:51:21.885  3549  3863 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
05-25 13:51:21.885  3549  3863 E WifiController: illegal state found both WifiController and WifiStateMachine
,05-25 13:51:21.905  3549  4066 D ActivityManager: cleanUpApplicationRecord -- 8875
05-25 13:51:21.905 10233 10233 D TimaKeyStoreProvider: TimaSignature is unavailable
05-25 13:51:21.905 10233 10233 D ActivityThread: Added TimaKeyStore provider
05-25 13:51:21.905  3549  4066 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.scloud, Auto Run ON
,05-25 13:51:21.915  3549  4285 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{1043fd5 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{620523c 10233:com.sec.knox.switcher/1000}
,05-25 13:51:21.915 10233 10233 W ResourcesManager: getTopLevelResources: /system/app/KnoxSwitcher/KnoxSwitcher.apk / 1.0 running in com.sec.knox.switcher rsrc of package com.sec.knox.switcher
,05-25 13:51:21.925  3549  4931 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-25 13:51:21.925 10233 10233 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-25 13:51:21.925 10233 10233 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:51:21.925  3549  3859 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,05-25 13:51:21.925 10233 10233 I InjectionManager: Inside getClassLibPath caller 
05-25 13:51:21.925  3549  3859 E WifiStateMachine: Error! unhandled message{ when=-5m2s326ms what=131156 target=com.android.internal.util.StateMachine$SmHandler }
05-25 13:51:21.925  3549  3859 E WifiHW  : ##################### set firmware type 0 #####################
,05-25 13:51:21.925  3157  3613 I WifiHW  : wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
,05-25 13:51:21.925  3157  3613 I WifiHW  : module is semco
05-25 13:51:21.925  3157  3613 E WifiHW  : ==========[WIFI] SEMCO MODULE ===========
05-25 13:51:21.925  3157  3613 I WifiHW  : wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
05-25 13:51:21.925  3157  3613 E WifiHW  : TEMP_FAILURE_RETRY complete
05-25 13:51:21.925  3157  3613 D SoftapController: Softap fwReload - Ok
,05-25 13:51:21.935  3157  3613 D CommandListener: Setting iface cfg
,05-25 13:51:21.935  3157  3613 D CommandListener: Trying to bring down wlan0
05-25 13:51:21.935  3157  3613 D CommandListener: Clearing all IP addresses on wlan0
,05-25 13:51:21.935 10233 10233 W System  : ClassLoader referenced unknown path: /system/app/KnoxSwitcher/lib/arm64
,05-25 13:51:21.935  3549  3859 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
05-25 13:51:21.935  3549  3859 D wifi    : Can not initialize the vendor function pointer table
05-25 13:51:21.935  3549  3859 E WifiNative-HAL: Could not start hal
05-25 13:51:21.935  3549  3859 E WifiStateMachine: Failed to start HAL
,05-25 13:51:21.935  3549  3859 E WifiHW  : supplicant_name : p2p_supplicant
,05-25 13:51:21.935 10233 10233 D KnoxUsageDB: getInstance - KnoxUsageDBHelper
05-25 13:51:21.935 10233 10233 D KnoxUsageDB: null == mDbHelperInstance - KnoxUsageDBHelper
,05-25 13:51:21.935 10233 10233 D InjectionManager: InjectionManager
05-25 13:51:21.935 10233 10233 D InjectionManager: fillFeatureStoreMap com.sec.knox.switcher
05-25 13:51:21.935 10233 10233 I InjectionManager: Constructor com.sec.knox.switcher, Feature store :{}
05-25 13:51:21.935 10233 10233 I InjectionManager: featureStore :{}
,05-25 13:51:21.935 10233 10233 I usagelog: received in receiver
05-25 13:51:21.935 10233 10233 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
,05-25 13:51:21.935 10233 10233 I KnoxUsageLogPro: premStatus:2
,05-25 13:51:21.945 10233 10233 I KnoxUsageLogPro: isEulaShown : false
05-25 13:51:21.945 10233 10233 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,05-25 13:51:21.945  3549  3981 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:51:21.955 10247 10247 E Zygote  : v2
05-25 13:51:21.955 10247 10247 I libpersona: KNOX_SDCARD checking this for 10135
05-25 13:51:21.955 10247 10247 I libpersona: KNOX_SDCARD not a persona
,05-25 13:51:21.955 10247 10247 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
05-25 13:51:21.955  3549  3981 I ActivityManager: Start proc 10247:com.samsung.android.sm.policy/u0a135 for broadcast-5 com.samsung.android.sm.policy/.PolicyBroadCastReceiver
,05-25 13:51:21.955 10247 10247 E Zygote  : accessInfo : 0
05-25 13:51:21.955 10247 10247 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.sm.policy 
05-25 13:51:21.955  3549  3981 I ActivityManager: Killing 8889:com.samsung.android.coreapps/5011 (adj 15): DHA:empty #33
,05-25 13:51:21.985 10247 10247 D TimaKeyStoreProvider: TimaSignature is unavailable
05-25 13:51:21.985 10247 10247 D ActivityThread: Added TimaKeyStore provider
05-25 13:51:21.985  3549  4433 D ActivityManager: cleanUpApplicationRecord -- 8889
,05-25 13:51:21.985  3549  4433 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.coreapps, Auto Run ON
,05-25 13:51:21.995  3549  3567 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{1043fd5 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b397bc5 10247:com.samsung.android.sm.policy/u0a135}
,05-25 13:51:22.005 10247 10247 W ResourcesManager: getTopLevelResources: /system/app/SCPMClient/SCPMClient.apk / 1.0 running in com.samsung.android.sm.policy rsrc of package com.samsung.android.sm.policy
,05-25 13:51:22.005  3549  4066 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-25 13:51:22.005 10247 10247 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-25 13:51:22.005 10247 10247 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:51:22.005 10247 10247 I InjectionManager: Inside getClassLibPath caller 
,05-25 13:51:22.015 10247 10247 W System  : ClassLoader referenced unknown path: /system/app/SCPMClient/lib/arm64
,05-25 13:51:22.025 10247 10247 D InjectionManager: InjectionManager
05-25 13:51:22.025 10247 10247 D InjectionManager: fillFeatureStoreMap com.samsung.android.sm.policy
,05-25 13:51:22.025 10247 10247 I InjectionManager: Constructor com.samsung.android.sm.policy, Feature store :{}
05-25 13:51:22.025 10247 10247 I InjectionManager: featureStore :{}
,05-25 13:51:22.035  3549  3859 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,05-25 13:51:22.035  3549  3549 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
,05-25 13:51:22.035  3549  3549 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
05-25 13:51:22.035  3549  3867 I WifiHs20Service: Message received 5011
05-25 13:51:22.035  3549  3601 D libgps  : agps_ril_update_network_state: Waiting for IPC connection - timeout
05-25 13:51:22.035  3549  3601 E libgps  : LIBGPS: Cannot communicate (write) with a GPSD
05-25 13:51:22.035  3549  3601 E libgps  : IPC Communication Error, ../../../../tmp/14982990_270314/allPartners/os/android/gps_interface/gpsi_client/GpsiClient.cpp:1710 agps_ril_update_network_state
05-25 13:51:22.035  3549  3601 D libgps  : agps_ril_update_network_availability: Waiting for IPC connection...
05-25 13:51:22.035  3549  3549 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,05-25 13:51:22.045  3949  4133 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
05-25 13:51:22.045  3549  3871 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,05-25 13:51:22.045  3949  3949 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
05-25 13:51:22.045  3949  3949 I HotspotTile: Provider is not defined returning false
,05-25 13:51:22.045  4260  4272 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
05-25 13:51:22.045  4260  4272 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
05-25 13:51:22.045  3549  3871 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
05-25 13:51:22.045  3949  3949 D HotspotTile: onReceive : 2, 0
,05-25 13:51:22.045  9936  9936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:51:22.045  3549  3603 I ActivityManager: Killing 8917:com.google.android.apps.photos/u0a129 (adj 15): DHA:empty #33
,05-25 13:51:22.055  3549  4286 D ActivityManager:  getDeferredInfo final delay 0
05-25 13:51:22.055  3549  3603 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a8de91a u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{14616a1 9936:com.thaliproject.thalitest/u0a74}
,05-25 13:51:22.055  3549  4435 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:22.055  3549  4435 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:22.055  3549  4435 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:22.055  3549  4435 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:22.055  3549  4435 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:22.055  3549  4435 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:22.055  3549  4435 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:22.055  3549  4435 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:22.055  3549  4435 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:22.055  3549  4435 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:22.055  3549  4435 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:22.055  3549  4435 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
05-25 13:51:22.055  3549  4435 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:22.055  3549  4435 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:22.055  3549  4435 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:51:22.065 10259 10259 E Zygote  : v2
05-25 13:51:22.065 10259 10259 I libpersona: KNOX_SDCARD checking this for 5005
05-25 13:51:22.065 10259 10259 I libpersona: KNOX_SDCARD not a persona
,05-25 13:51:22.065 10259 10259 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-25 13:51:22.065 10259 10259 E Zygote  : accessInfo : 0
05-25 13:51:22.065 10259 10259 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.app.FileShareClient 
,05-25 13:51:22.065  3549  4286 I ActivityManager: Start proc 10259:com.samsung.android.app.FileShareClient/5005 for broadcast-5 com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver
,05-25 13:51:22.075  3549  3981 D ActivityManager: cleanUpApplicationRecord -- 8917
,05-25 13:51:22.075  3549  3981 D ActivityManager: isAutoRunBlockedApp:: com.google.android.apps.photos, Auto Run ON
,05-25 13:51:22.085 10246 10246 I FIPS_bssl: FIPS approved mode (1) | 10246 | /system/bin/wpa_supplicant
,05-25 13:51:22.095 10246 10246 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
05-25 13:51:22.095 10246 10246 I wpa_supplicant: Successfully initialized wpa_supplicant
05-25 13:51:22.095 10246 10246 I wpa_supplicant: set_csc_config : ifname(wlan0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x20000), vendorssid_list()
05-25 13:51:22.095 10246 10246 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,05-25 13:51:22.095 10259 10259 D TimaKeyStoreProvider: TimaSignature is unavailable
,05-25 13:51:22.095 10259 10259 D ActivityThread: Added TimaKeyStore provider
,05-25 13:51:22.105  3549  3568 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{f8e5c4b u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cbe5628 10259:com.samsung.android.app.FileShareClient/5005}
,05-25 13:51:22.105 10259 10259 W ResourcesManager: getTopLevelResources: /system/app/AllshareFileShareClient/AllshareFileShareClient.apk / 1.0 running in com.samsung.android.app.FileShareClient rsrc of package com.samsung.android.app.FileShareClient
,05-25 13:51:22.105  3549  4435 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-25 13:51:22.105 10259 10259 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-25 13:51:22.115 10246 10246 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
05-25 13:51:22.115 10259 10259 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:51:22.115  3015  3015 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 10246
05-25 13:51:22.115  3015  3015 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
05-25 13:51:22.115 10246 10246 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
05-25 13:51:22.115 10246 10246 I wpa_supplicant: ssSupport state is = 1
05-25 13:51:22.115 10246 10246 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
05-25 13:51:22.115 10246 10246 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,05-25 13:51:22.115  3015  3015 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 10246
05-25 13:51:22.115  3015  3015 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x00000106
,05-25 13:51:22.115 10259 10259 I InjectionManager: Inside getClassLibPath caller 
,05-25 13:51:22.125 10246 10246 I SecureStorage: [INFO]: SPID(0x00000005)ss_id will be loaded by secure_storage_daemon: /system/bin/wpa_supplicant
,05-25 13:51:22.125 10259 10259 W System  : ClassLoader referenced unknown path: /system/app/AllshareFileShareClient/lib/arm64
,05-25 13:51:22.125 10259 10259 D InjectionManager: InjectionManager
,05-25 13:51:22.125 10259 10259 D InjectionManager: fillFeatureStoreMap com.samsung.android.app.FileShareClient
05-25 13:51:22.125 10259 10259 I InjectionManager: Constructor com.samsung.android.app.FileShareClient, Feature store :{}
05-25 13:51:22.125 10259 10259 I InjectionManager: featureStore :{}
,05-25 13:51:22.125 10259 10259 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,05-25 13:51:22.125 10259 10259 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,05-25 13:51:22.145 10259 10259 D FileShare-Client: Outbound.stopDelayTimer - 
,05-25 13:51:22.145  3549  4286 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:51:22.155 10272 10272 E Zygote  : v2
05-25 13:51:22.155 10272 10272 I libpersona: KNOX_SDCARD checking this for 5005
05-25 13:51:22.155 10272 10272 I libpersona: KNOX_SDCARD not a persona
,05-25 13:51:22.155 10272 10272 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
05-25 13:51:22.155  3549  4286 I ActivityManager: Start proc 10272:com.samsung.android.app.FileShareServer/5005 for broadcast-5 com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver
,05-25 13:51:22.155 10272 10272 E Zygote  : accessInfo : 0
05-25 13:51:22.155 10272 10272 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.app.FileShareServer 
05-25 13:51:22.155  3549  4286 I ActivityManager: Killing 8607:com.android.providers.calendar/u0a47 (adj 15): DHA:empty #33
,05-25 13:51:22.185 10272 10272 D TimaKeyStoreProvider: TimaSignature is unavailable
05-25 13:51:22.185 10272 10272 D ActivityThread: Added TimaKeyStore provider
,05-25 13:51:22.185  3549  4430 D ActivityManager: cleanUpApplicationRecord -- 8607
,05-25 13:51:22.185  3549  4430 D ActivityManager: isAutoRunBlockedApp:: com.android.providers.calendar, Auto Run ON
,05-25 13:51:22.195  3549  4931 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{f8e5c4b u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{63b0f41 10272:com.samsung.android.app.FileShareServer/5005}
,05-25 13:51:22.205 10272 10272 W ResourcesManager: getTopLevelResources: /system/app/AllshareFileShareServer/AllshareFileShareServer.apk / 1.0 running in com.samsung.android.app.FileShareServer rsrc of package com.samsung.android.app.FileShareServer
,05-25 13:51:22.205  3549  3981 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-25 13:51:22.205 10272 10272 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-25 13:51:22.205 10272 10272 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:51:22.205 10272 10272 I InjectionManager: Inside getClassLibPath caller 
,05-25 13:51:22.215 10272 10272 D InjectionManager: InjectionManager
05-25 13:51:22.215 10272 10272 D InjectionManager: fillFeatureStoreMap com.samsung.android.app.FileShareServer
05-25 13:51:22.215 10272 10272 I InjectionManager: Constructor com.samsung.android.app.FileShareServer, Feature store :{}
05-25 13:51:22.215 10272 10272 I InjectionManager: featureStore :{}
,05-25 13:51:22.215 10272 10272 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,05-25 13:51:22.215 10272 10272 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,05-25 13:51:22.215 10272 10272 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,05-25 13:51:22.225  3549  4430 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:51:22.235 10284 10284 E Zygote  : v2
05-25 13:51:22.235 10284 10284 I libpersona: KNOX_SDCARD checking this for 1000
05-25 13:51:22.235 10284 10284 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
05-25 13:51:22.235 10284 10284 I libpersona: KNOX_SDCARD not a persona
05-25 13:51:22.235  3549  4430 I ActivityManager: Start proc 10284:com.policydm/1000 for broadcast-5 com.policydm/.XDMBroadcastReceiver
,05-25 13:51:22.235 10284 10284 E Zygote  : accessInfo : 0
05-25 13:51:22.235  3549  4430 I ActivityManager: Killing 8434:com.google.android.talk:matchstick/u0a112 (adj 15): DHA:empty #33
,05-25 13:51:22.265  3549  4931 D ActivityManager: cleanUpApplicationRecord -- 8434
,05-25 13:51:22.265  3549  4931 D ActivityManager: isAutoRunBlockedApp:: com.google.android.talk, Auto Run ON
,05-25 13:51:22.265 10284 10284 D TimaKeyStoreProvider: TimaSignature is unavailable
05-25 13:51:22.265 10284 10284 D ActivityThread: Added TimaKeyStore provider
,05-25 13:51:22.275  3549  4433 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{c3d5f08 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3117ce6 10284:com.policydm/1000}
,05-25 13:51:22.285 10284 10284 W ResourcesManager: getTopLevelResources: /system/priv-app/SPDClient/SPDClient.apk / 1.0 running in com.policydm rsrc of package com.policydm
,05-25 13:51:22.285  3549  4420 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-25 13:51:22.285 10284 10284 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-25 13:51:22.285 10284 10284 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:51:22.295 10284 10284 I InjectionManager: Inside getClassLibPath caller 
,05-25 13:51:22.295 10284 10284 W System  : ClassLoader referenced unknown path: /system/priv-app/SPDClient/lib/arm64
,05-25 13:51:22.315 10284 10284 I FOTA    : [lIlIIlIIlIlllIIIIlll(108/llIIIIlllllIIllIIllI)] oms: /customer.xml
05-25 13:51:22.315 10284 10284 I FOTA    : [lIlIIlIIlIlllIIIIlll(199/lllIlIlIIIllIIlIllIl)] read default : /system/csc/customer.xml
,05-25 13:51:22.335 10284 10284 I FOTA    : [com.sec.android.policyagent.PolicyApplication(36/onCreate)] PolicyApplication onCreated!
,05-25 13:51:22.335 10284 10284 I DBG_POLICYDM: [com.policydm.db.XDB(1600/IllIlIIIIlIIlIIIllIl)] xdbDMffs_Init
,05-25 13:51:22.345 10284 10284 I DBG_POLICYDM: [com.policydm.db.llIIIIlllllIIllIIllI(142/llIIIIlllllIIllIIllI)] try read dbString
,05-25 13:51:22.385  9936 10036 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,05-25 13:51:22.395  3549  4430 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,05-25 13:51:22.395  3549  4430 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,05-25 13:51:22.395  3549  4430 D WifiService: setWifiEnabled: true pid=9936, uid=10074
,05-25 13:51:22.395  3549  4430 W ActivityManager: Permission Denial: getCurrentUser() from pid=9936, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
05-25 13:51:22.395  3549  4430 W WifiService: Failed getting userId using ActivityManagerNative
05-25 13:51:22.395  3549  4430 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9936, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
05-25 13:51:22.395  3549  4430 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-25 13:51:22.395  3549  4430 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
05-25 13:51:22.395  3549  4430 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
05-25 13:51:22.395  3549  4430 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
05-25 13:51:22.395  3549  4430 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
,05-25 13:51:22.405  3549  4430 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
05-25 13:51:22.405  3549  4430 D SettingsProvider: isChangeAllowed() : name = wifi_on
,05-25 13:51:22.405  3549  3863 D WifiStateMachine: setFccChannel: channel = 0
05-25 13:51:22.405  3549  3863 D WifiController: [FCC]setFccChannel() is called !!!
05-25 13:51:22.405  3549  3863 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
,05-25 13:51:22.405 10284 10284 I DBG_POLICYDM: [com.policydm.XDMService(161/llIIIIlllllIIllIIllI)] xdmUIHandelerInit
,05-25 13:51:22.405 10284 10284 I DBG_POLICYDM: [IlIIIllIlIIIlIIlIIlI(52/<init>)] 
,05-25 13:51:22.405 10284 10284 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1394 android.content.ContextWrapper.bindService:632 IlIIIllIlIIIlIIlIIlI.<init>:56 IIIlIIlllIlIlIIIIIII.llIIIIlllllIIllIIllI:19 IIIlIIlllIlIlIIIIIII.llllIIIllIlIIIIllllI:25 
,05-25 13:51:22.425  3549  4066 I ActivityManager: Start proc 10300:com.samsung.aasaservice/1000 for service com.samsung.aasaservice/.AASAService
,05-25 13:51:22.425 10300 10300 E Zygote  : v2
05-25 13:51:22.425 10300 10300 I libpersona: KNOX_SDCARD checking this for 1000
05-25 13:51:22.425 10284 10284 I DBG_POLICYDM: [IIIlIIlllIlIlIIIIIII(28/llllIIIllIlIIIIllllI)] AASAUpdater Init Success
05-25 13:51:22.425 10300 10300 I libpersona: KNOX_SDCARD not a persona
05-25 13:51:22.425 10300 10300 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-25 13:51:22.425 10300 10300 E Zygote  : accessInfo : 0
,05-25 13:51:22.425  3015  3015 I SecureStorage: [INFO]: SPID(0x00000005)Secure Storage Daemon finished processing with result: 0
05-25 13:51:22.425 10246 10246 I SecureStorage: [INFO]: SPID(0x00000005)Processing data has been completed
,05-25 13:51:22.435 10284 10284 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,05-25 13:51:22.435 10284 10284 I DBG_POLICYDM: [com.policydm.XDMService(585/llIlIllllllllllllllI)] get NotibarState : 0
,05-25 13:51:22.435 10284 10284 D InjectionManager: InjectionManager
05-25 13:51:22.435 10284 10284 D InjectionManager: fillFeatureStoreMap com.policydm
05-25 13:51:22.435 10284 10284 I InjectionManager: Constructor com.policydm, Feature store :{}
05-25 13:51:22.435 10284 10284 I InjectionManager: featureStore :{}
,05-25 13:51:22.445 10284 10284 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(574/IlIIIllllIIlIIIIIlII)] Initiated Type: 0
,05-25 13:51:22.445 10284 10284 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,05-25 13:51:22.445 10284 10284 I DBG_POLICYDM: [com.policydm.XDMService(585/llIlIllllllllllllllI)] get NotibarState : 0
,05-25 13:51:22.455  3549  3981 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:51:22.455  3549  3981 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{c3d5f08 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3117ce6 10284:com.policydm/1000}
,05-25 13:51:22.465 10284 10284 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(51/onReceive)] RegistrationReceiver onReceive! action = android.net.conn.CONNECTIVITY_CHANGE
,05-25 13:51:22.465  3549  3986 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:51:22.465 10246 10246 I wpa_supplicant: Ctrl_iface: loading system cred
,05-25 13:51:22.465  3549  3986 I ActivityManager: Killing 8972:com.android.defcontainer/u0a8 (adj 15): DHA:empty #33
05-25 13:51:22.465 10300 10300 D TimaKeyStoreProvider: TimaSignature is unavailable
05-25 13:51:22.465 10300 10300 D ActivityThread: Added TimaKeyStore provider
05-25 13:51:22.465 10246 10246 I SecureStorage: [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,05-25 13:51:22.475  3549  3986 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{c3d5f08 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b9114b5 6737:com.wssyncmldm/1000}
,05-25 13:51:22.485 10246 10246 I SecureStorage: [INFO]: SPID(0x00000005)This device supports Secure Storage
,05-25 13:51:22.485  3015  3015 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 10246
05-25 13:51:22.485  3015  3015 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
05-25 13:51:22.485 10246 10246 I SecureStorage: [INFO]: SPID(0x00000005)SS Daemon is running
05-25 13:51:22.485 10246 10246 I wpa_supplicant: ssSupport state is = 1
05-25 13:51:22.485  3549  4285 D ActivityManager:  getDeferredInfo final delay 300
,05-25 13:51:22.485 10246 10246 I wpa_supplicant: Blacklist: Clear (all) 
,05-25 13:51:22.485 10246 10246 E wpa_supplicant: getSavedIMSI cannot open /data/misc/radio/kmem: No such file or directory
05-25 13:51:22.485 10246 10246 I wpa_supplicant: [getIMSI]: sim_num 0
,05-25 13:51:22.485 10246 10246 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,05-25 13:51:22.485 10300 10300 W ResourcesManager: getTopLevelResources: /system/app/AASAservice/AASAservice.apk / 1.0 running in com.samsung.aasaservice rsrc of package com.samsung.aasaservice
,05-25 13:51:22.495  3549  4432 D ActivityManager: cleanUpApplicationRecord -- 8972
05-25 13:51:22.495  3549  4170 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-25 13:51:22.495 10300 10300 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-25 13:51:22.495  3549  4432 D ActivityManager: isAutoRunBlockedApp:: com.android.defcontainer, Auto Run ON
,05-25 13:51:22.495 10300 10300 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:51:22.495 10300 10300 I InjectionManager: Inside getClassLibPath caller 
,05-25 13:51:22.495 10300 10300 W System  : ClassLoader referenced unknown path: /system/app/AASAservice/lib/arm64
,05-25 13:51:22.505 10300 10300 D InjectionManager: InjectionManager
05-25 13:51:22.505 10300 10300 D InjectionManager: fillFeatureStoreMap com.samsung.aasaservice
,05-25 13:51:22.505 10300 10300 I InjectionManager: Constructor com.samsung.aasaservice, Feature store :{}
05-25 13:51:22.505 10300 10300 I InjectionManager: featureStore :{}
,05-25 13:51:22.505 10300 10300 D AASAservice: onCreate()
,05-25 13:51:22.505  3549  4435 I ActivityManager: Killing 9069:com.samsung.android.app.galaxylabs/u0a15 (adj 15): DHA:empty #33
,05-25 13:51:22.505 10284 10284 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(38/onServiceConnected)] AASA: onServiceConnected
,05-25 13:51:22.525  3549  4367 D ActivityManager: cleanUpApplicationRecord -- 9069
,05-25 13:51:22.525  3549  4367 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.galaxylabs, Auto Run ON
,05-25 13:51:22.785  3549  3603 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:51:22.795  3549  3603 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{c3d5f08 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6766968 6850:com.samsung.fresco.logging/5015}
,05-25 13:51:22.795  3549  4066 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,05-25 13:51:22.795  3549  4066 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:51:22.795  3549  4066 D BatteryService: online:4, current avg:4, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:106
05-25 13:51:22.795  3549  3549 D BatteryService: Sending ACTION_BATTERY_CHANGED.
05-25 13:51:22.795  3549  4286 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:22.795  3549  4170 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:51:22.795  3549  3549 I MotionRecognitionService: Plugged
05-25 13:51:22.795  3549  3549 D MotionRecognitionService:   cableConnection= 1
05-25 13:51:22.795  3549  3549 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:51:22.795  3549  3549 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:51:22.795  3549  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:51:22.805  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
05-25 13:51:22.805  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
,05-25 13:51:22.805  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:51:22.815  4905  4905 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:51:22.825  4905  4905 D BatteryMonitor: new battery level: 100
,05-25 13:51:22.825 10053 10053 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-25 13:51:22.825  3549  3981 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:51:22.825 10053 10095 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-25 13:51:22.835  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
05-25 13:51:22.835  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:22.835  3549  3981 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{c3d5f08 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{90a8bbc 7359:com.sec.spp.push/u0a39}
,05-25 13:51:22.845  7359  7359 E SPPClientService: [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
05-25 13:51:22.845  7359  7359 E SPPClientService: [SystemStateMoniter] Current Time : 303243
,05-25 13:51:22.845  7359  7359 E SPPClientService: [SystemStateMoniter] No Connect : true
,05-25 13:51:22.855  3549  3981 D ActivityManager:  getDeferredInfo final delay 300
,05-25 13:51:22.865  7359 10315 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,05-25 13:51:22.905  9936 10036 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,05-25 13:51:22.905  3549  4435 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
05-25 13:51:22.905  3549  4435 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,05-25 13:51:22.905  3549  4435 D WifiService: setWifiEnabled: true pid=9936, uid=10074
,05-25 13:51:22.905  3549  4435 W ActivityManager: Permission Denial: getCurrentUser() from pid=9936, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
05-25 13:51:22.905  3549  4435 W WifiService: Failed getting userId using ActivityManagerNative
05-25 13:51:22.905  3549  4435 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9936, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
05-25 13:51:22.905  3549  4435 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-25 13:51:22.905  3549  4435 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
05-25 13:51:22.905  3549  4435 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
05-25 13:51:22.905  3549  4435 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
05-25 13:51:22.905  3549  4435 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
05-25 13:51:22.905  3549  4435 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
05-25 13:51:22.905  3549  4435 D SettingsProvider: isChangeAllowed() : name = wifi_on
05-25 13:51:22.905  3549  3863 D WifiController: [FCC]setFccChannel() is called !!!
05-25 13:51:22.905  3549  3863 D WifiStateMachine: setFccChannel: channel = 0
05-25 13:51:22.905  3549  3863 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
,05-25 13:51:22.925  3549  4430 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-25 13:51:22.925  3549  4430 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4308, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:51:22.925  3549  4430 D BatteryService: online:4, current avg:4, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-163
05-25 13:51:22.925  3549  3549 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:51:22.925  3549  3549 I MotionRecognitionService: Plugged
05-25 13:51:22.925  3549  3549 D MotionRecognitionService:   cableConnection= 1
05-25 13:51:22.925  3549  3549 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:51:22.925  3549  3549 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:51:22.925  3549  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:51:22.925  4905  4905 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:51:22.935  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
05-25 13:51:22.935  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:51:22.935  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
05-25 13:51:22.935  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
05-25 13:51:22.935  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:22.935 10053 10053 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-25 13:51:22.935 10053 10095 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-25 13:51:22.935  4905  4905 D BatteryMonitor: new battery level: 100
,05-25 13:51:22.975  3549  3567 V AlarmManager:  remove PendingIntent] PendingIntent{29c09c3: PendingIntentRecord{6801218 com.android.bluetooth broadcastIntent}}
,05-25 13:51:23.005  3549  4435 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1248000  uid : 1000  pid : 3549  tag : BADGE_UPDATE@CPU_MIN@1
,05-25 13:51:23.045  3549  3601 D libgps  : agps_ril_update_network_availability: Waiting for IPC connection - timeout
05-25 13:51:23.045  3549  3601 E libgps  : LIBGPS: Cannot communicate (write) with a GPSD
05-25 13:51:23.045  3549  3601 E libgps  : IPC Communication Error, ../../../../tmp/14982990_270314/allPartners/os/android/gps_interface/gpsi_client/GpsiClient.cpp:1729 agps_ril_update_network_availability
,05-25 13:51:23.075  3549  6068 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:51:23.235  3157  3606 D Netd    : Iface wlan0 link up
,05-25 13:51:23.245  3157  3606 D Netd    : Iface wlan0 link up
05-25 13:51:23.245  3157  3606 D Netd    : Iface wlan0 link up
,05-25 13:51:23.245  3549  3614 D Tethering: interfaceLinkStateChanged wlan0, true
05-25 13:51:23.245  3549  3614 D Tethering: interfaceStatusChanged wlan0, true
,05-25 13:51:23.245  4905  9487 D PdnController: Interface Changed wlan0 link up
,05-25 13:51:23.245  3549  3614 D Tethering: interfaceLinkStateChanged wlan0, true
05-25 13:51:23.245  3549  3614 D Tethering: interfaceStatusChanged wlan0, true
,05-25 13:51:23.245  4905  4919 D PdnController: Interface Changed wlan0 link up
05-25 13:51:23.245  3549  3614 D Tethering: interfaceLinkStateChanged wlan0, true
05-25 13:51:23.245  3549  3614 D Tethering: interfaceStatusChanged wlan0, true
,05-25 13:51:23.245  4905  4920 D PdnController: Interface Changed wlan0 link up
,05-25 13:51:23.255  3549  3603 D ActivityManager:  getDeferredInfo final delay 200
,05-25 13:51:23.345 10246 10246 I wpa_supplicant: set_csc_config : ifname(p2p0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x0), vendorssid_list()
,05-25 13:51:23.345 10246 10246 I SecureStorage: [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,05-25 13:51:23.385 10246 10246 I SecureStorage: [INFO]: SPID(0x00000005)This device supports Secure Storage
,05-25 13:51:23.385  3015  3015 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 10246
05-25 13:51:23.385  3015  3015 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
05-25 13:51:23.385 10246 10246 I SecureStorage: [INFO]: SPID(0x00000005)SS Daemon is running
05-25 13:51:23.385 10246 10246 I wpa_supplicant: ssSupport state is = 1
,05-25 13:51:23.395 10246 10246 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,05-25 13:51:23.395 10246 10246 E wpa_supplicant: nl80211: Could not configure driver mode
05-25 13:51:23.395 10246 10246 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
,05-25 13:51:23.395 10246 10246 E wpa_supplicant: p2p0: Failed to initialize driver interface
05-25 13:51:23.395 10246 10246 I wpa_supplicant: Blacklist: Clear (all) 
05-25 13:51:23.395 10246 10246 I wpa_supplicant: set_csc_config : ifname(p2p0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x0), vendorssid_list()
,05-25 13:51:23.395 10246 10246 I SecureStorage: [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,05-25 13:51:23.405  9936 10036 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,05-25 13:51:23.415  3549  4066 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,05-25 13:51:23.415  3549  4066 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,05-25 13:51:23.425  3549  4066 D WifiService: setWifiEnabled: true pid=9936, uid=10074
,05-25 13:51:23.425  3549  4066 W ActivityManager: Permission Denial: getCurrentUser() from pid=9936, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
05-25 13:51:23.425  3549  4066 W WifiService: Failed getting userId using ActivityManagerNative
05-25 13:51:23.425  3549  4066 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9936, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
05-25 13:51:23.425  3549  4066 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-25 13:51:23.425  3549  4066 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
05-25 13:51:23.425  3549  4066 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
05-25 13:51:23.425  3549  4066 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
05-25 13:51:23.425  3549  4066 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
05-25 13:51:23.425  3549  4066 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
05-25 13:51:23.425  3549  4066 D SettingsProvider: isChangeAllowed() : name = wifi_on
,05-25 13:51:23.425  3549  3863 D WifiStateMachine: setFccChannel: channel = 0
05-25 13:51:23.425  3549  3863 D WifiController: [FCC]setFccChannel() is called !!!
05-25 13:51:23.425  3549  3863 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
,05-25 13:51:23.435 10246 10246 I SecureStorage: [INFO]: SPID(0x00000005)This device supports Secure Storage
,05-25 13:51:23.435  3015  3015 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 10246
05-25 13:51:23.435  3015  3015 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
,05-25 13:51:23.435 10246 10246 I SecureStorage: [INFO]: SPID(0x00000005)SS Daemon is running
05-25 13:51:23.435 10246 10246 I wpa_supplicant: ssSupport state is = 1
05-25 13:51:23.435 10246 10246 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,05-25 13:51:23.455 10246 10246 I wpa_supplicant: P2P: Set prekey state (NONE -> NONE)
,05-25 13:51:23.455  3549  3603 D ActivityManager:  getDeferredInfo final delay 200
,05-25 13:51:23.465  3549  3859 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,05-25 13:51:23.465  3549  3859 E WifiStateMachine: Deffering msg in Supplicant Starting State131085
,05-25 13:51:23.465  3549  3859 D WifiBigDataLog: getJsonFormat() - feature : ONOF
05-25 13:51:23.465  3549  3859 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,05-25 13:51:23.465  3549  3859 D WifiBigDataLog: init : 
,05-25 13:51:23.475  3549  3859 E WifiStateMachine: Deffering msg in Supplicant Starting State131083
,05-25 13:51:23.475  3549  3859 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,05-25 13:51:23.475  3549  3859 D WifiBigDataLog: getJsonFormat() - feature : ONOF
05-25 13:51:23.475  3549  3859 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,05-25 13:51:23.485  3549  3603 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{73bc240 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{44442de 4889:com.samsung.android.providers.context/u0a7}
,05-25 13:51:23.485  3549  3859 D WifiBigDataLog: init : 
,05-25 13:51:23.485  3549  3859 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,05-25 13:51:23.485  3549  3859 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,05-25 13:51:23.495  3549  4367 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7216579 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{44442de 4889:com.samsung.android.providers.context/u0a7}
,05-25 13:51:23.505  3549  3859 D WifiBigDataLog: init : 
,05-25 13:51:23.505  3549  3859 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,05-25 13:51:23.505  3549  3859 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,05-25 13:51:23.515  3549  4367 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ab942be u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{44442de 4889:com.samsung.android.providers.context/u0a7}
,05-25 13:51:23.515  3549  3859 D WifiBigDataLog: init : 
,05-25 13:51:23.525  3549  3859 D WifiNative-wlan0: callSECApiBoolean - ID [301]
,05-25 13:51:23.525 10246 10246 I wpa_supplicant: HOTSPOT20_ENABLE called ON
05-25 13:51:23.525 10246 10246 I wpa_supplicant: Blacklist: Clear (all) 
,05-25 13:51:23.525  3549  3981 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2b7f1f u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{44442de 4889:com.samsung.android.providers.context/u0a7}
,05-25 13:51:23.535 10246 10246 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,05-25 13:51:23.535 10246 10246 I wpa_supplicant: wlan0: Skip scan - bUseNetwork false
,05-25 13:51:23.545  3549  3859 D WifiNative-wlan0: callSECApiInt - ID [210]
,05-25 13:51:23.545  3549  3549 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
,05-25 13:51:23.545  3549  3864 D HS20StateMachine: WIFI_STATE_ENABLED
05-25 13:51:23.545  3549  3864 D HS20StateMachine: reloadCredentialsToSupplicant
05-25 13:51:23.545  3549  3864 D HotspotDBHandler: getCredentialIds
05-25 13:51:23.545  3549  3549 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
05-25 13:51:23.545  3549  3867 I WifiHs20Service: Message received 5011
,05-25 13:51:23.545  3549  3549 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,05-25 13:51:23.545  3949  4133 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
05-25 13:51:23.555  3549  4211 W SLocation: No Active Data Connection
,05-25 13:51:23.555  3949  3949 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 272
05-25 13:51:23.555  3549  3871 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
05-25 13:51:23.555  3949  3949 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,05-25 13:51:23.555  3949  3949 I HotspotTile: Provider is not defined returning false
05-25 13:51:23.555  3949  3949 D HotspotTile: onReceive : 3, 0
05-25 13:51:23.555  4260  4272 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,05-25 13:51:23.555  4260  4272 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
05-25 13:51:23.555  3549  3871 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,05-25 13:51:23.565  9936  9936 D BluetoothAdapter: STATE_ON
,05-25 13:51:23.565  3549  3603 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{43ac26c u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{14616a1 9936:com.thaliproject.thalitest/u0a74}
05-25 13:51:23.565  9936  9936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-25 13:51:23.565  9936  9936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-25 13:51:23.565  9936  9936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-25 13:51:23.565  9936  9936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-25 13:51:23.565  9936  9936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-25 13:51:23.565  9936  9936 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
05-25 13:51:23.565  9936  9936 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
05-25 13:51:23.565  9936  9936 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
05-25 13:51:23.565  9936  9936 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,05-25 13:51:23.575  9936  9936 D BluetoothAdapter: STATE_ON
,05-25 13:51:23.575  9936  9936 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,05-25 13:51:23.585  3549  4430 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:23.585  3549  4430 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:23.585  3549  4430 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:23.585  3549  4430 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:51:23.585  3549  4430 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:23.585  3549  4430 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:23.585  3549  4430 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:23.585 10246 10246 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
05-25 13:51:23.585  3549  4430 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:23.585  3549  4430 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:51:23.585  3549  4430 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:23.585  3549  4430 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:23.585  3549  4430 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
05-25 13:51:23.585  3549  4430 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:51:23.585  3549  4430 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:23.585  3549  4430 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:51:23.585  3549  3859 D WifiConfigStore: Loading config and enabling all networks 
,05-25 13:51:23.595 10323 10323 E Zygote  : v2
05-25 13:51:23.595 10323 10323 I libpersona: KNOX_SDCARD checking this for 10114
05-25 13:51:23.595 10323 10323 I libpersona: KNOX_SDCARD not a persona
,05-25 13:51:23.595 10323 10323 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
05-25 13:51:23.595  3549  3864 I ActivityManager: Start proc 10323:com.samsung.hs20provider/u0a114 for content provider com.samsung.hs20provider/.Hs20Provider
,05-25 13:51:23.595 10323 10323 E Zygote  : accessInfo : 0
,05-25 13:51:23.595 10323 10323 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.samsung.hs20provider 
,05-25 13:51:23.605  3549  3859 I WifiConfigStore: "Thali_internal" is a verified password AP: false
05-25 13:51:23.605  3549  3859 E WifiConfigStore: Not a HS20
,05-25 13:51:23.615  3549  3859 I WifiConfigStore: "AndroidHotspot2346" is a verified password AP: true
05-25 13:51:23.615  3549  3859 E WifiConfigStore: Not a HS20
,05-25 13:51:23.625  3549  3859 I WifiConfigStore: "MC" is a verified password AP: false
05-25 13:51:23.625  3549  3859 E WifiConfigStore: Not a HS20
,05-25 13:51:23.635 10323 10323 D TimaKeyStoreProvider: TimaSignature is unavailable
05-25 13:51:23.635 10323 10323 D ActivityThread: Added TimaKeyStore provider
,05-25 13:51:23.635  3549  3859 I WifiConfigStore: "MC" is a verified password AP: true
05-25 13:51:23.635  3549  3859 E WifiConfigStore: Not a HS20
,05-25 13:51:23.645  3549  3859 I WifiConfigStore: "NG700" is a verified password AP: true
05-25 13:51:23.645  3549  3859 E WifiConfigStore: Not a HS20
,05-25 13:51:23.655  3549  3859 D WifiConfigStore: loaded 0 passpoint configs
,05-25 13:51:23.655  3549  3603 D ActivityManager:  getDeferredInfo final delay 200
,05-25 13:51:23.655  3549  3859 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
05-25 13:51:23.655 10323 10323 W ResourcesManager: getTopLevelResources: /system/app/Hs20Provider/Hs20Provider.apk / 1.0 running in com.samsung.hs20provider rsrc of package com.samsung.hs20provider
,05-25 13:51:23.655  3549  3859 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
05-25 13:51:23.655  3549  3859 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,05-25 13:51:23.655  3549  3859 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
,05-25 13:51:23.655  3549  3859 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,05-25 13:51:23.655  3549  4420 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-25 13:51:23.655 10323 10323 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-25 13:51:23.665 10323 10323 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:51:23.665  3549  3859 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
05-25 13:51:23.665  3549  3859 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
05-25 13:51:23.665  3549  3859 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
05-25 13:51:23.665  3549  3859 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"NONE
05-25 13:51:23.665  3549  3859 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
05-25 13:51:23.665  3549  3859 E WifiConfigStore: found sortedWifiConfigurations : "MC"NONE
05-25 13:51:23.665  3549  3859 D WifiConfigStore: setNetworkPriorityDefault: networkId = 4, priority = 1
05-25 13:51:23.665  3549  3549 I WifiHs20Service: Broadcast received:android.net.wifi.CONFIGURED_NETWORKS_CHANGE
05-25 13:51:23.665  3549  3549 D WifiHs20Service: reason: 2
,05-25 13:51:23.665  3549  3867 I WifiHs20Service: Message received 5014
05-25 13:51:23.665  3549  3867 E WifiHs20Service: received HS20_UTILITY_ACTION_TYPE_HS20_CONFIGURATION_CHANGED
05-25 13:51:23.665  3549  3867 E WifiHs20Service: The changed config is NULL
05-25 13:51:23.665  3549  3859 D WifiConfigStore: setNetworkPriorityDefault: networkId = 1, priority = 1
,05-25 13:51:23.665  3549  3859 D WifiConfigStore: setNetworkPriorityDefault: networkId = 0, priority = 1
,05-25 13:51:23.665  3549  3859 D WifiConfigStore: setNetworkPriorityDefault: networkId = 3, priority = 1
05-25 13:51:23.665  3549  3859 D WifiConfigStore: setNetworkPriorityDefault: networkId = 2, priority = 1
,05-25 13:51:23.665 10323 10323 I InjectionManager: Inside getClassLibPath caller 
05-25 13:51:23.665  3549  3859 D WifiNative-wlan0: callSECApiInt - ID [65]
,05-25 13:51:23.675  3549  3859 D WifiNative-wlan0: callSECApiBoolean - ID [13]
,05-25 13:51:23.675 10246 10246 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
05-25 13:51:23.675 10246 10246 I wpa_supplicant: resume autoscan
05-25 13:51:23.675 10246 10246 I wpa_supplicant: autoscan_samsung_exponential_notify_scan : scan_interval = 8
05-25 13:51:23.675 10246 10246 I wpa_supplicant: autoscan: autoscan_notify_scan, scan_interval = 8
05-25 13:51:23.675 10246 10246 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
05-25 13:51:23.675 10246 10246 I wpa_supplicant: reset timer : RESET_TIMER 0
,05-25 13:51:23.675 10246 10246 I wpa_supplicant: P2P: Current p2p state = IDLE
05-25 13:51:23.675 10246 10246 I wpa_supplicant: First Scan Start,
05-25 13:51:23.675 10323 10323 W System  : ClassLoader referenced unknown path: /system/app/Hs20Provider/lib/arm64
,05-25 13:51:23.685 10246 10246 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,05-25 13:51:23.685  3549  3859 D WifiNative-wlan0: Setting external_sim to 1
,05-25 13:51:23.685  3549  3859 D WifiStateMachine: [setCountryCode()] Airplane mode return !!!
05-25 13:51:23.685  3549  3859 D WifiStateMachine: Setting OUI to DA-A1-19
,05-25 13:51:23.685 10246 10246 I wpa_supplicant: bt_status is set be DISCONNECTED
,05-25 13:51:23.685 10323 10323 D InjectionManager: InjectionManager
,05-25 13:51:23.685 10323 10323 D InjectionManager: fillFeatureStoreMap com.samsung.hs20provider
05-25 13:51:23.685 10323 10323 I InjectionManager: Constructor com.samsung.hs20provider, Feature store :{}
05-25 13:51:23.685 10323 10323 I InjectionManager: featureStore :{}
,05-25 13:51:23.695  3549  3859 E WifiNative-wlan0: do suspend false
,05-25 13:51:23.695 10323 10333 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_credentials
,05-25 13:51:23.695 10323 10333 D HotspotProvider: CREDENTIAL
05-25 13:51:23.695 10323 10333 D HotspotProvider: No prepend tags
,05-25 13:51:23.705  3549  3864 D HS20StateMachine: CMD_HOTSPOT20_ENABLE : 
,05-25 13:51:23.705  3549  3864 D HS20StateMachine: enter : DiscoveringState
,05-25 13:51:23.705  3549  3549 I ActivityManager: Killing 9088:com.google.android.partnersetup/u0a23 (adj 15): DHA:empty #33
,05-25 13:51:23.705  3549  3859 D WifiStateMachine:  p2p Needed be enabled 
,05-25 13:51:23.705  3549  3858 D WifiP2pService: P2pDisabledState{ what=131203 }
,05-25 13:51:23.715  3157  3613 D CommandListener: Setting iface cfg
05-25 13:51:23.715  3157  3613 D CommandListener: Trying to bring up p2p0
05-25 13:51:23.715  3157  3606 D Netd    : Iface p2p0 link up
,05-25 13:51:23.715  3549  3859 D WifiNative-HAL: Failing getSupportedFeatureset because HAL isn't started
,05-25 13:51:23.715  3549  3859 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
05-25 13:51:23.715  3549  3614 D Tethering: interfaceLinkStateChanged p2p0, true
,05-25 13:51:23.715  3549  3614 D Tethering: interfaceStatusChanged p2p0, true
05-25 13:51:23.715  3549  3858 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,05-25 13:51:23.715  3549  3858 D SecContentProvider: insert(), uri = 2
05-25 13:51:23.715  3549  3859 D WifiStateMachine: [FCC]Airplane on, setFccChannel(0)!!!
05-25 13:51:23.715  3549  3859 D WifiStateMachine: setFccChannelNative: channel = 0
05-25 13:51:23.715  3549  3859 D WifiNative-wlan0: callSECApiInt - ID [230]
05-25 13:51:23.715  4905  5185 D PdnController: Interface Changed p2p0 link up
,05-25 13:51:23.725  3549  3858 D WifiP2pService: P2pEnablingState
,05-25 13:51:23.725  3549  3858 D WifiP2pService: P2pEnablingState{ what=147457 }
05-25 13:51:23.725  3549  3858 D WifiP2pService: P2p socket connection successful
,05-25 13:51:23.725  3549  3858 D WifiP2pService: P2pEnabledState
05-25 13:51:23.725  3549  3858 D SecContentProvider: insert(), uri = 2
,05-25 13:51:23.725  3549  3892 E WifiScanningService: could not start HAL
,05-25 13:51:23.725  3549  3549 D RttService: SCAN_AVAILABLE : 3
05-25 13:51:23.725  3549  3893 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,05-25 13:51:23.735  3549  3858 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,05-25 13:51:23.735  3549  3869 E ConnectivityService: updateNetworkInfo()
05-25 13:51:23.735  3549  3869 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
05-25 13:51:23.735  3549  3859 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,05-25 13:51:23.735  3549  3838 D ActivityManager: cleanUpApplicationRecord -- 9088
,05-25 13:51:23.735  3549  3838 D ActivityManager: isAutoRunBlockedApp:: com.google.android.partnersetup, Auto Run ON
,05-25 13:51:23.745  3549  3549 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,05-25 13:51:23.745  3549  3620 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false, mScanRequestedInConnected = false
05-25 13:51:23.745  3549  3620 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
05-25 13:51:23.745  3549  3620 D WifiDisplayController: disconnect
05-25 13:51:23.745  3549  3620 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,05-25 13:51:23.745  3949  3949 D SoundPathController: onReceive - android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
05-25 13:51:23.745  3949  3949 D ApMirroringController: onReceive android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,05-25 13:51:23.745  3949  3949 D AllShareCastTile: onReceive : android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
05-25 13:51:23.745  3549  4367 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,05-25 13:51:23.745  3949  3949 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,05-25 13:51:23.755 10246 10246 I wpa_supplicant: P2P: Set Samsung Discovery Icon = 256
05-25 13:51:23.755  3549  3620 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:23.755  3949  3949 D WifiP2pController: onReceive android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,05-25 13:51:23.755  3549  3620 I WifiDisplayAdapter: onP2pDisconnected
05-25 13:51:23.755 10246 10246 I wpa_supplicant: P2P: Set Samsung Discovery name = 
05-25 13:51:23.755  3549  3620 D IpRemoteDisplayController: disconnectWfdBridgeServer
05-25 13:51:23.755  3549  3620 D IpRemoteDisplayController: WfdBridgeServer is already null
,05-25 13:51:23.755  4260  4623 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,05-25 13:51:23.755  3549  3603 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{942ccca u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cbe5628 10259:com.samsung.android.app.FileShareClient/5005}
,05-25 13:51:23.765 10259 10259 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
05-25 13:51:23.765  3549  3859 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,05-25 13:51:23.765 10259 10259 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,05-25 13:51:23.765 10259 10259 D FileShare-Client: Outbound.stopDelayTimer - 
,05-25 13:51:23.765  9936  9936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:51:23.775  3549  3986 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{942ccca u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{63b0f41 10272:com.samsung.android.app.FileShareServer/5005}
,05-25 13:51:23.795 10272 10272 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,05-25 13:51:23.795 10272 10272 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,05-25 13:51:23.795 10272 10272 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,05-25 13:51:23.805  9936  9936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:51:23.815  3549  3858 E WifiP2pService: Failed to set my phone number info into probe response
,05-25 13:51:23.815  3549  3858 D WifiNative-p2p0: p2pGetDeviceAddress
,05-25 13:51:23.815  3549  3858 D WifiNative-p2p0: p2pGetDeviceAddress returning 4e:66:41:a9:15:41
,05-25 13:51:23.825  3549  3858 D WifiP2pService: DeviceAddress: 4e:15:41
05-25 13:51:23.825  3549  3620 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: [Phone] Samsung Galaxy S7
05-25 13:51:23.825  3549  3620 D WifiDisplayController:  deviceAddress: 4e:66:41:a9:15:41
05-25 13:51:23.825  3549  3620 D WifiDisplayController:  primary type: 10-0050F204-5
05-25 13:51:23.825  3549  3620 D WifiDisplayController:  secondary type: null
05-25 13:51:23.825  3549  3620 D WifiDisplayController:  wps: 0
05-25 13:51:23.825  3549  3620 D WifiDisplayController:  grpcapab: 0
05-25 13:51:23.825  3549  3620 D WifiDisplayController:  devcapab: 0
05-25 13:51:23.825  3549  3620 D WifiDisplayController:  status: 3
05-25 13:51:23.825  3549  3620 D WifiDisplayController:  wfdInfo: null
05-25 13:51:23.825  3549  3620 D WifiDisplayController:  groupownerAddress: null
05-25 13:51:23.825  3549  3620 D WifiDisplayController:  GOdeviceName: null
05-25 13:51:23.825  3549  3620 D WifiDisplayController:  interfaceAddress: 
05-25 13:51:23.825  3549  3620 D WifiDisplayController:  SConnectInfo : null
05-25 13:51:23.825  3549  3620 D WifiDisplayController:  contactInfoHash : null
05-25 13:51:23.825  3549  3620 D WifiDisplayController:  ssDevInfo : 0
05-25 13:51:23.825  3549  3620 D WifiDisplayController:  iconIdx : 0
,05-25 13:51:23.835  3549  3858 D WifiP2pService: sending p2p persistent groups changed broadcast
,05-25 13:51:23.835  3549  3858 D WifiP2pService: InactiveState
05-25 13:51:23.835  3549  3858 D WifiP2pService: InactiveState{ what=143376 }
,05-25 13:51:23.835  3549  3858 D WifiP2pService: P2pEnabledState{ what=143376 }
05-25 13:51:23.835  3549  3858 E WifiP2pService: Airplane mode : skipped SET_COUNTRY_CODE
,05-25 13:51:23.855  3549  3603 D ActivityManager:  getDeferredInfo final delay 200
,05-25 13:51:23.945  9936 10036 D BluetoothAdapter: STATE_ON
,05-25 13:51:23.945  9936 10036 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-25 13:51:23.945  9936 10036 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-25 13:51:23.945  9936 10036 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-25 13:51:23.945  9936 10036 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-25 13:51:23.945  9936 10036 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-25 13:51:23.945  9936 10036 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
05-25 13:51:23.945  9936 10036 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
05-25 13:51:23.945  9936 10036 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
05-25 13:51:23.945  9936 10036 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,05-25 13:51:23.945  9936  9999 D BluetoothAdapter: enable()
,05-25 13:51:23.965  9936  9999 D BluetoothAdapter: enable(): BT is already enabled..!
,05-25 13:51:23.985  3549  3603 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a12ee3b u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{44442de 4889:com.samsung.android.providers.context/u0a7}
,05-25 13:51:23.985  9936  9999 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,05-25 13:51:23.995  3549  3838 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,05-25 13:51:23.995  3549  3838 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,05-25 13:51:23.995  3549  3838 D WifiService: setWifiEnabled: true pid=9936, uid=10074
,05-25 13:51:23.995  3549  3838 W ActivityManager: Permission Denial: getCurrentUser() from pid=9936, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
,05-25 13:51:24.005  3549  3838 W WifiService: Failed getting userId using ActivityManagerNative
05-25 13:51:24.005  3549  3838 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9936, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
05-25 13:51:24.005  3549  3838 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-25 13:51:24.005  3549  3838 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
05-25 13:51:24.005  3549  3838 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
05-25 13:51:24.005  3549  3838 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
05-25 13:51:24.005  3549  3838 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
05-25 13:51:24.005  3549  3838 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
05-25 13:51:24.005  3549  3838 D SettingsProvider: isChangeAllowed() : name = wifi_on
05-25 13:51:24.005  3549  3863 D WifiController: [FCC]setFccChannel() is called !!!
,05-25 13:51:24.005  3549  3863 D WifiStateMachine: setFccChannel: channel = 0
,05-25 13:51:24.005  3549  3863 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
05-25 13:51:24.005  9936  9999 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
05-25 13:51:24.005  3549  3859 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,05-25 13:51:24.005  3549  3859 D WifiBigDataLog: getJsonFormat() - feature : ONOF
05-25 13:51:24.005  9936  9999 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
05-25 13:51:24.005  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
05-25 13:51:24.005  9936  9999 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
05-25 13:51:24.005  9936  9999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,05-25 13:51:24.005  9936  9999 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c552781 removed from the list
05-25 13:51:24.005  9936  9999 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c552781 removed from the list
05-25 13:51:24.005  9936  9999 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
05-25 13:51:24.005  9936  9999 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1115026 removed from the list
05-25 13:51:24.005  9936  9999 D io.jxcore.node.ConnectivityMonitor: stop
05-25 13:51:24.005  9936  9999 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,05-25 13:51:24.005  9936  9999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
05-25 13:51:24.005  3549  3859 D WifiBigDataLog: init : 
05-25 13:51:24.005  9936  9999 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testRun
05-25 13:51:24.005  3549  3859 D WifiStateMachine: setFccChannelNative: channel = 0
,05-25 13:51:24.005  3549  3859 D WifiNative-wlan0: callSECApiInt - ID [230]
05-25 13:51:24.015  9936 10335 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
05-25 13:51:24.015  9936 10335 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,05-25 13:51:24.015  3549  3603 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b479958 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{44442de 4889:com.samsung.android.providers.context/u0a7}
,05-25 13:51:24.015  3157  3609 D EnterpriseController: netId is 0
,05-25 13:51:24.015  3157  3609 D Netd    : getNetworkForDns: using netid 0 for uid 10074
,05-25 13:51:24.025  9936 10337 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,05-25 13:51:24.025  9936 10337 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
05-25 13:51:24.025  9936 10337 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-25 13:51:24.025  9936 10335 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
05-25 13:51:24.025  9936 10335 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
05-25 13:51:24.025  9936 10335 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-25 13:51:24.025  9936 10337 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-25 13:51:24.025  9936 10335 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,05-25 13:51:24.025  9936 10337 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
05-25 13:51:24.025  9936 10335 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,05-25 13:51:24.035  9936 10342 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 240, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:24.035  9936 10342 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:51:24.035  9936 10342 D io.jxcore.node.StreamCopyingThread:  id: 75
,05-25 13:51:24.035  9936 10342 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 240, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:24.035  9936 10342 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:51:24.035  9936 10342 D io.jxcore.node.StreamCopyingThread:  id: 75
05-25 13:51:24.035  9936 10341 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 239, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:24.035  9936 10341 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:51:24.035  9936 10341 D io.jxcore.node.StreamCopyingThread:  id: 74
05-25 13:51:24.035  9936 10342 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:24.035  9936 10342 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:51:24.035  9936 10342 D io.jxcore.node.StreamCopyingThread:  id: 75
05-25 13:51:24.035  9936 10342 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,05-25 13:51:24.035  9936 10342 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
05-25 13:51:24.035  9936 10341 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 239, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:24.035  9936 10341 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:51:24.035  9936 10341 D io.jxcore.node.StreamCopyingThread:  id: 74
05-25 13:51:24.035  9936 10342 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
05-25 13:51:24.035  9936 10341 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:24.035  9936 10341 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:51:24.035  9936 10341 D io.jxcore.node.StreamCopyingThread:  id: 74
05-25 13:51:24.035  9936 10342 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
05-25 13:51:24.035  9936 10341 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
05-25 13:51:24.035  9936 10342 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
05-25 13:51:24.035  9936 10341 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
05-25 13:51:24.035  9936 10342 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,05-25 13:51:24.035  9936 10341 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
05-25 13:51:24.035  9936 10341 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
05-25 13:51:24.035  9936 10341 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
05-25 13:51:24.035  9936 10342 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 240, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:24.035  9936 10342 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:51:24.035  9936 10342 D io.jxcore.node.StreamCopyingThread:  id: 75 .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
05-25 13:51:24.035  9936 10341 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
05-25 13:51:24.035  9936 10341 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 239, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:24.035  9936 10341 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:51:24.035  9936 10341 D io.jxcore.node.StreamCopyingThread:  id: 74 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
05-25 13:51:24.035  9936 10339 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 237, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:24.035  9936 10339 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:51:24.035  9936 10339 D io.jxcore.node.StreamCopyingThread:  id: 74
05-25 13:51:24.035  9936 10339 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 237, thread name: IncomingSocketThread/Sender): recvfrom failed: EBADF (Bad file descriptor)
05-25 13:51:24.035  9936 10339 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 237, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:24.035  9936 10339 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:51:24.035  9936 10339 D io.jxcore.node.StreamCopyingThread:  id: 74 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
,05-25 13:51:24.035  9936 10339 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: recvfrom failed: EBADF (Bad file descriptor)
05-25 13:51:24.035  9936 10339 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
05-25 13:51:24.035  9936 10340 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 238, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:24.035  9936 10340 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:51:24.035  9936 10340 D io.jxcore.node.StreamCopyingThread:  id: 75
05-25 13:51:24.035  9936 10339 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 237, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:24.035  9936 10339 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:51:24.035  9936 10339 D io.jxcore.node.StreamCopyingThread:  id: 74 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
05-25 13:51:24.035  9936 10340 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 238, thread name: OutgoingSocketThread/Sender): recvfrom failed: EBADF (Bad file descriptor)
05-25 13:51:24.035  9936 10340 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 238, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:24.035  9936 10340 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:51:24.035  9936 10340 D io.jxcore.node.StreamCopyingThread:  id: 75 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
05-25 13:51:24.035  9936 10340 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: recvfrom failed: EBADF (Bad file descriptor)
05-25 13:51:24.035  9936 10340 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
05-25 13:51:24.035  9936 10340 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 238, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:24.035  9936 10340 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:51:24.035  9936 10340 D io.jxcore.node.StreamCopyingThread:  id: 75 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
,05-25 13:51:24.055  3549  3603 D ActivityManager:  getDeferredInfo final delay 80
,05-25 13:51:24.135  3549  3603 D ActivityManager:  getDeferredInfo final delay 80
,05-25 13:51:24.255  3157  3606 D Netd    : Iface wlan0 link up
,05-25 13:51:24.265 10246 10246 I wpa_supplicant: nl80211: Received scan results (7 BSSes)
05-25 13:51:24.265  3549  3614 D Tethering: interfaceLinkStateChanged wlan0, true
05-25 13:51:24.265  3549  3614 D Tethering: interfaceStatusChanged wlan0, true
05-25 13:51:24.265 10246 10246 I wpa_supplicant: autoscan_samsung_exponential_notify_scan : scan_interval = 8
05-25 13:51:24.265 10246 10246 I wpa_supplicant: autoscan: autoscan_notify_scan, scan_interval = 8
05-25 13:51:24.265 10246 10246 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,05-25 13:51:24.265  4905  4920 D PdnController: Interface Changed wlan0 link up
,05-25 13:51:24.265 10246 10246 I wpa_supplicant:    allow  - level is under -85dBm [-41] or selected nid [-1] [4]
,05-25 13:51:24.265 10246 10246 I wpa_supplicant:  selected from pick network BSS F4.99.3E ssid='NG700' et= 090,gp=03,cu=987654321,sc=987654321
05-25 13:51:24.265 10246 10246 I wpa_supplicant:    allow  - level is under -85dBm [-41] or selected nid [-1] [4]
05-25 13:51:24.265 10246 10246 I wpa_supplicant: wlan0: Trying to associate with f4:f2:6d:22:99:3e (SSID='NG700' freq=2442 MHz level=-41) 
,05-25 13:51:24.295  3549  3603 D ActivityManager:  getDeferredInfo final delay 80
,05-25 13:51:24.295  3549  3859 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,05-25 13:51:24.305  3549  3549 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.SCAN_RESULTS
,05-25 13:51:24.305  3549  3603 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{454ab1 u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c130950 3949:com.android.systemui/u0a62}
,05-25 13:51:24.315  9936  9936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:51:24.365 10246 10246 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,05-25 13:51:24.375  3157  3606 D Netd    : Iface wlan0 link up
05-25 13:51:24.375  3157  3606 D Netd    : Iface wlan0 link up
05-25 13:51:24.375  3157  3606 D Netd    : Iface wlan0 link up
,05-25 13:51:24.375  3549  3614 D Tethering: interfaceLinkStateChanged wlan0, true
05-25 13:51:24.375  3549  3614 D Tethering: interfaceStatusChanged wlan0, true
,05-25 13:51:24.375  4905  5185 D PdnController: Interface Changed wlan0 link up
05-25 13:51:24.375  3549  3603 D ActivityManager:  getDeferredInfo final delay 80
05-25 13:51:24.375  3549  3614 D Tethering: interfaceLinkStateChanged wlan0, true
05-25 13:51:24.375  3549  3614 D Tethering: interfaceStatusChanged wlan0, true
,05-25 13:51:24.375  4905  9487 D PdnController: Interface Changed wlan0 link up
05-25 13:51:24.375  3549  3614 D Tethering: interfaceLinkStateChanged wlan0, true
05-25 13:51:24.375  3549  3614 D Tethering: interfaceStatusChanged wlan0, true
,05-25 13:51:24.375 10246 10246 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
05-25 13:51:24.375  4905  4919 D PdnController: Interface Changed wlan0 link up
,05-25 13:51:24.375 10246 10246 I wpa_supplicant: wlan0: WPA: RX message 1 of 4-Way Handshake from F4.99.3E (ver=2)
,05-25 13:51:24.385 10246 10246 I wpa_supplicant: wlan0: WPA: Sending EAPOL-Key 2/4
,05-25 13:51:24.395  3549  3859 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,05-25 13:51:24.395  3549  3859 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,05-25 13:51:24.395 10246 10246 I wpa_supplicant: wlan0: WPA: RX message 3 of 4-Way Handshake from F4.99.3E (ver=2)
,05-25 13:51:24.405  9936  9936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:51:24.405 10246 10246 I wpa_supplicant: wlan0: WPA: Sending EAPOL-Key 4/4
,05-25 13:51:24.405  9936  9936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:51:24.405 10246 10246 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,05-25 13:51:24.405 10246 10246 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=4 id_str=]
05-25 13:51:24.405  3157  3606 D Netd    : Iface wlan0 link up
,05-25 13:51:24.405 10246 10246 I wpa_supplicant: Blacklist: Clear (temp) 
05-25 13:51:24.405  3549  3614 D Tethering: interfaceLinkStateChanged wlan0, true
,05-25 13:51:24.405  3549  3614 D Tethering: interfaceStatusChanged wlan0, true
05-25 13:51:24.415  4905  4920 D PdnController: Interface Changed wlan0 link up
,05-25 13:51:24.415  3549  3859 D WifiNative-wlan0: callSECApiVoid - ID [50]
,05-25 13:51:24.425  3549  3859 V AlarmManager:  remove PendingIntent] PendingIntent{8eb0492: PendingIntentRecord{2619e63 android broadcastIntent}}
,05-25 13:51:24.425  3549  3859 D WifiNetworkAgent: NetworkAgent: Registering NetworkAgent
,05-25 13:51:24.425  3549  3549 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
,05-25 13:51:24.425  3549  3549 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
05-25 13:51:24.425  3549  3549 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
,05-25 13:51:24.425  3549  3549 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
,05-25 13:51:24.435  3549  3859 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
05-25 13:51:24.425  3549  3867 I WifiHs20Service: Message received 5007
05-25 13:51:24.435  3549  3869 D ConnectivityService: Got NetworkAgent Messenger
,05-25 13:51:24.435  3549  3869 E ConnectivityService: updateNetworkInfo()
05-25 13:51:24.435  3549  3869 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-25 13:51:24.435  3949  4133 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-25 13:51:24.435  3549  3869 D ConnectivityService: NetworkAgent connected
,05-25 13:51:24.435  3157  3613 D CommandListener: Setting iface cfg
,05-25 13:51:24.435  4260  4260 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,05-25 13:51:24.445  3549  3603 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e3440a5 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ec43a0e 10220:com.sec.android.diagmonagent/1000}
,05-25 13:51:24.445  3549  3859 D WifiStateMachine: Start Dhcp Watchdog 2
,05-25 13:51:24.445 10220 10220 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,05-25 13:51:24.445 10220 10220 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
05-25 13:51:24.445 10220 10220 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
05-25 13:51:24.445 10220 10220 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,05-25 13:51:24.455  3549  3859 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,05-25 13:51:24.465  3549  4430 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e3440a5 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5d86d50 6413:com.enhance.gameservice/u0a106}
,05-25 13:51:24.475  3549  3603 D ActivityManager:  getDeferredInfo final delay 80
,05-25 13:51:24.475  9936  9936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:51:24.485  3549  4430 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e3440a5 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{620523c 10233:com.sec.knox.switcher/1000}
,05-25 13:51:24.485 10233 10233 I usagelog: received in receiver
05-25 13:51:24.485 10233 10233 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
05-25 13:51:24.485 10233 10233 I KnoxUsageLogPro: premStatus:2
,05-25 13:51:24.485 10233 10233 I KnoxUsageLogPro: isEulaShown : false
05-25 13:51:24.485 10233 10233 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,05-25 13:51:24.495  3949  4133 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-25 13:51:24.505  3549  3859 D WifiNetworkAgent: NetworkAgent: NetworkAgent fully connected
,05-25 13:51:24.505  3549  3869 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -38]
05-25 13:51:24.505  3549  3869 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 503]
05-25 13:51:24.505  3549  3869 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,05-25 13:51:24.505  3549  3859 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,05-25 13:51:24.505  3549  4430 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e3440a5 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b397bc5 10247:com.samsung.android.sm.policy/u0a135}
,05-25 13:51:24.535  9936  9936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:51:24.555  3549  3603 D ActivityManager:  getDeferredInfo final delay 80
,05-25 13:51:24.625  3549  3859 E WifiNative-wlan0: do suspend false
,05-25 13:51:24.635  3549  3603 D ActivityManager:  getDeferredInfo final delay 80
,05-25 13:51:24.645  3549  3858 D WifiP2pService: InactiveState{ what=143375 }
,05-25 13:51:24.645  3549  3858 D WifiP2pService: P2pEnabledState{ what=143375 }
,05-25 13:51:24.695 10345 10345 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,05-25 13:51:24.695 10345 10345 I dhcpcd  : version 5.5.6 starting
,05-25 13:51:24.695 10345 10345 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,05-25 13:51:24.715  3549  3603 D ActivityManager:  getDeferredInfo final delay 80
,05-25 13:51:24.785 10345 10345 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,05-25 13:51:24.785 10345 10345 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
05-25 13:51:24.785 10345 10345 I dhcpcd  : bssid match
,05-25 13:51:24.785 10345 10345 I dhcpcd  : wlan0: rebinding lease of 192.168.1.137
,05-25 13:51:24.795  3549  3603 D ActivityManager:  getDeferredInfo final delay 80
,05-25 13:51:24.795  3549  4931 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-25 13:51:24.795  3549  4931 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4324, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:51:24.795  3549  4931 D BatteryService: online:4, current avg:0, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:69
,05-25 13:51:24.795  3549  3549 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:51:24.795  3549  3549 I MotionRecognitionService: Plugged
,05-25 13:51:24.795  3549  3549 D MotionRecognitionService:   cableConnection= 1
05-25 13:51:24.795  3549  3549 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:51:24.795  3549  3549 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:51:24.805  3549  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:51:24.805  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,05-25 13:51:24.805  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
05-25 13:51:24.805  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:51:24.815  4905  4905 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:51:24.825  4905  4905 D BatteryMonitor: new battery level: 100
,05-25 13:51:24.825 10053 10053 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,05-25 13:51:24.825 10053 10095 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-25 13:51:24.835  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:24.835  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:24.845  3549  6068 D SSRM:n  : SIOP:: AP = 340, PST = 331 (W:10), CP = 279, LCD = 40
,05-25 13:51:24.855  3549  6068 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:51:24.865  3549  3981 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,05-25 13:51:24.865  3549  3981 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4315, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:51:24.865  3549  3981 D BatteryService: online:4, current avg:0, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:10
05-25 13:51:24.865  3549  3549 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:51:24.865  3549  3549 I MotionRecognitionService: Plugged
05-25 13:51:24.865  3549  3549 D MotionRecognitionService:   cableConnection= 1
05-25 13:51:24.865  3549  3549 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:51:24.865  3549  3549 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:51:24.865  3549  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:51:24.865  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,05-25 13:51:24.865  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
05-25 13:51:24.865  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
,05-25 13:51:24.875 10345 10345 I dhcpcd  : wlan0: acknowledged 192.168.1.137 from 192.168.1.1
,05-25 13:51:24.875  4905  4905 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:51:24.875 10053 10053 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,05-25 13:51:24.875  3549  3603 D ActivityManager:  getDeferredInfo final delay 80
05-25 13:51:24.875 10053 10095 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-25 13:51:24.885  4905  4905 D BatteryMonitor: new battery level: 100
,05-25 13:51:24.895  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:24.895  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:24.955  3549  3603 D ActivityManager:  getDeferredInfo final delay 80
,05-25 13:51:24.965 10345 10345 I dhcpcd  : wlan0: leased 192.168.1.137 for 172800 seconds
,05-25 13:51:24.965  3549  3869 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,05-25 13:51:25.035  3549  3603 D ActivityManager:  getDeferredInfo final delay 80
,05-25 13:51:25.115  3549  3603 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:51:25.135  3549  3603 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{c3d5f08 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1381225 4984:android.process.media/u0a48}
,05-25 13:51:25.145  4984  4984 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,05-25 13:51:25.155  3549  4066 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:51:25.175 10367 10367 E Zygote  : v2
05-25 13:51:25.175 10367 10367 I libpersona: KNOX_SDCARD checking this for 1000
05-25 13:51:25.175 10367 10367 I libpersona: KNOX_SDCARD not a persona
,05-25 13:51:25.175 10367 10367 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-25 13:51:25.185 10367 10367 E Zygote  : accessInfo : 0
,05-25 13:51:25.185  3549  4066 I ActivityManager: Start proc 10367:com.samsung.android.SettingsReceiver/1000 for broadcast-5 com.samsung.android.SettingsReceiver/.SettingsIntentReceiver
,05-25 13:51:25.235 10367 10367 D TimaKeyStoreProvider: TimaSignature is unavailable
05-25 13:51:25.235 10367 10367 D ActivityThread: Added TimaKeyStore provider
,05-25 13:51:25.255  3549  3567 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{c3d5f08 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bf560a0 10367:com.samsung.android.SettingsReceiver/1000}
,05-25 13:51:25.265 10367 10367 W ResourcesManager: getTopLevelResources: /system/priv-app/SettingsReceiver/SettingsReceiver.apk / 1.0 running in com.samsung.android.SettingsReceiver rsrc of package com.samsung.android.SettingsReceiver
,05-25 13:51:25.265  3549  4435 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-25 13:51:25.265 10367 10367 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-25 13:51:25.265 10367 10367 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:51:25.275 10367 10367 I InjectionManager: Inside getClassLibPath caller 
,05-25 13:51:25.285 10367 10367 W System  : ClassLoader referenced unknown path: /system/priv-app/SettingsReceiver/lib/arm64
,05-25 13:51:25.285 10367 10367 D InjectionManager: InjectionManager
,05-25 13:51:25.285 10367 10367 D InjectionManager: fillFeatureStoreMap com.samsung.android.SettingsReceiver
05-25 13:51:25.285 10367 10367 I InjectionManager: Constructor com.samsung.android.SettingsReceiver, Feature store :{}
05-25 13:51:25.285 10367 10367 I InjectionManager: featureStore :{}
,05-25 13:51:25.295 10367 10367 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in com.samsung.android.SettingsReceiver rsrc of package com.android.settings
,05-25 13:51:25.295 10367 10367 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:51:25.305 10367 10367 E ActivityThread: Failed to find provider info for com.myscript.atk.rmc
,05-25 13:51:25.365  3549  4170 W ProcessCpuTracker: Skipping unknown process pid 10354
,05-25 13:51:25.365  3549  4170 W ProcessCpuTracker: Skipping unknown process pid 10385
,05-25 13:51:25.365  3549  4170 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:51:25.375 10389 10389 E Zygote  : v2
05-25 13:51:25.375 10389 10389 I libpersona: KNOX_SDCARD checking this for 10064
05-25 13:51:25.375 10389 10389 I libpersona: KNOX_SDCARD not a persona
,05-25 13:51:25.375 10389 10389 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-25 13:51:25.385 10389 10389 E Zygote  : accessInfo : 0
05-25 13:51:25.385 10389 10389 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.android.themestore 
,05-25 13:51:25.385  3549  4170 I ActivityManager: Start proc 10389:com.samsung.android.themestore/u0a64 for broadcast-5 com.samsung.android.themestore/.manager.autoSelfUpgradeService.AutoSelfUpgradeReceiver
,05-25 13:51:25.385  3549  4170 I ActivityManager: Killing 9106:com.samsung.android.asksmanager/u0a171 (adj 15): DHA:empty #33
,05-25 13:51:25.415 10389 10389 D TimaKeyStoreProvider: TimaSignature is unavailable
05-25 13:51:25.415 10389 10389 D ActivityThread: Added TimaKeyStore provider
,05-25 13:51:25.415  3549  3568 D ActivityManager: cleanUpApplicationRecord -- 9106
,05-25 13:51:25.425  3549  3568 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.asksmanager, Auto Run ON
,05-25 13:51:25.445  3549  4430 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{c3d5f08 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6ab1459 10389:com.samsung.android.themestore/u0a64}
,05-25 13:51:25.455 10389 10389 W ResourcesManager: getTopLevelResources: /system/priv-app/ThemeStore_3xh/ThemeStore_3xh.apk / 1.0 running in com.samsung.android.themestore rsrc of package com.samsung.android.themestore
,05-25 13:51:25.465  3549  4285 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-25 13:51:25.465 10389 10389 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-25 13:51:25.465  3549  3858 D WifiP2pService: InactiveState{ what=143375 }
,05-25 13:51:25.465  3549  3858 D WifiP2pService: P2pEnabledState{ what=143375 }
,05-25 13:51:25.465 10389 10389 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:51:25.465  3549  3869 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,05-25 13:51:25.465  3549  3859 D WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
05-25 13:51:25.475  3549  3869 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -38], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -38]
05-25 13:51:25.475  3549  3859 D WifiStateMachine: VerifyingLinkState enter
,05-25 13:51:25.475  3949  4133 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-25 13:51:25.475 10389 10389 I InjectionManager: Inside getClassLibPath caller 
,05-25 13:51:25.475  3549  3549 D WifiNotificationController: SHOW_NOTI_MESSAGE : 9, visible : false, ssid : "NG700", targetSSID : null, netId : -1, titleType : -1
05-25 13:51:25.475  3549  3869 E ConnectivityService: updateNetworkInfo()
,05-25 13:51:25.485  3549  3869 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}, oldLp = null
05-25 13:51:25.485  3549  3869 D ConnectivityService: Adding iface wlan0 to network 503
,05-25 13:51:25.485  3549  3549 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
05-25 13:51:25.485  3549  3549 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,05-25 13:51:25.485  3549  3549 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
05-25 13:51:25.485  3549  3867 I WifiHs20Service: Message received 5007
05-25 13:51:25.485 10389 10389 W System  : ClassLoader referenced unknown path: /system/priv-app/ThemeStore_3xh/lib/arm64
,05-25 13:51:25.495  3549  3549 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
,05-25 13:51:25.495  3549  3885 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,05-25 13:51:25.495  3549  3885 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}
05-25 13:51:25.495  3549  3885 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}
,05-25 13:51:25.495  3549  3885 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}
05-25 13:51:25.495  3549  3885 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}
,05-25 13:51:25.495  3949  4133 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-25 13:51:25.495  4260  4260 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,05-25 13:51:25.505 10389 10389 D a       : Exist Config : false
,05-25 13:51:25.505 10389 10389 D a       : getMcc
,05-25 13:51:25.505 10389 10389 D ai      : isQaMode
,05-25 13:51:25.515  3549  3603 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ce0f81e u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ec43a0e 10220:com.sec.android.diagmonagent/1000}
05-25 13:51:25.515  3549  3885 I WifiManager: isCaptivePortalException
05-25 13:51:25.515  3549  3885 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
05-25 13:51:25.515 10220 10220 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
05-25 13:51:25.515  3549  3885 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
05-25 13:51:25.515  3549  3885 D WifiWatchdogStateMachine: 3Captive portal check should be processed whether SNS option is on or off.
05-25 13:51:25.515  3549  3885 D WifiWatchdogStateMachine.CaptivePortalHandler: [checkCaptivePortal] - callbackHandler=Handler (com.android.server.wifi.WifiWatchdogStateMachine$CaptivePortalHandler) {48cc304}
05-25 13:51:25.515  3549  3885 I WifiManager: isCaptivePortalException
05-25 13:51:25.515  3549  3885 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
05-25 13:51:25.515  3549  3885 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
05-25 13:51:25.515 10220 10220 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
05-25 13:51:25.515 10220 10220 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
05-25 13:51:25.515 10220 10220 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,05-25 13:51:25.515  3549  3859 D WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to CONNECTED
05-25 13:51:25.515  3549  3869 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 503
,05-25 13:51:25.525  3549  3869 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,05-25 13:51:25.525 10389 10389 D a       : getMnc
05-25 13:51:25.525  3549  3869 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
05-25 13:51:25.525 10389 10389 D a       : getCsc
05-25 13:51:25.525 10389 10389 D a       : getSystemCountryCode
05-25 13:51:25.525 10389 10389 D a       : getImei
,05-25 13:51:25.525  3549  4170 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ce0f81e u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5d86d50 6413:com.enhance.gameservice/u0a106}
,05-25 13:51:25.525  3549  3869 E ConnectivityService: Unexpected mtu value: 0, wlan0
05-25 13:51:25.525  3549  3869 D ConnectivityService: Setting Dns servers for network 503 to [/192.168.1.1]
,05-25 13:51:25.525  3549  3859 D SecContentProvider: insert(), uri = 2
05-25 13:51:25.525 10389 10389 D ai      : getMd5HashString
,05-25 13:51:25.535 10389 10389 D ai      : getSha256HashString
,05-25 13:51:25.535 10389 10389 D a       : getMsisdn
,05-25 13:51:25.535  3549  3549 D WifiNotificationController: SHOW_NOTI_MESSAGE : 9, visible : false, ssid : "NG700", targetSSID : null, netId : -1, titleType : -1
,05-25 13:51:25.535  4260  4621 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,05-25 13:51:25.535  3549  3859 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
05-25 13:51:25.535  3549  3859 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
05-25 13:51:25.535  3549  3869 V NetworkStats: updateIfacesLocked()
05-25 13:51:25.535  3549  3869 D NtpTrustedTime: currentTimeMillis() cache hit
05-25 13:51:25.535  3549  3869 V NetworkStats: performPollLocked(flags=0x1)
05-25 13:51:25.535  3549  3549 I WifiTrafficPoller: evaluateTrafficStatsPolling
05-25 13:51:25.535  3549  3549 D WifiNative-wlan0: callSECApiVoid - ID [212]
,05-25 13:51:25.535 10246 10246 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
05-25 13:51:25.535 10246 10246 I wpa_supplicant: P2P: Current p2p state = IDLE
,05-25 13:51:25.545  3549  3869 D NetworkStatsRecorder: entry.iface is null
05-25 13:51:25.545  3549  3869 D NetworkStatsRecorder: entry.iface is null
05-25 13:51:25.545  3549  3869 D NetworkStatsRecorder: entry.iface is null
05-25 13:51:25.545  3549  3869 D NetworkStatsRecorder: entry.iface is null
,05-25 13:51:25.545 10246 10246 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
05-25 13:51:25.545  3549  3869 V NetworkStats: performPollLocked() took 7ms
05-25 13:51:25.545  3549  3869 D NtpTrustedTime: currentTimeMillis() cache hit
,05-25 13:51:25.545  3549  3549 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
05-25 13:51:25.545  3549  3549 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
05-25 13:51:25.545  3549  3549 D HS20StateMachine: SSID : "NG700"
05-25 13:51:25.545  3549  3549 D HS20StateMachine: NetId : 4
05-25 13:51:25.545  3549  3549 D HS20StateMachine: checkifOSUAP  null
,05-25 13:51:25.545 10389 10389 D a       : getModelName
05-25 13:51:25.545  3549  3549 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
05-25 13:51:25.545 10389 10389 D a       : getVirtualModelName
05-25 13:51:25.545  3549  3867 I WifiHs20Service: Message received 5007
05-25 13:51:25.545 10389 10389 D a       : getAndroidSDKVersion
05-25 13:51:25.545 10389 10389 D a       : getLanguageCode
05-25 13:51:25.545 10389 10389 D a       : getCountryCode
,05-25 13:51:25.545  3549  3549 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
,05-25 13:51:25.545 10389 10389 D a       : getNetworkType
,05-25 13:51:25.555  3949  4133 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-25 13:51:25.555  3549  4931 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
05-25 13:51:25.555  4260  4260 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,05-25 13:51:25.555 10389 10389 D t       : isSupportedAodSystemFeature
,05-25 13:51:25.565 10389 10389 D a       : isLogPrintMode
,05-25 13:51:25.565  3549  4420 D SecContentProvider2: query(), uri = 15 selection = getToastGravityEnabledState
,05-25 13:51:25.565 10389 10389 D ai      : isQaMode
,05-25 13:51:25.565  3549  3603 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ce0f81e u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{620523c 10233:com.sec.knox.switcher/1000}
,05-25 13:51:25.565 10233 10233 I usagelog: received in receiver
05-25 13:51:25.565 10233 10233 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
05-25 13:51:25.565 10233 10233 I KnoxUsageLogPro: premStatus:2
,05-25 13:51:25.575 10389 10389 D a       : getVerName
05-25 13:51:25.575  3549  3869 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-25 13:51:25.575  3549  3869 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -38]
05-25 13:51:25.575  3549  3869 D ConnectivityService: Not required to send intent.
05-25 13:51:25.575  3549  3869 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
05-25 13:51:25.575  3549  3869 E ConnectivityService: updateNetworkInfo()
05-25 13:51:25.575  3549  3869 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = CONNECTING
05-25 13:51:25.575  3549  3869 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -38]
,05-25 13:51:25.575  3549  3869 V NetworkStats: updateIfacesLocked()
05-25 13:51:25.575  3549  3869 D NtpTrustedTime: currentTimeMillis() cache hit
05-25 13:51:25.575  3549  3869 V NetworkStats: performPollLocked(flags=0x1)
,05-25 13:51:25.585  3549  3869 D NetworkStatsRecorder: entry.iface is null
05-25 13:51:25.585  3549  3869 D NetworkStatsRecorder: entry.iface is null
05-25 13:51:25.585  3549  3869 D NetworkStatsRecorder: entry.iface is null
05-25 13:51:25.585  3549  3869 D NetworkStatsRecorder: entry.iface is null
,05-25 13:51:25.585  3549  3869 D NtpTrustedTime: currentTimeMillis() cache hit
05-25 13:51:25.585  3549  3869 V NetworkStats: performPollLocked() took 11ms
05-25 13:51:25.585 10233 10233 I KnoxUsageLogPro: isEulaShown : false
05-25 13:51:25.585 10233 10233 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,05-25 13:51:25.585  3549  3857 D NtpTrustedTime: currentTimeMillis() cache hit
05-25 13:51:25.585  3549  3857 D NtpTrustedTime: currentTimeMillis() cache hit
,05-25 13:51:25.595 10389 10389 D a       : getVerCode
05-25 13:51:25.595  3549  4285 D SecContentProvider2: query(), uri = 15 selection = getToastEnabledState
,05-25 13:51:25.595 10389 10389 D a       : getPackageName
05-25 13:51:25.595 10389 10389 D a       : getAutoUpgradeInterval
,05-25 13:51:25.595 10389 10389 D a       : loadCountrySearchEx
,05-25 13:51:25.595  3549  3567 D SecContentProvider2: query(), uri = 15 selection = getToastShowPackageNameState
,05-25 13:51:25.605 10389 10389 I a       : voCountrySearchEx loaded.
,05-25 13:51:25.605 10389 10389 I a       : # initConfig Time : 106
05-25 13:51:25.605  3549  4170 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ce0f81e u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b397bc5 10247:com.samsung.android.sm.policy/u0a135}
05-25 13:51:25.605 10389 10389 I a       : ● MCCNNC : 260 0
05-25 13:51:25.605 10389 10389 I a       : ● Model : SM-G930F_TM
05-25 13:51:25.605 10389 10389 I a       : ● MyApp Vertion : 1.03.22(20160524)
05-25 13:51:25.605 10389 10389 I a       : ● OS Vertion : 23
,05-25 13:51:25.615  3549 10343 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
05-25 13:51:25.615  3549  3869 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-25 13:51:25.615  3549 10343 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: Connected
05-25 13:51:25.615  3549  3869 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -38]
05-25 13:51:25.615  3549 10343 D NetworkMonitor: registerReceiver Captive portal receiver
05-25 13:51:25.615  3549  3869 D ConnectivityService: scheduleUnvalidatedPrompt 503
05-25 13:51:25.615  3549  3869 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 503]
05-25 13:51:25.615  3549  3869 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
05-25 13:51:25.615  3549  3869 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -38]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,05-25 13:51:25.615  3549  3859 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,05-25 13:51:25.615  3549  3859 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,05-25 13:51:25.615  3549  3857 D NtpTrustedTime: currentTimeMillis() cache hit
05-25 13:51:25.625  3549  3857 D NtpTrustedTime: currentTimeMillis() cache hit
,05-25 13:51:25.625  3549 10343 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
05-25 13:51:25.625 10389 10389 D InjectionManager: InjectionManager
05-25 13:51:25.625  3549 10343 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: Validated
05-25 13:51:25.625 10389 10389 D InjectionManager: fillFeatureStoreMap com.samsung.android.themestore
05-25 13:51:25.625 10389 10389 I InjectionManager: Constructor com.samsung.android.themestore, Feature store :{}
05-25 13:51:25.625 10389 10389 I InjectionManager: featureStore :{}
,05-25 13:51:25.625 10389 10389 D AutoSelfUpgradeReceiver: onReceive() android.net.conn.CONNECTIVITY_CHANGE
,05-25 13:51:25.635  3549  4170 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{10aa3b8 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ec43a0e 10220:com.sec.android.diagmonagent/1000}
,05-25 13:51:25.635 10220 10220 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,05-25 13:51:25.635 10220 10220 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
05-25 13:51:25.635 10220 10220 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
,05-25 13:51:25.635 10220 10220 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 android.content.ContextWrapper.sendBroadcast:410 android.content.ContextWrapper.sendBroadcast:410 com.sec.android.diagmonagent.DiagMonConnectivityChangeReciever.onReceive:19 android.app.ActivityThread.handleReceiver:3635 
,05-25 13:51:25.645  3549  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: true
,05-25 13:51:25.645  3549  4931 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:51:25.645  3549  3869 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,05-25 13:51:25.645  4260  4623 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
05-25 13:51:25.645  4260  4623 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
05-25 13:51:25.645  3549  3869 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
05-25 13:51:25.645  3549  3869 D ConnectivityService: currentScore = 0, newScore = 20
05-25 13:51:25.645  3549  3869 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 503]
05-25 13:51:25.645  3549  3869 D ConnectivityService:    accepting network in place of null
05-25 13:51:25.645  3549  3859 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:51:25.645  3549  3869 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:51:25.645  3549  3859 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-25 13:51:25.645  3549  3859 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
05-25 13:51:25.645  3549  3859 D WIFI    : evalRequest
05-25 13:51:25.645  3549  3859 D WIFI    :   done
05-25 13:51:25.645  3549  3859 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:51:25.645  3549  3859 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-25 13:51:25.645  3549  3859 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
05-25 13:51:25.645  3549  3859 D WIFI    : evalRequest
05-25 13:51:25.645  3549  3859 D WIFI    :   done
05-25 13:51:25.645  3549  3859 D WIFI_UT : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:51:25.645  3549  3859 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-25 13:51:25.655  3549  3859 D WIFI_UT : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
05-25 13:51:25.655  3549  3859 D WIFI_UT : evalRequest
05-25 13:51:25.655  3549  3859 D WIFI_UT :   done
05-25 13:51:25.655  3549  3858 D WIFI_P2P: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:51:25.655  3549  3858 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-25 13:51:25.655  3549  3858 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
05-25 13:51:25.655  3549  3858 D WIFI_P2P: evalRequest
05-25 13:51:25.655  3549  3858 D WIFI_P2P:   done
05-25 13:51:25.655  3549  3894 D Ethernet: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:51:25.655  3549  3894 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
05-25 13:51:25.655  3549  3894 D Ethernet: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
05-25 13:51:25.655  3549  3894 D Ethernet: evalRequest
05-25 13:51:25.655  3549  3894 D Ethernet:   done
05-25 13:51:25.655  3949  4133 D ViewRootImpl: #1 mView = android.widget.LinearLayout{cfca1d0 V.E...... ......I. 0,0-0,0 #102039c android:id/toast_layout_root}
05-25 13:51:25.655  3949  3949 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 272
,05-25 13:51:25.665  3549  4435 D ISSUE_DEBUG: InputChannelName : 225ecf6 Toast
05-25 13:51:25.665  3549  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-25 13:51:25.665  3549  4435 V MARsPolicyManager: handelAlertToastWindowStarted pkgName = com.android.systemui
,05-25 13:51:25.665  3549  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,05-25 13:51:25.665 10411 10411 E Zygote  : v2
05-25 13:51:25.665 10411 10411 I libpersona: KNOX_SDCARD checking this for 5009
05-25 13:51:25.665 10411 10411 I libpersona: KNOX_SDCARD not a persona
05-25 13:51:25.665 10411 10411 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-25 13:51:25.665 10411 10411 E Zygote  : accessInfo : 0
05-25 13:51:25.665 10411 10411 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.scloud:contentsync 
,05-25 13:51:25.675  3549  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-25 13:51:25.675  3549  4931 I ActivityManager: Start proc 10411:com.samsung.android.scloud:contentsync/5009 for broadcast-5 com.samsung.android.scloud/.cloudagent.detector.DetectorReceiver
,05-25 13:51:25.675  3011  3011 I SurfaceFlinger: id=20 createSurf (1x1),1 flag=4, Uoast
,05-25 13:51:25.685  3549  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-25 13:51:25.685  3549  3560 I art     : Background sticky concurrent mark sweep GC freed 172239(13MB) AllocSpace objects, 66(1320KB) LOS objects, 28% free, 36MB/51MB, paused 3.254ms total 106.655ms
05-25 13:51:25.685  3549  4430 I ActivityManager: Killing 9144:com.samsung.svoice.sync/u0a40 (adj 15): DHA:empty #33
,05-25 13:51:25.705  3549  4430 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{10aa3b8 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5d86d50 6413:com.enhance.gameservice/u0a106}
,05-25 13:51:25.705  3549  4432 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3549
,05-25 13:51:25.715 10411 10411 D TimaKeyStoreProvider: TimaSignature is unavailable
05-25 13:51:25.715 10411 10411 D ActivityThread: Added TimaKeyStore provider
,05-25 13:51:25.725  3549  4066 D ActivityManager: cleanUpApplicationRecord -- 9144
,05-25 13:51:25.725  3549  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-25 13:51:25.725  3549  4066 D ActivityManager: isAutoRunBlockedApp:: com.samsung.svoice.sync, Auto Run ON
,05-25 13:51:25.735  3949  4130 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1033x201]-format:1
,05-25 13:51:25.745  3549  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,05-25 13:51:25.745  3549  3869 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -38]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
05-25 13:51:25.745  3949  4133 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
05-25 13:51:25.745  3549  3986 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{10aa3b8 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{620523c 10233:com.sec.knox.switcher/1000}
05-25 13:51:25.745 10233 10233 I usagelog: received in receiver
05-25 13:51:25.745 10233 10233 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
05-25 13:51:25.745 10233 10233 I KnoxUsageLogPro: premStatus:2
05-25 13:51:25.755 10233 10233 I KnoxUsageLogPro: isEulaShown : false
05-25 13:51:25.755 10233 10233 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,05-25 13:51:25.755  3549  4931 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{c3d5f08 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5a24364 10411:com.samsung.android.scloud:contentsync/5009}
,05-25 13:51:25.755  3949  4133 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,05-25 13:51:25.765  3157  3613 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,05-25 13:51:25.785  3549  4066 V WindowStateAnimator: Finishing drawing window Window{225ecf6 u0 d0 Toast}: mDrawState=DRAW_PENDING
,05-25 13:51:25.785  3549  3567 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{10aa3b8 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b397bc5 10247:com.samsung.android.sm.policy/u0a135}
,05-25 13:51:25.785  3011  3011 D libEGL  : eglInitialize EGLDisplay = 0x7fcec79e68
05-25 13:51:25.795  3157  3613 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,05-25 13:51:25.795  3549  3869 D ConnectivityService: 503 network ip type : v4
,05-25 13:51:25.795  3549  3869 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:51:25.795  3549  3869 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:51:25.795 10411 10411 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.samsung.android.scloud
,05-25 13:51:25.795  3549  3869 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:51:25.805  3549  3869 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:51:25.815  3549  3869 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=5, legacyType=-1, [] ]
,05-25 13:51:25.815  3549  3869 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -38]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} } for legacy network type 1
05-25 13:51:25.815  3549  3869 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
05-25 13:51:25.815  3549  3869 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,05-25 13:51:25.815  3549  3838 D ConnectivityService: getVpnConfig > userId : 0
,05-25 13:51:25.825  3549  4435 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-25 13:51:25.825  3549  3619 D EntConnectivity: Not allowed due to - mEnabled false
05-25 13:51:25.825 10411 10411 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
05-25 13:51:25.825 10411 10411 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:51:25.825  3549  3889 D WifiWatchdogStateMachine.CaptivePortalHandler: start check captive portal 
,05-25 13:51:25.835 10220 10220 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: com.sec.android.diagmonagent.intent.NETWORK_CHANGED
05-25 13:51:25.835  3549  4170 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{40f3d93 u0 com.sec.android.diagmonagent.intent.NETWORK_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ec43a0e 10220:com.sec.android.diagmonagent/1000}
05-25 13:51:25.835  3549  3619 D EntConnectivity: Not allowed due to - mEnabled false
05-25 13:51:25.835 10220 10220 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
,05-25 13:51:25.835 10220 10220 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(67/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,05-25 13:51:25.845 10411 10411 I InjectionManager: Inside getClassLibPath caller 
,05-25 13:51:25.845  3549  3869 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -38]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
05-25 13:51:25.845  3549  3869 D ConnectivityService: unneeded: NetworkRequestInfo for = Request from uid/pid:1000/3549 for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:51:25.845  3549  3869 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
05-25 13:51:25.845  3549  3869 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
05-25 13:51:25.845  3549  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:51:25.845  3549  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:51:25.845  3549  3869 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:51:25.845  3549  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
,05-25 13:51:25.845  3549  3869 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=5, legacyType=-1, [] ]
,05-25 13:51:25.845  3549  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:51:25.845  3549  3869 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:51:25.845  3549  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:51:25.845  3549  3869 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:51:25.845  3549  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:51:25.845  3549  3869 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:51:25.845  3549  3869 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
05-25 13:51:25.855  3549  3869 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] validation  passed
05-25 13:51:25.855  3549  3869 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -38], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -38]
05-25 13:51:25.855  3549  3869 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
,05-25 13:51:25.855 10411 10411 W System  : ClassLoader referenced unknown path: /system/priv-app/SamsungCloud/lib/arm64
,05-25 13:51:25.855  3549  3869 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -38]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
05-25 13:51:25.855  3549  3549 D Tethering: Tethering got CONNECTIVITY_ACTION
05-25 13:51:25.855  3549  3619 D Tethering: MasterInitialState.processMessage what=3
,05-25 13:51:25.855  3549  3549 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
05-25 13:51:25.855  3549  3549 I CLocInfoService: ['16.5] External Intent Received android.net.conn.CONNECTIVITY_CHANGE
05-25 13:51:25.855  3549  3549 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
05-25 13:51:25.855  3549  3549 I CLocInfoService: CLocinfo wifi true 
,05-25 13:51:25.865  3949  4133 D NetworkController: onReceive: intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-25 13:51:25.865  3549  3601 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
05-25 13:51:25.865  3549  3601 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
05-25 13:51:25.865  3549  3601 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,05-25 13:51:25.865  3549  4212 V AlarmManager:  remove PendingIntent] PendingIntent{41bdc30: PendingIntentRecord{a1390a9 android broadcastIntent}}
,05-25 13:51:25.875  3549  3871 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,05-25 13:51:25.875  4260  4621 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
05-25 13:51:25.875  4260  4621 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,05-25 13:51:25.875  3549  3871 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,05-25 13:51:25.885  3549  3869 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
,05-25 13:51:25.895  3549  3549 V MARsPolicyManager: DataConnection: true
,05-25 13:51:25.905  4782  4782 D SamsungIME: EngineType = SWIFTKEY
,05-25 13:51:25.905  4905  5035 D CellLocationSupport: onReceive ACTION = android.net.conn.CONNECTIVITY_CHANGE
05-25 13:51:25.905  4905  5035 I CellLocationSupport: onCellLocationChanged
05-25 13:51:25.905  4782  4782 D SamsungIME: mNetworkChangeReceiver isWLANConnected : true
05-25 13:51:25.905  3549  3857 D NtpTrustedTime: currentTimeMillis() cache hit
05-25 13:51:25.905  3549  3857 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-25 13:51:25.905  3549  3857 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -38]
05-25 13:51:25.905  3549  3857 D NtpTrustedTime: currentTimeMillis() cache hit
05-25 13:51:25.905  3549  3857 D NtpTrustedTime: currentTimeMillis() cache hit
05-25 13:51:25.905  3549  3857 D NtpTrustedTime: currentTimeMillis() cache hit
05-25 13:51:25.905  3549  3857 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
,05-25 13:51:25.905 10411 10411 I [SC]CloudManager: requestInit
,05-25 13:51:25.915  3549  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-25 13:51:25.925  4905  4905 D PdnController: CONNECTIVITY_ACTION: networkType 1 isConnected true
,05-25 13:51:25.925  4905  4905 D PdnController: isSuspended [false] networktype [1]
,05-25 13:51:25.925  3549  3838 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
05-25 13:51:25.925  4905  4905 D PdnController: Updated Interface [wlan0] For Network [1]
,05-25 13:51:25.925  4905  4905 D PdnController: isPdnUp  [true] networktype [1]
05-25 13:51:25.925  4905  4905 D PdnController: Notify Result to LocalIP Registrants! : networkType [1] isConnected [true] 
,05-25 13:51:25.935  5475  5475 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@fef2a46 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-25 13:51:25.935  4905  5035 I CellLocationSupport: Block to update PANI information in non VoWIFI
05-25 13:51:25.935  4905  5035 D SlickSSConfigHandler: EVENT_LOCAL_IP_CHANGED
,05-25 13:51:25.935  3549  4430 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:51:25.935  5475  5475 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,05-25 13:51:25.935  4905  5035 D PdnController: isIfaceDisconnected result [true] networkType [0] interfaceName [null] 
05-25 13:51:25.935  4905  5035 D PdnController: isPdnUp  [false] networktype [0]
05-25 13:51:25.935  4905  5035 D SlickSSConfigHandler: handleNetworkStateChange: check isDefaultPDNConnected[false], mReadyForDocFetch[false
05-25 13:51:25.945  3549  3567 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,05-25 13:51:25.945  6737  6737 I FOTA_AGENT: [lIlIIlIlIlIllllllIII(91/llllIIIllIlIIIIllllI)] WiFi Network is connected
,05-25 13:51:25.945  3549  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,05-25 13:51:25.945  4905  5035 D RegistrationManager: handleMessage(): 5
,05-25 13:51:25.945  3549  4430 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:51:25.955  4905  5035 D PdnController: isIfaceDisconnected result [true] networkType [11] interfaceName [null] 
05-25 13:51:25.955  4905  5035 D PdnController: isPdnUp  [false] networktype [11]
05-25 13:51:25.955  4905  5035 D RegistrationManager: setEPDGIPSecConnected [false]
05-25 13:51:25.955  4905  5035 D RegistrationManager: notifyNetworkState : NetworkType [1] IsConnected [true] IPAddresses [[/192.168.1.137]] DNSAddresses [[/192.168.1.1]] 
05-25 13:51:25.955  4905  5035 D RegistrationManager: isEPDGAvailable [false]
05-25 13:51:25.955  4905  5035 D RegistrationManager: setWifiPreparedOnAPM [true]
,05-25 13:51:25.955  3549  4367 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,05-25 13:51:25.965  9159  9159 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 com.samsung.SMT.SamsungTTSService.g:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.c.onReceive:-1 
,05-25 13:51:25.965  4199  4199 D FusedRequestManager: manageLocationRequest, new passive request from com.samsung.voiceserviceplatform with b0baa04 , interval = 1800000 through LocationManagerService
,05-25 13:51:25.975  3549  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-25 13:51:25.985  3157  3609 D EnterpriseController: netId is 0
05-25 13:51:25.985  3157  3609 D Netd    : getNetworkForDns: using netid 503 for uid 10001
05-25 13:51:25.985  3549  3888 D WifiWatchdogStateMachine: response code : 204
,05-25 13:51:25.985  4905  5035 D TranslatorCollection: translateToNwkSvcType: networkType XAN_NWK_TYPE_WLAN
05-25 13:51:25.985  4905  5035 D RegistrationManager: getNetworkType [0]
05-25 13:51:25.985  4905  5035 D CoreStackAdaptor2: notifyNetworkState() [1] isConnected [true] nwkSvcType  [XAN_NWK_TYPE_WLAN] nwkInfoType [XAN_SVC_NETWORK_SVCTYPE_WIFI] dedicated   [NONE] 
05-25 13:51:25.985  4905  5035 D CellLocationSupport: Siso Stack not called RegisterAN yet on XAN_NWK_TYPE_WLAN
,05-25 13:51:25.995  4905  5035 D TranslatorCollection: translateToNwkSvcType: networkType XAN_NWK_TYPE_WLAN
,05-25 13:51:25.995  4905  5035 D CoreStackAdaptor2: ipList Not Null[/192.168.1.137]
05-25 13:51:25.995  4905  5035 D RegistrationManager: tryRegister(CONNECTIVITY_STATUS_CHANGE)
05-25 13:51:25.995  4905  5035 D RegistrationManager: isPreconditionProperToGoOn
05-25 13:51:25.995  4905  5035 D RegistrationManager: isDeviceShutdown [false]
05-25 13:51:25.995  4905  5035 D RegistrationManager: isStackShuttingDownForAllPDNs [false]
05-25 13:51:25.995  4905  5035 D RegistrationManager: isDmVoLTEUpdated [false]
05-25 13:51:25.995  4905  5035 D RegistrationManager: tryRegister : Abort Reason [IMS feature disabled]
05-25 13:51:25.995  4905  5035 D RegistrationManager: tryRegister : Not all preconditions are met!
,05-25 13:51:25.995 10411 10411 I [SC]Utils: folder : cachecreate fail, try again.
05-25 13:51:25.995 10411 10411 I [SC]Utils: folder : cache create fail.
,05-25 13:51:25.995 10411 10411 I [SC]Utils: folder : thumbnailcreate fail, try again.
05-25 13:51:25.995 10411 10411 I [SC]Utils: folder : thumbnail create fail.
05-25 13:51:25.995 10411 10411 I [SC]Utils: folder : sharecreate fail, try again.
,05-25 13:51:25.995 10411 10411 I [SC]Utils: folder : share create fail.
05-25 13:51:25.995 10411 10411 I [SC]Utils: folder : scratchcreate fail, try again.
05-25 13:51:25.995 10411 10411 I [SC]Utils: folder : scratch create fail.
,05-25 13:51:25.995 10411 10411 I [SC]Utils: folder : eventSynccreate fail, try again.
,05-25 13:51:25.995 10411 10411 I [SC]Utils: folder : eventSync create fail.
,05-25 13:51:26.005  3549  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-25 13:51:26.005  3549  3889 D WifiWatchdogStateMachine.CaptivePortalHandler: result = 0, mCaptivePortalCheckMode = 11, mCouldNotIdentifyCaptivePortalState = true
,05-25 13:51:26.015  9936  9936 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,05-25 13:51:26.025  4416  4416 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,05-25 13:51:26.045 10284 10294 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(86/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
,05-25 13:51:26.045 10284 10294 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(86/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
,05-25 13:51:26.055 10284 10294 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(43/llIIIIlllllIIllIIllI)] already Eula Agree
,05-25 13:51:26.065  9936  9936 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,05-25 13:51:26.065  3549  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-25 13:51:26.075 10284 10295 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(86/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
,05-25 13:51:26.075  4865  4865 E audit   : type=1400 msg=audit(1495713086.075:278): avc:  denied  { ioctl } for  pid=7036 comm="ChromiumNet" path="socket:[42174]" dev="sockfs" ino=42174 ioctlcmd=8b1b scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=udp_socket permissive=0
05-25 13:51:26.075  4865  4865 E audit   :  SEPF_SECMOBILE_6.0.1_0031
05-25 13:51:26.075  4865  4865 E audit   : type=1300 msg=audit(1495713086.075:278): arch=c00000b7 syscall=29 success=no exit=-13 a0=19 a1=8b1b a2=7f78143cc8 a3=7f78143c90 items=0 ppid=3183 pid=7036 auid=4294967295 uid=10068 gid=10068 euid=10068 suid=10068 fsuid=10068 egid=10068 sgid=10068 fsgid=10068 tty=(none) ses=4294967295 comm="ChromiumNet" exe="/system/bin/app_process64" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
05-25 13:51:26.075  4865  4865 E audit   : type=1327 msg=audit(1495713086.075:278): proctitle="com.google.android.googlequicksearchbox:search"
05-25 13:51:26.075  4865  4865 E audit   : type=1320 msg=audit(1495713086.075:278): 
05-25 13:51:26.075  4865  4865 E audit   : type=1400 msg=audit(1495713086.075:279): avc:  denied  { ioctl } for  pid=7036 comm="ChromiumNet" path="socket:[42175]" dev="sockfs" ino=42175 ioctlcmd=8b1b scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=udp_socket permissive=0
05-25 13:51:26.075  4865  4865 E audit   :  SEPF_SECMOBILE_6.0.1_0031
05-25 13:51:26.075  4865  4865 E audit   : type=1300 msg=audit(1495713086.075:279): arch=c00000b7 syscall=29 success=no exit=-13 a0=19 a1=8b1b a2=7f78143cc8 a3=7f78143c90 items=0 ppid=3183 pid=7036 auid=4294967295 uid=10068 gid=10068 euid=10068 suid=10068 fsuid=10068 egid=10068 sgid=10068 fsgid=10068 tty=(none) ses=4294967295 comm="ChromiumNet" exe="/system/bin/app_process64" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
05-25 13:51:26.075 10284 10295 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(86/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
05-25 13:51:26.075  4865  4865 E audit   : type=1327 msg=audit(1495713086.075:279): proctitle="com.google.android.googlequicksearchbox:search"
05-25 13:51:26.075  4865  4865 E audit   : type=1320 msg=audit(1495713086.075:279): 
,05-25 13:51:26.075 10284 10295 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(43/llIIIIlllllIIllIIllI)] already Eula Agree
,05-25 13:51:26.085 10411 10411 V SamsungCloudLogs:  set Log level [4->4]act[false]
,05-25 13:51:26.085 10411 10411 I [SC]CommonUtil: isSemAvailable:0
,05-25 13:51:26.105  9936  9936 D BluetoothAdapter: STATE_ON
,05-25 13:51:26.105  3549  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
05-25 13:51:26.105  3549  3869 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -38]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
05-25 13:51:26.105  3549  3869 D ConnectivityService: unneeded: NetworkRequestInfo for = Request from uid/pid:1000/3549 for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:51:26.105  3549  3869 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
05-25 13:51:26.105  3549  3869 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 503]
05-25 13:51:26.105  3549  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:51:26.105 10411 10411 I [SC]SamsungCloudApp: AppVer[2.1.14][L:4]Sem[false]V21MAIN_R slog[false]com.samsung.android.scloud:contentsync
05-25 13:51:26.105  3549  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:51:26.105 10411 10411 D InjectionManager: InjectionManager
05-25 13:51:26.105  3549  3869 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:51:26.105 10411 10411 D InjectionManager: fillFeatureStoreMap com.samsung.android.scloud
05-25 13:51:26.105  3549  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
05-25 13:51:26.105  3549  3869 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=5, legacyType=-1, [] ]
,05-25 13:51:26.105  3549  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:51:26.105  3549  3869 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:51:26.105 10411 10411 I InjectionManager: Constructor com.samsung.android.scloud, Feature store :{}
05-25 13:51:26.105 10411 10411 I InjectionManager: featureStore :{}
05-25 13:51:26.105 10438 10438 I libpersona: KNOX_SDCARD checking this for 1000
05-25 13:51:26.105 10438 10438 E Zygote  : v2
05-25 13:51:26.105 10438 10438 I libpersona: KNOX_SDCARD not a persona
,05-25 13:51:26.105 10438 10438 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
05-25 13:51:26.105  3549  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:51:26.105  3549  3869 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:51:26.115  3549  4435 I ActivityManager: Start proc 10438:com.sec.android.soagent/1000 for content provider com.sec.android.soagent/.log.MasterLogProvider
05-25 13:51:26.115 10438 10438 E Zygote  : accessInfo : 0
,05-25 13:51:26.115 10411 10411 I [SC]FeatureManager: FeatureManager 
05-25 13:51:26.115 10411 10411 I [SC]FeatureManager: [SEC_FLOATING_FEATURE_SAMSUNGCLOUD_CONFIG_CLOUD_USAGE_MENU_TREE]str 
05-25 13:51:26.115 10411 10411 I [SC]FeatureManager: [SEC_FLOATING_FEATURE_SAMSUNGCLOUD_ENABLE_SETTING_MENU]bln true
05-25 13:51:26.115  3549  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:51:26.115  3549  3869 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:51:26.115  3549  3869 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:51:26.115  3549  3858 D WIFI_P2P: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:51:26.115  3549  3858 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-25 13:51:26.115  3549  3858 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
05-25 13:51:26.115  3549  3858 D WIFI_P2P: evalRequest
05-25 13:51:26.115  3549  3858 D WIFI_P2P:   done
05-25 13:51:26.115  3549  3859 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:51:26.115  3549  3859 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-25 13:51:26.115 10411 10411 E [SC]SCLOUD_ERR-Utils: isShipMode : 1 
05-25 13:51:26.115  3549  3859 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
05-25 13:51:26.115  3549  3859 D WIFI    : evalRequest
05-25 13:51:26.115  3549  3859 D WIFI    :   done
05-25 13:51:26.115  3549  3859 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:51:26.115  3549  3859 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-25 13:51:26.115  3549  3859 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
05-25 13:51:26.115  3549  3859 D WIFI    : evalRequest
05-25 13:51:26.115  3549  3859 D WIFI    :   done
,05-25 13:51:26.115  3549  3859 D WIFI_UT : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:51:26.115  3549  3859 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-25 13:51:26.115  3549  3859 D WIFI_UT : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
05-25 13:51:26.115  3549  3859 D WIFI_UT : evalRequest
05-25 13:51:26.115  3549  3859 D WIFI_UT :   done
05-25 13:51:26.115  9936  9936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-25 13:51:26.115  9936  9936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-25 13:51:26.115  9936  9936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-25 13:51:26.115  9936  9936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-25 13:51:26.115  9936  9936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-25 13:51:26.115  9936  9936 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-25 13:51:26.115  9936  9936 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-25 13:51:26.115  9936  9936 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-25 13:51:26.115  9936  9936 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,05-25 13:51:26.115  3549  3869 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
05-25 13:51:26.115  3549  3894 D Ethernet: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:51:26.115  3549  3894 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
05-25 13:51:26.115  3549  3894 D Ethernet: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,05-25 13:51:26.115  3549  3894 D Ethernet: evalRequest
05-25 13:51:26.115  3549  3894 D Ethernet:   done
,05-25 13:51:26.125  3549  3859 D WifiNetworkAgent: NetworkAgent: CMD_REPORT_NETWORK_STATUS(VALID)
05-25 13:51:26.125  3549  3859 D WifiNetworkAgent: NetworkAgent: CMD_REPORT_NETWORK_STATUS(1)
,05-25 13:51:26.125 10411 10411 I [SC]DetectorReceiver: onReceive [android.net.conn.CONNECTIVITY_CHANGE]
05-25 13:51:26.125 10411 10411 I [SC]CloudManager: requestInit
05-25 13:51:26.125 10411 10411 I [SC]Utils: folder : cachecreate fail, try again.
,05-25 13:51:26.125 10411 10411 I [SC]Utils: folder : cache create fail.
05-25 13:51:26.125 10411 10411 I [SC]Utils: folder : thumbnailcreate fail, try again.
,05-25 13:51:26.125 10411 10411 I [SC]Utils: folder : thumbnail create fail.
05-25 13:51:26.125  3549  3859 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
05-25 13:51:26.125  3549  3859 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
05-25 13:51:26.125  3549  3859 D WifiStateMachine: sendBroadcastForCaptivePortalNotLoginIcon : false
05-25 13:51:26.125 10411 10411 I [SC]Utils: folder : sharecreate fail, try again.
05-25 13:51:26.125 10411 10411 I [SC]Utils: folder : share create fail.
,05-25 13:51:26.125 10411 10411 I [SC]Utils: folder : scratchcreate fail, try again.
,05-25 13:51:26.135 10411 10411 I [SC]Utils: folder : scratch create fail.
05-25 13:51:26.135 10411 10411 I [SC]Utils: folder : eventSynccreate fail, try again.
05-25 13:51:26.135  3949  4133 D NetworkController: onReceive: intent=Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
05-25 13:51:26.135 10411 10411 I [SC]Utils: folder : eventSync create fail.
,05-25 13:51:26.135  3549  3859 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
,05-25 13:51:26.135  9936  9936 D BluetoothAdapter: STATE_ON
,05-25 13:51:26.135  9936  9936 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,05-25 13:51:26.145  3549  3859 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
,05-25 13:51:26.145 10438 10438 D TimaKeyStoreProvider: TimaSignature is unavailable
05-25 13:51:26.145 10438 10438 D ActivityThread: Added TimaKeyStore provider
,05-25 13:51:26.145  4260  4272 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
05-25 13:51:26.145  4260  4272 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,05-25 13:51:26.155  7288  7299 I SA      : [SCU] isHaveSA() - false
05-25 13:51:26.155  7288  7299 I SA      : [OCP] Samsung account is not Signed-in
05-25 13:51:26.155  3949  4133 D NetworkController: onReceive: intent=Intent { act=com.samsung.intent.action.WIFI_CAPTIVE_NOT_LOGIN flg=0x10 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-25 13:51:26.155  3949  4133 D NetworkController.WifiSignalController: updateWifiState : mCurrentState.wifiCaptiveNotLogin = false
05-25 13:51:26.155  3549  4211 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:51:26.155  3549  3601 D TelephonyManager: getDataEnabled: retVal=true
,05-25 13:51:26.155  7288  7299 I SA      : [OCP] Delete DB (TNC data)
,05-25 13:51:26.155 10411 10411 I [SC]CommonUtil: Samsung Account Not Logged in
,05-25 13:51:26.165 10438 10438 W ResourcesManager: getTopLevelResources: /system/priv-app/SOAgent/SOAgent.apk / 1.0 running in com.sec.android.soagent rsrc of package com.sec.android.soagent
,05-25 13:51:26.165  3549  4420 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-25 13:51:26.165 10438 10438 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
05-25 13:51:26.165  3549  3567 D ActivityManager:  getDeferredInfo final delay 300
,05-25 13:51:26.165  4260  4546 D TelephonyProvider: query: url=content://telephony/carriers/preferapn, projectionIn=[Ljava.lang.String;@edd451d, selection=nullselectionArgs=null, sort=name ASC
,05-25 13:51:26.165 10438 10438 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:51:26.175  4260  4546 D TelephonyProvider: query: match = 5
,05-25 13:51:26.175  4260  4546 D TelephonyProvider: getPreferredApnId(subId = 2147483643),return -1
05-25 13:51:26.175  4260  4546 D TelephonyProvider: query: selection modified to edited!=2 and edited!=3 and edited!=5 and edited!=6
,05-25 13:51:26.175 10438 10438 I InjectionManager: Inside getClassLibPath caller 
,05-25 13:51:26.185 10438 10438 W System  : ClassLoader referenced unknown path: /system/priv-app/SOAgent/lib/arm64
,05-25 13:51:26.185  3549  3601 E GpsLocationProvider: No APN found to select.
,05-25 13:51:26.185  3549  3601 D libgps  : agps_ril_update_network_state: Waiting for IPC connection...
,05-25 13:51:26.195 10438 10438 D InjectionManager: InjectionManager
05-25 13:51:26.195 10438 10438 D InjectionManager: fillFeatureStoreMap com.sec.android.soagent
,05-25 13:51:26.195 10438 10438 I InjectionManager: Constructor com.sec.android.soagent, Feature store :{}
05-25 13:51:26.195 10438 10438 I InjectionManager: featureStore :{}
,05-25 13:51:26.225  3549  3567 I ActivityManager: Killing 8985:com.samsung.android.sm.devicesecurity/5012 (adj 15): DHA:empty #33
05-25 13:51:26.225  3549  3567 I ActivityManager: Killing 9200:com.samsung.android.provider.shootingmodeprovider/u0a57 (adj 15): DHA:empty #33
,05-25 13:51:26.235  3549  3567 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{86c1de7 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{14616a1 9936:com.thaliproject.thalitest/u0a74}
,05-25 13:51:26.235  3549  4435 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:26.235  3549  4435 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
05-25 13:51:26.235  3549  4435 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:26.235  3549  4435 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:26.235  3549  4435 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:26.235  3549  4435 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:26.235  3549  4435 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:26.235  3549  4435 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:26.235  3549  4435 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:26.235  3549  4435 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:51:26.235  3549  4435 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:26.235  3549  4435 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true],
05-25 13:51:26.235  3549  4435 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:51:26.235  3549  4435 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:51:26.235  3549  4435 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:51:26.255  3549  4367 D ActivityManager: cleanUpApplicationRecord -- 9200
,05-25 13:51:26.255  3549  4367 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.provider.shootingmodeprovider, Auto Run ON
,05-25 13:51:26.265  3549  4286 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{86c1de7 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a61135 3549:system/1000}
,05-25 13:51:26.275  3549  3986 D ActivityManager: cleanUpApplicationRecord -- 8985
,05-25 13:51:26.275  3549  3986 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sm.devicesecurity, Auto Run ON
,05-25 13:51:26.295  3549  3549 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{86c1de7 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c4f3aaa 4628:com.google.android.gms/u0a19}
,05-25 13:51:26.305  4628  4628 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,05-25 13:51:26.305  4628  5663 I iu.UploadsManager: num queued entries: 0
,05-25 13:51:26.305  4628  5663 I iu.UploadsManager: num updated entries: 0
,05-25 13:51:26.305  4628  5663 I iu.SyncManager: NEXT; no task
,05-25 13:51:26.315  3549  4420 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{86c1de7 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c4f3aaa 4628:com.google.android.gms/u0a19}
,05-25 13:51:26.325  3549  4420 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{86c1de7 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f3ae3d9 4287:com.google.android.gms.persistent/u0a19}
,05-25 13:51:26.345  3549  4285 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{86c1de7 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3117ce6 10284:com.policydm/1000}
,05-25 13:51:26.345  3157  3609 D EnterpriseController: netId is 0
05-25 13:51:26.345  3157  3609 D Netd    : getNetworkForDns: using netid 503 for uid 10019
,05-25 13:51:26.355 10181 10181 D Babel   : RefCountedService(com.google.android.apps.hangouts.requestwriter.RequestWriter) onDestroy (count=0, startId=1 stopped=true)
,05-25 13:51:26.365 10284 10284 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(574/IlIIIllllIIlIIIIIlII)] Initiated Type: 0
,05-25 13:51:26.375 10284 10284 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,05-25 13:51:26.375 10284 10284 I DBG_POLICYDM: [com.policydm.XDMService(585/llIlIllllllllllllllI)] get NotibarState : 0
,05-25 13:51:26.375  3549  4435 I ActivityManager: Killing 9215:com.samsung.android.themecenter/1000 (adj 15): DHA:empty #33
,05-25 13:51:26.405  3549  4433 D ActivityManager: cleanUpApplicationRecord -- 9215
,05-25 13:51:26.405  3549  4433 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.themecenter, Auto Run ON
,05-25 13:51:26.535  3549  3603 D ActivityManager:  getDeferredInfo final delay 860
,05-25 13:51:26.795  3549  3869 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,05-25 13:51:27.205  3549  3601 D libgps  : agps_ril_update_network_state: Waiting for IPC connection - timeout
05-25 13:51:27.205  3549  3601 E libgps  : LIBGPS: Cannot communicate (write) with a GPSD
05-25 13:51:27.205  3549  3601 E libgps  : IPC Communication Error, ../../../../tmp/14982990_270314/allPartners/os/android/gps_interface/gpsi_client/GpsiClient.cpp:1710 agps_ril_update_network_state
05-25 13:51:27.205  3549  3601 D libgps  : agps_ril_update_network_availability: Waiting for IPC connection...
,05-25 13:51:27.305  3549  3603 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ecf4d94 u0 com.google.android.gcm.CONNECTED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8e6b578 10181:com.google.android.talk/u0a112}
,05-25 13:51:27.315  3549  3986 V AlarmManager:  remove PendingIntent] PendingIntent{c5f503d: PendingIntentRecord{e1c90a com.google.android.gms broadcastIntent}}
,05-25 13:51:27.395  3549  3603 D ActivityManager:  getDeferredInfo final delay 560
,05-25 13:51:27.505  3549  3869 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -38], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -35]
,05-25 13:51:27.505  3549  3869 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
05-25 13:51:27.505  3549  3869 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -35]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,05-25 13:51:27.515  3949  4133 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-25 13:51:27.535  3549  3869 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
,05-25 13:51:27.545  3549  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-25 13:51:27.555  3549  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,05-25 13:51:27.565  3549  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-25 13:51:27.575  3549  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-25 13:51:27.585  3549  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-25 13:51:27.605  3549  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
05-25 13:51:27.605  3549  3869 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 503]
05-25 13:51:27.605  3549  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:51:27.605  3549  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:51:27.605  3549  3869 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:51:27.605  3549  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
05-25 13:51:27.605  3549  3869 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=5, legacyType=-1, [] ]
,05-25 13:51:27.605  3549  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:51:27.605  3549  3869 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:51:27.605  3549  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:51:27.605  3549  3869 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:51:27.615  3549  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:51:27.615  3549  3869 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:51:27.635  3949  4133 D ViewRootImpl: #3 mView = null
,05-25 13:51:27.645  3549  3981 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3549) eventTime = 308042
,05-25 13:51:27.645  3549  3981 D PowerManagerService: [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3549 (0x0)
05-25 13:51:27.645  3549  3981 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3549, ws=WorkSource{10062}) (elapsedTime=1935)
,05-25 13:51:27.995  3549  3603 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:51:28.015 10456 10456 E Zygote  : v2
05-25 13:51:28.015 10456 10456 I libpersona: KNOX_SDCARD checking this for 5011
05-25 13:51:28.015 10456 10456 I libpersona: KNOX_SDCARD not a persona
,05-25 13:51:28.015 10456 10456 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
05-25 13:51:28.015  3549  3603 I ActivityManager: Start proc 10456:com.samsung.android.coreapps/5011 for broadcast-5 com.samsung.android.coreapps/.easysignup.receiver.NetworkStateListener
,05-25 13:51:28.015 10456 10456 E Zygote  : accessInfo : 0
05-25 13:51:28.015 10456 10456 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.coreapps 
,05-25 13:51:28.045 10456 10456 D TimaKeyStoreProvider: TimaSignature is unavailable
05-25 13:51:28.055 10456 10456 D ActivityThread: Added TimaKeyStore provider
,05-25 13:51:28.065  3549  3838 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{c3d5f08 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{31daf00 10456:com.samsung.android.coreapps/5011}
,05-25 13:51:28.075 10456 10456 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in com.samsung.android.coreapps rsrc of package com.samsung.android.coreapps
,05-25 13:51:28.085  3549  4367 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-25 13:51:28.085 10456 10456 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-25 13:51:28.085 10456 10456 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:51:28.095 10456 10456 I InjectionManager: Inside getClassLibPath caller 
,05-25 13:51:28.105 10456 10456 W System  : ClassLoader referenced unknown path: /system/app/CoreApps/lib/arm64
,05-25 13:51:28.125 10456 10456 D CoreApps: SEC_LOG - true
,05-25 13:51:28.175 10456 10456 E GooglePlayServicesUtil: The Google Play services resources were not found. Check your project configuration to ensure that the resources are included.
,05-25 13:51:28.175  3011  3024 I SurfaceFlinger: id=20 Removed Uoast (8/10)
05-25 13:51:28.175  3011  3022 I SurfaceFlinger: id=20 Removed Uoast (-2/10)
,05-25 13:51:28.195  3011  3011 D libEGL  : eglTerminate EGLDisplay = 0x7fcec79f88
,05-25 13:51:28.205  3549  3601 D libgps  : agps_ril_update_network_availability: Waiting for IPC connection - timeout
05-25 13:51:28.205  3549  3601 E libgps  : LIBGPS: Cannot communicate (write) with a GPSD
05-25 13:51:28.205  3549  3601 E libgps  : IPC Communication Error, ../../../../tmp/14982990_270314/allPartners/os/android/gps_interface/gpsi_client/GpsiClient.cpp:1729 agps_ril_update_network_availability
,05-25 13:51:28.325 10456 10456 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Epic_Common/SecMms_Epic_Common.apk / 1.0 running in com.samsung.android.coreapps rsrc of package com.android.mms
,05-25 13:51:28.325 10456 10456 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:51:28.335 10456 10456 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.samsung.android.coreapps rsrc of package com.google.android.talk
,05-25 13:51:28.335 10456 10456 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:51:28.345 10456 10456 D InjectionManager: InjectionManager
,05-25 13:51:28.345 10456 10456 D InjectionManager: fillFeatureStoreMap com.samsung.android.coreapps
05-25 13:51:28.355 10456 10456 I InjectionManager: Constructor com.samsung.android.coreapps, Feature store :{}
05-25 13:51:28.355 10456 10456 I InjectionManager: featureStore :{}
,05-25 13:51:28.355  3549  3981 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:51:28.365  3549  3981 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{c3d5f08 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{31daf00 10456:com.samsung.android.coreapps/5011}
,05-25 13:51:28.385  3549  3568 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:51:28.395  3549  3568 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{c3d5f08 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{31daf00 10456:com.samsung.android.coreapps/5011}
,05-25 13:51:28.405  3549  3568 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:51:28.405  3549  3568 I ActivityManager: Killing 9227:com.samsung.ipservice/5004 (adj 15): DHA:empty #33
,05-25 13:51:28.415  3549  3568 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{c3d5f08 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ba3ee7d 4967:com.microsoft.skydrive/u0a124}
,05-25 13:51:28.425  3549  4066 D ActivityManager: cleanUpApplicationRecord -- 9227
,05-25 13:51:28.425  3549  4066 D ActivityManager: isAutoRunBlockedApp:: com.samsung.ipservice, Auto Run ON
,05-25 13:51:28.445  3549  3981 W IntentResolver: resolveIntent failed: found match, but none with CATEGORY_DEFAULT
,05-25 13:51:28.445  3549  3838 D ActivityManager:  getDeferredInfo final delay 300
,05-25 13:51:28.745  3549  3603 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:51:28.765 10484 10484 E Zygote  : v2
05-25 13:51:28.765 10484 10484 I libpersona: KNOX_SDCARD checking this for 10129
05-25 13:51:28.765 10484 10484 I libpersona: KNOX_SDCARD not a persona
,05-25 13:51:28.775 10484 10484 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
05-25 13:51:28.775  3549  3603 I ActivityManager: Start proc 10484:com.google.android.apps.photos/u0a129 for broadcast-5 com.google.android.apps.photos/.actionqueue.SystemReceiver
,05-25 13:51:28.775  3549  3857 D NetworkPolicy: isUidForegroundLocked: 10129, mScreenOn: true, uidstate: -1, mProxSensorScreenOff: false
,05-25 13:51:28.775 10484 10484 E Zygote  : accessInfo : 0
05-25 13:51:28.775 10484 10484 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.photos 
,05-25 13:51:28.805 10484 10484 D TimaKeyStoreProvider: TimaSignature is unavailable
05-25 13:51:28.805 10484 10484 D ActivityThread: Added TimaKeyStore provider
,05-25 13:51:28.825  3549  4420 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{c3d5f08 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a84e2df 10484:com.google.android.apps.photos/u0a129}
,05-25 13:51:28.835  3549  3857 D NetworkPolicy: isUidForegroundLocked: 10129, mScreenOn: true, uidstate: 11, mProxSensorScreenOff: false
,05-25 13:51:28.845 10484 10484 W ResourcesManager: getTopLevelResources: /system/app/Photos/Photos.apk / 1.0 running in com.google.android.apps.photos rsrc of package com.google.android.apps.photos
,05-25 13:51:28.845  3549  3567 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-25 13:51:28.845 10484 10484 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-25 13:51:28.855 10484 10484 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:51:28.855 10484 10484 I InjectionManager: Inside getClassLibPath caller 
,05-25 13:51:28.875 10484 10484 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm64
,05-25 13:51:29.105 10484 10484 W ResourcesManager: getTopLevelResources: /system/app/Photos/Photos.apk / 1.0 running in com.google.android.apps.photos rsrc of package com.google.android.apps.photos
,05-25 13:51:29.185 10345 10345 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,05-25 13:51:29.195 10484 10484 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,05-25 13:51:29.315 10484 10484 D InjectionManager: InjectionManager
05-25 13:51:29.315 10484 10484 D InjectionManager: fillFeatureStoreMap com.google.android.apps.photos
,05-25 13:51:29.315 10484 10484 I InjectionManager: Constructor com.google.android.apps.photos, Feature store :{}
05-25 13:51:29.315 10484 10484 I InjectionManager: featureStore :{}
,05-25 13:51:29.325  3549  3603 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5ff1e56 u0 com.google.android.apps.photos.actionqueue.INTERNAL_ACTION qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a84e2df 10484:com.google.android.apps.photos/u0a129}
,05-25 13:51:29.345  3549  6115 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,05-25 13:51:29.375  3549  3568 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:51:29.385  3549  3568 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{c3d5f08 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a84e2df 10484:com.google.android.apps.photos/u0a129}
,05-25 13:51:29.395  3549  3568 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2b43c4 u0 com.google.android.apps.photos.jobqueue.EXECUTE_JOBS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a84e2df 10484:com.google.android.apps.photos/u0a129}
,05-25 13:51:29.415  3549  3568 D ActivityManager:  getDeferredInfo final delay 300
,05-25 13:51:29.435  3549  3568 I ActivityManager: Killing 9241:com.samsung.android.scloud/5009 (adj 15): DHA:empty #33
,05-25 13:51:29.465  3549  4435 D ActivityManager: cleanUpApplicationRecord -- 9241
,05-25 13:51:29.465  3549  4435 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.scloud, Auto Run ON
,05-25 13:51:29.515  9936  9999 I io.jxcore.node.IncomingSocketThreadTest: testRun
,05-25 13:51:29.515  9936 10513 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
05-25 13:51:29.515  9936 10513 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,05-25 13:51:29.525  3157  3609 D EnterpriseController: netId is 0
05-25 13:51:29.525  3157  3609 D Netd    : getNetworkForDns: using netid 503 for uid 10074
,05-25 13:51:29.525  9936 10515 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
05-25 13:51:29.525  9936 10515 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
05-25 13:51:29.525  9936 10513 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
05-25 13:51:29.525  9936 10513 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
05-25 13:51:29.525  9936 10515 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-25 13:51:29.525  9936 10513 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-25 13:51:29.525  9936 10515 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-25 13:51:29.525  9936 10513 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,05-25 13:51:29.525  9936 10515 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
05-25 13:51:29.525  9936 10513 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,05-25 13:51:29.535  9936 10520 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 248, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:29.535  9936 10520 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:51:29.535  9936 10520 D io.jxcore.node.StreamCopyingThread:  id: 78
,05-25 13:51:29.535  9936 10520 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 248, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:29.535  9936 10520 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:51:29.535  9936 10520 D io.jxcore.node.StreamCopyingThread:  id: 78
05-25 13:51:29.535  9936 10520 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:29.535  9936 10520 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:51:29.535  9936 10520 D io.jxcore.node.StreamCopyingThread:  id: 78
05-25 13:51:29.535  9936 10520 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
05-25 13:51:29.535  9936 10520 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
05-25 13:51:29.535  9936 10520 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,05-25 13:51:29.535  9936 10520 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
05-25 13:51:29.535  9936 10520 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
05-25 13:51:29.535  9936 10520 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
05-25 13:51:29.535  9936 10520 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 248, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:29.535  9936 10520 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:51:29.535  9936 10520 D io.jxcore.node.StreamCopyingThread:  id: 78 .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
05-25 13:51:29.535  9936 10518 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 246, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:29.535  9936 10518 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:51:29.535  9936 10518 D io.jxcore.node.StreamCopyingThread:  id: 78
05-25 13:51:29.535  9936 10517 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 245, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:29.535  9936 10517 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:51:29.535  9936 10517 D io.jxcore.node.StreamCopyingThread:  id: 77
,05-25 13:51:29.535  9936 10518 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 246, thread name: OutgoingSocketThread/Sender): recvfrom failed: EBADF (Bad file descriptor)
05-25 13:51:29.535  9936 10517 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 245, thread name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:29.535  9936 10517 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:51:29.535  9936 10517 D io.jxcore.node.StreamCopyingThread:  id: 77
05-25 13:51:29.535  9936 10518 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 246, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:29.535  9936 10518 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:51:29.535  9936 10518 D io.jxcore.node.StreamCopyingThread:  id: 78 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
05-25 13:51:29.535  9936 10517 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:29.535  9936 10517 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:51:29.535  9936 10517 D io.jxcore.node.StreamCopyingThread:  id: 77
05-25 13:51:29.535  9936 10517 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
05-25 13:51:29.535  9936 10518 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: recvfrom failed: EBADF (Bad file descriptor)
05-25 13:51:29.535  9936 10517 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,05-25 13:51:29.535  9936 10518 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
05-25 13:51:29.535  9936 10517 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
05-25 13:51:29.535  9936 10517 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
05-25 13:51:29.535  9936 10517 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
05-25 13:51:29.535  9936 10518 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 246, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:29.535  9936 10518 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:51:29.535  9936 10518 D io.jxcore.node.StreamCopyingThread:  id: 78 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
05-25 13:51:29.535  9936 10517 I io.jxcore.node.IncomingSocketThread: The sending thread is done
,05-25 13:51:29.535  9936 10517 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 245, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:29.535  9936 10517 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:51:29.535  9936 10517 D io.jxcore.node.StreamCopyingThread:  id: 77 .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
05-25 13:51:29.535  9936 10519 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 247, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:29.535  9936 10519 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:51:29.535  9936 10519 D io.jxcore.node.StreamCopyingThread:  id: 77
05-25 13:51:29.535  9936 10519 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 247, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:29.535  9936 10519 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:51:29.535  9936 10519 D io.jxcore.node.StreamCopyingThread:  id: 77
05-25 13:51:29.535  9936 10519 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:29.535  9936 10519 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:51:29.535  9936 10519 D io.jxcore.node.StreamCopyingThread:  id: 77
05-25 13:51:29.535  9936 10519 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
05-25 13:51:29.535  9936 10519 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,05-25 13:51:29.535  9936 10519 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
05-25 13:51:29.535  9936 10519 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
05-25 13:51:29.535  9936 10519 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
05-25 13:51:29.535  9936 10519 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
05-25 13:51:29.535  9936 10519 I io.jxcore.node.IncomingSocketThread: Both threads are done, notifying the listener...
05-25 13:51:29.535  9936 10519 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 247, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:29.535  9936 10519 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:51:29.535  9936 10519 D io.jxcore.node.StreamCopyingThread:  id: 77 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,05-25 13:51:29.565  3157  3606 D Netd    : Iface wlan0 link up
,05-25 13:51:29.565  3549  3614 D Tethering: interfaceLinkStateChanged wlan0, true
,05-25 13:51:29.565  3549  3614 D Tethering: interfaceStatusChanged wlan0, true
05-25 13:51:29.565 10246 10246 I wpa_supplicant: nl80211: Received scan results (22 BSSes)
,05-25 13:51:29.565  4905  9487 D PdnController: Interface Changed wlan0 link up
,05-25 13:51:29.575  3549  3858 D WifiP2pService: InactiveState{ what=147461 }
05-25 13:51:29.575  3549  3858 D WifiP2pService: P2pEnabledState{ what=147461 }
05-25 13:51:29.575  3549  3858 D WifiP2pService: DefaultState{ what=147461 }
,05-25 13:51:29.605  3549  3549 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.SCAN_RESULTS
,05-25 13:51:29.615  3549  3603 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d4cdca9 u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c130950 3949:com.android.systemui/u0a62}
,05-25 13:51:29.715  3549  3603 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:51:29.735  3549  3603 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{c3d5f08 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ef3b2f5 4724:com.sec.android.daemonapp/u0a159}
,05-25 13:51:29.745  4724  4724 D [Weather Widget]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CFAAE09BFCA326403459399C53A4EE79DAC193CEB26509F8FF7498BE5251A746097407E81C28CD811D388C49D613C81F395B356AA489D29CB4C3BE983CCC84BA76AF507AA66A943348DF162DECA2A5A7DD]}
,05-25 13:51:29.745  4724  4724 D [Weather Widget]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CFE2E89F45594D9820F24D88E9AF210A78F9CD3967C07B6DE6AAB9923C4C53919020112019F4465EB3AA6FD266958B212E]}
,05-25 13:51:29.745  3549  4066 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:51:29.765  3549  4066 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{c3d5f08 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f3e5ff6 7884:com.sec.android.app.samsungapps/u0a14}
,05-25 13:51:29.775  7884  7884 D [SAUI]  : NetworkStateReceiver::connected::recovered?false
,05-25 13:51:29.795  7884  7884 D [SAUI]  : Global::recovered::false
,05-25 13:51:29.795  3549  4420 D ActivityManager:  getDeferredInfo final delay 300
05-25 13:51:29.795  7884  7884 D [SAUI]  : AutoUpdateService::onStartCommand
05-25 13:51:29.795  7884  7884 D [SAUI]  : AutoUpdateService::runAutoUpdateManager
05-25 13:51:29.795  7884  7884 D [SAUI]  : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,05-25 13:51:29.795  7884  7884 D [SAUI]  : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
05-25 13:51:29.805  7884  7884 D [SA_INIT]: AutoUpdateManager ServiceInitializer startInitialize()
,05-25 13:51:29.805  7884  8948 D [SA_INIT]: createTaskForServiceInitialize()
,05-25 13:51:29.805  7884  8947 D [SA_INIT]: NetworkStateCheckUnit workImpl()
,05-25 13:51:29.805  7884  8947 D [SA_INIT]: NetworkStateCheckUnit result : 1
,05-25 13:51:29.805  7884  7884 V JOULE   : JOULELOG [main]  com.sec.android.app.joule.f Task [35, 83112724_0] [END] FINISHED
05-25 13:51:29.805  7884  7884 D [SA_INIT]: ServiceInitializer onInitializeResult() reuslt : true
05-25 13:51:29.805  7884  7884 D [SAUI]  : AutoUpdateManager:INITCHECK:onInitializeSuccess
,05-25 13:51:29.805  7884  7884 D [SAUI]  : AutoUpdateTriggerManager:IDLE:notifyNextTime
,05-25 13:51:29.815  7884  7884 D [SAUI]  : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,05-25 13:51:29.865  3549  3981 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-25 13:51:29.865  3549  3981 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:51:29.865  3549  3981 D BatteryService: online:4, current avg:-16, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:123
05-25 13:51:29.865  3549  3549 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:51:29.865  3549  3549 I MotionRecognitionService: Plugged
05-25 13:51:29.865  3549  3549 D MotionRecognitionService:   cableConnection= 1
05-25 13:51:29.865  3549  3549 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:51:29.865  3549  3549 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:51:29.875  3549  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:51:29.875  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
05-25 13:51:29.875  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
,05-25 13:51:29.875  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:51:29.885  4905  4905 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:51:29.895  4905  4905 D BatteryMonitor: new battery level: 100
,05-25 13:51:29.905 10053 10053 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-25 13:51:29.905 10053 10095 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-25 13:51:29.905  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:29.905  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:30.095  3549  3603 D ActivityManager:  getDeferredInfo final delay 300
,05-25 13:51:30.445  3549  3603 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:51:30.455  3549  3603 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{377429e u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ec43a0e 10220:com.sec.android.diagmonagent/1000}
,05-25 13:51:30.455 10220 10220 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,05-25 13:51:30.455 10220 10220 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
05-25 13:51:30.455 10220 10220 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,05-25 13:51:30.455  3549  4285 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:51:30.465  3549  4285 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{377429e u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{620523c 10233:com.sec.knox.switcher/1000}
,05-25 13:51:30.465 10233 10233 I usagelog: received in receiver
05-25 13:51:30.465 10233 10233 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
05-25 13:51:30.465 10233 10233 I KnoxUsageLogPro: premStatus:2
,05-25 13:51:30.475 10233 10233 I KnoxUsageLogPro: isEulaShown : false
05-25 13:51:30.475 10233 10233 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,05-25 13:51:30.475  3549  4170 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:51:30.485  3549  4170 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{377429e u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b397bc5 10247:com.samsung.android.sm.policy/u0a135}
,05-25 13:51:30.485  3549  4931 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:51:30.505 10523 10523 E Zygote  : v2
,05-25 13:51:30.505 10523 10523 I libpersona: KNOX_SDCARD checking this for 1000
05-25 13:51:30.505 10523 10523 I libpersona: KNOX_SDCARD not a persona
05-25 13:51:30.505 10523 10523 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-25 13:51:30.515 10523 10523 E Zygote  : accessInfo : 0
,05-25 13:51:30.525  3549  4931 I ActivityManager: Start proc 10523:com.samsung.android.securitylogagent/1000 for broadcast-5 com.samsung.android.securitylogagent/.receivers.NetworkReceiver
,05-25 13:51:30.555 10523 10523 D TimaKeyStoreProvider: TimaSignature is unavailable
05-25 13:51:30.555 10523 10523 D ActivityThread: Added TimaKeyStore provider
,05-25 13:51:30.565  3549  3981 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{43ac26c u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a1241cf 10523:com.samsung.android.securitylogagent/1000}
,05-25 13:51:30.575 10523 10523 W ResourcesManager: getTopLevelResources: /system/app/SecurityLogAgent/SecurityLogAgent.apk / 1.0 running in com.samsung.android.securitylogagent rsrc of package com.samsung.android.securitylogagent
,05-25 13:51:30.575  3549  4367 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-25 13:51:30.575 10523 10523 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-25 13:51:30.585 10523 10523 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:51:30.585 10523 10523 I InjectionManager: Inside getClassLibPath caller 
,05-25 13:51:30.595 10523 10523 W System  : ClassLoader referenced unknown path: /system/app/SecurityLogAgent/lib/arm64
,05-25 13:51:30.595 10523 10523 D InjectionManager: InjectionManager
,05-25 13:51:30.595 10523 10523 D InjectionManager: fillFeatureStoreMap com.samsung.android.securitylogagent
05-25 13:51:30.595 10523 10523 I InjectionManager: Constructor com.samsung.android.securitylogagent, Feature store :{}
05-25 13:51:30.595 10523 10523 I InjectionManager: featureStore :{}
,05-25 13:51:30.605 10523 10523 D SecurityLogAgent: NetworkReceiver : Network Change Receiver Is Called
,05-25 13:51:30.605 10523 10523 D SecurityLogAgent: NetworkReceiver : Wifi_state is 3
,05-25 13:51:30.625 10523 10523 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,05-25 13:51:30.625 10523 10523 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
05-25 13:51:30.625 10523 10523 D SecurityLogAgent: StateMachine : Current State = 1
,05-25 13:51:30.625  3549  4433 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:51:30.645  3549  4433 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{86c1de7 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3117ce6 10284:com.policydm/1000}
,05-25 13:51:30.645 10284 10284 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(51/onReceive)] RegistrationReceiver onReceive! action = android.net.conn.CONNECTIVITY_CHANGE
,05-25 13:51:30.695 10284 10284 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(87/llllIIIllIlIIIIllllI)] device register flag at setting DB : true
,05-25 13:51:30.715 10284 10284 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(96/onReceive)] Already device registered...
,05-25 13:51:30.715  3549  3838 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-25 13:51:30.715  3549  3838 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:51:30.715  3549  3838 D BatteryService: online:4, current avg:-4, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:92
05-25 13:51:30.725  3549  3549 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:51:30.725 10284 10284 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(87/llllIIIllIlIIIIllllI)] device register flag at setting DB : true
,05-25 13:51:30.725  3549  3549 I MotionRecognitionService: Plugged
05-25 13:51:30.725  3549  3549 D MotionRecognitionService:   cableConnection= 1
05-25 13:51:30.725  3549  3549 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:51:30.725  3549  3549 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:51:30.725  3549  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:51:30.725  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
05-25 13:51:30.735  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
,05-25 13:51:30.735  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:51:30.735 10284 10284 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(342/lllIlIlIIIllIIlIllIl)] OMC not Supported model
,05-25 13:51:30.745 10284 10284 I DBG_POLICYDM: [IIIIlllIIIlIlllllIll(111/llIlIIIIlIIIIIlIlIII)] Polling time is vaild
05-25 13:51:30.745 10284 10284 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(281/llIIIIlllllIIllIIllI)] Heartbeat settings is activated.
05-25 13:51:30.745 10284 10284 I DBG_POLICYDM: [IIlllIIllIllIllIIlll(52/llllIIIllIlIIIIllllI)] Next heartbeat time:2017/06/05/19:54:27
,05-25 13:51:30.755 10284 10284 I DBG_POLICYDM: [IIlllIIllIllIllIIlll(55/llllIIIllIlIIIIllllI)] heartbeat time is vaild
,05-25 13:51:30.755  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
05-25 13:51:30.755  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:30.765  4905  4905 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:51:30.765  4905  4905 D BatteryMonitor: new battery level: 100
,05-25 13:51:30.765 10053 10053 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-25 13:51:30.765 10053 10095 D HeadsetStateMachine: Disconnected process message: 10, size: 0
05-25 13:51:30.765  3549  3981 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:51:30.775  3549  3981 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{86c1de7 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1b75d8f 7288:com.osp.app.signin/u0a41}
,05-25 13:51:30.785  7288  7288 I SA      : [OR] onReceive log=[SA = 2.2.02-12 V = 23 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = pl_PL CSC = XEO MCC = 0 MNC 0 T = user DEVICE = herolte P = heroltexx I = MMB29K M = SM-G930F OKLEFT false DIS MMB29K.G930FXXU1BPJG PSS = 5.059173621445858  ]
,05-25 13:51:30.785  7288  7288 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
05-25 13:51:30.785  7288  7288 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,05-25 13:51:30.795  7288  7288 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
05-25 13:51:30.795  7288  7288 I SA      : [OR] == isSIMCardReady false ==
,05-25 13:51:30.795  7288  7288 I SA      : [SCU] == networkStateCheck == true
05-25 13:51:30.795  7288  7288 I SA      : [DM] getCountryCodeFromCSC : PL
05-25 13:51:30.795  7288  7288 I SA      : isChinaCountryCode : false
05-25 13:51:30.795  7288  7288 I SA      : [SCU] is ChinestModel Data Restricted   : false
05-25 13:51:30.795  7288  7288 I SA      : [OR] == networkStateCheck true ==
05-25 13:51:30.795  7288  7288 I SA      : [OR] GetMyCountryZoneTask
,05-25 13:51:30.795  7288  7288 I SA      : [OR] onReceive END
,05-25 13:51:30.795  3549  4285 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:51:30.795  7288 10537 I SA      : [SRS] prepareGetMyCountryZone
,05-25 13:51:30.795  3549  4285 I ActivityManager: Killing 9261:com.samsung.android.bbc.bbcagent/1000 (adj 15): DHA:empty #33
,05-25 13:51:30.805  3549  4285 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{86c1de7 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b9114b5 6737:com.wssyncmldm/1000}
,05-25 13:51:30.815  7288 10537 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
05-25 13:51:30.815  7288 10537 I SA      : [SSP] query invoked
,05-25 13:51:30.815  7288 10537 I SA      : [TPMU] GetMccFromDB : null
05-25 13:51:30.815  7288 10537 I SA      : [SCU] getMccFromPreferece mcc = 260
05-25 13:51:30.815  7288 10537 I SA      : [LBE] isSupportCheckDomainRegion : true
05-25 13:51:30.815  7288 10537 I SA      : [TPM] isNoProxy(default) : true
05-25 13:51:30.815  7288 10537 I SA_HTTPURLCONNECTION: [RC New] Execute method=[GET] start
,05-25 13:51:30.825  3549  3567 D ActivityManager:  getDeferredInfo final delay 300
05-25 13:51:30.825  3549  4367 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-25 13:51:30.825  3549  4367 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:51:30.825  3549  4367 D BatteryService: online:4, current avg:-3, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:92
05-25 13:51:30.825  3549  3549 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:51:30.825  6737 10538 I FOTA_AGENT: [com.samsung.android.app.fotaclient.llIlIIIIlIIIIIlIlIII(87/llIIIIlllllIIllIIllI)] Nothing to do action: android.net.conn.CONNECTIVITY_CHANGE
,05-25 13:51:30.835  3549  4286 D ActivityManager: cleanUpApplicationRecord -- 9261
,05-25 13:51:30.835  3549  4286 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.bbc.bbcagent, Auto Run ON
,05-25 13:51:30.845  3549  3549 I MotionRecognitionService: Plugged
,05-25 13:51:30.845  3549  3549 D MotionRecognitionService:   cableConnection= 1
,05-25 13:51:30.845  3549  3549 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:51:30.845  3549  3549 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:51:30.845  7288 10537 I SA_HTTPURLCONNECTION: [RC New] Security=[true]
05-25 13:51:30.845  7288 10537 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
05-25 13:51:30.845  7288 10537 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,05-25 13:51:30.845  3157  3609 D EnterpriseController: netId is 0
,05-25 13:51:30.845  3157  3609 D Netd    : getNetworkForDns: using netid 503 for uid 10041
,05-25 13:51:30.855  3549  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:51:30.855  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,05-25 13:51:30.855  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
05-25 13:51:30.855  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:51:30.865  4905  4905 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:51:30.875  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
05-25 13:51:30.875  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:30.875  4905  4905 D BatteryMonitor: new battery level: 100
05-25 13:51:30.875 10053 10053 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-25 13:51:30.875 10053 10095 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-25 13:51:30.905  3549  3805 D TimaService: TIMA: TimaService scheduler is intialized. 
05-25 13:51:30.905  3549  3805 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,05-25 13:51:30.905  3549  3804 D TimaService: TimaServiceHandler.handleMessage what =1
,05-25 13:51:30.915  3549  3805 I TLC_TIMA_PKM_initialize: initializing...
05-25 13:51:30.915  3549  3805 I TLC_TIMA_PKM_initialize: root = 0, root_strlen = 1
05-25 13:51:30.915  3549  3805 I TLC_TIMA_PKM_initialize: process = ffffffff00000000000000000000000a, process_strlen = 32
05-25 13:51:30.915  3549  3805 I TZ: mc_tlc_communication: input max_sendmsg_size = 262196
05-25 13:51:30.915  3549  3805 I TZ: mc_tlc_communication: input max_recvmsg_size = 262196
05-25 13:51:30.915  3549  3805 I TZ: mc_tlc_communication: root = 0, root_len = 1
05-25 13:51:30.915  3549  3805 I TZ: mc_tlc_communication: process = ffffffff00000000000000000000000a, process_strlen = 32
05-25 13:51:30.915  3549  3805 I TZ: mc_tlc_communication: aligned max_sendmsg_size = 262208
05-25 13:51:30.915  3549  3805 I TZ: mc_tlc_communication: aligned max_recvmsg_size = 262208
05-25 13:51:30.915  3549  3805 I TZ: mc_tlc_communication: device_id = 0x0
05-25 13:51:30.915  3549  3805 I TZ: mc_tlc_communication: tlc_open() was called
05-25 13:51:30.915  3549  3805 I TZ: mc_tlc_communication: Opening MobiCore device
05-25 13:51:30.915  3549  3805 I TeeDriverClient: driver client open [hardware/samsung_slsi/exynos8890/mobicore/ClientLib/src/driver_client.cpp:103]
05-25 13:51:30.915  3549  3805 I TZ: mc_tlc_communication: Allocating message buffer for TCI
,05-25 13:51:30.915  3549  3805 I TZ: mc_tlc_communication: Opening the session
,05-25 13:51:30.915  3549  4066 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,05-25 13:51:30.915  3549  4066 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:51:30.915  3549  4066 D BatteryService: online:4, current avg:-3, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-2
05-25 13:51:30.915  3549  3549 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:51:30.915  3549  3549 I MotionRecognitionService: Plugged
,05-25 13:51:30.915  3549  3549 D MotionRecognitionService:   cableConnection= 1
05-25 13:51:30.915  3549  3549 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:51:30.915  3549  3549 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:51:30.925  3549  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:51:30.925  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
05-25 13:51:30.925  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
05-25 13:51:30.925  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:51:30.935  4905  4905 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:51:30.935  3549  3805 I TZ: mc_tlc_communication: tlc_open() succeeded
,05-25 13:51:30.935  3549  3805 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info1
05-25 13:51:30.935  4905  4905 D BatteryMonitor: new battery level: 100
,05-25 13:51:30.945  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:30.945  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:30.945 10053 10053 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,05-25 13:51:30.945 10053 10095 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-25 13:51:30.945  3549  3805 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info2
,05-25 13:51:30.965  3549  3805 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info3
,05-25 13:51:30.975  3549  3805 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info4
,05-25 13:51:30.975  3549  3805 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,05-25 13:51:31.125  3549  3603 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:51:31.135  3549  3603 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{86c1de7 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6766968 6850:com.samsung.fresco.logging/5015}
,05-25 13:51:31.135  3549  3568 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,05-25 13:51:31.135  3549  4432 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:51:31.135  3549  4433 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:51:31.155  3549  4433 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{86c1de7 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{90a8bbc 7359:com.sec.spp.push/u0a39}
,05-25 13:51:31.155  7359  7359 E SPPClientService: [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,05-25 13:51:31.155  7359  7359 E SPPClientService: [SystemStateMoniter] Current Time : 311551
05-25 13:51:31.155  7359  7359 E SPPClientService: [SystemStateMoniter] No Connect : false
,05-25 13:51:31.155  3549  4433 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:51:31.165  3549  4433 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{86c1de7 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1381225 4984:android.process.media/u0a48}
,05-25 13:51:31.175  4984  4984 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,05-25 13:51:31.185  3549  4430 D ActivityManager:  getDeferredInfo final delay 300
,05-25 13:51:31.205  3549  3981 D SecContentProvider2: query(), uri = 15 selection = getAppBlockDownloadState
,05-25 13:51:31.525  7288 10537 I SA_HTTPURLCONNECTION: [RC New] [v2liruge] api execute + 679
,05-25 13:51:31.535  7288 10537 I SA      : [ODM] saveOpenData( GEO_IP, PL )
,05-25 13:51:31.535  7288 10537 I SA      : [OCP] update openData : PL
,05-25 13:51:31.555  3549  3603 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:51:31.555  7288 10537 I SA      : [TPMU] getNetworkMcc : 
,05-25 13:51:31.555  7288 10537 I SA      : [SCU] saveMccToPreferece Start
05-25 13:51:31.555  7288 10537 I SA      : [SCU] RegionMCC : 260
05-25 13:51:31.565  7288 10537 I SA      : [SSP] query invoked
,05-25 13:51:31.565  3549  3603 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{86c1de7 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bf560a0 10367:com.samsung.android.SettingsReceiver/1000}
,05-25 13:51:31.565 10367 10367 E ActivityThread: Failed to find provider info for com.myscript.atk.rmc
,05-25 13:51:31.565  3549  4432 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:51:31.575  7288 10537 I SA      : [TPMU] GetMccFromDB : null
05-25 13:51:31.575  7288 10537 I SA      : [SCU] getMccFromPreferece mcc = 260
05-25 13:51:31.575  7288 10537 I SA      : [SCU] saveMccToPreferece End
05-25 13:51:31.575  7288 10537 I SA_HTTPURLCONNECTION: [RC New] executeRequest [v2liruge] end. 754
05-25 13:51:31.575  7288 10537 I SA_HTTPURLCONNECTION: [RC New] Execute end
,05-25 13:51:31.575  7288  7288 I SA      : [OR] GetMyCountryZoneTask mcc = 260
05-25 13:51:31.575  7288  7288 I SA      : [OR] GetMyCountryZoneTask Success
,05-25 13:51:31.585  3549  4432 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{86c1de7 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6ab1459 10389:com.samsung.android.themestore/u0a64}
,05-25 13:51:31.585 10389 10389 D AutoSelfUpgradeReceiver: onReceive() android.net.conn.CONNECTIVITY_CHANGE
,05-25 13:51:31.605 10389 10389 D AutoSelfUpgradeService: onCreate() 
05-25 13:51:31.605  3549  3986 D ActivityManager:  getDeferredInfo final delay 300
05-25 13:51:31.605 10389 10389 D AutoSelfUpgradeService: onStartCommand() action.selfupgrade.via.net
05-25 13:51:31.605 10389 10545 D AutoSelfUpgradeService: startInitAutoSelfUpdate()
,05-25 13:51:31.615 10389 10545 D AutoSelfUpgradeService: getAlarmIntent() 
,05-25 13:51:31.615 10389 10545 D AutoSelfUpgradeService: isAlarmActivated() false
05-25 13:51:31.615 10389 10545 I AutoSelfUpgradeService: Not a time to rum self upgrade yet.
,05-25 13:51:31.615  3549  4170 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-25 13:51:31.625  3549  4170 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4323, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:51:31.625  3549  4170 D BatteryService: online:4, current avg:-2, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:5
05-25 13:51:31.625  3549  3549 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:51:31.625 10389 10389 D AutoSelfUpgradeService: onDestroy()
,05-25 13:51:31.625  3549  3549 I MotionRecognitionService: Plugged
05-25 13:51:31.625  3549  3549 D MotionRecognitionService:   cableConnection= 1
05-25 13:51:31.625  3549  3549 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:51:31.625  3549  3549 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:51:31.625  3549  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:51:31.625  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,05-25 13:51:31.625  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
05-25 13:51:31.625  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
,05-25 13:51:31.635  4905  4905 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:51:31.645 10053 10053 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,05-25 13:51:31.645 10053 10095 D HeadsetStateMachine: Disconnected process message: 10, size: 0
05-25 13:51:31.645  4905  4905 D BatteryMonitor: new battery level: 100
,05-25 13:51:31.665  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
05-25 13:51:31.665  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:31.685  3549  4066 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-25 13:51:31.685  3549  4066 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4323, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:51:31.685  3549  4066 D BatteryService: online:4, current avg:-1, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:5
05-25 13:51:31.685  3549  3549 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:51:31.685  3549  3549 I MotionRecognitionService: Plugged
05-25 13:51:31.685  3549  3549 D MotionRecognitionService:   cableConnection= 1
05-25 13:51:31.685  3549  3549 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:51:31.685  3549  3549 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:51:31.685  3549  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:51:31.685  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
05-25 13:51:31.685  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
,05-25 13:51:31.695  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:51:31.695  4905  4905 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:51:31.705  4905  4905 D BatteryMonitor: new battery level: 100
,05-25 13:51:31.705 10053 10053 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,05-25 13:51:31.705 10053 10095 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-25 13:51:31.715  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
05-25 13:51:31.715  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:31.905  3549  3603 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:51:31.915  3549  3603 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{86c1de7 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5a24364 10411:com.samsung.android.scloud:contentsync/5009}
,05-25 13:51:31.915 10411 10411 I [SC]DetectorReceiver: onReceive [android.net.conn.CONNECTIVITY_CHANGE]
05-25 13:51:31.915 10411 10411 I [SC]CloudManager: requestInit
,05-25 13:51:31.915 10411 10411 I [SC]Utils: folder : cachecreate fail, try again.
05-25 13:51:31.915 10411 10411 I [SC]Utils: folder : cache create fail.
05-25 13:51:31.915 10411 10411 I [SC]Utils: folder : thumbnailcreate fail, try again.
05-25 13:51:31.915 10411 10411 I [SC]Utils: folder : thumbnail create fail.
,05-25 13:51:31.915 10411 10411 I [SC]Utils: folder : sharecreate fail, try again.
05-25 13:51:31.915 10411 10411 I [SC]Utils: folder : share create fail.
05-25 13:51:31.915 10411 10411 I [SC]Utils: folder : scratchcreate fail, try again.
05-25 13:51:31.915 10411 10411 I [SC]Utils: folder : scratch create fail.
05-25 13:51:31.915 10411 10411 I [SC]Utils: folder : eventSynccreate fail, try again.
05-25 13:51:31.915 10411 10411 I [SC]Utils: folder : eventSync create fail.
,05-25 13:51:31.935  7288  7836 I SA      : [SCU] isHaveSA() - false
05-25 13:51:31.935  7288  7836 I SA      : [OCP] Samsung account is not Signed-in
,05-25 13:51:31.935  7288  7836 I SA      : [OCP] Delete DB (TNC data)
,05-25 13:51:31.935 10411 10411 I [SC]CommonUtil: Samsung Account Not Logged in
,05-25 13:51:31.945  3549  4367 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:51:31.945  3549  4367 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{86c1de7 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{31daf00 10456:com.samsung.android.coreapps/5011}
,05-25 13:51:31.975  3549  4286 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,05-25 13:51:31.975  3549  4286 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:51:31.975  3549  4286 D BatteryService: online:4, current avg:0, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:143
05-25 13:51:31.975  3549  3549 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:51:31.975  3549  3549 I MotionRecognitionService: Plugged
05-25 13:51:31.975  3549  3549 D MotionRecognitionService:   cableConnection= 1
05-25 13:51:31.975  3549  3549 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:51:31.975  3549  3549 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:51:31.975  3549  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:51:31.985  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
05-25 13:51:31.985  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
05-25 13:51:31.985  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:51:31.995  4905  4905 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:51:31.995  4905  4905 D BatteryMonitor: new battery level: 100
,05-25 13:51:31.995 10053 10053 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-25 13:51:31.995 10053 10095 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-25 13:51:32.015  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
05-25 13:51:32.015  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:32.025  3549  4066 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:51:32.035  3549  4066 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{86c1de7 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{31daf00 10456:com.samsung.android.coreapps/5011}
,05-25 13:51:32.055  3549  4286 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:51:32.065  3549  4435 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,05-25 13:51:32.065  3549  4286 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{86c1de7 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{31daf00 10456:com.samsung.android.coreapps/5011}
,05-25 13:51:32.065  3549  4286 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:51:32.075  3549  4286 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{86c1de7 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ba3ee7d 4967:com.microsoft.skydrive/u0a124}
,05-25 13:51:32.095  3549  3981 W IntentResolver: resolveIntent failed: found match, but none with CATEGORY_DEFAULT
,05-25 13:51:32.095  3549  3568 D ActivityManager:  getDeferredInfo final delay 300
,05-25 13:51:32.165  3549  3567 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-25 13:51:32.165  3549  3567 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4317, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:51:32.165  3549  3567 D BatteryService: online:4, current avg:0, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-75
05-25 13:51:32.165  3549  3549 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:51:32.165  3549  3549 I MotionRecognitionService: Plugged
05-25 13:51:32.165  3549  3549 D MotionRecognitionService:   cableConnection= 1
05-25 13:51:32.165  3549  3549 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:51:32.165  3549  3549 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:51:32.165  3549  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:51:32.165  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
05-25 13:51:32.165  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
,05-25 13:51:32.165  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:51:32.175  4905  4905 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:51:32.175  4905  4905 D BatteryMonitor: new battery level: 100
,05-25 13:51:32.185 10053 10053 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-25 13:51:32.185 10053 10095 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-25 13:51:32.195  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
05-25 13:51:32.195  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:32.215  3549  4430 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,05-25 13:51:32.365  3549  3981 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-25 13:51:32.365  3549  3981 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4325, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:51:32.365  3549  3981 D BatteryService: online:4, current avg:0, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:62
05-25 13:51:32.365  3549  3549 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:51:32.365  3549  3549 I MotionRecognitionService: Plugged
05-25 13:51:32.365  3549  3549 D MotionRecognitionService:   cableConnection= 1
05-25 13:51:32.365  3549  3549 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:51:32.365  3549  3549 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:51:32.365  3549  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:51:32.375  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,05-25 13:51:32.375  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
05-25 13:51:32.375  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:51:32.385  4905  4905 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:51:32.395  4905  4905 D BatteryMonitor: new battery level: 100
,05-25 13:51:32.395 10053 10053 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-25 13:51:32.395 10053 10095 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-25 13:51:32.395  3549  3603 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:51:32.405  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:32.405  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:32.415  3549  3603 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{86c1de7 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a84e2df 10484:com.google.android.apps.photos/u0a129}
,05-25 13:51:32.425  3549  3603 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d2277e1 u0 com.google.android.apps.photos.actionqueue.INTERNAL_ACTION qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a84e2df 10484:com.google.android.apps.photos/u0a129}
05-25 13:51:32.425  3549  3568 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:51:32.435  3549  3568 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{86c1de7 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a84e2df 10484:com.google.android.apps.photos/u0a129}
,05-25 13:51:32.465  3549  3603 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{17e9bc7 u0 com.google.android.apps.photos.jobqueue.EXECUTE_JOBS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a84e2df 10484:com.google.android.apps.photos/u0a129}
05-25 13:51:32.465  3549  4420 D ActivityManager:  getDeferredInfo final delay 300
,05-25 13:51:32.575  3549  3986 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-25 13:51:32.575  3549  3986 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:51:32.575  3549  3986 D BatteryService: online:4, current avg:1, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:99
,05-25 13:51:32.575  3549  3549 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:51:32.585  3549  3549 I MotionRecognitionService: Plugged
05-25 13:51:32.585  3549  3549 D MotionRecognitionService:   cableConnection= 1
05-25 13:51:32.585  3549  3549 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:51:32.585  3549  3549 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:51:32.585  3549  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:51:32.585  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,05-25 13:51:32.595  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:51:32.595  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
,05-25 13:51:32.605  4905  4905 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:51:32.615  4905  4905 D BatteryMonitor: new battery level: 100
,05-25 13:51:32.615 10053 10053 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-25 13:51:32.615 10053 10095 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-25 13:51:32.625  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
05-25 13:51:32.625  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:32.685  3549  4432 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-25 13:51:32.685  3549  4432 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4328, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:51:32.685  3549  4432 D BatteryService: online:4, current avg:3, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:114
05-25 13:51:32.685  3549  3549 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:51:32.685  3549  3549 I MotionRecognitionService: Plugged
05-25 13:51:32.685  3549  3549 D MotionRecognitionService:   cableConnection= 1
05-25 13:51:32.685  3549  3549 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:51:32.685  3549  3549 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:51:32.695  3549  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:51:32.695  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
05-25 13:51:32.695  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
05-25 13:51:32.695  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:51:32.705  4905  4905 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:51:32.715  4905  4905 D BatteryMonitor: new battery level: 100
,05-25 13:51:32.715 10053 10053 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-25 13:51:32.715 10053 10095 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-25 13:51:32.725  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
05-25 13:51:32.725  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:32.795  3549  3603 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:51:32.805  3549  3603 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{86c1de7 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ef3b2f5 4724:com.sec.android.daemonapp/u0a159}
,05-25 13:51:32.805  4724  4724 D [Weather Widget]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CFAAE09BFCA326403459399C53A4EE79DAC193CEB26509F8FF7498BE5251A746097407E81C28CD811D388C49D613C81F395B356AA489D29CB4C3BE983CCC84BA76AF507AA66A943348DF162DECA2A5A7DD]}
,05-25 13:51:32.805  4724  4724 D [Weather Widget]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CFE2E89F45594D9820F24D88E9AF210A78152C254DDD0027D207FA50AD616546E30965FECE0D7B834EEF4B0E211833EA2B]}
05-25 13:51:32.805  3549  4433 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:51:32.815  3549  4433 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{86c1de7 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f3e5ff6 7884:com.sec.android.app.samsungapps/u0a14}
,05-25 13:51:32.815  7884  7884 D [SAUI]  : NetworkStateReceiver::connected::recovered?false
,05-25 13:51:32.825  7884  7884 D [SAUI]  : Global::recovered::false
,05-25 13:51:32.825  3549  4435 D ActivityManager:  getDeferredInfo final delay 300
05-25 13:51:32.825  7884  7884 D [SAUI]  : AutoUpdateService::onStartCommand
05-25 13:51:32.825  7884  7884 D [SAUI]  : AutoUpdateService::runAutoUpdateManager
,05-25 13:51:32.835  7884  7884 D [SAUI]  : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,05-25 13:51:32.835  7884  7884 D [SAUI]  : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
,05-25 13:51:32.835  7884  7884 D [SA_INIT]: AutoUpdateManager ServiceInitializer startInitialize()
05-25 13:51:32.835  7884  9019 D [SA_INIT]: createTaskForServiceInitialize()
,05-25 13:51:32.835  7884  9020 D [SA_INIT]: NetworkStateCheckUnit workImpl()
,05-25 13:51:32.835  7884  9020 D [SA_INIT]: NetworkStateCheckUnit result : 1
05-25 13:51:32.835  7884  7884 V JOULE   : JOULELOG [main]  com.sec.android.app.joule.f Task [35, 234026243_0] [END] FINISHED
05-25 13:51:32.835  7884  7884 D [SA_INIT]: ServiceInitializer onInitializeResult() reuslt : true
05-25 13:51:32.835  7884  7884 D [SAUI]  : AutoUpdateManager:INITCHECK:onInitializeSuccess
,05-25 13:51:32.835  7884  7884 D [SAUI]  : AutoUpdateTriggerManager:IDLE:notifyNextTime
,05-25 13:51:32.835  7884  7884 D [SAUI]  : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,05-25 13:51:33.195 10345 10345 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,05-25 13:51:33.345  3549  4131 E Watchdog: !@Sync 10 [05-25 13:51:33.355]
,05-25 13:51:33.615  3549  3869 D ConnectivityService: handlePromptUnvalidated 503
,05-25 13:51:34.035  3549  3805 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
05-25 13:51:34.035  3549  3805 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,05-25 13:51:34.035  3549  3805 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,05-25 13:51:34.035  3549  3805 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,05-25 13:51:34.525  9936  9999 I io.jxcore.node.IncomingSocketThreadTest: IncomingSocketThreadTest failed, attempts left 9
05-25 13:51:34.525  9936  9999 I io.jxcore.node.IncomingSocketThreadTest: outgoingOutputStream.toString() = 
05-25 13:51:34.525  9936  9999 I io.jxcore.node.IncomingSocketThreadTest: textIncoming = Nullam in massa. Vivamus elit odio, in neque ut congue quis, venenatis placerat, nulla ornare suscipit, erat urna, pellentesque dapibus vel, lorem. Sed egestas non, dolor. Aliquam hendrerit sollicitudin sed.
,05-25 13:51:34.525  9936 10563 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
05-25 13:51:34.525  9936 10563 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,05-25 13:51:34.535  3157  3609 D EnterpriseController: netId is 0
05-25 13:51:34.535  3157  3609 D Netd    : getNetworkForDns: using netid 503 for uid 10074
,05-25 13:51:34.535  9936 10565 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
05-25 13:51:34.535  9936 10565 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
05-25 13:51:34.535  9936 10565 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-25 13:51:34.535  9936 10565 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-25 13:51:34.535  9936 10563 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
05-25 13:51:34.535  9936 10563 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
05-25 13:51:34.535  9936 10565 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
05-25 13:51:34.535  9936 10563 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-25 13:51:34.535  9936 10563 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-25 13:51:34.545  9936 10563 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,05-25 13:51:34.545  9936 10567 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 252, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:34.545  9936 10567 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:51:34.545  9936 10567 D io.jxcore.node.StreamCopyingThread:  id: 80
,05-25 13:51:34.545  9936 10569 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 254, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:34.545  9936 10569 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:51:34.545  9936 10569 D io.jxcore.node.StreamCopyingThread:  id: 81
,05-25 13:51:34.545  9936 10570 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 255, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:34.545  9936 10570 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:51:34.545  9936 10570 D io.jxcore.node.StreamCopyingThread:  id: 81
05-25 13:51:34.545  9936 10570 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 255, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:34.545  9936 10570 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:51:34.545  9936 10570 D io.jxcore.node.StreamCopyingThread:  id: 81
05-25 13:51:34.545  9936 10570 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:34.545  9936 10570 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:51:34.545  9936 10570 D io.jxcore.node.StreamCopyingThread:  id: 81
05-25 13:51:34.545  9936 10570 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,05-25 13:51:34.545  9936 10570 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
05-25 13:51:34.545  9936 10570 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
05-25 13:51:34.545  9936 10570 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
05-25 13:51:34.545  9936 10570 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
05-25 13:51:34.545  9936 10570 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
05-25 13:51:34.545  9936 10570 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 255, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:34.545  9936 10570 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:51:34.545  9936 10570 D io.jxcore.node.StreamCopyingThread:  id: 81 .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,05-25 13:51:34.545  9936 10568 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 253, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:34.545  9936 10568 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:51:34.545  9936 10568 D io.jxcore.node.StreamCopyingThread:  id: 80
05-25 13:51:34.545  9936 10568 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 253, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:34.545  9936 10568 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:51:34.545  9936 10568 D io.jxcore.node.StreamCopyingThread:  id: 80
05-25 13:51:34.545  9936 10568 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:34.545  9936 10568 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:51:34.545  9936 10568 D io.jxcore.node.StreamCopyingThread:  id: 80
05-25 13:51:34.545  9936 10568 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
05-25 13:51:34.545  9936 10568 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
05-25 13:51:34.545  9936 10568 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
05-25 13:51:34.545  9936 10568 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,05-25 13:51:34.545  9936 10568 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
05-25 13:51:34.545  9936 10568 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
05-25 13:51:34.545  9936 10568 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 253, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:34.545  9936 10568 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:51:34.545  9936 10568 D io.jxcore.node.StreamCopyingThread:  id: 80 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
05-25 13:51:34.545  9936 10569 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 254, thread name: OutgoingSocketThread/Sender): Socket closed
05-25 13:51:34.545  9936 10569 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 254, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:34.545  9936 10569 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:51:34.545  9936 10569 D io.jxcore.node.StreamCopyingThread:  id: 81 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
05-25 13:51:34.545  9936 10569 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
,05-25 13:51:34.545  9936 10569 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
05-25 13:51:34.545  9936 10569 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 254, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:34.545  9936 10569 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:51:34.545  9936 10569 D io.jxcore.node.StreamCopyingThread:  id: 81 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
05-25 13:51:34.545  9936 10567 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 252, thread name: IncomingSocketThread/Sender): Socket closed
05-25 13:51:34.545  9936 10567 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 252, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:34.545  9936 10567 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:51:34.545  9936 10567 D io.jxcore.node.StreamCopyingThread:  id: 80 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
05-25 13:51:34.545  9936 10567 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
05-25 13:51:34.545  9936 10567 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,05-25 13:51:34.545  9936 10567 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 252, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:34.545  9936 10567 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:51:34.545  9936 10567 D io.jxcore.node.StreamCopyingThread:  id: 80 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
,05-25 13:51:34.885  3549  6068 D SSRM:n  : SIOP:: AP = 330, PST = 331 (W:10), CP = 279, CUR = 3, LCD = 40
,05-25 13:51:35.005  4359  4458 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
05-25 13:51:35.005  4359  4458 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,05-25 13:51:36.145 10181 10204 W Babel   : ayr TOOK TOO LONG! (15001ms > 10000ms)
,05-25 13:51:36.145 10181 10206 W Babel   : ayr TOOK TOO LONG! (15001ms > 10000ms)
,05-25 13:51:36.165  3549  4420 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity newState = 2 callingPackage = 10112
,05-25 13:51:36.215 10181 10214 W Babel   : ayr TOOK TOO LONG! (15001ms > 10000ms)
,05-25 13:51:36.225 10572 10572 E Zygote  : v2
05-25 13:51:36.225 10572 10572 I libpersona: KNOX_SDCARD checking this for 10112
05-25 13:51:36.225 10572 10572 I libpersona: KNOX_SDCARD not a persona
,05-25 13:51:36.225 10572 10572 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-25 13:51:36.225  3549  3603 I ActivityManager: Start proc 10572:com.google.android.talk:matchstick/u0a112 for broadcast-3 com.google.android.talk/com.google.android.libraries.matchstick.net.MatchstickInProcessReceiver
,05-25 13:51:36.235 10572 10572 E Zygote  : accessInfo : 0
05-25 13:51:36.235 10572 10572 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.talk:matchstick 
,05-25 13:51:36.245  3549  4432 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,05-25 13:51:36.255 10181 10181 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
05-25 13:51:36.255 10181 10181 W Babel   : BAM#gBA: invalid account id: -1
05-25 13:51:36.255 10181 10181 W Babel   : BAM#gBA: invalid account id: -1
05-25 13:51:36.255 10181 10181 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,05-25 13:51:36.265 10572 10572 D TimaKeyStoreProvider: TimaSignature is unavailable
05-25 13:51:36.265 10572 10572 D ActivityThread: Added TimaKeyStore provider
,05-25 13:51:36.265  3549  3838 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,05-25 13:51:36.295  3549  4367 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7bf2d63 u0 register_intent_action qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9ccad60 10572:com.google.android.talk:matchstick/u0a112}
,05-25 13:51:36.305 10572 10572 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.google.android.talk rsrc of package com.google.android.talk
,05-25 13:51:36.305  3549  4931 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-25 13:51:36.305 10572 10572 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-25 13:51:36.315 10572 10572 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:51:36.315 10572 10572 I InjectionManager: Inside getClassLibPath caller 
,05-25 13:51:36.335 10572 10572 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm64
,05-25 13:51:36.425 10572 10572 D InjectionManager: InjectionManager
05-25 13:51:36.425 10572 10572 D InjectionManager: fillFeatureStoreMap com.google.android.talk
05-25 13:51:36.425 10572 10572 I InjectionManager: Constructor com.google.android.talk, Feature store :{}
05-25 13:51:36.425 10572 10572 I InjectionManager: featureStore :{}
,05-25 13:51:36.435  3549  4367 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-25 13:51:36.435  3549  4367 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:51:36.435  3549  4367 D BatteryService: online:4, current avg:44, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:39
05-25 13:51:36.435  3549  3549 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:51:36.445  3549  3549 I MotionRecognitionService: Plugged
05-25 13:51:36.445  3549  3549 D MotionRecognitionService:   cableConnection= 1
05-25 13:51:36.445  3549  3549 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:51:36.445  3549  3549 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:51:36.445  3549  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:51:36.445  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,05-25 13:51:36.455  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
05-25 13:51:36.455  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:51:36.455  4905  4905 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:51:36.465 10053 10053 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-25 13:51:36.465  4905  4905 D BatteryMonitor: new battery level: 100
05-25 13:51:36.465 10053 10095 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-25 13:51:36.485  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
05-25 13:51:36.485  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:36.605 10572 10591 I MS_RegisterService: RegisterService intent:Intent { act=register_intent_action flg=0x10 cmp=com.google.android.talk/com.google.android.libraries.matchstick.net.SilentRegisterService bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} } isPeriodic:false
,05-25 13:51:36.615 10572 10591 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in com.google.android.talk rsrc of package com.google.android.gms
,05-25 13:51:36.625 10572 10591 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:51:36.625 10572 10591 I InjectionManager: Inside getClassLibPath caller 
,05-25 13:51:36.645 10572 10591 W System  : ClassLoader referenced unknown path: /system/priv-app/GmsCore/lib/arm64
,05-25 13:51:36.655  3549  3568 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,05-25 13:51:36.655  3549  3568 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4329, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:51:36.655  3549  3568 D BatteryService: online:4, current avg:45, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:113
05-25 13:51:36.655  3549  3549 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:51:36.655  3549  3549 I MotionRecognitionService: Plugged
05-25 13:51:36.655  3549  3549 D MotionRecognitionService:   cableConnection= 1
05-25 13:51:36.655  3549  3549 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:51:36.655  3549  3549 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:51:36.655  3549  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:51:36.655  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,05-25 13:51:36.665  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
,05-25 13:51:36.665  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:51:36.665  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:36.675  4905  4905 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:51:36.675  4905  4905 D BatteryMonitor: new battery level: 100
,05-25 13:51:36.675 10053 10053 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-25 13:51:36.675 10053 10095 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-25 13:51:36.695  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:36.715  3549  3981 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,05-25 13:51:36.735 10572 10591 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,05-25 13:51:36.765 10572 10591 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,05-25 13:51:36.765 10572 10591 I MS_RegisterService: Not registered and not enabled. Doing nothing.
,05-25 13:51:36.765  3549  4285 I ActivityManager: Killing 9273:com.google.android.apps.docs/u0a93 (adj 15): DHA:empty #33
,05-25 13:51:36.805  3549  3567 D ActivityManager: cleanUpApplicationRecord -- 9273
,05-25 13:51:36.805  3549  3567 D ActivityManager: isAutoRunBlockedApp:: com.google.android.apps.docs, Auto Run ON
,05-25 13:51:37.005  3549  4170 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-25 13:51:37.005  3549  4170 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4334, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:51:37.005  3549  4170 D BatteryService: online:4, current avg:44, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:152
05-25 13:51:37.005  3549  3549 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:51:37.015  3549  3549 I MotionRecognitionService: Plugged
05-25 13:51:37.015  3549  3549 D MotionRecognitionService:   cableConnection= 1
05-25 13:51:37.015  3549  3549 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:51:37.015  3549  3549 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:51:37.015  3549  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:51:37.015  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
05-25 13:51:37.015  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
,05-25 13:51:37.015  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:51:37.025  4905  4905 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:51:37.035 10053 10053 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-25 13:51:37.035 10053 10095 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-25 13:51:37.045  4905  4905 D BatteryMonitor: new battery level: 100
,05-25 13:51:37.055  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:37.055  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:37.205 10345 10345 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,05-25 13:51:37.205 10345 10345 I dhcpcd  : wlan0: no IPv6 Routers available
,05-25 13:51:39.535  9936  9999 I io.jxcore.node.IncomingSocketThreadTest: IncomingSocketThreadTest failed, attempts left 8
05-25 13:51:39.535  9936  9999 I io.jxcore.node.IncomingSocketThreadTest: outgoingOutputStream.toString() = 
05-25 13:51:39.535  9936  9999 I io.jxcore.node.IncomingSocketThreadTest: textIncoming = Nullam in massa. Vivamus elit odio, in neque ut congue quis, venenatis placerat, nulla ornare suscipit, erat urna, pellentesque dapibus vel, lorem. Sed egestas non, dolor. Aliquam hendrerit sollicitudin sed.
,05-25 13:51:39.535  9936 10602 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
05-25 13:51:39.535  9936 10602 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,05-25 13:51:39.545  3157  3609 D EnterpriseController: netId is 0
05-25 13:51:39.545  3157  3609 D Netd    : getNetworkForDns: using netid 503 for uid 10074
,05-25 13:51:39.545  9936 10604 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,05-25 13:51:39.545  9936 10604 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
05-25 13:51:39.545  9936 10604 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-25 13:51:39.545  9936 10604 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-25 13:51:39.545  9936 10602 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
05-25 13:51:39.545  9936 10602 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
05-25 13:51:39.545  9936 10602 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-25 13:51:39.555  9936 10606 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 259, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:39.555  9936 10606 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:51:39.555  9936 10606 D io.jxcore.node.StreamCopyingThread:  id: 83
,05-25 13:51:39.555  9936 10604 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
05-25 13:51:39.555  9936 10602 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,05-25 13:51:39.555  9936 10607 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 260, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:39.555  9936 10607 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:51:39.555  9936 10607 D io.jxcore.node.StreamCopyingThread:  id: 83
05-25 13:51:39.555  9936 10602 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
05-25 13:51:39.555  9936 10607 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 260, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:39.555  9936 10607 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:51:39.555  9936 10607 D io.jxcore.node.StreamCopyingThread:  id: 83
05-25 13:51:39.555  9936 10607 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:39.555  9936 10607 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:51:39.555  9936 10607 D io.jxcore.node.StreamCopyingThread:  id: 83
05-25 13:51:39.555  9936 10607 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
05-25 13:51:39.555  9936 10607 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,05-25 13:51:39.555  9936 10607 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
05-25 13:51:39.555  9936 10607 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
05-25 13:51:39.555  9936 10607 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
05-25 13:51:39.555  9936 10607 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
05-25 13:51:39.555  9936 10606 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 259, thread name: IncomingSocketThread/Sender): Socket closed
05-25 13:51:39.555  9936 10607 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 260, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:39.555  9936 10607 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:51:39.555  9936 10607 D io.jxcore.node.StreamCopyingThread:  id: 83 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,05-25 13:51:39.555  9936 10606 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 259, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:39.555  9936 10606 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:51:39.555  9936 10606 D io.jxcore.node.StreamCopyingThread:  id: 83 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
05-25 13:51:39.555  9936 10606 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
05-25 13:51:39.555  9936 10606 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
05-25 13:51:39.555  9936 10606 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 259, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:39.555  9936 10606 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:51:39.555  9936 10606 D io.jxcore.node.StreamCopyingThread:  id: 83 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
,05-25 13:51:39.555  9936 10609 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 262, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:39.555  9936 10609 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:51:39.555  9936 10609 D io.jxcore.node.StreamCopyingThread:  id: 84
05-25 13:51:39.555  9936 10609 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 262, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:39.555  9936 10609 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:51:39.555  9936 10609 D io.jxcore.node.StreamCopyingThread:  id: 84
05-25 13:51:39.555  9936 10609 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:39.555  9936 10609 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:51:39.555  9936 10609 D io.jxcore.node.StreamCopyingThread:  id: 84
05-25 13:51:39.555  9936 10609 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,05-25 13:51:39.555  9936 10609 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
05-25 13:51:39.555  9936 10609 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
05-25 13:51:39.555  9936 10609 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
05-25 13:51:39.555  9936 10609 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
05-25 13:51:39.555  9936 10609 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
05-25 13:51:39.555  9936 10609 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 262, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:39.555  9936 10609 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:51:39.555  9936 10609 D io.jxcore.node.StreamCopyingThread:  id: 84 .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
05-25 13:51:39.555  9936 10608 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 261, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:39.555  9936 10608 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:51:39.555  9936 10608 D io.jxcore.node.StreamCopyingThread:  id: 84
05-25 13:51:39.555  9936 10608 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 261, thread name: OutgoingSocketThread/Sender): recvfrom failed: EBADF (Bad file descriptor)
05-25 13:51:39.555  9936 10608 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 261, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:39.555  9936 10608 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:51:39.555  9936 10608 D io.jxcore.node.StreamCopyingThread:  id: 84 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
05-25 13:51:39.555  9936 10608 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: recvfrom failed: EBADF (Bad file descriptor)
05-25 13:51:39.555  9936 10608 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
05-25 13:51:39.555  9936 10608 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 261, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:39.555  9936 10608 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:51:39.555  9936 10608 D io.jxcore.node.StreamCopyingThread:  id: 84 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
,05-25 13:51:39.825  7884  7884 D PreloadUpdateManagerStateMachine: execute::IDLE:EXECUTE
05-25 13:51:39.825  7884  7884 D PreloadUpdateManagerStateMachine: exit::IDLE
05-25 13:51:39.825  7884  7884 D PreloadUpdateManagerStateMachine: entry::CHECK_TIMEOUT_FOR_UPDATE
,05-25 13:51:39.825  7884  7884 D [SAUI]  : AutoUpdateTriggerManager:IDLE:notifyNextTime
05-25 13:51:39.825  7884  7884 D PreloadUpdateManagerStateMachine: execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,05-25 13:51:39.835  7884  7884 D PreloadUpdateManagerStateMachine: exit::CHECK_TIMEOUT_FOR_UPDATE
,05-25 13:51:39.835  7884  7884 D PreloadUpdateManagerStateMachine: entry::IDLE
,05-25 13:51:40.485  3549  3813 V AlarmManager: Expired Alarm result :4
,05-25 13:51:40.495 10246 10246 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,05-25 13:51:40.495 10246 10246 I wpa_supplicant: P2P: Current p2p state = IDLE
,05-25 13:51:40.515 10246 10246 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,05-25 13:51:40.535  3549  3603 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ca81b51 u0 null qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c4f3aaa 4628:com.google.android.gms/u0a19}
,05-25 13:51:40.575 10611 10611 E Zygote  : v2
05-25 13:51:40.575 10611 10611 I libpersona: KNOX_SDCARD checking this for 1000
05-25 13:51:40.575 10611 10611 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
05-25 13:51:40.575 10611 10611 I libpersona: KNOX_SDCARD not a persona
,05-25 13:51:40.575  3549  3813 I ActivityManager: Start proc 10611:com.mobeam.barcodeService/1000 for service com.mobeam.barcodeService/.system.AppService
05-25 13:51:40.575 10611 10611 E Zygote  : accessInfo : 0
,05-25 13:51:40.615 10611 10611 D TimaKeyStoreProvider: TimaSignature is unavailable
05-25 13:51:40.615 10611 10611 D ActivityThread: Added TimaKeyStore provider
,05-25 13:51:40.645 10611 10611 W ResourcesManager: getTopLevelResources: /system/app/BeamService/BeamService.apk / 1.0 running in com.mobeam.barcodeService rsrc of package com.mobeam.barcodeService
,05-25 13:51:40.645  3549  4170 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-25 13:51:40.645 10611 10611 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-25 13:51:40.645 10611 10611 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:51:40.655 10611 10611 I InjectionManager: Inside getClassLibPath caller 
,05-25 13:51:40.655  4628 10623 I EventLogService: Aggregate from 1495711300438 (log), 1495711300438 (data)
,05-25 13:51:40.665 10611 10611 W System  : ClassLoader referenced unknown path: /system/app/BeamService/lib/arm64
,05-25 13:51:40.665 10611 10611 D InjectionManager: InjectionManager
05-25 13:51:40.665 10611 10611 D InjectionManager: fillFeatureStoreMap com.mobeam.barcodeService
,05-25 13:51:40.675 10611 10611 I InjectionManager: Constructor com.mobeam.barcodeService, Feature store :{}
05-25 13:51:40.675 10611 10611 I InjectionManager: featureStore :{}
,05-25 13:51:40.675  3549  3568 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-25 13:51:40.675  3549  3568 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:51:40.675  3549  3568 D BatteryService: online:4, current avg:73, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-9
05-25 13:51:40.675  3549  3549 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:51:40.675  3549  3549 I MotionRecognitionService: Plugged
05-25 13:51:40.675  3549  3549 D MotionRecognitionService:   cableConnection= 1
05-25 13:51:40.675  3549  3549 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:51:40.675  3549  3549 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:51:40.675  3549  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:51:40.675  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
05-25 13:51:40.685  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
,05-25 13:51:40.685  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:51:40.685  4905  4905 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:51:40.695  4905  4905 D BatteryMonitor: new battery level: 100
,05-25 13:51:40.695 10053 10053 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-25 13:51:40.695 10053 10095 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-25 13:51:40.705  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
05-25 13:51:40.705  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:40.705  3549  3567 I ActivityManager: Killing 9295:com.samsung.android.app.filterinstaller/1000 (adj 15): DHA:empty #33
,05-25 13:51:40.725  3549  4286 D ActivityManager: cleanUpApplicationRecord -- 9295
,05-25 13:51:40.725  3549  4286 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.filterinstaller, Auto Run ON
,05-25 13:51:40.805 10627 10627 E Zygote  : v2
05-25 13:51:40.805 10627 10627 I libpersona: KNOX_SDCARD checking this for 1000
05-25 13:51:40.805 10627 10627 I libpersona: KNOX_SDCARD not a persona
,05-25 13:51:40.805 10627 10627 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-25 13:51:40.805  3549  3603 I ActivityManager: Start proc 10627:com.samsung.android.sm/1000 for broadcast-3 com.samsung.android.sm/.common.SmartManagerReceiver
05-25 13:51:40.805 10627 10627 E Zygote  : accessInfo : 0
,05-25 13:51:40.835 10627 10627 D TimaKeyStoreProvider: TimaSignature is unavailable
05-25 13:51:40.835 10627 10627 D ActivityThread: Added TimaKeyStore provider
,05-25 13:51:40.855  3549  3986 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f863553 u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1962e90 10627:com.samsung.android.sm/1000}
,05-25 13:51:40.865 10627 10627 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3_NoIcon/SmartManager_v3_NoIcon.apk / 1.0 running in com.samsung.android.sm rsrc of package com.samsung.android.sm
,05-25 13:51:40.865  3549  4066 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-25 13:51:40.865 10627 10627 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-25 13:51:40.865 10627 10627 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:51:40.875 10627 10627 I InjectionManager: Inside getClassLibPath caller 
,05-25 13:51:40.885 10627 10627 D InjectionManager: InjectionManager
05-25 13:51:40.885 10627 10627 D InjectionManager: fillFeatureStoreMap com.samsung.android.sm
,05-25 13:51:40.885 10627 10627 I InjectionManager: Constructor com.samsung.android.sm, Feature store :{}
05-25 13:51:40.885 10627 10627 I InjectionManager: featureStore :{}
,05-25 13:51:40.895  3549  3986 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{281e389 u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1962e90 10627:com.samsung.android.sm/1000}
,05-25 13:51:40.905  3549  3986 I ActivityManager: Killing 9310:com.sec.android.widgetapp.samsungapps/u0a105 (adj 15): DHA:empty #33
,05-25 13:51:40.925  3549  4285 D ActivityManager: cleanUpApplicationRecord -- 9310
,05-25 13:51:40.925  3549  4285 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.widgetapp.samsungapps, Auto Run ON
,05-25 13:51:41.385  3549  3568 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-25 13:51:41.385  3549  3568 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4328, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:51:41.385  3549  3568 D BatteryService: online:4, current avg:68, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:94
05-25 13:51:41.385  3549  3549 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:51:41.385  3549  3549 I MotionRecognitionService: Plugged
05-25 13:51:41.385  3549  3549 D MotionRecognitionService:   cableConnection= 1
05-25 13:51:41.385  3549  3549 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:51:41.385  3549  3549 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:51:41.385  3549  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:51:41.385  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
05-25 13:51:41.385  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
05-25 13:51:41.385  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
,05-25 13:51:41.395  4905  4905 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:51:41.405  4905  4905 D BatteryMonitor: new battery level: 100
,05-25 13:51:41.405 10053 10053 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-25 13:51:41.405 10053 10095 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-25 13:51:41.415  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:41.415  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:41.445  3549  4435 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,05-25 13:51:41.815  3549  3986 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-25 13:51:41.815  3549  3986 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:51:41.815  3549  3986 D BatteryService: online:4, current avg:66, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:58
05-25 13:51:41.815  3549  3549 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:51:41.815  3549  3549 I MotionRecognitionService: Plugged
05-25 13:51:41.815  3549  3549 D MotionRecognitionService:   cableConnection= 1
05-25 13:51:41.815  3549  3549 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:51:41.815  3549  3549 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:51:41.815  3549  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:51:41.815  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
05-25 13:51:41.815  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
05-25 13:51:41.815  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:51:41.825  4905  4905 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:51:41.835 10053 10053 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,05-25 13:51:41.835 10053 10095 D HeadsetStateMachine: Disconnected process message: 10, size: 0
05-25 13:51:41.835  4905  4905 D BatteryMonitor: new battery level: 100
,05-25 13:51:41.845  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:41.845  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:41.945  3549  4286 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,05-25 13:51:41.945  3549  4286 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4325, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:51:41.945  3549  4286 D BatteryService: online:4, current avg:66, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:58
05-25 13:51:41.945  3549  3549 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:51:41.955  3549  3549 I MotionRecognitionService: Plugged
,05-25 13:51:41.955  3549  3549 D MotionRecognitionService:   cableConnection= 1
05-25 13:51:41.955  3549  3549 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:51:41.955  3549  3549 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:51:41.955  3549  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:51:41.965  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,05-25 13:51:41.965  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
,05-25 13:51:41.965  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:51:41.975  4905  4905 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:51:41.985  4905  4905 D BatteryMonitor: new battery level: 100
,05-25 13:51:41.995 10053 10053 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-25 13:51:41.995 10053 10095 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-25 13:51:42.015  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
05-25 13:51:42.015  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:42.405  3549  4432 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-25 13:51:42.415  3549  4432 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:51:42.415  3549  4432 D BatteryService: online:4, current avg:64, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:61
05-25 13:51:42.415  3549  3549 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:51:42.415  3549  3549 I MotionRecognitionService: Plugged
05-25 13:51:42.415  3549  3549 D MotionRecognitionService:   cableConnection= 1
05-25 13:51:42.415  3549  3549 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:51:42.415  3549  3549 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:51:42.415  3549  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:51:42.415  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
05-25 13:51:42.415  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
,05-25 13:51:42.425  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:51:42.435  4905  4905 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:51:42.435  4905  4905 D BatteryMonitor: new battery level: 100
,05-25 13:51:42.445 10053 10053 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-25 13:51:42.445 10053 10095 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-25 13:51:42.455  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
05-25 13:51:42.455  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:42.485  3549  3981 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,05-25 13:51:42.845  7884  7884 D PreloadUpdateManagerStateMachine: execute::IDLE:EXECUTE
05-25 13:51:42.845  7884  7884 D PreloadUpdateManagerStateMachine: exit::IDLE
05-25 13:51:42.845  7884  7884 D PreloadUpdateManagerStateMachine: entry::CHECK_TIMEOUT_FOR_UPDATE
,05-25 13:51:42.845  7884  7884 D [SAUI]  : AutoUpdateTriggerManager:IDLE:notifyNextTime
05-25 13:51:42.845  7884  7884 D PreloadUpdateManagerStateMachine: execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,05-25 13:51:42.845  7884  7884 D PreloadUpdateManagerStateMachine: exit::CHECK_TIMEOUT_FOR_UPDATE
05-25 13:51:42.845  7884  7884 D PreloadUpdateManagerStateMachine: entry::IDLE
,05-25 13:51:42.845  3549  4432 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,05-25 13:51:42.855  3549  4432 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4325, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:51:42.855  3549  4432 D BatteryService: online:4, current avg:63, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:33
05-25 13:51:42.855  3549  3549 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:51:42.855  3549  3549 I MotionRecognitionService: Plugged
,05-25 13:51:42.855  3549  3549 D MotionRecognitionService:   cableConnection= 1
05-25 13:51:42.855  3549  3549 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:51:42.855  3549  3549 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:51:42.855  3549  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:51:42.855  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
05-25 13:51:42.855  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
,05-25 13:51:42.855  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:51:42.865  4905  4905 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:51:42.865 10053 10053 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,05-25 13:51:42.875 10053 10095 D HeadsetStateMachine: Disconnected process message: 10, size: 0
05-25 13:51:42.875  4905  4905 D BatteryMonitor: new battery level: 100
,05-25 13:51:42.885  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
05-25 13:51:42.885  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:42.965  3549  4435 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-25 13:51:42.965  3549  4435 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:51:42.965  3549  4435 D BatteryService: online:4, current avg:62, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:28
05-25 13:51:42.965  3549  3549 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:51:42.965  3549  3549 I MotionRecognitionService: Plugged
,05-25 13:51:42.965  3549  3549 D MotionRecognitionService:   cableConnection= 1
05-25 13:51:42.965  3549  3549 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:51:42.965  3549  3549 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:51:42.975  3549  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:51:42.975  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
05-25 13:51:42.975  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
,05-25 13:51:42.975  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:51:42.985  4905  4905 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:51:42.985 10053 10053 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,05-25 13:51:42.985 10053 10095 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-25 13:51:42.995  4905  4905 D BatteryMonitor: new battery level: 100
,05-25 13:51:43.005  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:43.005  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:43.425  3549  4420 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-25 13:51:43.425  3549  4420 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:51:43.425  3549  4420 D BatteryService: online:4, current avg:61, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:64
05-25 13:51:43.425  3549  3549 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:51:43.435  3549  3549 I MotionRecognitionService: Plugged
05-25 13:51:43.435  3549  3549 D MotionRecognitionService:   cableConnection= 1
05-25 13:51:43.435  3549  3549 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:51:43.435  3549  3549 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:51:43.435  3549  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:51:43.435  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
05-25 13:51:43.435  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
05-25 13:51:43.435  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:51:43.455  4905  4905 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:51:43.455 10053 10053 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,05-25 13:51:43.455 10053 10095 D HeadsetStateMachine: Disconnected process message: 10, size: 0
05-25 13:51:43.465  4905  4905 D BatteryMonitor: new battery level: 100
,05-25 13:51:43.475  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:43.485  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:43.545  3549  4931 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,05-25 13:51:43.845  3549  4367 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-25 13:51:43.845  3549  4367 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:51:43.845  3549  4367 D BatteryService: online:4, current avg:61, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:35
05-25 13:51:43.845  3549  3549 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:51:43.855  3549  3549 I MotionRecognitionService: Plugged
05-25 13:51:43.855  3549  3549 D MotionRecognitionService:   cableConnection= 1
05-25 13:51:43.855  3549  3549 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:51:43.855  3549  3549 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:51:43.855  3549  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:51:43.865  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,05-25 13:51:43.865  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
05-25 13:51:43.865  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:51:43.875  4905  4905 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:51:43.885  4905  4905 D BatteryMonitor: new battery level: 100
,05-25 13:51:43.885 10053 10053 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-25 13:51:43.885 10053 10095 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-25 13:51:43.905  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
05-25 13:51:43.905  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:43.935  3549  3568 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-25 13:51:43.935  3549  3568 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4322, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:51:43.935  3549  3568 D BatteryService: online:4, current avg:61, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-20
05-25 13:51:43.935  3549  3549 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:51:43.945  3549  3549 I MotionRecognitionService: Plugged
05-25 13:51:43.945  3549  3549 D MotionRecognitionService:   cableConnection= 1
05-25 13:51:43.945  3549  3549 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:51:43.945  3549  3549 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:51:43.945  3549  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:51:43.945  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
05-25 13:51:43.945  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
,05-25 13:51:43.945  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:51:43.965  4905  4905 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:51:43.965 10053 10053 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,05-25 13:51:43.965 10053 10095 D HeadsetStateMachine: Disconnected process message: 10, size: 0
05-25 13:51:43.965  4905  4905 D BatteryMonitor: new battery level: 100
,05-25 13:51:43.985  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:43.985  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:44.505  3157  3606 D Netd    : Iface wlan0 link up
,05-25 13:51:44.515 10246 10246 I wpa_supplicant: nl80211: Received scan results (13 BSSes)
05-25 13:51:44.515  3549  3614 D Tethering: interfaceLinkStateChanged wlan0, true
05-25 13:51:44.515  3549  3614 D Tethering: interfaceStatusChanged wlan0, true
,05-25 13:51:44.515 10246 10246 I wpa_supplicant: scan_only_handler, so autoscan_notify() !!!
05-25 13:51:44.515  4905  5185 D PdnController: Interface Changed wlan0 link up
,05-25 13:51:44.515  3549  3858 D WifiP2pService: InactiveState{ what=147461 }
,05-25 13:51:44.515  3549  3858 D WifiP2pService: P2pEnabledState{ what=147461 }
05-25 13:51:44.515  3549  3858 D WifiP2pService: DefaultState{ what=147461 }
,05-25 13:51:44.535  3549  3549 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.SCAN_RESULTS
,05-25 13:51:44.545  9936  9999 I io.jxcore.node.IncomingSocketThreadTest: IncomingSocketThreadTest failed, attempts left 7
05-25 13:51:44.545  9936  9999 I io.jxcore.node.IncomingSocketThreadTest: outgoingOutputStream.toString() = 
05-25 13:51:44.545  9936  9999 I io.jxcore.node.IncomingSocketThreadTest: textIncoming = Nullam in massa. Vivamus elit odio, in neque ut congue quis, venenatis placerat, nulla ornare suscipit, erat urna, pellentesque dapibus vel, lorem. Sed egestas non, dolor. Aliquam hendrerit sollicitudin sed.
05-25 13:51:44.545  3549  3603 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cb4d3af u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c130950 3949:com.android.systemui/u0a62}
,05-25 13:51:44.545  9936 10660 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
05-25 13:51:44.545  9936 10660 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,05-25 13:51:44.555  3157  3609 D EnterpriseController: netId is 0
05-25 13:51:44.555  3157  3609 D Netd    : getNetworkForDns: using netid 503 for uid 10074
,05-25 13:51:44.555  9936 10662 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
05-25 13:51:44.555  9936 10662 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
05-25 13:51:44.555  9936 10662 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,05-25 13:51:44.555  9936 10662 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-25 13:51:44.555  9936 10660 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
05-25 13:51:44.555  9936 10660 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
05-25 13:51:44.555  9936 10660 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-25 13:51:44.555  9936 10662 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
05-25 13:51:44.555  9936 10660 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,05-25 13:51:44.565  9936 10660 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,05-25 13:51:44.565  9936 10665 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 267, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:44.565  9936 10665 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:51:44.565  9936 10665 D io.jxcore.node.StreamCopyingThread:  id: 86
,05-25 13:51:44.565  9936 10665 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 267, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:44.565  9936 10665 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:51:44.565  9936 10665 D io.jxcore.node.StreamCopyingThread:  id: 86
05-25 13:51:44.565  9936 10665 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:44.565  9936 10665 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:51:44.565  9936 10665 D io.jxcore.node.StreamCopyingThread:  id: 86
05-25 13:51:44.565  9936 10665 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
05-25 13:51:44.565  9936 10665 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
05-25 13:51:44.565  9936 10665 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
05-25 13:51:44.565  9936 10665 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
05-25 13:51:44.565  9936 10665 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
05-25 13:51:44.565  9936 10665 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
05-25 13:51:44.565  9936 10665 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 267, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:44.565  9936 10665 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:51:44.565  9936 10665 D io.jxcore.node.StreamCopyingThread:  id: 86 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
05-25 13:51:44.565  9936 10666 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 268, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:44.565  9936 10666 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:51:44.565  9936 10666 D io.jxcore.node.StreamCopyingThread:  id: 87
05-25 13:51:44.565  9936 10666 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 268, thread name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:44.565  9936 10666 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:51:44.565  9936 10666 D io.jxcore.node.StreamCopyingThread:  id: 87
05-25 13:51:44.565  9936 10666 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:44.565  9936 10666 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:51:44.565  9936 10666 D io.jxcore.node.StreamCopyingThread:  id: 87
05-25 13:51:44.565  9936 10666 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
05-25 13:51:44.565  9936 10666 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
05-25 13:51:44.565  9936 10666 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
05-25 13:51:44.565  9936 10666 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
05-25 13:51:44.565  9936 10666 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
05-25 13:51:44.565  9936 10666 I io.jxcore.node.OutgoingSocketThread: The sending thread is done
05-25 13:51:44.565  9936 10666 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 268, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:44.565  9936 10666 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:51:44.565  9936 10666 D io.jxcore.node.StreamCopyingThread:  id: 87 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,05-25 13:51:44.565  9936 10664 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 266, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:44.565  9936 10664 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:51:44.565  9936 10664 D io.jxcore.node.StreamCopyingThread:  id: 86
05-25 13:51:44.565  9936 10664 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 266, thread name: IncomingSocketThread/Sender): recvfrom failed: EBADF (Bad file descriptor)
05-25 13:51:44.565  9936 10664 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 266, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:44.565  9936 10664 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:51:44.565  9936 10664 D io.jxcore.node.StreamCopyingThread:  id: 86 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
05-25 13:51:44.565  9936 10664 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: recvfrom failed: EBADF (Bad file descriptor)
,05-25 13:51:44.565  9936 10664 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
05-25 13:51:44.565  9936 10664 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 266, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:44.565  9936 10664 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:51:44.565  9936 10664 D io.jxcore.node.StreamCopyingThread:  id: 86 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
05-25 13:51:44.565  9936 10667 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 269, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:44.565  9936 10667 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:51:44.565  9936 10667 D io.jxcore.node.StreamCopyingThread:  id: 87
05-25 13:51:44.565  9936 10667 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 269, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:44.565  9936 10667 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:51:44.565  9936 10667 D io.jxcore.node.StreamCopyingThread:  id: 87
05-25 13:51:44.565  9936 10667 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:44.565  9936 10667 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:51:44.565  9936 10667 D io.jxcore.node.StreamCopyingThread:  id: 87
05-25 13:51:44.565  9936 10667 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
05-25 13:51:44.565  9936 10667 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
05-25 13:51:44.565  9936 10667 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
05-25 13:51:44.565  9936 10667 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
05-25 13:51:44.565  9936 10667 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,05-25 13:51:44.565  9936 10667 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
05-25 13:51:44.565  9936 10667 I io.jxcore.node.OutgoingSocketThread: Both threads are done, notifying the listener...
05-25 13:51:44.565  9936 10667 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 269, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:44.565  9936 10667 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:51:44.565  9936 10667 D io.jxcore.node.StreamCopyingThread:  id: 87 .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,05-25 13:51:44.575  3549  4170 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,05-25 13:51:44.575  3549  4170 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4321, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:51:44.575  3549  4170 D BatteryService: online:4, current avg:59, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:67
05-25 13:51:44.575  3549  3549 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:51:44.585  3549  3549 I MotionRecognitionService: Plugged
,05-25 13:51:44.585  3549  3549 D MotionRecognitionService:   cableConnection= 1
05-25 13:51:44.585  3549  3549 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:51:44.585  3549  3549 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:51:44.585  3549  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:51:44.585  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
05-25 13:51:44.585  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
,05-25 13:51:44.585  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:51:44.595  4905  4905 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:51:44.595 10053 10053 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,05-25 13:51:44.595 10053 10095 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-25 13:51:44.595  4905  4905 D BatteryMonitor: new battery level: 100
,05-25 13:51:44.615  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
05-25 13:51:44.615  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:44.635  3549  4430 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-25 13:51:44.635  3549  4430 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4321, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:51:44.635  3549  4430 D BatteryService: online:4, current avg:59, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-35
05-25 13:51:44.635  3549  3549 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:51:44.635  3549  3549 I MotionRecognitionService: Plugged
05-25 13:51:44.635  3549  3549 D MotionRecognitionService:   cableConnection= 1
05-25 13:51:44.635  3549  3549 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:51:44.635  3549  3549 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:51:44.635  3549  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:51:44.635  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
05-25 13:51:44.635  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
,05-25 13:51:44.635  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:51:44.645  4905  4905 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:51:44.645 10053 10053 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,05-25 13:51:44.645 10053 10095 D HeadsetStateMachine: Disconnected process message: 10, size: 0
05-25 13:51:44.645  4905  4905 D BatteryMonitor: new battery level: 100
,05-25 13:51:44.665  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:44.665  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:44.905  3549  6068 D SSRM:n  : SIOP:: AP = 320, PST = 330 (W:10), CP = 277, CUR = 59, LCD = 40
,05-25 13:51:44.905  3549  4420 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-25 13:51:44.905  3549  4420 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4328, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:51:44.905  3549  4420 D BatteryService: online:4, current avg:59, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:162
05-25 13:51:44.905  3549  3549 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:51:44.905  3549  3549 I MotionRecognitionService: Plugged
05-25 13:51:44.905  3549  3549 D MotionRecognitionService:   cableConnection= 1
05-25 13:51:44.905  3549  3549 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:51:44.905  3549  3549 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:51:44.905  3549  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:51:44.905  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,05-25 13:51:44.905  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
05-25 13:51:44.915  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:51:44.915  4905  4905 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:51:44.925 10053 10053 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-25 13:51:44.925 10053 10095 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-25 13:51:44.925  4905  4905 D BatteryMonitor: new battery level: 100
,05-25 13:51:44.935  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
05-25 13:51:44.935  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:49.355  3549  6115 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,05-25 13:51:49.545  9936  9999 I io.jxcore.node.IncomingSocketThreadTest: IncomingSocketThreadTest failed, attempts left 6
05-25 13:51:49.545  9936  9999 I io.jxcore.node.IncomingSocketThreadTest: outgoingOutputStream.toString() = Nullam in massa. Vivamus elit odio, in neque ut congue quis, venenatis placerat, nulla ornare suscipit, erat urna, pellentesque dapibus vel, lorem. Sed egestas non, dolor. Aliquam hendrerit sollicitudin sed.
05-25 13:51:49.545  9936  9999 I io.jxcore.node.IncomingSocketThreadTest: textIncoming = Nullam in massa. Vivamus elit odio, in neque ut congue quis, venenatis placerat, nulla ornare suscipit, erat urna, pellentesque dapibus vel, lorem. Sed egestas non, dolor. Aliquam hendrerit sollicitudin sed.
05-25 13:51:49.555  9936  9999 I !!      :  finally closed
,05-25 13:51:49.555  9936  9999 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
,05-25 13:51:49.555  9936  9999 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,05-25 13:51:49.555  9936  9999 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
05-25 13:51:49.555  9936  9999 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,05-25 13:51:49.555  9936  9999 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,05-25 13:51:49.565  9936  9999 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
,05-25 13:51:49.565  9936  9999 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.thaliproject.thalitest.MainActivity@3eeb9d3 Bundle[{}]
,05-25 13:51:49.565  9936  9999 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
05-25 13:51:49.565  9936  9999 I io.jxcore.node.LifeCycleMonitor: start: OK
05-25 13:51:49.565  9936  9999 I io.jxcore.node.LifeCycleMonitor: stop: OK
,05-25 13:51:49.565  9936  9999 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
,05-25 13:51:49.565  9936  9999 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,05-25 13:51:49.575  9936  9999 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
05-25 13:51:49.575  9936  9999 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
05-25 13:51:49.575  9936  9999 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
05-25 13:51:49.575  9936  9999 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
05-25 13:51:49.575  9936  9999 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
05-25 13:51:49.575  9936  9999 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,05-25 13:51:49.575  9936  9999 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
,05-25 13:51:49.575  9936  9999 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,05-25 13:51:49.575  9936  9999 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
,05-25 13:51:49.585  9936  9999 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
,05-25 13:51:49.585  9936  9999 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
,05-25 13:51:49.585  9936  9999 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
,05-25 13:51:49.585  9936  9999 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testRun
,05-25 13:51:49.585  9936 10673 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,05-25 13:51:49.585  9936 10673 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,05-25 13:51:49.595  3157  3609 D EnterpriseController: netId is 0
,05-25 13:51:49.595  3157  3609 D Netd    : getNetworkForDns: using netid 503 for uid 10074
,05-25 13:51:49.595  9936 10675 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
05-25 13:51:49.595  9936 10675 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,05-25 13:51:49.595  9936 10675 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-25 13:51:49.595  9936 10673 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
05-25 13:51:49.595  9936 10675 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-25 13:51:49.595  9936 10673 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
05-25 13:51:49.595  9936 10673 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-25 13:51:49.595  9936 10675 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
05-25 13:51:49.595  9936 10673 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-25 13:51:49.595  9936 10673 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,05-25 13:51:49.605  9936 10680 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 276, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:49.605  9936 10680 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:51:49.605  9936 10680 D io.jxcore.node.StreamCopyingThread:  id: 90
,05-25 13:51:49.605  9936 10680 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 276, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:49.605  9936 10680 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:51:49.605  9936 10680 D io.jxcore.node.StreamCopyingThread:  id: 90
05-25 13:51:49.605  9936 10680 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:49.605  9936 10680 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:51:49.605  9936 10680 D io.jxcore.node.StreamCopyingThread:  id: 90
05-25 13:51:49.605  9936 10680 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
05-25 13:51:49.605  9936 10680 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
05-25 13:51:49.605  9936 10680 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
05-25 13:51:49.605  9936 10680 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,05-25 13:51:49.605  9936 10680 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
05-25 13:51:49.605  9936 10680 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
05-25 13:51:49.605  9936 10680 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 276, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:49.605  9936 10680 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:51:49.605  9936 10680 D io.jxcore.node.StreamCopyingThread:  id: 90 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
05-25 13:51:49.605  9936 10679 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 275, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:49.605  9936 10679 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:51:49.605  9936 10679 D io.jxcore.node.StreamCopyingThread:  id: 90
,05-25 13:51:49.605  9936 10678 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 274, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:49.605  9936 10678 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:51:49.605  9936 10678 D io.jxcore.node.StreamCopyingThread:  id: 89
,05-25 13:51:49.605  9936 10679 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 275, thread name: OutgoingSocketThread/Sender): recvfrom failed: EBADF (Bad file descriptor)
05-25 13:51:49.605  9936 10679 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 275, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:49.605  9936 10679 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:51:49.605  9936 10679 D io.jxcore.node.StreamCopyingThread:  id: 90 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
05-25 13:51:49.605  9936 10679 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: recvfrom failed: EBADF (Bad file descriptor)
,05-25 13:51:49.605  9936 10679 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
05-25 13:51:49.605  9936 10679 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 275, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:49.605  9936 10679 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:51:49.605  9936 10679 D io.jxcore.node.StreamCopyingThread:  id: 90 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
05-25 13:51:49.605  9936 10677 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 273, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:49.605  9936 10677 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:51:49.605  9936 10677 D io.jxcore.node.StreamCopyingThread:  id: 89
05-25 13:51:49.605  9936 10677 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 273, thread name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:49.605  9936 10677 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:51:49.605  9936 10677 D io.jxcore.node.StreamCopyingThread:  id: 89
,05-25 13:51:49.605  9936 10678 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 274, thread name: IncomingSocketThread/Receiver): sendto failed: EPIPE (Broken pipe)
05-25 13:51:49.605  9936 10677 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:49.605  9936 10677 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:51:49.605  9936 10677 D io.jxcore.node.StreamCopyingThread:  id: 89
05-25 13:51:49.605  9936 10677 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
05-25 13:51:49.605  9936 10677 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
05-25 13:51:49.605  9936 10677 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
05-25 13:51:49.605  9936 10678 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 274, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:49.605  9936 10678 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:51:49.605  9936 10678 D io.jxcore.node.StreamCopyingThread:  id: 89 .During the lifetime of the thread the total number of bytes read was 8192 and the total number of bytes written 4096
,05-25 13:51:49.605  9936 10677 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
05-25 13:51:49.605  9936 10677 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
05-25 13:51:49.605  9936 10677 I io.jxcore.node.IncomingSocketThread: The sending thread is done
05-25 13:51:49.605  9936 10678 E io.jxcore.node.IncomingSocketThread: The receiving thread failed with error "Failed to write to the output stream: sendto failed: EPIPE (Broken pipe)", this is likely due to peer having disconnected
05-25 13:51:49.605  9936 10678 D io.jxcore.node.StreamCopyingThread: number of bytes read = 4096
05-25 13:51:49.605  9936 10677 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 273, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:49.605  9936 10677 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:51:49.605  9936 10677 D io.jxcore.node.StreamCopyingThread:  id: 89 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,05-25 13:51:49.605  9936 10678 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 274, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:51:49.605  9936 10678 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:51:49.605  9936 10678 D io.jxcore.node.StreamCopyingThread:  id: 89 .During the lifetime of the thread the total number of bytes read was 8192 and the total number of bytes written 4096

```
