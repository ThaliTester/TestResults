#### Test 9835488260af434_thali05_samsung-SM-G935F Logs


```
--------- beginning of main
12-19 12:52:30.332  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:30.522  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
12-19 12:52:30.702  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
12-19 12:52:30.742  3421  9500 I HarmonyEASService: Updating for all 1
12-19 12:52:30.842  9560  9560 I FIPS_bssl: FIPS approved mode (1) | 9560 | app_process
12-19 12:52:30.842  9560  9560 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
12-19 12:52:30.842  9560  9560 D AndroidRuntime: CheckJNI is OFF
12-19 12:52:30.852  9560  9560 D AndroidRuntime: readGMSProperty: start
12-19 12:52:30.852  9560  9560 D AndroidRuntime: readGMSProperty: already setted!!
12-19 12:52:30.852  9560  9560 D AndroidRuntime: propertySet: couldn't set property (it is from app)
12-19 12:52:30.852  9560  9560 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
12-19 12:52:30.852  9560  9560 D AndroidRuntime: readGMSProperty: end
12-19 12:52:30.852  9560  9560 D AndroidRuntime: addProductProperty: start
12-19 12:52:30.872  9560  9560 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
12-19 12:52:30.882  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
12-19 12:52:30.892  9560  9560 I Radio-JNI: register_android_hardware_Radio DONE
12-19 12:52:30.902  9560  9560 E AffinityControl: AffinityControl: registerfunction enter
12-19 12:52:30.912  9560  9560 D AndroidRuntime: Calling main entry com.android.commands.am.Am
12-19 12:52:30.932  3421  3472 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
--------- beginning of system
12-19 12:52:30.932  3421  3472 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
12-19 12:52:30.942  3421  3472 D ResourcesManager: For user 0 new overlays fetched Null
12-19 12:52:30.942  3421  3472 D GameManagerService: identifyGamePackage. com.test.thalitest
12-19 12:52:30.942  3421  3472 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
12-19 12:52:30.952  3421  3472 D ActivityManager: mDVFSHelper.acquire()
12-19 12:52:30.952  3421  3472 V WindowManager: addAppToken: AppWindowToken{d0d45be8c token=Token{a1257bf ActivityRecord{74799de u0 com.test.thalitest/.MainActivity t20}}} to stack=2 task=20 at 0
12-19 12:52:30.952  3421  3570 I InjectionManager: Inside getClassLibPath caller 
12-19 12:52:30.962  3421  3570 D SecWifiDisplayUtil: Metadata value : SecSettings2
12-19 12:52:30.962  3421  3570 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{6f35324 V.E...... R.....ID 0,0-0,0}
12-19 12:52:30.972  9569  9569 E Zygote  : v2
12-19 12:52:30.972  9569  9569 I libpersona: KNOX_SDCARD checking this for 10078
12-19 12:52:30.972  9569  9569 I libpersona: KNOX_SDCARD not a persona
12-19 12:52:30.982  9569  9569 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0029
12-19 12:52:30.982  3421  3472 I ActivityManager: Start proc 9569:com.test.thalitest/u0a78 for activity com.test.thalitest/.MainActivity
12-19 12:52:30.982  3421  3570 D ISSUE_DEBUG: InputChannelName : 274d842 Starting com.test.thalitest
12-19 12:52:30.982  3421  3570 W WindowManager: Failed looking up window
12-19 12:52:30.982  3421  3570 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@ac78e8d does not exist
12-19 12:52:30.982  3421  3570 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14805)
12-19 12:52:30.982  3421  3570 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
12-19 12:52:30.982  3421  3570 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
12-19 12:52:30.982  3421  3570 W WindowManager: 	at android.view.ViewRootImpl.pokeDrawLockIfNeeded(ViewRootImpl.java:1203)
12-19 12:52:30.982  3421  3570 W WindowManager: 	at android.view.ViewRootImpl.scheduleTraversals(ViewRootImpl.java:1415)
12-19 12:52:30.982  3421  3570 W WindowManager: 	at android.view.ViewRootImpl.requestLayout(ViewRootImpl.java:1222)
12-19 12:52:30.982  3421  3570 W WindowManager: 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:800)
12-19 12:52:30.982  3421  3570 W WindowManager: 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:337)
12-19 12:52:30.982  3421  3570 W WindowManager: 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:91)
12-19 12:52:30.982  3421  3570 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4378)
12-19 12:52:30.982  3421  3570 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13482)
12-19 12:52:30.982  3421  3570 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
12-19 12:52:30.982  3421  3570 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
12-19 12:52:30.982  3421  3570 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
12-19 12:52:30.982  3421  3570 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
12-19 12:52:30.982  9569  9569 E Zygote  : accessInfo : 0
12-19 12:52:30.982  3421  3472 D InputDispatcher: Focused application set to: xxxx
12-19 12:52:30.982  9569  9569 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
12-19 12:52:30.982  9560  9560 D AndroidRuntime: Shutting down VM
12-19 12:52:30.982  3421  3856 D NetworkPolicy: isUidForegroundLocked: 10078, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
12-19 12:52:30.992  3010  3010 I SurfaceFlinger: id=20 createSurf (1x1),1 flag=404, uhalitest
12-19 12:52:31.002  9569  9569 D TimaKeyStoreProvider: TimaSignature is unavailable
12-19 12:52:31.002  9569  9569 D ActivityThread: Added TimaKeyStore provider
12-19 12:52:31.022  3421  3570 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
12-19 12:52:31.042  5854  5854 E CocktailBarPositionManager: Window direction: 0
12-19 12:52:31.042  5854  5854 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
12-19 12:52:31.042  3421  4391 D ActivityManager:  Launching com.test.thalitest, updated priority
12-19 12:52:31.042  4310  4310 V ActivityThread: updateVisibility : ActivityRecord{6b81730 token=android.os.BinderProxy@a68b46f {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
12-19 12:52:31.052  6834  6834 V ActivityThread: updateVisibility : ActivityRecord{86e5c32 token=android.os.BinderProxy@74cd84b {com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity}} show : false
12-19 12:52:31.062  3010  3827 I SurfaceFlinger: id=19 Removed YUIInstallC (7/12)
12-19 12:52:31.062  5854  5864 I TrayUsageStatesWatcher: noteResumeComponent : ComponentInfo{com.test.thalitest/com.test.thalitest.MainActivity} Intent { flg=0x10000000 cmp=com.test.thalitest/.MainActivity VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
12-19 12:52:31.062  3010  3021 I SurfaceFlinger: id=19 Removed YUIInstallC (-2/12)
12-19 12:52:31.072  3421  3421 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
12-19 12:52:31.072  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
12-19 12:52:31.072  3010  4490 D libEGL  : eglTerminate EGLDisplay = 0x7f9b200e78
12-19 12:52:31.072  3010  4490 D libEGL  : eglTerminate EGLDisplay = 0x7f9b200e78
12-19 12:52:31.072  3421  3570 V WindowStateAnimator: Finishing drawing window Window{274d842 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
12-19 12:52:31.072  3010  4490 I SurfaceFlinger: id=10 Removed MauncherAct (6/11)
12-19 12:52:31.072  3010  3019 I SurfaceFlinger: id=10 Removed MauncherAct (-2/11)
12-19 12:52:31.082  4310  4310 D Launcher: onTrimMemory. Level: 20
12-19 12:52:31.082  3010  3010 D libEGL  : eglTerminate EGLDisplay = 0x7fdb1e64b8
12-19 12:52:31.082  3010  3010 D libEGL  : eglInitialize EGLDisplay = 0x7fdb1e6398
,12-19 12:52:31.242  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:31.302  9507  9507 D AASAservice-RuleManager: IsSharedUID() : pkgname - com.test.thalitest, mSharedUserId - null
12-19 12:52:31.302  9507  9507 D AASAservice-UpdateReceiver: AASAUpdateReceiver : check SharedUID package.
12-19 12:52:31.302  9507  9507 I AASAservice-UpdateReceiver: AASAUpdateReceiver() : BLOCK BY PACKAGE
12-19 12:52:31.302  9507  9507 E AASAservice-UpdateReceiver: AASAUpdateReceiver : myrule is null.
12-19 12:52:31.302  9507  9507 I art     : System.exit called, status: 0
12-19 12:52:31.302  9507  9507 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,12-19 12:52:31.362  5854  5854 I TrayVisibilityController: handleMessage : msg.what = 1
,12-19 12:52:31.372  3421  4391 I WindowManager: Screenshot max retries 4 of Token{a1257bf ActivityRecord{74799de u0 com.test.thalitest/.MainActivity t20}} appWin=Window{274d842 u0 d0 Starting com.test.thalitest} drawState=4
,12-19 12:52:31.372  5854  5865 I TrayUsageStatesWatcher: notePauseComponent : ComponentInfo{com.test.thalitest/com.test.thalitest.MainActivity}
12-19 12:52:31.372  3421  3534 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
,12-19 12:52:31.392  3421  4417 I ActivityManager: Process com.samsung.aasaservice (pid 9507)(adj 0) has died(93,1785)
,12-19 12:52:31.392  3421  4417 D ActivityManager: isAutoRunBlockedApp:: com.samsung.aasaservice, Auto Run ON
,12-19 12:52:31.402  5854  5854 I Utils   : isCurrentUser current = 0, ownerId = 0
12-19 12:52:31.402  5854  5854 I TrayVisibilityController: getComputedTrayVisible : keyguardState = 3
12-19 12:52:31.402  5854  5854 I TrayVisibilityController: updateTrayVisible : State : 3 visible = 2 mCurrentVisible = 2
12-19 12:52:31.412  9569  9569 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
12-19 12:52:31.412  9569  9569 D RelationGraph: garbageCollect()
12-19 12:52:31.412  9569  9569 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
,12-19 12:52:31.412  3421  3534 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b3fbe6e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{212d1d3 9134:com.samsung.android.app.appsedge/u0a1}
12-19 12:52:31.422  9569  9569 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
12-19 12:52:31.422  3421  3984 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
12-19 12:52:31.422  9134  9134 I AppsEdgeBroadcastReceiver: onReceive: android.intent.action.PACKAGE_ADDED
12-19 12:52:31.422  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:31.442  9569  9569 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:31.442  9584  9584 E Zygote  : v2
12-19 12:52:31.442  9584  9584 I libpersona: KNOX_SDCARD checking this for 10017
12-19 12:52:31.442  9584  9584 I libpersona: KNOX_SDCARD not a persona
,12-19 12:52:31.442  9584  9584 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0029
,12-19 12:52:31.452  9569  9569 I InjectionManager: Inside getClassLibPath caller 
12-19 12:52:31.452  3421  4989 I ActivityManager: Start proc 9584:com.samsung.android.app.galaxylabs/u0a17 for broadcast-3 com.samsung.android.app.galaxylabs/.LabsIntentReceiver
12-19 12:52:31.452  9584  9584 E Zygote  : accessInfo : 0
12-19 12:52:31.452  9584  9584 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.app.galaxylabs 
,12-19 12:52:31.452  3421  3565 D MARsDBManager: onChange - mSmartManagerObserver! Uri = content://com.samsung.android.sm/AppFreezer?MARs-self=true&MARs=true
,12-19 12:52:31.462  3421  6150 D GameManagerService: identifyGamePackage. com.test.thalitest
12-19 12:52:31.462  3421  6150 D GameManagerService: identifyGamePackage. com.test.thalitest
,12-19 12:52:31.462  3421  3856 D NetworkPolicy: isUidForegroundLocked: 10078, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
,12-19 12:52:31.472  3421  6150 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
12-19 12:52:31.472  9569  9569 D InjectionManager: InjectionManager
,12-19 12:52:31.472  9569  9569 D InjectionManager: fillFeatureStoreMap com.test.thalitest
,12-19 12:52:31.472  9569  9569 I InjectionManager: Constructor com.test.thalitest, Feature store :{}
,12-19 12:52:31.472  9569  9569 I InjectionManager: featureStore :{}
,12-19 12:52:31.472  3421  6150 D GameManagerService: identifyGamePackage. com.test.thalitest
,12-19 12:52:31.482  9569  9569 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
,12-19 12:52:31.482  9569  9569 D RelationGraph: garbageCollect()
,12-19 12:52:31.492  3421  6150 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,12-19 12:52:31.492  9569  9569 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
,12-19 12:52:31.492  3421  6150 D GameManagerService: identifyGamePackage. com.test.thalitest
,12-19 12:52:31.492  3421  6150 D GameManagerService: identifyGamePackage. com.test.thalitest
,12-19 12:52:31.502  9584  9584 D TimaKeyStoreProvider: TimaSignature is unavailable
,12-19 12:52:31.502  9584  9584 D ActivityThread: Added TimaKeyStore provider
,12-19 12:52:31.502  9569  9569 I CordovaLog: Changing log level to DEBUG(3)
,12-19 12:52:31.502  9569  9569 I CordovaActivity: Apache Cordova native platform version 6.0.0 is starting
12-19 12:52:31.502  9569  9569 D CordovaActivity: CordovaActivity.onCreate()
,12-19 12:52:31.512  9569  9569 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310550)
,12-19 12:52:31.512  3421  3474 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b3fbe6e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{da47d90 9584:com.samsung.android.app.galaxylabs/u0a17}
,12-19 12:52:31.532  9584  9584 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,12-19 12:52:31.532  9584  9584 D RelationGraph: garbageCollect()
,12-19 12:52:31.532  9584  9584 W ResourcesManager: getTopLevelResources: /system/priv-app/GalaxyLabs/GalaxyLabs.apk / 1.0 running in com.samsung.android.app.galaxylabs rsrc of package com.samsung.android.app.galaxylabs
,12-19 12:52:31.532  3421  3981 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,12-19 12:52:31.532  9584  9584 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,12-19 12:52:31.542  9584  9584 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:31.542  9584  9584 I InjectionManager: Inside getClassLibPath caller 
,12-19 12:52:31.552  9584  9584 W System  : ClassLoader referenced unknown path: /system/priv-app/GalaxyLabs/lib/arm64
,12-19 12:52:31.552  9584  9584 D InjectionManager: InjectionManager
12-19 12:52:31.552  9584  9584 D InjectionManager: fillFeatureStoreMap com.samsung.android.app.galaxylabs
,12-19 12:52:31.552  9584  9584 I InjectionManager: Constructor com.samsung.android.app.galaxylabs, Feature store :{}
12-19 12:52:31.552  9584  9584 I InjectionManager: featureStore :{}
12-19 12:52:31.552  9584  9584 D LabsIntentReceiver: action: android.intent.action.PACKAGE_ADDED
12-19 12:52:31.552  9584  9584 D LabsIntentReceiver: pkg: com.test.thalitest
12-19 12:52:31.552  9584  9584 D LabsIntentReceiver: context: android.app.ReceiverRestrictedContext@92e8cc6
12-19 12:52:31.552  9584  9584 D LabsIntentReceiver: extra: false
,12-19 12:52:31.552  9584  9584 D LabsLoader: loadByPackageName: deleteDB com.test.thalitest
,12-19 12:52:31.562  9569  9569 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package com.google.android.webview
12-19 12:52:31.562  9569  9569 D ResourcesManager: For user 0 new overlays fetched Null
12-19 12:52:31.562  9569  9569 I InjectionManager: Inside getClassLibPath caller 
12-19 12:52:31.562  4310  4310 D LauncherApplication: galaxy labs setting changed!!!
12-19 12:52:31.562  9569  9569 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
12-19 12:52:31.572  3421  4421 I ActivityManager: Killing 9037:com.sec.spp.push:RemoteNotiProcess/u0a42 (adj 15): DHA:empty #33
12-19 12:52:31.572  3421  4421 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b3fbe6e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4ade0f0 4335:com.google.android.gms.persistent/u0a21}
,12-19 12:52:31.602  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:31.602  9569  9569 I cr_LibraryLoader: Time to load native libraries: 19 ms (timestamps 7452-7471)
12-19 12:52:31.602  9569  9569 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
,12-19 12:52:31.612  3421  3984 D ActivityManager: isAutoRunBlockedApp:: com.sec.spp.push, Auto Run ON
,12-19 12:52:31.632  3421  3474 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b3fbe6e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8344b65 4637:com.google.android.gms/u0a21}
,12-19 12:52:31.632  9569  9600 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,12-19 12:52:31.642  4310  4310 D LauncherApplication: galaxy labs cursor count is 0
,12-19 12:52:31.642  3421  3882 D MdnieScenarioControlService:  packageName : com.test.thalitest    className : com.test.thalitest.MainActivity
,12-19 12:52:31.652  9569  9569 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {8a30e55}
12-19 12:52:31.652  9569  9569 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
12-19 12:52:31.652  3421  4417 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b3fbe6e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8344b65 4637:com.google.android.gms/u0a21}
,12-19 12:52:31.662  4637  4637 D AsyncTaskServiceImpl: Submit a task: k
,12-19 12:52:31.672  9569  9569 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
,12-19 12:52:31.682  4637  9601 D k       : Processing package: com.test.thalitest
,12-19 12:52:31.692  3421  3983 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b3fbe6e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8344b65 4637:com.google.android.gms/u0a21}
12-19 12:52:31.692  4637  9601 D GassUtils: Found app info for package com.test.thalitest:10000. Hash: 99c4c6a4ac1409a0c1eab18ffe67fa037e034f91d8588365b3d8c1f353531711
12-19 12:52:31.692  4637  9601 D k       : Found info for package com.test.thalitest in db.
,12-19 12:52:31.712  9569  9569 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,12-19 12:52:31.712  3421  4417 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b3fbe6e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8344b65 4637:com.google.android.gms/u0a21}
,12-19 12:52:31.742  3421  4417 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b3fbe6e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4ade0f0 4335:com.google.android.gms.persistent/u0a21}
,12-19 12:52:31.742  3421  3882 I MdnieScenarioControlService: mGameModeLauncher : false
12-19 12:52:31.742  3421  3882 I MdnieScenarioControlService: setUIMode
,12-19 12:52:31.742  4637  9598 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,12-19 12:52:31.762  3421  4415 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b3fbe6e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4ade0f0 4335:com.google.android.gms.persistent/u0a21}
,12-19 12:52:31.782  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:31.782  4637  9609 I PeopleContactsSync: triggerPendingContactsCleanup: no accounts
,12-19 12:52:31.792  3421  3983 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity newState = 1 callingPackage = 10021
,12-19 12:52:31.792  9610  9610 E Zygote  : v2
12-19 12:52:31.792  9610  9610 I libpersona: KNOX_SDCARD checking this for 10025
12-19 12:52:31.792  9610  9610 I libpersona: KNOX_SDCARD not a persona
,12-19 12:52:31.792  9610  9610 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0029
,12-19 12:52:31.792  3421  4415 I ActivityManager: Start proc 9610:com.google.android.partnersetup/u0a25 for broadcast-3 com.google.android.partnersetup/.RlzPingBroadcastReceiver
12-19 12:52:31.792  9610  9610 E Zygote  : accessInfo : 0
12-19 12:52:31.792  9610  9610 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.partnersetup 
,12-19 12:52:31.832  9610  9610 D TimaKeyStoreProvider: TimaSignature is unavailable
12-19 12:52:31.832  9610  9610 D ActivityThread: Added TimaKeyStore provider
,12-19 12:52:31.832  9569  9569 D libEGL  : eglInitialize EGLDisplay = 0xff93edbc
,12-19 12:52:31.832  4637  9598 D WearableController: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,12-19 12:52:31.852  3421  4182 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b3fbe6e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f620443 9610:com.google.android.partnersetup/u0a25}
,12-19 12:52:31.862  9610  9610 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,12-19 12:52:31.862  9610  9610 D RelationGraph: garbageCollect()
,12-19 12:52:31.872  9610  9610 W ResourcesManager: getTopLevelResources: /system/priv-app/GooglePartnerSetup/GooglePartnerSetup.apk / 1.0 running in com.google.android.partnersetup rsrc of package com.google.android.partnersetup
,12-19 12:52:31.882  3421  3534 W ActivityManager: Activity pause timeout for ActivityRecord{74799de u0 com.test.thalitest/.MainActivity t20}
,12-19 12:52:31.882  3421  4616 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,12-19 12:52:31.882  9610  9610 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,12-19 12:52:31.882  9610  9610 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:31.892  9610  9610 I InjectionManager: Inside getClassLibPath caller 
,12-19 12:52:31.902  9610  9610 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePartnerSetup/lib/arm64
,12-19 12:52:31.912  3421  3472 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10078
12-19 12:52:31.912  3421  3472 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29734 com.android.server.am.ActivityManagerService.registerReceiver:22599 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,12-19 12:52:31.932  9610  9610 D InjectionManager: InjectionManager
12-19 12:52:31.932  9610  9610 D InjectionManager: fillFeatureStoreMap com.google.android.partnersetup
,12-19 12:52:31.942  9610  9610 I InjectionManager: Constructor com.google.android.partnersetup, Feature store :{}
12-19 12:52:31.942  9610  9610 I InjectionManager: featureStore :{}
,12-19 12:52:31.962  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:31.972  9569  9569 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,12-19 12:52:31.972  3421  3981 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b3fbe6e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f620443 9610:com.google.android.partnersetup/u0a25}
,12-19 12:52:31.982  9569  9569 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,12-19 12:52:31.982  9569  9569 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,12-19 12:52:32.002  9569  9569 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,12-19 12:52:32.012  3421  4989 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b3fbe6e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{470760e 9151:com.android.vending/u0a35}
,12-19 12:52:32.012  4166  4177 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg com.android.vending,id=1003285959,extra=Bundle[mParcelledData.dataSize=84]
12-19 12:52:32.012  4166  4166 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=1003285959, samsung.notification.type=normal, samsung.people.package_name=com.android.vending}]
,12-19 12:52:32.012  4166  4166 I PeopleStripeService: PeopleNotificationReceiver:3
12-19 12:52:32.012  4166  4166 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
12-19 12:52:32.012  4166  4166 I PeopleDataManager: removeNotification
12-19 12:52:32.012  4166  4166 I NotificationParser: getNotiType:com.android.vending,null
12-19 12:52:32.012  4166  4166 D PeopleDataManager: removeNotiInfo: id =1003285959,packageName=com.android.vending,isEdgeNotification=false,key=null,removeAll=false
12-19 12:52:32.012  4166  4166 D PeopleDataManager: removeNotiInfo =null
,12-19 12:52:32.022  9569  9569 D PluginManager: init()
,12-19 12:52:32.022  9569  9569 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,12-19 12:52:32.042  9569  9569 D Activity: performCreate Call Injection manager
,12-19 12:52:32.052  9151  9151 I Finsky  : [1] com.google.android.finsky.utils.PermissionPolicies$PermissionPolicyService.onStartCommand(117): post-install permissions check for com.test.thalitest
,12-19 12:52:32.052  9151  9151 W Finsky  : [1] com.google.android.finsky.FinskyApp.i(1379): No account configured on this device.
,12-19 12:52:32.062  9660  9660 E Zygote  : v2
12-19 12:52:32.062  9660  9660 I libpersona: KNOX_SDCARD checking this for 10177
12-19 12:52:32.062  9660  9660 I libpersona: KNOX_SDCARD not a persona
,12-19 12:52:32.062  9660  9660 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0029
,12-19 12:52:32.062  3421  3984 I ActivityManager: Start proc 9660:com.samsung.android.asksmanager/u0a177 for broadcast-3 com.samsung.android.asksmanager/.PackageReceiver
,12-19 12:52:32.062  9660  9660 E Zygote  : accessInfo : 0
12-19 12:52:32.062  9660  9660 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.asksmanager 
,12-19 12:52:32.072  9569  9569 D CordovaActivity: Started the activity.
12-19 12:52:32.072  9569  9569 I InjectionManager: dispatchOnViewCreated > Target : com.test.thalitest.MainActivity isFragment :false
12-19 12:52:32.072  9569  9569 D CordovaActivity: Resumed the activity.
,12-19 12:52:32.072  9151  9151 I Finsky  : [1] com.google.android.finsky.utils.bc.run(2302): Package state data is missing for com.test.thalitest
,12-19 12:52:32.082  9151  9151 W Finsky  : [1] com.google.android.finsky.FinskyApp.i(1379): No account configured on this device.
12-19 12:52:32.082  9569  9569 D SecWifiDisplayUtil: Metadata value : SecSettings2
,12-19 12:52:32.082  9569  9569 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{7a29058 I.E...... R.....ID 0,0-0,0}
,12-19 12:52:32.092  9569  9672 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,12-19 12:52:32.102  3421  3853 W WindowManager: Failed looking up window
12-19 12:52:32.102  3421  3853 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@d14411 does not exist
12-19 12:52:32.102  3421  3853 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14805)
12-19 12:52:32.102  3421  3853 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
12-19 12:52:32.102  3421  3853 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
12-19 12:52:32.102  3421  3853 W WindowManager: 	at android.view.IWindowSession$Stub.onTransact(IWindowSession.java:688)
12-19 12:52:32.102  3421  3853 W WindowManager: 	at com.android.server.wm.Session.onTransact(Session.java:139)
12-19 12:52:32.102  3421  3853 W WindowManager: 	at android.os.Binder.execTransact(Binder.java:453)
,12-19 12:52:32.102  3421  4570 D ISSUE_DEBUG: InputChannelName : 1fd5976 com.test.thalitest/com.test.thalitest.MainActivity
,12-19 12:52:32.102  3421  3983 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
12-19 12:52:32.102  3421  3983 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
12-19 12:52:32.102  9660  9660 D TimaKeyStoreProvider: TimaSignature is unavailable
12-19 12:52:32.102  9660  9660 D ActivityThread: Added TimaKeyStore provider
12-19 12:52:32.102  3421  3421 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
12-19 12:52:32.102  9569  9569 D CordovaActivity: Paused the activity.
,12-19 12:52:32.102  3421  3421 I KnoxTimeoutHandler: Shared devices show user statefalse
,12-19 12:52:32.112  3421  4989 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b3fbe6e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{45d9702 9660:com.samsung.android.asksmanager/u0a177}
12-19 12:52:32.122  9569  9569 V ActivityThread: updateVisibility : ActivityRecord{80e3a96 token=android.os.BinderProxy@cb06ae0 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
12-19 12:52:32.122  9569  9569 D CordovaActivity: Stopped the activity.
,12-19 12:52:32.122  9660  9660 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,12-19 12:52:32.122  9660  9660 D RelationGraph: garbageCollect()
,12-19 12:52:32.132  9569  9600 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
12-19 12:52:32.132  9660  9660 W ResourcesManager: getTopLevelResources: /system/priv-app/ASKSManager/ASKSManager.apk / 1.0 running in com.samsung.android.asksmanager rsrc of package com.samsung.android.asksmanager
12-19 12:52:32.132  3421  4333 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
12-19 12:52:32.132  9660  9660 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
12-19 12:52:32.132  9660  9660 D ResourcesManager: For user 0 new overlays fetched Null
12-19 12:52:32.132  9660  9660 I InjectionManager: Inside getClassLibPath caller 
,12-19 12:52:32.142  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:32.142  9660  9660 W System  : ClassLoader referenced unknown path: /system/priv-app/ASKSManager/lib/arm64
,12-19 12:52:32.142  9569  9569 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10078, CallingPid : 9569
,12-19 12:52:32.142  9660  9660 D InjectionManager: InjectionManager
,12-19 12:52:32.142  9660  9660 D InjectionManager: fillFeatureStoreMap com.samsung.android.asksmanager
12-19 12:52:32.142  9660  9660 I InjectionManager: Constructor com.samsung.android.asksmanager, Feature store :{}
12-19 12:52:32.142  9660  9660 I InjectionManager: featureStore :{}
,12-19 12:52:32.142  3421  4417 D ConnectivityService: listenForNetwork for Listen from uid/pid:10078/9569 for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,12-19 12:52:32.152  3421  3867 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,12-19 12:52:32.152  3421  3867 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -42]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,12-19 12:52:32.152  3421  3867 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,12-19 12:52:32.152  3421  4989 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b3fbe6e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2565e6c 9199:com.sec.android.app.shealth:remote/u0a39}
,12-19 12:52:32.162  3421  3867 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,12-19 12:52:32.162  3421  3867 D ConnectivityService:   checking if request is: NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,12-19 12:52:32.162  3421  4616 I ActivityManager: Killing 9053:com.sec.android.Kies/1000 (adj 15): DHA:empty #33
,12-19 12:52:32.162  3421  3867 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,12-19 12:52:32.172  3421  3867 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,12-19 12:52:32.182  9569  9569 D SecWifiDisplayUtil: Metadata value : SecSettings2
,12-19 12:52:32.192  9676  9676 E Zygote  : v2
12-19 12:52:32.192  9676  9676 I libpersona: KNOX_SDCARD checking this for 10043
12-19 12:52:32.192  9676  9676 I libpersona: KNOX_SDCARD not a persona
,12-19 12:52:32.192  9676  9676 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0029
,12-19 12:52:32.192  9676  9676 E Zygote  : accessInfo : 0
12-19 12:52:32.192  9676  9676 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.voiceserviceplatform 
,12-19 12:52:32.192  3421  3867 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,12-19 12:52:32.192  3421  3867 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,12-19 12:52:32.192  3010  3010 I SurfaceFlinger: id=21 createSurf (1x1),1 flag=404, NainActivit
,12-19 12:52:32.202  3421  4415 I ActivityManager: Start proc 9676:com.samsung.voiceserviceplatform/u0a43 for broadcast-3 com.samsung.voiceserviceplatform/com.samsung.vsf.sharedlib.utils.TTSPlayer$TTSDownloadReceiver
,12-19 12:52:32.202  3421  4415 I ActivityManager: Killing 8824:com.samsung.android.scloud:contentsync/5009 (adj 15): DHA:empty #33
,12-19 12:52:32.212  3421  4570 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.Kies, Auto Run ON
,12-19 12:52:32.222  9676  9676 D TimaKeyStoreProvider: TimaSignature is unavailable
12-19 12:52:32.222  9676  9676 D ActivityThread: Added TimaKeyStore provider
,12-19 12:52:32.222  9569  9672 D libEGL  : eglInitialize EGLDisplay = 0xdd2ff7c4
12-19 12:52:32.222  9569  9672 I OpenGLRenderer: Initialized EGL, version 1.4
,12-19 12:52:32.232  9569  9672 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,12-19 12:52:32.232  3421  3984 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b3fbe6e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{492214e 9676:com.samsung.voiceserviceplatform/u0a43}
12-19 12:52:32.232  3421  4415 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3421
12-19 12:52:32.232  3421  4415 I libsuspend: !@autosuspend_wakeup_count_disable
12-19 12:52:32.232  3421  4415 D PowerManagerService: mDisplayReady: false
12-19 12:52:32.232  3421  4415 I libsuspend: !@autosuspend_wakeup_count_disable done
12-19 12:52:32.232  3421  3574 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-19 12:52:32.232  3421  4415 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
12-19 12:52:32.232  3421  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-19 12:52:32.232  3421  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-19 12:52:32.232  3421  3574 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-19 12:52:32.232  3421  3586 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
,12-19 12:52:32.232  3421  3570 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
12-19 12:52:32.232  3421  3570 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
12-19 12:52:32.232  3010  3010 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fa2c03c00
12-19 12:52:32.232  3010  3010 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
,12-19 12:52:32.252  3421  3574 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-19 12:52:32.252  3421  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-19 12:52:32.252  3421  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-19 12:52:32.252  3421  3574 I libsuspend: !@autosuspend_wakeup_count_enable
12-19 12:52:32.252  3421  3574 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-19 12:52:32.252  3421  3574 I libsuspend: !@autosuspend_wakeup_count_enable done
12-19 12:52:32.252  3421  3574 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-19 12:52:32.252  3421  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-19 12:52:32.252  3421  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-19 12:52:32.252  3421  3574 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-19 12:52:32.252  3421  3574 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
12-19 12:52:32.252  3421  3574 D PowerManagerService: mDisplayReady: true
12-19 12:52:32.252  3421  3574 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,12-19 12:52:32.252  5854  5854 E CocktailBarPositionManager: Window direction: 0
12-19 12:52:32.252  5854  5854 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,12-19 12:52:32.252  3421  4616 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.scloud, Auto Run ON
,12-19 12:52:32.272  9676  9676 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,12-19 12:52:32.272  9676  9676 D RelationGraph: garbageCollect()
,12-19 12:52:32.272  9569  9569 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,12-19 12:52:32.272  9676  9676 W ResourcesManager: getTopLevelResources: /system/priv-app/SVoice_1.0/SVoice_1.0.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.samsung.voiceserviceplatform
,12-19 12:52:32.272  3421  3981 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,12-19 12:52:32.272  9569  9688 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
12-19 12:52:32.272  9569  9688 D libEGL  : eglInitialize EGLDisplay = 0xdb9bf3f4
12-19 12:52:32.272  9676  9676 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,12-19 12:52:32.282  9676  9676 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:32.282  9676  9676 I InjectionManager: Inside getClassLibPath caller 
,12-19 12:52:32.282  3421  4421 V WindowStateAnimator: Finishing drawing window Window{1fd5976 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,12-19 12:52:32.282  9569  9569 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
,12-19 12:52:32.292  3421  3853 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3421
,12-19 12:52:32.292  3421  3570 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
12-19 12:52:32.292  3421  3421 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
12-19 12:52:32.292  9569  9688 D libGLESv2: DTS_GLAPI : DTS is not allowed for Package : com.test.thalitest
12-19 12:52:32.292  3421  3570 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +915ms (total +1s339ms)
,12-19 12:52:32.292  3421  3570 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{74799de u0 com.test.thalitest/.MainActivity t20} time:58166
12-19 12:52:32.292  3421  3570 D ActivityManager: mDVFSHelper.release()
12-19 12:52:32.292  3421  3570 D ViewRootImpl: #3 mView = null
12-19 12:52:32.292  3421  3421 I KnoxTimeoutHandler: SD activityfalse
12-19 12:52:32.292  3010  4490 I SurfaceFlinger: id=20 Removed uhalitest (6/11)
,12-19 12:52:32.292  3010  4490 I SurfaceFlinger: id=20 Removed uhalitest (-2/11)
,12-19 12:52:32.302  3421  4989 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3421
,12-19 12:52:32.302  3010  3010 D libEGL  : eglTerminate EGLDisplay = 0x7fdb1e64b8
,12-19 12:52:32.312  3421  4182 V WindowStateAnimator: Finishing drawing window Window{1fd5976 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
,12-19 12:52:32.312  9569  9569 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
,12-19 12:52:32.312  9569  9569 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@cb06ae0 time:58186
,12-19 12:52:32.322  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:32.332  9569  9569 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9569
,12-19 12:52:32.362  9676  9676 I BNRClientProivder, VERSION : 1.7.8: register - started.
,12-19 12:52:32.422  9676  9676 I BNRClientProivder, VERSION : 1.7.8: register - xml6 quick_backup : SVOICESETTING, bLEmzxKOex, com.samsung.voiceserviceplatform.SCloudBackUp
,12-19 12:52:32.432  9676  9676 I QBNRClientHelper: init SyncClientHelper : SVOICESETTING
,12-19 12:52:32.432  9676  9676 I l       : :main:VSP::S Voice language is null. Set to System Locale
12-19 12:52:32.442  9676  9676 I l       : :main:VSP::setLocale locale : pl_PL
12-19 12:52:32.442  9676  9676 W ResourcesManager: getTopLevelResources: /system/priv-app/SVoice_1.0/SVoice_1.0.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.samsung.voiceserviceplatform
,12-19 12:52:32.442  9676  9676 D ResourcesManager: For user 0 new overlays fetched Null
12-19 12:52:32.442  9676  9676 I QuickDialApplication: :main:VSP::QuickDialApplication Started ver:1.9.35-130 (193502130
,12-19 12:52:32.442  9676  9676 I VoiceServicePlatformApp:main:  : VSP::SvoiceApp Oncreate()
,12-19 12:52:32.452  3421  3421 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3421 (0x0)
12-19 12:52:32.452  3421  3421 D PowerManagerService: mDisplayReady: false
12-19 12:52:32.452  3421  3421 I libsuspend: !@autosuspend_wakeup_count_disable
12-19 12:52:32.452  3421  3574 D DisplayPowerController: animateScreenStateChange[0]: target=4
12-19 12:52:32.452  3421  3421 I libsuspend: !@autosuspend_wakeup_count_disable done
12-19 12:52:32.452  3421  3421 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
12-19 12:52:32.452  3421  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-19 12:52:32.452  3421  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-19 12:52:32.452  3421  3574 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-19 12:52:32.452  3421  3586 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
,12-19 12:52:32.452  3010  3010 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7fa2c03c00
12-19 12:52:32.452  3421  3570 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
12-19 12:52:32.452  3010  3010 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
12-19 12:52:32.452  3421  3570 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
,12-19 12:52:32.452  3421  6151 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
,12-19 12:52:32.462  3421  3574 D DisplayPowerController: animateScreenStateChange[0]: target=4
12-19 12:52:32.462  3421  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-19 12:52:32.462  3421  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
,12-19 12:52:32.462  3421  3574 I libsuspend: !@autosuspend_wakeup_count_enable
12-19 12:52:32.462  3421  3574 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-19 12:52:32.462  3421  3574 I libsuspend: !@autosuspend_wakeup_count_enable done
12-19 12:52:32.462  3421  3574 D DisplayPowerController: animateScreenStateChange[0]: target=4
12-19 12:52:32.462  3421  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
,12-19 12:52:32.462  3421  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-19 12:52:32.462  3421  3574 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-19 12:52:32.462  3421  3574 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
12-19 12:52:32.462  3421  3574 D PowerManagerService: mDisplayReady: true
12-19 12:52:32.462  3421  3574 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,12-19 12:52:32.472  5854  5854 E CocktailBarPositionManager: Window direction: 0
,12-19 12:52:32.472  5854  5854 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,12-19 12:52:32.472  9676  9676 I AppSessionManager:main:  : VSP::init() Update from sharedpref
12-19 12:52:32.472  9676  9676 I AppSessionManager:main:  : VSP::init() Update from sharedpref
,12-19 12:52:32.472  9569  9569 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,12-19 12:52:32.482  9697  9697 E Zygote  : v2
12-19 12:52:32.482  9697  9697 I libpersona: KNOX_SDCARD checking this for 10043
12-19 12:52:32.482  9697  9697 I libpersona: KNOX_SDCARD not a persona
,12-19 12:52:32.482  9697  9697 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0029
,12-19 12:52:32.482  9697  9697 E Zygote  : accessInfo : 0
12-19 12:52:32.482  9697  9697 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.svoice.sync 
,12-19 12:52:32.492  3421  4616 I ActivityManager: Start proc 9697:com.samsung.svoice.sync/u0a43 for content provider com.samsung.svoice.sync/com.svoice.upload.database.PLMProvider
,12-19 12:52:32.492  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:32.502  9697  9697 D TimaKeyStoreProvider: TimaSignature is unavailable
12-19 12:52:32.502  9697  9697 D ActivityThread: Added TimaKeyStore provider
,12-19 12:52:32.522  9697  9697 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
12-19 12:52:32.522  9697  9697 D RelationGraph: garbageCollect()
,12-19 12:52:32.522  9697  9697 W ResourcesManager: getTopLevelResources: /system/priv-app/SVoicePLM_1.0/SVoicePLM_1.0.apk / 1.0 running in com.samsung.svoice.sync rsrc of package com.samsung.svoice.sync
,12-19 12:52:32.522  3421  3983 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
12-19 12:52:32.522  9697  9697 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,12-19 12:52:32.522  9697  9697 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:32.522  9697  9697 I InjectionManager: Inside getClassLibPath caller 
,12-19 12:52:32.532  9697  9697 I UploadDatabase: svoicelocal DB: main : PLM :: mUploadDBManager is null , creating new one !! 
,12-19 12:52:32.542  9569  9709 D jxcore_app_log: JniHelper::setJavaVM(0xf4fb4000), pthread_self() = -644875984
,12-19 12:52:32.542  9697  9697 E SQLiteLog: (5) statement aborts at 2: [PRAGMA journal_mode=PERSIST] 
,12-19 12:52:32.542  9697  9697 W SQLiteConnection: Could not change the database journal mode of '/data/user/0/com.samsung.svoice.sync/databases/svoicelocal.db' from 'wal' to 'PERSIST' because the database is locked.  This usually means that there are other open connections to the database which prevents the database from enabling or disabling write-ahead logging mode.  Proceeding without changing the journal mode.
,12-19 12:52:32.542  9569  9569 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,12-19 12:52:32.552  9697  9697 D InjectionManager: InjectionManager
,12-19 12:52:32.552  9697  9697 D InjectionManager: fillFeatureStoreMap com.samsung.svoice.sync
12-19 12:52:32.552  9697  9697 I InjectionManager: Constructor com.samsung.svoice.sync, Feature store :{}
12-19 12:52:32.552  9697  9697 I InjectionManager: featureStore :{}
,12-19 12:52:32.552  9569  9569 D SystemWebChromeClient: file:///android_asset/www/js/index.js: Line 36 : Uncaught TypeError: Cannot read property 'querySelector' of null
,12-19 12:52:32.552  9697  9707 D PLMProvider: match for uri : content://com.samsung.svoice.sync/tos_accepted is : 8
12-19 12:52:32.552  9569  9569 I chromium: [INFO:CONSOLE(36)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (36)
,12-19 12:52:32.562  9676  9676 I SVFSettings:main:  : VSP::inside updateAppLocale() en_US
,12-19 12:52:32.562  9676  9676 I SVFSettings:main:  : VSP::Current locale string in updateAppLocale method en-US
,12-19 12:52:32.562  9676  9676 I SVFSettings:main:  : VSP::After updateing N66_ComamndHandler current locale is en-US
,12-19 12:52:32.572  9676  9676 D DeviceInfo: DeviceInfo
,12-19 12:52:32.572  9676  9676 D DeviceInfo: getLocale =  en-US
12-19 12:52:32.572  9676  9676 I N66_CommonHandler:main:  : VSP:: locale info at present in updateServerBasedOnlanguage : en-US
12-19 12:52:32.572  9676  9676 I N66_CommonHandler:main:  : VSP::Current configured server is interaction-us2.samsung-svoice.com
12-19 12:52:32.572  9676  9676 I N66_CommonHandler:main:  : VSP::Current configured server port is 443
,12-19 12:52:32.592  9676  9676 D SettingsValueDB:main:  : VSP:: match for uri : content://com.samsung.voiceserviceplatform.database.SettingsValueDB/SettingsvalueTb is : -1
12-19 12:52:32.592  9676  9676 D SettingsValueDB:main:  : VSP::URI didnt match
,12-19 12:52:32.592  9676  9676 D SettingsValueDB:main:  : VSP:: match for uri : content://com.samsung.voiceserviceplatform.database.SettingsValueDB/SettingsvalueTb is : -1
12-19 12:52:32.592  9676  9676 D SettingsValueDB:main:  : VSP::URI didnt match
,12-19 12:52:32.592  9676  9676 D SettingsValueDB:main:  : VSP:: match for uri : content://com.samsung.voiceserviceplatform.database.SettingsValueDB/language is : 3
12-19 12:52:32.592  9676  9676 D SettingsValueDB:main:  : VSP::lang from content values is  en_US
12-19 12:52:32.592  9676  9676 I skwskw:main:  : VSP::############################122 value : en_US
,12-19 12:52:32.592  9697  9708 D PLMProvider: match for uri : content://com.samsung.svoice.sync/tos_accepted is : 8
,12-19 12:52:32.592  9676  9676 I N66_CommonHandler:main:  : VSP:: rowUpdated : 1
,12-19 12:52:32.602  9676  9676 D SVFSettings: updateServerBasedOnLang() connect to server US_PROD2_SERVER_HOST_IP
12-19 12:52:32.602  9676  9676 D p       : :main:VSP::setTargetServerAddress() : interaction-us2.samsung-svoice.com
12-19 12:52:32.602  9676  9676 D p       : :main:VSP::setTargetServerPort() : 443
,12-19 12:52:32.632  9676  9676 W ResourcesManager: getTopLevelResources: /system/app/SamsungTTS/SamsungTTS.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.samsung.SMT
,12-19 12:52:32.632  9676  9676 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:32.632  9676  9676 W ResourcesManager: getTopLevelResources: /system/app/GoogleTTS/GoogleTTS.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.tts
,12-19 12:52:32.632  9676  9676 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:32.642  9714  9714 E Zygote  : v2
12-19 12:52:32.642  9714  9714 I libpersona: KNOX_SDCARD checking this for 1000
12-19 12:52:32.642  9714  9714 I libpersona: KNOX_SDCARD not a persona
,12-19 12:52:32.642  9714  9714 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0029
,12-19 12:52:32.642  9714  9714 E Zygote  : accessInfo : 0
,12-19 12:52:32.652  3421  3981 I ActivityManager: Start proc 9714:com.samsung.SMT/1000 for service com.samsung.SMT/.SamsungTTSService
,12-19 12:52:32.652  9676  9676 I TextToSpeech: Sucessfully bound to com.samsung.SMT
12-19 12:52:32.652  9676  9676 D Test    : Creating TTS instance!
,12-19 12:52:32.662  9714  9714 D TimaKeyStoreProvider: TimaSignature is unavailable
12-19 12:52:32.662  9714  9714 D ActivityThread: Added TimaKeyStore provider
,12-19 12:52:32.662  9676  9676 I SamsungHTTPClient:main:  : VSP::MY THREAD ID UI : 1
,12-19 12:52:32.672  9697  9708 D PLMProvider: match for uri : content://com.samsung.svoice.sync/device_id is : 1
,12-19 12:52:32.672  9697  9708 D PLMDeviceInfo: Binder_2 : PLM ::Device Id generation is complete
,12-19 12:52:32.672  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:32.682  9676  9676 I svoiceapi_jar: RELEASE_DATE 2016 May 25
12-19 12:52:32.682  9714  9714 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
12-19 12:52:32.682  9676  9676 I svoiceapi_jar: RELEASE_VER  0.99_26_1_TCP_Prepare2_TTS
12-19 12:52:32.682  9676  9676 I svoiceapi_jar: Loading svoice dll
12-19 12:52:32.682  9714  9714 D RelationGraph: garbageCollect()
,12-19 12:52:32.682  9714  9714 W ResourcesManager: getTopLevelResources: /system/app/SamsungTTS/SamsungTTS.apk / 1.0 running in com.samsung.SMT rsrc of package com.samsung.SMT
,12-19 12:52:32.682  9714  9714 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
12-19 12:52:32.682  3421  4989 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
12-19 12:52:32.682  9714  9714 I InjectionManager: Inside getClassLibPath caller 
12-19 12:52:32.682  9714  9714 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:32.692  9714  9714 W System  : ClassLoader referenced unknown path: /system/app/SamsungTTS/lib/arm64
,12-19 12:52:32.692  9714  9714 D InjectionManager: InjectionManager
12-19 12:52:32.692  9714  9714 D InjectionManager: fillFeatureStoreMap com.samsung.SMT
12-19 12:52:32.692  9714  9714 I InjectionManager: Constructor com.samsung.SMT, Feature store :{}
12-19 12:52:32.692  9714  9714 I InjectionManager: featureStore :{}
,12-19 12:52:32.712  9676  9676 I svoiceapi_jar: Loading success
,12-19 12:52:32.732  9676  9676 I svoiceapi: SVoiceSession Release Date : 2016 May 25
12-19 12:52:32.732  9676  9676 I svoiceapi: Library Ver : 0.99_26_1_TCP_Prepare2_TTS
12-19 12:52:32.732  9676  9676 I svoiceapi: SVoiceSession::SVoiceSession, Default loglevel = 5
12-19 12:52:32.732  9676  9676 I svoiceapi: create handle : 0xf4f32a00
12-19 12:52:32.732  9676  9676 I svoiceapi: Sentinel registered : -185249088
12-19 12:52:32.732  9676  9676 I svoiceapi: SVoiceSession::Enable logs, loglevel = 4
12-19 12:52:32.732  9676  9676 I sessionThread:main:  : VSP::LOG_LEVEL is set as 4
,12-19 12:52:32.732  9676  9676 D ClientSDKManager : initNLUResponseList
12-19 12:52:32.732  9676  9676 D InjectionManager: InjectionManager
12-19 12:52:32.732  9676  9676 D InjectionManager: fillFeatureStoreMap com.samsung.voiceserviceplatform
,12-19 12:52:32.732  9676  9676 I InjectionManager: Constructor com.samsung.voiceserviceplatform, Feature store :{}
12-19 12:52:32.732  9676  9676 I InjectionManager: featureStore :{}
12-19 12:52:32.732  9676  9676 I SV_TTSPlayer: inside TTSDownloadReceiver
,12-19 12:52:32.732  9676  9733 I sessionThread: DEBUG : SDK : Session Thread run got called : 
12-19 12:52:32.732  9676  9733 I sessionThread:SessionThread:  : VSP::Inside processTask while loop; task is empty so sleeping : 
,12-19 12:52:32.742  9676  9676 I VoiceFrameworkService:main:  : VSP::Oncreate() of Service
12-19 12:52:32.742  9676  9676 I VoiceFrameworkServiceHandler:main:  : VSP::VoiceFrameworkServiceHandler() Start
12-19 12:52:32.742  9676  9676 I VoiceFrameworkServiceHandler:main:  : VSP::MyHandlerThread
12-19 12:52:32.742  9676  9676 I VoiceFrameworkServiceHandler:main:  : VSP::VoiceFrameworkServiceHandler() end
,12-19 12:52:32.742  9676  9734 I VoiceFrameworkServiceHandler:VoiceFrameworkServiceHandler MyHandlerThread:  : VSP::MyHandlerThread run
,12-19 12:52:32.792  3421  4570 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b3fbe6e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d4cfcac 4400:android.process.acore/u0a5}
,12-19 12:52:32.792  9676  9676 I VoiceFrameworkServiceHandler:main:  : VSP::sendMessagetoHandler Rcvd msgCode = 0
12-19 12:52:32.792  9676  9676 I VoiceFrameworkServiceHandler:main:  : VSP::sendMessagetoHandler mHandler = Handler (com.samsung.vsf.core.framework.VoiceFrameworkServiceHandler$MyHandlerThread$1) {689306a}
12-19 12:52:32.792  9676  9676 I VoiceFrameworkServiceHandler:main:  : VSP:: sendMessagetoHandler() VSF Thread isAlive : true
12-19 12:52:32.792  9676  9676 I VoiceFrameworkServiceHandler:main:  : VSP::mHandler is not null msgCode =0
12-19 12:52:32.792  9676  9734 I VoiceFrameworkServiceHandler:VoiceFrameworkServiceHandler MyHandlerThread:  : VSP::MSG_VSF_INIT Rcvd
12-19 12:52:32.792  9676  9734 I VoiceFrameworkServiceHandler:VoiceFrameworkServiceHandler MyHandlerThread:  : VSP::VSFInit()
12-19 12:52:32.792  9676  9734 I VoiceServicePlatformSdk:VoiceFrameworkServiceHandler MyHandlerThread:  : VSP::Oncreate()
,12-19 12:52:32.802  9676  9734 I SessionRuntime:VoiceFrameworkServiceHandler MyHandlerThread:  : VSP::Current Network State is same as previous, so ignoring
,12-19 12:52:32.812  9697  9707 D PLMProvider: match for uri : content://com.samsung.svoice.sync/tos_accepted is : 8
,12-19 12:52:32.812  9676  9734 I System.out: SVoiceProfiling : time taken to finish oncreate : 27
,12-19 12:52:32.822  9735  9735 E Zygote  : v2
12-19 12:52:32.822  9735  9735 I libpersona: KNOX_SDCARD checking this for 1000
12-19 12:52:32.822  9735  9735 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0029
12-19 12:52:32.822  9735  9735 I libpersona: KNOX_SDCARD not a persona
,12-19 12:52:32.822  9735  9735 E Zygote  : accessInfo : 0
,12-19 12:52:32.822  3421  4570 I ActivityManager: Start proc 9735:com.android.settings/1000 for broadcast-3 com.android.settings/.applock.PackageActionReceiver
,12-19 12:52:32.832  9676  9734 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'void android.location.LocationManager.requestLocationUpdates(long, float, android.location.Criteria, android.location.LocationListener, android.os.Looper)' on a null object reference
,12-19 12:52:32.832  9676  9734 W System.err: 	at com.samsung.vsf.core.framework.SessionRuntime.requestLocationUpdate(SessionRuntime.java:336)
12-19 12:52:32.832  9676  9734 W System.err: 	at com.samsung.vsf.core.framework.SessionRuntime.registerNetworkReceiver(SessionRuntime.java:246)
12-19 12:52:32.832  9676  9734 W System.err: 	at com.samsung.vsf.core.framework.SessionRuntime.registerBroadcastReceivers(SessionRuntime.java:115)
12-19 12:52:32.832  9676  9734 W System.err: 	at com.samsung.vsf.core.framework.SessionRuntime.init(SessionRuntime.java:103)
12-19 12:52:32.832  9676  9734 W System.err: 	at com.samsung.vsf.core.framework.VoiceFrameworkServiceHandler.VSFInit(VoiceFrameworkServiceHandler.java:188)
12-19 12:52:32.832  9676  9734 W System.err: 	at com.samsung.vsf.core.framework.VoiceFrameworkServiceHandler.access$200(VoiceFrameworkServiceHandler.java:27)
12-19 12:52:32.832  9676  9734 W System.err: 	at com.samsung.vsf.core.framework.VoiceFrameworkServiceHandler$MyHandlerThread$1.handleMessage(VoiceFrameworkServiceHandler.java:109)
,12-19 12:52:32.832  9676  9734 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
12-19 12:52:32.832  9676  9734 W System.err: 	at android.os.Looper.loop(Looper.java:158)
12-19 12:52:32.832  9676  9734 W System.err: 	at com.samsung.vsf.core.framework.VoiceFrameworkServiceHandler$MyHandlerThread.run(VoiceFrameworkServiceHandler.java:178)
,12-19 12:52:32.832  9735  9735 D TimaKeyStoreProvider: TimaSignature is unavailable
12-19 12:52:32.832  9735  9735 D ActivityThread: Added TimaKeyStore provider
,12-19 12:52:32.832  9676  9676 I SessionRuntime:main:  : VSP::Current Network State is same as previous, so ignoring
,12-19 12:52:32.842  9676  9734 I EmbeddedFrameworkManager:VoiceFrameworkServiceHandler MyHandlerThread:  : VSP::N66 locale is en_US
,12-19 12:52:32.842  3421  3983 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b3fbe6e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{14d0c26 9735:com.android.settings/1000}
,12-19 12:52:32.852  9676  9734 I EmbeddedFrameworkManager:VoiceFrameworkServiceHandler MyHandlerThread:  : VSP::SHL init():
12-19 12:52:32.852  9676  9734 I EmbeddedFrameworkManager:VoiceFrameworkServiceHandler MyHandlerThread: SHL Config:
12-19 12:52:32.852  9676  9734 I EmbeddedFrameworkManager:VoiceFrameworkServiceHandler MyHandlerThread: Locale: en_US
12-19 12:52:32.852  9676  9734 I EmbeddedFrameworkManager:VoiceFrameworkServiceHandler MyHandlerThread: Recognition Path: EMBEDDED
12-19 12:52:32.852  9676  9734 I EmbeddedFrameworkManager:VoiceFrameworkServiceHandler MyHandlerThread: Audio buffer format: PCM_NS
12-19 12:52:32.852  9676  9734 I EmbeddedFrameworkManager:VoiceFrameworkServiceHandler MyHandlerThread: Use internal recorder: false
12-19 12:52:32.852  9676  9734 I EmbeddedFrameworkManager:VoiceFrameworkServiceHandler MyHandlerThread: Use internal EPD: false
,12-19 12:52:32.852  9676  9734 I SHL:VoiceFrameworkServiceHandler MyHandlerThread:  : VSP::SHL Initialize
12-19 12:52:32.852  3421  4391 I AppOps  : sendInfoToFLP, code=41 , uid=10043 , packageName=com.samsung.voiceserviceplatform , type=startOp
12-19 12:52:32.852  9735  9735 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
12-19 12:52:32.852  9735  9735 D RelationGraph: garbageCollect()
,12-19 12:52:32.852  4242  4242 D FusedRequestManager: manageLocationRequest, new passive request from com.samsung.voiceserviceplatform with 1d0ee14 , interval = 1800000 through LocationManagerService
12-19 12:52:32.852  9735  9735 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in com.android.settings rsrc of package com.android.settings
12-19 12:52:32.862  9735  9735 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
12-19 12:52:32.862  3421  3472 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
12-19 12:52:32.862  9676  9734 I etickcount:VoiceFrameworkServiceHandler MyHandlerThread:  : VSP::PocketSphinxEngine:Trying to load libEmbeddedAsr.so
12-19 12:52:32.862  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:32.862  9569  9578 I art     : Background sticky concurrent mark sweep GC freed 13137(1561KB) AllocSpace objects, 0(0B) LOS objects, 11% free, 9MB/10MB, paused 9.702ms total 29.056ms
12-19 12:52:32.862  9735  9735 D ResourcesManager: For user 0 new overlays fetched Null
12-19 12:52:32.862  3421  3853 I ActivityManager: Killing 7546:com.osp.app.signin/u0a44 (adj 15): DHA:empty #33
,12-19 12:52:32.862  9735  9735 I InjectionManager: Inside getClassLibPath caller 
,12-19 12:52:32.882  9735  9735 W System  : ClassLoader referenced unknown path: /system/priv-app/SecSettings2/lib/arm64
,12-19 12:52:32.892  3421  3984 D ActivityManager: isAutoRunBlockedApp:: com.osp.app.signin, Auto Run ON
,12-19 12:52:32.902  9735  9735 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in com.android.settings rsrc of package com.android.settings
,12-19 12:52:32.902  4025  4025 D Recents : onTaskStackChanged
,12-19 12:52:32.902  9676  9734 I etickcount:VoiceFrameworkServiceHandler MyHandlerThread:  : VSP::PocketSphinxEngine:loading libEmbeddedAsr.so done
,12-19 12:52:32.912  9735  9735 D SFinderConnectProvider: onCreate
,12-19 12:52:32.912  4025  4025 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.test.thalitest
,12-19 12:52:32.912  9676  9734 I etickcount:VoiceFrameworkServiceHandler MyHandlerThread:  : VSP::State changed to NULL
12-19 12:52:32.912  9676  9734 I etickcount:VoiceFrameworkServiceHandler MyHandlerThread:  : VSP::Creating engines for en_US
,12-19 12:52:32.912  9676  9734 D CMDTest : VoiceFrameworkServiceHandler MyHandlerThread : posted CreateCmd
12-19 12:52:32.912  9676  9734 I etickcount:VoiceFrameworkServiceHandler MyHandlerThread:  : VSP::RecognitionManager loading..
,12-19 12:52:32.912  9676  9753 D tickcount:PocketSphinx Recognition Engine:  : VSP::CreateCmd execution latency: 0ms
12-19 12:52:32.912  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP::PocketSphinxEngine:create()
12-19 12:52:32.912  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP::State changed to INIT
,12-19 12:52:32.922  9676  9734 D CMDTest : VoiceFrameworkServiceHandler MyHandlerThread : posted ConfigureCmd
12-19 12:52:32.922  9676  9734 I etickcount:VoiceFrameworkServiceHandler MyHandlerThread:  : VSP::State changed to INIT
,12-19 12:52:32.922  9676  9753 D tickcount:PocketSphinx Recognition Engine:  : VSP::ConfigureCmd execution latency: 0ms
12-19 12:52:32.922  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP::PocketSphinxEngine:configure() in state INIT
,12-19 12:52:32.922  4025  4025 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:32.922  9676  9734 I etickcount:VoiceFrameworkServiceHandler MyHandlerThread:  : VSP::setSpeechRecognitionListener: com.samsung.vsf.core.framework.embedded.EmbeddedFrameworkManager@bac58d3
12-19 12:52:32.922  9676  9753 W ResourcesManager: getTopLevelResources: /system/priv-app/SVoiceLang_EnglishPack_US_1.0/SVoiceLang_EnglishPack_US_1.0.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.svoice.lang.en_US
,12-19 12:52:32.922  9676  9753 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:32.932  9697  9708 D PLMProvider: match for uri : content://com.samsung.svoice.sync/tos_accepted is : 8
,12-19 12:52:32.942  9735  9735 I BNRClientProivder, VERSION : 1.7.5: register - xml6 quick_backup : ACCESSIBILITYSETTINGS, X6qErjsfs2, com.android.settings.accessibility.sharedaccessibility.scloud.BNRTask
,12-19 12:52:32.942  9735  9735 I QBNRClientHelper: init SyncClientHelper : ACCESSIBILITYSETTINGS
12-19 12:52:32.942  9735  9735 I BNRClientProivder, VERSION : 1.7.5: register - xml6 quick_backup : CONNECTIONS, C0phMaUuZZ, com.android.settings.wifi.mobileap.WifiApBackupRestore
,12-19 12:52:32.942  9735  9735 I QBNRClientHelper: init SyncClientHelper : CONNECTIONS
12-19 12:52:32.942  9735  9735 I BNRClientProivder, VERSION : 1.7.5: register - xml6 quick_backup : WiFi, C0phMaUuZZ, com.android.settings.wifi.WifiBackupRestore
12-19 12:52:32.942  9735  9735 I QBNRClientHelper: init SyncClientHelper : WiFi
,12-19 12:52:32.952  9735  9735 D InjectionManager: InjectionManager
,12-19 12:52:32.952  9735  9735 D InjectionManager: fillFeatureStoreMap com.android.settings
12-19 12:52:32.952  9735  9735 I InjectionManager: Constructor com.android.settings, Feature store :{}
12-19 12:52:32.952  9735  9735 I InjectionManager: featureStore :{}
,12-19 12:52:32.952  3421  4616 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b3fbe6e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{14d0c26 9735:com.android.settings/1000}
,12-19 12:52:32.962  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP::MD5 Files From Assets : en_US.zip.MD5
,12-19 12:52:32.962  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP:: Time Taken LoadMD5FromPackage:  0.002 seconds.
,12-19 12:52:32.962  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP:: Time Taken LoadMD5FromAssets:  0.0 seconds.
12-19 12:52:32.962  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP:: MD5 Checked in :  0.031 seconds.
12-19 12:52:32.962  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP::No Update 0
,12-19 12:52:32.962  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP:: #### No Update in The Models #####
12-19 12:52:32.962  9676  9753 D etickcount:PocketSphinx Recognition Engine:  : VSP::TimeTaken for unpacking 39ms
12-19 12:52:32.962  9676  9753 D etickcount: Lang is en_US
12-19 12:52:32.962  9676  9753 I PLMGenManager: Version  : V_030816
12-19 12:52:32.962  9676  9753 D Flag    : configFalg value : 0
12-19 12:52:32.962  9676  9753 D PLMGenManager: Is JSON file found ? false
,12-19 12:52:32.962  9676  9753 D PLMGenManager: Config flag is : 0
,12-19 12:52:32.962  9676  9753 D AppInfo : TimeTaken for App Alias name generation : 2ms
,12-19 12:52:32.972  3421  4616 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b3fbe6e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{14d0c26 9735:com.android.settings/1000}
,12-19 12:52:32.972  9735  9735 I DataWarningReceiver: DataWarningReceiver
,12-19 12:52:32.972  9676  9753 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2015/SecGallery2015.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.gallery3d
,12-19 12:52:32.972  9676  9753 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:32.972  9714  9714 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 android.content.ContextWrapper.sendBroadcast:410 com.samsung.SMT.b.i.a:-1 com.samsung.SMT.SamsungTTSService.onCreate:-1 android.app.ActivityThread.handleCreateService:3808 
,12-19 12:52:32.972  9676  9753 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2015/SecGallery2015.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.gallery3d
,12-19 12:52:32.972  9676  9753 I PLM     : App title : Gallery & activity name : com.sec.android.gallery3d.app.GalleryOpaqueActivity_com.sec.android.gallery3d
,12-19 12:52:32.982  9676  9753 W ResourcesManager: getTopLevelResources: /system/priv-app/Phonesky/Phonesky.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.android.vending
,12-19 12:52:32.982  9569  9710 W jxcore-log: Initializing JXcore engine
,12-19 12:52:32.982  9569  9710 W jxcore-log: JXcore engine is ready
,12-19 12:52:32.982  9676  9753 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:32.982  9676  9753 W ResourcesManager: getTopLevelResources: /system/priv-app/Phonesky/Phonesky.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.android.vending
,12-19 12:52:32.982  9676  9753 I PLM     : App title : Play_Store & activity name : com.android.vending.AssetBrowserActivity_com.android.vending
,12-19 12:52:32.982  9676  9753 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.shealth
,12-19 12:52:32.982  9755  9755 E Zygote  : v2
,12-19 12:52:32.982  9755  9755 I libpersona: KNOX_SDCARD checking this for 10060
12-19 12:52:32.982  9755  9755 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0029
12-19 12:52:32.982  9755  9755 I libpersona: KNOX_SDCARD not a persona
12-19 12:52:32.982  9676  9753 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:32.992  9755  9755 E Zygote  : accessInfo : 0
12-19 12:52:32.992  9755  9755 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.provider.shootingmodeprovider 
,12-19 12:52:32.992  9676  9753 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.shealth
12-19 12:52:32.992  3421  4417 I ActivityManager: Start proc 9755:com.samsung.android.provider.shootingmodeprovider/u0a60 for broadcast-3 com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver
12-19 12:52:32.992  9676  9753 I PLM     : App title : S_Health & activity name : com.samsung.android.app.shealth.home.HomeMainActivity_com.sec.android.app.shealth
12-19 12:52:32.992  9676  9753 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCamera5/SamsungCamera5.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.camera
12-19 12:52:32.992  3421  4417 I ActivityManager: Killing 8809:com.samsung.android.SettingsReceiver/1000 (adj 15): DHA:empty #33
12-19 12:52:32.992  9676  9753 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:33.002  9676  9753 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCamera5/SamsungCamera5.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.camera
12-19 12:52:33.002  9676  9753 I PLM     : App title : Camera & activity name : com.sec.android.app.camera.Camera_com.sec.android.app.camera
,12-19 12:52:33.002  9676  9753 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.android.contacts
,12-19 12:52:33.002  5061  5061 E audit   : type=1400 msg=audit(1482148353.002:264): avc:  denied  { ioctl } for  pid=9710 comm="Thread-140" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2224 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
12-19 12:52:33.002  5061  5061 E audit   :  SEPF_SECMOBILE_6.0.1_0029
12-19 12:52:33.002  5061  5061 E audit   : type=1300 msg=audit(1482148353.002:264): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=8 a1=5451 a2=4 a3=d8d053c8 items=0 ppid=3179 pid=9710 auid=4294967295 uid=10078 gid=10078 euid=10078 suid=10078 fsuid=10078 egid=10078 sgid=10078 fsgid=10078 tty=(none) ses=4294967295 comm="Thread-140" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
12-19 12:52:33.002  5061  5061 E audit   : type=1327 msg=audit(1482148353.002:264): proctitle="com.test.thalitest"
12-19 12:52:33.002  5061  5061 E audit   : type=1320 msg=audit(1482148353.002:264): 
12-19 12:52:33.002  5061  5061 E audit   : type=1400 msg=audit(1482148353.002:265): avc:  denied  { ioctl } for  pid=9710 comm="Thread-140" path="socket:[11067]" dev="sockfs" ino=11067 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
12-19 12:52:33.002  5061  5061 E audit   :  SEPF_SECMOBILE_6.0.1_0029
12-19 12:52:33.002  5061  5061 E audit   : type=1300 msg=audit(1482148353.002:265): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=3c a1=5451 a2=4 a3=d8d053c8 items=0 ppid=3179 pid=9710 auid=4294967295 uid=10078 gid=10078 euid=10078 suid=10078 fsuid=10078 egid=10078 sgid=10078 fsgid=10078 tty=(none) ses=4294967295 comm="Thread-140" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
12-19 12:52:33.002  5061  5061 E audit   : type=1327 msg=audit(1482148353.002:265): proctitle="com.test.thalitest"
12-19 12:52:33.002  5061  5061 E audit   : type=1320 msg=audit(1482148353.002:265): 
,12-19 12:52:33.012  4637  7403 I Icing   : Indexing E1051AF754FD4764B2B13213EB917898AAC96AFB from com.google.android.gms
,12-19 12:52:33.012  9676  9753 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:33.012  9569  9710 W jxcore-log: Starting JXcore engine
,12-19 12:52:33.012  9755  9755 D TimaKeyStoreProvider: TimaSignature is unavailable
12-19 12:52:33.012  9755  9755 D ActivityThread: Added TimaKeyStore provider
12-19 12:52:33.012  3421  3474 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.SettingsReceiver, Auto Run ON
,12-19 12:52:33.012  9676  9753 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.android.contacts
,12-19 12:52:33.012  9676  9753 I PLM     : App title : Contacts & activity name : com.android.contacts.activities.PeopleActivity_com.android.contacts
,12-19 12:52:33.012  9676  9753 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.android.contacts
,12-19 12:52:33.012  9676  9753 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.android.contacts
12-19 12:52:33.012  9676  9753 I PLM     : App title : Phone & activity name : com.android.dialer.DialtactsActivity_com.android.contacts
,12-19 12:52:33.022  9676  9753 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.samsung.android.email.provider
,12-19 12:52:33.022  9676  9753 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:33.022  9676  9753 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.samsung.android.email.provider
,12-19 12:52:33.022  9676  9753 I PLM     : App title : Email & activity name : com.samsung.android.email.ui.activity.MessageListXL_com.samsung.android.email.provider
12-19 12:52:33.022  9676  9753 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Epic_Common/SecMms_Epic_Common.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.android.mms
,12-19 12:52:33.022  9676  9753 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:33.022  9676  9753 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Epic_Common/SecMms_Epic_Common.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.android.mms
12-19 12:52:33.032  9676  9753 I PLM     : App alias title : sms & activity name : com.android.mms.ui.ConversationComposer_com.android.mms
12-19 12:52:33.032  9676  9753 I PLM     : App title : Messages & activity name : com.android.mms.ui.ConversationComposer_com.android.mms
12-19 12:52:33.032  3421  4391 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b3fbe6e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{745380a 9755:com.samsung.android.provider.shootingmodeprovider/u0a60}
,12-19 12:52:33.032  9676  9753 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.android.settings
,12-19 12:52:33.032  9714  9714 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 com.samsung.SMT.SamsungTTSService.g:-1 com.samsung.SMT.SamsungTTSService.onCreate:-1 android.app.ActivityThread.handleCreateService:3808 
,12-19 12:52:33.032  9676  9753 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:33.032  9676  9753 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.android.settings
12-19 12:52:33.032  9676  9753 I PLM     : App title : Settings & activity name : com.android.settings.Settings_com.android.settings
12-19 12:52:33.032  9676  9753 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.android.chrome
12-19 12:52:33.032  9755  9755 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
12-19 12:52:33.032  9755  9755 D RelationGraph: garbageCollect()
12-19 12:52:33.032  9676  9753 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:33.032  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:33.042  9714  9714 I SamsungTTS: Interface ver201503021
12-19 12:52:33.042  9714  9714 I SamsungTTS: Engine ver200812311
12-19 12:52:33.042  9755  9755 W ResourcesManager: getTopLevelResources: /system/priv-app/ShootingModeProvider/ShootingModeProvider.apk / 1.0 running in com.samsung.android.provider.shootingmodeprovider rsrc of package com.samsung.android.provider.shootingmodeprovider
,12-19 12:52:33.042  9676  9753 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.android.chrome
12-19 12:52:33.042  9676  9753 I PLM     : App title : Chrome & activity name : com.google.android.apps.chrome.Main_com.android.chrome
,12-19 12:52:33.042  9676  9676 I TextToSpeech: Connected to ComponentInfo{com.samsung.SMT/com.samsung.SMT.SamsungTTSService}
,12-19 12:52:33.042  3421  4333 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
12-19 12:52:33.042  9676  9753 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.apps.docs
,12-19 12:52:33.042  9714  9714 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 com.samsung.SMT.SamsungTTSService.g:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.c.onReceive:-1 
12-19 12:52:33.042  9755  9755 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,12-19 12:52:33.042  9676  9753 D ResourcesManager: For user 0 new overlays fetched Null
12-19 12:52:33.042  9755  9755 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:33.052  9676  9753 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.apps.docs
,12-19 12:52:33.052  9755  9755 I InjectionManager: Inside getClassLibPath caller 
12-19 12:52:33.052  9714  9725 D SamsungTTS: onIsLanguageAvailable() : L=pol  C=POL  V=null  LANG_NOT_SUPPORTED
12-19 12:52:33.052  9676  9753 I PLM     : App title : Drive & activity name : com.google.android.apps.docs.app.NewMainProxyActivity_com.google.android.apps.docs
,12-19 12:52:33.052  9676  9753 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.gm
,12-19 12:52:33.052  9755  9755 W System  : ClassLoader referenced unknown path: /system/priv-app/ShootingModeProvider/lib/arm64
,12-19 12:52:33.052  9676  9767 I TextToSpeech: Set up connection to ComponentInfo{com.samsung.SMT/com.samsung.SMT.SamsungTTSService}
,12-19 12:52:33.062  9676  9753 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:33.062  9569  9710 W jxcore-log: Platform android
12-19 12:52:33.062  9569  9710 W jxcore-log: 
,12-19 12:52:33.062  9569  9710 W jxcore-log: Process ARCH arm
12-19 12:52:33.062  9569  9710 W jxcore-log: 
,12-19 12:52:33.062  9676  9753 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.gm
,12-19 12:52:33.062  9676  9676 I SV_TTSPlayer:main:  : VSP::locale is: en_US
12-19 12:52:33.062  9676  9753 I PLM     : App title : Gmail & activity name : com.google.android.gm.ConversationListActivityGmail_com.google.android.gm
,12-19 12:52:33.062  9714  9724 D SamsungTTS: onIsLanguageAvailable() : L=eng  C=USA  V=null  LANG_COUNTRY_AVAILABLE
,12-19 12:52:33.062  9676  9753 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.talk
,12-19 12:52:33.062  9714  9725 D SamsungTTS: onIsLanguageAvailable() : L=eng  C=USA  V=null  LANG_COUNTRY_AVAILABLE
,12-19 12:52:33.062  9755  9755 D InjectionManager: InjectionManager
12-19 12:52:33.062  9714  9724 D SamsungTTS: onIsLanguageAvailable() : L=eng  C=USA  V=null  LANG_COUNTRY_AVAILABLE
12-19 12:52:33.062  9755  9755 D InjectionManager: fillFeatureStoreMap com.samsung.android.provider.shootingmodeprovider
,12-19 12:52:33.072  9676  9753 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:33.072  9755  9755 I InjectionManager: Constructor com.samsung.android.provider.shootingmodeprovider, Feature store :{}
12-19 12:52:33.072  9755  9755 I InjectionManager: featureStore :{}
,12-19 12:52:33.072  9714  9727 D SamsungTTS: onIsLanguageAvailable() : L=eng  C=USA  V=f00  LANG_COUNTRY_VAR_AVAILABLE
12-19 12:52:33.072  9714  9727 D SamsungTTS: onLoadLanguage() : [ LANG_COUNTRY_VAR_AVAILABLE ]  L=eng  C=USA  V=f00
,12-19 12:52:33.072  9676  9753 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.talk
,12-19 12:52:33.072  9676  9753 I PLM     : App title : Hangouts & activity name : com.google.android.talk.SigningInActivity_com.google.android.talk
,12-19 12:52:33.072  9676  9753 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.music
12-19 12:52:33.082  9676  9753 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:33.082  9676  9753 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.music
,12-19 12:52:33.082  9676  9753 I PLM     : App title : Play_Music & activity name : com.android.music.activitymanagement.TopLevelActivity_com.google.android.music
12-19 12:52:33.082  9676  9753 W ResourcesManager: getTopLevelResources: /system/app/Photos/Photos.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.apps.photos
,12-19 12:52:33.082  3421  3984 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b3fbe6e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d35c157 9523:com.samsung.android.sm.provider/1000}
,12-19 12:52:33.102  9676  9676 D Test    : TTS initialized! & queue size is : 0
12-19 12:52:33.102  3421  4415 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b3fbe6e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ac93068 9462:com.samsung.android.sm.devicesecurity/5012}
,12-19 12:52:33.112  4637  7403 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.gms rsrc of package com.test.thalitest
,12-19 12:52:33.122  3421  4415 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b3fbe6e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cf5b5b3 9213:com.samsung.android.app.taskedge/u0a67}
,12-19 12:52:33.122  9213  9213 I TaskEdgeBroadcastReceiver: onReceive:android.intent.action.PACKAGE_ADDED
,12-19 12:52:33.122  9676  9753 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:33.132  4637  7403 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:33.132  9676  9753 W ResourcesManager: getTopLevelResources: /system/app/Photos/Photos.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.apps.photos
12-19 12:52:33.132  9676  9753 I PLM     : App title : Photos & activity name : com.google.android.apps.photos.home.HomeActivity_com.google.android.apps.photos
,12-19 12:52:33.132  4637  7403 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.gms rsrc of package com.test.thalitest
,12-19 12:52:33.132  9676  9753 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.sbrowser
,12-19 12:52:33.132  9676  9753 D ResourcesManager: For user 0 new overlays fetched Null
12-19 12:52:33.132  9676  9753 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.sbrowser
12-19 12:52:33.132  9676  9753 I PLM     : App title : Internet & activity name : com.sec.android.app.sbrowser.SBrowserMainActivity_com.sec.android.app.sbrowser
12-19 12:52:33.132  9676  9753 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M/SPlanner_M.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.android.calendar
12-19 12:52:33.132  9676  9753 D ResourcesManager: For user 0 new overlays fetched Null
12-19 12:52:33.132  3421  3981 I ActivityManager: Killing 9080:com.samsung.android.app.simplesharing/5011 (adj 15): DHA:empty #33
,12-19 12:52:33.142  9676  9753 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M/SPlanner_M.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.android.calendar
,12-19 12:52:33.142  9676  9753 I PLM     : App alias title : calendar & activity name : com.android.calendar.AllInOneActivity_com.android.calendar
12-19 12:52:33.142  9676  9753 I PLM     : App alias title : s_planner & activity name : com.android.calendar.AllInOneActivity_com.android.calendar
12-19 12:52:33.142  9676  9753 I PLM     : App alias title : schedule & activity name : com.android.calendar.AllInOneActivity_com.android.calendar
12-19 12:52:33.142  9676  9753 I PLM     : App alias title : diary & activity name : com.android.calendar.AllInOneActivity_com.android.calendar
12-19 12:52:33.142  9676  9753 I PLM     : App title : S_Planner & activity name : com.android.calendar.AllInOneActivity_com.android.calendar
12-19 12:52:33.142  9676  9753 W ResourcesManager: getTopLevelResources: /system/app/Videos/Videos.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.videos
12-19 12:52:33.142  9676  9753 D ResourcesManager: For user 0 new overlays fetched Null
12-19 12:52:33.142  9676  9753 W ResourcesManager: getTopLevelResources: /system/app/Videos/Videos.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.videos
,12-19 12:52:33.142  3421  3981 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b3fbe6e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ef8770f 4298:com.android.phone/1001},
12-19 12:52:33.142  9676  9753 I PLM     : App title : Play_Movies_&_TV & activity name : com.google.android.youtube.videos.EntryPoint_com.google.android.videos
12-19 12:52:33.142  9676  9753 W ResourcesManager: getTopLevelResources: /system/app/YouTube/YouTube.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.youtube
,12-19 12:52:33.152  9676  9753 D ResourcesManager: For user 0 new overlays fetched Null
12-19 12:52:33.152  4637  7403 I Icing   : Indexing done E1051AF754FD4764B2B13213EB917898AAC96AFB
12-19 12:52:33.152  9676  9753 W ResourcesManager: getTopLevelResources: /system/app/YouTube/YouTube.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.youtube
12-19 12:52:33.152  9676  9753 I PLM     : App title : YouTube & activity name : com.google.android.youtube.app.honeycomb.Shell$HomeActivity_com.google.android.youtube
12-19 12:52:33.152  9676  9753 W ResourcesManager: getTopLevelResources: /system/priv-app/Excel_SamsungStub/Excel_SamsungStub.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.microsoft.office.excel
12-19 12:52:33.152  9676  9753 D ResourcesManager: For user 0 new overlays fetched Null
12-19 12:52:33.152  9676  9753 W ResourcesManager: getTopLevelResources: /system/priv-app/Excel_SamsungStub/Excel_SamsungStub.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.microsoft.office.excel
12-19 12:52:33.152  9676  9753 I PLM     : App title : Excel & activity name : com.microsoft.office.apphost.LaunchActivity_com.microsoft.office.excel
12-19 12:52:33.162  9676  9753 W ResourcesManager: getTopLevelResources: /system/priv-app/GearManager/GearManager.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.samsung.android.app.watchmanager
12-19 12:52:33.162  9676  9753 D ResourcesManager: For user 0 new overlays fetched Null
12-19 12:52:33.162  3161  3875 V MediaPlayerService: Client(6) destructor pid = 9080
12-19 12:52:33.162  3161  3875 V MediaPlayerService: disconnect(6) from pid 9080
12-19 12:52:33.162  3161  3875 D NuPlayerDriver: reset(0xf184bea0)
12-19 12:52:33.162  3161  3875 D NuPlayerDriver: notifyListener_l(0xf184bea0), (8, 0, 0)
12-19 12:52:33.162  3161  9100 V NuPlayer: kWhatReset
12-19 12:52:33.162  3161  9100 V NuPlayer: performReset
12-19 12:52:33.162  3161  9100 V GenericSource: stop()
12-19 12:52:33.162  3161  9100 V GenericSource: PREPARE_CANCELLED set to true
12-19 12:52:33.162  3161  9100 V GenericSource: [Flag] set 0x40 -> mFlags = 0x48
12-19 12:52:33.162  3161  9100 V GenericSource: [Flag] clear 0x8 -> mFlags = 0x40
12-19 12:52:33.162  3161  9100 V GenericSource: stop() end
12-19 12:52:33.162  3161  9100 V GenericSource: ~GenericSource()
12-19 12:52:33.162  3161  9100 I OggExtractor: OggSource::stop() mExtractor ref count = 2
12-19 12:52:33.162  3161  9100 I OggExtractor: ~OggSource --
12-19 12:52:33.162  3161  9100 D NuPlayerDriver: notifyResetComplete(0xf184bea0)
12-19 12:52:33.162  3161  3875 V NuPlayerDriver: ~NuPlayerDriver(0xf184bea0)
12-19 12:52:33.162  3161  3875 I OggExtractor: ~OggExtractor ++
12-19 12:52:33.162  3161  3875 I OggExtractor: ~MyOggExtractor ++ 
12-19 12:52:33.162  3161  3875 I OggExtractor: ~MyOggExtractor --
12-19 12:52:33.162  3161  3875 I OggExtractor: ~OggExtractor --
12-19 12:52:33.162  9676  9753 W ResourcesManager: getTopLevelResources: /system/priv-app/GearManager/GearManager.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.samsung.android.app.watchmanager
12-19 12:52:33.162  3161  3875 V AudioSink: +++ close
12-19 12:52:33.162  3161  3875 V AudioSink: --- close
12-19 12:52:33.162  9676  9753 I PLM     : App title : Samsung_Gear & activity name : com.samsung.android.app.watchmanager.setupwizard.SetupWizardWelcomeActivity_com.samsung.android.app.watchmanager
12-19 12:52:33.162  9676  9753 W ResourcesManager: getTopLevelResources: /system/priv-app/PowerPoint_SamsungStub/PowerPoint_SamsungStub.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.microsoft.office.powerpoint
12-19 12:52:33.162  9676  9753 D ResourcesManager: For user 0 new overlays fetched Null
12-19 12:52:33.162  9676  9753 W ResourcesManager: getTopLevelResources: /system/priv-app/PowerPoint_SamsungStub/PowerPoint_SamsungStub.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.microsoft.office.powerpoint
12-19 12:52:33.162  9676  9753 I PLM     : App title : PowerPoint & activity name : com.microsoft.office.apphost.LaunchActivity_com.microsoft.office.powerpoint
12-19 12:52:33.172  9676  9753 W ResourcesManager: getTopLevelResources: /system/priv-app/SVoice_1.0/SVoice_1.0.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.samsung.voiceserviceplatform
12-19 12:52:33.172  9676  9753 W ResourcesManager: getTopLevelResources: /system/priv-app/SVoice_1.0/SVoice_1.0.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.samsung.voiceserviceplatform
12-19 12:52:33.172  9676  9753 W ResourcesManager: getTopLevelResources: /system/priv-app/SecCalculator_M/SecCalculator_M.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.popupcalculator
12-19 12:52:33.172  9676  9753 D ResourcesManager: For user 0 new overlays fetched Null
12-19 12:52:33.172  9676  9753 W ResourcesManager: getTopLevelResources: /system/priv-app/SecCalculator_M/SecCalculator_M.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.popupcalculator
12-19 12:52:33.172  9676  9753 I PLM     : App title : Calculator & activity name : com.sec.android.app.popupcalculator.Calculator_com.sec.android.app.popupcalculator
12-19 12:52:33.172  9676  9753 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles/SecMyFiles.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.myfiles
12-19 12:52:33.172  9676  9753 D ResourcesManager: For user 0 new overlays fetched Null
12-19 12:52:33.172  9676  9753 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles/SecMyFiles.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.myfiles
12-19 12:52:33.172  9676  9753 I PLM     : App title : My_Files & activity name : com.sec.android.app.myfiles.common.MainActivity_com.sec.android.app.myfiles
12-19 12:52:33.172  9676  9753 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.googlequicksearchbox
12-19 12:52:33.172  3421  4182 I ActivityManager: Start proc 9770:com.samsung.android.themecenter/1000 for broadcast-3 com.samsung.android.themecenter/com.samsung.android.thememanager.ThemeManagerReceiver
12-19 12:52:33.182  9770  9770 E Zygote  : v2
12-19 12:52:33.182  9770  9770 I libpersona: KNOX_SDCARD checking this for 1000
12-19 12:52:33.182  9770  9770 I libpersona: KNOX_SDCARD not a persona
12-19 12:52:33.182  9770  9770 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0029
12-19 12:52:33.182  9676  9753 D ResourcesManager: For user 0 new overlays fetched Null
12-19 12:52:33.182  9770  9770 E Zygote  : accessInfo : 0
12-19 12:52:33.182  9676  9753 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.googlequicksearchbox
12-19 12:52:33.182  9676  9753 I PLM     : App title : Voice_Search & activity name : com.google.android.googlequicksearchbox.VoiceSearchActivity_com.google.android.googlequicksearchbox
12-19 12:52:33.182  9676  9753 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.googlequicksearchbox
12-19 12:52:33.182  9676  9753 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.googlequicksearchbox
12-19 12:52:33.182  9676  9753 I PLM     : App title : Google & activity name : com.google.android.googlequicksearchbox.SearchActivity_com.google.android.googlequicksearchbox
12-19 12:52:33.182  9676  9753 W ResourcesManager: getTopLevelResources: /system/priv-app/VoiceNote_4.0/VoiceNote_4.0.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.voicenote
12-19 12:52:33.192  3421  4989 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.simplesharing, Auto Run ON
12-19 12:52:33.192  9676  9753 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:33.192  9676  9753 W ResourcesManager: getTopLevelResources: /system/priv-app/VoiceNote_4.0/VoiceNote_4.0.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.voicenote
,12-19 12:52:33.192  9569  9710 I jxcore-log: JXcore Cordova bridge is ready!
12-19 12:52:33.192  9569  9710 I jxcore-log: 
12-19 12:52:33.192  9676  9753 I PLM     : App title : Voice_Recorder & activity name : com.sec.android.app.voicenote.main.VNMainActivity_com.sec.android.app.voicenote
12-19 12:52:33.192  9569  9710 W jxcore-log: JXcore engine is started
12-19 12:52:33.202  9676  9753 W ResourcesManager: getTopLevelResources: /system/priv-app/Word_SamsungStub/Word_SamsungStub.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.microsoft.office.word
,12-19 12:52:33.202  9676  9753 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:33.202  9676  9753 W ResourcesManager: getTopLevelResources: /system/priv-app/Word_SamsungStub/Word_SamsungStub.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.microsoft.office.word
12-19 12:52:33.202  9676  9753 I PLM     : App title : Word & activity name : com.microsoft.office.apphost.LaunchActivity_com.microsoft.office.word
,12-19 12:52:33.202  9676  9753 W ResourcesManager: getTopLevelResources: /system/priv-app/player-production-release-3.3.3-newSDK_23/player-production-release-3.3.3-newSDK_23.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package pl.tvn.player
,12-19 12:52:33.202  9676  9753 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:33.202  9770  9770 D TimaKeyStoreProvider: TimaSignature is unavailable
12-19 12:52:33.202  9770  9770 D ActivityThread: Added TimaKeyStore provider
,12-19 12:52:33.202  9676  9753 W ResourcesManager: getTopLevelResources: /system/priv-app/player-production-release-3.3.3-newSDK_23/player-production-release-3.3.3-newSDK_23.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package pl.tvn.player
12-19 12:52:33.202  9676  9753 I PLM     : App title : Player & activity name : pl.tvn.player.ui.SplashActivity_pl.tvn.player
,12-19 12:52:33.202  9676  9753 W ResourcesManager: getTopLevelResources: /system/app/ClockPackage_M/ClockPackage_M.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.clockpackage
,12-19 12:52:33.212  9676  9753 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:33.212  3421  3472 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b3fbe6e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1160444 9770:com.samsung.android.themecenter/1000}
,12-19 12:52:33.212  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:33.222  9676  9753 W ResourcesManager: getTopLevelResources: /system/app/ClockPackage_M/ClockPackage_M.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.clockpackage
12-19 12:52:33.222  9676  9753 I PLM     : App alias title : alarm & activity name : com.sec.android.app.clockpackage.ClockPackage_com.sec.android.app.clockpackage
12-19 12:52:33.222  9676  9753 I PLM     : App title : Clock & activity name : com.sec.android.app.clockpackage.ClockPackage_com.sec.android.app.clockpackage
,12-19 12:52:33.222  9676  9753 W ResourcesManager: getTopLevelResources: /system/app/FBInstagram_stub/FBInstagram_stub.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.instagram.android
,12-19 12:52:33.222  9676  9753 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:33.222  9676  9753 W ResourcesManager: getTopLevelResources: /system/app/FBInstagram_stub/FBInstagram_stub.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.instagram.android
12-19 12:52:33.222  9676  9753 I PLM     : App title : Instagram & activity name : com.instagram.android.activity.MainTabActivity_com.instagram.android
,12-19 12:52:33.222  9770  9770 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
12-19 12:52:33.222  9770  9770 D RelationGraph: garbageCollect()
12-19 12:52:33.222  9676  9753 W ResourcesManager: getTopLevelResources: /system/app/Facebook_stub/Facebook_stub.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.facebook.katana
12-19 12:52:33.222  9770  9770 W ResourcesManager: getTopLevelResources: /system/priv-app/ThemeCenter/ThemeCenter.apk / 1.0 running in com.samsung.android.themecenter rsrc of package com.samsung.android.themecenter
,12-19 12:52:33.222  9676  9753 D ResourcesManager: For user 0 new overlays fetched Null
12-19 12:52:33.222  3421  3474 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
12-19 12:52:33.222  9770  9770 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
12-19 12:52:33.222  9676  9753 W ResourcesManager: getTopLevelResources: /system/app/Facebook_stub/Facebook_stub.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.facebook.katana
12-19 12:52:33.222  9676  9753 I PLM     : App title : Facebook & activity name : com.facebook.katana.LoginActivity_com.facebook.katana
12-19 12:52:33.222  9676  9753 W ResourcesManager: getTopLevelResources: /system/app/MSSkype_stub/MSSkype_stub.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.skype.raider
12-19 12:52:33.222  9770  9770 D ResourcesManager: For user 0 new overlays fetched Null
12-19 12:52:33.232  9676  9753 D ResourcesManager: For user 0 new overlays fetched Null
12-19 12:52:33.232  9676  9753 W ResourcesManager: getTopLevelResources: /system/app/MSSkype_stub/MSSkype_stub.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.skype.raider
12-19 12:52:33.232  9676  9753 I PLM     : App title : Skype & activity name : com.skype.raider.Main_com.skype.raider
,12-19 12:52:33.232  9770  9770 I InjectionManager: Inside getClassLibPath caller 
12-19 12:52:33.232  9676  9753 W ResourcesManager: getTopLevelResources: /system/app/Maps/Maps.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.apps.maps
,12-19 12:52:33.232  9714  9727 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 android.content.ContextWrapper.sendBroadcast:410 com.samsung.SMT.b.i.a:-1 com.samsung.SMT.SamsungTTSService.b:-1 com.samsung.SMT.SamsungTTSService.onLoadLanguage:-1 
,12-19 12:52:33.232  9676  9753 D ResourcesManager: For user 0 new overlays fetched Null
12-19 12:52:33.232  9770  9770 W System  : ClassLoader referenced unknown path: /system/priv-app/ThemeCenter/lib/arm64
,12-19 12:52:33.232  9676  9753 W ResourcesManager: getTopLevelResources: /system/app/Maps/Maps.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.apps.maps
12-19 12:52:33.232  9714  9727 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 android.content.ContextWrapper.sendBroadcast:410 android.speech.tts.TextToSpeechService$SynthThread.broadcastTtsQueueProcessingCompleted:460 android.speech.tts.TextToSpeechService$SynthThread.queueIdle:452 android.os.MessageQueue.next:392 
12-19 12:52:33.232  9676  9753 I PLM     : App title : Maps & activity name : com.google.android.maps.MapsActivity_com.google.android.apps.maps
,12-19 12:52:33.232  9770  9770 D InjectionManager: InjectionManager
12-19 12:52:33.232  9770  9770 D InjectionManager: fillFeatureStoreMap com.samsung.android.themecenter
12-19 12:52:33.232  9676  9753 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.microsoft.skydrive
,12-19 12:52:33.232  9770  9770 I InjectionManager: Constructor com.samsung.android.themecenter, Feature store :{}
12-19 12:52:33.232  9770  9770 I InjectionManager: featureStore :{}
,12-19 12:52:33.242  9676  9753 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:33.242  9770  9770 I ThemeManagerReceiver: ThemeManagerReceiver onReceive android.intent.action.PACKAGE_ADDED
,12-19 12:52:33.242  9676  9753 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.microsoft.skydrive
,12-19 12:52:33.242  9676  9753 I PLM     : App title : OneDrive & activity name : com.microsoft.skydrive.MainActivity_com.microsoft.skydrive
12-19 12:52:33.242  9676  9753 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.microsoft.office.onenote
,12-19 12:52:33.242  3421  4333 I ActivityManager: Killing 8847:com.samsung.android.coreapps/5011 (adj 15): DHA:empty #33
,12-19 12:52:33.242  9676  9753 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:33.242  9676  9753 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.microsoft.office.onenote
,12-19 12:52:33.242  9676  9753 I PLM     : App title : OneNote & activity name : com.microsoft.office.onenote.ui.ONMSplashActivity_com.microsoft.office.onenote
12-19 12:52:33.242  9676  9753 W ResourcesManager: getTopLevelResources: /system/app/SecMemo3/SecMemo3.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.samsung.android.app.memo
,12-19 12:52:33.242  9676  9753 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:33.242  3421  4333 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b3fbe6e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d5246eb 4422:com.google.android.googlequicksearchbox:search/u0a72}
,12-19 12:52:33.242  9676  9753 W ResourcesManager: getTopLevelResources: /system/app/SecMemo3/SecMemo3.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.samsung.android.app.memo
12-19 12:52:33.252  9676  9753 I PLM     : App title : Memo & activity name : com.samsung.android.app.memo.Main_com.samsung.android.app.memo
12-19 12:52:33.252  9676  9753 W ResourcesManager: getTopLevelResources: /system/app/WhatsAppDownloader/WhatsAppDownloader.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.whatsapp
,12-19 12:52:33.252  9676  9753 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:33.252  9676  9753 I PLM     : App title : WhatsApp & activity name : com.whatsapp.Main_com.whatsapp
,12-19 12:52:33.252  9676  9753 W ResourcesManager: getTopLevelResources: /data/app/com.sec.android.app.samsungapps-2/base.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.samsungapps
,12-19 12:52:33.252  9676  9753 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:33.252  9676  9753 W ResourcesManager: getTopLevelResources: /data/app/com.sec.android.app.samsungapps-2/base.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.samsungapps
,12-19 12:52:33.252  9676  9753 I PLM     : App title : Galaxy_Apps & activity name : com.sec.android.app.samsungapps.SamsungAppsMainActivity_com.sec.android.app.samsungapps
,12-19 12:52:33.252  9676  9753 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.test.thalitest
,12-19 12:52:33.262  9676  9753 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:33.262  9676  9753 I PLM     : App title : ThaliTest & activity name : com.test.thalitest.MainActivity_com.test.thalitest
,12-19 12:52:33.262  9676  9753 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.test.thalitest
,12-19 12:52:33.262  3421  4182 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b3fbe6e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d5246eb 4422:com.google.android.googlequicksearchbox:search/u0a72}
,12-19 12:52:33.282  3421  3984 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.coreapps, Auto Run ON
,12-19 12:52:33.292  4422  9782 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,12-19 12:52:33.302  9783  9783 E Zygote  : v2
12-19 12:52:33.302  9783  9783 I libpersona: KNOX_SDCARD checking this for 5009
12-19 12:52:33.302  9783  9783 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0029
12-19 12:52:33.302  9783  9783 I libpersona: KNOX_SDCARD not a persona
,12-19 12:52:33.302  9783  9783 E Zygote  : accessInfo : 0
12-19 12:52:33.302  9783  9783 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.scloud 
12-19 12:52:33.302  3421  4417 I ActivityManager: Start proc 9783:com.samsung.android.scloud/5009 for broadcast-3 com.samsung.android.scloud/.receivers.SCloudReceiver
,12-19 12:52:33.312  9676  9753 D ContactInfo: Matched with previous entries!
,12-19 12:52:33.322  9783  9783 D TimaKeyStoreProvider: TimaSignature is unavailable
12-19 12:52:33.322  9783  9783 D ActivityThread: Added TimaKeyStore provider
,12-19 12:52:33.332  3421  4421 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b3fbe6e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f7cbe62 9783:com.samsung.android.scloud/5009}
,12-19 12:52:33.332  9676  9753 D PLMGenManager: Any updates for FSG and DICT? : Yes
12-19 12:52:33.332  9676  9753 D PLMGenManager: TimeTaken for Contact & App sync 374ms
,12-19 12:52:33.332  9676  9753 D etickcount:BuildCmd: Dictionary name : /data/user/0/com.sec.svoice.lang.en_US/files/en_US/dict/hero.dict
,12-19 12:52:33.342  9783  9783 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
12-19 12:52:33.342  9783  9783 D RelationGraph: garbageCollect()
,12-19 12:52:33.342  9783  9783 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.samsung.android.scloud
,12-19 12:52:33.342  9783  9783 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
12-19 12:52:33.342  3421  3853 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
12-19 12:52:33.342  9676  9753 I FSGFileGenerator:PocketSphinx: Model dir : /data/user/0/com.sec.svoice.lang.en_US/files/en_US
,12-19 12:52:33.342  9676  9753 I FSGFileGenerator:PocketSphinx: FSG : start
12-19 12:52:33.342  9783  9783 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:33.342  9676  9753 D FSGFileGenerator:PocketSphinx: Inside initFileWriter
,12-19 12:52:33.342  9676  9753 I FSGFileGenerator:PocketSphinx: templateFsgFileToRead = { /data/user/0/com.sec.svoice.lang.en_US/files/en_US/lm/hero.detmin.fsg.org, fsgFileToCreate = /data/user/0/com.sec.svoice.lang.en_US/files/en_US/lm/hero.detmin.fsg }
,12-19 12:52:33.342  9783  9783 I InjectionManager: Inside getClassLibPath caller 
12-19 12:52:33.342  9676  9753 D FSGFileGenerator:PocketSphinx: FileWriter/FileReader created
12-19 12:52:33.342  4422  9782 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package com.test.thalitest
,12-19 12:52:33.352  9783  9783 W System  : ClassLoader referenced unknown path: /system/priv-app/SamsungCloud/lib/arm64
,12-19 12:52:33.362  4422  9782 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:33.372  4422  9782 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package com.test.thalitest
,12-19 12:52:33.372  9676  9753 D FSGFileGenerator:PocketSphinx: FileWriter is closed sucessfull
12-19 12:52:33.372  9676  9753 D FSGFileGenerator:PocketSphinx: FileReader is closed sucessfull
12-19 12:52:33.372  9676  9753 D FSGFileGenerator:PocketSphinx: Inside initFileWriter
12-19 12:52:33.372  9676  9753 I FSGFileGenerator:PocketSphinx: templateFsgFileToRead = { /data/user/0/com.sec.svoice.lang.en_US/files/en_US/lm/hero.detmin.wo.wakeup.fsg.org, fsgFileToCreate = /data/user/0/com.sec.svoice.lang.en_US/files/en_US/lm/hero.detmin.wo.wakeup.fsg }
,12-19 12:52:33.372  9676  9753 D FSGFileGenerator:PocketSphinx: FileWriter/FileReader created
12-19 12:52:33.372  9783  9783 I [SC]RequestProvider: onCreate() ~!! : com.samsung.android.scloud.framework.SamsungCloudApp@624f2a1
,12-19 12:52:33.372  9783  9783 I [SC]QuotaInterfaceManager: sync start
,12-19 12:52:33.382  9783  9783 I [SC]RequestProvider: uiregister - started.
12-19 12:52:33.382  9783  9783 I [SC]RequestProvider: quotaregister - started.
,12-19 12:52:33.382  9783  9783 I [SC]ExternalOEMControlProvider: onCreate
,12-19 12:52:33.392  9676  9753 D FSGFileGenerator:PocketSphinx: FileWriter is closed sucessfull
,12-19 12:52:33.392  9676  9753 D FSGFileGenerator:PocketSphinx: FileReader is closed sucessfull
12-19 12:52:33.392  9676  9753 D FSGFileGenerator:PocketSphinx: FSG : COMPLETED in 47 ms.
12-19 12:52:33.392  9676  9753 I FSGFileGenerator:PocketSphinx: FSG : start
12-19 12:52:33.392  9676  9753 D FSGFileGenerator:PocketSphinx: Inside initFileWriter
12-19 12:52:33.392  9676  9753 I FSGFileGenerator:PocketSphinx: templateFsgFileToRead = { /data/user/0/com.sec.svoice.lang.en_US/files/en_US/lm/contact.fsg.org, fsgFileToCreate = /data/user/0/com.sec.svoice.lang.en_US/files/en_US/lm/contact.fsg }
12-19 12:52:33.392  9676  9753 D FSGFileGenerator:PocketSphinx: FileWriter/FileReader created
,12-19 12:52:33.392  9676  9753 D FSGFileGenerator:PocketSphinx: FileWriter is closed sucessfull
12-19 12:52:33.392  9676  9753 D FSGFileGenerator:PocketSphinx: FileReader is closed sucessfull
12-19 12:52:33.392  9676  9753 D FSGFileGenerator:PocketSphinx: Inside initFileWriter
,12-19 12:52:33.392  9676  9753 I FSGFileGenerator:PocketSphinx: templateFsgFileToRead = { /data/user/0/com.sec.svoice.lang.en_US/files/en_US/lm/contact.fav.fsg.org, fsgFileToCreate = /data/user/0/com.sec.svoice.lang.en_US/files/en_US/lm/contact.fav.fsg }
12-19 12:52:33.392  9676  9753 D FSGFileGenerator:PocketSphinx: FileWriter/FileReader created
,12-19 12:52:33.392  9676  9753 D FSGFileGenerator:PocketSphinx: FileWriter is closed sucessfull
12-19 12:52:33.392  9676  9753 D FSGFileGenerator:PocketSphinx: FileReader is closed sucessfull
12-19 12:52:33.392  9676  9753 D FSGFileGenerator:PocketSphinx:OWC: FSG : COMPLETED in 3 ms.
12-19 12:52:33.392  9676  9753 I DictionaryGenerator:PocketSphinx: Model dir : /data/user/0/com.sec.svoice.lang.en_US/files/en_US
12-19 12:52:33.392  9676  9753 I DictionaryGenerator:PocketSphinx: Locale : en_US
,12-19 12:52:33.392  9676  9753 I DictionaryGenerator:PocketSphinx: DFG : Start
12-19 12:52:33.392  9676  9753 D DictionaryGenerator:PocketSphinx: Inside initFileWriter : Dict file name : /data/user/0/com.sec.svoice.lang.en_US/files/en_US/dict/hero.dict
12-19 12:52:33.392  9676  9753 I DictionaryGenerator:PocketSphinx: mDictionaryFile = { /data/user/0/com.sec.svoice.lang.en_US/files/en_US/dict/hero.dict }
12-19 12:52:33.392  9676  9753 D DictionaryGenerator:PocketSphinx: FileWriter created
,12-19 12:52:33.392  9676  9753 D DictionaryGenerator:PocketSphinx: copying frm : /data/user/0/com.sec.svoice.lang.en_US/files/en_US/dict/hero.dict
,12-19 12:52:33.392  9676  9753 D DictionaryGenerator:PocketSphinx: Wakeup word is : null
12-19 12:52:33.392  9676  9753 D DictionaryGenerator:PocketSphinx: wakeup string added to dict : slot_wakeup_start__WAKEUP__slot_wakeup_end	S L AA T W EY K AH P S T AA R T W EY K AH P S L AA T W EY K AH P EH N D
12-19 12:52:33.392  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:33.402  9676  9753 I G2P     : PocketSphinxEngine:Trying to load : /data/user/0/com.sec.svoice.lang.en_US/files/en_US/libs/libG2PenUS.so
12-19 12:52:33.402  9783  9783 V SamsungCloudLogs:  set Log level [4->4]act[false]
,12-19 12:52:33.402  9783  9783 I [SC]CommonUtil: isSemAvailable:0
12-19 12:52:33.402  9783  9783 I [SC]SamsungCloudApp: AppVer[2.1.11][L:4]Sem[false]V2DEV_R slog[false]com.samsung.android.scloud
12-19 12:52:33.402  9783  9783 I [SC]SamsungCloudApp: controller allowed
,12-19 12:52:33.402  9783  9783 I [SC]MetaManager: MetaManager--[elapse:       1] Version Info[2.0.00]
,12-19 12:52:33.402  9783  9783 I [SC]FeatureManager: FeatureManager 
12-19 12:52:33.402  9783  9783 I [SC]FeatureManager: [SEC_FLOATING_FEATURE_SAMSUNGCLOUD_CONFIG_CLOUD_USAGE_MENU_TREE]str 
12-19 12:52:33.402  9783  9783 I [SC]FeatureManager: [SEC_FLOATING_FEATURE_SAMSUNGCLOUD_ENABLE_SETTING_MENU]bln true
,12-19 12:52:33.402  9783  9783 I [SC]ModelManager: ModelManager++
12-19 12:52:33.402  9783  9783 I [SC]CommonUtil: getClockPkgName pkg[com.sec.android.app.clockpackage] csc[]
12-19 12:52:33.402  9783  9783 I [SC]CommonUtil: getContactsPkgName pkg[com.android.contacts] csc[]
12-19 12:52:33.402  9783  9783 I [SC]CommonUtil: getMessagePkgName com.android.mms
,12-19 12:52:33.402  9783  9783 I [SC]CommonUtil: getEmailProviderPkgName com.samsung.android.email.provider
12-19 12:52:33.402  9783  9783 I [SC]CommonUtil: getCalendarPkgName com.android.calendar
12-19 12:52:33.402  9676  9753 I G2P     : PocketSphinxEngine:loading /data/user/0/com.sec.svoice.lang.en_US/files/en_US/libs/libG2PenUS.so done
,12-19 12:52:33.402  9783  9783 I [SC]CommonUtil: getMessagePkgName com.android.mms
12-19 12:52:33.402  9783  9783 I [SC]CommonUtil: getContactsPkgName pkg[com.android.contacts] csc[]
12-19 12:52:33.402  9783  9783 I [SC]CommonUtil: getCallPkgName com.android.incallui
12-19 12:52:33.402  9783  9783 I [SC]CommonUtil: getEmailProviderPkgName com.samsung.android.email.provider
12-19 12:52:33.402  9676  9753 V G2P-SRIB: Build date: Apr 28 2016, 15:00:24
12-19 12:52:33.402  9676  9753 V G2P-SRIB: enUS G2P libs
12-19 12:52:33.402  9676  9753 V G2P-SRIB: stringCount: 46
,12-19 12:52:33.402  9676  9753 V G2P-SRIB: Config: lang: en-US
12-19 12:52:33.402  9676  9753 V G2P-SRIB: variant: mp
12-19 12:52:33.402  9676  9753 V G2P-SRIB: prefix: slot_application_names_start__
12-19 12:52:33.402  9676  9753 V G2P-SRIB: suffix: __slot_application_names_end
12-19 12:52:33.402  9676  9753 V G2P-SRIB: Options dump_pron: W W K K K K K K K K K K K K K W W,
12-19 12:52:33.402  9676  9753 V G2P-SRIB: After conversion: Internet, Internet, 8, 8
,12-19 12:52:33.412  9783  9783 I [SC]Logs: [BaseModel]CALLLOGS                  logs                                               content://logs/historys
,12-19 12:52:33.412  9783  9783 I [SC]CommonUtil: isVoiceCallSupport : true
,12-19 12:52:33.412  9783  9783 I [SC]ModelManager: addModel[+] CALLLOGS                  isEnable[true ] --:content://logs/historys::com.android.contacts
12-19 12:52:33.412  9676  9753 V G2P-SRIB: After g2p: prons 1, max_pron_len 17
12-19 12:52:33.412  9676  9753 V G2P-SRIB: Output pron: ih n t er n eh t, i in loop: 0
12-19 12:52:33.412  9676  9753 V G2P-SRIB: After conversion: Phone, Phone, 5, 5
12-19 12:52:33.412  9783  9783 I [SC]VIPList: [BaseModel]VIPLIST                   com.samsung.android.email.provider                 content://com.samsung.android.email.provider/viplist
,12-19 12:52:33.412  9783  9783 I [SC]ModelManager: addModel[+] VIPLIST                   isEnable[true ] --:content://com.samsung.android.email.provider/viplist::com.samsung.android.email.provider
12-19 12:52:33.412  9783  9783 I [SC]BlackList: [BaseModel]BLACKLIST                 com.samsung.android.email.provider                 content://com.samsung.android.email.provider/blacklist
,12-19 12:52:33.412  9676  9753 V G2P-SRIB: After g2p: prons 1, max_pron_len 7
,12-19 12:52:33.412  9676  9753 V G2P-SRIB: Output pron: f ow n, i in loop: 0
12-19 12:52:33.412  9783  9783 I [SC]ModelManager: addModel[+] BLACKLIST                 isEnable[true ] --:content://com.samsung.android.email.provider/blacklist::com.samsung.android.email.provider
12-19 12:52:33.412  9676  9753 V G2P-SRIB: After conversion: Voice_Recorder, Voice_Recorder, 14, 14
12-19 12:52:33.412  9783  9783 I [SC]Spam: [BaseModel]SPAM                      mms-sms                                            content://mms-sms/spam-filter
,12-19 12:52:33.412  9783  9783 I [SC]ModelManager: addModel[+] SPAM                      isEnable[true ] --:content://mms-sms/spam-filter::com.android.mms
12-19 12:52:33.412  9676  9753 V G2P-SRIB: After g2p: prons 1, max_pron_len 24
12-19 12:52:33.412  9676  9753 V G2P-SRIB: Output pron: v oy s r ih k ao r d er, i in loop: 0
,12-19 12:52:33.412  9676  9753 V G2P-SRIB: After conversion: Player, Player, 6, 6
12-19 12:52:33.412  9783  9783 I [SC]CallReject: [BaseModel]CALLREJECT                com.android.phone.callsettings                     content://com.android.phone.callsettings/reject_num
12-19 12:52:33.412  9676  9753 V G2P-SRIB: After g2p: prons 1, max_pron_len 10
12-19 12:52:33.412  9676  9753 V G2P-SRIB: Output pron: p l ey er, i in loop: 0
12-19 12:52:33.412  9676  9753 V G2P-SRIB: After conversion: Word, Word, 4, 4
12-19 12:52:33.412  9676  9753 V G2P-SRIB: After g2p: prons 1, max_pron_len 7
,12-19 12:52:33.412  9676  9753 V G2P-SRIB: Output pron: w er d, i in loop: 0
12-19 12:52:33.412  9676  9753 V G2P-SRIB: After conversion: Samsung_Gear, Samsung_Gear, 12, 12
12-19 12:52:33.412  9676  9753 V G2P-SRIB: After g2p: prons 1, max_pron_len 22
12-19 12:52:33.412  9676  9753 V G2P-SRIB: Output pron: s ae m s ah ng g ih r, i in loop: 0
12-19 12:52:33.412  9676  9753 V G2P-SRIB: After conversion: schedule, schedule, 8, 8
,12-19 12:52:33.412  9676  9753 V G2P-SRIB: After g2p: prons 1, max_pron_len 15
12-19 12:52:33.412  9676  9753 V G2P-SRIB: Output pron: s k eh jh uh l, i in loop: 0
12-19 12:52:33.412  9676  9753 V G2P-SRIB: After conversion: Play_Music, Play_Music, 10, 10
12-19 12:52:33.412  9676  9753 V G2P-SRIB: After g2p: prons 1, max_pron_len 21
12-19 12:52:33.412  9676  9753 V G2P-SRIB: Output pron: p l ey m y uw z ih k, i in loop: 0
,12-19 12:52:33.412  9676  9753 V G2P-SRIB: After conversion: S_Planner, S_Planner, 9, 9
12-19 12:52:33.412  9676  9753 V G2P-SRIB: After g2p: prons 1, max_pron_len 17
12-19 12:52:33.412  9676  9753 V G2P-SRIB: Output pron: eh s p l ae n er, i in loop: 0
12-19 12:52:33.412  9676  9753 V G2P-SRIB: After conversion: Memo, Memo, 4, 4
12-19 12:52:33.412  9676  9753 V G2P-SRIB: After g2p: prons 1, max_pron_len 10
12-19 12:52:33.412  9676  9753 V G2P-SRIB: Output pron: m eh m ow, i in loop: 0
12-19 12:52:33.412  9676  9753 V G2P-SRIB: After conversion: Drive, Drive, 5, 5
,12-19 12:52:33.412  9676  9753 V G2P-SRIB: After g2p: prons 1, max_pron_len 9
12-19 12:52:33.412  9676  9753 V G2P-SRIB: Output pron: d r ay v, i in loop: 0
,12-19 12:52:33.412  9676  9753 V G2P-SRIB: After conversion: Galaxy_Apps, Galaxy_Apps, 11, 11
12-19 12:52:33.422  9676  9753 V G2P-SRIB: After g2p: prons 1, max_pron_len 24
,12-19 12:52:33.422  9676  9753 V G2P-SRIB: Output pron: g ae l ah k s iy ae p s, i in loop: 0
12-19 12:52:33.422  9676  9753 V G2P-SRIB: After conversion: Calculator, Calculator, 10, 10
12-19 12:52:33.422  9676  9753 V G2P-SRIB: After g2p: prons 1, max_pron_len 24
,12-19 12:52:33.422  9676  9753 V G2P-SRIB: Output pron: k ae l k y ah l ey t er, i in loop: 0
12-19 12:52:33.422  9676  9753 V G2P-SRIB: After conversion: Chrome, Chrome, 6, 6
12-19 12:52:33.422  9676  9753 V G2P-SRIB: After g2p: prons 1, max_pron_len 9
12-19 12:52:33.422  9676  9753 V G2P-SRIB: Output pron: k r ow m, i in loop: 0
12-19 12:52:33.422  9676  9753 V G2P-SRIB: After conversion: OneDrive, OneDrive, 8, 8
,12-19 12:52:33.422  9676  9753 V G2P-SRIB: After g2p: prons 1, max_pron_len 19
12-19 12:52:33.422  9676  9753 V G2P-SRIB: Output pron: w ah n eh d r ay v, i in loop: 0
12-19 12:52:33.422  9676  9753 V G2P-SRIB: After conversion: Instagram, Instagram, 9, 9
,12-19 12:52:33.422  9676  9753 V G2P-SRIB: After g2p: prons 1, max_pron_len 21
12-19 12:52:33.422  9676  9753 V G2P-SRIB: Output pron: ih n s t ax g r ae m, i in loop: 0
12-19 12:52:33.422  9676  9753 V G2P-SRIB: After conversion: Contacts, Contacts, 8, 8
12-19 12:52:33.422  9676  9753 V G2P-SRIB: After g2p: prons 1, max_pron_len 18
12-19 12:52:33.422  9676  9753 V G2P-SRIB: Output pron: k aa n t ae k t s, i in loop: 0
,12-19 12:52:33.422  9676  9753 V G2P-SRIB: After conversion: ThaliTest, ThaliTest, 9, 9
12-19 12:52:33.422  9676  9753 V G2P-SRIB: After g2p: prons 1, max_pron_len 20
12-19 12:52:33.422  9676  9753 V G2P-SRIB: Output pron: th ae l ay t ax s t, i in loop: 0
12-19 12:52:33.422  9676  9753 V G2P-SRIB: After conversion: WhatsApp, WhatsApp, 8, 8
12-19 12:52:33.422  9676  9753 V G2P-SRIB: After g2p: prons 1, max_pron_len 14
12-19 12:52:33.422  9676  9753 V G2P-SRIB: Output pron: w aa t s ae p, i in loop: 0
,12-19 12:52:33.422  9676  9753 V G2P-SRIB: After conversion: Messages, Messages, 8, 8
12-19 12:52:33.422  9676  9753 V G2P-SRIB: After g2p: prons 1, max_pron_len 18
12-19 12:52:33.422  9676  9753 V G2P-SRIB: Output pron: m eh s ax jh ax z, i in loop: 0
12-19 12:52:33.422  9676  9753 V G2P-SRIB: After conversion: Email, Email, 5, 5
12-19 12:52:33.422  9676  9753 V G2P-SRIB: After g2p: prons 1, max_pron_len 10
12-19 12:52:33.422  9676  9753 V G2P-SRIB: Output pron: iy m ey l, i in loop: 0
12-19 12:52:33.422  9676  9753 V G2P-SRIB: After conversion: Hangouts, Hangouts, 8, 8
12-19 12:52:33.422  9676  9753 V G2P-SRIB: After g2p: prons 1, max_pron_len 16
12-19 12:52:33.422  9676  9753 V G2P-SRIB: Output pron: hh ae ng aw t s, i in loop: 0
12-19 12:52:33.422  9676  9753 V G2P-SRIB: After conversion: OneNote, OneNote, 7, 7
12-19 12:52:33.422  9676  9753 V G2P-SRIB: After g2p: prons 1, max_pron_len 17
12-19 12:52:33.422  9676  9753 V G2P-SRIB: Output pron: w ah n ih n ow t, i in loop: 0
12-19 12:52:33.422  9676  9753 V G2P-SRIB: After conversion: calendar, calendar, 8, 8
12-19 12:52:33.422  9676  9753 V G2P-SRIB: After g2p: prons 1, max_pron_len 17
12-19 12:52:33.422  9676  9753 V G2P-SRIB: Output pron: k ae l ax n d er, i in loop: 0
12-19 12:52:33.422  9676  9753 V G2P-SRIB: After conversion: Play_Store, Play_Store, 10, 10
12-19 12:52:33.422  9676  9753 V G2P-SRIB: After g2p: prons 1, max_pron_len 16
12-19 12:52:33.422  9676  9753 V G2P-SRIB: Output pron: p l ey s t ao r, i in loop: 0
12-19 12:52:33.422  9676  9753 V G2P-SRIB: After conversion: Photos, Photos, 6, 6
12-19 12:52:33.422  9676  9753 V G2P-SRIB: After g2p: prons 1, max_pron_len 12
12-19 12:52:33.422  9676  9753 V G2P-SRIB: Output pron: f ow t ow z, i in loop: 0
12-19 12:52:33.422  9676  9753 V G2P-SRIB: After conversion: Excel, Excel, 5, 5
12-19 12:52:33.422  9676  9753 V G2P-SRIB: After g2p: prons 1, max_pron_len 12
12-19 12:52:33.422  9676  9753 V G2P-SRIB: Output pron: ih k s eh l, i in loop: 0
12-19 12:52:33.422  9676  9753 V G2P-SRIB: After conversion: Gallery, Gallery, 7, 7
12-19 12:52:33.422  9676  9753 V G2P-SRIB: After g2p: prons 1, max_pron_len 13
,12-19 12:52:33.422  9676  9753 V G2P-SRIB: Output pron: g ae l er iy, i in loop: 0
12-19 12:52:33.422  9676  9753 V G2P-SRIB: After conversion: sms, sms, 3, 3
12-19 12:52:33.432  9676  9753 V G2P-SRIB: After g2p: prons 1, max_pron_len 15
12-19 12:52:33.432  9676  9753 V G2P-SRIB: Output pron: eh s eh m eh s, i in loop: 0
12-19 12:52:33.432  9676  9753 V G2P-SRIB: After conversion: S_Health, S_Health, 8, 8
,12-19 12:52:33.432  9676  9753 V G2P-SRIB: After g2p: prons 1, max_pron_len 16
12-19 12:52:33.432  9676  9753 V G2P-SRIB: Output pron: eh s hh eh l th, i in loop: 0
12-19 12:52:33.432  9676  9753 V G2P-SRIB: After conversion: Skype, Skype, 5, 5
12-19 12:52:33.432  9676  9753 V G2P-SRIB: After g2p: prons 1, max_pron_len 9
12-19 12:52:33.432  9676  9753 V G2P-SRIB: Output pron: s k ay p, i in loop: 0
12-19 12:52:33.432  9676  9753 V G2P-SRIB: After conversion: alarm, alarm, 5, 5
,12-19 12:52:33.432  9676  9753 V G2P-SRIB: After g2p: prons 1, max_pron_len 12
12-19 12:52:33.432  9676  9753 V G2P-SRIB: Output pron: ah l aa r m, i in loop: 0
12-19 12:52:33.432  9676  9753 V G2P-SRIB: After conversion: Voice_Search, Voice_Search, 12, 12
12-19 12:52:33.432  9676  9753 V G2P-SRIB: After g2p: prons 1, max_pron_len 15
,12-19 12:52:33.432  9676  9753 V G2P-SRIB: Output pron: v oy s s er ch, i in loop: 0
12-19 12:52:33.432  9676  9753 V G2P-SRIB: After conversion: Play_Movies_&_TV, Play_Movies_&_TV, 16, 16
,12-19 12:52:33.432  9783  9783 I [SC]CommonUtil: isVoiceCallSupport : true
,12-19 12:52:33.432  9783  9783 I [SC]ModelManager: addModel[+] CALLREJECT                isEnable[true ] --:content://com.android.phone.callsettings/reject_num::com.android.incallui
,12-19 12:52:33.432  9783  9783 I [SC]ConnectionsSetting: [BaseModel]CONNECTIONS               com.android.settings.accessibility.sharedaccessibility.backup content://com.android.settings.accessibility.sharedaccessibility.backup
,12-19 12:52:33.432  9676  9753 V G2P-SRIB: After g2p: prons 4, max_pron_len 49
12-19 12:52:33.432  9676  9753 V G2P-SRIB: Output pron: p l ey m uw v iy z ah n d t iy v iy, i in loop: 0
12-19 12:52:33.432  9676  9753 V G2P-SRIB: Output pron: p l ey m uw v iy z ae n d t iy v iy, i in loop: 1
12-19 12:52:33.432  9676  9753 V G2P-SRIB: Output pron: p l ey m uw v iy z ah n d t eh l ah v ih zh ah n, i in loop: 2
12-19 12:52:33.432  9676  9753 V G2P-SRIB: Output pron: p l ey m uw v iy z ae n d t eh l ah v ih zh ah n, i in loop: 3
12-19 12:52:33.432  9676  9753 V G2P-SRIB: After conversion: My_Files, My_Files, 8, 8
12-19 12:52:33.432  9676  9753 V G2P-SRIB: After g2p: prons 1, max_pron_len 14
12-19 12:52:33.432  9676  9753 V G2P-SRIB: Output pron: m ay f ay l z, i in loop: 0
12-19 12:52:33.432  9676  9753 V G2P-SRIB: After conversion: Maps, Maps, 4, 4
12-19 12:52:33.432  9676  9753 V G2P-SRIB: After g2p: prons 1, max_pron_len 9
12-19 12:52:33.432  9676  9753 V G2P-SRIB: Output pron: m ae p s, i in loop: 0
12-19 12:52:33.432  9676  9753 V G2P-SRIB: After conversion: Clock, Clock, 5, 5
,12-19 12:52:33.432  9676  9753 V G2P-SRIB: After g2p: prons 1, max_pron_len 9
12-19 12:52:33.432  9676  9753 V G2P-SRIB: Output pron: k l aa k, i in loop: 0
12-19 12:52:33.432  9676  9753 V G2P-SRIB: After conversion: Settings, Settings, 8, 8
,12-19 12:52:33.432  9676  9753 V G2P-SRIB: After g2p: prons 1, max_pron_len 15
12-19 12:52:33.432  9676  9753 V G2P-SRIB: Output pron: s eh t ih ng z, i in loop: 0
12-19 12:52:33.432  9676  9753 V G2P-SRIB: After conversion: s_planner, s_planner, 9, 9
,12-19 12:52:33.442  9676  9753 V G2P-SRIB: After g2p: prons 1, max_pron_len 17
12-19 12:52:33.442  9676  9753 V G2P-SRIB: Output pron: eh s p l ae n er, i in loop: 0
12-19 12:52:33.442  9676  9753 V G2P-SRIB: After conversion: PowerPoint, PowerPoint, 10, 10
,12-19 12:52:33.442  9676  9753 V G2P-SRIB: After g2p: prons 1, max_pron_len 17
12-19 12:52:33.442  9676  9753 V G2P-SRIB: Output pron: p aw er p oy n t, i in loop: 0
12-19 12:52:33.442  9676  9753 V G2P-SRIB: After conversion: Facebook, Facebook, 8, 8
,12-19 12:52:33.442  9676  9753 V G2P-SRIB: After g2p: prons 1, max_pron_len 14
12-19 12:52:33.442  9676  9753 V G2P-SRIB: Output pron: f ey s b uh k, i in loop: 0
12-19 12:52:33.442  9676  9753 V G2P-SRIB: After conversion: Gmail, Gmail, 5, 5
12-19 12:52:33.442  9676  9753 V G2P-SRIB: After g2p: prons 1, max_pron_len 9
12-19 12:52:33.442  9676  9753 V G2P-SRIB: Output pron: g m ey l, i in loop: 0
12-19 12:52:33.442  9676  9753 V G2P-SRIB: After conversion: YouTube, YouTube, 7, 7
,12-19 12:52:33.442  9676  9753 V G2P-SRIB: After g2p: prons 1, max_pron_len 12
12-19 12:52:33.442  9676  9753 V G2P-SRIB: Output pron: y uw t uw b, i in loop: 0
12-19 12:52:33.442  9676  9753 V G2P-SRIB: After conversion: diary, diary, 5, 5
,12-19 12:52:33.442  9676  9753 V G2P-SRIB: After g2p: prons 1, max_pron_len 11
12-19 12:52:33.442  9676  9753 V G2P-SRIB: Output pron: d ay er iy, i in loop: 0
12-19 12:52:33.442  9676  9753 V G2P-SRIB: After conversion: Camera, Camera, 6, 6
,12-19 12:52:33.442  9676  9753 V G2P-SRIB: After g2p: prons 1, max_pron_len 13
12-19 12:52:33.442  9676  9753 V G2P-SRIB: Output pron: k ae m er ax, i in loop: 0
12-19 12:52:33.442  9676  9753 V G2P-SRIB: After conversion: Google, Google, 6, 6
,12-19 12:52:33.442  9676  9753 V G2P-SRIB: After g2p: prons 1, max_pron_len 12
12-19 12:52:33.442  9676  9753 V G2P-SRIB: Output pron: g uw g ax l, i in loop: 0
12-19 12:52:33.442  9676  9753 V G2P-SRIB: First char , last char 
12-19 12:52:33.442  9676  9753 V G2P-SRIB: Before UTF release deinit
12-19 12:52:33.442  9676  9753 V G2P-SRIB: Before g2p deinit
,12-19 12:52:33.442  9676  9753 D DictionaryGenerator:PocketSphinx: FileWriter is closed sucessfull
,12-19 12:52:33.442  9676  9753 D DictionaryGenerator:PocketSphinx: DFG : COMPLETED in 51 ms.
12-19 12:52:33.442  9676  9753 I DictionaryGenerator:PocketSphinx:OWC: DFG : Start
12-19 12:52:33.442  9676  9753 D DictionaryGenerator:PocketSphinx: Inside initFileWriter : Dict file name : /data/user/0/com.sec.svoice.lang.en_US/files/en_US/dict/contact.dict
12-19 12:52:33.442  9676  9753 I DictionaryGenerator:PocketSphinx: mDictionaryFile = { /data/user/0/com.sec.svoice.lang.en_US/files/en_US/dict/contact.dict }
12-19 12:52:33.442  9676  9753 D DictionaryGenerator:PocketSphinx: FileWriter created
12-19 12:52:33.442  9676  9753 D DictionaryGenerator:PocketSphinx: copying frm : /data/user/0/com.sec.svoice.lang.en_US/files/en_US/dict/contact.dict
,12-19 12:52:33.442  9676  9753 D DictionaryGenerator:PocketSphinx: inside process_one_word_Call
12-19 12:52:33.442  9676  9753 D DictionaryGenerator:PocketSphinx: /data/user/0/com.sec.svoice.lang.en_US/databases
,12-19 12:52:33.442  9783  9783 I [SC]ModelManager: addModel[+] CONNECTIONS               isEnable[false] --:content://com.android.settings.accessibility.sharedaccessibility.backup::com.android.settings
,12-19 12:52:33.452  9783  9783 I [SC]RingtoneSetting: [BaseModel]RINGTONESETTING           null                                               null
,12-19 12:52:33.452  4166  4177 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg com.google.android.googlequicksearchbox,id=10436,extra=Bundle[mParcelledData.dataSize=84]
,12-19 12:52:33.452  4166  4166 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=10436, samsung.notification.type=normal, samsung.people.package_name=com.google.android.googlequicksearchbox}]
12-19 12:52:33.452  4166  4166 I PeopleStripeService: PeopleNotificationReceiver:3
12-19 12:52:33.452  4166  4166 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
12-19 12:52:33.452  4166  4166 I PeopleDataManager: removeNotification
12-19 12:52:33.452  4166  4166 I NotificationParser: getNotiType:com.google.android.googlequicksearchbox,null
12-19 12:52:33.452  4166  4166 D PeopleDataManager: removeNotiInfo: id =10436,packageName=com.google.android.googlequicksearchbox,isEdgeNotification=false,key=null,removeAll=false
12-19 12:52:33.452  4166  4166 D PeopleDataManager: removeNotiInfo =null
,12-19 12:52:33.452  9783  9783 I [SC]ModelManager: addModel[+] RINGTONESETTING           isEnable[true ] --:null::com.sec.android.app.ringtoneBR
,12-19 12:52:33.452  9783  9783 I [SC]Music: [BaseModel]MUSIC                     null                                               null
12-19 12:52:33.452  9783  9783 I [SC]ModelManager: addModel[+] MUSIC                     isEnable[true ] --:null::com.samsung.android.scloud
12-19 12:52:33.452  9676  9753 D DictionaryGenerator:PocketSphinx::OWC: Deleted below entries : 
12-19 12:52:33.452  9676  9753 D DictionaryGenerator:PocketSphinx::OWC: Newly added entries are : 
12-19 12:52:33.452  9676  9753 V G2P-SRIB: Build date: Apr 28 2016, 15:00:24
12-19 12:52:33.452  9676  9753 V G2P-SRIB: enUS G2P libs
,12-19 12:52:33.452  9676  9753 V G2P-SRIB: stringCount: 0
12-19 12:52:33.452  9676  9753 V G2P-SRIB: Config: lang: en-US
12-19 12:52:33.452  9676  9753 V G2P-SRIB: variant: mp
12-19 12:52:33.452  9676  9753 V G2P-SRIB: prefix: slot_contacts_start__
12-19 12:52:33.452  9676  9753 V G2P-SRIB: suffix: __slot_contacts_end
12-19 12:52:33.452  9676  9753 V G2P-SRIB: Options dump_pron: W W K K K K K K K K K K K K K W W,
12-19 12:52:33.452  9676  9753 V G2P-SRIB: First char , last char �
12-19 12:52:33.452  9676  9753 V G2P-SRIB: Before UTF release deinit
12-19 12:52:33.452  9676  9753 V G2P-SRIB: Before g2p deinit
12-19 12:52:33.452  9783  9783 I [SC]Document: [BaseModel]DOCUMENT                  null                                               null
12-19 12:52:33.452  9783  9783 I [SC]ModelManager: addModel[+] DOCUMENT                  isEnable[true ] --:null::com.samsung.android.scloud
,12-19 12:52:33.462  9676  9753 D DictionaryGenerator:PocketSphinx: FileWriter is closed sucessfull
12-19 12:52:33.462  9676  9753 D DictionaryGenerator:PocketSphinx:OWC: DFG : COMPLETED in 15 ms.
12-19 12:52:33.462  9676  9753 D PLMGenManager: TimeTaken for Dict & FSG generation 123ms
12-19 12:52:33.462  9676  9753 D etickcount:PocketSphinx Recognition Engine:  : VSP::TimeTaken for syncUserData 498ms
,12-19 12:52:33.462  9783  9783 I [SC]Application: [BaseModel]APP                       null                                               null
,12-19 12:52:33.462  9783  9783 I [SC]ModelManager: addModel[+] APP                       isEnable[true ] --:null::com.samsung.android.scloud
,12-19 12:52:33.462  9783  9783 I [SC]Home: [BaseModel]HomescreenBackup          com.sec.android.app.launcher                       content://com.sec.android.app.launcher
12-19 12:52:33.462  9783  9783 I [SC]ModelManager: addModel[+] HomescreenBackup          isEnable[true ] --:content://com.sec.android.app.launcher::com.sec.android.app.launcher
,12-19 12:52:33.462  9783  9783 W ResourcesManager: getTopLevelResources: /system/priv-app/VoiceNote_4.0/VoiceNote_4.0.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.sec.android.app.voicenote
,12-19 12:52:33.462  9676  9753 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : #en_us_v2.0.6
12-19 12:52:33.462  9783  9783 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:33.462  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP::#en_us_v2.0.6
12-19 12:52:33.462  9676  9753 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : ##General
12-19 12:52:33.462  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP::##General
12-19 12:52:33.462  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP::-hmm	am
12-19 12:52:33.462  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP::-fsg	lm/hero.detmin.fsg
12-19 12:52:33.462  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP::-fsg2,	lm/hero.detmin.wo.wakeup.fsg
12-19 12:52:33.462  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP::-dict	dict/hero.dict
12-19 12:52:33.472  9676  9753 I eN66    : JNI Enter Function Java_com_asr_pocketsphinx_pocketsphinxJNI_Config_1setNLUCfg
12-19 12:52:33.472  9676  9753 I eN66    : Library build date: May  2 2016 @ 14:31:17
12-19 12:52:33.472  9676  9753 I eN66    : JNI Config_setNLUCfg /data/user/0/com.sec.svoice.lang.en_US/files/en_US/nlu/nlu.cfg
12-19 12:52:33.472  9676  9753 I eN66    : JNI debug Config_setNLUCfg /data/user/0/com.sec.svoice.lang.en_US/files/en_US/nlu/nlu.cfg 1 time
,12-19 12:52:33.472  9676  9753 I eN66    : JNI Exit Function Java_com_asr_pocketsphinx_pocketsphinxJNI_Config_1setNLUCfg
12-19 12:52:33.472  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP::-rnlu	nlu/nlu.cfg
12-19 12:52:33.472  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP::-maxwpf	4
12-19 12:52:33.472  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP::-maxhmmpf	1800
,12-19 12:52:33.472  9676  9753 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : #-rawlogdir
12-19 12:52:33.472  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP::#-rawlogdir	log
12-19 12:52:33.472  9676  9753 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : 
12-19 12:52:33.472  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP::
,12-19 12:52:33.472  9676  9753 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : ##DNN
12-19 12:52:33.472  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP::##DNN
12-19 12:52:33.472  9783  9783 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.samsung.android.email.provider
,12-19 12:52:33.472  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP::-context	11
12-19 12:52:33.472  9676  9753 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : #quantization range
12-19 12:52:33.472  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP::#quantization range
12-19 12:52:33.472  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP::-QRange	1024
12-19 12:52:33.472  9676  9753 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : #1 means not skipped, 2 means skip every 2 frames
12-19 12:52:33.472  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP::#1 means not skipped, 2 means skip every 2 frames
12-19 12:52:33.472  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP::-frmskip	1
,12-19 12:52:33.472  9676  9753 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : #quantized dnn binary file (not using dnn)
12-19 12:52:33.472  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP::#quantized dnn binary file (not using dnn)
12-19 12:52:33.472  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP::-qdnn	am/qdnn.net
12-19 12:52:33.472  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP::-feat_transform	am/feat.bin
,12-19 12:52:33.472  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP::-prior	am/prior_prob.out
12-19 12:52:33.472  9676  9753 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : 
12-19 12:52:33.472  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP::
12-19 12:52:33.472  9676  9753 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : ##Confidence score
12-19 12:52:33.472  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP::##Confidence score
,12-19 12:52:33.472  9676  9753 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : #-confs
12-19 12:52:33.472  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP::#-confs	yes
12-19 12:52:33.472  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP::-conf_use_senone	0
12-19 12:52:33.472  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP::-conf_use_pls	0
12-19 12:52:33.472  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP::-conf_use_ll	1
12-19 12:52:33.472  9783  9783 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:33.472  9783  9783 I [SC]ExternalOEMControl_VOICE: updateModelInfo() called, src[VOICE] cid[vMkD7IBgaR] isNew[true] dataType[null]
12-19 12:52:33.472  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP::-pip	1.5
12-19 12:52:33.472  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP::-wip	7
12-19 12:52:33.472  9783  9783 I [SC]ExternalModel: [BaseModel]VOICE                     com.sec.android.app.voicenote                      content://com.sec.android.app.voicenote.backup
12-19 12:52:33.472  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP::-lw	3
12-19 12:52:33.472  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP::-dnn_ascale	2.5
12-19 12:52:33.472  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP::-prior_ratio	0.92
12-19 12:52:33.472  9783  9783 I [SC]ExternalModel: duplicateConfig[0] : true
12-19 12:52:33.472  9783  9783 I [SC]ExternalModel: duplicateConfig[1] : false
12-19 12:52:33.472  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP::-conf_mapscore_params	[-42,0,-18,50,-4,100][9,0,28,50,57,100][-12,0,10,50,24,100]
,12-19 12:52:33.472  9783  9783 I [SC]ModelManager: addModel[+] VOICE                     isEnable[true ] V2:content://com.sec.android.app.voicenote.backup::com.sec.android.app.voicenote
12-19 12:52:33.472  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP::-non_speech_tied_states	[93:94:95]
12-19 12:52:33.472  9783  9783 I [SC]ModelManager: loadExternalModelsFromPkg[VOICE                                        ] pkg:com.sec.android.app.voicenote                 register[IFileClient:vMkD7IBgaR]
12-19 12:52:33.472  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP::-conf_disagreement_percent	20.0
,12-19 12:52:33.472  9676  9753 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : 
12-19 12:52:33.472  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP::
12-19 12:52:33.472  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP::-conf_max_llr_th	25
12-19 12:52:33.472  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP::-conf_use_ci	no
12-19 12:52:33.472  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP::-bestpath	0
,12-19 12:52:33.472  9676  9753 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : #now phoneloop score is not used phoneloop score => senon score
,12-19 12:52:33.472  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP::#now phoneloop score is not used phoneloop score => senon score
12-19 12:52:33.472  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP::-pl_window	0
12-19 12:52:33.472  9676  9753 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : #excluding silence frames in score
12-19 12:52:33.472  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP::#excluding silence frames in score
,12-19 12:52:33.472  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP::-no_silence	1
12-19 12:52:33.472  9676  9753 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : #mapping parameter
12-19 12:52:33.472  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP::#mapping parameter
12-19 12:52:33.472  9676  9753 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : #-lang
12-19 12:52:33.472  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP::#-lang	1
,12-19 12:52:33.472  9676  9753 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : #excluding score on WUW
12-19 12:52:33.472  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP::#excluding score on WUW
12-19 12:52:33.472  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP::-wake-up-cmd	1
12-19 12:52:33.472  9676  9753 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : 
12-19 12:52:33.482  9783  9783 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.sec.android.app.sbrowser
12-19 12:52:33.472  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP::
12-19 12:52:33.472  9676  9753 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : ##Rejection
,12-19 12:52:33.472  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP::##Rejection
12-19 12:52:33.472  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP::-reject_list	lm/reject.hyp
12-19 12:52:33.472  9676  9753 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : 
12-19 12:52:33.472  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP::
12-19 12:52:33.472  9676  9753 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : ##Android related
12-19 12:52:33.472  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP::##Android related
12-19 12:52:33.472  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP::-conf_thresh	49
,12-19 12:52:33.472  9676  9753 D etickcount:PocketSphinx Recognition Engine:  : VSP::Previous state : INIT,
12-19 12:52:33.472  9676  9753 I eN66    : JNI Enter Function Java_com_asr_pocketsphinx_pocketsphinxJNI_new_1Decoder_1_1SWIG_11
12-19 12:52:33.482  9783  9783 D ResourcesManager: For user 0 new overlays fetched Null
12-19 12:52:33.472  9676  9753 I eN66    : ps_reinit start
12-19 12:52:33.472  9676  9753 I eN66    : configured dir of hmm /data/user/0/com.sec.svoice.lang.en_US/files/en_US/am
,12-19 12:52:33.472  9676  9753 I eN66    : ps_init_defaults end
12-19 12:52:33.482  9783  9783 I [SC]ExternalOEMControlLegacy_Email: updateModelInfo() called, src[Email] cid[QJ5JBlRnP9] isNew[true]
12-19 12:52:33.482  9783  9783 I [SC]ExternalModelLegacy: [BaseModel]Email                     com.samsung.android.email.provider                 content://com.samsung.android.email.provider.backup[Q]
12-19 12:52:33.482  9783  9783 I [SC]ModelManager: addModel[+] Email                     isEnable[true ] V1:content://com.samsung.android.email.provider.backup::com.samsung.android.email.provider:[Q]
12-19 12:52:33.482  9783  9783 I [SC]ModelManager: loadExternalModelsFromPkg[Email                                        ] pkg:com.samsung.android.email.provider            register[ISCloudQBNRClient:QJ5JBlRnP9]
12-19 12:52:33.482  4422  9782 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 189 ms] updated apps [took 189 ms] 
,12-19 12:52:33.482  9783  9783 I [SC]ExternalOEMControlLegacy_SBROWSERSETTING: updateModelInfo() called, src[SBROWSERSETTING] cid[kw8vqQFzo3] isNew[true]
12-19 12:52:33.482  9783  9783 I [SC]ExternalModelLegacy: [BaseModel]SBROWSERSETTING           com.sec.android.app.sbrowser                       content://com.sec.android.app.sbrowser.backup[Q]
12-19 12:52:33.482  9783  9783 I [SC]ModelManager: addModel[+] SBROWSERSETTING           isEnable[true ] V1:content://com.sec.android.app.sbrowser.backup::com.sec.android.app.sbrowser:[Q]
12-19 12:52:33.482  9783  9783 I [SC]ModelManager: loadExternalModelsFromPkg[SBROWSERSETTING                              ] pkg:com.sec.android.app.sbrowser                  register[ISCloudQBNRClient:kw8vqQFzo3]
,12-19 12:52:33.482  9783  9783 W ResourcesManager: getTopLevelResources: /system/priv-app/SVoice_1.0/SVoice_1.0.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.samsung.voiceserviceplatform
,12-19 12:52:33.492  9783  9783 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:33.492  9783  9783 I [SC]ExternalOEMControlLegacy_SVOICESETTING: updateModelInfo() called, src[SVOICESETTING] cid[bLEmzxKOex] isNew[true]
12-19 12:52:33.492  9783  9783 I [SC]ExternalModelLegacy: [BaseModel]SVOICESETTING             com.samsung.voiceserviceplatform                   content://com.samsung.voiceserviceplatform.backup[Q]
12-19 12:52:33.492  9783  9783 I [SC]ModelManager: addModel[+] SVOICESETTING             isEnable[true ] V1:content://com.samsung.voiceserviceplatform.backup::com.samsung.voiceserviceplatform:[Q]
12-19 12:52:33.492  9783  9783 I [SC]ModelManager: loadExternalModelsFromPkg[SVOICESETTING                                ] pkg:com.samsung.voiceserviceplatform              register[ISCloudQBNRClient:bLEmzxKOex]
,12-19 12:52:33.492  9783  9783 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M/SPlanner_M.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.android.calendar
,12-19 12:52:33.492  9783  9783 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:33.492  9783  9783 I [SC]ExternalOEMControlLegacy_CALENDARSETTING: updateModelInfo() called, src[CALENDARSETTING] cid[ztQlGIvsvZ] isNew[true]
12-19 12:52:33.492  9783  9783 I [SC]ExternalModelLegacy: [BaseModel]CALENDARSETTING           com.android.calendar                               content://com.android.calendar.backup[Q]
12-19 12:52:33.492  9783  9783 I [SC]ModelManager: addModel[+] CALENDARSETTING           isEnable[true ] V1:content://com.android.calendar.backup::com.android.calendar:[Q]
12-19 12:52:33.492  9783  9783 I [SC]ModelManager: loadExternalModelsFromPkg[CALENDARSETTING                              ] pkg:com.android.calendar                          register[ISCloudQBNRClient:ztQlGIvsvZ]
,12-19 12:52:33.502  9783  9783 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.android.settings
,12-19 12:52:33.502  9783  9783 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:33.502  9783  9783 I [SC]ExternalOEMControlLegacy_ACCESSIBILITYSETTINGS: updateModelInfo() called, src[ACCESSIBILITYSETTINGS] cid[X6qErjsfs2] isNew[true]
12-19 12:52:33.502  9783  9783 I [SC]ExternalModelLegacy: [BaseModel]ACCESSIBILITYSETTINGS     com.android.settings                               content://com.android.settings.accessibility.sharedaccessibility.backup[Q]
12-19 12:52:33.502  9783  9783 I [SC]ModelManager: addModel[+] ACCESSIBILITYSETTINGS     isEnable[true ] V1:content://com.android.settings.accessibility.sharedaccessibility.backup::com.android.settings:[Q]
12-19 12:52:33.502  9783  9783 I [SC]ModelManager: loadExternalModelsFromPkg[ACCESSIBILITYSETTINGS                        ] pkg:com.android.settings                          register[ISCloudQBNRClient:X6qErjsfs2]
,12-19 12:52:33.502  9783  9783 I [SC]ModelManager: loadExternalModelsFromPkg[CONNECTIONS                                  ] pkg:com.android.settings                          subKey[CONNECTIONS]
12-19 12:52:33.502  9783  9783 I [SC]ConnectionsSetting: CONNECTIONS               setEnable[true]
12-19 12:52:33.502  9783  9783 I [SC]ModelManager: loadExternalModelsFromPkg[CONNECTIONS                                  ] pkg:com.android.settings                          subKey[WiFi]
12-19 12:52:33.502  9783  9783 I [SC]ConnectionsSetting: CONNECTIONS               setEnable[true]
,12-19 12:52:33.502  9783  9783 W ResourcesManager: getTopLevelResources: /system/priv-app/TouchWizHome_2016/TouchWizHome_2016.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.sec.android.app.launcher
,12-19 12:52:33.502  9783  9783 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:33.512  9783  9783 E [SC]SCLOUD_ERR-CommonUtil: getCertificateSHA1Fingerprint err :com.samsung.android.scloud.backupsamplecode 
12-19 12:52:33.512  9783  9783 I [SC]ModelManager: loadExternalModelsFromPkg pkg:com.samsung.android.scloud.backupsamplecode   NotExist[null]
,12-19 12:52:33.512  9783  9783 W ResourcesManager: getTopLevelResources: /system/priv-app/TeleService/TeleService.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.android.phone
,12-19 12:52:33.512  9783  9783 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:33.512  9783  9783 I [SC]ExternalOEMControlLegacy_CALLSETTING: updateModelInfo() called, src[CALLSETTING] cid[IHLhQxraiP] isNew[true]
12-19 12:52:33.512  9783  9783 I [SC]ExternalModelLegacy: [BaseModel]CALLSETTING               com.android.phone                                  content://com.android.phone.backup[Q]
12-19 12:52:33.512  9783  9783 I [SC]ModelManager: addModel[+] CALLSETTING               isEnable[true ] V1:content://com.android.phone.backup::com.android.phone:[Q]
12-19 12:52:33.512  9783  9783 I [SC]ModelManager: loadExternalModelsFromPkg[CALLSETTING                                  ] pkg:com.android.phone                             register[ISCloudQBNRClient:IHLhQxraiP]
,12-19 12:52:33.512  9783  9783 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.sec.android.inputmethod
,12-19 12:52:33.512  9783  9783 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:33.522  9783  9783 I [SC]ExternalOEMControlLegacy_IMESETTING: updateModelInfo() called, src[IMESETTING] cid[ghXxWAP1aK] isNew[true]
12-19 12:52:33.522  9783  9783 I [SC]ExternalModelLegacy: [BaseModel]IMESETTING                com.sec.android.inputmethod                        content://com.sec.android.inputmethod.backup[Q]
12-19 12:52:33.522  9783  9783 I [SC]ModelManager: addModel[+] IMESETTING                isEnable[true ] V1:content://com.sec.android.inputmethod.backup::com.sec.android.inputmethod:[Q]
12-19 12:52:33.522  9783  9783 I [SC]ModelManager: loadExternalModelsFromPkg[IMESETTING                                   ] pkg:com.sec.android.inputmethod                   register[ISCloudQBNRClient:ghXxWAP1aK]
,12-19 12:52:33.522  9783  9783 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.android.contacts
,12-19 12:52:33.522  9783  9783 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:33.522  9783  9783 I [SC]ExternalOEMControlLegacy_MyProfile: updateModelInfo() called, src[MyProfile] cid[2yOE2P9maz] isNew[true]
12-19 12:52:33.522  9783  9783 I [SC]ExternalModelLegacy: [BaseModel]MyProfile                 com.android.contacts                               content://com.samsung.contacts.backup
12-19 12:52:33.522  9783  9783 I [SC]ModelManager: addModel[+] MyProfile                 isEnable[true ] V1:content://com.samsung.contacts.backup::com.android.contacts:
12-19 12:52:33.522  9783  9783 I [SC]ModelManager: loadExternalModelsFromPkg[MyProfile                                    ] pkg:com.android.contacts                          register[ISCloudBNRClient:2yOE2P9maz]
12-19 12:52:33.522  9783  9783 I [SC]ExternalOEMControlLegacy_CONTACTSETTING: updateModelInfo() called, src[CONTACTSETTING] cid[jqwmo66Bdc] isNew[true]
12-19 12:52:33.522  9783  9783 I [SC]ExternalModelLegacy: [BaseModel]CONTACTSETTING            com.android.contacts                               content://com.samsung.contacts.backup[Q]
12-19 12:52:33.522  9783  9783 I [SC]ModelManager: addModel[+] CONTACTSETTING            isEnable[true ] V1:content://com.samsung.contacts.backup::com.android.contacts:[Q]
12-19 12:52:33.522  9783  9783 I [SC]ModelManager: loadExternalModelsFromPkg[CONTACTSETTING                               ] pkg:com.android.contacts                          register[ISCloudQBNRClient:jqwmo66Bdc]
12-19 12:52:33.522  9783  9783 I [SC]ExternalOEMControl_CONTACT: updateModelInfo() called, src[CONTACT] cid[2vInYbEf2V] isNew[true] dataType[json]
12-19 12:52:33.522  9783  9783 I [SC]ExternalModel: [BaseModel]CONTACT                   com.android.contacts                               content://com.samsung.contacts.backup
12-19 12:52:33.522  9783  9783 I [SC]ModelManager: addModel[+] CONTACT                   isEnable[true ] V2:content://com.samsung.contacts.backup::com.android.contacts
12-19 12:52:33.522  9783  9783 I [SC]ModelManager: loadExternalModelsFromPkg[CONTACT                                      ] pkg:com.android.contacts                          register[IRecordClient:2vInYbEf2V]
12-19 12:52:33.522  9783  9783 I [SC]ModelManager: loadExternalModelsFromPkg[HomescreenBackup                             ] pkg:com.android.contacts                          subKey[HomescreenContactShortcut]
,12-19 12:52:33.522  9783  9783 W ResourcesManager: getTopLevelResources: /system/app/ClockPackage_M/ClockPackage_M.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.sec.android.app.clockpackage
,12-19 12:52:33.532  9783  9783 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:33.532  9783  9783 I [SC]ExternalOEMControlLegacy_Alarm: updateModelInfo() called, src[Alarm] cid[v5VJ0Ep6EE] isNew[true]
,12-19 12:52:33.532  9783  9783 I [SC]ExternalModelLegacy: [BaseModel]Alarm                     com.sec.android.app.clockpackage                   content://com.sec.android.app.clockpackage
12-19 12:52:33.532  9783  9783 I [SC]ModelManager: addModel[+] Alarm                     isEnable[true ] V1:content://com.sec.android.app.clockpackage::com.sec.android.app.clockpackage:
12-19 12:52:33.532  9783  9783 I [SC]ModelManager: loadExternalModelsFromPkg[Alarm                                        ] pkg:com.sec.android.app.clockpackage              register[ISCloudBNRClient:v5VJ0Ep6EE]
12-19 12:52:33.532  9783  9783 I [SC]ExternalOEMControlLegacy_WorldClock: updateModelInfo() called, src[WorldClock] cid[pYz7p28bSl] isNew[true]
12-19 12:52:33.532  9783  9783 I [SC]ExternalModelLegacy: [BaseModel]WorldClock                com.sec.android.app.clockpackage                   content://com.sec.android.app.clockpackage
12-19 12:52:33.532  9783  9783 I [SC]ModelManager: addModel[+] WorldClock                isEnable[true ] V1:content://com.sec.android.app.clockpackage::com.sec.android.app.clockpackage:
12-19 12:52:33.532  9783  9783 I [SC]ModelManager: loadExternalModelsFromPkg[WorldClock                                   ] pkg:com.sec.android.app.clockpackage              register[ISCloudBNRClient:pYz7p28bSl]
12-19 12:52:33.532  9783  9783 I [SC]ModelManager: loadExternalModelsFromPkg[HomescreenBackup                             ] pkg:com.sec.android.app.clockpackage              subKey[ALARMWIDGET]
12-19 12:52:33.532  9783  9783 I [SC]ModelManager: loadExternalModelsFromPkg[HomescreenBackup                             ] pkg:com.sec.android.app.clockpackage              subKey[DUALCLOCKWIDGET]
,12-19 12:52:33.532  9783  9783 W ResourcesManager: getTopLevelResources: /system/priv-app/SecCalendarProvider_NOTSTICKER/SecCalendarProvider_NOTSTICKER.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.android.providers.calendar
,12-19 12:52:33.532  9783  9783 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:33.532  9783  9783 I [SC]ExternalOEMControl_EVENT: updateModelInfo() called, src[EVENT] cid[qsoHwGCEEw] isNew[true] dataType[json]
12-19 12:52:33.532  9783  9783 I [SC]ExternalModel: [BaseModel]EVENT                     com.android.providers.calendar                     content://com.samsung.android.providers.calendar.backup
12-19 12:52:33.532  9783  9783 I [SC]ModelManager: addModel[+] EVENT                     isEnable[true ] V2:content://com.samsung.android.providers.calendar.backup::com.android.providers.calendar
12-19 12:52:33.532  9783  9783 I [SC]ModelManager: loadExternalModelsFromPkg[EVENT                                        ] pkg:com.android.providers.calendar                register[IRecordClient:qsoHwGCEEw]
12-19 12:52:33.532  9783  9783 I [SC]ExternalOEMControl_TASK: updateModelInfo() called, src[TASK] cid[cLT79jJ29l] isNew[true] dataType[json]
12-19 12:52:33.532  9783  9783 I [SC]ExternalModel: [BaseModel]TASK                      com.android.providers.calendar                     content://com.samsung.android.providers.calendar.backup
,12-19 12:52:33.532  9783  9783 I [SC]ModelManager: addModel[+] TASK                      isEnable[true ] V2:content://com.samsung.android.providers.calendar.backup::com.android.providers.calendar
12-19 12:52:33.532  9783  9783 I [SC]ModelManager: loadExternalModelsFromPkg[TASK                                         ] pkg:com.android.providers.calendar                register[IRecordClient:cLT79jJ29l]
,12-19 12:52:33.532  9783  9783 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Epic_Common/SecMms_Epic_Common.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.android.mms
,12-19 12:52:33.542  9783  9783 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:33.542  9783  9783 I [SC]ExternalOEMControlLegacy_MessagesSettings: updateModelInfo() called, src[MessagesSettings] cid[XUHtHcYNfq] isNew[true]
12-19 12:52:33.542  9783  9783 I [SC]ExternalModelLegacy: [BaseModel]MessagesSettings          com.android.mms                                    content://com.samsung.mms.settings.backup[Q]
12-19 12:52:33.542  9783  9783 I [SC]ModelManager: addModel[+] MessagesSettings          isEnable[true ] V1:content://com.samsung.mms.settings.backup::com.android.mms:[Q]
12-19 12:52:33.542  9783  9783 I [SC]ModelManager: loadExternalModelsFromPkg[MessagesSettings                             ] pkg:com.android.mms                               register[ISCloudQBNRClient:XUHtHcYNfq]
,12-19 12:52:33.542  9783  9783 W ResourcesManager: getTopLevelResources: /system/priv-app/SecTelephonyProvider_Epic/SecTelephonyProvider_Epic.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.android.providers.telephony
,12-19 12:52:33.542  9783  9783 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:33.542  9783  9783 I [SC]ExternalOEMControlLegacy_Chat: updateModelInfo() called, src[Chat] cid[nx7Fde25jd] isNew[true]
,12-19 12:52:33.542  4298  4726 I [PDLIB]ClientProvider, VERSION : 2.2.0: call !!  method : getClientInfo, arg : Chat
12-19 12:52:33.542  4298  4726 D TP/BnRUtils: getCscFreeMessage(), config = off
12-19 12:52:33.542  4298  4726 D TP/BnRUtils: getEnableSupportBackup() = false
12-19 12:52:33.542  4298  4726 I [PDLIB]BNRClientHelper-Chat: GET_CLIENT_INFO, Chat
,12-19 12:52:33.542  9783  9783 I [SC]ExternalOEMControlLegacy_Chat: updateModelInfo() supportBnr is false
,12-19 12:52:33.542  9783  9783 I [SC]ExternalOEMControlLegacy_FileTransfer: updateModelInfo() called, src[FileTransfer] cid[LyxMGTa8W3] isNew[true]
,12-19 12:52:33.542  4298  5434 I [PDLIB]ClientProvider, VERSION : 2.2.0: call !!  method : getClientInfo, arg : FileTransfer
12-19 12:52:33.542  4298  5434 D TP/BnRUtils: getCscFreeMessage(), config = off
12-19 12:52:33.542  4298  5434 D TP/BnRUtils: getEnableSupportBackup() = false
12-19 12:52:33.542  4298  5434 I [PDLIB]BNRClientHelper-FileTransfer: GET_CLIENT_INFO, FileTransfer
,12-19 12:52:33.542  9783  9783 I [SC]ExternalOEMControlLegacy_FileTransfer: updateModelInfo() supportBnr is false
,12-19 12:52:33.542  9783  9783 I [SC]ExternalOEMControl_SMS: updateModelInfo() called, src[SMS] cid[N0iXqXm9oM] isNew[true] dataType[json]
12-19 12:52:33.542  9783  9783 I [SC]ExternalModel: [BaseModel]SMS                       com.android.providers.telephony                    content://com.android.providers.telephony.backup
12-19 12:52:33.542  9783  9783 I [SC]ModelManager: addModel[+] SMS                       isEnable[true ] V2:content://com.android.providers.telephony.backup::com.android.providers.telephony
12-19 12:52:33.542  9783  9783 I [SC]ModelManager: loadExternalModelsFromPkg[SMS                                          ] pkg:com.android.providers.telephony               register[IRecordClient:N0iXqXm9oM]
12-19 12:52:33.542  9783  9783 I [SC]ExternalOEMControl_MMS: updateModelInfo() called, src[MMS] cid[I7o6E6m1Lj] isNew[true] dataType[json]
12-19 12:52:33.542  9783  9783 I [SC]ExternalModel: [BaseModel]MMS                       com.android.providers.telephony                    content://com.android.providers.telephony.backup
12-19 12:52:33.542  9783  9783 I [SC]ModelManager: addModel[+] MMS                       isEnable[true ] V2:content://com.android.providers.telephony.backup::com.android.providers.telephony
12-19 12:52:33.542  9783  9783 I [SC]ModelManager: loadExternalModelsFromPkg[MMS                                          ] pkg:com.android.providers.telephony               register[IRecordClient:I7o6E6m1Lj]
,12-19 12:52:33.552  9783  9783 W ResourcesManager: getTopLevelResources: /system/app/WeatherWidget2016/WeatherWidget2016.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.sec.android.daemonapp
,12-19 12:52:33.552  9783  9783 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:33.552  9783  9783 I [SC]ExternalOEMControlLegacy_WEATHERWIDGET: updateModelInfo() called, src[WEATHERWIDGET] cid[oo2JSUuSBb] isNew[true]
,12-19 12:52:33.552  9783  9783 I [SC]ExternalModelLegacy: [BaseModel]WEATHERWIDGET             com.sec.android.daemonapp                          content://com.sec.android.daemonapp.backup[Q]
12-19 12:52:33.552  9783  9783 I [SC]ModelManager: addModel[+] WEATHERWIDGET             isEnable[true ] V1:content://com.sec.android.daemonapp.backup::com.sec.android.daemonapp:[Q]
12-19 12:52:33.552  9783  9783 I [SC]ModelManager: loadExternalModelsFromPkg[WEATHERWIDGET                                ] pkg:com.sec.android.daemonapp                     register[ISCloudQBNRClient:oo2JSUuSBb]
,12-19 12:52:33.552  9783  9783 I [SC]ModelManager: loadExternalModelsFromPkg[elapse:      92]
12-19 12:52:33.552  9783  9783 I [SC]ModelManager: ModelManager--[elapse:     150]
,12-19 12:52:33.572  9783  9783 D InjectionManager: InjectionManager
,12-19 12:52:33.572  9783  9783 D InjectionManager: fillFeatureStoreMap com.samsung.android.scloud
12-19 12:52:33.572  9783  9783 I InjectionManager: Constructor com.samsung.android.scloud, Feature store :{}
12-19 12:52:33.572  9783  9783 I InjectionManager: featureStore :{}
,12-19 12:52:33.572  9783  9783 I [SC]SCloudReceiver: onReceive : android.intent.action.PACKAGE_ADDED
,12-19 12:52:33.572  9676  9753 I eN66    : 
12-19 12:52:33.572  9676  9753 I eN66    : FSG model <n66_cmd_eng> is loaded
,12-19 12:52:33.572  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:33.582  9804  9804 E Zygote  : v2
12-19 12:52:33.582  9804  9804 I libpersona: KNOX_SDCARD checking this for 1000
12-19 12:52:33.582  9804  9804 I libpersona: KNOX_SDCARD not a persona
,12-19 12:52:33.582  9804  9804 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0029
,12-19 12:52:33.582  9804  9804 E Zygote  : accessInfo : 0
,12-19 12:52:33.592  3421  3474 I ActivityManager: Start proc 9804:com.samsung.android.bbc.bbcagent/1000 for broadcast-3 com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver
,12-19 12:52:33.592  3421  3474 I ActivityManager: Killing 9108:com.google.android.apps.photos/u0a135 (adj 15): DHA:empty #33
,12-19 12:52:33.602  9676  9753 I eN66    : 
12-19 12:52:33.602  9676  9753 I eN66    : ps_reinit : Secondary FSG model <n66_cmd_eng> is loaded
12-19 12:52:33.602  9676  9753 I eN66    : 
12-19 12:52:33.602  9676  9753 I eN66    : ps_reinit : Current active FSG model is <n66_cmd_eng>
12-19 12:52:33.602  9676  9753 I eN66    : Decoder initialization is complete
12-19 12:52:33.602  9676  9753 I eN66    : JNI Exit Function Java_com_asr_pocketsphinx_pocketsphinxJNI_new_1Decoder_1_1SWIG_11 Instance -184835104
12-19 12:52:33.602  9676  9753 I etickcount:PocketSphinx Recognition Engine:  : VSP::State changed to READY
12-19 12:52:33.602  9676  9753 D etickcount:PocketSphinx Recognition Engine:  : VSP::TimeTaken for Decoder init 142ms
12-19 12:52:33.602  9676  9753 D etickcount:PocketSphinx Recognition Engine:  : VSP::Total Load time 679ms
,12-19 12:52:33.602  9804  9804 D TimaKeyStoreProvider: TimaSignature is unavailable
12-19 12:52:33.602  9804  9804 D ActivityThread: Added TimaKeyStore provider
,12-19 12:52:33.622  3421  3983 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b3fbe6e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{95f97dc 9804:com.samsung.android.bbc.bbcagent/1000}
,12-19 12:52:33.622  3421  4333 D ActivityManager: isAutoRunBlockedApp:: com.google.android.apps.photos, Auto Run ON
,12-19 12:52:33.622  9804  9804 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
12-19 12:52:33.622  9804  9804 D RelationGraph: garbageCollect()
,12-19 12:52:33.622  9804  9804 W ResourcesManager: getTopLevelResources: /system/app/BBCAgent/BBCAgent.apk / 1.0 running in com.samsung.android.bbc.bbcagent rsrc of package com.samsung.android.bbc.bbcagent
,12-19 12:52:33.632  3421  3984 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
12-19 12:52:33.632  9804  9804 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,12-19 12:52:33.632  9804  9804 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:33.632  9804  9804 I InjectionManager: Inside getClassLibPath caller 
,12-19 12:52:33.642  9804  9804 W System  : ClassLoader referenced unknown path: /system/app/BBCAgent/lib/arm64
,12-19 12:52:33.642  9804  9804 D InjectionManager: InjectionManager
,12-19 12:52:33.642  9804  9804 D InjectionManager: fillFeatureStoreMap com.samsung.android.bbc.bbcagent
12-19 12:52:33.642  9804  9804 I InjectionManager: Constructor com.samsung.android.bbc.bbcagent, Feature store :{}
12-19 12:52:33.642  9804  9804 I InjectionManager: featureStore :{}
,12-19 12:52:33.662  9816  9816 E Zygote  : v2
,12-19 12:52:33.662  9816  9816 I libpersona: KNOX_SDCARD checking this for 10098
12-19 12:52:33.662  9816  9816 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0029
12-19 12:52:33.662  9816  9816 I libpersona: KNOX_SDCARD not a persona
,12-19 12:52:33.662  9816  9816 E Zygote  : accessInfo : 0
12-19 12:52:33.662  9816  9816 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.docs 
12-19 12:52:33.662  3421  3981 I ActivityManager: Start proc 9816:com.google.android.apps.docs/u0a98 for broadcast-3 com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,12-19 12:52:33.662  3421  3981 I ActivityManager: Killing 9263:com.sec.android.service.health/u0a26 (adj 15): DHA:empty #33
,12-19 12:52:33.682  9816  9816 D TimaKeyStoreProvider: TimaSignature is unavailable
,12-19 12:52:33.682  9816  9816 D ActivityThread: Added TimaKeyStore provider
,12-19 12:52:33.682  3421  4417 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.service.health, Auto Run ON
,12-19 12:52:33.702  3421  3984 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b3fbe6e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e20e0e5 9816:com.google.android.apps.docs/u0a98}
,12-19 12:52:33.702  9816  9816 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
12-19 12:52:33.702  9816  9816 D RelationGraph: garbageCollect()
,12-19 12:52:33.712  9816  9816 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package com.google.android.apps.docs
,12-19 12:52:33.712  3421  4182 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
12-19 12:52:33.712  9816  9816 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,12-19 12:52:33.712  9816  9816 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:33.712  9816  9816 I InjectionManager: Inside getClassLibPath caller 
,12-19 12:52:33.722  9816  9816 W System  : ClassLoader referenced unknown path: /system/app/Drive/lib/arm64
,12-19 12:52:33.752  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:33.862  3421  6185 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-19 12:52:33.882  9816  9830 I GAv4    : Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
12-19 12:52:33.882  9816  9830 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
12-19 12:52:33.882  9816  9830 I GAv4    :   adb logcat -s GAv4
,12-19 12:52:33.902  9816  9830 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package com.google.android.apps.docs
,12-19 12:52:33.902  3421  4989 V AlarmManager:  remove PendingIntent] PendingIntent{183a661: PendingIntentRecord{1c59586 com.google.android.apps.docs broadcastIntent}}
,12-19 12:52:33.902  9816  9830 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,12-19 12:52:33.912  9816  9830 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,12-19 12:52:33.912  9816  9834 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,12-19 12:52:33.932  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:33.962  3421  3908 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/20_task.xml.bak
,12-19 12:52:33.962  9816  9816 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.apps.docs/cache/docs_glide
,12-19 12:52:33.972  9816  9830 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db
12-19 12:52:33.972  9816  9830 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-journal
12-19 12:52:33.972  9816  9830 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-shm
12-19 12:52:33.972  9816  9830 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-wal
,12-19 12:52:33.982  9816  9816 D InjectionManager: InjectionManager
12-19 12:52:33.982  9816  9816 D InjectionManager: fillFeatureStoreMap com.google.android.apps.docs
,12-19 12:52:33.982  9816  9816 I InjectionManager: Constructor com.google.android.apps.docs, Feature store :{}
12-19 12:52:33.982  9816  9816 I InjectionManager: featureStore :{}
,12-19 12:52:34.002  9839  9839 E Zygote  : v2
12-19 12:52:34.002  9839  9839 I libpersona: KNOX_SDCARD checking this for 1000
12-19 12:52:34.002  9839  9839 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0029
12-19 12:52:34.002  9839  9839 I libpersona: KNOX_SDCARD not a persona
,12-19 12:52:34.002  9839  9839 E Zygote  : accessInfo : 0
,12-19 12:52:34.002  3421  4182 I ActivityManager: Start proc 9839:com.samsung.android.app.filterinstaller/1000 for broadcast-3 com.samsung.android.app.filterinstaller/.PackageIntentReceiver
,12-19 12:52:34.002  3421  4182 I ActivityManager: Killing 9237:com.samsung.android.app.FileShareServer/5005 (adj 15): DHA:empty #33
,12-19 12:52:34.022  9839  9839 D TimaKeyStoreProvider: TimaSignature is unavailable
12-19 12:52:34.022  9839  9839 D ActivityThread: Added TimaKeyStore provider
,12-19 12:52:34.032  3421  3983 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b3fbe6e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ed58412 9839:com.samsung.android.app.filterinstaller/1000}
,12-19 12:52:34.042  3421  4420 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.FileShareServer, Auto Run ON
,12-19 12:52:34.042  9839  9839 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
12-19 12:52:34.042  9839  9839 D RelationGraph: garbageCollect()
,12-19 12:52:34.042  9839  9839 W ResourcesManager: getTopLevelResources: /system/app/FilterInstaller/FilterInstaller.apk / 1.0 running in com.samsung.android.app.filterinstaller rsrc of package com.samsung.android.app.filterinstaller
,12-19 12:52:34.042  9839  9839 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
12-19 12:52:34.042  3421  3984 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,12-19 12:52:34.052  9839  9839 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:34.052  9839  9839 I InjectionManager: Inside getClassLibPath caller 
,12-19 12:52:34.062  9839  9839 W System  : ClassLoader referenced unknown path: /system/app/FilterInstaller/lib/arm64
,12-19 12:52:34.062  9816  9831 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in com.google.android.apps.docs rsrc of package com.google.android.gms
,12-19 12:52:34.062  9839  9839 D InjectionManager: InjectionManager
12-19 12:52:34.062  9839  9839 D InjectionManager: fillFeatureStoreMap com.samsung.android.app.filterinstaller
12-19 12:52:34.062  9839  9839 I InjectionManager: Constructor com.samsung.android.app.filterinstaller, Feature store :{}
12-19 12:52:34.062  9839  9839 I InjectionManager: featureStore :{}
,12-19 12:52:34.062  9839  9839 E FilterPackageIntentReceiver: This package is not a effect filter
,12-19 12:52:34.062  9816  9831 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:34.072  9816  9831 I InjectionManager: Inside getClassLibPath caller 
,12-19 12:52:34.072  9854  9854 E Zygote  : v2
12-19 12:52:34.072  9854  9854 I libpersona: KNOX_SDCARD checking this for 10110
12-19 12:52:34.072  9854  9854 I libpersona: KNOX_SDCARD not a persona
12-19 12:52:34.072  9854  9854 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0029
,12-19 12:52:34.082  9854  9854 E Zygote  : accessInfo : 0
12-19 12:52:34.082  9854  9854 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.sec.android.widgetapp.samsungapps 
12-19 12:52:34.082  3421  3474 I ActivityManager: Start proc 9854:com.sec.android.widgetapp.samsungapps/u0a110 for broadcast-3 com.sec.android.widgetapp.samsungapps/.PackageChangeReceiver
,12-19 12:52:34.082  3421  3474 I ActivityManager: Killing 9250:com.enhance.gameservice/u0a111 (adj 15): DHA:empty #33
,12-19 12:52:34.092  9854  9854 D TimaKeyStoreProvider: TimaSignature is unavailable
12-19 12:52:34.092  9854  9854 D ActivityThread: Added TimaKeyStore provider
,12-19 12:52:34.102  3421  4989 D ActivityManager: isAutoRunBlockedApp:: com.enhance.gameservice, Auto Run ON
,12-19 12:52:34.102  9816  9831 W System  : ClassLoader referenced unknown path: /system/priv-app/GmsCore/lib/arm64
,12-19 12:52:34.112  3421  4333 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b3fbe6e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{712e7e3 9854:com.sec.android.widgetapp.samsungapps/u0a110}
,12-19 12:52:34.122  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:34.122  9854  9854 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
12-19 12:52:34.122  9854  9854 D RelationGraph: garbageCollect()
,12-19 12:52:34.122  9854  9854 W ResourcesManager: getTopLevelResources: /system/app/GalaxyAppsWidget_Phone_Hero/GalaxyAppsWidget_Phone_Hero.apk / 1.0 running in com.sec.android.widgetapp.samsungapps rsrc of package com.sec.android.widgetapp.samsungapps
,12-19 12:52:34.122  3421  4616 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
12-19 12:52:34.122  9854  9854 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,12-19 12:52:34.122  9854  9854 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:34.122  9854  9854 I InjectionManager: Inside getClassLibPath caller 
,12-19 12:52:34.132  9854  9854 W System  : ClassLoader referenced unknown path: /system/app/GalaxyAppsWidget_Phone_Hero/lib/arm64
,12-19 12:52:34.142  9854  9854 D InjectionManager: InjectionManager
,12-19 12:52:34.142  9854  9854 D InjectionManager: fillFeatureStoreMap com.sec.android.widgetapp.samsungapps
12-19 12:52:34.142  9854  9854 I InjectionManager: Constructor com.sec.android.widgetapp.samsungapps, Feature store :{}
12-19 12:52:34.142  9854  9854 I InjectionManager: featureStore :{}
,12-19 12:52:34.152  9868  9868 E Zygote  : v2
12-19 12:52:34.152  9868  9868 I libpersona: KNOX_SDCARD checking this for 10111
12-19 12:52:34.152  9868  9868 I libpersona: KNOX_SDCARD not a persona
12-19 12:52:34.152  9868  9868 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0029
,12-19 12:52:34.152  9868  9868 E Zygote  : accessInfo : 0
12-19 12:52:34.152  9868  9868 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.enhance.gameservice 
,12-19 12:52:34.162  3421  4333 I ActivityManager: Start proc 9868:com.enhance.gameservice/u0a111 for broadcast-3 com.enhance.gameservice/.GameServiceReceiver
,12-19 12:52:34.162  3421  4333 I ActivityManager: Killing 9275:com.samsung.android.app.watchmanagerstub/u0a112 (adj 15): DHA:empty #33
,12-19 12:52:34.172  9868  9868 D TimaKeyStoreProvider: TimaSignature is unavailable
12-19 12:52:34.172  9868  9868 D ActivityThread: Added TimaKeyStore provider
,12-19 12:52:34.172  9816  9831 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,12-19 12:52:34.182  3421  4415 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b3fbe6e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{24615e0 9868:com.enhance.gameservice/u0a111}
,12-19 12:52:34.182  3421  3474 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.watchmanagerstub, Auto Run ON
,12-19 12:52:34.192  9868  9868 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
12-19 12:52:34.192  9868  9868 D RelationGraph: garbageCollect()
,12-19 12:52:34.192  9868  9868 W ResourcesManager: getTopLevelResources: /system/app/GameOptimizer/GameOptimizer.apk / 1.0 running in com.enhance.gameservice rsrc of package com.enhance.gameservice
,12-19 12:52:34.192  9816  9831 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,12-19 12:52:34.192  3421  3984 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
12-19 12:52:34.192  9868  9868 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,12-19 12:52:34.192  9868  9868 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:34.192  9868  9868 I InjectionManager: Inside getClassLibPath caller 
,12-19 12:52:34.202  9868  9868 W System  : ClassLoader referenced unknown path: /system/app/GameOptimizer/lib/arm64
,12-19 12:52:34.202  9868  9868 D InjectionManager: InjectionManager
,12-19 12:52:34.202  9868  9868 D InjectionManager: fillFeatureStoreMap com.enhance.gameservice
12-19 12:52:34.202  9868  9868 I InjectionManager: Constructor com.enhance.gameservice, Feature store :{}
12-19 12:52:34.202  9868  9868 I InjectionManager: featureStore :{}
,12-19 12:52:34.212  9868  9880 I DatabaseHelper: android.app.Application@92e8cc6
12-19 12:52:34.212  9868  9880 I DatabaseHelper: Create a DatabaseHelper
,12-19 12:52:34.222  9882  9882 E Zygote  : v2
12-19 12:52:34.222  9882  9882 I libpersona: KNOX_SDCARD checking this for 1000
12-19 12:52:34.222  9882  9882 I libpersona: KNOX_SDCARD not a persona
12-19 12:52:34.222  9882  9882 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0029
,12-19 12:52:34.222  9882  9882 E Zygote  : accessInfo : 0
12-19 12:52:34.222  3421  4415 I ActivityManager: Start proc 9882:com.samsung.android.app.mirrorlink/1000 for broadcast-3 com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener
,12-19 12:52:34.232  9868  9880 W RequestHeader: java.lang.StringIndexOutOfBoundsException: length=0; regionStart=0; regionLength=3
,12-19 12:52:34.232  9868  9880 I DataManager: checkResolution
12-19 12:52:34.232  9868  9880 I DataManager: Create a DataManager
,12-19 12:52:34.242  9868  9880 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,12-19 12:52:34.242  9868  9880 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,12-19 12:52:34.242  9882  9882 D TimaKeyStoreProvider: TimaSignature is unavailable
12-19 12:52:34.242  9882  9882 D ActivityThread: Added TimaKeyStore provider
,12-19 12:52:34.242  3153  3634 D EnterpriseController: netId is 0
,12-19 12:52:34.242  3153  3634 D Netd    : getNetworkForDns: using netid 502 for uid 10111
,12-19 12:52:34.252  3421  4421 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b3fbe6e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{383cf5e 9882:com.samsung.android.app.mirrorlink/1000}
,12-19 12:52:34.262  9882  9882 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
12-19 12:52:34.262  9882  9882 D RelationGraph: garbageCollect()
,12-19 12:52:34.262  9882  9882 W ResourcesManager: getTopLevelResources: /system/app/MirrorLink/MirrorLink.apk / 1.0 running in com.samsung.android.app.mirrorlink rsrc of package com.samsung.android.app.mirrorlink
,12-19 12:52:34.262  3421  3981 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
12-19 12:52:34.262  9882  9882 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,12-19 12:52:34.262  9882  9882 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:34.272  9882  9882 I InjectionManager: Inside getClassLibPath caller 
,12-19 12:52:34.272  9882  9882 W System  : ClassLoader referenced unknown path: /system/app/MirrorLink/lib/arm
,12-19 12:52:34.292  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:34.302  9882  9882 D InjectionManager: InjectionManager
12-19 12:52:34.302  9882  9882 D InjectionManager: fillFeatureStoreMap com.samsung.android.app.mirrorlink
,12-19 12:52:34.302  9882  9882 I InjectionManager: Constructor com.samsung.android.app.mirrorlink, Feature store :{}
12-19 12:52:34.302  9882  9882 I InjectionManager: featureStore :{}
,12-19 12:52:34.302  9882  9882 D AcmsPackageEventListener: action2:android.intent.action.PACKAGE_ADDED
12-19 12:52:34.302  9882  9882 D AcmsPackageEventListener: pkgName:com.test.thalitest ,10078
,12-19 12:52:34.302  3421  4421 I ActivityManager: Killing 9065:com.samsung.android.app.assistantmenu/1000 (adj 15): DHA:empty #33
,12-19 12:52:34.312  3421  4421 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b3fbe6e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a13bedb 4873:com.microsoft.skydrive/u0a130}
,12-19 12:52:34.322  4873  4873 V ApplicationReceiver: 2016-12-19 11:52:34-null-Application install message is received ver:1.1.10
,12-19 12:52:34.322  4873  4873 V ApplicationReceiver: 2016-12-19 11:52:34-null-Installing:package:com.test.thalitest ver:1.1.10
,12-19 12:52:34.322  3421  4333 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.assistantmenu, Auto Run ON
,12-19 12:52:34.342  9895  9895 E Zygote  : v2
12-19 12:52:34.342  9895  9895 I libpersona: KNOX_SDCARD checking this for 10141
12-19 12:52:34.342  9895  9895 I libpersona: KNOX_SDCARD not a persona
,12-19 12:52:34.342  9895  9895 E Zygote  : isSdpEnabledProcess - SDP enabled
,12-19 12:52:34.342  9895  9895 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0029
,12-19 12:52:34.342  9895  9895 E Zygote  : accessInfo : 64
12-19 12:52:34.342  9895  9895 E Zygote  : isSdpEnabledProcess - SDP enabled
12-19 12:52:34.342  9895  9895 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10141 / [uid]: 10141
12-19 12:52:34.352  9895  9895 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.sbrowser 
12-19 12:52:34.352  3421  3983 I ActivityManager: Start proc 9895:com.sec.android.app.sbrowser/u0a141 for broadcast-3 com.sec.android.app.sbrowser/.preferences.ContentBlockerReceiver
,12-19 12:52:34.362  9895  9895 D TimaKeyStoreProvider: TimaSignature is unavailable
12-19 12:52:34.362  9895  9895 D ActivityThread: Added TimaKeyStore provider
,12-19 12:52:34.382  3421  4570 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b3fbe6e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9021f3f 9895:com.sec.android.app.sbrowser/u0a141}
,12-19 12:52:34.382  9895  9895 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
12-19 12:52:34.382  9895  9895 D RelationGraph: garbageCollect()
,12-19 12:52:34.382  9895  9895 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package com.sec.android.app.sbrowser
,12-19 12:52:34.392  3421  3472 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,12-19 12:52:34.392  9895  9895 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,12-19 12:52:34.392  9895  9895 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:34.392  9895  9895 I InjectionManager: Inside getClassLibPath caller 
,12-19 12:52:34.392  4242  9752 D FusedRequestManager: manageLocationRequest, new fused (NO_POWER) request from com.samsung.voiceserviceplatform with 10043_NOPOWER through GooglePlayService
,12-19 12:52:34.402  9895  9895 W System  : ClassLoader referenced unknown path: /system/app/SBrowser_4_LATEST/lib/arm
,12-19 12:52:34.412  9895  9895 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package com.sec.android.app.sbrowser
,12-19 12:52:34.412  9895  9895 D ManifestProvider: onCreate()
,12-19 12:52:34.412  9895  9895 I SBrowserUtils: getSystemProperty of sales_code : XEO
12-19 12:52:34.412  9895  9895 I SBrowserUtils: getSystemProperty of country_code : Poland
12-19 12:52:34.412  9895  9895 I SBrowserUtils: getSystemProperty of country_code : Poland
12-19 12:52:34.412  9895  9895 I SBrowserUtils: getSystemProperty of countryiso_code : PL
,12-19 12:52:34.422  9895  9895 V SBrowserContentProviderUtility: enableSyncClientProivder is called!
,12-19 12:52:34.422  9895  9895 D [MM]MHDataBaseProvider: onCreate()
,12-19 12:52:34.432  9895  9895 D ApplicationStatus: initialize application (com.sec.android.app.sbrowser.common.SBrowserMobileApplication@54b5f8)
,12-19 12:52:34.442  9895  9895 D InjectionManager: InjectionManager
,12-19 12:52:34.442  9895  9895 D InjectionManager: fillFeatureStoreMap com.sec.android.app.sbrowser
12-19 12:52:34.442  9895  9895 I InjectionManager: Constructor com.sec.android.app.sbrowser, Feature store :{}
12-19 12:52:34.442  9895  9895 I InjectionManager: featureStore :{}
,12-19 12:52:34.442  3421  3474 I ActivityManager: Killing 9294:com.sec.android.app.popupuireceiver/1000 (adj 15): DHA:empty #33
,12-19 12:52:34.452  3421  3474 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b3fbe6e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e723f5c 5096:com.sec.imsservice/1000}
,12-19 12:52:34.462  3421  4421 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.popupuireceiver, Auto Run ON
,12-19 12:52:34.472  3421  6150 D GameManagerService: identifyGamePackage. com.test.thalitest
,12-19 12:52:34.482  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:34.482  4637  7403 I Icing   : Indexing 5C970AF099F6E45AC5F7CE88D00EDBB4B63BF8D6 from com.google.android.googlequicksearchbox
,12-19 12:52:34.482  9910  9910 E Zygote  : v2
,12-19 12:52:34.482  9910  9910 I libpersona: KNOX_SDCARD checking this for 10016
12-19 12:52:34.482  9910  9910 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0029
12-19 12:52:34.482  9910  9910 I libpersona: KNOX_SDCARD not a persona
,12-19 12:52:34.482  9910  9910 E Zygote  : accessInfo : 0
12-19 12:52:34.482  3421  3474 I ActivityManager: Start proc 9910:com.sec.android.app.samsungapps/u0a16 for broadcast-3 com.sec.android.app.samsungapps/.MyPackageReplacedReceiver
12-19 12:52:34.482  9910  9910 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.sec.android.app.samsungapps 
,12-19 12:52:34.492  3421  3856 D NetworkPolicy: isUidForegroundLocked: 10016, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,12-19 12:52:34.492  3421  3856 D NetworkPolicy: isUidForegroundLocked: 10016, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,12-19 12:52:34.502  9910  9910 D TimaKeyStoreProvider: TimaSignature is unavailable
12-19 12:52:34.502  9910  9910 D ActivityThread: Added TimaKeyStore provider
,12-19 12:52:34.512  3421  3984 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b3fbe6e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{526b00c 9910:com.sec.android.app.samsungapps/u0a16}
,12-19 12:52:34.522  9910  9910 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
12-19 12:52:34.522  9910  9910 D RelationGraph: garbageCollect()
,12-19 12:52:34.522  9910  9910 W ResourcesManager: getTopLevelResources: /data/app/com.sec.android.app.samsungapps-2/base.apk / 1.0 running in com.sec.android.app.samsungapps rsrc of package com.sec.android.app.samsungapps
,12-19 12:52:34.522  3421  3474 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
12-19 12:52:34.522  9910  9910 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,12-19 12:52:34.522  9910  9910 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:34.532  9910  9910 I InjectionManager: Inside getClassLibPath caller 
,12-19 12:52:34.532  9910  9910 W System  : ClassLoader referenced unknown path: /data/app/com.sec.android.app.samsungapps-2/lib/arm64
,12-19 12:52:34.542  9910  9910 W ResourcesManager: getTopLevelResources: /data/app/com.sec.android.app.samsungapps-2/base.apk / 1.0 running in com.sec.android.app.samsungapps rsrc of package com.sec.android.app.samsungapps
,12-19 12:52:34.562  4637  7403 I Icing   : Indexing done 5C970AF099F6E45AC5F7CE88D00EDBB4B63BF8D6
,12-19 12:52:34.562  9910  9910 V deviceInfo: NetworkOperator_MCC : 
12-19 12:52:34.562  9910  9910 V deviceInfo: MCC value is not correct
,12-19 12:52:34.582  9910  9910 V deviceInfo: NetworkOperator_MCC : 
12-19 12:52:34.582  9910  9910 V deviceInfo: MCC value is not correct
,12-19 12:52:34.592  9910  9910 V deviceInfo: NetworkOperator_MNC : 
,12-19 12:52:34.622  9910  9910 D Sppmt   : Test mode:false, cfgFileExist:false, canWrite:false
,12-19 12:52:34.632  9910  9910 D InjectionManager: InjectionManager
12-19 12:52:34.632  9910  9910 D InjectionManager: fillFeatureStoreMap com.sec.android.app.samsungapps
,12-19 12:52:34.632  9910  9910 I InjectionManager: Constructor com.sec.android.app.samsungapps, Feature store :{}
12-19 12:52:34.632  9910  9910 I InjectionManager: featureStore :{}
,12-19 12:52:34.632  9910  9910 D [SAUI]  : Global::recovered::false
,12-19 12:52:34.642  9929  9929 E Zygote  : v2
12-19 12:52:34.642  9929  9929 I libpersona: KNOX_SDCARD checking this for 10014
12-19 12:52:34.642  9929  9929 I libpersona: KNOX_SDCARD not a persona
12-19 12:52:34.642  9929  9929 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0029
,12-19 12:52:34.642  9929  9929 E Zygote  : accessInfo : 0
12-19 12:52:34.652  9929  9929 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.facebook.system 
12-19 12:52:34.652  3421  4182 I ActivityManager: Start proc 9929:com.facebook.system/u0a14 for broadcast-3 com.facebook.system/com.facebook.oxygen.installer.service.PackageReceiver
,12-19 12:52:34.662  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:34.662  3421  4616 I ActivityManager: Killing 9307:com.samsung.android.sm/1000 (adj 15): DHA:empty #33
,12-19 12:52:34.662  9929  9929 D TimaKeyStoreProvider: TimaSignature is unavailable
12-19 12:52:34.662  9929  9929 D ActivityThread: Added TimaKeyStore provider
,12-19 12:52:34.672  3421  4570 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b3fbe6e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{639836a 9929:com.facebook.system/u0a14}
,12-19 12:52:34.682  9929  9929 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
12-19 12:52:34.682  9929  9929 D RelationGraph: garbageCollect()
,12-19 12:52:34.682  9929  9929 W ResourcesManager: getTopLevelResources: /data/app/com.facebook.system-2/base.apk / 1.0 running in com.facebook.system rsrc of package com.facebook.system
,12-19 12:52:34.682  3421  3474 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sm, Auto Run ON
12-19 12:52:34.682  3421  4616 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,12-19 12:52:34.682  9929  9929 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,12-19 12:52:34.682  9929  9929 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:34.692  9929  9929 I InjectionManager: Inside getClassLibPath caller 
,12-19 12:52:34.692  9929  9929 W System  : ClassLoader referenced unknown path: /data/app/com.facebook.system-2/lib/arm64
,12-19 12:52:34.702  9929  9929 D InjectionManager: InjectionManager
12-19 12:52:34.702  9929  9929 D InjectionManager: fillFeatureStoreMap com.facebook.system
,12-19 12:52:34.702  9929  9929 I InjectionManager: Constructor com.facebook.system, Feature store :{}
12-19 12:52:34.702  9929  9929 I InjectionManager: featureStore :{}
,12-19 12:52:34.712  9941  9941 E Zygote  : v2
12-19 12:52:34.712  9941  9941 I libpersona: KNOX_SDCARD checking this for 10103
12-19 12:52:34.712  9941  9941 I libpersona: KNOX_SDCARD not a persona
12-19 12:52:34.712  9941  9941 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0029
,12-19 12:52:34.712  9941  9941 E Zygote  : accessInfo : 0
12-19 12:52:34.712  9941  9941 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.facebook.appmanager 
12-19 12:52:34.712  3421  4417 I ActivityManager: Start proc 9941:com.facebook.appmanager/u0a103 for broadcast-3 com.facebook.appmanager/com.facebook.oxygen.appmanager.common.packages.PackageReceiver
,12-19 12:52:34.712  3421  4417 I ActivityManager: Killing 8727:com.google.android.talk/u0a117 (adj 15): DHA:empty #33
,12-19 12:52:34.732  9941  9941 D TimaKeyStoreProvider: TimaSignature is unavailable
12-19 12:52:34.732  9941  9941 D ActivityThread: Added TimaKeyStore provider
,12-19 12:52:34.742  3421  4333 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b3fbe6e u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a83705b 9941:com.facebook.appmanager/u0a103}
,12-19 12:52:34.742  9941  9941 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
12-19 12:52:34.742  9941  9941 D RelationGraph: garbageCollect()
,12-19 12:52:34.742  3421  4421 D ActivityManager: isAutoRunBlockedApp:: com.google.android.talk, Auto Run ON
,12-19 12:52:34.752  9941  9941 W ResourcesManager: getTopLevelResources: /data/app/com.facebook.appmanager-2/base.apk / 1.0 running in com.facebook.appmanager rsrc of package com.facebook.appmanager
,12-19 12:52:34.752  3421  3853 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
12-19 12:52:34.752  9941  9941 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,12-19 12:52:34.752  9941  9941 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:34.752  9941  9941 I InjectionManager: Inside getClassLibPath caller 
,12-19 12:52:34.762  9941  9941 D ACRA    : ACRA init; reportURL: https://www.facebook.com/mobile/generic_android_crash_logs/659091980805095
,12-19 12:52:34.762  9941  9941 D ACRA    : ACRA is enabled for com.facebook.appmanager, intializing...
,12-19 12:52:34.772  9941  9941 V fb-UnpackingSoSource: locked dso store /data/user/0/com.facebook.appmanager/lib-main
,12-19 12:52:34.772  9941  9941 I fb-UnpackingSoSource: dso store is up-to-date: /data/user/0/com.facebook.appmanager/lib-main
12-19 12:52:34.772  9941  9941 V fb-UnpackingSoSource: releasing dso store lock for /data/user/0/com.facebook.appmanager/lib-main
,12-19 12:52:34.792  9941  9941 W com.facebook.appmanager:cp: Verify
,12-19 12:52:34.792  9941  9941 D InjectionManager: InjectionManager
,12-19 12:52:34.792  9941  9941 D InjectionManager: fillFeatureStoreMap com.facebook.appmanager
12-19 12:52:34.792  9941  9941 I InjectionManager: Constructor com.facebook.appmanager, Feature store :{}
12-19 12:52:34.792  9941  9941 I InjectionManager: featureStore :{}
,12-19 12:52:34.832  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:34.842  3421  3474 I ActivityManager: Killing 9345:com.samsung.ipservice/5004 (adj 15): DHA:empty #33
,12-19 12:52:34.852  8430  8430 I ServiceManager: [#CMH#] Disconnected to Service  com.samsung.ipservice.IPService
,12-19 12:52:34.872  9962  9962 E Zygote  : v2
12-19 12:52:34.872  9962  9962 I libpersona: KNOX_SDCARD checking this for 10039
12-19 12:52:34.872  9962  9962 I libpersona: KNOX_SDCARD not a persona
,12-19 12:52:34.872  9962  9962 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0029
,12-19 12:52:34.872  9962  9962 E Zygote  : accessInfo : 0
12-19 12:52:34.872  9962  9962 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.sec.android.app.shealth 
,12-19 12:52:34.882  3421  3421 I ActivityManager: Start proc 9962:com.sec.android.app.shealth/u0a39 for broadcast-3 com.sec.android.app.shealth/com.samsung.android.app.shealth.serviceframework.partner.PluginBroadcastReceiver
,12-19 12:52:34.892  3421  4417 D ActivityManager: isAutoRunBlockedApp:: com.samsung.ipservice, Auto Run ON
12-19 12:52:34.892  3421  4417 W ActivityManager: Scheduling restart of crashed service com.samsung.ipservice/.IPService in 20415ms
,12-19 12:52:34.892  9962  9962 D TimaKeyStoreProvider: TimaSignature is unavailable
12-19 12:52:34.892  9962  9962 D ActivityThread: Added TimaKeyStore provider
,12-19 12:52:34.912  3421  4570 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c8315c2 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a7d8fd3 9962:com.sec.android.app.shealth/u0a39}
,12-19 12:52:34.922  3421  3421 I BackgroundCompactionService: onStart. jobID=801
,12-19 12:52:34.922  3421  3421 I BackgroundCompactionService: onStart done. jobID=801
,12-19 12:52:34.922  9962  9962 D RelationGraph: garbageCollect()
12-19 12:52:34.922  9962  9962 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
12-19 12:52:34.922  3421  9974 I BackgroundCompactionService: Execute BGCompaction (type1). (0 times)
,12-19 12:52:34.922  3421  9974 I BackgroundCompactionService: compact_memory command done
,12-19 12:52:34.922  9962  9962 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.sec.android.app.shealth rsrc of package com.sec.android.app.shealth
,12-19 12:52:34.932  3421  3472 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,12-19 12:52:34.932  9962  9962 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,12-19 12:52:34.942  9962  9962 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:34.942  9962  9962 I InjectionManager: Inside getClassLibPath caller 
,12-19 12:52:34.952  3421  4420 D PackageManager: setEnabledSetting : userId = 0 packageName = com.facebook.appmanager cmp = com.facebook.oxygen.appmanager.crashmanager.CrashManagerActivity newState = 2 callingPackage = 10103
,12-19 12:52:34.952  9962  9962 W System  : ClassLoader referenced unknown path: /system/priv-app/SHealth4/lib/arm64
,12-19 12:52:34.952  9962  9962 I MultiDex: VM with version 2.1.0 has multidex support
12-19 12:52:34.952  9962  9962 I MultiDex: install
12-19 12:52:34.952  9962  9962 I MultiDex: VM has multidex support, MultiDex support library is disabled.
12-19 12:52:34.952  9962  9962 I MultiDex: install
12-19 12:52:34.952  9962  9962 I MultiDex: VM has multidex support, MultiDex support library is disabled.
12-19 12:52:34.952  3421  4182 D PackageManager: setEnabledSetting : userId = 0 packageName = com.facebook.appmanager cmp = com.facebook.oxygen.appmanager.firstparty.tos.ShouldAcceptTos newState = 2 callingPackage = 10103
,12-19 12:52:34.962  3421  3472 D PackageManager: setEnabledSetting : userId = 0 packageName = com.facebook.appmanager cmp = com.facebook.oxygen.appmanager.firstparty.tos.ShouldShowTos newState = 2 callingPackage = 10103
,12-19 12:52:34.962  9962  9962 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.sec.android.app.shealth rsrc of package com.sec.android.app.shealth
,12-19 12:52:34.962  3421  4333 D PackageManager: setEnabledSetting : userId = 0 packageName = com.facebook.appmanager cmp = com.facebook.oxygen.appmanager.firstparty.tos.ShouldShowExplicitTos newState = 2 callingPackage = 10103
,12-19 12:52:34.972  3421  4616 D PackageManager: setEnabledSetting : userId = 0 packageName = com.facebook.appmanager cmp = com.facebook.oxygen.appmanager.nekodirect.NekoDirectService newState = 2 callingPackage = 10103
,12-19 12:52:34.972  3421  4420 D PackageManager: setEnabledSetting : userId = 0 packageName = com.facebook.appmanager cmp = com.facebook.oxygen.appmanager.nekodirect.progress.ProgressContentProvider newState = 2 callingPackage = 10103
,12-19 12:52:34.982  9941  9977 E ActivityThread: Failed to find provider info for com.facebook.appmanager.oxygen.nekodirect.progress
,12-19 12:52:35.012  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:35.022  9962  9962 D InjectionManager: InjectionManager
12-19 12:52:35.022  9962  9962 D InjectionManager: fillFeatureStoreMap com.sec.android.app.shealth
,12-19 12:52:35.022  9962  9962 I InjectionManager: Constructor com.sec.android.app.shealth, Feature store :{}
12-19 12:52:35.022  9962  9962 I InjectionManager: featureStore :{}
,12-19 12:52:35.022  9962  9962 D HealthDataStore: Service for HealthDataStore is connected
,12-19 12:52:35.022  9962  9962 D HealthDataStore: HealthConnectionErrorResult code : 9
,12-19 12:52:35.032  9962  9962 D HealthConsole: Service for HealthDataConsole is connected
,12-19 12:52:35.032  3421  4421 I ActivityManager: Killing 8430:com.samsung.cmh:CMH/5004 (adj 15): DHA:empty #33
,12-19 12:52:35.032  9962  9962 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
,12-19 12:52:35.032  9962  9962 E HealthDataStore: disconnectService: Context instance is invalid
,12-19 12:52:35.042  3421  4421 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c8315c2 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2565e6c 9199:com.sec.android.app.shealth:remote/u0a39}
,12-19 12:52:35.052  3421  4417 E GameManagerService: remoteCallback died, callback: com.samsung.android.game.IGameManagerCallback$Stub$Proxy@4acced4, cookie: null
,12-19 12:52:35.062  3421  4989 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c8315c2 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2565e6c 9199:com.sec.android.app.shealth:remote/u0a39}
,12-19 12:52:35.082  9321  9321 I StoryService: [StoryService] On destroy() 
,12-19 12:52:35.082  9321  9321 I ServiceController: [StoryService] shutdown() 
,12-19 12:52:35.092  3421  4415 D ActivityManager: isAutoRunBlockedApp:: com.samsung.cmh, Auto Run ON
12-19 12:52:35.092  9474  9474 I EnhanceService: [EnhanceService] onDestroy () called 
,12-19 12:52:35.112  3421  4989 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d507372 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{afd4916 5084:com.samsung.android.providers.context/u0a9}
,12-19 12:52:35.122  3421  3981 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a9a13c3 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{afd4916 5084:com.samsung.android.providers.context/u0a9}
,12-19 12:52:35.132  3421  4616 I ActivityManager: Killing 8661:com.android.calendar/u0a144 (adj 15): DHA:empty #33
,12-19 12:52:35.162  3421  4420 D ActivityManager: isAutoRunBlockedApp:: com.android.calendar, Auto Run ON
,12-19 12:52:35.192  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:35.382  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:35.562  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:35.742  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:35.922  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:36.092  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:36.262  3421  3815 V AlarmManager: Expired Alarm result :4
,12-19 12:52:36.272  3421  4421 V AlarmManager:  remove PendingIntent] PendingIntent{4577f79: PendingIntentRecord{e96d19c com.google.android.gms broadcastIntent}}
,12-19 12:52:36.272  3421  3856 D NetworkPolicy: isUidForegroundLocked: 10021, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
12-19 12:52:36.272  3421  3856 D NetworkPolicy: isUidForegroundLocked: 10021, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,12-19 12:52:36.282  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:36.412  3421  6150 D SSRM:n  : SIOP:: AP = 460, PST = 471 (W:6), CP = 317, CUR = -372, LCD = 1
,12-19 12:52:36.462  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:36.642  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:36.822  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:37.002  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:37.172  3421  3983 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,12-19 12:52:37.172  3421  3983 D BatteryService: level:99, scale:100, status:2, health:2, present:true, voltage: 4253, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 12:52:37.172  3421  3983 D BatteryService: online:4, current avg:-517, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-463
12-19 12:52:37.172  3421  3983 D BatteryService: stay LED for charging
12-19 12:52:37.172  3421  3421 D BatteryService: Sending ACTION_BATTERY_CHANGED.
12-19 12:52:37.182  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:37.182  3421  3421 I MotionRecognitionService: Plugged
12-19 12:52:37.182  3421  3421 D MotionRecognitionService:   cableConnection= 1
12-19 12:52:37.182  3421  3421 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-19 12:52:37.182  3421  3421 D MotionRecognitionService: skip setTransmitPower. 
,12-19 12:52:37.182  3421  3861 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-19 12:52:37.182  3938  3938 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-19 12:52:37.182  3938  3938 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-19 12:52:37.192  3938  3938 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : 201000 mChargingTime : 201000
12-19 12:52:37.192  3938  3938 D KeyguardUpdateMonitor: handleBatteryUpdate
12-19 12:52:37.192  3938  3938 D PowerUI.Notification: There is no change about charging status, so return!
,12-19 12:52:37.192  5096  5096 D CommonServiceConfiguration: getStringValueSetting
,12-19 12:52:37.202  5054  5054 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-19 12:52:37.202  5054  5457 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-19 12:52:37.202  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
12-19 12:52:37.202  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
12-19 12:52:37.202  5096  5096 D BatteryMonitor: new battery level: 99
,12-19 12:52:37.202  4740  4740 D BatteryController: saveBatteryData : level[99], status[2]
,12-19 12:52:37.272  9676  9683 I eN66    : JNI Enter Function Java_com_asr_pocketsphinx_pocketsphinxJNI_delete_1Config
12-19 12:52:37.272  9676  9683 I eN66    : JNI Exit Function Java_com_asr_pocketsphinx_pocketsphinxJNI_delete_1Config
,12-19 12:52:37.362  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:37.512  3421  6150 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,12-19 12:52:37.522  9697  9704 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+user+0+com_samsung_svoice_sync+databases+svoicelocal_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,12-19 12:52:37.542  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:37.722  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:37.902  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:38.082  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:38.262  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:38.442  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:38.622  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:38.792  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:38.862  3421  6185 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-19 12:52:38.982  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:39.162  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:39.342  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:39.522  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:39.702  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:39.882  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:39.892  9569  9710 E JX-Cordova: JavaCall recevied a call for unknown method didRegisterToNative
12-19 12:52:39.892  9569  9710 E JX-Cordova: JavaCall recevied a call for unknown method didRegisterToNative
12-19 12:52:39.892  9569  9710 E JX-Cordova: JavaCall recevied a call for unknown method didRegisterToNative
12-19 12:52:39.892  9569  9710 E JX-Cordova: JavaCall recevied a call for unknown method didRegisterToNative
,12-19 12:52:40.042  9569  9710 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
,12-19 12:52:40.042  9569  9710 I jxcore-log: Failed to execute UT.
12-19 12:52:40.042  9569  9710 I jxcore-log: 
12-19 12:52:40.042  9569  9710 I jxcore-log: 2016-12-19 11:52:40 - DEBUG UnitTest_app: 'Failed to execute UT.'
12-19 12:52:40.042  9569  9710 I jxcore-log: 
,12-19 12:52:40.042  9569  9710 I jxcore-log: 2016-12-19 11:52:40 - DEBUG UnitTest_app: 'Unit Test app is loaded'
12-19 12:52:40.042  9569  9710 I jxcore-log: 
,12-19 12:52:40.062  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:40.062  9569  9569 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 68 : UIApp is all set and ready!
,12-19 12:52:40.062  9569  9569 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,12-19 12:52:40.242  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:40.422  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:40.602  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:40.782  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:40.962  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:41.002  3421  3595 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,12-19 12:52:41.032  3421  3595 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,12-19 12:52:41.142  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:41.322  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:41.492  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:41.502  4637  9994 W IcingInternalCorpora: getNumBytesRead when not calculated.
,12-19 12:52:41.682  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:41.862  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:42.042  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:42.222  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:42.402  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:42.582  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:42.762  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:42.942  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:43.122  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:43.302  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:43.482  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:43.662  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:43.842  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:43.862  3421  6185 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-19 12:52:44.022  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:44.202  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:44.382  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:44.562  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:44.742  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:44.922  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:45.102  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:45.282  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:45.462  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:45.632  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:45.702  4166  4176 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg com.google.android.music,id=10436,extra=Bundle[mParcelledData.dataSize=84]
,12-19 12:52:45.702  4166  4166 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=10436, samsung.notification.type=normal, samsung.people.package_name=com.google.android.music}]
,12-19 12:52:45.712  4166  4166 I PeopleStripeService: PeopleNotificationReceiver:3
12-19 12:52:45.712  4166  4166 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
12-19 12:52:45.712  4166  4166 I PeopleDataManager: removeNotification
12-19 12:52:45.712  4166  4166 I NotificationParser: getNotiType:com.google.android.music,null
12-19 12:52:45.712  4166  4166 D PeopleDataManager: removeNotiInfo: id =10436,packageName=com.google.android.music,isEdgeNotification=false,key=null,removeAll=false
12-19 12:52:45.712  4166  4166 D PeopleDataManager: removeNotiInfo =null
,12-19 12:52:45.812  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:46.002  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:46.182  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:46.282  3421  3856 D NetworkPolicy: isUidForegroundLocked: 10021, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
12-19 12:52:46.282  3421  3856 D NetworkPolicy: isUidForegroundLocked: 10021, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,12-19 12:52:46.362  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:46.442  3421  6150 D SSRM:n  : SIOP:: AP = 400, PST = 461 (W:7), CP = 316, CUR = -517, LCD = 1
,12-19 12:52:46.542  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:46.722  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:46.842  3938  3938 V KeyguardUpdateMonitor: onSubscriptionInfoChanged()
,12-19 12:52:46.842  3938  3938 V KeyguardUpdateMonitor: onSubscriptionInfoChanged: list is null
,12-19 12:52:46.852  3938  3938 D KeyguardCarrierText: onRefreshCarrierInfo: 
,12-19 12:52:46.852  3938  3938 D KeyguardCarrierText: updateAllSlot
,12-19 12:52:46.862  3938  3938 D KeyguardCarrierText: updateIntentData(): isMultiSIMState: falsesubId: 2147483643 phoneId:0plmn: Brak sieciSPN: 
,12-19 12:52:46.862  3421  4182 D SecContentProvider2: query(), uri = 15 selection = getLockScreenHiddenItems
,12-19 12:52:46.872  3938  3938 D KeyguardCarrierText: updateCarrierText(): isMultiSIMState: false
,12-19 12:52:46.872  3938  3938 D KeyguardCarrierText: updateDate All slot
,12-19 12:52:46.872  3938  3938 D KeyguardCarrierText: mSimState[0]ABSENT
,12-19 12:52:46.872  3938  3938 D KeyguardCarrierText: mSimState[1]ABSENT
12-19 12:52:46.872  3938  3938 D KeyguardCarrierText: Getting plmn/spn sticky brdcst  mPlmn:Brak sieci / mSpn:  phoneId:0 subId:2147483643 showPlmn: true showSpn:false
12-19 12:52:46.872  3938  3938 D KeyguardCarrierText: getStatusForIccState :  SIM state = ABSENT
,12-19 12:52:46.872  3938  3938 D KeyguardCarrierText: makeCarrierStringOnEmergencyCapable :  mIsEmergencyCallCapable:  true
12-19 12:52:46.872  3938  3938 D KeyguardCarrierText: concatenate : plmn = Brak karty SIM, spn = Brak sieci
12-19 12:52:46.872  3938  3938 D KeyguardCarrierText: getCarrierTextForSimState :  SIM state = SimMissingcarrierText: Brak karty SIM | Brak sieci
12-19 12:52:46.872  3938  3938 D KeyguardCarrierText: Handling ABSENT , carrierTextForSimState = Brak karty SIM | Brak sieci
,12-19 12:52:46.882  3938  3938 D KeyguardCarrierText: updateCarrierText insertedMultiSim = false
,12-19 12:52:46.882  3938  3938 D KeyguardCarrierText: updateCarrierText State: Absent SIM Number = 0
,12-19 12:52:46.892  3938  3938 D KeyguardCarrierText: Getting plmn/spn sticky brdcst for Absent case Brak sieci/showPlmn: trueshowSpn: false phoneId:0 subId:2147483643
,12-19 12:52:46.892  3938  3938 D KeyguardCarrierText: concatenate : plmn = Brak sieci
12-19 12:52:46.892  3938  3938 D KeyguardCarrierText: makeCarrierStringOnEmergencyCapable :  mIsEmergencyCallCapable:  true
12-19 12:52:46.892  3938  3938 D KeyguardCarrierText: concatenate : plmn = Brak karty SIM, spn = Brak sieci
,12-19 12:52:46.892  3938  3938 D KeyguardCarrierText: setText :  displayText = Tryb Offline
,12-19 12:52:46.892  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:46.902  3938  3938 D EmergencyButton: onRefreshCarrierInfo,
,12-19 12:52:47.012  3421  3815 V AlarmManager: Expired Alarm result :4
,12-19 12:52:47.052  9151  9194 W Finsky  : [942] com.google.android.finsky.FinskyApp.i(1379): No account configured on this device.
,12-19 12:52:47.062  9151  9194 I Finsky  : [942] com.google.android.finsky.c.e.run(1151): Replicating app states via AMAS.
,12-19 12:52:47.072  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:47.222  3421  3474 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-19 12:52:47.222  3421  3474 D BatteryService: level:99, scale:100, status:2, health:2, present:true, voltage: 4320, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 12:52:47.222  3421  3474 D BatteryService: online:4, current avg:-179, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:106
12-19 12:52:47.222  3421  3474 D BatteryService: stay LED for charging
12-19 12:52:47.222  3421  3421 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-19 12:52:47.222  3421  3421 I MotionRecognitionService: Plugged
12-19 12:52:47.222  3421  3421 D MotionRecognitionService:   cableConnection= 1
12-19 12:52:47.222  3421  3421 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-19 12:52:47.222  3421  3421 D MotionRecognitionService: skip setTransmitPower. 
,12-19 12:52:47.222  3421  3861 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-19 12:52:47.232  3938  3938 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
12-19 12:52:47.232  3938  3938 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-19 12:52:47.232  3938  3938 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-19 12:52:47.232  3938  3938 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : 201000 mChargingTime : 252000
12-19 12:52:47.232  3938  3938 D PowerUI.Notification: showChargingNotification()
,12-19 12:52:47.242  5096  5096 D CommonServiceConfiguration: getStringValueSetting
,12-19 12:52:47.242  5054  5054 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
12-19 12:52:47.242  3421  4415 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = -1
12-19 12:52:47.242  5054  5457 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-19 12:52:47.252  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
12-19 12:52:47.252  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,12-19 12:52:47.252  5096  5096 D BatteryMonitor: new battery level: 99
,12-19 12:52:47.252  4740  4740 D BatteryController: saveBatteryData : level[99], status[2]
,12-19 12:52:47.252  3421  3421 W ResourcesManager: getTopLevelResources: /system/priv-app/SystemUI/SystemUI.apk / 1.0 running in null rsrc of package com.android.systemui
,12-19 12:52:47.252  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:47.262  3421  3421 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:47.262  3421  3421 D MARsPolicyManager: NotificationListenerService OngoingNotificationPosted : com.android.systemui
,12-19 12:52:47.272  4153  4165 D CatchNotificationsService: onNotificationPosted
,12-19 12:52:47.282  3938  3938 W ResourcesManager: getTopLevelResources: /system/priv-app/SystemUI/SystemUI.apk / 1.0 running in com.android.systemui rsrc of package com.android.systemui
,12-19 12:52:47.292  9410  9422 D BadgeProvider: query, [selection] : null
12-19 12:52:47.292  3938  3938 D PhoneStatusBar: setAreThereNotifications: N=3 any=true clearable=false
,12-19 12:52:47.292  4153  4165 E CatchNotificationsService: Invalid notification data
,12-19 12:52:47.432  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:47.532  3421  4152 E Watchdog: !@Sync 2 [12-19 12:52:47.543]
,12-19 12:52:47.622  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:47.662  3421  3534 I ActivityManager: Waited long enough for: ServiceRecord{5e0fc05 u0 com.samsung.voiceserviceplatform/com.samsung.vsf.core.framework.VoiceFrameworkService}
,12-19 12:52:47.802  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:47.942  9151  9194 I Finsky  : [942] com.google.android.finsky.c.c.a(311): Completed 0 account content syncs with 0 successful.
,12-19 12:52:47.942  9151  9151 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
,12-19 12:52:47.972  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:48.162  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:48.342  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:48.522  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:48.652  4400  4465 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
12-19 12:52:48.652  4400  4465 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,12-19 12:52:48.702  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:48.872  3421  6185 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-19 12:52:48.872  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:49.052  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:49.242  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:49.422  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:49.592  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:49.772  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:49.962  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:50.132  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:50.312  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:50.492  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:50.672  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:50.852  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:51.032  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:51.212  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:51.402  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:51.412  3153  3630 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,12-19 12:52:51.582  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:51.682  3421  5124 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
12-19 12:52:51.682  3421  5124 V MARsPolicyManager: updateSMDBValues
,12-19 12:52:51.682  3421  3565 E MARsDBManager: updateDBAll : begin --size 0
12-19 12:52:51.682  3421  3565 E MARsDBManager: updateDBAll : end
,12-19 12:52:51.762  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:51.942  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:52.112  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:52.302  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:52.332  3153  3630 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,12-19 12:52:52.482  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:52.662  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:52.832  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:53.012  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:53.192  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:53.382  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:53.562  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:53.742  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:53.872  3421  6185 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-19 12:52:53.922  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:54.092  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:54.272  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:54.452  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:54.642  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:54.812  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:54.992  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:55.172  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:55.362  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:55.532  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:55.712  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:55.892  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:56.082  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:56.252  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:56.432  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:56.462  3421  6150 D SSRM:n  : SIOP:: AP = 350, PST = 447 (W:8), CP = 301, CUR = -179, LCD = 1
,12-19 12:52:56.462  3421  6150 D N       : limitCPUFreq:: freq = 2496000
,12-19 12:52:56.472  3421  6150 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MAX_LIMIT  frequency : 2496000  uid : 1000  pid : 3421  pkgName : SIOP_ARM_MAX@22
,12-19 12:52:56.472  3421  6150 D N       : broadcastSiopLevelIntent:: currentSiopLevel = 0
,12-19 12:52:56.472  4906  4906 D ContentApp:  LEVEL : 0
,12-19 12:52:56.512 10000 10000 E Zygote  : v2
12-19 12:52:56.512 10000 10000 I libpersona: KNOX_SDCARD checking this for 5009
12-19 12:52:56.512 10000 10000 I libpersona: KNOX_SDCARD not a persona
,12-19 12:52:56.512 10000 10000 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0029
,12-19 12:52:56.512  3421  3534 I ActivityManager: Start proc 10000:com.samsung.android.scloud:contentsync/5009 for broadcast-3 com.samsung.android.scloud/.cloudagent.detector.DetectorReceiver
,12-19 12:52:56.512 10000 10000 E Zygote  : accessInfo : 0
12-19 12:52:56.512 10000 10000 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.scloud:contentsync 
,12-19 12:52:56.522  3421  6150 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,12-19 12:52:56.552 10000 10000 D TimaKeyStoreProvider: TimaSignature is unavailable
12-19 12:52:56.552 10000 10000 D ActivityThread: Added TimaKeyStore provider
,12-19 12:52:56.572  3421  3981 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{62efd70 u-1 android.intent.action.CHECK_SIOP_LEVEL qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7da38e9 10000:com.samsung.android.scloud:contentsync/5009}
,12-19 12:52:56.592 10000 10000 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,12-19 12:52:56.592 10000 10000 D RelationGraph: garbageCollect()
,12-19 12:52:56.592 10000 10000 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.samsung.android.scloud
,12-19 12:52:56.602  3421  4333 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
12-19 12:52:56.602 10000 10000 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,12-19 12:52:56.602 10000 10000 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:56.612 10000 10000 I InjectionManager: Inside getClassLibPath caller 
,12-19 12:52:56.612  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
12-19 12:52:56.612 10000 10000 W System  : ClassLoader referenced unknown path: /system/priv-app/SamsungCloud/lib/arm64
,12-19 12:52:56.652 10000 10000 I [SC]CloudManager: requestInit
,12-19 12:52:56.672 10000 10000 I [SC]Utils: folder : cachecreate fail, try again.
12-19 12:52:56.672 10000 10000 I [SC]Utils: folder : cache create fail.
12-19 12:52:56.672 10000 10000 I [SC]Utils: folder : thumbnailcreate fail, try again.
12-19 12:52:56.672 10000 10000 I [SC]Utils: folder : thumbnail create fail.
12-19 12:52:56.672 10000 10000 I [SC]Utils: folder : sharecreate fail, try again.
12-19 12:52:56.672 10000 10000 I [SC]Utils: folder : share create fail.
12-19 12:52:56.672 10000 10000 I [SC]Utils: folder : scratchcreate fail, try again.
12-19 12:52:56.672 10000 10000 I [SC]Utils: folder : scratch create fail.
,12-19 12:52:56.672 10000 10000 I [SC]Utils: folder : eventSynccreate fail, try again.
12-19 12:52:56.672 10000 10000 I [SC]Utils: folder : eventSync create fail.
,12-19 12:52:56.682 10000 10000 V SamsungCloudLogs:  set Log level [4->4]act[false]
,12-19 12:52:56.682 10000 10000 I [SC]CommonUtil: isSemAvailable:0
,12-19 12:52:56.692 10000 10000 I [SC]SamsungCloudApp: AppVer[2.1.11][L:4]Sem[false]V2DEV_R slog[false]com.samsung.android.scloud:contentsync
,12-19 12:52:56.692 10000 10000 D InjectionManager: InjectionManager
12-19 12:52:56.692 10000 10000 D InjectionManager: fillFeatureStoreMap com.samsung.android.scloud
12-19 12:52:56.692 10000 10000 I InjectionManager: Constructor com.samsung.android.scloud, Feature store :{}
12-19 12:52:56.692 10000 10000 I InjectionManager: featureStore :{}
,12-19 12:52:56.692 10000 10000 I [SC]FeatureManager: FeatureManager 
12-19 12:52:56.692 10000 10000 I [SC]FeatureManager: [SEC_FLOATING_FEATURE_SAMSUNGCLOUD_CONFIG_CLOUD_USAGE_MENU_TREE]str 
12-19 12:52:56.692 10000 10000 I [SC]FeatureManager: [SEC_FLOATING_FEATURE_SAMSUNGCLOUD_ENABLE_SETTING_MENU]bln true
,12-19 12:52:56.692 10000 10000 E [SC]SCLOUD_ERR-Utils: isShipMode : 1 
,12-19 12:52:56.702 10000 10000 I [SC]DetectorReceiver: onReceive [android.intent.action.CHECK_SIOP_LEVEL]
12-19 12:52:56.702 10000 10000 I [SC]CloudManager: requestInit
,12-19 12:52:56.702 10000 10000 I [SC]Utils: folder : cachecreate fail, try again.
12-19 12:52:56.702 10000 10000 I [SC]Utils: folder : cache create fail.
12-19 12:52:56.702 10000 10000 I [SC]Utils: folder : thumbnailcreate fail, try again.
12-19 12:52:56.702 10000 10000 I [SC]Utils: folder : thumbnail create fail.
12-19 12:52:56.702 10000 10000 I [SC]Utils: folder : sharecreate fail, try again.
12-19 12:52:56.702 10000 10000 I [SC]Utils: folder : share create fail.
12-19 12:52:56.702 10000 10000 I [SC]Utils: folder : scratchcreate fail, try again.
12-19 12:52:56.702 10000 10000 I [SC]Utils: folder : scratch create fail.
12-19 12:52:56.702 10000 10000 I [SC]Utils: folder : eventSynccreate fail, try again.
,12-19 12:52:56.702 10000 10000 I [SC]Utils: folder : eventSync create fail.
,12-19 12:52:56.722 10013 10013 E Zygote  : v2
12-19 12:52:56.722 10013 10013 I libpersona: KNOX_SDCARD checking this for 10044
12-19 12:52:56.722 10013 10013 I libpersona: KNOX_SDCARD not a persona
,12-19 12:52:56.722 10013 10013 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0029
,12-19 12:52:56.722 10013 10013 E Zygote  : accessInfo : 0
12-19 12:52:56.722 10013 10013 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.osp.app.signin 
,12-19 12:52:56.732  3421  4417 I ActivityManager: Start proc 10013:com.osp.app.signin/u0a44 for content provider com.osp.app.signin/com.msc.openprovider.OpenContentProvider
,12-19 12:52:56.732  3421  3856 D NetworkPolicy: isUidForegroundLocked: 10044, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,12-19 12:52:56.762 10013 10013 D TimaKeyStoreProvider: TimaSignature is unavailable
12-19 12:52:56.762 10013 10013 D ActivityThread: Added TimaKeyStore provider
,12-19 12:52:56.782  3421  3856 D NetworkPolicy: isUidForegroundLocked: 10044, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
,12-19 12:52:56.792  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:56.802 10013 10013 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
12-19 12:52:56.802 10013 10013 D RelationGraph: garbageCollect()
,12-19 12:52:56.802 10013 10013 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungAccount_Hero/SamsungAccount_Hero.apk / 1.0 running in com.osp.app.signin rsrc of package com.osp.app.signin
,12-19 12:52:56.812  3421  4333 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,12-19 12:52:56.812 10013 10013 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,12-19 12:52:56.822 10013 10013 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:56.832 10013 10013 I InjectionManager: Inside getClassLibPath caller 
,12-19 12:52:56.852 10013 10013 W System  : ClassLoader referenced unknown path: /system/priv-app/SamsungAccount_Hero/lib/arm64
,12-19 12:52:56.862 10013 10013 I SA      : [SSP] onCreated
,12-19 12:52:56.902 10013 10024 I SA      : [SCU] isHaveSA() - false
12-19 12:52:56.902 10013 10024 I SA      : [OCP] Samsung account is not Signed-in
,12-19 12:52:56.902 10013 10024 I SA      : [OCP] Delete DB (TNC data)
,12-19 12:52:56.902 10013 10013 D SamsungAnalytics: [Tracker] Tracker start:1.2.00
,12-19 12:52:56.912 10000 10000 I [SC]CommonUtil: Samsung Account Not Logged in
,12-19 12:52:56.912  3421  4391 I ActivityManager: Killing 9361:com.google.android.gm/u0a113 (adj 15): DHA:empty #33
,12-19 12:52:56.912  3421  4391 I ActivityManager: Killing 9321:com.samsung.storyservice/5004 (adj 15): DHA:empty #33
,12-19 12:52:56.922 10013 10013 I SA      : [TPM] There is no property file
,12-19 12:52:56.922 10013 10013 I SA      : [SCU] isHaveSA() - false
,12-19 12:52:56.932 10013 10013 I SA      : [TPM] getModelProperty : null
,12-19 12:52:56.932 10013 10013 I SA      : [TPM] getCSCProperty : null
,12-19 12:52:56.932 10013 10013 I SA      : [DM] FLOATING AMOLED FEATURE: true
,12-19 12:52:56.932 10013 10013 I SA      : [DM] PRODUCT AMOLED FEATURE: false
,12-19 12:52:56.932 10013 10013 I SA      : [DM] TFT FEATURE: false
,12-19 12:52:56.932 10013 10013 I SA      : [SCU] isHaveSA() - false
,12-19 12:52:56.932 10013 10013 I SA      : [SCU] == networkStateCheck == true
,12-19 12:52:56.942 10013 10013 I SA      : [DirServerUtil] isRetryAvailable = true
12-19 12:52:56.942 10013 10013 I SA      : [SS] no success marketing info data
,12-19 12:52:56.942 10013 10013 D InjectionManager: InjectionManager
12-19 12:52:56.942 10013 10013 D InjectionManager: fillFeatureStoreMap com.osp.app.signin
,12-19 12:52:56.942 10013 10013 I InjectionManager: Constructor com.osp.app.signin, Feature store :{}
12-19 12:52:56.942 10013 10013 I InjectionManager: featureStore :{}
,12-19 12:52:56.952  3421  3983 D ActivityManager: isAutoRunBlockedApp:: com.samsung.storyservice, Auto Run ON
,12-19 12:52:56.962  3421  3981 D ActivityManager: isAutoRunBlockedApp:: com.google.android.gm, Auto Run ON
,12-19 12:52:56.972  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:57.152  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:57.282  3421  3853 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-19 12:52:57.282  3421  3853 D BatteryService: level:99, scale:100, status:2, health:2, present:true, voltage: 4327, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 12:52:57.282  3421  3853 D BatteryService: online:4, current avg:51, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:180
12-19 12:52:57.282  3421  3853 D BatteryService: stay LED for charging
12-19 12:52:57.282  3421  3421 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-19 12:52:57.292  3421  3421 I MotionRecognitionService: Plugged
,12-19 12:52:57.292  3421  3421 D MotionRecognitionService:   cableConnection= 1
12-19 12:52:57.292  3421  3421 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-19 12:52:57.292  3421  3421 D MotionRecognitionService: skip setTransmitPower. 
,12-19 12:52:57.292  3421  3861 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-19 12:52:57.302  3938  3938 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
12-19 12:52:57.302  3938  3938 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-19 12:52:57.302  3938  3938 D PowerUI : priorPlugType = 2 mPlugType =  2,
,12-19 12:52:57.302  3938  3938 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : 252000 mChargingTime : 252000
,12-19 12:52:57.302  3938  3938 D PowerUI.Notification: There is no change about charging status, so return!
,12-19 12:52:57.322  5096  5096 D CommonServiceConfiguration: getStringValueSetting
,12-19 12:52:57.322  5054  5054 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-19 12:52:57.322  5054  5457 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-19 12:52:57.332  5096  5096 D BatteryMonitor: new battery level: 99
,12-19 12:52:57.332  4740  4740 D BatteryController: saveBatteryData : level[99], status[2]
,12-19 12:52:57.332  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:57.352  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,12-19 12:52:57.352  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,12-19 12:52:57.522  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:57.692  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:57.872  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:58.052  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:58.232  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:58.412  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:58.592  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:58.772  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:58.872  3421  6185 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-19 12:52:58.962  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:59.132  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:59.322  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:59.492  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:59.682  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:59.852  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:52:59.982  3421  3815 V AlarmManager: Expired Alarm result :8
,12-19 12:53:00.002  3421  3815 V AlarmManager: Expired Alarm result :4
,12-19 12:53:00.002  3421  3815 V AlarmManager: Send whitelist package alarm :PendingIntent{a0239b3: PendingIntentRecord{3f94b70 com.samsung.android.app.aodservice broadcastIntent}}
,12-19 12:53:00.002  3421  3421 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,12-19 12:53:00.002  3421  3421 V AlarmManagerEXT: <AppSync3 Whitelist>
,12-19 12:53:00.012  3421  3421 V AlarmManagerEXT: (AppSync) ### 0 added ###
,12-19 12:53:00.012  3938  3938 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
12-19 12:53:00.012  3938  3938 D KeyguardUpdateMonitor: handleTimeUpdate
,12-19 12:53:00.032  3938  3938 D Clock   : received broadcast android.intent.action.TIME_TICK
,12-19 12:53:00.032  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:00.102  3938  3938 D DateView: received broadcast android.intent.action.TIME_TICK
,12-19 12:53:00.132  8036  8036 D [WeatherWidget(1240)]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,12-19 12:53:00.152  8036  8036 W [WeatherWidget(1240)]  : {[15CF912BDCF42F9CFB4A85BDA543B9C03270F5FAA9F5676E82AF8C619BCF91CE5FB3CE2082F25CD9A43F9287628E184E1B535DD573D2968B1284E288CF459C13DF414A1402CD333D136FA7792C603AC4]}
,12-19 12:53:00.152  8036  8036 D [WeatherWidget(1240)]  AutoRefresh: {[9BDBD671986BB5350BB30F5195E2700D025AD0AB6B43765153FE15B38684E558D03F28FB0B91AB39310ABEC4D7D82D6E635843040DF4C0F1B9C2397CFFDE153E031020FC4E2C26F3A31388ED7A346963]}
,12-19 12:53:00.152  8036  8036 D [WeatherWidget(1240)]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,12-19 12:53:00.152  8036  8036 D [WeatherWidget(1240)]  : {[9F9F443422C90E3D1C251B879888811D9BE8F5469D72520331506A4B883A4D63F11DD6D802FFA8F6CE10F27B8D429FC5]}
,12-19 12:53:00.152  8036  8036 D [WeatherWidget(1240)]  : {[68086835334BD11DCD92A5E633AE22E2D31F6EB793B927E1EFC2545E08F3928E96ECD7F469DC78A2FA30FE5745C0F4C5]}
,12-19 12:53:00.162  8036  8036 D [WeatherWidget(1240)]  : {[00E3D6BBB5F57518CE2AE63D1C0379D98B2214ED769C08BFA216B2BA55E91A620DC80E9633ECD3EFD4D65A30244FC1F0]}
,12-19 12:53:00.162  4740  4740 D AODService.ClockTimer: onReceive : com.samsung.android.app.aodservice.ClockTimer.TICK, mWakeUp = true
,12-19 12:53:00.162  4740  4740 V BatteryController: getBatteryLevel[99.0], batteryStatus[2]
,12-19 12:53:00.172  3421  4989 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,12-19 12:53:00.172  3421  4989 I CAE     : setPropertyValue(DevicePhysicalContextMonitorRunner.java:155) - Get status
,12-19 12:53:00.172  3421  4989 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -72, 56, 1, 1,
12-19 12:53:00.172  3421  4989 D SensorHubManager: SendSensorHubData: send data = -72, 56, 1, 1
,12-19 12:53:00.172  3168  3168 D Sensorhubs: sendContextData: -72, 56, 1, 1
,12-19 12:53:00.182  3421  4989 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
,12-19 12:53:00.182  3421  4989 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
12-19 12:53:00.182  3421  4989 D SContextService: requestToUpdate() : service = Device Physical Context Monitor
12-19 12:53:00.182  4740  4740 D SContextManager:   .requestToUpdate : listener = com.samsung.android.app.aodservice.AODService$7@63b629b, service=Device Physical Context Monitor
,12-19 12:53:00.182  4740  4740 I AlpmModeManager: startAlpmMode : state  = BLANK
,12-19 12:53:00.192  4740  4740 D DefaultClockView: Window showed. Time views updating
,12-19 12:53:00.192  3421  3983 I libsuspend: !@autosuspend_wakeup_count_disable
12-19 12:53:00.192  3421  3983 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3421
12-19 12:53:00.192  3421  3983 I libsuspend: !@autosuspend_wakeup_count_disable done
12-19 12:53:00.192  3421  3983 D PowerManagerService: mDisplayReady: false
12-19 12:53:00.192  4740  4740 D AODUpdatePositionController: updatePosition: direction[2] updatePosition: X[26] Y[222] NewPositionTimer[59]
12-19 12:53:00.192  3421  3983 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
12-19 12:53:00.192  3010  3010 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fa2c03c00
12-19 12:53:00.192  3421  3574 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-19 12:53:00.192  3010  3010 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
12-19 12:53:00.192  3421  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-19 12:53:00.192  3421  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-19 12:53:00.192  3421  3574 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-19 12:53:00.192  3421  3586 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
,12-19 12:53:00.192  3421  3570 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
12-19 12:53:00.202  4740  4740 D DefaultClockView: LocalTime Pattern : HH:mm
,12-19 12:53:00.192  3421  3570 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
,12-19 12:53:00.202  4740  4740 D TimeViewHolder: onTimeUpdate: timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] isSplitHour:false isSingleView:false isAMPMonLeft:null time01: 12:53 time02: null ampm: null
,12-19 12:53:00.212  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
12-19 12:53:00.212  3168  3213 D Sensorhubs: readContextData: 1, 1, 56, 1, 1, 1, 1
,12-19 12:53:00.212  3421  3818 D SensorHubManager: onGetSensorHubDataLocked: library(7) = 1, 1, 56, 1, 1, 1, 1
,12-19 12:53:00.222  3421  3817 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 14, 11, 53, 0,
12-19 12:53:00.222  3421  3574 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-19 12:53:00.222  3421  3817 D SensorHubManager: SendSensorHubData: send data = -63, 14, 11, 53, 0
12-19 12:53:00.222  3421  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-19 12:53:00.222  3421  3574 I libsuspend: !@autosuspend_wakeup_count_enable
12-19 12:53:00.222  3421  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-19 12:53:00.222  3421  3574 I libsuspend: !@autosuspend_wakeup_count_enable done
12-19 12:53:00.222  3421  3574 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-19 12:53:00.222  3421  3574 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-19 12:53:00.222  3421  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-19 12:53:00.222  3421  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-19 12:53:00.222  3421  3574 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-19 12:53:00.222  3421  3574 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
12-19 12:53:00.222  3421  3574 D PowerManagerService: mDisplayReady: true
12-19 12:53:00.222  3421  3574 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,12-19 12:53:00.222  3168  3214 D Sensorhubs: sendContextData: -63, 14, 11, 53, 0
,12-19 12:53:00.222  5854  5854 E CocktailBarPositionManager: Window direction: 0
12-19 12:53:00.222  5854  5854 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,12-19 12:53:00.232  3421  3817 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :7], AP_SLEEP
12-19 12:53:00.232  3421  3817 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 7
12-19 12:53:00.232  3421  3817 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 56, 1, 1, 1, 1,
12-19 12:53:00.232  3421  3817 D CAE     : display(ContextProvider.java:375) - ================= DEVICE_PHYSICAL_CONTEXT_MONITOR =================
12-19 12:53:00.232  3421  3817 I CAE     : display(ContextProvider.java:391) - AODReason=[1], AODStatus=[1], DataType=[1]
,12-19 12:53:00.232  3421  3820 D SContextService: updateSContext() : event = Device Physical Context Monitor
12-19 12:53:00.232  4740  4740 D RoamingTimeViewHolder: isDualClockSetting :: true isHomeTimeZoneExist :: false isEasyUxON :: false Utils.isRoaming(mContext) :: false
,12-19 12:53:00.242  4740  4740 D RoamingTimeViewHolder: getHomeCalendar : No homecity_timezone, set as default :  (libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167])
12-19 12:53:00.242  4740  4740 D RoamingTimeViewHolder: onTimeUpdate: isVisible:false timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] text:pon., 19 gru 12:53
12-19 12:53:00.242  4740  4740 I AODService.ClockTimer: startAlarm : TICK
12-19 12:53:00.242  3421  4182 V AlarmManager: Add whitelist package alarm :PendingIntent{1a10a88: PendingIntentRecord{3f94b70 com.samsung.android.app.aodservice broadcastIntent}}
,12-19 12:53:00.242  4740  4740 I AlpmModeManager: handleUnblankDisplay: state  = BLANK
12-19 12:53:00.242  4740  4740 V AlpmModeManager: updateAlpmMode: setDoze [DISPLAY_STATE_DOZE_SUSPEND]
12-19 12:53:00.242  3421  3984 I PowerManagerService: [api] setDozeOverrideFromAod AlpmHlpmSysfs = -1, screenState = 4, Brightness = 0, wakefulness = false
12-19 12:53:00.242  3421  3984 D PowerManagerService: setDozeModeBySysfs:  value is -1 , we ignore it. 
12-19 12:53:00.242  3421  4616 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3421
,12-19 12:53:00.252  4740  4740 D DefaultClockView: RootView invalidate()
,12-19 12:53:00.252  3421  3474 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3421
,12-19 12:53:00.252  4740  4740 I AODService: onSContextChanged: AODScreenShown state is already true
,12-19 12:53:00.392  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:00.402  3421  3421 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3421 (0x0)
,12-19 12:53:00.402  3421  3421 I libsuspend: !@autosuspend_wakeup_count_disable
12-19 12:53:00.402  3421  3421 D PowerManagerService: mDisplayReady: false
12-19 12:53:00.402  3421  3421 I libsuspend: !@autosuspend_wakeup_count_disable done
,12-19 12:53:00.402  3421  3574 D DisplayPowerController: animateScreenStateChange[0]: target=4
12-19 12:53:00.402  3010  3010 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7fa2c03c00
12-19 12:53:00.402  3421  3421 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
,12-19 12:53:00.402  3010  3010 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
12-19 12:53:00.402  3421  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
,12-19 12:53:00.402  3421  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-19 12:53:00.402  3421  3574 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-19 12:53:00.402  3421  3586 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
12-19 12:53:00.402  3421  3570 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
,12-19 12:53:00.402  3421  3570 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
12-19 12:53:00.412  3421  3574 I libsuspend: !@autosuspend_wakeup_count_enable
,12-19 12:53:00.412  3421  3574 D DisplayPowerController: animateScreenStateChange[0]: target=4
12-19 12:53:00.412  3421  3574 I libsuspend: !@autosuspend_wakeup_count_enable done
12-19 12:53:00.412  3421  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-19 12:53:00.412  3421  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
,12-19 12:53:00.412  3421  3574 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-19 12:53:00.412  3421  3574 D DisplayPowerController: animateScreenStateChange[0]: target=4
12-19 12:53:00.412  3421  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-19 12:53:00.412  3421  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-19 12:53:00.412  3421  3574 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-19 12:53:00.412  3421  3574 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
,12-19 12:53:00.412  3421  3574 D PowerManagerService: mDisplayReady: true
,12-19 12:53:00.412  3421  3574 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,12-19 12:53:00.442  5854  5854 E CocktailBarPositionManager: Window direction: 0
,12-19 12:53:00.442  5854  5854 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,12-19 12:53:00.572  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:00.682  6231  6231 D FactoryTest: User mode
,12-19 12:53:00.682  6231  6231 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
12-19 12:53:00.682  6231  6231 D MTPRx   : still no open session command from host, so toast
,12-19 12:53:00.702  3421  3472 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
12-19 12:53:00.702  3421  3472 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package com.samsung.android.MtpApplication
,12-19 12:53:00.702  3421  3472 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:53:00.712  3421  3472 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
,12-19 12:53:00.712  3421  3472 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.samsung.android.MtpApplication)
,12-19 12:53:00.712  3421  3472 D ActivityManager: mDVFSHelper.acquire()
,12-19 12:53:00.722  3421  3472 V WindowManager: addAppToken: AppWindowToken{d06047a07 token=Token{94f3846 ActivityRecord{ff71c21 u0 com.samsung.android.MtpApplication/.USBConnection t21}}} to stack=2 task=21 at 0
,12-19 12:53:00.722  3421  3472 D ActivityManager:  Launching com.samsung.android.MtpApplication, updated priority
,12-19 12:53:00.742  5854  5864 I TrayUsageStatesWatcher: noteResumeComponent : ComponentInfo{com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection} Intent { flg=0x10800000 cmp=com.samsung.android.MtpApplication/.USBConnection VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,12-19 12:53:00.742  3421  3421 D GameManagerService: NotifyRunnable. pkg: com.samsung.android.MtpApplication, type: 4, isMinimized: false, isTunableApp: false
,12-19 12:53:00.742  3421  3534 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
,12-19 12:53:00.752  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:00.762  5854  5865 I TrayUsageStatesWatcher: notePauseComponent : ComponentInfo{com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}
,12-19 12:53:00.762  3421  3472 D InputDispatcher: Focused application set to: xxxx
,12-19 12:53:00.772  6231  6231 E MTPRx   : started activity for popup
,12-19 12:53:00.772  6231  6231 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package com.samsung.android.MtpApplication
12-19 12:53:00.772  6231  6231 D RelationGraph: garbageCollect()
12-19 12:53:00.772  3421  6150 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
,12-19 12:53:00.772  3421  6150 D N       : limitCPUFreq:: freq = -1
12-19 12:53:00.772  3421  6150 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MAX_LIMIT  frequency : 2496000  uid : 1000  pid : 3421  tag : SIOP_ARM_MAX@22
,12-19 12:53:00.782  6231  6231 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package com.samsung.android.MtpApplication
,12-19 12:53:00.792  3421  6150 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,12-19 12:53:00.792  3421  6150 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
,12-19 12:53:00.802  3421  6150 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,12-19 12:53:00.802  6231  6231 D MTPUSBConnection: onCreate in USBConnection
,12-19 12:53:00.802  6231  6231 V MTPUSBConnection: Registering broadcast receiver.
,12-19 12:53:00.802  3421  6150 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
,12-19 12:53:00.802  3421  6150 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
,12-19 12:53:00.812  6231  6231 E MTPUSBConnection: AlertDialog Mode is : TIMEOUT
,12-19 12:53:00.812  3421  3472 D SecContentProvider2: query(), uri = 14 selection = getSealedState
,12-19 12:53:00.902  6231  6231 D TAG     : dev.kiessupport is : TRUE
,12-19 12:53:00.932  6231  6231 D SecWifiDisplayUtil: Metadata value : SecSettings2
,12-19 12:53:00.932  6231  6231 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{f552a0f V.E...... R.....I. 0,0-0,0}
,12-19 12:53:00.932  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:00.932  3421  4182 W WindowManager: Failed looking up window
12-19 12:53:00.932  3421  4182 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@c70a1e does not exist
12-19 12:53:00.932  3421  4182 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14805)
12-19 12:53:00.932  3421  4182 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
12-19 12:53:00.932  3421  4182 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
12-19 12:53:00.932  3421  4182 W WindowManager: 	at android.view.IWindowSession$Stub.onTransact(IWindowSession.java:688)
12-19 12:53:00.932  3421  4182 W WindowManager: 	at com.android.server.wm.Session.onTransact(Session.java:139)
12-19 12:53:00.932  3421  4182 W WindowManager: 	at android.os.Binder.execTransact(Binder.java:453)
,12-19 12:53:00.932  3421  4415 D ISSUE_DEBUG: InputChannelName : b08a2ff com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
,12-19 12:53:00.942  6231  6231 D Activity: performCreate Call Injection manager
,12-19 12:53:00.942  6231  6231 I InjectionManager: dispatchOnViewCreated > Target : com.samsung.android.MtpApplication.USBConnection isFragment :false
,12-19 12:53:00.952  6231  6231 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{2151246 I.E...... R.....I. 0,0-0,0}
,12-19 12:53:00.952  3421  4420 W WindowManager: Failed looking up window
12-19 12:53:00.952  3421  4420 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@49148cc does not exist
12-19 12:53:00.952  3421  4420 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14805)
12-19 12:53:00.952  3421  4420 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
12-19 12:53:00.952  3421  4420 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
12-19 12:53:00.952  3421  4420 W WindowManager: 	at android.view.IWindowSession$Stub.onTransact(IWindowSession.java:688)
12-19 12:53:00.952  3421  4420 W WindowManager: 	at com.android.server.wm.Session.onTransact(Session.java:139)
12-19 12:53:00.952  3421  4420 W WindowManager: 	at android.os.Binder.execTransact(Binder.java:453)
,12-19 12:53:00.962  3421  3984 D ISSUE_DEBUG: InputChannelName : fd25715 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
,12-19 12:53:00.962  3421  4391 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
,12-19 12:53:00.962  3421  4391 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
12-19 12:53:00.962  3421  3421 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,12-19 12:53:00.962  3421  3421 I KnoxTimeoutHandler: Shared devices show user statefalse
,12-19 12:53:00.962  3421  3421 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,12-19 12:53:00.992  3010  3010 I SurfaceFlinger: id=22 createSurf (193x193),1 flag=4, VSBConnecti
,12-19 12:53:01.022  3421  3882 D MdnieScenarioControlService:  packageName : com.samsung.android.MtpApplication    className : com.samsung.android.MtpApplication.USBConnection
,12-19 12:53:01.032  3421  3472 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3421
,12-19 12:53:01.032  3421  3472 I libsuspend: !@autosuspend_wakeup_count_disable
12-19 12:53:01.032  3421  3472 D PowerManagerService: mDisplayReady: false
,12-19 12:53:01.032  3421  3472 I libsuspend: !@autosuspend_wakeup_count_disable done
12-19 12:53:01.032  3421  3574 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-19 12:53:01.032  3010  3010 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fa2c03c00
,12-19 12:53:01.032  3421  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-19 12:53:01.032  3010  3010 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
12-19 12:53:01.032  3421  3472 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
12-19 12:53:01.032  3421  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
,12-19 12:53:01.032  3421  3574 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-19 12:53:01.032  3421  3586 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
12-19 12:53:01.032  3421  3570 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
12-19 12:53:01.042  3010  3055 W SurfaceFlinger: Ignoring duplicate VSYNC event from HWC (t=86912370822)
,12-19 12:53:01.032  3421  3570 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
12-19 12:53:01.042  5854  5854 I TrayVisibilityController: handleMessage : msg.what = 1
,12-19 12:53:01.052  3010  3010 I SurfaceFlinger: id=23 createSurf (257x257),1 flag=4, VSBConnecti
,12-19 12:53:01.052  3421  3574 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-19 12:53:01.052  3421  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-19 12:53:01.062  3421  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-19 12:53:01.062  3421  3574 I libsuspend: !@autosuspend_wakeup_count_enable
12-19 12:53:01.062  3421  3574 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-19 12:53:01.062  3421  3574 I libsuspend: !@autosuspend_wakeup_count_enable done
12-19 12:53:01.062  3421  3574 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-19 12:53:01.062  3421  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-19 12:53:01.062  3421  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-19 12:53:01.062  3421  3574 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-19 12:53:01.062  3421  3574 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
12-19 12:53:01.062  3421  3574 D PowerManagerService: mDisplayReady: true
12-19 12:53:01.062  3421  3574 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,12-19 12:53:01.062  5854  5854 I Utils   : isCurrentUser current = 0, ownerId = 0
,12-19 12:53:01.062  5854  5854 I TrayVisibilityController: getComputedTrayVisible : keyguardState = 3
12-19 12:53:01.062  5854  5854 I TrayVisibilityController: updateTrayVisible : State : 3 visible = 2 mCurrentVisible = 2
,12-19 12:53:01.062  5854  5854 E CocktailBarPositionManager: Window direction: 0
12-19 12:53:01.062  5854  5854 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,12-19 12:53:01.092  3421  4417 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3421
,12-19 12:53:01.102  6231  6231 V ActivityThread: updateVisibility : ActivityRecord{f800cd2 token=android.os.BinderProxy@fe38d77 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : true
,12-19 12:53:01.112  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:01.122  3421  3882 I MdnieScenarioControlService: mGameModeLauncher : false
,12-19 12:53:01.122  3421  3882 I MdnieScenarioControlService: setUIMode
,12-19 12:53:01.162  3421  3474 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3421
,12-19 12:53:01.172  3421  3984 V WindowStateAnimator: Finishing drawing window Window{b08a2ff u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,12-19 12:53:01.172  3421  4616 V WindowStateAnimator: Finishing drawing window Window{fd25715 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,12-19 12:53:01.172  6231  6231 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,12-19 12:53:01.182  3421  4421 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3421
,12-19 12:53:01.182  3421  3570 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
12-19 12:53:01.182  3421  3421 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,12-19 12:53:01.182  3421  3570 D ActivityManager: mDVFSHelper.release()
12-19 12:53:01.182  3421  3570 I ActivityManager: Displayed com.samsung.android.MtpApplication/.USBConnection: +421ms (total +462ms)
12-19 12:53:01.182  3421  4391 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3421
,12-19 12:53:01.182  6231  6231 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
12-19 12:53:01.182  3421  3570 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{ff71c21 u0 com.samsung.android.MtpApplication/.USBConnection t21} time:87054
12-19 12:53:01.182  3010  3010 D libEGL  : eglInitialize EGLDisplay = 0x7fdb1e6398
12-19 12:53:01.182  3010  3010 D libEGL  : eglInitialize EGLDisplay = 0x7fdb1e6398
,12-19 12:53:01.192  3421  3421 I KnoxTimeoutHandler: SD activityfalse
,12-19 12:53:01.212  3421  3474 V WindowStateAnimator: Finishing drawing window Window{b08a2ff u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
,12-19 12:53:01.212  3421  3853 V WindowStateAnimator: Finishing drawing window Window{fd25715 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
12-19 12:53:01.212  6231  6231 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@fe38d77 time:87085
,12-19 12:53:01.212  3010  3010 D libEGL  : eglInitialize EGLDisplay = 0x7fdb1e6398
,12-19 12:53:01.292  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:01.342  3421  3421 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3421 (0x0)
,12-19 12:53:01.342  3421  3421 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3421 (0x0)
12-19 12:53:01.342  3421  3421 I libsuspend: !@autosuspend_wakeup_count_disable
,12-19 12:53:01.342  3421  3421 D PowerManagerService: mDisplayReady: false
12-19 12:53:01.342  3421  3421 I libsuspend: !@autosuspend_wakeup_count_disable done
12-19 12:53:01.342  3421  3574 D DisplayPowerController: animateScreenStateChange[0]: target=4
,12-19 12:53:01.342  3421  3421 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
12-19 12:53:01.342  3421  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-19 12:53:01.342  3010  3010 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7fa2c03c00
12-19 12:53:01.342  3421  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
,12-19 12:53:01.342  3010  3010 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
12-19 12:53:01.342  3421  3574 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-19 12:53:01.342  3421  3586 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
12-19 12:53:01.342  3421  3570 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
,12-19 12:53:01.342  3421  3570 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
,12-19 12:53:01.362  3421  3574 D DisplayPowerController: animateScreenStateChange[0]: target=4
12-19 12:53:01.362  3421  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-19 12:53:01.362  3421  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-19 12:53:01.362  3421  3574 I libsuspend: !@autosuspend_wakeup_count_enable
12-19 12:53:01.362  3421  3574 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-19 12:53:01.362  3421  3574 I libsuspend: !@autosuspend_wakeup_count_enable done
12-19 12:53:01.362  3421  3574 D DisplayPowerController: animateScreenStateChange[0]: target=4
12-19 12:53:01.362  3421  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-19 12:53:01.362  3421  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-19 12:53:01.362  3421  3574 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-19 12:53:01.362  3421  3574 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
12-19 12:53:01.362  3421  3574 D PowerManagerService: mDisplayReady: true
12-19 12:53:01.362  3421  3574 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,12-19 12:53:01.372  5854  5854 E CocktailBarPositionManager: Window direction: 0
12-19 12:53:01.372  5854  5854 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,12-19 12:53:01.472  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:01.652  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:01.782  3421  6151 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package com.samsung.android.MtpApplication
,12-19 12:53:01.832  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:01.962  4025  4025 D Recents : onTaskStackChanged
,12-19 12:53:01.992  4025  4025 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.test.thalitest
,12-19 12:53:02.012  3421  4415 D PackageManager: getComponentMetadataForIconTray : com.test.thalitest.MainActivity does not exist in mServices
,12-19 12:53:02.012  3421  4415 D PackageManager: getComponentMetadataForIconTray : com.test.thalitest.MainActivity does not exist in mProviders
12-19 12:53:02.012  3421  4415 D PackageManager: getComponentMetadataForIconTray : com.test.thalitest.MainActivity does not exist in mReceivers
,12-19 12:53:02.012  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:02.022  4025  4025 I ApplicationPackageManager: load=com.test.thalitest, bg=192-192, dr=192-192
,12-19 12:53:02.022  4025  4025 I ApplicationPackageManager: scaled rate=0.97032255, size=192, alpha=3, hold=26, target=192
,12-19 12:53:02.192  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:02.372  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:02.562  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:02.572  3421  4391 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3421
,12-19 12:53:02.572  3421  4391 I libsuspend: !@autosuspend_wakeup_count_disable
12-19 12:53:02.572  3421  4391 D PowerManagerService: mDisplayReady: false
,12-19 12:53:02.572  3421  4391 I libsuspend: !@autosuspend_wakeup_count_disable done
12-19 12:53:02.572  3421  3574 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-19 12:53:02.572  3010  3010 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fa2c03c00
,12-19 12:53:02.572  3421  4391 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
12-19 12:53:02.572  3010  3010 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
12-19 12:53:02.572  3421  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
,12-19 12:53:02.572  3421  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-19 12:53:02.572  3421  3574 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-19 12:53:02.572  3421  3586 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
,12-19 12:53:02.572  3421  3570 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
,12-19 12:53:02.572  3421  3570 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
,12-19 12:53:02.602  3421  3574 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-19 12:53:02.602  3421  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-19 12:53:02.602  3421  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-19 12:53:02.612  3421  3574 I libsuspend: !@autosuspend_wakeup_count_enable
12-19 12:53:02.602  3421  3574 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-19 12:53:02.612  3421  3574 I libsuspend: !@autosuspend_wakeup_count_enable done
12-19 12:53:02.602  3421  3574 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-19 12:53:02.602  3421  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-19 12:53:02.602  3421  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-19 12:53:02.602  3421  3574 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-19 12:53:02.602  3421  3574 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
12-19 12:53:02.602  3421  3574 D PowerManagerService: mDisplayReady: true
,12-19 12:53:02.612  3421  3574 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,12-19 12:53:02.612  5854  5854 E CocktailBarPositionManager: Window direction: 0
12-19 12:53:02.612  5854  5854 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,12-19 12:53:02.622  3421  4417 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3421
,12-19 12:53:02.742  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:02.772  3421  3421 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3421 (0x0)
12-19 12:53:02.772  3421  3421 I libsuspend: !@autosuspend_wakeup_count_disable
12-19 12:53:02.772  3421  3421 D PowerManagerService: mDisplayReady: false
12-19 12:53:02.772  3421  3421 I libsuspend: !@autosuspend_wakeup_count_disable done
12-19 12:53:02.772  3421  3421 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
12-19 12:53:02.772  3421  3574 D DisplayPowerController: animateScreenStateChange[0]: target=4
12-19 12:53:02.772  3421  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-19 12:53:02.772  3421  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-19 12:53:02.772  3421  3574 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-19 12:53:02.772  3421  3586 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
12-19 12:53:02.772  3421  3570 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
12-19 12:53:02.772  3010  3010 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7fa2c03c00
12-19 12:53:02.772  3010  3010 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
12-19 12:53:02.772  3421  3570 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
,12-19 12:53:02.812  3421  3574 D DisplayPowerController: animateScreenStateChange[0]: target=4
12-19 12:53:02.812  3421  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-19 12:53:02.812  3421  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-19 12:53:02.812  3421  3574 I libsuspend: !@autosuspend_wakeup_count_enable
12-19 12:53:02.812  3421  3574 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-19 12:53:02.812  3421  3574 I libsuspend: !@autosuspend_wakeup_count_enable done
12-19 12:53:02.812  3421  3574 D DisplayPowerController: animateScreenStateChange[0]: target=4
12-19 12:53:02.812  3421  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-19 12:53:02.812  3421  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-19 12:53:02.812  3421  3574 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-19 12:53:02.812  3421  3574 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
12-19 12:53:02.812  3421  3574 D PowerManagerService: mDisplayReady: true
12-19 12:53:02.812  3421  3574 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,12-19 12:53:02.822  5854  5854 E CocktailBarPositionManager: Window direction: 0
12-19 12:53:02.822  5854  5854 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,12-19 12:53:02.922  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:03.102  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:03.282  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:03.462  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:03.642  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:03.822  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:03.882  3421  6185 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-19 12:53:04.002  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:04.172  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:04.362  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:04.532  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:04.722  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:04.902  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:05.082  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:05.252  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:05.442  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:05.622  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:05.802  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:05.972  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:06.152  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:06.342  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:06.522  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:06.572  3421  6150 D SSRM:n  : SIOP:: AP = 330, PST = 434 (W:9), CP = 290, CUR = 51, LCD = 1
,12-19 12:53:06.592  3421  6150 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,12-19 12:53:06.702  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:06.822  3421  6150 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,12-19 12:53:06.872  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:07.052  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:07.232  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:07.342  3421  4420 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-19 12:53:07.342  3421  4420 D BatteryService: level:99, scale:100, status:2, health:2, present:true, voltage: 4331, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 12:53:07.342  3421  4420 D BatteryService: online:4, current avg:141, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:206
12-19 12:53:07.342  3421  4420 D BatteryService: stay LED for charging
12-19 12:53:07.342  3421  3421 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-19 12:53:07.352  3421  3421 I MotionRecognitionService: Plugged
,12-19 12:53:07.352  3421  3421 D MotionRecognitionService:   cableConnection= 1
12-19 12:53:07.352  3421  3421 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-19 12:53:07.352  3421  3421 D MotionRecognitionService: skip setTransmitPower. 
,12-19 12:53:07.352  3421  3861 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-19 12:53:07.362  3938  3938 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
12-19 12:53:07.362  3938  3938 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-19 12:53:07.362  3938  3938 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-19 12:53:07.362  3938  3938 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : 252000 mChargingTime : 201000
12-19 12:53:07.362  3938  3938 D PowerUI.Notification: showChargingNotification()
,12-19 12:53:07.382  5096  5096 D CommonServiceConfiguration: getStringValueSetting
,12-19 12:53:07.382  3421  4989 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = -1
,12-19 12:53:07.382  5054  5054 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
12-19 12:53:07.392  5054  5457 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-19 12:53:07.392  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,12-19 12:53:07.392  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,12-19 12:53:07.392  5096  5096 D BatteryMonitor: new battery level: 99
,12-19 12:53:07.392  4740  4740 D BatteryController: saveBatteryData : level[99], status[2]
,12-19 12:53:07.402  3421  3421 D MARsPolicyManager: NotificationListenerService OngoingNotificationPosted : com.android.systemui
,12-19 12:53:07.412  4153  4165 D CatchNotificationsService: onNotificationPosted
,12-19 12:53:07.412  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:07.432  3938  3938 W ResourcesManager: getTopLevelResources: /system/priv-app/SystemUI/SystemUI.apk / 1.0 running in com.android.systemui rsrc of package com.android.systemui
,12-19 12:53:07.452  9410  9422 D BadgeProvider: query, [selection] : null
,12-19 12:53:07.452  3938  3938 D PhoneStatusBar: setAreThereNotifications: N=3 any=true clearable=false
,12-19 12:53:07.462  4153  4165 E CatchNotificationsService: Invalid notification data
,12-19 12:53:07.592  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:07.772  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:07.952  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:08.132  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:08.322  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:08.492  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:08.682  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:08.852  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:09.032  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:09.212  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:09.402  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:09.572  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:09.762  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:09.932  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:10.112  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:10.292  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:10.482  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:10.662  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:10.832  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:11.012  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:11.192  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:11.372  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:11.552  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:11.732  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:11.912  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:12.092  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:12.272  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:12.452  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:12.632  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:12.812  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:12.842  3421  3815 V AlarmManager: Expired Alarm result :4
,12-19 12:53:12.862  3421  3534 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ece701b u0 com.google.android.gms.gcm.ACTION_CHECK_QUEUE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4ade0f0 4335:com.google.android.gms.persistent/u0a21}
,12-19 12:53:12.882  3421  4415 V AlarmManager:  remove PendingIntent] PendingIntent{3f025b8: PendingIntentRecord{7477fb4 com.google.android.gms broadcastIntent}}
,12-19 12:53:12.982  3421  3474 V AlarmManager:  remove PendingIntent] PendingIntent{67c3ef6: PendingIntentRecord{7477fb4 com.google.android.gms broadcastIntent}}
,12-19 12:53:12.982  4335  4365 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@bb2a7ba)
,12-19 12:53:12.992  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:13.082  4335 10035 I VacuumService: Vacuum at: now=1482148393096 tag=VacuumService
,12-19 12:53:13.172  3421  4420 V AlarmManager:  remove PendingIntent] PendingIntent{93753cd: PendingIntentRecord{7477fb4 com.google.android.gms broadcastIntent}}
,12-19 12:53:13.172  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:13.352  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:13.532  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:13.712  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:13.892  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:14.072  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:14.252  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:14.432  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:14.612  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:14.792  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:14.972  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:15.152  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:15.332  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:15.512  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:15.692  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:15.872  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:16.052  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:16.232  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:16.412  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:16.592  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:16.652  3421  6150 D SSRM:n  : SIOP:: AP = 320, PST = 423 (W:10), CP = 282, CUR = 141, LCD = 1
,12-19 12:53:16.772  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:16.952  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:17.132  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:17.312  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:17.402  3421  3474 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-19 12:53:17.402  3421  3474 D BatteryService: level:99, scale:100, status:2, health:2, present:true, voltage: 4335, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 12:53:17.402  3421  3474 D BatteryService: online:4, current avg:176, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:236
12-19 12:53:17.402  3421  3474 D BatteryService: stay LED for charging
12-19 12:53:17.402  3421  3421 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-19 12:53:17.412  3421  3421 I MotionRecognitionService: Plugged
12-19 12:53:17.412  3421  3421 D MotionRecognitionService:   cableConnection= 1
12-19 12:53:17.412  3421  3421 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-19 12:53:17.412  3421  3421 D MotionRecognitionService: skip setTransmitPower. 
,12-19 12:53:17.412  3421  3861 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-19 12:53:17.412  3938  3938 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
12-19 12:53:17.422  3938  3938 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-19 12:53:17.422  3938  3938 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-19 12:53:17.422  3938  3938 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : 201000 mChargingTime : 201000
12-19 12:53:17.422  3938  3938 D PowerUI.Notification: There is no change about charging status, so return!
,12-19 12:53:17.442  5096  5096 D CommonServiceConfiguration: getStringValueSetting
,12-19 12:53:17.442  5054  5054 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
12-19 12:53:17.442  5054  5457 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-19 12:53:17.452  5096  5096 D BatteryMonitor: new battery level: 99
,12-19 12:53:17.452  4740  4740 D BatteryController: saveBatteryData : level[99], status[2]
,12-19 12:53:17.462  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,12-19 12:53:17.462  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,12-19 12:53:17.492  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:17.532  3421  4152 E Watchdog: !@Sync 3 [12-19 12:53:17.546]
,12-19 12:53:17.672  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:17.852  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:18.032  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:18.212  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:18.392  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:18.572  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:18.752  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:18.932  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:19.112  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:19.292  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:19.472  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:19.652  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:19.832  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:20.012  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:20.192  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:20.372  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:20.552  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:20.732  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:20.912  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:21.102  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:21.272  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:21.452  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:21.642  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:21.822  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:21.992  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:22.172  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:22.362  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:22.532  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:22.722  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:22.902  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:23.072  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:23.252  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:23.432  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:23.622  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:23.792  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:23.882  3421  6185 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-19 12:53:23.972  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:24.152  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:24.332  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:24.512  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:24.572  3153  3630 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,12-19 12:53:24.692  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:24.872  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:25.052  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:25.232  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:25.412  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:25.592  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:25.772  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:25.952  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:26.132  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:26.312  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:26.492  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:26.672  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:26.702  3421  6150 D SSRM:n  : SIOP:: AP = 320, PST = 408 (W:10), CP = 277, CUR = 176, LCD = 1
,12-19 12:53:26.852  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:27.032  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:27.212  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:27.392  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:27.462  3421  4182 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-19 12:53:27.462  3421  4182 D BatteryService: level:99, scale:100, status:2, health:2, present:true, voltage: 4338, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 12:53:27.462  3421  4182 D BatteryService: online:4, current avg:201, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:241
12-19 12:53:27.462  3421  4182 D BatteryService: stay LED for charging
12-19 12:53:27.462  3421  3421 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-19 12:53:27.472  3421  3421 I MotionRecognitionService: Plugged
12-19 12:53:27.472  3421  3421 D MotionRecognitionService:   cableConnection= 1
12-19 12:53:27.472  3421  3421 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-19 12:53:27.472  3421  3421 D MotionRecognitionService: skip setTransmitPower. 
,12-19 12:53:27.472  3421  3861 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-19 12:53:27.472  3938  3938 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-19 12:53:27.482  3938  3938 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-19 12:53:27.482  3938  3938 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-19 12:53:27.482  3938  3938 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : 201000 mChargingTime : 201000
12-19 12:53:27.482  3938  3938 D PowerUI.Notification: There is no change about charging status, so return!
,12-19 12:53:27.492  5096  5096 D CommonServiceConfiguration: getStringValueSetting
,12-19 12:53:27.502  5054  5054 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-19 12:53:27.502  5054  5457 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-19 12:53:27.502  5096  5096 D BatteryMonitor: new battery level: 99
,12-19 12:53:27.512  4740  4740 D BatteryController: saveBatteryData : level[99], status[2]
,12-19 12:53:27.522  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
12-19 12:53:27.522  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,12-19 12:53:27.572  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:27.752  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:27.932  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:28.112  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:28.292  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:28.472  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:28.652  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:28.832  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:29.012  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:29.192  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:29.372  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:29.552  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:29.732  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:29.912  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:30.092  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:30.272  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:30.452  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:30.632  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:30.812  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:30.992  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:31.172  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:31.352  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:31.532  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:31.712  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:31.892  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:32.072  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:32.252  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:32.432  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:32.612  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:32.792  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:32.972  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:33.152  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:33.332  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:33.512  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:33.692  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:33.872  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:34.052  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:34.232  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:34.412  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:34.592  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:34.772  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:34.952  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:35.132  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:35.312  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:35.492  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:35.562  3153  3630 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,12-19 12:53:35.672  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:35.852  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:36.032  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:36.212  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:36.392  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:36.572  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:36.732  3421  6150 D SSRM:n  : SIOP:: AP = 310, PST = 390 (W:10), CP = 273, CUR = 201, LCD = 1
,12-19 12:53:36.752  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:36.932  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:37.112  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:37.292  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:37.472  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:37.522  3421  3474 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,12-19 12:53:37.522  3421  3474 D BatteryService: level:99, scale:100, status:2, health:2, present:true, voltage: 4337, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 12:53:37.522  3421  3474 D BatteryService: online:4, current avg:207, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:221
12-19 12:53:37.522  3421  3474 D BatteryService: stay LED for charging
12-19 12:53:37.522  3421  3421 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-19 12:53:37.522  3421  3421 I MotionRecognitionService: Plugged
,12-19 12:53:37.522  3421  3421 D MotionRecognitionService:   cableConnection= 1
12-19 12:53:37.522  3421  3421 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-19 12:53:37.522  3421  3421 D MotionRecognitionService: skip setTransmitPower. 
,12-19 12:53:37.532  3421  3861 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-19 12:53:37.532  3938  3938 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
12-19 12:53:37.532  3938  3938 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-19 12:53:37.542  3938  3938 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-19 12:53:37.542  3938  3938 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : 201000 mChargingTime : 151000
,12-19 12:53:37.542  3938  3938 D PowerUI.Notification: showChargingNotification()
,12-19 12:53:37.552  5096  5096 D CommonServiceConfiguration: getStringValueSetting
,12-19 12:53:37.562  5054  5054 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-19 12:53:37.562  5054  5457 D HeadsetStateMachine: Disconnected process message: 10, size: 0
12-19 12:53:37.562  3421  4415 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = -1
,12-19 12:53:37.572  5096  5096 D BatteryMonitor: new battery level: 99
,12-19 12:53:37.572  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,12-19 12:53:37.572  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,12-19 12:53:37.582  4740  4740 D BatteryController: saveBatteryData : level[99], status[2]
,12-19 12:53:37.582  3421  3421 D MARsPolicyManager: NotificationListenerService OngoingNotificationPosted : com.android.systemui
,12-19 12:53:37.592  4153  4164 D CatchNotificationsService: onNotificationPosted
,12-19 12:53:37.612  3938  3938 W ResourcesManager: getTopLevelResources: /system/priv-app/SystemUI/SystemUI.apk / 1.0 running in com.android.systemui rsrc of package com.android.systemui
,12-19 12:53:37.622  9410  9422 D BadgeProvider: query, [selection] : null
,12-19 12:53:37.632  3938  3938 D PhoneStatusBar: setAreThereNotifications: N=3 any=true clearable=false
,12-19 12:53:37.632  4153  4164 E CatchNotificationsService: Invalid notification data
,12-19 12:53:37.642  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:37.832  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:38.012  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:38.192  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:38.372  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:38.552  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:38.732  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:38.912  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:39.092  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:39.272  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:39.452  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:39.632  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:39.812  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:39.992  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:40.172  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:40.352  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:40.532  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:40.712  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:40.892  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:41.072  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:41.252  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:41.432  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:41.612  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:41.792  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:41.972  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:42.152  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:42.332  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:42.512  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:42.682  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:42.872  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:43.052  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:43.222  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:43.402  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:43.592  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:43.762  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:43.872  3421  6185 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-19 12:53:43.942  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:44.132  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:44.312  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:44.492  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:44.672  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:44.842  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:45.022  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:45.202  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:45.392  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:45.572  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:45.752  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:45.932  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:46.102  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:46.292  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:46.472  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:46.652  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:46.762  3421  6150 D SSRM:n  : SIOP:: AP = 310, PST = 371 (W:10), CP = 269, CUR = 207, LCD = 1
,12-19 12:53:46.832  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:47.002  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:47.182  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:47.372  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:47.532  3421  4152 E Watchdog: !@Sync 4 [12-19 12:53:47.547]
,12-19 12:53:47.542  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:47.582  3421  3981 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-19 12:53:47.582  3421  3981 D BatteryService: level:99, scale:100, status:2, health:2, present:true, voltage: 4340, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 12:53:47.582  3421  3981 D BatteryService: online:4, current avg:207, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:215
12-19 12:53:47.582  3421  3981 D BatteryService: stay LED for charging
12-19 12:53:47.582  3421  3421 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-19 12:53:47.582  3421  3421 I MotionRecognitionService: Plugged
,12-19 12:53:47.582  3421  3421 D MotionRecognitionService:   cableConnection= 1
12-19 12:53:47.582  3421  3421 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-19 12:53:47.582  3421  3421 D MotionRecognitionService: skip setTransmitPower. 
,12-19 12:53:47.592  3421  3861 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-19 12:53:47.592  3938  3938 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-19 12:53:47.592  3938  3938 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-19 12:53:47.602  3938  3938 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-19 12:53:47.602  3938  3938 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : 151000 mChargingTime : 151000
12-19 12:53:47.602  3938  3938 D PowerUI.Notification: There is no change about charging status, so return!
,12-19 12:53:47.622  5096  5096 D CommonServiceConfiguration: getStringValueSetting
,12-19 12:53:47.622  5054  5054 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
12-19 12:53:47.622  5054  5457 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-19 12:53:47.632  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
12-19 12:53:47.632  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,12-19 12:53:47.632  5096  5096 D BatteryMonitor: new battery level: 99
,12-19 12:53:47.632  4740  4740 D BatteryController: saveBatteryData : level[99], status[2]
,12-19 12:53:47.722  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:47.912  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:48.082  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:48.262  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:48.442  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:48.632  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:48.762  4400  4465 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
12-19 12:53:48.762  4400  4465 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,12-19 12:53:48.802  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:48.992  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:49.162  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:49.342  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:49.532  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:49.712  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:49.882  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:50.072  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:50.242  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:50.422  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:50.612  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:50.792  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:50.972  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:51.152  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:51.332  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:51.512  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:51.682  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:51.862  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:52.042  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:52.232  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:52.412  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:52.582  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:52.772  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:52.942  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:53.122  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:53.312  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:53.482  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:53.662  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:53.852  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:54.022  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:54.202  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:54.382  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:54.562  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:54.742  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:54.932  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:55.102  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:55.292  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:55.472  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:55.652  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:55.832  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:56.012  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:56.182  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:56.362  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:56.552  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:56.732  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:56.812  3421  6150 D SSRM:n  : SIOP:: AP = 310, PST = 354 (W:10), CP = 267, CUR = 207, LCD = 1
,12-19 12:53:56.912  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:57.082  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:57.272  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:57.442  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:57.622  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:57.642  3421  4182 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,12-19 12:53:57.642  3421  4182 D BatteryService: level:99, scale:100, status:2, health:2, present:true, voltage: 4340, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 12:53:57.642  3421  4182 D BatteryService: online:4, current avg:216, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:229
12-19 12:53:57.642  3421  4182 D BatteryService: stay LED for charging
12-19 12:53:57.642  3421  3421 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-19 12:53:57.652  3421  3421 I MotionRecognitionService: Plugged
12-19 12:53:57.652  3421  3421 D MotionRecognitionService:   cableConnection= 1
12-19 12:53:57.652  3421  3421 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-19 12:53:57.652  3421  3421 D MotionRecognitionService: skip setTransmitPower. 
,12-19 12:53:57.652  3421  3861 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-19 12:53:57.652  3938  3938 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
12-19 12:53:57.662  3938  3938 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-19 12:53:57.662  3938  3938 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-19 12:53:57.662  3938  3938 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : 151000 mChargingTime : 151000
,12-19 12:53:57.662  3938  3938 D PowerUI.Notification: There is no change about charging status, so return!
,12-19 12:53:57.672  5096  5096 D CommonServiceConfiguration: getStringValueSetting
,12-19 12:53:57.682  5054  5054 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-19 12:53:57.682  5054  5457 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-19 12:53:57.682  5096  5096 D BatteryMonitor: new battery level: 99
,12-19 12:53:57.692  4740  4740 D BatteryController: saveBatteryData : level[99], status[2]
,12-19 12:53:57.712  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
12-19 12:53:57.712  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,12-19 12:53:57.802  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:57.982  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:58.162  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:58.352  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:58.532  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:58.712  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:58.882  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:59.072  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:59.252  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:59.432  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:59.602  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:59.782  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:59.962  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:53:59.982  3421  3815 V AlarmManager: Expired Alarm result :8
,12-19 12:54:00.142  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:00.252  3421  3815 V AlarmManager: Expired Alarm result :4
,12-19 12:54:00.252  3421  3815 V AlarmManager: Send whitelist package alarm :PendingIntent{1a10a88: PendingIntentRecord{3f94b70 com.samsung.android.app.aodservice broadcastIntent}}
,12-19 12:54:00.252  3938  3938 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK,
12-19 12:54:00.252  3938  3938 D KeyguardUpdateMonitor: handleTimeUpdate
,12-19 12:54:00.262  3938  3938 D Clock   : received broadcast android.intent.action.TIME_TICK
,12-19 12:54:00.322  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:00.322  3938  3938 D DateView: received broadcast android.intent.action.TIME_TICK
,12-19 12:54:00.352  8036  8036 D [WeatherWidget(1240)]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,12-19 12:54:00.352  8036  8036 D [WeatherWidget(1240)]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,12-19 12:54:00.362  4740  4740 D AODService.ClockTimer: onReceive : com.samsung.android.app.aodservice.ClockTimer.TICK, mWakeUp = true
12-19 12:54:00.362  4740  4740 V BatteryController: getBatteryLevel[99.0], batteryStatus[2]
,12-19 12:54:00.362  3421  3981 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,12-19 12:54:00.362  3421  3981 I CAE     : setPropertyValue(DevicePhysicalContextMonitorRunner.java:155) - Get status
,12-19 12:54:00.362  3421  3981 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -72, 56, 1, 1,
12-19 12:54:00.362  3421  3981 D SensorHubManager: SendSensorHubData: send data = -72, 56, 1, 1
,12-19 12:54:00.362  3168  3168 D Sensorhubs: sendContextData: -72, 56, 1, 1
,12-19 12:54:00.372  3421  3981 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
12-19 12:54:00.372  3421  3981 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,12-19 12:54:00.372  3421  3981 D SContextService: requestToUpdate() : service = Device Physical Context Monitor
12-19 12:54:00.372  4740  4740 D SContextManager:   .requestToUpdate : listener = com.samsung.android.app.aodservice.AODService$7@63b629b, service=Device Physical Context Monitor
12-19 12:54:00.372  4740  4740 I AlpmModeManager: startAlpmMode : state  = BLANK
12-19 12:54:00.372  4740  4740 D DefaultClockView: Window showed. Time views updating
,12-19 12:54:00.372  3421  4420 I libsuspend: !@autosuspend_wakeup_count_disable
12-19 12:54:00.372  3421  4420 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3421
12-19 12:54:00.372  3421  4420 I libsuspend: !@autosuspend_wakeup_count_disable done
12-19 12:54:00.372  3421  4420 D PowerManagerService: mDisplayReady: false
12-19 12:54:00.372  4740  4740 D AODUpdatePositionController: updatePosition: direction[2] updatePosition: X[26] Y[221] NewPositionTimer[58]
12-19 12:54:00.372  3421  3574 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-19 12:54:00.372  3010  3010 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fa2c03c00
12-19 12:54:00.372  3421  4420 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
12-19 12:54:00.372  3010  3010 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
12-19 12:54:00.372  3421  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-19 12:54:00.372  4740  4740 D DefaultClockView: LocalTime Pattern : HH:mm
12-19 12:54:00.372  3421  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
,12-19 12:54:00.372  3421  3574 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-19 12:54:00.372  3421  3586 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
12-19 12:54:00.372  3421  3570 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
12-19 12:54:00.372  3421  3570 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
,12-19 12:54:00.382  4740  4740 D TimeViewHolder: onTimeUpdate: timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] isSplitHour:false isSingleView:false isAMPMonLeft:null time01: 12:54 time02: null ampm: null
,12-19 12:54:00.382  3168  3213 D Sensorhubs: readContextData: 1, 1, 56, 1, 1, 1, 1
,12-19 12:54:00.382  3421  3818 D SensorHubManager: onGetSensorHubDataLocked: library(7) = 1, 1, 56, 1, 1, 1, 1
12-19 12:54:00.382  3421  3817 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 14, 11, 54, 0,
12-19 12:54:00.382  3421  3817 D SensorHubManager: SendSensorHubData: send data = -63, 14, 11, 54, 0
,12-19 12:54:00.392  3421  3574 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-19 12:54:00.392  3421  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-19 12:54:00.392  3421  3574 I libsuspend: !@autosuspend_wakeup_count_enable
12-19 12:54:00.392  3421  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-19 12:54:00.392  3421  3574 I libsuspend: !@autosuspend_wakeup_count_enable done
12-19 12:54:00.392  3421  3574 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-19 12:54:00.392  3421  3574 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-19 12:54:00.392  3421  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-19 12:54:00.392  3421  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-19 12:54:00.392  3421  3574 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-19 12:54:00.392  3421  3574 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
12-19 12:54:00.392  3421  3574 D PowerManagerService: mDisplayReady: true
12-19 12:54:00.392  3421  3574 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,12-19 12:54:00.392  3168  3214 D Sensorhubs: sendContextData: -63, 14, 11, 54, 0
,12-19 12:54:00.392  5854  5854 E CocktailBarPositionManager: Window direction: 0
12-19 12:54:00.392  5854  5854 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,12-19 12:54:00.402  3421  3817 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :7], AP_SLEEP
,12-19 12:54:00.402  3421  3817 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 7
12-19 12:54:00.402  3421  3817 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 56, 1, 1, 1, 1,
,12-19 12:54:00.402  3421  3817 D CAE     : display(ContextProvider.java:375) - ================= DEVICE_PHYSICAL_CONTEXT_MONITOR =================
,12-19 12:54:00.402  3421  3817 I CAE     : display(ContextProvider.java:391) - AODReason=[1], AODStatus=[1], DataType=[1]
,12-19 12:54:00.402  3421  3820 D SContextService: updateSContext() : event = Device Physical Context Monitor
,12-19 12:54:00.402  4740  4740 D RoamingTimeViewHolder: isDualClockSetting :: true isHomeTimeZoneExist :: false isEasyUxON :: false Utils.isRoaming(mContext) :: false
,12-19 12:54:00.402  4740  4740 D RoamingTimeViewHolder: getHomeCalendar : No homecity_timezone, set as default :  (libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167])
,12-19 12:54:00.412  4740  4740 D RoamingTimeViewHolder: onTimeUpdate: isVisible:false timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] text:pon., 19 gru 12:54
,12-19 12:54:00.412  4740  4740 I AODService.ClockTimer: startAlarm : TICK
12-19 12:54:00.412  3421  4417 V AlarmManager: Add whitelist package alarm :PendingIntent{7c5f3d0: PendingIntentRecord{3f94b70 com.samsung.android.app.aodservice broadcastIntent}}
,12-19 12:54:00.412  4740  4740 I AlpmModeManager: handleUnblankDisplay: state  = BLANK
,12-19 12:54:00.412  4740  4740 V AlpmModeManager: updateAlpmMode: setDoze [DISPLAY_STATE_DOZE_SUSPEND]
12-19 12:54:00.412  3421  4415 I PowerManagerService: [api] setDozeOverrideFromAod AlpmHlpmSysfs = -1, screenState = 4, Brightness = 0, wakefulness = false
12-19 12:54:00.412  3421  4415 D PowerManagerService: setDozeModeBySysfs:  value is -1 , we ignore it. 
,12-19 12:54:00.412  3421  4182 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3421
,12-19 12:54:00.412  4740  4740 I AODService: onSContextChanged: AODScreenShown state is already true
12-19 12:54:00.412  4740  4740 D DefaultClockView: RootView invalidate()
12-19 12:54:00.422  3421  4570 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3421
,12-19 12:54:00.502  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:00.572  3421  3421 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3421 (0x0)
,12-19 12:54:00.572  3421  3421 I libsuspend: !@autosuspend_wakeup_count_disable
12-19 12:54:00.572  3421  3421 D PowerManagerService: mDisplayReady: false
12-19 12:54:00.572  3421  3421 I libsuspend: !@autosuspend_wakeup_count_disable done
12-19 12:54:00.572  3421  3574 D DisplayPowerController: animateScreenStateChange[0]: target=4
,12-19 12:54:00.572  3421  3421 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
12-19 12:54:00.572  3010  3010 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7fa2c03c00
12-19 12:54:00.572  3421  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
,12-19 12:54:00.572  3010  3010 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
12-19 12:54:00.572  3421  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
,12-19 12:54:00.572  3421  3574 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-19 12:54:00.572  3421  3586 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
,12-19 12:54:00.572  3421  3570 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
,12-19 12:54:00.572  3421  3570 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
,12-19 12:54:00.582  3421  3574 D DisplayPowerController: animateScreenStateChange[0]: target=4
12-19 12:54:00.582  3421  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-19 12:54:00.582  3421  3574 I libsuspend: !@autosuspend_wakeup_count_enable
12-19 12:54:00.582  3421  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-19 12:54:00.582  3421  3574 I libsuspend: !@autosuspend_wakeup_count_enable done
12-19 12:54:00.582  3421  3574 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-19 12:54:00.582  3421  3574 D DisplayPowerController: animateScreenStateChange[0]: target=4
12-19 12:54:00.582  3421  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-19 12:54:00.582  3421  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-19 12:54:00.582  3421  3574 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-19 12:54:00.582  3421  3574 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
12-19 12:54:00.582  3421  3574 D PowerManagerService: mDisplayReady: true
12-19 12:54:00.582  3421  3574 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,12-19 12:54:00.602  5854  5854 E CocktailBarPositionManager: Window direction: 0
12-19 12:54:00.602  5854  5854 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,12-19 12:54:00.682  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:00.862  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:01.042  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:01.232  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:01.412  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:01.582  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:01.772  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:01.952  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:02.122  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:02.312  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:02.492  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:02.672  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:02.852  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:03.022  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:03.202  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:03.382  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:03.562  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:03.752  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:03.882  3421  6185 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-19 12:54:03.932  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:04.112  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:04.292  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:04.472  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:04.652  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:04.822  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:05.002  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:05.182  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:05.362  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:05.552  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:05.722  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:05.912  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:06.082  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:06.272  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:06.442  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:06.622  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:06.812  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:06.872  3421  6150 D SSRM:n  : SIOP:: AP = 300, PST = 341 (W:14), CP = 265, CUR = 216, LCD = 1
,12-19 12:54:06.992  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:07.162  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:07.352  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:07.532  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:07.702  3421  3474 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,12-19 12:54:07.702  3421  3474 D BatteryService: level:99, scale:100, status:2, health:2, present:true, voltage: 4341, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 12:54:07.702  3421  3474 D BatteryService: online:4, current avg:212, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:229
12-19 12:54:07.702  3421  3421 D BatteryService: Sending ACTION_BATTERY_CHANGED.
12-19 12:54:07.702  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:07.702  3421  3474 D BatteryService: stay LED for charging
,12-19 12:54:07.712  3421  3421 I MotionRecognitionService: Plugged
12-19 12:54:07.712  3421  3421 D MotionRecognitionService:   cableConnection= 1
12-19 12:54:07.712  3421  3421 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-19 12:54:07.712  3421  3421 D MotionRecognitionService: skip setTransmitPower. 
,12-19 12:54:07.712  3421  3861 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-19 12:54:07.722  3938  3938 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-19 12:54:07.722  3938  3938 D KeyguardUpdateMonitor: handleBatteryUpdate
12-19 12:54:07.722  3938  3938 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-19 12:54:07.722  3938  3938 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : 151000 mChargingTime : 151000
,12-19 12:54:07.722  3938  3938 D PowerUI.Notification: There is no change about charging status, so return!
,12-19 12:54:07.732  5096  5096 D CommonServiceConfiguration: getStringValueSetting
,12-19 12:54:07.742  5054  5054 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
12-19 12:54:07.742  5054  5457 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-19 12:54:07.742  5096  5096 D BatteryMonitor: new battery level: 99
,12-19 12:54:07.752  4740  4740 D BatteryController: saveBatteryData : level[99], status[2]
,12-19 12:54:07.762  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,12-19 12:54:07.762  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,12-19 12:54:07.882  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:08.062  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:08.242  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:08.422  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:08.602  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:08.782  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:08.962  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:09.142  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:09.322  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:09.502  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:09.682  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:09.862  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:10.042  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:10.222  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:10.402  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:10.582  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:10.762  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:10.942  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:11.122  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:11.302  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:11.482  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:11.662  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:11.842  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:12.022  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:12.202  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:12.382  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:12.562  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:12.742  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:12.872  3421  3815 V AlarmManager: Expired Alarm result :4
,12-19 12:54:12.882  3421  3534 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{25836ce u0 com.google.android.gms.gcm.ACTION_CHECK_QUEUE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4ade0f0 4335:com.google.android.gms.persistent/u0a21}
,12-19 12:54:12.902  3421  3983 V AlarmManager:  remove PendingIntent] PendingIntent{19649ef: PendingIntentRecord{7477fb4 com.google.android.gms broadcastIntent}}
,12-19 12:54:12.922  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:12.982  4637 10044 D UdcContextInitService: registered all accounts: true
,12-19 12:54:13.072  3421  4333 V AlarmManager:  remove PendingIntent] PendingIntent{a382f85: PendingIntentRecord{7477fb4 com.google.android.gms broadcastIntent}}
,12-19 12:54:13.102  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:13.282  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:13.332  4335 10048 I PhenotypeConfigurator: Scheduling Phenotype for one-off execution 2419 seconds from now (1482148453347)
,12-19 12:54:13.372  3421  3534 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1dfe232 u0 com.google.android.gms.gcm.ACTION_SCHEDULE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4ade0f0 4335:com.google.android.gms.persistent/u0a21}
,12-19 12:54:13.432  4335 10046 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,12-19 12:54:13.432  4335 10046 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,12-19 12:54:13.462  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:13.642  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:13.662  4335 10046 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-19 12:54:13.662  4335 10046 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,12-19 12:54:13.672  3153  3634 D EnterpriseController: netId is 0
12-19 12:54:13.672  3153  3634 D Netd    : getNetworkForDns: using netid 502 for uid 10021
,12-19 12:54:13.742  4335 10046 I qtaguid : Tagging socket 63 with tag 1000120100000000{268440065,0} uid -1, pid: 4335, getuid(): 10021
,12-19 12:54:13.782  4335 10046 I qtaguid : Tagging socket 67 with tag 1000120100000000{268440065,0} uid -1, pid: 4335, getuid(): 10021
,12-19 12:54:13.822  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:14.002  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:14.082  4335 10046 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-19 12:54:14.082  4335 10046 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-19 12:54:14.082  4335 10046 I qtaguid : Tagging socket 63 with tag 1000120100000000{268440065,0} uid -1, pid: 4335, getuid(): 10021
,12-19 12:54:14.182  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:14.362  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:14.382  4335 10046 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-19 12:54:14.382  4335 10046 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-19 12:54:14.382  4335 10046 I qtaguid : Tagging socket 63 with tag 1000120100000000{268440065,0} uid -1, pid: 4335, getuid(): 10021
,12-19 12:54:14.522  3421  4391 V AlarmManager:  remove PendingIntent] PendingIntent{3b91d2c: PendingIntentRecord{7477fb4 com.google.android.gms broadcastIntent}}
,12-19 12:54:14.542  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:14.732  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:14.902  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:15.082  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:15.262  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:15.452  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:15.622  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:15.802  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:15.992  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:16.162  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:16.352  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:16.532  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:16.712  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:16.882  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:16.922  3421  6150 D SSRM:n  : SIOP:: AP = 300, PST = 317 (W:14), CP = 264, CUR = 212, LCD = 1
,12-19 12:54:16.952  3421  6150 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,12-19 12:54:17.062  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:17.242  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:17.422  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:17.542  3421  4152 E Watchdog: !@Sync 5 [12-19 12:54:17.549]
,12-19 12:54:17.602  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:17.762  3421  3472 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,12-19 12:54:17.762  3421  3472 D BatteryService: level:99, scale:100, status:2, health:2, present:true, voltage: 4342, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 12:54:17.762  3421  3472 D BatteryService: online:4, current avg:201, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:242
12-19 12:54:17.762  3421  3472 D BatteryService: stay LED for charging
12-19 12:54:17.762  3421  3421 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-19 12:54:17.772  3421  3421 I MotionRecognitionService: Plugged
12-19 12:54:17.772  3421  3421 D MotionRecognitionService:   cableConnection= 1
12-19 12:54:17.772  3421  3421 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-19 12:54:17.772  3421  3421 D MotionRecognitionService: skip setTransmitPower. 
,12-19 12:54:17.772  3421  3861 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-19 12:54:17.772  3938  3938 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
12-19 12:54:17.782  3938  3938 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-19 12:54:17.782  3938  3938 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-19 12:54:17.782  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:17.782  3938  3938 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : 151000 mChargingTime : 151000
12-19 12:54:17.782  3938  3938 D PowerUI.Notification: There is no change about charging status, so return!
,12-19 12:54:17.802  5096  5096 D CommonServiceConfiguration: getStringValueSetting
,12-19 12:54:17.812  5054  5054 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
12-19 12:54:17.812  5054  5457 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-19 12:54:17.812  4740  4740 D BatteryController: saveBatteryData : level[99], status[2]
12-19 12:54:17.812  5096  5096 D BatteryMonitor: new battery level: 99
,12-19 12:54:17.832  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,12-19 12:54:17.832  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,12-19 12:54:17.962  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:18.142  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:18.322  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:18.502  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:18.682  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:18.862  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:19.042  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:19.222  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:19.402  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:19.582  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:19.762  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:19.942  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:20.122  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:20.302  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:20.482  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:20.662  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:20.842  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:21.022  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:21.202  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:21.382  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:21.562  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:21.742  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:21.922  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:22.102  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:22.282  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:22.462  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:22.642  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:22.822  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:23.002  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:23.182  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:23.362  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:23.542  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:23.722  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:23.892  3421  6185 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-19 12:54:23.902  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:24.082  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:24.262  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:24.442  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:24.622  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:24.802  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:24.982  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:25.162  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:25.342  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:25.522  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:25.702  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:25.882  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:26.062  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:26.242  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:26.422  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:26.602  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:26.782  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:26.962  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:26.982  3421  6150 D SSRM:n  : SIOP:: AP = 300, PST = 310 (W:14), CP = 263, CUR = 201, LCD = 1
,12-19 12:54:27.142  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:27.322  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:27.502  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:27.682  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:27.822  3421  3981 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-19 12:54:27.822  3421  3981 D BatteryService: level:99, scale:100, status:2, health:2, present:true, voltage: 4342, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 12:54:27.822  3421  3981 D BatteryService: online:4, current avg:212, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:203
12-19 12:54:27.822  3421  3981 D BatteryService: stay LED for charging
12-19 12:54:27.822  3421  3421 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-19 12:54:27.822  3421  3421 I MotionRecognitionService: Plugged
,12-19 12:54:27.822  3421  3421 D MotionRecognitionService:   cableConnection= 1
12-19 12:54:27.822  3421  3421 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,12-19 12:54:27.822  3421  3421 D MotionRecognitionService: skip setTransmitPower. 
,12-19 12:54:27.832  3421  3861 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-19 12:54:27.832  3938  3938 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-19 12:54:27.832  3938  3938 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-19 12:54:27.832  3938  3938 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-19 12:54:27.842  3938  3938 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : 151000 mChargingTime : 151000
,12-19 12:54:27.842  3938  3938 D PowerUI.Notification: There is no change about charging status, so return!
,12-19 12:54:27.852  5096  5096 D CommonServiceConfiguration: getStringValueSetting
,12-19 12:54:27.862  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:27.862  5054  5054 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-19 12:54:27.862  5054  5457 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-19 12:54:27.862  4740  4740 D BatteryController: saveBatteryData : level[99], status[2]
,12-19 12:54:27.872  5096  5096 D BatteryMonitor: new battery level: 99
,12-19 12:54:27.882  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,12-19 12:54:27.882  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,12-19 12:54:28.042  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:28.222  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:28.402  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:28.582  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:28.762  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:28.942  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:29.122  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:29.302  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:29.482  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:29.492  3153  3630 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,12-19 12:54:29.662  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:29.842  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:30.022  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:30.202  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:30.382  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:30.562  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:30.742  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:30.922  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:31.102  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:31.282  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:31.462  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:31.642  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:31.822  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:32.002  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:32.182  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:32.362  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:32.542  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:32.722  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:32.902  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:33.082  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:33.262  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:33.442  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:33.622  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:33.802  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:33.982  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:34.162  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:34.342  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:34.522  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:34.702  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:34.882  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:35.062  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:35.222  3421  6151 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.N.run:-1 android.os.Handler.handleCallback:739 
,12-19 12:54:35.232  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:35.242  3421  3534 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{da6ea71 u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d35c157 9523:com.samsung.android.sm.provider/1000}
,12-19 12:54:35.262  3421  6151 W ResourcesManager: getTopLevelResources: /system/app/Bluetooth/Bluetooth.apk / 1.0 running in null rsrc of package com.android.bluetooth
,12-19 12:54:35.262  3421  6151 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:54:35.272  3421  6151 W ResourcesManager: getTopLevelResources: /system/app/bootagent/bootagent.apk / 1.0 running in null rsrc of package com.samsung.ucs.agent.boot
,12-19 12:54:35.272  3421  6151 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:54:35.272  3421  6151 W ResourcesManager: getTopLevelResources: /system/app/BriefingPanel/BriefingPanel.apk / 1.0 running in null rsrc of package com.samsung.android.widgetapp.briefing
,12-19 12:54:35.272  3421  6151 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:54:35.282  3421  6151 W ResourcesManager: getTopLevelResources: /system/app/BluetoothTest/BluetoothTest.apk / 1.0 running in null rsrc of package com.sec.android.app.bluetoothtest
,12-19 12:54:35.282  3421  6151 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:54:35.282  3421  6151 W ResourcesManager: getTopLevelResources: /system/priv-app/SystemUI/SystemUI.apk / 1.0 running in null rsrc of package com.android.systemui
,12-19 12:54:35.282  3421  6151 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,12-19 12:54:35.282  3421  6151 W ResourcesManager: getTopLevelResources: /system/app/imsservice/imsservice.apk / 1.0 running in null rsrc of package com.sec.imsservice
,12-19 12:54:35.292  3421  6151 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:54:35.292  3421  6151 W ResourcesManager: getTopLevelResources: /system/priv-app/PeopleStripe/PeopleStripe.apk / 1.0 running in null rsrc of package com.samsung.android.service.peoplestripe
,12-19 12:54:35.292  3421  6151 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:54:35.302  3421  6151 W ResourcesManager: getTopLevelResources: /system/app/EdmSimPinService/EdmSimPinService.apk / 1.0 running in null rsrc of package com.sec.enterprise.mdm.services.simpin
,12-19 12:54:35.302  3421  6151 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:54:35.302  3421  6151 W ResourcesManager: getTopLevelResources: /system/app/SamsungTTS/SamsungTTS.apk / 1.0 running in null rsrc of package com.samsung.SMT
,12-19 12:54:35.302  3421  6151 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:54:35.302  3421  6151 W ResourcesManager: getTopLevelResources: /system/app/AntHalService/AntHalService.apk / 1.0 running in null rsrc of package com.dsi.ant.server
,12-19 12:54:35.302  3421  6151 W ResourcesManager: getTopLevelResources: /system/priv-app/SVoice_1.0/SVoice_1.0.apk / 1.0 running in null rsrc of package com.samsung.voiceserviceplatform
,12-19 12:54:35.312  3421  6151 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:54:35.312  3421  6151 W ResourcesManager: getTopLevelResources: /system/priv-app/NSFusedLocation_Global/NSFusedLocation_Global.apk / 1.0 running in null rsrc of package com.sec.location.nsflp2
,12-19 12:54:35.312  3421  6151 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:54:35.312  3421  6151 W ResourcesManager: getTopLevelResources: /system/app/ESEServiceAgent/ESEServiceAgent.apk / 1.0 running in null rsrc of package com.samsung.ucs.agent.ese
,12-19 12:54:35.312  3421  6151 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:54:35.322  3421  6151 W ResourcesManager: getTopLevelResources: /system/priv-app/CSC/CSC.apk / 1.0 running in null rsrc of package com.samsung.sec.android.application.csc
,12-19 12:54:35.322  3421  6151 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:54:35.322  3421  6151 W ResourcesManager: getTopLevelResources: /system/app/TuiService/TuiService.apk / 1.0 running in null rsrc of package com.trustonic.tuiservice
,12-19 12:54:35.322  3421  6151 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:54:35.322  3421  6151 W ResourcesManager: getTopLevelResources: /system/priv-app/AODService/AODService.apk / 1.0 running in null rsrc of package com.samsung.android.app.aodservice
,12-19 12:54:35.322  3421  6151 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:54:35.322  3421  6151 W ResourcesManager: getTopLevelResources: /system/framework/framework-res.apk / 1.0 running in null rsrc of package android
,12-19 12:54:35.332  3421  6151 W ResourcesManager: getTopLevelResources: /system/priv-app/Telecom/Telecom.apk / 1.0 running in null rsrc of package com.android.server.telecom
,12-19 12:54:35.332  3421  6151 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartcardManager/SmartcardManager.apk / 1.0 running in null rsrc of package com.sec.smartcard.manager
,12-19 12:54:35.332  3421  6151 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:54:35.332  3421  6151 W ResourcesManager: getTopLevelResources: /system/app/Stk/Stk.apk / 1.0 running in null rsrc of package com.android.stk
,12-19 12:54:35.332  3421  6151 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:54:35.342  3421  6151 W ResourcesManager: getTopLevelResources: /system/app/Stk/Stk.apk / 1.0 running in null rsrc of package com.android.stk
,12-19 12:54:35.342  3421  6151 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package com.android.chrome
,12-19 12:54:35.342  3421  6151 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMediaProvider/SecMediaProvider.apk / 1.0 running in null rsrc of package com.android.providers.media
,12-19 12:54:35.342  3421  6151 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:54:35.352  3421  6151 W ResourcesManager: getTopLevelResources: /system/priv-app/ContextProvider/ContextProvider.apk / 1.0 running in null rsrc of package com.samsung.android.providers.context
,12-19 12:54:35.352  3421  6151 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:54:35.352  3421  6151 W ResourcesManager: getTopLevelResources: /system/priv-app/CocktailBarService/CocktailBarService.apk / 1.0 running in null rsrc of package com.samsung.android.app.cocktailbarservice
,12-19 12:54:35.352  3421  6151 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:54:35.352  3421  6151 W ResourcesManager: getTopLevelResources: /system/app/Stk2/Stk2.apk / 1.0 running in null rsrc of package com.android.stk2
,12-19 12:54:35.352  3421  6151 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:54:35.352  3421  6151 W ResourcesManager: getTopLevelResources: /system/app/Stk2/Stk2.apk / 1.0 running in null rsrc of package com.android.stk2
,12-19 12:54:35.362  3421  6151 W ResourcesManager: getTopLevelResources: /data/app/de.axelspringer.yana.zeropage-2/base.apk / 1.0 running in null rsrc of package de.axelspringer.yana.zeropage
12-19 12:54:35.362  3421  6151 W ResourcesManager: getTopLevelResources: /system/priv-app/TeleService/TeleService.apk / 1.0 running in null rsrc of package com.android.phone
,12-19 12:54:35.362  3421  6151 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:54:35.362  3421  6151 W ResourcesManager: getTopLevelResources: /system/priv-app/Fresco_1.0/Fresco_1.0.apk / 1.0 running in null rsrc of package com.samsung.fresco.logging
,12-19 12:54:35.362  3421  6151 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:54:35.362  3421  6151 W ResourcesManager: getTopLevelResources: /system/priv-app/UcsPinpad/UcsPinpad.apk / 1.0 running in null rsrc of package com.samsung.ucs.ucspinpad
,12-19 12:54:35.362  3421  6151 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:54:35.422  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:35.592  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:35.772  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:35.952  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:36.132  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:36.312  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:36.492  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:36.672  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:36.852  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:37.002  3421  6150 D SSRM:n  : SIOP:: AP = 320, PST = 308 (W:6), CP = 262, CUR = 212, LCD = 1
,12-19 12:54:37.032  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:37.212  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:37.392  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:37.572  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:37.752  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:37.872  3421  3853 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-19 12:54:37.872  3421  3853 D BatteryService: level:99, scale:100, status:2, health:2, present:true, voltage: 4313, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 12:54:37.872  3421  3853 D BatteryService: online:4, current avg:106, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:42
12-19 12:54:37.872  3421  3853 D BatteryService: stay LED for charging
12-19 12:54:37.872  3421  3421 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-19 12:54:37.892  3421  3421 I MotionRecognitionService: Plugged
,12-19 12:54:37.892  3421  3421 D MotionRecognitionService:   cableConnection= 1
12-19 12:54:37.892  3421  3421 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,12-19 12:54:37.892  3421  3421 D MotionRecognitionService: skip setTransmitPower. 
,12-19 12:54:37.892  3421  3861 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-19 12:54:37.892  3938  3938 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-19 12:54:37.892  3938  3938 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-19 12:54:37.902  3938  3938 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-19 12:54:37.902  3938  3938 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : 151000 mChargingTime : 151000
12-19 12:54:37.902  3938  3938 D PowerUI.Notification: There is no change about charging status, so return!
,12-19 12:54:37.912  5096  5096 D CommonServiceConfiguration: getStringValueSetting
,12-19 12:54:37.912  5054  5054 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-19 12:54:37.912  5054  5457 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-19 12:54:37.912  5096  5096 D BatteryMonitor: new battery level: 99
,12-19 12:54:37.922  4740  4740 D BatteryController: saveBatteryData : level[99], status[2]
,12-19 12:54:37.922  3421  6151 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.L.run:-1 android.os.Handler.handleCallback:739 
,12-19 12:54:37.932  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:37.942  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,12-19 12:54:37.942  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,12-19 12:54:37.942  3421  3534 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3dc38d7 u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d35c157 9523:com.samsung.android.sm.provider/1000}
,12-19 12:54:38.122  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:38.302  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:38.472  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:38.492  9523 10060 W ResourcesManager: getTopLevelResources: /system/priv-app/Phonesky/Phonesky.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.android.vending
,12-19 12:54:38.492  9523 10060 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:54:38.502  9523 10060 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2015/SecGallery2015.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.sec.android.gallery3d
,12-19 12:54:38.502  9523 10060 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:54:38.512  9523 10060 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.sec.android.app.shealth
,12-19 12:54:38.512  9523 10060 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:54:38.522  9523 10060 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCamera5/SamsungCamera5.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.sec.android.app.camera
,12-19 12:54:38.532  9523 10060 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:54:38.532  9523 10060 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.android.contacts
,12-19 12:54:38.542  9523 10060 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:54:38.552  9523 10060 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.android.contacts
,12-19 12:54:38.552  9523 10060 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.samsung.android.email.provider
,12-19 12:54:38.562  9523 10060 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:54:38.562  9523 10060 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Epic_Common/SecMms_Epic_Common.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.android.mms
,12-19 12:54:38.572  9523 10060 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:54:38.582  9523 10060 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.android.settings
,12-19 12:54:38.582  9523 10060 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:54:38.592  9523 10060 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.android.chrome
,12-19 12:54:38.602  9523 10060 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:54:38.612  9523 10060 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.google.android.apps.docs
,12-19 12:54:38.612  9523 10060 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:54:38.622  9523 10060 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.google.android.gm
,12-19 12:54:38.632  9523 10060 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:54:38.632  9523 10060 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.google.android.talk
,12-19 12:54:38.642  9523 10060 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:54:38.652  9523 10060 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.google.android.music
,12-19 12:54:38.652  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:38.662  9523 10060 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:54:38.672  9523 10060 W ResourcesManager: getTopLevelResources: /system/app/Photos/Photos.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.google.android.apps.photos
,12-19 12:54:38.762  9523 10060 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:54:38.772  9523 10060 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.sec.android.app.sbrowser
,12-19 12:54:38.782  9523 10060 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:54:38.792  9523 10060 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M/SPlanner_M.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.android.calendar
,12-19 12:54:38.802  9523 10060 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:54:38.812  9523 10060 W ResourcesManager: getTopLevelResources: /system/app/Videos/Videos.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.google.android.videos
,12-19 12:54:38.812  9523 10060 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:54:38.832  9523 10060 W ResourcesManager: getTopLevelResources: /system/app/YouTube/YouTube.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.google.android.youtube
,12-19 12:54:38.842  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:38.852  9523 10060 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:54:38.872  9523 10060 W ResourcesManager: getTopLevelResources: /system/priv-app/Excel_SamsungStub/Excel_SamsungStub.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.microsoft.office.excel
,12-19 12:54:38.882  9523 10060 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:54:38.902  9523 10060 W ResourcesManager: getTopLevelResources: /system/priv-app/GearManager/GearManager.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.samsung.android.app.watchmanager
,12-19 12:54:38.912  9523 10060 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:54:38.932  9523 10060 W ResourcesManager: getTopLevelResources: /system/priv-app/SVoice_1.0/SVoice_1.0.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.samsung.voiceserviceplatform
,12-19 12:54:38.942  9523 10060 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:54:38.952  9523 10060 W ResourcesManager: getTopLevelResources: /system/priv-app/PowerPoint_SamsungStub/PowerPoint_SamsungStub.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.microsoft.office.powerpoint
,12-19 12:54:38.952  9523 10060 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:54:38.962  9523 10060 W ResourcesManager: getTopLevelResources: /system/priv-app/SecCalculator_M/SecCalculator_M.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.sec.android.app.popupcalculator
,12-19 12:54:38.972  9523 10060 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:54:38.982  9523 10060 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles/SecMyFiles.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.sec.android.app.myfiles
,12-19 12:54:38.992  9523 10060 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:54:39.012  9523 10060 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.google.android.googlequicksearchbox
,12-19 12:54:39.022  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:39.022  9523 10060 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:54:39.032  9523 10060 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.google.android.googlequicksearchbox
,12-19 12:54:39.042  9523 10060 W ResourcesManager: getTopLevelResources: /system/priv-app/VoiceNote_4.0/VoiceNote_4.0.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.sec.android.app.voicenote
,12-19 12:54:39.042  9523 10060 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:54:39.052  9523 10060 W ResourcesManager: getTopLevelResources: /system/priv-app/Word_SamsungStub/Word_SamsungStub.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.microsoft.office.word
,12-19 12:54:39.062  9523 10060 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:54:39.062  9523 10060 W ResourcesManager: getTopLevelResources: /system/priv-app/player-production-release-3.3.3-newSDK_23/player-production-release-3.3.3-newSDK_23.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package pl.tvn.player
,12-19 12:54:39.072  9523 10060 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:54:39.082  9523 10060 W ResourcesManager: getTopLevelResources: /system/app/ClockPackage_M/ClockPackage_M.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.sec.android.app.clockpackage
,12-19 12:54:39.092  9523 10060 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:54:39.102  9523 10060 W ResourcesManager: getTopLevelResources: /system/app/FBInstagram_stub/FBInstagram_stub.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.instagram.android
,12-19 12:54:39.102  9523 10060 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:54:39.112  9523 10060 W ResourcesManager: getTopLevelResources: /system/app/Facebook_stub/Facebook_stub.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.facebook.katana
,12-19 12:54:39.112  9523 10060 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:54:39.122  9523 10060 W ResourcesManager: getTopLevelResources: /system/app/MSSkype_stub/MSSkype_stub.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.skype.raider
,12-19 12:54:39.132  9523 10060 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:54:39.142  9523 10060 W ResourcesManager: getTopLevelResources: /system/app/Maps/Maps.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.google.android.apps.maps
,12-19 12:54:39.152  9523 10060 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:54:39.182  9523 10060 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.microsoft.skydrive
,12-19 12:54:39.192  9523 10060 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:54:39.192  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:39.212  9523 10060 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.microsoft.office.onenote
,12-19 12:54:39.222  9523 10060 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:54:39.252  9523 10060 W ResourcesManager: getTopLevelResources: /system/app/SecMemo3/SecMemo3.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.samsung.android.app.memo
,12-19 12:54:39.252  9523 10060 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:54:39.302  9523 10060 W ResourcesManager: getTopLevelResources: /data/app/com.sec.android.app.samsungapps-2/base.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.sec.android.app.samsungapps
,12-19 12:54:39.322  9523 10060 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:54:39.342  9523 10060 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.test.thalitest
,12-19 12:54:39.372  9523 10060 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:54:39.372  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:39.552  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:39.732  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:39.922  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:40.092  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:40.282  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:40.462  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:40.632  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:40.822  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:41.002  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:41.172  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:41.362  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:41.532  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:41.722  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:41.902  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:42.072  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:42.252  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:42.442  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:42.622  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:42.802  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:42.982  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:43.152  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:43.342  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:43.522  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:43.702  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:43.882  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:43.882  3421  6185 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-19 12:54:44.052  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:44.242  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:44.422  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:44.592  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:44.772  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:44.952  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:45.142  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:45.312  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:45.502  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:45.672  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:45.862  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:46.032  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:46.212  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:46.402  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:46.582  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:46.762  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:46.932  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:47.052  3421  6150 D SSRM:n  : SIOP:: AP = 310, PST = 305 (W:6), CP = 265, CUR = 106, LCD = 1
,12-19 12:54:47.112  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:47.292  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:47.472  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:47.532  3421  4152 E Watchdog: !@Sync 6 [12-19 12:54:47.551]
,12-19 12:54:47.662  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:47.842  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:47.932  3421  3981 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-19 12:54:47.932  3421  3981 D BatteryService: level:99, scale:100, status:2, health:2, present:true, voltage: 4342, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 12:54:47.932  3421  3981 D BatteryService: online:4, current avg:165, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:206
12-19 12:54:47.932  3421  3981 D BatteryService: stay LED for charging
12-19 12:54:47.932  3421  3421 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-19 12:54:47.942  3421  3421 I MotionRecognitionService: Plugged
,12-19 12:54:47.942  3421  3421 D MotionRecognitionService:   cableConnection= 1
12-19 12:54:47.942  3421  3421 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-19 12:54:47.942  3421  3421 D MotionRecognitionService: skip setTransmitPower. 
,12-19 12:54:47.952  3421  3861 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-19 12:54:47.952  3938  3938 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-19 12:54:47.952  3938  3938 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-19 12:54:47.952  3938  3938 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-19 12:54:47.952  3938  3938 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : 151000 mChargingTime : 100000
,12-19 12:54:47.952  3938  3938 D PowerUI.Notification: showChargingNotification()
,12-19 12:54:47.972  5096  5096 D CommonServiceConfiguration: getStringValueSetting
,12-19 12:54:47.972  3421  4333 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = -1
,12-19 12:54:47.982  5054  5054 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
12-19 12:54:47.982  5054  5457 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-19 12:54:47.982  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
12-19 12:54:47.982  5096  5096 D BatteryMonitor: new battery level: 99
12-19 12:54:47.982  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,12-19 12:54:47.992  4740  4740 D BatteryController: saveBatteryData : level[99], status[2]
,12-19 12:54:48.002  3421  3421 D MARsPolicyManager: NotificationListenerService OngoingNotificationPosted : com.android.systemui
,12-19 12:54:48.012  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:48.022  4153  4164 D CatchNotificationsService: onNotificationPosted
,12-19 12:54:48.032  3938  3938 W ResourcesManager: getTopLevelResources: /system/priv-app/SystemUI/SystemUI.apk / 1.0 running in com.android.systemui rsrc of package com.android.systemui
,12-19 12:54:48.042  3938  3938 D PhoneStatusBar: setAreThereNotifications: N=3 any=true clearable=false
,12-19 12:54:48.042  9410  9422 D BadgeProvider: query, [selection] : null
,12-19 12:54:48.062  4153  4164 E CatchNotificationsService: Invalid notification data
,12-19 12:54:48.192  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:48.382  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:48.552  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:48.742  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:48.872  4400  4465 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
12-19 12:54:48.872  4400  4465 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,12-19 12:54:48.912  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:49.002  4400  4465 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 134ms lastUpdatedAfter : 127506ms
,12-19 12:54:49.092  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:49.272  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:49.452  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:49.632  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:49.812  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:49.992  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:50.172  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:50.362  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:50.532  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:50.722  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:50.892  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:51.072  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:51.262  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:51.432  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:51.622  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:51.792  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:51.982  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:52.152  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:52.342  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:52.522  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:52.692  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:52.872  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:53.052  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:53.242  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:53.412  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:53.602  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:53.782  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:53.962  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:54.132  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:54.312  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:54.502  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:54.672  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:54.862  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:55.042  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:55.212  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:55.392  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:55.582  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:55.762  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:55.942  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:56.112  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:56.292  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:56.472  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:56.662  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:56.842  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:57.012  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:57.112  3421  6150 D SSRM:n  : SIOP:: AP = 300, PST = 305 (W:6), CP = 263, CUR = 165, LCD = 1
,12-19 12:54:57.192  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:57.372  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:57.552  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:57.732  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:57.912  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:57.992  3421  4415 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-19 12:54:57.992  3421  4415 D BatteryService: level:99, scale:100, status:2, health:2, present:true, voltage: 4341, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 12:54:57.992  3421  4415 D BatteryService: online:4, current avg:195, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:211
12-19 12:54:57.992  3421  4415 D BatteryService: stay LED for charging
12-19 12:54:57.992  3421  3421 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-19 12:54:58.002  3421  3421 I MotionRecognitionService: Plugged
,12-19 12:54:58.002  3421  3421 D MotionRecognitionService:   cableConnection= 1
12-19 12:54:58.002  3421  3421 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-19 12:54:58.002  3421  3421 D MotionRecognitionService: skip setTransmitPower. 
,12-19 12:54:58.002  3421  3861 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-19 12:54:58.012  3938  3938 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-19 12:54:58.012  3938  3938 D KeyguardUpdateMonitor: handleBatteryUpdate
12-19 12:54:58.012  3938  3938 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-19 12:54:58.012  3938  3938 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : 100000 mChargingTime : 100000
,12-19 12:54:58.012  3938  3938 D PowerUI.Notification: There is no change about charging status, so return!
,12-19 12:54:58.032  5096  5096 D CommonServiceConfiguration: getStringValueSetting
,12-19 12:54:58.032  5054  5054 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-19 12:54:58.032  5054  5457 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-19 12:54:58.042  5096  5096 D BatteryMonitor: new battery level: 99
,12-19 12:54:58.042  4740  4740 D BatteryController: saveBatteryData : level[99], status[2]
,12-19 12:54:58.062  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,12-19 12:54:58.062  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,12-19 12:54:58.092  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:58.272  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:58.452  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:58.632  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:58.812  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:58.992  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:59.172  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:59.352  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:59.532  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:59.712  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:59.892  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:54:59.982  3421  3815 V AlarmManager: Expired Alarm result :8
,12-19 12:55:00.072  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:00.252  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:00.412  3421  3815 V AlarmManager: Expired Alarm result :4
,12-19 12:55:00.412  3421  3815 V AlarmManager: Send whitelist package alarm :PendingIntent{7c5f3d0: PendingIntentRecord{3f94b70 com.samsung.android.app.aodservice broadcastIntent}}
,12-19 12:55:00.412  3938  3938 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,12-19 12:55:00.412  3938  3938 D KeyguardUpdateMonitor: handleTimeUpdate
,12-19 12:55:00.432  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:00.432  3938  3938 D Clock   : received broadcast android.intent.action.TIME_TICK
,12-19 12:55:00.512  3938  3938 D DateView: received broadcast android.intent.action.TIME_TICK
,12-19 12:55:00.542  8036  8036 D [WeatherWidget(1240)]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,12-19 12:55:00.542  8036  8036 D [WeatherWidget(1240)]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,12-19 12:55:00.552  4740  4740 D AODService.ClockTimer: onReceive : com.samsung.android.app.aodservice.ClockTimer.TICK, mWakeUp = true
12-19 12:55:00.552  4740  4740 V BatteryController: getBatteryLevel[99.0], batteryStatus[2]
,12-19 12:55:00.552  3421  4420 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,12-19 12:55:00.552  3421  4420 I CAE     : setPropertyValue(DevicePhysicalContextMonitorRunner.java:155) - Get status
,12-19 12:55:00.552  3421  4420 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -72, 56, 1, 1,
12-19 12:55:00.552  3421  4420 D SensorHubManager: SendSensorHubData: send data = -72, 56, 1, 1
12-19 12:55:00.552  3168  3168 D Sensorhubs: sendContextData: -72, 56, 1, 1
,12-19 12:55:00.562  3421  4420 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
,12-19 12:55:00.562  3421  4420 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
12-19 12:55:00.562  3421  4420 D SContextService: requestToUpdate() : service = Device Physical Context Monitor
12-19 12:55:00.562  4740  4740 D SContextManager:   .requestToUpdate : listener = com.samsung.android.app.aodservice.AODService$7@63b629b, service=Device Physical Context Monitor
12-19 12:55:00.562  4740  4740 I AlpmModeManager: startAlpmMode : state  = BLANK
,12-19 12:55:00.562  4740  4740 D DefaultClockView: Window showed. Time views updating
,12-19 12:55:00.562  3421  4182 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3421
12-19 12:55:00.562  3421  4182 I libsuspend: !@autosuspend_wakeup_count_disable
12-19 12:55:00.562  3421  4182 D PowerManagerService: mDisplayReady: false
,12-19 12:55:00.562  3421  4182 I libsuspend: !@autosuspend_wakeup_count_disable done
,12-19 12:55:00.562  3421  3574 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-19 12:55:00.562  3421  4182 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
12-19 12:55:00.572  4740  4740 D AODUpdatePositionController: updatePosition: direction[3] updatePosition: X[27] Y[220] NewPositionTimer[57]
,12-19 12:55:00.562  3421  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-19 12:55:00.562  3421  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
,12-19 12:55:00.572  4740  4740 D DefaultClockView: LocalTime Pattern : HH:mm
12-19 12:55:00.562  3421  3574 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-19 12:55:00.572  3421  3586 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
,12-19 12:55:00.572  3421  3570 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
12-19 12:55:00.572  3421  3570 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
,12-19 12:55:00.572  3010  3010 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fa2c03c00
,12-19 12:55:00.572  3010  3010 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
12-19 12:55:00.572  4740  4740 D TimeViewHolder: onTimeUpdate: timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] isSplitHour:false isSingleView:false isAMPMonLeft:null time01: 12:55 time02: null ampm: null
,12-19 12:55:00.582  3421  3574 D DisplayPowerController: animateScreenStateChange[0]: target=3
,12-19 12:55:00.582  3421  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-19 12:55:00.582  3421  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-19 12:55:00.582  3421  3574 I libsuspend: !@autosuspend_wakeup_count_enable
,12-19 12:55:00.582  3421  3574 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-19 12:55:00.582  3421  3574 I libsuspend: !@autosuspend_wakeup_count_enable done
12-19 12:55:00.582  3421  3574 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-19 12:55:00.582  3421  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-19 12:55:00.582  3421  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
,12-19 12:55:00.582  3421  3574 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-19 12:55:00.582  3421  3574 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
12-19 12:55:00.582  3421  3574 D PowerManagerService: mDisplayReady: true
,12-19 12:55:00.582  3421  3574 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,12-19 12:55:00.592  5854  5854 E CocktailBarPositionManager: Window direction: 0
,12-19 12:55:00.592  5854  5854 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,12-19 12:55:00.592  4740  4740 D RoamingTimeViewHolder: isDualClockSetting :: true isHomeTimeZoneExist :: false isEasyUxON :: false Utils.isRoaming(mContext) :: false
,12-19 12:55:00.592  4740  4740 D RoamingTimeViewHolder: getHomeCalendar : No homecity_timezone, set as default :  (libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167])
,12-19 12:55:00.592  4740  4740 D RoamingTimeViewHolder: onTimeUpdate: isVisible:false timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] text:pon., 19 gru 12:55
12-19 12:55:00.592  4740  4740 I AODService.ClockTimer: startAlarm : TICK
,12-19 12:55:00.592  3421  4333 V AlarmManager: Add whitelist package alarm :PendingIntent{f418b73: PendingIntentRecord{3f94b70 com.samsung.android.app.aodservice broadcastIntent}}
,12-19 12:55:00.592  4740  4740 I AlpmModeManager: handleUnblankDisplay: state  = BLANK
12-19 12:55:00.592  4740  4740 V AlpmModeManager: updateAlpmMode: setDoze [DISPLAY_STATE_DOZE_SUSPEND]
,12-19 12:55:00.602  3421  3474 I PowerManagerService: [api] setDozeOverrideFromAod AlpmHlpmSysfs = -1, screenState = 4, Brightness = 0, wakefulness = false
,12-19 12:55:00.602  3421  3474 D PowerManagerService: setDozeModeBySysfs:  value is -1 , we ignore it. 
,12-19 12:55:00.602  4740  4740 D DefaultClockView: RootView invalidate()
,12-19 12:55:00.602  3421  3984 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3421
,12-19 12:55:00.612  3168  3213 D Sensorhubs: readContextData: 1, 1, 56, 1, 1, 1, 1
,12-19 12:55:00.612  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
12-19 12:55:00.612  3421  3818 D SensorHubManager: onGetSensorHubDataLocked: library(7) = 1, 1, 56, 1, 1, 1, 1
,12-19 12:55:00.612  3421  3817 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 14, 11, 55, 0,
12-19 12:55:00.612  3421  3817 D SensorHubManager: SendSensorHubData: send data = -63, 14, 11, 55, 0
12-19 12:55:00.612  3168  3214 D Sensorhubs: sendContextData: -63, 14, 11, 55, 0
,12-19 12:55:00.612  3421  3817 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :7], AP_SLEEP
,12-19 12:55:00.612  3421  3817 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 7
12-19 12:55:00.612  3421  3817 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 56, 1, 1, 1, 1,
,12-19 12:55:00.612  3421  3817 D CAE     : display(ContextProvider.java:375) - ================= DEVICE_PHYSICAL_CONTEXT_MONITOR =================
12-19 12:55:00.612  3421  3817 I CAE     : display(ContextProvider.java:391) - AODReason=[1], AODStatus=[1], DataType=[1]
,12-19 12:55:00.622  3421  3820 D SContextService: updateSContext() : event = Device Physical Context Monitor
,12-19 12:55:00.632  4740  4740 I AODService: onSContextChanged: AODScreenShown state is already true
,12-19 12:55:00.762  3421  3421 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3421 (0x0)
,12-19 12:55:00.762  3421  3421 I libsuspend: !@autosuspend_wakeup_count_disable
12-19 12:55:00.762  3421  3421 D PowerManagerService: mDisplayReady: false
12-19 12:55:00.762  3421  3421 I libsuspend: !@autosuspend_wakeup_count_disable done
,12-19 12:55:00.762  3421  3574 D DisplayPowerController: animateScreenStateChange[0]: target=4
12-19 12:55:00.762  3010  3010 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7fa2c03c00
,12-19 12:55:00.762  3421  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
,12-19 12:55:00.762  3010  3010 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
12-19 12:55:00.762  3421  3421 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
,12-19 12:55:00.762  3421  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-19 12:55:00.762  3421  3574 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-19 12:55:00.762  3421  3586 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
,12-19 12:55:00.762  3421  3570 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
12-19 12:55:00.762  3421  3570 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
,12-19 12:55:00.792  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:00.802  3421  3574 D DisplayPowerController: animateScreenStateChange[0]: target=4
12-19 12:55:00.802  3421  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-19 12:55:00.802  3421  3574 I libsuspend: !@autosuspend_wakeup_count_enable
12-19 12:55:00.802  3421  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-19 12:55:00.802  3421  3574 I libsuspend: !@autosuspend_wakeup_count_enable done
12-19 12:55:00.802  3421  3574 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-19 12:55:00.802  3421  3574 D DisplayPowerController: animateScreenStateChange[0]: target=4
12-19 12:55:00.802  3421  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-19 12:55:00.802  3421  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-19 12:55:00.802  3421  3574 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-19 12:55:00.802  3421  3574 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
12-19 12:55:00.802  3421  3574 D PowerManagerService: mDisplayReady: true
12-19 12:55:00.802  3421  3574 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,12-19 12:55:00.812  5854  5854 E CocktailBarPositionManager: Window direction: 0
12-19 12:55:00.812  5854  5854 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,12-19 12:55:00.972  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:01.152  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:01.332  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:01.512  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:01.692  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:01.872  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:02.052  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:02.232  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:02.412  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:02.602  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:02.782  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:02.962  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:03.132  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:03.312  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:03.502  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:03.682  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:03.852  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:03.892  3421  6185 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-19 12:55:04.042  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:04.212  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:04.392  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:04.572  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:04.762  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:04.942  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:05.112  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:05.292  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:05.472  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:05.652  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:05.832  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:06.012  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:06.192  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:06.372  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:06.552  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:06.732  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:06.912  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:07.092  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:07.162  3421  6150 D SSRM:n  : SIOP:: AP = 300, PST = 305 (W:6), CP = 262, CUR = 195, LCD = 1
,12-19 12:55:07.272  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:07.302  3421  3431 I art     : Background sticky concurrent mark sweep GC freed 157121(11MB) AllocSpace objects, 113(2MB) LOS objects, 23% free, 46MB/61MB, paused 2.521ms total 157.578ms
,12-19 12:55:07.452  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:07.632  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:07.812  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:07.992  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:08.052  3421  4182 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-19 12:55:08.052  3421  4182 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4342, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
,12-19 12:55:08.052  3421  4182 D BatteryService: online:4, current avg:207, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:222
12-19 12:55:08.052  3421  4182 D BatteryService: stay LED for charging
,12-19 12:55:08.062  3421  3538 D BluetoothAdapter: STATE_ON
,12-19 12:55:08.072  3421  4391 V AlarmManager:  remove PendingIntent] PendingIntent{5579a30: PendingIntentRecord{4f1e9d1 com.android.bluetooth broadcastIntent}}
,12-19 12:55:08.082  3421  3981 V AlarmManager:  remove PendingIntent] PendingIntent{86776a9: PendingIntentRecord{4f1e9d1 com.android.bluetooth broadcastIntent}}
,12-19 12:55:08.092  3421  3421 D BatteryService: !@[BatteryInfo] readFromFile /sys/class/power_supply/battery/fg_asoc: 99
,12-19 12:55:08.102  3421  3421 D BatteryService: !@[BatteryInfo] readFromFile /efs/FactoryApp/asoc: 99
,12-19 12:55:08.102  3421  3421 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-19 12:55:08.102  3421  3574 D PowerManagerService: [PSM] lowPowerModeEnabled: false (mLowPowerModeSetting: false, mIsPowered: true, mAutoLowPowerModeConfigured: false, mBatteryLevel: 100, mLowBatteryTriggerLevel: 0)
,12-19 12:55:08.102  3421  3421 I MotionRecognitionService: Plugged
,12-19 12:55:08.102  3421  3421 D MotionRecognitionService:   cableConnection= 1
12-19 12:55:08.102  3421  3421 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,12-19 12:55:08.102  3421  3421 D MotionRecognitionService: skip setTransmitPower. 
,12-19 12:55:08.112  3421  3861 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-19 12:55:08.112  3938  3938 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-19 12:55:08.112  3938  3938 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-19 12:55:08.122  5096  5096 D CommonServiceConfiguration: getStringValueSetting
,12-19 12:55:08.122  5054  5054 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-19 12:55:08.122  5054  5457 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-19 12:55:08.132  3938  3938 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : 100000 mChargingTime : -1
,12-19 12:55:08.132  3938  3938 D PowerUI.Notification: showChargingNotification()
,12-19 12:55:08.132  5096  5096 D BatteryMonitor: new battery level: 100
12-19 12:55:08.132  3421  3421 D SSRM:aZ : Battery is fully charged.
,12-19 12:55:08.132  3421  6150 D SSRM:aZ : MSG_TYPE_DB_CLEAN_ALL::
,12-19 12:55:08.132  3421  4391 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = -1
,12-19 12:55:08.142  3938  3938 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-19 12:55:08.142  4906  4906 E MtpServerJNI: server is null in send_object_removed
,12-19 12:55:08.142  4740  4740 D BatteryController: saveBatteryData : level[100], status[2]
12-19 12:55:08.142  3421  3421 W ResourcesManager: getTopLevelResources: /system/priv-app/SystemUI/SystemUI.apk / 1.0 running in null rsrc of package com.android.systemui
12-19 12:55:08.142  4740  4740 D AODService: Received intent, service updating android.intent.action.BATTERY_CHANGED
12-19 12:55:08.152  3421  3474 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3421
12-19 12:55:08.152  3421  3474 I libsuspend: !@autosuspend_wakeup_count_disable
12-19 12:55:08.152  3421  3474 D PowerManagerService: mDisplayReady: false
12-19 12:55:08.152  3421  3474 I libsuspend: !@autosuspend_wakeup_count_disable done
12-19 12:55:08.152  3421  3474 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
12-19 12:55:08.152  3421  3574 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-19 12:55:08.152  3421  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-19 12:55:08.152  3421  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-19 12:55:08.152  3421  3574 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-19 12:55:08.152  3421  3586 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
,12-19 12:55:08.152  3421  3570 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
,12-19 12:55:08.152  3421  3570 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
,12-19 12:55:08.152  3421  3421 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:55:08.152  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
12-19 12:55:08.152  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,12-19 12:55:08.162  3421  3421 D MARsPolicyManager: NotificationListenerService OngoingNotificationPosted : com.android.systemui
12-19 12:55:08.162  3010  3010 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fa2c03c00
,12-19 12:55:08.162  3010  3010 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
,12-19 12:55:08.172  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:08.172  3421  3574 D DisplayPowerController: animateScreenStateChange[0]: target=3
,12-19 12:55:08.172  3421  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-19 12:55:08.172  3421  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-19 12:55:08.172  3421  3574 I libsuspend: !@autosuspend_wakeup_count_enable
12-19 12:55:08.172  3421  3574 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-19 12:55:08.172  3421  3574 I libsuspend: !@autosuspend_wakeup_count_enable done
,12-19 12:55:08.172  3421  3574 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-19 12:55:08.172  3421  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-19 12:55:08.172  3421  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
,12-19 12:55:08.172  3421  3574 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-19 12:55:08.172  3421  3574 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
12-19 12:55:08.172  3421  3574 D PowerManagerService: mDisplayReady: true
12-19 12:55:08.172  3421  3574 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,12-19 12:55:08.172  5854  5854 E CocktailBarPositionManager: Window direction: 0
12-19 12:55:08.172  5854  5854 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,12-19 12:55:08.202  4153  4164 D CatchNotificationsService: onNotificationPosted
,12-19 12:55:08.202  3421  4333 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3421
,12-19 12:55:08.202  4740  4740 D BatteryMeterView: onDraw batteryColor : -986896
,12-19 12:55:08.222  9410  9420 D BadgeProvider: query, [selection] : null
,12-19 12:55:08.222  4153  4164 E CatchNotificationsService: Invalid notification data
,12-19 12:55:08.252  3938  3938 W ResourcesManager: getTopLevelResources: /system/priv-app/SystemUI/SystemUI.apk / 1.0 running in com.android.systemui rsrc of package com.android.systemui
,12-19 12:55:08.262  3938  3938 D KnoxNotification: ----- inflateViews : modified publicViewLocal -----
,12-19 12:55:08.262  3938  3938 W ResourcesManager: getTopLevelResources: /system/priv-app/SystemUI/SystemUI.apk / 1.0 running in com.android.systemui rsrc of package com.android.systemui
,12-19 12:55:08.282  3938  3938 D KnoxNotification: ----- inflateViews : modified KnoxViewLocal -----
,12-19 12:55:08.282  3938  3938 W ResourcesManager: getTopLevelResources: /system/priv-app/SystemUI/SystemUI.apk / 1.0 running in com.android.systemui rsrc of package com.android.systemui
,12-19 12:55:08.292  3938  3938 D PhoneStatusBar: setAreThereNotifications: N=3 any=true clearable=false
,12-19 12:55:08.352  3421  3421 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3421 (0x0)
12-19 12:55:08.352  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
12-19 12:55:08.352  3421  3421 D PowerManagerService: mDisplayReady: false
12-19 12:55:08.352  3421  3421 I libsuspend: !@autosuspend_wakeup_count_disable
12-19 12:55:08.352  3421  3574 D DisplayPowerController: animateScreenStateChange[0]: target=4
12-19 12:55:08.352  3421  3421 I libsuspend: !@autosuspend_wakeup_count_disable done
12-19 12:55:08.352  3421  3421 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
12-19 12:55:08.352  3421  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-19 12:55:08.352  3421  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-19 12:55:08.352  3421  3574 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-19 12:55:08.352  3421  3586 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
,12-19 12:55:08.352  3010  3010 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7fa2c03c00
12-19 12:55:08.352  3421  3570 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
,12-19 12:55:08.352  3010  3010 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
,12-19 12:55:08.352  3421  3570 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
,12-19 12:55:08.392  3421  3574 D DisplayPowerController: animateScreenStateChange[0]: target=4
12-19 12:55:08.392  3421  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-19 12:55:08.392  3421  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-19 12:55:08.392  3421  3574 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-19 12:55:08.392  3421  3574 I libsuspend: !@autosuspend_wakeup_count_enable
12-19 12:55:08.392  3421  3574 D DisplayPowerController: animateScreenStateChange[0]: target=4
12-19 12:55:08.392  3421  3574 I libsuspend: !@autosuspend_wakeup_count_enable done
12-19 12:55:08.392  3421  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-19 12:55:08.392  3421  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-19 12:55:08.392  3421  3574 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-19 12:55:08.392  3421  3574 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
,12-19 12:55:08.392  3421  3574 D PowerManagerService: mDisplayReady: true
12-19 12:55:08.392  3421  3574 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,12-19 12:55:08.402  5854  5854 E CocktailBarPositionManager: Window direction: 0
12-19 12:55:08.402  5854  5854 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,12-19 12:55:08.532  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:08.712  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:08.892  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:09.072  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:09.252  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:09.432  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:09.612  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:09.792  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:09.972  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:10.152  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:10.332  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:10.512  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:10.692  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:10.872  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:11.052  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:11.232  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:11.422  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:11.592  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:11.782  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:11.952  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:12.132  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:12.312  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:12.492  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:12.682  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:12.862  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:13.032  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:13.212  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:13.392  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:13.582  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:13.762  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:13.932  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:14.112  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:14.292  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:14.472  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:14.652  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:14.832  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:15.012  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:15.192  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:15.372  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:15.552  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:15.732  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:15.912  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:16.092  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:16.272  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:16.452  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:16.632  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:16.812  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:16.992  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:17.172  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:17.212  3421  6150 D SSRM:n  : SIOP:: AP = 300, PST = 305 (W:10), CP = 260, CUR = 207, LCD = 1
,12-19 12:55:17.232  3421  6150 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,12-19 12:55:17.352  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:17.532  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:17.542  3421  4152 E Watchdog: !@Sync 7 [12-19 12:55:17.553]
,12-19 12:55:17.712  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:17.892  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:18.072  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:18.112  3421  3472 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-19 12:55:18.112  3421  3472 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4342, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 12:55:18.112  3421  3472 D BatteryService: online:4, current avg:207, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:174
12-19 12:55:18.112  3421  3472 D BatteryService: stay LED for charging
12-19 12:55:18.112  3421  3421 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-19 12:55:18.122  3421  3421 I MotionRecognitionService: Plugged
,12-19 12:55:18.122  3421  3421 D MotionRecognitionService:   cableConnection= 1
12-19 12:55:18.122  3421  3421 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-19 12:55:18.122  3421  3421 D MotionRecognitionService: skip setTransmitPower. 
,12-19 12:55:18.132  3421  3861 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-19 12:55:18.132  3938  3938 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-19 12:55:18.132  3938  3938 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-19 12:55:18.142  3938  3938 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-19 12:55:18.142  3938  3938 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,12-19 12:55:18.142  3938  3938 D PowerUI.Notification: There is no change about charging status, so return!
,12-19 12:55:18.162  5096  5096 D CommonServiceConfiguration: getStringValueSetting
,12-19 12:55:18.162  5054  5054 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-19 12:55:18.162  5054  5457 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-19 12:55:18.172  4740  4740 D BatteryController: saveBatteryData : level[100], status[2]
,12-19 12:55:18.172  5096  5096 D BatteryMonitor: new battery level: 100
,12-19 12:55:18.202  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,12-19 12:55:18.202  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,12-19 12:55:18.252  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:18.432  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:18.612  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:18.792  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:18.972  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:19.152  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:19.332  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:19.512  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:19.692  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:19.872  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:20.052  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:20.232  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:20.412  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:20.592  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:20.772  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:20.952  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:21.132  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:21.312  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:21.492  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:21.672  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:21.852  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:22.032  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:22.212  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:22.392  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:22.572  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:22.752  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:22.932  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:23.112  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:23.292  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:23.472  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:23.652  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:23.832  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:23.882  3421  6185 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-19 12:55:24.012  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:24.192  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:24.372  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:24.552  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:24.732  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:24.912  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:25.092  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:25.272  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:25.452  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:25.632  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:25.812  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:25.992  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:26.172  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:26.352  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:26.532  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:26.712  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:26.892  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:27.072  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:27.252  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:27.272  3421  6150 D SSRM:n  : SIOP:: AP = 300, PST = 303 (W:10), CP = 260, CUR = 207, LCD = 1
,12-19 12:55:27.432  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:27.612  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:27.792  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:27.972  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:28.152  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:28.172  3421  3981 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,12-19 12:55:28.172  3421  3981 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4345, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 12:55:28.172  3421  3981 D BatteryService: online:4, current avg:213, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:212
12-19 12:55:28.172  3421  3981 D BatteryService: stay LED for charging
12-19 12:55:28.172  3421  3421 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-19 12:55:28.172  3421  3421 I MotionRecognitionService: Plugged
12-19 12:55:28.172  3421  3421 D MotionRecognitionService:   cableConnection= 1
12-19 12:55:28.172  3421  3421 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-19 12:55:28.172  3421  3421 D MotionRecognitionService: skip setTransmitPower. 
,12-19 12:55:28.182  3421  3861 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-19 12:55:28.182  3938  3938 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
12-19 12:55:28.182  3938  3938 D KeyguardUpdateMonitor: handleBatteryUpdate
12-19 12:55:28.182  3938  3938 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-19 12:55:28.192  3938  3938 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,12-19 12:55:28.192  3938  3938 D PowerUI.Notification: There is no change about charging status, so return!
,12-19 12:55:28.202  5096  5096 D CommonServiceConfiguration: getStringValueSetting
,12-19 12:55:28.202  5054  5054 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-19 12:55:28.202  5054  5457 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-19 12:55:28.212  4740  4740 D BatteryController: saveBatteryData : level[100], status[2]
,12-19 12:55:28.212  5096  5096 D BatteryMonitor: new battery level: 100
,12-19 12:55:28.232  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,12-19 12:55:28.232  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,12-19 12:55:28.332  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:28.512  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:28.692  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:28.872  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:29.052  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:29.232  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:29.412  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:29.592  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:29.772  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:29.952  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:30.132  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:30.312  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:30.492  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:30.672  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:30.852  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:31.032  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:31.212  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:31.392  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:31.572  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:31.752  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:31.932  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:32.112  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:32.292  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:32.472  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:32.652  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:32.832  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:33.012  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:33.182  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:33.372  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:33.552  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:33.722  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:33.912  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:34.082  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:34.262  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:34.442  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:34.632  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:34.812  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:34.992  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:35.162  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:35.342  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:35.532  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:35.712  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:35.892  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:36.072  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:36.252  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:36.432  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:36.612  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:36.792  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:36.972  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:37.142  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:37.322  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:37.332  3421  6150 D SSRM:n  : SIOP:: AP = 300, PST = 301 (W:10), CP = 259, CUR = 213, LCD = 1
,12-19 12:55:37.512  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:37.682  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:37.862  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:38.052  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:38.222  3421  4421 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,12-19 12:55:38.222  3421  4421 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4343, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 12:55:38.222  3421  4421 D BatteryService: online:4, current avg:214, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:218
,12-19 12:55:38.222  3421  3421 D BatteryService: Sending ACTION_BATTERY_CHANGED.
12-19 12:55:38.222  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
12-19 12:55:38.222  3421  4421 D BatteryService: stay LED for charging
,12-19 12:55:38.232  3421  3421 I MotionRecognitionService: Plugged
,12-19 12:55:38.232  3421  3421 D MotionRecognitionService:   cableConnection= 1
12-19 12:55:38.232  3421  3421 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-19 12:55:38.232  3421  3421 D MotionRecognitionService: skip setTransmitPower. 
,12-19 12:55:38.232  3421  3861 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-19 12:55:38.242  3938  3938 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-19 12:55:38.242  3938  3938 D KeyguardUpdateMonitor: handleBatteryUpdate
12-19 12:55:38.242  3938  3938 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-19 12:55:38.242  3938  3938 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
12-19 12:55:38.242  3938  3938 D PowerUI.Notification: There is no change about charging status, so return!
,12-19 12:55:38.262  5096  5096 D CommonServiceConfiguration: getStringValueSetting
,12-19 12:55:38.262  5054  5054 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-19 12:55:38.262  5054  5457 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-19 12:55:38.272  5096  5096 D BatteryMonitor: new battery level: 100
,12-19 12:55:38.272  4740  4740 D BatteryController: saveBatteryData : level[100], status[2]
,12-19 12:55:38.292  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,12-19 12:55:38.292  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,12-19 12:55:38.402  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:38.582  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:38.762  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:38.952  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:39.122  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:39.312  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:39.492  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:39.662  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:39.852  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:40.022  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:40.212  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:40.382  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:40.572  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:40.752  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:40.932  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:41.102  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:41.292  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:41.462  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:41.642  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:41.822  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:42.012  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:42.182  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:42.372  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:42.552  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:42.722  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:42.902  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:43.082  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:43.262  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:43.452  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:43.622  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:43.812  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:43.892  3421  6185 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-19 12:55:43.982  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:44.082  3421  3815 V AlarmManager: Expired Alarm result :4
,12-19 12:55:44.162  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:44.342  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:44.532  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:44.702  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:44.892  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:45.062  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:45.252  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:45.432  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:45.612  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:45.792  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:45.972  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:46.142  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:46.322  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:46.512  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:46.682  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:46.872  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:47.052  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:47.222  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:47.392  3421  6150 D SSRM:n  : SIOP:: AP = 300, PST = 300 (W:10), CP = 258, CUR = 214, LCD = 1
,12-19 12:55:47.402  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:47.552  3421  4152 E Watchdog: !@Sync 8 [12-19 12:55:47.555]
,12-19 12:55:47.592  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:47.772  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:47.942  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:48.132  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:48.282  3421  3853 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-19 12:55:48.282  3421  3853 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4347, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 12:55:48.282  3421  3853 D BatteryService: online:4, current avg:215, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:187
12-19 12:55:48.282  3421  3853 D BatteryService: stay LED for charging
12-19 12:55:48.282  3421  3421 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-19 12:55:48.292  3421  3421 I MotionRecognitionService: Plugged
,12-19 12:55:48.292  3421  3421 D MotionRecognitionService:   cableConnection= 1
12-19 12:55:48.292  3421  3421 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-19 12:55:48.292  3421  3421 D MotionRecognitionService: skip setTransmitPower. 
,12-19 12:55:48.292  3421  3861 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-19 12:55:48.302  3938  3938 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
12-19 12:55:48.302  3938  3938 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-19 12:55:48.302  3938  3938 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-19 12:55:48.302  3938  3938 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,12-19 12:55:48.312  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
12-19 12:55:48.302  3938  3938 D PowerUI.Notification: There is no change about charging status, so return!
,12-19 12:55:48.322  5096  5096 D CommonServiceConfiguration: getStringValueSetting
,12-19 12:55:48.322  5054  5054 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-19 12:55:48.332  5054  5457 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-19 12:55:48.332  5096  5096 D BatteryMonitor: new battery level: 100
12-19 12:55:48.342  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
12-19 12:55:48.342  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
12-19 12:55:48.342  4740  4740 D BatteryController: saveBatteryData : level[100], status[2]
,12-19 12:55:48.482  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:48.672  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:48.852  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:49.022  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:49.062  4400  4465 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
12-19 12:55:49.062  4400  4465 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,12-19 12:55:49.202  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:49.382  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:49.572  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:49.742  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:49.922  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:50.102  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:50.282  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:50.462  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:50.642  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:50.822  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:51.002  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:51.182  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:51.362  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:51.542  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:51.722  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:51.902  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:52.082  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:52.262  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:52.442  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:52.622  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:52.802  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:52.982  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:53.162  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:53.342  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:53.522  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:53.702  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:53.882  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:54.072  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:54.242  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:54.422  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:54.612  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:54.792  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:54.972  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:55.142  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:55.332  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:55.502  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:55.682  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:55.872  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:56.052  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:56.222  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:56.412  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:56.582  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:56.762  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:56.952  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:57.132  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:57.312  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:57.452  3421  6150 D SSRM:n  : SIOP:: AP = 300, PST = 300 (W:14), CP = 258, CUR = 215, LCD = 1
,12-19 12:55:57.482  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:57.662  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:57.852  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:58.022  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:58.202  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:58.342  3421  4417 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,12-19 12:55:58.342  3421  4417 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4346, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 12:55:58.342  3421  4417 D BatteryService: online:4, current avg:218, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:276
12-19 12:55:58.342  3421  4417 D BatteryService: stay LED for charging
12-19 12:55:58.342  3421  3421 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-19 12:55:58.352  3421  3421 I MotionRecognitionService: Plugged
,12-19 12:55:58.352  3421  3421 D MotionRecognitionService:   cableConnection= 1
12-19 12:55:58.352  3421  3421 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-19 12:55:58.352  3421  3421 D MotionRecognitionService: skip setTransmitPower. 
,12-19 12:55:58.362  3421  3861 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-19 12:55:58.362  3938  3938 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
12-19 12:55:58.362  3938  3938 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-19 12:55:58.362  3938  3938 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-19 12:55:58.362  3938  3938 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,12-19 12:55:58.362  3938  3938 D PowerUI.Notification: There is no change about charging status, so return!
,12-19 12:55:58.382  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:58.382  5096  5096 D CommonServiceConfiguration: getStringValueSetting
,12-19 12:55:58.392  5054  5054 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-19 12:55:58.392  5054  5457 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-19 12:55:58.392  5096  5096 D BatteryMonitor: new battery level: 100
,12-19 12:55:58.402  4740  4740 D BatteryController: saveBatteryData : level[100], status[2]
,12-19 12:55:58.412  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,12-19 12:55:58.412  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,12-19 12:55:58.572  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:58.742  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:58.922  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:59.102  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:59.282  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:59.462  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:59.642  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:59.822  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:55:59.982  3421  3815 V AlarmManager: Expired Alarm result :8
,12-19 12:56:00.002  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:00.182  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:00.362  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:00.542  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:00.602  3421  3815 V AlarmManager: Expired Alarm result :4
,12-19 12:56:00.602  3421  3815 V AlarmManager: Send whitelist package alarm :PendingIntent{f418b73: PendingIntentRecord{3f94b70 com.samsung.android.app.aodservice broadcastIntent}}
,12-19 12:56:00.602  3938  3938 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
12-19 12:56:00.602  3938  3938 D KeyguardUpdateMonitor: handleTimeUpdate
,12-19 12:56:00.622  3938  3938 D Clock   : received broadcast android.intent.action.TIME_TICK
,12-19 12:56:00.692  3938  3938 D DateView: received broadcast android.intent.action.TIME_TICK
,12-19 12:56:00.722  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:00.722  8036  8036 D [WeatherWidget(1240)]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,12-19 12:56:00.722  8036  8036 D [WeatherWidget(1240)]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,12-19 12:56:00.732  4740  4740 D AODService.ClockTimer: onReceive : com.samsung.android.app.aodservice.ClockTimer.TICK, mWakeUp = true
,12-19 12:56:00.732  4740  4740 V BatteryController: getBatteryLevel[100.0], batteryStatus[2]
,12-19 12:56:00.732  3421  4415 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
12-19 12:56:00.732  3421  4415 I CAE     : setPropertyValue(DevicePhysicalContextMonitorRunner.java:155) - Get status
12-19 12:56:00.732  3421  4415 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -72, 56, 1, 1,
12-19 12:56:00.732  3421  4415 D SensorHubManager: SendSensorHubData: send data = -72, 56, 1, 1
,12-19 12:56:00.732  3168  3168 D Sensorhubs: sendContextData: -72, 56, 1, 1
,12-19 12:56:00.742  3421  4415 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
,12-19 12:56:00.742  3421  4415 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
12-19 12:56:00.742  3421  4415 D SContextService: requestToUpdate() : service = Device Physical Context Monitor
12-19 12:56:00.742  4740  4740 D SContextManager:   .requestToUpdate : listener = com.samsung.android.app.aodservice.AODService$7@63b629b, service=Device Physical Context Monitor
12-19 12:56:00.742  4740  4740 I AlpmModeManager: startAlpmMode : state  = BLANK
12-19 12:56:00.742  4740  4740 D DefaultClockView: Window showed. Time views updating
12-19 12:56:00.742  3421  3984 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3421
12-19 12:56:00.742  3421  3984 I libsuspend: !@autosuspend_wakeup_count_disable
,12-19 12:56:00.742  3421  3984 D PowerManagerService: mDisplayReady: false
12-19 12:56:00.742  3421  3984 I libsuspend: !@autosuspend_wakeup_count_disable done
12-19 12:56:00.742  3421  3574 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-19 12:56:00.742  4740  4740 D AODUpdatePositionController: updatePosition: direction[4] updatePosition: X[28] Y[220] NewPositionTimer[56]
12-19 12:56:00.742  3421  3984 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
12-19 12:56:00.742  4740  4740 D DefaultClockView: LocalTime Pattern : HH:mm
12-19 12:56:00.742  3421  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
,12-19 12:56:00.742  4740  4740 D TimeViewHolder: onTimeUpdate: timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] isSplitHour:false isSingleView:false isAMPMonLeft:null time01: 12:56 time02: null ampm: null
12-19 12:56:00.742  3421  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-19 12:56:00.742  3421  3574 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-19 12:56:00.752  3010  3010 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fa2c03c00
12-19 12:56:00.742  3421  3586 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
12-19 12:56:00.752  3010  3010 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
,12-19 12:56:00.742  3421  3570 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
12-19 12:56:00.742  3421  3570 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
,12-19 12:56:00.762  3421  3574 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-19 12:56:00.762  3421  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-19 12:56:00.762  3421  3574 I libsuspend: !@autosuspend_wakeup_count_enable
,12-19 12:56:00.762  3421  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-19 12:56:00.762  3421  3574 I libsuspend: !@autosuspend_wakeup_count_enable done
12-19 12:56:00.762  3421  3574 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-19 12:56:00.762  3421  3574 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-19 12:56:00.762  3421  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-19 12:56:00.762  3421  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-19 12:56:00.762  3421  3574 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-19 12:56:00.762  3421  3574 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
12-19 12:56:00.762  3421  3574 D PowerManagerService: mDisplayReady: true
12-19 12:56:00.762  3421  3574 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,12-19 12:56:00.762  5854  5854 E CocktailBarPositionManager: Window direction: 0
,12-19 12:56:00.762  5854  5854 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,12-19 12:56:00.772  4740  4740 D RoamingTimeViewHolder: isDualClockSetting :: true isHomeTimeZoneExist :: false isEasyUxON :: false Utils.isRoaming(mContext) :: false
12-19 12:56:00.772  4740  4740 D RoamingTimeViewHolder: getHomeCalendar : No homecity_timezone, set as default :  (libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167])
12-19 12:56:00.772  4740  4740 D RoamingTimeViewHolder: onTimeUpdate: isVisible:false timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] text:pon., 19 gru 12:56
,12-19 12:56:00.772  4740  4740 I AODService.ClockTimer: startAlarm : TICK
12-19 12:56:00.772  3421  3984 V AlarmManager: Add whitelist package alarm :PendingIntent{afa653a: PendingIntentRecord{3f94b70 com.samsung.android.app.aodservice broadcastIntent}}
,12-19 12:56:00.772  4740  4740 I AlpmModeManager: handleUnblankDisplay: state  = BLANK
12-19 12:56:00.772  4740  4740 V AlpmModeManager: updateAlpmMode: setDoze [DISPLAY_STATE_DOZE_SUSPEND]
,12-19 12:56:00.772  3421  3474 I PowerManagerService: [api] setDozeOverrideFromAod AlpmHlpmSysfs = -1, screenState = 4, Brightness = 0, wakefulness = false
12-19 12:56:00.772  3421  3474 D PowerManagerService: setDozeModeBySysfs:  value is -1 , we ignore it. 
,12-19 12:56:00.782  3168  3213 D Sensorhubs: readContextData: 1, 1, 56, 1, 1, 1, 1
12-19 12:56:00.782  3421  3818 D SensorHubManager: onGetSensorHubDataLocked: library(7) = 1, 1, 56, 1, 1, 1, 1
12-19 12:56:00.782  3421  3817 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 14, 11, 56, 0,
12-19 12:56:00.782  3421  3817 D SensorHubManager: SendSensorHubData: send data = -63, 14, 11, 56, 0
,12-19 12:56:00.782  3168  3214 D Sensorhubs: sendContextData: -63, 14, 11, 56, 0
,12-19 12:56:00.782  4740  4740 D DefaultClockView: RootView invalidate()
12-19 12:56:00.782  3421  4989 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3421
,12-19 12:56:00.782  3421  3817 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :7], AP_SLEEP
,12-19 12:56:00.792  3421  3817 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 7
12-19 12:56:00.792  3421  3817 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 56, 1, 1, 1, 1,
,12-19 12:56:00.792  3421  3817 D CAE     : display(ContextProvider.java:375) - ================= DEVICE_PHYSICAL_CONTEXT_MONITOR =================
12-19 12:56:00.792  3421  3817 I CAE     : display(ContextProvider.java:391) - AODReason=[1], AODStatus=[1], DataType=[1]
,12-19 12:56:00.792  3421  3820 D SContextService: updateSContext() : event = Device Physical Context Monitor
,12-19 12:56:00.812  4740  4740 I AODService: onSContextChanged: AODScreenShown state is already true
,12-19 12:56:00.902  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:00.942  3421  3421 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3421 (0x0)
,12-19 12:56:00.942  3421  3421 I libsuspend: !@autosuspend_wakeup_count_disable
12-19 12:56:00.942  3421  3421 D PowerManagerService: mDisplayReady: false
12-19 12:56:00.942  3421  3421 I libsuspend: !@autosuspend_wakeup_count_disable done
,12-19 12:56:00.942  3421  3574 D DisplayPowerController: animateScreenStateChange[0]: target=4
,12-19 12:56:00.942  3010  3010 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7fa2c03c00
,12-19 12:56:00.942  3421  3421 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
12-19 12:56:00.942  3010  3010 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
,12-19 12:56:00.942  3421  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-19 12:56:00.942  3421  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
,12-19 12:56:00.942  3421  3574 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-19 12:56:00.942  3421  3586 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
12-19 12:56:00.942  3421  3570 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
12-19 12:56:00.942  3421  3570 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
,12-19 12:56:00.962  3421  3574 D DisplayPowerController: animateScreenStateChange[0]: target=4
12-19 12:56:00.962  3421  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-19 12:56:00.962  3421  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-19 12:56:00.962  3421  3574 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-19 12:56:00.962  3421  3574 I libsuspend: !@autosuspend_wakeup_count_enable
12-19 12:56:00.962  3421  3574 D DisplayPowerController: animateScreenStateChange[0]: target=4
12-19 12:56:00.962  3421  3574 I libsuspend: !@autosuspend_wakeup_count_enable done
12-19 12:56:00.962  3421  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-19 12:56:00.962  3421  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-19 12:56:00.962  3421  3574 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-19 12:56:00.962  3421  3574 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
12-19 12:56:00.962  3421  3574 D PowerManagerService: mDisplayReady: true
12-19 12:56:00.962  3421  3574 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,12-19 12:56:00.982  5854  5854 E CocktailBarPositionManager: Window direction: 0
12-19 12:56:00.982  5854  5854 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,12-19 12:56:01.082  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:01.272  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:01.442  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:01.622  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:01.802  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:01.992  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:02.162  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:02.342  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:02.522  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:02.702  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:02.882  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:03.062  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:03.242  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:03.422  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:03.612  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:03.782  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:03.892  3421  6185 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-19 12:56:03.962  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:04.142  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:04.322  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:04.502  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:04.692  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:04.872  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:05.042  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
12-19 12:56:05.042  3153  3630 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,12-19 12:56:05.222  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:05.402  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:05.582  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:05.762  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:05.952  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:06.122  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:06.312  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:06.492  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:06.662  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:06.842  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:07.022  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:07.202  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:07.382  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:07.512  3421  6150 D SSRM:n  : SIOP:: AP = 300, PST = 300 (W:14), CP = 257, CUR = 218, LCD = 1
,12-19 12:56:07.562  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:07.742  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:07.922  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:08.102  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:08.282  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:08.402  3421  4333 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-19 12:56:08.402  3421  4333 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4346, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 12:56:08.402  3421  4333 D BatteryService: online:4, current avg:215, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:215
12-19 12:56:08.402  3421  4333 D BatteryService: stay LED for charging
12-19 12:56:08.402  3421  3421 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-19 12:56:08.402  3421  3421 I MotionRecognitionService: Plugged
,12-19 12:56:08.402  3421  3421 D MotionRecognitionService:   cableConnection= 1
12-19 12:56:08.412  3421  3421 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-19 12:56:08.412  3421  3421 D MotionRecognitionService: skip setTransmitPower. 
,12-19 12:56:08.412  3421  3861 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-19 12:56:08.412  3938  3938 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-19 12:56:08.412  3938  3938 D KeyguardUpdateMonitor: handleBatteryUpdate
12-19 12:56:08.412  3938  3938 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-19 12:56:08.422  3938  3938 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,12-19 12:56:08.422  3938  3938 D PowerUI.Notification: There is no change about charging status, so return!
,12-19 12:56:08.432  5096  5096 D CommonServiceConfiguration: getStringValueSetting
,12-19 12:56:08.432  5054  5054 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-19 12:56:08.432  5054  5457 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-19 12:56:08.442  5096  5096 D BatteryMonitor: new battery level: 100
,12-19 12:56:08.442  4740  4740 D BatteryController: saveBatteryData : level[100], status[2]
,12-19 12:56:08.462  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,12-19 12:56:08.462  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
12-19 12:56:08.462  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:08.642  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:08.832  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:09.012  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:09.182  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:09.372  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:09.542  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:09.732  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:09.912  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:10.082  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:10.262  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:10.452  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:10.632  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:10.802  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:10.982  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:11.162  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:11.342  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:11.522  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:11.702  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:11.882  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:12.062  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:12.242  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:12.422  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:12.602  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:12.782  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:12.962  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:13.142  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:13.322  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:13.502  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:13.682  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:13.862  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:14.042  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:14.222  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:14.402  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:14.582  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:14.762  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:14.942  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:15.122  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:15.302  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:15.482  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:15.662  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:15.842  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:16.022  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:16.202  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:16.382  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:16.562  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:16.742  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:16.922  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:17.102  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:17.282  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:17.462  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:17.542  3421  4152 E Watchdog: !@Sync 9 [12-19 12:56:17.556]
,12-19 12:56:17.562  3421  6150 D SSRM:n  : SIOP:: AP = 290, PST = 299 (W:14), CP = 257, CUR = 215, LCD = 1
,12-19 12:56:17.642  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:17.822  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:18.002  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:18.182  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:18.362  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:18.462  3421  4417 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-19 12:56:18.462  3421  4417 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4347, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 12:56:18.462  3421  4417 D BatteryService: online:4, current avg:217, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:200
12-19 12:56:18.462  3421  4417 D BatteryService: stay LED for charging
12-19 12:56:18.462  3421  3421 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-19 12:56:18.462  3421  3421 I MotionRecognitionService: Plugged
12-19 12:56:18.462  3421  3421 D MotionRecognitionService:   cableConnection= 1
12-19 12:56:18.462  3421  3421 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-19 12:56:18.462  3421  3421 D MotionRecognitionService: skip setTransmitPower. 
,12-19 12:56:18.472  3421  3861 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-19 12:56:18.472  3938  3938 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-19 12:56:18.472  3938  3938 D KeyguardUpdateMonitor: handleBatteryUpdate
12-19 12:56:18.472  3938  3938 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-19 12:56:18.482  3938  3938 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,12-19 12:56:18.482  3938  3938 D PowerUI.Notification: There is no change about charging status, so return!
,12-19 12:56:18.492  5096  5096 D CommonServiceConfiguration: getStringValueSetting
,12-19 12:56:18.502  5054  5054 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-19 12:56:18.502  5054  5457 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-19 12:56:18.502  5096  5096 D BatteryMonitor: new battery level: 100
,12-19 12:56:18.512  4740  4740 D BatteryController: saveBatteryData : level[100], status[2]
,12-19 12:56:18.532  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,12-19 12:56:18.532  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,12-19 12:56:18.542  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:18.722  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:18.902  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:19.082  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:19.262  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:19.442  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:19.622  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:19.802  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:19.982  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:20.092  3153  3630 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,12-19 12:56:20.162  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:20.342  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:20.522  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:20.702  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:20.882  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:21.062  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:21.242  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:21.422  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:21.602  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:21.782  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:21.962  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:22.142  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:22.322  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:22.502  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:22.682  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:22.862  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:23.042  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:23.222  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:23.402  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:23.582  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:23.762  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:23.892  3421  6185 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-19 12:56:23.942  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:24.122  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:24.302  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:24.482  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:24.662  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:24.842  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:25.022  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:25.202  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:25.382  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:25.562  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:25.742  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:25.922  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:26.102  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:26.282  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:26.462  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:26.642  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:26.822  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:27.002  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:27.182  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:27.362  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:27.542  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:27.622  3421  6150 D SSRM:n  : SIOP:: AP = 290, PST = 298 (W:14), CP = 256, CUR = 217, LCD = 1
,12-19 12:56:27.722  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:27.902  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:28.082  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:28.262  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:28.442  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:28.522  3421  4417 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-19 12:56:28.522  3421  4417 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4346, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 12:56:28.522  3421  4417 D BatteryService: online:4, current avg:218, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:182
12-19 12:56:28.522  3421  4417 D BatteryService: stay LED for charging
12-19 12:56:28.522  3421  3421 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-19 12:56:28.522  3421  3421 I MotionRecognitionService: Plugged
12-19 12:56:28.522  3421  3421 D MotionRecognitionService:   cableConnection= 1
,12-19 12:56:28.522  3421  3421 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-19 12:56:28.522  3421  3421 D MotionRecognitionService: skip setTransmitPower. 
,12-19 12:56:28.532  3421  3861 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-19 12:56:28.532  3938  3938 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
12-19 12:56:28.532  3938  3938 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-19 12:56:28.532  3938  3938 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-19 12:56:28.542  3938  3938 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,12-19 12:56:28.542  3938  3938 D PowerUI.Notification: There is no change about charging status, so return!
,12-19 12:56:28.552  5096  5096 D CommonServiceConfiguration: getStringValueSetting
,12-19 12:56:28.562  5054  5054 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-19 12:56:28.562  5054  5457 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-19 12:56:28.562  5096  5096 D BatteryMonitor: new battery level: 100
,12-19 12:56:28.572  4740  4740 D BatteryController: saveBatteryData : level[100], status[2]
,12-19 12:56:28.572  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,12-19 12:56:28.572  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,12-19 12:56:28.612  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:28.802  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:28.982  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:29.152  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:29.342  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:29.522  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:29.702  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:29.882  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:30.062  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:30.232  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:30.422  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:30.602  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:30.782  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:30.952  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:31.132  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:31.312  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:31.502  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:31.682  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:31.852  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:32.042  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:32.212  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:32.402  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:32.572  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:32.752  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:32.942  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:33.112  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:33.302  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:33.472  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:33.652  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:33.842  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:34.022  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:34.192  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:34.382  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:34.552  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:34.732  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:34.922  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:35.092  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:35.282  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:35.462  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:35.642  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:35.822  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:35.992  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:36.172  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:36.362  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:36.542  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:36.722  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:36.892  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:37.072  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:37.262  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:37.432  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:37.612  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:37.682  3421  6150 D SSRM:n  : SIOP:: AP = 290, PST = 297 (W:14), CP = 256, CUR = 218, LCD = 1
,12-19 12:56:37.792  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:37.972  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:38.152  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:38.342  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:38.522  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:38.582  3421  3474 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,12-19 12:56:38.582  3421  3474 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4348, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 12:56:38.582  3421  3474 D BatteryService: online:4, current avg:216, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:204
12-19 12:56:38.582  3421  3474 D BatteryService: stay LED for charging
12-19 12:56:38.582  3421  3421 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-19 12:56:38.582  3421  3421 I MotionRecognitionService: Plugged
,12-19 12:56:38.582  3421  3421 D MotionRecognitionService:   cableConnection= 1
12-19 12:56:38.582  3421  3421 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-19 12:56:38.582  3421  3421 D MotionRecognitionService: skip setTransmitPower. 
,12-19 12:56:38.592  3421  3861 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-19 12:56:38.592  3938  3938 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-19 12:56:38.592  3938  3938 D KeyguardUpdateMonitor: handleBatteryUpdate
12-19 12:56:38.592  3938  3938 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-19 12:56:38.602  3938  3938 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
12-19 12:56:38.602  3938  3938 D PowerUI.Notification: There is no change about charging status, so return!
,12-19 12:56:38.612  5096  5096 D CommonServiceConfiguration: getStringValueSetting
,12-19 12:56:38.612  5054  5054 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
12-19 12:56:38.612  5054  5457 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-19 12:56:38.622  5096  5096 D BatteryMonitor: new battery level: 100
,12-19 12:56:38.622  4740  4740 D BatteryController: saveBatteryData : level[100], status[2]
,12-19 12:56:38.652  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,12-19 12:56:38.652  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,12-19 12:56:38.692  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:38.872  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:39.052  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:39.242  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:39.422  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:39.602  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:39.772  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:39.962  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:40.132  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:40.312  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:40.492  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:40.672  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:40.862  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:41.042  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:41.212  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:41.402  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:41.572  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:41.762  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:41.932  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:42.112  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:42.292  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:42.482  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:42.662  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:42.832  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:43.012  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:43.192  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:43.382  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:43.562  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:43.742  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:43.892  3421  6185 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-19 12:56:43.912  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:44.092  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:44.282  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:44.462  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:44.632  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:44.822  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:44.992  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:45.122  3421  3807 D TimaService: TIMA: TimaService scheduler is intialized. 
,12-19 12:56:45.122  3421  3807 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,12-19 12:56:45.132  3421  3806 D TimaService: TimaServiceHandler.handleMessage what =1
,12-19 12:56:45.132  3421  3807 I TLC_TIMA_PKM_initialize: initializing...
,12-19 12:56:45.132  3421  3807 I TLC_TIMA_PKM_initialize: root = 0, root_strlen = 1
12-19 12:56:45.132  3421  3807 I TLC_TIMA_PKM_initialize: process = ffffffff00000000000000000000000a, process_strlen = 32
12-19 12:56:45.132  3421  3807 I TZ: mc_tlc_communication: input max_sendmsg_size = 262196
12-19 12:56:45.132  3421  3807 I TZ: mc_tlc_communication: input max_recvmsg_size = 262196
12-19 12:56:45.132  3421  3807 I TZ: mc_tlc_communication: root = 0, root_len = 1
12-19 12:56:45.132  3421  3807 I TZ: mc_tlc_communication: process = ffffffff00000000000000000000000a, process_strlen = 32
12-19 12:56:45.132  3421  3807 I TZ: mc_tlc_communication: aligned max_sendmsg_size = 262208
,12-19 12:56:45.132  3421  3807 I TZ: mc_tlc_communication: aligned max_recvmsg_size = 262208
12-19 12:56:45.132  3421  3807 I TZ: mc_tlc_communication: device_id = 0x0
12-19 12:56:45.132  3421  3807 I TZ: mc_tlc_communication: tlc_open() was called
12-19 12:56:45.132  3421  3807 I TZ: mc_tlc_communication: Opening MobiCore device
12-19 12:56:45.132  3421  3807 I TeeDriverClient: driver client open [hardware/samsung_slsi/exynos8890/mobicore/ClientLib/src/driver_client.cpp:103]
12-19 12:56:45.132  3421  3807 I TZ: mc_tlc_communication: Allocating message buffer for TCI
12-19 12:56:45.132  3421  3807 I TZ: mc_tlc_communication: Opening the session
,12-19 12:56:45.172  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:45.182  3421  3807 I TZ: mc_tlc_communication: tlc_open() succeeded
12-19 12:56:45.182  3421  3807 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info1
,12-19 12:56:45.202  3421  3807 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info2
,12-19 12:56:45.212  3421  3807 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info3
,12-19 12:56:45.222  3421  3807 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info4
,12-19 12:56:45.252  3421  3807 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,12-19 12:56:45.352  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:45.532  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:45.712  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:45.892  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:46.072  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:46.252  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:46.432  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:46.612  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:46.792  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:46.972  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:47.152  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:47.332  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:47.512  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:47.542  3421  4152 E Watchdog: !@Sync 10 [12-19 12:56:47.558]
,12-19 12:56:47.692  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:47.732  3421  6150 D SSRM:n  : SIOP:: AP = 300, PST = 297 (W:10), CP = 256, CUR = 216, LCD = 1
,12-19 12:56:47.872  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:48.052  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:48.232  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:48.412  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:48.582  3421  3815 V AlarmManager: Expired Alarm result :4
,12-19 12:56:48.592  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:48.632  3421  4616 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,12-19 12:56:48.632  3421  4616 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4345, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 12:56:48.632  3421  4616 D BatteryService: online:4, current avg:213, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:212
12-19 12:56:48.632  3421  4616 D BatteryService: stay LED for charging
,12-19 12:56:48.632 10079 10079 E Zygote  : v2
12-19 12:56:48.642 10079 10079 I libpersona: KNOX_SDCARD checking this for 1000
12-19 12:56:48.642 10079 10079 I libpersona: KNOX_SDCARD not a persona
,12-19 12:56:48.642 10079 10079 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0029
,12-19 12:56:48.642  3421  3815 I ActivityManager: Start proc 10079:com.mobeam.barcodeService/1000 for service com.mobeam.barcodeService/.system.AppService
,12-19 12:56:48.642 10079 10079 E Zygote  : accessInfo : 0
12-19 12:56:48.642  3421  3421 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-19 12:56:48.642  3421  3421 I MotionRecognitionService: Plugged
,12-19 12:56:48.642  3421  3421 D MotionRecognitionService:   cableConnection= 1
12-19 12:56:48.642  3421  3421 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-19 12:56:48.642  3421  3421 D MotionRecognitionService: skip setTransmitPower. 
,12-19 12:56:48.652  3421  3861 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-19 12:56:48.652  3938  3938 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-19 12:56:48.652  3938  3938 D KeyguardUpdateMonitor: handleBatteryUpdate
12-19 12:56:48.652  3938  3938 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-19 12:56:48.652  3938  3938 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
12-19 12:56:48.652  3938  3938 D PowerUI.Notification: There is no change about charging status, so return!
,12-19 12:56:48.662  5096  5096 D CommonServiceConfiguration: getStringValueSetting
,12-19 12:56:48.662  5054  5054 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-19 12:56:48.662  5054  5457 D HeadsetStateMachine: Disconnected process message: 10, size: 0
12-19 12:56:48.662  5096  5096 D BatteryMonitor: new battery level: 100
,12-19 12:56:48.672  4740  4740 D BatteryController: saveBatteryData : level[100], status[2]
,12-19 12:56:48.672 10079 10079 D TimaKeyStoreProvider: TimaSignature is unavailable
,12-19 12:56:48.672 10079 10079 D ActivityThread: Added TimaKeyStore provider
,12-19 12:56:48.682  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,12-19 12:56:48.682  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,12-19 12:56:48.702 10079 10079 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
12-19 12:56:48.702 10079 10079 D RelationGraph: garbageCollect()
,12-19 12:56:48.712 10079 10079 W ResourcesManager: getTopLevelResources: /system/app/BeamService/BeamService.apk / 1.0 running in com.mobeam.barcodeService rsrc of package com.mobeam.barcodeService
,12-19 12:56:48.712  3421  3474 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
12-19 12:56:48.712 10079 10079 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,12-19 12:56:48.712 10079 10079 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:56:48.722 10079 10079 I InjectionManager: Inside getClassLibPath caller 
,12-19 12:56:48.732 10079 10079 W System  : ClassLoader referenced unknown path: /system/app/BeamService/lib/arm64
,12-19 12:56:48.732 10079 10079 D InjectionManager: InjectionManager
12-19 12:56:48.732 10079 10079 D InjectionManager: fillFeatureStoreMap com.mobeam.barcodeService
,12-19 12:56:48.732 10079 10079 I InjectionManager: Constructor com.mobeam.barcodeService, Feature store :{}
12-19 12:56:48.732 10079 10079 I InjectionManager: featureStore :{}
,12-19 12:56:48.762  3421  4182 I ActivityManager: Killing 8677:com.android.providers.calendar/u0a50 (adj 15): DHA:empty #33
,12-19 12:56:48.772  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:48.792  3421  3983 D ActivityManager: isAutoRunBlockedApp:: com.android.providers.calendar, Auto Run ON
,12-19 12:56:48.822  3421  3807 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
12-19 12:56:48.822  3421  3807 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,12-19 12:56:48.832  3421  3807 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,12-19 12:56:48.832  3421  3807 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,12-19 12:56:48.952  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:49.132  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:49.132  4400  4465 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
12-19 12:56:49.132  4400  4465 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,12-19 12:56:49.312  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:49.492  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:49.672  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:49.852  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:50.032  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:50.212  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:50.392  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:50.572  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:50.752  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:50.932  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:51.112  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:51.292  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:51.482  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:51.652  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:51.822  3153  3630 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,12-19 12:56:51.832  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:52.012  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:52.192  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:52.372  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:52.552  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:52.742  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:52.912  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:53.092  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:53.282  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:53.452  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:53.642  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:53.812  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:54.002  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:54.172  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:54.352  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:54.532  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:54.712  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:54.902  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:55.072  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:55.262  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:55.432  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:55.612  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:55.792  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:55.972  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:56.152  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:56.332  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:56.512  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:56.692  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:56.872  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:57.052  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:57.232  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:57.412  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:57.592  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:57.772  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:57.792  3421  6150 D SSRM:n  : SIOP:: AP = 290, PST = 296 (W:10), CP = 256, CUR = 213, LCD = 1
,12-19 12:56:57.952  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:58.132  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:58.312  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:58.492  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:58.672  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:58.692  3421  4420 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-19 12:56:58.692  3421  4420 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4349, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 12:56:58.692  3421  4420 D BatteryService: online:4, current avg:219, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:250
12-19 12:56:58.692  3421  4420 D BatteryService: stay LED for charging
12-19 12:56:58.692  3421  3421 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-19 12:56:58.702  3421  3421 I MotionRecognitionService: Plugged
,12-19 12:56:58.702  3421  3421 D MotionRecognitionService:   cableConnection= 1
12-19 12:56:58.702  3421  3421 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-19 12:56:58.702  3421  3421 D MotionRecognitionService: skip setTransmitPower. 
,12-19 12:56:58.712  3421  3861 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-19 12:56:58.712  3938  3938 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-19 12:56:58.712  3938  3938 D KeyguardUpdateMonitor: handleBatteryUpdate
12-19 12:56:58.712  3938  3938 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-19 12:56:58.712  3938  3938 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
12-19 12:56:58.712  3938  3938 D PowerUI.Notification: There is no change about charging status, so return!
,12-19 12:56:58.732  5096  5096 D CommonServiceConfiguration: getStringValueSetting
,12-19 12:56:58.732  5054  5054 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
12-19 12:56:58.732  5054  5457 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-19 12:56:58.742  5096  5096 D BatteryMonitor: new battery level: 100
,12-19 12:56:58.742  4740  4740 D BatteryController: saveBatteryData : level[100], status[2]
,12-19 12:56:58.762  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,12-19 12:56:58.762  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,12-19 12:56:58.852  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:59.032  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:59.212  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:59.392  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:59.572  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:59.752  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:59.932  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:56:59.982  3421  3815 V AlarmManager: Expired Alarm result :8
,12-19 12:57:00.112  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:00.292  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:00.472  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:00.652  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:00.782  3421  3815 V AlarmManager: Expired Alarm result :4
,12-19 12:57:00.782  3421  3815 V AlarmManager: Send whitelist package alarm :PendingIntent{afa653a: PendingIntentRecord{3f94b70 com.samsung.android.app.aodservice broadcastIntent}}
,12-19 12:57:00.782  3938  3938 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
12-19 12:57:00.782  3938  3938 D KeyguardUpdateMonitor: handleTimeUpdate
,12-19 12:57:00.802  3938  3938 D Clock   : received broadcast android.intent.action.TIME_TICK
,12-19 12:57:00.832  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:00.882  3938  3938 D DateView: received broadcast android.intent.action.TIME_TICK
,12-19 12:57:00.912  8036  8036 D [WeatherWidget(1240)]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,12-19 12:57:00.912  8036  8036 D [WeatherWidget(1240)]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,12-19 12:57:00.922  4740  4740 D AODService.ClockTimer: onReceive : com.samsung.android.app.aodservice.ClockTimer.TICK, mWakeUp = true
,12-19 12:57:00.922  4740  4740 V BatteryController: getBatteryLevel[100.0], batteryStatus[2]
,12-19 12:57:00.922  3421  3474 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,12-19 12:57:00.922  3421  3474 I CAE     : setPropertyValue(DevicePhysicalContextMonitorRunner.java:155) - Get status
12-19 12:57:00.922  3421  3474 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -72, 56, 1, 1,
12-19 12:57:00.922  3421  3474 D SensorHubManager: SendSensorHubData: send data = -72, 56, 1, 1
12-19 12:57:00.922  3168  3168 D Sensorhubs: sendContextData: -72, 56, 1, 1
,12-19 12:57:00.932  3421  3474 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
,12-19 12:57:00.932  3421  3474 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
12-19 12:57:00.932  3421  3474 D SContextService: requestToUpdate() : service = Device Physical Context Monitor
12-19 12:57:00.932  4740  4740 D SContextManager:   .requestToUpdate : listener = com.samsung.android.app.aodservice.AODService$7@63b629b, service=Device Physical Context Monitor
,12-19 12:57:00.932  4740  4740 I AlpmModeManager: startAlpmMode : state  = BLANK
12-19 12:57:00.932  4740  4740 D DefaultClockView: Window showed. Time views updating
12-19 12:57:00.932  3421  4415 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3421
,12-19 12:57:00.932  3421  4415 I libsuspend: !@autosuspend_wakeup_count_disable
12-19 12:57:00.932  3421  4415 D PowerManagerService: mDisplayReady: false
12-19 12:57:00.932  3421  4415 I libsuspend: !@autosuspend_wakeup_count_disable done
12-19 12:57:00.932  3421  3574 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-19 12:57:00.932  4740  4740 D AODUpdatePositionController: updatePosition: direction[1] updatePosition: X[27] Y[219] NewPositionTimer[55]
12-19 12:57:00.932  3421  4415 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
12-19 12:57:00.932  3421  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-19 12:57:00.942  3010  3010 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fa2c03c00
12-19 12:57:00.932  3421  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-19 12:57:00.942  3010  3010 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
12-19 12:57:00.932  3421  3574 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-19 12:57:00.942  4740  4740 D DefaultClockView: LocalTime Pattern : HH:mm
12-19 12:57:00.932  3421  3586 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
12-19 12:57:00.942  4740  4740 D TimeViewHolder: onTimeUpdate: timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] isSplitHour:false isSingleView:false isAMPMonLeft:null time01: 12:57 time02: null ampm: null
,12-19 12:57:00.942  3421  3570 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
12-19 12:57:00.942  3421  3570 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
,12-19 12:57:00.952  3168  3213 D Sensorhubs: readContextData: 1, 1, 56, 1, 1, 1, 1
,12-19 12:57:00.952  3421  3818 D SensorHubManager: onGetSensorHubDataLocked: library(7) = 1, 1, 56, 1, 1, 1, 1
12-19 12:57:00.952  3421  3817 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 14, 11, 57, 0,
,12-19 12:57:00.952  3421  3817 D SensorHubManager: SendSensorHubData: send data = -63, 14, 11, 57, 0
,12-19 12:57:00.952  3421  3574 D DisplayPowerController: animateScreenStateChange[0]: target=3
,12-19 12:57:00.952  3421  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-19 12:57:00.952  3421  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-19 12:57:00.952  3421  3574 I libsuspend: !@autosuspend_wakeup_count_enable
12-19 12:57:00.952  3421  3574 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-19 12:57:00.952  3421  3574 I libsuspend: !@autosuspend_wakeup_count_enable done
12-19 12:57:00.952  3421  3574 D DisplayPowerController: animateScreenStateChange[0]: target=3
,12-19 12:57:00.952  3421  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-19 12:57:00.952  3421  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-19 12:57:00.952  3421  3574 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-19 12:57:00.952  3421  3574 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
12-19 12:57:00.952  3421  3574 D PowerManagerService: mDisplayReady: true
12-19 12:57:00.952  3421  3574 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,12-19 12:57:00.952  3168  3214 D Sensorhubs: sendContextData: -63, 14, 11, 57, 0
,12-19 12:57:00.962  5854  5854 E CocktailBarPositionManager: Window direction: 0
12-19 12:57:00.962  5854  5854 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,12-19 12:57:00.962  3421  3817 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :7], AP_SLEEP
12-19 12:57:00.962  3421  3817 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 7
,12-19 12:57:00.962  3421  3817 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 56, 1, 1, 1, 1,
,12-19 12:57:00.962  3421  3817 D CAE     : display(ContextProvider.java:375) - ================= DEVICE_PHYSICAL_CONTEXT_MONITOR =================
12-19 12:57:00.962  3421  3817 I CAE     : display(ContextProvider.java:391) - AODReason=[1], AODStatus=[1], DataType=[1]
,12-19 12:57:00.962  3421  3820 D SContextService: updateSContext() : event = Device Physical Context Monitor
,12-19 12:57:00.972  4740  4740 D RoamingTimeViewHolder: isDualClockSetting :: true isHomeTimeZoneExist :: false isEasyUxON :: false Utils.isRoaming(mContext) :: false
,12-19 12:57:00.972  4740  4740 D RoamingTimeViewHolder: getHomeCalendar : No homecity_timezone, set as default :  (libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167])
,12-19 12:57:00.972  4740  4740 D RoamingTimeViewHolder: onTimeUpdate: isVisible:false timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] text:pon., 19 gru 12:57
12-19 12:57:00.972  4740  4740 I AODService.ClockTimer: startAlarm : TICK
,12-19 12:57:00.972  3421  3981 V AlarmManager: Add whitelist package alarm :PendingIntent{3ea47f4: PendingIntentRecord{3f94b70 com.samsung.android.app.aodservice broadcastIntent}}
,12-19 12:57:00.972  4740  4740 I AlpmModeManager: handleUnblankDisplay: state  = BLANK
12-19 12:57:00.972  4740  4740 V AlpmModeManager: updateAlpmMode: setDoze [DISPLAY_STATE_DOZE_SUSPEND]
,12-19 12:57:00.982  3421  4421 I PowerManagerService: [api] setDozeOverrideFromAod AlpmHlpmSysfs = -1, screenState = 4, Brightness = 0, wakefulness = false
12-19 12:57:00.982  3421  4421 D PowerManagerService: setDozeModeBySysfs:  value is -1 , we ignore it. 
,12-19 12:57:00.982  4740  4740 I AODService: onSContextChanged: AODScreenShown state is already true
,12-19 12:57:00.982  4740  4740 D DefaultClockView: RootView invalidate()
12-19 12:57:00.982  3421  4420 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3421
,12-19 12:57:01.012  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:01.132  3421  3421 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3421 (0x0)
,12-19 12:57:01.132  3421  3421 I libsuspend: !@autosuspend_wakeup_count_disable
12-19 12:57:01.132  3421  3421 D PowerManagerService: mDisplayReady: false
12-19 12:57:01.132  3421  3421 I libsuspend: !@autosuspend_wakeup_count_disable done
12-19 12:57:01.132  3421  3574 D DisplayPowerController: animateScreenStateChange[0]: target=4
,12-19 12:57:01.132  3421  3421 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
12-19 12:57:01.132  3421  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-19 12:57:01.132  3421  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-19 12:57:01.132  3010  3010 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7fa2c03c00
,12-19 12:57:01.132  3421  3574 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-19 12:57:01.132  3010  3010 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
12-19 12:57:01.132  3421  3586 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
12-19 12:57:01.132  3421  3570 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
12-19 12:57:01.132  3421  3570 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
,12-19 12:57:01.142  3421  3574 D DisplayPowerController: animateScreenStateChange[0]: target=4
12-19 12:57:01.142  3421  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
,12-19 12:57:01.142  3421  3574 I libsuspend: !@autosuspend_wakeup_count_enable
12-19 12:57:01.142  3421  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1,
12-19 12:57:01.142  3421  3574 I libsuspend: !@autosuspend_wakeup_count_enable done
,12-19 12:57:01.142  3421  3574 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-19 12:57:01.142  3421  3574 D DisplayPowerController: animateScreenStateChange[0]: target=4
12-19 12:57:01.142  3421  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
,12-19 12:57:01.142  3421  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-19 12:57:01.142  3421  3574 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-19 12:57:01.142  3421  3574 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
12-19 12:57:01.142  3421  3574 D PowerManagerService: mDisplayReady: true
12-19 12:57:01.142  3421  3574 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,12-19 12:57:01.172  5854  5854 E CocktailBarPositionManager: Window direction: 0
12-19 12:57:01.172  5854  5854 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,12-19 12:57:01.192  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:01.372  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:01.552  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:01.732  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:01.912  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:02.092  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:02.272  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:02.452  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:02.632  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:02.812  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:02.992  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:03.172  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:03.352  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:03.532  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:03.712  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:03.892  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:03.892  3421  6185 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-19 12:57:04.082  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:04.252  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:04.432  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:04.612  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:04.792  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:04.972  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:05.152  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:05.332  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:05.512  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:05.692  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:05.872  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:06.052  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:06.232  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:06.412  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:06.592  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:06.772  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:06.952  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:07.132  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:07.312  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:07.492  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:07.672  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:07.852  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:07.852  3421  6150 D SSRM:n  : SIOP:: AP = 290, PST = 295 (W:10), CP = 255, CUR = 219, LCD = 1
,12-19 12:57:08.032  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:08.212  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:08.392  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:08.572  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:08.752  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:08.752  3421  4333 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-19 12:57:08.752  3421  4333 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4349, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 12:57:08.752  3421  4333 D BatteryService: online:4, current avg:217, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:233
12-19 12:57:08.752  3421  4333 D BatteryService: stay LED for charging
12-19 12:57:08.752  3421  3421 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-19 12:57:08.762  3421  3421 I MotionRecognitionService: Plugged
12-19 12:57:08.762  3421  3421 D MotionRecognitionService:   cableConnection= 1
12-19 12:57:08.762  3421  3421 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-19 12:57:08.762  3421  3421 D MotionRecognitionService: skip setTransmitPower. 
,12-19 12:57:08.762  3421  3861 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-19 12:57:08.772  3938  3938 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-19 12:57:08.772  3938  3938 D KeyguardUpdateMonitor: handleBatteryUpdate
12-19 12:57:08.772  3938  3938 D PowerUI : priorPlugType = 2 mPlugType =  2,
,12-19 12:57:08.772  3938  3938 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,12-19 12:57:08.772  3938  3938 D PowerUI.Notification: There is no change about charging status, so return!
,12-19 12:57:08.792  5096  5096 D CommonServiceConfiguration: getStringValueSetting
,12-19 12:57:08.792  5054  5054 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-19 12:57:08.792  5054  5457 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-19 12:57:08.802  5096  5096 D BatteryMonitor: new battery level: 100
,12-19 12:57:08.802  4740  4740 D BatteryController: saveBatteryData : level[100], status[2]
,12-19 12:57:08.822  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,12-19 12:57:08.822  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,12-19 12:57:08.932  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:09.112  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:09.292  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:09.472  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:09.652  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:09.832  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:10.012  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:10.192  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:10.372  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:10.552  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:10.732  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:10.912  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:11.092  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:11.272  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:11.452  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:11.632  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:11.812  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:11.992  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:12.162  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:12.352  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:12.532  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:12.712  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:12.892  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:13.072  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:13.252  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:13.432  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:13.612  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:13.792  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:13.962  9151  9192 W PlayEventLogger: No account for auth token provided
,12-19 12:57:13.972  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
12-19 12:57:13.972  9151  9192 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-19 12:57:13.972  9151  9192 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,12-19 12:57:13.982  3153  3634 D EnterpriseController: netId is 0
,12-19 12:57:13.982  3153  3634 D Netd    : getNetworkForDns: using netid 502 for uid 10035
,12-19 12:57:14.142  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:14.332  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:14.512  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:14.692  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:14.872  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:15.052  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:15.232  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:15.412  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:15.592  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:15.772  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:15.952  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:16.132  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:16.312  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:16.492  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:16.662  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:16.852  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:17.032  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:17.212  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:17.392  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:17.542  3421  4152 E Watchdog: !@Sync 11 [12-19 12:57:17.560]
,12-19 12:57:17.572  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:17.752  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:17.912  3421  6150 D SSRM:n  : SIOP:: AP = 290, PST = 294 (W:10), CP = 255, CUR = 217, LCD = 1
,12-19 12:57:17.922  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:18.102  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:18.292  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:18.472  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:18.652  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:18.812  3421  4616 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-19 12:57:18.812  3421  4616 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4350, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 12:57:18.812  3421  4616 D BatteryService: online:4, current avg:219, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:228
12-19 12:57:18.812  3421  4616 D BatteryService: stay LED for charging
12-19 12:57:18.812  3421  3421 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-19 12:57:18.812  3421  3421 I MotionRecognitionService: Plugged
,12-19 12:57:18.812  3421  3421 D MotionRecognitionService:   cableConnection= 1
12-19 12:57:18.812  3421  3421 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-19 12:57:18.812  3421  3421 D MotionRecognitionService: skip setTransmitPower. 
,12-19 12:57:18.822  3421  3861 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-19 12:57:18.822  3938  3938 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-19 12:57:18.822  3938  3938 D KeyguardUpdateMonitor: handleBatteryUpdate
12-19 12:57:18.822  3938  3938 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-19 12:57:18.832  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:18.832  3938  3938 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,12-19 12:57:18.832  3938  3938 D PowerUI.Notification: There is no change about charging status, so return!
,12-19 12:57:18.852  5096  5096 D CommonServiceConfiguration: getStringValueSetting
,12-19 12:57:18.852  5054  5054 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-19 12:57:18.852  5054  5457 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-19 12:57:18.862  5096  5096 D BatteryMonitor: new battery level: 100
,12-19 12:57:18.862  4740  4740 D BatteryController: saveBatteryData : level[100], status[2]
,12-19 12:57:18.892  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,12-19 12:57:18.892  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,12-19 12:57:19.012  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:19.182  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:19.372  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:19.542  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:19.732  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:19.912  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:20.082  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:20.272  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:20.452  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:20.632  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:20.802  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:20.992  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:21.162  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:21.352  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:21.532  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:21.702  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:21.892  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:22.062  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:22.242  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:22.422  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:22.602  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:22.792  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:22.972  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:23.142  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:23.332  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:23.502  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:23.692  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:23.872  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:23.892  3421  6185 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-19 12:57:24.042  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:24.222  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:24.402  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:24.592  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:24.762  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:24.952  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:25.122  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:25.302  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:25.482  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:25.672  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:25.842  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:26.022  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:26.212  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:26.392  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:26.572  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:26.742  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:26.932  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:27.102  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:27.282  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:27.462  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:27.642  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:27.822  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:27.972  3421  6150 D SSRM:n  : SIOP:: AP = 290, PST = 293 (W:14), CP = 255, CUR = 219, LCD = 1
,12-19 12:57:28.002  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:28.182  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:28.372  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:28.542  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:28.722  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:28.872  3421  4421 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,12-19 12:57:28.872  3421  4421 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4349, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 12:57:28.872  3421  4421 D BatteryService: online:4, current avg:222, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:230
12-19 12:57:28.872  3421  4421 D BatteryService: stay LED for charging
12-19 12:57:28.872  3421  3421 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-19 12:57:28.872  3421  3421 I MotionRecognitionService: Plugged
,12-19 12:57:28.872  3421  3421 D MotionRecognitionService:   cableConnection= 1
12-19 12:57:28.872  3421  3421 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-19 12:57:28.872  3421  3421 D MotionRecognitionService: skip setTransmitPower. 
,12-19 12:57:28.882  3421  3861 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-19 12:57:28.882  3938  3938 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-19 12:57:28.882  3938  3938 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-19 12:57:28.882  3938  3938 D PowerUI : priorPlugType = 2 mPlugType =  2
12-19 12:57:28.892  3938  3938 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,12-19 12:57:28.892  3938  3938 D PowerUI.Notification: There is no change about charging status, so return!
,12-19 12:57:28.902  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:28.912  5096  5096 D CommonServiceConfiguration: getStringValueSetting
,12-19 12:57:28.912  5054  5054 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-19 12:57:28.912  5054  5457 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-19 12:57:28.922  5096  5096 D BatteryMonitor: new battery level: 100
,12-19 12:57:28.922  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,12-19 12:57:28.922  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,12-19 12:57:28.932  4740  4740 D BatteryController: saveBatteryData : level[100], status[2]
,12-19 12:57:29.082  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:29.272  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:29.332  3153  3630 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,12-19 12:57:29.452  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:29.632  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:29.812  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:29.992  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:30.162  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:30.352  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:30.522  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:30.712  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:30.892  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:31.062  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:31.252  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:31.422  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:31.602  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:31.782  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:31.962  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:32.142  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:32.322  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:32.502  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:32.682  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:32.862  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:33.042  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:33.222  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:33.402  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:33.582  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:33.762  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:33.942  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:34.122  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:34.302  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:34.482  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:34.662  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:34.822  3153  3630 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,12-19 12:57:34.842  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:35.022  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:35.202  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:35.382  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:35.562  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:35.742  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:35.922  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:36.102  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:36.292  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:36.472  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:36.652  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:36.822  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:37.012  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:37.182  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:37.362  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:37.542  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:37.732  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:37.912  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:38.032  3421  6150 D SSRM:n  : SIOP:: AP = 290, PST = 291 (W:14), CP = 254, CUR = 222, LCD = 1
,12-19 12:57:38.082  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:38.272  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:38.442  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:38.622  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:38.802  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:38.922  3421  4182 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-19 12:57:38.922  3421  4182 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4350, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 12:57:38.922  3421  4182 D BatteryService: online:4, current avg:222, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:215
12-19 12:57:38.922  3421  4182 D BatteryService: stay LED for charging
12-19 12:57:38.932  3421  3421 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-19 12:57:38.932  3421  3421 I MotionRecognitionService: Plugged
,12-19 12:57:38.932  3421  3421 D MotionRecognitionService:   cableConnection= 1
12-19 12:57:38.932  3421  3421 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,12-19 12:57:38.932  3421  3421 D MotionRecognitionService: skip setTransmitPower. 
,12-19 12:57:38.942  3421  3861 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-19 12:57:38.942  3938  3938 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-19 12:57:38.942  3938  3938 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-19 12:57:38.942  3938  3938 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-19 12:57:38.952  3938  3938 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,12-19 12:57:38.952  3938  3938 D PowerUI.Notification: There is no change about charging status, so return!
,12-19 12:57:38.962  5096  5096 D CommonServiceConfiguration: getStringValueSetting
,12-19 12:57:38.972  5054  5054 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-19 12:57:38.972  5054  5457 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-19 12:57:38.972  5096  5096 D BatteryMonitor: new battery level: 100
,12-19 12:57:38.982  4740  4740 D BatteryController: saveBatteryData : level[100], status[2]
,12-19 12:57:38.982  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:38.992  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,12-19 12:57:38.992  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,12-19 12:57:39.162  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:39.342  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:39.532  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:39.702  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:39.882  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:40.062  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:40.252  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:40.432  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:40.612  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:40.792  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:40.962  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:41.142  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:41.322  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:41.512  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:41.682  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:41.872  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:42.052  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:42.232  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:42.412  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:42.582  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:42.772  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:42.942  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:43.122  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:43.312  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:43.482  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:43.662  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:43.842  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:43.902  3421  6185 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-19 12:57:44.022  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:44.202  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:44.382  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:44.562  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:44.742  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:44.922  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:45.102  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:45.282  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:45.462  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:45.642  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:45.822  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:46.002  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:46.182  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:46.362  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:46.542  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:46.722  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:46.902  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:47.082  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:47.262  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:47.442  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:47.552  3421  4152 E Watchdog: !@Sync 12 [12-19 12:57:47.562]
,12-19 12:57:47.622  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:47.802  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:47.982  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:48.052  3421  6150 D SSRM:n  : SIOP:: AP = 290, PST = 290 (W:14), CP = 254, CUR = 222, LCD = 1
,12-19 12:57:48.162  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:48.342  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:48.522  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:48.702  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:48.882  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:48.982  3421  4333 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,12-19 12:57:48.982  3421  4333 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4349, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 12:57:48.982  3421  4333 D BatteryService: online:4, current avg:221, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:168
12-19 12:57:48.982  3421  4333 D BatteryService: stay LED for charging
,12-19 12:57:48.982  3421  3421 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-19 12:57:48.992  3421  3421 I MotionRecognitionService: Plugged
,12-19 12:57:48.992  3421  3421 D MotionRecognitionService:   cableConnection= 1
12-19 12:57:48.992  3421  3421 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-19 12:57:48.992  3421  3421 D MotionRecognitionService: skip setTransmitPower. 
,12-19 12:57:49.002  3421  3861 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-19 12:57:49.002  3938  3938 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
12-19 12:57:49.002  3938  3938 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-19 12:57:49.002  3938  3938 D PowerUI : priorPlugType = 2 mPlugType =  2
12-19 12:57:49.002  3938  3938 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,12-19 12:57:49.002  3938  3938 D PowerUI.Notification: There is no change about charging status, so return!
,12-19 12:57:49.022  5096  5096 D CommonServiceConfiguration: getStringValueSetting
,12-19 12:57:49.022  5054  5054 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
12-19 12:57:49.022  5054  5457 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-19 12:57:49.022  5096  5096 D BatteryMonitor: new battery level: 100
,12-19 12:57:49.032  4740  4740 D BatteryController: saveBatteryData : level[100], status[2]
,12-19 12:57:49.052  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,12-19 12:57:49.052  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,12-19 12:57:49.062  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:49.242  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:49.242  4400  4465 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
12-19 12:57:49.242  4400  4465 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,12-19 12:57:49.332  4400  4465 E ContactsProvider_EventLog: Flush buffer to file cnt : 4 size : 0Kb duration : 88ms lastUpdatedAfter : 180333ms
,12-19 12:57:49.422  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:49.602  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:49.782  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:49.852  3153  3630 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,12-19 12:57:49.962  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:50.142  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:50.322  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:50.502  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:50.682  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:50.862  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:51.042  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:51.222  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:51.402  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:51.582  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:51.762  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:51.942  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:52.122  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:52.302  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:52.482  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:52.662  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:52.842  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:53.022  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:53.202  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:53.382  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:53.562  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:53.742  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:53.922  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:54.102  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:54.282  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:54.462  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:54.642  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:54.822  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:55.002  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:55.182  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:55.362  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:55.542  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:55.722  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:55.902  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:56.082  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:56.262  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:56.442  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:56.622  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:56.802  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:56.982  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:57.162  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:57.342  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:57.522  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:57.702  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:57.882  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:58.062  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:58.112  3421  6150 D SSRM:n  : SIOP:: AP = 290, PST = 290 (W:14), CP = 254, CUR = 221, LCD = 1
,12-19 12:57:58.242  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:58.422  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:58.602  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:58.782  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:58.962  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:59.042  3421  4333 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-19 12:57:59.042  3421  4333 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4351, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 12:57:59.042  3421  4333 D BatteryService: online:4, current avg:214, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:210
12-19 12:57:59.042  3421  4333 D BatteryService: stay LED for charging
12-19 12:57:59.042  3421  3421 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-19 12:57:59.052  3421  3421 I MotionRecognitionService: Plugged
,12-19 12:57:59.052  3421  3421 D MotionRecognitionService:   cableConnection= 1
12-19 12:57:59.052  3421  3421 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-19 12:57:59.052  3421  3421 D MotionRecognitionService: skip setTransmitPower. 
,12-19 12:57:59.052  3421  3861 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-19 12:57:59.062  3938  3938 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-19 12:57:59.062  3938  3938 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-19 12:57:59.062  3938  3938 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-19 12:57:59.062  3938  3938 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
12-19 12:57:59.062  3938  3938 D PowerUI.Notification: There is no change about charging status, so return!
,12-19 12:57:59.082  5096  5096 D CommonServiceConfiguration: getStringValueSetting
,12-19 12:57:59.082  5054  5054 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-19 12:57:59.082  5054  5457 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-19 12:57:59.092  5096  5096 D BatteryMonitor: new battery level: 100
,12-19 12:57:59.092  4740  4740 D BatteryController: saveBatteryData : level[100], status[2]
,12-19 12:57:59.112  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,12-19 12:57:59.112  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,12-19 12:57:59.142  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:59.322  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:59.502  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:59.682  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:59.862  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:57:59.992  3421  3815 V AlarmManager: Expired Alarm result :8
,12-19 12:58:00.042  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:58:00.222  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:58:00.402  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:58:00.582  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:58:00.762  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:58:00.942  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:58:00.972  3421  3815 V AlarmManager: Expired Alarm result :4
,12-19 12:58:00.972  3421  3815 V AlarmManager: Send whitelist package alarm :PendingIntent{3ea47f4: PendingIntentRecord{3f94b70 com.samsung.android.app.aodservice broadcastIntent}}
,12-19 12:58:00.982  3938  3938 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
12-19 12:58:00.982  3938  3938 D KeyguardUpdateMonitor: handleTimeUpdate
,12-19 12:58:01.002  3938  3938 D Clock   : received broadcast android.intent.action.TIME_TICK
,12-19 12:58:01.062  3938  3938 D DateView: received broadcast android.intent.action.TIME_TICK
,12-19 12:58:01.092  8036  8036 D [WeatherWidget(1240)]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,12-19 12:58:01.092  8036  8036 D [WeatherWidget(1240)]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,12-19 12:58:01.092  4740  4740 D AODService.ClockTimer: onReceive : com.samsung.android.app.aodservice.ClockTimer.TICK, mWakeUp = true
12-19 12:58:01.102  4740  4740 V BatteryController: getBatteryLevel[100.0], batteryStatus[2]
,12-19 12:58:01.102  3421  4420 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,12-19 12:58:01.102  3421  4420 I CAE     : setPropertyValue(DevicePhysicalContextMonitorRunner.java:155) - Get status
12-19 12:58:01.102  3421  4420 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -72, 56, 1, 1,
12-19 12:58:01.102  3421  4420 D SensorHubManager: SendSensorHubData: send data = -72, 56, 1, 1
12-19 12:58:01.102  3168  3168 D Sensorhubs: sendContextData: -72, 56, 1, 1
,12-19 12:58:01.112  3421  4420 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
12-19 12:58:01.112  3421  4420 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
12-19 12:58:01.112  3421  4420 D SContextService: requestToUpdate() : service = Device Physical Context Monitor
,12-19 12:58:01.112  4740  4740 D SContextManager:   .requestToUpdate : listener = com.samsung.android.app.aodservice.AODService$7@63b629b, service=Device Physical Context Monitor
12-19 12:58:01.112  4740  4740 I AlpmModeManager: startAlpmMode : state  = BLANK
12-19 12:58:01.112  4740  4740 D DefaultClockView: Window showed. Time views updating
,12-19 12:58:01.112  3421  4391 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3421
12-19 12:58:01.112  3421  4391 I libsuspend: !@autosuspend_wakeup_count_disable
12-19 12:58:01.112  3421  4391 D PowerManagerService: mDisplayReady: false
12-19 12:58:01.112  3421  4391 I libsuspend: !@autosuspend_wakeup_count_disable done
12-19 12:58:01.112  3421  3574 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-19 12:58:01.112  3010  3010 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fa2c03c00
12-19 12:58:01.112  3421  4391 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
12-19 12:58:01.112  3010  3010 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
12-19 12:58:01.112  3421  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
,12-19 12:58:01.112  3421  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-19 12:58:01.112  3421  3574 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-19 12:58:01.112  3421  3586 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
12-19 12:58:01.112  3421  3570 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
12-19 12:58:01.112  3421  3570 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
,12-19 12:58:01.122  3168  3213 D Sensorhubs: readContextData: 1, 1, 56, 1, 1, 1, 1
12-19 12:58:01.122  3421  3818 D SensorHubManager: onGetSensorHubDataLocked: library(7) = 1, 1, 56, 1, 1, 1, 1
12-19 12:58:01.122  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:58:01.122  3421  3817 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 14, 11, 58, 1,
12-19 12:58:01.122  3421  3817 D SensorHubManager: SendSensorHubData: send data = -63, 14, 11, 58, 1
,12-19 12:58:01.122  4740  4740 D AODUpdatePositionController: updatePosition: direction[7] updatePosition: X[26] Y[220] NewPositionTimer[54]
,12-19 12:58:01.132  4740  4740 D DefaultClockView: LocalTime Pattern : HH:mm
,12-19 12:58:01.132  4740  4740 D TimeViewHolder: onTimeUpdate: timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] isSplitHour:false isSingleView:false isAMPMonLeft:null time01: 12:58 time02: null ampm: null
,12-19 12:58:01.142  3168  3214 D Sensorhubs: sendContextData: -63, 14, 11, 58, 1
12-19 12:58:01.142  3421  3574 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-19 12:58:01.142  3421  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-19 12:58:01.142  3421  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-19 12:58:01.142  3421  3574 I libsuspend: !@autosuspend_wakeup_count_enable
12-19 12:58:01.142  3421  3574 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-19 12:58:01.142  3421  3574 I libsuspend: !@autosuspend_wakeup_count_enable done
12-19 12:58:01.142  3421  3574 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-19 12:58:01.142  3421  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-19 12:58:01.142  3421  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-19 12:58:01.142  3421  3574 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-19 12:58:01.142  3421  3574 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
12-19 12:58:01.142  3421  3574 D PowerManagerService: mDisplayReady: true
12-19 12:58:01.142  3421  3574 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,12-19 12:58:01.142  5854  5854 E CocktailBarPositionManager: Window direction: 0
12-19 12:58:01.142  5854  5854 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,12-19 12:58:01.142  3421  3817 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :7], AP_SLEEP
12-19 12:58:01.152  3421  3817 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 7
,12-19 12:58:01.152  3421  3817 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 56, 1, 1, 1, 1,
,12-19 12:58:01.152  3421  3817 D CAE     : display(ContextProvider.java:375) - ================= DEVICE_PHYSICAL_CONTEXT_MONITOR =================
12-19 12:58:01.152  3421  3817 I CAE     : display(ContextProvider.java:391) - AODReason=[1], AODStatus=[1], DataType=[1]
,12-19 12:58:01.152  3421  3820 D SContextService: updateSContext() : event = Device Physical Context Monitor
,12-19 12:58:01.152  4740  4740 D RoamingTimeViewHolder: isDualClockSetting :: true isHomeTimeZoneExist :: false isEasyUxON :: false Utils.isRoaming(mContext) :: false
,12-19 12:58:01.152  4740  4740 D RoamingTimeViewHolder: getHomeCalendar : No homecity_timezone, set as default :  (libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167])
,12-19 12:58:01.152  4740  4740 D RoamingTimeViewHolder: onTimeUpdate: isVisible:false timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] text:pon., 19 gru 12:58
12-19 12:58:01.152  4740  4740 I AODService.ClockTimer: startAlarm : TICK
,12-19 12:58:01.152  3421  4421 V AlarmManager: Add whitelist package alarm :PendingIntent{aa43763: PendingIntentRecord{3f94b70 com.samsung.android.app.aodservice broadcastIntent}}
,12-19 12:58:01.162  4740  4740 I AlpmModeManager: handleUnblankDisplay: state  = BLANK
,12-19 12:58:01.162  4740  4740 V AlpmModeManager: updateAlpmMode: setDoze [DISPLAY_STATE_DOZE_SUSPEND]
12-19 12:58:01.162  3421  3853 I PowerManagerService: [api] setDozeOverrideFromAod AlpmHlpmSysfs = -1, screenState = 4, Brightness = 0, wakefulness = false
12-19 12:58:01.162  3421  3853 D PowerManagerService: setDozeModeBySysfs:  value is -1 , we ignore it. 
,12-19 12:58:01.162  4740  4740 I AODService: onSContextChanged: AODScreenShown state is already true
12-19 12:58:01.162  4740  4740 D DefaultClockView: RootView invalidate()
12-19 12:58:01.162  3421  4333 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3421
,12-19 12:58:01.302  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:58:01.312  3421  3421 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3421 (0x0)
,12-19 12:58:01.312  3421  3421 I libsuspend: !@autosuspend_wakeup_count_disable
12-19 12:58:01.312  3421  3421 D PowerManagerService: mDisplayReady: false
12-19 12:58:01.312  3421  3421 I libsuspend: !@autosuspend_wakeup_count_disable done
12-19 12:58:01.312  3421  3574 D DisplayPowerController: animateScreenStateChange[0]: target=4
12-19 12:58:01.312  3421  3421 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
,12-19 12:58:01.312  3421  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-19 12:58:01.322  3010  3010 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7fa2c03c00
12-19 12:58:01.312  3421  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-19 12:58:01.322  3010  3010 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
,12-19 12:58:01.312  3421  3574 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-19 12:58:01.312  3421  3586 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
12-19 12:58:01.322  3421  3570 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
,12-19 12:58:01.322  3421  3570 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
,12-19 12:58:01.352  3421  3574 D DisplayPowerController: animateScreenStateChange[0]: target=4
,12-19 12:58:01.352  3421  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-19 12:58:01.352  3421  3574 I libsuspend: !@autosuspend_wakeup_count_enable
12-19 12:58:01.352  3421  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
,12-19 12:58:01.352  3421  3574 I libsuspend: !@autosuspend_wakeup_count_enable done
12-19 12:58:01.352  3421  3574 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-19 12:58:01.352  3421  3574 D DisplayPowerController: animateScreenStateChange[0]: target=4
12-19 12:58:01.352  3421  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-19 12:58:01.352  3421  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-19 12:58:01.352  3421  3574 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-19 12:58:01.352  3421  3574 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
,12-19 12:58:01.352  3421  3574 D PowerManagerService: mDisplayReady: true
12-19 12:58:01.352  3421  3574 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,12-19 12:58:01.372  5854  5854 E CocktailBarPositionManager: Window direction: 0
12-19 12:58:01.372  5854  5854 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,12-19 12:58:01.482  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:58:01.662  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:58:01.842  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:58:02.022  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:58:02.202  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:58:02.382  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:58:02.562  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:58:02.742  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:58:02.922  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:58:03.102  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:58:03.282  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:58:03.462  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:58:03.642  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:58:03.822  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:58:03.902  3421  6185 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-19 12:58:04.002  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:58:04.182  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:58:04.362  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:58:04.542  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:58:04.722  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:58:04.902  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:58:05.082  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:58:05.262  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:58:05.442  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:58:05.622  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:58:05.802  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:58:05.982  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:58:06.162  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:58:06.342  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:58:06.522  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:58:06.702  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:58:06.882  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:58:07.062  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:58:07.242  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:58:07.422  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:58:07.602  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:58:07.782  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:58:07.962  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:58:08.142  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:58:08.162  3421  6150 D SSRM:n  : SIOP:: AP = 290, PST = 290 (W:14), CP = 254, CUR = 214, LCD = 1
,12-19 12:58:08.322  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:58:08.502  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:58:08.682  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:58:08.862  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:58:09.042  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:58:09.092  3421  4570 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,12-19 12:58:09.102  3421  4570 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4350, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 12:58:09.102  3421  4570 D BatteryService: online:4, current avg:214, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:215
12-19 12:58:09.102  3421  4570 D BatteryService: stay LED for charging
12-19 12:58:09.102  3421  3421 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-19 12:58:09.102  3421  3421 I MotionRecognitionService: Plugged
,12-19 12:58:09.102  3421  3421 D MotionRecognitionService:   cableConnection= 1
12-19 12:58:09.102  3421  3421 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-19 12:58:09.102  3421  3421 D MotionRecognitionService: skip setTransmitPower. 
,12-19 12:58:09.112  3421  3861 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-19 12:58:09.112  3938  3938 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-19 12:58:09.112  3938  3938 D KeyguardUpdateMonitor: handleBatteryUpdate
12-19 12:58:09.112  3938  3938 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-19 12:58:09.122  3938  3938 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,12-19 12:58:09.122  3938  3938 D PowerUI.Notification: There is no change about charging status, so return!
,12-19 12:58:09.132  5096  5096 D CommonServiceConfiguration: getStringValueSetting
,12-19 12:58:09.142  5054  5054 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-19 12:58:09.142  5054  5457 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-19 12:58:09.142  5096  5096 D BatteryMonitor: new battery level: 100
,12-19 12:58:09.152  4740  4740 D BatteryController: saveBatteryData : level[100], status[2]
,12-19 12:58:09.162  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,12-19 12:58:09.162  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,12-19 12:58:09.212  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:58:09.402  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:58:09.582  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:58:09.762  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:58:09.942  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:58:10.122  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-19 12:58:10.302  3421  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120

```
