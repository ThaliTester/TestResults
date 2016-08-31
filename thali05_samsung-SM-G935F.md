#### Test 83084099807e426_thali05_samsung-SM-G935F Logs


```
--------- beginning of main
08-31 16:50:25.109  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-31 16:50:25.159  3152  3633 D EnterpriseController: netId is 0
08-31 16:50:25.159  3152  3633 D Netd    : getNetworkForDns: using netid 0 for uid 10002
08-31 16:50:25.169  4585  4747 E         : Error communicating to API: https://prod.yana.asideas.de/api/v2/categories
08-31 16:50:25.169  4585  4747 E         : retrofit.RetrofitError: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
08-31 16:50:25.169  4585  4747 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:395)
08-31 16:50:25.169  4585  4747 E         : 	at retrofit.RestAdapter$RestHandler.access$100(RestAdapter.java:220)
08-31 16:50:25.169  4585  4747 E         : 	at retrofit.RestAdapter$RestHandler$1.invoke(RestAdapter.java:265)
08-31 16:50:25.169  4585  4747 E         : 	at retrofit.RxSupport$2.run(RxSupport.java:55)
08-31 16:50:25.169  4585  4747 E         : 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-31 16:50:25.169  4585  4747 E         : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-31 16:50:25.169  4585  4747 E         : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-31 16:50:25.169  4585  4747 E         : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-31 16:50:25.169  4585  4747 E         : 	at retrofit.Platform$Android$2$1.run(Platform.java:142)
08-31 16:50:25.169  4585  4747 E         : 	at java.lang.Thread.run(Thread.java:818)
08-31 16:50:25.169  4585  4747 E         : Caused by: java.net.UnknownHostException: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
08-31 16:50:25.169  4585  4747 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:470)
08-31 16:50:25.169  4585  4747 E         : 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
08-31 16:50:25.169  4585  4747 E         : 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
08-31 16:50:25.169  4585  4747 E         : 	at com.squareup.okhttp.internal.Network$1.resolveInetAddresses(Network.java:29)
08-31 16:50:25.169  4585  4747 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:187)
08-31 16:50:25.169  4585  4747 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.nextProxy(RouteSelector.java:156)
08-31 16:50:25.169  4585  4747 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.next(RouteSelector.java:98)
08-31 16:50:25.169  4585  4747 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.createNextConnection(HttpEngine.java:344)
08-31 16:50:25.169  4585  4747 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:327)
08-31 16:50:25.169  4585  4747 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:245)
08-31 16:50:25.169  4585  4747 E         : 	at com.squareup.okhttp.Call.getResponse(Call.java:267)
08-31 16:50:25.169  4585  4747 E         : 	at com.squareup.okhttp.Call$ApplicationInterceptorChain.proceed(Call.java:224)
08-31 16:50:25.169  4585  4747 E         : 	at com.squareup.okhttp.Call.getResponseWithInterceptorChain(Call.java:195)
08-31 16:50:25.169  4585  4747 E         : 	at com.squareup.okhttp.Call.execute(Call.java:79)
08-31 16:50:25.169  4585  4747 E         : 	at retrofit.client.OkClient.execute(OkClient.java:53)
08-31 16:50:25.169  4585  4747 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:326)
08-31 16:50:25.169  4585  4747 E         : 	... 9 more
08-31 16:50:25.169  4585  4747 E         : Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
08-31 16:50:25.169  4585  4747 E         : 	at libcore.io.Posix.android_getaddrinfo(Native Method)
08-31 16:50:25.169  4585  4747 E         : 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
08-31 16:50:25.169  4585  4747 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:451)
08-31 16:50:25.169  4585  4747 E         : 	... 24 more
08-31 16:50:25.169  4585  4747 E         : 
08-31 16:50:25.219  3381  8642 I HarmonyEASService: Updating for all 1
08-31 16:50:25.289  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
08-31 16:50:25.399  8649  8649 D AASAservice-RuleManager: IsSharedUID() : pkgname - com.test.thalitest, mSharedUserId - null
08-31 16:50:25.399  8649  8649 D AASAservice-UpdateReceiver: AASAUpdateReceiver : check SharedUID package.
08-31 16:50:25.399  8649  8649 E AASAservice-UpdateReceiver: AASAUpdateReceiver : myrule is null.
08-31 16:50:25.399  8649  8649 I art     : System.exit called, status: 0
08-31 16:50:25.399  8649  8649 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
--------- beginning of system
08-31 16:50:25.439  3381  4771 I ActivityManager: Process com.samsung.aasaservice (pid 8649)(adj 0) has died(159,1817)
08-31 16:50:25.439  3381  4771 D ActivityManager: isAutoRunBlockedApp:: com.samsung.aasaservice, Auto Run ON
08-31 16:50:25.459  3381  3523 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f20a0cc u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4bc546 8364:com.samsung.android.app.appsedge/u0a1}
08-31 16:50:25.459  8364  8364 I AppsEdgeBroadcastReceiver: onReceive: android.intent.action.PACKAGE_ADDED
08-31 16:50:25.469  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
08-31 16:50:25.469  8705  8705 E Zygote  : v2
08-31 16:50:25.469  8705  8705 I libpersona: KNOX_SDCARD checking this for 10017
08-31 16:50:25.469  8705  8705 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
08-31 16:50:25.469  8705  8705 I libpersona: KNOX_SDCARD not a persona
08-31 16:50:25.469  8705  8705 E Zygote  : accessInfo : 0
08-31 16:50:25.469  8705  8705 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.app.galaxylabs 
08-31 16:50:25.479  3381  4419 I ActivityManager: Start proc 8705:com.samsung.android.app.galaxylabs/u0a17 for broadcast-3 com.samsung.android.app.galaxylabs/.LabsIntentReceiver
08-31 16:50:25.479  8702  8702 I FIPS_bssl: FIPS approved mode (1) | 8702 | app_process
08-31 16:50:25.489  8702  8702 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-31 16:50:25.489  8705  8705 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:50:25.489  8705  8705 D ActivityThread: Added TimaKeyStore provider
08-31 16:50:25.489  8702  8702 D AndroidRuntime: CheckJNI is OFF
08-31 16:50:25.489  8702  8702 D AndroidRuntime: readGMSProperty: start
08-31 16:50:25.489  8702  8702 D AndroidRuntime: readGMSProperty: already setted!!
08-31 16:50:25.489  8702  8702 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-31 16:50:25.489  8702  8702 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-31 16:50:25.489  8702  8702 D AndroidRuntime: readGMSProperty: end
08-31 16:50:25.489  8702  8702 D AndroidRuntime: addProductProperty: start
08-31 16:50:25.499  3381  3461 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f20a0cc u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{abae9a6 8705:com.samsung.android.app.galaxylabs/u0a17}
08-31 16:50:25.509  8705  8705 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
08-31 16:50:25.509  8705  8705 D RelationGraph: garbageCollect()
08-31 16:50:25.509  8705  8705 W ResourcesManager: getTopLevelResources: /system/priv-app/GalaxyLabs/GalaxyLabs.apk / 1.0 running in com.samsung.android.app.galaxylabs rsrc of package com.samsung.android.app.galaxylabs
08-31 16:50:25.509  3381  4558 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
08-31 16:50:25.509  8705  8705 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
08-31 16:50:25.509  8702  8702 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-31 16:50:25.509  8705  8705 D ResourcesManager: For user 0 new overlays fetched Null
08-31 16:50:25.509  8705  8705 I InjectionManager: Inside getClassLibPath caller 
08-31 16:50:25.509  8705  8705 W System  : ClassLoader referenced unknown path: /system/priv-app/GalaxyLabs/lib/arm64
08-31 16:50:25.529  8705  8705 D InjectionManager: InjectionManager
08-31 16:50:25.529  8705  8705 D InjectionManager: fillFeatureStoreMap com.samsung.android.app.galaxylabs
08-31 16:50:25.529  8705  8705 I InjectionManager: Constructor com.samsung.android.app.galaxylabs, Feature store :{}
08-31 16:50:25.529  8705  8705 I InjectionManager: featureStore :{}
08-31 16:50:25.529  8705  8705 D LabsIntentReceiver: action: android.intent.action.PACKAGE_ADDED
08-31 16:50:25.529  8705  8705 D LabsIntentReceiver: pkg: com.test.thalitest
08-31 16:50:25.529  8705  8705 D LabsIntentReceiver: context: android.app.ReceiverRestrictedContext@e39cee9
08-31 16:50:25.529  8705  8705 D LabsIntentReceiver: extra: false
08-31 16:50:25.529  8705  8705 D LabsLoader: loadByPackageName: deleteDB com.test.thalitest
08-31 16:50:25.529  8702  8702 I Radio-JNI: register_android_hardware_Radio DONE
08-31 16:50:25.529  8702  8702 E AffinityControl: AffinityControl: registerfunction enter
08-31 16:50:25.529  4292  4292 D LauncherApplication: galaxy labs setting changed!!!
08-31 16:50:25.529  3381  3974 I ActivityManager: Killing 8226:com.samsung.android.app.simplesharing/5011 (adj 15): DHA:empty #33
08-31 16:50:25.539  8702  8702 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-31 16:50:25.539  3381  3974 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f20a0cc u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{51aad4d 4305:com.google.android.gms.persistent/u0a21}
08-31 16:50:25.549  3160  3160 V MediaPlayerService: Client(6) destructor pid = 8226
08-31 16:50:25.549  3160  3160 V MediaPlayerService: disconnect(6) from pid 8226
08-31 16:50:25.549  3160  3160 D NuPlayerDriver: reset(0xf188bd60)
08-31 16:50:25.549  3160  3160 D NuPlayerDriver: notifyListener_l(0xf188bd60), (8, 0, 0)
08-31 16:50:25.549  3160  8246 V NuPlayer: kWhatReset
08-31 16:50:25.549  3160  8246 V NuPlayer: performReset
08-31 16:50:25.549  3160  8246 V GenericSource: stop()
08-31 16:50:25.549  3160  8246 V GenericSource: PREPARE_CANCELLED set to true
08-31 16:50:25.549  3160  8246 V GenericSource: [Flag] set 0x40 -> mFlags = 0x48
08-31 16:50:25.549  3160  8246 V GenericSource: [Flag] clear 0x8 -> mFlags = 0x40
08-31 16:50:25.549  3160  8246 V GenericSource: stop() end
08-31 16:50:25.549  3160  8246 V GenericSource: ~GenericSource()
08-31 16:50:25.549  3160  8246 I OggExtractor: OggSource::stop() mExtractor ref count = 2
08-31 16:50:25.549  3160  8246 I OggExtractor: ~OggSource --
08-31 16:50:25.549  3160  8246 D NuPlayerDriver: notifyResetComplete(0xf188bd60)
08-31 16:50:25.549  3160  3160 V NuPlayerDriver: ~NuPlayerDriver(0xf188bd60)
08-31 16:50:25.549  3160  3160 I OggExtractor: ~OggExtractor ++
08-31 16:50:25.549  3160  3160 I OggExtractor: ~MyOggExtractor ++ 
08-31 16:50:25.549  3160  3160 I OggExtractor: ~MyOggExtractor --
08-31 16:50:25.549  3160  3160 I OggExtractor: ~OggExtractor --
08-31 16:50:25.549  3160  3160 V AudioSink: +++ close
08-31 16:50:25.549  3160  3160 V AudioSink: --- close
08-31 16:50:25.569  3381  4419 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
08-31 16:50:25.569  3381  4419 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
08-31 16:50:25.579  3381  4419 D ResourcesManager: For user 0 new overlays fetched Null
08-31 16:50:25.579  3381  4419 D GameManagerService: identifyGamePackage. com.test.thalitest
08-31 16:50:25.579  3381  4419 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
08-31 16:50:25.579  3381  4419 D ActivityManager: mDVFSHelper.acquire()
08-31 16:50:25.589  3009  3009 I SurfaceFlinger: id=15 createSurf (16x16),-1 flag=20004, EimLayer(Di
08-31 16:50:25.589  3009  3009 I SurfaceFlinger: id=16 createSurf (16x16),-1 flag=20004, EimLayer(An
08-31 16:50:25.599  3381  3381 D ViewRootImpl: MSG_RESIZED: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
08-31 16:50:25.599  3946  3946 D ViewRootImpl: MSG_RESIZED: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
08-31 16:50:25.599  3946  4797 D WallpaperService: resized:[frame]Rect(0, 0 - 2240, 2560) [newConfig] is null
08-31 16:50:25.599  3381  3381 D ViewRootImpl: MSG_RESIZED: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
08-31 16:50:25.599  3946  3946 D WallpaperService: MSG_WINDOW_RESIZED
08-31 16:50:25.599  3381  4419 D FocusedStackFrame: Set to : 0
08-31 16:50:25.599  3946  3946 D WallpaperService: updateSurface:[forceRelayout]true[redrawNeeded]false
08-31 16:50:25.599  3946  3946 V WallpaperService: Changes: creating=false format=false size=false
08-31 16:50:25.599  3946  3946 V WallpaperService: currentWidth:2240 currentHeight:2560 requestedWidth:2240 requestedWidth:2560
08-31 16:50:25.599  3381  4419 V WindowManager: addAppToken: AppWindowToken{d0f0b877e token=Token{f72c539 ActivityRecord{3fbc900 u0 com.test.thalitest/.MainActivity t37}}} to stack=2 task=37 at 0
08-31 16:50:25.609  3946  3946 V WallpaperService: relayout result: Surface(name=null)/@0x8b195ce, frame=Rect(0, 0 - 2240, 2560),relayoutResult:1, mConfiguration{0 1.0 themeSeq = 0 showBtnBg = -1 ?mcc?mnc pl_PL ?layoutDir ?swdp ?wdp ?hdp ?density ?lsize ?long ?orien ?uimode ?night ?touch ?keyb/?/? ?nav/? mkbd/?}
08-31 16:50:25.609  3946  3946 V WallpaperService: Wallpaper size has changed: (2240, 2560)
08-31 16:50:25.609  3381  3562 I InjectionManager: Inside getClassLibPath caller 
08-31 16:50:25.619  3381  3562 D SecWifiDisplayUtil: Metadata value : SecSettings2
08-31 16:50:25.619  3381  3562 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{2670856 V.E...... R.....ID 0,0-0,0}
08-31 16:50:25.619  8726  8726 E Zygote  : v2
08-31 16:50:25.619  8726  8726 I libpersona: KNOX_SDCARD checking this for 10177
08-31 16:50:25.619  8726  8726 I libpersona: KNOX_SDCARD not a persona
08-31 16:50:25.619  8726  8726 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
08-31 16:50:25.619  3381  3562 W WindowManager: Failed looking up window
08-31 16:50:25.619  3381  3562 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@2ecf0d7 does not exist
08-31 16:50:25.619  3381  3562 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
08-31 16:50:25.619  3381  3562 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
08-31 16:50:25.619  3381  3562 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
08-31 16:50:25.619  3381  3562 W WindowManager: 	at android.view.ViewRootImpl.pokeDrawLockIfNeeded(ViewRootImpl.java:1203)
08-31 16:50:25.619  3381  3562 W WindowManager: 	at android.view.ViewRootImpl.scheduleTraversals(ViewRootImpl.java:1415)
08-31 16:50:25.619  3381  3562 W WindowManager: 	at android.view.ViewRootImpl.requestLayout(ViewRootImpl.java:1222)
08-31 16:50:25.619  3381  3562 W WindowManager: 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:800)
08-31 16:50:25.619  3381  3562 W WindowManager: 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:337)
08-31 16:50:25.619  3381  3562 W WindowManager: 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:91)
08-31 16:50:25.619  3381  3562 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4378)
08-31 16:50:25.619  3381  3562 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
08-31 16:50:25.619  3381  3562 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 16:50:25.619  3381  3562 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
08-31 16:50:25.619  3381  3562 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 16:50:25.619  3381  3562 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-31 16:50:25.619  8726  8726 E Zygote  : accessInfo : 0
08-31 16:50:25.629  3381  3562 D ISSUE_DEBUG: InputChannelName : d8e3dc4 Starting com.test.thalitest
08-31 16:50:25.629  8726  8726 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
08-31 16:50:25.629  3381  4419 I ActivityManager: Start proc 8726:com.test.thalitest/u0a177 for activity com.test.thalitest/.MainActivity
08-31 16:50:25.629  3381  4419 D InputDispatcher: Focused application set to: xxxx
08-31 16:50:25.629  3381  3854 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-31 16:50:25.629  8702  8702 D AndroidRuntime: Shutting down VM
08-31 16:50:25.639  3009  3009 I SurfaceFlinger: id=17 createSurf (1x1),1 flag=404, uhalitest
08-31 16:50:25.649  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
08-31 16:50:25.649  3381  4428 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.simplesharing, Auto Run ON
08-31 16:50:25.659  4292  4292 D LauncherApplication: galaxy labs cursor count is 0
08-31 16:50:25.669  8726  8726 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:50:25.669  8726  8726 D ActivityThread: Added TimaKeyStore provider
08-31 16:50:25.669  3381  4915 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f20a0cc u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8c548ae 4568:com.google.android.gms/u0a21}
08-31 16:50:25.669  3381  3562 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
08-31 16:50:25.679  3381  3854 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-31 16:50:25.689  5674  5674 E CocktailBarPositionManager: Window direction: 0
08-31 16:50:25.689  5674  5674 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
08-31 16:50:25.689  3381  4304 D ActivityManager:  Launching com.test.thalitest, updated priority
08-31 16:50:25.709  3381  3381 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
08-31 16:50:25.709  5674  6500 I TrayUsageStatesWatcher: noteResumeComponent : ComponentInfo{com.test.thalitest/com.test.thalitest.MainActivity} Intent { flg=0x10000000 cmp=com.test.thalitest/.MainActivity VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
08-31 16:50:25.719  3381  3562 V WindowStateAnimator: Finishing drawing window Window{d8e3dc4 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
08-31 16:50:25.729  3009  3009 D libEGL  : eglInitialize EGLDisplay = 0x7fe84f8be8
08-31 16:50:25.829  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-31 16:50:26.009  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-31 16:50:26.009  5674  5674 I TrayVisibilityController: handleMessage : msg.what = 1
,08-31 16:50:26.019  3381  4304 I WindowManager: Screenshot max retries 4 of Token{f72c539 ActivityRecord{3fbc900 u0 com.test.thalitest/.MainActivity t37}} appWin=Window{d8e3dc4 u0 d0 Starting com.test.thalitest} drawState=4
,08-31 16:50:26.019  5674  5684 I TrayUsageStatesWatcher: notePauseComponent : ComponentInfo{com.test.thalitest/com.test.thalitest.MainActivity}
,08-31 16:50:26.049  3381  3523 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
,08-31 16:50:26.049  5674  5674 I Utils   : isCurrentUser current = 0, ownerId = 0
08-31 16:50:26.049  5674  5674 I TrayVisibilityController: getComputedTrayVisible : keyguardState = 3
08-31 16:50:26.049  5674  5674 I TrayVisibilityController: updateTrayVisible : State : 3 visible = 2 mCurrentVisible = 2
,08-31 16:50:26.059  3381  5953 D GameManagerService: identifyGamePackage. com.test.thalitest
,08-31 16:50:26.059  8726  8726 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,08-31 16:50:26.059  8726  8726 D RelationGraph: garbageCollect()
,08-31 16:50:26.069  8726  8726 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
,08-31 16:50:26.069  4292  4292 V ActivityThread: updateVisibility : ActivityRecord{791c005 token=android.os.BinderProxy@bcc2591 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
,08-31 16:50:26.069  3381  4771 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f20a0cc u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8c548ae 4568:com.google.android.gms/u0a21}
08-31 16:50:26.069  4292  4292 D Launcher: onTrimMemory. Level: 20
08-31 16:50:26.069  3381  3851 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,08-31 16:50:26.069  8726  8726 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,08-31 16:50:26.069  3009  4540 I SurfaceFlinger: Modify Choreographer's phase offset to 0
,08-31 16:50:26.079  3009  3020 I SurfaceFlinger: Modify SurfaceFlinger's phase offset to 0
,08-31 16:50:26.079  3381  5953 D GameManagerService: identifyGamePackage. com.test.thalitest
,08-31 16:50:26.079  3381  5953 D N       : limitCPUFreq:: freq = 2496000
,08-31 16:50:26.079  3381  5953 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MAX_LIMIT  frequency : 2496000  uid : 1000  pid : 3381  pkgName : SIOP_ARM_MAX@22
,08-31 16:50:26.079  4568  4568 D AsyncTaskServiceImpl: Submit a task: k
,08-31 16:50:26.089  8726  8726 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:26.089  3009  4336 D libEGL  : eglTerminate EGLDisplay = 0x7f781fee78
08-31 16:50:26.089  3009  4336 D libEGL  : eglTerminate EGLDisplay = 0x7f781fee78
,08-31 16:50:26.099  3009  3018 I SurfaceFlinger: id=10 Removed MauncherAct (6/11)
08-31 16:50:26.099  3009  4540 I SurfaceFlinger: id=10 Removed MauncherAct (-2/11)
,08-31 16:50:26.099  8726  8726 I InjectionManager: Inside getClassLibPath caller 
,08-31 16:50:26.109  3009  3009 D libEGL  : eglTerminate EGLDisplay = 0x7fe84f8d08
08-31 16:50:26.119  4568  8739 D k       : Processing package: com.test.thalitest
,08-31 16:50:26.119  3381  4558 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f20a0cc u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8c548ae 4568:com.google.android.gms/u0a21}
,08-31 16:50:26.129  4568  8739 D GassUtils: Found app info for package com.test.thalitest:19. Hash: 864f03fe3ff04107c0cf32bdae9dc2051eeb22f81b585d28acec96d4114a47f5
08-31 16:50:26.129  3381  5953 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:50:26.129  4568  8739 D k       : Found info for package com.test.thalitest in db.
08-31 16:50:26.129  3381  5953 D GameManagerService: identifyGamePackage. com.test.thalitest
08-31 16:50:26.129  8726  8726 D InjectionManager: InjectionManager
08-31 16:50:26.129  3381  5953 D N       : limitCPUFreq:: freq = -1
08-31 16:50:26.129  8726  8726 D InjectionManager: fillFeatureStoreMap com.test.thalitest
08-31 16:50:26.129  3381  5953 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MAX_LIMIT  frequency : 2496000  uid : 1000  pid : 3381  tag : SIOP_ARM_MAX@22
08-31 16:50:26.129  8726  8726 I InjectionManager: Constructor com.test.thalitest, Feature store :{}
08-31 16:50:26.129  8726  8726 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
08-31 16:50:26.129  8726  8726 I InjectionManager: featureStore :{}
08-31 16:50:26.129  4568  8725 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
08-31 16:50:26.129  8726  8726 D RelationGraph: garbageCollect()
,08-31 16:50:26.139  8726  8726 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
,08-31 16:50:26.159  3381  5953 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,08-31 16:50:26.159  3381  5953 D GameManagerService: identifyGamePackage. com.test.thalitest
08-31 16:50:26.159  3381  5953 D GameManagerService: identifyGamePackage. com.test.thalitest
,08-31 16:50:26.159  3381  3461 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f20a0cc u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8c548ae 4568:com.google.android.gms/u0a21}
,08-31 16:50:26.159  8726  8726 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310550)
,08-31 16:50:26.179  3381  5025 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
,08-31 16:50:26.179  3381  3461 D ActivityManager:  Launching com.google.android.gms, updated priority
,08-31 16:50:26.189  3381  5025 V MARsPolicyManager: updateSMDBValues
,08-31 16:50:26.189  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-31 16:50:26.189  3381  3557 E MARsDBManager: updateDBAll : begin --size 1
08-31 16:50:26.199  8726  8726 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package com.google.android.webview
,08-31 16:50:26.199  8726  8726 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:26.199  8726  8726 I InjectionManager: Inside getClassLibPath caller 
,08-31 16:50:26.209  3381  4428 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f20a0cc u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{51aad4d 4305:com.google.android.gms.persistent/u0a21}
,08-31 16:50:26.229  8726  8726 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-31 16:50:26.229  4568  8725 D WearableController: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
08-31 16:50:26.229  3381  3557 E MARsDBManager: updateDBAll : end
08-31 16:50:26.229  3381  3557 D MARsDBManager: onChange - mSmartManagerObserver! Uri = content://com.samsung.android.sm/AppFreezer?MARs-self=true&MARs=true
,08-31 16:50:26.249  3381  4419 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f20a0cc u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{51aad4d 4305:com.google.android.gms.persistent/u0a21}
,08-31 16:50:26.279  8726  8726 I cr_LibraryLoader: Time to load native libraries: 29 ms (timestamps 7038-7067)
,08-31 16:50:26.279  8726  8726 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
,08-31 16:50:26.309  8749  8749 E Zygote  : v2
08-31 16:50:26.309  8749  8749 I libpersona: KNOX_SDCARD checking this for 10025
08-31 16:50:26.319  8726  8748 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
08-31 16:50:26.309  8749  8749 I libpersona: KNOX_SDCARD not a persona
,08-31 16:50:26.319  8749  8749 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,08-31 16:50:26.319  8749  8749 E Zygote  : accessInfo : 0
,08-31 16:50:26.319  8749  8749 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.partnersetup 
08-31 16:50:26.319  3381  4915 I ActivityManager: Start proc 8749:com.google.android.partnersetup/u0a25 for broadcast-3 com.google.android.partnersetup/.RlzPingBroadcastReceiver
,08-31 16:50:26.319  8726  8726 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {42343fd}
08-31 16:50:26.319  8726  8726 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
,08-31 16:50:26.329  3381  3878 D MdnieScenarioControlService:  packageName : com.test.thalitest    className : com.test.thalitest.MainActivity
,08-31 16:50:26.339  8726  8726 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
,08-31 16:50:26.349  8749  8749 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:50:26.349  8749  8749 D ActivityThread: Added TimaKeyStore provider
,08-31 16:50:26.359  4568  8740 I PeopleContactsSync: triggerPendingContactsCleanup: no accounts
,08-31 16:50:26.359  3381  4915 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity newState = 1 callingPackage = 10021
,08-31 16:50:26.369  3381  3460 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f20a0cc u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7a75419 8749:com.google.android.partnersetup/u0a25}
,08-31 16:50:26.369  8726  8726 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
08-31 16:50:26.369  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-31 16:50:26.389  8749  8749 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,08-31 16:50:26.389  8749  8749 D RelationGraph: garbageCollect()
,08-31 16:50:26.389  8749  8749 W ResourcesManager: getTopLevelResources: /system/priv-app/GooglePartnerSetup/GooglePartnerSetup.apk / 1.0 running in com.google.android.partnersetup rsrc of package com.google.android.partnersetup
,08-31 16:50:26.399  3381  4419 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,08-31 16:50:26.399  8749  8749 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,08-31 16:50:26.399  4568  8740 I PeopleDatabaseHelper: cleanUpNonGplusAccounts done.
,08-31 16:50:26.409  8749  8749 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:26.409  8749  8749 I InjectionManager: Inside getClassLibPath caller 
,08-31 16:50:26.419  8749  8749 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePartnerSetup/lib/arm64
,08-31 16:50:26.429  3381  3878 I MdnieScenarioControlService: mGameModeLauncher : false
08-31 16:50:26.429  3381  3878 I MdnieScenarioControlService: setUIMode
,08-31 16:50:26.429  8749  8749 D InjectionManager: InjectionManager
08-31 16:50:26.429  8749  8749 D InjectionManager: fillFeatureStoreMap com.google.android.partnersetup
,08-31 16:50:26.429  8749  8749 I InjectionManager: Constructor com.google.android.partnersetup, Feature store :{}
08-31 16:50:26.429  8749  8749 I InjectionManager: featureStore :{}
,08-31 16:50:26.439  4568  8740 I PeopleContactsSync: triggerPendingContactsCleanup: no accounts
,08-31 16:50:26.439  8726  8763 W chromium: [WARNING:dns_config_service_posix.cc(306)] Failed to read DnsConfig.
,08-31 16:50:26.449  3381  4411 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f20a0cc u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7a75419 8749:com.google.android.partnersetup/u0a25}
,08-31 16:50:26.469  3381  4771 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f20a0cc u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5f71e8 8383:com.android.vending/u0a35}
,08-31 16:50:26.479  4146  4161 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg com.android.vending,id=1003285959,extra=Bundle[mParcelledData.dataSize=84]
08-31 16:50:26.479  4146  4146 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=1003285959, samsung.notification.type=normal, samsung.people.package_name=com.android.vending}]
08-31 16:50:26.479  4146  4146 I PeopleStripeService: PeopleNotificationReceiver:3
08-31 16:50:26.479  4146  4146 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
08-31 16:50:26.479  4146  4146 I PeopleDataManager: removeNotification
08-31 16:50:26.479  4146  4146 I NotificationParser: getNotiType:com.android.vending,null
08-31 16:50:26.479  4146  4146 D PeopleDataManager: removeNotiInfo: id =1003285959,packageName=com.android.vending,isEdgeNotification=false,key=null,removeAll=false
08-31 16:50:26.479  4146  4146 D PeopleDataManager: removeNotiInfo =null
,08-31 16:50:26.489  8726  8726 D libEGL  : eglInitialize EGLDisplay = 0xffd1900c
,08-31 16:50:26.509  8383  8383 I Finsky  : [1] com.google.android.finsky.utils.PermissionPolicies$PermissionPolicyService.onStartCommand(117): post-install permissions check for com.test.thalitest
,08-31 16:50:26.519  8383  8383 W Finsky  : [1] com.google.android.finsky.FinskyApp.i(1379): No account configured on this device.
,08-31 16:50:26.519  3381  4181 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f20a0cc u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6284b71 8433:com.sec.android.app.shealth:remote/u0a39}
,08-31 16:50:26.519  3381  3523 W ActivityManager: Activity pause timeout for ActivityRecord{3fbc900 u0 com.test.thalitest/.MainActivity t37}
,08-31 16:50:26.529  8383  8383 I Finsky  : [1] com.google.android.finsky.utils.bc.run(2302): Package state data is missing for com.test.thalitest
,08-31 16:50:26.529  8383  8383 W Finsky  : [1] com.google.android.finsky.FinskyApp.i(1379): No account configured on this device.
,08-31 16:50:26.549  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-31 16:50:26.549  8794  8794 E Zygote  : v2
08-31 16:50:26.549  8794  8794 I libpersona: KNOX_SDCARD checking this for 10043
08-31 16:50:26.549  8794  8794 I libpersona: KNOX_SDCARD not a persona
,08-31 16:50:26.549  8794  8794 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,08-31 16:50:26.549  8794  8794 E Zygote  : accessInfo : 0
08-31 16:50:26.549  3381  4558 I ActivityManager: Start proc 8794:com.samsung.voiceserviceplatform/u0a43 for broadcast-3 com.samsung.voiceserviceplatform/com.samsung.vsf.sharedlib.utils.TTSPlayer$TTSDownloadReceiver
08-31 16:50:26.559  8794  8794 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.voiceserviceplatform 
,08-31 16:50:26.559  3381  3975 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10177
,08-31 16:50:26.559  3381  3975 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29734 com.android.server.am.ActivityManagerService.registerReceiver:22599 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,08-31 16:50:26.569  3381  4773 I ActivityManager: Killing 8184:com.samsung.android.app.assistantmenu/1000 (adj 15): DHA:empty #33
,08-31 16:50:26.579  8794  8794 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:50:26.579  8794  8794 D ActivityThread: Added TimaKeyStore provider
,08-31 16:50:26.589  3381  4179 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.assistantmenu, Auto Run ON
,08-31 16:50:26.609  3381  4304 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f20a0cc u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2ff3fd 8794:com.samsung.voiceserviceplatform/u0a43}
,08-31 16:50:26.619  8794  8794 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,08-31 16:50:26.619  8794  8794 D RelationGraph: garbageCollect()
,08-31 16:50:26.619  8794  8794 W ResourcesManager: getTopLevelResources: /system/priv-app/SVoice_1.0/SVoice_1.0.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.samsung.voiceserviceplatform
,08-31 16:50:26.619  3381  3460 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,08-31 16:50:26.619  8794  8794 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,08-31 16:50:26.629  8794  8794 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:26.629  8794  8794 I InjectionManager: Inside getClassLibPath caller 
,08-31 16:50:26.649  8726  8726 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,08-31 16:50:26.669  8726  8726 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-31 16:50:26.669  8726  8726 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,08-31 16:50:26.699  8726  8726 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-31 16:50:26.729  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
08-31 16:50:26.729  8794  8794 I BNRClientProivder, VERSION : 1.7.8: register - started.
08-31 16:50:26.739  8726  8726 D Activity: performCreate Call Injection manager
08-31 16:50:26.739  8726  8726 I InjectionManager: dispatchOnViewCreated > Target : com.test.thalitest.MainActivity isFragment :false
08-31 16:50:26.749  8726  8726 D SecWifiDisplayUtil: Metadata value : SecSettings2
08-31 16:50:26.749  8726  8726 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{68b6420 I.E...... R.....ID 0,0-0,0}
08-31 16:50:26.759  8726  8813 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
08-31 16:50:26.759  3381  3851 W WindowManager: Failed looking up window
08-31 16:50:26.759  3381  3851 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@927e44a does not exist
08-31 16:50:26.759  3381  3851 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
08-31 16:50:26.759  3381  3851 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
08-31 16:50:26.759  3381  3851 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
08-31 16:50:26.759  3381  3851 W WindowManager: 	at android.view.IWindowSession$Stub.onTransact(IWindowSession.java:688)
08-31 16:50:26.759  3381  3851 W WindowManager: 	at com.android.server.wm.Session.onTransact(Session.java:139)
08-31 16:50:26.759  3381  3851 W WindowManager: 	at android.os.Binder.execTransact(Binder.java:453)
08-31 16:50:26.759  3381  3974 D ISSUE_DEBUG: InputChannelName : 8c6efbb com.test.thalitest/com.test.thalitest.MainActivity
08-31 16:50:26.769  3381  4773 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
08-31 16:50:26.769  3381  4773 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-31 16:50:26.769  3381  3381 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-31 16:50:26.769  3381  3381 I KnoxTimeoutHandler: Shared devices show user statefalse
08-31 16:50:26.769  8726  8726 V ActivityThread: updateVisibility : ActivityRecord{8b9727f token=android.os.BinderProxy@9c5a9a8 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-31 16:50:26.779  8726  8748 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
08-31 16:50:26.799  8726  8726 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10177, CallingPid : 8726
08-31 16:50:26.799  3381  4181 D ConnectivityService: listenForNetwork for Listen from uid/pid:10177/8726 for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:50:26.829  8726  8726 D SecWifiDisplayUtil: Metadata value : SecSettings2
08-31 16:50:26.849  3009  3009 I SurfaceFlinger: id=18 createSurf (1x1),1 flag=404, NainActivit
08-31 16:50:26.869  8726  8813 D libEGL  : eglInitialize EGLDisplay = 0xdc9bf7c4
08-31 16:50:26.869  8726  8813 I OpenGLRenderer: Initialized EGL, version 1.4
08-31 16:50:26.869  8726  8813 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
08-31 16:50:26.879  3381  4428 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3381
08-31 16:50:26.879  3381  4428 I libsuspend: !@autosuspend_wakeup_count_disable
08-31 16:50:26.879  3381  4428 D PowerManagerService: mDisplayReady: false
08-31 16:50:26.879  3381  4428 I libsuspend: !@autosuspend_wakeup_count_disable done
08-31 16:50:26.879  3381  4428 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
08-31 16:50:26.879  3381  3568 D DisplayPowerController: animateScreenStateChange[0]: target=3
08-31 16:50:26.879  3381  3568 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
08-31 16:50:26.879  3381  3568 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
08-31 16:50:26.879  3381  3568 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
08-31 16:50:26.879  3381  3578 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
08-31 16:50:26.879  3009  3009 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7f80383c00
08-31 16:50:26.879  3009  3009 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
08-31 16:50:26.879  3381  3562 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
08-31 16:50:26.879  3381  3562 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
08-31 16:50:26.889  8726  8726 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
08-31 16:50:26.899  3381  3568 D DisplayPowerController: animateScreenStateChange[0]: target=3
08-31 16:50:26.899  3381  3568 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
08-31 16:50:26.899  3381  3568 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
08-31 16:50:26.899  8794  8794 I BNRClientProivder, VERSION : 1.7.8: register - xml6 quick_backup : SVOICESETTING, bLEmzxKOex, com.samsung.voiceserviceplatform.SCloudBackUp
08-31 16:50:26.899  3381  3568 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
08-31 16:50:26.899  3381  3568 I libsuspend: !@autosuspend_wakeup_count_enable
08-31 16:50:26.899  3381  3568 D DisplayPowerController: animateScreenStateChange[0]: target=3
08-31 16:50:26.899  3381  3568 I libsuspend: !@autosuspend_wakeup_count_enable done
08-31 16:50:26.899  3381  3568 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
08-31 16:50:26.899  3381  3568 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
08-31 16:50:26.899  3381  3568 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
08-31 16:50:26.899  3381  3568 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
08-31 16:50:26.899  3381  3568 D PowerManagerService: mDisplayReady: true
08-31 16:50:26.899  3381  3568 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
08-31 16:50:26.899  8794  8794 I QBNRClientHelper: init SyncClientHelper : SVOICESETTING
08-31 16:50:26.909  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
08-31 16:50:26.919  5674  5674 E CocktailBarPositionManager: Window direction: 0
08-31 16:50:26.919  5674  5674 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
08-31 16:50:26.919  3381  3460 V WindowStateAnimator: Finishing drawing window Window{8c6efbb u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
08-31 16:50:26.919  8726  8726 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
08-31 16:50:26.929  8794  8794 I l       : :main:VSP::S Voice language is null. Set to System Locale
08-31 16:50:26.929  3381  3851 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3381
08-31 16:50:26.929  8794  8794 I l       : :main:VSP::setLocale locale : pl_PL
08-31 16:50:26.929  8794  8794 W ResourcesManager: getTopLevelResources: /system/priv-app/SVoice_1.0/SVoice_1.0.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.samsung.voiceserviceplatform
08-31 16:50:26.939  8794  8794 D ResourcesManager: For user 0 new overlays fetched Null
08-31 16:50:26.939  3381  3461 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3381
08-31 16:50:26.939  8794  8794 I QuickDialApplication: :main:VSP::QuickDialApplication Started ver:1.9.35-130 (193502130
08-31 16:50:26.939  3381  3562 D ActivityManager: mDVFSHelper.release()
08-31 16:50:26.939  3381  3562 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-31 16:50:26.939  3381  3381 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-31 16:50:26.939  3381  3562 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +916ms (total +1s331ms)
08-31 16:50:26.939  3381  3562 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3fbc900 u0 com.test.thalitest/.MainActivity t37} time:77725
08-31 16:50:26.939  8726  8818 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-31 16:50:26.939  8726  8818 D libEGL  : eglInitialize EGLDisplay = 0xdc19f3f4
08-31 16:50:26.939  3381  3381 I KnoxTimeoutHandler: SD activityfalse
08-31 16:50:26.949  8794  8794 I VoiceServicePlatformApp:main:  : VSP::SvoiceApp Oncreate()
08-31 16:50:26.949  3381  4771 V WindowStateAnimator: Finishing drawing window Window{8c6efbb u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
08-31 16:50:26.949  3381  3562 D ViewRootImpl: #3 mView = null
08-31 16:50:26.949  3009  4540 I SurfaceFlinger: id=17 Removed uhalitest (6/11)
08-31 16:50:26.949  3009  3020 I SurfaceFlinger: id=17 Removed uhalitest (-2/11)
08-31 16:50:26.949  8726  8726 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@9c5a9a8 time:77735
08-31 16:50:26.949  3009  3009 D libEGL  : eglTerminate EGLDisplay = 0x7fe84f8d08
08-31 16:50:26.959  8726  8818 D libGLESv2: DTS_GLAPI : DTS is not allowed for Package : com.test.thalitest
08-31 16:50:26.959  8794  8794 I AppSessionManager:main:  : VSP::init() Update from sharedpref
08-31 16:50:26.959  8794  8794 I AppSessionManager:main:  : VSP::init() Update from sharedpref
08-31 16:50:26.979  8822  8822 E Zygote  : v2
08-31 16:50:26.979  8822  8822 I libpersona: KNOX_SDCARD checking this for 10043
08-31 16:50:26.979  8822  8822 I libpersona: KNOX_SDCARD not a persona
08-31 16:50:26.979  8822  8822 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
08-31 16:50:26.979  8822  8822 E Zygote  : accessInfo : 0
08-31 16:50:26.979  8822  8822 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.svoice.sync 
08-31 16:50:26.979  3381  4915 I ActivityManager: Start proc 8822:com.samsung.svoice.sync/u0a43 for content provider com.samsung.svoice.sync/com.svoice.upload.database.PLMProvider
08-31 16:50:26.999  8726  8726 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 8726
08-31 16:50:27.009  8822  8822 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:50:27.009  8822  8822 D ActivityThread: Added TimaKeyStore provider
08-31 16:50:27.019  8822  8822 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
08-31 16:50:27.029  8822  8822 D RelationGraph: garbageCollect()
08-31 16:50:27.029  8822  8822 W ResourcesManager: getTopLevelResources: /system/priv-app/SVoicePLM_1.0/SVoicePLM_1.0.apk / 1.0 running in com.samsung.svoice.sync rsrc of package com.samsung.svoice.sync
08-31 16:50:27.029  3381  4771 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
08-31 16:50:27.029  8822  8822 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
08-31 16:50:27.029  8822  8822 D ResourcesManager: For user 0 new overlays fetched Null
08-31 16:50:27.029  8822  8822 I InjectionManager: Inside getClassLibPath caller 
08-31 16:50:27.039  8822  8822 I UploadDatabase: svoicelocal DB: main : PLM :: mUploadDBManager is null , creating new one !! 
08-31 16:50:27.049  3381  5955 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
08-31 16:50:27.049  8822  8822 E SQLiteLog: (5) statement aborts at 2: [PRAGMA journal_mode=PERSIST] 
08-31 16:50:27.049  8822  8822 W SQLiteConnection: Could not change the database journal mode of '/data/user/0/com.samsung.svoice.sync/databases/svoicelocal.db' from 'wal' to 'PERSIST' because the database is locked.  This usually means that there are other open connections to the database which prevents the database from enabling or disabling write-ahead logging mode.  Proceeding without changing the journal mode.
08-31 16:50:27.049  8822  8822 D InjectionManager: InjectionManager
08-31 16:50:27.049  8822  8822 D InjectionManager: fillFeatureStoreMap com.samsung.svoice.sync
08-31 16:50:27.059  8822  8822 I InjectionManager: Constructor com.samsung.svoice.sync, Feature store :{}
08-31 16:50:27.059  8822  8822 I InjectionManager: featureStore :{}
08-31 16:50:27.059  8822  8832 D PLMProvider: match for uri : content://com.samsung.svoice.sync/tos_accepted is : 8
08-31 16:50:27.069  8794  8794 I SVFSettings:main:  : VSP::inside updateAppLocale() en_US
08-31 16:50:27.069  8794  8794 I SVFSettings:main:  : VSP::Current locale string in updateAppLocale method en-US
08-31 16:50:27.069  8794  8794 I SVFSettings:main:  : VSP::After updateing N66_ComamndHandler current locale is en-US
08-31 16:50:27.079  8794  8794 D DeviceInfo: DeviceInfo
08-31 16:50:27.089  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
08-31 16:50:27.089  3381  3381 I libsuspend: !@autosuspend_wakeup_count_disable
08-31 16:50:27.089  3381  3381 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3381 (0x0)
08-31 16:50:27.089  3381  3381 I libsuspend: !@autosuspend_wakeup_count_disable done
08-31 16:50:27.089  3381  3381 D PowerManagerService: mDisplayReady: false
08-31 16:50:27.089  3381  3381 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
08-31 16:50:27.089  3381  3568 D DisplayPowerController: animateScreenStateChange[0]: target=4
08-31 16:50:27.089  3381  3568 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
08-31 16:50:27.089  3381  3568 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
08-31 16:50:27.089  3381  3568 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
08-31 16:50:27.089  3381  3578 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
08-31 16:50:27.089  3381  3562 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
08-31 16:50:27.089  3381  3562 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
08-31 16:50:27.089  3009  3009 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7f80383c00
08-31 16:50:27.089  3009  3009 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
08-31 16:50:27.099  3381  3568 D DisplayPowerController: animateScreenStateChange[0]: target=4
08-31 16:50:27.099  3381  3568 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
08-31 16:50:27.099  3381  3568 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
08-31 16:50:27.099  3381  3568 I libsuspend: !@autosuspend_wakeup_count_enable
08-31 16:50:27.099  3381  3568 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
08-31 16:50:27.099  3381  3568 I libsuspend: !@autosuspend_wakeup_count_enable done
08-31 16:50:27.099  3381  3568 D DisplayPowerController: animateScreenStateChange[0]: target=4
08-31 16:50:27.099  3381  3568 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
08-31 16:50:27.099  3381  3568 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
08-31 16:50:27.099  3381  3568 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
08-31 16:50:27.099  3381  3568 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
08-31 16:50:27.099  3381  3568 D PowerManagerService: mDisplayReady: true
08-31 16:50:27.099  3381  3568 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
08-31 16:50:27.109  8794  8794 D DeviceInfo: getLocale =  en-US
08-31 16:50:27.109  8794  8794 I N66_CommonHandler:main:  : VSP:: locale info at present in updateServerBasedOnlanguage : en-US
08-31 16:50:27.109  8794  8794 I N66_CommonHandler:main:  : VSP::Current configured server is interaction-us2.samsung-svoice.com
08-31 16:50:27.109  8794  8794 I N66_CommonHandler:main:  : VSP::Current configured server port is 443
08-31 16:50:27.109  5674  5674 E CocktailBarPositionManager: Window direction: 0
08-31 16:50:27.109  5674  5674 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
08-31 16:50:27.119  8794  8794 D SettingsValueDB:main:  : VSP:: match for uri : content://com.samsung.voiceserviceplatform.database.SettingsValueDB/SettingsvalueTb is : -1
08-31 16:50:27.119  8794  8794 D SettingsValueDB:main:  : VSP::URI didnt match
08-31 16:50:27.119  8794  8794 D SettingsValueDB:main:  : VSP:: match for uri : content://com.samsung.voiceserviceplatform.database.SettingsValueDB/SettingsvalueTb is : -1
08-31 16:50:27.119  8794  8794 D SettingsValueDB:main:  : VSP::URI didnt match
08-31 16:50:27.129  8794  8794 D SettingsValueDB:main:  : VSP:: match for uri : content://com.samsung.voiceserviceplatform.database.SettingsValueDB/language is : 3
08-31 16:50:27.129  8794  8794 D SettingsValueDB:main:  : VSP::lang from content values is  en_US
08-31 16:50:27.129  8794  8794 I skwskw:main:  : VSP::############################122 value : en_US
08-31 16:50:27.129  8822  8832 D PLMProvider: match for uri : content://com.samsung.svoice.sync/tos_accepted is : 8
08-31 16:50:27.129  8794  8794 I N66_CommonHandler:main:  : VSP:: rowUpdated : 1
08-31 16:50:27.129  8794  8794 D SVFSettings: updateServerBasedOnLang() connect to server US_PROD2_SERVER_HOST_IP
08-31 16:50:27.129  8794  8794 D p       : :main:VSP::setTargetServerAddress() : interaction-us2.samsung-svoice.com
08-31 16:50:27.129  8794  8794 D p       : :main:VSP::setTargetServerPort() : 443
08-31 16:50:27.159  8794  8794 W ResourcesManager: getTopLevelResources: /system/app/SamsungTTS/SamsungTTS.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.samsung.SMT
08-31 16:50:27.159  8794  8794 D ResourcesManager: For user 0 new overlays fetched Null
08-31 16:50:27.169  8794  8794 W ResourcesManager: getTopLevelResources: /system/app/GoogleTTS/GoogleTTS.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.tts
08-31 16:50:27.169  8794  8794 D ResourcesManager: For user 0 new overlays fetched Null
08-31 16:50:27.189  8842  8842 E Zygote  : v2
08-31 16:50:27.189  8842  8842 I libpersona: KNOX_SDCARD checking this for 1000
08-31 16:50:27.189  8842  8842 I libpersona: KNOX_SDCARD not a persona
08-31 16:50:27.189  8842  8842 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
08-31 16:50:27.189  8842  8842 E Zygote  : accessInfo : 0
08-31 16:50:27.199  3381  3975 I ActivityManager: Start proc 8842:com.samsung.SMT/1000 for service com.samsung.SMT/.SamsungTTSService
08-31 16:50:27.199  8794  8794 I TextToSpeech: Sucessfully bound to com.samsung.SMT
08-31 16:50:27.199  8794  8794 D Test    : Creating TTS instance!
08-31 16:50:27.209  8726  8726 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-31 16:50:27.209  8794  8794 I SamsungHTTPClient:main:  : VSP::MY THREAD ID UI : 1
08-31 16:50:27.209  8822  8832 D PLMProvider: match for uri : content://com.samsung.svoice.sync/device_id is : 1
08-31 16:50:27.219  8842  8842 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:50:27.219  8842  8842 D ActivityThread: Added TimaKeyStore provider
08-31 16:50:27.219  8822  8832 D PLMDeviceInfo: Binder_1 : PLM ::Device Id generation is complete
08-31 16:50:27.229  8794  8794 I svoiceapi_jar: RELEASE_DATE 2016 May 25
08-31 16:50:27.229  8794  8794 I svoiceapi_jar: RELEASE_VER  0.99_26_1_TCP_Prepare2_TTS
08-31 16:50:27.229  8794  8794 I svoiceapi_jar: Loading svoice dll
08-31 16:50:27.239  8842  8842 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
08-31 16:50:27.239  8842  8842 D RelationGraph: garbageCollect()
08-31 16:50:27.239  8842  8842 W ResourcesManager: getTopLevelResources: /system/app/SamsungTTS/SamsungTTS.apk / 1.0 running in com.samsung.SMT rsrc of package com.samsung.SMT
08-31 16:50:27.249  3381  4915 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
08-31 16:50:27.249  8842  8842 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
08-31 16:50:27.249  8842  8842 D ResourcesManager: For user 0 new overlays fetched Null
08-31 16:50:27.249  8842  8842 I InjectionManager: Inside getClassLibPath caller 
08-31 16:50:27.259  8842  8842 W System  : ClassLoader referenced unknown path: /system/app/SamsungTTS/lib/arm64
08-31 16:50:27.259  8842  8842 D InjectionManager: InjectionManager
08-31 16:50:27.259  8842  8842 D InjectionManager: fillFeatureStoreMap com.samsung.SMT
08-31 16:50:27.259  8842  8842 I InjectionManager: Constructor com.samsung.SMT, Feature store :{}
08-31 16:50:27.259  8842  8842 I InjectionManager: featureStore :{}
08-31 16:50:27.259  8794  8794 I svoiceapi_jar: Loading success
08-31 16:50:27.269  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
08-31 16:50:27.269  8794  8794 I svoiceapi: SVoiceSession Release Date : 2016 May 25
08-31 16:50:27.269  8794  8794 I svoiceapi: Library Ver : 0.99_26_1_TCP_Prepare2_TTS
08-31 16:50:27.269  8794  8794 I svoiceapi: SVoiceSession::SVoiceSession, Default loglevel = 5
08-31 16:50:27.269  8794  8794 I svoiceapi: create handle : 0xf4fb2680
08-31 16:50:27.269  8794  8794 I svoiceapi: Sentinel registered : -184668080
08-31 16:50:27.269  8794  8794 I svoiceapi: SVoiceSession::Enable logs, loglevel = 4
08-31 16:50:27.269  8794  8794 I sessionThread:main:  : VSP::LOG_LEVEL is set as 4
08-31 16:50:27.279  8794  8794 D ClientSDKManager : initNLUResponseList
08-31 16:50:27.279  8794  8794 D InjectionManager: InjectionManager
08-31 16:50:27.279  8794  8794 D InjectionManager: fillFeatureStoreMap com.samsung.voiceserviceplatform
08-31 16:50:27.279  8794  8794 I InjectionManager: Constructor com.samsung.voiceserviceplatform, Feature store :{}
08-31 16:50:27.279  8794  8794 I InjectionManager: featureStore :{}
08-31 16:50:27.279  8794  8862 I sessionThread: DEBUG : SDK : Session Thread run got called : 
08-31 16:50:27.279  8794  8862 I sessionThread:SessionThread:  : VSP::Inside processTask while loop; task is empty so sleeping : 
08-31 16:50:27.279  8794  8794 I SV_TTSPlayer: inside TTSDownloadReceiver
08-31 16:50:27.289  8794  8794 I VoiceFrameworkService:main:  : VSP::Oncreate() of Service
08-31 16:50:27.289  8794  8794 I VoiceFrameworkServiceHandler:main:  : VSP::VoiceFrameworkServiceHandler() Start
08-31 16:50:27.289  3381  4304 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f20a0cc u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9c9b41f 4385:android.process.acore/u0a5}
08-31 16:50:27.289  8794  8794 I VoiceFrameworkServiceHandler:main:  : VSP::MyHandlerThread
08-31 16:50:27.289  8794  8794 I VoiceFrameworkServiceHandler:main:  : VSP::VoiceFrameworkServiceHandler() end
08-31 16:50:27.289  8794  8863 I VoiceFrameworkServiceHandler:VoiceFrameworkServiceHandler MyHandlerThread:  : VSP::MyHandlerThread run
08-31 16:50:27.289  8794  8794 I VoiceFrameworkServiceHandler:main:  : VSP::sendMessagetoHandler Rcvd msgCode = 0
08-31 16:50:27.289  8794  8794 I VoiceFrameworkServiceHandler:main:  : VSP::sendMessagetoHandler mHandler = Handler (com.samsung.vsf.core.framework.VoiceFrameworkServiceHandler$MyHandlerThread$1) {46938f2}
08-31 16:50:27.289  8794  8794 I VoiceFrameworkServiceHandler:main:  : VSP:: sendMessagetoHandler() VSF Thread isAlive : true
08-31 16:50:27.299  8794  8794 I VoiceFrameworkServiceHandler:main:  : VSP::mHandler is not null msgCode =0
08-31 16:50:27.299  8794  8863 I VoiceFrameworkServiceHandler:VoiceFrameworkServiceHandler MyHandlerThread:  : VSP::MSG_VSF_INIT Rcvd
08-31 16:50:27.299  8794  8863 I VoiceFrameworkServiceHandler:VoiceFrameworkServiceHandler MyHandlerThread:  : VSP::VSFInit()
08-31 16:50:27.299  8794  8863 I VoiceServicePlatformSdk:VoiceFrameworkServiceHandler MyHandlerThread:  : VSP::Oncreate()
08-31 16:50:27.299  8726  8855 D jxcore_app_log: JniHelper::setJavaVM(0xf5034000), pthread_self() = -652216016
08-31 16:50:27.299  8726  8855 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-31 16:50:27.299  8726  8855 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-31 16:50:27.299  8726  8855 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-31 16:50:27.299  8726  8855 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-31 16:50:27.299  8726  8855 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-31 16:50:27.309  8726  8855 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f07f13 added. We now have 1 listener(s)
08-31 16:50:27.309  8726  8855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: A8:81:95:E9:5F:6F
08-31 16:50:27.309  8726  8855 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
08-31 16:50:27.309  8864  8864 I libpersona: KNOX_SDCARD checking this for 1000
08-31 16:50:27.309  8864  8864 E Zygote  : v2
08-31 16:50:27.309  8864  8864 I libpersona: KNOX_SDCARD not a persona
08-31 16:50:27.309  8726  8855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 16:50:27.309  8726  8855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 16:50:27.309  8864  8864 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
08-31 16:50:27.309  8864  8864 E Zygote  : accessInfo : 0
08-31 16:50:27.309  8726  8855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-31 16:50:27.309  8726  8855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-31 16:50:27.309  8726  8855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-31 16:50:27.309  8726  8855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: A8:81:95:E9:5F:6F
08-31 16:50:27.309  8726  8855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-31 16:50:27.309  8726  8855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-31 16:50:27.309  8726  8855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-31 16:50:27.309  8726  8855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-31 16:50:27.309  8726  8855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-31 16:50:27.309  8726  8855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-31 16:50:27.309  8726  8855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-31 16:50:27.309  8726  8855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-31 16:50:27.309  8726  8855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-31 16:50:27.309  8726  8855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-31 16:50:27.309  8726  8855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fa6f44e added. We now have 1 listener(s)
08-31 16:50:27.309  8726  8855 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 16:50:27.309  3381  4773 I ActivityManager: Start proc 8864:com.android.settings/1000 for broadcast-3 com.android.settings/.applock.PackageActionReceiver
08-31 16:50:27.329  8864  8864 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:50:27.329  8864  8864 D ActivityThread: Added TimaKeyStore provider
08-31 16:50:27.379  8726  8855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 16:50:27.379  8726  8855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-31 16:50:27.379  8726  8855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-31 16:50:27.379  8726  8855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-31 16:50:27.379  8726  8855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-31 16:50:27.389  8794  8863 I System.out: SVoiceProfiling : time taken to finish oncreate : 96
08-31 16:50:27.399  3381  4179 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f20a0cc u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fdb56ee 8864:com.android.settings/1000}
08-31 16:50:27.399  8726  8855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 16:50:27.399  8726  8855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is A8:81:95:E9:5F:6F
08-31 16:50:27.409  8822  8833 D PLMProvider: match for uri : content://com.samsung.svoice.sync/tos_accepted is : 8
08-31 16:50:27.409  8726  8855 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 16:50:27.409  8726  8855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 16:50:27.409  8726  8855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 16:50:27.409  8726  8855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-31 16:50:27.409  8726  8855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 16:50:27.409  8726  8855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 16:50:27.409  8726  8855 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 16:50:27.409  8726  8855 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 16:50:27.409  8726  8855 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 16:50:27.409  8726  8855 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-31 16:50:27.409  8726  8855 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 16:50:27.409  8726  8855 I io.jxcore.node.LifeCycleMonitor: start: OK
08-31 16:50:27.419  3381  4428 I ActivityManager: Killing 7697:com.samsung.android.communicationservice/5002 (adj 15): DHA:empty #33
08-31 16:50:27.419  4568  7015 I Icing   : Indexing E1051AF754FD4764B2B13213EB917898AAC96AFB from com.google.android.gms
08-31 16:50:27.429  8864  8864 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
08-31 16:50:27.429  8864  8864 D RelationGraph: garbageCollect()
08-31 16:50:27.429  8864  8864 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in com.android.settings rsrc of package com.android.settings
08-31 16:50:27.429  3381  4773 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
08-31 16:50:27.429  8864  8864 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
08-31 16:50:27.439  8794  8863 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'void android.location.LocationManager.requestLocationUpdates(long, float, android.location.Criteria, android.location.LocationListener, android.os.Looper)' on a null object reference
08-31 16:50:27.439  8864  8864 D ResourcesManager: For user 0 new overlays fetched Null
08-31 16:50:27.439  8794  8863 W System.err: 	at com.samsung.vsf.core.framework.SessionRuntime.requestLocationUpdate(SessionRuntime.java:336)
08-31 16:50:27.439  8794  8863 W System.err: 	at com.samsung.vsf.core.framework.SessionRuntime.registerNetworkReceiver(SessionRuntime.java:246)
08-31 16:50:27.439  8794  8863 W System.err: 	at com.samsung.vsf.core.framework.SessionRuntime.registerBroadcastReceivers(SessionRuntime.java:115)
08-31 16:50:27.439  8794  8863 W System.err: 	at com.samsung.vsf.core.framework.SessionRuntime.init(SessionRuntime.java:103)
08-31 16:50:27.439  8794  8863 W System.err: 	at com.samsung.vsf.core.framework.VoiceFrameworkServiceHandler.VSFInit(VoiceFrameworkServiceHandler.java:188)
08-31 16:50:27.439  8794  8863 W System.err: 	at com.samsung.vsf.core.framework.VoiceFrameworkServiceHandler.access$200(VoiceFrameworkServiceHandler.java:27)
08-31 16:50:27.439  8794  8863 W System.err: 	at com.samsung.vsf.core.framework.VoiceFrameworkServiceHandler$MyHandlerThread$1.handleMessage(VoiceFrameworkServiceHandler.java:109)
08-31 16:50:27.439  8794  8863 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 16:50:27.439  8794  8863 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-31 16:50:27.439  8794  8863 W System.err: 	at com.samsung.vsf.core.framework.VoiceFrameworkServiceHandler$MyHandlerThread.run(VoiceFrameworkServiceHandler.java:178)
08-31 16:50:27.449  8794  8863 I EmbeddedFrameworkManager:VoiceFrameworkServiceHandler MyHandlerThread:  : VSP::N66 locale is en_US
08-31 16:50:27.449  8864  8864 I InjectionManager: Inside getClassLibPath caller 
08-31 16:50:27.449  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
08-31 16:50:27.449  8726  8726 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
08-31 16:50:27.449  8794  8863 I EmbeddedFrameworkManager:VoiceFrameworkServiceHandler MyHandlerThread:  : VSP::SHL init():
08-31 16:50:27.449  8794  8863 I EmbeddedFrameworkManager:VoiceFrameworkServiceHandler MyHandlerThread: SHL Config:
08-31 16:50:27.449  8794  8863 I EmbeddedFrameworkManager:VoiceFrameworkServiceHandler MyHandlerThread: Locale: en_US
08-31 16:50:27.449  8794  8863 I EmbeddedFrameworkManager:VoiceFrameworkServiceHandler MyHandlerThread: Recognition Path: EMBEDDED
08-31 16:50:27.449  8794  8863 I EmbeddedFrameworkManager:VoiceFrameworkServiceHandler MyHandlerThread: Audio buffer format: PCM_NS
08-31 16:50:27.449  8794  8863 I EmbeddedFrameworkManager:VoiceFrameworkServiceHandler MyHandlerThread: Use internal recorder: false
08-31 16:50:27.449  8794  8863 I EmbeddedFrameworkManager:VoiceFrameworkServiceHandler MyHandlerThread: Use internal EPD: false
08-31 16:50:27.449  8794  8863 I SHL:VoiceFrameworkServiceHandler MyHandlerThread:  : VSP::SHL Initialize
08-31 16:50:27.449  8794  8863 I etickcount:VoiceFrameworkServiceHandler MyHandlerThread:  : VSP::PocketSphinxEngine:Trying to load libEmbeddedAsr.so
08-31 16:50:27.459  7754  7754 D Mms/MmsApp: CommunicationService Disconnected
08-31 16:50:27.459  3381  4771 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.communicationservice, Auto Run ON
08-31 16:50:27.459  3381  4771 W ActivityManager: Scheduling restart of crashed service com.samsung.android.communicationservice/.ITransactionManagerService in 1000ms
08-31 16:50:27.479  8864  8864 W System  : ClassLoader referenced unknown path: /system/priv-app/SecSettings2/lib/arm64
08-31 16:50:27.489  8794  8863 I etickcount:VoiceFrameworkServiceHandler MyHandlerThread:  : VSP::PocketSphinxEngine:loading libEmbeddedAsr.so done
08-31 16:50:27.509  8794  8863 I etickcount:VoiceFrameworkServiceHandler MyHandlerThread:  : VSP::State changed to NULL
08-31 16:50:27.509  8794  8863 I etickcount:VoiceFrameworkServiceHandler MyHandlerThread:  : VSP::Creating engines for en_US
08-31 16:50:27.509  8864  8864 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in com.android.settings rsrc of package com.android.settings
08-31 16:50:27.509  8864  8864 D SFinderConnectProvider: onCreate
08-31 16:50:27.509  8794  8863 D CMDTest : VoiceFrameworkServiceHandler MyHandlerThread : posted CreateCmd
08-31 16:50:27.509  8794  8863 I etickcount:VoiceFrameworkServiceHandler MyHandlerThread:  : VSP::RecognitionManager loading..
08-31 16:50:27.509  8794  8882 D tickcount:PocketSphinx Recognition Engine:  : VSP::CreateCmd execution latency: 1ms
08-31 16:50:27.509  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP::PocketSphinxEngine:create()
08-31 16:50:27.509  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP::State changed to INIT
08-31 16:50:27.509  8794  8863 D CMDTest : VoiceFrameworkServiceHandler MyHandlerThread : posted ConfigureCmd
08-31 16:50:27.509  8794  8863 I etickcount:VoiceFrameworkServiceHandler MyHandlerThread:  : VSP::State changed to INIT
08-31 16:50:27.519  8794  8863 I etickcount:VoiceFrameworkServiceHandler MyHandlerThread:  : VSP::setSpeechRecognitionListener: com.samsung.vsf.core.framework.embedded.EmbeddedFrameworkManager@4c9bdec
08-31 16:50:27.519  4568  7015 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.gms rsrc of package com.test.thalitest
08-31 16:50:27.529  8794  8882 D tickcount:PocketSphinx Recognition Engine:  : VSP::ConfigureCmd execution latency: 11ms
08-31 16:50:27.529  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP::PocketSphinxEngine:configure() in state INIT
08-31 16:50:27.529  8794  8882 W ResourcesManager: getTopLevelResources: /system/priv-app/SVoiceLang_EnglishPack_US_1.0/SVoiceLang_EnglishPack_US_1.0.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.svoice.lang.en_US
08-31 16:50:27.529  4019  4019 D Recents : onTaskStackChanged
08-31 16:50:27.529  8822  8832 D PLMProvider: match for uri : content://com.samsung.svoice.sync/tos_accepted is : 8
08-31 16:50:27.529  8794  8882 D ResourcesManager: For user 0 new overlays fetched Null
08-31 16:50:27.529  4568  7015 D ResourcesManager: For user 0 new overlays fetched Null
08-31 16:50:27.549  4568  7015 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.gms rsrc of package com.test.thalitest
08-31 16:50:27.559  4019  4019 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.test.thalitest
08-31 16:50:27.559  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP::MD5 Files From Assets : en_US.zip.MD5
08-31 16:50:27.559  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP:: Time Taken LoadMD5FromPackage:  0.001 seconds.
08-31 16:50:27.559  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP:: Time Taken LoadMD5FromAssets:  0.0 seconds.
08-31 16:50:27.559  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP:: MD5 Checked in :  0.029 seconds.
08-31 16:50:27.559  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP::No Update 0
08-31 16:50:27.559  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP:: #### No Update in The Models #####
08-31 16:50:27.559  8794  8882 D etickcount:PocketSphinx Recognition Engine:  : VSP::TimeTaken for unpacking 36ms
08-31 16:50:27.559  8794  8882 D etickcount: Lang is en_US
08-31 16:50:27.559  8794  8882 I PLMGenManager: Version  : V_030816
08-31 16:50:27.559  8794  8882 D Flag    : configFalg value : 0
08-31 16:50:27.559  8794  8882 D PLMGenManager: Is JSON file found ? false
08-31 16:50:27.559  8794  8882 D PLMGenManager: Config flag is : 0
,08-31 16:50:27.559  4568  7015 I Icing   : Indexing done E1051AF754FD4764B2B13213EB917898AAC96AFB
08-31 16:50:27.569  8794  8882 D AppInfo : TimeTaken for App Alias name generation : 4ms
,08-31 16:50:27.569  4019  4019 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:27.579  8794  8882 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2015/SecGallery2015.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.gallery3d
,08-31 16:50:27.589  8794  8882 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:27.589  8864  8864 I BNRClientProivder, VERSION : 1.7.5: register - xml6 quick_backup : ACCESSIBILITYSETTINGS, X6qErjsfs2, com.android.settings.accessibility.sharedaccessibility.scloud.BNRTask
,08-31 16:50:27.589  8864  8864 I QBNRClientHelper: init SyncClientHelper : ACCESSIBILITYSETTINGS
,08-31 16:50:27.589  8794  8882 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2015/SecGallery2015.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.gallery3d
08-31 16:50:27.589  8864  8864 I BNRClientProivder, VERSION : 1.7.5: register - xml6 quick_backup : CONNECTIONS, C0phMaUuZZ, com.android.settings.wifi.mobileap.WifiApBackupRestore
,08-31 16:50:27.589  8864  8864 I QBNRClientHelper: init SyncClientHelper : CONNECTIONS
,08-31 16:50:27.589  8864  8864 I BNRClientProivder, VERSION : 1.7.5: register - xml6 quick_backup : WiFi, C0phMaUuZZ, com.android.settings.wifi.WifiBackupRestore
08-31 16:50:27.589  8864  8864 I QBNRClientHelper: init SyncClientHelper : WiFi
,08-31 16:50:27.589  8794  8882 I PLM     : App title : Gallery & activity name : com.sec.android.gallery3d.app.GalleryOpaqueActivity_com.sec.android.gallery3d
08-31 16:50:27.589  8794  8882 W ResourcesManager: getTopLevelResources: /system/priv-app/Phonesky/Phonesky.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.android.vending
,08-31 16:50:27.599  8794  8882 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:27.599  8864  8864 D InjectionManager: InjectionManager
08-31 16:50:27.599  8864  8864 D InjectionManager: fillFeatureStoreMap com.android.settings
,08-31 16:50:27.599  8864  8864 I InjectionManager: Constructor com.android.settings, Feature store :{},
08-31 16:50:27.599  8864  8864 I InjectionManager: featureStore :{}
,08-31 16:50:27.599  8794  8882 W ResourcesManager: getTopLevelResources: /system/priv-app/Phonesky/Phonesky.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.android.vending
,08-31 16:50:27.599  3381  5990 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-31 16:50:27.599  8794  8882 I PLM     : App title : Play_Store & activity name : com.android.vending.AssetBrowserActivity_com.android.vending
,08-31 16:50:27.599  8794  8882 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.shealth
,08-31 16:50:27.609  8794  8882 D ResourcesManager: For user 0 new overlays fetched Null
08-31 16:50:27.609  3381  4419 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f20a0cc u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fdb56ee 8864:com.android.settings/1000}
,08-31 16:50:27.609  8794  8882 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.shealth
,08-31 16:50:27.609  8794  8882 I PLM     : App title : S_Health & activity name : com.samsung.android.app.shealth.home.HomeMainActivity_com.sec.android.app.shealth
,08-31 16:50:27.609  8794  8882 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCamera5/SamsungCamera5.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.camera
,08-31 16:50:27.609  8794  8882 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:27.619  8794  8882 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCamera5/SamsungCamera5.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.camera
,08-31 16:50:27.619  8794  8882 I PLM     : App title : Camera & activity name : com.sec.android.app.camera.Camera_com.sec.android.app.camera
,08-31 16:50:27.619  8794  8882 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.android.contacts
,08-31 16:50:27.619  8842  8842 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 android.content.ContextWrapper.sendBroadcast:410 com.samsung.SMT.b.i.a:-1 com.samsung.SMT.SamsungTTSService.onCreate:-1 android.app.ActivityThread.handleCreateService:3808 
,08-31 16:50:27.619  8794  8882 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:27.619  3381  4419 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f20a0cc u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fdb56ee 8864:com.android.settings/1000}
08-31 16:50:27.619  8864  8864 I DataWarningReceiver: DataWarningReceiver
,08-31 16:50:27.619  8794  8882 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.android.contacts
08-31 16:50:27.619  8794  8882 I PLM     : App title : Contacts & activity name : com.android.contacts.activities.PeopleActivity_com.android.contacts
,08-31 16:50:27.619  8794  8882 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.android.contacts
,08-31 16:50:27.629  8794  8882 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.android.contacts
08-31 16:50:27.629  8794  8882 I PLM     : App title : Phone & activity name : com.android.dialer.DialtactsActivity_com.android.contacts
,08-31 16:50:27.629  8794  8882 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.samsung.android.email.provider
,08-31 16:50:27.629  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-31 16:50:27.629  8794  8882 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:27.629  8794  8882 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.samsung.android.email.provider
08-31 16:50:27.629  8794  8882 I PLM     : App title : Email & activity name : com.samsung.android.email.ui.activity.MessageListXL_com.samsung.android.email.provider
,08-31 16:50:27.629  8794  8882 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Epic_Common/SecMms_Epic_Common.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.android.mms
,08-31 16:50:27.639  8794  8882 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:27.639  8794  8882 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Epic_Common/SecMms_Epic_Common.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.android.mms
,08-31 16:50:27.639  8794  8882 I PLM     : App alias title : sms & activity name : com.android.mms.ui.ConversationComposer_com.android.mms
08-31 16:50:27.639  8794  8882 I PLM     : App title : Messages & activity name : com.android.mms.ui.ConversationComposer_com.android.mms
,08-31 16:50:27.639  8794  8882 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.android.settings
,08-31 16:50:27.639  8794  8882 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:27.639  8794  8882 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.android.settings
,08-31 16:50:27.639  8794  8882 I PLM     : App title : Settings & activity name : com.android.settings.Settings_com.android.settings
08-31 16:50:27.639  8884  8884 E Zygote  : v2
08-31 16:50:27.639  8884  8884 I libpersona: KNOX_SDCARD checking this for 10060
08-31 16:50:27.639  8884  8884 I libpersona: KNOX_SDCARD not a persona
08-31 16:50:27.639  8794  8882 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.android.chrome
08-31 16:50:27.639  8884  8884 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,08-31 16:50:27.649  8884  8884 E Zygote  : accessInfo : 0
,08-31 16:50:27.649  8884  8884 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.provider.shootingmodeprovider 
,08-31 16:50:27.649  3381  4419 I ActivityManager: Start proc 8884:com.samsung.android.provider.shootingmodeprovider/u0a60 for broadcast-3 com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver
,08-31 16:50:27.649  8794  8882 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:27.649  8794  8882 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.android.chrome
08-31 16:50:27.649  8794  8882 I PLM     : App title : Chrome & activity name : com.google.android.apps.chrome.Main_com.android.chrome
08-31 16:50:27.649  3381  4419 I ActivityManager: Killing 8292:com.sec.android.app.popupuireceiver/1000 (adj 15): DHA:empty #33
,08-31 16:50:27.649  8794  8882 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.apps.docs
,08-31 16:50:27.649  8794  8882 D ResourcesManager: For user 0 new overlays fetched Null
08-31 16:50:27.649  8794  8882 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.apps.docs
08-31 16:50:27.659  8794  8882 I PLM     : App title : Drive & activity name : com.google.android.apps.docs.app.NewMainProxyActivity_com.google.android.apps.docs
08-31 16:50:27.659  8794  8882 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.gm
08-31 16:50:27.659  8794  8882 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:27.669  8794  8882 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.gm
,08-31 16:50:27.669  8794  8882 I PLM     : App title : Gmail & activity name : com.google.android.gm.ConversationListActivityGmail_com.google.android.gm
,08-31 16:50:27.669  8794  8882 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.talk
,08-31 16:50:27.669  8884  8884 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:50:27.669  8884  8884 D ActivityThread: Added TimaKeyStore provider
,08-31 16:50:27.679  3381  3975 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.popupuireceiver, Auto Run ON
,08-31 16:50:27.679  8794  8882 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:27.679  8794  8882 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.talk
,08-31 16:50:27.679  8794  8882 I PLM     : App title : Hangouts & activity name : com.google.android.talk.SigningInActivity_com.google.android.talk
08-31 16:50:27.679  8794  8882 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.music
,08-31 16:50:27.679  8842  8842 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 com.samsung.SMT.SamsungTTSService.g:-1 com.samsung.SMT.SamsungTTSService.onCreate:-1 android.app.ActivityThread.handleCreateService:3808 
,08-31 16:50:27.679  8794  8882 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:27.689  8794  8882 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.music
,08-31 16:50:27.689  8794  8882 I PLM     : App title : Play_Music & activity name : com.android.music.activitymanagement.TopLevelActivity_com.google.android.music
08-31 16:50:27.689  8794  8882 W ResourcesManager: getTopLevelResources: /system/app/Photos/Photos.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.apps.photos
,08-31 16:50:27.689  3381  4428 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f20a0cc u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3352295 8884:com.samsung.android.provider.shootingmodeprovider/u0a60}
,08-31 16:50:27.699  8884  8884 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,08-31 16:50:27.699  8842  8842 I SamsungTTS: Interface ver201503021
08-31 16:50:27.699  8884  8884 D RelationGraph: garbageCollect()
08-31 16:50:27.699  8842  8842 I SamsungTTS: Engine ver200812311
,08-31 16:50:27.699  8884  8884 W ResourcesManager: getTopLevelResources: /system/priv-app/ShootingModeProvider/ShootingModeProvider.apk / 1.0 running in com.samsung.android.provider.shootingmodeprovider rsrc of package com.samsung.android.provider.shootingmodeprovider
,08-31 16:50:27.699  8794  8794 I TextToSpeech: Connected to ComponentInfo{com.samsung.SMT/com.samsung.SMT.SamsungTTSService}
,08-31 16:50:27.699  3381  4558 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
08-31 16:50:27.699  8884  8884 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,08-31 16:50:27.699  8884  8884 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:27.709  8884  8884 I InjectionManager: Inside getClassLibPath caller 
,08-31 16:50:27.709  8842  8852 D SamsungTTS: onIsLanguageAvailable() : L=pol  C=POL  V=null  LANG_NOT_SUPPORTED
08-31 16:50:27.709  8794  8896 I TextToSpeech: Set up connection to ComponentInfo{com.samsung.SMT/com.samsung.SMT.SamsungTTSService}
,08-31 16:50:27.709  8794  8794 I SV_TTSPlayer:main:  : VSP::locale is: en_US
08-31 16:50:27.709  8884  8884 W System  : ClassLoader referenced unknown path: /system/priv-app/ShootingModeProvider/lib/arm64
,08-31 16:50:27.709  8842  8853 D SamsungTTS: onIsLanguageAvailable() : L=eng  C=USA  V=null  LANG_COUNTRY_AVAILABLE
,08-31 16:50:27.709  8842  8852 D SamsungTTS: onIsLanguageAvailable() : L=eng  C=USA  V=null  LANG_COUNTRY_AVAILABLE
,08-31 16:50:27.709  8842  8853 D SamsungTTS: onIsLanguageAvailable() : L=eng  C=USA  V=null  LANG_COUNTRY_AVAILABLE
,08-31 16:50:27.709  8842  8856 D SamsungTTS: onIsLanguageAvailable() : L=eng  C=USA  V=f00  LANG_COUNTRY_VAR_AVAILABLE
08-31 16:50:27.709  8842  8856 D SamsungTTS: onLoadLanguage() : [ LANG_COUNTRY_VAR_AVAILABLE ]  L=eng  C=USA  V=f00
,08-31 16:50:27.719  8884  8884 D InjectionManager: InjectionManager
08-31 16:50:27.719  8884  8884 D InjectionManager: fillFeatureStoreMap com.samsung.android.provider.shootingmodeprovider
,08-31 16:50:27.719  8884  8884 I InjectionManager: Constructor com.samsung.android.provider.shootingmodeprovider, Feature store :{}
08-31 16:50:27.719  8884  8884 I InjectionManager: featureStore :{}
,08-31 16:50:27.729  3381  4558 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f20a0cc u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9c2bc76 8665:com.samsung.android.sm.provider/1000}
,08-31 16:50:27.729  8794  8882 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:27.739  8794  8882 W ResourcesManager: getTopLevelResources: /system/app/Photos/Photos.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.apps.photos
08-31 16:50:27.739  8794  8882 I PLM     : App title : Photos & activity name : com.google.android.apps.photos.home.HomeActivity_com.google.android.apps.photos
08-31 16:50:27.739  8794  8882 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.sbrowser
,08-31 16:50:27.739  8794  8794 D Test    : TTS initialized! & queue size is : 0
,08-31 16:50:27.749  8794  8882 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:27.749  3381  4411 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f20a0cc u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e577405 8618:com.samsung.android.sm.devicesecurity/5012}
,08-31 16:50:27.769  8794  8882 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.sbrowser
,08-31 16:50:27.769  8794  8882 I PLM     : App title : Internet & activity name : com.sec.android.app.sbrowser.SBrowserMainActivity_com.sec.android.app.sbrowser
08-31 16:50:27.769  8794  8882 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M/SPlanner_M.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.android.calendar
,08-31 16:50:27.779  8794  8882 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:27.779  8794  8882 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M/SPlanner_M.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.android.calendar
08-31 16:50:27.779  8794  8882 I PLM     : App alias title : calendar & activity name : com.android.calendar.AllInOneActivity_com.android.calendar
08-31 16:50:27.779  8794  8882 I PLM     : App alias title : s_planner & activity name : com.android.calendar.AllInOneActivity_com.android.calendar
08-31 16:50:27.779  8794  8882 I PLM     : App alias title : schedule & activity name : com.android.calendar.AllInOneActivity_com.android.calendar
08-31 16:50:27.779  8794  8882 I PLM     : App alias title : diary & activity name : com.android.calendar.AllInOneActivity_com.android.calendar
08-31 16:50:27.779  8794  8882 I PLM     : App title : S_Planner & activity name : com.android.calendar.AllInOneActivity_com.android.calendar
,08-31 16:50:27.779  8794  8882 W ResourcesManager: getTopLevelResources: /system/app/Videos/Videos.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.videos
,08-31 16:50:27.779  8794  8882 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:27.779  8794  8882 W ResourcesManager: getTopLevelResources: /system/app/Videos/Videos.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.videos
08-31 16:50:27.779  8794  8882 I PLM     : App title : Play_Movies_&_TV & activity name : com.google.android.youtube.videos.EntryPoint_com.google.android.videos
,08-31 16:50:27.789  8794  8882 W ResourcesManager: getTopLevelResources: /system/app/YouTube/YouTube.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.youtube
,08-31 16:50:27.789  3381  4057 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f20a0cc u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fdd223a 8450:com.samsung.android.app.taskedge/u0a67}
,08-31 16:50:27.789  8794  8882 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:27.789  8450  8450 I TaskEdgeBroadcastReceiver: onReceive:android.intent.action.PACKAGE_ADDED
,08-31 16:50:27.789  8794  8882 W ResourcesManager: getTopLevelResources: /system/app/YouTube/YouTube.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.youtube
08-31 16:50:27.789  8794  8882 I PLM     : App title : YouTube & activity name : com.google.android.youtube.app.honeycomb.Shell$HomeActivity_com.google.android.youtube
,08-31 16:50:27.789  8794  8882 W ResourcesManager: getTopLevelResources: /system/priv-app/Excel_SamsungStub/Excel_SamsungStub.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.microsoft.office.excel
,08-31 16:50:27.789  8794  8882 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:27.799  8794  8882 W ResourcesManager: getTopLevelResources: /system/priv-app/Excel_SamsungStub/Excel_SamsungStub.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.microsoft.office.excel
08-31 16:50:27.799  8794  8882 I PLM     : App title : Excel & activity name : com.microsoft.office.apphost.LaunchActivity_com.microsoft.office.excel
,08-31 16:50:27.799  3381  3851 I ActivityManager: Killing 7834:com.samsung.enhanceservice/5004 (adj 15): DHA:empty #33
,08-31 16:50:27.799  8794  8882 W ResourcesManager: getTopLevelResources: /system/priv-app/GearManager/GearManager.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.samsung.android.app.watchmanager
,08-31 16:50:27.799  8794  8882 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:27.799  8794  8882 W ResourcesManager: getTopLevelResources: /system/priv-app/GearManager/GearManager.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.samsung.android.app.watchmanager
,08-31 16:50:27.799  8794  8882 I PLM     : App title : Samsung_Gear & activity name : com.samsung.android.app.watchmanager.setupwizard.SetupWizardWelcomeActivity_com.samsung.android.app.watchmanager
08-31 16:50:27.799  8794  8882 W ResourcesManager: getTopLevelResources: /system/priv-app/PowerPoint_SamsungStub/PowerPoint_SamsungStub.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.microsoft.office.powerpoint
,08-31 16:50:27.799  8794  8882 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:27.809  8794  8882 W ResourcesManager: getTopLevelResources: /system/priv-app/PowerPoint_SamsungStub/PowerPoint_SamsungStub.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.microsoft.office.powerpoint
,08-31 16:50:27.809  8794  8882 I PLM     : App title : PowerPoint & activity name : com.microsoft.office.apphost.LaunchActivity_com.microsoft.office.powerpoint
,08-31 16:50:27.809  8794  8882 W ResourcesManager: getTopLevelResources: /system/priv-app/SVoice_1.0/SVoice_1.0.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.samsung.voiceserviceplatform
08-31 16:50:27.809  8794  8882 W ResourcesManager: getTopLevelResources: /system/priv-app/SVoice_1.0/SVoice_1.0.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.samsung.voiceserviceplatform
,08-31 16:50:27.809  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-31 16:50:27.809  8794  8882 W ResourcesManager: getTopLevelResources: /system/priv-app/SecCalculator_M/SecCalculator_M.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.popupcalculator
,08-31 16:50:27.809  8794  8882 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:27.809  3381  3851 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f20a0cc u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1f5732e 4280:com.android.phone/1001}
,08-31 16:50:27.809  8794  8882 I PLM     : App title : Calculator & activity name : com.sec.android.app.popupcalculator.Calculator_com.sec.android.app.popupcalculator
08-31 16:50:27.809  8794  8882 W ResourcesManager: getTopLevelResources: /system/priv-app/SecCalculator_M/SecCalculator_M.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.popupcalculator
,08-31 16:50:27.809  8794  8882 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles/SecMyFiles.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.myfiles
,08-31 16:50:27.809  8794  8882 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:27.819  7809  7809 I ServiceManager: [#CMH#] Disconnected to Service  com.samsung.enhanceservice.EnhanceService
,08-31 16:50:27.819  8794  8882 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles/SecMyFiles.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.myfiles
,08-31 16:50:27.819  8794  8882 I PLM     : App title : My_Files & activity name : com.sec.android.app.myfiles.common.MainActivity_com.sec.android.app.myfiles
08-31 16:50:27.819  8794  8882 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.googlequicksearchbox
08-31 16:50:27.819  8794  8882 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:27.819  3381  3975 D ActivityManager: isAutoRunBlockedApp:: com.samsung.enhanceservice, Auto Run ON
08-31 16:50:27.819  3381  3975 W ActivityManager: Scheduling restart of crashed service com.samsung.enhanceservice/.EnhanceService in 1000ms
,08-31 16:50:27.819  8794  8882 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.googlequicksearchbox
08-31 16:50:27.819  8794  8882 I PLM     : App title : Voice_Search & activity name : com.google.android.googlequicksearchbox.VoiceSearchActivity_com.google.android.googlequicksearchbox
,08-31 16:50:27.829  8794  8882 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.googlequicksearchbox
08-31 16:50:27.829  8794  8882 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.googlequicksearchbox
08-31 16:50:27.829  8794  8882 I PLM     : App title : Google & activity name : com.google.android.googlequicksearchbox.SearchActivity_com.google.android.googlequicksearchbox
08-31 16:50:27.829  8794  8882 W ResourcesManager: getTopLevelResources: /system/priv-app/VoiceNote_4.0/VoiceNote_4.0.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.voicenote
08-31 16:50:27.829  8794  8882 D ResourcesManager: For user 0 new overlays fetched Null
08-31 16:50:27.829  8794  8882 W ResourcesManager: getTopLevelResources: /system/priv-app/VoiceNote_4.0/VoiceNote_4.0.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.voicenote
,08-31 16:50:27.829  8794  8882 I PLM     : App title : Voice_Recorder & activity name : com.sec.android.app.voicenote.main.VNMainActivity_com.sec.android.app.voicenote
08-31 16:50:27.829  8794  8882 W ResourcesManager: getTopLevelResources: /system/priv-app/Word_SamsungStub/Word_SamsungStub.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.microsoft.office.word
,08-31 16:50:27.829  8794  8882 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:27.829  8794  8882 W ResourcesManager: getTopLevelResources: /system/priv-app/Word_SamsungStub/Word_SamsungStub.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.microsoft.office.word
08-31 16:50:27.829  8794  8882 I PLM     : App title : Word & activity name : com.microsoft.office.apphost.LaunchActivity_com.microsoft.office.word
,08-31 16:50:27.829  8794  8882 W ResourcesManager: getTopLevelResources: /system/priv-app/player-production-release-3.3.3-newSDK_23/player-production-release-3.3.3-newSDK_23.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package pl.tvn.player
,08-31 16:50:27.829  8794  8882 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:27.839  8794  8882 W ResourcesManager: getTopLevelResources: /system/priv-app/player-production-release-3.3.3-newSDK_23/player-production-release-3.3.3-newSDK_23.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package pl.tvn.player
,08-31 16:50:27.839  8794  8882 I PLM     : App title : Player & activity name : pl.tvn.player.ui.SplashActivity_pl.tvn.player
08-31 16:50:27.839  8794  8882 W ResourcesManager: getTopLevelResources: /system/app/ClockPackage_M/ClockPackage_M.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.clockpackage
,08-31 16:50:27.839  8726  8877 W jxcore-log: Initializing JXcore engine
,08-31 16:50:27.839  8726  8877 W jxcore-log: JXcore engine is ready
08-31 16:50:27.839  8794  8882 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:27.839  8794  8882 W ResourcesManager: getTopLevelResources: /system/app/ClockPackage_M/ClockPackage_M.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.clockpackage
08-31 16:50:27.839  8794  8882 I PLM     : App alias title : alarm & activity name : com.sec.android.app.clockpackage.ClockPackage_com.sec.android.app.clockpackage
,08-31 16:50:27.839  8794  8882 I PLM     : App title : Clock & activity name : com.sec.android.app.clockpackage.ClockPackage_com.sec.android.app.clockpackage
08-31 16:50:27.839  8794  8882 W ResourcesManager: getTopLevelResources: /system/app/FBInstagram_stub/FBInstagram_stub.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.instagram.android
,08-31 16:50:27.839  8794  8882 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:27.839  8842  8856 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 android.content.ContextWrapper.sendBroadcast:410 com.samsung.SMT.b.i.a:-1 com.samsung.SMT.SamsungTTSService.b:-1 com.samsung.SMT.SamsungTTSService.onLoadLanguage:-1 
,08-31 16:50:27.839  8899  8899 E Zygote  : v2
08-31 16:50:27.839  8899  8899 I libpersona: KNOX_SDCARD checking this for 1000
08-31 16:50:27.839  8899  8899 I libpersona: KNOX_SDCARD not a persona
,08-31 16:50:27.839  8899  8899 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
08-31 16:50:27.839  8794  8882 W ResourcesManager: getTopLevelResources: /system/app/FBInstagram_stub/FBInstagram_stub.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.instagram.android
08-31 16:50:27.849  8794  8882 I PLM     : App title : Instagram & activity name : com.instagram.android.activity.MainTabActivity_com.instagram.android
08-31 16:50:27.849  8899  8899 E Zygote  : accessInfo : 0
,08-31 16:50:27.849  8794  8882 W ResourcesManager: getTopLevelResources: /system/app/Facebook_stub/Facebook_stub.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.facebook.katana
08-31 16:50:27.849  3381  3851 I ActivityManager: Start proc 8899:com.samsung.android.themecenter/1000 for broadcast-3 com.samsung.android.themecenter/com.samsung.android.thememanager.ThemeManagerReceiver
,08-31 16:50:27.849  8794  8882 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:27.849  8794  8882 W ResourcesManager: getTopLevelResources: /system/app/Facebook_stub/Facebook_stub.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.facebook.katana
,08-31 16:50:27.849  8794  8882 I PLM     : App title : Facebook & activity name : com.facebook.katana.LoginActivity_com.facebook.katana
08-31 16:50:27.849  8794  8882 W ResourcesManager: getTopLevelResources: /system/app/MSSkype_stub/MSSkype_stub.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.skype.raider
,08-31 16:50:27.849  8794  8882 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:27.849  8842  8856 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 android.content.ContextWrapper.sendBroadcast:410 android.speech.tts.TextToSpeechService$SynthThread.broadcastTtsQueueProcessingCompleted:460 android.speech.tts.TextToSpeechService$SynthThread.queueIdle:452 android.os.MessageQueue.next:392 
,08-31 16:50:27.849  8794  8882 W ResourcesManager: getTopLevelResources: /system/app/MSSkype_stub/MSSkype_stub.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.skype.raider
,08-31 16:50:27.849  8794  8882 I PLM     : App title : Skype & activity name : com.skype.raider.Main_com.skype.raider
08-31 16:50:27.849  8794  8882 W ResourcesManager: getTopLevelResources: /system/app/Maps/Maps.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.apps.maps
,08-31 16:50:27.859  8794  8882 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:27.859  8794  8882 W ResourcesManager: getTopLevelResources: /system/app/Maps/Maps.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.apps.maps
,08-31 16:50:27.859  8794  8882 I PLM     : App title : Maps & activity name : com.google.android.maps.MapsActivity_com.google.android.apps.maps
08-31 16:50:27.859  8794  8882 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.microsoft.skydrive
08-31 16:50:27.859  8899  8899 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:50:27.859  8899  8899 D ActivityThread: Added TimaKeyStore provider
,08-31 16:50:27.859  8794  8882 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:27.859  8794  8882 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.microsoft.skydrive
,08-31 16:50:27.859  8794  8882 I PLM     : App title : OneDrive & activity name : com.microsoft.skydrive.MainActivity_com.microsoft.skydrive
08-31 16:50:27.859  4952  4952 E audit   : type=1400 msg=audit(1472655027.859:256): avc:  denied  { ioctl } for  pid=8877 comm="Thread-116" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3108 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-31 16:50:27.859  8794  8882 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.microsoft.office.onenote
08-31 16:50:27.859  4952  4952 E audit   :  SEPF_SECMOBILE_6.0.1_0013
08-31 16:50:27.859  4952  4952 E audit   : type=1300 msg=audit(1472655027.859:256): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=8 a1=5451 a2=3 a3=d86053c8 items=0 ppid=3177 pid=8877 auid=4294967295 uid=10177 gid=10177 euid=10177 suid=10177 fsuid=10177 egid=10177 sgid=10177 fsgid=10177 tty=(none) ses=4294967295 comm="Thread-116" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-31 16:50:27.859  4952  4952 E audit   : type=1327 msg=audit(1472655027.859:256): proctitle="com.test.thalitest"
08-31 16:50:27.859  4952  4952 E audit   : type=1320 msg=audit(1472655027.859:256): 
08-31 16:50:27.859  4952  4952 E audit   : type=1400 msg=audit(1472655027.859:257): avc:  denied  { ioctl } for  pid=8877 comm="Thread-116" path="socket:[10943]" dev="sockfs" ino=10943 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-31 16:50:27.859  4952  4952 E audit   :  SEPF_SECMOBILE_6.0.1_0013
08-31 16:50:27.859  4952  4952 E audit   : type=1300 msg=audit(1472655027.859:257): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=3b a1=5451 a2=3 a3=d86053c8 items=0 ppid=3177 pid=8877 auid=4294967295 uid=10177 gid=10177 euid=10177 suid=10177 fsuid=10177 egid=10177 sgid=10177 fsgid=10177 tty=(none) ses=4294967295 comm="Thread-116" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-31 16:50:27.859  4952  4952 E audit   : type=1327 msg=audit(1472655027.859:257): proctitle="com.test.thalitest"
,08-31 16:50:27.859  4952  4952 E audit   : type=1320 msg=audit(1472655027.859:257): 
08-31 16:50:27.869  8794  8882 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:27.869  8794  8882 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.microsoft.office.onenote
08-31 16:50:27.869  8794  8882 I PLM     : App title : OneNote & activity name : com.microsoft.office.onenote.ui.ONMSplashActivity_com.microsoft.office.onenote
,08-31 16:50:27.869  8794  8882 W ResourcesManager: getTopLevelResources: /system/app/SecMemo3/SecMemo3.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.samsung.android.app.memo
,08-31 16:50:27.869  8794  8882 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:27.869  8726  8877 W jxcore-log: Starting JXcore engine
08-31 16:50:27.869  3381  4057 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f20a0cc u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{69a6277 8899:com.samsung.android.themecenter/1000}
,08-31 16:50:27.869  8794  8882 W ResourcesManager: getTopLevelResources: /system/app/SecMemo3/SecMemo3.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.samsung.android.app.memo
,08-31 16:50:27.869  8794  8882 I PLM     : App title : Memo & activity name : com.samsung.android.app.memo.Main_com.samsung.android.app.memo
,08-31 16:50:27.869  8794  8882 W ResourcesManager: getTopLevelResources: /system/app/WhatsAppDownloader/WhatsAppDownloader.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.whatsapp
,08-31 16:50:27.869  8794  8882 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:27.879  8899  8899 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,08-31 16:50:27.879  8794  8882 I PLM     : App title : WhatsApp & activity name : com.whatsapp.Main_com.whatsapp
08-31 16:50:27.879  8899  8899 D RelationGraph: garbageCollect()
08-31 16:50:27.879  8794  8882 W ResourcesManager: getTopLevelResources: /data/app/com.sec.android.app.samsungapps-1/base.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.samsungapps
,08-31 16:50:27.879  8899  8899 W ResourcesManager: getTopLevelResources: /system/priv-app/ThemeCenter/ThemeCenter.apk / 1.0 running in com.samsung.android.themecenter rsrc of package com.samsung.android.themecenter
,08-31 16:50:27.879  3381  4915 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
08-31 16:50:27.879  8899  8899 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,08-31 16:50:27.879  8794  8882 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:27.879  8899  8899 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:27.879  8794  8882 W ResourcesManager: getTopLevelResources: /data/app/com.sec.android.app.samsungapps-1/base.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.samsungapps
08-31 16:50:27.879  8794  8882 I PLM     : App title : Galaxy_Apps & activity name : com.sec.android.app.samsungapps.SamsungAppsMainActivity_com.sec.android.app.samsungapps
08-31 16:50:27.879  8794  8882 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.test.thalitest
,08-31 16:50:27.879  8899  8899 I InjectionManager: Inside getClassLibPath caller 
,08-31 16:50:27.879  8794  8882 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:27.879  8794  8882 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.test.thalitest
08-31 16:50:27.879  8794  8882 I PLM     : App title : ThaliTest & activity name : com.test.thalitest.MainActivity_com.test.thalitest
08-31 16:50:27.879  8899  8899 W System  : ClassLoader referenced unknown path: /system/priv-app/ThemeCenter/lib/arm64
,08-31 16:50:27.889  8899  8899 D InjectionManager: InjectionManager
,08-31 16:50:27.889  8899  8899 D InjectionManager: fillFeatureStoreMap com.samsung.android.themecenter
08-31 16:50:27.889  8899  8899 I InjectionManager: Constructor com.samsung.android.themecenter, Feature store :{}
08-31 16:50:27.889  8899  8899 I InjectionManager: featureStore :{}
,08-31 16:50:27.889  8899  8899 I ThemeManagerReceiver: ThemeManagerReceiver onReceive android.intent.action.PACKAGE_ADDED
,08-31 16:50:27.889  3381  4915 I ActivityManager: Killing 7846:com.samsung.dcmservice/5004 (adj 15): DHA:empty #33
,08-31 16:50:27.899  3381  4915 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f20a0cc u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5ebf003 4434:com.google.android.googlequicksearchbox:search/u0a72}
,08-31 16:50:27.909  7809  7809 I ServiceManager: [#CMH#] Disconnected to Service  com.samsung.dcmservice.DCMService
,08-31 16:50:27.909  8726  8877 W jxcore-log: Platform android
08-31 16:50:27.909  8726  8877 W jxcore-log: 
08-31 16:50:27.909  8726  8877 W jxcore-log: Process ARCH arm
08-31 16:50:27.909  8726  8877 W jxcore-log: 
,08-31 16:50:27.919  3381  4419 D ActivityManager: isAutoRunBlockedApp:: com.samsung.dcmservice, Auto Run ON
08-31 16:50:27.919  3381  4419 W ActivityManager: Scheduling restart of crashed service com.samsung.dcmservice/.DCMService in 10907ms
,08-31 16:50:27.929  3381  4181 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f20a0cc u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5ebf003 4434:com.google.android.googlequicksearchbox:search/u0a72}
,08-31 16:50:27.939  8794  8882 D ContactInfo: Matched with previous entries!
,08-31 16:50:27.949  8912  8912 E Zygote  : v2
08-31 16:50:27.949  8912  8912 I libpersona: KNOX_SDCARD checking this for 5009
08-31 16:50:27.949  8912  8912 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
08-31 16:50:27.949  8912  8912 I libpersona: KNOX_SDCARD not a persona
,08-31 16:50:27.949  8912  8912 E Zygote  : accessInfo : 0
08-31 16:50:27.949  8912  8912 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.scloud 
,08-31 16:50:27.949  3381  4181 I ActivityManager: Start proc 8912:com.samsung.android.scloud/5009 for broadcast-3 com.samsung.android.scloud/.receivers.SCloudReceiver
,08-31 16:50:27.959  8912  8912 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:50:27.959  8912  8912 D ActivityThread: Added TimaKeyStore provider
,08-31 16:50:27.969  4434  8911 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,08-31 16:50:27.979  3381  4179 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f20a0cc u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5b80f4d 8912:com.samsung.android.scloud/5009}
,08-31 16:50:27.989  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-31 16:50:27.989  8726  8877 I jxcore-log: JXcore Cordova bridge is ready!
08-31 16:50:27.989  8726  8877 I jxcore-log: 
08-31 16:50:27.989  8726  8877 W jxcore-log: JXcore engine is started
,08-31 16:50:27.989  8794  8882 D PLMGenManager: Any updates for FSG and DICT? : Yes
08-31 16:50:27.989  8794  8882 D PLMGenManager: TimeTaken for Contact & App sync 428ms
,08-31 16:50:27.989  8912  8912 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
08-31 16:50:27.989  8912  8912 D RelationGraph: garbageCollect()
08-31 16:50:27.989  8794  8882 D etickcount:BuildCmd: Dictionary name : /data/user/0/com.sec.svoice.lang.en_US/files/en_US/dict/hero.dict
,08-31 16:50:27.989  8912  8912 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.samsung.android.scloud
,08-31 16:50:27.989  8726  8855 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-31 16:50:27.989  3381  3851 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
08-31 16:50:27.999  8912  8912 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,08-31 16:50:27.999  8912  8912 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:27.999  8726  8726 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-31 16:50:27.999  8912  8912 I InjectionManager: Inside getClassLibPath caller 
,08-31 16:50:27.999  8794  8882 I FSGFileGenerator:PocketSphinx: Model dir : /data/user/0/com.sec.svoice.lang.en_US/files/en_US
08-31 16:50:27.999  8912  8912 W System  : ClassLoader referenced unknown path: /system/priv-app/SamsungCloud/lib/arm64
,08-31 16:50:27.999  8794  8882 I FSGFileGenerator:PocketSphinx: FSG : start
08-31 16:50:27.999  8794  8882 D FSGFileGenerator:PocketSphinx: Inside initFileWriter
,08-31 16:50:27.999  8794  8882 I FSGFileGenerator:PocketSphinx: templateFsgFileToRead = { /data/user/0/com.sec.svoice.lang.en_US/files/en_US/lm/hero.detmin.fsg.org, fsgFileToCreate = /data/user/0/com.sec.svoice.lang.en_US/files/en_US/lm/hero.detmin.fsg }
,08-31 16:50:27.999  8794  8882 D FSGFileGenerator:PocketSphinx: FileWriter/FileReader created
,08-31 16:50:28.019  8912  8912 I [SC]RequestProvider: onCreate() ~!! : com.samsung.android.scloud.framework.SamsungCloudApp@e972b70
,08-31 16:50:28.019  8912  8912 I [SC]QuotaInterfaceManager: sync start
,08-31 16:50:28.019  8794  8882 D FSGFileGenerator:PocketSphinx: FileWriter is closed sucessfull
08-31 16:50:28.019  8794  8882 D FSGFileGenerator:PocketSphinx: FileReader is closed sucessfull
08-31 16:50:28.019  8794  8882 D FSGFileGenerator:PocketSphinx: Inside initFileWriter
08-31 16:50:28.019  8794  8882 I FSGFileGenerator:PocketSphinx: templateFsgFileToRead = { /data/user/0/com.sec.svoice.lang.en_US/files/en_US/lm/hero.detmin.wo.wakeup.fsg.org, fsgFileToCreate = /data/user/0/com.sec.svoice.lang.en_US/files/en_US/lm/hero.detmin.wo.wakeup.fsg }
,08-31 16:50:28.019  8794  8882 D FSGFileGenerator:PocketSphinx: FileWriter/FileReader created
,08-31 16:50:28.029  8912  8912 I [SC]RequestProvider: uiregister - started.
08-31 16:50:28.029  8912  8912 I [SC]RequestProvider: quotaregister - started.
,08-31 16:50:28.029  8912  8912 I [SC]ExternalOEMControlProvider: onCreate
,08-31 16:50:28.029  4434  8911 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package com.test.thalitest
,08-31 16:50:28.029  4434  8911 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:28.029  4434  8911 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package com.test.thalitest
,08-31 16:50:28.039  8912  8912 V SamsungCloudLogs:  set Log level [4->4]act[false]
,08-31 16:50:28.039  8794  8882 D FSGFileGenerator:PocketSphinx: FileWriter is closed sucessfull
08-31 16:50:28.039  8794  8882 D FSGFileGenerator:PocketSphinx: FileReader is closed sucessfull
08-31 16:50:28.039  8794  8882 D FSGFileGenerator:PocketSphinx: FSG : COMPLETED in 38 ms.
08-31 16:50:28.039  8794  8882 I FSGFileGenerator:PocketSphinx: FSG : start
08-31 16:50:28.039  8794  8882 D FSGFileGenerator:PocketSphinx: Inside initFileWriter
08-31 16:50:28.039  8794  8882 I FSGFileGenerator:PocketSphinx: templateFsgFileToRead = { /data/user/0/com.sec.svoice.lang.en_US/files/en_US/lm/contact.fsg.org, fsgFileToCreate = /data/user/0/com.sec.svoice.lang.en_US/files/en_US/lm/contact.fsg }
08-31 16:50:28.039  8912  8912 I [SC]CommonUtil: isSemAvailable:0
08-31 16:50:28.039  8912  8912 I [SC]SamsungCloudApp: AppVer[2.1.11][L:4]Sem[false]V2DEV_R slog[false]com.samsung.android.scloud
,08-31 16:50:28.039  8912  8912 I [SC]SamsungCloudApp: controller allowed
,08-31 16:50:28.039  8912  8912 I [SC]MetaManager: MetaManager--[elapse:       1] Version Info[2.0.00]
,08-31 16:50:28.039  8794  8882 D FSGFileGenerator:PocketSphinx: FileWriter/FileReader created
,08-31 16:50:28.039  8912  8912 I [SC]FeatureManager: FeatureManager 
08-31 16:50:28.039  8912  8912 I [SC]FeatureManager: [SEC_FLOATING_FEATURE_SAMSUNGCLOUD_CONFIG_CLOUD_USAGE_MENU_TREE]str 
08-31 16:50:28.039  8912  8912 I [SC]FeatureManager: [SEC_FLOATING_FEATURE_SAMSUNGCLOUD_ENABLE_SETTING_MENU]bln true
,08-31 16:50:28.039  8912  8912 I [SC]ModelManager: ModelManager++
08-31 16:50:28.039  8912  8912 I [SC]CommonUtil: getClockPkgName pkg[com.sec.android.app.clockpackage] csc[]
08-31 16:50:28.039  8912  8912 I [SC]CommonUtil: getContactsPkgName pkg[com.android.contacts] csc[]
08-31 16:50:28.039  8912  8912 I [SC]CommonUtil: getMessagePkgName com.android.mms
,08-31 16:50:28.039  8912  8912 I [SC]CommonUtil: getEmailProviderPkgName com.samsung.android.email.provider
08-31 16:50:28.039  8912  8912 I [SC]CommonUtil: getCalendarPkgName com.android.calendar
08-31 16:50:28.039  8912  8912 I [SC]CommonUtil: getMessagePkgName com.android.mms
,08-31 16:50:28.039  8912  8912 I [SC]CommonUtil: getContactsPkgName pkg[com.android.contacts] csc[]
08-31 16:50:28.039  8912  8912 I [SC]CommonUtil: getCallPkgName com.android.incallui
08-31 16:50:28.039  8912  8912 I [SC]CommonUtil: getEmailProviderPkgName com.samsung.android.email.provider
08-31 16:50:28.039  8794  8882 D FSGFileGenerator:PocketSphinx: FileWriter is closed sucessfull
08-31 16:50:28.039  8794  8882 D FSGFileGenerator:PocketSphinx: FileReader is closed sucessfull
08-31 16:50:28.039  8794  8882 D FSGFileGenerator:PocketSphinx: Inside initFileWriter
08-31 16:50:28.039  8794  8882 I FSGFileGenerator:PocketSphinx: templateFsgFileToRead = { /data/user/0/com.sec.svoice.lang.en_US/files/en_US/lm/contact.fav.fsg.org, fsgFileToCreate = /data/user/0/com.sec.svoice.lang.en_US/files/en_US/lm/contact.fav.fsg }
08-31 16:50:28.049  8794  8882 D FSGFileGenerator:PocketSphinx: FileWriter/FileReader created
,08-31 16:50:28.049  8794  8882 D FSGFileGenerator:PocketSphinx: FileWriter is closed sucessfull
08-31 16:50:28.049  8794  8882 D FSGFileGenerator:PocketSphinx: FileReader is closed sucessfull
08-31 16:50:28.049  8794  8882 D FSGFileGenerator:PocketSphinx:OWC: FSG : COMPLETED in 7 ms.
08-31 16:50:28.049  8794  8882 I DictionaryGenerator:PocketSphinx: Model dir : /data/user/0/com.sec.svoice.lang.en_US/files/en_US
08-31 16:50:28.049  8794  8882 I DictionaryGenerator:PocketSphinx: Locale : en_US
08-31 16:50:28.049  8912  8912 I [SC]Logs: [BaseModel]CALLLOGS                  logs                                               content://logs/historys
08-31 16:50:28.049  8794  8882 I DictionaryGenerator:PocketSphinx: DFG : Start
08-31 16:50:28.049  8794  8882 D DictionaryGenerator:PocketSphinx: Inside initFileWriter : Dict file name : /data/user/0/com.sec.svoice.lang.en_US/files/en_US/dict/hero.dict
,08-31 16:50:28.049  8794  8882 I DictionaryGenerator:PocketSphinx: mDictionaryFile = { /data/user/0/com.sec.svoice.lang.en_US/files/en_US/dict/hero.dict }
08-31 16:50:28.049  8794  8882 D DictionaryGenerator:PocketSphinx: FileWriter created
08-31 16:50:28.049  8794  8882 D DictionaryGenerator:PocketSphinx: copying frm : /data/user/0/com.sec.svoice.lang.en_US/files/en_US/dict/hero.dict
,08-31 16:50:28.049  8912  8912 I [SC]CommonUtil: isVoiceCallSupport : true
08-31 16:50:28.049  8912  8912 I [SC]ModelManager: addModel[+] CALLLOGS                  isEnable[true ] --:content://logs/historys::com.android.contacts
08-31 16:50:28.049  8912  8912 I [SC]VIPList: [BaseModel]VIPLIST                   com.samsung.android.email.provider                 content://com.samsung.android.email.provider/viplist
,08-31 16:50:28.049  8912  8912 I [SC]ModelManager: addModel[+] VIPLIST                   isEnable[true ] --:content://com.samsung.android.email.provider/viplist::com.samsung.android.email.provider
,08-31 16:50:28.049  8912  8912 I [SC]BlackList: [BaseModel]BLACKLIST                 com.samsung.android.email.provider                 content://com.samsung.android.email.provider/blacklist
,08-31 16:50:28.049  8912  8912 I [SC]ModelManager: addModel[+] BLACKLIST                 isEnable[true ] --:content://com.samsung.android.email.provider/blacklist::com.samsung.android.email.provider
08-31 16:50:28.049  8912  8912 I [SC]Spam: [BaseModel]SPAM                      mms-sms                                            content://mms-sms/spam-filter
08-31 16:50:28.049  8794  8882 D DictionaryGenerator:PocketSphinx: Wakeup word is : null
08-31 16:50:28.049  8794  8882 D DictionaryGenerator:PocketSphinx: wakeup string added to dict : slot_wakeup_start__WAKEUP__slot_wakeup_end	S L AA T W EY K AH P S T AA R T W EY K AH P S L AA T W EY K AH P EH N D
,08-31 16:50:28.049  8912  8912 I [SC]ModelManager: addModel[+] SPAM                      isEnable[true ] --:content://mms-sms/spam-filter::com.android.mms
,08-31 16:50:28.049  8912  8912 I [SC]CallReject: [BaseModel]CALLREJECT                com.android.phone.callsettings                     content://com.android.phone.callsettings/reject_num
08-31 16:50:28.049  8794  8882 I G2P     : PocketSphinxEngine:Trying to load : /data/user/0/com.sec.svoice.lang.en_US/files/en_US/libs/libG2PenUS.so
,08-31 16:50:28.059  8794  8882 I G2P     : PocketSphinxEngine:loading /data/user/0/com.sec.svoice.lang.en_US/files/en_US/libs/libG2PenUS.so done
08-31 16:50:28.059  8794  8882 V G2P-SRIB: Build date: Apr 28 2016, 15:00:24
08-31 16:50:28.059  8794  8882 V G2P-SRIB: enUS G2P libs
08-31 16:50:28.059  8794  8882 V G2P-SRIB: stringCount: 46
08-31 16:50:28.059  8794  8882 V G2P-SRIB: Config: lang: en-US
08-31 16:50:28.059  8794  8882 V G2P-SRIB: variant: mp
08-31 16:50:28.059  8794  8882 V G2P-SRIB: prefix: slot_application_names_start__
08-31 16:50:28.059  8794  8882 V G2P-SRIB: suffix: __slot_application_names_end
08-31 16:50:28.059  8794  8882 V G2P-SRIB: Options dump_pron: W W K K K K K K K K K K K K K W W,
08-31 16:50:28.059  8794  8882 V G2P-SRIB: After conversion: Internet, Internet, 8, 8
,08-31 16:50:28.059  8794  8882 V G2P-SRIB: After g2p: prons 1, max_pron_len 17
08-31 16:50:28.059  8794  8882 V G2P-SRIB: Output pron: ih n t er n eh t, i in loop: 0
08-31 16:50:28.059  8794  8882 V G2P-SRIB: After conversion: Phone, Phone, 5, 5
,08-31 16:50:28.059  8794  8882 V G2P-SRIB: After g2p: prons 1, max_pron_len 7
,08-31 16:50:28.059  8794  8882 V G2P-SRIB: Output pron: f ow n, i in loop: 0
08-31 16:50:28.059  8794  8882 V G2P-SRIB: After conversion: Voice_Recorder, Voice_Recorder, 14, 14
08-31 16:50:28.059  8912  8912 I [SC]CommonUtil: isVoiceCallSupport : true
08-31 16:50:28.059  8912  8912 I [SC]ModelManager: addModel[+] CALLREJECT                isEnable[true ] --:content://com.android.phone.callsettings/reject_num::com.android.incallui
,08-31 16:50:28.059  8794  8882 V G2P-SRIB: After g2p: prons 1, max_pron_len 24
08-31 16:50:28.059  8794  8882 V G2P-SRIB: Output pron: v oy s r ih k ao r d er, i in loop: 0
08-31 16:50:28.059  8794  8882 V G2P-SRIB: After conversion: Player, Player, 6, 6
08-31 16:50:28.059  8912  8912 I [SC]ConnectionsSetting: [BaseModel]CONNECTIONS               com.android.settings.accessibility.sharedaccessibility.backup content://com.android.settings.accessibility.sharedaccessibility.backup
,08-31 16:50:28.059  8794  8882 V G2P-SRIB: After g2p: prons 1, max_pron_len 10
08-31 16:50:28.059  8794  8882 V G2P-SRIB: Output pron: p l ey er, i in loop: 0
08-31 16:50:28.059  8794  8882 V G2P-SRIB: After conversion: Word, Word, 4, 4
08-31 16:50:28.069  8794  8882 V G2P-SRIB: After g2p: prons 1, max_pron_len 7
08-31 16:50:28.069  8794  8882 V G2P-SRIB: Output pron: w er d, i in loop: 0
08-31 16:50:28.069  8912  8912 I [SC]ModelManager: addModel[+] CONNECTIONS               isEnable[false] --:content://com.android.settings.accessibility.sharedaccessibility.backup::com.android.settings
08-31 16:50:28.069  8794  8882 V G2P-SRIB: After conversion: Samsung_Gear, Samsung_Gear, 12, 12
08-31 16:50:28.069  8794  8882 V G2P-SRIB: After g2p: prons 1, max_pron_len 22
08-31 16:50:28.069  8794  8882 V G2P-SRIB: Output pron: s ae m s ah ng g ih r, i in loop: 0
08-31 16:50:28.069  8794  8882 V G2P-SRIB: After conversion: schedule, schedule, 8, 8
08-31 16:50:28.069  8912  8912 I [SC]RingtoneSetting: [BaseModel]RINGTONESETTING           null                                               null
08-31 16:50:28.069  8794  8882 V G2P-SRIB: After g2p: prons 1, max_pron_len 15
08-31 16:50:28.069  8794  8882 V G2P-SRIB: Output pron: s k eh jh uh l, i in loop: 0
08-31 16:50:28.069  8794  8882 V G2P-SRIB: After conversion: Play_Music, Play_Music, 10, 10
08-31 16:50:28.069  8912  8912 I [SC]ModelManager: addModel[+] RINGTONESETTING           isEnable[true ] --:null::com.sec.android.app.ringtoneBR
08-31 16:50:28.069  8794  8882 V G2P-SRIB: After g2p: prons 1, max_pron_len 21
08-31 16:50:28.069  8794  8882 V G2P-SRIB: Output pron: p l ey m y uw z ih k, i in loop: 0
08-31 16:50:28.069  8794  8882 V G2P-SRIB: After conversion: S_Planner, S_Planner, 9, 9
08-31 16:50:28.069  8794  8882 V G2P-SRIB: After g2p: prons 1, max_pron_len 17
08-31 16:50:28.069  8794  8882 V G2P-SRIB: Output pron: eh s p l ae n er, i in loop: 0
08-31 16:50:28.069  8794  8882 V G2P-SRIB: After conversion: Memo, Memo, 4, 4
08-31 16:50:28.069  8794  8882 V G2P-SRIB: After g2p: prons 1, max_pron_len 10
,08-31 16:50:28.069  8794  8882 V G2P-SRIB: Output pron: m eh m ow, i in loop: 0
08-31 16:50:28.069  8794  8882 V G2P-SRIB: After conversion: Drive, Drive, 5, 5
08-31 16:50:28.069  8794  8882 V G2P-SRIB: After g2p: prons 1, max_pron_len 9
08-31 16:50:28.069  8794  8882 V G2P-SRIB: Output pron: d r ay v, i in loop: 0
08-31 16:50:28.069  8794  8882 V G2P-SRIB: After conversion: Galaxy_Apps, Galaxy_Apps, 11, 11
08-31 16:50:28.069  8912  8912 I [SC]Music: [BaseModel]MUSIC                     null                                               null
,08-31 16:50:28.069  8794  8882 V G2P-SRIB: After g2p: prons 1, max_pron_len 24
08-31 16:50:28.069  8794  8882 V G2P-SRIB: Output pron: g ae l ah k s iy ae p s, i in loop: 0
08-31 16:50:28.069  8794  8882 V G2P-SRIB: After conversion: Calculator, Calculator, 10, 10
08-31 16:50:28.069  8912  8912 I [SC]ModelManager: addModel[+] MUSIC                     isEnable[true ] --:null::com.samsung.android.scloud
08-31 16:50:28.069  8794  8882 V G2P-SRIB: After g2p: prons 1, max_pron_len 24
08-31 16:50:28.069  8794  8882 V G2P-SRIB: Output pron: k ae l k y ah l ey t er, i in loop: 0
08-31 16:50:28.069  8794  8882 V G2P-SRIB: After conversion: Chrome, Chrome, 6, 6
,08-31 16:50:28.069  8912  8912 I [SC]Document: [BaseModel]DOCUMENT                  null                                               null
08-31 16:50:28.069  8794  8882 V G2P-SRIB: After g2p: prons 1, max_pron_len 9
08-31 16:50:28.069  8794  8882 V G2P-SRIB: Output pron: k r ow m, i in loop: 0
08-31 16:50:28.069  8794  8882 V G2P-SRIB: After conversion: OneDrive, OneDrive, 8, 8
08-31 16:50:28.069  8912  8912 I [SC]ModelManager: addModel[+] DOCUMENT                  isEnable[true ] --:null::com.samsung.android.scloud
08-31 16:50:28.069  8794  8882 V G2P-SRIB: After g2p: prons 1, max_pron_len 19
08-31 16:50:28.069  8794  8882 V G2P-SRIB: Output pron: w ah n eh d r ay v, i in loop: 0
08-31 16:50:28.069  8794  8882 V G2P-SRIB: After conversion: Instagram, Instagram, 9, 9
,08-31 16:50:28.069  8794  8882 V G2P-SRIB: After g2p: prons 1, max_pron_len 21
08-31 16:50:28.069  8794  8882 V G2P-SRIB: Output pron: ih n s t ax g r ae m, i in loop: 0
08-31 16:50:28.069  8794  8882 V G2P-SRIB: After conversion: Contacts, Contacts, 8, 8
08-31 16:50:28.069  8794  8882 V G2P-SRIB: After g2p: prons 1, max_pron_len 18
08-31 16:50:28.069  8794  8882 V G2P-SRIB: Output pron: k aa n t ae k t s, i in loop: 0
08-31 16:50:28.069  8794  8882 V G2P-SRIB: After conversion: ThaliTest, ThaliTest, 9, 9
08-31 16:50:28.069  8794  8882 V G2P-SRIB: After g2p: prons 1, max_pron_len 20
08-31 16:50:28.069  8794  8882 V G2P-SRIB: Output pron: th ae l ay t ax s t, i in loop: 0
08-31 16:50:28.069  8794  8882 V G2P-SRIB: After conversion: WhatsApp, WhatsApp, 8, 8
08-31 16:50:28.069  8794  8882 V G2P-SRIB: After g2p: prons 1, max_pron_len 14
08-31 16:50:28.069  8794  8882 V G2P-SRIB: Output pron: w aa t s ae p, i in loop: 0
08-31 16:50:28.069  8794  8882 V G2P-SRIB: After conversion: Messages, Messages, 8, 8
08-31 16:50:28.069  8912  8912 I [SC]Application: [BaseModel]APP                       null                                               null
08-31 16:50:28.069  8794  8882 V G2P-SRIB: After g2p: prons 1, max_pron_len 18
08-31 16:50:28.069  8794  8882 V G2P-SRIB: Output pron: m eh s ax jh ax z, i in loop: 0
08-31 16:50:28.069  8794  8882 V G2P-SRIB: After conversion: Email, Email, 5, 5
08-31 16:50:28.069  8794  8882 V G2P-SRIB: After g2p: prons 1, max_pron_len 10
,08-31 16:50:28.069  8794  8882 V G2P-SRIB: Output pron: iy m ey l, i in loop: 0
08-31 16:50:28.069  8912  8912 I [SC]ModelManager: addModel[+] APP                       isEnable[true ] --:null::com.samsung.android.scloud
08-31 16:50:28.069  8794  8882 V G2P-SRIB: After conversion: Hangouts, Hangouts, 8, 8
08-31 16:50:28.069  8794  8882 V G2P-SRIB: After g2p: prons 1, max_pron_len 16
08-31 16:50:28.069  8794  8882 V G2P-SRIB: Output pron: hh ae ng aw t s, i in loop: 0
08-31 16:50:28.069  8794  8882 V G2P-SRIB: After conversion: OneNote, OneNote, 7, 7
08-31 16:50:28.069  8912  8912 I [SC]Home: [BaseModel]HomescreenBackup          com.sec.android.app.launcher                       content://com.sec.android.app.launcher
08-31 16:50:28.069  8794  8882 V G2P-SRIB: After g2p: prons 1, max_pron_len 17
,08-31 16:50:28.069  8794  8882 V G2P-SRIB: Output pron: w ah n ih n ow t, i in loop: 0
08-31 16:50:28.069  8794  8882 V G2P-SRIB: After conversion: calendar, calendar, 8, 8
08-31 16:50:28.079  8794  8882 V G2P-SRIB: After g2p: prons 1, max_pron_len 17
08-31 16:50:28.079  8794  8882 V G2P-SRIB: Output pron: k ae l ax n d er, i in loop: 0
08-31 16:50:28.079  8794  8882 V G2P-SRIB: After conversion: Play_Store, Play_Store, 10, 10
08-31 16:50:28.079  8912  8912 I [SC]ModelManager: addModel[+] HomescreenBackup          isEnable[true ] --:content://com.sec.android.app.launcher::com.sec.android.app.launcher
08-31 16:50:28.079  8794  8882 V G2P-SRIB: After g2p: prons 1, max_pron_len 16
08-31 16:50:28.079  8794  8882 V G2P-SRIB: Output pron: p l ey s t ao r, i in loop: 0
08-31 16:50:28.079  8794  8882 V G2P-SRIB: After conversion: Photos, Photos, 6, 6
08-31 16:50:28.079  8794  8882 V G2P-SRIB: After g2p: prons 1, max_pron_len 12
08-31 16:50:28.079  8794  8882 V G2P-SRIB: Output pron: f ow t ow z, i in loop: 0
08-31 16:50:28.079  8794  8882 V G2P-SRIB: After conversion: Excel, Excel, 5, 5
08-31 16:50:28.079  8794  8882 V G2P-SRIB: After g2p: prons 1, max_pron_len 12
08-31 16:50:28.079  8794  8882 V G2P-SRIB: Output pron: ih k s eh l, i in loop: 0
08-31 16:50:28.079  8794  8882 V G2P-SRIB: After conversion: Gallery, Gallery, 7, 7
08-31 16:50:28.079  8794  8882 V G2P-SRIB: After g2p: prons 1, max_pron_len 13
08-31 16:50:28.079  8794  8882 V G2P-SRIB: Output pron: g ae l er iy, i in loop: 0
08-31 16:50:28.079  8794  8882 V G2P-SRIB: After conversion: sms, sms, 3, 3
08-31 16:50:28.079  8794  8882 V G2P-SRIB: After g2p: prons 1, max_pron_len 15
08-31 16:50:28.079  8794  8882 V G2P-SRIB: Output pron: eh s eh m eh s, i in loop: 0
08-31 16:50:28.079  8794  8882 V G2P-SRIB: After conversion: S_Health, S_Health, 8, 8
08-31 16:50:28.079  8794  8882 V G2P-SRIB: After g2p: prons 1, max_pron_len 16
08-31 16:50:28.079  8794  8882 V G2P-SRIB: Output pron: eh s hh eh l th, i in loop: 0
08-31 16:50:28.079  8794  8882 V G2P-SRIB: After conversion: Skype, Skype, 5, 5
08-31 16:50:28.079  8794  8882 V G2P-SRIB: After g2p: prons 1, max_pron_len 9
08-31 16:50:28.079  8794  8882 V G2P-SRIB: Output pron: s k ay p, i in loop: 0
08-31 16:50:28.079  8794  8882 V G2P-SRIB: After conversion: alarm, alarm, 5, 5
08-31 16:50:28.079  8794  8882 V G2P-SRIB: After g2p: prons 1, max_pron_len 12
08-31 16:50:28.079  8794  8882 V G2P-SRIB: Output pron: ah l aa r m, i in loop: 0
08-31 16:50:28.079  8794  8882 V G2P-SRIB: After conversion: Voice_Search, Voice_Search, 12, 12
08-31 16:50:28.079  8794  8882 V G2P-SRIB: After g2p: prons 1, max_pron_len 15
08-31 16:50:28.079  8912  8912 W ResourcesManager: getTopLevelResources: /system/priv-app/VoiceNote_4.0/VoiceNote_4.0.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.sec.android.app.voicenote
08-31 16:50:28.079  8794  8882 V G2P-SRIB: Output pron: v oy s s er ch, i in loop: 0
08-31 16:50:28.079  8794  8882 V G2P-SRIB: After conversion: Play_Movies_&_TV, Play_Movies_&_TV, 16, 16
08-31 16:50:28.079  8912  8912 D ResourcesManager: For user 0 new overlays fetched Null
08-31 16:50:28.079  8912  8912 I [SC]ExternalOEMControl_VOICE: updateModelInfo() called, src[VOICE] cid[vMkD7IBgaR] isNew[true] dataType[null]
08-31 16:50:28.079  8912  8912 I [SC]ExternalModel: [BaseModel]VOICE                     com.sec.android.app.voicenote                      content://com.sec.android.app.voicenote.backup
08-31 16:50:28.079  8912  8912 I [SC]ExternalModel: duplicateConfig[0] : true
08-31 16:50:28.079  8912  8912 I [SC]ExternalModel: duplicateConfig[1] : false
08-31 16:50:28.079  8912  8912 I [SC]ModelManager: addModel[+] VOICE                     isEnable[true ] V2:content://com.sec.android.app.voicenote.backup::com.sec.android.app.voicenote
08-31 16:50:28.079  8912  8912 I [SC]ModelManager: loadExternalModelsFromPkg[VOICE                                        ] pkg:com.sec.android.app.voicenote                 register[IFileClient:vMkD7IBgaR]
08-31 16:50:28.079  4146  4161 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg com.google.android.googlequicksearchbox,id=10436,extra=Bundle[mParcelledData.dataSize=84]
08-31 16:50:28.079  4146  4146 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=10436, samsung.notification.type=normal, samsung.people.package_name=com.google.android.googlequicksearchbox}]
08-31 16:50:28.079  4146  4146 I PeopleStripeService: PeopleNotificationReceiver:3
08-31 16:50:28.079  8794  8882 V G2P-SRIB: After g2p: prons 4, max_pron_len 49
08-31 16:50:28.079  8794  8882 V G2P-SRIB: Output pron: p l ey m uw v iy z ah n d t iy v iy, i in loop: 0
08-31 16:50:28.079  8794  8882 V G2P-SRIB: Output pron: p l ey m uw v iy z ae n d t iy v iy, i in loop: 1
08-31 16:50:28.079  8794  8882 V G2P-SRIB: Output pron: p l ey m uw v iy z ah n d t eh l ah v ih zh ah n, i in loop: 2
08-31 16:50:28.079  8794  8882 V G2P-SRIB: Output pron: p l ey m uw v iy z ae n d t eh l ah v ih zh ah n, i in loop: 3
08-31 16:50:28.079  4146  4146 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
08-31 16:50:28.079  8794  8882 V G2P-SRIB: After conversion: My_Files, My_Files, 8, 8
08-31 16:50:28.079  4146  4146 I PeopleDataManager: removeNotification
08-31 16:50:28.089  8912  8912 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.samsung.android.email.provider
08-31 16:50:28.079  4146  4146 I NotificationParser: getNotiType:com.google.android.googlequicksearchbox,null
08-31 16:50:28.079  4146  4146 D PeopleDataManager: removeNotiInfo: id =10436,packageName=com.google.android.googlequicksearchbox,isEdgeNotification=false,key=null,removeAll=false
08-31 16:50:28.079  4146  4146 D PeopleDataManager: removeNotiInfo =null
08-31 16:50:28.079  8794  8882 V G2P-SRIB: After g2p: prons 1, max_pron_len 14
08-31 16:50:28.079  8794  8882 V G2P-SRIB: Output pron: m ay f ay l z, i in loop: 0
08-31 16:50:28.079  8794  8882 V G2P-SRIB: After conversion: Maps, Maps, 4, 4
08-31 16:50:28.089  8794  8882 V G2P-SRIB: After g2p: prons 1, max_pron_len 9
08-31 16:50:28.089  8794  8882 V G2P-SRIB: Output pron: m ae p s, i in loop: 0
08-31 16:50:28.089  8794  8882 V G2P-SRIB: After conversion: Clock, Clock, 5, 5
08-31 16:50:28.089  8794  8882 V G2P-SRIB: After g2p: prons 1, max_pron_len 9
08-31 16:50:28.089  8794  8882 V G2P-SRIB: Output pron: k l aa k, i in loop: 0
08-31 16:50:28.089  8794  8882 V G2P-SRIB: After conversion: Settings, Settings, 8, 8
08-31 16:50:28.089  8794  8882 V G2P-SRIB: After g2p: prons 1, max_pron_len 15
08-31 16:50:28.089  8794  8882 V G2P-SRIB: Output pron: s eh t ih ng z, i in loop: 0
08-31 16:50:28.089  8794  8882 V G2P-SRIB: After conversion: s_planner, s_planner, 9, 9
08-31 16:50:28.089  8794  8882 V G2P-SRIB: After g2p: prons 1, max_pron_len 17
08-31 16:50:28.089  8794  8882 V G2P-SRIB: Output pron: eh s p l ae n er, i in loop: 0
08-31 16:50:28.089  8794  8882 V G2P-SRIB: After conversion: PowerPoint, PowerPoint, 10, 10
08-31 16:50:28.089  8794  8882 V G2P-SRIB: After g2p: prons 1, max_pron_len 17
08-31 16:50:28.089  8794  8882 V G2P-SRIB: Output pron: p aw er p oy n t, i in loop: 0
08-31 16:50:28.089  8912  8912 D ResourcesManager: For user 0 new overlays fetched Null
08-31 16:50:28.089  8794  8882 V G2P-SRIB: After conversion: Facebook, Facebook, 8, 8
08-31 16:50:28.089  8794  8882 V G2P-SRIB: After g2p: prons 1, max_pron_len 14
08-31 16:50:28.089  8794  8882 V G2P-SRIB: Output pron: f ey s b uh k, i in loop: 0
08-31 16:50:28.089  8794  8882 V G2P-SRIB: After conversion: Gmail, Gmail, 5, 5
08-31 16:50:28.089  8794  8882 V G2P-SRIB: After g2p: prons 1, max_pron_len 9
08-31 16:50:28.089  8794  8882 V G2P-SRIB: Output pron: g m ey l, i in loop: 0
08-31 16:50:28.089  8794  8882 V G2P-SRIB: After conversion: YouTube, YouTube, 7, 7
08-31 16:50:28.089  8794  8882 V G2P-SRIB: After g2p: prons 1, max_pron_len 12
08-31 16:50:28.089  8794  8882 V G2P-SRIB: Output pron: y uw t uw b, i in loop: 0
08-31 16:50:28.089  8794  8882 V G2P-SRIB: After conversion: diary, diary, 5, 5
08-31 16:50:28.089  8794  8882 V G2P-SRIB: After g2p: prons 1, max_pron_len 11
08-31 16:50:28.089  8794  8882 V G2P-SRIB: Output pron: d ay er iy, i in loop: 0
08-31 16:50:28.089  8794  8882 V G2P-SRIB: After conversion: Camera, Camera, 6, 6
08-31 16:50:28.089  8912  8912 I [SC]ExternalOEMControlLegacy_Email: updateModelInfo() called, src[Email] cid[QJ5JBlRnP9] isNew[true]
08-31 16:50:28.089  8912  8912 I [SC]ExternalModelLegacy: [BaseModel]Email                     com.samsung.android.email.provider                 content://com.samsung.android.email.provider.backup[Q]
08-31 16:50:28.089  8912  8912 I [SC]ModelManager: addModel[+] Email                     isEnable[true ] V1:content://com.samsung.android.email.provider.backup::com.samsung.android.email.provider:[Q]
08-31 16:50:28.089  8912  8912 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.sec.android.app.sbrowser
08-31 16:50:28.089  8794  8882 V G2P-SRIB: After g2p: prons 1, max_pron_len 13
08-31 16:50:28.089  8912  8912 I [SC]ModelManager: loadExternalModelsFromPkg[Email                                        ] pkg:com.samsung.android.email.provider            register[ISCloudQBNRClient:QJ5JBlRnP9]
08-31 16:50:28.089  8794  8882 V G2P-SRIB: Output pron: k ae m er ax, i in loop: 0
08-31 16:50:28.089  8794  8882 V G2P-SRIB: After conversion: Google, Google, 6, 6
08-31 16:50:28.089  8794  8882 V G2P-SRIB: After g2p: prons 1, max_pron_len 12
08-31 16:50:28.089  8794  8882 V G2P-SRIB: Output pron: g uw g ax l, i in loop: 0
08-31 16:50:28.089  8794  8882 V G2P-SRIB: First char , last char 
08-31 16:50:28.089  8794  8882 V G2P-SRIB: Before UTF release deinit
08-31 16:50:28.089  8794  8882 V G2P-SRIB: Before g2p deinit
08-31 16:50:28.089  8794  8882 D DictionaryGenerator:PocketSphinx: FileWriter is closed sucessfull
08-31 16:50:28.089  8794  8882 D DictionaryGenerator:PocketSphinx: DFG : COMPLETED in 44 ms.
08-31 16:50:28.089  8794  8882 I DictionaryGenerator:PocketSphinx:OWC: DFG : Start
08-31 16:50:28.089  8794  8882 D DictionaryGenerator:PocketSphinx: Inside initFileWriter : Dict file name : /data/user/0/com.sec.svoice.lang.en_US/files/en_US/dict/contact.dict
08-31 16:50:28.089  8794  8882 I DictionaryGenerator:PocketSphinx: mDictionaryFile = { /data/user/0/com.sec.svoice.lang.en_US/files/en_US/dict/contact.dict }
08-31 16:50:28.089  8794  8882 D DictionaryGenerator:PocketSphinx: FileWriter created
08-31 16:50:28.089  8794  8882 D DictionaryGenerator:PocketSphinx: copying frm : /data/user/0/com.sec.svoice.lang.en_US/files/en_US/dict/contact.dict
08-31 16:50:28.089  8794  8882 D DictionaryGenerator:PocketSphinx: inside process,_one_word_Call
08-31 16:50:28.089  8794  8882 D DictionaryGenerator:PocketSphinx: /data/user/0/com.sec.svoice.lang.en_US/databases
08-31 16:50:28.089  8912  8912 D ResourcesManager: For user 0 new overlays fetched Null
08-31 16:50:28.089  8912  8912 I [SC]ExternalOEMControlLegacy_SBROWSERSETTING: updateModelInfo() called, src[SBROWSERSETTING] cid[kw8vqQFzo3] isNew[true]
08-31 16:50:28.089  8912  8912 I [SC]ExternalModelLegacy: [BaseModel]SBROWSERSETTING           com.sec.android.app.sbrowser                       content://com.sec.android.app.sbrowser.backup[Q]
08-31 16:50:28.089  8912  8912 I [SC]ModelManager: addModel[+] SBROWSERSETTING           isEnable[true ] V1:content://com.sec.android.app.sbrowser.backup::com.sec.android.app.sbrowser:[Q]
08-31 16:50:28.089  8912  8912 I [SC]ModelManager: loadExternalModelsFromPkg[SBROWSERSETTING                              ] pkg:com.sec.android.app.sbrowser                  register[ISCloudQBNRClient:kw8vqQFzo3]
08-31 16:50:28.099  8794  8882 D DictionaryGenerator:PocketSphinx::OWC: Deleted below entries : 
08-31 16:50:28.099  8794  8882 D DictionaryGenerator:PocketSphinx::OWC: Newly added entries are : 
08-31 16:50:28.099  8794  8882 V G2P-SRIB: Build date: Apr 28 2016, 15:00:24
08-31 16:50:28.099  8794  8882 V G2P-SRIB: enUS G2P libs
08-31 16:50:28.099  8794  8882 V G2P-SRIB: stringCount: 0
08-31 16:50:28.099  8794  8882 V G2P-SRIB: Config: lang: en-US
08-31 16:50:28.099  8794  8882 V G2P-SRIB: variant: mp
08-31 16:50:28.099  8794  8882 V G2P-SRIB: prefix: slot_contacts_start__
08-31 16:50:28.099  8794  8882 V G2P-SRIB: suffix: __slot_contacts_end
08-31 16:50:28.099  8912  8912 W ResourcesManager: getTopLevelResources: /system/priv-app/SVoice_1.0/SVoice_1.0.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.samsung.voiceserviceplatform
08-31 16:50:28.099  8794  8882 V G2P-SRIB: Options dump_pron: W W K K K K K K K K K K K K K W W,
08-31 16:50:28.099  8794  8882 V G2P-SRIB: First char , last char �
08-31 16:50:28.099  8794  8882 V G2P-SRIB: Before UTF release deinit
08-31 16:50:28.099  8794  8882 V G2P-SRIB: Before g2p deinit
08-31 16:50:28.099  8912  8912 D ResourcesManager: For user 0 new overlays fetched Null
08-31 16:50:28.099  8794  8882 D DictionaryGenerator:PocketSphinx: FileWriter is closed sucessfull
08-31 16:50:28.099  8794  8882 D DictionaryGenerator:PocketSphinx:OWC: DFG : COMPLETED in 9 ms.
08-31 16:50:28.099  8912  8912 I [SC]ExternalOEMControlLegacy_SVOICESETTING: updateModelInfo() called, src[SVOICESETTING] cid[bLEmzxKOex] isNew[true]
08-31 16:50:28.099  8794  8882 D PLMGenManager: TimeTaken for Dict & FSG generation 109ms
08-31 16:50:28.099  8794  8882 D etickcount:PocketSphinx Recognition Engine:  : VSP::TimeTaken for syncUserData 538ms
08-31 16:50:28.099  8912  8912 I [SC]ExternalModelLegacy: [BaseModel]SVOICESETTING             com.samsung.voiceserviceplatform                   content://com.samsung.voiceserviceplatform.backup[Q]
08-31 16:50:28.099  8912  8912 I [SC]ModelManager: addModel[+] SVOICESETTING             isEnable[true ] V1:content://com.samsung.voiceserviceplatform.backup::com.samsung.voiceserviceplatform:[Q]
08-31 16:50:28.099  8912  8912 I [SC]ModelManager: loadExternalModelsFromPkg[SVOICESETTING                                ] pkg:com.samsung.voiceserviceplatform              register[ISCloudQBNRClient:bLEmzxKOex]
08-31 16:50:28.099  4434  8911 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 131 ms] updated apps [took 131 ms] 
08-31 16:50:28.099  8912  8912 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M/SPlanner_M.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.android.calendar
08-31 16:50:28.109  8912  8912 D ResourcesManager: For user 0 new overlays fetched Null
08-31 16:50:28.109  8794  8882 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : #en_us_v2.0.6
08-31 16:50:28.109  8912  8912 I [SC]ExternalOEMControlLegacy_CALENDARSETTING: updateModelInfo() called, src[CALENDARSETTING] cid[ztQlGIvsvZ] isNew[true]
08-31 16:50:28.109  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP::#en_us_v2.0.6
08-31 16:50:28.109  8794  8882 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : ##General
08-31 16:50:28.109  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP::##General
08-31 16:50:28.109  8912  8912 I [SC]ExternalModelLegacy: [BaseModel]CALENDARSETTING           com.android.calendar                               content://com.android.calendar.backup[Q]
08-31 16:50:28.109  8912  8912 I [SC]ModelManager: addModel[+] CALENDARSETTING           isEnable[true ] V1:content://com.android.calendar.backup::com.android.calendar:[Q]
08-31 16:50:28.109  8912  8912 I [SC]ModelManager: loadExternalModelsFromPkg[CALENDARSETTING                              ] pkg:com.android.calendar                          register[ISCloudQBNRClient:ztQlGIvsvZ]
08-31 16:50:28.109  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP::-hmm	am
08-31 16:50:28.109  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP::-fsg	lm/hero.detmin.fsg
08-31 16:50:28.109  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP::-fsg2	lm/hero.detmin.wo.wakeup.fsg
08-31 16:50:28.109  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP::-dict	dict/hero.dict
08-31 16:50:28.109  8794  8882 I eN66    : JNI Enter Function Java_com_asr_pocketsphinx_pocketsphinxJNI_Config_1setNLUCfg
08-31 16:50:28.109  8794  8882 I eN66    : Library build date: May  2 2016 @ 14:31:17
08-31 16:50:28.109  8794  8882 I eN66    : JNI Config_setNLUCfg /data/user/0/com.sec.svoice.lang.en_US/files/en_US/nlu/nlu.cfg
08-31 16:50:28.109  8794  8882 I eN66    : JNI debug Config_setNLUCfg /data/user/0/com.sec.svoice.lang.en_US/files/en_US/nlu/nlu.cfg 1 time
08-31 16:50:28.109  8794  8882 I eN66    : JNI Exit Function Java_com_asr_pocketsphinx_pocketsphinxJNI_Config_1setNLUCfg
08-31 16:50:28.109  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP::-rnlu	nlu/nlu.cfg
08-31 16:50:28.109  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP::-maxwpf	4
08-31 16:50:28.109  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP::-maxhmmpf	1800
08-31 16:50:28.109  8794  8882 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : #-rawlogdir
08-31 16:50:28.109  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP::#-rawlogdir	log
08-31 16:50:28.109  8794  8882 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : 
08-31 16:50:28.109  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP::
08-31 16:50:28.109  8794  8882 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : ##DNN
08-31 16:50:28.109  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP::##DNN
08-31 16:50:28.109  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP::-context	11
08-31 16:50:28.109  8794  8882 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : #quantization range
08-31 16:50:28.109  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP::#quantization range
08-31 16:50:28.109  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP::-QRange	1024
08-31 16:50:28.109  8794  8882 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : #1 means not skipped, 2 means skip every 2 frames
08-31 16:50:28.109  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP::#1 means not skipped, 2 means skip every 2 frames
08-31 16:50:28.109  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP::-frmskip	1
08-31 16:50:28.109  8794  8882 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : #quantized dnn binary file (not using dnn)
08-31 16:50:28.109  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP::#quantized dnn binary file (not using dnn)
08-31 16:50:28.109  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP::-qdnn	am/qdnn.net
08-31 16:50:28.109  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP::-feat_transform	am/feat.bin
08-31 16:50:28.109  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP::-prior	am/prior_prob.out
08-31 16:50:28.109  8794  8882 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : 
08-31 16:50:28.109  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP::
08-31 16:50:28.109  8794  8882 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : ##Confidence score
08-31 16:50:28.109  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP::##Confidence score
08-31 16:50:28.109  8794  8882 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : #-confs
08-31 16:50:28.109  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP::#-confs	yes
08-31 16:50:28.109  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP::-conf_use_senone	0
08-31 16:50:28.109  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP::-conf_use_pls	0
08-31 16:50:28.109  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP::-conf_use_ll	1
08-31 16:50:28.109  8912  8912 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.android.settings
08-31 16:50:28.109  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP::-pip	1.5
08-31 16:50:28.109  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP::-wip	7
08-31 16:50:28.109  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP::-lw	3
08-31 16:50:28.109  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP::-dnn_ascale	2.5
08-31 16:50:28.109  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP::-prior_ratio	0.92
08-31 16:50:28.109  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP::-conf_mapscore_params	[-42,0,-18,50,-4,100][9,0,28,50,57,100][-12,0,10,50,24,100]
08-31 16:50:28.109  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP::-non_speech_tied_states	[93:94:95]
08-31 16:50:28.109  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP::-conf_disagreement_percent	20.0
08-31 16:50:28.109  8794  8882 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : 
08-31 16:50:28.109  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP::
08-31 16:50:28.109  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP::-conf_max_llr_th	25
08-31 16:50:28.109  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP::-conf_use_ci	no
08-31 16:50:28.109  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP::-bestpath	0
08-31 16:50:28.109  8794  8882 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : #now phoneloop score is not used phoneloop score => senon score
08-31 16:50:28.109  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP::#now phoneloop score is not used phoneloop score => senon score
08-31 16:50:28.109  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP::-pl_window	0
08-31 16:50:28.109  8794  8882 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : #excluding silence frames in score
08-31 16:50:28.109  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP::#excluding silence frames in score
08-31 16:50:28.109  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP::-no_silence	1
08-31 16:50:28.109  8794  8882 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : #mapping parameter
08-31 16:50:28.109  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP::#mapping parameter
08-31 16:50:28.109  8794  8882 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : #-lang
08-31 16:50:28.109  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP::#-lang	1
08-31 16:50:28.109  8794  8882 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : #excluding score on WUW
08-31 16:50:28.109  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP::#excluding score on WUW
08-31 16:50:28.109  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP::-wake-up-cmd	1
08-31 16:50:28.109  8794  8882 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : 
08-31 16:50:28.109  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP::
08-31 16:50:28.109  8794  8882 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : ##Rejection
08-31 16:50:28.109  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP::##Rejection
08-31 16:50:28.109  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP::-reject_list	lm/reject.hyp
08-31 16:50:28.109  8794  8882 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : 
08-31 16:50:28.109  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP::
08-31 16:50:28.109  8794  8882 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : ##Android related
08-31 16:50:28.109  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP::##Android related
08-31 16:50:28.109  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP::-conf_thresh	49
08-31 16:50:28.109  8794  8882 D etickcount:PocketSphinx Recognition Engine:  : VSP::Previous state : INIT
08-31 16:50:28.109  8794  8882 I eN66    : JNI Enter Function Java_com_asr_pocketsphinx_pocketsphinxJNI_new_1Decoder_1_1SWIG_11
08-31 16:50:28.109  8794  8882 I eN66    : ps_reinit start
08-31 16:50:28.109  8794  8882 I eN66    : configured dir of hmm /data/user/0/com.sec.svoice.lang.en_US/files/en_US/am
08-31 16:50:28.109  8794  8882 I eN66    : ps_init_defaults end
08-31 16:50:28.109  8912  8912 D ResourcesManager: For user 0 new overlays fetched Null
08-31 16:50:28.109  8912  8912 I [SC]ExternalOEMControlLegacy_ACCESSIBILITYSETTINGS: updateModelInfo() called, src[ACCESSIBILITYSETTINGS] cid[X6qErjsfs2] isNew[true]
08-31 16:50:28.109  8912  8912 I [SC]ExternalModelLegacy: [BaseModel]ACCESSIBILITYSETTINGS     com.android.settings                               content://com.android.settings.accessibility.sharedaccessibility.backup[Q]
08-31 16:50:28.109  8912  8912 I [SC]ModelManager: addModel[+] ACCESSIBILITYSETTINGS     isEnable[true ] V1:content://com.android.settings.accessibility.sharedaccessibility.backup::com.android.settings:[Q]
08-31 16:50:28.109  8912  8912 I [SC]ModelManager: loadExternalModelsFromPkg[ACCESSIBILITYSETTINGS                        ] pkg:com.android.settings                          register[ISCloudQBNRClient:X6qErjsfs2]
08-31 16:50:28.109  8912  8912 I [SC]ModelManager: loadExternalModelsFromPkg[CONNECTIONS                                  ] pkg:com.android.settings                          subKey[CONNECTIONS]
08-31 16:50:28.109  8912  8912 I [SC]ConnectionsSetting: CONNECTIONS               setEnable[true]
08-31 16:50:28.109  8912  8912 I [SC]ModelManager: loadExternalModelsFromPkg[CONNECTIONS                                  ] pkg:com.android.settings                          subKey[WiFi]
08-31 16:50:28.109  8912  8912 I [SC]ConnectionsSetting: CONNECTIONS               setEnable[true]
08-31 16:50:28.109  8912  8912 W ResourcesManager: getTopLevelResources: /system/priv-app/TouchWizHome_2016/TouchWizHome_2016.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.sec.android.app.launcher
08-31 16:50:28.109  8912  8912 D ResourcesManager: For user 0 new overlays fetched Null
08-31 16:50:28.119  8912  8912 E [SC]SCLOUD_ERR-CommonUtil: getCertificateSHA1Fingerprint err :com.samsung.android.scloud.backupsamplecode 
08-31 16:50:28.119  8912  8912 I [SC]ModelManager: loadExternalModelsFromPkg pkg:com.samsung.android.scloud.backupsamplecode   NotExist[null]
08-31 16:50:28.119  8912  8912 W ResourcesManager: getTopLevelResources: /system/priv-app/TeleService/TeleService.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.android.phone
08-31 16:50:28.119  8912  8912 D ResourcesManager: For user 0 new overlays fetched Null
08-31 16:50:28.119  8912  8912 I [SC]ExternalOEMControlLegacy_CALLSETTING: updateModelInfo() called, src[CALLSETTING] cid[IHLhQxraiP] isNew[true]
08-31 16:50:28.119  8912  8912 I [SC]ExternalModelLegacy: [BaseModel]CALLSETTING               com.android.phone                                  content://com.android.phone.backup[Q]
08-31 16:50:28.119  8912  8912 I [SC]ModelManager: addModel[+] CALLSETTING               isEnable[true ] V1:content://com.android.phone.backup::com.android.phone:[Q]
08-31 16:50:28.119  8912  8912 I [SC]ModelManager: loadExternalModelsFromPkg[CALLSETTING                                  ] pkg:com.android.phone                             register[ISCloudQBNRClient:IHLhQxraiP]
08-31 16:50:28.119  8912  8912 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.sec.android.inputmethod
08-31 16:50:28.119  8912  8912 D ResourcesManager: For user 0 new overlays fetched Null
08-31 16:50:28.129  8912  8912 I [SC]ExternalOEMControlLegacy_IMESETTING: updateModelInfo() called, src[IMESETTING] cid[ghXxWAP1aK] isNew[true]
08-31 16:50:28.129  8912  8912 I [SC]ExternalModelLegacy: [BaseModel]IMESETTING                com.sec.android.inputmethod                        content://com.sec.android.inputmethod.backup[Q]
08-31 16:50:28.129  8912  8912 I [SC]ModelManager: addModel[+] IMESETTING                isEnable[true ] V1:content://com.sec.android.inputmethod.backup::com.sec.android.inputmethod:[Q]
08-31 16:50:28.129  8912  8912 I [SC]ModelManager: loadExternalModelsFromPkg[IMESETTING                                   ] pkg:com.sec.android.inputmethod                   register[ISCloudQBNRClient:ghXxWAP1aK]
08-31 16:50:28.129  8912  8912 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.android.contacts
08-31 16:50:28.129  8912  8912 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:28.129  8912  8912 I [SC]ExternalOEMControlLegacy_MyProfile: updateModelInfo() called, src[MyProfile] cid[2yOE2P9maz] isNew[true]
08-31 16:50:28.129  8912  8912 I [SC]ExternalModelLegacy: [BaseModel]MyProfile                 com.android.contacts                               content://com.samsung.contacts.backup
08-31 16:50:28.129  8912  8912 I [SC]ModelManager: addModel[+] MyProfile                 isEnable[true ] V1:content://com.samsung.contacts.backup::com.android.contacts:
08-31 16:50:28.129  8912  8912 I [SC]ModelManager: loadExternalModelsFromPkg[MyProfile                                    ] pkg:com.android.contacts                          register[ISCloudBNRClient:2yOE2P9maz]
08-31 16:50:28.129  8912  8912 I [SC]ExternalOEMControlLegacy_CONTACTSETTING: updateModelInfo() called, src[CONTACTSETTING] cid[jqwmo66Bdc] isNew[true]
08-31 16:50:28.129  8912  8912 I [SC]ExternalModelLegacy: [BaseModel]CONTACTSETTING            com.android.contacts                               content://com.samsung.contacts.backup[Q]
08-31 16:50:28.129  8912  8912 I [SC]ModelManager: addModel[+] CONTACTSETTING            isEnable[true ] V1:content://com.samsung.contacts.backup::com.android.contacts:[Q]
08-31 16:50:28.129  8912  8912 I [SC]ModelManager: loadExternalModelsFromPkg[CONTACTSETTING                               ] pkg:com.android.contacts                          register[ISCloudQBNRClient:jqwmo66Bdc]
08-31 16:50:28.129  8912  8912 I [SC]ExternalOEMControl_CONTACT: updateModelInfo() called, src[CONTACT] cid[2vInYbEf2V] isNew[true] dataType[json]
08-31 16:50:28.129  8912  8912 I [SC]ExternalModel: [BaseModel]CONTACT                   com.android.contacts                               content://com.samsung.contacts.backup
08-31 16:50:28.129  8912  8912 I [SC]ModelManager: addModel[+] CONTACT                   isEnable[true ] V2:content://com.samsung.contacts.backup::com.android.contacts
08-31 16:50:28.129  8912  8912 I [SC]ModelManager: loadExternalModelsFromPkg[CONTACT                                      ] pkg:com.android.contacts                          register[IRecordClient:2vInYbEf2V]
08-31 16:50:28.129  8912  8912 I [SC]ModelManager: loadExternalModelsFromPkg[HomescreenBackup                             ] pkg:com.android.contacts                          subKey[HomescreenContactShortcut]
08-31 16:50:28.129  8912  8912 W ResourcesManager: getTopLevelResources: /system/app/ClockPackage_M/ClockPackage_M.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.sec.android.app.clockpackage
08-31 16:50:28.139  8912  8912 D ResourcesManager: For user 0 new overlays fetched Null
08-31 16:50:28.139  8912  8912 I [SC]ExternalOEMControlLegacy_Alarm: updateModelInfo() called, src[Alarm] cid[v5VJ0Ep6EE] isNew[true]
08-31 16:50:28.139  8912  8912 I [SC]ExternalModelLegacy: [BaseModel]Alarm                     com.sec.android.app.clockpackage                   content://com.sec.android.app.clockpackage
08-31 16:50:28.139  8912  8912 I [SC]ModelManager: addModel[+] Alarm                     isEnable[true ] V1:content://com.sec.android.app.clockpackage::com.sec.android.app.clockpackage:
08-31 16:50:28.139  8912  8912 I [SC]ModelManager: loadExternalModelsFromPkg[Alarm                                        ] pkg:com.sec.android.app.clockpackage              register[ISCloudBNRClient:v5VJ0Ep6EE]
08-31 16:50:28.139  8912  8912 I [SC]ExternalOEMControlLegacy_WorldClock: updateModelInfo() called, src[WorldClock] cid[pYz7p28bSl] isNew[true]
08-31 16:50:28.139  8912  8912 I [SC]ExternalModelLegacy: [BaseModel]WorldClock                com.sec.android.app.clockpackage                   content://com.sec.android.app.clockpackage
08-31 16:50:28.139  8912  8912 I [SC]ModelManager: addModel[+] WorldClock                isEnable[true ] V1:content://com.sec.android.app.clockpackage::com.sec.android.app.clockpackage:
08-31 16:50:28.139  8912  8912 I [SC]ModelManager: loadExternalModelsFromPkg[WorldClock                                   ] pkg:com.sec.android.app.clockpackage              register[ISCloudBNRClient:pYz7p28bSl]
08-31 16:50:28.139  8912  8912 I [SC]ModelManager: loadExternalModelsFromPkg[HomescreenBackup                             ] pkg:com.sec.android.app.clockpackage              subKey[ALARMWIDGET]
08-31 16:50:28.139  8912  8912 I [SC]ModelManager: loadExternalModelsFromPkg[HomescreenBackup                             ] pkg:com.sec.android.app.clockpackage              subKey[DUALCLOCKWIDGET]
08-31 16:50:28.139  8912  8912 W ResourcesManager: getTopLevelResources: /system/priv-app/SecCalendarProvider_NOTSTICKER/SecCalendarProvider_NOTSTICKER.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.android.providers.calendar
08-31 16:50:28.139  8912  8912 D ResourcesManager: For user 0 new overlays fetched Null
08-31 16:50:28.139  8912  8912 I [SC]ExternalOEMControl_EVENT: updateModelInfo() called, src[EVENT] cid[qsoHwGCEEw] isNew[true] dataType[json]
08-31 16:50:28.139  8912  8912 I [SC]ExternalModel: [BaseModel]EVENT                     com.android.providers.calendar                     content://com.samsung.android.providers.calendar.backup
08-31 16:50:28.139  8912  8912 I [SC]ModelManager: addModel[+] EVENT                     isEnable[true ] V2:content://com.samsung.android.providers.calendar.backup::com.android.providers.calendar
08-31 16:50:28.139  8912  8912 I [SC]ModelManager: loadExternalModelsFromPkg[EVENT                                        ] pkg:com.android.providers.calendar                register[IRecordClient:qsoHwGCEEw]
08-31 16:50:28.139  8912  8912 I [SC]ExternalOEMControl_TASK: updateModelInfo() called, src[TASK] cid[cLT79jJ29l] isNew[true] dataType[json]
08-31 16:50:28.139  8912  8912 I [SC]ExternalModel: [BaseModel]TASK                      com.android.providers.calendar                     content://com.samsung.android.providers.calendar.backup
08-31 16:50:28.139  8912  8912 I [SC]ModelManager: addModel[+] TASK                      isEnable[true ] V2:content://com.samsung.android.providers.calendar.backup::com.android.providers.calendar
08-31 16:50:28.139  8912  8912 I [SC]ModelManager: loadExternalModelsFromPkg[TASK                                         ] pkg:com.android.providers.calendar                register[IRecordClient:cLT79jJ29l]
08-31 16:50:28.139  8912  8912 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Epic_Common/SecMms_Epic_Common.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.android.mms
08-31 16:50:28.139  8912  8912 D ResourcesManager: For user 0 new overlays fetched Null
08-31 16:50:28.149  8912  8912 I [SC]ExternalOEMControlLegacy_MessagesSettings: updateModelInfo() called, src[MessagesSettings] cid[XUHtHcYNfq] isNew[true]
08-31 16:50:28.149  8912  8912 I [SC]ExternalModelLegacy: [BaseModel]MessagesSettings          com.android.mms                                    content://com.samsung.mms.settings.backup[Q]
08-31 16:50:28.149  8912  8912 I [SC]ModelManager: addModel[+] MessagesSettings          isEnable[true ] V1:content://com.samsung.mms.settings.backup::com.android.mms:[Q]
08-31 16:50:28.149  8912  8912 I [SC]ModelManager: loadExternalModelsFromPkg[MessagesSettings                             ] pkg:com.android.mms                               register[ISCloudQBNRClient:XUHtHcYNfq]
08-31 16:50:28.149  8912  8912 W ResourcesManager: getTopLevelResources: /system/priv-app/SecTelephonyProvider_Epic/SecTelephonyProvider_Epic.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.android.providers.telephony
08-31 16:50:28.149  8912  8912 D ResourcesManager: For user 0 new overlays fetched Null
08-31 16:50:28.149  8912  8912 I [SC]ExternalOEMControlLegacy_Chat: updateModelInfo() called, src[Chat] cid[nx7Fde25jd] isNew[true]
08-31 16:50:28.149  4280  4291 I [PDLIB]ClientProvider, VERSION : 2.2.0: call !!  method : getClientInfo, arg : Chat
08-31 16:50:28.149  4280  4291 D TP/BnRUtils: getCscFreeMessage(), config = off
08-31 16:50:28.149  4280  4291 D TP/BnRUtils: getEnableSupportBackup() = false
08-31 16:50:28.149  4280  4291 I [PDLIB]BNRClientHelper-Chat: GET_CLIENT_INFO, Chat
08-31 16:50:28.149  8912  8912 I [SC]ExternalOEMControlLegacy_Chat: updateModelInfo() supportBnr is false
08-31 16:50:28.149  8912  8912 I [SC]ExternalOEMControlLegacy_FileTransfer: updateModelInfo() called, src[FileTransfer] cid[LyxMGTa8W3] isNew[true]
08-31 16:50:28.149  4280  4636 I [PDLIB]ClientProvider, VERSION : 2.2.0: call !!  method : getClientInfo, arg : FileTransfer
08-31 16:50:28.149  4280  4636 D TP/BnRUtils: getCscFreeMessage(), config = off
08-31 16:50:28.149  4280  4636 D TP/BnRUtils: getEnableSupportBackup() = false
08-31 16:50:28.149  4280  4636 I [PDLIB]BNRClientHelper-FileTransfer: GET_CLIENT_INFO, FileTransfer
08-31 16:50:28.149  8912  8912 I [SC]ExternalOEMControlLegacy_FileTransfer: updateModelInfo() supportBnr is false
08-31 16:50:28.149  8912  8912 I [SC]ExternalOEMControl_SMS: updateModelInfo() called, src[SMS] cid[N0iXqXm9oM] isNew[true] dataType[json]
08-31 16:50:28.149  8912  8912 I [SC]ExternalModel: [BaseModel]SMS                       com.android.providers.telephony                    content://com.android.providers.telephony.backup
08-31 16:50:28.149  8912  8912 I [SC]ModelManager: addModel[+] SMS                       isEnable[true ] V2:content://com.android.providers.telephony.backup::com.android.providers.telephony
08-31 16:50:28.149  8912  8912 I [SC]ModelManager: loadExternalModelsFromPkg[SMS                                          ] pkg:com.android.providers.telephony               register[IRecordClient:N0iXqXm9oM]
08-31 16:50:28.149  8912  8912 I [SC]ExternalOEMControl_MMS: updateModelInfo() called, src[MMS] cid[I7o6E6m1Lj] isNew[true] dataType[json]
08-31 16:50:28.149  8912  8912 I [SC]ExternalModel: [BaseModel]MMS                       com.android.providers.telephony                    content://com.android.providers.telephony.backup
08-31 16:50:28.149  8912  8912 I [SC]ModelManager: addModel[+] MMS                       isEnable[true ] V2:content://com.android.providers.telephony.backup::com.android.providers.telephony
08-31 16:50:28.149  8912  8912 I [SC]ModelManager: loadExternalModelsFromPkg[MMS                                          ] pkg:com.android.providers.telephony               register[IRecordClient:I7o6E6m1Lj]
08-31 16:50:28.149  8912  8912 W ResourcesManager: getTopLevelResources: /system/app/WeatherWidget2016/WeatherWidget2016.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.sec.android.daemonapp
08-31 16:50:28.159  8912  8912 D ResourcesManager: For user 0 new overlays fetched Null
08-31 16:50:28.159  8912  8912 I [SC]ExternalOEMControlLegacy_WEATHERWIDGET: updateModelInfo() called, src[WEATHERWIDGET] cid[oo2JSUuSBb] isNew[true]
08-31 16:50:28.159  8912  8912 I [SC]ExternalModelLegacy: [BaseModel]WEATHERWIDGET             com.sec.android.daemonapp                          content://com.sec.android.daemonapp.backup[Q]
08-31 16:50:28.159  8912  8912 I [SC]ModelManager: addModel[+] WEATHERWIDGET             isEnable[true ] V1:content://com.sec.android.daemonapp.backup::com.sec.android.daemonapp:[Q]
08-31 16:50:28.159  8912  8912 I [SC]ModelManager: loadExternalModelsFromPkg[WEATHERWIDGET                                ] pkg:com.sec.android.daemonapp                     register[ISCloudQBNRClient:oo2JSUuSBb]
08-31 16:50:28.159  8912  8912 I [SC]ModelManager: loadExternalModelsFromPkg[elapse:      81]
08-31 16:50:28.159  8912  8912 I [SC]ModelManager: ModelManager--[elapse:     113]
08-31 16:50:28.159  8912  8912 D InjectionManager: InjectionManager
08-31 16:50:28.159  8912  8912 D InjectionManager: fillFeatureStoreMap com.samsung.android.scloud
08-31 16:50:28.159  8912  8912 I InjectionManager: Constructor com.samsung.android.scloud, Feature store :{}
08-31 16:50:28.159  8912  8912 I InjectionManager: featureStore :{}
08-31 16:50:28.159  8912  8912 I [SC]SCloudReceiver: onReceive : android.intent.action.PACKAGE_ADDED
08-31 16:50:28.169  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
08-31 16:50:28.169  3152  3633 D EnterpriseController: netId is 0
08-31 16:50:28.169  3152  3633 D Netd    : getNetworkForDns: using netid 0 for uid 10002
,08-31 16:50:28.169  4585  4747 E         : Error communicating to API: https://prod.yana.asideas.de/api/v2/categories
08-31 16:50:28.169  4585  4747 E         : retrofit.RetrofitError: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
08-31 16:50:28.169  4585  4747 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:395)
08-31 16:50:28.169  4585  4747 E         : 	at retrofit.RestAdapter$RestHandler.access$100(RestAdapter.java:220)
08-31 16:50:28.169  4585  4747 E         : 	at retrofit.RestAdapter$RestHandler$1.invoke(RestAdapter.java:265)
08-31 16:50:28.169  4585  4747 E         : 	at retrofit.RxSupport$2.run(RxSupport.java:55)
08-31 16:50:28.169  4585  4747 E         : 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-31 16:50:28.169  4585  4747 E         : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-31 16:50:28.169  4585  4747 E         : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-31 16:50:28.169  4585  4747 E         : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-31 16:50:28.169  4585  4747 E         : 	at retrofit.Platform$Android$2$1.run(Platform.java:142)
08-31 16:50:28.169  4585  4747 E         : 	at java.lang.Thread.run(Thread.java:818)
08-31 16:50:28.169  4585  4747 E         : Caused by: java.net.UnknownHostException: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
08-31 16:50:28.169  4585  4747 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:470)
08-31 16:50:28.169  4585  4747 E         : 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
08-31 16:50:28.169  4585  4747 E         : 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
08-31 16:50:28.169  4585  4747 E         : 	at com.squareup.okhttp.internal.Network$1.resolveInetAddresses(Network.java:29)
08-31 16:50:28.169  4585  4747 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:187)
08-31 16:50:28.169  4585  4747 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.nextProxy(RouteSelector.java:156)
08-31 16:50:28.169  4585  4747 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.next(RouteSelector.java:98)
08-31 16:50:28.169  4585  4747 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.createNextConnection(HttpEngine.java:344)
08-31 16:50:28.169  4585  4747 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:327)
08-31 16:50:28.169  4585  4747 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:245)
08-31 16:50:28.169  4585  4747 E         : 	at com.squareup.okhttp.Call.getResponse(Call.java:267)
08-31 16:50:28.169  4585  4747 E         : 	at com.squareup.okhttp.Call$ApplicationInterceptorChain.proceed(Call.java:224)
08-31 16:50:28.169  4585  4747 E         : 	at com.squareup.okhttp.Call.getResponseWithInterceptorChain(Call.java:195)
08-31 16:50:28.169  4585  4747 E         : 	at com.squareup.okhttp.Call.execute(Call.java:79)
08-31 16:50:28.169  4585  4747 E         : 	at retrofit.client.OkClient.execute(OkClient.java:53)
08-31 16:50:28.169  4585  4747 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:326)
08-31 16:50:28.169  4585  4747 E         : 	... 9 more
08-31 16:50:28.169  4585  4747 E         : Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
08-31 16:50:28.169  4585  4747 E         : 	at libcore.io.Posix.android_getaddrinfo(Native Method)
08-31 16:50:28.169  4585  4747 E         : 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
08-31 16:50:28.169  4585  4747 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:451)
08-31 16:50:28.169  4585  4747 E         : 	... 24 more
08-31 16:50:28.169  4585  4747 E         : 
,08-31 16:50:28.179  8935  8935 E Zygote  : v2
08-31 16:50:28.179  8935  8935 I libpersona: KNOX_SDCARD checking this for 1000
08-31 16:50:28.179  8935  8935 I libpersona: KNOX_SDCARD not a persona
08-31 16:50:28.179  8935  8935 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,08-31 16:50:28.179  8935  8935 E Zygote  : accessInfo : 0
,08-31 16:50:28.179  3381  4915 I ActivityManager: Start proc 8935:com.samsung.android.bbc.bbcagent/1000 for broadcast-3 com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver
,08-31 16:50:28.179  3381  4915 I ActivityManager: Killing 8325:com.samsung.faceservice/5004 (adj 15): DHA:empty #33
,08-31 16:50:28.189  8794  8882 I eN66    : 
08-31 16:50:28.189  8794  8882 I eN66    : FSG model <n66_cmd_eng> is loaded
,08-31 16:50:28.189  8935  8935 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:50:28.189  8935  8935 D ActivityThread: Added TimaKeyStore provider
,08-31 16:50:28.189  7809  7809 I ServiceManager: [#CMH#] Disconnected to Service  com.samsung.faceservice.FaceService
,08-31 16:50:28.199  3381  4558 D ActivityManager: isAutoRunBlockedApp:: com.samsung.faceservice, Auto Run ON
08-31 16:50:28.199  3381  4558 W ActivityManager: Scheduling restart of crashed service com.samsung.faceservice/.FaceService in 20626ms
,08-31 16:50:28.209  8794  8882 I eN66    : 
08-31 16:50:28.209  8794  8882 I eN66    : ps_reinit : Secondary FSG model <n66_cmd_eng> is loaded
08-31 16:50:28.209  8794  8882 I eN66    : 
08-31 16:50:28.209  8794  8882 I eN66    : ps_reinit : Current active FSG model is <n66_cmd_eng>
08-31 16:50:28.209  8794  8882 I eN66    : Decoder initialization is complete
08-31 16:50:28.209  8794  8882 I eN66    : JNI Exit Function Java_com_asr_pocketsphinx_pocketsphinxJNI_new_1Decoder_1_1SWIG_11 Instance -184318016
08-31 16:50:28.209  8794  8882 I etickcount:PocketSphinx Recognition Engine:  : VSP::State changed to READY
08-31 16:50:28.209  8794  8882 D etickcount:PocketSphinx Recognition Engine:  : VSP::TimeTaken for Decoder init 111ms
08-31 16:50:28.209  8794  8882 D etickcount:PocketSphinx Recognition Engine:  : VSP::Total Load time 685ms
,08-31 16:50:28.209  3381  3974 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f20a0cc u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d40e44e 8935:com.samsung.android.bbc.bbcagent/1000}
,08-31 16:50:28.219  8935  8935 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
08-31 16:50:28.219  8935  8935 D RelationGraph: garbageCollect()
,08-31 16:50:28.219  8935  8935 W ResourcesManager: getTopLevelResources: /system/app/BBCAgent/BBCAgent.apk / 1.0 running in com.samsung.android.bbc.bbcagent rsrc of package com.samsung.android.bbc.bbcagent
,08-31 16:50:28.219  3381  4411 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,08-31 16:50:28.219  8935  8935 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
08-31 16:50:28.219  8935  8935 D ResourcesManager: For user 0 new overlays fetched Null
08-31 16:50:28.219  8935  8935 I InjectionManager: Inside getClassLibPath caller 
,08-31 16:50:28.229  8935  8935 W System  : ClassLoader referenced unknown path: /system/app/BBCAgent/lib/arm64
,08-31 16:50:28.229  8935  8935 D InjectionManager: InjectionManager
08-31 16:50:28.229  8935  8935 D InjectionManager: fillFeatureStoreMap com.samsung.android.bbc.bbcagent
,08-31 16:50:28.229  8935  8935 I InjectionManager: Constructor com.samsung.android.bbc.bbcagent, Feature store :{}
08-31 16:50:28.229  8935  8935 I InjectionManager: featureStore :{}
,08-31 16:50:28.249  8947  8947 E Zygote  : v2
08-31 16:50:28.249  8947  8947 I libpersona: KNOX_SDCARD checking this for 10098
08-31 16:50:28.249  8947  8947 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
08-31 16:50:28.249  8947  8947 I libpersona: KNOX_SDCARD not a persona
,08-31 16:50:28.249  8947  8947 E Zygote  : accessInfo : 0
08-31 16:50:28.249  8947  8947 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.docs 
,08-31 16:50:28.249  3381  3974 I ActivityManager: Start proc 8947:com.google.android.apps.docs/u0a98 for broadcast-3 com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,08-31 16:50:28.249  3381  3974 I ActivityManager: Killing 8313:com.samsung.ipservice/5004 (adj 15): DHA:empty #33
,08-31 16:50:28.269  8947  8947 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:50:28.269  8947  8947 D ActivityThread: Added TimaKeyStore provider
,08-31 16:50:28.269  7809  7809 I ServiceManager: [#CMH#] Disconnected to Service  com.samsung.ipservice.IPService
,08-31 16:50:28.279  3381  4428 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f20a0cc u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c85296f 8947:com.google.android.apps.docs/u0a98}
,08-31 16:50:28.289  8947  8947 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
08-31 16:50:28.289  8947  8947 D RelationGraph: garbageCollect()
,08-31 16:50:28.289  3381  4304 D ActivityManager: isAutoRunBlockedApp:: com.samsung.ipservice, Auto Run ON
08-31 16:50:28.289  3381  4304 W ActivityManager: Scheduling restart of crashed service com.samsung.ipservice/.IPService in 30538ms
08-31 16:50:28.289  8947  8947 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package com.google.android.apps.docs
,08-31 16:50:28.289  3381  3974 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
08-31 16:50:28.289  8947  8947 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,08-31 16:50:28.289  8947  8947 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:28.289  8947  8947 I InjectionManager: Inside getClassLibPath caller 
,08-31 16:50:28.299  8947  8947 W System  : ClassLoader referenced unknown path: /system/app/Drive/lib/arm64
,08-31 16:50:28.349  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-31 16:50:28.449  8947  8961 I GAv4    : Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
08-31 16:50:28.449  8947  8961 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-31 16:50:28.449  8947  8961 I GAv4    :   adb logcat -s GAv4
,08-31 16:50:28.459  8947  8961 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package com.google.android.apps.docs
,08-31 16:50:28.459  3381  4411 V AlarmManager:  remove PendingIntent] PendingIntent{564ed8b: PendingIntentRecord{dbae68 com.google.android.apps.docs broadcastIntent}}
,08-31 16:50:28.469  8947  8961 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-31 16:50:28.469  8947  8961 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-31 16:50:28.469  8947  8965 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-31 16:50:28.509  8947  8947 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.apps.docs/cache/docs_glide
,08-31 16:50:28.519  8947  8961 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db
08-31 16:50:28.519  8947  8961 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-journal
08-31 16:50:28.519  8947  8961 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-shm
08-31 16:50:28.519  8947  8961 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-wal
,08-31 16:50:28.529  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-31 16:50:28.539  8947  8947 D InjectionManager: InjectionManager
08-31 16:50:28.539  8947  8947 D InjectionManager: fillFeatureStoreMap com.google.android.apps.docs
08-31 16:50:28.539  8947  8947 I InjectionManager: Constructor com.google.android.apps.docs, Feature store :{}
08-31 16:50:28.539  8947  8947 I InjectionManager: featureStore :{}
,08-31 16:50:28.549  8970  8970 E Zygote  : v2
08-31 16:50:28.549  8970  8970 I libpersona: KNOX_SDCARD checking this for 1000
08-31 16:50:28.549  8970  8970 I libpersona: KNOX_SDCARD not a persona
08-31 16:50:28.549  8970  8970 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,08-31 16:50:28.549  8970  8970 E Zygote  : accessInfo : 0
08-31 16:50:28.549  3381  4419 I ActivityManager: Start proc 8970:com.samsung.android.app.filterinstaller/1000 for broadcast-3 com.samsung.android.app.filterinstaller/.PackageIntentReceiver
,08-31 16:50:28.559  3381  3974 I ActivityManager: Killing 7809:com.samsung.cmh:CMH/5004 (adj 15): DHA:empty #33
,08-31 16:50:28.569  8970  8970 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:50:28.569  8970  8970 D ActivityThread: Added TimaKeyStore provider
,08-31 16:50:28.579  3381  3460 E GameManagerService: remoteCallback died, callback: com.samsung.android.game.IGameManagerCallback$Stub$Proxy@6f14914, cookie: null
,08-31 16:50:28.579  3381  4428 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f20a0cc u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{27865bd 8970:com.samsung.android.app.filterinstaller/1000}
,08-31 16:50:28.589  8947  8962 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in com.google.android.apps.docs rsrc of package com.google.android.gms
,08-31 16:50:28.589  8970  8970 D RelationGraph: garbageCollect()
08-31 16:50:28.589  8970  8970 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,08-31 16:50:28.589  8970  8970 W ResourcesManager: getTopLevelResources: /system/app/FilterInstaller/FilterInstaller.apk / 1.0 running in com.samsung.android.app.filterinstaller rsrc of package com.samsung.android.app.filterinstaller
,08-31 16:50:28.589  3381  4771 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
08-31 16:50:28.589  8970  8970 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,08-31 16:50:28.589  8970  8970 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:28.589  3381  4179 D ActivityManager: isAutoRunBlockedApp:: com.samsung.cmh, Auto Run ON
,08-31 16:50:28.589  8947  8962 D ResourcesManager: For user 0 new overlays fetched Null
08-31 16:50:28.589  7869  7869 I StoryService: [StoryService] On destroy() 
08-31 16:50:28.589  7869  7869 I ServiceController: [StoryService] shutdown() 
08-31 16:50:28.589  8970  8970 I InjectionManager: Inside getClassLibPath caller 
,08-31 16:50:28.589  8947  8962 I InjectionManager: Inside getClassLibPath caller 
,08-31 16:50:28.599  8970  8970 W System  : ClassLoader referenced unknown path: /system/app/FilterInstaller/lib/arm64
,08-31 16:50:28.599  8970  8970 D InjectionManager: InjectionManager
08-31 16:50:28.599  8970  8970 D InjectionManager: fillFeatureStoreMap com.samsung.android.app.filterinstaller
,08-31 16:50:28.599  8970  8970 I InjectionManager: Constructor com.samsung.android.app.filterinstaller, Feature store :{}
08-31 16:50:28.599  8970  8970 I InjectionManager: featureStore :{}
,08-31 16:50:28.599  8970  8970 E FilterPackageIntentReceiver: This package is not a effect filter
,08-31 16:50:28.619  8947  8962 W System  : ClassLoader referenced unknown path: /system/priv-app/GmsCore/lib/arm64
,08-31 16:50:28.619  8983  8983 E Zygote  : v2
08-31 16:50:28.619  8983  8983 I libpersona: KNOX_SDCARD checking this for 10110
08-31 16:50:28.619  8983  8983 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
08-31 16:50:28.619  8983  8983 I libpersona: KNOX_SDCARD not a persona
,08-31 16:50:28.619  3381  4057 I ActivityManager: Start proc 8983:com.sec.android.widgetapp.samsungapps/u0a110 for broadcast-3 com.sec.android.widgetapp.samsungapps/.PackageChangeReceiver
08-31 16:50:28.619  8983  8983 E Zygote  : accessInfo : 0
08-31 16:50:28.619  8983  8983 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.sec.android.widgetapp.samsungapps 
,08-31 16:50:28.619  3381  4057 I ActivityManager: Killing 7986:com.google.android.gm/u0a113 (adj 15): DHA:empty #33
,08-31 16:50:28.629  8983  8983 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:50:28.629  8983  8983 D ActivityThread: Added TimaKeyStore provider
,08-31 16:50:28.639  3381  3904 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/37_task.xml.bak
,08-31 16:50:28.649  3381  4428 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f20a0cc u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{97117b2 8983:com.sec.android.widgetapp.samsungapps/u0a110}
,08-31 16:50:28.649  3381  4411 D ActivityManager: isAutoRunBlockedApp:: com.google.android.gm, Auto Run ON
,08-31 16:50:28.649  8983  8983 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
08-31 16:50:28.649  8983  8983 D RelationGraph: garbageCollect()
,08-31 16:50:28.649  8983  8983 W ResourcesManager: getTopLevelResources: /system/app/GalaxyAppsWidget_Phone_Hero/GalaxyAppsWidget_Phone_Hero.apk / 1.0 running in com.sec.android.widgetapp.samsungapps rsrc of package com.sec.android.widgetapp.samsungapps
,08-31 16:50:28.649  3381  4915 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
08-31 16:50:28.649  8983  8983 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,08-31 16:50:28.659  8983  8983 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:28.659  8983  8983 I InjectionManager: Inside getClassLibPath caller 
,08-31 16:50:28.659  8983  8983 W System  : ClassLoader referenced unknown path: /system/app/GalaxyAppsWidget_Phone_Hero/lib/arm64
,08-31 16:50:28.669  8983  8983 D InjectionManager: InjectionManager
08-31 16:50:28.669  8983  8983 D InjectionManager: fillFeatureStoreMap com.sec.android.widgetapp.samsungapps
,08-31 16:50:28.669  8983  8983 I InjectionManager: Constructor com.sec.android.widgetapp.samsungapps, Feature store :{}
08-31 16:50:28.669  8983  8983 I InjectionManager: featureStore :{}
,08-31 16:50:28.669  8947  8962 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-31 16:50:28.679  3381  3851 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f20a0cc u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8539eb6 8487:com.enhance.gameservice/u0a111}
,08-31 16:50:28.689  8947  8962 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-31 16:50:28.689  8487  8996 I DatabaseHelper: android.app.Application@e39cee9
08-31 16:50:28.689  8487  8996 I DatabaseHelper: Create a DatabaseHelper
,08-31 16:50:28.699  8997  8997 E Zygote  : v2
08-31 16:50:28.699  8997  8997 I libpersona: KNOX_SDCARD checking this for 1000
,08-31 16:50:28.699  8997  8997 I libpersona: KNOX_SDCARD not a persona
08-31 16:50:28.699  8997  8997 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,08-31 16:50:28.699  8997  8997 E Zygote  : accessInfo : 0
08-31 16:50:28.699  3381  4915 I ActivityManager: Start proc 8997:com.samsung.android.app.mirrorlink/1000 for broadcast-3 com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener
,08-31 16:50:28.699  8487  8996 W RequestHeader: java.lang.StringIndexOutOfBoundsException: length=0; regionStart=0; regionLength=3
,08-31 16:50:28.709  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-31 16:50:28.709  8487  8996 I DataManager: checkResolution
08-31 16:50:28.709  8487  8996 I DataManager: Create a DataManager
,08-31 16:50:28.719  8997  8997 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:50:28.719  8997  8997 D ActivityThread: Added TimaKeyStore provider
08-31 16:50:28.719  8487  8996 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-31 16:50:28.719  8487  8996 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-31 16:50:28.719  3152  3633 D EnterpriseController: netId is 0
08-31 16:50:28.719  3152  3633 D Netd    : getNetworkForDns: using netid 0 for uid 10111
,08-31 16:50:28.719  8487  8996 W NetworkServiceClient: Cannot get correct response, responseCode -1, URL: https://service.game-mode.net/gamemode/mode/value/package/?device_name=hero2lte&package_name=com.test.thalitest&installer_package_name=null&installed_time=1472655028720
,08-31 16:50:28.729  3381  4411 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f20a0cc u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e23e280 8997:com.samsung.android.app.mirrorlink/1000}
,08-31 16:50:28.729  3381  4057 I ActivityManager: Killing 7869:com.samsung.storyservice/5004 (adj 15): DHA:empty #33
,08-31 16:50:28.729  8997  8997 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,08-31 16:50:28.729  8997  8997 D RelationGraph: garbageCollect()
08-31 16:50:28.729  8997  8997 W ResourcesManager: getTopLevelResources: /system/app/MirrorLink/MirrorLink.apk / 1.0 running in com.samsung.android.app.mirrorlink rsrc of package com.samsung.android.app.mirrorlink
,08-31 16:50:28.739  3381  3975 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,08-31 16:50:28.739  8997  8997 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,08-31 16:50:28.739  8997  8997 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:28.739  8997  8997 I InjectionManager: Inside getClassLibPath caller 
,08-31 16:50:28.739  8997  8997 W System  : ClassLoader referenced unknown path: /system/app/MirrorLink/lib/arm
,08-31 16:50:28.749  3381  4419 D ActivityManager: isAutoRunBlockedApp:: com.samsung.storyservice, Auto Run ON
,08-31 16:50:28.769  8997  8997 D InjectionManager: InjectionManager
08-31 16:50:28.769  8997  8997 D InjectionManager: fillFeatureStoreMap com.samsung.android.app.mirrorlink
08-31 16:50:28.769  8997  8997 I InjectionManager: Constructor com.samsung.android.app.mirrorlink, Feature store :{}
08-31 16:50:28.769  8997  8997 I InjectionManager: featureStore :{}
,08-31 16:50:28.769  8997  8997 D AcmsPackageEventListener: action2:android.intent.action.PACKAGE_ADDED
08-31 16:50:28.769  8997  8997 D AcmsPackageEventListener: pkgName:com.test.thalitest ,10177
,08-31 16:50:28.769  3381  4057 I ActivityManager: Killing 8062:com.wssyncmldm/1000 (adj 15): DHA:empty #33
,08-31 16:50:28.779  3381  4057 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f20a0cc u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d26d28f 4814:com.microsoft.skydrive/u0a130}
,08-31 16:50:28.779  4814  4814 V ApplicationReceiver: 2016-08-31 14:50:28-null-Application install message is received ver:1.1.10
,08-31 16:50:28.779  4814  4814 V ApplicationReceiver: 2016-08-31 14:50:28-null-Installing:package:com.test.thalitest ver:1.1.10
,08-31 16:50:28.789  9011  9011 E Zygote  : v2
08-31 16:50:28.789  9011  9011 E Zygote  : isSdpEnabledProcess - SDP enabled
08-31 16:50:28.789  9011  9011 I libpersona: KNOX_SDCARD checking this for 10141
08-31 16:50:28.789  9011  9011 I libpersona: KNOX_SDCARD not a persona
08-31 16:50:28.789  9011  9011 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,08-31 16:50:28.789  9011  9011 E Zygote  : accessInfo : 64
08-31 16:50:28.789  9011  9011 E Zygote  : isSdpEnabledProcess - SDP enabled
08-31 16:50:28.789  9011  9011 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10141 / [uid]: 10141
08-31 16:50:28.789  9011  9011 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.sbrowser 
,08-31 16:50:28.799  3381  4181 I ActivityManager: Start proc 9011:com.sec.android.app.sbrowser/u0a141 for broadcast-3 com.sec.android.app.sbrowser/.preferences.ContentBlockerReceiver
,08-31 16:50:28.809  9011  9011 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:50:28.809  9011  9011 D ActivityThread: Added TimaKeyStore provider
,08-31 16:50:28.809  3381  4773 D ActivityManager: isAutoRunBlockedApp:: com.wssyncmldm, Auto Run ON
,08-31 16:50:28.829  3381  4304 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f20a0cc u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{34aa0b9 9011:com.sec.android.app.sbrowser/u0a141}
,08-31 16:50:28.829  9011  9011 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
08-31 16:50:28.829  9011  9011 D RelationGraph: garbageCollect()
,08-31 16:50:28.829  9011  9011 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package com.sec.android.app.sbrowser
,08-31 16:50:28.829  3381  4558 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
08-31 16:50:28.829  9011  9011 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,08-31 16:50:28.829  9011  9011 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:28.839  9011  9011 I InjectionManager: Inside getClassLibPath caller 
,08-31 16:50:28.839  9011  9011 W System  : ClassLoader referenced unknown path: /system/app/SBrowser_4_LATEST/lib/arm
,08-31 16:50:28.849  9011  9011 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package com.sec.android.app.sbrowser
,08-31 16:50:28.849  9011  9011 D ManifestProvider: onCreate()
,08-31 16:50:28.849  9011  9011 I SBrowserUtils: getSystemProperty of sales_code : XEO
,08-31 16:50:28.849  9011  9011 I SBrowserUtils: getSystemProperty of country_code : Poland
08-31 16:50:28.849  9011  9011 I SBrowserUtils: getSystemProperty of country_code : Poland
08-31 16:50:28.849  9011  9011 I SBrowserUtils: getSystemProperty of countryiso_code : PL
,08-31 16:50:28.859  9011  9011 V SBrowserContentProviderUtility: enableSyncClientProivder is called!
,08-31 16:50:28.859  9011  9011 D [MM]MHDataBaseProvider: onCreate()
,08-31 16:50:28.869  9011  9011 D ApplicationStatus: initialize application (com.sec.android.app.sbrowser.common.SBrowserMobileApplication@c6a05c0)
,08-31 16:50:28.869  9011  9011 D InjectionManager: InjectionManager
,08-31 16:50:28.869  9011  9011 D InjectionManager: fillFeatureStoreMap com.sec.android.app.sbrowser
08-31 16:50:28.869  9011  9011 I InjectionManager: Constructor com.sec.android.app.sbrowser, Feature store :{}
08-31 16:50:28.869  9011  9011 I InjectionManager: featureStore :{}
,08-31 16:50:28.879  3381  4771 I ActivityManager: Killing 8253:com.android.calendar/u0a144 (adj 15): DHA:empty #33
,08-31 16:50:28.879  3381  4771 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f20a0cc u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3124b8e 4991:com.sec.imsservice/1000}
,08-31 16:50:28.889  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-31 16:50:28.899  9026  9026 E Zygote  : v2
08-31 16:50:28.899  9026  9026 I libpersona: KNOX_SDCARD checking this for 10016
08-31 16:50:28.899  9026  9026 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
08-31 16:50:28.899  9026  9026 I libpersona: KNOX_SDCARD not a persona
,08-31 16:50:28.899  9026  9026 E Zygote  : accessInfo : 0
08-31 16:50:28.899  3381  4915 I ActivityManager: Start proc 9026:com.sec.android.app.samsungapps/u0a16 for broadcast-3 com.sec.android.app.samsungapps/.MyPackageReplacedReceiver
08-31 16:50:28.899  9026  9026 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.sec.android.app.samsungapps 
,08-31 16:50:28.909  9026  9026 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:50:28.909  9026  9026 D ActivityThread: Added TimaKeyStore provider
08-31 16:50:28.909  3381  4558 D ActivityManager: isAutoRunBlockedApp:: com.android.calendar, Auto Run ON
,08-31 16:50:28.929  3381  4428 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f20a0cc u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bd4fcfe 9026:com.sec.android.app.samsungapps/u0a16}
,08-31 16:50:28.929  9026  9026 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,08-31 16:50:28.929  9026  9026 D RelationGraph: garbageCollect()
,08-31 16:50:28.939  9026  9026 W ResourcesManager: getTopLevelResources: /data/app/com.sec.android.app.samsungapps-1/base.apk / 1.0 running in com.sec.android.app.samsungapps rsrc of package com.sec.android.app.samsungapps
,08-31 16:50:28.939  3381  4057 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
08-31 16:50:28.939  9026  9026 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,08-31 16:50:28.939  9026  9026 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:28.939  9026  9026 I InjectionManager: Inside getClassLibPath caller 
,08-31 16:50:28.949  9026  9026 W System  : ClassLoader referenced unknown path: /data/app/com.sec.android.app.samsungapps-1/lib/arm64
,08-31 16:50:28.989  9026  9026 D InjectionManager: InjectionManager
,08-31 16:50:28.989  9026  9026 D InjectionManager: fillFeatureStoreMap com.sec.android.app.samsungapps
08-31 16:50:28.989  9026  9026 I InjectionManager: Constructor com.sec.android.app.samsungapps, Feature store :{}
08-31 16:50:28.989  9026  9026 I InjectionManager: featureStore :{}
,08-31 16:50:28.999  9039  9039 E Zygote  : v2
,08-31 16:50:28.999  9039  9039 I libpersona: KNOX_SDCARD checking this for 10103
08-31 16:50:28.999  9039  9039 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
08-31 16:50:28.999  9039  9039 I libpersona: KNOX_SDCARD not a persona
08-31 16:50:28.999  9039  9039 E Zygote  : accessInfo : 0
,08-31 16:50:28.999  9039  9039 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.facebook.appmanager 
08-31 16:50:28.999  3381  4428 I ActivityManager: Start proc 9039:com.facebook.appmanager/u0a103 for broadcast-3 com.facebook.appmanager/com.facebook.oxygen.appmanager.common.packages.PackageReceiver
,08-31 16:50:29.009  3381  4428 I ActivityManager: Killing 8474:com.samsung.android.app.FileShareServer/5005 (adj 15): DHA:empty #33
,08-31 16:50:29.019  9039  9039 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:50:29.019  9039  9039 D ActivityThread: Added TimaKeyStore provider
,08-31 16:50:29.029  3381  5953 D SSRM:n  : SIOP:: AP = 410, PST = 418 (W:8), CP = 293, CUR = 22, LCD = 1
,08-31 16:50:29.029  3381  4179 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f20a0cc u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9394c5f 9039:com.facebook.appmanager/u0a103}
,08-31 16:50:29.029  3381  3975 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.FileShareServer, Auto Run ON
08-31 16:50:29.029  9039  9039 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
08-31 16:50:29.029  9039  9039 D RelationGraph: garbageCollect()
,08-31 16:50:29.029  9039  9039 W ResourcesManager: getTopLevelResources: /data/app/com.facebook.appmanager-1/base.apk / 1.0 running in com.facebook.appmanager rsrc of package com.facebook.appmanager
,08-31 16:50:29.029  3381  4558 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
08-31 16:50:29.029  9039  9039 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,08-31 16:50:29.039  9039  9039 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:29.039  9039  9039 I InjectionManager: Inside getClassLibPath caller 
,08-31 16:50:29.039  3381  5953 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,08-31 16:50:29.049  9039  9039 D ACRA    : ACRA init; reportURL: https://www.facebook.com/mobile/generic_android_crash_logs/659091980805095
,08-31 16:50:29.049  9039  9039 D ACRA    : ACRA is enabled for com.facebook.appmanager, intializing...
,08-31 16:50:29.049  9039  9039 V fb-UnpackingSoSource: locked dso store /data/user/0/com.facebook.appmanager/lib-main
,08-31 16:50:29.049  9039  9039 I fb-UnpackingSoSource: dso store is up-to-date: /data/user/0/com.facebook.appmanager/lib-main
08-31 16:50:29.049  9039  9039 V fb-UnpackingSoSource: releasing dso store lock for /data/user/0/com.facebook.appmanager/lib-main
,08-31 16:50:29.069  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-31 16:50:29.069  9039  9039 W com.facebook.appmanager:co: Verify
,08-31 16:50:29.069  9039  9039 D InjectionManager: InjectionManager
,08-31 16:50:29.069  9039  9039 D InjectionManager: fillFeatureStoreMap com.facebook.appmanager
08-31 16:50:29.069  9039  9039 I InjectionManager: Constructor com.facebook.appmanager, Feature store :{}
08-31 16:50:29.069  9039  9039 I InjectionManager: featureStore :{}
,08-31 16:50:29.079  3381  5953 D GameManagerService: identifyGamePackage. com.test.thalitest
,08-31 16:50:29.099  9055  9055 E Zygote  : v2
08-31 16:50:29.099  9055  9055 I libpersona: KNOX_SDCARD checking this for 10014
08-31 16:50:29.099  9055  9055 I libpersona: KNOX_SDCARD not a persona
08-31 16:50:29.099  9055  9055 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
08-31 16:50:29.099  4568  7015 I Icing   : Indexing 5C970AF099F6E45AC5F7CE88D00EDBB4B63BF8D6 from com.google.android.googlequicksearchbox
,08-31 16:50:29.099  9055  9055 E Zygote  : accessInfo : 0
08-31 16:50:29.099  9055  9055 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.facebook.system 
,08-31 16:50:29.109  3381  4915 I ActivityManager: Start proc 9055:com.facebook.system/u0a14 for broadcast-3 com.facebook.system/com.facebook.oxygen.installer.service.PackageReceiver
,08-31 16:50:29.119  9055  9055 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:50:29.119  9055  9055 D ActivityThread: Added TimaKeyStore provider
,08-31 16:50:29.129  3381  3974 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f20a0cc u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{66b8f75 9055:com.facebook.system/u0a14}
,08-31 16:50:29.129  9055  9055 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
08-31 16:50:29.129  9055  9055 D RelationGraph: garbageCollect()
,08-31 16:50:29.139  9055  9055 W ResourcesManager: getTopLevelResources: /data/app/com.facebook.system-1/base.apk / 1.0 running in com.facebook.system rsrc of package com.facebook.system
,08-31 16:50:29.139  3381  4411 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
08-31 16:50:29.139  9055  9055 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,08-31 16:50:29.139  9055  9055 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:29.139  9055  9055 I InjectionManager: Inside getClassLibPath caller 
,08-31 16:50:29.139  9055  9055 W System  : ClassLoader referenced unknown path: /data/app/com.facebook.system-1/lib/arm64
,08-31 16:50:29.149  9055  9055 D InjectionManager: InjectionManager
08-31 16:50:29.149  9055  9055 D InjectionManager: fillFeatureStoreMap com.facebook.system
,08-31 16:50:29.149  9055  9055 I InjectionManager: Constructor com.facebook.system, Feature store :{}
08-31 16:50:29.149  9055  9055 I InjectionManager: featureStore :{}
,08-31 16:50:29.149  3381  3461 D PackageManager: setEnabledSetting : userId = 0 packageName = com.facebook.appmanager cmp = com.facebook.oxygen.appmanager.crashmanager.CrashManagerActivity newState = 2 callingPackage = 10103
,08-31 16:50:29.159  3381  3460 D PackageManager: setEnabledSetting : userId = 0 packageName = com.facebook.appmanager cmp = com.facebook.oxygen.appmanager.firstparty.tos.ShouldShowTos newState = 2 callingPackage = 10103
,08-31 16:50:29.159  3381  4558 D PackageManager: setEnabledSetting : userId = 0 packageName = com.facebook.appmanager cmp = com.facebook.oxygen.appmanager.nekodirect.NekoDirectService newState = 2 callingPackage = 10103
,08-31 16:50:29.169  9075  9075 E Zygote  : v2
08-31 16:50:29.169  9075  9075 I libpersona: KNOX_SDCARD checking this for 10039
08-31 16:50:29.169  9075  9075 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
08-31 16:50:29.169  9075  9075 I libpersona: KNOX_SDCARD not a persona
,08-31 16:50:29.169  9075  9075 E Zygote  : accessInfo : 0
08-31 16:50:29.169  9075  9075 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.sec.android.app.shealth 
08-31 16:50:29.169  3381  4181 I ActivityManager: Start proc 9075:com.sec.android.app.shealth/u0a39 for broadcast-3 com.sec.android.app.shealth/com.samsung.android.app.shealth.serviceframework.partner.PluginBroadcastReceiver
,08-31 16:50:29.169  3381  4773 D PackageManager: setEnabledSetting : userId = 0 packageName = com.facebook.appmanager cmp = com.facebook.oxygen.appmanager.nekodirect.progress.ProgressContentProvider newState = 2 callingPackage = 10103
,08-31 16:50:29.169  3381  4181 I ActivityManager: Killing 8500:com.sec.android.service.health/u0a26 (adj 15): DHA:empty #33
,08-31 16:50:29.179  9039  9071 E ActivityThread: Failed to find provider info for com.facebook.appmanager.oxygen.nekodirect.progress
,08-31 16:50:29.189  9075  9075 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:50:29.189  9075  9075 D ActivityThread: Added TimaKeyStore provider
,08-31 16:50:29.189  3381  4771 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.service.health, Auto Run ON
,08-31 16:50:29.199  4568  7015 I Icing   : Indexing done 5C970AF099F6E45AC5F7CE88D00EDBB4B63BF8D6
,08-31 16:50:29.199  3381  3851 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{539add6 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{60a6857 9075:com.sec.android.app.shealth/u0a39}
,08-31 16:50:29.209  9075  9075 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
08-31 16:50:29.209  9075  9075 D RelationGraph: garbageCollect()
,08-31 16:50:29.209  3381  4419 I ActivityManager: Killing 8512:com.samsung.android.app.watchmanagerstub/u0a112 (adj 15): DHA:empty #33
,08-31 16:50:29.219  9075  9075 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.sec.android.app.shealth rsrc of package com.sec.android.app.shealth
,08-31 16:50:29.219  3381  4428 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
08-31 16:50:29.219  9075  9075 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,08-31 16:50:29.219  9075  9075 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:29.229  9075  9075 I InjectionManager: Inside getClassLibPath caller 
,08-31 16:50:29.239  9075  9075 W System  : ClassLoader referenced unknown path: /system/priv-app/SHealth4/lib/arm64
,08-31 16:50:29.239  3381  4419 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.watchmanagerstub, Auto Run ON
,08-31 16:50:29.239  9075  9075 I MultiDex: VM with version 2.1.0 has multidex support
08-31 16:50:29.239  9075  9075 I MultiDex: install
08-31 16:50:29.239  9075  9075 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-31 16:50:29.239  9075  9075 I MultiDex: install
08-31 16:50:29.239  9075  9075 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-31 16:50:29.239  9075  9075 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.sec.android.app.shealth rsrc of package com.sec.android.app.shealth
,08-31 16:50:29.249  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-31 16:50:29.279  9075  9075 D InjectionManager: InjectionManager
08-31 16:50:29.279  9075  9075 D InjectionManager: fillFeatureStoreMap com.sec.android.app.shealth
08-31 16:50:29.279  9075  9075 I InjectionManager: Constructor com.sec.android.app.shealth, Feature store :{}
08-31 16:50:29.279  9075  9075 I InjectionManager: featureStore :{}
,08-31 16:50:29.279  9075  9075 D HealthDataStore: Service for HealthDataStore is connected
,08-31 16:50:29.289  9075  9075 D HealthDataStore: HealthConnectionErrorResult code : 9
,08-31 16:50:29.289  3381  4773 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{539add6 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6284b71 8433:com.sec.android.app.shealth:remote/u0a39}
,08-31 16:50:29.299  9075  9075 D HealthConsole: Service for HealthDataConsole is connected
,08-31 16:50:29.299  9075  9075 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
,08-31 16:50:29.299  9075  9075 E HealthDataStore: disconnectService: Context instance is invalid
,08-31 16:50:29.309  3381  4558 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{539add6 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6284b71 8433:com.sec.android.app.shealth:remote/u0a39}
,08-31 16:50:29.319  3381  4181 I ActivityManager: Killing 7711:com.samsung.android.coreapps/5011 (adj 15): DHA:empty #33
,08-31 16:50:29.329  3381  4181 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1740b4f u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4ead505 4977:com.samsung.android.providers.context/u0a9}
,08-31 16:50:29.339  3381  4773 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7f512dc u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4ead505 4977:com.samsung.android.providers.context/u0a9}
,08-31 16:50:29.349  3381  4411 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.coreapps, Auto Run ON
,08-31 16:50:29.429  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-31 16:50:29.609  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-31 16:50:29.789  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-31 16:50:29.969  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-31 16:50:30.149  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-31 16:50:30.329  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-31 16:50:30.509  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-31 16:50:30.689  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-31 16:50:30.869  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-31 16:50:31.049  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-31 16:50:31.179  3152  3633 D EnterpriseController: netId is 0
08-31 16:50:31.179  3152  3633 D Netd    : getNetworkForDns: using netid 0 for uid 10002
,08-31 16:50:31.179  4585  4747 E         : Error communicating to API: https://prod.yana.asideas.de/api/v2/categories,
08-31 16:50:31.179  4585  4747 E         : retrofit.RetrofitError: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
08-31 16:50:31.179  4585  4747 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:395)
08-31 16:50:31.179  4585  4747 E         : 	at retrofit.RestAdapter$RestHandler.access$100(RestAdapter.java:220)
08-31 16:50:31.179  4585  4747 E         : 	at retrofit.RestAdapter$RestHandler$1.invoke(RestAdapter.java:265)
08-31 16:50:31.179  4585  4747 E         : 	at retrofit.RxSupport$2.run(RxSupport.java:55)
08-31 16:50:31.179  4585  4747 E         : 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-31 16:50:31.179  4585  4747 E         : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-31 16:50:31.179  4585  4747 E         : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-31 16:50:31.179  4585  4747 E         : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-31 16:50:31.179  4585  4747 E         : 	at retrofit.Platform$Android$2$1.run(Platform.java:142)
08-31 16:50:31.179  4585  4747 E         : 	at java.lang.Thread.run(Thread.java:818)
08-31 16:50:31.179  4585  4747 E         : Caused by: java.net.UnknownHostException: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
08-31 16:50:31.179  4585  4747 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:470)
08-31 16:50:31.179  4585  4747 E         : 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
08-31 16:50:31.179  4585  4747 E         : 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
08-31 16:50:31.179  4585  4747 E         : 	at com.squareup.okhttp.internal.Network$1.resolveInetAddresses(Network.java:29)
08-31 16:50:31.179  4585  4747 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:187)
08-31 16:50:31.179  4585  4747 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.nextProxy(RouteSelector.java:156)
08-31 16:50:31.179  4585  4747 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.next(RouteSelector.java:98)
08-31 16:50:31.179  4585  4747 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.createNextConnection(HttpEngine.java:344)
08-31 16:50:31.179  4585  4747 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:327)
08-31 16:50:31.179  4585  4747 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:245)
08-31 16:50:31.179  4585  4747 E         : 	at com.squareup.okhttp.Call.getResponse(Call.java:267)
08-31 16:50:31.179  4585  4747 E         : 	at com.squareup.okhttp.Call$ApplicationInterceptorChain.proceed(Call.java:224)
08-31 16:50:31.179  4585  4747 E         : 	at com.squareup.okhttp.Call.getResponseWithInterceptorChain(Call.java:195)
08-31 16:50:31.179  4585  4747 E         : 	at com.squareup.okhttp.Call.execute(Call.java:79)
08-31 16:50:31.179  4585  4747 E         : 	at retrofit.client.OkClient.execute(OkClient.java:53)
08-31 16:50:31.179  4585  4747 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:326)
08-31 16:50:31.179  4585  4747 E         : 	... 9 more
08-31 16:50:31.179  4585  4747 E         : Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
08-31 16:50:31.179  4585  4747 E         : 	at libcore.io.Posix.android_getaddrinfo(Native Method)
08-31 16:50:31.179  4585  4747 E         : 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
08-31 16:50:31.179  4585  4747 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:451)
08-31 16:50:31.179  4585  4747 E         : 	... 24 more
08-31 16:50:31.179  4585  4747 E         : 
,08-31 16:50:31.229  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-31 16:50:31.409  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-31 16:50:31.589  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-31 16:50:31.679  8794  8801 I eN66    : JNI Enter Function Java_com_asr_pocketsphinx_pocketsphinxJNI_delete_1Config
08-31 16:50:31.679  8794  8801 I eN66    : JNI Exit Function Java_com_asr_pocketsphinx_pocketsphinxJNI_delete_1Config
,08-31 16:50:31.769  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-31 16:50:31.949  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-31 16:50:32.039  3381  4411 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-31 16:50:32.039  3381  4411 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4325, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
08-31 16:50:32.039  3381  4411 D BatteryService: online:4, current avg:-150, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-231
08-31 16:50:32.039  3381  4411 D BatteryService: stay LED for fully charged
08-31 16:50:32.039  3381  3381 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-31 16:50:32.039  3381  3381 I MotionRecognitionService: Plugged
08-31 16:50:32.039  3381  3381 D MotionRecognitionService:   cableConnection= 1
08-31 16:50:32.039  3381  3381 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-31 16:50:32.039  3381  3381 D MotionRecognitionService: skip setTransmitPower. 
,08-31 16:50:32.049  3946  3946 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-31 16:50:32.049  3946  3946 D PowerUI : priorPlugType = 2 mPlugType =  2
08-31 16:50:32.049  3946  3946 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-31 16:50:32.059  4991  4991 D CommonServiceConfiguration: getStringValueSetting
,08-31 16:50:32.059  8822  8829 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+user+0+com_samsung_svoice_sync+databases+svoicelocal_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,08-31 16:50:32.059  4991  4991 D BatteryMonitor: new battery level: 100
,08-31 16:50:32.069  4730  4730 D BatteryController: saveBatteryData : level[100], status[5]
,08-31 16:50:32.069  3946  3946 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-31 16:50:32.069  3946  3946 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-31 16:50:32.129  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-31 16:50:32.159  3381  5953 D N       : limitCPUFreq:: freq = 2496000
08-31 16:50:32.159  3381  5953 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MAX_LIMIT  frequency : 2496000  uid : 1000  pid : 3381  pkgName : SIOP_ARM_MAX@22
,08-31 16:50:32.169  3381  5953 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,08-31 16:50:32.309  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-31 16:50:32.489  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-31 16:50:32.599  3381  5990 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-31 16:50:32.669  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-31 16:50:32.849  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-31 16:50:33.029  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-31 16:50:33.209  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-31 16:50:33.389  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-31 16:50:33.569  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-31 16:50:33.749  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-31 16:50:33.929  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-31 16:50:34.109  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-31 16:50:34.189  3152  3633 D EnterpriseController: netId is 0
08-31 16:50:34.189  3152  3633 D Netd    : getNetworkForDns: using netid 0 for uid 10002
,08-31 16:50:34.189  4585  4747 E         : Error communicating to API: https://prod.yana.asideas.de/api/v2/categories
08-31 16:50:34.189  4585  4747 E         : retrofit.RetrofitError: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
08-31 16:50:34.189  4585  4747 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:395)
08-31 16:50:34.189  4585  4747 E         : 	at retrofit.RestAdapter$RestHandler.access$100(RestAdapter.java:220)
08-31 16:50:34.189  4585  4747 E         : 	at retrofit.RestAdapter$RestHandler$1.invoke(RestAdapter.java:265)
08-31 16:50:34.189  4585  4747 E         : 	at retrofit.RxSupport$2.run(RxSupport.java:55)
08-31 16:50:34.189  4585  4747 E         : 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-31 16:50:34.189  4585  4747 E         : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-31 16:50:34.189  4585  4747 E         : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-31 16:50:34.189  4585  4747 E         : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-31 16:50:34.189  4585  4747 E         : 	at retrofit.Platform$Android$2$1.run(Platform.java:142)
08-31 16:50:34.189  4585  4747 E         : 	at java.lang.Thread.run(Thread.java:818)
08-31 16:50:34.189  4585  4747 E         : Caused by: java.net.UnknownHostException: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
08-31 16:50:34.189  4585  4747 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:470)
08-31 16:50:34.189  4585  4747 E         : 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
08-31 16:50:34.189  4585  4747 E         : 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
08-31 16:50:34.189  4585  4747 E         : 	at com.squareup.okhttp.internal.Network$1.resolveInetAddresses(Network.java:29)
08-31 16:50:34.189  4585  4747 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:187)
08-31 16:50:34.189  4585  4747 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.nextProxy(RouteSelector.java:156)
08-31 16:50:34.189  4585  4747 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.next(RouteSelector.java:98)
08-31 16:50:34.189  4585  4747 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.createNextConnection(HttpEngine.java:344)
08-31 16:50:34.189  4585  4747 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:327)
08-31 16:50:34.189  4585  4747 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:245)
08-31 16:50:34.189  4585  4747 E         : 	at com.squareup.okhttp.Call.getResponse(Call.java:267)
08-31 16:50:34.189  4585  4747 E         : 	at com.squareup.okhttp.Call$ApplicationInterceptorChain.proceed(Call.java:224)
08-31 16:50:34.189  4585  4747 E         : 	at com.squareup.okhttp.Call.getResponseWithInterceptorChain(Call.java:195)
08-31 16:50:34.189  4585  4747 E         : 	at com.squareup.okhttp.Call.execute(Call.java:79)
08-31 16:50:34.189  4585  4747 E         : 	at retrofit.client.OkClient.execute(OkClient.java:53)
08-31 16:50:34.189  4585  4747 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:326)
08-31 16:50:34.189  4585  4747 E         : 	... 9 more
08-31 16:50:34.189  4585  4747 E         : Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
08-31 16:50:34.189  4585  4747 E         : 	at libcore.io.Posix.android_getaddrinfo(Native Method)
08-31 16:50:34.189  4585  4747 E         : 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
08-31 16:50:34.189  4585  4747 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:451)
08-31 16:50:34.189  4585  4747 E         : 	... 24 more
08-31 16:50:34.189  4585  4747 E         : 
,08-31 16:50:34.259  6020  6020 D FactoryTest: User mode
,08-31 16:50:34.259  6020  6020 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
08-31 16:50:34.259  6020  6020 D MTPRx   : still no open session command from host, so toast
,08-31 16:50:34.269  3381  3851 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
08-31 16:50:34.269  3381  3851 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package com.samsung.android.MtpApplication
,08-31 16:50:34.269  3381  3851 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:34.269  3381  3851 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
,08-31 16:50:34.269  3381  3851 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.samsung.android.MtpApplication)
,08-31 16:50:34.269  3381  3851 D ActivityManager: mDVFSHelper.acquire()
,08-31 16:50:34.279  3381  3851 V WindowManager: addAppToken: AppWindowToken{d06900d6b token=Token{bf12aba ActivityRecord{1403fe5 u0 com.samsung.android.MtpApplication/.USBConnection t38}}} to stack=2 task=38 at 0
,08-31 16:50:34.279  3381  3851 D ActivityManager:  Launching com.samsung.android.MtpApplication, updated priority
,08-31 16:50:34.289  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-31 16:50:34.289  3381  3381 D GameManagerService: NotifyRunnable. pkg: com.samsung.android.MtpApplication, type: 4, isMinimized: false, isTunableApp: false
,08-31 16:50:34.289  5674  5684 I TrayUsageStatesWatcher: noteResumeComponent : ComponentInfo{com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection} Intent { flg=0x10800000 cmp=com.samsung.android.MtpApplication/.USBConnection VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
08-31 16:50:34.289  3381  3523 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
,08-31 16:50:34.299  5674  5685 I TrayUsageStatesWatcher: notePauseComponent : ComponentInfo{com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}
,08-31 16:50:34.309  3381  3851 D InputDispatcher: Focused application set to: xxxx
,08-31 16:50:34.309  6020  6020 E MTPRx   : started activity for popup
,08-31 16:50:34.309  6020  6020 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package com.samsung.android.MtpApplication
08-31 16:50:34.309  6020  6020 D RelationGraph: garbageCollect()
,08-31 16:50:34.309  3381  5953 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
,08-31 16:50:34.309  3381  5953 D N       : limitCPUFreq:: freq = -1
08-31 16:50:34.309  3381  5953 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MAX_LIMIT  frequency : 2496000  uid : 1000  pid : 3381  tag : SIOP_ARM_MAX@22
,08-31 16:50:34.309  6020  6020 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package com.samsung.android.MtpApplication
,08-31 16:50:34.319  3381  5953 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,08-31 16:50:34.319  3381  5953 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
,08-31 16:50:34.329  3381  5953 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,08-31 16:50:34.329  3381  5953 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
,08-31 16:50:34.329  3381  5953 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
,08-31 16:50:34.329  6020  6020 D MTPUSBConnection: onCreate in USBConnection
,08-31 16:50:34.329  6020  6020 V MTPUSBConnection: Registering broadcast receiver.
,08-31 16:50:34.329  6020  6020 E MTPUSBConnection: AlertDialog Mode is : TIMEOUT
,08-31 16:50:34.339  3381  3851 D SecContentProvider2: query(), uri = 14 selection = getSealedState
,08-31 16:50:34.339  8726  8877 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-31 16:50:34.339  8726  8877 I jxcore-log: 
,08-31 16:50:34.339  8726  8877 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-31 16:50:34.339  8726  8877 I jxcore-log: 
,08-31 16:50:34.339  8726  8877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 16:50:34.339  8726  8877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 16:50:34.339  8726  8877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 16:50:34.339  8726  8877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-31 16:50:34.339  8726  8877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 16:50:34.339  8726  8877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 16:50:34.339  8726  8877 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 16:50:34.339  8726  8877 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 16:50:34.339  8726  8877 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 16:50:34.339  8726  8877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 16:50:34.339  8726  8877 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 16:50:34.339  8726  8877 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-31 16:50:34.339  8726  8877 I jxcore-log: 
,08-31 16:50:34.339  8726  8877 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-31 16:50:34.339  8726  8877 I jxcore-log: 
,08-31 16:50:34.389  6020  6020 D TAG     : dev.kiessupport is : TRUE
,08-31 16:50:34.409  6020  6020 D SecWifiDisplayUtil: Metadata value : SecSettings2
,08-31 16:50:34.409  6020  6020 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{ec8116 V.E...... R.....I. 0,0-0,0}
,08-31 16:50:34.409  3381  4773 W WindowManager: Failed looking up window
08-31 16:50:34.409  3381  4773 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@3fe5712 does not exist
08-31 16:50:34.409  3381  4773 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
08-31 16:50:34.409  3381  4773 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
08-31 16:50:34.409  3381  4773 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
08-31 16:50:34.409  3381  4773 W WindowManager: 	at android.view.IWindowSession$Stub.onTransact(IWindowSession.java:688)
08-31 16:50:34.409  3381  4773 W WindowManager: 	at com.android.server.wm.Session.onTransact(Session.java:139)
08-31 16:50:34.409  3381  4773 W WindowManager: 	at android.os.Binder.execTransact(Binder.java:453)
,08-31 16:50:34.409  3381  4411 D ISSUE_DEBUG: InputChannelName : bbebee3 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
,08-31 16:50:34.409  6020  6020 D Activity: performCreate Call Injection manager
,08-31 16:50:34.419  6020  6020 I InjectionManager: dispatchOnViewCreated > Target : com.samsung.android.MtpApplication.USBConnection isFragment :false
,08-31 16:50:34.419  6020  6020 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{cb40a69 I.E...... R.....I. 0,0-0,0}
,08-31 16:50:34.419  3381  4428 W WindowManager: Failed looking up window
08-31 16:50:34.419  3381  4428 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@4f2a0e0 does not exist
08-31 16:50:34.419  3381  4428 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
08-31 16:50:34.419  3381  4428 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
08-31 16:50:34.419  3381  4428 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
08-31 16:50:34.419  3381  4428 W WindowManager: 	at android.view.IWindowSession$Stub.onTransact(IWindowSession.java:688)
08-31 16:50:34.419  3381  4428 W WindowManager: 	at com.android.server.wm.Session.onTransact(Session.java:139)
08-31 16:50:34.419  3381  4428 W WindowManager: 	at android.os.Binder.execTransact(Binder.java:453)
,08-31 16:50:34.419  3381  4915 D ISSUE_DEBUG: InputChannelName : 592ef99 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
,08-31 16:50:34.419  3381  4181 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
,08-31 16:50:34.419  3381  4181 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-31 16:50:34.419  3381  3381 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-31 16:50:34.429  3381  3381 I KnoxTimeoutHandler: Shared devices show user statefalse
,08-31 16:50:34.429  3381  3381 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,08-31 16:50:34.439  3009  3009 I SurfaceFlinger: id=19 createSurf (193x193),1 flag=4, VSBConnecti
,08-31 16:50:34.449  3381  4558 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3381
,08-31 16:50:34.449  3381  4558 I libsuspend: !@autosuspend_wakeup_count_disable
08-31 16:50:34.449  3381  4558 D PowerManagerService: mDisplayReady: false
08-31 16:50:34.449  3381  4558 I libsuspend: !@autosuspend_wakeup_count_disable done
08-31 16:50:34.449  3381  3568 D DisplayPowerController: animateScreenStateChange[0]: target=3
08-31 16:50:34.449  3381  3568 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
,08-31 16:50:34.449  3009  3009 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7f80383c00
08-31 16:50:34.449  3381  4558 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
,08-31 16:50:34.449  3009  3009 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
08-31 16:50:34.449  3381  3568 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
08-31 16:50:34.449  3381  3568 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
08-31 16:50:34.449  3381  3578 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
08-31 16:50:34.449  3381  3562 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
,08-31 16:50:34.449  3381  3562 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
,08-31 16:50:34.449  3009  3009 I SurfaceFlinger: id=20 createSurf (257x257),1 flag=4, VSBConnecti
,08-31 16:50:34.459  3381  3568 D DisplayPowerController: animateScreenStateChange[0]: target=3
08-31 16:50:34.459  3381  3568 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
08-31 16:50:34.459  3381  3568 I libsuspend: !@autosuspend_wakeup_count_enable
,08-31 16:50:34.459  3381  3568 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
,08-31 16:50:34.459  3381  3568 I libsuspend: !@autosuspend_wakeup_count_enable done
08-31 16:50:34.459  3381  3568 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
08-31 16:50:34.459  3381  3568 D DisplayPowerController: animateScreenStateChange[0]: target=3
08-31 16:50:34.469  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
08-31 16:50:34.459  3381  3568 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
,08-31 16:50:34.459  3381  3568 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
08-31 16:50:34.459  3381  3568 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
08-31 16:50:34.459  3381  3568 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
08-31 16:50:34.459  3381  3568 D PowerManagerService: mDisplayReady: true
08-31 16:50:34.459  3381  3568 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,08-31 16:50:34.469  5674  5674 E CocktailBarPositionManager: Window direction: 0
08-31 16:50:34.469  5674  5674 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,08-31 16:50:34.499  3381  4411 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3381
,08-31 16:50:34.499  6020  6020 V ActivityThread: updateVisibility : ActivityRecord{f39a01c token=android.os.BinderProxy@9a1681e {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : true
,08-31 16:50:34.539  3381  4773 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3381
,08-31 16:50:34.549  3381  4428 V WindowStateAnimator: Finishing drawing window Window{bbebee3 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-31 16:50:34.549  3381  4057 V WindowStateAnimator: Finishing drawing window Window{592ef99 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-31 16:50:34.549  6020  6020 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,08-31 16:50:34.559  3381  3878 D MdnieScenarioControlService:  packageName : com.samsung.android.MtpApplication    className : com.samsung.android.MtpApplication.USBConnection
,08-31 16:50:34.559  3009  3009 D libEGL  : eglInitialize EGLDisplay = 0x7fe84f8be8
,08-31 16:50:34.559  3381  4558 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3381
,08-31 16:50:34.559  3009  3009 D libEGL  : eglInitialize EGLDisplay = 0x7fe84f8be8
08-31 16:50:34.559  3381  3562 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-31 16:50:34.559  3381  3381 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-31 16:50:34.559  3381  3562 I ActivityManager: Displayed com.samsung.android.MtpApplication/.USBConnection: +260ms (total +286ms)
,08-31 16:50:34.559  3381  3562 D ActivityManager: mDVFSHelper.release()
,08-31 16:50:34.559  3381  3562 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1403fe5 u0 com.samsung.android.MtpApplication/.USBConnection t38} time:85347
,08-31 16:50:34.559  3381  3381 I KnoxTimeoutHandler: SD activityfalse
,08-31 16:50:34.559  6020  6020 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,08-31 16:50:34.569  3381  3461 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3381
,08-31 16:50:34.589  5674  5674 I TrayVisibilityController: handleMessage : msg.what = 1
,08-31 16:50:34.589  5674  5674 I Utils   : isCurrentUser current = 0, ownerId = 0
,08-31 16:50:34.589  5674  5674 I TrayVisibilityController: getComputedTrayVisible : keyguardState = 3
08-31 16:50:34.589  5674  5674 I TrayVisibilityController: updateTrayVisible : State : 3 visible = 2 mCurrentVisible = 2
,08-31 16:50:34.609  3009  3009 D libEGL  : eglInitialize EGLDisplay = 0x7fe84f8be8
,08-31 16:50:34.609  3381  4304 V WindowStateAnimator: Finishing drawing window Window{bbebee3 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
,08-31 16:50:34.609  3381  4057 V WindowStateAnimator: Finishing drawing window Window{592ef99 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
,08-31 16:50:34.609  6020  6020 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@9a1681e time:85394
,08-31 16:50:34.629  8726  8877 I jxcore-log: Running unit tests
08-31 16:50:34.629  8726  8877 I jxcore-log: 
,08-31 16:50:34.629  8726  8877 E JX-Cordova: JavaCall recevied a call for unknown method ExecuteNativeTests
08-31 16:50:34.629  8726  8877 I jxcore-log: Failed to execute UT.
08-31 16:50:34.629  8726  8877 I jxcore-log: 
,08-31 16:50:34.629  8726  8877 I jxcore-log: Unit Test app is loaded
08-31 16:50:34.629  8726  8877 I jxcore-log: 
,08-31 16:50:34.629  8726  8877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 16:50:34.629  8726  8877 I jxcore-log: 
,08-31 16:50:34.639  8726  8877 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,08-31 16:50:34.639  3381  4411 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,08-31 16:50:34.639  8726  8726 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-31 16:50:34.639  3381  4411 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,08-31 16:50:34.639  3381  4411 E SContext.CaeProvider: setAttribute() : attribute is null!
,08-31 16:50:34.649  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-31 16:50:34.649  3381  4411 W CAE     : registerCallback(ContextAwareService.java:144) - [regi 01] Mutex is locked for ACTIVITY_TRACKER
,08-31 16:50:34.649  3381  4411 V CAE     : start(ContextProvider.java:128)
,08-31 16:50:34.649  3381  4411 V CAE     : clear(ActivityTrackerRunner.java:108)
,08-31 16:50:34.649  3381  4411 V CAE     : enable(ActivityTrackerRunner.java:84)
,08-31 16:50:34.649  3381  4411 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -79, 26, 0, 0, 0, 0, 0, 0, 0, 0, 14, 50, 34,
,08-31 16:50:34.649  3381  4411 D SensorHubManager: SendSensorHubData: send data = -79, 26, 0, 0, 0, 0, 0, 0, 0, 0, 14, 50, 34
,08-31 16:50:34.649  3167  3210 D Sensorhubs: sendContextData: -79, 26, 0, 0, 0, 0, 0, 0, 0, 0, 14, 50, 34
,08-31 16:50:34.659  3381  4411 D CAE     : getFaultDetectionResult(ActivityTrackerRunner.java:154) - true
,08-31 16:50:34.659  3381  4411 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,08-31 16:50:34.659  3381  3878 I MdnieScenarioControlService: mGameModeLauncher : false
08-31 16:50:34.659  3381  3878 I MdnieScenarioControlService: setUIMode
,08-31 16:50:34.669  3381  4411 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
,08-31 16:50:34.669  3381  4411 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 1, serviceCount = 1, subCollectionCount = 0
,08-31 16:50:34.669  3381  4411 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
08-31 16:50:34.669  3381  4411 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@fc991c5, Service : DEVICE_PHYSICAL_CONTEXT_MONITOR(1)
,08-31 16:50:34.669  3381  4411 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@de6d25e, Service : ACTIVITY_TRACKER(1)
08-31 16:50:34.669  3381  4411 W CAE     : registerCallback(ContextAwareService.java:180) - [regi 02] Mutex is unlocked for ACTIVITY_TRACKER
08-31 16:50:34.669  3381  4411 D SContextService: 	.registerCallback : 2, client=
08-31 16:50:34.669  3381  4411 D SContextService: ===== SContext Service List =====
08-31 16:50:34.669  3381  4411 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@203d827, Service : Device Physical Context Monitor
08-31 16:50:34.669  3381  4411 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@d90eb0c, Service : Activity Tracker
08-31 16:50:34.669  3381  4411 D SContextManager:   .registerListener : listener = com.android.server.wifi.WifiServiceImpl$11@214663f, service=Activity Tracker
,08-31 16:50:34.669  3381  4411 W CAE     : getContextInfo(ContextAwareService.java:457) - [getContext 01] Mutex is locked for ACTIVITY_TRACKER_CURRENT_INFO
,08-31 16:50:34.679  3381  4411 V CAE     : enable(ActivityTrackerCurrentInfoRunner.java:178)
,08-31 16:50:34.679  3381  4411 V CAE     : clear(ActivityTrackerCurrentInfoRunner.java:202)
08-31 16:50:34.679  3381  4411 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -72, 26, 1, 0,
08-31 16:50:34.679  3381  4411 D SensorHubManager: SendSensorHubData: send data = -72, 26, 1, 0
,08-31 16:50:34.679  3167  3167 D Sensorhubs: sendContextData: -72, 26, 1, 0
,08-31 16:50:34.679  3381  4411 D CAE     : getFaultDetectionResult(ActivityTrackerCurrentInfoRunner.java:214) - true
,08-31 16:50:34.679  3381  4411 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,08-31 16:50:34.689  3381  4411 W CAE     : getContextInfo(ContextAwareService.java:511) - [getContext 02] Mutex is unlocked for ACTIVITY_TRACKER_CURRENT_INFO
,08-31 16:50:34.689  3381  4411 D SContextService: requestToUpdate() : service = Activity Tracker
08-31 16:50:34.689  3381  4411 D WifiService: Wi-Fi on and Screen on , checkSensorStatus !!
08-31 16:50:34.689  3381  4411 D SContextManager:   .requestToUpdate : listener = com.android.server.wifi.WifiServiceImpl$11@214663f, service=Activity Tracker
08-31 16:50:34.689  3381  4411 D WifiService: setWifiEnabled: true pid=8726, uid=10177
08-31 16:50:34.699  3381  4411 W ActivityManager: Permission Denial: getCurrentUser() from pid=8726, uid=10177 requires android.permission.INTERACT_ACROSS_USERS
,08-31 16:50:34.699  3381  4411 W WifiService: Failed getting userId using ActivityManagerNative
08-31 16:50:34.699  3381  4411 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=8726, uid=10177 requires android.permission.INTERACT_ACROSS_USERS
08-31 16:50:34.699  3381  4411 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28247)
08-31 16:50:34.699  3381  4411 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
08-31 16:50:34.699  3381  4411 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
08-31 16:50:34.699  3381  4411 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
08-31 16:50:34.699  3381  4411 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
08-31 16:50:34.699  3381  3856 D WifiBigDataLog: getJsonFormat() - feature : ONOF
08-31 16:50:34.699  3381  4411 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
,08-31 16:50:34.699  3381  4411 D SettingsProvider: isChangeAllowed() : name = wifi_on
,08-31 16:50:34.699  3381  3859 D WifiController: [FCC]setFccChannel() is called !!!
08-31 16:50:34.699  3381  3859 D WifiStateMachine: setFccChannel: channel = 0
,08-31 16:50:34.699  3381  3859 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
08-31 16:50:34.699  3381  3859 D SecContentProvider: insert(), uri = 2
,08-31 16:50:34.699  3381  3856 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
08-31 16:50:34.699  3381  4771 I WifiService: disconnect: pid=8726, uid=10177
,08-31 16:50:34.699  3381  3856 D WifiBigDataLog: init : 
,08-31 16:50:34.699  3381  3856 E WifiHW  : ##################### set firmware type 0 #####################
08-31 16:50:34.699  8726  8877 D BluetoothAdapter: enable()
08-31 16:50:34.709  3152  3637 I WifiHW  : wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
08-31 16:50:34.709  3167  3209 D Sensorhubs: readContextData: 1, 1, 26, 1, 3, 47, 87, 99, 1, 1
,08-31 16:50:34.709  3381  3817 D SensorHubManager: onGetSensorHubDataLocked: library(10) = 1, 1, 26, 1, 3, 47, 87, 99, 1, 1
08-31 16:50:34.709  3152  3637 I WifiHW  : module is semco
08-31 16:50:34.709  3381  3381 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3381 (0x0)
08-31 16:50:34.709  3152  3637 E WifiHW  : ==========[WIFI] SEMCO MODULE ===========
08-31 16:50:34.709  3381  3523 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{599ec55 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4ead505 4977:com.samsung.android.providers.context/u0a9}
08-31 16:50:34.709  3152  3637 I WifiHW  : wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
08-31 16:50:34.709  3152  3637 E WifiHW  : TEMP_FAILURE_RETRY complete
08-31 16:50:34.709  3152  3637 D SoftapController: Softap fwReload - Ok
08-31 16:50:34.709  3381  3816 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 14, 14, 50, 34,
,08-31 16:50:34.709  3381  3816 D SensorHubManager: SendSensorHubData: send data = -63, 14, 14, 50, 34
08-31 16:50:34.709  3167  3210 D Sensorhubs: sendContextData: -63, 14, 14, 50, 34
08-31 16:50:34.709  3152  3637 D CommandListener: Setting iface cfg
08-31 16:50:34.709  3152  3637 D CommandListener: Trying to bring down wlan0
,08-31 16:50:34.719  3152  3637 D CommandListener: Clearing all IP addresses on wlan0
08-31 16:50:34.719  3381  3381 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3381 (0x0)
08-31 16:50:34.719  3381  3816 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :10], AP_SLEEP
08-31 16:50:34.719  3381  3381 D PowerManagerService: mDisplayReady: false
08-31 16:50:34.719  3381  3381 I libsuspend: !@autosuspend_wakeup_count_disable
08-31 16:50:34.719  3381  3381 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
08-31 16:50:34.719  3381  3381 I libsuspend: !@autosuspend_wakeup_count_disable done
08-31 16:50:34.719  3381  3568 D DisplayPowerController: animateScreenStateChange[0]: target=4
08-31 16:50:34.719  3381  3816 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 10
08-31 16:50:34.719  3381  3568 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
08-31 16:50:34.719  3381  3816 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 26, 1, 3, 47, 87, 99, 1, 1,
08-31 16:50:34.719  3381  3568 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
08-31 16:50:34.719  3381  3816 D CAE     : display(ContextProvider.java:375) - ================= ACTIVITY_TRACKER =================
08-31 16:50:34.719  3381  3568 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
08-31 16:50:34.719  3009  3009 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7f80383c00
08-31 16:50:34.719  3381  3578 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
08-31 16:50:34.719  3009  3009 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
08-31 16:50:34.719  3381  3562 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
08-31 16:50:34.719  3381  3816 I CAE     : display(ContextProvider.java:391) - Accuracy=[1], OperationMode=[0], ActivityType=[1], TimeStamp=[1472655034211]
08-31 16:50:34.719  3381  3562 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
,08-31 16:50:34.719  3381  3819 D SContextService: updateSContext() : event = Activity Tracker
08-31 16:50:34.719  3381  3381 D WifiService: mActivityTrackerListener: onSContextChanged(): 25
08-31 16:50:34.729  3381  3381 D WifiStateMachine: setWifiScanMove bMove = 0
,08-31 16:50:34.719  3381  3381 D WifiService: ACTIVITY_STATUS_STATIONARY 
08-31 16:50:34.729  3381  3381 I WifiStateMachine: not vehicle, sendMessageDelayed CMD_SET_SCAN_MOVE with 0
08-31 16:50:34.729  3381  3381 D WifiService: setWifiScanWithSensor bMove = 0
,08-31 16:50:34.729  3381  3856 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,08-31 16:50:34.739  3381  3568 D DisplayPowerController: animateScreenStateChange[0]: target=4
08-31 16:50:34.739  3381  3568 I libsuspend: !@autosuspend_wakeup_count_enable
08-31 16:50:34.739  3381  3568 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
08-31 16:50:34.739  3381  3568 I libsuspend: !@autosuspend_wakeup_count_enable done
08-31 16:50:34.739  3381  3568 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
08-31 16:50:34.739  3381  3568 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
08-31 16:50:34.739  3381  3568 D DisplayPowerController: animateScreenStateChange[0]: target=4
08-31 16:50:34.739  3381  3568 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
08-31 16:50:34.739  3381  3568 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
08-31 16:50:34.739  3381  3568 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
08-31 16:50:34.739  3381  3568 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
08-31 16:50:34.739  3381  3568 D PowerManagerService: mDisplayReady: true
08-31 16:50:34.739  3381  3568 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,08-31 16:50:34.749  5674  5674 E CocktailBarPositionManager: Window direction: 0
08-31 16:50:34.749  5674  5674 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
08-31 16:50:34.749  3381  4179 W ActivityManager: Permission Denial: getCurrentUser() from pid=8726, uid=10177 requires android.permission.INTERACT_ACROSS_USERS
,08-31 16:50:34.749  3381  4179 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-31 16:50:34.749  3381  4179 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=8726, uid=10177 requires android.permission.INTERACT_ACROSS_USERS
08-31 16:50:34.749  3381  4179 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28247)
08-31 16:50:34.749  3381  4179 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2852)
08-31 16:50:34.749  3381  4179 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2842)
08-31 16:50:34.749  3381  4179 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.setBtEnableFlag(BluetoothManagerService.java:1222)
08-31 16:50:34.749  3381  4179 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:254)
08-31 16:50:34.749  3381  4179 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:453)
08-31 16:50:34.749  3381  4179 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-31 16:50:34.759  3381  4179 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,08-31 16:50:34.759  3381  4179 D SettingsProvider: isChangeAllowed() : name = bluetooth_on
,08-31 16:50:34.779  8726  8877 I jxcore-log: My device name is: samsung-SM-G935F
08-31 16:50:34.779  8726  8877 I jxcore-log: 
,08-31 16:50:34.779  8726  8877 I jxcore-log: WARN testUtils: myNameCallback not set!
08-31 16:50:34.779  8726  8877 I jxcore-log: 
,08-31 16:50:34.789  9106  9106 E Zygote  : v2
08-31 16:50:34.789  9106  9106 I libpersona: KNOX_SDCARD checking this for 1002
08-31 16:50:34.789  9106  9106 I libpersona: KNOX_SDCARD not a persona
,08-31 16:50:34.789  9106  9106 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,08-31 16:50:34.789  3381  3560 I ActivityManager: Start proc 9106:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-31 16:50:34.789  9106  9106 E Zygote  : accessInfo : 0
,08-31 16:50:34.819  9106  9106 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:50:34.819  9106  9106 D ActivityThread: Added TimaKeyStore provider
,08-31 16:50:34.829  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-31 16:50:34.829  3381  3856 D wifi    : Can not initialize the vendor function pointer table
08-31 16:50:34.829  3381  3856 E WifiNative-HAL: Could not start hal
,08-31 16:50:34.829  3381  3856 E WifiStateMachine: Failed to start HAL
,08-31 16:50:34.829  3381  3856 E WifiHW  : supplicant_name : p2p_supplicant
,08-31 16:50:34.849  9106  9106 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
08-31 16:50:34.849  9106  9106 D RelationGraph: garbageCollect()
,08-31 16:50:34.849  9106  9106 W ResourcesManager: getTopLevelResources: /system/app/Bluetooth/Bluetooth.apk / 1.0 running in com.android.bluetooth rsrc of package com.android.bluetooth
,08-31 16:50:34.859  3381  4915 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,08-31 16:50:34.859  9106  9106 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,08-31 16:50:34.859  9106  9106 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:34.869  9106  9106 I InjectionManager: Inside getClassLibPath caller 
,08-31 16:50:34.919  9106  9106 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-31 16:50:34.939  3381  3856 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-31 16:50:34.939  3381  3381 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
,08-31 16:50:34.939  3381  3381 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
08-31 16:50:34.939  3381  3863 I WifiHs20Service: Message received 5011
,08-31 16:50:34.949  3946  4130 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
08-31 16:50:34.949  3381  3381 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,08-31 16:50:34.949  3381  3866 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,08-31 16:50:34.959  4280  4624 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
08-31 16:50:34.959  3946  3946 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-31 16:50:34.959  3946  3946 I HotspotTile: Provider is not defined returning false
,08-31 16:50:34.959  4280  4624 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,08-31 16:50:34.959  3946  3946 D HotspotTile: onReceive : 2, 0
,08-31 16:50:34.959  3381  3866 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,08-31 16:50:34.969  8726  8726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 16:50:34.979  3381  3523 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c32de37 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6e78fa4 8726:com.test.thalitest/u0a177}
,08-31 16:50:34.979  3381  4773 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,08-31 16:50:34.979  3381  4773 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:50:34.979  3381  4773 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:50:34.979  3381  4773 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,08-31 16:50:34.979  3381  4773 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:50:34.979  3381  4773 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:50:34.979  3381  4773 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,08-31 16:50:34.979  3381  4773 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:50:34.979  3381  4773 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:50:34.979  3381  4773 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:50:34.979  3381  4773 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:50:34.979  3381  4773 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,08-31 16:50:34.979  3381  4773 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,08-31 16:50:34.979  3381  4773 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:50:34.989  9106  9106 D BtSettings.ProfileConfig: Adding GattService
08-31 16:50:34.979  3381  4773 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:50:34.989  9106  9106 D BtSettings.ProfileConfig: Adding HeadsetService
08-31 16:50:34.999  9106  9106 D BtSettings.ProfileConfig: Adding A2dpService
08-31 16:50:34.999  9106  9106 D BtSettings.ProfileConfig: Adding HidService
,08-31 16:50:34.999  9106  9106 D BtSettings.ProfileConfig: Adding HealthService
,08-31 16:50:34.999  9106  9106 D BtSettings.ProfileConfig: Adding PanService
,08-31 16:50:34.999  9106  9106 D BtSettings.ProfileConfig: Adding BluetoothMapService
,08-31 16:50:34.999  9106  9106 D BtSettings.ProfileConfig: Adding SapService
08-31 16:50:34.999  9106  9106 D BtSettings.ProfileConfig: Adding HeadsetClientService
,08-31 16:50:34.999  9106  9106 D BtSettings.ProfileConfig: Adding A2dpSinkService
,08-31 16:50:34.999  9106  9106 D BtSettings.ProfileConfig: Adding BleAudioService
08-31 16:50:34.999  9106  9106 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-31 16:50:35.009  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-31 16:50:35.009  9118  9118 I FIPS_bssl: FIPS approved mode (1) | 9118 | /system/bin/wpa_supplicant
,08-31 16:50:35.009  9119  9119 E Zygote  : v2
,08-31 16:50:35.009  9119  9119 I libpersona: KNOX_SDCARD checking this for 1000
08-31 16:50:35.009  9119  9119 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
08-31 16:50:35.009  9119  9119 I libpersona: KNOX_SDCARD not a persona
,08-31 16:50:35.019  9119  9119 E Zygote  : accessInfo : 0
,08-31 16:50:35.019  3381  3523 I ActivityManager: Start proc 9119:com.samsung.android.securitylogagent/1000 for broadcast-5 com.samsung.android.securitylogagent/.receivers.NetworkReceiver
,08-31 16:50:35.019  3381  3974 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-31 16:50:35.019  3381  3974 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
08-31 16:50:35.019  3381  3974 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 16:50:35.019  3381  3974 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:50:35.019  3381  3974 D SettingsProvider: selectionArgs: false
08-31 16:50:35.019  3381  3974 D SettingsProvider: selectionArgs: 1002
,08-31 16:50:35.019  3381  3974 D SettingsProvider: ret = -1
,08-31 16:50:35.019  3381  4179 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-31 16:50:35.019  3381  4179 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
08-31 16:50:35.019  3381  4179 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-31 16:50:35.019  3381  4179 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:50:35.019  3381  4179 D SettingsProvider: selectionArgs: false
08-31 16:50:35.019  3381  4179 D SettingsProvider: selectionArgs: 1002
08-31 16:50:35.019  3381  4179 D SettingsProvider: ret = -1
,08-31 16:50:35.019  3381  4558 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,08-31 16:50:35.019  3381  4558 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
08-31 16:50:35.019  3381  4558 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 16:50:35.019  3381  4558 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:50:35.019  3381  4558 D SettingsProvider: selectionArgs: false
08-31 16:50:35.019  3381  4558 D SettingsProvider: selectionArgs: 1002
08-31 16:50:35.019  3381  4558 D SettingsProvider: ret = -1
,08-31 16:50:35.019  3381  3851 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.hid.HidService
08-31 16:50:35.019  3381  3851 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 16:50:35.019  3381  3851 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
08-31 16:50:35.019  3381  3851 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:50:35.019  3381  3851 D SettingsProvider: selectionArgs: false
08-31 16:50:35.019  3381  3851 D SettingsProvider: selectionArgs: 1002
,08-31 16:50:35.019  3381  3851 D SettingsProvider: ret = -1
,08-31 16:50:35.029  3381  4411 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-31 16:50:35.029  3381  4411 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
08-31 16:50:35.029  3381  4411 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 16:50:35.029  3381  4411 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-31 16:50:35.029  3381  4411 D SettingsProvider: selectionArgs: false
08-31 16:50:35.029  3381  4411 D SettingsProvider: selectionArgs: 1002
08-31 16:50:35.029  3381  4411 D SettingsProvider: ret = -1
08-31 16:50:35.029  3381  4419 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.pan.PanService
,08-31 16:50:35.029  3381  4419 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
08-31 16:50:35.029  3381  4419 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 16:50:35.029  3381  4419 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:50:35.029  3381  4419 D SettingsProvider: selectionArgs: false
,08-31 16:50:35.029  3381  4419 D SettingsProvider: selectionArgs: 1002
08-31 16:50:35.029  3381  4419 D SettingsProvider: ret = -1
,08-31 16:50:35.029  3381  3460 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-31 16:50:35.029  3381  3460 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,08-31 16:50:35.029  3381  3460 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 16:50:35.029  3381  3460 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:50:35.029  3381  3460 D SettingsProvider: selectionArgs: false
08-31 16:50:35.029  3381  3460 D SettingsProvider: selectionArgs: 1002
08-31 16:50:35.029  3381  3460 D SettingsProvider: ret = -1
,08-31 16:50:35.029  9118  9118 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-31 16:50:35.029  9118  9118 I wpa_supplicant: Successfully initialized wpa_supplicant
08-31 16:50:35.029  9118  9118 I wpa_supplicant: set_csc_config : ifname(wlan0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x20000), vendorssid_list()
08-31 16:50:35.029  3381  3975 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.sap.SapService
,08-31 16:50:35.029  9118  9118 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
08-31 16:50:35.029  3381  3975 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 16:50:35.029  3381  3975 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
08-31 16:50:35.029  3381  3975 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:50:35.029  3381  3975 D SettingsProvider: selectionArgs: false
08-31 16:50:35.029  3381  3975 D SettingsProvider: selectionArgs: 1002
,08-31 16:50:35.029  3381  3975 D SettingsProvider: ret = -1
,08-31 16:50:35.029  3381  4304 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-31 16:50:35.029  3381  4304 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
08-31 16:50:35.029  3381  4304 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-31 16:50:35.029  3381  4304 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:50:35.029  3381  4304 D SettingsProvider: selectionArgs: false
08-31 16:50:35.029  3381  4304 D SettingsProvider: selectionArgs: 1002
08-31 16:50:35.029  3381  4304 D SettingsProvider: ret = -1
,08-31 16:50:35.039  3381  3461 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
,08-31 16:50:35.039  3381  3461 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
08-31 16:50:35.039  3381  3461 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 16:50:35.039  3381  3461 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:50:35.039  3381  3461 D SettingsProvider: selectionArgs: false
08-31 16:50:35.039  3381  3461 D SettingsProvider: selectionArgs: 1002
,08-31 16:50:35.039  3381  3461 D SettingsProvider: ret = -1
,08-31 16:50:35.039  3381  4057 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.broadcom.bt.service.bleaudio.BleAudioService
,08-31 16:50:35.039  3381  4057 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
08-31 16:50:35.039  3381  4057 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 16:50:35.039  3381  4057 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:50:35.039  3381  4057 D SettingsProvider: selectionArgs: false
08-31 16:50:35.039  3381  4057 D SettingsProvider: selectionArgs: 1002
,08-31 16:50:35.039  3381  4057 D SettingsProvider: ret = -1
,08-31 16:50:35.039  9106  9106 D InjectionManager: InjectionManager
08-31 16:50:35.039  9106  9106 D InjectionManager: fillFeatureStoreMap com.android.bluetooth
,08-31 16:50:35.039  9106  9106 I InjectionManager: Constructor com.android.bluetooth, Feature store :{}
08-31 16:50:35.039  9106  9106 I InjectionManager: featureStore :{}
,08-31 16:50:35.039  9119  9119 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:50:35.039  9119  9119 D ActivityThread: Added TimaKeyStore provider
,08-31 16:50:35.049  9118  9118 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-31 16:50:35.049  3013  3013 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 9118
,08-31 16:50:35.049  3013  3013 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-31 16:50:35.049  9118  9118 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
,08-31 16:50:35.049  9118  9118 I wpa_supplicant: ssSupport state is = 1
,08-31 16:50:35.049  9118  9118 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-31 16:50:35.049  9118  9118 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-31 16:50:35.049  3013  3013 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 9118
08-31 16:50:35.049  3013  3013 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x00000106
,08-31 16:50:35.049  3381  4771 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{c32de37 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b34510d 9119:com.samsung.android.securitylogagent/1000}
,08-31 16:50:35.059  9118  9118 I SecureStorage: [INFO]: SPID(0x00000004)ss_id will be loaded by secure_storage_daemon: /system/bin/wpa_supplicant
,08-31 16:50:35.069  9119  9119 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,08-31 16:50:35.069  9119  9119 D RelationGraph: garbageCollect()
,08-31 16:50:35.069  9119  9119 W ResourcesManager: getTopLevelResources: /system/app/SecurityLogAgent/SecurityLogAgent.apk / 1.0 running in com.samsung.android.securitylogagent rsrc of package com.samsung.android.securitylogagent
,08-31 16:50:35.069  3381  3460 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,08-31 16:50:35.069  9119  9119 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,08-31 16:50:35.069  9119  9119 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:35.079  9119  9119 I InjectionManager: Inside getClassLibPath caller 
,08-31 16:50:35.079  9119  9119 W System  : ClassLoader referenced unknown path: /system/app/SecurityLogAgent/lib/arm64
,08-31 16:50:35.089  9119  9119 D InjectionManager: InjectionManager
08-31 16:50:35.089  9119  9119 D InjectionManager: fillFeatureStoreMap com.samsung.android.securitylogagent
,08-31 16:50:35.089  9119  9119 I InjectionManager: Constructor com.samsung.android.securitylogagent, Feature store :{}
08-31 16:50:35.089  9119  9119 I InjectionManager: featureStore :{}
,08-31 16:50:35.099  3381  4558 I ActivityManager: Killing 8531:com.samsung.android.sm/1000 (adj 15): DHA:empty #33
,08-31 16:50:35.109  9106  9106 D BluetoothAdapterState: make() - Creating AdapterState
,08-31 16:50:35.109  9106  9134 I BluetoothAdapterState: Entering OffState
08-31 16:50:35.109  9106  9106 I bt_bluedroid: init
,08-31 16:50:35.109  9106  9135 E bt_core_counter: counter_init unable to open counter port
08-31 16:50:35.109  9106  9135 E bt_core_module: module_init failed to initialize "counter_module"
,08-31 16:50:35.119  9106  9135 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-31 16:50:35.119  9106  9135 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-31 16:50:35.119  9106  9135 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-31 16:50:35.119  9106  9135 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-31 16:50:35.119  9106  9106 I bt_bluedroid: get_profile_interface socket
,08-31 16:50:35.119  9106  9106 W bt_btif : btif_get_adapter_property 2
08-31 16:50:35.119  9106  9106 W bt_btif : btif_get_adapter_property 1
,08-31 16:50:35.119  9106  9138 D BluetoothAdapterProperties: Address is:A8:81:95:E9:5F:6F
08-31 16:50:35.119  9106  9138 E BluetoothServiceJni: populateRssiValuesNative
08-31 16:50:35.119  9106  9138 I bt_bluedroid: getModelRssiValues
08-31 16:50:35.119  9106  9138 E BluetoothServiceJni: model_rssi_values_callback: low = -75, mid = -65, high = 127
08-31 16:50:35.119  9106  9138 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -75,-65,127
,08-31 16:50:35.119  9106  9106 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-31 16:50:35.119  3381  4411 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sm, Auto Run ON
,08-31 16:50:35.119  9106  9106 I bt_bluedroid: get_profile_interface sdp
,08-31 16:50:35.129  9106  9138 D BluetoothAdapterProperties: Name is: Samsung Galaxy S7 edge
,08-31 16:50:35.129  3381  3381 D SettingsProvider: isChangeAllowed() : name = bluetooth_name
,08-31 16:50:35.139  9106  9116 I bt_bluedroid: config_hci_snoop_log
,08-31 16:50:35.139  3381  3560 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,08-31 16:50:35.149  9106  9134 D BluetoothAdapterState: Current state: OFF, message: BLE_TURN_ON
,08-31 16:50:35.149  9106  9134 D BluetoothAdapterProperties: Setting state to 14
,08-31 16:50:35.149  9106  9134 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
08-31 16:50:35.149  9106  9134 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-31 16:50:35.149  9106  9134 D BluetoothAdapterService: updateAdapterState state is 14
08-31 16:50:35.149  9106  9134 D BluetoothAdapterService: Autoconnection is available 
,08-31 16:50:35.149  9106  9134 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 14
08-31 16:50:35.149  3381  3560 D BluetoothManagerService: Ble Turning On/Off, G state: 1, S state: 1
,08-31 16:50:35.159  9106  9134 D BluetoothSecureManager: getInstant: null
,08-31 16:50:35.159  9106  9134 D BluetoothSecureManager: calling getMethod for getService
08-31 16:50:35.159  9106  9134 D BluetoothSecureManager: calling getService
,08-31 16:50:35.159  9106  9134 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@8f3389f
,08-31 16:50:35.159  3381  3461 D BluetoothSecureManagerService: isSecureModeEnabled
08-31 16:50:35.159  3381  3461 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
08-31 16:50:35.159  9106  9134 D BtConfig.SecureMode: isSecureModeOn:false
,08-31 16:50:35.159  9106  9134 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-31 16:50:35.159  9106  9134 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
,08-31 16:50:35.159  9106  9134 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-31 16:50:35.159  9106  9134 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-31 16:50:35.159  9106  9134 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-31 16:50:35.159  9106  9134 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-31 16:50:35.159  9106  9134 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 16:50:35.159  9106  9134 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-31 16:50:35.159  9106  9134 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-31 16:50:35.159  9106  9134 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-31 16:50:35.159  9106  9134 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-31 16:50:35.159  9106  9134 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-31 16:50:35.159  9106  9134 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-31 16:50:35.169  9106  9134 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
,08-31 16:50:35.169  9106  9134 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
08-31 16:50:35.169  9106  9134 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.sap.SapService
,08-31 16:50:35.169  9106  9134 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-31 16:50:35.169  9106  9134 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-31 16:50:35.169  9106  9134 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-31 16:50:35.169  9106  9134 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-31 16:50:35.169  9106  9134 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.bleaudio.BleAudioService
,08-31 16:50:35.169  9106  9134 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.bleaudio.BleAudioService
,08-31 16:50:35.169  9106  9134 D BluetoothBondStateMachine: make
,08-31 16:50:35.169  9106  9139 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-31 16:50:35.179  9106  9134 I BluetoothAdapterState: Entering PendingCommandState
08-31 16:50:35.189  9106  9106 I BtGatt.JNI: classInitNative(L992): classInitNative: Success!
08-31 16:50:35.189  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-31 16:50:35.189  9106  9106 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-31 16:50:35.189  9106  9106 D BtGatt.GattService: Received start request. Starting profile...
08-31 16:50:35.189  9106  9106 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@46938f2
08-31 16:50:35.189  9106  9106 D BtGatt.GattService: start()
08-31 16:50:35.189  9106  9106 I bt_bluedroid: get_profile_interface gatt
,08-31 16:50:35.189  9106  9106 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@46938f2
,08-31 16:50:35.189  9106  9106 D BtGatt.AdvertiseManager: advertise manager created
08-31 16:50:35.189  9106  9106 D BtGatt.AdvertiseManager: start
,08-31 16:50:35.199  9106  9106 D BtGatt.ScanManager: start
,08-31 16:50:35.199  9106  9106 D BtGatt.GattService: [GSIM LOG]: loadLogPref
,08-31 16:50:35.209  9106  9106 D BtGatt.GattService: [GSIM LOG]: loadLogPref END
,08-31 16:50:35.219  9106  9106 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, Message sending
08-31 16:50:35.219  9106  9106 E BtGatt.GattService: notifyProfileServiceStateChanged
,08-31 16:50:35.219  9106  9106 E BluetoothAdapterService: handleMessage() - Message: 1
08-31 16:50:35.219  9106  9106 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, Before synchronized
,08-31 16:50:35.219  9106  9106 V BluetoothAdapterState: isTurningOff()=false
08-31 16:50:35.219  9106  9106 V BluetoothAdapterState: isTurningOn()=false
08-31 16:50:35.219  9106  9106 V BluetoothAdapterState: isBleTurningOn()=true
08-31 16:50:35.219  9106  9106 V BluetoothAdapterState: isBleTurningOff()=false
08-31 16:50:35.219  9106  9134 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BLE_STARTED
,08-31 16:50:35.219  9106  9134 I bt_bluedroid: bt_bluedroid
08-31 16:50:35.219  9106  9135 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-31 16:50:35.229  9106  9135 I bt_hci  : start_up
,08-31 16:50:35.229  9106  9135 I bt_vendor: alloc value 0xf3bb2169
,08-31 16:50:35.239  9106  9135 I bt_vendor: init
08-31 16:50:35.239  9106  9135 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-31 16:50:35.239  9106  9135 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
08-31 16:50:35.239  9106  9135 I bt_upio : upio_set_bluetooth_power(on: 0)
,08-31 16:50:35.239  9106  9135 I bt_upio : upio_set_bluetooth_power(on: 1)
,08-31 16:50:35.289  3013  3013 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
08-31 16:50:35.289  9118  9118 I SecureStorage: [INFO]: SPID(0x00000004)Processing data has been completed
,08-31 16:50:35.309  3381  5955 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package com.samsung.android.MtpApplication
,08-31 16:50:35.309  9118  9118 I wpa_supplicant: Ctrl_iface: loading system cred
08-31 16:50:35.309  9118  9118 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,08-31 16:50:35.319  9118  9118 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
,08-31 16:50:35.319  3013  3013 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 9118
08-31 16:50:35.319  3013  3013 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
08-31 16:50:35.319  9118  9118 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
08-31 16:50:35.319  9118  9118 I wpa_supplicant: ssSupport state is = 1
,08-31 16:50:35.319  9118  9118 I wpa_supplicant: Blacklist: Clear (all) 
,08-31 16:50:35.319  9118  9118 E wpa_supplicant: getSavedIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 16:50:35.319  9118  9118 I wpa_supplicant: [getIMSI]: sim_num 0
,08-31 16:50:35.319  9118  9118 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-31 16:50:35.349  9106  9135 D bt_hci  : start_up starting async portion
,08-31 16:50:35.349  9106  9151 I bt_hci  : event_finish_startup
08-31 16:50:35.349  9106  9151 I bt_hci_h4: hal_open
08-31 16:50:35.349  9106  9151 I bt_userial_vendor: userial vendor open: opening /dev/ttySAC1
,08-31 16:50:35.349  9106  9151 I bt_userial_vendor: userial_vendor_open():UART is setup
08-31 16:50:35.349  9106  9151 I bt_userial_vendor: device fd = 60 open
,08-31 16:50:35.349  9106  9151 E bt_hwcfg: Start CFG HW, HCI reset
,08-31 16:50:35.359  9106  9151 E bt_hwcfg: Read Local Name after HCI reset
,08-31 16:50:35.359  3381  4179 V AlarmManager:  remove PendingIntent] PendingIntent{4ced7be: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.369  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-31 16:50:35.379  9106  9151 D bt_hwcfg: Chipset BCM4359C0
08-31 16:50:35.379  9106  9151 D bt_hwcfg: Target name = [BCM4359C0]
,08-31 16:50:35.379  9106  9151 I bt_hwcfg: module_type[semco_b90s_c0].
08-31 16:50:35.379  9106  9151 E bt_hwcfg: patchram path ORG . BCM4359C0
08-31 16:50:35.379  9106  9151 E bt_hwcfg: patchram path ORG .. BCM4359C0
,08-31 16:50:35.379  9106  9151 E bt_hwcfg: patchram path ORG bcm4359C0_V0044.0061_murata.hcd BCM4359C0
08-31 16:50:35.379  9106  9151 E bt_hwcfg: patchram path ORG companion_2l1_master_setfile.bin BCM4359C0
08-31 16:50:35.379  9106  9151 E bt_hwcfg: patchram path ORG companion_2l1_mode_setfile.bin BCM4359C0
08-31 16:50:35.379  9106  9151 E bt_hwcfg: patchram path ORG companion_fw_2l1.bin BCM4359C0
08-31 16:50:35.379  9106  9151 E bt_hwcfg: patchram path ORG companion_fw_imx260.bin BCM4359C0
08-31 16:50:35.379  9106  9151 E bt_hwcfg: patchram path ORG companion_imx260_master_setfile.bin BCM4359C0
08-31 16:50:35.379  9106  9151 E bt_hwcfg: patchram path ORG companion_imx260_mode_setfile.bin BCM4359C0
08-31 16:50:35.379  9106  9151 E bt_hwcfg: patchram path ORG fimc_is_fw2_2l1.bin BCM4359C0
08-31 16:50:35.379  9106  9151 E bt_hwcfg: patchram path ORG fimc_is_fw2_imx260.bin BCM4359C0
08-31 16:50:35.379  9106  9151 E bt_hwcfg: patchram path ORG mfc_fw.bin BCM4359C0
08-31 16:50:35.379  9106  9151 E bt_hwcfg: patchram path ORG ois_fw_dom.bin BCM4359C0
,08-31 16:50:35.379  9106  9151 E bt_hwcfg: patchram path ORG ois_fw_sec.bin BCM4359C0
08-31 16:50:35.379  9106  9151 E bt_hwcfg: patchram path ORG sec_s3nrn81_firmware.bin BCM4359C0
08-31 16:50:35.379  9106  9151 E bt_hwcfg: patchram path ORG seiren_fw_dram.bin BCM4359C0
08-31 16:50:35.379  9106  9151 E bt_hwcfg: patchram path ORG seiren_fw_sram.bin BCM4359C0
08-31 16:50:35.379  9106  9151 E bt_hwcfg: patchram path ORG setfile_2l1.bin BCM4359C0
08-31 16:50:35.379  9106  9151 E bt_hwcfg: patchram path ORG setfile_4e6.bin BCM4359C0
08-31 16:50:35.379  9106  9151 E bt_hwcfg: patchram path ORG setfile_imx260.bin BCM4359C0
08-31 16:50:35.379  9106  9151 E bt_hwcfg: patchram path ORG bcm4359C0_V0044.0062_semco.hcd BCM4359C0
08-31 16:50:35.379  9106  9151 I bt_hwcfg: patch(org) : bcm4359C0_V0044.0062_semco.hcd
08-31 16:50:35.379  9106  9151 I bt_hwcfg: Found patchfile: /vendor/firmware/bcm4359C0_V0044.0062_semco.hcd
08-31 16:50:35.379  9106  9151 E bt_hwcfg: ORG patchram base 0044
08-31 16:50:35.379  9106  9151 E bt_hwcfg: ORG patchram minor 0062
08-31 16:50:35.379  9106  9151 E bt_hwcfg: fw ver (org)44.62
,08-31 16:50:35.379  9106  9151 E bt_hwcfg: Final Patchram is /vendor/firmware/bcm4359C0_V0044.0062_semco.hcd
,08-31 16:50:35.389  9106  9151 I bt_hwcfg: Axi patch failure or not include AXI patching
,08-31 16:50:35.389  3381  3851 V AlarmManager:  remove PendingIntent] PendingIntent{cc1f01f: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.389  9106  9151 I bt_hwcfg: bt vendor lib baud_1: set UART baud 3000000
,08-31 16:50:35.399  3381  3975 V AlarmManager:  remove PendingIntent] PendingIntent{cb6df6c: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.419  4019  4019 D Recents : onTaskStackChanged
,08-31 16:50:35.429  4019  4019 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.test.thalitest
,08-31 16:50:35.439  3381  3460 D PackageManager: getComponentMetadataForIconTray : com.test.thalitest.MainActivity does not exist in mServices
,08-31 16:50:35.439  3381  3460 D PackageManager: getComponentMetadataForIconTray : com.test.thalitest.MainActivity does not exist in mProviders
08-31 16:50:35.439  3381  3460 D PackageManager: getComponentMetadataForIconTray : com.test.thalitest.MainActivity does not exist in mReceivers
,08-31 16:50:35.449  4019  4019 I ApplicationPackageManager: load=com.test.thalitest, bg=192-192, dr=192-192
,08-31 16:50:35.449  4019  4019 I ApplicationPackageManager: scaled rate=0.97032255, size=192, alpha=3, hold=26, target=192
,08-31 16:50:35.489  3381  4428 V AlarmManager:  remove PendingIntent] PendingIntent{b783935: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.499  3381  4181 V AlarmManager:  remove PendingIntent] PendingIntent{79cb1ca: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.549  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-31 16:50:35.549  3381  4771 V AlarmManager:  remove PendingIntent] PendingIntent{81f6f3b: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.549  3381  3461 V AlarmManager:  remove PendingIntent] PendingIntent{be88658: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.549  3381  3460 V AlarmManager:  remove PendingIntent] PendingIntent{b0033b1: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.559  3381  4411 V AlarmManager:  remove PendingIntent] PendingIntent{abc2096: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.559  3381  4773 V AlarmManager:  remove PendingIntent] PendingIntent{e0bc417: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.569  3381  3974 V AlarmManager:  remove PendingIntent] PendingIntent{18bb004: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.579  3381  4558 V AlarmManager:  remove PendingIntent] PendingIntent{f3359ed: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.589  3381  4304 V AlarmManager:  remove PendingIntent] PendingIntent{891b022: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.599  3381  4057 V AlarmManager:  remove PendingIntent] PendingIntent{5fe8ab3: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.609  3381  4915 V AlarmManager:  remove PendingIntent] PendingIntent{515c870: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.609  3381  4179 V AlarmManager:  remove PendingIntent] PendingIntent{3f8a7e9: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.619  3381  3851 V AlarmManager:  remove PendingIntent] PendingIntent{b3eac6e: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.619  3381  3975 V AlarmManager:  remove PendingIntent] PendingIntent{d4d1f0f: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.629  3381  4419 V AlarmManager:  remove PendingIntent] PendingIntent{de6fb9c: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.629  3381  4428 V AlarmManager:  remove PendingIntent] PendingIntent{2aad9a5: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.629  3381  4181 V AlarmManager:  remove PendingIntent] PendingIntent{bad217a: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.639  3381  4771 V AlarmManager:  remove PendingIntent] PendingIntent{7469d2b: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.639  3381  3461 V AlarmManager:  remove PendingIntent] PendingIntent{7363588: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.639  3381  3460 V AlarmManager:  remove PendingIntent] PendingIntent{5946b21: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.649  3381  3584 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-31 16:50:35.659  3381  3584 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-31 16:50:35.659  3381  4411 V AlarmManager:  remove PendingIntent] PendingIntent{55bdb46: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.659  3381  4773 V AlarmManager:  remove PendingIntent] PendingIntent{30fe107: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.669  3381  3974 V AlarmManager:  remove PendingIntent] PendingIntent{6bd2234: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.669  3381  4558 V AlarmManager:  remove PendingIntent] PendingIntent{72b985d: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.669  3381  4304 V AlarmManager:  remove PendingIntent] PendingIntent{aea65d2: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.679  3381  4057 V AlarmManager:  remove PendingIntent] PendingIntent{33f86a3: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.679  3381  4915 V AlarmManager:  remove PendingIntent] PendingIntent{2242da0: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.679  3381  4179 V AlarmManager:  remove PendingIntent] PendingIntent{90e5d59: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.689  3381  3851 V AlarmManager:  remove PendingIntent] PendingIntent{7650d1e: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.689  3381  3975 V AlarmManager:  remove PendingIntent] PendingIntent{339e9ff: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.689  3381  4419 V AlarmManager:  remove PendingIntent] PendingIntent{f2e83cc: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.699  3381  4428 V AlarmManager:  remove PendingIntent] PendingIntent{ebe7615: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.699  3381  4181 V AlarmManager:  remove PendingIntent] PendingIntent{850dd2a: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.699  3381  4771 V AlarmManager:  remove PendingIntent] PendingIntent{64d271b: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.709  3381  3461 V AlarmManager:  remove PendingIntent] PendingIntent{aa610b8: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.709  3381  3460 V AlarmManager:  remove PendingIntent] PendingIntent{81d5e91: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.709  3381  4411 V AlarmManager:  remove PendingIntent] PendingIntent{c77a1f6: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.719  3381  4773 V AlarmManager:  remove PendingIntent] PendingIntent{c8d19f7: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.719  3381  3974 V AlarmManager:  remove PendingIntent] PendingIntent{2078064: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.719  3381  4558 V AlarmManager:  remove PendingIntent] PendingIntent{7a852cd: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.729  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-31 16:50:35.729  9106  9151 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-31 16:50:35.729  9106  9151 I bt_hwcfg: FW Download delta = 371882
08-31 16:50:35.729  9106  9151 D bt_hwcfg: Settlement delay -- 100 ms
08-31 16:50:35.729  9106  9151 I bt_hwcfg: Setting fw settlement delay to 100 
,08-31 16:50:35.729  3381  4304 V AlarmManager:  remove PendingIntent] PendingIntent{373e782: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.729  3381  4057 V AlarmManager:  remove PendingIntent] PendingIntent{96f5e93: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.729  3381  4915 V AlarmManager:  remove PendingIntent] PendingIntent{bee3ed0: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.739  3381  4179 V AlarmManager:  remove PendingIntent] PendingIntent{744ec9: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.739  3381  3851 V AlarmManager:  remove PendingIntent] PendingIntent{9fcf9ce: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.739  3381  3975 V AlarmManager:  remove PendingIntent] PendingIntent{82750ef: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.749  3381  4419 V AlarmManager:  remove PendingIntent] PendingIntent{b4077fc: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.749  3381  4428 V AlarmManager:  remove PendingIntent] PendingIntent{7ea0e85: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.749  3381  4181 V AlarmManager:  remove PendingIntent] PendingIntent{ef2e4da: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.759  3381  4771 V AlarmManager:  remove PendingIntent] PendingIntent{9c20d0b: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.759  3381  3461 V AlarmManager:  remove PendingIntent] PendingIntent{91b17e8: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.759  3381  3460 V AlarmManager:  remove PendingIntent] PendingIntent{7420e01: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.759  3381  4411 V AlarmManager:  remove PendingIntent] PendingIntent{d2a74a6: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.769  3381  4773 V AlarmManager:  remove PendingIntent] PendingIntent{9026ee7: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.769  3381  3974 V AlarmManager:  remove PendingIntent] PendingIntent{17dca94: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.769  3381  4558 V AlarmManager:  remove PendingIntent] PendingIntent{8c0893d: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.779  3381  4304 V AlarmManager:  remove PendingIntent] PendingIntent{5f93532: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.779  3381  4057 V AlarmManager:  remove PendingIntent] PendingIntent{ffd1283: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.779  3381  4915 V AlarmManager:  remove PendingIntent] PendingIntent{eb6fc00: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.789  3381  4179 V AlarmManager:  remove PendingIntent] PendingIntent{cb17c39: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.789  3381  3851 V AlarmManager:  remove PendingIntent] PendingIntent{881727e: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.789  3381  3975 V AlarmManager:  remove PendingIntent] PendingIntent{b7453df: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.789  3381  4419 V AlarmManager:  remove PendingIntent] PendingIntent{f8fd82c: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.799  3381  4428 V AlarmManager:  remove PendingIntent] PendingIntent{224a2f5: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.799  3381  4181 V AlarmManager:  remove PendingIntent] PendingIntent{1be388a: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.799  3381  4771 V AlarmManager:  remove PendingIntent] PendingIntent{7f44efb: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.809  3381  3461 V AlarmManager:  remove PendingIntent] PendingIntent{4384b18: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.809  3381  3460 V AlarmManager:  remove PendingIntent] PendingIntent{f697971: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.809  3381  4411 V AlarmManager:  remove PendingIntent] PendingIntent{14f5356: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.809  3381  4773 V AlarmManager:  remove PendingIntent] PendingIntent{4aedfd7: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.819  3381  3974 V AlarmManager:  remove PendingIntent] PendingIntent{df300c4: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.819  3381  4558 V AlarmManager:  remove PendingIntent] PendingIntent{64b3bad: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.819  3381  4304 V AlarmManager:  remove PendingIntent] PendingIntent{f054ee2: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.829  3381  4057 V AlarmManager:  remove PendingIntent] PendingIntent{817a273: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.829  3381  4915 V AlarmManager:  remove PendingIntent] PendingIntent{d816530: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.829  3381  4179 V AlarmManager:  remove PendingIntent] PendingIntent{ce5a9: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.839  3381  3851 V AlarmManager:  remove PendingIntent] PendingIntent{d2d772e: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.839  3381  3975 V AlarmManager:  remove PendingIntent] PendingIntent{23ff2cf: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.839  3381  4419 V AlarmManager:  remove PendingIntent] PendingIntent{c4fa45c: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.849  3381  4428 V AlarmManager:  remove PendingIntent] PendingIntent{d253365: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.849  3381  4181 V AlarmManager:  remove PendingIntent] PendingIntent{39dd83a: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.849  9106  9151 I bt_hwcfg: bt vendor lib baud_2: set UART baud 3000000
,08-31 16:50:35.849  3381  4771 V AlarmManager:  remove PendingIntent] PendingIntent{8f2eceb: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.859  3381  3461 V AlarmManager:  remove PendingIntent] PendingIntent{c60aa48: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.859  3381  3460 V AlarmManager:  remove PendingIntent] PendingIntent{4baa0e1: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.859  3381  4411 V AlarmManager:  remove PendingIntent] PendingIntent{f813e06: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.869  3381  4773 V AlarmManager:  remove PendingIntent] PendingIntent{9916cc7: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.869  3381  3974 V AlarmManager:  remove PendingIntent] PendingIntent{afa22f4: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.869  3381  4558 V AlarmManager:  remove PendingIntent] PendingIntent{fdf6a1d: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.879  3381  4304 V AlarmManager:  remove PendingIntent] PendingIntent{3e33492: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.879  3381  4057 V AlarmManager:  remove PendingIntent] PendingIntent{cae0e63: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.879  3381  4773 V AlarmManager:  remove PendingIntent] PendingIntent{2107a60: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.889  3381  4771 V AlarmManager:  remove PendingIntent] PendingIntent{c8d8b19: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.889  3381  3461 V AlarmManager:  remove PendingIntent] PendingIntent{6fc07de: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.889  3381  3460 V AlarmManager:  remove PendingIntent] PendingIntent{7692dbf: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.899  3381  4411 V AlarmManager:  remove PendingIntent] PendingIntent{472dc8c: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.899  3381  4773 V AlarmManager:  remove PendingIntent] PendingIntent{462bfd5: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.899  3381  3974 V AlarmManager:  remove PendingIntent] PendingIntent{83cc3ea: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.909  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-31 16:50:35.909  3381  4558 V AlarmManager:  remove PendingIntent] PendingIntent{68ce6db: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.909  3381  4304 V AlarmManager:  remove PendingIntent] PendingIntent{b73578: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.909  3381  4057 V AlarmManager:  remove PendingIntent] PendingIntent{31c8451: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.919  3381  4915 V AlarmManager:  remove PendingIntent] PendingIntent{b1b34b6: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.919  3381  4179 V AlarmManager:  remove PendingIntent] PendingIntent{f6915b7: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.919  3381  3851 V AlarmManager:  remove PendingIntent] PendingIntent{6e63124: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.929  3381  3975 V AlarmManager:  remove PendingIntent] PendingIntent{8d4148d: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.929  3381  4419 V AlarmManager:  remove PendingIntent] PendingIntent{29de642: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.929  3381  4428 V AlarmManager:  remove PendingIntent] PendingIntent{26f5653: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.939  3381  4181 V AlarmManager:  remove PendingIntent] PendingIntent{ce73b90: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.939  3381  4771 V AlarmManager:  remove PendingIntent] PendingIntent{3fa6c89: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.939  3152  3630 D Netd    : Iface wlan0 link up
,08-31 16:50:35.939  3152  3630 D Netd    : Iface wlan0 link up
08-31 16:50:35.939  3152  3630 D Netd    : Iface wlan0 link up
,08-31 16:50:35.939  3381  3528 D Tethering: interfaceLinkStateChanged wlan0, true
08-31 16:50:35.939  3381  3528 D Tethering: interfaceStatusChanged wlan0, true
,08-31 16:50:35.939  4991  5004 D PdnController: Interface Changed wlan0 link up
,08-31 16:50:35.939  3381  3528 D Tethering: interfaceLinkStateChanged wlan0, true
,08-31 16:50:35.939  3381  3528 D Tethering: interfaceStatusChanged wlan0, true
08-31 16:50:35.939  3381  3461 V AlarmManager:  remove PendingIntent] PendingIntent{9a8248e: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
08-31 16:50:35.939  4991  5012 D PdnController: Interface Changed wlan0 link up
,08-31 16:50:35.939  3381  3528 D Tethering: interfaceLinkStateChanged wlan0, true
,08-31 16:50:35.939  3381  3528 D Tethering: interfaceStatusChanged wlan0, true
08-31 16:50:35.949  4991  5321 D PdnController: Interface Changed wlan0 link up
,08-31 16:50:35.949  3381  3460 V AlarmManager:  remove PendingIntent] PendingIntent{b8f04af: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.949  3381  4411 V AlarmManager:  remove PendingIntent] PendingIntent{dac80bc: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.949  3381  4773 V AlarmManager:  remove PendingIntent] PendingIntent{f144845: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.949  3381  3974 V AlarmManager:  remove PendingIntent] PendingIntent{405fb9a: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.959  9106  9151 I bt_hwcfg: vendor lib fwcfg completed
08-31 16:50:35.959  9106  9151 I bt_vendor: firmware callback
08-31 16:50:35.959  9106  9151 I bt_hci  : firmware_config_callback
,08-31 16:50:35.959  9106  9157 I bt_btu_task: Bluetooth chip preload is complete
,08-31 16:50:35.959  3381  4558 V AlarmManager:  remove PendingIntent] PendingIntent{c513ccb: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.959  9106  9157 I         : BTE_InitTraceLevels -- TRC_HCI
08-31 16:50:35.959  9106  9157 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-31 16:50:35.959  9106  9157 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-31 16:50:35.959  9106  9157 I         : BTE_InitTraceLevels -- TRC_AVDT
08-31 16:50:35.959  9106  9157 I         : BTE_InitTraceLevels -- TRC_AVRC
08-31 16:50:35.959  9106  9157 I         : BTE_InitTraceLevels -- TRC_A2D
08-31 16:50:35.959  9106  9157 I         : BTE_InitTraceLevels -- TRC_BNEP
08-31 16:50:35.959  9106  9157 I         : BTE_InitTraceLevels -- TRC_BTM
,08-31 16:50:35.959  9106  9157 I         : BTE_InitTraceLevels -- TRC_GAP
08-31 16:50:35.959  9106  9157 I         : BTE_InitTraceLevels -- TRC_PAN
08-31 16:50:35.959  9106  9157 I         : BTE_InitTraceLevels -- TRC_SDP
08-31 16:50:35.959  9106  9157 I         : BTE_InitTraceLevels -- TRC_GATT
08-31 16:50:35.959  9106  9157 I         : BTE_InitTraceLevels -- TRC_SMP
08-31 16:50:35.959  9106  9157 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-31 16:50:35.959  9106  9157 I         : BTE_InitTraceLevels -- TRC_BTIF
08-31 16:50:35.959  9106  9157 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
08-31 16:50:35.959  3381  4304 V AlarmManager:  remove PendingIntent] PendingIntent{f1eeca8: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.959  3381  4057 V AlarmManager:  remove PendingIntent] PendingIntent{e3623c1: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.969  3381  4915 V AlarmManager:  remove PendingIntent] PendingIntent{4383766: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.969  3381  4179 V AlarmManager:  remove PendingIntent] PendingIntent{bb4daa7: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.969  3381  3851 V AlarmManager:  remove PendingIntent] PendingIntent{aca2b54: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.979  3381  3975 V AlarmManager:  remove PendingIntent] PendingIntent{8403afd: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.979  3381  4419 V AlarmManager:  remove PendingIntent] PendingIntent{20063f2: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.979  3381  4428 V AlarmManager:  remove PendingIntent] PendingIntent{7ca7a43: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.989  3381  4181 V AlarmManager:  remove PendingIntent] PendingIntent{548a8c0: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.989  3381  4771 V AlarmManager:  remove PendingIntent] PendingIntent{7da89f9: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.989  3381  3461 V AlarmManager:  remove PendingIntent] PendingIntent{daccd3e: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.989  3381  3460 V AlarmManager:  remove PendingIntent] PendingIntent{510779f: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.999  3381  4411 V AlarmManager:  remove PendingIntent] PendingIntent{6f90ec: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.999  3381  4773 V AlarmManager:  remove PendingIntent] PendingIntent{30ccb5: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:35.999  3381  3974 V AlarmManager:  remove PendingIntent] PendingIntent{c247f4a: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:36.009  3381  4558 V AlarmManager:  remove PendingIntent] PendingIntent{78eeebb: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:36.009  3381  4304 V AlarmManager:  remove PendingIntent] PendingIntent{43acfd8: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:36.009  3381  4057 V AlarmManager:  remove PendingIntent] PendingIntent{16e7f31: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:36.009  3381  4915 V AlarmManager:  remove PendingIntent] PendingIntent{7b34616: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:36.019  3381  4179 V AlarmManager:  remove PendingIntent] PendingIntent{1b3bb97: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:36.019  8726  8877 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-31 16:50:36.019  8726  8877 I jxcore-log: 
,08-31 16:50:36.019  3381  3851 V AlarmManager:  remove PendingIntent] PendingIntent{a791184: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:36.019  3381  3975 V AlarmManager:  remove PendingIntent] PendingIntent{8fadd6d: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:36.029  3381  4419 V AlarmManager:  remove PendingIntent] PendingIntent{195ada2: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:36.029  9118  9118 I wpa_supplicant: set_csc_config : ifname(p2p0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x0), vendorssid_list()
,08-31 16:50:36.029  3381  4057 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3381
08-31 16:50:36.029  9118  9118 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
08-31 16:50:36.029  3381  3568 D DisplayPowerController: animateScreenStateChange[0]: target=3
08-31 16:50:36.029  3381  3568 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
08-31 16:50:36.029  3381  3568 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
,08-31 16:50:36.029  3381  3568 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
08-31 16:50:36.029  3381  3568 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
,08-31 16:50:36.029  3381  3578 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
,08-31 16:50:36.029  3381  3562 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
,08-31 16:50:36.029  3381  3562 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
,08-31 16:50:36.029  3381  4057 D PowerManagerService: mDisplayReady: false
,08-31 16:50:36.029  3381  4057 I libsuspend: !@autosuspend_wakeup_count_disable
08-31 16:50:36.029  3381  4773 V AlarmManager:  remove PendingIntent] PendingIntent{4ee7a33: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
08-31 16:50:36.029  3381  4057 I libsuspend: !@autosuspend_wakeup_count_disable done
,08-31 16:50:36.039  9118  9118 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
,08-31 16:50:36.039  3013  3013 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 9118
08-31 16:50:36.039  3013  3013 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
08-31 16:50:36.039  9118  9118 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
,08-31 16:50:36.039  9118  9118 I wpa_supplicant: ssSupport state is = 1
,08-31 16:50:36.039  9118  9118 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-31 16:50:36.039  9118  9118 E wpa_supplicant: nl80211: Could not configure driver mode
08-31 16:50:36.039  9118  9118 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
08-31 16:50:36.039  9118  9118 E wpa_supplicant: p2p0: Failed to initialize driver interface
08-31 16:50:36.039  9118  9118 I wpa_supplicant: Blacklist: Clear (all) 
08-31 16:50:36.039  9106  9157 W bt_l2cap: l2c_link_processs_ble_num_bufs 15
,08-31 16:50:36.039  9106  9157 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3b027a9
08-31 16:50:36.039  9106  9157 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3b027a9 
08-31 16:50:36.039  9106  9157 E bt_btm  : btm_ble_set_search_if search_if=4
,08-31 16:50:36.039  3009  3009 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7f80383c00
08-31 16:50:36.039  3009  3009 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
08-31 16:50:36.049  9118  9118 I wpa_supplicant: set_csc_config : ifname(p2p0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x0), vendorssid_list()
08-31 16:50:36.049  9118  9118 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,08-31 16:50:36.049  9106  9138 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 9 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 20 mIsExtendedScanSupported = true mIsDebugLogSupported = true mAobleSupported = 1
,08-31 16:50:36.059  9118  9118 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
,08-31 16:50:36.059  3013  3013 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 9118
,08-31 16:50:36.059  3013  3013 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
08-31 16:50:36.059  9118  9118 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
08-31 16:50:36.059  9118  9118 I wpa_supplicant: ssSupport state is = 1
08-31 16:50:36.059  9118  9118 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-31 16:50:36.059  3381  3568 D DisplayPowerController: animateScreenStateChange[0]: target=3
,08-31 16:50:36.059  3381  3568 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
,08-31 16:50:36.059  3381  3568 I libsuspend: !@autosuspend_wakeup_count_enable
08-31 16:50:36.059  3381  3568 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
,08-31 16:50:36.059  3381  3568 I libsuspend: !@autosuspend_wakeup_count_enable done
08-31 16:50:36.059  3381  3568 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
08-31 16:50:36.059  3381  3568 D DisplayPowerController: animateScreenStateChange[0]: target=3
08-31 16:50:36.059  3381  3568 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
08-31 16:50:36.059  3381  3568 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
,08-31 16:50:36.059  3381  3568 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
08-31 16:50:36.059  3381  3568 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
08-31 16:50:36.059  3381  3568 D PowerManagerService: mDisplayReady: true
,08-31 16:50:36.059  9106  9138 E bt_btif : btif_transfer_context() Caller thread is BTIF thread. Don't try context switch.
,08-31 16:50:36.059  3381  3568 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,08-31 16:50:36.069  5674  5674 E CocktailBarPositionManager: Window direction: 0
,08-31 16:50:36.069  5674  5674 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,08-31 16:50:36.069  9118  9118 I wpa_supplicant: P2P: Set prekey state (NONE -> NONE),
,08-31 16:50:36.069  9106  9138 D bt_hci  : do_postload posting postload work item
,08-31 16:50:36.069  9106  9151 I bt_hci  : event_postload
,08-31 16:50:36.069  9106  9138 E bt_btif_sock: btif_sock_init: !vhci_init
,08-31 16:50:36.069  9106  9151 D bt_hwcfg: hw_sco_config
,08-31 16:50:36.069  9106  9151 I bt_vendor: sco_config_cb
08-31 16:50:36.069  9106  9138 E bt_btif : ## init_cmd_fd assert ts[h].cmd_fdr == -1 && ts[h].cmd_fdw == -1 failed at line:289 ##
,08-31 16:50:36.069  9106  9151 I bt_hci  : sco_config_callback postload finished.
08-31 16:50:36.069  3381  3856 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
08-31 16:50:36.069  3381  3856 E WifiStateMachine: Deffering msg in Supplicant Starting State131085
,08-31 16:50:36.079  9106  9138 D bt_bte_conf: Device ID record 1 : primary
,08-31 16:50:36.079  9106  9138 D bt_bte_conf:   vendorId            = 0075
08-31 16:50:36.079  9106  9138 D bt_bte_conf:   vendorIdSource      = 0001
,08-31 16:50:36.079  9106  9138 D bt_bte_conf:   product             = 0100
08-31 16:50:36.079  9106  9138 D bt_bte_conf:   version             = 0200
,08-31 16:50:36.079  9106  9138 D bt_bte_conf:   clientExecutableURL = 
08-31 16:50:36.079  9106  9138 D bt_bte_conf:   serviceDescription  = 
08-31 16:50:36.079  9106  9138 D bt_bte_conf:   documentationURL    = 
08-31 16:50:36.079  9106  9138 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-31 16:50:36.079  9106  9135 D bt_stack_manager: event_start_up_stack finished
08-31 16:50:36.079  9106  9138 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  14 , val : 15
08-31 16:50:36.079  9106  9138 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  15 , val : 8
08-31 16:50:36.079  9106  9138 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  16 , val : 24838
,08-31 16:50:36.079  9106  9138 D BluetoothDataManager: UpdateLocalInfo for String is called!!! type : 17, val : BCM4359C0 Hero SWB-B90S eLNA-0044
08-31 16:50:36.079  9106  9138 D BluetoothDataManager: firmwareVersion from Property : bcm4359C0_V0044.0062_semco.hcd
08-31 16:50:36.079  9106  9138 E BluetoothAdapterState: stateChangeCallback : 1
,08-31 16:50:36.079  9106  9134 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: ENABLED_READY
08-31 16:50:36.079  9106  9134 D BluetoothAdapterProperties: Setting state to 15
08-31 16:50:36.079  3381  3974 V AlarmManager:  remove PendingIntent] PendingIntent{937c1f0: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:36.079  9106  9134 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-31 16:50:36.079  9106  9151 I bt_vendor: low_power_mode_cb
08-31 16:50:36.079  3381  3856 D WifiNative-wlan0: callSECApiBoolean - ID [301]
08-31 16:50:36.079  9118  9118 I wpa_supplicant: HOTSPOT20_ENABLE called ON
,08-31 16:50:36.079  9118  9118 I wpa_supplicant: Blacklist: Clear (all) 
,08-31 16:50:36.089  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-31 16:50:36.089  9118  9118 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-31 16:50:36.089  9106  9134 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-31 16:50:36.089  9106  9134 D BluetoothAdapterService: updateAdapterState state is 15
08-31 16:50:36.089  3381  4419 V AlarmManager:  remove PendingIntent] PendingIntent{974e369: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:36.089  9106  9134 D BluetoothAdapterService: Autoconnection is available 
,08-31 16:50:36.089  9106  9134 D BluetoothAdapterService: updateAdapterState prevState = 14newState = 15
08-31 16:50:36.089  9106  9134 I BluetoothAdapterState: Entering BleOnState
08-31 16:50:36.089  9118  9118 I wpa_supplicant: wlan0: Skip scan - bUseNetwork false
,08-31 16:50:36.089  3381  3856 D WifiNative-wlan0: callSECApiInt - ID [210]
,08-31 16:50:36.099  3381  3381 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
,08-31 16:50:36.099  3381  3860 D HS20StateMachine: WIFI_STATE_ENABLED
08-31 16:50:36.099  3381  3860 D HS20StateMachine: reloadCredentialsToSupplicant
,08-31 16:50:36.099  3381  3381 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
08-31 16:50:36.099  3381  3860 D HotspotDBHandler: getCredentialIds
,08-31 16:50:36.099  3381  3863 I WifiHs20Service: Message received 5011
08-31 16:50:36.099  3946  4130 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,08-31 16:50:36.099  3381  3381 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION,
,08-31 16:50:36.109  3381  4236 W SLocation: No Active Data Connection
,08-31 16:50:36.109  3381  3866 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,08-31 16:50:36.109  4280  4624 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
08-31 16:50:36.109  4280  4624 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,08-31 16:50:36.109  3381  3866 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,08-31 16:50:36.119  8726  8726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 16:50:36.119  8726  8726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 16:50:36.119  8726  8726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 16:50:36.119  8726  8726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-31 16:50:36.119  8726  8726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 16:50:36.119  8726  8726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 16:50:36.119  8726  8726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 16:50:36.119  8726  8726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 16:50:36.119  8726  8726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 16:50:36.119  8726  8726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 16:50:36.119  8726  8726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 16:50:36.119  3381  3523 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c868f u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b34510d 9119:com.samsung.android.securitylogagent/1000}
,08-31 16:50:36.119  3381  3560 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-31 16:50:36.119  3381  3560 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,08-31 16:50:36.129  9106  9134 D BluetoothAdapterState: Current state: BLE ON, message: USER_TURN_ON
,08-31 16:50:36.129  3381  4057 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c868f u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6e78fa4 8726:com.test.thalitest/u0a177}
,08-31 16:50:36.129  3381  3974 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,08-31 16:50:36.129  3381  3974 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:50:36.129  3381  3974 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:50:36.129  3381  3974 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,08-31 16:50:36.129  3381  3974 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:50:36.139  3381  3974 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:50:36.139  3381  3974 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:50:36.139  3381  3974 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:50:36.139  3381  3974 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:50:36.139  3381  3974 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,08-31 16:50:36.139  3381  3974 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:50:36.139  3381  3974 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,08-31 16:50:36.139  3381  3974 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:50:36.139  3381  3974 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:50:36.139  3381  3974 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,08-31 16:50:36.149  9118  9118 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,08-31 16:50:36.149  3381  3856 D WifiConfigStore: Loading config and enabling all networks 
,08-31 16:50:36.149  3946  3946 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 16:50:36.149  3946  3946 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 272
,08-31 16:50:36.149  3946  3946 I HotspotTile: Provider is not defined returning false
,08-31 16:50:36.149  3946  3946 D HotspotTile: onReceive : 3, 0
08-31 16:50:36.149  9164  9164 E Zygote  : v2
08-31 16:50:36.149  9164  9164 I libpersona: KNOX_SDCARD checking this for 10119
08-31 16:50:36.149  9164  9164 I libpersona: KNOX_SDCARD not a persona
,08-31 16:50:36.149  9164  9164 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,08-31 16:50:36.149  9164  9164 E Zygote  : accessInfo : 0
08-31 16:50:36.149  9164  9164 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.samsung.hs20provider 
,08-31 16:50:36.159  3381  3860 I ActivityManager: Start proc 9164:com.samsung.hs20provider/u0a119 for content provider com.samsung.hs20provider/.Hs20Provider
,08-31 16:50:36.159  9106  9134 D BluetoothAdapterProperties: Setting state to 11
08-31 16:50:36.159  3381  4181 V AlarmManager:  remove PendingIntent] PendingIntent{7ef0d1c: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
08-31 16:50:36.159  9106  9134 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-31 16:50:36.159  9106  9134 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-31 16:50:36.159  9106  9134 D BluetoothAdapterService: updateAdapterState state is 11
08-31 16:50:36.159  3381  3560 D BluetoothManagerService: Turning On/Off, G state: 2, S state: 2, mBLE count: 0, s BLE count: 0
08-31 16:50:36.159  9106  9134 D BluetoothAdapterService: Autoconnection is available 
08-31 16:50:36.159  9106  9134 D BluetoothAdapterService: updateAdapterState prevState = 15newState = 11
08-31 16:50:36.159  9106  9134 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-31 16:50:36.159  9106  9134 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-31 16:50:36.159  9106  9134 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-31 16:50:36.169  3381  3856 I WifiConfigStore: "NG700" is a verified password AP: true
08-31 16:50:36.169  3381  3856 E WifiConfigStore: Not a HS20
08-31 16:50:36.169  9106  9134 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-31 16:50:36.169  3381  3856 D WifiConfigStore: loaded 0 passpoint configs
,08-31 16:50:36.169  3381  3856 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-31 16:50:36.179  3381  3856 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-31 16:50:36.179  9106  9106 D HeadsetService: Received start request. Starting profile...
08-31 16:50:36.179  9106  9106 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@46938f2
08-31 16:50:36.179  3381  3856 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
08-31 16:50:36.179  3381  3856 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
08-31 16:50:36.179  9106  9106 D HeadsetProvider: make
08-31 16:50:36.179  9106  9106 D HeadsetProvider: HeadsetProvider
08-31 16:50:36.179  9106  9106 I HeadsetProvider: clearAllHeadsetSettings(0)
08-31 16:50:36.179  9164  9164 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:50:36.179  9164  9164 D ActivityThread: Added TimaKeyStore provider
,08-31 16:50:36.179  9106  9134 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-31 16:50:36.179  3381  3381 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-31 16:50:36.179  3381  3381 I InputMethodManagerService: [BT Setting State] State =11
,08-31 16:50:36.179  3381  3381 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3381 (0x0)
08-31 16:50:36.189  3381  3381 I libsuspend: !@autosuspend_wakeup_count_disable
,08-31 16:50:36.189  3381  3381 I libsuspend: !@autosuspend_wakeup_count_disable done
08-31 16:50:36.189  3381  3381 D PowerManagerService: mDisplayReady: false
,08-31 16:50:36.189  4338  4338 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
08-31 16:50:36.189  3381  3568 D DisplayPowerController: animateScreenStateChange[0]: target=4
08-31 16:50:36.189  3946  4130 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,08-31 16:50:36.189  3381  3381 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
08-31 16:50:36.189  3009  3009 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7f80383c00
08-31 16:50:36.189  3381  3568 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
08-31 16:50:36.189  3009  3009 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
08-31 16:50:36.189  3381  3568 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
08-31 16:50:36.189  3381  3568 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
08-31 16:50:36.189  3381  3578 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
,08-31 16:50:36.189  3381  3562 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
08-31 16:50:36.189  3381  3562 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
,08-31 16:50:36.189  3946  4130 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-31 16:50:36.199  9106  9106 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-31 16:50:36.199  9106  9106 D HeadsetStateMachine: make
,08-31 16:50:36.199  3381  3568 D DisplayPowerController: animateScreenStateChange[0]: target=4
08-31 16:50:36.199  3381  3568 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
,08-31 16:50:36.199  3381  3568 I libsuspend: !@autosuspend_wakeup_count_enable
08-31 16:50:36.199  3381  3568 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
08-31 16:50:36.199  3381  3568 I libsuspend: !@autosuspend_wakeup_count_enable done
,08-31 16:50:36.199  3381  3568 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
08-31 16:50:36.199  9106  9106 E HeadsetStateMachine: # of Max HF connection is 3
08-31 16:50:36.199  3381  3568 D DisplayPowerController: animateScreenStateChange[0]: target=4
08-31 16:50:36.199  3381  3568 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
08-31 16:50:36.199  3381  3568 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
,08-31 16:50:36.199  3381  3568 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
08-31 16:50:36.199  3381  3568 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
08-31 16:50:36.199  3381  3568 D PowerManagerService: mDisplayReady: true
08-31 16:50:36.199  3381  3568 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,08-31 16:50:36.199  5674  5674 E CocktailBarPositionManager: Window direction: 0
,08-31 16:50:36.199  5674  5674 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,08-31 16:50:36.209  3381  3381 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
,08-31 16:50:36.209  3381  3381 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 16:50:36.209  3381  3381 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,08-31 16:50:36.209  7104  7104 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-31 16:50:36.209  8726  8726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 16:50:36.219  3381  3523 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{754fcab u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fdb56ee 8864:com.android.settings/1000}
,08-31 16:50:36.219  3381  3856 D WifiConfigStore: setNetworkPriorityDefault: networkId = 0, priority = 1
,08-31 16:50:36.219  3381  3856 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-31 16:50:36.229  3381  3975 V AlarmManager:  remove PendingIntent] PendingIntent{fec96a1: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:36.229  3381  3856 D WifiNative-wlan0: callSECApiBoolean - ID [13]
,08-31 16:50:36.229  9118  9118 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-31 16:50:36.229  9118  9118 I wpa_supplicant: resume autoscan
08-31 16:50:36.229  9118  9118 I wpa_supplicant: autoscan_samsung_exponential_notify_scan : scan_interval = 8
08-31 16:50:36.229  9118  9118 I wpa_supplicant: autoscan: autoscan_notify_scan, scan_interval = 8
08-31 16:50:36.229  9118  9118 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-31 16:50:36.229  9118  9118 I wpa_supplicant: reset timer : RESET_TIMER 0
08-31 16:50:36.229  9118  9118 I wpa_supplicant: P2P: Current p2p state = IDLE
08-31 16:50:36.229  9118  9118 I wpa_supplicant: First Scan Start
08-31 16:50:36.229  8726  8877 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-31 16:50:36.229  8726  8877 I jxcore-log: 
,08-31 16:50:36.239  9118  9118 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
08-31 16:50:36.239  9106  9134 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-31 16:50:36.239  3381  3856 D WifiNative-wlan0: Setting external_sim to 1
,08-31 16:50:36.239  3381  3856 D WifiStateMachine: [setCountryCode()] Airplane mode return !!!
,08-31 16:50:36.239  3381  3856 D WifiStateMachine: Setting OUI to DA-A1-19
,08-31 16:50:36.239  9118  9118 I wpa_supplicant: bt_status is set be DISCONNECTED
,08-31 16:50:36.239  8726  8877 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-31 16:50:36.239  8726  8877 I jxcore-log: 
,08-31 16:50:36.249  3381  3381 I WifiHs20Service: Broadcast received:android.net.wifi.CONFIGURED_NETWORKS_CHANGE
08-31 16:50:36.249  3381  3381 D WifiHs20Service: reason: 2
08-31 16:50:36.249  3381  3863 I WifiHs20Service: Message received 5014
08-31 16:50:36.249  3381  3863 E WifiHs20Service: received HS20_UTILITY_ACTION_TYPE_HS20_CONFIGURATION_CHANGED
08-31 16:50:36.249  3381  3863 E WifiHs20Service: The changed config is NULL
,08-31 16:50:36.249  3946  4195 D BluetoothTile: handleUpdateState :  supported = true, enabled = false, enabling = true, connected = false, connecting = false, mController.getLastDeviceName() = null
,08-31 16:50:36.249  3381  3856 E WifiNative-wlan0: do suspend true
,08-31 16:50:36.249  3381  4428 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{754fcab u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4ead505 4977:com.samsung.android.providers.context/u0a9}
08-31 16:50:36.249  3946  3946 D QSTileView: handleLabelStateChanged() label = Bluetooth cellWidth 272
,08-31 16:50:36.259  3381  3856 D WifiStateMachine:  p2p Needed be enabled 
,08-31 16:50:36.259  9164  9164 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
08-31 16:50:36.259  9164  9164 D RelationGraph: garbageCollect()
,08-31 16:50:36.259  9164  9164 W ResourcesManager: getTopLevelResources: /system/app/Hs20Provider/Hs20Provider.apk / 1.0 running in com.samsung.hs20provider rsrc of package com.samsung.hs20provider
08-31 16:50:36.259  3381  3855 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-31 16:50:36.259  3381  4411 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[],
08-31 16:50:36.269  3152  3637 D CommandListener: Setting iface cfg
08-31 16:50:36.269  3152  3637 D CommandListener: Trying to bring up p2p0
08-31 16:50:36.269  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
08-31 16:50:36.269  3152  3630 D Netd    : Iface p2p0 link up
08-31 16:50:36.269  3381  3855 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-31 16:50:36.269  3381  3855 D SecContentProvider: insert(), uri = 2
08-31 16:50:36.269  3381  3528 D Tethering: interfaceLinkStateChanged p2p0, true
08-31 16:50:36.269  3381  3528 D Tethering: interfaceStatusChanged p2p0, true
,08-31 16:50:36.269  9164  9164 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,08-31 16:50:36.279  4991  5321 D PdnController: Interface Changed p2p0 link up
,08-31 16:50:36.279  3381  3855 D WifiP2pService: P2pEnablingState
,08-31 16:50:36.279  3381  3855 D WifiP2pService: P2pEnablingState{ what=147457 }
08-31 16:50:36.279  9106  9134 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-31 16:50:36.279  3381  3855 D WifiP2pService: P2p socket connection successful
08-31 16:50:36.279  3381  3855 D WifiP2pService: P2pEnabledState
08-31 16:50:36.279  3381  3855 D SecContentProvider: insert(), uri = 2
08-31 16:50:36.279  9164  9164 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:36.279  9106  9106 I bt_bluedroid: get_profile_interface handsfree
,08-31 16:50:36.289  9164  9164 I InjectionManager: Inside getClassLibPath caller 
,08-31 16:50:36.289  3381  4558 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{754fcab u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{51aad4d 4305:com.google.android.gms.persistent/u0a21}
,08-31 16:50:36.289  4305  4305 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
,08-31 16:50:36.289  9164  9164 W System  : ClassLoader referenced unknown path: /system/app/Hs20Provider/lib/arm64
,08-31 16:50:36.299  3381  3856 D WifiNative-HAL: Failing getSupportedFeatureset because HAL isn't started
,08-31 16:50:36.299  3381  3856 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-31 16:50:36.299  3381  3856 D WifiStateMachine: [FCC]Airplane on, setFccChannel(0)!!!
08-31 16:50:36.299  3381  3856 D WifiStateMachine: setFccChannelNative: channel = 0
08-31 16:50:36.299  3381  3856 D WifiNative-wlan0: callSECApiInt - ID [230]
,08-31 16:50:36.309  9106  9134 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-31 16:50:36.309  3381  3855 D WifiP2pService: sending p2p connection changed broadcast: IDLE
,08-31 16:50:36.309  3381  3856 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,08-31 16:50:36.309  3381  3855 D WifiP2pService: create mNetworkAgent
,08-31 16:50:36.309  3381  3855 D P2pNetworkAgent: NetworkAgent: Registering NetworkAgent
,08-31 16:50:36.319  9106  9134 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
,08-31 16:50:36.319  3381  3889 E WifiScanningService: could not start HAL
08-31 16:50:36.319  3381  3855 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-31 16:50:36.319  3381  3381 D RttService: SCAN_AVAILABLE : 3
08-31 16:50:36.319  3381  3865 D ConnectivityService: Got NetworkAgent Messenger
08-31 16:50:36.319  3381  3890 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-31 16:50:36.319  3381  3865 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from null to UNKNOWN, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 16:50:36.319  3381  3865 E ConnectivityService: updateNetworkInfo()
08-31 16:50:36.319  3381  3865 D ConnectivityService: NetworkAgent connected
08-31 16:50:36.319  3381  3865 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} } for legacy network type 13
,08-31 16:50:36.319  3381  3381 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-31 16:50:36.319  3381  3562 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,08-31 16:50:36.319  3381  3562 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false, mScanRequestedInConnected = false
08-31 16:50:36.319  3381  3562 D WifiDisplayController: disconnect
08-31 16:50:36.319  3381  3562 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-31 16:50:36.329  3381  4558 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{754fcab u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6284b71 8433:com.sec.android.app.shealth:remote/u0a39}
,08-31 16:50:36.329  3381  3856 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
08-31 16:50:36.329  3381  3461 V AlarmManager:  remove PendingIntent] PendingIntent{c77964d: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:36.339  9106  9134 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-31 16:50:36.339  9106  9134 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-31 16:50:36.339  9106  9134 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-31 16:50:36.339  9106  9134 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-31 16:50:36.339  9106  9134 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.bleaudio.BleAudioService
,08-31 16:50:36.339  9118  9118 I wpa_supplicant: P2P: Set Samsung Discovery Icon = 256
,08-31 16:50:36.339  9118  9118 I wpa_supplicant: P2P: Set Samsung Discovery name = 
,08-31 16:50:36.349  9106  9106 I DualScoManager: Instantiating Dual Sco Manager
08-31 16:50:36.349  9106  9106 I DualScoManager: Set HeadsetServiceHelper
,08-31 16:50:36.349  9106  9106 D BluetoothAtMessage: createCMTIContentObservers
,08-31 16:50:36.349  9164  9164 D InjectionManager: InjectionManager
08-31 16:50:36.349  9164  9164 D InjectionManager: fillFeatureStoreMap com.samsung.hs20provider
08-31 16:50:36.349  3381  3562 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,08-31 16:50:36.349  9164  9164 I InjectionManager: Constructor com.samsung.hs20provider, Feature store :{}
08-31 16:50:36.349  9164  9164 I InjectionManager: featureStore :{}
,08-31 16:50:36.349  3946  3946 D WifiP2pController: onReceive android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-31 16:50:36.349  3946  3946 D SoundPathController: onReceive - android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-31 16:50:36.359  3946  3946 D ApMirroringController: onReceive android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-31 16:50:36.359  3946  3946 D AllShareCastTile: onReceive : android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-31 16:50:36.359  3381  4428 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-31 16:50:36.359  3946  3946 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-31 16:50:36.359  9164  9175 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_credentials
,08-31 16:50:36.359  9164  9175 D HotspotProvider: CREDENTIAL
08-31 16:50:36.359  9164  9175 D HotspotProvider: No prepend tags
,08-31 16:50:36.359  4280  4636 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,08-31 16:50:36.369  3381  4558 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{754fcab u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fdb56ee 8864:com.android.settings/1000}
,08-31 16:50:36.369  8864  8864 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
08-31 16:50:36.369  8864  8864 D BluetoothStatusReceiver: AdapterStateChanged :: state = 11
,08-31 16:50:36.369  8864  8864 D LocalBluetoothManager: LocalBluetoothManager :: sInstance == null
,08-31 16:50:36.379  8864  8864 D LocalBluetoothManager: LocalBluetoothManager :: constructor
,08-31 16:50:36.379  9106  9134 I BluetoothAdapterState: Entering PendingCommandState
,08-31 16:50:36.379  8864  8864 D BluetoothEventManager: BluetoothEventManager Constructor :: 
,08-31 16:50:36.389  3381  3461 V AlarmManager:  remove PendingIntent] PendingIntent{7658168: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:36.389  3381  3860 D HS20StateMachine: CMD_HOTSPOT20_ENABLE : 
08-31 16:50:36.389  3381  3860 D HS20StateMachine: enter : DiscoveringState
,08-31 16:50:36.399  3381  4558 V AlarmManager:  remove PendingIntent] PendingIntent{215f981: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
08-31 16:50:36.399  8864  8864 D LocalBluetoothProfileManager: PANU : true
,08-31 16:50:36.399  9106  9106 D HeadsetProvider: Created cursor android.database.sqlite.SQLiteCursor@478d987
,08-31 16:50:36.409  3381  3460 V AlarmManager:  remove PendingIntent] PendingIntent{c990667: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:36.409  9106  9106 D HeadsetProvider: setHeadsetDB - Can't find 300 for A8:81:95:E9:5F:XX
,08-31 16:50:36.409  3381  4773 V AlarmManager:  remove PendingIntent] PendingIntent{9a757b9: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:36.409  3381  3855 E WifiP2pService: Failed to set my phone number info into probe response
,08-31 16:50:36.419  8864  8864 D BluetoothSap: Create BluetoothSap proxy object
,08-31 16:50:36.419  9106  9106 I HeadsetProvider: setHeadsetDB - A8:81:95:E9:5F:XX, 300, 1, true
,08-31 16:50:36.419  3381  3855 D WifiNative-p2p0: p2pGetDeviceAddress
,08-31 16:50:36.419  3381  3855 D WifiNative-p2p0: p2pGetDeviceAddress returning 4e:66:41:a6:c7:2d
,08-31 16:50:36.419  3381  3855 D WifiP2pService: DeviceAddress: 4e:c7:2d
,08-31 16:50:36.419  3381  3562 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: [Phone] Samsung Galaxy S7 edge
08-31 16:50:36.419  3381  3562 D WifiDisplayController:  deviceAddress: 4e:66:41:a6:c7:2d
08-31 16:50:36.419  3381  3562 D WifiDisplayController:  primary type: 10-0050F204-5
08-31 16:50:36.419  3381  3562 D WifiDisplayController:  secondary type: null
08-31 16:50:36.419  3381  3562 D WifiDisplayController:  wps: 0
08-31 16:50:36.419  3381  3562 D WifiDisplayController:  grpcapab: 0
08-31 16:50:36.419  3381  3562 D WifiDisplayController:  devcapab: 0
08-31 16:50:36.419  3381  3562 D WifiDisplayController:  status: 3
08-31 16:50:36.419  3381  3562 D WifiDisplayController:  wfdInfo: null
08-31 16:50:36.419  3381  3562 D WifiDisplayController:  groupownerAddress: null
08-31 16:50:36.419  3381  3562 D WifiDisplayController:  GOdeviceName: null
08-31 16:50:36.419  3381  3562 D WifiDisplayController:  interfaceAddress: 
08-31 16:50:36.419  3381  3562 D WifiDisplayController:  SConnectInfo : null
08-31 16:50:36.419  3381  3562 D WifiDisplayController:  contactInfoHash : null
08-31 16:50:36.419  3381  3562 D WifiDisplayController:  ssDevInfo : 0
08-31 16:50:36.419  3381  3562 D WifiDisplayController:  iconIdx : 0
,08-31 16:50:36.429  3381  4915 V AlarmManager:  remove PendingIntent] PendingIntent{9565b5f: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:36.429  8864  8864 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-31 16:50:36.429  8864  8864 D LocalBluetoothManager: LocalBluetoothManager :: onInitCallback != null
,08-31 16:50:36.429  3381  3855 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-31 16:50:36.439  9106  9106 D HeadsetProvider: Created cursor android.database.sqlite.SQLiteCursor@7201852
,08-31 16:50:36.439  9106  9106 D HeadsetProvider: setHeadsetDB - Can't find 400 for A8:81:95:E9:5F:XX
,08-31 16:50:36.449  9106  9106 I HeadsetProvider: setHeadsetDB - A8:81:95:E9:5F:XX, 400, 1, true
08-31 16:50:36.449  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
08-31 16:50:36.449  9106  9176 D HeadsetStateMachine: Enter Disconnected: -2, size: 0/0
,08-31 16:50:36.449  9181  9181 E Zygote  : v2
,08-31 16:50:36.449  9181  9181 I libpersona: KNOX_SDCARD checking this for 5010
08-31 16:50:36.449  9181  9181 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
08-31 16:50:36.449  9181  9181 I libpersona: KNOX_SDCARD not a persona
08-31 16:50:36.449  9181  9181 E Zygote  : accessInfo : 0
08-31 16:50:36.449  3381  4411 I ActivityManager: Start proc 9181:com.samsung.android.intelligenceservice2/5010 for broadcast-3 com.samsung.android.intelligenceservice2/com.samsung.android.intelligenceservice.useranalysis.predictor.PlacePredictor$BtConnectionReceiver
08-31 16:50:36.449  9181  9181 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.intelligenceservice2 
08-31 16:50:36.449  3381  4411 I ActivityManager: Killing 8544:com.samsung.android.app.aodservice:settingui/u0a0 (adj 15): DHA:empty #33
,08-31 16:50:36.459  3381  3855 D P2pNetworkAgent: NetworkAgent: NetworkAgent fully connected
08-31 16:50:36.459  3381  3855 D WifiP2pService: InactiveState
08-31 16:50:36.459  3381  3865 E ConnectivityService: updateNetworkInfo()
08-31 16:50:36.459  3381  3865 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = UNKNOWN
08-31 16:50:36.459  3381  3855 D WifiP2pService: InactiveState{ what=143376 }
,08-31 16:50:36.459  3381  3855 E WifiP2pService: Airplane mode : skipped SET_COUNTRY_CODE
08-31 16:50:36.459  3381  3855 D WifiP2pService: P2pEnabledState{ what=143376 }
08-31 16:50:36.459  9106  9106 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Message sending
08-31 16:50:36.459  9106  9106 E HeadsetService: notifyProfileServiceStateChanged
,08-31 16:50:36.459  3381  3975 V AlarmManager:  remove PendingIntent] PendingIntent{2cf44f1: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:36.459  4977  4977 D BluetoothA2dp: Proxy object connected
,08-31 16:50:36.469  3381  3381 D BluetoothA2dp: Proxy object connected
,08-31 16:50:36.469  9106  9106 D A2dpService: Received start request. Starting profile...
,08-31 16:50:36.469  9106  9106 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@46938f2
,08-31 16:50:36.469  9106  9106 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-31 16:50:36.469  9106  9176 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-31 16:50:36.479  3381  3851 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.aodservice, Auto Run ON
08-31 16:50:36.479  9106  9176 D HeadsetStateMachine: map size, before remove : 0
08-31 16:50:36.479  9106  9176 D HeadsetStateMachine: map size, after remove: 0
08-31 16:50:36.479  9181  9181 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:50:36.479  9181  9181 D ActivityThread: Added TimaKeyStore provider
,08-31 16:50:36.479  9106  9106 I bt_bluedroid: get_profile_interface avrcp
,08-31 16:50:36.489  3381  4179 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{754fcab u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ca7f8d6 9181:com.samsung.android.intelligenceservice2/5010}
,08-31 16:50:36.489  3381  4181 V AlarmManager:  remove PendingIntent] PendingIntent{b02cc62: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:36.489  9106  9106 I Avrcp   : No of Audio players :: 1
,08-31 16:50:36.489  9106  9106 I Avrcp   : App Package name is GM
,08-31 16:50:36.489  3381  3461 V AlarmManager:  remove PendingIntent] PendingIntent{4311f3: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:36.499  9181  9181 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,08-31 16:50:36.499  9181  9181 D RelationGraph: garbageCollect()
08-31 16:50:36.499  9106  9106 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in com.android.bluetooth rsrc of package com.google.android.music
,08-31 16:50:36.499  9181  9181 W ResourcesManager: getTopLevelResources: /system/priv-app/intelligenceservice2/intelligenceservice2.apk / 1.0 running in com.samsung.android.intelligenceservice2 rsrc of package com.samsung.android.intelligenceservice2
,08-31 16:50:36.499  9106  9106 D ResourcesManager: For user 0 new overlays fetched Null
08-31 16:50:36.499  3381  4558 V AlarmManager:  remove PendingIntent] PendingIntent{f8deb0: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:36.499  3381  3460 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,08-31 16:50:36.499  9181  9181 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,08-31 16:50:36.499  9106  9106 V Avrcp   : MediaPlayerInfo: mPlayerId=1
08-31 16:50:36.509  9181  9181 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:36.509  3381  3974 V AlarmManager:  remove PendingIntent] PendingIntent{9f0a129: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:36.509  9106  9106 I Avrcp   : No of Video players :: 2
08-31 16:50:36.509  9106  9106 I Avrcp   : Video App Package name is others
,08-31 16:50:36.509  9181  9181 I InjectionManager: Inside getClassLibPath caller 
,08-31 16:50:36.509  9106  9106 W ResourcesManager: getTopLevelResources: /system/app/Photos/Photos.apk / 1.0 running in com.android.bluetooth rsrc of package com.google.android.apps.photos
,08-31 16:50:36.509  3381  3460 V AlarmManager:  remove PendingIntent] PendingIntent{b454cae: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:36.509  9181  9181 W System  : ClassLoader referenced unknown path: /system/priv-app/intelligenceservice2/lib/arm64
,08-31 16:50:36.509  3381  4771 V AlarmManager:  remove PendingIntent] PendingIntent{672da4f: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:36.509  9181  9181 D UserAnalysis.Provider: PlaceProvider onCreate()
,08-31 16:50:36.519  3381  3461 V AlarmManager:  remove PendingIntent] PendingIntent{58535dc: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:36.519  3381  4773 V AlarmManager:  remove PendingIntent] PendingIntent{44926e5: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:36.519  3381  4558 V AlarmManager:  remove PendingIntent] PendingIntent{71d85ba: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:36.519  3381  4179 V AlarmManager:  remove PendingIntent] PendingIntent{e2ccc6b: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:36.529  3381  4915 V AlarmManager:  remove PendingIntent] PendingIntent{51dd3c8: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:36.529  9181  9181 D UserAnalysis.Secu: Key for secure DB is newly created
08-31 16:50:36.529  3381  3974 V AlarmManager:  remove PendingIntent] PendingIntent{8ea4c61: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
08-31 16:50:36.529  9181  9181 D UserAnalysis.SDBH: SecurePlaceDbHelper() 
08-31 16:50:36.529  9181  9181 D UserAnalysis: Create SecureDbHelper
08-31 16:50:36.529  3381  4428 V AlarmManager:  remove PendingIntent] PendingIntent{30e4386: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
08-31 16:50:36.529  3381  3975 V AlarmManager:  remove PendingIntent] PendingIntent{549c447: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:36.539  9181  9181 D UserAnalysis.App: onCreate()
,08-31 16:50:36.539  9181  9181 D InjectionManager: InjectionManager
08-31 16:50:36.539  9181  9181 D InjectionManager: fillFeatureStoreMap com.samsung.android.intelligenceservice2
08-31 16:50:36.539  9181  9181 I InjectionManager: Constructor com.samsung.android.intelligenceservice2, Feature store :{}
,08-31 16:50:36.539  9181  9181 I InjectionManager: featureStore :{}
,08-31 16:50:36.539  9181  9181 D UserAnalysis.App: no applications having user consent for prediction
08-31 16:50:36.539  3381  4419 V AlarmManager:  remove PendingIntent] PendingIntent{206474: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
08-31 16:50:36.539  3381  4771 I ActivityManager: Killing 8198:com.google.android.talk/u0a117 (adj 15): DHA:empty #33
,08-31 16:50:36.549  3381  4771 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{754fcab u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f2760c6 9106:com.android.bluetooth/1002}
,08-31 16:50:36.549  9181  9181 V PlaceDetection v1.0.29 : [PlaceDetection::stopService] Service stopped.
,08-31 16:50:36.549  3381  3851 V AlarmManager:  remove PendingIntent] PendingIntent{21e4d9d: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:36.549  9181  9181 V PlaceDetection v1.0.29 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-31 16:50:36.559  3381  4558 V AlarmManager:  remove PendingIntent] PendingIntent{6fb1212: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:36.559  3381  3460 V AlarmManager:  remove PendingIntent] PendingIntent{4545de3: PendingIntentRecord{d1953e0 com.samsung.android.intelligenceservice2 broadcastIntent}}
,08-31 16:50:36.559  9106  9106 D ResourcesManager: For user 0 new overlays fetched Null
08-31 16:50:36.559  3381  4411 V AlarmManager:  remove PendingIntent] PendingIntent{a972699: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:36.559  9106  9106 V Avrcp   : MediaPlayerInfo: mPlayerId=2
08-31 16:50:36.559  9106  9106 I Avrcp   : Video App Package name is VP
,08-31 16:50:36.559  9106  9106 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungVideoPlayer/SamsungVideoPlayer.apk / 1.0 running in com.android.bluetooth rsrc of package com.samsung.android.video
,08-31 16:50:36.559  3381  4304 V AlarmManager:  remove PendingIntent] PendingIntent{3743d5e: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:36.569  3381  4057 V AlarmManager:  remove PendingIntent] PendingIntent{7e4f53f: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:36.569  9106  9106 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:36.579  9106  9106 V Avrcp   : MediaPlayerInfo: mPlayerId=3
08-31 16:50:36.579  9106  9106 I Avrcp   : Add tempPlayer
08-31 16:50:36.579  9106  9106 V Avrcp   : MediaPlayerInfo: mPlayerId=4
08-31 16:50:36.579  9106  9106 V Avrcp   : no_of_players : 4
08-31 16:50:36.579  9106  9106 I Avrcp   : Total no of players: 4
08-31 16:50:36.579  9106  9106 V Avrcp   : Samsung player is the 1st player
08-31 16:50:36.579  9106  9106 D Avrcp   : Compose Browsing Service Candidate
,08-31 16:50:36.579  9106  9106 D Avrcp   : ResolveInfo info ResolveInfo{8b9727f com.google.android.music/.browse.MediaBrowserService m=0x108000}
08-31 16:50:36.579  9106  9106 D Avrcp   : Initialize Media Controller
08-31 16:50:36.579  3381  4057 D ActivityManager: isAutoRunBlockedApp:: com.google.android.talk, Auto Run ON
,08-31 16:50:36.579  9106  9106 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-31 16:50:36.579  9106  9106 E Avrcp   : getActiveSessions
08-31 16:50:36.579  9106  9106 D Avrcp   : pick active media Controller
08-31 16:50:36.579  9106  9106 D Avrcp   : Get the active Media Controller 
08-31 16:50:36.579  9106  9106 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-31 16:50:36.579  9106  9106 D A2dpStateMachine: make
,08-31 16:50:36.579  9106  9106 I bt_bluedroid: get_profile_interface a2dp
,08-31 16:50:36.579  9106  9106 E bt_btif : warning : media task started media_task_refcnt 1 
,08-31 16:50:36.579  3381  3851 V AlarmManager:  remove PendingIntent] PendingIntent{cefce0c: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:36.589  9106  9195 D A2dpStateMachine: Enter Disconnected: -2
,08-31 16:50:36.589  9106  9106 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Message sending
08-31 16:50:36.589  9106  9106 E A2dpService: notifyProfileServiceStateChanged
,08-31 16:50:36.589  3381  4419 V AlarmManager:  remove PendingIntent] PendingIntent{5d1bef8: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:36.589  9106  9106 I BluetoothHidServiceJni: classInitNative: succeeds
,08-31 16:50:36.589  3381  4411 V AlarmManager:  remove PendingIntent] PendingIntent{e4e0fd1: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:36.589  9106  9106 D HidService: Received start request. Starting profile...
,08-31 16:50:36.589  9106  9106 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@46938f2
08-31 16:50:36.589  9106  9106 I bt_bluedroid: get_profile_interface hidhost
08-31 16:50:36.589  9106  9106 D HidService: setHidService(): set to: null
08-31 16:50:36.589  9106  9106 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, Message sending
08-31 16:50:36.589  9106  9106 E HidService: notifyProfileServiceStateChanged
,08-31 16:50:36.589  9106  9106 D HeadsetStateMachine: Try to query the phonestate on bind
08-31 16:50:36.589  3381  4179 I Telecom : BluetoothPhoneService: queryPhoneState
08-31 16:50:36.589  3381  4179 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState : true
08-31 16:50:36.589  9106  9106 I BluetoothHealthServiceJni: classInitNative: succeeds
08-31 16:50:36.589  3381  4181 V AlarmManager:  remove PendingIntent] PendingIntent{cb49a36: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:36.589  9106  9106 D HealthService: Received start request. Starting profile...
08-31 16:50:36.589  9106  9106 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@46938f2
,08-31 16:50:36.599  9106  9106 I bt_bluedroid: get_profile_interface health
08-31 16:50:36.599  9106  9106 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, Message sending
08-31 16:50:36.599  9106  9106 E HealthService: notifyProfileServiceStateChanged
08-31 16:50:36.599  9106  9106 D HeadsetStateMachine: Proxy object connected
08-31 16:50:36.599  3381  3461 V AlarmManager:  remove PendingIntent] PendingIntent{ba64d37: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:36.599  9106  9106 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-31 16:50:36.599  3381  4411 V AlarmManager:  remove PendingIntent] PendingIntent{dfd2a4: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
08-31 16:50:36.599  9106  9176 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-31 16:50:36.599  9106  9176 E HeadsetStateMachine: Unknown message: 11
08-31 16:50:36.599  9106  9106 I BluetoothPanServiceJni: classInitNative(L113): succeeds
,08-31 16:50:36.599  3381  3381 D BluetoothPan: BluetoothPAN Proxy object connected
,08-31 16:50:36.599  3946  3946 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 16:50:36.599  8864  8864 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 16:50:36.599  3946  3946 D PanProfile: Bluetooth service connected
08-31 16:50:36.599  8864  8864 D PanProfile: Bluetooth service connected
,08-31 16:50:36.609  9106  9106 D PanService: Received start request. Starting profile...
,08-31 16:50:36.609  9106  9106 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@46938f2
08-31 16:50:36.609  9106  9106 D BluetoothPanServiceJni: initializeNative(L118): pan
08-31 16:50:36.609  3381  4773 V AlarmManager:  remove PendingIntent] PendingIntent{52d80d: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
08-31 16:50:36.609  9106  9106 I bt_bluedroid: get_profile_interface pan
,08-31 16:50:36.609  9106  9106 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, Message sending
08-31 16:50:36.609  9106  9106 E PanService: notifyProfileServiceStateChanged
,08-31 16:50:36.609  9106  9106 D BluetoothMapService: Received start request. Starting profile...
08-31 16:50:36.609  9106  9106 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@46938f2
08-31 16:50:36.609  3381  4304 V AlarmManager:  remove PendingIntent] PendingIntent{82823c2: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:36.609  9106  9106 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Message sending
08-31 16:50:36.609  9106  9106 E BluetoothMapService: notifyProfileServiceStateChanged
08-31 16:50:36.609  9106  9106 D HeadsetPhoneState: sendDeviceDataStateChanged
08-31 16:50:36.609  9106  9106 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-31 16:50:36.609  9106  9176 D HeadsetStateMachine: Disconnected process message: 19, size: 0
08-31 16:50:36.609  9106  9176 E HeadsetStateMachine: Unknown message: 19
,08-31 16:50:36.609  9106  9106 V SapService: SapBinder()
,08-31 16:50:36.609  3946  3946 D BluetoothSap: Proxy object connected
08-31 16:50:36.609  3381  3461 V AlarmManager:  remove PendingIntent] PendingIntent{c4bac2f: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:36.609  3946  3946 D SapProfile: Bluetooth service connected
08-31 16:50:36.619  9106  9106 D SapService: Received start request. Starting profile...
08-31 16:50:36.619  9106  9106 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@46938f2
08-31 16:50:36.619  9106  9106 V SapService: start()
08-31 16:50:36.619  8864  8864 D BluetoothSap: Proxy object connected
08-31 16:50:36.619  9106  9106 D SapService: Disable sap : false
08-31 16:50:36.619  8864  8864 D SapProfile: Bluetooth service connected
,08-31 16:50:36.619  9106  9106 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=12, Message sending
08-31 16:50:36.619  9106  9106 E SapService: notifyProfileServiceStateChanged
,08-31 16:50:36.619  3381  4304 V AlarmManager:  remove PendingIntent] PendingIntent{cf0dc4b: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:36.619  3381  3460 V AlarmManager:  remove PendingIntent] PendingIntent{2aed628: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:36.619  3381  4773 V AlarmManager:  remove PendingIntent] PendingIntent{4a18f41: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:36.619  9106  9106 D BleAudioService: Received start request. Starting profile...
08-31 16:50:36.619  9106  9106 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@46938f2
08-31 16:50:36.619  9106  9106 E DualScoManager: Dual Sco Manager already instantiated
08-31 16:50:36.619  9106  9106 I BtBleAudio.JNI: classInitNative(L304): succeeds
08-31 16:50:36.619  9106  9106 D BleAudioStateMachine: make
,08-31 16:50:36.619  9106  9106 I BleAudioStateMachine: Constructor Of BleAudioStateMachine
,08-31 16:50:36.619  9106  9106 D BtBleAudio.JNI: initializeNative(L309): ble audio jni initializeNative: 0
08-31 16:50:36.619  9106  9106 I bt_bluedroid: get_profile_interface bleaudio_source
08-31 16:50:36.619  9106  9106 D BleAudioStateMachine: make
08-31 16:50:36.619  9106  9200 E BleAudioStateMachine_L: Enter Disconnected: -2
,08-31 16:50:36.629  9106  9106 I BleAudioStateMachine: Constructor Of BleAudioStateMachine
08-31 16:50:36.629  9106  9106 D BtBleAudio.JNI: initializeNative(L309): ble audio jni initializeNative: 1
08-31 16:50:36.629  9106  9106 V BleAudioService: [registerCallStateListener]
08-31 16:50:36.629  9106  9201 E BleAudioStateMachine_R: Enter Disconnected: -2
08-31 16:50:36.629  3381  3851 V AlarmManager:  remove PendingIntent] PendingIntent{fb5fce6: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:36.629  9106  9106 V BleAudioService: [registerAobleStateChangeListener]
08-31 16:50:36.629  3381  3975 V AlarmManager:  remove PendingIntent] PendingIntent{36ef227: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:36.629  9106  9106 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.broadcom.bt.service.bleaudio.BleAudioService, state=12, Message sending
08-31 16:50:36.629  9106  9106 E BleAudioService: notifyProfileServiceStateChanged
,08-31 16:50:36.629  9106  9106 E BluetoothAdapterService: handleMessage() - Message: 1
08-31 16:50:36.629  9106  9106 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Before synchronized
,08-31 16:50:36.629  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
08-31 16:50:36.629  9106  9106 V BluetoothAdapterState: isTurningOff()=false
08-31 16:50:36.629  9106  9106 V BluetoothAdapterState: isTurningOn()=true
,08-31 16:50:36.629  9106  9106 V BluetoothAdapterState: isBleTurningOn()=false
08-31 16:50:36.629  9106  9106 V BluetoothAdapterState: isBleTurningOff()=false
08-31 16:50:36.629  9106  9106 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-31 16:50:36.629  9106  9176 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-31 16:50:36.629  9106  9106 E BluetoothAdapterService: handleMessage() - Message: 1
08-31 16:50:36.629  9106  9106 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Before synchronized
,08-31 16:50:36.629  9106  9176 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-31 16:50:36.629  9106  9176 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-31 16:50:36.629  9106  9176 E HeadsetStateMachine: Unknown message: 11
08-31 16:50:36.629  9106  9106 V BluetoothAdapterState: isTurningOff()=false
08-31 16:50:36.629  9106  9106 V BluetoothAdapterState: isTurningOn()=true
08-31 16:50:36.629  9106  9106 V BluetoothAdapterState: isBleTurningOn()=false
08-31 16:50:36.629  9106  9106 V BluetoothAdapterState: isBleTurningOff()=false
08-31 16:50:36.629  9106  9106 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-31 16:50:36.629  9106  9106 D HeadsetPhoneState: sendDeviceDataStateChanged
08-31 16:50:36.629  9106  9106 D HeadsetPhoneState: Signal level : previous=0 curr=0,
08-31 16:50:36.629  9106  9176 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-31 16:50:36.629  9106  9106 E BluetoothAdapterService: handleMessage() - Message: 1
08-31 16:50:36.629  9106  9106 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, Before synchronized
,08-31 16:50:36.629  9106  9176 E HeadsetStateMachine: Unknown message: 11
08-31 16:50:36.629  9106  9176 D HeadsetStateMachine: Disconnected process message: 19, size: 0
08-31 16:50:36.629  9106  9176 E HeadsetStateMachine: Unknown message: 19
08-31 16:50:36.639  9106  9106 V BluetoothAdapterState: isTurningOff()=false
08-31 16:50:36.639  9106  9106 V BluetoothAdapterState: isTurningOn()=true
08-31 16:50:36.639  9106  9106 V BluetoothAdapterState: isBleTurningOn()=false
08-31 16:50:36.639  9106  9106 V BluetoothAdapterState: isBleTurningOff()=false
08-31 16:50:36.639  9106  9106 D BluetoothAdapterService: HID Host service started
,08-31 16:50:36.649  9202  9202 E Zygote  : v2
08-31 16:50:36.649  9202  9202 I libpersona: KNOX_SDCARD checking this for 10125
08-31 16:50:36.649  9202  9202 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
08-31 16:50:36.649  9202  9202 I libpersona: KNOX_SDCARD not a persona
,08-31 16:50:36.649  3381  3461 I ActivityManager: Start proc 9202:com.google.android.apps.maps/u0a125 for broadcast-3 com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
08-31 16:50:36.649  9202  9202 E Zygote  : accessInfo : 0
08-31 16:50:36.649  9202  9202 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.maps 
,08-31 16:50:36.649  3946  4130 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CONNECTION_HID_HOST
,08-31 16:50:36.649  8864  8864 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CONNECTION_HID_HOST
,08-31 16:50:36.659  3381  3460 V AlarmManager:  remove PendingIntent] PendingIntent{9ce89c3: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:36.659  3946  4130 D BluetoothMap: Create BluetoothMap proxy object
,08-31 16:50:36.659  9106  9106 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-31 16:50:36.659  9106  9106 E BluetoothAdapterService: handleMessage() - Message: 1
08-31 16:50:36.659  9106  9106 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, Before synchronized
,08-31 16:50:36.659  9106  9106 V BluetoothAdapterState: isTurningOff()=false
08-31 16:50:36.659  9106  9106 V BluetoothAdapterState: isTurningOn()=true
08-31 16:50:36.659  9106  9106 V BluetoothAdapterState: isBleTurningOn()=false
08-31 16:50:36.659  9106  9106 V BluetoothAdapterState: isBleTurningOff()=false
08-31 16:50:36.659  9106  9106 E BluetoothAdapterService: handleMessage() - Message: 1
08-31 16:50:36.659  9106  9106 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, Before synchronized
08-31 16:50:36.659  8864  8864 D BluetoothMap: Create BluetoothMap proxy object
,08-31 16:50:36.659  9106  9106 V BluetoothAdapterState: isTurningOff()=false
08-31 16:50:36.659  9106  9106 V BluetoothAdapterState: isTurningOn()=true
08-31 16:50:36.659  9106  9106 V BluetoothAdapterState: isBleTurningOn()=false
08-31 16:50:36.659  9106  9106 V BluetoothAdapterState: isBleTurningOff()=false
08-31 16:50:36.659  9106  9106 E BluetoothAdapterService: handleMessage() - Message: 1
08-31 16:50:36.659  9106  9106 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Before synchronized
,08-31 16:50:36.659  9106  9106 V BluetoothAdapterState: isTurningOff()=false
08-31 16:50:36.659  9106  9106 V BluetoothAdapterState: isTurningOn()=true
08-31 16:50:36.659  9106  9106 V BluetoothAdapterState: isBleTurningOn()=false
08-31 16:50:36.659  9106  9106 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 16:50:36.659  9106  9106 E BluetoothAdapterService: handleMessage() - Message: 1
08-31 16:50:36.659  9106  9106 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=12, Before synchronized
,08-31 16:50:36.659  3381  3460 V AlarmManager:  remove PendingIntent] PendingIntent{f43426c: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:36.669  9106  9106 V BluetoothAdapterState: isTurningOff()=false
08-31 16:50:36.669  9106  9106 V BluetoothAdapterState: isTurningOn()=true
08-31 16:50:36.669  9106  9106 V BluetoothAdapterState: isBleTurningOn()=false
08-31 16:50:36.669  9106  9106 V BluetoothAdapterState: isBleTurningOff()=false
08-31 16:50:36.669  9106  9106 D BleAudioService: [onCallStateChanged] ENTER -- State: (0)
08-31 16:50:36.669  9106  9106 D BleAudioService: [onCallStateChanged] No devices in connected state
08-31 16:50:36.669  9106  9106 D BleAudioService: [onCallStateChanged][PHONECALL STATE Changed]: EXIT
08-31 16:50:36.669  9106  9106 E BluetoothAdapterService: handleMessage() - Message: 1
08-31 16:50:36.669  9106  9106 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.bleaudio.BleAudioService, state=12, Before synchronized
,08-31 16:50:36.669  9106  9106 V BluetoothAdapterState: isTurningOff()=false
08-31 16:50:36.669  9106  9106 V BluetoothAdapterState: isTurningOn()=true
08-31 16:50:36.669  9106  9106 V BluetoothAdapterState: isBleTurningOn()=false
08-31 16:50:36.669  9106  9106 V BluetoothAdapterState: isBleTurningOff()=false
08-31 16:50:36.669  9106  9134 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_STARTED
,08-31 16:50:36.669  9202  9202 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:50:36.669  9202  9202 D ActivityThread: Added TimaKeyStore provider
,08-31 16:50:36.669  9106  9134 E BluetoothServiceJni: enableBrEdrNative:
08-31 16:50:36.669  9106  9134 I bt_bluedroid: enable_bredr
,08-31 16:50:36.669  3381  4179 V AlarmManager:  remove PendingIntent] PendingIntent{cbf4cca: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:36.679  3381  4915 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{754fcab u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5156e3b 9202:com.google.android.apps.maps/u0a125}
,08-31 16:50:36.679  9106  9138 I bt_bta_hh: BTA_HhEnable sec_mask:0x24 p_cback:0xf3ad3f29
08-31 16:50:36.679  9106  9138 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x100048
08-31 16:50:36.679  9106  9138 D BluetoothAdapterProperties: Address is:A8:81:95:E9:5F:6F
08-31 16:50:36.679  9106  9138 E BluetoothServiceJni: populateRssiValuesNative
08-31 16:50:36.679  9106  9138 I bt_bluedroid: getModelRssiValues
08-31 16:50:36.679  9106  9138 E BluetoothServiceJni: model_rssi_values_callback: low = -75, mid = -65, high = 127
08-31 16:50:36.679  9106  9138 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -75,-65,127
08-31 16:50:36.679  9106  9157 D CODEC_IF: codec_if_open: opening libbt-codec_aptx.so...
08-31 16:50:36.689  8864  8864 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
,08-31 16:50:36.689  3946  3946 D BluetoothMap: Proxy object connected
08-31 16:50:36.689  3946  3946 D MapProfile: Bluetooth service connected
,08-31 16:50:36.689  3946  3946 D BluetoothMap: getConnectedDevices()
,08-31 16:50:36.689  9106  9138 D BluetoothAdapterProperties: Name is: Samsung Galaxy S7 edge
,08-31 16:50:36.689  3381  3381 D SettingsProvider: isChangeAllowed() : name = bluetooth_name
,08-31 16:50:36.689  3946  3946 D BluetoothMap: Bluetooth is Not enabled
,08-31 16:50:36.689  9106  9157 D CODEC_IF_MOD: codec_open: codec_open
08-31 16:50:36.689  9106  9157 D CODEC_IF_MOD: codec_open: apt-x encoder initialized successfully
08-31 16:50:36.689  9106  9157 D CODEC_IF_MOD: codec_open:    version : 1.0.1.0
,08-31 16:50:36.689  9106  9157 D CODEC_IF_MOD: codec_open:    build : Android_JB_4.2.2
08-31 16:50:36.689  9106  9157 D CODEC_IF: codec_if_open: codec module opened (v0.1
,08-31 16:50:36.689  9106  9157 D CODEC_IF: codec_if_close: codec_if_close hdl -283836412
08-31 16:50:36.689  9106  9157 D CODEC_IF_MOD: codec_close: codec_close
08-31 16:50:36.689  9106  9157 D CODEC_IF_MOD: codec_close: freed apt-x encoder
08-31 16:50:36.689  9106  9157 D         : Codec ==> check 96kHz mode : check_sshd_encoder_available:332
,08-31 16:50:36.689  9106  9157 D CODEC_IF: codec_if_open: opening libbt-codec_sshd.so...
,08-31 16:50:36.699  9106  9157 D CODEC_IF_SSHD: codec_open: codec_open
08-31 16:50:36.699  9106  9157 D CODEC_IF_SSHD: Codec ==> pcm_info.sampling_freq : 96000
08-31 16:50:36.699  9106  9157 D CODEC_IF_SSHD: codec_open: SSHD encoder initialized successfully
08-31 16:50:36.699  9106  9157 D CODEC_IF: codec_if_open: codec module opened (v0.1
08-31 16:50:36.699  9106  9157 D CODEC_IF: codec_if_close: codec_if_close hdl -580702848
08-31 16:50:36.699  9106  9157 D CODEC_IF_SSHD: codec_close: codec_close
08-31 16:50:36.699  9106  9157 D         : Codec ==> copy capability info [bta_av_co_audio_init:559]
08-31 16:50:36.699  9106  9157 D CODEC_IF: codec_if_open: opening libbt-codec_aptx.so...
,08-31 16:50:36.699  9106  9157 D CODEC_IF_MOD: codec_open: codec_open
08-31 16:50:36.709  9106  9157 D CODEC_IF_MOD: codec_open: apt-x encoder initialized successfully
08-31 16:50:36.709  9106  9157 D CODEC_IF_MOD: codec_open:    version : 1.0.1.0
08-31 16:50:36.709  9106  9157 D CODEC_IF_MOD: codec_open:    build : Android_JB_4.2.2
08-31 16:50:36.709  9106  9157 D CODEC_IF: codec_if_open: codec module opened (v0.1
08-31 16:50:36.709  9106  9157 D CODEC_IF: codec_if_close: codec_if_close hdl -283836412
08-31 16:50:36.709  9106  9157 D CODEC_IF_MOD: codec_close: codec_close
08-31 16:50:36.709  9106  9157 D CODEC_IF_MOD: codec_close: freed apt-x encoder
08-31 16:50:36.709  9106  9157 D         : Codec ==> check 96kHz mode : check_sshd_encoder_available:332
,08-31 16:50:36.709  9106  9157 D CODEC_IF: codec_if_open: opening libbt-codec_sshd.so...
08-31 16:50:36.709  9106  9157 D CODEC_IF_SSHD: codec_open: codec_open
08-31 16:50:36.709  9106  9157 D CODEC_IF_SSHD: Codec ==> pcm_info.sampling_freq : 96000
08-31 16:50:36.709  9106  9157 D CODEC_IF_SSHD: codec_open: SSHD encoder initialized successfully
08-31 16:50:36.709  9106  9157 D CODEC_IF: codec_if_open: codec module opened (v0.1
,08-31 16:50:36.709  9106  9157 D CODEC_IF: codec_if_close: codec_if_close hdl -580702848
08-31 16:50:36.709  9106  9157 D CODEC_IF_SSHD: codec_close: codec_close
08-31 16:50:36.709  9106  9157 D         : Codec ==> copy capability info [bta_av_co_audio_init:559]
,08-31 16:50:36.709  9106  9138 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-31 16:50:36.709  9106  9138 D BluetoothAdapterProperties: Scan Mode:20
08-31 16:50:36.709  9106  9138 D BluetoothAdapterProperties: Discoverable Timeout:-1
,08-31 16:50:36.709  9106  9138 E bt_btif : btif_handle_bluetooth_enable_evt
08-31 16:50:36.709  9106  9138 E bt_btif : ANT+ socket does not initialize.
,08-31 16:50:36.709  8864  8864 D LocalBluetoothProfileManager: Adding local BleAudio profile
,08-31 16:50:36.709  3381  4915 V AlarmManager:  remove PendingIntent] PendingIntent{dd569b3: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:36.709  9202  9202 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
08-31 16:50:36.709  9202  9202 D RelationGraph: garbageCollect()
,08-31 16:50:36.709  9106  9138 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-31 16:50:36.709  8864  8864 D BluetoothLeAudio: getProfileProxy()
08-31 16:50:36.709  9106  9138 D IOP_DB_BT: db_open: db_open : handle 4087775248l, read 18483 bytes onto local cache
08-31 16:50:36.709  9106  9138 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
08-31 16:50:36.709  9106  9138 D IOP_DB_BT: db_query: result 1
08-31 16:50:36.709  9106  9138 I         : iop_db_open: iop_db_open status 0
08-31 16:50:36.709  9106  9138 E BluetoothAdapterState: stateChangeCallback : 17
08-31 16:50:36.709  9106  9138 E bt_btif : no av cb found, event:0, BTA_ [NonConn-0,  ignored!
08-31 16:50:36.709  9106  9138 E bt_btif : BTM_SetConnectability
08-31 16:50:36.709  9106  9134 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_NATIVE_STARTED
08-31 16:50:36.709  9106  9138 E bt_btif : bta_av_co_get_peer peer index out of bounds:255
08-31 16:50:36.709  9106  9138 E bt_btif : BTA got event 0xe0c
08-31 16:50:36.709  9106  9138 E bt_btif : BTM_SEC_REG[12block availa : sec: 0x36
08-31 16:50:36.709  9106  9138 E bt_btif :                : sec: 0x20b0, service na
08-31 16:50:36.709  9106  9138 E bt_btif : no av control ]: id 27, is_orig 0, psm 0
08-31 16:50:36.709  9106  9138 E bt_btif : warning : no comma into EIR
08-31 16:50:36.709  9106  9138 E bt_btif : bta_dm_eir_update_uuid UUID bit mask=0x0
08-31 16:50:36.709  9106  9138 E bt_btif : no av control ]: id 25, is_orig 1, psm 0
08-31 16:50:36.709  9106  9138 W bt_btif : BTM_SEC_REG[13]: id 25, is_orig 0, psm 0x000f, proto_id 5TER_EVT
08-31 16:50:36.709  9106  9138 E bt_btif : Adding UUID=0x11 : Invalid handle
08-31 16:50:36.709  9106  9138 E bt_btif : Write Extended Inquiry Response to controller
08-31 16:50:36.709  9106  9138 E bt_btif : bta_av_co_audio_peer_init No active peer with this handle 0x0
08-31 16:50:36.719  9106  9138 E bt_btif : Adding UUID=0x1115uuid UUID bit mask=0x0
08-31 16:50:36.719  9106  9138 E bt_btif : no av control block available at state:3
08-31 16:50:36.719  9106  9138 E bt_btif : bta_dm_eir_update_uuid UUID bit mask=0x0
08-31 16:50:36.719  9106  9138 E bt_btif : warning : no command pending, ignore ack
08-31 16:50:36.719  9106  9138 E bt_btif : no av control block available at state:3
08-31 16:50:36.719  9106  9138 E bt_btif : no av control block available at state:2
08-31 16:50:36.719  9106  9138 W bt_btif : btif_av_state_idle_handler : unhandled event:BTA_AV_REGISTER_EVT
08-31 16:50:36.719  9106  9138 E bt_btif : btif_sm_dispatch : Invalid handle
08-31 16:50:36.719  9106  9138 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-31 16:50:36.719  9106  9134 D BluetoothAdapterProperties: ScanMode =  20
08-31 16:50:36.719  9106  9134 D BluetoothAdapterProperties: State =  11
08-31 16:50:36.719  9202  9202 W ResourcesManager: getTopLevelResources: /system/app/Maps/Maps.apk / 1.0 running in com.google.android.apps.maps rsrc of package com.google.android.apps.maps
08-31 16:50:36.719  8726  8726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 16:50:36.729  3381  3975 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
08-31 16:50:36.729  3381  4057 V AlarmManager:  remove PendingIntent] PendingIntent{b401ee9: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:36.729  3381  4179 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
08-31 16:50:36.729  9202  9202 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,08-31 16:50:36.739  3381  4181 D SecContentProvider: insert(), uri = 2
08-31 16:50:36.739  8864  8864 D BluetoothLeAudio: Success to bind to IBluetoothLeAudio with Intent { act=com.broadcom.bt.service.bleaudio.IBluetoothLeAudio cmp=com.android.bluetooth/com.broadcom.bt.service.bleaudio.BleAudioService VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
,08-31 16:50:36.739  9202  9202 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:36.739  9106  9134 D BluetoothAdapterProperties: Setting state to 12
08-31 16:50:36.739  9106  9134 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-31 16:50:36.739  9106  9134 D HeadsetService: setBleAudioService(): com.broadcom.bt.service.bleaudio.BleAudioService@148df75
08-31 16:50:36.739  9106  9134 D A2dpService: setBleAudioService(): com.broadcom.bt.service.bleaudio.BleAudioService@148df75
08-31 16:50:36.739  8864  8864 D BluetoothMap: Proxy object connected
08-31 16:50:36.739  9106  9134 D BleAudioService: setHeadsetService: setting HeadsetService
08-31 16:50:36.739  9106  9134 D BleAudioService: setA2dpService: setting A2dpService
,08-31 16:50:36.739  8864  8864 D MapProfile: Bluetooth service connected
,08-31 16:50:36.739  8864  8864 D BluetoothMap: getConnectedDevices()
,08-31 16:50:36.739  9106  9134 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-31 16:50:36.739  9106  9134 D BluetoothAdapterService: updateAdapterState state is 12
,08-31 16:50:36.739  3381  4411 V AlarmManager:  remove PendingIntent] PendingIntent{c72c0a5: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:36.749  9106  9138 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-31 16:50:36.749  9106  9138 D BluetoothAdapterProperties: Scan Mode:21
08-31 16:50:36.749  9106  9138 D BluetoothAdapterProperties: Discoverable Timeout:-1
,08-31 16:50:36.759  9106  9134 V BluetoothAdapterService: start opp service
,08-31 16:50:36.759  8726  8726 D BluetoothAdapter: STATE_ON
,08-31 16:50:36.759  9202  9202 I InjectionManager: Inside getClassLibPath caller 
,08-31 16:50:36.769  8864  8864 D BluetoothInputDevice: Proxy object connected
,08-31 16:50:36.769  8864  8864 D HidProfile: Bluetooth service connected
,08-31 16:50:36.769  9106  9134 D BluetoothAdapterService: Autoconnection is available 
08-31 16:50:36.769  9106  9134 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-31 16:50:36.769  9106  9134 D BluetoothAdapterService: starting service from this receiver
08-31 16:50:36.769  8864  8875 D BluetoothPan: onBluetoothStateChange on: true
08-31 16:50:36.769  9202  9202 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,08-31 16:50:36.769  3381  3974 V AlarmManager:  remove PendingIntent] PendingIntent{a308888: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:36.779  8726  8726 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-31 16:50:36.789  9106  9134 D BluetoothAdapterService: BT on, init HID DEV count : 0
08-31 16:50:36.789  9106  9134 I BluetoothAdapterState: Entering OnState
,08-31 16:50:36.789  3946  4099 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 16:50:36.789  3946  4099 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 16:50:36.789  9106  9106 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-31 16:50:36.799  8864  8864 D BluetoothLeAudio: Proxy object connected
,08-31 16:50:36.799  8726  8726 D BluetoothAdapter: STATE_ON
,08-31 16:50:36.799  8864  8864 D BleAudioProfile: Bluetooth service connected
08-31 16:50:36.799  8864  8864 D BluetoothLeAudio: getConnectedDevices()
,08-31 16:50:36.809  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
08-31 16:50:36.809  9118  9118 I wpa_supplicant: nl80211: Received scan results (23 BSSes)
08-31 16:50:36.809  9118  9118 I wpa_supplicant: autoscan_samsung_exponential_notify_scan : scan_interval = 8
08-31 16:50:36.809  9118  9118 I wpa_supplicant: autoscan: autoscan_notify_scan, scan_interval = 8
08-31 16:50:36.809  9118  9118 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-31 16:50:36.809  9118  9118 I wpa_supplicant:    allow  - level is under -85dBm [-43] or selected nid [-1] [0]
08-31 16:50:36.809  9118  9118 I wpa_supplicant:  selected from pick network BSS F4.99.3E ssid='NG700' et= 090,gp=03,cu=987654321,sc=987654321
08-31 16:50:36.809  9118  9118 I wpa_supplicant:    allow  - level is under -85dBm [-43] or selected nid [-1] [0]
08-31 16:50:36.809  9118  9118 I wpa_supplicant: wlan0: Trying to associate with f4:f2:6d:22:99:3e (SSID='NG700' freq=2437 MHz level=-43) 
08-31 16:50:36.819  3152  3630 D Netd    : Iface wlan0 link up
,08-31 16:50:36.819  3381  3528 D Tethering: interfaceLinkStateChanged wlan0, true
08-31 16:50:36.819  3381  3528 D Tethering: interfaceStatusChanged wlan0, true
,08-31 16:50:36.819  3381  3851 V AlarmManager:  remove PendingIntent] PendingIntent{7295f5d: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:36.819  4991  5321 D PdnController: Interface Changed wlan0 link up
,08-31 16:50:36.819  4977  4989 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 16:50:36.819  4977  4989 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 16:50:36.819  9106  9106 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,08-31 16:50:36.819  3381  3560 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 16:50:36.819  3381  3560 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 16:50:36.819  8864  8864 D BluetoothPbap: Proxy object connected
,08-31 16:50:36.819  8864  8864 D PbapServerProfile: Bluetooth service connected
,08-31 16:50:36.829  8726  8726 D BluetoothAdapter: STATE_ON
,08-31 16:50:36.829  8726  8736 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 16:50:36.829  8726  8736 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 16:50:36.829  9106  9106 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,08-31 16:50:36.829  4977  4990 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-31 16:50:36.839  8726  8726 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-31 16:50:36.839  4280  4624 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 16:50:36.839  4280  4624 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 16:50:36.839  9106  9106 V BtOppService: isOwner == true
,08-31 16:50:36.839  8864  8875 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-31 16:50:36.849  3381  3560 D BluetoothPan: onBluetoothStateChange on: true
08-31 16:50:36.849  3381  3851 V AlarmManager:  remove PendingIntent] PendingIntent{69a20d2: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:36.859  9106  9218 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 16:50:36.859  9106  9218 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 16:50:36.859  8864  8874 D BluetoothPbap: onBluetoothStateChange: up=true
,08-31 16:50:36.859  8726  8726 D BluetoothAdapter: STATE_ON
08-31 16:50:36.859  3946  3958 D BluetoothMap: onBluetoothStateChange: up=true
,08-31 16:50:36.859  8864  8875 D BluetoothSap: onBluetoothStateChange: up=true
,08-31 16:50:36.859  3381  3974 V AlarmManager:  remove PendingIntent] PendingIntent{a0c25a3: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
08-31 16:50:36.859  8726  8726 D BluetoothAdapter: STATE_ON
,08-31 16:50:36.859  3946  4557 D BluetoothSap: onBluetoothStateChange: up=true
,08-31 16:50:36.869  8864  8874 D BluetoothMap: onBluetoothStateChange: up=true
,08-31 16:50:36.869  8726  8726 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-31 16:50:36.869  4146  4160 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg com.android.bluetooth,id=0,extra=Bundle[mParcelledData.dataSize=160]
08-31 16:50:36.869  4146  4146 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=0, samsung.notification.type=normal, samsung.people.package_name=com.android.bluetooth, samsung.notification.remove_all=true}]
08-31 16:50:36.869  4146  4146 I PeopleStripeService: PeopleNotificationReceiver:3
,08-31 16:50:36.869  8864  8875 D BluetoothLeAudio: onBluetoothStateChange: up=true
,08-31 16:50:36.869  4146  4146 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
,08-31 16:50:36.869  4146  4146 I PeopleDataManager: removeNotification
08-31 16:50:36.869  4146  4146 I NotificationParser: getNotiType:com.android.bluetooth,null
08-31 16:50:36.869  4146  4146 D PeopleDataManager: removeNotiInfo: id =0,packageName=com.android.bluetooth,isEdgeNotification=false,key=null,removeAll=true
08-31 16:50:36.869  4146  4146 D PeopleDataManager: removeNotiInfo =null
08-31 16:50:36.869  3381  4558 V AlarmManager:  remove PendingIntent] PendingIntent{3b178ff: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:36.879  4268  6989 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 16:50:36.879  4268  6989 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 16:50:36.879  8864  8874 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 16:50:36.879  8864  8874 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 16:50:36.879  3381  4057 V AlarmManager:  remove PendingIntent] PendingIntent{9a866cc: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:36.889  4305  4315 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 16:50:36.889  4305  4315 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 16:50:36.889  8433  8443 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 16:50:36.889  8433  8443 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 16:50:36.889  8726  8726 D BluetoothAdapter: STATE_ON
,08-31 16:50:36.889  3946  4797 D BluetoothPan: onBluetoothStateChange on: true
,08-31 16:50:36.889  3381  4915 V AlarmManager:  remove PendingIntent] PendingIntent{4086282: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
08-31 16:50:36.889  3381  3560 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-31 16:50:36.899  3381  3381 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-31 16:50:36.899  3381  3381 I InputMethodManagerService: [BT Setting State] State =12
,08-31 16:50:36.899  8726  8726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 16:50:36.899  8726  8726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 16:50:36.899  8726  8726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 16:50:36.899  8726  8726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 16:50:36.899  8726  8726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 16:50:36.899  8726  8726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 16:50:36.899  8726  8726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 16:50:36.899  8726  8726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 16:50:36.899  3381  3381 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-31 16:50:36.899  8726  8726 D BluetoothAdapter: STATE_ON
08-31 16:50:36.899  4338  4338 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
,08-31 16:50:36.899  8726  8877 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-31 16:50:36.899  8726  8877 I jxcore-log: 
,08-31 16:50:36.899  3381  3381 I Telecom : BluetoothPhoneService: queryPhoneState
08-31 16:50:36.899  3381  3381 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState : true
,08-31 16:50:36.909  8726  8726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 16:50:36.909  3381  3381 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
08-31 16:50:36.909  3381  3381 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 16:50:36.909  3381  3381 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,08-31 16:50:36.909  7104  7104 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-31 16:50:36.909  8864  8864 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,08-31 16:50:36.909  8864  8864 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-31 16:50:36.919  8726  8726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 16:50:36.919  8864  8864 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-31 16:50:36.919  3381  3856 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,08-31 16:50:36.929  8864  8864 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-31 16:50:36.929  3381  4915 V AlarmManager:  remove PendingIntent] PendingIntent{1baeae8: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
08-31 16:50:36.929  3381  3381 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.SCAN_RESULTS
,08-31 16:50:36.929  9106  9106 I BluetoothPbapService: Handler(): got msg=1
,08-31 16:50:36.939  8864  8864 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-31 16:50:36.939  9202  9202 D InjectionManager: InjectionManager
08-31 16:50:36.939  9202  9202 D InjectionManager: fillFeatureStoreMap com.google.android.apps.maps
08-31 16:50:36.939  3381  4771 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
08-31 16:50:36.939  8864  8864 E BluetoothHeadset: BTStateChangeCB is registed
,08-31 16:50:36.939  9202  9202 I InjectionManager: Constructor com.google.android.apps.maps, Feature store :{}
08-31 16:50:36.939  9202  9202 I InjectionManager: featureStore :{}
,08-31 16:50:36.949  3381  4558 V AlarmManager:  remove PendingIntent] PendingIntent{fc7cd94: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:36.949  8864  8864 W LocalBluetoothProfileManager: updateLocalProfiles :: MAP profile was previously added but the UUID is now missing.
,08-31 16:50:36.949  8864  8864 W LocalBluetoothProfileManager: updateLocalProfiles :: PBAP profile was previously added but the UUID is now missing.
08-31 16:50:36.949  8864  8864 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
08-31 16:50:36.949  8864  8864 W LocalBluetoothProfileManager: updateLocalProfiles :: HID profile was previously added but the UUID is now missing.
08-31 16:50:36.949  8864  8864 W LocalBluetoothProfileManager: updateLocalProfiles :: BleAudio profile was created already 
,08-31 16:50:36.959  9106  9233 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-31 16:50:36.959  3381  4419 V AlarmManager:  remove PendingIntent] PendingIntent{e227032: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:36.959  3381  4181 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
08-31 16:50:36.959  3381  3381 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@82c3339
,08-31 16:50:36.959  3381  3381 D BluetoothHeadset: registerMessageListener
,08-31 16:50:36.959  9106  9117 D HeadsetService: registerMessageListener
,08-31 16:50:36.959  9106  9117 D HeadsetService: registerMessageListener
08-31 16:50:36.959  9106  9176 D HeadsetStateMachine: Disconnected process message: 70, size: 0
08-31 16:50:36.959  9106  9176 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@6118fe5
,08-31 16:50:36.959  3381  3381 I Telecom : BluetoothManager : register MessageListener
08-31 16:50:36.969  3381  3381 I Telecom : CallAudioManager: onBluetoothStateChange: no focus
08-31 16:50:36.969  9118  9118 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,08-31 16:50:36.969  3152  3630 D Netd    : Iface wlan0 link up
,08-31 16:50:36.969  3152  3630 D Netd    : Iface wlan0 link up
08-31 16:50:36.969  3152  3630 D Netd    : Iface wlan0 link up
08-31 16:50:36.969  3381  3528 D Tethering: interfaceLinkStateChanged wlan0, true
,08-31 16:50:36.969  3381  3528 D Tethering: interfaceStatusChanged wlan0, true
,08-31 16:50:36.969  4991  5004 D PdnController: Interface Changed wlan0 link up
,08-31 16:50:36.969  9118  9118 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-31 16:50:36.969  3381  3528 D Tethering: interfaceLinkStateChanged wlan0, true
08-31 16:50:36.969  3381  3528 D Tethering: interfaceStatusChanged wlan0, true
08-31 16:50:36.969  9118  9118 I wpa_supplicant: wlan0: WPA: RX message 1 of 4-Way Handshake from F4.99.3E (ver=2)
,08-31 16:50:36.969  9118  9118 I wpa_supplicant: wlan0: WPA: Sending EAPOL-Key 2/4
,08-31 16:50:36.979  3381  3856 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,08-31 16:50:36.989  4991  5012 D PdnController: Interface Changed wlan0 link up
08-31 16:50:36.989  9118  9118 I wpa_supplicant: wlan0: WPA: RX message 3 of 4-Way Handshake from F4.99.3E (ver=2)
,08-31 16:50:36.989  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-31 16:50:36.989  9106  9233 D BluetoothSocket: bindListen(): myUserId = 0
08-31 16:50:36.989  9106  9233 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 16:50:36.989  3381  3528 D Tethering: interfaceLinkStateChanged wlan0, true
,08-31 16:50:36.989  3381  3974 V AlarmManager:  remove PendingIntent] PendingIntent{df62df: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:36.989  3381  3528 D Tethering: interfaceStatusChanged wlan0, true
08-31 16:50:36.989  9118  9118 I wpa_supplicant: wlan0: WPA: Sending EAPOL-Key 4/4
,08-31 16:50:36.989  4991  5321 D PdnController: Interface Changed wlan0 link up
,08-31 16:50:36.989  9118  9118 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 16:50:36.989  3381  3856 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
08-31 16:50:36.989  9118  9118 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-31 16:50:36.989  3152  3630 D Netd    : Iface wlan0 link up
08-31 16:50:36.989  9118  9118 I wpa_supplicant: Blacklist: Clear (temp) 
,08-31 16:50:36.999  3381  3528 D Tethering: interfaceLinkStateChanged wlan0, true
08-31 16:50:36.999  3381  3528 D Tethering: interfaceStatusChanged wlan0, true
,08-31 16:50:36.999  4991  5004 D PdnController: Interface Changed wlan0 link up
,08-31 16:50:36.999  9106  9233 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-31 16:50:37.009  8864  8864 D BluetoothA2dp: Proxy object connected
08-31 16:50:37.009  3381  3856 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-31 16:50:37.009  8864  8864 D A2dpProfile: Bluetooth service connected
,08-31 16:50:37.009  9106  9235 D BluetoothSocket: bindListen(): myUserId = 0
08-31 16:50:37.009  9106  9235 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 16:50:37.019  9236  9236 E Zygote  : v2
08-31 16:50:37.019  9236  9236 I libpersona: KNOX_SDCARD checking this for 10052
08-31 16:50:37.019  9236  9236 E Zygote  : isSdpEnabledProcess - SDP enabled
08-31 16:50:37.019  9236  9236 I libpersona: KNOX_SDCARD not a persona
08-31 16:50:37.019  9236  9236 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,08-31 16:50:37.019  9236  9236 E Zygote  : accessInfo : 64
08-31 16:50:37.019  9236  9236 E Zygote  : isSdpEnabledProcess - SDP enabled
08-31 16:50:37.019  9236  9236 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10052 / [uid]: 10052
08-31 16:50:37.019  9236  9236 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.email.provider 
,08-31 16:50:37.019  3381  4181 I ActivityManager: Start proc 9236:com.samsung.android.email.provider/u0a52 for content provider com.samsung.android.email.provider/.provider.database.EmailProvider
,08-31 16:50:37.019  3381  3854 D NetworkPolicy: isUidForegroundLocked: 10052, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-31 16:50:37.019  3381  4428 V AlarmManager:  remove PendingIntent] PendingIntent{873d38a: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
08-31 16:50:37.019  3946  3946 D BluetoothPbap: Proxy object connected
,08-31 16:50:37.019  3946  3946 D PbapServerProfile: Bluetooth service connected
,08-31 16:50:37.029  3381  3856 V AlarmManager:  remove PendingIntent] PendingIntent{a814dfb: PendingIntentRecord{9f2de18 android broadcastIntent}}
,08-31 16:50:37.029  3381  3856 D WifiNetworkAgent: NetworkAgent: Registering NetworkAgent
,08-31 16:50:37.029  9106  9235 I BtOppRfcommListener: Accept thread started.
08-31 16:50:37.029  3381  3856 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-31 16:50:37.029  9106  9217 D A2dpStateMachine: getConnectedDevices : size=0
08-31 16:50:37.029  3381  3865 D ConnectivityService: Got NetworkAgent Messenger
08-31 16:50:37.029  9106  9218 D A2dpStateMachine: getConnectedDevices : size=0
08-31 16:50:37.029  3381  3865 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 16:50:37.029  3381  3865 E ConnectivityService: updateNetworkInfo()
08-31 16:50:37.029  3381  3865 D ConnectivityService: NetworkAgent connected
,08-31 16:50:37.029  3152  3637 D CommandListener: Setting iface cfg
,08-31 16:50:37.029  3946  4130 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
,08-31 16:50:37.029  8726  8877 I jxcore-log: ERROR runTests: 
08-31 16:50:37.029  8726  8877 I jxcore-log: 
,08-31 16:50:37.039  8726  8877 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-31 16:50:37.039  8726  8877 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"38","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
,08-31 16:50:37.039  8726  8877 I jxcore-log: WARN testUtils: logCallback not set!
08-31 16:50:37.039  8726  8877 I jxcore-log: 
,08-31 16:50:37.039  8726  8877 I jxcore-log: [ { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-31 16:50:37.039  8726  8877 I jxcore-log:     _functionName: 'loadFile',
08-31 16:50:37.039  8726  8877 I jxcore-log:     _lineNumber: '26',
08-31 16:50:37.039  8726  8877 I jxcore-log:     _columnNumber: '11',
08-31 16:50:37.039  8726  8877 I jxcore-log:     _msg: '    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11' },
08-31 16:50:37.039  8726  8877 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-31 16:50:37.039  8726  8877 I jxcore-log:     _functionName: '',
08-31 16:50:37.039  8726  8877 I jxcore-log:     _lineNumber: '38',
08-31 16:50:37.039  8726  8877 I jxcore-log:     _columnNumber: '7',
08-31 16:50:37.039  8726  8877 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7' },
08-31 16:50:37.039  8726  8877 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-31 16:50:37.039  8726  8877 I jxcore-log:     _functionName: '',
08-31 16:50:37.039  8726  8877 I jxcore-log:     _lineNumber: '35',
08-31 16:50:37.039  8726  8877 I jxcore-log:     _columnNumber: '3',
08-31 16:50:37.039  8726  8877 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3' },
08-31 16:50:37.039  8726  8877 I jxcore-log:   { _fileName: 'module.js',
08-31 16:50:37.039  8726  8877 I jxcore-log:     _functionName: '$w.prototype._compile',
08-31 16:50:37.039  8726  8877 I jxcore-log:     _lineNumber: '621',
08-31 16:50:37.039  8726  8877 I jxcore-log:     _columnNumber: '8',
08-31 16:50:37.039  8726  8877 I jxcore-log:     _msg: '    at $w.prototype._compile@module.js:621:8' },
08-31 16:50:37.039  8726  8877 I jxcore-log:   { _fileName: 'module.js',
08-31 16:50:37.039  8726  8877 I jxcore-log:     _functionName: '$w._extensions[".js"]',
08-31 16:50:37.039  8726  8877 I jxcore-log:     _lineNumber: '651',
08-31 16:50:37.039  8726  8877 I jxcore-log:     _columnNumber: '1',
08-31 16:50:37.039  8726  8877 I jxcore-log:    
08-31 16:50:37.039  8726  8877 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-31 16:50:37.039  8726  8877 I jxcore-log: 
08-31 16:50:37.039  8726  8877 E jxcore-log: Error: 
08-31 16:50:37.039  8726  8877 E jxcore-log: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-31 16:50:37.039  8726  8877 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/runTests.js 26:11)
08-31 16:50:37.039  8726  8877 E jxcore-log: 
,08-31 16:50:37.039  8726  8877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 16:50:37.039  8726  8877 I jxcore-log: 
08-31 16:50:37.039  8726  8877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 16:50:37.039  8726  8877 I jxcore-log: 
08-31 16:50:37.039  3381  3381 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
08-31 16:50:37.039  3381  3381 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
08-31 16:50:37.049  8864  8864 D HeadsetProfile: Bluetooth service connected
08-31 16:50:37.049  3381  3381 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
08-31 16:50:37.049  3381  3863 I WifiHs20Service: Message received 5007
,08-31 16:50:37.049  3381  3381 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
,08-31 16:50:37.059  9236  9236 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:50:37.059  9236  9236 D ActivityThread: Added TimaKeyStore provider
,08-31 16:50:37.059  9106  9234 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,08-31 16:50:37.059  4280  4280 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
08-31 16:50:37.059  9106  9234 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,08-31 16:50:37.059  3381  3856 D WifiStateMachine: Start Dhcp Watchdog 1
,08-31 16:50:37.069  3381  3856 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,08-31 16:50:37.069  9202  9223 W System.err: mkdir failed: EEXIST (File exists) : /storage/emulated/0/Android/data/com.google.android.apps.maps/testdata
,08-31 16:50:37.069  9202  9223 W System.err: mkdir failed: EEXIST (File exists) : /data/user/0/com.google.android.apps.maps/app_/testdata
,08-31 16:50:37.079  3381  4304 V AlarmManager:  remove PendingIntent] PendingIntent{94f72de: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
08-31 16:50:37.079  3946  3946 D BluetoothInputDevice: Proxy object connected
,08-31 16:50:37.079  3946  3946 D HidProfile: Bluetooth service connected
,08-31 16:50:37.079  3946  4130 D LocalBluetoothProfileManager: Adding local BleAudio profile
,08-31 16:50:37.079  3381  3856 D WifiNetworkAgent: NetworkAgent: NetworkAgent fully connected
,08-31 16:50:37.079  3946  4130 D BluetoothLeAudio: getProfileProxy()
08-31 16:50:37.079  3381  3865 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
,08-31 16:50:37.089  3381  3460 I ActivityManager: Killing 8271:com.android.providers.calendar/u0a50 (adj 15): DHA:empty #33
,08-31 16:50:37.089  9236  9236 D RelationGraph: garbageCollect()
08-31 16:50:37.089  9236  9236 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,08-31 16:50:37.089  3381  3865 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -43]
,08-31 16:50:37.089  3381  3865 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,08-31 16:50:37.099  9236  9236 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in com.samsung.android.email.provider rsrc of package com.samsung.android.email.provider
,08-31 16:50:37.099  3381  3974 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,08-31 16:50:37.099  9236  9236 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,08-31 16:50:37.099  9236  9236 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:37.099  3381  3523 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{187bcbf u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fdb56ee 8864:com.android.settings/1000}
,08-31 16:50:37.109  9236  9236 I InjectionManager: Inside getClassLibPath caller 
,08-31 16:50:37.109  9253  9253 E Zygote  : v2
08-31 16:50:37.109  9253  9253 I libpersona: KNOX_SDCARD checking this for 5005
08-31 16:50:37.109  9253  9253 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
08-31 16:50:37.109  9253  9253 I libpersona: KNOX_SDCARD not a persona
,08-31 16:50:37.109  9253  9253 E Zygote  : accessInfo : 0
08-31 16:50:37.109  9202  9223 W System.err: mkdir failed: EEXIST (File exists) : /storage/emulated/0/Android/data/com.google.android.apps.maps/cache
08-31 16:50:37.109  9253  9253 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.app.FileShareClient 
,08-31 16:50:37.119  9236  9236 W System  : ClassLoader referenced unknown path: /system/priv-app/SecEmail_M/lib/arm64
,08-31 16:50:37.119  8864  8864 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 16:50:37.119  3381  3523 I ActivityManager: Start proc 9253:com.samsung.android.app.FileShareClient/5005 for broadcast-5 com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver
,08-31 16:50:37.119  3381  3854 D NetworkPolicy: isUidForegroundLocked: 10052, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,08-31 16:50:37.129  9202  9227 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-31 16:50:37.129  3946  3946 D BluetoothLeAudio: Proxy object connected
,08-31 16:50:37.139  3946  3946 D BleAudioProfile: Bluetooth service connected
08-31 16:50:37.139  3946  3946 D BluetoothLeAudio: getConnectedDevices()
,08-31 16:50:37.139  3946  4130 D BluetoothLeAudio: Success to bind to IBluetoothLeAudio with Intent { act=com.broadcom.bt.service.bleaudio.IBluetoothLeAudio cmp=com.android.bluetooth/com.broadcom.bt.service.bleaudio.BleAudioService VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
08-31 16:50:37.139  3381  4411 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 16:50:37.149  3381  4428 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{187bcbf u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4ead505 4977:com.samsung.android.providers.context/u0a9}
,08-31 16:50:37.159  3381  3974 V AlarmManager:  remove PendingIntent] PendingIntent{eea84b7: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:37.159  3381  4419 D ActivityManager: isAutoRunBlockedApp:: com.android.providers.calendar, Auto Run ON
,08-31 16:50:37.159  3946  4130 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
08-31 16:50:37.159  3946  4130 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-31 16:50:37.169  9253  9253 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:50:37.169  9253  9253 D ActivityThread: Added TimaKeyStore provider
08-31 16:50:37.169  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-31 16:50:37.179  3381  3851 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{187bcbf u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{51aad4d 4305:com.google.android.gms.persistent/u0a21}
,08-31 16:50:37.179  4305  4305 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
,08-31 16:50:37.189  3381  4773 D RCPManagerService: exchangeData() failure , invalid userId
08-31 16:50:37.189  3946  4130 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-31 16:50:37.189  9236  9236 D InjectionManager: InjectionManager
08-31 16:50:37.189  9236  9236 D InjectionManager: fillFeatureStoreMap com.samsung.android.email.provider
,08-31 16:50:37.189  9236  9236 I InjectionManager: Constructor com.samsung.android.email.provider, Feature store :{}
08-31 16:50:37.189  9236  9236 I InjectionManager: featureStore :{}
,08-31 16:50:37.189  4146  4161 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg com.google.android.apps.maps,id=10436,extra=Bundle[mParcelledData.dataSize=84]
,08-31 16:50:37.189  4146  4146 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=10436, samsung.notification.type=normal, samsung.people.package_name=com.google.android.apps.maps}]
08-31 16:50:37.189  4146  4146 I PeopleStripeService: PeopleNotificationReceiver:3
08-31 16:50:37.199  4146  4146 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
08-31 16:50:37.199  4146  4146 I PeopleDataManager: removeNotification
08-31 16:50:37.199  4146  4146 I NotificationParser: getNotiType:com.google.android.apps.maps,null
08-31 16:50:37.199  4146  4146 D PeopleDataManager: removeNotiInfo: id =10436,packageName=com.google.android.apps.maps,isEdgeNotification=false,key=null,removeAll=false
08-31 16:50:37.199  4146  4146 D PeopleDataManager: removeNotiInfo =null
,08-31 16:50:37.199  3381  4428 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{4f6ae90 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9986389 9253:com.samsung.android.app.FileShareClient/5005}
08-31 16:50:37.199  3152  3633 D EnterpriseController: netId is 0
08-31 16:50:37.199  3152  3633 D Netd    : getNetworkForDns: using netid 0 for uid 10002
,08-31 16:50:37.199  8864  8864 D DockEventReceiver: finishStartingService: stopping service
,08-31 16:50:37.199  4585  4747 E         : Error communicating to API: https://prod.yana.asideas.de/api/v2/categories
08-31 16:50:37.199  4585  4747 E         : retrofit.RetrofitError: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
08-31 16:50:37.199  4585  4747 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:395)
08-31 16:50:37.199  4585  4747 E         : 	at retrofit.RestAdapter$RestHandler.access$100(RestAdapter.java:220)
08-31 16:50:37.199  4585  4747 E         : 	at retrofit.RestAdapter$RestHandler$1.invoke(RestAdapter.java:265)
08-31 16:50:37.199  4585  4747 E         : 	at retrofit.RxSupport$2.run(RxSupport.java:55)
08-31 16:50:37.199  4585  4747 E         : 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-31 16:50:37.199  4585  4747 E         : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-31 16:50:37.199  4585  4747 E         : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-31 16:50:37.199  4585  4747 E         : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-31 16:50:37.199  4585  4747 E         : 	at retrofit.Platform$Android$2$1.run(Platform.java:142)
08-31 16:50:37.199  4585  4747 E         : 	at java.lang.Thread.run(Thread.java:818)
08-31 16:50:37.199  4585  4747 E         : Caused by: java.net.UnknownHostException: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
08-31 16:50:37.199  4585  4747 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:470)
08-31 16:50:37.199  4585  4747 E         : 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
08-31 16:50:37.199  4585  4747 E         : 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
08-31 16:50:37.199  4585  4747 E         : 	at com.squareup.okhttp.internal.Network$1.resolveInetAddresses(Network.java:29)
08-31 16:50:37.199  4585  4747 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:187)
08-31 16:50:37.199  4585  4747 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.nextProxy(RouteSelector.java:156)
08-31 16:50:37.199  4585  4747 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.next(RouteSelector.java:98)
08-31 16:50:37.199  4585  4747 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.createNextConnection(HttpEngine.java:344)
08-31 16:50:37.199  4585  4747 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:327)
08-31 16:50:37.199  4585  4747 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:245)
08-31 16:50:37.199  4585  4747 E         : 	at com.squareup.okhttp.Call.getResponse(Call.java:267)
08-31 16:50:37.199  4585  4747 E         : 	at com.squareup.okhttp.Call$ApplicationInterceptorChain.proceed(Call.java:224)
08-31 16:50:37.199  4585  4747 E         : 	at com.squareup.okhttp.Call.getResponseWithInterceptorChain(Call.java:195)
08-31 16:50:37.199  4585  4747 E         : 	at com.squareup.okhttp.Call.execute(Call.java:79)
08-31 16:50:37.199  4585  4747 E         : 	at retrofit.client.OkClient.execute(OkClient.java:53)
08-31 16:50:37.199  4585  4747 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:326)
08-31 16:50:37.199  4585  4747 E         : 	... 9 more
08-31 16:50:37.199  4585  4747 E         : Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
08-31 16:50:37.199  4585  4747 E         : 	at libcore.io.Posix.android_getaddrinfo(Native Method)
08-31 16:50:37.199  4585  4747 E         : 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
08-31 16:50:37.199  4585  4747 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:451)
08-31 16:50:37.199  4585  4747 E         : 	... 24 more
08-31 16:50:37.199  4585  4747 E         : 
,08-31 16:50:37.209  9253  9253 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
08-31 16:50:37.209  9253  9253 D RelationGraph: garbageCollect()
,08-31 16:50:37.209  9253  9253 W ResourcesManager: getTopLevelResources: /system/app/AllshareFileShareClient/AllshareFileShareClient.apk / 1.0 running in com.samsung.android.app.FileShareClient rsrc of package com.samsung.android.app.FileShareClient
,08-31 16:50:37.219  3381  4771 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
08-31 16:50:37.219  9253  9253 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,08-31 16:50:37.219  3946  4130 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-31 16:50:37.219  9276  9276 E Zygote  : v2
08-31 16:50:37.219  9276  9276 I libpersona: KNOX_SDCARD checking this for 10052
08-31 16:50:37.219  9276  9276 E Zygote  : isSdpEnabledProcess - SDP enabled
08-31 16:50:37.219  9276  9276 I libpersona: KNOX_SDCARD not a persona
08-31 16:50:37.219  9276  9276 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,08-31 16:50:37.219  9276  9276 E Zygote  : accessInfo : 64
08-31 16:50:37.219  9276  9276 E Zygote  : isSdpEnabledProcess - SDP enabled
08-31 16:50:37.219  9276  9276 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10052 / [uid]: 10052
08-31 16:50:37.219  9276  9276 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.email.provider:service 
,08-31 16:50:37.219  3381  4915 I ActivityManager: Start proc 9276:com.samsung.android.email.provider:service/u0a52 for service com.samsung.android.email.provider/com.samsung.android.email.sync.service.EmailService
,08-31 16:50:37.229  3381  4057 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{187bcbf u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6284b71 8433:com.sec.android.app.shealth:remote/u0a39}
,08-31 16:50:37.229  3381  3856 E WifiNative-wlan0: do suspend false
,08-31 16:50:37.239  3946  3946 D BluetoothA2dp: Proxy object connected
08-31 16:50:37.239  9253  9253 D ResourcesManager: For user 0 new overlays fetched Null
08-31 16:50:37.239  3946  3946 D A2dpProfile: Bluetooth service connected
,08-31 16:50:37.239  3381  4558 V AlarmManager:  remove PendingIntent] PendingIntent{5e77bcb: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:37.239  3381  3856 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
08-31 16:50:37.239  3381  3855 D WifiP2pService: InactiveState{ what=143375 }
,08-31 16:50:37.239  3381  3855 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-31 16:50:37.259  9106  9217 D A2dpStateMachine: getConnectedDevices : size=0
,08-31 16:50:37.259  9289  9289 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-31 16:50:37.259  9289  9289 I dhcpcd  : version 5.5.6 starting
,08-31 16:50:37.259  9289  9289 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
08-31 16:50:37.259  9253  9253 I InjectionManager: Inside getClassLibPath caller 
,08-31 16:50:37.259  9276  9276 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:50:37.259  9276  9276 D ActivityThread: Added TimaKeyStore provider
,08-31 16:50:37.269  9106  9106 D BleAudioService: onReceive:: INTENT mAobleStateChangeListener got : android.bluetooth.adapter.action.STATE_CHANGED
08-31 16:50:37.269  9106  9106 D BleAudioService: BluetoothAdapter.ACTION_STATE_CHANGED,  state is12
,08-31 16:50:37.269  3946  4130 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-31 16:50:37.269  9106  9201 D BleAudioStateMachine_R: [Disconnected] Disconnected process message: 41
08-31 16:50:37.269  9106  9200 D BleAudioStateMachine_L: [Disconnected] Disconnected process message: 41
08-31 16:50:37.269  9106  9200 D BleAudioStateMachine_L: [Disconnected] MSG_ADAPTER_BT_ON_EVT event received
,08-31 16:50:37.269  9106  9201 D BleAudioStateMachine_R: [Disconnected] MSG_ADAPTER_BT_ON_EVT event received
,08-31 16:50:37.269  9106  9200 D BleAudioStateMachine: getLastConnectedDeviceAddress() for channel = 1
08-31 16:50:37.269  9106  9200 D BleAudioService: NotifyEvents: n : 0
,08-31 16:50:37.269  9106  9201 D BleAudioStateMachine: getLastConnectedDeviceAddress() for channel = 2
08-31 16:50:37.269  9106  9201 D BleAudioService: NotifyEvents: n : 0
,08-31 16:50:37.269  3381  4304 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{187bcbf u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fdb56ee 8864:com.android.settings/1000}
,08-31 16:50:37.269  8864  8864 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
08-31 16:50:37.269  8864  8864 D BluetoothStatusReceiver: AdapterStateChanged :: state = 12
08-31 16:50:37.279  9253  9253 W System  : ClassLoader referenced unknown path: /system/app/AllshareFileShareClient/lib/arm64
,08-31 16:50:37.279  9253  9253 D InjectionManager: InjectionManager
08-31 16:50:37.279  9253  9253 D InjectionManager: fillFeatureStoreMap com.samsung.android.app.FileShareClient
,08-31 16:50:37.279  9253  9253 I InjectionManager: Constructor com.samsung.android.app.FileShareClient, Feature store :{}
08-31 16:50:37.279  9253  9253 I InjectionManager: featureStore :{}
,08-31 16:50:37.279  3946  4130 E BluetoothHeadset: BTStateChangeCB is registed
,08-31 16:50:37.279  9253  9253 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-31 16:50:37.289  3946  4130 W LocalBluetoothProfileManager: updateLocalProfiles :: MAP profile was previously added but the UUID is now missing.
08-31 16:50:37.289  3946  4130 W LocalBluetoothProfileManager: updateLocalProfiles :: PBAP profile was previously added but the UUID is now missing.
08-31 16:50:37.289  3946  4130 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
08-31 16:50:37.289  3946  4130 W LocalBluetoothProfileManager: updateLocalProfiles :: HID profile was previously added but the UUID is now missing.
08-31 16:50:37.289  3946  4130 W LocalBluetoothProfileManager: updateLocalProfiles :: BleAudio profile was created already 
,08-31 16:50:37.289  9253  9253 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-31 16:50:37.289  9276  9276 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
08-31 16:50:37.289  9276  9276 D RelationGraph: garbageCollect()
,08-31 16:50:37.299  9276  9276 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in com.samsung.android.email.provider rsrc of package com.samsung.android.email.provider
,08-31 16:50:37.299  9106  9106 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2) for masId0
,08-31 16:50:37.299  3381  4915 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,08-31 16:50:37.299  9276  9276 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,08-31 16:50:37.299  9276  9276 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:37.299  9106  9106 D BluetoothSocket: bindListen(): myUserId = 0
08-31 16:50:37.299  9106  9106 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 16:50:37.309  3381  4304 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{187bcbf u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ca7f8d6 9181:com.samsung.android.intelligenceservice2/5010}
,08-31 16:50:37.309  9276  9276 I InjectionManager: Inside getClassLibPath caller 
,08-31 16:50:37.309  9289  9289 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,08-31 16:50:37.309  9289  9289 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
,08-31 16:50:37.309  9289  9289 I dhcpcd  : bssid match
08-31 16:50:37.309  9289  9289 I dhcpcd  : wlan0: rebinding lease of 192.168.1.107
,08-31 16:50:37.319  9106  9295 D BluetoothSocket: bindListen(): myUserId = 0
08-31 16:50:37.319  9106  9295 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 16:50:37.319  3381  4304 I ActivityManager: Killing 7959:com.samsung.android.scloud:contentsync/5009 (adj 15): DHA:empty #33
,08-31 16:50:37.319  9276  9276 W System  : ClassLoader referenced unknown path: /system/priv-app/SecEmail_M/lib/arm64
,08-31 16:50:37.319  9253  9253 D FileShare-Client: Outbound.stopDelayTimer - 
,08-31 16:50:37.319  3381  4304 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{187bcbf u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f2760c6 9106:com.android.bluetooth/1002}
,08-31 16:50:37.339  3946  4130 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
08-31 16:50:37.339  3946  4195 D BluetoothTile: handleUpdateState :  supported = true, enabled = true, enabling = false, connected = false, connecting = false, mController.getLastDeviceName() = null
08-31 16:50:37.339  3381  3851 D StatusBarManagerService: setIcon slot=bluetooth index=18 icon=StatusBarIcon(icon=Icon(typ=RESOURCE pkg=com.android.systemui id=0x7f02049a) visible user=0 )
,08-31 16:50:37.339  3946  4130 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
08-31 16:50:37.339  3381  3461 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-31 16:50:37.339  3946  3946 W ResourcesManager: getTopLevelResources: /system/priv-app/SystemUI/SystemUI.apk / 1.0 running in com.android.systemui rsrc of package com.android.systemui
,08-31 16:50:37.339  9299  9299 E Zygote  : v2
08-31 16:50:37.339  9299  9299 I libpersona: KNOX_SDCARD checking this for 5005
08-31 16:50:37.339  9299  9299 I libpersona: KNOX_SDCARD not a persona
08-31 16:50:37.339  9299  9299 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,08-31 16:50:37.339  9299  9299 E Zygote  : accessInfo : 0
08-31 16:50:37.339  9299  9299 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.app.FileShareServer 
,08-31 16:50:37.339  3381  4304 I ActivityManager: Start proc 9299:com.samsung.android.app.FileShareServer/5005 for broadcast-5 com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver
,08-31 16:50:37.339  3381  4304 I ActivityManager: Killing 7091:com.osp.app.signin/u0a44 (adj 15): DHA:empty #33
,08-31 16:50:37.349  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-31 16:50:37.349  9106  9295 D BluetoothSdpJni: sdpCreateSapsRecordNative:
08-31 16:50:37.349  3381  4915 V AlarmManager:  remove PendingIntent] PendingIntent{1f009a7: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
08-31 16:50:37.349  9106  9295 D BluetoothSdpJni: SDP Create record success - handle: 0
08-31 16:50:37.349  9106  9106 D BluetoothSocket: bindListen(): myUserId = 0
08-31 16:50:37.349  9106  9106 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 16:50:37.349  9276  9276 I BNRClientProivder, VERSION : 1.7.5: register - xml6 quick_backup : Email, QJ5JBlRnP9, com.samsung.android.email.provider.service.sCloudBNRService
,08-31 16:50:37.349  9276  9276 I QBNRClientHelper: init SyncClientHelper : Email
,08-31 16:50:37.349  3381  4773 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.scloud, Auto Run ON
,08-31 16:50:37.359  9299  9299 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:50:37.359  9299  9299 D ActivityThread: Added TimaKeyStore provider
,08-31 16:50:37.379  9289  9289 I dhcpcd  : wlan0: acknowledged 192.168.1.107 from 192.168.1.1
,08-31 16:50:37.379  9313  9313 E Zygote  : v2
08-31 16:50:37.379  9313  9313 I libpersona: KNOX_SDCARD checking this for 10004
08-31 16:50:37.379  9313  9313 I libpersona: KNOX_SDCARD not a persona
,08-31 16:50:37.379  9313  9313 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
08-31 16:50:37.379  9313  9313 E Zygote  : accessInfo : 0
08-31 16:50:37.379  9313  9313 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.provider.badge 
,08-31 16:50:37.379  3381  3460 I ActivityManager: Start proc 9313:com.sec.android.provider.badge/u0a4 for content provider com.sec.android.provider.badge/.BadgeProvider
,08-31 16:50:37.379  9106  9106 D ObexServerSockets: Succeed to create listening sockets 
08-31 16:50:37.379  9106  9106 D ObexServerSockets: startAccept()
,08-31 16:50:37.389  3381  4304 D ActivityManager: isAutoRunBlockedApp:: com.osp.app.signin, Auto Run ON
08-31 16:50:37.389  9106  9323 D ObexServerSockets: Accepting socket connection for masId0
,08-31 16:50:37.389  3946  3946 D HeadsetProfile: Bluetooth service connected
08-31 16:50:37.389  9106  9324 D ObexServerSockets: Accepting socket connection for masId0
,08-31 16:50:37.389  9106  9106 D BluetoothMapMasInstance: set MAP SDP message type : 1
08-31 16:50:37.389  9106  9106 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-31 16:50:37.389  9106  9106 D BluetoothSdpJni: SDP Create record success - handle: 1
,08-31 16:50:37.399  9106  9106 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@46938f2
08-31 16:50:37.399  9106  9106 D BtConfig.SecureMode: isSecureModeOn:false
,08-31 16:50:37.399  3381  4915 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{4f6ae90 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ecc81fd 9299:com.samsung.android.app.FileShareServer/5005}
,08-31 16:50:37.399  9313  9313 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:50:37.399  9313  9313 D ActivityThread: Added TimaKeyStore provider
,08-31 16:50:37.409  9299  9299 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
08-31 16:50:37.409  9299  9299 D RelationGraph: garbageCollect()
,08-31 16:50:37.409  3381  4181 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{187bcbf u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5156e3b 9202:com.google.android.apps.maps/u0a125}
,08-31 16:50:37.409  9299  9299 W ResourcesManager: getTopLevelResources: /system/app/AllshareFileShareServer/AllshareFileShareServer.apk / 1.0 running in com.samsung.android.app.FileShareServer rsrc of package com.samsung.android.app.FileShareServer
,08-31 16:50:37.409  3381  4771 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,08-31 16:50:37.409  9299  9299 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,08-31 16:50:37.409  9299  9299 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:37.409  9299  9299 I InjectionManager: Inside getClassLibPath caller 
,08-31 16:50:37.409  3381  4915 V AlarmManager:  remove PendingIntent] PendingIntent{35c9ef2: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:37.419  9299  9299 D InjectionManager: InjectionManager
08-31 16:50:37.419  9299  9299 D InjectionManager: fillFeatureStoreMap com.samsung.android.app.FileShareServer
,08-31 16:50:37.419  9299  9299 I InjectionManager: Constructor com.samsung.android.app.FileShareServer, Feature store :{}
08-31 16:50:37.419  9299  9299 I InjectionManager: featureStore :{}
,08-31 16:50:37.419  3381  4181 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8099943 u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e7a02 3946:com.android.systemui/u0a65}
,08-31 16:50:37.439  9289  9289 I dhcpcd  : wlan0: leased 192.168.1.107 for 172800 seconds
,08-31 16:50:37.439  3381  3865 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
,08-31 16:50:37.449  9313  9313 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
08-31 16:50:37.449  9313  9313 D RelationGraph: garbageCollect()
,08-31 16:50:37.449  9313  9313 W ResourcesManager: getTopLevelResources: /system/priv-app/BadgeProvider_M/BadgeProvider_M.apk / 1.0 running in com.sec.android.provider.badge rsrc of package com.sec.android.provider.badge
,08-31 16:50:37.449  3381  4773 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,08-31 16:50:37.449  9313  9313 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,08-31 16:50:37.449  9313  9313 D ResourcesManager: For user 0 new overlays fetched Null
08-31 16:50:37.449  3381  3523 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{59adbc0 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8539eb6 8487:com.enhance.gameservice/u0a111}
,08-31 16:50:37.459  9299  9299 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-31 16:50:37.459  3381  4428 V AlarmManager:  remove PendingIntent] PendingIntent{86440f9: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:37.459  9299  9299 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,08-31 16:50:37.469  9299  9299 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,08-31 16:50:37.469  9313  9313 I InjectionManager: Inside getClassLibPath caller 
,08-31 16:50:37.479  3381  4179 V AlarmManager:  remove PendingIntent] PendingIntent{811b83e: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
08-31 16:50:37.479  9313  9313 W System  : ClassLoader referenced unknown path: /system/priv-app/BadgeProvider_M/lib/arm64
,08-31 16:50:37.479  9313  9313 D BadgeProvider: onCreate
,08-31 16:50:37.479  9313  9313 D BadgeProvider: DatabaseHelper
,08-31 16:50:37.489  9251  9251 I FIPS_bssl: FIPS approved mode (1) | 9251 | app_process
,08-31 16:50:37.489  9251  9251 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-31 16:50:37.489  3381  4419 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 16:50:37.489  9251  9251 D AndroidRuntime: CheckJNI is OFF
,08-31 16:50:37.489  9251  9251 D AndroidRuntime: readGMSProperty: start
08-31 16:50:37.489  9251  9251 D AndroidRuntime: readGMSProperty: already setted!!
08-31 16:50:37.489  9251  9251 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-31 16:50:37.489  3381  4411 I ActivityManager: Start proc 9334:com.sec.android.diagmonagent/1000 for broadcast-5 com.sec.android.diagmonagent/.DiagMonConnectivityChangeReciever
08-31 16:50:37.489  9251  9251 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-31 16:50:37.489  9251  9251 D AndroidRuntime: readGMSProperty: end
08-31 16:50:37.489  9251  9251 D AndroidRuntime: addProductProperty: start
,08-31 16:50:37.499  9334  9334 E Zygote  : v2
08-31 16:50:37.499  9334  9334 I libpersona: KNOX_SDCARD checking this for 1000
08-31 16:50:37.499  9334  9334 I libpersona: KNOX_SDCARD not a persona
,08-31 16:50:37.499  9334  9334 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,08-31 16:50:37.499  9334  9334 E Zygote  : accessInfo : 0
,08-31 16:50:37.499  9276  9276 D InjectionManager: InjectionManager
,08-31 16:50:37.499  9276  9276 D InjectionManager: fillFeatureStoreMap com.samsung.android.email.provider
,08-31 16:50:37.499  9276  9276 I InjectionManager: Constructor com.samsung.android.email.provider, Feature store :{}
08-31 16:50:37.499  9276  9276 I InjectionManager: featureStore :{}
08-31 16:50:37.499  9313  9313 D InjectionManager: InjectionManager
08-31 16:50:37.499  9313  9313 D InjectionManager: fillFeatureStoreMap com.sec.android.provider.badge
,08-31 16:50:37.499  9313  9313 I InjectionManager: Constructor com.sec.android.provider.badge, Feature store :{}
08-31 16:50:37.499  9313  9313 I InjectionManager: featureStore :{}
,08-31 16:50:37.509  3381  4915 V AlarmManager:  remove PendingIntent] PendingIntent{3a2869f: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:37.509  3381  4411 V AlarmManager:  remove PendingIntent] PendingIntent{f31f3ec: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:37.519  3381  4304 V AlarmManager:  remove PendingIntent] PendingIntent{51ef3b5: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
08-31 16:50:37.519  9251  9251 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-31 16:50:37.519  3381  3851 V AlarmManager:  remove PendingIntent] PendingIntent{f6d1a4a: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:37.519  9334  9334 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:50:37.519  9334  9334 D ActivityThread: Added TimaKeyStore provider
,08-31 16:50:37.519  3381  4304 V AlarmManager:  remove PendingIntent] PendingIntent{eb2edbb: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:37.529  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-31 16:50:37.529  3381  3461 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1248000  uid : 1000  pid : 3381  pkgName : BADGE_UPDATE@CPU_MIN@1
,08-31 16:50:37.529  3381  4915 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{59adbc0 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4062d8 9334:com.sec.android.diagmonagent/1000}
,08-31 16:50:37.529  3381  4411 V AlarmManager:  remove PendingIntent] PendingIntent{4981631: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:37.539  9313  9326 D BaseReflect: null getOwnClass TEST
,08-31 16:50:37.539  9313  9326 D MethodReflector: android.content.ContentResolver getClass TEST
08-31 16:50:37.539  9313  9326 D BaseReflect: class android.content.ContentResolver isSupportClass TEST
08-31 16:50:37.539  9313  9326 D BaseReflect: class android.content.ContentResolver getOwnClass TEST
,08-31 16:50:37.539  9251  9251 I Radio-JNI: register_android_hardware_Radio DONE
,08-31 16:50:37.539  9334  9334 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
08-31 16:50:37.539  9334  9334 D RelationGraph: garbageCollect()
,08-31 16:50:37.539  3381  3460 V AlarmManager:  remove PendingIntent] PendingIntent{aa6e46d: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:37.539  9334  9334 W ResourcesManager: getTopLevelResources: /system/priv-app/DiagMonAgent/DiagMonAgent.apk / 1.0 running in com.sec.android.diagmonagent rsrc of package com.sec.android.diagmonagent
,08-31 16:50:37.539  9251  9251 E AffinityControl: AffinityControl: registerfunction enter
,08-31 16:50:37.539  3381  4773 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
08-31 16:50:37.539  9334  9334 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,08-31 16:50:37.549  3381  4428 V AlarmManager:  remove PendingIntent] PendingIntent{bf6a8a2: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:37.549  4132  4132 D CatchNotificationsService: Update badge
,08-31 16:50:37.549  9334  9334 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:37.549  4292  4292 D Launcher.Model: reloadBadges entered.
,08-31 16:50:37.549  5674  5674 D BadgeManager: onChange
,08-31 16:50:37.549  9251  9251 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-31 16:50:37.549  3381  4915 V AlarmManager:  remove PendingIntent] PendingIntent{eb35933: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
08-31 16:50:37.549  9313  9362 D BadgeProvider: query, [selection] : null
,08-31 16:50:37.559  9313  9325 D BadgeProvider: query, [selection] : null
,08-31 16:50:37.559  4292  4381 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.email.provider = 0
08-31 16:50:37.559  4292  4381 D BadgeCache: 1. updateBadgeCounts: com.android.mms = 0
08-31 16:50:37.559  9334  9334 I InjectionManager: Inside getClassLibPath caller 
08-31 16:50:37.559  4292  4381 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 0
08-31 16:50:37.559  4292  4381 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 0
08-31 16:50:37.559  4292  4381 D BadgeCache: 1. updateBadgeCounts: com.sec.android.app.samsungapps = 0
,08-31 16:50:37.559  3381  4428 V AlarmManager:  remove PendingIntent] PendingIntent{7fcb4f0: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:37.559  9334  9334 W System  : ClassLoader referenced unknown path: /system/priv-app/DiagMonAgent/lib/arm64
,08-31 16:50:37.569  3381  3974 D PackageManager: START PACKAGE DELETE: observer{123361897}
08-31 16:50:37.569  3381  3974 D PackageManager: pkg{<packageName>}
08-31 16:50:37.569  3381  3974 D PackageManager: user{0}
08-31 16:50:37.569  3381  3974 D PackageManager: caller{2000}
08-31 16:50:37.569  3381  3974 D PackageManager: flags{2}
08-31 16:50:37.569  3381  3974 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-31 16:50:37.569  3381  3974 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-31 16:50:37.569  3381  3974 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-31 16:50:37.569  3381  3974 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-31 16:50:37.569  3381  3974 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-31 16:50:37.569  3381  3584 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-31 16:50:37.569  3381  3584 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-31 16:50:37.569  3381  3584 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-31 16:50:37.569  3381  3584 D ApplicationPolicy: getApplicationUninstallationEnabled
08-31 16:50:37.569  3381  3584 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-31 16:50:37.569  9313  9326 D MethodReflector: notifyChange is called
08-31 16:50:37.569  3381  4411 V AlarmManager:  remove PendingIntent] PendingIntent{f3aacee: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:37.569  3381  3584 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
08-31 16:50:37.569  3381  3584 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
08-31 16:50:37.569  4132  4132 D CatchNotificationsService: Update badge
,08-31 16:50:37.579  3381  3584 D PackageManager: !@killApplicatoin: 10177, uninstall pkg
08-31 16:50:37.579  3381  3584 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
08-31 16:50:37.579  4292  4292 D Launcher.Model: reloadBadges entered.
08-31 16:50:37.579  3381  3584 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,08-31 16:50:37.579  3381  3851 V AlarmManager:  remove PendingIntent] PendingIntent{ac0558f: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
08-31 16:50:37.579  3381  3523 I ActivityManager: Force stopping com.test.thalitest appid=10177 user=-1: uninstall pkg
,08-31 16:50:37.579  3381  3523 I ActivityManager: Killing 8726:com.test.thalitest/u0a177 (adj 1): stop com.test.thalitest cause uninstall pkg
08-31 16:50:37.579  5674  5674 D BadgeManager: onChange
,08-31 16:50:37.579  3381  3523 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-31 16:50:37.579  3381  3584 D AASAinstall: there is not AASApackages.xml file
,08-31 16:50:37.589  9313  9326 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
08-31 16:50:37.589  9313  9326 D BadgeProvider: sendNotify, [notify] : null
,08-31 16:50:37.589  9313  9326 D BadgeProvider: update, getCallingPackage() : com.samsung.android.email.provider
08-31 16:50:37.589  9313  9326 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
08-31 16:50:37.589  9313  9326 D BadgeProvider: update, [uri.query] : null
08-31 16:50:37.589  9313  9326 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-31 16:50:37.589  9313  9326 D BadgeProvider: update, [UpdateCount] : 1
,08-31 16:50:37.599  3381  5990 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-31 16:50:37.709  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-31 16:50:37.709  3381  4181 D GraphicsStats: Buffer count: 7
08-31 16:50:37.709  3381  4773 I WindowState: WIN DEATH: Window{8c6efbb u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-31 16:50:37.709  3381  4304 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@990301c)
,08-31 16:50:37.709  3381  3865 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:50:37.709  3381  3865 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 16:50:37.709  3009  4336 I SurfaceFlinger: id=18 Removed NainActivit (4/12)
,08-31 16:50:37.709  3381  3865 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 16:50:37.709  3009  3018 I SurfaceFlinger: id=18 Removed NainActivit (-2/12)
,08-31 16:50:37.719  3009  4540 I SurfaceFlinger: id=18 Removed NainActivit (-2/12)
,08-31 16:50:37.769  3381  3584 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,08-31 16:50:37.809  3381  3584 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-31 16:50:37.809  3381  3523 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-31 16:50:37.809  3165  3165 W keystore: ENTER clear_uid from uid 1000 for 10177
,08-31 16:50:37.809  9313  9365 D BadgeProvider: query, [selection] : null
08-31 16:50:37.809  3381  3584 I art     : Starting a blocking GC Explicit
08-31 16:50:37.809  9334  9334 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-31 16:50:37.809  3381  3523 E ActivityManager: Failure starting process com.test.thalitest
08-31 16:50:37.809  3381  3523 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-31 16:50:37.809  3381  3523 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:5277)
08-31 16:50:37.809  3381  3523 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:5194)
08-31 16:50:37.809  3381  3523 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:5032)
08-31 16:50:37.809  3381  3523 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:2643)
08-31 16:50:37.809  3381  3523 E ActivityManager: 	at com.android.server.am.ActivityStack.ensureActivitiesVisibleLocked(ActivityStack.java:2338)
08-31 16:50:37.809  3381  3523 E ActivityManager: 	at com.android.server.am.ActivityStack.ensureActivitiesVisibleLocked(ActivityStack.java:2215)
08-31 16:50:37.809  3381  3523 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.ensureActivitiesVisibleLocked(ActivityStackSupervisor.java:6689)
08-31 16:50:37.809  3381  3523 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:7385)
08-31 16:50:37.809  3381  3523 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:9146)
08-31 16:50:37.809  3381  3523 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:8769)
08-31 16:50:37.809  3381  3523 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:8924)
08-31 16:50:37.809  3381  3523 E ActivityManager: 	at com.android.server.am.ActivityManagerService.access$1000(ActivityManagerService.java:458)
08-31 16:50:37.809  3381  3523 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:2597)
08-31 16:50:37.809  3381  3523 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 16:50:37.809  3381  3523 E ActivityManager: 	at android.os.Looper.loop(Looper.java:158)
08-31 16:50:37.809  3381  3523 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 16:50:37.809  3381  3523 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-31 16:50:37.819  3381  3523 I ActivityManager:   Force finishing activity ActivityRecord{3fbc900 u0 com.test.thalitest/.MainActivity t37}
,08-31 16:50:37.819  3381  3523 W VirtualScreenManagerService: moveTaskBackToDisplayIfNeeded(): top activity or app is null
,08-31 16:50:37.819  3381  3856 E WifiNative-wlan0: do suspend true
,08-31 16:50:37.829  3381  3851 I ActivityManager: Killing 8603:com.android.defcontainer/u0a10 (adj 15): DHA:empty #33
,08-31 16:50:37.829  9313  9363 D BadgeProvider: query, [selection] : null
,08-31 16:50:37.829  3381  3855 D WifiP2pService: InactiveState{ what=143375 }
,08-31 16:50:37.829  3381  3855 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-31 16:50:37.839  3381  4771 V AlarmManager:  remove PendingIntent] PendingIntent{6a8a9fa: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:37.839  3381  3865 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
,08-31 16:50:37.839  4292  4381 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.email.provider = 0
08-31 16:50:37.839  4292  4381 D BadgeCache: 1. updateBadgeCounts: com.android.mms = 0
08-31 16:50:37.839  4292  4381 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 0
08-31 16:50:37.839  4292  4381 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 0
08-31 16:50:37.839  4292  4381 D BadgeCache: 1. updateBadgeCounts: com.sec.android.app.samsungapps = 0
,08-31 16:50:37.849  3381  3856 D WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-31 16:50:37.849  3381  3856 D WifiStateMachine: VerifyingLinkState enter
08-31 16:50:37.849  3381  3865 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -43], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -43]
,08-31 16:50:37.849  3381  4181 D ActivityManager: isAutoRunBlockedApp:: com.android.defcontainer, Auto Run ON
,08-31 16:50:37.859  3381  4915 I ActivityManager: Killing 8364:com.samsung.android.app.appsedge/u0a1 (adj 15): DHA:empty #33
,08-31 16:50:37.859  3381  3381 D WifiNotificationController: SHOW_NOTI_MESSAGE : 9, visible : false, ssid : "NG700", targetSSID : null, netId : -1, titleType : -1
,08-31 16:50:37.859  3381  3865 E ConnectivityService: updateNetworkInfo()
08-31 16:50:37.859  4146  7140 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=17041883,extra=Bundle[mParcelledData.dataSize=84]
08-31 16:50:37.859  4146  4146 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=17041883, samsung.notification.type=normal, samsung.people.package_name=android}]
08-31 16:50:37.859  3946  4130 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
08-31 16:50:37.859  4146  4146 I PeopleStripeService: PeopleNotificationReceiver:3
08-31 16:50:37.859  4146  4146 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
08-31 16:50:37.859  4146  4146 I PeopleDataManager: removeNotification
08-31 16:50:37.859  4146  4146 I NotificationParser: getNotiType:android,null
08-31 16:50:37.859  3381  3975 V AlarmManager:  remove PendingIntent] PendingIntent{af6bbab: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
08-31 16:50:37.859  4146  4146 D PeopleDataManager: removeNotiInfo: id =17041883,packageName=android,isEdgeNotification=false,key=null,removeAll=false
,08-31 16:50:37.859  4146  4146 D PeopleDataManager: removeNotiInfo =null
08-31 16:50:37.859  3381  3865 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}, oldLp = null
08-31 16:50:37.869  3381  3865 D ConnectivityService: Adding iface wlan0 to network 502
,08-31 16:50:37.869  3381  3381 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
08-31 16:50:37.869  3381  3381 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
08-31 16:50:37.869  3381  3381 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
,08-31 16:50:37.869  3381  3863 I WifiHs20Service: Message received 5007
08-31 16:50:37.869  3381  3381 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
,08-31 16:50:37.869  3381  3882 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
08-31 16:50:37.869  3381  3882 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}
08-31 16:50:37.869  3381  3882 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}
08-31 16:50:37.869  3381  3882 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}
08-31 16:50:37.869  3946  4130 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
08-31 16:50:37.869  3381  3882 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}
08-31 16:50:37.869  4280  4280 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,08-31 16:50:37.879  9334  9334 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-31 16:50:37.879  3381  3523 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{97e3208 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4062d8 9334:com.sec.android.diagmonagent/1000}
,08-31 16:50:37.879  9334  9334 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(72/onCreate)] DiagMon DM Application Start !
08-31 16:50:37.879  9334  9334 D InjectionManager: InjectionManager
08-31 16:50:37.879  9334  9334 D InjectionManager: fillFeatureStoreMap com.sec.android.diagmonagent
,08-31 16:50:37.879  9334  9334 I InjectionManager: Constructor com.sec.android.diagmonagent, Feature store :{}
08-31 16:50:37.879  9334  9334 I InjectionManager: featureStore :{}
,08-31 16:50:37.879  9334  9334 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,08-31 16:50:37.879  9334  9334 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
08-31 16:50:37.879  9334  9334 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
08-31 16:50:37.879  9334  9334 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
08-31 16:50:37.879  9334  9334 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,08-31 16:50:37.879  9334  9334 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
08-31 16:50:37.879  9334  9334 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
08-31 16:50:37.879  9334  9334 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
08-31 16:50:37.879  3381  4558 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.appsedge, Auto Run ON
,08-31 16:50:37.889  3381  3865 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 502
,08-31 16:50:37.889  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
08-31 16:50:37.889  3381  3865 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 502
,08-31 16:50:37.889  3381  3882 I WifiManager: isCaptivePortalException
,08-31 16:50:37.889  3381  3865 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 502
,08-31 16:50:37.889  3381  3865 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-31 16:50:37.889  3381  3865 D ConnectivityService: Setting Dns servers for network 502 to [/192.168.1.1]
,08-31 16:50:37.899  9377  9377 E Zygote  : v2
08-31 16:50:37.899  9377  9377 I libpersona: KNOX_SDCARD checking this for 1000
08-31 16:50:37.899  9377  9377 I libpersona: KNOX_SDCARD not a persona
,08-31 16:50:37.899  9377  9377 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,08-31 16:50:37.899  9377  9377 E Zygote  : accessInfo : 0
,08-31 16:50:37.899  3381  4428 I ActivityManager: Start proc 9377:com.sec.knox.switcher/1000 for broadcast-5 com.sec.knox.switcher/.knoxusage.KnoxUsageReceiver
,08-31 16:50:37.899  3381  4181 V AlarmManager:  remove PendingIntent] PendingIntent{829eda1: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:37.909  3381  4428 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{97e3208 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8539eb6 8487:com.enhance.gameservice/u0a111}
,08-31 16:50:37.909  3381  3882 D WifiStateMachine: isPackageRunning - top:com.samsung.android.MtpApplication.USBConnection
,08-31 16:50:37.909  3381  4428 I ActivityManager: Killing 8705:com.samsung.android.app.galaxylabs/u0a17 (adj 15): DHA:empty #33
,08-31 16:50:37.909  9377  9377 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:50:37.909  9377  9377 D ActivityThread: Added TimaKeyStore provider
,08-31 16:50:37.919  3381  4428 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{59adbc0 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bc76bc6 9377:com.sec.knox.switcher/1000}
,08-31 16:50:37.919  3381  3865 V NetworkStats: updateIfacesLocked()
08-31 16:50:37.919  3381  3865 V NetworkStats: performPollLocked(flags=0x1)
,08-31 16:50:37.929  3381  3523 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 72)
08-31 16:50:37.929  3381  3865 V NetworkStats: performPollLocked() took 2ms
08-31 16:50:37.929  3381  3523 W ActivityManager: Failed to clear dns cache for: com.samsung.android.app.galaxylabs
,08-31 16:50:37.939  9377  9377 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
08-31 16:50:37.939  9377  9377 D RelationGraph: garbageCollect()
,08-31 16:50:37.939  3381  3584 I art     : Explicit concurrent mark sweep GC freed 123758(7MB) AllocSpace objects, 6(1960KB) LOS objects, 32% free, 33MB/49MB, paused 1.446ms total 124.383ms
,08-31 16:50:37.939  3381  3865 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 16:50:37.939  3381  3865 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -43]
,08-31 16:50:37.939  3381  3882 D WifiStateMachine: isPackageRunning - top:com.samsung.android.MtpApplication.USBConnection
08-31 16:50:37.939  3381  3865 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
08-31 16:50:37.939  3381  3865 D ConnectivityService: Not required to send intent.
08-31 16:50:37.939  3381  3865 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = CONNECTING
08-31 16:50:37.939  3381  3882 D WifiWatchdogStateMachine: 3Captive portal check should be processed whether SNS option is on or off.
08-31 16:50:37.939  3381  3882 D WifiWatchdogStateMachine.CaptivePortalHandler: [checkCaptivePortal] - callbackHandler=Handler (com.android.server.wifi.WifiWatchdogStateMachine$CaptivePortalHandler) {7be7e52}
08-31 16:50:37.939  3381  3882 I WifiManager: isCaptivePortalException
08-31 16:50:37.939  9377  9377 W ResourcesManager: getTopLevelResources: /system/app/KnoxSwitcher/KnoxSwitcher.apk / 1.0 running in com.sec.knox.switcher rsrc of package com.sec.knox.switcher
,08-31 16:50:37.939  3381  3461 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
08-31 16:50:37.939  9377  9377 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,08-31 16:50:37.939  9377  9377 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:37.939  9377  9377 I InjectionManager: Inside getClassLibPath caller 
,08-31 16:50:37.949  3381  4411 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.galaxylabs, Auto Run ON
08-31 16:50:37.949  9377  9377 W System  : ClassLoader referenced unknown path: /system/app/KnoxSwitcher/lib/arm64
,08-31 16:50:37.949  9377  9377 D KnoxUsageDB: getInstance - KnoxUsageDBHelper
08-31 16:50:37.949  3381  3584 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
08-31 16:50:37.949  9377  9377 D KnoxUsageDB: null == mDbHelperInstance - KnoxUsageDBHelper
08-31 16:50:37.949  3381  3584 D AASAuninstall: userId = 0, info.removedAppID = 10177, info.uid = 10177, packageName = com.test.thalitest
,08-31 16:50:37.949  3381  3584 D AASAinstall: there is not AASApackages.xml file
08-31 16:50:37.949  3381  3584 D PackageManager: result of delete: 1{123361897}
,08-31 16:50:37.949  3381  3854 D NtpTrustedTime: forceRefresh: no connectivity
08-31 16:50:37.949  3381  3584 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-31 16:50:37.949  3381  3584 D PackageManager: userId{-1}
08-31 16:50:37.949  3381  3584 D PackageManager: andCode{true}
,08-31 16:50:37.949  9251  9251 I art     : System.exit called, status: 0
08-31 16:50:37.949  9251  9251 I AndroidRuntime: VM exiting with result code 0.
,08-31 16:50:37.949  3381  3882 D WifiStateMachine: isPackageRunning - top:com.samsung.android.MtpApplication.USBConnection
08-31 16:50:37.949  3381  3851 V AlarmManager:  remove PendingIntent] PendingIntent{c04f523: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
08-31 16:50:37.949  3381  3882 D WifiStateMachine: isPackageRunning - top:com.samsung.android.MtpApplication.USBConnection
08-31 16:50:37.949  9377  9377 D InjectionManager: InjectionManager
08-31 16:50:37.949  9377  9377 D InjectionManager: fillFeatureStoreMap com.sec.knox.switcher
08-31 16:50:37.949  3381  3856 D WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to CONNECTED
,08-31 16:50:37.949  9377  9377 I InjectionManager: Constructor com.sec.knox.switcher, Feature store :{}
08-31 16:50:37.949  9377  9377 I InjectionManager: featureStore :{}
08-31 16:50:37.949  9377  9377 I usagelog: received in receiver
08-31 16:50:37.949  9377  9377 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
,08-31 16:50:37.959  9390  9390 E Zygote  : v2
08-31 16:50:37.959  9390  9390 I libpersona: KNOX_SDCARD checking this for 10010
,08-31 16:50:37.959  9390  9390 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
08-31 16:50:37.959  9390  9390 I libpersona: KNOX_SDCARD not a persona
08-31 16:50:37.959  9390  9390 E libpersona: scanKnoxPersonas
08-31 16:50:37.959  9390  9390 E libpersona: Couldn't open the File - /data/system/users/0/personalist.xml - No such file or directory
08-31 16:50:37.959  9390  9390 E Zygote  : accessInfo : 0
08-31 16:50:37.959  9390  9390 E libpersona: scanKnoxPersonas
08-31 16:50:37.959  9390  9390 E libpersona: Couldn't open the File - /data/system/users/0/personalist.xml - No such file or directory
,08-31 16:50:37.959  9106  9392 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
08-31 16:50:37.959  9106  9392 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,08-31 16:50:37.959  3381  3584 I ActivityManager: Start proc 9390:com.android.defcontainer/u0a10 for service com.android.defcontainer/.DefaultContainerService
08-31 16:50:37.959  3381  3584 I ActivityManager: Force stopping com.test.thalitest appid=10177 user=0: pkg removed
,08-31 16:50:37.969  3381  3856 D SecContentProvider: insert(), uri = 2
,08-31 16:50:37.979  9390  9390 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:50:37.979  9390  9390 D ActivityThread: Added TimaKeyStore provider
,08-31 16:50:37.989  3381  3865 E ConnectivityService: updateNetworkInfo()
,08-31 16:50:37.989  3381  3865 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -43]
08-31 16:50:37.989  3381  3865 V NetworkStats: updateIfacesLocked()
08-31 16:50:37.989  3381  3865 V NetworkStats: performPollLocked(flags=0x1)
,08-31 16:50:37.989  3381  3523 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-31 16:50:37.989  3381  3865 V NetworkStats: performPollLocked() took 5ms
08-31 16:50:37.989  3381  3523 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
08-31 16:50:37.989  3381  3460 V AlarmManager:  remove PendingIntent] PendingIntent{381afd9: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
,08-31 16:50:37.989  9377  9377 I KnoxUsageLogPro: premStatus:2
,08-31 16:50:37.999  9377  9377 I KnoxUsageLogPro: isEulaShown : false
08-31 16:50:37.999  9377  9377 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,08-31 16:50:37.999  3381  3856 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-31 16:50:37.999  3381  3856 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-31 16:50:37.999  3381  3865 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 16:50:37.999  3381  3865 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -43]
08-31 16:50:37.999  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,08-31 16:50:37.999  3381  9246 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-31 16:50:37.999  3381  3865 D ConnectivityService: scheduleUnvalidatedPrompt 502
08-31 16:50:37.999  3381  9246 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: Connected
08-31 16:50:37.999  3381  9246 D NetworkMonitor: registerReceiver Captive portal receiver
,08-31 16:50:37.999  3381  3865 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 502]
08-31 16:50:37.999  3381  3865 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,08-31 16:50:37.999  3381  3856 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-31 16:50:37.999  3381  3517 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package com.google.android.googlequicksearchbox
08-31 16:50:37.999  9390  9390 D RelationGraph: garbageCollect()
08-31 16:50:37.999  9390  9390 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
08-31 16:50:37.999  3381  3856 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-31 16:50:37.999  3381  3865 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -43]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-31 16:50:37.999  3381  3381 D ResourcesManager: For user 0 new overlays fetched Null
08-31 16:50:37.999  9390  9390 W ResourcesManager: getTopLevelResources: /system/priv-app/DefaultContainerService/DefaultContainerService.apk / 1.0 running in com.android.defcontainer rsrc of package com.android.defcontainer
08-31 16:50:37.999  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-31 16:50:37.999  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
08-31 16:50:37.999  3381  3517 D ResourcesManager: For user 0 new overlays fetched Null
08-31 16:50:37.999  3381  3517 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package com.google.android.googlequicksearchbox
08-31 16:50:37.999  3381  3517 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
08-31 16:50:37.999  3381  3381 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:38.009  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
,08-31 16:50:38.009  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
08-31 16:50:38.009  9390  9390 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
08-31 16:50:38.009  3381  4179 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
08-31 16:50:38.009  3381  3517 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:38.009  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
08-31 16:50:38.009  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
08-31 16:50:38.009  3381  3517 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
,08-31 16:50:38.009  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
08-31 16:50:38.009  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungAccount_Hero/SamsungAccount_Hero.apk / 1.0 running in null rsrc of package com.osp.app.signin
,08-31 16:50:38.009  9390  9390 D ResourcesManager: For user 0 new overlays fetched Null
08-31 16:50:38.009  3381  3517 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package com.google.android.googlequicksearchbox
08-31 16:50:38.009  3381  3517 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
08-31 16:50:38.009  3381  3517 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
08-31 16:50:38.009  3381  3517 W ResourcesManager: getTopLevelResources: /system/priv-app/LiveBroadcast/LiveBroadcast.apk / 1.0 running in null rsrc of package com.sec.android.app.camera.plb
08-31 16:50:38.009  3381  3865 D ConnectivityService:   checking if request is: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: true
08-31 16:50:38.009  3381  3865 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,08-31 16:50:38.009  9390  9390 I InjectionManager: Inside getClassLibPath caller 
08-31 16:50:38.009  4280  4636 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
08-31 16:50:38.009  4280  4636 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
08-31 16:50:38.009  3381  3865 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,08-31 16:50:38.009  3381  3865 D ConnectivityService: currentScore = 0, newScore = 20
,08-31 16:50:38.009  3381  3865 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 502]
08-31 16:50:38.009  3381  3865 D ConnectivityService:    accepting network in place of null
,08-31 16:50:38.009  3381  3865 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 16:50:38.009  3381  3855 D WIFI_P2P: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:50:38.009  3381  3855 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 16:50:38.019  3381  3855 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-31 16:50:38.019  3381  3855 D WIFI_P2P: evalRequest
08-31 16:50:38.019  3381  3855 D WIFI_P2P:   done
08-31 16:50:38.019  3381  3856 D WIFI_UT : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:50:38.019  3381  3891 D Ethernet: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:50:38.019  3381  3856 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 16:50:38.019  3381  3891 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
08-31 16:50:38.019  3381  3856 D WIFI_UT : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-31 16:50:38.019  3381  3856 D WIFI_UT : evalRequest
08-31 16:50:38.019  3381  3856 D WIFI_UT :   done
08-31 16:50:38.019  3381  3891 D Ethernet: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-31 16:50:38.019  3381  3891 D Ethernet: evalRequest
08-31 16:50:38.019  3381  3381 D ResourcesManager: For user 0 new overlays fetched Null
08-31 16:50:38.019  3381  3891 D Ethernet:   done
08-31 16:50:38.019  3381  3856 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:50:38.019  3381  3856 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 16:50:38.019  3381  3856 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-31 16:50:38.019  3381  3856 D WIFI    : evalRequest
08-31 16:50:38.019  3381  3856 D WIFI    :   done
08-31 16:50:38.019  3381  3856 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 16:50:38.019  3381  3856 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 16:50:38.019  3381  3856 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-31 16:50:38.019  3381  3517 D ResourcesManager: For user 0 new overlays fetched Null
08-31 16:50:38.019  3381  3856 D WIFI    : evalRequest
08-31 16:50:38.019  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungAccount_Hero/SamsungAccount_Hero.apk / 1.0 running in null rsrc of package com.osp.app.signin
08-31 16:50:38.019  3381  3856 D WIFI    :   done
08-31 16:50:38.019  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-31 16:50:38.019  9390  9390 D InjectionManager: InjectionManager
08-31 16:50:38.019  3381  3517 W ResourcesManager: getTopLevelResources: /system/priv-app/LiveBroadcast/LiveBroadcast.apk / 1.0 running in null rsrc of package com.sec.android.app.camera.plb
08-31 16:50:38.019  9390  9390 D InjectionManager: fillFeatureStoreMap com.android.defcontainer
08-31 16:50:38.019  3381  3517 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCamera5/SamsungCamera5.apk / 1.0 running in null rsrc of package com.sec.android.app.camera
,08-31 16:50:38.019  9390  9390 I InjectionManager: Constructor com.android.defcontainer, Feature store :{}
08-31 16:50:38.019  9390  9390 I InjectionManager: featureStore :{}
,08-31 16:50:38.019  3381  3517 D ResourcesManager: For user 0 new overlays fetched Null
08-31 16:50:38.019  3381  3381 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:38.019  3381  3517 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCamera5/SamsungCamera5.apk / 1.0 running in null rsrc of package com.sec.android.app.camera
08-31 16:50:38.019  3381  3517 W ResourcesManager: getTopLevelResources: /system/app/STalkback/STalkback.apk / 1.0 running in null rsrc of package com.samsung.android.app.talkback
08-31 16:50:38.019  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-31 16:50:38.019  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-31 16:50:38.019  3946  3946 D ShortcutManager: onReceive : android.intent.action.PACKAGE_REMOVED
08-31 16:50:38.019  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-31 16:50:38.019  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-31 16:50:38.019  3946  3946 D ShortcutManager: onReceive : Intent.EXTRA_REPLACING false,com.test.thalitest
08-31 16:50:38.019  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-31 16:50:38.019  3381  3517 D ResourcesManager: For user 0 new overlays fetched Null
08-31 16:50:38.019  3381  3381 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in null rsrc of package com.samsung.android.coreapps
,08-31 16:50:38.019  3381  3517 W ResourcesManager: getTopLevelResources: /system/app/STalkback/STalkback.apk / 1.0 running in null rsrc of package com.samsung.android.app.talkback
08-31 16:50:38.019  3381  3517 W ResourcesManager: getTopLevelResources: /system/app/UniversalSwitch/UniversalSwitch.apk / 1.0 running in null rsrc of package com.samsung.android.universalswitch
,08-31 16:50:38.019  3381  3381 D ResourcesManager: For user 0 new overlays fetched Null
08-31 16:50:38.019  3381  3517 D ResourcesManager: For user 0 new overlays fetched Null
08-31 16:50:38.019  3381  3517 W ResourcesManager: getTopLevelResources: /system/app/UniversalSwitch/UniversalSwitch.apk / 1.0 running in null rsrc of package com.samsung.android.universalswitch
,08-31 16:50:38.019  3381  3381 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in null rsrc of package com.samsung.android.coreapps
08-31 16:50:38.019  3381  3381 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
08-31 16:50:38.019  3381  3865 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,08-31 16:50:38.019  3381  3517 D AccessibilityManagerService: onUserStateChangedLocked()
08-31 16:50:38.019  3381  3517 D AccessibilityManagerService: updateServicesLocked().mIsAccessibilityEnabled : false
08-31 16:50:38.019  3381  3381 D ResourcesManager: For user 0 new overlays fetched Null
08-31 16:50:38.029  3381  3381 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
08-31 16:50:38.029  3381  3381 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
08-31 16:50:38.029  4132  4132 I CatchNotificationsService: mPackageChangedReceiver : onReceive action = android.intent.action.PACKAGE_REMOVED
08-31 16:50:38.029  3381  3381 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
08-31 16:50:38.029  3381  3381 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
08-31 16:50:38.029  3381  3381 D ResourcesManager: For user 0 new overlays fetched Null
08-31 16:50:38.029  3381  3381 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
08-31 16:50:38.029  3381  3381 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in null rsrc of package com.microsoft.office.onenote
,08-31 16:50:38.029  3381  3381 D ResourcesManager: For user 0 new overlays fetched Null
08-31 16:50:38.029  3381  3865 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
08-31 16:50:38.029  9390  9404 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
08-31 16:50:38.029  3381  3562 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package com.android.inputdevices
08-31 16:50:38.029  3381  3517 D EnterpriseDeviceManagerService: Package has changed for user 0
08-31 16:50:38.029  3381  3517 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
08-31 16:50:38.029  3381  3381 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in null rsrc of package com.microsoft.office.onenote
08-31 16:50:38.029  3381  3381 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
,08-31 16:50:38.029  3381  3562 D ResourcesManager: For user 0 new overlays fetched Null
08-31 16:50:38.029  3381  3381 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:38.029  3381  3562 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package com.android.inputdevices
08-31 16:50:38.029  3381  3381 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
,08-31 16:50:38.029  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-31 16:50:38.029  3381  3828 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-31 16:50:38.029  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-31 16:50:38.029  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-31 16:50:38.029  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,08-31 16:50:38.029  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-31 16:50:38.029  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-31 16:50:38.029  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-31 16:50:38.029  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-31 16:50:38.029  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-31 16:50:38.029  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-31 16:50:38.029  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-31 16:50:38.029  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,08-31 16:50:38.029  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-31 16:50:38.029  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-31 16:50:38.029  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-31 16:50:38.029  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-31 16:50:38.029  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-31 16:50:38.039  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-31 16:50:38.039  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-31 16:50:38.039  9390  9404 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
08-31 16:50:38.039  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,08-31 16:50:38.039  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-31 16:50:38.039  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-31 16:50:38.039  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-31 16:50:38.039  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-31 16:50:38.039  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-31 16:50:38.039  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-31 16:50:38.039  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,08-31 16:50:38.039  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-31 16:50:38.039  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-31 16:50:38.039  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-31 16:50:38.039  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-31 16:50:38.039  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-31 16:50:38.039  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package com.google.android.gsf
,08-31 16:50:38.039  3381  3381 D ResourcesManager: For user 0 new overlays fetched Null
08-31 16:50:38.039  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package com.google.android.gsf
08-31 16:50:38.039  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package com.sec.android.app.shealth
08-31 16:50:38.039  9390  9404 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
,08-31 16:50:38.039  3381  3865 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,08-31 16:50:38.039  3381  3865 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -43]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-31 16:50:38.039  3381  3517 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
08-31 16:50:38.039  3381  3517 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
08-31 16:50:38.039  3381  3381 D ResourcesManager: For user 0 new overlays fetched Null
08-31 16:50:38.039  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package com.sec.android.app.shealth
08-31 16:50:38.039  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package com.sec.android.app.shealth
,08-31 16:50:38.039  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package com.sec.android.app.shealth
08-31 16:50:38.039  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
08-31 16:50:38.039  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
08-31 16:50:38.039  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
08-31 16:50:38.039  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
08-31 16:50:38.039  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
08-31 16:50:38.039  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
08-31 16:50:38.039  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
08-31 16:50:38.039  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
08-31 16:50:38.039  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
,08-31 16:50:38.039  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
08-31 16:50:38.039  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
08-31 16:50:38.039  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
08-31 16:50:38.039  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-31 16:50:38.039  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-31 16:50:38.039  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-31 16:50:38.039  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-31 16:50:38.039  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-31 16:50:38.039  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-31 16:50:38.039  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,08-31 16:50:38.039  4305  4807 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-31 16:50:38.039  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-31 16:50:38.039  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-31 16:50:38.039  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-31 16:50:38.039  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-31 16:50:38.039  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-31 16:50:38.039  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-31 16:50:38.039  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-31 16:50:38.039  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-31 16:50:38.039  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-31 16:50:38.039  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
,08-31 16:50:38.049  4991  5190 D PresenceModule: onReceive: package removed
08-31 16:50:38.049  4991  5190 D PresenceModule: handleMessage: msg 50, Last Publish Info: null
08-31 16:50:38.049  4991  5190 D PresenceModule: Application package removed
08-31 16:50:38.049  4991  5190 D PresenceModule: onAppPkgRemoved: com.test.thalitest
08-31 16:50:38.049  4991  5190 D PresenceModule: onApplicationPackageRemoved: invalid package
,08-31 16:50:38.049  4146  4146 I PeoplePackageManager: onReceive:android.intent.action.PACKAGE_REMOVED
,08-31 16:50:38.049  3381  3381 D ResourcesManager: For user 0 new overlays fetched Null
08-31 16:50:38.049  3381  3517 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in null rsrc of package com.android.settings
,08-31 16:50:38.049  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
08-31 16:50:38.049  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
08-31 16:50:38.049  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
08-31 16:50:38.049  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
08-31 16:50:38.049  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
08-31 16:50:38.049  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
,08-31 16:50:38.049  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
08-31 16:50:38.049  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
08-31 16:50:38.049  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
08-31 16:50:38.049  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
08-31 16:50:38.049  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
08-31 16:50:38.049  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
08-31 16:50:38.049  3381  3381 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
08-31 16:50:38.049  3381  3381 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package com.android.chrome
,08-31 16:50:38.049  3381  3517 D ResourcesManager: For user 0 new overlays fetched Null,
08-31 16:50:38.049  3381  3517 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in null rsrc of package com.android.settings
08-31 16:50:38.049  3381  3381 D ResourcesManager: For user 0 new overlays fetched Null
08-31 16:50:38.049  3381  3517 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
08-31 16:50:38.049  3381  3853 V NetworkStats: removeUidsLocked() for UIDs [10177]
08-31 16:50:38.049  3381  3853 V NetworkStats: performPollLocked(flags=0x3)
08-31 16:50:38.049  3381  3381 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package com.android.chrome
08-31 16:50:38.049  3381  3381 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in null rsrc of package com.samsung.android.coreapps
08-31 16:50:38.049  3381  3381 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in null rsrc of package com.samsung.android.coreapps
08-31 16:50:38.049  3381  3381 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package com.google.android.apps.docs
,08-31 16:50:38.049  3381  3517 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:38.049  3381  3517 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
08-31 16:50:38.049  3381  3517 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
08-31 16:50:38.059  3381  3381 D ResourcesManager: For user 0 new overlays fetched Null
08-31 16:50:38.059  3381  3517 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
,08-31 16:50:38.059  3381  3381 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package com.google.android.apps.docs
08-31 16:50:38.059  3381  3517 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-31 16:50:38.059  3152  3637 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-31 16:50:38.059  3381  3381 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
08-31 16:50:38.059  3381  3381 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
,08-31 16:50:38.059  3381  3517 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-31 16:50:38.059  3381  3381 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
08-31 16:50:38.059  3381  3381 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
08-31 16:50:38.059  3381  3517 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Epic_Common/SecMms_Epic_Common.apk / 1.0 running in null rsrc of package com.android.mms
08-31 16:50:38.059  3381  3381 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
08-31 16:50:38.059  3381  3381 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
08-31 16:50:38.059  3381  3381 W ResourcesManager: getTopLevelResources: /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk / 1.0 running in null rsrc of package com.google.android.syncadapters.calendar
,08-31 16:50:38.059  3381  3517 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:38.059  3381  3517 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Epic_Common/SecMms_Epic_Common.apk / 1.0 running in null rsrc of package com.android.mms
08-31 16:50:38.059  3381  3517 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles/SecMyFiles.apk / 1.0 running in null rsrc of package com.sec.android.app.myfiles
08-31 16:50:38.059  3381  3381 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:38.059  3381  3381 W ResourcesManager: getTopLevelResources: /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk / 1.0 running in null rsrc of package com.google.android.syncadapters.calendar
08-31 16:50:38.059  3381  3517 D ResourcesManager: For user 0 new overlays fetched Null
08-31 16:50:38.059  3946  4130 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
08-31 16:50:38.059  3381  3381 W ResourcesManager: getTopLevelResources: /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk / 1.0 running in null rsrc of package com.google.android.syncadapters.contacts
,08-31 16:50:38.059  3381  4057 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
08-31 16:50:38.059  3381  3517 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles/SecMyFiles.apk / 1.0 running in null rsrc of package com.sec.android.app.myfiles
08-31 16:50:38.059  3381  3854 D NtpTrustedTime: forceRefresh() from cache miss
08-31 16:50:38.059  3381  3381 D ResourcesManager: For user 0 new overlays fetched Null
08-31 16:50:38.059  3152  3633 D EnterpriseController: netId is 0
08-31 16:50:38.059  3381  3517 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package com.google.android.music
08-31 16:50:38.059  3152  3633 D Netd    : getNetworkForDns: using netid 0 for uid 1000
08-31 16:50:38.059  3381  3381 W ResourcesManager: getTopLevelResources: /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk / 1.0 running in null rsrc of package com.google.android.syncadapters.contacts
08-31 16:50:38.059  3381  3854 D NtpTrustedTime: forceRefresh Fail.
08-31 16:50:38.059  3381  3381 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package com.google.android.music
08-31 16:50:38.059  3381  3381 D ResourcesManager: For user 0 new overlays fetched Null
08-31 16:50:38.059  3381  3517 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:38.059  3381  3517 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package com.google.android.music
08-31 16:50:38.059  3381  3517 W ResourcesManager: getTopLevelResources: /system/app/SecMemo3/SecMemo3.apk / 1.0 running in null rsrc of package com.samsung.android.app.memo
08-31 16:50:38.059  3381  3381 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package com.google.android.music
08-31 16:50:38.059  3381  3523 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{322e50e u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2f44388 6383:com.samsung.klmsagent/u0a28}
08-31 16:50:38.059  3381  3381 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
08-31 16:50:38.059  3381  3381 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
08-31 16:50:38.059  3381  3381 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in null rsrc of package com.microsoft.office.onenote
08-31 16:50:38.059  3381  3517 D ResourcesManager: For user 0 new overlays fetched Null
08-31 16:50:38.059  3381  3381 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in null rsrc of package com.microsoft.office.onenote
08-31 16:50:38.059  3381  3381 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
08-31 16:50:38.059  3381  3381 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
08-31 16:50:38.069  3381  3381 W ResourcesManager: getTopLevelResources: /system/app/Videos/Videos.apk / 1.0 running in null rsrc of package com.google.android.videos
08-31 16:50:38.069  3381  3517 W ResourcesManager: getTopLevelResources: /system/app/SecMemo3/SecMemo3.apk / 1.0 running in null rsrc of package com.samsung.android.app.memo
08-31 16:50:38.069  3381  3517 W ResourcesManager: getTopLevelResources: /system/app/Weather2016/Weather2016.apk / 1.0 running in null rsrc of package com.samsung.android.weather
,08-31 16:50:38.069  3381  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-31 16:50:38.069  3381  3381 D ResourcesManager: For user 0 new overlays fetched Null
08-31 16:50:38.069  3381  3517 D ResourcesManager: For user 0 new overlays fetched Null
08-31 16:50:38.069  3381  3381 W ResourcesManager: getTopLevelResources: /system/app/Videos/Videos.apk / 1.0 running in null rsrc of package com.google.android.videos
08-31 16:50:38.069  3381  3517 W ResourcesManager: getTopLevelResources: /system/app/Weather2016/Weather2016.apk / 1.0 running in null rsrc of package com.samsung.android.weather
,08-31 16:50:38.069  3381  3517 W ResourcesManager: getTopLevelResources: /system/app/YouTube/YouTube.apk / 1.0 running in null rsrc of package com.google.android.youtube
,08-31 16:50:38.069  3381  3517 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:38.069  3381  3517 W ResourcesManager: getTopLevelResources: /system/app/YouTube/YouTube.apk / 1.0 running in null rsrc of package com.google.android.youtube
08-31 16:50:38.069  3152  3637 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-31 16:50:38.069  3381  3517 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-31 16:50:38.069  6383  6383 I KLMS-2.6.201: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) } | timestamp: Wed Aug 31 16:50:38 GMT+02:00 2016
08-31 16:50:38.069  3381  4773 D SecContentProvider2: query(), uri = 15 selection = getToastGravityEnabledState
08-31 16:50:38.069  3381  3517 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,08-31 16:50:38.069  3381  3517 W ResourcesManager: getTopLevelResources: /system/priv-app/MyPlaces_Hero/MyPlaces_Hero.apk / 1.0 running in null rsrc of package com.sec.android.widgetapp.locationwidget
,08-31 16:50:38.069  3381  3517 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:38.069  3381  3517 W ResourcesManager: getTopLevelResources: /system/priv-app/MyPlaces_Hero/MyPlaces_Hero.apk / 1.0 running in null rsrc of package com.sec.android.widgetapp.locationwidget
08-31 16:50:38.069  3381  3517 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-31 16:50:38.069  3381  3853 V NetworkStats: performPollLocked() took 22ms
08-31 16:50:38.069  3381  3517 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in null rsrc of package com.android.settings
08-31 16:50:38.069  3381  3865 D ConnectivityService: Setting tx/rx TCP buffers to 524288,1048576,2097120,524288,1048576,4194240
08-31 16:50:38.069  3381  3517 W ResourcesManager: getTopLevelResources: /system/priv-app/TouchWizHome_2016/TouchWizHome_2016.apk / 1.0 running in null rsrc of package com.sec.android.app.launcher
,08-31 16:50:38.069  3381  3517 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package com.android.chrome
08-31 16:50:38.069  3381  3517 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package com.android.chrome
,08-31 16:50:38.069  3381  4057 D SecContentProvider2: query(), uri = 15 selection = getToastEnabledState
08-31 16:50:38.069  3381  3517 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package com.google.android.apps.docs
08-31 16:50:38.069  3381  3517 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package com.google.android.apps.docs
08-31 16:50:38.069  3381  3517 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package com.google.android.apps.docs
,08-31 16:50:38.079  3381  3517 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
08-31 16:50:38.079  3381  3517 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
08-31 16:50:38.079  3381  3517 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M/SPlanner_M.apk / 1.0 running in null rsrc of package com.android.calendar
,08-31 16:50:38.079  3381  3560 D EntConnectivity: Not allowed due to - mEnabled false
08-31 16:50:38.079  3381  3517 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:38.079  3381  3517 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M/SPlanner_M.apk / 1.0 running in null rsrc of package com.android.calendar
08-31 16:50:38.079  3381  3517 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M/SPlanner_M.apk / 1.0 running in null rsrc of package com.android.calendar
08-31 16:50:38.079  4280  4280 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-31 16:50:38.079  3381  4304 D SecContentProvider2: query(), uri = 15 selection = getToastShowPackageNameState
08-31 16:50:38.079  3381  3517 W ResourcesManager: getTopLevelResources: /system/app/Weather2016/Weather2016.apk / 1.0 running in null rsrc of package com.samsung.android.weather
08-31 16:50:38.079  3381  3517 W ResourcesManager: getTopLevelResources: /system/app/Weather2016/Weather2016.apk / 1.0 running in null rsrc of package com.samsung.android.weather
08-31 16:50:38.079  3381  3517 W ResourcesManager: getTopLevelResources: /system/app/YouTube/YouTube.apk / 1.0 running in null rsrc of package com.google.android.youtube
08-31 16:50:38.079  3381  3517 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package com.google.android.googlequicksearchbox
,08-31 16:50:38.079  3381  3517 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package com.google.android.googlequicksearchbox
08-31 16:50:38.079  3381  3517 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
08-31 16:50:38.079  4280  4280 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,08-31 16:50:38.079  3381  3517 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2015/SecGallery2015.apk / 1.0 running in null rsrc of package com.sec.android.gallery3d
,08-31 16:50:38.079  3381  3517 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:38.079  3381  3517 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2015/SecGallery2015.apk / 1.0 running in null rsrc of package com.sec.android.gallery3d
08-31 16:50:38.079  9412  9412 E Zygote  : v2
08-31 16:50:38.079  9412  9412 I libpersona: KNOX_SDCARD checking this for 10012
08-31 16:50:38.079  9412  9412 I libpersona: KNOX_SDCARD not a persona
,08-31 16:50:38.079  3381  3517 W ResourcesManager: getTopLevelResources: /system/priv-app/SFinder_v4/SFinder_v4.apk / 1.0 running in null rsrc of package com.samsung.android.app.galaxyfinder
,08-31 16:50:38.079  3381  3517 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:38.079  9412  9412 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
08-31 16:50:38.079  3381  3851 I ActivityManager: Start proc 9412:com.microsoft.office.onenote.connectionReceiverProcess/u0a12 for broadcast-5 com.microsoft.office.onenote/com.microsoft.bing.datamining.quasar.api.ConnectionChangeReceiver
08-31 16:50:38.079  9412  9412 E Zygote  : accessInfo : 0
08-31 16:50:38.079  3381  3517 W ResourcesManager: getTopLevelResources: /system/priv-app/SFinder_v4/SFinder_v4.apk / 1.0 running in null rsrc of package com.samsung.android.app.galaxyfinder
08-31 16:50:38.079  9412  9412 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.microsoft.office.onenote.connectionReceiverProcess 
08-31 16:50:38.079  3381  3517 W ResourcesManager: getTopLevelResources: /system/priv-app/SFinder_v4/SFinder_v4.apk / 1.0 running in null rsrc of package com.samsung.android.app.galaxyfinder
08-31 16:50:38.079  3381  3851 I ActivityManager: Killing 8749:com.google.android.partnersetup/u0a25 (adj 15): DHA:empty #33
08-31 16:50:38.079  3381  3517 W ResourcesManager: getTopLevelResources: /system/priv-app/VoiceNote_4.0/VoiceNote_4.0.apk / 1.0 running in null rsrc of package com.sec.android.app.voicenote
08-31 16:50:38.079  3381  3517 D ResourcesManager: For user 0 new overlays fetched Null
08-31 16:50:38.079  3381  3517 W ResourcesManager: getTopLevelResources: /system/priv-app/VoiceNote_4.0/VoiceNote_4.0.apk / 1.0 running in null rsrc of package com.sec.android.app.voicenote
08-31 16:50:38.079  3381  3517 W ResourcesManager: getTopLevelResources: /system/priv-app/VoiceNote_4.0/VoiceNote_4.0.apk / 1.0 running in null rsrc of package com.sec.android.app.voicenote
08-31 16:50:38.089  3381  3517 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
08-31 16:50:38.089  3381  3517 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
,08-31 16:50:38.089  4019  4019 I Recents_MultiWindowAppListInfo: android.intent.action.PACKAGE_REMOVE
,08-31 16:50:38.089  3381  4915 W ActivityManager: Permission Denial: Accessing service ComponentInfo{com.google.android.music/com.google.android.music.dial.DialMediaRouteProviderService} from pid=4814, uid=10130 that is not exported from uid 10128
,08-31 16:50:38.099  6383  6383 I KLMS-2.6.201: : KLMSAbstractReciever(): onReceive().END.
,08-31 16:50:38.099  6383  6383 I KLMS-2.6.201: : KLMSIntentService(): onCreate()
08-31 16:50:38.099  6383  6383 I KLMS-2.6.201: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-31 16:50:38.099  3381  3854 D NtpTrustedTime: forceRefresh() from cache miss
,08-31 16:50:38.099  3152  3633 D EnterpriseController: netId is 0
08-31 16:50:38.099  3152  3633 D Netd    : getNetworkForDns: using netid 502 for uid 1000
,08-31 16:50:38.099  6383  6383 I KLMS-2.6.201: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-31 16:50:38.099  6383  9424 I KLMS-2.6.201: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
08-31 16:50:38.099  6383  9424 D KLMS-2.6.201: : KLMSIntentService(): PACKAGE_REMOVED
08-31 16:50:38.099  6383  9424 I KLMS-2.6.201: : Systemprocess(): listeningToPackageRemoved().START
08-31 16:50:38.099  6383  9424 I KLMS-2.6.201: : Systemprocess(): listeningToPackageRemoved().packageName: com.test.thalitest
08-31 16:50:38.099  6383  9424 I KLMS-2.6.201: : Systemprocess(): listeningToPackageRemovedforELM().START - com.test.thalitest
08-31 16:50:38.099  6383  9424 I KLMS-2.6.201: : MDMBridge(): getAllLicenseInfoFromSDK()
,08-31 16:50:38.099  3381  9246 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 16:50:38.099  3381  9246 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: Validated
08-31 16:50:38.099  3381  3381 V AlarmManager: Remove alarm for next reason : android.intent.action.PACKAGE_REMOVED : package: com.test.thalitest
08-31 16:50:38.099  6383  9424 I KLMS-2.6.201: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
08-31 16:50:38.099  3381  3381 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-31 16:50:38.099  3381  3381 D UniversalCredentialManagerService: inside mPkgReciever onReceive : android.intent.action.PACKAGE_REMOVED
08-31 16:50:38.099  3381  3381 D UniversalCredentialManagerService: ACTION_PACKAGE_REMOVED is called....
08-31 16:50:38.099  3381  3381 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-31 16:50:38.099  3381  3381 I OTPFW   : PackageRemovalReceiver::onReceive Enter
,08-31 16:50:38.099  3381  3381 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10177 container id = 0
,08-31 16:50:38.099  3381  3381 I OTPFW   : ProvisionData::getAllEntries Enter
,08-31 16:50:38.099  9412  9412 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:50:38.099  9412  9412 D ActivityThread: Added TimaKeyStore provider
08-31 16:50:38.099  3381  3381 E OTPFW   : ProvisionData::getAllEntries Table is empty
08-31 16:50:38.099  3381  3381 E SDAgentPackageStateReceiver: Not going to handle 'com.test.thalitest'!
,08-31 16:50:38.099  3381  4558 V AlarmManager:  remove PendingIntent] PendingIntent{e9fae70: PendingIntentRecord{e6c2e79 com.android.bluetooth broadcastIntent}}
08-31 16:50:38.109  3381  3460 D ActivityManager: isAutoRunBlockedApp:: com.google.android.partnersetup, Auto Run ON
,08-31 16:50:38.109  3381  3381 D UcmService: onReceive android.intent.action.PACKAGE_REMOVED
08-31 16:50:38.109  3381  3381 D UcmService: Package update in userId-0 and uid-10177
08-31 16:50:38.109  3381  3381 D InjectionManagerService -AppFeature:  Info before com.test.thalitest removal target ={} 
08-31 16:50:38.109  3381  3381 D InjectionManagerService -AppFeature:  source ={}
08-31 16:50:38.109  3381  3381 W SQLiteLog: (28) failed to open "/data/system/gamemanager.db" with flag (131138) and mode_t (0) due to error (30)
,08-31 16:50:38.109  3381  3381 E SQLiteDatabase: Failed to open database '/data/system/gamemanager.db'.
08-31 16:50:38.109  3381  3381 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 16:50:38.109  3381  3381 E SQLiteDatabase: #################################################################
08-31 16:50:38.109  3381  3381 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
08-31 16:50:38.109  3381  3381 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
08-31 16:50:38.109  3381  3381 E SQLiteDatabase: #################################################################
08-31 16:50:38.109  3381  3381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 16:50:38.109  3381  3381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:283)
08-31 16:50:38.109  3381  3381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:210)
08-31 16:50:38.109  3381  3381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-31 16:50:38.109  3381  3381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-31 16:50:38.109  3381  3381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-31 16:50:38.109  3381  3381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-31 16:50:38.109  3381  3381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-31 16:50:38.109  3381  3381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-31 16:50:38.109  3381  3381 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:633)
08-31 16:50:38.109  3381  3381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 16:50:38.109  3381  3381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 16:50:38.109  3381  3381 E SQLiteDatabase: 	at com.samsung.android.game.data.DatabaseHelper.removeGame(DatabaseHelper.java:144)
08-31 16:50:38.109  3381  3381 E SQLiteDatabase: 	at com.samsung.android.game.GameManagerService$UninstallReceiver.onReceive(GameManagerService.java:512)
08-31 16:50:38.109  3381  3381 E SQLiteDatabase: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:993)
08-31 16:50:38.109  3381  3381 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 16:50:38.109  3381  3381 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 16:50:38.109  3381  3381 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:158)
08-31 16:50:38.109  3381  3381 E SQLiteDatabase: 	at com.android.server.SystemServer.run(SystemServer.java:508)
08-31 16:50:38.109  3381  3381 E SQLiteDatabase: 	at com.android.server.SystemServer.main(SystemServer.java:363)
08-31 16:50:38.109  3381  3381 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 16:50:38.109  3381  3381 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-31 16:50:38.109  3381  3381 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-31 16:50:38.109  3381  3381 D AndroidRuntime: Shutting down VM
,08-31 16:50:38.109  3381  3381 E AndroidRuntime: *** FATAL EXCEPTION IN SYSTEM PROCESS: main
08-31 16:50:38.109  3381  3381 E AndroidRuntime: java.lang.RuntimeException: Error receiving broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) } in com.samsung.android.game.GameManagerService$UninstallReceiver@3aaf1e7
08-31 16:50:38.109  3381  3381 E AndroidRuntime: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1003)
08-31 16:50:38.109  3381  3381 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 16:50:38.109  3381  3381 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 16:50:38.109  3381  3381 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:158)
08-31 16:50:38.109  3381  3381 E AndroidRuntime: 	at com.android.server.SystemServer.run(SystemServer.java:508)
08-31 16:50:38.109  3381  3381 E AndroidRuntime: 	at com.android.server.SystemServer.main(SystemServer.java:363)
08-31 16:50:38.109  3381  3381 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 16:50:38.109  3381  3381 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-31 16:50:38.109  3381  3381 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-31 16:50:38.109  3381  3381 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 16:50:38.109  3381  3381 E AndroidRuntime: #################################################################
08-31 16:50:38.109  3381  3381 E AndroidRuntime: Error Code : 0 (SQLITE_OK)
08-31 16:50:38.109  3381  3381 E AndroidRuntime: Caused By : not an error (code 0): Could not open the database in read/write mode.
08-31 16:50:38.109  3381  3381 E AndroidRuntime: #################################################################
08-31 16:50:38.109  3381  3381 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 16:50:38.109  3381  3381 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:283)
08-31 16:50:38.109  3381  3381 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:210)
08-31 16:50:38.109  3381  3381 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-31 16:50:38.109  3381  3381 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-31 16:50:38.109  3381  3381 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-31 16:50:38.109  3381  3381 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-31 16:50:38.109  3381  3381 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-31 16:50:38.109  3381  3381 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-31 16:50:38.109  3381  3381 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:633)
08-31 16:50:38.109  3381  3381 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 16:50:38.109  3381  3381 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 16:50:38.109  3381  3381 E AndroidRuntime: 	at com.samsung.android.game.data.DatabaseHelper.removeGame(DatabaseHelper.java:144)
08-31 16:50:38.109  3381  3381 E AndroidRuntime: 	at com.samsung.android.game.GameManagerService$UninstallReceiver.onReceive(GameManagerService.java:512)
08-31 16:50:38.109  3381  3381 E AndroidRuntime: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:993)
08-31 16:50:38.10,9  3381  3381 E AndroidRuntime: 	... 8 more
08-31 16:50:38.109  6383  9424 I KLMS-2.6.201: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-31 16:50:38.109  6383  9424 I KLMS-2.6.201: : MDMBridge(): getAllLicenseInfoFromSDK()
,08-31 16:50:38.109  3946  4130 D ViewRootImpl: #1 mView = android.widget.LinearLayout{f9ce4ff V.E...... ......I. 0,0-0,0 #102039c android:id/toast_layout_root}
,08-31 16:50:38.109  6383  9424 D KLMS-2.6.201: : Systemprocess(): arrayLicenseInfo is null
,08-31 16:50:38.109  3381  3517 W ResourcesManager: getTopLevelResources: /system/priv-app/LiveBroadcast/LiveBroadcast.apk / 1.0 running in null rsrc of package com.sec.android.app.camera.plb
,08-31 16:50:38.109  3381  3517 W ResourcesManager: getTopLevelResources: /system/priv-app/LiveBroadcast/LiveBroadcast.apk / 1.0 running in null rsrc of package com.sec.android.app.camera.plb
08-31 16:50:38.109  3381  3517 W ResourcesManager: getTopLevelResources: /system/priv-app/LiveBroadcast/LiveBroadcast.apk / 1.0 running in null rsrc of package com.sec.android.app.camera.plb
08-31 16:50:38.109  3381  4057 W WindowManager: Failed looking up window
08-31 16:50:38.109  3381  4057 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@eb4bd0f does not exist
08-31 16:50:38.109  3381  4057 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
08-31 16:50:38.109  3381  4057 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
08-31 16:50:38.109  3381  4057 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
08-31 16:50:38.109  3381  4057 W WindowManager: 	at android.view.IWindowSession$Stub.onTransact(IWindowSession.java:688)
08-31 16:50:38.109  3381  4057 W WindowManager: 	at com.android.server.wm.Session.onTransact(Session.java:139)
08-31 16:50:38.109  3381  4057 W WindowManager: 	at android.os.Binder.execTransact(Binder.java:453)
08-31 16:50:38.109  3381  3517 W ResourcesManager: getTopLevelResources: /system/priv-app/SFinder_v4/SFinder_v4.apk / 1.0 running in null rsrc of package com.samsung.android.app.galaxyfinder
,08-31 16:50:38.109  6383  9424 W SQLiteLog: (28) failed to open "/data/user/0/com.samsung.klmsagent/databases/klms.db" with flag (131138) and mode_t (0) due to error (30)
08-31 16:50:38.109  3381  3517 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCamera5/SamsungCamera5.apk / 1.0 running in null rsrc of package com.sec.android.app.camera
08-31 16:50:38.109  3381  4411 D ISSUE_DEBUG: InputChannelName : 736a7a5 Toast
08-31 16:50:38.109  3381  3517 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCamera5/SamsungCamera5.apk / 1.0 running in null rsrc of package com.sec.android.app.camera
,08-31 16:50:38.119  6383  9424 E SQLiteDatabase: Failed to open database '/data/user/0/com.samsung.klmsagent/databases/klms.db'.
08-31 16:50:38.119  6383  9424 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 16:50:38.119  6383  9424 E SQLiteDatabase: #################################################################
08-31 16:50:38.119  6383  9424 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
08-31 16:50:38.119  6383  9424 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
08-31 16:50:38.119  6383  9424 E SQLiteDatabase: #################################################################
08-31 16:50:38.119  6383  9424 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 16:50:38.119  6383  9424 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:283)
08-31 16:50:38.119  6383  9424 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:210)
08-31 16:50:38.119  6383  9424 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-31 16:50:38.119  6383  9424 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-31 16:50:38.119  6383  9424 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-31 16:50:38.119  6383  9424 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-31 16:50:38.119  6383  9424 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-31 16:50:38.119  6383  9424 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-31 16:50:38.119  6383  9424 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:633)
08-31 16:50:38.119  6383  9424 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
08-31 16:50:38.119  6383  9424 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 16:50:38.119  6383  9424 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 16:50:38.119  6383  9424 E SQLiteDatabase: 	at com.samsung.klmsagent.database.DataSource.fetchData(DataSource.java:88)
08-31 16:50:38.119  6383  9424 E SQLiteDatabase: 	at com.samsung.klmsagent.util.DataBaseUtils.checkKnoxLicenseActivationRecord(DataBaseUtils.java:323)
08-31 16:50:38.119  6383  9424 E SQLiteDatabase: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemovedforELM(Systemprocess.java:587)
08-31 16:50:38.119  6383  9424 E SQLiteDatabase: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemoved(Systemprocess.java:523)
08-31 16:50:38.119  6383  9424 E SQLiteDatabase: 	at com.samsung.klmsagent.service.KLMSIntentService.onHandleIntent(KLMSIntentService.java:173)
08-31 16:50:38.119  6383  9424 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-31 16:50:38.119  6383  9424 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 16:50:38.119  6383  9424 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:158)
08-31 16:50:38.119  6383  9424 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 16:50:38.119  3381  4411 V MARsPolicyManager: handelAlertToastWindowStarted pkgName = com.android.systemui
08-31 16:50:38.119  6383  9424 E SQLiteOpenHelper: Couldn't open klms.db for writing (will try read-only):
08-31 16:50:38.119  6383  9424 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 16:50:38.119  6383  9424 E SQLiteOpenHelper: ################################################,#################
08-31 16:50:38.119  6383  9424 E SQLiteOpenHelper: Error Code : 0 (SQLITE_OK)
08-31 16:50:38.119  6383  9424 E SQLiteOpenHelper: Caused By : not an error (code 0): Could not open the database in read/write mode.
08-31 16:50:38.119  6383  9424 E SQLiteOpenHelper: #################################################################
08-31 16:50:38.119  6383  9424 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 16:50:38.119  6383  9424 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:283)
08-31 16:50:38.119  6383  9424 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:210)
08-31 16:50:38.119  6383  9424 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-31 16:50:38.119  6383  9424 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-31 16:50:38.119  6383  9424 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-31 16:50:38.119  6383  9424 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-31 16:50:38.119  6383  9424 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-31 16:50:38.119  6383  9424 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-31 16:50:38.119  6383  9424 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:633)
08-31 16:50:38.119  6383  9424 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
08-31 16:50:38.119  6383  9424 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 16:50:38.119  6383  9424 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 16:50:38.119  6383  9424 E SQLiteOpenHelper: 	at com.samsung.klmsagent.database.DataSource.fetchData(DataSource.java:88)
08-31 16:50:38.119  6383  9424 E SQLiteOpenHelper: 	at com.samsung.klmsagent.util.DataBaseUtils.checkKnoxLicenseActivationRecord(DataBaseUtils.java:323)
08-31 16:50:38.119  6383  9424 E SQLiteOpenHelper: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemovedforELM(Systemprocess.java:587)
08-31 16:50:38.119  6383  9424 E SQLiteOpenHelper: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemoved(Systemprocess.java:523)
08-31 16:50:38.119  6383  9424 E SQLiteOpenHelper: 	at com.samsung.klmsagent.service.KLMSIntentService.onHandleIntent(KLMSIntentService.java:173)
08-31 16:50:38.119  6383  9424 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-31 16:50:38.119  6383  9424 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 16:50:38.119  6383  9424 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:158)
08-31 16:50:38.119  6383  9424 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 16:50:38.119  3381  3517 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
08-31 16:50:38.119  6383  9424 W SQLiteOpenHelper: Opened klms.db in read-only mode
,08-31 16:50:38.119  6383  9424 D KLMS-2.6.201: : DataSource(): Fetched Data from data base count : 0
08-31 16:50:38.119  3381  3517 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
08-31 16:50:38.119  6383  9424 W System.err: rename failed: EROFS (Read-only file system) : /data/user/0/com.samsung.klmsagent/shared_prefs/klmsagent.preferences.xml -> /data/user/0/com.samsung.klmsagent/shared_prefs/klmsagent.preferences.xml.bak
,08-31 16:50:38.119  6383  9424 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.samsung.klmsagent/shared_prefs/klmsagent.preferences.xml to backup file /data/user/0/com.samsung.klmsagent/shared_prefs/klmsagent.preferences.xml.bak
08-31 16:50:38.119  3381  3517 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
,08-31 16:50:38.119  3381  3381 E android.os.Debug: THIS IS SYSTEM_SERVER.. store dumpState!!
,08-31 16:50:38.119  3381  3517 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
08-31 16:50:38.119  9313  9326 D BadgeProvider: query, [selection] : null
,08-31 16:50:38.119  3381  3517 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,08-31 16:50:38.119  3381  3517 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2015/SecGallery2015.apk / 1.0 running in null rsrc of package com.sec.android.gallery3d
,08-31 16:50:38.119  3381  3517 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2015/SecGallery2015.apk / 1.0 running in null rsrc of package com.sec.android.gallery3d
,08-31 16:50:38.119  3381  3517 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Epic_Common/SecMms_Epic_Common.apk / 1.0 running in null rsrc of package com.android.mms
,08-31 16:50:38.119  3381  3517 W ResourcesManager: getTopLevelResources: /system/priv-app/VoiceNote_4.0/VoiceNote_4.0.apk / 1.0 running in null rsrc of package com.sec.android.app.voicenote
,08-31 16:50:38.119  3381  3517 W ResourcesManager: getTopLevelResources: /system/app/ClockPackage_M/ClockPackage_M.apk / 1.0 running in null rsrc of package com.sec.android.app.clockpackage
,08-31 16:50:38.129  3009  3009 I SurfaceFlinger: id=21 createSurf (1x1),1 flag=4, Uoast
,08-31 16:50:38.129  3381  3517 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:38.129  3381  3975 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{59adbc0 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7422834 9412:com.microsoft.office.onenote.connectionReceiverProcess/u0a12}
,08-31 16:50:38.129  3381  3517 W ResourcesManager: getTopLevelResources: /system/app/ClockPackage_M/ClockPackage_M.apk / 1.0 running in null rsrc of package com.sec.android.app.clockpackage
,08-31 16:50:38.129  3381  3517 W ResourcesManager: getTopLevelResources: /system/app/ClockPackage_M/ClockPackage_M.apk / 1.0 running in null rsrc of package com.sec.android.app.clockpackage
,08-31 16:50:38.129  3381  3517 W ResourcesManager: getTopLevelResources: /system/app/QuickConnect_40/QuickConnect_40.apk / 1.0 running in null rsrc of package com.samsung.android.qconnect
,08-31 16:50:38.139  3381  3517 D ResourcesManager: For user 0 new overlays fetched Null
,08-31 16:50:38.139  3381  3517 W ResourcesManager: getTopLevelResources: /system/app/QuickConnect_40/QuickConnect_40.apk / 1.0 running in null rsrc of package com.samsung.android.qconnect
,08-31 16:50:38.139  3381  3517 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
,08-31 16:50:38.139  3381  3517 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M/SPlanner_M.apk / 1.0 running in null rsrc of package com.android.calendar
,08-31 16:50:38.139  3381  3517 W ResourcesManager: getTopLevelResources: /system/app/SecMemo3/SecMemo3.apk / 1.0 running in null rsrc of package com.samsung.android.app.memo
,08-31 16:50:38.139  3381  3517 W ResourcesManager: getTopLevelResources: /system/app/SecMemo3/SecMemo3.apk / 1.0 running in null rsrc of package com.samsung.android.app.memo
,08-31 16:50:38.139  3381  3517 D UsbSettingsManager: clearDefaults: com.test.thalitest
,08-31 16:50:38.149  9412  9412 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
08-31 16:50:38.149  9412  9412 D RelationGraph: garbageCollect()
,08-31 16:50:38.149  4292  4292 E Launcher.Model: onPackageRemoved :com.test.thalitest
,08-31 16:50:38.149  4292  4381 E SQLiteLog: (10) unixWrite() File Descriptor : 19 gets errno : 30
,08-31 16:50:38.159  3381  4419 D SettingsProvider: isChangeAllowed() : name = klm_eula_shown
08-31 16:50:38.159  3381  4419 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
08-31 16:50:38.159  3381  4773 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{322e50e u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f68c41f 3381:system/1000}
,08-31 16:50:38.159  3381  4419 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 16:50:38.159  3381  4419 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:50:38.159  3381  4419 D SettingsProvider: selectionArgs: false
08-31 16:50:38.159  3381  4419 D SettingsProvider: selectionArgs: 10028
08-31 16:50:38.159  9412  9412 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in com.microsoft.office.onenote rsrc of package com.microsoft.office.onenote
08-31 16:50:38.159  3381  4419 D SettingsProvider: ret = -1
,08-31 16:50:38.159  4292  4381 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-31 16:50:38.159  4292  4381 E AndroidRuntime: Process: com.sec.android.app.launcher, PID: 4292
08-31 16:50:38.159  4292  4381 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
08-31 16:50:38.159  4292  4381 E AndroidRuntime: #################################################################
08-31 16:50:38.159  4292  4381 E AndroidRuntime: Error Code : 778 (SQLITE_IOERR_WRITE)
08-31 16:50:38.159  4292  4381 E AndroidRuntime: Caused By : Disk I/O error occurred during 'write' operation.
08-31 16:50:38.159  4292  4381 E AndroidRuntime: 	(disk I/O error (code 778))
08-31 16:50:38.159  4292  4381 E AndroidRuntime: #################################################################
08-31 16:50:38.159  4292  4381 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-31 16:50:38.159  4292  4381 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:679)
08-31 16:50:38.159  4292  4381 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
08-31 16:50:38.159  4292  4381 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
08-31 16:50:38.159  4292  4381 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:527)
08-31 16:50:38.159  4292  4381 E AndroidRuntime: 	at com.android.launcher2.LauncherProvider.updateAppItems(LauncherProvider.java:508)
08-31 16:50:38.159  4292  4381 E AndroidRuntime: 	at com.android.launcher2.LauncherModel$6.run(LauncherModel.java:837)
08-31 16:50:38.159  4292  4381 E AndroidRuntime: 	at com.android.launcher2.LauncherModel.updateAppItems(LauncherModel.java:841)
08-31 16:50:38.159  4292  4381 E AndroidRuntime: 	at com.android.launcher2.MenuAppLoader.removePackage(MenuAppLoader.java:862)
08-31 16:50:38.159  4292  4381 E AndroidRuntime: 	at com.android.launcher2.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3674)
08-31 16:50:38.159  4292  4381 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 16:50:38.159  4292  4381 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 16:50:38.159  4292  4381 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:158)
08-31 16:50:38.159  4292  4381 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-31 16:50:38.159  3381  4057 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3381
,08-31 16:50:38.159  3381  4428 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,08-31 16:50:38.159  9412  9412 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,08-31 16:50:38.169  3946  3946 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 272

```
