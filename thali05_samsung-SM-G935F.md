#### Test 82642184ea62b6e_thali05_samsung-SM-G935F Logs


```
--------- beginning of main
08-30 23:10:32.145  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,--------- beginning of system
08-30 23:10:32.185  3384  3856 D NetworkPolicy: isUidForegroundLocked: 10021, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
08-30 23:10:32.185  3384  3856 D NetworkPolicy: isUidForegroundLocked: 10021, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
08-30 23:10:32.225  3384  9422 I HarmonyEASService: Updating for all 1
08-30 23:10:32.325  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
08-30 23:10:32.365  9429  9429 D AASAservice-RuleManager: IsSharedUID() : pkgname - com.test.thalitest, mSharedUserId - null
08-30 23:10:32.365  9429  9429 D AASAservice-UpdateReceiver: AASAUpdateReceiver : check SharedUID package.
08-30 23:10:32.365  9429  9429 E AASAservice-UpdateReceiver: AASAUpdateReceiver : myrule is null.
08-30 23:10:32.365  9429  9429 I art     : System.exit called, status: 0
08-30 23:10:32.365  9429  9429 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-30 23:10:32.395  3384  4609 I ActivityManager: Process com.samsung.aasaservice (pid 9429)(adj 0) has died(159,1700)
08-30 23:10:32.395  3384  4609 D ActivityManager: isAutoRunBlockedApp:: com.samsung.aasaservice, Auto Run ON
08-30 23:10:32.415  3384  3510 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ae45f40 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6b27426 9006:com.samsung.android.app.appsedge/u0a1}
08-30 23:10:32.415  9006  9006 I AppsEdgeBroadcastReceiver: onReceive: android.intent.action.PACKAGE_ADDED
08-30 23:10:32.435  9486  9486 E Zygote  : v2
08-30 23:10:32.435  9486  9486 I libpersona: KNOX_SDCARD checking this for 10017
08-30 23:10:32.435  9486  9486 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
08-30 23:10:32.435  9486  9486 I libpersona: KNOX_SDCARD not a persona
08-30 23:10:32.435  9486  9486 E Zygote  : accessInfo : 0
08-30 23:10:32.435  9486  9486 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.app.galaxylabs 
08-30 23:10:32.435  3384  3978 I ActivityManager: Start proc 9486:com.samsung.android.app.galaxylabs/u0a17 for broadcast-3 com.samsung.android.app.galaxylabs/.LabsIntentReceiver
08-30 23:10:32.445  9486  9486 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 23:10:32.445  9486  9486 D ActivityThread: Added TimaKeyStore provider
08-30 23:10:32.455  3384  3853 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ae45f40 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c4c7a1d 9486:com.samsung.android.app.galaxylabs/u0a17}
08-30 23:10:32.465  9486  9486 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
08-30 23:10:32.465  9486  9486 D RelationGraph: garbageCollect()
08-30 23:10:32.465  9486  9486 W ResourcesManager: getTopLevelResources: /system/priv-app/GalaxyLabs/GalaxyLabs.apk / 1.0 running in com.samsung.android.app.galaxylabs rsrc of package com.samsung.android.app.galaxylabs
08-30 23:10:32.465  3384  4058 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
08-30 23:10:32.465  9486  9486 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
08-30 23:10:32.465  9486  9486 D ResourcesManager: For user 0 new overlays fetched Null
08-30 23:10:32.465  9486  9486 I InjectionManager: Inside getClassLibPath caller 
08-30 23:10:32.475  9486  9486 W System  : ClassLoader referenced unknown path: /system/priv-app/GalaxyLabs/lib/arm64
08-30 23:10:32.475  9486  9486 D InjectionManager: InjectionManager
08-30 23:10:32.475  9486  9486 D InjectionManager: fillFeatureStoreMap com.samsung.android.app.galaxylabs
08-30 23:10:32.475  9486  9486 I InjectionManager: Constructor com.samsung.android.app.galaxylabs, Feature store :{}
08-30 23:10:32.475  9486  9486 I InjectionManager: featureStore :{}
08-30 23:10:32.475  9486  9486 D LabsIntentReceiver: action: android.intent.action.PACKAGE_ADDED
08-30 23:10:32.475  9486  9486 D LabsIntentReceiver: pkg: com.test.thalitest
08-30 23:10:32.475  9486  9486 D LabsIntentReceiver: context: android.app.ReceiverRestrictedContext@2262ea9
08-30 23:10:32.475  9486  9486 D LabsIntentReceiver: extra: false
08-30 23:10:32.475  9486  9486 D LabsLoader: loadByPackageName: deleteDB com.test.thalitest
08-30 23:10:32.475  4309  4309 D LauncherApplication: galaxy labs setting changed!!!
08-30 23:10:32.485  3384  4250 I ActivityManager: Killing 8943:com.sec.spp.push:RemoteDlcProcess/u0a42 (adj 15): DHA:empty #33
08-30 23:10:32.485  3384  4250 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ae45f40 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{de2f82c 4339:com.google.android.gms.persistent/u0a21}
08-30 23:10:32.505  9483  9483 I FIPS_bssl: FIPS approved mode (1) | 9483 | app_process
08-30 23:10:32.505  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
08-30 23:10:32.515  9483  9483 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-30 23:10:32.515  9483  9483 D AndroidRuntime: CheckJNI is OFF
08-30 23:10:32.515  9483  9483 D AndroidRuntime: readGMSProperty: start
08-30 23:10:32.515  9483  9483 D AndroidRuntime: readGMSProperty: already setted!!
08-30 23:10:32.515  9483  9483 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-30 23:10:32.515  9483  9483 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-30 23:10:32.515  9483  9483 D AndroidRuntime: readGMSProperty: end
08-30 23:10:32.515  9483  9483 D AndroidRuntime: addProductProperty: start
08-30 23:10:32.515  3384  4473 D ActivityManager: isAutoRunBlockedApp:: com.sec.spp.push, Auto Run ON
08-30 23:10:32.535  9483  9483 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-30 23:10:32.535  3384  4315 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ae45f40 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7afc170 4612:com.google.android.gms/u0a21}
08-30 23:10:32.545  4309  4309 D LauncherApplication: galaxy labs cursor count is 0
08-30 23:10:32.555  3384  4323 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ae45f40 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7afc170 4612:com.google.android.gms/u0a21}
08-30 23:10:32.555  4612  4612 D AsyncTaskServiceImpl: Submit a task: k
08-30 23:10:32.555  9483  9483 I Radio-JNI: register_android_hardware_Radio DONE
08-30 23:10:32.565  9483  9483 E AffinityControl: AffinityControl: registerfunction enter
08-30 23:10:32.565  3384  6471 D SSRM:n  : SIOP:: AP = 430, PST = 441 (W:7), CP = 296, CUR = 133, LCD = 1
08-30 23:10:32.575  9483  9483 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-30 23:10:32.575  4612  9505 D k       : Processing package: com.test.thalitest
08-30 23:10:32.575  4612  9505 D GassUtils: Found app info for package com.test.thalitest:19. Hash: 864f03fe3ff04107c0cf32bdae9dc2051eeb22f81b585d28acec96d4114a47f5
08-30 23:10:32.575  4612  9505 D k       : Found info for package com.test.thalitest in db.
08-30 23:10:32.585  3384  4313 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ae45f40 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7afc170 4612:com.google.android.gms/u0a21}
08-30 23:10:32.595  3384  4323 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ae45f40 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7afc170 4612:com.google.android.gms/u0a21}
08-30 23:10:32.605  3384  4997 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
08-30 23:10:32.605  3384  4997 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
08-30 23:10:32.615  3384  4997 D ResourcesManager: For user 0 new overlays fetched Null
08-30 23:10:32.615  3384  4997 D GameManagerService: identifyGamePackage. com.test.thalitest
08-30 23:10:32.615  3384  4997 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
08-30 23:10:32.615  3384  4997 D ActivityManager: mDVFSHelper.acquire()
08-30 23:10:32.625  3006  3006 I SurfaceFlinger: id=16 createSurf (16x16),-1 flag=20004, EimLayer(Di
08-30 23:10:32.625  3006  3006 I SurfaceFlinger: id=17 createSurf (16x16),-1 flag=20004, EimLayer(An
08-30 23:10:32.635  3384  3384 D ViewRootImpl: MSG_RESIZED: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
08-30 23:10:32.635  3938  3938 D ViewRootImpl: MSG_RESIZED: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
08-30 23:10:32.635  3938  6544 D WallpaperService: resized:[frame]Rect(0, 0 - 2240, 2560) [newConfig] is null
08-30 23:10:32.635  3384  3384 D ViewRootImpl: MSG_RESIZED: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
08-30 23:10:32.635  3938  3938 D WallpaperService: MSG_WINDOW_RESIZED
08-30 23:10:32.635  3384  4997 D FocusedStackFrame: Set to : 0
08-30 23:10:32.635  3938  3938 D WallpaperService: updateSurface:[forceRelayout]true[redrawNeeded]false
08-30 23:10:32.635  3938  3938 V WallpaperService: Changes: creating=false format=false size=false
08-30 23:10:32.635  3938  3938 V WallpaperService: currentWidth:2240 currentHeight:2560 requestedWidth:2240 requestedWidth:2560
08-30 23:10:32.635  3938  3938 V WallpaperService: relayout result: Surface(name=null)/@0x5df849, frame=Rect(0, 0 - 2240, 2560),relayoutResult:1, mConfiguration{0 1.0 themeSeq = 0 showBtnBg = -1 ?mcc?mnc pl_PL ?layoutDir ?swdp ?wdp ?hdp ?density ?lsize ?long ?orien ?uimode ?night ?touch ?keyb/?/? ?nav/? mkbd/?}
08-30 23:10:32.635  3938  3938 V WallpaperService: Wallpaper size has changed: (2240, 2560)
08-30 23:10:32.635  3384  4997 V WindowManager: addAppToken: AppWindowToken{d08ca76db token=Token{db693ea ActivityRecord{f61cfd5 u0 com.test.thalitest/.MainActivity t37}}} to stack=2 task=37 at 0
08-30 23:10:32.645  3384  3543 I InjectionManager: Inside getClassLibPath caller 
08-30 23:10:32.655  3384  3543 D SecWifiDisplayUtil: Metadata value : SecSettings2
08-30 23:10:32.655  3384  3543 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{ccee653 V.E...... R.....ID 0,0-0,0}
08-30 23:10:32.655  3384  3543 W WindowManager: Failed looking up window
08-30 23:10:32.655  3384  3543 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@5778b90 does not exist
08-30 23:10:32.655  3384  3543 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
08-30 23:10:32.655  3384  3543 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
08-30 23:10:32.655  3384  3543 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
08-30 23:10:32.655  3384  3543 W WindowManager: 	at android.view.ViewRootImpl.pokeDrawLockIfNeeded(ViewRootImpl.java:1203)
08-30 23:10:32.655  3384  3543 W WindowManager: 	at android.view.ViewRootImpl.scheduleTraversals(ViewRootImpl.java:1415)
08-30 23:10:32.655  3384  3543 W WindowManager: 	at android.view.ViewRootImpl.requestLayout(ViewRootImpl.java:1222)
08-30 23:10:32.655  3384  3543 W WindowManager: 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:800)
08-30 23:10:32.655  3384  3543 W WindowManager: 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:337)
08-30 23:10:32.655  3384  3543 W WindowManager: 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:91)
08-30 23:10:32.655  3384  3543 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4378)
08-30 23:10:32.655  3384  3543 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
08-30 23:10:32.655  3384  3543 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 23:10:32.655  3384  3543 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
08-30 23:10:32.655  3384  3543 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 23:10:32.655  3384  3543 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-30 23:10:32.655  9509  9509 E Zygote  : v2
08-30 23:10:32.655  9509  9509 I libpersona: KNOX_SDCARD checking this for 10177
08-30 23:10:32.655  9509  9509 I libpersona: KNOX_SDCARD not a persona
08-30 23:10:32.665  9509  9509 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
08-30 23:10:32.665  3384  4997 I ActivityManager: Start proc 9509:com.test.thalitest/u0a177 for activity com.test.thalitest/.MainActivity
08-30 23:10:32.665  9509  9509 E Zygote  : accessInfo : 0
08-30 23:10:32.665  9509  9509 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
08-30 23:10:32.665  3384  3543 D ISSUE_DEBUG: InputChannelName : 1cc7c89 Starting com.test.thalitest
08-30 23:10:32.665  3938  3938 V KeyguardUpdateMonitor: onSubscriptionInfoChanged()
08-30 23:10:32.665  3384  4997 D InputDispatcher: Focused application set to: xxxx
08-30 23:10:32.665  3938  3938 V KeyguardUpdateMonitor: onSubscriptionInfoChanged: list is null
08-30 23:10:32.665  4612  9499 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
08-30 23:10:32.675  3006  3006 I SurfaceFlinger: id=18 createSurf (1x1),1 flag=404, uhalitest
08-30 23:10:32.675  3938  3938 D KeyguardCarrierText: onRefreshCarrierInfo: 
08-30 23:10:32.675  3938  3938 D KeyguardCarrierText: updateAllSlot
08-30 23:10:32.675  9483  9483 D AndroidRuntime: Shutting down VM
08-30 23:10:32.685  3938  3938 D KeyguardCarrierText: updateIntentData(): isMultiSIMState: falsesubId: 2147483643 phoneId:0plmn: Brak sieciSPN: 
08-30 23:10:32.685  3384  3449 D SecContentProvider2: query(), uri = 15 selection = getLockScreenHiddenItems
08-30 23:10:32.685  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
08-30 23:10:32.695  3938  3938 D KeyguardCarrierText: updateCarrierText(): isMultiSIMState: false
08-30 23:10:32.695  3938  3938 D KeyguardCarrierText: updateDate All slot
08-30 23:10:32.695  3938  3938 D KeyguardCarrierText: mSimState[0]ABSENT
08-30 23:10:32.695  3384  4323 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ae45f40 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{de2f82c 4339:com.google.android.gms.persistent/u0a21}
08-30 23:10:32.695  3938  3938 D KeyguardCarrierText: mSimState[1]ABSENT
08-30 23:10:32.695  3938  3938 D KeyguardCarrierText: Getting plmn/spn sticky brdcst  mPlmn:Brak sieci / mSpn:  phoneId:0 subId:2147483643 showPlmn: true showSpn:false
08-30 23:10:32.695  3938  3938 D KeyguardCarrierText: getStatusForIccState :  SIM state = ABSENT
08-30 23:10:32.695  3938  3938 D KeyguardCarrierText: makeCarrierStringOnEmergencyCapable :  mIsEmergencyCallCapable:  true
08-30 23:10:32.695  3938  3938 D KeyguardCarrierText: concatenate : plmn = Brak karty SIM, spn = Brak sieci
08-30 23:10:32.695  3938  3938 D KeyguardCarrierText: getCarrierTextForSimState :  SIM state = SimMissingcarrierText: Brak karty SIM | Brak sieci
08-30 23:10:32.695  3938  3938 D KeyguardCarrierText: Handling ABSENT , carrierTextForSimState = Brak karty SIM | Brak sieci
08-30 23:10:32.695  3384  3543 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
08-30 23:10:32.705  3938  3938 D KeyguardCarrierText: updateCarrierText insertedMultiSim = false
08-30 23:10:32.705  3938  3938 D KeyguardCarrierText: updateCarrierText State: Absent SIM Number = 0
08-30 23:10:32.705  9509  9509 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 23:10:32.705  9509  9509 D ActivityThread: Added TimaKeyStore provider
08-30 23:10:32.725  3938  3938 D KeyguardCarrierText: Getting plmn/spn sticky brdcst for Absent case Brak sieci/showPlmn: trueshowSpn: false phoneId:0 subId:2147483643
08-30 23:10:32.725  3938  3938 D KeyguardCarrierText: concatenate : plmn = Brak sieci
08-30 23:10:32.725  3938  3938 D KeyguardCarrierText: makeCarrierStringOnEmergencyCapable :  mIsEmergencyCallCapable:  true
08-30 23:10:32.725  3938  3938 D KeyguardCarrierText: concatenate : plmn = Brak karty SIM, spn = Brak sieci
08-30 23:10:32.725  3938  3938 D KeyguardCarrierText: setText :  displayText = Tryb Offline
08-30 23:10:32.725  3938  3938 D EmergencyButton: onRefreshCarrierInfo
08-30 23:10:32.725  3384  4250 D ActivityManager:  Launching com.test.thalitest, updated priority
08-30 23:10:32.735  4309  4309 V ActivityThread: updateVisibility : ActivityRecord{3480a49 token=android.os.BinderProxy@5a22d51 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
08-30 23:10:32.745  3384  3543 V WindowStateAnimator: Finishing drawing window Window{1cc7c89 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
08-30 23:10:32.755  3006  3006 D libEGL  : eglInitialize EGLDisplay = 0x7fd1ae6ea8
08-30 23:10:32.775  6208  6208 E CocktailBarPositionManager: Window direction: 0
08-30 23:10:32.775  6208  6208 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
08-30 23:10:32.775  3384  3384 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
08-30 23:10:32.785  6208  6218 I TrayUsageStatesWatcher: noteResumeComponent : ComponentInfo{com.test.thalitest/com.test.thalitest.MainActivity} Intent { flg=0x10000000 cmp=com.test.thalitest/.MainActivity VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
08-30 23:10:32.795  3006  3068 D libEGL  : eglTerminate EGLDisplay = 0x7f9cbfee78
08-30 23:10:32.795  3006  3068 D libEGL  : eglTerminate EGLDisplay = 0x7f9cbfee78
08-30 23:10:32.795  3384  4609 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-30 23:10:32.795  3384  4609 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
08-30 23:10:32.795  3384  4609 D BatteryService: online:4, current avg:-150, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:236
08-30 23:10:32.795  3384  4609 D BatteryService: stay LED for fully charged
08-30 23:10:32.795  3384  3384 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-30 23:10:32.795  3006  4507 I SurfaceFlinger: id=9 Removed MauncherAct (5/11)
08-30 23:10:32.795  3006  3017 I SurfaceFlinger: id=9 Removed MauncherAct (-2/11)
08-30 23:10:32.795  3006  3006 D libEGL  : eglTerminate EGLDisplay = 0x7fd1ae6fc8
08-30 23:10:32.805  4309  4309 D Launcher: onTrimMemory. Level: 20
08-30 23:10:32.865  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:33.045  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:33.085  6208  6208 I TrayVisibilityController: handleMessage : msg.what = 1
08-30 23:10:33.115  3384  4250 I WindowManager: Screenshot max retries 4 of Token{db693ea ActivityRecord{f61cfd5 u0 com.test.thalitest/.MainActivity t37}} appWin=Window{1cc7c89 u0 d0 Starting com.test.thalitest} drawState=4
08-30 23:10:33.115  6208  6219 I TrayUsageStatesWatcher: notePauseComponent : ComponentInfo{com.test.thalitest/com.test.thalitest.MainActivity}
08-30 23:10:33.145  9509  9509 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
08-30 23:10:33.145  9509  9509 D RelationGraph: garbageCollect()
08-30 23:10:33.145  9509  9509 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
08-30 23:10:33.155  3384  4315 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
08-30 23:10:33.155  9509  9509 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
08-30 23:10:33.155  3384  4323 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ae45f40 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{de2f82c 4339:com.google.android.gms.persistent/u0a21}
08-30 23:10:33.165  6208  6208 I Utils   : isCurrentUser current = 0, ownerId = 0
08-30 23:10:33.165  6208  6208 I TrayVisibilityController: getComputedTrayVisible : keyguardState = 3
08-30 23:10:33.165  6208  6208 I TrayVisibilityController: updateTrayVisible : State : 3 visible = 2 mCurrentVisible = 2
08-30 23:10:33.175  9509  9509 D ResourcesManager: For user 0 new overlays fetched Null
08-30 23:10:33.175  3384  3510 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
08-30 23:10:33.185  9509  9509 I InjectionManager: Inside getClassLibPath caller 
08-30 23:10:33.205  9509  9509 D InjectionManager: InjectionManager
08-30 23:10:33.205  9509  9509 D InjectionManager: fillFeatureStoreMap com.test.thalitest
08-30 23:10:33.215  4612  9499 D WearableController: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
08-30 23:10:33.215  9509  9509 I InjectionManager: Constructor com.test.thalitest, Feature store :{}
08-30 23:10:33.215  9509  9509 I InjectionManager: featureStore :{}
08-30 23:10:33.225  3384  3384 I MotionRecognitionService: Plugged
08-30 23:10:33.225  3384  3384 D MotionRecognitionService:   cableConnection= 1
08-30 23:10:33.225  3384  3384 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-30 23:10:33.225  3384  3384 D MotionRecognitionService: skip setTransmitPower. 
08-30 23:10:33.225  9509  9509 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
08-30 23:10:33.225  9509  9509 D RelationGraph: garbageCollect()
08-30 23:10:33.225  3384  3861 D WifiController: ApOrStaEnabledState  msg.what= 155652
08-30 23:10:33.225  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
08-30 23:10:33.225  3938  3938 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-30 23:10:33.225  3938  3938 D PowerUI : priorPlugType = 2 mPlugType =  2
08-30 23:10:33.225  3938  3938 D KeyguardUpdateMonitor: handleBatteryUpdate
08-30 23:10:33.225  9509  9509 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
08-30 23:10:33.235  5081  5081 D CommonServiceConfiguration: getStringValueSetting
08-30 23:10:33.235  5039  5039 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-30 23:10:33.235  5039  5435 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-30 23:10:33.245  5081  5081 D BatteryMonitor: new battery level: 100
08-30 23:10:33.245  4718  4718 D BatteryController: saveBatteryData : level[100], status[5]
08-30 23:10:33.255  9527  9527 E Zygote  : v2
08-30 23:10:33.255  9527  9527 I libpersona: KNOX_SDCARD checking this for 10025
08-30 23:10:33.255  9527  9527 I libpersona: KNOX_SDCARD not a persona
08-30 23:10:33.255  9527  9527 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
08-30 23:10:33.255  3384  4250 I ActivityManager: Start proc 9527:com.google.android.partnersetup/u0a25 for broadcast-3 com.google.android.partnersetup/.RlzPingBroadcastReceiver
08-30 23:10:33.255  9527  9527 E Zygote  : accessInfo : 0
08-30 23:10:33.265  9527  9527 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.partnersetup 
08-30 23:10:33.275  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-30 23:10:33.275  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-30 23:10:33.285  3384  6471 D GameManagerService: identifyGamePackage. com.test.thalitest
08-30 23:10:33.295  9509  9509 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310550)
08-30 23:10:33.305  3006  4591 I SurfaceFlinger: Modify Choreographer's phase offset to 0
08-30 23:10:33.305  3006  3068 I SurfaceFlinger: Modify SurfaceFlinger's phase offset to 0
08-30 23:10:33.305  9527  9527 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 23:10:33.305  9527  9527 D ActivityThread: Added TimaKeyStore provider
08-30 23:10:33.305  3384  6471 D GameManagerService: identifyGamePackage. com.test.thalitest
08-30 23:10:33.305  3384  6471 D N       : limitCPUFreq:: freq = 2496000
08-30 23:10:33.305  3384  6471 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MAX_LIMIT  frequency : 2496000  uid : 1000  pid : 3384  pkgName : SIOP_ARM_MAX@22
08-30 23:10:33.325  3384  3853 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ae45f40 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b7833f2 9527:com.google.android.partnersetup/u0a25}
08-30 23:10:33.345  9527  9527 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
08-30 23:10:33.345  9527  9527 D RelationGraph: garbageCollect()
08-30 23:10:33.345  9527  9527 W ResourcesManager: getTopLevelResources: /system/priv-app/GooglePartnerSetup/GooglePartnerSetup.apk / 1.0 running in com.google.android.partnersetup rsrc of package com.google.android.partnersetup
08-30 23:10:33.355  3384  4058 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
08-30 23:10:33.355  9527  9527 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
08-30 23:10:33.355  3384  6471 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
08-30 23:10:33.355  9527  9527 D ResourcesManager: For user 0 new overlays fetched Null
08-30 23:10:33.365  3384  6471 D GameManagerService: identifyGamePackage. com.test.thalitest
08-30 23:10:33.365  3384  6471 D N       : limitCPUFreq:: freq = -1
08-30 23:10:33.365  3384  6471 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MAX_LIMIT  frequency : 2496000  uid : 1000  pid : 3384  tag : SIOP_ARM_MAX@22
08-30 23:10:33.365  9527  9527 I InjectionManager: Inside getClassLibPath caller 
08-30 23:10:33.365  9509  9509 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package com.google.android.webview
08-30 23:10:33.375  9509  9509 D ResourcesManager: For user 0 new overlays fetched Null
08-30 23:10:33.375  9509  9509 I InjectionManager: Inside getClassLibPath caller 
08-30 23:10:33.375  9527  9527 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePartnerSetup/lib/arm64
08-30 23:10:33.375  3384  4144 E Watchdog: !@Sync 2 [08-30 23:10:33.381]
08-30 23:10:33.375  3384  6471 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
08-30 23:10:33.375  3384  6471 D GameManagerService: identifyGamePackage. com.test.thalitest
08-30 23:10:33.375  9509  9509 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-30 23:10:33.375  3384  6471 D GameManagerService: identifyGamePackage. com.test.thalitest
08-30 23:10:33.385  9527  9527 D InjectionManager: InjectionManager
08-30 23:10:33.385  9527  9527 D InjectionManager: fillFeatureStoreMap com.google.android.partnersetup
08-30 23:10:33.385  9527  9527 I InjectionManager: Constructor com.google.android.partnersetup, Feature store :{}
08-30 23:10:33.385  9527  9527 I InjectionManager: featureStore :{}
08-30 23:10:33.395  4612  9522 I PeopleContactsSync: triggerPendingContactsCleanup: no accounts
08-30 23:10:33.395  3384  4315 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity newState = 1 callingPackage = 10021
08-30 23:10:33.405  3384  4250 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ae45f40 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b7833f2 9527:com.google.android.partnersetup/u0a25}
08-30 23:10:33.405  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
08-30 23:10:33.415  9509  9509 I cr_LibraryLoader: Time to load native libraries: 20 ms (timestamps 3416-3436)
08-30 23:10:33.415  9509  9509 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
08-30 23:10:33.435  3384  3449 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ae45f40 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c19e1fe 9033:com.android.vending/u0a35}
08-30 23:10:33.435  4157  4170 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg com.android.vending,id=1003285959,extra=Bundle[mParcelledData.dataSize=84]
08-30 23:10:33.435  4157  4157 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=1003285959, samsung.notification.type=normal, samsung.people.package_name=com.android.vending}]
08-30 23:10:33.435  4157  4157 I PeopleStripeService: PeopleNotificationReceiver:3
08-30 23:10:33.435  4157  4157 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
08-30 23:10:33.435  4157  4157 I PeopleDataManager: removeNotification
08-30 23:10:33.435  4157  4157 I NotificationParser: getNotiType:com.android.vending,null
08-30 23:10:33.435  4157  4157 D PeopleDataManager: removeNotiInfo: id =1003285959,packageName=com.android.vending,isEdgeNotification=false,key=null,removeAll=false
08-30 23:10:33.435  4157  4157 D PeopleDataManager: removeNotiInfo =null
08-30 23:10:33.445  9509  9546 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
08-30 23:10:33.445  9509  9509 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {ae3aacf}
08-30 23:10:33.445  9509  9509 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
08-30 23:10:33.455  4612  9522 I PeopleDatabaseHelper: cleanUpNonGplusAccounts done.
08-30 23:10:33.465  9509  9509 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 23:10:33.485  3384  3880 D MdnieScenarioControlService:  packageName : com.test.thalitest    className : com.test.thalitest.MainActivity
08-30 23:10:33.495  9509  9509 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
08-30 23:10:33.495  9033  9033 I Finsky  : [1] com.google.android.finsky.utils.PermissionPolicies$PermissionPolicyService.onStartCommand(117): post-install permissions check for com.test.thalitest
08-30 23:10:33.495  9033  9033 W Finsky  : [1] com.google.android.finsky.FinskyApp.i(1379): No account configured on this device.
08-30 23:10:33.495  4612  9522 I PeopleContactsSync: triggerPendingContactsCleanup: no accounts
08-30 23:10:33.505  3384  4997 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ae45f40 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e9cf9d 9098:com.sec.android.app.shealth:remote/u0a39}
08-30 23:10:33.515  9033  9033 I Finsky  : [1] com.google.android.finsky.utils.bc.run(2302): Package state data is missing for com.test.thalitest
08-30 23:10:33.515  9033  9033 W Finsky  : [1] com.google.android.finsky.FinskyApp.i(1379): No account configured on this device.
08-30 23:10:33.535  9548  9548 E Zygote  : v2
08-30 23:10:33.535  9548  9548 I libpersona: KNOX_SDCARD checking this for 10043
08-30 23:10:33.535  9548  9548 I libpersona: KNOX_SDCARD not a persona
08-30 23:10:33.535  9548  9548 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
08-30 23:10:33.545  9548  9548 E Zygote  : accessInfo : 0
08-30 23:10:33.545  9548  9548 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.voiceserviceplatform 
08-30 23:10:33.545  3384  4058 I ActivityManager: Start proc 9548:com.samsung.voiceserviceplatform/u0a43 for broadcast-3 com.samsung.voiceserviceplatform/com.samsung.vsf.sharedlib.utils.TTSPlayer$TTSDownloadReceiver
08-30 23:10:33.555  3384  4315 I ActivityManager: Killing 8964:com.sec.spp.push:RemoteNotiProcess/u0a42 (adj 15): DHA:empty #33
08-30 23:10:33.575  9548  9548 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 23:10:33.575  9548  9548 D ActivityThread: Added TimaKeyStore provider
08-30 23:10:33.575  3384  4058 D ActivityManager: isAutoRunBlockedApp:: com.sec.spp.push, Auto Run ON
08-30 23:10:33.585  3384  3880 I MdnieScenarioControlService: mGameModeLauncher : false
08-30 23:10:33.585  3384  3880 I MdnieScenarioControlService: setUIMode
08-30 23:10:33.585  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
08-30 23:10:33.595  3384  4315 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ae45f40 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6968f31 9548:com.samsung.voiceserviceplatform/u0a43}
08-30 23:10:33.595  9509  9509 D libEGL  : eglInitialize EGLDisplay = 0xffd67a6c
08-30 23:10:33.605  9548  9548 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
08-30 23:10:33.605  9548  9548 D RelationGraph: garbageCollect()
08-30 23:10:33.605  9548  9548 W ResourcesManager: getTopLevelResources: /system/priv-app/SVoice_1.0/SVoice_1.0.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.samsung.voiceserviceplatform
08-30 23:10:33.605  3384  3853 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
08-30 23:10:33.605  9548  9548 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
08-30 23:10:33.605  9548  9548 D ResourcesManager: For user 0 new overlays fetched Null
08-30 23:10:33.615  9548  9548 I InjectionManager: Inside getClassLibPath caller 
08-30 23:10:33.615  3384  3510 W ActivityManager: Activity pause timeout for ActivityRecord{f61cfd5 u0 com.test.thalitest/.MainActivity t37}
08-30 23:10:33.645  3384  4250 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10177
08-30 23:10:33.645  3384  4250 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29734 com.android.server.am.ActivityManagerService.registerReceiver:22599 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
08-30 23:10:33.745  9509  9509 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
08-30 23:10:33.745  9548  9548 I BNRClientProivder, VERSION : 1.7.8: register - started.
08-30 23:10:33.765  9509  9509 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
08-30 23:10:33.765  9509  9509 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
08-30 23:10:33.765  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
08-30 23:10:33.795  9509  9509 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
08-30 23:10:33.835  9509  9509 D Activity: performCreate Call Injection manager
08-30 23:10:33.835  9509  9509 I InjectionManager: dispatchOnViewCreated > Target : com.test.thalitest.MainActivity isFragment :false
08-30 23:10:33.835  9509  9509 D SecWifiDisplayUtil: Metadata value : SecSettings2
08-30 23:10:33.845  9509  9509 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{386c045 I.E...... R.....ID 0,0-0,0}
08-30 23:10:33.845  9509  9595 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
08-30 23:10:33.855  3384  4054 W WindowManager: Failed looking up window
08-30 23:10:33.855  3384  4054 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@63f454c does not exist
08-30 23:10:33.855  3384  4054 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
08-30 23:10:33.855  3384  4054 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
08-30 23:10:33.855  3384  4054 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
08-30 23:10:33.855  3384  4054 W WindowManager: 	at android.view.IWindowSession$Stub.onTransact(IWindowSession.java:688)
08-30 23:10:33.855  3384  4054 W WindowManager: 	at com.android.server.wm.Session.onTransact(Session.java:139)
08-30 23:10:33.855  3384  4054 W WindowManager: 	at android.os.Binder.execTransact(Binder.java:453)
08-30 23:10:33.855  3384  3449 D ISSUE_DEBUG: InputChannelName : 4d5d995 com.test.thalitest/com.test.thalitest.MainActivity
08-30 23:10:33.855  3384  3978 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
08-30 23:10:33.855  3384  3978 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-30 23:10:33.855  3384  3384 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-30 23:10:33.855  3384  3384 I KnoxTimeoutHandler: Shared devices show user statefalse
08-30 23:10:33.855  9509  9509 V ActivityThread: updateVisibility : ActivityRecord{b7474cb token=android.os.BinderProxy@3b66e2 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-30 23:10:33.865  9509  9546 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
08-30 23:10:33.865  9548  9548 I BNRClientProivder, VERSION : 1.7.8: register - xml6 quick_backup : SVOICESETTING, bLEmzxKOex, com.samsung.voiceserviceplatform.SCloudBackUp
08-30 23:10:33.875  9548  9548 I QBNRClientHelper: init SyncClientHelper : SVOICESETTING
08-30 23:10:33.885  9509  9509 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10177, CallingPid : 9509
08-30 23:10:33.885  3384  3853 D ConnectivityService: listenForNetwork for Listen from uid/pid:10177/9509 for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 23:10:33.885  9548  9548 I l       : :main:VSP::S Voice language is null. Set to System Locale
08-30 23:10:33.885  3384  3867 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
08-30 23:10:33.885  3384  3867 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-30 23:10:33.885  9548  9548 I l       : :main:VSP::setLocale locale : pl_PL
08-30 23:10:33.885  9548  9548 W ResourcesManager: getTopLevelResources: /system/priv-app/SVoice_1.0/SVoice_1.0.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.samsung.voiceserviceplatform
08-30 23:10:33.885  9548  9548 D ResourcesManager: For user 0 new overlays fetched Null
08-30 23:10:33.895  9548  9548 I QuickDialApplication: :main:VSP::QuickDialApplication Started ver:1.9.35-130 (193502130
08-30 23:10:33.895  3384  3867 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
08-30 23:10:33.905  9548  9548 I VoiceServicePlatformApp:main:  : VSP::SvoiceApp Oncreate()
08-30 23:10:33.905  3384  3867 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-30 23:10:33.915  9509  9509 D SecWifiDisplayUtil: Metadata value : SecSettings2
08-30 23:10:33.915  9548  9548 I AppSessionManager:main:  : VSP::init() Update from sharedpref
08-30 23:10:33.915  9548  9548 I AppSessionManager:main:  : VSP::init() Update from sharedpref
08-30 23:10:33.915  3384  3867 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,08-30 23:10:33.915  3384  3867 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,08-30 23:10:33.925  3384  3867 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,08-30 23:10:33.925  3384  3867 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 23:10:33.925  3006  3006 I SurfaceFlinger: id=19 createSurf (1x1),1 flag=404, NainActivit
,08-30 23:10:33.935  9601  9601 E Zygote  : v2
08-30 23:10:33.935  9601  9601 I libpersona: KNOX_SDCARD checking this for 10043
08-30 23:10:33.935  9601  9601 I libpersona: KNOX_SDCARD not a persona
,08-30 23:10:33.935  9601  9601 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,08-30 23:10:33.935  9601  9601 E Zygote  : accessInfo : 0
08-30 23:10:33.935  3384  3449 I ActivityManager: Start proc 9601:com.samsung.svoice.sync/u0a43 for content provider com.samsung.svoice.sync/com.svoice.upload.database.PLMProvider
,08-30 23:10:33.935  9601  9601 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.svoice.sync 
,08-30 23:10:33.945  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:33.955  9509  9595 D libEGL  : eglInitialize EGLDisplay = 0xdc93f7c4
08-30 23:10:33.955  9509  9595 I OpenGLRenderer: Initialized EGL, version 1.4
,08-30 23:10:33.965  9509  9595 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,08-30 23:10:33.965  9601  9601 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 23:10:33.965  9601  9601 D ActivityThread: Added TimaKeyStore provider
,08-30 23:10:33.975  3384  4054 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3384
08-30 23:10:33.975  3384  4054 I libsuspend: !@autosuspend_wakeup_count_disable
08-30 23:10:33.975  3384  4054 D PowerManagerService: mDisplayReady: false
08-30 23:10:33.975  3384  4054 I libsuspend: !@autosuspend_wakeup_count_disable done
08-30 23:10:33.975  3384  3547 D DisplayPowerController: animateScreenStateChange[0]: target=3
08-30 23:10:33.975  3384  4054 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
,08-30 23:10:33.975  3384  3547 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
08-30 23:10:33.975  3384  3547 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
08-30 23:10:33.975  3384  3547 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
08-30 23:10:33.975  3384  3560 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
,08-30 23:10:33.975  3384  3543 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
08-30 23:10:33.975  3384  3543 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
,08-30 23:10:33.985  3006  3006 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fa3583c00
,08-30 23:10:33.985  3006  3006 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
,08-30 23:10:33.995  3384  3547 D DisplayPowerController: animateScreenStateChange[0]: target=3
08-30 23:10:33.995  3384  3547 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
08-30 23:10:33.995  3384  3547 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
08-30 23:10:33.995  3384  3547 I libsuspend: !@autosuspend_wakeup_count_enable
08-30 23:10:33.995  3384  3547 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
08-30 23:10:33.995  3384  3547 I libsuspend: !@autosuspend_wakeup_count_enable done
08-30 23:10:33.995  3384  3547 D DisplayPowerController: animateScreenStateChange[0]: target=3
08-30 23:10:33.995  3384  3547 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
08-30 23:10:33.995  3384  3547 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
08-30 23:10:33.995  3384  3547 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
08-30 23:10:33.995  3384  3547 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
08-30 23:10:33.995  3384  3547 D PowerManagerService: mDisplayReady: true
08-30 23:10:33.995  3384  3547 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,08-30 23:10:34.005  6208  6208 E CocktailBarPositionManager: Window direction: 0
08-30 23:10:34.005  6208  6208 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,08-30 23:10:34.025  9509  9509 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-30 23:10:34.035  9601  9601 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,08-30 23:10:34.035  9601  9601 D RelationGraph: garbageCollect()
,08-30 23:10:34.035  9601  9601 W ResourcesManager: getTopLevelResources: /system/priv-app/SVoicePLM_1.0/SVoicePLM_1.0.apk / 1.0 running in com.samsung.svoice.sync rsrc of package com.samsung.svoice.sync
08-30 23:10:34.035  3384  3448 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
08-30 23:10:34.035  9601  9601 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
08-30 23:10:34.045  3384  3853 V WindowStateAnimator: Finishing drawing window Window{4d5d995 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
08-30 23:10:34.045  9509  9509 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
08-30 23:10:34.045  9601  9601 D ResourcesManager: For user 0 new overlays fetched Null
08-30 23:10:34.045  9601  9601 I InjectionManager: Inside getClassLibPath caller 
08-30 23:10:34.045  3384  4058 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3384
08-30 23:10:34.055  3384  3543 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-30 23:10:34.055  3384  3384 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-30 23:10:34.055  3384  3978 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3384
08-30 23:10:34.055  3384  3543 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +937ms (total +1s412ms)
08-30 23:10:34.055  3384  3384 I KnoxTimeoutHandler: SD activityfalse
08-30 23:10:34.055  3384  4473 V WindowStateAnimator: Finishing drawing window Window{4d5d995 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
08-30 23:10:34.055  9509  9509 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3b66e2 time:74076
08-30 23:10:34.055  3384  3543 D ActivityManager: mDVFSHelper.release()
08-30 23:10:34.055  3384  3543 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{f61cfd5 u0 com.test.thalitest/.MainActivity t37} time:74078
08-30 23:10:34.055  3384  3543 D ViewRootImpl: #3 mView = null
08-30 23:10:34.055  3006  3017 I SurfaceFlinger: id=18 Removed uhalitest (6/11)
08-30 23:10:34.065  3006  3017 I SurfaceFlinger: id=18 Removed uhalitest (-2/11)
,08-30 23:10:34.075  9601  9601 I UploadDatabase: svoicelocal DB: main : PLM :: mUploadDBManager is null , creating new one !! 
,08-30 23:10:34.075  9509  9613 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 23:10:34.075  9509  9613 D libEGL  : eglInitialize EGLDisplay = 0xdc13f3f4
,08-30 23:10:34.085  3006  3006 D libEGL  : eglTerminate EGLDisplay = 0x7fd1ae6fc8
,08-30 23:10:34.085  9601  9601 E SQLiteLog: (5) statement aborts at 2: [PRAGMA journal_mode=PERSIST] 
,08-30 23:10:34.085  9601  9601 W SQLiteConnection: Could not change the database journal mode of '/data/user/0/com.samsung.svoice.sync/databases/svoicelocal.db' from 'wal' to 'PERSIST' because the database is locked.  This usually means that there are other open connections to the database which prevents the database from enabling or disabling write-ahead logging mode.  Proceeding without changing the journal mode.
,08-30 23:10:34.095  9601  9601 D InjectionManager: InjectionManager
08-30 23:10:34.095  9601  9601 D InjectionManager: fillFeatureStoreMap com.samsung.svoice.sync
,08-30 23:10:34.095  9601  9601 I InjectionManager: Constructor com.samsung.svoice.sync, Feature store :{}
08-30 23:10:34.095  9601  9601 I InjectionManager: featureStore :{}
,08-30 23:10:34.095  9601  9612 D PLMProvider: match for uri : content://com.samsung.svoice.sync/tos_accepted is : 8
,08-30 23:10:34.095  9509  9613 D libGLESv2: DTS_GLAPI : DTS is not allowed for Package : com.test.thalitest
,08-30 23:10:34.105  9548  9548 I SVFSettings:main:  : VSP::inside updateAppLocale() en_US
,08-30 23:10:34.105  9548  9548 I SVFSettings:main:  : VSP::Current locale string in updateAppLocale method en-US
,08-30 23:10:34.105  9548  9548 I SVFSettings:main:  : VSP::After updateing N66_ComamndHandler current locale is en-US
,08-30 23:10:34.115  9548  9548 D DeviceInfo: DeviceInfo
,08-30 23:10:34.125  9548  9548 D DeviceInfo: getLocale =  en-US
08-30 23:10:34.125  9548  9548 I N66_CommonHandler:main:  : VSP:: locale info at present in updateServerBasedOnlanguage : en-US
08-30 23:10:34.125  9548  9548 I N66_CommonHandler:main:  : VSP::Current configured server is interaction-us2.samsung-svoice.com
08-30 23:10:34.125  9548  9548 I N66_CommonHandler:main:  : VSP::Current configured server port is 443
,08-30 23:10:34.125  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:34.135  9548  9548 D SettingsValueDB:main:  : VSP:: match for uri : content://com.samsung.voiceserviceplatform.database.SettingsValueDB/SettingsvalueTb is : -1
,08-30 23:10:34.135  9548  9548 D SettingsValueDB:main:  : VSP::URI didnt match
,08-30 23:10:34.135  9548  9548 D SettingsValueDB:main:  : VSP:: match for uri : content://com.samsung.voiceserviceplatform.database.SettingsValueDB/SettingsvalueTb is : -1
08-30 23:10:34.135  9548  9548 D SettingsValueDB:main:  : VSP::URI didnt match
,08-30 23:10:34.135  9509  9509 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9509
,08-30 23:10:34.135  9548  9548 D SettingsValueDB:main:  : VSP:: match for uri : content://com.samsung.voiceserviceplatform.database.SettingsValueDB/language is : 3
08-30 23:10:34.135  9548  9548 D SettingsValueDB:main:  : VSP::lang from content values is  en_US
08-30 23:10:34.135  9548  9548 I skwskw:main:  : VSP::############################122 value : en_US
,08-30 23:10:34.145  9601  9611 D PLMProvider: match for uri : content://com.samsung.svoice.sync/tos_accepted is : 8
,08-30 23:10:34.145  9548  9548 I N66_CommonHandler:main:  : VSP:: rowUpdated : 1
,08-30 23:10:34.145  9548  9548 D SVFSettings: updateServerBasedOnLang() connect to server US_PROD2_SERVER_HOST_IP
,08-30 23:10:34.145  9548  9548 D p       : :main:VSP::setTargetServerAddress() : interaction-us2.samsung-svoice.com
08-30 23:10:34.145  9548  9548 D p       : :main:VSP::setTargetServerPort() : 443
,08-30 23:10:34.185  9548  9548 W ResourcesManager: getTopLevelResources: /system/app/SamsungTTS/SamsungTTS.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.samsung.SMT
,08-30 23:10:34.185  9548  9548 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:34.185  9548  9548 W ResourcesManager: getTopLevelResources: /system/app/GoogleTTS/GoogleTTS.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.tts
,08-30 23:10:34.195  9548  9548 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:34.205  3384  3384 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3384 (0x0)
,08-30 23:10:34.205  3384  3384 I libsuspend: !@autosuspend_wakeup_count_disable
08-30 23:10:34.205  3384  3384 D PowerManagerService: mDisplayReady: false
08-30 23:10:34.205  3384  3384 I libsuspend: !@autosuspend_wakeup_count_disable done
08-30 23:10:34.205  3384  3547 D DisplayPowerController: animateScreenStateChange[0]: target=4
08-30 23:10:34.205  3006  3006 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7fa3583c00
08-30 23:10:34.205  3384  3384 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
08-30 23:10:34.205  3006  3006 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
08-30 23:10:34.205  3384  3547 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
08-30 23:10:34.205  3384  3547 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
08-30 23:10:34.205  3384  3547 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
08-30 23:10:34.205  3384  3560 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
08-30 23:10:34.205  3384  3543 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
08-30 23:10:34.205  3384  3543 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
,08-30 23:10:34.215  9621  9621 E Zygote  : v2
08-30 23:10:34.215  9621  9621 I libpersona: KNOX_SDCARD checking this for 1000
08-30 23:10:34.215  9621  9621 I libpersona: KNOX_SDCARD not a persona
08-30 23:10:34.215  9621  9621 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,08-30 23:10:34.215  3384  4054 I ActivityManager: Start proc 9621:com.samsung.SMT/1000 for service com.samsung.SMT/.SamsungTTSService
08-30 23:10:34.215  3384  6472 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
08-30 23:10:34.215  9621  9621 E Zygote  : accessInfo : 0
,08-30 23:10:34.225  3384  3547 D DisplayPowerController: animateScreenStateChange[0]: target=4
08-30 23:10:34.225  3384  3547 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
08-30 23:10:34.225  3384  3547 I libsuspend: !@autosuspend_wakeup_count_enable
08-30 23:10:34.225  3384  3547 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
08-30 23:10:34.225  3384  3547 I libsuspend: !@autosuspend_wakeup_count_enable done
08-30 23:10:34.225  3384  3547 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
08-30 23:10:34.225  3384  3547 D DisplayPowerController: animateScreenStateChange[0]: target=4
08-30 23:10:34.225  3384  3547 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
08-30 23:10:34.225  3384  3547 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
08-30 23:10:34.225  3384  3547 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
08-30 23:10:34.225  3384  3547 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
08-30 23:10:34.225  3384  3547 D PowerManagerService: mDisplayReady: true
08-30 23:10:34.225  3384  3547 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,08-30 23:10:34.225  9548  9548 I TextToSpeech: Sucessfully bound to com.samsung.SMT
08-30 23:10:34.225  9548  9548 D Test    : Creating TTS instance!
,08-30 23:10:34.225  6208  6208 E CocktailBarPositionManager: Window direction: 0
08-30 23:10:34.225  6208  6208 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,08-30 23:10:34.245  9548  9548 I SamsungHTTPClient:main:  : VSP::MY THREAD ID UI : 1
,08-30 23:10:34.245  9621  9621 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 23:10:34.245  9621  9621 D ActivityThread: Added TimaKeyStore provider
,08-30 23:10:34.255  9601  9612 D PLMProvider: match for uri : content://com.samsung.svoice.sync/device_id is : 1
,08-30 23:10:34.255  9601  9612 D PLMDeviceInfo: Binder_2 : PLM ::Device Id generation is complete
,08-30 23:10:34.265  9548  9548 I svoiceapi_jar: RELEASE_DATE 2016 May 25
08-30 23:10:34.265  9548  9548 I svoiceapi_jar: RELEASE_VER  0.99_26_1_TCP_Prepare2_TTS
08-30 23:10:34.265  9548  9548 I svoiceapi_jar: Loading svoice dll
,08-30 23:10:34.265  9621  9621 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,08-30 23:10:34.265  9621  9621 D RelationGraph: garbageCollect()
,08-30 23:10:34.275  9621  9621 W ResourcesManager: getTopLevelResources: /system/app/SamsungTTS/SamsungTTS.apk / 1.0 running in com.samsung.SMT rsrc of package com.samsung.SMT
,08-30 23:10:34.275  3384  4315 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,08-30 23:10:34.275  9621  9621 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,08-30 23:10:34.275  9621  9621 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:34.275  9621  9621 I InjectionManager: Inside getClassLibPath caller 
,08-30 23:10:34.285  9621  9621 W System  : ClassLoader referenced unknown path: /system/app/SamsungTTS/lib/arm64
,08-30 23:10:34.285  9621  9621 D InjectionManager: InjectionManager
,08-30 23:10:34.285  9621  9621 D InjectionManager: fillFeatureStoreMap com.samsung.SMT
08-30 23:10:34.295  9621  9621 I InjectionManager: Constructor com.samsung.SMT, Feature store :{}
08-30 23:10:34.295  9621  9621 I InjectionManager: featureStore :{}
,08-30 23:10:34.295  9548  9548 I svoiceapi_jar: Loading success
,08-30 23:10:34.305  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:34.305  9548  9548 I svoiceapi: SVoiceSession Release Date : 2016 May 25
08-30 23:10:34.305  9548  9548 I svoiceapi: Library Ver : 0.99_26_1_TCP_Prepare2_TTS
08-30 23:10:34.305  9548  9548 I svoiceapi: SVoiceSession::SVoiceSession, Default loglevel = 5
08-30 23:10:34.305  9548  9548 I svoiceapi: create handle : 0xf4eb2bc0
08-30 23:10:34.305  9548  9548 I svoiceapi: Sentinel registered : -294088496
08-30 23:10:34.305  9548  9548 I svoiceapi: SVoiceSession::Enable logs, loglevel = 4
08-30 23:10:34.305  9548  9548 I sessionThread:main:  : VSP::LOG_LEVEL is set as 4
,08-30 23:10:34.315  9548  9548 D ClientSDKManager : initNLUResponseList
08-30 23:10:34.315  9548  9548 D InjectionManager: InjectionManager
08-30 23:10:34.315  9548  9548 D InjectionManager: fillFeatureStoreMap com.samsung.voiceserviceplatform
08-30 23:10:34.315  9548  9548 I InjectionManager: Constructor com.samsung.voiceserviceplatform, Feature store :{}
08-30 23:10:34.315  9548  9548 I InjectionManager: featureStore :{}
08-30 23:10:34.315  9548  9642 I sessionThread: DEBUG : SDK : Session Thread run got called : 
08-30 23:10:34.315  9548  9548 I SV_TTSPlayer: inside TTSDownloadReceiver
08-30 23:10:34.315  9548  9642 I sessionThread:SessionThread:  : VSP::Inside processTask while loop; task is empty so sleeping : 
,08-30 23:10:34.325  9548  9548 I VoiceFrameworkService:main:  : VSP::Oncreate() of Service
,08-30 23:10:34.325  9548  9548 I VoiceFrameworkServiceHandler:main:  : VSP::VoiceFrameworkServiceHandler() Start
,08-30 23:10:34.325  9548  9548 I VoiceFrameworkServiceHandler:main:  : VSP::MyHandlerThread
08-30 23:10:34.325  9548  9548 I VoiceFrameworkServiceHandler:main:  : VSP::VoiceFrameworkServiceHandler() end
,08-30 23:10:34.325  9548  9643 I VoiceFrameworkServiceHandler:VoiceFrameworkServiceHandler MyHandlerThread:  : VSP::MyHandlerThread run
,08-30 23:10:34.335  3384  4761 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ae45f40 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cde10f6 4408:android.process.acore/u0a5}
,08-30 23:10:34.335  9548  9548 I VoiceFrameworkServiceHandler:main:  : VSP::sendMessagetoHandler Rcvd msgCode = 0
08-30 23:10:34.335  9548  9548 I VoiceFrameworkServiceHandler:main:  : VSP::sendMessagetoHandler mHandler = Handler (com.samsung.vsf.core.framework.VoiceFrameworkServiceHandler$MyHandlerThread$1) {4fbab65}
08-30 23:10:34.335  9548  9548 I VoiceFrameworkServiceHandler:main:  : VSP:: sendMessagetoHandler() VSF Thread isAlive : true
08-30 23:10:34.335  9548  9548 I VoiceFrameworkServiceHandler:main:  : VSP::mHandler is not null msgCode =0
08-30 23:10:34.335  9548  9643 I VoiceFrameworkServiceHandler:VoiceFrameworkServiceHandler MyHandlerThread:  : VSP::MSG_VSF_INIT Rcvd
08-30 23:10:34.335  9548  9643 I VoiceFrameworkServiceHandler:VoiceFrameworkServiceHandler MyHandlerThread:  : VSP::VSFInit()
08-30 23:10:34.335  9548  9643 I VoiceServicePlatformSdk:VoiceFrameworkServiceHandler MyHandlerThread:  : VSP::Oncreate()
,08-30 23:10:34.395  4612  7728 I Icing   : Indexing E1051AF754FD4764B2B13213EB917898AAC96AFB from com.google.android.gms
,08-30 23:10:34.395  9509  9509 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-30 23:10:34.435  9601  9611 D PLMProvider: match for uri : content://com.samsung.svoice.sync/tos_accepted is : 8
,08-30 23:10:34.445  9548  9643 I SessionRuntime:VoiceFrameworkServiceHandler MyHandlerThread:  : VSP::Current Network State is same as previous, so ignoring
,08-30 23:10:34.445  9644  9644 E Zygote  : v2
08-30 23:10:34.445  9644  9644 I libpersona: KNOX_SDCARD checking this for 1000
08-30 23:10:34.445  9644  9644 I libpersona: KNOX_SDCARD not a persona
,08-30 23:10:34.445  9644  9644 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,08-30 23:10:34.455  9644  9644 E Zygote  : accessInfo : 0
,08-30 23:10:34.455  3384  4761 I ActivityManager: Start proc 9644:com.android.settings/1000 for broadcast-3 com.android.settings/.applock.PackageActionReceiver
,08-30 23:10:34.465  3384  3448 I ActivityManager: Killing 9113:com.samsung.android.app.taskedge/u0a67 (adj 15): DHA:empty #33
,08-30 23:10:34.475  9548  9643 I System.out: SVoiceProfiling : time taken to finish oncreate : 133
,08-30 23:10:34.475  9644  9644 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 23:10:34.475  9644  9644 D ActivityThread: Added TimaKeyStore provider
,08-30 23:10:34.485  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:34.495  9548  9548 I SessionRuntime:main:  : VSP::Current Network State is same as previous, so ignoring
,08-30 23:10:34.495  9509  9645 D jxcore_app_log: JniHelper::setJavaVM(0xf4f34000), pthread_self() = -644351696
,08-30 23:10:34.495  9509  9645 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 23:10:34.495  9509  9645 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 23:10:34.495  9509  9645 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 23:10:34.495  9509  9645 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 23:10:34.495  9509  9645 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-30 23:10:34.495  9509  9645 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23144b5 added. We now have 1 listener(s)
,08-30 23:10:34.505  9548  9643 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'void android.location.LocationManager.requestLocationUpdates(long, float, android.location.Criteria, android.location.LocationListener, android.os.Looper)' on a null object reference
,08-30 23:10:34.505  3384  4761 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ae45f40 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{389086f 9644:com.android.settings/1000}
,08-30 23:10:34.505  9509  9645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: A8:81:95:E9:5F:6F
08-30 23:10:34.505  9509  9645 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
08-30 23:10:34.505  9509  9645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 23:10:34.505  9509  9645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 23:10:34.505  9509  9645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 23:10:34.505  9509  9645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 23:10:34.505  9509  9645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 23:10:34.505  9509  9645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: A8:81:95:E9:5F:6F
08-30 23:10:34.505  9509  9645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 23:10:34.505  9509  9645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 23:10:34.505  9509  9645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 23:10:34.505  9509  9645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 23:10:34.505  9509  9645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 23:10:34.505  9509  9645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 23:10:34.505  9509  9645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 23:10:34.505  9509  9645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 23:10:34.505  9509  9645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 23:10:34.505  9509  9645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-30 23:10:34.505  9509  9645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eafa7d8 added. We now have 1 listener(s)
08-30 23:10:34.505  9509  9645 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 23:10:34.505  9509  9645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 23:10:34.505  9509  9645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-30 23:10:34.505  9509  9645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-30 23:10:34.505  9509  9645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-30 23:10:34.505  9509  9645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-30 23:10:34.515  9548  9643 W System.err: 	at com.samsung.vsf.core.framework.SessionRuntime.requestLocationUpdate(SessionRuntime.java:336)
08-30 23:10:34.515  9548  9643 W System.err: 	at com.samsung.vsf.core.framework.SessionRuntime.registerNetworkReceiver(SessionRuntime.java:246)
08-30 23:10:34.515  9548  9643 W System.err: 	at com.samsung.vsf.core.framework.SessionRuntime.registerBroadcastReceivers(SessionRuntime.java:115)
08-30 23:10:34.515  9548  9643 W System.err: 	at com.samsung.vsf.core.framework.SessionRuntime.init(SessionRuntime.java:103)
08-30 23:10:34.515  3384  3449 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.taskedge, Auto Run ON
08-30 23:10:34.515  9548  9643 W System.err: 	at com.samsung.vsf.core.framework.VoiceFrameworkServiceHandler.VSFInit(VoiceFrameworkServiceHandler.java:188)
08-30 23:10:34.515  9548  9643 W System.err: 	at com.samsung.vsf.core.framework.VoiceFrameworkServiceHandler.access$200(VoiceFrameworkServiceHandler.java:27)
08-30 23:10:34.515  9548  9643 W System.err: 	at com.samsung.vsf.core.framework.VoiceFrameworkServiceHandler$MyHandlerThread$1.handleMessage(VoiceFrameworkServiceHandler.java:109)
08-30 23:10:34.515  9548  9643 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 23:10:34.515  9548  9643 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-30 23:10:34.515  9548  9643 W System.err: 	at com.samsung.vsf.core.framework.VoiceFrameworkServiceHandler$MyHandlerThread.run(VoiceFrameworkServiceHandler.java:178)
08-30 23:10:34.515  9548  9643 I EmbeddedFrameworkManager:VoiceFrameworkServiceHandler MyHandlerThread:  : VSP::N66 locale is en_US
08-30 23:10:34.515  3384  4058 I AppOps  : sendInfoToFLP, code=41 , uid=10043 , packageName=com.samsung.voiceserviceplatform , type=startOp
08-30 23:10:34.525  4219  4219 D FusedRequestManager: manageLocationRequest, new passive request from com.samsung.voiceserviceplatform with a615205 , interval = 1800000 through LocationManagerService
08-30 23:10:34.525  9548  9643 I EmbeddedFrameworkManager:VoiceFrameworkServiceHandler MyHandlerThread:  : VSP::SHL init():
08-30 23:10:34.525  9548  9643 I EmbeddedFrameworkManager:VoiceFrameworkServiceHandler MyHandlerThread: SHL Config:
08-30 23:10:34.525  9548  9643 I EmbeddedFrameworkManager:VoiceFrameworkServiceHandler MyHandlerThread: Locale: en_US
08-30 23:10:34.525  9548  9643 I EmbeddedFrameworkManager:VoiceFrameworkServiceHandler MyHandlerThread: Recognition Path: EMBEDDED
08-30 23:10:34.525  9548  9643 I EmbeddedFrameworkManager:VoiceFrameworkServiceHandler MyHandlerThread: Audio buffer format: PCM_NS
08-30 23:10:34.525  9548  9643 I EmbeddedFrameworkManager:VoiceFrameworkServiceHandler MyHandlerThread: Use internal recorder: false
08-30 23:10:34.525  9548  9643 I EmbeddedFrameworkManager:VoiceFrameworkServiceHandler MyHandlerThread: Use internal EPD: false
08-30 23:10:34.525  9548  9643 I SHL:VoiceFrameworkServiceHandler MyHandlerThread:  : VSP::SHL Initialize
08-30 23:10:34.525  9548  9643 I etickcount:VoiceFrameworkServiceHandler MyHandlerThread:  : VSP::PocketSphinxEngine:Trying to load libEmbeddedAsr.so
08-30 23:10:34.525  9509  9645 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 23:10:34.525  9509  9645 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is A8:81:95:E9:5F:6F
08-30 23:10:34.535  9509  9645 D BluetoothAdapter: STATE_ON
08-30 23:10:34.535  9644  9644 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
08-30 23:10:34.535  9644  9644 D RelationGraph: garbageCollect()
,08-30 23:10:34.545  4408  4467 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
08-30 23:10:34.545  4408  4467 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
08-30 23:10:34.545  9644  9644 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in com.android.settings rsrc of package com.android.settings
08-30 23:10:34.545  9509  9645 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-30 23:10:34.545  9509  9645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 23:10:34.545  9509  9645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 23:10:34.545  9509  9645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 23:10:34.545  9509  9645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 23:10:34.545  9509  9645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 23:10:34.545  9509  9645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 23:10:34.545  9509  9645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 23:10:34.545  9509  9645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 23:10:34.545  9509  9645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-30 23:10:34.545  9509  9645 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 23:10:34.545  9509  9645 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 23:10:34.545  3384  4609 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
08-30 23:10:34.545  9644  9644 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
08-30 23:10:34.555  9509  9509 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 23:10:34.555  9644  9644 D ResourcesManager: For user 0 new overlays fetched Null
08-30 23:10:34.555  9548  9643 I etickcount:VoiceFrameworkServiceHandler MyHandlerThread:  : VSP::PocketSphinxEngine:loading libEmbeddedAsr.so done
08-30 23:10:34.565  9644  9644 I InjectionManager: Inside getClassLibPath caller 
08-30 23:10:34.565  9509  9509 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 23:10:34.575  9548  9643 I etickcount:VoiceFrameworkServiceHandler MyHandlerThread:  : VSP::State changed to NULL
08-30 23:10:34.575  9548  9643 I etickcount:VoiceFrameworkServiceHandler MyHandlerThread:  : VSP::Creating engines for en_US
08-30 23:10:34.575  9548  9643 D CMDTest : VoiceFrameworkServiceHandler MyHandlerThread : posted CreateCmd
08-30 23:10:34.575  9548  9643 I etickcount:VoiceFrameworkServiceHandler MyHandlerThread:  : VSP::RecognitionManager loading..
08-30 23:10:34.575  9509  9509 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
08-30 23:10:34.575  9548  9664 D tickcount:PocketSphinx Recognition Engine:  : VSP::CreateCmd execution latency: 1ms
08-30 23:10:34.575  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP::PocketSphinxEngine:create()
08-30 23:10:34.575  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP::State changed to INIT
08-30 23:10:34.575  9644  9644 W System  : ClassLoader referenced unknown path: /system/priv-app/SecSettings2/lib/arm64
,08-30 23:10:34.585  9548  9643 D CMDTest : VoiceFrameworkServiceHandler MyHandlerThread : posted ConfigureCmd
08-30 23:10:34.585  9548  9643 I etickcount:VoiceFrameworkServiceHandler MyHandlerThread:  : VSP::State changed to INIT
08-30 23:10:34.585  9548  9664 D tickcount:PocketSphinx Recognition Engine:  : VSP::ConfigureCmd execution latency: 0ms
08-30 23:10:34.585  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP::PocketSphinxEngine:configure() in state INIT
,08-30 23:10:34.585  9548  9643 I etickcount:VoiceFrameworkServiceHandler MyHandlerThread:  : VSP::setSpeechRecognitionListener: com.samsung.vsf.core.framework.embedded.EmbeddedFrameworkManager@acf4c92
,08-30 23:10:34.585  9548  9664 W ResourcesManager: getTopLevelResources: /system/priv-app/SVoiceLang_EnglishPack_US_1.0/SVoiceLang_EnglishPack_US_1.0.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.svoice.lang.en_US
,08-30 23:10:34.585  9548  9664 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:34.585  4612  7728 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.gms rsrc of package com.test.thalitest
,08-30 23:10:34.595  9601  9612 D PLMProvider: match for uri : content://com.samsung.svoice.sync/tos_accepted is : 8
,08-30 23:10:34.605  9644  9644 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in com.android.settings rsrc of package com.android.settings
,08-30 23:10:34.605  4612  7728 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:34.605  9644  9644 D SFinderConnectProvider: onCreate
,08-30 23:10:34.605  4612  7728 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.gms rsrc of package com.test.thalitest
,08-30 23:10:34.615  4021  4021 D Recents : onTaskStackChanged
,08-30 23:10:34.615  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP::MD5 Files From Assets : en_US.zip.MD5
,08-30 23:10:34.615  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP:: Time Taken LoadMD5FromPackage:  0.002 seconds.
08-30 23:10:34.615  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP:: Time Taken LoadMD5FromAssets:  0.0 seconds.
08-30 23:10:34.615  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP:: MD5 Checked in :  0.034 seconds.
08-30 23:10:34.615  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP::No Update 0
08-30 23:10:34.615  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP:: #### No Update in The Models #####
08-30 23:10:34.615  9548  9664 D etickcount:PocketSphinx Recognition Engine:  : VSP::TimeTaken for unpacking 39ms
08-30 23:10:34.615  9548  9664 D etickcount: Lang is en_US
08-30 23:10:34.625  9548  9664 I PLMGenManager: Version  : V_030816
08-30 23:10:34.625  9548  9664 D Flag    : configFalg value : 0
08-30 23:10:34.625  9548  9664 D PLMGenManager: Is JSON file found ? false
08-30 23:10:34.625  9548  9664 D PLMGenManager: Config flag is : 0
,08-30 23:10:34.625  4612  7728 I Icing   : Indexing done E1051AF754FD4764B2B13213EB917898AAC96AFB
,08-30 23:10:34.625  4021  4021 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.test.thalitest
,08-30 23:10:34.625  9548  9664 D AppInfo : TimeTaken for App Alias name generation : 6ms
,08-30 23:10:34.635  9621  9621 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 android.content.ContextWrapper.sendBroadcast:410 com.samsung.SMT.b.i.a:-1 com.samsung.SMT.SamsungTTSService.onCreate:-1 android.app.ActivityThread.handleCreateService:3808 
,08-30 23:10:34.635  4021  4021 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:34.635  9548  9664 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2015/SecGallery2015.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.gallery3d
,08-30 23:10:34.645  9548  9664 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:34.645  9644  9644 I BNRClientProivder, VERSION : 1.7.5: register - xml6 quick_backup : ACCESSIBILITYSETTINGS, X6qErjsfs2, com.android.settings.accessibility.sharedaccessibility.scloud.BNRTask
,08-30 23:10:34.645  9644  9644 I QBNRClientHelper: init SyncClientHelper : ACCESSIBILITYSETTINGS
,08-30 23:10:34.645  9644  9644 I BNRClientProivder, VERSION : 1.7.5: register - xml6 quick_backup : CONNECTIONS, C0phMaUuZZ, com.android.settings.wifi.mobileap.WifiApBackupRestore
08-30 23:10:34.645  9644  9644 I QBNRClientHelper: init SyncClientHelper : CONNECTIONS
,08-30 23:10:34.645  9548  9664 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2015/SecGallery2015.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.gallery3d
08-30 23:10:34.645  9644  9644 I BNRClientProivder, VERSION : 1.7.5: register - xml6 quick_backup : WiFi, C0phMaUuZZ, com.android.settings.wifi.WifiBackupRestore
08-30 23:10:34.645  9644  9644 I QBNRClientHelper: init SyncClientHelper : WiFi
,08-30 23:10:34.655  9548  9664 I PLM     : App title : Gallery & activity name : com.sec.android.gallery3d.app.GalleryOpaqueActivity_com.sec.android.gallery3d
,08-30 23:10:34.655  9548  9664 W ResourcesManager: getTopLevelResources: /system/priv-app/Phonesky/Phonesky.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.android.vending
,08-30 23:10:34.655  9621  9621 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 com.samsung.SMT.SamsungTTSService.g:-1 com.samsung.SMT.SamsungTTSService.onCreate:-1 android.app.ActivityThread.handleCreateService:3808 
,08-30 23:10:34.655  9644  9644 D InjectionManager: InjectionManager
08-30 23:10:34.655  9644  9644 D InjectionManager: fillFeatureStoreMap com.android.settings
,08-30 23:10:34.665  9644  9644 I InjectionManager: Constructor com.android.settings, Feature store :{}
,08-30 23:10:34.665  9644  9644 I InjectionManager: featureStore :{}
08-30 23:10:34.665  9548  9664 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:34.665  9548  9664 W ResourcesManager: getTopLevelResources: /system/priv-app/Phonesky/Phonesky.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.android.vending
,08-30 23:10:34.665  9621  9621 I SamsungTTS: Interface ver201503021
,08-30 23:10:34.665  9548  9664 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.shealth
08-30 23:10:34.665  9621  9621 I SamsungTTS: Engine ver200812311
08-30 23:10:34.665  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
08-30 23:10:34.675  3384  4315 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ae45f40 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{389086f 9644:com.android.settings/1000}
08-30 23:10:34.665  9548  9664 I PLM     : App title : Play_Store & activity name : com.android.vending.AssetBrowserActivity_com.android.vending
08-30 23:10:34.675  9548  9664 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:34.675  9548  9664 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.shealth
,08-30 23:10:34.675  9548  9664 I PLM     : App title : S_Health & activity name : com.samsung.android.app.shealth.home.HomeMainActivity_com.sec.android.app.shealth
,08-30 23:10:34.675  9548  9664 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCamera5/SamsungCamera5.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.camera
,08-30 23:10:34.675  9548  9664 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:34.675  9548  9664 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCamera5/SamsungCamera5.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.camera
,08-30 23:10:34.675  9548  9664 I PLM     : App title : Camera & activity name : com.sec.android.app.camera.Camera_com.sec.android.app.camera
,08-30 23:10:34.675  9548  9664 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.android.contacts,
08-30 23:10:34.685  9548  9548 I TextToSpeech: Connected to ComponentInfo{com.samsung.SMT/com.samsung.SMT.SamsungTTSService}
08-30 23:10:34.685  9621  9621 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 com.samsung.SMT.SamsungTTSService.g:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.c.onReceive:-1 
08-30 23:10:34.685  9548  9664 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:34.685  9548  9664 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.android.contacts
08-30 23:10:34.685  9548  9664 I PLM     : App title : Contacts & activity name : com.android.contacts.activities.PeopleActivity_com.android.contacts
,08-30 23:10:34.685  9548  9664 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.android.contacts
,08-30 23:10:34.685  9548  9664 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.android.contacts
,08-30 23:10:34.685  9548  9664 I PLM     : App title : Phone & activity name : com.android.dialer.DialtactsActivity_com.android.contacts
,08-30 23:10:34.695  9548  9664 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.samsung.android.email.provider
,08-30 23:10:34.695  3384  3448 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ae45f40 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{389086f 9644:com.android.settings/1000}
,08-30 23:10:34.695  9644  9644 I DataWarningReceiver: DataWarningReceiver
,08-30 23:10:34.695  9548  9664 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:34.695  9621  9631 D SamsungTTS: onIsLanguageAvailable() : L=pol  C=POL  V=null  LANG_NOT_SUPPORTED
08-30 23:10:34.695  9548  9666 I TextToSpeech: Set up connection to ComponentInfo{com.samsung.SMT/com.samsung.SMT.SamsungTTSService}
,08-30 23:10:34.695  9548  9664 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.samsung.android.email.provider
08-30 23:10:34.695  9548  9548 I SV_TTSPlayer:main:  : VSP::locale is: en_US
08-30 23:10:34.695  9548  9664 I PLM     : App title : Email & activity name : com.samsung.android.email.ui.activity.MessageListXL_com.samsung.android.email.provider
08-30 23:10:34.695  9548  9664 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Epic_Common/SecMms_Epic_Common.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.android.mms
08-30 23:10:34.695  9621  9632 D SamsungTTS: onIsLanguageAvailable() : L=eng  C=USA  V=null  LANG_COUNTRY_AVAILABLE
,08-30 23:10:34.695  9621  9667 D SamsungTTS: onIsLanguageAvailable() : L=eng  C=USA  V=null  LANG_COUNTRY_AVAILABLE
08-30 23:10:34.695  9621  9631 D SamsungTTS: onIsLanguageAvailable() : L=eng  C=USA  V=null  LANG_COUNTRY_AVAILABLE
,08-30 23:10:34.705  9548  9664 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:34.705  9621  9636 D SamsungTTS: onIsLanguageAvailable() : L=eng  C=USA  V=f00  LANG_COUNTRY_VAR_AVAILABLE
,08-30 23:10:34.705  9621  9636 D SamsungTTS: onLoadLanguage() : [ LANG_COUNTRY_VAR_AVAILABLE ]  L=eng  C=USA  V=f00
,08-30 23:10:34.705  9548  9664 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Epic_Common/SecMms_Epic_Common.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.android.mms
,08-30 23:10:34.705  9548  9664 I PLM     : App alias title : sms & activity name : com.android.mms.ui.ConversationComposer_com.android.mms
08-30 23:10:34.705  9548  9664 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.android.settings
08-30 23:10:34.705  9548  9664 I PLM     : App title : Messages & activity name : com.android.mms.ui.ConversationComposer_com.android.mms
,08-30 23:10:34.705  9548  9664 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:34.715  9548  9664 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.android.settings
08-30 23:10:34.715  9548  9664 I PLM     : App title : Settings & activity name : com.android.settings.Settings_com.android.settings
08-30 23:10:34.715  9668  9668 I libpersona: KNOX_SDCARD checking this for 10060
08-30 23:10:34.715  9668  9668 E Zygote  : v2
08-30 23:10:34.715  9668  9668 I libpersona: KNOX_SDCARD not a persona
08-30 23:10:34.715  9668  9668 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,08-30 23:10:34.715  9548  9664 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.android.chrome
,08-30 23:10:34.715  9668  9668 E Zygote  : accessInfo : 0
08-30 23:10:34.715  9668  9668 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.provider.shootingmodeprovider 
,08-30 23:10:34.725  9548  9664 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:34.725  9548  9664 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.android.chrome
08-30 23:10:34.725  9548  9664 I PLM     : App title : Chrome & activity name : com.google.android.apps.chrome.Main_com.android.chrome
,08-30 23:10:34.725  9548  9548 D Test    : TTS initialized! & queue size is : 0
08-30 23:10:34.725  9548  9664 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.apps.docs
,08-30 23:10:34.725  3384  3448 I ActivityManager: Start proc 9668:com.samsung.android.provider.shootingmodeprovider/u0a60 for broadcast-3 com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver
08-30 23:10:34.725  3384  3448 I ActivityManager: Killing 9137:com.samsung.android.app.FileShareServer/5005 (adj 15): DHA:empty #33
08-30 23:10:34.725  9548  9664 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:34.725  9548  9664 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.apps.docs
,08-30 23:10:34.735  9548  9664 I PLM     : App title : Drive & activity name : com.google.android.apps.docs.app.NewMainProxyActivity_com.google.android.apps.docs
,08-30 23:10:34.735  9548  9664 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.gm
,08-30 23:10:34.735  9548  9664 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:34.745  9668  9668 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 23:10:34.745  9668  9668 D ActivityThread: Added TimaKeyStore provider
,08-30 23:10:34.745  9548  9664 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.gm
,08-30 23:10:34.745  9548  9664 I PLM     : App title : Gmail & activity name : com.google.android.gm.ConversationListActivityGmail_com.google.android.gm
,08-30 23:10:34.745  9548  9664 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.talk
,08-30 23:10:34.745  9548  9664 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:34.745  9548  9664 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.talk
08-30 23:10:34.745  9548  9664 I PLM     : App title : Hangouts & activity name : com.google.android.talk.SigningInActivity_com.google.android.talk
,08-30 23:10:34.755  9548  9664 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.music
,08-30 23:10:34.755  9548  9664 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:34.755  9548  9664 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.music
08-30 23:10:34.755  3384  4250 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ae45f40 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{68754f1 9668:com.samsung.android.provider.shootingmodeprovider/u0a60}
08-30 23:10:34.755  9548  9664 I PLM     : App title : Play_Music & activity name : com.android.music.activitymanagement.TopLevelActivity_com.google.android.music
,08-30 23:10:34.755  9548  9664 W ResourcesManager: getTopLevelResources: /system/app/Photos/Photos.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.apps.photos
,08-30 23:10:34.765  3384  3978 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.FileShareServer, Auto Run ON
,08-30 23:10:34.765  9668  9668 D RelationGraph: garbageCollect()
08-30 23:10:34.765  9668  9668 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,08-30 23:10:34.765  9668  9668 W ResourcesManager: getTopLevelResources: /system/priv-app/ShootingModeProvider/ShootingModeProvider.apk / 1.0 running in com.samsung.android.provider.shootingmodeprovider rsrc of package com.samsung.android.provider.shootingmodeprovider
,08-30 23:10:34.775  3384  4054 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,08-30 23:10:34.775  9668  9668 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,08-30 23:10:34.775  9668  9668 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:34.775  9668  9668 I InjectionManager: Inside getClassLibPath caller 
,08-30 23:10:34.785  9668  9668 W System  : ClassLoader referenced unknown path: /system/priv-app/ShootingModeProvider/lib/arm64
,08-30 23:10:34.805  9668  9668 D InjectionManager: InjectionManager
08-30 23:10:34.805  9668  9668 D InjectionManager: fillFeatureStoreMap com.samsung.android.provider.shootingmodeprovider
,08-30 23:10:34.805  9668  9668 I InjectionManager: Constructor com.samsung.android.provider.shootingmodeprovider, Feature store :{}
08-30 23:10:34.805  9668  9668 I InjectionManager: featureStore :{}
,08-30 23:10:34.805  9548  9664 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:34.815  3384  4609 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ae45f40 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6e6c8d6 9443:com.samsung.android.sm.provider/1000}
,08-30 23:10:34.825  9548  9664 W ResourcesManager: getTopLevelResources: /system/app/Photos/Photos.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.apps.photos,
08-30 23:10:34.825  9548  9664 I PLM     : App title : Photos & activity name : com.google.android.apps.photos.home.HomeActivity_com.google.android.apps.photos
,08-30 23:10:34.825  9548  9664 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.sbrowser
,08-30 23:10:34.835  9548  9664 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:34.835  9548  9664 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.sbrowser
08-30 23:10:34.835  9548  9664 I PLM     : App title : Internet & activity name : com.sec.android.app.sbrowser.SBrowserMainActivity_com.sec.android.app.sbrowser
,08-30 23:10:34.835  3384  4609 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ae45f40 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{689fa02 9404:com.samsung.android.sm.devicesecurity/5012}
08-30 23:10:34.835  9548  9664 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M/SPlanner_M.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.android.calendar
,08-30 23:10:34.835  9548  9664 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:34.835  9548  9664 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M/SPlanner_M.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.android.calendar
08-30 23:10:34.835  9548  9664 I PLM     : App alias title : calendar & activity name : com.android.calendar.AllInOneActivity_com.android.calendar
08-30 23:10:34.835  9548  9664 I PLM     : App alias title : s_planner & activity name : com.android.calendar.AllInOneActivity_com.android.calendar
08-30 23:10:34.835  9548  9664 I PLM     : App alias title : schedule & activity name : com.android.calendar.AllInOneActivity_com.android.calendar
08-30 23:10:34.835  9548  9664 I PLM     : App alias title : diary & activity name : com.android.calendar.AllInOneActivity_com.android.calendar
08-30 23:10:34.835  9548  9664 I PLM     : App title : S_Planner & activity name : com.android.calendar.AllInOneActivity_com.android.calendar
,08-30 23:10:34.835  9548  9664 W ResourcesManager: getTopLevelResources: /system/app/Videos/Videos.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.videos
,08-30 23:10:34.845  9548  9664 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:34.845  9548  9664 W ResourcesManager: getTopLevelResources: /system/app/Videos/Videos.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.videos
,08-30 23:10:34.845  9548  9664 I PLM     : App title : Play_Movies_&_TV & activity name : com.google.android.youtube.videos.EntryPoint_com.google.android.videos
08-30 23:10:34.845  9548  9664 W ResourcesManager: getTopLevelResources: /system/app/YouTube/YouTube.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.youtube
,08-30 23:10:34.845  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:34.845  9548  9664 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:34.845  9548  9664 W ResourcesManager: getTopLevelResources: /system/app/YouTube/YouTube.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.youtube
08-30 23:10:34.845  9548  9664 I PLM     : App title : YouTube & activity name : com.google.android.youtube.app.honeycomb.Shell$HomeActivity_com.google.android.youtube
08-30 23:10:34.845  9548  9664 W ResourcesManager: getTopLevelResources: /system/priv-app/Excel_SamsungStub/Excel_SamsungStub.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.microsoft.office.excel
,08-30 23:10:34.855  9548  9664 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:34.855  9548  9664 W ResourcesManager: getTopLevelResources: /system/priv-app/Excel_SamsungStub/Excel_SamsungStub.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.microsoft.office.excel
08-30 23:10:34.855  9548  9664 I PLM     : App title : Excel & activity name : com.microsoft.office.apphost.LaunchActivity_com.microsoft.office.excel
,08-30 23:10:34.855  9548  9664 W ResourcesManager: getTopLevelResources: /system/priv-app/GearManager/GearManager.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.samsung.android.app.watchmanager
,08-30 23:10:34.855  9548  9664 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:34.855  9681  9681 E Zygote  : v2
08-30 23:10:34.855  9681  9681 I libpersona: KNOX_SDCARD checking this for 10067
08-30 23:10:34.855  9681  9681 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
08-30 23:10:34.855  9681  9681 I libpersona: KNOX_SDCARD not a persona
,08-30 23:10:34.855  9681  9681 E Zygote  : accessInfo : 0
08-30 23:10:34.855  9681  9681 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.app.taskedge 
,08-30 23:10:34.855  9548  9664 W ResourcesManager: getTopLevelResources: /system/priv-app/GearManager/GearManager.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.samsung.android.app.watchmanager
,08-30 23:10:34.855  9548  9664 I PLM     : App title : Samsung_Gear & activity name : com.samsung.android.app.watchmanager.setupwizard.SetupWizardWelcomeActivity_com.samsung.android.app.watchmanager
,08-30 23:10:34.865  3384  4609 I ActivityManager: Start proc 9681:com.samsung.android.app.taskedge/u0a67 for broadcast-3 com.samsung.android.app.taskedge/.TaskEdgeBroadcastReceiver
,08-30 23:10:34.865  3384  4609 I ActivityManager: Killing 9150:com.enhance.gameservice/u0a111 (adj 15): DHA:empty #33
,08-30 23:10:34.875  9548  9664 W ResourcesManager: getTopLevelResources: /system/priv-app/PowerPoint_SamsungStub/PowerPoint_SamsungStub.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.microsoft.office.powerpoint
,08-30 23:10:34.875  9548  9664 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:34.875  9681  9681 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 23:10:34.875  9681  9681 D ActivityThread: Added TimaKeyStore provider
,08-30 23:10:34.875  9548  9664 W ResourcesManager: getTopLevelResources: /system/priv-app/PowerPoint_SamsungStub/PowerPoint_SamsungStub.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.microsoft.office.powerpoint
08-30 23:10:34.875  9548  9664 I PLM     : App title : PowerPoint & activity name : com.microsoft.office.apphost.LaunchActivity_com.microsoft.office.powerpoint
,08-30 23:10:34.875  9548  9664 W ResourcesManager: getTopLevelResources: /system/priv-app/SVoice_1.0/SVoice_1.0.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.samsung.voiceserviceplatform
08-30 23:10:34.875  9548  9664 W ResourcesManager: getTopLevelResources: /system/priv-app/SVoice_1.0/SVoice_1.0.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.samsung.voiceserviceplatform
,08-30 23:10:34.885  9548  9664 W ResourcesManager: getTopLevelResources: /system/priv-app/SecCalculator_M/SecCalculator_M.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.popupcalculator
,08-30 23:10:34.885  9548  9664 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:34.885  3384  4473 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ae45f40 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cf8e757 9681:com.samsung.android.app.taskedge/u0a67}
,08-30 23:10:34.895  9548  9664 I PLM     : App title : Calculator & activity name : com.sec.android.app.popupcalculator.Calculator_com.sec.android.app.popupcalculator
08-30 23:10:34.895  9548  9664 W ResourcesManager: getTopLevelResources: /system/priv-app/SecCalculator_M/SecCalculator_M.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.popupcalculator
,08-30 23:10:34.895  9548  9664 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles/SecMyFiles.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.myfiles
,08-30 23:10:34.895  9548  9664 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:34.895  3384  4997 D ActivityManager: isAutoRunBlockedApp:: com.enhance.gameservice, Auto Run ON
08-30 23:10:34.895  9548  9664 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles/SecMyFiles.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.myfiles
,08-30 23:10:34.895  9548  9664 I PLM     : App title : My_Files & activity name : com.sec.android.app.myfiles.common.MainActivity_com.sec.android.app.myfiles
08-30 23:10:34.895  9548  9664 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.googlequicksearchbox
,08-30 23:10:34.895  9681  9681 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
08-30 23:10:34.895  9681  9681 D RelationGraph: garbageCollect()
,08-30 23:10:34.905  9548  9664 D ResourcesManager: For user 0 new overlays fetched Null
08-30 23:10:34.905  9681  9681 W ResourcesManager: getTopLevelResources: /system/priv-app/TaskEdgePanel/TaskEdgePanel.apk / 1.0 running in com.samsung.android.app.taskedge rsrc of package com.samsung.android.app.taskedge
08-30 23:10:34.905  9548  9664 I PLM     : App title : Voice_Search & activity name : com.google.android.googlequicksearchbox.VoiceSearchActivity_com.google.android.googlequicksearchbox
08-30 23:10:34.905  9548  9664 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.googlequicksearchbox
08-30 23:10:34.905  9681  9681 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,08-30 23:10:34.905  3384  4313 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
08-30 23:10:34.905  9548  9664 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.googlequicksearchbox
08-30 23:10:34.905  9548  9664 I PLM     : App title : Google & activity name : com.google.android.googlequicksearchbox.SearchActivity_com.google.android.googlequicksearchbox
08-30 23:10:34.905  9548  9664 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.googlequicksearchbox
08-30 23:10:34.905  9681  9681 D ResourcesManager: For user 0 new overlays fetched Null
08-30 23:10:34.905  9548  9664 W ResourcesManager: getTopLevelResources: /system/priv-app/VoiceNote_4.0/VoiceNote_4.0.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.voicenote
,08-30 23:10:34.905  9548  9664 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:34.905  9621  9636 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 android.content.ContextWrapper.sendBroadcast:410 com.samsung.SMT.b.i.a:-1 com.samsung.SMT.SamsungTTSService.b:-1 com.samsung.SMT.SamsungTTSService.onLoadLanguage:-1 
,08-30 23:10:34.905  9509  9663 W jxcore-log: Initializing JXcore engine
,08-30 23:10:34.905  9548  9664 W ResourcesManager: getTopLevelResources: /system/priv-app/VoiceNote_4.0/VoiceNote_4.0.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.voicenote
08-30 23:10:34.905  9509  9663 W jxcore-log: JXcore engine is ready
08-30 23:10:34.905  9681  9681 I InjectionManager: Inside getClassLibPath caller 
08-30 23:10:34.915  9621  9636 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 android.content.ContextWrapper.sendBroadcast:410 android.speech.tts.TextToSpeechService$SynthThread.broadcastTtsQueueProcessingCompleted:460 android.speech.tts.TextToSpeechService$SynthThread.queueIdle:452 android.os.MessageQueue.next:392 
08-30 23:10:34.905  9548  9664 I PLM     : App title : Voice_Recorder & activity name : com.sec.android.app.voicenote.main.VNMainActivity_com.sec.android.app.voicenote
,08-30 23:10:34.915  9548  9664 W ResourcesManager: getTopLevelResources: /system/priv-app/Word_SamsungStub/Word_SamsungStub.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.microsoft.office.word
,08-30 23:10:34.915  9548  9664 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:34.915  9548  9664 W ResourcesManager: getTopLevelResources: /system/priv-app/Word_SamsungStub/Word_SamsungStub.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.microsoft.office.word
08-30 23:10:34.915  9548  9664 I PLM     : App title : Word & activity name : com.microsoft.office.apphost.LaunchActivity_com.microsoft.office.word
,08-30 23:10:34.915  9548  9664 W ResourcesManager: getTopLevelResources: /system/priv-app/player-production-release-3.3.3-newSDK_23/player-production-release-3.3.3-newSDK_23.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package pl.tvn.player
08-30 23:10:34.915  9681  9681 W System  : ClassLoader referenced unknown path: /system/priv-app/TaskEdgePanel/lib/arm64
,08-30 23:10:34.915  9548  9664 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:34.915  9548  9664 W ResourcesManager: getTopLevelResources: /system/priv-app/player-production-release-3.3.3-newSDK_23/player-production-release-3.3.3-newSDK_23.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package pl.tvn.player
,08-30 23:10:34.915  9548  9664 I PLM     : App title : Player & activity name : pl.tvn.player.ui.SplashActivity_pl.tvn.player
08-30 23:10:34.915  9548  9664 W ResourcesManager: getTopLevelResources: /system/app/ClockPackage_M/ClockPackage_M.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.clockpackage
,08-30 23:10:34.915  9548  9664 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:34.915  9548  9664 W ResourcesManager: getTopLevelResources: /system/app/ClockPackage_M/ClockPackage_M.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.clockpackage
,08-30 23:10:34.915  9548  9664 I PLM     : App alias title : alarm & activity name : com.sec.android.app.clockpackage.ClockPackage_com.sec.android.app.clockpackage
08-30 23:10:34.925  9548  9664 W ResourcesManager: getTopLevelResources: /system/app/FBInstagram_stub/FBInstagram_stub.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.instagram.android
08-30 23:10:34.915  9548  9664 I PLM     : App title : Clock & activity name : com.sec.android.app.clockpackage.ClockPackage_com.sec.android.app.clockpackage
08-30 23:10:34.925  9681  9681 D InjectionManager: InjectionManager
08-30 23:10:34.925  9681  9681 D InjectionManager: fillFeatureStoreMap com.samsung.android.app.taskedge
,08-30 23:10:34.925  9681  9681 I InjectionManager: Constructor com.samsung.android.app.taskedge, Feature store :{}
08-30 23:10:34.925  9681  9681 I InjectionManager: featureStore :{}
08-30 23:10:34.925  9681  9681 I TaskEdgeBroadcastReceiver: onReceive:android.intent.action.PACKAGE_ADDED
,08-30 23:10:34.925  9548  9664 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:34.925  9548  9664 W ResourcesManager: getTopLevelResources: /system/app/FBInstagram_stub/FBInstagram_stub.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.instagram.android
08-30 23:10:34.925  9548  9664 I PLM     : App title : Instagram & activity name : com.instagram.android.activity.MainTabActivity_com.instagram.android
,08-30 23:10:34.925  3384  4058 I ActivityManager: Killing 9163:com.sec.android.service.health/u0a26 (adj 15): DHA:empty #33
,08-30 23:10:34.925  9548  9664 W ResourcesManager: getTopLevelResources: /system/app/Facebook_stub/Facebook_stub.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.facebook.katana
,08-30 23:10:34.925  9548  9664 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:34.925  9548  9664 W ResourcesManager: getTopLevelResources: /system/app/Facebook_stub/Facebook_stub.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.facebook.katana
,08-30 23:10:34.925  9548  9664 I PLM     : App title : Facebook & activity name : com.facebook.katana.LoginActivity_com.facebook.katana
08-30 23:10:34.925  9548  9664 W ResourcesManager: getTopLevelResources: /system/app/MSSkype_stub/MSSkype_stub.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.skype.raider
,08-30 23:10:34.925  9548  9664 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:34.925  9548  9664 W ResourcesManager: getTopLevelResources: /system/app/MSSkype_stub/MSSkype_stub.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.skype.raider
08-30 23:10:34.925  9548  9664 I PLM     : App title : Skype & activity name : com.skype.raider.Main_com.skype.raider
,08-30 23:10:34.925  9548  9664 W ResourcesManager: getTopLevelResources: /system/app/Maps/Maps.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.apps.maps
,08-30 23:10:34.935  9548  9664 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:34.935  5050  5050 E audit   : type=1400 msg=audit(1472591434.935:262): avc:  denied  { ioctl } for  pid=9663 comm="Thread-148" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4118 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-30 23:10:34.935  9548  9664 W ResourcesManager: getTopLevelResources: /system/app/Maps/Maps.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.google.android.apps.maps
08-30 23:10:34.935  5050  5050 E audit   :  SEPF_SECMOBILE_6.0.1_0013
08-30 23:10:34.935  5050  5050 E audit   : type=1300 msg=audit(1472591434.935:262): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=8 a1=5451 a2=3 a3=d907f3c8 items=0 ppid=3179 pid=9663 auid=4294967295 uid=10177 gid=10177 euid=10177 suid=10177 fsuid=10177 egid=10177 sgid=10177 fsgid=10177 tty=(none) ses=4294967295 comm="Thread-148" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-30 23:10:34.935  5050  5050 E audit   : type=1327 msg=audit(1472591434.935:262): proctitle="com.test.thalitest"
08-30 23:10:34.935  9548  9664 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.microsoft.skydrive
,08-30 23:10:34.935  5050  5050 E audit   : type=1320 msg=audit(1472591434.935:262): 
08-30 23:10:34.935  5050  5050 E audit   : type=1400 msg=audit(1472591434.935:263): avc:  denied  { ioctl } for  pid=9663 comm="Thread-148" path="socket:[11005]" dev="sockfs" ino=11005 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-30 23:10:34.935  5050  5050 E audit   :  SEPF_SECMOBILE_6.0.1_0013
08-30 23:10:34.935  5050  5050 E audit   : type=1300 msg=audit(1472591434.935:263): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=3b a1=5451 a2=3 a3=d907f3c8 items=0 ppid=3179 pid=9663 auid=4294967295 uid=10177 gid=10177 euid=10177 suid=10177 fsuid=10177 egid=10177 sgid=10177 fsgid=10177 tty=(none) ses=4294967295 comm="Thread-148" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-30 23:10:34.935  5050  5050 E audit   : type=1327 msg=audit(1472591434.935:263): proctitle="com.test.thalitest"
08-30 23:10:34.935  5050  5050 E audit   : type=1320 msg=audit(1472591434.935:263): 
08-30 23:10:34.935  9548  9664 I PLM     : App title : Maps & activity name : com.google.android.maps.MapsActivity_com.google.android.apps.maps
,08-30 23:10:34.935  9548  9664 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:34.935  9548  9664 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.microsoft.skydrive
08-30 23:10:34.935  9548  9664 I PLM     : App title : OneDrive & activity name : com.microsoft.skydrive.MainActivity_com.microsoft.skydrive
,08-30 23:10:34.935  9548  9664 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.microsoft.office.onenote
08-30 23:10:34.935  3384  4058 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ae45f40 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{41a2ec0 4296:com.android.phone/1001}
08-30 23:10:34.935  9509  9663 W jxcore-log: Starting JXcore engine
,08-30 23:10:34.935  9548  9664 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:34.945  9548  9664 I PLM     : App title : OneNote & activity name : com.microsoft.office.onenote.ui.ONMSplashActivity_com.microsoft.office.onenote
,08-30 23:10:34.945  9548  9664 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.microsoft.office.onenote
08-30 23:10:34.945  9548  9664 W ResourcesManager: getTopLevelResources: /system/app/SecMemo3/SecMemo3.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.samsung.android.app.memo
,08-30 23:10:34.945  9548  9664 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:34.945  9548  9664 W ResourcesManager: getTopLevelResources: /system/app/SecMemo3/SecMemo3.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.samsung.android.app.memo
,08-30 23:10:34.945  9548  9664 I PLM     : App title : Memo & activity name : com.samsung.android.app.memo.Main_com.samsung.android.app.memo
08-30 23:10:34.945  9548  9664 W ResourcesManager: getTopLevelResources: /system/app/WhatsAppDownloader/WhatsAppDownloader.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.whatsapp
,08-30 23:10:34.945  9548  9664 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:34.945  9548  9664 I PLM     : App title : WhatsApp & activity name : com.whatsapp.Main_com.whatsapp
,08-30 23:10:34.945  9548  9664 W ResourcesManager: getTopLevelResources: /data/app/com.sec.android.app.samsungapps-1/base.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.samsungapps
,08-30 23:10:34.955  9548  9664 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:34.955  9548  9664 W ResourcesManager: getTopLevelResources: /data/app/com.sec.android.app.samsungapps-1/base.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.sec.android.app.samsungapps
,08-30 23:10:34.955  9548  9664 I PLM     : App title : Galaxy_Apps & activity name : com.sec.android.app.samsungapps.SamsungAppsMainActivity_com.sec.android.app.samsungapps
08-30 23:10:34.955  9548  9664 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.test.thalitest
,08-30 23:10:34.955  9693  9693 E Zygote  : v2
08-30 23:10:34.955  9693  9693 I libpersona: KNOX_SDCARD checking this for 1000
08-30 23:10:34.955  9693  9693 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
08-30 23:10:34.955  9693  9693 I libpersona: KNOX_SDCARD not a persona
,08-30 23:10:34.955  3384  4054 I ActivityManager: Start proc 9693:com.samsung.android.themecenter/1000 for broadcast-3 com.samsung.android.themecenter/com.samsung.android.thememanager.ThemeManagerReceiver
08-30 23:10:34.955  9693  9693 E Zygote  : accessInfo : 0
08-30 23:10:34.955  9548  9664 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:34.955  9548  9664 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.samsung.voiceserviceplatform rsrc of package com.test.thalitest
08-30 23:10:34.955  9548  9664 I PLM     : App title : ThaliTest & activity name : com.test.thalitest.MainActivity_com.test.thalitest
,08-30 23:10:34.965  3384  4761 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.service.health, Auto Run ON
,08-30 23:10:34.975  9693  9693 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 23:10:34.975  9693  9693 D ActivityThread: Added TimaKeyStore provider
,08-30 23:10:34.985  9509  9663 W jxcore-log: Platform android
08-30 23:10:34.985  9509  9663 W jxcore-log: 
,08-30 23:10:34.985  9509  9663 W jxcore-log: Process ARCH arm
08-30 23:10:34.985  9509  9663 W jxcore-log: 
,08-30 23:10:34.985  3384  3853 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ae45f40 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c13244 9693:com.samsung.android.themecenter/1000}
,08-30 23:10:34.995  9693  9693 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
08-30 23:10:34.995  9693  9693 D RelationGraph: garbageCollect()
,08-30 23:10:34.995  9693  9693 W ResourcesManager: getTopLevelResources: /system/priv-app/ThemeCenter/ThemeCenter.apk / 1.0 running in com.samsung.android.themecenter rsrc of package com.samsung.android.themecenter
,08-30 23:10:34.995  3384  3853 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
08-30 23:10:34.995  9693  9693 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,08-30 23:10:34.995  9548  9664 D ContactInfo: Matched with previous entries!
,08-30 23:10:34.995  9693  9693 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:35.005  9693  9693 I InjectionManager: Inside getClassLibPath caller 
,08-30 23:10:35.005  9693  9693 W System  : ClassLoader referenced unknown path: /system/priv-app/ThemeCenter/lib/arm64
,08-30 23:10:35.005  9548  9664 D PLMGenManager: Any updates for FSG and DICT? : Yes
,08-30 23:10:35.005  9548  9664 D PLMGenManager: TimeTaken for Contact & App sync 385ms
08-30 23:10:35.005  9693  9693 D InjectionManager: InjectionManager
08-30 23:10:35.005  9693  9693 D InjectionManager: fillFeatureStoreMap com.samsung.android.themecenter
08-30 23:10:35.005  9693  9693 I InjectionManager: Constructor com.samsung.android.themecenter, Feature store :{}
08-30 23:10:35.005  9693  9693 I InjectionManager: featureStore :{}
08-30 23:10:35.005  9548  9664 D etickcount:BuildCmd: Dictionary name : /data/user/0/com.sec.svoice.lang.en_US/files/en_US/dict/hero.dict
,08-30 23:10:35.005  9548  9664 I FSGFileGenerator:PocketSphinx: Model dir : /data/user/0/com.sec.svoice.lang.en_US/files/en_US
,08-30 23:10:35.005  9548  9664 I FSGFileGenerator:PocketSphinx: FSG : start
08-30 23:10:35.005  9548  9664 D FSGFileGenerator:PocketSphinx: Inside initFileWriter
08-30 23:10:35.005  9548  9664 I FSGFileGenerator:PocketSphinx: templateFsgFileToRead = { /data/user/0/com.sec.svoice.lang.en_US/files/en_US/lm/hero.detmin.fsg.org, fsgFileToCreate = /data/user/0/com.sec.svoice.lang.en_US/files/en_US/lm/hero.detmin.fsg }
08-30 23:10:35.005  9548  9664 D FSGFileGenerator:PocketSphinx: FileWriter/FileReader created
,08-30 23:10:35.015  9693  9693 I ThemeManagerReceiver: ThemeManagerReceiver onReceive android.intent.action.PACKAGE_ADDED
,08-30 23:10:35.015  3384  4473 I ActivityManager: Killing 9175:com.samsung.android.app.watchmanagerstub/u0a112 (adj 15): DHA:empty #33
,08-30 23:10:35.015  9548  9664 D FSGFileGenerator:PocketSphinx: FileWriter is closed sucessfull
,08-30 23:10:35.015  9548  9664 D FSGFileGenerator:PocketSphinx: FileReader is closed sucessfull
08-30 23:10:35.015  9548  9664 D FSGFileGenerator:PocketSphinx: Inside initFileWriter
08-30 23:10:35.015  9548  9664 I FSGFileGenerator:PocketSphinx: templateFsgFileToRead = { /data/user/0/com.sec.svoice.lang.en_US/files/en_US/lm/hero.detmin.wo.wakeup.fsg.org, fsgFileToCreate = /data/user/0/com.sec.svoice.lang.en_US/files/en_US/lm/hero.detmin.wo.wakeup.fsg }
08-30 23:10:35.025  9548  9664 D FSGFileGenerator:PocketSphinx: FileWriter/FileReader created
08-30 23:10:35.025  3384  4473 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ae45f40 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d1d3958 4453:com.google.android.googlequicksearchbox:search/u0a72}
,08-30 23:10:35.025  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:35.035  9548  9664 D FSGFileGenerator:PocketSphinx: FileWriter is closed sucessfull
08-30 23:10:35.035  9548  9664 D FSGFileGenerator:PocketSphinx: FileReader is closed sucessfull
08-30 23:10:35.035  9548  9664 D FSGFileGenerator:PocketSphinx: FSG : COMPLETED in 23 ms.
08-30 23:10:35.035  9548  9664 I FSGFileGenerator:PocketSphinx: FSG : start
08-30 23:10:35.035  9548  9664 D FSGFileGenerator:PocketSphinx: Inside initFileWriter
08-30 23:10:35.035  9548  9664 I FSGFileGenerator:PocketSphinx: templateFsgFileToRead = { /data/user/0/com.sec.svoice.lang.en_US/files/en_US/lm/contact.fsg.org, fsgFileToCreate = /data/user/0/com.sec.svoice.lang.en_US/files/en_US/lm/contact.fsg }
08-30 23:10:35.035  9548  9664 D FSGFileGenerator:PocketSphinx: FileWriter/FileReader created
,08-30 23:10:35.035  9548  9664 D FSGFileGenerator:PocketSphinx: FileWriter is closed sucessfull
08-30 23:10:35.035  9548  9664 D FSGFileGenerator:PocketSphinx: FileReader is closed sucessfull
08-30 23:10:35.035  9548  9664 D FSGFileGenerator:PocketSphinx: Inside initFileWriter
08-30 23:10:35.035  9548  9664 I FSGFileGenerator:PocketSphinx: templateFsgFileToRead = { /data/user/0/com.sec.svoice.lang.en_US/files/en_US/lm/contact.fav.fsg.org, fsgFileToCreate = /data/user/0/com.sec.svoice.lang.en_US/files/en_US/lm/contact.fav.fsg }
08-30 23:10:35.035  9548  9664 D FSGFileGenerator:PocketSphinx: FileWriter/FileReader created
,08-30 23:10:35.035  9548  9664 D FSGFileGenerator:PocketSphinx: FileWriter is closed sucessfull
08-30 23:10:35.035  9548  9664 D FSGFileGenerator:PocketSphinx: FileReader is closed sucessfull
08-30 23:10:35.035  9548  9664 D FSGFileGenerator:PocketSphinx:OWC: FSG : COMPLETED in 2 ms.
08-30 23:10:35.035  9548  9664 I DictionaryGenerator:PocketSphinx: Model dir : /data/user/0/com.sec.svoice.lang.en_US/files/en_US
08-30 23:10:35.035  9548  9664 I DictionaryGenerator:PocketSphinx: Locale : en_US
08-30 23:10:35.035  9548  9664 I DictionaryGenerator:PocketSphinx: DFG : Start
08-30 23:10:35.035  9548  9664 D DictionaryGenerator:PocketSphinx: Inside initFileWriter : Dict file name : /data/user/0/com.sec.svoice.lang.en_US/files/en_US/dict/hero.dict
08-30 23:10:35.035  9548  9664 I DictionaryGenerator:PocketSphinx: mDictionaryFile = { /data/user/0/com.sec.svoice.lang.en_US/files/en_US/dict/hero.dict }
08-30 23:10:35.035  9548  9664 D DictionaryGenerator:PocketSphinx: FileWriter created
08-30 23:10:35.035  9548  9664 D DictionaryGenerator:PocketSphinx: copying frm : /data/user/0/com.sec.svoice.lang.en_US/files/en_US/dict/hero.dict
08-30 23:10:35.035  9548  9664 D DictionaryGenerator:PocketSphinx: Wakeup word is : null
,08-30 23:10:35.035  9548  9664 D DictionaryGenerator:PocketSphinx: wakeup string added to dict : slot_wakeup_start__WAKEUP__slot_wakeup_end	S L AA T W EY K AH P S T AA R T W EY K AH P S L AA T W EY K AH P EH N D
08-30 23:10:35.035  9548  9664 I G2P     : PocketSphinxEngine:Trying to load : /data/user/0/com.sec.svoice.lang.en_US/files/en_US/libs/libG2PenUS.so
08-30 23:10:35.035  3384  3448 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.watchmanagerstub, Auto Run ON
08-30 23:10:35.045  9548  9664 I G2P     : PocketSphinxEngine:loading /data/user/0/com.sec.svoice.lang.en_US/files/en_US/libs/libG2PenUS.so done
08-30 23:10:35.045  9548  9664 V G2P-SRIB: Build date: Apr 28 2016, 15:00:24
08-30 23:10:35.045  9548  9664 V G2P-SRIB: enUS G2P libs
08-30 23:10:35.045  9548  9664 V G2P-SRIB: stringCount: 46
08-30 23:10:35.045  9548  9664 V G2P-SRIB: Config: lang: en-US
08-30 23:10:35.045  9548  9664 V G2P-SRIB: variant: mp
08-30 23:10:35.045  9548  9664 V G2P-SRIB: prefix: slot_application_names_start__
08-30 23:10:35.045  9548  9664 V G2P-SRIB: suffix: __slot_application_names_end
08-30 23:10:35.045  9548  9664 V G2P-SRIB: Options dump_pron: W W K K K K K K K K K K K K K W W,
08-30 23:10:35.045  9548  9664 V G2P-SRIB: After conversion: Internet, Internet, 8, 8
08-30 23:10:35.045  9548  9664 V G2P-SRIB: After g2p: prons 1, max_pron_len 17
08-30 23:10:35.045  9548  9664 V G2P-SRIB: Output pron: ih n t er n eh t, i in loop: 0
08-30 23:10:35.045  9548  9664 V G2P-SRIB: After conversion: Phone, Phone, 5, 5
08-30 23:10:35.045  9548  9664 V G2P-SRIB: After g2p: prons 1, max_pron_len 7
08-30 23:10:35.045  9548  9664 V G2P-SRIB: Output pron: f ow n, i in loop: 0
08-30 23:10:35.045  9548  9664 V G2P-SRIB: After conversion: Voice_Recorder, Voice_Recorder, 14, 14
08-30 23:10:35.055  9548  9664 V G2P-SRIB: After g2p: prons 1, max_pron_len 24
08-30 23:10:35.055  9548  9664 V G2P-SRIB: Output pron: v oy s r ih k ao r d er, i in loop: 0
08-30 23:10:35.055  9548  9664 V G2P-SRIB: After conversion: Player, Player, 6, 6
08-30 23:10:35.055  9548  9664 V G2P-SRIB: After g2p: prons 1, max_pron_len 10
08-30 23:10:35.055  9548  9664 V G2P-SRIB: Output pron: p l ey er, i in loop: 0
08-30 23:10:35.055  9548  9664 V G2P-SRIB: After conversion: Word, Word, 4, 4
08-30 23:10:35.055  9548  9664 V G2P-SRIB: After g2p: prons 1, max_pron_len 7
08-30 23:10:35.055  9548  9664 V G2P-SRIB: Output pron: w er d, i in loop: 0
08-30 23:10:35.055  9548  9664 V G2P-SRIB: After conversion: Samsung_Gear, Samsung_Gear, 12, 12
08-30 23:10:35.055  9548  9664 V G2P-SRIB: After g2p: prons 1, max_pron_len 22
08-30 23:10:35.055  9548  9664 V G2P-SRIB: Output pron: s ae m s ah ng g ih r, i in loop: 0
08-30 23:10:35.055  9548  9664 V G2P-SRIB: After conversion: schedule, schedule, 8, 8
08-30 23:10:35.055  9548  9664 V G2P-SRIB: After g2p: prons 1, max_pron_len 15
08-30 23:10:35.055  9548  9664 V G2P-SRIB: Output pron: s k eh jh uh l, i in loop: 0
08-30 23:10:35.055  9548  9664 V G2P-SRIB: After conversion: Play_Music, Play_Music, 10, 10
08-30 23:10:35.055  9548  9664 V G2P-SRIB: After g2p: prons 1, max_pron_len 21
08-30 23:10:35.055  9548  9664 V G2P-SRIB: Output pron: p l ey m y uw z ih k, i in loop: 0
08-30 23:10:35.055  9548  9664 V G2P-SRIB: After conversion: S_Planner, S_Planner, 9, 9
08-30 23:10:35.055  9548  9664 V G2P-SRIB: After g2p: prons 1, max_pron_len 17
08-30 23:10:35.055  9548  9664 V G2P-SRIB: Output pron: eh s p l ae n er, i in loop: 0
08-30 23:10:35.055  9548  9664 V G2P-SRIB: After conversion: Memo, Memo, 4, 4
08-30 23:10:35.055  9548  9664 V G2P-SRIB: After g2p: prons 1, max_pron_len 10
08-30 23:10:35.055  9548  9664 V G2P-SRIB: Output pron: m eh m ow, i in loop: 0
08-30 23:10:35.055  9548  9664 V G2P-SRIB: After conversion: Drive, Drive, 5, 5
08-30 23:10:35.055  9548  9664 V G2P-SRIB: After g2p: prons 1, max_pron_len 9
08-30 23:10:35.055  9548  9664 V G2P-SRIB: Output pron: d r ay v, i in loop: 0
08-30 23:10:35.055  9548  9664 V G2P-SRIB: After conversion: Galaxy_Apps, Galaxy_Apps, 11, 11
08-30 23:10:35.055  3384  4997 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ae45f40 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d1d3958 4453:com.google.android.googlequicksearchbox:search/u0a72}
08-30 23:10:35.055  9548  9664 V G2P-SRIB: After g2p: prons 1, max_pron_len 24
08-30 23:10:35.055  9548  9664 V G2P-SRIB: Output pron: g ae l ah k s iy ae p s, i in loop: 0
08-30 23:10:35.055  9548  9664 V G2P-SRIB: After conversion: Calculator, Calculator, 10, 10
08-30 23:10:35.055  9548  9664 V G2P-SRIB: After g2p: prons 1, max_pron_len 24
08-30 23:10:35.055  9548  9664 V G2P-SRIB: Output pron: k ae l k y ah l ey t er, i in loop: 0
08-30 23:10:35.055  9548  9664 V G2P-SRIB: After conversion: Chrome, Chrome, 6, 6
08-30 23:10:35.055  9548  9664 V G2P-SRIB: After g2p: prons 1, max_pron_len 9
08-30 23:10:35.055  9548  9664 V G2P-SRIB: Output pron: k r ow m, i in loop: 0
08-30 23:10:35.055  9548  9664 V G2P-SRIB: After conversion: OneDrive, OneDrive, 8, 8
08-30 23:10:35.055  9548  9664 V G2P-SRIB: After g2p: prons 1, max_pron_len 19
08-30 23:10:35.055  9548  9664 V G2P-SRIB: Output pron: w ah n eh d r ay v, i in loop: 0
08-30 23:10:35.055  9548  9664 V G2P-SRIB: After conversion: Instagram, Instagram, 9, 9
08-30 23:10:35.055  9548  9664 V G2P-SRIB: After g2p: prons 1, max_pron_len 21
08-30 23:10:35.055  9548  9664 V G2P-SRIB: Output pron: ih n s t ax g r ae m, i in loop: 0
08-30 23:10:35.055  9548  9664 V G2P-SRIB: After conversion: Contacts, Contacts, 8, 8
08-30 23:10:35.055  9548  9664 V G2P-SRIB: After g2p: prons 1, max_pron_len 18
08-30 23:10:35.055  9548  9664 V G2P-SRIB: Output pron: k aa n t ae k t s, i in loop: 0
08-30 23:10:35.055  9548  9664 V G2P-SRIB: After conversion: ThaliTest, ThaliTest, 9, 9
08-30 23:10:35.055  9548  9664 V G2P-SRIB: After g2p: prons 1, max_pron_len 20
08-30 23:10:35.055  9548  9664 V G2P-SRIB: Output pron: th ae l ay t ax s t, i in loop: 0
08-30 23:10:35.055  9548  9664 V G2P-SRIB: After conversion: WhatsApp, WhatsApp, 8, 8
08-30 23:10:35.065  9548  9664 V G2P-SRIB: After g2p: prons 1, max_pron_len 14
08-30 23:10:35.065  9548  9664 V G2P-SRIB: Output pron: w aa t s ae p, i in loop: 0
08-30 23:10:35.065  9548  9664 V G2P-SRIB: After conversion: Messages, Messages, 8, 8
08-30 23:10:35.065  9548  9664 V G2P-SRIB: After g2p: prons 1, max_pron_len 18
08-30 23:10:35.065  9548  9664 V G2P-SRIB: Output pron: m eh s ax jh ax z, i in loop: 0
08-30 23:10:35.065  9548  9664 V G2P-SRIB: After conversion: Email, Email, 5, 5
08-30 23:10:35.065  9548  9664 V G2P-SRIB: After g2p: prons 1, max_pron_len 10
08-30 23:10:35.065  9548  9664 V G2P-SRIB: Output pron: iy m ey l, i in loop: 0
08-30 23:10:35.065  9548  9664 V G2P-SRIB: After conversion: Hangouts, Hangouts, 8, 8
08-30 23:10:35.065  9548  9664 V G2P-SRIB: After g2p: prons 1, max_pron_len 16
08-30 23:10:35.065  9548  9664 V G2P-SRIB: Output pron: hh ae ng aw t s, i in loop: 0
08-30 23:10:35.065  9548  9664 V G2P-SRIB: After conversion: OneNote, OneNote, 7, 7
08-30 23:10:35.065  9548  9664 V G2P-SRIB: After g2p: prons 1, max_pron_len 17
08-30 23:10:35.065  9548  9664 V G2P-SRIB: Output pron: w ah n ih n ow t, i in loop: 0
08-30 23:10:35.065  9548  9664 V G2P-SRIB: After conversion: calendar, calendar, 8, 8
08-30 23:10:35.065  9548  9664 V G2P-SRIB: After g2p: prons 1, max_pron_len 17
08-30 23:10:35.065  9548  9664 V G2P-SRIB: Output pron: k ae l ax n d er, i in loop: 0
08-30 23:10:35.065  9548  9664 V G2P-SRIB: After conversion: Play_Store, Play_Store, 10, 10
08-30 23:10:35.065  9548  9664 V G2P-SRIB: After g2p: prons 1, max_pron_len 16
08-30 23:10:35.065  9548  9664 V G2P-SRIB: Output pron: p l ey s t ao r, i in loop: 0
08-30 23:10:35.065  9548  9664 V G2P-SRIB: After conversion: Photos, Photos, 6, 6
08-30 23:10:35.065  9548  9664 V G2P-SRIB: After g2p: prons 1, max_pron_len 12
08-30 23:10:35.065  9548  9664 V G2P-SRIB: Output pron: f ow t ow z, i in loop: 0
08-30 23:10:35.065  9548  9664 V G2P-SRIB: After conversion: Excel, Excel, 5, 5
08-30 23:10:35.065  9548  9664 V G2P-SRIB: After g2p: prons 1, max_pron_len 12
08-30 23:10:35.065  9548  9664 V G2P-SRIB: Output pron: ih k s eh l, i in loop: 0
08-30 23:10:35.065  9548  9664 V G2P-SRIB: After conversion: Gallery, Gallery, 7, 7
08-30 23:10:35.065  9548  9664 V G2P-SRIB: After g2p: prons 1, max_pron_len 13
08-30 23:10:35.065  9548  9664 V G2P-SRIB: Output pron: g ae l er iy, i in loop: 0
08-30 23:10:35.065  9548  9664 V G2P-SRIB: After conversion: sms, sms, 3, 3
08-30 23:10:35.065  9548  9664 V G2P-SRIB: After g2p: prons 1, max_pron_len 15
08-30 23:10:35.065  9548  9664 V G2P-SRIB: Output pron: eh s eh m eh s, i in loop: 0
08-30 23:10:35.065  9548  9664 V G2P-SRIB: After conversion: S_Health, S_Health, 8, 8
08-30 23:10:35.065  9548  9664 V G2P-SRIB: After g2p: prons 1, max_pron_len 16
08-30 23:10:35.065  9548  9664 V G2P-SRIB: Output pron: eh s hh eh l th, i in loop: 0
08-30 23:10:35.065  9548  9664 V G2P-SRIB: After conversion: Skype, Skype, 5, 5
08-30 23:10:35.065  9548  9664 V G2P-SRIB: After g2p: prons 1, max_pron_len 9
08-30 23:10:35.065  9548  9664 V G2P-SRIB: Output pron: s k ay p, i in loop: 0
08-30 23:10:35.065  9548  9664 V G2P-SRIB: After conversion: alarm, alarm, 5, 5
08-30 23:10:35.065  9548  9664 V G2P-SRIB: After g2p: prons 1, max_pron_len 12
08-30 23:10:35.065  9548  9664 V G2P-SRIB: Output pron: ah l aa r m, i in loop: 0
08-30 23:10:35.065  9548  9664 V G2P-SRIB: After conversion: Voice_Search, Voice_Search, 12, 12
08-30 23:10:35.065  9548  9664 V G2P-SRIB: After g2p: prons 1, max_pron_len 15
08-30 23:10:35.065  9548  9664 V G2P-SRIB: Output pron: v oy s s er ch, i in loop: 0
08-30 23:10:35.065  9548  9664 V G2P-SRIB: After conversion: Play_Movies_&_TV, Play_Movies_&_TV, 16, 16
08-30 23:10:35.075  9548  9664 V G2P-SRIB: After g2p: prons 4, max_pron_len 49
08-30 23:10:35.075  9548  9664 V G2P-SRIB: Output pron: p l ey m uw v iy z ah n d t iy v iy, i in loop: 0
08-30 23:10:35.075  9548  9664 V G2P-SRIB: Output pron: p l ey m uw v iy z ae n d t iy v iy, i in loop: 1
08-30 23:10:35.075  9548  9664 V G2P-SRIB: Output pron: p l ey m uw v iy z ah n d t eh l ah v ih zh ah n, i in loop: 2
08-30 23:10:35.075  9548  9664 V G2P-SRIB: Output pron: p l ey m uw v iy z ae n d t eh l ah v ih zh ah n, i in loop: 3
,08-30 23:10:35.075  9548  9664 V G2P-SRIB: After conversion: My_Files, My_Files, 8, 8
08-30 23:10:35.075  9548  9664 V G2P-SRIB: After g2p: prons 1, max_pron_len 14
08-30 23:10:35.075  9548  9664 V G2P-SRIB: Output pron: m ay f ay l z, i in loop: 0
08-30 23:10:35.075  9548  9664 V G2P-SRIB: After conversion: Maps, Maps, 4, 4
08-30 23:10:35.075  9548  9664 V G2P-SRIB: After g2p: prons 1, max_pron_len 9
08-30 23:10:35.075  9548  9664 V G2P-SRIB: Output pron: m ae p s, i in loop: 0
08-30 23:10:35.075  9548  9664 V G2P-SRIB: After conversion: Clock, Clock, 5, 5
08-30 23:10:35.075  9548  9664 V G2P-SRIB: After g2p: prons 1, max_pron_len 9
08-30 23:10:35.075  9548  9664 V G2P-SRIB: Output pron: k l aa k, i in loop: 0
08-30 23:10:35.075  9548  9664 V G2P-SRIB: After conversion: Settings, Settings, 8, 8
08-30 23:10:35.075  9548  9664 V G2P-SRIB: After g2p: prons 1, max_pron_len 15
,08-30 23:10:35.075  9548  9664 V G2P-SRIB: Output pron: s eh t ih ng z, i in loop: 0
08-30 23:10:35.075  9548  9664 V G2P-SRIB: After conversion: s_planner, s_planner, 9, 9
08-30 23:10:35.075  9548  9664 V G2P-SRIB: After g2p: prons 1, max_pron_len 17
08-30 23:10:35.075  9548  9664 V G2P-SRIB: Output pron: eh s p l ae n er, i in loop: 0
08-30 23:10:35.075  9548  9664 V G2P-SRIB: After conversion: PowerPoint, PowerPoint, 10, 10
08-30 23:10:35.075  9548  9664 V G2P-SRIB: After g2p: prons 1, max_pron_len 17
08-30 23:10:35.075  9548  9664 V G2P-SRIB: Output pron: p aw er p oy n t, i in loop: 0
08-30 23:10:35.075  9548  9664 V G2P-SRIB: After conversion: Facebook, Facebook, 8, 8
08-30 23:10:35.075  9548  9664 V G2P-SRIB: After g2p: prons 1, max_pron_len 14
08-30 23:10:35.075  9548  9664 V G2P-SRIB: Output pron: f ey s b uh k, i in loop: 0
08-30 23:10:35.075  9548  9664 V G2P-SRIB: After conversion: Gmail, Gmail, 5, 5
08-30 23:10:35.075  9548  9664 V G2P-SRIB: After g2p: prons 1, max_pron_len 9
08-30 23:10:35.075  9548  9664 V G2P-SRIB: Output pron: g m ey l, i in loop: 0
08-30 23:10:35.075  9548  9664 V G2P-SRIB: After conversion: YouTube, YouTube, 7, 7
08-30 23:10:35.075  9548  9664 V G2P-SRIB: After g2p: prons 1, max_pron_len 12
08-30 23:10:35.075  9706  9706 I libpersona: KNOX_SDCARD checking this for 5009
08-30 23:10:35.075  9548  9664 V G2P-SRIB: Output pron: y uw t uw b, i in loop: 0
08-30 23:10:35.075  9706  9706 I libpersona: KNOX_SDCARD not a persona
08-30 23:10:35.075  9548  9664 V G2P-SRIB: After conversion: diary, diary, 5, 5
08-30 23:10:35.075  9548  9664 V G2P-SRIB: After g2p: prons 1, max_pron_len 11
08-30 23:10:35.075  9548  9664 V G2P-SRIB: Output pron: d ay er iy, i in loop: 0
08-30 23:10:35.075  9548  9664 V G2P-SRIB: After conversion: Camera, Camera, 6, 6
08-30 23:10:35.075  9706  9706 E Zygote  : v2
08-30 23:10:35.075  9548  9664 V G2P-SRIB: After g2p: prons 1, max_pron_len 13
08-30 23:10:35.075  9548  9664 V G2P-SRIB: Output pron: k ae m er ax, i in loop: 0
08-30 23:10:35.075  9548  9664 V G2P-SRIB: After conversion: Google, Google, 6, 6
08-30 23:10:35.075  9706  9706 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
08-30 23:10:35.075  9548  9664 V G2P-SRIB: After g2p: prons 1, max_pron_len 12
08-30 23:10:35.075  9548  9664 V G2P-SRIB: Output pron: g uw g ax l, i in loop: 0
08-30 23:10:35.075  9548  9664 V G2P-SRIB: First char , last char 
08-30 23:10:35.075  9548  9664 V G2P-SRIB: Before UTF release deinit
08-30 23:10:35.075  3384  4250 I ActivityManager: Start proc 9706:com.samsung.android.scloud/5009 for broadcast-3 com.samsung.android.scloud/.receivers.SCloudReceiver
08-30 23:10:35.075  9548  9664 V G2P-SRIB: Before g2p deinit
08-30 23:10:35.075  9706  9706 E Zygote  : accessInfo : 0
08-30 23:10:35.075  9706  9706 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.scloud 
08-30 23:10:35.075  9548  9664 D DictionaryGenerator:PocketSphinx: FileWriter is closed sucessfull
08-30 23:10:35.075  9548  9664 D DictionaryGenerator:PocketSphinx: DFG : COMPLETED in 46 ms.
08-30 23:10:35.075  9548  9664 I DictionaryGenerator:PocketSphinx:OWC: DFG : Start
08-30 23:10:35.075  9548  9664 D DictionaryGenerator:PocketSphinx: Inside initFileWriter : Dict file name : /data/user/0/com.sec.svoice.lang.en_US/files/en_US/dict/contact.dict
08-30 23:10:35.075  9548  9664 I DictionaryGenerator:PocketSphinx: mDictionaryFile = { /data/user/0/com.sec.svoice.lang.en_US/files/en_US/dict/contact.dict }
08-30 23:10:35.075  9509  9663 I jxcore-log: JXcore Cordova bridge is ready!
08-30 23:10:35.075  9509  9663 I jxcore-log: 
08-30 23:10:35.075  9509  9663 W jxcore-log: JXcore engine is started
08-30 23:10:35.075  9548  9664 D DictionaryGenerator:PocketSphinx: FileWriter created
08-30 23:10:35.075  9548  9664 D DictionaryGenerator:PocketSphinx: copying frm : /data/user/0/com.sec.svoice.lang.en_US/files/en_US/dict/contact.dict
08-30 23:10:35.075  9548  9664 D DictionaryGenerator:PocketSphinx: inside process_one_word_Call
08-30 23:10:35.075  9548  9664 D DictionaryGenerator:PocketSphinx: /data/user/0/com.sec.svoice.lang.en_US/databases
,08-30 23:10:35.085  9548  9664 D DictionaryGenerator:PocketSphinx::OWC: Deleted below entries : 
,08-30 23:10:35.085  9548  9664 D DictionaryGenerator:PocketSphinx::OWC: Newly added entries are : 
08-30 23:10:35.085  9548  9664 V G2P-SRIB: Build date: Apr 28 2016, 15:00:24
08-30 23:10:35.085  9548  9664 V G2P-SRIB: enUS G2P libs
08-30 23:10:35.085  9548  9664 V G2P-SRIB: stringCount: 0
08-30 23:10:35.085  9548  9664 V G2P-SRIB: Config: lang: en-US
08-30 23:10:35.085  9548  9664 V G2P-SRIB: variant: mp
08-30 23:10:35.085  9548  9664 V G2P-SRIB: prefix: slot_contacts_start__
08-30 23:10:35.085  9548  9664 V G2P-SRIB: suffix: __slot_contacts_end
08-30 23:10:35.085  9548  9664 V G2P-SRIB: Options dump_pron: W W K K K K K K K K K K K K K W W,
08-30 23:10:35.085  9548  9664 V G2P-SRIB: First char , last char �
08-30 23:10:35.085  9548  9664 V G2P-SRIB: Before UTF release deinit,
08-30 23:10:35.085  9548  9664 V G2P-SRIB: Before g2p deinit
08-30 23:10:35.085  9509  9645 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-30 23:10:35.085  4453  9705 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,08-30 23:10:35.085  9548  9664 D DictionaryGenerator:PocketSphinx: FileWriter is closed sucessfull
,08-30 23:10:35.085  9548  9664 D DictionaryGenerator:PocketSphinx:OWC: DFG : COMPLETED in 11 ms.
08-30 23:10:35.085  9548  9664 D PLMGenManager: TimeTaken for Dict & FSG generation 84ms
,08-30 23:10:35.085  9548  9664 D etickcount:PocketSphinx Recognition Engine:  : VSP::TimeTaken for syncUserData 470ms
,08-30 23:10:35.095  9509  9509 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-30 23:10:35.095  9706  9706 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 23:10:35.095  9706  9706 D ActivityThread: Added TimaKeyStore provider
,08-30 23:10:35.095  9548  9664 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : #en_us_v2.0.6
08-30 23:10:35.095  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP::#en_us_v2.0.6
08-30 23:10:35.095  9548  9664 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : ##General
08-30 23:10:35.095  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP::##General
08-30 23:10:35.095  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP::-hmm	am
08-30 23:10:35.095  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP::-fsg	lm/hero.detmin.fsg
08-30 23:10:35.095  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP::-fsg2	lm/hero.detmin.wo.wakeup.fsg
08-30 23:10:35.095  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP::-dict	dict/hero.dict
08-30 23:10:35.095  9548  9664 I eN66    : JNI Enter Function Java_com_asr_pocketsphinx_pocketsphinxJNI_Config_1setNLUCfg
08-30 23:10:35.095  9548  9664 I eN66    : Library build date: May  2 2016 @ 14:31:17
08-30 23:10:35.095  9548  9664 I eN66    : JNI Config_setNLUCfg /data/user/0/com.sec.svoice.lang.en_US/files/en_US/nlu/nlu.cfg
08-30 23:10:35.095  9548  9664 I eN66    : JNI debug Config_setNLUCfg /data/user/0/com.sec.svoice.lang.en_US/files/en_US/nlu/nlu.cfg 1 time
08-30 23:10:35.095  9548  9664 I eN66    : JNI Exit Function Java_com_asr_pocketsphinx_pocketsphinxJNI_Config_1setNLUCfg
08-30 23:10:35.095  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP::-rnlu	nlu/nlu.cfg
08-30 23:10:35.095  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP::-maxwpf	4
08-30 23:10:35.095  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP::-maxhmmpf	1800
08-30 23:10:35.095  9548  9664 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : #-rawlogdir
08-30 23:10:35.095  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP::#-rawlogdir	log
08-30 23:10:35.095  9548  9664 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : 
08-30 23:10:35.095  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP::
08-30 23:10:35.095  9548  9664 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : ##DNN
08-30 23:10:35.095  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP::##DNN
08-30 23:10:35.095  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP::-context	11
08-30 23:10:35.095  9548  9664 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : #quantization range
08-30 23:10:35.095  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP::#quantization range
08-30 23:10:35.095  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP::-QRange	1024
08-30 23:10:35.095  9548  9664 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : #1 means not skipped, 2 means skip every 2 frames
08-30 23:10:35.095  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP::#1 means not skipped, 2 means skip every 2 frames
08-30 23:10:35.095  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP::-frmskip	1
08-30 23:10:35.095  9548  9664 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : #quantized dnn binary file (not using dnn)
08-30 23:10:35.095  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP::#quantized dnn binary file (not using dnn)
08-30 23:10:35.095  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP::-qdnn	am/qdnn.net
08-30 23:10:35.095  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP::-feat_transform	am/feat.bin
08-30 23:10:35.095  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP::-prior	am/prior_prob.out
08-30 23:10:35,.095  9548  9664 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : 
08-30 23:10:35.095  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP::
08-30 23:10:35.095  9548  9664 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : ##Confidence score
08-30 23:10:35.095  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP::##Confidence score
08-30 23:10:35.095  9548  9664 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : #-confs
08-30 23:10:35.095  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP::#-confs	yes
08-30 23:10:35.095  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP::-conf_use_senone	0
08-30 23:10:35.095  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP::-conf_use_pls	0
08-30 23:10:35.095  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP::-conf_use_ll	1
08-30 23:10:35.095  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP::-pip	1.5
08-30 23:10:35.095  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP::-wip	7
08-30 23:10:35.095  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP::-lw	3
08-30 23:10:35.095  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP::-dnn_ascale	2.5
08-30 23:10:35.095  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP::-prior_ratio	0.92
08-30 23:10:35.095  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP::-conf_mapscore_params	[-42,0,-18,50,-4,100][9,0,28,50,57,100][-12,0,10,50,24,100]
08-30 23:10:35.095  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP::-non_speech_tied_states	[93:94:95]
08-30 23:10:35.095  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP::-conf_disagreement_percent	20.0
08-30 23:10:35.095  9548  9664 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : 
08-30 23:10:35.095  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP::
08-30 23:10:35.095  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP::-conf_max_llr_th	25
08-30 23:10:35.095  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP::-conf_use_ci	no
08-30 23:10:35.095  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP::-bestpath	0
08-30 23:10:35.095  9548  9664 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : #now phoneloop score is not used phoneloop score => senon score
08-30 23:10:35.095  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP::#now phoneloop score is not used phoneloop score => senon score
08-30 23:10:35.095  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP::-pl_window	0
08-30 23:10:35.095  9548  9664 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : #excluding silence frames in score
08-30 23:10:35.095  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP::#excluding silence frames in score
08-30 23:10:35.095  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP::-no_silence	1
08-30 23:10:35.095  9548  9664 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : #mapping parameter
08-30 23:10:35.095  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP::#mapping parameter
08-30 23:10:35.105  9548  9664 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : #-lang
08-30 23:10:35.105  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP::#-lang	1
08-30 23:10:35.105  9548  9664 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : #excluding score on WUW
08-30 23:10:35.105  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP::#excluding score on WUW
08-30 2,3:10:35.105  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP::-wake-up-cmd	1
08-30 23:10:35.105  9548  9664 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : 
08-30 23:10:35.105  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP::
08-30 23:10:35.105  9548  9664 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : ##Rejection
08-30 23:10:35.105  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP::##Rejection
08-30 23:10:35.105  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP::-reject_list	lm/reject.hyp
08-30 23:10:35.105  9548  9664 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : 
08-30 23:10:35.105  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP::
08-30 23:10:35.105  9548  9664 W etickcount:PocketSphinx Recognition Engine:  : VSP::Entered to default case....i.e. a miss happened for : ##Android related
08-30 23:10:35.105  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP::##Android related
08-30 23:10:35.105  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP::-conf_thresh	49
08-30 23:10:35.105  9548  9664 D etickcount:PocketSphinx Recognition Engine:  : VSP::Previous state : INIT
08-30 23:10:35.105  9548  9664 I eN66    : JNI Enter Function Java_com_asr_pocketsphinx_pocketsphinxJNI_new_1Decoder_1_1SWIG_11
08-30 23:10:35.105  9548  9664 I eN66    : ps_reinit start
08-30 23:10:35.105  9548  9664 I eN66    : configured dir of hmm /data/user/0/com.sec.svoice.lang.en_US/files/en_US/am
08-30 23:10:35.105  9548  9664 I eN66    : ps_init_defaults end
08-30 23:10:35.105  3384  4323 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ae45f40 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{25e9c62 9706:com.samsung.android.scloud/5009}
08-30 23:10:35.115  9706  9706 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
08-30 23:10:35.115  9706  9706 D RelationGraph: garbageCollect()
08-30 23:10:35.115  9706  9706 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.samsung.android.scloud
08-30 23:10:35.115  3384  3449 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
08-30 23:10:35.115  9706  9706 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
08-30 23:10:35.115  9706  9706 D ResourcesManager: For user 0 new overlays fetched Null
08-30 23:10:35.115  9706  9706 I InjectionManager: Inside getClassLibPath caller 
08-30 23:10:35.125  9706  9706 W System  : ClassLoader referenced unknown path: /system/priv-app/SamsungCloud/lib/arm64
08-30 23:10:35.125  4453  9705 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package com.test.thalitest
08-30 23:10:35.135  4453  9705 D ResourcesManager: For user 0 new overlays fetched Null
08-30 23:10:35.135  4453  9705 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package com.test.thalitest
08-30 23:10:35.135  9706  9706 I [SC]RequestProvider: onCreate() ~!! : com.samsung.android.scloud.framework.SamsungCloudApp@87e3230
08-30 23:10:35.135  9706  9706 I [SC]QuotaInterfaceManager: sync start
,08-30 23:10:35.145  9706  9706 I [SC]RequestProvider: uiregister - started.
08-30 23:10:35.145  9706  9706 I [SC]RequestProvider: quotaregister - started.
,08-30 23:10:35.145  9706  9706 I [SC]ExternalOEMControlProvider: onCreate
,08-30 23:10:35.165  9706  9706 V SamsungCloudLogs:  set Log level [4->4]act[false]
,08-30 23:10:35.165  9706  9706 I [SC]CommonUtil: isSemAvailable:0
08-30 23:10:35.165  9706  9706 I [SC]SamsungCloudApp: AppVer[2.1.11][L:4]Sem[false]V2DEV_R slog[false]com.samsung.android.scloud
08-30 23:10:35.165  9706  9706 I [SC]SamsungCloudApp: controller allowed
,08-30 23:10:35.165  9706  9706 I [SC]MetaManager: MetaManager--[elapse:       1] Version Info[2.0.00]
,08-30 23:10:35.165  9706  9706 I [SC]FeatureManager: FeatureManager 
08-30 23:10:35.165  9706  9706 I [SC]FeatureManager: [SEC_FLOATING_FEATURE_SAMSUNGCLOUD_CONFIG_CLOUD_USAGE_MENU_TREE]str 
08-30 23:10:35.165  9706  9706 I [SC]FeatureManager: [SEC_FLOATING_FEATURE_SAMSUNGCLOUD_ENABLE_SETTING_MENU]bln true
,08-30 23:10:35.165  9706  9706 I [SC]ModelManager: ModelManager++
08-30 23:10:35.165  9706  9706 I [SC]CommonUtil: getClockPkgName pkg[com.sec.android.app.clockpackage] csc[]
08-30 23:10:35.165  9706  9706 I [SC]CommonUtil: getContactsPkgName pkg[com.android.contacts] csc[]
08-30 23:10:35.165  9706  9706 I [SC]CommonUtil: getMessagePkgName com.android.mms
,08-30 23:10:35.165  9706  9706 I [SC]CommonUtil: getEmailProviderPkgName com.samsung.android.email.provider
08-30 23:10:35.165  9706  9706 I [SC]CommonUtil: getCalendarPkgName com.android.calendar
,08-30 23:10:35.165  9706  9706 I [SC]CommonUtil: getMessagePkgName com.android.mms
08-30 23:10:35.165  9706  9706 I [SC]CommonUtil: getContactsPkgName pkg[com.android.contacts] csc[]
08-30 23:10:35.165  9706  9706 I [SC]CommonUtil: getCallPkgName com.android.incallui
08-30 23:10:35.165  9706  9706 I [SC]CommonUtil: getEmailProviderPkgName com.samsung.android.email.provider
,08-30 23:10:35.165  9706  9706 I [SC]Logs: [BaseModel]CALLLOGS                  logs                                               content://logs/historys
,08-30 23:10:35.175  9706  9706 I [SC]CommonUtil: isVoiceCallSupport : true
08-30 23:10:35.175  9706  9706 I [SC]ModelManager: addModel[+] CALLLOGS                  isEnable[true ] --:content://logs/historys::com.android.contacts
,08-30 23:10:35.175  9706  9706 I [SC]VIPList: [BaseModel]VIPLIST                   com.samsung.android.email.provider                 content://com.samsung.android.email.provider/viplist
,08-30 23:10:35.175  9706  9706 I [SC]ModelManager: addModel[+] VIPLIST                   isEnable[true ] --:content://com.samsung.android.email.provider/viplist::com.samsung.android.email.provider
08-30 23:10:35.175  9706  9706 I [SC]BlackList: [BaseModel]BLACKLIST                 com.samsung.android.email.provider                 content://com.samsung.android.email.provider/blacklist
,08-30 23:10:35.175  9706  9706 I [SC]ModelManager: addModel[+] BLACKLIST                 isEnable[true ] --:content://com.samsung.android.email.provider/blacklist::com.samsung.android.email.provider
,08-30 23:10:35.175  9706  9706 I [SC]Spam: [BaseModel]SPAM                      mms-sms                                            content://mms-sms/spam-filter
08-30 23:10:35.175  9706  9706 I [SC]ModelManager: addModel[+] SPAM                      isEnable[true ] --:content://mms-sms/spam-filter::com.android.mms
,08-30 23:10:35.175  9706  9706 I [SC]CallReject: [BaseModel]CALLREJECT                com.android.phone.callsettings                     content://com.android.phone.callsettings/reject_num
,08-30 23:10:35.175  9548  9664 I eN66    : 
08-30 23:10:35.175  9548  9664 I eN66    : FSG model <n66_cmd_eng> is loaded
,08-30 23:10:35.195  4157  4170 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg com.google.android.googlequicksearchbox,id=10436,extra=Bundle[mParcelledData.dataSize=84]
08-30 23:10:35.195  4157  4157 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=10436, samsung.notification.type=normal, samsung.people.package_name=com.google.android.googlequicksearchbox}]
,08-30 23:10:35.195  4157  4157 I PeopleStripeService: PeopleNotificationReceiver:3
08-30 23:10:35.195  4157  4157 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
08-30 23:10:35.195  4157  4157 I PeopleDataManager: removeNotification
08-30 23:10:35.195  4157  4157 I NotificationParser: getNotiType:com.google.android.googlequicksearchbox,null
08-30 23:10:35.195  4157  4157 D PeopleDataManager: removeNotiInfo: id =10436,packageName=com.google.android.googlequicksearchbox,isEdgeNotification=false,key=null,removeAll=false
08-30 23:10:35.195  4157  4157 D PeopleDataManager: removeNotiInfo =null
08-30 23:10:35.195  9548  9664 I eN66    : 
08-30 23:10:35.195  9548  9664 I eN66    : ps_reinit : Secondary FSG model <n66_cmd_eng> is loaded
08-30 23:10:35.195  9548  9664 I eN66    : 
08-30 23:10:35.195  9548  9664 I eN66    : ps_reinit : Current active FSG model is <n66_cmd_eng>
08-30 23:10:35.195  9548  9664 I eN66    : Decoder initialization is complete
08-30 23:10:35.195  9548  9664 I eN66    : JNI Exit Function Java_com_asr_pocketsphinx_pocketsphinxJNI_new_1Decoder_1_1SWIG_11 Instance -185359392
08-30 23:10:35.195  9706  9706 I [SC]CommonUtil: isVoiceCallSupport : true
08-30 23:10:35.195  9706  9706 I [SC]ModelManager: addModel[+] CALLREJECT                isEnable[true ] --:content://com.android.phone.callsettings/reject_num::com.android.incallui
08-30 23:10:35.195  9548  9664 I etickcount:PocketSphinx Recognition Engine:  : VSP::State changed to READY
08-30 23:10:35.205  9548  9664 D etickcount:PocketSphinx Recognition Engine:  : VSP::TimeTaken for Decoder init 111ms
08-30 23:10:35.205  9548  9664 D etickcount:PocketSphinx Recognition Engine:  : VSP::Total Load time 620ms
08-30 23:10:35.205  9706  9706 I [SC]ConnectionsSetting: [BaseModel]CONNECTIONS               com.android.settings.accessibility.sharedaccessibility.backup content://com.android.settings.accessibility.sharedaccessibility.backup
,08-30 23:10:35.205  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:35.205  9706  9706 I [SC]ModelManager: addModel[+] CONNECTIONS               isEnable[false] --:content://com.android.settings.accessibility.sharedaccessibility.backup::com.android.settings
,08-30 23:10:35.205  9706  9706 I [SC]RingtoneSetting: [BaseModel]RINGTONESETTING           null                                               null
08-30 23:10:35.205  9706  9706 I [SC]ModelManager: addModel[+] RINGTONESETTING           isEnable[true ] --:null::com.sec.android.app.ringtoneBR
,08-30 23:10:35.215  9706  9706 I [SC]Music: [BaseModel]MUSIC                     null                                               null
,08-30 23:10:35.215  9706  9706 I [SC]ModelManager: addModel[+] MUSIC                     isEnable[true ] --:null::com.samsung.android.scloud
,08-30 23:10:35.215  9706  9706 I [SC]Document: [BaseModel]DOCUMENT                  null                                               null
,08-30 23:10:35.215  9706  9706 I [SC]ModelManager: addModel[+] DOCUMENT                  isEnable[true ] --:null::com.samsung.android.scloud
,08-30 23:10:35.215  9706  9706 I [SC]Application: [BaseModel]APP                       null                                               null
,08-30 23:10:35.215  9706  9706 I [SC]ModelManager: addModel[+] APP                       isEnable[true ] --:null::com.samsung.android.scloud
,08-30 23:10:35.215  9706  9706 I [SC]Home: [BaseModel]HomescreenBackup          com.sec.android.app.launcher                       content://com.sec.android.app.launcher
08-30 23:10:35.215  9706  9706 I [SC]ModelManager: addModel[+] HomescreenBackup          isEnable[true ] --:content://com.sec.android.app.launcher::com.sec.android.app.launcher
,08-30 23:10:35.225  9706  9706 W ResourcesManager: getTopLevelResources: /system/priv-app/VoiceNote_4.0/VoiceNote_4.0.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.sec.android.app.voicenote
,08-30 23:10:35.225  9706  9706 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:35.225  9706  9706 I [SC]ExternalOEMControl_VOICE: updateModelInfo() called, src[VOICE] cid[vMkD7IBgaR] isNew[true] dataType[null]
,08-30 23:10:35.225  9706  9706 I [SC]ExternalModel: [BaseModel]VOICE                     com.sec.android.app.voicenote                      content://com.sec.android.app.voicenote.backup
08-30 23:10:35.225  9706  9706 I [SC]ExternalModel: duplicateConfig[0] : true
,08-30 23:10:35.225  9706  9706 I [SC]ExternalModel: duplicateConfig[1] : false
08-30 23:10:35.225  9706  9706 I [SC]ModelManager: addModel[+] VOICE                     isEnable[true ] V2:content://com.sec.android.app.voicenote.backup::com.sec.android.app.voicenote
08-30 23:10:35.225  9706  9706 I [SC]ModelManager: loadExternalModelsFromPkg[VOICE                                        ] pkg:com.sec.android.app.voicenote                 register[IFileClient:vMkD7IBgaR]
,08-30 23:10:35.225  9706  9706 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.samsung.android.email.provider
,08-30 23:10:35.225  9706  9706 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:35.225  4453  9705 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 141 ms] updated apps [took 141 ms] 
,08-30 23:10:35.235  9706  9706 I [SC]ExternalOEMControlLegacy_Email: updateModelInfo() called, src[Email] cid[QJ5JBlRnP9] isNew[true]
08-30 23:10:35.235  9706  9706 I [SC]ExternalModelLegacy: [BaseModel]Email                     com.samsung.android.email.provider                 content://com.samsung.android.email.provider.backup[Q]
08-30 23:10:35.235  9706  9706 I [SC]ModelManager: addModel[+] Email                     isEnable[true ] V1:content://com.samsung.android.email.provider.backup::com.samsung.android.email.provider:[Q]
08-30 23:10:35.235  9706  9706 I [SC]ModelManager: loadExternalModelsFromPkg[Email                                        ] pkg:com.samsung.android.email.provider            register[ISCloudQBNRClient:QJ5JBlRnP9]
,08-30 23:10:35.235  9706  9706 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.sec.android.app.sbrowser
,08-30 23:10:35.235  9706  9706 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:35.235  9706  9706 I [SC]ExternalOEMControlLegacy_SBROWSERSETTING: updateModelInfo() called, src[SBROWSERSETTING] cid[kw8vqQFzo3] isNew[true]
,08-30 23:10:35.235  9706  9706 I [SC]ExternalModelLegacy: [BaseModel]SBROWSERSETTING           com.sec.android.app.sbrowser                       content://com.sec.android.app.sbrowser.backup[Q]
08-30 23:10:35.235  9706  9706 I [SC]ModelManager: addModel[+] SBROWSERSETTING           isEnable[true ] V1:content://com.sec.android.app.sbrowser.backup::com.sec.android.app.sbrowser:[Q]
08-30 23:10:35.235  9706  9706 I [SC]ModelManager: loadExternalModelsFromPkg[SBROWSERSETTING                              ] pkg:com.sec.android.app.sbrowser                  register[ISCloudQBNRClient:kw8vqQFzo3]
,08-30 23:10:35.235  9706  9706 W ResourcesManager: getTopLevelResources: /system/priv-app/SVoice_1.0/SVoice_1.0.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.samsung.voiceserviceplatform
,08-30 23:10:35.235  9706  9706 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:35.235  9706  9706 I [SC]ExternalOEMControlLegacy_SVOICESETTING: updateModelInfo() called, src[SVOICESETTING] cid[bLEmzxKOex] isNew[true]
,08-30 23:10:35.235  9706  9706 I [SC]ExternalModelLegacy: [BaseModel]SVOICESETTING             com.samsung.voiceserviceplatform                   content://com.samsung.voiceserviceplatform.backup[Q]
08-30 23:10:35.235  9706  9706 I [SC]ModelManager: addModel[+] SVOICESETTING             isEnable[true ] V1:content://com.samsung.voiceserviceplatform.backup::com.samsung.voiceserviceplatform:[Q]
08-30 23:10:35.235  9706  9706 I [SC]ModelManager: loadExternalModelsFromPkg[SVOICESETTING                                ] pkg:com.samsung.voiceserviceplatform              register[ISCloudQBNRClient:bLEmzxKOex]
,08-30 23:10:35.245  9706  9706 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M/SPlanner_M.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.android.calendar
,08-30 23:10:35.245  9706  9706 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:35.245  9706  9706 I [SC]ExternalOEMControlLegacy_CALENDARSETTING: updateModelInfo() called, src[CALENDARSETTING] cid[ztQlGIvsvZ] isNew[true]
08-30 23:10:35.245  9706  9706 I [SC]ExternalModelLegacy: [BaseModel]CALENDARSETTING           com.android.calendar                               content://com.android.calendar.backup[Q]
,08-30 23:10:35.245  9706  9706 I [SC]ModelManager: addModel[+] CALENDARSETTING           isEnable[true ] V1:content://com.android.calendar.backup::com.android.calendar:[Q]
08-30 23:10:35.245  9706  9706 I [SC]ModelManager: loadExternalModelsFromPkg[CALENDARSETTING                              ] pkg:com.android.calendar                          register[ISCloudQBNRClient:ztQlGIvsvZ]
,08-30 23:10:35.245  9706  9706 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.android.settings
,08-30 23:10:35.245  9706  9706 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:35.245  9706  9706 I [SC]ExternalOEMControlLegacy_ACCESSIBILITYSETTINGS: updateModelInfo() called, src[ACCESSIBILITYSETTINGS] cid[X6qErjsfs2] isNew[true]
,08-30 23:10:35.245  9706  9706 I [SC]ExternalModelLegacy: [BaseModel]ACCESSIBILITYSETTINGS     com.android.settings                               content://com.android.settings.accessibility.sharedaccessibility.backup[Q]
08-30 23:10:35.245  9706  9706 I [SC]ModelManager: addModel[+] ACCESSIBILITYSETTINGS     isEnable[true ] V1:content://com.android.settings.accessibility.sharedaccessibility.backup::com.android.settings:[Q]
08-30 23:10:35.245  9706  9706 I [SC]ModelManager: loadExternalModelsFromPkg[ACCESSIBILITYSETTINGS                        ] pkg:com.android.settings                          register[ISCloudQBNRClient:X6qErjsfs2]
08-30 23:10:35.245  9706  9706 I [SC]ModelManager: loadExternalModelsFromPkg[CONNECTIONS                                  ] pkg:com.android.settings                          subKey[CONNECTIONS]
08-30 23:10:35.245  9706  9706 I [SC]ConnectionsSetting: CONNECTIONS               setEnable[true]
08-30 23:10:35.245  9706  9706 I [SC]ModelManager: loadExternalModelsFromPkg[CONNECTIONS                                  ] pkg:com.android.settings                          subKey[WiFi]
,08-30 23:10:35.245  9706  9706 I [SC]ConnectionsSetting: CONNECTIONS               setEnable[true]
,08-30 23:10:35.255  9706  9706 W ResourcesManager: getTopLevelResources: /system/priv-app/TouchWizHome_2016/TouchWizHome_2016.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.sec.android.app.launcher
,08-30 23:10:35.255  9706  9706 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:35.255  9706  9706 E [SC]SCLOUD_ERR-CommonUtil: getCertificateSHA1Fingerprint err :com.samsung.android.scloud.backupsamplecode 
,08-30 23:10:35.255  9706  9706 I [SC]ModelManager: loadExternalModelsFromPkg pkg:com.samsung.android.scloud.backupsamplecode   NotExist[null]
,08-30 23:10:35.255  9706  9706 W ResourcesManager: getTopLevelResources: /system/priv-app/TeleService/TeleService.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.android.phone
,08-30 23:10:35.255  9706  9706 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:35.255  9706  9706 I [SC]ExternalOEMControlLegacy_CALLSETTING: updateModelInfo() called, src[CALLSETTING] cid[IHLhQxraiP] isNew[true]
08-30 23:10:35.255  9706  9706 I [SC]ExternalModelLegacy: [BaseModel]CALLSETTING               com.android.phone                                  content://com.android.phone.backup[Q]
,08-30 23:10:35.255  9706  9706 I [SC]ModelManager: addModel[+] CALLSETTING               isEnable[true ] V1:content://com.android.phone.backup::com.android.phone:[Q]
08-30 23:10:35.255  9706  9706 I [SC]ModelManager: loadExternalModelsFromPkg[CALLSETTING                                  ] pkg:com.android.phone                             register[ISCloudQBNRClient:IHLhQxraiP]
,08-30 23:10:35.265  9706  9706 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.sec.android.inputmethod
,08-30 23:10:35.265  9706  9706 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:35.265  9706  9706 I [SC]ExternalOEMControlLegacy_IMESETTING: updateModelInfo() called, src[IMESETTING] cid[ghXxWAP1aK] isNew[true]
,08-30 23:10:35.265  9706  9706 I [SC]ExternalModelLegacy: [BaseModel]IMESETTING                com.sec.android.inputmethod                        content://com.sec.android.inputmethod.backup[Q]
08-30 23:10:35.265  9706  9706 I [SC]ModelManager: addModel[+] IMESETTING                isEnable[true ] V1:content://com.sec.android.inputmethod.backup::com.sec.android.inputmethod:[Q]
08-30 23:10:35.265  9706  9706 I [SC]ModelManager: loadExternalModelsFromPkg[IMESETTING                                   ] pkg:com.sec.android.inputmethod                   register[ISCloudQBNRClient:ghXxWAP1aK]
,08-30 23:10:35.265  9706  9706 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.android.contacts
,08-30 23:10:35.265  9706  9706 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:35.265  9706  9706 I [SC]ExternalOEMControlLegacy_MyProfile: updateModelInfo() called, src[MyProfile] cid[2yOE2P9maz] isNew[true]
08-30 23:10:35.265  9706  9706 I [SC]ExternalModelLegacy: [BaseModel]MyProfile                 com.android.contacts                               content://com.samsung.contacts.backup
,08-30 23:10:35.265  9706  9706 I [SC]ModelManager: addModel[+] MyProfile                 isEnable[true ] V1:content://com.samsung.contacts.backup::com.android.contacts:
08-30 23:10:35.265  9706  9706 I [SC]ModelManager: loadExternalModelsFromPkg[MyProfile                                    ] pkg:com.android.contacts                          register[ISCloudBNRClient:2yOE2P9maz]
08-30 23:10:35.265  9706  9706 I [SC]ExternalOEMControlLegacy_CONTACTSETTING: updateModelInfo() called, src[CONTACTSETTING] cid[jqwmo66Bdc] isNew[true]
08-30 23:10:35.265  9706  9706 I [SC]ExternalModelLegacy: [BaseModel]CONTACTSETTING            com.android.contacts                               content://com.samsung.contacts.backup[Q]
08-30 23:10:35.265  9706  9706 I [SC]ModelManager: addModel[+] CONTACTSETTING            isEnable[true ] V1:content://com.samsung.contacts.backup::com.android.contacts:[Q]
08-30 23:10:35.265  9706  9706 I [SC]ModelManager: loadExternalModelsFromPkg[CONTACTSETTING                               ] pkg:com.android.contacts                          register[ISCloudQBNRClient:jqwmo66Bdc]
08-30 23:10:35.265  9706  9706 I [SC]ExternalOEMControl_CONTACT: updateModelInfo() called, src[CONTACT] cid[2vInYbEf2V] isNew[true] dataType[json]
,08-30 23:10:35.265  9706  9706 I [SC]ExternalModel: [BaseModel]CONTACT                   com.android.contacts                               content://com.samsung.contacts.backup
08-30 23:10:35.265  9706  9706 I [SC]ModelManager: addModel[+] CONTACT                   isEnable[true ] V2:content://com.samsung.contacts.backup::com.android.contacts
08-30 23:10:35.265  9706  9706 I [SC]ModelManager: loadExternalModelsFromPkg[CONTACT                                      ] pkg:com.android.contacts                          register[IRecordClient:2vInYbEf2V]
08-30 23:10:35.265  9706  9706 I [SC]ModelManager: loadExternalModelsFromPkg[HomescreenBackup                             ] pkg:com.android.contacts                          subKey[HomescreenContactShortcut]
,08-30 23:10:35.275  9706  9706 W ResourcesManager: getTopLevelResources: /system/app/ClockPackage_M/ClockPackage_M.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.sec.android.app.clockpackage
,08-30 23:10:35.275  9706  9706 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:35.275  9706  9706 I [SC]ExternalOEMControlLegacy_Alarm: updateModelInfo() called, src[Alarm] cid[v5VJ0Ep6EE] isNew[true]
,08-30 23:10:35.275  9706  9706 I [SC]ExternalModelLegacy: [BaseModel]Alarm                     com.sec.android.app.clockpackage                   content://com.sec.android.app.clockpackage
08-30 23:10:35.275  9706  9706 I [SC]ModelManager: addModel[+] Alarm                     isEnable[true ] V1:content://com.sec.android.app.clockpackage::com.sec.android.app.clockpackage:
08-30 23:10:35.275  9706  9706 I [SC]ModelManager: loadExternalModelsFromPkg[Alarm                                        ] pkg:com.sec.android.app.clockpackage              register[ISCloudBNRClient:v5VJ0Ep6EE]
08-30 23:10:35.275  9706  9706 I [SC]ExternalOEMControlLegacy_WorldClock: updateModelInfo() called, src[WorldClock] cid[pYz7p28bSl] isNew[true]
08-30 23:10:35.275  9706  9706 I [SC]ExternalModelLegacy: [BaseModel]WorldClock                com.sec.android.app.clockpackage                   content://com.sec.android.app.clockpackage
08-30 23:10:35.275  9706  9706 I [SC]ModelManager: addModel[+] WorldClock                isEnable[true ] V1:content://com.sec.android.app.clockpackage::com.sec.android.app.clockpackage:
08-30 23:10:35.275  9706  9706 I [SC]ModelManager: loadExternalModelsFromPkg[WorldClock                                   ] pkg:com.sec.android.app.clockpackage              register[ISCloudBNRClient:pYz7p28bSl]
08-30 23:10:35.275  9706  9706 I [SC]ModelManager: loadExternalModelsFromPkg[HomescreenBackup                             ] pkg:com.sec.android.app.clockpackage              subKey[ALARMWIDGET]
,08-30 23:10:35.275  9706  9706 I [SC]ModelManager: loadExternalModelsFromPkg[HomescreenBackup                             ] pkg:com.sec.android.app.clockpackage              subKey[DUALCLOCKWIDGET]
,08-30 23:10:35.275  9706  9706 W ResourcesManager: getTopLevelResources: /system/priv-app/SecCalendarProvider_NOTSTICKER/SecCalendarProvider_NOTSTICKER.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.android.providers.calendar
,08-30 23:10:35.275  9706  9706 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:35.275  9706  9706 I [SC]ExternalOEMControl_EVENT: updateModelInfo() called, src[EVENT] cid[qsoHwGCEEw] isNew[true] dataType[json]
,08-30 23:10:35.275  9706  9706 I [SC]ExternalModel: [BaseModel]EVENT                     com.android.providers.calendar                     content://com.samsung.android.providers.calendar.backup
08-30 23:10:35.275  9706  9706 I [SC]ModelManager: addModel[+] EVENT                     isEnable[true ] V2:content://com.samsung.android.providers.calendar.backup::com.android.providers.calendar
08-30 23:10:35.275  9706  9706 I [SC]ModelManager: loadExternalModelsFromPkg[EVENT                                        ] pkg:com.android.providers.calendar                register[IRecordClient:qsoHwGCEEw]
08-30 23:10:35.275  9706  9706 I [SC]ExternalOEMControl_TASK: updateModelInfo() called, src[TASK] cid[cLT79jJ29l] isNew[true] dataType[json]
08-30 23:10:35.275  9706  9706 I [SC]ExternalModel: [BaseModel]TASK                      com.android.providers.calendar                     content://com.samsung.android.providers.calendar.backup
08-30 23:10:35.275  9706  9706 I [SC]ModelManager: addModel[+] TASK                      isEnable[true ] V2:content://com.samsung.android.providers.calendar.backup::com.android.providers.calendar
08-30 23:10:35.275  9706  9706 I [SC]ModelManager: loadExternalModelsFromPkg[TASK                                         ] pkg:com.android.providers.calendar                register[IRecordClient:cLT79jJ29l]
,08-30 23:10:35.285  9706  9706 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Epic_Common/SecMms_Epic_Common.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.android.mms
,08-30 23:10:35.285  9706  9706 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:35.285  9706  9706 I [SC]ExternalOEMControlLegacy_MessagesSettings: updateModelInfo() called, src[MessagesSettings] cid[XUHtHcYNfq] isNew[true]
,08-30 23:10:35.285  9706  9706 I [SC]ExternalModelLegacy: [BaseModel]MessagesSettings          com.android.mms                                    content://com.samsung.mms.settings.backup[Q]
08-30 23:10:35.285  9706  9706 I [SC]ModelManager: addModel[+] MessagesSettings          isEnable[true ] V1:content://com.samsung.mms.settings.backup::com.android.mms:[Q]
08-30 23:10:35.285  9706  9706 I [SC]ModelManager: loadExternalModelsFromPkg[MessagesSettings                             ] pkg:com.android.mms                               register[ISCloudQBNRClient:XUHtHcYNfq]
,08-30 23:10:35.285  9706  9706 W ResourcesManager: getTopLevelResources: /system/priv-app/SecTelephonyProvider_Epic/SecTelephonyProvider_Epic.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.android.providers.telephony
,08-30 23:10:35.285  9706  9706 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:35.285  9706  9706 I [SC]ExternalOEMControlLegacy_Chat: updateModelInfo() called, src[Chat] cid[nx7Fde25jd] isNew[true]
,08-30 23:10:35.285  4296  4673 I [PDLIB]ClientProvider, VERSION : 2.2.0: call !!  method : getClientInfo, arg : Chat
,08-30 23:10:35.285  4296  4673 D TP/BnRUtils: getCscFreeMessage(), config = off
08-30 23:10:35.285  4296  4673 D TP/BnRUtils: getEnableSupportBackup() = false
08-30 23:10:35.285  4296  4673 I [PDLIB]BNRClientHelper-Chat: GET_CLIENT_INFO, Chat
,08-30 23:10:35.295  9706  9706 I [SC]ExternalOEMControlLegacy_Chat: updateModelInfo() supportBnr is false
08-30 23:10:35.295  9706  9706 I [SC]ExternalOEMControlLegacy_FileTransfer: updateModelInfo() called, src[FileTransfer] cid[LyxMGTa8W3] isNew[true]
08-30 23:10:35.295  4296  4308 I [PDLIB]ClientProvider, VERSION : 2.2.0: call !!  method : getClientInfo, arg : FileTransfer
08-30 23:10:35.295  4296  4308 D TP/BnRUtils: getCscFreeMessage(), config = off
,08-30 23:10:35.295  4296  4308 D TP/BnRUtils: getEnableSupportBackup() = false
08-30 23:10:35.295  4296  4308 I [PDLIB]BNRClientHelper-FileTransfer: GET_CLIENT_INFO, FileTransfer
08-30 23:10:35.295  9706  9706 I [SC]ExternalOEMControlLegacy_FileTransfer: updateModelInfo() supportBnr is false
08-30 23:10:35.295  9706  9706 I [SC]ExternalOEMControl_SMS: updateModelInfo() called, src[SMS] cid[N0iXqXm9oM] isNew[true] dataType[json]
08-30 23:10:35.295  9706  9706 I [SC]ExternalModel: [BaseModel]SMS                       com.android.providers.telephony                    content://com.android.providers.telephony.backup
08-30 23:10:35.295  9706  9706 I [SC]ModelManager: addModel[+] SMS                       isEnable[true ] V2:content://com.android.providers.telephony.backup::com.android.providers.telephony
,08-30 23:10:35.295  9706  9706 I [SC]ModelManager: loadExternalModelsFromPkg[SMS                                          ] pkg:com.android.providers.telephony               register[IRecordClient:N0iXqXm9oM]
08-30 23:10:35.295  9706  9706 I [SC]ExternalOEMControl_MMS: updateModelInfo() called, src[MMS] cid[I7o6E6m1Lj] isNew[true] dataType[json]
08-30 23:10:35.295  9706  9706 I [SC]ExternalModel: [BaseModel]MMS                       com.android.providers.telephony                    content://com.android.providers.telephony.backup
08-30 23:10:35.295  9706  9706 I [SC]ModelManager: addModel[+] MMS                       isEnable[true ] V2:content://com.android.providers.telephony.backup::com.android.providers.telephony
08-30 23:10:35.295  9706  9706 I [SC]ModelManager: loadExternalModelsFromPkg[MMS                                          ] pkg:com.android.providers.telephony               register[IRecordClient:I7o6E6m1Lj]
,08-30 23:10:35.295  9706  9706 W ResourcesManager: getTopLevelResources: /system/app/WeatherWidget2016/WeatherWidget2016.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.sec.android.daemonapp
,08-30 23:10:35.295  9706  9706 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:35.295  9706  9706 I [SC]ExternalOEMControlLegacy_WEATHERWIDGET: updateModelInfo() called, src[WEATHERWIDGET] cid[oo2JSUuSBb] isNew[true]
08-30 23:10:35.295  9706  9706 I [SC]ExternalModelLegacy: [BaseModel]WEATHERWIDGET             com.sec.android.daemonapp                          content://com.sec.android.daemonapp.backup[Q]
,08-30 23:10:35.295  9706  9706 I [SC]ModelManager: addModel[+] WEATHERWIDGET             isEnable[true ] V1:content://com.sec.android.daemonapp.backup::com.sec.android.daemonapp:[Q]
08-30 23:10:35.295  9706  9706 I [SC]ModelManager: loadExternalModelsFromPkg[WEATHERWIDGET                                ] pkg:com.sec.android.daemonapp                     register[ISCloudQBNRClient:oo2JSUuSBb]
08-30 23:10:35.295  9706  9706 I [SC]ModelManager: loadExternalModelsFromPkg[elapse:      79]
08-30 23:10:35.295  9706  9706 I [SC]ModelManager: ModelManager--[elapse:     132]
,08-30 23:10:35.305  9706  9706 D InjectionManager: InjectionManager
,08-30 23:10:35.305  9706  9706 D InjectionManager: fillFeatureStoreMap com.samsung.android.scloud
08-30 23:10:35.305  9706  9706 I InjectionManager: Constructor com.samsung.android.scloud, Feature store :{}
08-30 23:10:35.305  9706  9706 I InjectionManager: featureStore :{}
,08-30 23:10:35.305  9706  9706 I [SC]SCloudReceiver: onReceive : android.intent.action.PACKAGE_ADDED
,08-30 23:10:35.315  9729  9729 E Zygote  : v2
08-30 23:10:35.315  9729  9729 I libpersona: KNOX_SDCARD checking this for 1000
08-30 23:10:35.315  9729  9729 I libpersona: KNOX_SDCARD not a persona
08-30 23:10:35.315  9729  9729 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,08-30 23:10:35.315  9729  9729 E Zygote  : accessInfo : 0
08-30 23:10:35.315  3384  4997 I ActivityManager: Start proc 9729:com.samsung.android.bbc.bbcagent/1000 for broadcast-3 com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver
,08-30 23:10:35.315  3384  4997 I ActivityManager: Killing 8979:com.google.android.apps.photos/u0a135 (adj 15): DHA:empty #33
,08-30 23:10:35.335  9729  9729 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 23:10:35.335  9729  9729 D ActivityThread: Added TimaKeyStore provider
,08-30 23:10:35.345  3384  4058 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ae45f40 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{18285dc 9729:com.samsung.android.bbc.bbcagent/1000}
,08-30 23:10:35.355  3384  4315 D ActivityManager: isAutoRunBlockedApp:: com.google.android.apps.photos, Auto Run ON
,08-30 23:10:35.355  9729  9729 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
08-30 23:10:35.355  9729  9729 D RelationGraph: garbageCollect()
,08-30 23:10:35.355  9729  9729 W ResourcesManager: getTopLevelResources: /system/app/BBCAgent/BBCAgent.apk / 1.0 running in com.samsung.android.bbc.bbcagent rsrc of package com.samsung.android.bbc.bbcagent
,08-30 23:10:35.355  3384  4609 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,08-30 23:10:35.355  9729  9729 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,08-30 23:10:35.355  9729  9729 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:35.365  9729  9729 I InjectionManager: Inside getClassLibPath caller 
,08-30 23:10:35.365  9729  9729 W System  : ClassLoader referenced unknown path: /system/app/BBCAgent/lib/arm64
,08-30 23:10:35.375  9729  9729 D InjectionManager: InjectionManager
08-30 23:10:35.375  9729  9729 D InjectionManager: fillFeatureStoreMap com.samsung.android.bbc.bbcagent
,08-30 23:10:35.375  9729  9729 I InjectionManager: Constructor com.samsung.android.bbc.bbcagent, Feature store :{}
08-30 23:10:35.375  9729  9729 I InjectionManager: featureStore :{}
,08-30 23:10:35.385  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:35.395  9741  9741 E Zygote  : v2
,08-30 23:10:35.395  9741  9741 I libpersona: KNOX_SDCARD checking this for 10098
08-30 23:10:35.395  9741  9741 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
08-30 23:10:35.395  9741  9741 I libpersona: KNOX_SDCARD not a persona
08-30 23:10:35.395  9741  9741 E Zygote  : accessInfo : 0
,08-30 23:10:35.395  9741  9741 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.docs 
08-30 23:10:35.395  3384  4407 I ActivityManager: Start proc 9741:com.google.android.apps.docs/u0a98 for broadcast-3 com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,08-30 23:10:35.395  3384  4407 I ActivityManager: Killing 9201:com.sec.android.app.popupuireceiver/1000 (adj 15): DHA:empty #33
,08-30 23:10:35.405  9741  9741 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 23:10:35.405  9741  9741 D ActivityThread: Added TimaKeyStore provider
,08-30 23:10:35.415  3384  4761 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ae45f40 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d8436e5 9741:com.google.android.apps.docs/u0a98}
,08-30 23:10:35.425  3384  4997 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.popupuireceiver, Auto Run ON
,08-30 23:10:35.425  9741  9741 D RelationGraph: garbageCollect()
08-30 23:10:35.425  9741  9741 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,08-30 23:10:35.425  9741  9741 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package com.google.android.apps.docs
,08-30 23:10:35.425  3384  3978 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,08-30 23:10:35.425  9741  9741 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,08-30 23:10:35.435  9741  9741 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:35.435  9741  9741 I InjectionManager: Inside getClassLibPath caller 
,08-30 23:10:35.435  9741  9741 W System  : ClassLoader referenced unknown path: /system/app/Drive/lib/arm64
,08-30 23:10:35.565  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:35.595  9741  9755 I GAv4    : Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
08-30 23:10:35.595  9741  9755 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-30 23:10:35.595  9741  9755 I GAv4    :   adb logcat -s GAv4
,08-30 23:10:35.605  9741  9755 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package com.google.android.apps.docs
,08-30 23:10:35.605  3384  3853 V AlarmManager:  remove PendingIntent] PendingIntent{2c65c61: PendingIntentRecord{2a11386 com.google.android.apps.docs broadcastIntent}}
,08-30 23:10:35.605  9741  9755 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
08-30 23:10:35.605  9741  9755 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
08-30 23:10:35.615  9741  9759 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-30 23:10:35.645  3384  3906 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/37_task.xml.bak
,08-30 23:10:35.655  9741  9741 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.apps.docs/cache/docs_glide
,08-30 23:10:35.665  9741  9755 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db
08-30 23:10:35.665  9741  9755 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-journal
,08-30 23:10:35.665  9741  9755 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-shm
08-30 23:10:35.665  9741  9755 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-wal
,08-30 23:10:35.675  9741  9741 D InjectionManager: InjectionManager
,08-30 23:10:35.675  9741  9741 D InjectionManager: fillFeatureStoreMap com.google.android.apps.docs
08-30 23:10:35.675  9741  9741 I InjectionManager: Constructor com.google.android.apps.docs, Feature store :{}
08-30 23:10:35.675  9741  9741 I InjectionManager: featureStore :{}
,08-30 23:10:35.685  3384  4315 I ActivityManager: Killing 9214:com.sec.android.Kies/1000 (adj 15): DHA:empty #33
,08-30 23:10:35.715  9767  9767 E Zygote  : v2
08-30 23:10:35.715  9767  9767 I libpersona: KNOX_SDCARD checking this for 1000
08-30 23:10:35.715  9767  9767 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
08-30 23:10:35.715  9767  9767 I libpersona: KNOX_SDCARD not a persona
,08-30 23:10:35.715  9767  9767 E Zygote  : accessInfo : 0
,08-30 23:10:35.715  9741  9756 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in com.google.android.apps.docs rsrc of package com.google.android.gms
08-30 23:10:35.715  3384  4250 I ActivityManager: Start proc 9767:com.samsung.android.app.filterinstaller/1000 for broadcast-3 com.samsung.android.app.filterinstaller/.PackageIntentReceiver
,08-30 23:10:35.725  9741  9756 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:35.725  9741  9756 I InjectionManager: Inside getClassLibPath caller 
,08-30 23:10:35.725  3384  4997 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.Kies, Auto Run ON
,08-30 23:10:35.735  9767  9767 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 23:10:35.735  9767  9767 D ActivityThread: Added TimaKeyStore provider
,08-30 23:10:35.745  3384  4473 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ae45f40 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4eae212 9767:com.samsung.android.app.filterinstaller/1000}
,08-30 23:10:35.745  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:35.755  9767  9767 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
08-30 23:10:35.755  9767  9767 D RelationGraph: garbageCollect()
,08-30 23:10:35.755  9767  9767 W ResourcesManager: getTopLevelResources: /system/app/FilterInstaller/FilterInstaller.apk / 1.0 running in com.samsung.android.app.filterinstaller rsrc of package com.samsung.android.app.filterinstaller
,08-30 23:10:35.755  3384  3448 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
08-30 23:10:35.755  9767  9767 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,08-30 23:10:35.755  9767  9767 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:35.755  9741  9756 W System  : ClassLoader referenced unknown path: /system/priv-app/GmsCore/lib/arm64
,08-30 23:10:35.755  9767  9767 I InjectionManager: Inside getClassLibPath caller 
,08-30 23:10:35.765  9767  9767 W System  : ClassLoader referenced unknown path: /system/app/FilterInstaller/lib/arm64
,08-30 23:10:35.765  9767  9767 D InjectionManager: InjectionManager
08-30 23:10:35.765  9767  9767 D InjectionManager: fillFeatureStoreMap com.samsung.android.app.filterinstaller
,08-30 23:10:35.765  9767  9767 I InjectionManager: Constructor com.samsung.android.app.filterinstaller, Feature store :{}
08-30 23:10:35.765  9767  9767 I InjectionManager: featureStore :{}
,08-30 23:10:35.765  9767  9767 E FilterPackageIntentReceiver: This package is not a effect filter
,08-30 23:10:35.775  3384  4473 I ActivityManager: Start proc 9780:com.sec.android.widgetapp.samsungapps/u0a110 for broadcast-3 com.sec.android.widgetapp.samsungapps/.PackageChangeReceiver
,08-30 23:10:35.775  9780  9780 E Zygote  : v2
08-30 23:10:35.775  9780  9780 I libpersona: KNOX_SDCARD checking this for 10110
08-30 23:10:35.775  9780  9780 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
08-30 23:10:35.775  9780  9780 I libpersona: KNOX_SDCARD not a persona
,08-30 23:10:35.775  3384  4473 I ActivityManager: Killing 9227:com.samsung.android.app.simplesharing/5011 (adj 15): DHA:empty #33
08-30 23:10:35.775  9780  9780 E Zygote  : accessInfo : 0
08-30 23:10:35.775  9780  9780 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.sec.android.widgetapp.samsungapps 
,08-30 23:10:35.795  9780  9780 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 23:10:35.795  9780  9780 D ActivityThread: Added TimaKeyStore provider
,08-30 23:10:35.795  3161  3651 V MediaPlayerService: Client(6) destructor pid = 9227
08-30 23:10:35.795  3161  3651 V MediaPlayerService: disconnect(6) from pid 9227
08-30 23:10:35.795  3161  3651 D NuPlayerDriver: reset(0xec682320)
08-30 23:10:35.795  3161  3651 D NuPlayerDriver: notifyListener_l(0xec682320), (8, 0, 0)
08-30 23:10:35.795  3161  9246 V NuPlayer: kWhatReset
08-30 23:10:35.795  3161  9246 V NuPlayer: performReset
08-30 23:10:35.795  3161  9246 V GenericSource: stop()
08-30 23:10:35.795  3161  9246 V GenericSource: PREPARE_CANCELLED set to true
08-30 23:10:35.795  3161  9246 V GenericSource: [Flag] set 0x40 -> mFlags = 0x48
08-30 23:10:35.795  3161  9246 V GenericSource: [Flag] clear 0x8 -> mFlags = 0x40
08-30 23:10:35.795  3161  9246 V GenericSource: stop() end
08-30 23:10:35.795  3161  9246 V GenericSource: ~GenericSource()
08-30 23:10:35.795  3161  9246 I OggExtractor: OggSource::stop() mExtractor ref count = 2
08-30 23:10:35.795  3161  9246 I OggExtractor: ~OggSource --
08-30 23:10:35.795  3161  9246 D NuPlayerDriver: notifyResetComplete(0xec682320)
,08-30 23:10:35.795  3161  3651 V NuPlayerDriver: ~NuPlayerDriver(0xec682320)
08-30 23:10:35.795  3161  3651 I OggExtractor: ~OggExtractor ++
08-30 23:10:35.795  3161  3651 I OggExtractor: ~MyOggExtractor ++ 
08-30 23:10:35.795  3161  3651 I OggExtractor: ~MyOggExtractor --
,08-30 23:10:35.795  3161  3651 I OggExtractor: ~OggExtractor --
08-30 23:10:35.795  3161  3651 V AudioSink: +++ close
08-30 23:10:35.795  3161  3651 V AudioSink: --- close
,08-30 23:10:35.805  3384  4609 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ae45f40 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4cfede3 9780:com.sec.android.widgetapp.samsungapps/u0a110}
,08-30 23:10:35.815  3384  4761 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.simplesharing, Auto Run ON
,08-30 23:10:35.815  9780  9780 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
08-30 23:10:35.815  9780  9780 D RelationGraph: garbageCollect()
,08-30 23:10:35.815  9780  9780 W ResourcesManager: getTopLevelResources: /system/app/GalaxyAppsWidget_Phone_Hero/GalaxyAppsWidget_Phone_Hero.apk / 1.0 running in com.sec.android.widgetapp.samsungapps rsrc of package com.sec.android.widgetapp.samsungapps
,08-30 23:10:35.815  3384  4997 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
08-30 23:10:35.815  9780  9780 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,08-30 23:10:35.815  9780  9780 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:35.815  9780  9780 I InjectionManager: Inside getClassLibPath caller 
,08-30 23:10:35.825  9780  9780 W System  : ClassLoader referenced unknown path: /system/app/GalaxyAppsWidget_Phone_Hero/lib/arm64
,08-30 23:10:35.825  9741  9756 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-30 23:10:35.825  9780  9780 D InjectionManager: InjectionManager
08-30 23:10:35.825  9780  9780 D InjectionManager: fillFeatureStoreMap com.sec.android.widgetapp.samsungapps
,08-30 23:10:35.835  9780  9780 I InjectionManager: Constructor com.sec.android.widgetapp.samsungapps, Feature store :{}
08-30 23:10:35.835  9780  9780 I InjectionManager: featureStore :{}
,08-30 23:10:35.835  9741  9756 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-30 23:10:35.845  9793  9793 E Zygote  : v2
08-30 23:10:35.845  9793  9793 I libpersona: KNOX_SDCARD checking this for 10111
08-30 23:10:35.845  9793  9793 I libpersona: KNOX_SDCARD not a persona
08-30 23:10:35.845  9793  9793 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,08-30 23:10:35.845  9793  9793 E Zygote  : accessInfo : 0
08-30 23:10:35.845  9793  9793 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.enhance.gameservice 
,08-30 23:10:35.845  3384  3853 I ActivityManager: Start proc 9793:com.enhance.gameservice/u0a111 for broadcast-3 com.enhance.gameservice/.GameServiceReceiver
,08-30 23:10:35.845  3384  3853 I ActivityManager: Killing 9188:com.samsung.android.app.assistantmenu/1000 (adj 15): DHA:empty #33
,08-30 23:10:35.855  9793  9793 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 23:10:35.855  9793  9793 D ActivityThread: Added TimaKeyStore provider
,08-30 23:10:35.865  3384  4997 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.assistantmenu, Auto Run ON
,08-30 23:10:35.875  3384  3449 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ae45f40 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{795a3e0 9793:com.enhance.gameservice/u0a111}
,08-30 23:10:35.885  9793  9793 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
08-30 23:10:35.885  9793  9793 D RelationGraph: garbageCollect()
,08-30 23:10:35.885  9793  9793 W ResourcesManager: getTopLevelResources: /system/app/GameOptimizer/GameOptimizer.apk / 1.0 running in com.enhance.gameservice rsrc of package com.enhance.gameservice
,08-30 23:10:35.885  3384  3853 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
08-30 23:10:35.885  9793  9793 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,08-30 23:10:35.885  9793  9793 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:35.905  9793  9793 I InjectionManager: Inside getClassLibPath caller 
,08-30 23:10:35.905  9793  9793 W System  : ClassLoader referenced unknown path: /system/app/GameOptimizer/lib/arm64
,08-30 23:10:35.905  9793  9793 D InjectionManager: InjectionManager
,08-30 23:10:35.905  9793  9793 D InjectionManager: fillFeatureStoreMap com.enhance.gameservice
08-30 23:10:35.905  9793  9793 I InjectionManager: Constructor com.enhance.gameservice, Feature store :{}
08-30 23:10:35.905  9793  9793 I InjectionManager: featureStore :{}
,08-30 23:10:35.915  9793  9805 I DatabaseHelper: android.app.Application@2262ea9
,08-30 23:10:35.915  9793  9805 I DatabaseHelper: Create a DatabaseHelper
,08-30 23:10:35.925  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:35.925  9793  9805 W RequestHeader: java.lang.StringIndexOutOfBoundsException: length=0; regionStart=0; regionLength=3
,08-30 23:10:35.925  9807  9807 E Zygote  : v2
08-30 23:10:35.925  9807  9807 I libpersona: KNOX_SDCARD checking this for 1000
08-30 23:10:35.925  9807  9807 I libpersona: KNOX_SDCARD not a persona
08-30 23:10:35.935  9807  9807 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,08-30 23:10:35.935  9807  9807 E Zygote  : accessInfo : 0
,08-30 23:10:35.935  3384  3978 I ActivityManager: Start proc 9807:com.samsung.android.app.mirrorlink/1000 for broadcast-3 com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener
,08-30 23:10:35.935  9793  9805 I DataManager: checkResolution
08-30 23:10:35.935  9793  9805 I DataManager: Create a DataManager
,08-30 23:10:35.945  9793  9805 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-30 23:10:35.945  9793  9805 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 23:10:35.945  3153  3636 D EnterpriseController: netId is 0
,08-30 23:10:35.945  3153  3636 D Netd    : getNetworkForDns: using netid 502 for uid 10111
,08-30 23:10:35.955  9807  9807 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 23:10:35.955  9807  9807 D ActivityThread: Added TimaKeyStore provider
,08-30 23:10:35.965  3384  4407 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ae45f40 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8910d5e 9807:com.samsung.android.app.mirrorlink/1000}
,08-30 23:10:35.965  9807  9807 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
08-30 23:10:35.965  9807  9807 D RelationGraph: garbageCollect()
,08-30 23:10:35.975  9807  9807 W ResourcesManager: getTopLevelResources: /system/app/MirrorLink/MirrorLink.apk / 1.0 running in com.samsung.android.app.mirrorlink rsrc of package com.samsung.android.app.mirrorlink
,08-30 23:10:35.975  3384  4761 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,08-30 23:10:35.975  9807  9807 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,08-30 23:10:35.975  9807  9807 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:35.975  9807  9807 I InjectionManager: Inside getClassLibPath caller 
,08-30 23:10:35.985  9807  9807 W System  : ClassLoader referenced unknown path: /system/app/MirrorLink/lib/arm
,08-30 23:10:36.005  9807  9807 D InjectionManager: InjectionManager
,08-30 23:10:36.005  9807  9807 D InjectionManager: fillFeatureStoreMap com.samsung.android.app.mirrorlink
08-30 23:10:36.005  9807  9807 I InjectionManager: Constructor com.samsung.android.app.mirrorlink, Feature store :{}
08-30 23:10:36.005  9807  9807 I InjectionManager: featureStore :{}
08-30 23:10:36.005  9807  9807 D AcmsPackageEventListener: action2:android.intent.action.PACKAGE_ADDED
,08-30 23:10:36.005  9807  9807 D AcmsPackageEventListener: pkgName:com.test.thalitest ,10177
,08-30 23:10:36.005  3384  4407 I ActivityManager: Killing 9276:com.android.calendar/u0a144 (adj 15): DHA:empty #33
,08-30 23:10:36.015  3384  4407 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ae45f40 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{78e2196 4904:com.microsoft.skydrive/u0a130}
,08-30 23:10:36.025  4904  4904 V ApplicationReceiver: 2016-08-30 21:10:36-null-Application install message is received ver:1.1.10
,08-30 23:10:36.025  4904  4904 V ApplicationReceiver: 2016-08-30 21:10:36-null-Installing:package:com.test.thalitest ver:1.1.10
,08-30 23:10:36.035  9820  9820 E Zygote  : v2
08-30 23:10:36.035  9820  9820 I libpersona: KNOX_SDCARD checking this for 10141
08-30 23:10:36.035  9820  9820 E Zygote  : isSdpEnabledProcess - SDP enabled
08-30 23:10:36.035  9820  9820 I libpersona: KNOX_SDCARD not a persona
08-30 23:10:36.035  9820  9820 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,08-30 23:10:36.045  3384  3853 I ActivityManager: Start proc 9820:com.sec.android.app.sbrowser/u0a141 for broadcast-3 com.sec.android.app.sbrowser/.preferences.ContentBlockerReceiver
,08-30 23:10:36.045  9820  9820 E Zygote  : accessInfo : 64
08-30 23:10:36.045  9820  9820 E Zygote  : isSdpEnabledProcess - SDP enabled
08-30 23:10:36.045  9820  9820 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10141 / [uid]: 10141
08-30 23:10:36.045  9820  9820 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.sbrowser 
,08-30 23:10:36.055  3384  4315 D ActivityManager: isAutoRunBlockedApp:: com.android.calendar, Auto Run ON
,08-30 23:10:36.055  9820  9820 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 23:10:36.055  9820  9820 D ActivityThread: Added TimaKeyStore provider
,08-30 23:10:36.065  4219  9662 D FusedRequestManager: manageLocationRequest, new fused (NO_POWER) request from com.samsung.voiceserviceplatform with 10043_NOPOWER through GooglePlayService
,08-30 23:10:36.075  3384  4997 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ae45f40 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c89853f 9820:com.sec.android.app.sbrowser/u0a141}
,08-30 23:10:36.085  9820  9820 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
08-30 23:10:36.085  9820  9820 D RelationGraph: garbageCollect()
,08-30 23:10:36.085  9820  9820 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package com.sec.android.app.sbrowser
,08-30 23:10:36.085  3384  4313 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,08-30 23:10:36.085  9820  9820 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,08-30 23:10:36.085  9820  9820 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:36.085  9820  9820 I InjectionManager: Inside getClassLibPath caller 
,08-30 23:10:36.095  9820  9820 W System  : ClassLoader referenced unknown path: /system/app/SBrowser_4_LATEST/lib/arm
,08-30 23:10:36.105  9820  9820 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package com.sec.android.app.sbrowser
,08-30 23:10:36.105  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:36.105  9820  9820 D ManifestProvider: onCreate()
,08-30 23:10:36.115  9820  9820 I SBrowserUtils: getSystemProperty of sales_code : XEO
,08-30 23:10:36.115  9820  9820 I SBrowserUtils: getSystemProperty of country_code : Poland
08-30 23:10:36.115  9820  9820 I SBrowserUtils: getSystemProperty of country_code : Poland
08-30 23:10:36.115  9820  9820 I SBrowserUtils: getSystemProperty of countryiso_code : PL
,08-30 23:10:36.115  9820  9820 V SBrowserContentProviderUtility: enableSyncClientProivder is called!
,08-30 23:10:36.115  9820  9820 D [MM]MHDataBaseProvider: onCreate()
,08-30 23:10:36.135  9820  9820 D ApplicationStatus: initialize application (com.sec.android.app.sbrowser.common.SBrowserMobileApplication@27ef03a)
,08-30 23:10:36.135  9820  9820 D InjectionManager: InjectionManager
,08-30 23:10:36.135  9820  9820 D InjectionManager: fillFeatureStoreMap com.sec.android.app.sbrowser
08-30 23:10:36.135  9820  9820 I InjectionManager: Constructor com.sec.android.app.sbrowser, Feature store :{}
08-30 23:10:36.135  9820  9820 I InjectionManager: featureStore :{}
,08-30 23:10:36.145  3384  4473 I ActivityManager: Killing 9045:com.samsung.faceservice/5004 (adj 15): DHA:empty #33
,08-30 23:10:36.145  3384  4473 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ae45f40 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e9e426a 5081:com.sec.imsservice/1000}
,08-30 23:10:36.165  8534  8534 I ServiceManager: [#CMH#] Disconnected to Service  com.samsung.faceservice.FaceService
,08-30 23:10:36.185  9836  9836 E Zygote  : v2
08-30 23:10:36.185  9836  9836 I libpersona: KNOX_SDCARD checking this for 10016
08-30 23:10:36.185  9836  9836 I libpersona: KNOX_SDCARD not a persona
08-30 23:10:36.185  9836  9836 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,08-30 23:10:36.185  9836  9836 E Zygote  : accessInfo : 0
08-30 23:10:36.185  9836  9836 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.sec.android.app.samsungapps 
,08-30 23:10:36.185  3384  4473 I ActivityManager: Start proc 9836:com.sec.android.app.samsungapps/u0a16 for broadcast-3 com.sec.android.app.samsungapps/.MyPackageReplacedReceiver
,08-30 23:10:36.205  3384  4313 D ActivityManager: isAutoRunBlockedApp:: com.samsung.faceservice, Auto Run ON
,08-30 23:10:36.205  3384  4313 W ActivityManager: Scheduling restart of crashed service com.samsung.faceservice/.FaceService in 1000ms
08-30 23:10:36.205  9836  9836 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 23:10:36.205  9836  9836 D ActivityThread: Added TimaKeyStore provider
,08-30 23:10:36.215  3384  4315 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ae45f40 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ae11e0c 9836:com.sec.android.app.samsungapps/u0a16}
,08-30 23:10:36.225  9836  9836 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
08-30 23:10:36.225  9836  9836 D RelationGraph: garbageCollect()
,08-30 23:10:36.225  9836  9836 W ResourcesManager: getTopLevelResources: /data/app/com.sec.android.app.samsungapps-1/base.apk / 1.0 running in com.sec.android.app.samsungapps rsrc of package com.sec.android.app.samsungapps
,08-30 23:10:36.235  3384  3448 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,08-30 23:10:36.235  9836  9836 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
08-30 23:10:36.235  4612  7728 I Icing   : Indexing 5C970AF099F6E45AC5F7CE88D00EDBB4B63BF8D6 from com.google.android.googlequicksearchbox
,08-30 23:10:36.235  9836  9836 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:36.235  9836  9836 I InjectionManager: Inside getClassLibPath caller 
,08-30 23:10:36.245  9836  9836 W System  : ClassLoader referenced unknown path: /data/app/com.sec.android.app.samsungapps-1/lib/arm64
,08-30 23:10:36.255  9836  9836 D InjectionManager: InjectionManager
08-30 23:10:36.255  9836  9836 D InjectionManager: fillFeatureStoreMap com.sec.android.app.samsungapps
,08-30 23:10:36.255  9836  9836 I InjectionManager: Constructor com.sec.android.app.samsungapps, Feature store :{}
08-30 23:10:36.255  9836  9836 I InjectionManager: featureStore :{}
,08-30 23:10:36.275  9849  9849 E Zygote  : v2
08-30 23:10:36.275  9849  9849 I libpersona: KNOX_SDCARD checking this for 10103
08-30 23:10:36.275  9849  9849 I libpersona: KNOX_SDCARD not a persona
08-30 23:10:36.275  9849  9849 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,08-30 23:10:36.275  9849  9849 E Zygote  : accessInfo : 0
,08-30 23:10:36.275  9849  9849 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.facebook.appmanager 
,08-30 23:10:36.275  3384  3449 I ActivityManager: Start proc 9849:com.facebook.appmanager/u0a103 for broadcast-3 com.facebook.appmanager/com.facebook.oxygen.appmanager.common.packages.PackageReceiver
,08-30 23:10:36.275  3384  3449 I ActivityManager: Killing 8559:com.samsung.enhanceservice/5004 (adj 15): DHA:empty #33
,08-30 23:10:36.285  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:36.295  9849  9849 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 23:10:36.295  9849  9849 D ActivityThread: Added TimaKeyStore provider
,08-30 23:10:36.295  8534  8534 I ServiceManager: [#CMH#] Disconnected to Service  com.samsung.enhanceservice.EnhanceService
,08-30 23:10:36.305  3384  3448 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ae45f40 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{249a355 9849:com.facebook.appmanager/u0a103}
,08-30 23:10:36.305  3384  4997 D ActivityManager: isAutoRunBlockedApp:: com.samsung.enhanceservice, Auto Run ON
08-30 23:10:36.305  9849  9849 D RelationGraph: garbageCollect()
08-30 23:10:36.305  9849  9849 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
08-30 23:10:36.305  3384  4997 W ActivityManager: Scheduling restart of crashed service com.samsung.enhanceservice/.EnhanceService in 10893ms
,08-30 23:10:36.315  9849  9849 W ResourcesManager: getTopLevelResources: /data/app/com.facebook.appmanager-1/base.apk / 1.0 running in com.facebook.appmanager rsrc of package com.facebook.appmanager
,08-30 23:10:36.315  3384  3449 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
08-30 23:10:36.315  9849  9849 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,08-30 23:10:36.315  9849  9849 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:36.315  9849  9849 I InjectionManager: Inside getClassLibPath caller 
08-30 23:10:36.315  3384  6471 D GameManagerService: identifyGamePackage. com.test.thalitest
,08-30 23:10:36.335  9849  9849 D ACRA    : ACRA init; reportURL: https://www.facebook.com/mobile/generic_android_crash_logs/659091980805095
,08-30 23:10:36.335  9849  9849 D ACRA    : ACRA is enabled for com.facebook.appmanager, intializing...
,08-30 23:10:36.335  9849  9849 V fb-UnpackingSoSource: locked dso store /data/user/0/com.facebook.appmanager/lib-main
,08-30 23:10:36.335  9849  9849 I fb-UnpackingSoSource: dso store is up-to-date: /data/user/0/com.facebook.appmanager/lib-main
08-30 23:10:36.335  9849  9849 V fb-UnpackingSoSource: releasing dso store lock for /data/user/0/com.facebook.appmanager/lib-main
,08-30 23:10:36.345  4612  7728 I Icing   : Indexing done 5C970AF099F6E45AC5F7CE88D00EDBB4B63BF8D6
,08-30 23:10:36.355  9849  9849 W com.facebook.appmanager:co: Verify
,08-30 23:10:36.365  9849  9849 D InjectionManager: InjectionManager
08-30 23:10:36.365  9849  9849 D InjectionManager: fillFeatureStoreMap com.facebook.appmanager
,08-30 23:10:36.365  9849  9849 I InjectionManager: Constructor com.facebook.appmanager, Feature store :{}
08-30 23:10:36.365  9849  9849 I InjectionManager: featureStore :{}
,08-30 23:10:36.395  9865  9865 E Zygote  : v2
08-30 23:10:36.395  9865  9865 I libpersona: KNOX_SDCARD checking this for 10014
08-30 23:10:36.395  9865  9865 I libpersona: KNOX_SDCARD not a persona
08-30 23:10:36.395  9865  9865 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,08-30 23:10:36.395  9865  9865 E Zygote  : accessInfo : 0
08-30 23:10:36.395  9865  9865 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.facebook.system 
,08-30 23:10:36.395  3384  4997 I ActivityManager: Start proc 9865:com.facebook.system/u0a14 for broadcast-3 com.facebook.system/com.facebook.oxygen.installer.service.PackageReceiver
,08-30 23:10:36.415  9865  9865 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 23:10:36.415  9865  9865 D ActivityThread: Added TimaKeyStore provider
,08-30 23:10:36.425  3384  3448 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ae45f40 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e4cdd37 9865:com.facebook.system/u0a14}
,08-30 23:10:36.435  9865  9865 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
08-30 23:10:36.435  9865  9865 D RelationGraph: garbageCollect()
,08-30 23:10:36.435  3384  4997 D PackageManager: setEnabledSetting : userId = 0 packageName = com.facebook.appmanager cmp = com.facebook.oxygen.appmanager.crashmanager.CrashManagerActivity newState = 2 callingPackage = 10103
08-30 23:10:36.435  9865  9865 W ResourcesManager: getTopLevelResources: /data/app/com.facebook.system-1/base.apk / 1.0 running in com.facebook.system rsrc of package com.facebook.system
,08-30 23:10:36.435  3384  4473 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
08-30 23:10:36.435  9865  9865 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,08-30 23:10:36.435  9865  9865 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:36.445  3384  4315 D PackageManager: setEnabledSetting : userId = 0 packageName = com.facebook.appmanager cmp = com.facebook.oxygen.appmanager.firstparty.tos.ShouldShowTos newState = 2 callingPackage = 10103
,08-30 23:10:36.445  9865  9865 I InjectionManager: Inside getClassLibPath caller 
,08-30 23:10:36.445  3384  4058 D PackageManager: setEnabledSetting : userId = 0 packageName = com.facebook.appmanager cmp = com.facebook.oxygen.appmanager.nekodirect.NekoDirectService newState = 2 callingPackage = 10103
,08-30 23:10:36.445  9865  9865 W System  : ClassLoader referenced unknown path: /data/app/com.facebook.system-1/lib/arm64
,08-30 23:10:36.455  3384  3853 D PackageManager: setEnabledSetting : userId = 0 packageName = com.facebook.appmanager cmp = com.facebook.oxygen.appmanager.nekodirect.progress.ProgressContentProvider newState = 2 callingPackage = 10103
,08-30 23:10:36.455  9865  9865 D InjectionManager: InjectionManager
08-30 23:10:36.455  9865  9865 D InjectionManager: fillFeatureStoreMap com.facebook.system
,08-30 23:10:36.455  9865  9865 I InjectionManager: Constructor com.facebook.system, Feature store :{}
08-30 23:10:36.455  9865  9865 I InjectionManager: featureStore :{}
,08-30 23:10:36.465  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:36.465  9885  9885 E Zygote  : v2
08-30 23:10:36.465  9885  9885 I libpersona: KNOX_SDCARD checking this for 10039
08-30 23:10:36.465  9885  9885 I libpersona: KNOX_SDCARD not a persona
08-30 23:10:36.465  9885  9885 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,08-30 23:10:36.465  9885  9885 E Zygote  : accessInfo : 0
08-30 23:10:36.465  9885  9885 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.sec.android.app.shealth 
,08-30 23:10:36.465  3384  4609 I ActivityManager: Start proc 9885:com.sec.android.app.shealth/u0a39 for broadcast-3 com.sec.android.app.shealth/com.samsung.android.app.shealth.serviceframework.partner.PluginBroadcastReceiver
,08-30 23:10:36.465  3384  4609 I ActivityManager: Killing 8571:com.samsung.dcmservice/5004 (adj 15): DHA:empty #33
,08-30 23:10:36.475  9849  9881 E ActivityThread: Failed to find provider info for com.facebook.appmanager.oxygen.nekodirect.progress
,08-30 23:10:36.475  3384  4473 I ActivityManager: Killing 9021:com.samsung.ipservice/5004 (adj 15): DHA:empty #33
,08-30 23:10:36.485  8534  8534 I ServiceManager: [#CMH#] Disconnected to Service  com.samsung.dcmservice.DCMService
,08-30 23:10:36.485  9885  9885 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 23:10:36.485  9885  9885 D ActivityThread: Added TimaKeyStore provider
,08-30 23:10:36.495  8534  8534 I ServiceManager: [#CMH#] Disconnected to Service  com.samsung.ipservice.IPService
,08-30 23:10:36.495  3384  3449 D ActivityManager: isAutoRunBlockedApp:: com.samsung.dcmservice, Auto Run ON
08-30 23:10:36.495  3384  3449 W ActivityManager: Scheduling restart of crashed service com.samsung.dcmservice/.DCMService in 20709ms
,08-30 23:10:36.515  3384  4609 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1ab22a4 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{943e80d 9885:com.sec.android.app.shealth/u0a39}
,08-30 23:10:36.515  3384  4313 D ActivityManager: isAutoRunBlockedApp:: com.samsung.ipservice, Auto Run ON
08-30 23:10:36.515  3384  4313 W ActivityManager: Scheduling restart of crashed service com.samsung.ipservice/.IPService in 30686ms
,08-30 23:10:36.515  9885  9885 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
08-30 23:10:36.515  9885  9885 D RelationGraph: garbageCollect()
08-30 23:10:36.515  9885  9885 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.sec.android.app.shealth rsrc of package com.sec.android.app.shealth
,08-30 23:10:36.525  3384  3978 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,08-30 23:10:36.525  9885  9885 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,08-30 23:10:36.525  3384  3448 I ActivityManager: Killing 8534:com.samsung.cmh:CMH/5004 (adj 15): DHA:empty #33
,08-30 23:10:36.525  9885  9885 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:36.535  9885  9885 I InjectionManager: Inside getClassLibPath caller 
,08-30 23:10:36.545  9885  9885 W System  : ClassLoader referenced unknown path: /system/priv-app/SHealth4/lib/arm64
08-30 23:10:36.545  3384  3978 E GameManagerService: remoteCallback died, callback: com.samsung.android.game.IGameManagerCallback$Stub$Proxy@9abf3c2, cookie: null
,08-30 23:10:36.555  9885  9885 I MultiDex: VM with version 2.1.0 has multidex support
08-30 23:10:36.555  9885  9885 I MultiDex: install
08-30 23:10:36.555  9885  9885 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-30 23:10:36.555  9885  9885 I MultiDex: install
08-30 23:10:36.555  9885  9885 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-30 23:10:36.555  3384  4058 D ActivityManager: isAutoRunBlockedApp:: com.samsung.cmh, Auto Run ON
,08-30 23:10:36.555  9885  9885 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.sec.android.app.shealth rsrc of package com.sec.android.app.shealth
,08-30 23:10:36.555  8611  8611 I StoryService: [StoryService] On destroy() 
08-30 23:10:36.555  8611  8611 I ServiceController: [StoryService] shutdown() 
,08-30 23:10:36.605  9885  9885 D InjectionManager: InjectionManager
08-30 23:10:36.605  9885  9885 D InjectionManager: fillFeatureStoreMap com.sec.android.app.shealth
08-30 23:10:36.605  9885  9885 I InjectionManager: Constructor com.sec.android.app.shealth, Feature store :{}
08-30 23:10:36.605  9885  9885 I InjectionManager: featureStore :{}
,08-30 23:10:36.605  9885  9885 D HealthDataStore: Service for HealthDataStore is connected
08-30 23:10:36.605  3384  6511 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-30 23:10:36.605  9885  9885 D HealthDataStore: HealthConnectionErrorResult code : 9
,08-30 23:10:36.615  3384  4323 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1ab22a4 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e9cf9d 9098:com.sec.android.app.shealth:remote/u0a39}
,08-30 23:10:36.615  9885  9885 D HealthConsole: Service for HealthDataConsole is connected
,08-30 23:10:36.625  9885  9885 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
,08-30 23:10:36.625  9885  9885 E HealthDataStore: disconnectService: Context instance is invalid
,08-30 23:10:36.625  3384  4315 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1ab22a4 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e9cf9d 9098:com.sec.android.app.shealth:remote/u0a39}
,08-30 23:10:36.635  3384  4315 I ActivityManager: Killing 8103:com.android.providers.calendar/u0a50 (adj 15): DHA:empty #33
,08-30 23:10:36.645  3384  4315 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{218391a u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{aee70da 5068:com.samsung.android.providers.context/u0a9}
,08-30 23:10:36.645  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:36.655  3384  4058 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9d26c4b u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{aee70da 5068:com.samsung.android.providers.context/u0a9}
,08-30 23:10:36.665  3384  4634 D ActivityManager: isAutoRunBlockedApp:: com.android.providers.calendar, Auto Run ON
,08-30 23:10:36.825  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:37.005  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:37.185  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:37.365  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:37.395  3384  5107 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
,08-30 23:10:37.395  3384  5107 V MARsPolicyManager: updateSMDBValues
,08-30 23:10:37.395  3384  3538 E MARsDBManager: updateDBAll : begin --size 1
,08-30 23:10:37.425  3384  3538 E MARsDBManager: updateDBAll : end
,08-30 23:10:37.425  3384  3538 D MARsDBManager: onChange - mSmartManagerObserver! Uri = content://com.samsung.android.sm/AppFreezer?MARs-self=true&MARs=true
,08-30 23:10:37.545  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:37.725  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:37.905  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:38.085  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:38.265  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:38.445  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:38.625  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:38.655  9548  9554 I eN66    : JNI Enter Function Java_com_asr_pocketsphinx_pocketsphinxJNI_delete_1Config
08-30 23:10:38.655  9548  9554 I eN66    : JNI Exit Function Java_com_asr_pocketsphinx_pocketsphinxJNI_delete_1Config
,08-30 23:10:38.805  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:38.985  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:39.055  9601  9608 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+user+0+com_samsung_svoice_sync+databases+svoicelocal_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,08-30 23:10:39.165  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:39.345  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:39.385  3384  6471 D N       : limitCPUFreq:: freq = 2496000
08-30 23:10:39.385  3384  6471 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MAX_LIMIT  frequency : 2496000  uid : 1000  pid : 3384  pkgName : SIOP_ARM_MAX@22
,08-30 23:10:39.385  3384  6471 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-30 23:10:39.525  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:39.705  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:39.885  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:40.065  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:40.245  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:40.425  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:40.605  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:40.785  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:40.965  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:41.145  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:41.325  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:41.505  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:41.505  9509  9663 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-30 23:10:41.505  9509  9663 I jxcore-log: 
,08-30 23:10:41.505  9509  9663 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-30 23:10:41.505  9509  9663 I jxcore-log: 
,08-30 23:10:41.515  9509  9663 D BluetoothAdapter: STATE_ON
,08-30 23:10:41.515  9509  9663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 23:10:41.515  9509  9663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 23:10:41.515  9509  9663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 23:10:41.515  9509  9663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 23:10:41.515  9509  9663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 23:10:41.515  9509  9663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 23:10:41.515  9509  9663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 23:10:41.515  9509  9663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 23:10:41.515  9509  9663 D BluetoothAdapter: STATE_ON
,08-30 23:10:41.525  9509  9663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 23:10:41.525  9509  9663 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 23:10:41.525  9509  9663 I jxcore-log: 
,08-30 23:10:41.525  9509  9663 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 23:10:41.525  9509  9663 I jxcore-log: 
,08-30 23:10:41.615  3384  6511 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-30 23:10:41.675  9509  9663 I jxcore-log: Running unit tests
08-30 23:10:41.675  9509  9663 I jxcore-log: 
,08-30 23:10:41.675  9509  9663 E JX-Cordova: JavaCall recevied a call for unknown method ExecuteNativeTests
08-30 23:10:41.675  9509  9663 I jxcore-log: Failed to execute UT.
08-30 23:10:41.675  9509  9663 I jxcore-log: 
08-30 23:10:41.675  9509  9663 I jxcore-log: Unit Test app is loaded
08-30 23:10:41.675  9509  9663 I jxcore-log: 
,08-30 23:10:41.675  9509  9663 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 23:10:41.675  9509  9663 I jxcore-log: 
,08-30 23:10:41.685  9509  9663 I jxcore-log: My device name is: samsung-SM-G935F
08-30 23:10:41.685  9509  9663 I jxcore-log: 
,08-30 23:10:41.685  9509  9663 I jxcore-log: WARN testUtils: myNameCallback not set!
08-30 23:10:41.685  9509  9663 I jxcore-log: 
,08-30 23:10:41.685  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:41.695  9509  9509 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-30 23:10:41.865  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:42.045  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:42.225  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:42.405  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:42.585  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:42.605  3384  6471 D SSRM:n  : SIOP:: AP = 440, PST = 441 (W:8), CP = 306, CUR = -150, LCD = 1
,08-30 23:10:42.615  3384  6471 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-30 23:10:42.685  3384  3569 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-30 23:10:42.695  3384  3569 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-30 23:10:42.735  9509  9663 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-30 23:10:42.735  9509  9663 I jxcore-log: 
,08-30 23:10:42.765  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:42.845  3384  3853 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-30 23:10:42.845  3384  3853 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4325, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
08-30 23:10:42.845  3384  3853 D BatteryService: online:4, current avg:-191, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-175
08-30 23:10:42.845  3384  3853 D BatteryService: stay LED for fully charged
,08-30 23:10:42.845  3384  3384 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-30 23:10:42.845  3384  3384 I MotionRecognitionService: Plugged
,08-30 23:10:42.845  3384  3384 D MotionRecognitionService:   cableConnection= 1
08-30 23:10:42.845  3384  3384 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-30 23:10:42.845  3384  3384 D MotionRecognitionService: skip setTransmitPower. 
,08-30 23:10:42.855  3384  3861 D WifiController: ApOrStaEnabledState  msg.what= 155652
,08-30 23:10:42.855  3938  3938 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-30 23:10:42.855  3938  3938 D PowerUI : priorPlugType = 2 mPlugType =  2
08-30 23:10:42.855  3938  3938 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-30 23:10:42.865  5081  5081 D CommonServiceConfiguration: getStringValueSetting
,08-30 23:10:42.875  5039  5039 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-30 23:10:42.875  5039  5435 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-30 23:10:42.875  5081  5081 D BatteryMonitor: new battery level: 100
08-30 23:10:42.875  4718  4718 D BatteryController: saveBatteryData : level[100], status[5]
,08-30 23:10:42.905  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-30 23:10:42.905  3938  3938 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-30 23:10:42.935  9509  9663 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-30 23:10:42.935  9509  9663 I jxcore-log: 
,08-30 23:10:42.945  9509  9663 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-30 23:10:42.945  9509  9663 I jxcore-log: 
,08-30 23:10:42.945  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:43.125  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:43.305  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:43.485  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:43.545  9509  9663 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-30 23:10:43.545  9509  9663 I jxcore-log: 
,08-30 23:10:43.645  9509  9663 I jxcore-log: ERROR runTests: 
08-30 23:10:43.645  9509  9663 I jxcore-log: 
,08-30 23:10:43.645  9509  9663 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-30 23:10:43.645  9509  9663 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"38","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
08-30 23:10:43.645  9509  9663 I jxcore-log: WARN testUtils: logCallback not set!
08-30 23:10:43.645  9509  9663 I jxcore-log: 
,08-30 23:10:43.655  9509  9663 I jxcore-log: [ { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 23:10:43.655  9509  9663 I jxcore-log:     _functionName: 'loadFile',
08-30 23:10:43.655  9509  9663 I jxcore-log:     _lineNumber: '26',
08-30 23:10:43.655  9509  9663 I jxcore-log:     _columnNumber: '11',
08-30 23:10:43.655  9509  9663 I jxcore-log:     _msg: '    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11' },
08-30 23:10:43.655  9509  9663 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 23:10:43.655  9509  9663 I jxcore-log:     _functionName: '',
08-30 23:10:43.655  9509  9663 I jxcore-log:     _lineNumber: '38',
08-30 23:10:43.655  9509  9663 I jxcore-log:     _columnNumber: '7',
08-30 23:10:43.655  9509  9663 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7' },
08-30 23:10:43.655  9509  9663 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 23:10:43.655  9509  9663 I jxcore-log:     _functionName: '',
08-30 23:10:43.655  9509  9663 I jxcore-log:     _lineNumber: '35',
08-30 23:10:43.655  9509  9663 I jxcore-log:     _columnNumber: '3',
08-30 23:10:43.655  9509  9663 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3' },
08-30 23:10:43.655  9509  9663 I jxcore-log:   { _fileName: 'module.js',
08-30 23:10:43.655  9509  9663 I jxcore-log:     _functionName: '$w.prototype._compile',
08-30 23:10:43.655  9509  9663 I jxcore-log:     _lineNumber: '621',
08-30 23:10:43.655  9509  9663 I jxcore-log:     _columnNumber: '8',
08-30 23:10:43.655  9509  9663 I jxcore-log:     _msg: '    at $w.prototype._compile@module.js:621:8' },
08-30 23:10:43.655  9509  9663 I jxcore-log:   { _fileName: 'module.js',
08-30 23:10:43.655  9509  9663 I jxcore-log:     _functionName: '$w._extensions[".js"]',
08-30 23:10:43.655  9509  9663 I jxcore-log:     _lineNumber: '651',
08-30 23:10:43.655  9509  9663 I jxcore-log:     _columnNumber: '1',
08-30 23:10:43.655  9509  9663 I jxcore-log:    
,08-30 23:10:43.655  9509  9663 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-30 23:10:43.655  9509  9663 I jxcore-log: 
08-30 23:10:43.655  9509  9663 E jxcore-log: Error: 
08-30 23:10:43.655  9509  9663 E jxcore-log: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-30 23:10:43.655  9509  9663 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/runTests.js 26:11)
,08-30 23:10:43.655  9509  9663 E jxcore-log: 
08-30 23:10:43.665  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:43.845  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:44.025  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:44.125  9911  9911 I FIPS_bssl: FIPS approved mode (1) | 9911 | app_process
,08-30 23:10:44.135  9911  9911 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-30 23:10:44.135  9911  9911 D AndroidRuntime: CheckJNI is OFF
08-30 23:10:44.135  9911  9911 D AndroidRuntime: readGMSProperty: start
08-30 23:10:44.135  9911  9911 D AndroidRuntime: readGMSProperty: already setted!!
08-30 23:10:44.135  9911  9911 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-30 23:10:44.135  9911  9911 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-30 23:10:44.135  9911  9911 D AndroidRuntime: readGMSProperty: end
08-30 23:10:44.135  9911  9911 D AndroidRuntime: addProductProperty: start
,08-30 23:10:44.155  9911  9911 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-30 23:10:44.175  9911  9911 I Radio-JNI: register_android_hardware_Radio DONE
,08-30 23:10:44.175  9911  9911 E AffinityControl: AffinityControl: registerfunction enter
,08-30 23:10:44.185  9911  9911 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-30 23:10:44.195  3384  3853 D PackageManager: START PACKAGE DELETE: observer{231055169}
08-30 23:10:44.195  3384  3853 D PackageManager: pkg{<packageName>}
08-30 23:10:44.195  3384  3853 D PackageManager: user{0}
08-30 23:10:44.195  3384  3853 D PackageManager: caller{2000}
08-30 23:10:44.195  3384  3853 D PackageManager: flags{2}
,08-30 23:10:44.195  3384  3853 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-30 23:10:44.195  3384  3853 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-30 23:10:44.195  3384  3853 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-30 23:10:44.195  3384  3853 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-30 23:10:44.195  3384  3853 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-30 23:10:44.195  3384  3569 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-30 23:10:44.195  3384  3569 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-30 23:10:44.195  3384  3569 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
,08-30 23:10:44.195  3384  3569 D ApplicationPolicy: getApplicationUninstallationEnabled
08-30 23:10:44.195  3384  3569 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
08-30 23:10:44.195  3384  3569 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
,08-30 23:10:44.195  3384  3569 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,08-30 23:10:44.195  3384  3569 D PackageManager: !@killApplicatoin: 10177, uninstall pkg
,08-30 23:10:44.195  3384  3569 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
08-30 23:10:44.205  3384  3510 I ActivityManager: Force stopping com.test.thalitest appid=10177 user=-1: uninstall pkg
08-30 23:10:44.195  3384  3569 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
08-30 23:10:44.205  3384  3510 I ActivityManager: Killing 9509:com.test.thalitest/u0a177 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-30 23:10:44.205  3384  3510 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-30 23:10:44.205  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:44.215  3384  3510 D ActivityManager: mDVFSHelper.acquire()
,08-30 23:10:44.225  3384  3543 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,08-30 23:10:44.225  3384  3543 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
08-30 23:10:44.225  3384  3543 W System.err: 	at com.android.internal.policy.PhoneWindow.installDecor(PhoneWindow.java:4813)
08-30 23:10:44.225  3384  3543 W System.err: 	at com.android.internal.policy.PhoneWindow.getDecorView(PhoneWindow.java:2263)
08-30 23:10:44.225  3384  3543 W System.err: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4338)
08-30 23:10:44.225  3384  3543 W System.err: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
08-30 23:10:44.225  3384  3543 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 23:10:44.225  3384  3543 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-30 23:10:44.225  3384  3543 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 23:10:44.225  3384  3543 W System.err: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-30 23:10:44.225  3384  3543 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{f5219c3 V.E...... R.....ID 0,0-0,0}
08-30 23:10:44.225  3384  3543 D SecWifiDisplayUtil: Metadata value : SecSettings2
,08-30 23:10:44.225  3384  3543 W WindowManager: Failed looking up window
08-30 23:10:44.225  3384  3543 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@9a09240 does not exist
08-30 23:10:44.225  3384  3543 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
08-30 23:10:44.225  3384  3543 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
08-30 23:10:44.225  3384  3543 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
08-30 23:10:44.225  3384  3543 W WindowManager: 	at android.view.ViewRootImpl.pokeDrawLockIfNeeded(ViewRootImpl.java:1203)
08-30 23:10:44.225  3384  3543 W WindowManager: 	at android.view.ViewRootImpl.scheduleTraversals(ViewRootImpl.java:1415)
08-30 23:10:44.225  3384  3543 W WindowManager: 	at android.view.ViewRootImpl.requestLayout(ViewRootImpl.java:1222)
08-30 23:10:44.225  3384  3543 W WindowManager: 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:800)
08-30 23:10:44.225  3384  3543 W WindowManager: 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:337)
08-30 23:10:44.225  3384  3543 W WindowManager: 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:91)
08-30 23:10:44.225  3384  3543 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4378)
08-30 23:10:44.225  3384  3543 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
08-30 23:10:44.225  3384  3543 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 23:10:44.225  3384  3543 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
08-30 23:10:44.225  3384  3543 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 23:10:44.225  3384  3543 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-30 23:10:44.225  3384  3543 W WindowManager: view not successfully added to wm, removing view
08-30 23:10:44.235  3384  3543 D ViewRootImpl: #3 mView = null
,08-30 23:10:44.235  9920  9920 E Zygote  : v2
08-30 23:10:44.235  9920  9920 I libpersona: KNOX_SDCARD checking this for 10177
08-30 23:10:44.235  9920  9920 I libpersona: KNOX_SDCARD not a persona
,08-30 23:10:44.235  9920  9920 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,08-30 23:10:44.235  9920  9920 E Zygote  : accessInfo : 0
08-30 23:10:44.235  9920  9920 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
,08-30 23:10:44.245  3384  3569 D AASAinstall: there is not AASApackages.xml file
,08-30 23:10:44.245  3384  3510 I ActivityManager: Start proc 9920:com.test.thalitest/u0a177 for activity com.test.thalitest/.MainActivity
08-30 23:10:44.245  3384  3510 I ActivityManager:   Force finishing activity ActivityRecord{f61cfd5 u0 com.test.thalitest/.MainActivity t37}
08-30 23:10:44.245  3384  3510 W VirtualScreenManagerService: moveTaskBackToDisplayIfNeeded(): top activity or app is null
,08-30 23:10:44.275  9920  9920 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 23:10:44.275  9920  9920 D ActivityThread: Added TimaKeyStore provider
08-30 23:10:44.275  3006  3068 I SurfaceFlinger: id=19 Removed NainActivit (6/10)
,08-30 23:10:44.275  3006  4591 I SurfaceFlinger: id=19 Removed NainActivit (-2/10)
,08-30 23:10:44.285  3384  3510 D InputDispatcher: Focused application released
,08-30 23:10:44.285  3384  3510 D FocusedStackFrame: Set to : 0
08-30 23:10:44.285  3384  3510 W VirtualScreenManagerService: failed to move task null
,08-30 23:10:44.335  3384  3978 D GraphicsStats: Buffer count: 7
08-30 23:10:44.335  3384  4323 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@36df579)
08-30 23:10:44.335  3384  3867 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 23:10:44.335  3384  3867 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 23:10:44.345  3384  3867 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 23:10:44.385  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:44.525  3384  3569 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,08-30 23:10:44.565  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:44.595  3384  3569 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-30 23:10:44.595  3166  3166 W keystore: ENTER clear_uid from uid 1000 for 10177
,08-30 23:10:44.595  3384  3569 I art     : Starting a blocking GC Explicit
,08-30 23:10:44.625  6208  6219 I TrayUsageStatesWatcher: notePauseComponent : ComponentInfo{com.sec.android.app.launcher/com.android.launcher2.Launcher}
08-30 23:10:44.625  3384  3384 D GameManagerService: NotifyRunnable. pkg: com.sec.android.app.launcher, type: 4, isMinimized: false, isTunableApp: false
,08-30 23:10:44.625  6208  6219 I TrayUsageStatesWatcher: noteResumeComponent : ComponentInfo{com.sec.android.app.launcher/com.android.launcher2.Launcher} Intent { act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10800000 cmp=com.sec.android.app.launcher/.activities.LauncherActivity VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
,08-30 23:10:44.635  4309  4309 D Launcher: onRestart, Launcher: 78538986
,08-30 23:10:44.645  3384  3510 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.sec.android.app.launcher
,08-30 23:10:44.645  3384  4473 I ActivityManager: Killing 8611:com.samsung.storyservice/5004 (adj 15): DHA:empty #33
,08-30 23:10:44.655  4309  4309 D Launcher: onStart, Launcher: 78538986
08-30 23:10:44.655  4309  4309 D Launcher.HomeView: onStart
,08-30 23:10:44.665  4309  4309 D Launcher: onResume, Launcher: 78538986
,08-30 23:10:44.665  3384  6471 D GameManagerService: identifyGamePackage. com.sec.android.app.launcher
,08-30 23:10:44.665  3384  4323 D SettingsProvider: isChangeAllowed() : name = kids_home_mode
08-30 23:10:44.665  3384  4323 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
08-30 23:10:44.665  3384  4323 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 23:10:44.665  3384  4323 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 23:10:44.665  3384  4323 D SettingsProvider: selectionArgs: false
08-30 23:10:44.665  3384  4323 D SettingsProvider: selectionArgs: 10069
,08-30 23:10:44.665  3384  4323 D SettingsProvider: ret = -1
08-30 23:10:44.665  4309  4309 D Launcher.HomeView: onResume
,08-30 23:10:44.675  3006  3068 I SurfaceFlinger: Modify Choreographer's phase offset to 6666666
,08-30 23:10:44.675  4309  4309 D capture : ---------checkFileExist land
08-30 23:10:44.675  4309  4309 D capture : currentOrientation: 1 mMainHomeScreenshot: true mMainHomeScreenshotLand: true
,08-30 23:10:44.675  4309  4309 D FestivalPageManager: isFestivalChanged prevFestivalString : null , festivalString : null
,08-30 23:10:44.685  3006  3015 I SurfaceFlinger: Modify SurfaceFlinger's phase offset to 6666666
08-30 23:10:44.685  3384  4609 D ActivityManager: isAutoRunBlockedApp:: com.samsung.storyservice, Auto Run ON
08-30 23:10:44.685  4309  4309 D FestivalPageManager: isFestivalChanged : false themeEnable : false
08-30 23:10:44.685  3384  6471 D N       : limitCPUFreq:: freq = -1
08-30 23:10:44.685  3384  6471 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MAX_LIMIT  frequency : 2496000  uid : 1000  pid : 3384  tag : SIOP_ARM_MAX@22
,08-30 23:10:44.685  4309  4309 D Launcher.Model: LoaderTask isFestivalLoader: false
,08-30 23:10:44.685  4309  4399 D Launcher.Model: Begin LoaderTask: 265719188
08-30 23:10:44.685  9920  9920 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,08-30 23:10:44.685  4309  4399 D Launcher.Model: Setting thread priority to DEFAULT
,08-30 23:10:44.685  9920  9920 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
08-30 23:10:44.685  4309  4399 D Launcher.Model: extraUpdateByFota => return, it is not FirstRun!
08-30 23:10:44.685  4309  4399 D Launcher.Model: step 1: loading first workspace
08-30 23:10:44.685  4309  4399 D Launcher.Model: loadAndBindWorkspaceFirst mWorkspaceLoaded: true, mRefreshRequired: false
,08-30 23:10:44.685  4309  4399 D Launcher.Model: bindWorkspace()
08-30 23:10:44.685  9920  9920 D RelationGraph: garbageCollect()
08-30 23:10:44.685  4309  4399 D Launcher.Model:     hotseat : 3
08-30 23:10:44.685  4309  4399 D Launcher.Model:     workspaceCurrentPage : 4
08-30 23:10:44.685  4309  4399 D Launcher.Model:     folders : 3
08-30 23:10:44.685  4309  4399 D Launcher.Model:     widgets : 3
08-30 23:10:44.685  4309  4399 D Launcher.Model:     workspaceOtherPage : 4
08-30 23:10:44.695  4309  4399 D Launcher.Model: Setting thread priority to BACKGROUND
08-30 23:10:44.695  3384  4054 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,08-30 23:10:44.695  9920  9920 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,08-30 23:10:44.705  9920  9920 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/cache
08-30 23:10:44.705  9920  9920 V ActivityThread: Unable to initialize "java.io.tmpdir" property due to missing cache directory
,08-30 23:10:44.705  9920  9920 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/code_cache
08-30 23:10:44.705  9920  9920 E ActivityThread: Unable to setupGraphicsSupport due to missing code-cache directory
08-30 23:10:44.705  9933  9933 I libpersona: KNOX_SDCARD checking this for 10093
08-30 23:10:44.705  9933  9933 E Zygote  : v2
08-30 23:10:44.705  9933  9933 I libpersona: KNOX_SDCARD not a persona
,08-30 23:10:44.705  9933  9933 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,08-30 23:10:44.705  9933  9933 E Zygote  : accessInfo : 0
08-30 23:10:44.705  9933  9933 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.clockpackage 
,08-30 23:10:44.705  9920  9920 I InjectionManager: Inside getClassLibPath caller 
,08-30 23:10:44.715  3384  3510 I ActivityManager: Start proc 9933:com.sec.android.app.clockpackage/u0a93 for broadcast-3 com.sec.android.app.clockpackage/.alarmwidget.ClockAlarmWidgetProvider
,08-30 23:10:44.715  4309  4309 D MenuAppsGridFragment: onResume
08-30 23:10:44.715  3384  3856 D NetworkPolicy: isUidForegroundLocked: 10093, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-30 23:10:44.715  4309  4309 D MenuAppsGridFragment: changeState: (new)NORMAL(old)NORMAL(force)false
08-30 23:10:44.715  3384  6471 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
08-30 23:10:44.715  4309  4309 I MenuAppsGridFragment: onResume mPendingModelUpdate is true, so we need to load apps
08-30 23:10:44.715  4309  4309 D Launcher.MenuAppsGrid: appModelUpdated:-1
08-30 23:10:44.715  4309  4309 D MenuAppModel: get TopLevelItems:20
08-30 23:10:44.715  4309  4309 D Launcher.MenuAppsGrid: syncPages
08-30 23:10:44.715  4309  4309 D MenuAppModel: get TopLevelItems:20
08-30 23:10:44.715  4309  4309 D Launcher.MenuAppsGrid: syncPages end
,08-30 23:10:44.725  3384  6471 D GameManagerService: identifyGamePackage. com.sec.android.app.launcher
,08-30 23:10:44.725  3384  6471 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-30 23:10:44.735  9920  9920 D AndroidRuntime: Shutting down VM
08-30 23:10:44.735  3384  6471 D GameManagerService: identifyGamePackage. com.sec.android.app.launcher
08-30 23:10:44.735  3384  6471 D GameManagerService: identifyGamePackage. com.sec.android.app.launcher
,08-30 23:10:44.735  9933  9933 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 23:10:44.735  9933  9933 D ActivityThread: Added TimaKeyStore provider
,08-30 23:10:44.735  9920  9920 E AndroidRuntime: FATAL EXCEPTION: main
08-30 23:10:44.735  9920  9920 E AndroidRuntime: Process: com.test.thalitest, PID: 9920
08-30 23:10:44.735  9920  9920 E AndroidRuntime: java.lang.RuntimeException: Unable to instantiate application android.app.Application: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
08-30 23:10:44.735  9920  9920 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:676)
08-30 23:10:44.735  9920  9920 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6294)
08-30 23:10:44.735  9920  9920 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:222)
08-30 23:10:44.735  9920  9920 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1861)
08-30 23:10:44.735  9920  9920 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 23:10:44.735  9920  9920 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:158)
08-30 23:10:44.735  9920  9920 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:7229)
08-30 23:10:44.735  9920  9920 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 23:10:44.735  9920  9920 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-30 23:10:44.735  9920  9920 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-30 23:10:44.735  9920  9920 E AndroidRuntime: Caused by: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
08-30 23:10:44.735  9920  9920 E AndroidRuntime: 	at android.app.LoadedApk.initializeJavaContextClassLoader(LoadedApk.java:485)
08-30 23:10:44.735  9920  9920 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:661)
08-30 23:10:44.735  9920  9920 E AndroidRuntime: 	... 9 more
,08-30 23:10:44.745  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:44.745  3384  3978 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1c926c u0 com.android.launcher.action.HOME_MODE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c4f7035 9933:com.sec.android.app.clockpackage/u0a93}
,08-30 23:10:44.745  3384  3856 D NetworkPolicy: isUidForegroundLocked: 10093, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
,08-30 23:10:44.755  9920  9920 I Process : Sending signal. PID: 9920 SIG: 9
,08-30 23:10:44.775  3384  4609 I ActivityManager: Process com.test.thalitest (pid 9920)(adj 9) has died(195,1687)
,08-30 23:10:44.775  3384  4609 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-30 23:10:44.775  3384  4609 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.am.ActivityManagerService.updateOomAdjLocked:26743 com.android.server.am.ActivityManagerService.appDiedLocked:7562 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1916 android.os.BinderProxy.sendDeathNotice:558 
,08-30 23:10:44.785  9933  9933 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,08-30 23:10:44.785  9933  9933 D RelationGraph: garbageCollect()
,08-30 23:10:44.785  9933  9933 W ResourcesManager: getTopLevelResources: /system/app/ClockPackage_M/ClockPackage_M.apk / 1.0 running in com.sec.android.app.clockpackage rsrc of package com.sec.android.app.clockpackage
,08-30 23:10:44.785  3384  4634 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,08-30 23:10:44.795  9933  9933 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
08-30 23:10:44.795  4309  4309 W ResourcesManager: getTopLevelResources: /system/app/ClockPackage_M/ClockPackage_M.apk / 1.0 running in com.sec.android.app.launcher rsrc of package com.sec.android.app.clockpackage
,08-30 23:10:44.795  4309  4309 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:44.795  9933  9933 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:44.805  4309  4309 D ApplicationPackageManager: we don't have com.sec.android.app.clockpackage class. load it
,08-30 23:10:44.805  9933  9933 I InjectionManager: Inside getClassLibPath caller 
,08-30 23:10:44.805  4309  4309 W ResourcesManager: getTopLevelResources: /system/app/ClockPackage_M/ClockPackage_M.apk / 1.0 running in com.sec.android.app.launcher rsrc of package com.sec.android.app.clockpackage
08-30 23:10:44.805  3384  3569 I art     : Explicit concurrent mark sweep GC freed 276719(17MB) AllocSpace objects, 33(2MB) LOS objects, 31% free, 34MB/50MB, paused 3.503ms total 210.656ms
,08-30 23:10:44.815  9933  9933 W System  : ClassLoader referenced unknown path: /system/app/ClockPackage_M/lib/arm64
,08-30 23:10:44.835  3384  3569 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
08-30 23:10:44.835  3384  3569 D AASAuninstall: userId = 0, info.removedAppID = 10177, info.uid = 10177, packageName = com.test.thalitest
,08-30 23:10:44.835  3384  3569 D AASAinstall: there is not AASApackages.xml file
08-30 23:10:44.835  3384  3569 D PackageManager: result of delete: 1{231055169}
,08-30 23:10:44.835  4309  4309 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M/SPlanner_M.apk / 1.0 running in com.sec.android.app.launcher rsrc of package com.android.calendar
,08-30 23:10:44.835  9911  9911 I art     : System.exit called, status: 0
08-30 23:10:44.835  4309  4309 D ResourcesManager: For user 0 new overlays fetched Null
08-30 23:10:44.835  9911  9911 I AndroidRuntime: VM exiting with result code 0.
,08-30 23:10:44.835  3384  3569 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-30 23:10:44.835  3384  3569 D PackageManager: userId{-1}
08-30 23:10:44.835  3384  3569 D PackageManager: andCode{true}
,08-30 23:10:44.845  4309  4309 D ApplicationPackageManager: we don't have com.android.calendar class. load it
,08-30 23:10:44.845  3384  3569 I ActivityManager: Force stopping com.test.thalitest appid=10177 user=0: pkg removed
08-30 23:10:44.845  4309  4309 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M/SPlanner_M.apk / 1.0 running in com.sec.android.app.launcher rsrc of package com.android.calendar
,08-30 23:10:44.855  4309  4309 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
08-30 23:10:44.855  4309  4309 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
08-30 23:10:44.855  4309  4309 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
,08-30 23:10:44.875  9383  9949 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
,08-30 23:10:44.875  4309  4309 D Launcher.MenuAppsGrid: updateGridSize:GRID_4x4 cellWidth:348  cellHeight:432
,08-30 23:10:44.875  9383  9949 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
,08-30 23:10:44.875  9383  9949 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
,08-30 23:10:44.895  9933  9933 I BNRClientProivder, VERSION : 1.7.6: register - xml6 : Alarm, v5VJ0Ep6EE, com.sec.android.app.clockpackage.alarm.backuprestore.AlarmSCloudBackupRestore
,08-30 23:10:44.905  9933  9933 I BNRClientHelper: 101, Alarm, VERSION 1.7.6
08-30 23:10:44.905  3384  4313 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() true
08-30 23:10:44.905  3384  4313 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
08-30 23:10:44.905  3384  4313 D KnoxTimeoutHandler: post home show event for user 0
08-30 23:10:44.905  3384  3384 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
08-30 23:10:44.905  3384  4313 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-30 23:10:44.905  3384  3384 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
08-30 23:10:44.905  3384  3384 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-30 23:10:44.905  4309  4309 D Launcher: onPause, Launcher: 78538986
08-30 23:10:44.905  4309  4309 D Launcher.HomeView: onPause
08-30 23:10:44.905  4309  4309 D Launcher.Workspace: exitWidgetResizeMode. isClearResizeFrame is false
08-30 23:10:44.905  9933  9933 I BNRClientProivder, VERSION : 1.7.6: register - xml6 : WorldClock, pYz7p28bSl, com.sec.android.app.clockpackage.worldclock.backuprestore.WorldclockSCloudBackupRestore
,08-30 23:10:44.905  3384  3384 I KnoxTimeoutHandler: Shared devices show user statefalse
,08-30 23:10:44.905  4309  4309 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 684 440 span 2 1 (widgetid 2) [current Gridsize : GRID_4x4]
08-30 23:10:44.905  4309  4309 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Pogoda(widget id = 2) result hostview size = 684 x 440
08-30 23:10:44.905  4309  4309 D LauncherAppWidgetHostView: setResizeScaleResult() 684/ 440 scaleToResize = 1.0(widget id = 2)
08-30 23:10:44.905  4309  4309 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 1372 440 span 4 1 (widgetid 3) [current Gridsize : GRID_4x4]
08-30 23:10:44.905  4309  4309 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Aplikacja Google(widget id = 3) result hostview size = 1372 x 440
08-30 23:10:44.905  4309  4309 D LauncherAppWidgetHostView: setResizeScaleResult() 1372/ 440 scaleToResize = 1.0(widget id = 3)
08-30 23:10:44.905  4309  4309 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 1372 440 span 4 1 (widgetid 4) [current Gridsize : GRID_4x4]
08-30 23:10:44.905  4309  4309 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Galaxy Essentials(widget id = 4) result hostview size = 1372 x 440
08-30 23:10:44.905  4309  4309 D LauncherAppWidgetHostView: setResizeScaleResult() 1372/ 440 scaleToResize = 1.0(widget id = 4)
08-30 23:10:44.915  9933  9933 I BNRClientHelper: 101, WorldClock, VERSION 1.7.6
08-30 23:10:44.915  9933  9933 I BNRClientProivder, VERSION : 1.7.6: register - xml6 quick_backup : ALARMWIDGET, I6IHHRg397, com.sec.android.app.clockpackage.alarm.backuprestore.AlarmWidgetSCloudBackupRestore
08-30 23:10:44.915  9933  9933 I QBNRClientHelper: init SyncClientHelper : ALARMWIDGET
,08-30 23:10:44.915  9933  9933 I BNRClientProivder, VERSION : 1.7.6: register - xml6 quick_backup : DUALCLOCKWIDGET, ZCms5GaCFo, com.sec.android.widgetapp.dualclockdigital.DualClockDigitalBackupRestoreReceiver
,08-30 23:10:44.915  9933  9933 I QBNRClientHelper: init SyncClientHelper : DUALCLOCKWIDGET
,08-30 23:10:44.915  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,08-30 23:10:44.915  3006  3006 I SurfaceFlinger: id=20 createSurf (1440x2560),1 flag=4, MauncherAct
,08-30 23:10:44.925  3384  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package com.google.android.googlequicksearchbox
08-30 23:10:44.925  4309  4626 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,08-30 23:10:44.925  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 23:10:44.925  3384  3384 D ResourcesManager: For user 0 new overlays fetched Null
08-30 23:10:44.925  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-30 23:10:44.925  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
,08-30 23:10:44.925  3384  3505 D ResourcesManager: For user 0 new overlays fetched Null
08-30 23:10:44.925  6208  6208 I TrayVisibilityController: handleMessage : msg.what = 1
,08-30 23:10:44.925  3384  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package com.google.android.googlequicksearchbox
08-30 23:10:44.925  3384  3384 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:44.925  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
08-30 23:10:44.925  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
08-30 23:10:44.925  3384  3505 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
08-30 23:10:44.935  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
,08-30 23:10:44.935  4309  4309 D MenuAppModel: invalidateTopLevelItems
08-30 23:10:44.935  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
08-30 23:10:44.935  4309  4309 D Launcher.Model: MenuAppModel.onModelRefreshed called
08-30 23:10:44.935  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
08-30 23:10:44.935  4309  4309 D Launcher.MenuWidgetsLoader: MenuWidgetLoade-loadMenuWidgets : true
08-30 23:10:44.935  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungAccount_Hero/SamsungAccount_Hero.apk / 1.0 running in null rsrc of package com.osp.app.signin
,08-30 23:10:44.935  4309  4309 D Launcher.Model: bindAppsLoaded called
,08-30 23:10:44.935  4309  4309 V ActivityThread: updateVisibility : ActivityRecord{3480a49 token=android.os.BinderProxy@5a22d51 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : true
08-30 23:10:44.935  4309  4309 D Launcher.HomeView: onStop
08-30 23:10:44.935  4309  4309 D capture : ----destroy
,08-30 23:10:44.945  3384  3505 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:44.945  3384  3384 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:44.945  3384  3505 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
,08-30 23:10:44.945  3384  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package com.google.android.googlequicksearchbox
,08-30 23:10:44.945  3384  3505 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
,08-30 23:10:44.945  3384  3505 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
,08-30 23:10:44.945  3384  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/LiveBroadcast/LiveBroadcast.apk / 1.0 running in null rsrc of package com.sec.android.app.camera.plb
,08-30 23:10:44.955  3384  3505 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:44.955  3384  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/LiveBroadcast/LiveBroadcast.apk / 1.0 running in null rsrc of package com.sec.android.app.camera.plb
,08-30 23:10:44.955  3384  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCamera5/SamsungCamera5.apk / 1.0 running in null rsrc of package com.sec.android.app.camera
,08-30 23:10:44.955  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungAccount_Hero/SamsungAccount_Hero.apk / 1.0 running in null rsrc of package com.osp.app.signin
08-30 23:10:44.955  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,08-30 23:10:44.955  3384  3505 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:44.955  3384  3384 D ResourcesManager: For user 0 new overlays fetched Null
08-30 23:10:44.955  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-30 23:10:44.955  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-30 23:10:44.955  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-30 23:10:44.955  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-30 23:10:44.955  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,08-30 23:10:44.955  3384  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCamera5/SamsungCamera5.apk / 1.0 running in null rsrc of package com.sec.android.app.camera
08-30 23:10:44.955  3384  3384 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in null rsrc of package com.samsung.android.coreapps
08-30 23:10:44.955  3384  3505 W ResourcesManager: getTopLevelResources: /system/app/STalkback/STalkback.apk / 1.0 running in null rsrc of package com.samsung.android.app.talkback
08-30 23:10:44.955  3384  3384 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:44.955  3384  3505 D ResourcesManager: For user 0 new overlays fetched Null
08-30 23:10:44.955  3384  3384 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in null rsrc of package com.samsung.android.coreapps
08-30 23:10:44.955  3384  3384 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
08-30 23:10:44.955  3384  3505 W ResourcesManager: getTopLevelResources: /system/app/STalkback/STalkback.apk / 1.0 running in null rsrc of package com.samsung.android.app.talkback
08-30 23:10:44.955  3384  3505 W ResourcesManager: getTopLevelResources: /system/app/UniversalSwitch/UniversalSwitch.apk / 1.0 running in null rsrc of package com.samsung.android.universalswitch
,08-30 23:10:44.965  3384  3505 D ResourcesManager: For user 0 new overlays fetched Null
08-30 23:10:44.965  3384  3384 D ResourcesManager: For user 0 new overlays fetched Null
08-30 23:10:44.965  3384  3505 W ResourcesManager: getTopLevelResources: /system/app/UniversalSwitch/UniversalSwitch.apk / 1.0 running in null rsrc of package com.samsung.android.universalswitch
08-30 23:10:44.965  3384  3384 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
08-30 23:10:44.965  3384  3505 D AccessibilityManagerService: onUserStateChangedLocked()
08-30 23:10:44.965  3384  3505 D AccessibilityManagerService: updateServicesLocked().mIsAccessibilityEnabled : false
08-30 23:10:44.965  3384  3384 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
08-30 23:10:44.965  3384  3384 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
08-30 23:10:44.965  3384  3384 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
,08-30 23:10:44.965  3384  3384 D ResourcesManager: For user 0 new overlays fetched Null
08-30 23:10:44.965  3384  3384 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
08-30 23:10:44.965  3384  3384 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in null rsrc of package com.microsoft.office.onenote
,08-30 23:10:44.965  3384  3384 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:44.965  3384  3384 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in null rsrc of package com.microsoft.office.onenote
08-30 23:10:44.965  3384  3384 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
,08-30 23:10:44.965  3384  3384 D ResourcesManager: For user 0 new overlays fetched Null
08-30 23:10:44.965  3384  3384 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
,08-30 23:10:44.965  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-30 23:10:44.965  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-30 23:10:44.965  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-30 23:10:44.965  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-30 23:10:44.965  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-30 23:10:44.965  3384  3505 D EnterpriseDeviceManagerService: Package has changed for user 0
08-30 23:10:44.965  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-30 23:10:44.965  3384  3505 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
08-30 23:10:44.965  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-30 23:10:44.965  3938  3938 D ShortcutManager: onReceive : android.intent.action.PACKAGE_REMOVED
08-30 23:10:44.965  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-30 23:10:44.965  3938  3938 D ShortcutManager: onReceive : Intent.EXTRA_REPLACING false,com.test.thalitest
08-30 23:10:44.965  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-30 23:10:44.965  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-30 23:10:44.965  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-30 23:10:44.965  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-30 23:10:44.965  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-30 23:10:44.965  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-30 23:10:44.965  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-30 23:10:44.965  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-30 23:10:44.965  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-30 23:10:44.965  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-30 23:10:44.965  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-30 23:10:44.965  3384  3505 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
08-30 23:10:44.965  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-30 23:10:44.965  3384  3384 W ResourcesManager: getT,opLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-30 23:10:44.965  3384  3505 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
08-30 23:10:44.965  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-30 23:10:44.965  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-30 23:10:44.965  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-30 23:10:44.965  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-30 23:10:44.965  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-30 23:10:44.965  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-30 23:10:44.965  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-30 23:10:44.965  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-30 23:10:44.965  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-30 23:10:44.965  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-30 23:10:44.965  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-30 23:10:44.965  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package com.google.android.gsf
08-30 23:10:44.975  3384  3384 D ResourcesManager: For user 0 new overlays fetched Null
08-30 23:10:44.975  3384  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in null rsrc of package com.android.settings
08-30 23:10:44.975  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package com.google.android.gsf
08-30 23:10:44.975  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package com.sec.android.app.shealth
08-30 23:10:44.975  3384  3543 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package com.android.inputdevices
08-30 23:10:44.975  4145  4145 I CatchNotificationsService: mPackageChangedReceiver : onReceive action = android.intent.action.PACKAGE_REMOVED
08-30 23:10:44.975  3384  3384 D ResourcesManager: For user 0 new overlays fetched Null
08-30 23:10:44.975  3384  3505 D ResourcesManager: For user 0 new overlays fetched Null
08-30 23:10:44.975  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package com.sec.android.app.shealth
08-30 23:10:44.975  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package com.sec.android.app.shealth
08-30 23:10:44.975  3384  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in null rsrc of package com.android.settings
08-30 23:10:44.975  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package com.sec.android.app.shealth
08-30 23:10:44.975  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
08-30 23:10:44.975  3384  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
08-30 23:10:44.975  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
08-30 23:10:44.975  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
08-30 23:10:44.975  3384  3543 D ResourcesManager: For user 0 new overlays fetched Null
08-30 23:10:44.975  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
08-30 23:10:44.975  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
08-30 23:10:44.975  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
08-30 23:10:44.975  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
08-30 23:10:44.975  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
08-30 23:10:44.975  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
08-30 23:10:44.975  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
08-30 23:10:44.975  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
08-30 23:10:44.975  3384  3543 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package com.android.inputdevices
08-30 23:10:44.975  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
08-30 23:10:44.975  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-30 23:10:44.975  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-30 23:10:44.985  3384  3830 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-30 23:10:44.975  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-30 23:10:44.975  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-30 23:10:44.975  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-30 23:10:44.975  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-30 23:10:44.975  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-30 23:10:44.975  3384  3505 D ResourcesManager: For user 0 new overlays fetched Null
08-30 23:10:44.975  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-30 23:10:44.975  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-30 23:10:44.975  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-30 23:10:44.975  3384  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
08-30 23:10:44.975  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-30 23:10:44.975  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-30 23:10:44.975  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-30 23:10:44.975  3384  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
08-30 23:10:44.975  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-30 23:10:44.975  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-30 23:10:44.975  3384  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
08-30 23:10:44.975  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-30 23:10:44.975  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
08-30 23:10:44.975  3384  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-30 23:10:44.975  3384  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-30 23:10:44.975  3384  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Epic_Common/SecMms_Epic_Common.apk / 1.0 running in null rsrc of package com.android.mms
08-30 23:10:44.975  3384  3384 D ResourcesManager: For user 0 new overlays fetched Null
08-30 23:10:44.975  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
08-30 23:10:44.975  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
08-30 23:10:44.975  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
08-30 23:10:44.975  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
08-30 23:10:44.975  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
08-30 23:10:44.975  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
08-30 23:10:44.975  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
08-30 23:10:44.975  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
08-30 23:10:44.985  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
08-30 23:10:44.985  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
08-30 23:10:44.985  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
08-30 23:10:44.985  3384  3505 D ResourcesManager: For user 0 new overlays fetched Null
08-30 23:10:44.985  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
08-30 23:10:44.985  3384  3384 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
08-30 23:10:44.985  3384  3384 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package com.android.chrome
08-30 23:10:44.985  3384  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Epic_Common/SecMms_Epic_Common.apk / 1.0 running in null rsrc of package com.android.mms
08-30 23:10:44.985  3384  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles/SecMyFiles.apk / 1.0 running in null rsrc of package com.sec.android.app.myfiles
08-30 23:10:44.985  3384  3384 D ResourcesManager: For user 0 new overlays fetched Null
08-30 23:10:44.985  3384  3505 D ResourcesManager: For user 0 new overlays fetched Null
08-30 23:10:44.985  3384  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles/SecMyFiles.apk / 1.0 running in null rsrc of package com.sec.android.app.myfiles
08-30 23:10:44.985  3384  3384 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package com.android.chrome
08-30 23:10:44.985  3384  3384 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in null rsrc of package com.samsung.android.coreapps
08-30 23:10:44.985  3384  3384 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in null rsrc of package com.samsung.android.coreapps
08-30 23:10:44.985  3384  3505 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package com.google.android.music
08-30 23:10:44.985  3384  3384 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package com.google.android.apps.docs
08-30 23:10:44.985  3384  3384 D ResourcesManager: For user 0 new overlays fetched Null
08-30 23:10:44.985  3384  3505 D ResourcesManager: For user 0 new overlays fetched Null
08-30 23:10:44.985  3384  3384 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package com.google.android.apps.docs
08-30 23:10:44.985  3384  3384 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
08-30 23:10:44.985  3384  3505 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package com.google.android.music
08-30 23:10:44.985  3384  3384 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
08-30 23:10:44.985  3384  3384 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
08-30 23:10:44.985  3384  3384 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
08-30 23:10:44.985  3384  3505 W ResourcesManager: getTopLevelResources: /system/app/SecMemo3/SecMemo3.apk / 1.0 running in null rsrc of package com.samsung.android.app.memo
08-30 23:10:44.985  3384  3384 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
08-30 23:10:44.985  3384  3384 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
08-30 23:10:44.985  3384  3384 W ResourcesManager: getTopLevelResources: /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk / 1.0 running in null rsrc of package com.google.android.syncadapters.calendar
08-30 23:10:44.985  3384  3384 D ResourcesManager: For user 0 new overlays fetched Null
08-30 23:10:44.985  3384  3505 D ResourcesManager: For user 0 new overlays fetched Null
08-30 23:10:44.985  3384  3384 W ResourcesManager: getTopLevelResources: /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk / 1.0 running in null rsrc of package com.google.android.syncadapters.calendar
08-30 23:10:44.985  3384  3384 W ResourcesManager: getTopLevelResources: /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk / 1.0 running in null rsrc of package com.google.android.syncadapters.contacts
08-30 23:10:44.985  3384  3384 D ResourcesManager: For user 0 new overlays fetched Null
08-30 23:10:44.985  3384  3384 W ResourcesManager: getTopLevelResources: /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk / 1.0 running in null rsrc of package com.google.android.syncadapters.contacts
08-30 23:10:44.985  3384  3384 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package com.google.android.music
08-30 23:10:44.985  3384  3384 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package com.google.android.music
08-30 23:10:44.985  3384  3384 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
08-30 23:10:44.985  3384  3505 W ResourcesManager: getTopLevelResources: /system/app/SecMemo3/SecMemo3.apk / 1.0 running in null rsrc of package com.samsung.android.app.memo
08-30 23:10:44.985  3384  3384 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
08-30 23:10:44.985  3384  3384 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in null rsrc of package com.microsoft.office.onenote
08-30 23:10:44.985  3384  3384 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in null rsrc of package com.microsoft.office.onenote
08-30 23:10:44.985  3384  3384 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
08-30 23:10:44.985  3384  3384 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
08-30 23:10:44.985  3384  3384 W ResourcesManager: getTopLevelResources: /system/app/Videos/Videos.apk / 1.0 running in null rsrc of package com.google.android.videos
08-30 23:10:44.985  3384  3505 W ResourcesManager: getTopLevelResources: /system/app/Weather2016/Weather2016.apk / 1.0 running in null rsrc of package com.samsung.android.weather
08-30 23:10:44.995  3384  3384 D ResourcesManager: For user 0 new overlays fetched Null
08-30 23:10:44.995  3006  3006 D libEGL  : eglInitialize EGLDisplay = 0x7fd1ae6ea8
08-30 23:10:44.995  3384  3505 D ResourcesManager: For user 0 new overlays fetched Null
08-30 23:10:44.995  3384  3505 W ResourcesManager: getTopLevelResources: /system/app/Weather2016/Weather2016.apk / 1.0 running in null rsrc of package com.samsung.android.weather
08-30 23:10:44.995  3384  3384 W ResourcesManager: getTopLevelResources: /system/app/Videos/Videos.apk / 1.0 running in null rsrc of package com.google.android.videos
08-30 23:10:44.995  3384  3505 W ResourcesManager: getTopLevelResources: /system/app/YouTube/YouTube.apk / 1.0 running in null rsrc of package com.google.android.youtube
08-30 23:10:44.995  3384  3384 V AlarmManager: Remove alarm for next reason : android.intent.action.PACKAGE_REMOVED : package: com.test.thalitest
08-30 23:10:44.995  3384  3384 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
08-30 23:10:44.995  3384  3384 D UniversalCredentialManagerService: inside mPkgReciever onReceive : android.intent.action.PACKAGE_REMOVED
08-30 23:10:44.995  3384  3384 D UniversalCredentialManagerService: ACTION_PACKAGE_REMOVED is called....
08-30 23:10:44.995  3384  3384 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-30 23:10:44.995  3384  3384 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-30 23:10:44.995  3384  3384 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10177 container id = 0
08-30 23:10:44.995  4339  4804 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-30 23:10:44.995  3384  3384 I OTPFW   : ProvisionData::getAllEntries Enter
08-30 23:10:44.995  3384  3505 D ResourcesManager: For user 0 new overlays fetched Null
08-30 23:10:44.995  3384  4997 V WindowStateAnimator: Finishing drawing window Window{dd169cc u0 d0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}: mDrawState=DRAW_PENDING
08-30 23:10:44.995  3384  3505 W ResourcesManager: getTopLevelResources: /system/app/YouTube/YouTube.apk / 1.0 running in null rsrc of package com.google.android.youtube
08-30 23:10:44.995  3384  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-30 23:10:44.995  3384  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
08-30 23:10:44.995  3384  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/MyPlaces_Hero/MyPlaces_Hero.apk / 1.0 running in null rsrc of package com.sec.android.widgetapp.locationwidget
08-30 23:10:44.995  3384  3384 E OTPFW   : ProvisionData::getAllEntries Table is empty
08-30 23:10:44.995  3384  3384 E SDAgentPackageStateReceiver: Not going to handle 'com.test.thalitest'!
08-30 23:10:44.995  3384  3505 D ResourcesManager: For user 0 new overlays fetched Null
08-30 23:10:44.995  3384  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/MyPlaces_Hero/MyPlaces_Hero.apk / 1.0 running in null rsrc of package com.sec.android.widgetapp.locationwidget
08-30 23:10:44.995  3384  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
08-30 23:10:44.995  3384  3384 D UcmService: onReceive android.intent.action.PACKAGE_REMOVED
08-30 23:10:44.995  3384  3384 D UcmService: Package update in userId-0 and uid-10177
08-30 23:10:44.995  3384  3384 D InjectionManagerService -AppFeature:  Info before com.test.thalitest removal target ={} 
08-30 23:10:44.995  3384  3384 D InjectionManagerService -AppFeature:  source ={}
08-30 23:10:44.995  3384  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in null rsrc of package com.android.settings
08-30 23:10:44.995  3384  3384 W SQLiteLog: (28) failed to open "/data/system/gamemanager.db" with flag (131138) and mode_t (0) due to error (30)
08-30 23:10:44.995  3384  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/TouchWizHome_2016/TouchWizHome_2016.apk / 1.0 running in null rsrc of package com.sec.android.app.launcher
08-30 23:10:44.995  3384  3505 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package com.android.chrome
08-30 23:10:44.995  3384  3505 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package com.android.chrome
08-30 23:10:44.995  3384  3505 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package com.google.android.apps.docs
08-30 23:10:44.995  3384  3505 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package com.google.android.apps.docs
08-30 23:10:44.995  3384  3505 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package com.google.android.apps.docs
08-30 23:10:44.995  3384  3505 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
08-30 23:10:44.995  3384  3505 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
08-30 23:10:44.995  3384  3505 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M/SPlanner_M.apk / 1.0 running in null rsrc of package com.android.calendar
08-30 23:10:44.995  3384  3384 E SQLiteDatabase: Failed to open database '/data/system/gamemanager.db'.
08-30 23:10:44.995  3384  3384 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 23:10:44.995  3384  3384 E SQLiteDatabase: #################################################################
08-30 23:10:44.995  3384  3384 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
08-30 23:10:44.995  3384  3384 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
08-30 23:10:44.995  3384  3384 E SQLiteDatabase: #################################################################
08-30 23:10:44.995  3384  3384 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 23:10:44.995  3384  3384 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:283)
08-30 23:10:44.995  3384  3384 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:210)
08-30 23:10:44.995  3384  3384 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-30 23:10:44.995  3384  3384 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-30 23:10:44.995  3384  3384 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-30 23:10:44.995  3384  3384 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-30 23:10:44.995  3384  3384 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-30 23:10:44.995  3384  3384 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-30 23:10:44.995  3384  3384 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:633)
08-30 23:10:44.995  3384  3384 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 23:10:44.995  3384  3384 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 23:10:44.995  3384  3384 E SQLiteDatabase: 	at com.samsung.android.game.data.DatabaseHelper.removeGame(DatabaseHelper.java:144)
08-30 23:10:44.995  3384  3384 E SQLiteDatabase: 	at com.samsung.android.game.GameManagerService$UninstallReceiver.onReceive(GameManagerService.java:512)
08-30 23:10:44.995  3384  3384 E SQLiteDatabase: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:993)
08-30 23:10:44.995  3384  3384 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 23:10:44.995  3384  3384 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 23:10:44.995  3384  3384 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:158)
08-30 23:10:44.995  3384  3384 E SQLiteDatabase: 	at com.android.server.SystemServer.run(SystemServer.java:508)
08-30 23:10:44.995  3384  3384 E SQLiteDatabase: 	at com.android.server.SystemServer.main(SystemServer.java:363)
08-30 23:10:44.995  3384  3384 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 23:10:44.995  3384  3384 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-30 23:10:44.995  3384  3384 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-30 23:10:44.995  3384  3384 D AndroidRuntime: Shutting down VM
08-30 23:10:44.995  3384  3505 D ResourcesManager: For user 0 new overlays fetched Null
08-30 23:10:44.995  3384  3384 E AndroidRuntime: *** FATAL EXCEPTION IN SYSTEM PROCESS: main
08-30 23:10:44.995  3384  3384 E AndroidRuntime: java.lang.RuntimeException: Error receiving broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) } in com.samsung.android.game.GameManagerService$UninstallReceiver@305a066
08-30 23:10:44.995  3384  3384 E AndroidRuntime: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1003)
08-30 23:10:44.995  3384  3384 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 23:10:44.995  3384  3384 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 23:10:44.995  3384  3384 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:158)
08-30 23:10:44.995  3384  3384 E AndroidRuntime: 	at com.android.server.SystemServer.run(SystemServer.java:508)
08-30 23:10:44.995  3384  3384 E AndroidRuntime: 	at com.android.server.SystemServer.main(SystemServer.java:363)
08-30 23:10:44.995  3384  3384 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 23:10:44.995  3384  3384 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-30 23:10:44.995  3384  3384 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-30 23:10:44.995  3384  3384 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 23:10:44.995  3384  3384 E AndroidRuntime: #################################################################
08-30 23:10:44.995  3384  3384 E AndroidRuntime: Error Code : 0 (SQLITE_OK)
08-30 23:10:44.995  3384  3384 E AndroidRuntime: Caused By : not an error (code 0): Could not open the database in read/write mode.
08-30 23:10:44.995  3384  3384 E AndroidRuntime: #################################################################
08-30 23:10:44.995  3384  3384 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 23:10:44.995  3384  3384 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:283)
08-30 23:10:44.995  3384  3384 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:210)
08-30 23:10:44.995  3384  3384 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-30 23:10:44.995  3384  3384 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-30 23:10:44.995  3384  3384 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-30 23:10:44.995  3384  3384 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-30 23:10:44.995  3384  3384 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-30 23:10:44.995  3384  3384 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-30 23:10:44.995  3384  3384 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:633)
08-30 23:10:44.995  3384  3384 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 23:10:44.995  3384  3384 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 23:10:44.995  3384  3384 E AndroidRuntime: 	at com.samsung.android.game.data.DatabaseHelper.removeGame(DatabaseHelper.java:144)
08-30 23:10:44.995  3384  3384 E AndroidRuntime: 	at com.samsung.android.game.GameManagerService$UninstallReceiver.onReceive(GameManagerService.java:512)
08-30 23:10:44.995  3384  3384 E AndroidRuntime: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:993)
08-30 23:10:44.995  3384  3384 E AndroidRuntime: 	... 8 more
08-30 23:10:44.995  3384  3505 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M/SPlanner_M.apk / 1.0 running in null rsrc of package com.android.calendar
08-30 23:10:44.995  3384  3505 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M/SPlanner_M.apk / 1.0 running in null rsrc of package com.android.calendar
08-30 23:10:45.005  3384  3505 W ResourcesManager: getTopLevelResources: /system/app/Weather2016/Weather2016.apk / 1.0 running in null rsrc of package com.samsung.android.weather
08-30 23:10:45.005  3384  3505 W ResourcesManager: getTopLevelResources: /system/app/Weather2016/Weather2016.apk / 1.0 running in null rsrc of package com.samsung.android.weather
08-30 23:10:45.005  3384  3505 W ResourcesManager: getTopLevelResources: /system/app/YouTube/YouTube.apk / 1.0 running in null rsrc of package com.google.android.youtube
08-30 23:10:45.005  3384  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package com.google.android.googlequicksearchbox
08-30 23:10:45.005  3384  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package com.google.android.googlequicksearchbox
08-30 23:10:45.005  3384  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
08-30 23:10:45.005  3384  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2015/SecGallery2015.apk / 1.0 running in null rsrc of package com.sec.android.gallery3d
08-30 23:10:45.005  3384  3505 D ResourcesManager: For user 0 new overlays fetched Null
08-30 23:10:45.005  5081  5317 D PresenceModule: onReceive: package removed
08-30 23:10:45.005  3384  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2015/SecGallery2015.apk / 1.0 running in null rsrc of package com.sec.android.gallery3d
08-30 23:10:45.005  5081  5317 D PresenceModule: handleMessage: msg 50, Last Publish Info: null
08-30 23:10:45.005  3384  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/SFinder_v4/SFinder_v4.apk / 1.0 running in null rsrc of package com.samsung.android.app.galaxyfinder
08-30 23:10:45.005  5081  5317 D PresenceModule: Application package removed
08-30 23:10:45.005  5081  5317 D PresenceModule: onAppPkgRemoved: com.test.thalitest
08-30 23:10:45.005  5081  5317 D PresenceModule: onApplicationPackageRemoved: invalid package
08-30 23:10:45.005  3384  3505 D ResourcesManager: For user 0 new overlays fetched Null
08-30 23:10:45.005  3384  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/SFinder_v4/SFinder_v4.apk / 1.0 running in null rsrc of package com.samsung.android.app.galaxyfinder
08-30 23:10:45.005  3384  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/SFinder_v4/SFinder_v4.apk / 1.0 running in null rsrc of package com.samsung.android.app.galaxyfinder
08-30 23:10:45.005  3384  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/VoiceNote_4.0/VoiceNote_4.0.apk / 1.0 running in null rsrc of package com.sec.android.app.voicenote
08-30 23:10:45.005  3384  3505 D ResourcesManager: For user 0 new overlays fetched Null
08-30 23:10:45.005  3384  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/VoiceNote_4.0/VoiceNote_4.0.apk / 1.0 running in null rsrc of package com.sec.android.app.voicenote
08-30 23:10:45.005  3384  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/VoiceNote_4.0/VoiceNote_4.0.apk / 1.0 running in null rsrc of package com.sec.android.app.voicenote
08-30 23:10:45.005  3384  3505 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
08-30 23:10:45.005  3384  3505 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
08-30 23:10:45.005  4157  4157 I PeoplePackageManager: onReceive:android.intent.action.PACKAGE_REMOVED
,08-30 23:10:45.015  3384  3384 E android.os.Debug: THIS IS SYSTEM_SERVER.. store dumpState!!
08-30 23:10:45.025  3384  3855 V NetworkStats: removeUidsLocked() for UIDs [10177]
08-30 23:10:45.025  3384  3855 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 23:10:45.025  3384  3855 V NetworkStats: performPollLocked(flags=0x3)
08-30 23:10:45.025  4309  4309 W CellLayoutChildren: Adding view to CellLayoutChildren without an associated item.
08-30 23:10:45.025  4309  4309 D CellLayoutHotseat: addItem : Telefon, 1
08-30 23:10:45.035  3384  3855 D NetworkStatsRecorder: entry.iface is null
08-30 23:10:45.035  3384  3855 D NetworkStatsRecorder: entry.iface is null
08-30 23:10:45.035  4296  4296 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
08-30 23:10:45.035  3384  3855 D NetworkStatsRecorder: entry.iface is null
08-30 23:10:45.035  3384  3855 D NetworkStatsRecorder: entry.iface is null
08-30 23:10:45.035  4309  4309 D CellLayoutHotseat: addItem : Wiadomości, 2
08-30 23:10:45.035  3384  3855 W System.err: rename failed: EROFS (Read-only file system) : /data/system/netstats/uid.1472201541317- -> /data/system/netstats/uid.1472201541317-.backup
08-30 23:10:45.035  4309  4309 D CellLayoutHotseat: addItem : Internet, 3
08-30 23:10:45.035  3384  3855 W System.err: remove failed: EROFS (Read-only file system) : /data/system/netstats/uid.1472201541317-
08-30 23:10:45.045  3384  3855 W System.err: rename failed: EROFS (Read-only file system) : /data/system/netstats/uid.1472201541317-.backup -> /data/system/netstats/uid.1472201541317-
08-30 23:10:45.045  3384  3855 E DropBoxManagerService: Can't write: netstats_dump
08-30 23:10:45.045  3384  3855 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop97.tmp: open failed: EROFS (Read-only file system)
08-30 23:10:45.045  3384  3855 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 23:10:45.045  3384  3855 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 23:10:45.045  3384  3855 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 23:10:45.045  3384  3855 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 23:10:45.045  3384  3855 E DropBoxManagerService: 	at android.os.DropBoxManager.addData(DropBoxManager.java:282)
08-30 23:10:45.045  3384  3855 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsRecorder.recoverFromWtf(NetworkStatsRecorder.java:500)
08-30 23:10:45.045  3384  3855 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsRecorder.forcePersistLocked(NetworkStatsRecorder.java:324)
08-30 23:10:45.045  3384  3855 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsRecorder.maybePersistLocked(NetworkStatsRecorder.java:306)
08-30 23:10:45.045  3384  3855 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService.performPollLocked(NetworkStatsService.java:1222)
08-30 23:10:45.045  3384  3855 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService.removeUidsLocked(NetworkStatsService.java:1288)
08-30 23:10:45.045  3384  3855 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService.access$1600(NetworkStatsService.java:151)
08-30 23:10:45.045  3384  3855 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService$5.onReceive(NetworkStatsService.java:883)
08-30 23:10:45.045  3384  3855 E DropBoxManagerService: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:993)
08-30 23:10:45.045  3384  3855 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 23:10:45.045  3384  3855 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 23:10:45.045  3384  3855 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:158)
08-30 23:10:45.045  3384  3855 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 23:10:45.045  3384  3855 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 23:10:45.045  3384  3855 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 23:10:45.045  3384  3855 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 23:10:45.045  3384  3855 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 23:10:45.045  3384  3855 E DropBoxManagerService: 	... 16 more
08-30 23:10:45.045  3384  3855 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/dropbox/drop97.tmp
08-30 23:10:45.045  3384  3855 W System.err: remove failed: EROFS (Read-only file system) : /data/system/netstats/uid.1472201541317-
,08-30 23:10:45.055  3384  3855 W System.err: rename failed: EROFS (Read-only file system) : /data/system/netstats/uid_tag.1472201541317- -> /data/system/netstats/uid_tag.1472201541317-.backup
,08-30 23:10:45.055  3384  3855 W System.err: remove failed: EROFS (Read-only file system) : /data/system/netstats/uid_tag.1472201541317-
,08-30 23:10:45.055  3384  3855 W System.err: rename failed: EROFS (Read-only file system) : /data/system/netstats/uid_tag.1472201541317-.backup -> /data/system/netstats/uid_tag.1472201541317-
08-30 23:10:45.055  4309  4309 D CellLayoutHotseat: reapplyIconViewStyles : 4
,08-30 23:10:45.055  4309  4309 D IconInfo: hotseatSizeChanged : 232, iconCount : 4
,08-30 23:10:45.055  3384  3855 E DropBoxManagerService: Can't write: netstats_dump
08-30 23:10:45.055  3384  3855 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop97.tmp: open failed: EROFS (Read-only file system)
08-30 23:10:45.055  3384  3855 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 23:10:45.055  3384  3855 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 23:10:45.055  3384  3855 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 23:10:45.055  3384  3855 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 23:10:45.055  3384  3855 E DropBoxManagerService: 	at android.os.DropBoxManager.addData(DropBoxManager.java:282)
08-30 23:10:45.055  3384  3855 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsRecorder.recoverFromWtf(NetworkStatsRecorder.java:500)
08-30 23:10:45.055  3384  3855 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsRecorder.forcePersistLocked(NetworkStatsRecorder.java:324)
08-30 23:10:45.055  3384  3855 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsRecorder.maybePersistLocked(NetworkStatsRecorder.java:306)
08-30 23:10:45.055  3384  3855 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService.performPollLocked(NetworkStatsService.java:1223)
08-30 23:10:45.055  3384  3855 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService.removeUidsLocked(NetworkStatsService.java:1288)
08-30 23:10:45.055  3384  3855 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService.access$1600(NetworkStatsService.java:151)
08-30 23:10:45.055  3384  3855 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService$5.onReceive(NetworkStatsService.java:883)
08-30 23:10:45.055  3384  3855 E DropBoxManagerService: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:993)
08-30 23:10:45.055  3384  3855 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 23:10:45.055  3384  3855 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 23:10:45.055  3384  3855 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:158)
08-30 23:10:45.055  3384  3855 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 23:10:45.055  3384  3855 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 23:10:45.055  3384  3855 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 23:10:45.055  3384  3855 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 23:10:45.055  3384  3855 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 23:10:45.055  3384  3855 E DropBoxManagerService: 	... 16 more
,08-30 23:10:45.055  3384  3855 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/dropbox/drop97.tmp
08-30 23:10:45.055  3384  3855 W System.err: remove failed: EROFS (Read-only file system) : /data/system/netstats/uid_tag.1472201541317-
08-30 23:10:45.055  3384  3855 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 23:10:45.055  3384  3855 V NetworkStats: performPollLocked() took 32ms
,08-30 23:10:45.055  6208  6208 I Utils   : isCurrentUser current = 0, ownerId = 0
,08-30 23:10:45.065  3384  4407 W ActivityManager: Permission Denial: Accessing service ComponentInfo{com.google.android.music/com.google.android.music.dial.DialMediaRouteProviderService} from pid=4904, uid=10130 that is not exported from uid 10128
08-30 23:10:45.055  6208  6208 I TrayVisibilityController: getComputedTrayVisible : keyguardState = 3
08-30 23:10:45.055  6208  6208 I TrayVisibilityController: updateTrayVisible : State : 3 visible = 2 mCurrentVisible = 2
08-30 23:10:45.065  4021  4021 I Recents_MultiWindowAppListInfo: android.intent.action.PACKAGE_REMOVE
08-30 23:10:45.065  3384  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/LiveBroadcast/LiveBroadcast.apk / 1.0 running in null rsrc of package com.sec.android.app.camera.plb
,08-30 23:10:45.065  9933  9933 D InjectionManager: InjectionManager
08-30 23:10:45.065  9933  9933 D InjectionManager: fillFeatureStoreMap com.sec.android.app.clockpackage
08-30 23:10:45.065  3384  3543 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-30 23:10:45.065  3384  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/LiveBroadcast/LiveBroadcast.apk / 1.0 running in null rsrc of package com.sec.android.app.camera.plb
,08-30 23:10:45.065  3384  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/LiveBroadcast/LiveBroadcast.apk / 1.0 running in null rsrc of package com.sec.android.app.camera.plb
,08-30 23:10:45.065  3384  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/SFinder_v4/SFinder_v4.apk / 1.0 running in null rsrc of package com.samsung.android.app.galaxyfinder
,08-30 23:10:45.065  3384  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCamera5/SamsungCamera5.apk / 1.0 running in null rsrc of package com.sec.android.app.camera
08-30 23:10:45.065  3384  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCamera5/SamsungCamera5.apk / 1.0 running in null rsrc of package com.sec.android.app.camera
,08-30 23:10:45.065  3384  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
,08-30 23:10:45.075  3384  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
,08-30 23:10:45.075  9933  9933 I InjectionManager: Constructor com.sec.android.app.clockpackage, Feature store :{}
,08-30 23:10:45.075  9933  9933 I InjectionManager: featureStore :{}
08-30 23:10:45.075  3384  3856 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 23:10:45.075  3384  3856 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 23:10:45.075  3384  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
08-30 23:10:45.075  4309  4309 D Launcher.Model: bindWorkspace:: Callback to Bind hotseat
08-30 23:10:45.075  3384  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
,08-30 23:10:45.085  3384  3543 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{fcd2f3 u0 com.sec.android.app.launcher/.activities.LauncherActivity t35} time:85101
08-30 23:10:45.085  3384  3880 D MdnieScenarioControlService:  packageName : com.sec.android.app.launcher    className : com.sec.android.app.launcher.activities.LauncherActivity
08-30 23:10:45.085  3384  3880 I MdnieScenarioControlService: mGameModeLauncher : false
,08-30 23:10:45.085  3384  3906 W System.err: remove failed: EROFS (Read-only file system) : /data/system/recent_tasks/37_task.xml
08-30 23:10:45.085  3384  3880 I MdnieScenarioControlService: setUIMode
08-30 23:10:45.085  3384  3543 D ActivityManager: mDVFSHelper.release()
08-30 23:10:45.085  3384  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,08-30 23:10:45.085  3384  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2015/SecGallery2015.apk / 1.0 running in null rsrc of package com.sec.android.gallery3d
,08-30 23:10:45.085  3384  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2015/SecGallery2015.apk / 1.0 running in null rsrc of package com.sec.android.gallery3d
,08-30 23:10:45.085  3384  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Epic_Common/SecMms_Epic_Common.apk / 1.0 running in null rsrc of package com.android.mms
,08-30 23:10:45.095  3384  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/VoiceNote_4.0/VoiceNote_4.0.apk / 1.0 running in null rsrc of package com.sec.android.app.voicenote
,08-30 23:10:45.095  3384  3505 W ResourcesManager: getTopLevelResources: /system/app/ClockPackage_M/ClockPackage_M.apk / 1.0 running in null rsrc of package com.sec.android.app.clockpackage
,08-30 23:10:45.105  3384  3505 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 23:10:45.105  3384  3505 W ResourcesManager: getTopLevelResources: /system/app/ClockPackage_M/ClockPackage_M.apk / 1.0 running in null rsrc of package com.sec.android.app.clockpackage
,08-30 23:10:45.105  3384  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
08-30 23:10:45.105  4285  9957 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.android.nfc rsrc of package com.sec.android.app.shealth
,08-30 23:10:45.105  4285  9957 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.android.nfc rsrc of package com.sec.android.app.shealth
08-30 23:10:45.105  4285  9957 W ResourcesManager: getTopLevelResources: /system/priv-app/Tag/Tag.apk / 1.0 running in com.android.nfc rsrc of package com.android.apps.tag
08-30 23:10:45.105  4285  9957 D RegisteredComponentCache: Collect Tech packages for Knox
08-30 23:10:45.105  4285  9957 W ResourcesManager: getTopLevelResources: /system/priv-app/Tag/Tag.apk / 1.0 running in com.android.nfc rsrc of package com.android.apps.tag
,08-30 23:10:45.105  3384  3505 W ResourcesManager: getTopLevelResources: /system/app/ClockPackage_M/ClockPackage_M.apk / 1.0 running in null rsrc of package com.sec.android.app.clockpackage

```
