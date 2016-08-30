#### Test 83243049e1001da_thali05_samsung-SM-G935F Logs


```
--------- beginning of main
08-30 12:37:12.609  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:12.679  3431  9475 I HarmonyEASService: Updating for all 1
08-30 12:37:12.779  4167  7724 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg com.google.android.music,id=10436,extra=Bundle[mParcelledData.dataSize=84]
08-30 12:37:12.779  4167  4167 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=10436, samsung.notification.type=normal, samsung.people.package_name=com.google.android.music}]
08-30 12:37:12.779  4167  4167 I PeopleStripeService: PeopleNotificationReceiver:3
08-30 12:37:12.779  4167  4167 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
08-30 12:37:12.779  4167  4167 I PeopleDataManager: removeNotification
08-30 12:37:12.779  4167  4167 I NotificationParser: getNotiType:com.google.android.music,null
08-30 12:37:12.779  4167  4167 D PeopleDataManager: removeNotiInfo: id =10436,packageName=com.google.android.music,isEdgeNotification=false,key=null,removeAll=false
08-30 12:37:12.779  4167  4167 D PeopleDataManager: removeNotiInfo =null
08-30 12:37:12.789  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
08-30 12:37:12.939  9482  9482 D AASAservice-RuleManager: IsSharedUID() : pkgname - com.test.thalitest, mSharedUserId - null
08-30 12:37:12.939  9482  9482 D AASAservice-UpdateReceiver: AASAUpdateReceiver : check SharedUID package.
08-30 12:37:12.939  9482  9482 E AASAservice-UpdateReceiver: AASAUpdateReceiver : myrule is null.
08-30 12:37:12.939  9482  9482 I art     : System.exit called, status: 0
08-30 12:37:12.939  9482  9482 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
--------- beginning of system
08-30 12:37:12.959  3431  3855 I ActivityManager: Process com.samsung.aasaservice (pid 9482)(adj 0) has died(159,1718)
08-30 12:37:12.959  3431  3855 D ActivityManager: isAutoRunBlockedApp:: com.samsung.aasaservice, Auto Run ON
08-30 12:37:12.969  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
08-30 12:37:12.969  3431  3516 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d234ec u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{38d43fb 9018:com.samsung.android.app.appsedge/u0a1}
08-30 12:37:12.969  3431  6545 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-30 12:37:12.969  9018  9018 I AppsEdgeBroadcastReceiver: onReceive: android.intent.action.PACKAGE_ADDED
08-30 12:37:12.979  9535  9535 I FIPS_bssl: FIPS approved mode (1) | 9535 | app_process
08-30 12:37:12.979  9535  9535 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-30 12:37:12.989  9535  9535 D AndroidRuntime: CheckJNI is OFF
08-30 12:37:12.989  9535  9535 D AndroidRuntime: readGMSProperty: start
08-30 12:37:12.989  9535  9535 D AndroidRuntime: readGMSProperty: already setted!!
08-30 12:37:12.989  9535  9535 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-30 12:37:12.989  9535  9535 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-30 12:37:12.989  9535  9535 D AndroidRuntime: readGMSProperty: end
08-30 12:37:12.989  9535  9535 D AndroidRuntime: addProductProperty: start
08-30 12:37:12.989  3431  3982 I ActivityManager: Start proc 9539:com.samsung.android.app.galaxylabs/u0a17 for broadcast-3 com.samsung.android.app.galaxylabs/.LabsIntentReceiver
08-30 12:37:12.999  9539  9539 E Zygote  : v2
08-30 12:37:12.999  9539  9539 I libpersona: KNOX_SDCARD checking this for 10017
08-30 12:37:12.999  9539  9539 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
08-30 12:37:12.999  9539  9539 I libpersona: KNOX_SDCARD not a persona
08-30 12:37:12.999  9539  9539 E Zygote  : accessInfo : 0
08-30 12:37:12.999  9539  9539 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.app.galaxylabs 
08-30 12:37:13.009  9535  9535 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-30 12:37:13.029  9539  9539 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 12:37:13.029  9539  9539 D ActivityThread: Added TimaKeyStore provider
08-30 12:37:13.029  9535  9535 I Radio-JNI: register_android_hardware_Radio DONE
08-30 12:37:13.039  9535  9535 E AffinityControl: AffinityControl: registerfunction enter
08-30 12:37:13.039  9535  9535 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-30 12:37:13.049  3431  4608 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d234ec u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e2c6061 9539:com.samsung.android.app.galaxylabs/u0a17}
08-30 12:37:13.059  9539  9539 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
08-30 12:37:13.059  9539  9539 D RelationGraph: garbageCollect()
08-30 12:37:13.059  9539  9539 W ResourcesManager: getTopLevelResources: /system/priv-app/GalaxyLabs/GalaxyLabs.apk / 1.0 running in com.samsung.android.app.galaxylabs rsrc of package com.samsung.android.app.galaxylabs
08-30 12:37:13.059  3431  4985 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
08-30 12:37:13.059  9539  9539 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
08-30 12:37:13.059  9539  9539 D ResourcesManager: For user 0 new overlays fetched Null
08-30 12:37:13.069  9539  9539 I InjectionManager: Inside getClassLibPath caller 
08-30 12:37:13.069  3431  4208 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
08-30 12:37:13.069  3431  4208 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
08-30 12:37:13.069  9539  9539 W System  : ClassLoader referenced unknown path: /system/priv-app/GalaxyLabs/lib/arm64
08-30 12:37:13.079  3431  4208 D ResourcesManager: For user 0 new overlays fetched Null
08-30 12:37:13.079  3431  4208 D GameManagerService: identifyGamePackage. com.test.thalitest
08-30 12:37:13.079  3431  4208 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
08-30 12:37:13.089  3431  4208 D ActivityManager: mDVFSHelper.acquire()
08-30 12:37:13.099  3005  3005 I SurfaceFlinger: id=16 createSurf (16x16),-1 flag=20004, EimLayer(Di
08-30 12:37:13.099  3005  3005 I SurfaceFlinger: id=17 createSurf (16x16),-1 flag=20004, EimLayer(An
08-30 12:37:13.109  3431  3431 D ViewRootImpl: MSG_RESIZED: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
08-30 12:37:13.109  3431  3431 D ViewRootImpl: MSG_RESIZED: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
08-30 12:37:13.109  3951  3951 D ViewRootImpl: MSG_RESIZED: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
08-30 12:37:13.109  3431  4208 D FocusedStackFrame: Set to : 0
08-30 12:37:13.109  3951  4861 D WallpaperService: resized:[frame]Rect(0, 0 - 2240, 2560) [newConfig] is null
08-30 12:37:13.109  3951  3951 D WallpaperService: MSG_WINDOW_RESIZED
08-30 12:37:13.109  3431  4208 V WindowManager: addAppToken: AppWindowToken{d0b87ba99 token=Token{7dfb7e0 ActivityRecord{665d1e3 u0 com.test.thalitest/.MainActivity t37}}} to stack=2 task=37 at 0
08-30 12:37:13.109  3951  3951 D WallpaperService: updateSurface:[forceRelayout]true[redrawNeeded]false
08-30 12:37:13.109  3951  3951 V WallpaperService: Changes: creating=false format=false size=false
08-30 12:37:13.109  3951  3951 V WallpaperService: currentWidth:2240 currentHeight:2560 requestedWidth:2240 requestedWidth:2560
08-30 12:37:13.119  3951  3951 V WallpaperService: relayout result: Surface(name=null)/@0x30ac6d4, frame=Rect(0, 0 - 2240, 2560),relayoutResult:1, mConfiguration{0 1.0 themeSeq = 0 showBtnBg = -1 ?mcc?mnc pl_PL ?layoutDir ?swdp ?wdp ?hdp ?density ?lsize ?long ?orien ?uimode ?night ?touch ?keyb/?/? ?nav/? mkbd/?}
08-30 12:37:13.119  3951  3951 V WallpaperService: Wallpaper size has changed: (2240, 2560)
08-30 12:37:13.119  3431  3553 I InjectionManager: Inside getClassLibPath caller 
08-30 12:37:13.129  3431  3553 D SecWifiDisplayUtil: Metadata value : SecSettings2
08-30 12:37:13.129  3431  3553 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{23d23d1 V.E...... R.....ID 0,0-0,0}
08-30 12:37:13.129  9558  9558 E Zygote  : v2
08-30 12:37:13.129  9558  9558 I libpersona: KNOX_SDCARD checking this for 10177
08-30 12:37:13.129  9558  9558 I libpersona: KNOX_SDCARD not a persona
08-30 12:37:13.129  9558  9558 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
08-30 12:37:13.139  3431  3553 W WindowManager: Failed looking up window
08-30 12:37:13.139  3431  3553 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@9981e36 does not exist
08-30 12:37:13.139  3431  3553 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
08-30 12:37:13.139  3431  3553 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
08-30 12:37:13.139  3431  3553 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
08-30 12:37:13.139  3431  3553 W WindowManager: 	at android.view.ViewRootImpl.pokeDrawLockIfNeeded(ViewRootImpl.java:1203)
08-30 12:37:13.139  3431  3553 W WindowManager: 	at android.view.ViewRootImpl.scheduleTraversals(ViewRootImpl.java:1415)
08-30 12:37:13.139  3431  3553 W WindowManager: 	at android.view.ViewRootImpl.requestLayout(ViewRootImpl.java:1222)
08-30 12:37:13.139  3431  3553 W WindowManager: 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:800)
08-30 12:37:13.139  3431  3553 W WindowManager: 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:337)
08-30 12:37:13.139  3431  3553 W WindowManager: 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:91)
08-30 12:37:13.139  3431  3553 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4378)
08-30 12:37:13.139  3431  3553 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
08-30 12:37:13.139  3431  3553 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:37:13.139  3431  3553 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
08-30 12:37:13.139  3431  3553 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 12:37:13.139  3431  3553 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-30 12:37:13.139  3431  3553 D ISSUE_DEBUG: InputChannelName : 2bd8137 Starting com.test.thalitest
08-30 12:37:13.139  9558  9558 E Zygote  : accessInfo : 0
08-30 12:37:13.139  9558  9558 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
08-30 12:37:13.139  3431  4208 I ActivityManager: Start proc 9558:com.test.thalitest/u0a177 for activity com.test.thalitest/.MainActivity
08-30 12:37:13.139  3431  4208 D InputDispatcher: Focused application set to: xxxx
08-30 12:37:13.139  9535  9535 D AndroidRuntime: Shutting down VM
08-30 12:37:13.139  3005  3005 I SurfaceFlinger: id=18 createSurf (1x1),1 flag=404, uhalitest
08-30 12:37:13.139  3431  3858 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-30 12:37:13.139  9539  9539 D InjectionManager: InjectionManager
08-30 12:37:13.139  9539  9539 D InjectionManager: fillFeatureStoreMap com.samsung.android.app.galaxylabs
08-30 12:37:13.149  9539  9539 I InjectionManager: Constructor com.samsung.android.app.galaxylabs, Feature store :{}
08-30 12:37:13.149  9539  9539 I InjectionManager: featureStore :{}
08-30 12:37:13.149  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
08-30 12:37:13.149  9539  9539 D LabsIntentReceiver: action: android.intent.action.PACKAGE_ADDED
08-30 12:37:13.149  9539  9539 D LabsIntentReceiver: pkg: com.test.thalitest
08-30 12:37:13.149  9539  9539 D LabsIntentReceiver: context: android.app.ReceiverRestrictedContext@a61305f
08-30 12:37:13.149  9539  9539 D LabsIntentReceiver: extra: false
08-30 12:37:13.149  9539  9539 D LabsLoader: loadByPackageName: deleteDB com.test.thalitest
08-30 12:37:13.169  3431  3553 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
08-30 12:37:13.169  4314  4314 D LauncherApplication: galaxy labs setting changed!!!
08-30 12:37:13.169  9558  9558 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 12:37:13.169  9558  9558 D ActivityThread: Added TimaKeyStore provider
08-30 12:37:13.169  3431  4326 I ActivityManager: Killing 8986:com.google.android.apps.photos/u0a135 (adj 15): DHA:empty #33
08-30 12:37:13.179  3431  4326 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d234ec u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8cd788e 4330:com.google.android.gms.persistent/u0a21}
08-30 12:37:13.219  3431  3553 V WindowStateAnimator: Finishing drawing window Window{2bd8137 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
08-30 12:37:13.219  3431  4985 D ActivityManager:  Launching com.test.thalitest, updated priority
08-30 12:37:13.219  3005  3005 D libEGL  : eglInitialize EGLDisplay = 0x7fdefe6e48
08-30 12:37:13.239  6261  6261 E CocktailBarPositionManager: Window direction: 0
08-30 12:37:13.239  6261  6261 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
08-30 12:37:13.249  3431  3431 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
08-30 12:37:13.249  6261  6272 I TrayUsageStatesWatcher: noteResumeComponent : ComponentInfo{com.test.thalitest/com.test.thalitest.MainActivity} Intent { flg=0x10000000 cmp=com.test.thalitest/.MainActivity VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
08-30 12:37:13.329  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:13.509  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:13.549  6261  6261 I TrayVisibilityController: handleMessage : msg.what = 1
,08-30 12:37:13.569  3431  4985 I WindowManager: Screenshot max retries 4 of Token{7dfb7e0 ActivityRecord{665d1e3 u0 com.test.thalitest/.MainActivity t37}} appWin=Window{2bd8137 u0 d0 Starting com.test.thalitest} drawState=4
,08-30 12:37:13.569  6261  6271 I TrayUsageStatesWatcher: notePauseComponent : ComponentInfo{com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 12:37:13.569  3431  3858 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
,08-30 12:37:13.579  3431  4925 D ActivityManager: isAutoRunBlockedApp:: com.google.android.apps.photos, Auto Run ON
,08-30 12:37:13.589  9558  9558 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,08-30 12:37:13.589  9558  9558 D RelationGraph: garbageCollect()
,08-30 12:37:13.599  9558  9558 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
,08-30 12:37:13.599  3431  4747 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,08-30 12:37:13.599  9558  9558 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,08-30 12:37:13.609  3431  4326 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d234ec u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{753886 4588:com.google.android.gms/u0a21}
08-30 12:37:13.609  3431  3516 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
,08-30 12:37:13.609  6261  6261 I Utils   : isCurrentUser current = 0, ownerId = 0
,08-30 12:37:13.609  3431  6509 D GameManagerService: identifyGamePackage. com.test.thalitest
08-30 12:37:13.609  6261  6261 I TrayVisibilityController: getComputedTrayVisible : keyguardState = 3
08-30 12:37:13.609  6261  6261 I TrayVisibilityController: updateTrayVisible : State : 3 visible = 2 mCurrentVisible = 2
,08-30 12:37:13.619  9558  9558 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:13.619  3005  3014 I SurfaceFlinger: Modify Choreographer's phase offset to 0
,08-30 12:37:13.619  3005  3016 I SurfaceFlinger: Modify SurfaceFlinger's phase offset to 0
08-30 12:37:13.619  3431  6509 D GameManagerService: identifyGamePackage. com.test.thalitest
,08-30 12:37:13.619  3431  6509 D N       : limitCPUFreq:: freq = 2496000
08-30 12:37:13.629  3431  6509 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MAX_LIMIT  frequency : 2496000  uid : 1000  pid : 3431  pkgName : SIOP_ARM_MAX@22
,08-30 12:37:13.629  4314  4314 D LauncherApplication: galaxy labs cursor count is 0
,08-30 12:37:13.639  9558  9558 I InjectionManager: Inside getClassLibPath caller 
,08-30 12:37:13.649  3431  3982 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d234ec u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{753886 4588:com.google.android.gms/u0a21}
,08-30 12:37:13.659  4588  4588 D AsyncTaskServiceImpl: Submit a task: k
,08-30 12:37:13.669  9558  9558 D InjectionManager: InjectionManager
08-30 12:37:13.669  9558  9558 D InjectionManager: fillFeatureStoreMap com.test.thalitest
,08-30 12:37:13.669  4314  4314 V ActivityThread: updateVisibility : ActivityRecord{4dfead5 token=android.os.BinderProxy@3c17947 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
,08-30 12:37:13.669  9558  9558 I InjectionManager: Constructor com.test.thalitest, Feature store :{}
08-30 12:37:13.669  9558  9558 I InjectionManager: featureStore :{}
,08-30 12:37:13.669  4314  4314 D Launcher: onTrimMemory. Level: 20
,08-30 12:37:13.679  3431  6509 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-30 12:37:13.679  9558  9558 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
08-30 12:37:13.679  9558  9558 D RelationGraph: garbageCollect()
08-30 12:37:13.679  3431  6509 D GameManagerService: identifyGamePackage. com.test.thalitest
08-30 12:37:13.679  3431  6509 D N       : limitCPUFreq:: freq = -1
08-30 12:37:13.679  3431  6509 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MAX_LIMIT  frequency : 2496000  uid : 1000  pid : 3431  tag : SIOP_ARM_MAX@22
08-30 12:37:13.679  9558  9558 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
08-30 12:37:13.689  4588  9573 D k       : Processing package: com.test.thalitest
08-30 12:37:13.689  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
08-30 12:37:13.699  3431  4327 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d234ec u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{753886 4588:com.google.android.gms/u0a21}
08-30 12:37:13.699  4588  9573 D GassUtils: Found app info for package com.test.thalitest:19. Hash: 864f03fe3ff04107c0cf32bdae9dc2051eeb22f81b585d28acec96d4114a47f5
08-30 12:37:13.699  4588  9573 D k       : Found info for package com.test.thalitest in db.
08-30 12:37:13.699  3005  4478 D libEGL  : eglTerminate EGLDisplay = 0x7f940ffe78
08-30 12:37:13.699  3005  4478 D libEGL  : eglTerminate EGLDisplay = 0x7f940ffe78
08-30 12:37:13.699  3005  3907 I SurfaceFlinger: id=10 Removed MauncherAct (6/11)
08-30 12:37:13.709  3005  3908 I SurfaceFlinger: id=10 Removed MauncherAct (-2/11)
,08-30 12:37:13.719  3005  3005 D libEGL  : eglTerminate EGLDisplay = 0x7fdefe6f68
,08-30 12:37:13.719  9558  9558 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310550)
,08-30 12:37:13.719  3431  6509 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
08-30 12:37:13.719  3431  6509 D GameManagerService: identifyGamePackage. com.test.thalitest
08-30 12:37:13.729  3431  4326 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d234ec u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{753886 4588:com.google.android.gms/u0a21}
08-30 12:37:13.729  3431  6509 D GameManagerService: identifyGamePackage. com.test.thalitest
,08-30 12:37:13.729  4588  9571 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-30 12:37:13.739  3431  3855 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d234ec u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8cd788e 4330:com.google.android.gms.persistent/u0a21}
,08-30 12:37:13.769  3431  3855 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d234ec u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8cd788e 4330:com.google.android.gms.persistent/u0a21}
,08-30 12:37:13.779  9558  9558 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package com.google.android.webview
,08-30 12:37:13.779  9558  9558 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:13.779  9558  9558 I InjectionManager: Inside getClassLibPath caller 
,08-30 12:37:13.789  9558  9558 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-30 12:37:13.799  9577  9577 E Zygote  : v2
08-30 12:37:13.799  9577  9577 I libpersona: KNOX_SDCARD checking this for 10025
08-30 12:37:13.799  9577  9577 I libpersona: KNOX_SDCARD not a persona
08-30 12:37:13.799  9577  9577 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
08-30 12:37:13.799  9577  9577 E Zygote  : accessInfo : 0
08-30 12:37:13.799  9577  9577 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.partnersetup 
08-30 12:37:13.809  3431  4747 I ActivityManager: Start proc 9577:com.google.android.partnersetup/u0a25 for broadcast-3 com.google.android.partnersetup/.RlzPingBroadcastReceiver
08-30 12:37:13.819  9558  9558 I cr_LibraryLoader: Time to load native libraries: 19 ms (timestamps 2627-2646)
08-30 12:37:13.819  9558  9558 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
08-30 12:37:13.829  3951  3951 V KeyguardUpdateMonitor: onSubscriptionInfoChanged()
08-30 12:37:13.829  9577  9577 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 12:37:13.829  9577  9577 D ActivityThread: Added TimaKeyStore provider
08-30 12:37:13.839  3951  3951 V KeyguardUpdateMonitor: onSubscriptionInfoChanged: list is null
08-30 12:37:13.839  3951  3951 D KeyguardCarrierText: onRefreshCarrierInfo: 
08-30 12:37:13.839  3951  3951 D KeyguardCarrierText: updateAllSlot
08-30 12:37:13.849  3951  3951 D KeyguardCarrierText: updateIntentData(): isMultiSIMState: falsesubId: 2147483643 phoneId:0plmn: Brak sieciSPN: 
08-30 12:37:13.849  3431  4208 D SecContentProvider2: query(), uri = 15 selection = getLockScreenHiddenItems
08-30 12:37:13.849  3951  3951 D KeyguardCarrierText: updateCarrierText(): isMultiSIMState: false
08-30 12:37:13.849  3951  3951 D KeyguardCarrierText: updateDate All slot
08-30 12:37:13.859  3431  3855 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d234ec u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8bacfc5 9577:com.google.android.partnersetup/u0a25}
08-30 12:37:13.859  9558  9592 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
08-30 12:37:13.859  3951  3951 D KeyguardCarrierText: mSimState[0]ABSENT
08-30 12:37:13.859  3951  3951 D KeyguardCarrierText: mSimState[1]ABSENT
08-30 12:37:13.859  3951  3951 D KeyguardCarrierText: Getting plmn/spn sticky brdcst  mPlmn:Brak sieci / mSpn:  phoneId:0 subId:2147483643 showPlmn: true showSpn:false
08-30 12:37:13.859  3951  3951 D KeyguardCarrierText: getStatusForIccState :  SIM state = ABSENT
08-30 12:37:13.869  3951  3951 D KeyguardCarrierText: makeCarrierStringOnEmergencyCapable :  mIsEmergencyCallCapable:  true
08-30 12:37:13.869  3951  3951 D KeyguardCarrierText: concatenate : plmn = Brak karty SIM, spn = Brak sieci
08-30 12:37:13.869  3951  3951 D KeyguardCarrierText: getCarrierTextForSimState :  SIM state = SimMissingcarrierText: Brak karty SIM | Brak sieci
08-30 12:37:13.869  3951  3951 D KeyguardCarrierText: Handling ABSENT , carrierTextForSimState = Brak karty SIM | Brak sieci
08-30 12:37:13.869  4588  9571 D WearableController: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
08-30 12:37:13.869  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
08-30 12:37:13.869  3951  3951 D KeyguardCarrierText: updateCarrierText insertedMultiSim = false
08-30 12:37:13.869  3951  3951 D KeyguardCarrierText: updateCarrierText State: Absent SIM Number = 0
08-30 12:37:13.879  3951  3951 D KeyguardCarrierText: Getting plmn/spn sticky brdcst for Absent case Brak sieci/showPlmn: trueshowSpn: false phoneId:0 subId:2147483643
08-30 12:37:13.879  3951  3951 D KeyguardCarrierText: concatenate : plmn = Brak sieci
08-30 12:37:13.879  3951  3951 D KeyguardCarrierText: makeCarrierStringOnEmergencyCapable :  mIsEmergencyCallCapable:  true
08-30 12:37:13.879  3951  3951 D KeyguardCarrierText: concatenate : plmn = Brak karty SIM, spn = Brak sieci
08-30 12:37:13.879  3951  3951 D KeyguardCarrierText: setText :  displayText = Tryb Offline
08-30 12:37:13.889  9558  9558 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {624d339}
08-30 12:37:13.889  9558  9558 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
08-30 12:37:13.889  3951  3951 D EmergencyButton: onRefreshCarrierInfo
08-30 12:37:13.909  9558  9558 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 12:37:13.909  3431  3881 D MdnieScenarioControlService:  packageName : com.test.thalitest    className : com.test.thalitest.MainActivity
08-30 12:37:13.919  9577  9577 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
08-30 12:37:13.919  9577  9577 D RelationGraph: garbageCollect()
08-30 12:37:13.939  9577  9577 W ResourcesManager: getTopLevelResources: /system/priv-app/GooglePartnerSetup/GooglePartnerSetup.apk / 1.0 running in com.google.android.partnersetup rsrc of package com.google.android.partnersetup
08-30 12:37:13.939  9558  9558 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
08-30 12:37:13.949  3431  4608 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
08-30 12:37:13.949  9577  9577 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
08-30 12:37:13.959  9577  9577 D ResourcesManager: For user 0 new overlays fetched Null
08-30 12:37:13.969  9577  9577 I InjectionManager: Inside getClassLibPath caller 
08-30 12:37:13.969  3431  4747 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-30 12:37:13.969  3431  4747 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
08-30 12:37:13.969  3431  4747 D BatteryService: online:4, current avg:-135, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:130
08-30 12:37:13.969  3431  4747 D BatteryService: stay LED for fully charged
08-30 12:37:13.969  9577  9577 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePartnerSetup/lib/arm64
08-30 12:37:13.969  3431  3431 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-30 12:37:13.979  3431  3431 I MotionRecognitionService: Plugged
08-30 12:37:13.979  3431  3431 D MotionRecognitionService:   cableConnection= 1
08-30 12:37:13.979  3431  3431 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-30 12:37:13.979  3431  3431 D MotionRecognitionService: skip setTransmitPower. 
08-30 12:37:13.989  3431  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
08-30 12:37:13.989  3951  3951 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-30 12:37:13.989  3951  3951 D PowerUI : priorPlugType = 2 mPlugType =  2
08-30 12:37:13.989  3951  3951 D KeyguardUpdateMonitor: handleBatteryUpdate
08-30 12:37:13.999  5090  5090 D CommonServiceConfiguration: getStringValueSetting
08-30 12:37:13.999  5049  5049 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-30 12:37:13.999  5049  5438 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-30 12:37:13.999  5090  5090 D BatteryMonitor: new battery level: 100
08-30 12:37:13.999  4766  4766 D BatteryController: saveBatteryData : level[100], status[5]
08-30 12:37:14.009  9577  9577 D InjectionManager: InjectionManager
08-30 12:37:14.009  3431  3881 I MdnieScenarioControlService: mGameModeLauncher : false
08-30 12:37:14.009  9577  9577 D InjectionManager: fillFeatureStoreMap com.google.android.partnersetup
08-30 12:37:14.009  3431  3881 I MdnieScenarioControlService: setUIMode
08-30 12:37:14.009  9577  9577 I InjectionManager: Constructor com.google.android.partnersetup, Feature store :{}
08-30 12:37:14.009  9577  9577 I InjectionManager: featureStore :{}
08-30 12:37:14.019  3951  3951 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-30 12:37:14.019  3951  3951 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-30 12:37:14.039  3431  3982 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d234ec u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8bacfc5 9577:com.google.android.partnersetup/u0a25}
08-30 12:37:14.049  4588  9575 I PeopleContactsSync: triggerPendingContactsCleanup: no accounts
08-30 12:37:14.049  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
08-30 12:37:14.049  3431  3982 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity newState = 1 callingPackage = 10021
08-30 12:37:14.059  3431  3516 W ActivityManager: Activity pause timeout for ActivityRecord{665d1e3 u0 com.test.thalitest/.MainActivity t37}
08-30 12:37:14.069  3431  4399 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d234ec u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9608c56 9034:com.android.vending/u0a35}
08-30 12:37:14.069  4167  7724 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg com.android.vending,id=1003285959,extra=Bundle[mParcelledData.dataSize=84]
08-30 12:37:14.069  4167  4167 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=1003285959, samsung.notification.type=normal, samsung.people.package_name=com.android.vending}]
08-30 12:37:14.069  4167  4167 I PeopleStripeService: PeopleNotificationReceiver:3
08-30 12:37:14.069  4167  4167 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
08-30 12:37:14.069  4167  4167 I PeopleDataManager: removeNotification
08-30 12:37:14.069  4167  4167 I NotificationParser: getNotiType:com.android.vending,null
08-30 12:37:14.069  4167  4167 D PeopleDataManager: removeNotiInfo: id =1003285959,packageName=com.android.vending,isEdgeNotification=false,key=null,removeAll=false
08-30 12:37:14.069  4167  4167 D PeopleDataManager: removeNotiInfo =null
08-30 12:37:14.079  9558  9558 D libEGL  : eglInitialize EGLDisplay = 0xffc5c10c
08-30 12:37:14.109  4588  9575 I PeopleDatabaseHelper: cleanUpNonGplusAccounts done.
08-30 12:37:14.129  9034  9034 I Finsky  : [1] com.google.android.finsky.utils.PermissionPolicies$PermissionPolicyService.onStartCommand(117): post-install permissions check for com.test.thalitest
08-30 12:37:14.139  9034  9034 W Finsky  : [1] com.google.android.finsky.FinskyApp.i(1379): No account configured on this device.
08-30 12:37:14.139  3431  4326 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d234ec u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{defbca3 8449:com.sec.android.app.shealth:remote/u0a39}
08-30 12:37:14.149  3431  4327 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10177
08-30 12:37:14.149  3431  4327 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29734 com.android.server.am.ActivityManagerService.registerReceiver:22599 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
08-30 12:37:14.159  9034  9034 I Finsky  : [1] com.google.android.finsky.utils.bc.run(2302): Package state data is missing for com.test.thalitest
08-30 12:37:14.159  9034  9034 W Finsky  : [1] com.google.android.finsky.FinskyApp.i(1379): No account configured on this device.
08-30 12:37:14.169  9631  9631 E Zygote  : v2
08-30 12:37:14.169  9631  9631 I libpersona: KNOX_SDCARD checking this for 10043
08-30 12:37:14.169  9631  9631 I libpersona: KNOX_SDCARD not a persona
08-30 12:37:14.169  9631  9631 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
08-30 12:37:14.169  9631  9631 E Zygote  : accessInfo : 0
08-30 12:37:14.169  9631  9631 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.voiceserviceplatform 
08-30 12:37:14.169  3431  4747 I ActivityManager: Start proc 9631:com.samsung.voiceserviceplatform/u0a43 for broadcast-3 com.samsung.voiceserviceplatform/com.samsung.vsf.sharedlib.utils.TTSPlayer$TTSDownloadReceiver
08-30 12:37:14.189  4588  9575 I PeopleContactsSync: triggerPendingContactsCleanup: no accounts
08-30 12:37:14.199  9631  9631 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 12:37:14.199  9631  9631 D ActivityThread: Added TimaKeyStore provider
08-30 12:37:14.219  3431  4470 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d234ec u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9d7b2e9 9631:com.samsung.voiceserviceplatform/u0a43}
08-30 12:37:14.229  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
08-30 12:37:14.229  9558  9558 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
08-30 12:37:14.229  9631  9631 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
08-30 12:37:14.229  9631  9631 D RelationGraph: garbageCollect()
08-30 12:37:14.229  9631  9631 W ResourcesManager: getTopLevelResources: /system/priv-app/SVoice_1.0/SVoice_1.0.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.samsung.voiceserviceplatform
08-30 12:37:14.229  3431  4747 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
08-30 12:37:14.229  9631  9631 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
08-30 12:37:14.239  9631  9631 D ResourcesManager: For user 0 new overlays fetched Null
08-30 12:37:14.239  9631  9631 I InjectionManager: Inside getClassLibPath caller 
08-30 12:37:14.249  9558  9558 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
08-30 12:37:14.249  9558  9558 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
08-30 12:37:14.259  9558  9558 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
08-30 12:37:14.299  9558  9558 D Activity: performCreate Call Injection manager
08-30 12:37:14.299  9558  9558 I InjectionManager: dispatchOnViewCreated > Target : com.test.thalitest.MainActivity isFragment :false
08-30 12:37:14.309  9558  9558 D SecWifiDisplayUtil: Metadata value : SecSettings2
08-30 12:37:14.309  9558  9558 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{a115cbf I.E...... R.....ID 0,0-0,0}
08-30 12:37:14.309  9558  9648 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
08-30 12:37:14.319  3431  4326 W WindowManager: Failed looking up window
08-30 12:37:14.319  3431  4326 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@38044a0 does not exist
08-30 12:37:14.319  3431  4326 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
08-30 12:37:14.319  3431  4326 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
08-30 12:37:14.319  3431  4326 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
08-30 12:37:14.319  3431  4326 W WindowManager: 	at android.view.IWindowSession$Stub.onTransact(IWindowSession.java:688)
08-30 12:37:14.319  3431  4326 W WindowManager: 	at com.android.server.wm.Session.onTransact(Session.java:139)
08-30 12:37:14.319  3431  4326 W WindowManager: 	at android.os.Binder.execTransact(Binder.java:453)
08-30 12:37:14.319  3431  3451 D ISSUE_DEBUG: InputChannelName : 6462859 com.test.thalitest/com.test.thalitest.MainActivity
08-30 12:37:14.319  3431  4470 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
08-30 12:37:14.319  3431  4470 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-30 12:37:14.319  3431  3431 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-30 12:37:14.329  3431  3431 I KnoxTimeoutHandler: Shared devices show user statefalse
08-30 12:37:14.329  9558  9558 V ActivityThread: updateVisibility : ActivityRecord{5a406d5 token=android.os.BinderProxy@68ced94 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-30 12:37:14.339  9631  9631 I BNRClientProivder, VERSION : 1.7.8: register - started.
08-30 12:37:14.339  9558  9592 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
08-30 12:37:14.359  9558  9558 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10177, CallingPid : 9558
08-30 12:37:14.369  3431  4208 D ConnectivityService: listenForNetwork for Listen from uid/pid:10177/9558 for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:37:14.369  3431  3869 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
08-30 12:37:14.369  3431  3869 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-30 12:37:14.369  3431  3858 D NetworkPolicy: isUidForegroundLocked: 10021, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
08-30 12:37:14.369  3431  3858 D NetworkPolicy: isUidForegroundLocked: 10021, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
08-30 12:37:14.379  3431  3869 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
08-30 12:37:14.379  3431  4327 I ActivityManager: Killing 9112:com.samsung.android.app.taskedge/u0a67 (adj 15): DHA:empty #33
08-30 12:37:14.379  3431  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-30 12:37:14.389  3431  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-30 12:37:14.389  9558  9558 D SecWifiDisplayUtil: Metadata value : SecSettings2
08-30 12:37:14.399  3431  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
08-30 12:37:14.409  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
08-30 12:37:14.409  3431  3450 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.taskedge, Auto Run ON
08-30 12:37:14.409  3431  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-30 12:37:14.419  3005  3005 I SurfaceFlinger: id=19 createSurf (1x1),1 flag=404, NainActivit
08-30 12:37:14.429  3431  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
08-30 12:37:14.429  3431  3869 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:37:14.449  9558  9648 D libEGL  : eglInitialize EGLDisplay = 0xdbfff7c4
08-30 12:37:14.449  9558  9648 I OpenGLRenderer: Initialized EGL, version 1.4
08-30 12:37:14.459  9558  9648 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
08-30 12:37:14.459  3431  4925 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3431
08-30 12:37:14.459  3431  4925 I libsuspend: !@autosuspend_wakeup_count_disable
08-30 12:37:14.459  3431  4925 D PowerManagerService: mDisplayReady: false
08-30 12:37:14.459  3431  4925 I libsuspend: !@autosuspend_wakeup_count_disable done
08-30 12:37:14.459  3431  3561 D DisplayPowerController: animateScreenStateChange[0]: target=3
08-30 12:37:14.459  3431  4925 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
08-30 12:37:14.459  3431  3561 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
08-30 12:37:14.459  3431  3561 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
08-30 12:37:14.459  3431  3561 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
08-30 12:37:14.459  3431  3574 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
08-30 12:37:14.459  3431  3553 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
08-30 12:37:14.459  3431  3553 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
08-30 12:37:14.469  3005  3005 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7f9c2c3c00
08-30 12:37:14.469  3005  3005 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
08-30 12:37:14.469  9631  9631 I BNRClientProivder, VERSION : 1.7.8: register - xml6 quick_backup : SVOICESETTING, bLEmzxKOex, com.samsung.voiceserviceplatform.SCloudBackUp
08-30 12:37:14.479  9631  9631 I QBNRClientHelper: init SyncClientHelper : SVOICESETTING
08-30 12:37:14.479  3431  3561 D DisplayPowerController: animateScreenStateChange[0]: target=3
08-30 12:37:14.479  3431  3561 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
08-30 12:37:14.479  3431  3561 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
08-30 12:37:14.479  3431  3561 I libsuspend: !@autosuspend_wakeup_count_enable
08-30 12:37:14.479  3431  3561 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
08-30 12:37:14.479  3431  3561 D DisplayPowerController: animateScreenStateChange[0]: target=3
08-30 12:37:14.489  3431  3561 I libsuspend: !@autosuspend_wakeup_count_enable done
08-30 12:37:14.479  3431  3561 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
08-30 12:37:14.479  3431  3561 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
08-30 12:37:14.479  3431  3561 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
08-30 12:37:14.479  3431  3561 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
08-30 12:37:14.479  3431  3561 D PowerManagerService: mDisplayReady: true
08-30 12:37:14.489  3431  3561 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
08-30 12:37:14.489  6261  6261 E CocktailBarPositionManager: Window direction: 0
08-30 12:37:14.489  6261  6261 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
08-30 12:37:14.499  9558  9558 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
08-30 12:37:14.499  9631  9631 I l       : :main:VSP::S Voice language is null. Set to System Locale
08-30 12:37:14.499  9631  9631 I l       : :main:VSP::setLocale locale : pl_PL
08-30 12:37:14.499  9631  9631 W ResourcesManager: getTopLevelResources: /system/priv-app/SVoice_1.0/SVoice_1.0.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.samsung.voiceserviceplatform
08-30 12:37:14.499  9631  9631 D ResourcesManager: For user 0 new overlays fetched Null
08-30 12:37:14.499  9631  9631 I QuickDialApplication: :main:VSP::QuickDialApplication Started ver:1.9.35-130 (193502130
08-30 12:37:14.509  9631  9631 I VoiceServicePlatformApp:main:  : VSP::SvoiceApp Oncreate()
08-30 12:37:14.509  3431  4208 V WindowStateAnimator: Finishing drawing window Window{6462859 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
08-30 12:37:14.509  9558  9558 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
08-30 12:37:14.519  9631  9631 I AppSessionManager:main:  : VSP::init() Update from sharedpref
08-30 12:37:14.519  9631  9631 I AppSessionManager:main:  : VSP::init() Update from sharedpref
08-30 12:37:14.529  3431  4608 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3431
08-30 12:37:14.529  3431  3553 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-30 12:37:14.529  3431  3431 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-30 12:37:14.529  3431  4650 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3431
08-30 12:37:14.529  3431  3553 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +966ms (total +1s413ms)
08-30 12:37:14.529  3431  3553 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{665d1e3 u0 com.test.thalitest/.MainActivity t37} time:73355
08-30 12:37:14.529  3431  3553 D ActivityManager: mDVFSHelper.release()
08-30 12:37:14.529  3431  3553 D ViewRootImpl: #3 mView = null
08-30 12:37:14.529  3005  3908 I SurfaceFlinger: id=18 Removed uhalitest (6/11)
08-30 12:37:14.529  3431  4151 E Watchdog: !@Sync 2 [08-30 12:37:14.544]
08-30 12:37:14.529  3431  3431 I KnoxTimeoutHandler: SD activityfalse
08-30 12:37:14.529  3005  4478 I SurfaceFlinger: id=18 Removed uhalitest (-2/11)
08-30 12:37:14.539  3431  4208 V WindowStateAnimator: Finishing drawing window Window{6462859 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
08-30 12:37:14.539  9558  9654 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 12:37:14.539  9558  9654 D libEGL  : eglInitialize EGLDisplay = 0xda47f3f4
08-30 12:37:14.549  9558  9558 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@68ced94 time:73370
08-30 12:37:14.549  3005  3005 D libEGL  : eglTerminate EGLDisplay = 0x7fdefe6f68
08-30 12:37:14.549  9657  9657 E Zygote  : v2
08-30 12:37:14.549  9657  9657 I libpersona: KNOX_SDCARD checking this for 10043
08-30 12:37:14.549  9657  9657 I libpersona: KNOX_SDCARD not a persona
08-30 12:37:14.559  9657  9657 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
08-30 12:37:14.559  3431  4747 I ActivityManager: Start proc 9657:com.samsung.svoice.sync/u0a43 for content provider com.samsung.svoice.sync/com.svoice.upload.database.PLMProvider
08-30 12:37:14.569  9657  9657 E Zygote  : accessInfo : 0
08-30 12:37:14.569  9657  9657 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.svoice.sync 
08-30 12:37:14.569  9558  9654 D libGLESv2: DTS_GLAPI : DTS is not allowed for Package : com.test.thalitest
08-30 12:37:14.589  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
08-30 12:37:14.589  9657  9657 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 12:37:14.589  9657  9657 D ActivityThread: Added TimaKeyStore provider
08-30 12:37:14.609  9558  9558 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9558
08-30 12:37:14.609  9657  9657 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
08-30 12:37:14.609  9657  9657 D RelationGraph: garbageCollect()
08-30 12:37:14.609  9657  9657 W ResourcesManager: getTopLevelResources: /system/priv-app/SVoicePLM_1.0/SVoicePLM_1.0.apk / 1.0 running in com.samsung.svoice.sync rsrc of package com.samsung.svoice.sync
08-30 12:37:14.609  3431  4208 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
08-30 12:37:14.609  9657  9657 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
08-30 12:37:14.619  9657  9657 D ResourcesManager: For user 0 new overlays fetched Null
08-30 12:37:14.619  9657  9657 I InjectionManager: Inside getClassLibPath caller 
,08-30 12:37:14.629  9657  9657 I UploadDatabase: svoicelocal DB: main : PLM :: mUploadDBManager is null , creating new one !! 
,08-30 12:37:14.629  3431  6511 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
,08-30 12:37:14.639  9657  9657 E SQLiteLog: (5) statement aborts at 2: [PRAGMA journal_mode=PERSIST] 
,08-30 12:37:14.639  9657  9657 W SQLiteConnection: Could not change the database journal mode of '/data/user/0/com.samsung.svoice.sync/databases/svoicelocal.db' from 'wal' to 'PERSIST' because the database is locked.  This usually means that there are other open connections to the database which prevents the database from enabling or disabling write-ahead logging mode.  Proceeding without changing the journal mode.
,08-30 12:37:14.639  9657  9657 D InjectionManager: InjectionManager
,08-30 12:37:14.639  9657  9657 D InjectionManager: fillFeatureStoreMap com.samsung.svoice.sync
,08-30 12:37:14.639  9657  9657 I InjectionManager: Constructor com.samsung.svoice.sync, Feature store :{}
,08-30 12:37:14.639  9657  9657 I InjectionManager: featureStore :{}
08-30 12:37:14.639  9657  9668 D PLMProvider: match for uri : content://com.samsung.svoice.sync/tos_accepted is : 8
,08-30 12:37:14.649  9631  9631 I SVFSettings:main:  : VSP::inside updateAppLocale() en_US
,08-30 12:37:14.659  9631  9631 I SVFSettings:main:  : VSP::Current locale string in updateAppLocale method en-US
,08-30 12:37:14.659  9631  9631 I SVFSettings:main:  : VSP::After updateing N66_ComamndHandler current locale is en-US
,08-30 12:37:14.669  9631  9631 D DeviceInfo: DeviceInfo
,08-30 12:37:14.669  9631  9631 D DeviceInfo: getLocale =  en-US
08-30 12:37:14.669  9631  9631 I N66_CommonHandler:main:  : VSP:: locale info at present in updateServerBasedOnlanguage : en-US
08-30 12:37:14.669  9631  9631 I N66_CommonHandler:main:  : VSP::Current configured server is interaction-us2.samsung-svoice.com
08-30 12:37:14.669  9631  9631 I N66_CommonHandler:main:  : VSP::Current configured server port is 443
,08-30 12:37:14.679  3431  3431 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3431 (0x0)
08-30 12:37:14.679  3431  3431 I libsuspend: !@autosuspend_wakeup_count_disable
08-30 12:37:14.679  3431  3431 D PowerManagerService: mDisplayReady: false
08-30 12:37:14.679  3431  3431 I libsuspend: !@autosuspend_wakeup_count_disable done
08-30 12:37:14.679  3431  3561 D DisplayPowerController: animateScreenStateChange[0]: target=4
08-30 12:37:14.679  3431  3561 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
08-30 12:37:14.679  3431  3431 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
08-30 12:37:14.679  3431  3561 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
08-30 12:37:14.679  3431  3561 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
08-30 12:37:14.679  3431  3574 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
08-30 12:37:14.679  3005  3005 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7f9c2c3c00
08-30 12:37:14.679  3431  3553 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
08-30 12:37:14.679  3005  3005 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
08-30 12:37:14.679  3431  3553 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
,08-30 12:37:14.679  9631  9631 D SettingsValueDB:main:  : VSP:: match for uri : content://com.samsung.voiceserviceplatform.database.SettingsValueDB/SettingsvalueTb is : -1
,08-30 12:37:14.679  9631  9631 D SettingsValueDB:main:  : VSP::URI didnt match
,08-30 12:37:14.689  3431  3561 D DisplayPowerController: animateScreenStateChange[0]: target=4
08-30 12:37:14.689  3431  3561 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
08-30 12:37:14.689  3431  3561 I libsuspend: !@autosuspend_wakeup_count_enable
08-30 12:37:14.689  3431  3561 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
08-30 12:37:14.689  3431  3561 I libsuspend: !@autosuspend_wakeup_count_enable done
08-30 12:37:14.689  3431  3561 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
08-30 12:37:14.689  3431  3561 D DisplayPowerController: animateScreenStateChange[0]: target=4
08-30 12:37:14.689  3431  3561 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
08-30 12:37:14.689  3431  3561 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
08-30 12:37:14.689  3431  3561 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
08-30 12:37:14.689  3431  3561 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
08-30 12:37:14.689  3431  3561 D PowerManagerService: mDisplayReady: true
08-30 12:37:14.689  3431  3561 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,08-30 12:37:14.699  6261  6261 E CocktailBarPositionManager: Window direction: 0
08-30 12:37:14.699  9631  9631 D SettingsValueDB:main:  : VSP:: match for uri : content://com.samsung.voiceserviceplatform.database.SettingsValueDB/SettingsvalueTb is : -1
08-30 12:37:14.699  9631  9631 D SettingsValueDB:main:  : VSP::URI didnt match
08-30 12:37:14.699  6261  6261 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,08-30 12:37:14.699  9631  9631 D SettingsValueDB:main:  : VSP:: match for uri : content://com.samsung.voiceserviceplatform.database.SettingsValueDB/language is : 3
08-30 12:37:14.699  9631  9631 D SettingsValueDB:main:  : VSP::lang from content values is  en_US
08-30 12:37:14.699  9631  9631 I skwskw:main:  : VSP::############################122 value : en_US
,08-30 12:37:14.699  9558  9558 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-30 12:37:14.699  9657  9668 D PLMProvider: match for uri : content://com.samsung.svoice.sync/tos_accepted is : 8
,08-30 12:37:14.699  9631  9631 I N66_CommonHandler:main:  : VSP:: rowUpdated : 1
,08-30 12:37:14.709  9631  9631 D SVFSettings: updateServerBasedOnLang() connect to server US_PROD2_SERVER_HOST_IP
,08-30 12:37:14.709  9631  9631 D p       : :main:VSP::setTargetServerAddress() : interaction-us2.samsung-svoice.com
08-30 12:37:14.709  9631  9631 D p       : :main:VSP::setTargetServerPort() : 443
,08-30 12:37:14.729  9631  9631 W ResourcesManager: getTopLevelResources: /system/app/SamsungTTS/SamsungTTS.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.samsung.SMT
,08-30 12:37:14.739  9631  9631 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:14.739  9631  9631 W ResourcesManager: getTopLevelResources: /system/app/GoogleTTS/GoogleTTS.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.tts
,08-30 12:37:14.739  3431  6509 D SSRM:n  : SIOP:: AP = 440, PST = 457 (W:7), CP = 315, CUR = -135, LCD = 1
08-30 12:37:14.739  3431  6509 D N       : broadcastSiopLevelIntent:: currentSiopLevel = 0
08-30 12:37:14.739  9631  9631 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:14.739  4876  4876 D ContentApp:  LEVEL : 0
,08-30 12:37:14.739  8585  8604 I SystemBroadcastReceiver: [#CMH#] Received broadcast 
08-30 12:37:14.739  8585  8604 I PolicyManager: [#CMH#] onReceive action = EVENT_SIOP
08-30 12:37:14.739  8585  8604 I SystemBroadcastReceiver: [#CMH#] onReceive completed 
,08-30 12:37:14.759  9676  9676 E Zygote  : v2
08-30 12:37:14.759  9676  9676 I libpersona: KNOX_SDCARD checking this for 1000
08-30 12:37:14.759  9676  9676 I libpersona: KNOX_SDCARD not a persona
,08-30 12:37:14.759  9676  9676 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,08-30 12:37:14.759  3431  3982 I ActivityManager: Start proc 9676:com.samsung.SMT/1000 for service com.samsung.SMT/.SamsungTTSService
,08-30 12:37:14.759  9676  9676 E Zygote  : accessInfo : 0
,08-30 12:37:14.759  9631  9631 I TextToSpeech: Sucessfully bound to com.samsung.SMT
08-30 12:37:14.759  9631  9631 D Test    : Creating TTS instance!
,08-30 12:37:14.759  3431  6509 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-30 12:37:14.769  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:14.769  9631  9631 I SamsungHTTPClient:main:  : VSP::MY THREAD ID UI : 1
,08-30 12:37:14.779  9657  9668 D PLMProvider: match for uri : content://com.samsung.svoice.sync/device_id is : 1
,08-30 12:37:14.779  9657  9668 D PLMDeviceInfo: Binder_2 : PLM ::Device Id generation is complete
,08-30 12:37:14.789  9631  9631 I svoiceapi_jar: RELEASE_DATE 2016 May 25
08-30 12:37:14.789  9631  9631 I svoiceapi_jar: RELEASE_VER  0.99_26_1_TCP_Prepare2_TTS
08-30 12:37:14.789  9631  9631 I svoiceapi_jar: Loading svoice dll
,08-30 12:37:14.799  9676  9676 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 12:37:14.799  9676  9676 D ActivityThread: Added TimaKeyStore provider
,08-30 12:37:14.819  9631  9631 I svoiceapi_jar: Loading success
,08-30 12:37:14.819  9676  9676 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,08-30 12:37:14.819  9676  9676 D RelationGraph: garbageCollect()
,08-30 12:37:14.819  9676  9676 W ResourcesManager: getTopLevelResources: /system/app/SamsungTTS/SamsungTTS.apk / 1.0 running in com.samsung.SMT rsrc of package com.samsung.SMT
,08-30 12:37:14.819  9676  9676 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
08-30 12:37:14.819  3431  4399 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,08-30 12:37:14.829  9676  9676 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:14.829  9631  9631 I svoiceapi: SVoiceSession Release Date : 2016 May 25
08-30 12:37:14.829  9631  9631 I svoiceapi: Library Ver : 0.99_26_1_TCP_Prepare2_TTS
08-30 12:37:14.829  9631  9631 I svoiceapi: SVoiceSession::SVoiceSession, Default loglevel = 5
08-30 12:37:14.829  9631  9631 I svoiceapi: create handle : 0xf4872bc0
,08-30 12:37:14.829  9631  9631 I svoiceapi: Sentinel registered : -197488176
08-30 12:37:14.829  9631  9631 I svoiceapi: SVoiceSession::Enable logs, loglevel = 4
08-30 12:37:14.829  9631  9631 I sessionThread:main:  : VSP::LOG_LEVEL is set as 4
,08-30 12:37:14.829  9676  9676 I InjectionManager: Inside getClassLibPath caller 
08-30 12:37:14.829  9631  9631 D ClientSDKManager : initNLUResponseList
08-30 12:37:14.829  9631  9631 D InjectionManager: InjectionManager
08-30 12:37:14.829  9631  9631 D InjectionManager: fillFeatureStoreMap com.samsung.voiceserviceplatform
08-30 12:37:14.829  9631  9631 I InjectionManager: Constructor com.samsung.voiceserviceplatform, Feature store :{}
08-30 12:37:14.829  9631  9631 I InjectionManager: featureStore :{}
08-30 12:37:14.829  9631  9693 I sessionThread: DEBUG : SDK : Session Thread run got called : 
08-30 12:37:14.829  9631  9631 I SV_TTSPlayer: inside TTSDownloadReceiver
08-30 12:37:14.829  9631  9693 I sessionThread:SessionThread:  : VSP::Inside processTask while loop; task is empty so sleeping : 
08-30 12:37:14.839  9676  9676 W System  : ClassLoader referenced unknown path: /system/app/SamsungTTS/lib/arm64
08-30 12:37:14.839  9676  9676 D InjectionManager: InjectionManager
08-30 12:37:14.839  9676  9676 D InjectionManager: fillFeatureStoreMap com.samsung.SMT
,08-30 12:37:14.839  9676  9676 I InjectionManager: Constructor com.samsung.SMT, Feature store :{}
08-30 12:37:14.839  9676  9676 I InjectionManager: featureStore :{}
,08-30 12:37:14.839  9631  9631 I VoiceFrameworkService:main:  : VSP::Oncreate() of Service
,08-30 12:37:14.839  9631  9631 I VoiceFrameworkServiceHandler:main:  : VSP::VoiceFrameworkServiceHandler() Start
,08-30 12:37:14.849  9631  9631 I VoiceFrameworkServiceHandler:main:  : VSP::MyHandlerThread
08-30 12:37:14.849  9631  9631 I VoiceFrameworkServiceHandler:main:  : VSP::VoiceFrameworkServiceHandler() end
,08-30 12:37:14.849  3431  3855 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d234ec u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f21855a 4428:android.process.acore/u0a5}
08-30 12:37:14.849  9631  9695 I VoiceFrameworkServiceHandler:VoiceFrameworkServiceHandler MyHandlerThread:  : VSP::MyHandlerThread run
,08-30 12:37:14.849  9631  9631 I VoiceFrameworkServiceHandler:main:  : VSP::sendMessagetoHandler Rcvd msgCode = 0
08-30 12:37:14.849  9631  9631 I VoiceFrameworkServiceHandler:main:  : VSP::sendMessagetoHandler mHandler = Handler (com.samsung.vsf.core.framework.VoiceFrameworkServiceHandler$MyHandlerThread$1) {c1902df}
08-30 12:37:14.849  9631  9631 I VoiceFrameworkServiceHandler:main:  : VSP:: sendMessagetoHandler() VSF Thread isAlive : true
08-30 12:37:14.849  9631  9631 I VoiceFrameworkServiceHandler:main:  : VSP::mHandler is not null msgCode =0
,08-30 12:37:14.849  9631  9695 I VoiceFrameworkServiceHandler:VoiceFrameworkServiceHandler MyHandlerThread:  : VSP::MSG_VSF_INIT Rcvd
08-30 12:37:14.849  9631  9695 I VoiceFrameworkServiceHandler:VoiceFrameworkServiceHandler MyHandlerThread:  : VSP::VSFInit()
,08-30 12:37:14.859  9631  9695 I VoiceServicePlatformSdk:VoiceFrameworkServiceHandler MyHandlerThread:  : VSP::Oncreate()
,08-30 12:37:14.869  9631  9695 I SessionRuntime:VoiceFrameworkServiceHandler MyHandlerThread:  : VSP::Current Network State is same as previous, so ignoring
,08-30 12:37:14.869  3431  3450 I ActivityManager: Start proc 9698:com.android.settings/1000 for broadcast-3 com.android.settings/.applock.PackageActionReceiver
08-30 12:37:14.869  9698  9698 E Zygote  : v2
08-30 12:37:14.869  9698  9698 I libpersona: KNOX_SDCARD checking this for 1000
08-30 12:37:14.869  9698  9698 I libpersona: KNOX_SDCARD not a persona
,08-30 12:37:14.869  9698  9698 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,08-30 12:37:14.869  9698  9698 E Zygote  : accessInfo : 0
,08-30 12:37:14.869  9631  9695 I System.out: SVoiceProfiling : time taken to finish oncreate : 20
,08-30 12:37:14.899  9657  9667 D PLMProvider: match for uri : content://com.samsung.svoice.sync/tos_accepted is : 8
,08-30 12:37:14.899  9558  9694 D jxcore_app_log: JniHelper::setJavaVM(0xf48f4000), pthread_self() = -641730256
08-30 12:37:14.899  9631  9695 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'void android.location.LocationManager.requestLocationUpdates(long, float, android.location.Criteria, android.location.LocationListener, android.os.Looper)' on a null object reference
,08-30 12:37:14.899  9631  9695 W System.err: 	at com.samsung.vsf.core.framework.SessionRuntime.requestLocationUpdate(SessionRuntime.java:336)
08-30 12:37:14.899  9631  9695 W System.err: 	at com.samsung.vsf.core.framework.SessionRuntime.registerNetworkReceiver(SessionRuntime.java:246)
08-30 12:37:14.899  9631  9695 W System.err: 	at com.samsung.vsf.core.framework.SessionRuntime.registerBroadcastReceivers(SessionRuntime.java:115)
08-30 12:37:14.899  9631  9695 W System.err: 	at com.samsung.vsf.core.framework.SessionRuntime.init(SessionRuntime.java:103)
08-30 12:37:14.899  9631  9695 W System.err: 	at com.samsung.vsf.core.framework.VoiceFrameworkServiceHandler.VSFInit(VoiceFrameworkServiceHandler.java:188)
08-30 12:37:14.899  9631  9695 W System.err: 	at com.samsung.vsf.core.framework.VoiceFrameworkServiceHandler.access$200(VoiceFrameworkServiceHandler.java:27)
08-30 12:37:14.899  9558  9694 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 12:37:14.899  9558  9694 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 12:37:14.899  9558  9694 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 12:37:14.899  9558  9694 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 12:37:14.899  9558  9694 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-30 12:37:14.899  9631  9695 W System.err: 	at com.samsung.vsf.core.framework.VoiceFrameworkServiceHandler$MyHandlerThread$1.handleMessage(VoiceFrameworkServiceHandler.java:109)
08-30 12:37:14.899  9631  9695 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:37:14.899  9631  9695 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-30 12:37:14.899  9558  9694 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c20f3af added. We now have 1 listener(s)
08-30 12:37:14.899  9631  9695 W System.err: 	at com.samsung.vsf.core.framework.VoiceFrameworkServiceHandler$MyHandlerThread.run(VoiceFrameworkServiceHandler.java:178)
,08-30 12:37:14.899  9631  9695 I EmbeddedFrameworkManager:VoiceFrameworkServiceHandler MyHandlerThread:  : VSP::N66 locale is en_US
08-30 12:37:14.909  9558  9694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: A8:81:95:E9:5F:6F
08-30 12:37:14.909  9558  9694 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
08-30 12:37:14.909  9558  9694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 12:37:14.909  9698  9698 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 12:37:14.909  9558  9694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 12:37:14.909  9698  9698 D ActivityThread: Added TimaKeyStore provider
08-30 12:37:14.909  9558  9694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 12:37:14.909  9558  9694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 12:37:14.909  9558  9694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 12:37:14.909  9558  9694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: A8:81:95:E9:5F:6F
08-30 12:37:14.909  9558  9694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 12:37:14.909  9558  9694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 12:37:14.909  9558  9694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 12:37:14.909  9558  9694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 12:37:14.909  9558  9694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 12:37:14.909  9558  9694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 12:37:14.909  9558  9694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 12:37:14.909  9558  9694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 12:37:14.909  9558  9694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 12:37:14.909  9558  9694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-30 12:37:14.909  9558  9694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b7f69a added. We now have 1 listener(s)
08-30 12:37:14.909  9558  9694 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 12:37:14.919  9631  9695 I EmbeddedFrameworkManager:VoiceFrameworkServiceHandler MyHandlerThread:  : VSP::SHL init():
08-30 12:37:14.919  9631  9695 I EmbeddedFrameworkManager:VoiceFrameworkServiceHandler MyHandlerThread: SHL Config:
08-30 12:37:14.919  9631  9695 I EmbeddedFrameworkManager:VoiceFrameworkServiceHandler MyHandlerThread: Locale: en_US
08-30 12:37:14.919  9631  9695 I EmbeddedFrameworkManager:VoiceFrameworkServiceHandler MyHandlerThread: Recognition Path: EMBEDDED
08-30 12:37:14.919  9631  9695 I EmbeddedFrameworkManager:VoiceFrameworkServiceHandler MyHandlerThread: Audio buffer format: PCM_NS
08-30 12:37:14.919  9631  9695 I EmbeddedFrameworkManager:VoiceFrameworkServiceHandler MyHandlerThread: Use internal recorder: false
08-30 12:37:14.919  9631  9695 I EmbeddedFrameworkManager:VoiceFrameworkServiceHandler MyHandlerThread: Use internal EPD: false
08-30 12:37:14.919  9631  9695 I SHL:VoiceFrameworkServiceHandler MyHandlerThread:  : VSP::SHL Initialize
08-30 12:37:14.919  9631  9695 I etickcount:VoiceFrameworkServiceHandler MyHandlerThread:  : VSP::PocketSphinxEngine:Trying to load libEmbeddedAsr.so
,08-30 12:37:14.939  9631  9695 I etickcount:VoiceFrameworkServiceHandler MyHandlerThread:  : VSP::PocketSphinxEngine:loading libEmbeddedAsr.so done
08-30 12:37:14.949  9631  9695 I etickcount:VoiceFrameworkServiceHandler MyHandlerThread:  : VSP::State changed to NULL
08-30 12:37:14.949  9631  9695 I etickcount:VoiceFrameworkServiceHandler MyHandlerThread:  : VSP::Creating engines for en_US
08-30 12:37:14.949  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
08-30 12:37:14.949  9631  9695 D CMDTest : VoiceFrameworkServiceHandler MyHandlerThread : posted CreateCmd
08-30 12:37:14.949  9631  9695 I etickcount:VoiceFrameworkServiceHandler MyHandlerThread:  : VSP::RecognitionManager loading..
08-30 12:37:14.949  9631  9711 D tickcount:PocketSphinx Recognition Engine:  : VSP::CreateCmd execution latency: 0ms
08-30 12:37:14.949  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP::PocketSphinxEngine:create()
08-30 12:37:14.949  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP::State changed to INIT
08-30 12:37:14.949  9631  9695 D CMDTest : VoiceFrameworkServiceHandler MyHandlerThread : posted ConfigureCmd
08-30 12:37:14.949  9631  9695 I etickcount:VoiceFrameworkServiceHandler MyHandlerThread:  : VSP::State changed to INIT
08-30 12:37:14.949  9631  9711 D tickcount:PocketSphinx Recognition Engine:  : VSP::ConfigureCmd execution latency: 1ms
08-30 12:37:14.949  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP::PocketSphinxEngine:configure() in state INIT
,08-30 12:37:14.989  9631  9631 I SessionRuntime:main:  : VSP::Current Network State is same as previous, so ignoring
,08-30 12:37:14.989  9631  9711 W ResourcesManager: getTopLevelResources: /system/priv-app/SVoiceLang_EnglishPack_US_1.0/SVoiceLang_EnglishPack_US_1.0.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.svoice.lang.en_US
,08-30 12:37:14.989  9558  9694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 12:37:14.989  9558  9694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-30 12:37:14.989  9558  9694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-30 12:37:14.989  9558  9694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-30 12:37:14.989  9558  9694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-30 12:37:14.999  9631  9711 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:14.999  3431  4608 I AppOps  : sendInfoToFLP, code=41 , uid=10043 , packageName=com.samsung.voiceserviceplatform , type=startOp
,08-30 12:37:15.009  3431  4925 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d234ec u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cb4d9c9 9698:com.android.settings/1000}
,08-30 12:37:15.009  9631  9695 I etickcount:VoiceFrameworkServiceHandler MyHandlerThread:  : VSP::setSpeechRecognitionListener: com.samsung.vsf.core.framework.embedded.EmbeddedFrameworkManager@290e3c4
08-30 12:37:15.009  4228  4228 D FusedRequestManager: manageLocationRequest, new passive request from com.samsung.voiceserviceplatform with 3fe15d0 , interval = 1800000 through LocationManagerService
,08-30 12:37:15.009  3431  4608 I ActivityManager: Killing 9126:com.samsung.android.app.FileShareServer/5005 (adj 15): DHA:empty #33
,08-30 12:37:15.019  4588  7826 I Icing   : Indexing E1051AF754FD4764B2B13213EB917898AAC96AFB from com.google.android.gms
,08-30 12:37:15.029  9558  9694 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:37:15.029  9558  9694 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is A8:81:95:E9:5F:6F
,08-30 12:37:15.029  9657  9668 D PLMProvider: match for uri : content://com.samsung.svoice.sync/tos_accepted is : 8
,08-30 12:37:15.029  9698  9698 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
08-30 12:37:15.029  9698  9698 D RelationGraph: garbageCollect()
,08-30 12:37:15.039  9698  9698 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in com.android.settings rsrc of package com.android.settings
,08-30 12:37:15.049  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP::MD5 Files From Assets : en_US.zip.MD5
,08-30 12:37:15.049  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP:: Time Taken LoadMD5FromPackage:  0.003 seconds.
,08-30 12:37:15.049  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP:: Time Taken LoadMD5FromAssets:  0.0 seconds.
08-30 12:37:15.049  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP:: MD5 Checked in :  0.041 seconds.
08-30 12:37:15.049  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP::No Update 0
08-30 12:37:15.049  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP:: #### No Update in The Models #####
08-30 12:37:15.049  9631  9711 D etickcount:PocketSphinx Recognition Engine:  : VSP::TimeTaken for unpacking 97ms
08-30 12:37:15.049  9631  9711 D etickcount: Lang is en_US
,08-30 12:37:15.049  9631  9711 I PLMGenManager: Version  : V_030816
08-30 12:37:15.049  9631  9711 D Flag    : configFalg value : 0
,08-30 12:37:15.049  9631  9711 D PLMGenManager: Is JSON file found ? false
08-30 12:37:15.049  9631  9711 D PLMGenManager: Config flag is : 0
,08-30 12:37:15.049  3431  4327 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,08-30 12:37:15.049  9631  9711 D AppInfo : TimeTaken for App Alias name generation : 2ms
,08-30 12:37:15.059  9698  9698 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,08-30 12:37:15.059  3431  3982 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.FileShareServer, Auto Run ON
,08-30 12:37:15.069  9698  9698 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:15.069  9558  9694 D BluetoothAdapter: STATE_ON
,08-30 12:37:15.069  9631  9711 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2015/SecGallery2015.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.gallery3d
,08-30 12:37:15.069  9631  9711 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:15.069  9558  9694 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-30 12:37:15.069  9558  9694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:37:15.069  9558  9694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:37:15.069  9558  9694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:37:15.069  9558  9694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:37:15.069  9558  9694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:37:15.069  9558  9694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:37:15.069  9558  9694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:37:15.069  9558  9694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 12:37:15.069  9558  9694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-30 12:37:15.069  9558  9694 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 12:37:15.079  9558  9694 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 12:37:15.079  9631  9711 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2015/SecGallery2015.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.gallery3d
08-30 12:37:15.079  9698  9698 I InjectionManager: Inside getClassLibPath caller 
08-30 12:37:15.079  9631  9711 I PLM     : App title : Gallery & activity name : com.sec.android.gallery3d.app.GalleryOpaqueActivity_com.sec.android.gallery3d
08-30 12:37:15.079  9631  9711 W ResourcesManager: getTopLevelResources: /system/priv-app/Phonesky/Phonesky.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.android.vending
08-30 12:37:15.089  4026  4026 D Recents : onTaskStackChanged
,08-30 12:37:15.089  9558  9558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:37:15.089  9631  9711 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:15.099  9698  9698 W System  : ClassLoader referenced unknown path: /system/priv-app/SecSettings2/lib/arm64
,08-30 12:37:15.109  9631  9711 W ResourcesManager: getTopLevelResources: /system/priv-app/Phonesky/Phonesky.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.android.vending
,08-30 12:37:15.109  9558  9558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:37:15.119  9558  9558 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
08-30 12:37:15.119  9631  9711 I PLM     : App title : Play_Store & activity name : com.android.vending.AssetBrowserActivity_com.android.vending
,08-30 12:37:15.119  9631  9711 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.shealth
,08-30 12:37:15.119  4026  4026 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.test.thalitest
,08-30 12:37:15.119  9631  9711 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:15.129  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:15.129  9631  9711 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.shealth
,08-30 12:37:15.139  9631  9711 I PLM     : App title : S_Health & activity name : com.samsung.android.app.shealth.home.HomeMainActivity_com.sec.android.app.shealth
,08-30 12:37:15.139  9698  9698 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in com.android.settings rsrc of package com.android.settings
,08-30 12:37:15.139  9698  9698 D SFinderConnectProvider: onCreate
,08-30 12:37:15.149  4026  4026 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:15.149  9631  9711 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCamera5/SamsungCamera5.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.camera
,08-30 12:37:15.149  9631  9711 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:15.149  9631  9711 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCamera5/SamsungCamera5.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.camera
08-30 12:37:15.149  9631  9711 I PLM     : App title : Camera & activity name : com.sec.android.app.camera.Camera_com.sec.android.app.camera
,08-30 12:37:15.159  9631  9711 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.android.contacts
,08-30 12:37:15.159  9631  9711 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:15.159  9631  9711 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.android.contacts
,08-30 12:37:15.159  9631  9711 I PLM     : App title : Contacts & activity name : com.android.contacts.activities.PeopleActivity_com.android.contacts
,08-30 12:37:15.169  9631  9711 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.android.contacts,
,08-30 12:37:15.169  9631  9711 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.android.contacts
,08-30 12:37:15.169  9631  9711 I PLM     : App title : Phone & activity name : com.android.dialer.DialtactsActivity_com.android.contacts
,08-30 12:37:15.169  9631  9711 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.samsung.android.email.provider
,08-30 12:37:15.169  9631  9711 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:15.179  9631  9711 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.samsung.android.email.provider
,08-30 12:37:15.179  9631  9711 I PLM     : App title : Email & activity name : com.samsung.android.email.ui.activity.MessageListXL_com.samsung.android.email.provider
,08-30 12:37:15.179  9631  9711 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Epic_Common/SecMms_Epic_Common.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.android.mms
,08-30 12:37:15.189  9631  9711 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:15.189  4588  7826 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.gms rsrc of package com.test.thalitest
,08-30 12:37:15.199  9631  9711 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Epic_Common/SecMms_Epic_Common.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.android.mms
08-30 12:37:15.199  9631  9711 I PLM     : App alias title : sms & activity name : com.android.mms.ui.ConversationComposer_com.android.mms
08-30 12:37:15.199  9631  9711 I PLM     : App title : Messages & activity name : com.android.mms.ui.ConversationComposer_com.android.mms
,08-30 12:37:15.199  9631  9711 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.android.settings
,08-30 12:37:15.199  9631  9711 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:15.199  9631  9711 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.android.settings
08-30 12:37:15.199  9631  9711 I PLM     : App title : Settings & activity name : com.android.settings.Settings_com.android.settings
,08-30 12:37:15.199  9631  9711 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.android.chrome
,08-30 12:37:15.209  4588  7826 D ResourcesManager: For user 0 new overlays fetched Null
08-30 12:37:15.209  9631  9711 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:15.209  9631  9711 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.android.chrome
,08-30 12:37:15.209  9631  9711 I PLM     : App title : Chrome & activity name : com.google.android.apps.chrome.Main_com.android.chrome
08-30 12:37:15.209  4588  7826 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.gms rsrc of package com.test.thalitest
,08-30 12:37:15.209  9631  9711 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.apps.docs
,08-30 12:37:15.209  9698  9698 I BNRClientProivder, VERSION : 1.7.5: register - xml6 quick_backup : ACCESSIBILITYSETTINGS, X6qErjsfs2, com.android.settings.accessibility.sharedaccessibility.scloud.BNRTask
08-30 12:37:15.209  9631  9711 D ResourcesManager: For user 0 new overlays fetched Null
08-30 12:37:15.209  9698  9698 I QBNRClientHelper: init SyncClientHelper : ACCESSIBILITYSETTINGS
08-30 12:37:15.209  9698  9698 I BNRClientProivder, VERSION : 1.7.5: register - xml6 quick_backup : CONNECTIONS, C0phMaUuZZ, com.android.settings.wifi.mobileap.WifiApBackupRestore
08-30 12:37:15.209  9698  9698 I QBNRClientHelper: init SyncClientHelper : CONNECTIONS
08-30 12:37:15.209  9698  9698 I BNRClientProivder, VERSION : 1.7.5: register - xml6 quick_backup : WiFi, C0phMaUuZZ, com.android.settings.wifi.WifiBackupRestore
08-30 12:37:15.209  9676  9676 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 android.content.ContextWrapper.sendBroadcast:410 com.samsung.SMT.b.i.a:-1 com.samsung.SMT.SamsungTTSService.onCreate:-1 android.app.ActivityThread.handleCreateService:3808 
08-30 12:37:15.209  9698  9698 I QBNRClientHelper: init SyncClientHelper : WiFi
,08-30 12:37:15.209  9631  9711 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.apps.docs
,08-30 12:37:15.219  4588  7826 I Icing   : Indexing done E1051AF754FD4764B2B13213EB917898AAC96AFB
,08-30 12:37:15.219  9631  9711 I PLM     : App title : Drive & activity name : com.google.android.apps.docs.app.NewMainProxyActivity_com.google.android.apps.docs
,08-30 12:37:15.219  9631  9711 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.gm
,08-30 12:37:15.219  9698  9698 D InjectionManager: InjectionManager
08-30 12:37:15.219  9698  9698 D InjectionManager: fillFeatureStoreMap com.android.settings
,08-30 12:37:15.219  9698  9698 I InjectionManager: Constructor com.android.settings, Feature store :{}
,08-30 12:37:15.219  9698  9698 I InjectionManager: featureStore :{}
,08-30 12:37:15.229  9631  9711 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:15.229  9631  9711 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.gm
,08-30 12:37:15.229  9631  9711 I PLM     : App title : Gmail & activity name : com.google.android.gm.ConversationListActivityGmail_com.google.android.gm
,08-30 12:37:15.229  9631  9711 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.talk
,08-30 12:37:15.239  3431  4208 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d234ec u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cb4d9c9 9698:com.android.settings/1000}
,08-30 12:37:15.239  9631  9711 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:15.239  9631  9711 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.talk
08-30 12:37:15.239  9631  9711 I PLM     : App title : Hangouts & activity name : com.google.android.talk.SigningInActivity_com.google.android.talk
,08-30 12:37:15.239  9631  9711 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.music
,08-30 12:37:15.239  9631  9711 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:15.249  9631  9711 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.music
,08-30 12:37:15.249  9631  9711 I PLM     : App title : Play_Music & activity name : com.android.music.activitymanagement.TopLevelActivity_com.google.android.music
,08-30 12:37:15.249  9631  9711 W ResourcesManager: getTopLevelResources: /system/app/Photos/Photos.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.apps.photos
,08-30 12:37:15.249  3431  4208 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d234ec u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cb4d9c9 9698:com.android.settings/1000}
,08-30 12:37:15.249  9698  9698 I DataWarningReceiver: DataWarningReceiver
,08-30 12:37:15.259  9676  9676 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 com.samsung.SMT.SamsungTTSService.g:-1 com.samsung.SMT.SamsungTTSService.onCreate:-1 android.app.ActivityThread.handleCreateService:3808 
,08-30 12:37:15.269  9719  9719 E Zygote  : v2
08-30 12:37:15.269  9719  9719 I libpersona: KNOX_SDCARD checking this for 10060
08-30 12:37:15.269  9719  9719 I libpersona: KNOX_SDCARD not a persona
,08-30 12:37:15.269  9719  9719 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,08-30 12:37:15.269  9719  9719 E Zygote  : accessInfo : 0
08-30 12:37:15.269  9719  9719 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.provider.shootingmodeprovider 
,08-30 12:37:15.269  3431  4208 I ActivityManager: Start proc 9719:com.samsung.android.provider.shootingmodeprovider/u0a60 for broadcast-3 com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver
,08-30 12:37:15.279  3431  4208 I ActivityManager: Killing 9139:com.enhance.gameservice/u0a111 (adj 15): DHA:empty #33
,08-30 12:37:15.289  9676  9676 I SamsungTTS: Interface ver201503021
08-30 12:37:15.289  9676  9676 I SamsungTTS: Engine ver200812311
,08-30 12:37:15.289  9676  9676 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 com.samsung.SMT.SamsungTTSService.g:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.c.onReceive:-1 
,08-30 12:37:15.299  9631  9631 I TextToSpeech: Connected to ComponentInfo{com.samsung.SMT/com.samsung.SMT.SamsungTTSService}
,08-30 12:37:15.299  3431  4399 D ActivityManager: isAutoRunBlockedApp:: com.enhance.gameservice, Auto Run ON
,08-30 12:37:15.309  9719  9719 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 12:37:15.309  9719  9719 D ActivityThread: Added TimaKeyStore provider
,08-30 12:37:15.309  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:15.309  9631  9711 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:15.319  9676  9686 D SamsungTTS: onIsLanguageAvailable() : L=pol  C=POL  V=null  LANG_NOT_SUPPORTED
08-30 12:37:15.319  9631  9711 W ResourcesManager: getTopLevelResources: /system/app/Photos/Photos.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.apps.photos
08-30 12:37:15.319  9631  9711 I PLM     : App title : Photos & activity name : com.google.android.apps.photos.home.HomeActivity_com.google.android.apps.photos
08-30 12:37:15.319  9631  9731 I TextToSpeech: Set up connection to ComponentInfo{com.samsung.SMT/com.samsung.SMT.SamsungTTSService}
,08-30 12:37:15.319  9631  9711 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.sbrowser
,08-30 12:37:15.319  9631  9711 I PLM     : App title : Internet & activity name : com.sec.android.app.sbrowser.SBrowserMainActivity_com.sec.android.app.sbrowser
08-30 12:37:15.319  9631  9711 D ResourcesManager: For user 0 new overlays fetched Null
08-30 12:37:15.319  9631  9711 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.sbrowser
,08-30 12:37:15.319  9631  9711 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M/SPlanner_M.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.android.calendar
,08-30 12:37:15.319  9631  9711 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:15.329  9631  9631 I SV_TTSPlayer:main:  : VSP::locale is: en_US
08-30 12:37:15.329  9631  9711 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M/SPlanner_M.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.android.calendar
08-30 12:37:15.329  9631  9711 I PLM     : App alias title : calendar & activity name : com.android.calendar.AllInOneActivity_com.android.calendar
08-30 12:37:15.329  9631  9711 I PLM     : App alias title : s_planner & activity name : com.android.calendar.AllInOneActivity_com.android.calendar
08-30 12:37:15.329  9631  9711 I PLM     : App alias title : schedule & activity name : com.android.calendar.AllInOneActivity_com.android.calendar
08-30 12:37:15.329  9631  9711 I PLM     : App alias title : diary & activity name : com.android.calendar.AllInOneActivity_com.android.calendar
08-30 12:37:15.329  9631  9711 I PLM     : App title : S_Planner & activity name : com.android.calendar.AllInOneActivity_com.android.calendar
,08-30 12:37:15.329  9631  9711 W ResourcesManager: getTopLevelResources: /system/app/Videos/Videos.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.videos
,08-30 12:37:15.329  9676  9687 D SamsungTTS: onIsLanguageAvailable() : L=eng  C=USA  V=null  LANG_COUNTRY_AVAILABLE
,08-30 12:37:15.329  9631  9711 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:15.329  3431  4327 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d234ec u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ee79df5 9719:com.samsung.android.provider.shootingmodeprovider/u0a60}
,08-30 12:37:15.329  9631  9711 W ResourcesManager: getTopLevelResources: /system/app/Videos/Videos.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.videos
,08-30 12:37:15.329  9676  9686 D SamsungTTS: onIsLanguageAvailable() : L=eng  C=USA  V=null  LANG_COUNTRY_AVAILABLE
08-30 12:37:15.329  9631  9711 I PLM     : App title : Play_Movies_&_TV & activity name : com.google.android.youtube.videos.EntryPoint_com.google.android.videos
08-30 12:37:15.329  9676  9732 D SamsungTTS: onIsLanguageAvailable() : L=eng  C=USA  V=null  LANG_COUNTRY_AVAILABLE
08-30 12:37:15.329  9631  9711 W ResourcesManager: getTopLevelResources: /system/app/YouTube/YouTube.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.youtube
,08-30 12:37:15.329  9676  9696 D SamsungTTS: onIsLanguageAvailable() : L=eng  C=USA  V=f00  LANG_COUNTRY_VAR_AVAILABLE
,08-30 12:37:15.329  9676  9696 D SamsungTTS: onLoadLanguage() : [ LANG_COUNTRY_VAR_AVAILABLE ]  L=eng  C=USA  V=f00
,08-30 12:37:15.339  9631  9711 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:15.339  9719  9719 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
08-30 12:37:15.339  9719  9719 D RelationGraph: garbageCollect()
,08-30 12:37:15.339  9631  9711 W ResourcesManager: getTopLevelResources: /system/app/YouTube/YouTube.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.youtube
08-30 12:37:15.349  9631  9711 I PLM     : App title : YouTube & activity name : com.google.android.youtube.app.honeycomb.Shell$HomeActivity_com.google.android.youtube
,08-30 12:37:15.349  9719  9719 W ResourcesManager: getTopLevelResources: /system/priv-app/ShootingModeProvider/ShootingModeProvider.apk / 1.0 running in com.samsung.android.provider.shootingmodeprovider rsrc of package com.samsung.android.provider.shootingmodeprovider
08-30 12:37:15.349  9631  9711 W ResourcesManager: getTopLevelResources: /system/priv-app/Excel_SamsungStub/Excel_SamsungStub.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.microsoft.office.excel
,08-30 12:37:15.349  9631  9711 D ResourcesManager: For user 0 new overlays fetched Null
08-30 12:37:15.359  3431  4470 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,08-30 12:37:15.359  9719  9719 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,08-30 12:37:15.359  9631  9711 I PLM     : App title : Excel & activity name : com.microsoft.office.apphost.LaunchActivity_com.microsoft.office.excel
08-30 12:37:15.359  9631  9711 W ResourcesManager: getTopLevelResources: /system/priv-app/Excel_SamsungStub/Excel_SamsungStub.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.microsoft.office.excel
08-30 12:37:15.359  9719  9719 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:15.359  9631  9711 W ResourcesManager: getTopLevelResources: /system/priv-app/GearManager/GearManager.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.samsung.android.app.watchmanager
,08-30 12:37:15.369  9631  9631 D Test    : TTS initialized! & queue size is : 0
,08-30 12:37:15.379  9631  9711 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:15.379  9719  9719 I InjectionManager: Inside getClassLibPath caller 
,08-30 12:37:15.379  9631  9711 W ResourcesManager: getTopLevelResources: /system/priv-app/GearManager/GearManager.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.samsung.android.app.watchmanager
08-30 12:37:15.379  9631  9711 I PLM     : App title : Samsung_Gear & activity name : com.samsung.android.app.watchmanager.setupwizard.SetupWizardWelcomeActivity_com.samsung.android.app.watchmanager
,08-30 12:37:15.379  9631  9711 W ResourcesManager: getTopLevelResources: /system/priv-app/PowerPoint_SamsungStub/PowerPoint_SamsungStub.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.microsoft.office.powerpoint
,08-30 12:37:15.379  9631  9711 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:15.379  9631  9711 W ResourcesManager: getTopLevelResources: /system/priv-app/PowerPoint_SamsungStub/PowerPoint_SamsungStub.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.microsoft.office.powerpoint
08-30 12:37:15.379  9631  9711 I PLM     : App title : PowerPoint & activity name : com.microsoft.office.apphost.LaunchActivity_com.microsoft.office.powerpoint
,08-30 12:37:15.389  9631  9711 W ResourcesManager: getTopLevelResources: /system/priv-app/SVoice_1.0/SVoice_1.0.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.samsung.voiceserviceplatform
08-30 12:37:15.389  9631  9711 W ResourcesManager: getTopLevelResources: /system/priv-app/SVoice_1.0/SVoice_1.0.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.samsung.voiceserviceplatform
08-30 12:37:15.389  9631  9711 W ResourcesManager: getTopLevelResources: /system/priv-app/SecCalculator_M/SecCalculator_M.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.popupcalculator
,08-30 12:37:15.389  9719  9719 W System  : ClassLoader referenced unknown path: /system/priv-app/ShootingModeProvider/lib/arm64
,08-30 12:37:15.389  9631  9711 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:15.399  9631  9711 W ResourcesManager: getTopLevelResources: /system/priv-app/SecCalculator_M/SecCalculator_M.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.popupcalculator
08-30 12:37:15.399  9631  9711 I PLM     : App title : Calculator & activity name : com.sec.android.app.popupcalculator.Calculator_com.sec.android.app.popupcalculator
,08-30 12:37:15.399  9631  9711 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles/SecMyFiles.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.myfiles
,08-30 12:37:15.399  9631  9711 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:15.399  9719  9719 D InjectionManager: InjectionManager
08-30 12:37:15.399  9719  9719 D InjectionManager: fillFeatureStoreMap com.samsung.android.provider.shootingmodeprovider
,08-30 12:37:15.399  9719  9719 I InjectionManager: Constructor com.samsung.android.provider.shootingmodeprovider, Feature store :{}
08-30 12:37:15.399  9719  9719 I InjectionManager: featureStore :{}
,08-30 12:37:15.399  9631  9711 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles/SecMyFiles.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.myfiles
,08-30 12:37:15.399  9631  9711 I PLM     : App title : My_Files & activity name : com.sec.android.app.myfiles.common.MainActivity_com.sec.android.app.myfiles
,08-30 12:37:15.399  9631  9711 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.googlequicksearchbox
,08-30 12:37:15.409  9631  9711 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:15.409  9631  9711 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.googlequicksearchbox
08-30 12:37:15.409  9631  9711 I PLM     : App title : Voice_Search & activity name : com.google.android.googlequicksearchbox.VoiceSearchActivity_com.google.android.googlequicksearchbox
,08-30 12:37:15.409  9631  9711 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.googlequicksearchbox
,08-30 12:37:15.409  9631  9711 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.googlequicksearchbox
08-30 12:37:15.409  9631  9711 I PLM     : App title : Google & activity name : com.google.android.googlequicksearchbox.SearchActivity_com.google.android.googlequicksearchbox
,08-30 12:37:15.409  9631  9711 W ResourcesManager: getTopLevelResources: /system/priv-app/VoiceNote_4.0/VoiceNote_4.0.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.voicenote
,08-30 12:37:15.409  9631  9711 D ResourcesManager: For user 0 new overlays fetched Null
08-30 12:37:15.419  3431  4608 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d234ec u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b3d178a 9498:com.samsung.android.sm.provider/1000}
,08-30 12:37:15.419  9631  9711 W ResourcesManager: getTopLevelResources: /system/priv-app/VoiceNote_4.0/VoiceNote_4.0.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.voicenote
08-30 12:37:15.419  9631  9711 I PLM     : App title : Voice_Recorder & activity name : com.sec.android.app.voicenote.main.VNMainActivity_com.sec.android.app.voicenote
,08-30 12:37:15.419  9631  9711 W ResourcesManager: getTopLevelResources: /system/priv-app/Word_SamsungStub/Word_SamsungStub.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.microsoft.office.word
,08-30 12:37:15.419  9631  9711 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:15.429  9631  9711 W ResourcesManager: getTopLevelResources: /system/priv-app/Word_SamsungStub/Word_SamsungStub.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.microsoft.office.word
,08-30 12:37:15.429  9631  9711 I PLM     : App title : Word & activity name : com.microsoft.office.apphost.LaunchActivity_com.microsoft.office.word
,08-30 12:37:15.449  3431  4985 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d234ec u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8c8f4b8 9457:com.samsung.android.sm.devicesecurity/5012}
,08-30 12:37:15.449  9631  9711 W ResourcesManager: getTopLevelResources: /system/priv-app/player-production-release-3.3.3-newSDK_23/player-production-release-3.3.3-newSDK_23.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package pl.tvn.player
,08-30 12:37:15.459  9558  9718 W jxcore-log: Initializing JXcore engine
08-30 12:37:15.459  9558  9718 W jxcore-log: JXcore engine is ready
,08-30 12:37:15.459  9631  9711 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:15.459  9631  9711 W ResourcesManager: getTopLevelResources: /system/priv-app/player-production-release-3.3.3-newSDK_23/player-production-release-3.3.3-newSDK_23.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package pl.tvn.player
,08-30 12:37:15.459  9631  9711 I PLM     : App title : Player & activity name : pl.tvn.player.ui.SplashActivity_pl.tvn.player
,08-30 12:37:15.469  9631  9711 W ResourcesManager: getTopLevelResources: /system/app/ClockPackage_M/ClockPackage_M.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.clockpackage
,08-30 12:37:15.469  9734  9734 E Zygote  : v2
08-30 12:37:15.469  9734  9734 I libpersona: KNOX_SDCARD checking this for 10067
08-30 12:37:15.469  9734  9734 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
08-30 12:37:15.469  9734  9734 I libpersona: KNOX_SDCARD not a persona
08-30 12:37:15.469  9734  9734 E Zygote  : accessInfo : 0
08-30 12:37:15.469  3431  4608 I ActivityManager: Start proc 9734:com.samsung.android.app.taskedge/u0a67 for broadcast-3 com.samsung.android.app.taskedge/.TaskEdgeBroadcastReceiver
08-30 12:37:15.469  9734  9734 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.app.taskedge 
08-30 12:37:15.469  3431  4608 I ActivityManager: Killing 9152:com.samsung.android.app.watchmanagerstub/u0a112 (adj 15): DHA:empty #33
,08-30 12:37:15.479  5057  5057 E audit   : type=1400 msg=audit(1472553435.479:264): avc:  denied  { ioctl } for  pid=9718 comm="Thread-148" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3100 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-30 12:37:15.479  5057  5057 E audit   :  SEPF_SECMOBILE_6.0.1_0013
08-30 12:37:15.479  5057  5057 E audit   : type=1300 msg=audit(1472553435.479:264): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=8 a1=5451 a2=3 a3=d880a3c8 items=0 ppid=3180 pid=9718 auid=4294967295 uid=10177 gid=10177 euid=10177 suid=10177 fsuid=10177 egid=10177 sgid=10177 fsgid=10177 tty=(none) ses=4294967295 comm="Thread-148" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-30 12:37:15.479  5057  5057 E audit   : type=1327 msg=audit(1472553435.479:264): proctitle="com.test.thalitest"
08-30 12:37:15.479  5057  5057 E audit   : type=1320 msg=audit(1472553435.479:264): 
08-30 12:37:15.479  5057  5057 E audit   : type=1400 msg=audit(1472553435.479:265): avc:  denied  { ioctl } for  pid=9718 comm="Thread-148" path="socket:[10178]" dev="sockfs" ino=10178 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-30 12:37:15.479  5057  5057 E audit   :  SEPF_SECMOBILE_6.0.1_0013
08-30 12:37:15.479  5057  5057 E audit   : type=1300 msg=audit(1472553435.479:265): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=3b a1=5451 a2=3 a3=d880a3c8 items=0 ppid=3180 pid=9718 auid=4294967295 uid=10177 gid=10177 euid=10177 suid=10177 fsuid=10177 egid=10177 sgid=10177 fsgid=10177 tty=(none) ses=4294967295 comm="Thread-148" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-30 12:37:15.479  5057  5057 E audit   : type=1327 msg=audit(1472553435.479:265): proctitle="com.test.thalitest"
08-30 12:37:15.479  5057  5057 E audit   : type=1320 msg=audit(1472553435.479:265): 
,08-30 12:37:15.479  9631  9711 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:15.489  9631  9711 W ResourcesManager: getTopLevelResources: /system/app/ClockPackage_M/ClockPackage_M.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.clockpackage
,08-30 12:37:15.489  9631  9711 I PLM     : App alias title : alarm & activity name : com.sec.android.app.clockpackage.ClockPackage_com.sec.android.app.clockpackage
08-30 12:37:15.489  9631  9711 I PLM     : App title : Clock & activity name : com.sec.android.app.clockpackage.ClockPackage_com.sec.android.app.clockpackage
,08-30 12:37:15.489  9631  9711 W ResourcesManager: getTopLevelResources: /system/app/FBInstagram_stub/FBInstagram_stub.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.instagram.android
,08-30 12:37:15.489  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:15.489  9631  9711 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:15.489  9631  9711 W ResourcesManager: getTopLevelResources: /system/app/FBInstagram_stub/FBInstagram_stub.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.instagram.android
,08-30 12:37:15.499  9631  9711 I PLM     : App title : Instagram & activity name : com.instagram.android.activity.MainTabActivity_com.instagram.android
,08-30 12:37:15.499  9558  9718 W jxcore-log: Starting JXcore engine
08-30 12:37:15.499  9631  9711 W ResourcesManager: getTopLevelResources: /system/app/Facebook_stub/Facebook_stub.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.facebook.katana
,08-30 12:37:15.499  9631  9711 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:15.499  9631  9711 W ResourcesManager: getTopLevelResources: /system/app/Facebook_stub/Facebook_stub.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.facebook.katana
,08-30 12:37:15.499  9631  9711 I PLM     : App title : Facebook & activity name : com.facebook.katana.LoginActivity_com.facebook.katana
,08-30 12:37:15.499  9631  9711 W ResourcesManager: getTopLevelResources: /system/app/MSSkype_stub/MSSkype_stub.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.skype.raider
,08-30 12:37:15.499  9734  9734 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 12:37:15.499  9734  9734 D ActivityThread: Added TimaKeyStore provider
,08-30 12:37:15.509  9631  9711 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:15.509  9631  9711 W ResourcesManager: getTopLevelResources: /system/app/MSSkype_stub/MSSkype_stub.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.skype.raider
,08-30 12:37:15.509  9631  9711 I PLM     : App title : Skype & activity name : com.skype.raider.Main_com.skype.raider
08-30 12:37:15.509  9631  9711 W ResourcesManager: getTopLevelResources: /system/app/Maps/Maps.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.apps.maps
,08-30 12:37:15.519  9631  9711 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:15.519  3431  3450 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d234ec u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4eb41fb 9734:com.samsung.android.app.taskedge/u0a67}
,08-30 12:37:15.519  9631  9711 W ResourcesManager: getTopLevelResources: /system/app/Maps/Maps.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.apps.maps
,08-30 12:37:15.519  9631  9711 I PLM     : App title : Maps & activity name : com.google.android.maps.MapsActivity_com.google.android.apps.maps
,08-30 12:37:15.519  9631  9711 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.microsoft.skydrive
,08-30 12:37:15.519  9631  9711 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:15.529  9631  9711 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.microsoft.skydrive
,08-30 12:37:15.529  9631  9711 I PLM     : App title : OneDrive & activity name : com.microsoft.skydrive.MainActivity_com.microsoft.skydrive
,08-30 12:37:15.529  9734  9734 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,08-30 12:37:15.529  9734  9734 D RelationGraph: garbageCollect()
,08-30 12:37:15.529  9631  9711 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.microsoft.office.onenote
,08-30 12:37:15.529  9734  9734 W ResourcesManager: getTopLevelResources: /system/priv-app/TaskEdgePanel/TaskEdgePanel.apk / 1.0 running in com.samsung.android.app.taskedge rsrc of package com.samsung.android.app.taskedge
,08-30 12:37:15.529  3431  3982 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
08-30 12:37:15.539  9734  9734 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,08-30 12:37:15.539  9631  9711 D ResourcesManager: For user 0 new overlays fetched Null
08-30 12:37:15.539  9631  9711 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.microsoft.office.onenote
,08-30 12:37:15.539  9631  9711 I PLM     : App title : OneNote & activity name : com.microsoft.office.onenote.ui.ONMSplashActivity_com.microsoft.office.onenote
,08-30 12:37:15.539  9631  9711 W ResourcesManager: getTopLevelResources: /system/app/SecMemo3/SecMemo3.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.samsung.android.app.memo
,08-30 12:37:15.539  9558  9718 W jxcore-log: Platform android
08-30 12:37:15.539  9558  9718 W jxcore-log: 
08-30 12:37:15.539  9558  9718 W jxcore-log: Process ARCH arm
08-30 12:37:15.539  9558  9718 W jxcore-log: 
,08-30 12:37:15.539  9734  9734 D ResourcesManager: For user 0 new overlays fetched Null
08-30 12:37:15.539  9631  9711 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:15.549  9734  9734 I InjectionManager: Inside getClassLibPath caller 
08-30 12:37:15.549  9631  9711 W ResourcesManager: getTopLevelResources: /system/app/SecMemo3/SecMemo3.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.samsung.android.app.memo
,08-30 12:37:15.549  9631  9711 I PLM     : App title : Memo & activity name : com.samsung.android.app.memo.Main_com.samsung.android.app.memo
,08-30 12:37:15.549  9631  9711 W ResourcesManager: getTopLevelResources: /system/app/WhatsAppDownloader/WhatsAppDownloader.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.whatsapp
,08-30 12:37:15.549  9734  9734 W System  : ClassLoader referenced unknown path: /system/priv-app/TaskEdgePanel/lib/arm64
08-30 12:37:15.549  9631  9711 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:15.549  9631  9711 I PLM     : App title : WhatsApp & activity name : com.whatsapp.Main_com.whatsapp
,08-30 12:37:15.549  9631  9711 W ResourcesManager: getTopLevelResources: /data/app/com.sec.android.app.samsungapps-1/base.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.samsungapps
08-30 12:37:15.559  9734  9734 D InjectionManager: InjectionManager
08-30 12:37:15.559  9734  9734 D InjectionManager: fillFeatureStoreMap com.samsung.android.app.taskedge
08-30 12:37:15.559  9734  9734 I InjectionManager: Constructor com.samsung.android.app.taskedge, Feature store :{}
08-30 12:37:15.559  9734  9734 I InjectionManager: featureStore :{}
08-30 12:37:15.559  9734  9734 I TaskEdgeBroadcastReceiver: onReceive:android.intent.action.PACKAGE_ADDED
08-30 12:37:15.559  9631  9711 D ResourcesManager: For user 0 new overlays fetched Null
08-30 12:37:15.559  3431  3451 I ActivityManager: Killing 9165:com.sec.android.app.popupuireceiver/1000 (adj 15): DHA:empty #33
08-30 12:37:15.569  3431  3451 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d234ec u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c5d3701 4300:com.android.phone/1001}
08-30 12:37:15.579  9631  9711 W ResourcesManager: getTopLevelResources: /data/app/com.sec.android.app.samsungapps-1/base.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.samsungapps
08-30 12:37:15.579  9631  9711 I PLM     : App title : Galaxy_Apps & activity name : com.sec.android.app.samsungapps.SamsungAppsMainActivity_com.sec.android.app.samsungapps
08-30 12:37:15.579  9631  9711 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.test.thalitest
08-30 12:37:15.579  9631  9711 D ResourcesManager: For user 0 new overlays fetched Null
08-30 12:37:15.579  9631  9711 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.test.thalitest
08-30 12:37:15.579  9631  9711 I PLM     : App title : ThaliTest & activity name : com.test.thalitest.MainActivity_com.test.thalitest
08-30 12:37:15.589  9676  9696 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 android.content.ContextWrapper.sendBroadcast:410 com.samsung.SMT.b.i.a:-1 com.samsung.SMT.SamsungTTSService.b:-1 com.samsung.SMT.SamsungTTSService.onLoadLanguage:-1 
,08-30 12:37:15.609  9747  9747 E Zygote  : v2
08-30 12:37:15.609  9747  9747 I libpersona: KNOX_SDCARD checking this for 1000
08-30 12:37:15.609  9747  9747 I libpersona: KNOX_SDCARD not a persona
,08-30 12:37:15.609  9747  9747 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
08-30 12:37:15.609  3431  3451 I ActivityManager: Start proc 9747:com.samsung.android.themecenter/1000 for broadcast-3 com.samsung.android.themecenter/com.samsung.android.thememanager.ThemeManagerReceiver
08-30 12:37:15.609  9747  9747 E Zygote  : accessInfo : 0
,08-30 12:37:15.619  3431  4399 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.popupuireceiver, Auto Run ON
,08-30 12:37:15.629  9747  9747 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 12:37:15.629  9747  9747 D ActivityThread: Added TimaKeyStore provider
,08-30 12:37:15.629  3431  4208 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.watchmanagerstub, Auto Run ON
,08-30 12:37:15.639  9676  9696 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 android.content.ContextWrapper.sendBroadcast:410 android.speech.tts.TextToSpeechService$SynthThread.broadcastTtsQueueProcessingCompleted:460 android.speech.tts.TextToSpeechService$SynthThread.queueIdle:452 android.os.MessageQueue.next:392 
,08-30 12:37:15.639  9558  9718 I jxcore-log: JXcore Cordova bridge is ready!
08-30 12:37:15.639  9558  9718 I jxcore-log: 
08-30 12:37:15.639  9558  9718 W jxcore-log: JXcore engine is started
,08-30 12:37:15.639  9558  9694 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-30 12:37:15.649  9558  9558 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-30 12:37:15.649  3431  4925 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d234ec u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{967c218 9747:com.samsung.android.themecenter/1000}
,08-30 12:37:15.659  9747  9747 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
08-30 12:37:15.659  9747  9747 D RelationGraph: garbageCollect()
,08-30 12:37:15.659  9747  9747 W ResourcesManager: getTopLevelResources: /system/priv-app/ThemeCenter/ThemeCenter.apk / 1.0 running in com.samsung.android.themecenter rsrc of package com.samsung.android.themecenter
,08-30 12:37:15.659  3431  3451 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
08-30 12:37:15.659  9747  9747 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,08-30 12:37:15.669  9631  9711 D ContactInfo: Matched with previous entries!
,08-30 12:37:15.669  9747  9747 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:15.669  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
08-30 12:37:15.669  9747  9747 I InjectionManager: Inside getClassLibPath caller 
,08-30 12:37:15.669  9747  9747 W System  : ClassLoader referenced unknown path: /system/priv-app/ThemeCenter/lib/arm64
,08-30 12:37:15.679  9747  9747 D InjectionManager: InjectionManager
08-30 12:37:15.679  9747  9747 D InjectionManager: fillFeatureStoreMap com.samsung.android.themecenter
,08-30 12:37:15.679  9747  9747 I InjectionManager: Constructor com.samsung.android.themecenter, Feature store :{}
08-30 12:37:15.679  9747  9747 I InjectionManager: featureStore :{}
,08-30 12:37:15.679  9747  9747 I ThemeManagerReceiver: ThemeManagerReceiver onReceive android.intent.action.PACKAGE_ADDED
,08-30 12:37:15.689  3431  4208 I ActivityManager: Killing 9191:com.sec.spp.push:RemoteDlcProcess/u0a42 (adj 15): DHA:empty #33
,08-30 12:37:15.689  3431  4208 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d234ec u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8bdd8e4 4444:com.google.android.googlequicksearchbox:search/u0a72}
,08-30 12:37:15.699  9631  9711 D PLMGenManager: Any updates for FSG and DICT? : Yes
,08-30 12:37:15.699  9631  9711 D PLMGenManager: TimeTaken for Contact & App sync 648ms
,08-30 12:37:15.699  9631  9711 D etickcount:BuildCmd: Dictionary name : /data/user/0/com.sec.svoice.lang.en_US/files/en_US/dict/hero.dict
,08-30 12:37:15.709  9631  9711 I FSGFileGenerator:PocketSphinx: Model dir : /data/user/0/com.sec.svoice.lang.en_US/files/en_US
,08-30 12:37:15.709  9631  9711 I FSGFileGenerator:PocketSphinx: FSG : start
,08-30 12:37:15.709  9631  9711 D FSGFileGenerator:PocketSphinx: Inside initFileWriter
,08-30 12:37:15.709  9631  9711 I FSGFileGenerator:PocketSphinx: templateFsgFileToRead = { /data/user/0/com.sec.svoice.lang.en_US/files/en_US/lm/hero.detmin.fsg.org, fsgFileToCreate = /data/user/0/com.sec.svoice.lang.en_US/files/en_US/lm/hero.detmin.fsg }
,08-30 12:37:15.709  9631  9711 D FSGFileGenerator:PocketSphinx: FileWriter/FileReader created
,08-30 12:37:15.709  3431  3450 D ActivityManager: isAutoRunBlockedApp:: com.sec.spp.push, Auto Run ON
,08-30 12:37:15.729  9631  9711 D FSGFileGenerator:PocketSphinx: FileWriter is closed sucessfull
08-30 12:37:15.729  9631  9711 D FSGFileGenerator:PocketSphinx: FileReader is closed sucessfull
08-30 12:37:15.729  9631  9711 D FSGFileGenerator:PocketSphinx: Inside initFileWriter
08-30 12:37:15.729  9631  9711 I FSGFileGenerator:PocketSphinx: templateFsgFileToRead = { /data/user/0/com.sec.svoice.lang.en_US/files/en_US/lm/hero.detmin.wo.wakeup.fsg.org, fsgFileToCreate = /data/user/0/com.sec.svoice.lang.en_US/files/en_US/lm/hero.detmin.wo.wakeup.fsg }
,08-30 12:37:15.729  9631  9711 D FSGFileGenerator:PocketSphinx: FileWriter/FileReader created
,08-30 12:37:15.729  3431  4608 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d234ec u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8bdd8e4 4444:com.google.android.googlequicksearchbox:search/u0a72}
,08-30 12:37:15.739  4444  9759 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,08-30 12:37:15.749  9631  9711 D FSGFileGenerator:PocketSphinx: FileWriter is closed sucessfull
08-30 12:37:15.749  9631  9711 D FSGFileGenerator:PocketSphinx: FileReader is closed sucessfull
08-30 12:37:15.749  9631  9711 D FSGFileGenerator:PocketSphinx: FSG : COMPLETED in 40 ms.
08-30 12:37:15.749  9631  9711 I FSGFileGenerator:PocketSphinx: FSG : start
08-30 12:37:15.749  9631  9711 D FSGFileGenerator:PocketSphinx: Inside initFileWriter
08-30 12:37:15.749  9631  9711 I FSGFileGenerator:PocketSphinx: templateFsgFileToRead = { /data/user/0/com.sec.svoice.lang.en_US/files/en_US/lm/contact.fsg.org, fsgFileToCreate = /data/user/0/com.sec.svoice.lang.en_US/files/en_US/lm/contact.fsg }
08-30 12:37:15.749  9631  9711 D FSGFileGenerator:PocketSphinx: FileWriter/FileReader created
,08-30 12:37:15.749  9631  9711 D FSGFileGenerator:PocketSphinx: FileWriter is closed sucessfull
08-30 12:37:15.749  9631  9711 D FSGFileGenerator:PocketSphinx: FileReader is closed sucessfull
08-30 12:37:15.749  9631  9711 D FSGFileGenerator:PocketSphinx: Inside initFileWriter
08-30 12:37:15.749  9631  9711 I FSGFileGenerator:PocketSphinx: templateFsgFileToRead = { /data/user/0/com.sec.svoice.lang.en_US/files/en_US/lm/contact.fav.fsg.org, fsgFileToCreate = /data/user/0/com.sec.svoice.lang.en_US/files/en_US/lm/contact.fav.fsg }
08-30 12:37:15.749  9631  9711 D FSGFileGenerator:PocketSphinx: FileWriter/FileReader created
,08-30 12:37:15.749  9631  9711 D FSGFileGenerator:PocketSphinx: FileWriter is closed sucessfull
08-30 12:37:15.749  9631  9711 D FSGFileGenerator:PocketSphinx: FileReader is closed sucessfull
08-30 12:37:15.749  9631  9711 D FSGFileGenerator:PocketSphinx:OWC: FSG : COMPLETED in 3 ms.
08-30 12:37:15.749  9631  9711 I DictionaryGenerator:PocketSphinx: Model dir : /data/user/0/com.sec.svoice.lang.en_US/files/en_US
08-30 12:37:15.749  9631  9711 I DictionaryGenerator:PocketSphinx: Locale : en_US
,08-30 12:37:15.749  9631  9711 I DictionaryGenerator:PocketSphinx: DFG : Start
08-30 12:37:15.749  9631  9711 D DictionaryGenerator:PocketSphinx: Inside initFileWriter : Dict file name : /data/user/0/com.sec.svoice.lang.en_US/files/en_US/dict/hero.dict
08-30 12:37:15.749  9631  9711 I DictionaryGenerator:PocketSphinx: mDictionaryFile = { /data/user/0/com.sec.svoice.lang.en_US/files/en_US/dict/hero.dict }
08-30 12:37:15.749  9631  9711 D DictionaryGenerator:PocketSphinx: FileWriter created
08-30 12:37:15.749  9631  9711 D DictionaryGenerator:PocketSphinx: copying frm : /data/user/0/com.sec.svoice.lang.en_US/files/en_US/dict/hero.dict
,08-30 12:37:15.749  9760  9760 E Zygote  : v2
,08-30 12:37:15.749  9760  9760 I libpersona: KNOX_SDCARD checking this for 5009
08-30 12:37:15.749  9760  9760 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
08-30 12:37:15.749  9760  9760 I libpersona: KNOX_SDCARD not a persona
,08-30 12:37:15.749  9631  9711 D DictionaryGenerator:PocketSphinx: Wakeup word is : null
,08-30 12:37:15.749  3431  3981 I ActivityManager: Start proc 9760:com.samsung.android.scloud/5009 for broadcast-3 com.samsung.android.scloud/.receivers.SCloudReceiver
08-30 12:37:15.749  9631  9711 D DictionaryGenerator:PocketSphinx: wakeup string added to dict : slot_wakeup_start__WAKEUP__slot_wakeup_end	S L AA T W EY K AH P S T AA R T W EY K AH P S L AA T W EY K AH P EH N D
08-30 12:37:15.749  9760  9760 E Zygote  : accessInfo : 0
08-30 12:37:15.749  9760  9760 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.scloud 
,08-30 12:37:15.759  9631  9711 I G2P     : PocketSphinxEngine:Trying to load : /data/user/0/com.sec.svoice.lang.en_US/files/en_US/libs/libG2PenUS.so
,08-30 12:37:15.769  9631  9711 I G2P     : PocketSphinxEngine:loading /data/user/0/com.sec.svoice.lang.en_US/files/en_US/libs/libG2PenUS.so done
,08-30 12:37:15.769  9631  9711 V G2P-SRIB: Build date: Apr 28 2016, 15:00:24
08-30 12:37:15.769  9631  9711 V G2P-SRIB: enUS G2P libs
08-30 12:37:15.769  9631  9711 V G2P-SRIB: stringCount: 46
08-30 12:37:15.769  4428  4476 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
08-30 12:37:15.769  4428  4476 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
08-30 12:37:15.769  9631  9711 V G2P-SRIB: Config: lang: en-US,
08-30 12:37:15.769  9631  9711 V G2P-SRIB: variant: mp
08-30 12:37:15.769  9631  9711 V G2P-SRIB: prefix: slot_application_names_start__
08-30 12:37:15.769  9631  9711 V G2P-SRIB: suffix: __slot_application_names_end
,08-30 12:37:15.769  9631  9711 V G2P-SRIB: Options dump_pron: W W K K K K K K K K K K K K K W W,
08-30 12:37:15.769  9631  9711 V G2P-SRIB: After conversion: Internet, Internet, 8, 8
08-30 12:37:15.769  9760  9760 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 12:37:15.769  9760  9760 D ActivityThread: Added TimaKeyStore provider
,08-30 12:37:15.769  9631  9711 V G2P-SRIB: After g2p: prons 1, max_pron_len 17
,08-30 12:37:15.769  9631  9711 V G2P-SRIB: Output pron: ih n t er n eh t, i in loop: 0
08-30 12:37:15.769  9631  9711 V G2P-SRIB: After conversion: Phone, Phone, 5, 5
08-30 12:37:15.769  9631  9711 V G2P-SRIB: After g2p: prons 1, max_pron_len 7
08-30 12:37:15.779  9631  9711 V G2P-SRIB: Output pron: f ow n, i in loop: 0
08-30 12:37:15.779  9631  9711 V G2P-SRIB: After conversion: Voice_Recorder, Voice_Recorder, 14, 14
08-30 12:37:15.779  9631  9711 V G2P-SRIB: After g2p: prons 1, max_pron_len 24
08-30 12:37:15.779  9631  9711 V G2P-SRIB: Output pron: v oy s r ih k ao r d er, i in loop: 0
08-30 12:37:15.779  9631  9711 V G2P-SRIB: After conversion: Player, Player, 6, 6
08-30 12:37:15.779  9631  9711 V G2P-SRIB: After g2p: prons 1, max_pron_len 10
08-30 12:37:15.779  9631  9711 V G2P-SRIB: Output pron: p l ey er, i in loop: 0
08-30 12:37:15.779  9631  9711 V G2P-SRIB: After conversion: Word, Word, 4, 4
08-30 12:37:15.779  9631  9711 V G2P-SRIB: After g2p: prons 1, max_pron_len 7
08-30 12:37:15.779  3431  4327 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d234ec u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d5d2256 9760:com.samsung.android.scloud/5009}
08-30 12:37:15.779  9631  9711 V G2P-SRIB: Output pron: w er d, i in loop: 0
08-30 12:37:15.779  9631  9711 V G2P-SRIB: After conversion: Samsung_Gear, Samsung_Gear, 12, 12
08-30 12:37:15.779  9631  9711 V G2P-SRIB: After g2p: prons 1, max_pron_len 22
08-30 12:37:15.779  9631  9711 V G2P-SRIB: Output pron: s ae m s ah ng g ih r, i in loop: 0
08-30 12:37:15.779  9631  9711 V G2P-SRIB: After conversion: schedule, schedule, 8, 8
08-30 12:37:15.779  9631  9711 V G2P-SRIB: After g2p: prons 1, max_pron_len 15
,08-30 12:37:15.779  9631  9711 V G2P-SRIB: Output pron: s k eh jh uh l, i in loop: 0
08-30 12:37:15.779  9631  9711 V G2P-SRIB: After conversion: Play_Music, Play_Music, 10, 10
08-30 12:37:15.779  9631  9711 V G2P-SRIB: After g2p: prons 1, max_pron_len 21
08-30 12:37:15.779  9631  9711 V G2P-SRIB: Output pron: p l ey m y uw z ih k, i in loop: 0
08-30 12:37:15.779  9631  9711 V G2P-SRIB: After conversion: S_Planner, S_Planner, 9, 9
08-30 12:37:15.779  9631  9711 V G2P-SRIB: After g2p: prons 1, max_pron_len 17
08-30 12:37:15.779  9631  9711 V G2P-SRIB: Output pron: eh s p l ae n er, i in loop: 0
08-30 12:37:15.779  9631  9711 V G2P-SRIB: After conversion: Memo, Memo, 4, 4
08-30 12:37:15.779  9631  9711 V G2P-SRIB: After g2p: prons 1, max_pron_len 10
,08-30 12:37:15.779  9631  9711 V G2P-SRIB: Output pron: m eh m ow, i in loop: 0
08-30 12:37:15.779  9631  9711 V G2P-SRIB: After conversion: Drive, Drive, 5, 5
08-30 12:37:15.779  9631  9711 V G2P-SRIB: After g2p: prons 1, max_pron_len 9
08-30 12:37:15.779  9631  9711 V G2P-SRIB: Output pron: d r ay v, i in loop: 0
08-30 12:37:15.779  9631  9711 V G2P-SRIB: After conversion: Galaxy_Apps, Galaxy_Apps, 11, 11
08-30 12:37:15.779  9631  9711 V G2P-SRIB: After g2p: prons 1, max_pron_len 24
08-30 12:37:15.779  9631  9711 V G2P-SRIB: Output pron: g ae l ah k s iy ae p s, i in loop: 0
,08-30 12:37:15.779  9631  9711 V G2P-SRIB: After conversion: Calculator, Calculator, 10, 10
08-30 12:37:15.779  9631  9711 V G2P-SRIB: After g2p: prons 1, max_pron_len 24
,08-30 12:37:15.779  9631  9711 V G2P-SRIB: Output pron: k ae l k y ah l ey t er, i in loop: 0
08-30 12:37:15.779  9631  9711 V G2P-SRIB: After conversion: Chrome, Chrome, 6, 6
08-30 12:37:15.779  9631  9711 V G2P-SRIB: After g2p: prons 1, max_pron_len 9
08-30 12:37:15.779  9631  9711 V G2P-SRIB: Output pron: k r ow m, i in loop: 0
,08-30 12:37:15.779  9631  9711 V G2P-SRIB: After conversion: OneDrive, OneDrive, 8, 8
08-30 12:37:15.789  9631  9711 V G2P-SRIB: After g2p: prons 1, max_pron_len 19
08-30 12:37:15.789  9631  9711 V G2P-SRIB: Output pron: w ah n eh d r ay v, i in loop: 0
08-30 12:37:15.789  9631  9711 V G2P-SRIB: After conversion: Instagram, Instagram, 9, 9
,08-30 12:37:15.789  9631  9711 V G2P-SRIB: After g2p: prons 1, max_pron_len 21
08-30 12:37:15.789  9631  9711 V G2P-SRIB: Output pron: ih n s t ax g r ae m, i in loop: 0
08-30 12:37:15.789  9631  9711 V G2P-SRIB: After conversion: Contacts, Contacts, 8, 8
08-30 12:37:15.789  9631  9711 V G2P-SRIB: After g2p: prons 1, max_pron_len 18
08-30 12:37:15.789  9631  9711 V G2P-SRIB: Output pron: k aa n t ae k t s, i in loop: 0
08-30 12:37:15.789  9631  9711 V G2P-SRIB: After conversion: ThaliTest, ThaliTest, 9, 9
,08-30 12:37:15.789  9631  9711 V G2P-SRIB: After g2p: prons 1, max_pron_len 20
08-30 12:37:15.789  9631  9711 V G2P-SRIB: Output pron: th ae l ay t ax s t, i in loop: 0
08-30 12:37:15.789  4444  9759 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package com.test.thalitest
08-30 12:37:15.789  9631  9711 V G2P-SRIB: After conversion: WhatsApp, WhatsApp, 8, 8
,08-30 12:37:15.789  9631  9711 V G2P-SRIB: After g2p: prons 1, max_pron_len 14
08-30 12:37:15.789  9631  9711 V G2P-SRIB: Output pron: w aa t s ae p, i in loop: 0
08-30 12:37:15.789  9631  9711 V G2P-SRIB: After conversion: Messages, Messages, 8, 8
08-30 12:37:15.789  9631  9711 V G2P-SRIB: After g2p: prons 1, max_pron_len 18
,08-30 12:37:15.789  9631  9711 V G2P-SRIB: Output pron: m eh s ax jh ax z, i in loop: 0
08-30 12:37:15.789  9631  9711 V G2P-SRIB: After conversion: Email, Email, 5, 5
08-30 12:37:15.789  9631  9711 V G2P-SRIB: After g2p: prons 1, max_pron_len 10
08-30 12:37:15.789  9631  9711 V G2P-SRIB: Output pron: iy m ey l, i in loop: 0
08-30 12:37:15.789  9631  9711 V G2P-SRIB: After conversion: Hangouts, Hangouts, 8, 8
,08-30 12:37:15.789  9631  9711 V G2P-SRIB: After g2p: prons 1, max_pron_len 16
08-30 12:37:15.789  9631  9711 V G2P-SRIB: Output pron: hh ae ng aw t s, i in loop: 0
08-30 12:37:15.789  9631  9711 V G2P-SRIB: After conversion: OneNote, OneNote, 7, 7
,08-30 12:37:15.789  9631  9711 V G2P-SRIB: After g2p: prons 1, max_pron_len 17
08-30 12:37:15.789  9631  9711 V G2P-SRIB: Output pron: w ah n ih n ow t, i in loop: 0
08-30 12:37:15.789  9631  9711 V G2P-SRIB: After conversion: calendar, calendar, 8, 8
08-30 12:37:15.789  9631  9711 V G2P-SRIB: After g2p: prons 1, max_pron_len 17
,08-30 12:37:15.789  9631  9711 V G2P-SRIB: Output pron: k ae l ax n d er, i in loop: 0
08-30 12:37:15.789  9631  9711 V G2P-SRIB: After conversion: Play_Store, Play_Store, 10, 10
08-30 12:37:15.789  9631  9711 V G2P-SRIB: After g2p: prons 1, max_pron_len 16
08-30 12:37:15.789  9631  9711 V G2P-SRIB: Output pron: p l ey s t ao r, i in loop: 0
08-30 12:37:15.789  9631  9711 V G2P-SRIB: After conversion: Photos, Photos, 6, 6
,08-30 12:37:15.789  9631  9711 V G2P-SRIB: After g2p: prons 1, max_pron_len 12
08-30 12:37:15.789  9631  9711 V G2P-SRIB: Output pron: f ow t ow z, i in loop: 0
08-30 12:37:15.789  9631  9711 V G2P-SRIB: After conversion: Excel, Excel, 5, 5
,08-30 12:37:15.789  9631  9711 V G2P-SRIB: After g2p: prons 1, max_pron_len 12
08-30 12:37:15.789  9631  9711 V G2P-SRIB: Output pron: ih k s eh l, i in loop: 0
,08-30 12:37:15.789  9631  9711 V G2P-SRIB: After conversion: Gallery, Gallery, 7, 7
08-30 12:37:15.789  9631  9711 V G2P-SRIB: After g2p: prons 1, max_pron_len 13
08-30 12:37:15.789  9631  9711 V G2P-SRIB: Output pron: g ae l er iy, i in loop: 0
08-30 12:37:15.789  4444  9759 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:15.789  9631  9711 V G2P-SRIB: After conversion: sms, sms, 3, 3
08-30 12:37:15.789  9631  9711 V G2P-SRIB: After g2p: prons 1, max_pron_len 15
08-30 12:37:15.789  9631  9711 V G2P-SRIB: Output pron: eh s eh m eh s, i in loop: 0
08-30 12:37:15.789  9631  9711 V G2P-SRIB: After conversion: S_Health, S_Health, 8, 8
08-30 12:37:15.789  9631  9711 V G2P-SRIB: After g2p: prons 1, max_pron_len 16
08-30 12:37:15.789  9631  9711 V G2P-SRIB: Output pron: eh s hh eh l th, i in loop: 0
,08-30 12:37:15.789  9631  9711 V G2P-SRIB: After conversion: Skype, Skype, 5, 5
08-30 12:37:15.789  9631  9711 V G2P-SRIB: After g2p: prons 1, max_pron_len 9
08-30 12:37:15.789  9631  9711 V G2P-SRIB: Output pron: s k ay p, i in loop: 0
08-30 12:37:15.789  9631  9711 V G2P-SRIB: After conversion: alarm, alarm, 5, 5
08-30 12:37:15.789  9631  9711 V G2P-SRIB: After g2p: prons 1, max_pron_len 12
,08-30 12:37:15.789  9631  9711 V G2P-SRIB: Output pron: ah l aa r m, i in loop: 0
08-30 12:37:15.789  9631  9711 V G2P-SRIB: After conversion: Voice_Search, Voice_Search, 12, 12
08-30 12:37:15.789  9631  9711 V G2P-SRIB: After g2p: prons 1, max_pron_len 15
08-30 12:37:15.789  9631  9711 V G2P-SRIB: Output pron: v oy s s er ch, i in loop: 0
08-30 12:37:15.789  9631  9711 V G2P-SRIB: After conversion: Play_Movies_&_TV, Play_Movies_&_TV, 16, 16
,08-30 12:37:15.799  9760  9760 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,08-30 12:37:15.799  9760  9760 D RelationGraph: garbageCollect()
,08-30 12:37:15.799  4444  9759 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package com.test.thalitest
08-30 12:37:15.799  9760  9760 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.samsung.android.scloud
,08-30 12:37:15.799  3431  4608 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,08-30 12:37:15.799  9760  9760 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,08-30 12:37:15.799  9760  9760 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:15.799  9631  9711 V G2P-SRIB: After g2p: prons 4, max_pron_len 49
,08-30 12:37:15.799  9631  9711 V G2P-SRIB: Output pron: p l ey m uw v iy z ah n d t iy v iy, i in loop: 0
08-30 12:37:15.799  9631  9711 V G2P-SRIB: Output pron: p l ey m uw v iy z ae n d t iy v iy, i in loop: 1
08-30 12:37:15.799  9631  9711 V G2P-SRIB: Output pron: p l ey m uw v iy z ah n d t eh l ah v ih zh ah n, i in loop: 2
08-30 12:37:15.799  9631  9711 V G2P-SRIB: Output pron: p l ey m uw v iy z ae n d t eh l ah v ih zh ah n, i in loop: 3
,08-30 12:37:15.799  9631  9711 V G2P-SRIB: After conversion: My_Files, My_Files, 8, 8
08-30 12:37:15.799  9631  9711 V G2P-SRIB: After g2p: prons 1, max_pron_len 14
08-30 12:37:15.799  9631  9711 V G2P-SRIB: Output pron: m ay f ay l z, i in loop: 0
08-30 12:37:15.799  9631  9711 V G2P-SRIB: After conversion: Maps, Maps, 4, 4
08-30 12:37:15.799  9760  9760 I InjectionManager: Inside getClassLibPath caller 
08-30 12:37:15.799  9631  9711 V G2P-SRIB: After g2p: prons 1, max_pron_len 9
08-30 12:37:15.799  9631  9711 V G2P-SRIB: Output pron: m ae p s, i in loop: 0
08-30 12:37:15.799  9631  9711 V G2P-SRIB: After conversion: Clock, Clock, 5, 5
08-30 12:37:15.799  9631  9711 V G2P-SRIB: After g2p: prons 1, max_pron_len 9
,08-30 12:37:15.799  9631  9711 V G2P-SRIB: Output pron: k l aa k, i in loop: 0
08-30 12:37:15.799  9631  9711 V G2P-SRIB: After conversion: Settings, Settings, 8, 8
08-30 12:37:15.809  9631  9711 V G2P-SRIB: After g2p: prons 1, max_pron_len 15
08-30 12:37:15.809  9631  9711 V G2P-SRIB: Output pron: s eh t ih ng z, i in loop: 0
08-30 12:37:15.809  9631  9711 V G2P-SRIB: After conversion: s_planner, s_planner, 9, 9
,08-30 12:37:15.809  9631  9711 V G2P-SRIB: After g2p: prons 1, max_pron_len 17
08-30 12:37:15.809  9631  9711 V G2P-SRIB: Output pron: eh s p l ae n er, i in loop: 0
08-30 12:37:15.809  9631  9711 V G2P-SRIB: After conversion: PowerPoint, PowerPoint, 10, 10
,08-30 12:37:15.809  9631  9711 V G2P-SRIB: After g2p: prons 1, max_pron_len 17
08-30 12:37:15.809  9631  9711 V G2P-SRIB: Output pron: p aw er p oy n t, i in loop: 0
08-30 12:37:15.809  9631  9711 V G2P-SRIB: After conversion: Facebook, Facebook, 8, 8
,08-30 12:37:15.809  9631  9711 V G2P-SRIB: After g2p: prons 1, max_pron_len 14
08-30 12:37:15.809  9631  9711 V G2P-SRIB: Output pron: f ey s b uh k, i in loop: 0
08-30 12:37:15.809  9631  9711 V G2P-SRIB: After conversion: Gmail, Gmail, 5, 5
08-30 12:37:15.809  9631  9711 V G2P-SRIB: After g2p: prons 1, max_pron_len 9
08-30 12:37:15.809  9631  9711 V G2P-SRIB: Output pron: g m ey l, i in loop: 0
,08-30 12:37:15.809  9631  9711 V G2P-SRIB: After conversion: YouTube, YouTube, 7, 7
08-30 12:37:15.809  9631  9711 V G2P-SRIB: After g2p: prons 1, max_pron_len 12
08-30 12:37:15.809  9631  9711 V G2P-SRIB: Output pron: y uw t uw b, i in loop: 0
08-30 12:37:15.809  9631  9711 V G2P-SRIB: After conversion: diary, diary, 5, 5
08-30 12:37:15.809  9631  9711 V G2P-SRIB: After g2p: prons 1, max_pron_len 11
,08-30 12:37:15.809  9631  9711 V G2P-SRIB: Output pron: d ay er iy, i in loop: 0
08-30 12:37:15.809  9631  9711 V G2P-SRIB: After conversion: Camera, Camera, 6, 6
08-30 12:37:15.809  9631  9711 V G2P-SRIB: After g2p: prons 1, max_pron_len 13
08-30 12:37:15.809  9631  9711 V G2P-SRIB: Output pron: k ae m er ax, i in loop: 0
08-30 12:37:15.809  9631  9711 V G2P-SRIB: After conversion: Google, Google, 6, 6
,08-30 12:37:15.809  9631  9711 V G2P-SRIB: After g2p: prons 1, max_pron_len 12
08-30 12:37:15.809  9631  9711 V G2P-SRIB: Output pron: g uw g ax l, i in loop: 0
08-30 12:37:15.809  9631  9711 V G2P-SRIB: First char , last char 
08-30 12:37:15.809  9631  9711 V G2P-SRIB: Before UTF release deinit
08-30 12:37:15.809  9631  9711 V G2P-SRIB: Before g2p deinit
,08-30 12:37:15.809  9631  9711 D DictionaryGenerator:PocketSphinx: FileWriter is closed sucessfull
08-30 12:37:15.809  9631  9711 D DictionaryGenerator:PocketSphinx: DFG : COMPLETED in 60 ms.
,08-30 12:37:15.809  9631  9711 I DictionaryGenerator:PocketSphinx:OWC: DFG : Start
08-30 12:37:15.809  9631  9711 D DictionaryGenerator:PocketSphinx: Inside initFileWriter : Dict file name : /data/user/0/com.sec.svoice.lang.en_US/files/en_US/dict/contact.dict
08-30 12:37:15.809  9631  9711 I DictionaryGenerator:PocketSphinx: mDictionaryFile = { /data/user/0/com.sec.svoice.lang.en_US/files/en_US/dict/contact.dict }
08-30 12:37:15.809  9631  9711 D DictionaryGenerator:PocketSphinx: FileWriter created
08-30 12:37:15.809  9631  9711 D DictionaryGenerator:PocketSphinx: copying frm : /data/user/0/com.sec.svoice.lang.en_US/files/en_US/dict/contact.dict
08-30 12:37:15.809  9631  9711 D DictionaryGenerator:PocketSphinx: inside process_one_word_Call
08-30 12:37:15.809  9631  9711 D DictionaryGenerator:PocketSphinx: /data/user/0/com.sec.svoice.lang.en_US/databases
,08-30 12:37:15.809  9760  9760 W System  : ClassLoader referenced unknown path: /system/priv-app/SamsungCloud/lib/arm64
,08-30 12:37:15.819  9631  9711 D DictionaryGenerator:PocketSphinx::OWC: Deleted below entries : 
08-30 12:37:15.819  9631  9711 D DictionaryGenerator:PocketSphinx::OWC: Newly added entries are : 
08-30 12:37:15.819  9631  9711 V G2P-SRIB: Build date: Apr 28 2016, 15:00:24
08-30 12:37:15.819  9631  9711 V G2P-SRIB: enUS G2P libs
08-30 12:37:15.819  9631  9711 V G2P-SRIB: stringCount: 0
08-30 12:37:15.819  9631  9711 V G2P-SRIB: Config: lang: en-US
08-30 12:37:15.819  9631  9711 V G2P-SRIB: variant: mp
08-30 12:37:15.819  9631  9711 V G2P-SRIB: prefix: slot_contacts_start__
08-30 12:37:15.819  9631  9711 V G2P-SRIB: suffix: __slot_contacts_end
08-30 12:37:15.819  9631  9711 V G2P-SRIB: Options dump_pron: W W K K K K K K K K K K K K K W W,
08-30 12:37:15.819  9631  9711 V G2P-SRIB: First char , last char �
08-30 12:37:15.819  9631  9711 V G2P-SRIB: Before UTF release deinit
08-30 12:37:15.819  9631  9711 V G2P-SRIB: Before g2p deinit
,08-30 12:37:15.819  9631  9711 D DictionaryGenerator:PocketSphinx: FileWriter is closed sucessfull
08-30 12:37:15.819  9631  9711 D DictionaryGenerator:PocketSphinx:OWC: DFG : COMPLETED in 13 ms.
08-30 12:37:15.819  9631  9711 D PLMGenManager: TimeTaken for Dict & FSG generation 125ms
08-30 12:37:15.819  9631  9711 D etickcount:PocketSphinx Recognition Engine:  : VSP::TimeTaken for syncUserData 774ms
,08-30 12:37:15.829  9760  9760 I [SC]RequestProvider: onCreate() ~!! : com.samsung.android.scloud.framework.SamsungCloudApp@2ddf0fe
,08-30 12:37:15.829  9760  9760 I [SC]QuotaInterfaceManager: sync start
,08-30 12:37:15.829  9631  9711 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : #en_us_v2.0.6
08-30 12:37:15.829  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP::#en_us_v2.0.6
08-30 12:37:15.829  9631  9711 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : ##General
08-30 12:37:15.829  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP::##General
,08-30 12:37:15.829  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP::-hmm	am
08-30 12:37:15.829  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP::-fsg	lm/hero.detmin.fsg
08-30 12:37:15.829  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP::-fsg2	lm/hero.detmin.wo.wakeup.fsg
08-30 12:37:15.829  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP::-dict	dict/hero.dict
08-30 12:37:15.829  9631  9711 I eN66    : JNI Enter Function Java_com_asr_pocketsphinx_pocketsphinxJNI_Config_1setNLUCfg
08-30 12:37:15.829  9631  9711 I eN66    : Library build date: May  2 2016 @ 14:31:17
08-30 12:37:15.829  9631  9711 I eN66    : JNI Config_setNLUCfg /data/user/0/com.sec.svoice.lang.en_US/files/en_US/nlu/nlu.cfg
,08-30 12:37:15.829  9631  9711 I eN66    : JNI debug Config_setNLUCfg /data/user/0/com.sec.svoice.lang.en_US/files/en_US/nlu/nlu.cfg 1 time
08-30 12:37:15.829  9631  9711 I eN66    : JNI Exit Function Java_com_asr_pocketsphinx_pocketsphinxJNI_Config_1setNLUCfg
08-30 12:37:15.829  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP::-rnlu	nlu/nlu.cfg
08-30 12:37:15.829  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP::-maxwpf	4
08-30 12:37:15.829  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP::-maxhmmpf	1800
08-30 12:37:15.829  9631  9711 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : #-rawlogdir
08-30 12:37:15.829  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP::#-rawlogdir	log
08-30 12:37:15.829  9631  9711 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : 
,08-30 12:37:15.829  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP::
08-30 12:37:15.829  9631  9711 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : ##DNN
08-30 12:37:15.829  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP::##DNN
08-30 12:37:15.829  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP::-context	11
08-30 12:37:15.829  9631  9711 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : #quantization range
08-30 12:37:15.829  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP::#quantization range
08-30 12:37:15.829  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP::-QRange	1024
08-30 12:37:15.829  9631  9711 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : #1 means not skipped, 2 means skip every 2 frames
08-30 12:37:15.829  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP::#1 means not skipped, 2 means skip every 2 frames
08-30 12:37:15.829  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP::-frmskip	1
08-30 12:37:15.829  9631  9711 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : #quantized dnn binary file (not using dnn)
,08-30 12:37:15.829  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP::#quantized dnn binary file (not using dnn)
08-30 12:37:15.829  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP::-qdnn	am/qdnn.net
08-30 12:37:15.829  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP::-feat_transform	am/feat.bin
08-30 12:37:15.829  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP::-prior	am/prior_prob.out
08-30 12:37:15.829  9631  9711 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : 
08-30 12:37:15.829  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP::
08-30 12:37:15.829  9631  9711 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : ##Confidence score
08-30 12:37:15.829  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP::##Confidence score
,08-30 12:37:15.829  9631  9711 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : #-confs
08-30 12:37:15.829  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP::#-confs	yes
08-30 12:37:15.829  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP::-conf_use_senone	0
08-30 12:37:15.829  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP::-conf_use_pls	0
08-30 12:37:15.829  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP::-conf_use_ll	1
08-30 12:37:15.829  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP::-pip	1.5
,08-30 12:37:15.829  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP::-wip	7
08-30 12:37:15.829  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP::-lw	3
08-30 12:37:15.829  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP::-dnn_ascale	2.5
08-30 12:37:15.829  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP::-prior_ratio	0.92
08-30 12:37:15.829  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP::-conf_mapscore_params	[-42,0,-18,50,-4,100][9,0,28,50,57,100][-12,0,10,50,24,100]
08-30 12:37:15.829  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP::-non_speech_tied_states	[93:94:95]
08-30 12:37:15.829  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP::-conf_disagreement_percent	20.0
08-30 12:37:15.829  9631  9711 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : 
08-30 12:37:15.829  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP::
,08-30 12:37:15.829  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP::-conf_max_llr_th	25
08-30 12:37:15.829  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP::-conf_use_ci	no
08-30 12:37:15.829  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP::-bestpath	0
08-30 12:37:15.829  9631  9711 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : #now phoneloop score is not used phoneloop score => senon score
08-30 12:37:15.829  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP::#now phoneloop score is not used phoneloop score => senon score
08-30 12:37:15.829  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP::-pl_window	0
08-30 12:37:15.829  9631  9711 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : #excluding silence frames in score
08-30 12:37:15.829  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP::#excluding silence frames in score
,08-30 12:37:15.829  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP::-no_silence	1
08-30 12:37:15.829  9631  9711 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : #mapping parameter
08-30 12:37:15.829  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP::#mapping parameter
08-30 12:37:15.829  9631  9711 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : #-lang
08-30 12:37:15.829  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP::#-lang	1
08-30 12:37:15.829  9631  9711 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : #excluding score on WUW
08-30 12:37:15.829  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP::#excluding score on WUW
08-30 12:37:15.829  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP::-wake-up-cmd	1
,08-30 12:37:15.829  9631  9711 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : 
08-30 12:37:15.829  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP::
08-30 12:37:15.829  9631  9711 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : ##Rejection
08-30 12:37:15.829  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP::##Rejection
08-30 12:37:15.829  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP::-reject_list	lm/reject.hyp
08-30 12:37:15.829  9631  9711 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : 
08-30 12:37:15.829  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP::
08-30 12:37:15.829  9631  9711 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : ##Android related
08-30 12:37:15.829  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP::##Android related
,08-30 12:37:15.839  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP::-conf_thresh	49
08-30 12:37:15.839  9631  9711 D etickcount:PocketSphinx Recognition Engine:  : VSP::Previous state : INIT
08-30 12:37:15.839  9631  9711 I eN66    : JNI Enter Function Java_com_asr_pocketsphinx_pocketsphinxJNI_new_1Decoder_1_1SWIG_11
08-30 12:37:15.839  9631  9711 I eN66    : ps_reinit start
08-30 12:37:15.839  9631  9711 I eN66    : configured dir of hmm /data/user/0/com.sec.svoice.lang.en_US/files/en_US/am
08-30 12:37:15.839  9760  9760 I [SC]RequestProvider: uiregister - started.
08-30 12:37:15.839  9760  9760 I [SC]RequestProvider: quotaregister - started.
08-30 12:37:15.839  9760  9760 I [SC]ExternalOEMControlProvider: onCreate
08-30 12:37:15.839  9631  9711 I eN66    : ps_init_defaults end
,08-30 12:37:15.849  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:15.849  9760  9760 V SamsungCloudLogs:  set Log level [4->4]act[false]
,08-30 12:37:15.849  9760  9760 I [SC]CommonUtil: isSemAvailable:0
08-30 12:37:15.849  9760  9760 I [SC]SamsungCloudApp: AppVer[2.1.11][L:4]Sem[false]V2DEV_R slog[false]com.samsung.android.scloud
08-30 12:37:15.849  9760  9760 I [SC]SamsungCloudApp: controller allowed
,08-30 12:37:15.859  9760  9760 I [SC]MetaManager: MetaManager--[elapse:       1] Version Info[2.0.00]
,08-30 12:37:15.859  9760  9760 I [SC]FeatureManager: FeatureManager 
08-30 12:37:15.859  9760  9760 I [SC]FeatureManager: [SEC_FLOATING_FEATURE_SAMSUNGCLOUD_CONFIG_CLOUD_USAGE_MENU_TREE]str 
08-30 12:37:15.859  9760  9760 I [SC]FeatureManager: [SEC_FLOATING_FEATURE_SAMSUNGCLOUD_ENABLE_SETTING_MENU]bln true
08-30 12:37:15.859  9760  9760 I [SC]ModelManager: ModelManager++
,08-30 12:37:15.859  9760  9760 I [SC]CommonUtil: getClockPkgName pkg[com.sec.android.app.clockpackage] csc[]
08-30 12:37:15.859  9760  9760 I [SC]CommonUtil: getContactsPkgName pkg[com.android.contacts] csc[]
08-30 12:37:15.859  9760  9760 I [SC]CommonUtil: getMessagePkgName com.android.mms
,08-30 12:37:15.859  9760  9760 I [SC]CommonUtil: getEmailProviderPkgName com.samsung.android.email.provider
08-30 12:37:15.859  9760  9760 I [SC]CommonUtil: getCalendarPkgName com.android.calendar
,08-30 12:37:15.859  9760  9760 I [SC]CommonUtil: getMessagePkgName com.android.mms
08-30 12:37:15.859  9760  9760 I [SC]CommonUtil: getContactsPkgName pkg[com.android.contacts] csc[]
08-30 12:37:15.859  9760  9760 I [SC]CommonUtil: getCallPkgName com.android.incallui
08-30 12:37:15.859  9760  9760 I [SC]CommonUtil: getEmailProviderPkgName com.samsung.android.email.provider
,08-30 12:37:15.859  9760  9760 I [SC]Logs: [BaseModel]CALLLOGS                  logs                                               content://logs/historys
,08-30 12:37:15.869  9760  9760 I [SC]CommonUtil: isVoiceCallSupport : true
08-30 12:37:15.869  9760  9760 I [SC]ModelManager: addModel[+] CALLLOGS                  isEnable[true ] --:content://logs/historys::com.android.contacts
,08-30 12:37:15.869  9760  9760 I [SC]VIPList: [BaseModel]VIPLIST                   com.samsung.android.email.provider                 content://com.samsung.android.email.provider/viplist
08-30 12:37:15.869  9760  9760 I [SC]ModelManager: addModel[+] VIPLIST                   isEnable[true ] --:content://com.samsung.android.email.provider/viplist::com.samsung.android.email.provider
,08-30 12:37:15.869  4167  7724 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg com.google.android.googlequicksearchbox,id=10436,extra=Bundle[mParcelledData.dataSize=84]
08-30 12:37:15.869  9760  9760 I [SC]BlackList: [BaseModel]BLACKLIST                 com.samsung.android.email.provider                 content://com.samsung.android.email.provider/blacklist
08-30 12:37:15.869  4167  4167 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=10436, samsung.notification.type=normal, samsung.people.package_name=com.google.android.googlequicksearchbox}]
08-30 12:37:15.869  4167  4167 I PeopleStripeService: PeopleNotificationReceiver:3
08-30 12:37:15.869  9760  9760 I [SC]ModelManager: addModel[+] BLACKLIST                 isEnable[true ] --:content://com.samsung.android.email.provider/blacklist::com.samsung.android.email.provider
08-30 12:37:15.869  4167  4167 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
,08-30 12:37:15.869  4167  4167 I PeopleDataManager: removeNotification
08-30 12:37:15.869  4167  4167 I NotificationParser: getNotiType:com.google.android.googlequicksearchbox,null
08-30 12:37:15.869  4167  4167 D PeopleDataManager: removeNotiInfo: id =10436,packageName=com.google.android.googlequicksearchbox,isEdgeNotification=false,key=null,removeAll=false
08-30 12:37:15.869  4167  4167 D PeopleDataManager: removeNotiInfo =null
,08-30 12:37:15.869  9760  9760 I [SC]Spam: [BaseModel]SPAM                      mms-sms                                            content://mms-sms/spam-filter
08-30 12:37:15.869  9760  9760 I [SC]ModelManager: addModel[+] SPAM                      isEnable[true ] --:content://mms-sms/spam-filter::com.android.mms
,08-30 12:37:15.869  9760  9760 I [SC]CallReject: [BaseModel]CALLREJECT                com.android.phone.callsettings                     content://com.android.phone.callsettings/reject_num
,08-30 12:37:15.889  9760  9760 I [SC]CommonUtil: isVoiceCallSupport : true
08-30 12:37:15.889  9760  9760 I [SC]ModelManager: addModel[+] CALLREJECT                isEnable[true ] --:content://com.android.phone.callsettings/reject_num::com.android.incallui
,08-30 12:37:15.889  4444  9759 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 155 ms] updated apps [took 155 ms] 
08-30 12:37:15.889  9760  9760 I [SC]ConnectionsSetting: [BaseModel]CONNECTIONS               com.android.settings.accessibility.sharedaccessibility.backup content://com.android.settings.accessibility.sharedaccessibility.backup
,08-30 12:37:15.889  9760  9760 I [SC]ModelManager: addModel[+] CONNECTIONS               isEnable[false] --:content://com.android.settings.accessibility.sharedaccessibility.backup::com.android.settings
,08-30 12:37:15.899  9760  9760 I [SC]RingtoneSetting: [BaseModel]RINGTONESETTING           null                                               null
,08-30 12:37:15.899  9760  9760 I [SC]ModelManager: addModel[+] RINGTONESETTING           isEnable[true ] --:null::com.sec.android.app.ringtoneBR
,08-30 12:37:15.899  9760  9760 I [SC]Music: [BaseModel]MUSIC                     null                                               null
,08-30 12:37:15.899  9760  9760 I [SC]ModelManager: addModel[+] MUSIC                     isEnable[true ] --:null::com.samsung.android.scloud
,08-30 12:37:15.899  9760  9760 I [SC]Document: [BaseModel]DOCUMENT                  null                                               null
,08-30 12:37:15.899  9760  9760 I [SC]ModelManager: addModel[+] DOCUMENT                  isEnable[true ] --:null::com.samsung.android.scloud
,08-30 12:37:15.899  9760  9760 I [SC]Application: [BaseModel]APP                       null                                               null
,08-30 12:37:15.899  9760  9760 I [SC]ModelManager: addModel[+] APP                       isEnable[true ] --:null::com.samsung.android.scloud
,08-30 12:37:15.899  9760  9760 I [SC]Home: [BaseModel]HomescreenBackup          com.sec.android.app.launcher                       content://com.sec.android.app.launcher
,08-30 12:37:15.899  9760  9760 I [SC]ModelManager: addModel[+] HomescreenBackup          isEnable[true ] --:content://com.sec.android.app.launcher::com.sec.android.app.launcher
,08-30 12:37:15.909  9760  9760 W ResourcesManager: getTopLevelResources: /system/priv-app/VoiceNote_4.0/VoiceNote_4.0.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.sec.android.app.voicenote
,08-30 12:37:15.909  9760  9760 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:15.909  9760  9760 I [SC]ExternalOEMControl_VOICE: updateModelInfo() called, src[VOICE] cid[vMkD7IBgaR] isNew[true] dataType[null]
,08-30 12:37:15.909  9760  9760 I [SC]ExternalModel: [BaseModel]VOICE                     com.sec.android.app.voicenote                      content://com.sec.android.app.voicenote.backup
08-30 12:37:15.909  9760  9760 I [SC]ExternalModel: duplicateConfig[0] : true
08-30 12:37:15.909  9760  9760 I [SC]ExternalModel: duplicateConfig[1] : false
08-30 12:37:15.909  9760  9760 I [SC]ModelManager: addModel[+] VOICE                     isEnable[true ] V2:content://com.sec.android.app.voicenote.backup::com.sec.android.app.voicenote
08-30 12:37:15.909  9760  9760 I [SC]ModelManager: loadExternalModelsFromPkg[VOICE                                        ] pkg:com.sec.android.app.voicenote                 register[IFileClient:vMkD7IBgaR]
,08-30 12:37:15.909  9760  9760 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.samsung.android.email.provider
,08-30 12:37:15.919  9631  9711 I eN66    : 
08-30 12:37:15.919  9631  9711 I eN66    : FSG model <n66_cmd_eng> is loaded
,08-30 12:37:15.919  9760  9760 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:15.919  9760  9760 I [SC]ExternalOEMControlLegacy_Email: updateModelInfo() called, src[Email] cid[QJ5JBlRnP9] isNew[true]
08-30 12:37:15.919  9760  9760 I [SC]ExternalModelLegacy: [BaseModel]Email                     com.samsung.android.email.provider                 content://com.samsung.android.email.provider.backup[Q]
08-30 12:37:15.919  9760  9760 I [SC]ModelManager: addModel[+] Email                     isEnable[true ] V1:content://com.samsung.android.email.provider.backup::com.samsung.android.email.provider:[Q]
08-30 12:37:15.919  9760  9760 I [SC]ModelManager: loadExternalModelsFromPkg[Email                                        ] pkg:com.samsung.android.email.provider            register[ISCloudQBNRClient:QJ5JBlRnP9]
,08-30 12:37:15.919  9760  9760 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.sec.android.app.sbrowser
,08-30 12:37:15.919  9760  9760 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:15.919  9760  9760 I [SC]ExternalOEMControlLegacy_SBROWSERSETTING: updateModelInfo() called, src[SBROWSERSETTING] cid[kw8vqQFzo3] isNew[true]
,08-30 12:37:15.919  9760  9760 I [SC]ExternalModelLegacy: [BaseModel]SBROWSERSETTING           com.sec.android.app.sbrowser                       content://com.sec.android.app.sbrowser.backup[Q]
08-30 12:37:15.919  9760  9760 I [SC]ModelManager: addModel[+] SBROWSERSETTING           isEnable[true ] V1:content://com.sec.android.app.sbrowser.backup::com.sec.android.app.sbrowser:[Q]
08-30 12:37:15.919  9760  9760 I [SC]ModelManager: loadExternalModelsFromPkg[SBROWSERSETTING                              ] pkg:com.sec.android.app.sbrowser                  register[ISCloudQBNRClient:kw8vqQFzo3]
,08-30 12:37:15.919  9760  9760 W ResourcesManager: getTopLevelResources: /system/priv-app/SVoice_1.0/SVoice_1.0.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.samsung.voiceserviceplatform
,08-30 12:37:15.929  9760  9760 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:15.929  9760  9760 I [SC]ExternalOEMControlLegacy_SVOICESETTING: updateModelInfo() called, src[SVOICESETTING] cid[bLEmzxKOex] isNew[true]
,08-30 12:37:15.929  9760  9760 I [SC]ExternalModelLegacy: [BaseModel]SVOICESETTING             com.samsung.voiceserviceplatform                   content://com.samsung.voiceserviceplatform.backup[Q]
08-30 12:37:15.929  9760  9760 I [SC]ModelManager: addModel[+] SVOICESETTING             isEnable[true ] V1:content://com.samsung.voiceserviceplatform.backup::com.samsung.voiceserviceplatform:[Q]
08-30 12:37:15.929  9760  9760 I [SC]ModelManager: loadExternalModelsFromPkg[SVOICESETTING                                ] pkg:com.samsung.voiceserviceplatform              register[ISCloudQBNRClient:bLEmzxKOex]
,08-30 12:37:15.929  9760  9760 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M/SPlanner_M.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.android.calendar
,08-30 12:37:15.929  9760  9760 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:15.929  9760  9760 I [SC]ExternalOEMControlLegacy_CALENDARSETTING: updateModelInfo() called, src[CALENDARSETTING] cid[ztQlGIvsvZ] isNew[true]
,08-30 12:37:15.929  9760  9760 I [SC]ExternalModelLegacy: [BaseModel]CALENDARSETTING           com.android.calendar                               content://com.android.calendar.backup[Q]
08-30 12:37:15.929  9760  9760 I [SC]ModelManager: addModel[+] CALENDARSETTING           isEnable[true ] V1:content://com.android.calendar.backup::com.android.calendar:[Q]
08-30 12:37:15.929  9760  9760 I [SC]ModelManager: loadExternalModelsFromPkg[CALENDARSETTING                              ] pkg:com.android.calendar                          register[ISCloudQBNRClient:ztQlGIvsvZ]
,08-30 12:37:15.929  9760  9760 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.android.settings
,08-30 12:37:15.939  9760  9760 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:15.939  9631  9711 I eN66    : 
08-30 12:37:15.939  9631  9711 I eN66    : ps_reinit : Secondary FSG model <n66_cmd_eng> is loaded
08-30 12:37:15.939  9631  9711 I eN66    : 
08-30 12:37:15.939  9631  9711 I eN66    : ps_reinit : Current active FSG model is <n66_cmd_eng>
,08-30 12:37:15.939  9631  9711 I eN66    : Decoder initialization is complete
08-30 12:37:15.939  9631  9711 I eN66    : JNI Exit Function Java_com_asr_pocketsphinx_pocketsphinxJNI_new_1Decoder_1_1SWIG_11 Instance -191912992
08-30 12:37:15.939  9760  9760 I [SC]ExternalOEMControlLegacy_ACCESSIBILITYSETTINGS: updateModelInfo() called, src[ACCESSIBILITYSETTINGS] cid[X6qErjsfs2] isNew[true]
08-30 12:37:15.939  9760  9760 I [SC]ExternalModelLegacy: [BaseModel]ACCESSIBILITYSETTINGS     com.android.settings                               content://com.android.settings.accessibility.sharedaccessibility.backup[Q]
08-30 12:37:15.939  9760  9760 I [SC]ModelManager: addModel[+] ACCESSIBILITYSETTINGS     isEnable[true ] V1:content://com.android.settings.accessibility.sharedaccessibility.backup::com.android.settings:[Q]
08-30 12:37:15.939  9760  9760 I [SC]ModelManager: loadExternalModelsFromPkg[ACCESSIBILITYSETTINGS                        ] pkg:com.android.settings                          register[ISCloudQBNRClient:X6qErjsfs2]
08-30 12:37:15.939  9760  9760 I [SC]ModelManager: loadExternalModelsFromPkg[CONNECTIONS                                  ] pkg:com.android.settings                          subKey[CONNECTIONS]
,08-30 12:37:15.939  9760  9760 I [SC]ConnectionsSetting: CONNECTIONS               setEnable[true]
08-30 12:37:15.939  9760  9760 I [SC]ModelManager: loadExternalModelsFromPkg[CONNECTIONS                                  ] pkg:com.android.settings                          subKey[WiFi]
08-30 12:37:15.939  9760  9760 I [SC]ConnectionsSetting: CONNECTIONS               setEnable[true]
08-30 12:37:15.939  9631  9711 I etickcount:PocketSphinx Recognition Engine:  : VSP::State changed to READY
08-30 12:37:15.939  9631  9711 D etickcount:PocketSphinx Recognition Engine:  : VSP::TimeTaken for Decoder init 115ms
08-30 12:37:15.939  9631  9711 D etickcount:PocketSphinx Recognition Engine:  : VSP::Total Load time 987ms
,08-30 12:37:15.939  9760  9760 W ResourcesManager: getTopLevelResources: /system/priv-app/TouchWizHome_2016/TouchWizHome_2016.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.sec.android.app.launcher
,08-30 12:37:15.939  9760  9760 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:15.939  9760  9760 E [SC]SCLOUD_ERR-CommonUtil: getCertificateSHA1Fingerprint err :com.samsung.android.scloud.backupsamplecode 
08-30 12:37:15.939  9760  9760 I [SC]ModelManager: loadExternalModelsFromPkg pkg:com.samsung.android.scloud.backupsamplecode   NotExist[null]
,08-30 12:37:15.949  9760  9760 W ResourcesManager: getTopLevelResources: /system/priv-app/TeleService/TeleService.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.android.phone
,08-30 12:37:15.949  9760  9760 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:15.949  9760  9760 I [SC]ExternalOEMControlLegacy_CALLSETTING: updateModelInfo() called, src[CALLSETTING] cid[IHLhQxraiP] isNew[true]
08-30 12:37:15.949  9760  9760 I [SC]ExternalModelLegacy: [BaseModel]CALLSETTING               com.android.phone                                  content://com.android.phone.backup[Q]
,08-30 12:37:15.949  9760  9760 I [SC]ModelManager: addModel[+] CALLSETTING               isEnable[true ] V1:content://com.android.phone.backup::com.android.phone:[Q]
08-30 12:37:15.949  9760  9760 I [SC]ModelManager: loadExternalModelsFromPkg[CALLSETTING                                  ] pkg:com.android.phone                             register[ISCloudQBNRClient:IHLhQxraiP]
,08-30 12:37:15.949  9760  9760 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.sec.android.inputmethod
,08-30 12:37:15.949  9760  9760 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:15.949  9760  9760 I [SC]ExternalOEMControlLegacy_IMESETTING: updateModelInfo() called, src[IMESETTING] cid[ghXxWAP1aK] isNew[true]
,08-30 12:37:15.949  9760  9760 I [SC]ExternalModelLegacy: [BaseModel]IMESETTING                com.sec.android.inputmethod                        content://com.sec.android.inputmethod.backup[Q]
08-30 12:37:15.949  9760  9760 I [SC]ModelManager: addModel[+] IMESETTING                isEnable[true ] V1:content://com.sec.android.inputmethod.backup::com.sec.android.inputmethod:[Q]
08-30 12:37:15.949  9760  9760 I [SC]ModelManager: loadExternalModelsFromPkg[IMESETTING                                   ] pkg:com.sec.android.inputmethod                   register[ISCloudQBNRClient:ghXxWAP1aK]
,08-30 12:37:15.959  9760  9760 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.android.contacts
,08-30 12:37:15.959  9760  9760 D ResourcesManager: For user 0 new overlays fetched Null
08-30 12:37:15.959  9760  9760 I [SC]ExternalOEMControlLegacy_MyProfile: updateModelInfo() called, src[MyProfile] cid[2yOE2P9maz] isNew[true]
08-30 12:37:15.959  9760  9760 I [SC]ExternalModelLegacy: [BaseModel]MyProfile                 com.android.contacts                               content://com.samsung.contacts.backup
08-30 12:37:15.959  9760  9760 I [SC]ModelManager: addModel[+] MyProfile                 isEnable[true ] V1:content://com.samsung.contacts.backup::com.android.contacts:
08-30 12:37:15.959  9760  9760 I [SC]ModelManager: loadExternalModelsFromPkg[MyProfile                                    ] pkg:com.android.contacts                          register[ISCloudBNRClient:2yOE2P9maz]
08-30 12:37:15.959  9760  9760 I [SC]ExternalOEMControlLegacy_CONTACTSETTING: updateModelInfo() called, src[CONTACTSETTING] cid[jqwmo66Bdc] isNew[true]
08-30 12:37:15.959  9760  9760 I [SC]ExternalModelLegacy: [BaseModel]CONTACTSETTING            com.android.contacts                               content://com.samsung.contacts.backup[Q]
08-30 12:37:15.959  9760  9760 I [SC]ModelManager: addModel[+] CONTACTSETTING            isEnable[true ] V1:content://com.samsung.contacts.backup::com.android.contacts:[Q]
08-30 12:37:15.959  9760  9760 I [SC]ModelManager: loadExternalModelsFromPkg[CONTACTSETTING                               ] pkg:com.android.contacts                          register[ISCloudQBNRClient:jqwmo66Bdc]
08-30 12:37:15.959  9760  9760 I [SC]ExternalOEMControl_CONTACT: updateModelInfo() called, src[CONTACT] cid[2vInYbEf2V] isNew[true] dataType[json]
08-30 12:37:15.959  9760  9760 I [SC]ExternalModel: [BaseModel]CONTACT                   com.android.contacts                               content://com.samsung.contacts.backup
08-30 12:37:15.959  9760  9760 I [SC]ModelManager: addModel[+] CONTACT                   isEnable[true ] V2:content://com.samsung.contacts.backup::com.android.contacts
08-30 12:37:15.959  9760  9760 I [SC]ModelManager: loadExternalModelsFromPkg[CONTACT                                      ] pkg:com.android.contacts                          register[IRecordClient:2vInYbEf2V]
08-30 12:37:15.959  9760  9760 I [SC]ModelManager: loadExternalModelsFromPkg[HomescreenBackup                             ] pkg:com.android.contacts                          subKey[HomescreenContactShortcut]
08-30 12:37:15.959  9760  9760 W ResourcesManager: getTopLevelResources: /system/app/ClockPackage_M/ClockPackage_M.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.sec.android.app.clockpackage
08-30 12:37:15.959  9760  9760 D ResourcesManager: For user 0 new overlays fetched Null
08-30 12:37:15.959  9760  9760 I [SC]ExternalOEMControlLegacy_Alarm: updateModelInfo() called, src[Alarm] cid[v5VJ0Ep6EE] isNew[true]
08-30 12:37:15.959  9760  9760 I [SC]ExternalModelLegacy: [BaseModel]Alarm                     com.sec.android.app.clockpackage                   content://com.sec.android.app.clockpackage
,08-30 12:37:15.959  9760  9760 I [SC]ModelManager: addModel[+] Alarm                     isEnable[true ] V1:content://com.sec.android.app.clockpackage::com.sec.android.app.clockpackage:
08-30 12:37:15.959  9760  9760 I [SC]ModelManager: loadExternalModelsFromPkg[Alarm                                        ] pkg:com.sec.android.app.clockpackage              register[ISCloudBNRClient:v5VJ0Ep6EE]
08-30 12:37:15.959  9760  9760 I [SC]ExternalOEMControlLegacy_WorldClock: updateModelInfo() called, src[WorldClock] cid[pYz7p28bSl] isNew[true]
08-30 12:37:15.959  9760  9760 I [SC]ExternalModelLegacy: [BaseModel]WorldClock                com.sec.android.app.clockpackage                   content://com.sec.android.app.clockpackage
08-30 12:37:15.959  9760  9760 I [SC]ModelManager: addModel[+] WorldClock                isEnable[true ] V1:content://com.sec.android.app.clockpackage::com.sec.android.app.clockpackage:
08-30 12:37:15.959  9760  9760 I [SC]ModelManager: loadExternalModelsFromPkg[WorldClock                                   ] pkg:com.sec.android.app.clockpackage              register[ISCloudBNRClient:pYz7p28bSl]
08-30 12:37:15.959  9760  9760 I [SC]ModelManager: loadExternalModelsFromPkg[HomescreenBackup                             ] pkg:com.sec.android.app.clockpackage              subKey[ALARMWIDGET]
08-30 12:37:15.969  9760  9760 I [SC]ModelManager: loadExternalModelsFromPkg[HomescreenBackup                             ] pkg:com.sec.android.app.clockpackage              subKey[DUALCLOCKWIDGET]
,08-30 12:37:15.969  9760  9760 W ResourcesManager: getTopLevelResources: /system/priv-app/SecCalendarProvider_NOTSTICKER/SecCalendarProvider_NOTSTICKER.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.android.providers.calendar
,08-30 12:37:15.969  9760  9760 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:15.969  9760  9760 I [SC]ExternalOEMControl_EVENT: updateModelInfo() called, src[EVENT] cid[qsoHwGCEEw] isNew[true] dataType[json]
,08-30 12:37:15.969  9760  9760 I [SC]ExternalModel: [BaseModel]EVENT                     com.android.providers.calendar                     content://com.samsung.android.providers.calendar.backup
08-30 12:37:15.969  9760  9760 I [SC]ModelManager: addModel[+] EVENT                     isEnable[true ] V2:content://com.samsung.android.providers.calendar.backup::com.android.providers.calendar
08-30 12:37:15.969  9760  9760 I [SC]ModelManager: loadExternalModelsFromPkg[EVENT                                        ] pkg:com.android.providers.calendar                register[IRecordClient:qsoHwGCEEw]
08-30 12:37:15.969  9760  9760 I [SC]ExternalOEMControl_TASK: updateModelInfo() called, src[TASK] cid[cLT79jJ29l] isNew[true] dataType[json]
08-30 12:37:15.969  9760  9760 I [SC]ExternalModel: [BaseModel]TASK                      com.android.providers.calendar                     content://com.samsung.android.providers.calendar.backup
,08-30 12:37:15.969  9760  9760 I [SC]ModelManager: addModel[+] TASK                      isEnable[true ] V2:content://com.samsung.android.providers.calendar.backup::com.android.providers.calendar
08-30 12:37:15.969  9760  9760 I [SC]ModelManager: loadExternalModelsFromPkg[TASK                                         ] pkg:com.android.providers.calendar                register[IRecordClient:cLT79jJ29l]
,08-30 12:37:15.969  9760  9760 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Epic_Common/SecMms_Epic_Common.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.android.mms
,08-30 12:37:15.969  9760  9760 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:15.969  9760  9760 I [SC]ExternalOEMControlLegacy_MessagesSettings: updateModelInfo() called, src[MessagesSettings] cid[XUHtHcYNfq] isNew[true]
08-30 12:37:15.969  9760  9760 I [SC]ExternalModelLegacy: [BaseModel]MessagesSettings          com.android.mms                                    content://com.samsung.mms.settings.backup[Q]
,08-30 12:37:15.969  9760  9760 I [SC]ModelManager: addModel[+] MessagesSettings          isEnable[true ] V1:content://com.samsung.mms.settings.backup::com.android.mms:[Q]
08-30 12:37:15.969  9760  9760 I [SC]ModelManager: loadExternalModelsFromPkg[MessagesSettings                             ] pkg:com.android.mms                               register[ISCloudQBNRClient:XUHtHcYNfq]
,08-30 12:37:15.979  9760  9760 W ResourcesManager: getTopLevelResources: /system/priv-app/SecTelephonyProvider_Epic/SecTelephonyProvider_Epic.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.android.providers.telephony
,08-30 12:37:15.979  9760  9760 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:15.979  9760  9760 I [SC]ExternalOEMControlLegacy_Chat: updateModelInfo() called, src[Chat] cid[nx7Fde25jd] isNew[true]
,08-30 12:37:15.979  4300  4613 I [PDLIB]ClientProvider, VERSION : 2.2.0: call !!  method : getClientInfo, arg : Chat
,08-30 12:37:15.979  4300  4613 D TP/BnRUtils: getCscFreeMessage(), config = off
08-30 12:37:15.979  4300  4613 D TP/BnRUtils: getEnableSupportBackup() = false
08-30 12:37:15.979  4300  4613 I [PDLIB]BNRClientHelper-Chat: GET_CLIENT_INFO, Chat
,08-30 12:37:15.979  9760  9760 I [SC]ExternalOEMControlLegacy_Chat: updateModelInfo() supportBnr is false
08-30 12:37:15.979  9760  9760 I [SC]ExternalOEMControlLegacy_FileTransfer: updateModelInfo() called, src[FileTransfer] cid[LyxMGTa8W3] isNew[true]
,08-30 12:37:15.979  4300  4658 I [PDLIB]ClientProvider, VERSION : 2.2.0: call !!  method : getClientInfo, arg : FileTransfer
08-30 12:37:15.979  4300  4658 D TP/BnRUtils: getCscFreeMessage(), config = off
,08-30 12:37:15.979  4300  4658 D TP/BnRUtils: getEnableSupportBackup() = false
08-30 12:37:15.979  4300  4658 I [PDLIB]BNRClientHelper-FileTransfer: GET_CLIENT_INFO, FileTransfer
,08-30 12:37:15.979  9760  9760 I [SC]ExternalOEMControlLegacy_FileTransfer: updateModelInfo() supportBnr is false
08-30 12:37:15.979  9760  9760 I [SC]ExternalOEMControl_SMS: updateModelInfo() called, src[SMS] cid[N0iXqXm9oM] isNew[true] dataType[json]
,08-30 12:37:15.979  9760  9760 I [SC]ExternalModel: [BaseModel]SMS                       com.android.providers.telephony                    content://com.android.providers.telephony.backup
08-30 12:37:15.979  9760  9760 I [SC]ModelManager: addModel[+] SMS                       isEnable[true ] V2:content://com.android.providers.telephony.backup::com.android.providers.telephony
08-30 12:37:15.979  9760  9760 I [SC]ModelManager: loadExternalModelsFromPkg[SMS                                          ] pkg:com.android.providers.telephony               register[IRecordClient:N0iXqXm9oM]
08-30 12:37:15.979  9760  9760 I [SC]ExternalOEMControl_MMS: updateModelInfo() called, src[MMS] cid[I7o6E6m1Lj] isNew[true] dataType[json]
08-30 12:37:15.979  9760  9760 I [SC]ExternalModel: [BaseModel]MMS                       com.android.providers.telephony                    content://com.android.providers.telephony.backup
08-30 12:37:15.989  9760  9760 I [SC]ModelManager: addModel[+] MMS                       isEnable[true ] V2:content://com.android.providers.telephony.backup::com.android.providers.telephony
08-30 12:37:15.989  9760  9760 I [SC]ModelManager: loadExternalModelsFromPkg[MMS                                          ] pkg:com.android.providers.telephony               register[IRecordClient:I7o6E6m1Lj]
,08-30 12:37:15.989  9760  9760 W ResourcesManager: getTopLevelResources: /system/app/WeatherWidget2016/WeatherWidget2016.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.sec.android.daemonapp
,08-30 12:37:15.989  9760  9760 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:15.989  9760  9760 I [SC]ExternalOEMControlLegacy_WEATHERWIDGET: updateModelInfo() called, src[WEATHERWIDGET] cid[oo2JSUuSBb] isNew[true]
,08-30 12:37:15.989  9760  9760 I [SC]ExternalModelLegacy: [BaseModel]WEATHERWIDGET             com.sec.android.daemonapp                          content://com.sec.android.daemonapp.backup[Q]
08-30 12:37:15.989  9760  9760 I [SC]ModelManager: addModel[+] WEATHERWIDGET             isEnable[true ] V1:content://com.sec.android.daemonapp.backup::com.sec.android.daemonapp:[Q]
08-30 12:37:15.989  9760  9760 I [SC]ModelManager: loadExternalModelsFromPkg[WEATHERWIDGET                                ] pkg:com.sec.android.daemonapp                     register[ISCloudQBNRClient:oo2JSUuSBb]
08-30 12:37:15.989  9760  9760 I [SC]ModelManager: loadExternalModelsFromPkg[elapse:      86]
08-30 12:37:15.989  9760  9760 I [SC]ModelManager: ModelManager--[elapse:     133]
,08-30 12:37:15.999  9760  9760 D InjectionManager: InjectionManager
,08-30 12:37:15.999  9760  9760 D InjectionManager: fillFeatureStoreMap com.samsung.android.scloud
08-30 12:37:15.999  9760  9760 I InjectionManager: Constructor com.samsung.android.scloud, Feature store :{}
08-30 12:37:15.999  9760  9760 I InjectionManager: featureStore :{}
,08-30 12:37:15.999  9760  9760 I [SC]SCloudReceiver: onReceive : android.intent.action.PACKAGE_ADDED
,08-30 12:37:16.009  9782  9782 E Zygote  : v2
08-30 12:37:16.009  9782  9782 I libpersona: KNOX_SDCARD checking this for 1000
08-30 12:37:16.009  9782  9782 I libpersona: KNOX_SDCARD not a persona
08-30 12:37:16.009  9782  9782 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,08-30 12:37:16.009  9782  9782 E Zygote  : accessInfo : 0
,08-30 12:37:16.019  3431  3982 I ActivityManager: Start proc 9782:com.samsung.android.bbc.bbcagent/1000 for broadcast-3 com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver
,08-30 12:37:16.019  3431  3982 I ActivityManager: Killing 9208:com.sec.spp.push:RemoteNotiProcess/u0a42 (adj 15): DHA:empty #33
,08-30 12:37:16.029  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:16.029  9782  9782 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 12:37:16.029  9782  9782 D ActivityThread: Added TimaKeyStore provider
,08-30 12:37:16.049  3431  4925 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d234ec u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{899f573 9782:com.samsung.android.bbc.bbcagent/1000}
,08-30 12:37:16.049  3431  3451 D ActivityManager: isAutoRunBlockedApp:: com.sec.spp.push, Auto Run ON
,08-30 12:37:16.059  9782  9782 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
08-30 12:37:16.059  9782  9782 D RelationGraph: garbageCollect()
,08-30 12:37:16.059  9782  9782 W ResourcesManager: getTopLevelResources: /system/app/BBCAgent/BBCAgent.apk / 1.0 running in com.samsung.android.bbc.bbcagent rsrc of package com.samsung.android.bbc.bbcagent
,08-30 12:37:16.059  3431  3982 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,08-30 12:37:16.059  9782  9782 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,08-30 12:37:16.059  9782  9782 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:16.059  9782  9782 I InjectionManager: Inside getClassLibPath caller 
,08-30 12:37:16.069  9782  9782 W System  : ClassLoader referenced unknown path: /system/app/BBCAgent/lib/arm64
,08-30 12:37:16.069  9782  9782 D InjectionManager: InjectionManager
,08-30 12:37:16.069  9782  9782 D InjectionManager: fillFeatureStoreMap com.samsung.android.bbc.bbcagent
08-30 12:37:16.069  9782  9782 I InjectionManager: Constructor com.samsung.android.bbc.bbcagent, Feature store :{}
08-30 12:37:16.069  9782  9782 I InjectionManager: featureStore :{}
,08-30 12:37:16.089  9794  9794 E Zygote  : v2
08-30 12:37:16.089  9794  9794 I libpersona: KNOX_SDCARD checking this for 10098
08-30 12:37:16.089  9794  9794 I libpersona: KNOX_SDCARD not a persona
08-30 12:37:16.089  9794  9794 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,08-30 12:37:16.089  9794  9794 E Zygote  : accessInfo : 0
08-30 12:37:16.089  9794  9794 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.docs 
08-30 12:37:16.089  3431  4925 I ActivityManager: Start proc 9794:com.google.android.apps.docs/u0a98 for broadcast-3 com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,08-30 12:37:16.099  3431  4925 I ActivityManager: Killing 9223:com.sec.android.Kies/1000 (adj 15): DHA:empty #33
,08-30 12:37:16.109  9794  9794 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 12:37:16.109  9794  9794 D ActivityThread: Added TimaKeyStore provider
,08-30 12:37:16.119  3431  3450 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.Kies, Auto Run ON
,08-30 12:37:16.119  3431  3909 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/37_task.xml.bak
,08-30 12:37:16.129  3431  4399 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d234ec u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c48bc30 9794:com.google.android.apps.docs/u0a98}
,08-30 12:37:16.139  9794  9794 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,08-30 12:37:16.139  9794  9794 D RelationGraph: garbageCollect()
,08-30 12:37:16.139  9794  9794 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package com.google.android.apps.docs
,08-30 12:37:16.149  3431  4747 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
08-30 12:37:16.149  9794  9794 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,08-30 12:37:16.149  9794  9794 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:16.149  9794  9794 I InjectionManager: Inside getClassLibPath caller 
,08-30 12:37:16.159  9794  9794 W System  : ClassLoader referenced unknown path: /system/app/Drive/lib/arm64
,08-30 12:37:16.209  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:16.389  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:16.409  9794  9808 I GAv4    : Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
08-30 12:37:16.409  9794  9808 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-30 12:37:16.409  9794  9808 I GAv4    :   adb logcat -s GAv4
,08-30 12:37:16.539  9794  9808 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package com.google.android.apps.docs
,08-30 12:37:16.539  3431  4925 V AlarmManager:  remove PendingIntent] PendingIntent{5b56b5c: PendingIntentRecord{a1cee65 com.google.android.apps.docs broadcastIntent}}
,08-30 12:37:16.539  9794  9808 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-30 12:37:16.539  4228  9713 D FusedRequestManager: manageLocationRequest, new fused (NO_POWER) request from com.samsung.voiceserviceplatform with 10043_NOPOWER through GooglePlayService
,08-30 12:37:16.549  9794  9808 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-30 12:37:16.559  9794  9812 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-30 12:37:16.569  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:16.629  3431  6509 D GameManagerService: identifyGamePackage. com.test.thalitest
,08-30 12:37:16.649  9794  9794 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.apps.docs/cache/docs_glide
,08-30 12:37:16.659  9794  9808 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db
08-30 12:37:16.659  9794  9808 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-journal
08-30 12:37:16.659  9794  9808 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-shm
08-30 12:37:16.659  9794  9808 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-wal
,08-30 12:37:16.689  9794  9794 D InjectionManager: InjectionManager
08-30 12:37:16.699  9794  9794 D InjectionManager: fillFeatureStoreMap com.google.android.apps.docs
,08-30 12:37:16.699  9794  9794 I InjectionManager: Constructor com.google.android.apps.docs, Feature store :{}
08-30 12:37:16.699  9794  9794 I InjectionManager: featureStore :{}
,08-30 12:37:16.739  8585  8608 I ReschedulableTimer: [#CMH#] ReschedulableTimer started 
,08-30 12:37:16.749  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:16.779  9817  9817 E Zygote  : v2
08-30 12:37:16.779  9817  9817 I libpersona: KNOX_SDCARD checking this for 1000
08-30 12:37:16.779  9817  9817 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
08-30 12:37:16.779  9817  9817 I libpersona: KNOX_SDCARD not a persona
,08-30 12:37:16.779  9817  9817 E Zygote  : accessInfo : 0
08-30 12:37:16.779  3431  4985 I ActivityManager: Start proc 9817:com.samsung.android.app.filterinstaller/1000 for broadcast-3 com.samsung.android.app.filterinstaller/.PackageIntentReceiver
,08-30 12:37:16.779  3431  4985 I ActivityManager: Killing 9236:com.samsung.android.app.simplesharing/5011 (adj 15): DHA:empty #33
,08-30 12:37:16.809  9817  9817 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 12:37:16.809  9817  9817 D ActivityThread: Added TimaKeyStore provider
,08-30 12:37:16.809  3159  4493 V MediaPlayerService: Client(6) destructor pid = 9236
08-30 12:37:16.809  3159  4493 V MediaPlayerService: disconnect(6) from pid 9236
08-30 12:37:16.809  3159  4493 D NuPlayerDriver: reset(0xf154c6c0)
08-30 12:37:16.809  3159  4493 D NuPlayerDriver: notifyListener_l(0xf154c6c0), (8, 0, 0)
,08-30 12:37:16.809  3159  9255 V NuPlayer: kWhatReset
08-30 12:37:16.809  3159  9255 V NuPlayer: performReset
08-30 12:37:16.809  3159  9255 V GenericSource: stop()
08-30 12:37:16.809  3159  9255 V GenericSource: PREPARE_CANCELLED set to true
08-30 12:37:16.809  3159  9255 V GenericSource: [Flag] set 0x40 -> mFlags = 0x48
08-30 12:37:16.809  3159  9255 V GenericSource: [Flag] clear 0x8 -> mFlags = 0x40
08-30 12:37:16.809  3159  9255 V GenericSource: stop() end
08-30 12:37:16.809  3159  9255 V GenericSource: ~GenericSource()
,08-30 12:37:16.809  3159  9255 I OggExtractor: OggSource::stop() mExtractor ref count = 2
08-30 12:37:16.809  3159  9255 I OggExtractor: ~OggSource --
08-30 12:37:16.809  3159  9255 D NuPlayerDriver: notifyResetComplete(0xf154c6c0)
08-30 12:37:16.809  3159  4493 V NuPlayerDriver: ~NuPlayerDriver(0xf154c6c0)
,08-30 12:37:16.819  3159  4493 I OggExtractor: ~OggExtractor ++
08-30 12:37:16.819  3159  4493 I OggExtractor: ~MyOggExtractor ++ 
,08-30 12:37:16.819  3159  4493 I OggExtractor: ~MyOggExtractor --
08-30 12:37:16.819  3159  4493 I OggExtractor: ~OggExtractor --
08-30 12:37:16.819  3159  4493 V AudioSink: +++ close
08-30 12:37:16.819  3159  4493 V AudioSink: --- close
,08-30 12:37:16.819  3431  4128 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d234ec u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8f30be1 9817:com.samsung.android.app.filterinstaller/1000}
,08-30 12:37:16.829  3431  3450 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.simplesharing, Auto Run ON
,08-30 12:37:16.829  9817  9817 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
08-30 12:37:16.829  9817  9817 D RelationGraph: garbageCollect()
,08-30 12:37:16.839  9817  9817 W ResourcesManager: getTopLevelResources: /system/app/FilterInstaller/FilterInstaller.apk / 1.0 running in com.samsung.android.app.filterinstaller rsrc of package com.samsung.android.app.filterinstaller
,08-30 12:37:16.839  3431  4985 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,08-30 12:37:16.839  9817  9817 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,08-30 12:37:16.839  9817  9817 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:16.839  9817  9817 I InjectionManager: Inside getClassLibPath caller 
,08-30 12:37:16.839  9794  9809 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in com.google.android.apps.docs rsrc of package com.google.android.gms
,08-30 12:37:16.849  9817  9817 W System  : ClassLoader referenced unknown path: /system/app/FilterInstaller/lib/arm64
,08-30 12:37:16.849  9817  9817 D InjectionManager: InjectionManager
08-30 12:37:16.849  9817  9817 D InjectionManager: fillFeatureStoreMap com.samsung.android.app.filterinstaller
,08-30 12:37:16.849  9817  9817 I InjectionManager: Constructor com.samsung.android.app.filterinstaller, Feature store :{}
08-30 12:37:16.849  9817  9817 I InjectionManager: featureStore :{}
,08-30 12:37:16.849  9817  9817 E FilterPackageIntentReceiver: This package is not a effect filter
,08-30 12:37:16.849  9794  9809 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:16.849  9794  9809 I InjectionManager: Inside getClassLibPath caller 
,08-30 12:37:16.859  9832  9832 E Zygote  : v2
08-30 12:37:16.859  9832  9832 I libpersona: KNOX_SDCARD checking this for 10110
08-30 12:37:16.859  9832  9832 I libpersona: KNOX_SDCARD not a persona
08-30 12:37:16.859  9832  9832 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,08-30 12:37:16.869  9832  9832 E Zygote  : accessInfo : 0
08-30 12:37:16.869  3431  4985 I ActivityManager: Start proc 9832:com.sec.android.widgetapp.samsungapps/u0a110 for broadcast-3 com.sec.android.widgetapp.samsungapps/.PackageChangeReceiver
08-30 12:37:16.869  9832  9832 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.sec.android.widgetapp.samsungapps 
,08-30 12:37:16.869  3431  4985 I ActivityManager: Killing 9178:com.samsung.android.app.assistantmenu/1000 (adj 15): DHA:empty #33
,08-30 12:37:16.879  9832  9832 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 12:37:16.879  9832  9832 D ActivityThread: Added TimaKeyStore provider
,08-30 12:37:16.889  3431  4326 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.assistantmenu, Auto Run ON
,08-30 12:37:16.889  4588  7826 I Icing   : Indexing 5C970AF099F6E45AC5F7CE88D00EDBB4B63BF8D6 from com.google.android.googlequicksearchbox
,08-30 12:37:16.899  9794  9809 W System  : ClassLoader referenced unknown path: /system/priv-app/GmsCore/lib/arm64
,08-30 12:37:16.899  3431  4650 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d234ec u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e20cd06 9832:com.sec.android.widgetapp.samsungapps/u0a110}
,08-30 12:37:16.909  9832  9832 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
08-30 12:37:16.909  9832  9832 D RelationGraph: garbageCollect()
,08-30 12:37:16.909  9832  9832 W ResourcesManager: getTopLevelResources: /system/app/GalaxyAppsWidget_Phone_Hero/GalaxyAppsWidget_Phone_Hero.apk / 1.0 running in com.sec.android.widgetapp.samsungapps rsrc of package com.sec.android.widgetapp.samsungapps
,08-30 12:37:16.909  9832  9832 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
08-30 12:37:16.909  3431  4399 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,08-30 12:37:16.909  9832  9832 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:16.919  9832  9832 I InjectionManager: Inside getClassLibPath caller 
,08-30 12:37:16.919  9832  9832 W System  : ClassLoader referenced unknown path: /system/app/GalaxyAppsWidget_Phone_Hero/lib/arm64
,08-30 12:37:16.929  9832  9832 D InjectionManager: InjectionManager
08-30 12:37:16.929  9832  9832 D InjectionManager: fillFeatureStoreMap com.sec.android.widgetapp.samsungapps
08-30 12:37:16.929  9832  9832 I InjectionManager: Constructor com.sec.android.widgetapp.samsungapps, Feature store :{}
08-30 12:37:16.929  9832  9832 I InjectionManager: featureStore :{}
,08-30 12:37:16.929  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:16.939  9845  9845 E Zygote  : v2
08-30 12:37:16.939  9845  9845 I libpersona: KNOX_SDCARD checking this for 10111
08-30 12:37:16.939  9845  9845 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
08-30 12:37:16.939  9845  9845 I libpersona: KNOX_SDCARD not a persona
,08-30 12:37:16.939  9845  9845 E Zygote  : accessInfo : 0
08-30 12:37:16.939  9845  9845 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.enhance.gameservice 
08-30 12:37:16.939  3431  4399 I ActivityManager: Start proc 9845:com.enhance.gameservice/u0a111 for broadcast-3 com.enhance.gameservice/.GameServiceReceiver
,08-30 12:37:16.949  3431  4399 I ActivityManager: Killing 9286:com.android.calendar/u0a144 (adj 15): DHA:empty #33
,08-30 12:37:16.969  9845  9845 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 12:37:16.969  9845  9845 D ActivityThread: Added TimaKeyStore provider
,08-30 12:37:16.969  9794  9809 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-30 12:37:16.969  3431  4326 D ActivityManager: isAutoRunBlockedApp:: com.android.calendar, Auto Run ON
,08-30 12:37:16.979  4588  7826 I Icing   : Indexing done 5C970AF099F6E45AC5F7CE88D00EDBB4B63BF8D6
,08-30 12:37:16.979  9794  9809 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-30 12:37:16.979  3431  4128 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d234ec u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b134fc7 9845:com.enhance.gameservice/u0a111}
,08-30 12:37:16.989  9845  9845 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
08-30 12:37:16.989  9845  9845 D RelationGraph: garbageCollect()
,08-30 12:37:16.989  9845  9845 W ResourcesManager: getTopLevelResources: /system/app/GameOptimizer/GameOptimizer.apk / 1.0 running in com.enhance.gameservice rsrc of package com.enhance.gameservice
,08-30 12:37:16.989  3431  4326 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,08-30 12:37:16.989  9845  9845 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,08-30 12:37:16.999  9845  9845 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:16.999  9845  9845 I InjectionManager: Inside getClassLibPath caller 
,08-30 12:37:16.999  9845  9845 W System  : ClassLoader referenced unknown path: /system/app/GameOptimizer/lib/arm64
,08-30 12:37:16.999  9845  9845 D InjectionManager: InjectionManager
08-30 12:37:16.999  9845  9845 D InjectionManager: fillFeatureStoreMap com.enhance.gameservice
,08-30 12:37:16.999  9845  9845 I InjectionManager: Constructor com.enhance.gameservice, Feature store :{}
08-30 12:37:16.999  9845  9845 I InjectionManager: featureStore :{}
,08-30 12:37:17.009  9845  9857 I DatabaseHelper: android.app.Application@a61305f
08-30 12:37:17.009  9845  9857 I DatabaseHelper: Create a DatabaseHelper
,08-30 12:37:17.019  9845  9857 W RequestHeader: java.lang.StringIndexOutOfBoundsException: length=0; regionStart=0; regionLength=3
,08-30 12:37:17.019  3431  3855 I ActivityManager: Start proc 9859:com.samsung.android.app.mirrorlink/1000 for broadcast-3 com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener
,08-30 12:37:17.029  9859  9859 E Zygote  : v2
08-30 12:37:17.029  9859  9859 I libpersona: KNOX_SDCARD checking this for 1000
08-30 12:37:17.029  9859  9859 I libpersona: KNOX_SDCARD not a persona
,08-30 12:37:17.029  9859  9859 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,08-30 12:37:17.029  9859  9859 E Zygote  : accessInfo : 0
,08-30 12:37:17.029  9845  9857 I DataManager: checkResolution
08-30 12:37:17.029  9845  9857 I DataManager: Create a DataManager
,08-30 12:37:17.039  9845  9857 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-30 12:37:17.039  9845  9857 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 12:37:17.039  3151  3635 D EnterpriseController: netId is 0
,08-30 12:37:17.039  3151  3635 D Netd    : getNetworkForDns: using netid 502 for uid 10111
,08-30 12:37:17.039  9859  9859 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 12:37:17.039  9859  9859 D ActivityThread: Added TimaKeyStore provider
,08-30 12:37:17.049  3431  4327 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d234ec u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6b3851d 9859:com.samsung.android.app.mirrorlink/1000}
,08-30 12:37:17.059  9859  9859 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,08-30 12:37:17.059  9859  9859 D RelationGraph: garbageCollect()
,08-30 12:37:17.059  9859  9859 W ResourcesManager: getTopLevelResources: /system/app/MirrorLink/MirrorLink.apk / 1.0 running in com.samsung.android.app.mirrorlink rsrc of package com.samsung.android.app.mirrorlink
,08-30 12:37:17.059  3431  4399 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
08-30 12:37:17.059  9859  9859 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,08-30 12:37:17.059  9859  9859 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:17.069  9859  9859 I InjectionManager: Inside getClassLibPath caller 
,08-30 12:37:17.069  9859  9859 W System  : ClassLoader referenced unknown path: /system/app/MirrorLink/lib/arm
,08-30 12:37:17.089  9859  9859 D InjectionManager: InjectionManager
,08-30 12:37:17.089  9859  9859 D InjectionManager: fillFeatureStoreMap com.samsung.android.app.mirrorlink
08-30 12:37:17.089  9859  9859 I InjectionManager: Constructor com.samsung.android.app.mirrorlink, Feature store :{}
08-30 12:37:17.089  9859  9859 I InjectionManager: featureStore :{}
,08-30 12:37:17.089  9859  9859 D AcmsPackageEventListener: action2:android.intent.action.PACKAGE_ADDED
08-30 12:37:17.089  9859  9859 D AcmsPackageEventListener: pkgName:com.test.thalitest ,10177
,08-30 12:37:17.099  3431  4327 I ActivityManager: Killing 9066:com.samsung.faceservice/5004 (adj 15): DHA:empty #33
,08-30 12:37:17.099  3431  4327 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d234ec u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6553dab 4907:com.microsoft.skydrive/u0a130}
,08-30 12:37:17.109  4907  4907 V ApplicationReceiver: 2016-08-30 10:37:17-null-Application install message is received ver:1.1.10
,08-30 12:37:17.109  4907  4907 V ApplicationReceiver: 2016-08-30 10:37:17-null-Installing:package:com.test.thalitest ver:1.1.10
,08-30 12:37:17.109  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:17.119  8585  8585 I ServiceManager: [#CMH#] Disconnected to Service  com.samsung.faceservice.FaceService
,08-30 12:37:17.119  9872  9872 E Zygote  : v2
08-30 12:37:17.119  9872  9872 E Zygote  : isSdpEnabledProcess - SDP enabled
08-30 12:37:17.119  9872  9872 I libpersona: KNOX_SDCARD checking this for 10141
08-30 12:37:17.119  9872  9872 I libpersona: KNOX_SDCARD not a persona
,08-30 12:37:17.119  9872  9872 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,08-30 12:37:17.119  9872  9872 E Zygote  : accessInfo : 64
08-30 12:37:17.119  9872  9872 E Zygote  : isSdpEnabledProcess - SDP enabled
08-30 12:37:17.119  9872  9872 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10141 / [uid]: 10141
08-30 12:37:17.119  9872  9872 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.sbrowser 
,08-30 12:37:17.129  3431  4985 I ActivityManager: Start proc 9872:com.sec.android.app.sbrowser/u0a141 for broadcast-3 com.sec.android.app.sbrowser/.preferences.ContentBlockerReceiver
,08-30 12:37:17.139  3431  4925 D ActivityManager: isAutoRunBlockedApp:: com.samsung.faceservice, Auto Run ON
08-30 12:37:17.139  3431  4925 W ActivityManager: Scheduling restart of crashed service com.samsung.faceservice/.FaceService in 1000ms
,08-30 12:37:17.139  9872  9872 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 12:37:17.139  9872  9872 D ActivityThread: Added TimaKeyStore provider
,08-30 12:37:17.149  3431  4326 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d234ec u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e6cb392 9872:com.sec.android.app.sbrowser/u0a141}
,08-30 12:37:17.159  9872  9872 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
08-30 12:37:17.159  9872  9872 D RelationGraph: garbageCollect()
,08-30 12:37:17.159  9872  9872 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package com.sec.android.app.sbrowser
,08-30 12:37:17.159  3431  3982 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,08-30 12:37:17.159  9872  9872 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,08-30 12:37:17.159  9872  9872 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:17.169  9872  9872 I InjectionManager: Inside getClassLibPath caller 
,08-30 12:37:17.179  9872  9872 W System  : ClassLoader referenced unknown path: /system/app/SBrowser_4_LATEST/lib/arm
,08-30 12:37:17.179  9872  9872 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package com.sec.android.app.sbrowser
,08-30 12:37:17.179  9872  9872 D ManifestProvider: onCreate()
,08-30 12:37:17.189  9872  9872 I SBrowserUtils: getSystemProperty of sales_code : XEO
08-30 12:37:17.189  9872  9872 I SBrowserUtils: getSystemProperty of country_code : Poland
,08-30 12:37:17.189  9872  9872 I SBrowserUtils: getSystemProperty of country_code : Poland
08-30 12:37:17.189  9872  9872 I SBrowserUtils: getSystemProperty of countryiso_code : PL
,08-30 12:37:17.189  9872  9872 V SBrowserContentProviderUtility: enableSyncClientProivder is called!
,08-30 12:37:17.189  9872  9872 D [MM]MHDataBaseProvider: onCreate()
,08-30 12:37:17.209  9872  9872 D ApplicationStatus: initialize application (com.sec.android.app.sbrowser.common.SBrowserMobileApplication@d005b2c)
,08-30 12:37:17.209  9872  9872 D InjectionManager: InjectionManager
,08-30 12:37:17.209  9872  9872 D InjectionManager: fillFeatureStoreMap com.sec.android.app.sbrowser
08-30 12:37:17.209  9872  9872 I InjectionManager: Constructor com.sec.android.app.sbrowser, Feature store :{}
08-30 12:37:17.209  9872  9872 I InjectionManager: featureStore :{}
,08-30 12:37:17.219  3431  4327 I ActivityManager: Killing 8610:com.samsung.enhanceservice/5004 (adj 15): DHA:empty #33
,08-30 12:37:17.219  3431  4327 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d234ec u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{11934b6 5090:com.sec.imsservice/1000}
,08-30 12:37:17.229  8585  8585 I ServiceManager: [#CMH#] Disconnected to Service  com.samsung.enhanceservice.EnhanceService
,08-30 12:37:17.229  3431  4650 D ActivityManager: isAutoRunBlockedApp:: com.samsung.enhanceservice, Auto Run ON
,08-30 12:37:17.229  3431  4650 W ActivityManager: Scheduling restart of crashed service com.samsung.enhanceservice/.EnhanceService in 10905ms
,08-30 12:37:17.249  9887  9887 E Zygote  : v2
08-30 12:37:17.249  9887  9887 I libpersona: KNOX_SDCARD checking this for 10016
08-30 12:37:17.249  9887  9887 I libpersona: KNOX_SDCARD not a persona
08-30 12:37:17.259  9887  9887 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,08-30 12:37:17.259  9887  9887 E Zygote  : accessInfo : 0
08-30 12:37:17.259  9887  9887 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.sec.android.app.samsungapps 
,08-30 12:37:17.259  3431  4327 I ActivityManager: Start proc 9887:com.sec.android.app.samsungapps/u0a16 for broadcast-3 com.sec.android.app.samsungapps/.MyPackageReplacedReceiver
,08-30 12:37:17.269  9887  9887 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 12:37:17.269  9887  9887 D ActivityThread: Added TimaKeyStore provider
,08-30 12:37:17.279  3431  4925 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d234ec u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7eb2163 9887:com.sec.android.app.samsungapps/u0a16}
,08-30 12:37:17.289  9887  9887 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,08-30 12:37:17.289  9887  9887 D RelationGraph: garbageCollect()
,08-30 12:37:17.289  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
08-30 12:37:17.289  9887  9887 W ResourcesManager: getTopLevelResources: /data/app/com.sec.android.app.samsungapps-1/base.apk / 1.0 running in com.sec.android.app.samsungapps rsrc of package com.sec.android.app.samsungapps
,08-30 12:37:17.289  3431  4470 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,08-30 12:37:17.289  9887  9887 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,08-30 12:37:17.289  9887  9887 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:17.299  9887  9887 I InjectionManager: Inside getClassLibPath caller 
,08-30 12:37:17.299  9887  9887 W System  : ClassLoader referenced unknown path: /data/app/com.sec.android.app.samsungapps-1/lib/arm64
,08-30 12:37:17.309  9887  9887 D InjectionManager: InjectionManager
08-30 12:37:17.309  9887  9887 D InjectionManager: fillFeatureStoreMap com.sec.android.app.samsungapps
,08-30 12:37:17.309  9887  9887 I InjectionManager: Constructor com.sec.android.app.samsungapps, Feature store :{}
08-30 12:37:17.309  9887  9887 I InjectionManager: featureStore :{}
,08-30 12:37:17.329  9900  9900 E Zygote  : v2
08-30 12:37:17.329  9900  9900 I libpersona: KNOX_SDCARD checking this for 10103
08-30 12:37:17.329  9900  9900 I libpersona: KNOX_SDCARD not a persona
08-30 12:37:17.329  9900  9900 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,08-30 12:37:17.329  9900  9900 E Zygote  : accessInfo : 0
08-30 12:37:17.329  9900  9900 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.facebook.appmanager 
,08-30 12:37:17.329  3431  4925 I ActivityManager: Start proc 9900:com.facebook.appmanager/u0a103 for broadcast-3 com.facebook.appmanager/com.facebook.oxygen.appmanager.common.packages.PackageReceiver
,08-30 12:37:17.329  3431  4925 I ActivityManager: Killing 8622:com.samsung.dcmservice/5004 (adj 15): DHA:empty #33
,08-30 12:37:17.339  8585  8585 I ServiceManager: [#CMH#] Disconnected to Service  com.samsung.dcmservice.DCMService
,08-30 12:37:17.339  9900  9900 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 12:37:17.339  9900  9900 D ActivityThread: Added TimaKeyStore provider
,08-30 12:37:17.349  3431  4326 D ActivityManager: isAutoRunBlockedApp:: com.samsung.dcmservice, Auto Run ON
08-30 12:37:17.349  3431  4326 W ActivityManager: Scheduling restart of crashed service com.samsung.dcmservice/.DCMService in 20792ms
,08-30 12:37:17.359  3431  3982 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d234ec u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8db9160 9900:com.facebook.appmanager/u0a103}
,08-30 12:37:17.369  9900  9900 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
08-30 12:37:17.369  9900  9900 D RelationGraph: garbageCollect()
,08-30 12:37:17.369  9900  9900 W ResourcesManager: getTopLevelResources: /data/app/com.facebook.appmanager-1/base.apk / 1.0 running in com.facebook.appmanager rsrc of package com.facebook.appmanager
,08-30 12:37:17.369  3431  4925 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,08-30 12:37:17.369  9900  9900 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,08-30 12:37:17.369  9900  9900 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:17.369  9900  9900 I InjectionManager: Inside getClassLibPath caller 
,08-30 12:37:17.389  9900  9900 D ACRA    : ACRA init; reportURL: https://www.facebook.com/mobile/generic_android_crash_logs/659091980805095
,08-30 12:37:17.389  9900  9900 D ACRA    : ACRA is enabled for com.facebook.appmanager, intializing...
,08-30 12:37:17.389  9900  9900 V fb-UnpackingSoSource: locked dso store /data/user/0/com.facebook.appmanager/lib-main
,08-30 12:37:17.389  9900  9900 I fb-UnpackingSoSource: dso store is up-to-date: /data/user/0/com.facebook.appmanager/lib-main
08-30 12:37:17.389  9900  9900 V fb-UnpackingSoSource: releasing dso store lock for /data/user/0/com.facebook.appmanager/lib-main
,08-30 12:37:17.409  9900  9900 W com.facebook.appmanager:co: Verify
,08-30 12:37:17.409  9900  9900 D InjectionManager: InjectionManager
,08-30 12:37:17.409  9900  9900 D InjectionManager: fillFeatureStoreMap com.facebook.appmanager
08-30 12:37:17.409  9900  9900 I InjectionManager: Constructor com.facebook.appmanager, Feature store :{}
08-30 12:37:17.409  9900  9900 I InjectionManager: featureStore :{}
,08-30 12:37:17.439  9917  9917 E Zygote  : v2
08-30 12:37:17.439  9917  9917 I libpersona: KNOX_SDCARD checking this for 10014
08-30 12:37:17.439  9917  9917 I libpersona: KNOX_SDCARD not a persona
08-30 12:37:17.439  9917  9917 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,08-30 12:37:17.439  9917  9917 E Zygote  : accessInfo : 0
08-30 12:37:17.439  9917  9917 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.facebook.system 
,08-30 12:37:17.439  3431  4399 I ActivityManager: Start proc 9917:com.facebook.system/u0a14 for broadcast-3 com.facebook.system/com.facebook.oxygen.installer.service.PackageReceiver
,08-30 12:37:17.459  9917  9917 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 12:37:17.459  9917  9917 D ActivityThread: Added TimaKeyStore provider
,08-30 12:37:17.469  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:17.469  3431  3982 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d234ec u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c9722ea 9917:com.facebook.system/u0a14}
,08-30 12:37:17.469  3431  4650 I ActivityManager: Killing 9054:com.samsung.ipservice/5004 (adj 15): DHA:empty #33
,08-30 12:37:17.479  9917  9917 D RelationGraph: garbageCollect()
08-30 12:37:17.479  9917  9917 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,08-30 12:37:17.479  9917  9917 W ResourcesManager: getTopLevelResources: /data/app/com.facebook.system-1/base.apk / 1.0 running in com.facebook.system rsrc of package com.facebook.system
,08-30 12:37:17.479  3431  4985 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
08-30 12:37:17.479  9917  9917 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,08-30 12:37:17.479  9917  9917 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:17.489  8585  8585 I ServiceManager: [#CMH#] Disconnected to Service  com.samsung.ipservice.IPService
08-30 12:37:17.489  9917  9917 I InjectionManager: Inside getClassLibPath caller 
,08-30 12:37:17.489  9917  9917 W System  : ClassLoader referenced unknown path: /data/app/com.facebook.system-1/lib/arm64
,08-30 12:37:17.489  3431  4326 D PackageManager: setEnabledSetting : userId = 0 packageName = com.facebook.appmanager cmp = com.facebook.oxygen.appmanager.crashmanager.CrashManagerActivity newState = 2 callingPackage = 10103
08-30 12:37:17.489  3431  3982 D ActivityManager: isAutoRunBlockedApp:: com.samsung.ipservice, Auto Run ON
,08-30 12:37:17.489  3431  3982 W ActivityManager: Scheduling restart of crashed service com.samsung.ipservice/.IPService in 30648ms
,08-30 12:37:17.499  3431  4650 D PackageManager: setEnabledSetting : userId = 0 packageName = com.facebook.appmanager cmp = com.facebook.oxygen.appmanager.firstparty.tos.ShouldShowTos newState = 2 callingPackage = 10103
,08-30 12:37:17.499  9917  9917 D InjectionManager: InjectionManager
,08-30 12:37:17.499  9917  9917 D InjectionManager: fillFeatureStoreMap com.facebook.system
08-30 12:37:17.499  9917  9917 I InjectionManager: Constructor com.facebook.system, Feature store :{}
08-30 12:37:17.499  9917  9917 I InjectionManager: featureStore :{}
,08-30 12:37:17.499  3431  4747 D PackageManager: setEnabledSetting : userId = 0 packageName = com.facebook.appmanager cmp = com.facebook.oxygen.appmanager.nekodirect.NekoDirectService newState = 2 callingPackage = 10103
,08-30 12:37:17.509  3431  4327 D PackageManager: setEnabledSetting : userId = 0 packageName = com.facebook.appmanager cmp = com.facebook.oxygen.appmanager.nekodirect.progress.ProgressContentProvider newState = 2 callingPackage = 10103
,08-30 12:37:17.509  9936  9936 E Zygote  : v2
08-30 12:37:17.509  9936  9936 I libpersona: KNOX_SDCARD checking this for 10039
08-30 12:37:17.509  9936  9936 I libpersona: KNOX_SDCARD not a persona
08-30 12:37:17.509  9936  9936 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,08-30 12:37:17.509  9936  9936 E Zygote  : accessInfo : 0
08-30 12:37:17.509  9936  9936 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.sec.android.app.shealth 
08-30 12:37:17.509  3431  4608 I ActivityManager: Start proc 9936:com.sec.android.app.shealth/u0a39 for broadcast-3 com.sec.android.app.shealth/com.samsung.android.app.shealth.serviceframework.partner.PluginBroadcastReceiver
,08-30 12:37:17.509  3431  4608 I ActivityManager: Killing 8585:com.samsung.cmh:CMH/5004 (adj 15): DHA:empty #33
,08-30 12:37:17.529  9900  9933 E ActivityThread: Failed to find provider info for com.facebook.appmanager.oxygen.nekodirect.progress
,08-30 12:37:17.529  9936  9936 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 12:37:17.529  9936  9936 D ActivityThread: Added TimaKeyStore provider
,08-30 12:37:17.529  3431  3855 E GameManagerService: remoteCallback died, callback: com.samsung.android.game.IGameManagerCallback$Stub$Proxy@3f959db, cookie: null
,08-30 12:37:17.539  3431  4128 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4ee2c78 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7c5af51 9936:com.sec.android.app.shealth/u0a39}
,08-30 12:37:17.539  9936  9936 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
08-30 12:37:17.539  9936  9936 D RelationGraph: garbageCollect()
,08-30 12:37:17.539  9936  9936 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.sec.android.app.shealth rsrc of package com.sec.android.app.shealth
,08-30 12:37:17.549  3431  4470 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
08-30 12:37:17.549  9936  9936 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,08-30 12:37:17.549  9936  9936 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:17.549  3431  4326 D ActivityManager: isAutoRunBlockedApp:: com.samsung.cmh, Auto Run ON
,08-30 12:37:17.549  8661  8661 I StoryService: [StoryService] On destroy() 
,08-30 12:37:17.549  8661  8661 I ServiceController: [StoryService] shutdown() 
,08-30 12:37:17.549  9936  9936 I InjectionManager: Inside getClassLibPath caller 
,08-30 12:37:17.559  9936  9936 W System  : ClassLoader referenced unknown path: /system/priv-app/SHealth4/lib/arm64
,08-30 12:37:17.559  9936  9936 I MultiDex: VM with version 2.1.0 has multidex support
08-30 12:37:17.559  9936  9936 I MultiDex: install
08-30 12:37:17.559  9936  9936 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-30 12:37:17.559  9936  9936 I MultiDex: install
08-30 12:37:17.559  9936  9936 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-30 12:37:17.569  9936  9936 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.sec.android.app.shealth rsrc of package com.sec.android.app.shealth
,08-30 12:37:17.569  3431  4128 I ActivityManager: Killing 8160:com.android.providers.calendar/u0a50 (adj 15): DHA:empty #33
,08-30 12:37:17.599  3431  4985 D ActivityManager: isAutoRunBlockedApp:: com.android.providers.calendar, Auto Run ON
,08-30 12:37:17.619  9936  9936 D InjectionManager: InjectionManager
08-30 12:37:17.619  9936  9936 D InjectionManager: fillFeatureStoreMap com.sec.android.app.shealth
,08-30 12:37:17.619  9936  9936 I InjectionManager: Constructor com.sec.android.app.shealth, Feature store :{}
08-30 12:37:17.619  9936  9936 I InjectionManager: featureStore :{}
,08-30 12:37:17.619  9936  9936 D HealthDataStore: Service for HealthDataStore is connected
,08-30 12:37:17.619  9936  9936 D HealthDataStore: HealthConnectionErrorResult code : 9
,08-30 12:37:17.629  3431  4327 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4ee2c78 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{defbca3 8449:com.sec.android.app.shealth:remote/u0a39}
,08-30 12:37:17.629  9936  9936 D HealthConsole: Service for HealthDataConsole is connected
,08-30 12:37:17.639  9936  9936 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
,08-30 12:37:17.639  9936  9936 E HealthDataStore: disconnectService: Context instance is invalid
,08-30 12:37:17.639  3431  4128 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4ee2c78 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{defbca3 8449:com.sec.android.app.shealth:remote/u0a39}
,08-30 12:37:17.649  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:17.659  3431  4608 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{93df789 u-1 android.intent.action.CHECK_SIOP_LEVEL qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{321a496 9392:com.samsung.android.scloud:contentsync/5009}
,08-30 12:37:17.659  9392  9392 I [SC]DetectorReceiver: onReceive [android.intent.action.CHECK_SIOP_LEVEL]
,08-30 12:37:17.659  9392  9392 I [SC]CloudManager: requestInit
,08-30 12:37:17.659  9392  9392 I [SC]Utils: folder : cachecreate fail, try again.
,08-30 12:37:17.659  9392  9392 I [SC]Utils: folder : cache create fail.
,08-30 12:37:17.659  9392  9392 I [SC]Utils: folder : thumbnailcreate fail, try again.
08-30 12:37:17.659  9392  9392 I [SC]Utils: folder : thumbnail create fail.
08-30 12:37:17.659  9392  9392 I [SC]Utils: folder : sharecreate fail, try again.
08-30 12:37:17.659  9392  9392 I [SC]Utils: folder : share create fail.
,08-30 12:37:17.659  9392  9392 I [SC]Utils: folder : scratchcreate fail, try again.
08-30 12:37:17.659  9392  9392 I [SC]Utils: folder : scratch create fail.
08-30 12:37:17.659  9392  9392 I [SC]Utils: folder : eventSynccreate fail, try again.
,08-30 12:37:17.659  9392  9392 I [SC]Utils: folder : eventSync create fail.
,08-30 12:37:17.669  9408  9419 I SA      : [SCU] isHaveSA() - false
08-30 12:37:17.669  9408  9419 I SA      : [OCP] Samsung account is not Signed-in
,08-30 12:37:17.679  9408  9419 I SA      : [OCP] Delete DB (TNC data)
,08-30 12:37:17.679  9392  9392 I [SC]CommonUtil: Samsung Account Not Logged in
,08-30 12:37:17.679  3431  3982 I ActivityManager: Killing 8661:com.samsung.storyservice/5004 (adj 15): DHA:empty #33
,08-30 12:37:17.689  3431  3982 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{dc4538e u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{69d497c 5079:com.samsung.android.providers.context/u0a9}
,08-30 12:37:17.709  3431  3982 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{be107af u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{69d497c 5079:com.samsung.android.providers.context/u0a9}
,08-30 12:37:17.719  3431  4399 D ActivityManager: isAutoRunBlockedApp:: com.samsung.storyservice, Auto Run ON
,08-30 12:37:17.829  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:17.969  3431  6545 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-30 12:37:18.009  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:18.189  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:18.369  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:18.549  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:18.609  3431  5111 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
08-30 12:37:18.609  3431  5111 V MARsPolicyManager: updateSMDBValues
,08-30 12:37:18.609  3431  3548 E MARsDBManager: updateDBAll : begin --size 1
,08-30 12:37:18.639  3431  3548 E MARsDBManager: updateDBAll : end
,08-30 12:37:18.639  3431  3548 D MARsDBManager: onChange - mSmartManagerObserver! Uri = content://com.samsung.android.sm/AppFreezer?MARs-self=true&MARs=true
,08-30 12:37:18.729  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:18.909  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:19.089  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:19.269  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:19.269  9631  9638 I eN66    : JNI Enter Function Java_com_asr_pocketsphinx_pocketsphinxJNI_delete_1Config
08-30 12:37:19.269  9631  9638 I eN66    : JNI Exit Function Java_com_asr_pocketsphinx_pocketsphinxJNI_delete_1Config
,08-30 12:37:19.449  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:19.609  9657  9664 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+user+0+com_samsung_svoice_sync+databases+svoicelocal_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,08-30 12:37:19.629  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:19.729  3431  6509 D N       : limitCPUFreq:: freq = 2496000
,08-30 12:37:19.729  3431  6509 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MAX_LIMIT  frequency : 2496000  uid : 1000  pid : 3431  pkgName : SIOP_ARM_MAX@22
,08-30 12:37:19.739  3431  6509 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-30 12:37:19.809  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:19.989  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:20.169  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:20.349  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:20.529  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:20.709  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:20.889  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:21.069  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:21.249  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:21.429  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:21.609  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:21.789  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:21.969  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:22.149  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:22.329  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:22.509  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:22.549  9558  9718 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-30 12:37:22.549  9558  9718 I jxcore-log: 
,08-30 12:37:22.549  9558  9718 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-30 12:37:22.549  9558  9718 I jxcore-log: 
,08-30 12:37:22.559  9558  9718 D BluetoothAdapter: STATE_ON
,08-30 12:37:22.559  9558  9718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:37:22.559  9558  9718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:37:22.559  9558  9718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:37:22.559  9558  9718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:37:22.559  9558  9718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:37:22.559  9558  9718 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:37:22.559  9558  9718 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:37:22.559  9558  9718 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 12:37:22.559  9558  9718 D BluetoothAdapter: STATE_ON
,08-30 12:37:22.559  9558  9718 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 12:37:22.559  9558  9718 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 12:37:22.559  9558  9718 I jxcore-log: 
,08-30 12:37:22.559  9558  9718 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 12:37:22.559  9558  9718 I jxcore-log: 
,08-30 12:37:22.689  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:22.719  9558  9718 I jxcore-log: Running unit tests
08-30 12:37:22.719  9558  9718 I jxcore-log: 
,08-30 12:37:22.719  9558  9718 E JX-Cordova: JavaCall recevied a call for unknown method ExecuteNativeTests
08-30 12:37:22.719  9558  9718 I jxcore-log: Failed to execute UT.
08-30 12:37:22.719  9558  9718 I jxcore-log: 
08-30 12:37:22.719  9558  9718 I jxcore-log: Unit Test app is loaded
08-30 12:37:22.719  9558  9718 I jxcore-log: 
,08-30 12:37:22.719  9558  9718 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:37:22.719  9558  9718 I jxcore-log: 
,08-30 12:37:22.729  9558  9718 I jxcore-log: My device name is: samsung-SM-G935F
08-30 12:37:22.729  9558  9718 I jxcore-log: 
,08-30 12:37:22.729  9558  9718 I jxcore-log: WARN testUtils: myNameCallback not set!
08-30 12:37:22.729  9558  9718 I jxcore-log: 
,08-30 12:37:22.739  9558  9558 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-30 12:37:22.869  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:22.969  3431  6545 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-30 12:37:23.049  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:23.159  3431  3582 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-30 12:37:23.179  3431  3582 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-30 12:37:23.229  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:23.409  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:23.589  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:23.769  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:23.819  9558  9718 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-30 12:37:23.819  9558  9718 I jxcore-log: 
,08-30 12:37:23.949  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:24.019  9558  9718 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-30 12:37:24.019  9558  9718 I jxcore-log: 
,08-30 12:37:24.019  3431  4327 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-30 12:37:24.019  3431  4327 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4325, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
08-30 12:37:24.019  3431  4327 D BatteryService: online:4, current avg:-202, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-209
,08-30 12:37:24.019  3431  4327 D BatteryService: stay LED for fully charged
08-30 12:37:24.019  3431  3431 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-30 12:37:24.019  3431  3431 I MotionRecognitionService: Plugged
,08-30 12:37:24.029  3431  3431 D MotionRecognitionService:   cableConnection= 1
08-30 12:37:24.029  3431  3431 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-30 12:37:24.029  3431  3431 D MotionRecognitionService: skip setTransmitPower. 
,08-30 12:37:24.029  9558  9718 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-30 12:37:24.029  9558  9718 I jxcore-log: 
,08-30 12:37:24.029  3431  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,08-30 12:37:24.029  3951  3951 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,08-30 12:37:24.039  3951  3951 D PowerUI : priorPlugType = 2 mPlugType =  2
08-30 12:37:24.039  3951  3951 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-30 12:37:24.049  5090  5090 D CommonServiceConfiguration: getStringValueSetting
,08-30 12:37:24.049  5049  5049 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-30 12:37:24.049  5049  5438 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-30 12:37:24.049  3951  3951 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-30 12:37:24.049  3951  3951 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-30 12:37:24.049  5090  5090 D BatteryMonitor: new battery level: 100
,08-30 12:37:24.059  4766  4766 D BatteryController: saveBatteryData : level[100], status[5]
,08-30 12:37:24.129  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:24.309  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:24.489  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:24.649  9558  9718 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-30 12:37:24.649  9558  9718 I jxcore-log: 
,08-30 12:37:24.669  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:24.749  9558  9718 I jxcore-log: ERROR runTests: 
08-30 12:37:24.749  9558  9718 I jxcore-log: 
,08-30 12:37:24.749  9558  9718 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-30 12:37:24.749  9558  9718 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"38","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
08-30 12:37:24.749  9558  9718 I jxcore-log: WARN testUtils: logCallback not set!
08-30 12:37:24.749  9558  9718 I jxcore-log: 
,08-30 12:37:24.759  9558  9718 I jxcore-log: [ { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 12:37:24.759  9558  9718 I jxcore-log:     _functionName: 'loadFile',
08-30 12:37:24.759  9558  9718 I jxcore-log:     _lineNumber: '26',
08-30 12:37:24.759  9558  9718 I jxcore-log:     _columnNumber: '11',
08-30 12:37:24.759  9558  9718 I jxcore-log:     _msg: '    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11' },
08-30 12:37:24.759  9558  9718 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 12:37:24.759  9558  9718 I jxcore-log:     _functionName: '',
08-30 12:37:24.759  9558  9718 I jxcore-log:     _lineNumber: '38',
08-30 12:37:24.759  9558  9718 I jxcore-log:     _columnNumber: '7',
08-30 12:37:24.759  9558  9718 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7' },
08-30 12:37:24.759  9558  9718 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 12:37:24.759  9558  9718 I jxcore-log:     _functionName: '',
08-30 12:37:24.759  9558  9718 I jxcore-log:     _lineNumber: '35',
08-30 12:37:24.759  9558  9718 I jxcore-log:     _columnNumber: '3',
08-30 12:37:24.759  9558  9718 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3' },
08-30 12:37:24.759  9558  9718 I jxcore-log:   { _fileName: 'module.js',
08-30 12:37:24.759  9558  9718 I jxcore-log:     _functionName: '$w.prototype._compile',
08-30 12:37:24.759  9558  9718 I jxcore-log:     _lineNumber: '621',
08-30 12:37:24.759  9558  9718 I jxcore-log:     _columnNumber: '8',
08-30 12:37:24.759  9558  9718 I jxcore-log:     _msg: '    at $w.prototype._compile@module.js:621:8' },
08-30 12:37:24.759  9558  9718 I jxcore-log:   { _fileName: 'module.js',
08-30 12:37:24.759  9558  9718 I jxcore-log:     _functionName: '$w._extensions[".js"]',
08-30 12:37:24.759  9558  9718 I jxcore-log:     _lineNumber: '651',
08-30 12:37:24.759  9558  9718 I jxcore-log:     _columnNumber: '1',
08-30 12:37:24.759  9558  9718 I jxcore-log:    
08-30 12:37:24.759  9558  9718 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-30 12:37:24.759  9558  9718 I jxcore-log: 
08-30 12:37:24.759  9558  9718 E jxcore-log: Error: 
08-30 12:37:24.759  9558  9718 E jxcore-log: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-30 12:37:24.759  9558  9718 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/runTests.js 26:11)
08-30 12:37:24.759  9558  9718 E jxcore-log: 
,08-30 12:37:24.789  3431  6509 D SSRM:n  : SIOP:: AP = 460, PST = 457 (W:8), CP = 324, CUR = -202, LCD = 1
,08-30 12:37:24.799  3431  6509 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-30 12:37:24.849  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:25.029  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:25.209  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:25.229  9961  9961 I FIPS_bssl: FIPS approved mode (1) | 9961 | app_process
,08-30 12:37:25.239  9961  9961 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-30 12:37:25.239  9961  9961 D AndroidRuntime: CheckJNI is OFF
,08-30 12:37:25.239  9961  9961 D AndroidRuntime: readGMSProperty: start
08-30 12:37:25.239  9961  9961 D AndroidRuntime: readGMSProperty: already setted!!
08-30 12:37:25.239  9961  9961 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-30 12:37:25.239  9961  9961 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-30 12:37:25.239  9961  9961 D AndroidRuntime: readGMSProperty: end
08-30 12:37:25.239  9961  9961 D AndroidRuntime: addProductProperty: start
,08-30 12:37:25.259  9961  9961 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-30 12:37:25.279  9961  9961 I Radio-JNI: register_android_hardware_Radio DONE
,08-30 12:37:25.279  9961  9961 E AffinityControl: AffinityControl: registerfunction enter
,08-30 12:37:25.289  9961  9961 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-30 12:37:25.299  3431  4650 D PackageManager: START PACKAGE DELETE: observer{210076485}
08-30 12:37:25.299  3431  4650 D PackageManager: pkg{<packageName>}
08-30 12:37:25.299  3431  4650 D PackageManager: user{0}
08-30 12:37:25.299  3431  4650 D PackageManager: caller{2000}
08-30 12:37:25.299  3431  4650 D PackageManager: flags{2}
,08-30 12:37:25.299  3431  4650 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-30 12:37:25.299  3431  4650 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-30 12:37:25.299  3431  4650 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
,08-30 12:37:25.299  3431  4650 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-30 12:37:25.299  3431  4650 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-30 12:37:25.299  3431  3582 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-30 12:37:25.299  3431  3582 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
,08-30 12:37:25.299  3431  3582 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-30 12:37:25.299  3431  3582 D ApplicationPolicy: getApplicationUninstallationEnabled
08-30 12:37:25.299  3431  3582 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-30 12:37:25.299  3431  3582 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
08-30 12:37:25.299  3431  3582 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,08-30 12:37:25.309  3431  3582 D PackageManager: !@killApplicatoin: 10177, uninstall pkg
08-30 12:37:25.309  3431  3582 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
,08-30 12:37:25.309  3431  3516 I ActivityManager: Force stopping com.test.thalitest appid=10177 user=-1: uninstall pkg
08-30 12:37:25.309  3431  3582 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,08-30 12:37:25.309  3431  3516 I ActivityManager: Killing 9558:com.test.thalitest/u0a177 (adj 0): stop com.test.thalitest cause uninstall pkg
08-30 12:37:25.309  3431  3516 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-30 12:37:25.319  3431  3516 D ActivityManager: mDVFSHelper.acquire()
,08-30 12:37:25.339  3431  3582 D AASAinstall: there is not AASApackages.xml file
,08-30 12:37:25.349  9970  9970 E Zygote  : v2
08-30 12:37:25.349  9970  9970 I libpersona: KNOX_SDCARD checking this for 10177
08-30 12:37:25.349  9970  9970 I libpersona: KNOX_SDCARD not a persona
,08-30 12:37:25.349  9970  9970 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,08-30 12:37:25.349  9970  9970 E Zygote  : accessInfo : 0
,08-30 12:37:25.349  9970  9970 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
08-30 12:37:25.349  3431  3516 I ActivityManager: Start proc 9970:com.test.thalitest/u0a177 for activity com.test.thalitest/.MainActivity
,08-30 12:37:25.359  3431  3516 I ActivityManager:   Force finishing activity ActivityRecord{665d1e3 u0 com.test.thalitest/.MainActivity t37}
08-30 12:37:25.359  3431  3516 W VirtualScreenManagerService: moveTaskBackToDisplayIfNeeded(): top activity or app is null
,08-30 12:37:25.379  9970  9970 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 12:37:25.379  9970  9970 D ActivityThread: Added TimaKeyStore provider
,08-30 12:37:25.389  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:25.389  3005  3016 I SurfaceFlinger: id=19 Removed NainActivit (6/10)
,08-30 12:37:25.389  3005  3907 I SurfaceFlinger: id=19 Removed NainActivit (-2/10)
,08-30 12:37:25.399  3431  3516 D InputDispatcher: Focused application released
,08-30 12:37:25.399  3431  3516 D FocusedStackFrame: Set to : 0
08-30 12:37:25.399  3431  3516 W VirtualScreenManagerService: failed to move task null
,08-30 12:37:25.449  3431  4608 D GraphicsStats: Buffer count: 7
,08-30 12:37:25.449  3431  3982 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@de43da7)
08-30 12:37:25.449  3431  3869 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:37:25.449  3431  3869 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:37:25.449  3431  3869 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 12:37:25.569  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:25.639  3431  3582 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,08-30 12:37:25.709  3431  3582 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-30 12:37:25.709  3431  3553 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,08-30 12:37:25.719  3431  3553 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
08-30 12:37:25.719  3431  3553 W System.err: 	at com.android.internal.policy.PhoneWindow.installDecor(PhoneWindow.java:4813)
08-30 12:37:25.719  3431  3553 W System.err: 	at com.android.internal.policy.PhoneWindow.getDecorView(PhoneWindow.java:2263)
08-30 12:37:25.719  3431  3553 W System.err: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4338)
08-30 12:37:25.719  3431  3553 W System.err: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
08-30 12:37:25.719  3431  3553 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:37:25.719  3431  3553 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-30 12:37:25.719  3431  3553 D SecWifiDisplayUtil: Metadata value : SecSettings2
08-30 12:37:25.719  3431  3553 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 12:37:25.719  3431  3553 W System.err: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-30 12:37:25.719  3431  3553 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{b215254 V.E...... R.....ID 0,0-0,0}
,08-30 12:37:25.719  3164  3164 W keystore: ENTER clear_uid from uid 1000 for 10177
,08-30 12:37:25.719  3431  3582 I art     : Starting a blocking GC Explicit
,08-30 12:37:25.729  3431  3553 W WindowManager: Failed looking up window
08-30 12:37:25.729  3431  3553 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@53dd5fd does not exist
08-30 12:37:25.729  3431  3553 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
08-30 12:37:25.729  3431  3553 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
08-30 12:37:25.729  3431  3553 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
08-30 12:37:25.729  3431  3553 W WindowManager: 	at android.view.ViewRootImpl.pokeDrawLockIfNeeded(ViewRootImpl.java:1203)
08-30 12:37:25.729  3431  3553 W WindowManager: 	at android.view.ViewRootImpl.scheduleTraversals(ViewRootImpl.java:1415)
08-30 12:37:25.729  3431  3553 W WindowManager: 	at android.view.ViewRootImpl.requestLayout(ViewRootImpl.java:1222)
08-30 12:37:25.729  3431  3553 W WindowManager: 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:800)
08-30 12:37:25.729  3431  3553 W WindowManager: 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:337)
08-30 12:37:25.729  3431  3553 W WindowManager: 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:91)
08-30 12:37:25.729  3431  3553 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4378)
08-30 12:37:25.729  3431  3553 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
08-30 12:37:25.729  3431  3553 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:37:25.729  3431  3553 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
08-30 12:37:25.729  3431  3553 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 12:37:25.729  3431  3553 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-30 12:37:25.729  3431  3553 W WindowManager: Attempted to add application window with unknown token Token{7dfb7e0 ActivityRecord{665d1e3 u0 com.test.thalitest/.MainActivity t37 f}}.  Aborting.
,08-30 12:37:25.729  3431  3553 D ViewRootImpl: #3 mView = null
,08-30 12:37:25.729  3431  3553 W WindowManager: Token{7dfb7e0 ActivityRecord{665d1e3 u0 com.test.thalitest/.MainActivity t37 f}} already running, starting window not displayed. Unable to add window -- token Token{7dfb7e0 ActivityRecord{665d1e3 u0 com.test.thalitest/.MainActivity t37 f}} is not valid; is your activity running?
08-30 12:37:25.729  3431  3553 W WindowManager: view not successfully added to wm, removing view
,08-30 12:37:25.729  3431  3553 W WindowManager: Exception when adding starting window
08-30 12:37:25.729  3431  3553 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{b215254 V.E...... R.....ID 0,0-0,0} not attached to window manager
08-30 12:37:25.729  3431  3553 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:451)
08-30 12:37:25.729  3431  3553 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:377)
08-30 12:37:25.729  3431  3553 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:122)
08-30 12:37:25.729  3431  3553 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4395)
08-30 12:37:25.729  3431  3553 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
08-30 12:37:25.729  3431  3553 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:37:25.729  3431  3553 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
08-30 12:37:25.729  3431  3553 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 12:37:25.729  3431  3553 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-30 12:37:25.739  6261  6272 I TrayUsageStatesWatcher: notePauseComponent : ComponentInfo{com.sec.android.app.launcher/com.android.launcher2.Launcher}
,08-30 12:37:25.749  6261  6271 I TrayUsageStatesWatcher: noteResumeComponent : ComponentInfo{com.sec.android.app.launcher/com.android.launcher2.Launcher} Intent { act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10800000 cmp=com.sec.android.app.launcher/.activities.LauncherActivity VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
,08-30 12:37:25.749  3431  3431 D GameManagerService: NotifyRunnable. pkg: com.sec.android.app.launcher, type: 4, isMinimized: false, isTunableApp: false
08-30 12:37:25.749  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:25.759  4314  4314 D Launcher: onRestart, Launcher: 46978248
,08-30 12:37:25.759  3431  3516 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.sec.android.app.launcher
,08-30 12:37:25.769  3431  4128 I ActivityManager: Killing 9258:com.samsung.android.coreapps/5011 (adj 15): DHA:empty #33
,08-30 12:37:25.779  4314  4314 D Launcher: onStart, Launcher: 46978248
08-30 12:37:25.779  4314  4314 D Launcher.HomeView: onStart
,08-30 12:37:25.779  4314  4314 D Launcher: onResume, Launcher: 46978248
,08-30 12:37:25.779  3431  6509 D GameManagerService: identifyGamePackage. com.sec.android.app.launcher
,08-30 12:37:25.779  3431  4327 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
08-30 12:37:25.779  3431  4327 D SettingsProvider: isChangeAllowed() : name = kids_home_mode
08-30 12:37:25.779  3431  4327 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 12:37:25.779  3431  4327 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 12:37:25.779  3431  4327 D SettingsProvider: selectionArgs: false
08-30 12:37:25.779  3431  4327 D SettingsProvider: selectionArgs: 10069
,08-30 12:37:25.789  3431  4327 D SettingsProvider: ret = -1
,08-30 12:37:25.789  4314  4314 D Launcher.HomeView: onResume
,08-30 12:37:25.789  4314  4314 D capture : ---------checkFileExist land
,08-30 12:37:25.789  4314  4314 D capture : currentOrientation: 1 mMainHomeScreenshot: true mMainHomeScreenshotLand: true
,08-30 12:37:25.799  9970  9970 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,08-30 12:37:25.799  9970  9970 D RelationGraph: garbageCollect()
,08-30 12:37:25.799  3005  3014 I SurfaceFlinger: Modify Choreographer's phase offset to 6666666
,08-30 12:37:25.799  9970  9970 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
,08-30 12:37:25.809  4314  4314 D FestivalPageManager: isFestivalChanged prevFestivalString : null , festivalString : null
,08-30 12:37:25.809  3431  3451 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
08-30 12:37:25.809  9970  9970 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,08-30 12:37:25.809  3005  4478 I SurfaceFlinger: Modify SurfaceFlinger's phase offset to 6666666
,08-30 12:37:25.809  3431  6509 D N       : limitCPUFreq:: freq = -1
08-30 12:37:25.809  3431  6509 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MAX_LIMIT  frequency : 2496000  uid : 1000  pid : 3431  tag : SIOP_ARM_MAX@22
,08-30 12:37:25.809  4314  4314 D FestivalPageManager: isFestivalChanged : false themeEnable : false
08-30 12:37:25.809  4314  4314 D Launcher.Model: LoaderTask isFestivalLoader: false
08-30 12:37:25.809  4314  4427 D Launcher.Model: Begin LoaderTask: 163222657
08-30 12:37:25.809  4314  4427 D Launcher.Model: Setting thread priority to DEFAULT
,08-30 12:37:25.809  3431  4650 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.coreapps, Auto Run ON
,08-30 12:37:25.809  4314  4427 D Launcher.Model: extraUpdateByFota => return, it is not FirstRun!
,08-30 12:37:25.809  4314  4427 D Launcher.Model: step 1: loading first workspace
08-30 12:37:25.809  4314  4427 D Launcher.Model: loadAndBindWorkspaceFirst mWorkspaceLoaded: true, mRefreshRequired: false
,08-30 12:37:25.809  4314  4427 D Launcher.Model: bindWorkspace()
08-30 12:37:25.809  4314  4427 D Launcher.Model:     hotseat : 3
,08-30 12:37:25.809  4314  4427 D Launcher.Model:     workspaceCurrentPage : 4
,08-30 12:37:25.809  4314  4427 D Launcher.Model:     folders : 3
,08-30 12:37:25.809  4314  4427 D Launcher.Model:     widgets : 3
08-30 12:37:25.809  4314  4427 D Launcher.Model:     workspaceOtherPage : 4
08-30 12:37:25.809  9970  9970 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/cache
08-30 12:37:25.809  9970  9970 V ActivityThread: Unable to initialize "java.io.tmpdir" property due to missing cache directory
08-30 12:37:25.809  9970  9970 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/code_cache
,08-30 12:37:25.809  9970  9970 E ActivityThread: Unable to setupGraphicsSupport due to missing code-cache directory
08-30 12:37:25.819  4314  4427 D Launcher.Model: Setting thread priority to BACKGROUND
,08-30 12:37:25.819  9970  9970 I InjectionManager: Inside getClassLibPath caller 
,08-30 12:37:25.819  3431  6509 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-30 12:37:25.829  9970  9970 D AndroidRuntime: Shutting down VM
,08-30 12:37:25.829  3431  6509 D GameManagerService: identifyGamePackage. com.sec.android.app.launcher
08-30 12:37:25.829  9970  9970 E AndroidRuntime: FATAL EXCEPTION: main
08-30 12:37:25.829  9970  9970 E AndroidRuntime: Process: com.test.thalitest, PID: 9970
08-30 12:37:25.829  9970  9970 E AndroidRuntime: java.lang.RuntimeException: Unable to instantiate application android.app.Application: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
08-30 12:37:25.829  9970  9970 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:676)
08-30 12:37:25.829  9970  9970 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6294)
08-30 12:37:25.829  9970  9970 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:222)
08-30 12:37:25.829  9970  9970 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1861)
08-30 12:37:25.829  9970  9970 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:37:25.829  9970  9970 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:158)
08-30 12:37:25.829  9970  9970 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:7229)
08-30 12:37:25.829  9970  9970 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:37:25.829  9970  9970 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-30 12:37:25.829  9970  9970 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-30 12:37:25.829  9970  9970 E AndroidRuntime: Caused by: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
08-30 12:37:25.829  9970  9970 E AndroidRuntime: 	at android.app.LoadedApk.initializeJavaContextClassLoader(LoadedApk.java:485)
08-30 12:37:25.829  9970  9970 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:661)
08-30 12:37:25.829  9970  9970 E AndroidRuntime: 	... 9 more
,08-30 12:37:25.839  9983  9983 E Zygote  : v2
,08-30 12:37:25.839  9983  9983 I libpersona: KNOX_SDCARD checking this for 10093
08-30 12:37:25.839  9983  9983 I libpersona: KNOX_SDCARD not a persona
08-30 12:37:25.839  9983  9983 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,08-30 12:37:25.839  9983  9983 E Zygote  : accessInfo : 0
08-30 12:37:25.839  9983  9983 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.clockpackage 
,08-30 12:37:25.839  3431  3516 I ActivityManager: Start proc 9983:com.sec.android.app.clockpackage/u0a93 for broadcast-3 com.sec.android.app.clockpackage/.alarmwidget.ClockAlarmWidgetProvider
,08-30 12:37:25.839  4314  4314 D MenuAppsGridFragment: onResume
08-30 12:37:25.839  4314  4314 D MenuAppsGridFragment: changeState: (new)NORMAL(old)NORMAL(force)false
08-30 12:37:25.839  4314  4314 I MenuAppsGridFragment: onResume mPendingModelUpdate is true, so we need to load apps
08-30 12:37:25.839  4314  4314 D Launcher.MenuAppsGrid: appModelUpdated:-1
08-30 12:37:25.839  4314  4314 D MenuAppModel: get TopLevelItems:20
08-30 12:37:25.839  4314  4314 D Launcher.MenuAppsGrid: syncPages
08-30 12:37:25.839  4314  4314 D MenuAppModel: get TopLevelItems:20
,08-30 12:37:25.839  3431  3858 D NetworkPolicy: isUidForegroundLocked: 10093, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,08-30 12:37:25.849  9970  9970 I Process : Sending signal. PID: 9970 SIG: 9
08-30 12:37:25.849  4314  4314 D Launcher.MenuAppsGrid: syncPages end
08-30 12:37:25.849  3431  6509 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
08-30 12:37:25.849  3431  6509 D GameManagerService: identifyGamePackage. com.sec.android.app.launcher
08-30 12:37:25.849  3431  6509 D GameManagerService: identifyGamePackage. com.sec.android.app.launcher
,08-30 12:37:25.859  9983  9983 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 12:37:25.859  9983  9983 D ActivityThread: Added TimaKeyStore provider
,08-30 12:37:25.869  3431  3855 I ActivityManager: Process com.test.thalitest (pid 9970)(adj 9) has died(192,1747)
,08-30 12:37:25.869  3431  3855 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-30 12:37:25.869  3431  3855 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.am.ActivityManagerService.updateOomAdjLocked:26743 com.android.server.am.ActivityManagerService.appDiedLocked:7562 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1916 android.os.BinderProxy.sendDeathNotice:558 
,08-30 12:37:25.879  3431  4608 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{10d0d43 u0 com.android.launcher.action.HOME_MODE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{16b3fc0 9983:com.sec.android.app.clockpackage/u0a93}
,08-30 12:37:25.879  3431  3858 D NetworkPolicy: isUidForegroundLocked: 10093, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
,08-30 12:37:25.889  9983  9983 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,08-30 12:37:25.889  9983  9983 D RelationGraph: garbageCollect()
,08-30 12:37:25.899  9983  9983 W ResourcesManager: getTopLevelResources: /system/app/ClockPackage_M/ClockPackage_M.apk / 1.0 running in com.sec.android.app.clockpackage rsrc of package com.sec.android.app.clockpackage
,08-30 12:37:25.899  3431  3450 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,08-30 12:37:25.899  9983  9983 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,08-30 12:37:25.899  9983  9983 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:25.909  9983  9983 I InjectionManager: Inside getClassLibPath caller 
,08-30 12:37:25.909  4314  4314 W ResourcesManager: getTopLevelResources: /system/app/ClockPackage_M/ClockPackage_M.apk / 1.0 running in com.sec.android.app.launcher rsrc of package com.sec.android.app.clockpackage
,08-30 12:37:25.919  4314  4314 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:25.919  4314  4314 D ApplicationPackageManager: we don't have com.sec.android.app.clockpackage class. load it
,08-30 12:37:25.929  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:37:25.929  9983  9983 W System  : ClassLoader referenced unknown path: /system/app/ClockPackage_M/lib/arm64
,08-30 12:37:25.929  4314  4314 W ResourcesManager: getTopLevelResources: /system/app/ClockPackage_M/ClockPackage_M.apk / 1.0 running in com.sec.android.app.launcher rsrc of package com.sec.android.app.clockpackage
,08-30 12:37:25.949  3431  3582 I art     : Explicit concurrent mark sweep GC freed 279673(17MB) AllocSpace objects, 34(2MB) LOS objects, 31% free, 34MB/50MB, paused 1.841ms total 228.615ms
,08-30 12:37:25.959  4314  4314 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M/SPlanner_M.apk / 1.0 running in com.sec.android.app.launcher rsrc of package com.android.calendar
,08-30 12:37:25.959  4314  4314 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:25.959  4314  4314 D ApplicationPackageManager: we don't have com.android.calendar class. load it
,08-30 12:37:25.969  4314  4314 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M/SPlanner_M.apk / 1.0 running in com.sec.android.app.launcher rsrc of package com.android.calendar
,08-30 12:37:25.969  4314  4314 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
08-30 12:37:25.969  4314  4314 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
08-30 12:37:25.969  4314  4314 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
,08-30 12:37:25.979  3431  3582 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
08-30 12:37:25.979  3431  3582 D AASAuninstall: userId = 0, info.removedAppID = 10177, info.uid = 10177, packageName = com.test.thalitest
,08-30 12:37:25.979  3431  3582 D AASAinstall: there is not AASApackages.xml file
08-30 12:37:25.979  3431  3582 D PackageManager: result of delete: 1{210076485}
,08-30 12:37:25.989  9961  9961 I art     : System.exit called, status: 0
08-30 12:37:25.989  9961  9961 I AndroidRuntime: VM exiting with result code 0.
08-30 12:37:25.989  3431  3582 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-30 12:37:25.989  3431  3582 D PackageManager: userId{-1}
08-30 12:37:25.989  3431  3582 D PackageManager: andCode{true}
,08-30 12:37:25.989  4314  4314 D Launcher.MenuAppsGrid: updateGridSize:GRID_4x4 cellWidth:348  cellHeight:432
,08-30 12:37:25.989  3431  3582 I ActivityManager: Force stopping com.test.thalitest appid=10177 user=0: pkg removed
,08-30 12:37:26.049  9437  9999 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
,08-30 12:37:26.049  6261  6261 I TrayVisibilityController: handleMessage : msg.what = 1
,08-30 12:37:26.049  9437  9999 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
,08-30 12:37:26.049  9437  9999 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
,08-30 12:37:26.069  9983  9983 I BNRClientProivder, VERSION : 1.7.6: register - xml6 : Alarm, v5VJ0Ep6EE, com.sec.android.app.clockpackage.alarm.backuprestore.AlarmSCloudBackupRestore
,08-30 12:37:26.079  9983  9983 I BNRClientHelper: 101, Alarm, VERSION 1.7.6
,08-30 12:37:26.079  9983  9983 I BNRClientProivder, VERSION : 1.7.6: register - xml6 : WorldClock, pYz7p28bSl, com.sec.android.app.clockpackage.worldclock.backuprestore.WorldclockSCloudBackupRestore
,08-30 12:37:26.079  9983  9983 I BNRClientHelper: 101, WorldClock, VERSION 1.7.6
08-30 12:37:26.079  9983  9983 I BNRClientProivder, VERSION : 1.7.6: register - xml6 quick_backup : ALARMWIDGET, I6IHHRg397, com.sec.android.app.clockpackage.alarm.backuprestore.AlarmWidgetSCloudBackupRestore
,08-30 12:37:26.079  9983  9983 I QBNRClientHelper: init SyncClientHelper : ALARMWIDGET
08-30 12:37:26.079  9983  9983 I BNRClientProivder, VERSION : 1.7.6: register - xml6 quick_backup : DUALCLOCKWIDGET, ZCms5GaCFo, com.sec.android.widgetapp.dualclockdigital.DualClockDigitalBackupRestoreReceiver
08-30 12:37:26.079  9983  9983 I QBNRClientHelper: init SyncClientHelper : DUALCLOCKWIDGET
,08-30 12:37:26.099  3431  4650 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() true
08-30 12:37:26.099  3431  4650 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
08-30 12:37:26.099  3431  4650 D KnoxTimeoutHandler: post home show event for user 0
08-30 12:37:26.099  3431  4650 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-30 12:37:26.099  3431  3431 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
08-30 12:37:26.099  3431  3431 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
08-30 12:37:26.099  3431  3431 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-30 12:37:26.099  4314  4314 D Launcher: onPause, Launcher: 46978248
08-30 12:37:26.099  4314  4314 D Launcher.HomeView: onPause
08-30 12:37:26.099  4314  4314 D Launcher.Workspace: exitWidgetResizeMode. isClearResizeFrame is false
08-30 12:37:26.099  6261  6261 I Utils   : isCurrentUser current = 0, ownerId = 0
08-30 12:37:26.099  6261  6261 I TrayVisibilityController: getComputedTrayVisible : keyguardState = 3
08-30 12:37:26.099  6261  6261 I TrayVisibilityController: updateTrayVisible : State : 3 visible = 2 mCurrentVisible = 2
,08-30 12:37:26.109  3431  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
08-30 12:37:26.109  9983  9983 D InjectionManager: InjectionManager
08-30 12:37:26.109  9983  9983 D InjectionManager: fillFeatureStoreMap com.sec.android.app.clockpackage
08-30 12:37:26.109  3431  3431 I KnoxTimeoutHandler: Shared devices show user statefalse
08-30 12:37:26.109  3431  3881 D MdnieScenarioControlService:  packageName : com.sec.android.app.launcher    className : com.sec.android.app.launcher.activities.LauncherActivity
08-30 12:37:26.109  3431  3881 I MdnieScenarioControlService: mGameModeLauncher : false
08-30 12:37:26.109  3431  3881 I MdnieScenarioControlService: setUIMode
08-30 12:37:26.109  9983  9983 I InjectionManager: Constructor com.sec.android.app.clockpackage, Feature store :{}
08-30 12:37:26.109  9983  9983 I InjectionManager: featureStore :{}
08-30 12:37:26.119  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,08-30 12:37:26.119  3431  3431 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:26.119  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,08-30 12:37:26.119  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
,08-30 12:37:26.129  3431  3431 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:26.129  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
,08-30 12:37:26.129  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
08-30 12:37:26.129  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
,08-30 12:37:26.129  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
,08-30 12:37:26.129  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
08-30 12:37:26.129  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungAccount_Hero/SamsungAccount_Hero.apk / 1.0 running in null rsrc of package com.osp.app.signin
,08-30 12:37:26.139  4314  4314 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 684 440 span 2 1 (widgetid 2) [current Gridsize : GRID_4x4]
,08-30 12:37:26.139  4314  4314 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Pogoda(widget id = 2) result hostview size = 684 x 440
,08-30 12:37:26.139  4314  4314 D LauncherAppWidgetHostView: setResizeScaleResult() 684/ 440 scaleToResize = 1.0(widget id = 2)
08-30 12:37:26.139  4314  4314 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 1372 440 span 4 1 (widgetid 3) [current Gridsize : GRID_4x4]
,08-30 12:37:26.139  4314  4314 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Aplikacja Google(widget id = 3) result hostview size = 1372 x 440
08-30 12:37:26.139  4314  4314 D LauncherAppWidgetHostView: setResizeScaleResult() 1372/ 440 scaleToResize = 1.0(widget id = 3)
08-30 12:37:26.139  4314  4314 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 1372 440 span 4 1 (widgetid 4) [current Gridsize : GRID_4x4]
08-30 12:37:26.139  4314  4314 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Galaxy Essentials(widget id = 4) result hostview size = 1372 x 440
08-30 12:37:26.139  4314  4314 D LauncherAppWidgetHostView: setResizeScaleResult() 1372/ 440 scaleToResize = 1.0(widget id = 4)
,08-30 12:37:26.139  3431  3431 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:26.149  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungAccount_Hero/SamsungAccount_Hero.apk / 1.0 running in null rsrc of package com.osp.app.signin
08-30 12:37:26.149  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-30 12:37:26.149  3431  3511 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package com.google.android.googlequicksearchbox
08-30 12:37:26.149  3005  3005 I SurfaceFlinger: id=20 createSurf (1440x2560),1 flag=4, MauncherAct
08-30 12:37:26.149  3431  3431 D ResourcesManager: For user 0 new overlays fetched Null
08-30 12:37:26.149  3431  3511 D ResourcesManager: For user 0 new overlays fetched Null
08-30 12:37:26.149  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,08-30 12:37:26.149  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,08-30 12:37:26.159  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-30 12:37:26.159  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-30 12:37:26.159  3431  3511 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package com.google.android.googlequicksearchbox
,08-30 12:37:26.159  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-30 12:37:26.159  3431  3431 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in null rsrc of package com.samsung.android.coreapps
08-30 12:37:26.159  3431  3511 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
,08-30 12:37:26.159  3431  3431 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:26.159  3431  3431 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in null rsrc of package com.samsung.android.coreapps
,08-30 12:37:26.159  3431  3431 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
08-30 12:37:26.159  4314  4661 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,08-30 12:37:26.169  3431  3511 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:26.169  3951  3951 D ShortcutManager: onReceive : android.intent.action.PACKAGE_REMOVED
08-30 12:37:26.169  3431  3431 D ResourcesManager: For user 0 new overlays fetched Null
08-30 12:37:26.169  3951  3951 D ShortcutManager: onReceive : Intent.EXTRA_REPLACING false,com.test.thalitest
,08-30 12:37:26.169  3431  3431 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
08-30 12:37:26.169  3431  3511 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
08-30 12:37:26.169  3431  3431 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
08-30 12:37:26.169  3431  3431 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
,08-30 12:37:26.169  3431  3431 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
08-30 12:37:26.169  4314  4314 D MenuAppModel: invalidateTopLevelItems
,08-30 12:37:26.169  4314  4314 D Launcher.Model: MenuAppModel.onModelRefreshed called
08-30 12:37:26.169  4314  4314 D Launcher.MenuWidgetsLoader: MenuWidgetLoade-loadMenuWidgets : true
,08-30 12:37:26.169  4314  4314 D Launcher.Model: bindAppsLoaded called
,08-30 12:37:26.169  3431  3431 D ResourcesManager: For user 0 new overlays fetched Null
08-30 12:37:26.169  3431  3511 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package com.google.android.googlequicksearchbox
,08-30 12:37:26.169  3431  3511 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
08-30 12:37:26.169  3431  3431 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
08-30 12:37:26.169  3431  3431 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in null rsrc of package com.microsoft.office.onenote
,08-30 12:37:26.169  3431  3511 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
08-30 12:37:26.169  4153  4153 I CatchNotificationsService: mPackageChangedReceiver : onReceive action = android.intent.action.PACKAGE_REMOVED
,08-30 12:37:26.169  3431  3511 W ResourcesManager: getTopLevelResources: /system/priv-app/LiveBroadcast/LiveBroadcast.apk / 1.0 running in null rsrc of package com.sec.android.app.camera.plb
,08-30 12:37:26.179  3431  3431 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:26.179  3431  3431 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in null rsrc of package com.microsoft.office.onenote
08-30 12:37:26.179  3431  3431 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
08-30 12:37:26.179  3431  3511 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:26.179  3431  3553 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package com.android.inputdevices
08-30 12:37:26.179  3431  3511 W ResourcesManager: getTopLevelResources: /system/priv-app/LiveBroadcast/LiveBroadcast.apk / 1.0 running in null rsrc of package com.sec.android.app.camera.plb
,08-30 12:37:26.179  3431  3511 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCamera5/SamsungCamera5.apk / 1.0 running in null rsrc of package com.sec.android.app.camera
,08-30 12:37:26.179  3431  3431 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:26.179  3431  3431 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
08-30 12:37:26.179  3431  3511 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:26.179  3431  3511 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCamera5/SamsungCamera5.apk / 1.0 running in null rsrc of package com.sec.android.app.camera
,08-30 12:37:26.179  3431  3511 W ResourcesManager: getTopLevelResources: /system/app/STalkback/STalkback.apk / 1.0 running in null rsrc of package com.samsung.android.app.talkback
,08-30 12:37:26.179  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-30 12:37:26.179  3431  3553 D ResourcesManager: For user 0 new overlays fetched Null
08-30 12:37:26.179  3431  3511 D ResourcesManager: For user 0 new overlays fetched Null
08-30 12:37:26.189  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-30 12:37:26.189  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-30 12:37:26.189  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-30 12:37:26.189  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-30 12:37:26.189  3431  3511 W ResourcesManager: getTopLevelResources: /system/app/STalkback/STalkback.apk / 1.0 running in null rsrc of package com.samsung.android.app.talkback
08-30 12:37:26.189  3431  3511 W ResourcesManager: getTopLevelResources: /system/app/UniversalSwitch/UniversalSwitch.apk / 1.0 running in null rsrc of package com.samsung.android.universalswitch
08-30 12:37:26.189  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-30 12:37:26.189  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,08-30 12:37:26.189  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-30 12:37:26.189  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-30 12:37:26.189  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-30 12:37:26.189  3431  3553 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package com.android.inputdevices
08-30 12:37:26.189  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-30 12:37:26.189  3431  3511 D ResourcesManager: For user 0 new overlays fetched Null
08-30 12:37:26.189  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,08-30 12:37:26.189  3431  3511 W ResourcesManager: getTopLevelResources: /system/app/UniversalSwitch/UniversalSwitch.apk / 1.0 running in null rsrc of package com.samsung.android.universalswitch
08-30 12:37:26.189  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-30 12:37:26.189  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-30 12:37:26.189  3431  3511 D AccessibilityManagerService: onUserStateChangedLocked()
08-30 12:37:26.189  3431  3511 D AccessibilityManagerService: updateServicesLocked().mIsAccessibilityEnabled : false
08-30 12:37:26.189  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,08-30 12:37:26.189  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-30 12:37:26.189  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-30 12:37:26.189  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-30 12:37:26.189  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-30 12:37:26.189  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-30 12:37:26.189  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,08-30 12:37:26.189  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-30 12:37:26.189  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,08-30 12:37:26.189  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-30 12:37:26.189  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-30 12:37:26.189  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-30 12:37:26.189  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,08-30 12:37:26.189  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-30 12:37:26.189  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-30 12:37:26.189  3431  3832 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-30 12:37:26.189  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-30 12:37:26.189  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-30 12:37:26.189  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-30 12:37:26.189  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package com.google.android.gsf
,08-30 12:37:26.189  3431  3431 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:26.199  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package com.google.android.gsf
08-30 12:37:26.199  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package com.sec.android.app.shealth
,08-30 12:37:26.199  3431  3431 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:37:26.199  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package com.sec.android.app.shealth
08-30 12:37:26.199  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package com.sec.android.app.shealth
,08-30 12:37:26.199  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package com.sec.android.app.shealth
08-30 12:37:26.199  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
08-30 12:37:26.199  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
08-30 12:37:26.199  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
,08-30 12:37:26.199  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
08-30 12:37:26.199  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
08-30 12:37:26.199  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
08-30 12:37:26.199  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
,08-30 12:37:26.199  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
08-30 12:37:26.199  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
08-30 12:37:26.199  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
08-30 12:37:26.209  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
,08-30 12:37:26.209  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
08-30 12:37:26.209  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-30 12:37:26.209  4330  4811 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-30 12:37:26.209  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-30 12:37:26.209  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-30 12:37:26.209  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-30 12:37:26.209  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-30 12:37:26.209  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-30 12:37:26.209  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-30 12:37:26.209  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-30 12:37:26.209  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-30 12:37:26.209  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-30 12:37:26.209  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-30 12:37:26.209  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-30 12:37:26.209  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-30 12:37:26.209  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-30 12:37:26.209  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-30 12:37:26.209  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-30 12:37:26.209  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
08-30 12:37:26.209  3431  4747 V WindowStateAnimator: Finishing drawing window Window{24bdb68 u0 d0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}: mDrawState=DRAW_PENDING
08-30 12:37:26.209  3431  3431 D ResourcesManager: For user 0 new overlays fetched Null
08-30 12:37:26.209  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
08-30 12:37:26.209  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
08-30 12:37:26.209  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
08-30 12:37:26.209  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
08-30 12:37:26.209  5090  5277 D PresenceModule: onReceive: package removed
08-30 12:37:26.209  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
08-30 12:37:26.209  5090  5277 D PresenceModule: handleMessage: msg 50, Last Publish Info: null
08-30 12:37:26.209  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
08-30 12:37:26.209  5090  5277 D PresenceModule: Application package removed
08-30 12:37:26.209  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
08-30 12:37:26.209  5090  5277 D PresenceModule: onAppPkgRemoved: com.test.thalitest
08-30 12:37:26.209  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
08-30 12:37:26.209  5090  5277 D PresenceModule: onApplicationPackageRemoved: invalid package
08-30 12:37:26.209  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
08-30 12:37:26.209  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
08-30 12:37:26.209  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
08-30 12:37:26.219  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
08-30 12:37:26.219  3431  3431 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
08-30 12:37:26.219  3431  3431 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package com.android.chrome
08-30 12:37:26.219  3005  3005 D libEGL  : eglInitialize EGLDisplay = 0x7fdefe6e48
08-30 12:37:26.219  3431  3431 D ResourcesManager: For user 0 new overlays fetched Null
08-30 12:37:26.219  4167  4167 I PeoplePackageManager: onReceive:android.intent.action.PACKAGE_REMOVED
08-30 12:37:26.219  3431  3431 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package com.android.chrome
08-30 12:37:26.219  3431  3431 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in null rsrc of package com.samsung.android.coreapps
08-30 12:37:26.219  3431  3431 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in null rsrc of package com.samsung.android.coreapps
08-30 12:37:26.219  3431  3431 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package com.google.android.apps.docs
08-30 12:37:26.229  3431  3431 D ResourcesManager: For user 0 new overlays fetched Null
08-30 12:37:26.229  3431  3431 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package com.google.android.apps.docs
08-30 12:37:26.229  3431  3431 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
08-30 12:37:26.229  3431  3431 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
08-30 12:37:26.229  3431  3431 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
08-30 12:37:26.229  3431  3431 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
08-30 12:37:26.229  3431  3431 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
08-30 12:37:26.229  3431  3431 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
08-30 12:37:26.229  3431  3431 W ResourcesManager: getTopLevelResources: /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk / 1.0 running in null rsrc of package com.google.android.syncadapters.calendar
08-30 12:37:26.229  3431  3431 D ResourcesManager: For user 0 new overlays fetched Null
08-30 12:37:26.229  3431  3511 D EnterpriseDeviceManagerService: Package has changed for user 0
08-30 12:37:26.229  3431  3431 W ResourcesManager: getTopLevelResources: /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk / 1.0 running in null rsrc of package com.google.android.syncadapters.calendar
08-30 12:37:26.229  3431  3431 W ResourcesManager: getTopLevelResources: /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk / 1.0 running in null rsrc of package com.google.android.syncadapters.contacts
08-30 12:37:26.229  3431  3511 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
08-30 12:37:26.229  3431  3511 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
08-30 12:37:26.229  3431  3431 D ResourcesManager: For user 0 new overlays fetched Null

```
